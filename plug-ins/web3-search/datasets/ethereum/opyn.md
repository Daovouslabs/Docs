# opyn

## 1. Table: OptionsFactory\_event\_AssetAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-25 16:41:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10932920                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4319a48d56aaf2cad8c81a6fd74a1fc0e43bf0028df3675f9568d86194bceb3d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 203                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcc5d905b9c2c8c9329eb4e25dc086369d6c7777c                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xc33e514e79311fe606801af4b4f343c83a3b72dca711239a516f2103673922d1 |                                                              |
| addr              | VARCHAR   | 0xc011a73ee8576fb46f5e1c5751ca3b9fe0af2a6f                         |                                                              |

## 2. Table: OptionsFactory\_event\_AssetChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |
| addr              | VARCHAR   |                                                              |             |

## 3. Table: OptionsFactory\_event\_AssetDeleted\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |

## 4. Table: OptionsFactory\_event\_OptionsContractCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-21 19:15:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10111083                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfd7121976245f5f3c02c6556f8794e6eaa5c71ce01c7834f88d74b8772fd6ce9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 55                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcc5d905b9c2c8c9329eb4e25dc086369d6c7777c                         | Address of the contract that produced the log                |
| addr              | VARCHAR   | 0x4edf4f93a45fad46e5a2450bfcffe8ff53d0a5b2                         |                                                              |

## 5. Table: OptionsFactory\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-14 23:15:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10266804                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0cfbcc8aba43d77cf300d7af66c71c1f97f797da2a8fb7081ae9c774834dd3a8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 199                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcc5d905b9c2c8c9329eb4e25dc086369d6c7777c                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x9e68b67660c223b3e0634d851f5df821e0e17d84                         |                                                              |
| newOwner          | VARCHAR   | 0x87887cf0e37d937f989ab76b99e4f4682da044c4                         |                                                              |

## 6. Table: oToken\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-05 03:11:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10203219                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x245c1afbc42c2c17a87d688aa62da19caab824e454e2046e2e43637ec5052df6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 96                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4edf4f93a45fad46e5a2450bfcffe8ff53d0a5b2                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x39246c4f3f6592c974ebc44f80ba6dc69b817c71                         |                                                              |
| spender           | VARCHAR   | 0xeb2cc32f4b1d8e498619be6960030fdffb1e7c47                         |                                                              |
| value             | VARCHAR   | 8647376298                                                         |                                                              |

## 7. Table: oToken\_event\_BurnOTokens\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-01 18:07:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11368147                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa287e2cbe16bdea9c176adaa3c510f5c22ead873ca228834e42b6e1579deb244 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 118                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbc1e2390d693ad617142500e3b7094606433c234                         | Address of the contract that produced the log                |
| vaultOwner        | VARCHAR   | 0x2a4e6c78f12333481a6d932ba526eb56bd64f008                         |                                                              |
| oTokensBurned     | VARCHAR   | 213190000                                                          |                                                              |

## 8. Table: oToken\_event\_ERC20CollateralAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-09 23:24:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11024177                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x029f0275fa525d2594090ca5f0a7e240e278a840bf0ced36c8bd5e1ac6a9c6a7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 269                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0578779e746d7186253a36cf651ea786acfcf087                         | Address of the contract that produced the log                |
| vaultOwner        | VARCHAR   | 0x4b5160ab8efec1742f20a74428e08790cbc90a48                         |                                                              |
| amount            | VARCHAR   | 1000000000                                                         |                                                              |
| payer             | VARCHAR   | 0x4b5160ab8efec1742f20a74428e08790cbc90a48                         |                                                              |

## 9. Table: oToken\_event\_ETHCollateralAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-24 17:33:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11517688                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x310ea62aebd8dbfd23a91181553c6118fbc3dd7aa60228f904af681b83260600 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 204                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x95d52139a62df9abdc9db3996a810c1d319ecd23                         | Address of the contract that produced the log                |
| vaultOwner        | VARCHAR   | 0x639e4bb8d28d477beba288da38696948df14d68e                         |                                                              |
| amount            | VARCHAR   | 8300000000000000000                                                |                                                              |
| payer             | VARCHAR   | 0x639e4bb8d28d477beba288da38696948df14d68e                         |                                                              |

## 10. Table: oToken\_event\_Exercise\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2021-01-21 04:58:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 11696798                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0xc12dfd0046f6b1562a57d610c3e000bfe17c31b216af5205c69028ea6007507f | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 141                                                                | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x2e40fe398483ddc20e296c2a75e5cea07f629b9c                         | Address of the contract that produced the log                |
| amtUnderlyingToPay | VARCHAR   | 1597475295                                                         |                                                              |
| amtCollateralToPay | VARCHAR   | 399368823750000000000                                              |                                                              |
| exerciser          | VARCHAR   | 0xd0a8b9b78eeb93f932a4dcc9b9bcdc83a9255b31                         |                                                              |
| vaultExercisedFrom | VARCHAR   | 0x3d44bc69dbbe0cdde8fafb278ff9f75c9e09a1e5                         |                                                              |

## 11. Table: oToken\_event\_IssuedOTokens\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-15 09:43:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11456878                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdea2185bfdb5d9f9288cb0b3dd9ecfb8a166787b7f5c007d76719c9d301248e0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 264                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x76e73543a14de519575d5efea050f9958b0b484f                         | Address of the contract that produced the log                |
| issuedTo          | VARCHAR   | 0x76e73543a14de519575d5efea050f9958b0b484f                         |                                                              |
| oTokensIssued     | VARCHAR   | 47314156                                                           |                                                              |
| vaultOwner        | VARCHAR   | 0xc5df4d5ed23f645687a867d8f83a41836fcf8811                         |                                                              |

## 12. Table: oToken\_event\_Liquidate\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2020-08-04 20:01:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 10595329                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0xc329be13c96712b2d446e0700c84a93acafd8d6b2764aca68a70d495c1740cb2 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 91                                                                 | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x3cbfc1397def0602c2d211c70a1c0c38cedb5448                         | Address of the contract that produced the log                |
| amtCollateralToPay | VARCHAR   | 0                                                                  |                                                              |
| vaultOwner         | VARCHAR   | 0x24dd242c3c4061b1fcaa5119af608b56afbaea95                         |                                                              |
| liquidator         | VARCHAR   | 0xb72e60ea1d0c04605f406c158dce9ac6ae6d224c                         |                                                              |

## 13. Table: oToken\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-22 21:13:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11108421                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x544d40435db852ed2872869848d94f274bb6695005dde578bcf176b50c510949 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 24                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x06e9061947c592f07fb66e569aa3052fa230b068                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0xcc5d905b9c2c8c9329eb4e25dc086369d6c7777c                         |                                                              |

## 14. Table: oToken\_event\_RedeemVaultBalance\_history

| Column                | Type      | Example                                                            | Description                                                  |
| --------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp      | TIMESTAMP | 2020-04-24 11:04:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number         | INTEGER   | 9934851                                                            | The block number where this event was emitted                |
| transaction\_hash     | VARCHAR   | 0xa635f6112a4063bca02b94b562df662710cab24879b7af10cc277f9b7d1ec074 | Hash of the transactions in which this event was emitted     |
| log\_index            | INTEGER   | 33                                                                 | Integer of the log index position in the block of this event |
| contract\_address     | VARCHAR   | 0x6c79f10543c7886c6946b8a996f824e474bac8f2                         | Address of the contract that produced the log                |
| amtCollateralRedeemed | VARCHAR   | 10000000000                                                        |                                                              |
| amtUnderlyingRedeemed | VARCHAR   | 0                                                                  |                                                              |
| vaultOwner            | VARCHAR   | 0x27003ba96fbf876018ca6117acf338f0212c811f                         |                                                              |

## 15. Table: oToken\_event\_RemoveCollateral\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-23 00:46:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11708637                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x98e0a18fe263863bd5d10f5efb6b03ed7eff708701205c56b35ba7048d3c422e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 79                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcad0c9aff9f44f86bcce10f8ffeb14b3d199997f                         | Address of the contract that produced the log                |
| amtRemoved        | VARCHAR   | 427000000                                                          |                                                              |
| vaultOwner        | VARCHAR   | 0x076c95c6cd2eb823acc6347fdf5b3dd9b83511e4                         |                                                              |

## 16. Table: oToken\_event\_RemoveUnderlying\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-07 12:12:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10412232                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbdc89256c53bdfcb101c161c21d3232d90576d4f652ab72b00664313abc06d71 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 96                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa337bce3112a1b11cb1a916e3b7b6a5ccb61a15d                         | Address of the contract that produced the log                |
| amountUnderlying  | VARCHAR   | 6500000000000000000                                                |                                                              |
| vaultOwner        | VARCHAR   | 0x264f0864c48f61871757f72ca04d6a4c4ace9b63                         |                                                              |

## 17. Table: oToken\_event\_TransferFee\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| to                | VARCHAR   |                                                              |             |
| fees              | VARCHAR   |                                                              |             |

## 18. Table: oToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-07 22:15:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11610173                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5d0bc6586ebd69ef5c59e248e3f94d6ad2ce72c3593439734bb1965999b6048b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 137                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2e40fe398483ddc20e296c2a75e5cea07f629b9c                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x39246c4f3f6592c974ebc44f80ba6dc69b817c71                         |                                                              |
| to                | VARCHAR   | 0x707caa394108290d901e3fbf15d2b1a703639eea                         |                                                              |
| value             | VARCHAR   | 24000000                                                           |                                                              |

## 19. Table: oToken\_event\_UpdateParameters\_history

| Column                    | Type      | Example                                                            | Description                                                  |
| ------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp          | TIMESTAMP | 2020-11-19 21:15:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number             | INTEGER   | 11290862                                                           | The block number where this event was emitted                |
| transaction\_hash         | VARCHAR   | 0x4eec4c9cb3c6e8f57cf077b728083c18dcc964023c43c1db58bafb8dcae841e3 | Hash of the transactions in which this event was emitted     |
| log\_index                | INTEGER   | 75                                                                 | Integer of the log index position in the block of this event |
| contract\_address         | VARCHAR   | 0x0376ae94db1bad7774eb2ba646ff61715b4b5d82                         | Address of the contract that produced the log                |
| liquidationIncentive      | VARCHAR   | 0                                                                  |                                                              |
| liquidationFactor         | VARCHAR   | 0                                                                  |                                                              |
| transactionFee            | VARCHAR   | 0                                                                  |                                                              |
| minCollateralizationRatio | VARCHAR   | 10                                                                 |                                                              |
| owner                     | VARCHAR   | 0x87887cf0e37d937f989ab76b99e4f4682da044c4                         |                                                              |

## 20. Table: oToken\_event\_VaultOpened\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-19 00:12:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9899546                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x74dd87e8528e14ddbfa748b8461aa2e48a6228c6878d87a8c70d95680c925974 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 181                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x461cd647add2159e85ad57141cb5371566fceed3                         | Address of the contract that produced the log                |
| vaultOwner        | VARCHAR   | 0x4f50d47d20380172746527bbeaa274940c38efac                         |                                                              |
