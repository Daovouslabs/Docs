# aave

## 1. Table: ATokenV2\_event\_BalanceTransfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-11 12:07:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 44949312                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbd7b6708844dc8339e3080c03956553336faeda1ed5faeb756ffcb3652617c3e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 457                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1d2a0e5ec8e5bbdca5cb219e649b565d8e5c3360                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xea4040b21cb68afb94889cb60834b13427cfc4eb                         |                                                              |
| to                | VARCHAR   | 0xd8d22817d216164d09ca5909a70beca608d65aa9                         |                                                              |
| value             | VARCHAR   | 438094425471521473                                                 |                                                              |
| index             | VARCHAR   | 1000556720002352932884748615                                       |                                                              |

## 2. Table: ATokenV2\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-19 09:28:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 18152664                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0975e95d663d511e5922b42b42b139fb1697d5124ac112f1a53f91e0560405a8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 270                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1a13f4ca1d028320a707d99520abfefca3998b7f                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x445fe580ef8d70ff569ab36e80c647af338db351                         |                                                              |
| target            | VARCHAR   | 0x0003bbb966655dc0fbbb380797b07fc547e9ddc5                         |                                                              |
| value             | VARCHAR   | 500000000                                                          |                                                              |
| index             | VARCHAR   | 1011501537294218648035387936                                       |                                                              |

## 3. Table: ATokenV2\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-27 09:59:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45575206                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa2826d946ef40c2e738806e50ee4b02f6c64263ad4ad4ba9912020768b292116 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 139                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8df3aad3a84da6b69a4da8aec3ea40d9091b2ac4                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xe8599f3cc5d38a9ad6f3684cd5cea72f10dbc383                         |                                                              |
| value             | VARCHAR   | 69215086829297275                                                  |                                                              |
| index             | VARCHAR   | 1031968223807578815306918047                                       |                                                              |

## 4. Table: ATokenV2\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-10 15:02:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 34172456                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb7329a9a643f88df390a0090654ebf1f81f3c1d1360a7f8dd12c91fc100fb249 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 279                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x080b5bf8f360f624628e0fb961f4e67c9e3c7cf1                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x7734280a4337f37fbf4651073db7c28c80b339e9                         |                                                              |
| value             | VARCHAR   | 231293450511713643                                                 |                                                              |

## 5. Table: AToken\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-11 10:05:25+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30598658                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x29d1fff30297cafbbcd32666fa3c66d97c2e0d1840ffe4a098658209a019108f             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 246                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x078f358208685046a11c85e8ad32895ded33a249                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x2b448d9fa8387e2fa9c4e9098237846e328bffa0                                     |                                                              |
| spender           | VARCHAR   | 0x301f221bc732907e2da2dbbfaa8f8f6847c170c3                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913121805435 |                                                              |

## 6. Table: AToken\_event\_BalanceTransfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-07 14:06:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 39020010                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8904e38a51216235a4d3ec32b7f94079c92b8b38054e4fb658efcd5fd8cd843e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 235                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe50fa9b3c56ffb159cb0fca61f5c9d750e8128c8                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x885c352d2cd24dde44dd4673d4e2b5142b6f6bfb                         |                                                              |
| to                | VARCHAR   | 0x2ffb34aaae1ecb33f1ad90738aeddd86c5ab3477                         |                                                              |
| value             | VARCHAR   | 4000000000000000000                                                |                                                              |
| index             | VARCHAR   | 1004099591508373922132691464                                       |                                                              |

## 7. Table: AToken\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-17 14:56:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 31998517                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xebf59098a8d55db2b7268e7dc72556ff3b412c7101c84c339c133001280be221 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 306                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf329e36c7bf6e5e86ce2150875a84ce77f477375                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xb1f083361c0a2b8f8ba2bc4523afc948ea378558                         |                                                              |
| target            | VARCHAR   | 0xb1f083361c0a2b8f8ba2bc4523afc948ea378558                         |                                                              |
| value             | VARCHAR   | 5000000000000000000                                                |                                                              |
| balanceIncrease   | VARCHAR   | 0                                                                  |                                                              |
| index             | VARCHAR   | 1000133899565137019760980182                                       |                                                              |

## 8. Table: AToken\_event\_Initialized\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2022-09-14 16:26:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 33101585                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x9470258f40ba4cdf5150dcb0aa7a926492357d1e74d1baa180c9c89bf6be28c7 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 168                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0xea1132120ddcdda2f119e99fa7a27a0d036f7ac9                         | Address of the contract that produced the log                |
| underlyingAsset      | VARCHAR   | 0x3a58a54c066fdc0f2d55fc9c89f0415c92ebf3c4                         |                                                              |
| pool                 | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         |                                                              |
| treasury             | VARCHAR   | 0xe8599f3cc5d38a9ad6f3684cd5cea72f10dbc383                         |                                                              |
| incentivesController | VARCHAR   | 0x929ec64c34a17401f460460d4b9390518e5b473e                         |                                                              |
| aTokenDecimals       | VARCHAR   | 18                                                                 |                                                              |
| aTokenName           | VARCHAR   | Aave Polygon STMATIC                                               |                                                              |
| aTokenSymbol         | VARCHAR   | aPolSTMATIC                                                        |                                                              |
| params               | VARCHAR   | 0x                                                                 |                                                              |

## 9. Table: AToken\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-04 11:49:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 38899294                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe614fb8003bd7ce15f2de08ed993bcf8f6057f1e603830091dedd206d0a46518 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 241                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x078f358208685046a11c85e8ad32895ded33a249                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x011c79c3f951dc3d26fb08d226b60a7653753a95                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x011c79c3f951dc3d26fb08d226b60a7653753a95                         |                                                              |
| value             | VARCHAR   | 7078769                                                            |                                                              |
| balanceIncrease   | VARCHAR   | 0                                                                  |                                                              |
| index             | VARCHAR   | 1001301335628365892284278435                                       |                                                              |

## 10. Table: AToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-12 03:32:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 41430709                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x64dd3efef269a64f8ee6be07c0e249eebcce66abdb6bad7d2aab2b6ce02fd88f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 260                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x078f358208685046a11c85e8ad32895ded33a249                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x6a4b2b595d369c963493fc704cf48e42fad8260b                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 31099                                                              |                                                              |

## 11. Table: Aave\_Lending\_Pool\_V2\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-10 22:38:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 44926979                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbd9619c17ab7ad5db588bba0f591d3fbbf6bcf3520915d6724a41f78df0bd87d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 556                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8dff5e27ea6b7ac08ebfdf9eb090f32ee9a30fcf                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         |                                                              |
| user              | VARCHAR   | 0x5270e8d5e7e53841be327da5d927b754a8b9dee9                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x5270e8d5e7e53841be327da5d927b754a8b9dee9                         |                                                              |
| amount            | VARCHAR   | 136000000000000000000                                              |                                                              |
| borrowRateMode    | VARCHAR   | 2                                                                  |                                                              |
| borrowRate        | VARCHAR   | 34485541380961549754195444                                         |                                                              |
| referral          | VARCHAR   | 3228                                                               |                                                              |

## 12. Table: Aave\_Lending\_Pool\_V2\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-11 18:55:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 39182512                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc51ef51cb44d731d178d92b8d91df748f540a365d1669dd20462e031f0431bf1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 448                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8dff5e27ea6b7ac08ebfdf9eb090f32ee9a30fcf                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         |                                                              |
| user              | VARCHAR   | 0x35784a624d4ffbc3594f4d16fa3801fef063241c                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x3a0267f9d7cb2f0bcb2239742837485400bdef57                         |                                                              |
| amount            | VARCHAR   | 81205759321865816730                                               |                                                              |
| referral          | VARCHAR   | 0                                                                  |                                                              |

## 13. Table: Aave\_Lending\_Pool\_V2\_event\_FlashLoan\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-03 23:27:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45877210                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa287c60782dc54bb12b1d13ece0f20985995bb578e1a5bc2feacda55e2d0735f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2307                                                               | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8dff5e27ea6b7ac08ebfdf9eb090f32ee9a30fcf                         | Address of the contract that produced the log                |
| target            | VARCHAR   | 0x35784a624d4ffbc3594f4d16fa3801fef063241c                         |                                                              |
| initiator         | VARCHAR   | 0xa904377da88f885ce62daee6a01eb11161f5b216                         |                                                              |
| asset             | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         |                                                              |
| amount            | VARCHAR   | 1502432265399320200000                                             |                                                              |
| premium           | VARCHAR   | 1352189038859388180                                                |                                                              |
| referralCode      | VARCHAR   | 0                                                                  |                                                              |

## 14. Table: Aave\_Lending\_Pool\_V2\_event\_LiquidationCall\_history

| Column                     | Type      | Example                                                            | Description                                                  |
| -------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp           | TIMESTAMP | 2023-08-06 04:22:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number              | INTEGER   | 45965334                                                           | The block number where this event was emitted                |
| transaction\_hash          | VARCHAR   | 0x09300092bd46e74697851bd4dd5e6225a2b26151dbe3f619e3cc905948a2ba83 | Hash of the transactions in which this event was emitted     |
| log\_index                 | INTEGER   | 11                                                                 | Integer of the log index position in the block of this event |
| contract\_address          | VARCHAR   | 0x8dff5e27ea6b7ac08ebfdf9eb090f32ee9a30fcf                         | Address of the contract that produced the log                |
| collateralAsset            | VARCHAR   | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                         |                                                              |
| debtAsset                  | VARCHAR   | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                         |                                                              |
| user                       | VARCHAR   | 0x55acb075c91366b3f99f943e14a70448bcb2c066                         |                                                              |
| debtToCover                | VARCHAR   | 1035515923                                                         |                                                              |
| liquidatedCollateralAmount | VARCHAR   | 1087291719                                                         |                                                              |
| liquidator                 | VARCHAR   | 0x3bb7a0f2fe88aba35408c64f588345481490fe93                         |                                                              |
| receiveAToken              | VARCHAR   | false                                                              |                                                              |

## 15. Table: Aave\_Lending\_Pool\_V2\_event\_Paused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 16. Table: Aave\_Lending\_Pool\_V2\_event\_RebalanceStableBorrowRate\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| reserve           | VARCHAR   |                                                              |             |
| user              | VARCHAR   |                                                              |             |

## 17. Table: Aave\_Lending\_Pool\_V2\_event\_Repay\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-01 16:46:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 43414341                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4c72f868e89a524fbd57a3dba11f8ad9d37149a3bc6af494633f2eea8f05960c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 196                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8dff5e27ea6b7ac08ebfdf9eb090f32ee9a30fcf                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         |                                                              |
| user              | VARCHAR   | 0x679b7f9e6dcc743d1ff73e28cd70a3be3d3927bb                         |                                                              |
| repayer           | VARCHAR   | 0x3db487975ab1728db5787b798866c2021b24ec52                         |                                                              |
| amount            | VARCHAR   | 53932159977716074268                                               |                                                              |

## 18. Table: Aave\_Lending\_Pool\_V2\_event\_ReserveDataUpdated\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2023-05-11 03:01:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 42558208                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xd9080cb0c6059728333592db6109645bb2609a45cb9c78b899906586d48107e0 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 15                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x8dff5e27ea6b7ac08ebfdf9eb090f32ee9a30fcf                         | Address of the contract that produced the log                |
| reserve             | VARCHAR   | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                         |                                                              |
| liquidityRate       | VARCHAR   | 17719855527824673307483524                                         |                                                              |
| stableBorrowRate    | VARCHAR   | 53790660853784141629868062                                         |                                                              |
| variableBorrowRate  | VARCHAR   | 29581321707568283259736124                                         |                                                              |
| liquidityIndex      | VARCHAR   | 1045595701363448937322917552                                       |                                                              |
| variableBorrowIndex | VARCHAR   | 1067790143589004604879379528                                       |                                                              |

## 19. Table: Aave\_Lending\_Pool\_V2\_event\_ReserveUsedAsCollateralDisabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-17 19:56:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 35732333                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5215a0ab323e805a68433c401923a613bfb690e215c6367397ec5d59bf8a4ebd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8dff5e27ea6b7ac08ebfdf9eb090f32ee9a30fcf                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         |                                                              |
| user              | VARCHAR   | 0x8867cea1d4a6c8f57ca48c1b54e64a3dbb1e0148                         |                                                              |

## 20. Table: Aave\_Lending\_Pool\_V2\_event\_ReserveUsedAsCollateralEnabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-13 12:34:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 31843340                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x40e751b68cfc1c4ac83daf5ff81754bd01891d00470f7625f60572f1325c655c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 246                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8dff5e27ea6b7ac08ebfdf9eb090f32ee9a30fcf                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         |                                                              |
| user              | VARCHAR   | 0x008fa7ed1c37e0fd2bf2dc372b6acc5ed1a1919d                         |                                                              |

## 21. Table: Aave\_Lending\_Pool\_V2\_event\_Swap\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| reserve           | VARCHAR   |                                                              |             |
| user              | VARCHAR   |                                                              |             |
| rateMode          | VARCHAR   |                                                              |             |

## 22. Table: Aave\_Lending\_Pool\_V2\_event\_Unpaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 23. Table: Aave\_Lending\_Pool\_V2\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-08 21:52:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 40122001                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbfb60ba076845537487a48949683a5c6121b474a5f09a1a98a35799a4274a719 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 511                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8dff5e27ea6b7ac08ebfdf9eb090f32ee9a30fcf                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         |                                                              |
| user              | VARCHAR   | 0x136b0157badb2e76f03a98185ef18ef3777a98c5                         |                                                              |
| to                | VARCHAR   | 0x136b0157badb2e76f03a98185ef18ef3777a98c5                         |                                                              |
| amount            | VARCHAR   | 5160767667857241313                                                |                                                              |

## 24. Table: Aave\_V3\_Pool\_event\_BackUnbacked\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| reserve           | VARCHAR   |                                                              |             |
| backer            | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |
| fee               | VARCHAR   |                                                              |             |

## 25. Table: Aave\_V3\_Pool\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-31 20:19:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 38756593                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x12953c197a2a361d4ff18335f6fe519c70d68159583eb26c99d1111ac23cbd69 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 40                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x0b3f868e0be5597d5db7feb59e1cadbb0fdda50a                         |                                                              |
| user              | VARCHAR   | 0x9fc7d6e7a3d4ab7b8b28d813f68674c8a6e91e83                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x9fc7d6e7a3d4ab7b8b28d813f68674c8a6e91e83                         |                                                              |
| amount            | VARCHAR   | 115000000000000000000                                              |                                                              |
| interestRateMode  | VARCHAR   | 2                                                                  |                                                              |
| borrowRate        | VARCHAR   | 53961181632522001246265920                                         |                                                              |
| referralCode      | VARCHAR   | 0                                                                  |                                                              |

## 26. Table: Aave\_V3\_Pool\_event\_FlashLoan\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-14 20:13:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 27139654                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb0e2f1abf9d2b325f4467c16025fbc84e4ee5b550ae0857407cfc9bb661f55ea | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 311                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| target            | VARCHAR   | 0x00d48554f570b6f1c474ebe56116159c3b1d625f                         |                                                              |
| initiator         | VARCHAR   | 0x566d9202208dc35ab0232988b28a3c8de766ea44                         |                                                              |
| asset             | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         |                                                              |
| amount            | VARCHAR   | 1052564030017418900000                                             |                                                              |
| interestRateMode  | VARCHAR   | 0                                                                  |                                                              |
| premium           | VARCHAR   | 526282015008709450                                                 |                                                              |
| referralCode      | VARCHAR   | 0                                                                  |                                                              |

## 27. Table: Aave\_V3\_Pool\_event\_IsolationModeTotalDebtUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-19 14:42:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 35805455                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x04e75d1333ffcdfd9faa9418dbe469c51d49f939135b77be1174ef2048df885e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xa3fa99a148fa48d14ed51d610c367c61876997f1                         |                                                              |
| totalDebt         | VARCHAR   | 13303721                                                           |                                                              |

## 28. Table: Aave\_V3\_Pool\_event\_LiquidationCall\_history

| Column                     | Type      | Example                                                            | Description                                                  |
| -------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp           | TIMESTAMP | 2023-01-07 00:10:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number              | INTEGER   | 37761502                                                           | The block number where this event was emitted                |
| transaction\_hash          | VARCHAR   | 0x28e4776e4005a2e97f1890897bcb6231f647bd5e73b20a17bc78d1f0701b3992 | Hash of the transactions in which this event was emitted     |
| log\_index                 | INTEGER   | 172                                                                | Integer of the log index position in the block of this event |
| contract\_address          | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| collateralAsset            | VARCHAR   | 0xd6df932a45c0f255f85145f286ea0b292b21c90b                         |                                                              |
| debtAsset                  | VARCHAR   | 0x385eeac5cb85a38a9a07a70c73e0a3271cfb54a7                         |                                                              |
| user                       | VARCHAR   | 0x78f9741828a71d69392a8185e7e7eb3d1de36c02                         |                                                              |
| debtToCover                | VARCHAR   | 241849316534474493                                                 |                                                              |
| liquidatedCollateralAmount | VARCHAR   | 4496254863262429                                                   |                                                              |
| liquidator                 | VARCHAR   | 0xebde83c70db053e7c839cbcab44743dcbfd34e62                         |                                                              |
| receiveAToken              | VARCHAR   | false                                                              |                                                              |

## 29. Table: Aave\_V3\_Pool\_event\_MintUnbacked\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| reserve           | VARCHAR   |                                                              |             |
| user              | VARCHAR   |                                                              |             |
| onBehalfOf        | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |
| referralCode      | VARCHAR   |                                                              |             |

## 30. Table: Aave\_V3\_Pool\_event\_MintedToTreasury\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-22 19:00:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 43022838                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6da8e197e8eb09288a1d498ead00b66faf4f6d593d26844b1b0dd81076228475 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 532                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0xd6df932a45c0f255f85145f286ea0b292b21c90b                         |                                                              |
| amountMinted      | VARCHAR   | 22476746799174                                                     |                                                              |

## 31. Table: Aave\_V3\_Pool\_event\_RebalanceStableBorrowRate\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| reserve           | VARCHAR   |                                                              |             |
| user              | VARCHAR   |                                                              |             |

## 32. Table: Aave\_V3\_Pool\_event\_Repay\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-01 10:13:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 43403616                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6e96ae4d754308e43a5b4c908b71e85e6fce82e3d2306ea37cb5b7d886320891 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 205                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x03b54a6e9a984069379fae1a4fc4dbae93b3bccd                         |                                                              |
| user              | VARCHAR   | 0x7de658c2a269399759e25d700e65c19415cf5069                         |                                                              |
| repayer           | VARCHAR   | 0x7de658c2a269399759e25d700e65c19415cf5069                         |                                                              |
| amount            | VARCHAR   | 105931178230697268                                                 |                                                              |
| useATokens        | VARCHAR   | false                                                              |                                                              |

## 33. Table: Aave\_V3\_Pool\_event\_ReserveDataUpdated\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2022-10-07 05:28:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 34032148                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x66c3d54b9044b856ff2d99602deacb27fe1e88c254a28151ddc7488c1a70e88f | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 269                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve             | VARCHAR   | 0xd6df932a45c0f255f85145f286ea0b292b21c90b                         |                                                              |
| liquidityRate       | VARCHAR   | 0                                                                  |                                                              |
| stableBorrowRate    | VARCHAR   | 90000000000000000000000000                                         |                                                              |
| variableBorrowRate  | VARCHAR   | 0                                                                  |                                                              |
| liquidityIndex      | VARCHAR   | 1000179179098065387280469316                                       |                                                              |
| variableBorrowIndex | VARCHAR   | 1000000000000000000000000000                                       |                                                              |

## 34. Table: Aave\_V3\_Pool\_event\_ReserveUsedAsCollateralDisabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-11 10:52:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 28187761                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfa16f777ff9141d58a74329de08805b2b080b9f88f1751c56fc47322045456e4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 178                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x0b3f868e0be5597d5db7feb59e1cadbb0fdda50a                         |                                                              |
| user              | VARCHAR   | 0x88b0ea576428da635d0fa9deb686765c90cfde2e                         |                                                              |

## 35. Table: Aave\_V3\_Pool\_event\_ReserveUsedAsCollateralEnabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-10 17:27:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 44918587                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb5aceb9a351d03c4c1b0448831476a2f35946e6b8c4f2cb5fd779a8826564def | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 54                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         |                                                              |
| user              | VARCHAR   | 0xcfd674f8731e801a4a15c1ae31770960e1afded1                         |                                                              |

## 36. Table: Aave\_V3\_Pool\_event\_Supply\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-20 20:51:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29803503                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x036e92ac008c055b7964ad72af51308a20bb41dae82ed4486cf2e54b0557beab | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 509                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0xe111178a87a3bff0c8d18decba5798827539ae99                         |                                                              |
| user              | VARCHAR   | 0x1f5e8942d652d9b1f639a3f1f797d767ba458668                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x1f5e8942d652d9b1f639a3f1f797d767ba458668                         |                                                              |
| amount            | VARCHAR   | 1396                                                               |                                                              |
| referralCode      | VARCHAR   | 0                                                                  |                                                              |

## 37. Table: Aave\_V3\_Pool\_event\_SwapBorrowRateMode\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-06 00:57:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45959666                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x92a5f46c5c714006ffd8970201a6507178d8de4d52da80bd7eb50ff339c93272 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 103                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                         |                                                              |
| user              | VARCHAR   | 0xa0f57d5abccc758ff964c035775e5a69a26a861a                         |                                                              |
| interestRateMode  | VARCHAR   | 1                                                                  |                                                              |

## 38. Table: Aave\_V3\_Pool\_event\_UserEModeSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-09 15:01:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 43716530                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe2436c6dea83723a708168f15a97128edc906bd83838ea0e08707cc6ac30bcb1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 775                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xe4217040c894e8873ee19d675b6d0eec992c2c0d                         |                                                              |
| categoryId        | VARCHAR   | 0                                                                  |                                                              |

## 39. Table: Aave\_V3\_Pool\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-07 18:28:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 37792487                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe87f3849cf53b2716172d2b217cc80d1b49af85c76c576bd2d8a5da6446b0799 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 164                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x0b3f868e0be5597d5db7feb59e1cadbb0fdda50a                         |                                                              |
| user              | VARCHAR   | 0x037ac478992e23340fbd4114f218943037916300                         |                                                              |
| to                | VARCHAR   | 0x037ac478992e23340fbd4114f218943037916300                         |                                                              |
| amount            | VARCHAR   | 5515000000000000000                                                |                                                              |

## 40. Table: LendingPoolConfigurator\_v2\_event\_ATokenUpgraded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-24 02:03:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 41885927                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcac668760f4ac39ed843a16f34b691349f733591563fbdc43a52426d06d4f501 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 70                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x26db2b833021583566323e3b8985999981b9f1f3                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x8f3cf7ad23cd3cadbd9735aff958023239c6a063                         |                                                              |
| proxy             | VARCHAR   | 0x27f8d03b3a2196956ed754badc28d73be8830a6e                         |                                                              |
| implementation    | VARCHAR   | 0x80f2c02224a2e548fc67c0bf705ebfa825dd5439                         |                                                              |

## 41. Table: LendingPoolConfigurator\_v2\_event\_BorrowingDisabledOnReserve\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-31 14:39:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12696811                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8c52c52ba2666b6604c8422e73f6106ec66e61329e55eb1737b0b6741728ce28 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x26db2b833021583566323e3b8985999981b9f1f3                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xd6df932a45c0f255f85145f286ea0b292b21c90b                         |                                                              |

## 42. Table: LendingPoolConfigurator\_v2\_event\_BorrowingEnabledOnReserve\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-30 21:25:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 24356970                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5bdeb60a7fe02e9e30e1a87801d451bdf1689554e87c1158371d0a20f033d293 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 153                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x26db2b833021583566323e3b8985999981b9f1f3                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x172370d5cd63279efa6d502dab29171933a610af                         |                                                              |
| stableRateEnabled | VARCHAR   | false                                                              |                                                              |

## 43. Table: LendingPoolConfigurator\_v2\_event\_CollateralConfigurationChanged\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2022-10-27 17:48:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 34871898                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xc6d621974b3d9a4d92ff5664d11ea0169793d6fd723f92d0fd60a0d074dd1bef | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 58                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x26db2b833021583566323e3b8985999981b9f1f3                         | Address of the contract that produced the log                |
| asset                | VARCHAR   | 0x385eeac5cb85a38a9a07a70c73e0a3271cfb54a7                         |                                                              |
| ltv                  | VARCHAR   | 2500                                                               |                                                              |
| liquidationThreshold | VARCHAR   | 4000                                                               |                                                              |
| liquidationBonus     | VARCHAR   | 11250                                                              |                                                              |

## 44. Table: LendingPoolConfigurator\_v2\_event\_ReserveActivated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |

## 45. Table: LendingPoolConfigurator\_v2\_event\_ReserveDeactivated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |

## 46. Table: LendingPoolConfigurator\_v2\_event\_ReserveDecimalsChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |
| decimals          | VARCHAR   |                                                              |             |

## 47. Table: LendingPoolConfigurator\_v2\_event\_ReserveFactorChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-07 09:14:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 46012775                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfbd91d0a6827a3847301b0cce883c7bac2a7629517ddccaf9f8ee8adf7b74f2d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 581                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x26db2b833021583566323e3b8985999981b9f1f3                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x8f3cf7ad23cd3cadbd9735aff958023239c6a063                         |                                                              |
| factor            | VARCHAR   | 2600                                                               |                                                              |

## 48. Table: LendingPoolConfigurator\_v2\_event\_ReserveFrozen\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-30 22:46:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 36270735                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x38622d5ab3a22b331f49065bf80de44a15475c318756c42a9b892b10eefb6f1a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x26db2b833021583566323e3b8985999981b9f1f3                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x0b3f868e0be5597d5db7feb59e1cadbb0fdda50a                         |                                                              |

## 49. Table: LendingPoolConfigurator\_v2\_event\_ReserveInitialized\_history

| Column                      | Type      | Example                                                            | Description                                                  |
| --------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp            | TIMESTAMP | 2022-01-30 21:25:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number               | INTEGER   | 24356970                                                           | The block number where this event was emitted                |
| transaction\_hash           | VARCHAR   | 0x5bdeb60a7fe02e9e30e1a87801d451bdf1689554e87c1158371d0a20f033d293 | Hash of the transactions in which this event was emitted     |
| log\_index                  | INTEGER   | 125                                                                | Integer of the log index position in the block of this event |
| contract\_address           | VARCHAR   | 0x26db2b833021583566323e3b8985999981b9f1f3                         | Address of the contract that produced the log                |
| asset                       | VARCHAR   | 0x85955046df4668e1dd369d2de9f3aeb98dd2a369                         |                                                              |
| aToken                      | VARCHAR   | 0x81fb82aacb4abe262fc57f06fd4c1d2de347d7b1                         |                                                              |
| stableDebtToken             | VARCHAR   | 0xa742710c0244a8ebcf533368e3f0b956b6e53f7b                         |                                                              |
| variableDebtToken           | VARCHAR   | 0x43150aa0b7e19293d935a412c8607f9172d3d3f3                         |                                                              |
| interestRateStrategyAddress | VARCHAR   | 0x6405f880e431403588e92b241ca15603047ef8a4                         |                                                              |

## 50. Table: LendingPoolConfigurator\_v2\_event\_ReserveInterestRateStrategyChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-02 16:59:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 42223162                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x16e98a6102a8b92211604386c2266adc3066c492091846decaa6f7ff5e25dccf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 28                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x26db2b833021583566323e3b8985999981b9f1f3                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x9a71012b13ca4d3d0cdc72a177df3ef03b0e76a3                         |                                                              |
| strategy          | VARCHAR   | 0x54da5057cda764909f4c79ba9fbb2d4a214eeae5                         |                                                              |

## 51. Table: LendingPoolConfigurator\_v2\_event\_ReserveUnfrozen\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |

## 52. Table: LendingPoolConfigurator\_v2\_event\_StableDebtTokenUpgraded\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |
| proxy             | VARCHAR   |                                                              |             |
| implementation    | VARCHAR   |                                                              |             |

## 53. Table: LendingPoolConfigurator\_v2\_event\_StableRateDisabledOnReserve\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |

## 54. Table: LendingPoolConfigurator\_v2\_event\_StableRateEnabledOnReserve\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |

## 55. Table: LendingPoolConfigurator\_v2\_event\_VariableDebtTokenUpgraded\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |
| proxy             | VARCHAR   |                                                              |             |
| implementation    | VARCHAR   |                                                              |             |

## 56. Table: PoolConfigurator\_v3\_event\_ATokenUpgraded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-10 13:37:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 42535602                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0967c39ab7306cf2fe43bce0ad6e918ba7aeeee94609b8e76d2401d5df61a994 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 576                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x03b54a6e9a984069379fae1a4fc4dbae93b3bccd                         |                                                              |
| proxy             | VARCHAR   | 0xf59036caebea7dc4b86638dfa2e3c97da9fccd40                         |                                                              |
| implementation    | VARCHAR   | 0xcf85ff1c37c594a10195f7a9ab85cbb0a03f69de                         |                                                              |

## 57. Table: PoolConfigurator\_v3\_event\_BorrowCapChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-28 00:43:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 37359227                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa3a85eaf3e96061c80aa72e0083c6f33cb323080ecf3c428bc40594c7d7cbd53 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 313                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x9a71012b13ca4d3d0cdc72a177df3ef03b0e76a3                         |                                                              |
| oldBorrowCap      | VARCHAR   | 96798                                                              |                                                              |
| newBorrowCap      | VARCHAR   | 156530                                                             |                                                              |

## 58. Table: PoolConfigurator\_v3\_event\_BorrowableInIsolationChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-11 10:45:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 25826490                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x72efaa67e38370ae31f31a1d42cfc0cadac47541550a9bae3b065f375326f416 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 36                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x8f3cf7ad23cd3cadbd9735aff958023239c6a063                         |                                                              |
| borrowable        | VARCHAR   | true                                                               |                                                              |

## 59. Table: PoolConfigurator\_v3\_event\_BridgeProtocolFeeUpdated\_history

| Column               | Type      | Example                                                      | Description |
| -------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp     | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number        | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash    | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index           | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address    | VARCHAR   | Address of the contract that produced the log                |             |
| oldBridgeProtocolFee | VARCHAR   |                                                              |             |
| newBridgeProtocolFee | VARCHAR   |                                                              |             |

## 60. Table: PoolConfigurator\_v3\_event\_CollateralConfigurationChanged\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2022-08-29 16:15:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 32453842                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xb59f6b57a14cd0535ade8b75ef29f6ac471dbef6c3fc6f6b54fe566e5928374d | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 281                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset                | VARCHAR   | 0xa3fa99a148fa48d14ed51d610c367c61876997f1                         |                                                              |
| ltv                  | VARCHAR   | 7500                                                               |                                                              |
| liquidationThreshold | VARCHAR   | 8000                                                               |                                                              |
| liquidationBonus     | VARCHAR   | 10500                                                              |                                                              |

## 61. Table: PoolConfigurator\_v3\_event\_DebtCeilingChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-11 10:45:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 25826485                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb13037e0368aeb5fca20112c4a7978052e34109c563908ff7ba4e60af0502128 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 71                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xe111178a87a3bff0c8d18decba5798827539ae99                         |                                                              |
| oldDebtCeiling    | VARCHAR   | 0                                                                  |                                                              |
| newDebtCeiling    | VARCHAR   | 5000000                                                            |                                                              |

## 62. Table: PoolConfigurator\_v3\_event\_EModeAssetCategoryChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-19 21:02:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33316863                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xffd11dcfb6db64df0c6919e15483ca3b09032be9214fef93c5d990f8c95f3ec2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 83                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xfa68fb4628dff1028cfec22b4162fccd0d45efb6                         |                                                              |
| oldCategoryId     | VARCHAR   | 0                                                                  |                                                              |
| newCategoryId     | VARCHAR   | 2                                                                  |                                                              |

## 63. Table: PoolConfigurator\_v3\_event\_EModeCategoryAdded\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2022-09-14 16:26:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 33101585                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x9470258f40ba4cdf5150dcb0aa7a926492357d1e74d1baa180c9c89bf6be28c7 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 176                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| categoryId           | VARCHAR   | 2                                                                  |                                                              |
| ltv                  | VARCHAR   | 9250                                                               |                                                              |
| liquidationThreshold | VARCHAR   | 9500                                                               |                                                              |
| liquidationBonus     | VARCHAR   | 10100                                                              |                                                              |
| oracle               | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| label                | VARCHAR   | MATIC correlated                                                   |                                                              |

## 64. Table: PoolConfigurator\_v3\_event\_FlashloanPremiumToProtocolUpdated\_history

| Column                        | Type      | Example                                                            | Description                                                  |
| ----------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp              | TIMESTAMP | 2023-05-10 13:37:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number                 | INTEGER   | 42535602                                                           | The block number where this event was emitted                |
| transaction\_hash             | VARCHAR   | 0x0967c39ab7306cf2fe43bce0ad6e918ba7aeeee94609b8e76d2401d5df61a994 | Hash of the transactions in which this event was emitted     |
| log\_index                    | INTEGER   | 380                                                                | Integer of the log index position in the block of this event |
| contract\_address             | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| oldFlashloanPremiumToProtocol | VARCHAR   | 0                                                                  |                                                              |
| newFlashloanPremiumToProtocol | VARCHAR   | 4                                                                  |                                                              |

## 65. Table: PoolConfigurator\_v3\_event\_FlashloanPremiumTotalUpdated\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2023-05-10 13:37:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 42535602                                                           | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0x0967c39ab7306cf2fe43bce0ad6e918ba7aeeee94609b8e76d2401d5df61a994 | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 379                                                                | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| oldFlashloanPremiumTotal | VARCHAR   | 9                                                                  |                                                              |
| newFlashloanPremiumTotal | VARCHAR   | 5                                                                  |                                                              |

## 66. Table: PoolConfigurator\_v3\_event\_LiquidationProtocolFeeChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-29 16:15:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 32453842                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb59f6b57a14cd0535ade8b75ef29f6ac471dbef6c3fc6f6b54fe566e5928374d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 279                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xa3fa99a148fa48d14ed51d610c367c61876997f1                         |                                                              |
| oldFee            | VARCHAR   | 0                                                                  |                                                              |
| newFee            | VARCHAR   | 1000                                                               |                                                              |

## 67. Table: PoolConfigurator\_v3\_event\_ReserveActive\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |
| active            | VARCHAR   |                                                              |             |

## 68. Table: PoolConfigurator\_v3\_event\_ReserveBorrowing\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-29 16:15:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 32453842                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb59f6b57a14cd0535ade8b75ef29f6ac471dbef6c3fc6f6b54fe566e5928374d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 276                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xa3fa99a148fa48d14ed51d610c367c61876997f1                         |                                                              |
| enabled           | VARCHAR   | true                                                               |                                                              |

## 69. Table: PoolConfigurator\_v3\_event\_ReserveDropped\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |

## 70. Table: PoolConfigurator\_v3\_event\_ReserveFactorChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-27 20:35:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 40837423                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4e3faf7943112277f1e8b73d6d98c4c05a7ec5153422f9656db78ca761e810a7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 49                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xa3fa99a148fa48d14ed51d610c367c61876997f1                         |                                                              |
| oldReserveFactor  | VARCHAR   | 1000                                                               |                                                              |
| newReserveFactor  | VARCHAR   | 2000                                                               |                                                              |

## 71. Table: PoolConfigurator\_v3\_event\_ReserveFrozen\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-28 08:21:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 38618354                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc1d59453eee08542b977a48d8b095f19ada7e4c98ce99b20a7b922e63d9b3e2a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 303                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x4e3decbb3645551b8a19f0ea1678079fcb33fb4c                         |                                                              |
| frozen            | VARCHAR   | true                                                               |                                                              |

## 72. Table: PoolConfigurator\_v3\_event\_ReserveInitialized\_history

| Column                      | Type      | Example                                                            | Description                                                  |
| --------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp            | TIMESTAMP | 2022-08-29 16:15:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number               | INTEGER   | 32453842                                                           | The block number where this event was emitted                |
| transaction\_hash           | VARCHAR   | 0xb59f6b57a14cd0535ade8b75ef29f6ac471dbef6c3fc6f6b54fe566e5928374d | Hash of the transactions in which this event was emitted     |
| log\_index                  | INTEGER   | 274                                                                | Integer of the log index position in the block of this event |
| contract\_address           | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset                       | VARCHAR   | 0xa3fa99a148fa48d14ed51d610c367c61876997f1                         |                                                              |
| aToken                      | VARCHAR   | 0xebe517846d0f36eced99c735cbf6131e1feb775d                         |                                                              |
| stableDebtToken             | VARCHAR   | 0x687871030477bf974725232f764aa04318a8b9c8                         |                                                              |
| variableDebtToken           | VARCHAR   | 0x18248226c16bf76c032817854e7c83a2113b4f06                         |                                                              |
| interestRateStrategyAddress | VARCHAR   | 0x41b66b4b6b4c9dab039d96528d1b88f7baf8c5a4                         |                                                              |

## 73. Table: PoolConfigurator\_v3\_event\_ReserveInterestRateStrategyChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-24 19:41:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 43102713                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4c469164e15d0c6e787f0ddb46e689a96957b33e6c1740b601b8a0e328dbdf46 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 259                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x85955046df4668e1dd369d2de9f3aeb98dd2a369                         |                                                              |
| oldStrategy       | VARCHAR   | 0x03733f4e008d36f2e37f0080ff1c8df756622e6f                         |                                                              |
| newStrategy       | VARCHAR   | 0xd9d85499449f26d2a2c240defd75314f23920089                         |                                                              |

## 74. Table: PoolConfigurator\_v3\_event\_ReservePaused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-14 19:20:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 25943381                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbb46332f2b7757658e11c2c0dbd09bb449435271213c475722b55ab203e6ef82 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 144                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x53e0bca35ec356bd5dddfebbd1fc0fd03fabad39                         |                                                              |
| paused            | VARCHAR   | true                                                               |                                                              |

## 75. Table: PoolConfigurator\_v3\_event\_ReserveStableRateBorrowing\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-02 15:25:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 42220525                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x026e80d2cad6383b8f1f62993f402e4f03bd7bccad80e013182a2a432ac3365f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 61                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x03b54a6e9a984069379fae1a4fc4dbae93b3bccd                         |                                                              |
| enabled           | VARCHAR   | false                                                              |                                                              |

## 76. Table: PoolConfigurator\_v3\_event\_SiloedBorrowingChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-02 15:25:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 42220525                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x026e80d2cad6383b8f1f62993f402e4f03bd7bccad80e013182a2a432ac3365f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 63                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x03b54a6e9a984069379fae1a4fc4dbae93b3bccd                         |                                                              |
| oldState          | VARCHAR   | false                                                              |                                                              |
| newState          | VARCHAR   | false                                                              |                                                              |

## 77. Table: PoolConfigurator\_v3\_event\_StableDebtTokenUpgraded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-10 13:37:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 42535602                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0967c39ab7306cf2fe43bce0ad6e918ba7aeeee94609b8e76d2401d5df61a994 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 482                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x0b3f868e0be5597d5db7feb59e1cadbb0fdda50a                         |                                                              |
| proxy             | VARCHAR   | 0x78246294a4c6fbf614ed73ccc9f8b875ca8ee841                         |                                                              |
| implementation    | VARCHAR   | 0x50ddd0cd4266299527d25de9cbb55fe0eb8dac30                         |                                                              |

## 78. Table: PoolConfigurator\_v3\_event\_SupplyCapChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-07 21:22:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 43650210                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf462615d7afcce69f371698503187f6e7c007ea15da9f85b9f6d2aad550b0be5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 321                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         |                                                              |
| oldSupplyCap      | VARCHAR   | 90000000                                                           |                                                              |
| newSupplyCap      | VARCHAR   | 105000000                                                          |                                                              |

## 79. Table: PoolConfigurator\_v3\_event\_UnbackedMintCapChanged\_history

| Column             | Type      | Example                                                      | Description |
| ------------------ | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number      | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index         | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address  | VARCHAR   | Address of the contract that produced the log                |             |
| asset              | VARCHAR   |                                                              |             |
| oldUnbackedMintCap | VARCHAR   |                                                              |             |
| newUnbackedMintCap | VARCHAR   |                                                              |             |

## 80. Table: PoolConfigurator\_v3\_event\_VariableDebtTokenUpgraded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-10 13:37:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 42535602                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0967c39ab7306cf2fe43bce0ad6e918ba7aeeee94609b8e76d2401d5df61a994 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 449                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xd6df932a45c0f255f85145f286ea0b292b21c90b                         |                                                              |
| proxy             | VARCHAR   | 0xe80761ea617f66f96274ea5e8c37f03960ecc679                         |                                                              |
| implementation    | VARCHAR   | 0x79b5e91037ae441de0d9e6fd3fd85b96b83d4e93                         |                                                              |

## 81. Table: StableDebtTokenV2\_event\_BorrowAllowanceDelegated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-17 01:36:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29658527                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x52eff13442c5450ee3c96f8a094bfc31e371d5eced0ec9058a93c4860fade7ff | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 276                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2238101b7014c279aaf6b408a284e49cdbd5db55                         | Address of the contract that produced the log                |
| fromUser          | VARCHAR   | 0x09d1b76f745def66c98c30cf4af7a1a352fc28d3                         |                                                              |
| toUser            | VARCHAR   | 0x125d2e4a83bbba4e6f51a244c494f9a1958d20bb                         |                                                              |
| asset             | VARCHAR   | 0x8f3cf7ad23cd3cadbd9735aff958023239c6a063                         |                                                              |
| amount            | VARCHAR   | 45000000000000000000                                               |                                                              |

## 82. Table: StableDebtTokenV2\_event\_Burn\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| user              | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |
| currentBalance    | VARCHAR   |                                                              |             |
| balanceIncrease   | VARCHAR   |                                                              |             |
| avgStableRate     | VARCHAR   |                                                              |             |
| newTotalSupply    | VARCHAR   |                                                              |             |

## 83. Table: StableDebtTokenV2\_event\_Mint\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| user              | VARCHAR   |                                                              |             |
| onBehalfOf        | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |
| currentBalance    | VARCHAR   |                                                              |             |
| balanceIncrease   | VARCHAR   |                                                              |             |
| newRate           | VARCHAR   |                                                              |             |
| avgStableRate     | VARCHAR   |                                                              |             |
| newTotalSupply    | VARCHAR   |                                                              |             |

## 84. Table: StableDebtTokenV2\_event\_Transfer\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| from              | VARCHAR   |                                                              |             |
| to                | VARCHAR   |                                                              |             |
| value             | VARCHAR   |                                                              |             |

## 85. Table: StableDebtToken\_event\_Approval\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| owner             | VARCHAR   |                                                              |             |
| spender           | VARCHAR   |                                                              |             |
| value             | VARCHAR   |                                                              |             |

## 86. Table: StableDebtToken\_event\_BorrowAllowanceDelegated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-06 18:00:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 43605411                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4d4686d9b1c40857915b33b80e4424013ae9f78d50127efac1a30b5f860af00b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 281                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x307ffe186f84a3bc2613d1ea417a5737d69a7007                         | Address of the contract that produced the log                |
| fromUser          | VARCHAR   | 0x03095d365cf2c0ad2e34c805ec5fbe2a6d53e4f5                         |                                                              |
| toUser            | VARCHAR   | 0xba3a2f2abc7610f0e3f0d86b91d5801f694fd563                         |                                                              |
| asset             | VARCHAR   | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                         |                                                              |
| amount            | VARCHAR   | 1000000000000                                                      |                                                              |

## 87. Table: StableDebtToken\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-07 16:26:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 37788998                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x27cbbde3de0925cdcb7bbedca63437c64346b16a251cd983f94a277ca256677b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 288                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x307ffe186f84a3bc2613d1ea417a5737d69a7007                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xef8d414cdc6d075dff0d8855050a2e70f36acebe                         |                                                              |
| amount            | VARCHAR   | 22466342                                                           |                                                              |
| currentBalance    | VARCHAR   | 492804522                                                          |                                                              |
| balanceIncrease   | VARCHAR   | 95                                                                 |                                                              |
| avgStableRate     | VARCHAR   | 52533594086377072541865771                                         |                                                              |
| newTotalSupply    | VARCHAR   | 147702594966                                                       |                                                              |

## 88. Table: StableDebtToken\_event\_Initialized\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2022-08-29 16:15:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 32453842                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xb59f6b57a14cd0535ade8b75ef29f6ac471dbef6c3fc6f6b54fe566e5928374d | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 272                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x687871030477bf974725232f764aa04318a8b9c8                         | Address of the contract that produced the log                |
| underlyingAsset      | VARCHAR   | 0xa3fa99a148fa48d14ed51d610c367c61876997f1                         |                                                              |
| pool                 | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         |                                                              |
| incentivesController | VARCHAR   | 0x929ec64c34a17401f460460d4b9390518e5b473e                         |                                                              |
| debtTokenDecimals    | VARCHAR   | 18                                                                 |                                                              |
| debtTokenName        | VARCHAR   | Aave Polygon Stable Debt MIMATIC                                   |                                                              |
| debtTokenSymbol      | VARCHAR   | stableDebtPolMIMATIC                                               |                                                              |
| params               | VARCHAR   | 0x                                                                 |                                                              |

## 89. Table: StableDebtToken\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-11 14:11:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30605505                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1bd5889273da9dab858fb3ecb492bfe42a1ea5906cc3f75221e081708f25c4da | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 666                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x307ffe186f84a3bc2613d1ea417a5737d69a7007                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x8ae14156e60b1742a9582bd3c41dd16285bfe435                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x8ae14156e60b1742a9582bd3c41dd16285bfe435                         |                                                              |
| amount            | VARCHAR   | 50031654                                                           |                                                              |
| currentBalance    | VARCHAR   | 200031654                                                          |                                                              |
| balanceIncrease   | VARCHAR   | 31654                                                              |                                                              |
| newRate           | VARCHAR   | 52214099875402232070984100                                         |                                                              |
| avgStableRate     | VARCHAR   | 53264751330477180091023732                                         |                                                              |
| newTotalSupply    | VARCHAR   | 149931922299                                                       |                                                              |

## 90. Table: StableDebtToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-11 20:14:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 44962676                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc8ecd3b1ace23cb2a08b9f32f6562917e34a8f7a11a803d5b0d7458ec0968c01 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 78                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x307ffe186f84a3bc2613d1ea417a5737d69a7007                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x377192fe303667d4037c997e02cb8c377593c2d0                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 33835818                                                           |                                                              |

## 91. Table: VariableDebtTokenV2\_event\_BorrowAllowanceDelegated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-11 22:10:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 24829008                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcc69e738fe09eb60d14ce5e822de192d549e1beabaad8e66380824e61ec8d046 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 144                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x248960a9d75edfa3de94f7193eae3161eb349a12                         | Address of the contract that produced the log                |
| fromUser          | VARCHAR   | 0xd41908f92e29387babc3861d76b9504d7f18bf4e                         |                                                              |
| toUser            | VARCHAR   | 0x125d2e4a83bbba4e6f51a244c494f9a1958d20bb                         |                                                              |
| asset             | VARCHAR   | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                         |                                                              |
| amount            | VARCHAR   | 0                                                                  |                                                              |

## 92. Table: VariableDebtTokenV2\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-04 02:43:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 38884512                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7df4fb376c976755682a870777dc9561ee2d923d9216489e2198bffbc2b6940c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 280                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf664f50631a6f0d72ecdaa0e49b0c019fa72a8dc                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xfe4513281d4370c5e565d1829210c86c9cfae95b                         |                                                              |
| amount            | VARCHAR   | 7641397                                                            |                                                              |
| index             | VARCHAR   | 1017458338264153276860346720                                       |                                                              |

## 93. Table: VariableDebtTokenV2\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-29 02:04:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30119564                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x60064c9fac86b9cb24aea78a6cbd6d36e7393a09d745a5a786409508816709a6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 167                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x248960a9d75edfa3de94f7193eae3161eb349a12                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0624c3f446240427362146f75acf549afb042ebd                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x0624c3f446240427362146f75acf549afb042ebd                         |                                                              |
| value             | VARCHAR   | 22581704                                                           |                                                              |
| index             | VARCHAR   | 1049819564076128139007145768                                       |                                                              |

## 94. Table: VariableDebtTokenV2\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-07 02:39:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 24639587                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1c474a354760f139935ccdca3f6045549ce0b7569cf0d1d537d0e2e930febd39 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 120                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x248960a9d75edfa3de94f7193eae3161eb349a12                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xfa05e80c2c032ca91014951120457b00a7572312                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 400602070                                                          |                                                              |

## 95. Table: VariableDebtToken\_event\_Approval\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| owner             | VARCHAR   |                                                              |             |
| spender           | VARCHAR   |                                                              |             |
| value             | VARCHAR   |                                                              |             |

## 96. Table: VariableDebtToken\_event\_BorrowAllowanceDelegated\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-07 23:00:35+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 37799776                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2e9f01d7a88012dccfdeddfe1884b5a512526147476d54ffc4ecc502dbbe47c7             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 149                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0c84331e39d6658cd6e6b9ba04736cc4c4734351                                     | Address of the contract that produced the log                |
| fromUser          | VARCHAR   | 0xda174bb98ffe276712e18c0b131f51692a2ab2d5                                     |                                                              |
| toUser            | VARCHAR   | 0xd061418b66c7b96915634d231039186be3ecce15                                     |                                                              |
| asset             | VARCHAR   | 0x7ceb23fd6bc0add59e62ac25578270cff1b9f619                                     |                                                              |
| amount            | VARCHAR   | 115792089237316195423570985008687907853269984665640563986769628561790669955895 |                                                              |

## 97. Table: VariableDebtToken\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-09 00:22:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 31676845                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9d50024a48808070a3f45b7c9d5bbf8ddef842f2dd52f46bdcf6f70a98fcc60d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 546                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x92b42c66840c7ad907b4bf74879ff3ef7c529473                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xbc2131b75c5c634a20e14239c34fc6102abded00                         |                                                              |
| target            | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 5002                                                               |                                                              |
| balanceIncrease   | VARCHAR   | 0                                                                  |                                                              |
| index             | VARCHAR   | 1001865778891829037209601113                                       |                                                              |

## 98. Table: VariableDebtToken\_event\_Initialized\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2022-09-19 21:02:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 33316863                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xffd11dcfb6db64df0c6919e15483ca3b09032be9214fef93c5d990f8c95f3ec2 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 77                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0xb5b46f918c2923fc7f26db76e8a6a6e9c4347cf9                         | Address of the contract that produced the log                |
| underlyingAsset      | VARCHAR   | 0xfa68fb4628dff1028cfec22b4162fccd0d45efb6                         |                                                              |
| pool                 | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         |                                                              |
| incentivesController | VARCHAR   | 0x929ec64c34a17401f460460d4b9390518e5b473e                         |                                                              |
| debtTokenDecimals    | VARCHAR   | 18                                                                 |                                                              |
| debtTokenName        | VARCHAR   | Aave Polygon Variable Debt MATICX                                  |                                                              |
| debtTokenSymbol      | VARCHAR   | variableDebtPolMATICX                                              |                                                              |
| params               | VARCHAR   | 0x                                                                 |                                                              |

## 99. Table: VariableDebtToken\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-13 10:05:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29513153                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x496513c22cdcca04c9efad9e49d4ade64d2952d370c32bdefe3089fe4746ae6f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 562                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0c84331e39d6658cd6e6b9ba04736cc4c4734351                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x01732178fe9411f1b46b526e5d52ed958ac0027e                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x01732178fe9411f1b46b526e5d52ed958ac0027e                         |                                                              |
| value             | VARCHAR   | 150000000000000000                                                 |                                                              |
| balanceIncrease   | VARCHAR   | 0                                                                  |                                                              |
| index             | VARCHAR   | 1001308547795735816395442706                                       |                                                              |

## 100. Table: VariableDebtToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-29 02:30:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30120263                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4875b3f83b5b13ad9686790bd134134eafa0d386ddfbb02af69fdc8e9eb49efa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 175                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0c84331e39d6658cd6e6b9ba04736cc4c4734351                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xda174bb98ffe276712e18c0b131f51692a2ab2d5                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 25421124662012070                                                  |                                                              |
