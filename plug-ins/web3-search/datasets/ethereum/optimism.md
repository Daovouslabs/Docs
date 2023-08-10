# optimism

## 1. Table: AddressManager\_event\_AddressSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-24 01:46:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12098716                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2562042fa485924c7d8c7db4a866ea211a5320764a5bbac8577757f6ddf28d04 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 179                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1de8cfd4c1a486200286073ae91de6e8099519f1                         | Address of the contract that produced the log                |
| \_name            | VARCHAR   | OVM\_StateCommitmentChain                                          |                                                              |
| \_newAddress      | VARCHAR   | 0x901a629a72a5daf200fc359657f070b34bbfdd18                         |                                                              |

## 2. Table: AddressManager\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-14 01:10:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11650206                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6e0829acc11ce3d57dc89282b3acc6858b17e0ba3b000e8f631a11ddc352d67d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 243                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1de8cfd4c1a486200286073ae91de6e8099519f1                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0xc6dbc2dc7649c7d4292d955da08a7c21a21e1528                         |                                                              |

## 3. Table: OVM\_CanonicalTransactionChain\_event\_QueueBatchAppended\_history

| Column               | Type      | Example                                                      | Description |
| -------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp     | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number        | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash    | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index           | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address    | VARCHAR   | Address of the contract that produced the log                |             |
| \_startingQueueIndex | VARCHAR   |                                                              |             |
| \_numQueueElements   | VARCHAR   |                                                              |             |
| \_totalElements      | VARCHAR   |                                                              |             |

## 4. Table: OVM\_CanonicalTransactionChain\_event\_SequencerBatchAppended\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2022-03-07 09:09:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 14338817                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x0ab7709c640ba17dd33e499f90b04e861c82269c5af7cb708eddaf9bb4c8aeff | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 349                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x5e4e65926ba27467555eb562121fac00d24e9dd2                         | Address of the contract that produced the log                |
| \_startingQueueIndex | VARCHAR   | 54350                                                              |                                                              |
| \_numQueueElements   | VARCHAR   | 0                                                                  |                                                              |
| \_totalElements      | VARCHAR   | 4198250                                                            |                                                              |

## 5. Table: OVM\_CanonicalTransactionChain\_event\_TransactionBatchAppended\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2021-04-09 20:57:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 12207949                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x200946512b6623780039c42f9ae740147567fea64ebf4b2998b5ef7a2a7be260 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 57                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0xed2701f7135eab0d7ca02e6ab634ad6cbe159ffb                         | Address of the contract that produced the log                |
| \_batchIndex        | VARCHAR   | 964                                                                |                                                              |
| \_batchRoot         | VARCHAR   | 0xc28778c9751d29524750bfe2f3b8adad5a07c7ba2368453a25a6559a16612db6 |                                                              |
| \_batchSize         | VARCHAR   | 1                                                                  |                                                              |
| \_prevTotalElements | VARCHAR   | 126002                                                             |                                                              |
| \_extraData         | VARCHAR   | 0x                                                                 |                                                              |

## 6. Table: OVM\_CanonicalTransactionChain\_event\_TransactionEnqueued\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-27 00:04:35+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11734518                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfdea9e8ec28aade6a7f5d454c782b525b2871dae0f17d5e869d77ed5e5590877                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 303                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xed2701f7135eab0d7ca02e6ab634ad6cbe159ffb                                                           | Address of the contract that produced the log                |
| \_l1TxOrigin      | VARCHAR   | 0xfbe93ba0a2df92a8e8d40ce00accf9248a6fc812                                                           |                                                              |
| \_target          | VARCHAR   | 0x4200000000000000000000000000000000000007                                                           |                                                              |
| \_gasLimit        | VARCHAR   | 3000000                                                                                              |                                                              |
| \_data            | VARCHAR   | 0xcbd4ece90000000000000000000000004d7186818dabfe88bd80421656bbd07dffc979cc00000000000000000000000004 |                                                              |
| \_queueIndex      | VARCHAR   | 2091                                                                                                 |                                                              |
| \_timestamp       | VARCHAR   | 1611705875                                                                                           |                                                              |

## 7. Table: OVM\_FraudVerifier\_event\_FraudProofFinalized\_history

| Column              | Type      | Example                                                      | Description |
| ------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp    | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number       | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash   | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index          | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address   | VARCHAR   | Address of the contract that produced the log                |             |
| \_preStateRoot      | VARCHAR   |                                                              |             |
| \_preStateRootIndex | VARCHAR   |                                                              |             |
| \_transactionHash   | VARCHAR   |                                                              |             |
| \_who               | VARCHAR   |                                                              |             |

## 8. Table: OVM\_FraudVerifier\_event\_FraudProofInitialized\_history

| Column              | Type      | Example                                                      | Description |
| ------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp    | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number       | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash   | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index          | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address   | VARCHAR   | Address of the contract that produced the log                |             |
| \_preStateRoot      | VARCHAR   |                                                              |             |
| \_preStateRootIndex | VARCHAR   |                                                              |             |
| \_transactionHash   | VARCHAR   |                                                              |             |
| \_who               | VARCHAR   |                                                              |             |

## 9. Table: OVM\_L1CrossDomainMessenger\_event\_RelayedMessage\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| msgHash           | VARCHAR   |                                                              |             |

## 10. Table: OVM\_L1CrossDomainMessenger\_event\_SentMessage\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| message           | VARCHAR   |                                                              |             |

## 11. Table: OVM\_L1ETHGateway\_event\_DepositInitiated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-24 00:05:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12299599                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfe101f639b5ff000755c8adc227a803c7d9288efc9086f6f94ad3e9e1974a0c0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 170                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf20c38fcddf0c790319fd7431d17ea0c2bc9959c                         | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0xb7a23cc3e8c61f4aaef5f6a17173a29fbf2da628                         |                                                              |
| \_to              | VARCHAR   | 0xb7a23cc3e8c61f4aaef5f6a17173a29fbf2da628                         |                                                              |
| \_amount          | VARCHAR   | 50000000000000000                                                  |                                                              |

## 12. Table: OVM\_L1ETHGateway\_event\_WithdrawalFinalized\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_to              | VARCHAR   |                                                              |             |
| \_amount          | VARCHAR   |                                                              |             |

## 13. Table: OVM\_StateCommitmentChain\_event\_StateBatchAppended\_history

| Column              | Type      | Example                                                                                              | Description                                                  |
| ------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2021-01-15 07:41:02+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 11658381                                                                                             | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x2a4d6f119b0b014bbbe32955224dfe26fe1fdc1a5f24df7b1c637b387a97c20f                                   | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 239                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x901a629a72a5daf200fc359657f070b34bbfdd18                                                           | Address of the contract that produced the log                |
| \_batchIndex        | VARCHAR   | 6                                                                                                    |                                                              |
| \_batchRoot         | VARCHAR   | 0x098c0d69c9c30a7eddcf49f56dacbd3980a7180251199bf1accb82ede3f84b66                                   |                                                              |
| \_batchSize         | VARCHAR   | 1                                                                                                    |                                                              |
| \_prevTotalElements | VARCHAR   | 103                                                                                                  |                                                              |
| \_extraData         | VARCHAR   | 0x000000000000000000000000000000000000000000000000000000006001470e000000000000000000000000e6d4d6d822 |                                                              |

## 14. Table: OVM\_StateCommitmentChain\_event\_StateBatchDeleted\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_batchIndex      | VARCHAR   |                                                              |             |
| \_batchRoot       | VARCHAR   |                                                              |             |

## 15. Table: SynthetixBridgeToOptimism\_event\_BridgeMigrated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-11 00:10:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12409822                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x200d75d3c4981edbc09941f6f2f20cb4c99a5a42ccee15acd9b4e36c5f596d65 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 53                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x045e507925d2e05d114534d0810a1abd94aca8d6                         | Address of the contract that produced the log                |
| oldBridge         | VARCHAR   | 0x045e507925d2e05d114534d0810a1abd94aca8d6                         |                                                              |
| newBridge         | VARCHAR   | 0x5fd79d46eba7f351fe49bff9e87cdea6c821ef9f                         |                                                              |
| amount            | VARCHAR   | 5390673983819021813567608                                          |                                                              |

## 16. Table: SynthetixBridgeToOptimism\_event\_CacheUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-15 06:10:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11657950                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcfd4103d09d5402a0ee262cbd83218ae53ecc09a3b701b4d0ba524ce87a3c624 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 70                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x045e507925d2e05d114534d0810a1abd94aca8d6                         | Address of the contract that produced the log                |
| name              | VARCHAR   | 0x52657761726473446973747269627574696f6e00000000000000000000000000 |                                                              |
| destination       | VARCHAR   | 0x29c295b046a73cde593f21f63091b072d407e3f2                         |                                                              |

## 17. Table: SynthetixBridgeToOptimism\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-04 21:50:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11792341                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcaba4ababdcc21316098e7fb28a2e872f0aa587e5d8b2d283951bf8d6f6ab410 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 239                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x045e507925d2e05d114534d0810a1abd94aca8d6                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x75f03bcf0e56b7de72ed26585caee949f0d5bf1a                         |                                                              |
| amount            | VARCHAR   | 1306845396580171537336                                             |                                                              |

## 18. Table: SynthetixBridgeToOptimism\_event\_ExportedVestingEntries\_history

| Column                 | Type      | Example                                                                                              | Description                                                  |
| ---------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2021-02-06 06:19:44+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 11801111                                                                                             | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0x376d8f800e8ff9561df90ed685568bbb219a80db1a444f34baf859634469339b                                   | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 148                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0x045e507925d2e05d114534d0810a1abd94aca8d6                                                           | Address of the contract that produced the log                |
| account                | VARCHAR   | 0x170ce88506ee01d6aebb6ee267c550df7a6d4320                                                           |                                                              |
| escrowedAccountBalance | VARCHAR   | 3658401768161797584598                                                                               |                                                              |
| vestingEntries         | VARCHAR   | 1620235254,239159016801780761643,1619619218,230473301887714416115,1619080190,250051809067354803842,1 |                                                              |

## 19. Table: SynthetixBridgeToOptimism\_event\_OwnerChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-14 23:50:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11656238                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8f2538b27584286121e27803d5193a6c38e80ae954e9459b128142cba01bcbcd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 26                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x045e507925d2e05d114534d0810a1abd94aca8d6                         | Address of the contract that produced the log                |
| oldOwner          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0xde910777c787903f78c89e7a0bf7f4c435cbb1fe                         |                                                              |

## 20. Table: SynthetixBridgeToOptimism\_event\_OwnerNominated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-15 00:06:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11656313                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6b147020e11b01c2df0cade784c49807ffa7a4179fe6c7736e6ff9c7246bae3b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 337                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x045e507925d2e05d114534d0810a1abd94aca8d6                         | Address of the contract that produced the log                |
| newOwner          | VARCHAR   | 0xeb3107117fead7de89cd14d463d340a2e6917769                         |                                                              |

## 21. Table: SynthetixBridgeToOptimism\_event\_RewardDeposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-11 23:21:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11838244                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcf8adc5934b1363d59b7605e9ef17b44ffc28148d176b27291ee22b9f3b481dd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 169                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x045e507925d2e05d114534d0810a1abd94aca8d6                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xde910777c787903f78c89e7a0bf7f4c435cbb1fe                         |                                                              |
| amount            | VARCHAR   | 25000000000000000000000                                            |                                                              |

## 22. Table: SynthetixBridgeToOptimism\_event\_WithdrawalCompleted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-29 04:10:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11748573                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xca7e80eed2431c8690ac76db2479b05b9b93ecb089e35f56aaaeb9591df24536 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 280                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x045e507925d2e05d114534d0810a1abd94aca8d6                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x00fae6d94585235c7aa8d1972b6f9ce0051849aa                         |                                                              |
| amount            | VARCHAR   | 80011585111206375949                                               |                                                              |
