# multis

## 1. Table: GSNMultiSigWalletWithDailyLimit\_event\_Confirmation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-07 20:17:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13960409                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd8687264f502b74c7224536228559c86789e1b9b0a2867c0f55b0ac271373620 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 45                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6ed4d595358a0451d71f7e98980c407d079b43c1                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xe993486b257cd1481aef74b3b909a2627fc8d305                         |                                                              |
| transactionId     | VARCHAR   | 138                                                                |                                                              |

## 2. Table: GSNMultiSigWalletWithDailyLimit\_event\_DailyLimitChange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-03 05:02:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9797019                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8642e46027974ab52351188ed094f77df0f4e8efcc28e9602092892bb056aaf0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 213                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf945442c378217c4de525c2db5e218d5186edaaf                         | Address of the contract that produced the log                |
| dailyLimit        | VARCHAR   | 15000000000000000000                                               |                                                              |

## 3. Table: GSNMultiSigWalletWithDailyLimit\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-06 05:15:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10403930                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb0079bc5bff8e91d42dee3881708fb6c624f52d97bda937436e25fbb7eea03fc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 30                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb65735084e3b3820745673384c82214dfbdd92c1                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xcdeaddd3d131cf88c55d31ba978e0f059f2b158d                         |                                                              |
| value             | VARCHAR   | 5490995000000000000                                                |                                                              |

## 4. Table: GSNMultiSigWalletWithDailyLimit\_event\_ExecutionFailure\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-26 21:27:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11935279                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xec454f1635cc92a6b70120c760873d394af84bb1e480daad0c693b74ed553fcf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 110                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf22c2e3475e4a066f4e9f44567c950dd36112d05                         | Address of the contract that produced the log                |
| transactionId     | VARCHAR   | 70                                                                 |                                                              |

## 5. Table: GSNMultiSigWalletWithDailyLimit\_event\_Execution\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-07 13:36:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12978239                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xebb67417e7d52c2f5218af967f7e507cbbedb2d6c594308bc2a205ca5cdf8203 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 39                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6ed4d595358a0451d71f7e98980c407d079b43c1                         | Address of the contract that produced the log                |
| transactionId     | VARCHAR   | 119                                                                |                                                              |

## 6. Table: GSNMultiSigWalletWithDailyLimit\_event\_OwnerAddition\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-06 21:12:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10015025                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x826a6509f0a1e34934c29bba64f26332034d859d2899dd161079fdd23625d1e7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcaaa1e32bca3be0f93bff40dbcec33f1f390ae3f                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xbfbcd35a42660200ccd82e1f9e68c1e89ffa5dcf                         |                                                              |

## 7. Table: GSNMultiSigWalletWithDailyLimit\_event\_OwnerRemoval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-28 08:28:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15426753                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe53e260afdd336755d96cf4bda3b5b60299638f95f6e4e25309f7d49482d0dc2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x77fd00aa38e6f0322ef98d72c04f7f6500bb2f3e                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xc003170af17eb17fce55a9cef5c799e92532005e                         |                                                              |

## 8. Table: GSNMultiSigWalletWithDailyLimit\_event\_RelayHubChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-22 17:58:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10117102                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xace884e7f1ee54dd155fb30367c5f3e243e4f5bd9a4b4d80577410a2148223c7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 55                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x580dc61b7f74042617ed95aae72cfbbc69f7cddc                         | Address of the contract that produced the log                |
| oldRelayHub       | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newRelayHub       | VARCHAR   | 0xd216153c06e857cd7f72665e0af1d7d82172f494                         |                                                              |

## 9. Table: GSNMultiSigWalletWithDailyLimit\_event\_RequirementChange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-22 10:21:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10508625                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5ffc5011370665a66baf871e772915b56a50abd6f40417660aab918ecb48a67d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 150                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x77fd00aa38e6f0322ef98d72c04f7f6500bb2f3e                         | Address of the contract that produced the log                |
| required          | VARCHAR   | 2                                                                  |                                                              |

## 10. Table: GSNMultiSigWalletWithDailyLimit\_event\_Revocation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-19 15:38:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9903730                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2da1c460a315a30cbe41808fe08af95ee0bd7e1355da7575ae616d11a8eaedae | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x222f980ae15253740dd5c568ccab89f6f246b5d4                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xf385aa5455cfdde43d16d149eaf6cf93a886b5ea                         |                                                              |
| transactionId     | VARCHAR   | 3                                                                  |                                                              |

## 11. Table: GSNMultiSigWalletWithDailyLimit\_event\_Submission\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-30 09:48:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10366361                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x850c40c69596d8d886c30e9c56ef5d21eb20c3966ebb18e61c95be8ad34a0ee3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 58                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcdec88ca8854fc98fc4c120519572434c95ce360                         | Address of the contract that produced the log                |
| transactionId     | VARCHAR   | 2                                                                  |                                                              |

## 12. Table: GSNMultisigFactory\_event\_ContractInstantiation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-28 18:06:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9761523                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x722ac0e6c79100e5a33aaa600e6ee56974311283ea30f64a9e52a6d4c853fb32 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 27                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x16154f7e9de01e6b39dac3159805e9b1531ee3cf                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x890b70ecebd0bc879e289bea5ae2328a83993062                         |                                                              |
| instantiation     | VARCHAR   | 0x6e02942eb227f3625ce89d68a029706536dfcb68                         |                                                              |

## 13. Table: GSNMultisigFactory\_event\_MinterAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-10 10:27:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9252472                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x732ed4c3dfb33d5e3d023a0a235ca02fa05c05f999750b995affa483dc71becd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 116                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x16154f7e9de01e6b39dac3159805e9b1531ee3cf                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xe0184667f02f5d9210123be7f279ed7c67c3c54a                         |                                                              |

## 14. Table: GSNMultisigFactory\_event\_MinterRemoved\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |

## 15. Table: GSNMultisigFactory\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-10 10:27:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9252472                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x732ed4c3dfb33d5e3d023a0a235ca02fa05c05f999750b995affa483dc71becd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 117                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x16154f7e9de01e6b39dac3159805e9b1531ee3cf                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0xe0184667f02f5d9210123be7f279ed7c67c3c54a                         |                                                              |

## 16. Table: GSNMultisigFactory\_event\_RelayHubChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-10 10:27:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9252472                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x732ed4c3dfb33d5e3d023a0a235ca02fa05c05f999750b995affa483dc71becd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 115                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x16154f7e9de01e6b39dac3159805e9b1531ee3cf                         | Address of the contract that produced the log                |
| oldRelayHub       | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newRelayHub       | VARCHAR   | 0xd216153c06e857cd7f72665e0af1d7d82172f494                         |                                                              |
