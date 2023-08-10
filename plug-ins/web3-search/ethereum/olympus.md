# olympus

## 1. Table: OP\_AlchemixCustomTreasury\_call\_deposit\_history

| Column                  | Type      | Example                                                            | Description                                                                                                            |
| ----------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp        | TIMESTAMP | 2022-01-05 22:39:25+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number           | INTEGER   | 13948196                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash       | VARCHAR   | 0x0358f59bc8296022a4f817be9ab10a717dc47bb8cae0263cc54a2b344437984c | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index      | INTEGER   | 289                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address          | VARCHAR   | 14                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address             | VARCHAR   | 0x246c00f93001c344038a0d9cf012754b539c1014                         | Address of the called contract                                                                                         |
| status                  | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                   | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_principleTokenAddress | VARCHAR   | 0xc3f279090a47e80990fe3a9c30d24cb117ef91a8                         |                                                                                                                        |
| \_amountPrincipleToken  | VARCHAR   | 5107479194847094986                                                |                                                                                                                        |
| \_amountPayoutToken     | VARCHAR   | 38232553644418178665                                               |                                                                                                                        |

## 2. Table: OP\_AlchemixCustomTreasury\_call\_toggleBondContract\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-12-21 12:18:53+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 13848488                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x437ee00f84c59095e4001bcb4d6fee7a60b823256e47fc99f44dcde98372b9e0 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 294                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x246c00f93001c344038a0d9cf012754b539c1014                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_bondContract     | VARCHAR   | 0xd9fee3cdbf0b55461977756dbaee4421cc0a52e0                         |                                                                                                                        |

## 3. Table: OP\_AlchemixCustomTreasury\_call\_transferManagment\_history

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
| \_newOwner         | VARCHAR   |                                                                                                                        |             |

## 4. Table: OP\_AlchemixCustomTreasury\_call\_withdraw\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-12-17 06:29:07+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 13821024                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x56141756ea696c59a1dcd77afefe9e428ed0b2f29caa27244992ccb3c5f2d127 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 83                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0,0                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x246c00f93001c344038a0d9cf012754b539c1014                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_token            | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                                                                                        |
| \_destination      | VARCHAR   | 0x9e2b6378ee8ad2a4a95fe481d63caba8fb0ebbf9                         |                                                                                                                        |
| \_amount           | VARCHAR   | 64084290098217161110                                               |                                                                                                                        |

## 5. Table: OP\_AlchemixCustomTreasury\_event\_BondContractToggled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-21 12:18:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13848488                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x437ee00f84c59095e4001bcb4d6fee7a60b823256e47fc99f44dcde98372b9e0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 306                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x246c00f93001c344038a0d9cf012754b539c1014                         | Address of the contract that produced the log                |
| bondContract      | VARCHAR   | 0xd9fee3cdbf0b55461977756dbaee4421cc0a52e0                         |                                                              |
| approved          | VARCHAR   | true                                                               |                                                              |

## 6. Table: OP\_AlchemixCustomTreasury\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-13 16:42:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13411099                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0756765c44958e4d28284b54f0bf92a2304ed6a20fca8f431388e3ac3032d09d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 142                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x246c00f93001c344038a0d9cf012754b539c1014                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0xc3f279090a47e80990fe3a9c30d24cb117ef91a8                         |                                                              |
| destination       | VARCHAR   | 0x9e2b6378ee8ad2a4a95fe481d63caba8fb0ebbf9                         |                                                              |
| amount            | VARCHAR   | 110689764153088348000                                              |                                                              |
