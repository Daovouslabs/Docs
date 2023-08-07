# chainlink

## 1. Table: AccessControlledOffchainAggregator\_event\_AddedAccess\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-14 15:51:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 22172405                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3614a16c40f8b676455f873bc2a197a5252f0d81705ba47f2d554404ab770c73 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 16                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd690b2cf0d2bcbce51c4ce2dc46e02c508465c5c                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x9a177bb9f5b6083e962f9e62bd21d4b5660aeb03                         |                                                              |

## 2. Table: AccessControlledOffchainAggregator\_event\_AnswerUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-16 17:36:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 24841984                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb2b416f79842babb9b9e15c893767ab7ab98e739b056bce05d98b3929c23620a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 183                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8f8289e5ca9a4c867ec7a257b0e9dd1132093e23                         | Address of the contract that produced the log                |
| current           | VARCHAR   | 457136000                                                          |                                                              |
| roundId           | VARCHAR   | 30804                                                              |                                                              |
| updatedAt         | VARCHAR   | 1673890580                                                         |                                                              |

## 3. Table: AccessControlledOffchainAggregator\_event\_BillingAccessControllerSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-17 03:16:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10096809                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x66aa6bf21637db104b4e961571c31313623fdf59223dacddfc276f71ff371b12 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 31                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf1eed6f4a9006b3cf8f547b36d055b97ef50de8b                         | Address of the contract that produced the log                |
| old               | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| current           | VARCHAR   | 0x5324dd615144dfc18a290d50172789699aec34ee                         |                                                              |

## 4. Table: AccessControlledOffchainAggregator\_event\_BillingSet\_history

| Column                  | Type      | Example                                                            | Description                                                  |
| ----------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp        | TIMESTAMP | 2022-07-05 16:26:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number           | INTEGER   | 19289187                                                           | The block number where this event was emitted                |
| transaction\_hash       | VARCHAR   | 0x0df40c78f63c73d3d21a37e6437437ad482ad992db1b46ec973d57ab365de33e | Hash of the transactions in which this event was emitted     |
| log\_index              | INTEGER   | 1249                                                               | Integer of the log index position in the block of this event |
| contract\_address       | VARCHAR   | 0x38d0f1dfe37aac059ad06b2d30ef60aa537f0b05                         | Address of the contract that produced the log                |
| maximumGasPrice         | VARCHAR   | 500                                                                |                                                              |
| reasonableGasPrice      | VARCHAR   | 17                                                                 |                                                              |
| microLinkPerEth         | VARCHAR   | 36600000                                                           |                                                              |
| linkGweiPerObservation  | VARCHAR   | 257569                                                             |                                                              |
| linkGweiPerTransmission | VARCHAR   | 1547641                                                            |                                                              |

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
| block\_timestamp          | TIMESTAMP | 2021-08-17 03:17:37+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number             | INTEGER   | 10096830                                                                                             | The block number where this event was emitted                |
| transaction\_hash         | VARCHAR   | 0xf4d427f97775b1fe728ac5f17f80ac9ebe3b3b4800ba5928bd32a45f38e41229                                   | Hash of the transactions in which this event was emitted     |
| log\_index                | INTEGER   | 35                                                                                                   | Integer of the log index position in the block of this event |
| contract\_address         | VARCHAR   | 0xf1eed6f4a9006b3cf8f547b36d055b97ef50de8b                                                           | Address of the contract that produced the log                |
| previousConfigBlockNumber | VARCHAR   | 0                                                                                                    |                                                              |
| configCount               | VARCHAR   | 1                                                                                                    |                                                              |
| signers                   | VARCHAR   | 0xCaF0534bA1fdc5ceEc2852503E9c9a93478e2DE7,0xf15aCfAb7D411f40D4cda56380ec3A7Eb158a56a,0xbdEC52b0AF1e |                                                              |
| transmitters              | VARCHAR   | 0xa53bdb1522a58dEe57B89e0579C13B15825B8D77,0x3032cE567c21329fC95B150022d50753ecCB4F1d,0xA1e96Ecaab9d |                                                              |
| threshold                 | VARCHAR   | 5                                                                                                    |                                                              |
| encodedConfigVersion      | VARCHAR   | 1                                                                                                    |                                                              |
| encoded                   | VARCHAR   | 0x00000000000000000000000000000000000000000000000000000000000000200000000000000000000000000000000000 |                                                              |

## 8. Table: AccessControlledOffchainAggregator\_event\_NewRound\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-11 22:25:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29881295                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa2f8f24f7445852bfdda85fd79f2dd0a0d460e64f0481525d1504291db3ec486 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 264                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00865e449e123ba4c3a46d614330da56b739f723                         | Address of the contract that produced the log                |
| roundId           | VARCHAR   | 12918                                                              |                                                              |
| startedBy         | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| startedAt         | VARCHAR   | 1689114325                                                         |                                                              |

## 9. Table: AccessControlledOffchainAggregator\_event\_NewTransmission\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-13 15:36:15+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14333288                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf4e8f6bc73d8f66414244bf0256594145fd4200a2e5eb24fab5334b917dac985                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 563                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x066d0cd30f981a96e2fe4f958c5e7f4999be0adf                                                           | Address of the contract that produced the log                |
| aggregatorRoundId | VARCHAR   | 15470                                                                                                |                                                              |
| answer            | VARCHAR   | 1428543                                                                                              |                                                              |
| transmitter       | VARCHAR   | 0x17721d492b7efdcf7365e541edefdde552a1360f                                                           |                                                              |
| observations      | VARCHAR   | 1422527,1422527,1423993,1423993,1423993,1425863,1428372,1428543,1428543,1430437,1431428,1431895,1435 |                                                              |
| observers         | VARCHAR   | 0x09070c050a0304010f00080d0b02060e                                                                   |                                                              |
| rawReportContext  | VARCHAR   | 0x0000000000000000000000521a50e17adf50640dd6472f7ec580bd0001a08c05                                   |                                                              |

## 10. Table: AccessControlledOffchainAggregator\_event\_OraclePaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-20 02:52:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 18841787                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x91d7cda0dc889fd566c02a39bb03ec24a8ef07bb9fc8707620c04d798aac4ae6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 292                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x178ba789e24a1d51e9ea3cb1db3b52917963d71d                         | Address of the contract that produced the log                |
| transmitter       | VARCHAR   | 0xd46f50ba5bd6e4a2ab3fad8207fcd94c7ba0dea7                         |                                                              |
| payee             | VARCHAR   | 0x1b17eb8fae3c28cb2463235f9d407b527ba4e6dd                         |                                                              |
| amount            | VARCHAR   | 24577665386000000000                                               |                                                              |

## 11. Table: AccessControlledOffchainAggregator\_event\_OwnershipTransferRequested\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-17 14:29:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17882384                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x65a5c629c822fe3b6ecd0cf25116334e2e7e6719f049ffac7b997e3ffa38408f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 71                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x982675d04d9c9fa074c702f5aca3d84d04fe31d5                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x7e1978b6efb88a9fab0bbfbdfb150b440ffcbcce                         |                                                              |
| to                | VARCHAR   | 0xcb6754d5e11c4b70601d0f2068ea62089325979b                         |                                                              |

## 12. Table: AccessControlledOffchainAggregator\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-26 18:36:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10372977                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6e80ee7fbacaed2e74ed225df1348f56e8695367f4716a80e4aebf3d32f4fa66 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 509                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6c9c9757f0478bc38bf73abda27ac42864de0645                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xfb1660905af3f93a684914af1348234d3a19b01c                         |                                                              |
| to                | VARCHAR   | 0xcb6754d5e11c4b70601d0f2068ea62089325979b                         |                                                              |

## 13. Table: AccessControlledOffchainAggregator\_event\_PayeeshipTransferRequested\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-22 20:27:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30194922                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfba668d8fe85b5b7f100bb972ca2fe02e2993b04342dd1c33bd65fda99677246 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe978daa50d3a8574f139c1e3fe5d511ddb323bc5                         | Address of the contract that produced the log                |
| transmitter       | VARCHAR   | 0x39d36fd647a933fe51670c1eb6b0e6b8b4a69f07                         |                                                              |
| current           | VARCHAR   | 0xd9459cc85e78e0336adb349eabf257dbaf9d5a2b                         |                                                              |
| proposed          | VARCHAR   | 0x552c56469c4ca50d7a35755702b95b9ffb4a4471                         |                                                              |

## 14. Table: AccessControlledOffchainAggregator\_event\_PayeeshipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-27 17:04:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 22543809                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb464b55cbb4d4839c623b6f7cdd5d8f44ec01c9bc58368b220388d3571876874 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x322aa7da39250d891c6f01ff07af1ea164d99280                         | Address of the contract that produced the log                |
| transmitter       | VARCHAR   | 0x19588efd97dd4a5d412352047334ed6fdf1b8eb9                         |                                                              |
| previous          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| current           | VARCHAR   | 0xb98da55e3e72babf18c4f421ea5b653519e79f2b                         |                                                              |

## 15. Table: AccessControlledOffchainAggregator\_event\_RemovedAccess\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-03 13:32:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12333578                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x55d92ef36d2b783fc58ec9e9cba38d7c9a157480cd9e3ca92d3141ecc80ead18 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 744                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe0a34b8fc5e80c877fd568bd22b49e1bca977b6f                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xd54174811aef2ade4562118bb6b3654707dc8cb3                         |                                                              |

## 16. Table: AccessControlledOffchainAggregator\_event\_RequesterAccessControllerSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-02 09:48:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12301577                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaf5710fd05e3658096220bdc38d5c401cbfce7280b6cb991d9198c579779b09e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 68                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe0a34b8fc5e80c877fd568bd22b49e1bca977b6f                         | Address of the contract that produced the log                |
| old               | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| current           | VARCHAR   | 0xa347e4d65be5e355efd3afe97f2facded7061ac6                         |                                                              |

## 17. Table: AccessControlledOffchainAggregator\_event\_RoundRequested\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-28 02:00:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8678125                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x59b2cb64bc710ff10d6282850ce951b1c1777e98d022a1545d8ce9e373d2c35f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 402                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x178ba789e24a1d51e9ea3cb1db3b52917963d71d                         | Address of the contract that produced the log                |
| requester         | VARCHAR   | 0xd3f7b014aa29b776f9bfc29ebe8cddaefa59a05e                         |                                                              |
| configDigest      | VARCHAR   | 0x95e1a7e276bea0aa4f3d942647044f9a                                 |                                                              |
| epoch             | VARCHAR   | 23554                                                              |                                                              |
| round             | VARCHAR   | 1                                                                  |                                                              |

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
| block\_timestamp   | TIMESTAMP | 2021-05-20 17:23:18+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 7578801                                                            | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x251bdd55d6c16d4a73d0a97d86af9e7509b34520f9e7404e182bdda9d393db0d | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 214                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0,0,31                                                           | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3ab0a0d137d4f946fbb19eecc6e92e64660231c8                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_aggregator       | VARCHAR   | 0xd0a597ffc7075e1449ece7feaa9880488ddb34fd                         |                                                                                                                        |
