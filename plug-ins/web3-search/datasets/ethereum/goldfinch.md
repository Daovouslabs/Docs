# goldfinch

## 1. Table: GoldfinchFactory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-17 01:03:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13819566                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x13c2288c4b0f1153f01c4e6b7155678f42be08f71130212e8ab05131bf46872e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 269                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd20508e1e971b80ee172c73517905bfffcbd87f9                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0x1d596d28a7923a22aa013b0e7082bba23daa656b                         |                                                              |
| borrower          | VARCHAR   | 0xcf595641c40008fdc97e5ccbce710ab4d31539a3                         |                                                              |

## 2. Table: SeniorPool\_event\_DepositMade\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| capitalProvider   | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |
| shares            | VARCHAR   |                                                              |             |

## 3. Table: SeniorPool\_event\_GoldfinchConfigUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| who               | VARCHAR   |                                                              |             |
| configAddress     | VARCHAR   |                                                              |             |

## 4. Table: SeniorPool\_event\_InterestCollected\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| payer             | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 5. Table: SeniorPool\_event\_InvestmentMadeInJunior\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-03 15:15:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13153512                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8a1c04842686ccb3f0f6d47dce95ea29d7d9e2bc6d8ebe31592200d798e5d421 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 50                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8481a6ebaf5c7dabc3f7e09e44a89531fd31f822                         | Address of the contract that produced the log                |
| tranchedPool      | VARCHAR   | 0xc13465ce9ae3aa184eb536f04fdc3f54d2def277                         |                                                              |
| amount            | VARCHAR   | 4875000000000                                                      |                                                              |

## 6. Table: SeniorPool\_event\_InvestmentMadeInSenior\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| tranchedPool      | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 7. Table: SeniorPool\_event\_Paused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |

## 8. Table: SeniorPool\_event\_PrincipalCollected\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| payer             | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 9. Table: SeniorPool\_event\_PrincipalWrittenDown\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| tranchedPool      | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 10. Table: SeniorPool\_event\_ReserveFundsCollected\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| user              | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 11. Table: SeniorPool\_event\_RoleGranted\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| role              | VARCHAR   |                                                              |             |
| account           | VARCHAR   |                                                              |             |
| sender            | VARCHAR   |                                                              |             |

## 12. Table: SeniorPool\_event\_RoleRevoked\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| role              | VARCHAR   |                                                              |             |
| account           | VARCHAR   |                                                              |             |
| sender            | VARCHAR   |                                                              |             |

## 13. Table: SeniorPool\_event\_Unpaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |

## 14. Table: SeniorPool\_event\_WithdrawalMade\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| capitalProvider   | VARCHAR   |                                                              |             |
| userAmount        | VARCHAR   |                                                              |             |
| reserveAmount     | VARCHAR   |                                                              |             |

## 15. Table: TranchedPool\_event\_DrawdownMade\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-11 21:42:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13597355                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x48df87a11bd2347d11e2bd47fbc1233614dbacbdee71708bf930d84dbd3e0005 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 157                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc9bdd0d3b80cc6efe79a82d850f44ec9b55387ae                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0xd750033cd9ab91ead99074f671bbcbce0ffd91a8                         |                                                              |
| amount            | VARCHAR   | 2142674000000                                                      |                                                              |

## 16. Table: TranchedPool\_event\_PaymentApplied\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-25 23:52:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17339536                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfc9eb88ac4e9bc44df5ef90119b709a740ddcdaa0d344520a811124c8c87d212 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 90                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xefeb69edf6b6999b0e3f2fa856a2acf3bdea4ab5                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0xcf595641c40008fdc97e5ccbce710ab4d31539a3                         |                                                              |
| pool              | VARCHAR   | 0xefeb69edf6b6999b0e3f2fa856a2acf3bdea4ab5                         |                                                              |
| interestAmount    | VARCHAR   | 22225725175                                                        |                                                              |
| principalAmount   | VARCHAR   | 4825                                                               |                                                              |
| remainingAmount   | VARCHAR   | 0                                                                  |                                                              |
| reserveAmount     | VARCHAR   | 2222572517                                                         |                                                              |

## 17. Table: TranchedPool\_event\_WithdrawalMade\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2023-06-25 18:53:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 17558400                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x2406d24362ce46b115855af87cdfea56bc36bff4aa1cfceb694502e2e5576903 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 308                                                                | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0xefeb69edf6b6999b0e3f2fa856a2acf3bdea4ab5                         | Address of the contract that produced the log                |
| owner              | VARCHAR   | 0xdcd7d160815a1c256ddc73b3faa89391114d8249                         |                                                              |
| tranche            | VARCHAR   | 2                                                                  |                                                              |
| tokenId            | VARCHAR   | 32                                                                 |                                                              |
| interestWithdrawn  | VARCHAR   | 462328749                                                          |                                                              |
| principalWithdrawn | VARCHAR   | 66                                                                 |                                                              |
