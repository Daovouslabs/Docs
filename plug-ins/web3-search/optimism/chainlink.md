# chainlink

## 1. Table: AccessControlledOffchainAggregator\_event\_AddedAccess\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-27 09:04:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13259772                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8a1140a39ba86d0f989099ecfb1a365834a307b8375497bd57a9f2de0187096b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f6dfdfd4d68f68b2692e79f9e94796fc8015770                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x0d276fc14719f9292d5c1ea2198673d1f4269246                         |                                                              |

## 2. Table: AccessControlledOffchainAggregator\_event\_AnswerUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-14 22:09:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 3555092                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb1212a87467e6c722920efb2d882a8e653597d179a50291ee196710fba36c69c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x584f57911b6eedab5503e202f8e193663c9bd3db                         | Address of the contract that produced the log                |
| current           | VARCHAR   | 454720000                                                          |                                                              |
| roundId           | VARCHAR   | 10856                                                              |                                                              |
| updatedAt         | VARCHAR   | 1644876576                                                         |                                                              |

## 3. Table: AccessControlledOffchainAggregator\_event\_BillingAccessControllerSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-07 16:14:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 35469638                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2744792ac3747e084e43774da88c71a220f290eebecd08ced08a333f20c9e3de | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x615209a932768861908161cccefccac9b582ace8                         | Address of the contract that produced the log                |
| old               | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| current           | VARCHAR   | 0x0f86056d00bcf39baef81bbed1786e6f32c1a5fe                         |                                                              |

## 4. Table: AccessControlledOffchainAggregator\_event\_BillingSet\_history

| Column                  | Type      | Example                                                            | Description                                                  |
| ----------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp        | TIMESTAMP | 2023-02-07 17:23:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number           | INTEGER   | 72768584                                                           | The block number where this event was emitted                |
| transaction\_hash       | VARCHAR   | 0x5aed3716f4657d5ceeccf4d7f0408f169d60046833d361b0ca26e353a28b0be6 | Hash of the transactions in which this event was emitted     |
| log\_index              | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address       | VARCHAR   | 0xd1cb03cc31caa72d34dba7ebe21897d9580c4af0                         | Address of the contract that produced the log                |
| maximumGasPrice         | VARCHAR   | 10                                                                 |                                                              |
| reasonableGasPrice      | VARCHAR   | 1                                                                  |                                                              |
| microLinkPerEth         | VARCHAR   | 234942446                                                          |                                                              |
| linkGweiPerObservation  | VARCHAR   | 8855066                                                            |                                                              |
| linkGweiPerTransmission | VARCHAR   | 53132422                                                           |                                                              |

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
| block\_timestamp          | TIMESTAMP | 2022-09-06 22:47:50+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number             | INTEGER   | 22201923                                                                                             | The block number where this event was emitted                |
| transaction\_hash         | VARCHAR   | 0x3ca806ae5ab51d2444107e8d25d809305857cdf96d07ca5c48011af018752240                                   | Hash of the transactions in which this event was emitted     |
| log\_index                | INTEGER   | 21                                                                                                   | Integer of the log index position in the block of this event |
| contract\_address         | VARCHAR   | 0x0c1272d2ac652d10d03bb4deb0d31f15ea3eab2b                                                           | Address of the contract that produced the log                |
| previousConfigBlockNumber | VARCHAR   | 13392516                                                                                             |                                                              |
| configCount               | VARCHAR   | 3                                                                                                    |                                                              |
| signers                   | VARCHAR   | 0x4daE5a769FA9CEe52dC67a8DefABd7B99CDe66BC,0xE3d07E1f7342aEdaAB3F84D6cB2611276C58Ed67,0x37Da5d6D39d5 |                                                              |
| transmitters              | VARCHAR   | 0x56873b5E7299d2C0d4ab28d9128D734CF3bf8398,0x2bdF9249c350C68a43a9714c1b9153af54751b1C,0x85C8aAA2232D |                                                              |
| threshold                 | VARCHAR   | 3                                                                                                    |                                                              |
| encodedConfigVersion      | VARCHAR   | 1                                                                                                    |                                                              |
| encoded                   | VARCHAR   | 0x00000000000000000000000000000000000000000000000000000000000000200000000000000000000000000000000000 |                                                              |

## 8. Table: AccessControlledOffchainAggregator\_event\_NewRound\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-11 02:04:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 18674973                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe9aacebad3969131aea822bf10490b3a096f6598312f7d2865c1b1c6394cf77c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x02f5e9e9dcc66ba6392f6904d5fcf8625d9b19c9                         | Address of the contract that produced the log                |
| roundId           | VARCHAR   | 51154                                                              |                                                              |
| startedBy         | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| startedAt         | VARCHAR   | 1660183464                                                         |                                                              |

## 9. Table: AccessControlledOffchainAggregator\_event\_NewTransmission\_history

| Column            | Type      | Example                                                                                   | Description                                                  |
| ----------------- | --------- | ----------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-12 14:25:43+00:00                                                                 | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5721367                                                                                   | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd8026e22c32409a6d08bc9b0e183180cc94cab45501531e0ac44bd9887310bb7                        | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                                         | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x663ed3d2ab9f8d5282a94ba4636e346e59bddeb9                                                | Address of the contract that produced the log                |
| aggregatorRoundId | VARCHAR   | 3136                                                                                      |                                                              |
| answer            | VARCHAR   | 12033579                                                                                  |                                                              |
| transmitter       | VARCHAR   | 0x2878c587eba4c4251f97784ce124f7387305ab32                                                |                                                              |
| observations      | VARCHAR   | 12002312,12015557,12015557,12027420,12033579,12033579,12037478,12041864,12042955,12044201 |                                                              |
| observers         | VARCHAR   | 0x02000905010406070308                                                                    |                                                              |
| rawReportContext  | VARCHAR   | 0x00000000000000000000008e653819348c39daca17fdc827d23e890000692101                        |                                                              |

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
| block\_timestamp  | TIMESTAMP | 2022-02-02 19:30:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 3135233                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb2791362f8d6680bf13ce64678a6e8320a2fb2b7af418e738333a36bcdd4d1e7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7c56d3650f9acd992b3aa635c04a311c54ad264c                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x03863f6ad36f1fcd908517e3c56c6b3fd3f50752                         |                                                              |
| to                | VARCHAR   | 0xabc73a7dbd0a1d6576d55f19809a6f017913c078                         |                                                              |

## 12. Table: AccessControlledOffchainAggregator\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-26 00:37:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 42273339                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1def4c38c5ab99c9aae87b15b672be850e1332fe89dec723629d605491adf792 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x65f2c716937fb44b2c28417a7afc2daccf1c2d61                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x03863f6ad36f1fcd908517e3c56c6b3fd3f50752                         |                                                              |
| to                | VARCHAR   | 0xabc73a7dbd0a1d6576d55f19809a6f017913c078                         |                                                              |

## 13. Table: AccessControlledOffchainAggregator\_event\_PayeeshipTransferRequested\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-22 19:55:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 107228471                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe728dac4d4226c5350fa6891de80292cbcc24a807dde53b0a7264b38446ca053 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 12                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6e7a3ceb4797d0fd7b9854b251929ad68849951a                         | Address of the contract that produced the log                |
| transmitter       | VARCHAR   | 0xf9b9fbeb0512283a445f1a948a78af8f954b3343                         |                                                              |
| current           | VARCHAR   | 0xd9459cc85e78e0336adb349eabf257dbaf9d5a2b                         |                                                              |
| proposed          | VARCHAR   | 0x552c56469c4ca50d7a35755702b95b9ffb4a4471                         |                                                              |

## 14. Table: AccessControlledOffchainAggregator\_event\_PayeeshipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-03 17:44:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6992737                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6b4b38af83c5464df86d157c3c1b8c9b3db74db378232be1240fe72459bfd567 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xab544fdad5f68f0f8e53284f942d76177635a3d6                         | Address of the contract that produced the log                |
| transmitter       | VARCHAR   | 0xf9b9fbeb0512283a445f1a948a78af8f954b3343                         |                                                              |
| previous          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| current           | VARCHAR   | 0xd9459cc85e78e0336adb349eabf257dbaf9d5a2b                         |                                                              |

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
| block\_timestamp  | TIMESTAMP | 2022-01-24 21:32:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 2771675                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x68cc5024e99b5eb39e27bc8ff1601d2a6a7379c848ec251e8ff24fed265c0044 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xaa75ace4575abbe1d237d991a7461f497a56a8f0                         | Address of the contract that produced the log                |
| old               | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| current           | VARCHAR   | 0x1f69648f1b985344cdeccd5d2a36255cd22aded7                         |                                                              |

## 17. Table: AccessControlledOffchainAggregator\_event\_RoundRequested\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-27 09:54:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15997635                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1589b0df96386c1c78f3e9ee0150fdeb4c3a44501437045b0bdadc87634ddacf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe4391393205b6265585250e7a026103a0d1e168d                         | Address of the contract that produced the log                |
| requester         | VARCHAR   | 0x473ab11a7b649064ee50b255b5b14dfe284a0373                         |                                                              |
| configDigest      | VARCHAR   | 0x07317c89866714eca3c94c21472595ec                                 |                                                              |
| epoch             | VARCHAR   | 114                                                                |                                                              |
| round             | VARCHAR   | 6                                                                  |                                                              |

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
| \_aggregator       | VARCHAR   |                                                                                                                        |             |
