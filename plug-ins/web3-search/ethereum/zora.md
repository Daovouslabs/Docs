# zora

## 1. Table: AsksV1\_1\_event\_ExchangeExecuted\_history

| Column            | Type                                                         | Example                                                                                              | Description                                                  |
| ----------------- | ------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP                                                    | 2022-10-31 17:56:23+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER                                                      | 15869674                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR                                                      | 0x548a482572abab13a532b08c1d5662422f49769016d1c9bf4f314ebad3a0bbf0                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER                                                      | 298                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR                                                      | 0x6170b3c3a54c3d8c854934cbc314ed479b2b29a3                                                           | Address of the contract that produced the log                |
| userA             | VARCHAR                                                      | 0x5c2aeb0f2b70e3896d5cde7ed02e78961e53fa2c                                                           |                                                              |
| userB             | VARCHAR                                                      | 0xda5921614a824a6cc187175750b8b3dcb4dbe67d                                                           |                                                              |
| a                 | STRUCT\<tokenContract STRING, tokenId STRING, amount STRING> | {'tokenContract': '0xa6cb03f9b265948cc4014ce1f943f6b51469e385', 'tokenId': '2', 'amount': '1'}       |                                                              |
| a.tokenContract   | VARCHAR                                                      | 0xa6cb03f9b265948cc4014ce1f943f6b51469e385                                                           |                                                              |
| a.tokenId         | VARCHAR                                                      | 2                                                                                                    |                                                              |
| a.amount          | VARCHAR                                                      | 1                                                                                                    |                                                              |
| b                 | STRUCT\<tokenContract STRING, tokenId STRING, amount STRING> | {'tokenContract': '0x0000000000000000000000000000000000000000', 'tokenId': '0', 'amount': '105000000 |                                                              |
| b.tokenContract   | VARCHAR                                                      | 0x0000000000000000000000000000000000000000                                                           |                                                              |
| b.tokenId         | VARCHAR                                                      | 0                                                                                                    |                                                              |
| b.amount          | VARCHAR                                                      | 1050000000000000000                                                                                  |                                                              |

## 2. Table: AuctionHouse\_event\_AuctionEnded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-16 16:14:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14597344                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x52fa06362b4f8d08225d2d193ecf2e73208a521b50581ef2866199b74f4fff5b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 173                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe468ce99444174bd3bbbed09209577d25d1ad673                         | Address of the contract that produced the log                |
| auctionId         | VARCHAR   | 5053                                                               |                                                              |
| tokenId           | VARCHAR   | 4852                                                               |                                                              |
| tokenContract     | VARCHAR   | 0x19b703f65aa7e1e775bd06c2aa0d0d08c80f1c45                         |                                                              |
| tokenOwner        | VARCHAR   | 0x2a2c412c440dfb0e7cae46eff581e3e26afd1cd0                         |                                                              |
| curator           | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| winner            | VARCHAR   | 0xf598aadf12a2fc4709b5db0c4c169715efaf2038                         |                                                              |
| amount            | VARCHAR   | 100000000000000000                                                 |                                                              |
| curatorFee        | VARCHAR   | 0                                                                  |                                                              |
| auctionCurrency   | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
