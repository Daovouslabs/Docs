# otherside

## 1. Table: Land\_event\_ApprovalForAll\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-07 07:27:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17427014                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcc76244f64dac1a4bcd9f885576dfded138ce3614a36b54fde396574bcd26e23 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 271                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x34d85c9cdeb23fa97cb08333b511ac86e1c4e258                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xf91000c77c8bba1418359eebefc10374f21f2a87                         |                                                              |
| operator          | VARCHAR   | 0x00000000000111abe46ff893f3b2fdf1f759a8a8                         |                                                              |
| approved          | VARCHAR   | true                                                               |                                                              |

## 2. Table: Land\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-21 02:10:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17738458                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5108458e007f4d35d5317406260a5a4d63eb81e45fc2163aa951605f1966f1eb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 200                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x34d85c9cdeb23fa97cb08333b511ac86e1c4e258                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x0000553f880ffa3728b290e04e819053a3590000                         |                                                              |
| approved          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| tokenId           | VARCHAR   | 69599                                                              |                                                              |

## 3. Table: Land\_event\_ClaimableStateChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-23 03:59:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14827355                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb6f5fe26d09486c0b6c7f91146c8d463b5cb54e59f16a173e9f07170ea498cea | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 131                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x34d85c9cdeb23fa97cb08333b511ac86e1c4e258                         | Address of the contract that produced the log                |
| claimableActive   | VARCHAR   | false                                                              |                                                              |

## 4. Table: Land\_event\_ContributorsClaimStart\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-29 13:50:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14679560                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x06dc39cbc48cc6b4c8441012d56d38eb9a3bdb46dc037c217c02f77f5043c879 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 327                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x34d85c9cdeb23fa97cb08333b511ac86e1c4e258                         | Address of the contract that produced the log                |
| \_timestamp       | VARCHAR   | 1651240253                                                         |                                                              |

## 5. Table: Land\_event\_ContributorsClaimStop\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-29 22:19:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14681830                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe5a70de7b6ca57731a82b62ba79b8fba8e1360ae18931ec711156c1a8c85f248 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 68                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x34d85c9cdeb23fa97cb08333b511ac86e1c4e258                         | Address of the contract that produced the log                |
| \_timestamp       | VARCHAR   | 1651270751                                                         |                                                              |

## 6. Table: Land\_event\_LandPublicSaleStart\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-01 00:59:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14688876                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x257f966c3d155cf45e213f8919d0e0b26fc8737034f28f54c00a0f4e2410ed38 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 90                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x34d85c9cdeb23fa97cb08333b511ac86e1c4e258                         | Address of the contract that produced the log                |
| \_saleDuration    | VARCHAR   | 1                                                                  |                                                              |
| \_saleStartTime   | VARCHAR   | 1651366791                                                         |                                                              |

## 7. Table: Land\_event\_LandPublicSaleStop\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-01 03:41:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14689606                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xab0692dcebaaed9d4207bd3151ff3bbc8934786f6370f0a59f4595e3caddb0b1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 14                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x34d85c9cdeb23fa97cb08333b511ac86e1c4e258                         | Address of the contract that produced the log                |
| \_currentPrice    | VARCHAR   | 305000000000000000000                                              |                                                              |
| \_timeElapsed     | VARCHAR   | 9706                                                               |                                                              |

## 8. Table: Land\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-28 12:49:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14672945                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2f3b642dbc7c44db1dd0e5d125e5eeb8007035d3cdacf1a28ec037f9f7c8c684 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 35                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x34d85c9cdeb23fa97cb08333b511ac86e1c4e258                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0xe53c9cbfc1314b6cf6ba508230457df130552bc6                         |                                                              |

## 9. Table: Land\_event\_PublicSaleMint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-01 01:01:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14688884                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0eefa6ba0e4bf55af1ccce19134dad9ac36bec3755befa1733ce752e70fc8658 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 56                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x34d85c9cdeb23fa97cb08333b511ac86e1c4e258                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x1adcd438ae52f590ab55d5ab32ea1807d29dd2c7                         |                                                              |
| numLands          | VARCHAR   | 1                                                                  |                                                              |
| mintPrice         | VARCHAR   | 305000000000000000000                                              |                                                              |

## 10. Table: Land\_event\_StartingIndexSetAlphaBeta\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-01 19:06:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14693706                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xba2cc81ecd02488cbfb81d472e0920f94489a5fd5eb18b89460e756e9cf4c3b2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 170                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x34d85c9cdeb23fa97cb08333b511ac86e1c4e258                         | Address of the contract that produced the log                |
| \_alphaOffset     | VARCHAR   | 5491                                                               |                                                              |
| \_betaOffset      | VARCHAR   | 15491                                                              |                                                              |

## 11. Table: Land\_event\_StartingIndexSetPublicSale\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-01 19:13:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14693735                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2b0daebbe50801f4db68e8d63ca51b1b3b8f7a0aab7fd24490bd7bf753bbfb9d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 103                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x34d85c9cdeb23fa97cb08333b511ac86e1c4e258                         | Address of the contract that produced the log                |
| \_startingIndex   | VARCHAR   | 35117                                                              |                                                              |

## 12. Table: Land\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-15 06:18:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17263362                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa586997b5e8e2728404cbe28558d493905da9ca369dc99bbce3270bff6b2289d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 274                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x34d85c9cdeb23fa97cb08333b511ac86e1c4e258                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x6d0267156f1c6ce44caa4bf129b76009d3d41830                         |                                                              |
| to                | VARCHAR   | 0x000000000000000000000000000000000000dead                         |                                                              |
| tokenId           | VARCHAR   | 18657                                                              |                                                              |
