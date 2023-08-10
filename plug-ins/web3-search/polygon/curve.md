# curve

## 1. Table: CryptoRegistry\_event\_PoolAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-10 12:32:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 23556741                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x22d58085b1ac8b02489fbd5bc5ba36d0ead357a0bb9794b4c7af4957a988d39b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 96                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x47bb542b9de58b970ba50c9dae444ddb4c16751a                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0xb446bf7b8d6d4276d0c75ec0e3ee8dd7fe15783a                         |                                                              |

## 2. Table: CryptoRegistry\_event\_PoolRemoved\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| pool              | VARCHAR   |                                                              |             |

## 3. Table: CryptoSwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-11 13:06:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30603750                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc702c7187f581844016be5ae323ec1e3fd54bb543975f9cacc9aa02269cf0de6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 224                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb446bf7b8d6d4276d0c75ec0e3ee8dd7fe15783a                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x225fb4176f0e20cdb66b4a3df70ca3063281e855                         |                                                              |
| token\_amounts    | VARCHAR   | 0,75619231410546549558                                             |                                                              |
| fee               | VARCHAR   | 46603209074404336                                                  |                                                              |
| token\_supply     | VARCHAR   | 4126971210146270801589439                                          |                                                              |

## 4. Table: CryptoSwap\_event\_ClaimAdminFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-11 18:18:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 44959441                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x72fedccb37e8332b27d807cf0bf3b2660dd54ce25ba466fdcc88a85b0ddb914c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 263                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7bbc0e92505b485aeb3e82e828cb505daf1e50c6                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0x774d1dba98cfbd1f2bc3a1f59c494125e07c48f9                         |                                                              |
| tokens            | VARCHAR   | 87072134159836                                                     |                                                              |

## 5. Table: CryptoSwap\_event\_CommitNewParameters\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2021-11-13 21:24:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 21334435                                                           | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0xc4b6f37e2d4261393a1962322cc7d3e2102a0281e53fa91ac3579bd20d9065f2 | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 566                                                                | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0xb446bf7b8d6d4276d0c75ec0e3ee8dd7fe15783a                         | Address of the contract that produced the log                |
| deadline               | VARCHAR   | 1637097851                                                         |                                                              |
| admin\_fee             | VARCHAR   | 5000000000                                                         |                                                              |
| mid\_fee               | VARCHAR   | 5000000                                                            |                                                              |
| out\_fee               | VARCHAR   | 45000000                                                           |                                                              |
| fee\_gamma             | VARCHAR   | 5000000000000000                                                   |                                                              |
| allowed\_extra\_profit | VARCHAR   | 10000000000                                                        |                                                              |
| adjustment\_step       | VARCHAR   | 5500000000000                                                      |                                                              |
| ma\_half\_time         | VARCHAR   | 2000                                                               |                                                              |

## 6. Table: CryptoSwap\_event\_NewParameters\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2023-01-26 16:44:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 38555379                                                           | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0xb4f532d6c51a85527773ed95c62cda536b665884f016bb4b6e05013cfcb8f587 | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 211                                                                | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0x92215849c439e1f8612b6646060b4e3e5ef822cc                         | Address of the contract that produced the log                |
| admin\_fee             | VARCHAR   | 5000000000                                                         |                                                              |
| mid\_fee               | VARCHAR   | 3000000                                                            |                                                              |
| out\_fee               | VARCHAR   | 30000000                                                           |                                                              |
| fee\_gamma             | VARCHAR   | 500000000000000                                                    |                                                              |
| allowed\_extra\_profit | VARCHAR   | 200000000000                                                       |                                                              |
| adjustment\_step       | VARCHAR   | 500000000000000                                                    |                                                              |
| ma\_half\_time         | VARCHAR   | 600                                                                |                                                              |

## 7. Table: CryptoSwap\_event\_RampAgamma\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-12 17:32:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 19032318                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3bd27f379318218a1b9e2ba7ddf805053512e48569dfc01c66aac0a0286f3dbd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 437                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x92215849c439e1f8612b6646060b4e3e5ef822cc                         | Address of the contract that produced the log                |
| initial\_A        | VARCHAR   | 540000                                                             |                                                              |
| future\_A         | VARCHAR   | 5400000                                                            |                                                              |
| initial\_gamma    | VARCHAR   | 21000000000000                                                     |                                                              |
| future\_gamma     | VARCHAR   | 21000000000000                                                     |                                                              |
| initial\_time     | VARCHAR   | 1631467954                                                         |                                                              |
| future\_time      | VARCHAR   | 1632072456                                                         |                                                              |

## 8. Table: CryptoSwap\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-18 04:16:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45213355                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x001ea2947f1311f31ffcf8e054de4ec0f776b04910d077584c816130333df590 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 423                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x92215849c439e1f8612b6646060b4e3e5ef822cc                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x1d8b86e3d88cdb2d34688e87e72f388cb541b7c8                         |                                                              |
| token\_amount     | VARCHAR   | 420305987645406680                                                 |                                                              |
| coin\_index       | VARCHAR   | 0                                                                  |                                                              |
| coin\_amount      | VARCHAR   | 474907280991419064264                                              |                                                              |

## 9. Table: CryptoSwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-20 17:33:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45312100                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd5992d932710aba64674534a64a040f2fdbefa2145731b799f102cb9197efc89 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 321                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb446bf7b8d6d4276d0c75ec0e3ee8dd7fe15783a                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x225fb4176f0e20cdb66b4a3df70ca3063281e855                         |                                                              |
| token\_amounts    | VARCHAR   | 192978880,216957970890831071008                                    |                                                              |
| token\_supply     | VARCHAR   | 1734680042583039599681999                                          |                                                              |

## 10. Table: CryptoSwap\_event\_StopRampA\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-31 18:24:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 18597834                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x459b6edeae5cac49df6695c375d14d020b0534830e0b53986361cdbca2a8897d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 154                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x92215849c439e1f8612b6646060b4e3e5ef822cc                         | Address of the contract that produced the log                |
| current\_A        | VARCHAR   | 112126                                                             |                                                              |
| current\_gamma    | VARCHAR   | 279999999999999                                                    |                                                              |
| time              | VARCHAR   | 1630434240                                                         |                                                              |

## 11. Table: CryptoSwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-01 01:02:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 43388466                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x61d1b13cd8bcfaeb4ce08e7c432c24c06bb41d9124b6ae4bbe0ecad9bf6eaa83 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 202                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfb6fe7802ba9290ef8b00ca16af4bc26eb663a28                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xefa413de95fd661346c6de01342b4779df2dd517                         |                                                              |
| sold\_id          | VARCHAR   | 1                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 299960136934927290143                                              |                                                              |
| bought\_id        | VARCHAR   | 0                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 279677283802816809662                                              |                                                              |

## 12. Table: MainRegistry\_event\_PoolAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-02 09:16:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13991871                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdcb4f3f4287f48a9b42144965c538282b5231f7fb289774cab95c408e4650a88 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 65                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x094d12e5b541784701fd8d65f11fc0598fbc6332                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0x445fe580ef8d70ff569ab36e80c647af338db351                         |                                                              |
| rate\_method\_id  | VARCHAR   | 0x00000000                                                         |                                                              |

## 13. Table: MainRegistry\_event\_PoolRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-08 17:21:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 31665749                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xac65bb2c587298ea9821459543e567854b6466743f2230efe24b77b12f32857e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 381                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x094d12e5b541784701fd8d65f11fc0598fbc6332                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0x445fe580ef8d70ff569ab36e80c647af338db351                         |                                                              |

## 14. Table: PegSwap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| provider          | VARCHAR   |                                                              |             |
| token\_amounts    | VARCHAR   |                                                              |             |
| fees              | VARCHAR   |                                                              |             |
| invariant         | VARCHAR   |                                                              |             |
| token\_supply     | VARCHAR   |                                                              |             |

## 15. Table: PegSwap\_event\_CommitNewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-14 23:19:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 22530665                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0759892156c64c291d7c35e81a080987f348e11b8faf188c4ea0926ca17ee097 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 242                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc2d95eef97ec6c17551d45e77b590dc1f9117c67                         | Address of the contract that produced the log                |
| deadline          | VARCHAR   | 1639783176                                                         |                                                              |
| admin             | VARCHAR   | 0x774d1dba98cfbd1f2bc3a1f59c494125e07c48f9                         |                                                              |

## 16. Table: PegSwap\_event\_CommitNewFee\_history

| Column                  | Type      | Example                                                      | Description |
| ----------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp        | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number           | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash       | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index              | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address       | VARCHAR   | Address of the contract that produced the log                |             |
| deadline                | VARCHAR   |                                                              |             |
| fee                     | VARCHAR   |                                                              |             |
| admin\_fee              | VARCHAR   |                                                              |             |
| offpeg\_fee\_multiplier | VARCHAR   |                                                              |             |

## 17. Table: PegSwap\_event\_NewFee\_history

| Column                  | Type      | Example                                                      | Description |
| ----------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp        | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number           | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash       | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index              | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address       | VARCHAR   | Address of the contract that produced the log                |             |
| fee                     | VARCHAR   |                                                              |             |
| admin\_fee              | VARCHAR   |                                                              |             |
| offpeg\_fee\_multiplier | VARCHAR   |                                                              |             |

## 18. Table: PegSwap\_event\_RemoveLiquidityImbalance\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| provider          | VARCHAR   |                                                              |             |
| token\_amounts    | VARCHAR   |                                                              |             |
| fees              | VARCHAR   |                                                              |             |
| invariant         | VARCHAR   |                                                              |             |
| token\_supply     | VARCHAR   |                                                              |             |

## 19. Table: PegSwap\_event\_RemoveLiquidityOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-11 20:02:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 44962332                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4f5dd9b718f8a97e6c0d2f816ed55a61edf9baa61fb0ee7acc050ebf94907f51 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 659                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc2d95eef97ec6c17551d45e77b590dc1f9117c67                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x41abad0f397d7b5d2d2a6b52bacca53f06caa687                         |                                                              |
| token\_amount     | VARCHAR   | 198184920050971533                                                 |                                                              |
| coin\_amount      | VARCHAR   | 20099166                                                           |                                                              |

## 20. Table: PegSwap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| provider          | VARCHAR   |                                                              |             |
| token\_amounts    | VARCHAR   |                                                              |             |
| fees              | VARCHAR   |                                                              |             |
| token\_supply     | VARCHAR   |                                                              |             |

## 21. Table: PegSwap\_event\_TokenExchangeUnderlying\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-18 13:43:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 41673665                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x76ba452edb1859446bb87b063b8963dd9c18a88fe5638ad74737048a23fce65b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 444                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x447646e84498552e62ecf097cc305eabfff09308                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x5ab5c56b9db92ba45a0b46a207286cd83c15c939                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 597956792649803826652                                              |                                                              |
| bought\_id        | VARCHAR   | 2                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 595435299                                                          |                                                              |

## 22. Table: PegSwap\_event\_TokenExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-05 02:30:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 20994891                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1c33976d5fbe682835a0e6792bc2ddcd85c4f4ada79a8dc998adcaeba30f4f9e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 213                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc2d95eef97ec6c17551d45e77b590dc1f9117c67                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x3440e79458a109ae852b380b61b2fa6e5bd2f5b1                         |                                                              |
| sold\_id          | VARCHAR   | 0                                                                  |                                                              |
| tokens\_sold      | VARCHAR   | 39535230                                                           |                                                              |
| bought\_id        | VARCHAR   | 1                                                                  |                                                              |
| tokens\_bought    | VARCHAR   | 39605174                                                           |                                                              |
