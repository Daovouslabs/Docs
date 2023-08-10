# paxos

## 1. Table: PAXGImplementation\_event\_AddressFrozen\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-09-05 19:25:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8491917                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x78b7566124bb681f854084c2eee7491c739d043015f8d4af2d3417d5c3891f82 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 66                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45804880de22913dafe09f4980848ece6ecbaf78                         | Address of the contract that produced the log                |
| addr              | VARCHAR   | 0x8a82042fbf41f2cfbb05af8dbaea048adb900637                         |                                                              |

## 2. Table: PAXGImplementation\_event\_AddressUnfrozen\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| addr              | VARCHAR   |                                                              |             |

## 3. Table: PAXGImplementation\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-27 19:18:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15226352                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa93c50500ab2fbba8ba76248bb70bd3cd9d6765ffdacb3395ba4150876c4aa8e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 226                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45804880de22913dafe09f4980848ece6ecbaf78                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xfdc8dddd6f8dbab62d996bf313226bbfe69c5869                         |                                                              |
| spender           | VARCHAR   | 0x1111111254fb6c44bac0bed2854e76f90643097d                         |                                                              |
| value             | VARCHAR   | 856280487231214039                                                 |                                                              |

## 4. Table: PAXGImplementation\_event\_AssetProtectionRoleSet\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2021-05-04 16:54:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 12368956                                                           | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0xdc47ad4c501450f67a752d484096481424dbc7257b31552641b037c48e95b96b | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0x45804880de22913dafe09f4980848ece6ecbaf78                         | Address of the contract that produced the log                |
| oldAssetProtectionRole | VARCHAR   | 0xb87cec7baa2ce4a055f8563e9cc5a210cedc329f                         |                                                              |
| newAssetProtectionRole | VARCHAR   | 0x0644bd0248d5f89e4f6e845a91d15c23591e5d33                         |                                                              |

## 5. Table: PAXGImplementation\_event\_BetaDelegateUnwhitelisted\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldDelegate       | VARCHAR   |                                                              |             |

## 6. Table: PAXGImplementation\_event\_BetaDelegateWhitelisted\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newDelegate       | VARCHAR   |                                                              |             |

## 7. Table: PAXGImplementation\_event\_BetaDelegateWhitelisterSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldWhitelister    | VARCHAR   |                                                              |             |
| newWhitelister    | VARCHAR   |                                                              |             |

## 8. Table: PAXGImplementation\_event\_BetaDelegatedTransfer\_history

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
| serviceFee        | VARCHAR   |                                                              |             |

## 9. Table: PAXGImplementation\_event\_FeeCollected\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-16 22:12:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14598950                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x59da82da239f077eab82b4c234630bd0210fa4c1dbd2b4d647920deb33193fe9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 77                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45804880de22913dafe09f4980848ece6ecbaf78                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x000000000dfde7deaf24138722987c9a6991e2d4                         |                                                              |
| to                | VARCHAR   | 0x38699d04656ff537ef8671b6b595402ebdbdf6f4                         |                                                              |
| value             | VARCHAR   | 4036400000000000                                                   |                                                              |

## 10. Table: PAXGImplementation\_event\_FeeControllerSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-04 16:52:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12368945                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x133bd170c438581989777186cdceede8e4d61aa9df3690e70f37efc243fc2ba9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 15                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45804880de22913dafe09f4980848ece6ecbaf78                         | Address of the contract that produced the log                |
| oldFeeController  | VARCHAR   | 0x5195427ca88df768c298721da791b93ad11eca65                         |                                                              |
| newFeeController  | VARCHAR   | 0x0644bd0248d5f89e4f6e845a91d15c23591e5d33                         |                                                              |

## 11. Table: PAXGImplementation\_event\_FeeRateSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-08-26 15:30:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8426676                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb03a553490d2348756958253439e890d6a3c5c0654ef3abf2f3717af3e06bc8c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 19                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45804880de22913dafe09f4980848ece6ecbaf78                         | Address of the contract that produced the log                |
| oldFeeRate        | VARCHAR   | 0                                                                  |                                                              |
| newFeeRate        | VARCHAR   | 200                                                                |                                                              |

## 12. Table: PAXGImplementation\_event\_FeeRecipientSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-04 17:56:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12369245                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfc7a9ba855c250c3380204f1b8c7b34b363c4273ccd0fbd3656a6ced8a50a4d7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 86                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45804880de22913dafe09f4980848ece6ecbaf78                         | Address of the contract that produced the log                |
| oldFeeRecipient   | VARCHAR   | 0x611479ce1d3d457ffe9fb2abbaf8d3fe2ad8fffb                         |                                                              |
| newFeeRecipient   | VARCHAR   | 0x38699d04656ff537ef8671b6b595402ebdbdf6f4                         |                                                              |

## 13. Table: PAXGImplementation\_event\_FrozenAddressWiped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-22 16:33:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16241466                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x05dd47e72f90e878e0e4d12b2548cdba5746f981495d3afc832293c3a20a6471 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 536                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45804880de22913dafe09f4980848ece6ecbaf78                         | Address of the contract that produced the log                |
| addr              | VARCHAR   | 0x5ea8132c16d6fa409c65d48c5e093a0dffa0d253                         |                                                              |

## 14. Table: PAXGImplementation\_event\_OwnershipTransferDisregarded\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldProposedOwner  | VARCHAR   |                                                              |             |

## 15. Table: PAXGImplementation\_event\_OwnershipTransferProposed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-08-26 15:37:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8426707                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x46f3b66febad972e251cd6ade571f48ab4e953f160e10864b61c1ee5744294a3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 18                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45804880de22913dafe09f4980848ece6ecbaf78                         | Address of the contract that produced the log                |
| currentOwner      | VARCHAR   | 0x36c2e652a6c774f4c48f6d3ae747c17916aeb537                         |                                                              |
| proposedOwner     | VARCHAR   | 0xb87cec7baa2ce4a055f8563e9cc5a210cedc329f                         |                                                              |

## 16. Table: PAXGImplementation\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-09-05 19:23:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8491908                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5efee23676184eab4424d3d06bde12462f4a565f668083c711641281d964166c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 32                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45804880de22913dafe09f4980848ece6ecbaf78                         | Address of the contract that produced the log                |
| oldOwner          | VARCHAR   | 0x36c2e652a6c774f4c48f6d3ae747c17916aeb537                         |                                                              |
| newOwner          | VARCHAR   | 0xb87cec7baa2ce4a055f8563e9cc5a210cedc329f                         |                                                              |

## 17. Table: PAXGImplementation\_event\_Pause\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-08-26 15:06:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8426561                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0270eeb532bbb7362e98551eaf884b6009ce1f5ff428d6f0d8b95afcda0008f1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 45                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45804880de22913dafe09f4980848ece6ecbaf78                         | Address of the contract that produced the log                |

## 18. Table: PAXGImplementation\_event\_SupplyControllerSet\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2021-03-17 15:58:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 12057138                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x5a48c96522b4e9fbaa75be101b40be2bd940cfc8b1766e8ca54571bb23c5605e | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 249                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x45804880de22913dafe09f4980848ece6ecbaf78                         | Address of the contract that produced the log                |
| oldSupplyController | VARCHAR   | 0x5195427ca88df768c298721da791b93ad11eca65                         |                                                              |
| newSupplyController | VARCHAR   | 0xe25a329d385f77df5d4ed56265babe2b99a5436e                         |                                                              |

## 19. Table: PAXGImplementation\_event\_SupplyDecreased\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-25 14:21:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13487111                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x93603d2433407e2999d98267db7aa859485f7539ddfee60aa09acc5744a0ab2c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 25                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45804880de22913dafe09f4980848ece6ecbaf78                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xe25a329d385f77df5d4ed56265babe2b99a5436e                         |                                                              |
| value             | VARCHAR   | 827151000000000000000                                              |                                                              |

## 20. Table: PAXGImplementation\_event\_SupplyIncreased\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-02-28 13:48:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9572459                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7aaac3251c156fd058abaaea6012b5f078543c67a3897a36831eb2c794914ede | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 53                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45804880de22913dafe09f4980848ece6ecbaf78                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0x5195427ca88df768c298721da791b93ad11eca65                         |                                                              |
| value             | VARCHAR   | 802733000000000000000                                              |                                                              |

## 21. Table: PAXGImplementation\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-29 10:00:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12728322                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd9065874ff8143920761eea00c5fd3f5c7fe6ae0ef578c239f3661460dfb0b55 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 88                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45804880de22913dafe09f4980848ece6ecbaf78                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xd9fc3fe3b78e9bcef72eefeb84ede9561c6a871c                         |                                                              |
| to                | VARCHAR   | 0x38699d04656ff537ef8671b6b595402ebdbdf6f4                         |                                                              |
| value             | VARCHAR   | 5056190530629558                                                   |                                                              |

## 22. Table: PAXGImplementation\_event\_Unpause\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-08-26 15:07:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8426565                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1550aeb0d6e4ac08bd5443bb836fc8b7ee6f457c0d0598d042dbc62a5badf9ee | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45804880de22913dafe09f4980848ece6ecbaf78                         | Address of the contract that produced the log                |

## 23. Table: PAXImplementationV2\_event\_AddressFrozen\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-22 14:57:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15589621                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7611603cacb3631d0db59cdf0d928d14442d27756acccaaa730dc621b5bfbd19 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 481                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8e870d67f660d95d5be530380d0ec0bd388289e1                         | Address of the contract that produced the log                |
| addr              | VARCHAR   | 0xe74b28c2eae8679e3ccc3a94d5d0de83ccb84705                         |                                                              |

## 24. Table: PAXImplementationV2\_event\_AddressUnfrozen\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| addr              | VARCHAR   |                                                              |             |

## 25. Table: PAXImplementationV2\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-08 16:23:35+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16784703                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x086a894bd6968ba59cf1504a976705cd2fd0af31101911d420870db4af45652b             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 186                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8e870d67f660d95d5be530380d0ec0bd388289e1                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x571337e6552032a98315e81933a6ad786a0d8842                                     |                                                              |
| spender           | VARCHAR   | 0x000000000022d473030f116ddee9f6b43ac78ba3                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 26. Table: PAXImplementationV2\_event\_AssetProtectionRoleSet\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2021-05-04 16:53:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 12368946                                                           | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0xc6a5e6145a29b8338e7503d3b0be7f1f30653a576fcefe8024738c336f080640 | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 15                                                                 | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0x8e870d67f660d95d5be530380d0ec0bd388289e1                         | Address of the contract that produced the log                |
| oldAssetProtectionRole | VARCHAR   | 0x87f1aa3037ae65e141cd895dca066db872a94e95                         |                                                              |
| newAssetProtectionRole | VARCHAR   | 0x0644bd0248d5f89e4f6e845a91d15c23591e5d33                         |                                                              |

## 27. Table: PAXImplementationV2\_event\_BetaDelegateUnwhitelisted\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldDelegate       | VARCHAR   |                                                              |             |

## 28. Table: PAXImplementationV2\_event\_BetaDelegateWhitelisted\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newDelegate       | VARCHAR   |                                                              |             |

## 29. Table: PAXImplementationV2\_event\_BetaDelegateWhitelisterSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldWhitelister    | VARCHAR   |                                                              |             |
| newWhitelister    | VARCHAR   |                                                              |             |

## 30. Table: PAXImplementationV2\_event\_BetaDelegatedTransfer\_history

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

## 31. Table: PAXImplementationV2\_event\_FrozenAddressWiped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-16 14:48:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15983281                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x35d1acabf1e832d2d86a36d15842cd164624f58fa7316f7bc97d64a75c341ad2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8e870d67f660d95d5be530380d0ec0bd388289e1                         | Address of the contract that produced the log                |
| addr              | VARCHAR   | 0xe74b28c2eae8679e3ccc3a94d5d0de83ccb84705                         |                                                              |

## 32. Table: PAXImplementationV2\_event\_OwnershipTransferDisregarded\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldProposedOwner  | VARCHAR   |                                                              |             |

## 33. Table: PAXImplementationV2\_event\_OwnershipTransferProposed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-04 16:56:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12368963                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x81ee4702a444849193da143ca2aa9e75e6272fe7b8d2e3c4c3484a6df899bcdf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 19                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8e870d67f660d95d5be530380d0ec0bd388289e1                         | Address of the contract that produced the log                |
| currentOwner      | VARCHAR   | 0xb87cec7baa2ce4a055f8563e9cc5a210cedc329f                         |                                                              |
| proposedOwner     | VARCHAR   | 0x0644bd0248d5f89e4f6e845a91d15c23591e5d33                         |                                                              |

## 34. Table: PAXImplementationV2\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-09-20 20:50:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6368596                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc249f02290b2ce21a7a0963cbb638889aac7ad7e3a058ebe31105c8fde6dc908 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8e870d67f660d95d5be530380d0ec0bd388289e1                         | Address of the contract that produced the log                |
| oldOwner          | VARCHAR   | 0x51e15804cf7ff061410193512b499f071ecf9c4b                         |                                                              |
| newOwner          | VARCHAR   | 0xb87cec7baa2ce4a055f8563e9cc5a210cedc329f                         |                                                              |

## 35. Table: PAXImplementationV2\_event\_Pause\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 36. Table: PAXImplementationV2\_event\_SupplyControllerSet\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2018-10-23 07:56:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 6567468                                                            | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x44fa2191dcba56c5fa39ea7a884c5f43156ad7e6ce4d0293fa02a6edaffbf383 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 49                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x8e870d67f660d95d5be530380d0ec0bd388289e1                         | Address of the contract that produced the log                |
| oldSupplyController | VARCHAR   | 0xcba1766e19f32d79e3ba7a2764f04a7042324f0a                         |                                                              |
| newSupplyController | VARCHAR   | 0x5195427ca88df768c298721da791b93ad11eca65                         |                                                              |

## 37. Table: PAXImplementationV2\_event\_SupplyDecreased\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-14 02:57:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10857575                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0304d205f252e5e5238f77a579b5b1be499a7f56c33619a81e3c727e16a8dac4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 101                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8e870d67f660d95d5be530380d0ec0bd388289e1                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x5195427ca88df768c298721da791b93ad11eca65                         |                                                              |
| value             | VARCHAR   | 1348859290000000000000000                                          |                                                              |

## 38. Table: PAXImplementationV2\_event\_SupplyIncreased\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-05-23 17:03:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7817187                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9d45bf5d0aa45b7845dae2ab5d2443fd78ed581feff985c9ad18c779eab92a90 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 55                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8e870d67f660d95d5be530380d0ec0bd388289e1                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0x5195427ca88df768c298721da791b93ad11eca65                         |                                                              |
| value             | VARCHAR   | 779574560000000000000000                                           |                                                              |

## 39. Table: PAXImplementationV2\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-19 12:27:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14990773                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe6d08c255822fbe8d3a32faec1a5bd760f53c83829bb00ae223fc7d51731181f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 199                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8e870d67f660d95d5be530380d0ec0bd388289e1                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xc88f7666330b4b511358b7742dc2a3234710e7b1                         |                                                              |
| to                | VARCHAR   | 0x5e609007ee00f23bd0d8fda9d8216c52b9c1c7c5                         |                                                              |
| value             | VARCHAR   | 9533725757930000000000                                             |                                                              |

## 40. Table: PAXImplementationV2\_event\_Unpause\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 41. Table: USDPImplementationV3\_event\_AddressFrozen\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-11-29 18:19:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6795733                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcb4218963d6edf343b4b3d37ea710b247ed1168c448b785d410774571b6bbf7a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 27                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8e870d67f660d95d5be530380d0ec0bd388289e1                         | Address of the contract that produced the log                |
| addr              | VARCHAR   | 0x8e870d67f660d95d5be530380d0ec0bd388289e1                         |                                                              |

## 42. Table: USDPImplementationV3\_event\_AddressUnfrozen\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| addr              | VARCHAR   |                                                              |             |

## 43. Table: USDPImplementationV3\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-06 06:26:48+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12579291                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1d3254c6f0eedde845384dcfd2235e83829ec6f6f9d934f1ea1d413aebeedcfe             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 185                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8e870d67f660d95d5be530380d0ec0bd388289e1                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x9b3f49a186670194f625199b822fcbdfd3feacf7                                     |                                                              |
| spender           | VARCHAR   | 0x06364f10b501e868329afbc005b3492902d6c763                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 44. Table: USDPImplementationV3\_event\_AssetProtectionRoleSet\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2021-05-04 16:53:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 12368946                                                           | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0xc6a5e6145a29b8338e7503d3b0be7f1f30653a576fcefe8024738c336f080640 | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 15                                                                 | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0x8e870d67f660d95d5be530380d0ec0bd388289e1                         | Address of the contract that produced the log                |
| oldAssetProtectionRole | VARCHAR   | 0x87f1aa3037ae65e141cd895dca066db872a94e95                         |                                                              |
| newAssetProtectionRole | VARCHAR   | 0x0644bd0248d5f89e4f6e845a91d15c23591e5d33                         |                                                              |

## 45. Table: USDPImplementationV3\_event\_FrozenAddressWiped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-16 14:48:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15983281                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x35d1acabf1e832d2d86a36d15842cd164624f58fa7316f7bc97d64a75c341ad2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8e870d67f660d95d5be530380d0ec0bd388289e1                         | Address of the contract that produced the log                |
| addr              | VARCHAR   | 0xe74b28c2eae8679e3ccc3a94d5d0de83ccb84705                         |                                                              |

## 46. Table: USDPImplementationV3\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-09-20 20:50:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6368596                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc249f02290b2ce21a7a0963cbb638889aac7ad7e3a058ebe31105c8fde6dc908 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8e870d67f660d95d5be530380d0ec0bd388289e1                         | Address of the contract that produced the log                |
| oldOwner          | VARCHAR   | 0x51e15804cf7ff061410193512b499f071ecf9c4b                         |                                                              |
| newOwner          | VARCHAR   | 0xb87cec7baa2ce4a055f8563e9cc5a210cedc329f                         |                                                              |

## 47. Table: USDPImplementationV3\_event\_Pause\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 48. Table: USDPImplementationV3\_event\_SupplyControllerSet\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2018-09-09 19:28:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 6301747                                                            | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xfbc52f6787d74511624fce3bf691e43390cee9ce41c1862919722c0179b6ab86 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 32                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x8e870d67f660d95d5be530380d0ec0bd388289e1                         | Address of the contract that produced the log                |
| oldSupplyController | VARCHAR   | 0x51e15804cf7ff061410193512b499f071ecf9c4b                         |                                                              |
| newSupplyController | VARCHAR   | 0x5195427ca88df768c298721da791b93ad11eca65                         |                                                              |

## 49. Table: USDPImplementationV3\_event\_SupplyDecreased\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-02-03 05:57:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7167136                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf183b35faef7bc14e13be27aeb169d405af1098761942ee8e105d861ad0672c8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 85                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8e870d67f660d95d5be530380d0ec0bd388289e1                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x5195427ca88df768c298721da791b93ad11eca65                         |                                                              |
| value             | VARCHAR   | 448119420000000000000000                                           |                                                              |

## 50. Table: USDPImplementationV3\_event\_SupplyIncreased\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-02 21:54:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16543927                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7702bd912eaf0d576320928352be409d5a1e713348cd38c67ba516435800321e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 61                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8e870d67f660d95d5be530380d0ec0bd388289e1                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0xe25a329d385f77df5d4ed56265babe2b99a5436e                         |                                                              |
| value             | VARCHAR   | 3594033230000000000000000                                          |                                                              |

## 51. Table: USDPImplementationV3\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-12 21:39:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16171361                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x75e19cdf830f6f74a16a59eecca2868ce486342e80854905c28dec2414d0cc1d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 318                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8e870d67f660d95d5be530380d0ec0bd388289e1                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xab4c461429e318b6840c0d821da0e9928f98548d                         |                                                              |
| to                | VARCHAR   | 0x254890d08aaa8056cb5a430cbdb9fa43ae336aca                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 52. Table: USDPImplementationV3\_event\_Unpause\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
