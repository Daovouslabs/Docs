# common

## 1. Table: All\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-14 04:32:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7014952                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3ecdd35d968481e96b500a7b236c459d4119f0a67482841078bc51b1ef407d7c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1f1e4c845183ef6d50e9609f16f6f9cae43bc9cb                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x0b22380b7c423470979ac3ed7d3c07696773dea1                         |                                                              |
| spender           | VARCHAR   | 0x05748fd0d03780637a85df5b2293ce857c1fa309                         |                                                              |
| value             | VARCHAR   | 44456859213687                                                     |                                                              |

## 2. Table: All\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-09 11:11:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5518803                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1966574e76301ecee337a9f288463b4b47b77d407e17f4a2976a09a513bbe0bb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         | Address of the contract that produced the log                |
| dst               | VARCHAR   | 0x5625ff6c4716efd2a35cf17c8c2694ca16939506                         |                                                              |
| wad               | VARCHAR   | 40000000000000000000                                               |                                                              |

## 3. Table: All\_event\_MetaTransactionExecuted\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-10 16:24:19+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 34174848                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb40aa781d389abe153cb7838dc3e586ce92f0baa09bf3f36024d5271107e2409                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 349                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc2132d05d31c914a87c6611c10748aeb04b58e8f                                                           | Address of the contract that produced the log                |
| userAddress       | VARCHAR   | 0xf1a908db202b0f76320ddcfa27ba87e55c4388db                                                           |                                                              |
| relayerAddress    | VARCHAR   | 0x000007e0510d26571d6996491c8edadfa5679311                                                           |                                                              |
| functionSignature | VARCHAR   | 0x095ea7b300000000000000000000000014dc79964da2c08b23698b3d3cc7ca32193d995500000000000000000000000000 |                                                              |

## 4. Table: All\_event\_TransferBatch\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-13 04:09:39+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10791822                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa227c128afa209b3c727bfa9f4842731fd06606f2c092132446f5db8c759795b                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 33                                                                                                   | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4d97dcd97ec945f40cf65f87097ace5ea0476045                                                           | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0x0361bdb04c9a2d36a5ddea28940708d541210e9a                                                           |                                                              |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                                                           |                                                              |
| to                | VARCHAR   | 0x0361bdb04c9a2d36a5ddea28940708d541210e9a                                                           |                                                              |
| ids               | VARCHAR   | 64260092556571579981301207468660817298136182811186187107824732088006168495706,4912333117721643345465 |                                                              |
| values            | VARCHAR   | 2058000,2058000                                                                                      |                                                              |

## 5. Table: All\_event\_TransferSingle\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-27 15:58:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6280923                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x30cc397a7a7e136a52bc677c421f89c44f6be02b0d6a8f0790a792c24e6711a8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5ebdbc8174da2bdbedfdb6dcf43dd79d12910a2c                         | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0xbd8ea13981ded8038224e9c32607131ac3d8492d                         |                                                              |
| from              | VARCHAR   | 0xbd8ea13981ded8038224e9c32607131ac3d8492d                         |                                                              |
| to                | VARCHAR   | 0xc77c5126a3aed8ae2526e01414fefd6abe56cadb                         |                                                              |
| id                | VARCHAR   | 2                                                                  |                                                              |
| value             | VARCHAR   | 50000000000000000000                                               |                                                              |

## 6. Table: All\_event\_Withdrawal\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-09 20:31:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10653719                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x08235cc9498fc99fa1baeb68b9d8166d9603f14d87548dd8906fcbc91a22b0c2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x084666322d3ee89aabdbbcd084323c9af705c7f5                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0x193919f422a262b1edfd8ca2776b8cfb000bdd3d                         |                                                              |
| wad               | VARCHAR   | 4291500818852203017                                                |                                                              |
