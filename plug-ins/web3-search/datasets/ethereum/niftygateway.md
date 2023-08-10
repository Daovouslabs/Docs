# niftygateway

## 1. Table: BuilderShop\_call\_createNewBuilderInstance\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-04-15 15:34:32+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 12245490                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x1cbf9c8f57d68ef8b90a80e93db35fe9fb99bddf4295c8b2c3d8af6c9c09f69f | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 16                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x431bd1297a1c7664d599364a427a2d926a1f58ae                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_name             | VARCHAR   | PRESSURE STONE// by Fvckrender                                     |                                                                                                                        |
| \_symbol           | VARCHAR   | PRESSURESTONEBYFVCKRENDER                                          |                                                                                                                        |
| num\_nifties       | VARCHAR   | 1                                                                  |                                                                                                                        |
| nifty\_quantities  | VARCHAR   | 10                                                                 |                                                                                                                        |
| token\_base\_uri   | VARCHAR   | https://api.niftygateway.com/pressurestone/                        |                                                                                                                        |
| creator\_name      | VARCHAR   | Fvckrender                                                         |                                                                                                                        |

## 2. Table: BuilderShop\_event\_BuilderInstanceCreated\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2020-10-09 22:48:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 11024005                                                           | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0x4e7f1af7f49a581f2c6cd96e3dd7372b2a99e1f0ac938440a4339ed9b70602a4 | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 129                                                                | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0x431bd1297a1c7664d599364a427a2d926a1f58ae                         | Address of the contract that produced the log                |
| new\_contract\_address | VARCHAR   | 0x648e89955fbe0d9e3f46c598458c87a4c355c23c                         |                                                              |
| contractId             | VARCHAR   | 76                                                                 |                                                              |

## 3. Table: NiftyRegistry\_event\_OwnerAddition\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| owner             | VARCHAR   |                                                              |             |

## 4. Table: NiftyRegistry\_event\_OwnerRemoval\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| owner             | VARCHAR   |                                                              |             |

## 5. Table: PackBuilderShop\_event\_BuilderInstanceCreated\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2021-01-27 18:13:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 11739421                                                           | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0xc2e29ac4eeb942d4dd6fee18628d541812353abce63eba5d0226d7185e91bd5c | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 18                                                                 | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0x5e156645b572dae1c3a487173fa2dfaae3a1fa22                         | Address of the contract that produced the log                |
| new\_contract\_address | VARCHAR   | 0x3ead77c1b86072d700d54efd9727a34058002c8b                         |                                                              |
| contractId             | VARCHAR   | 40                                                                 |                                                              |
