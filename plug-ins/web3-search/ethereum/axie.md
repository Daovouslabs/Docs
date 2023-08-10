# axie

## 1. Table: AxieClockAuction\_event\_AuctionCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-26 10:52:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10937813                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x580cc74145dae6c0ecb0146e2041d45aac43d51bede53a8c6b6c5ea2c03359ca | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 143                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf4985070ce32b6b1994329df787d1acc9a2dd9e2                         | Address of the contract that produced the log                |
| \_nftAddress      | VARCHAR   | 0xf5b0a3efb8e8e4c201e2a935f110eaaf3ffecb8d                         |                                                              |
| \_tokenId         | VARCHAR   | 1662                                                               |                                                              |

## 2. Table: AxieClockAuction\_event\_AuctionCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-07-12 19:21:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8138102                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x151a9755e708507ad70c71b198d683a0cfdd1a693fa92387ce7c5c0304f98737 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 62                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf4985070ce32b6b1994329df787d1acc9a2dd9e2                         | Address of the contract that produced the log                |
| \_nftAddress      | VARCHAR   | 0xf5b0a3efb8e8e4c201e2a935f110eaaf3ffecb8d                         |                                                              |
| \_tokenId         | VARCHAR   | 10531                                                              |                                                              |
| \_startingPrice   | VARCHAR   | 1000000000000000000                                                |                                                              |
| \_endingPrice     | VARCHAR   | 1000000000000                                                      |                                                              |
| \_duration        | VARCHAR   | 864000000                                                          |                                                              |
| \_seller          | VARCHAR   | 0x806a7328ace7c0766615b78838aa312bd0bf65f5                         |                                                              |

## 3. Table: AxieClockAuction\_event\_AuctionSuccessful\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-05 01:42:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7011927                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb5d0fe39fa419c8910307a9ab06439ac2c7757f4bae8221e0986aa92cda03a3a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 38                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf4985070ce32b6b1994329df787d1acc9a2dd9e2                         | Address of the contract that produced the log                |
| \_nftAddress      | VARCHAR   | 0xf5b0a3efb8e8e4c201e2a935f110eaaf3ffecb8d                         |                                                              |
| \_tokenId         | VARCHAR   | 4791                                                               |                                                              |
| \_totalPrice      | VARCHAR   | 200000000000000000                                                 |                                                              |
| \_winner          | VARCHAR   | 0x004f980394e98123e0a3414f7eb25a9f2c123d04                         |                                                              |

## 4. Table: AxieCore\_event\_ApprovalForAll\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-03 01:06:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15266496                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc9bd89385505b93f1556ccdda1cdc4b2b2be59b01ffaf9cb6b6c39d1c8fa8726 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 510                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf5b0a3efb8e8e4c201e2a935f110eaaf3ffecb8d                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x8dbbca57ea56290efa14d835bbfd34faf1d89753                         |                                                              |
| \_operator        | VARCHAR   | 0x1e6b394dea8069d365c6eeec872eeb433f48418d                         |                                                              |
| \_approved        | VARCHAR   | false                                                              |                                                              |

## 5. Table: AxieCore\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-27 12:18:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11138574                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0e3ed239969e0326f962b98f9b2286af5aa75c7f650c49707c9b6057bfb967a1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 111                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf5b0a3efb8e8e4c201e2a935f110eaaf3ffecb8d                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x0026c675728fcbd1c03f1683a319e548c7416341                         |                                                              |
| \_approved        | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_tokenId         | VARCHAR   | 163739                                                             |                                                              |

## 6. Table: AxieCore\_event\_AxieEvolved\_history

| Column            | Type      | Example                                                                       | Description                                                  |
| ----------------- | --------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-07-03 22:15:00+00:00                                                     | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8081044                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4c5e43f21a5ce73362753c533c609f4ff2a6ef4c64298cc8c82b3458fa4fbc12            | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 56                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf5b0a3efb8e8e4c201e2a935f110eaaf3ffecb8d                                    | Address of the contract that produced the log                |
| \_axieId          | VARCHAR   | 72730                                                                         |                                                              |
| \_oldGenes        | VARCHAR   | 0                                                                             |                                                              |
| \_newGenes        | VARCHAR   | 25329519522048463539065091232159132598789149900996245841413536730827074902220 |                                                              |

## 7. Table: AxieCore\_event\_AxieSpawned\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-19 10:25:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9902292                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x99432a17846aa4ded49573e34202be1faf161db8414e8f186d753758d786a727 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 139                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf5b0a3efb8e8e4c201e2a935f110eaaf3ffecb8d                         | Address of the contract that produced the log                |
| \_axieId          | VARCHAR   | 146895                                                             |                                                              |
| \_owner           | VARCHAR   | 0x0b946efae53975b97a0d1d02f75fabf55d0d6a96                         |                                                              |
| \_genes           | VARCHAR   | 0                                                                  |                                                              |

## 8. Table: AxieCore\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-19 13:33:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10690853                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd7ec555d5825dac5ec889b7f819469f18e56d285b295d2f5e897f465fa584bc1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 181                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf5b0a3efb8e8e4c201e2a935f110eaaf3ffecb8d                         | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_to              | VARCHAR   | 0x4cda119c7bec1685bb39ebcf9e4be4252670a754                         |                                                              |
| \_tokenId         | VARCHAR   | 151166                                                             |                                                              |

## 9. Table: AxieOriginCoin\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-09-12 23:46:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6320901                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3747c253133752761b23d8988b48f30dcc093b89fb3bf29123e6c6df3d9ddbf6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 36                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73d7b530d181ef957525c6fbe2ab8f28bf4f81cf                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x08797952462b82db639ddbfdef2ab1718ffa7676                         |                                                              |
| \_spender         | VARCHAR   | 0xae8e74a21c25c22112749f7a9cd600d4b5cb2191                         |                                                              |
| \_value           | VARCHAR   | 5                                                                  |                                                              |

## 10. Table: AxieOriginCoin\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-04-24 23:47:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5500151                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x89c29f1d4d1d17e5e0ef6b0f69d7dacf430750f988e9402acf60a9715d7686e7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 14                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73d7b530d181ef957525c6fbe2ab8f28bf4f81cf                         | Address of the contract that produced the log                |
| burner            | VARCHAR   | 0xc75efe55705770db12724dea5c901301789ddb45                         |                                                              |
| value             | VARCHAR   | 5                                                                  |                                                              |

## 11. Table: AxieOriginCoin\_event\_MintFinished\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-04-24 22:35:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5499884                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3c14003498bf7d97a876d12cd4393249772fa538f1a5da551ed99037db41e4fa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 88                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73d7b530d181ef957525c6fbe2ab8f28bf4f81cf                         | Address of the contract that produced the log                |

## 12. Table: AxieOriginCoin\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-04-24 22:35:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5499884                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3c14003498bf7d97a876d12cd4393249772fa538f1a5da551ed99037db41e4fa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73d7b530d181ef957525c6fbe2ab8f28bf4f81cf                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0x1878b18693fc273de9fd833b83f9679785c01ab2                         |                                                              |
| value             | VARCHAR   | 1                                                                  |                                                              |

## 13. Table: AxieOriginCoin\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-05-06 00:55:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5563462                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb039bd680eff4a5bd88ebd2c5a47af506b31bcb875b287afded5c93c2c297b36 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 106                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73d7b530d181ef957525c6fbe2ab8f28bf4f81cf                         | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0x5ea1d56d0dde1ca5b50c277275855f69edefa169                         |                                                              |
| \_to              | VARCHAR   | 0x28fcfc54f11d2897db25741913d6578605ac32b5                         |                                                              |
| \_value           | VARCHAR   | 1                                                                  |                                                              |

## 14. Table: AxiePresaleExtended\_event\_AdoptedAxiesRedeemed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-04-19 09:12:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5467607                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9d6af5324a031aeb4af8b1f4736af50d736dad328ee998fce56a4cfa4fbc85c9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 173                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3d5be9a472d6b5c8d45b4b3a3bffb80e0c52ef15                         | Address of the contract that produced the log                |
| \_receiver        | VARCHAR   | 0xa368781908d25144f80b0943abf3967d82f9dccf                         |                                                              |
| \_class           | VARCHAR   | 0                                                                  |                                                              |
| \_quantity        | VARCHAR   | 1                                                                  |                                                              |

## 15. Table: AxiePresaleExtended\_event\_AxiesAdopted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-03-19 14:53:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5283835                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x08dacfb3751a7ffb61f63570a1e1b68225f4cf1a636276bf16e1ae882f506b73 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3d5be9a472d6b5c8d45b4b3a3bffb80e0c52ef15                         | Address of the contract that produced the log                |
| \_adopter         | VARCHAR   | 0xde089d1801e6ed1d75076950c4717445d02ae984                         |                                                              |
| \_class           | VARCHAR   | 2                                                                  |                                                              |
| \_quantity        | VARCHAR   | 1                                                                  |                                                              |
| \_referrer        | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 16. Table: AxiePresaleExtended\_event\_AxiesRewarded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-04-05 17:33:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5386264                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x917d3946646158311ca6504a37df8a88adb280a9b2807f8727ba8aa6f273c28f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 74                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3d5be9a472d6b5c8d45b4b3a3bffb80e0c52ef15                         | Address of the contract that produced the log                |
| \_receiver        | VARCHAR   | 0xa6bcec585f12cefba9709a080ce2efd38f871024                         |                                                              |
| \_quantity        | VARCHAR   | 7                                                                  |                                                              |

## 17. Table: AxiePresaleExtended\_event\_RefCreditsMinted\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2018-03-13 23:39:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 5250639                                                            | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0xb8174f09181a9d8a37ab559ec9d1357c405589254f7f688ab59eee044a0a575e | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 75                                                                 | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x3d5be9a472d6b5c8d45b4b3a3bffb80e0c52ef15                         | Address of the contract that produced the log                |
| \_receiver         | VARCHAR   | 0xc75efe55705770db12724dea5c901301789ddb45                         |                                                              |
| \_numMintedCredits | VARCHAR   | 15                                                                 |                                                              |

## 18. Table: AxiePresaleExtended\_event\_RewardedAxiesRedeemed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-04-08 17:33:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5404483                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0217b0929c5fdde1aa645acbaacde35f17650958fc3104891cfadc51045b6665 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3d5be9a472d6b5c8d45b4b3a3bffb80e0c52ef15                         | Address of the contract that produced the log                |
| \_receiver        | VARCHAR   | 0x73601fd195e1c6407e21845ed40b0c9d61c37ab1                         |                                                              |
| \_quantity        | VARCHAR   | 1                                                                  |                                                              |

## 19. Table: AxiePresale\_event\_AxiesAdopted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-02-25 16:50:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5154799                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x273f6a12dbaff5cf65f75e70db1ae56683a994ad854fcf69b8865b6a67da9ff2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 25                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb28a3dd24036151c819c6d401f7a222d9aa3671b                         | Address of the contract that produced the log                |
| adopter           | VARCHAR   | 0xc75efe55705770db12724dea5c901301789ddb45                         |                                                              |
| clazz             | VARCHAR   | 0                                                                  |                                                              |
| quantity          | VARCHAR   | 2                                                                  |                                                              |
| referrer          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 20. Table: AxiePresale\_event\_AxiesRewarded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-02-20 22:53:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5126924                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaf6025c5ee08cfa893f20ea6cc3ab7afa1dd71821e89fde28eff6bbc49e0f799 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 42                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb28a3dd24036151c819c6d401f7a222d9aa3671b                         | Address of the contract that produced the log                |
| receiver          | VARCHAR   | 0xd387a6e4e84a6c86bd90c158c6028a58cc8ac459                         |                                                              |
| quantity          | VARCHAR   | 2                                                                  |                                                              |

## 21. Table: AxiePresale\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-03-13 07:07:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5246609                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaa4bfdb1d203738b6f7f6a8b198a662aca41e1089a7c45359a63550283445338 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 8                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb28a3dd24036151c819c6d401f7a222d9aa3671b                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x01bf1d7c5e192313c26414e134584275f46271cf                         |                                                              |
| newOwner          | VARCHAR   | 0x3d5be9a472d6b5c8d45b4b3a3bffb80e0c52ef15                         |                                                              |

## 22. Table: AxiePresale\_event\_Pause\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-03-13 07:08:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5246614                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0064620148262dc5011da8484d7a7e76319cc7e6479f50497c6b061139ea3c2b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb28a3dd24036151c819c6d401f7a222d9aa3671b                         | Address of the contract that produced the log                |

## 23. Table: AxieSiringClockAuction\_event\_AuctionCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-11-02 15:55:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6630548                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2817af3cd38eb5fbbfd90eb98ab95c876f2e390169d754ff9b5500bb6738b2dd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 172                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x60ce035dc589c3fd185b224a7ca03c598948973b                         | Address of the contract that produced the log                |
| \_axieId          | VARCHAR   | 7937                                                               |                                                              |

## 24. Table: AxieSiringClockAuction\_event\_AuctionCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-06-12 23:14:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5778502                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x27c80195deedb5548c52fec8b432e71982540a19fb7b6d3c160876ff93d3681b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 53                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x60ce035dc589c3fd185b224a7ca03c598948973b                         | Address of the contract that produced the log                |
| \_axieId          | VARCHAR   | 4169                                                               |                                                              |
| \_startingPrice   | VARCHAR   | 65000000000000000                                                  |                                                              |
| \_endingPrice     | VARCHAR   | 65000000000000000                                                  |                                                              |
| \_duration        | VARCHAR   | 86400                                                              |                                                              |
| \_seller          | VARCHAR   | 0x2643796cb6b4e715140f09c352ea26afff1a7d93                         |                                                              |

## 25. Table: AxieSiringClockAuction\_event\_AuctionSuccessful\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-10-13 21:11:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6509614                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xefffe66bf3cf84b4df8dc7a95c1f8ce14800c011f391a7c8aa4675c139c18d2c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 35                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x60ce035dc589c3fd185b224a7ca03c598948973b                         | Address of the contract that produced the log                |
| \_sireId          | VARCHAR   | 1399                                                               |                                                              |
| \_matronId        | VARCHAR   | 6411                                                               |                                                              |
| \_totalPrice      | VARCHAR   | 50000000000000000                                                  |                                                              |
| \_winner          | VARCHAR   | 0x027747771ce20e60d24344e2a62a1377960cced0                         |                                                              |

## 26. Table: AxieSiringClockAuction\_event\_Pause\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-18 12:46:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9125650                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0d128eff1994028f7991e6ff1fe54085f5e4ba6db4b4a5a4ca871e138e2bd0ca | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 78                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x60ce035dc589c3fd185b224a7ca03c598948973b                         | Address of the contract that produced the log                |

## 27. Table: LUNA\_event\_AdminChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-22 12:58:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7108912                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe0a13d22affeaf7e025da3cd6e649b70fa61b643108f70ea89fede96e047b06a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 20                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x92bf969865c80eda082fd5d8b4e28da4d58e1c3a                         | Address of the contract that produced the log                |
| \_oldAdmin        | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_newAdmin        | VARCHAR   | 0x28fa65ab4a4a5f31e7958a00c1ce410a426e6fe8                         |                                                              |

## 28. Table: LUNA\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-02-08 06:35:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7191726                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc9150e2b9737ee66f35c728ae03047ccdbc6cc5489959c02128a2c045f7adbb6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 68                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x92bf969865c80eda082fd5d8b4e28da4d58e1c3a                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x4fbd8c884640a10d20a2dcbc4cd85146f0b0efd7                         |                                                              |
| \_spender         | VARCHAR   | 0x2299a91cc0bffd8c7f71349da8ab03527b79724f                         |                                                              |
| \_value           | VARCHAR   | 1946507101146277105655                                             |                                                              |

## 29. Table: LUNA\_event\_MinterAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-22 12:59:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7108918                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x85a4e9a63109d222724a7a20788667ffa6e946c4c0b8e8a7f170f7fcb0708818 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 32                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x92bf969865c80eda082fd5d8b4e28da4d58e1c3a                         | Address of the contract that produced the log                |
| \_minter          | VARCHAR   | 0x28fa65ab4a4a5f31e7958a00c1ce410a426e6fe8                         |                                                              |

## 30. Table: LUNA\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-14 16:21:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10065345                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd9a893f930a7eb0dbd342b7f05f342bf01b64b8b7ba0f54ef1376e982d680630 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 24                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x92bf969865c80eda082fd5d8b4e28da4d58e1c3a                         | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0xb09d6f2004912a12abb0a75d6c631292508e214c                         |                                                              |
| \_to              | VARCHAR   | 0xc2ea113c212e265f2ce672e15fc97dc9b39b83b3                         |                                                              |
| \_value           | VARCHAR   | 84943481049117516360                                               |                                                              |

## 31. Table: LandSale\_event\_AdminChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-22 12:59:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7108917                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7ac8a91a0833e207d1f1f336febebaf9ee33981ba5d0b3147e156bfb96a59d2c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 35                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7a11462a2adaed5571b91e34a127e4cbf51b152c                         | Address of the contract that produced the log                |
| \_oldAdmin        | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_newAdmin        | VARCHAR   | 0x28fa65ab4a4a5f31e7958a00c1ce410a426e6fe8                         |                                                              |

## 32. Table: LandSale\_event\_ChestPurchased\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2019-01-23 12:59:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 7113895                                                            | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xd18c8a766dadf8eb2185baedb9f8fffade0feb657a9b26264ddea7dc32f5bf6e | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 96                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x7a11462a2adaed5571b91e34a127e4cbf51b152c                         | Address of the contract that produced the log                |
| \_chestType          | VARCHAR   | 0                                                                  |                                                              |
| \_chestAmount        | VARCHAR   | 1                                                                  |                                                              |
| \_tokenAddress       | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| \_tokenAmount        | VARCHAR   | 45000000000000000                                                  |                                                              |
| \_totalPrice         | VARCHAR   | 45000000000000000                                                  |                                                              |
| \_lunaCashbackAmount | VARCHAR   | 5365760399999999997                                                |                                                              |
| \_buyer              | VARCHAR   | 0x55050ff53a1ab7eeb18fcca5fbc463c7f4f23e70                         |                                                              |
| \_owner              | VARCHAR   | 0x55050ff53a1ab7eeb18fcca5fbc463c7f4f23e70                         |                                                              |

## 33. Table: LandSale\_event\_CustomTokenRateUpdated\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2019-01-22 12:59:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 7108917                                                            | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x7ac8a91a0833e207d1f1f336febebaf9ee33981ba5d0b3147e156bfb96a59d2c | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 36                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x7a11462a2adaed5571b91e34a127e4cbf51b152c                         | Address of the contract that produced the log                |
| \_tokenAddress      | VARCHAR   | 0x92bf969865c80eda082fd5d8b4e28da4d58e1c3a                         |                                                              |
| \_quoteTokenAddress | VARCHAR   | 0x89d24a6b4ccb1b6faa2625fe562bdd9a23260359                         |                                                              |
| \_rate              | VARCHAR   | 100000000000000000                                                 |                                                              |

## 34. Table: LandSale\_event\_Paused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-22 13:59:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7109108                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3827d5149212232bd2a8c44154b5bf0131b669c892a58b59fcd9a4b3bf309f6b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 58                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7a11462a2adaed5571b91e34a127e4cbf51b152c                         | Address of the contract that produced the log                |

## 35. Table: LandSale\_event\_ReferralRewarded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-22 15:11:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7109377                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x18f22fb719d070569ad6d255ba8a1f2a940ee478efe3d2f81463f54d5eb287c9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 31                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7a11462a2adaed5571b91e34a127e4cbf51b152c                         | Address of the contract that produced the log                |
| \_referrer        | VARCHAR   | 0x288bf6134beb79d63173a13d65bc92f4ebd718b2                         |                                                              |
| \_referralReward  | VARCHAR   | 2250000000000000                                                   |                                                              |

## 36. Table: LandSale\_event\_Unpaused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-22 14:42:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7109281                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x48e67fb29dbb0152fcd518adc3e1454a1ad2e68468a474ae88b2f51a18315e8b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7a11462a2adaed5571b91e34a127e4cbf51b152c                         | Address of the contract that produced the log                |

## 37. Table: LandSale\_v2\_event\_AdminChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-23 22:22:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7115901                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xef89d56a0ae4cb26d178cec3aa60d09bab9e8cead9049a0032eaf9302de49ff0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 88                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2299a91cc0bffd8c7f71349da8ab03527b79724f                         | Address of the contract that produced the log                |
| \_oldAdmin        | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_newAdmin        | VARCHAR   | 0x28fa65ab4a4a5f31e7958a00c1ce410a426e6fe8                         |                                                              |

## 38. Table: LandSale\_v2\_event\_ChestPurchased\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2019-07-18 01:59:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 8171866                                                            | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x696a980dbac96a95259bd8174d3fc28eb6e5a0fdc9cd0bbfdee5d48a65804509 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 50                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x2299a91cc0bffd8c7f71349da8ab03527b79724f                         | Address of the contract that produced the log                |
| \_chestType          | VARCHAR   | 2                                                                  |                                                              |
| \_chestAmount        | VARCHAR   | 1                                                                  |                                                              |
| \_tokenAddress       | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| \_tokenAmount        | VARCHAR   | 450000000000000000                                                 |                                                              |
| \_totalPrice         | VARCHAR   | 450000000000000000                                                 |                                                              |
| \_lunaCashbackAmount | VARCHAR   | 64285714285714285714                                               |                                                              |
| \_buyer              | VARCHAR   | 0x071ef7f7b9dbaba85fd6dc9f9a9b10e71f00a69b                         |                                                              |
| \_owner              | VARCHAR   | 0x071ef7f7b9dbaba85fd6dc9f9a9b10e71f00a69b                         |                                                              |

## 39. Table: LandSale\_v2\_event\_CustomTokenRateUpdated\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2019-01-24 11:39:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 7118727                                                            | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xb7dac8c8226e9617707b5b7ed4fd8eba74016deb0b8a08e3f02b13ea19f82f37 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 69                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x2299a91cc0bffd8c7f71349da8ab03527b79724f                         | Address of the contract that produced the log                |
| \_tokenAddress      | VARCHAR   | 0xa4e8c3ec456107ea67d3075bf9e3df3a75823db0                         |                                                              |
| \_quoteTokenAddress | VARCHAR   | 0x89d24a6b4ccb1b6faa2625fe562bdd9a23260359                         |                                                              |
| \_rate              | VARCHAR   | 45000000000000000                                                  |                                                              |

## 40. Table: LandSale\_v2\_event\_Paused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-05-04 16:16:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7695525                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x102d41fa9718b787e9ceacf45d088cc12c51d0169766828ab750b783630f2a15 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 36                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2299a91cc0bffd8c7f71349da8ab03527b79724f                         | Address of the contract that produced the log                |

## 41. Table: LandSale\_v2\_event\_ReferralPercentageUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-24 07:58:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7117943                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf07d9bc2cbd486226290bbffc9af657a721990adf9119ed08f10d1fc8690908d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 27                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2299a91cc0bffd8c7f71349da8ab03527b79724f                         | Address of the contract that produced the log                |
| \_referrer        | VARCHAR   | 0x2ebeb3c8f4d69300137a2aeb27a30e2793eb89b8                         |                                                              |
| \_percentage      | VARCHAR   | 1500                                                               |                                                              |

## 42. Table: LandSale\_v2\_event\_ReferralRewarded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-02-22 20:49:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7254518                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7853ce5eae98b758cbdbf3652e3fcf3242a8a3904c048e2410ee64c39900a1c6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 38                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2299a91cc0bffd8c7f71349da8ab03527b79724f                         | Address of the contract that produced the log                |
| \_referrer        | VARCHAR   | 0xb1abafb4b7f60c7ad8af161be7871cbc7cb3b1dc                         |                                                              |
| \_referralReward  | VARCHAR   | 16000000000000000                                                  |                                                              |

## 43. Table: LandSale\_v2\_event\_Unpaused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-05-06 09:37:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7706505                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xce49a637d278a2630a0ea3f406f7406fc6d7c56d5898aaf7dd903564eb7b8c11 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 69                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2299a91cc0bffd8c7f71349da8ab03527b79724f                         | Address of the contract that produced the log                |

## 44. Table: LandSale\_v3\_event\_AdminChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-08-19 15:15:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8381562                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3dd382b66d4c0a8ff349157f15120d7b2fad70dd1e867e04afe1afe6bcab8ff8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 46                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x66536a95cc83ee672da58b6d3e57f7582184d5df                         | Address of the contract that produced the log                |
| \_oldAdmin        | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_newAdmin        | VARCHAR   | 0x01bf1d7c5e192313c26414e134584275f46271cf                         |                                                              |

## 45. Table: LandSale\_v3\_event\_ChestPurchased\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2020-04-22 22:40:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 9925007                                                            | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xcd9b9eebc654f7f5f63d23e5448a8ddd3b02a0b9627a9586b72e86ff2a2f6ae0 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 26                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x66536a95cc83ee672da58b6d3e57f7582184d5df                         | Address of the contract that produced the log                |
| \_chestType          | VARCHAR   | 2                                                                  |                                                              |
| \_chestAmount        | VARCHAR   | 1                                                                  |                                                              |
| \_tokenAddress       | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| \_tokenAmount        | VARCHAR   | 450000000000000000                                                 |                                                              |
| \_totalPrice         | VARCHAR   | 450000000000000000                                                 |                                                              |
| \_lunaCashbackAmount | VARCHAR   | 82093509503022612774                                               |                                                              |
| \_buyer              | VARCHAR   | 0x9e315e9701908501f6dc68a2af6e28a20c75d970                         |                                                              |
| \_owner              | VARCHAR   | 0x9e315e9701908501f6dc68a2af6e28a20c75d970                         |                                                              |

## 46. Table: LandSale\_v3\_event\_CustomTokenRateUpdated\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2019-08-19 15:15:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 8381562                                                            | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x3dd382b66d4c0a8ff349157f15120d7b2fad70dd1e867e04afe1afe6bcab8ff8 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 47                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x66536a95cc83ee672da58b6d3e57f7582184d5df                         | Address of the contract that produced the log                |
| \_tokenAddress      | VARCHAR   | 0x92bf969865c80eda082fd5d8b4e28da4d58e1c3a                         |                                                              |
| \_quoteTokenAddress | VARCHAR   | 0x89d24a6b4ccb1b6faa2625fe562bdd9a23260359                         |                                                              |
| \_rate              | VARCHAR   | 100000000000000000                                                 |                                                              |

## 47. Table: LandSale\_v3\_event\_ReferralRewarded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-25 23:35:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9743459                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x244c232dfdc7fefdef1ec7156a285eb79c43bbc1775030502ee5f4d5a44f5a9e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 88                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x66536a95cc83ee672da58b6d3e57f7582184d5df                         | Address of the contract that produced the log                |
| \_referrer        | VARCHAR   | 0x030809eef95a7c9b74e08dfa22af76f7a7671502                         |                                                              |
| \_referralReward  | VARCHAR   | 45000000000000000                                                  |                                                              |

## 48. Table: MainchainGatewayProxy\_event\_AdminChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-25 11:53:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11724674                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb6bf3ce1639b76a10502bf8d7b76268974c456277c8f0be89bd2b1e39aa25160 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 147                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1a2a1c938ce3ec39b6d47113c7955baa9dd454f2                         | Address of the contract that produced the log                |
| \_oldAdmin        | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_newAdmin        | VARCHAR   | 0x01bf1d7c5e192313c26414e134584275f46271cf                         |                                                              |

## 49. Table: MainchainGatewayProxy\_event\_AdminRemoved\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_oldAdmin        | VARCHAR   |                                                              |             |

## 50. Table: MainchainGatewayProxy\_event\_Paused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-28 11:54:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15039524                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xddde5a569bab906d94617f47b45d45dc9144ff26b7769c8f237ce10b95cd9cdf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 324                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1a2a1c938ce3ec39b6d47113c7955baa9dd454f2                         | Address of the contract that produced the log                |

## 51. Table: MainchainGatewayProxy\_event\_ProxyUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-25 11:53:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11724674                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb6bf3ce1639b76a10502bf8d7b76268974c456277c8f0be89bd2b1e39aa25160 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 148                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1a2a1c938ce3ec39b6d47113c7955baa9dd454f2                         | Address of the contract that produced the log                |
| \_new             | VARCHAR   | 0x8407dc57739bcda7aa53ca6f12f82f9d51c2f21e                         |                                                              |
| \_old             | VARCHAR   | 0x8407dc57739bcda7aa53ca6f12f82f9d51c2f21e                         |                                                              |

## 52. Table: MainchainGatewayProxy\_event\_TokenDeposited\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2021-03-24 19:16:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 12103410                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0xec39aa6f0b0932a54c9822b1b0c33f4c9628c1f3627fc7af302a88fae18c4e21 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 130                                                                | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x1a2a1c938ce3ec39b6d47113c7955baa9dd454f2                         | Address of the contract that produced the log                |
| \_depositId        | VARCHAR   | 1203                                                               |                                                              |
| \_owner            | VARCHAR   | 0xf83fff5b77afe07e3ef63e1d877077ed00017337                         |                                                              |
| \_tokenAddress     | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| \_sidechainAddress | VARCHAR   | 0xc99a6a985ed2cac1ef41640596c5a5f9f4e19ef5                         |                                                              |
| \_standard         | VARCHAR   | 20                                                                 |                                                              |
| \_tokenNumber      | VARCHAR   | 816500000000000000                                                 |                                                              |

## 53. Table: MainchainGatewayProxy\_event\_TokenWithdrew\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-12 17:05:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12620875                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x938a526fe703975db3c1f85009d3add0360a09a967af714b5c5550add0c488e1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 262                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1a2a1c938ce3ec39b6d47113c7955baa9dd454f2                         | Address of the contract that produced the log                |
| \_withdrawId      | VARCHAR   | 34520                                                              |                                                              |
| \_owner           | VARCHAR   | 0xfb1011acf27d4e5f2f5a96f70684dee033f59146                         |                                                              |
| \_tokenAddress    | VARCHAR   | 0xbb0e17ef65f82ab018d8edd776e8dd940327b28b                         |                                                              |
| \_tokenNumber     | VARCHAR   | 637000000000000000000                                              |                                                              |

## 54. Table: MainchainGatewayProxy\_event\_Unpaused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-28 11:54:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15039524                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xddde5a569bab906d94617f47b45d45dc9144ff26b7769c8f237ce10b95cd9cdf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 317                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1a2a1c938ce3ec39b6d47113c7955baa9dd454f2                         | Address of the contract that produced the log                |
