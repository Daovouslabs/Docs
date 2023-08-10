# aave

## 1. Table: AToken\_event\_Approval\_history

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

## 2. Table: AToken\_event\_BalanceTransfer\_history

| Column                | Type      | Example                                                      | Description |
| --------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp      | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number         | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash     | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index            | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address     | VARCHAR   | Address of the contract that produced the log                |             |
| \_from                | VARCHAR   |                                                              |             |
| \_to                  | VARCHAR   |                                                              |             |
| \_value               | VARCHAR   |                                                              |             |
| \_fromBalanceIncrease | VARCHAR   |                                                              |             |
| \_toBalanceIncrease   | VARCHAR   |                                                              |             |
| \_fromIndex           | VARCHAR   |                                                              |             |
| \_toIndex             | VARCHAR   |                                                              |             |

## 3. Table: AToken\_event\_BurnOnLiquidation\_history

| Column                | Type      | Example                                                      | Description |
| --------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp      | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number         | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash     | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index            | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address     | VARCHAR   | Address of the contract that produced the log                |             |
| \_from                | VARCHAR   |                                                              |             |
| \_value               | VARCHAR   |                                                              |             |
| \_fromBalanceIncrease | VARCHAR   |                                                              |             |
| \_fromIndex           | VARCHAR   |                                                              |             |

## 4. Table: AToken\_event\_InterestRedirectionAllowanceChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_from            | VARCHAR   |                                                              |             |
| \_to              | VARCHAR   |                                                              |             |

## 5. Table: AToken\_event\_InterestStreamRedirected\_history

| Column                | Type      | Example                                                      | Description |
| --------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp      | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number         | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash     | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index            | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address     | VARCHAR   | Address of the contract that produced the log                |             |
| \_from                | VARCHAR   |                                                              |             |
| \_to                  | VARCHAR   |                                                              |             |
| \_redirectedBalance   | VARCHAR   |                                                              |             |
| \_fromBalanceIncrease | VARCHAR   |                                                              |             |
| \_fromIndex           | VARCHAR   |                                                              |             |

## 6. Table: AToken\_event\_MintOnDeposit\_history

| Column                | Type      | Example                                                      | Description |
| --------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp      | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number         | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash     | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index            | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address     | VARCHAR   | Address of the contract that produced the log                |             |
| \_from                | VARCHAR   |                                                              |             |
| \_value               | VARCHAR   |                                                              |             |
| \_fromBalanceIncrease | VARCHAR   |                                                              |             |
| \_fromIndex           | VARCHAR   |                                                              |             |

## 7. Table: AToken\_event\_Redeem\_history

| Column                | Type      | Example                                                      | Description |
| --------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp      | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number         | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash     | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index            | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address     | VARCHAR   | Address of the contract that produced the log                |             |
| \_from                | VARCHAR   |                                                              |             |
| \_value               | VARCHAR   |                                                              |             |
| \_fromBalanceIncrease | VARCHAR   |                                                              |             |
| \_fromIndex           | VARCHAR   |                                                              |             |

## 8. Table: AToken\_event\_RedirectedBalanceUpdated\_history

| Column                     | Type      | Example                                                      | Description |
| -------------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp           | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number              | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash          | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index                 | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address          | VARCHAR   | Address of the contract that produced the log                |             |
| \_targetAddress            | VARCHAR   |                                                              |             |
| \_targetBalanceIncrease    | VARCHAR   |                                                              |             |
| \_targetIndex              | VARCHAR   |                                                              |             |
| \_redirectedBalanceAdded   | VARCHAR   |                                                              |             |
| \_redirectedBalanceRemoved | VARCHAR   |                                                              |             |

## 9. Table: AToken\_event\_Transfer\_history

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

## 10. Table: AToken\_v2\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-27 14:20:28+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11536309                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5e5d96375dfaf01f9e1e13f960a59335ef66e57574e19b072d791343917767f6             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 185                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x030ba81f1c18d280636f32af80b9aad02cf0854e                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x3b4512e84017ec2dbc24e97006b47318807e1d3f                                     |                                                              |
| spender           | VARCHAR   | 0x0a87c89b5007ff406ab5280abdd80fc495ec238e                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 11. Table: AToken\_v2\_event\_BalanceTransfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-13 19:58:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13018848                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x14b5b141c743673046b4058f88d5a962590670d3dbef93d6e033830f1626e638 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 451                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xffc97d72e13e01096502cb8eb52dee56f74dad7b                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xc3eb5e143bbdcc5a5b1b5385229de4bf79da4cad                         |                                                              |
| to                | VARCHAR   | 0x498c5431eb517101582988fbb36431ddaac8f4b1                         |                                                              |
| value             | VARCHAR   | 96718738706752656724                                               |                                                              |
| index             | VARCHAR   | 1000083247779197198547502099                                       |                                                              |

## 12. Table: AToken\_v2\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-12 12:41:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16168693                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x340337292a22e97794e0673fea2b407fb0899a45195df67c4a2582457646a18c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 133                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x028171bca77440897b824ca71d1c56cac55b68a3                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x00a25c455636cc01bffcb717db900a6d4c767a8a                         |                                                              |
| target            | VARCHAR   | 0x00a25c455636cc01bffcb717db900a6d4c767a8a                         |                                                              |
| value             | VARCHAR   | 200000352785413754628357                                           |                                                              |
| index             | VARCHAR   | 1078519805096090338826772926                                       |                                                              |

## 13. Table: AToken\_v2\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-07 05:31:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12976021                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xec85ab568a06f8f7ec9f32761310107cf9173e698407740422b93778215957d2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 201                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xffc97d72e13e01096502cb8eb52dee56f74dad7b                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xe019372c6fdb1274c6dd6104b947d7a9d1139796                         |                                                              |
| value             | VARCHAR   | 3255845549885754960                                                |                                                              |
| index             | VARCHAR   | 1000083212110431614737299338                                       |                                                              |

## 14. Table: AToken\_v2\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-29 14:14:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17152279                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x909664038e6bfadd0c3751058b164db709ec059ee9176a5680bf32287adac87c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 274                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x028171bca77440897b824ca71d1c56cac55b68a3                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x464c71f6c2f760dda6093dcb91c24c39e5d6e18c                         |                                                              |
| value             | VARCHAR   | 49162186594180471738                                               |                                                              |

## 15. Table: AToken\_v3\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-08 10:17:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17648398                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2e612d5366c6d6dfa90b2a3bd63fb19f18f12f4373e73ca4a7636c1aab1c0dfd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 262                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4d5f47fa6a74757f35c14fd3a6ef8e3c9bc514e8                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x0ca7e7e5745bd457f5ed7265ff2cd1c8208575e1                         |                                                              |
| spender           | VARCHAR   | 0x1809f186d680f239420b56948c58f8dbbcdf1e18                         |                                                              |
| value             | VARCHAR   | 10994624171853745000                                               |                                                              |

## 16. Table: AToken\_v3\_event\_BalanceTransfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-13 11:25:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17250745                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xee254b659f4ecf08829ca95607eeb58c5e4f6df2ed56688ad5db96dcbf507d18 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 209                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0b925ed163218f6662a35e0f0371ac234f9e9371                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x7b2c841ed85c5997713add9b523423aca5cdd796                         |                                                              |
| to                | VARCHAR   | 0x14a09fa327d008a181ef56b067217772182f5d0d                         |                                                              |
| value             | VARCHAR   | 14824679126247676                                                  |                                                              |
| index             | VARCHAR   | 1000358919994625922219503700                                       |                                                              |

## 17. Table: AToken\_v3\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-25 09:37:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16903633                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9904806f7ef466e9b8d3149cd95d89ea24668da1d3cdadae0f685b4c76984098 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 315                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x018008bfb33d285247a21d44e50697654f754e63                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0cd93ed428f4c91c8d58b6e94e716b030e2ceb0c                         |                                                              |
| target            | VARCHAR   | 0x0cd93ed428f4c91c8d58b6e94e716b030e2ceb0c                         |                                                              |
| value             | VARCHAR   | 12153710812042109980886                                            |                                                              |
| balanceIncrease   | VARCHAR   | 126542955268951                                                    |                                                              |
| index             | VARCHAR   | 1002580919293062033790205397                                       |                                                              |

## 18. Table: AToken\_v3\_event\_Initialized\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2023-07-15 14:02:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 17699249                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xae8e542d4fdb5a6a33eeb129bb80f9bf23a1ceb3ef5f6caed1fd634ae3730c0b | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 82                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x00907f9921424583e7ffbfedf84f92b7b2be4977                         | Address of the contract that produced the log                |
| underlyingAsset      | VARCHAR   | 0x40d16fc0246ad3160ccc09b8d0d3a2cd28ae6c2f                         |                                                              |
| pool                 | VARCHAR   | 0x87870bca3f3fd6335c3f4ce8392d69350b4fa4e2                         |                                                              |
| treasury             | VARCHAR   | 0x464c71f6c2f760dda6093dcb91c24c39e5d6e18c                         |                                                              |
| incentivesController | VARCHAR   | 0x8164cc65827dcfe994ab23944cbc90e0aa80bfcb                         |                                                              |
| aTokenDecimals       | VARCHAR   | 18                                                                 |                                                              |
| aTokenName           | VARCHAR   | Aave Ethereum GHO                                                  |                                                              |
| aTokenSymbol         | VARCHAR   | aEthGHO                                                            |                                                              |
| params               | VARCHAR   | 0x                                                                 |                                                              |

## 19. Table: AToken\_v3\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-28 14:54:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17792275                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x670076d1a70e39dcb88b07e0c4e27ff088ed7db462f7f32ed24ff2ae68e8f526 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 242                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa700b4eb416be35b2911fd5dee80678ff64ff6c9                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x02e7b8511831b1b02d9018215a0f8f500ea5c6b3                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x7d83643271420aa016fbfdf8b8d57d3c6b220c0f                         |                                                              |
| value             | VARCHAR   | 22488966603073663                                                  |                                                              |
| balanceIncrease   | VARCHAR   | 0                                                                  |                                                              |
| index             | VARCHAR   | 1000000000000000000000000000                                       |                                                              |

## 20. Table: AToken\_v3\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-22 22:13:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17751572                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xea88363069bd655ed185f59a3d1d8488e9c2f28dacf9e6cca8c522bddd25700e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 339                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x018008bfb33d285247a21d44e50697654f754e63                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x840cffa2a3a6f56eb2f205a06748a8284b683355                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 2556262115501094588105942                                          |                                                              |

## 21. Table: AaveGovernanceV2\_event\_ExecutorAuthorized\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-11 15:42:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11432501                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x86af2695c4095ad78eab6bc2e0dcf6a648673bec8966cbe1ca8d3cadeca0b264 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 194                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xec568fffba86c094cf06b22134b23074dfe2252c                         | Address of the contract that produced the log                |
| executor          | VARCHAR   | 0x61910ecd7e8e942136ce7fe7943f956cea1cc2f7                         |                                                              |

## 22. Table: AaveGovernanceV2\_event\_ExecutorUnauthorized\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| executor          | VARCHAR   |                                                              |             |

## 23. Table: AaveGovernanceV2\_event\_GovernanceStrategyChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-10 20:40:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11427398                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x645324a65e3132aca7f277aea6d72a945593446c8755e99390c82848111698a0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 11                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xec568fffba86c094cf06b22134b23074dfe2252c                         | Address of the contract that produced the log                |
| newStrategy       | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| initiatorChange   | VARCHAR   | 0x46bcf35d96eda5e5f6ec48c7956bb4ed9caba1f2                         |                                                              |

## 24. Table: AaveGovernanceV2\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-23 16:45:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15812087                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1cd4424e0314bfc861590dcbd51ef67eb80d88b1544b4f5711921b76e91a8a31 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 336                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xec568fffba86c094cf06b22134b23074dfe2252c                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x61910ecd7e8e942136ce7fe7943f956cea1cc2f7                         |                                                              |
| newOwner          | VARCHAR   | 0x79426a1c24b2978d90d7a5070a46c65b07bc4299                         |                                                              |

## 25. Table: AaveGovernanceV2\_event\_ProposalCanceled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-24 14:53:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17550096                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3b06abbca75b71aeef22a85785584803dfa3288a2b7bf81ec487d4fb36d32bba | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 90                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xec568fffba86c094cf06b22134b23074dfe2252c                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 249                                                                |                                                              |

## 26. Table: AaveGovernanceV2\_event\_ProposalCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-20 03:25:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17518220                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x280265498b7e9cfc934d8d353235b9672eb319dedb78a8344f4be76b893f2157 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 19                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xec568fffba86c094cf06b22134b23074dfe2252c                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 249                                                                |                                                              |
| creator           | VARCHAR   | 0x55b16934c3661e1990939bc57322554d9b09f262                         |                                                              |
| executor          | VARCHAR   | 0xee56e2b3d491590b5b31738cc34d5232f378a8d5                         |                                                              |
| targets           | VARCHAR   | 0xc002feCEDD712ca0178D90083e702eFcCF639C42                         |                                                              |
| values            | VARCHAR   | 0                                                                  |                                                              |
| signatures        | VARCHAR   | execute()                                                          |                                                              |
| calldatas         | VARCHAR   | 0x                                                                 |                                                              |
| withDelegatecalls | VARCHAR   | true                                                               |                                                              |
| startBlock        | VARCHAR   | 17525420                                                           |                                                              |
| endBlock          | VARCHAR   | 17544620                                                           |                                                              |
| strategy          | VARCHAR   | 0xb7e383ef9b1e9189fc0f71fb30af8aa14377429e                         |                                                              |
| ipfsHash          | VARCHAR   | 0xd1ad8ad41f5f2483c2f18e3c16a85bd87c9aa82f92ff584d27027dd6dec656b0 |                                                              |

## 27. Table: AaveGovernanceV2\_event\_ProposalExecuted\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2023-06-27 09:27:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 17569814                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x9d4e53de352a2684aaf8f280b893865071673fcf8c3b9a7b19345354a088c299 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 191                                                                | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0xec568fffba86c094cf06b22134b23074dfe2252c                         | Address of the contract that produced the log                |
| id                 | VARCHAR   | 250                                                                |                                                              |
| initiatorExecution | VARCHAR   | 0x55b16934c3661e1990939bc57322554d9b09f262                         |                                                              |

## 28. Table: AaveGovernanceV2\_event\_ProposalQueued\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-18 06:15:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14797209                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x093b384af1e2b39a1a2a575124eefab96d0f831e615f6fa8c9e853a953f53f77 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 37                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xec568fffba86c094cf06b22134b23074dfe2252c                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 75                                                                 |                                                              |
| executionTime     | VARCHAR   | 1652940939                                                         |                                                              |
| initiatorQueueing | VARCHAR   | 0xdd659911ecbd4458db07ee7cddec79bf8f859abc                         |                                                              |

## 29. Table: AaveGovernanceV2\_event\_VoteEmitted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-24 01:17:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16694897                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcdc0ba602462c5f4836b02698f01bf2b812771d859a69e33fbd9859b1532d4ea | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 382                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xec568fffba86c094cf06b22134b23074dfe2252c                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 160                                                                |                                                              |
| voter             | VARCHAR   | 0x6fcf7bcd09f92d3cbeea6afca5e016a6798c7766                         |                                                              |
| support           | VARCHAR   | true                                                               |                                                              |
| votingPower       | VARCHAR   | 1000000000000000000                                                |                                                              |

## 30. Table: AaveGovernanceV2\_event\_VotingDelayChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-23 16:45:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15812087                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1cd4424e0314bfc861590dcbd51ef67eb80d88b1544b4f5711921b76e91a8a31 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 334                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xec568fffba86c094cf06b22134b23074dfe2252c                         | Address of the contract that produced the log                |
| newVotingDelay    | VARCHAR   | 7200                                                               |                                                              |
| initiatorChange   | VARCHAR   | 0x61910ecd7e8e942136ce7fe7943f956cea1cc2f7                         |                                                              |

## 31. Table: AaveOracle\_v2\_event\_AssetSourceUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-24 01:15:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17546061                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfb2fc29f90d40463b482b103e3bfb8272184d5c6c13b0ec56db931e06e1211d7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 36                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa50ba011c48153de246e5192c8f9258a2ba79ca9                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xae7ab96520de3a18e5e111b5eaab095312d7fe84                         |                                                              |
| source            | VARCHAR   | 0xade6cba6c45aa8e9d0337cac3d2619eabc39d901                         |                                                              |

## 32. Table: AaveOracle\_v2\_event\_FallbackOracleUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-17 14:11:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11275902                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x55609beb6701b676d116a6fc424534e20dc4cbc941ff25d13b4141dd3c403aab | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 101                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa50ba011c48153de246e5192c8f9258a2ba79ca9                         | Address of the contract that produced the log                |
| fallbackOracle    | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 33. Table: AaveOracle\_v2\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-12 10:04:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12418983                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x875fe0280cfc2d86d8ac27c1d962baa8cc924f7fe0c29add3a97cf730a48d739 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 115                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa50ba011c48153de246e5192c8f9258a2ba79ca9                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0xb9062896ec3a615a4e4444df183f0531a77218ae                         |                                                              |
| newOwner          | VARCHAR   | 0xee56e2b3d491590b5b31738cc34d5232f378a8d5                         |                                                              |

## 34. Table: AaveOracle\_v2\_event\_WethSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-17 14:11:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11275902                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x55609beb6701b676d116a6fc424534e20dc4cbc941ff25d13b4141dd3c403aab | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 122                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa50ba011c48153de246e5192c8f9258a2ba79ca9                         | Address of the contract that produced the log                |
| weth              | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |

## 35. Table: AavePropositionPower\_event\_Approval\_history

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

## 36. Table: AavePropositionPower\_event\_MinterAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-24 14:24:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10925857                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb3c0cafef4ea783623ee41fdcec7836735640596cfee0a3ede28e41d6f1b299d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 77                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x72bbcfc20d355fc3e8ac4ce8fcaf63874f746631                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x51f22ac850d29c879367a77d241734acb276b815                         |                                                              |

## 37. Table: AavePropositionPower\_event\_MinterRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-24 14:45:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10925955                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x95e7b617caddde9547fd6c938c1537cf90724cde2ef20a59fa44baf555f3d429 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 102                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x72bbcfc20d355fc3e8ac4ce8fcaf63874f746631                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x51f22ac850d29c879367a77d241734acb276b815                         |                                                              |

## 38. Table: AavePropositionPower\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-24 14:24:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10925857                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb3c0cafef4ea783623ee41fdcec7836735640596cfee0a3ede28e41d6f1b299d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 78                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x72bbcfc20d355fc3e8ac4ce8fcaf63874f746631                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xb9062896ec3a615a4e4444df183f0531a77218ae                         |                                                              |
| value             | VARCHAR   | 1000000000000000000                                                |                                                              |

## 39. Table: AaveProtoGovernance\_event\_AbstainWins\_history

| Column             | Type      | Example                                                      | Description |
| ------------------ | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number      | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index         | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address  | VARCHAR   | Address of the contract that produced the log                |             |
| proposalId         | VARCHAR   |                                                              |             |
| abstainVotingPower | VARCHAR   |                                                              |             |
| yesVotingPower     | VARCHAR   |                                                              |             |
| noVotingPower      | VARCHAR   |                                                              |             |

## 40. Table: AaveProtoGovernance\_event\_NoWins\_history

| Column             | Type      | Example                                                      | Description |
| ------------------ | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number      | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index         | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address  | VARCHAR   | Address of the contract that produced the log                |             |
| proposalId         | VARCHAR   |                                                              |             |
| abstainVotingPower | VARCHAR   |                                                              |             |
| yesVotingPower     | VARCHAR   |                                                              |             |
| noVotingPower      | VARCHAR   |                                                              |             |

## 41. Table: AaveProtoGovernance\_event\_ProposalCreated\_history

| Column                    | Type      | Example                                                            | Description                                                  |
| ------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp          | TIMESTAMP | 2020-09-25 18:18:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number             | INTEGER   | 10933363                                                           | The block number where this event was emitted                |
| transaction\_hash         | VARCHAR   | 0x9ab6fc8cb16984c5c070e655f8d72882e638961ce6eb9f33d59139e25ed596fe | Hash of the transactions in which this event was emitted     |
| log\_index                | INTEGER   | 304                                                                | Integer of the log index position in the block of this event |
| contract\_address         | VARCHAR   | 0x8a2efd9a790199f4c94c6effe210fce0b4724f52                         | Address of the contract that produced the log                |
| proposalId                | VARCHAR   | 0                                                                  |                                                              |
| ipfsHash                  | VARCHAR   | 0x36a87fc5990289f89465db28799db30222e9b68c3c80e1b145c56b8ea1d1a98e |                                                              |
| proposalType              | VARCHAR   | 0xd694595c564f11d247c779f18a879b58ce0acbd2a948a563ab105f26e405d2fa |                                                              |
| propositionPowerOfCreator | VARCHAR   | 1000000000000000000                                                |                                                              |
| threshold                 | VARCHAR   | 65000000000000000000000000                                         |                                                              |
| maxMovesToVotingAllowed   | VARCHAR   | 3                                                                  |                                                              |
| votingBlocksDuration      | VARCHAR   | 32500                                                              |                                                              |
| validatingBlocksDuration  | VARCHAR   | 6500                                                               |                                                              |
| proposalExecutor          | VARCHAR   | 0x95a4949f09415b12da789e144b2522956620d005                         |                                                              |

## 42. Table: AaveProtoGovernance\_event\_StatusChangeToExecuted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-10 22:10:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13780035                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf16a1b45f1ead58384c23757c8a005dc9a3d606b762bf66dbfe173c0f08cad2a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 67                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8a2efd9a790199f4c94c6effe210fce0b4724f52                         | Address of the contract that produced the log                |
| proposalId        | VARCHAR   | 4                                                                  |                                                              |

## 43. Table: AaveProtoGovernance\_event\_StatusChangeToValidating\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-09 21:46:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13773488                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1f500cf99a5b54ccd3d0ac7fcf6403e15b3028c7e54a8eece5d9aed42183c155 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 52                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8a2efd9a790199f4c94c6effe210fce0b4724f52                         | Address of the contract that produced the log                |
| proposalId        | VARCHAR   | 4                                                                  |                                                              |

## 44. Table: AaveProtoGovernance\_event\_StatusChangeToVoting\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-11 16:42:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11432750                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x37d2dc0df70279db0665b869839f6057e35822aa337ce4895abf4a04839ba401 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 74                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8a2efd9a790199f4c94c6effe210fce0b4724f52                         | Address of the contract that produced the log                |
| proposalId        | VARCHAR   | 3                                                                  |                                                              |
| movesToVoting     | VARCHAR   | 1                                                                  |                                                              |

## 45. Table: AaveProtoGovernance\_event\_VoteCancelled\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2020-09-28 13:17:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 10951189                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x8ce554db65034cfc5efaf966c54ba3944e5ac6009dc35be2b550e132b6aab490 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 133                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x8a2efd9a790199f4c94c6effe210fce0b4724f52                         | Address of the contract that produced the log                |
| proposalId           | VARCHAR   | 0                                                                  |                                                              |
| voter                | VARCHAR   | 0x99391c6f4d33ddac56e0856db4ef0013851031bd                         |                                                              |
| vote                 | VARCHAR   | 1                                                                  |                                                              |
| asset                | VARCHAR   | 0x0671ca7e039af2cf2d2c5e7f1aa261ae78b3ffdf                         |                                                              |
| weight               | VARCHAR   | 1                                                                  |                                                              |
| balance              | VARCHAR   | 7321278634927437769956                                             |                                                              |
| proposalStatusBefore | VARCHAR   | 1                                                                  |                                                              |

## 46. Table: AaveProtoGovernance\_event\_VoteEmitted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-08 17:32:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13766120                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf9b59232948b91817472c27782162bbd7c41d7ce3e129952e65290a6fff24215 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 201                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8a2efd9a790199f4c94c6effe210fce0b4724f52                         | Address of the contract that produced the log                |
| proposalId        | VARCHAR   | 4                                                                  |                                                              |
| voter             | VARCHAR   | 0xc4a936b003bc223df757b35ee52f6da66b062935                         |                                                              |
| vote              | VARCHAR   | 1                                                                  |                                                              |
| asset             | VARCHAR   | 0xa5e83c1a6e56f27f7764e5c5d99a9b8786e3a391                         |                                                              |
| weight            | VARCHAR   | 100                                                                |                                                              |
| balance           | VARCHAR   | 92529610130779253898828                                            |                                                              |

## 47. Table: AaveProtoGovernance\_event\_YesWins\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2020-11-22 16:21:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 11309079                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0xfdddf2a13c91325f7f4fad63cddb5bf42114db07331440db45b5ecffb2220c81 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 104                                                                | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x8a2efd9a790199f4c94c6effe210fce0b4724f52                         | Address of the contract that produced the log                |
| proposalId         | VARCHAR   | 1                                                                  |                                                              |
| abstainVotingPower | VARCHAR   | 0                                                                  |                                                              |
| yesVotingPower     | VARCHAR   | 55597300063563595973641000                                         |                                                              |
| noVotingPower      | VARCHAR   | 0                                                                  |                                                              |

## 48. Table: AaveTokenV2\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-11 17:00:02+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12414324                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcac5f0a306632a383e5dde87112dbd62bb95962d6920fa97c3de14d3a6c6572f             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 8                                                                              | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7fc66500c84a76ad7e9c93437bfc5ac33e2ddae9                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x0000006daea1723962647b7e189d311d757fb793                                     |                                                              |
| spender           | VARCHAR   | 0x0000000476fde29330084b2b0b08a9f7d2ac6f2b                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564012932600395522483838975 |                                                              |

## 49. Table: AaveTokenV2\_event\_DelegateChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-03 05:24:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17832367                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x48316297f00d4da8df5cdc01ad7abbc44c7d553ec14aaa51a68118f8f3da9391 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 61                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7fc66500c84a76ad7e9c93437bfc5ac33e2ddae9                         | Address of the contract that produced the log                |
| delegator         | VARCHAR   | 0x952c2b4ffff5fa12a2dd55e1d1bc1865f2945a65                         |                                                              |
| delegatee         | VARCHAR   | 0x952c2b4ffff5fa12a2dd55e1d1bc1865f2945a65                         |                                                              |
| delegationType    | VARCHAR   | 1                                                                  |                                                              |

## 50. Table: AaveTokenV2\_event\_DelegatedPowerChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-08 06:12:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13376512                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1989798c1bb0e90b162f37b6d6c400b72294e81d41c01d2b6562e98ddde26926 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 213                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7fc66500c84a76ad7e9c93437bfc5ac33e2ddae9                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xc08d3b738bc4f55e81d51a395e60d5a4c69672f0                         |                                                              |
| amount            | VARCHAR   | 3907457994251009723017                                             |                                                              |
| delegationType    | VARCHAR   | 1                                                                  |                                                              |

## 51. Table: AaveTokenV2\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-15 04:11:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14007831                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8958f98b96f3843c50c9ee3cf5ee975457d895e047b105a68d484607b64e4c63 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 20                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7fc66500c84a76ad7e9c93437bfc5ac33e2ddae9                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x00000000003b3cc22af3ae1eac0440bcee416b40                         |                                                              |
| to                | VARCHAR   | 0x1353fe67fff8f376762b7034dc9066f0be15a723                         |                                                              |
| value             | VARCHAR   | 39284849907235273388                                               |                                                              |

## 52. Table: AssetVotingWeightProvider\_event\_AssetWeightSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-01 20:33:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10972370                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9a6b0b9d3c63e82fa21d6d6d0627e7d6cc25b088278e87c3e3f4f012dcbf4e38 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 93                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5ac493b8c2cef1f02f117b9ba2797e7da95574aa                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x0671ca7e039af2cf2d2c5e7f1aa261ae78b3ffdf                         |                                                              |
| setter            | VARCHAR   | 0x8a2efd9a790199f4c94c6effe210fce0b4724f52                         |                                                              |
| weight            | VARCHAR   | 0                                                                  |                                                              |

## 53. Table: AssetVotingWeightProvider\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-24 14:33:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10925905                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xed4788fc138f4bd922ea9c8411b61d5917b6cc72e7bf0581b518aa61c948dd95 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 232                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5ac493b8c2cef1f02f117b9ba2797e7da95574aa                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x51f22ac850d29c879367a77d241734acb276b815                         |                                                              |
| newOwner          | VARCHAR   | 0x8a2efd9a790199f4c94c6effe210fce0b4724f52                         |                                                              |

## 54. Table: EthLendToken\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-21 22:47:47+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16679943                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x85598be1b233ae4e895c36c29b6be4b87a43aad4358ed25a45e04e37f980030d             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 155                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x80fb784b7ed66730e8b1dbd9820afd29931aab03                                     | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x9455e60d8bb9df7c7ba8b0938a18f8b34f73dc16                                     |                                                              |
| \_spender         | VARCHAR   | 0x68b3465833fb72a70ecdf485e0e4c7bd8665fc45                                     |                                                              |
| \_value           | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 55. Table: EthLendToken\_event\_LogBurn\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| owner             | VARCHAR   |                                                              |             |
| value             | VARCHAR   |                                                              |             |

## 56. Table: EthLendToken\_event\_LogBuy\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2017-11-29 10:08:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4643254                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5050ac9ecd1f08dd38e98f86759ea2669beaf244bc7c1c4124b917b9238e30a9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x80fb784b7ed66730e8b1dbd9820afd29931aab03                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x1ad9ff994abdf03cff140e92e111f07e2bff2c24                         |                                                              |
| value             | VARCHAR   | 1250000000000000000000                                             |                                                              |

## 57. Table: EthLendToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-07-12 15:11:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8137001                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe80389f4f92b20b6023c4b620a026157e6c927d885483619acd7f8fbf0cd8b9b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 152                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x80fb784b7ed66730e8b1dbd9820afd29931aab03                         | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0x0260300582cd919047142f8b9a28a21b850de15f                         |                                                              |
| \_to              | VARCHAR   | 0xcb6a511f383e8cab16473d214835495034ac3f0a                         |                                                              |
| \_value           | VARCHAR   | 13500000000000000000000                                            |                                                              |

## 58. Table: Executor\_v2\_event\_CancelledAction\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-30 20:23:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17594437                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf953a37db221574528b8b94a97775cd6cec547d62c88149f01cb632124f1d214 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 176                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xee56e2b3d491590b5b31738cc34d5232f378a8d5                         | Address of the contract that produced the log                |
| actionHash        | VARCHAR   | 0x75822612956dbb6854be1af61a70f10f3cbb95ed3df3e1a516bacfa54b229c95 |                                                              |
| target            | VARCHAR   | 0x5f5c02875a8e9b5a26fbd09040abcfdeb2aa6711                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |
| signature         | VARCHAR   | execute(address)                                                   |                                                              |
| data              | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000 |                                                              |
| executionTime     | VARCHAR   | 0                                                                  |                                                              |
| withDelegatecall  | VARCHAR   | true                                                               |                                                              |

## 59. Table: Executor\_v2\_event\_ExecutedAction\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-31 02:12:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13130558                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdfb2401c9e86a1839c781f87e7fcbc51e382719136da3e0ec499d6bece6d3780 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 128                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xee56e2b3d491590b5b31738cc34d5232f378a8d5                         | Address of the contract that produced the log                |
| actionHash        | VARCHAR   | 0x6f7cfdc6fb2dbcd5382389dad74704f95b47743acaf4d19ae35d7505691b68ae |                                                              |
| target            | VARCHAR   | 0xf442c0fae2e9a157cd0202bd63bf9b932d3aa4c8                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |
| signature         | VARCHAR   | sendMessage()                                                      |                                                              |
| data              | VARCHAR   | 0x                                                                 |                                                              |
| executionTime     | VARCHAR   | 1630355630                                                         |                                                              |
| withDelegatecall  | VARCHAR   | true                                                               |                                                              |
| resultData        | VARCHAR   | 0x                                                                 |                                                              |

## 60. Table: Executor\_v2\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-10 20:57:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11427484                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2006a1bf79e9169ab02f634dcedef31cfdc9b095026e566dab40fdfd605f64e1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 94                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x61910ecd7e8e942136ce7fe7943f956cea1cc2f7                         | Address of the contract that produced the log                |
| newAdmin          | VARCHAR   | 0xec568fffba86c094cf06b22134b23074dfe2252c                         |                                                              |

## 61. Table: Executor\_v2\_event\_NewDelay\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-10 20:47:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11427433                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x101fb723f02545fa8c0bb8e2ab4a2523be0e5bd27e56568d02e1d9a40c004de5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 95                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xee56e2b3d491590b5b31738cc34d5232f378a8d5                         | Address of the contract that produced the log                |
| delay             | VARCHAR   | 86400                                                              |                                                              |

## 62. Table: Executor\_v2\_event\_NewPendingAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newPendingAdmin   | VARCHAR   |                                                              |             |

## 63. Table: Executor\_v2\_event\_QueuedAction\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-14 10:37:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17477634                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9c990c36310e36a058421871510ee429738458a370022c6af0c6f9f6382ffa4d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 411                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xee56e2b3d491590b5b31738cc34d5232f378a8d5                         | Address of the contract that produced the log                |
| actionHash        | VARCHAR   | 0x56083d6503150d9c9b24ebc58e5ef1dd4d2139f4895d0c411954146570e74fb5 |                                                              |
| target            | VARCHAR   | 0x158a6bc04f0828318821bae797f50b0a1299d45b                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |
| signature         | VARCHAR   | execute(address)                                                   |                                                              |
| data              | VARCHAR   | 0x00000000000000000000000076884cafecf1f7d4146da6c4053b18b76bf6ed14 |                                                              |
| executionTime     | VARCHAR   | 1686825431                                                         |                                                              |
| withDelegatecall  | VARCHAR   | true                                                               |                                                              |

## 64. Table: GovernanceParamsProvider\_event\_AssetVotingWeightProviderSet\_history

| Column                    | Type      | Example                                                            | Description                                                  |
| ------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp          | TIMESTAMP | 2020-09-24 14:27:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number             | INTEGER   | 10925871                                                           | The block number where this event was emitted                |
| transaction\_hash         | VARCHAR   | 0xaafa9b8cb85caf801da81a73b6f1bed9e0226f20d981cadde98f05b4ef9b0af6 | Hash of the transactions in which this event was emitted     |
| log\_index                | INTEGER   | 188                                                                | Integer of the log index position in the block of this event |
| contract\_address         | VARCHAR   | 0xf7ff0aee0c2d6fbdea3a85742443e284b62fd0b2                         | Address of the contract that produced the log                |
| setter                    | VARCHAR   | 0x51f22ac850d29c879367a77d241734acb276b815                         |                                                              |
| assetVotingWeightProvider | VARCHAR   | 0x5ac493b8c2cef1f02f117b9ba2797e7da95574aa                         |                                                              |

## 65. Table: GovernanceParamsProvider\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-24 14:32:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10925895                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8e40522daf55d3ae3caf918c5c1a8b2bcefd9b2480c31838155056702d3c7852 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 69                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf7ff0aee0c2d6fbdea3a85742443e284b62fd0b2                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x51f22ac850d29c879367a77d241734acb276b815                         |                                                              |
| newOwner          | VARCHAR   | 0x8a2efd9a790199f4c94c6effe210fce0b4724f52                         |                                                              |

## 66. Table: GovernanceParamsProvider\_event\_PropositionPowerSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-24 14:27:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10925871                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaafa9b8cb85caf801da81a73b6f1bed9e0226f20d981cadde98f05b4ef9b0af6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 187                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf7ff0aee0c2d6fbdea3a85742443e284b62fd0b2                         | Address of the contract that produced the log                |
| setter            | VARCHAR   | 0x51f22ac850d29c879367a77d241734acb276b815                         |                                                              |
| propositionPower  | VARCHAR   | 0x72bbcfc20d355fc3e8ac4ce8fcaf63874f746631                         |                                                              |

## 67. Table: GovernanceParamsProvider\_event\_PropositionPowerThresholdSet\_history

| Column                    | Type      | Example                                                            | Description                                                  |
| ------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp          | TIMESTAMP | 2020-09-24 14:27:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number             | INTEGER   | 10925871                                                           | The block number where this event was emitted                |
| transaction\_hash         | VARCHAR   | 0xaafa9b8cb85caf801da81a73b6f1bed9e0226f20d981cadde98f05b4ef9b0af6 | Hash of the transactions in which this event was emitted     |
| log\_index                | INTEGER   | 186                                                                | Integer of the log index position in the block of this event |
| contract\_address         | VARCHAR   | 0xf7ff0aee0c2d6fbdea3a85742443e284b62fd0b2                         | Address of the contract that produced the log                |
| setter                    | VARCHAR   | 0x51f22ac850d29c879367a77d241734acb276b815                         |                                                              |
| propositionPowerThreshold | VARCHAR   | 2                                                                  |                                                              |

## 68. Table: LendingPoolAddressesProviderRegistry\_v2\_event\_AddressesProviderRegistered\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-30 21:23:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11362563                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbe805ad536372edce92b9b8e25a77ae90a7c2c18df843148ae8ba442f553a42d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x52d306e36e3b6b02c153d0266ff0f85d18bcd413                         | Address of the contract that produced the log                |
| newAddress        | VARCHAR   | 0xb53c1a33016b2dc2ff3653530bff1848a515c8c5                         |                                                              |

## 69. Table: LendingPoolAddressesProviderRegistry\_v2\_event\_AddressesProviderUnregistered\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newAddress        | VARCHAR   |                                                              |             |

## 70. Table: LendingPoolAddressesProviderRegistry\_v2\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-30 15:24:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11360925                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0d3970ee7d60eb11790406bfd74a2f6413aabfeb43fd41b1dabdbae88d79eee1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 157                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x52d306e36e3b6b02c153d0266ff0f85d18bcd413                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0xbd723fc4f1d737dcfc48a07fe7336766d34cad5f                         |                                                              |

## 71. Table: LendingPoolAddressesProvider\_event\_EthereumAddressUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newAddress        | VARCHAR   |                                                              |             |

## 72. Table: LendingPoolAddressesProvider\_event\_FeeProviderUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-22 12:46:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10315612                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x718a84b802169c30208c8cd635629654b054a1fb7017dcd07ac942c5cae40cd1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 142                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x24a42fd28c976a61df5d00d0599c34c4f90748c8                         | Address of the contract that produced the log                |
| newAddress        | VARCHAR   | 0x4be4e50fdc97be51a26e2b516d73c189904a071f                         |                                                              |

## 73. Table: LendingPoolAddressesProvider\_event\_LendingPoolConfiguratorUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-08 16:19:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9241011                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9b56eaed8e864f970f7c4bf308af9d5cd93061fa8053604f71be3df7c01b6890 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x24a42fd28c976a61df5d00d0599c34c4f90748c8                         | Address of the contract that produced the log                |
| newAddress        | VARCHAR   | 0xb61306c8eb34a2104d9eb8d84f1bb1001067fa4b                         |                                                              |

## 74. Table: LendingPoolAddressesProvider\_event\_LendingPoolCoreUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-08 16:18:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9241008                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x744a53a26ea64651c648083e469117b2794b179d8e2b3348b2d36d327913726d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x24a42fd28c976a61df5d00d0599c34c4f90748c8                         | Address of the contract that produced the log                |
| newAddress        | VARCHAR   | 0x0752139330bb7550097a9dd9111570ee4e3b534a                         |                                                              |

## 75. Table: LendingPoolAddressesProvider\_event\_LendingPoolDataProviderUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-08 16:22:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9241017                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x27208919cd257359dfd0d10c4eaaff9b3d224d30bab85f2eeab1fa04e51dcc5e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 37                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x24a42fd28c976a61df5d00d0599c34c4f90748c8                         | Address of the contract that produced the log                |
| newAddress        | VARCHAR   | 0x60853118431dafba53d4d8fcc9bd3d17279b61fe                         |                                                              |

## 76. Table: LendingPoolAddressesProvider\_event\_LendingPoolLiquidationManagerUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-19 15:58:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9312708                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1ff9b3656924727694537fbeda2a16f2f56fae2b78fb6e15673edcf7cfe71870 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 87                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x24a42fd28c976a61df5d00d0599c34c4f90748c8                         | Address of the contract that produced the log                |
| newAddress        | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 77. Table: LendingPoolAddressesProvider\_event\_LendingPoolManagerUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-14 12:50:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11451221                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x558fa06a670098a995ad9b8c5496d135a8319b65fd9aad399d87d9f64cc62006 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 81                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x24a42fd28c976a61df5d00d0599c34c4f90748c8                         | Address of the contract that produced the log                |
| newAddress        | VARCHAR   | 0xee56e2b3d491590b5b31738cc34d5232f378a8d5                         |                                                              |

## 78. Table: LendingPoolAddressesProvider\_event\_LendingPoolParametersProviderUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-08 16:16:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9241000                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd21fc8f45cd92a919398c5d973d8d159faebd44cbac5995927b5e536c2fcecc5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 37                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x24a42fd28c976a61df5d00d0599c34c4f90748c8                         | Address of the contract that produced the log                |
| newAddress        | VARCHAR   | 0x6a990206b3aa8743b62a9d24f17db955d81a3389                         |                                                              |

## 79. Table: LendingPoolAddressesProvider\_event\_LendingPoolUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-08 13:13:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12199347                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa1ebbbc6a5698216b4e615b4fd994c7d87cd9d29c621b37ca269fe5d12133846 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 270                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x24a42fd28c976a61df5d00d0599c34c4f90748c8                         | Address of the contract that produced the log                |
| newAddress        | VARCHAR   | 0xdb9217fad3c1463093fc2801dd0a22c930850a61                         |                                                              |

## 80. Table: LendingPoolAddressesProvider\_event\_LendingRateOracleUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-26 09:19:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9746110                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x11544db8a7df463d60a2cee756c17e390deddc53770682af179700f5135dbaa9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 98                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x24a42fd28c976a61df5d00d0599c34c4f90748c8                         | Address of the contract that produced the log                |
| newAddress        | VARCHAR   | 0x4d728a4496e4de35f218d5a214366bde3a62b51c                         |                                                              |

## 81. Table: LendingPoolAddressesProvider\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-08 16:13:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9240988                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9ef1ca9adb8ff7f3ab4fb792223084d3a5fff4e85c25b03fb21138b1264e36c3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x24a42fd28c976a61df5d00d0599c34c4f90748c8                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x2fbb0c60a41cb7ea5323071624dcead3d213d0fa                         |                                                              |

## 82. Table: LendingPoolAddressesProvider\_event\_PriceOracleUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-08 16:31:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9241057                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb71475cae6541c1dcc8063651d49ab431572df4711acf5d237a8d6f629a59688 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 8                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x24a42fd28c976a61df5d00d0599c34c4f90748c8                         | Address of the contract that produced the log                |
| newAddress        | VARCHAR   | 0x76b47460d7f7c5222cfb6b6a75615ab10895dde4                         |                                                              |

## 83. Table: LendingPoolAddressesProvider\_event\_ProxyCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-08 16:19:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9241011                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9b56eaed8e864f970f7c4bf308af9d5cd93061fa8053604f71be3df7c01b6890 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 9                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x24a42fd28c976a61df5d00d0599c34c4f90748c8                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 0x4c454e44494e475f504f4f4c5f434f4e464947555241544f5200000000000000 |                                                              |
| newAddress        | VARCHAR   | 0x4965f6fa20fe9728decf5165016fc338a5a85abf                         |                                                              |

## 84. Table: LendingPoolAddressesProvider\_event\_TokenDistributorUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-07 16:23:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14921832                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfea6e5fffac696bab8656cdde40dfa11a97d9eaf84e3e8adf95c18e6845c9a8d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 68                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x24a42fd28c976a61df5d00d0599c34c4f90748c8                         | Address of the contract that produced the log                |
| newAddress        | VARCHAR   | 0x464c71f6c2f760dda6093dcb91c24c39e5d6e18c                         |                                                              |

## 85. Table: LendingPoolAddressesProvider\_v2\_event\_AddressSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-02 16:34:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11374220                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7b14840220f9dc3ac473bbf893227f047963755de409ea195cf246a928b8fd52 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 188                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb53c1a33016b2dc2ff3653530bff1848a515c8c5                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 0x0100000000000000000000000000000000000000000000000000000000000000 |                                                              |
| newAddress        | VARCHAR   | 0x057835ad21a177dbdd3090bb1cae03eacf78fc6d                         |                                                              |
| hasProxy          | VARCHAR   | false                                                              |                                                              |

## 86. Table: LendingPoolAddressesProvider\_v2\_event\_ConfigurationAdminUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-01 14:19:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11367172                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc3542c2aa01f5cb1399f9cd395e5701abaa11f5f408dc2b3489ec755b95ae990 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 347                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb53c1a33016b2dc2ff3653530bff1848a515c8c5                         | Address of the contract that produced the log                |
| newAddress        | VARCHAR   | 0xbb94a575935772d7d8ba78cd33caa64d4fb61d6b                         |                                                              |

## 87. Table: LendingPoolAddressesProvider\_v2\_event\_EmergencyAdminUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-30 21:24:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11362569                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9b777345023273e2e08b549c2c8847ea56a4b01ffb553c2d8267cc4b0aab1555 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb53c1a33016b2dc2ff3653530bff1848a515c8c5                         | Address of the contract that produced the log                |
| newAddress        | VARCHAR   | 0xbd723fc4f1d737dcfc48a07fe7336766d34cad5f                         |                                                              |

## 88. Table: LendingPoolAddressesProvider\_v2\_event\_LendingPoolCollateralManagerUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-30 22:23:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11362832                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x615f8a35b7f00b1a86aab5afaed7c752425616b07cda8d1b2b1a2c16d4089a86 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 22                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb53c1a33016b2dc2ff3653530bff1848a515c8c5                         | Address of the contract that produced the log                |
| newAddress        | VARCHAR   | 0xbd4765210d4167ce2a5b87280d9e8ee316d5ec7c                         |                                                              |

## 89. Table: LendingPoolAddressesProvider\_v2\_event\_LendingPoolConfiguratorUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-30 21:26:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11362582                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x04d82219cf3dbfbcde1379421eb23ae324e66357b796d7e9455d3bd992154c08 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 32                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb53c1a33016b2dc2ff3653530bff1848a515c8c5                         | Address of the contract that produced the log                |
| newAddress        | VARCHAR   | 0x3a95ee42f080ff7289c8b4a14eb483a8644d7521                         |                                                              |

## 90. Table: LendingPoolAddressesProvider\_v2\_event\_LendingPoolUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-30 21:25:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11362579                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7d77cc7523a491fa670bfefa0a386ab036b6511d6d9fa6c2cf5c07b349dc9d3a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb53c1a33016b2dc2ff3653530bff1848a515c8c5                         | Address of the contract that produced the log                |
| newAddress        | VARCHAR   | 0x987115c38fd9fd2aa2c6f1718451d167c13a3186                         |                                                              |

## 91. Table: LendingPoolAddressesProvider\_v2\_event\_LendingRateOracleUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-30 21:28:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11362587                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xec969b10f7cac8db0f599bf7f0a723183a0011e4d46d09bcc0f5cec9e31f64fa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb53c1a33016b2dc2ff3653530bff1848a515c8c5                         | Address of the contract that produced the log                |
| newAddress        | VARCHAR   | 0x8a32f49ffba88aba6eff96f45d8bd1d4b3f35c7d                         |                                                              |

## 92. Table: LendingPoolAddressesProvider\_v2\_event\_MarketIdSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-30 21:22:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11362562                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x26f55c918b013a572fdc3174566cec22923183180775bfc3ef6b46e470bec093 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 53                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb53c1a33016b2dc2ff3653530bff1848a515c8c5                         | Address of the contract that produced the log                |
| newMarketId       | VARCHAR   | Aave genesis market                                                |                                                              |

## 93. Table: LendingPoolAddressesProvider\_v2\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-30 21:22:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11362562                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x26f55c918b013a572fdc3174566cec22923183180775bfc3ef6b46e470bec093 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 52                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb53c1a33016b2dc2ff3653530bff1848a515c8c5                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0xbd723fc4f1d737dcfc48a07fe7336766d34cad5f                         |                                                              |

## 94. Table: LendingPoolAddressesProvider\_v2\_event\_PriceOracleUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-30 21:28:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11362586                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0a7c6af603fca21ee5ea9d422f0934a5cd741abc349705f9468074ecb21def7a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb53c1a33016b2dc2ff3653530bff1848a515c8c5                         | Address of the contract that produced the log                |
| newAddress        | VARCHAR   | 0xa50ba011c48153de246e5192c8f9258a2ba79ca9                         |                                                              |

## 95. Table: LendingPoolAddressesProvider\_v2\_event\_ProxyCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-30 21:26:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11362582                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x04d82219cf3dbfbcde1379421eb23ae324e66357b796d7e9455d3bd992154c08 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 31                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb53c1a33016b2dc2ff3653530bff1848a515c8c5                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 0x4c454e44494e475f504f4f4c5f434f4e464947555241544f5200000000000000 |                                                              |
| newAddress        | VARCHAR   | 0x311bb771e4f8952e6da169b425e7e92d6ac45756                         |                                                              |

## 96. Table: LendingPoolCollateralManager\_v2\_event\_LiquidationCall\_history

| Column                     | Type      | Example                                                      | Description |
| -------------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp           | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number              | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash          | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index                 | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address          | VARCHAR   | Address of the contract that produced the log                |             |
| collateral                 | VARCHAR   |                                                              |             |
| principal                  | VARCHAR   |                                                              |             |
| user                       | VARCHAR   |                                                              |             |
| debtToCover                | VARCHAR   |                                                              |             |
| liquidatedCollateralAmount | VARCHAR   |                                                              |             |
| liquidator                 | VARCHAR   |                                                              |             |
| receiveAToken              | VARCHAR   |                                                              |             |

## 97. Table: LendingPoolCollateralManager\_v2\_event\_ReserveUsedAsCollateralDisabled\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| reserve           | VARCHAR   |                                                              |             |
| user              | VARCHAR   |                                                              |             |

## 98. Table: LendingPoolCollateralManager\_v2\_event\_ReserveUsedAsCollateralEnabled\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| reserve           | VARCHAR   |                                                              |             |
| user              | VARCHAR   |                                                              |             |

## 99. Table: LendingPoolConfigurator\_v2\_event\_ATokenUpgraded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-22 10:38:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13664001                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0b4c6b1ec434d109609ec3e23931cc7c7f0b9c4df59b22326e39a89fedf7996d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 78                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x311bb771e4f8952e6da169b425e7e92d6ac45756                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xd533a949740bb3306d119cc777fa900ba034cd52                         |                                                              |
| proxy             | VARCHAR   | 0x8dae6cb04688c62d939ed9b68d32bc62e49970b1                         |                                                              |
| implementation    | VARCHAR   | 0xd78037ed778ec3e2fcdb03b622c42d2f1b66d469                         |                                                              |

## 100. Table: LendingPoolConfigurator\_v2\_event\_BorrowingDisabledOnReserve\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-06 05:32:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17853853                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6a7568a25a3313e9ee0da4dacf24dac0db35a82ebc3b25db286ed630e2f6b087 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 145                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x311bb771e4f8952e6da169b425e7e92d6ac45756                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x0000000000085d4780b73119b644ae5ecd22b376                         |                                                              |

## 101. Table: LendingPoolConfigurator\_v2\_event\_BorrowingEnabledOnReserve\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-20 17:59:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13264119                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4aa2ae4446c17fd20935b0ddc419cd2da7ea860be52d8077126eaf542e4fd413 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 416                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x311bb771e4f8952e6da169b425e7e92d6ac45756                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x956f47f50a910163d8bf957cf5846d573e7f87ca                         |                                                              |
| stableRateEnabled | VARCHAR   | false                                                              |                                                              |

## 102. Table: LendingPoolConfigurator\_v2\_event\_CollateralConfigurationChanged\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2021-10-16 01:59:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 13426219                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xc78cedcdc84fc0b9a19e09ab16471cffcc572eb58ee33082a6da1492d128cffc | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 97                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x311bb771e4f8952e6da169b425e7e92d6ac45756                         | Address of the contract that produced the log                |
| asset                | VARCHAR   | 0xc011a73ee8576fb46f5e1c5751ca3b9fe0af2a6f                         |                                                              |
| ltv                  | VARCHAR   | 3000                                                               |                                                              |
| liquidationThreshold | VARCHAR   | 5500                                                               |                                                              |
| liquidationBonus     | VARCHAR   | 10750                                                              |                                                              |

## 103. Table: LendingPoolConfigurator\_v2\_event\_ReserveActivated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |

## 104. Table: LendingPoolConfigurator\_v2\_event\_ReserveDeactivated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |

## 105. Table: LendingPoolConfigurator\_v2\_event\_ReserveDecimalsChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |
| decimals          | VARCHAR   |                                                              |             |

## 106. Table: LendingPoolConfigurator\_v2\_event\_ReserveFactorChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-18 09:20:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17719186                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x31042069895b547a3b9751a867cee06693116271650d928618ead082264f04f4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 12                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x311bb771e4f8952e6da169b425e7e92d6ac45756                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xba100000625a3754423978a60c9317c58a424e3d                         |                                                              |
| factor            | VARCHAR   | 3000                                                               |                                                              |

## 107. Table: LendingPoolConfigurator\_v2\_event\_ReserveFrozen\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-03 18:44:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17615298                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x20c7e346b241a46a71fcbfad996095b133c0dd9bb8f05997563f091f9fe8a944 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 170                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x311bb771e4f8952e6da169b425e7e92d6ac45756                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x0000000000085d4780b73119b644ae5ecd22b376                         |                                                              |

## 108. Table: LendingPoolConfigurator\_v2\_event\_ReserveInitialized\_history

| Column                      | Type      | Example                                                            | Description                                                  |
| --------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp            | TIMESTAMP | 2020-12-27 21:46:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number               | INTEGER   | 11538358                                                           | The block number where this event was emitted                |
| transaction\_hash           | VARCHAR   | 0xfbe4d346e8908e8dbd683628029f1a2032581c8af2e03db8210470cb8a6df3e1 | Hash of the transactions in which this event was emitted     |
| log\_index                  | INTEGER   | 42                                                                 | Integer of the log index position in the block of this event |
| contract\_address           | VARCHAR   | 0x311bb771e4f8952e6da169b425e7e92d6ac45756                         | Address of the contract that produced the log                |
| asset                       | VARCHAR   | 0xd533a949740bb3306d119cc777fa900ba034cd52                         |                                                              |
| aToken                      | VARCHAR   | 0x8dae6cb04688c62d939ed9b68d32bc62e49970b1                         |                                                              |
| stableDebtToken             | VARCHAR   | 0x9288059a74f589c919c7cf1db433251cdfeb874b                         |                                                              |
| variableDebtToken           | VARCHAR   | 0x00ad8ebf64f141f1c81e9f8f792d3d1631c6c684                         |                                                              |
| interestRateStrategyAddress | VARCHAR   | 0xe3a3de71b827cb73663a24cdb6243ba7f986cc3b                         |                                                              |

## 109. Table: LendingPoolConfigurator\_v2\_event\_ReserveInterestRateStrategyChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-02 13:37:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17827655                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x965f9031fca1b9848d6bb5949a37c45ee7b2a0ae30b05e704b3dabe8036357c9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 147                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x311bb771e4f8952e6da169b425e7e92d6ac45756                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x956f47f50a910163d8bf957cf5846d573e7f87ca                         |                                                              |
| strategy          | VARCHAR   | 0x795dc59ea6472dfa4298a454c6e8dcb005643a13                         |                                                              |

## 110. Table: LendingPoolConfigurator\_v2\_event\_ReserveUnfrozen\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-30 19:32:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16084912                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf8d79abd287d40e0c486cee1fc3085fce143ffe5f6aaffa28aea76c8373eba71 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 287                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x311bb771e4f8952e6da169b425e7e92d6ac45756                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x57ab1ec28d129707052df4df418d58a2d46d5f51                         |                                                              |

## 111. Table: LendingPoolConfigurator\_v2\_event\_StableDebtTokenUpgraded\_history

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

## 112. Table: LendingPoolConfigurator\_v2\_event\_StableRateDisabledOnReserve\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-06 05:32:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17853853                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6a7568a25a3313e9ee0da4dacf24dac0db35a82ebc3b25db286ed630e2f6b087 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 146                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x311bb771e4f8952e6da169b425e7e92d6ac45756                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x0000000000085d4780b73119b644ae5ecd22b376                         |                                                              |

## 113. Table: LendingPoolConfigurator\_v2\_event\_StableRateEnabledOnReserve\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-03 13:24:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11379872                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x86e15dc4593494f381c16e949cd22d5216cf449f17beb4f81e0e77c633d2c5b3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 210                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x311bb771e4f8952e6da169b425e7e92d6ac45756                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         |                                                              |

## 114. Table: LendingPoolConfigurator\_v2\_event\_VariableDebtTokenUpgraded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-15 15:05:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13231003                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x742e32cd4f97161ea3d5928e71367bd09c859964998f8600a125e4e0a3baa408 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 81                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x311bb771e4f8952e6da169b425e7e92d6ac45756                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xba100000625a3754423978a60c9317c58a424e3d                         |                                                              |
| proxy             | VARCHAR   | 0x13210d4fe0d5402bd7ecbc4b5bc5cfca3b71adb0                         |                                                              |
| implementation    | VARCHAR   | 0x6c179cc11aee78e87c63d1c61b8602fad6a1655d                         |                                                              |

## 115. Table: LendingPoolCore\_event\_ReserveUpdated\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2023-04-28 10:15:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 17143966                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x5e543cbe0d714c1a7fe5cb935a8bcea69ba59a48eadee99466ac346f84b4bad2 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 100                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x3dfd23a6c5e8bbcfc9581d2e864a68feb6a076d3                         | Address of the contract that produced the log                |
| reserve             | VARCHAR   | 0x9f8f72aa9304c8b593d555f12ef6589cc3a579a2                         |                                                              |
| liquidityRate       | VARCHAR   | 42653781951803748299213                                            |                                                              |
| stableBorrowRate    | VARCHAR   | 33184189023524512727338940                                         |                                                              |
| variableBorrowRate  | VARCHAR   | 2228932316467158909137258                                          |                                                              |
| liquidityIndex      | VARCHAR   | 1011162358159500364567937547                                       |                                                              |
| variableBorrowIndex | VARCHAR   | 1037330433823942811420940807                                       |                                                              |

## 116. Table: LendingPool\_event\_Borrow\_history

| Column                  | Type      | Example                                                            | Description                                                  |
| ----------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp        | TIMESTAMP | 2020-04-01 01:33:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number           | INTEGER   | 9783044                                                            | The block number where this event was emitted                |
| transaction\_hash       | VARCHAR   | 0x7c86bab1b1c313aab40231bb2dc8203b8631170a8bf26e7beb5415caf1912e9a | Hash of the transactions in which this event was emitted     |
| log\_index              | INTEGER   | 51                                                                 | Integer of the log index position in the block of this event |
| contract\_address       | VARCHAR   | 0x398ec7346dcd622edc5ae82352f02be94c62d119                         | Address of the contract that produced the log                |
| \_reserve               | VARCHAR   | 0x514910771af9ca656af840dff83e8264ecf986ca                         |                                                              |
| \_user                  | VARCHAR   | 0x6c083eb040f0514885baac82e28ff912d7875f53                         |                                                              |
| \_amount                | VARCHAR   | 45444123692637144246                                               |                                                              |
| \_borrowRateMode        | VARCHAR   | 1                                                                  |                                                              |
| \_borrowRate            | VARCHAR   | 30857010408193227973102749                                         |                                                              |
| \_originationFee        | VARCHAR   | 113610309231592861                                                 |                                                              |
| \_borrowBalanceIncrease | VARCHAR   | 0                                                                  |                                                              |
| \_referral              | VARCHAR   | 0                                                                  |                                                              |
| \_timestamp             | VARCHAR   | 1585704806                                                         |                                                              |

## 117. Table: LendingPool\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-30 01:01:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12732305                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x888ecf5a106fe6de630d8f18b8a2f9be80ae77415f32c19138a237a7e8a25b4c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 130                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x398ec7346dcd622edc5ae82352f02be94c62d119                         | Address of the contract that produced the log                |
| \_reserve         | VARCHAR   | 0xf629cbd94d3791c9250152bd8dfbdf380e2a3b9c                         |                                                              |
| \_user            | VARCHAR   | 0x7e7373b7ad044c03cb002277697771eab8dc5b6c                         |                                                              |
| \_amount          | VARCHAR   | 2467280000000000000000                                             |                                                              |
| \_referral        | VARCHAR   | 0                                                                  |                                                              |
| \_timestamp       | VARCHAR   | 1625014912                                                         |                                                              |

## 118. Table: LendingPool\_event\_FlashLoan\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-10 12:04:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13777297                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfdce86fe40c783c09d03857dfcc9d2a5b023648034d0f6919648504378a88968 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 492                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x398ec7346dcd622edc5ae82352f02be94c62d119                         | Address of the contract that produced the log                |
| \_target          | VARCHAR   | 0x409f216aa8034a12135ab6b74bf6444335004bbd                         |                                                              |
| \_reserve         | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         |                                                              |
| \_amount          | VARCHAR   | 130000000000000000000000                                           |                                                              |
| \_totalFee        | VARCHAR   | 117000000000000000000                                              |                                                              |
| \_protocolFee     | VARCHAR   | 35100000000000000000                                               |                                                              |
| \_timestamp       | VARCHAR   | 1639137897                                                         |                                                              |

## 119. Table: LendingPool\_event\_LiquidationCall\_history

| Column                       | Type      | Example                                                            | Description                                                  |
| ---------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp             | TIMESTAMP | 2021-01-07 07:52:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number                | INTEGER   | 11606312                                                           | The block number where this event was emitted                |
| transaction\_hash            | VARCHAR   | 0xe0f9527345bf02dd4ac31200284372c069d571094c7b43b5a35d9024171adc5b | Hash of the transactions in which this event was emitted     |
| log\_index                   | INTEGER   | 19                                                                 | Integer of the log index position in the block of this event |
| contract\_address            | VARCHAR   | 0x398ec7346dcd622edc5ae82352f02be94c62d119                         | Address of the contract that produced the log                |
| \_collateral                 | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| \_reserve                    | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         |                                                              |
| \_user                       | VARCHAR   | 0xdfec9c70c3c35d55845e14bb356c3466da744efc                         |                                                              |
| \_purchaseAmount             | VARCHAR   | 11233398900086409216                                               |                                                              |
| \_liquidatedCollateralAmount | VARCHAR   | 9894926203218098                                                   |                                                              |
| \_accruedBorrowInterest      | VARCHAR   | 629012745510274868                                                 |                                                              |
| \_liquidator                 | VARCHAR   | 0x8ee5a15c20ed56d362254da5f2d63ff69dde45ff                         |                                                              |
| \_receiveAToken              | VARCHAR   | false                                                              |                                                              |
| \_timestamp                  | VARCHAR   | 1610005926                                                         |                                                              |

## 120. Table: LendingPool\_event\_OriginationFeeLiquidated\_history

| Column                       | Type      | Example                                                            | Description                                                  |
| ---------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp             | TIMESTAMP | 2020-02-09 04:27:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number                | INTEGER   | 9446425                                                            | The block number where this event was emitted                |
| transaction\_hash            | VARCHAR   | 0xb3d3fe3c48f2f62e5dc4ec01457b8f5c240f4f849ded60de26d17300566e2ef3 | Hash of the transactions in which this event was emitted     |
| log\_index                   | INTEGER   | 38                                                                 | Integer of the log index position in the block of this event |
| contract\_address            | VARCHAR   | 0x398ec7346dcd622edc5ae82352f02be94c62d119                         | Address of the contract that produced the log                |
| \_collateral                 | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| \_reserve                    | VARCHAR   | 0x0f5d2fb29fb7d3cfee444a200298f468908cc942                         |                                                              |
| \_user                       | VARCHAR   | 0x8ae928cb080aa43a50393cd08de208ef2b1bb86a                         |                                                              |
| \_feeLiquidated              | VARCHAR   | 147057600564205337862                                              |                                                              |
| \_liquidatedCollateralForFee | VARCHAR   | 9483463                                                            |                                                              |
| \_timestamp                  | VARCHAR   | 1581222465                                                         |                                                              |

## 121. Table: LendingPool\_event\_RebalanceStableBorrowRate\_history

| Column                  | Type      | Example                                                            | Description                                                  |
| ----------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp        | TIMESTAMP | 2021-04-03 00:17:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number           | INTEGER   | 12163296                                                           | The block number where this event was emitted                |
| transaction\_hash       | VARCHAR   | 0xbe98cec1d0c4964d84feec944676e0979472e27c78af63abd2ff364556f8591c | Hash of the transactions in which this event was emitted     |
| log\_index              | INTEGER   | 49                                                                 | Integer of the log index position in the block of this event |
| contract\_address       | VARCHAR   | 0x398ec7346dcd622edc5ae82352f02be94c62d119                         | Address of the contract that produced the log                |
| \_reserve               | VARCHAR   | 0xdac17f958d2ee523a2206206994597c13d831ec7                         |                                                              |
| \_user                  | VARCHAR   | 0x4deb3edd991cfd2fcdaa6dcfe5f1743f6e7d16a6                         |                                                              |
| \_newStableRate         | VARCHAR   | 139030293863492036871642314                                        |                                                              |
| \_borrowBalanceIncrease | VARCHAR   | 95120304723                                                        |                                                              |
| \_timestamp             | VARCHAR   | 1617409072                                                         |                                                              |

## 122. Table: LendingPool\_event\_RedeemUnderlying\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-04 02:05:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16108351                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3f39608202856c5305006764b55f16a51f01c5a0f00da39b635391ff916deafa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 80                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x398ec7346dcd622edc5ae82352f02be94c62d119                         | Address of the contract that produced the log                |
| \_reserve         | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         |                                                              |
| \_user            | VARCHAR   | 0xbcc4371cc40592794bf5b727c17cf7de37ac180a                         |                                                              |
| \_amount          | VARCHAR   | 3165434063703386102739                                             |                                                              |
| \_timestamp       | VARCHAR   | 1670119535                                                         |                                                              |

## 123. Table: LendingPool\_event\_Repay\_history

| Column                  | Type      | Example                                                            | Description                                                  |
| ----------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp        | TIMESTAMP | 2020-12-25 18:37:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number           | INTEGER   | 11524457                                                           | The block number where this event was emitted                |
| transaction\_hash       | VARCHAR   | 0xaab265006979cf97d54f7272b98a27d8fe9942a070c5aa876d5058d3aef59a86 | Hash of the transactions in which this event was emitted     |
| log\_index              | INTEGER   | 124                                                                | Integer of the log index position in the block of this event |
| contract\_address       | VARCHAR   | 0x398ec7346dcd622edc5ae82352f02be94c62d119                         | Address of the contract that produced the log                |
| \_reserve               | VARCHAR   | 0x0000000000085d4780b73119b644ae5ecd22b376                         |                                                              |
| \_user                  | VARCHAR   | 0x3cda30bd84db976bfabb64b622d74d38e78edfd3                         |                                                              |
| \_repayer               | VARCHAR   | 0x3cda30bd84db976bfabb64b622d74d38e78edfd3                         |                                                              |
| \_amountMinusFees       | VARCHAR   | 4589030007587576466758                                             |                                                              |
| \_fees                  | VARCHAR   | 4000000000000000                                                   |                                                              |
| \_borrowBalanceIncrease | VARCHAR   | 139099013195587543003                                              |                                                              |
| \_timestamp             | VARCHAR   | 1608921479                                                         |                                                              |

## 124. Table: LendingPool\_event\_ReserveUsedAsCollateralDisabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-14 19:17:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11856661                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe901d9fda3fb20da48e4b71bb67519ddcf92f1d12083c78da12c8e6e9ee3b567 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x398ec7346dcd622edc5ae82352f02be94c62d119                         | Address of the contract that produced the log                |
| \_reserve         | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| \_user            | VARCHAR   | 0x0c2ce00e722bd42048c429842f9e1aaf42590140                         |                                                              |

## 125. Table: LendingPool\_event\_ReserveUsedAsCollateralEnabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-12 02:03:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9854628                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe61f32c8fcbae6bd89536ec92742883d96875b909a4eb5e9d5d5f1b1f87de305 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 15                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x398ec7346dcd622edc5ae82352f02be94c62d119                         | Address of the contract that produced the log                |
| \_reserve         | VARCHAR   | 0xc011a73ee8576fb46f5e1c5751ca3b9fe0af2a6f                         |                                                              |
| \_user            | VARCHAR   | 0xd8408a97401ec903dc9955372fd0fb790cfdcea6                         |                                                              |

## 126. Table: LendingPool\_event\_Swap\_history

| Column                  | Type      | Example                                                            | Description                                                  |
| ----------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp        | TIMESTAMP | 2020-07-19 08:42:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number           | INTEGER   | 10488926                                                           | The block number where this event was emitted                |
| transaction\_hash       | VARCHAR   | 0xae436ba96500e50617cd9f3122415a337e8915e5017b67ce0b5047fa79e3a7ea | Hash of the transactions in which this event was emitted     |
| log\_index              | INTEGER   | 201                                                                | Integer of the log index position in the block of this event |
| contract\_address       | VARCHAR   | 0x398ec7346dcd622edc5ae82352f02be94c62d119                         | Address of the contract that produced the log                |
| \_reserve               | VARCHAR   | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599                         |                                                              |
| \_user                  | VARCHAR   | 0xd3d0e837f1aff3833bb3a0ad2ae58858b7ad8ebd                         |                                                              |
| \_newRateMode           | VARCHAR   | 1                                                                  |                                                              |
| \_newRate               | VARCHAR   | 32381096538279716491723407                                         |                                                              |
| \_borrowBalanceIncrease | VARCHAR   | 7                                                                  |                                                              |
| \_timestamp             | VARCHAR   | 1595148161                                                         |                                                              |

## 127. Table: LendingPool\_v2\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-14 17:10:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11856081                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x274586dd76276e0b8b5c9f8964284c7d034a0e627504fc1be91d8cc11dfd43e2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 175                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7d2768de32b0b80b7a3454c06bdac94a69ddc7a9                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x0000000000085d4780b73119b644ae5ecd22b376                         |                                                              |
| user              | VARCHAR   | 0x88fb646c1eea8abbbfb9a8bacfb28a952b376998                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x88fb646c1eea8abbbfb9a8bacfb28a952b376998                         |                                                              |
| amount            | VARCHAR   | 1000000000000000000000                                             |                                                              |
| borrowRateMode    | VARCHAR   | 2                                                                  |                                                              |
| borrowRate        | VARCHAR   | 275233340658445572986683285                                        |                                                              |
| referral          | VARCHAR   | 0                                                                  |                                                              |

## 128. Table: LendingPool\_v2\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-25 17:34:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17771631                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x97b4f3a14d3a219406e734332e9b7ca45d85c4e89a495f096fb3e0b28675184e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 246                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7d2768de32b0b80b7a3454c06bdac94a69ddc7a9                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599                         |                                                              |
| user              | VARCHAR   | 0x135896de8421be2ec868e0b811006171d9df802a                         |                                                              |
| onBehalfOf        | VARCHAR   | 0xbf2be2410a02eaacb81d979c48c4200434e015bd                         |                                                              |
| amount            | VARCHAR   | 136623883                                                          |                                                              |
| referral          | VARCHAR   | 0                                                                  |                                                              |

## 129. Table: LendingPool\_v2\_event\_FlashLoan\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-06 13:11:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17856134                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x109ff9fe9391a6a6ead240c2068f6d5b7d09147f2b11548539de3f4875eb40ae | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 721                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7d2768de32b0b80b7a3454c06bdac94a69ddc7a9                         | Address of the contract that produced the log                |
| target            | VARCHAR   | 0x135896de8421be2ec868e0b811006171d9df802a                         |                                                              |
| initiator         | VARCHAR   | 0x87c0700498758a6b884dd5f270b2116195339532                         |                                                              |
| asset             | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| amount            | VARCHAR   | 1352185937                                                         |                                                              |
| premium           | VARCHAR   | 1216967                                                            |                                                              |
| referralCode      | VARCHAR   | 0                                                                  |                                                              |

## 130. Table: LendingPool\_v2\_event\_LiquidationCall\_history

| Column                     | Type      | Example                                                            | Description                                                  |
| -------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp           | TIMESTAMP | 2023-03-09 20:44:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number              | INTEGER   | 16793098                                                           | The block number where this event was emitted                |
| transaction\_hash          | VARCHAR   | 0xabc80584f3eb0a83aef2c8e763db5ea2ad3ec525100076817539ac2fa9de6b10 | Hash of the transactions in which this event was emitted     |
| log\_index                 | INTEGER   | 68                                                                 | Integer of the log index position in the block of this event |
| contract\_address          | VARCHAR   | 0x7d2768de32b0b80b7a3454c06bdac94a69ddc7a9                         | Address of the contract that produced the log                |
| collateralAsset            | VARCHAR   | 0x514910771af9ca656af840dff83e8264ecf986ca                         |                                                              |
| debtAsset                  | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| user                       | VARCHAR   | 0x21cfe08c7ddb08a8e5fa04baac8b2a1457696731                         |                                                              |
| debtToCover                | VARCHAR   | 2082812735                                                         |                                                              |
| liquidatedCollateralAmount | VARCHAR   | 362377250212217844725                                              |                                                              |
| liquidator                 | VARCHAR   | 0x78bde1fe54d93d6bc483e160205f4b7e1c7ca5fb                         |                                                              |
| receiveAToken              | VARCHAR   | true                                                               |                                                              |

## 131. Table: LendingPool\_v2\_event\_Paused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 132. Table: LendingPool\_v2\_event\_RebalanceStableBorrowRate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-04 20:57:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11590309                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x01623d19012747c819a686aae5efbefdab3592a13162dbebf6425c2e074aa9bc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 118                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7d2768de32b0b80b7a3454c06bdac94a69ddc7a9                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x0000000000085d4780b73119b644ae5ecd22b376                         |                                                              |
| user              | VARCHAR   | 0x39ed3bf3e177fe08c5de25dbb4fd972e8b3c6c46                         |                                                              |

## 133. Table: LendingPool\_v2\_event\_Repay\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-27 15:10:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13500117                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x84662f17e2f66c95396508a5b09aadf87d97d1fa2dfd253705bf9d31d8170a34 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 659                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7d2768de32b0b80b7a3454c06bdac94a69ddc7a9                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x0f5d2fb29fb7d3cfee444a200298f468908cc942                         |                                                              |
| user              | VARCHAR   | 0x3af015f6e3ac79d217198f00ef36af099d223e29                         |                                                              |
| repayer           | VARCHAR   | 0x3af015f6e3ac79d217198f00ef36af099d223e29                         |                                                              |
| amount            | VARCHAR   | 2870446997202208772011889                                          |                                                              |

## 134. Table: LendingPool\_v2\_event\_ReserveDataUpdated\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2021-12-29 11:03:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 13899838                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xb8c7fe5db0d813f28aefc7d4dfce8ffbf95e6afd1ee49e16c039e52a99cd3586 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 54                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x7d2768de32b0b80b7a3454c06bdac94a69ddc7a9                         | Address of the contract that produced the log                |
| reserve             | VARCHAR   | 0x7fc66500c84a76ad7e9c93437bfc5ac33e2ddae9                         |                                                              |
| liquidityRate       | VARCHAR   | 0                                                                  |                                                              |
| stableBorrowRate    | VARCHAR   | 0                                                                  |                                                              |
| variableBorrowRate  | VARCHAR   | 0                                                                  |                                                              |
| liquidityIndex      | VARCHAR   | 1000089631447215908098079387                                       |                                                              |
| variableBorrowIndex | VARCHAR   | 1000000000000000000000000000                                       |                                                              |

## 135. Table: LendingPool\_v2\_event\_ReserveUsedAsCollateralDisabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-11 12:34:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17670403                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x94d9e3c6ede43b09a01822e5d07e33518549da8d2a4d9d91ed74aa01bac45b31 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 69                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7d2768de32b0b80b7a3454c06bdac94a69ddc7a9                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| user              | VARCHAR   | 0x135896de8421be2ec868e0b811006171d9df802a                         |                                                              |

## 136. Table: LendingPool\_v2\_event\_ReserveUsedAsCollateralEnabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-10 08:54:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17662209                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x88870630b2e3271aeab87d85c57ab4cd1fed6f3b363717f1d4e0b6141a404287 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 479                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7d2768de32b0b80b7a3454c06bdac94a69ddc7a9                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x056fd409e1d7a124bd7017459dfea2f387b6d5cd                         |                                                              |
| user              | VARCHAR   | 0x1821ddc499b7866368ad4be36975df3248e08ef8                         |                                                              |

## 137. Table: LendingPool\_v2\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-03 17:51:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17836072                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa63f18988d3d66528cadb8b016b3d5551fda4bcb0755dbbbae80f9f5ec3b3883 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 16                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7d2768de32b0b80b7a3454c06bdac94a69ddc7a9                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| user              | VARCHAR   | 0xe607320c91ee5c964c7d44209fb8500d60145371                         |                                                              |
| rateMode          | VARCHAR   | 2                                                                  |                                                              |

## 138. Table: LendingPool\_v2\_event\_Unpaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 139. Table: LendingPool\_v2\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-04 05:40:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13738075                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x55f2046b03bd29e84dce6696c8631325a1d6cd7ac76bde33c612ed1b056c328e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 206                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7d2768de32b0b80b7a3454c06bdac94a69ddc7a9                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x0000000000085d4780b73119b644ae5ecd22b376                         |                                                              |
| user              | VARCHAR   | 0x3ddfa8ec3052539b6c9549f12cea2c295cff5296                         |                                                              |
| to                | VARCHAR   | 0x3ddfa8ec3052539b6c9549f12cea2c295cff5296                         |                                                              |
| amount            | VARCHAR   | 25000000000000000000000000                                         |                                                              |

## 140. Table: LendingRateOracle\_v2\_event\_MarketBorrowRateSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-18 17:30:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12064021                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6be7cfca5c2e6a08f64d1cfffc8528b6d0fbb49c38036cdcfc25f58710dc9f4d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 109                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8a32f49ffba88aba6eff96f45d8bd1d4b3f35c7d                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| rate              | VARCHAR   | 90000000000000000000000000                                         |                                                              |

## 141. Table: LendingRateOracle\_v2\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-21 12:56:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16677016                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe3554d7ad1bcc52f8a9c627ce9fc39fa2ffefde9f599fcf5ba93fb4103dcb03b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 92                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8a32f49ffba88aba6eff96f45d8bd1d4b3f35c7d                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0xb9062896ec3a615a4e4444df183f0531a77218ae                         |                                                              |
| newOwner          | VARCHAR   | 0xee56e2b3d491590b5b31738cc34d5232f378a8d5                         |                                                              |

## 142. Table: PermissionManager\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-18 16:03:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13640275                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa784cb66eafd768a11b386a9368d89eee7e1b32504d1d25363da6dfbbf7fb014 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 203                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf4a1f5fea79c3609514a417425971fadc10ecfbe                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x438c763b3441215fcd6b7f75434901b74ded4f53                         | Transfer of role ownership                                   |
| newOwner          | VARCHAR   | 0xace1d11d836cb3f51ef658fd4d353ffb3c301218                         |                                                              |

## 143. Table: PermissionManager\_event\_PermissionsAdminSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-04 10:26:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13549667                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x74ca7a7d9f1ce6e19643a9f98c556b11f5f4fd2783fa83538a7d8c5198779d61 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 313                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf4a1f5fea79c3609514a417425971fadc10ecfbe                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x438c763b3441215fcd6b7f75434901b74ded4f53                         | Permissions of admin set                                     |
| set               | VARCHAR   | false                                                              |                                                              |

## 144. Table: PermissionManager\_event\_RoleSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-04 10:19:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13549633                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf751136525013c9951d40bfadda91f3dc9dcea647a6fa154cf390efca8478a91 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 95                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf4a1f5fea79c3609514a417425971fadc10ecfbe                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xd51e46b02ecb71357cbdf661e2789ec787d94af9                         | Setting the role of a particular address                     |
| role              | VARCHAR   | 1                                                                  |                                                              |
| whiteLister       | VARCHAR   | 0x438c763b3441215fcd6b7f75434901b74ded4f53                         |                                                              |
| set               | VARCHAR   | true                                                               |                                                              |

## 145. Table: PoolConfigurator\_event\_ATokenUpgraded\_history

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

## 146. Table: PoolConfigurator\_event\_BorrowCapChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-18 18:38:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17075380                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5ac529887a71e69b6ea1e3713cda4dcd4017dcb5925ceafca5ba6dde0d4e339c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 138                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x64b761d848206f447fe2dd461b0c635ec39ebb27                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x5a98fcbea516cf06857215779fd812ca3bef1b32                         |                                                              |
| oldBorrowCap      | VARCHAR   | 0                                                                  |                                                              |
| newBorrowCap      | VARCHAR   | 3000000                                                            |                                                              |

## 147. Table: PoolConfigurator\_event\_BorrowableInIsolationChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-23 03:52:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17539726                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1cccbb1b88d9aa969348db2577a53dc1fcc76b42e270784d453005838c5968a0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 89                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x64b761d848206f447fe2dd461b0c635ec39ebb27                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xc18360217d8f7ab5e7c516566761ea12ce7f9d72                         |                                                              |
| borrowable        | VARCHAR   | false                                                              |                                                              |

## 148. Table: PoolConfigurator\_event\_BridgeProtocolFeeUpdated\_history

| Column               | Type      | Example                                                      | Description |
| -------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp     | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number        | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash    | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index           | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address    | VARCHAR   | Address of the contract that produced the log                |             |
| oldBridgeProtocolFee | VARCHAR   |                                                              |             |
| newBridgeProtocolFee | VARCHAR   |                                                              |             |

## 149. Table: PoolConfigurator\_event\_CollateralConfigurationChanged\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2023-06-23 03:52:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 17539726                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x1cccbb1b88d9aa969348db2577a53dc1fcc76b42e270784d453005838c5968a0 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 93                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x64b761d848206f447fe2dd461b0c635ec39ebb27                         | Address of the contract that produced the log                |
| asset                | VARCHAR   | 0xc18360217d8f7ab5e7c516566761ea12ce7f9d72                         |                                                              |
| ltv                  | VARCHAR   | 3900                                                               |                                                              |
| liquidationThreshold | VARCHAR   | 4900                                                               |                                                              |
| liquidationBonus     | VARCHAR   | 10800                                                              |                                                              |

## 150. Table: PoolConfigurator\_event\_DebtCeilingChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-07 10:29:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17641336                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8b5dbaf0f9b9a5b1f297c2b109a806a6cbe42263dda58c82a4bde7b447ac62c5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 122                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x64b761d848206f447fe2dd461b0c635ec39ebb27                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x853d955acef822db058eb8505911ed77f175b99e                         |                                                              |
| oldDebtCeiling    | VARCHAR   | 0                                                                  |                                                              |
| newDebtCeiling    | VARCHAR   | 1000000000                                                         |                                                              |

## 151. Table: PoolConfigurator\_event\_EModeAssetCategoryChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-23 03:52:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17539726                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1cccbb1b88d9aa969348db2577a53dc1fcc76b42e270784d453005838c5968a0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 115                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x64b761d848206f447fe2dd461b0c635ec39ebb27                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x111111111117dc0aa78b770fa6a738034120c302                         |                                                              |
| oldCategoryId     | VARCHAR   | 0                                                                  |                                                              |
| newCategoryId     | VARCHAR   | 0                                                                  |                                                              |

## 152. Table: PoolConfigurator\_event\_EModeCategoryAdded\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2023-01-27 07:53:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 16496783                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x2cfcf7c42c7176833b87f3f321c54355121ad50f7f3e237ba45ffd87ecfd5c14 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 202                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x64b761d848206f447fe2dd461b0c635ec39ebb27                         | Address of the contract that produced the log                |
| categoryId           | VARCHAR   | 1                                                                  |                                                              |
| ltv                  | VARCHAR   | 9000                                                               |                                                              |
| liquidationThreshold | VARCHAR   | 9300                                                               |                                                              |
| liquidationBonus     | VARCHAR   | 10100                                                              |                                                              |
| oracle               | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| label                | VARCHAR   | ETH correlated                                                     |                                                              |

## 153. Table: PoolConfigurator\_event\_FlashloanPremiumToProtocolUpdated\_history

| Column                        | Type      | Example                                                            | Description                                                  |
| ----------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp              | TIMESTAMP | 2022-12-29 14:52:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number                 | INTEGER   | 16291132                                                           | The block number where this event was emitted                |
| transaction\_hash             | VARCHAR   | 0xde9d361e594fbf0e2b16ee6fd89b9b6c0eb185a4abfa7157e9448bf323053309 | Hash of the transactions in which this event was emitted     |
| log\_index                    | INTEGER   | 185                                                                | Integer of the log index position in the block of this event |
| contract\_address             | VARCHAR   | 0x64b761d848206f447fe2dd461b0c635ec39ebb27                         | Address of the contract that produced the log                |
| oldFlashloanPremiumToProtocol | VARCHAR   | 0                                                                  |                                                              |
| newFlashloanPremiumToProtocol | VARCHAR   | 4                                                                  |                                                              |

## 154. Table: PoolConfigurator\_event\_FlashloanPremiumTotalUpdated\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2023-05-08 07:09:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 17214196                                                           | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0x012b6d5e9be9ae815f6d4af51adc11aed782a6979eca66f9afbf4d122245f342 | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 120                                                                | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0x64b761d848206f447fe2dd461b0c635ec39ebb27                         | Address of the contract that produced the log                |
| oldFlashloanPremiumTotal | VARCHAR   | 9                                                                  |                                                              |
| newFlashloanPremiumTotal | VARCHAR   | 5                                                                  |                                                              |

## 155. Table: PoolConfigurator\_event\_LiquidationProtocolFeeChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-18 21:17:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17722731                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x896feeb3cc5aa3d6e082b210f1042f8dc2b7eaab4a8fc74dafcd9277911a4a5d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 279                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x64b761d848206f447fe2dd461b0c635ec39ebb27                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xdac17f958d2ee523a2206206994597c13d831ec7                         |                                                              |
| oldFee            | VARCHAR   | 0                                                                  |                                                              |
| newFee            | VARCHAR   | 1000                                                               |                                                              |

## 156. Table: PoolConfigurator\_event\_ReserveActive\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |
| active            | VARCHAR   |                                                              |             |

## 157. Table: PoolConfigurator\_event\_ReserveBorrowing\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-15 14:02:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17699249                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xae8e542d4fdb5a6a33eeb129bb80f9bf23a1ceb3ef5f6caed1fd634ae3730c0b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 86                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x64b761d848206f447fe2dd461b0c635ec39ebb27                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x40d16fc0246ad3160ccc09b8d0d3a2cd28ae6c2f                         |                                                              |
| enabled           | VARCHAR   | true                                                               |                                                              |

## 158. Table: PoolConfigurator\_event\_ReserveDropped\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |

## 159. Table: PoolConfigurator\_event\_ReserveFactorChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-23 03:52:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17539726                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1cccbb1b88d9aa969348db2577a53dc1fcc76b42e270784d453005838c5968a0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 91                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x64b761d848206f447fe2dd461b0c635ec39ebb27                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xc18360217d8f7ab5e7c516566761ea12ce7f9d72                         |                                                              |
| oldReserveFactor  | VARCHAR   | 0                                                                  |                                                              |
| newReserveFactor  | VARCHAR   | 2000                                                               |                                                              |

## 160. Table: PoolConfigurator\_event\_ReserveFrozen\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |
| frozen            | VARCHAR   |                                                              |             |

## 161. Table: PoolConfigurator\_event\_ReserveInitialized\_history

| Column                      | Type      | Example                                                            | Description                                                  |
| --------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp            | TIMESTAMP | 2023-02-07 08:43:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number               | INTEGER   | 16575788                                                           | The block number where this event was emitted                |
| transaction\_hash           | VARCHAR   | 0x81f7834dd63765db398bb3b1e90fc56fd61c193046b10ce20afb04baa78e8dc7 | Hash of the transactions in which this event was emitted     |
| log\_index                  | INTEGER   | 454                                                                | Integer of the log index position in the block of this event |
| contract\_address           | VARCHAR   | 0x64b761d848206f447fe2dd461b0c635ec39ebb27                         | Address of the contract that produced the log                |
| asset                       | VARCHAR   | 0xbe9895146f7af43049ca1c1ae358b0541ea49704                         |                                                              |
| aToken                      | VARCHAR   | 0x977b6fc5de62598b08c85ac8cf2b745874e8b78c                         |                                                              |
| stableDebtToken             | VARCHAR   | 0x82be6012cea6d147b968ebaea5ceecf6a5b4f493                         |                                                              |
| variableDebtToken           | VARCHAR   | 0x0c91bca95b5fe69164ce583a2ec9429a569798ed                         |                                                              |
| interestRateStrategyAddress | VARCHAR   | 0x24701a6368ff6d2874d6b8cdadd461552b8a5283                         |                                                              |

## 162. Table: PoolConfigurator\_event\_ReserveInterestRateStrategyChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-30 16:39:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17160111                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb7d12de9f5d810d90f64b0fbc94faabee39ecca7161085933f0046d7fb30b234 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 254                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x64b761d848206f447fe2dd461b0c635ec39ebb27                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xba100000625a3754423978a60c9317c58a424e3d                         |                                                              |
| oldStrategy       | VARCHAR   | 0xcbdc7d7984d7ad59434f0b1999d2006898c40f9a                         |                                                              |
| newStrategy       | VARCHAR   | 0xd9d85499449f26d2a2c240defd75314f23920089                         |                                                              |

## 163. Table: PoolConfigurator\_event\_ReservePaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |
| paused            | VARCHAR   |                                                              |             |

## 164. Table: PoolConfigurator\_event\_ReserveStableRateBorrowing\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-23 03:52:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17539726                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1cccbb1b88d9aa969348db2577a53dc1fcc76b42e270784d453005838c5968a0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 88                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x64b761d848206f447fe2dd461b0c635ec39ebb27                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xc18360217d8f7ab5e7c516566761ea12ce7f9d72                         |                                                              |
| enabled           | VARCHAR   | false                                                              |                                                              |

## 165. Table: PoolConfigurator\_event\_SiloedBorrowingChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-23 03:52:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17539726                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1cccbb1b88d9aa969348db2577a53dc1fcc76b42e270784d453005838c5968a0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 90                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x64b761d848206f447fe2dd461b0c635ec39ebb27                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xc18360217d8f7ab5e7c516566761ea12ce7f9d72                         |                                                              |
| oldState          | VARCHAR   | false                                                              |                                                              |
| newState          | VARCHAR   | false                                                              |                                                              |

## 166. Table: PoolConfigurator\_event\_StableDebtTokenUpgraded\_history

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

## 167. Table: PoolConfigurator\_event\_SupplyCapChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-15 17:38:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17700301                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc49f87cb5a8a35201231df04edcea9299c8be4f4546da560e5fd97bb6ed22158 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 69                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x64b761d848206f447fe2dd461b0c635ec39ebb27                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x514910771af9ca656af840dff83e8264ecf986ca                         |                                                              |
| oldSupplyCap      | VARCHAR   | 24000000                                                           |                                                              |
| newSupplyCap      | VARCHAR   | 15000000                                                           |                                                              |

## 168. Table: PoolConfigurator\_event\_UnbackedMintCapChanged\_history

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

## 169. Table: PoolConfigurator\_event\_VariableDebtTokenUpgraded\_history

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

## 170. Table: Pool\_v3\_event\_BackUnbacked\_history

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

## 171. Table: Pool\_v3\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-07 09:14:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16575940                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe2bf606cb4c588581bba8150654aab6df912471302b2b02fe3b5b9ae80d99a20 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 72                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x87870bca3f3fd6335c3f4ce8392d69350b4fa4e2                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599                         |                                                              |
| user              | VARCHAR   | 0x5e828ff60fe3871f9f156ff46eb351ed5a17abb3                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x5e828ff60fe3871f9f156ff46eb351ed5a17abb3                         |                                                              |
| amount            | VARCHAR   | 400000000                                                          |                                                              |
| interestRateMode  | VARCHAR   | 2                                                                  |                                                              |
| borrowRate        | VARCHAR   | 9975471088893460398830918                                          |                                                              |
| referralCode      | VARCHAR   | 0                                                                  |                                                              |

## 172. Table: Pool\_v3\_event\_FlashLoan\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-23 19:47:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17544444                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf26dac857f45da1592a4e5aa8ea62419f3b956588d766354935aeb0eaba8d9a1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 215                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x87870bca3f3fd6335c3f4ce8392d69350b4fa4e2                         | Address of the contract that produced the log                |
| target            | VARCHAR   | 0x1809f186d680f239420b56948c58f8dbbcdf1e18                         |                                                              |
| initiator         | VARCHAR   | 0x7c51967dfc95a847ea79fee64811470ce794fd13                         |                                                              |
| asset             | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| amount            | VARCHAR   | 16226155548979178823                                               |                                                              |
| interestRateMode  | VARCHAR   | 0                                                                  |                                                              |
| premium           | VARCHAR   | 8113077774489589                                                   |                                                              |
| referralCode      | VARCHAR   | 0                                                                  |                                                              |

## 173. Table: Pool\_v3\_event\_IsolationModeTotalDebtUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-01 03:48:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17596643                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbf7baec05075504f23b1c76e6b77491a87447d2daa31ffec8d008c276f7beee5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x87870bca3f3fd6335c3f4ce8392d69350b4fa4e2                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x5a98fcbea516cf06857215779fd812ca3bef1b32                         |                                                              |
| totalDebt         | VARCHAR   | 5899318                                                            |                                                              |

## 174. Table: Pool\_v3\_event\_LiquidationCall\_history

| Column                     | Type      | Example                                                            | Description                                                  |
| -------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp           | TIMESTAMP | 2023-03-25 19:09:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number              | INTEGER   | 16906458                                                           | The block number where this event was emitted                |
| transaction\_hash          | VARCHAR   | 0xe933b1ade18a0376c93c69f4180dfe0ee57f62c6872d9b57799f5e3892029c21 | Hash of the transactions in which this event was emitted     |
| log\_index                 | INTEGER   | 48                                                                 | Integer of the log index position in the block of this event |
| contract\_address          | VARCHAR   | 0x87870bca3f3fd6335c3f4ce8392d69350b4fa4e2                         | Address of the contract that produced the log                |
| collateralAsset            | VARCHAR   | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599                         |                                                              |
| debtAsset                  | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| user                       | VARCHAR   | 0x2db98d6507f14615cd9b9b287d8109328b6dc209                         |                                                              |
| debtToCover                | VARCHAR   | 3001180412                                                         |                                                              |
| liquidatedCollateralAmount | VARCHAR   | 11582707                                                           |                                                              |
| liquidator                 | VARCHAR   | 0x80d4230c0a68fc59cb264329d3a717fcaa472a13                         |                                                              |
| receiveAToken              | VARCHAR   | false                                                              |                                                              |

## 175. Table: Pool\_v3\_event\_MintUnbacked\_history

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

## 176. Table: Pool\_v3\_event\_MintedToTreasury\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-11 23:50:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17240410                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdbdc71ce2fab523c899eb0a7bcfdd84f1202780adc978b8f6379cb6dfdbd3ca1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 425                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x87870bca3f3fd6335c3f4ce8392d69350b4fa4e2                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599                         |                                                              |
| amountMinted      | VARCHAR   | 4019726                                                            |                                                              |

## 177. Table: Pool\_v3\_event\_RebalanceStableBorrowRate\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| reserve           | VARCHAR   |                                                              |             |
| user              | VARCHAR   |                                                              |             |

## 178. Table: Pool\_v3\_event\_Repay\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-23 04:22:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17319544                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x22ec1e9f397a1891df389912fd9f189d98efe75f0aabfd951935b54a7746ff6a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 34                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x87870bca3f3fd6335c3f4ce8392d69350b4fa4e2                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599                         |                                                              |
| user              | VARCHAR   | 0x0000cd00001700b10049dfc947103e00e1c62683                         |                                                              |
| repayer           | VARCHAR   | 0x0000cd00001700b10049dfc947103e00e1c62683                         |                                                              |
| amount            | VARCHAR   | 982304779                                                          |                                                              |
| useATokens        | VARCHAR   | false                                                              |                                                              |

## 179. Table: Pool\_v3\_event\_ReserveDataUpdated\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2023-04-04 04:58:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 16973334                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x1b95798cc6f7738eb83a2ed9b8d9cc09fff042310d684f2f430d0b5cf012d3f8 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 176                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x87870bca3f3fd6335c3f4ce8392d69350b4fa4e2                         | Address of the contract that produced the log                |
| reserve             | VARCHAR   | 0x7fc66500c84a76ad7e9c93437bfc5ac33e2ddae9                         |                                                              |
| liquidityRate       | VARCHAR   | 0                                                                  |                                                              |
| stableBorrowRate    | VARCHAR   | 90000000000000000000000000                                         |                                                              |
| variableBorrowRate  | VARCHAR   | 0                                                                  |                                                              |
| liquidityIndex      | VARCHAR   | 1000000000000000000000000000                                       |                                                              |
| variableBorrowIndex | VARCHAR   | 1000000000000000000000000000                                       |                                                              |

## 180. Table: Pool\_v3\_event\_ReserveUsedAsCollateralDisabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-09 23:50:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17226260                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x89b794682b6b2b77be1ea8f72e0d7691e7241ddf17e76b0173b9d85f44b22287 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 258                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x87870bca3f3fd6335c3f4ce8392d69350b4fa4e2                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599                         |                                                              |
| user              | VARCHAR   | 0x67ec8f6695db86dd0cb1a5649517e072495706c7                         |                                                              |

## 181. Table: Pool\_v3\_event\_ReserveUsedAsCollateralEnabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-11 15:18:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17671215                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x59eaaf35596aabf7949e958b49d0b27051cddc411619dddef26cbd9c5d9f12a1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 68                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x87870bca3f3fd6335c3f4ce8392d69350b4fa4e2                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599                         |                                                              |
| user              | VARCHAR   | 0x6e1924386f8b73d37d8292033da73513e5edf011                         |                                                              |

## 182. Table: Pool\_v3\_event\_Supply\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-20 03:34:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17518264                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xeea8272170b6cf6382bb18106fa52600e4e935f595f8d5538e0448c1aa0b07fd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 169                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x87870bca3f3fd6335c3f4ce8392d69350b4fa4e2                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599                         |                                                              |
| user              | VARCHAR   | 0x117a34b37723506a44e1cc063f9945ea68c92c29                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x117a34b37723506a44e1cc063f9945ea68c92c29                         |                                                              |
| amount            | VARCHAR   | 69936077                                                           |                                                              |
| referralCode      | VARCHAR   | 0                                                                  |                                                              |

## 183. Table: Pool\_v3\_event\_SwapBorrowRateMode\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| reserve           | VARCHAR   |                                                              |             |
| user              | VARCHAR   |                                                              |             |
| interestRateMode  | VARCHAR   |                                                              |             |

## 184. Table: Pool\_v3\_event\_UserEModeSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-10 04:59:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17661046                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcb2f767f835740f99284533b48238f272a0e3dac2b099c5d3930d4509f2e7596 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 102                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x87870bca3f3fd6335c3f4ce8392d69350b4fa4e2                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xd814e1b7cc203ff6ca4358bf4aa3ce9771fedc68                         |                                                              |
| categoryId        | VARCHAR   | 0                                                                  |                                                              |

## 185. Table: Pool\_v3\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-09 18:48:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17444544                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdb9e2150481a3f1021672da75f392102ce9146f371e249cbe359f9fc740e84c1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 203                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x87870bca3f3fd6335c3f4ce8392d69350b4fa4e2                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599                         |                                                              |
| user              | VARCHAR   | 0x1809f186d680f239420b56948c58f8dbbcdf1e18                         |                                                              |
| to                | VARCHAR   | 0x1809f186d680f239420b56948c58f8dbbcdf1e18                         |                                                              |
| amount            | VARCHAR   | 83207824                                                           |                                                              |

## 186. Table: Proxy\_event\_ReserveInitialized\_history

| Column                        | Type      | Example                                                      | Description |
| ----------------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp              | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number                 | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash             | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index                    | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address             | VARCHAR   | Address of the contract that produced the log                |             |
| \_reserve                     | VARCHAR   |                                                              |             |
| \_wToken                      | VARCHAR   |                                                              |             |
| \_interestRateStrategyAddress | VARCHAR   |                                                              |             |

## 187. Table: StableDebtToken\_v2\_event\_Approval\_history

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

## 188. Table: StableDebtToken\_v2\_event\_BorrowAllowanceDelegated\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-09 20:06:02+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14934452                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf447f38c98cbd89123ec03f6212786c0629c386f38154a51ece90cd594b47b7f             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 183                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4e977830ba4bd783c0bb7f15d3e243f73ff57121                                     | Address of the contract that produced the log                |
| fromUser          | VARCHAR   | 0x34478822dc80b79b3fb564d9cf434d64dbc981b0                                     |                                                              |
| toUser            | VARCHAR   | 0xcc9a0b7c43dc2a5f023bb9b738e45b0ef6b06e04                                     |                                                              |
| asset             | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                                     |                                                              |
| amount            | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 189. Table: StableDebtToken\_v2\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-28 12:36:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12722562                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0825cbe703c47e2bf490b906c621d84b39feeb48d58c077ca08e97a4721513e4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 160                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4e977830ba4bd783c0bb7f15d3e243f73ff57121                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x0c90a9d2b0f573c21c499ddac720e2c6e2899f7c                         |                                                              |
| amount            | VARCHAR   | 22994844231028689009                                               |                                                              |
| currentBalance    | VARCHAR   | 25098224804530603840                                               |                                                              |
| balanceIncrease   | VARCHAR   | 5155768971310991                                                   |                                                              |
| avgStableRate     | VARCHAR   | 50871959184864518801505783                                         |                                                              |
| newTotalSupply    | VARCHAR   | 541558558127383246645                                              |                                                              |

## 190. Table: StableDebtToken\_v2\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-14 01:43:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11851866                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x26da016db8c7817ce5efcfeae667fc79d00e2969bf330a4f5c7c21beedbcdc6f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 118                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4e977830ba4bd783c0bb7f15d3e243f73ff57121                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xdcd33426ba191383f1c9b431a342498fdac73488                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x8f6da831710a8d30de1111aaf28c697aaf5056dd                         |                                                              |
| amount            | VARCHAR   | 12000000000000000000                                               |                                                              |
| currentBalance    | VARCHAR   | 0                                                                  |                                                              |
| balanceIncrease   | VARCHAR   | 0                                                                  |                                                              |
| newRate           | VARCHAR   | 50593888004247425680418325                                         |                                                              |
| avgStableRate     | VARCHAR   | 61098050060245996613813249                                         |                                                              |
| newTotalSupply    | VARCHAR   | 652598904965846469778                                              |                                                              |

## 191. Table: StableDebtToken\_v2\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-02 20:41:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16543564                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8e54c1f452ee3e0da3c771750e6c79006d42dff36c9bef59878571a60f80966e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 218                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe4922afab0bbadd8ab2a88e0c79d884ad337fca6                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x540f45337b548824438a25734f429e4b4095476a                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 1000000000                                                         |                                                              |

## 192. Table: StableDebtToken\_v3\_event\_Approval\_history

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

## 193. Table: StableDebtToken\_v3\_event\_BorrowAllowanceDelegated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| fromUser          | VARCHAR   |                                                              |             |
| toUser            | VARCHAR   |                                                              |             |
| asset             | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 194. Table: StableDebtToken\_v3\_event\_Burn\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| from              | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |
| currentBalance    | VARCHAR   |                                                              |             |
| balanceIncrease   | VARCHAR   |                                                              |             |
| avgStableRate     | VARCHAR   |                                                              |             |
| newTotalSupply    | VARCHAR   |                                                              |             |

## 195. Table: StableDebtToken\_v3\_event\_Initialized\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2023-06-23 03:52:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 17539726                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x1cccbb1b88d9aa969348db2577a53dc1fcc76b42e270784d453005838c5968a0 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 101                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x4b62bfaff61ab3985798e5202d2d167f567d0bcd                         | Address of the contract that produced the log                |
| underlyingAsset      | VARCHAR   | 0x111111111117dc0aa78b770fa6a738034120c302                         |                                                              |
| pool                 | VARCHAR   | 0x87870bca3f3fd6335c3f4ce8392d69350b4fa4e2                         |                                                              |
| incentivesController | VARCHAR   | 0x8164cc65827dcfe994ab23944cbc90e0aa80bfcb                         |                                                              |
| debtTokenDecimals    | VARCHAR   | 18                                                                 |                                                              |
| debtTokenName        | VARCHAR   | Aave Ethereum Stable Debt 1INCH                                    |                                                              |
| debtTokenSymbol      | VARCHAR   | stableDebtEth1INCH                                                 |                                                              |
| params               | VARCHAR   | 0x                                                                 |                                                              |

## 196. Table: StableDebtToken\_v3\_event\_Mint\_history

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

## 197. Table: StableDebtToken\_v3\_event\_Transfer\_history

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

## 198. Table: StakedAave\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-05 19:37:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17850904                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x56e55e19f50208f67087efa404b3ff07aec46ad5b971f5e67cabb2351af7421c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 291                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4da27a545c0c5b758a6ba100e3a049001de870f5                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x653050f11b5f20213c9d1ee62cc02a76518649c6                         |                                                              |
| spender           | VARCHAR   | 0x167c606be99dbf5a8af61e1983e5b309e8fa2ae7                         |                                                              |
| value             | VARCHAR   | 100000000000000000000                                              |                                                              |

## 199. Table: StakedAave\_event\_AssetConfigUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-01 20:33:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10972370                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9a6b0b9d3c63e82fa21d6d6d0627e7d6cc25b088278e87c3e3f4f012dcbf4e38 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 95                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4da27a545c0c5b758a6ba100e3a049001de870f5                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x4da27a545c0c5b758a6ba100e3a049001de870f5                         |                                                              |
| emission          | VARCHAR   | 4629629629629630                                                   |                                                              |

## 200. Table: StakedAave\_event\_AssetIndexUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-28 21:35:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17794265                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb799ad957bab09028fb142be0ceea78fc3dd27ab2848b13a3eba2ee5571ececf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 259                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4da27a545c0c5b758a6ba100e3a049001de870f5                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x4da27a545c0c5b758a6ba100e3a049001de870f5                         |                                                              |
| index             | VARCHAR   | 26045056595311876536                                               |                                                              |

## 201. Table: StakedAave\_event\_Cooldown\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-01 12:07:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11770228                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x24348943ddf54b9acb6e48b3c467e9163e9c3ddd25800bface609b80f722f5f4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 260                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4da27a545c0c5b758a6ba100e3a049001de870f5                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xa36fa934d40b34e4b833bbd73d153eb8c0d88b6a                         |                                                              |

## 202. Table: StakedAave\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-25 01:11:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14452413                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbcbdc50d2be361010c7cff89f7c2ec81404bac87f65fa6bf6f49338104bcdb3f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 37                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4da27a545c0c5b758a6ba100e3a049001de870f5                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x7d544a853dbcd39a53315e7002f4951a6d2f080d                         |                                                              |
| to                | VARCHAR   | 0x7d544a853dbcd39a53315e7002f4951a6d2f080d                         |                                                              |
| amount            | VARCHAR   | 19085604545975837945                                               |                                                              |

## 203. Table: StakedAave\_event\_RewardsAccrued\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-01 16:42:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17387214                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3270826dc3ef68bf26c9afd45e4c3abe016af645b6026803f49657fb34513de8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 125                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4da27a545c0c5b758a6ba100e3a049001de870f5                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x37a41ed023207c94049db7c24489c2cf69dba8cd                         |                                                              |
| amount            | VARCHAR   | 64286718616299202000                                               |                                                              |

## 204. Table: StakedAave\_event\_RewardsClaimed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-26 09:13:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15616581                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5607d2612dd861aa8182fae57c1d71a736189d495e59f1b609aec0f02323e328 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 80                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4da27a545c0c5b758a6ba100e3a049001de870f5                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x4c9d61adb5d8b7b554fa3d1056c65daab1158963                         |                                                              |
| to                | VARCHAR   | 0x4c9d61adb5d8b7b554fa3d1056c65daab1158963                         |                                                              |
| amount            | VARCHAR   | 0                                                                  |                                                              |

## 205. Table: StakedAave\_event\_SnapshotDone\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-18 03:54:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11279622                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4a775709e7989e9adf83b9f4a39f40aa24cfb196588678da9275654626991df8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 213                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4da27a545c0c5b758a6ba100e3a049001de870f5                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x327b9dee1830f8201efa751fd96f7b1ad0b300a1                         |                                                              |
| oldValue          | VARCHAR   | 129740933147437540348                                              |                                                              |
| newValue          | VARCHAR   | 0                                                                  |                                                              |

## 206. Table: StakedAave\_event\_Staked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-03 09:57:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16547505                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x64719a45470f2e87fcfe548b3228f2e285c5e34f195fbf234ab6b52ef67faa98 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 125                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4da27a545c0c5b758a6ba100e3a049001de870f5                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x10ce9c96a2f0102c22055982ecf8f393e3534b16                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x10ce9c96a2f0102c22055982ecf8f393e3534b16                         |                                                              |
| amount            | VARCHAR   | 95039284810000000000                                               |                                                              |

## 207. Table: StakedAave\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-07 16:50:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12979131                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x486db51716ce1ac00c4a56fbf9ca51227685335fc78f98e27605c116d3bc5e9d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 121                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4da27a545c0c5b758a6ba100e3a049001de870f5                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x856678ba7e5e57642b71af14425af4cbe9830f0f                         |                                                              |
| value             | VARCHAR   | 42358347067342069                                                  |                                                              |

## 208. Table: StakedAave\_event\_UserIndexUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-27 00:04:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13304550                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbedccb37444e668887fe6a87c4b32ccbe61732806afcd69e19054248b79b4692 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 61                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4da27a545c0c5b758a6ba100e3a049001de870f5                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x20165075174b51a2f9efbf7d6d8f3c72bbc63064                         |                                                              |
| asset             | VARCHAR   | 0x4da27a545c0c5b758a6ba100e3a049001de870f5                         |                                                              |
| index             | VARCHAR   | 25913542035208011772                                               |                                                              |

## 209. Table: StakedTokenV2\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-22 18:08:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16464039                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd3315bdb1ef921ccec15df77773645204d6eea24fcf5e7715e6e1cf284c52d74 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 148                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4da27a545c0c5b758a6ba100e3a049001de870f5                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xfd94fb2f07a4a0cb5c8b88c7a4346dded36f2b1d                         |                                                              |
| spender           | VARCHAR   | 0xa372a45fab2aa66d79fae09b6089da5c53ca8fdf                         |                                                              |
| value             | VARCHAR   | 10000000000000000000000000000000                                   |                                                              |

## 210. Table: StakedTokenV2\_event\_AssetConfigUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-01 20:33:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10972370                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9a6b0b9d3c63e82fa21d6d6d0627e7d6cc25b088278e87c3e3f4f012dcbf4e38 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 95                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4da27a545c0c5b758a6ba100e3a049001de870f5                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x4da27a545c0c5b758a6ba100e3a049001de870f5                         |                                                              |
| emission          | VARCHAR   | 4629629629629630                                                   |                                                              |

## 211. Table: StakedTokenV2\_event\_AssetIndexUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-23 22:07:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17545136                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbb57af0c9d8f45082dba518cce05d2360116a2e9659b88a12730d720d9829097 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 264                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4da27a545c0c5b758a6ba100e3a049001de870f5                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x4da27a545c0c5b758a6ba100e3a049001de870f5                         |                                                              |
| index             | VARCHAR   | 26039077632681086783                                               |                                                              |

## 212. Table: StakedTokenV2\_event\_Cooldown\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-06 11:49:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12580776                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x85c68a8eefd39fc4bc923d8769c0afa7bcc72eadc475513b3c89cb3e50f6b9c5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4da27a545c0c5b758a6ba100e3a049001de870f5                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x17901e99e4757df5102e15253575761cc71d8e95                         |                                                              |

## 213. Table: StakedTokenV2\_event\_DelegateChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-01 07:02:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17597597                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf3d4923f9b09a9b76a0131d1cd44c2a76119064e76bce0439c4742b012511f7b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 83                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4da27a545c0c5b758a6ba100e3a049001de870f5                         | Address of the contract that produced the log                |
| delegator         | VARCHAR   | 0x0bb31c6278d58cff41b7e8ed3b20f76424fd69ad                         |                                                              |
| delegatee         | VARCHAR   | 0x0bb31c6278d58cff41b7e8ed3b20f76424fd69ad                         |                                                              |
| delegationType    | VARCHAR   | 1                                                                  |                                                              |

## 214. Table: StakedTokenV2\_event\_DelegatedPowerChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-19 05:17:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15369485                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2d6a58d3f98621cac06b5894cb03e7eea12e07e05fcccf22c1be337ed80c8bc3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 282                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4da27a545c0c5b758a6ba100e3a049001de870f5                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x60a6d69802239e8678f35cf3cff8af6d64ab4088                         |                                                              |
| amount            | VARCHAR   | 0                                                                  |                                                              |
| delegationType    | VARCHAR   | 0                                                                  |                                                              |

## 215. Table: StakedTokenV2\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-18 04:04:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15994393                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc5bc5b1bca1d84ce5fff2a53f8792f13806a0a1fd42886a58041dfd35f678219 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 126                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4da27a545c0c5b758a6ba100e3a049001de870f5                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x4f88dc12cdbc6606efd359fa4bc8a76d61229e0c                         |                                                              |
| to                | VARCHAR   | 0x4f88dc12cdbc6606efd359fa4bc8a76d61229e0c                         |                                                              |
| amount            | VARCHAR   | 1000000000000000000                                                |                                                              |

## 216. Table: StakedTokenV2\_event\_RewardsAccrued\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-13 19:56:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17686795                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xda2e546ea85e0a0f09a7a82e16a9f25298ef38a8f21bc1e22268553c751666cb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 174                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4da27a545c0c5b758a6ba100e3a049001de870f5                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x1a76f6b9b3d9c532e0b56990944a31a705933fbd                         |                                                              |
| amount            | VARCHAR   | 4552280555703155                                                   |                                                              |

## 217. Table: StakedTokenV2\_event\_RewardsClaimed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-27 11:55:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16061159                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf912b87acb979b86dc93d14dc3651e648de922fe3a5292af543cb120908e8e85 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 262                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4da27a545c0c5b758a6ba100e3a049001de870f5                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x7dc1f21120e9c69d1f420e96e92b049749dc65e7                         |                                                              |
| to                | VARCHAR   | 0x7dc1f21120e9c69d1f420e96e92b049749dc65e7                         |                                                              |
| amount            | VARCHAR   | 299032645438253773                                                 |                                                              |

## 218. Table: StakedTokenV2\_event\_Staked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-24 05:51:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11918080                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd7f8c4c5c747e8f00aaf1041f0509fa1adae9dfdb2c5c9a28fe3ceed883d503e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 263                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4da27a545c0c5b758a6ba100e3a049001de870f5                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xe96afdbd72c29a2c74e1efb2e8d2807abf41d650                         |                                                              |
| onBehalfOf        | VARCHAR   | 0xe96afdbd72c29a2c74e1efb2e8d2807abf41d650                         |                                                              |
| amount            | VARCHAR   | 1025000000000000000000                                             |                                                              |

## 219. Table: StakedTokenV2\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-10 21:00:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17665791                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x862fa1f03491aee63f633a12b4ad722dca525edabac70ff105bf760842d86d1d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 238                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4da27a545c0c5b758a6ba100e3a049001de870f5                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xc15e011b8e117fba8cc241c70950fc79f515ab3e                         |                                                              |
| value             | VARCHAR   | 23800668562130387696                                               |                                                              |

## 220. Table: StakedTokenV2\_event\_UserIndexUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-06 00:18:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17852298                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe0f37cd237161e4449e1702ed31f5a6c660a983cb5f04b408f9281a481dcd744 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 344                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4da27a545c0c5b758a6ba100e3a049001de870f5                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x23c8a0405078d4ab5afbef469f5ea949a604c06b                         |                                                              |
| asset             | VARCHAR   | 0x4da27a545c0c5b758a6ba100e3a049001de870f5                         |                                                              |
| index             | VARCHAR   | 26046471217713262496                                               |                                                              |

## 221. Table: VariableDebtToken\_v2\_event\_Approval\_history

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

## 222. Table: VariableDebtToken\_v2\_event\_BorrowAllowanceDelegated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-22 13:18:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14436327                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf2b2b4ed925c1f8cc00bd13dad3370ab06bc7976d972d5842dfd4c247e1ac197 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 73                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5bdb050a92cadccfcdcccbfc17204a1c9cc0ab73                         | Address of the contract that produced the log                |
| fromUser          | VARCHAR   | 0xcad7698157cc212871c20434424ee7223a1195c5                         |                                                              |
| toUser            | VARCHAR   | 0x59daa74f2d15c87aac435ec18cb559f92490c100                         |                                                              |
| asset             | VARCHAR   | 0x1f9840a85d5af5bf1d1762f925bdaddc4201f984                         |                                                              |
| amount            | VARCHAR   | 1000000000000000000000000                                          |                                                              |

## 223. Table: VariableDebtToken\_v2\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-16 01:27:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13233779                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa90e2e7f4d0c15a48248ad128e57f75428f2e87f9ffcfa398551304fdd261b47 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 293                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfafedf95e21184e3d880bd56d4806c4b8d31c69a                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x9136f2bc99eff3b702ffb72a2f39c937cc2a872c                         |                                                              |
| amount            | VARCHAR   | 4302351505226899237644                                             |                                                              |
| index             | VARCHAR   | 1002096944610458156384671336                                       |                                                              |

## 224. Table: VariableDebtToken\_v2\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-01 21:19:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13335827                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb1b19df73c5489ccae8866339f9e873c48bb7537eb0cff33a8bb0bd24ded40e5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 144                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00ad8ebf64f141f1c81e9f8f792d3d1631c6c684                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xcd76ef2ad25a565e2038b899bc08b0fd273db636                         |                                                              |
| onBehalfOf        | VARCHAR   | 0xcd76ef2ad25a565e2038b899bc08b0fd273db636                         |                                                              |
| value             | VARCHAR   | 410425760000000000000000                                           |                                                              |
| index             | VARCHAR   | 1120018558525545775198650615                                       |                                                              |

## 225. Table: VariableDebtToken\_v2\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-02 09:34:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16540255                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2646805b912eb77f68719a7ec94326999c8843d64027408203c09b4e7bcaae20 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 262                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00ad8ebf64f141f1c81e9f8f792d3d1631c6c684                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xab7e29b882ba62e0a727d5e17308d2d7c67733d1                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 540660736514597990095118                                           |                                                              |

## 226. Table: VariableDebtToken\_v3\_event\_Approval\_history

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

## 227. Table: VariableDebtToken\_v3\_event\_BorrowAllowanceDelegated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-20 23:42:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17524240                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2a72f6bdf73fec07cbf5d43dc0a57bff37dce440a6d9c8df96bdc03dc710c93c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 143                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x72e95b8931767c79ba4eee721354d6e99a61d004                         | Address of the contract that produced the log                |
| fromUser          | VARCHAR   | 0x87f8e46b9d6e9dcf57e65b5e0738e5e9df8b0abf                         |                                                              |
| toUser            | VARCHAR   | 0x9901bac880caecad999e292811db9c1db3e86f8a                         |                                                              |
| asset             | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| amount            | VARCHAR   | 9000000000                                                         |                                                              |

## 228. Table: VariableDebtToken\_v3\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-13 13:03:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17251230                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x14fdd1911bfe454da5b9c468441e19197363a8ce48420439e0724a80ea5a2f4f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 367                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x33652e48e4b74d18520f11bfe58edd2ed2cec5a2                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x87dd8e76e0c20ebc88754b5dc92ad5150c044ceb                         |                                                              |
| target            | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 79551503751850888872969                                            |                                                              |
| balanceIncrease   | VARCHAR   | 332656672700211780341                                              |                                                              |
| index             | VARCHAR   | 1007104157915004627566194799                                       |                                                              |

## 229. Table: VariableDebtToken\_v3\_event\_Initialized\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2023-06-23 03:52:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 17539726                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x1cccbb1b88d9aa969348db2577a53dc1fcc76b42e270784d453005838c5968a0 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 102                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0xa38fca8c6bf9bda52e76eb78f08caa3be7c5a970                         | Address of the contract that produced the log                |
| underlyingAsset      | VARCHAR   | 0x111111111117dc0aa78b770fa6a738034120c302                         |                                                              |
| pool                 | VARCHAR   | 0x87870bca3f3fd6335c3f4ce8392d69350b4fa4e2                         |                                                              |
| incentivesController | VARCHAR   | 0x8164cc65827dcfe994ab23944cbc90e0aa80bfcb                         |                                                              |
| debtTokenDecimals    | VARCHAR   | 18                                                                 |                                                              |
| debtTokenName        | VARCHAR   | Aave Ethereum Variable Debt 1INCH                                  |                                                              |
| debtTokenSymbol      | VARCHAR   | variableDebtEth1INCH                                               |                                                              |
| params               | VARCHAR   | 0x                                                                 |                                                              |

## 230. Table: VariableDebtToken\_v3\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-06 09:13:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16768356                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x783a16ecd715fba1a32867ea1f1e8a0ce93cc43a4d69c38432602bbb6de85c93 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 286                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4228f8895c7dda20227f6a5c6751b8ebf19a6ba8                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x2bc12061c8912505978472c21d4a23db43af62aa                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x2bc12061c8912505978472c21d4a23db43af62aa                         |                                                              |
| value             | VARCHAR   | 200000000000000000                                                 |                                                              |
| balanceIncrease   | VARCHAR   | 0                                                                  |                                                              |
| index             | VARCHAR   | 1000218614244723773237778251                                       |                                                              |

## 231. Table: VariableDebtToken\_v3\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-18 19:11:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16856636                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0bf48e39c915d2e48aba706f9d7ec25f5f7c477243d7638ee08d7948620e389b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 127                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x33652e48e4b74d18520f11bfe58edd2ed2cec5a2                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x5276a8ccf431c46d2cf448b9827eac0f4e4da64c                         |                                                              |
| value             | VARCHAR   | 2507374611647268517613                                             |                                                              |
