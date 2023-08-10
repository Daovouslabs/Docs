# copper

## 1. Table: CopperProxyV2\_event\_GradualWeightUpdateScheduled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-20 10:09:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14422634                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2c3517d08f6e87bfc92ff9c1cbbeb47ce23b5c048be1340d957f4aad2957454d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 339                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9a74cbff3f36ff1e433ef88d0ec1cdcd1eb79afa                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0x820298d6c264c2bb95152c44270d8729057ec467                         |                                                              |
| startTime         | VARCHAR   | 1647777600                                                         |                                                              |
| endTime           | VARCHAR   | 1654165194                                                         |                                                              |
| endWeights        | VARCHAR   | 500000000000000000,500000000000000000                              |                                                              |

## 2. Table: CopperProxyV2\_event\_JoinedPool\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-20 00:55:54+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15176424                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf0d8e519c5a51577afdfe29ddfdfc3b9abe48eb7e0d8fde0c3933b8fda8d1883                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 396                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9a74cbff3f36ff1e433ef88d0ec1cdcd1eb79afa                                                           | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0xd81207e64ce0fce740d82956762e4131ee806941                                                           |                                                              |
| tokens            | VARCHAR   | 0x249928c4F18E83d9abD4b7Ca8aB0330b10A92AAa,0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2                |                                                              |
| amounts           | VARCHAR   | 60000000000000000,4000000000000000000                                                                |                                                              |
| userData          | VARCHAR   | 0x00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000 |                                                              |

## 3. Table: CopperProxyV2\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-16 16:31:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14398706                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x982aeec065515ccfe75792ac74f6e2261835bace1a6630653654f980cf2f0d58 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 336                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9a74cbff3f36ff1e433ef88d0ec1cdcd1eb79afa                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x6480bc106f5a0b13d15f5c3acb97fa9945b34508                         |                                                              |

## 4. Table: CopperProxyV2\_event\_PoolCreated\_history

| Column             | Type      | Example                                                                               | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2022-07-30 05:13:59+00:00                                                             | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 15241893                                                                              | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x5b9ce9e209b1973373d1206771f2b52561c8a8a0c3cde25632afab9d64e74c62                    | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 585                                                                                   | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x9a74cbff3f36ff1e433ef88d0ec1cdcd1eb79afa                                            | Address of the contract that produced the log                |
| pool               | VARCHAR   | 0x3197b84a2c62547907069c809d0ef77cb3c5a794                                            |                                                              |
| poolId             | VARCHAR   | 0x3197b84a2c62547907069c809d0ef77cb3c5a7940002000000000000000002e8                    |                                                              |
| name               | VARCHAR   | UFO2 Copper LBP                                                                       |                                                              |
| symbol             | VARCHAR   | UFO2\_LBP                                                                             |                                                              |
| tokens             | VARCHAR   | 0x5b46d3611d992cDe2381a7c43E75c1Ea6D999238,0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48 |                                                              |
| weights            | VARCHAR   | 990000000000000000,10000000000000000                                                  |                                                              |
| swapFeePercentage  | VARCHAR   | 25099999999999996                                                                     |                                                              |
| owner              | VARCHAR   | 0x9a74cbff3f36ff1e433ef88d0ec1cdcd1eb79afa                                            |                                                              |
| swapEnabledOnStart | VARCHAR   | false                                                                                 |                                                              |
