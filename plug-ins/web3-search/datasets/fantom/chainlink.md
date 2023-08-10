# chainlink

## 1. Table: AccessControlledOffchainAggregator\_event\_AddedAccess\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-02 09:52:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 32349447                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x266eeb2e78249fd441a3295701ebaebd2b3018675c4d3fc4c630bac03a5d8be8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 32                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd867c068534ad7d3be0fe4f321aacddce371db1a                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x95d3fff86a754ab81a7c59fcab1468a2076f8c9b                         |                                                              |

## 2. Table: AccessControlledOffchainAggregator\_event\_AnswerUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-09 02:05:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 61812756                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7eefc1c4fd3889b34768cea475e87ce9cfb14c36a9503989711daa87da73e040 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 39                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x15e682ba1f3e68d507eb8d21f2d2a90ba82559ae                         | Address of the contract that produced the log                |
| current           | VARCHAR   | 99990000                                                           |                                                              |
| roundId           | VARCHAR   | 10867                                                              |                                                              |
| updatedAt         | VARCHAR   | 1683597937                                                         |                                                              |

## 3. Table: AccessControlledOffchainAggregator\_event\_BillingAccessControllerSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-15 18:24:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 40591090                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6325bb2b9fef59843066e0c87de38ef8c8fd64db5388052083ef047cfc4a6e36 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa4ea84d48d59f84bdd1a7f8da9410d2da2261d6f                         | Address of the contract that produced the log                |
| old               | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| current           | VARCHAR   | 0x57824ad627e5b37ca01296b7f306c66396ee9885                         |                                                              |

## 4. Table: AccessControlledOffchainAggregator\_event\_BillingSet\_history

| Column                  | Type      | Example                                                            | Description                                                  |
| ----------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp        | TIMESTAMP | 2022-06-09 15:00:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number           | INTEGER   | 40143935                                                           | The block number where this event was emitted                |
| transaction\_hash       | VARCHAR   | 0x958f2f25b6cc13e5b02dd53baff9da796a472cf866a7f44e49bf2e8a8fac1106 | Hash of the transactions in which this event was emitted     |
| log\_index              | INTEGER   | 308                                                                | Integer of the log index position in the block of this event |
| contract\_address       | VARCHAR   | 0x50f8339e5668f85bcb4d8df987c12b7df4c99084                         | Address of the contract that produced the log                |
| maximumGasPrice         | VARCHAR   | 15000                                                              |                                                              |
| reasonableGasPrice      | VARCHAR   | 250                                                                |                                                              |
| microLinkPerEth         | VARCHAR   | 36900                                                              |                                                              |
| linkGweiPerObservation  | VARCHAR   | 3384865                                                            |                                                              |
| linkGweiPerTransmission | VARCHAR   | 20312996                                                           |                                                              |

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
| block\_timestamp          | TIMESTAMP | 2021-08-10 22:15:36+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number             | INTEGER   | 14287465                                                                                             | The block number where this event was emitted                |
| transaction\_hash         | VARCHAR   | 0x09a9182300a18fb0f511c6b16b44ca960d7e9bd11a74ecad8f334de6eec12101                                   | Hash of the transactions in which this event was emitted     |
| log\_index                | INTEGER   | 34                                                                                                   | Integer of the log index position in the block of this event |
| contract\_address         | VARCHAR   | 0x472105bb154bd92580a9669ab2483864c3de9974                                                           | Address of the contract that produced the log                |
| previousConfigBlockNumber | VARCHAR   | 14204748                                                                                             |                                                              |
| configCount               | VARCHAR   | 2                                                                                                    |                                                              |
| signers                   | VARCHAR   | 0xb97283D1B2fe3b32Cc616fE8130a731AFDdf587a,0x7fc01A90f7863B2Aa57035Cf63366C0Fc57909De,0x5f83b9f1330A |                                                              |
| transmitters              | VARCHAR   | 0x9482f1C1a7Be7376373cc17274c573085059bFEE,0x05Ee5882122A86C8D15D8D5ECB42830503A7d0d8,0x31C67a7132DB |                                                              |
| threshold                 | VARCHAR   | 5                                                                                                    |                                                              |
| encodedConfigVersion      | VARCHAR   | 1                                                                                                    |                                                              |
| encoded                   | VARCHAR   | 0x00000000000000000000000000000000000000000000000000000000000000200000000000000000000000000000000000 |                                                              |

## 8. Table: AccessControlledOffchainAggregator\_event\_NewRound\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-29 13:20:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 61060264                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x71c717a39d9eb0c7c65685ffad1ddf8e54e2add1dfa766874065cc2f0f77fdc8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 48                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x15e682ba1f3e68d507eb8d21f2d2a90ba82559ae                         | Address of the contract that produced the log                |
| roundId           | VARCHAR   | 10846                                                              |                                                              |
| startedBy         | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| startedAt         | VARCHAR   | 1682774433                                                         |                                                              |

## 9. Table: AccessControlledOffchainAggregator\_event\_NewTransmission\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-27 12:09:23+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 23280380                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe15af680a5aec7c82ff814326f1e0ae42bf692ed37dd46dca2cac14f2a5166ca                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                                                    | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x15e682ba1f3e68d507eb8d21f2d2a90ba82559ae                                                           | Address of the contract that produced the log                |
| aggregatorRoundId | VARCHAR   | 199                                                                                                  |                                                              |
| answer            | VARCHAR   | 100029505                                                                                            |                                                              |
| transmitter       | VARCHAR   | 0xe9300e1dada80a7178b14f3980616d2657e706d5                                                           |                                                              |
| observations      | VARCHAR   | 99980902,99994077,100007252,100007252,100007252,100010701,100010701,100010701,100029505,100029505,10 |                                                              |
| observers         | VARCHAR   | 0x0002060e0401080f0c09050d0a0b0307                                                                   |                                                              |
| rawReportContext  | VARCHAR   | 0x0000000000000000000000fda1b0a9c723d3c34733bbe5ea6c80840000ccc604                                   |                                                              |

## 10. Table: AccessControlledOffchainAggregator\_event\_OraclePaid\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| transmitter       | VARCHAR   |                                                              |             |
| payee             | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 11. Table: AccessControlledOffchainAggregator\_event\_OwnershipTransferRequested\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-03 21:57:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 23909181                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7029a1493e3b0cb11feb04a3dc4551ba336153d331ba694041b9b23466762b1a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 14                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x69ae9c103f8f39df5d35fc6bfcf346223a71ba48                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xda96660167d4f8e70b7607cebc478616927f8ede                         |                                                              |
| to                | VARCHAR   | 0x9ba4c51512752e79317b59ab4577658e12a43f55                         |                                                              |

## 12. Table: AccessControlledOffchainAggregator\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-03 23:45:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 23916601                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5bc5979d4f1320d60c2a1db6af398273be55fd3e140e43601cc36e1b2c8741b5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 19                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x69ae9c103f8f39df5d35fc6bfcf346223a71ba48                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xda96660167d4f8e70b7607cebc478616927f8ede                         |                                                              |
| to                | VARCHAR   | 0x9ba4c51512752e79317b59ab4577658e12a43f55                         |                                                              |

## 13. Table: AccessControlledOffchainAggregator\_event\_PayeeshipTransferRequested\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-22 19:47:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 66192758                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc5fa44e028434b9e26982399d7a9b44ff11443a5b19409dda20f105083ce3e1d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf13148424cc6fdfa793eae323b081c130ff839f1                         | Address of the contract that produced the log                |
| transmitter       | VARCHAR   | 0x09285fbb87b75fba9400683233c0bc1de53afca8                         |                                                              |
| current           | VARCHAR   | 0xd9459cc85e78e0336adb349eabf257dbaf9d5a2b                         |                                                              |
| proposed          | VARCHAR   | 0x552c56469c4ca50d7a35755702b95b9ffb4a4471                         |                                                              |

## 14. Table: AccessControlledOffchainAggregator\_event\_PayeeshipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-06 22:32:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 24195535                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2613cff697ae10c97ce21c050e1129e21698e2a659185bf1ce7a70868bc82094 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 17                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbfc6236ce03765739db1393421c0d7675eed8d7d                         | Address of the contract that produced the log                |
| transmitter       | VARCHAR   | 0x991340a2a87db4397339e913e7bbdc1847b61414                         |                                                              |
| previous          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| current           | VARCHAR   | 0xfae26207ab74ee528214ee92f94427f8cdbb6a32                         |                                                              |

## 15. Table: AccessControlledOffchainAggregator\_event\_RemovedAccess\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-03 22:20:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 23910799                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x90b3c4dcae500fc576ce47e21c183759e9164991def908050fa1b9c7976e4504 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 9                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x69ae9c103f8f39df5d35fc6bfcf346223a71ba48                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xda96660167d4f8e70b7607cebc478616927f8ede                         |                                                              |

## 16. Table: AccessControlledOffchainAggregator\_event\_RequesterAccessControllerSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-01 17:00:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 32289010                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd82fd3a9eb462914b9f34ac9d716b05c1a870d8b47f0274bd68ac1501c7f2624 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 12                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd867c068534ad7d3be0fe4f321aacddce371db1a                         | Address of the contract that produced the log                |
| old               | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| current           | VARCHAR   | 0x2cfd1a55e0b2f9c7921cd5e942f42387ca7c5dc7                         |                                                              |

## 17. Table: AccessControlledOffchainAggregator\_event\_RoundRequested\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-03 21:37:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 23907733                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1faeadacefc6d084ba94d759919431561eeb8607ad6820567587fba0313db9b9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x69ae9c103f8f39df5d35fc6bfcf346223a71ba48                         | Address of the contract that produced the log                |
| requester         | VARCHAR   | 0xda96660167d4f8e70b7607cebc478616927f8ede                         |                                                              |
| configDigest      | VARCHAR   | 0xd4d49adfc04d00b11006d6379ea95d6c                                 |                                                              |
| epoch             | VARCHAR   | 556                                                                |                                                              |
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
