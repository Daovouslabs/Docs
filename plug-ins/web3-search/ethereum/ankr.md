# ankr

## 1. Table: GlobalPool\_R38\_call\_crossChainStake\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-10-27 15:01:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 13500080                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xec69ed2bcf4f5e5ad7d1579effc129fa519c0db27159a5d992486aca76942a9c | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 338                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x84db6ee82b7cf3b47e8f19270abde5718b936670                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| addresses          | VARCHAR   | 0x6AD55cbD6dF050673698ba58868Ae5dCC5F1924f                         |                                                                                                                        |
| amounts            | VARCHAR   | 68300000000000000000                                               |                                                                                                                        |

## 2. Table: GlobalPool\_R38\_call\_pushToBeacon\_history

| Column                  | Type      | Example                                                                                              | Description                                                                                                            |
| ----------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp        | TIMESTAMP | 2023-07-03 12:17:23+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number           | INTEGER   | 17613387                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash       | VARCHAR   | 0xa94ade3f99b23e6e956c822179f477a82d24ededf8913edcb8877ff428b65410                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index      | INTEGER   | 52                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address          | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address             | VARCHAR   | 0x84db6ee82b7cf3b47e8f19270abde5718b936670                                                           | Address of the called contract                                                                                         |
| status                  | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                   | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| pubkey                  | VARCHAR   | 0xa552d322be87e2972c699c07885fabd4ce38b5cc5536aabc9dec808134aca1f2951d40fcb98a0cc7be4a56e6f7fe564a   |                                                                                                                        |
| withdrawal\_credentials | VARCHAR   | 0x01000000000000000000000067428de0680494e448f1a19d33c2022a51719348                                   |                                                                                                                        |
| signature               | VARCHAR   | 0x8fdc665212916c681040456eab25f633ab8b937d4c4b128a2b3d4a9361800a7d895be185b46b9b4bdc5b32fb9eb0d2ef05 |                                                                                                                        |
| deposit\_data\_root     | VARCHAR   | 0x3367e3d526f5088619e0251fb3d9a59a79bd47686add470672627ae4d22719db                                   |                                                                                                                        |

## 3. Table: GlobalPool\_R38\_call\_stakeAndClaimAethB\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-11-14 16:05:15+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 13614941                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x24dbf44ffcab08d07033109aa1fb128b62874f69c0f1892d67fae21f3732b209 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 117                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x84db6ee82b7cf3b47e8f19270abde5718b936670                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 4. Table: GlobalPool\_R38\_call\_stakeAndClaimAethC\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-05-27 11:57:35+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17350233                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x7bc0e76a57dcd2516838166bd16cc4d0de63e72ac924f15ea1c7d3ab8d631628 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 11                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x84db6ee82b7cf3b47e8f19270abde5718b936670                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 5. Table: GlobalPool\_R38\_call\_stake\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-04-04 17:17:01+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 12174439                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xeefa57d98b2d79e972430269f55b4d52af4bd8044c4da25757b429623e28d54d | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 206                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x84db6ee82b7cf3b47e8f19270abde5718b936670                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 6. Table: GlobalPool\_R38\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-09 19:08:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11225126                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa213b9d5fe615c1bab3fd8043960e26c346cad7ed881991932dedb6b5b831eb2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 45                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x84db6ee82b7cf3b47e8f19270abde5718b936670                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x2ffc59d32a524611bb891cab759112a51f9e33c0                         |                                                              |

## 7. Table: GlobalPool\_R38\_event\_PoolCompleted\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| pool              | VARCHAR   |                                                              |             |

## 8. Table: GlobalPool\_R38\_event\_PoolOnGoing\_history

| Column            | Type      | Example                                                                                            | Description                                                  |
| ----------------- | --------- | -------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-29 09:44:14+00:00                                                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12728249                                                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb112d293512475093d3514902ac776d21d91b296ecbad409f723b00310cc77ab                                 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 332                                                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x84db6ee82b7cf3b47e8f19270abde5718b936670                                                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0x8eef096bcd2d134923e2f771f8e06799b3a44486effa4c60ee74a2c4c987506f03a632a8bfee569fba5aea3c948c2f89 |                                                              |

## 9. Table: GlobalPool\_R38\_event\_ProviderExited\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-01 21:23:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13335844                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb0a5ee867147dd3b31b64e34e3aec04ecd55d933ba49634314b72479b20699aa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 84                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x84db6ee82b7cf3b47e8f19270abde5718b936670                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xa4104c8457557cebcd6f8a55bb223110ea4c324e                         |                                                              |

## 10. Table: GlobalPool\_R38\_event\_ProviderLockedEthReset\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-31 19:04:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15448349                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x542a0bcaeb8273a1558df141782d7fae45f8ec30202ee22d5bbe67230aeef037 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 185                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x84db6ee82b7cf3b47e8f19270abde5718b936670                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x7947bf23ca755bec780b80b6a08c45ef38eacc14                         |                                                              |
| amount            | VARCHAR   | 1979779194614655744                                                |                                                              |
| legacy            | VARCHAR   | 0                                                                  |                                                              |

## 11. Table: GlobalPool\_R38\_event\_ProviderSlashedAnkr\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| provider          | VARCHAR   |                                                              |             |
| ankrAmount        | VARCHAR   |                                                              |             |
| etherEquivalence  | VARCHAR   |                                                              |             |

## 12. Table: GlobalPool\_R38\_event\_ProviderSlashedEth\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| provider          | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 13. Table: GlobalPool\_R38\_event\_ProviderToppedUpAnkr\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-25 22:11:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12312065                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb7c7dd27dc7038ae9c41be7559279c4a01561c4a3b225f8589d32edd0113a9b7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 367                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x84db6ee82b7cf3b47e8f19270abde5718b936670                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xdb0015b3704eb75c0377c3f691a0a390608606c9                         |                                                              |
| amount            | VARCHAR   | 25000000000000000000000                                            |                                                              |

## 14. Table: GlobalPool\_R38\_event\_ProviderToppedUpEth\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-07 23:59:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11408754                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdab0cc7189bfa6bfae80268c5f2d0148b07f00cb9d92bd3d19d9cab671cce927 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 87                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x84db6ee82b7cf3b47e8f19270abde5718b936670                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xf93ef5f324167ff243e6a5bbbd5ceaf2fcff91d4                         |                                                              |
| amount            | VARCHAR   | 3000000000000000000                                                |                                                              |

## 15. Table: GlobalPool\_R38\_event\_RewardClaimed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-05 06:20:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13357396                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0661f662320e94a5ebe8485151c1f87989b2475b35c3885d53c52bc664158e44 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 454                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x84db6ee82b7cf3b47e8f19270abde5718b936670                         | Address of the contract that produced the log                |
| staker            | VARCHAR   | 0xeb79121e712ecf9bfebeac401dbfcea9be4c7b45                         |                                                              |
| amount            | VARCHAR   | 7736975041205909696                                                |                                                              |
| isAETH            | VARCHAR   | true                                                               |                                                              |

## 16. Table: GlobalPool\_R38\_event\_StakeConfirmed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-26 20:31:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11531501                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x30c703651979fa4d4c6750d6a4219e6776b118a07e9a86e0c4ce0e1a3d719e18 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 117                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x84db6ee82b7cf3b47e8f19270abde5718b936670                         | Address of the contract that produced the log                |
| staker            | VARCHAR   | 0x4f91a47ee8dd4c20dbf1752f711797620c5121b1                         |                                                              |
| amount            | VARCHAR   | 4000000000000000000                                                |                                                              |

## 17. Table: GlobalPool\_R38\_event\_StakePending\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-20 09:52:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11893149                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa120ce4c2f7af311511e516856f32948dc834c770eec1fd40f779d5fcff6d422 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 60                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x84db6ee82b7cf3b47e8f19270abde5718b936670                         | Address of the contract that produced the log                |
| staker            | VARCHAR   | 0x0f117363b992c988bcd4033b0b100d5ae90cb5b4                         |                                                              |
| amount            | VARCHAR   | 400000000000000000000                                              |                                                              |

## 18. Table: GlobalPool\_R38\_event\_StakeRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-18 09:43:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11281177                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5e9e0b23ce68ed681a9ff60c15a2830304183a518c10aed0698c1c332df967a6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 115                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x84db6ee82b7cf3b47e8f19270abde5718b936670                         | Address of the contract that produced the log                |
| staker            | VARCHAR   | 0x7a869e79b3772fd4d1bde39cba3d00e22e9639ca                         |                                                              |
| amount            | VARCHAR   | 10000000000000000000                                               |                                                              |
