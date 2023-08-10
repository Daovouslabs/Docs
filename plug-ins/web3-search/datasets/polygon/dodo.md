# dodo

## 1. Table: DODORouteProxy\_event\_OrderHistory\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-15 10:57:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 21396456                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcb504010d72ddbca1a99b017784eaae2781a9239c4c95ceffb163ba520313da3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 197                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2fa4334cfd7c56a0e7ca02bd81455205fcbdc5e9                         | Address of the contract that produced the log                |
| fromToken         | VARCHAR   | 0x08e175a1eac9744a0f1ccaeb8f669af6a2bda3ce                         |                                                              |
| toToken           | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| sender            | VARCHAR   | 0x510786f789c14f3f897ee66af60972f5a47bc108                         |                                                              |
| fromAmount        | VARCHAR   | 118500000000000000                                                 |                                                              |
| returnAmount      | VARCHAR   | 530626546705895507                                                 |                                                              |

## 2. Table: DODORouteProxy\_v2\_event\_OrderHistory\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-09 21:53:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 23532994                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xba16cb1f6ba30ddb0f2afe7da5614b686a51ff5fea5c72dbc99bd4e456506056 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 76                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa222e6a71d1a1dd5f279805fbe38d5329c1d0e70                         | Address of the contract that produced the log                |
| fromToken         | VARCHAR   | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                         |                                                              |
| toToken           | VARCHAR   | 0x0169ec1f8f639b32eec6d923e24c2a2ff45b9dd6                         |                                                              |
| sender            | VARCHAR   | 0x8b51e11b673b8a47b3558af8380add9acfc19356                         |                                                              |
| fromAmount        | VARCHAR   | 400000000                                                          |                                                              |
| returnAmount      | VARCHAR   | 14551658677552820588248                                            |                                                              |

## 3. Table: DODORouteProxy\_v2\_event\_OwnershipTransferPrepared\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner     | VARCHAR   |                                                              |             |
| newOwner          | VARCHAR   |                                                              |             |

## 4. Table: DODORouteProxy\_v2\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner     | VARCHAR   |                                                              |             |
| newOwner          | VARCHAR   |                                                              |             |

## 5. Table: DODOZoo\_event\_DODOBirth\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-04 15:12:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 20976090                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x789a749f1f98bf2ac4a415974ed049274110661838d28a315686c776719a2d53 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 153                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x357c5e9cfa8b834edcef7c7aabd8f9db09119d11                         | Address of the contract that produced the log                |
| newBorn           | VARCHAR   | 0xb16f2ff8e8499e31b257d2a02d25e8956ae6afe7                         |                                                              |
| baseToken         | VARCHAR   | 0xf4b3a195587d2735b656b7ffe9060f478faf1b32                         |                                                              |
| quoteToken        | VARCHAR   | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                         |                                                              |

## 6. Table: DODOZoo\_event\_OwnershipTransferPrepared\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-11 09:24:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14359534                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x55de8cf638282480c0d0066ca182c376f3ca453b24f10f7f6ac54abdc8760ec7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 14                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x357c5e9cfa8b834edcef7c7aabd8f9db09119d11                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x16cc37d06fe5061cd0023fb8d142abaabb396a2b                         |                                                              |
| newOwner          | VARCHAR   | 0x3cd6d7f5ff977bf8069548ea1f9441b061162b42                         |                                                              |

## 7. Table: DODOZoo\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-17 11:46:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14602893                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x32e966f9f64b2a8a06962ff0e2c08900d1370071b8fcc8e1011c1b5dff1265ac | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 674                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x357c5e9cfa8b834edcef7c7aabd8f9db09119d11                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x16cc37d06fe5061cd0023fb8d142abaabb396a2b                         |                                                              |
| newOwner          | VARCHAR   | 0x3cd6d7f5ff977bf8069548ea1f9441b061162b42                         |                                                              |

## 8. Table: DODO\_event\_BuyBaseToken\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-25 22:45:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 40768438                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x63c95ad9ac84fd48904ee810a917710df7c761c3cd7b5ef383d8199db24d9072 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 26                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x813fddeccd0401c4fa73b092b074802440544e52                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x022f87dec1a4292882dccbaf8796aefcc212b394                         |                                                              |
| receiveBase       | VARCHAR   | 626651883                                                          |                                                              |
| payQuote          | VARCHAR   | 625968747                                                          |                                                              |

## 9. Table: DODO\_event\_ChargeMaintainerFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-12 07:39:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 42606085                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x634a251cc089e484f1ed0c27dc7532606726660aeeef98e4d8cd3ca5858749b5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 269                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x813fddeccd0401c4fa73b092b074802440544e52                         | Address of the contract that produced the log                |
| maintainer        | VARCHAR   | 0x3cd6d7f5ff977bf8069548ea1f9441b061162b42                         |                                                              |
| isBaseToken       | VARCHAR   | true                                                               |                                                              |
| amount            | VARCHAR   | 8261                                                               |                                                              |

## 10. Table: DODO\_event\_ChargePenalty\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-14 20:58:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 21372809                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1dfc580996e665577d25ae98fd4b47484f4dd377387cb8a83f4341677652aa48 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 313                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x813fddeccd0401c4fa73b092b074802440544e52                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0x22bf900bdfd4cdf0af25e142bf0d12f383c6ba75                         |                                                              |
| isBaseToken       | VARCHAR   | true                                                               |                                                              |
| amount            | VARCHAR   | 246                                                                |                                                              |

## 11. Table: DODO\_event\_ClaimAssets\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-08 11:30:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 22275843                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x85eb22ee10933763974976dbcf796eb55c1febceb22269f4d9528ffc5455b0c1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 141                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3d9d765b0fbaf594f90f07bc42889473e6613c7a                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x253956aedc059947e700071bc6d74bd8e34fe2ab                         |                                                              |
| baseTokenAmount   | VARCHAR   | 0                                                                  |                                                              |
| quoteTokenAmount  | VARCHAR   | 0                                                                  |                                                              |

## 12. Table: DODO\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-04 08:21:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 31504004                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x163a923ab202a71611b732f199fa2d827aa2461e7f48c5c1c73b60fa13140546 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 163                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x813fddeccd0401c4fa73b092b074802440544e52                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0x69554b32c001fd161aa48bae6fd8785767087672                         |                                                              |
| receiver          | VARCHAR   | 0x69554b32c001fd161aa48bae6fd8785767087672                         |                                                              |
| isBaseToken       | VARCHAR   | true                                                               |                                                              |
| amount            | VARCHAR   | 5363806                                                            |                                                              |
| lpTokenAmount     | VARCHAR   | 4762110                                                            |                                                              |

## 13. Table: DODO\_event\_Donate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-07 06:39:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 37772406                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x55217eacf11e836e0307a67bc9af37cea38efb1258fa4d476d301d46ba998512 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x813fddeccd0401c4fa73b092b074802440544e52                         | Address of the contract that produced the log                |
| amount            | VARCHAR   | 0                                                                  |                                                              |
| isBaseToken       | VARCHAR   | false                                                              |                                                              |

## 14. Table: DODO\_event\_OwnershipTransferPrepared\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-05 02:49:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 20995462                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x184d6285e629ea93b758a0ce7eb36bab4a0474afa6c7cf5d5a8ddb96869ec994 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 241                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb16f2ff8e8499e31b257d2a02d25e8956ae6afe7                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x3cd6d7f5ff977bf8069548ea1f9441b061162b42                         |                                                              |
| newOwner          | VARCHAR   | 0x16cc37d06fe5061cd0023fb8d142abaabb396a2b                         |                                                              |

## 15. Table: DODO\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-05 02:51:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 20995524                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc3099fef55b13dabbd40415f0912c44b1128885f6777eee0b87f7238906de44a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 293                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa46f5ec3219f956d14c6816ef9cf6cabf13bdd77                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x3cd6d7f5ff977bf8069548ea1f9441b061162b42                         |                                                              |
| newOwner          | VARCHAR   | 0x16cc37d06fe5061cd0023fb8d142abaabb396a2b                         |                                                              |

## 16. Table: DODO\_event\_SellBaseToken\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-08 19:47:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 40118769                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xacf8182753acf86f4cb3f085dc7822912cfa2edbe6a864a0f873143e7f654fe3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 9                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x813fddeccd0401c4fa73b092b074802440544e52                         | Address of the contract that produced the log                |
| seller            | VARCHAR   | 0x0773edc0438b2ef18fc535b21d0ac77912c308c0                         |                                                              |
| payBase           | VARCHAR   | 3030896766                                                         |                                                              |
| receiveQuote      | VARCHAR   | 3030865351                                                         |                                                              |

## 17. Table: DODO\_event\_UpdateLiquidityProviderFeeRate\_history

| Column                      | Type      | Example                                                            | Description                                                  |
| --------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp            | TIMESTAMP | 2021-11-26 01:24:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number               | INTEGER   | 21804524                                                           | The block number where this event was emitted                |
| transaction\_hash           | VARCHAR   | 0x6a492834d8222d0cc8e0995147cd314a9b8be5fdc313437b4faf5de41b6c7387 | Hash of the transactions in which this event was emitted     |
| log\_index                  | INTEGER   | 445                                                                | Integer of the log index position in the block of this event |
| contract\_address           | VARCHAR   | 0xb16f2ff8e8499e31b257d2a02d25e8956ae6afe7                         | Address of the contract that produced the log                |
| oldLiquidityProviderFeeRate | VARCHAR   | 0                                                                  |                                                              |
| newLiquidityProviderFeeRate | VARCHAR   | 3000000000000000                                                   |                                                              |

## 18. Table: DODO\_event\_UpdateMaintainerFeeRate\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2022-01-20 13:46:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 23948234                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x00bc27144e40c08da0b968bd115066f34d692d18d33b64232a1ebf1a85b3bc2c | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 222                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x813fddeccd0401c4fa73b092b074802440544e52                         | Address of the contract that produced the log                |
| oldMaintainerFeeRate | VARCHAR   | 0                                                                  |                                                              |
| newMaintainerFeeRate | VARCHAR   | 20000000000000                                                     |                                                              |

## 19. Table: DODO\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-21 02:46:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 23970374                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd17bf4ccff5d34497fa3052a2e00c92aca089068fe6f59d5bbce283e3547d8c9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 150                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x813fddeccd0401c4fa73b092b074802440544e52                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0x958b6ac6a7cec484352eb88a8b71fd90df316791                         |                                                              |
| receiver          | VARCHAR   | 0x958b6ac6a7cec484352eb88a8b71fd90df316791                         |                                                              |
| isBaseToken       | VARCHAR   | false                                                              |                                                              |
| amount            | VARCHAR   | 500000455                                                          |                                                              |
| lpTokenAmount     | VARCHAR   | 390167125                                                          |                                                              |

## 20. Table: DPPFactory\_event\_NewDPP\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-28 09:01:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 31230383                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0ae5128f2e4e3255005b38be1daab7cc6b57f0748bc4b14091a48fa2002dc878 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 188                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd24153244066f0afa9415563bfc7ba248bfb7a51                         | Address of the contract that produced the log                |
| baseToken         | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         |                                                              |
| quoteToken        | VARCHAR   | 0x7289d73034b2aa8eff303cba5d9c45691590885c                         |                                                              |
| creator           | VARCHAR   | 0x4d5bf05e1b2a0c8e89521b87ceb7770a4ada58ef                         |                                                              |
| dpp               | VARCHAR   | 0xc37c438648bef6d2c8de94cf18cec90203be9339                         |                                                              |

## 21. Table: DPPFactory\_event\_RemoveDPP\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-23 15:11:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 27484955                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdb9353034c73861c58fce30583973936d589bc8b32ad755562185d72f171c769 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 278                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd24153244066f0afa9415563bfc7ba248bfb7a51                         | Address of the contract that produced the log                |
| dpp               | VARCHAR   | 0xd093179f318a5f232d386da02f7bc3624174fbb2                         |                                                              |

## 22. Table: DPP\_event\_DODOFlashLoan\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-13 03:04:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 19046347                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5fa5c569b6da1df2b34db3f8f5e482c1cddcf06bbdc3e6cf8583c67d8dea8cbe | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 171                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x10dd6d8a29d489bede472cc1b22dc695c144c5c7                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0x091798fd4266fab398e4de0c7d72f9038d13a5b8                         |                                                              |
| assetTo           | VARCHAR   | 0x091798fd4266fab398e4de0c7d72f9038d13a5b8                         |                                                              |
| baseAmount        | VARCHAR   | 0                                                                  |                                                              |
| quoteAmount       | VARCHAR   | 622231951                                                          |                                                              |

## 23. Table: DPP\_event\_DODOSwap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-06 21:52:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45994080                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf334830f2df8734039e911a91bf26c03dda4c830e7d2e2badfd7a2c0cca045e8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 396                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb5f7d510c6c6412eda5554bc7ae40391c9b66599                         | Address of the contract that produced the log                |
| fromToken         | VARCHAR   | 0xc2132d05d31c914a87c6611c10748aeb04b58e8f                         |                                                              |
| toToken           | VARCHAR   | 0xfb021f1ce0d5327ee31efe21f9b23c0b9a9ccc58                         |                                                              |
| fromAmount        | VARCHAR   | 42                                                                 |                                                              |
| toAmount          | VARCHAR   | 637                                                                |                                                              |
| trader            | VARCHAR   | 0xefa413de95fd661346c6de01342b4779df2dd517                         |                                                              |
| receiver          | VARCHAR   | 0x0c88f9becf2782e9b77c8d1adf433a5f13f4330a                         |                                                              |

## 24. Table: DSPFactory\_event\_NewDSP\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-13 14:56:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16820061                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x060f58e65f456b2041f19a23596f6aa12685467f5b42237b27b831508a359976 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 351                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x43c49f8dd240e1545f147211ec9f917376ac1e87                         | Address of the contract that produced the log                |
| baseToken         | VARCHAR   | 0xa4267447628e96e2a73ef258772ba0df49af45a9                         |                                                              |
| quoteToken        | VARCHAR   | 0x13246d97d8bf790b40f4f077fe6add710cc166e3                         |                                                              |
| creator           | VARCHAR   | 0xffc73a1317e3b023062dc86f6b0d335954bbf59f                         |                                                              |
| DSP               | VARCHAR   | 0xc0d9c8d85ac2ca53f0d1338793abca22e82471eb                         |                                                              |

## 25. Table: DSPFactory\_event\_RemoveDSP\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| DSP               | VARCHAR   |                                                              |             |

## 26. Table: DSP\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-21 05:15:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 22776680                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa40798637f515ed5464b7f6395170744dcdb287838d1dd6cc8f89491da4055ef | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 679                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x077da961d0ebdc2efa4ac9308da126e84810233b                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x310f6b7625dd1f48f99f0d7dafbf43b8893545ba                         |                                                              |
| value             | VARCHAR   | 28232790499418937385                                               |                                                              |

## 27. Table: DSP\_event\_BuyShares\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-13 14:56:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16820061                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x060f58e65f456b2041f19a23596f6aa12685467f5b42237b27b831508a359976 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 356                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc0d9c8d85ac2ca53f0d1338793abca22e82471eb                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0xffc73a1317e3b023062dc86f6b0d335954bbf59f                         |                                                              |
| increaseShares    | VARCHAR   | 100000000000000000000000000000000                                  |                                                              |
| totalShares       | VARCHAR   | 100000000000000000000000000000000                                  |                                                              |

## 28. Table: DSP\_event\_DODOFlashLoan\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-23 04:58:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45409830                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe2814ea95e31b6079d28e92b5e3fc84f43cb3df1215e2e45b8024554e096ead7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 95                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0362f28c4928cb5d1ea88b95d5c04fa770aa9c67                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0xefa413de95fd661346c6de01342b4779df2dd517                         |                                                              |
| assetTo           | VARCHAR   | 0xefa413de95fd661346c6de01342b4779df2dd517                         |                                                              |
| baseAmount        | VARCHAR   | 2198809056467194675                                                |                                                              |
| quoteAmount       | VARCHAR   | 0                                                                  |                                                              |

## 29. Table: DSP\_event\_DODOSwap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-24 08:18:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 34734440                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x35a140d99c3c0512021c01e396c22c4e1c3ea5766ded76e0a0fa4c213568daf7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 115                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8ab8219208b9aec6c49e0b4242803f0ebe704323                         | Address of the contract that produced the log                |
| fromToken         | VARCHAR   | 0x369582d2010b6ed950b571f4101e3bb9b554876f                         |                                                              |
| toToken           | VARCHAR   | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                         |                                                              |
| fromAmount        | VARCHAR   | 63080754754906579210                                               |                                                              |
| toAmount          | VARCHAR   | 81163092                                                           |                                                              |
| trader            | VARCHAR   | 0xa222e6a71d1a1dd5f279805fbe38d5329c1d0e70                         |                                                              |
| receiver          | VARCHAR   | 0xdef171fe48cf0115b1d80b88dc8eab59176fee57                         |                                                              |

## 30. Table: DSP\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-13 10:52:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 27084718                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2044e7ee6f3eba319eb3cfe58001a85b360453dfa6f92c41b5d2272af96296e2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 251                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2503b2afeacc2476ecd975daeb783f679b69aec9                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x6647a1c54486645cce6a10cd5a1fc59f885a0e72                         |                                                              |
| value             | VARCHAR   | 69979000000000000000                                               |                                                              |

## 31. Table: DSP\_event\_RChange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-29 19:23:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30147380                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x794be7a035487c54d65b0f4bc72dc12191978db47a37caa5d842f43460bf6a99 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 282                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x68da1079a99130b162f34c762639eb242f893747                         | Address of the contract that produced the log                |
| newRState         | VARCHAR   | 1                                                                  |                                                              |

## 32. Table: DSP\_event\_SellShares\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-07 21:19:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29290045                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdeef326cb3bf1f217e0a7a507b2c88dc7cb32250b849738e2920b4551f2c3004 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 255                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xac992250b76bf825cf10d02c13553b4cf016535b                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0x4cbd885555906f60ab4e13cb873e2314c438f8b9                         |                                                              |
| to                | VARCHAR   | 0x4cbd885555906f60ab4e13cb873e2314c438f8b9                         |                                                              |
| decreaseShares    | VARCHAR   | 20093511931                                                        |                                                              |
| totalShares       | VARCHAR   | 202964767                                                          |                                                              |

## 33. Table: DSP\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-18 19:30:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 27295914                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0cbd1904a9449fb144649f5b282de031db5fb3e92a80c4f9ee81b110c99381c9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 184                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe54b12f8d65fb99271dc1561f22e426ac2f9ea81                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x815201ff5d97ab0106ebba1509506f4865942714                         |                                                              |
| amount            | VARCHAR   | 99500                                                              |                                                              |

## 34. Table: DVMFactory\_event\_NewDVM\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-19 15:58:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 40532508                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x67bbaef261e80859aed87111d054c0ac5e3bd7806912f3feb4cfff3f68a17606 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 32                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x79887f65f83bdf15bcc8736b5e5bcdb48fb8fe13                         | Address of the contract that produced the log                |
| baseToken         | VARCHAR   | 0x712502daee557e04c6063b451ff97c3635de86bb                         |                                                              |
| quoteToken        | VARCHAR   | 0x9a42dc7edb66f881bf779d884ff3209e0fa57a51                         |                                                              |
| creator           | VARCHAR   | 0x2029ba7ad196da403c6c42fa77dca798aec5ed90                         |                                                              |
| dvm               | VARCHAR   | 0x05191fdcf20117a41cb5f80a7b17b330498474e4                         |                                                              |

## 35. Table: DVMFactory\_event\_RemoveDVM\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| dvm               | VARCHAR   |                                                              |             |

## 36. Table: DVM\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-27 06:08:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 25377837                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x53940d95e7b53cd7dcc3ede2ec4c2b02a17980f0fe1a09415c96ce67910113ff | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 34                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x581c7db44f2616781c86c331d31c1f09db87a746                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x923e337670c54e637c2d7a5652de5e4c7e496921                         |                                                              |
| value             | VARCHAR   | 11384574830881610163                                               |                                                              |

## 37. Table: DVM\_event\_BuyShares\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-25 10:29:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 25319393                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3cec35f97a8727a32d71ea04ce7a08b6faf18ab96b25dcff336b0f3b7e40b16f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 238                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x104d128dc393c4a382bd1b035e0f04a6e042214b                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0x2b1b01a06c8a4ee35cf29f7a6c2e2597ce2cec91                         |                                                              |
| increaseShares    | VARCHAR   | 228028428335092222                                                 |                                                              |
| totalShares       | VARCHAR   | 228028428335092222                                                 |                                                              |

## 38. Table: DVM\_event\_DODOFlashLoan\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-11 13:25:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 44951506                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3b3de7165e4ff2d600517cff81303df605d2277d1320a6a66f2ecea35c03dbc7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 104                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd028e331c9a29a1b5de87279bf79de5ff04fe98b                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0x1e8fedd7a16e4d6a869d0e1c8636d98f7504b4f5                         |                                                              |
| assetTo           | VARCHAR   | 0x1e8fedd7a16e4d6a869d0e1c8636d98f7504b4f5                         |                                                              |
| baseAmount        | VARCHAR   | 0                                                                  |                                                              |
| quoteAmount       | VARCHAR   | 17661999999900000                                                  |                                                              |

## 39. Table: DVM\_event\_DODOSwap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-11 03:46:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 44935399                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x281ae612c265a578eeb5718f82431dfe0a238e6afb71c9cdecf11468473f197e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 619                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe4e5a63c11c6ecd792aef46200117d47803edd32                         | Address of the contract that produced the log                |
| fromToken         | VARCHAR   | 0xe4bf2864ebec7b7fdf6eeca9bacae7cdfdaffe78                         |                                                              |
| toToken           | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         |                                                              |
| fromAmount        | VARCHAR   | 1192609653357693050                                                |                                                              |
| toAmount          | VARCHAR   | 154309452033058155                                                 |                                                              |
| trader            | VARCHAR   | 0x6c30be15d88462b788dea7c6a860a2ccaf7b2670                         |                                                              |
| receiver          | VARCHAR   | 0x2fa4334cfd7c56a0e7ca02bd81455205fcbdc5e9                         |                                                              |

## 40. Table: DVM\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-26 00:21:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 22964523                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7dbce4e0a9bb62fadd03a93e0d360ecd7e8c57c8bc9fda85d03ef793f9e85d56 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 172                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0f20c4148369fb70083593b1475922bec87aebe3                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x77b77b0c6a7253dfdeb7a5264c0594c7d3e5ac50                         |                                                              |
| value             | VARCHAR   | 27120581157385832823                                               |                                                              |

## 41. Table: DVM\_event\_SellShares\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-02 19:40:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45831019                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x77472035e5a2a90fa1b8ec2e11a355c0afc4e2c77a7575c3150f9757902ce593 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 229                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0c93a5746c41e831852d4c7cfb720e6f19495023                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0xa67f4d6dd924cd89587fc742365970716f9a8f51                         |                                                              |
| to                | VARCHAR   | 0xa67f4d6dd924cd89587fc742365970716f9a8f51                         |                                                              |
| decreaseShares    | VARCHAR   | 917264178996                                                       |                                                              |
| totalShares       | VARCHAR   | 17428019400962                                                     |                                                              |

## 42. Table: DVM\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-06 17:02:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 37749487                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7ad1710c6981efb47fc79ba8afa383442817ce4ec5a1e3c5adf92b191266fabc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 207                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x71d487d735f9a293188c7936af19703a9b56154c                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x15f9bf593e4e39476d5ca8a66ee98a5dc1593439                         |                                                              |
| amount            | VARCHAR   | 174249376243750000000000000000                                     |                                                              |
