# aelf

## 1. Table: AElfToken\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-01 14:16:00+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13333961                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdbf505958d4f7227fb061aa4d876da24f7c21db4537b50c65fd55ffdab464465             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 506                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbf2179859fc6d5bee9bf9158632dc51678a4100e                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x5cb542832b6ac0a2b461d44a0780f8a8e99f2c2b                                     |                                                              |
| spender           | VARCHAR   | 0x3213b78de00cb85302ae5a5e05e80b24b39bd7dd                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 2. Table: AElfToken\_event\_ApproveMintTokens\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-01-30 03:18:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4997515                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9037bbb58dec7e8a9843061d31c3ebf0e4b9e9c1c0d7148a92d7e11bcd08361c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 58                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbf2179859fc6d5bee9bf9158632dc51678a4100e                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x7b35da02a8a9de700843d0671334e55ec6b2c15d                         |                                                              |
| \_amount          | VARCHAR   | 20000000000000000000000000                                         |                                                              |

## 3. Table: AElfToken\_event\_BurnTokens\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-12-09 15:04:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6855347                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x35e2c232d572d36addf44a4671f9d57041d7cf24e1b52d3fd0fdca8145e97343 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 20                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbf2179859fc6d5bee9bf9158632dc51678a4100e                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x680ac5ee6db009cb7f10d745ff8c45723463edcd                         |                                                              |
| \_amount          | VARCHAR   | 13534191232809720                                                  |                                                              |

## 4. Table: AElfToken\_event\_DisableSetTransferable\_history

| Column               | Type      | Example                                                      | Description |
| -------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp     | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number        | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash    | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index           | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address    | VARCHAR   | Address of the contract that produced the log                |             |
| \_address            | VARCHAR   |                                                              |             |
| \_canSetTransferable | VARCHAR   |                                                              |             |

## 5. Table: AElfToken\_event\_MintFinished\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_caller          | VARCHAR   |                                                              |             |

## 6. Table: AElfToken\_event\_MintTokens\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2017-12-22 06:39:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4775322                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2da08123e2e40acc2786a6c68aa9f370ac5585535765d706e1b5a079b7e06301 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 19                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbf2179859fc6d5bee9bf9158632dc51678a4100e                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x7b35da02a8a9de700843d0671334e55ec6b2c15d                         |                                                              |
| \_amount          | VARCHAR   | 3000000000000000000000000                                          |                                                              |

## 7. Table: AElfToken\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner     | VARCHAR   |                                                              |             |
| newOwner          | VARCHAR   |                                                              |             |

## 8. Table: AElfToken\_event\_SetAElfCommunityMultisig\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_old             | VARCHAR   |                                                              |             |
| \_new             | VARCHAR   |                                                              |             |

## 9. Table: AElfToken\_event\_SetAElfDevMultisig\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2017-12-19 17:56:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4761206                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdca9c9ffe54e694f449b5855cbd86f06e12228e7334512cc79aab6f0dfbf2703 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbf2179859fc6d5bee9bf9158632dc51678a4100e                         | Address of the contract that produced the log                |
| \_old             | VARCHAR   | 0x6d3e0b5abfc141caa674a3c11e1580e6fff2a0b9                         |                                                              |
| \_new             | VARCHAR   | 0x7c623bc289e59360865215a26718ba2834e9f28e                         |                                                              |

## 10. Table: AElfToken\_event\_SetDurationOfLock\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_caller          | VARCHAR   |                                                              |             |

## 11. Table: AElfToken\_event\_SetTransferable\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2017-12-19 15:24:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4760617                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9e952b1ea5948e08671da90ffac997a90e95faa81572f28668e4a6da99cb6209 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 12                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbf2179859fc6d5bee9bf9158632dc51678a4100e                         | Address of the contract that produced the log                |
| \_address         | VARCHAR   | 0x6d3e0b5abfc141caa674a3c11e1580e6fff2a0b9                         |                                                              |
| \_transferable    | VARCHAR   | true                                                               |                                                              |

## 12. Table: AElfToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-05-10 10:39:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5588835                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdd49bcd0909095eb6ddac78e67cbad9092cb238313decaad43eebf8657b87db2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbf2179859fc6d5bee9bf9158632dc51678a4100e                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x05d716498c99b4538dab308684eeeec67d43a6eb                         |                                                              |
| to                | VARCHAR   | 0x812449093690308e1efa26310ea1d76b3a947593                         |                                                              |
| value             | VARCHAR   | 284000000000000000000                                              |                                                              |

## 13. Table: AElfToken\_event\_WithdrawMintTokens\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_owner           | VARCHAR   |                                                              |             |
| \_amount          | VARCHAR   |                                                              |             |
