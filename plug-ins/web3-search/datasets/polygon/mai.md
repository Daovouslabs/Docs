# mai

## 1. Table: Anchor\_call\_swapFrom\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-02-14 15:04:07+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 24935389                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xa052949f18cb2b91eece32aac413cbbfd25baed7be4270c3a85561b32589b1cd | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 134                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x947d711c25220d8301c087b25ba111fe8cbf6672                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| amount             | VARCHAR   | 300000000                                                          |                                                                                                                        |

## 2. Table: Anchor\_call\_swapTo\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-09-11 03:42:01+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 18977197                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x3a9469be2bcf72cad2c181037e074a274cfcff389f4c484cbbd4ffae7e6db7ff | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 88                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x947d711c25220d8301c087b25ba111fe8cbf6672                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| amount             | VARCHAR   | 282000000000000000000                                              |                                                                                                                        |

## 3. Table: Anchor\_call\_transferToken\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-01-12 22:07:52+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 23647602                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x1438bb6b4020f37599a93efd7947c3b8801a0b090f2c83f74ad7addcee187eff | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 4                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,2                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x947d711c25220d8301c087b25ba111fe8cbf6672                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| token              | VARCHAR   | 0xa3fa99a148fa48d14ed51d610c367c61876997f1                         |                                                                                                                        |
| amountToken        | VARCHAR   | 85600000000000000000000000                                         |                                                                                                                        |

## 4. Table: Farm\_call\_add\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-08-12 19:30:32+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 31816435                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x9014ba28440f66c22c503d324adc60b08ab3210ddbbc5694404ed338a1cfc8c4 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 26                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xffd2aa58cca3a44120aaa42cea2852348a9c2ea6                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_allocPoint       | VARCHAR   | 75                                                                 |                                                                                                                        |
| \_lpToken          | VARCHAR   | 0x9a8b2601760814019b7e6ee0052e25f1c623d1e6                         |                                                                                                                        |
| \_withUpdate       | VARCHAR   | true                                                               |                                                                                                                        |
| \_depositFeeBP     | VARCHAR   | 0                                                                  |                                                                                                                        |

## 5. Table: Farm\_call\_deposit\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-01-06 04:17:06+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 37728115                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x7028381d564da37afe74aab9bcdc0336230ec88eb9df0430b42886401f378a93 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 70                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x9f9f0456005ed4e7248199b6260752e95682a883                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_pid              | VARCHAR   | 0                                                                  |                                                                                                                        |
| \_amount           | VARCHAR   | 0                                                                  |                                                                                                                        |

## 6. Table: Farm\_call\_fund\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-10-23 22:38:41+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 34717661                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xbb6e788b0cdb9c161069b8bceffdf5f2c2df7907cac97436bdb110fa1401d5c3 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 46                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,3                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x9f9f0456005ed4e7248199b6260752e95682a883                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_amount           | VARCHAR   | 400000000000000000000000                                           |                                                                                                                        |

## 7. Table: Farm\_call\_withdraw\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-05-27 07:21:09+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 28823201                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xdc81cc9ac0e94133f7846c80a849c4fec7ce47796d17c9d1f4b7a0d6099bb3f8 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 18                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x0635af5ab29fc7bba007b8cebad27b7a3d3d1958                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_pid              | VARCHAR   | 0                                                                  |                                                                                                                        |
| \_amount           | VARCHAR   | 0                                                                  |                                                                                                                        |

## 8. Table: Farm\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-21 22:24:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 24001963                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x09b8fc3df623a3afdd4b9b0c87e2f015f88b6df6ab4fcabe9b44d7c4e76998f3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 88                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x574fe4e8120c4da1741b5fd45584de7a5b521f0f                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x44042079e15b2bed922f4ffe10024e2b726c5b6c                         |                                                              |
| pid               | VARCHAR   | 1                                                                  |                                                              |
| amount            | VARCHAR   | 0                                                                  |                                                              |

## 9. Table: Farm\_event\_EmergencyWithdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-15 15:01:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 35641496                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc7cbc03e690b6250a3f7939452862de9398610f3dd8bb1fc7e10df5559041114 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 293                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcc54afcecd0d89e0b2db58f5d9e58468e7ad20dc                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xc444f30ffc745431ef839171c70082084ff12f6e                         |                                                              |
| pid               | VARCHAR   | 1                                                                  |                                                              |
| amount            | VARCHAR   | 2440857393302792                                                   |                                                              |

## 10. Table: Farm\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-10 16:10:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 44916450                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf5a6214afc7008bc7c6ec38b6f389c9470d5b961a792e79360deb643cf7f2e86 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 295                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xffd2aa58cca3a44120aaa42cea2852348a9c2ea6                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x535557295e566aaa0f07358103b8da438c5b9911                         |                                                              |
| pid               | VARCHAR   | 0                                                                  |                                                              |
| amount            | VARCHAR   | 0                                                                  |                                                              |

## 11. Table: MAI\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-07 00:57:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 37762816                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf5dc48507475afd0d4d901ee07c3ffd384e426f8da23beb829e0e3e3e8e56549 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 553                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa3fa99a148fa48d14ed51d610c367c61876997f1                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x7043375a2297133e32bb62b4b48804d165073245                         |                                                              |
| to                | VARCHAR   | 0x7212d38aa05d4d76c9af19721fda00c21b7f8b28                         |                                                              |
| value             | VARCHAR   | 62827275388147630080                                               |                                                              |

## 12. Table: MaiVault\_call\_borrowToken\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-02-11 21:15:49+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 39186212                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x8d874050759c1b9443752346acdeb48de02c39ecb1066128dad730ef60b156b4 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 103                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x11a33631a5b5349af3f165d2b7901a4d67e561ad                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| vaultID            | VARCHAR   | 2510                                                               |                                                                                                                        |
| amount             | VARCHAR   | 2895423749730370114589                                             |                                                                                                                        |

## 13. Table: MaiVault\_call\_createVault\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-09-22 17:57:16+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 33434016                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x86d249b10653f6b95aa3b12bc54fb027813989ba5fd7a754618db7ebce3aeff7 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 21                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x11a33631a5b5349af3f165d2b7901a4d67e561ad                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 14. Table: MaiVault\_call\_depositCollateral\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-11-27 14:55:38+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 21864321                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xd3114c7e0422c7b9c55d115863839d4f4ef77992ef34da825d612c529ac37b81 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 68                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x11a33631a5b5349af3f165d2b7901a4d67e561ad                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| vaultID            | VARCHAR   | 1260                                                               |                                                                                                                        |
| amount             | VARCHAR   | 23888190757486061                                                  |                                                                                                                        |

## 15. Table: MaiVault\_call\_destroyVault\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-09-02 08:15:11+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 32589823                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x3e907c412cdb9cf3c1238611f20ee4b8919fa669128e3b38f24c13d8911d5241 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 49                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x37131aedd3da288467b6ebe9a77c523a700e6ca1                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| vaultID            | VARCHAR   | 1527                                                               |                                                                                                                        |

## 16. Table: MaiVault\_call\_liquidateVault\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-11-08 21:22:50+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 35369767                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x735685420c5415eca4d6439f518c31724e2f9ecbc5455ce6edf652e7898d2702 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 9                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 6                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x1dcc1f864a4bd0b8f4ad33594b758b68e9fa872c                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| vaultID            | VARCHAR   | 83                                                                 |                                                                                                                        |

## 17. Table: MaiVault\_call\_payBackToken\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-08-02 10:06:25+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 45815326                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x758afbcf18d2338a95f21a2fef7603da628c2de6677fe397fc420d704a2f9faa | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 71                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x1dcc1f864a4bd0b8f4ad33594b758b68e9fa872c                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| vaultID            | VARCHAR   | 45                                                                 |                                                                                                                        |
| amount             | VARCHAR   | 140625000000000000                                                 |                                                                                                                        |

## 18. Table: MaiVault\_call\_safeTransferFrom\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-09-22 15:58:03+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 19389301                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xc6095edcc4eed42bb240f17ea5972d8b134906a78091239bd8429145e16bdb07 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 391                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 1                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3fd939b017b31eaadf9ae50c7ff7fa5c0661d47c                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| from               | VARCHAR   | 0x0ae04c4ba132737c855bfde51d175a087d9c51a4                         |                                                                                                                        |
| to                 | VARCHAR   | 0xd796cf165c954ba4371c90a445ae624996eb4d86                         |                                                                                                                        |
| tokenId            | VARCHAR   | 282                                                                |                                                                                                                        |
| \_data             | VARCHAR   | 0x                                                                 |                                                                                                                        |

## 19. Table: MaiVault\_call\_transferFrom\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-05-25 14:07:26+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 43133269                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xa0ad72a77bd264d958ec32d60aa5ad1f99c4d3e041c2c3df12b8ebb22bcf3865 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 236                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 6,6,0                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xa3fa99a148fa48d14ed51d610c367c61876997f1                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| from               | VARCHAR   | 0xc834b3cb4134f3f5b7080d92cf6360bf5700dece                         |                                                                                                                        |
| to                 | VARCHAR   | 0x0bef3882798219eeaf40a8b63563a3d3ab6092ab                         |                                                                                                                        |
| tokenId            | VARCHAR   | 120347714561010122752                                              |                                                                                                                        |

## 20. Table: MaiVault\_call\_transferOwnership\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-04-08 15:06:33+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 26894684                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x2a24b402871becdbe7504dfdfbc862cc8770367bcb1d81d0f9eba03dc46583b8 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 40                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x178f1c95c85fe7221c7a6a3d6f12b7da3253eeae                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| newOwner           | VARCHAR   | 0x3feacf904b152b1880bde8bf04ac9eb636fee4d8                         |                                                                                                                        |

## 21. Table: MaiVault\_call\_transferToken\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-04-02 00:58:14+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 26636484                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xb5beddeb7a2328e45ac6931ed04e24e0af9d3871ff39c355b93d3ca8bf7e4fd8 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 2                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x37131aedd3da288467b6ebe9a77c523a700e6ca1                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| to                 | VARCHAR   | 0x608cfc1575b56a82a352f14d61be100fa9709d75                         |                                                                                                                        |
| token              | VARCHAR   | 0x37131aedd3da288467b6ebe9a77c523a700e6ca1                         |                                                                                                                        |
| amountToken        | VARCHAR   | 36899878                                                           |                                                                                                                        |

## 22. Table: MaiVault\_call\_withdrawCollateral\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-01-01 23:28:39+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 37559852                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xe92ab415d71e073186c86e9cf0cd664cb87eaa16038214f1bfcfda4bfcc243aa | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 68                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x11a33631a5b5349af3f165d2b7901a4d67e561ad                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| vaultID            | VARCHAR   | 3164                                                               |                                                                                                                        |
| amount             | VARCHAR   | 10449991016172                                                     |                                                                                                                        |

## 23. Table: MaiVault\_event\_BorrowToken\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-19 19:50:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 32083604                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf271b2ae033ebf06604b5f97bfd07ec558646c6c72a73e677181140765e164a9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 200                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x11a33631a5b5349af3f165d2b7901a4d67e561ad                         | Address of the contract that produced the log                |
| vaultID           | VARCHAR   | 890                                                                |                                                              |
| amount            | VARCHAR   | 500000000000000000000                                              |                                                              |

## 24. Table: MaiVault\_event\_CreateVault\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-26 00:20:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 21802912                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8cefed723fa23e7711888aa54df99b74bfa249fa130283d797103049573e3086 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 705                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x11a33631a5b5349af3f165d2b7901a4d67e561ad                         | Address of the contract that produced the log                |
| vaultID           | VARCHAR   | 1249                                                               |                                                              |
| creator           | VARCHAR   | 0x1e71782f4a40d56e46000ba5b02bea6c3c508adc                         |                                                              |

## 25. Table: MaiVault\_event\_DepositCollateral\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-01 05:40:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 43395998                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7ef6c1440b6b6d275f037ff76f574431e11bd4af398aa371ee1e4a5f8a700342 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 165                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x11a33631a5b5349af3f165d2b7901a4d67e561ad                         | Address of the contract that produced the log                |
| vaultID           | VARCHAR   | 1236                                                               |                                                              |
| amount            | VARCHAR   | 10992942390395767                                                  |                                                              |

## 26. Table: MaiVault\_event\_DestroyVault\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-13 17:34:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 42662385                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4ee6cf3464eefe4d78d3784d9a8e3e9b4fedfc5b7faf236a5ebbe977bb713262 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 306                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1f0aa72b980d65518e88841ba1da075bd43fa933                         | Address of the contract that produced the log                |
| vaultID           | VARCHAR   | 255                                                                |                                                              |

## 27. Table: MaiVault\_event\_LiquidateVault\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2021-07-19 20:33:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 17045260                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xe631ab341f7f68d42641f68059d55389835c1b78ddbf5bab89d2227dc79010e7 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 216                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x88d84a85a87ed12b8f098e8953b322ff789fcd1a                         | Address of the contract that produced the log                |
| vaultID              | VARCHAR   | 15                                                                 |                                                              |
| owner                | VARCHAR   | 0xc824c8098ad962dcd0e8d980b590292d929e952c                         |                                                              |
| buyer                | VARCHAR   | 0xe0f1f6d9b57db098a1c786a835a55a1ff64d39ee                         |                                                              |
| debtRepaid           | VARCHAR   | 1188868244164943224                                                |                                                              |
| collateralLiquidated | VARCHAR   | 1769858696574107572                                                |                                                              |
| closingFee           | VARCHAR   | 8044812257155034                                                   |                                                              |

## 28. Table: MaiVault\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-11 09:32:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 35473042                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9e7fc97a94506afad1a12cbc5cc27fb4dd78e8fb0cdde35b4196632109bce3fb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 328                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7d75f83f0abe2ece0b9daf41cceddf38cb66146b                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x985a29e88e75394dbdae41a269409f701ccf6a43                         |                                                              |
| newOwner          | VARCHAR   | 0x1d8a6b7941ef1349c1b5e378783cd56b001ecfbc                         |                                                              |

## 29. Table: MaiVault\_event\_PayBackToken\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-12 04:07:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 41431700                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe9a29986c97ff8d23c900b7ff67a8a9b037c57f73211b2ff603d862b97028283 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 301                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x11a33631a5b5349af3f165d2b7901a4d67e561ad                         | Address of the contract that produced the log                |
| vaultID           | VARCHAR   | 2127                                                               |                                                              |
| amount            | VARCHAR   | 153129762109659925603                                              |                                                              |
| closingFee        | VARCHAR   | 404246736974980                                                    |                                                              |

## 30. Table: MaiVault\_event\_TransferVault\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-30 23:12:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 27772759                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9152a2a64b2d278099b7c97edb8541632acd7e8a74c52560ba638043b64fceaf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 24                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa3fa99a148fa48d14ed51d610c367c61876997f1                         | Address of the contract that produced the log                |
| vaultID           | VARCHAR   | 5931                                                               |                                                              |
| from              | VARCHAR   | 0x595b3e98641c4d66900a24aa6ada590b41ef85aa                         |                                                              |
| to                | VARCHAR   | 0x72d4d59f31d0cb4a4213a5dc81fc0108241ecc71                         |                                                              |

## 31. Table: MaiVault\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-11 19:07:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 25837410                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0b2dd926553fadeaf153781b31ab330300aabbdc8a646a60b4ac1e5b1771bf38 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 262                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x11a33631a5b5349af3f165d2b7901a4d67e561ad                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xd8d22817d216164d09ca5909a70beca608d65aa9                         |                                                              |
| to                | VARCHAR   | 0x562a7ccf32fb6ee2ac2fe37b9ea5d55f4ce04d08                         |                                                              |
| tokenId           | VARCHAR   | 663                                                                |                                                              |

## 32. Table: MaiVault\_event\_WithdrawCollateral\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-28 21:18:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45634419                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc3ae7a431f83562ce265125b1ec2589168292c5caa7fa1308739cc485231f17a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 263                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x11a33631a5b5349af3f165d2b7901a4d67e561ad                         | Address of the contract that produced the log                |
| vaultID           | VARCHAR   | 2048                                                               |                                                              |
| amount            | VARCHAR   | 1508398911486829099                                                |                                                              |

## 33. Table: QI\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-04 01:50:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45881187                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2aa74fbcf47176778c2c204809882d7762fdee4036a8d0ef21e827748b6e920e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 149                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x580a84c73811e1839f75d86d75d88cca0c241ff4                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xcc54afcecd0d89e0b2db58f5d9e58468e7ad20dc                         |                                                              |
| to                | VARCHAR   | 0xd9585bfa7d956066141766bb332c87fffc03d3a9                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 34. Table: camToken\_call\_enter\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-06-06 08:36:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 43590004                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x424415058335a3ff400895e5a3819bd7dbdf497a44fc082b33f4f668e576d48c | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 82                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xba6273a78a23169e01317bd0f6338547f869e8df                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_amount           | VARCHAR   | 3881999                                                            |                                                                                                                        |

## 35. Table: camToken\_call\_leave\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-05-27 01:25:14+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 28813359                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x3c10b6357998421f425af174070fba51a6577cd08cf491864d1d0e1f212fcb66 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 4                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 2                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x0470cd31c8fcc42671465880ba81d631f0b76c1d                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_share            | VARCHAR   | 125111008662900                                                    |                                                                                                                        |

## 36. Table: camToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-05 04:04:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45924907                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6abe41fc79f2f3a7e2d48741f7886cb4a3cb27d85f5a206c9f6a18870e685cd7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 86                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0470cd31c8fcc42671465880ba81d631f0b76c1d                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x9224bbb4e0fbe2f2f8fab55debc41eb21fdfb804                         |                                                              |
| to                | VARCHAR   | 0x11a33631a5b5349af3f165d2b7901a4d67e561ad                         |                                                              |
| value             | VARCHAR   | 442852290564967                                                    |                                                              |

## 37. Table: escrowedQi\_event\_Enter\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-28 12:24:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 36172218                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x972a4aaaa782670dc73eb53c49b6b44e5ab5d0bad6236b7a9b421891537659aa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 327                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x880decade22ad9c58a8a4202ef143c4f305100b3                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x039e8cb6cf84518696939ea80ff8e021b871fde9                         |                                                              |
| amount            | VARCHAR   | 5021000000000000000                                                |                                                              |
| endBlock          | VARCHAR   | 96220263                                                           |                                                              |

## 38. Table: escrowedQi\_event\_Leave\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-04 13:13:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45899915                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf9bca67daa4fbb55704475e34811dab5aa85e29d494e627b66dfa28154e8fc20 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 392                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x880decade22ad9c58a8a4202ef143c4f305100b3                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x3120670b117855b54306c548216a4c25dc704982                         |                                                              |
| amount            | VARCHAR   | 5820709688631645254                                                |                                                              |
| endBlock          | VARCHAR   | 25765020                                                           |                                                              |

## 39. Table: escrowedQi\_event\_Transfer\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| from              | VARCHAR   |                                                              |             |
| to                | VARCHAR   |                                                              |             |
| value             | VARCHAR   |                                                              |             |
