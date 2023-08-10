# totle

## 1. Table: Light\_event\_CancelUpTo\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| nonce             | VARCHAR   |                                                              |             |
| signerWallet      | VARCHAR   |                                                              |             |

## 2. Table: Light\_event\_Cancel\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| nonce             | VARCHAR   |                                                              |             |
| signerWallet      | VARCHAR   |                                                              |             |

## 3. Table: Light\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-31 10:51:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11763362                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3e9ce498f5fd79dd98eb39c492ebbfe5d9008d35bca35d775643ea98e8d2e66d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 97                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc50cb225e0f45e814fd41bcb3a120463ab1f04c3                         | Address of the contract that produced the log                |
| nonce             | VARCHAR   | 1612090187                                                         |                                                              |
| timestamp         | VARCHAR   | 1612090269                                                         |                                                              |
| signerWallet      | VARCHAR   | 0xa5d07e978398eb1715056d3ca5cb31035c02fdad                         |                                                              |
| senderWallet      | VARCHAR   | 0x74de5d4fcbf63e00296fd95d33236b9794016631                         |                                                              |
| signerToken       | VARCHAR   | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599                         |                                                              |
| senderToken       | VARCHAR   | 0xdac17f958d2ee523a2206206994597c13d831ec7                         |                                                              |
| signerAmount      | VARCHAR   | 1271362                                                            |                                                              |
| senderAmount      | VARCHAR   | 430000000                                                          |                                                              |

## 4. Table: TotlePrimary\_0x3179\_event\_LogSwapCollection\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-09-18 05:02:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8571419                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x88e86c8e038c7a7b3b963021c7a2a55825b1bb5ca02b6e86b9c17a0d5bb1046e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 81                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3179e4cd7ff08eb14397e1c402d0de44e1523f2e                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 0xb27c6cf6fc2c44f582f9a73ca601aee89b8b8a48e6734311b08c15af6de33d1c |                                                              |
| partnerContract   | VARCHAR   | 0x027b73a7e03e66bec20ae43df1813d960aef779d                         |                                                              |
| user              | VARCHAR   | 0x3207d6637fb1cda2eec9ec1f5cc2220d251f637c                         |                                                              |

## 5. Table: TotlePrimary\_0x3179\_event\_LogSwap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-09-11 20:47:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8530716                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6bddb6fa51caa44f46523afb44de1a68db95c13efe832b3a34884dd532f3a2e4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 43                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3179e4cd7ff08eb14397e1c402d0de44e1523f2e                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 0xe2e0453f43ae4e34a3157eefad7834682abf461a088145918de0e90d977bac50 |                                                              |
| sourceAsset       | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| destinationAsset  | VARCHAR   | 0x89d24a6b4ccb1b6faa2625fe562bdd9a23260359                         |                                                              |
| sourceAmount      | VARCHAR   | 200000000000000000                                                 |                                                              |
| destinationAmount | VARCHAR   | 34656278640292798395                                               |                                                              |
| feeAsset          | VARCHAR   | 0x89d24a6b4ccb1b6faa2625fe562bdd9a23260359                         |                                                              |
| feeAmount         | VARCHAR   | 174152153971320594                                                 |                                                              |

## 6. Table: TotlePrimary\_0x3179\_event\_Log\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| a                 | VARCHAR   |                                                              |             |
| b                 | VARCHAR   |                                                              |             |
| c                 | VARCHAR   |                                                              |             |

## 7. Table: TotlePrimary\_0x3179\_event\_OwnershipRenounced\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner     | VARCHAR   |                                                              |             |

## 8. Table: TotlePrimary\_0x3179\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner     | VARCHAR   |                                                              |             |
| newOwner          | VARCHAR   |                                                              |             |

## 9. Table: TotlePrimary\_0x3179\_event\_Paused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 10. Table: TotlePrimary\_0x3179\_event\_Unpaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 11. Table: TotlePrimary\_0x7720\_event\_LogSwapCollection\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-02 16:40:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10187521                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa10e0e33cc52f240cdcbc4801c068a360ebd3ede3f2a97a2ca9a59da5219dea6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 88                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x77208a6000691e440026bed1b178ef4661d37426                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 0xb8c68afb01e34ea39c313fb976fe881a736fe2c275c7483691e45f0087515ddf |                                                              |
| partnerContract   | VARCHAR   | 0x627db0690c4729c36cef22beb4648a440548510c                         |                                                              |
| user              | VARCHAR   | 0x0b8d3e5c4768eeae8168bf6c9baa9f6429ee3d5a                         |                                                              |

## 12. Table: TotlePrimary\_0x7720\_event\_LogSwap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-22 22:46:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10118410                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2e0ffc4731da709d3230d2aae6a95eb37017e5285b287f593b7ebffc19f5d3ec | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 96                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x77208a6000691e440026bed1b178ef4661d37426                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 0x30f84efbf2e94e2886dd63cb10f505bbaa68078e0c344676b083d3e2c6e3c507 |                                                              |
| sourceAsset       | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| destinationAsset  | VARCHAR   | 0xdac17f958d2ee523a2206206994597c13d831ec7                         |                                                              |
| sourceAmount      | VARCHAR   | 80000000000000000                                                  |                                                              |
| destinationAmount | VARCHAR   | 16495659                                                           |                                                              |
| feeAsset          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| feeAmount         | VARCHAR   | 800000000000000                                                    |                                                              |

## 13. Table: TotlePrimary\_0x7720\_event\_OwnershipRenounced\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner     | VARCHAR   |                                                              |             |

## 14. Table: TotlePrimary\_0x7720\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner     | VARCHAR   |                                                              |             |
| newOwner          | VARCHAR   |                                                              |             |

## 15. Table: TotlePrimary\_0x7720\_event\_Paused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 16. Table: TotlePrimary\_0x7720\_event\_Unpaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 17. Table: TotlePrimary\_v2\_event\_LogSwapCollection\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-06-29 10:54:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8052350                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb79a9f57f2cece388fc05a63d5146acff4841603eb6f9004077d01889e281122 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 61                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x623520377f092c1c70bd57d17ae9ede6a288412c                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 0x5871f357ef914197b83880d786d78820a1f2c8bcd1a54d98a7b89061a9605415 |                                                              |
| partnerContract   | VARCHAR   | 0x103814878dc77737ed687c9e2e71fd59b497afbf                         |                                                              |
| user              | VARCHAR   | 0xd262d146e869915444d0f34ecdaabab5ab43007e                         |                                                              |

## 18. Table: TotlePrimary\_v2\_event\_LogSwap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-06-29 10:54:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8052350                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb79a9f57f2cece388fc05a63d5146acff4841603eb6f9004077d01889e281122 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 56                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x623520377f092c1c70bd57d17ae9ede6a288412c                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 0x5871f357ef914197b83880d786d78820a1f2c8bcd1a54d98a7b89061a9605415 |                                                              |
| sourceAsset       | VARCHAR   | 0xd26114cd6ee289accf82350c8d8487fedb8a0c07                         |                                                              |
| destinationAsset  | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| sourceAmount      | VARCHAR   | 2566076492254211400                                                |                                                              |
| destinationAmount | VARCHAR   | 22722342194563322                                                  |                                                              |
| feeAsset          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| feeAmount         | VARCHAR   | 113611710972816                                                    |                                                              |

## 19. Table: TotlePrimary\_v2\_event\_Log\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-06-24 20:06:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8022787                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xda1eff645191c90b45b93b2e381d2cac175c29a16f7ac779308d7832f16d8a6b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 16                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x623520377f092c1c70bd57d17ae9ede6a288412c                         | Address of the contract that produced the log                |
| a                 | VARCHAR   | Created eth balance                                                |                                                              |
| b                 | VARCHAR   | 0                                                                  |                                                              |
| c                 | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000 |                                                              |

## 20. Table: TotlePrimary\_v2\_event\_OwnershipRenounced\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner     | VARCHAR   |                                                              |             |

## 21. Table: TotlePrimary\_v2\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner     | VARCHAR   |                                                              |             |
| newOwner          | VARCHAR   |                                                              |             |

## 22. Table: TotlePrimary\_v2\_event\_Paused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 23. Table: TotlePrimary\_v2\_event\_Unpaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 24. Table: TotlePrimary\_v3\_event\_LogSwapCollection\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-07-18 18:50:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8176407                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbeb732ef64ffbf9e0be088e272e69aed92a64f3b01526c694d2d255752a94a57 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 97                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcd2053679de3bcf2b7e2c2efb6b499c57701222c                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 0xd35be63139134fd8b35f66fdb37290410fb5967148c54db8aad6b5898df18b0d |                                                              |
| partnerContract   | VARCHAR   | 0x5073e4821012fc43efef95c06c8ae6a104c5fd7a                         |                                                              |
| user              | VARCHAR   | 0xf4fc5c29304397f4ee4873fbad80852726baf8d0                         |                                                              |

## 25. Table: TotlePrimary\_v3\_event\_LogSwap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-07-05 23:19:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8094151                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x12addb022663045aabb24844aacaaae6d042f5d0821f56645d429477c0d25f91 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 83                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcd2053679de3bcf2b7e2c2efb6b499c57701222c                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 0xf1814958ee2b4fb58c28ab6109d380d23a870ba8793a46218e7545f032a3e857 |                                                              |
| sourceAsset       | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| destinationAsset  | VARCHAR   | 0x89d24a6b4ccb1b6faa2625fe562bdd9a23260359                         |                                                              |
| sourceAmount      | VARCHAR   | 5000000000000000                                                   |                                                              |
| destinationAmount | VARCHAR   | 1450551233400882012                                                |                                                              |
| feeAsset          | VARCHAR   | 0x89d24a6b4ccb1b6faa2625fe562bdd9a23260359                         |                                                              |
| feeAmount         | VARCHAR   | 8703307400405292                                                   |                                                              |

## 26. Table: TotlePrimary\_v3\_event\_Log\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-07-08 21:04:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8112934                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x69256a9d87bda5205ce6e23198c505f512f7eb5a5cee0ea8d2fb7e123d4cca66 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 15                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcd2053679de3bcf2b7e2c2efb6b499c57701222c                         | Address of the contract that produced the log                |
| a                 | VARCHAR   | Created eth balance                                                |                                                              |
| b                 | VARCHAR   | 0                                                                  |                                                              |
| c                 | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000 |                                                              |

## 27. Table: TotlePrimary\_v3\_event\_OwnershipRenounced\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner     | VARCHAR   |                                                              |             |

## 28. Table: TotlePrimary\_v3\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner     | VARCHAR   |                                                              |             |
| newOwner          | VARCHAR   |                                                              |             |

## 29. Table: TotlePrimary\_v3\_event\_Paused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 30. Table: TotlePrimary\_v3\_event\_Unpaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 31. Table: TotlePrimary\_v4\_event\_LogSwapCollection\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-01 16:58:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8853823                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x245a7d087dbd7f1a5440476f4ebaf4dec08aced4e31f08a8886ad9fe807284c8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 135                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x37629db35889e1e87dcee07b171efd565e571e05                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 0xbed39462a2cf41eabe69ab0b87614f18ee88c487a2804dd684c9465b724a37a8 |                                                              |
| partnerContract   | VARCHAR   | 0xd53799e6f0728fdfb56b746dcd7b75dfcb422d74                         |                                                              |
| user              | VARCHAR   | 0xec3281124d4c2fca8a88e3076c1e7749cfecb7f2                         |                                                              |

## 32. Table: TotlePrimary\_v4\_event\_LogSwap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-06 14:19:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8884332                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x59a8b59e277be10f4b6006acd67a8a3d6e0d26ae77e7311820a17c875592cdfc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 173                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x37629db35889e1e87dcee07b171efd565e571e05                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 0xee75792903a244acb867491ad560b3113a2987c3bb7c426585445b40f56e4897 |                                                              |
| sourceAsset       | VARCHAR   | 0x89d24a6b4ccb1b6faa2625fe562bdd9a23260359                         |                                                              |
| destinationAsset  | VARCHAR   | 0x14094949152eddbfcd073717200da82fed8dc960                         |                                                              |
| sourceAmount      | VARCHAR   | 10000000000000000                                                  |                                                              |
| destinationAmount | VARCHAR   | 9696267938354747                                                   |                                                              |
| feeAsset          | VARCHAR   | 0x14094949152eddbfcd073717200da82fed8dc960                         |                                                              |
| feeAmount         | VARCHAR   | 24301423404397                                                     |                                                              |

## 33. Table: TotlePrimary\_v4\_event\_Log\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| a                 | VARCHAR   |                                                              |             |
| b                 | VARCHAR   |                                                              |             |
| c                 | VARCHAR   |                                                              |             |

## 34. Table: TotlePrimary\_v4\_event\_OwnershipRenounced\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner     | VARCHAR   |                                                              |             |

## 35. Table: TotlePrimary\_v4\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner     | VARCHAR   |                                                              |             |
| newOwner          | VARCHAR   |                                                              |             |

## 36. Table: TotlePrimary\_v4\_event\_Paused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 37. Table: TotlePrimary\_v4\_event\_Unpaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 38. Table: TotlePrimary\_v5\_event\_LogSwapCollection\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-30 20:39:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9028671                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdb9d4733d731a827b469c123a099108bf4e309c3c6ca3ffa5538569bfeb595b8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 124                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc755af998e8c50d6df1779ce3d7e4084a17b4c56                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 0xdc074d883d484fe684161ef299b9470d6135f38036bb414d9d59144fb01972ee |                                                              |
| partnerContract   | VARCHAR   | 0x027b73a7e03e66bec20ae43df1813d960aef779d                         |                                                              |
| user              | VARCHAR   | 0x33d6cba4177ad8c8f00a5798197686f3d388399d                         |                                                              |

## 39. Table: TotlePrimary\_v5\_event\_LogSwap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-28 20:57:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9017448                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x60be148a4f7b25cde56f066cee27ac5cc3d5bbd47a8be00ac76e311b41ecf2f6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 177                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc755af998e8c50d6df1779ce3d7e4084a17b4c56                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 0x1e95a4e9c626499eaaaf4c5fa33f42e792a228d94823475aab28e6066195611b |                                                              |
| sourceAsset       | VARCHAR   | 0x89d24a6b4ccb1b6faa2625fe562bdd9a23260359                         |                                                              |
| destinationAsset  | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         |                                                              |
| sourceAmount      | VARCHAR   | 996736590456447789931                                              |                                                              |
| destinationAmount | VARCHAR   | 986030636897707027138                                              |                                                              |
| feeAsset          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| feeAmount         | VARCHAR   | 64969236755610555                                                  |                                                              |

## 40. Table: TotlePrimary\_v5\_event\_Log\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| a                 | VARCHAR   |                                                              |             |
| b                 | VARCHAR   |                                                              |             |
| c                 | VARCHAR   |                                                              |             |

## 41. Table: TotlePrimary\_v5\_event\_OwnershipRenounced\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner     | VARCHAR   |                                                              |             |

## 42. Table: TotlePrimary\_v5\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner     | VARCHAR   |                                                              |             |
| newOwner          | VARCHAR   |                                                              |             |

## 43. Table: TotlePrimary\_v5\_event\_Paused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 44. Table: TotlePrimary\_v5\_event\_Unpaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 45. Table: TotlePrimary\_v6\_event\_LogSwapCollection\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-02-03 19:48:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9411587                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x97475bbff3505693be6c77e70c56c293fa94caf4ea5ea11887471df7229ffd0c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 49                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3b21d6d25e7f036c8277efe9a7ebf17ca12fe4f6                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 0x02f699946c344140b1bb7f60490f91bb80405ad5747c45feab27411453c8487d |                                                              |
| partnerContract   | VARCHAR   | 0x027b73a7e03e66bec20ae43df1813d960aef779d                         |                                                              |
| user              | VARCHAR   | 0xb304ac728f4404f45ab6bf5c3dbfc96cdfa1270e                         |                                                              |

## 46. Table: TotlePrimary\_v6\_event\_LogSwap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-17 12:27:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9298734                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb058b96399997dc43f64acebeca35ec74c87a009dfecc419c855b9de28c57d1d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 39                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3b21d6d25e7f036c8277efe9a7ebf17ca12fe4f6                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 0x734b5b9eb6c6412884f64077c066ed5d75aa7fb9802e44ef804d62de558f05bb |                                                              |
| sourceAsset       | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         |                                                              |
| destinationAsset  | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| sourceAmount      | VARCHAR   | 340000000000000000000                                              |                                                              |
| destinationAmount | VARCHAR   | 1994784876140808344                                                |                                                              |
| feeAsset          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| feeAmount         | VARCHAR   | 20149342183240488                                                  |                                                              |

## 47. Table: TotlePrimary\_v6\_event\_Log\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| a                 | VARCHAR   |                                                              |             |
| b                 | VARCHAR   |                                                              |             |
| c                 | VARCHAR   |                                                              |             |

## 48. Table: TotlePrimary\_v6\_event\_OwnershipRenounced\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner     | VARCHAR   |                                                              |             |

## 49. Table: TotlePrimary\_v6\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner     | VARCHAR   |                                                              |             |
| newOwner          | VARCHAR   |                                                              |             |

## 50. Table: TotlePrimary\_v6\_event\_Paused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 51. Table: TotlePrimary\_v6\_event\_Unpaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 52. Table: TotlePrimary\_v7\_event\_LogSwapCollection\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-05 01:08:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11194146                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7000f9e3c42d11e470c2fffc1b01436ebd042a83d3c914b49aaafde2efd1ec7e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 241                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7113dd99c79aff93d54cfa4b2885576535a132de                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 0x859a2764c44a45f5a272273fe8ef9ceb234b4eed48f049f2806538fcacaf8d2b |                                                              |
| partnerContract   | VARCHAR   | 0x1a4b11ae4e3142e36b71c6981dfbcdee7aa52b7a                         |                                                              |
| user              | VARCHAR   | 0x4d4f4d24268e661e00934fb438126d809d15c911                         |                                                              |

## 53. Table: TotlePrimary\_v7\_event\_LogSwap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-20 08:34:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11489147                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa9ea4ac9cf5a96af08ef5c1ed363752a1d9aff779f13fbccd2d818df6b9fb61e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 127                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7113dd99c79aff93d54cfa4b2885576535a132de                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 0x16ef27ace8564e7c9efc0b03eafc46aaf8747118ba864da8a7374dae9b7592f9 |                                                              |
| sourceAsset       | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| destinationAsset  | VARCHAR   | 0xd46ba6d942050d489dbd938a2c909a5d5039a161                         |                                                              |
| sourceAmount      | VARCHAR   | 3700000000000000000                                                |                                                              |
| destinationAmount | VARCHAR   | 2695652854215                                                      |                                                              |
| feeAsset          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| feeAmount         | VARCHAR   | 0                                                                  |                                                              |

## 54. Table: TotlePrimary\_v7\_event\_OwnershipRenounced\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner     | VARCHAR   |                                                              |             |

## 55. Table: TotlePrimary\_v7\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner     | VARCHAR   |                                                              |             |
| newOwner          | VARCHAR   |                                                              |             |

## 56. Table: TotlePrimary\_v7\_event\_Paused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 57. Table: TotlePrimary\_v7\_event\_Unpaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
