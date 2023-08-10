# aave\_arc

## 1. Table: AToken\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-03 00:14:03+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13730390                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc300f7d1260a763f4504b2ea3ee02381163f98bbe955c506b8e74bdb82557e4b             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 406                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x319190e3bbc595602a9e63b2bcfb61c6634355b1                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x2057f774f0e081bd2bbe301e2bb73b9dbe38381c                                     |                                                              |
| spender           | VARCHAR   | 0xd51e46b02ecb71357cbdf661e2789ec787d94af9                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457583007913129639935 |                                                              |

## 2. Table: AToken\_event\_BalanceTransfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-19 16:37:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14805999                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8d372804dc62ca312c6c359bb4ddf26f0d190de9a29cbc1c4255432e5a3a13c6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 31                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x319190e3bbc595602a9e63b2bcfb61c6634355b1                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x42dd4bcde3d1d2d56a518c4f052f119d0f10beec                         |                                                              |
| to                | VARCHAR   | 0xd51e46b02ecb71357cbdf661e2789ec787d94af9                         |                                                              |
| value             | VARCHAR   | 20000178867851685271                                               |                                                              |
| index             | VARCHAR   | 1000040722893115233390476951                                       |                                                              |

## 3. Table: AToken\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-14 10:05:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14384062                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xddb03383970f0dd515a46e0e628105948085ff69f77f0ca4053827a1f523c174 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 273                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x319190e3bbc595602a9e63b2bcfb61c6634355b1                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xd51e46b02ecb71357cbdf661e2789ec787d94af9                         |                                                              |
| target            | VARCHAR   | 0xd51e46b02ecb71357cbdf661e2789ec787d94af9                         |                                                              |
| value             | VARCHAR   | 4199000013676984997252                                             |                                                              |
| index             | VARCHAR   | 1000034386010880802284507254                                       |                                                              |

## 4. Table: AToken\_event\_Initialized\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2021-10-16 22:25:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 13431722                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x148f22323fe871d883f9e29612e71b3682602a0a40ef3a2d35189c77876c0114 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x319190e3bbc595602a9e63b2bcfb61c6634355b1                         | Address of the contract that produced the log                |
| underlyingAsset      | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| pool                 | VARCHAR   | 0x37d7306019a38af123e4b245eb6c28af552e0bb0                         |                                                              |
| treasury             | VARCHAR   | 0x464c71f6c2f760dda6093dcb91c24c39e5d6e18c                         |                                                              |
| incentivesController | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| aTokenDecimals       | VARCHAR   | 18                                                                 |                                                              |
| aTokenName           | VARCHAR   | Aave Arc market WETH                                               |                                                              |
| aTokenSymbol         | VARCHAR   | aWETH                                                              |                                                              |
| params               | VARCHAR   | 0x10                                                               |                                                              |

## 5. Table: AToken\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-17 09:27:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14978425                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x21d36e50111b0d7b2eb57c168c3ffdd80097f08b01e74d3380f513640ae31d00 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 267                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x319190e3bbc595602a9e63b2bcfb61c6634355b1                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x1b7793dfd62d0131fceeb2be4c404ff9bbc5c67c                         |                                                              |
| value             | VARCHAR   | 1000000000000000000                                                |                                                              |
| index             | VARCHAR   | 1000045315969667422018681316                                       |                                                              |

## 6. Table: AToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-19 18:19:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14037541                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe4e6df8aaebc2a6a141c0d5d46dbb815824f4492f7ed90cb9e37312fb9620e69 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 392                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x319190e3bbc595602a9e63b2bcfb61c6634355b1                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x464c71f6c2f760dda6093dcb91c24c39e5d6e18c                         |                                                              |
| value             | VARCHAR   | 111251622354                                                       |                                                              |

## 7. Table: PermissionedLendingPool\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-20 18:16:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13843643                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8212f63ffce5770f29413808319c36fb27c01e1cdd10998055a727f1a38abae6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 37                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x37d7306019a38af123e4b245eb6c28af552e0bb0                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| user              | VARCHAR   | 0x42dd4bcde3d1d2d56a518c4f052f119d0f10beec                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x42dd4bcde3d1d2d56a518c4f052f119d0f10beec                         |                                                              |
| amount            | VARCHAR   | 10000000000                                                        |                                                              |
| borrowRateMode    | VARCHAR   | 1                                                                  |                                                              |
| borrowRate        | VARCHAR   | 50111223235316585505851203                                         |                                                              |
| referral          | VARCHAR   | 0                                                                  |                                                              |

## 8. Table: PermissionedLendingPool\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-20 10:27:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13841476                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x88c478f8207953ef8c955fdfe42977b1eb2b7db09d861e61b1b124e45615f3a1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 180                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x37d7306019a38af123e4b245eb6c28af552e0bb0                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x7fc66500c84a76ad7e9c93437bfc5ac33e2ddae9                         |                                                              |
| user              | VARCHAR   | 0x008c8395eaba2553cde019af1be19a89630e031f                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x008c8395eaba2553cde019af1be19a89630e031f                         |                                                              |
| amount            | VARCHAR   | 10289275817130000000000                                            |                                                              |
| referral          | VARCHAR   | 0                                                                  |                                                              |

## 9. Table: PermissionedLendingPool\_event\_FlashLoan\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| target            | VARCHAR   |                                                              |             |
| initiator         | VARCHAR   |                                                              |             |
| asset             | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |
| premium           | VARCHAR   |                                                              |             |
| referralCode      | VARCHAR   |                                                              |             |

## 10. Table: PermissionedLendingPool\_event\_LiquidationCall\_history

| Column                     | Type      | Example                                                      | Description |
| -------------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp           | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number              | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash          | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index                 | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address          | VARCHAR   | Address of the contract that produced the log                |             |
| collateralAsset            | VARCHAR   |                                                              |             |
| debtAsset                  | VARCHAR   |                                                              |             |
| user                       | VARCHAR   |                                                              |             |
| debtToCover                | VARCHAR   |                                                              |             |
| liquidatedCollateralAmount | VARCHAR   |                                                              |             |
| liquidator                 | VARCHAR   |                                                              |             |
| receiveAToken              | VARCHAR   |                                                              |             |

## 11. Table: PermissionedLendingPool\_event\_Paused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-16 22:01:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13431610                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb8365ec0787a5fadb1e3d4da792744be9b4f4cb4566ce1530a009815b923a5c7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x37d7306019a38af123e4b245eb6c28af552e0bb0                         | Address of the contract that produced the log                |

## 12. Table: PermissionedLendingPool\_event\_RebalanceStableBorrowRate\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| reserve           | VARCHAR   |                                                              |             |
| user              | VARCHAR   |                                                              |             |

## 13. Table: PermissionedLendingPool\_event\_Repay\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-03 13:42:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14897438                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdb492e059ef75f659aa51c1f78925b6be9c613133866bc37c7c30b9f844f1eb7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 245                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x37d7306019a38af123e4b245eb6c28af552e0bb0                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| user              | VARCHAR   | 0x2a5469d6a6a1cb8a0d539a5aec446b45ba1bcf83                         |                                                              |
| repayer           | VARCHAR   | 0xd51e46b02ecb71357cbdf661e2789ec787d94af9                         |                                                              |
| amount            | VARCHAR   | 800657556577971683                                                 |                                                              |

## 14. Table: PermissionedLendingPool\_event\_ReserveDataUpdated\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2022-01-26 13:40:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 14081589                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xf080ce53b16f63d1599102b2560b725543c20d193074e96d80221ff742dc7954 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 135                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x37d7306019a38af123e4b245eb6c28af552e0bb0                         | Address of the contract that produced the log                |
| reserve             | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| liquidityRate       | VARCHAR   | 12437891980720635406164633                                         |                                                              |
| stableBorrowRate    | VARCHAR   | 51384880211204051973463661                                         |                                                              |
| variableBorrowRate  | VARCHAR   | 24769760422408103946927321                                         |                                                              |
| liquidityIndex      | VARCHAR   | 1002079075973394418509732398                                       |                                                              |
| variableBorrowIndex | VARCHAR   | 1003421923682544822594329174                                       |                                                              |

## 15. Table: PermissionedLendingPool\_event\_ReserveUsedAsCollateralDisabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-26 13:40:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14081589                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf080ce53b16f63d1599102b2560b725543c20d193074e96d80221ff742dc7954 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 136                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x37d7306019a38af123e4b245eb6c28af552e0bb0                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| user              | VARCHAR   | 0x74ba0c212b6f6eaffe8d1956d547142e19291368                         |                                                              |

## 16. Table: PermissionedLendingPool\_event\_ReserveUsedAsCollateralEnabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-28 16:49:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14095352                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x57f8c7050b3118caf2a94de21cb1721625e39366d3a5c2631967b56a6a14921b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 11                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x37d7306019a38af123e4b245eb6c28af552e0bb0                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| user              | VARCHAR   | 0x12660c90eab7eb98d6065f55fb222f8b68b80f24                         |                                                              |

## 17. Table: PermissionedLendingPool\_event\_Swap\_history

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

## 18. Table: PermissionedLendingPool\_event\_Unpaused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-27 20:19:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13698141                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x23913443ec3c6260cb266a0324051a864ccf8ec2e0dc01919bf9923944755b7b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 588                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x37d7306019a38af123e4b245eb6c28af552e0bb0                         | Address of the contract that produced the log                |

## 19. Table: PermissionedLendingPool\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-25 12:06:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14275144                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x79f3305269cd4f739e10993f003b3b29035e0de309e0ea91290e829d4d61e4a5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 150                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x37d7306019a38af123e4b245eb6c28af552e0bb0                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| user              | VARCHAR   | 0x74ba0c212b6f6eaffe8d1956d547142e19291368                         |                                                              |
| to                | VARCHAR   | 0x74ba0c212b6f6eaffe8d1956d547142e19291368                         |                                                              |
| amount            | VARCHAR   | 400100000                                                          |                                                              |
