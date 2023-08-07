# chainlink

## 1. Table: AccessControlledOffchainAggregator\_event\_AddedAccess\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-26 10:38:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7448943                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcdfd6734b49d71cf631de0de6a6fc70b0f29fdf73ea6b31fc0a878e98b3c91a7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45b181254ab5b5dfac5cf6165418b8eecae351ce                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xee631272f4831b2e4a44ccc682303625d0d12bec                         |                                                              |

## 2. Table: AccessControlledOffchainAggregator\_event\_AnswerUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-04 02:30:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 25804800                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7cde0b7f890e3fd010d794e1405835af179c26958b9af5e19d22d2972de124b1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9450a29ef091b625e976ce66f2a5818e20791999                         | Address of the contract that produced the log                |
| current           | VARCHAR   | 2117000000                                                         |                                                              |
| roundId           | VARCHAR   | 353150                                                             |                                                              |
| updatedAt         | VARCHAR   | 1675477856                                                         |                                                              |

## 3. Table: AccessControlledOffchainAggregator\_event\_BillingAccessControllerSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-23 15:17:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 19020869                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2614daee1b30779239b16b74b15f2d88c7837b7509da95a3e37e98f62d9c3e74 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x375b72e40c1a16424ead361ec308b1cbcf5cb721                         | Address of the contract that produced the log                |
| old               | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| current           | VARCHAR   | 0x528ad9a405128fc16df86628c2a1314fad1c029b                         |                                                              |

## 4. Table: AccessControlledOffchainAggregator\_event\_BillingSet\_history

| Column                  | Type      | Example                                                            | Description                                                  |
| ----------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp        | TIMESTAMP | 2023-06-20 13:55:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number           | INTEGER   | 31576145                                                           | The block number where this event was emitted                |
| transaction\_hash       | VARCHAR   | 0xb63034429bf8c0ef2837d550535674b6b9a7aa18a53e990b1fd53b45bdc3dec3 | Hash of the transactions in which this event was emitted     |
| log\_index              | INTEGER   | 75                                                                 | Integer of the log index position in the block of this event |
| contract\_address       | VARCHAR   | 0xfbd998938f8f7210eec3d1e12e80a10972f02aed                         | Address of the contract that produced the log                |
| maximumGasPrice         | VARCHAR   | 1                                                                  |                                                              |
| reasonableGasPrice      | VARCHAR   | 1                                                                  |                                                              |
| microLinkPerEth         | VARCHAR   | 1                                                                  |                                                              |
| linkGweiPerObservation  | VARCHAR   | 18805944                                                           |                                                              |
| linkGweiPerTransmission | VARCHAR   | 113028158                                                          |                                                              |

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
| block\_timestamp          | TIMESTAMP | 2022-11-28 21:49:34+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number             | INTEGER   | 22965835                                                                                             | The block number where this event was emitted                |
| transaction\_hash         | VARCHAR   | 0x5b94b4ba1d41673448f9aa12fe331b571133a694b5c8d71cb4fd6689a91becae                                   | Hash of the transactions in which this event was emitted     |
| log\_index                | INTEGER   | 51                                                                                                   | Integer of the log index position in the block of this event |
| contract\_address         | VARCHAR   | 0x318bfa8c1ce223836fde0ad60e8a5e04fd0d8924                                                           | Address of the contract that produced the log                |
| previousConfigBlockNumber | VARCHAR   | 18977878                                                                                             |                                                              |
| configCount               | VARCHAR   | 3                                                                                                    |                                                              |
| signers                   | VARCHAR   | 0x0000000000000000000000000000000000000001,0x0000000000000000000000000000000000000002,0x000000000000 |                                                              |
| transmitters              | VARCHAR   | 0x0000000000000000000000000000000000000005,0x0000000000000000000000000000000000000006,0x000000000000 |                                                              |
| threshold                 | VARCHAR   | 1                                                                                                    |                                                              |
| encodedConfigVersion      | VARCHAR   | 4294967295                                                                                           |                                                              |
| encoded                   | VARCHAR   | 0x                                                                                                   |                                                              |

## 8. Table: AccessControlledOffchainAggregator\_event\_NewRound\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-17 21:56:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5765715                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfbdf31fecee203773535a63a3ab2d6040fa51918a8aad0157d2bf76388deee4d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0accdfd55026873cb12f75f66513b42fb4974245                         | Address of the contract that produced the log                |
| roundId           | VARCHAR   | 514                                                                |                                                              |
| startedBy         | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| startedAt         | VARCHAR   | 1634507787                                                         |                                                              |

## 9. Table: AccessControlledOffchainAggregator\_event\_NewTransmission\_history

| Column            | Type      | Example                                                                                         | Description                                                  |
| ----------------- | --------- | ----------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-28 08:15:40+00:00                                                                       | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29322944                                                                                        | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x07058e651c34f083f4830d0b63896f569a4b8168d0c1b5cfb11ce65dc3f28519                              | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 38                                                                                              | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0a58227e7d7a8175e4f5f8a0d32968d153b9ce59                                                      | Address of the contract that produced the log                |
| aggregatorRoundId | VARCHAR   | 25359                                                                                           |                                                              |
| answer            | VARCHAR   | 68970                                                                                           |                                                              |
| transmitter       | VARCHAR   | 0x00b1943ffb046ac69e9618361f1ead3cce112fea                                                      |                                                              |
| observations      | VARCHAR   | 68936,68941,68952,68955,68955,68955,68956,68962,68970,68970,68972,68972,68988,69000,69016,69375 |                                                              |
| observers         | VARCHAR   | 0x020d08040c0e00070601090a050b030f                                                              |                                                              |
| rawReportContext  | VARCHAR   | 0x00000000000000000000007c9845b85f79cf9d34557728611657b20001d2b501                              |                                                              |

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
| block\_timestamp  | TIMESTAMP | 2021-10-22 16:03:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5965537                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6f31ca79f3af631ceee42239945fb99fb83bda34a433c97384606e07ce622aaa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9d0aaba64b0ba4650419a37d14175da05471793c                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x5f5320f1c556f6332c25bfc1cb09bb96f3ddc40d                         |                                                              |
| to                | VARCHAR   | 0x75d8a28b87f5a88849542a7e1ac838f19b5d34c7                         |                                                              |

## 12. Table: AccessControlledOffchainAggregator\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-04 17:29:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11683401                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1b5088cb1b920523faa60ad94e67873520a5a6d87ee4b1fdbe036970824fa6b8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x92398caf00d65e9a63b5d50d1cbd53223137a400                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xee631272f4831b2e4a44ccc682303625d0d12bec                         |                                                              |
| to                | VARCHAR   | 0x75d8a28b87f5a88849542a7e1ac838f19b5d34c7                         |                                                              |

## 13. Table: AccessControlledOffchainAggregator\_event\_PayeeshipTransferRequested\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-18 20:08:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4527138                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe5c9498d595c7d0e10f038bdc4aee5dfbef4460a00ea70e5b307195b1783f6d5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 76                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcb7f6ef54bdc05b704a0acf604a6a16c53d359e1                         | Address of the contract that produced the log                |
| transmitter       | VARCHAR   | 0x0499bea33347cb62d79a9c0b1eda01d8d329894c                         |                                                              |
| current           | VARCHAR   | 0x15918ff7f6c44592c81d999b442956b07d26cc44                         |                                                              |
| proposed          | VARCHAR   | 0x7c2a9d03991d808b6a3c7967ba174d4acdc085db                         |                                                              |

## 14. Table: AccessControlledOffchainAggregator\_event\_PayeeshipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-01 16:31:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11553302                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3eb68a5d068aab5b9c9d94c1bb8031f4da5b05d54cf868b1b839f89998a601e3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 17                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x92398caf00d65e9a63b5d50d1cbd53223137a400                         | Address of the contract that produced the log                |
| transmitter       | VARCHAR   | 0x5b17db9668bb9cbfe87f416b4da1132b5193959d                         |                                                              |
| previous          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| current           | VARCHAR   | 0x3615fa045f00ae0ed60dc0141911757c2adc5e03                         |                                                              |

## 15. Table: AccessControlledOffchainAggregator\_event\_RemovedAccess\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-14 21:20:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 2668590                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3cd32ddd31bb79b03884377a364b07c790d80345589ef1b5842cef6d2397f848 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcc4633a1a85d553623bac7945bd87cfad6e6a8c8                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xd4b705299a16e85ba7ef7dfa5c2b318b973bba7c                         |                                                              |

## 16. Table: AccessControlledOffchainAggregator\_event\_RequesterAccessControllerSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-19 19:51:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5844959                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x17735ad76b5952204fa87b7be02a6973098ee26e5727739036974f0beefcdde8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9d0aaba64b0ba4650419a37d14175da05471793c                         | Address of the contract that produced the log                |
| old               | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| current           | VARCHAR   | 0x7dda421b2914a28501c8106bcdde4427de9aa650                         |                                                              |

## 17. Table: AccessControlledOffchainAggregator\_event\_RoundRequested\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-07 08:00:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 31016621                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9776afd1b4697763f6b9c2924a6a17a6b47e7d9aa023efad5278baa1b39e894f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xefaa69f461e0aaf0be1798b01371daf14ac55ea8                         | Address of the contract that produced the log                |
| requester         | VARCHAR   | 0xba5aa1c7b855a62be1d789bbf92bc0974fce4f5a                         |                                                              |
| configDigest      | VARCHAR   | 0x4282421243527097352c79c6fcbd7a21                                 |                                                              |
| epoch             | VARCHAR   | 138686                                                             |                                                              |
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
| block\_timestamp   | TIMESTAMP | 2022-06-13 16:52:18+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15985078                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xbf2ca2234652b8d03b3cc3450d250990ea1e1a23378690c8746171e43613a703 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 8                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0,0,1                                                            | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x36e039e6391a5e7a7267650979fdf613f659be5d                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_aggregator       | VARCHAR   | 0x4bc3bebb7eb60155f8b38771d9926d9a23dad5b5                         |                                                                                                                        |
