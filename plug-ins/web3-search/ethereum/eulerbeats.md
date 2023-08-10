# eulerbeats

## 1. Table: EulerBeats\_event\_ApprovalForAll\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-20 18:02:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13264129                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf0ec2b0a47495797c047a9eec0be860cd20b622b04dc17f44a896fe282d6a11d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 27                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8754f54074400ce745a7ceddc928fb1b7e985ed6                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x6c615c4ecfea0aff9e87746723eaa35495fd52f5                         |                                                              |
| operator          | VARCHAR   | 0x8cac485c30641ece09dbeb2b5245e24de4830f27                         |                                                              |
| approved          | VARCHAR   | true                                                               |                                                              |

## 2. Table: EulerBeats\_event\_MintOriginal\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-15 18:49:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11863090                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1f78db1751bdd764c8d6f0157497b67240353f3cabc552d72f1f1621a7b7e7b8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 136                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8754f54074400ce745a7ceddc928fb1b7e985ed6                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0x2c979c65504f4b758e6333268b42639eb4114daf                         |                                                              |
| seed              | VARCHAR   | 554240256                                                          |                                                              |
| originalsMinted   | VARCHAR   | 9                                                                  |                                                              |

## 3. Table: EulerBeats\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-23 02:28:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11910592                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6001fa073d73331bef32847c9fa9f54283abc8209e1948bf6b0ab8d8d331332f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8754f54074400ce745a7ceddc928fb1b7e985ed6                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x163890fd512475f3d891fa4c5632ccd3bc8cfef4                         |                                                              |
| newOwner          | VARCHAR   | 0x8cac485c30641ece09dbeb2b5245e24de4830f27                         |                                                              |

## 4. Table: EulerBeats\_event\_PrintBurned\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-02 05:19:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14696428                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x232874aa9e851dbe9173ccf4b7e13ede994a8dad901c70bf4ca61039959fc6cc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 122                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8754f54074400ce745a7ceddc928fb1b7e985ed6                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0x8cac485c30641ece09dbeb2b5245e24de4830f27                         |                                                              |
| id                | VARCHAR   | 572119909635                                                       |                                                              |
| seed              | VARCHAR   | 22364095747                                                        |                                                              |
| priceReceived     | VARCHAR   | 1026900000000000000                                                |                                                              |
| nextPrintPrice    | VARCHAR   | 1141000000000000000                                                |                                                              |
| nextBurnPrice     | VARCHAR   | 983700000000000000                                                 |                                                              |
| printsSupply      | VARCHAR   | 34                                                                 |                                                              |
| reserve           | VARCHAR   | 488932200000000000000                                              |                                                              |

## 5. Table: EulerBeats\_event\_PrintMinted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-22 10:55:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12088203                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6a876aa30173bae0f5bb7f466cef7f96113392c077910bbc50892f7f45c45aad | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 187                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8754f54074400ce745a7ceddc928fb1b7e985ed6                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0x8cac485c30641ece09dbeb2b5245e24de4830f27                         |                                                              |
| id                | VARCHAR   | 563580897539                                                       |                                                              |
| seed              | VARCHAR   | 13825083651                                                        |                                                              |
| pricePaid         | VARCHAR   | 3219000000000000000                                                |                                                              |
| nextPrintPrice    | VARCHAR   | 3422000000000000000                                                |                                                              |
| nextBurnPrice     | VARCHAR   | 2897100000000000000                                                |                                                              |
| printsSupply      | VARCHAR   | 56                                                                 |                                                              |
| royaltyPaid       | VARCHAR   | 257520000000000000                                                 |                                                              |
| reserve           | VARCHAR   | 1849898700000000000000                                             |                                                              |
| royaltyRecipient  | VARCHAR   | 0x947559ea1cf44739935ff96b58a0bed3f2ab42eb                         |                                                              |

## 6. Table: EulerBeats\_event\_TransferBatch\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-04 12:03:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11971669                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x563ecc50c812212cfa218f3ff1165346b9fd1b1b93debffd90f3267b067edee8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 181                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8754f54074400ce745a7ceddc928fb1b7e985ed6                         | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0x65f304bfb9dee92fa77363e7390658063cea6260                         |                                                              |
| from              | VARCHAR   | 0x65f304bfb9dee92fa77363e7390658063cea6260                         |                                                              |
| to                | VARCHAR   | 0x72aa7371cd5113fb7f1b1452867a421b2a375353                         |                                                              |
| ids               | VARCHAR   | 563312067587                                                       |                                                              |
| values            | VARCHAR   | 1                                                                  |                                                              |

## 7. Table: EulerBeats\_event\_TransferSingle\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-06 00:27:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13168980                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xca4a42b2d66717cbd920b689e11eb433c42e4650971aa13bd6277f01890df046 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8754f54074400ce745a7ceddc928fb1b7e985ed6                         | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0x0140a5def60faa75b73469e600c5ed967416a400                         |                                                              |
| from              | VARCHAR   | 0x0140a5def60faa75b73469e600c5ed967416a400                         |                                                              |
| to                | VARCHAR   | 0x1010595f96ab62b31bfeac411ec5f8f60db5dc23                         |                                                              |
| id                | VARCHAR   | 558681818883                                                       |                                                              |
| value             | VARCHAR   | 1                                                                  |                                                              |

## 8. Table: EulerBeats\_event\_URI\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| value             | VARCHAR   |                                                              |             |
| id                | VARCHAR   |                                                              |             |
