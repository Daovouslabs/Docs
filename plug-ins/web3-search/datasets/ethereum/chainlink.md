# chainlink

## 1. Table: AccessControlledOffchainAggregator\_event\_AddedAccess\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-29 15:58:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14482033                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaf30fd504400c82cca91dfb7f3f4fc763b636044f34b9fe577e00c48b406e60e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 29                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1c026c25271c1bfba95b65c848f734a23ea62d4e                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x47fb2585d2c56fe188d0e6ec628a38b74fceeedf                         |                                                              |

## 2. Table: AccessControlledOffchainAggregator\_event\_AnswerUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-02 04:38:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16538789                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd805a03583dca5aee654e0d6be657244938a9665a030773c2bfb857455c99f10 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 253                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4b35f7854e1fd8291f4ec714ac3ebb1dea450585                         | Address of the contract that produced the log                |
| current           | VARCHAR   | 123700000                                                          |                                                              |
| roundId           | VARCHAR   | 15398                                                              |                                                              |
| updatedAt         | VARCHAR   | 1675312727                                                         |                                                              |

## 3. Table: AccessControlledOffchainAggregator\_event\_BillingAccessControllerSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-24 21:43:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11922311                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd364f7b317d3a71037cbc4e5d7954dd73c6314772c89bcf68df1fc57fd5e8c0a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 9                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x02f878a94a1ae1b15705acd65b5519a46fe3517e                         | Address of the contract that produced the log                |
| old               | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| current           | VARCHAR   | 0x9db83cef9f68b63989e4e82d65d549e7ff2acda9                         |                                                              |

## 4. Table: AccessControlledOffchainAggregator\_event\_BillingSet\_history

| Column                  | Type      | Example                                                            | Description                                                  |
| ----------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp        | TIMESTAMP | 2023-03-13 20:20:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number           | INTEGER   | 16821403                                                           | The block number where this event was emitted                |
| transaction\_hash       | VARCHAR   | 0x154e0e07e577453e36fd041278d1d797db37d250bdad95b6a9640858490eade6 | Hash of the transactions in which this event was emitted     |
| log\_index              | INTEGER   | 542                                                                | Integer of the log index position in the block of this event |
| contract\_address       | VARCHAR   | 0xdf0da6b3d19e4427852f2112d0a963d8a158e9c7                         | Address of the contract that produced the log                |
| maximumGasPrice         | VARCHAR   | 3000                                                               |                                                              |
| reasonableGasPrice      | VARCHAR   | 60                                                                 |                                                              |
| microLinkPerEth         | VARCHAR   | 245831579                                                          |                                                              |
| linkGweiPerObservation  | VARCHAR   | 90485129                                                           |                                                              |
| linkGweiPerTransmission | VARCHAR   | 542907913                                                          |                                                              |

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
| block\_timestamp          | TIMESTAMP | 2021-10-12 20:05:13+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number             | INTEGER   | 13405699                                                                                             | The block number where this event was emitted                |
| transaction\_hash         | VARCHAR   | 0x9651482ed0d7664ccfc9a96da18017ae90de555f7b115ebd9783b5ef77f38d05                                   | Hash of the transactions in which this event was emitted     |
| log\_index                | INTEGER   | 170                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address         | VARCHAR   | 0x2abfc56aaa39be7a946ec39aac5d452e30614df1                                                           | Address of the contract that produced the log                |
| previousConfigBlockNumber | VARCHAR   | 0                                                                                                    |                                                              |
| configCount               | VARCHAR   | 1                                                                                                    |                                                              |
| signers                   | VARCHAR   | 0x503bd542a29F089319855cd9F6F6F937C7Be87c7,0xCdEf689d3098A796F840A26f383CE19F4f023B5B,0x5007b477F939 |                                                              |
| transmitters              | VARCHAR   | 0xEdBED9F5dEA03dD0ec484577C41502af68B7c46a,0x686beC83b59F8b23A6129f03550A3Aad245a543C,0xDbfea8D58221 |                                                              |
| threshold                 | VARCHAR   | 5                                                                                                    |                                                              |
| encodedConfigVersion      | VARCHAR   | 1                                                                                                    |                                                              |
| encoded                   | VARCHAR   | 0x00000000000000000000000000000000000000000000000000000000000000200000000000000000000000000000000000 |                                                              |

## 8. Table: AccessControlledOffchainAggregator\_event\_NewRound\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-23 16:19:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17323071                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5fd2aad43649728ea68737622cbb1d5ad6e81ae69c932fb3e87c3c3039c285b9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 80                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd74ff3f1b565597e59d44320f53a5c5c8ba85f7b                         | Address of the contract that produced the log                |
| roundId           | VARCHAR   | 200                                                                |                                                              |
| startedBy         | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| startedAt         | VARCHAR   | 1684858763                                                         |                                                              |

## 9. Table: AccessControlledOffchainAggregator\_event\_NewTransmission\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-07 02:28:53+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15487718                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc96a642dd2fb8864bbe77558991c6617b0fa141579914b9306257bac4fd85168                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 161                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x56f98706c14df5c290b02cec491bb4c20834bb51                                                           | Address of the contract that produced the log                |
| aggregatorRoundId | VARCHAR   | 1957                                                                                                 |                                                              |
| answer            | VARCHAR   | 666220000000000                                                                                      |                                                              |
| transmitter       | VARCHAR   | 0x0312ea121df0a323ff535b753172736cc9d53d13                                                           |                                                              |
| observations      | VARCHAR   | 663426360074055,664852217720573,665280212258562,665336629933015,665336629933015,665336629933015,6661 |                                                              |
| observers         | VARCHAR   | 0x040506020d080e010b0c0a0f07090300                                                                   |                                                              |
| rawReportContext  | VARCHAR   | 0x0000000000000000000000611c54b32edbea22c8cda83e2d2401dc00039bc901                                   |                                                              |

## 10. Table: AccessControlledOffchainAggregator\_event\_OraclePaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-16 18:33:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13238415                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x31e7f3cc93c58476b1bd65a95faf3fbeb928f6a2a6ce01e8bcce69d277b4a147 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 95                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0deaf87519d434dcf74551b2e907af18d2304946                         | Address of the contract that produced the log                |
| transmitter       | VARCHAR   | 0xc4b732fd121f2f3783a9ac2a6c62fd535fd13fda                         |                                                              |
| payee             | VARCHAR   | 0x183a96629ff566e7aa8afa38980cd037eb40a59a                         |                                                              |
| amount            | VARCHAR   | 4927696437000000000                                                |                                                              |

## 11. Table: AccessControlledOffchainAggregator\_event\_OwnershipTransferRequested\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-07 20:21:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15920501                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0de3ff8bb689b9359fb28ba005dffa416e10e5729156a9f137dd9fe7d8d5ee8d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 69                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x646d61986f45deec2477a3a355edba60b4c16d6b                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xe92f783fcce110b902ae6eb86889101449a3d138                         |                                                              |
| to                | VARCHAR   | 0x21f73d42eb58ba49ddb685dc29d3bf5c0f0373ca                         |                                                              |

## 12. Table: AccessControlledOffchainAggregator\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-09 21:14:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14934705                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc8fcd0d2e6bb60f514ed1aa979c1688c9ac44cd23cc9f167b0da4e03cd0ca2e2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 310                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf8efb55fbf6e7f48637561182dac1ef09f38d767                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xe92f783fcce110b902ae6eb86889101449a3d138                         |                                                              |
| to                | VARCHAR   | 0x21f73d42eb58ba49ddb685dc29d3bf5c0f0373ca                         |                                                              |

## 13. Table: AccessControlledOffchainAggregator\_event\_PayeeshipTransferRequested\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-28 06:42:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17789837                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9cff43e8f8c4555aa08990d0ef1cd423ec2d07b0d4585cb0ba6d45d80d90405c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 257                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x27b97a63091d185ce056e1747624b9b92baad056                         | Address of the contract that produced the log                |
| transmitter       | VARCHAR   | 0xdde59ceec7a2cc8b2bd78199877ba22018966813                         |                                                              |
| current           | VARCHAR   | 0x9d69b0fcbcf9a7e513e947cd7ce2019904e2e764                         |                                                              |
| proposed          | VARCHAR   | 0x41edd305eabfd3497c98341f8d0849f3c520b896                         |                                                              |

## 14. Table: AccessControlledOffchainAggregator\_event\_PayeeshipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-29 21:44:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12136617                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2720785d3ca8cadc0b541910042627940f682fe8a703a48f2448f60608b96a6b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 206                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x61b5793cd5f454d2b25ba1acb5c1aa1728f67e1c                         | Address of the contract that produced the log                |
| transmitter       | VARCHAR   | 0x5565b5362ff9f468ba2f144f38b87187c9a010a8                         |                                                              |
| previous          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| current           | VARCHAR   | 0xfdc770353dc0bfce80a17ab8a6a2e7d80590f1ba                         |                                                              |

## 15. Table: AccessControlledOffchainAggregator\_event\_RemovedAccess\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-10 18:34:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13779048                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1814b1c195b545f1129481e0642471f055e252c6479b36b7bd86d219e89c6a3c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 214                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdeaa4288c85e7e0be40bce49e76d4e321d20fc36                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x536ee6348b3790ec74c21fcbe3d990066e9b8ec7                         |                                                              |

## 16. Table: AccessControlledOffchainAggregator\_event\_RequesterAccessControllerSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-31 15:25:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12542898                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9d55231472b74bac707142b1de05fd82d2415e72deb242e841f1776cfde9c426 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 133                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc1d757bee6bcdd45093979bfe60d341b833b2db0                         | Address of the contract that produced the log                |
| old               | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| current           | VARCHAR   | 0x641b698ad1c6e503470520b0eecb472c0589dfe6                         |                                                              |

## 17. Table: AccessControlledOffchainAggregator\_event\_RoundRequested\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-08 08:00:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17002363                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7d97f373163fe1bedf3889c681949f723147965399bf37793c955ee896113623 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 226                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdfd03bfc3465107ce570a0397b247f546a42d0fa                         | Address of the contract that produced the log                |
| requester         | VARCHAR   | 0xd8aa8f3be2fb0c790d3579dcf68a04701c1e33db                         |                                                              |
| configDigest      | VARCHAR   | 0xd143d03737900137dbd2c20d614d4a58                                 |                                                              |
| epoch             | VARCHAR   | 4547                                                               |                                                              |
| round             | VARCHAR   | 1                                                                  |                                                              |

## 18. Table: AccessControlledOffchainAggregator\_event\_ValidatorConfigSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-28 02:16:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16723634                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3e524219d038851fd6e1d7cfec6a659758a5da9d4511bf2a40f9a6daffbd7c86 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 99                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4b35f7854e1fd8291f4ec714ac3ebb1dea450585                         | Address of the contract that produced the log                |
| previousValidator | VARCHAR   | 0x44750a79ae69d5e9bc1651e099dffe1fb8611aba                         |                                                              |
| previousGasLimit  | VARCHAR   | 450000                                                             |                                                              |
| currentValidator  | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| currentGasLimit   | VARCHAR   | 450000                                                             |                                                              |

## 19. Table: AccessControlledOffchainAggregator\_event\_ValidatorUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previous          | VARCHAR   |                                                              |             |
| current           | VARCHAR   |                                                              |             |

## 20. Table: Aggregator\_AUD\_USD\_event\_AnswerUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-07 16:23:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15697383                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xca5d2c41378ac2452197853e9a18b789715b5b711087b57a2cb73aad411bb443 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 257                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7f7b323291c052de18926396176d384c4a8e19e2                         | Address of the contract that produced the log                |
| current           | VARCHAR   | 63881433                                                           |                                                              |
| roundId           | VARCHAR   | 4748                                                               |                                                              |
| timestamp         | VARCHAR   | 1665159827                                                         |                                                              |

## 21. Table: Aggregator\_AUD\_USD\_event\_ChainlinkFulfilled\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| id                | VARCHAR   |                                                              |             |

## 22. Table: Aggregator\_AUD\_USD\_event\_ChainlinkRequested\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| id                | VARCHAR   |                                                              |             |

## 23. Table: Aggregator\_AUD\_USD\_event\_NewRound\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| roundId           | VARCHAR   |                                                              |             |
| startedBy         | VARCHAR   |                                                              |             |

## 24. Table: Aggregator\_AUD\_USD\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-02 18:50:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11960559                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbb98ae21a2039dd8f924e7cba9298a73a6dd4c34540b605491f93e9e54f9e88d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 92                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7f7b323291c052de18926396176d384c4a8e19e2                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x8183f851eb1479b7191e97545b936446fbe08eba                         |                                                              |
| newOwner          | VARCHAR   | 0x21f73d42eb58ba49ddb685dc29d3bf5c0f0373ca                         |                                                              |

## 25. Table: Aggregator\_AUD\_USD\_event\_ResponseReceived\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| response          | VARCHAR   |                                                              |             |
| answerId          | VARCHAR   |                                                              |             |
| sender            | VARCHAR   |                                                              |             |

## 26. Table: Aggregator\_BTC\_USD\_event\_AnswerUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-20 19:04:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15576654                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd09f5c41d283dc76bc2319c0159bac66dcf3a64a21cbbfe6b84254a65d66964b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 264                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xae74faa92cb67a95ebcab07358bc222e33a34da7                         | Address of the contract that produced the log                |
| current           | VARCHAR   | 1905191176887                                                      |                                                              |
| roundId           | VARCHAR   | 26297                                                              |                                                              |
| timestamp         | VARCHAR   | 1663700663                                                         |                                                              |

## 27. Table: Aggregator\_BTC\_USD\_event\_ChainlinkFulfilled\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| id                | VARCHAR   |                                                              |             |

## 28. Table: Aggregator\_BTC\_USD\_event\_ChainlinkRequested\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| id                | VARCHAR   |                                                              |             |

## 29. Table: Aggregator\_BTC\_USD\_event\_NewRound\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| roundId           | VARCHAR   |                                                              |             |
| startedBy         | VARCHAR   |                                                              |             |

## 30. Table: Aggregator\_BTC\_USD\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-14 21:40:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12435030                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf563d3d76dddab1c1fc94222214eb6e0290e4e47e250e4822cff5d78b7705dd1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 124                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xae74faa92cb67a95ebcab07358bc222e33a34da7                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x536ee6348b3790ec74c21fcbe3d990066e9b8ec7                         |                                                              |
| newOwner          | VARCHAR   | 0x21f73d42eb58ba49ddb685dc29d3bf5c0f0373ca                         |                                                              |

## 31. Table: Aggregator\_BTC\_USD\_event\_ResponseReceived\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| response          | VARCHAR   |                                                              |             |
| answerId          | VARCHAR   |                                                              |             |
| sender            | VARCHAR   |                                                              |             |

## 32. Table: Aggregator\_CHF\_USD\_event\_AnswerUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-04 12:11:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17841539                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3e5e4dbdfa2e2a3c1346ad528a3692b48af5f564cfea01e49e85dcffd842f2ab | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 61                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7c8719f3683585a242a67c73f6f3c98362004da4                         | Address of the contract that produced the log                |
| current           | VARCHAR   | 114049790                                                          |                                                              |
| roundId           | VARCHAR   | 5973                                                               |                                                              |
| timestamp         | VARCHAR   | 1691151119                                                         |                                                              |

## 33. Table: Aggregator\_CHF\_USD\_event\_ChainlinkFulfilled\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| id                | VARCHAR   |                                                              |             |

## 34. Table: Aggregator\_CHF\_USD\_event\_ChainlinkRequested\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| id                | VARCHAR   |                                                              |             |

## 35. Table: Aggregator\_CHF\_USD\_event\_NewRound\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| roundId           | VARCHAR   |                                                              |             |
| startedBy         | VARCHAR   |                                                              |             |

## 36. Table: Aggregator\_CHF\_USD\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-02 18:50:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11960559                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbb98ae21a2039dd8f924e7cba9298a73a6dd4c34540b605491f93e9e54f9e88d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 88                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7c8719f3683585a242a67c73f6f3c98362004da4                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x8183f851eb1479b7191e97545b936446fbe08eba                         |                                                              |
| newOwner          | VARCHAR   | 0x21f73d42eb58ba49ddb685dc29d3bf5c0f0373ca                         |                                                              |

## 37. Table: Aggregator\_CHF\_USD\_event\_ResponseReceived\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| response          | VARCHAR   |                                                              |             |
| answerId          | VARCHAR   |                                                              |             |
| sender            | VARCHAR   |                                                              |             |

## 38. Table: Aggregator\_ETH\_USD\_event\_AnswerUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-14 22:55:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14586349                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf5619daa4ac86a0ccc79793a5c4d873c83c4ec9736b93ac8704e6d8893f5f197 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x37bc7498f4ff12c19678ee8fe19d713b87f6a9e6                         | Address of the contract that produced the log                |
| current           | VARCHAR   | 301650000000                                                       |                                                              |
| roundId           | VARCHAR   | 22444                                                              |                                                              |
| updatedAt         | VARCHAR   | 1649976929                                                         |                                                              |

## 39. Table: Aggregator\_ETH\_USD\_event\_ChainlinkFulfilled\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| id                | VARCHAR   |                                                              |             |

## 40. Table: Aggregator\_ETH\_USD\_event\_ChainlinkRequested\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| id                | VARCHAR   |                                                              |             |

## 41. Table: Aggregator\_ETH\_USD\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-14 21:40:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12435030                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf563d3d76dddab1c1fc94222214eb6e0290e4e47e250e4822cff5d78b7705dd1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 122                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x37bc7498f4ff12c19678ee8fe19d713b87f6a9e6                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x536ee6348b3790ec74c21fcbe3d990066e9b8ec7                         |                                                              |
| newOwner          | VARCHAR   | 0x21f73d42eb58ba49ddb685dc29d3bf5c0f0373ca                         |                                                              |

## 42. Table: Aggregator\_ETH\_USD\_event\_ResponseReceived\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| response          | VARCHAR   |                                                              |             |
| answerId          | VARCHAR   |                                                              |             |
| sender            | VARCHAR   |                                                              |             |

## 43. Table: Aggregator\_EUR\_USD\_event\_AnswerUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-11 16:02:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14366460                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8bd425a8938da0b5a7d7ab556f3b131d132a3012d27bf08198350adcefe6ec2e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x02f878a94a1ae1b15705acd65b5519a46fe3517e                         | Address of the contract that produced the log                |
| current           | VARCHAR   | 109675600                                                          |                                                              |
| roundId           | VARCHAR   | 1221                                                               |                                                              |
| timestamp         | VARCHAR   | 1647014571                                                         |                                                              |

## 44. Table: Aggregator\_EUR\_USD\_event\_ChainlinkFulfilled\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| id                | VARCHAR   |                                                              |             |

## 45. Table: Aggregator\_EUR\_USD\_event\_ChainlinkRequested\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| id                | VARCHAR   |                                                              |             |

## 46. Table: Aggregator\_EUR\_USD\_event\_NewRound\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| roundId           | VARCHAR   |                                                              |             |
| startedBy         | VARCHAR   |                                                              |             |

## 47. Table: Aggregator\_EUR\_USD\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-02 18:50:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11960559                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbb98ae21a2039dd8f924e7cba9298a73a6dd4c34540b605491f93e9e54f9e88d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 89                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x02f878a94a1ae1b15705acd65b5519a46fe3517e                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x8183f851eb1479b7191e97545b936446fbe08eba                         |                                                              |
| newOwner          | VARCHAR   | 0x21f73d42eb58ba49ddb685dc29d3bf5c0f0373ca                         |                                                              |

## 48. Table: Aggregator\_EUR\_USD\_event\_ResponseReceived\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| response          | VARCHAR   |                                                              |             |
| answerId          | VARCHAR   |                                                              |             |
| sender            | VARCHAR   |                                                              |             |

## 49. Table: Aggregator\_GBP\_USD\_event\_AnswerUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-13 18:16:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15334963                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xedc8939de6aca917e508592fefc207f08e1f8543a6e464197a0d213cd1b3c016 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 312                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x568b8fd03992f56bf240958d22f5a6fcf7bd850b                         | Address of the contract that produced the log                |
| current           | VARCHAR   | 121389750                                                          |                                                              |
| roundId           | VARCHAR   | 2431                                                               |                                                              |
| timestamp         | VARCHAR   | 1660414600                                                         |                                                              |

## 50. Table: Aggregator\_GBP\_USD\_event\_ChainlinkFulfilled\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| id                | VARCHAR   |                                                              |             |

## 51. Table: Aggregator\_GBP\_USD\_event\_ChainlinkRequested\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| id                | VARCHAR   |                                                              |             |

## 52. Table: Aggregator\_GBP\_USD\_event\_NewRound\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| roundId           | VARCHAR   |                                                              |             |
| startedBy         | VARCHAR   |                                                              |             |

## 53. Table: Aggregator\_GBP\_USD\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-02 18:50:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11960559                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbb98ae21a2039dd8f924e7cba9298a73a6dd4c34540b605491f93e9e54f9e88d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 91                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x568b8fd03992f56bf240958d22f5a6fcf7bd850b                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x8183f851eb1479b7191e97545b936446fbe08eba                         |                                                              |
| newOwner          | VARCHAR   | 0x21f73d42eb58ba49ddb685dc29d3bf5c0f0373ca                         |                                                              |

## 54. Table: Aggregator\_GBP\_USD\_event\_ResponseReceived\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| response          | VARCHAR   |                                                              |             |
| answerId          | VARCHAR   |                                                              |             |
| sender            | VARCHAR   |                                                              |             |

## 55. Table: Aggregator\_JPY\_USD\_event\_AnswerUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-03 15:47:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17835459                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x815f715cac3bcc5bd5e4ccc9f46406743ab228df64ab3f0fb27a653d58f0848a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 99                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x01a1f73b1f4726eb6eb189ffa5cbb91af8e14025                         | Address of the contract that produced the log                |
| current           | VARCHAR   | 702414                                                             |                                                              |
| roundId           | VARCHAR   | 6672                                                               |                                                              |
| timestamp         | VARCHAR   | 1691077667                                                         |                                                              |

## 56. Table: Aggregator\_JPY\_USD\_event\_ChainlinkFulfilled\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| id                | VARCHAR   |                                                              |             |

## 57. Table: Aggregator\_JPY\_USD\_event\_ChainlinkRequested\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| id                | VARCHAR   |                                                              |             |

## 58. Table: Aggregator\_JPY\_USD\_event\_NewRound\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| roundId           | VARCHAR   |                                                              |             |
| startedBy         | VARCHAR   |                                                              |             |

## 59. Table: Aggregator\_JPY\_USD\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-02 18:50:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11960559                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbb98ae21a2039dd8f924e7cba9298a73a6dd4c34540b605491f93e9e54f9e88d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 90                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x01a1f73b1f4726eb6eb189ffa5cbb91af8e14025                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x8183f851eb1479b7191e97545b936446fbe08eba                         |                                                              |
| newOwner          | VARCHAR   | 0x21f73d42eb58ba49ddb685dc29d3bf5c0f0373ca                         |                                                              |

## 60. Table: Aggregator\_JPY\_USD\_event\_ResponseReceived\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| response          | VARCHAR   |                                                              |             |
| answerId          | VARCHAR   |                                                              |             |
| sender            | VARCHAR   |                                                              |             |

## 61. Table: Aggregator\_XAG\_USD\_event\_AnswerUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-26 17:45:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12511376                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0ab02615695b003dd2f297e11078aff0ca4192dff385d2b07f06ce08b1ba7638 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 156                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdeb43523e2857b7ec29d078c77b73709d958c62f                         | Address of the contract that produced the log                |
| current           | VARCHAR   | 2768050000                                                         |                                                              |
| roundId           | VARCHAR   | 1452                                                               |                                                              |
| timestamp         | VARCHAR   | 1622051153                                                         |                                                              |

## 62. Table: Aggregator\_XAG\_USD\_event\_ChainlinkFulfilled\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| id                | VARCHAR   |                                                              |             |

## 63. Table: Aggregator\_XAG\_USD\_event\_ChainlinkRequested\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| id                | VARCHAR   |                                                              |             |

## 64. Table: Aggregator\_XAG\_USD\_event\_NewRound\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| roundId           | VARCHAR   |                                                              |             |
| startedBy         | VARCHAR   |                                                              |             |

## 65. Table: Aggregator\_XAG\_USD\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-02 18:50:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11960559                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbb98ae21a2039dd8f924e7cba9298a73a6dd4c34540b605491f93e9e54f9e88d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 93                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdeb43523e2857b7ec29d078c77b73709d958c62f                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x8183f851eb1479b7191e97545b936446fbe08eba                         |                                                              |
| newOwner          | VARCHAR   | 0x21f73d42eb58ba49ddb685dc29d3bf5c0f0373ca                         |                                                              |

## 66. Table: Aggregator\_XAG\_USD\_event\_ResponseReceived\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| response          | VARCHAR   |                                                              |             |
| answerId          | VARCHAR   |                                                              |             |
| sender            | VARCHAR   |                                                              |             |

## 67. Table: Aggregator\_XAU\_USD\_event\_AnswerUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-21 08:22:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17740298                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x80758ef3196acddb67a4a6e31af6574f971b39b56930bcce238dc1ccf18e2c6e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 248                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xea5f70faa03f5c30b96029635c8d431d1a3cd1b8                         | Address of the contract that produced the log                |
| current           | VARCHAR   | 196240300000                                                       |                                                              |
| roundId           | VARCHAR   | 4231                                                               |                                                              |
| timestamp         | VARCHAR   | 1689927767                                                         |                                                              |

## 68. Table: Aggregator\_XAU\_USD\_event\_ChainlinkFulfilled\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| id                | VARCHAR   |                                                              |             |

## 69. Table: Aggregator\_XAU\_USD\_event\_ChainlinkRequested\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| id                | VARCHAR   |                                                              |             |

## 70. Table: Aggregator\_XAU\_USD\_event\_NewRound\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| roundId           | VARCHAR   |                                                              |             |
| startedBy         | VARCHAR   |                                                              |             |

## 71. Table: Aggregator\_XAU\_USD\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-02 18:50:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11960559                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbb98ae21a2039dd8f924e7cba9298a73a6dd4c34540b605491f93e9e54f9e88d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 94                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xea5f70faa03f5c30b96029635c8d431d1a3cd1b8                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x8183f851eb1479b7191e97545b936446fbe08eba                         |                                                              |
| newOwner          | VARCHAR   | 0x21f73d42eb58ba49ddb685dc29d3bf5c0f0373ca                         |                                                              |

## 72. Table: Aggregator\_XAU\_USD\_event\_ResponseReceived\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| response          | VARCHAR   |                                                              |             |
| answerId          | VARCHAR   |                                                              |             |
| sender            | VARCHAR   |                                                              |             |

## 73. Table: EACAggregatorProxy\_call\_confirmAggregator\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-04-06 19:01:07+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 12187957                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x3f87ca00c5613fbca9d0220a7b7bd256b5b38506bd94fb38096b1aea13b826a0 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 173                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0,0,1                                                            | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3e7d1eab13ad0104d2750b8863b489d65364e32d                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_aggregator       | VARCHAR   | 0xa964273552c1dba201f5f000215f5bd5576e8f93                         |                                                                                                                        |

## 74. Table: LinkToken\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-26 15:49:20+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9358377                                                                        | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc9d9fc3c33b05ef013aed84386a7b0100754be8044c83b7c6b2af6fd777b1614             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 252                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x514910771af9ca656af840dff83e8264ecf986ca                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xf01dd641b91f316017859abafeca174bb12a48bd                                     |                                                              |
| spender           | VARCHAR   | 0x1a1c87d9a6f55d3bbb064bff1059ad37b6bdc097                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 75. Table: LinkToken\_event\_Transfer\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-06 02:43:42+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14330711                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb8fcc12afbaf6816d846eaf87a7c57601289eff37284ef1f1b3eaf82c34be5b0                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                                                    | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x514910771af9ca656af840dff83e8264ecf986ca                                                           | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x3ce9ce2f0a82d0f207e2bc8610aa41852a3b1b1b                                                           |                                                              |
| to                | VARCHAR   | 0xdaf50e6f70b6b11f01c063f1ec23145c8e7e6083                                                           |                                                              |
| value             | VARCHAR   | 100000000000000000                                                                                   |                                                              |
| data              | VARCHAR   | 0x40429946000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000 |                                                              |
