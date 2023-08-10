# enzyme

## 1. Table: FundDeployer\_event\_ComptrollerLibSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-11 23:34:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11636632                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5d3b9e5d4954d78838cc9f071d4dc95264864c1fe5fb541a67fc36d0d9d94f82 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 160                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9134c9975244b46692ad9a7da36dba8734ec6da3                         | Address of the contract that produced the log                |
| comptrollerLib    | VARCHAR   | 0x94f262802806be3646612d0705802710dd5b58df                         |                                                              |

## 2. Table: FundDeployer\_event\_ComptrollerProxyDeployed\_history

| Column                  | Type      | Example                                                                                              | Description                                                  |
| ----------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp        | TIMESTAMP | 2021-09-11 23:08:36+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number           | INTEGER   | 13207317                                                                                             | The block number where this event was emitted                |
| transaction\_hash       | VARCHAR   | 0x82bedb9612898aada6fb7bcc36dc4125667d0dbd95ff10bcd40a9e10382a0b03                                   | Hash of the transactions in which this event was emitted     |
| log\_index              | INTEGER   | 533                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address       | VARCHAR   | 0x7e6d3b1161df9c9c7527f68d651b297d2fdb820b                                                           | Address of the contract that produced the log                |
| creator                 | VARCHAR   | 0x9b55d80af9dd8d23c372915ad55c010799010b4d                                                           |                                                              |
| comptrollerProxy        | VARCHAR   | 0x52d39a652e0a3b57c40aa3934cd381362f61c835                                                           |                                                              |
| denominationAsset       | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                                                           |                                                              |
| sharesActionTimelock    | VARCHAR   | 86400                                                                                                |                                                              |
| feeManagerConfigData    | VARCHAR   | 0x00000000000000000000000000000000000000000000000000000000000000400000000000000000000000000000000000 |                                                              |
| policyManagerConfigData | VARCHAR   | 0x00000000000000000000000000000000000000000000000000000000000000400000000000000000000000000000000000 |                                                              |
| forMigration            | VARCHAR   | false                                                                                                |                                                              |

## 3. Table: FundDeployer\_event\_NewFundCreated\_history

| Column                  | Type      | Example                                                                                              | Description                                                  |
| ----------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp        | TIMESTAMP | 2021-03-28 23:55:04+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number           | INTEGER   | 12130739                                                                                             | The block number where this event was emitted                |
| transaction\_hash       | VARCHAR   | 0xb244849d74890363cec50e0285054e88358e5086cfde8c5d07c2521d6d824942                                   | Hash of the transactions in which this event was emitted     |
| log\_index              | INTEGER   | 37                                                                                                   | Integer of the log index position in the block of this event |
| contract\_address       | VARCHAR   | 0x9134c9975244b46692ad9a7da36dba8734ec6da3                                                           | Address of the contract that produced the log                |
| creator                 | VARCHAR   | 0xa4518ef7250727cd264ad2201fa31f878ba66f5f                                                           |                                                              |
| comptrollerProxy        | VARCHAR   | 0xae2feda62a272ee775a269477e94d37a975111dd                                                           |                                                              |
| vaultProxy              | VARCHAR   | 0x15ed28de4e4f711095b07082c484b3a93313d6bf                                                           |                                                              |
| fundOwner               | VARCHAR   | 0xa4518ef7250727cd264ad2201fa31f878ba66f5f                                                           |                                                              |
| fundName                | VARCHAR   | Spaidshares Interest                                                                                 |                                                              |
| denominationAsset       | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                                                           |                                                              |
| sharesActionTimelock    | VARCHAR   | 1                                                                                                    |                                                              |
| feeManagerConfigData    | VARCHAR   | 0x00000000000000000000000000000000000000000000000000000000000000400000000000000000000000000000000000 |                                                              |
| policyManagerConfigData | VARCHAR   | 0x00000000000000000000000000000000000000000000000000000000000000400000000000000000000000000000000000 |                                                              |

## 4. Table: FundDeployer\_event\_ReleaseStatusSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-07 18:52:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12388901                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5b06784b74464a2ac932565affdc3ca008ff53dc0b55f873d852512c6615a68b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 230                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7e6d3b1161df9c9c7527f68d651b297d2fdb820b                         | Address of the contract that produced the log                |
| prevStatus        | VARCHAR   | 0                                                                  |                                                              |
| nextStatus        | VARCHAR   | 1                                                                  |                                                              |

## 5. Table: FundDeployer\_event\_VaultCallDeregistered\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| contractAddress   | VARCHAR   |                                                              |             |
| selector          | VARCHAR   |                                                              |             |

## 6. Table: FundDeployer\_event\_VaultCallRegistered\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-11 23:23:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11636590                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x46a222e92c2ed80cf21b18d2fb219e4c02ebfe3edbeb3b0154b4d4d29a0fd940 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 161                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9134c9975244b46692ad9a7da36dba8734ec6da3                         | Address of the contract that produced the log                |
| contractAddress   | VARCHAR   | 0x15fd6e554874b9e70f832ed37f231ac5e142362f                         |                                                              |
| selector          | VARCHAR   | 0x447fbc63                                                         |                                                              |

## 7. Table: MelonV1\_Dispatcher\_event\_CurrentFundDeployerSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-09 08:01:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14170674                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3c0425addb74ccbb4f91ee202c99088c067e9eef0892b808b774a08da60ba892 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 72                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc3dc853dd716bd5754f421ef94fdcbac3902ab32                         | Address of the contract that produced the log                |
| prevFundDeployer  | VARCHAR   | 0x7e6d3b1161df9c9c7527f68d651b297d2fdb820b                         |                                                              |
| nextFundDeployer  | VARCHAR   | 0x4f1c53f096533c04d8157efb6bca3eb22ddc6360                         |                                                              |

## 8. Table: MelonV1\_Dispatcher\_event\_MigrationCancelled\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2021-06-16 06:33:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 12643929                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xfcbb2f555228f6ae72a3a5b55c79114bda427dd303e725d76222d10d04126f29 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 396                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0xc3dc853dd716bd5754f421ef94fdcbac3902ab32                         | Address of the contract that produced the log                |
| vaultProxy          | VARCHAR   | 0x182abda9983d2aebed448421581cefc9b21a2c54                         |                                                              |
| prevFundDeployer    | VARCHAR   | 0x9134c9975244b46692ad9a7da36dba8734ec6da3                         |                                                              |
| nextFundDeployer    | VARCHAR   | 0x7e6d3b1161df9c9c7527f68d651b297d2fdb820b                         |                                                              |
| nextVaultAccessor   | VARCHAR   | 0x1ba451b2ae4413b1d15c88901e71e52c3f7d6d72                         |                                                              |
| nextVaultLib        | VARCHAR   | 0x1b3694907ed7459c7b0116e7c6a4b7788288577f                         |                                                              |
| executableTimestamp | VARCHAR   | 1623402619                                                         |                                                              |

## 9. Table: MelonV1\_Dispatcher\_event\_MigrationExecuted\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2022-05-23 09:40:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 14828831                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xcb29523533d83cbbcace06f2b10e5fa832c7e3dbf9b3f55e2275098be9761e6b | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 1216                                                               | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0xc3dc853dd716bd5754f421ef94fdcbac3902ab32                         | Address of the contract that produced the log                |
| vaultProxy          | VARCHAR   | 0xdb99e4e656f3c705d8467be35081dcb2f05370b0                         |                                                              |
| prevFundDeployer    | VARCHAR   | 0x7e6d3b1161df9c9c7527f68d651b297d2fdb820b                         |                                                              |
| nextFundDeployer    | VARCHAR   | 0x4f1c53f096533c04d8157efb6bca3eb22ddc6360                         |                                                              |
| nextVaultAccessor   | VARCHAR   | 0x81303c261031c68f3c123255df76a8c91de3a28f                         |                                                              |
| nextVaultLib        | VARCHAR   | 0x891dee0483ebaa922e274ddd2ebbaa2d33468a38                         |                                                              |
| executableTimestamp | VARCHAR   | 1652993883                                                         |                                                              |

## 10. Table: MelonV1\_Dispatcher\_event\_MigrationInCancelHookFailed\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| failureReturnData | VARCHAR   |                                                              |             |
| vaultProxy        | VARCHAR   |                                                              |             |
| prevFundDeployer  | VARCHAR   |                                                              |             |
| nextFundDeployer  | VARCHAR   |                                                              |             |
| nextVaultAccessor | VARCHAR   |                                                              |             |
| nextVaultLib      | VARCHAR   |                                                              |             |

## 11. Table: MelonV1\_Dispatcher\_event\_MigrationOutHookFailed\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-24 01:11:34+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12494012                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaf0a50416a168cf5079c6e60fc5b081e2326f0d1d662d61c267d5ff049982019                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 138                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc3dc853dd716bd5754f421ef94fdcbac3902ab32                                                           | Address of the contract that produced the log                |
| failureReturnData | VARCHAR   | 0x08c379a0000000000000000000000000000000000000000000000000000000000000002000000000000000000000000000 |                                                              |
| hook              | VARCHAR   | 2                                                                                                    |                                                              |
| vaultProxy        | VARCHAR   | 0x86a8a22e4673e9e0455e790fb0a45b967473ff8f                                                           |                                                              |
| prevFundDeployer  | VARCHAR   | 0x9134c9975244b46692ad9a7da36dba8734ec6da3                                                           |                                                              |
| nextFundDeployer  | VARCHAR   | 0x7e6d3b1161df9c9c7527f68d651b297d2fdb820b                                                           |                                                              |
| nextVaultAccessor | VARCHAR   | 0xa72ce4c37797fe66759324c20cc001452275e311                                                           |                                                              |
| nextVaultLib      | VARCHAR   | 0x1b3694907ed7459c7b0116e7c6a4b7788288577f                                                           |                                                              |

## 12. Table: MelonV1\_Dispatcher\_event\_MigrationSignaled\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2021-07-29 02:48:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 12918193                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x62b5185acfcab0e0b38b31c20c267d0e6a77df3c660925d399dffac9a0c44e3c | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 82                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0xc3dc853dd716bd5754f421ef94fdcbac3902ab32                         | Address of the contract that produced the log                |
| vaultProxy          | VARCHAR   | 0xf874fc9e7fb5e60ca709600a947a4a2a10760272                         |                                                              |
| prevFundDeployer    | VARCHAR   | 0x9134c9975244b46692ad9a7da36dba8734ec6da3                         |                                                              |
| nextFundDeployer    | VARCHAR   | 0x7e6d3b1161df9c9c7527f68d651b297d2fdb820b                         |                                                              |
| nextVaultAccessor   | VARCHAR   | 0x308c951909c16f54db60a6944052731b6e5a916f                         |                                                              |
| nextVaultLib        | VARCHAR   | 0x1b3694907ed7459c7b0116e7c6a4b7788288577f                         |                                                              |
| executableTimestamp | VARCHAR   | 1627699693                                                         |                                                              |

## 13. Table: MelonV1\_Dispatcher\_event\_MigrationTimelockSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-03 14:14:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12562022                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4916a2f92ad4f65e6267474e523b1487153a3c662f60ebef10508c030f1df69c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 71                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc3dc853dd716bd5754f421ef94fdcbac3902ab32                         | Address of the contract that produced the log                |
| prevTimelock      | VARCHAR   | 0                                                                  |                                                              |
| nextTimelock      | VARCHAR   | 172800                                                             |                                                              |

## 14. Table: MelonV1\_Dispatcher\_event\_NominatedOwnerRemoved\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| nominatedOwner    | VARCHAR   |                                                              |             |

## 15. Table: MelonV1\_Dispatcher\_event\_NominatedOwnerSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-12 11:47:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11639906                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7df1299e3d4bb3a5b75aa62577f750f057fbcd7106810d089656b73f0ef18f1f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 209                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc3dc853dd716bd5754f421ef94fdcbac3902ab32                         | Address of the contract that produced the log                |
| nominatedOwner    | VARCHAR   | 0x4456afcac5db685ff8be5efec23ef1547b20b14a                         |                                                              |

## 16. Table: MelonV1\_Dispatcher\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-16 23:44:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11870867                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x019067d98d0c7042ac85345537b2b741929a7c71f3e1a2af3f02a6f3ca92e96d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 212                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc3dc853dd716bd5754f421ef94fdcbac3902ab32                         | Address of the contract that produced the log                |
| prevOwner         | VARCHAR   | 0x4456afcac5db685ff8be5efec23ef1547b20b14a                         |                                                              |
| nextOwner         | VARCHAR   | 0xb270fe91e8e4b80452fbf1b4704208792a350f53                         |                                                              |

## 17. Table: MelonV1\_Dispatcher\_event\_SharesTokenSymbolSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_nextSymbol      | VARCHAR   |                                                              |             |

## 18. Table: MelonV1\_Dispatcher\_event\_VaultProxyDeployed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-29 21:59:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11753343                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc05e487286eeb4c61518eb3e87f9893aa347cb674b890d43e70efa3b712b0c25 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 54                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc3dc853dd716bd5754f421ef94fdcbac3902ab32                         | Address of the contract that produced the log                |
| fundDeployer      | VARCHAR   | 0x9134c9975244b46692ad9a7da36dba8734ec6da3                         |                                                              |
| owner             | VARCHAR   | 0xf90bd2a4cc3c5814a9c4ad8809ecef42f7a7c659                         |                                                              |
| vaultProxy        | VARCHAR   | 0x6feab7e551fd6858cd702f121918c58785cbb8d6                         |                                                              |
| vaultLib          | VARCHAR   | 0xac3fe07f51c51153e181be892e4e37326eea13da                         |                                                              |
| vaultAccessor     | VARCHAR   | 0xc0e6ea4b4634a52859c9afd1ebcd14f08abd4659                         |                                                              |
| fundName          | VARCHAR   | NFT FUND                                                           |                                                              |
