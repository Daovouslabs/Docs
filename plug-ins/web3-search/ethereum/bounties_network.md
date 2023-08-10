# bounties\_network

## 1. Table: StandardBounties\_event\_BountyDataChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-21 05:12:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8972576                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfad52ad9074e1f4d8b881c75e329bb010b3138f69b30af9cc0ff7daad6a85559 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 126                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa7135d0a62939501b5304a04bf00d1a9a22f6623                         | Address of the contract that produced the log                |
| \_bountyId        | VARCHAR   | 16                                                                 |                                                              |
| \_changer         | VARCHAR   | 0x59d47550bfc7905aa52044610eeda530d780329b                         |                                                              |
| \_data            | VARCHAR   | QmUAtmPjR4eSiREZ2fgZrtEFAWeXjEbzqkPEc5KVTkovsC                     |                                                              |

## 2. Table: StandardBounties\_event\_BountyDeadlineChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-29 21:35:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9182725                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x898e2fe22a384c2dfe4945870e7f9b23e3232d9c01c7eb969514f1553b8cf480 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 54                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa7135d0a62939501b5304a04bf00d1a9a22f6623                         | Address of the contract that produced the log                |
| \_bountyId        | VARCHAR   | 48                                                                 |                                                              |
| \_changer         | VARCHAR   | 0xbc62985faabed27a8f174cbd5ea1ee7b1ed8fc12                         |                                                              |
| \_deadline        | VARCHAR   | 1578687981                                                         |                                                              |

## 3. Table: StandardBounties\_event\_BountyDrained\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-29 20:35:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9023022                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x05f5eb9fcd9e33629ee5092b0e0269bb3babaab3fcee293c955c34d72ae5a390 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 198                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa7135d0a62939501b5304a04bf00d1a9a22f6623                         | Address of the contract that produced the log                |
| \_bountyId        | VARCHAR   | 9                                                                  |                                                              |
| \_issuer          | VARCHAR   | 0xe11e22965bf346b3cb79713aa15fa06bfef7aee4                         |                                                              |
| \_amounts         | VARCHAR   | 2320000000000                                                      |                                                              |

## 4. Table: StandardBounties\_event\_BountyFulfilled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-30 02:38:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10364502                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd6dd9a4df00240c6e1cc6d31923fb7adb5da09e386d1dd51e27acb0deaecad2d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 119                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa7135d0a62939501b5304a04bf00d1a9a22f6623                         | Address of the contract that produced the log                |
| \_bountyId        | VARCHAR   | 18                                                                 |                                                              |
| \_fulfillmentId   | VARCHAR   | 17                                                                 |                                                              |
| \_fulfillers      | VARCHAR   | 0x2C417C2Bf50a0CBf0283EdbCb36eA2DDFb77716D                         |                                                              |
| \_data            | VARCHAR   | QmRNN3Mn5TrTL3WnU1Cys1hHkQVpb7zanUJNMsEKSgfN76                     |                                                              |
| \_submitter       | VARCHAR   | 0x2c417c2bf50a0cbf0283edbcb36ea2ddfb77716d                         |                                                              |

## 5. Table: StandardBounties\_event\_BountyIssued\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-21 14:32:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8974900                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe1c782e251e396ff341bf74003c995123936d93a5a983296602b3478efd0fe8a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 222                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa7135d0a62939501b5304a04bf00d1a9a22f6623                         | Address of the contract that produced the log                |
| \_bountyId        | VARCHAR   | 27                                                                 |                                                              |
| \_creator         | VARCHAR   | 0xe2689e394fae140069486becf07508a4b8ae2a32                         |                                                              |
| \_issuers         | VARCHAR   | 0xe2689e394faE140069486becf07508a4b8AE2a32                         |                                                              |
| \_approvers       | VARCHAR   | 0xe2689e394faE140069486becf07508a4b8AE2a32                         |                                                              |
| \_data            | VARCHAR   | QmUBiUzfVqvtdHi1s148GyvDQ4xn7PPRtzD6eCzf8QddXw                     |                                                              |
| \_deadline        | VARCHAR   | 1575856820                                                         |                                                              |
| \_token           | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_tokenVersion    | VARCHAR   | 0                                                                  |                                                              |

## 6. Table: StandardBounties\_event\_BountyIssuersUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-26 16:33:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9005171                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf8df190437cc1dd8fc7ba07dc2dc1031bf982d2abc534c791f1840d7cba67d22 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 79                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa7135d0a62939501b5304a04bf00d1a9a22f6623                         | Address of the contract that produced the log                |
| \_bountyId        | VARCHAR   | 35                                                                 |                                                              |
| \_changer         | VARCHAR   | 0xbfdb50dc66c8df9fd9688d8fe5a0c34126427645                         |                                                              |
| \_issuers         | VARCHAR   | 0x54BeCc7560a7Be76d72ED76a1f5fee6C5a2A7Ab6                         |                                                              |

## 7. Table: StandardBounties\_event\_ContributionAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-22 12:35:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8980439                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf0e4f0235d1e0a2a7b320aa8ca884dc9397b990ee430e3c39a128fa66bd21af7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 171                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa7135d0a62939501b5304a04bf00d1a9a22f6623                         | Address of the contract that produced the log                |
| \_bountyId        | VARCHAR   | 13                                                                 |                                                              |
| \_contributionId  | VARCHAR   | 1                                                                  |                                                              |
| \_contributor     | VARCHAR   | 0x9428b39e978a35f659fe577e6a412b50473f636c                         |                                                              |
| \_amount          | VARCHAR   | 10000000000000000000000                                            |                                                              |

## 8. Table: StandardBounties\_event\_FulfillmentAccepted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-02-13 09:42:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9473924                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x579e24f6cc33994dbb073641af466f45a064bf174a481a9b23e091c8e1c6edb6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 108                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa7135d0a62939501b5304a04bf00d1a9a22f6623                         | Address of the contract that produced the log                |
| \_bountyId        | VARCHAR   | 47                                                                 |                                                              |
| \_fulfillmentId   | VARCHAR   | 0                                                                  |                                                              |
| \_approver        | VARCHAR   | 0x418cf9e24c8e74e0155c9c7f6da8a10b0ca799cd                         |                                                              |
| \_tokenAmounts    | VARCHAR   | 5000000000000000000                                                |                                                              |

## 9. Table: StandardBounties\_event\_FulfillmentUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-03 02:50:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9041414                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0e15294c56529518988e5ddc05687468644b2cefa7df8fd9c117ef8cff7a93ec | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 159                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa7135d0a62939501b5304a04bf00d1a9a22f6623                         | Address of the contract that produced the log                |
| \_bountyId        | VARCHAR   | 0                                                                  |                                                              |
| \_fulfillmentId   | VARCHAR   | 5                                                                  |                                                              |
| \_fulfillers      | VARCHAR   | 0x71EF787248b8B95Fc42758c0a0D4811B95c43B41                         |                                                              |
| \_data            | VARCHAR   | QmcyU9pQ69Dj23uV36jPpvqCjTHL9M8M8gDs12RtS3EvWu                     |                                                              |
