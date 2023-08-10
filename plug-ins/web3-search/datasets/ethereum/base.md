# base

## 1. Table: BaseIntroduced\_event\_AdminChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousAdmin     | VARCHAR   |                                                              |             |
| newAdmin          | VARCHAR   |                                                              |             |

## 2. Table: BaseIntroduced\_event\_ApprovalForAll\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-27 13:17:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17784643                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x57ba46f4730d685ac059b3ab713553da1eedd0c5ced355a06f8db03fc5e22cf5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 186                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd4307e0acd12cf46fd6cf93bc264f5d5d1598792                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x4b3b5b7acd9490156bc0c49f4d0699dfd127f53b                         |                                                              |
| operator          | VARCHAR   | 0x1e0049783f008a0085193e00003d00cd54003c71                         |                                                              |
| approved          | VARCHAR   | true                                                               |                                                              |

## 3. Table: BaseIntroduced\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-24 01:11:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17546043                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xef3f4976461d800d9dc6cbe90aaaf402b6c39550b018147fc38a35357f2ddb2d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 193                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd4307e0acd12cf46fd6cf93bc264f5d5d1598792                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x07fd387ae14f8ec8fcc89ff1efa60154f40692f4                         |                                                              |
| approved          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| tokenId           | VARCHAR   | 250393                                                             |                                                              |

## 4. Table: BaseIntroduced\_event\_BatchMetadataUpdate\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_fromTokenId     | VARCHAR   |                                                              |             |
| \_toTokenId       | VARCHAR   |                                                              |             |

## 5. Table: BaseIntroduced\_event\_BeaconUpgraded\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| beacon            | VARCHAR   |                                                              |             |

## 6. Table: BaseIntroduced\_event\_FundsReceived\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-08 19:05:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17437530                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x98ea1ea4b71d22237f546b590cc49def01e2ff807c3fd6c9006c3a7f075dac0d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 104                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd4307e0acd12cf46fd6cf93bc264f5d5d1598792                         | Address of the contract that produced the log                |
| source            | VARCHAR   | 0x074a3d1fb090e9a8c05345756f98a8494df79497                         |                                                              |
| amount            | VARCHAR   | 16249461736581000                                                  |                                                              |

## 7. Table: BaseIntroduced\_event\_FundsRecipientChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newAddress        | VARCHAR   |                                                              |             |
| changedBy         | VARCHAR   |                                                              |             |

## 8. Table: BaseIntroduced\_event\_FundsWithdrawn\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| withdrawnBy       | VARCHAR   |                                                              |             |
| withdrawnTo       | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |
| feeRecipient      | VARCHAR   |                                                              |             |
| feeAmount         | VARCHAR   |                                                              |             |

## 9. Table: BaseIntroduced\_event\_MetadataUpdate\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_tokenId         | VARCHAR   |                                                              |             |

## 10. Table: BaseIntroduced\_event\_MintFeePayout\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-02 02:19:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16737874                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x22b4cbe0f57b47112ffde17b814606cea58dc2799bc1da84f25ccd7aefaee775 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 186                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd4307e0acd12cf46fd6cf93bc264f5d5d1598792                         | Address of the contract that produced the log                |
| mintFeeAmount     | VARCHAR   | 777000000000000                                                    |                                                              |
| mintFeeRecipient  | VARCHAR   | 0xd1d1d4e36117ab794ec5d4c78cbd3a8904e691d0                         |                                                              |
| success           | VARCHAR   | true                                                               |                                                              |

## 11. Table: BaseIntroduced\_event\_OpenMintFinalized\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| sender            | VARCHAR   |                                                              |             |
| numberOfMints     | VARCHAR   |                                                              |             |

## 12. Table: BaseIntroduced\_event\_OwnerCanceled\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner     | VARCHAR   |                                                              |             |
| potentialNewOwner | VARCHAR   |                                                              |             |

## 13. Table: BaseIntroduced\_event\_OwnerPending\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner     | VARCHAR   |                                                              |             |
| potentialNewOwner | VARCHAR   |                                                              |             |

## 14. Table: BaseIntroduced\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-23 13:56:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16691530                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdf8c5d18693c841bf96b03dbd2505801bcf99e396f6c556ef19fb966e21ccd1c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 124                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd4307e0acd12cf46fd6cf93bc264f5d5d1598792                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0xaadd9cbfb3e959aeaaf29b586192eabe1eaa156f                         |                                                              |

## 15. Table: BaseIntroduced\_event\_RoleAdminChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| role              | VARCHAR   |                                                              |             |
| previousAdminRole | VARCHAR   |                                                              |             |
| newAdminRole      | VARCHAR   |                                                              |             |

## 16. Table: BaseIntroduced\_event\_RoleGranted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-28 17:52:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16728260                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x70902000761ff9c71cd22dbcd489c9da75da8269b11e5434b3fce414c63888b9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 232                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd4307e0acd12cf46fd6cf93bc264f5d5d1598792                         | Address of the contract that produced the log                |
| role              | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000 |                                                              |
| account           | VARCHAR   | 0x55b5a348fdaeae63c1e433c9898b869cb9a7689b                         |                                                              |
| sender            | VARCHAR   | 0xaadd9cbfb3e959aeaaf29b586192eabe1eaa156f                         |                                                              |

## 17. Table: BaseIntroduced\_event\_RoleRevoked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-23 13:56:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16691530                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdf8c5d18693c841bf96b03dbd2505801bcf99e396f6c556ef19fb966e21ccd1c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 127                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd4307e0acd12cf46fd6cf93bc264f5d5d1598792                         | Address of the contract that produced the log                |
| role              | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000 |                                                              |
| account           | VARCHAR   | 0xf74b146ce44cc162b601dec3be331784db111dc1                         |                                                              |
| sender            | VARCHAR   | 0xf74b146ce44cc162b601dec3be331784db111dc1                         |                                                              |

## 18. Table: BaseIntroduced\_event\_Sale\_history

| Column                | Type      | Example                                                            | Description                                                  |
| --------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp      | TIMESTAMP | 2023-02-28 02:31:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number         | INTEGER   | 16723712                                                           | The block number where this event was emitted                |
| transaction\_hash     | VARCHAR   | 0xb0c86d37c688c716effeb8218808d7da68afd9346a8c014e96012cca36e1dd12 | Hash of the transactions in which this event was emitted     |
| log\_index            | INTEGER   | 228                                                                | Integer of the log index position in the block of this event |
| contract\_address     | VARCHAR   | 0xd4307e0acd12cf46fd6cf93bc264f5d5d1598792                         | Address of the contract that produced the log                |
| to                    | VARCHAR   | 0x3759b20bdf329dd0766f300541fd4f66a4269db6                         |                                                              |
| quantity              | VARCHAR   | 1                                                                  |                                                              |
| pricePerToken         | VARCHAR   | 0                                                                  |                                                              |
| firstPurchasedTokenId | VARCHAR   | 374128                                                             |                                                              |

## 19. Table: BaseIntroduced\_event\_SalesConfigChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-23 13:56:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16691530                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdf8c5d18693c841bf96b03dbd2505801bcf99e396f6c556ef19fb966e21ccd1c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 126                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd4307e0acd12cf46fd6cf93bc264f5d5d1598792                         | Address of the contract that produced the log                |
| changedBy         | VARCHAR   | 0xf74b146ce44cc162b601dec3be331784db111dc1                         |                                                              |

## 20. Table: BaseIntroduced\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-18 07:16:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17284895                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8ba026f5327f73bac16550594438099a2a5fd44755e6ebaf3b067cff12dbeb70 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 243                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd4307e0acd12cf46fd6cf93bc264f5d5d1598792                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x39afc8529ffeffb37ffa2e7315cd3420e19fc362                         |                                                              |
| to                | VARCHAR   | 0xb27ef08b535f68fe3a30943329cc7d88c5e04d8c                         |                                                              |
| tokenId           | VARCHAR   | 221881                                                             |                                                              |

## 21. Table: BaseIntroduced\_event\_UpdatedMetadataRenderer\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| sender            | VARCHAR   |                                                              |             |
| renderer          | VARCHAR   |                                                              |             |

## 22. Table: BaseIntroduced\_event\_Upgraded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-23 13:56:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16691530                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdf8c5d18693c841bf96b03dbd2505801bcf99e396f6c556ef19fb966e21ccd1c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 122                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd4307e0acd12cf46fd6cf93bc264f5d5d1598792                         | Address of the contract that produced the log                |
| implementation    | VARCHAR   | 0x5eb5babcefea846b220c82f222f00df95934f5f0                         |                                                              |

## 23. Table: L2OutputOracle\_event\_OutputProposed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-31 14:57:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17813731                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd08e65bfc402205ba41844d15b0c21f0ca6fbe6c8839afd91c756768e44e7300 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 260                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x56315b90c40730925ec5485cf004d835058518a0                         | Address of the contract that produced the log                |
| outputRoot        | VARCHAR   | 0x504312102c29e99548754b6b902ea30b1a3f525cd20f18486d98e1c4d17158eb |                                                              |
| l2OutputIndex     | VARCHAR   | 1117                                                               |                                                              |
| l2BlockNumber     | VARCHAR   | 2012400                                                            |                                                              |
| l1Timestamp       | VARCHAR   | 1690815431                                                         |                                                              |
