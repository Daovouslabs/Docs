# maple

## 1. Table: LoanManagerFactory\_v2\_event\_DefaultVersionSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-06 16:39:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16127002                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9436123b684b53741fd8ef1ed42f826f98380a480adae7e75600f7e0563c358d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 105                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1551717ae4fdcb65ed028f7fb7aba39908f6a7a6                         | Address of the contract that produced the log                |
| version\_         | VARCHAR   | 100                                                                |                                                              |

## 2. Table: LoanManagerFactory\_v2\_event\_ImplementationRegistered\_history

| Column                  | Type      | Example                                                            | Description                                                  |
| ----------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp        | TIMESTAMP | 2023-06-06 14:32:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number           | INTEGER   | 17422018                                                           | The block number where this event was emitted                |
| transaction\_hash       | VARCHAR   | 0x851d489a8028ecf1bb7603143b7294aee387e3e16ec2e3a073147fe70df0e65a | Hash of the transactions in which this event was emitted     |
| log\_index              | INTEGER   | 125                                                                | Integer of the log index position in the block of this event |
| contract\_address       | VARCHAR   | 0x1551717ae4fdcb65ed028f7fb7aba39908f6a7a6                         | Address of the contract that produced the log                |
| version\_               | VARCHAR   | 301                                                                |                                                              |
| implementationAddress\_ | VARCHAR   | 0x5b97c9dcce2693844b90cea40ba1fd15bf99eb01                         |                                                              |
| initializer\_           | VARCHAR   | 0xcbe920b1931da57069b12a19bc6d11ad7b5adabd                         |                                                              |

## 3. Table: LoanManagerFactory\_v2\_event\_InstanceDeployed\_history

| Column                    | Type      | Example                                                            | Description                                                  |
| ------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp          | TIMESTAMP | 2023-01-25 19:11:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number             | INTEGER   | 16485840                                                           | The block number where this event was emitted                |
| transaction\_hash         | VARCHAR   | 0x8234a7e1f4bb9c8cb588646d0cc854f6ec6a895499b048b59062a37aeb59194b | Hash of the transactions in which this event was emitted     |
| log\_index                | INTEGER   | 329                                                                | Integer of the log index position in the block of this event |
| contract\_address         | VARCHAR   | 0x1551717ae4fdcb65ed028f7fb7aba39908f6a7a6                         | Address of the contract that produced the log                |
| version\_                 | VARCHAR   | 200                                                                |                                                              |
| instance\_                | VARCHAR   | 0xd05998a1940294e3e49f99dbb13fe20a3483f5ae                         |                                                              |
| initializationArguments\_ | VARCHAR   | 0x000000000000000000000000e9d33286f0e37f517b1204aa6da085564414996d |                                                              |

## 4. Table: LoanManagerFactory\_v2\_event\_InstanceUpgraded\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2023-06-06 14:38:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 17422049                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x14faad93fd7e69c23c2a1a792a1b120c82e0426b74803b4f6c873f2e8766bfca | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 233                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x1551717ae4fdcb65ed028f7fb7aba39908f6a7a6                         | Address of the contract that produced the log                |
| instance\_           | VARCHAR   | 0x9b300a28d7dc7d422c7d1b9442db0b51a6346e00                         |                                                              |
| fromVersion\_        | VARCHAR   | 200                                                                |                                                              |
| toVersion\_          | VARCHAR   | 301                                                                |                                                              |
| migrationArguments\_ | VARCHAR   | 0x                                                                 |                                                              |

## 5. Table: LoanManagerFactory\_v2\_event\_MapleGlobalsSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| mapleGlobals\_    | VARCHAR   |                                                              |             |

## 6. Table: LoanManagerFactory\_v2\_event\_UpgradePathDisabled\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| fromVersion\_     | VARCHAR   |                                                              |             |
| toVersion\_       | VARCHAR   |                                                              |             |

## 7. Table: LoanManagerFactory\_v2\_event\_UpgradePathEnabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-06 14:32:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17422018                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x851d489a8028ecf1bb7603143b7294aee387e3e16ec2e3a073147fe70df0e65a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 127                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1551717ae4fdcb65ed028f7fb7aba39908f6a7a6                         | Address of the contract that produced the log                |
| fromVersion\_     | VARCHAR   | 200                                                                |                                                              |
| toVersion\_       | VARCHAR   | 301                                                                |                                                              |
| migrator\_        | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 8. Table: LoanManager\_v2\_event\_AllowedSlippageSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| collateralAsset\_ | VARCHAR   |                                                              |             |
| newSlippage\_     | VARCHAR   |                                                              |             |

## 9. Table: LoanManager\_v2\_event\_FundsDistributed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-29 08:23:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17363432                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9daa17b78fda4b0b99dacbe33084db400104af6608527088f3e241021ec26cc5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 109                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9b300a28d7dc7d422c7d1b9442db0b51a6346e00                         | Address of the contract that produced the log                |
| loan\_            | VARCHAR   | 0x10f151006056ad9a3d2c385b08b63ca6db5e0efa                         |                                                              |
| principal\_       | VARCHAR   | 3500000000000                                                      |                                                              |
| netInterest\_     | VARCHAR   | 30924657535                                                        |                                                              |

## 10. Table: LoanManager\_v2\_event\_IssuanceParamsUpdated\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2023-04-14 03:06:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 17042683                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x560a8601e03abec46c458f971b0a335bbd27891f2c90c23148417d964e6be9ce | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 129                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x373bdcf21f6a939713d5de94096ffdb24a406391                         | Address of the contract that produced the log                |
| domainEnd\_         | VARCHAR   | 1683713015                                                         |                                                              |
| issuanceRate\_      | VARCHAR   | 9110089547320324191301277012633425606324687                        |                                                              |
| accountedInterest\_ | VARCHAR   | 5370310502283104465                                                |                                                              |

## 11. Table: LoanManager\_v2\_event\_LoanTransferAdminSet\_history

| Column              | Type      | Example                                                      | Description |
| ------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp    | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number       | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash   | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index          | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address   | VARCHAR   | Address of the contract that produced the log                |             |
| loanTransferAdmin\_ | VARCHAR   |                                                              |             |

## 12. Table: LoanManager\_v2\_event\_ManagementFeesPaid\_history

| Column                  | Type      | Example                                                            | Description                                                  |
| ----------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp        | TIMESTAMP | 2023-04-10 09:46:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number           | INTEGER   | 17017002                                                           | The block number where this event was emitted                |
| transaction\_hash       | VARCHAR   | 0xfdffd58a6a6385eb03b721d8e622a7cba0e083ea2081c9c95f9ecdd824f72238 | Hash of the transactions in which this event was emitted     |
| log\_index              | INTEGER   | 112                                                                | Integer of the log index position in the block of this event |
| contract\_address       | VARCHAR   | 0x74cb3c1938a15e532cc1b465e3b641c2c7e40c2b                         | Address of the contract that produced the log                |
| loan\_                  | VARCHAR   | 0xe12c3b659bc734b20f45ff35970bb2e892a1387c                         |                                                              |
| delegateManagementFee\_ | VARCHAR   | 4993150684                                                         |                                                              |
| platformManagementFee\_ | VARCHAR   | 924657534                                                          |                                                              |

## 13. Table: LoanManager\_v2\_event\_MinRatioSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| collateralAsset\_ | VARCHAR   |                                                              |             |
| newMinRatio\_     | VARCHAR   |                                                              |             |

## 14. Table: LoanManager\_v2\_event\_PaymentAdded\_history

| Column                      | Type      | Example                                                            | Description                                                  |
| --------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp            | TIMESTAMP | 2023-03-11 19:02:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number               | INTEGER   | 16806789                                                           | The block number where this event was emitted                |
| transaction\_hash           | VARCHAR   | 0x9a1a3c6f5b1db7dcec1e5df92c387db834b620c2db4b97de498129c2c356aa94 | Hash of the transactions in which this event was emitted     |
| log\_index                  | INTEGER   | 504                                                                | Integer of the log index position in the block of this event |
| contract\_address           | VARCHAR   | 0x373bdcf21f6a939713d5de94096ffdb24a406391                         | Address of the contract that produced the log                |
| loan\_                      | VARCHAR   | 0x023db56966858d139fe6406ae927275490715a3a                         |                                                              |
| paymentId\_                 | VARCHAR   | 18                                                                 |                                                              |
| platformManagementFeeRate\_ | VARCHAR   | 25000                                                              |                                                              |
| delegateManagementFeeRate\_ | VARCHAR   | 135000                                                             |                                                              |
| startDate\_                 | VARCHAR   | 1678561379                                                         |                                                              |
| nextPaymentDueDate\_        | VARCHAR   | 1681153379                                                         |                                                              |
| netRefinanceInterest\_      | VARCHAR   | 0                                                                  |                                                              |
| newRate\_                   | VARCHAR   | 1864535768645357500000000000000000000000000                        |                                                              |

## 15. Table: LoanManager\_v2\_event\_PaymentRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-14 03:09:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17475427                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x19f71e43d427392e46885cfa8a802734b37c5a5ba9bf90501cb75ed71a1d2612 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 150                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6b6491aaa92ce7e901330d8f91ec99c2a157ebd7                         | Address of the contract that produced the log                |
| loan\_            | VARCHAR   | 0x48a89e5267dd3e22822c99d0bf60a8a4cfd48b48                         |                                                              |
| paymentId\_       | VARCHAR   | 9                                                                  |                                                              |

## 16. Table: LoanManager\_v2\_event\_PrincipalOutUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-05 14:28:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17849367                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2333789514446aba8006f087a81a30b3527b388f0cdce9bbec069ad2a8e6ef21 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 205                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf4d4a5270aa834a2a77011526447fdf1e227018f                         | Address of the contract that produced the log                |
| principalOut\_    | VARCHAR   | 9677817900000                                                      |                                                              |

## 17. Table: LoanManager\_v2\_event\_UnrealizedLossesUpdated\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2022-12-20 16:03:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 16226981                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x2091ada34283bbcc6829554e4cc6bf7fea73f9f3fba8ceab7994bccec6dba5e3 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 204                                                                | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x373bdcf21f6a939713d5de94096ffdb24a406391                         | Address of the contract that produced the log                |
| unrealizedLosses\_ | VARCHAR   | 2421781720045662097247                                             |                                                              |

## 18. Table: LoanManager\_v2\_event\_Upgraded\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| toVersion\_       | VARCHAR   |                                                              |             |
| arguments\_       | VARCHAR   |                                                              |             |

## 19. Table: Loan\_call\_borrower\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-12-13 01:28:23+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16172502                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x2e06cb160d18f5491cf0cac38647116b3d22feefc6fe1496b36dd1d912cb2767 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 48                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0,1,0,8                                                          | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xf6950f28353ca676100c2a92dd360dea16a213ce                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 20. Table: Loan\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-26 15:36:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13690613                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7a575e455d814850352bb2858f4e1966376c9ed0931bcd2b184309fca7262ace | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 146                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3148897e19bce5d29817f192291c5442900d0d8a                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xa5b42880846634a466dd9a56edfc489fbe435efe                         |                                                              |
| spender           | VARCHAR   | 0xa5b42880846634a466dd9a56edfc489fbe435efe                         |                                                              |
| value             | VARCHAR   | 36164383561                                                        |                                                              |

## 21. Table: Loan\_event\_BalanceUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-14 09:23:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14383867                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xad031fa703b7459c9ad68e8cb10721ce7d0075143d9faa15c27c3a54bf0c5e82 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 123                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0525436f5c1df9c918c696264845c3e2c7c23f77                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x0525436f5c1df9c918c696264845c3e2c7c23f77                         |                                                              |
| token             | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| balance           | VARCHAR   | 40068493151                                                        |                                                              |

## 22. Table: Loan\_event\_Drawdown\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-10 14:32:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13391452                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x43ccd54ea5aecfe86abb187a1383f27c8d5fffa26f48829e3512e33fb2ad6373 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 143                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x844de39093d26ed4fd74aa564148cea4255f187a                         | Address of the contract that produced the log                |
| drawdownAmount    | VARCHAR   | 11200000000000                                                     |                                                              |

## 23. Table: Loan\_event\_FundsDistributed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-28 23:44:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13317272                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd56de4a5d6878f8444f7f5aeeabc6aeade4b8a0863c59a9aaebd8082070d50eb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 455                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3148897e19bce5d29817f192291c5442900d0d8a                         | Address of the contract that produced the log                |
| by                | VARCHAR   | 0x9614f88a1f0f791d255a2c50ae73900fd5b64f29                         |                                                              |
| fundsDistributed  | VARCHAR   | 36164383561                                                        |                                                              |

## 24. Table: Loan\_event\_FundsWithdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-30 02:52:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13904145                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa4910a76dce460157483ce696b8a1482894ef6b478fee806e590f00c5422e6b1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 129                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3148897e19bce5d29817f192291c5442900d0d8a                         | Address of the contract that produced the log                |
| by                | VARCHAR   | 0x8c31d39c6048d74fed245df68fe557074ed39f9b                         |                                                              |
| fundsWithdrawn    | VARCHAR   | 4036164383561                                                      |                                                              |
| totalWithdrawn    | VARCHAR   | 4236986301365                                                      |                                                              |

## 25. Table: Loan\_event\_Liquidation\_history

| Column                 | Type      | Example                                                      | Description |
| ---------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp       | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number          | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash      | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index             | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address      | VARCHAR   | Address of the contract that produced the log                |             |
| collateralSwapped      | VARCHAR   |                                                              |             |
| liquidityAssetReturned | VARCHAR   |                                                              |             |
| liquidationExcess      | VARCHAR   |                                                              |             |
| defaultSuffered        | VARCHAR   |                                                              |             |

## 26. Table: Loan\_event\_LoanAdminSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| loanAdmin         | VARCHAR   |                                                              |             |
| allowed           | VARCHAR   |                                                              |             |

## 27. Table: Loan\_event\_LoanFunded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-19 08:26:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12855962                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9dc09dc6cbe6ec04417f2dfa7d0af263f3838c9d736527b534337ec737217b16 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 195                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf1cd6920e94f97e1fdcbf145523472249145e29b                         | Address of the contract that produced the log                |
| fundedBy          | VARCHAR   | 0x6565b3cb3643ab358a4fd0ca23cae1355f1224a8                         |                                                              |
| amountFunded      | VARCHAR   | 250000000000                                                       |                                                              |

## 28. Table: Loan\_event\_LoanStateChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-27 04:05:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12514146                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6c044e74978c2f423b0dc4baa3acf45a1c6996ad8a2d834499d3d8b87b47ebaa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 132                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe8a6a46f8d50d029824dad5e0e7d580def6edf76                         | Address of the contract that produced the log                |
| state             | VARCHAR   | 1                                                                  |                                                              |

## 29. Table: Loan\_event\_Paused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |

## 30. Table: Loan\_event\_PaymentMade\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-27 04:28:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13305721                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x046a4ecb82c2bda93cc3d120bf324c9858847a980eedd0a9a9bd92ee0c2786cd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 194                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe38b9513aabcf988523ba8c12f2581388ccd7d65                         | Address of the contract that produced the log                |
| totalPaid         | VARCHAR   | 36986301369                                                        |                                                              |
| principalPaid     | VARCHAR   | 0                                                                  |                                                              |
| interestPaid      | VARCHAR   | 36986301369                                                        |                                                              |
| paymentsRemaining | VARCHAR   | 4                                                                  |                                                              |
| principalOwed     | VARCHAR   | 5000000000000                                                      |                                                              |
| nextPaymentDue    | VARCHAR   | 1635440506                                                         |                                                              |
| latePayment       | VARCHAR   | false                                                              |                                                              |

## 31. Table: Loan\_event\_PointsCorrectionUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-30 17:05:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13715994                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe63fba0f6e8f77e0c539c0decb01047b886bdd1ba7e3ec613628e3ec536551eb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 259                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x82db9c55639aae9d39c178d39fb6ea86af59869a                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xe7c058fa103f636e70097d621ab8ff68a525687c                         |                                                              |
| pointsCorrection  | VARCHAR   | 0                                                                  |                                                              |

## 32. Table: Loan\_event\_PointsPerShareUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-24 10:57:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13288084                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x70854a35d049c90f86b24eaaa91e34529bfb8dcb14f90e855ca34384f1a8e78b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5038c72b526008dbb8cf1e6ef5a43e096840fe13                         | Address of the contract that produced the log                |
| pointsPerShare    | VARCHAR   | 3018257980560951549689795                                          |                                                              |

## 33. Table: Loan\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-20 20:26:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13653996                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x50015d3db573deb96c52a75e22f959e9c03313f9a26a8278c96c850f6083b2b0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 206                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3e4693f3970920ece3c253262124b0c165c51a55                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x250e7d148b9e71a3d5f358beecb77f1667c8ad24                         |                                                              |
| value             | VARCHAR   | 7000000000000000000000000                                          |                                                              |

## 34. Table: Loan\_event\_Unpaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |

## 35. Table: MapleLoanFactory\_v2\_event\_DefaultVersionSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-10 13:06:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15115049                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x28d973cd71bb5d05144ad6c2571bf367d9ecb493f1c1fe0bcf274ab1eb73657d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 93                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x36a7350309b2eb30f3b908ab0154851b5ed81db0                         | Address of the contract that produced the log                |
| version\_         | VARCHAR   | 300                                                                |                                                              |

## 36. Table: MapleLoanFactory\_v2\_event\_ImplementationRegistered\_history

| Column                  | Type      | Example                                                            | Description                                                  |
| ----------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp        | TIMESTAMP | 2022-12-09 03:40:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number           | INTEGER   | 16144529                                                           | The block number where this event was emitted                |
| transaction\_hash       | VARCHAR   | 0xdff22fded5f1ebf11cfaaf91e7a736292582d997fa1967354e3dd0f57128671a | Hash of the transactions in which this event was emitted     |
| log\_index              | INTEGER   | 80                                                                 | Integer of the log index position in the block of this event |
| contract\_address       | VARCHAR   | 0x36a7350309b2eb30f3b908ab0154851b5ed81db0                         | Address of the contract that produced the log                |
| version\_               | VARCHAR   | 400                                                                |                                                              |
| implementationAddress\_ | VARCHAR   | 0xe7bd3cc389b2182e6ec350fa9c90670dd76c061c                         |                                                              |
| initializer\_           | VARCHAR   | 0xdaa12dd385cbd04c60494efbbe8e757ec1b649ca                         |                                                              |

## 37. Table: MapleLoanFactory\_v2\_event\_InstanceDeployed\_history

| Column                    | Type      | Example                                                                                              | Description                                                  |
| ------------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp          | TIMESTAMP | 2022-03-11 06:25:12+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number             | INTEGER   | 14363959                                                                                             | The block number where this event was emitted                |
| transaction\_hash         | VARCHAR   | 0xbe55a1baa85f3d392a7a130c9f67359caad590dcb84ce3cecd0dae28f7d7a531                                   | Hash of the transactions in which this event was emitted     |
| log\_index                | INTEGER   | 772                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address         | VARCHAR   | 0x36a7350309b2eb30f3b908ab0154851b5ed81db0                                                           | Address of the contract that produced the log                |
| version\_                 | VARCHAR   | 200                                                                                                  |                                                              |
| instance\_                | VARCHAR   | 0x52eea5b529ecf8e700b7ab5293ba672486ae56fe                                                           |                                                              |
| initializationArguments\_ | VARCHAR   | 0x000000000000000000000000d5dee8195ae62bc011a89f1959a7a375cc0daf380000000000000000000000002260fac5e5 |                                                              |

## 38. Table: MapleLoanFactory\_v2\_event\_InstanceUpgraded\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2022-09-09 13:21:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 15502962                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x2380ebc758a93596f82adbe18d7fad48b1e557f95e6c4b974f1cf41d39d1d4df | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 219                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x36a7350309b2eb30f3b908ab0154851b5ed81db0                         | Address of the contract that produced the log                |
| instance\_           | VARCHAR   | 0xc3f20c6eefe39e2be8214dcc8cc41479a115f8ea                         |                                                              |
| fromVersion\_        | VARCHAR   | 200                                                                |                                                              |
| toVersion\_          | VARCHAR   | 300                                                                |                                                              |
| migrationArguments\_ | VARCHAR   | 0x                                                                 |                                                              |

## 39. Table: MapleLoanFactory\_v2\_event\_MapleGlobalsSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-11 23:37:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16164798                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbe008fcc371787adff5f9be0b6121e4b30846a617aff6c7745e4adfb37754de6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 64                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x36a7350309b2eb30f3b908ab0154851b5ed81db0                         | Address of the contract that produced the log                |
| mapleGlobals\_    | VARCHAR   | 0x804a6f5f667170f545bf14e5ddb48c70b788390c                         |                                                              |

## 40. Table: MapleLoanFactory\_v2\_event\_UpgradePathDisabled\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| fromVersion\_     | VARCHAR   |                                                              |             |
| toVersion\_       | VARCHAR   |                                                              |             |

## 41. Table: MapleLoanFactory\_v2\_event\_UpgradePathEnabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-06 14:32:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17422018                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x851d489a8028ecf1bb7603143b7294aee387e3e16ec2e3a073147fe70df0e65a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 124                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x36a7350309b2eb30f3b908ab0154851b5ed81db0                         | Address of the contract that produced the log                |
| fromVersion\_     | VARCHAR   | 400                                                                |                                                              |
| toVersion\_       | VARCHAR   | 501                                                                |                                                              |
| migrator\_        | VARCHAR   | 0xaf19511ea6ad222695a762ce01b33fd2d777992c                         |                                                              |

## 42. Table: MapleLoan\_call\_borrower\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-12-13 01:28:23+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16172502                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x2e06cb160d18f5491cf0cac38647116b3d22feefc6fe1496b36dd1d912cb2767 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 48                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0,0,0,8                                                          | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x502ee6d0b16d834547fc44344d4be3e019fc2573                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 43. Table: MapleLoan\_call\_fundLoan\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-10-13 16:31:11+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15740400                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x25250bc8ab721cc71c959982588f8ca7f90d23b533c4738482df3ab4b0e76a46 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 118                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 2,6,2                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x91a4eee4d33d9cd7840cae21a4f408c0919f555d                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| lender\_           | VARCHAR   | 0x9af086c79b8d06c6d6286e07e300078318874061                         |                                                                                                                        |
| amount\_           | VARCHAR   | 1000000000000000000000                                             |                                                                                                                        |

## 44. Table: MapleLoan\_event\_BorrowerAccepted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-05 13:39:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16118958                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x88539e091d388f1838fc3b8c5df670cd2bacd1dbe9ec4df8251bb0dd378eeaa0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 79                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4dbe67c683a731807eaaa99a1df2d3e79ebeca00                         | Address of the contract that produced the log                |
| borrower\_        | VARCHAR   | 0x26c4b5f60070028b4a77a0b38574a4bb917e6df0                         |                                                              |

## 45. Table: MapleLoan\_event\_CollateralPosted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-09 22:24:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14174549                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf14312187135e8276cf38e1ec5c37a459c124da450487e76e07d47033edd77df | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 138                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4a4da317aa7fabd8d7d192b7fbc44814d6396a9b                         | Address of the contract that produced the log                |
| amount\_          | VARCHAR   | 474819343104734394064                                              |                                                              |

## 46. Table: MapleLoan\_event\_CollateralRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-09 02:01:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14739665                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb96a8ecee84cf08cf6d0085256327a90c0bf99ef9c7517e7c377349981d68661 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 55                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4a4da317aa7fabd8d7d192b7fbc44814d6396a9b                         | Address of the contract that produced the log                |
| amount\_          | VARCHAR   | 474819343104734394064                                              |                                                              |
| destination\_     | VARCHAR   | 0x07a2e516993972ecd674058e173f02694617e233                         |                                                              |

## 47. Table: MapleLoan\_event\_Funded\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2022-04-08 08:30:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 14544049                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x450ad47ff4f621044ebf013d2ea735bc5e1e5ca6c9842b462d8d817aa7b33581 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 306                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x726893373de92b8272298d76a7d60a5f51b90da9                         | Address of the contract that produced the log                |
| lender\_             | VARCHAR   | 0x3d8ce8509ad45a7932027132f2cbe8db274e356e                         |                                                              |
| amount\_             | VARCHAR   | 10000000000000                                                     |                                                              |
| nextPaymentDueDate\_ | VARCHAR   | 1651998627                                                         |                                                              |

## 48. Table: MapleLoan\_event\_FundsClaimed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-21 15:13:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15002894                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4c9a9e8f8198bd665e3b96cadf2dd86d5f9daa061338c96c373e548fe451b6b1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 295                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x62314a3d00c09329319f8914aadb736264a7d4dc                         | Address of the contract that produced the log                |
| amount\_          | VARCHAR   | 62465753424                                                        |                                                              |
| destination\_     | VARCHAR   | 0x6f6c8013f639979c84b756c7fc1500eb5af18dc4                         |                                                              |

## 49. Table: MapleLoan\_event\_FundsDrawnDown\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-01 21:34:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14303575                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x187200363d4410ee316e0b182f83d96201c07b276dc438b74d1b413530a7bc97 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 272                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x99e035d409a0dfee786a6b796485aaadf1fd8771                         | Address of the contract that produced the log                |
| amount\_          | VARCHAR   | 2997558904110                                                      |                                                              |
| destination\_     | VARCHAR   | 0xeb1ac5634a25ab15ea03af5c4f93d6b905de5577                         |                                                              |

## 50. Table: MapleLoan\_event\_FundsRedirected\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-09 13:35:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15503019                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3fbea3928b0b8d22f64efc0a2a76e69f7de0e140af563b20c109c448a1b845ca | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 140                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc3f20c6eefe39e2be8214dcc8cc41479a115f8ea                         | Address of the contract that produced the log                |
| amount\_          | VARCHAR   | 16000000000000                                                     |                                                              |
| destination\_     | VARCHAR   | 0xb60f9a927ca2d951e80c3d42b46e67051b45a887                         |                                                              |

## 51. Table: MapleLoan\_event\_FundsReturned\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-15 15:00:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16634897                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4ade0aa113db4d00026b4e1a3061c3eb7b00bc9116453d07a9565c47dd9b5668 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 129                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x500055809685eceba5ec55786f65440583954501                         | Address of the contract that produced the log                |
| amount\_          | VARCHAR   | 7667980613876                                                      |                                                              |

## 52. Table: MapleLoan\_event\_Initialized\_history

| Column            | Type      | Example                                                                               | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-29 08:03:28+00:00                                                             | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14479944                                                                              | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2658fe46b9c00a1d28b88e9f3996232d5ed684861822b4d927d6002641308688                    | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 172                                                                                   | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf83909327202bea1a05dd992aad5ada053c99243                                            | Address of the contract that produced the log                |
| borrower\_        | VARCHAR   | 0xd5dee8195ae62bc011a89f1959a7a375cc0daf38                                            |                                                              |
| assets\_          | VARCHAR   | 0x2260FAC5E5542a773Aa44fBCfeDf7C193bc2C599,0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48 |                                                              |
| termDetails\_     | VARCHAR   | 432000,2592000,3                                                                      |                                                              |
| amounts\_         | VARCHAR   | 0,20000000000000,20000000000000                                                       |                                                              |
| rates\_           | VARCHAR   | 85000000000000000,0,0,50000000000000000                                               |                                                              |

## 53. Table: MapleLoan\_event\_LenderAccepted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-11 23:02:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16164620                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdea9b9f09902370f84478943ccd2c404fc391159f9c72aa922b00ad8badd158d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 318                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x64982f1aa56340c0051bdcefb7a69911fd9d141d                         | Address of the contract that produced the log                |
| lender\_          | VARCHAR   | 0x373bdcf21f6a939713d5de94096ffdb24a406391                         |                                                              |

## 54. Table: MapleLoan\_event\_LoanClosed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-23 19:06:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14264081                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x88c4b54010ef167935d540bf0a9451dc922e077e0fb126a0c5fe04d4e16d6296 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 189                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6694b375a03951a37b98493abe7fcf04c441b76f                         | Address of the contract that produced the log                |
| principalPaid\_   | VARCHAR   | 6000000000000                                                      |                                                              |
| interestPaid\_    | VARCHAR   | 0                                                                  |                                                              |

## 55. Table: MapleLoan\_event\_NewTermsAccepted\_history

| Column                | Type      | Example                                                      | Description |
| --------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp      | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number         | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash     | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index            | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address     | VARCHAR   | Address of the contract that produced the log                |             |
| refinanceCommitment\_ | VARCHAR   |                                                              |             |
| refinancer\_          | VARCHAR   |                                                              |             |
| calls\_               | VARCHAR   |                                                              |             |

## 56. Table: MapleLoan\_event\_NewTermsProposed\_history

| Column                | Type      | Example                                                      | Description |
| --------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp      | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number         | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash     | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index            | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address     | VARCHAR   | Address of the contract that produced the log                |             |
| refinanceCommitment\_ | VARCHAR   |                                                              |             |
| refinancer\_          | VARCHAR   |                                                              |             |
| calls\_               | VARCHAR   |                                                              |             |

## 57. Table: MapleLoan\_event\_PaymentMade\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-29 07:00:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15043800                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x514806b2d61c95e3dba0f23b12ae8be97bed1d7cafc3e85deb7671dea2d13cd8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 150                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4c2e95bb1b5454446183ddcf1803a18b0a97d888                         | Address of the contract that produced the log                |
| principalPaid\_   | VARCHAR   | 0                                                                  |                                                              |
| interestPaid\_    | VARCHAR   | 40068493150                                                        |                                                              |

## 58. Table: MapleLoan\_event\_PendingBorrowerSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-05 12:18:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16118558                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb504530085dbfb3050758e1a9e95b3d838a051af1071b08b578f9ad51507e80d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 278                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf6950f28353ca676100c2a92dd360dea16a213ce                         | Address of the contract that produced the log                |
| pendingBorrower\_ | VARCHAR   | 0x26c4b5f60070028b4a77a0b38574a4bb917e6df0                         |                                                              |

## 59. Table: MapleLoan\_event\_PendingLenderSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-11 22:54:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16164579                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x413d6f6605ffacc7147f5a873feccab67d25b251d7e630beca5421208f3d3b4e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 43                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2cb5c20309b2dbfdda758237f20c94b5f72d0331                         | Address of the contract that produced the log                |
| pendingLender\_   | VARCHAR   | 0x373bdcf21f6a939713d5de94096ffdb24a406391                         |                                                              |

## 60. Table: MapleLoan\_event\_Repossessed\_history

| Column                  | Type      | Example                                                            | Description                                                  |
| ----------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp        | TIMESTAMP | 2023-02-15 17:15:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number           | INTEGER   | 16635571                                                           | The block number where this event was emitted                |
| transaction\_hash       | VARCHAR   | 0x7bbf62a51dabfd38a91a798f7ddb470ef3ae4d9142785a92989837e40917bb45 | Hash of the transactions in which this event was emitted     |
| log\_index              | INTEGER   | 181                                                                | Integer of the log index position in the block of this event |
| contract\_address       | VARCHAR   | 0x500055809685eceba5ec55786f65440583954501                         | Address of the contract that produced the log                |
| collateralRepossessed\_ | VARCHAR   | 0                                                                  |                                                              |
| fundsRepossessed\_      | VARCHAR   | 7667980613876                                                      |                                                              |
| destination\_           | VARCHAR   | 0x6b6491aaa92ce7e901330d8f91ec99c2a157ebd7                         |                                                              |

## 61. Table: MapleLoan\_event\_Skimmed\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| token\_           | VARCHAR   |                                                              |             |
| amount\_          | VARCHAR   |                                                              |             |
| destination\_     | VARCHAR   |                                                              |             |

## 62. Table: MapleLoan\_event\_Upgraded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-09 00:54:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16143702                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe380e6252b90e9195d606838bfb2fa810322a838dd9549c733ce096fe4f4d7b9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 291                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2cb5c20309b2dbfdda758237f20c94b5f72d0331                         | Address of the contract that produced the log                |
| toVersion\_       | VARCHAR   | 301                                                                |                                                              |
| arguments\_       | VARCHAR   | 0x                                                                 |                                                              |

## 63. Table: MapleLoan\_v2\_event\_FundsClaimed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-14 06:26:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17689912                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe5f659199a0609b3c5fc17d7188f2f9cab5fdee97bf5b20fe157a50430a2fe16 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 262                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x48a89e5267dd3e22822c99d0bf60a8a4cfd48b48                         | Address of the contract that produced the log                |
| amount\_          | VARCHAR   | 22011849081                                                        |                                                              |
| destination\_     | VARCHAR   | 0x6b6491aaa92ce7e901330d8f91ec99c2a157ebd7                         |                                                              |

## 64. Table: MapleLoan\_v2\_event\_FundsDrawnDown\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-08 03:33:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14343797                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb8b3ddceec1b6f72a94ad8842a0d2d79d409f22441c24846cbefb10e02bf8312 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 618                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x65d657b37dba8cc07bd83f1e843b3d79be1246fe                         | Address of the contract that produced the log                |
| amount\_          | VARCHAR   | 1955215452054794520549                                             |                                                              |
| destination\_     | VARCHAR   | 0x07b6c7bc3d7dc0f36133b542ea51aa7ac560e974                         |                                                              |

## 65. Table: MapleLoan\_v2\_event\_FundsReturned\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-15 16:58:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16635486                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4a19dddd7bd0d71e4c0fb37a1f9b0f791cbb30507c58fdc1cd3de5c42b62e3bb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 328                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2cb5c20309b2dbfdda758237f20c94b5f72d0331                         | Address of the contract that produced the log                |
| amount\_          | VARCHAR   | 4029847028082191774232                                             |                                                              |

## 66. Table: MapleLoan\_v2\_event\_Initialized\_history

| Column            | Type      | Example                                                                               | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-24 12:01:47+00:00                                                             | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17328912                                                                              | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xec1c81f273e80e73ca7f56357f1403819d612d25bb94e4b8f9aa8a9c86cf1f70                    | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 43                                                                                    | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcb8b7968b4b7333fe85e89e802f2a5ed98408320                                            | Address of the contract that produced the log                |
| borrower\_        | VARCHAR   | 0xda28e780472b5754a1144bce6e83af06a33107d2                                            |                                                              |
| feeManager\_      | VARCHAR   | 0xfeaca6a5703e6f9de0ebe0975c93ae34c00523f2                                            |                                                              |
| assets\_          | VARCHAR   | 0x2260FAC5E5542a773Aa44fBCfeDf7C193bc2C599,0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48 |                                                              |
| termDetails\_     | VARCHAR   | 432000,2592000,1                                                                      |                                                              |
| amounts\_         | VARCHAR   | 0,2267817900000,2267817900000                                                         |                                                              |
| rates\_           | VARCHAR   | 53800000000000000,0,0,20000000000000000                                               |                                                              |
| fees\_            | VARCHAR   | 0,0                                                                                   |                                                              |

## 67. Table: MapleLoan\_v2\_event\_LenderAccepted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-11 23:02:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16164620                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdea9b9f09902370f84478943ccd2c404fc391159f9c72aa922b00ad8badd158d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 314                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2cb5c20309b2dbfdda758237f20c94b5f72d0331                         | Address of the contract that produced the log                |
| lender\_          | VARCHAR   | 0x373bdcf21f6a939713d5de94096ffdb24a406391                         |                                                              |

## 68. Table: MapleLoan\_v2\_event\_LoanClosed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-12 00:16:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16164991                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc2500c5bf2112cc39f80d314941d33b15e88a852b8e9a7ac4f9e7d6abdf89aad | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 18                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3f542d451344ea0cb58323d049033fd46ae56ec3                         | Address of the contract that produced the log                |
| principalPaid\_   | VARCHAR   | 1246150                                                            |                                                              |
| interestPaid\_    | VARCHAR   | 0                                                                  |                                                              |
| feesPaid\_        | VARCHAR   | 675                                                                |                                                              |

## 69. Table: MapleLoan\_v2\_event\_LoanImpaired\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2022-12-20 16:04:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 16226986                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x698a1d1b0cf08290ed7ad977869c8d40ec8839ef5c2b3c9f80afe1992c558053 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 381                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x64982f1aa56340c0051bdcefb7a69911fd9d141d                         | Address of the contract that produced the log                |
| nextPaymentDueDate\_ | VARCHAR   | 1670943623                                                         |                                                              |

## 70. Table: MapleLoan\_v2\_event\_NewTermsAccepted\_history

| Column                | Type      | Example                                                                                              | Description                                                  |
| --------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp      | TIMESTAMP | 2023-06-26 15:58:35+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number         | INTEGER   | 17564637                                                                                             | The block number where this event was emitted                |
| transaction\_hash     | VARCHAR   | 0x8b77ebc3669265a4bcb2d6d48dbeee43da279c83c1e36f29797fa98da6a2bbbc                                   | Hash of the transactions in which this event was emitted     |
| log\_index            | INTEGER   | 280                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address     | VARCHAR   | 0xe32b24f1a8877de54804bf82dfb1d4578850135e                                                           | Address of the contract that produced the log                |
| refinanceCommitment\_ | VARCHAR   | 0x6b3495f98263052f00b81e687bdad1a8cbb81ce8bccd96449cf71c50a1e3ff0f                                   |                                                              |
| refinancer\_          | VARCHAR   | 0x27ea6e67fb62ab2a603d4acbc9377d7a9a0fd5e3                                                           |                                                              |
| deadline\_            | VARCHAR   | 1687966262                                                                                           |                                                              |
| calls\_               | VARCHAR   | 0x5f84f3020000000000000000000000000000000000000000000000000000000000000000,0x4764757e000000000000000 |                                                              |

## 71. Table: MapleLoan\_v2\_event\_NewTermsProposed\_history

| Column                | Type      | Example                                                                                              | Description                                                  |
| --------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp      | TIMESTAMP | 2023-08-05 14:15:11+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number         | INTEGER   | 17849299                                                                                             | The block number where this event was emitted                |
| transaction\_hash     | VARCHAR   | 0xfe4a58d62fb28c16b6695c6bc588b1bbf43fd5fa072684d1ffc3ca05cbaf934e                                   | Hash of the transactions in which this event was emitted     |
| log\_index            | INTEGER   | 233                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address     | VARCHAR   | 0x55c6ffd8637b3d936ed6f7924ddce591d013a0ff                                                           | Address of the contract that produced the log                |
| refinanceCommitment\_ | VARCHAR   | 0x5cc6a247055b190b9c43c1d138e89e40c9bf52d232fa41c29ee81525ec4d729a                                   |                                                              |
| refinancer\_          | VARCHAR   | 0x27ea6e67fb62ab2a603d4acbc9377d7a9a0fd5e3                                                           |                                                              |
| deadline\_            | VARCHAR   | 1691417680                                                                                           |                                                              |
| calls\_               | VARCHAR   | 0x5f84f302000000000000000000000000000000000000000000000000000000000000c864,0x4764757e000000000000000 |                                                              |

## 72. Table: MapleLoan\_v2\_event\_NewTermsRejected\_history

| Column                | Type      | Example                                                      | Description |
| --------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp      | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number         | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash     | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index            | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address     | VARCHAR   | Address of the contract that produced the log                |             |
| refinanceCommitment\_ | VARCHAR   |                                                              |             |
| refinancer\_          | VARCHAR   |                                                              |             |
| deadline\_            | VARCHAR   |                                                              |             |
| calls\_               | VARCHAR   |                                                              |             |

## 73. Table: MapleLoan\_v2\_event\_NextPaymentDueDateRestored\_history

| Column               | Type      | Example                                                      | Description |
| -------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp     | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number        | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash    | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index           | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address    | VARCHAR   | Address of the contract that produced the log                |             |
| nextPaymentDueDate\_ | VARCHAR   |                                                              |             |

## 74. Table: MapleLoan\_v2\_event\_PaymentMade\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-14 03:09:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17475427                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x19f71e43d427392e46885cfa8a802734b37c5a5ba9bf90501cb75ed71a1d2612 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 143                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x48a89e5267dd3e22822c99d0bf60a8a4cfd48b48                         | Address of the contract that produced the log                |
| principalPaid\_   | VARCHAR   | 0                                                                  |                                                              |
| interestPaid\_    | VARCHAR   | 43794713788                                                        |                                                              |
| fees\_            | VARCHAR   | 5018144285                                                         |                                                              |

## 75. Table: MapleLoan\_v2\_event\_PendingBorrowerSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-05 12:17:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16118550                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf8811e9f0c6d8bd174af68bb9e19b39f7801952f44dfa74fd46afc8ede4f73b5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 207                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x245de7e3b9b21b68c2c8d2e4759652f0dbce65a6                         | Address of the contract that produced the log                |
| pendingBorrower\_ | VARCHAR   | 0x26c4b5f60070028b4a77a0b38574a4bb917e6df0                         |                                                              |

## 76. Table: MapleLoan\_v2\_event\_PendingLenderSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-11 22:54:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16164579                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x413d6f6605ffacc7147f5a873feccab67d25b251d7e630beca5421208f3d3b4e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 47                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4dbe67c683a731807eaaa99a1df2d3e79ebeca00                         | Address of the contract that produced the log                |
| pendingLender\_   | VARCHAR   | 0x373bdcf21f6a939713d5de94096ffdb24a406391                         |                                                              |

## 77. Table: MapleLoan\_v2\_event\_Repossessed\_history

| Column                  | Type      | Example                                                            | Description                                                  |
| ----------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp        | TIMESTAMP | 2022-07-10 13:32:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number           | INTEGER   | 15115159                                                           | The block number where this event was emitted                |
| transaction\_hash       | VARCHAR   | 0xd4594f413667686e814a4edddaf10790d8aa28238e364d11891d5510d1635e0f | Hash of the transactions in which this event was emitted     |
| log\_index              | INTEGER   | 87                                                                 | Integer of the log index position in the block of this event |
| contract\_address       | VARCHAR   | 0x323bca025f293f9663f3162ff6cbc8edb8cf02b5                         | Address of the contract that produced the log                |
| collateralRepossessed\_ | VARCHAR   | 0                                                                  |                                                              |
| fundsRepossessed\_      | VARCHAR   | 0                                                                  |                                                              |
| destination\_           | VARCHAR   | 0xba88ccc288faaa376ac8678050eefad5a46818e9                         |                                                              |

## 78. Table: MapleLoan\_v2\_event\_Skimmed\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| token\_           | VARCHAR   |                                                              |             |
| amount\_          | VARCHAR   |                                                              |             |
| destination\_     | VARCHAR   |                                                              |             |

## 79. Table: MapleLoan\_v2\_event\_Upgraded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-04 07:19:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15673240                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe43c752762c5fa12263dc40fde3699e40b1f9437c76b61fd2bbad1b30d42968b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 31                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xecfecc0d17b756266ba3b57bcfa8f8be051adf6d                         | Address of the contract that produced the log                |
| toVersion\_       | VARCHAR   | 300                                                                |                                                              |
| arguments\_       | VARCHAR   | 0x                                                                 |                                                              |

## 80. Table: PoolFactory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-04 13:44:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13550563                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x778d42cb7d796fb7c6129d4f8d3d9ee1987e479164fafae6670318141491b822 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 169                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2cd79f7f8b38b9c0d80ea6b230441841a31537ec                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0xd618d93676762a8e3107554d9adbff7dfd7fbf47                         |                                                              |
| delegate          | VARCHAR   | 0xd59428c62650c9d4505b01fba9bf9469b920a66f                         |                                                              |
| liquidityAsset    | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| stakeAsset        | VARCHAR   | 0xc1b10e536cd611acff7a7c32a9e29ce6a02ef6ef                         |                                                              |
| liquidityLocker   | VARCHAR   | 0x600707c2411450851a2464f20ff2a07abdeeacf1                         |                                                              |
| stakeLocker       | VARCHAR   | 0xd9631f58f3afcd1d0e5863b31c7924a3fb79253d                         |                                                              |
| stakingFee        | VARCHAR   | 500                                                                |                                                              |
| delegateFee       | VARCHAR   | 0                                                                  |                                                              |
| liquidityCap      | VARCHAR   | 5000000000000                                                      |                                                              |
| name              | VARCHAR   | Maple Pool Token                                                   |                                                              |
| symbol            | VARCHAR   | MPL-LP                                                             |                                                              |

## 81. Table: PoolManagerFactory\_v2\_event\_DefaultVersionSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-06 14:32:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17422018                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x851d489a8028ecf1bb7603143b7294aee387e3e16ec2e3a073147fe70df0e65a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 120                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe463cd473ecc1d1a4ecf20b62624d84dd20a8339                         | Address of the contract that produced the log                |
| version\_         | VARCHAR   | 200                                                                |                                                              |

## 82. Table: PoolManagerFactory\_v2\_event\_ImplementationRegistered\_history

| Column                  | Type      | Example                                                            | Description                                                  |
| ----------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp        | TIMESTAMP | 2022-12-06 16:40:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number           | INTEGER   | 16127006                                                           | The block number where this event was emitted                |
| transaction\_hash       | VARCHAR   | 0x79eac15ed093560510310b09a252662611132df27fdd9399f1e5ed5e3974ecdc | Hash of the transactions in which this event was emitted     |
| log\_index              | INTEGER   | 74                                                                 | Integer of the log index position in the block of this event |
| contract\_address       | VARCHAR   | 0xe463cd473ecc1d1a4ecf20b62624d84dd20a8339                         | Address of the contract that produced the log                |
| version\_               | VARCHAR   | 100                                                                |                                                              |
| implementationAddress\_ | VARCHAR   | 0x09fe53d404fbe13750047ecdb64ec6aa6fae46e6                         |                                                              |
| initializer\_           | VARCHAR   | 0x0b240bf499773905802ee4de43f96407c436d549                         |                                                              |

## 83. Table: PoolManagerFactory\_v2\_event\_InstanceDeployed\_history

| Column                    | Type      | Example                                                                                              | Description                                                  |
| ------------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp          | TIMESTAMP | 2023-07-05 18:59:35+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number             | INTEGER   | 17629617                                                                                             | The block number where this event was emitted                |
| transaction\_hash         | VARCHAR   | 0x080ee99e70e8bb3777bfe28db649a4a8321e4db75cef2f8b96c497c7cb932c01                                   | Hash of the transactions in which this event was emitted     |
| log\_index                | INTEGER   | 65                                                                                                   | Integer of the log index position in the block of this event |
| contract\_address         | VARCHAR   | 0xe463cd473ecc1d1a4ecf20b62624d84dd20a8339                                                           | Address of the contract that produced the log                |
| version\_                 | VARCHAR   | 200                                                                                                  |                                                              |
| instance\_                | VARCHAR   | 0xe76b219f83e887e2503e14c343bb7e0b62a7af5d                                                           |                                                              |
| initializationArguments\_ | VARCHAR   | 0x000000000000000000000000cc780fe0e08ff81b1c1315d7f63e4ec04f21fe86000000000000000000000000dac17f958d |                                                              |

## 84. Table: PoolManagerFactory\_v2\_event\_InstanceUpgraded\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2023-06-06 14:38:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 17422049                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x14faad93fd7e69c23c2a1a792a1b120c82e0426b74803b4f6c873f2e8766bfca | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 225                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0xe463cd473ecc1d1a4ecf20b62624d84dd20a8339                         | Address of the contract that produced the log                |
| instance\_           | VARCHAR   | 0x83376e49c7bf776495313c89f9bf226c8b8971b6                         |                                                              |
| fromVersion\_        | VARCHAR   | 100                                                                |                                                              |
| toVersion\_          | VARCHAR   | 200                                                                |                                                              |
| migrationArguments\_ | VARCHAR   | 0x                                                                 |                                                              |

## 85. Table: PoolManagerFactory\_v2\_event\_MapleGlobalsSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| mapleGlobals\_    | VARCHAR   |                                                              |             |

## 86. Table: PoolManagerFactory\_v2\_event\_UpgradePathDisabled\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| fromVersion\_     | VARCHAR   |                                                              |             |
| toVersion\_       | VARCHAR   |                                                              |             |

## 87. Table: PoolManagerFactory\_v2\_event\_UpgradePathEnabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-06 14:32:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17422018                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x851d489a8028ecf1bb7603143b7294aee387e3e16ec2e3a073147fe70df0e65a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 121                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe463cd473ecc1d1a4ecf20b62624d84dd20a8339                         | Address of the contract that produced the log                |
| fromVersion\_     | VARCHAR   | 100                                                                |                                                              |
| toVersion\_       | VARCHAR   | 200                                                                |                                                              |
| migrator\_        | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 88. Table: PoolManager\_v2\_event\_AllowedLenderSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-10 15:53:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16599377                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x85592d84dc18a06ba9de1ddb8820ceafe03ac9da674064421f98ae754789dc39 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 316                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa9c908ee077ee26b52137fff714150c7eb69e160                         | Address of the contract that produced the log                |
| lender\_          | VARCHAR   | 0xf1ee962fd7d4d3856e151ef187aaa3aefd1f85fc                         |                                                              |
| isValid\_         | VARCHAR   | true                                                               |                                                              |

## 89. Table: PoolManager\_v2\_event\_CollateralLiquidationFinished\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2022-12-13 22:17:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 16178705                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x65f2b0459dd6f4a97285174b434c8f94bfce7a41f6693e39f1a44200472bdb0d | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 220                                                                | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x00d950a41a0d277ed91bf9fd366a5523fef0371e                         | Address of the contract that produced the log                |
| loan\_             | VARCHAR   | 0x726893373de92b8272298d76a7d60a5f51b90da9                         |                                                              |
| unrealizedLosses\_ | VARCHAR   | 10135031342464                                                     |                                                              |

## 90. Table: PoolManager\_v2\_event\_CollateralLiquidationTriggered\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| loan\_            | VARCHAR   |                                                              |             |

## 91. Table: PoolManager\_v2\_event\_CoverDeposited\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-13 22:37:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16178801                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1e28caf3886d5d4d441dae83dca613eec1c33efe3707daf2483e6dba0043d0b3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 264                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x833a5c9fc016a87419d21b10b64e24082bd1e49d                         | Address of the contract that produced the log                |
| amount\_          | VARCHAR   | 64239538137521005033                                               |                                                              |

## 92. Table: PoolManager\_v2\_event\_CoverWithdrawn\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| amount\_          | VARCHAR   |                                                              |             |

## 93. Table: PoolManager\_v2\_event\_DelegateManagementFeeRateSet\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2023-06-15 15:59:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 17486323                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xdbee14322ca39743e42539cbc650416094d7e73bce0bc7f073878b7debe4bf09 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 224                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x219654a61a0bc394055652986be403fa14405bb8                         | Address of the contract that produced the log                |
| managementFeeRate\_ | VARCHAR   | 50000                                                              |                                                              |

## 94. Table: PoolManager\_v2\_event\_LiquidityCapSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-05 18:59:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17629617                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x080ee99e70e8bb3777bfe28db649a4a8321e4db75cef2f8b96c497c7cb932c01 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 77                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe76b219f83e887e2503e14c343bb7e0b62a7af5d                         | Address of the contract that produced the log                |
| liquidityCap\_    | VARCHAR   | 0                                                                  |                                                              |

## 95. Table: PoolManager\_v2\_event\_LoanFunded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-06 14:02:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16570217                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa4a795f94854a03a35a97bd73857c21e95efac91b64efaefd0b087607b193235 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 216                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa9c908ee077ee26b52137fff714150c7eb69e160                         | Address of the contract that produced the log                |
| loan\_            | VARCHAR   | 0x0cbc028614f164a085fa24a895fe5e954fac5000                         |                                                              |
| loanManager\_     | VARCHAR   | 0xd05998a1940294e3e49f99dbb13fe20a3483f5ae                         |                                                              |
| amount\_          | VARCHAR   | 3000000000000                                                      |                                                              |

## 96. Table: PoolManager\_v2\_event\_LoanImpaired\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2022-12-13 14:32:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 16176393                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xcb6b4721f71322cc8028f90cc5730421efe6764957257960597034c039806ea4 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 321                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x00d950a41a0d277ed91bf9fd366a5523fef0371e                         | Address of the contract that produced the log                |
| loan\_              | VARCHAR   | 0xf6950f28353ca676100c2a92dd360dea16a213ce                         |                                                              |
| newPaymentDueDate\_ | VARCHAR   | 1670941967                                                         |                                                              |

## 97. Table: PoolManager\_v2\_event\_LoanImpairmentRemoved\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| loan\_            | VARCHAR   |                                                              |             |

## 98. Table: PoolManager\_v2\_event\_LoanManagerAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-05 18:59:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17629617                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x080ee99e70e8bb3777bfe28db649a4a8321e4db75cef2f8b96c497c7cb932c01 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 74                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe76b219f83e887e2503e14c343bb7e0b62a7af5d                         | Address of the contract that produced the log                |
| loanManager\_     | VARCHAR   | 0x1b61765e954113e6508c4f9db07675989f7f5874                         |                                                              |

## 99. Table: PoolManager\_v2\_event\_LoanManagerRemoved\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| loanManager\_     | VARCHAR   |                                                              |             |

## 100. Table: PoolManager\_v2\_event\_LoanRefinanced\_history

| Column              | Type      | Example                                                                                              | Description                                                  |
| ------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2023-02-24 09:51:35+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 16697425                                                                                             | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xaa23a891d1c348fc20ad894e1a0aacb04461cc5884a0e251cecccaf9dc876b6e                                   | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 205                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0xa9c908ee077ee26b52137fff714150c7eb69e160                                                           | Address of the contract that produced the log                |
| loan\_              | VARCHAR   | 0x3e36372119f12dee3de6c260cc7283557c24f471                                                           |                                                              |
| refinancer\_        | VARCHAR   | 0xec90671c2c8f4ccbb6074938f893306a13402251                                                           |                                                              |
| deadline\_          | VARCHAR   | 1677358107                                                                                           |                                                              |
| calls\_             | VARCHAR   | 0x5f84f30200000000000000000000000000000000000000000000000001988fe4052b8000,0x4764757e000000000000000 |                                                              |
| principalIncrease\_ | VARCHAR   | 0                                                                                                    |                                                              |

## 101. Table: PoolManager\_v2\_event\_OpenToPublic\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-11 20:04:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16163736                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x87827a93399b4272ec4c42f9ec12a45eb40f2f11472e1d89e59a07c2a0f49d26 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 346                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x833a5c9fc016a87419d21b10b64e24082bd1e49d                         | Address of the contract that produced the log                |

## 102. Table: PoolManager\_v2\_event\_PendingDelegateAccepted\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2022-12-13 14:09:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 16176277                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x570a5f7ca610b876f602d32e05c8bb5343d838af6a55bcfe48790f319f2c8057 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 210                                                                | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x00d950a41a0d277ed91bf9fd366a5523fef0371e                         | Address of the contract that produced the log                |
| previousDelegate\_ | VARCHAR   | 0xf11897a0009b3a37f15365a976015e7f22a16d50                         |                                                              |
| newDelegate\_      | VARCHAR   | 0xb8d8d40d999ff6758fab88e34ae1c54732d9ffff                         |                                                              |

## 103. Table: PoolManager\_v2\_event\_PendingDelegateSet\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2023-01-18 01:26:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 16430392                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x1966c08c9665ce3623bb7674e989118eb52826e7927a9a5a551ddc762a37b862 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 358                                                                | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0xe10a065d15a6eca69bb8a0063fe57eddb66999df                         | Address of the contract that produced the log                |
| previousDelegate\_ | VARCHAR   | 0x47c388644c7aa8736ca34e3bfa0ee1f8284778c1                         |                                                              |
| newDelegate\_      | VARCHAR   | 0x7371da5ac817c05547da65a84eacd72d653027af                         |                                                              |

## 104. Table: PoolManager\_v2\_event\_PoolConfigured\_history

| Column                      | Type      | Example                                                            | Description                                                  |
| --------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp            | TIMESTAMP | 2023-03-28 13:28:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number               | INTEGER   | 16926128                                                           | The block number where this event was emitted                |
| transaction\_hash           | VARCHAR   | 0xf521ccc9db0a7a967bf882118ddf1a510f9de4d64b426aea087ae0c95137c582 | Hash of the transactions in which this event was emitted     |
| log\_index                  | INTEGER   | 200                                                                | Integer of the log index position in the block of this event |
| contract\_address           | VARCHAR   | 0x83376e49c7bf776495313c89f9bf226c8b8971b6                         | Address of the contract that produced the log                |
| loanManager\_               | VARCHAR   | 0x9b300a28d7dc7d422c7d1b9442db0b51a6346e00                         |                                                              |
| withdrawalManager\_         | VARCHAR   | 0x7f0d63e2250bc99f48985b183af0c9a66bbc8ac3                         |                                                              |
| liquidityCap\_              | VARCHAR   | 10000000000000                                                     |                                                              |
| delegateManagementFeeRate\_ | VARCHAR   | 115000                                                             |                                                              |

## 105. Table: PoolManager\_v2\_event\_RedeemProcessed\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2022-12-31 18:32:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 16306556                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x31e5e7292ffd8156a0ffe3807f5c02e59a0e34ef117dc0673ee668d99d4a3a9f | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 363                                                                | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0xe10a065d15a6eca69bb8a0063fe57eddb66999df                         | Address of the contract that produced the log                |
| owner\_            | VARCHAR   | 0xcc9f61d9ca83e38eefccbac3a825acbfab10b080                         |                                                              |
| redeemableShares\_ | VARCHAR   | 9718616759                                                         |                                                              |
| resultingAssets\_  | VARCHAR   | 9757936296                                                         |                                                              |

## 106. Table: PoolManager\_v2\_event\_RedeemRequested\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-28 13:43:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16283627                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5c1dfba798ada437d7915f92d67f79bda221eaa9962087efc36ef6d65a3fd4ae | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 212                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00d950a41a0d277ed91bf9fd366a5523fef0371e                         | Address of the contract that produced the log                |
| owner\_           | VARCHAR   | 0x182d2d31ce99ecdb33a2d603b0916fb431707a40                         |                                                              |
| shares\_          | VARCHAR   | 0                                                                  |                                                              |

## 107. Table: PoolManager\_v2\_event\_SetAsActive\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-24 15:28:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16477567                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa6f6ae501cd342b524758ebc81e94f92654ced18a1b8ff2ef88b08f366438ae3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 101                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x72a231d127f5051b6bc1131382c5613fd5930cdf                         | Address of the contract that produced the log                |
| active\_          | VARCHAR   | true                                                               |                                                              |

## 108. Table: PoolManager\_v2\_event\_SharesRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-07 11:31:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16576620                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa68f187fc5010fe01346ab6914bec59a4f89f0b17adcf3b049ec444f6af08057 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 407                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x833a5c9fc016a87419d21b10b64e24082bd1e49d                         | Address of the contract that produced the log                |
| owner\_           | VARCHAR   | 0xaf0b4e80a78017b0f9290b3d943deb4b727346c8                         |                                                              |
| shares\_          | VARCHAR   | 1091000627062032580                                                |                                                              |

## 109. Table: PoolManager\_v2\_event\_Upgraded\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| toVersion\_       | VARCHAR   |                                                              |             |
| arguments\_       | VARCHAR   |                                                              |             |

## 110. Table: PoolManager\_v2\_event\_WithdrawalManagerSet\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2023-07-05 18:59:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 17629617                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x080ee99e70e8bb3777bfe28db649a4a8321e4db75cef2f8b96c497c7cb932c01 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 78                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0xe76b219f83e887e2503e14c343bb7e0b62a7af5d                         | Address of the contract that produced the log                |
| withdrawalManager\_ | VARCHAR   | 0xf0a66f70064ad3198abb35aae26b1eeeaea62c4b                         |                                                              |

## 111. Table: PoolManager\_v2\_event\_WithdrawalProcessed\_history

| Column             | Type      | Example                                                      | Description |
| ------------------ | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number      | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index         | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address  | VARCHAR   | Address of the contract that produced the log                |             |
| owner\_            | VARCHAR   |                                                              |             |
| redeemableShares\_ | VARCHAR   |                                                              |             |
| resultingAssets\_  | VARCHAR   |                                                              |             |

## 112. Table: Pool\_call\_deposit\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-09-02 13:34:27+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 13146551                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x260d4f974d4862f8b268aa969f6296a04350f1644f64a7bca6ff1e4c8e1658f3 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 122                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x6f6c8013f639979c84b756c7fc1500eb5af18dc4                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| amt                | VARCHAR   | 88979167441                                                        |                                                                                                                        |

## 113. Table: Pool\_call\_withdraw\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-06-26 00:04:23+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15026249                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xb2ffc82d2d9f576603262b51ebdbf60fcd5beaddb2db673f84000e6e090ac76f | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 192                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x1a066b0109545455bc771e49e6edef6303cb0a93                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| amt                | VARCHAR   | 58613786905199272601                                               |                                                                                                                        |

## 114. Table: Pool\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-07 16:12:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15296213                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9d0b7f870d53fd8480af249bfb1a70e9b839ba346bf07d759ea9f6fb10d1a3ed | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 234                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfebd6f15df3b73dc4307b1d7e65d46413e710c27                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x512a49c299f5f60edc1ee147abf1d68b41de4737                         |                                                              |
| spender           | VARCHAR   | 0x512a49c299f5f60edc1ee147abf1d68b41de4737                         |                                                              |
| value             | VARCHAR   | 2000000000000                                                      |                                                              |

## 115. Table: Pool\_event\_BalanceUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-28 00:40:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14291490                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x35c36c63c2bd8161bff57cf6314b666741eb89721ccb53d7a351101e54e82dbd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 170                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6f6c8013f639979c84b756c7fc1500eb5af18dc4                         | Address of the contract that produced the log                |
| liquidityProvider | VARCHAR   | 0xaaf126daea17f689d4f1753fccb559f0bbacc49e                         |                                                              |
| token             | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| balance           | VARCHAR   | 31022829808594                                                     |                                                              |

## 116. Table: Pool\_event\_Claim\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2022-09-07 07:35:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 15489055                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xb41ed584906fd496caf683acc000b11ec8197951f28d518cbe6d017d5fb55709 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 150                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x1a066b0109545455bc771e49e6edef6303cb0a93                         | Address of the contract that produced the log                |
| loan                | VARCHAR   | 0x633e4e82c257e8f10175ac5677735e06ecd00c20                         |                                                              |
| interest            | VARCHAR   | 8823287671232874701                                                |                                                              |
| principal           | VARCHAR   | 0                                                                  |                                                              |
| fee                 | VARCHAR   | 0                                                                  |                                                              |
| stakeLockerPortion  | VARCHAR   | 1102910958904109337                                                |                                                              |
| poolDelegatePortion | VARCHAR   | 1102910958904109337                                                |                                                              |

## 117. Table: Pool\_event\_Cooldown\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-01 03:03:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13718621                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xea1dde3909bc09112bebfd140b6d54e7f011d4e346b0d3a0ad8c705d2b597a43 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 447                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6f6c8013f639979c84b756c7fc1500eb5af18dc4                         | Address of the contract that produced the log                |
| liquidityProvider | VARCHAR   | 0x186cf5714316f47bc59e30a850615a3f938d7d79                         |                                                              |
| cooldown          | VARCHAR   | 0                                                                  |                                                              |

## 118. Table: Pool\_event\_CustodyAllowanceChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-04 12:18:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16111393                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc3332a7f2206370908de126dfb5ab899decf18b06397cdd46284a4851c8739db | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 128                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1a066b0109545455bc771e49e6edef6303cb0a93                         | Address of the contract that produced the log                |
| liquidityProvider | VARCHAR   | 0xb44cd5c304e1a9dd56c621d47060939df83a9238                         |                                                              |
| custodian         | VARCHAR   | 0x0a76c7913c94f2af16958fbdf9b4cf0bbdb159d8                         |                                                              |
| oldAllowance      | VARCHAR   | 13000000000000000000                                               |                                                              |
| newAllowance      | VARCHAR   | 0                                                                  |                                                              |

## 119. Table: Pool\_event\_CustodyTransfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-06 08:58:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14914078                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbe90148f01594df482cbe1c54e28fc444f5568fd759a4bd15aae2445e8e9c547 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6f6c8013f639979c84b756c7fc1500eb5af18dc4                         | Address of the contract that produced the log                |
| custodian         | VARCHAR   | 0x7c57bf654bc16b0c9080f4f75ff62876f50b8259                         |                                                              |
| from              | VARCHAR   | 0xb4522eb2ca49963de9c3dc69023cbe6d53489c98                         |                                                              |
| to                | VARCHAR   | 0xb4522eb2ca49963de9c3dc69023cbe6d53489c98                         |                                                              |
| amount            | VARCHAR   | 150000000000000000000000                                           |                                                              |

## 120. Table: Pool\_event\_DefaultSuffered\_history

| Column                          | Type      | Example                                                            | Description                                                  |
| ------------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp                | TIMESTAMP | 2022-07-10 13:38:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number                   | INTEGER   | 15115192                                                           | The block number where this event was emitted                |
| transaction\_hash               | VARCHAR   | 0x303a46d086d335b602f772e91a99c18a25bfd71fb83cc810ea2e352d4c810202 | Hash of the transactions in which this event was emitted     |
| log\_index                      | INTEGER   | 73                                                                 | Integer of the log index position in the block of this event |
| contract\_address               | VARCHAR   | 0xfebd6f15df3b73dc4307b1d7e65d46413e710c27                         | Address of the contract that produced the log                |
| loan                            | VARCHAR   | 0x323bca025f293f9663f3162ff6cbc8edb8cf02b5                         |                                                              |
| defaultSuffered                 | VARCHAR   | 10000000000000                                                     |                                                              |
| bptsBurned                      | VARCHAR   | 250021532179609691115                                              |                                                              |
| bptsReturned                    | VARCHAR   | 493734500845728318584                                              |                                                              |
| liquidityAssetRecoveredFromBurn | VARCHAR   | 2147853799302                                                      |                                                              |

## 121. Table: Pool\_event\_DepositDateUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-08 20:54:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13577993                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3370f80a6c44e29eee943419f0a36767fb2ad293acc359bf73f1fdf9f648ddbf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 363                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd618d93676762a8e3107554d9adbff7dfd7fbf47                         | Address of the contract that produced the log                |
| liquidityProvider | VARCHAR   | 0xd59428c62650c9d4505b01fba9bf9469b920a66f                         |                                                              |
| depositDate       | VARCHAR   | 1636242311                                                         |                                                              |

## 122. Table: Pool\_event\_FundsDistributed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-12 19:37:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14572696                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xeec32e00aaa7750a92cfa4f1ed2af3774b2b0ad6640fbd5f6a4c4b647d4fc1a8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 402                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd618d93676762a8e3107554d9adbff7dfd7fbf47                         | Address of the contract that produced the log                |
| by                | VARCHAR   | 0xd59428c62650c9d4505b01fba9bf9469b920a66f                         |                                                              |
| fundsDistributed  | VARCHAR   | 400000000000                                                       |                                                              |

## 123. Table: Pool\_event\_FundsWithdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-11 01:51:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14752059                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc3de78149946a366bbec4b3d36bed6b682bba9898b8b39d194d6cfa25ab0e706 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 547                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1a066b0109545455bc771e49e6edef6303cb0a93                         | Address of the contract that produced the log                |
| by                | VARCHAR   | 0xa0f75491720835b36edc92d06ddc468d201e9b73                         |                                                              |
| fundsWithdrawn    | VARCHAR   | 18371607447918347443                                               |                                                              |
| totalWithdrawn    | VARCHAR   | 18371607447918347443                                               |                                                              |

## 124. Table: Pool\_event\_LPStatusChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-24 22:19:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15820872                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x617ea8ebb6d6bf5f7f6cad8b82fcd87ccafa9caf74fa9e6c6f445740c28ca0fb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 105                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x733f56782d21b403e5ee9c8343645e1535f73cd4                         | Address of the contract that produced the log                |
| liquidityProvider | VARCHAR   | 0x55b2d42b2514ea4e3d1ab424fa6c29d4d64c01c7                         |                                                              |
| status            | VARCHAR   | true                                                               |                                                              |

## 125. Table: Pool\_event\_LiquidityCapSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-11 16:28:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13004917                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1442b79bd37b2f6da4a37bc3200e2e06f18c3dc36f6008ee357d7595552e0679 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 258                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfebd6f15df3b73dc4307b1d7e65d46413e710c27                         | Address of the contract that produced the log                |
| newLiquidityCap   | VARCHAR   | 52152549000000                                                     |                                                              |

## 126. Table: Pool\_event\_LoanFunded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-28 19:03:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15848529                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2395be89f3c987b544066b58f0a1cc9c9321330cb0a86a1457918fdba4d50e24 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 25                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6f6c8013f639979c84b756c7fc1500eb5af18dc4                         | Address of the contract that produced the log                |
| loan              | VARCHAR   | 0xa58fd39138083783689d700758d00873538c6c2a                         |                                                              |
| debtLocker        | VARCHAR   | 0x116c55005ea92f9e2f9c8d08213b77e381ca53fe                         |                                                              |
| amountFunded      | VARCHAR   | 5000000000000                                                      |                                                              |

## 127. Table: Pool\_event\_LockupPeriodSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-09 20:22:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15310103                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7776474276cafba7a8251c127d9a5f226b94efcba75103f380d205afa0c14244 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 204                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcc8058526de295c6ad917cb41416366d69a24cde                         | Address of the contract that produced the log                |
| newLockupPeriod   | VARCHAR   | 7776000                                                            |                                                              |

## 128. Table: Pool\_event\_LossesCorrectionUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-13 13:56:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13608073                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xba795b8bd013eb0772204de19ccc24f45f88aa519820a4cc300bb2504c805ef3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 408                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6f6c8013f639979c84b756c7fc1500eb5af18dc4                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x2e84988e2c221a1a5bdd8dc25ca405b4a42f119e                         |                                                              |
| lossesCorrection  | VARCHAR   | 0                                                                  |                                                              |

## 129. Table: Pool\_event\_LossesDistributed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-10 13:38:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15115192                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x303a46d086d335b602f772e91a99c18a25bfd71fb83cc810ea2e352d4c810202 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 70                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfebd6f15df3b73dc4307b1d7e65d46413e710c27                         | Address of the contract that produced the log                |
| by                | VARCHAR   | 0xa6ccb9483e3e7a737e3a4f5b72a1ce51838ba122                         |                                                              |
| lossesDistributed | VARCHAR   | 7852146200698                                                      |                                                              |

## 130. Table: Pool\_event\_LossesPerShareUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-10 13:38:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15115192                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x303a46d086d335b602f772e91a99c18a25bfd71fb83cc810ea2e352d4c810202 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 71                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfebd6f15df3b73dc4307b1d7e65d46413e710c27                         | Address of the contract that produced the log                |
| lossesPerShare    | VARCHAR   | 11047795910142880896539669                                         |                                                              |

## 131. Table: Pool\_event\_LossesRecognized\_history

| Column                | Type      | Example                                                            | Description                                                  |
| --------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp      | TIMESTAMP | 2022-06-06 23:35:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number         | INTEGER   | 14917644                                                           | The block number where this event was emitted                |
| transaction\_hash     | VARCHAR   | 0xf7014a14e8e215f8f0dbf3a2301b76584d74d99d600d65b4111ebb10489ae7b7 | Hash of the transactions in which this event was emitted     |
| log\_index            | INTEGER   | 153                                                                | Integer of the log index position in the block of this event |
| contract\_address     | VARCHAR   | 0x6f6c8013f639979c84b756c7fc1500eb5af18dc4                         | Address of the contract that produced the log                |
| by                    | VARCHAR   | 0x41e7d45610417b1909b6f71d0993cf7b5728e0e7                         |                                                              |
| lossesRecognized      | VARCHAR   | 0                                                                  |                                                              |
| totalLossesRecognized | VARCHAR   | 0                                                                  |                                                              |

## 132. Table: Pool\_event\_PointsCorrectionUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-27 20:16:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14290339                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbccd441acf488929b832a66b5ae310f48f405dc3ca1e38ce36282d2daf578b02 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 50                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfebd6f15df3b73dc4307b1d7e65d46413e710c27                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xbe102d2698b089e6e2a18c66281ecf29cf35d58e                         |                                                              |
| pointsCorrection  | VARCHAR   | -7988130400834590955977421500000000000000000000                    |                                                              |

## 133. Table: Pool\_event\_PointsPerShareUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-21 23:52:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13851647                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x72e5b76f935175702ea32b13058204ec544d6cd0de3041f9d5942892066817a8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 641                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfebd6f15df3b73dc4307b1d7e65d46413e710c27                         | Address of the contract that produced the log                |
| pointsPerShare    | VARCHAR   | 11906115471529398688049261                                         |                                                              |

## 134. Table: Pool\_event\_PoolAdminSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-08 15:12:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16140807                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1b401c8f18e952a7819ad9bc44a8bf5633fac9b5efb9eee8a8194c3a8d6c37ba | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 219                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1a066b0109545455bc771e49e6edef6303cb0a93                         | Address of the contract that produced the log                |
| poolAdmin         | VARCHAR   | 0x2ad93f308aa812961ec412a08ed778f4f4933758                         |                                                              |
| allowed           | VARCHAR   | true                                                               |                                                              |

## 135. Table: Pool\_event\_PoolOpenedToPublic\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-27 05:08:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12714150                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfb3baa316260ab93eddb74ef5263fd28e4de3b4c90881d261fe3384c104d341b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 324                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfebd6f15df3b73dc4307b1d7e65d46413e710c27                         | Address of the contract that produced the log                |
| isOpen            | VARCHAR   | false                                                              |                                                              |

## 136. Table: Pool\_event\_PoolStateChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-06 05:17:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12771988                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8c80af8e064aab3fd9b8c94502afca11bbb5d75a73482cac5015ce0cfaf34786 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 123                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6f6c8013f639979c84b756c7fc1500eb5af18dc4                         | Address of the contract that produced the log                |
| state             | VARCHAR   | 0                                                                  |                                                              |

## 137. Table: Pool\_event\_StakingFeeSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-12 19:33:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14572671                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0d1a216d527560868fcb1e93d37a91e1fea66275462428c7b4b6fef8b0636ad0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 241                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd618d93676762a8e3107554d9adbff7dfd7fbf47                         | Address of the contract that produced the log                |
| newStakingFee     | VARCHAR   | 0                                                                  |                                                              |

## 138. Table: Pool\_event\_TotalCustodyAllowanceUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-28 11:49:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15427625                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcfdbc1f5aafc85319ece6085871d71a16be5d41aed8fa29119b7d5db54c0b36f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 323                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1a066b0109545455bc771e49e6edef6303cb0a93                         | Address of the contract that produced the log                |
| liquidityProvider | VARCHAR   | 0x0a76c7913c94f2af16958fbdf9b4cf0bbdb159d8                         |                                                              |
| newTotalAllowance | VARCHAR   | 0                                                                  |                                                              |

## 139. Table: Pool\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-14 17:47:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14205700                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x12bbc466dabc496c404b7ec4642ac23b7c8ffb23b854a5cdc265d22154815c78 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 310                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6f6c8013f639979c84b756c7fc1500eb5af18dc4                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x2b4893286db2ea1d0de8606d6425a5c0b1f361bb                         |                                                              |
| value             | VARCHAR   | 31399000000000000000000                                            |                                                              |

## 140. Table: Pool\_v2\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-22 20:56:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16242776                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4525eef0cba6e0762ee164a0636bd29fe6c1a1431586eb62c2e9256366c9ff1b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 274                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x79400a2c9a5e2431419cac98bf46893c86e8bdd7                         | Address of the contract that produced the log                |
| owner\_           | VARCHAR   | 0xe10a065d15a6eca69bb8a0063fe57eddb66999df                         |                                                              |
| spender\_         | VARCHAR   | 0xd8f8bd488ba6ddf2a710f6c357a884fd1706981a                         |                                                              |
| amount\_          | VARCHAR   | 0                                                                  |                                                              |

## 141. Table: Pool\_v2\_event\_BootstrapMintPerformed\_history

| Column                | Type      | Example                                                            | Description                                                  |
| --------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp      | TIMESTAMP | 2023-01-25 07:39:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number         | INTEGER   | 16482402                                                           | The block number where this event was emitted                |
| transaction\_hash     | VARCHAR   | 0xeefc14d329abaf9d9ee26c38533d8f33ed1e986c2bf27369b36616262f897306 | Hash of the transactions in which this event was emitted     |
| log\_index            | INTEGER   | 40                                                                 | Integer of the log index position in the block of this event |
| contract\_address     | VARCHAR   | 0x228b210885e233cb538808900f50e054bdd61e54                         | Address of the contract that produced the log                |
| caller\_              | VARCHAR   | 0x375efc656fdf7d9f14fa4b3270a338e7e60c24f0                         |                                                              |
| receiver\_            | VARCHAR   | 0x375efc656fdf7d9f14fa4b3270a338e7e60c24f0                         |                                                              |
| assets\_              | VARCHAR   | 10000000                                                           |                                                              |
| shares\_              | VARCHAR   | 10000000                                                           |                                                              |
| bootStrapMintAmount\_ | VARCHAR   | 100000                                                             |                                                              |

## 142. Table: Pool\_v2\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-29 18:26:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17366414                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x11198475cab14d1e5d9d41a04e92e9e7d1a1fb68ff13fb99a788d63a4b88cc72 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 277                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfe119e9c24ab79f1bdd5dd884b86ceea2ee75d92                         | Address of the contract that produced the log                |
| caller\_          | VARCHAR   | 0x3295b00134a1ca31f2cfb7fb381644d289009407                         |                                                              |
| owner\_           | VARCHAR   | 0x3295b00134a1ca31f2cfb7fb381644d289009407                         |                                                              |
| assets\_          | VARCHAR   | 10000000000                                                        |                                                              |
| shares\_          | VARCHAR   | 9992572246                                                         |                                                              |

## 143. Table: Pool\_v2\_event\_OwnershipAccepted\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner\_   | VARCHAR   |                                                              |             |
| newOwner\_        | VARCHAR   |                                                              |             |

## 144. Table: Pool\_v2\_event\_PendingOwnerSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| owner\_           | VARCHAR   |                                                              |             |
| pendingOwner\_    | VARCHAR   |                                                              |             |

## 145. Table: Pool\_v2\_event\_RedemptionRequested\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-31 08:39:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16525671                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe3f9cd4e4fc97dfd58c54c1b2868f2492cf91366ea4914cb8b580c76841b509f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 169                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x79400a2c9a5e2431419cac98bf46893c86e8bdd7                         | Address of the contract that produced the log                |
| owner\_           | VARCHAR   | 0x07ae98d69128300e0ad7379b1927d8089d1baedb                         |                                                              |
| shares\_          | VARCHAR   | 0                                                                  |                                                              |
| escrowedShares\_  | VARCHAR   | 0                                                                  |                                                              |

## 146. Table: Pool\_v2\_event\_SharesRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-09 06:18:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16788817                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6bbd93d9872047c21fcf4a1d7db8d69807aed24317c459cd4c9b1349c0be676d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 52                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd3cd37a7299b963bbc69592e5ba933388f70dc88                         | Address of the contract that produced the log                |
| owner\_           | VARCHAR   | 0x902659b51cf8e57937f834d76dc0e66c70ee03ef                         |                                                              |
| shares\_          | VARCHAR   | 201682165                                                          |                                                              |

## 147. Table: Pool\_v2\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-25 07:39:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16482402                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xeefc14d329abaf9d9ee26c38533d8f33ed1e986c2bf27369b36616262f897306 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 39                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x228b210885e233cb538808900f50e054bdd61e54                         | Address of the contract that produced the log                |
| owner\_           | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| recipient\_       | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| amount\_          | VARCHAR   | 100000                                                             |                                                              |

## 148. Table: Pool\_v2\_event\_WithdrawRequested\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| owner\_           | VARCHAR   |                                                              |             |
| assets\_          | VARCHAR   |                                                              |             |
| escrowedShares\_  | VARCHAR   |                                                              |             |

## 149. Table: Pool\_v2\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-05 00:21:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17624079                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb3fcd876e54ad469f379123484c12746d31d2144d5a01f415817c678d48b61f3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 218                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfe119e9c24ab79f1bdd5dd884b86ceea2ee75d92                         | Address of the contract that produced the log                |
| caller\_          | VARCHAR   | 0x1cb7f3eab52bbe5f6635378b09d4856fb43ff7be                         |                                                              |
| receiver\_        | VARCHAR   | 0x1cb7f3eab52bbe5f6635378b09d4856fb43ff7be                         |                                                              |
| owner\_           | VARCHAR   | 0x1cb7f3eab52bbe5f6635378b09d4856fb43ff7be                         |                                                              |
| assets\_          | VARCHAR   | 246948189276                                                       |                                                              |
| shares\_          | VARCHAR   | 245630958046                                                       |                                                              |
