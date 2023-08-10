# creamfinance

## 1. Table: Unitroller\_event\_MarketListed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-20 06:38:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11690694                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7d3cbb37867f5414d66b855f2be1de359cc17b76cb6c0d0be96e40142c241ba9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 23                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3d5bc3c8d13dcb8bf317092d84783c2697ae9258                         | Address of the contract that produced the log                |
| cToken            | VARCHAR   | 0x85759961b116f1d36fd697855c57a6ae40793d9b                         |                                                              |

## 2. Table: cToken\_event\_AccrueInterest\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2022-01-07 07:46:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 13957069                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x2be91c5a5ea367957a5753502afdf56174f9dbfadf336ab64ff270ec37892809 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 164                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x10fdbd1e48ee2fd9336a482d746138ae19e649db                         | Address of the contract that produced the log                |
| cashPrior           | VARCHAR   | 0                                                                  |                                                              |
| interestAccumulated | VARCHAR   | 0                                                                  |                                                              |
| borrowIndex         | VARCHAR   | 1267886495299452162                                                |                                                              |
| totalBorrows        | VARCHAR   | 180897063822756053023266                                           |                                                              |

## 3. Table: cToken\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-14 03:52:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12822885                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3f72b2363b752f6517a22488db0432163040e52114938072afa9a6ac6fe3a0a4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 259                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2a537fa9ffaea8c1a41d3c2b68a9cb791529366d                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0xd5d5a7cb1807364cde0bad51d0a7d758943ab114                         |                                                              |
| borrowAmount      | VARCHAR   | 1000000000000000000000                                             |                                                              |
| accountBorrows    | VARCHAR   | 8723643418770022740698                                             |                                                              |
| totalBorrows      | VARCHAR   | 8964104755904029441285                                             |                                                              |

## 4. Table: cToken\_event\_LiquidateBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-16 04:09:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12248917                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc3fb0645c8add0a0d69de1f79e2267884e9afa14f8b92ac398bab25d12280dd8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc7fd8dcee4697ceef5a2fd4608a7bd6a94c77480                         | Address of the contract that produced the log                |
| liquidator        | VARCHAR   | 0xbf3f6477dbd514ef85b7d3ec6ac2205fd0962039                         |                                                              |
| borrower          | VARCHAR   | 0xb1b823e450d5e4ddde14972ef4af2b51c2a66f9f                         |                                                              |
| repayAmount       | VARCHAR   | 4949032364025402725417                                             |                                                              |
| cTokenCollateral  | VARCHAR   | 0x44fbebd2f576670a6c33f6fc0b00aa8c5753b322                         |                                                              |
| seizeTokens       | VARCHAR   | 111491592351528                                                    |                                                              |

## 5. Table: cToken\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-16 05:25:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13234855                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe04bd6324e831043f5d4f56cea1a7d3de7ba5bbc99ba6fefb0e1936e76243730 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 425                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x197070723ce0d3810a0e47f06e935c30a480d4fc                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0x4aab9e6eb125cdd378671188255f19325e3a804f                         |                                                              |
| mintAmount        | VARCHAR   | 44000000                                                           |                                                              |
| mintTokens        | VARCHAR   | 2171878247                                                         |                                                              |

## 6. Table: cToken\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-14 23:22:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12828033                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf90cefc816e3a8e9749c8eea8f0e3b45cd126df7aae096396f0f694526e036eb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 321                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1ff8cdb51219a8838b52e9cac09b71e591bc998e                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0x2a14a835ee1ba1980941dc032f255cb8beba5b60                         |                                                              |
| redeemAmount      | VARCHAR   | 9300000000000000000000                                             |                                                              |
| redeemTokens      | VARCHAR   | 42258647642413                                                     |                                                              |

## 7. Table: cToken\_event\_RepayBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-25 19:22:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11524674                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x851456a10235c8e5d82b7e22dea193fbbfc09e099aa2244974504418bf06ea43 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 58                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x17107f40d70f4470d20cb3f138a052cae8ebd4be                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0xd98ab42c842f7713580b2b422efe6fc52e3c49bc                         |                                                              |
| borrower          | VARCHAR   | 0xa0bb038a8981fc526fecf3fcea8701312d932e86                         |                                                              |
| repayAmount       | VARCHAR   | 17161847                                                           |                                                              |
| accountBorrows    | VARCHAR   | 17161936                                                           |                                                              |
| totalBorrows      | VARCHAR   | 2187010407                                                         |                                                              |

## 8. Table: cToken\_event\_ReservesAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-07 11:15:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11405322                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf859026d84987a9aab7218d3ddae8ef6286f41687a0f64aef9dcf41709a6d37f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 228                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3225e3c669b39c7c8b3e204a8614bb218c5e31bc                         | Address of the contract that produced the log                |
| benefactor        | VARCHAR   | 0x197939c1ca20c2b506d6811d8b6cdb3394471074                         |                                                              |
| addAmount         | VARCHAR   | 963315146931270490379                                              |                                                              |
| newTotalReserves  | VARCHAR   | 972363818656293202061                                              |                                                              |

## 9. Table: cToken\_event\_ReservesReduced\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-07 07:07:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11404251                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x86a92975d5a59109727cdb6f1655bd4cfc3bc9630dddcc9bae9abd394a7d67fa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 109                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8b86e0598616a8d4f1fdae8b59e55fb5bc33d0d6                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0x6d5a7597896a703fe8c85775b23395a48f971305                         |                                                              |
| reduceAmount      | VARCHAR   | 96331514693127049037964                                            |                                                              |
| newTotalReserves  | VARCHAR   | 21805011378229823                                                  |                                                              |

## 10. Table: cToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-22 09:00:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12087660                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x02dacca022fc343ecf28ee3e7f4af7953c83883139d1bec1ce6b88ace9b7b19d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 154                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x17107f40d70f4470d20cb3f138a052cae8ebd4be                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x17107f40d70f4470d20cb3f138a052cae8ebd4be                         |                                                              |
| to                | VARCHAR   | 0x0b32aa5c1e71715206fe29b7badb21ad95f272c0                         |                                                              |
| amount            | VARCHAR   | 84955207689                                                        |                                                              |
