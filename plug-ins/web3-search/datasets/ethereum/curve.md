# curve

## 1. Table: 3Crv\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-23 05:17:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17540150                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7bd7a6ee71ddc1d6210dd52056950de2149e9ce4624766c6a13efae85da71604 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 191                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6c3f90f043a72fa612cbac8115ee7e52bde6e490                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x92f3f71cef740ed5784874b8c70ff87ecdf33588                         |                                                              |
| \_spender         | VARCHAR   | 0xbebc44782c7db0a1a60cb6fe97d0b483032ff1c7                         |                                                              |
| \_value           | VARCHAR   | 0                                                                  |                                                              |

## 2. Table: 3Crv\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-21 00:39:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17738008                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x13677d37be8a0edf32fb6b2b5b48549940f3f65850d231d7998156d9159ce0ba | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 435                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6c3f90f043a72fa612cbac8115ee7e52bde6e490                         | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0x16f179f5c344cc29672a58ea327a26f64b941a63                         |                                                              |
| \_to              | VARCHAR   | 0x9e147216e2653ef342b20574b3f291a3ad801a19                         |                                                              |
| \_value           | VARCHAR   | 16323621149869982                                                  |                                                              |

## 3. Table: 3poolSwap\_call\_remove\_liquidity\_one\_coin\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-08-06 22:57:35+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17859038                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xf91975ee1ce479453790ea0988f32b16cca8f85287d64a8b60cfdd8b04b4d261 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 14                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xbebc44782c7db0a1a60cb6fe97d0b483032ff1c7                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_token\_amount    | VARCHAR   | 770645735410170376841                                              |                                                                                                                        |
| i                  | VARCHAR   | 0                                                                  |                                                                                                                        |
| min\_amount        | VARCHAR   | 790273565503727347350                                              |                                                                                                                        |

## 4. Table: 3poolSwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-15 14:42:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14010633                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3b8b8fd634ff2ef9dadc16f9176f1b99b140bd7a93d3c1f2084ab9eeb8902f7f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 211                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbebc44782c7db0a1a60cb6fe97d0b483032ff1c7                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x06cb22615ba53e60d67bf6c341a0fd5e718e1655                         |                                                              |
| token\_amounts    | VARCHAR   | 0,318584456163,0                                                   |                                                              |
| fees              | VARCHAR   | 11787879852937029112,23452863,11664344                             |                                                              |
| invariant         | VARCHAR   | 5784005073910023113814348335                                       |                                                              |
| token\_supply     | VARCHAR   | 5670674113243921291433799827                                       |                                                              |

## 5. Table: 3poolSwap\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-20 00:30:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11089752                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc7c98d20ae79e3907e69262eea57f034726074e57eb7c802a3e834df03d24ba5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 169                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbebc44782c7db0a1a60cb6fe97d0b483032ff1c7                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1603413000                                                         |                                                              |
| admin             | VARCHAR   | 0x56295b752e632f74a6526988eace33c25c52c623                         |                                                              |

## 6. Table: 3poolSwap\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-10 12:10:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14748483                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdc8085b553d1fab2d7d46c06ad8c3f918bb6f5f042465de4b6f91ece0f3da2c5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 387                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbebc44782c7db0a1a60cb6fe97d0b483032ff1c7                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1652443808                                                         |                                                              |
| fee               | VARCHAR   | 1000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 7. Table: 3poolSwap\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-30 17:49:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11361588                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xee31081171d817358085c7cd5df6f9f62f56f72b5ace388f765e46eeca50ecf2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 43                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbebc44782c7db0a1a60cb6fe97d0b483032ff1c7                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 8. Table: 3poolSwap\_event\_NewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-27 23:49:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10947641                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa0f18a420fb6da46de6c10fd1fdfad4ec13c4b8391c0f5d529141aec084fb6e7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 80                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbebc44782c7db0a1a60cb6fe97d0b483032ff1c7                         | Address of the contract that produced the log                |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 9. Table: 3poolSwap\_event\_RampA\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-26 10:01:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14847341                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x46a054105e5519c06ef81e18616aac06c454eb6235c802e22fae62a641863750 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1469                                                               | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbebc44782c7db0a1a60cb6fe97d0b483032ff1c7                         | Address of the contract that produced the log                |
| old\_A            | VARCHAR   | 5000                                                               |                                                              |
| new\_A            | VARCHAR   | 2000                                                               |                                                              |
| initial\_time     | VARCHAR   | 1653559305                                                         |                                                              |
| future\_time      | VARCHAR   | 1654158027                                                         |                                                              |

## 10. Table: 3poolSwap\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-03 01:46:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17831284                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4896db2bf455be8bc8404806cf7cc03882cb01fffc2c86e94cde58170c8381c0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 154                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbebc44782c7db0a1a60cb6fe97d0b483032ff1c7                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x8870898a85b03f030f1b893683c73015529838ad                         |                                                              |
| token\_amounts    | VARCHAR   | 4178967866043261042336,0,0                                         |                                                              |
| fees              | VARCHAR   | 122274198219579362,37199,85128                                     |                                                              |
| invariant         | VARCHAR   | 228088725464074241774828128                                        |                                                              |
| token\_supply     | VARCHAR   | 222150380888376346695610310                                        |                                                              |

## 11. Table: 3poolSwap\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-19 21:03:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17516335                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaa48dc51c397b2e5121f9498c669ea40383c0d7d852206e93238adfacd645900 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 189                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbebc44782c7db0a1a60cb6fe97d0b483032ff1c7                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x1033812efec8716bbae0c19e5678698d25e26edf                         |                                                              |
| token\_amount     | VARCHAR   | 9479205020173653330100                                             |                                                              |
| coin\_amount      | VARCHAR   | 9724792889679262689323                                             |                                                              |

## 12. Table: 3poolSwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-17 02:23:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15550310                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc3832b48c1eb1234cb5ee0f47d7b77ce310fe95a0187a541bddf30dfa48f5aaf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 211                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbebc44782c7db0a1a60cb6fe97d0b483032ff1c7                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xcb636b81743bb8a7f1e355debb7d33b07009cccc                         |                                                              |
| token\_amounts    | VARCHAR   | 81857210273090969508672,80778776526,80399793019                    |                                                              |
| fees              | VARCHAR   | 0,0,0                                                              |                                                              |
| token\_supply     | VARCHAR   | 752324124816105709497534721                                        |                                                              |

## 13. Table: 3poolSwap\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 14. Table: 3poolSwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-07 01:56:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12975089                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd0b5f7001592381517b242d1ec8e2a6cbbcb5be5010a92df9aa1d107feba90d1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 174                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbebc44782c7db0a1a60cb6fe97d0b483032ff1c7                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x0000000000007f150bd6f54c40a34d7c3d5e9f56                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 53666398240604489252864                                            |                                                              |
| bought\_id        | VARCHAR   | 2                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 53682441922                                                        |                                                              |

## 15. Table: AAVESwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-27 23:21:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13110394                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0b06cda5d9c94e82b9700dad16d3328ef2f2bf175591c6d30c2100c36f7307d7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 178                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdebf20617708857ebe4f679508e7b7863a8a8eee                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x14c9b684fe47df4d1b383cc431ea355fae7841dd                         |                                                              |
| token\_amounts    | VARCHAR   | 0,10002900000,0                                                    |                                                              |
| fees              | VARCHAR   | 312864384579633870,1437655,829953                                  |                                                              |
| invariant         | VARCHAR   | 174197830194291000088225503                                        |                                                              |
| token\_supply     | VARCHAR   | 163879704131977051795012099                                        |                                                              |

## 16. Table: AAVESwap\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-04 20:37:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11590215                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc83bbe39dafdd744b6e7e9fd6ad1c3f0dfde250862726310ead7280ef0551d5f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 169                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdebf20617708857ebe4f679508e7b7863a8a8eee                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1610051851                                                         |                                                              |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 17. Table: AAVESwap\_event\_CommitNewFee\_history

| Column                  | Type      | Example                                                      | Description |
| ----------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp        | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number           | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash       | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index              | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address       | VARCHAR   | Address of the contract that produced the log                |             |
| deadline                | VARCHAR   |                                                              |             |
| fee                     | VARCHAR   |                                                              |             |
| admin\_fee              | VARCHAR   |                                                              |             |
| offpeg\_fee\_multiplier | VARCHAR   |                                                              |             |

## 18. Table: AAVESwap\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-13 19:53:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11648704                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5323c105a4c3190be26f207cf9581c5c98001f4e7542eac7d083c55eddabad7b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 158                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdebf20617708857ebe4f679508e7b7863a8a8eee                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 19. Table: AAVESwap\_event\_NewFee\_history

| Column                  | Type      | Example                                                      | Description |
| ----------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp        | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number           | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash       | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index              | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address       | VARCHAR   | Address of the contract that produced the log                |             |
| fee                     | VARCHAR   |                                                              |             |
| admin\_fee              | VARCHAR   |                                                              |             |
| offpeg\_fee\_multiplier | VARCHAR   |                                                              |             |

## 20. Table: AAVESwap\_event\_RampA\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-02 17:00:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12947123                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x63cabda348223b1c6cf7110a803496aa9f5629ceb16f3b95a7c7948c4eb7c81b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 77                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdebf20617708857ebe4f679508e7b7863a8a8eee                         | Address of the contract that produced the log                |
| old\_A            | VARCHAR   | 20000                                                              |                                                              |
| new\_A            | VARCHAR   | 200000                                                             |                                                              |
| initial\_time     | VARCHAR   | 1627923611                                                         |                                                              |
| future\_time      | VARCHAR   | 1628525830                                                         |                                                              |

## 21. Table: AAVESwap\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-10 10:42:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13776911                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa12affe106ec6e567f148a0310870298beb951e25efb024203ab82fdfc7c0cf4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 129                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdebf20617708857ebe4f679508e7b7863a8a8eee                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x6cf9aa65ebad7028536e353393630e2340ca6049                         |                                                              |
| token\_amounts    | VARCHAR   | 0,2100000000000,0                                                  |                                                              |
| fees              | VARCHAR   | 140209153137784089147,371865549,94287281                           |                                                              |
| invariant         | VARCHAR   | 90417239263349000448373116                                         |                                                              |
| token\_supply     | VARCHAR   | 83792476727118290876617872                                         |                                                              |

## 22. Table: AAVESwap\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-14 08:54:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14582565                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x00e9b9eb6ef129fcc9a1479b0d86399166942e404857e88521922d639e738ef6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 341                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdebf20617708857ebe4f679508e7b7863a8a8eee                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x59daa74f2d15c87aac435ec18cb559f92490c100                         |                                                              |
| token\_amount     | VARCHAR   | 294828952484339131536                                              |                                                              |
| coin\_amount      | VARCHAR   | 320846538                                                          |                                                              |

## 23. Table: AAVESwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-23 01:27:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17539012                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1bb2adacfd68581b6af05ec6aec37c60b378955ac1598f0ecf20bfd122000c6b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 167                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdebf20617708857ebe4f679508e7b7863a8a8eee                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xfc9c46f98480acf1487e6a676b2da6e569f1f83e                         |                                                              |
| token\_amounts    | VARCHAR   | 122621598172538757034468,136051173188,172286953570                 |                                                              |
| fees              | VARCHAR   | 0,0,0                                                              |                                                              |
| token\_supply     | VARCHAR   | 19359764712553486395707764                                         |                                                              |

## 24. Table: AAVESwap\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 25. Table: AAVESwap\_event\_TokenExchangeUnderlying\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-15 00:07:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17695149                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8e3f7de6adf65d07501bd12cff8bd9f90cfdf8046e670e02395e486ebbaaee6b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 20                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdebf20617708857ebe4f679508e7b7863a8a8eee                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xda63a326d2c3c09586676a036e79af2e3c524090                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 241622776230000000000000                                           |                                                              |
| bought\_id        | VARCHAR   | 2                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 241490122498                                                       |                                                              |

## 26. Table: AAVESwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-21 19:30:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12285432                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x08e5f200d7004dd5da8f3d67eb65936299145c02cc0c770344792505ec938949 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 106                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdebf20617708857ebe4f679508e7b7863a8a8eee                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x561b94454b65614ae3db0897b74303f4acf7cc75                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 25000000000000000000000                                            |                                                              |
| bought\_id        | VARCHAR   | 2                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 24980553002                                                        |                                                              |

## 27. Table: BBTCSwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-13 03:41:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13605352                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf07258802d3e04fdfdb53695995bdc4ec76b4388645f9aeeae5bf014196eeeb1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 217                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x071c661b4deefb59e2a3ddb20db036821eee8f4b                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xc45b2eee6e09ca176ca3bb5f7eee7c47bf93c756                         |                                                              |
| token\_amounts    | VARCHAR   | 29899825000,0                                                      |                                                              |
| fees              | VARCHAR   | 3052941,30229272034678265                                          |                                                              |
| invariant         | VARCHAR   | 2988196109693584571299                                             |                                                              |
| token\_supply     | VARCHAR   | 2964608687471000321603                                             |                                                              |

## 28. Table: BBTCSwap\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| deadline          | VARCHAR   |                                                              |             |
| admin             | VARCHAR   |                                                              |             |

## 29. Table: BBTCSwap\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| deadline          | VARCHAR   |                                                              |             |
| fee               | VARCHAR   |                                                              |             |
| admin\_fee        | VARCHAR   |                                                              |             |

## 30. Table: BBTCSwap\_event\_NewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| admin             | VARCHAR   |                                                              |             |

## 31. Table: BBTCSwap\_event\_NewFee\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| fee               | VARCHAR   |                                                              |             |
| admin\_fee        | VARCHAR   |                                                              |             |

## 32. Table: BBTCSwap\_event\_RampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| old\_A            | VARCHAR   |                                                              |             |
| new\_A            | VARCHAR   |                                                              |             |
| initial\_time     | VARCHAR   |                                                              |             |
| future\_time      | VARCHAR   |                                                              |             |

## 33. Table: BBTCSwap\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-22 13:16:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12684223                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x20b91b9c19e1ae61a74e98e0a720141812e0498976705265445277659ffbe6f3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 178                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x071c661b4deefb59e2a3ddb20db036821eee8f4b                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xc45b2eee6e09ca176ca3bb5f7eee7c47bf93c756                         |                                                              |
| token\_amounts    | VARCHAR   | 0,3955859663688999303                                              |                                                              |
| fees              | VARCHAR   | 47859,473641944485451                                              |                                                              |
| invariant         | VARCHAR   | 2575506412187914189330                                             |                                                              |
| token\_supply     | VARCHAR   | 2559347038241459440225                                             |                                                              |

## 34. Table: BBTCSwap\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-14 01:11:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14580549                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb4badbb6c7f645af37c8977dfd71d2cc06e9814325595ffbe63602edd26f75ee | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 40                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x071c661b4deefb59e2a3ddb20db036821eee8f4b                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xc45b2eee6e09ca176ca3bb5f7eee7c47bf93c756                         |                                                              |
| token\_amount     | VARCHAR   | 136322835496928                                                    |                                                              |
| coin\_amount      | VARCHAR   | 136030742546971                                                    |                                                              |
| token\_supply     | VARCHAR   | 72936298669732969495                                               |                                                              |

## 35. Table: BBTCSwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-21 19:14:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12871592                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfb535ce2e2176dcb26d6451fdb0f3bc475d1413fb6ca65cb68ce75ef1805e338 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 216                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x071c661b4deefb59e2a3ddb20db036821eee8f4b                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xf96da4775776ea43c42795b116c7a6eccd6e71b5                         |                                                              |
| token\_amounts    | VARCHAR   | 2014192331,12294402260904450022                                    |                                                              |
| fees              | VARCHAR   | 0,0                                                                |                                                              |
| token\_supply     | VARCHAR   | 8907649489207901671799                                             |                                                              |

## 36. Table: BBTCSwap\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 37. Table: BBTCSwap\_event\_TokenExchangeUnderlying\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-27 08:35:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17349239                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x564aea8d0cb6f51fe66defbc2016649183ce3566ec8fda5bcb78588444977c75 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 272                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x071c661b4deefb59e2a3ddb20db036821eee8f4b                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xdef171fe48cf0115b1d80b88dc8eab59176fee57                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 7521060                                                            |                                                              |
| bought\_id        | VARCHAR   | 2                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 7502889                                                            |                                                              |

## 38. Table: BBTCSwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-15 08:59:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12638107                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x454d8c934b86cf775089ad76d8bee2b219adc5dcd7982b9b2961e1824adbc6e7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 90                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x071c661b4deefb59e2a3ddb20db036821eee8f4b                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x57196e30ba89c848147a19262a732191cbafaa37                         |                                                              |
| sold\_id          | VARCHAR   | 1                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 12879939262316326709                                               |                                                              |
| bought\_id        | VARCHAR   | 0                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 1301134230                                                         |                                                              |

## 39. Table: BUSDSwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-15 15:07:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11458350                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc20ce6575dc94e36a05406a3cc9afe8a5d372a246e39a43b4da1540e708ff10a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 44                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x79a8c46dea5ada233abaffd40f3a0a2b1e5a4f27                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x112570655b32a8c747845e0215ad139661e66e7f                         |                                                              |
| token\_amounts    | VARCHAR   | 5317503408741834306602,0,0,0                                       |                                                              |
| fees              | VARCHAR   | 613047881113493735,189675,227326,211541860503280798                |                                                              |
| invariant         | VARCHAR   | 64103188292325024135080885                                         |                                                              |
| token\_supply     | VARCHAR   | 60044900033605878077176977                                         |                                                              |

## 40. Table: BUSDSwap\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-20 00:30:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11089752                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc7c98d20ae79e3907e69262eea57f034726074e57eb7c802a3e834df03d24ba5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 151                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x79a8c46dea5ada233abaffd40f3a0a2b1e5a4f27                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1603413000                                                         |                                                              |
| admin             | VARCHAR   | 0x56295b752e632f74a6526988eace33c25c52c623                         |                                                              |

## 41. Table: BUSDSwap\_event\_CommitNewParameters\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-08 15:24:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9631544                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x981a6d6de182c905072f57acb4860ac52e516f9f0f0b76d98e0d6ab33781e994 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 155                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x79a8c46dea5ada233abaffd40f3a0a2b1e5a4f27                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1583940266                                                         |                                                              |
| A                 | VARCHAR   | 500                                                                |                                                              |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 0                                                                  |                                                              |

## 42. Table: BUSDSwap\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-30 17:49:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11361588                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7dbf058da28b26469d3ed8f8f32dd463df8afdd70ceab48b9a5f645d1a5e2a71 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 44                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x79a8c46dea5ada233abaffd40f3a0a2b1e5a4f27                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 43. Table: BUSDSwap\_event\_NewParameters\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-19 21:38:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10895154                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5665f967b7e8ce027c56677dbca8a8711275c179775539f7ba766effe043595b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 92                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x79a8c46dea5ada233abaffd40f3a0a2b1e5a4f27                         | Address of the contract that produced the log                |
| A                 | VARCHAR   | 500                                                                |                                                              |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 44. Table: BUSDSwap\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-22 17:23:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14056725                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfd2e95288d9dbd6e22b9a3633e8d3e3d588e6184085c80be8c742d437e773ac2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 280                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x79a8c46dea5ada233abaffd40f3a0a2b1e5a4f27                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xb6c057591e073249f2d9d88ba59a46cfc9b59edb                         |                                                              |
| token\_amounts    | VARCHAR   | 0,37242631111,0,0                                                  |                                                              |
| fees              | VARCHAR   | 1153002419196735528,3691058,1296864,1226282638820163513            |                                                              |
| invariant         | VARCHAR   | 20265910627702103392722853                                         |                                                              |
| token\_supply     | VARCHAR   | 17938272493385398198539657                                         |                                                              |

## 45. Table: BUSDSwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-21 00:45:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16673412                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdf6ca8dcb2eef760acce65440050670ecf6f42fae06c3886c316c342be9c755d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 215                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x79a8c46dea5ada233abaffd40f3a0a2b1e5a4f27                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xb6c057591e073249f2d9d88ba59a46cfc9b59edb                         |                                                              |
| token\_amounts    | VARCHAR   | 0,0,0,0                                                            |                                                              |
| fees              | VARCHAR   | 0,0,0,0                                                            |                                                              |
| token\_supply     | VARCHAR   | 5253715811054716657303955                                          |                                                              |

## 46. Table: BUSDSwap\_event\_TokenExchangeUnderlying\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-24 13:34:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11920131                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3e8828fb9df120b655b4aa4b0ddf51b92c5b23335d176acb23fdbb62e32d8c27 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 215                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x79a8c46dea5ada233abaffd40f3a0a2b1e5a4f27                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x22f9dcf4647084d6c31b2765f6910cd85c178c18                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 285847019843205714300329                                           |                                                              |
| bought\_id        | VARCHAR   | 1                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 286020022082                                                       |                                                              |

## 47. Table: BUSDSwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-14 16:34:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17479393                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2b0b9543d9f6fc85ba30a380c05fb8e1e59abcb49f9b401f9be847943655e768 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 245                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x79a8c46dea5ada233abaffd40f3a0a2b1e5a4f27                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x99a58482bd75cbab83b27ec03ca68ff489b5788f                         |                                                              |
| sold\_id          | VARCHAR   | 3                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 366673459301287750                                                 |                                                              |
| bought\_id        | VARCHAR   | 1                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 399728                                                             |                                                              |

## 48. Table: CompoundSwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-02-28 17:44:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9573578                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1565c2d13bc6d3eaf65c0993055f98388f5707bcccd535b43f7bec188cffa98d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 124                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa2b47e3d5c44877cca798226b7b8118f9bfb7a56                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xd133d1f0359dfeadf1fa7bb655e2e1c76be2f778                         |                                                              |
| token\_amounts    | VARCHAR   | 125750589,357151745                                                |                                                              |
| fees              | VARCHAR   | 24366,23562                                                        |                                                              |
| invariant         | VARCHAR   | 300443121020461010                                                 |                                                              |
| token\_supply     | VARCHAR   | 300386558965093062                                                 |                                                              |

## 49. Table: CompoundSwap\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-20 00:30:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11089752                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc7c98d20ae79e3907e69262eea57f034726074e57eb7c802a3e834df03d24ba5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 142                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa2b47e3d5c44877cca798226b7b8118f9bfb7a56                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1603413000                                                         |                                                              |
| admin             | VARCHAR   | 0x56295b752e632f74a6526988eace33c25c52c623                         |                                                              |

## 50. Table: CompoundSwap\_event\_CommitNewParameters\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-02 11:24:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9792308                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8518a3cb31b879daad7c272d1ad9f35f974c7e68d7913b1be452f5b0f872f5ab | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 77                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa2b47e3d5c44877cca798226b7b8118f9bfb7a56                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1586085893                                                         |                                                              |
| A                 | VARCHAR   | 450                                                                |                                                              |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 0                                                                  |                                                              |

## 51. Table: CompoundSwap\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-24 06:55:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10721560                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x62049a5cb0873b431fab94cd93ff443ab11cd56edcd0ec7d13a63e20a0a91f68 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 210                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa2b47e3d5c44877cca798226b7b8118f9bfb7a56                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0x6e8f6d1da6232d5e40b0b8758a0145d6c5123eb7                         |                                                              |

## 52. Table: CompoundSwap\_event\_NewParameters\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-06 19:01:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12973168                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8c695387da64c67688702d0a62cee73ef5f7d4eb0a92ce628e2001aac0a47c1a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 26                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa2b47e3d5c44877cca798226b7b8118f9bfb7a56                         | Address of the contract that produced the log                |
| A                 | VARCHAR   | 4500                                                               |                                                              |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 53. Table: CompoundSwap\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-04 05:44:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11586181                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd42d8737728c093546246e648e59e689181526ebe328b430279aad4c8d219d5f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 227                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa2b47e3d5c44877cca798226b7b8118f9bfb7a56                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xeb21209ae4c2c9ff2a86aca31e123764a3b6bc06                         |                                                              |
| token\_amounts    | VARCHAR   | 3672493619592246,0                                                 |                                                              |
| fees              | VARCHAR   | 501552259490,491057719949                                          |                                                              |
| invariant         | VARCHAR   | 67738516215093121451541491                                         |                                                              |
| token\_supply     | VARCHAR   | 64761533285569350730976000                                         |                                                              |

## 54. Table: CompoundSwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-15 23:48:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17702113                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x761872bd2bc97f403a772174d3a5c7a561af8647a819ed1836406e25fd1570fd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 287                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa2b47e3d5c44877cca798226b7b8118f9bfb7a56                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xeb21209ae4c2c9ff2a86aca31e123764a3b6bc06                         |                                                              |
| token\_amounts    | VARCHAR   | 3168010039970,6539124128947                                        |                                                              |
| fees              | VARCHAR   | 0,0                                                                |                                                              |
| token\_supply     | VARCHAR   | 5677856986030200517179460                                          |                                                              |

## 55. Table: CompoundSwap\_event\_TokenExchangeUnderlying\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-01 12:15:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17385894                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xebf33e54c911c0cbc7eb776dc653ca2db259239a4521ef9946d7159d377c5deb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 386                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa2b47e3d5c44877cca798226b7b8118f9bfb7a56                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xdef171fe48cf0115b1d80b88dc8eab59176fee57                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 1501859664000000000000                                             |                                                              |
| bought\_id        | VARCHAR   | 1                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 1501927512                                                         |                                                              |

## 56. Table: CompoundSwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-18 19:12:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10485278                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa511dd0cd4adf3ff3909adf625567ce5cbfbf72d3c936b16b9a9ff704a990378 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 20                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa2b47e3d5c44877cca798226b7b8118f9bfb7a56                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xfd4cb68718fcb254bc2d2f321ba6853f454e0bc7                         |                                                              |
| sold\_id          | VARCHAR   | 1                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 33603786350908                                                     |                                                              |
| bought\_id        | VARCHAR   | 0                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 34255577219600                                                     |                                                              |

## 57. Table: CryptoRegistry\_event\_PoolAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-11 22:42:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13987012                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8afa64d3d390770e6e53ed307a7e014f379ab150196477cd2d0bbf54495da1cc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 408                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8f942c20d02befc377d41445793068908e2250d0                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0xd51a44d3fae010294c616388b506acda1bfaae46                         |                                                              |

## 58. Table: CryptoRegistry\_event\_PoolRemoved\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| pool              | VARCHAR   |                                                              |             |

## 59. Table: CryptoSwapThreeAssets\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-19 23:06:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13838435                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x99c54574577398d451d23022775c80e1884ce3e8771a0e118942cde3f725bda2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 413                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd51a44d3fae010294c616388b506acda1bfaae46                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x3993d34e7e99abf6b6f367309975d1360222d446                         |                                                              |
| token\_amounts    | VARCHAR   | 0,0,880000000000000000                                             |                                                              |
| fee               | VARCHAR   | 950326391505056                                                    |                                                              |
| token\_supply     | VARCHAR   | 513808632868994898831260                                           |                                                              |

## 60. Table: CryptoSwapThreeAssets\_event\_CommitNewParameters\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2023-02-04 20:29:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 16557810                                                           | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0xfe94479623ca6a6adfba7ec2ac7e4a0df7748bccdba26092a66c0875d8fc302b | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 194                                                                | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0xd51a44d3fae010294c616388b506acda1bfaae46                         | Address of the contract that produced the log                |
| deadline               | VARCHAR   | 1675801763                                                         |                                                              |
| admin\_fee             | VARCHAR   | 5000000000                                                         |                                                              |
| mid\_fee               | VARCHAR   | 3000000                                                            |                                                              |
| out\_fee               | VARCHAR   | 30000000                                                           |                                                              |
| fee\_gamma             | VARCHAR   | 500000000000000                                                    |                                                              |
| allowed\_extra\_profit | VARCHAR   | 2000000000000                                                      |                                                              |
| adjustment\_step       | VARCHAR   | 490000000000000                                                    |                                                              |
| ma\_half\_time         | VARCHAR   | 600                                                                |                                                              |

## 61. Table: CryptoSwapThreeAssets\_event\_NewParameters\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2023-02-07 20:30:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 16579299                                                           | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0x1463b0c1d2c4626a763c60764855b4b9b30125eab9f427a72b6377949d5691fe | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 476                                                                | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0xd51a44d3fae010294c616388b506acda1bfaae46                         | Address of the contract that produced the log                |
| admin\_fee             | VARCHAR   | 5000000000                                                         |                                                              |
| mid\_fee               | VARCHAR   | 3000000                                                            |                                                              |
| out\_fee               | VARCHAR   | 30000000                                                           |                                                              |
| fee\_gamma             | VARCHAR   | 500000000000000                                                    |                                                              |
| allowed\_extra\_profit | VARCHAR   | 2000000000000                                                      |                                                              |
| adjustment\_step       | VARCHAR   | 490000000000000                                                    |                                                              |
| ma\_half\_time         | VARCHAR   | 600                                                                |                                                              |

## 62. Table: CryptoSwapThreeAssets\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-11 14:40:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17671026                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x32591accab9d4f58a11cff2eb04dbdfa1b9be3237a2f96e2d5400d2bac0e1a8f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 142                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd51a44d3fae010294c616388b506acda1bfaae46                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x2305cd8ce60085184e5eb79c51c374b1d590dfa2                         |                                                              |
| token\_amounts    | VARCHAR   | 31734328,103945,17064104872400024                                  |                                                              |
| token\_supply     | VARCHAR   | 116300738491345508749370                                           |                                                              |

## 63. Table: CryptoSwapTwoAssets\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-09 19:35:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17444777                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5fd960f5be3378f7293f467e55be7344f031777cb430e923ea3f89ffcdf89266 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 229                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6ec38b3228251a0c5d491faf66858e2e23d7728b                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xe27baebd7b14602de3797974db9f5f4f8dcb6679                         |                                                              |
| token\_amounts    | VARCHAR   | 0,524573170464889891                                               |                                                              |
| fee               | VARCHAR   | 7211717630175302                                                   |                                                              |
| token\_supply     | VARCHAR   | 159990021783918594890                                              |                                                              |

## 64. Table: CryptoSwapTwoAssets\_event\_CommitNewParameters\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2023-07-13 19:39:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 17686710                                                           | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0x4ee8130900c5d9c25865511f16092b291618fcc28b48d7e489d3c57b524abb90 | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 215                                                                | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0x9838eccc42659fa8aa7daf2ad134b53984c9427b                         | Address of the contract that produced the log                |
| deadline               | VARCHAR   | 1689536351                                                         |                                                              |
| admin\_fee             | VARCHAR   | 5000000000                                                         |                                                              |
| mid\_fee               | VARCHAR   | 3000000                                                            |                                                              |
| out\_fee               | VARCHAR   | 45000000                                                           |                                                              |
| fee\_gamma             | VARCHAR   | 5000000000                                                         |                                                              |
| allowed\_extra\_profit | VARCHAR   | 10000000000                                                        |                                                              |
| adjustment\_step       | VARCHAR   | 300000000000000                                                    |                                                              |
| ma\_half\_time         | VARCHAR   | 2000                                                               |                                                              |

## 65. Table: CryptoSwapTwoAssets\_event\_NewParameters\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2021-11-20 11:54:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 13651732                                                           | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0xef0c50d40c7a00b8f02481dc4b6a1a0fadce0c8317f29d06341c152eb66e6e3d | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 228                                                                | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0x98a7f18d4e56cfe84e3d081b40001b3d5bd3eb8b                         | Address of the contract that produced the log                |
| admin\_fee             | VARCHAR   | 5000000000                                                         |                                                              |
| mid\_fee               | VARCHAR   | 5000000                                                            |                                                              |
| out\_fee               | VARCHAR   | 45000000                                                           |                                                              |
| fee\_gamma             | VARCHAR   | 5000000000000000                                                   |                                                              |
| allowed\_extra\_profit | VARCHAR   | 10000000000                                                        |                                                              |
| adjustment\_step       | VARCHAR   | 300000000000000                                                    |                                                              |
| ma\_half\_time         | VARCHAR   | 2000                                                               |                                                              |

## 66. Table: CryptoSwapTwoAssets\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-01 18:16:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16735490                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7255b5736be8df20e91da021b4408c34eeedb5c3cc63edbcdf9322ac59c4a136 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 178                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x838af967537350d2c44abb8c010e49e32673ab94                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xb2d0016d9baf8c053539871de0b302c5a6a15b09                         |                                                              |
| token\_amounts    | VARCHAR   | 17219636318069537786,2499817925291547638155                        |                                                              |
| token\_supply     | VARCHAR   | 31218210732257700144583                                            |                                                              |

## 67. Table: CryptoSwap\_call\_exchange\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-03-07 19:43:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16778572                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x9d942642bb0e129290c105994e2def5bc44fb644558a2234164bff38c776eda5 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 77                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 1,0,2                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x838af967537350d2c44abb8c010e49e32673ab94                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| i                  | VARCHAR   | 0                                                                  |                                                                                                                        |
| j                  | VARCHAR   | 1                                                                  |                                                                                                                        |
| dx                 | VARCHAR   | 1648448029216592239                                                |                                                                                                                        |
| min\_dy            | VARCHAR   | 340564257916035225072                                              |                                                                                                                        |
| use\_eth           | VARCHAR   | false                                                              |                                                                                                                        |
| receiver           | VARCHAR   | 0x1111111254eeb25477b68fb85ed929f73a960582                         |                                                                                                                        |

## 68. Table: CryptoSwap\_call\_exchangeextended\_history

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
| i                  | VARCHAR   |                                                                                                                        |             |
| j                  | VARCHAR   |                                                                                                                        |             |
| dx                 | VARCHAR   |                                                                                                                        |             |
| min\_dy            | VARCHAR   |                                                                                                                        |             |
| use\_eth           | VARCHAR   |                                                                                                                        |             |
| sender             | VARCHAR   |                                                                                                                        |             |
| receiver           | VARCHAR   |                                                                                                                        |             |
| cb                 | VARCHAR   |                                                                                                                        |             |

## 69. Table: CryptoSwap\_call\_exchangeunderlying\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-06-09 19:29:11+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17444745                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xdfa4f3cbdc5c8f01c2fca9effa128515f99374c4c3537d29ade2e5351e4dfd3d | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 10                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 1                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xfb8814d005c5f32874391e888da6eb2fe7a27902                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| i                  | VARCHAR   | 0                                                                  |                                                                                                                        |
| j                  | VARCHAR   | 1                                                                  |                                                                                                                        |
| dx                 | VARCHAR   | 2051140370000000000                                                |                                                                                                                        |
| min\_dy            | VARCHAR   | 0                                                                  |                                                                                                                        |
| receiver           | VARCHAR   | 0x0000000000a84d1a9b0063a910315c7ffa9cd248                         |                                                                                                                        |

## 70. Table: CryptoSwap\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-10 21:53:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17666051                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9bd00efe8ebdacd4ea23e4d73718d8cfd4487700c47178772b47d5af15042c68 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 306                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8301ae4fc9c624d1d396cbdaa1ed877821d7c511                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xc0403fdad54f0ae24c4c30cb589f7ecead227567                         |                                                              |
| token\_amount     | VARCHAR   | 20722809133115916679                                               |                                                              |
| coin\_index       | VARCHAR   | 0                                                                  |                                                              |
| coin\_amount      | VARCHAR   | 898589548862276683                                                 |                                                              |

## 71. Table: CryptoSwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-25 11:28:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16904184                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa4726a3c85b5862ec291f4977d02d3d69793e90fa2f987a0b24b434184b3b21e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 12                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd51a44d3fae010294c616388b506acda1bfaae46                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x00000000003b3cc22af3ae1eac0440bcee416b40                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 77407303319                                                        |                                                              |
| bought\_id        | VARCHAR   | 2                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 44390024668378498426                                               |                                                              |

## 72. Table: CurveExchangeAdapter2\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-25 20:41:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10337179                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x50c34f0619d506af85625fdb293ba6c5ecc0559574efde6ba179ee27b4a4fa74 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 39                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x26d9980571e77ffb0349f9c801dd7ca9951fb656                         | Address of the contract that produced the log                |
| burnAmount        | VARCHAR   | 497089334                                                          |                                                              |

## 73. Table: CurveExchangeAdapter2\_event\_DepositMintedCurve\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-28 13:02:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10354413                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x282d727341e3abae8b11e4a17c2e607178d656e96dec87b7d86ecded78181d61 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 92                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x26d9980571e77ffb0349f9c801dd7ca9951fb656                         | Address of the contract that produced the log                |
| mintedAmount      | VARCHAR   | 544455                                                             |                                                              |
| curveAmount       | VARCHAR   | 5402688051550936                                                   |                                                              |

## 74. Table: CurveExchangeAdapter2\_event\_ReceiveRen\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| renAmount         | VARCHAR   |                                                              |             |

## 75. Table: CurveExchangeAdapter2\_event\_SwapReceived\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-29 17:55:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10362186                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x18fb83020b35f5ca9c2a54b395535347c4f5de29cee909c593905f8f879edcbe | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 96                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x26d9980571e77ffb0349f9c801dd7ca9951fb656                         | Address of the contract that produced the log                |
| mintedAmount      | VARCHAR   | 64935                                                              |                                                              |
| wbtcAmount        | VARCHAR   | 64609                                                              |                                                              |

## 76. Table: CurveExchangeAdapter3\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-13 14:03:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11848687                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x09b3205ed634219d87b4417e8f72b4ddc7212e681de88b307eda362d05a64fae | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 40                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73ab2bd10ad10f7174a1ad5afae3ce3d991c5047                         | Address of the contract that produced the log                |
| burnAmount        | VARCHAR   | 124426314                                                          |                                                              |

## 77. Table: CurveExchangeAdapter3\_event\_DepositMintedCurve\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-22 22:27:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10914964                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xca0b1ef110eb84c816bd5811facad8bde6d7f31950a18a62f652747bbfea5905 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 98                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73ab2bd10ad10f7174a1ad5afae3ce3d991c5047                         | Address of the contract that produced the log                |
| mintedAmount      | VARCHAR   | 99998878                                                           |                                                              |
| curveAmount       | VARCHAR   | 984861327487056833                                                 |                                                              |

## 78. Table: CurveExchangeAdapter3\_event\_MetaTransactionExecuted\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-01 00:04:45+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10370299                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc3ab5961157c8141b0ae0ac75fc45b11014c4257bc165a19545ac2bdb40088fd                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 37                                                                                                   | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73ab2bd10ad10f7174a1ad5afae3ce3d991c5047                                                           | Address of the contract that produced the log                |
| userAddress       | VARCHAR   | 0xbf7d65d769e82e7b862df338223263ba33f72623                                                           |                                                              |
| relayerAddress    | VARCHAR   | 0x6436b8efadcf9de6fba945f7ca9955565a51d2db                                                           |                                                              |
| functionSignature | VARCHAR   | 0xdcf0bb3a000000000000000000000000bf7d65d769e82e7b862df338223263ba33f7262300000000000000000000000000 |                                                              |

## 79. Table: CurveExchangeAdapter3\_event\_ReceiveRen\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-12 18:41:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11641850                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa0a967f74d71ad000d295bf0c0e40d79914c230bc054d7a6fe392268acd5aadd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 320                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73ab2bd10ad10f7174a1ad5afae3ce3d991c5047                         | Address of the contract that produced the log                |
| renAmount         | VARCHAR   | 10532850                                                           |                                                              |

## 80. Table: CurveExchangeAdapter3\_event\_SwapReceived\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-13 05:16:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11247399                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x54ee77e768f0c1706db776d62611a6dacbd201314db4319be6de9f1d3bd2a41d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 198                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73ab2bd10ad10f7174a1ad5afae3ce3d991c5047                         | Address of the contract that produced the log                |
| mintedAmount      | VARCHAR   | 199500200                                                          |                                                              |
| wbtcAmount        | VARCHAR   | 198904334                                                          |                                                              |

## 81. Table: CurveExchangeAdapterSBTC\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-27 09:38:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13498663                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x760da9aeb34daf1510f3d8431422d045428f46f718ef7366dde32719cd8ca49b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 292                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xaeade605d01fe9a8e9c4b3aa0130a90d62167029                         | Address of the contract that produced the log                |
| burnAmount        | VARCHAR   | 3770817                                                            |                                                              |

## 82. Table: CurveExchangeAdapterSBTC\_event\_DepositMintedCurve\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-18 03:17:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13247241                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x49068d4a66ed408d82380878664a7f18e73a034befb0f6b0666381caaba2cea1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 428                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xaeade605d01fe9a8e9c4b3aa0130a90d62167029                         | Address of the contract that produced the log                |
| mintedAmount      | VARCHAR   | 4985310                                                            |                                                              |
| curveAmount       | VARCHAR   | 49347256475844175                                                  |                                                              |
| amounts           | VARCHAR   | 4985310,0,0                                                        |                                                              |

## 83. Table: CurveExchangeAdapterSBTC\_event\_MetaTransactionExecuted\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-28 03:31:31+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10545578                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcc2ca67a0183df282b3d2f88d4e452956b627c410fe43fad4758efdee4209e86                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 190                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xaeade605d01fe9a8e9c4b3aa0130a90d62167029                                                           | Address of the contract that produced the log                |
| userAddress       | VARCHAR   | 0x5640239fdae101ad42f03973e6ef545104fdbe6d                                                           |                                                              |
| relayerAddress    | VARCHAR   | 0x4455d7d6a8f35aa84e64703ee8bf3fb838014f70                                                           |                                                              |
| functionSignature | VARCHAR   | 0xa318f9de0000000000000000000000005640239fdae101ad42f03973e6ef545104fdbe6d00000000000000000000000000 |                                                              |

## 84. Table: CurveExchangeAdapterSBTC\_event\_ReceiveRen\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-17 11:33:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10879433                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb6bd53dd730de5e94fda21979b8278808c3d1280ab0b0d339425d09d1086b686 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 76                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xaeade605d01fe9a8e9c4b3aa0130a90d62167029                         | Address of the contract that produced the log                |
| renAmount         | VARCHAR   | 299630070                                                          |                                                              |

## 85. Table: CurveExchangeAdapterSBTC\_event\_SwapReceived\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-26 01:22:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11728369                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9fa3a87502d978cf7fdaeae4432ce658ca41fd59b24e9ca168f69eb5a5f853e2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 57                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xaeade605d01fe9a8e9c4b3aa0130a90d62167029                         | Address of the contract that produced the log                |
| mintedAmount      | VARCHAR   | 49775250                                                           |                                                              |
| erc20BTCAmount    | VARCHAR   | 49673983                                                           |                                                              |
| j                 | VARCHAR   | 1                                                                  |                                                              |

## 86. Table: CurveExchangeAdapter\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-21 02:07:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10902988                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x791d9d4e57d6fb6e714b9ab3156104815edb5dd5cb33caa947c8d724137eb1a8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 207                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9fe350dfa5f66bc086243f21a8f0932514316627                         | Address of the contract that produced the log                |
| burnAmount        | VARCHAR   | 100122914                                                          |                                                              |

## 87. Table: CurveExchangeAdapter\_event\_DepositMintedCurve\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-21 19:30:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10310992                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x90d8f1f17f75e0da6c13822e4041d389b911b96fc34f2c1f4fb03f301f34a1cf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 166                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9fe350dfa5f66bc086243f21a8f0932514316627                         | Address of the contract that produced the log                |
| mintedAmount      | VARCHAR   | 1283715                                                            |                                                              |
| curveAmount       | VARCHAR   | 12764114845722470                                                  |                                                              |

## 88. Table: CurveExchangeAdapter\_event\_ReceiveRen\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-06 17:06:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10809267                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdf9abb449a902beb79d988964d246ce106812eb95da99b58061982c3bebba399 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 150                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9fe350dfa5f66bc086243f21a8f0932514316627                         | Address of the contract that produced the log                |
| renAmount         | VARCHAR   | 929070                                                             |                                                              |

## 89. Table: CurveExchangeAdapter\_event\_RelayHubChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldRelayHub       | VARCHAR   |                                                              |             |
| newRelayHub       | VARCHAR   |                                                              |             |

## 90. Table: CurveExchangeAdapter\_event\_SwapReceived\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-16 15:20:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10873901                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb742578c0b98ba321986bee658dfa7f769996dad4e783551d90389eb25b6fb63 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 148                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9fe350dfa5f66bc086243f21a8f0932514316627                         | Address of the contract that produced the log                |
| mintedAmount      | VARCHAR   | 1132796070                                                         |                                                              |
| wbtcAmount        | VARCHAR   | 1132341442                                                         |                                                              |

## 91. Table: DUSDSwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-11 05:21:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11833348                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x444ddc55a9ffa3c2825e9c902cb1bab33c4b4d002267c9667c8d18150665b214 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 321                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8038c01a0390a8c547446a0b2c18fc9aefecc10c                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x61e10659fe3aa93d036d099405224e4ac24996d0                         |                                                              |
| token\_amounts    | VARCHAR   | 88087418649905051942,0                                             |                                                              |
| fees              | VARCHAR   | 6679424241974559,6573446587289340                                  |                                                              |
| invariant         | VARCHAR   | 6536768955973240963628784                                          |                                                              |
| token\_supply     | VARCHAR   | 6488802452776579811833978                                          |                                                              |

## 92. Table: DUSDSwap\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-27 01:32:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11337591                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x458b70dad200640e747b08fe8c952ec11bb1efcaca0b32fa0955a6fec8b7339e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 111                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8038c01a0390a8c547446a0b2c18fc9aefecc10c                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1606699951                                                         |                                                              |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 93. Table: DUSDSwap\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-27 01:27:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11337570                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8c2dae6134ce78bb75297bcfc226b5b6d5c81920eddbc25e84f180995061c08f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 274                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8038c01a0390a8c547446a0b2c18fc9aefecc10c                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1606699661                                                         |                                                              |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 94. Table: DUSDSwap\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-30 18:29:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11361740                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x551f74b74692da936f3767853e0ec5b79148ea739ebe0115b33e2478407ba25b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 186                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8038c01a0390a8c547446a0b2c18fc9aefecc10c                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 95. Table: DUSDSwap\_event\_NewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-30 04:41:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11357964                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x178bf3a691e85f27e75bc0728ebb2dd2283209bb704c51c0cb4387e7d4d3e851 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 315                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8038c01a0390a8c547446a0b2c18fc9aefecc10c                         | Address of the contract that produced the log                |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 96. Table: DUSDSwap\_event\_RampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| old\_A            | VARCHAR   |                                                              |             |
| new\_A            | VARCHAR   |                                                              |             |
| initial\_time     | VARCHAR   |                                                              |             |
| future\_time      | VARCHAR   |                                                              |             |

## 97. Table: DUSDSwap\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-20 01:57:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12860636                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x70356cd83a43919011d86158524059599c543ab592b6caabdc84010cb213e57a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 34                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8038c01a0390a8c547446a0b2c18fc9aefecc10c                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x61e10659fe3aa93d036d099405224e4ac24996d0                         |                                                              |
| token\_amounts    | VARCHAR   | 0,255536288290173395263768                                         |                                                              |
| fees              | VARCHAR   | 30663683099979938602,30061292618369670395                          |                                                              |
| invariant         | VARCHAR   | 47342641743181673897916977                                         |                                                              |
| token\_supply     | VARCHAR   | 46811783923186591635581938                                         |                                                              |

## 98. Table: DUSDSwap\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-08 10:24:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12393100                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x476ca86cc5f1ffd361e88b1704d61b1c1fc388e1765916733f59d5f9a41aca0b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 206                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8038c01a0390a8c547446a0b2c18fc9aefecc10c                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x61e10659fe3aa93d036d099405224e4ac24996d0                         |                                                              |
| token\_amount     | VARCHAR   | 314565505552230496619590                                           |                                                              |
| coin\_amount      | VARCHAR   | 312683230444062135096969                                           |                                                              |
| token\_supply     | VARCHAR   | 16104307852559053319741392                                         |                                                              |

## 99. Table: DUSDSwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-26 16:36:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11335133                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1d6707360cb6aa2ea018decb80dfafb69574af01a5b122a531a857c2acc307b9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 59                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8038c01a0390a8c547446a0b2c18fc9aefecc10c                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x61e10659fe3aa93d036d099405224e4ac24996d0                         |                                                              |
| token\_amounts    | VARCHAR   | 33044991068234135005168,28767984599254179337893                    |                                                              |
| fees              | VARCHAR   | 0,0                                                                |                                                              |
| token\_supply     | VARCHAR   | 10916682108439543571287028                                         |                                                              |

## 100. Table: DUSDSwap\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 101. Table: DUSDSwap\_event\_TokenExchangeUnderlying\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-19 22:50:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14618353                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1a4be636696ed2452e785eb0064349f573110da412d52047d94efa1699af0273 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 14                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8038c01a0390a8c547446a0b2c18fc9aefecc10c                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x45716d9eddbc332df1d42b9f540fbebed671b20f                         |                                                              |
| sold\_id          | VARCHAR   | 2                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 1074895941                                                         |                                                              |
| bought\_id        | VARCHAR   | 0                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 1140498641565961710960                                             |                                                              |

## 102. Table: DUSDSwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-09 00:40:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17652659                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc3a962c6c021262ead5868a3cbc5365d390cb449f13ad7bac7bd0ffc86f17877 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 275                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8038c01a0390a8c547446a0b2c18fc9aefecc10c                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xe4000004000bd8006e00720000d27d1fa000d43e                         |                                                              |
| sold\_id          | VARCHAR   | 1                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 74998417987455037800                                               |                                                              |
| bought\_id        | VARCHAR   | 0                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 77344006483813237951                                               |                                                              |

## 103. Table: EURSSwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-20 21:27:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13265074                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7fabe56f27333af49757a4d3ad1becb4f9bb8fcfe89dac3dad23da7ed4445c3c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 219                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0ce6a5ff5217e38315f87032cf90686c96627caa                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x77fcb2c2c7ea27f97a47bd9641677d297382a8a9                         |                                                              |
| token\_amounts    | VARCHAR   | 103265,0                                                           |                                                              |
| fees              | VARCHAR   | 5,53827138259650814                                                |                                                              |
| invariant         | VARCHAR   | 67900349495061040583628910                                         |                                                              |
| token\_supply     | VARCHAR   | 67723886337824799019762082                                         |                                                              |

## 104. Table: EURSSwap\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| deadline          | VARCHAR   |                                                              |             |
| admin             | VARCHAR   |                                                              |             |

## 105. Table: EURSSwap\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| deadline          | VARCHAR   |                                                              |             |
| fee               | VARCHAR   |                                                              |             |
| admin\_fee        | VARCHAR   |                                                              |             |

## 106. Table: EURSSwap\_event\_NewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| admin             | VARCHAR   |                                                              |             |

## 107. Table: EURSSwap\_event\_NewFee\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| fee               | VARCHAR   |                                                              |             |
| admin\_fee        | VARCHAR   |                                                              |             |

## 108. Table: EURSSwap\_event\_RampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| old\_A            | VARCHAR   |                                                              |             |
| new\_A            | VARCHAR   |                                                              |             |
| initial\_time     | VARCHAR   |                                                              |             |
| future\_time      | VARCHAR   |                                                              |             |

## 109. Table: EURSSwap\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-28 22:18:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11948478                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2d284dbf7e5fccbaa670355f72d2c63b040ff4ea98d9cbe40378b11e9a00249d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 47                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0ce6a5ff5217e38315f87032cf90686c96627caa                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x678783721b49a5d079f4aadf12c91049ebf7b3c1                         |                                                              |
| token\_amounts    | VARCHAR   | 0,332804180000000000000000                                         |                                                              |
| fees              | VARCHAR   | 3348,33475540986773128818                                          |                                                              |
| invariant         | VARCHAR   | 55762749606339924330409964                                         |                                                              |
| token\_supply     | VARCHAR   | 55672031113251493268482206                                         |                                                              |

## 110. Table: EURSSwap\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-06 06:18:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17854081                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8bf682b3f5e256c8dad1901fad56cc0855dbeceee4338551cdeb036bd99a187f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 226                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0ce6a5ff5217e38315f87032cf90686c96627caa                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x4d0abbde0cb30d828a90cfff33d40b966473825f                         |                                                              |
| token\_amount     | VARCHAR   | 3563961195496114047377                                             |                                                              |
| coin\_amount      | VARCHAR   | 3577966615300473042322                                             |                                                              |
| token\_supply     | VARCHAR   | 2449269541650506657319156                                          |                                                              |

## 111. Table: EURSSwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-22 02:58:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12873675                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5b02e2a1d5e956b93cdc73d513bce357667070980ac3ed65cd1ff7af3efec71a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 223                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0ce6a5ff5217e38315f87032cf90686c96627caa                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x551db350ee9adaa9b43335f1d464f0abdaa9bb24                         |                                                              |
| token\_amounts    | VARCHAR   | 36439,616790870356227688981                                        |                                                              |
| fees              | VARCHAR   | 0,0                                                                |                                                              |
| token\_supply     | VARCHAR   | 182774509444466306844139992                                        |                                                              |

## 112. Table: EURSSwap\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 113. Table: EURSSwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-26 19:15:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11531159                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3049f4a8cd5328933daee55b8af2393ef1ebe5d1e708e476389a78b00dba0722 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 230                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0ce6a5ff5217e38315f87032cf90686c96627caa                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xcbba4fb07d4a86267741cf1a2c363284eed00f0f                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 2462911                                                            |                                                              |
| bought\_id        | VARCHAR   | 1                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 24790753942471599148139                                            |                                                              |

## 114. Table: FactoryCryptoSwap\_event\_CryptoPoolDeployed\_history

| Column                 | Type      | Example                                                                               | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2023-08-02 09:08:23+00:00                                                             | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 17826320                                                                              | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0x98e7a6b5abb835a0451d328c7c0f710c161b4b73f23b7fb2dd88ec7c9919e89f                    | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 155                                                                                   | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0xf18056bbd320e96a48e3fbf8bc061322531aac99                                            | Address of the contract that produced the log                |
| token                  | VARCHAR   | 0x4e731427ffe035e34112c695952771a2d9d9c870                                            |                                                              |
| coins                  | VARCHAR   | 0x13Cc8D626445c6fcCC548aAE172CBACF572EF5A4,0x9220f3eff6F4a32Ebcd414198c52da86D78DcCEb |                                                              |
| A                      | VARCHAR   | 400000                                                                                |                                                              |
| gamma                  | VARCHAR   | 145000000000000                                                                       |                                                              |
| mid\_fee               | VARCHAR   | 26000000                                                                              |                                                              |
| out\_fee               | VARCHAR   | 45000000                                                                              |                                                              |
| allowed\_extra\_profit | VARCHAR   | 2000000000000                                                                         |                                                              |
| fee\_gamma             | VARCHAR   | 230000000000000                                                                       |                                                              |
| adjustment\_step       | VARCHAR   | 146000000000000                                                                       |                                                              |
| admin\_fee             | VARCHAR   | 5000000000                                                                            |                                                              |
| ma\_half\_time         | VARCHAR   | 600                                                                                   |                                                              |
| initial\_price         | VARCHAR   | 29600000000000000000000                                                               |                                                              |
| deployer               | VARCHAR   | 0xbf0cbf718dc6d70663a29dfa00681bfd90228500                                            |                                                              |

## 115. Table: FactoryCryptoSwap\_event\_LiquidityGaugeDeployed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-07 08:04:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17427194                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6d9c789dda85884eef180a7aa074db60c5a1c727afa55332ddce7f2670cf90ec | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 66                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf18056bbd320e96a48e3fbf8bc061322531aac99                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0xb0973f4fb4e1280d6bddba5b18ae00576a6e78f4                         |                                                              |
| token             | VARCHAR   | 0xd531a9e82e468042c78c737a3e450ec87b829c8b                         |                                                              |
| gauge             | VARCHAR   | 0xd6dbe11d0a07bc554e732aa7ce30f40ea19a9075                         |                                                              |

## 116. Table: FactoryCryptoSwap\_event\_TransferOwnership\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-29 15:04:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15434799                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd55243741b6f8cd1c91139977e50cf5c46ee4f4db24b350e74489ff1dcec8226 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 304                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf18056bbd320e96a48e3fbf8bc061322531aac99                         | Address of the contract that produced the log                |
| \_old\_owner      | VARCHAR   | 0xbabe61887f1de2713c6f97e567623453d3c79f67                         |                                                              |
| \_new\_owner      | VARCHAR   | 0x5a8fdc979ba9b6179916404414f7ba4d8b77c8a1                         |                                                              |

## 117. Table: FactoryCryptoSwap\_event\_UpdateFeeReceiver\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2022-01-14 18:46:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 14005321                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x9ec3da07b975d0d149b9fd44d33c5b6dc29ee2bc80db32f5d337fc6ecf53c897 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 180                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0xf18056bbd320e96a48e3fbf8bc061322531aac99                         | Address of the contract that produced the log                |
| \_old\_fee\_receiver | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_new\_fee\_receiver | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 118. Table: FactoryCryptoSwap\_event\_UpdateGaugeImplementation\_history

| Column                       | Type      | Example                                                            | Description                                                  |
| ---------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp             | TIMESTAMP | 2022-01-14 18:46:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number                | INTEGER   | 14005321                                                           | The block number where this event was emitted                |
| transaction\_hash            | VARCHAR   | 0x9ec3da07b975d0d149b9fd44d33c5b6dc29ee2bc80db32f5d337fc6ecf53c897 | Hash of the transactions in which this event was emitted     |
| log\_index                   | INTEGER   | 183                                                                | Integer of the log index position in the block of this event |
| contract\_address            | VARCHAR   | 0xf18056bbd320e96a48e3fbf8bc061322531aac99                         | Address of the contract that produced the log                |
| \_old\_gauge\_implementation | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_new\_gauge\_implementation | VARCHAR   | 0xdc892358d55d5ae1ec47a531130d62151eba36e5                         |                                                              |

## 119. Table: FactoryCryptoSwap\_event\_UpdatePoolImplementation\_history

| Column                      | Type      | Example                                                            | Description                                                  |
| --------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp            | TIMESTAMP | 2022-01-14 18:46:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number               | INTEGER   | 14005321                                                           | The block number where this event was emitted                |
| transaction\_hash           | VARCHAR   | 0x9ec3da07b975d0d149b9fd44d33c5b6dc29ee2bc80db32f5d337fc6ecf53c897 | Hash of the transactions in which this event was emitted     |
| log\_index                  | INTEGER   | 181                                                                | Integer of the log index position in the block of this event |
| contract\_address           | VARCHAR   | 0xf18056bbd320e96a48e3fbf8bc061322531aac99                         | Address of the contract that produced the log                |
| \_old\_pool\_implementation | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_new\_pool\_implementation | VARCHAR   | 0xa85461afc2deec01bda23b5cd267d51f765fba10                         |                                                              |

## 120. Table: FactoryCryptoSwap\_event\_UpdateTokenImplementation\_history

| Column                       | Type      | Example                                                            | Description                                                  |
| ---------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp             | TIMESTAMP | 2022-01-14 18:46:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number                | INTEGER   | 14005321                                                           | The block number where this event was emitted                |
| transaction\_hash            | VARCHAR   | 0x9ec3da07b975d0d149b9fd44d33c5b6dc29ee2bc80db32f5d337fc6ecf53c897 | Hash of the transactions in which this event was emitted     |
| log\_index                   | INTEGER   | 182                                                                | Integer of the log index position in the block of this event |
| contract\_address            | VARCHAR   | 0xf18056bbd320e96a48e3fbf8bc061322531aac99                         | Address of the contract that produced the log                |
| \_old\_token\_implementation | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_new\_token\_implementation | VARCHAR   | 0xc08550a4cc5333f40e593ecc4c4724808085d304                         |                                                              |

## 121. Table: FactoryStableSwap\_event\_BasePoolAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-10 05:10:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16152126                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x450d6bc7c6cd2dc593b4a1d45012a2f5589f536b970faa82a5eeeb9d05bb0036 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 199                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb9fc157394af804a3578134a6585c0dc9cc990d4                         | Address of the contract that produced the log                |
| base\_pool        | VARCHAR   | 0xf253f83aca21aabd2a20553ae0bf7f65c755a07f                         |                                                              |

## 122. Table: FactoryStableSwap\_event\_LiquidityGaugeDeployed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-14 15:05:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13224553                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xea6ed7eb2ba25e274d90eadfeea20f40b190101aebd0a2c4bcc47dc7a4ce58dc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 506                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb9fc157394af804a3578134a6585c0dc9cc990d4                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0x4e52cfc80679f402d10f7766fa3f85351a7c2530                         |                                                              |
| gauge             | VARCHAR   | 0x517616c02c4286daa20e5841cad084039f2062fc                         |                                                              |

## 123. Table: FactoryStableSwap\_event\_MetaPoolDeployed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-24 19:23:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13679040                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x104be1de9d7e7a415544933a24ad24f46dad7b2de849eac097ba20d5dc7ab1fc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 156                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb9fc157394af804a3578134a6585c0dc9cc990d4                         | Address of the contract that produced the log                |
| coin              | VARCHAR   | 0x573d2505a7ee69d136a8667b4cd915f039ac54e5                         |                                                              |
| base\_pool        | VARCHAR   | 0xbebc44782c7db0a1a60cb6fe97d0b483032ff1c7                         |                                                              |
| A                 | VARCHAR   | 100                                                                |                                                              |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| deployer          | VARCHAR   | 0x8acbc4a734f494935fec9d03b975f5b9a5b9c8ca                         |                                                              |

## 124. Table: FactoryStableSwap\_event\_PlainPoolDeployed\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-29 18:41:37+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14482785                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9868762a164781398295c896488101209a23398bb39c5525d41318b5383823dc                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 388                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb9fc157394af804a3578134a6585c0dc9cc990d4                                                           | Address of the contract that produced the log                |
| coins             | VARCHAR   | 0xFe2e637202056d30016725477c5da089Ab0A043A,0xae7ab96520DE3A18E5e111B5EaAb095312D7fE84,0x000000000000 |                                                              |
| A                 | VARCHAR   | 50                                                                                                   |                                                              |
| fee               | VARCHAR   | 4000000                                                                                              |                                                              |
| deployer          | VARCHAR   | 0x61b01a33aea3e827b3941ab097778bd3fa48a332                                                           |                                                              |

## 125. Table: IronBankSwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-26 03:51:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13098645                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x18afc39fc04533675bab6150ec911dace0800f3d0fabe451a988e1203c686e6a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 28                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2dded6da1bf5dbdf597c45fcfaa3194e53ecfeaf                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xf0aaba6bb8e6bae83ea984bc4b7dcf0ff54a8fef                         |                                                              |
| token\_amounts    | VARCHAR   | 365708060924079,0,0                                                |                                                              |
| fees              | VARCHAR   | 67170719692,42947934086,24998415109                                |                                                              |
| invariant         | VARCHAR   | 328895979532169777618640123                                        |                                                              |
| token\_supply     | VARCHAR   | 319843827791611019548363803                                        |                                                              |

## 126. Table: IronBankSwap\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-10 21:24:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11831189                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2a0fd302945326048d4ef6395b2e1684d0fb821480aec25e3e56ab7ea8cc21b1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 280                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2dded6da1bf5dbdf597c45fcfaa3194e53ecfeaf                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1613251489                                                         |                                                              |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 127. Table: IronBankSwap\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-02 17:00:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12947123                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x63cabda348223b1c6cf7110a803496aa9f5629ceb16f3b95a7c7948c4eb7c81b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 68                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2dded6da1bf5dbdf597c45fcfaa3194e53ecfeaf                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1628182811                                                         |                                                              |
| fee               | VARCHAR   | 6000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 128. Table: IronBankSwap\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-03 16:45:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11966483                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcb4d3e7ce97bd0d80b9dfdc47321db5bb238da2e2f366b3d918c4983b5a764af | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 150                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2dded6da1bf5dbdf597c45fcfaa3194e53ecfeaf                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 129. Table: IronBankSwap\_event\_NewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-06 18:55:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12973135                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x54a7e977b0e1fb0f58e4f32227e63accaba08384a8ffb8ed09e672a3816cdf84 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 517                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2dded6da1bf5dbdf597c45fcfaa3194e53ecfeaf                         | Address of the contract that produced the log                |
| fee               | VARCHAR   | 6000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 130. Table: IronBankSwap\_event\_RampA\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-02 17:00:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12947123                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x63cabda348223b1c6cf7110a803496aa9f5629ceb16f3b95a7c7948c4eb7c81b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 71                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2dded6da1bf5dbdf597c45fcfaa3194e53ecfeaf                         | Address of the contract that produced the log                |
| old\_A            | VARCHAR   | 60000                                                              |                                                              |
| new\_A            | VARCHAR   | 600000                                                             |                                                              |
| initial\_time     | VARCHAR   | 1627923611                                                         |                                                              |
| future\_time      | VARCHAR   | 1628525830                                                         |                                                              |

## 131. Table: IronBankSwap\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-23 05:20:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12488651                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x281feebfdadf1c2b4f835e220ed661bd803e8c2d5e2507f23175b8308e3ea5d7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 30                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2dded6da1bf5dbdf597c45fcfaa3194e53ecfeaf                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x72dbb36793cbfc871ec3bca152ac345147d9dd0d                         |                                                              |
| token\_amounts    | VARCHAR   | 0,974651929028072,0                                                |                                                              |
| fees              | VARCHAR   | 36683320961,78628820090,41745787137                                |                                                              |
| invariant         | VARCHAR   | 305553810636807446913215823                                        |                                                              |
| token\_supply     | VARCHAR   | 300117168770319608629144111                                        |                                                              |

## 132. Table: IronBankSwap\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-04 06:28:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16109660                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x06ee75c39eea5bb93e678500f04252d3ac9ea71fffc3e9b0af1736834c8a9b40 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 29                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2dded6da1bf5dbdf597c45fcfaa3194e53ecfeaf                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x7ab92ce66c975c9e2dabbb9c682a794eb0a7425b                         |                                                              |
| token\_amount     | VARCHAR   | 101886845606106140063                                              |                                                              |
| coin\_amount      | VARCHAR   | 1015545945846                                                      |                                                              |

## 133. Table: IronBankSwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-02 21:56:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12357310                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xefa7086fc416f65bc92f7b66eb1aa833c0be5b39cf0c790b6f0501f118183551 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 234                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2dded6da1bf5dbdf597c45fcfaa3194e53ecfeaf                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x4e78e70469f617abcf3fa97a88b3ec9626e8f692                         |                                                              |
| token\_amounts    | VARCHAR   | 154888767015946,270866521269645,203175728454736                    |                                                              |
| fees              | VARCHAR   | 0,0,0                                                              |                                                              |
| token\_supply     | VARCHAR   | 244532803580840017151323062                                        |                                                              |

## 134. Table: IronBankSwap\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 135. Table: IronBankSwap\_event\_TokenExchangeUnderlying\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-23 22:16:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17545182                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3b73cd440bd497cd86ceb24b548d2efabd1f25102175eb8fe2478efdcbcb93d8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 43                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2dded6da1bf5dbdf597c45fcfaa3194e53ecfeaf                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x80d4230c0a68fc59cb264329d3a717fcaa472a13                         |                                                              |
| sold\_id          | VARCHAR   | 1                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 271347972819                                                       |                                                              |
| bought\_id        | VARCHAR   | 2                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 271298792910                                                       |                                                              |

## 136. Table: IronBankSwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-15 09:11:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17484315                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x62531f7711609a26c2331386dd181866e894ce10f0abeb18b1b0d5735abe7cb8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 53                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2dded6da1bf5dbdf597c45fcfaa3194e53ecfeaf                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x7d32c90762e22379235fc311fdb16fab399ed40a                         |                                                              |
| sold\_id          | VARCHAR   | 1                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 433202542252356                                                    |                                                              |
| bought\_id        | VARCHAR   | 2                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 408223569397113                                                    |                                                              |

## 137. Table: LDOETH\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-28 21:48:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17794327                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1f12a5d39dc856c8d6d5eed8a392367be34c6bf4516241034117e762c4fc8a36 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 29                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9409280dc1e6d33ab7a8c6ec03e5763fb61772b5                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xebe9f4059ff0d5cc2dce85b95d03bf8aaf96446b                         |                                                              |
| token\_amounts    | VARCHAR   | 126246983315319868,0                                               |                                                              |
| fee               | VARCHAR   | 3742148217182698                                                   |                                                              |
| token\_supply     | VARCHAR   | 177513136417966633747639                                           |                                                              |

## 138. Table: LDOETH\_event\_ClaimAdminFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-17 15:59:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16649466                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1073ebbbf13d887c6cd7e32bd0d82033425124ff0648dc9ad3632a552dea65fe | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9409280dc1e6d33ab7a8c6ec03e5763fb61772b5                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |
| tokens            | VARCHAR   | 188421333603073402                                                 |                                                              |

## 139. Table: LDOETH\_event\_CommitNewParameters\_history

| Column                 | Type      | Example                                                      | Description |
| ---------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp       | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number          | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash      | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index             | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address      | VARCHAR   | Address of the contract that produced the log                |             |
| deadline               | VARCHAR   |                                                              |             |
| admin\_fee             | VARCHAR   |                                                              |             |
| mid\_fee               | VARCHAR   |                                                              |             |
| out\_fee               | VARCHAR   |                                                              |             |
| fee\_gamma             | VARCHAR   |                                                              |             |
| allowed\_extra\_profit | VARCHAR   |                                                              |             |
| adjustment\_step       | VARCHAR   |                                                              |             |
| ma\_half\_time         | VARCHAR   |                                                              |             |

## 140. Table: LDOETH\_event\_NewParameters\_history

| Column                 | Type      | Example                                                      | Description |
| ---------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp       | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number          | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash      | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index             | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address      | VARCHAR   | Address of the contract that produced the log                |             |
| admin\_fee             | VARCHAR   |                                                              |             |
| mid\_fee               | VARCHAR   |                                                              |             |
| out\_fee               | VARCHAR   |                                                              |             |
| fee\_gamma             | VARCHAR   |                                                              |             |
| allowed\_extra\_profit | VARCHAR   |                                                              |             |
| adjustment\_step       | VARCHAR   |                                                              |             |
| ma\_half\_time         | VARCHAR   |                                                              |             |

## 141. Table: LDOETH\_event\_RampAgamma\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| initial\_A        | VARCHAR   |                                                              |             |
| future\_A         | VARCHAR   |                                                              |             |
| initial\_gamma    | VARCHAR   |                                                              |             |
| future\_gamma     | VARCHAR   |                                                              |             |
| initial\_time     | VARCHAR   |                                                              |             |
| future\_time      | VARCHAR   |                                                              |             |

## 142. Table: LDOETH\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-05 14:20:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16983130                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x29937b4eb3054a0c6a153ee1b8b69e825b8d3c295ceb3a0aa522f8dbec92987c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 119                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9409280dc1e6d33ab7a8c6ec03e5763fb61772b5                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xc0b338da0fdd43dc48539837594cf6363795feea                         |                                                              |
| token\_amount     | VARCHAR   | 78558310112785747622                                               |                                                              |
| coin\_index       | VARCHAR   | 0                                                                  |                                                              |
| coin\_amount      | VARCHAR   | 5904392635848887461                                                |                                                              |

## 143. Table: LDOETH\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-15 03:14:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17049706                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3885aa5e2b1e5baaaa90244a27985b40e94902caac11e8751b850b584278e3e6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 22                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9409280dc1e6d33ab7a8c6ec03e5763fb61772b5                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x3eefca588c985b096f793fabf14bb395a475a330                         |                                                              |
| token\_amounts    | VARCHAR   | 405664706804058893089,321459762426667935878775                     |                                                              |
| token\_supply     | VARCHAR   | 242294750653630809402984                                           |                                                              |

## 144. Table: LDOETH\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| current\_A        | VARCHAR   |                                                              |             |
| current\_gamma    | VARCHAR   |                                                              |             |
| time              | VARCHAR   |                                                              |             |

## 145. Table: LDOETH\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-25 21:30:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16486529                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2a7eec84f89355baeecea34eb15f1bf59bba7ca15ab6c9111571c44b1dc3c76c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 125                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9409280dc1e6d33ab7a8c6ec03e5763fb61772b5                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x0000000000007f150bd6f54c40a34d7c3d5e9f56                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 11128771170000001024                                               |                                                              |
| bought\_id        | VARCHAR   | 1                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 7016219506458291905265                                             |                                                              |

## 146. Table: LinkUSDSwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-21 22:20:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11102165                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1eb1d2e010e1ad40d6275eef73c61aaffc421fbfe23d076b3930bc41efe84c83 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 163                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe7a24ef0c5e95ffb0f6684b813a78f2a3ad7d171                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xf6bdc2619ffda72c537cd9605e0a274dc48cb1c9                         |                                                              |
| token\_amounts    | VARCHAR   | 1000000000000000000000,993785509509820220299                       |                                                              |
| fees              | VARCHAR   | 42092961784559777,41151501513291046                                |                                                              |
| invariant         | VARCHAR   | 324668583572265880548057                                           |                                                              |
| token\_supply     | VARCHAR   | 324256337282038722045653                                           |                                                              |

## 147. Table: LinkUSDSwap\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-18 19:05:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11081727                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x03161c0591a3165905f183d7e1bbaecaec4023e0eaaef3cd6a92371f1e7fa7ca | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 127                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe7a24ef0c5e95ffb0f6684b813a78f2a3ad7d171                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1603307101                                                         |                                                              |
| admin             | VARCHAR   | 0x3f4232107ff437bcd7ea9abc134ad553efeddaff                         |                                                              |

## 148. Table: LinkUSDSwap\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-18 19:04:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11081725                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7cf480ae558cfcf76aa54d01cd235578a297667d0aaf65ddbc12264cc7b35700 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 215                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe7a24ef0c5e95ffb0f6684b813a78f2a3ad7d171                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1603307075                                                         |                                                              |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 149. Table: LinkUSDSwap\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-24 23:50:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11122193                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8f27e8611f0fed6b1b32ea4bc6297de7bbc941533f813b0baeed6e1f5961964c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 148                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe7a24ef0c5e95ffb0f6684b813a78f2a3ad7d171                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0x3f4232107ff437bcd7ea9abc134ad553efeddaff                         |                                                              |

## 150. Table: LinkUSDSwap\_event\_NewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-24 23:53:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11122204                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3fa5bdfdfb8762fab4e1c363fc99e4db90755a95f541ac7173d9151e865d77b7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 35                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe7a24ef0c5e95ffb0f6684b813a78f2a3ad7d171                         | Address of the contract that produced the log                |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 151. Table: LinkUSDSwap\_event\_RampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| old\_A            | VARCHAR   |                                                              |             |
| new\_A            | VARCHAR   |                                                              |             |
| initial\_time     | VARCHAR   |                                                              |             |
| future\_time      | VARCHAR   |                                                              |             |

## 152. Table: LinkUSDSwap\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-19 11:54:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11483500                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc19cfee784afa5522ce9b97cedf900586a4db9cefcfb8e403e502c48737b84c8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 77                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe7a24ef0c5e95ffb0f6684b813a78f2a3ad7d171                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x1de7f0866e2c4adac7b457c58cc25c8688cda1f2                         |                                                              |
| token\_amounts    | VARCHAR   | 800000000000000000000,795354020310293150208                        |                                                              |
| fees              | VARCHAR   | 13509657766315797,13062901335819457                                |                                                              |
| invariant         | VARCHAR   | 237161358029287863279701                                           |                                                              |
| token\_supply     | VARCHAR   | 236647338459592454287194                                           |                                                              |

## 153. Table: LinkUSDSwap\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-06 15:10:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11601764                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x142fda4c9a9a46f0fae7a3821016e615dddf2b0b01d214affe108cc66159dae5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 74                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe7a24ef0c5e95ffb0f6684b813a78f2a3ad7d171                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x1de7f0866e2c4adac7b457c58cc25c8688cda1f2                         |                                                              |
| token\_amount     | VARCHAR   | 1055222803043655889188                                             |                                                              |
| coin\_amount      | VARCHAR   | 1082222737867882485097                                             |                                                              |
| token\_supply     | VARCHAR   | 154052646413255996930714                                           |                                                              |

## 154. Table: LinkUSDSwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-22 14:03:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11503715                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x82399f19372a11febce4842e5dfedc41cec80b23def0ebbac04e8c6a6a3a9363 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 284                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe7a24ef0c5e95ffb0f6684b813a78f2a3ad7d171                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xcac59f91e4536bc0e79ab816a5cd54e89f10433c                         |                                                              |
| token\_amounts    | VARCHAR   | 1114623892861067313182,906685224373036718027                       |                                                              |
| fees              | VARCHAR   | 0,0                                                                |                                                              |
| token\_supply     | VARCHAR   | 231349469261072230975890                                           |                                                              |

## 155. Table: LinkUSDSwap\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 156. Table: LinkUSDSwap\_event\_TokenExchangeUnderlying\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-18 21:57:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12065235                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xebb1b1de0d83e5f4a1d28a39812a71cf7b5ce6462c7d07b98c97c579117dc655 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 272                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe7a24ef0c5e95ffb0f6684b813a78f2a3ad7d171                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xb33b9e6a11b8fc5b576123dde191ee4ac011ecdd                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 839053094936290469520                                              |                                                              |
| bought\_id        | VARCHAR   | 3                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 926543947                                                          |                                                              |

## 157. Table: LinkUSDSwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-30 06:34:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11755712                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcf1b278978dc42fe5ea5a0c96afaad40b2851d193685adfc95e114c3a1c3448f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 145                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe7a24ef0c5e95ffb0f6684b813a78f2a3ad7d171                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xf6b25a5dcb117e524c8c7355af90886286e9f33d                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 50925567028087510262                                               |                                                              |
| bought\_id        | VARCHAR   | 1                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 52286391435802676296                                               |                                                              |

## 158. Table: MUSDSwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-11 12:22:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11633596                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3260e334da025b03bc2e289c28b41825adcb723aebd850f9a4f49d96e2c80d68 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 222                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8474ddbe98f5aa3179b3b3f5942d724afcdec9f6                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xb258ad4125e84068f3a47fbbc4f6aced2bc148ec                         |                                                              |
| token\_amounts    | VARCHAR   | 10000000000000000000,5000000000000000000                           |                                                              |
| fees              | VARCHAR   | 222576722079530,220590616512158                                    |                                                              |
| invariant         | VARCHAR   | 5521721538856531880946160                                          |                                                              |
| token\_supply     | VARCHAR   | 5493454177639873920528280                                          |                                                              |

## 159. Table: MUSDSwap\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-27 13:37:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11340846                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2496882c3dfa545785a06252337f90ae917aadc0a6e99c804ef6d7bc3c0a5c8d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 166                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8474ddbe98f5aa3179b3b3f5942d724afcdec9f6                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1606743476                                                         |                                                              |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 160. Table: MUSDSwap\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-18 19:05:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11081731                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x45ce9fe2623e6c34cdc071f96673d42e648dd3f18a9865a9afcccb340cfbc363 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 149                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8474ddbe98f5aa3179b3b3f5942d724afcdec9f6                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1603307135                                                         |                                                              |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 161. Table: MUSDSwap\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-30 17:59:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11361625                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa5ec68a30833ea7a9ebc4def400370f0cd05303657a63a8f697a4e4f1e62cfb4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 215                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8474ddbe98f5aa3179b3b3f5942d724afcdec9f6                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 162. Table: MUSDSwap\_event\_NewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-24 23:53:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11122204                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3fa5bdfdfb8762fab4e1c363fc99e4db90755a95f541ac7173d9151e865d77b7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 36                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8474ddbe98f5aa3179b3b3f5942d724afcdec9f6                         | Address of the contract that produced the log                |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 163. Table: MUSDSwap\_event\_RampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| old\_A            | VARCHAR   |                                                              |             |
| new\_A            | VARCHAR   |                                                              |             |
| initial\_time     | VARCHAR   |                                                              |             |
| future\_time      | VARCHAR   |                                                              |             |

## 164. Table: MUSDSwap\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-07 08:36:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11404626                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x53a1aa1a24fdf8390e85f4b36d0c253c2037749feec0ef0c3b2f18c1971c7ba9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 156                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8474ddbe98f5aa3179b3b3f5942d724afcdec9f6                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x803a2b40c5a9bb2b86dd630b274fa2a9202874c2                         |                                                              |
| token\_amounts    | VARCHAR   | 0,994035102767182493712                                            |                                                              |
| fees              | VARCHAR   | 123605589182823977,122636210101168505                              |                                                              |
| invariant         | VARCHAR   | 3791003753183806785637364                                          |                                                              |
| token\_supply     | VARCHAR   | 3776776305550088907137854                                          |                                                              |

## 165. Table: MUSDSwap\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-09 14:04:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14353025                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x82e5353eedcd61279c1afa2c10ba8d61965287f25db47d2a06194b1cbe699d82 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 128                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8474ddbe98f5aa3179b3b3f5942d724afcdec9f6                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x4d5b5376cbcc001bb4f8930208828ab87d121da8                         |                                                              |
| token\_amount     | VARCHAR   | 631449720443608586705162                                           |                                                              |
| coin\_amount      | VARCHAR   | 628667834782821227920341                                           |                                                              |
| token\_supply     | VARCHAR   | 68891675530988963078615506                                         |                                                              |

## 166. Table: MUSDSwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-19 23:16:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11890298                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x28a01898f43d0241b4480c6408b115ec9ba0f65e50f4f3d81a897fd407dd1421 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 39                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8474ddbe98f5aa3179b3b3f5942d724afcdec9f6                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x803a2b40c5a9bb2b86dd630b274fa2a9202874c2                         |                                                              |
| token\_amounts    | VARCHAR   | 21862619444712593560617,18237378086210803608377                    |                                                              |
| fees              | VARCHAR   | 0,0                                                                |                                                              |
| token\_supply     | VARCHAR   | 10935891708378032727597470                                         |                                                              |

## 167. Table: MUSDSwap\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 168. Table: MUSDSwap\_event\_TokenExchangeUnderlying\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-12 04:24:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14568586                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1b94a2530f50f9197b62e79fe4346e0eb9981eee47be54452d807d6139aef9ba | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 66                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8474ddbe98f5aa3179b3b3f5942d724afcdec9f6                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x45716d9eddbc332df1d42b9f540fbebed671b20f                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 340761455882552013161                                              |                                                              |
| bought\_id        | VARCHAR   | 1                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 340444185753177390560                                              |                                                              |

## 169. Table: MUSDSwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-28 21:20:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12331313                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbbaeaabc0114871b3c706583a292f998244c8537c2f7e21787e39365a874e996 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 298                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8474ddbe98f5aa3179b3b3f5942d724afcdec9f6                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x2393c368c70b42f055a4932a3fbec2ac9c548011                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 29198133529923061377                                               |                                                              |
| bought\_id        | VARCHAR   | 1                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 28760422979422768905                                               |                                                              |

## 170. Table: MainRegistry\_event\_PoolAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-02 21:14:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14700596                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2bf8774b45101bfb0b93e32f88855b0817dcc09e3544843b7dd7ebeaa7fe7fd8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 293                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x90e00ace148ca3b23ac1bc8c240c2a7dd9c2d7f5                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0x4e0915c88bc70750d68c481540f081fefaf22273                         |                                                              |
| rate\_method\_id  | VARCHAR   | 0x00000000                                                         |                                                              |

## 171. Table: MainRegistry\_event\_PoolRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-10 21:36:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13393346                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe59a6c7ecae4e11cff91326347406e301e775999a98d6ee3d396e4e6cb20784f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 57                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x90e00ace148ca3b23ac1bc8c240c2a7dd9c2d7f5                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0xfd5db7463a3ab53fd211b4af195c5bccc1a03890                         |                                                              |

## 172. Table: PAXSwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-23 05:47:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11110757                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe1b0cbb82db94c841fc69dbe04acd50713094b024eea2ceb26713fd9f08d7c18 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 145                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x06364f10b501e868329afbc005b3492902d6c763                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xa50ccc70b6a011cffddf45057e39679379187287                         |                                                              |
| token\_amounts    | VARCHAR   | 0,0,99417175,0                                                     |                                                              |
| fees              | VARCHAR   | 1622815151932767,3865,9973,4489307359821979                        |                                                              |
| invariant         | VARCHAR   | 3101174501280852229336237                                          |                                                              |
| token\_supply     | VARCHAR   | 3030540187699262505910240                                          |                                                              |

## 173. Table: PAXSwap\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-20 00:30:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11089752                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc7c98d20ae79e3907e69262eea57f034726074e57eb7c802a3e834df03d24ba5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 157                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x06364f10b501e868329afbc005b3492902d6c763                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1603413000                                                         |                                                              |
| admin             | VARCHAR   | 0x56295b752e632f74a6526988eace33c25c52c623                         |                                                              |

## 174. Table: PAXSwap\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-16 19:48:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10875110                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd86f34e988709d22067837467fdb039917967feca9a0959cd3d0e6dd3f823cbc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 223                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x06364f10b501e868329afbc005b3492902d6c763                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1600544926                                                         |                                                              |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 175. Table: PAXSwap\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-30 17:59:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11361629                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe354a43fc18a138cbb5e65a4b2daa108ac160532148eb874b9b75d23d336c78e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 55                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x06364f10b501e868329afbc005b3492902d6c763                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 176. Table: PAXSwap\_event\_NewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-19 21:38:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10895154                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5665f967b7e8ce027c56677dbca8a8711275c179775539f7ba766effe043595b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 94                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x06364f10b501e868329afbc005b3492902d6c763                         | Address of the contract that produced the log                |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 177. Table: PAXSwap\_event\_RampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| old\_A            | VARCHAR   |                                                              |             |
| new\_A            | VARCHAR   |                                                              |             |
| initial\_time     | VARCHAR   |                                                              |             |
| future\_time      | VARCHAR   |                                                              |             |

## 178. Table: PAXSwap\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-09 08:58:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12003375                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf387b0bb6f2ded2dafc1961ddc7fb62c84319a58edb04f85f16b2d33e19380ef | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 95                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x06364f10b501e868329afbc005b3492902d6c763                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xa50ccc70b6a011cffddf45057e39679379187287                         |                                                              |
| token\_amounts    | VARCHAR   | 0,100895830690,0,0                                                 |                                                              |
| fees              | VARCHAR   | 2997317107005262499,10248931,3112842,4217388660006406320           |                                                              |
| invariant         | VARCHAR   | 7103709484948231681630661                                          |                                                              |
| token\_supply     | VARCHAR   | 6887884907074287810989370                                          |                                                              |

## 179. Table: PAXSwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-27 05:55:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11136807                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb2fdc94fb8515915cf30137d0cf32d7c086324b286cbe8bfe2bf703260612cc3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 194                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x06364f10b501e868329afbc005b3492902d6c763                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xa50ccc70b6a011cffddf45057e39679379187287                         |                                                              |
| token\_amounts    | VARCHAR   | 430151199248034619597,1141463016,1025602749,1238276985417819164042 |                                                              |
| fees              | VARCHAR   | 0,0,0,0                                                            |                                                              |
| token\_supply     | VARCHAR   | 2982222887386219863122805                                          |                                                              |

## 180. Table: PAXSwap\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 181. Table: PAXSwap\_event\_TokenExchangeUnderlying\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-16 22:40:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10875886                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xae4274616bc0f70716976e31e190202be76176358b6c3677fe7357ba84555d5f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 130                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x06364f10b501e868329afbc005b3492902d6c763                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x728bbe9bbee3af78ad611315076621865950b344                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 700000000000000000000                                              |                                                              |
| bought\_id        | VARCHAR   | 2                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 709960302                                                          |                                                              |

## 182. Table: PAXSwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-21 14:30:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17528639                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfa6db7600c5816fa850d2f614907787aafaa3978351e2bc5c57f29a26883637e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x06364f10b501e868329afbc005b3492902d6c763                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xe8c060f8052e07423f71d445277c61ac5138a2e5                         |                                                              |
| sold\_id          | VARCHAR   | 3                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 1104482161502746110719                                             |                                                              |
| bought\_id        | VARCHAR   | 1                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 1060069281                                                         |                                                              |

## 183. Table: PegSwapFourAssets\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-28 10:33:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17790986                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x70eaee403cabd4faac99f3fc866172d638ae9bcb8f7705bce7586727509d393d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 91                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa5407eae9ba41422680e2e00537571bcc53efbfd                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x084240d5ce3f28ad8697e0fcf379bccfa6f33987                         |                                                              |
| token\_amounts    | VARCHAR   | 0,64400312,0,0                                                     |                                                              |
| fees              | VARCHAR   | 1094026977247922,3225,1126,1005126740589622                        |                                                              |
| invariant         | VARCHAR   | 30772377039929335902317976                                         |                                                              |
| token\_supply     | VARCHAR   | 28898994993839746288416012                                         |                                                              |

## 184. Table: PegSwapFourAssets\_event\_CommitNewParameters\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-08 15:24:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9631544                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x981a6d6de182c905072f57acb4860ac52e516f9f0f0b76d98e0d6ab33781e994 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 155                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x79a8c46dea5ada233abaffd40f3a0a2b1e5a4f27                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1583940266                                                         |                                                              |
| A                 | VARCHAR   | 500                                                                |                                                              |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 0                                                                  |                                                              |

## 185. Table: PegSwapFourAssets\_event\_NewParameters\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-06 18:59:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12973163                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x978a3411d23f47e6cf99b5897fd91d8c05d0d8cd6e13970acd477991ab99e7a3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 84                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45f783cce6b7ff23b2ab2d70e416cdb7d6055f51                         | Address of the contract that produced the log                |
| A                 | VARCHAR   | 2048                                                               |                                                              |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 186. Table: PegSwapFourAssets\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-19 20:18:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10298288                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x732c4a80fa9633bad0ba8b6cff6f1cb1d48f4e4d3b7c448d65b3a6ba98cd3aef | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 241                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45f783cce6b7ff23b2ab2d70e416cdb7d6055f51                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xbbc81d23ea2c3ec7e56d39296f0cbb648873a5d3                         |                                                              |
| token\_amounts    | VARCHAR   | 0,0,4881493803,0                                                   |                                                              |
| fees              | VARCHAR   | 41340664835342641,182598,363105,116917603730836947                 |                                                              |
| invariant         | VARCHAR   | 3645774970562363605748311                                          |                                                              |
| token\_supply     | VARCHAR   | 3526372563928952260657745                                          |                                                              |

## 187. Table: PegSwapFourAssets\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                                     | Description                                                  |
| ----------------- | --------- | --------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-05 04:55:35+00:00                                                   | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13554590                                                                    | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6b0ddde92df68cf7252ef3fa435a076030302e4d0e61817a02cdbd3e692a08d4          | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 547                                                                         | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa5407eae9ba41422680e2e00537571bcc53efbfd                                  | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xfcba3e75865d2d561be8d220616520c171f12851                                  |                                                              |
| token\_amounts    | VARCHAR   | 189932479101112240890772,187300588200,179567897390,175372737495466546298105 |                                                              |
| fees              | VARCHAR   | 0,0,0,0                                                                     |                                                              |
| token\_supply     | VARCHAR   | 90198925369708225838142552                                                  |                                                              |

## 188. Table: PegSwapThreeAssets\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-01 18:46:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9787710                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8ccdde26cb12ae48a5a841d34f561afb46926db4bed50e348b01bc4ffc00e141 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 73                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x52ea46506b9cc5ef470c5bf89f17dc28bb35d85c                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x42b9df65b219b3dd36ff330a4dd8f327a6ada990                         |                                                              |
| token\_amounts    | VARCHAR   | 0,0,100000                                                         |                                                              |
| fees              | VARCHAR   | 2894,47526,10                                                      |                                                              |
| invariant         | VARCHAR   | 54911086799970604783065                                            |                                                              |
| token\_supply     | VARCHAR   | 54098125559250955476225                                            |                                                              |

## 189. Table: PegSwapThreeAssets\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-16 19:48:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10875110                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd86f34e988709d22067837467fdb039917967feca9a0959cd3d0e6dd3f823cbc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 229                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7fc77b5c7614e1533320ea6ddc2eb61fa00a9714                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1600544926                                                         |                                                              |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 190. Table: PegSwapThreeAssets\_event\_NewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-05 15:09:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12768210                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0ccbffa23dff7d7c47dcdaed14c3d98aab5e4c63d531d8e243365745cbb1484e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 100                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbebc44782c7db0a1a60cb6fe97d0b483032ff1c7                         | Address of the contract that produced the log                |
| fee               | VARCHAR   | 3000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 191. Table: PegSwapThreeAssets\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-08 09:58:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17215038                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8a8551566b3e0d506b981a611649add6ee5519d5226f1261370f59ecc3f54f12 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 387                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbebc44782c7db0a1a60cb6fe97d0b483032ff1c7                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x8870898a85b03f030f1b893683c73015529838ad                         |                                                              |
| token\_amounts    | VARCHAR   | 31069413928658829178855,0,0                                        |                                                              |
| fees              | VARCHAR   | 679139070345550733,525548,153415                                   |                                                              |
| invariant         | VARCHAR   | 396825129069288347013388385                                        |                                                              |
| token\_supply     | VARCHAR   | 386869652457752726964320017                                        |                                                              |

## 192. Table: PegSwapThreeAssets\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-10 12:38:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15717754                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe4b6bc269514f8e72bd6ea954eefc170511a67a24ad193cb9d1fed0e38664d22 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 200                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbebc44782c7db0a1a60cb6fe97d0b483032ff1c7                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xe8db196d31fce86f74c9725d0045f1c0f6287a46                         |                                                              |
| token\_amounts    | VARCHAR   | 2030689322223743302383,1959851479,1623295393                       |                                                              |
| fees              | VARCHAR   | 0,0,0                                                              |                                                              |
| token\_supply     | VARCHAR   | 837563514791808064016266277                                        |                                                              |

## 193. Table: PegSwapTwoAssets\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-01 19:29:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16314016                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x44d90181f12d73be61d766834cdbe7388fbaebe122dade8d6a55fd45b660daad | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 43                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0f9cb53ebe405d49a0bbdbd291a65ff571bc83e1                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x094d12e5b541784701fd8d65f11fc0598fbc6332                         |                                                              |
| token\_amounts    | VARCHAR   | 0,19549266710999982650                                             |                                                              |
| fees              | VARCHAR   | 9535049693159341,3744846252273320                                  |                                                              |
| invariant         | VARCHAR   | 6045816099653326249719170                                          |                                                              |
| token\_supply     | VARCHAR   | 5673943549101548934203340                                          |                                                              |

## 194. Table: PegSwapTwoAssets\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-02 22:15:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17395938                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf1a187bb457e1bbe41488ef6c240690c9adabcfba591de4e0b10242cc04e6109 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 139                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa1f8a6807c402e4a15ef4eba36528a3fed24e577                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1686003323                                                         |                                                              |
| fee               | VARCHAR   | 2000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 195. Table: PegSwapTwoAssets\_event\_NewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-06 18:55:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12973135                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x54a7e977b0e1fb0f58e4f32227e63accaba08384a8ffb8ed09e672a3816cdf84 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 517                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2dded6da1bf5dbdf597c45fcfaa3194e53ecfeaf                         | Address of the contract that produced the log                |
| fee               | VARCHAR   | 6000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 196. Table: PegSwapTwoAssets\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-04 05:49:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13738116                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7b172481c81a7249b39b3d5e49644118dfd0ac35a1139e5ebd5cabcee6b0d8ad | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 299                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5a6a4d54456819380173272a5e8e9b9904bdf41b                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xa79828df1850e8a3a3064576f380d90aecdd3359                         |                                                              |
| token\_amounts    | VARCHAR   | 0,79341290005410405022433                                          |                                                              |
| fees              | VARCHAR   | 9322166975772501940,9140827790289616075                            |                                                              |
| invariant         | VARCHAR   | 2379919138160008734433059144                                       |                                                              |
| token\_supply     | VARCHAR   | 2371883415999587704593613961                                       |                                                              |

## 197. Table: PegSwapTwoAssets\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-18 19:13:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14412256                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7de1cc0ebb2fccf695b2b32c46798302dcaae58ce30472c94b5d8241e292b217 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 310                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5a6a4d54456819380173272a5e8e9b9904bdf41b                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xa79828df1850e8a3a3064576f380d90aecdd3359                         |                                                              |
| token\_amounts    | VARCHAR   | 8077052040679365417496,1946648171660325303919                      |                                                              |
| fees              | VARCHAR   | 0,0                                                                |                                                              |
| token\_supply     | VARCHAR   | 1184917670664088914471252874                                       |                                                              |

## 198. Table: PegSwap\_call\_exchange\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-07-10 04:21:11+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17660857                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x04796e71c328c2ea88b89831c46effd7c7be0efc68db99e7c4e2a2495ab7619f | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 41                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,1,0,6                                                            | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xf7b55c3732ad8b2c2da7c24f30a69f55c54fb717                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| i                  | VARCHAR   | 0                                                                  |                                                                                                                        |
| j                  | VARCHAR   | 1                                                                  |                                                                                                                        |
| dx                 | VARCHAR   | 6661745223381369750045                                             |                                                                                                                        |
| min\_dy            | VARCHAR   | 0                                                                  |                                                                                                                        |
| \_receiver         | VARCHAR   | 0x1c0d72a330f2768daf718def8a19bab019eead09                         |                                                                                                                        |

## 199. Table: PegSwap\_call\_exchangeunderlying\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-06-03 06:37:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17398422                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xbea76b3d5e49f3f24e8d93546d45d6cc683d2f06df71488b1a4303ba9f37aae4 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 0                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,3,0,1,2,1                                                        | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xe6b5cc1b4b47305c58392ce3d359b10282fc36ea                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| i                  | VARCHAR   | 0                                                                  |                                                                                                                        |
| j                  | VARCHAR   | 2                                                                  |                                                                                                                        |
| dx                 | VARCHAR   | 325639138753494588063744                                           |                                                                                                                        |
| min\_dy            | VARCHAR   | 325260798752                                                       |                                                                                                                        |
| \_receiver         | VARCHAR   | 0x3416cf6c708da44db2624d63ea0aaef7113527c6                         |                                                                                                                        |

## 200. Table: PegSwap\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-10 16:22:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15718864                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x64a22e107107606c924ae019f4cb7b6be121bcd22022037944eb6d13873eb6e8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 304                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7fc77b5c7614e1533320ea6ddc2eb61fa00a9714                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x071c661b4deefb59e2a3ddb20db036821eee8f4b                         |                                                              |
| token\_amount     | VARCHAR   | 980080719181304929                                                 |                                                              |
| coin\_amount      | VARCHAR   | 99783126                                                           |                                                              |

## 201. Table: PegSwap\_event\_TokenExchangeUnderlying\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-21 12:32:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11301489                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xce7f3a27ccbf3112f7e8769babd13e9ce67f0ae9b8b53d86947476ebeab4bd5a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 15                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x06364f10b501e868329afbc005b3492902d6c763                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x0000000094acb89a43eac2fbb3a07973efc2435c                         |                                                              |
| sold\_id          | VARCHAR   | 2                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 184501219504                                                       |                                                              |
| bought\_id        | VARCHAR   | 0                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 184216390292639959369103                                           |                                                              |

## 202. Table: PegSwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-15 05:34:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13618531                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x92d0999ad8cb86d9575a16c5f677123cbeb055587642be8979a61366b5b49388 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 208                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x04c90c198b2eff55716079bc06d7ccc4aa4d7512                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xf2f3ab09e2d8986fbecbba59ae838a5418a6680c                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 25407754894346840825                                               |                                                              |
| bought\_id        | VARCHAR   | 1                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 25375545957117130127                                               |                                                              |

## 203. Table: RENCurveExchangeAdapter2\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-26 07:58:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10340194                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1135708d40bed83262730b94f21ac7f5ed2caa6a35afc70b640bdb422e179913 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 86                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x26d9980571e77ffb0349f9c801dd7ca9951fb656                         | Address of the contract that produced the log                |
| burnAmount        | VARCHAR   | 497432581                                                          |                                                              |

## 204. Table: RENCurveExchangeAdapter2\_event\_DepositMintedCurve\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-25 02:12:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10332185                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfd8a93037ebc08e0863e5b208ef5fa01c0aa757e3825c5a702b37bf815349fcc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 217                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x26d9980571e77ffb0349f9c801dd7ca9951fb656                         | Address of the contract that produced the log                |
| mintedAmount      | VARCHAR   | 4995                                                               |                                                              |
| curveAmount       | VARCHAR   | 49594473221134                                                     |                                                              |

## 205. Table: RENCurveExchangeAdapter2\_event\_ReceiveRen\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| renAmount         | VARCHAR   |                                                              |             |

## 206. Table: RENCurveExchangeAdapter2\_event\_SwapReceived\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-29 17:55:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10362186                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x18fb83020b35f5ca9c2a54b395535347c4f5de29cee909c593905f8f879edcbe | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 96                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x26d9980571e77ffb0349f9c801dd7ca9951fb656                         | Address of the contract that produced the log                |
| mintedAmount      | VARCHAR   | 64935                                                              |                                                              |
| wbtcAmount        | VARCHAR   | 64609                                                              |                                                              |

## 207. Table: RENCurveExchangeAdapter3\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-17 15:07:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10678259                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x57e740dcc2111027648e61eaae76166f2d0ae78d135befaf99ca95f3203d12c3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 224                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73ab2bd10ad10f7174a1ad5afae3ce3d991c5047                         | Address of the contract that produced the log                |
| burnAmount        | VARCHAR   | 15771824                                                           |                                                              |

## 208. Table: RENCurveExchangeAdapter3\_event\_DepositMintedCurve\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-25 23:20:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10531507                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa8573aceb74f1036bdcbe6df871ab3e9e9209858c4ead97bb50f5c9191cfa58d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 57                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73ab2bd10ad10f7174a1ad5afae3ce3d991c5047                         | Address of the contract that produced the log                |
| mintedAmount      | VARCHAR   | 39960                                                              |                                                              |
| curveAmount       | VARCHAR   | 395965575091051                                                    |                                                              |

## 209. Table: RENCurveExchangeAdapter3\_event\_MetaTransactionExecuted\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-30 23:06:11+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10370027                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4b7ed3c22fa6c98ff7cad7f86c3aee51637c4916de4ea83e1d6f385b6f37ec5b                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 88                                                                                                   | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73ab2bd10ad10f7174a1ad5afae3ce3d991c5047                                                           | Address of the contract that produced the log                |
| userAddress       | VARCHAR   | 0xbf7d65d769e82e7b862df338223263ba33f72623                                                           |                                                              |
| relayerAddress    | VARCHAR   | 0xccc51ee93e9db01c670b5ccda59f73342135475b                                                           |                                                              |
| functionSignature | VARCHAR   | 0x74955c420000000000000000000000000000000000000000000000000000000005f143ab00000000000000000000000000 |                                                              |

## 210. Table: RENCurveExchangeAdapter3\_event\_ReceiveRen\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-21 22:54:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11701651                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x58513f8654a72fee91e7d66cbcf98125fbe9a7e026eb727b25f68b8733325a0a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 273                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73ab2bd10ad10f7174a1ad5afae3ce3d991c5047                         | Address of the contract that produced the log                |
| renAmount         | VARCHAR   | 388925250                                                          |                                                              |

## 211. Table: RENCurveExchangeAdapter3\_event\_SwapReceived\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-14 10:56:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11854406                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x87d3a9ea2a183c06b4b1b3ac7a76148666680b8f7b15d679b62e997ef67af349 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 229                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73ab2bd10ad10f7174a1ad5afae3ce3d991c5047                         | Address of the contract that produced the log                |
| mintedAmount      | VARCHAR   | 299250                                                             |                                                              |
| wbtcAmount        | VARCHAR   | 299128                                                             |                                                              |

## 212. Table: RENCurveExchangeAdapter\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-21 02:54:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10701010                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa2139207ebcae5c074f8fd8ed7fde39f4a4d274676e92e149936913c1105ff93 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 89                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9fe350dfa5f66bc086243f21a8f0932514316627                         | Address of the contract that produced the log                |
| burnAmount        | VARCHAR   | 30948045                                                           |                                                              |

## 213. Table: RENCurveExchangeAdapter\_event\_DepositMintedCurve\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-10 21:06:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10240271                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x582a3c32a0e3ea00d7e442670a0a9688752c7290291bfbf678ba1e136e9a59ae | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 157                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9fe350dfa5f66bc086243f21a8f0932514316627                         | Address of the contract that produced the log                |
| mintedAmount      | VARCHAR   | 4995                                                               |                                                              |
| curveAmount       | VARCHAR   | 49777210809020                                                     |                                                              |

## 214. Table: RENCurveExchangeAdapter\_event\_ReceiveRen\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-17 05:32:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10675714                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x009154ece15f313fb4a31503f0d4fdd1ea8b1df0198fd5d440d67aa1009e18d5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 25                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9fe350dfa5f66bc086243f21a8f0932514316627                         | Address of the contract that produced the log                |
| renAmount         | VARCHAR   | 929070                                                             |                                                              |

## 215. Table: RENCurveExchangeAdapter\_event\_RelayHubChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldRelayHub       | VARCHAR   |                                                              |             |
| newRelayHub       | VARCHAR   |                                                              |             |

## 216. Table: RENCurveExchangeAdapter\_event\_SwapReceived\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-26 20:12:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10738232                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x44c6215f91dacc15973a72c6a57fce57c5547f401ed86fe92c1efc4a87119935 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 274                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9fe350dfa5f66bc086243f21a8f0932514316627                         | Address of the contract that produced the log                |
| mintedAmount      | VARCHAR   | 399530070                                                          |                                                              |
| wbtcAmount        | VARCHAR   | 399476940                                                          |                                                              |

## 217. Table: RENSwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-31 10:35:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14113128                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc60e186f5963b67ec6d48f2b1f9a150639d2db0d4627e7f9eabee3f5c72eeeb2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 70                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x93054188d876f558f4a66b2ef1d97d16edf0895b                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x61e16b46f74aed8f9c2ec6cb2dcb2258bdfc7071                         |                                                              |
| token\_amounts    | VARCHAR   | 0,15419                                                            |                                                              |
| fees              | VARCHAR   | 2,2                                                                |                                                              |
| invariant         | VARCHAR   | 13770052427532677639835                                            |                                                              |
| token\_supply     | VARCHAR   | 13522380896427733857219                                            |                                                              |

## 218. Table: RENSwap\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-20 00:30:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11089752                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc7c98d20ae79e3907e69262eea57f034726074e57eb7c802a3e834df03d24ba5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 160                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x93054188d876f558f4a66b2ef1d97d16edf0895b                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1603413000                                                         |                                                              |
| admin             | VARCHAR   | 0x56295b752e632f74a6526988eace33c25c52c623                         |                                                              |

## 219. Table: RENSwap\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-16 19:48:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10875110                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd86f34e988709d22067837467fdb039917967feca9a0959cd3d0e6dd3f823cbc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 226                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x93054188d876f558f4a66b2ef1d97d16edf0895b                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1600544926                                                         |                                                              |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 220. Table: RENSwap\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-30 18:02:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11361635                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x202c74c05ec500f1d5eb4ed48adcd7dd39e84217a1d04a69da1fd69acefbd364 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 310                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x93054188d876f558f4a66b2ef1d97d16edf0895b                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 221. Table: RENSwap\_event\_NewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-19 21:38:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10895154                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5665f967b7e8ce027c56677dbca8a8711275c179775539f7ba766effe043595b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 95                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x93054188d876f558f4a66b2ef1d97d16edf0895b                         | Address of the contract that produced the log                |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 222. Table: RENSwap\_event\_RampA\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-19 16:57:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11087676                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4ccdf200b63de22bb99ba43c0338d5ab9474257401bdb79b31f6913dec083dc5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 113                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x93054188d876f558f4a66b2ef1d97d16edf0895b                         | Address of the contract that produced the log                |
| old\_A            | VARCHAR   | 125                                                                |                                                              |
| new\_A            | VARCHAR   | 200                                                                |                                                              |
| initial\_time     | VARCHAR   | 1603126643                                                         |                                                              |
| future\_time      | VARCHAR   | 1603549164                                                         |                                                              |

## 223. Table: RENSwap\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-07 06:56:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11404200                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x08971ac78891ee545dea069ddfa8eae77bde8e715dc1821b2bd5e4dc703eb07a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 167                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x93054188d876f558f4a66b2ef1d97d16edf0895b                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xc5cb4ea2984ea47f8c9948211b9d75aac1b518bb                         |                                                              |
| token\_amounts    | VARCHAR   | 0,20000000                                                         |                                                              |
| fees              | VARCHAR   | 1825,1827                                                          |                                                              |
| invariant         | VARCHAR   | 18075498639531194795088                                            |                                                              |
| token\_supply     | VARCHAR   | 17812851213328768958836                                            |                                                              |

## 224. Table: RENSwap\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-15 06:50:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11260872                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x594b93d5d62ad5d5969ce3f78bddd936531b2008e3e4328d6205f0ee696bf567 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 270                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x93054188d876f558f4a66b2ef1d97d16edf0895b                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xe297dd41de91a5c61338e1688ec4865b48dd3f8c                         |                                                              |
| token\_amount     | VARCHAR   | 2958068980054259044                                                |                                                              |
| coin\_amount      | VARCHAR   | 299682908                                                          |                                                              |

## 225. Table: RENSwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-10 03:28:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11025256                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xff839fb0446cddecbc51066095014531689bd8ffb2cd8d9eabdf146663560fef | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 147                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x93054188d876f558f4a66b2ef1d97d16edf0895b                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x0ac5598dd50c95923fed44151ec688152ceeaf22                         |                                                              |
| token\_amounts    | VARCHAR   | 52668144237,56225483561                                            |                                                              |
| fees              | VARCHAR   | 0,0                                                                |                                                              |
| token\_supply     | VARCHAR   | 27522841724426589733804                                            |                                                              |

## 226. Table: RENSwap\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 227. Table: RENSwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-29 01:08:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16287037                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x884e1c568777737ab9dfdc2219fd74a23bc537befe41fbdc590d668e329c9fec | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 28                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x93054188d876f558f4a66b2ef1d97d16edf0895b                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xfd0000000100069ad1670066004306009b487ad7                         |                                                              |
| sold\_id          | VARCHAR   | 1                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 8102480                                                            |                                                              |
| bought\_id        | VARCHAR   | 0                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 6951855                                                            |                                                              |

## 228. Table: RSVSwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-10 16:22:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12998485                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe2cc12a5c5aa97587f7559abf76df5e15d9de8d0fd0a7ec15c8b52da8413113f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 198                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc18cc39da8b11da8c3541c598ee022258f9744da                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xbe175115bf33e12348ff77ccfee4726866a0fbd5                         |                                                              |
| token\_amounts    | VARCHAR   | 0,495093480059154346254233                                         |                                                              |
| fees              | VARCHAR   | 29064613616817270635,28726528178437144989                          |                                                              |
| invariant         | VARCHAR   | 11704071863292272067682035                                         |                                                              |
| token\_supply     | VARCHAR   | 11405091359209468275597162                                         |                                                              |

## 229. Table: RSVSwap\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-18 19:03:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11081722                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x98361c05d4c46bc6d6440f35cd8949e847d1ef3e386e7687702171c64b10b22b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 111                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc18cc39da8b11da8c3541c598ee022258f9744da                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1603307023                                                         |                                                              |
| admin             | VARCHAR   | 0x3f4232107ff437bcd7ea9abc134ad553efeddaff                         |                                                              |

## 230. Table: RSVSwap\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-18 19:02:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11081719                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4f94da2b85ddd8a4c510532beeb335ef3df7be8ee799f95f0d7c65a2bd36421c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc18cc39da8b11da8c3541c598ee022258f9744da                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1603306978                                                         |                                                              |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 231. Table: RSVSwap\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-24 22:14:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11121775                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9334ed7360110e7427457b370a5cba4beb5ac5b9b99cc246c9b85752079fa746 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 78                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc18cc39da8b11da8c3541c598ee022258f9744da                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0x3f4232107ff437bcd7ea9abc134ad553efeddaff                         |                                                              |

## 232. Table: RSVSwap\_event\_NewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-24 22:18:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11121791                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8d64bd743cb812a35c38fd7509c3bb7d7ede47f8d241299d2152b2873e358949 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 94                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc18cc39da8b11da8c3541c598ee022258f9744da                         | Address of the contract that produced the log                |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 233. Table: RSVSwap\_event\_RampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| old\_A            | VARCHAR   |                                                              |             |
| new\_A            | VARCHAR   |                                                              |             |
| initial\_time     | VARCHAR   |                                                              |             |
| future\_time      | VARCHAR   |                                                              |             |

## 234. Table: RSVSwap\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-05 14:07:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11197666                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc2c83f5c06eae4bbcd0f28f6e757a88b72c818eda56df8126497ebf40bf90583 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 211                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc18cc39da8b11da8c3541c598ee022258f9744da                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xbe175115bf33e12348ff77ccfee4726866a0fbd5                         |                                                              |
| token\_amounts    | VARCHAR   | 0,29813377851684194984521                                          |                                                              |
| fees              | VARCHAR   | 3476248690780970079,3455287220359134504                            |                                                              |
| invariant         | VARCHAR   | 714004475830618208522346                                           |                                                              |
| token\_supply     | VARCHAR   | 713546572698465802583811                                           |                                                              |

## 235. Table: RSVSwap\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-27 23:53:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13310953                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe294ceac6a4da8594cc12cc28de515543b2ce29d360b066392a3de2937fcfab9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 146                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc18cc39da8b11da8c3541c598ee022258f9744da                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xbe175115bf33e12348ff77ccfee4726866a0fbd5                         |                                                              |
| token\_amount     | VARCHAR   | 5584969917468378017215                                             |                                                              |
| coin\_amount      | VARCHAR   | 5638712277828649374880                                             |                                                              |
| token\_supply     | VARCHAR   | 10325034142328992530186709                                         |                                                              |

## 236. Table: RSVSwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-13 13:36:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11444987                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbe60bec7e19888ea8c071554925f1bba3f2320441f546b8b2c3aa5c2a2497926 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 276                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc18cc39da8b11da8c3541c598ee022258f9744da                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xdf094b37e65dc2f11d7f93e21add124802271c51                         |                                                              |
| token\_amounts    | VARCHAR   | 0,0                                                                |                                                              |
| fees              | VARCHAR   | 0,0                                                                |                                                              |
| token\_supply     | VARCHAR   | 630119912668384243036939                                           |                                                              |

## 237. Table: RSVSwap\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 238. Table: RSVSwap\_event\_TokenExchangeUnderlying\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-25 05:27:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12106194                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5d7fa0fc1231716316bdd7d1321b96a10bcafa672957da295be32bb0407c1591 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 231                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc18cc39da8b11da8c3541c598ee022258f9744da                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xdb38ae75c5f44276803345f7f02e95a0aeef5944                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 12452010165208775060452                                            |                                                              |
| bought\_id        | VARCHAR   | 1                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 12438015608623302012561                                            |                                                              |

## 239. Table: RSVSwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-29 20:53:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12731183                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd232fca5ec8af27c3ed4dfef3b32661b3f45dad0149cc562ada81e3ef92937ca | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 264                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc18cc39da8b11da8c3541c598ee022258f9744da                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x2393c368c70b42f055a4932a3fbec2ac9c548011                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 4611968939993825962                                                |                                                              |
| bought\_id        | VARCHAR   | 1                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 4517944696351197399                                                |                                                              |

## 240. Table: RegistryProvider\_event\_AddressModified\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-14 06:59:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16181302                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x11cb09e51d1f291667e69ff5cfb3d94c1c5c6a1d39a6b41b93e6316a83363749 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 180                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0000000022d53366457f9d5e68ec105046fc4383                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 2                                                                  |                                                              |
| new\_address      | VARCHAR   | 0x99a58482bd75cbab83b27ec03ca68ff489b5788f                         |                                                              |
| version           | VARCHAR   | 13                                                                 |                                                              |

## 241. Table: RegistryProvider\_event\_NewAddressIdentifier\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-04 19:31:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17189395                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x11fa308132f07f0272e1228ac53f0fca94f58093738be1d49b5cbd8d24031cf8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 217                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0000000022d53366457f9d5e68ec105046fc4383                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 10                                                                 |                                                              |
| addr              | VARCHAR   | 0x0145fd99f1dd6e2491e44fca608c481c9c5b97a9                         |                                                              |
| description       | VARCHAR   | crvUSD plain pools                                                 |                                                              |

## 242. Table: Registry\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-20 12:40:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10302704                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb90506f6e28aa6658b9eab948e33e74e209c528b9aea1bbe6cbc999018d8a80d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 131                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7002b727ef8f5571cb5f9d70d13dbeeb4dfae9d1                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1592916020                                                         |                                                              |
| admin             | VARCHAR   | 0xc447fcaf1def19a583f97b3620627bf69c05b5fb                         |                                                              |

## 243. Table: Registry\_event\_NewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| admin             | VARCHAR   |                                                              |             |

## 244. Table: Registry\_event\_PoolAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-20 12:18:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10302597                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x53e8074c02ac7f3a6af01401dfa097cbe6d1c89a59b04a989d6978a72237d42f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 133                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7002b727ef8f5571cb5f9d70d13dbeeb4dfae9d1                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0xa5407eae9ba41422680e2e00537571bcc53efbfd                         |                                                              |
| rate\_method\_id  | VARCHAR   | 0x00000000                                                         |                                                              |

## 245. Table: Registry\_event\_PoolRemoved\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| pool              | VARCHAR   |                                                              |             |

## 246. Table: Registry\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-10 17:39:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11231194                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4bebcee29e37bcccf0a4e7d7da43b5b5039edd6440a0d0ae3ccccbfe51134c93 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 252                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7002b727ef8f5571cb5f9d70d13dbeeb4dfae9d1                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xc7235982f6929e1239e45399cea15ae03d0f213e                         |                                                              |
| pool              | VARCHAR   | 0xa2b47e3d5c44877cca798226b7b8118f9bfb7a56                         |                                                              |
| token\_sold       | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         |                                                              |
| token\_bought     | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| amount\_sold      | VARCHAR   | 44094663242667074022                                               |                                                              |
| amount\_bought    | VARCHAR   | 44441080                                                           |                                                              |

## 247. Table: Registry\_v2\_event\_PoolAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-21 01:21:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11493710                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x632d61022f9200effe26df3d722c55af482236baad3fecfd02e4560da5d83950 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 275                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7d86446ddb609ed0f5f8684acf30380a356b2b4c                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0xc5424b857f758e906013f3555dad202e4bdb4567                         |                                                              |
| rate\_method\_id  | VARCHAR   | 0x00000000                                                         |                                                              |

## 248. Table: Registry\_v2\_event\_PoolRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-27 01:48:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11532964                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcc0766d2c8b71782c060836d4bbd3f26d82d5d4763ad00ccbb94665d5ca762b2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 179                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7d86446ddb609ed0f5f8684acf30380a356b2b4c                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0x83f252f036761a1e3d10daca8e16d7b21e3744d7                         |                                                              |

## 249. Table: USDD3CRV\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-02 08:05:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17391762                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd459000397a1cf47311294904610de4cc61971e1a9c8ad9805046c5ccb201a07 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 365                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe6b5cc1b4b47305c58392ce3d359b10282fc36ea                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xa79828df1850e8a3a3064576f380d90aecdd3359                         |                                                              |
| token\_amounts    | VARCHAR   | 0,192038691193282648293722                                         |                                                              |
| fees              | VARCHAR   | 20465156046009208501,19947711075276788144                          |                                                              |
| invariant         | VARCHAR   | 3020592622403692652882376                                          |                                                              |
| token\_supply     | VARCHAR   | 3001521470281104741765936                                          |                                                              |

## 250. Table: USDD3CRV\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-31 22:26:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17381805                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4f82dcf7c100dd38a724055e85ad1a0ee752086788396df9e91ed157912d4435 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 186                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe6b5cc1b4b47305c58392ce3d359b10282fc36ea                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x42b525262012db5ce0723eb14f2cdfac51f3556e                         |                                                              |
| spender           | VARCHAR   | 0x7f3f33b42b9734e61cb44424d130b5f6e09c9db3                         |                                                              |
| value             | VARCHAR   | 8000000000000000000000000000                                       |                                                              |

## 251. Table: USDD3CRV\_event\_RampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| old\_A            | VARCHAR   |                                                              |             |
| new\_A            | VARCHAR   |                                                              |             |
| initial\_time     | VARCHAR   |                                                              |             |
| future\_time      | VARCHAR   |                                                              |             |

## 252. Table: USDD3CRV\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-25 00:28:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16701739                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe666d1a6cd8f332c10c6ba2839065b041248771218a8526b4e774c420f37f0c0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 545                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe6b5cc1b4b47305c58392ce3d359b10282fc36ea                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x3ca1e1efa15de2bad5032e2f173d55b5e92857ed                         |                                                              |
| token\_amounts    | VARCHAR   | 0,44045275241326348235922                                          |                                                              |
| fees              | VARCHAR   | 5585070570897521713,5440257913245695475                            |                                                              |
| invariant         | VARCHAR   | 19525428996683847464822587                                         |                                                              |
| token\_supply     | VARCHAR   | 19446751716930504574678330                                         |                                                              |

## 253. Table: USDD3CRV\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-11 08:54:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16604454                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x37d79d1099750cb54f8e0ab1893a26fd430614d61c3d1b01b40aa12b4b9d1fc0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 58                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe6b5cc1b4b47305c58392ce3d359b10282fc36ea                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xa79828df1850e8a3a3064576f380d90aecdd3359                         |                                                              |
| token\_amount     | VARCHAR   | 125030516109863355206                                              |                                                              |
| coin\_amount      | VARCHAR   | 125885364636843043340                                              |                                                              |
| token\_supply     | VARCHAR   | 20303545024209444518934856                                         |                                                              |

## 254. Table: USDD3CRV\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-04 08:11:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17405985                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x592cd6d7de47de1ec6c5b78d2e8336c86819434eb8e24f1ccb291d33c75b0b61 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 73                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe6b5cc1b4b47305c58392ce3d359b10282fc36ea                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xa79828df1850e8a3a3064576f380d90aecdd3359                         |                                                              |
| token\_amounts    | VARCHAR   | 64962543038162638234711,56835067475735679133755                    |                                                              |
| fees              | VARCHAR   | 0,0                                                                |                                                              |
| token\_supply     | VARCHAR   | 2879035038451551707766982                                          |                                                              |

## 255. Table: USDD3CRV\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 256. Table: USDD3CRV\_event\_TokenExchangeUnderlying\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-04 12:08:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16111345                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc1e7139e982ae8ec3299a85e00696d7d5edcb2ffd4dd48dbb2b9e84e8db4e3cb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 9                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe6b5cc1b4b47305c58392ce3d359b10282fc36ea                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x53222470cdcfb8081c0e3a50fd106f0d69e63f20                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 260666672467699389022503                                           |                                                              |
| bought\_id        | VARCHAR   | 2                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 256389123871                                                       |                                                              |

## 257. Table: USDD3CRV\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-14 16:21:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17479334                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x150f26e80d87c423b524e8fe35e09003d45e95bcea9f78aa845ad6f79ec908e7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 129                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe6b5cc1b4b47305c58392ce3d359b10282fc36ea                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xb9fc157394af804a3578134a6585c0dc9cc990d4                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 330907607356896791202                                              |                                                              |
| bought\_id        | VARCHAR   | 1                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 322234198548222925783                                              |                                                              |

## 258. Table: USDD3CRV\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-07 08:46:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16353805                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7903c0b655f836632311287a2b3d2f1ce1dc643c9f5b0628b449fb8b205276f5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 83                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe6b5cc1b4b47305c58392ce3d359b10282fc36ea                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| receiver          | VARCHAR   | 0xd11c6816a2a550e330a9d1049d9c545a39974fc2                         |                                                              |
| value             | VARCHAR   | 336932218664473052209                                              |                                                              |

## 259. Table: USDKSwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-07 19:58:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11407701                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9c5c728a48174d1e7bb7bf764f58f478ee6a95d24f79ce8ebc0a5249b1aaf7c0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 46                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3e01dd8a5e1fb3481f0f589056b428fc308af0fb                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xf1f85a74ad6c64315f85af52d3d46bf715236adc                         |                                                              |
| token\_amounts    | VARCHAR   | 0,354727960769124315640                                            |                                                              |
| fees              | VARCHAR   | 31168578492804137,31045100996404204                                |                                                              |
| invariant         | VARCHAR   | 831760355316348830825349                                           |                                                              |
| token\_supply     | VARCHAR   | 451396984334676449688691                                           |                                                              |

## 260. Table: USDKSwap\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-27 13:37:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11340846                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2496882c3dfa545785a06252337f90ae917aadc0a6e99c804ef6d7bc3c0a5c8d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 160                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3e01dd8a5e1fb3481f0f589056b428fc308af0fb                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1606743476                                                         |                                                              |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 261. Table: USDKSwap\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-18 19:02:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11081713                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1c91a0880597f293dfc5e1acf64d44bb1ceec5eaab05b080d74c2b2452915e71 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 149                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3e01dd8a5e1fb3481f0f589056b428fc308af0fb                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1603306948                                                         |                                                              |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 262. Table: USDKSwap\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-30 18:07:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11361660                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xef4ae2bd118e6b33224d465b0877b4268349e166a4cf59fdd58ccce343e9eafd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 249                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3e01dd8a5e1fb3481f0f589056b428fc308af0fb                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 263. Table: USDKSwap\_event\_NewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-24 23:53:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11122204                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3fa5bdfdfb8762fab4e1c363fc99e4db90755a95f541ac7173d9151e865d77b7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 34                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3e01dd8a5e1fb3481f0f589056b428fc308af0fb                         | Address of the contract that produced the log                |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 264. Table: USDKSwap\_event\_RampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| old\_A            | VARCHAR   |                                                              |             |
| new\_A            | VARCHAR   |                                                              |             |
| initial\_time     | VARCHAR   |                                                              |             |
| future\_time      | VARCHAR   |                                                              |             |

## 265. Table: USDKSwap\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-26 03:44:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11331639                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6b1cfb476f22798d0cfd78fd42d4936d6738840e9b769479f963bbbf64599037 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 220                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3e01dd8a5e1fb3481f0f589056b428fc308af0fb                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xf1f85a74ad6c64315f85af52d3d46bf715236adc                         |                                                              |
| token\_amounts    | VARCHAR   | 0,41990906363158724063960                                          |                                                              |
| fees              | VARCHAR   | 2543002704722421652,2543430379492975263                            |                                                              |
| invariant         | VARCHAR   | 831751983964682747959970                                           |                                                              |
| token\_supply     | VARCHAR   | 451504051577216899294369                                           |                                                              |

## 266. Table: USDKSwap\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-15 19:33:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11459598                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x176d507eeca657923e50a6fccd20ea4dcf16d2233f08166dcd39d68ddce01627 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 288                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3e01dd8a5e1fb3481f0f589056b428fc308af0fb                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xf1f85a74ad6c64315f85af52d3d46bf715236adc                         |                                                              |
| token\_amount     | VARCHAR   | 28563318294282928178173                                            |                                                              |
| coin\_amount      | VARCHAR   | 52298294462382617062886                                            |                                                              |
| token\_supply     | VARCHAR   | 335645791191822143381770                                           |                                                              |

## 267. Table: USDKSwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-21 23:34:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14820121                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x17436a78479e0268599b8eedbb741cd89858da2902e479a692de8da9a1b3ecef | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 420                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3e01dd8a5e1fb3481f0f589056b428fc308af0fb                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xf1f85a74ad6c64315f85af52d3d46bf715236adc                         |                                                              |
| token\_amounts    | VARCHAR   | 389678365006446812564,225839106844558935231                        |                                                              |
| fees              | VARCHAR   | 0,0                                                                |                                                              |
| token\_supply     | VARCHAR   | 261370040894301690004415                                           |                                                              |

## 268. Table: USDKSwap\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 269. Table: USDKSwap\_event\_TokenExchangeUnderlying\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-14 00:14:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17688071                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3cc66bd66541fc5bd4e26c1bc38b9954e52933a4f9552a23bb0e40722286016c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 248                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3e01dd8a5e1fb3481f0f589056b428fc308af0fb                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xd291328a6c202c5b18dcb24f279f69de1e065f70                         |                                                              |
| sold\_id          | VARCHAR   | 2                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 6284000000                                                         |                                                              |
| bought\_id        | VARCHAR   | 3                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 6281555245                                                         |                                                              |

## 270. Table: USDKSwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-04 20:17:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16557749                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3ad950c989d2ddde2311aa13a6f0d4864edf6083a21ae03989f1b20e375d3f03 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3e01dd8a5e1fb3481f0f589056b428fc308af0fb                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x340f820684dec78c59068aabc9f8c99a2ce6b69c                         |                                                              |
| sold\_id          | VARCHAR   | 1                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 136991565366378041999                                              |                                                              |
| bought\_id        | VARCHAR   | 0                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 140416790497799724610                                              |                                                              |

## 271. Table: USDNSwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-17 02:07:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14020240                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x07a33a0fa2492c19e506a5926b4d2fa366c8f0b850ec9adcd350a3e33651ba4e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 17                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0f9cb53ebe405d49a0bbdbd291a65ff571bc83e1                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x094d12e5b541784701fd8d65f11fc0598fbc6332                         |                                                              |
| token\_amounts    | VARCHAR   | 0,1411493122210732157134842                                        |                                                              |
| fees              | VARCHAR   | 180236172355332228172,174836418885805920399                        |                                                              |
| invariant         | VARCHAR   | 380224314640412590912369431                                        |                                                              |
| token\_supply     | VARCHAR   | 362773209196721611745500398                                        |                                                              |

## 272. Table: USDNSwap\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-27 01:36:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11337610                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1728cd3aa595fd70f8e1c326c19683d36a30514e8991f71e0cb2b703bfc62c18 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 215                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0f9cb53ebe405d49a0bbdbd291a65ff571bc83e1                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1606700188                                                         |                                                              |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 273. Table: USDNSwap\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| deadline          | VARCHAR   |                                                              |             |
| fee               | VARCHAR   |                                                              |             |
| admin\_fee        | VARCHAR   |                                                              |             |

## 274. Table: USDNSwap\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-30 18:10:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11361668                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x32ccc7128e6bf6c2a7cb51b35287adba63af3f533ce55258199be213881bdc40 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 119                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0f9cb53ebe405d49a0bbdbd291a65ff571bc83e1                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 275. Table: USDNSwap\_event\_NewFee\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| fee               | VARCHAR   |                                                              |             |
| admin\_fee        | VARCHAR   |                                                              |             |

## 276. Table: USDNSwap\_event\_RampA\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-19 20:20:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11889473                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3cb30e76f7e834651aa675937e01d3631dfdcf9a17c3e3e824a2a8432473c2bb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 86                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0f9cb53ebe405d49a0bbdbd291a65ff571bc83e1                         | Address of the contract that produced the log                |
| old\_A            | VARCHAR   | 10000                                                              |                                                              |
| new\_A            | VARCHAR   | 5000                                                               |                                                              |
| initial\_time     | VARCHAR   | 1613766029                                                         |                                                              |
| future\_time      | VARCHAR   | 1614285782                                                         |                                                              |

## 277. Table: USDNSwap\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-10 06:41:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12995835                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x655d2e874ce6819f1041fc35550fcccd4cc02ec2aee7785e333359c334e5f949 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 246                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0f9cb53ebe405d49a0bbdbd291a65ff571bc83e1                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x094d12e5b541784701fd8d65f11fc0598fbc6332                         |                                                              |
| token\_amounts    | VARCHAR   | 0,103134910844295980049289                                         |                                                              |
| fees              | VARCHAR   | 10150847084659292210,9980236486086797889                           |                                                              |
| invariant         | VARCHAR   | 671301284828213621634260177                                        |                                                              |
| token\_supply     | VARCHAR   | 649490464141711564319261368                                        |                                                              |

## 278. Table: USDNSwap\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-03 01:35:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11578565                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa91d2a131d9010849b57cf564e1dea5f5774919c66bc894337fe73435072445a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 20                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0f9cb53ebe405d49a0bbdbd291a65ff571bc83e1                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x094d12e5b541784701fd8d65f11fc0598fbc6332                         |                                                              |
| token\_amount     | VARCHAR   | 261134679600522879358352                                           |                                                              |
| coin\_amount      | VARCHAR   | 257007608689065606270535                                           |                                                              |
| token\_supply     | VARCHAR   | 99820501303690265999671880                                         |                                                              |

## 279. Table: USDNSwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-13 06:04:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14196029                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdf232adb3c6f90a069d080af5a5e917faadd073d8f2b367c982f292eb4255106 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 80                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0f9cb53ebe405d49a0bbdbd291a65ff571bc83e1                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x094d12e5b541784701fd8d65f11fc0598fbc6332                         |                                                              |
| token\_amounts    | VARCHAR   | 582140478700865876943418,349995385635886734221182                  |                                                              |
| fees              | VARCHAR   | 0,0                                                                |                                                              |
| token\_supply     | VARCHAR   | 256620292174775347415155269                                        |                                                              |

## 280. Table: USDNSwap\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 281. Table: USDNSwap\_event\_TokenExchangeUnderlying\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-23 07:47:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14828336                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x003ac60fc3202806ebb50c74fbdf99d12f66e9d69405527198fd1024d9d82b5a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 252                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0f9cb53ebe405d49a0bbdbd291a65ff571bc83e1                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x81c46feca27b31f3adc2b91ee4be9717d1cd3dd7                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 62168291520000000000                                               |                                                              |
| bought\_id        | VARCHAR   | 3                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 60918772                                                           |                                                              |

## 282. Table: USDNSwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-07 19:53:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16357124                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9facee9c18ece1478655efef635092335ce4d8666082457d927841316b80471e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 26                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0f9cb53ebe405d49a0bbdbd291a65ff571bc83e1                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xe4000004000bd8006e00720000d27d1fa000d43e                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 753970224757521981248                                              |                                                              |
| bought\_id        | VARCHAR   | 1                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 300419935033017823127                                              |                                                              |

## 283. Table: USDTSwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-30 09:41:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11157410                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x17aa51896883b8ce156620e3f43b97001f7cede323e8b0b596f6af67410b76b0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 236                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x52ea46506b9cc5ef470c5bf89f17dc28bb35d85c                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xac795d2c97e60df6a99ff1c814727302fd747a80                         |                                                              |
| token\_amounts    | VARCHAR   | 0,0,6968758940                                                     |                                                              |
| fees              | VARCHAR   | 265659304,2301028666,543795                                        |                                                              |
| invariant         | VARCHAR   | 4052306421114757570290689                                          |                                                              |
| token\_supply     | VARCHAR   | 3886114970060317856675280                                          |                                                              |

## 284. Table: USDTSwap\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-01 21:02:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10972510                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe9da848a20ccc6708b1e2ff8b494dcaefd41edfe08615c13fc0e8f2d6d0ce882 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 264                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x52ea46506b9cc5ef470c5bf89f17dc28bb35d85c                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1601845343                                                         |                                                              |
| admin             | VARCHAR   | 0x6e8f6d1da6232d5e40b0b8758a0145d6c5123eb7                         |                                                              |

## 285. Table: USDTSwap\_event\_CommitNewParameters\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-02-17 02:01:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9497846                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xefd4f1829262c7d6b3df13064b0f0bbee291eabacf01fa1450c17e00ca19d150 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 159                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x52ea46506b9cc5ef470c5bf89f17dc28bb35d85c                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1582164107                                                         |                                                              |
| A                 | VARCHAR   | 1350                                                               |                                                              |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 0                                                                  |                                                              |

## 286. Table: USDTSwap\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-30 18:26:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11361727                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0c78e2df3a5a29ba3ba218d7e76982bfccd4f9bac0ee41510bbc562662a92f19 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 237                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x52ea46506b9cc5ef470c5bf89f17dc28bb35d85c                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 287. Table: USDTSwap\_event\_NewParameters\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-15 17:15:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11061687                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8a11f0dcd9668e69d3062c86451bc423ad6807c2dc40caef3b92fb793a333975 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 54                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x52ea46506b9cc5ef470c5bf89f17dc28bb35d85c                         | Address of the contract that produced the log                |
| A                 | VARCHAR   | 2000                                                               |                                                              |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 288. Table: USDTSwap\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-19 16:31:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14037035                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x825f825b4f4108a2ba035b0549b453bd40e23623f3a30690a916ddd00a711131 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 213                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x52ea46506b9cc5ef470c5bf89f17dc28bb35d85c                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xac795d2c97e60df6a99ff1c814727302fd747a80                         |                                                              |
| token\_amounts    | VARCHAR   | 0,0,3730980093                                                     |                                                              |
| fees              | VARCHAR   | 578530408,706045872,285015                                         |                                                              |
| invariant         | VARCHAR   | 7516965087684770155241476                                          |                                                              |
| token\_supply     | VARCHAR   | 6838312615534070784938290                                          |                                                              |

## 289. Table: USDTSwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-11 09:19:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11235462                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9106a1dc8c5a23384c5c248b8a1e8364852036a66b2ebc29dd05782f1e61bf84 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 66                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x52ea46506b9cc5ef470c5bf89f17dc28bb35d85c                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xac795d2c97e60df6a99ff1c814727302fd747a80                         |                                                              |
| token\_amounts    | VARCHAR   | 13063228213149,145929840019069,9657608491                          |                                                              |
| fees              | VARCHAR   | 0,0,0                                                              |                                                              |
| token\_supply     | VARCHAR   | 950057734046741264163165                                           |                                                              |

## 290. Table: USDTSwap\_event\_TokenExchangeUnderlying\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-23 17:57:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17543898                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xed245de7d415ef37d252c9505e6b6782e50f8acb75857970bcb1ef62d4f20f4f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 151                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x52ea46506b9cc5ef470c5bf89f17dc28bb35d85c                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xf7a2f863299c17dfa11cd8a14e7c7dca92f315b9                         |                                                              |
| sold\_id          | VARCHAR   | 1                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 3321263237                                                         |                                                              |
| bought\_id        | VARCHAR   | 2                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 3321578501                                                         |                                                              |

## 291. Table: USDTSwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-05 15:04:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12374913                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6a4ca3b5b899e884a01a03af111b2d156eab31f9ae8313159ae65cc7ebc9cd53 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 322                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x52ea46506b9cc5ef470c5bf89f17dc28bb35d85c                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xdb38ae75c5f44276803345f7f02e95a0aeef5944                         |                                                              |
| sold\_id          | VARCHAR   | 2                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 4475536128                                                         |                                                              |
| bought\_id        | VARCHAR   | 1                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 20381688192433                                                     |                                                              |

## 292. Table: USTSwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-23 13:59:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14442968                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x26a63790f59b13d4b46036e67cc260f436b8de185780e69566d808edc5f96f07 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 207                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x890f4e345b1daed0367a877a1612f86a1f86985f                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xb0a0716841f2fc03fba72a891b8bb13584f52f2d                         |                                                              |
| token\_amounts    | VARCHAR   | 0,9800873376986540703                                              |                                                              |
| fees              | VARCHAR   | 852400213966880,837776570015421                                    |                                                              |
| invariant         | VARCHAR   | 30643764438036554786607569                                         |                                                              |
| token\_supply     | VARCHAR   | 29213481146495164306771374                                         |                                                              |

## 293. Table: USTSwap\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| deadline          | VARCHAR   |                                                              |             |
| admin             | VARCHAR   |                                                              |             |

## 294. Table: USTSwap\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| deadline          | VARCHAR   |                                                              |             |
| fee               | VARCHAR   |                                                              |             |
| admin\_fee        | VARCHAR   |                                                              |             |

## 295. Table: USTSwap\_event\_NewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| admin             | VARCHAR   |                                                              |             |

## 296. Table: USTSwap\_event\_NewFee\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| fee               | VARCHAR   |                                                              |             |
| admin\_fee        | VARCHAR   |                                                              |             |

## 297. Table: USTSwap\_event\_RampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| old\_A            | VARCHAR   |                                                              |             |
| new\_A            | VARCHAR   |                                                              |             |
| initial\_time     | VARCHAR   |                                                              |             |
| future\_time      | VARCHAR   |                                                              |             |

## 298. Table: USTSwap\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-24 00:54:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11715221                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x158c622c6578874fc5c2e6714fa5207155c53b38420f9d42e7e16104c917739b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 246                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x890f4e345b1daed0367a877a1612f86a1f86985f                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xb0a0716841f2fc03fba72a891b8bb13584f52f2d                         |                                                              |
| token\_amounts    | VARCHAR   | 0,1983738557560223566700                                           |                                                              |
| fees              | VARCHAR   | 166387746372357822,165669927151970102                              |                                                              |
| invariant         | VARCHAR   | 10875888044330367144601594                                         |                                                              |
| token\_supply     | VARCHAR   | 10835834676364207590008796                                         |                                                              |

## 299. Table: USTSwap\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-21 05:58:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12281833                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaa4f58e5a271678d121d6b824a0bc0927edad48097d5b3d5a2071a57a89333a4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 118                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x890f4e345b1daed0367a877a1612f86a1f86985f                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xb0a0716841f2fc03fba72a891b8bb13584f52f2d                         |                                                              |
| token\_amount     | VARCHAR   | 98769318065983237492288                                            |                                                              |
| coin\_amount      | VARCHAR   | 98530510073153720583977                                            |                                                              |
| token\_supply     | VARCHAR   | 37945588845405923656033547                                         |                                                              |

## 300. Table: USTSwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-30 11:48:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14106950                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0b67f3290d2cb93bfa8be69b6a41dc4087b15bed1cea0b6e064b6b98609f6eac | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 113                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x890f4e345b1daed0367a877a1612f86a1f86985f                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xb0a0716841f2fc03fba72a891b8bb13584f52f2d                         |                                                              |
| token\_amounts    | VARCHAR   | 164706670880440944288690,171974087753501221706823                  |                                                              |
| fees              | VARCHAR   | 0,0                                                                |                                                              |
| token\_supply     | VARCHAR   | 68417153400790228180688441                                         |                                                              |

## 301. Table: USTSwap\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 302. Table: USTSwap\_event\_TokenExchangeUnderlying\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-19 09:12:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12269640                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8b8ee11d8a499c3f396de59ea9324bc443176076d8525451c0d5795ab9f0cc78 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 46                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x890f4e345b1daed0367a877a1612f86a1f86985f                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xdd23abb2227b4a3add86051810e03791f41c34e4                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 28221000000000000000000                                            |                                                              |
| bought\_id        | VARCHAR   | 1                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 28298654508078788935355                                            |                                                              |

## 303. Table: USTSwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-25 01:53:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14651009                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x80610baa3f285deb93e837a89c2c84406afc52dd281522e11957ab373222b2ba | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 28                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x890f4e345b1daed0367a877a1612f86a1f86985f                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xa1006d0051a35b0000f961a8000000009ea8d2db                         |                                                              |
| sold\_id          | VARCHAR   | 1                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 1463531293382181207138                                             |                                                              |
| bought\_id        | VARCHAR   | 0                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 1490799494597973658733                                             |                                                              |

## 304. Table: WBETH\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-23 04:29:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17319579                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc0103a96df8946726ce17f70a7f6f5e79b7ab0629a0dae9ff6652c7e949b030d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 191                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbfab6fa95e0091ed66058ad493189d2cb29385e6                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xca40e5d0321a67bea2f2cf0c24848673f5c38279                         |                                                              |
| token\_amounts    | VARCHAR   | 400000000000000000000,0                                            |                                                              |
| fees              | VARCHAR   | 47217817620071215,47101399242230360                                |                                                              |
| invariant         | VARCHAR   | 4823965033881218562455                                             |                                                              |
| token\_supply     | VARCHAR   | 4814141483775363070668                                             |                                                              |

## 305. Table: WBETH\_event\_ApplyNewFee\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| fee               | VARCHAR   |                                                              |             |

## 306. Table: WBETH\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-18 08:37:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17505525                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xce859c71039905df62bb1b2e0c8b13e91b027e56ea1ee60b3c2e029641e5f9ce | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 177                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbfab6fa95e0091ed66058ad493189d2cb29385e6                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x989aeb4d175e16225e39e87d0d97a3360524ad80                         |                                                              |
| spender           | VARCHAR   | 0x50161102a240b1456d770dbb55c76d8dc2d160aa                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 307. Table: WBETH\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| new\_fee          | VARCHAR   |                                                              |             |

## 308. Table: WBETH\_event\_RampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| old\_A            | VARCHAR   |                                                              |             |
| new\_A            | VARCHAR   |                                                              |             |
| initial\_time     | VARCHAR   |                                                              |             |
| future\_time      | VARCHAR   |                                                              |             |

## 309. Table: WBETH\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-27 17:38:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17139050                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdb10013cba6cd39049b22e2bdee6b7ef271b498ca756719013d29c8266190b0a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 300                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbfab6fa95e0091ed66058ad493189d2cb29385e6                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xe6da683076b7ed6ce7ec972f21eb8f91e9137a17                         |                                                              |
| token\_amounts    | VARCHAR   | 31426202710297236,23721266788390160                                |                                                              |
| fees              | VARCHAR   | 922587392755,922753188078                                          |                                                              |
| invariant         | VARCHAR   | 268031378759258660                                                 |                                                              |
| token\_supply     | VARCHAR   | 268010624677850050                                                 |                                                              |

## 310. Table: WBETH\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-06 02:37:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17418497                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc84e623d07822c34bde90f3260f3b8f6df4c45b52596102ae6180f8727e7c014 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 366                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbfab6fa95e0091ed66058ad493189d2cb29385e6                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x750aaa6b24f82faf710776a7d0bdea3cfe6cb064                         |                                                              |
| token\_amount     | VARCHAR   | 19686571620836506303                                               |                                                              |
| coin\_amount      | VARCHAR   | 19734132602285589726                                               |                                                              |
| token\_supply     | VARCHAR   | 5297010855037875584228                                             |                                                              |

## 311. Table: WBETH\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-02 10:14:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17826649                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x13790cbbcb77872b4bf5170008da9af70fd0ccb4c1c9ed412ada4bf138f91aa9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 245                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbfab6fa95e0091ed66058ad493189d2cb29385e6                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x188b2d6ac1a8752ea4ef4adb582646f074096aee                         |                                                              |
| token\_amounts    | VARCHAR   | 117398294486825951229,259362513335944898325                        |                                                              |
| fees              | VARCHAR   | 0,0                                                                |                                                              |
| token\_supply     | VARCHAR   | 1749488053055365603138                                             |                                                              |

## 312. Table: WBETH\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 313. Table: WBETH\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-10 08:26:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17448583                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6f098024e3a884614eff0d8564d3203d87de642498e4ae15d19afd5c469df2d2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 60                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbfab6fa95e0091ed66058ad493189d2cb29385e6                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x92f3f71cef740ed5784874b8c70ff87ecdf33588                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 32000000000000000000                                               |                                                              |
| bought\_id        | VARCHAR   | 1                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 31972560404041456989                                               |                                                              |

## 314. Table: WBETH\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-20 01:55:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17517776                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0258fc30e000c43a2ce9d77b237f52903ccbb173fd24939d074ee492d674b6cf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 71                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbfab6fa95e0091ed66058ad493189d2cb29385e6                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x92055df6cf2697af2e89db2398050154e693cbcd                         |                                                              |
| receiver          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 33956529725655539789                                               |                                                              |

## 315. Table: ankrETHSwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-27 18:55:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17352307                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdce8e3c9ee0b9ff50dbeea2d84e7be36bd638c76db3836620af58b3ca8b54d6c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 392                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa96a65c051bf88b4095ee1f2451c2a9d43f53ae2                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xda436db56e7d5d7ceeb20003fc63acd4d8b465ba                         |                                                              |
| token\_amounts    | VARCHAR   | 100000000000000,0                                                  |                                                              |
| fees              | VARCHAR   | 10014251958,8977865926                                             |                                                              |
| invariant         | VARCHAR   | 1678021063505954730249                                             |                                                              |
| token\_supply     | VARCHAR   | 1566820542968129827021                                             |                                                              |

## 316. Table: ankrETHSwap\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-24 12:15:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11919771                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd5b5d0d71a53abdfd1b1caa2a9056b23ca0b94771c072d0a8c31d015490cb056 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 283                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa96a65c051bf88b4095ee1f2451c2a9d43f53ae2                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1614428143                                                         |                                                              |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 317. Table: ankrETHSwap\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| deadline          | VARCHAR   |                                                              |             |
| fee               | VARCHAR   |                                                              |             |
| admin\_fee        | VARCHAR   |                                                              |             |

## 318. Table: ankrETHSwap\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-03 16:45:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11966483                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x35d525b3821c21398b1f67c1b840efc42c37880eb0f7ea577fdd364ff676e9ee | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 149                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa96a65c051bf88b4095ee1f2451c2a9d43f53ae2                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 319. Table: ankrETHSwap\_event\_NewFee\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| fee               | VARCHAR   |                                                              |             |
| admin\_fee        | VARCHAR   |                                                              |             |

## 320. Table: ankrETHSwap\_event\_RampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| old\_A            | VARCHAR   |                                                              |             |
| new\_A            | VARCHAR   |                                                              |             |
| initial\_time     | VARCHAR   |                                                              |             |
| future\_time      | VARCHAR   |                                                              |             |

## 321. Table: ankrETHSwap\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-12 02:27:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17241178                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2a76dc3dd270fccbf476331273f614878690b6609acb3e70f3565b0ef843fec1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 237                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa96a65c051bf88b4095ee1f2451c2a9d43f53ae2                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xdfd85e1cc31340c28fd8102de63b6b09d207c02a                         |                                                              |
| token\_amounts    | VARCHAR   | 14660855690000000000,13393286180000000000                          |                                                              |
| fees              | VARCHAR   | 382831,344489                                                      |                                                              |
| invariant         | VARCHAR   | 1810709855201700001133                                             |                                                              |
| token\_supply     | VARCHAR   | 1692890858518406607860                                             |                                                              |

## 322. Table: ankrETHSwap\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-13 20:56:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13219658                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x56af252230ebb50a4e5ed9f6434678aa94c3be4ed6571d2a6653586e8a4edf8a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 49                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa96a65c051bf88b4095ee1f2451c2a9d43f53ae2                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x4bed4d66b1a17855d60b3cba81905d16d645a817                         |                                                              |
| token\_amount     | VARCHAR   | 11416798566452807692                                               |                                                              |
| coin\_amount      | VARCHAR   | 10871111751448345381                                               |                                                              |

## 323. Table: ankrETHSwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-12 15:49:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12226124                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0daf148c26c773da5731e67ae028b9b2abd122b2e355728440bae8b94407471b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 318                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa96a65c051bf88b4095ee1f2451c2a9d43f53ae2                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xb48aff2979169766a9d4457b05175abdc68ada2c                         |                                                              |
| token\_amounts    | VARCHAR   | 2915737193981847185,7171932530726946578                            |                                                              |
| fees              | VARCHAR   | 0,0                                                                |                                                              |
| token\_supply     | VARCHAR   | 8903369915415980497470                                             |                                                              |

## 324. Table: ankrETHSwap\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 325. Table: ankrETHSwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-16 08:43:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17704742                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1b0344c8d436c48ed0a9ae1da79ea24bfa780cd1fe90eebfd2e3141761e518cf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 151                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa96a65c051bf88b4095ee1f2451c2a9d43f53ae2                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x92f3f71cef740ed5784874b8c70ff87ecdf33588                         |                                                              |
| sold\_id          | VARCHAR   | 1                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 3942577274380945091                                                |                                                              |
| bought\_id        | VARCHAR   | 0                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 4414616515064831725                                                |                                                              |

## 326. Table: bCrv\_contract\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-13 21:01:12+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11850583                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe81b21da760ae471355396088a4a0b2bd87fa762618869df1ab298be02ef4569             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 81                                                                             | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3b3ac5386837dc563660fb6a0937dfaa5924333b                                     | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x862467611d0b5ec4d7616774e51ead3ad58fed0c                                     |                                                              |
| \_spender         | VARCHAR   | 0x2994529c0652d127b7842094103715ec5299bbed                                     |                                                              |
| \_value           | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 327. Table: bCrv\_contract\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-26 19:12:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13303247                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x67fd74f6325f95b36b89703714e85816619665e5496c9296528d4d8812ee9f24 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 19                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3b3ac5386837dc563660fb6a0937dfaa5924333b                         | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0x69fb7c45726cfe2badee8317005d3f94be838840                         |                                                              |
| \_to              | VARCHAR   | 0xad46823600a0e7c7bc2ad7bb04cc20533ca29053                         |                                                              |
| \_value           | VARCHAR   | 162066146534959794443890                                           |                                                              |

## 328. Table: bCrv\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-04 16:53:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14140721                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x13a80c3bc668a13055163b45b67d05441ea3c6d8797dd5fc76bdeb90a7fd5c64 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 175                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3b3ac5386837dc563660fb6a0937dfaa5924333b                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x6a19aea134cc3c6069b2d89b5a1042cabc683cde                         |                                                              |
| \_spender         | VARCHAR   | 0xf403c135812408bfbe8713b5a23a04b3d48aae31                         |                                                              |
| \_value           | VARCHAR   | 407247510143456072600                                              |                                                              |

## 329. Table: bCrv\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-11 04:37:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17234784                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb8dcccf89a473bd3a789e3732f45f1ad92ea46cb4af2b764a18c5e5d7f6e9913 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 249                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3b3ac5386837dc563660fb6a0937dfaa5924333b                         | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0x989aeb4d175e16225e39e87d0d97a3360524ad80                         |                                                              |
| \_to              | VARCHAR   | 0x69fb7c45726cfe2badee8317005d3f94be838840                         |                                                              |
| \_value           | VARCHAR   | 431124505331461082224359                                           |                                                              |

## 330. Table: cCrv\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-26 14:03:18+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11731755                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6a7f443b278af90e4054c61d95fed08b3a63d458074b61e671302e3b2387ab90             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 109                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x845838df265dcd2c412a1dc9e959c7d08537f8a2                                     | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x3cea23ed75ac1515999009ea437d207f85d7e778                                     |                                                              |
| \_spender         | VARCHAR   | 0x629c759d1e83efbf63d84eb3868b564d9521c129                                     |                                                              |
| \_value           | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 331. Table: cCrv\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-04 05:37:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13738065                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x17dde0858102dd2d9ec9a4998bb7a09086cf2ff653ef033c49668d64d7edb107 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 396                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x845838df265dcd2c412a1dc9e959c7d08537f8a2                         | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0x7ca5b0a2910b33e9759dc7ddb0413949071d7575                         |                                                              |
| \_to              | VARCHAR   | 0xac3e2b760232a413171d539c78008cdb7c18ab52                         |                                                              |
| \_value           | VARCHAR   | 632424364438407201123606                                           |                                                              |

## 332. Table: frax\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-07 12:05:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17428383                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x03264bf8c2557784cddfb76e7193780fd208a9dbdb8e6bfc57e402ba2b5fd2ee | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 89                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd632f22692fac7611d2aa1c0d552930d43caed3b                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x7d31cd07af9d02d27f3d4f6591126dca079db992                         |                                                              |
| token\_amounts    | VARCHAR   | 0,7712707184713750946385                                           |                                                              |
| fees              | VARCHAR   | 1079255778217925351,1051309621726900291                            |                                                              |
| invariant         | VARCHAR   | 293668893011007397521333745                                        |                                                              |
| token\_supply     | VARCHAR   | 290698310602200955925125412                                        |                                                              |

## 333. Table: frax\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-16 02:31:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17702913                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6ccb86086e05822e87edc679d7f6952b319bdaa9ce0e107960028490f1ff566a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 78                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd632f22692fac7611d2aa1c0d552930d43caed3b                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x989aeb4d175e16225e39e87d0d97a3360524ad80                         |                                                              |
| spender           | VARCHAR   | 0x72e158d38dbd50a483501c24f792bdaaa3e7d55c                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 334. Table: frax\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| deadline          | VARCHAR   |                                                              |             |
| admin             | VARCHAR   |                                                              |             |

## 335. Table: frax\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| deadline          | VARCHAR   |                                                              |             |
| fee               | VARCHAR   |                                                              |             |
| admin\_fee        | VARCHAR   |                                                              |             |

## 336. Table: frax\_event\_NewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| admin             | VARCHAR   |                                                              |             |

## 337. Table: frax\_event\_NewFee\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| fee               | VARCHAR   |                                                              |             |
| admin\_fee        | VARCHAR   |                                                              |             |

## 338. Table: frax\_event\_RampA\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-09 10:05:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13383889                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x40c225f854d0b47242876575a455330baa3df319014acb9aaa9f68bd58818923 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 255                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd632f22692fac7611d2aa1c0d552930d43caed3b                         | Address of the contract that produced the log                |
| old\_A            | VARCHAR   | 10000                                                              |                                                              |
| new\_A            | VARCHAR   | 50000                                                              |                                                              |
| initial\_time     | VARCHAR   | 1633773936                                                         |                                                              |
| future\_time      | VARCHAR   | 1634659917                                                         |                                                              |

## 339. Table: frax\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-30 06:42:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12733808                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x70a2c23a01bc92d6ddaee156e665036a2c9698c618b2eed17fe260f1699dd0d8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 283                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd632f22692fac7611d2aa1c0d552930d43caed3b                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xa79828df1850e8a3a3064576f380d90aecdd3359                         |                                                              |
| token\_amounts    | VARCHAR   | 0,108072883573320847880912                                         |                                                              |
| fees              | VARCHAR   | 10718023011563133121,10534955332084626588                          |                                                              |
| invariant         | VARCHAR   | 210597268502336007830456671                                        |                                                              |
| token\_supply     | VARCHAR   | 209533162238349151015246941                                        |                                                              |

## 340. Table: frax\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-25 15:08:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13095228                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb80caa27aa8c0bd13f733686ea6f2a4047f3f923b57b5d8b3655d643e1b9f6d3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 359                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd632f22692fac7611d2aa1c0d552930d43caed3b                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xa79828df1850e8a3a3064576f380d90aecdd3359                         |                                                              |
| token\_amount     | VARCHAR   | 993817234913517267                                                 |                                                              |
| coin\_amount      | VARCHAR   | 999614764528441872                                                 |                                                              |
| token\_supply     | VARCHAR   | 321630614601176662412200757                                        |                                                              |

## 341. Table: frax\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-19 23:00:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14993291                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3995cb25a3de61c9db8084ab234bfcbfdd4e4aab9d168b473402ba7aeba8b7f3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 552                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd632f22692fac7611d2aa1c0d552930d43caed3b                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xa79828df1850e8a3a3064576f380d90aecdd3359                         |                                                              |
| token\_amounts    | VARCHAR   | 0,0                                                                |                                                              |
| fees              | VARCHAR   | 0,0                                                                |                                                              |
| token\_supply     | VARCHAR   | 1251479508267305180510917550                                       |                                                              |

## 342. Table: frax\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 343. Table: frax\_event\_TokenExchangeUnderlying\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-31 10:35:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17378298                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x51164210f65243062f6b32c197af274cb95f0242eeb05b14a6212db14b0f626b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 239                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd632f22692fac7611d2aa1c0d552930d43caed3b                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x29c66cf57a03d41cfe6d9ecb6883aa0e2aba21ec                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 31007228199710028539                                               |                                                              |
| bought\_id        | VARCHAR   | 3                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 30963964                                                           |                                                              |

## 344. Table: frax\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-09 16:02:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17223953                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf2c18143f9584ef7a16916a6fdd4a6d3719c4cfb7091aec98418159a6db75fa4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 61                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd632f22692fac7611d2aa1c0d552930d43caed3b                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xb634316e06cc0b358437cbadd4dc94f1d3a92b3b                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 275638837410537934004408                                           |                                                              |
| bought\_id        | VARCHAR   | 1                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 268439778133411104039130                                           |                                                              |

## 345. Table: frax\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-13 10:38:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17250509                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1f126427e4dffc8cbfb05294c95330180e5e75cd5898d48d88be7e738bdcf0a2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 176                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd632f22692fac7611d2aa1c0d552930d43caed3b                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x839bb033738510aa6b4f78af20f066bdc824b189                         |                                                              |
| receiver          | VARCHAR   | 0x631ea73794462cf9bf0a8a7ebf581c062c535b59                         |                                                              |
| value             | VARCHAR   | 3165290680253623540384                                             |                                                              |

## 346. Table: fraxusdc\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-27 17:57:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17572312                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5e6b3951e7d0d8bb00cc7a382c395f4b3cf347caa1cabb4cfbb9c81bf15911a3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 113                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdcef968d416a41cdac0ed8702fac8128a64241a2                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x08780fb7e580e492c1935bee4fa5920b94aa95da                         |                                                              |
| token\_amounts    | VARCHAR   | 376878052006896557150686,284432347659                              |                                                              |
| fees              | VARCHAR   | 3956706794747899006,3953985                                        |                                                              |
| invariant         | VARCHAR   | 618842245991041108448541084                                        |                                                              |
| token\_supply     | VARCHAR   | 618068794040994464757619578                                        |                                                              |

## 347. Table: fraxusdc\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| deadline          | VARCHAR   |                                                              |             |
| admin             | VARCHAR   |                                                              |             |

## 348. Table: fraxusdc\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-18 04:57:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15772748                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0012ef27a491c3ab96150842a6f38a7d68e8c9789a25520e69542353bd4b43a6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 131                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdcef968d416a41cdac0ed8702fac8128a64241a2                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1666328243                                                         |                                                              |
| fee               | VARCHAR   | 1000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 349. Table: fraxusdc\_event\_NewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| admin             | VARCHAR   |                                                              |             |

## 350. Table: fraxusdc\_event\_NewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-31 22:36:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16529833                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8a82d5207fe09755878da71545749e841abcdfb475a49063a6efbf2fb4961365 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 137                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdcef968d416a41cdac0ed8702fac8128a64241a2                         | Address of the contract that produced the log                |
| fee               | VARCHAR   | 1000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 351. Table: fraxusdc\_event\_RampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| old\_A            | VARCHAR   |                                                              |             |
| new\_A            | VARCHAR   |                                                              |             |
| initial\_time     | VARCHAR   |                                                              |             |
| future\_time      | VARCHAR   |                                                              |             |

## 352. Table: fraxusdc\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-16 02:55:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17703033                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa1407b96506a090878d58ae206d627eebd29d933f11b57b59943b83821895d40 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 171                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdcef968d416a41cdac0ed8702fac8128a64241a2                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xba3f5c056500ce033e9d74494b820d495efcf19d                         |                                                              |
| token\_amounts    | VARCHAR   | 0,4515798249                                                       |                                                              |
| fees              | VARCHAR   | 157603363337604767,157486                                          |                                                              |
| invariant         | VARCHAR   | 625935972524696321880256747                                        |                                                              |
| token\_supply     | VARCHAR   | 625147730891869958750462620                                        |                                                              |

## 353. Table: fraxusdc\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-29 07:43:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17363235                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xced39214ea9f68a23a805b5bf3ccbb8b5b60097ccee4d61688177a29b76887a2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 149                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdcef968d416a41cdac0ed8702fac8128a64241a2                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x06a62c6e449ba3026e238e1350c7e25a3d409544                         |                                                              |
| token\_amount     | VARCHAR   | 269681403259176222340397                                           |                                                              |
| coin\_amount      | VARCHAR   | 269881496434                                                       |                                                              |
| token\_supply     | VARCHAR   | 499059380571639578581942063                                        |                                                              |

## 354. Table: fraxusdc\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-25 11:41:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16904246                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe027b8df7193df1e0f451aa0bdd015bb3aa375f21f573836cafd339fa17ab4a0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 247                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdcef968d416a41cdac0ed8702fac8128a64241a2                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x5de4ef4879f4fe3bbadf2227d2ac5d0e2d76c895                         |                                                              |
| token\_amounts    | VARCHAR   | 48548486819536046827688,31605558317                                |                                                              |
| fees              | VARCHAR   | 0,0                                                                |                                                              |
| token\_supply     | VARCHAR   | 486769731446501966786698897                                        |                                                              |

## 355. Table: fraxusdc\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 356. Table: fraxusdc\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-18 02:45:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17717233                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1693042f07313ac1af7c1a157ca7d31b544abb5bb528fd37953961f12d063358 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 380                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdcef968d416a41cdac0ed8702fac8128a64241a2                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x1f409ec6f395493ad39f5b27945f1a6658a23908                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 658305093029740183183                                              |                                                              |
| bought\_id        | VARCHAR   | 1                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 657757552                                                          |                                                              |

## 357. Table: frxeth\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-28 02:07:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17788470                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4c298edfa66fe146c0e0df475ad966d381cc5d77cc32e9362ad26b84e56b721d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 54                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa1f8a6807c402e4a15ef4eba36528a3fed24e577                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xefcc9be27e577513a7d179dca7a64d6d73f3189a                         |                                                              |
| token\_amounts    | VARCHAR   | 3081917578557129791,0                                              |                                                              |
| fees              | VARCHAR   | 195556969942901,195658913015917                                    |                                                              |
| invariant         | VARCHAR   | 85279735672326207933026                                            |                                                              |
| token\_supply     | VARCHAR   | 85180001891127462439838                                            |                                                              |

## 358. Table: frxeth\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-30 11:58:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17371595                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7779013a5fa1e6fd5d765ef2c5161ea2f1647dbb214a8710d7769695ee65c9d6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 146                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa1f8a6807c402e4a15ef4eba36528a3fed24e577                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1685707103                                                         |                                                              |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 359. Table: frxeth\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-02 22:15:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17395938                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf1a187bb457e1bbe41488ef6c240690c9adabcfba591de4e0b10242cc04e6109 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 139                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa1f8a6807c402e4a15ef4eba36528a3fed24e577                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1686003323                                                         |                                                              |
| fee               | VARCHAR   | 2000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 360. Table: frxeth\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-02 22:16:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17395942                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xae5333316342ea35233d198f3cb72408d01de5aa955e20842084575bdf4a18f9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 176                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa1f8a6807c402e4a15ef4eba36528a3fed24e577                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 361. Table: frxeth\_event\_NewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-05 23:40:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17417620                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x465db19584276f75b4d39e25a758739036d1c5b421674144cffb94ab43d28bdc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 193                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa1f8a6807c402e4a15ef4eba36528a3fed24e577                         | Address of the contract that produced the log                |
| fee               | VARCHAR   | 2000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 362. Table: frxeth\_event\_RampA\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-14 02:51:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17042608                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb29addc206cdeab87f72c501b2d6c0302eccddf9e4367f4f8f6e53b64e5683f6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 126                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa1f8a6807c402e4a15ef4eba36528a3fed24e577                         | Address of the contract that produced the log                |
| old\_A            | VARCHAR   | 12000                                                              |                                                              |
| new\_A            | VARCHAR   | 120000                                                             |                                                              |
| initial\_time     | VARCHAR   | 1681440683                                                         |                                                              |
| future\_time      | VARCHAR   | 1682045475                                                         |                                                              |

## 363. Table: frxeth\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-10 05:44:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17015814                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc977e226a6a6966f9fab56fad3c455096f0e0a41fc731a2ead0ffabcefe8582a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 150                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa1f8a6807c402e4a15ef4eba36528a3fed24e577                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x374d5221a4367fe746cc6c92d333c6ce15386fcd                         |                                                              |
| token\_amounts    | VARCHAR   | 973971220000000000,1016890050000000000                             |                                                              |
| fees              | VARCHAR   | 369475,369607                                                      |                                                              |
| invariant         | VARCHAR   | 74933684027829866220836                                            |                                                              |
| token\_supply     | VARCHAR   | 74870063646295693108495                                            |                                                              |

## 364. Table: frxeth\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-13 19:15:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17686590                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd30090d4eba5a27211470fa7e473b410e5f8205447d54304d862b51010c2aa96 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 153                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa1f8a6807c402e4a15ef4eba36528a3fed24e577                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x857ab110153ad57240ab920e93bfb549c045af55                         |                                                              |
| token\_amount     | VARCHAR   | 254931061405432684445                                              |                                                              |
| coin\_amount      | VARCHAR   | 255119248888022548458                                              |                                                              |
| token\_supply     | VARCHAR   | 88155163788125710922328                                            |                                                              |

## 365. Table: frxeth\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-30 21:14:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17808455                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3877b07f3d4a61e5960e62bf41b5e4c4e8e3ed9af5a5e2568bca248a98589dd2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 141                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa1f8a6807c402e4a15ef4eba36528a3fed24e577                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x1ff4289735e5155c4db5c7808f40e586bf6d6f8e                         |                                                              |
| token\_amounts    | VARCHAR   | 127882946450372852,351377482072640791                              |                                                              |
| fees              | VARCHAR   | 0,0                                                                |                                                              |
| token\_supply     | VARCHAR   | 43327472715103946129950                                            |                                                              |

## 366. Table: frxeth\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 367. Table: frxeth\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-08 07:02:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17647432                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x60d1b81e395138449d48b5224e11a66d7f2a1244ea897a1054d9846172848bc2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 163                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa1f8a6807c402e4a15ef4eba36528a3fed24e577                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x23ebcd701fd92867235aeb0174b7c444b9b2b3ad                         |                                                              |
| sold\_id          | VARCHAR   | 1                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 22692900000000000000                                               |                                                              |
| bought\_id        | VARCHAR   | 0                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 22672659412985830880                                               |                                                              |

## 368. Table: gUSDSwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-28 12:15:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17791495                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1fa344a33464fd81c3656101a244ce409c28b5c03ded0b484f9862b23573129e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 165                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f062658eaaf2c1ccf8c8e36d6824cdf41167956                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x64448b78561690b70e17cbe8029a3e5c1bb7136e                         |                                                              |
| token\_amounts    | VARCHAR   | 0,182076264461743340489707                                         |                                                              |
| fees              | VARCHAR   | 1905,18558829050040375403                                          |                                                              |
| invariant         | VARCHAR   | 5255206707544311352946351                                          |                                                              |
| token\_supply     | VARCHAR   | 5064985865786771502316441                                          |                                                              |

## 369. Table: gUSDSwap\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-27 13:37:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11340846                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2496882c3dfa545785a06252337f90ae917aadc0a6e99c804ef6d7bc3c0a5c8d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 154                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f062658eaaf2c1ccf8c8e36d6824cdf41167956                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1606743476                                                         |                                                              |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 370. Table: gUSDSwap\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-18 19:09:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11081748                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3f6ed16ecc37910c676328cbb49bfbecccc0024f5a7765e545ad6c84f40007ef | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 294                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f062658eaaf2c1ccf8c8e36d6824cdf41167956                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1603307393                                                         |                                                              |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 371. Table: gUSDSwap\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-30 17:50:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11361593                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc1af226b8d0a452afdf668aa1f07b30978edbf381acd054714318eccc1b1ba4f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 289                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f062658eaaf2c1ccf8c8e36d6824cdf41167956                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 372. Table: gUSDSwap\_event\_NewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-24 23:53:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11122204                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3fa5bdfdfb8762fab4e1c363fc99e4db90755a95f541ac7173d9151e865d77b7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 32                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f062658eaaf2c1ccf8c8e36d6824cdf41167956                         | Address of the contract that produced the log                |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 373. Table: gUSDSwap\_event\_RampA\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-05 09:30:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14908367                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xea4fae70c97b30e3dc64cb012a1b88382addef116de55581e25728604b7c52d3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 285                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f062658eaaf2c1ccf8c8e36d6824cdf41167956                         | Address of the contract that produced the log                |
| old\_A            | VARCHAR   | 20000                                                              |                                                              |
| new\_A            | VARCHAR   | 100000                                                             |                                                              |
| initial\_time     | VARCHAR   | 1654421422                                                         |                                                              |
| future\_time      | VARCHAR   | 1654944987                                                         |                                                              |

## 374. Table: gUSDSwap\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-18 10:45:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12062172                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x02b8c34068d31d46b2b7d83b5c1ae0da07441bfd96da4da407c5e4829b739159 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f062658eaaf2c1ccf8c8e36d6824cdf41167956                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x662353d1a53c88c85e546d7c4a72ce8fe1018e72                         |                                                              |
| token\_amounts    | VARCHAR   | 0,1394183600000000000000000                                        |                                                              |
| fees              | VARCHAR   | 14221,140154667240323857621                                        |                                                              |
| invariant         | VARCHAR   | 180396718061311758384711561                                        |                                                              |
| token\_supply     | VARCHAR   | 177736805933618630555876529                                        |                                                              |

## 375. Table: gUSDSwap\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-24 00:24:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11916591                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd769b6aea857e1e09675400c3e72d4fd2fd7116a8a78481fb619f962e9cf5738 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 60                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f062658eaaf2c1ccf8c8e36d6824cdf41167956                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x64448b78561690b70e17cbe8029a3e5c1bb7136e                         |                                                              |
| token\_amount     | VARCHAR   | 1469623600851564729917                                             |                                                              |
| coin\_amount      | VARCHAR   | 1469618504370721456750                                             |                                                              |
| token\_supply     | VARCHAR   | 188249707212712821743800735                                        |                                                              |

## 376. Table: gUSDSwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-11 17:36:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14756204                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7ecb68ba5631c97af1fbfc5c1e9de262dba2344ef6544cb6ef29d9fc5febeda2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 28                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f062658eaaf2c1ccf8c8e36d6824cdf41167956                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x64448b78561690b70e17cbe8029a3e5c1bb7136e                         |                                                              |
| token\_amounts    | VARCHAR   | 578629831,7316595154064358623288085                                |                                                              |
| fees              | VARCHAR   | 0,0                                                                |                                                              |
| token\_supply     | VARCHAR   | 27929330551417915059019319                                         |                                                              |

## 377. Table: gUSDSwap\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 378. Table: gUSDSwap\_event\_TokenExchangeUnderlying\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-23 21:45:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17545030                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x385752c64f4631e3c8e4f4c8041ff8cea69faf18afa7fe8c49e49ca4d63fa826 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 217                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f062658eaaf2c1ccf8c8e36d6824cdf41167956                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x99a58482bd75cbab83b27ec03ca68ff489b5788f                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 40000000                                                           |                                                              |
| bought\_id        | VARCHAR   | 3                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 399754367213                                                       |                                                              |

## 379. Table: gUSDSwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-11 20:44:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17672827                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9f989c4cdb79f6a9860d71e7636bcc0396968ee76466ec0c4b66f33c2ac74e6f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 68                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f062658eaaf2c1ccf8c8e36d6824cdf41167956                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xb634316e06cc0b358437cbadd4dc94f1d3a92b3b                         |                                                              |
| sold\_id          | VARCHAR   | 1                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 2888805035895364724135                                             |                                                              |
| bought\_id        | VARCHAR   | 0                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 296311                                                             |                                                              |

## 380. Table: hBTCSwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-15 12:55:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11262540                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbfe4b6632a0a7c45f9bfdafd3fd07c2d7a356268cee5f9ad00c3b62913c8b25b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 230                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4ca9b3063ec5866a4b82e437059d2c43d1be596f                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x0a5774052b59dc2ebcc31549ac529415a07aefb4                         |                                                              |
| token\_amounts    | VARCHAR   | 49950000000000000,0                                                |                                                              |
| fees              | VARCHAR   | 5262379951277,526                                                  |                                                              |
| invariant         | VARCHAR   | 759834034673256266898                                              |                                                              |
| token\_supply     | VARCHAR   | 756550746369929927028                                              |                                                              |

## 381. Table: hBTCSwap\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-27 13:37:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11340846                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2496882c3dfa545785a06252337f90ae917aadc0a6e99c804ef6d7bc3c0a5c8d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 148                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4ca9b3063ec5866a4b82e437059d2c43d1be596f                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1606743476                                                         |                                                              |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 382. Table: hBTCSwap\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-16 19:48:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10875110                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd86f34e988709d22067837467fdb039917967feca9a0959cd3d0e6dd3f823cbc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 232                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4ca9b3063ec5866a4b82e437059d2c43d1be596f                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1600544926                                                         |                                                              |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 383. Table: hBTCSwap\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-24 22:06:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11121729                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1ff24caf209063cc96ba220d986fca98f8da094a8be4cc4d58a80c0bfddc739b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 201                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4ca9b3063ec5866a4b82e437059d2c43d1be596f                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0x56295b752e632f74a6526988eace33c25c52c623                         |                                                              |

## 384. Table: hBTCSwap\_event\_NewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-19 21:38:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10895154                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5665f967b7e8ce027c56677dbca8a8711275c179775539f7ba766effe043595b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 97                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4ca9b3063ec5866a4b82e437059d2c43d1be596f                         | Address of the contract that produced the log                |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 385. Table: hBTCSwap\_event\_RampA\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-05 14:33:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14909631                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5c0142eb2c8170299d7257aadb2fb0e0e03fb4232474ff77ba6eac5a6dd04777 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 121                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4ca9b3063ec5866a4b82e437059d2c43d1be596f                         | Address of the contract that produced the log                |
| old\_A            | VARCHAR   | 300                                                                |                                                              |
| new\_A            | VARCHAR   | 1000                                                               |                                                              |
| initial\_time     | VARCHAR   | 1654439617                                                         |                                                              |
| future\_time      | VARCHAR   | 1655030612                                                         |                                                              |

## 386. Table: hBTCSwap\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-08 09:30:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12593052                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcb93c339c9a7c2448d93a55fd1a204b2f9739bc5cbd908decb20e10417af1406 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 180                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4ca9b3063ec5866a4b82e437059d2c43d1be596f                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x7e8b062d0693ee611ca197f3a5ca412559f4a2f5                         |                                                              |
| token\_amounts    | VARCHAR   | 34999999999999996000,0                                             |                                                              |
| fees              | VARCHAR   | 3343465427237792,334249                                            |                                                              |
| invariant         | VARCHAR   | 12785601669100586480219                                            |                                                              |
| token\_supply     | VARCHAR   | 12701197006420015303050                                            |                                                              |

## 387. Table: hBTCSwap\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-07 13:58:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12978355                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5d9a1435acc26b46d1fe172abc4b0244444e57e1b52492d49e5587d3a7b5a585 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 169                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4ca9b3063ec5866a4b82e437059d2c43d1be596f                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xc255e0a1be0a4b7b8bf5ebe8d0aba162cf75bae2                         |                                                              |
| token\_amount     | VARCHAR   | 995710949659767673                                                 |                                                              |
| coin\_amount      | VARCHAR   | 100188561                                                          |                                                              |

## 388. Table: hBTCSwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-22 12:22:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12289967                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8a1f643726132817ebd707095973d877d8e4b87639a450a833cc9c559f389342 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 193                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4ca9b3063ec5866a4b82e437059d2c43d1be596f                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x5919b3d42bd84e816533c2dd6a7dff7d02303e87                         |                                                              |
| token\_amounts    | VARCHAR   | 3321636525943732129,424478142                                      |                                                              |
| fees              | VARCHAR   | 0,0                                                                |                                                              |
| token\_supply     | VARCHAR   | 8456507888832455342952                                             |                                                              |

## 389. Table: hBTCSwap\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 390. Table: hBTCSwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-06 17:38:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11400578                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5c717068a288f7ea3de0810c4f80da85fbe502d0e39431bda1cc494c8111cd61 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 209                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4ca9b3063ec5866a4b82e437059d2c43d1be596f                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xedf7b675a2fe3c27efb263fb4c204a3f0fb17d46                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 470374634050714844                                                 |                                                              |
| bought\_id        | VARCHAR   | 1                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 47058976                                                           |                                                              |

## 391. Table: hUSDSwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-11 07:25:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13982843                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9331829adfa4dca3f608e96a6fbebe488c2fbd9819c5da3ae9953292f5da5589 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 81                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3ef6a01a0f81d6046290f3e2a8c5b843e738e604                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x09672362833d8f703d5395ef3252d4bfa51c15ca                         |                                                              |
| token\_amounts    | VARCHAR   | 0,2574858273584841835305                                           |                                                              |
| fees              | VARCHAR   | 30468678,298227710949799409                                        |                                                              |
| invariant         | VARCHAR   | 2090303772647359046017567                                          |                                                              |
| token\_supply     | VARCHAR   | 2059881637647958383942082                                          |                                                              |

## 392. Table: hUSDSwap\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-27 13:37:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11340846                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2496882c3dfa545785a06252337f90ae917aadc0a6e99c804ef6d7bc3c0a5c8d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 157                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3ef6a01a0f81d6046290f3e2a8c5b843e738e604                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1606743476                                                         |                                                              |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 393. Table: hUSDSwap\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-18 18:56:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11081683                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5a2324e5ff2767d0ef64b53abdb26dd5befd7248e008592a901a761a30831a76 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 168                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3ef6a01a0f81d6046290f3e2a8c5b843e738e604                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1603306568                                                         |                                                              |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 394. Table: hUSDSwap\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-24 23:49:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11122182                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x166413df55723e906d1b89407f71d0a8c875b8669f70bc127f4e969a07000148 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 70                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3ef6a01a0f81d6046290f3e2a8c5b843e738e604                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0x3f4232107ff437bcd7ea9abc134ad553efeddaff                         |                                                              |

## 395. Table: hUSDSwap\_event\_NewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-24 23:53:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11122204                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3fa5bdfdfb8762fab4e1c363fc99e4db90755a95f541ac7173d9151e865d77b7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 33                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3ef6a01a0f81d6046290f3e2a8c5b843e738e604                         | Address of the contract that produced the log                |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 396. Table: hUSDSwap\_event\_RampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| old\_A            | VARCHAR   |                                                              |             |
| new\_A            | VARCHAR   |                                                              |             |
| initial\_time     | VARCHAR   |                                                              |             |
| future\_time      | VARCHAR   |                                                              |             |

## 397. Table: hUSDSwap\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-31 13:22:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11164893                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfdfb33e1c5a6f66ad65effed128c1f8e3ea259d84bbdc27609f836be6e6c7835 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 211                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3ef6a01a0f81d6046290f3e2a8c5b843e738e604                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x09672362833d8f703d5395ef3252d4bfa51c15ca                         |                                                              |
| token\_amounts    | VARCHAR   | 0,99450241720543216358                                             |                                                              |
| fees              | VARCHAR   | 1249786,12413361570579051                                          |                                                              |
| invariant         | VARCHAR   | 1954930164226207842919149                                          |                                                              |
| token\_supply     | VARCHAR   | 1950299584013075139930767                                          |                                                              |

## 398. Table: hUSDSwap\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-31 05:20:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14876932                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb5b4b518911bea790c87753109d56858128b9967c88ed6e2356474c72c18b0b6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 33                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3ef6a01a0f81d6046290f3e2a8c5b843e738e604                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x09672362833d8f703d5395ef3252d4bfa51c15ca                         |                                                              |
| token\_amount     | VARCHAR   | 952337634786887871576                                              |                                                              |
| coin\_amount      | VARCHAR   | 979729496239195786655                                              |                                                              |
| token\_supply     | VARCHAR   | 282381472663807807095772                                           |                                                              |

## 399. Table: hUSDSwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-27 09:44:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13307069                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa9bb3efa4ed1424d980c1e93e451c1152c92841cc594c0864831376aa5b4c19d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 422                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3ef6a01a0f81d6046290f3e2a8c5b843e738e604                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x09672362833d8f703d5395ef3252d4bfa51c15ca                         |                                                              |
| token\_amounts    | VARCHAR   | 5910394283132,61460904086038323487788                              |                                                              |
| fees              | VARCHAR   | 0,0                                                                |                                                              |
| token\_supply     | VARCHAR   | 1682464159761004103126274                                          |                                                              |

## 400. Table: hUSDSwap\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 401. Table: hUSDSwap\_event\_TokenExchangeUnderlying\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-02 00:39:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12156935                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8b3ca54c7cc22f033a6fe2b0a8de3fbe22e440fe681814c029292927de75cb4f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 162                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3ef6a01a0f81d6046290f3e2a8c5b843e738e604                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xf800d8407b1488bb6dc3789c2d45147c25c38af5                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 1400000000000                                                      |                                                              |
| bought\_id        | VARCHAR   | 2                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 13981880082                                                        |                                                              |

## 402. Table: hUSDSwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-13 09:50:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13409317                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5cd295513fa0aa1c0d9aa6a22fca817a95fc9f5889b689cfb6647c03fe330d3e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 330                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3ef6a01a0f81d6046290f3e2a8c5b843e738e604                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x0f7cd0e51ec3a904cee55098f68ea0c1cb2596dc                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 1564587811                                                         |                                                              |
| bought\_id        | VARCHAR   | 1                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 15364209676841158128                                               |                                                              |

## 403. Table: oBTC\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-16 00:37:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13425864                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0f838d183cc85511c61aa74a124875bd36575221ef69fcb41d9eff72cc04fd0e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 162                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd81da8d904b52208541bade1bd6595d8a251f8dd                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xd5bcf53e2c81e1991570f33fa881c49eea570c8d                         |                                                              |
| token\_amounts    | VARCHAR   | 0,4625500644084586                                                 |                                                              |
| fees              | VARCHAR   | 604230715123,596538310301                                          |                                                              |
| invariant         | VARCHAR   | 2407422216402107202703                                             |                                                              |
| token\_supply     | VARCHAR   | 2397756474343570312660                                             |                                                              |

## 404. Table: oBTC\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| deadline          | VARCHAR   |                                                              |             |
| admin             | VARCHAR   |                                                              |             |

## 405. Table: oBTC\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| deadline          | VARCHAR   |                                                              |             |
| fee               | VARCHAR   |                                                              |             |
| admin\_fee        | VARCHAR   |                                                              |             |

## 406. Table: oBTC\_event\_NewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| admin             | VARCHAR   |                                                              |             |

## 407. Table: oBTC\_event\_NewFee\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| fee               | VARCHAR   |                                                              |             |
| admin\_fee        | VARCHAR   |                                                              |             |

## 408. Table: oBTC\_event\_RampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| old\_A            | VARCHAR   |                                                              |             |
| new\_A            | VARCHAR   |                                                              |             |
| initial\_time     | VARCHAR   |                                                              |             |
| future\_time      | VARCHAR   |                                                              |             |

## 409. Table: oBTC\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-28 09:43:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11945058                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0fb611f8173bea2d1ec754cab95464930a76c3c8858f385d5c00c014bb83b379 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 148                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd81da8d904b52208541bade1bd6595d8a251f8dd                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xd5bcf53e2c81e1991570f33fa881c49eea570c8d                         |                                                              |
| token\_amounts    | VARCHAR   | 2000000000000000000,0                                              |                                                              |
| fees              | VARCHAR   | 145024662953172,143577010395597                                    |                                                              |
| invariant         | VARCHAR   | 531721625897056930533                                              |                                                              |
| token\_supply     | VARCHAR   | 530956581340244833866                                              |                                                              |

## 410. Table: oBTC\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-01 05:12:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16531802                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x29eb33d0dc76b1f46d69d1f88ac5ceb2538858e5961fd7548d9b71fc0797e09c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 347                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd81da8d904b52208541bade1bd6595d8a251f8dd                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xd5bcf53e2c81e1991570f33fa881c49eea570c8d                         |                                                              |
| token\_amount     | VARCHAR   | 40411270710333405                                                  |                                                              |
| coin\_amount      | VARCHAR   | 39808599559166151                                                  |                                                              |
| token\_supply     | VARCHAR   | 15688620419499260311                                               |                                                              |

## 411. Table: oBTC\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-11 07:56:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14563184                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5f96ef9989655b93826f457a963f00fd0c54a39cf3044f21b18657259ee016e9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 313                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd81da8d904b52208541bade1bd6595d8a251f8dd                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xd5bcf53e2c81e1991570f33fa881c49eea570c8d                         |                                                              |
| token\_amounts    | VARCHAR   | 4517240071788080422,3214950083771056501                            |                                                              |
| fees              | VARCHAR   | 0,0                                                                |                                                              |
| token\_supply     | VARCHAR   | 747993434815549239872                                              |                                                              |

## 412. Table: oBTC\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 413. Table: oBTC\_event\_TokenExchangeUnderlying\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-05 23:31:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17417576                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x217dd7370f7873fb09b0dc271b1649770494d4941a09d657abbbd8794b59bbc0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 66                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd81da8d904b52208541bade1bd6595d8a251f8dd                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x0000000000a84d1a9b0063a910315c7ffa9cd248                         |                                                              |
| sold\_id          | VARCHAR   | 2                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 3792022                                                            |                                                              |
| bought\_id        | VARCHAR   | 0                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 37911640395218728                                                  |                                                              |

## 414. Table: oBTC\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-22 19:07:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12291790                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x52e4087f53de6868d7e32afa0d17fc423a5adeeda4a442c1ce517ff59edee7b0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 350                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd81da8d904b52208541bade1bd6595d8a251f8dd                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x9f19a0adc27f7d901e8d2b9b0ccb0d862b72fd7d                         |                                                              |
| sold\_id          | VARCHAR   | 1                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 4089751045974630003                                                |                                                              |
| bought\_id        | VARCHAR   | 0                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 4128223631587163747                                                |                                                              |

## 415. Table: pBTCSwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-27 06:01:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11937618                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcd55b0f1c6e1996d8ea2f529fd58a3a3804af70622761607a071f13136c44532 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 146                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7f55dde206dbad629c080068923b36fe9d6bdbef                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x11f419adabbff8d595e7d5b223eee3863bb3902c                         |                                                              |
| token\_amounts    | VARCHAR   | 0,2474275404924468107                                              |                                                              |
| fees              | VARCHAR   | 263095218271721,261169836242968                                    |                                                              |
| invariant         | VARCHAR   | 350651085744064026968                                              |                                                              |
| token\_supply     | VARCHAR   | 350040428266454844135                                              |                                                              |

## 416. Table: pBTCSwap\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| deadline          | VARCHAR   |                                                              |             |
| admin             | VARCHAR   |                                                              |             |

## 417. Table: pBTCSwap\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| deadline          | VARCHAR   |                                                              |             |
| fee               | VARCHAR   |                                                              |             |
| admin\_fee        | VARCHAR   |                                                              |             |

## 418. Table: pBTCSwap\_event\_NewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| admin             | VARCHAR   |                                                              |             |

## 419. Table: pBTCSwap\_event\_NewFee\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| fee               | VARCHAR   |                                                              |             |
| admin\_fee        | VARCHAR   |                                                              |             |

## 420. Table: pBTCSwap\_event\_RampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| old\_A            | VARCHAR   |                                                              |             |
| new\_A            | VARCHAR   |                                                              |             |
| initial\_time     | VARCHAR   |                                                              |             |
| future\_time      | VARCHAR   |                                                              |             |

## 421. Table: pBTCSwap\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-23 12:02:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11913175                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9f4c975a4f62d33a9772b0928bb587282d45ccaf40ec01bd8c83e0ca533c4bf8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 169                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7f55dde206dbad629c080068923b36fe9d6bdbef                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x11f419adabbff8d595e7d5b223eee3863bb3902c                         |                                                              |
| token\_amounts    | VARCHAR   | 0,992271751740276906                                               |                                                              |
| fees              | VARCHAR   | 114997659693946,114038021498357                                    |                                                              |
| invariant         | VARCHAR   | 295027480631158134935                                              |                                                              |
| token\_supply     | VARCHAR   | 294530046551899372071                                              |                                                              |

## 422. Table: pBTCSwap\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-26 18:19:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13102599                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x77b19d040bcf8b066e2d3b0c832fb31e35400f1c94667875dca7bc802d568e25 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 318                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7f55dde206dbad629c080068923b36fe9d6bdbef                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x11f419adabbff8d595e7d5b223eee3863bb3902c                         |                                                              |
| token\_amount     | VARCHAR   | 9954652318718622656                                                |                                                              |
| coin\_amount      | VARCHAR   | 9900086209167078400                                                |                                                              |
| token\_supply     | VARCHAR   | 4141073154264623503939                                             |                                                              |

## 423. Table: pBTCSwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-09 10:24:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14932101                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfb0798a8005a4c2694a121c8ee4a559f68c083827ec55ef3fe986ee9c25219dc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 105                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7f55dde206dbad629c080068923b36fe9d6bdbef                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x11f419adabbff8d595e7d5b223eee3863bb3902c                         |                                                              |
| token\_amounts    | VARCHAR   | 256240172729750396,232672941794466923                              |                                                              |
| fees              | VARCHAR   | 0,0                                                                |                                                              |
| token\_supply     | VARCHAR   | 105702383881356005782                                              |                                                              |

## 424. Table: pBTCSwap\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 425. Table: pBTCSwap\_event\_TokenExchangeUnderlying\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-04 12:16:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16555357                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x76761eaafd9fad00ddf2a87217be85550f30735610194bf2c49edb8546c05f97 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 35                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7f55dde206dbad629c080068923b36fe9d6bdbef                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x24902aa0cf0000a08c0ea0b003b0c0bf600000e0                         |                                                              |
| sold\_id          | VARCHAR   | 2                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 5191088                                                            |                                                              |
| bought\_id        | VARCHAR   | 0                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 51295957868473846                                                  |                                                              |

## 426. Table: pBTCSwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-11 11:57:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15320569                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfd4504f44982ab7812e1b1a24da9f4964b5ecfe11c4daa7768226abc24cfbac2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 27                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7f55dde206dbad629c080068923b36fe9d6bdbef                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x04eb85ad427e7e6b3ffb67e049872210fd3fbae9                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 315119711254983246                                                 |                                                              |
| bought\_id        | VARCHAR   | 1                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 309584532518695922                                                 |                                                              |

## 427. Table: pCrv\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-29 17:59:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11355102                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x340cd75bf6c7cad96450cf9404fa4550f1b6b6c231a1bb56ca3d333647c6c4f5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 117                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd905e2eaebe188fc92179b6350807d8bd91db0d8                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0xd39b6849d2e1db20bab50dd7a4f3e0882c744404                         |                                                              |
| \_spender         | VARCHAR   | 0x64e3c23bfc40722d3b649844055f1d51c1ac041d                         |                                                              |
| \_value           | VARCHAR   | 5850469010054043297825                                             |                                                              |

## 428. Table: pCrv\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-21 00:09:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11695513                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x12dc79bd53d74ca0421afbab6d96f77748c8a919b6e5f5501c10bf7075595033 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 60                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd905e2eaebe188fc92179b6350807d8bd91db0d8                         | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0xa50ccc70b6a011cffddf45057e39679379187287                         |                                                              |
| \_to              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_value           | VARCHAR   | 110408306901689833010674                                           |                                                              |

## 429. Table: renCrv\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-10 12:31:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11027710                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4de95fd111311d5439eec40a140cc310c519fad22ac8df683bcfc5e0651ee7a6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 43                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x49849c98ae39fff122806c06791fa73784fb3675                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x001f60f22baf29dc6bb292de9071d887d986a287                         |                                                              |
| \_spender         | VARCHAR   | 0x1eb47c01cfab26d2346b449975b7bf20a34e0d45                         |                                                              |
| \_value           | VARCHAR   | 29666000000000000000                                               |                                                              |

## 430. Table: renCrv\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-25 22:44:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17339201                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x884b6a0b5222ddeaaf6241b243d21e96c06952203e1e34cc85f96bc84d7f3b28 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 430                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x49849c98ae39fff122806c06791fa73784fb3675                         | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0x0d313261953f41037ff6b2a03749d7056ea93cac                         |                                                              |
| \_to              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_value           | VARCHAR   | 8853044429276115                                                   |                                                              |

## 431. Table: sAAVESwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-25 11:53:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12309303                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdfbe41ec9befe630e6ba7ceee3da6985aea008fd42d686647c7538898ff72107 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 282                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeb16ae0052ed37f479f7fe63849198df1765a733                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x05296c03e59bb7a2fb0920e47a18044bab1ff632                         |                                                              |
| token\_amounts    | VARCHAR   | 0,210068652021448260504                                            |                                                              |
| fees              | VARCHAR   | 32027574394843923,32537962151295267                                |                                                              |
| invariant         | VARCHAR   | 22441137293286147700393563                                         |                                                              |
| token\_supply     | VARCHAR   | 21872743652142554355078639                                         |                                                              |

## 432. Table: sAAVESwap\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-24 12:15:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11919771                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xec54c874e8179bc83d67003b7060236f0a1a313e148e521eccc9d2f92502bcbd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 286                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeb16ae0052ed37f479f7fe63849198df1765a733                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1614428143                                                         |                                                              |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 433. Table: sAAVESwap\_event\_CommitNewFee\_history

| Column                  | Type      | Example                                                      | Description |
| ----------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp        | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number           | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash       | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index              | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address       | VARCHAR   | Address of the contract that produced the log                |             |
| deadline                | VARCHAR   |                                                              |             |
| fee                     | VARCHAR   |                                                              |             |
| admin\_fee              | VARCHAR   |                                                              |             |
| offpeg\_fee\_multiplier | VARCHAR   |                                                              |             |

## 434. Table: sAAVESwap\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-03 16:45:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11966483                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x141be2d15dbbbc9b7009b0deeb376a15f46cac0a8a269c8f0952dcbe34a39a86 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 148                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeb16ae0052ed37f479f7fe63849198df1765a733                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 435. Table: sAAVESwap\_event\_NewFee\_history

| Column                  | Type      | Example                                                      | Description |
| ----------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp        | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number           | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash       | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index              | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address       | VARCHAR   | Address of the contract that produced the log                |             |
| fee                     | VARCHAR   |                                                              |             |
| admin\_fee              | VARCHAR   |                                                              |             |
| offpeg\_fee\_multiplier | VARCHAR   |                                                              |             |

## 436. Table: sAAVESwap\_event\_RampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| old\_A            | VARCHAR   |                                                              |             |
| new\_A            | VARCHAR   |                                                              |             |
| initial\_time     | VARCHAR   |                                                              |             |
| future\_time      | VARCHAR   |                                                              |             |

## 437. Table: sAAVESwap\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-11 07:23:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12804654                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x81050f9a6212ace682e3b1af02f4470386b49bb1bff7613adc5a7e6da50c1319 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 166                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeb16ae0052ed37f479f7fe63849198df1765a733                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xa9f077abbebf343b66f967bd55e436d94e6400d8                         |                                                              |
| token\_amounts    | VARCHAR   | 10000000000000000000000,0                                          |                                                              |
| fees              | VARCHAR   | 786572798023933153,784929990652253596                              |                                                              |
| invariant         | VARCHAR   | 154937995679856992781028150                                        |                                                              |
| token\_supply     | VARCHAR   | 149474614282449515267211598                                        |                                                              |

## 438. Table: sAAVESwap\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-16 11:53:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17705675                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcfe9c25ae2eae30b6907bb70b6aae25c2930dbcad7b01894412da45b5b07caff | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 206                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeb16ae0052ed37f479f7fe63849198df1765a733                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x5d0c2cb547df7e52e18ee2e237729bc7fcc56d8e                         |                                                              |
| token\_amount     | VARCHAR   | 3768464024654860151212                                             |                                                              |
| coin\_amount      | VARCHAR   | 4124782993924208976250                                             |                                                              |

## 439. Table: sAAVESwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-13 21:44:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12821258                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x05e63cffcfca71e16ead52c83110c11514f5a5fc1201083ca14e1f545ecc0058 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 156                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeb16ae0052ed37f479f7fe63849198df1765a733                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x0ec4b6689d848c5138fb1f039064af8de6ba6551                         |                                                              |
| token\_amounts    | VARCHAR   | 42839422344228403650910,37117482304446145446998                    |                                                              |
| fees              | VARCHAR   | 0,0                                                                |                                                              |
| token\_supply     | VARCHAR   | 145519876318801466451007816                                        |                                                              |

## 440. Table: sAAVESwap\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 441. Table: sAAVESwap\_event\_TokenExchangeUnderlying\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-19 08:42:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16860650                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5f120fa597b91e4a9d738ae44a90aa8b07c74f746e13c5df7f65cdfce0a36bd0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 89                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeb16ae0052ed37f479f7fe63849198df1765a733                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xdef171fe48cf0115b1d80b88dc8eab59176fee57                         |                                                              |
| sold\_id          | VARCHAR   | 1                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 29101874554977915998439                                            |                                                              |
| bought\_id        | VARCHAR   | 0                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 29248549247934154728025                                            |                                                              |

## 442. Table: sAAVESwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-05 04:45:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14324835                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x05a10de6eca38a6601783aca19c85efb6953b600c3d6ce4a52365f1aa77a7a6f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 65                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeb16ae0052ed37f479f7fe63849198df1765a733                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xeef86c2e49e11345f1a693675df9a38f7d880c8f                         |                                                              |
| sold\_id          | VARCHAR   | 1                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 329236865722614634770536                                           |                                                              |
| bought\_id        | VARCHAR   | 0                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 329748329011036840237199                                           |                                                              |

## 443. Table: sBTCCurveExchangeAdapter2\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-04 03:38:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10390553                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x025e33eb80443820a3213b9b5599df9cacd17f3e147172e6b29e49fe863f9c96 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 54                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x02b3f51ac9202aa19be63d61a8c681579d6e3a51                         | Address of the contract that produced the log                |
| burnAmount        | VARCHAR   | 551218223                                                          |                                                              |

## 444. Table: sBTCCurveExchangeAdapter2\_event\_DepositMintedCurve\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-25 20:26:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10337115                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf6f579caa984e17c2747e1417fb017a412c6a8bbb67e560a35b8032dfa9b9f83 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 122                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x02b3f51ac9202aa19be63d61a8c681579d6e3a51                         | Address of the contract that produced the log                |
| mintedAmount      | VARCHAR   | 9955035                                                            |                                                              |
| curveAmount       | VARCHAR   | 99027616523467969                                                  |                                                              |
| amounts           | VARCHAR   | 9955035,0,0                                                        |                                                              |

## 445. Table: sBTCCurveExchangeAdapter2\_event\_ReceiveRen\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-07 02:07:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10409565                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x32bfe0b3adde17b147fe2577f05c41a430c677e51c90a4b468ba424cccdb5161 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 144                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x02b3f51ac9202aa19be63d61a8c681579d6e3a51                         | Address of the contract that produced the log                |
| renAmount         | VARCHAR   | 368253                                                             |                                                              |

## 446. Table: sBTCCurveExchangeAdapter2\_event\_SwapReceived\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-26 23:43:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10344441                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcc0668bf4f73d6994907048e11ffe7174a1fb9268d41b0687088f0000050f9c7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 68                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x02b3f51ac9202aa19be63d61a8c681579d6e3a51                         | Address of the contract that produced the log                |
| mintedAmount      | VARCHAR   | 2962035                                                            |                                                              |
| erc20BTCAmount    | VARCHAR   | 2947608                                                            |                                                              |
| j                 | VARCHAR   | 1                                                                  |                                                              |

## 447. Table: sBTCCurveExchangeAdapter\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-26 05:40:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10339578                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfc8b982d4799560beabdd0e6054cee6c29bb3fd50a643e163ea2ceeee852c791 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 64                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x104c1e66c67c385e6095ffcc6227d75c761dc019                         | Address of the contract that produced the log                |
| burnAmount        | VARCHAR   | 64831776                                                           |                                                              |

## 448. Table: sBTCCurveExchangeAdapter\_event\_DepositMintedCurve\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-22 21:55:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10318122                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe156debe7e2f1664460056d0be0013aaa77982d64f2362662de97ed2bec3f8e8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 79                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x104c1e66c67c385e6095ffcc6227d75c761dc019                         | Address of the contract that produced the log                |
| mintedAmount      | VARCHAR   | 4995                                                               |                                                              |
| curveAmount       | VARCHAR   | 112339446996442                                                    |                                                              |
| amounts           | VARCHAR   | 4995,0,62761764476468                                              |                                                              |

## 449. Table: sBTCCurveExchangeAdapter\_event\_ReceiveRen\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-25 14:30:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10335472                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x82c7acc0393f9718a26828e5162df975ea3efed97a10d6b440c15430150d1b7f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 78                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x104c1e66c67c385e6095ffcc6227d75c761dc019                         | Address of the contract that produced the log                |
| renAmount         | VARCHAR   | 64935                                                              |                                                              |

## 450. Table: sBTCCurveExchangeAdapter\_event\_RelayHubChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldRelayHub       | VARCHAR   |                                                              |             |
| newRelayHub       | VARCHAR   |                                                              |             |

## 451. Table: sBTCCurveExchangeAdapter\_event\_SwapReceived\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-25 12:59:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10335046                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x31688efd87884c9219d4e60b88e99cef4a3acf2439e760acd927d127dcce7935 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 59                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x104c1e66c67c385e6095ffcc6227d75c761dc019                         | Address of the contract that produced the log                |
| mintedAmount      | VARCHAR   | 1963035                                                            |                                                              |
| erc20BTCAmount    | VARCHAR   | 19481928572263336                                                  |                                                              |
| j                 | VARCHAR   | 2                                                                  |                                                              |

## 452. Table: sBTCSwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-07 19:08:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16578889                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x33d2ac6a0fd15af8a226077a16ff0d9e7ab420986b4ba0b34b5ddb767772c1ac | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 187                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7fc77b5c7614e1533320ea6ddc2eb61fa00a9714                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x071c661b4deefb59e2a3ddb20db036821eee8f4b                         |                                                              |
| token\_amounts    | VARCHAR   | 0,19945889,0                                                       |                                                              |
| fees              | VARCHAR   | 278,1527,12309681662700                                            |                                                              |
| invariant         | VARCHAR   | 286051759535255116503                                              |                                                              |
| token\_supply     | VARCHAR   | 280721914465366843735                                              |                                                              |

## 453. Table: sBTCSwap\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-20 00:30:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11089752                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc7c98d20ae79e3907e69262eea57f034726074e57eb7c802a3e834df03d24ba5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 163                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7fc77b5c7614e1533320ea6ddc2eb61fa00a9714                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1603413000                                                         |                                                              |
| admin             | VARCHAR   | 0x56295b752e632f74a6526988eace33c25c52c623                         |                                                              |

## 454. Table: sBTCSwap\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-16 19:48:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10875110                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd86f34e988709d22067837467fdb039917967feca9a0959cd3d0e6dd3f823cbc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 229                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7fc77b5c7614e1533320ea6ddc2eb61fa00a9714                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1600544926                                                         |                                                              |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 455. Table: sBTCSwap\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-24 07:02:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10721588                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa8087c87628f2047bd0aaf7e0307bd89613db8a82871f484c00114fcfe2df4d5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 109                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7fc77b5c7614e1533320ea6ddc2eb61fa00a9714                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0x6e8f6d1da6232d5e40b0b8758a0145d6c5123eb7                         |                                                              |

## 456. Table: sBTCSwap\_event\_NewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-19 21:38:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10895154                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5665f967b7e8ce027c56677dbca8a8711275c179775539f7ba766effe043595b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 96                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7fc77b5c7614e1533320ea6ddc2eb61fa00a9714                         | Address of the contract that produced the log                |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 457. Table: sBTCSwap\_event\_RampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| old\_A            | VARCHAR   |                                                              |             |
| new\_A            | VARCHAR   |                                                              |             |
| initial\_time     | VARCHAR   |                                                              |             |
| future\_time      | VARCHAR   |                                                              |             |

## 458. Table: sBTCSwap\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-23 00:13:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10512391                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xed017635bc96b4ecc7e30e27b7b8e02e2eb53072089bd3d462c0162c45b10571 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 38                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7fc77b5c7614e1533320ea6ddc2eb61fa00a9714                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x6af19757df4d223d285eb116ad4603126580eefb                         |                                                              |
| token\_amounts    | VARCHAR   | 37800000,0,0                                                       |                                                              |
| fees              | VARCHAR   | 4022,1297,27340572264853                                           |                                                              |
| invariant         | VARCHAR   | 2584169019997549239472                                             |                                                              |
| token\_supply     | VARCHAR   | 2577258250344936959995                                             |                                                              |

## 459. Table: sBTCSwap\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-01 13:39:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17386313                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf3aae7371a4051068912531d289da0955fff197a6799fa89ffdbe970037454e7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 239                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7fc77b5c7614e1533320ea6ddc2eb61fa00a9714                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x7f55dde206dbad629c080068923b36fe9d6bdbef                         |                                                              |
| token\_amount     | VARCHAR   | 67362661842194197                                                  |                                                              |
| coin\_amount      | VARCHAR   | 6921730                                                            |                                                              |

## 460. Table: sBTCSwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-19 21:55:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10693102                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x734eb317a67f052eb611e528631872d977438cfe25c14471fa9529c6d1c446c7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 56                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7fc77b5c7614e1533320ea6ddc2eb61fa00a9714                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xfe87f5d8b3e4ba2a54290cbd8b1025608dab5729                         |                                                              |
| token\_amounts    | VARCHAR   | 0,0,0                                                              |                                                              |
| fees              | VARCHAR   | 0,0,0                                                              |                                                              |
| token\_supply     | VARCHAR   | 16672109754970532212866                                            |                                                              |

## 461. Table: sBTCSwap\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 462. Table: sBTCSwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-10 17:05:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16155686                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcf0204703b590b747115868fc9021b242a7f7e9a7f7400f2f7ac482eb4c9fafc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 37                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7fc77b5c7614e1533320ea6ddc2eb61fa00a9714                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xd8c07491caa1edf960db3ceff387426d53942ea0                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 58976453                                                           |                                                              |
| bought\_id        | VARCHAR   | 1                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 59689586                                                           |                                                              |

## 463. Table: sCrv\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-02 01:40:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17824095                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3cd510490dd23bb1220109681600bd76d4cae5a2a9026cc7a937a19aa40523e3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 167                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc25a3a3b969415c80451098fa907ec722572917f                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x85ad7a2085d391af549a4413b84bd9fa38ed201a                         |                                                              |
| \_spender         | VARCHAR   | 0x9700e0b9d22fe10ff00170462c98abffa2505de2                         |                                                              |
| \_value           | VARCHAR   | 0                                                                  |                                                              |

## 464. Table: sCrv\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-13 11:44:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17250837                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1953ddcf381d6813c8149cc4fa691845d132df59f994325e769f4e6b0738528e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 209                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc25a3a3b969415c80451098fa907ec722572917f                         | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_to              | VARCHAR   | 0xfcba3e75865d2d561be8d220616520c171f12851                         |                                                              |
| \_value           | VARCHAR   | 908878895790372                                                    |                                                              |

## 465. Table: sETHSwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-16 03:04:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13234220                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8456f66b3b58980e9ffc216394602d2812b83c64daf78f38928005b6f0f2024a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 81                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc5424b857f758e906013f3555dad202e4bdb4567                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x07c9aa769a0c86c69e9c1f4cdc19ef55e0fd1abe                         |                                                              |
| token\_amounts    | VARCHAR   | 19800000000000000000,0                                             |                                                              |
| fees              | VARCHAR   | 1635592395524097,1633229476450690                                  |                                                              |
| invariant         | VARCHAR   | 191742124433369141542381                                           |                                                              |
| token\_supply     | VARCHAR   | 190620880423103798870792                                           |                                                              |

## 466. Table: sETHSwap\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| deadline          | VARCHAR   |                                                              |             |
| admin             | VARCHAR   |                                                              |             |

## 467. Table: sETHSwap\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-10 09:53:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16153534                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc34a24063a4d058cedd57300a6b946bda79b20e03aa6c6d95da748c168994049 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 116                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc5424b857f758e906013f3555dad202e4bdb4567                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1670925239                                                         |                                                              |
| fee               | VARCHAR   | 2000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 468. Table: sETHSwap\_event\_NewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| admin             | VARCHAR   |                                                              |             |

## 469. Table: sETHSwap\_event\_NewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-13 10:03:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16175063                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x971a25b98715bae9fc2b124d4adc8dca4d4b9da9ce0e0651cfdd83fe867e3fea | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 114                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc5424b857f758e906013f3555dad202e4bdb4567                         | Address of the contract that produced the log                |
| fee               | VARCHAR   | 2000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 470. Table: sETHSwap\_event\_RampA\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-02 17:00:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12947123                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x63cabda348223b1c6cf7110a803496aa9f5629ceb16f3b95a7c7948c4eb7c81b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 80                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc5424b857f758e906013f3555dad202e4bdb4567                         | Address of the contract that produced the log                |
| old\_A            | VARCHAR   | 10000                                                              |                                                              |
| new\_A            | VARCHAR   | 25600                                                              |                                                              |
| initial\_time     | VARCHAR   | 1627923611                                                         |                                                              |
| future\_time      | VARCHAR   | 1628525830                                                         |                                                              |

## 471. Table: sETHSwap\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-24 06:08:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14267073                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4fcbfad6b0203799661575728469834f5f8d3c55848aafc6719fc6587d430b8b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 66                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc5424b857f758e906013f3555dad202e4bdb4567                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x6dd0feeee8a2057a4c58183fa3060763f7f84ce6                         |                                                              |
| token\_amounts    | VARCHAR   | 50000000000000000000,0                                             |                                                              |
| fees              | VARCHAR   | 4298416376604306,4293538754223585                                  |                                                              |
| invariant         | VARCHAR   | 34624935351226958904680                                            |                                                              |
| token\_supply     | VARCHAR   | 34375448594656296855079                                            |                                                              |

## 472. Table: sETHSwap\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-09 16:55:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17224209                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x037de832b70bf642525f8c8305928200933ee1ceb323c4e31d596c7d06030761 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 274                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc5424b857f758e906013f3555dad202e4bdb4567                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x316be293c8f2380769e7b7e7382679fe5a3b6600                         |                                                              |
| token\_amount     | VARCHAR   | 44190000000000000000                                               |                                                              |
| coin\_amount      | VARCHAR   | 45037056364825197412                                               |                                                              |

## 473. Table: sETHSwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-26 12:40:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17343326                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd0df62562e50d0aed85026deffaeeedf47178a929794f74a4f77b20a9494cad8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 131                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc5424b857f758e906013f3555dad202e4bdb4567                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x7113fbdc1c6ef083a72ba152b446b10654e4e05e                         |                                                              |
| token\_amounts    | VARCHAR   | 131626847309571544420,103176054264062989974                        |                                                              |
| fees              | VARCHAR   | 0,0                                                                |                                                              |
| token\_supply     | VARCHAR   | 20147155451921768229213                                            |                                                              |

## 474. Table: sETHSwap\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 475. Table: sETHSwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-06 07:38:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14531051                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb8b430d37aeff7c8cf859a028b70efa9504d53e3a31bfad71fbb5f7014a69e3e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc5424b857f758e906013f3555dad202e4bdb4567                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x220bda5c8994804ac96ebe4df184d25e5c2196d4                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 298000000000000000000                                              |                                                              |
| bought\_id        | VARCHAR   | 1                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 297971412439975420573                                              |                                                              |

## 476. Table: sUSDSwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-02 09:09:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17172108                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3a1955d845975733f90b4aa6db307fcb5a747b90f3b365c3b732e5d27bbcf1c6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 427                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa5407eae9ba41422680e2e00537571bcc53efbfd                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xfcba3e75865d2d561be8d220616520c171f12851                         |                                                              |
| token\_amounts    | VARCHAR   | 0,36151353,0,0                                                     |                                                              |
| fees              | VARCHAR   | 675904282159603,1747,599,471587882830116                           |                                                              |
| invariant         | VARCHAR   | 54023789887815675255892920                                         |                                                              |
| token\_supply     | VARCHAR   | 50766776680689553068479459                                         |                                                              |

## 477. Table: sUSDSwap\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-27 13:37:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11340846                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2496882c3dfa545785a06252337f90ae917aadc0a6e99c804ef6d7bc3c0a5c8d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 133                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa5407eae9ba41422680e2e00537571bcc53efbfd                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1606743476                                                         |                                                              |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 478. Table: sUSDSwap\_event\_CommitNewParameters\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-10 05:10:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16152127                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x91f0d7096da1937b872538e140164f83e9b05a364d5aab46296ca2fbaba827a8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 182                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa5407eae9ba41422680e2e00537571bcc53efbfd                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1670908259                                                         |                                                              |
| A                 | VARCHAR   | 256                                                                |                                                              |
| fee               | VARCHAR   | 2000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 479. Table: sUSDSwap\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-30 18:07:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11361652                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe10be30663abc689bb9e60ea2a65aca9f188e15c80c641e99451007503d157b2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 208                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa5407eae9ba41422680e2e00537571bcc53efbfd                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 480. Table: sUSDSwap\_event\_NewParameters\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-19 21:38:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10895154                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5665f967b7e8ce027c56677dbca8a8711275c179775539f7ba766effe043595b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 93                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa5407eae9ba41422680e2e00537571bcc53efbfd                         | Address of the contract that produced the log                |
| A                 | VARCHAR   | 100                                                                |                                                              |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 481. Table: sUSDSwap\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-25 09:40:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17769283                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbb2801678b0b597b82242c8834fbaecf1c51bc9cf557afcbe3517e27906b083d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 229                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa5407eae9ba41422680e2e00537571bcc53efbfd                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xfcba3e75865d2d561be8d220616520c171f12851                         |                                                              |
| token\_amounts    | VARCHAR   | 0,0,4055478138,0                                                   |                                                              |
| fees              | VARCHAR   | 69528613280109759,67946,201844,64355052680502855                   |                                                              |
| invariant         | VARCHAR   | 30936956837627040449930040                                         |                                                              |
| token\_supply     | VARCHAR   | 29054013087534846357675713                                         |                                                              |

## 482. Table: sUSDSwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-03 12:49:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17834578                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8b28bb13e4727f0ee1fced3ed7aa34f582fd7d37b648e900b7bd0ced32a1c3fb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 180                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa5407eae9ba41422680e2e00537571bcc53efbfd                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xc45aaca1ba883b5459f242a3290acc2586a4bbe8                         |                                                              |
| token\_amounts    | VARCHAR   | 27340401378987911235,26725573,33837902,29171931426939509514        |                                                              |
| fees              | VARCHAR   | 0,0,0,0                                                            |                                                              |
| token\_supply     | VARCHAR   | 26009806012349157344299414                                         |                                                              |

## 483. Table: sUSDSwap\_event\_TokenExchangeUnderlying\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-11 14:17:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11634107                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2a552d71317f63530e5a023ff10494c89719e6e59a328eb58fa5528f619a7f6c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 22                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa5407eae9ba41422680e2e00537571bcc53efbfd                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x00000063f648c943346d2a239f0969bad32ff184                         |                                                              |
| sold\_id          | VARCHAR   | 2                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 100314174412                                                       |                                                              |
| bought\_id        | VARCHAR   | 0                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 100195902521784644751896                                           |                                                              |

## 484. Table: sUSDSwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-28 14:57:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10154891                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xee2f7272a1b5a30de73a6414150e944c1b035662df4163466531a8d5bf77d12c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 85                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa5407eae9ba41422680e2e00537571bcc53efbfd                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x6517e7592d28927e7ba4f03ab54079b527d6739d                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 1450000000000000000000                                             |                                                              |
| bought\_id        | VARCHAR   | 1                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 1452511359                                                         |                                                              |

## 485. Table: sbtc2\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-07 23:06:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17431640                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfe050e8d9a1f3c84565e4b97109993e1307ed7402d2b9bb34d87753045d97a84 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 74                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf253f83aca21aabd2a20553ae0bf7f65c755a07f                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xf95aaa7ebb1620e46221b73588502960ef63dba0                         |                                                              |
| token\_amounts    | VARCHAR   | 113156250,0                                                        |                                                              |
| fees              | VARCHAR   | 10814,108050206757438                                              |                                                              |
| invariant         | VARCHAR   | 543007048334380819588                                              |                                                              |
| token\_supply     | VARCHAR   | 541996314909537819637                                              |                                                              |

## 486. Table: sbtc2\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-02 22:08:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16100005                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7a5d842549babc798ce340ae32b0a97776ff1cf9441c179d314ea07e77d3463e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 327                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf253f83aca21aabd2a20553ae0bf7f65c755a07f                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1670278091                                                         |                                                              |
| admin             | VARCHAR   | 0xbabe61887f1de2713c6f97e567623453d3c79f67                         |                                                              |

## 487. Table: sbtc2\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| deadline          | VARCHAR   |                                                              |             |
| fee               | VARCHAR   |                                                              |             |
| admin\_fee        | VARCHAR   |                                                              |             |

## 488. Table: sbtc2\_event\_NewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| admin             | VARCHAR   |                                                              |             |

## 489. Table: sbtc2\_event\_NewFee\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| fee               | VARCHAR   |                                                              |             |
| admin\_fee        | VARCHAR   |                                                              |             |

## 490. Table: sbtc2\_event\_RampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| old\_A            | VARCHAR   |                                                              |             |
| new\_A            | VARCHAR   |                                                              |             |
| initial\_time     | VARCHAR   |                                                              |             |
| future\_time      | VARCHAR   |                                                              |             |

## 491. Table: sbtc2\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-21 07:32:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17740047                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4572f956365e0d2557722d050297c9df4fba61e7ac899c1ffb757d2fc490039c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 158                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf253f83aca21aabd2a20553ae0bf7f65c755a07f                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xba3f5c056500ce033e9d74494b820d495efcf19d                         |                                                              |
| token\_amounts    | VARCHAR   | 92965881,0                                                         |                                                              |
| fees              | VARCHAR   | 9416,94194822380486                                                |                                                              |
| invariant         | VARCHAR   | 696950067066603678826                                              |                                                              |
| token\_supply     | VARCHAR   | 695504398834041036494                                              |                                                              |

## 492. Table: sbtc2\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-13 12:23:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17251033                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x763ade0176b5accc2ef96b80a72750c38a7a4a58aacf6c2fa62e5a6ec73345d2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 167                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf253f83aca21aabd2a20553ae0bf7f65c755a07f                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x2863a328a0b7fc6040f11614fa0728587db8e353                         |                                                              |
| token\_amount     | VARCHAR   | 349055549798685678                                                 |                                                              |
| coin\_amount      | VARCHAR   | 34987446                                                           |                                                              |
| token\_supply     | VARCHAR   | 556252117697046034016                                              |                                                              |

## 493. Table: sbtc2\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-22 12:11:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17535077                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc04b923538a54c1d26946ab540686d00ed752739e6dfe1be6438c1cf17b9955a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 336                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf253f83aca21aabd2a20553ae0bf7f65c755a07f                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xa2d40edbf76c6c0701ba8899e2d059798eba628e                         |                                                              |
| token\_amounts    | VARCHAR   | 188203337,2052713179816956634                                      |                                                              |
| fees              | VARCHAR   | 0,0                                                                |                                                              |
| token\_supply     | VARCHAR   | 541226465583263814351                                              |                                                              |

## 494. Table: sbtc2\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 495. Table: sbtc2\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-20 23:49:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16451407                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xda229837e777a1aed318a12db7003d073272b045ebdce3837d15a4341c08217d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 290                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf253f83aca21aabd2a20553ae0bf7f65c755a07f                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x99a58482bd75cbab83b27ec03ca68ff489b5788f                         |                                                              |
| sold\_id          | VARCHAR   | 1                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 820357289196983712                                                 |                                                              |
| bought\_id        | VARCHAR   | 0                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 82215456                                                           |                                                              |

## 496. Table: sbtcCrv\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-20 23:28:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12674192                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1a6ca90562b46d95ebb70e0af6d35308c665e74034693b1e7ea707814f4696f6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 169                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x075b1bb99792c9e1041ba13afef80c91a1e70fb3                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x7a0a6906de7714d27413f5092ed1a0636a3fbc9a                         |                                                              |
| \_spender         | VARCHAR   | 0x7f55dde206dbad629c080068923b36fe9d6bdbef                         |                                                              |
| \_value           | VARCHAR   | 554646856973128582                                                 |                                                              |

## 497. Table: sbtcCrv\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-19 10:26:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17080051                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7a03a69442851a2febebc4322a72646d01e5c692dc4a1dcc50c2e4fecf7928f5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 142                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x075b1bb99792c9e1041ba13afef80c91a1e70fb3                         | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0x071c661b4deefb59e2a3ddb20db036821eee8f4b                         |                                                              |
| \_to              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_value           | VARCHAR   | 53737116036011755                                                  |                                                              |

## 498. Table: stETHSwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-24 19:12:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15819951                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x258ffe8d7337d7ce5cf1b0b2370e14c23d2451ba09fee115d793c5747005c284 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 409                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdc24316b9ae028f1497c275eb9192a3ea0f67022                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x153bb76df6e4bf1ead05e603114c553fd3c8d1d6                         |                                                              |
| token\_amounts    | VARCHAR   | 0,500294400000000000                                               |                                                              |
| fees              | VARCHAR   | 47901332147739,47980150073781                                      |                                                              |
| invariant         | VARCHAR   | 1227359349282483821287144                                          |                                                              |
| token\_supply     | VARCHAR   | 1164180917402891536360900                                          |                                                              |

## 499. Table: stETHSwap\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| deadline          | VARCHAR   |                                                              |             |
| admin             | VARCHAR   |                                                              |             |

## 500. Table: stETHSwap\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-29 18:05:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17586622                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe3073945bcade7a5a991e9eb6aa897968ca896d212e0ebbe0203259423bc5227 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 239                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdc24316b9ae028f1497c275eb9192a3ea0f67022                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1688321111                                                         |                                                              |
| fee               | VARCHAR   | 1000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 501. Table: stETHSwap\_event\_NewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| admin             | VARCHAR   |                                                              |             |

## 502. Table: stETHSwap\_event\_NewFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-02 19:54:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17608532                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb9b774f83d8eb8eeeb4bca93b13bfc80835fe11c20b52bfd9aaec342a6fb2d3b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 150                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdc24316b9ae028f1497c275eb9192a3ea0f67022                         | Address of the contract that produced the log                |
| fee               | VARCHAR   | 1000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 503. Table: stETHSwap\_event\_RampA\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-18 22:33:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16658509                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf5cd32dd182fcfe63906d1ed1c65b2ee68030b29bed2b19d2e30de879d0a0851 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 298                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdc24316b9ae028f1497c275eb9192a3ea0f67022                         | Address of the contract that produced the log                |
| old\_A            | VARCHAR   | 5000                                                               |                                                              |
| new\_A            | VARCHAR   | 3000                                                               |                                                              |
| initial\_time     | VARCHAR   | 1676759639                                                         |                                                              |
| future\_time      | VARCHAR   | 1677333717                                                         |                                                              |

## 504. Table: stETHSwap\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-09 10:26:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12599811                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x778cc7065e373feeb213332e4276e2711000914b1298d666d65cc32531b88bc1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 128                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdc24316b9ae028f1497c275eb9192a3ea0f67022                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x0961f86626e297450073048a2c2ad9657fe56fbe                         |                                                              |
| token\_amounts    | VARCHAR   | 8499999999999999000,0                                              |                                                              |
| fees              | VARCHAR   | 847690329294672,847598400849278                                    |                                                              |
| invariant         | VARCHAR   | 705382324753840998462488                                           |                                                              |
| token\_supply     | VARCHAR   | 695445486993610029254241                                           |                                                              |

## 505. Table: stETHSwap\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-28 12:17:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17791505                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x652dafa8780a76aea0a64b50bb70d4a7dece1311022a99c1fe3970381b99bb9b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 548                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdc24316b9ae028f1497c275eb9192a3ea0f67022                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xead8aa856fac469e54642151437c4e69743eee6e                         |                                                              |
| token\_amount     | VARCHAR   | 97887218014285699                                                  |                                                              |
| coin\_amount      | VARCHAR   | 105425046932393424                                                 |                                                              |

## 506. Table: stETHSwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-06 09:43:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17855097                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf1a2cbcda7470759927d179891f3b63ec3fdefa944acecb41c52e3e0ecba3032 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 106                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdc24316b9ae028f1497c275eb9192a3ea0f67022                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x2ef11177b77b7e683f978e925736c1645cb4297c                         |                                                              |
| token\_amounts    | VARCHAR   | 169451114772434495,170420534829773942                              |                                                              |
| fees              | VARCHAR   | 0,0                                                                |                                                              |
| token\_supply     | VARCHAR   | 195380798440568152781601                                           |                                                              |

## 507. Table: stETHSwap\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 508. Table: stETHSwap\_event\_TokenExchangeUnderlying\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| buyer             | VARCHAR   |                                                              |             |
| sold\_id          | VARCHAR   |                                                              |             |
| tokens\_sold      | VARCHAR   |                                                              |             |
| bought\_id        | VARCHAR   |                                                              |             |
| tokens\_bought    | VARCHAR   |                                                              |             |

## 509. Table: stETHSwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-07 17:02:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13959527                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x925cf5b0642ca95d735480b93f6ea633aca3803b484876a855c906af4f3a7807 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 12                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdc24316b9ae028f1497c275eb9192a3ea0f67022                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x0000000000007f150bd6f54c40a34d7c3d5e9f56                         |                                                              |
| sold\_id          | VARCHAR   | 1                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 3577463069473260544                                                |                                                              |
| bought\_id        | VARCHAR   | 0                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 3563515206254100265                                                |                                                              |

## 510. Table: stETHng\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-28 07:14:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17576265                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xefa91cd817a355b0eb92a155b861e9411daf3d5b070669e53b9a4d009d3da70e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 336                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x21e27a5e5513d6e65c4f830167390997aa84843a                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xe7341285e44697a1930f0eef05f4319b3275e2ed                         |                                                              |
| token\_amounts    | VARCHAR   | 21000000000000000000,562838802526061337                            |                                                              |
| fees              | VARCHAR   | 2486153870080522,2486894084169956                                  |                                                              |
| invariant         | VARCHAR   | 45109727037142833546741                                            |                                                              |
| token\_supply     | VARCHAR   | 44928362511030900029049                                            |                                                              |

## 511. Table: stETHng\_event\_ApplyNewFee\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| fee               | VARCHAR   |                                                              |             |

## 512. Table: stETHng\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-20 20:59:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17523433                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf0ad3db142d16c6ac27ad04fc816304d9157b0a61bb244d548ccbfacc5b1e374 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 81                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x21e27a5e5513d6e65c4f830167390997aa84843a                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x3cf54f3a1969be9916dad548f3c084331c4450b5                         |                                                              |
| spender           | VARCHAR   | 0xf403c135812408bfbe8713b5a23a04b3d48aae31                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 513. Table: stETHng\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| new\_fee          | VARCHAR   |                                                              |             |

## 514. Table: stETHng\_event\_RampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| old\_A            | VARCHAR   |                                                              |             |
| new\_A            | VARCHAR   |                                                              |             |
| initial\_time     | VARCHAR   |                                                              |             |
| future\_time      | VARCHAR   |                                                              |             |

## 515. Table: stETHng\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| provider          | VARCHAR   |                                                              |             |
| token\_amounts    | VARCHAR   |                                                              |             |
| fees              | VARCHAR   |                                                              |             |
| invariant         | VARCHAR   |                                                              |             |
| token\_supply     | VARCHAR   |                                                              |             |

## 516. Table: stETHng\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-26 23:48:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17566955                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe0a2c7172bce6e9da86ac07d1dc1d1f188a6d7bc90fcf3a67f532d363859e359 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 231                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x21e27a5e5513d6e65c4f830167390997aa84843a                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x6f544fee2ee3e08260bc473734dc94d546d7b3c5                         |                                                              |
| token\_amount     | VARCHAR   | 42912757855737128490                                               |                                                              |
| coin\_amount      | VARCHAR   | 43082226358173177681                                               |                                                              |
| token\_supply     | VARCHAR   | 45011038956040036217643                                            |                                                              |

## 517. Table: stETHng\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-09 10:40:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17655615                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x668053937f9196808704b3597210dc771e3d90ffff503e0d37ba3e6cfbdb71bd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 179                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x21e27a5e5513d6e65c4f830167390997aa84843a                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xd5203cb8ab0b4cc1296f9bdfdd548b3cc8749c7c                         |                                                              |
| token\_amounts    | VARCHAR   | 107950342581931284929,171027420616235445141                        |                                                              |
| fees              | VARCHAR   | 0,0                                                                |                                                              |
| token\_supply     | VARCHAR   | 40876580810617958201871                                            |                                                              |

## 518. Table: stETHng\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 519. Table: stETHng\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-28 05:29:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17789474                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe3848649f5a43775037db5e9b39b00981e086636d42334b37f1203c216608099 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 187                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x21e27a5e5513d6e65c4f830167390997aa84843a                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x99a58482bd75cbab83b27ec03ca68ff489b5788f                         |                                                              |
| sold\_id          | VARCHAR   | 1                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 500000000000000000                                                 |                                                              |
| bought\_id        | VARCHAR   | 0                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 499690898236604440                                                 |                                                              |

## 520. Table: stETHng\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-16 03:01:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17703062                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfb6990e6c1a84e77b2bfd6b36574c5c2ba7aeb2469219d980e12fbcc969d7c11 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 206                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x21e27a5e5513d6e65c4f830167390997aa84843a                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xf403c135812408bfbe8713b5a23a04b3d48aae31                         |                                                              |
| receiver          | VARCHAR   | 0xd007058e9b58e74c33c6bf6fbcd38baab813cbb6                         |                                                              |
| value             | VARCHAR   | 2250000000000000000                                                |                                                              |

## 521. Table: tBTCSwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-19 17:37:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12271877                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc8268e55158415179b915473d7a5e15daebc647263b02b6a382907273ab47a94 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 105                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc25099792e9349c7dd09759744ea681c7de2cb66                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xaa82ca713d94bba7a89ceab55314f9effeddc78c                         |                                                              |
| token\_amounts    | VARCHAR   | 0,247981849667389378                                               |                                                              |
| fees              | VARCHAR   | 13467213728181,13499121857357                                      |                                                              |
| invariant         | VARCHAR   | 2754371467508911619817                                             |                                                              |
| token\_supply     | VARCHAR   | 2746761242656895859118                                             |                                                              |

## 522. Table: tBTCSwap\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-27 13:37:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11340846                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2496882c3dfa545785a06252337f90ae917aadc0a6e99c804ef6d7bc3c0a5c8d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 139                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc25099792e9349c7dd09759744ea681c7de2cb66                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1606743476                                                         |                                                              |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 523. Table: tBTCSwap\_event\_CommitNewFee\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| deadline          | VARCHAR   |                                                              |             |
| fee               | VARCHAR   |                                                              |             |
| admin\_fee        | VARCHAR   |                                                              |             |

## 524. Table: tBTCSwap\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-30 18:07:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11361655                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaf05989970aeb82c144bc44b536671ed4a3cdd1c06ddc72883dd3cd0e80ee616 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 178                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc25099792e9349c7dd09759744ea681c7de2cb66                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |

## 525. Table: tBTCSwap\_event\_NewFee\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| fee               | VARCHAR   |                                                              |             |
| admin\_fee        | VARCHAR   |                                                              |             |

## 526. Table: tBTCSwap\_event\_RampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| old\_A            | VARCHAR   |                                                              |             |
| new\_A            | VARCHAR   |                                                              |             |
| initial\_time     | VARCHAR   |                                                              |             |
| future\_time      | VARCHAR   |                                                              |             |

## 527. Table: tBTCSwap\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-31 19:21:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11563782                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x35f92b1226840976e7fd735414b666ff57012430daaf55555a54be949f5618d3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 59                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc25099792e9349c7dd09759744ea681c7de2cb66                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xaa82ca713d94bba7a89ceab55314f9effeddc78c                         |                                                              |
| token\_amounts    | VARCHAR   | 0,485835060324337807                                               |                                                              |
| fees              | VARCHAR   | 34208054504058,34155538432658                                      |                                                              |
| invariant         | VARCHAR   | 4207751984191887438253                                             |                                                              |
| token\_supply     | VARCHAR   | 4200492658604233871641                                             |                                                              |

## 528. Table: tBTCSwap\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-25 19:22:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17772160                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb0d81eaccbe26b387151ce8ddc95ffe78bb06ee42bbb446bc8ac9975c341fbd2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 638                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc25099792e9349c7dd09759744ea681c7de2cb66                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xaa82ca713d94bba7a89ceab55314f9effeddc78c                         |                                                              |
| token\_amount     | VARCHAR   | 59566069027999267                                                  |                                                              |
| coin\_amount      | VARCHAR   | 60147249653439479                                                  |                                                              |
| token\_supply     | VARCHAR   | 79692131084669197057                                               |                                                              |

## 529. Table: tBTCSwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-26 11:29:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11932551                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0d10b6b747923140335b1e6bbb59d478503db91ace0d3ce3db672234f8db0478 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 274                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc25099792e9349c7dd09759744ea681c7de2cb66                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xaa82ca713d94bba7a89ceab55314f9effeddc78c                         |                                                              |
| token\_amounts    | VARCHAR   | 1398515255548545285,3696969793634649389                            |                                                              |
| fees              | VARCHAR   | 0,0                                                                |                                                              |
| token\_supply     | VARCHAR   | 4324037402519875639927                                             |                                                              |

## 530. Table: tBTCSwap\_event\_StopRampA\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| A                 | VARCHAR   |                                                              |             |
| t                 | VARCHAR   |                                                              |             |

## 531. Table: tBTCSwap\_event\_TokenExchangeUnderlying\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-19 02:47:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12662242                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd1acb100f80d5e2585f16c2c96a6af04e1d58f22659aa64c8e1ceb4f88074aa5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 24                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc25099792e9349c7dd09759744ea681c7de2cb66                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x1c073d5045b1abb6924d5f0f8b2f667b1653a4c3                         |                                                              |
| sold\_id          | VARCHAR   | 1                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 387200000                                                          |                                                              |
| bought\_id        | VARCHAR   | 0                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 3813004614247071158                                                |                                                              |

## 532. Table: tBTCSwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-07 02:40:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12777685                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x695b605d1ce5699113e04dee2bfeaeff93adcf3d5ccdd6a18028205bbb32ca5e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 202                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc25099792e9349c7dd09759744ea681c7de2cb66                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x57196e30ba89c848147a19262a732191cbafaa37                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 4997500000000000000                                                |                                                              |
| bought\_id        | VARCHAR   | 1                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 4983830078727918493                                                |                                                              |

## 533. Table: tCrv\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-10 00:25:15+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13774164                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc9ce265641a720f503a2203b9e1b07a9171325861dfc2f44edcbcbf812d01724             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 392                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9fc689ccada600b6df723d9e47d84d76664a1f23                                     | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x81dd41be577583b01cdc183fa158f3aa08bbb517                                     |                                                              |
| \_spender         | VARCHAR   | 0xf403c135812408bfbe8713b5a23a04b3d48aae31                                     |                                                              |
| \_value           | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 534. Table: tCrv\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-01 22:26:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11773029                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x602cdff12180dd05cd8041cbcb9bbd0f26dfe42251e7484f3dd87acae732b864 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 223                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9fc689ccada600b6df723d9e47d84d76664a1f23                         | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0xac795d2c97e60df6a99ff1c814727302fd747a80                         |                                                              |
| \_to              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_value           | VARCHAR   | 943715496800914020131                                              |                                                              |

## 535. Table: tricrypto2\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-16 00:08:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14593083                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc5f087a0bbe480d73246428ce91865bce3b924bc73aa54f48303d7ba09ba90c1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 84                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd51a44d3fae010294c616388b506acda1bfaae46                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xd10d54830714003575d9f472d62268a29c902e5a                         |                                                              |
| token\_amounts    | VARCHAR   | 7774645155,19860479,2550752634966250797                            |                                                              |
| fee               | VARCHAR   | 217586143422019                                                    |                                                              |
| token\_supply     | VARCHAR   | 570292061845199688301195                                           |                                                              |

## 536. Table: tricrypto2\_event\_ClaimAdminFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-13 22:00:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17253865                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4aa02129abfd8c92a8b99bbe749c9494242e9ff3c21eb874a191573d1eaceb5b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 240                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd51a44d3fae010294c616388b506acda1bfaae46                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0xecb456ea5365865ebab8a2661b0c503410e9b347                         |                                                              |
| tokens            | VARCHAR   | 1328733876061977861                                                |                                                              |

## 537. Table: tricrypto2\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| deadline          | VARCHAR   |                                                              |             |
| admin             | VARCHAR   |                                                              |             |

## 538. Table: tricrypto2\_event\_CommitNewParameters\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2021-07-24 21:46:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 12891527                                                           | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0xb076b576e799510ecba97d6cbb873a8e6ef9d3d2e9754ea1af9c23faef2162c0 | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 324                                                                | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0xd51a44d3fae010294c616388b506acda1bfaae46                         | Address of the contract that produced the log                |
| deadline               | VARCHAR   | 1627422392                                                         |                                                              |
| admin\_fee             | VARCHAR   | 5000000000                                                         |                                                              |
| mid\_fee               | VARCHAR   | 11000000                                                           |                                                              |
| out\_fee               | VARCHAR   | 45000000                                                           |                                                              |
| fee\_gamma             | VARCHAR   | 500000000000000                                                    |                                                              |
| allowed\_extra\_profit | VARCHAR   | 2000000000000                                                      |                                                              |
| adjustment\_step       | VARCHAR   | 2000000000000000                                                   |                                                              |
| ma\_half\_time         | VARCHAR   | 600                                                                |                                                              |

## 539. Table: tricrypto2\_event\_NewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| admin             | VARCHAR   |                                                              |             |

## 540. Table: tricrypto2\_event\_NewParameters\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2023-02-07 20:30:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 16579299                                                           | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0x1463b0c1d2c4626a763c60764855b4b9b30125eab9f427a72b6377949d5691fe | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 476                                                                | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0xd51a44d3fae010294c616388b506acda1bfaae46                         | Address of the contract that produced the log                |
| admin\_fee             | VARCHAR   | 5000000000                                                         |                                                              |
| mid\_fee               | VARCHAR   | 3000000                                                            |                                                              |
| out\_fee               | VARCHAR   | 30000000                                                           |                                                              |
| fee\_gamma             | VARCHAR   | 500000000000000                                                    |                                                              |
| allowed\_extra\_profit | VARCHAR   | 2000000000000                                                      |                                                              |
| adjustment\_step       | VARCHAR   | 490000000000000                                                    |                                                              |
| ma\_half\_time         | VARCHAR   | 600                                                                |                                                              |

## 541. Table: tricrypto2\_event\_RampAgamma\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-01 12:22:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13139772                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb6b3438033739094c9a462dd6399303246b29ab3cdaf0cb2d782b90a86b80a00 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 24                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd51a44d3fae010294c616388b506acda1bfaae46                         | Address of the contract that produced the log                |
| initial\_A        | VARCHAR   | 54000                                                              |                                                              |
| future\_A         | VARCHAR   | 405000                                                             |                                                              |
| initial\_gamma    | VARCHAR   | 280000000000000                                                    |                                                              |
| future\_gamma     | VARCHAR   | 28000000000000                                                     |                                                              |
| initial\_time     | VARCHAR   | 1630498968                                                         |                                                              |
| future\_time      | VARCHAR   | 1631100490                                                         |                                                              |

## 542. Table: tricrypto2\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-31 01:08:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17375499                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8a565baae0613203f4d23e333a791801255778a0ac3ba971a87e6cf9a27b0ab4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 889                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd51a44d3fae010294c616388b506acda1bfaae46                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x7fb69e8fb1525ceec03783ffd8a317bafbdfd394                         |                                                              |
| token\_amount     | VARCHAR   | 891588037541288365                                                 |                                                              |
| coin\_index       | VARCHAR   | 2                                                                  |                                                              |
| coin\_amount      | VARCHAR   | 543621665420907647                                                 |                                                              |

## 543. Table: tricrypto2\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-25 14:28:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16905073                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3e9b9a5aafceb1ae31c7cad9771da418748f0a9a4452a265be0d25c8790bfc12 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 231                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd51a44d3fae010294c616388b506acda1bfaae46                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x3993d34e7e99abf6b6f367309975d1360222d446                         |                                                              |
| token\_amounts    | VARCHAR   | 37169948853,133818470,21100263555782315393                         |                                                              |
| token\_supply     | VARCHAR   | 180656985170193183899221                                           |                                                              |

## 544. Table: tricrypto2\_event\_StopRampA\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-27 14:34:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12908614                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf3c4a7039b30aa89f54b2a344c983a11b60d5ec71881ee50ec9815827f41d524 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 333                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd51a44d3fae010294c616388b506acda1bfaae46                         | Address of the contract that produced the log                |
| current\_A        | VARCHAR   | 53992                                                              |                                                              |
| current\_gamma    | VARCHAR   | 3499499842873918                                                   |                                                              |
| time              | VARCHAR   | 1627396451                                                         |                                                              |

## 545. Table: tricrypto2\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-04 13:53:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16111866                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x933ae7ab6c8dc6b72293761f506accb0e0099c6860e81bddf10edabc3c0af9b0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 56                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd51a44d3fae010294c616388b506acda1bfaae46                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x0000000000a84d1a9b0063a910315c7ffa9cd248                         |                                                              |
| sold\_id          | VARCHAR   | 2                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 12873667460000000000                                               |                                                              |
| bought\_id        | VARCHAR   | 0                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 16132878877                                                        |                                                              |

## 546. Table: yCrv\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-05 10:54:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12373789                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x24c07a9d403179522cb5ac80a36b380343aa2de35fc56696d7d4422f2ac5d4e0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 218                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdf5e0e81dff6faf3a7e52ba697820c5e32d806a8                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0xde1f578292e75f26dfaebc78aa0eccca45b13521                         |                                                              |
| \_spender         | VARCHAR   | 0xa89bd606d5dadda60242e8dedeebc95c41ad8986                         |                                                              |
| \_value           | VARCHAR   | 0                                                                  |                                                              |

## 547. Table: yCrv\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-28 19:37:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10356231                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x20beb0cadc99ebd92df0389e400e6e4a8701f2eee4e17f3ca76fd6e1844099eb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 82                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdf5e0e81dff6faf3a7e52ba697820c5e32d806a8                         | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0x27c11b31ea0db2c5d013fc0748ba4b2544fdf2ff                         |                                                              |
| \_to              | VARCHAR   | 0xbbc81d23ea2c3ec7e56d39296f0cbb648873a5d3                         |                                                              |
| \_value           | VARCHAR   | 50691426778849207077907                                            |                                                              |

## 548. Table: ySwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-11 06:28:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9648595                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x17c390fdb28363e1571d8ba6baef97d6eed987e490f34777a448333492e05986 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 137                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45f783cce6b7ff23b2ab2d70e416cdb7d6055f51                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x2482dc04ac628a4b2700c071bfee557fd86c91ea                         |                                                              |
| token\_amounts    | VARCHAR   | 0,0,7501896902,0                                                   |                                                              |
| fees              | VARCHAR   | 46299543192492763,346553,720775,283396864518541661                 |                                                              |
| invariant         | VARCHAR   | 7603395460020744571297239                                          |                                                              |
| token\_supply     | VARCHAR   | 7510144974934667503437023                                          |                                                              |

## 549. Table: ySwap\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-20 00:30:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11089752                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc7c98d20ae79e3907e69262eea57f034726074e57eb7c802a3e834df03d24ba5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 148                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45f783cce6b7ff23b2ab2d70e416cdb7d6055f51                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1603413000                                                         |                                                              |
| admin             | VARCHAR   | 0x56295b752e632f74a6526988eace33c25c52c623                         |                                                              |

## 550. Table: ySwap\_event\_CommitNewParameters\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-16 19:48:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10875110                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd86f34e988709d22067837467fdb039917967feca9a0959cd3d0e6dd3f823cbc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 214                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45f783cce6b7ff23b2ab2d70e416cdb7d6055f51                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1600544926                                                         |                                                              |
| A                 | VARCHAR   | 1000                                                               |                                                              |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 5000000000                                                         |                                                              |

## 551. Table: ySwap\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-24 22:06:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11121729                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1ff24caf209063cc96ba220d986fca98f8da094a8be4cc4d58a80c0bfddc739b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 195                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45f783cce6b7ff23b2ab2d70e416cdb7d6055f51                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0x56295b752e632f74a6526988eace33c25c52c623                         |                                                              |

## 552. Table: ySwap\_event\_NewParameters\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-16 14:34:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10873718                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x911548f5f9b3612c35eb793668896b1bca36c3a784a9c77b7ed2ed32d8e35830 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 193                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45f783cce6b7ff23b2ab2d70e416cdb7d6055f51                         | Address of the contract that produced the log                |
| A                 | VARCHAR   | 1000                                                               |                                                              |
| fee               | VARCHAR   | 4000000                                                            |                                                              |
| admin\_fee        | VARCHAR   | 0                                                                  |                                                              |

## 553. Table: ySwap\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-11 14:03:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14755259                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8f4ad81aef8dce38ed751a85174658ce765ca0fce26edf44f87f533d56d6299d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 232                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45f783cce6b7ff23b2ab2d70e416cdb7d6055f51                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xbbc81d23ea2c3ec7e56d39296f0cbb648873a5d3                         |                                                              |
| token\_amounts    | VARCHAR   | 0,203296384427,0,0                                                 |                                                              |
| fees              | VARCHAR   | 7373777885460026901,22306468,13188637,4613334977992931252          |                                                              |
| invariant         | VARCHAR   | 14660831265938869716179582                                         |                                                              |
| token\_supply     | VARCHAR   | 12865268482264798229169061                                         |                                                              |

## 554. Table: ySwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                             | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-29 14:50:30+00:00                                           | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12729579                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf045fe31d76fbe928a0bf332226b14ae91b216215a13ed6e0d7375c9da1d75ef  | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 279                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45f783cce6b7ff23b2ab2d70e416cdb7d6055f51                          | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xbbc81d23ea2c3ec7e56d39296f0cbb648873a5d3                          |                                                              |
| token\_amounts    | VARCHAR   | 4688154665108841643136,7873527713,9445780897,7450812632696706490119 |                                                              |
| fees              | VARCHAR   | 0,0,0,0                                                             |                                                              |
| token\_supply     | VARCHAR   | 105773191347919168516899214                                         |                                                              |

## 555. Table: ySwap\_event\_TokenExchangeUnderlying\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-11 20:20:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17459193                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc009c40533a87c7caf46d26b1a915cafef5d768ec586b87b1e6ea99593d616e5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 126                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45f783cce6b7ff23b2ab2d70e416cdb7d6055f51                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xfa9a30350048b2bf66865ee20363067c66f67e58                         |                                                              |
| sold\_id          | VARCHAR   | 2                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 3819138439                                                         |                                                              |
| bought\_id        | VARCHAR   | 0                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 3820003659283243571493                                             |                                                              |

## 556. Table: ySwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-18 06:09:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12656787                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0f49e2a3f505d40c54f3e0ef413604b76dcfae52f68dea21ef4579e98fc35369 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 286                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45f783cce6b7ff23b2ab2d70e416cdb7d6055f51                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x4ba03330338172febeb0050be6940c6e7f9c91b0                         |                                                              |
| sold\_id          | VARCHAR   | 1                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 2531478190                                                         |                                                              |
| bought\_id        | VARCHAR   | 3                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 2903549975569068951142                                             |                                                              |
