# truefi

## 1. Table: LoanFactory2\_event\_LoanTokenCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-07 07:06:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15916543                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x99f9a11b2e67a5b2c8e86698e4c8746ee6ab3d8bc8581cdec8c6537b5395c463 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 61                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x69d844fb5928d0e7bc530cc6325a88e53d6685bc                         | Address of the contract that produced the log                |
| contractAddress   | VARCHAR   | 0x619578647dc3b58196c67d11e341a76ccb3d22d2                         |                                                              |

## 2. Table: LoanToken2\_event\_Approval\_history

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

## 3. Table: LoanToken2\_event\_Defaulted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-12 19:24:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15734095                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9a4309bad5a047f128ca62bd69e12ef47992da5eca3fd540256a9fe4507975f5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 137                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4a66a867f52df4ed1d8580a1c383b2dd036a3c47                         | Address of the contract that produced the log                |
| returnedAmount    | VARCHAR   | 645405815696064463503820                                           |                                                              |

## 4. Table: LoanToken2\_event\_Funded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-12 02:50:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13598742                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xeb8c6d07fb3fa09c66e2dfbdb9ad5d8b540ad08e3109996378b09dcf9dbb1456 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 106                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe02c823bdbb528683347519062426e1049ed1f7e                         | Address of the contract that produced the log                |
| lender            | VARCHAR   | 0xa606dd423df7dfb65efe14ab66f5fdebf62ff583                         |                                                              |

## 5. Table: LoanToken2\_event\_Liquidated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-02 17:05:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15883716                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6301a634575377750fd9cbd41b27a672bc96e70f14845a353ca14b7388d19eb6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 149                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x97688fb5a06b6f3d3b524f7530afbeb883cdc642                         | Address of the contract that produced the log                |
| status            | VARCHAR   | 5                                                                  |                                                              |

## 6. Table: LoanToken2\_event\_Reclaimed\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| borrower          | VARCHAR   |                                                              |             |
| reclaimedAmount   | VARCHAR   |                                                              |             |

## 7. Table: LoanToken2\_event\_Redeemed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-19 02:31:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12854371                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd17f41b07581ec2dfe07b25e47d2f44787dc676c6db4beb72a2557f4fe6c5390 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 268                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8ab3055722c62be1673a194cc9c7a0fbdd898eca                         | Address of the contract that produced the log                |
| receiver          | VARCHAR   | 0xa606dd423df7dfb65efe14ab66f5fdebf62ff583                         |                                                              |
| burnedAmount      | VARCHAR   | 506986301369                                                       |                                                              |
| redeemedAmount    | VARCHAR   | 506986301369                                                       |                                                              |

## 8. Table: LoanToken2\_event\_Repaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-23 17:54:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16471131                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x70b107fc343464d96b76950adb53204cc8abc81cdd802b6a9624aa23eb10d013 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 178                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x232e0a81c41c0b0999e7b671cb5046beb808c49f                         | Address of the contract that produced the log                |
| repayer           | VARCHAR   | 0xb868dd38a23b0ad901b635d7b7fe235f2460dc2b                         |                                                              |
| repaidAmount      | VARCHAR   | 5649178082191                                                      |                                                              |

## 9. Table: LoanToken2\_event\_Settled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-18 13:34:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15560761                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7601d7fa78a9835b5413025da1bc468c18554ae5b9a86c74f493024547b869b9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 76                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xccfceb165345e9c5231cf1465aa8e956dc28e2fb                         | Address of the contract that produced the log                |
| returnedAmount    | VARCHAR   | 2518534246575                                                      |                                                              |

## 10. Table: LoanToken2\_event\_TransferAllowanceChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |
| status            | VARCHAR   |                                                              |             |

## 11. Table: LoanToken2\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-25 00:26:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14650636                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x48b719eda3e56d4c190724bb2e4852c904d9e5dade071dee7ed39a70efd0e3a2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 12                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xafb79df39e1b898df00f0ac71e96dd7b7dc8bb97                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xa606dd423df7dfb65efe14ab66f5fdebf62ff583                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 51191053369863                                                     |                                                              |

## 12. Table: LoanToken2\_event\_Withdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-06 12:36:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13562991                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xea17918810c2a37daa393e9fe0b2c6c4366b61ee0e5dc3f67f9db54e4a5a7b07 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 283                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7b785b0dab2c37a07a307882c68cdbcff5301cdb                         | Address of the contract that produced the log                |
| beneficiary       | VARCHAR   | 0x728b77751a7b1ae29a94901695f3dd8add37d086                         |                                                              |

## 13. Table: ManagedPortfolioFactory\_event\_AdminChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousAdmin     | VARCHAR   |                                                              |             |
| newAdmin          | VARCHAR   |                                                              |             |

## 14. Table: ManagedPortfolioFactory\_event\_BeaconUpgraded\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| beacon            | VARCHAR   |                                                              |             |

## 15. Table: ManagedPortfolioFactory\_event\_ManagementTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-20 18:05:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14043986                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4e0b377637b7e33fe09ab048a5bf1fbdc2c101504c88a9a197747b1d07cb4d87 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 72                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x17b7b75fd4288197cfd99d20e13b0dd9da1ff3e7                         | Address of the contract that produced the log                |
| oldManager        | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newManager        | VARCHAR   | 0x456fd9437380f16ce5655e65e2d5e990ddc7b95f                         |                                                              |

## 16. Table: ManagedPortfolioFactory\_event\_PortfolioCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-20 20:02:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14044506                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5b48a6b2cec501da0af2d25c84af5d6d78f34bbdf085c96346ef4793839d4cfc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 63                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x17b7b75fd4288197cfd99d20e13b0dd9da1ff3e7                         | Address of the contract that produced the log                |
| newPortfolio      | VARCHAR   | 0xa62cafd41676613e3723ff966a0f2e3f6ddffee2                         |                                                              |
| manager           | VARCHAR   | 0xc8bd2387db21aafdd5235b4f223fd5e2c2815ed4                         |                                                              |

## 17. Table: ManagedPortfolioFactory\_event\_PortfolioImplementationChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-31 15:43:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14494845                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x71cb1770af2a94095d68608240dda46d04251de6715c8fc421997e43d31ec1ab | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 298                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x17b7b75fd4288197cfd99d20e13b0dd9da1ff3e7                         | Address of the contract that produced the log                |
| newImplementation | VARCHAR   | 0x7d738e64f278322a7eb1889753b9c528b74789f5                         |                                                              |

## 18. Table: ManagedPortfolioFactory\_event\_Upgraded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-20 18:05:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14043986                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4e0b377637b7e33fe09ab048a5bf1fbdc2c101504c88a9a197747b1d07cb4d87 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 71                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x17b7b75fd4288197cfd99d20e13b0dd9da1ff3e7                         | Address of the contract that produced the log                |
| implementation    | VARCHAR   | 0x239128d59a94cdc8f08b29e3c0a5ed9059787154                         |                                                              |

## 19. Table: ManagedPortfolioFactory\_event\_WhitelistChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-18 21:13:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14232420                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6ea15a52895dcd96e06e546c280186b744245cc9ab0e2c3e31fe53d1acd21baf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 84                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x17b7b75fd4288197cfd99d20e13b0dd9da1ff3e7                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xf0ae09d3abdf3641e2eb4cd45cf56873296a02cb                         |                                                              |
| whitelisted       | VARCHAR   | true                                                               |                                                              |

## 20. Table: ManagedPortfolio\_call\_initialize\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| \_name             | VARCHAR   |                                                                                                                        |             |
| \_symbol           | VARCHAR   |                                                                                                                        |             |
| \_manager          | VARCHAR   |                                                                                                                        |             |
| \_underlyingToken  | VARCHAR   |                                                                                                                        |             |
| \_bulletLoans      | VARCHAR   |                                                                                                                        |             |
| \_protocolConfig   | VARCHAR   |                                                                                                                        |             |
| \_lenderVerifier   | VARCHAR   |                                                                                                                        |             |
| \_duration         | VARCHAR   |                                                                                                                        |             |
| \_maxSize          | VARCHAR   |                                                                                                                        |             |
| \_managerFee       | VARCHAR   |                                                                                                                        |             |

## 21. Table: ManagedPortfolio\_event\_AdminChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousAdmin     | VARCHAR   |                                                              |             |
| newAdmin          | VARCHAR   |                                                              |             |

## 22. Table: ManagedPortfolio\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-08 18:52:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14347893                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x387f0a5aa42a9e5ada06306ae335d183b477bc6c7b618ecdbc53fed2a31b0b36 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 551                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6a32f6d334ea790e126737f12acefdf9ea94d335                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x5664230e0bcb842dad7deeec8c9c6e0a9a4c1ad4                         |                                                              |
| spender           | VARCHAR   | 0x5664230e0bcb842dad7deeec8c9c6e0a9a4c1ad4                         |                                                              |
| value             | VARCHAR   | 10000000000000000000000                                            |                                                              |

## 23. Table: ManagedPortfolio\_event\_BeaconUpgraded\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| beacon            | VARCHAR   |                                                              |             |

## 24. Table: ManagedPortfolio\_event\_BulletLoanCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-23 18:14:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17323636                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa94ee192d7575beaaa142d6da6789dbffb5a0b2b25f28cebfe66e730345928e7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 208                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe2805231071207bc9d5781f9f09afab43b068661                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 31                                                                 |                                                              |
| loanDuration      | VARCHAR   | 1123200                                                            |                                                              |
| borrower          | VARCHAR   | 0x95b84e1be8edccc41b04d126488e0f359263f9b5                         |                                                              |
| principalAmount   | VARCHAR   | 105250000000                                                       |                                                              |
| repaymentAmount   | VARCHAR   | 105549890410                                                       |                                                              |

## 25. Table: ManagedPortfolio\_event\_BulletLoanDefaulted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-21 12:46:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16233165                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd805be10acbadba680a80e93cfb85570cbcb9f388cbac973df028a09180b373b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 129                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3eabf546fff0a41edaaf5b667333a84628571318                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 15                                                                 |                                                              |

## 26. Table: ManagedPortfolio\_event\_Deposited\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-12 19:43:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14572737                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x706b14428db9abc4407526713c4ca6aa3d744e724710b22b27052d9b67d9c7ea | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 77                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6a32f6d334ea790e126737f12acefdf9ea94d335                         | Address of the contract that produced the log                |
| lender            | VARCHAR   | 0x4275b0239bc61979b1d3de59fc239875d9b53168                         |                                                              |
| amount            | VARCHAR   | 2038063050000                                                      |                                                              |

## 27. Table: ManagedPortfolio\_event\_EndDateChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-12 19:51:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15328973                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x696bd80e4eb8dcfb98c0b8a258937c1eb25a272c57a2c94589b9cdd49d099063 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 572                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfed8fd5ddcddba9bbe90842c94f6ff4cb2efedc9                         | Address of the contract that produced the log                |
| newEndDate        | VARCHAR   | 1660335300                                                         |                                                              |

## 28. Table: ManagedPortfolio\_event\_LenderVerifierChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-09 18:59:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14744062                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x38fb7c0de79cf570e821138f7e7c5aa1c55f225bd6ef6167a68748287c9a24a4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 291                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x021550e7c37b7d4fa1d16737ea8a17ef114668a8                         | Address of the contract that produced the log                |
| newLenderVerifier | VARCHAR   | 0x06d5718c2bb342bf8ad93165578c06c7f1ac0464                         |                                                              |

## 29. Table: ManagedPortfolio\_event\_ManagementTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-18 23:09:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14612001                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x73d824f4642b64f096dfcd78bffea0de4b147ba3c764cfb6656f97e44db20249 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 71                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x021550e7c37b7d4fa1d16737ea8a17ef114668a8                         | Address of the contract that produced the log                |
| oldManager        | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newManager        | VARCHAR   | 0xf0ae09d3abdf3641e2eb4cd45cf56873296a02cb                         |                                                              |

## 30. Table: ManagedPortfolio\_event\_ManagerFeeChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-08 22:33:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14168139                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdafcc0b22adcf9ac08e123be94870e271bda174701d2de9bf338109bdc7a4542 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 506                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf3094013e6106dc26828b64bcde92240398a8379                         | Address of the contract that produced the log                |
| newManagerFee     | VARCHAR   | 0                                                                  |                                                              |

## 31. Table: ManagedPortfolio\_event\_MaxSizeChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-20 22:37:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14045226                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbfbafedb739105500785e3045bdf37e75c5ba1580869bcc5903d949f03d1a40b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 615                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa62cafd41676613e3723ff966a0f2e3f6ddffee2                         | Address of the contract that produced the log                |
| newMaxSize        | VARCHAR   | 2010000000000                                                      |                                                              |

## 32. Table: ManagedPortfolio\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-19 08:49:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14415891                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1704cfc202b89754c36b94ea11fa35df5d1d9ca6553bf069d83b84b5f4c16359 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 147                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6a32f6d334ea790e126737f12acefdf9ea94d335                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xb58b3e8b334ebfda6eb27f0c13974e058085f422                         |                                                              |
| value             | VARCHAR   | 4998959272660332950175                                             |                                                              |

## 33. Table: ManagedPortfolio\_event\_Upgraded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-08 22:37:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17438583                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd991042ef889de4081dfd1effad68615ddf8a290b382d1e0f9a707cf882bb1ba | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 134                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe2805231071207bc9d5781f9f09afab43b068661                         | Address of the contract that produced the log                |
| implementation    | VARCHAR   | 0xcc25560cce858f7db67d76137f7a9d3e7992afd9                         |                                                              |

## 34. Table: ManagedPortfolio\_event\_Withdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-09 03:09:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17439921                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7a476a92487bd4d5d09e769b9ededcb7379ccce080760a5560a71bb58c2ef613 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 295                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe2805231071207bc9d5781f9f09afab43b068661                         | Address of the contract that produced the log                |
| lender            | VARCHAR   | 0xf96e2445bad0a1739a9f2cec71ed5a951d47149a                         |                                                              |
| sharesAmount      | VARCHAR   | 9899981533385103897                                                |                                                              |
| receivedAmount    | VARCHAR   | 496915277                                                          |                                                              |

## 35. Table: PoolFactory\_event\_AllowAllStatusChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| status            | VARCHAR   |                                                              |             |

## 36. Table: PoolFactory\_event\_AllowedStatusChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-09 20:36:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12993161                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd6eb20f0055fc11da15686e144bdfb3b0ac07be3abba1903b7df7403124e4552 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 140                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1391d9223e08845e536157995085fe0cef8bd393                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x0000000000085d4780b73119b644ae5ecd22b376                         |                                                              |
| status            | VARCHAR   | true                                                               |                                                              |

## 37. Table: PoolFactory\_event\_BorrowerWhitelistStatusChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| borrower          | VARCHAR   |                                                              |             |
| status            | VARCHAR   |                                                              |             |

## 38. Table: PoolFactory\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-20 19:22:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12473148                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbbfc9708b1dab134ff239aa067a2d5a8942283b3cbb8f2ef4f7914fefa9e0ef6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1391d9223e08845e536157995085fe0cef8bd393                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0xf6e2da7d82ee49f76ce652bc0beb546cbe0ea521                         |                                                              |
| newOwner          | VARCHAR   | 0x16cea306506c387713c70b9c1205fd5ac997e78e                         |                                                              |

## 39. Table: PoolFactory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-17 17:13:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12653200                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe4d353c8f2cd6f68b302ebe07d4c7eac64dc00a6a58255310f40090604913a3d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 292                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1391d9223e08845e536157995085fe0cef8bd393                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0xdac17f958d2ee523a2206206994597c13d831ec7                         |                                                              |
| pool              | VARCHAR   | 0x6002b1dcb26e7b1aa797a17551c6f487923299d7                         |                                                              |

## 40. Table: PoolFactory\_event\_SafuChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-24 21:25:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13090512                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x481b223920e1a27acc349e57bc3a7458520d88ed8a890888827240a9b4b9f0a6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 295                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1391d9223e08845e536157995085fe0cef8bd393                         | Address of the contract that produced the log                |
| newSafu           | VARCHAR   | 0x1ea63189eb1f4c109b10cf6567f328c826aa6151                         |                                                              |

## 41. Table: PoolFactory\_event\_SingleBorrowerPoolCreated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| borrower          | VARCHAR   |                                                              |             |
| token             | VARCHAR   |                                                              |             |
| pool              | VARCHAR   |                                                              |             |

## 42. Table: PoolFactory\_event\_TrueLenderChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-20 16:44:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12472423                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x103aa01234278cee8921a11297fb55af228896553789b6590ef737f72b49db66 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 155                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1391d9223e08845e536157995085fe0cef8bd393                         | Address of the contract that produced the log                |
| trueLender2       | VARCHAR   | 0xa606dd423df7dfb65efe14ab66f5fdebf62ff583                         |                                                              |

## 43. Table: TrueFiPool2\_event\_Approval\_history

| Column            | Type      | Example                                                                       | Description                                                  |
| ----------------- | --------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-22 21:23:11+00:00                                                     | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16242907                                                                      | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x42858bd1aca207e4aff3797cb1bf251cc4a706ca44f21e9771772e00989bbace            | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 53                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa991356d261fbaf194463af6df8f0464f8f1c742                                    | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xe6c58978d013b757eb315bd6fd776bee2ee2b63c                                    |                                                              |
| spender           | VARCHAR   | 0xec6c3fd795d6e6f202825ddb56e01b3c128b0b10                                    |                                                              |
| value             | VARCHAR   | 57896044618658097711785492504343953926634992332820282019728792003912809237500 |                                                              |

## 44. Table: TrueFiPool2\_event\_BeneficiaryChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newBeneficiary    | VARCHAR   |                                                              |             |

## 45. Table: TrueFiPool2\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-05 21:23:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13947840                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x640418281be5f3ae6cb8e01278dfa5f1c24e309cb0c60c5ef165fceff0a668d4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 174                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6002b1dcb26e7b1aa797a17551c6f487923299d7                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0xa606dd423df7dfb65efe14ab66f5fdebf62ff583                         |                                                              |
| amount            | VARCHAR   | 54310000000000                                                     |                                                              |

## 46. Table: TrueFiPool2\_event\_Collected\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| beneficiary       | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 47. Table: TrueFiPool2\_event\_CreditAgencyChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newCreditAgency   | VARCHAR   |                                                              |             |

## 48. Table: TrueFiPool2\_event\_DeficitReclaimed\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| loan              | VARCHAR   |                                                              |             |
| deficit           | VARCHAR   |                                                              |             |

## 49. Table: TrueFiPool2\_event\_Exited\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-09 15:23:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12601092                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0f4850c9e3189ef16b080ae20760ce6c8d2a36d023c21a65d89e2472d18cc9de | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 217                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa991356d261fbaf194463af6df8f0464f8f1c742                         | Address of the contract that produced the log                |
| staker            | VARCHAR   | 0xff6d071e814ce9bb571bd3fbc281afc1c4475411                         |                                                              |
| amount            | VARCHAR   | 762379560752                                                       |                                                              |

## 50. Table: TrueFiPool2\_event\_Flushed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-22 01:23:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13464517                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5ef004a8940a175294b5f5b8f59acb7a63023a5ead26f38b7843caac25adf4b7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 583                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa991356d261fbaf194463af6df8f0464f8f1c742                         | Address of the contract that produced the log                |
| currencyAmount    | VARCHAR   | 57165045120658                                                     |                                                              |

## 51. Table: TrueFiPool2\_event\_Joined\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-07 15:03:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15918920                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6a6528e2623457006d307e1647789c19b615f34e254dc8ebc4b8ee52c82fb69f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 226                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6002b1dcb26e7b1aa797a17551c6f487923299d7                         | Address of the contract that produced the log                |
| staker            | VARCHAR   | 0x298629982613bf36c48d0b31afd2fe7d1b4604dc                         |                                                              |
| deposited         | VARCHAR   | 2705813973095                                                      |                                                              |
| minted            | VARCHAR   | 2468808280446                                                      |                                                              |

## 52. Table: TrueFiPool2\_event\_JoiningFeeChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newFee            | VARCHAR   |                                                              |             |

## 53. Table: TrueFiPool2\_event\_OracleChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-16 17:27:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13627899                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe57e04ce0d6f69f702b8ed451d6bb989a179dae7442c3fdc830dadd3a89ee4da | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 51                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1ed460d149d48fa7d91703bf4890f97220c09437                         | Address of the contract that produced the log                |
| newOracle         | VARCHAR   | 0x93f2edf37f368c088dcc4ad3b9f74f6f7b359a8b                         |                                                              |

## 54. Table: TrueFiPool2\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-17 17:13:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12653200                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe4d353c8f2cd6f68b302ebe07d4c7eac64dc00a6a58255310f40090604913a3d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 291                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6002b1dcb26e7b1aa797a17551c6f487923299d7                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x16cea306506c387713c70b9c1205fd5ac997e78e                         |                                                              |

## 55. Table: TrueFiPool2\_event\_PauseStatusChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-27 06:25:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13694493                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6c099c3f0013284b1278b0368bd61e90d1e445dd54c75ce9117380936e9cb0b3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6002b1dcb26e7b1aa797a17551c6f487923299d7                         | Address of the contract that produced the log                |
| pauseStatus       | VARCHAR   | true                                                               |                                                              |

## 56. Table: TrueFiPool2\_event\_Pulled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-04 19:55:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13552193                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x44a6855c7ff69d43957d98ab9e86f48c041c9e709b290311cbd11bf60c5d5feb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 218                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa991356d261fbaf194463af6df8f0464f8f1c742                         | Address of the contract that produced the log                |
| minTokenAmount    | VARCHAR   | 40000000000000                                                     |                                                              |

## 57. Table: TrueFiPool2\_event\_Repaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-16 07:33:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13427713                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x80e6fe2d74bfc806a2ebe85a62e935fc00617060f0cf4d66b494e5b192d169d5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 286                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa991356d261fbaf194463af6df8f0464f8f1c742                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0xa606dd423df7dfb65efe14ab66f5fdebf62ff583                         |                                                              |
| amount            | VARCHAR   | 24542694776973                                                     |                                                              |

## 58. Table: TrueFiPool2\_event\_SafuChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-24 21:29:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13090530                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb8e4b7693f173a95d40c4da8c36b12e8b6c0bd0581c67e5f2bd347cd56753bc0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 264                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6002b1dcb26e7b1aa797a17551c6f487923299d7                         | Address of the contract that produced the log                |
| newSafu           | VARCHAR   | 0x1ea63189eb1f4c109b10cf6567f328c826aa6151                         |                                                              |

## 59. Table: TrueFiPool2\_event\_StrategySwitched\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-17 17:28:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13044055                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x40661605452daa9428c8a347af2ed94223ba67fd8f6594fc55ecc28d68a61979 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 24                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x97ce06c3e3d027715b2d6c22e67d5096000072e5                         | Address of the contract that produced the log                |
| newStrategy       | VARCHAR   | 0xcb829b1aa77b8b57d320af05a780757c8c2b88c1                         |                                                              |

## 60. Table: TrueFiPool2\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-08 00:25:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12590635                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb6efce86f76756563741f2777b492bf2ac5c0ec2bfe159dbc34ffef459580ff2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 239                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa991356d261fbaf194463af6df8f0464f8f1c742                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xff707c50efa2f3711916d4a335a5ca3af2d4f20a                         |                                                              |
| value             | VARCHAR   | 49003661985                                                        |                                                              |

## 61. Table: TrueFiPool\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-21 18:24:27+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12871369                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xae844ed6322cd0406ca28057d7b59efc582c7b8a7569a09628de810174324f84             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 206                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa1e72267084192db7387c8cc1328fade470e4149                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x74de5d4fcbf63e00296fd95d33236b9794016631                                     |                                                              |
| spender           | VARCHAR   | 0x11111112542d85b3ef69ae05771c2dccff4faa26                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564020381546402491853263695 |                                                              |

## 62. Table: TrueFiPool\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-02 14:09:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12946382                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x550e4311a3eb5580da77ec781e9b286fc698aa34f78e33ae17c6a42a7fc022b1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 251                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa1e72267084192db7387c8cc1328fade470e4149                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0xa606dd423df7dfb65efe14ab66f5fdebf62ff583                         |                                                              |
| amount            | VARCHAR   | 500000000000000000000000                                           |                                                              |
| fee               | VARCHAR   | 0                                                                  |                                                              |

## 63. Table: TrueFiPool\_event\_Collected\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-09 22:41:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14935063                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc3111369baca5936bb9161802bda0a7f482844a77eacf6717c8d30ac9fd34da2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 247                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa1e72267084192db7387c8cc1328fade470e4149                         | Address of the contract that produced the log                |
| beneficiary       | VARCHAR   | 0x2a5c94f3f00db7f11d53d1cfbd9ae8a2bbc7bbf0                         |                                                              |
| amount            | VARCHAR   | 143750002500000000000000                                           |                                                              |

## 64. Table: TrueFiPool\_event\_CrvOracleChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newOracle         | VARCHAR   |                                                              |             |

## 65. Table: TrueFiPool\_event\_Exited\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-02 11:01:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12159685                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9c499c027175f6dfd6c34e935931db8fd723ea810850ed6754ddb76bdcd698a2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 65                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa1e72267084192db7387c8cc1328fade470e4149                         | Address of the contract that produced the log                |
| staker            | VARCHAR   | 0x32833c97f04979753a2f48affdadcbea5ad41dd0                         |                                                              |
| amount            | VARCHAR   | 155750542480856748405302                                           |                                                              |

## 66. Table: TrueFiPool\_event\_Flushed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-03 22:36:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12564254                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x87102b9416c27b9a6430e9c79fc3662b4692dc070149805c2ab87f2e6fa7693c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 89                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa1e72267084192db7387c8cc1328fade470e4149                         | Address of the contract that produced the log                |
| currencyAmount    | VARCHAR   | 16500000000000000000000000                                         |                                                              |

## 67. Table: TrueFiPool\_event\_FundsManagerChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newManager        | VARCHAR   |                                                              |             |

## 68. Table: TrueFiPool\_event\_Joined\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-01 19:33:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11368564                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbb85803ee6e908b414c9dc0e6a80d9868b3255186bce395357051ca7df5d7bd1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 149                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa1e72267084192db7387c8cc1328fade470e4149                         | Address of the contract that produced the log                |
| staker            | VARCHAR   | 0xb5733959320c7efef22f1462f05f9074ed599d40                         |                                                              |
| deposited         | VARCHAR   | 11492772652872893974410                                            |                                                              |
| minted            | VARCHAR   | 11483669394166642415545                                            |                                                              |

## 69. Table: TrueFiPool\_event\_JoiningFeeChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newFee            | VARCHAR   |                                                              |             |

## 70. Table: TrueFiPool\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-22 06:56:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11306537                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa78f73efd969207c24c5f3f4504916f64884ffd2b20c709c4b0b31a9381ab345 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa1e72267084192db7387c8cc1328fade470e4149                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0xf6e2da7d82ee49f76ce652bc0beb546cbe0ea521                         |                                                              |
| newOwner          | VARCHAR   | 0x16cea306506c387713c70b9c1205fd5ac997e78e                         |                                                              |

## 71. Table: TrueFiPool\_event\_PauseStatusChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-26 18:16:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13102586                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd9e7e520a739aeeb72c01473a3b6beba9be9704a7566b6df4c27fdcf765087b5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 49                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa1e72267084192db7387c8cc1328fade470e4149                         | Address of the contract that produced the log                |
| pauseStatus       | VARCHAR   | true                                                               |                                                              |

## 72. Table: TrueFiPool\_event\_Pulled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-26 01:59:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11331173                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7c1705d8c5c5f32f3d79844729f4272b644722f54cb44b1314fbf8682431acab | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 93                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa1e72267084192db7387c8cc1328fade470e4149                         | Address of the contract that produced the log                |
| yAmount           | VARCHAR   | 500000000000000000                                                 |                                                              |

## 73. Table: TrueFiPool\_event\_Repaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-14 07:30:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13222500                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc9856fa3e5f8b92fce6f9fc19504334a03f54303a0d233c0e0ff73bb643b5efc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 56                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa1e72267084192db7387c8cc1328fade470e4149                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0xa606dd423df7dfb65efe14ab66f5fdebf62ff583                         |                                                              |
| amount            | VARCHAR   | 3555983204447939191034601                                          |                                                              |

## 74. Table: TrueFiPool\_event\_SafuChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-24 21:26:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13090516                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x06d807ef52fdd1d6c454dab45c1256b621ba8de33b6c3d20252cbb5fc8529068 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 72                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa1e72267084192db7387c8cc1328fade470e4149                         | Address of the contract that produced the log                |
| newSafu           | VARCHAR   | 0x1ea63189eb1f4c109b10cf6567f328c826aa6151                         |                                                              |

## 75. Table: TrueFiPool\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-25 18:12:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16906178                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2ad98a6baccca36475380653fddb81e231c86bb6dbad9b51067c3f42c27bc65e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 502                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa1e72267084192db7387c8cc1328fade470e4149                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x23696914ca9737466d8553a2d619948f548ee424                         |                                                              |
| to                | VARCHAR   | 0xe9451296bca9ba0c227abfa539032af01628c630                         |                                                              |
| value             | VARCHAR   | 3148021453745190                                                   |                                                              |

## 76. Table: TrueLender\_call\_distribute\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-05-29 10:24:30+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 12528683                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x2719e69126d9aaf2eff0ff42f1b659c21e9bdd57cdfc5632287a904fdbd6db4b | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 79                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,7                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x16d02dc67eb237c387023339356b25d1d54b0922                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| recipient          | VARCHAR   | 0x36cb763573813990dfae2069c4df4eefba3aec7f                         |                                                                                                                        |
| numerator          | VARCHAR   | 68539667893840601395207                                            |                                                                                                                        |
| denominator        | VARCHAR   | 92125128335578634274545634                                         |                                                                                                                        |

## 77. Table: TrueLender\_call\_fund\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-01-09 12:17:43+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 11620495                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x6379eee377616cf9fe7d67cc90a94e992f00f72422390c72cf9d37503997bc00 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 47                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x16d02dc67eb237c387023339356b25d1d54b0922                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| loanToken          | VARCHAR   | 0x24682b0cef4836ee5539b7eaba0f16b9990e7ab0                         |                                                                                                                        |

## 78. Table: TrueLender\_call\_initialize\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| \_pool             | VARCHAR   |                                                                                                                        |             |
| \_ratingAgency     | VARCHAR   |                                                                                                                        |             |
| \_stakingPool      | VARCHAR   |                                                                                                                        |             |

## 79. Table: TrueLender\_call\_loanIsAttractiveEnough\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| apy                | VARCHAR   |                                                                                                                        |             |

## 80. Table: TrueLender\_call\_loanIsCredible\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| apy                | VARCHAR   |                                                                                                                        |             |
| term               | VARCHAR   |                                                                                                                        |             |
| yesVotes           | VARCHAR   |                                                                                                                        |             |
| noVotes            | VARCHAR   |                                                                                                                        |             |

## 81. Table: TrueLender\_call\_setTermLimits\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-11-18 19:28:14+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 11283806                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xf87ff1e96c25b86ed2c51dab9ff9ae65ee82cb89daa1e783bc8e512901613132 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 139                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x16d02dc67eb237c387023339356b25d1d54b0922                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| min                | VARCHAR   | 60                                                                 |                                                                                                                        |
| max                | VARCHAR   | 3600                                                               |                                                                                                                        |

## 82. Table: TrueLender\_event\_Allowed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-13 05:04:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11644635                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5a4c5e893ff556220da70ff5221f8a572fda3c12f9915692be98d1e5b2e3f8aa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 26                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x16d02dc67eb237c387023339356b25d1d54b0922                         | Address of the contract that produced the log                |
| who               | VARCHAR   | 0xcafd96a3475aa9afcc66bc5f9ff589c74ce6a4bc                         |                                                              |
| status            | VARCHAR   | true                                                               |                                                              |

## 83. Table: TrueLender\_event\_ApyLimitsChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-21 15:10:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11302203                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa361cf59443416775fb4964f1b5bbff1e13044952cc4f82c626f0d668ad5e492 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 151                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x16d02dc67eb237c387023339356b25d1d54b0922                         | Address of the contract that produced the log                |
| minApy            | VARCHAR   | 100000                                                             |                                                              |
| maxApy            | VARCHAR   | 300000                                                             |                                                              |

## 84. Table: TrueLender\_event\_Funded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-26 08:24:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11931736                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x590877dde669b82ebf0244010b202cc4f83463cf8f2cf2f4d3ac59777d19fddb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 216                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x16d02dc67eb237c387023339356b25d1d54b0922                         | Address of the contract that produced the log                |
| loanToken         | VARCHAR   | 0xcf17b60d0c3900433cff5170c62f0a63d01ab3be                         |                                                              |
| amount            | VARCHAR   | 9975000000000000000000000                                          |                                                              |

## 85. Table: TrueLender\_event\_LoansLimitChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-26 06:02:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11729593                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0336354d6e6bd5d0c92e7f40f1b25aa2f668d3d9673c3a34ec686db53dad8811 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 14                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x16d02dc67eb237c387023339356b25d1d54b0922                         | Address of the contract that produced the log                |
| maxLoans          | VARCHAR   | 100                                                                |                                                              |

## 86. Table: TrueLender\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-18 18:46:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11283623                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa0c7ac08fdd7eda3b501b1be472ee8bd939e39739ae7da78d90909364eca2fd7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 43                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x16d02dc67eb237c387023339356b25d1d54b0922                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0xf6e2da7d82ee49f76ce652bc0beb546cbe0ea521                         |                                                              |

## 87. Table: TrueLender\_event\_ParticipationFactorChanged\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2021-01-26 23:26:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 11734346                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x2127da85d956bac3e65456578f03f727dbbb14423e3380e627ad3af701ab4cd8 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 178                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x16d02dc67eb237c387023339356b25d1d54b0922                         | Address of the contract that produced the log                |
| participationFactor | VARCHAR   | 5000                                                               |                                                              |

## 88. Table: TrueLender\_event\_RatingAgencyChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-19 15:40:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11888231                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x47e7c70642ea160e5dba7d3ee551be1a85ad1b590a29216c215932c182328dec | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 26                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x16d02dc67eb237c387023339356b25d1d54b0922                         | Address of the contract that produced the log                |
| newRatingAgency   | VARCHAR   | 0x05461334340568075be35438b221a3a0d261fb6b                         |                                                              |

## 89. Table: TrueLender\_event\_Reclaimed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-06 03:57:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12771623                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8693361bb634987a963c190e178fa81309e44f6e5c6d0fb4d07dbaa66e7f3a56 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 165                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x16d02dc67eb237c387023339356b25d1d54b0922                         | Address of the contract that produced the log                |
| loanToken         | VARCHAR   | 0xa2c6c6622fe3f1ed20ba764639fffd8aed752ee1                         |                                                              |
| amount            | VARCHAR   | 2026598519450662819064246                                          |                                                              |

## 90. Table: TrueLender\_event\_RiskAversionChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-21 04:36:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11299308                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2eb4918cd9bbe2e98e4de65e37e56cec39115f23dbcdc4155f5959b7c1778414 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 275                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x16d02dc67eb237c387023339356b25d1d54b0922                         | Address of the contract that produced the log                |
| riskAversion      | VARCHAR   | 15000                                                              |                                                              |

## 91. Table: TrueLender\_event\_SizeLimitsChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-25 23:37:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11330530                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbbf876407a8846b28d96afe73e2bc056ef860c9e66aa43e33e65b1bbade8fe27 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x16d02dc67eb237c387023339356b25d1d54b0922                         | Address of the contract that produced the log                |
| minSize           | VARCHAR   | 1000000000000000000000000                                          |                                                              |
| maxSize           | VARCHAR   | 10000000000000000000000000                                         |                                                              |

## 92. Table: TrueLender\_event\_StakingPoolChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-19 16:34:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11888463                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x03e75089c5ef3678b1325453809c2e4c6fcc185c56e6ef5ba0c9848c1b06ba21 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 15                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x16d02dc67eb237c387023339356b25d1d54b0922                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0x23696914ca9737466d8553a2d619948f548ee424                         |                                                              |

## 93. Table: TrueLender\_event\_TermLimitsChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-02 04:05:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11774555                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x63232c1b964e20c6f8458d7b70302531825c304349bc4ecd7f53582da5f83e04 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 76                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x16d02dc67eb237c387023339356b25d1d54b0922                         | Address of the contract that produced the log                |
| minTerm           | VARCHAR   | 86400                                                              |                                                              |
| maxTerm           | VARCHAR   | 7776000                                                            |                                                              |

## 94. Table: TrueLender\_event\_VotingPeriodChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-18 19:28:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11283806                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7ae5666b1d79fd6d6796b40cd881c4028396e7f1cc148d1ee16b12f5fa48f56d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 224                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x16d02dc67eb237c387023339356b25d1d54b0922                         | Address of the contract that produced the log                |
| votingPeriod      | VARCHAR   | 60                                                                 |                                                              |
