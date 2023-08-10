# based

## 1. Table: UFragments\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-14 08:37:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12824129                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x33a5cfa90535042da91202a475483a53dee1b8e480e68ed396e5d278f8036928 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 322                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x68a118ef45063051eac49c7e647ce5ace48a68a5                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x15de8fc4dcfa52c5cb58e1614c63e54964d28cf5                         |                                                              |
| spender           | VARCHAR   | 0x7a250d5630b4cf539739df2c5dacb4c659f2488d                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 2. Table: UFragments\_event\_LogMonetaryPolicyUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-18 17:46:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10685467                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4f5322ba21542e40ac5009e9cb14a5fcbb813b71df2547e8e346892f901efde7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 217                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x68a118ef45063051eac49c7e647ce5ace48a68a5                         | Address of the contract that produced the log                |
| monetaryPolicy    | VARCHAR   | 0x639cf2f84202f3424f5e703d248e1b6a7f466da9                         |                                                              |

## 3. Table: UFragments\_event\_LogRebase\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-05 20:07:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11394718                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0895333ac94faa7ca4a863124290f1f10ad9360022e413aa6996e7d339ff971c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 159                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x68a118ef45063051eac49c7e647ce5ace48a68a5                         | Address of the contract that produced the log                |
| epoch             | VARCHAR   | 73                                                                 |                                                              |
| totalSupply       | VARCHAR   | 8018915266355179342972329                                          |                                                              |

## 4. Table: UFragments\_event\_OwnershipRenounced\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-19 21:47:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10693063                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa8f22a6d3d6787dbde5b99551e1383160d552148864ddb8715a0121ffedab037 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x68a118ef45063051eac49c7e647ce5ace48a68a5                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x9e3c40045a3503b33bfedaea0bf6981120e8c753                         |                                                              |

## 5. Table: UFragments\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner     | VARCHAR   |                                                              |             |
| newOwner          | VARCHAR   |                                                              |             |

## 6. Table: UFragments\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-02 21:50:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12357287                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x90ada5f514ccbd9da9eb7bb411ea3787f65edc82a7f9558881ea7529c00244ac | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 300                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x68a118ef45063051eac49c7e647ce5ace48a68a5                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x26cf82e4ae43d31ea51e72b663d26e26a75af729                         |                                                              |
| to                | VARCHAR   | 0x5b25e226e1b6baec5d6b42f9aa58fcf97f0a3ef3                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |
