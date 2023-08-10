# usdc

## 1. Table: FiatTokenV1\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-09-09 12:02:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8515549                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x480bf0ef7cf264e133649481289c51e36a26c796085d82fcd96e5b121cbc8836 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xa8bdb1699093c114b83fb1a1f11da286f77568a3                         |                                                              |
| spender           | VARCHAR   | 0x00f2b67b5a5ec2ff88b2be7d5a8d1a39d5929237                         |                                                              |
| value             | VARCHAR   | 900000000000000000000                                              |                                                              |

## 2. Table: FiatTokenV1\_event\_Blacklisted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-30 22:33:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15649162                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9f63e2362bc319b6167120bbdec737e60216519d787c323b3465db6af5971d10 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 91                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         | Address of the contract that produced the log                |
| \_account         | VARCHAR   | 0x81c4d8816b29147c542dde87485608204690acf2                         |                                                              |

## 3. Table: FiatTokenV1\_event\_BlacklisterChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-06-27 19:42:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8041867                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x86b15e4288d445f65a5511e9bb3b9fad41cfe9b51d0a44e5f40ca9eec08984e9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         | Address of the contract that produced the log                |
| newBlacklister    | VARCHAR   | 0x5db0115f3b72d19cea34dd697cf412ff86dc7e1b                         |                                                              |

## 4. Table: FiatTokenV1\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-14 08:51:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9104534                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x393f5cc240f7814c16a526901e1793eefdcfd93e996e30a4ec366757ab1d31b4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 141                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         | Address of the contract that produced the log                |
| burner            | VARCHAR   | 0xe7ab0dd2a069fa115c0d7878af6fd95ba0f9100a                         |                                                              |
| amount            | VARCHAR   | 66443800000                                                        |                                                              |

## 5. Table: FiatTokenV1\_event\_MasterMinterChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-09-06 13:43:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6282558                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9b8c5e3c972893fcf2939ca59b56d6da3d3085407c934dd97d39c97159255caf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         | Address of the contract that produced the log                |
| newMasterMinter   | VARCHAR   | 0x166bb3cdf38d4ef4e7252116e272b297cce1ab4f                         |                                                              |

## 6. Table: FiatTokenV1\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-15 11:54:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9110268                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa35aaa5483830d22b25fcff4d8d0f4c06fda876519ae907bba6ee2c0fbba8434 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 31                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0x5b6122c109b78c6755486966148c1d70a50a47d7                         |                                                              |
| to                | VARCHAR   | 0x55fe002aeff02f77364de339a1292923a15844b8                         |                                                              |
| amount            | VARCHAR   | 599969700000                                                       |                                                              |

## 7. Table: FiatTokenV1\_event\_MinterConfigured\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2021-02-10 15:50:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 11829693                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x3f3ca8f42cb44e8f73767c61a9792eb65cc8b586ea7cc53e5055f7eac67adc78 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         | Address of the contract that produced the log                |
| minter              | VARCHAR   | 0x5b6122c109b78c6755486966148c1d70a50a47d7                         |                                                              |
| minterAllowedAmount | VARCHAR   | 906045136770980                                                    |                                                              |

## 8. Table: FiatTokenV1\_event\_MinterRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-06 17:33:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12187552                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb69c40a36304c9540d311a86bf84fc85d9ded5ba4808024d76213e6ddf0041ce | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         | Address of the contract that produced the log                |
| oldMinter         | VARCHAR   | 0xd4c1315948125cd20c11c5e9565a3632c1710055                         |                                                              |

## 9. Table: FiatTokenV1\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-09-06 14:00:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6282629                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1a9bd3dbef340c14ce238d8484b47c9a2cae1dd65b70b20cc206654faf3f50b1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0xa61e278899a8553d93d14eb19ba2791e05069e87                         |                                                              |
| newOwner          | VARCHAR   | 0xfcb19e6a322b27c06842a71e8c725399f049ae3a                         |                                                              |

## 10. Table: FiatTokenV1\_event\_Pause\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 11. Table: FiatTokenV1\_event\_PauserChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-09-06 13:06:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6282401                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x04fcdf7c503719e6fd597fae1ebb4fe17227e5bba8cfa00fd43466c728fa2df7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         | Address of the contract that produced the log                |
| newAddress        | VARCHAR   | 0xf8ac57c67946dfb13bba4fe6bf5176232fd24d8a                         |                                                              |

## 12. Table: FiatTokenV1\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-16 18:02:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13238272                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf4ffe234e832e5a9abcdc5410899b3585470131a0fef13fe0c0150f155e37d3f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 255                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xcbd6ed4fd56d83bac9640201c4dcde1efa1ad60f                         |                                                              |
| to                | VARCHAR   | 0x972eebcb30252640c60c7e4821b15118f03b267e                         |                                                              |
| value             | VARCHAR   | 100000000000                                                       |                                                              |

## 13. Table: FiatTokenV1\_event\_UnBlacklisted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-22 13:51:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17535570                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcfe2a5e9f1a698e507293571478cb03d9f7357df5abe20e6533d42e70c0c0449 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 139                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         | Address of the contract that produced the log                |
| \_account         | VARCHAR   | 0x6e2bfa169667c0d9addde8d532a22e05b72e8911                         |                                                              |

## 14. Table: FiatTokenV1\_event\_Unpause\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
