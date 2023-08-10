# tokenlon

## 1. Table: TokenlonExchange\_event\_FillOrder\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2019-12-03 06:44:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 9042271                                                            | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0xf87733927b17392d16b5e3e62db9e11a6cbb60bd05306025e19714c467d62d30 | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0xdc6c91b569c98f9f6f74d90f9beff99fdaf4248b                         | Address of the contract that produced the log                |
| executeTxHash          | VARCHAR   | 0x2d7b7bb5fc52f3c47c43da8ef706c3e21d0ab81698cb8168f02b693858bf9217 |                                                              |
| userAddr               | VARCHAR   | 0x59bde2ef73aec42cb0304d60bcb6c21170dc79f9                         |                                                              |
| receiverAddr           | VARCHAR   | 0x59bde2ef73aec42cb0304d60bcb6c21170dc79f9                         |                                                              |
| filledAmount           | VARCHAR   | 10000000000000000                                                  |                                                              |
| acutalMakerAssetAmount | VARCHAR   | 7573400246561000000                                                |                                                              |
