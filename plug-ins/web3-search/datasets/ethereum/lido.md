# lido

## 1. Table: Lido\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-25 01:22:11+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13680589                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcddf0e8f3f3867973cb44d1eec60e2191c7229d457adb148d5013e3c023853df             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 160                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xae7ab96520de3a18e5e111b5eaab095312d7fe84                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x29f5ea6951caf386a40359953d9fc38e069fb0e9                                     |                                                              |
| spender           | VARCHAR   | 0x11111112542d85b3ef69ae05771c2dccff4faa26                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039446817749237299473400 |                                                              |

## 2. Table: Lido\_event\_ELRewardsReceived\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-17 12:20:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16648393                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x929ee62cb146baf63886d1ec78c794839ed04375669e346d3d15897caaf702c4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 271                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xae7ab96520de3a18e5e111b5eaab095312d7fe84                         | Address of the contract that produced the log                |
| amount            | VARCHAR   | 254997587493358248027                                              |                                                              |

## 3. Table: Lido\_event\_FeeDistributionSet\_history

| Column                  | Type      | Example                                                            | Description                                                  |
| ----------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp        | TIMESTAMP | 2022-07-15 14:02:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number           | INTEGER   | 15147684                                                           | The block number where this event was emitted                |
| transaction\_hash       | VARCHAR   | 0xe61167aa87b2a7aa9bd68834bf703877d22315d6d765345ebf0135eb8c33c406 | Hash of the transactions in which this event was emitted     |
| log\_index              | INTEGER   | 50                                                                 | Integer of the log index position in the block of this event |
| contract\_address       | VARCHAR   | 0xae7ab96520de3a18e5e111b5eaab095312d7fe84                         | Address of the contract that produced the log                |
| treasuryFeeBasisPoints  | VARCHAR   | 5000                                                               |                                                              |
| insuranceFeeBasisPoints | VARCHAR   | 0                                                                  |                                                              |
| operatorsFeeBasisPoints | VARCHAR   | 5000                                                               |                                                              |

## 4. Table: Lido\_event\_FeeSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-17 22:17:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11473299                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe628b61854a48bac89b878c05b2d9ed4ba04d503ebcdd7bbb97861b5934e0e53 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 146                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xae7ab96520de3a18e5e111b5eaab095312d7fe84                         | Address of the contract that produced the log                |
| feeBasisPoints    | VARCHAR   | 1000                                                               |                                                              |

## 5. Table: Lido\_event\_RecoverToVault\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| vault             | VARCHAR   |                                                              |             |
| token             | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 6. Table: Lido\_event\_Resumed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-18 23:28:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11480166                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb525e2fc0b994ee3fa734479c6d70a3f11875358ff0a26295d4096378dc9df28 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 276                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xae7ab96520de3a18e5e111b5eaab095312d7fe84                         | Address of the contract that produced the log                |

## 7. Table: Lido\_event\_ScriptResult\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| executor          | VARCHAR   |                                                              |             |
| script            | VARCHAR   |                                                              |             |
| input             | VARCHAR   |                                                              |             |
| returnData        | VARCHAR   |                                                              |             |

## 8. Table: Lido\_event\_Stopped\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 9. Table: Lido\_event\_Submitted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-29 18:16:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17800424                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0d2d9550b99ae736b66d48b025bdf5b02bd4fc71bab895511634078443fd6007 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 45                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xae7ab96520de3a18e5e111b5eaab095312d7fe84                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x49245872dad62a72fa46421cc7994b37bfdee9b3                         |                                                              |
| amount            | VARCHAR   | 96339014870355140                                                  |                                                              |
| referral          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 10. Table: Lido\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-11 16:58:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14366720                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8e59a888cc398692605a6cff95e93f8c9474128fe4391a57ed131c139f8f8295 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 353                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xae7ab96520de3a18e5e111b5eaab095312d7fe84                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xa2f987a546d4cd1c607ee8141276876c26b72bdf                         |                                                              |
| to                | VARCHAR   | 0x3298a99fe63edfd71d1ea19b1cdda9f4792502fb                         |                                                              |
| value             | VARCHAR   | 9650763483                                                         |                                                              |

## 11. Table: Lido\_event\_Unbuffered\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-11 00:56:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17453464                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd342d2a9f7539e96305059a974f49df7ccc510312b3ee4c883df3d1e99d35b5a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 175                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xae7ab96520de3a18e5e111b5eaab095312d7fe84                         | Address of the contract that produced the log                |
| amount            | VARCHAR   | 160000000000000000000                                              |                                                              |

## 12. Table: Lido\_event\_WithdrawalCredentialsSet\_history

| Column                | Type      | Example                                                            | Description                                                  |
| --------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp      | TIMESTAMP | 2020-12-18 23:28:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number         | INTEGER   | 11480167                                                           | The block number where this event was emitted                |
| transaction\_hash     | VARCHAR   | 0xe8fa96048b06a3e37aaae09f8db725e3779a7e03669ef4095af1068988f3a67b | Hash of the transactions in which this event was emitted     |
| log\_index            | INTEGER   | 236                                                                | Integer of the log index position in the block of this event |
| contract\_address     | VARCHAR   | 0xae7ab96520de3a18e5e111b5eaab095312d7fe84                         | Address of the contract that produced the log                |
| withdrawalCredentials | VARCHAR   | 0x009690e5d4472c7c0dbdf490425d89862535d2a52fb686333f3a0a9ff5d2125e |                                                              |

## 13. Table: Lido\_event\_Withdrawal\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| sender            | VARCHAR   |                                                              |             |
| tokenAmount       | VARCHAR   |                                                              |             |
| sentFromBuffer    | VARCHAR   |                                                              |             |
| pubkeyHash        | VARCHAR   |                                                              |             |
| etherAmount       | VARCHAR   |                                                              |             |

## 14. Table: Voting\_event\_CastVote\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-13 11:23:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17250734                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xba3d8856c3873180762fafb874ee56efcce2b52917399e2c5f1f144fe855a740 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 175                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2e59a20f205bb85a89c53f1936454680651e618e                         | Address of the contract that produced the log                |
| voteId            | VARCHAR   | 156                                                                |                                                              |
| voter             | VARCHAR   | 0x3e4f4dee05c6b2f42704a3a713d4ae4a084ed8ed                         |                                                              |
| supports          | VARCHAR   | true                                                               |                                                              |
| stake             | VARCHAR   | 200000000000000000                                                 |                                                              |

## 15. Table: Voting\_event\_ChangeMinQuorum\_history

| Column             | Type      | Example                                                      | Description |
| ------------------ | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number      | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index         | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address  | VARCHAR   | Address of the contract that produced the log                |             |
| minAcceptQuorumPct | VARCHAR   |                                                              |             |

## 16. Table: Voting\_event\_ChangeSupportRequired\_history

| Column             | Type      | Example                                                      | Description |
| ------------------ | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number      | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index         | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address  | VARCHAR   | Address of the contract that produced the log                |             |
| supportRequiredPct | VARCHAR   |                                                              |             |

## 17. Table: Voting\_event\_ExecuteVote\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-10 16:26:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12213212                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xebbf2d853316d332bccac058f28196cf381cf0f60b00679e207efcd079827b05 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 161                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2e59a20f205bb85a89c53f1936454680651e618e                         | Address of the contract that produced the log                |
| voteId            | VARCHAR   | 56                                                                 |                                                              |

## 18. Table: Voting\_event\_RecoverToVault\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| vault             | VARCHAR   |                                                              |             |
| token             | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 19. Table: Voting\_event\_ScriptResult\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-05 18:26:54+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13558199                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4eff47401167516fb5865bf3b52ff19d15cb154e0a7b2f8a4b00ada2ce868464                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 411                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2e59a20f205bb85a89c53f1936454680651e618e                                                           | Address of the contract that produced the log                |
| executor          | VARCHAR   | 0x5ceb19e1890f677c3676d5ecdf7c501eba01a054                                                           |                                                              |
| script            | VARCHAR   | 0x00000001b9e5cbb9ca5b0d659238807e84d0176930753d86000000c4f63648460000000000000000000000005a98fcbea5 |                                                              |
| input             | VARCHAR   | 0x                                                                                                   |                                                              |
| returnData        | VARCHAR   | 0x                                                                                                   |                                                              |

## 20. Table: Voting\_event\_StartVote\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-26 14:49:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13493616                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4457be80ae257495e6e39902aabb469ee21419694a7ba83517dec56245aacaa2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 133                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2e59a20f205bb85a89c53f1936454680651e618e                         | Address of the contract that produced the log                |
| voteId            | VARCHAR   | 96                                                                 |                                                              |
| creator           | VARCHAR   | 0xf73a1260d222f447210581ddf212d915c09a3249                         |                                                              |
| metadata          | VARCHAR   |                                                                    |                                                              |

## 21. Table: WstETH\_call\_getStETHByWstETH\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-06-13 03:09:35+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17468317                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xf7e60fc02ef7d5fd62e750578c7f8cc15e5cbeebf0b6f41e7cc0c4f083ece841 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 99                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,1,2                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x7f39c581f595b53c5cb19bd0b3f8da6c935e2ca0                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_wstETHAmount     | VARCHAR   | 1000000000000000000                                                |                                                                                                                        |

## 22. Table: WstETH\_call\_getWstETHByStETH\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-07-10 05:39:35+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17661245                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x528f4267c0fdc07f8eecfbb6148e45dec24ebe77ffcea18bcb135b780036c6ff | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 109                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 1                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x7f39c581f595b53c5cb19bd0b3f8da6c935e2ca0                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_stETHAmount      | VARCHAR   | 2000000000000000000                                                |                                                                                                                        |

## 23. Table: WstETH\_call\_unwrap\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-07-18 04:11:35+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17717657                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x8f12876317b0c5c1f2d37e727a2d7205a90dee024f6440a05cd18a3df774b53e | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 47                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x7f39c581f595b53c5cb19bd0b3f8da6c935e2ca0                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_wstETHAmount     | VARCHAR   | 220773759764473378                                                 |                                                                                                                        |

## 24. Table: WstETH\_call\_wrap\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-08-02 02:32:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17824353                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x27d70bb6f3d7e004e0950957c6da8f5b740ff98535ebcee854a532811cc0d8eb | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 144                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x7f39c581f595b53c5cb19bd0b3f8da6c935e2ca0                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_stETHAmount      | VARCHAR   | 44000877009799731725                                               |                                                                                                                        |

## 25. Table: WstETH\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-17 19:04:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13044496                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd41092429604682a94803430c90fb14310f27983fad51298faa1c07be66f84e8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 198                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7f39c581f595b53c5cb19bd0b3f8da6c935e2ca0                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x055ef3015b9725a3264d154003bae428b820b0b0                         |                                                              |
| value             | VARCHAR   | 23492947684047481                                                  |                                                              |
