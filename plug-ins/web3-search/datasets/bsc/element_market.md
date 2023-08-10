# element\_market

## 1. Table: Element\_event\_ERC721BuyOrderFilled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-18 14:38:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 22285170                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa5958ec625e8a94b3e39cf30e4e49bf1ff6a6d0c273509db0f50b057992041d4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 72                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb3e3dfcb2d9f3dde16d78b9e6eb3538eb32b5ae1                         | Address of the contract that produced the log                |
| maker             | VARCHAR   | 0x4dcff827c29b95cda8ea8fe0df4cd4796fd315e0                         |                                                              |
| taker             | VARCHAR   | 0xb8cf8d483065541b2a62735d86280494497da13c                         |                                                              |
| erc20Token        | VARCHAR   | 0xbb4cdb9cbd36b01bd1cbaebf2de08d9173bc095c                         |                                                              |
| erc20TokenAmount  | VARCHAR   | 257850000000000000                                                 |                                                              |
| erc721Token       | VARCHAR   | 0x1f9c5be14b5d2ae7e467edce447a8ef6929b7d9d                         |                                                              |
| erc721TokenId     | VARCHAR   | 6098                                                               |                                                              |
| orderHash         | VARCHAR   | 0xa4a71f30f8f626a5e282f5c89fcbfe878b0510e0d2d8b7900e1f4b11822e18b5 |                                                              |

## 2. Table: Element\_event\_ERC721SellOrderFilled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-20 07:47:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 19710316                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb0937eadfb6f5cfb868f2b3b076cfbb7620918ce6ca37bbe3409392dd466d101 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 214                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb3e3dfcb2d9f3dde16d78b9e6eb3538eb32b5ae1                         | Address of the contract that produced the log                |
| maker             | VARCHAR   | 0xcaec14c40a4ca7f6ccd09b2bbdb5b2170eb8aacc                         |                                                              |
| taker             | VARCHAR   | 0xf959579edf47f166f316bc03887540d5d80aa302                         |                                                              |
| erc20Token        | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| erc20TokenAmount  | VARCHAR   | 6000000000000000                                                   |                                                              |
| erc721Token       | VARCHAR   | 0x9cee09946a8113a503c1264e328c0e3aee4c8bcf                         |                                                              |
| erc721TokenId     | VARCHAR   | 31004                                                              |                                                              |
| orderHash         | VARCHAR   | 0x24fbb2562026bdf7f059e541edaf37b206fde25a08503654abdeeb5fab4ffc57 |                                                              |

## 3. Table: Element\_event\_Fill\_history

| Column                 | Type      | Example                                                                                              | Description                                                  |
| ---------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2022-03-02 07:04:02+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 15701425                                                                                             | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0xeb13da4d934029be3304f4403c4aee9667927e91c6ed287f6d51d32d17ea8e52                                   | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 143                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0x381e8d08193a1eb7857f83495e96da6d52ba0087                                                           | Address of the contract that produced the log                |
| makerAddress           | VARCHAR   | 0xbf1e6475020928344f715f5ab6e6b0ab97edd6e4                                                           |                                                              |
| feeRecipientAddress    | VARCHAR   | 0x6b06e35531b2184578e4f5f5aabe1c4d229dc447                                                           |                                                              |
| makerAssetData         | VARCHAR   | 0xa7cb5fb7000000000000000000000000ce3e768faa1f50212cbd5250d0edfe9a43bdea9000000000000000000000000000 |                                                              |
| takerAssetData         | VARCHAR   | 0xf47261b0000000000000000000000000bb4cdb9cbd36b01bd1cbaebf2de08d9173bc095c                           |                                                              |
| makerFeeAssetData      | VARCHAR   | 0x                                                                                                   |                                                              |
| takerFeeAssetData      | VARCHAR   | 0xf47261b0000000000000000000000000bb4cdb9cbd36b01bd1cbaebf2de08d9173bc095c                           |                                                              |
| orderHash              | VARCHAR   | 0x3e39644c8dadc32e2e5a7a6443025dd367e120866a88bafdbbd15b0233492046                                   |                                                              |
| takerAddress           | VARCHAR   | 0xa34d87bff0bb716cd11da21b8c8fa02d0a7b76e5                                                           |                                                              |
| senderAddress          | VARCHAR   | 0xa34d87bff0bb716cd11da21b8c8fa02d0a7b76e5                                                           |                                                              |
| makerAssetFilledAmount | VARCHAR   | 1                                                                                                    |                                                              |
| takerAssetFilledAmount | VARCHAR   | 97500000000000                                                                                       |                                                              |
| makerFeePaid           | VARCHAR   | 0                                                                                                    |                                                              |
| takerFeePaid           | VARCHAR   | 2500000000000                                                                                        |                                                              |
| protocolFeePaid        | VARCHAR   | 0                                                                                                    |                                                              |
