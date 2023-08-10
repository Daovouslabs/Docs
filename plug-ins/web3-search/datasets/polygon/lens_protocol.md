# lens\_protocol

## 1. Table: LensHub\_event\_ApprovalForAll\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-08 19:11:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 35366017                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x18b29815df470f81d9873b4bc5c53dbce36c78566b5c88df636ded6244662883 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 455                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdb46d1dc155634fbc732f92e853b10b288ad5a1d                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xf66bfb02d1b0ca67c815d4a5759b6c8a49b5bdae                         |                                                              |
| operator          | VARCHAR   | 0x059927a006213dc82fe279981feec986274f21d6                         |                                                              |
| approved          | VARCHAR   | true                                                               |                                                              |

## 2. Table: LensHub\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-04 06:37:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 38890862                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa29ccd78ec605237bf69e30b3b144ddd3c7a38bf7e990bfc11aa59aa310b7ab3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 257                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdb46d1dc155634fbc732f92e853b10b288ad5a1d                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x997c4e92cce5ab05f90cf7fa7550267ae001f06b                         |                                                              |
| approved          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| tokenId           | VARCHAR   | 73863                                                              |                                                              |

## 3. Table: LensHub\_event\_BaseInitialized\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-16 10:00:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 28384641                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xca69b18b7e2daf4695c6d614e263d6aa9bdee44bee91bee7e0e6e5e5e4262fca | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 519                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdb46d1dc155634fbc732f92e853b10b288ad5a1d                         | Address of the contract that produced the log                |
| name              | VARCHAR   | Lens Protocol Profiles                                             |                                                              |
| symbol            | VARCHAR   | LPP                                                                |                                                              |
| timestamp         | VARCHAR   | 1652695224                                                         |                                                              |

## 4. Table: LensHub\_event\_CollectModuleWhitelisted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-15 14:09:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 42737307                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb6bbbe3fb8e6efd7bbf116ade4da3b0deb8a7efa22da4863bc0071b4ff32c60b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 245                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdb46d1dc155634fbc732f92e853b10b288ad5a1d                         | Address of the contract that produced the log                |
| collectModule     | VARCHAR   | 0x54325d507ed1b3776c146700eff61a98b45aec76                         |                                                              |
| whitelisted       | VARCHAR   | true                                                               |                                                              |
| timestamp         | VARCHAR   | 1684159744                                                         |                                                              |

## 5. Table: LensHub\_event\_CollectNFTDeployed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-17 15:30:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 31999465                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x11c36dc491b6373cb678a5d4d1ca5559098cc366dc68e8ada5f555a176a4d6a0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 576                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdb46d1dc155634fbc732f92e853b10b288ad5a1d                         | Address of the contract that produced the log                |
| profileId         | VARCHAR   | 53                                                                 |                                                              |
| pubId             | VARCHAR   | 15                                                                 |                                                              |
| collectNFT        | VARCHAR   | 0x868945f5a1434eb96e61dd0ea39ef57091771db0                         |                                                              |
| timestamp         | VARCHAR   | 1660750252                                                         |                                                              |

## 6. Table: LensHub\_event\_CollectNFTInitialized\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| profileId         | VARCHAR   |                                                              |             |
| pubId             | VARCHAR   |                                                              |             |
| timestamp         | VARCHAR   |                                                              |             |

## 7. Table: LensHub\_event\_CollectNFTTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-17 00:00:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 35698256                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x96024aa794b90c04c5cbef7f8e34cf7bf1b16a797409cad1ed6a3bb965a48d51 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 676                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdb46d1dc155634fbc732f92e853b10b288ad5a1d                         | Address of the contract that produced the log                |
| profileId         | VARCHAR   | 36                                                                 |                                                              |
| pubId             | VARCHAR   | 769                                                                |                                                              |
| collectNFTId      | VARCHAR   | 42                                                                 |                                                              |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x75fae78ce542de64824df2e60e2828bc2a2d953c                         |                                                              |
| timestamp         | VARCHAR   | 1668643214                                                         |                                                              |

## 8. Table: LensHub\_event\_Collected\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| collector         | VARCHAR   |                                                              |             |
| profileId         | VARCHAR   |                                                              |             |
| pubId             | VARCHAR   |                                                              |             |
| rootProfileId     | VARCHAR   |                                                              |             |
| rootPubId         | VARCHAR   |                                                              |             |
| timestamp         | VARCHAR   |                                                              |             |

## 9. Table: LensHub\_event\_CommentCreated\_history

| Column                    | Type      | Example                                                                                              | Description                                                  |
| ------------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp          | TIMESTAMP | 2022-05-26 15:40:20+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number             | INTEGER   | 28797486                                                                                             | The block number where this event was emitted                |
| transaction\_hash         | VARCHAR   | 0x85b35b72ad4ad87d8185bec63eb414db9aeb662a6d7bded959c000d026755627                                   | Hash of the transactions in which this event was emitted     |
| log\_index                | INTEGER   | 286                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address         | VARCHAR   | 0xdb46d1dc155634fbc732f92e853b10b288ad5a1d                                                           | Address of the contract that produced the log                |
| profileId                 | VARCHAR   | 4402                                                                                                 |                                                              |
| pubId                     | VARCHAR   | 1                                                                                                    |                                                              |
| contentURI                | VARCHAR   | https://i3al5fdaammr.usemoralis.com:2053/server/files/OM0lh4o5YtQJmH9yvmFUQE0UT12Dm7RBlIY0yqmo/QmZhn |                                                              |
| profileIdPointed          | VARCHAR   | 1                                                                                                    |                                                              |
| pubIdPointed              | VARCHAR   | 1                                                                                                    |                                                              |
| referenceModuleData       | VARCHAR   | 0x                                                                                                   |                                                              |
| collectModule             | VARCHAR   | 0xa31ff85e840ed117e172bc9ad89e55128a999205                                                           |                                                              |
| collectModuleReturnData   | VARCHAR   | 0x                                                                                                   |                                                              |
| referenceModule           | VARCHAR   | 0x0000000000000000000000000000000000000000                                                           |                                                              |
| referenceModuleReturnData | VARCHAR   | 0x                                                                                                   |                                                              |
| timestamp                 | VARCHAR   | 1653579620                                                                                           |                                                              |

## 10. Table: LensHub\_event\_DefaultProfileSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-08 00:31:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 36557063                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbaa9c3dae1be1488bd280cfa055c6ae1922108525e3e9b4d76c8a2efadf11a84 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 42                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdb46d1dc155634fbc732f92e853b10b288ad5a1d                         | Address of the contract that produced the log                |
| wallet            | VARCHAR   | 0xd44a8b8d8a651258556f0c8f5da4d003dcd020b1                         |                                                              |
| profileId         | VARCHAR   | 57306                                                              |                                                              |
| timestamp         | VARCHAR   | 1670459469                                                         |                                                              |

## 11. Table: LensHub\_event\_DispatcherSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-19 16:04:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 37024388                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbce413414bfe45a879ac0de37fd090e1d2d5e32da944ce53c9f0ec14725a6128 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdb46d1dc155634fbc732f92e853b10b288ad5a1d                         | Address of the contract that produced the log                |
| profileId         | VARCHAR   | 100509                                                             |                                                              |
| dispatcher        | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| timestamp         | VARCHAR   | 1671465858                                                         |                                                              |

## 12. Table: LensHub\_event\_EmergencyAdminSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-18 12:25:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 28468293                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1d185809ce7d15521c4774b8b6c3ee6c9bd63b033ff240e072c56b7369faed14 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 110                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdb46d1dc155634fbc732f92e853b10b288ad5a1d                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0xdab8b0559186c1cb7638b2d4239268cb9cf83ac5                         |                                                              |
| oldEmergencyAdmin | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newEmergencyAdmin | VARCHAR   | 0xd06b05a0ebda5ea9fdb3c2eb6be35ba6a16dcb4e                         |                                                              |
| timestamp         | VARCHAR   | 1652876756                                                         |                                                              |

## 13. Table: LensHub\_event\_FeeModuleBaseConstructed\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| moduleGlobals     | VARCHAR   |                                                              |             |
| timestamp         | VARCHAR   |                                                              |             |

## 14. Table: LensHub\_event\_FollowModuleSet\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2022-07-10 14:07:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 30565888                                                           | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0x0bf299b342e2ce3edcfff19a8d39b9a1dd8892fb52d143d72b08eef357daa681 | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 264                                                                | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0xdb46d1dc155634fbc732f92e853b10b288ad5a1d                         | Address of the contract that produced the log                |
| profileId              | VARCHAR   | 27903                                                              |                                                              |
| followModule           | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| followModuleReturnData | VARCHAR   | 0x                                                                 |                                                              |
| timestamp              | VARCHAR   | 1657462053                                                         |                                                              |

## 15. Table: LensHub\_event\_FollowModuleWhitelisted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-16 10:39:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 28385789                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcde2c3b7dbf049f190cea38ff7905e894fd72ef4727ffad1222990170ddffaca | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 236                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdb46d1dc155634fbc732f92e853b10b288ad5a1d                         | Address of the contract that produced the log                |
| followModule      | VARCHAR   | 0x80ae0e6048d6e295ee6520b07eb6ec4485193fd6                         |                                                              |
| whitelisted       | VARCHAR   | true                                                               |                                                              |
| timestamp         | VARCHAR   | 1652697592                                                         |                                                              |

## 16. Table: LensHub\_event\_FollowNFTDelegatedPowerChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| delegate          | VARCHAR   |                                                              |             |
| newPower          | VARCHAR   |                                                              |             |
| timestamp         | VARCHAR   |                                                              |             |

## 17. Table: LensHub\_event\_FollowNFTDeployed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-01 14:31:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 43410720                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdc121227e5a506a114d16abb9bd616eafb94584a213fcb7db13cf9dc36533e4c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 250                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdb46d1dc155634fbc732f92e853b10b288ad5a1d                         | Address of the contract that produced the log                |
| profileId         | VARCHAR   | 117444                                                             |                                                              |
| followNFT         | VARCHAR   | 0xd8cea6a6364efff888f5fb64a2c2f45e5b1f5dad                         |                                                              |
| timestamp         | VARCHAR   | 1685629889                                                         |                                                              |

## 18. Table: LensHub\_event\_FollowNFTInitialized\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| profileId         | VARCHAR   |                                                              |             |
| timestamp         | VARCHAR   |                                                              |             |

## 19. Table: LensHub\_event\_FollowNFTTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-26 00:10:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 28771731                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xadcd6d9265326123a71570d31d84ffb1680a466daa2a0ff4808a2cad03f648d8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 126                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdb46d1dc155634fbc732f92e853b10b288ad5a1d                         | Address of the contract that produced the log                |
| profileId         | VARCHAR   | 247                                                                |                                                              |
| followNFTId       | VARCHAR   | 1                                                                  |                                                              |
| from              | VARCHAR   | 0x38123a191e9685448658d2207b0543e2fb9282cc                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| timestamp         | VARCHAR   | 1653523848                                                         |                                                              |

## 20. Table: LensHub\_event\_FollowNFTURISet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-18 16:49:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 39437634                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x625f35bafb96379a6b2e3f053034b32c6a42e14b289f902694d23a50e73b73ad | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 381                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdb46d1dc155634fbc732f92e853b10b288ad5a1d                         | Address of the contract that produced the log                |
| profileId         | VARCHAR   | 110026                                                             |                                                              |
| followNFTURI      | VARCHAR   | ipfs://QmQ8vhCyBywN8Z2DGPEWwT2Edk92vS8j1rfLuQdAgNXMTc              |                                                              |
| timestamp         | VARCHAR   | 1676738954                                                         |                                                              |

## 21. Table: LensHub\_event\_Followed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-18 08:48:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33254231                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x798a44130004ab495c1b75bd58b6b6996d52084bf47105ce8ff4c020af6a91d7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 309                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdb46d1dc155634fbc732f92e853b10b288ad5a1d                         | Address of the contract that produced the log                |
| follower          | VARCHAR   | 0x0000ce08fa224696a819877070bf378e8b131acf                         |                                                              |
| profileIds        | VARCHAR   | 8                                                                  |                                                              |
| followModuleDatas | VARCHAR   | 0x00000000000000000000000000000000000000000000000000000000000024e8 |                                                              |
| timestamp         | VARCHAR   | 1663490937                                                         |                                                              |

## 22. Table: LensHub\_event\_FollowsApproved\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| owner             | VARCHAR   |                                                              |             |
| profileId         | VARCHAR   |                                                              |             |
| addresses         | VARCHAR   |                                                              |             |
| approved          | VARCHAR   |                                                              |             |
| timestamp         | VARCHAR   |                                                              |             |

## 23. Table: LensHub\_event\_GovernanceSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-18 12:26:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 28468296                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xabc103f77277bb18d1e33ce75633495baa7a05303931226cb5833a3bccc76961 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 81                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdb46d1dc155634fbc732f92e853b10b288ad5a1d                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0xdab8b0559186c1cb7638b2d4239268cb9cf83ac5                         |                                                              |
| prevGovernance    | VARCHAR   | 0xdab8b0559186c1cb7638b2d4239268cb9cf83ac5                         |                                                              |
| newGovernance     | VARCHAR   | 0xf94b90bbeee30996019babd12cecddccf68331de                         |                                                              |
| timestamp         | VARCHAR   | 1652876762                                                         |                                                              |

## 24. Table: LensHub\_event\_MirrorCreated\_history

| Column                    | Type      | Example                                                            | Description                                                  |
| ------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp          | TIMESTAMP | 2022-12-12 07:12:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number             | INTEGER   | 36731120                                                           | The block number where this event was emitted                |
| transaction\_hash         | VARCHAR   | 0x39651d64df92c5fcfc14e28527431c9c1dc5d7e309b4939c35904ba9603450c2 | Hash of the transactions in which this event was emitted     |
| log\_index                | INTEGER   | 108                                                                | Integer of the log index position in the block of this event |
| contract\_address         | VARCHAR   | 0xdb46d1dc155634fbc732f92e853b10b288ad5a1d                         | Address of the contract that produced the log                |
| profileId                 | VARCHAR   | 46667                                                              |                                                              |
| pubId                     | VARCHAR   | 44                                                                 |                                                              |
| profileIdPointed          | VARCHAR   | 1                                                                  |                                                              |
| pubIdPointed              | VARCHAR   | 1                                                                  |                                                              |
| referenceModuleData       | VARCHAR   | 0x                                                                 |                                                              |
| referenceModule           | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| referenceModuleReturnData | VARCHAR   | 0x                                                                 |                                                              |
| timestamp                 | VARCHAR   | 1670829152                                                         |                                                              |

## 25. Table: LensHub\_event\_ModuleBaseConstructed\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| hub               | VARCHAR   |                                                              |             |
| timestamp         | VARCHAR   |                                                              |             |

## 26. Table: LensHub\_event\_ModuleGlobalsCurrencyWhitelisted\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| currency          | VARCHAR   |                                                              |             |
| prevWhitelisted   | VARCHAR   |                                                              |             |
| whitelisted       | VARCHAR   |                                                              |             |
| timestamp         | VARCHAR   |                                                              |             |

## 27. Table: LensHub\_event\_ModuleGlobalsGovernanceSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| prevGovernance    | VARCHAR   |                                                              |             |
| newGovernance     | VARCHAR   |                                                              |             |
| timestamp         | VARCHAR   |                                                              |             |

## 28. Table: LensHub\_event\_ModuleGlobalsTreasuryFeeSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| prevTreasuryFee   | VARCHAR   |                                                              |             |
| newTreasuryFee    | VARCHAR   |                                                              |             |
| timestamp         | VARCHAR   |                                                              |             |

## 29. Table: LensHub\_event\_ModuleGlobalsTreasurySet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| prevTreasury      | VARCHAR   |                                                              |             |
| newTreasury       | VARCHAR   |                                                              |             |
| timestamp         | VARCHAR   |                                                              |             |

## 30. Table: LensHub\_event\_PostCreated\_history

| Column                    | Type      | Example                                                            | Description                                                  |
| ------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp          | TIMESTAMP | 2022-11-18 19:41:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number             | INTEGER   | 35772614                                                           | The block number where this event was emitted                |
| transaction\_hash         | VARCHAR   | 0x24d569cc08da2ef4312d57471cea9c05e80e8a9d225d37bc58df295d1cb063f8 | Hash of the transactions in which this event was emitted     |
| log\_index                | INTEGER   | 61                                                                 | Integer of the log index position in the block of this event |
| contract\_address         | VARCHAR   | 0xdb46d1dc155634fbc732f92e853b10b288ad5a1d                         | Address of the contract that produced the log                |
| profileId                 | VARCHAR   | 99837                                                              |                                                              |
| pubId                     | VARCHAR   | 6                                                                  |                                                              |
| contentURI                | VARCHAR   | https://arweave.net/nuxsWZTAE1BWVMDpNBm-9OqmOntB6NM-QeEgQ2gS3RM    |                                                              |
| collectModule             | VARCHAR   | 0x23b9467334beb345aaa6fd1545538f3d54436e96                         |                                                              |
| collectModuleReturnData   | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000 |                                                              |
| referenceModule           | VARCHAR   | 0x17317f96f0c7a845ffe78c60b10ab15789b57aaa                         |                                                              |
| referenceModuleReturnData | VARCHAR   | 0x                                                                 |                                                              |
| timestamp                 | VARCHAR   | 1668800464                                                         |                                                              |

## 31. Table: LensHub\_event\_ProfileCreated\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2023-06-01 06:07:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 43396748                                                           | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0xc4733f8ff39917b815a2b3868921cdb7018782ed4dd8e60f3af19404e5ef078f | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 122                                                                | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0xdb46d1dc155634fbc732f92e853b10b288ad5a1d                         | Address of the contract that produced the log                |
| profileId              | VARCHAR   | 117753                                                             |                                                              |
| creator                | VARCHAR   | 0x1eec6eccaa4625da3fa6cd6339dbcc2418710e8a                         |                                                              |
| to                     | VARCHAR   | 0x285c54d5fe93a2af4dcc788f878e042a02839946                         |                                                              |
| handle                 | VARCHAR   | theinfiltred.lens                                                  |                                                              |
| imageURI               | VARCHAR   |                                                                    |                                                              |
| followModule           | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| followModuleReturnData | VARCHAR   | 0x                                                                 |                                                              |
| followNFTURI           | VARCHAR   | ipfs://QmQwt9hFr25jzXmcfSSZppegLazndHyNtFLrBzCTRCw2T3              |                                                              |
| timestamp              | VARCHAR   | 1685599659                                                         |                                                              |

## 32. Table: LensHub\_event\_ProfileCreatorWhitelisted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-16 11:01:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 28386431                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x819f32c5da34712d360a65f1e27a50574670c7f72c5844fcd78e472cd2541104 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 470                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdb46d1dc155634fbc732f92e853b10b288ad5a1d                         | Address of the contract that produced the log                |
| profileCreator    | VARCHAR   | 0x1eec6eccaa4625da3fa6cd6339dbcc2418710e8a                         |                                                              |
| whitelisted       | VARCHAR   | true                                                               |                                                              |
| timestamp         | VARCHAR   | 1652698916                                                         |                                                              |

## 33. Table: LensHub\_event\_ProfileImageURISet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-28 07:44:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 36164231                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x215ef77ab390a4216881e357c4db71860cb1265b6d807dcccdd2b8b2ba074813 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdb46d1dc155634fbc732f92e853b10b288ad5a1d                         | Address of the contract that produced the log                |
| profileId         | VARCHAR   | 38296                                                              |                                                              |
| imageURI          | VARCHAR   | ipfs://bafkreihc4d3zo2kzvwfzkagnj3h2gqadlhpn4hc3wbdzvxuqg7vakpyagi |                                                              |
| timestamp         | VARCHAR   | 1669621473                                                         |                                                              |

## 34. Table: LensHub\_event\_ReferenceModuleWhitelisted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-22 12:48:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33425238                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1ea9cf7b3eb1e316a9d8cc965b8f9cdfb72d0212e0b7a83ee2daa456d24a23f1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 98                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdb46d1dc155634fbc732f92e853b10b288ad5a1d                         | Address of the contract that produced the log                |
| referenceModule   | VARCHAR   | 0x081a84abf515302a276d98dc551e69f3cc33a833                         |                                                              |
| whitelisted       | VARCHAR   | true                                                               |                                                              |
| timestamp         | VARCHAR   | 1663850922                                                         |                                                              |

## 35. Table: LensHub\_event\_StateSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-16 10:00:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 28384641                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xca69b18b7e2daf4695c6d614e263d6aa9bdee44bee91bee7e0e6e5e5e4262fca | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 520                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdb46d1dc155634fbc732f92e853b10b288ad5a1d                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0xc5979637239c2edd9c5e18577261cd931de36b4a                         |                                                              |
| prevState         | VARCHAR   | 0                                                                  |                                                              |
| newState          | VARCHAR   | 2                                                                  |                                                              |
| timestamp         | VARCHAR   | 1652695224                                                         |                                                              |

## 36. Table: LensHub\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-17 23:22:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 35738344                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfc27638a858c6bfee5d475d6cfb7491cd18d38d4d44e5874472f53446b8b42cd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdb46d1dc155634fbc732f92e853b10b288ad5a1d                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x89aad9c5b8287907d81f3d00074c7873b2d21054                         |                                                              |
| tokenId           | VARCHAR   | 101666                                                             |                                                              |
