# request

## 1. Table: RequestToken\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-07-08 13:21:47+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8110834                                                                        | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8bb4c78206cd8eb7ce235fd97b65b720cc1e5b0b6e2bfd7cb11eace461b3d50d             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                              | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8f8221afbb33998d8584a2b05749ba73c37a938a                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x0f01b5ea43719683c546868bfadeaccde14ab79e                                     |                                                              |
| spender           | VARCHAR   | 0x818e6fecd516ecc3849daf6845e3ec868087b755                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 2. Table: RequestToken\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-05-08 21:57:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5580103                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaad85da58a40e249114693f0cd29cc768942212650ddc3f1035b80b149bf59c6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 61                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8f8221afbb33998d8584a2b05749ba73c37a938a                         | Address of the contract that produced the log                |
| \_burner          | VARCHAR   | 0xfcb4393e7faef06fab01c00d67c1895545aff3b8                         |                                                              |
| \_value           | VARCHAR   | 766371793287214937                                                 |                                                              |

## 3. Table: RequestToken\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2017-10-07 15:47:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4345153                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0ce57bf9142799a03d46614696ab36b458a9683ab1257bf2e10ce7f6cd54f8ad | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 19                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8f8221afbb33998d8584a2b05749ba73c37a938a                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x97208bf5dc25e6fd4719cfc2a3c1d1a59a974c3b                         |                                                              |
| newOwner          | VARCHAR   | 0xdd76b55ee6dafe0c7c978bff69206d476a5b9ce7                         |                                                              |

## 4. Table: RequestToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-13 18:49:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17252935                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaf2f6ee096f41cca2d9fba7dbe4dfa20e505c25faa4ab2f3599a4f9cd39d71a6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 138                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8f8221afbb33998d8584a2b05749ba73c37a938a                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x21a31ee1afc51d94c2efccaa2092ad1028285549                         |                                                              |
| to                | VARCHAR   | 0x7dd10f505f59970fe068d357e0a69cd5267de2eb                         |                                                              |
| value             | VARCHAR   | 113949000000000000000000                                           |                                                              |
