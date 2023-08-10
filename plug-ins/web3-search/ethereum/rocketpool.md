# rocketpool

## 1. Table: RocketDepositPoolV1\_event\_DepositAssigned\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-04 23:19:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14142518                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe5f6477198de961e72549ce8b1a68e92cdbc62624366fe25ec3e93d2b0d0f3d7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 170                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4d05e3d48a938db4b7a9a59a802d5b45011bde58                         | Address of the contract that produced the log                |
| minipool          | VARCHAR   | 0xcb954e49a1d5eff5f644d07a5267a6a5cf2ef68f                         |                                                              |
| amount            | VARCHAR   | 16000000000000000000                                               |                                                              |
| time              | VARCHAR   | 1644016753                                                         |                                                              |

## 2. Table: RocketDepositPoolV1\_event\_DepositReceived\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-02 11:37:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14506514                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x565bea0b4478e07da90938fa276e6d62dc6c59fb4f9aa93862d1f5cb2d5d8586 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 309                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4d05e3d48a938db4b7a9a59a802d5b45011bde58                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x01a2a10ed806d4e65ad92c2c6b10bc4d5f37001e                         |                                                              |
| amount            | VARCHAR   | 16000000000000000000                                               |                                                              |
| time              | VARCHAR   | 1648899425                                                         |                                                              |

## 3. Table: RocketDepositPoolV1\_event\_DepositRecycled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-13 11:31:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15134030                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdc71d42c99c65e6c4175d2d0a07cb781da38b263fb94190ab583376bc8383f1d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 103                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4d05e3d48a938db4b7a9a59a802d5b45011bde58                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x8af6539910e2bb10ca882b661aeeb835eeb6f267                         |                                                              |
| amount            | VARCHAR   | 16000000000000000000                                               |                                                              |
| time              | VARCHAR   | 1657711862                                                         |                                                              |

## 4. Table: RocketDepositPoolV1\_event\_ExcessWithdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-05 09:08:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14325964                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x90a01d34eeb6154619fd9f36e8755c4917500bcc81899e32b643bd7b79c01aa8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 150                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4d05e3d48a938db4b7a9a59a802d5b45011bde58                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0xae78736cd615f374d3085123a210448e74fc6393                         |                                                              |
| amount            | VARCHAR   | 101726259383851577                                                 |                                                              |
| time              | VARCHAR   | 1646471327                                                         |                                                              |

## 5. Table: RocketDepositPoolV2\_event\_DepositAssigned\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-01 16:30:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15876379                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbeebf0e7a996ad815d905374304b83c3d0c5937139292c958c690d54a4cbf11b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 79                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2cac916b2a963bf162f076c0a8a4a8200bcfbfb4                         | Address of the contract that produced the log                |
| minipool          | VARCHAR   | 0x468c6482f47b08f1126c3d2a1e5db75b5fe53f76                         |                                                              |
| amount            | VARCHAR   | 16000000000000000000                                               |                                                              |
| time              | VARCHAR   | 1667320211                                                         |                                                              |

## 6. Table: RocketDepositPoolV2\_event\_DepositReceived\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-01 15:04:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16090734                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdd72109844d7a670b4d05df49f0448ff3382bccd463aaefeaba10e6143f55d0f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 49                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2cac916b2a963bf162f076c0a8a4a8200bcfbfb4                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x6c6b87d44d239b3750bf9badce26a9a0a3d2364e                         |                                                              |
| amount            | VARCHAR   | 144120643980010345                                                 |                                                              |
| time              | VARCHAR   | 1669907099                                                         |                                                              |

## 7. Table: RocketDepositPoolV2\_event\_DepositRecycled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-14 17:17:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15747786                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd6731ab8b856de1254c74a2342c32a8dc9de13ec5e4f3e84782e380e81b6bf73 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 87                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2cac916b2a963bf162f076c0a8a4a8200bcfbfb4                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xa4ffe825fa8c287f194776b8bafcf42cfc8db603                         |                                                              |
| amount            | VARCHAR   | 16000000000000000000                                               |                                                              |
| time              | VARCHAR   | 1665767855                                                         |                                                              |

## 8. Table: RocketDepositPoolV2\_event\_ExcessWithdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-13 18:24:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15740963                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4e8d90b076c1f4e7e3068b9e7ae024a2d5b9102843e9dec800c49943e41f277a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 224                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2cac916b2a963bf162f076c0a8a4a8200bcfbfb4                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0xae78736cd615f374d3085123a210448e74fc6393                         |                                                              |
| amount            | VARCHAR   | 28076522451331375781                                               |                                                              |
| time              | VARCHAR   | 1665685463                                                         |                                                              |

## 9. Table: RocketMinipoolManager\_event\_MinipoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-28 03:44:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14472366                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa52b55deedfa183f07ba869c4b6189a8766649c0e1e85425670d6b2dcd443061 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 126                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6293b8abc1f36afb22406be5f96d893072a8cf3a                         | Address of the contract that produced the log                |
| minipool          | VARCHAR   | 0xfdc3d40f4fffb780ca784158bdf6fbccd4a5a77d                         |                                                              |
| node              | VARCHAR   | 0x06fb9132f2f689e4f8076c712a5515aa96fb1879                         |                                                              |
| time              | VARCHAR   | 1648439053                                                         |                                                              |

## 10. Table: RocketMinipoolManager\_event\_MinipoolDestroyed\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| minipool          | VARCHAR   |                                                              |             |
| node              | VARCHAR   |                                                              |             |
| time              | VARCHAR   |                                                              |             |

## 11. Table: RocketNodeDeposit\_event\_DepositReceived\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-03 21:09:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13934828                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8d784240dbe0954638af0311b02c9628024788f1ef43b359e706acdf93c60e0c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 216                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdcd51fc5cd918e0461b9b7fb75967fdfd10dae2f                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0057805eae8506e179ce8159b8c7e5509dead95b                         |                                                              |
| amount            | VARCHAR   | 16000000000000000000                                               |                                                              |
| time              | VARCHAR   | 1641244159                                                         |                                                              |

## 12. Table: RocketPoolToken\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-12 13:25:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16168910                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf60af111f71cd92c057867b069936c830ec1f679cf7659183def688f14218fc5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 197                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb4efd85c19999d84251304bda99e90b92300bd93                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0xe826c57c314a951e5594ccdd5ed0c4c2e86e5eb8                         |                                                              |
| \_spender         | VARCHAR   | 0x7a250d5630b4cf539739df2c5dacb4c659f2488d                         |                                                              |
| \_value           | VARCHAR   | 0                                                                  |                                                              |

## 13. Table: RocketPoolToken\_event\_FlagAddress\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| flag              | VARCHAR   |                                                              |             |

## 14. Table: RocketPoolToken\_event\_FlagUint\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| flag              | VARCHAR   |                                                              |             |

## 15. Table: RocketPoolToken\_event\_MintToken\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-11-20 02:38:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6737048                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc4e93d4b266182f1993515b769e68893d36c9898419cd45a33881d33b455f16a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 17                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb4efd85c19999d84251304bda99e90b92300bd93                         | Address of the contract that produced the log                |
| \_agent           | VARCHAR   | 0x5f5ccb699caaa517c51410bc43979d27f51ba1c2                         |                                                              |
| \_address         | VARCHAR   | 0x36034cba5413c0678b8256acd0a87af4e9d0873a                         |                                                              |
| \_value           | VARCHAR   | 2704532603779685155145                                             |                                                              |

## 16. Table: RocketPoolToken\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_from            | VARCHAR   |                                                              |             |
| \_to              | VARCHAR   |                                                              |             |

## 17. Table: RocketPoolToken\_event\_SaleFinalised\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2017-11-24 07:12:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4611793                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2f64c9723ac0fc065eb2d1109a49b2b0eb22783a2d7bfe76230614c5c1509084 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 29                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb4efd85c19999d84251304bda99e90b92300bd93                         | Address of the contract that produced the log                |
| \_agent           | VARCHAR   | 0xb0defe01153dfc7fe58c1ad49925b64fc67fde9e                         |                                                              |
| \_address         | VARCHAR   | 0x4e3bc0dc25c42ed2745bfc67f1d0daa52103c01a                         |                                                              |
| \_value           | VARCHAR   | 8196199000000000000000000                                          |                                                              |

## 18. Table: RocketPoolToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-02-12 14:23:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7211286                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8f6c2af10d378a41ee7d2530d4f0b5986b4df8f6ad106e3e753d5336ad28897c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 17                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb4efd85c19999d84251304bda99e90b92300bd93                         | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0x1dae3fe9969e1b3d3a9d5f93b7791c791bf21043                         |                                                              |
| \_to              | VARCHAR   | 0xfa225258a04d7f01907faf72b49526292a1263c4                         |                                                              |
| \_value           | VARCHAR   | 50000000000000000000000                                            |                                                              |

## 19. Table: RocketRewardsPool\_event\_RPLTokensClaimed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-09 05:36:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14930917                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x393cfecfdc5994eb97f4f63a0f2dce9f4f2dbe94b834b24317a800288f38ae79 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 62                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa3a18348e6e2d3897b6f2671bb8c120e36554802                         | Address of the contract that produced the log                |
| claimingContract  | VARCHAR   | 0x428f0de7a6bf5ecca29e1c5e8c407b21e8becd39                         |                                                              |
| claimingAddress   | VARCHAR   | 0x428f0de7a6bf5ecca29e1c5e8c407b21e8becd39                         |                                                              |
| amount            | VARCHAR   | 10414433669299308269236                                            |                                                              |
| time              | VARCHAR   | 1654752973                                                         |                                                              |

## 20. Table: RocketTokenRETH\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-20 20:19:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17736717                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2b5faee120a92cadea5d8a43889f12ced01610de7bcad630aa703d52b729a63d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 291                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xae78736cd615f374d3085123a210448e74fc6393                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x13e851a2d30ef375f9ab5bc6e19b980e32ffe271                         |                                                              |
| spender           | VARCHAR   | 0x000000000022d473030f116ddee9f6b43ac78ba3                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 21. Table: RocketTokenRETH\_event\_EtherDeposited\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-19 23:55:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17296921                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb5ce1f62b24e98ae59ddf49500132d59c2a9fc44f2781e71cde6f29fa2d73c7e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xae78736cd615f374d3085123a210448e74fc6393                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x4fe776256ee74b2cf54e0ae2d77c306da050b1e9                         |                                                              |
| amount            | VARCHAR   | 0                                                                  |                                                              |
| time              | VARCHAR   | 1684540559                                                         |                                                              |

## 22. Table: RocketTokenRETH\_event\_TokensBurned\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-30 07:05:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17804249                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x29f69594079ff7ce3663633baa42cceeb5526a553b8304baf2680938eb2f0380 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xae78736cd615f374d3085123a210448e74fc6393                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x00000000000747d525e898424e8774f7eb317d00                         |                                                              |
| amount            | VARCHAR   | 224000000000000000000                                              |                                                              |
| ethAmount         | VARCHAR   | 241558001071669741807                                              |                                                              |
| time              | VARCHAR   | 1690700735                                                         |                                                              |

## 23. Table: RocketTokenRETH\_event\_TokensMinted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-04 00:23:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16551820                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0e0808540ccf8479492f2e3f6d2b3711b8e0d204188081a231fda9d2ae3c4050 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 102                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xae78736cd615f374d3085123a210448e74fc6393                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0x1f7e55f2e907ddce8074b916f94f62c7e8a18571                         |                                                              |
| amount            | VARCHAR   | 15126514213195319317                                               |                                                              |
| ethAmount         | VARCHAR   | 15992000000000000000                                               |                                                              |
| time              | VARCHAR   | 1675470239                                                         |                                                              |

## 24. Table: RocketTokenRETH\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-04 15:56:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14140467                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc4ed1ea8a9f72777eefe6a64b15f5e8daad92ba964d286ec36534ee5c648fd74 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 178                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xae78736cd615f374d3085123a210448e74fc6393                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xd62b0b2c1deff116c0b189483b0bbd0cc52649e0                         |                                                              |
| value             | VARCHAR   | 3945387462565036094                                                |                                                              |
