# ethblocks

## 1. Table: EthBlocks\_event\_ApprovalForAll\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-31 19:41:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15252200                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe960ab768486c8cdf3d234d63868c811ffbe329b5f4356171b802eba91d2e480 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 332                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x01234567bac6ff94d7e4f0ee23119cf848f93245                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x0681dc49d28d3d057bd275a748918ed10a0d8d6e                         |                                                              |
| operator          | VARCHAR   | 0x1e0049783f008a0085193e00003d00cd54003c71                         |                                                              |
| approved          | VARCHAR   | true                                                               |                                                              |

## 2. Table: EthBlocks\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-11 20:45:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17239502                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd0dafd6b0c752d2f16d6c2e73a11f52eb7b1ccad7c3c13033f2282ab904e96cd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 255                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x01234567bac6ff94d7e4f0ee23119cf848f93245                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x3e4335ad4947459bc364ce6f55de14e9c5bf3f40                         |                                                              |
| approved          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| tokenId           | VARCHAR   | 15998797                                                           |                                                              |

## 3. Table: EthBlocks\_event\_MetaTransactionExecuted\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| userAddress       | VARCHAR   |                                                              |             |
| relayerAddress    | VARCHAR   |                                                              |             |
| functionSignature | VARCHAR   |                                                              |             |

## 4. Table: EthBlocks\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-01 21:42:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13533653                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb9fbb886920ee594f6bb068be7425af7071bd1fe2e64bf191f5be9b86e89d05e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 183                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x01234567bac6ff94d7e4f0ee23119cf848f93245                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0xbfa50979dcc96d526cf2f776c1da894dc74b2dcf                         |                                                              |

## 5. Table: EthBlocks\_event\_RoyaltiesSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-26 09:39:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13880049                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd499d58fc57aff86de2fef87217b734bfdb50762ea6b886d63d9e078ebda7de9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 471                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x01234567bac6ff94d7e4f0ee23119cf848f93245                         | Address of the contract that produced the log                |
| tokenId           | VARCHAR   | 1527                                                               |                                                              |
| royalties         | VARCHAR   | 0xd28F5C5E6de83DDDf9B96F4F115763575DB86e9E,250                     |                                                              |

## 6. Table: EthBlocks\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-14 17:39:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14386145                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x94be2d12bd920bb19e3b298ad85152d8acdbf2b8a54572e0788664cd552f8541 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 525                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x01234567bac6ff94d7e4f0ee23119cf848f93245                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x087afb595816c955d10b03785b558b6257434a32                         |                                                              |
| tokenId           | VARCHAR   | 8529426                                                            |                                                              |

## 7. Table: EthBlocks\_event\_Updated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| tokenId           | VARCHAR   |                                                              |             |
| url               | VARCHAR   |                                                              |             |
