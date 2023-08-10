# bancor\_network

## 1. Table: BancorConverterFactory\_event\_NewConverter\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-20 10:45:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9908843                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x90ce9b49b650aaa01e68579bb480bb0614a4b3e7fdbf7e0cdbbdc92907adf1a6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 28                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3cc4a258aff14a88380ca3d9703d6bbfb7a8042e                         | Address of the contract that produced the log                |
| \_converter       | VARCHAR   | 0xceab75d622feeabf02a2a3d40af00956f0707702                         |                                                              |
| \_owner           | VARCHAR   | 0xc724bc5f3dd616c8fadb75a23c00c13880a6268f                         |                                                              |

## 2. Table: BancorConverterFactory\_v2\_event\_NewConverter\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-21 03:24:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11097041                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7e3887732bf52b9f22ae0900df1d11e0b3615efbdf881e208fb7c9c0ad8cba97 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 27                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4ade0e57bc2e129f62547af4d620fb40d28ea269                         | Address of the contract that produced the log                |
| \_type            | VARCHAR   | 1                                                                  |                                                              |
| \_converter       | VARCHAR   | 0xcbb50b9a3c587ff59b61702a9bb93b6ff0220ba9                         |                                                              |
| \_owner           | VARCHAR   | 0xcff01c40fa47faff359b6b31ebac86f7958be486                         |                                                              |

## 3. Table: ContractRegistry\_event\_AddressUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-07 12:43:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8694983                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1f144906b304305fbc65d88b9121caa4056fb0395da35c8b01b5431891cce8ec | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x52ae12abe5d8bd778bd5397f99ca900624cfadd4                         | Address of the contract that produced the log                |
| \_contractName    | VARCHAR   | 0x42616e636f724e6574776f726b5061746846696e646572000000000000000000 |                                                              |
| \_contractAddress | VARCHAR   | 0xdb4d6f8019f7a1bb1f629b2088eb27504ed8b137                         |                                                              |

## 4. Table: ContractRegistry\_event\_OwnerUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-10-23 10:01:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6567982                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe16a72a996373fd00b0d8718256576e7bb838aa884a7a28f832896af47638def | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x52ae12abe5d8bd778bd5397f99ca900624cfadd4                         | Address of the contract that produced the log                |
| \_prevOwner       | VARCHAR   | 0x50249160741773b1fed5aca6c7608d8ef6b50c64                         |                                                              |
| \_newOwner        | VARCHAR   | 0x51a3ac2399c89ffa893b0f627c740c05193875a6                         |                                                              |

## 5. Table: Converter\_event\_Activation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-05 22:16:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10402041                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5b97ec495a8251ad74555724a6206b2937cddb6eab9c763f41bf3d1c4f71cfa8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 27                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x53e9c0ee79ab9ccb46939685e1e62245adf90cba                         | Address of the contract that produced the log                |
| \_anchor          | VARCHAR   | 0x9db9ccfc66e5cacdef842c2f04fcd7d31c3fa137                         |                                                              |
| \_activated       | VARCHAR   | true                                                               |                                                              |

## 6. Table: Converter\_event\_ConversionFeeUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-18 16:50:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10685183                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x853f37ba3e77ea077b3cee2f2390c5c49cc4bb0efb7081538eb3fc9a4bdbed5b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 215                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe870d00176b2c71afd4c43cea550228e22be4abd                         | Address of the contract that produced the log                |
| \_prevFee         | VARCHAR   | 1000                                                               |                                                              |
| \_newFee          | VARCHAR   | 0                                                                  |                                                              |

## 7. Table: Converter\_event\_Conversion\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-11 00:55:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11630481                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd23c5ca6662630707d127ebabf4063e329d8c9ded9c387b8d27103c7c7661357 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfbbaf86d76ef7c86f1aea216242ef8e203a8be7e                         | Address of the contract that produced the log                |
| \_fromToken       | VARCHAR   | 0x1f573d6fb3f13d689ff844b4ce37794d79a7ff1c                         |                                                              |
| \_toToken         | VARCHAR   | 0x6710c63432a2de02954fc0f851db07146a6c0312                         |                                                              |
| \_trader          | VARCHAR   | 0x2f9ec37d6ccfff1cab21733bdadede11c823ccb0                         |                                                              |
| \_amount          | VARCHAR   | 1218659110251051614208                                             |                                                              |
| \_return          | VARCHAR   | 126336553647928504294951                                           |                                                              |
| \_conversionFee   | VARCHAR   | 761444104535008907597                                              |                                                              |

## 8. Table: Converter\_event\_LiquidityAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-22 00:34:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10706861                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb99203ab58e3fa397e903e38da0597a0beeffcfacaf066edcdf432c562bce219 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 241                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe870d00176b2c71afd4c43cea550228e22be4abd                         | Address of the contract that produced the log                |
| \_provider        | VARCHAR   | 0xd8650ccd2f8331cfb9ae9efcee0cd08175f7f824                         |                                                              |
| \_reserveToken    | VARCHAR   | 0x1f573d6fb3f13d689ff844b4ce37794d79a7ff1c                         |                                                              |
| \_amount          | VARCHAR   | 236501390796956037610                                              |                                                              |
| \_newBalance      | VARCHAR   | 3882777475721072146885070                                          |                                                              |
| \_newSupply       | VARCHAR   | 11558818459182187990459070                                         |                                                              |

## 9. Table: Converter\_event\_LiquidityRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-13 18:10:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10452754                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x86e1b68cbdea0e6e0fa3743b546e12397f5740a565586ba54fb4b73f1d06f663 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 46                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1a7ec550f463138f283c542d755cc28c5b6e26c3                         | Address of the contract that produced the log                |
| \_provider        | VARCHAR   | 0xbe30f7f47a35d6713776d1fd383da63f72ebb4a8                         |                                                              |
| \_reserveToken    | VARCHAR   | 0x8ae56a6850a7cbeac3c3ab2cb311e7620167eac8                         |                                                              |
| \_amount          | VARCHAR   | 7722439562698653749                                                |                                                              |
| \_newBalance      | VARCHAR   | 49952836334202969650614                                            |                                                              |
| \_newSupply       | VARCHAR   | 4822934158735480921261                                             |                                                              |

## 10. Table: Converter\_event\_OwnerUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-20 13:13:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8968523                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xac53a5961277e9bad6cf71b629e1ac9fd742d2b9134a06cd13c9fb7989373162 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 97                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x78d951e60129b17e29eda5faf4b2d7e4b1621e37                         | Address of the contract that produced the log                |
| \_prevOwner       | VARCHAR   | 0x99d8fb9f0b5b8828a677365be34280803c208232                         |                                                              |
| \_newOwner        | VARCHAR   | 0x20412bd6d146309c55cc607d30c5aad07fbf6148                         |                                                              |

## 11. Table: Converter\_event\_PriceDataUpdate\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2019-12-24 20:41:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 9157453                                                            | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x1c84502b7d452a534841fa9f79ca401f50cda065e83eaf8c1119f386a2a2821e | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 20                                                                 | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x9c248517b92ae226b88a0a0c28de02b9b7b039d3                         | Address of the contract that produced the log                |
| \_connectorToken   | VARCHAR   | 0xc0829421c1d260bd3cb3e0f06cfe2d52db2ce315                         |                                                              |
| \_tokenSupply      | VARCHAR   | 68529290254163969266367532                                         |                                                              |
| \_connectorBalance | VARCHAR   | 13371961253294517207069                                            |                                                              |
| \_connectorWeight  | VARCHAR   | 100000                                                             |                                                              |

## 12. Table: Converter\_event\_TokenRateUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-29 23:17:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11753695                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xac35d924b16e86bbdf626462d87284565c4f1915bd9031faa0b90d7017c03b68 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 335                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc964de24878b04afdf6a7df5e7956decc665d4be                         | Address of the contract that produced the log                |
| \_token1          | VARCHAR   | 0x2843f6c3b14e698e3d7562584959c61274f93328                         |                                                              |
| \_token2          | VARCHAR   | 0xe3818504c1b32bf1557b16c238b2e01fd3149c17                         |                                                              |
| \_rateN           | VARCHAR   | 1269096464477211448930058000000                                    |                                                              |
| \_rateD           | VARCHAR   | 43121979589244932030000000000                                      |                                                              |

## 13. Table: Converter\_v2\_event\_Activation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-18 15:04:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10684694                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x776b4dd8b878700e4cdd2ab769a36858fd07864e20810a029507b31912a92357 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 25                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb993e230195b5799559dfc35371be2d017f4d6f6                         | Address of the contract that produced the log                |
| \_type            | VARCHAR   | 2                                                                  |                                                              |
| \_anchor          | VARCHAR   | 0xc42a9e06cebf12ae96b11f8bae9acc3d6b016237                         |                                                              |
| \_activated       | VARCHAR   | false                                                              |                                                              |

## 14. Table: Converter\_v2\_event\_ConversionFeeUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-21 04:38:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10701475                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd6be673ba7196bc63d7a278425b52e79a587ff526bcdb494ae1fa2aa4b1fb2e9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 148                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x05840ca15bef62b48fd2248cb688860c8a69adff                         | Address of the contract that produced the log                |
| \_prevFee         | VARCHAR   | 0                                                                  |                                                              |
| \_newFee          | VARCHAR   | 1000                                                               |                                                              |

## 15. Table: Converter\_v2\_event\_Conversion\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-01 04:15:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11768152                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x502f6711eada36832b192caf7629299b0acd6e808fefa4a19f522f16cf65bf64 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 157                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xab56b87b9288a9a236ef38e762eb324dbe5e49f8                         | Address of the contract that produced the log                |
| \_fromToken       | VARCHAR   | 0x0ae055097c6d159879521c384f1d2123d1f195e6                         |                                                              |
| \_toToken         | VARCHAR   | 0x1f573d6fb3f13d689ff844b4ce37794d79a7ff1c                         |                                                              |
| \_trader          | VARCHAR   | 0x000000002605006ff4ad30ac969f0726821ebd7c                         |                                                              |
| \_amount          | VARCHAR   | 155977361256878868246                                              |                                                              |
| \_return          | VARCHAR   | 1387606818410174018684                                             |                                                              |
| \_conversionFee   | VARCHAR   | 14016230488991656754                                               |                                                              |

## 16. Table: Converter\_v2\_event\_LiquidityAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-19 06:56:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11084949                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x40138cdd122037124def6604b13c82edc88b5e9eaa0711cfb5043a1c59f31869 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 215                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd1a758f84bf6762bdf6f795a9ddee35eb0597ee4                         | Address of the contract that produced the log                |
| \_provider        | VARCHAR   | 0xc6bb76d4db067495f8b9b545e6e1cc9e550f3ff3                         |                                                              |
| \_reserveToken    | VARCHAR   | 0x1f573d6fb3f13d689ff844b4ce37794d79a7ff1c                         |                                                              |
| \_amount          | VARCHAR   | 256459117690863756632                                              |                                                              |
| \_newBalance      | VARCHAR   | 1837239950527773520461                                             |                                                              |
| \_newSupply       | VARCHAR   | 35724889115406                                                     |                                                              |

## 17. Table: Converter\_v2\_event\_LiquidityRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-18 13:29:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11679545                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb61fe1e327df1dad24250b19bd371fca3507dd17eae9fac4786aa3666bc18aa8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 240                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xab56b87b9288a9a236ef38e762eb324dbe5e49f8                         | Address of the contract that produced the log                |
| \_provider        | VARCHAR   | 0x9ab934010e6f2d633feeb5b6f1ddceeded601bcf                         |                                                              |
| \_reserveToken    | VARCHAR   | 0x1f573d6fb3f13d689ff844b4ce37794d79a7ff1c                         |                                                              |
| \_amount          | VARCHAR   | 1768589204311358651875                                             |                                                              |
| \_newBalance      | VARCHAR   | 55995163302554314294716                                            |                                                              |
| \_newSupply       | VARCHAR   | 22698302432337987615756                                            |                                                              |

## 18. Table: Converter\_v2\_event\_OwnerUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-14 23:27:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11056826                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd23a751da46deb14d2360c53dfea6e22a46b0f196ea63e62441cb7a220433c92 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 35                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x615fed2b7a84537e729d3dd32de150bf0253ff10                         | Address of the contract that produced the log                |
| \_prevOwner       | VARCHAR   | 0x1647f8480c65528aff347602460c3ff9429cef4d                         |                                                              |
| \_newOwner        | VARCHAR   | 0x973b1e385659e317dd43b49c29e45e66c0275696                         |                                                              |

## 19. Table: Converter\_v2\_event\_TokenRateUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-16 09:04:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10670201                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x304330b0fa0f366ed4258c917a46e557539786a31d033c42ef7913dbb9fef963 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 33                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0911ee3fa4c45fd68601cb4206c09b4afc84c384                         | Address of the contract that produced the log                |
| \_token1          | VARCHAR   | 0x0c485bffd5df019f66927b2c32360159884d4409                         |                                                              |
| \_token2          | VARCHAR   | 0x1f573d6fb3f13d689ff844b4ce37794d79a7ff1c                         |                                                              |
| \_rateN           | VARCHAR   | 132446399536162934464474000000                                     |                                                              |
| \_rateD           | VARCHAR   | 52146226618303109983451500000                                      |                                                              |
