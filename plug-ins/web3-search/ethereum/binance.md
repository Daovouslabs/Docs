# binance

## 1. Table: BUSDImplementation\_event\_AddressFrozen\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-06 02:10:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9815715                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x163de4667da540e36e94182ea724220c1441f4f2cd855da184aacfa99cca01ce | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 25                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4fabb145d64652a948d72533023f6e7a623c7c53                         | Address of the contract that produced the log                |
| addr              | VARCHAR   | 0x5c27cc68fe01a3994807b60a6c81d8ba638b4ba1                         |                                                              |

## 2. Table: BUSDImplementation\_event\_AddressUnfrozen\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| addr              | VARCHAR   |                                                              |             |

## 3. Table: BUSDImplementation\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-27 20:08:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11342570                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc202fedeba19c5ec450c878b2a6e95710dbf2cbaf72667bad2f56e8650b832c8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 248                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4fabb145d64652a948d72533023f6e7a623c7c53                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xcf8d47b55ecb6d5caaa03353a71af84f1cdccae4                         |                                                              |
| spender           | VARCHAR   | 0x0a87c89b5007ff406ab5280abdd80fc495ec238e                         |                                                              |
| value             | VARCHAR   | 270000000000000000000                                              |                                                              |

## 4. Table: BUSDImplementation\_event\_AssetProtectionRoleSet\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2020-04-06 02:09:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 9815712                                                            | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0x3be5062b6059e5cb6c50cf5551def4ca98a5b410363ce13ed6f6b82d9708b3ea | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 60                                                                 | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0x4fabb145d64652a948d72533023f6e7a623c7c53                         | Address of the contract that produced the log                |
| oldAssetProtectionRole | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newAssetProtectionRole | VARCHAR   | 0xb87cec7baa2ce4a055f8563e9cc5a210cedc329f                         |                                                              |

## 5. Table: BUSDImplementation\_event\_BetaDelegateUnwhitelisted\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldDelegate       | VARCHAR   |                                                              |             |

## 6. Table: BUSDImplementation\_event\_BetaDelegateWhitelisted\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newDelegate       | VARCHAR   |                                                              |             |

## 7. Table: BUSDImplementation\_event\_BetaDelegateWhitelisterSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldWhitelister    | VARCHAR   |                                                              |             |
| newWhitelister    | VARCHAR   |                                                              |             |

## 8. Table: BUSDImplementation\_event\_BetaDelegatedTransfer\_history

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

## 9. Table: BUSDImplementation\_event\_FrozenAddressWiped\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| addr              | VARCHAR   |                                                              |             |

## 10. Table: BUSDImplementation\_event\_OwnershipTransferDisregarded\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldProposedOwner  | VARCHAR   |                                                              |             |

## 11. Table: BUSDImplementation\_event\_OwnershipTransferProposed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-09-06 20:39:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8498603                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x960de5c6d013c15dbdc7bfa94e078f5d7220cbbce4ae1dc47e2b587397590b66 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 45                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4fabb145d64652a948d72533023f6e7a623c7c53                         | Address of the contract that produced the log                |
| currentOwner      | VARCHAR   | 0x1074253202528777561f83817d413e91bfa671d4                         |                                                              |
| proposedOwner     | VARCHAR   | 0xb87cec7baa2ce4a055f8563e9cc5a210cedc329f                         |                                                              |

## 12. Table: BUSDImplementation\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-04 17:49:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12369214                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x003867e1df858744659e9e23844000fdfae2c54a8173023b7ffc9cb6b96b0ef1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 338                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4fabb145d64652a948d72533023f6e7a623c7c53                         | Address of the contract that produced the log                |
| oldOwner          | VARCHAR   | 0xb87cec7baa2ce4a055f8563e9cc5a210cedc329f                         |                                                              |
| newOwner          | VARCHAR   | 0x0644bd0248d5f89e4f6e845a91d15c23591e5d33                         |                                                              |

## 13. Table: BUSDImplementation\_event\_Pause\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 14. Table: BUSDImplementation\_event\_SupplyControllerSet\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2019-09-06 01:42:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 8493635                                                            | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x7be79e80d33f5061e0421721f407a38a523eee6c93ca17af260798c6fc8bf7b1 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 54                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x4fabb145d64652a948d72533023f6e7a623c7c53                         | Address of the contract that produced the log                |
| oldSupplyController | VARCHAR   | 0x1074253202528777561f83817d413e91bfa671d4                         |                                                              |
| newSupplyController | VARCHAR   | 0x5195427ca88df768c298721da791b93ad11eca65                         |                                                              |

## 15. Table: BUSDImplementation\_event\_SupplyDecreased\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-11 16:40:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14755947                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x14cdab07747b5d73fb1f691d7b4167c2be8ff816948e2cf810081182c43974ba | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 12                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4fabb145d64652a948d72533023f6e7a623c7c53                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xe25a329d385f77df5d4ed56265babe2b99a5436e                         |                                                              |
| value             | VARCHAR   | 11361453470000000000000000                                         |                                                              |

## 16. Table: BUSDImplementation\_event\_SupplyIncreased\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-11 08:51:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14753894                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd50f93d859e1ccf2fab3ca194a98c0b15dd640ee50828087aa66127539dea27f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 61                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4fabb145d64652a948d72533023f6e7a623c7c53                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0xe25a329d385f77df5d4ed56265babe2b99a5436e                         |                                                              |
| value             | VARCHAR   | 39244896600000000000000000                                         |                                                              |

## 17. Table: BUSDImplementation\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-01 02:00:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17382857                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4f05df8cbc99982d3c1415269bed96804273f8c40e9e5d49a8470843263147d1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 328                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4fabb145d64652a948d72533023f6e7a623c7c53                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x46059c9af2903c08a8fb7f96cda852ec99a91a02                         |                                                              |
| to                | VARCHAR   | 0x28c6c06298d514db089934071355e5743bf21d60                         |                                                              |
| value             | VARCHAR   | 1600000000000000000000                                             |                                                              |

## 18. Table: BUSDImplementation\_event\_Unpause\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
