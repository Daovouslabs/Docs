# paypal

## 1. Table: PYUSDImplementation\_event\_AddressFrozen\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-03 20:11:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16550563                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8804c3ceb1f78c19ebb37e689851a670d87dd807ded1e79294fff5d937fecad0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 138                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6c3ea9036406852006290770bedfcaba0e23a0e8                         | Address of the contract that produced the log                |
| addr              | VARCHAR   | 0x8c760147004df4027dc792cf2cb8a4fd9855010c                         |                                                              |

## 2. Table: PYUSDImplementation\_event\_AddressUnfrozen\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-23 15:52:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16891245                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x015243c255b4af5cd5ce749792d5e26e54a04cf87f1d6c49560ffbd1828b6556 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 26                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6c3ea9036406852006290770bedfcaba0e23a0e8                         | Address of the contract that produced the log                |
| addr              | VARCHAR   | 0x8c760147004df4027dc792cf2cb8a4fd9855010c                         |                                                              |

## 3. Table: PYUSDImplementation\_event\_Approval\_history

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

## 4. Table: PYUSDImplementation\_event\_AssetProtectionRoleSet\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2022-11-08 01:48:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 15922126                                                           | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0xcdbc5de8965a8472a31d7e7faa8cf32352f745dee12cdc06a1307795912e1317 | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 47                                                                 | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0x6c3ea9036406852006290770bedfcaba0e23a0e8                         | Address of the contract that produced the log                |
| oldAssetProtectionRole | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newAssetProtectionRole | VARCHAR   | 0x0644bd0248d5f89e4f6e845a91d15c23591e5d33                         |                                                              |

## 5. Table: PYUSDImplementation\_event\_BetaDelegateUnwhitelisted\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldDelegate       | VARCHAR   |                                                              |             |

## 6. Table: PYUSDImplementation\_event\_BetaDelegateWhitelisted\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newDelegate       | VARCHAR   |                                                              |             |

## 7. Table: PYUSDImplementation\_event\_BetaDelegateWhitelisterSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldWhitelister    | VARCHAR   |                                                              |             |
| newWhitelister    | VARCHAR   |                                                              |             |

## 8. Table: PYUSDImplementation\_event\_BetaDelegatedTransfer\_history

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
| seq               | VARCHAR   |                                                              |             |
| fee               | VARCHAR   |                                                              |             |

## 9. Table: PYUSDImplementation\_event\_FrozenAddressWiped\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| addr              | VARCHAR   |                                                              |             |

## 10. Table: PYUSDImplementation\_event\_OwnershipTransferDisregarded\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldProposedOwner  | VARCHAR   |                                                              |             |

## 11. Table: PYUSDImplementation\_event\_OwnershipTransferProposed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-08 01:26:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15922017                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x99d72ebc4a714445bfce4677a09f11c2afc020bbf89c8355e233709288519d9e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6c3ea9036406852006290770bedfcaba0e23a0e8                         | Address of the contract that produced the log                |
| currentOwner      | VARCHAR   | 0x3b210c2a0cfcf237a48675b70626961be3e435db                         |                                                              |
| proposedOwner     | VARCHAR   | 0x0644bd0248d5f89e4f6e845a91d15c23591e5d33                         |                                                              |

## 12. Table: PYUSDImplementation\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-08 01:36:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15922068                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x40d453e2617705abf7644d6f0adbbd8de757c2f87b187b4abba7806009481fe2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6c3ea9036406852006290770bedfcaba0e23a0e8                         | Address of the contract that produced the log                |
| oldOwner          | VARCHAR   | 0x3b210c2a0cfcf237a48675b70626961be3e435db                         |                                                              |
| newOwner          | VARCHAR   | 0x0644bd0248d5f89e4f6e845a91d15c23591e5d33                         |                                                              |

## 13. Table: PYUSDImplementation\_event\_Pause\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 14. Table: PYUSDImplementation\_event\_SupplyControllerSet\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2022-11-08 01:25:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 15922012                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x6bc22250e7fbfbfc71977da778cf3081712b3fa65222dc08f424d7b9fb877b6c | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 89                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x6c3ea9036406852006290770bedfcaba0e23a0e8                         | Address of the contract that produced the log                |
| oldSupplyController | VARCHAR   | 0x3b210c2a0cfcf237a48675b70626961be3e435db                         |                                                              |
| newSupplyController | VARCHAR   | 0xe25a329d385f77df5d4ed56265babe2b99a5436e                         |                                                              |

## 15. Table: PYUSDImplementation\_event\_SupplyDecreased\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-03 14:37:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17835106                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1f83a3df01acf92ad32c6459f445dc48064aaaf1aa8079a418888fc3b9b84f35 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 50                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6c3ea9036406852006290770bedfcaba0e23a0e8                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xe25a329d385f77df5d4ed56265babe2b99a5436e                         |                                                              |
| value             | VARCHAR   | 1000000                                                            |                                                              |

## 16. Table: PYUSDImplementation\_event\_SupplyIncreased\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-24 14:30:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16477278                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa3bf4a8fc8a68d4eebcf84e649bf42e95ac34906e48ebaf597daf0fb794d7701 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 237                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6c3ea9036406852006290770bedfcaba0e23a0e8                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0xe25a329d385f77df5d4ed56265babe2b99a5436e                         |                                                              |
| value             | VARCHAR   | 1000000                                                            |                                                              |

## 17. Table: PYUSDImplementation\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-29 17:11:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17586360                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2d20e90c7b661d703b5258ff7151e340f56c01a7ca1bca33657dcf7d6e4545eb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 90                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6c3ea9036406852006290770bedfcaba0e23a0e8                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x2bcb6bc69991802124f04a1114ee487ff3fad197                         |                                                              |
| to                | VARCHAR   | 0xe25a329d385f77df5d4ed56265babe2b99a5436e                         |                                                              |
| value             | VARCHAR   | 10000000                                                           |                                                              |

## 18. Table: PYUSDImplementation\_event\_Unpause\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
