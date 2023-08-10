# nftx

## 1. Table: NFTXVaultFactoryUpgradeable\_event\_DisableVaultFees\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-11 19:01:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14756612                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x664034d6a6ffb7ec9acef5f76daae36e68ba88122c5bcb590804306b2da76820 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 53                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbe86f647b167567525ccaafcd6f881f1ee558216                         | Address of the contract that produced the log                |
| vaultId           | VARCHAR   | 7                                                                  |                                                              |

## 2. Table: NFTXVaultFactoryUpgradeable\_event\_FeeExclusion\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-24 02:26:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14065641                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9a834fed1217404a0d7de9d4f246eea1f1fef9cbee4a2c8afd922271a78fd228 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 125                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbe86f647b167567525ccaafcd6f881f1ee558216                         | Address of the contract that produced the log                |
| feeExcluded       | VARCHAR   | 0x58c1ff9bba25f14cf23ea3c5b408da234a456d04                         |                                                              |
| excluded          | VARCHAR   | true                                                               |                                                              |

## 3. Table: NFTXVaultFactoryUpgradeable\_event\_NewEligibilityManager\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-21 05:42:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12675827                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x22877631ae26323e7b01da7d7e79d1023fe763c69b1cbb16651cf3e1680f03b9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 67                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbe86f647b167567525ccaafcd6f881f1ee558216                         | Address of the contract that produced the log                |
| oldEligManager    | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newEligManager    | VARCHAR   | 0x4086e98cce041d286112d021612fd894cfed94d5                         |                                                              |

## 4. Table: NFTXVaultFactoryUpgradeable\_event\_NewFeeDistributor\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-30 05:53:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13516737                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9b0e1d55e4af182057e12a95f48ad01ea8b5e3a7226dcada69bbe379af308743 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 210                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbe86f647b167567525ccaafcd6f881f1ee558216                         | Address of the contract that produced the log                |
| oldDistributor    | VARCHAR   | 0x7ae9d7ee8489cad7afc84111b8b185ee594ae090                         |                                                              |
| newDistributor    | VARCHAR   | 0xfd8a76dc204e461db5da4f38687adc9cc5ae4a86                         |                                                              |

## 5. Table: NFTXVaultFactoryUpgradeable\_event\_NewVault\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-29 18:48:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16292305                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x84ee3505689a26681529091fe49cb5aa18db83af5628305d7228aafeb72215b4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 156                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbe86f647b167567525ccaafcd6f881f1ee558216                         | Address of the contract that produced the log                |
| vaultId           | VARCHAR   | 761                                                                |                                                              |
| vaultAddress      | VARCHAR   | 0xfb50691f38d9897bf1dcfb6ccf65e95daaf4dc52                         |                                                              |
| assetAddress      | VARCHAR   | 0x239adeeed414d163214d9b8a563c862dcf2206d0                         |                                                              |

## 6. Table: NFTXVaultFactoryUpgradeable\_event\_NewZapContract\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-13 09:48:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12818085                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x530fc68c3c10773f1f31dc4977d59dedfd66be39ede1dec7a272f9cf2c1f43c2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 132                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbe86f647b167567525ccaafcd6f881f1ee558216                         | Address of the contract that produced the log                |
| oldZap            | VARCHAR   | 0x0d74b761eab5cc7cc0e4e625a2e2b8251a4915c6                         |                                                              |
| newZap            | VARCHAR   | 0x0d74b761eab5cc7cc0e4e625a2e2b8251a4915c6                         |                                                              |

## 7. Table: NFTXVaultFactoryUpgradeable\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-09 08:32:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15709365                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd06f42a6589aab6f0653c2a40d1bf029029f941ab5d3a9f0617807c1e30c52ce | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbe86f647b167567525ccaafcd6f881f1ee558216                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x40d73df4f99bae688ce3c23a01022224fe16c7b2                         |                                                              |
| newOwner          | VARCHAR   | 0xaa29881aac939a025a3ab58024d7dd46200fb93d                         |                                                              |

## 8. Table: NFTXVaultFactoryUpgradeable\_event\_SetIsGuardian\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-21 05:44:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12675834                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb47f883d41e04964ca055bed9bf0c9097c1f9368deba78f153fe3e167a108569 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 33                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbe86f647b167567525ccaafcd6f881f1ee558216                         | Address of the contract that produced the log                |
| addr              | VARCHAR   | 0x3fce5449c7449983e263227c5aaeacb4a80b87c9                         |                                                              |
| isGuardian        | VARCHAR   | true                                                               |                                                              |

## 9. Table: NFTXVaultFactoryUpgradeable\_event\_SetPaused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-13 19:05:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15528612                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdcd38b866b3952c44739bd6633fe8441be0f02db27e3a25fab1c33f1a2f15f5d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 294                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbe86f647b167567525ccaafcd6f881f1ee558216                         | Address of the contract that produced the log                |
| lockId            | VARCHAR   | 1                                                                  |                                                              |
| paused            | VARCHAR   | true                                                               |                                                              |

## 10. Table: NFTXVaultFactoryUpgradeable\_event\_UpdateFactoryFees\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-08 21:55:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14167961                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7e5f38301a4b224c84cb233e4c8c26879f4cd415a2b7aeff6605fe9bdaad9fcd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 301                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbe86f647b167567525ccaafcd6f881f1ee558216                         | Address of the contract that produced the log                |
| mintFee           | VARCHAR   | 100000000000000000                                                 |                                                              |
| randomRedeemFee   | VARCHAR   | 40000000000000000                                                  |                                                              |
| targetRedeemFee   | VARCHAR   | 60000000000000000                                                  |                                                              |
| randomSwapFee     | VARCHAR   | 40000000000000000                                                  |                                                              |
| targetSwapFee     | VARCHAR   | 60000000000000000                                                  |                                                              |

## 11. Table: NFTXVaultFactoryUpgradeable\_event\_UpdateVaultFees\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-29 01:10:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17581605                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x769956c3d37f774d79f2e94bbe831061a1f2c689abe630990b7490a8f9b03319 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 428                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbe86f647b167567525ccaafcd6f881f1ee558216                         | Address of the contract that produced the log                |
| vaultId           | VARCHAR   | 821                                                                |                                                              |
| mintFee           | VARCHAR   | 50000000000000000                                                  |                                                              |
| randomRedeemFee   | VARCHAR   | 20000000000000000                                                  |                                                              |
| targetRedeemFee   | VARCHAR   | 30000000000000000                                                  |                                                              |
| randomSwapFee     | VARCHAR   | 20000000000000000                                                  |                                                              |
| targetSwapFee     | VARCHAR   | 50000000000000000                                                  |                                                              |

## 12. Table: NFTXVaultFactoryUpgradeable\_event\_Upgraded\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2022-06-10 16:33:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 14939479                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xd36d446a1a0056c7aae4436ff604a75ad2bf50e0a0a1d7085b476ed33532af9b | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 433                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0xbe86f647b167567525ccaafcd6f881f1ee558216                         | Address of the contract that produced the log                |
| childImplementation | VARCHAR   | 0xe0fbc366b704d0fcbcd752bfdded8382e93700b9                         |                                                              |
