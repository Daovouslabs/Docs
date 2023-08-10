# campfire

## 1. Table: CampfireMarket\_event\_Cancel\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2023-07-22 10:55:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 32929093                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x97ee2d0c499293362eb1e5da946e2e88e144ab124f0297376865c815e6ceec8d | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 35                                                                 | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0xbcb09cdb2011fea0591b52e52085bb102e4a082a                         | Address of the contract that produced the log                |
| creator            | VARCHAR   | 0x00d3be15cc9a9d071b6810531fbac7938c50ac39                         |                                                              |
| nftContractAddress | VARCHAR   | 0x8407518501fa8c9e58149ff7604cd8a6f7ee0329                         |                                                              |
| nftTokenId         | VARCHAR   | 80                                                                 |                                                              |
| price              | VARCHAR   | 7690000000000000000                                                |                                                              |
| kind               | VARCHAR   | 1                                                                  |                                                              |
| salt               | VARCHAR   | 0x161bf297246fdbc86e72dc8f961cd6af81520b554541eab4500e01edf51fad75 |                                                              |

## 2. Table: CampfireMarket\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-13 15:49:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12062283                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x092380264d621cdbef8361c886cac13f76341740c4cac65a36734b95193f4038 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 26                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbcb09cdb2011fea0591b52e52085bb102e4a082a                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x3b109762de20180e69144c620657d11e24205a9c                         |                                                              |

## 3. Table: CampfireMarket\_event\_Sale\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2022-09-07 20:29:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 19651943                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x850e0875b9360e775384c0d1d2bcbc6207aefc4fce006ca94831221c40283d8d | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0xbcb09cdb2011fea0591b52e52085bb102e4a082a                         | Address of the contract that produced the log                |
| buyer              | VARCHAR   | 0x544c0d65aee205aa5f4aed635cb0d15c713e17cb                         |                                                              |
| seller             | VARCHAR   | 0x3f2358b9fa1a21357d5c4c1b31185d50327a2c64                         |                                                              |
| nftContractAddress | VARCHAR   | 0x02eeb3cbe90ae618263d5ce7226270bdfa8424fc                         |                                                              |
| nftTokenId         | VARCHAR   | 77                                                                 |                                                              |
| price              | VARCHAR   | 1750000000000000000                                                |                                                              |
| kind               | VARCHAR   | 1                                                                  |                                                              |
| salt               | VARCHAR   | 0x53fc04affb761688682d007c89432962786d156a1eef2b770d97365b36f6c148 |                                                              |
