# chainlink

## 1. Table: AccessControlledOffchainAggregator\_event\_AddedAccess\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-16 15:37:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33183412                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8598037e40ff861b067b742519ba3338a089a56fce6d5e29be5ce8c9847e9877 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 22                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x54d81825c7ba6766d8770ec8ae9f786e700f6df2                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xda0f8df6f5db15b346f4b8d1156722027e194e60                         |                                                              |

## 2. Table: AccessControlledOffchainAggregator\_event\_AnswerUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-09 08:01:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 25757331                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1ff25e5d63b177fdf20b23bc71f68b878ce8bc8af2bd577179c65111cccd0cdd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 35                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x62439095489eb5de4572de632248682c09a05ad4                         | Address of the contract that produced the log                |
| current           | VARCHAR   | 100000950                                                          |                                                              |
| roundId           | VARCHAR   | 1582761                                                            |                                                              |
| updatedAt         | VARCHAR   | 1646812905                                                         |                                                              |

## 3. Table: AccessControlledOffchainAggregator\_event\_BillingAccessControllerSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-18 17:02:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 20352503                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x04b5ae6edb29fb3f964ff7aa5e6edfdba6425c7b460d397fff938faed1ca15e4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 135                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa25aa6588c0311b9db11c2887d9acbb6b5e3d1b0                         | Address of the contract that produced the log                |
| old               | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| current           | VARCHAR   | 0x494e19780c3fe5b2a61ee6d6380fea4b408a2c07                         |                                                              |

## 4. Table: AccessControlledOffchainAggregator\_event\_BillingSet\_history

| Column                  | Type      | Example                                                            | Description                                                  |
| ----------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp        | TIMESTAMP | 2022-06-29 13:50:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number           | INTEGER   | 30138515                                                           | The block number where this event was emitted                |
| transaction\_hash       | VARCHAR   | 0x7c4baa94d43bab9856b94692c330b36946375c6f646ba4ef9a0585df835aee4f | Hash of the transactions in which this event was emitted     |
| log\_index              | INTEGER   | 365                                                                | Integer of the log index position in the block of this event |
| contract\_address       | VARCHAR   | 0x7c91d32a126dff213b368d8527e8be13d641f81f                         | Address of the contract that produced the log                |
| maximumGasPrice         | VARCHAR   | 700                                                                |                                                              |
| reasonableGasPrice      | VARCHAR   | 40                                                                 |                                                              |
| microLinkPerEth         | VARCHAR   | 83600                                                              |                                                              |
| linkGweiPerObservation  | VARCHAR   | 98713                                                              |                                                              |
| linkGweiPerTransmission | VARCHAR   | 596760                                                             |                                                              |

## 5. Table: AccessControlledOffchainAggregator\_event\_CheckAccessDisabled\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 6. Table: AccessControlledOffchainAggregator\_event\_CheckAccessEnabled\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 7. Table: AccessControlledOffchainAggregator\_event\_ConfigSet\_history

| Column                    | Type      | Example                                                                                              | Description                                                  |
| ------------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp          | TIMESTAMP | 2022-03-31 01:58:47+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number             | INTEGER   | 26560612                                                                                             | The block number where this event was emitted                |
| transaction\_hash         | VARCHAR   | 0x45f5a03bf87a06a8224a4eb578650dcd8ed4e09a38fbd1cb0ef54ffc756a1661                                   | Hash of the transactions in which this event was emitted     |
| log\_index                | INTEGER   | 94                                                                                                   | Integer of the log index position in the block of this event |
| contract\_address         | VARCHAR   | 0x08f8d217e6f07ae423a2ad2ffb226ffcb577708d                                                           | Address of the contract that produced the log                |
| previousConfigBlockNumber | VARCHAR   | 0                                                                                                    |                                                              |
| configCount               | VARCHAR   | 1                                                                                                    |                                                              |
| signers                   | VARCHAR   | 0x8d0A03aB54126006D6c6880e2525b2Dea9F80a63,0x7E1f2b6525906B8f68139b9E614B5759e4904DeA,0x7A25F136758E |                                                              |
| transmitters              | VARCHAR   | 0xa1ab1c841898Fe94900d00d9312ba954e4F81501,0x550365027554bD20D750f9361e460C7428ffBd75,0x21148F81D302 |                                                              |
| threshold                 | VARCHAR   | 5                                                                                                    |                                                              |
| encodedConfigVersion      | VARCHAR   | 1                                                                                                    |                                                              |
| encoded                   | VARCHAR   | 0x00000000000000000000000000000000000000000000000000000000000000200000000000000000000000000000000000 |                                                              |

## 8. Table: AccessControlledOffchainAggregator\_event\_NewRound\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-02 00:10:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29052526                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa2aa5e3da5a7ae19b29347fe5506721825bd1be1d877c08b03dd43c6a346828c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 118                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3011e9d73e9b01a593da032f41626e6bbe9e408d                         | Address of the contract that produced the log                |
| roundId           | VARCHAR   | 2210833                                                            |                                                              |
| startedBy         | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| startedAt         | VARCHAR   | 1654128640                                                         |                                                              |

## 9. Table: AccessControlledOffchainAggregator\_event\_NewTransmission\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-18 23:13:04+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 41688642                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x59bce5077de7ccd0744bbdfd632394c13b60ce39913a20e86e169eb87ae6ab86                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 35                                                                                                   | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x02acd64082a7ea28feb39d8dc2e44c1600f89976                                                           | Address of the contract that produced the log                |
| aggregatorRoundId | VARCHAR   | 4805497                                                                                              |                                                              |
| answer            | VARCHAR   | 689710000                                                                                            |                                                              |
| transmitter       | VARCHAR   | 0x84a611b71254f5fccb1e5a619ad723cad8a03638                                                           |                                                              |
| observations      | VARCHAR   | 689520084,689661385,689661385,689670000,689700000,689700000,689700000,689710000,689710000,689742800, |                                                              |
| observers         | VARCHAR   | 0x020c060a010e09070d05030b0408000f                                                                   |                                                              |
| rawReportContext  | VARCHAR   | 0x000000000000000000000077c93bce0991d6588c9f8c67df089e8a00044f7603                                   |                                                              |

## 10. Table: AccessControlledOffchainAggregator\_event\_OraclePaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-11 13:38:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 24814522                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc105e2f9c68246fdbdd6418299f082ca2764d7e091ca616f73e304426f654a75 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 182                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x02acd64082a7ea28feb39d8dc2e44c1600f89976                         | Address of the contract that produced the log                |
| transmitter       | VARCHAR   | 0x21148f81d302442c34d39cb65b82f5e7138f9be6                         |                                                              |
| payee             | VARCHAR   | 0xb9e62f6a14ac8babb7f99993bdc3182a1976c22e                         |                                                              |
| amount            | VARCHAR   | 7544773660424000000                                                |                                                              |

## 11. Table: AccessControlledOffchainAggregator\_event\_OwnershipTransferRequested\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-28 20:28:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30110421                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbb1f633508c3366e2c831d33f62829467ef742382d7c372d0978a69af745c291 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 74                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0faf504bee22af6e92d6697af2eafb9941a1712d                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x67a356a1fae1755ec8cd3239d923a4fd485f57d0                         |                                                              |
| to                | VARCHAR   | 0x5a3ca642fded17296adddb53a496ce4f26901596                         |                                                              |

## 12. Table: AccessControlledOffchainAggregator\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-22 21:35:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 20500533                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbdf10fda96b3928ac03679e6d712c412c162c03640c07426a2d60e8d8a26b90e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 79                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa25aa6588c0311b9db11c2887d9acbb6b5e3d1b0                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x4c6da8b6bf7e43a2c1450a7d0e391fa62c99a5b9                         |                                                              |
| to                | VARCHAR   | 0x5a3ca642fded17296adddb53a496ce4f26901596                         |                                                              |

## 13. Table: AccessControlledOffchainAggregator\_event\_PayeeshipTransferRequested\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-22 20:51:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45396291                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xadf04f74242116e95202e848c55e3c9d6eb9042124ede6e4277607e3f587c5e1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x63a39d35751e8d3e80734bcdc755b2145718385d                         | Address of the contract that produced the log                |
| transmitter       | VARCHAR   | 0xe0ed2a6cad84df5191fe337e7dc9685d03ba3ed0                         |                                                              |
| current           | VARCHAR   | 0xd9459cc85e78e0336adb349eabf257dbaf9d5a2b                         |                                                              |
| proposed          | VARCHAR   | 0x552c56469c4ca50d7a35755702b95b9ffb4a4471                         |                                                              |

## 14. Table: AccessControlledOffchainAggregator\_event\_PayeeshipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-08 15:56:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16644608                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xffa53267a254e013d1eb076593aca783b3c250c8f49636df7070c507249455ba | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 17                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb54d6f958c3940db47ccfd65125a2a31d9fcb756                         | Address of the contract that produced the log                |
| transmitter       | VARCHAR   | 0xd0a8cb58efcee1caee48f3c357074862ca8210dc                         |                                                              |
| previous          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| current           | VARCHAR   | 0x3fb4600736d306ee2a89edf0356d4272fb095768                         |                                                              |

## 15. Table: AccessControlledOffchainAggregator\_event\_RemovedAccess\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| user              | VARCHAR   |                                                              |             |

## 16. Table: AccessControlledOffchainAggregator\_event\_RequesterAccessControllerSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-17 03:55:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 18069284                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x23ee0b0c78ad4098020efd4bf8eb59bb22d2edef7987bf9728063e15282f36d9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 34                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x953d8c16fd4f22951c2f497669c6869b86b4e60e                         | Address of the contract that produced the log                |
| old               | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| current           | VARCHAR   | 0x6a9f4359350172ac4b1d4132639fe23f9562d778                         |                                                              |

## 17. Table: AccessControlledOffchainAggregator\_event\_RoundRequested\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-09 20:00:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 21181062                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc09be6f05cf94b39ae60ae09ccfca3179de1f004a12552cc6b2f76bc85b20943 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 24                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc8125b9941fade2e9c86f555464d9d96ccb9e3e3                         | Address of the contract that produced the log                |
| requester         | VARCHAR   | 0xbeaf100f578a60446a71ede45a1ff64972f7b3f3                         |                                                              |
| configDigest      | VARCHAR   | 0xf1408c3633c5d5ae2a5be2ab3cff3b90                                 |                                                              |
| epoch             | VARCHAR   | 57178                                                              |                                                              |
| round             | VARCHAR   | 2                                                                  |                                                              |

## 18. Table: AccessControlledOffchainAggregator\_event\_ValidatorConfigSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousValidator | VARCHAR   |                                                              |             |
| previousGasLimit  | VARCHAR   |                                                              |             |
| currentValidator  | VARCHAR   |                                                              |             |
| currentGasLimit   | VARCHAR   |                                                              |             |

## 19. Table: EACAggregatorProxy\_call\_confirmAggregator\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-07-12 14:16:12+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16781919                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xa913c17ed75f1b2ae2ed40546a6e407bc438ae5adeb83e0cb47bd5d64227ac66 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 56                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0,0,1                                                            | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x0a6513e40db6eb1b165753ad52e80663aea50545                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_aggregator       | VARCHAR   | 0x3011e9d73e9b01a593da032f41626e6bbe9e408d                         |                                                                                                                        |
