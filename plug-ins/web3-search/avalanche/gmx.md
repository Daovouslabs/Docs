# gmx

## 1. Table: Router\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-09 05:25:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 31096189                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3f1715ca9746556b24fad62c8ddc8d335819d4743dc9bf6e2781f0aca04c00fe | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 23                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5f719c2f1095f7b9fc68a68e35b51194f4b6abe8                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x97e7d075167fe10167a835b8623d55dbb2824ab3                         |                                                              |
| tokenIn           | VARCHAR   | 0xb31f66aa3c1e785363f0875a1b74e27b85fd66c7                         |                                                              |
| tokenOut          | VARCHAR   | 0x152b9d0fdc40c096757f570a51e494bd4b943e50                         |                                                              |
| amountIn          | VARCHAR   | 150000000000000000                                                 |                                                              |
| amountOut         | VARCHAR   | 7813                                                               |                                                              |

## 2. Table: Vault\_event\_BuyUSDG\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-25 23:21:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 27906584                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7fe45741f7e391cafb181ec0041e5ec08c0ecc0868a00c04fa5ef0f4b637f058 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ab2de34a33fb459b538c43f251eb825645e8595                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xd152c7f25db7f4b95b7658323c5f33d176818ee4                         |                                                              |
| token             | VARCHAR   | 0x49d5c2bdffac6ce2bfdb6640f4f80f226bc10bab                         |                                                              |
| tokenAmount       | VARCHAR   | 439047884140865                                                    |                                                              |
| usdgAmount        | VARCHAR   | 764341095788136723                                                 |                                                              |
| feeBasisPoints    | VARCHAR   | 0                                                                  |                                                              |

## 3. Table: Vault\_event\_ClosePosition\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-30 13:41:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 31998829                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xeb90ce961cd378b1b3b36835e6c349f3f99e9c4528044193685c5143f006373a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 68                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ab2de34a33fb459b538c43f251eb825645e8595                         | Address of the contract that produced the log                |
| key               | VARCHAR   | 0xb230fb309edff9004ea94fb1a5b25e98b335382f72515d16818f160764191831 |                                                              |
| size              | VARCHAR   | 1900190427567224664000000000000000                                 |                                                              |
| collateral        | VARCHAR   | 0                                                                  |                                                              |
| averagePrice      | VARCHAR   | 30502628000000000000000000000000000                                |                                                              |
| entryFundingRate  | VARCHAR   | 299142                                                             |                                                              |
| reserveAmount     | VARCHAR   | 0                                                                  |                                                              |
| realisedPnl       | VARCHAR   | -28794935995467115882323057541140                                  |                                                              |

## 4. Table: Vault\_event\_CollectMarginFees\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-03 05:13:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33427213                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcc550b859ca0a24f4e102529fe36b4cfb1d131b2dc9535601b4586d40d48f9bd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ab2de34a33fb459b538c43f251eb825645e8595                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0xb31f66aa3c1e785363f0875a1b74e27b85fd66c7                         |                                                              |
| feeUsd            | VARCHAR   | 553706666666666666665282400000                                     |                                                              |
| feeTokens         | VARCHAR   | 44435171067062568                                                  |                                                              |

## 5. Table: Vault\_event\_CollectSwapFees\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-10 21:58:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 32438170                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x74724f79cfcc2b7e8a6b5f356fc2cddd4ebb6ffba102c9cc9c6ec238fa828b67 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 9                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ab2de34a33fb459b538c43f251eb825645e8595                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x152b9d0fdc40c096757f570a51e494bd4b943e50                         |                                                              |
| feeUsd            | VARCHAR   | 59929679700000000000000000000                                      |                                                              |
| feeTokens         | VARCHAR   | 198                                                                |                                                              |

## 6. Table: Vault\_event\_DecreaseGuaranteedUsd\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-16 01:12:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 28800749                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x94df8e324012ffc5e07a32632e27c8cbc2c971931a68b8aa4d5cd0af34d7f9a2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 8                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ab2de34a33fb459b538c43f251eb825645e8595                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x152b9d0fdc40c096757f570a51e494bd4b943e50                         |                                                              |
| amount            | VARCHAR   | 271574874090169000000000000000000000                               |                                                              |

## 7. Table: Vault\_event\_DecreasePoolAmount\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-22 00:49:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 23943169                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa9655fe5bcfb64add4feaee8ed20151d1dedfe0a9dd1a8cdb526699e94be4a98 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 29                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ab2de34a33fb459b538c43f251eb825645e8595                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x152b9d0fdc40c096757f570a51e494bd4b943e50                         |                                                              |
| amount            | VARCHAR   | 437536                                                             |                                                              |

## 8. Table: Vault\_event\_DecreasePosition\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-24 13:08:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 20218130                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc417547fe0d7c0ab4c41705184770f9f05aaceab67f44ab9a712ef97f22459ec | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 14                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ab2de34a33fb459b538c43f251eb825645e8595                         | Address of the contract that produced the log                |
| key               | VARCHAR   | 0xa00b19bfade586aca86408ea3eb5fbd7b3aa4c995d96ec24033b0139dfed5efd |                                                              |
| account           | VARCHAR   | 0x37ce4be6ccde73a47a9117364571e2a71acf956c                         |                                                              |
| collateralToken   | VARCHAR   | 0x152b9d0fdc40c096757f570a51e494bd4b943e50                         |                                                              |
| indexToken        | VARCHAR   | 0x152b9d0fdc40c096757f570a51e494bd4b943e50                         |                                                              |
| collateralDelta   | VARCHAR   | 0                                                                  |                                                              |
| sizeDelta         | VARCHAR   | 96961376828400000000000000000000000                                |                                                              |
| isLong            | VARCHAR   | true                                                               |                                                              |
| price             | VARCHAR   | 19214000000000000000000000000000000                                |                                                              |
| fee               | VARCHAR   | 97930990596684000000000000000000                                   |                                                              |

## 9. Table: Vault\_event\_DecreaseReservedAmount\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-16 20:42:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13509643                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbc7df2c84804b32da17631b8b8f25ee3c4a572b98caffc8df8cda4f4525c107c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ab2de34a33fb459b538c43f251eb825645e8595                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0xa7d7079b0fead91f3e65f86e8915cb59c1a4c664                         |                                                              |
| amount            | VARCHAR   | 4716764739                                                         |                                                              |

## 10. Table: Vault\_event\_DecreaseUsdgAmount\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-25 01:18:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33039792                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x631378ed143735165cca57fe4a20293e890fba9fdf9a811d2293ffab4810dd24 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ab2de34a33fb459b538c43f251eb825645e8595                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x152b9d0fdc40c096757f570a51e494bd4b943e50                         |                                                              |
| amount            | VARCHAR   | 4851687650236007663118                                             |                                                              |

## 11. Table: Vault\_event\_DirectPoolDeposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-04 07:57:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9116431                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x814a2fbfb4da0c9e96df2b7c6a8cc736cbdcf75fab52224258646d213976f730 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 19                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ab2de34a33fb459b538c43f251eb825645e8595                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x130966628846bfd36ff31a822705796e8cb8c18d                         |                                                              |
| amount            | VARCHAR   | 1500000000000000000000                                             |                                                              |

## 12. Table: Vault\_event\_IncreaseGuaranteedUsd\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-04 18:25:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33493233                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8f4724c8ddbe1978752b73a9edf14182e1574ad97ea15dea67d50c690122e82a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ab2de34a33fb459b538c43f251eb825645e8595                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0xb31f66aa3c1e785363f0875a1b74e27b85fd66c7                         |                                                              |
| amount            | VARCHAR   | 9669793154039497972583165430988                                    |                                                              |

## 13. Table: Vault\_event\_IncreasePoolAmount\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-22 01:19:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 31637952                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x79ec35173138be5910c7b1af15e09ce944f7d61b256eff934cbbf36d431174a7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ab2de34a33fb459b538c43f251eb825645e8595                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x130966628846bfd36ff31a822705796e8cb8c18d                         |                                                              |
| amount            | VARCHAR   | 65086830380000000000                                               |                                                              |

## 14. Table: Vault\_event\_IncreasePosition\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-13 01:00:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29945647                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6a67789f94750b73ebda3f3a8da162b7655688110bf91f105ad5a5643e8634c5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 25                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ab2de34a33fb459b538c43f251eb825645e8595                         | Address of the contract that produced the log                |
| key               | VARCHAR   | 0x1c183db3251ea48d70f328e206afd4f9746cc7b820ca7dfaed4b46454afeb8a2 |                                                              |
| account           | VARCHAR   | 0x2465204fde2ee7b9f58d3f63710a9ed197281c31                         |                                                              |
| collateralToken   | VARCHAR   | 0x152b9d0fdc40c096757f570a51e494bd4b943e50                         |                                                              |
| indexToken        | VARCHAR   | 0x152b9d0fdc40c096757f570a51e494bd4b943e50                         |                                                              |
| collateralDelta   | VARCHAR   | 231567581612000000000000000000000                                  |                                                              |
| sizeDelta         | VARCHAR   | 11027934132928020000000000000000000                                |                                                              |
| isLong            | VARCHAR   | true                                                               |                                                              |
| price             | VARCHAR   | 26873965000000000000000000000000000                                |                                                              |
| fee               | VARCHAR   | 11027934132928020000000000000000                                   |                                                              |

## 15. Table: Vault\_event\_IncreaseReservedAmount\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-04 15:52:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30903894                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2948279e72d6635902337aec5a4c44237ef1449fbc5567359ba7d07722af05f2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ab2de34a33fb459b538c43f251eb825645e8595                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x152b9d0fdc40c096757f570a51e494bd4b943e50                         |                                                              |
| amount            | VARCHAR   | 8147138                                                            |                                                              |

## 16. Table: Vault\_event\_IncreaseUsdgAmount\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-09 06:58:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11879019                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9d49f1b38674332e8043c75fb4503ff18a95961e90002325d5243d976c8e1b11 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ab2de34a33fb459b538c43f251eb825645e8595                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x49d5c2bdffac6ce2bfdb6640f4f80f226bc10bab                         |                                                              |
| amount            | VARCHAR   | 8527047724982480613940                                             |                                                              |

## 17. Table: Vault\_event\_LiquidatePosition\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-06 14:41:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 32255607                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4ddb62428f452925b0f015fe4120d5594a7a7615375908dd203b2ed526734125 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 17                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ab2de34a33fb459b538c43f251eb825645e8595                         | Address of the contract that produced the log                |
| key               | VARCHAR   | 0xae41a6d78431f246f3d291e88ae0917cb34afa14d1f4964fbd2bd1adafb1a44b |                                                              |
| account           | VARCHAR   | 0x991d5e956eec31cfcf48ee4962833cc67b5cb51e                         |                                                              |
| collateralToken   | VARCHAR   | 0x152b9d0fdc40c096757f570a51e494bd4b943e50                         |                                                              |
| indexToken        | VARCHAR   | 0x152b9d0fdc40c096757f570a51e494bd4b943e50                         |                                                              |
| isLong            | VARCHAR   | true                                                               |                                                              |
| size              | VARCHAR   | 239928221588326498730735499632000                                  |                                                              |
| collateral        | VARCHAR   | 9915285138011673501269264500368                                    |                                                              |
| reserveAmount     | VARCHAR   | 785993                                                             |                                                              |
| realisedPnl       | VARCHAR   | 0                                                                  |                                                              |
| markPrice         | VARCHAR   | 29894439000000000000000000000000000                                |                                                              |

## 18. Table: Vault\_event\_SellUSDG\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-04 02:22:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30880039                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6f5f8dbb76625f0d6253f8970476b6d9db5d1593ea6e84fd0f198e2e0350491a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 56                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ab2de34a33fb459b538c43f251eb825645e8595                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x6dc099dd341559ddb4495a488e6f0147d88e7e3c                         |                                                              |
| token             | VARCHAR   | 0x152b9d0fdc40c096757f570a51e494bd4b943e50                         |                                                              |
| usdgAmount        | VARCHAR   | 990329690353063748                                                 |                                                              |
| tokenAmount       | VARCHAR   | 3656                                                               |                                                              |
| feeBasisPoints    | VARCHAR   | 3                                                                  |                                                              |

## 19. Table: Vault\_event\_Swap\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2023-01-16 22:14:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 25032535                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x9af757fc770172405c5dfde747993cf51a34543342a6b842991ec47df5ae3c0c | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 8                                                                  | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x9ab2de34a33fb459b538c43f251eb825645e8595                         | Address of the contract that produced the log                |
| account            | VARCHAR   | 0x4e6063f675706b87b802e751f227e7e0282400dd                         |                                                              |
| tokenIn            | VARCHAR   | 0xa7d7079b0fead91f3e65f86e8915cb59c1a4c664                         |                                                              |
| tokenOut           | VARCHAR   | 0xb97ef9ef8734c71904d8002f8b6bc66dd9c48a6e                         |                                                              |
| amountIn           | VARCHAR   | 45886839                                                           |                                                              |
| amountOut          | VARCHAR   | 45886839                                                           |                                                              |
| amountOutAfterFees | VARCHAR   | 45882250                                                           |                                                              |
| feeBasisPoints     | VARCHAR   | 1                                                                  |                                                              |

## 20. Table: Vault\_event\_UpdateFundingRate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-01 05:19:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 32026213                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc2e2fc3057a167d82ac5de9b691b5351e248f2ec73bf21de836ebfaca8e3a315 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ab2de34a33fb459b538c43f251eb825645e8595                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x49d5c2bdffac6ce2bfdb6640f4f80f226bc10bab                         |                                                              |
| fundingRate       | VARCHAR   | 292235                                                             |                                                              |

## 21. Table: Vault\_event\_UpdatePnl\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-01 00:53:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30750761                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4686a48bb31a9a0c023b5ffffe7b0b57ade743a47e20be308b55b0879b7e6c87 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ab2de34a33fb459b538c43f251eb825645e8595                         | Address of the contract that produced the log                |
| key               | VARCHAR   | 0xa75a9dc2541b5ddd4092924016ff51d73769944ffa777094943b1afcd98e4795 |                                                              |
| hasProfit         | VARCHAR   | true                                                               |                                                              |
| delta             | VARCHAR   | 53042344523233798647424914473463                                   |                                                              |

## 22. Table: Vault\_event\_UpdatePosition\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-28 01:18:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 22929910                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x11895f82d02e9c2435ad8c8d1d4368e6c1fa1c72df7ca2751bc128f5befa9e17 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 48                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ab2de34a33fb459b538c43f251eb825645e8595                         | Address of the contract that produced the log                |
| key               | VARCHAR   | 0x380133a36135276c56d2dbcbbf43dbef63256dda542217e1f96581a090eff538 |                                                              |
| size              | VARCHAR   | 480528989605000000000000000000000                                  |                                                              |
| collateral        | VARCHAR   | 318390396802929205000000000000000                                  |                                                              |
| averagePrice      | VARCHAR   | 15966934011177148510335406181520926                                |                                                              |
| entryFundingRate  | VARCHAR   | 36758                                                              |                                                              |
| reserveAmount     | VARCHAR   | 3009524                                                            |                                                              |
| realisedPnl       | VARCHAR   | 0                                                                  |                                                              |
| markPrice         | VARCHAR   | 16299140000000000000000000000000000                                |                                                              |
