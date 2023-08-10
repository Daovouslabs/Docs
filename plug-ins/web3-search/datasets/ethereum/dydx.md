# dydx

## 1. Table: AdminImpl\_event\_LogAddMarket\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-04-16 00:27:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7575724                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb8c965c5f03691676304b7e89475522e82f4c796f3676b1d8a987478a393731e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 9                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1e0447b19bb6ecfdae1e4ae1694b0c3659614e4e                         | Address of the contract that produced the log                |
| marketId          | VARCHAR   | 0                                                                  |                                                              |
| token             | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |

## 2. Table: AdminImpl\_event\_LogSetEarningsRate\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2019-06-14 01:05:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 7953727                                                            | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x40da5512c355377764b45e1e55abbf395b92840edbb79068a32b676e7cd1686e | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 91                                                                 | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x1e0447b19bb6ecfdae1e4ae1694b0c3659614e4e                         | Address of the contract that produced the log                |
| earningsRate       | STRUCT    | {'value': '900000000000000000'}                                    |                                                              |
| earningsRate.value | VARCHAR   | 900000000000000000                                                 |                                                              |

## 3. Table: AdminImpl\_event\_LogSetGlobalOperator\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-17 00:50:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8755515                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x23eaa52199afbb2590d878f3cdbc4e7a614c51476f4cdd771c196f66acd8098e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 84                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1e0447b19bb6ecfdae1e4ae1694b0c3659614e4e                         | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0x0ece224fbc24d40b446c6a94a142dc41fae76f2d                         |                                                              |
| approved          | VARCHAR   | false                                                              |                                                              |

## 4. Table: AdminImpl\_event\_LogSetInterestSetter\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-04-16 00:27:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7575724                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb8c965c5f03691676304b7e89475522e82f4c796f3676b1d8a987478a393731e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 11                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1e0447b19bb6ecfdae1e4ae1694b0c3659614e4e                         | Address of the contract that produced the log                |
| marketId          | VARCHAR   | 0                                                                  |                                                              |
| interestSetter    | VARCHAR   | 0xad91a0ddf799176a0a87a32dafe8f3dd28479918                         |                                                              |

## 5. Table: AdminImpl\_event\_LogSetIsClosing\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-27 21:39:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9012020                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x21309a50f821648df8b2f14941bb8fadb37f7a0703aa3ac6fbf8ae7171e84d00 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 99                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1e0447b19bb6ecfdae1e4ae1694b0c3659614e4e                         | Address of the contract that produced the log                |
| marketId          | VARCHAR   | 3                                                                  |                                                              |
| isClosing         | VARCHAR   | false                                                              |                                                              |

## 6. Table: AdminImpl\_event\_LogSetLiquidationSpread\_history

| Column                  | Type      | Example                                                      | Description |
| ----------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp        | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number           | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash       | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index              | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address       | VARCHAR   | Address of the contract that produced the log                |             |
| liquidationSpread       | STRUCT    |                                                              |             |
| liquidationSpread.value | VARCHAR   |                                                              |             |

## 7. Table: AdminImpl\_event\_LogSetMarginPremium\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2019-04-16 00:27:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 7575724                                                            | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xb8c965c5f03691676304b7e89475522e82f4c796f3676b1d8a987478a393731e | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 12                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x1e0447b19bb6ecfdae1e4ae1694b0c3659614e4e                         | Address of the contract that produced the log                |
| marketId            | VARCHAR   | 0                                                                  |                                                              |
| marginPremium       | STRUCT    | {'value': '0'}                                                     |                                                              |
| marginPremium.value | VARCHAR   | 0                                                                  |                                                              |

## 8. Table: AdminImpl\_event\_LogSetMarginRatio\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| marginRatio       | STRUCT    |                                                              |             |
| marginRatio.value | VARCHAR   |                                                              |             |

## 9. Table: AdminImpl\_event\_LogSetMinBorrowedValue\_history

| Column                 | Type      | Example                                                      | Description |
| ---------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp       | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number          | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash      | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index             | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address      | VARCHAR   | Address of the contract that produced the log                |             |
| minBorrowedValue       | STRUCT    |                                                              |             |
| minBorrowedValue.value | VARCHAR   |                                                              |             |

## 10. Table: AdminImpl\_event\_LogSetPriceOracle\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-27 20:54:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9011821                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd5291213c339c51c5c6e45309db0a2b34982a7e0b62b420d62a3daebdf956d6f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 86                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1e0447b19bb6ecfdae1e4ae1694b0c3659614e4e                         | Address of the contract that produced the log                |
| marketId          | VARCHAR   | 3                                                                  |                                                              |
| priceOracle       | VARCHAR   | 0xccfcf083335633c48e99872899586113a2bd08d8                         |                                                              |

## 11. Table: AdminImpl\_event\_LogSetSpreadPremium\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2019-11-25 17:08:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 8999674                                                            | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xc6f543228c662bfbffb54aa62049a0bd9f7b60eafafcf6cfcabff3eb466c9acd | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x1e0447b19bb6ecfdae1e4ae1694b0c3659614e4e                         | Address of the contract that produced the log                |
| marketId            | VARCHAR   | 3                                                                  |                                                              |
| spreadPremium       | STRUCT    | {'value': '0'}                                                     |                                                              |
| spreadPremium.value | VARCHAR   | 0                                                                  |                                                              |

## 12. Table: AdminImpl\_event\_LogWithdrawExcessTokens\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-12 20:57:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9096410                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2541d3fb4649822e487a8fa8f855c519c3476558ef295871c933be62e6c3c0ae | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 32                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1e0447b19bb6ecfdae1e4ae1694b0c3659614e4e                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x89d24a6b4ccb1b6faa2625fe562bdd9a23260359                         |                                                              |
| amount            | VARCHAR   | 35066200478518583764943                                            |                                                              |

## 13. Table: GpsStatementVerifier\_event\_LogMemoryPagesHashes\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-29 21:14:59+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17154344                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x36686cf44e5c9aaf9e3d6a9013e49fa2da1218a3b47205bdc4d9e22543da7a82                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 293                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x894c4a12548fb18eaa48cf34f9cd874fc08b7fc3                                                           | Address of the contract that produced the log                |
| factHash          | VARCHAR   | 0x4e6490098de8dc902303639032b1dcd76f47570e2ffedd692a124c64f7bbac74                                   |                                                              |
| pagesHashes       | VARCHAR   | 0x3946bd3e41d4adc9ce4b1c2333b1337529e94518353a1d971dcdc53bb47726d9,0x39ea79c93833880363aab76bd2d42c5 |                                                              |

## 14. Table: PerpetualV1\_event\_LogAccountSettled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-19 13:59:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12270912                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa92b28f18b2f8aa3d56d7076bdb57d46ae026ede3b1441e10ac15adecabc1034 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 190                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x07abe965500a49370d331ecd613c7ac47dd6e547                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x000018bbb8df8de9e3eaf772db1c4eec228ef06c                         |                                                              |
| isPositive        | VARCHAR   | true                                                               |                                                              |
| amount            | VARCHAR   | 41364217                                                           |                                                              |
| balance           | VARCHAR   | 0x01000000000000000000030e08e03b620000000000000000000000008dea81b0 |                                                              |

## 15. Table: PerpetualV1\_event\_LogDeposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-21 12:11:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11698705                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc9479bc55570fa758aa8961ef4d7f4ed1741aeb162a67d3d3a3755f6fb0b461c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 110                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x07abe965500a49370d331ecd613c7ac47dd6e547                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x8d47c90dbd7dba1e013c6efca10af7112cf3d27d                         |                                                              |
| amount            | VARCHAR   | 0                                                                  |                                                              |
| balance           | VARCHAR   | 0x010000000000000000000039916d43d100000000000000000000000000000000 |                                                              |

## 16. Table: PerpetualV1\_event\_LogIndex\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-07 08:20:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11990238                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd5c98e80c594685593d1ddac1907f1dd768fe9c82e30eb6f723744e6b8cc87b3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 65                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x07abe965500a49370d331ecd613c7ac47dd6e547                         | Address of the contract that produced the log                |
| index             | VARCHAR   | 0x000000000000000000000060448cca010000000000000006cfd9fd8f81a3a660 |                                                              |

## 17. Table: PerpetualV1\_event\_LogSetGlobalOperator\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-20 04:24:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10100645                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7c1da7a4b04389ff9329a7656448245607022ecf8d94264ba9449249936af0dc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 118                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x07abe965500a49370d331ecd613c7ac47dd6e547                         | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0xa4e4a9ae84882be5049e450a3500ba1cd012f0c5                         |                                                              |
| approved          | VARCHAR   | true                                                               |                                                              |

## 18. Table: PerpetualV1\_event\_LogSetMinCollateral\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-23 22:25:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9931390                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x69f3b61d2390ccafc5855d3e4b9984e3e58d1f6d9739faacd8190313b51bf158 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 8                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x07abe965500a49370d331ecd613c7ac47dd6e547                         | Address of the contract that produced the log                |
| minCollateral     | VARCHAR   | 1075000000000000000                                                |                                                              |

## 19. Table: PerpetualV1\_event\_LogSetOracle\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-17 19:20:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9891792                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf1ea0d871606806734dcb99c38e9ae3c59da18ee82b7d0c56a6f0bbc2c771480 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 36                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x07abe965500a49370d331ecd613c7ac47dd6e547                         | Address of the contract that produced the log                |
| oracle            | VARCHAR   | 0x538038e526517680735568f9c5342c6e68bbda12                         |                                                              |

## 20. Table: PerpetualV1\_event\_LogTrade\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-07 21:20:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10414737                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xda098bcbcbe1d42758fc9d63190cd0198e937b57dfc77da8eb6dcae801aeebe5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 162                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x07abe965500a49370d331ecd613c7ac47dd6e547                         | Address of the contract that produced the log                |
| maker             | VARCHAR   | 0xd1407f8be4054ad94d515740dd6d05215eade4fd                         |                                                              |
| taker             | VARCHAR   | 0xf809e07870dca762b9536d61a4fbef1a17178092                         |                                                              |
| trader            | VARCHAR   | 0x3ea6f88ec8f7b24bb3ad206fa80124210e8e28f3                         |                                                              |
| marginAmount      | VARCHAR   | 92376900                                                           |                                                              |
| positionAmount    | VARCHAR   | 1000000                                                            |                                                              |
| isBuy             | VARCHAR   | false                                                              |                                                              |
| makerBalance      | VARCHAR   | 0x010000000000000000000000661ab4fa00000000000000000000000000a7d8c0 |                                                              |
| takerBalance      | VARCHAR   | 0x010000000000000000000000660bc41c00000000000000000000000000000000 |                                                              |

## 21. Table: PerpetualV1\_event\_LogWithdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-10 15:43:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11829648                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc9f96a6c35dcd33246df052a3524b0ac41aea7c0cfb659eecb459d702e1c57cf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 209                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x07abe965500a49370d331ecd613c7ac47dd6e547                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xe00e146a5946cacc67d1db5eeb49d9c15e77fe05                         |                                                              |
| destination       | VARCHAR   | 0xe00e146a5946cacc67d1db5eeb49d9c15e77fe05                         |                                                              |
| amount            | VARCHAR   | 79105597747                                                        |                                                              |
| balance           | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000 |                                                              |

## 22. Table: SoloMargin\_event\_LogBuy\_history

| Column                     | Type                                                                                            | Example                                                                                              | Description                                                  |
| -------------------------- | ----------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp           | TIMESTAMP                                                                                       | 2019-06-02 12:56:17+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number              | INTEGER                                                                                         | 7880207                                                                                              | The block number where this event was emitted                |
| transaction\_hash          | VARCHAR                                                                                         | 0x915f204127d8ea6a2c68b8dcdd1c1d952d785dad1309c23c748806c19c6e81f0                                   | Hash of the transactions in which this event was emitted     |
| log\_index                 | INTEGER                                                                                         | 47                                                                                                   | Integer of the log index position in the block of this event |
| contract\_address          | VARCHAR                                                                                         | 0x1e0447b19bb6ecfdae1e4ae1694b0c3659614e4e                                                           | Address of the contract that produced the log                |
| accountOwner               | VARCHAR                                                                                         | 0x1bc8b83c3a396a1a6bed44d1a1784210d3944178                                                           |                                                              |
| accountNumber              | VARCHAR                                                                                         | 87469494321515339936297030496415715866830255027663677939709341577609860541891                        |                                                              |
| takerMarket                | VARCHAR                                                                                         | 0                                                                                                    |                                                              |
| makerMarket                | VARCHAR                                                                                         | 1                                                                                                    |                                                              |
| takerUpdate                | STRUCT\<deltaWei STRUCT\<sign STRING, value STRING>, newPar STRUCT\<sign STRING, value STRING>> | {'deltaWei': {'sign': 'false', 'value': '30311251109228171276'}, 'newPar': {'sign': 'true', 'value': |                                                              |
| takerUpdate.deltaWei       | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'false', 'value': '30311251109228171276'}                                                   | None                                                         |
| takerUpdate.deltaWei.sign  | VARCHAR                                                                                         | false                                                                                                | None                                                         |
| takerUpdate.deltaWei.value | VARCHAR                                                                                         | 30311251109228171276                                                                                 | None                                                         |
| takerUpdate.newPar         | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'true', 'value': '13530527696374971235'}                                                    | None                                                         |
| takerUpdate.newPar.sign    | VARCHAR                                                                                         | true                                                                                                 | None                                                         |
| takerUpdate.newPar.value   | VARCHAR                                                                                         | 13530527696374971235                                                                                 | None                                                         |
| makerUpdate                | STRUCT\<deltaWei STRUCT\<sign STRING, value STRING>, newPar STRUCT\<sign STRING, value STRING>> | {'deltaWei': {'sign': 'true', 'value': '8258085528630252475524'}, 'newPar': {'sign': 'false', 'value |                                                              |
| makerUpdate.deltaWei       | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'true', 'value': '8258085528630252475524'}                                                  | None                                                         |
| makerUpdate.deltaWei.sign  | VARCHAR                                                                                         | true                                                                                                 | None                                                         |
| makerUpdate.deltaWei.value | VARCHAR                                                                                         | 8258085528630252475524                                                                               | None                                                         |
| makerUpdate.newPar         | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'false', 'value': '0'}                                                                      | None                                                         |
| makerUpdate.newPar.sign    | VARCHAR                                                                                         | false                                                                                                | None                                                         |
| makerUpdate.newPar.value   | VARCHAR                                                                                         | 0                                                                                                    | None                                                         |
| exchangeWrapper            | VARCHAR                                                                                         | 0xab33e884ec8fed4f5867246e4300228f3d666561                                                           |                                                              |

## 23. Table: SoloMargin\_event\_LogDeposit\_history

| Column                | Type                                                                                            | Example                                                                                              | Description                                                  |
| --------------------- | ----------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp      | TIMESTAMP                                                                                       | 2020-06-30 19:28:24+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number         | INTEGER                                                                                         | 10369007                                                                                             | The block number where this event was emitted                |
| transaction\_hash     | VARCHAR                                                                                         | 0x75f9af6af6a9844717a418bf3c6208a46b85f70c90c53f80f226f7858d6baea1                                   | Hash of the transactions in which this event was emitted     |
| log\_index            | INTEGER                                                                                         | 168                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address     | VARCHAR                                                                                         | 0x1e0447b19bb6ecfdae1e4ae1694b0c3659614e4e                                                           | Address of the contract that produced the log                |
| accountOwner          | VARCHAR                                                                                         | 0x000f7f22bfc28d940d4b68e13213ab17cf107790                                                           |                                                              |
| accountNumber         | VARCHAR                                                                                         | 0                                                                                                    |                                                              |
| market                | VARCHAR                                                                                         | 2                                                                                                    |                                                              |
| update                | STRUCT\<deltaWei STRUCT\<sign STRING, value STRING>, newPar STRUCT\<sign STRING, value STRING>> | {'deltaWei': {'sign': 'true', 'value': '100736938650'}, 'newPar': {'sign': 'false', 'value': '189897 |                                                              |
| update.deltaWei       | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'true', 'value': '100736938650'}                                                            | None                                                         |
| update.deltaWei.sign  | VARCHAR                                                                                         | true                                                                                                 | None                                                         |
| update.deltaWei.value | VARCHAR                                                                                         | 100736938650                                                                                         | None                                                         |
| update.newPar         | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'false', 'value': '189897658436'}                                                           | None                                                         |
| update.newPar.sign    | VARCHAR                                                                                         | false                                                                                                | None                                                         |
| update.newPar.value   | VARCHAR                                                                                         | 189897658436                                                                                         | None                                                         |
| from                  | VARCHAR                                                                                         | 0x000f7f22bfc28d940d4b68e13213ab17cf107790                                                           |                                                              |

## 24. Table: SoloMargin\_event\_LogIndexUpdate\_history

| Column            | Type                                                     | Example                                                                                        | Description                                                  |
| ----------------- | -------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP                                                | 2020-08-19 00:02:01+00:00                                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER                                                  | 10687197                                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR                                                  | 0xd520ba79d88bac997ec209b8edd930bf4a62fd7cae5d6991d5022ed43b7221e1                             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER                                                  | 2                                                                                              | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR                                                  | 0x1e0447b19bb6ecfdae1e4ae1694b0c3659614e4e                                                     | Address of the contract that produced the log                |
| market            | VARCHAR                                                  | 0                                                                                              |                                                              |
| index             | STRUCT\<borrow STRING, supply STRING, lastUpdate STRING> | {'borrow': '1013584123756755334', 'supply': '1001833128912685888', 'lastUpdate': '1597795321'} |                                                              |
| index.borrow      | VARCHAR                                                  | 1013584123756755334                                                                            |                                                              |
| index.supply      | VARCHAR                                                  | 1001833128912685888                                                                            |                                                              |
| index.lastUpdate  | VARCHAR                                                  | 1597795321                                                                                     |                                                              |

## 25. Table: SoloMargin\_event\_LogLiquidate\_history

| Column                          | Type                                                                                            | Example                                                                                               | Description                                                  |
| ------------------------------- | ----------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp                | TIMESTAMP                                                                                       | 2020-04-06 16:05:39+00:00                                                                             | Timestamp of the block where this event was emitted          |
| block\_number                   | INTEGER                                                                                         | 9819490                                                                                               | The block number where this event was emitted                |
| transaction\_hash               | VARCHAR                                                                                         | 0x3465e8eb4f304f5ed89e6d92c27915f744ed5eb9e8b745a832d7fa305a860b33                                    | Hash of the transactions in which this event was emitted     |
| log\_index                      | INTEGER                                                                                         | 14                                                                                                    | Integer of the log index position in the block of this event |
| contract\_address               | VARCHAR                                                                                         | 0x1e0447b19bb6ecfdae1e4ae1694b0c3659614e4e                                                            | Address of the contract that produced the log                |
| solidAccountOwner               | VARCHAR                                                                                         | 0x0f3c2476fbf0ed09dff00ea7f4ef252dcc72e6f1                                                            |                                                              |
| solidAccountNumber              | VARCHAR                                                                                         | 0                                                                                                     |                                                              |
| liquidAccountOwner              | VARCHAR                                                                                         | 0xbe443647eb1d578974c6190d8ff5f6f4f4f8175c                                                            |                                                              |
| liquidAccountNumber             | VARCHAR                                                                                         | 573131397700860086296635778721714254178412178008741246766887130215688309221                           |                                                              |
| heldMarket                      | VARCHAR                                                                                         | 3                                                                                                     |                                                              |
| owedMarket                      | VARCHAR                                                                                         | 0                                                                                                     |                                                              |
| solidHeldUpdate                 | STRUCT\<deltaWei STRUCT\<sign STRING, value STRING>, newPar STRUCT\<sign STRING, value STRING>> | {'deltaWei': {'sign': 'true', 'value': '13040408312092691'}, 'newPar': {'sign': 'true', 'value': '12  |                                                              |
| solidHeldUpdate.deltaWei        | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'true', 'value': '13040408312092691'}                                                        | None                                                         |
| solidHeldUpdate.deltaWei.sign   | VARCHAR                                                                                         | true                                                                                                  | None                                                         |
| solidHeldUpdate.deltaWei.value  | VARCHAR                                                                                         | 13040408312092691                                                                                     | None                                                         |
| solidHeldUpdate.newPar          | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'true', 'value': '12782351262070785'}                                                        | None                                                         |
| solidHeldUpdate.newPar.sign     | VARCHAR                                                                                         | true                                                                                                  | None                                                         |
| solidHeldUpdate.newPar.value    | VARCHAR                                                                                         | 12782351262070785                                                                                     | None                                                         |
| solidOwedUpdate                 | STRUCT\<deltaWei STRUCT\<sign STRING, value STRING>, newPar STRUCT\<sign STRING, value STRING>> | {'deltaWei': {'sign': 'false', 'value': '77446797752917'}, 'newPar': {'sign': 'true', 'value': '1608  |                                                              |
| solidOwedUpdate.deltaWei        | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'false', 'value': '77446797752917'}                                                          | None                                                         |
| solidOwedUpdate.deltaWei.sign   | VARCHAR                                                                                         | false                                                                                                 | None                                                         |
| solidOwedUpdate.deltaWei.value  | VARCHAR                                                                                         | 77446797752917                                                                                        | None                                                         |
| solidOwedUpdate.newPar          | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'true', 'value': '160828090779760801625'}                                                    | None                                                         |
| solidOwedUpdate.newPar.sign     | VARCHAR                                                                                         | true                                                                                                  | None                                                         |
| solidOwedUpdate.newPar.value    | VARCHAR                                                                                         | 160828090779760801625                                                                                 | None                                                         |
| liquidHeldUpdate                | STRUCT\<deltaWei STRUCT\<sign STRING, value STRING>, newPar STRUCT\<sign STRING, value STRING>> | {'deltaWei': {'sign': 'false', 'value': '13040408312092691'}, 'newPar': {'sign': 'true', 'value': '1  |                                                              |
| liquidHeldUpdate.deltaWei       | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'false', 'value': '13040408312092691'}                                                       | None                                                         |
| liquidHeldUpdate.deltaWei.sign  | VARCHAR                                                                                         | false                                                                                                 | None                                                         |
| liquidHeldUpdate.deltaWei.value | VARCHAR                                                                                         | 13040408312092691                                                                                     | None                                                         |
| liquidHeldUpdate.newPar         | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'true', 'value': '1536920285849927306004'}                                                   | None                                                         |
| liquidHeldUpdate.newPar.sign    | VARCHAR                                                                                         | true                                                                                                  | None                                                         |
| liquidHeldUpdate.newPar.value   | VARCHAR                                                                                         | 1536920285849927306004                                                                                | None                                                         |
| liquidOwedUpdate                | STRUCT\<deltaWei STRUCT\<sign STRING, value STRING>, newPar STRUCT\<sign STRING, value STRING>> | {'deltaWei': {'sign': 'true', 'value': '77446797752917'}, 'newPar': {'sign': 'false', 'value': '0'\}} |                                                              |
| liquidOwedUpdate.deltaWei       | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'true', 'value': '77446797752917'}                                                           | None                                                         |
| liquidOwedUpdate.deltaWei.sign  | VARCHAR                                                                                         | true                                                                                                  | None                                                         |
| liquidOwedUpdate.deltaWei.value | VARCHAR                                                                                         | 77446797752917                                                                                        | None                                                         |
| liquidOwedUpdate.newPar         | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'false', 'value': '0'}                                                                       | None                                                         |
| liquidOwedUpdate.newPar.sign    | VARCHAR                                                                                         | false                                                                                                 | None                                                         |
| liquidOwedUpdate.newPar.value   | VARCHAR                                                                                         | 0                                                                                                     | None                                                         |

## 26. Table: SoloMargin\_event\_LogSell\_history

| Column                     | Type                                                                                            | Example                                                                                              | Description                                                  |
| -------------------------- | ----------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp           | TIMESTAMP                                                                                       | 2019-04-24 17:17:16+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number              | INTEGER                                                                                         | 7631370                                                                                              | The block number where this event was emitted                |
| transaction\_hash          | VARCHAR                                                                                         | 0xb1a96f1f309dae4118aa0b5cb5988b8cc7ec9b2ec2326943ca01ac4f3628acae                                   | Hash of the transactions in which this event was emitted     |
| log\_index                 | INTEGER                                                                                         | 90                                                                                                   | Integer of the log index position in the block of this event |
| contract\_address          | VARCHAR                                                                                         | 0x1e0447b19bb6ecfdae1e4ae1694b0c3659614e4e                                                           | Address of the contract that produced the log                |
| accountOwner               | VARCHAR                                                                                         | 0x8b15f5c268ad121d863ce77bfcac5a607bd0e129                                                           |                                                              |
| accountNumber              | VARCHAR                                                                                         | 71039613658218446138769319844852555150546254223777522692865202944350033776711                        |                                                              |
| takerMarket                | VARCHAR                                                                                         | 0                                                                                                    |                                                              |
| makerMarket                | VARCHAR                                                                                         | 1                                                                                                    |                                                              |
| takerUpdate                | STRUCT\<deltaWei STRUCT\<sign STRING, value STRING>, newPar STRUCT\<sign STRING, value STRING>> | {'deltaWei': {'sign': 'false', 'value': '1168700000000000000'}, 'newPar': {'sign': 'false', 'value': |                                                              |
| takerUpdate.deltaWei       | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'false', 'value': '1168700000000000000'}                                                    | None                                                         |
| takerUpdate.deltaWei.sign  | VARCHAR                                                                                         | false                                                                                                | None                                                         |
| takerUpdate.deltaWei.value | VARCHAR                                                                                         | 1168700000000000000                                                                                  | None                                                         |
| takerUpdate.newPar         | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'false', 'value': '1168673214083452100'}                                                    | None                                                         |
| takerUpdate.newPar.sign    | VARCHAR                                                                                         | false                                                                                                | None                                                         |
| takerUpdate.newPar.value   | VARCHAR                                                                                         | 1168673214083452100                                                                                  | None                                                         |
| makerUpdate                | STRUCT\<deltaWei STRUCT\<sign STRING, value STRING>, newPar STRUCT\<sign STRING, value STRING>> | {'deltaWei': {'sign': 'true', 'value': '196055989999999999802'}, 'newPar': {'sign': 'true', 'value': |                                                              |
| makerUpdate.deltaWei       | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'true', 'value': '196055989999999999802'}                                                   | None                                                         |
| makerUpdate.deltaWei.sign  | VARCHAR                                                                                         | true                                                                                                 | None                                                         |
| makerUpdate.deltaWei.value | VARCHAR                                                                                         | 196055989999999999802                                                                                | None                                                         |
| makerUpdate.newPar         | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'true', 'value': '392215652883577591865'}                                                   | None                                                         |
| makerUpdate.newPar.sign    | VARCHAR                                                                                         | true                                                                                                 | None                                                         |
| makerUpdate.newPar.value   | VARCHAR                                                                                         | 392215652883577591865                                                                                | None                                                         |
| exchangeWrapper            | VARCHAR                                                                                         | 0xab33e884ec8fed4f5867246e4300228f3d666561                                                           |                                                              |

## 27. Table: SoloMargin\_event\_LogTrade\_history

| Column                           | Type                                                                                            | Example                                                                                              | Description                                                  |
| -------------------------------- | ----------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp                 | TIMESTAMP                                                                                       | 2021-07-27 08:18:14+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number                    | INTEGER                                                                                         | 12907033                                                                                             | The block number where this event was emitted                |
| transaction\_hash                | VARCHAR                                                                                         | 0x5c04d94019fc5a322f58ad3df7def28e110fd1e8c3cbed570a3039f3aa9eac11                                   | Hash of the transactions in which this event was emitted     |
| log\_index                       | INTEGER                                                                                         | 330                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address                | VARCHAR                                                                                         | 0x1e0447b19bb6ecfdae1e4ae1694b0c3659614e4e                                                           | Address of the contract that produced the log                |
| takerAccountOwner                | VARCHAR                                                                                         | 0xf809e07870dca762b9536d61a4fbef1a17178092                                                           |                                                              |
| takerAccountNumber               | VARCHAR                                                                                         | 0                                                                                                    |                                                              |
| makerAccountOwner                | VARCHAR                                                                                         | 0x231a07c825f052b895de5fd1513ce40d18e14af5                                                           |                                                              |
| makerAccountNumber               | VARCHAR                                                                                         | 86034289416643458232340245104445646347906692444544269750983903137313255842754                        |                                                              |
| inputMarket                      | VARCHAR                                                                                         | 2                                                                                                    |                                                              |
| outputMarket                     | VARCHAR                                                                                         | 0                                                                                                    |                                                              |
| takerInputUpdate                 | STRUCT\<deltaWei STRUCT\<sign STRING, value STRING>, newPar STRUCT\<sign STRING, value STRING>> | {'deltaWei': {'sign': 'false', 'value': '131970506340'}, 'newPar': {'sign': 'false', 'value': '18594 |                                                              |
| takerInputUpdate.deltaWei        | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'false', 'value': '131970506340'}                                                           | None                                                         |
| takerInputUpdate.deltaWei.sign   | VARCHAR                                                                                         | false                                                                                                | None                                                         |
| takerInputUpdate.deltaWei.value  | VARCHAR                                                                                         | 131970506340                                                                                         | None                                                         |
| takerInputUpdate.newPar          | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'false', 'value': '1859472383'}                                                             | None                                                         |
| takerInputUpdate.newPar.sign     | VARCHAR                                                                                         | false                                                                                                | None                                                         |
| takerInputUpdate.newPar.value    | VARCHAR                                                                                         | 1859472383                                                                                           | None                                                         |
| takerOutputUpdate                | STRUCT\<deltaWei STRUCT\<sign STRING, value STRING>, newPar STRUCT\<sign STRING, value STRING>> | {'deltaWei': {'sign': 'true', 'value': '59758377633243690224'}, 'newPar': {'sign': 'true', 'value':  |                                                              |
| takerOutputUpdate.deltaWei       | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'true', 'value': '59758377633243690224'}                                                    | None                                                         |
| takerOutputUpdate.deltaWei.sign  | VARCHAR                                                                                         | true                                                                                                 | None                                                         |
| takerOutputUpdate.deltaWei.value | VARCHAR                                                                                         | 59758377633243690224                                                                                 | None                                                         |
| takerOutputUpdate.newPar         | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'true', 'value': '66783174902531630804'}                                                    | None                                                         |
| takerOutputUpdate.newPar.sign    | VARCHAR                                                                                         | true                                                                                                 | None                                                         |
| takerOutputUpdate.newPar.value   | VARCHAR                                                                                         | 66783174902531630804                                                                                 | None                                                         |
| makerInputUpdate                 | STRUCT\<deltaWei STRUCT\<sign STRING, value STRING>, newPar STRUCT\<sign STRING, value STRING>> | {'deltaWei': {'sign': 'true', 'value': '131970506340'}, 'newPar': {'sign': 'true', 'value': '0'\}}   |                                                              |
| makerInputUpdate.deltaWei        | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'true', 'value': '131970506340'}                                                            | None                                                         |
| makerInputUpdate.deltaWei.sign   | VARCHAR                                                                                         | true                                                                                                 | None                                                         |
| makerInputUpdate.deltaWei.value  | VARCHAR                                                                                         | 131970506340                                                                                         | None                                                         |
| makerInputUpdate.newPar          | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'true', 'value': '0'}                                                                       | None                                                         |
| makerInputUpdate.newPar.sign     | VARCHAR                                                                                         | true                                                                                                 | None                                                         |
| makerInputUpdate.newPar.value    | VARCHAR                                                                                         | 0                                                                                                    | None                                                         |
| makerOutputUpdate                | STRUCT\<deltaWei STRUCT\<sign STRING, value STRING>, newPar STRUCT\<sign STRING, value STRING>> | {'deltaWei': {'sign': 'false', 'value': '59758377633243690224'}, 'newPar': {'sign': 'true', 'value': |                                                              |
| makerOutputUpdate.deltaWei       | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'false', 'value': '59758377633243690224'}                                                   | None                                                         |
| makerOutputUpdate.deltaWei.sign  | VARCHAR                                                                                         | false                                                                                                | None                                                         |
| makerOutputUpdate.deltaWei.value | VARCHAR                                                                                         | 59758377633243690224                                                                                 | None                                                         |
| makerOutputUpdate.newPar         | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'true', 'value': '20196490590982216758'}                                                    | None                                                         |
| makerOutputUpdate.newPar.sign    | VARCHAR                                                                                         | true                                                                                                 | None                                                         |
| makerOutputUpdate.newPar.value   | VARCHAR                                                                                         | 20196490590982216758                                                                                 | None                                                         |
| autoTrader                       | VARCHAR                                                                                         | 0xcd81398895bea7ad9eff273aeffc41a9d83b4dad                                                           |                                                              |

## 28. Table: SoloMargin\_event\_LogTransfer\_history

| Column                   | Type                                                                                            | Example                                                                                              | Description                                                  |
| ------------------------ | ----------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP                                                                                       | 2021-08-07 18:04:30+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER                                                                                         | 12979485                                                                                             | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR                                                                                         | 0xf5611a40f0a3324ec48f5dac109ea16bacb3693d7a40bfa383144e5d2cc62bd1                                   | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER                                                                                         | 345                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR                                                                                         | 0x1e0447b19bb6ecfdae1e4ae1694b0c3659614e4e                                                           | Address of the contract that produced the log                |
| accountOneOwner          | VARCHAR                                                                                         | 0xac8e57435fa53ca020e316e83b1035c63fa2b3dc                                                           |                                                              |
| accountOneNumber         | VARCHAR                                                                                         | 14981538385642474504653683649158411144014493562082338989641493324305871008605                        |                                                              |
| accountTwoOwner          | VARCHAR                                                                                         | 0xac8e57435fa53ca020e316e83b1035c63fa2b3dc                                                           |                                                              |
| accountTwoNumber         | VARCHAR                                                                                         | 0                                                                                                    |                                                              |
| market                   | VARCHAR                                                                                         | 0                                                                                                    |                                                              |
| updateOne                | STRUCT\<deltaWei STRUCT\<sign STRING, value STRING>, newPar STRUCT\<sign STRING, value STRING>> | {'deltaWei': {'sign': 'false', 'value': '1654217026627707044'}, 'newPar': {'sign': 'true', 'value':  |                                                              |
| updateOne.deltaWei       | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'false', 'value': '1654217026627707044'}                                                    | None                                                         |
| updateOne.deltaWei.sign  | VARCHAR                                                                                         | false                                                                                                | None                                                         |
| updateOne.deltaWei.value | VARCHAR                                                                                         | 1654217026627707044                                                                                  | None                                                         |
| updateOne.newPar         | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'true', 'value': '0'}                                                                       | None                                                         |
| updateOne.newPar.sign    | VARCHAR                                                                                         | true                                                                                                 | None                                                         |
| updateOne.newPar.value   | VARCHAR                                                                                         | 0                                                                                                    | None                                                         |
| updateTwo                | STRUCT\<deltaWei STRUCT\<sign STRING, value STRING>, newPar STRUCT\<sign STRING, value STRING>> | {'deltaWei': {'sign': 'true', 'value': '1654217026627707044'}, 'newPar': {'sign': 'true', 'value': ' |                                                              |
| updateTwo.deltaWei       | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'true', 'value': '1654217026627707044'}                                                     | None                                                         |
| updateTwo.deltaWei.sign  | VARCHAR                                                                                         | true                                                                                                 | None                                                         |
| updateTwo.deltaWei.value | VARCHAR                                                                                         | 1654217026627707044                                                                                  | None                                                         |
| updateTwo.newPar         | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'true', 'value': '1650995306988131799'}                                                     | None                                                         |
| updateTwo.newPar.sign    | VARCHAR                                                                                         | true                                                                                                 | None                                                         |
| updateTwo.newPar.value   | VARCHAR                                                                                         | 1650995306988131799                                                                                  | None                                                         |

## 29. Table: SoloMargin\_event\_LogVaporize\_history

| Column                         | Type                                                                                            | Example                                                                                          | Description                                                  |
| ------------------------------ | ----------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp               | TIMESTAMP                                                                                       | 2021-05-19 19:02:52+00:00                                                                        | Timestamp of the block where this event was emitted          |
| block\_number                  | INTEGER                                                                                         | 12466576                                                                                         | The block number where this event was emitted                |
| transaction\_hash              | VARCHAR                                                                                         | 0xf87abd1455d14e60fcd1604db87c9b34607a99af92095c31c5f8469d28f96fe0                               | Hash of the transactions in which this event was emitted     |
| log\_index                     | INTEGER                                                                                         | 193                                                                                              | Integer of the log index position in the block of this event |
| contract\_address              | VARCHAR                                                                                         | 0x1e0447b19bb6ecfdae1e4ae1694b0c3659614e4e                                                       | Address of the contract that produced the log                |
| solidAccountOwner              | VARCHAR                                                                                         | 0x533d480e0a2226139db7cc796b0062c40664e833                                                       |                                                              |
| solidAccountNumber             | VARCHAR                                                                                         | 0                                                                                                |                                                              |
| vaporAccountOwner              | VARCHAR                                                                                         | 0x5b4eb01c4a876277fd3410245707c55211239970                                                       |                                                              |
| vaporAccountNumber             | VARCHAR                                                                                         | 0                                                                                                |                                                              |
| heldMarket                     | VARCHAR                                                                                         | 0                                                                                                |                                                              |
| owedMarket                     | VARCHAR                                                                                         | 2                                                                                                |                                                              |
| solidHeldUpdate                | STRUCT\<deltaWei STRUCT\<sign STRING, value STRING>, newPar STRUCT\<sign STRING, value STRING>> | {'deltaWei': {'sign': 'true', 'value': '0'}, 'newPar': {'sign': 'true', 'value': '0'\}}          |                                                              |
| solidHeldUpdate.deltaWei       | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'true', 'value': '0'}                                                                   | None                                                         |
| solidHeldUpdate.deltaWei.sign  | VARCHAR                                                                                         | true                                                                                             | None                                                         |
| solidHeldUpdate.deltaWei.value | VARCHAR                                                                                         | 0                                                                                                | None                                                         |
| solidHeldUpdate.newPar         | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'true', 'value': '0'}                                                                   | None                                                         |
| solidHeldUpdate.newPar.sign    | VARCHAR                                                                                         | true                                                                                             | None                                                         |
| solidHeldUpdate.newPar.value   | VARCHAR                                                                                         | 0                                                                                                | None                                                         |
| solidOwedUpdate                | STRUCT\<deltaWei STRUCT\<sign STRING, value STRING>, newPar STRUCT\<sign STRING, value STRING>> | {'deltaWei': {'sign': 'true', 'value': '0'}, 'newPar': {'sign': 'false', 'value': '0'\}}         |                                                              |
| solidOwedUpdate.deltaWei       | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'true', 'value': '0'}                                                                   | None                                                         |
| solidOwedUpdate.deltaWei.sign  | VARCHAR                                                                                         | true                                                                                             | None                                                         |
| solidOwedUpdate.deltaWei.value | VARCHAR                                                                                         | 0                                                                                                | None                                                         |
| solidOwedUpdate.newPar         | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'false', 'value': '0'}                                                                  | None                                                         |
| solidOwedUpdate.newPar.sign    | VARCHAR                                                                                         | false                                                                                            | None                                                         |
| solidOwedUpdate.newPar.value   | VARCHAR                                                                                         | 0                                                                                                | None                                                         |
| vaporOwedUpdate                | STRUCT\<deltaWei STRUCT\<sign STRING, value STRING>, newPar STRUCT\<sign STRING, value STRING>> | {'deltaWei': {'sign': 'true', 'value': '109447311'}, 'newPar': {'sign': 'false', 'value': '0'\}} |                                                              |
| vaporOwedUpdate.deltaWei       | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'true', 'value': '109447311'}                                                           | None                                                         |
| vaporOwedUpdate.deltaWei.sign  | VARCHAR                                                                                         | true                                                                                             | None                                                         |
| vaporOwedUpdate.deltaWei.value | VARCHAR                                                                                         | 109447311                                                                                        | None                                                         |
| vaporOwedUpdate.newPar         | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'false', 'value': '0'}                                                                  | None                                                         |
| vaporOwedUpdate.newPar.sign    | VARCHAR                                                                                         | false                                                                                            | None                                                         |
| vaporOwedUpdate.newPar.value   | VARCHAR                                                                                         | 0                                                                                                | None                                                         |

## 30. Table: SoloMargin\_event\_LogWithdraw\_history

| Column                | Type                                                                                            | Example                                                                                              | Description                                                  |
| --------------------- | ----------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp      | TIMESTAMP                                                                                       | 2023-07-13 09:00:59+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number         | INTEGER                                                                                         | 17683562                                                                                             | The block number where this event was emitted                |
| transaction\_hash     | VARCHAR                                                                                         | 0xd10ae36538ff321f6cef5b5fbf751709b70f2468a4f3e8f58275a20613d927ea                                   | Hash of the transactions in which this event was emitted     |
| log\_index            | INTEGER                                                                                         | 58                                                                                                   | Integer of the log index position in the block of this event |
| contract\_address     | VARCHAR                                                                                         | 0x1e0447b19bb6ecfdae1e4ae1694b0c3659614e4e                                                           | Address of the contract that produced the log                |
| accountOwner          | VARCHAR                                                                                         | 0xe4000004000bd8006e00720000d27d1fa000d43e                                                           |                                                              |
| accountNumber         | VARCHAR                                                                                         | 0                                                                                                    |                                                              |
| market                | VARCHAR                                                                                         | 0                                                                                                    |                                                              |
| update                | STRUCT\<deltaWei STRUCT\<sign STRING, value STRING>, newPar STRUCT\<sign STRING, value STRING>> | {'deltaWei': {'sign': 'false', 'value': '70000000000000000000'}, 'newPar': {'sign': 'false', 'value' |                                                              |
| update.deltaWei       | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'false', 'value': '70000000000000000000'}                                                   | None                                                         |
| update.deltaWei.sign  | VARCHAR                                                                                         | false                                                                                                | None                                                         |
| update.deltaWei.value | VARCHAR                                                                                         | 70000000000000000000                                                                                 | None                                                         |
| update.newPar         | STRUCT\<sign STRING, value STRING>                                                              | {'sign': 'false', 'value': '68634689038339718547'}                                                   | None                                                         |
| update.newPar.sign    | VARCHAR                                                                                         | false                                                                                                | None                                                         |
| update.newPar.value   | VARCHAR                                                                                         | 68634689038339718547                                                                                 | None                                                         |
| to                    | VARCHAR                                                                                         | 0xe4000004000bd8006e00720000d27d1fa000d43e                                                           |                                                              |
