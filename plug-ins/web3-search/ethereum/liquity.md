# liquity

## 1. Table: ActivePool\_event\_ActivePoolETHBalanceUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-01 10:34:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13332912                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xab6bb459195a73323c6e9b6ae54283acb6c5813529295b5cd77cb74819c09ab5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 127                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdf9eb223bafbe5c5271415c75aecd68c21fe3d7f                         | Address of the contract that produced the log                |
| \_ETH             | VARCHAR   | 523548161387922045772113                                           |                                                              |

## 2. Table: ActivePool\_event\_ActivePoolLUSDDebtUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-13 01:32:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15330498                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd8f11bb1e0e6446583f7818bd20e98ebbae1b15d6a49f419747ed393e836d1eb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 578                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdf9eb223bafbe5c5271415c75aecd68c21fe3d7f                         | Address of the contract that produced the log                |
| \_LUSDDebt        | VARCHAR   | 186091766773978928380325882                                        |                                                              |

## 3. Table: ActivePool\_event\_ETHBalanceUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_newBalance      | VARCHAR   |                                                              |             |

## 4. Table: ActivePool\_event\_EtherSent\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-01 11:00:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17385525                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd7c24a924c6d4664e83e886883b1169e9f536dbbacec454d5f78f78307f19b3c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 429                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdf9eb223bafbe5c5271415c75aecd68c21fe3d7f                         | Address of the contract that produced the log                |
| \_to              | VARCHAR   | 0xa5c80308746ced604284e60ed4cdd4a871b47a23                         |                                                              |
| \_amount          | VARCHAR   | 0                                                                  |                                                              |

## 5. Table: ActivePool\_event\_LUSDBalanceUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_newBalance      | VARCHAR   |                                                              |             |

## 6. Table: BorrowerOperations\_event\_LUSDBorrowingFeePaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-28 12:32:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17144642                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xad5bc0eab3f28af4a44810932be78912fe4601f6dc7734835979eb5bcd0d3679 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 179                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x24179cd81c9e782a4096035f7ec97fb8b783e007                         | Address of the contract that produced the log                |
| \_borrower        | VARCHAR   | 0x136f6a2b398eaeed4a33a58b26e52fa7056fd4e7                         |                                                              |
| \_LUSDFee         | VARCHAR   | 0                                                                  |                                                              |

## 7. Table: BorrowerOperations\_event\_TroveCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-06 01:15:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13948904                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4b34644cf649a66e7017588e1337c95ebe2c95e75ada28c26457db89aca9a145 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 130                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x24179cd81c9e782a4096035f7ec97fb8b783e007                         | Address of the contract that produced the log                |
| \_borrower        | VARCHAR   | 0x0561a78021d8966ddd20c28c6c4318d8675ee1f0                         |                                                              |
| arrayIndex        | VARCHAR   | 1284                                                               |                                                              |

## 8. Table: BorrowerOperations\_event\_TroveUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-15 14:46:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13620930                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x55fcd8030d0f9940d929645fc36e894d9a318ae89dffa10c4f54eb7a0090757d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 390                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x24179cd81c9e782a4096035f7ec97fb8b783e007                         | Address of the contract that produced the log                |
| \_borrower        | VARCHAR   | 0x44a3ba8f42d26a4596719eea67240f7e8fa9e727                         |                                                              |
| \_debt            | VARCHAR   | 2009040044534808123800                                             |                                                              |
| \_coll            | VARCHAR   | 50000000000000000000                                               |                                                              |
| stake             | VARCHAR   | 50000000000000000000                                               |                                                              |
| operation         | VARCHAR   | 0                                                                  |                                                              |

## 9. Table: CollSurplusPool\_event\_CollBalanceUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-22 12:54:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17748796                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x649807fa1657a21ab39a280011d22b78946fcc373f38ae3f13cb404df5d95cf1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 73                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3d32e8b97ed5881324241cf03b2da5e2ebce5521                         | Address of the contract that produced the log                |
| \_account         | VARCHAR   | 0x2e291e566165604d6ccfbfc099014d1b02c50396                         |                                                              |
| \_newBalance      | VARCHAR   | 0                                                                  |                                                              |

## 10. Table: CollSurplusPool\_event\_EtherSent\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-20 11:55:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14423125                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf020798486d9ca40a2347b9aa73d806c56bcf70cf901efbd702fab3018c2f312 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 22                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3d32e8b97ed5881324241cf03b2da5e2ebce5521                         | Address of the contract that produced the log                |
| \_to              | VARCHAR   | 0xe59706fb08382147c44bf93e6921456524946491                         |                                                              |
| \_amount          | VARCHAR   | 13040247997196018019                                               |                                                              |

## 11. Table: DefaultPool\_event\_DefaultPoolETHBalanceUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-22 00:30:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17311295                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x179433b320d7f232c76833421821db0c13e1eec94a71dd01a5ddb2c7ec81b45e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x896a3f03176f05cfbb4f006bfcd8723f2b0d741c                         | Address of the contract that produced the log                |
| \_ETH             | VARCHAR   | 0                                                                  |                                                              |

## 12. Table: DefaultPool\_event\_DefaultPoolLUSDDebtUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-15 11:55:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17265019                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x65cf9dfa096d0f31638d086ff735f78f917ed64e9803811257c8c0e5adffd346 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x896a3f03176f05cfbb4f006bfcd8723f2b0d741c                         | Address of the contract that produced the log                |
| \_LUSDDebt        | VARCHAR   | 0                                                                  |                                                              |

## 13. Table: DefaultPool\_event\_ETHBalanceUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_newBalance      | VARCHAR   |                                                              |             |

## 14. Table: DefaultPool\_event\_EtherSent\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-15 11:55:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17265019                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x65cf9dfa096d0f31638d086ff735f78f917ed64e9803811257c8c0e5adffd346 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 8                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x896a3f03176f05cfbb4f006bfcd8723f2b0d741c                         | Address of the contract that produced the log                |
| \_to              | VARCHAR   | 0xdf9eb223bafbe5c5271415c75aecd68c21fe3d7f                         |                                                              |
| \_amount          | VARCHAR   | 0                                                                  |                                                              |

## 15. Table: DefaultPool\_event\_LUSDBalanceUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_newBalance      | VARCHAR   |                                                              |             |

## 16. Table: LQTYToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-27 12:23:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17350365                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfc3308301ec53f430a5410c22e36965ff897cca0a1bdb3c93cd1d9191ed60790 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 70                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6dea81c8171d0ba574754ef6f8b412f2ed88c54d                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x000000000dfde7deaf24138722987c9a6991e2d4                         |                                                              |
| to                | VARCHAR   | 0x410ed1cbcea3b3990a3f27362c06c3c5d1e75d08                         |                                                              |
| value             | VARCHAR   | 40000000000000000000000                                            |                                                              |

## 17. Table: LUSDToken\_call\_burn\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-05-31 20:42:11+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17381288                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x9ee9a5104c69d4f77305723a56eb13fd417996ce117b28ecf1dcfde1540cc1a9 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 100                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 18                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x5f98805a4e8be255a32880fdec7f6728c6568ba0                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_account          | VARCHAR   | 0xbafc16978f1b4e835ad4037e030abb6dfb759e62                         |                                                                                                                        |
| \_amount           | VARCHAR   | 0                                                                  |                                                                                                                        |

## 18. Table: LUSDToken\_call\_mint\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-06-19 13:32:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17514111                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x00e69f5b6297d1c873368f0af1f49b8f7f9c1c4940f9d745175cf473369d3cbf | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 57                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0,23                                                             | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x5f98805a4e8be255a32880fdec7f6728c6568ba0                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_account          | VARCHAR   | 0x3cc960fa1e49eeb802c8659eb01e8913a6c096ec                         |                                                                                                                        |
| \_amount           | VARCHAR   | 1800000000000000000000                                             |                                                                                                                        |

## 19. Table: LUSDToken\_event\_LUSDTokenBalanceUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_user            | VARCHAR   |                                                              |             |
| \_amount          | VARCHAR   |                                                              |             |

## 20. Table: LUSDToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-07 21:39:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15698944                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6d37b845726062233ab6ba9694acf55507e12f82ca05f82d53c1c41ca90df5cb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 386                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5f98805a4e8be255a32880fdec7f6728c6568ba0                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x4e0924d3a751be199c426d52fb1f2337fa96f736                         |                                                              |
| to                | VARCHAR   | 0x75cfe89fc94c9e6d36cf65e09953a9e5d977d030                         |                                                              |
| value             | VARCHAR   | 181017608157131592012                                              |                                                              |

## 21. Table: StabilityPool\_event\_DepositSnapshotUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-20 20:56:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16450540                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xee11e4fe941954fc7c8c809554f1b636cad62488edb9caf864003065b0621b81 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 382                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x66017d22b0f8556afdd19fc67041899eb65a21bb                         | Address of the contract that produced the log                |
| \_depositor       | VARCHAR   | 0x38bda5bc5d7c5f02b44dd2ae77fd25cb398d745a                         |                                                              |
| \_P               | VARCHAR   | 0                                                                  |                                                              |
| \_S               | VARCHAR   | 0                                                                  |                                                              |
| \_G               | VARCHAR   | 0                                                                  |                                                              |

## 22. Table: StabilityPool\_event\_ETHGainWithdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-27 01:17:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15418693                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa21e10b2fd8bce75abea5373bc1aaa79b0cf2c2ad06aaa4900b5f8479da4261c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 50                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x66017d22b0f8556afdd19fc67041899eb65a21bb                         | Address of the contract that produced the log                |
| \_depositor       | VARCHAR   | 0x0f632c22af8645401d15455fad789bdf9222d112                         |                                                              |
| \_ETH             | VARCHAR   | 0                                                                  |                                                              |
| \_LUSDLoss        | VARCHAR   | 0                                                                  |                                                              |

## 23. Table: StabilityPool\_event\_EpochUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_currentEpoch    | VARCHAR   |                                                              |             |

## 24. Table: StabilityPool\_event\_EtherSent\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-06 21:02:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17858465                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd18fc872104c9ab6b0123ac31dfef8fad47975198ce326a391f9ac97930bc775 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 296                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x66017d22b0f8556afdd19fc67041899eb65a21bb                         | Address of the contract that produced the log                |
| \_to              | VARCHAR   | 0x67c694a2baae46a27a0435008397ae010611bd20                         |                                                              |
| \_amount          | VARCHAR   | 881634007267791125                                                 |                                                              |

## 25. Table: StabilityPool\_event\_FrontEndStakeChanged\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2023-06-01 10:00:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 17385227                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x5e6e8bf2526fcb2e76b142285a3a9b3f653320afcc98688e375d7fd4978fa380 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 63                                                                 | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x66017d22b0f8556afdd19fc67041899eb65a21bb                         | Address of the contract that produced the log                |
| \_frontEnd         | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_newFrontEndStake | VARCHAR   | 42934152324723438651193617                                         |                                                              |
| \_depositor        | VARCHAR   | 0x896d8a30c32ead64f2e1195c2c8e0932be7dc20b                         |                                                              |

## 26. Table: StabilityPool\_event\_FrontEndTagSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-29 10:25:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13899655                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x69e4de7ebf22e4e2b9c3f32c21721dc55c1c943521e6502daf1262991c792596 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 57                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x66017d22b0f8556afdd19fc67041899eb65a21bb                         | Address of the contract that produced the log                |
| \_depositor       | VARCHAR   | 0xeb6b51d158a5fdf67ba74d66dfe44b396e4e227d                         |                                                              |
| \_frontEnd        | VARCHAR   | 0x30e5d10dc30a0ce2545a4dbe8de4fcba590062c5                         |                                                              |

## 27. Table: StabilityPool\_event\_G\_Updated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-07 23:01:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16580045                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5fe4b95a1c3de1e464179d22f59cd3392bc85bac4415ef1d35f1d41c3b308f24 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 291                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x66017d22b0f8556afdd19fc67041899eb65a21bb                         | Address of the contract that produced the log                |
| \_G               | VARCHAR   | 350484538916608741185514823023747942092                            |                                                              |
| \_epoch           | VARCHAR   | 0                                                                  |                                                              |
| \_scale           | VARCHAR   | 0                                                                  |                                                              |

## 28. Table: StabilityPool\_event\_LQTYPaidToDepositor\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-10 02:06:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13774604                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5ab97104c8701fd220b324840fb66ce7798e3dd527c1a949901272326296b57f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 392                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x66017d22b0f8556afdd19fc67041899eb65a21bb                         | Address of the contract that produced the log                |
| \_depositor       | VARCHAR   | 0x0d3abaa7e088c2c82f54b2f47613da438ea8c598                         |                                                              |
| \_LQTY            | VARCHAR   | 2775870304058068652934                                             |                                                              |

## 29. Table: StabilityPool\_event\_LQTYPaidToFrontEnd\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-23 05:46:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17319957                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa3b892faf5eaa933dbb7b60af62eeda4a641d2848cc93424885d82659f04fdee | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 294                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x66017d22b0f8556afdd19fc67041899eb65a21bb                         | Address of the contract that produced the log                |
| \_frontEnd        | VARCHAR   | 0x04e313306c008f704ad6e34a08d6523db3a271f9                         |                                                              |
| \_LQTY            | VARCHAR   | 0                                                                  |                                                              |

## 30. Table: StabilityPool\_event\_P\_Updated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-05 12:09:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12574354                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb5b290017d579cd63fd60f2fb01bb8d0095996359ce3c03bbd5e002a0fa825b8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 40                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x66017d22b0f8556afdd19fc67041899eb65a21bb                         | Address of the contract that produced the log                |
| \_P               | VARCHAR   | 911004556833527350                                                 |                                                              |

## 31. Table: StabilityPool\_event\_S\_Updated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-23 17:19:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12491894                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x290068c30026c482354208969aa5ec7f9d9c1434092e87cd6cdac7aee618067b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 151                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x66017d22b0f8556afdd19fc67041899eb65a21bb                         | Address of the contract that produced the log                |
| \_S               | VARCHAR   | 46334972520684964934371473919624                                   |                                                              |
| \_epoch           | VARCHAR   | 0                                                                  |                                                              |
| \_scale           | VARCHAR   | 0                                                                  |                                                              |

## 32. Table: StabilityPool\_event\_ScaleUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_currentScale    | VARCHAR   |                                                              |             |

## 33. Table: StabilityPool\_event\_StabilityPoolETHBalanceUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-28 16:53:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17145940                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6a6f5d151ba139b3669747ab0e05d3ecdf067b8826e42d2dc1a39a3d1e801816 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 55                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x66017d22b0f8556afdd19fc67041899eb65a21bb                         | Address of the contract that produced the log                |
| \_newBalance      | VARCHAR   | 1802809337988783430319                                             |                                                              |

## 34. Table: StabilityPool\_event\_StabilityPoolLUSDBalanceUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-19 00:43:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13052489                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x692535c260ef77ecbed346aa2ce9c7115631d9dcf36336e95e37d7bb06cfd429 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 257                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x66017d22b0f8556afdd19fc67041899eb65a21bb                         | Address of the contract that produced the log                |
| \_newBalance      | VARCHAR   | 511929946707682993538937623                                        |                                                              |

## 35. Table: StabilityPool\_event\_UserDepositChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-08 17:39:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16585601                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe6fc9ca2cd2891f12a69fffece2614f19af8277c6d9fdf883aef010e882cc6c0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 114                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x66017d22b0f8556afdd19fc67041899eb65a21bb                         | Address of the contract that produced the log                |
| \_depositor       | VARCHAR   | 0x00ff66ab8699aafa050ee5ef5041d1503aa0849a                         |                                                              |
| \_newDeposit      | VARCHAR   | 6997720620888055764288137                                          |                                                              |

## 36. Table: TroveManager\_event\_BaseRateUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-06 14:50:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14532968                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x09eb7583f541435f889d3bdeec74bd2e205b25cae20a7581ad150d54e975f369 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 259                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa39739ef8b0231dbfa0dcda07d7e29faabcf4bb2                         | Address of the contract that produced the log                |
| \_baseRate        | VARCHAR   | 61773070                                                           |                                                              |

## 37. Table: TroveManager\_event\_LastFeeOpTimeUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-02 14:16:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17827852                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x02353dc947f2c825a8e7247a984b6c711c754eb6738e1ed7af24b635edcb41d5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 273                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa39739ef8b0231dbfa0dcda07d7e29faabcf4bb2                         | Address of the contract that produced the log                |
| \_lastFeeOpTime   | VARCHAR   | 1690985819                                                         |                                                              |

## 38. Table: TroveManager\_event\_Liquidation\_history

| Column                | Type      | Example                                                            | Description                                                  |
| --------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp      | TIMESTAMP | 2023-06-14 20:05:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number         | INTEGER   | 17480438                                                           | The block number where this event was emitted                |
| transaction\_hash     | VARCHAR   | 0xc2e73bfb897a5ff18b0e0016c5eda92ca0fe9dc41015a6f69d9b48ed48893301 | Hash of the transactions in which this event was emitted     |
| log\_index            | INTEGER   | 53                                                                 | Integer of the log index position in the block of this event |
| contract\_address     | VARCHAR   | 0xa39739ef8b0231dbfa0dcda07d7e29faabcf4bb2                         | Address of the contract that produced the log                |
| \_liquidatedDebt      | VARCHAR   | 18004948095902498027174                                            |                                                              |
| \_liquidatedColl      | VARCHAR   | 11542000000000000000                                               |                                                              |
| \_collGasCompensation | VARCHAR   | 58000000000000000                                                  |                                                              |
| \_LUSDGasCompensation | VARCHAR   | 200000000000000000000                                              |                                                              |

## 39. Table: TroveManager\_event\_Redemption\_history

| Column                | Type      | Example                                                            | Description                                                  |
| --------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp      | TIMESTAMP | 2022-01-23 17:15:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number         | INTEGER   | 14063194                                                           | The block number where this event was emitted                |
| transaction\_hash     | VARCHAR   | 0xd48cd122e66395cee9e542a1fcdea7e641edda7458e405d34f640e18e3528561 | Hash of the transactions in which this event was emitted     |
| log\_index            | INTEGER   | 288                                                                | Integer of the log index position in the block of this event |
| contract\_address     | VARCHAR   | 0xa39739ef8b0231dbfa0dcda07d7e29faabcf4bb2                         | Address of the contract that produced the log                |
| \_attemptedLUSDAmount | VARCHAR   | 378370000000000000000                                              |                                                              |
| \_actualLUSDAmount    | VARCHAR   | 378370000000000000000                                              |                                                              |
| \_ETHSent             | VARCHAR   | 155509393772058688                                                 |                                                              |
| \_ETHFee              | VARCHAR   | 782290336004034                                                    |                                                              |

## 40. Table: TroveManager\_event\_TotalStakesUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-05 03:28:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12765071                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xda4782edd024d8003e97640b80ad25df6fb80f8c1a052adcd0f7fae7443d1a02 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 247                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa39739ef8b0231dbfa0dcda07d7e29faabcf4bb2                         | Address of the contract that produced the log                |
| \_newTotalStakes  | VARCHAR   | 1002058097753899229554450                                          |                                                              |

## 41. Table: TroveManager\_event\_TroveIndexUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-25 18:04:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13684961                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x27077650f4b54b11cb1a7c47a8ebe01e565f973363a0b8317695289e7f4d9946 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 465                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa39739ef8b0231dbfa0dcda07d7e29faabcf4bb2                         | Address of the contract that produced the log                |
| \_borrower        | VARCHAR   | 0x6ba02fe33c0d206c7c411c732345c47ca4771972                         |                                                              |
| \_newIndex        | VARCHAR   | 550                                                                |                                                              |

## 42. Table: TroveManager\_event\_TroveLiquidated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-06 09:24:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14332511                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1eed867d89b628fbaf4a8297b94f670d7d2a80d6b8eb04c927f9165e8ea4ba20 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa39739ef8b0231dbfa0dcda07d7e29faabcf4bb2                         | Address of the contract that produced the log                |
| \_borrower        | VARCHAR   | 0x63b63467daa472372e3f37ac049c1806b50bfd81                         |                                                              |
| \_debt            | VARCHAR   | 3179316220895794200044                                             |                                                              |
| \_coll            | VARCHAR   | 1327153053111653792                                                |                                                              |
| \_operation       | VARCHAR   | 1                                                                  |                                                              |

## 43. Table: TroveManager\_event\_TroveUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-18 22:47:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13642078                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4d241121f96854f9e51ec06fe6e7486229f8c55ed2d91a57a5ebed1544831096 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 524                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa39739ef8b0231dbfa0dcda07d7e29faabcf4bb2                         | Address of the contract that produced the log                |
| \_borrower        | VARCHAR   | 0xb56844e9e7882bfcf1892d4ae78b2dd9126fc6ae                         |                                                              |
| \_debt            | VARCHAR   | 10578383312665512010614                                            |                                                              |
| \_coll            | VARCHAR   | 2930982533806168498                                                |                                                              |
| \_stake           | VARCHAR   | 2930982533806168498                                                |                                                              |
| \_operation       | VARCHAR   | 3                                                                  |                                                              |
