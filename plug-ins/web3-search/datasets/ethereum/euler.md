# euler

## 1. Table: Euler\_event\_AssetStatus\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2022-01-06 03:11:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 13949405                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x3d8d2280daec3707a7a5c97d3b32ca35e96351ea6352f4fa48d7db26700892da | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 457                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x27182842e098f60e3d576794a5bffb0777e025d3                         | Address of the contract that produced the log                |
| underlying          | VARCHAR   | 0x24a6a37576377f63f194caa5f518a60f45b42921                         |                                                              |
| totalBalances       | VARCHAR   | 5368697581740764653272                                             |                                                              |
| totalBorrows        | VARCHAR   | 0                                                                  |                                                              |
| reserveBalance      | VARCHAR   | 0                                                                  |                                                              |
| poolSize            | VARCHAR   | 5368697581740764653272                                             |                                                              |
| interestAccumulator | VARCHAR   | 1000000000000000000000000000                                       |                                                              |
| interestRate        | VARCHAR   | 0                                                                  |                                                              |
| timestamp           | VARCHAR   | 1641438667                                                         |                                                              |

## 2. Table: Euler\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-26 08:09:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14846891                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc312098908b3b228392ddabdb2e24a47b4fd8c51593a4a87a77d91c9d116ee81 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 379                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x27182842e098f60e3d576794a5bffb0777e025d3                         | Address of the contract that produced the log                |
| underlying        | VARCHAR   | 0x1a7e4e63778b4f12a199c062f3efdd288afcbce8                         |                                                              |
| account           | VARCHAR   | 0xee3893b1c7f9ad58f6b3a44d130bcdd046e1738f                         |                                                              |
| amount            | VARCHAR   | 221511643492031825450194                                           |                                                              |

## 3. Table: Euler\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-06 11:14:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15910609                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5ccb26465d25e52340808fc1640cc306a7fe84a7a8655e4e50eda1b26c4f7305 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 84                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x27182842e098f60e3d576794a5bffb0777e025d3                         | Address of the contract that produced the log                |
| underlying        | VARCHAR   | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599                         |                                                              |
| account           | VARCHAR   | 0x6780ac060fdcba20ae02a6197c84bdc70cf8716b                         |                                                              |
| amount            | VARCHAR   | 1980332469917389011                                                |                                                              |

## 4. Table: Euler\_event\_Liquidation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-08 16:14:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15926443                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7ebbbf7528f1650619e273ca6ad58c0fae623b48b4567b312a563d659a97611f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 105                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x27182842e098f60e3d576794a5bffb0777e025d3                         | Address of the contract that produced the log                |
| liquidator        | VARCHAR   | 0xa5f95adf6a52c000ef1fb6ac850637615f8fd8f3                         |                                                              |
| violator          | VARCHAR   | 0x5364fae66b0d11ba9df72f0a6b740e14865e1c9b                         |                                                              |
| underlying        | VARCHAR   | 0x50d1c9771902476076ecfc8b2a83ad6b9355a4c9                         |                                                              |
| collateral        | VARCHAR   | 0xdac17f958d2ee523a2206206994597c13d831ec7                         |                                                              |
| repay             | VARCHAR   | 283028031606714912363                                              |                                                              |
| yield             | VARCHAR   | 6043994902908993921917                                             |                                                              |
| healthScore       | VARCHAR   | 901901115585004870                                                 |                                                              |
| baseDiscount      | VARCHAR   | 118098884414995130                                                 |                                                              |
| discount          | VARCHAR   | 118098884414995130                                                 |                                                              |

## 5. Table: Euler\_event\_MarketActivated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-07 19:41:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13960236                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7e7d708a13d7d293c533716ea4a656adb9c6b4ef06505b587ef77c879ce4393e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 34                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x27182842e098f60e3d576794a5bffb0777e025d3                         | Address of the contract that produced the log                |
| underlying        | VARCHAR   | 0x95ad61b0a150d79219dcf64e1e6cc01f0b64c4ce                         |                                                              |
| eToken            | VARCHAR   | 0x2ee4adbf628c52bc396ce1344116962f4a2143e9                         |                                                              |
| dToken            | VARCHAR   | 0xb4509999db185df3d7f8df1a39fbea9040df8277                         |                                                              |

## 6. Table: Euler\_event\_Repay\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-09 12:57:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14352706                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb2bfaeda42d0fda39ac2876341a7823d95728f2fa6545366803f7196e9e55b2a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 166                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x27182842e098f60e3d576794a5bffb0777e025d3                         | Address of the contract that produced the log                |
| underlying        | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| account           | VARCHAR   | 0x239eec9ec218f71cef5cc14d88b142ed4ff44110                         |                                                              |
| amount            | VARCHAR   | 40000000000000000000000                                            |                                                              |

## 7. Table: Euler\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-09 13:06:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15308166                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x31b8809a0a02896aa51b87dd0566e9d362dba1d127fb7a72bbc80f6ce2ba6ee2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 304                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x27182842e098f60e3d576794a5bffb0777e025d3                         | Address of the contract that produced the log                |
| underlying        | VARCHAR   | 0x24a6a37576377f63f194caa5f518a60f45b42921                         |                                                              |
| account           | VARCHAR   | 0x126fe1ada25abdbd0584b60f3e5156807ee18fc9                         |                                                              |
| amount            | VARCHAR   | 39007695108782255004                                               |                                                              |
