# cyclone

## 1. Table: CycloneV2dot3\_event\_AnonymityFeeUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-16 03:12:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12248682                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc8ea0c89038314a754353c44bfd1724145f896588704d1a706882f6653e674f6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 24                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x09f03488291063a8f3c67d2aab7002419d11c113                         | Address of the contract that produced the log                |
| oldValue          | VARCHAR   | 0                                                                  |                                                              |
| newValue          | VARCHAR   | 5000000000000000                                                   |                                                              |

## 2. Table: CycloneV2dot3\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-31 12:56:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17813130                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x97fadc796bcf4531553f3d2ed708c177daa523af0f4273500670f5f7e42014a1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 287                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x52609307f2f6c43b7df63364ef65718d299ac246                         | Address of the contract that produced the log                |
| commitment        | VARCHAR   | 0x10f87b6f280135b0cfe6361bf64ada66187981a2ec14b436d20d3fe8ebcc32af |                                                              |
| leafIndex         | VARCHAR   | 32                                                                 |                                                              |
| timestamp         | VARCHAR   | 1690808183                                                         |                                                              |
| cycDenomination   | VARCHAR   | 1995497847222166611                                                |                                                              |
| anonymityFee      | VARCHAR   | 0                                                                  |                                                              |

## 3. Table: CycloneV2dot3\_event\_RewardPerBlockUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-16 03:13:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12248684                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x46feeb96586b13df72319b36189fecdf8721fadd6cdb33c096e662b3262cd1a8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 77                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x09f03488291063a8f3c67d2aab7002419d11c113                         | Address of the contract that produced the log                |
| oldValue          | VARCHAR   | 0                                                                  |                                                              |
| newValue          | VARCHAR   | 45138888888889                                                     |                                                              |

## 4. Table: CycloneV2dot3\_event\_Withdrawal\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-08 05:41:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16137970                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x17eb9e1260c123e8f5065721f71b1d39a5aa4b929aa2534a109ad8fbf7d67279 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 254                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x52609307f2f6c43b7df63364ef65718d299ac246                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0x3580f83473ec50fdef1004362411966d10006d59                         |                                                              |
| nullifierHash     | VARCHAR   | 0x27395c654d4acc8e60e8dfea02e2d51b8571da61c981fa9ae273e74cce761da9 |                                                              |
| relayer           | VARCHAR   | 0xc36935397ee074d73c2d4cebb02871c8d0bf7c57                         |                                                              |
| reward            | VARCHAR   | 1995497847222166611                                                |                                                              |
| relayerFee        | VARCHAR   | 0                                                                  |                                                              |
