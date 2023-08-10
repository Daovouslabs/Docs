# element

## 1. Table: ElementERC1155V1\_event\_ERC1155BuyOrderFilled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-08 18:04:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 36587220                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x92612b9d273159661b9a5c9e6380fa0f0e06b1dc4387de77c71ef5f63d6cfa9a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 211                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeaf5453b329eb38be159a872a6ce91c9a8fb0260                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0xa07b52b23507ce63864b7c2214b107a096e9f029f42d006e956f20a5894a9d9a |                                                              |
| maker             | VARCHAR   | 0xf094dd72ed290311fa14ffb5d99a28b92bb77a93                         |                                                              |
| taker             | VARCHAR   | 0x09a6eceb1372c0d825a0a5417fadc2b4f059f53f                         |                                                              |
| nonce             | VARCHAR   | 81                                                                 |                                                              |
| erc20Token        | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         |                                                              |
| erc20FillAmount   | VARCHAR   | 1500000000000000000                                                |                                                              |
| fees              | VARCHAR   | 0xD207842d66b715dF6ea08CF52f025B9E2ed28788,30000000000000000       |                                                              |
| erc1155Token      | VARCHAR   | 0x200fb6e28edf0fbc9b5fabf7d39ae583981f5038                         |                                                              |
| erc1155TokenId    | VARCHAR   | 0                                                                  |                                                              |
| erc1155FillAmount | VARCHAR   | 1                                                                  |                                                              |

## 2. Table: ElementERC1155V1\_event\_ERC1155BuyOrderPreSigned\_history

| Column                 | Type      | Example                                                      | Description |
| ---------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp       | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number          | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash      | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index             | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address      | VARCHAR   | Address of the contract that produced the log                |             |
| maker                  | VARCHAR   |                                                              |             |
| taker                  | VARCHAR   |                                                              |             |
| expiry                 | VARCHAR   |                                                              |             |
| nonce                  | VARCHAR   |                                                              |             |
| erc20Token             | VARCHAR   |                                                              |             |
| erc20TokenAmount       | VARCHAR   |                                                              |             |
| fees                   | VARCHAR   |                                                              |             |
| erc1155Token           | VARCHAR   |                                                              |             |
| erc1155TokenId         | VARCHAR   |                                                              |             |
| erc1155TokenProperties | VARCHAR   |                                                              |             |
| erc1155TokenAmount     | VARCHAR   |                                                              |             |

## 3. Table: ElementERC1155V1\_event\_ERC1155OrderCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-25 08:23:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 43123819                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x871a6efc452edad03997f7ba157e33d1b90c92ccf726066878443febddd03fbf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 285                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeaf5453b329eb38be159a872a6ce91c9a8fb0260                         | Address of the contract that produced the log                |
| maker             | VARCHAR   | 0x14d0a1877f2fe5761eb0f968384126091c40d53f                         |                                                              |
| nonce             | VARCHAR   | 52                                                                 |                                                              |

## 4. Table: ElementERC1155V1\_event\_ERC1155SellOrderFilled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-10 20:29:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 44923621                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x611861ba80a97db0e2c813ff9422ab5ad2b9ac130c07c21cf4809328701369f9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 268                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeaf5453b329eb38be159a872a6ce91c9a8fb0260                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0x836f760fab1de804be170d604b77de5ed46eb3c976e55f7be32b99e2c7565081 |                                                              |
| maker             | VARCHAR   | 0x91ebcc511fcc24e2b32b7a2cd7802214b5111b93                         |                                                              |
| taker             | VARCHAR   | 0x86b4e570b92b19d6ce73779b54eb658ba8af5442                         |                                                              |
| nonce             | VARCHAR   | 6                                                                  |                                                              |
| erc20Token        | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| erc20FillAmount   | VARCHAR   | 500000000000000000                                                 |                                                              |
| fees              | VARCHAR   | 0xD207842d66b715dF6ea08CF52f025B9E2ed28788,10000000000000000       |                                                              |
| erc1155Token      | VARCHAR   | 0xe8bd3f0e767e600d72d433f863496e62a57665d4                         |                                                              |
| erc1155TokenId    | VARCHAR   | 3                                                                  |                                                              |
| erc1155FillAmount | VARCHAR   | 1                                                                  |                                                              |

## 5. Table: ElementERC1155V1\_event\_ERC1155SellOrderPreSigned\_history

| Column             | Type      | Example                                                      | Description |
| ------------------ | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number      | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index         | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address  | VARCHAR   | Address of the contract that produced the log                |             |
| maker              | VARCHAR   |                                                              |             |
| taker              | VARCHAR   |                                                              |             |
| expiry             | VARCHAR   |                                                              |             |
| nonce              | VARCHAR   |                                                              |             |
| erc20Token         | VARCHAR   |                                                              |             |
| erc20TokenAmount   | VARCHAR   |                                                              |             |
| fees               | VARCHAR   |                                                              |             |
| erc1155Token       | VARCHAR   |                                                              |             |
| erc1155TokenId     | VARCHAR   |                                                              |             |
| erc1155TokenAmount | VARCHAR   |                                                              |             |

## 6. Table: ElementERC1155V1\_event\_TakerDataEmitted\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| orderHash         | VARCHAR   |                                                              |             |
| takerData         | VARCHAR   |                                                              |             |

## 7. Table: ElementERC1155\_event\_ERC1155BuyOrderFilled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-13 02:12:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 43847755                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1ab73ceb28e5ca8857499cdbf929c1bb7e98115c860a1b609099b8a6f34c7d93 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 90                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeaf5453b329eb38be159a872a6ce91c9a8fb0260                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0xb254a46c9ecadc4c2198bb1a9e73282744151c0559b2a6fb2b70beb3d612d7af |                                                              |
| maker             | VARCHAR   | 0x326c0e3eec1c1a806d4d296c030123873cfc5011                         |                                                              |
| taker             | VARCHAR   | 0x8b3077e84a4217dea241dcff51c6a3651566d14e                         |                                                              |
| nonce             | VARCHAR   | 68                                                                 |                                                              |
| erc20Token        | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         |                                                              |
| erc20FillAmount   | VARCHAR   | 250000000000000000                                                 |                                                              |
| fees              | VARCHAR   | 0xD207842d66b715dF6ea08CF52f025B9E2ed28788,5000000000000000        |                                                              |
| erc1155Token      | VARCHAR   | 0x4bb5b2461e9ef782152c3a96698b2a4cf55b6162                         |                                                              |
| erc1155TokenId    | VARCHAR   | 88                                                                 |                                                              |
| erc1155FillAmount | VARCHAR   | 5                                                                  |                                                              |

## 8. Table: ElementERC1155\_event\_ERC1155BuyOrderPreSigned\_history

| Column                 | Type      | Example                                                      | Description |
| ---------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp       | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number          | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash      | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index             | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address      | VARCHAR   | Address of the contract that produced the log                |             |
| maker                  | VARCHAR   |                                                              |             |
| taker                  | VARCHAR   |                                                              |             |
| expiry                 | VARCHAR   |                                                              |             |
| nonce                  | VARCHAR   |                                                              |             |
| erc20Token             | VARCHAR   |                                                              |             |
| erc20TokenAmount       | VARCHAR   |                                                              |             |
| fees                   | VARCHAR   |                                                              |             |
| erc1155Token           | VARCHAR   |                                                              |             |
| erc1155TokenId         | VARCHAR   |                                                              |             |
| erc1155TokenProperties | VARCHAR   |                                                              |             |
| erc1155TokenAmount     | VARCHAR   |                                                              |             |

## 9. Table: ElementERC1155\_event\_ERC1155OrderCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-25 12:43:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45501596                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x527c439158a54f24cc033c94c40a4e7cfeb9356ec85b4b4cceb8d82e3647d12d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 150                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeaf5453b329eb38be159a872a6ce91c9a8fb0260                         | Address of the contract that produced the log                |
| maker             | VARCHAR   | 0x041ce6b8e4cdf6b1f83c9a0c48732e576e3d5afe                         |                                                              |
| nonce             | VARCHAR   | 1                                                                  |                                                              |

## 10. Table: ElementERC1155\_event\_ERC1155SellOrderFilled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-01 14:33:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 35070781                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5011cb40b0cafe639d49e10320f7d843d545acb3ee2f5572b4f3f33f82aa4e3b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 243                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeaf5453b329eb38be159a872a6ce91c9a8fb0260                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0x4f8720f76f4fa0e4c41d805c30da000b423f1fc6ded6f47484c03be66d4fa7f6 |                                                              |
| maker             | VARCHAR   | 0x34475ab5ec2795bb4f6e9cefc241be51455ad266                         |                                                              |
| taker             | VARCHAR   | 0xcb75762c6517ecd850cb6a2bacd66e7805926e3a                         |                                                              |
| nonce             | VARCHAR   | 4                                                                  |                                                              |
| erc20Token        | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| erc20FillAmount   | VARCHAR   | 3000000000000000000                                                |                                                              |
| fees              | VARCHAR   | 0xD207842d66b715dF6ea08CF52f025B9E2ed28788,60000000000000000       |                                                              |
| erc1155Token      | VARCHAR   | 0x200fb6e28edf0fbc9b5fabf7d39ae583981f5038                         |                                                              |
| erc1155TokenId    | VARCHAR   | 0                                                                  |                                                              |
| erc1155FillAmount | VARCHAR   | 1                                                                  |                                                              |

## 11. Table: ElementERC1155\_event\_ERC1155SellOrderPreSigned\_history

| Column             | Type      | Example                                                      | Description |
| ------------------ | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number      | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index         | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address  | VARCHAR   | Address of the contract that produced the log                |             |
| maker              | VARCHAR   |                                                              |             |
| taker              | VARCHAR   |                                                              |             |
| expiry             | VARCHAR   |                                                              |             |
| nonce              | VARCHAR   |                                                              |             |
| erc20Token         | VARCHAR   |                                                              |             |
| erc20TokenAmount   | VARCHAR   |                                                              |             |
| fees               | VARCHAR   |                                                              |             |
| erc1155Token       | VARCHAR   |                                                              |             |
| erc1155TokenId     | VARCHAR   |                                                              |             |
| erc1155TokenAmount | VARCHAR   |                                                              |             |

## 12. Table: ElementERC1155\_event\_TakerDataEmitted\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| orderHash         | VARCHAR   |                                                              |             |
| takerData         | VARCHAR   |                                                              |             |

## 13. Table: ElementERC721V1\_event\_ERC721BuyOrderFilled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-18 03:34:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33245153                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xffe6f79d326d540dc6f85ad3a5e9187e3a3e02b0fe672ec0e88d7f294052b07f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 116                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeaf5453b329eb38be159a872a6ce91c9a8fb0260                         | Address of the contract that produced the log                |
| maker             | VARCHAR   | 0xa9b32033be38144c5f7cdc6bdd3fe2ca2b5e0aaa                         |                                                              |
| taker             | VARCHAR   | 0x0dc8f1d9ddfa5e758ad090be6a2aaef0b55f0135                         |                                                              |
| erc20Token        | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         |                                                              |
| erc20TokenAmount  | VARCHAR   | 5049000000000000000                                                |                                                              |
| erc721Token       | VARCHAR   | 0x7546d34fc15b25471072493e25150e0a8901cd52                         |                                                              |
| erc721TokenId     | VARCHAR   | 7091                                                               |                                                              |
| orderHash         | VARCHAR   | 0x6952b2f6f7f622fd26e5f7655c2f60a9c89dffaecc5f657d29f1a47eebec8122 |                                                              |

## 14. Table: ElementERC721V1\_event\_ERC721BuyOrderPreSigned\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| maker             | VARCHAR   |                                                              |             |
| taker             | VARCHAR   |                                                              |             |
| expiry            | VARCHAR   |                                                              |             |
| nonce             | VARCHAR   |                                                              |             |
| erc20Token        | VARCHAR   |                                                              |             |
| erc20TokenAmount  | VARCHAR   |                                                              |             |
| fees              | VARCHAR   |                                                              |             |
| erc721Token       | VARCHAR   |                                                              |             |
| erc721TokenId     | VARCHAR   |                                                              |             |
| nftProperties     | VARCHAR   |                                                              |             |

## 15. Table: ElementERC721V1\_event\_ERC721OrderCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-09 12:33:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29355591                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xad088c782656c7c136668892c8576aa829c47fbfecae43a33cfd6bce732587f1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 202                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeaf5453b329eb38be159a872a6ce91c9a8fb0260                         | Address of the contract that produced the log                |
| maker             | VARCHAR   | 0xb4fc8b6d606911d7c295bd8ce0d780e4afe28522                         |                                                              |
| nonce             | VARCHAR   | 1654354515                                                         |                                                              |

## 16. Table: ElementERC721V1\_event\_ERC721SellOrderFilled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-26 01:33:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 31140758                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfe5605533515cbdb9a44881079e1c2bdc285de1d2c3451ddfc4a1524aa292b05 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 200                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeaf5453b329eb38be159a872a6ce91c9a8fb0260                         | Address of the contract that produced the log                |
| maker             | VARCHAR   | 0x074a2807d0941a248109450add7b4ad521acbb28                         |                                                              |
| taker             | VARCHAR   | 0xf439ab34f0e8eaaefc8706c5fbe675bd6efee05e                         |                                                              |
| erc20Token        | VARCHAR   | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                         |                                                              |
| erc20TokenAmount  | VARCHAR   | 50000000                                                           |                                                              |
| erc721Token       | VARCHAR   | 0x1871464f087db27823cff66aa88599aa4815ae95                         |                                                              |
| erc721TokenId     | VARCHAR   | 781284                                                             |                                                              |
| orderHash         | VARCHAR   | 0x740a4360a133696d6c2e90ae265ac3691039b750c41bb05267fcb335907672fb |                                                              |

## 17. Table: ElementERC721V1\_event\_ERC721SellOrderPreSigned\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| maker             | VARCHAR   |                                                              |             |
| taker             | VARCHAR   |                                                              |             |
| expiry            | VARCHAR   |                                                              |             |
| nonce             | VARCHAR   |                                                              |             |
| erc20Token        | VARCHAR   |                                                              |             |
| erc20TokenAmount  | VARCHAR   |                                                              |             |
| fees              | VARCHAR   |                                                              |             |
| erc721Token       | VARCHAR   |                                                              |             |
| erc721TokenId     | VARCHAR   |                                                              |             |

## 18. Table: ElementERC721V1\_event\_HashNonceIncremented\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-28 02:10:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 40845961                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb9b733f346ac8c3d7f85cc685433247ad43bc0143c38cf6931340110f8e26616 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 48                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeaf5453b329eb38be159a872a6ce91c9a8fb0260                         | Address of the contract that produced the log                |
| maker             | VARCHAR   | 0x21f573e04faca045a17b458cb18d4d7d69380705                         |                                                              |
| newHashNonce      | VARCHAR   | 1                                                                  |                                                              |

## 19. Table: ElementERC721V2\_event\_ERC721BuyOrderFilled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-06 06:02:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 40021688                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x890d15b5e684dad4e4a4bf28087b40e5bec5ecd1188fb370f59905c40286aacf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 320                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeaf5453b329eb38be159a872a6ce91c9a8fb0260                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0x54b0f2434236fe98a3113cdcf5868cebb26012108d3416a6d31b74e9c24d5833 |                                                              |
| maker             | VARCHAR   | 0x121d94c6c08d2e77c8459850fd70f05b2729ee21                         |                                                              |
| taker             | VARCHAR   | 0x6e1c8fb5af6f0b0582536613f093439791997640                         |                                                              |
| nonce             | VARCHAR   | 1291                                                               |                                                              |
| erc20Token        | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         |                                                              |
| erc20TokenAmount  | VARCHAR   | 110000000000000000                                                 |                                                              |
| fees              | VARCHAR   | 0xD207842d66b715dF6ea08CF52f025B9E2ed28788,2200000000000000        |                                                              |
| erc721Token       | VARCHAR   | 0x4c37636625e80d61f7c2c4ba8d7058f5aa92f487                         |                                                              |
| erc721TokenId     | VARCHAR   | 1389                                                               |                                                              |

## 20. Table: ElementERC721V2\_event\_ERC721BuyOrderPreSigned\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| maker             | VARCHAR   |                                                              |             |
| taker             | VARCHAR   |                                                              |             |
| expiry            | VARCHAR   |                                                              |             |
| nonce             | VARCHAR   |                                                              |             |
| erc20Token        | VARCHAR   |                                                              |             |
| erc20TokenAmount  | VARCHAR   |                                                              |             |
| fees              | VARCHAR   |                                                              |             |
| erc721Token       | VARCHAR   |                                                              |             |
| erc721TokenId     | VARCHAR   |                                                              |             |
| nftProperties     | VARCHAR   |                                                              |             |

## 21. Table: ElementERC721V2\_event\_ERC721OrderCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-23 13:19:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 43052409                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x97682ad4e881b953f82e5fa2b68754db1fb8b783f88fe7e8367e7052108ea43e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 395                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeaf5453b329eb38be159a872a6ce91c9a8fb0260                         | Address of the contract that produced the log                |
| maker             | VARCHAR   | 0x5a2988d0d325929118668350e2d39b42e4e19ed8                         |                                                              |
| nonce             | VARCHAR   | 1                                                                  |                                                              |

## 22. Table: ElementERC721V2\_event\_ERC721SellOrderFilled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-27 09:53:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45575039                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xeda2e9874c30d222592cbda2aeaed603156140c8e93952eb5ccd3cc1aa840e0e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 201                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeaf5453b329eb38be159a872a6ce91c9a8fb0260                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0x624ef414ce9fa88bf5a5b8dbc48976f001b788c3b0e66d6dbe240e3952749739 |                                                              |
| maker             | VARCHAR   | 0x5a420c0fec46181d472e30295d040f7c3db2e305                         |                                                              |
| taker             | VARCHAR   | 0x1ec499edf011b47abf002349ed6f54f14ef83e10                         |                                                              |
| nonce             | VARCHAR   | 1                                                                  |                                                              |
| erc20Token        | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| erc20TokenAmount  | VARCHAR   | 39200000000000000                                                  |                                                              |
| fees              | VARCHAR   | 0xD207842d66b715dF6ea08CF52f025B9E2ed28788,784000000000000         |                                                              |
| erc721Token       | VARCHAR   | 0x1fe4d1141e08de5652c209fd0245dc390db8b67d                         |                                                              |
| erc721TokenId     | VARCHAR   | 226                                                                |                                                              |

## 23. Table: ElementERC721V2\_event\_ERC721SellOrderPreSigned\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| maker             | VARCHAR   |                                                              |             |
| taker             | VARCHAR   |                                                              |             |
| expiry            | VARCHAR   |                                                              |             |
| nonce             | VARCHAR   |                                                              |             |
| erc20Token        | VARCHAR   |                                                              |             |
| erc20TokenAmount  | VARCHAR   |                                                              |             |
| fees              | VARCHAR   |                                                              |             |
| erc721Token       | VARCHAR   |                                                              |             |
| erc721TokenId     | VARCHAR   |                                                              |             |

## 24. Table: ElementERC721V2\_event\_HashNonceIncremented\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-29 04:35:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 34931854                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8f2a9b20b41b3448bbed609ed25e6d7b067b6af251801bddd40b682f498681a8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 129                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeaf5453b329eb38be159a872a6ce91c9a8fb0260                         | Address of the contract that produced the log                |
| maker             | VARCHAR   | 0xef1f10c051c92a604036d3a7fd403be403723194                         |                                                              |
| newHashNonce      | VARCHAR   | 1                                                                  |                                                              |

## 25. Table: ElementERC721V2\_event\_TakerDataEmitted\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| orderHash         | VARCHAR   |                                                              |             |
| takerData         | VARCHAR   |                                                              |             |
