# common

## 1. Table: All\_call\_setBaseURI\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-05-27 14:26:23+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17350975                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xbe841aab2f078a63ac6d5e2fb1bfcb992c7d23cc1690f5d900902768e4a21b55 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 8                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xee2c03ced8b6755e8d76ab144677f5f350203cab                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| baseURI            | VARCHAR   | ipfs://QmddrkXJRuokMoHgfhfcSy3qMoJH9krVL4wg9vcQsDa3W3/             |                                                                                                                        |

## 2. Table: All\_event\_AddedOwner\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-03 21:07:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11583888                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf70a06683543d5e5bbfe47c0f4d7d9ae39f480cfa3eccc2b1166c6354931cee4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 175                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeb3107117fead7de89cd14d463d340a2e6917769                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x45a10f35befa4ab841c77860204b133118b7ccae                         |                                                              |

## 3. Table: All\_event\_ApprovalForAll\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-04 12:11:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11587902                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4105392b2d885e965c2ac03461c869b62c52ea5acd1f4dc2af2de35ba7e6ce92 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 197                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2da71c9db22f9d620fdc07bd42105e852afe05a2                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xf279a2e96dd7d1c85b067084ecc8dd9ace91ca21                         |                                                              |
| operator          | VARCHAR   | 0x0069ca41fd66a0ac174db98c8fedc128c985b5f5                         |                                                              |
| approved          | VARCHAR   | true                                                               |                                                              |

## 4. Table: All\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-02-06 02:06:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5038523                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x61cd8b975c320503eeb7c22b0c49a2d643d547d4f3ec798ebdd94984f321febe | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 138                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa67aac23549f4c672256b59b43ab0bacfcfcd498                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xf3e45c8836311099c6575fbc2a278c7c3cca2a67                         |                                                              |
| spender           | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 63                                                                 |                                                              |

## 5. Table: All\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-30 19:49:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10369105                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x073482b14547f9be46878bb4fa2d41917bc837496aab38cbd87bb306d74f7a3b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0000000000085d4780b73119b644ae5ecd22b376                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000886                         |                                                              |
| amount            | VARCHAR   | 369998860000000000000000                                           |                                                              |

## 6. Table: All\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-08-29 18:12:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6236099                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xde4a91f3c572c4ca6ecdcb3855dd37b26a6ccc879b1241cc7ae4fc68e2bc845f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 56                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x07c62a47ebe0fa853bb83375e488896ce71266df                         | Address of the contract that produced the log                |
| dst               | VARCHAR   | 0x60d0cc2ae15859f69bf74dadb8ae3bd58434976b                         |                                                              |
| wad               | VARCHAR   | 4828544821229576881696                                             |                                                              |

## 7. Table: All\_event\_ForwarderCreated\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2021-10-17 13:27:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 13435694                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xe1b4b9d00e80fe37278d81f81d4ff4ef832a9bbb7782c05cb6208842060adb2c | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 189                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0xffa397285ce46fb78c588a9e993286aac68c37cd                         | Address of the contract that produced the log                |
| newForwarderAddress | VARCHAR   | 0xd7632457c7299289e51aeff828b2224d826faa66                         |                                                              |
| parentAddress       | VARCHAR   | 0x06585bc41f6baaed10e3f647d495f1906f4fb3a0                         |                                                              |

## 8. Table: All\_event\_Mint\_address\_address\_uint256\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-22 17:44:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13856398                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x12d4b16c3f43b1511e4590c55afc6242812cfb77c634007384814c572393f97b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 257                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0x5b6122c109b78c6755486966148c1d70a50a47d7                         |                                                              |
| to                | VARCHAR   | 0x55fe002aeff02f77364de339a1292923a15844b8                         |                                                              |
| amount            | VARCHAR   | 30489100000                                                        |                                                              |

## 9. Table: All\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2017-11-15 11:27:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4556984                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xac169f75930efa2a58554392b0e59f4d958a15553c79d98c2433c80e7e5b8822 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x06147110022b768ba8f99a8f385df11a151a9cc8                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0xe1380cd40fb1a996c766bcedced81cc4efdfc119                         |                                                              |
| amount            | VARCHAR   | 228                                                                |                                                              |

## 10. Table: All\_event\_RemovedOwner\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-01 15:55:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15057512                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb27890bfa9cd191aa0f2ca5d22cbca86ea0ac0e8403a6ccb506981ee14f8e467 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 166                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe5a154e2f4b5e394ebb01631d270ecc88ad7e050                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x02f3d178b7f2bfc6e5786aed1757dbbb2a5dd316                         |                                                              |

## 11. Table: All\_event\_TransferBatch\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-16 01:50:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14593524                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8e527a40a99361aebe9145a8f7d2d4b0dde6a6b5fa23b3bfe0d210103d00cd53 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 58                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0161b706371e0725e96c67cf55b2384540374cf1                         | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0x5aeedbc6b655c13950f32e5e8a0760d15bbe0afb                         |                                                              |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x5aeedbc6b655c13950f32e5e8a0760d15bbe0afb                         |                                                              |
| ids               | VARCHAR   | 2                                                                  |                                                              |
| values            | VARCHAR   | 1                                                                  |                                                              |

## 12. Table: All\_event\_TransferSingle\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-11 07:48:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8719157                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2af18cd8bff0ccd24730c0bab888f5cbb93a91065ea4a83f7d2073e6b8f197e9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 92                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa2a295ae156bcd0023783cc2666ccbb0ca218d9f                         | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0xdfc9b97ab528718f5b1e855dcfa03558f37af496                         |                                                              |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x96945c8be83feb47d8def0e7608c77a611d8e013                         |                                                              |
| id                | VARCHAR   | 1000001                                                            |                                                              |
| value             | VARCHAR   | 1                                                                  |                                                              |

## 13. Table: All\_event\_Upgraded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-18 11:11:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14410051                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x82f6e8673a880ae655a78949c7c80eabbc159800458466055157d77cd2335bd0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 40                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x82be77ce75ef4ffc63007397cd3462e0dfadf18c                         | Address of the contract that produced the log                |
| implementation    | VARCHAR   | 0x03409f442e930646f87d23da1e38052d0dda2ad0                         |                                                              |

## 14. Table: All\_event\_Withdrawal\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-12 15:09:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8727431                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x642dfdeed6a020971bd9fa9050b9b83c8685297e65fe01ba7639795ee3c0c922 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0xd40f3c129b33c536db47f0e419e10cbcab1c8a57                         |                                                              |
| wad               | VARCHAR   | 77803780000000000                                                  |                                                              |

## 15. Table: ERC223\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-19 09:51:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10489236                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8dbe419714487d62348e8616112833bb3a33b13d52bf5bc9493f27519697eeb2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 163                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1c83501478f1320977047008496dacbd60bb15ef                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x277ac8229e951bf36223c2fd17031e862ba29118                         |                                                              |
| to                | VARCHAR   | 0x04f2e1b20c2b6b8e7f28a149a13b8ea38d6cb3f7                         |                                                              |
| value             | VARCHAR   | 1000000000000000000000                                             |                                                              |
| data              | VARCHAR   | 0xc5d2460186f7233c927e7db2dcc703c0e500b653ca82273b7bfad8045d85a470 |                                                              |
