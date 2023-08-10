# dforce

## 1. Table: Controller\_event\_MarketAdded\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2022-07-16 04:39:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 15151619                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x026af8bd281ad718515853f96d837ab638a31353b8ba336be008b3f42e1a6c5f | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 386                                                                | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x8b53ab2c0df3230ea327017c91eb909f815ad113                         | Address of the contract that produced the log                |
| iToken             | VARCHAR   | 0x3e5cb932d7a1c0ca096b71cc486b2ad7e0dc3d0e                         |                                                              |
| collateralFactor   | VARCHAR   | 700000000000000000                                                 |                                                              |
| borrowFactor       | VARCHAR   | 1000000000000000000                                                |                                                              |
| supplyCapacity     | VARCHAR   | 100000000000000000000000                                           |                                                              |
| borrowCapacity     | VARCHAR   | 100000000000000000000000                                           |                                                              |
| distributionFactor | VARCHAR   | 1000000000000000000                                                |                                                              |

## 2. Table: iToken\_event\_AccrueInterest\_history

| Column              | Type      | Example                                                      | Description |
| ------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp    | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number       | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash   | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index          | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address   | VARCHAR   | Address of the contract that produced the log                |             |
| cashPrior           | VARCHAR   |                                                              |             |
| interestAccumulated | VARCHAR   |                                                              |             |
| borrowIndex         | VARCHAR   |                                                              |             |
| totalBorrows        | VARCHAR   |                                                              |             |

## 3. Table: iToken\_event\_Borrow\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2021-06-06 15:51:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 12581862                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x3da50d48075196fe613398e5513b9e6e99e1613da7eb47444e5cd5ba4e808ea9 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 270                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0xb3dc7425e63e1855eb41107134d471dd34d7b239                         | Address of the contract that produced the log                |
| borrower             | VARCHAR   | 0x639e323032e9d27c88f70ef8953f696d37ce20f6                         |                                                              |
| borrowAmount         | VARCHAR   | 100000000000000000000                                              |                                                              |
| accountBorrows       | VARCHAR   | 100000000000000000000                                              |                                                              |
| accountInterestIndex | VARCHAR   | 1000000142927847462                                                |                                                              |
| totalBorrows         | VARCHAR   | 502210071781086469199464                                           |                                                              |

## 4. Table: iToken\_event\_Flashloan\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| loaner            | VARCHAR   |                                                              |             |
| loanAmount        | VARCHAR   |                                                              |             |
| flashloanFee      | VARCHAR   |                                                              |             |
| protocolFee       | VARCHAR   |                                                              |             |
| timestamp         | VARCHAR   |                                                              |             |

## 5. Table: iToken\_event\_LiquidateBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-11 07:39:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16803415                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x160362ed0965d29abd0a72e6a4b24a3382a0f7bed681f3546c766e70e4a794fc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 184                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1adc34af68e970a93062b67344269fd341979eb0                         | Address of the contract that produced the log                |
| liquidator        | VARCHAR   | 0x4e1751fe4492a1f834c7320653f60158a0edf93b                         |                                                              |
| borrower          | VARCHAR   | 0xbe9e8ec25866b21ba34e97b9393bcabbcb4a5c86                         |                                                              |
| repayAmount       | VARCHAR   | 71329714421660920590511                                            |                                                              |
| iTokenCollateral  | VARCHAR   | 0x2f956b2f801c6dad74e87e7f45c94f6283bf0f45                         |                                                              |
| seizeTokens       | VARCHAR   | 82457014398                                                        |                                                              |

## 6. Table: iToken\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-06 15:54:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12581872                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x96492eecdd47e914e2683b2d6e5375dc33047eb3b654c90324b7c3a7c6d42aae | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 249                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb3dc7425e63e1855eb41107134d471dd34d7b239                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x639e323032e9d27c88f70ef8953f696d37ce20f6                         |                                                              |
| recipient         | VARCHAR   | 0x639e323032e9d27c88f70ef8953f696d37ce20f6                         |                                                              |
| mintAmount        | VARCHAR   | 22395140561518392935414                                            |                                                              |
| mintTokens        | VARCHAR   | 22395140473972244119822                                            |                                                              |

## 7. Table: iToken\_event\_Redeem\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2023-06-07 13:16:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 17428732                                                           | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0x5b8fea293cb61e4d2c44856a1ceb185bed25e374c2361164b7080d30cf1eeae1 | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 258                                                                | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0x2f956b2f801c6dad74e87e7f45c94f6283bf0f45                         | Address of the contract that produced the log                |
| from                   | VARCHAR   | 0x016f4eb10196d247ae5eb2c9d6c2562d7db7e61c                         |                                                              |
| recipient              | VARCHAR   | 0x016f4eb10196d247ae5eb2c9d6c2562d7db7e61c                         |                                                              |
| redeemiTokenAmount     | VARCHAR   | 204668160917                                                       |                                                              |
| redeemUnderlyingAmount | VARCHAR   | 214539677990                                                       |                                                              |

## 8. Table: iToken\_event\_RepayBorrow\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2021-05-08 08:02:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 12392439                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x2fe68ac39a01beb0ff9e6e6683cd8dea20910f0089756fac0f4b2e1e48d5b6c8 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 179                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x5acd75f21659a59ffab9aebaf350351a8bfaabc0                         | Address of the contract that produced the log                |
| payer                | VARCHAR   | 0x2d3efbe93cc1cd4748242a9ef7b9807bfc29daac                         |                                                              |
| borrower             | VARCHAR   | 0x2d3efbe93cc1cd4748242a9ef7b9807bfc29daac                         |                                                              |
| repayAmount          | VARCHAR   | 120000000000000000000                                              |                                                              |
| accountBorrows       | VARCHAR   | 880623437552015174856                                              |                                                              |
| accountInterestIndex | VARCHAR   | 1001115673666389345                                                |                                                              |
| totalBorrows         | VARCHAR   | 880623437552015230762                                              |                                                              |

## 9. Table: iToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-18 16:42:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12659540                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x554b086044a64dd10c4279417fefb16f5121c5979ed31666ab9b56411a5739f2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 301                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb3dc7425e63e1855eb41107134d471dd34d7b239                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xd6a68e5fb7b407f0fb2b4408a5f727cd11b8fda6                         |                                                              |
| amount            | VARCHAR   | 50209536402916410278162                                            |                                                              |
