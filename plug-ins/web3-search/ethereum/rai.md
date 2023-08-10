# rai

## 1. Table: AccountingEngine\_event\_AddAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-03 15:07:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13153485                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8671da87496329767f7a3809aebf07ba59d2bde1f105a6e21960a4b97e20a020 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 154                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcee6aa1ab47d0fb0f24f51a3072ec16e20f90fce                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x7df2d51e69aa58b69c3df18d75b8e9acc3c1b04e                         |                                                              |

## 2. Table: AccountingEngine\_event\_AuctionDebt\_history

| Column             | Type      | Example                                                      | Description |
| ------------------ | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number      | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index         | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address  | VARCHAR   | Address of the contract that produced the log                |             |
| id                 | VARCHAR   |                                                              |             |
| totalOnAuctionDebt | VARCHAR   |                                                              |             |
| debtBalance        | VARCHAR   |                                                              |             |

## 3. Table: AccountingEngine\_event\_AuctionSurplus\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2023-06-06 22:44:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 17424441                                                           | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0xf5f547730efd427086a0417e93894f04b3996f9d7476e302ee16d8df8616cba8 | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 252                                                                | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0xcee6aa1ab47d0fb0f24f51a3072ec16e20f90fce                         | Address of the contract that produced the log                |
| id                     | VARCHAR   | 19                                                                 |                                                              |
| lastSurplusAuctionTime | VARCHAR   | 1686091463                                                         |                                                              |
| coinBalance            | VARCHAR   | 500009064974056632075366964204389102591139504191956                |                                                              |

## 4. Table: AccountingEngine\_event\_CancelAuctionedDebtWithSurplus\_history

| Column             | Type      | Example                                                      | Description |
| ------------------ | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number      | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index         | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address  | VARCHAR   | Address of the contract that produced the log                |             |
| rad                | VARCHAR   |                                                              |             |
| totalOnAuctionDebt | VARCHAR   |                                                              |             |
| coinBalance        | VARCHAR   |                                                              |             |
| debtBalance        | VARCHAR   |                                                              |             |

## 5. Table: AccountingEngine\_event\_DisableContract\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| disableTimestamp  | VARCHAR   |                                                              |             |
| disableCooldown   | VARCHAR   |                                                              |             |
| coinBalance       | VARCHAR   |                                                              |             |
| debtBalance       | VARCHAR   |                                                              |             |

## 6. Table: AccountingEngine\_event\_ModifyParameters\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-17 13:07:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14023209                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc2136b4dcf992b29cda57fb3abea0e8270af95f563bae981fa4acc72b57e1462 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 89                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcee6aa1ab47d0fb0f24f51a3072ec16e20f90fce                         | Address of the contract that produced the log                |
| parameter         | VARCHAR   | 0x737572706c757341756374696f6e486f75736500000000000000000000000000 |                                                              |
| data              | VARCHAR   | 0x4eefdae928ca97817302242a851f317be1b85c90                         |                                                              |

## 7. Table: AccountingEngine\_event\_PopDebtFromQueue\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-06 03:18:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12968945                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbfd25f7b62213f931f610a909a9d74187f59a3082c613f0e63fa17d389890a3e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 249                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcee6aa1ab47d0fb0f24f51a3072ec16e20f90fce                         | Address of the contract that produced the log                |
| timestamp         | VARCHAR   | 1628219895                                                         |                                                              |
| debtQueueBlock    | VARCHAR   | 714999777877263857440877609119735294630850660088                   |                                                              |
| totalQueuedDebt   | VARCHAR   | 0                                                                  |                                                              |

## 8. Table: AccountingEngine\_event\_PushDebtToQueue\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-22 10:00:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12087953                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc84bf207d6d66164dbd6fffb34064af042a9b91e13a196bd7c810e3f153134f6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 44                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcee6aa1ab47d0fb0f24f51a3072ec16e20f90fce                         | Address of the contract that produced the log                |
| timestamp         | VARCHAR   | 1616407200                                                         |                                                              |
| debtQueueBlock    | VARCHAR   | 2040000000000000000000595693274620755795645070848                  |                                                              |
| totalQueuedDebt   | VARCHAR   | 39751674357671518838909882682129601192777242975636                 |                                                              |

## 9. Table: AccountingEngine\_event\_RemoveAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-13 13:05:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11848437                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x94c0d3d6131fab1e3ea0365db1f637a955d6c930c053160654096796b134d721 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 128                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcee6aa1ab47d0fb0f24f51a3072ec16e20f90fce                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xf71774ee859d884ebb8c37cd94b2851cd2e68842                         |                                                              |

## 10. Table: AccountingEngine\_event\_SettleDebt\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-21 09:58:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12081461                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8bf951d0b965b76fc3f74a946c3a68c2007087bf680964f18dc1945e95e4797b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 145                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcee6aa1ab47d0fb0f24f51a3072ec16e20f90fce                         | Address of the contract that produced the log                |
| rad               | VARCHAR   | 841001799222198507266098272441341774789819721688                   |                                                              |
| coinBalance       | VARCHAR   | 206137112608444671025106123362832684472713431146024                |                                                              |
| debtBalance       | VARCHAR   | 37711674357671518838909286988854980436981597904788                 |                                                              |

## 11. Table: AccountingEngine\_event\_TransferExtraSurplus\_history

| Column                 | Type      | Example                                                      | Description |
| ---------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp       | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number          | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash      | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index             | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address      | VARCHAR   | Address of the contract that produced the log                |             |
| extraSurplusReceiver   | VARCHAR   |                                                              |             |
| lastSurplusAuctionTime | VARCHAR   |                                                              |             |
| coinBalance            | VARCHAR   |                                                              |             |

## 12. Table: AccountingEngine\_event\_TransferPostSettlementSurplus\_history

| Column                     | Type      | Example                                                      | Description |
| -------------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp           | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number              | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash          | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index                 | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address          | VARCHAR   | Address of the contract that produced the log                |             |
| postSettlementSurplusDrain | VARCHAR   |                                                              |             |
| coinBalance                | VARCHAR   |                                                              |             |
| debtBalance                | VARCHAR   |                                                              |             |

## 13. Table: BurningSurplusAuctionHouse\_event\_AddAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-13 13:05:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11848436                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x84aef101190bf10c01b71196bf7b6f938379dbe5a38bf88384e26bedbec61848 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 93                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeef4ea1a548417df1e7f0f6ab89494eed9e06b70                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x24acc85528e6dd5b9c297fb8821522d36b1ae09f                         |                                                              |

## 14. Table: BurningSurplusAuctionHouse\_event\_DisableContract\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 15. Table: BurningSurplusAuctionHouse\_event\_IncreaseBidSize\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| id                | VARCHAR   |                                                              |             |
| highBidder        | VARCHAR   |                                                              |             |
| amountToBuy       | VARCHAR   |                                                              |             |
| bid               | VARCHAR   |                                                              |             |
| bidExpiry         | VARCHAR   |                                                              |             |

## 16. Table: BurningSurplusAuctionHouse\_event\_ModifyParameters\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-13 14:50:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11848927                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc9d4b010c8655b078345e09c789075a941979515a9c104826dac7bbcd1ae56d1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeef4ea1a548417df1e7f0f6ab89494eed9e06b70                         | Address of the contract that produced the log                |
| parameter         | VARCHAR   | 0x626964496e637265617365000000000000000000000000000000000000000000 |                                                              |
| data              | VARCHAR   | 1030000000000000000                                                |                                                              |

## 17. Table: BurningSurplusAuctionHouse\_event\_RemoveAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-13 13:47:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11848619                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x28cfcd873a606b7741519682c71e594a805ac1a04c632fac9e58c2b2f22bd9ae | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 92                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeef4ea1a548417df1e7f0f6ab89494eed9e06b70                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x24acc85528e6dd5b9c297fb8821522d36b1ae09f                         |                                                              |

## 18. Table: BurningSurplusAuctionHouse\_event\_RestartAuction\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| id                | VARCHAR   |                                                              |             |
| auctionDeadline   | VARCHAR   |                                                              |             |

## 19. Table: BurningSurplusAuctionHouse\_event\_SettleAuction\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| id                | VARCHAR   |                                                              |             |

## 20. Table: BurningSurplusAuctionHouse\_event\_StartAuction\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| id                | VARCHAR   |                                                              |             |
| auctionsStarted   | VARCHAR   |                                                              |             |
| amountToSell      | VARCHAR   |                                                              |             |
| initialBid        | VARCHAR   |                                                              |             |
| auctionDeadline   | VARCHAR   |                                                              |             |

## 21. Table: BurningSurplusAuctionHouse\_event\_TerminateAuctionPrematurely\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| id                | VARCHAR   |                                                              |             |
| sender            | VARCHAR   |                                                              |             |
| highBidder        | VARCHAR   |                                                              |             |
| bidAmount         | VARCHAR   |                                                              |             |

## 22. Table: ChainlinkMedianETHUSD\_event\_AddAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-13 12:35:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11848320                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd6d4408cafa97a53cd939cc7dae1f6c40ee3ef4a2a7624bf21112d95d6363a3e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6a4b575ba61d2fb86ad0ff5e5be286960580e71a                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x7fafc11677649db6abfec127b4b776d585520ae1                         |                                                              |

## 23. Table: ChainlinkMedianETHUSD\_event\_FailRewardCaller\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| revertReason      | VARCHAR   |                                                              |             |
| feeReceiver       | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 24. Table: ChainlinkMedianETHUSD\_event\_ModifyParameters\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-13 12:35:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11848320                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd6d4408cafa97a53cd939cc7dae1f6c40ee3ef4a2a7624bf21112d95d6363a3e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 9                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6a4b575ba61d2fb86ad0ff5e5be286960580e71a                         | Address of the contract that produced the log                |
| parameter         | VARCHAR   | 0x6261736555706461746543616c6c657252657761726400000000000000000000 |                                                              |
| val               | VARCHAR   | 0                                                                  |                                                              |

## 25. Table: ChainlinkMedianETHUSD\_event\_RemoveAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-13 15:44:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11849181                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4cc2ae992ba4409493359c8e0d8d0de91f792ef87562f12b125a53d1d34b674b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 95                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6a4b575ba61d2fb86ad0ff5e5be286960580e71a                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x7fafc11677649db6abfec127b4b776d585520ae1                         |                                                              |

## 26. Table: ChainlinkMedianETHUSD\_event\_UpdateResult\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-26 04:49:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11930758                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbb04c85fb8bbedc199d03e47dadb56b417a27ccae8d59a4295dd7bdb197d5b4a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 187                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6a4b575ba61d2fb86ad0ff5e5be286960580e71a                         | Address of the contract that produced the log                |
| medianPrice       | VARCHAR   | 1513336353230000000000                                             |                                                              |
| lastUpdateTime    | VARCHAR   | 1614314974                                                         |                                                              |

## 27. Table: ChainlinkRelayer\_event\_AddAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-14 14:05:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12238668                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4660eb38fc18ea86d24e6771717927668fc923405e9549550521a978ffba6c5f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 290                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb825e25856bd98b3f2faf2aeb6cb8742b38c4025                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xa57a4e6170930ac547c147cdf26ae4682fa8262e                         |                                                              |

## 28. Table: ChainlinkRelayer\_event\_ModifyParameters\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-14 14:04:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12238662                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2699bfef538c31f33ca7f7cc320478945c0b52c96669d4e30f8eac49b7424817 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 210                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb825e25856bd98b3f2faf2aeb6cb8742b38c4025                         | Address of the contract that produced the log                |
| parameter         | VARCHAR   | 0x7374616c655468726573686f6c64000000000000000000000000000000000000 |                                                              |
| val               | VARCHAR   | 21600                                                              |                                                              |

## 29. Table: ChainlinkRelayer\_event\_RemoveAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-14 14:06:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12238674                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x09ded30f340cf3b5ddd501484512f8e01fbf8639c2f488b9262a2050c5171c9c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 197                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb825e25856bd98b3f2faf2aeb6cb8742b38c4025                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xfa5e4955a11902f849ecaddef355db69c2036de6                         |                                                              |

## 30. Table: DebtAuctionHouse\_event\_AddAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-13 13:12:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11848460                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x824b013305e9a42be2c6b9aeff40334af323b884e5af70e317cb3e0cf0a176f7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 65                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1896adbe708bf91158748b3f33738ba497a69e8f                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xa57a4e6170930ac547c147cdf26ae4682fa8262e                         |                                                              |

## 31. Table: DebtAuctionHouse\_event\_DecreaseSoldAmount\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| id                | VARCHAR   |                                                              |             |
| highBidder        | VARCHAR   |                                                              |             |
| amountToBuy       | VARCHAR   |                                                              |             |
| bid               | VARCHAR   |                                                              |             |
| bidExpiry         | VARCHAR   |                                                              |             |

## 32. Table: DebtAuctionHouse\_event\_DisableContract\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| sender            | VARCHAR   |                                                              |             |

## 33. Table: DebtAuctionHouse\_event\_ModifyParameters\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-13 13:05:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11848437                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x94c0d3d6131fab1e3ea0365db1f637a955d6c930c053160654096796b134d721 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 129                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1896adbe708bf91158748b3f33738ba497a69e8f                         | Address of the contract that produced the log                |
| parameter         | VARCHAR   | 0x6163636f756e74696e67456e67696e6500000000000000000000000000000000 |                                                              |
| data              | VARCHAR   | 0xcee6aa1ab47d0fb0f24f51a3072ec16e20f90fce                         |                                                              |

## 34. Table: DebtAuctionHouse\_event\_RemoveAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-13 13:47:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11848619                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x28cfcd873a606b7741519682c71e594a805ac1a04c632fac9e58c2b2f22bd9ae | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 93                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1896adbe708bf91158748b3f33738ba497a69e8f                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x24acc85528e6dd5b9c297fb8821522d36b1ae09f                         |                                                              |

## 35. Table: DebtAuctionHouse\_event\_RestartAuction\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| id                | VARCHAR   |                                                              |             |
| auctionDeadline   | VARCHAR   |                                                              |             |

## 36. Table: DebtAuctionHouse\_event\_SettleAuction\_history

| Column             | Type      | Example                                                      | Description |
| ------------------ | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number      | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index         | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address  | VARCHAR   | Address of the contract that produced the log                |             |
| id                 | VARCHAR   |                                                              |             |
| activeDebtAuctions | VARCHAR   |                                                              |             |

## 37. Table: DebtAuctionHouse\_event\_StartAuction\_history

| Column             | Type      | Example                                                      | Description |
| ------------------ | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number      | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index         | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address  | VARCHAR   | Address of the contract that produced the log                |             |
| id                 | VARCHAR   |                                                              |             |
| auctionsStarted    | VARCHAR   |                                                              |             |
| amountToSell       | VARCHAR   |                                                              |             |
| initialBid         | VARCHAR   |                                                              |             |
| incomeReceiver     | VARCHAR   |                                                              |             |
| auctionDeadline    | VARCHAR   |                                                              |             |
| activeDebtAuctions | VARCHAR   |                                                              |             |

## 38. Table: DebtAuctionHouse\_event\_TerminateAuctionPrematurely\_history

| Column             | Type      | Example                                                      | Description |
| ------------------ | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number      | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index         | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address  | VARCHAR   | Address of the contract that produced the log                |             |
| id                 | VARCHAR   |                                                              |             |
| sender             | VARCHAR   |                                                              |             |
| highBidder         | VARCHAR   |                                                              |             |
| bidAmount          | VARCHAR   |                                                              |             |
| activeDebtAuctions | VARCHAR   |                                                              |             |

## 39. Table: ESM\_event\_AddAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-17 13:07:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14223825                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdc9297d8a4ba23c32c31fbfbfc1677e4fb048bd0f4f76fa4f73d7305bbf568a2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 64                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa33ea2ac39902d4a206d6a1f8d38c7330c80f094                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x5e79c6db9a04039b593877b96f885374470efb90                         |                                                              |

## 40. Table: ESM\_event\_FailRecomputeThreshold\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| revertReason      | VARCHAR   |                                                              |             |

## 41. Table: ESM\_event\_ModifyParameters\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-01 01:38:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12545697                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0800f87656b87f51918e084a2d9526d60442bd51eef86c95fa2714705b9071d1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 153                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa33ea2ac39902d4a206d6a1f8d38c7330c80f094                         | Address of the contract that produced the log                |
| parameter         | VARCHAR   | 0x7468726573686f6c645365747465720000000000000000000000000000000000 |                                                              |
| account           | VARCHAR   | 0xfb13059b11ac351968045af7c83a9d5250e4a3e6                         |                                                              |

## 42. Table: ESM\_event\_RemoveAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-06 13:07:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14532534                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x550c0e5406853a8d03da40153e59f9f71a374e6e2b9bce1619fe0c9bc485da52 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 112                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa33ea2ac39902d4a206d6a1f8d38c7330c80f094                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xa57a4e6170930ac547c147cdf26ae4682fa8262e                         |                                                              |

## 43. Table: ESM\_event\_Shutdown\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 44. Table: ExternallyFundedOSM\_event\_AddAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-05 02:23:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12371493                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8a746f23f231afc2287ab0c9d600acf6a5f2c66ae6ec076aad33317848870576 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 215                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd4a0e3ec2a937e7cca4a192756a8439a8bf4ba91                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xa57a4e6170930ac547c147cdf26ae4682fa8262e                         |                                                              |

## 45. Table: ExternallyFundedOSM\_event\_ChangeDelay\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| delay             | VARCHAR   |                                                              |             |

## 46. Table: ExternallyFundedOSM\_event\_ChangePriceSource\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-12 14:27:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15732622                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x52d2d0a8b39e4e9cf18fd2e094f8de51f733bb5150129eb3af330c845b2670a6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 97                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd4a0e3ec2a937e7cca4a192756a8439a8bf4ba91                         | Address of the contract that produced the log                |
| priceSource       | VARCHAR   | 0xbf26309b0ba639abe651dd1e1042eb3c57c3e100                         |                                                              |

## 47. Table: ExternallyFundedOSM\_event\_FailRenumerateCaller\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-24 05:00:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14266771                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa271e9995ccf7de2a1779136f4ef1964ce223626363feaa2fbb0b1a518c33188 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd4a0e3ec2a937e7cca4a192756a8439a8bf4ba91                         | Address of the contract that produced the log                |
| wrapper           | VARCHAR   | 0x105b857583346e250fbd04a57ce0e491eb204ba3                         |                                                              |
| caller            | VARCHAR   | 0x3818018827864479854553033560779879232681                         |                                                              |

## 48. Table: ExternallyFundedOSM\_event\_ModifyParameters\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-05 02:23:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12371493                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8a746f23f231afc2287ab0c9d600acf6a5f2c66ae6ec076aad33317848870576 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 219                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd4a0e3ec2a937e7cca4a192756a8439a8bf4ba91                         | Address of the contract that produced the log                |
| parameter         | VARCHAR   | 0x66736d5772617070657200000000000000000000000000000000000000000000 |                                                              |
| val               | VARCHAR   | 0x105b857583346e250fbd04a57ce0e491eb204ba3                         |                                                              |

## 49. Table: ExternallyFundedOSM\_event\_RemoveAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-12 14:27:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15732622                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x52d2d0a8b39e4e9cf18fd2e094f8de51f733bb5150129eb3af330c845b2670a6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 98                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd4a0e3ec2a937e7cca4a192756a8439a8bf4ba91                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xa57a4e6170930ac547c147cdf26ae4682fa8262e                         |                                                              |

## 50. Table: ExternallyFundedOSM\_event\_RestartValue\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 51. Table: ExternallyFundedOSM\_event\_Start\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 52. Table: ExternallyFundedOSM\_event\_Stop\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 53. Table: ExternallyFundedOSM\_event\_UpdateResult\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-03 11:02:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17834044                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb24e60a915206a563c5a7df606628e94eeff9428878bd00a33387c45fddecdd1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 191                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd4a0e3ec2a937e7cca4a192756a8439a8bf4ba91                         | Address of the contract that produced the log                |
| newMedian         | VARCHAR   | 1832119586180000000000                                             |                                                              |
| lastUpdateTime    | VARCHAR   | 1691060400                                                         |                                                              |

## 54. Table: FixedDiscountCollateralAuctionHouse\_event\_AddAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-13 13:44:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11848606                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0095533aeb3241705cf48dded91cfebf4164d5fb5e99fa3917962a61995f0978 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 15                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6d2a73e16c255c1931730b776d96aaff1909322e                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xa57a4e6170930ac547c147cdf26ae4682fa8262e                         |                                                              |

## 55. Table: FixedDiscountCollateralAuctionHouse\_event\_BuyCollateral\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-18 21:00:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12064998                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0fc900d57d6f5f7dca762df33386f5d2071be753dac084d8784619adbf119dd0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 23                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6d2a73e16c255c1931730b776d96aaff1909322e                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 103                                                                |                                                              |
| wad               | VARCHAR   | 12550654447963140377505                                            |                                                              |
| boughtCollateral  | VARCHAR   | 24449650603235593009                                               |                                                              |

## 56. Table: FixedDiscountCollateralAuctionHouse\_event\_ModifyParameters\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-07 15:22:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12387919                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x834a6e7ee870121bbb7387273f64835dc8d5e3dc646d6c5424c58d1f19d8854f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 115                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6d2a73e16c255c1931730b776d96aaff1909322e                         | Address of the contract that produced the log                |
| parameter         | VARCHAR   | 0x636f6c6c61746572616c46534d00000000000000000000000000000000000000 |                                                              |
| data              | VARCHAR   | 0x105b857583346e250fbd04a57ce0e491eb204ba3                         |                                                              |

## 57. Table: FixedDiscountCollateralAuctionHouse\_event\_RemoveAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-27 13:08:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12516543                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa51285033700d82bae7050f3d08ea592dd88653058bf139af05f19f2e3734798 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 324                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6d2a73e16c255c1931730b776d96aaff1909322e                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x6368a4ba80fc780a9a0fea547239c4635b97fd70                         |                                                              |

## 58. Table: FixedDiscountCollateralAuctionHouse\_event\_SettleAuction\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2021-02-23 11:19:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 11912965                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0xb6e155b86c6cb4259c72416ac21bfa69681008238a7f8ede639e7e988791ca8f | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 67                                                                 | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x6d2a73e16c255c1931730b776d96aaff1909322e                         | Address of the contract that produced the log                |
| id                 | VARCHAR   | 50                                                                 |                                                              |
| leftoverCollateral | VARCHAR   | 1792440418943964576                                                |                                                              |

## 59. Table: FixedDiscountCollateralAuctionHouse\_event\_StartAuction\_history

| Column                    | Type      | Example                                                            | Description                                                  |
| ------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp          | TIMESTAMP | 2021-05-23 17:08:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number             | INTEGER   | 12491848                                                           | The block number where this event was emitted                |
| transaction\_hash         | VARCHAR   | 0x71dc46051d7a5b2700299065e027128672e3a0d6a838bb3c047c14395388e04f | Hash of the transactions in which this event was emitted     |
| log\_index                | INTEGER   | 20                                                                 | Integer of the log index position in the block of this event |
| contract\_address         | VARCHAR   | 0x6d2a73e16c255c1931730b776d96aaff1909322e                         | Address of the contract that produced the log                |
| id                        | VARCHAR   | 142                                                                |                                                              |
| auctionsStarted           | VARCHAR   | 142                                                                |                                                              |
| amountToSell              | VARCHAR   | 4260000000000000000                                                |                                                              |
| initialBid                | VARCHAR   | 0                                                                  |                                                              |
| amountToRaise             | VARCHAR   | 2093032346025047971634099202601610951743199298600                  |                                                              |
| forgoneCollateralReceiver | VARCHAR   | 0x3794c06e5a77e48dc80a2da458d57ae814cb515b                         |                                                              |
| auctionIncomeRecipient    | VARCHAR   | 0xcee6aa1ab47d0fb0f24f51a3072ec16e20f90fce                         |                                                              |
| auctionDeadline           | VARCHAR   | 281474976710655                                                    |                                                              |

## 60. Table: FixedDiscountCollateralAuctionHouse\_event\_TerminateAuctionPrematurely\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| id                | VARCHAR   |                                                              |             |
| sender            | VARCHAR   |                                                              |             |
| collateralAmount  | VARCHAR   |                                                              |             |

## 61. Table: GebSafeManager\_event\_AllowHandler\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| sender            | VARCHAR   |                                                              |             |
| usr               | VARCHAR   |                                                              |             |
| ok                | VARCHAR   |                                                              |             |

## 62. Table: GebSafeManager\_event\_AllowSAFE\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-18 01:39:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12455458                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x741504f445619d46a0e081253c3a28aa8f2c0f51e6921852c48e8526e38430ee | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 255                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xefe0b4ca532769a3ae758fd82e1426a03a94f185                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x1c3132aeb09f5dd5e1d8283bd4f0363e7ea81c95                         |                                                              |
| safe              | VARCHAR   | 307                                                                |                                                              |
| usr               | VARCHAR   | 0xf91f8844258d3246be5daa201b52b51fc7fccfd7                         |                                                              |
| ok                | VARCHAR   | 1                                                                  |                                                              |

## 63. Table: GebSafeManager\_event\_EnterSystem\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| sender            | VARCHAR   |                                                              |             |
| src               | VARCHAR   |                                                              |             |
| safe              | VARCHAR   |                                                              |             |

## 64. Table: GebSafeManager\_event\_ModifySAFECollateralization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-19 14:29:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13056246                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4ed150785fad412482c5a5b4cc1cda759ab254b62c4cb8e6ecc235ff973bc70c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 545                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xefe0b4ca532769a3ae758fd82e1426a03a94f185                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x10b412ec9601a2d023e293a887a9de4dd169d722                         |                                                              |
| safe              | VARCHAR   | 1568                                                               |                                                              |
| deltaCollateral   | VARCHAR   | -40000000000000000000                                              |                                                              |
| deltaDebt         | VARCHAR   | -8145567667922073300914                                            |                                                              |

## 65. Table: GebSafeManager\_event\_MoveSAFE\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| sender            | VARCHAR   |                                                              |             |
| safeSrc           | VARCHAR   |                                                              |             |
| safeDst           | VARCHAR   |                                                              |             |

## 66. Table: GebSafeManager\_event\_OpenSAFE\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-06 16:22:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16348905                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3e8ea64598e349f9209273ef5bb1618b524e05c334254d4e965b9b7a4f287ecb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 258                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xefe0b4ca532769a3ae758fd82e1426a03a94f185                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x5767af7089799c7bb047c411a4f265b4ffeaac07                         |                                                              |
| own               | VARCHAR   | 0x5767af7089799c7bb047c411a4f265b4ffeaac07                         |                                                              |
| safe              | VARCHAR   | 2405                                                               |                                                              |

## 67. Table: GebSafeManager\_event\_ProtectSAFE\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-12 03:04:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12809947                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0a9fc5e4f88f0342b8457bc707f371619735e677e3e970ce1e8351678dcdf644 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 315                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xefe0b4ca532769a3ae758fd82e1426a03a94f185                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xcebdb3bcee6b1e52136418e2c6ba82a201be3664                         |                                                              |
| safe              | VARCHAR   | 2067                                                               |                                                              |
| liquidationEngine | VARCHAR   | 0x27efc6ffe79692e0521e7e27657cf228240a06c2                         |                                                              |
| saviour           | VARCHAR   | 0xa9402de5ce3f1e03be28871b914f77a4dd5e4364                         |                                                              |

## 68. Table: GebSafeManager\_event\_QuitSystem\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| sender            | VARCHAR   |                                                              |             |
| safe              | VARCHAR   |                                                              |             |
| dst               | VARCHAR   |                                                              |             |

## 69. Table: GebSafeManager\_event\_TransferCollateral\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| sender            | VARCHAR   |                                                              |             |
| collateralType    | VARCHAR   |                                                              |             |
| safe              | VARCHAR   |                                                              |             |
| dst               | VARCHAR   |                                                              |             |
| wad               | VARCHAR   |                                                              |             |

## 70. Table: GebSafeManager\_event\_TransferInternalCoins\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-10 09:14:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13390060                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc39cbccdc0aa76010933428fba082ffb40a6a4377f6bfcdf97eb46a7b922c81c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 503                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xefe0b4ca532769a3ae758fd82e1426a03a94f185                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x0662fd47894a610e82a194236d2056e3abcc9851                         |                                                              |
| safe              | VARCHAR   | 2185                                                               |                                                              |
| dst               | VARCHAR   | 0x0662fd47894a610e82a194236d2056e3abcc9851                         |                                                              |
| rad               | VARCHAR   | 16666000000000000000000000000000000000000000000000                 |                                                              |

## 71. Table: GebSafeManager\_event\_TransferSAFEOwnership\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-18 15:53:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14030430                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc250c6f86a4b0d8b03e0b69d19521ad4793a906b177b08548079a63d18a3c329 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 165                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xefe0b4ca532769a3ae758fd82e1426a03a94f185                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xfd36d71a2774ca525de18a59687c6b73d43e3820                         |                                                              |
| safe              | VARCHAR   | 1817                                                               |                                                              |
| dst               | VARCHAR   | 0xf6297dbcb96fa385b53247d8c7f78933b496b7cc                         |                                                              |

## 72. Table: GlobalSettlement\_event\_AddAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-24 18:25:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12498624                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x26b051ab0960521e7b4afc8b5ec51f0dc6610654e0b3b332d9788ac0132dfaaa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 310                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xee4cf96e5359d9619197fd82b6ef2a9eae7b91e1                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x3e0139ce3533a42a7d342841aee69ab2bfee1d51                         |                                                              |

## 73. Table: GlobalSettlement\_event\_CalculateCashPrice\_history

| Column              | Type      | Example                                                      | Description |
| ------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp    | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number       | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash   | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index          | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address   | VARCHAR   | Address of the contract that produced the log                |             |
| collateralType      | VARCHAR   |                                                              |             |
| collateralCashPrice | VARCHAR   |                                                              |             |

## 74. Table: GlobalSettlement\_event\_FastTrackAuction\_history

| Column              | Type      | Example                                                      | Description |
| ------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp    | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number       | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash   | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index          | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address   | VARCHAR   | Address of the contract that produced the log                |             |
| collateralType      | VARCHAR   |                                                              |             |
| auctionId           | VARCHAR   |                                                              |             |
| collateralTotalDebt | VARCHAR   |                                                              |             |

## 75. Table: GlobalSettlement\_event\_FreeCollateral\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| collateralType    | VARCHAR   |                                                              |             |
| sender            | VARCHAR   |                                                              |             |
| collateralAmount  | VARCHAR   |                                                              |             |

## 76. Table: GlobalSettlement\_event\_FreezeCollateralType\_history

| Column                      | Type      | Example                                                      | Description |
| --------------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp            | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number               | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash           | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index                  | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address           | VARCHAR   | Address of the contract that produced the log                |             |
| collateralType              | VARCHAR   |                                                              |             |
| finalCoinPerCollateralPrice | VARCHAR   |                                                              |             |

## 77. Table: GlobalSettlement\_event\_ModifyParameters\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-19 21:07:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14992864                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x19e34c68a40ea3c141be7f971aa3e9c1e208152352711deb5d125b9f462e971f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 192                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xee4cf96e5359d9619197fd82b6ef2a9eae7b91e1                         | Address of the contract that produced the log                |
| parameter         | VARCHAR   | 0x6c69717569646174696f6e456e67696e65000000000000000000000000000000 |                                                              |
| data              | VARCHAR   | 0x4ffbaa89d648079faafc7852de49ea1dc92f9976                         |                                                              |

## 78. Table: GlobalSettlement\_event\_PrepareCoinsForRedeeming\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| sender            | VARCHAR   |                                                              |             |
| coinBag           | VARCHAR   |                                                              |             |

## 79. Table: GlobalSettlement\_event\_ProcessSAFE\_history

| Column              | Type      | Example                                                      | Description |
| ------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp    | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number       | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash   | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index          | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address   | VARCHAR   | Address of the contract that produced the log                |             |
| collateralType      | VARCHAR   |                                                              |             |
| safe                | VARCHAR   |                                                              |             |
| collateralShortfall | VARCHAR   |                                                              |             |

## 80. Table: GlobalSettlement\_event\_RedeemCollateral\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| collateralType    | VARCHAR   |                                                              |             |
| sender            | VARCHAR   |                                                              |             |
| coinsAmount       | VARCHAR   |                                                              |             |
| collateralAmount  | VARCHAR   |                                                              |             |

## 81. Table: GlobalSettlement\_event\_RemoveAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-24 20:24:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12499184                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xeb684ee44b776d084af9c5f309aea96818e0c1dcf2e9e572ef45dcaf3c51aff5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 59                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xee4cf96e5359d9619197fd82b6ef2a9eae7b91e1                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x3e0139ce3533a42a7d342841aee69ab2bfee1d51                         |                                                              |

## 82. Table: GlobalSettlement\_event\_SetOutstandingCoinSupply\_history

| Column                | Type      | Example                                                      | Description |
| --------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp      | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number         | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash     | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index            | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address     | VARCHAR   | Address of the contract that produced the log                |             |
| outstandingCoinSupply | VARCHAR   |                                                              |             |

## 83. Table: GlobalSettlement\_event\_ShutdownSystem\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 84. Table: LiquidationEngine\_event\_AddAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-13 13:12:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11848460                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x824b013305e9a42be2c6b9aeff40334af323b884e5af70e317cb3e0cf0a176f7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 60                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x27efc6ffe79692e0521e7e27657cf228240a06c2                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xa57a4e6170930ac547c147cdf26ae4682fa8262e                         |                                                              |

## 85. Table: LiquidationEngine\_event\_ConnectSAFESaviour\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-20 13:09:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12471490                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4824b11286fae393b40c75b3d4c4481183e1646a6d41ed619ea7fdec31b61721 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 219                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x27efc6ffe79692e0521e7e27657cf228240a06c2                         | Address of the contract that produced the log                |
| saviour           | VARCHAR   | 0xa9402de5ce3f1e03be28871b914f77a4dd5e4364                         |                                                              |

## 86. Table: LiquidationEngine\_event\_DisableContract\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 87. Table: LiquidationEngine\_event\_DisconnectSAFESaviour\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| saviour           | VARCHAR   |                                                              |             |

## 88. Table: LiquidationEngine\_event\_FailedSAFESave\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-18 22:07:39+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12660979                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x45ba5f7dc9d416839158b157732f93881f9d5359f74fc7da7bbb963997fc22c0                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 117                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x27efc6ffe79692e0521e7e27657cf228240a06c2                                                           | Address of the contract that produced the log                |
| failReason        | VARCHAR   | 0x08c379a0000000000000000000000000000000000000000000000000000000000000002000000000000000000000000000 |                                                              |

## 89. Table: LiquidationEngine\_event\_Liquidate\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2022-01-06 16:00:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 13952829                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x08eec92e2b49f1be415570744c0a98a1dc59802476eac0afbff95561bb67bea4 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 66                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x27efc6ffe79692e0521e7e27657cf228240a06c2                         | Address of the contract that produced the log                |
| collateralType       | VARCHAR   | 0x4554482d41000000000000000000000000000000000000000000000000000000 |                                                              |
| safe                 | VARCHAR   | 0xf32725a3036be85d8618c7265c182bcadb06a488                         |                                                              |
| collateralAmount     | VARCHAR   | 60000000000000000000                                               |                                                              |
| debtAmount           | VARCHAR   | 49682202617800610938570                                            |                                                              |
| amountToRaise        | VARCHAR   | 49993728857245980128344181717059300649330519092340                 |                                                              |
| collateralAuctioneer | VARCHAR   | 0x9fc9ae5c87fd07368e87d1ea0970a6fc1e6dd6cb                         |                                                              |
| auctionId            | VARCHAR   | 37                                                                 |                                                              |

## 90. Table: LiquidationEngine\_event\_ModifyParameters\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-22 14:40:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12684600                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb9572618fa973868c5b7aab64236c0a36d68b26d7172c1fdd327d4f68f006b94 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 271                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x27efc6ffe79692e0521e7e27657cf228240a06c2                         | Address of the contract that produced the log                |
| collateralType    | VARCHAR   | 0x4554482d41000000000000000000000000000000000000000000000000000000 |                                                              |
| parameter         | VARCHAR   | 0x636f6c6c61746572616c41756374696f6e486f75736500000000000000000000 |                                                              |
| data              | VARCHAR   | 0x9fc9ae5c87fd07368e87d1ea0970a6fc1e6dd6cb                         |                                                              |

## 91. Table: LiquidationEngine\_event\_ProtectSAFE\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-12 02:21:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13208216                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbe2b487c69e73c39c10a61e903b59d03017a76e6e354e6444eba04292a3768a1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 381                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x27efc6ffe79692e0521e7e27657cf228240a06c2                         | Address of the contract that produced the log                |
| collateralType    | VARCHAR   | 0x4554482d41000000000000000000000000000000000000000000000000000000 |                                                              |
| safe              | VARCHAR   | 0x06b5db60cb55d25805e47afe685dbb6bf04bd87d                         |                                                              |
| saviour           | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 92. Table: LiquidationEngine\_event\_RemoveAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-26 14:26:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12510458                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1b30f8ae870311d9a1a122b0285fac333e6a3cdc7064e4deadf52f0cdf95741e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 105                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x27efc6ffe79692e0521e7e27657cf228240a06c2                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x6368a4ba80fc780a9a0fea547239c4635b97fd70                         |                                                              |

## 93. Table: LiquidationEngine\_event\_SaveSAFE\_history

| Column                      | Type      | Example                                                            | Description                                                  |
| --------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp            | TIMESTAMP | 2021-07-13 22:01:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number               | INTEGER   | 12821335                                                           | The block number where this event was emitted                |
| transaction\_hash           | VARCHAR   | 0x70be04b8ab69be8c2d51851b07b4e7dda30a99886c774eac21788150f9d31aad | Hash of the transactions in which this event was emitted     |
| log\_index                  | INTEGER   | 42                                                                 | Integer of the log index position in the block of this event |
| contract\_address           | VARCHAR   | 0x27efc6ffe79692e0521e7e27657cf228240a06c2                         | Address of the contract that produced the log                |
| collateralType              | VARCHAR   | 0x4554482d41000000000000000000000000000000000000000000000000000000 |                                                              |
| safe                        | VARCHAR   | 0x7a9cbccca7e6d888f42098c7f043666c5288ed51                         |                                                              |
| collateralAddedOrDebtRepaid | VARCHAR   | 160509487678819707370                                              |                                                              |

## 94. Table: LiquidationEngine\_event\_UpdateCurrentOnAuctionSystemCoins\_history

| Column                      | Type      | Example                                                            | Description                                                  |
| --------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp            | TIMESTAMP | 2021-03-09 09:56:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number               | INTEGER   | 12003646                                                           | The block number where this event was emitted                |
| transaction\_hash           | VARCHAR   | 0xb2bf386440487346e82f9be67f0fa864c38581148bf167b1dbdb4b5e01c5e031 | Hash of the transactions in which this event was emitted     |
| log\_index                  | INTEGER   | 43                                                                 | Integer of the log index position in the block of this event |
| contract\_address           | VARCHAR   | 0x27efc6ffe79692e0521e7e27657cf228240a06c2                         | Address of the contract that produced the log                |
| currentOnAuctionSystemCoins | VARCHAR   | 0                                                                  |                                                              |

## 95. Table: OSM\_event\_AddAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-13 12:46:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11848351                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5202d0f160d349164d6e3257fbf0b62244fbe921e0ec6766ab3081962128099f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 20                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe6f5377de93a361cd5531bdfbdf0f4b522e16b2b                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x7fafc11677649db6abfec127b4b776d585520ae1                         |                                                              |

## 96. Table: OSM\_event\_ChangeDelay\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-13 12:46:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11848354                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4804dbf44190fb1fe9dc6115c898eae07b1bfed3caf442f332a74ba04451b760 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe6f5377de93a361cd5531bdfbdf0f4b522e16b2b                         | Address of the contract that produced the log                |
| delay             | VARCHAR   | 3600                                                               |                                                              |

## 97. Table: OSM\_event\_ChangePriceSource\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-13 12:46:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11848351                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5202d0f160d349164d6e3257fbf0b62244fbe921e0ec6766ab3081962128099f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe6f5377de93a361cd5531bdfbdf0f4b522e16b2b                         | Address of the contract that produced the log                |
| priceSource       | VARCHAR   | 0x6a4b575ba61d2fb86ad0ff5e5be286960580e71a                         |                                                              |

## 98. Table: OSM\_event\_RemoveAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-13 15:42:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11849174                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfb24c6084d90c0838d10d1d5dac9f591aacedf7fb480f6df7b2dbb8ae22d2229 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 64                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe6f5377de93a361cd5531bdfbdf0f4b522e16b2b                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x7fafc11677649db6abfec127b4b776d585520ae1                         |                                                              |

## 99. Table: OSM\_event\_RestartValue\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 100. Table: OSM\_event\_Start\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 101. Table: OSM\_event\_Stop\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 102. Table: OSM\_event\_UpdateResult\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-22 23:09:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12091537                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe85375a425ca305a99700c4fd86e8a0428daeeecdbe3f80ad8dba81874edf9a5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 162                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe6f5377de93a361cd5531bdfbdf0f4b522e16b2b                         | Address of the contract that produced the log                |
| newMedian         | VARCHAR   | 1691490656540000000000                                             |                                                              |
| lastUpdateTime    | VARCHAR   | 1616454000                                                         |                                                              |

## 103. Table: OracleRelayer\_event\_AddAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-26 14:26:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12510458                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1b30f8ae870311d9a1a122b0285fac333e6a3cdc7064e4deadf52f0cdf95741e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 102                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4ed9c0dca0479bc64d8f4eb3007126d5791f7851                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xee4cf96e5359d9619197fd82b6ef2a9eae7b91e1                         |                                                              |

## 104. Table: OracleRelayer\_event\_DisableContract\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 105. Table: OracleRelayer\_event\_ModifyParameters\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-19 13:22:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13055944                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x75d0f0b6f3c9a174bf8814d2b97eec7bf6497cd70e82ca55151940cd5731e5f2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 549                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4ed9c0dca0479bc64d8f4eb3007126d5791f7851                         | Address of the contract that produced the log                |
| collateralType    | VARCHAR   | 0x4554482d41000000000000000000000000000000000000000000000000000000 |                                                              |
| parameter         | VARCHAR   | 0x73616665747943526174696f0000000000000000000000000000000000000000 |                                                              |
| data              | VARCHAR   | 1400000000000000000000000000                                       |                                                              |

## 106. Table: OracleRelayer\_event\_RemoveAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-26 14:26:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12510458                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1b30f8ae870311d9a1a122b0285fac333e6a3cdc7064e4deadf52f0cdf95741e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 107                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4ed9c0dca0479bc64d8f4eb3007126d5791f7851                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x6368a4ba80fc780a9a0fea547239c4635b97fd70                         |                                                              |

## 107. Table: OracleRelayer\_event\_UpdateCollateralPrice\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-03 02:07:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17831388                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa7f3bde824af5082ae7eeccbc0f144b88b5f75e6e9b955eb0ae8876c70ffa140 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 187                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4ed9c0dca0479bc64d8f4eb3007126d5791f7851                         | Address of the contract that produced the log                |
| collateralType    | VARCHAR   | 0x4554482d41000000000000000000000000000000000000000000000000000000 |                                                              |
| priceFeedValue    | VARCHAR   | 1829995170000000000000                                             |                                                              |
| safetyPrice       | VARCHAR   | 493106905567948136634832440977                                     |                                                              |
| liquidationPrice  | VARCHAR   | 493106905567948136634832440977                                     |                                                              |

## 108. Table: OracleRelayer\_event\_UpdateRedemptionPrice\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-06 23:27:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17859188                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x82f0485a99f0b4624f84fd6f2c00242c69fb047fa7c92564e249d1db53c15ea4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 36                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4ed9c0dca0479bc64d8f4eb3007126d5791f7851                         | Address of the contract that produced the log                |
| redemptionPrice   | VARCHAR   | 2748857127646262032018965944                                       |                                                              |

## 109. Table: SAFEEngine\_event\_AddAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-26 14:26:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12510458                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1b30f8ae870311d9a1a122b0285fac333e6a3cdc7064e4deadf52f0cdf95741e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 99                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcc88a9d330da1133df3a7bd823b95e52511a6962                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xee4cf96e5359d9619197fd82b6ef2a9eae7b91e1                         |                                                              |

## 110. Table: SAFEEngine\_event\_ApproveSAFEModification\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-10 22:38:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15720738                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xefe1f55fb8cf05a66b398674a5cfcf20e2850cabc23af6a95ca85ea2afe5ddbe | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 349                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcc88a9d330da1133df3a7bd823b95e52511a6962                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x3d60490949f537fd578286a8549adeccf1fa300a                         |                                                              |
| account           | VARCHAR   | 0x0a5653cca4db1b6e265f47caf6969e64f1cfdc45                         |                                                              |

## 111. Table: SAFEEngine\_event\_ConfiscateSAFECollateralAndDebt\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2021-05-16 18:00:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 12446976                                                           | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0xdebd7a70e6845ef16d984a588305305d1afb8ce8bd5993c331461d3e22a56bb1 | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 20                                                                 | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0xcc88a9d330da1133df3a7bd823b95e52511a6962                         | Address of the contract that produced the log                |
| collateralType         | VARCHAR   | 0x4554482d41000000000000000000000000000000000000000000000000000000 |                                                              |
| safe                   | VARCHAR   | 0x4f84045a6e74a57ba5444b0544cde748dc9304b7                         |                                                              |
| collateralCounterparty | VARCHAR   | 0x27efc6ffe79692e0521e7e27657cf228240a06c2                         |                                                              |
| debtCounterparty       | VARCHAR   | 0xcee6aa1ab47d0fb0f24f51a3072ec16e20f90fce                         |                                                              |
| deltaCollateral        | VARCHAR   | -1200000000000000000                                               |                                                              |
| deltaDebt              | VARCHAR   | -995036888634421942393                                             |                                                              |
| globalUnbackedDebt     | VARCHAR   | 2424333784346133136296825461314847078166864690766                  |                                                              |

## 112. Table: SAFEEngine\_event\_CreateUnbackedDebt\_history

| Column             | Type      | Example                                                      | Description |
| ------------------ | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number      | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index         | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address  | VARCHAR   | Address of the contract that produced the log                |             |
| debtDestination    | VARCHAR   |                                                              |             |
| coinDestination    | VARCHAR   |                                                              |             |
| rad                | VARCHAR   |                                                              |             |
| debtDstBalance     | VARCHAR   |                                                              |             |
| coinDstBalance     | VARCHAR   |                                                              |             |
| globalUnbackedDebt | VARCHAR   |                                                              |             |
| globalDebt         | VARCHAR   |                                                              |             |

## 113. Table: SAFEEngine\_event\_DenySAFEModification\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-06 10:10:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14722925                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xabe603cdef44db239903e2ce6deaad0508c65bc0afba609aafc8c4dc1fc20080 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 26                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcc88a9d330da1133df3a7bd823b95e52511a6962                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xbd3f90047b14e4f392d6877276d52d0ac59f4cf8                         |                                                              |
| account           | VARCHAR   | 0x138c3d13b633b5a5cb5db5faf27429eeed78b338                         |                                                              |

## 114. Table: SAFEEngine\_event\_DisableContract\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 115. Table: SAFEEngine\_event\_InitializeCollateralType\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-13 13:39:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11848573                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc7935c32b4b3602f0761587fe1b9011b08a9e163e61fe9064ecfe02b2c8bfbe3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 105                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcc88a9d330da1133df3a7bd823b95e52511a6962                         | Address of the contract that produced the log                |
| collateralType    | VARCHAR   | 0x4554482d41000000000000000000000000000000000000000000000000000000 |                                                              |

## 116. Table: SAFEEngine\_event\_ModifyCollateralBalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-11 16:04:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17671444                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x04699c69b78bb1c2f5f80ba197a6920ae228191bd5c44c6e39c1bd5c27836c78 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 394                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcc88a9d330da1133df3a7bd823b95e52511a6962                         | Address of the contract that produced the log                |
| collateralType    | VARCHAR   | 0x4554482d41000000000000000000000000000000000000000000000000000000 |                                                              |
| account           | VARCHAR   | 0x7f2528313483f6293e068a164d6e49e1e2ca4296                         |                                                              |
| wad               | VARCHAR   | -6500000000000000000                                               |                                                              |

## 117. Table: SAFEEngine\_event\_ModifyParameters\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-05 10:57:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13556164                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xda89e17aee9aa1b655656694d2c1fbb4101b6abec22b8caf686319e468ff063e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 108                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcc88a9d330da1133df3a7bd823b95e52511a6962                         | Address of the contract that produced the log                |
| collateralType    | VARCHAR   | 0x4554482d41000000000000000000000000000000000000000000000000000000 |                                                              |
| parameter         | VARCHAR   | 0x646562744365696c696e67000000000000000000000000000000000000000000 |                                                              |
| data              | VARCHAR   | 35221352219427937315145843530397892652067113926840492              |                                                              |

## 118. Table: SAFEEngine\_event\_ModifySAFECollateralization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-01 15:37:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17600139                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x23de69dc2c816d6a139dde4ea1dc7eb5209e1d0f97508f0a4c73471ee071da67 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 255                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcc88a9d330da1133df3a7bd823b95e52511a6962                         | Address of the contract that produced the log                |
| collateralType    | VARCHAR   | 0x4554482d41000000000000000000000000000000000000000000000000000000 |                                                              |
| safe              | VARCHAR   | 0x49ac39451e4ccadd67d7455848f3679e77996045                         |                                                              |
| collateralSource  | VARCHAR   | 0x49ac39451e4ccadd67d7455848f3679e77996045                         |                                                              |
| debtDestination   | VARCHAR   | 0x49ac39451e4ccadd67d7455848f3679e77996045                         |                                                              |
| deltaCollateral   | VARCHAR   | 0                                                                  |                                                              |
| deltaDebt         | VARCHAR   | -6119694196433880873750                                            |                                                              |
| lockedCollateral  | VARCHAR   | 100000000000000000000                                              |                                                              |
| generatedDebt     | VARCHAR   | 5570561783566713932533                                             |                                                              |
| globalDebt        | VARCHAR   | 3619161699289521521951717819690160138550310747221159               |                                                              |

## 119. Table: SAFEEngine\_event\_RemoveAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-26 13:27:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15218371                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb57fdc531e24ef7a08218a328f1c03996a0a7378b5051ebd8180e6b397b09d4e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 253                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcc88a9d330da1133df3a7bd823b95e52511a6962                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xa57a4e6170930ac547c147cdf26ae4682fa8262e                         |                                                              |

## 120. Table: SAFEEngine\_event\_SettleDebt\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2022-02-27 05:18:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 14286293                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x19fc8798f357bc4e0800860c44b8953896e832b8c56b7dab8211182f06ca3712 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0xcc88a9d330da1133df3a7bd823b95e52511a6962                         | Address of the contract that produced the log                |
| account            | VARCHAR   | 0xcee6aa1ab47d0fb0f24f51a3072ec16e20f90fce                         |                                                              |
| rad                | VARCHAR   | 359043017487106690076032443524071555683660890116340                |                                                              |
| debtBalance        | VARCHAR   | 0                                                                  |                                                              |
| coinBalance        | VARCHAR   | 572328908145191386265465386851985618868449268863604                |                                                              |
| globalUnbackedDebt | VARCHAR   | 0                                                                  |                                                              |
| globalDebt         | VARCHAR   | 25573837902486916137129488963816351460055142059542096              |                                                              |

## 121. Table: SAFEEngine\_event\_TransferCollateral\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-13 16:42:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15962367                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7fdfb2013799701fa1c160b24cf477618aeb9b26089e643a56432c9124bfeffc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 112                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcc88a9d330da1133df3a7bd823b95e52511a6962                         | Address of the contract that produced the log                |
| collateralType    | VARCHAR   | 0x4554482d41000000000000000000000000000000000000000000000000000000 |                                                              |
| src               | VARCHAR   | 0xc1ccea40a2652881d3f8af8ca79c8516cb0c7459                         |                                                              |
| dst               | VARCHAR   | 0x9edb54fe10c62f544e5977e6039d802a31f2c4c5                         |                                                              |
| wad               | VARCHAR   | 500000000000000000000                                              |                                                              |

## 122. Table: SAFEEngine\_event\_TransferInternalCoins\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-16 03:06:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12835423                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf5e0d3743dc5d70f6765004b6f5a922eb117e5f7688002b8891623c1d99bba19 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 123                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcc88a9d330da1133df3a7bd823b95e52511a6962                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0x83533fdd3285f48204215e9cf38c785371258e76                         |                                                              |
| dst               | VARCHAR   | 0x99fb4386310756522e727388bf5b68ccfaa22247                         |                                                              |
| rad               | VARCHAR   | 100000000000000000000000000000000000000000                         |                                                              |

## 123. Table: SAFEEngine\_event\_TransferSAFECollateralAndDebt\_history

| Column              | Type      | Example                                                      | Description |
| ------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp    | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number       | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash   | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index          | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address   | VARCHAR   | Address of the contract that produced the log                |             |
| collateralType      | VARCHAR   |                                                              |             |
| src                 | VARCHAR   |                                                              |             |
| dst                 | VARCHAR   |                                                              |             |
| deltaCollateral     | VARCHAR   |                                                              |             |
| deltaDebt           | VARCHAR   |                                                              |             |
| srcLockedCollateral | VARCHAR   |                                                              |             |
| srcGeneratedDebt    | VARCHAR   |                                                              |             |
| dstLockedCollateral | VARCHAR   |                                                              |             |
| dstGeneratedDebt    | VARCHAR   |                                                              |             |

## 124. Table: SAFEEngine\_event\_UpdateAccumulatedRate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-02 11:58:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11958679                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x006e5b24b1b337963f5e1159bbc6887a368201ac58bc6bc0ae5cb15d6fc728ff | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 118                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcc88a9d330da1133df3a7bd823b95e52511a6962                         | Address of the contract that produced the log                |
| collateralType    | VARCHAR   | 0x4554482d41000000000000000000000000000000000000000000000000000000 |                                                              |
| surplusDst        | VARCHAR   | 0xcee6aa1ab47d0fb0f24f51a3072ec16e20f90fce                         |                                                              |
| rateMultiplier    | VARCHAR   | 410732503126951672093                                              |                                                              |
| dstCoinBalance    | VARCHAR   | 1079014787602160398789865322857973111586692855612155               |                                                              |
| globalDebt        | VARCHAR   | 33967535083932281575471883970773532364943360831306000              |                                                              |

## 125. Table: TaxCollector\_event\_AddAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-25 13:07:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14275432                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7122c60f35446b86cdac33560758caefcada64396c22cc365b51baa3f4a5ded7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 104                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcdb05aeda142a1b0d6044c09c64e4226c1a281eb                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x95f5b549e4fddde4433ab20bae35f97f473f4a6f                         |                                                              |

## 126. Table: TaxCollector\_event\_AddSecondaryReceiver\_history

| Column                          | Type      | Example                                                            | Description                                                  |
| ------------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp                | TIMESTAMP | 2021-08-26 13:08:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number                   | INTEGER   | 13101162                                                           | The block number where this event was emitted                |
| transaction\_hash               | VARCHAR   | 0x94cc1650adbac6599417dcef395a0d10619e9636e9e47ca12d0f198bd2c12755 | Hash of the transactions in which this event was emitted     |
| log\_index                      | INTEGER   | 428                                                                | Integer of the log index position in the block of this event |
| contract\_address               | VARCHAR   | 0xcdb05aeda142a1b0d6044c09c64e4226c1a281eb                         | Address of the contract that produced the log                |
| collateralType                  | VARCHAR   | 0x4554482d41000000000000000000000000000000000000000000000000000000 |                                                              |
| secondaryReceiverNonce          | VARCHAR   | 2                                                                  |                                                              |
| latestSecondaryReceiver         | VARCHAR   | 2                                                                  |                                                              |
| secondaryReceiverAllotedTax     | VARCHAR   | 70000000000000000000000000000                                      |                                                              |
| secondaryReceiverRevenueSources | VARCHAR   | 1                                                                  |                                                              |

## 127. Table: TaxCollector\_event\_CollectTax\_history

| Column                | Type      | Example                                                            | Description                                                  |
| --------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp      | TIMESTAMP | 2021-03-05 19:25:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number         | INTEGER   | 11980224                                                           | The block number where this event was emitted                |
| transaction\_hash     | VARCHAR   | 0x8c6df52920eade8a94ada71e42377bcdfd0822854886c0eb3054ae361f6b5a02 | Hash of the transactions in which this event was emitted     |
| log\_index            | INTEGER   | 260                                                                | Integer of the log index position in the block of this event |
| contract\_address     | VARCHAR   | 0xcdb05aeda142a1b0d6044c09c64e4226c1a281eb                         | Address of the contract that produced the log                |
| collateralType        | VARCHAR   | 0x4554482d41000000000000000000000000000000000000000000000000000000 |                                                              |
| latestAccumulatedRate | VARCHAR   | 1001095343896599626813801314                                       |                                                              |
| deltaRate             | VARCHAR   | 2155552802499806260822                                             |                                                              |

## 128. Table: TaxCollector\_event\_DistributeTax\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-23 13:18:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17322182                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4b85cf5ce2e3aac143e6b5b17da56dd79323a254cac7da5ec88debf8653cb763 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 502                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcdb05aeda142a1b0d6044c09c64e4226c1a281eb                         | Address of the contract that produced the log                |
| collateralType    | VARCHAR   | 0x4554482d41000000000000000000000000000000000000000000000000000000 |                                                              |
| target            | VARCHAR   | 0x83533fdd3285f48204215e9cf38c785371258e76                         |                                                              |
| taxCut            | VARCHAR   | 4479409052363429455558                                             |                                                              |

## 129. Table: TaxCollector\_event\_InitializeCollateralType\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-13 13:39:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11848573                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc7935c32b4b3602f0761587fe1b9011b08a9e163e61fe9064ecfe02b2c8bfbe3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 106                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcdb05aeda142a1b0d6044c09c64e4226c1a281eb                         | Address of the contract that produced the log                |
| collateralType    | VARCHAR   | 0x4554482d41000000000000000000000000000000000000000000000000000000 |                                                              |

## 130. Table: TaxCollector\_event\_ModifyParameters\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-13 14:32:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11848836                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa103b453a2f50f3211d79671ec173d3f8aff9bf705c79ef3ab67a3be0f7bf370 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 58                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcdb05aeda142a1b0d6044c09c64e4226c1a281eb                         | Address of the contract that produced the log                |
| collateralType    | VARCHAR   | 0x4554482d41000000000000000000000000000000000000000000000000000000 |                                                              |
| position          | VARCHAR   | 100000000000000                                                    |                                                              |
| taxPercentage     | VARCHAR   | 50000000000000000000000000000                                      |                                                              |
| receiverAccount   | VARCHAR   | 0x83533fdd3285f48204215e9cf38c785371258e76                         |                                                              |

## 131. Table: TaxCollector\_event\_ModifySecondaryReceiver\_history

| Column                          | Type      | Example                                                            | Description                                                  |
| ------------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp                | TIMESTAMP | 2021-08-26 13:07:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number                   | INTEGER   | 13101160                                                           | The block number where this event was emitted                |
| transaction\_hash               | VARCHAR   | 0xb39b4d325db8ab6ef8d94705f582b93413b63b952a8bf630c9ba7633e3443020 | Hash of the transactions in which this event was emitted     |
| log\_index                      | INTEGER   | 243                                                                | Integer of the log index position in the block of this event |
| contract\_address               | VARCHAR   | 0xcdb05aeda142a1b0d6044c09c64e4226c1a281eb                         | Address of the contract that produced the log                |
| collateralType                  | VARCHAR   | 0x4554482d41000000000000000000000000000000000000000000000000000000 |                                                              |
| secondaryReceiverNonce          | VARCHAR   | 1                                                                  |                                                              |
| latestSecondaryReceiver         | VARCHAR   | 1                                                                  |                                                              |
| secondaryReceiverAllotedTax     | VARCHAR   | 40000000000000000000000000000                                      |                                                              |
| secondaryReceiverRevenueSources | VARCHAR   | 1                                                                  |                                                              |

## 132. Table: TaxCollector\_event\_RemoveAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-25 13:07:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14275432                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7122c60f35446b86cdac33560758caefcada64396c22cc365b51baa3f4a5ded7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 105                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcdb05aeda142a1b0d6044c09c64e4226c1a281eb                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x42fc2f8a6c712d4cbf00fc67fe05adacfebde382                         |                                                              |

## 133. Table: UniswapConsecutiveSlotsMedianRAIUSD\_event\_AddAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-13 15:44:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11849182                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4f9acf20126a3ce865edd16a87db94bfaaead329b04a9a0189d3eed419d63093 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 108                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x12a5e1c81b10b264a575930aeae80681ddf595fe                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xa57a4e6170930ac547c147cdf26ae4682fa8262e                         |                                                              |

## 134. Table: UniswapConsecutiveSlotsMedianRAIUSD\_event\_FailRewardCaller\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| revertReason      | VARCHAR   |                                                              |             |
| feeReceiver       | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 135. Table: UniswapConsecutiveSlotsMedianRAIUSD\_event\_FailedConverterFeedUpdate\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-23 09:49:36+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12094402                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xac1ae6d9857cde118312c63f9e93a96d739c066d5ed990aa714f3cfb7c304c73                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 222                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x12a5e1c81b10b264a575930aeae80681ddf595fe                                                           | Address of the contract that produced the log                |
| reason            | VARCHAR   | 0x08c379a0000000000000000000000000000000000000000000000000000000000000002000000000000000000000000000 |                                                              |

## 136. Table: UniswapConsecutiveSlotsMedianRAIUSD\_event\_FailedUniswapPairSync\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| reason            | VARCHAR   |                                                              |             |

## 137. Table: UniswapConsecutiveSlotsMedianRAIUSD\_event\_ModifyParameters\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-13 13:51:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11848635                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x18785b88ef494a43f4360b9517d6bb794af30d451cea43281e5966f7dc3ece3f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x12a5e1c81b10b264a575930aeae80681ddf595fe                         | Address of the contract that produced the log                |
| parameter         | VARCHAR   | 0x6d6178526577617264496e63726561736544656c617900000000000000000000 |                                                              |
| val               | VARCHAR   | 10800                                                              |                                                              |

## 138. Table: UniswapConsecutiveSlotsMedianRAIUSD\_event\_RemoveAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-13 15:45:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11849189                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x04091bff45221d727fc144978907812677f08a700e176ee4f6470b44a777c6fa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 50                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x12a5e1c81b10b264a575930aeae80681ddf595fe                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x7fafc11677649db6abfec127b4b776d585520ae1                         |                                                              |

## 139. Table: UniswapConsecutiveSlotsMedianRAIUSD\_event\_UpdateResult\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-20 04:58:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12275001                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x407f2aaee10f6f4f8d2815e85322e21a8f10ce94133c01f515d782334ce916e8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 220                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x12a5e1c81b10b264a575930aeae80681ddf595fe                         | Address of the contract that produced the log                |
| medianPrice       | VARCHAR   | 2936366313517132034                                                |                                                              |
| lastUpdateTime    | VARCHAR   | 1618894727                                                         |                                                              |

## 140. Table: UniswapConsecutiveSlotsPriceFeedMedianizer\_event\_AddAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-26 10:45:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12509517                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x27d18851f61cfc9b4d9d152490f04aed191d5fbaa5d4f4aa6f1dda86c993bbc6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 39                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfbf4849a06f6e6f53ecb31d2f8bd61aa7874b268                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xfa5e4955a11902f849ecaddef355db69c2036de6                         |                                                              |

## 141. Table: UniswapConsecutiveSlotsPriceFeedMedianizer\_event\_FailedConverterFeedUpdate\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| reason            | VARCHAR   |                                                              |             |

## 142. Table: UniswapConsecutiveSlotsPriceFeedMedianizer\_event\_FailedReimburseCaller\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-12 00:17:55+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13598055                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x199f8c9851e2b0dff93bedf41e02fdf297c0eec1f2606761a3d0445910951819                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 198                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfbf4849a06f6e6f53ecb31d2f8bd61aa7874b268                                                           | Address of the contract that produced the log                |
| revertReason      | VARCHAR   | 0x08c379a0000000000000000000000000000000000000000000000000000000000000002000000000000000000000000000 |                                                              |

## 143. Table: UniswapConsecutiveSlotsPriceFeedMedianizer\_event\_FailedUniswapPairSync\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| reason            | VARCHAR   |                                                              |             |

## 144. Table: UniswapConsecutiveSlotsPriceFeedMedianizer\_event\_ModifyParameters\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-26 10:45:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12509517                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x27d18851f61cfc9b4d9d152490f04aed191d5fbaa5d4f4aa6f1dda86c993bbc6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 41                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfbf4849a06f6e6f53ecb31d2f8bd61aa7874b268                         | Address of the contract that produced the log                |
| parameter         | VARCHAR   | 0x6d617857696e646f7753697a6500000000000000000000000000000000000000 |                                                              |
| val               | VARCHAR   | 93600                                                              |                                                              |

## 145. Table: UniswapConsecutiveSlotsPriceFeedMedianizer\_event\_RemoveAuthorization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-26 11:01:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12509589                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x27c4553c8a835d295e63b1a842efdeb1f6a416147ac8b12fe5a7208c6da07e52 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 238                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfbf4849a06f6e6f53ecb31d2f8bd61aa7874b268                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xfa5e4955a11902f849ecaddef355db69c2036de6                         |                                                              |

## 146. Table: UniswapConsecutiveSlotsPriceFeedMedianizer\_event\_UpdateResult\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-12 11:27:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12619391                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe69319cc0f8707ba8fa67ce96bbdb5921ca26add2785c00507c2033ff426401e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 132                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfbf4849a06f6e6f53ecb31d2f8bd61aa7874b268                         | Address of the contract that produced the log                |
| medianPrice       | VARCHAR   | 2970150965705494438                                                |                                                              |
| lastUpdateTime    | VARCHAR   | 1623497268                                                         |                                                              |
