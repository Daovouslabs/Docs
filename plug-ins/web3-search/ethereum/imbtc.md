# imbtc

## 1. Table: IMBTC\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-02-03 06:49:06+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9408036                                                                        | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x12f2e05eef62507519c5f285f08f2ac58df9c7edc9a49f50ff932d9ff413d877             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 57                                                                             | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3212b29e33587a00fb1c83346f5dbfa69a458923                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xb7a8ec1294ccd4332d08cb3fa8b8ae623eb454b7                                     |                                                              |
| spender           | VARCHAR   | 0x0eee3e3828a45f7601d5f54bf49bb01d1a9df5ea                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 2. Table: IMBTC\_event\_AuthorizedOperator\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| operator          | VARCHAR   |                                                              |             |
| tokenHolder       | VARCHAR   |                                                              |             |

## 3. Table: IMBTC\_event\_Burned\_history

| Column            | Type      | Example                                                                | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-02-03 23:27:05+00:00                                              | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9412566                                                                | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaf40f8009f1f15197ba89f26464aa262c4ccc1b2b4a627e1a1608398f26e8dce     | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 166                                                                    | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3212b29e33587a00fb1c83346f5dbfa69a458923                             | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0xbb90133a6c39327147e4d110ab13e91a8b490c2c                             |                                                              |
| from              | VARCHAR   | 0xbb90133a6c39327147e4d110ab13e91a8b490c2c                             |                                                              |
| amount            | VARCHAR   | 689131741                                                              |                                                              |
| data              | VARCHAR   | 0x334d62627a36706a4e733438344d5a644d696b326a7969565644544b4c3164544861 |                                                              |
| operatorData      | VARCHAR   | 0x                                                                     |                                                              |

## 4. Table: IMBTC\_event\_Minted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-11 08:34:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9258560                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x550bd80587ec0ceb85af76f2e3ff46084ab7042ce27225710c8d57407eccfd56 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 53                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3212b29e33587a00fb1c83346f5dbfa69a458923                         | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0x2b763c03a2a5af346b363be10659d0530dfdeb09                         |                                                              |
| to                | VARCHAR   | 0xb646fedb2996e2fc2093c403c0164c480aa8debc                         |                                                              |
| amount            | VARCHAR   | 1343056                                                            |                                                              |
| data              | VARCHAR   | 0x86e0be9cb5885493ee9aeb880b5069f97ca744a1edaac5cef61c2c9dfe121f0b |                                                              |
| operatorData      | VARCHAR   | 0x                                                                 |                                                              |

## 5. Table: IMBTC\_event\_MinterAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-25 15:40:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8810012                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x531873e045add22332f0f642672ec70279acbdb6e61b7e9f87721953582bcedf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 40                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3212b29e33587a00fb1c83346f5dbfa69a458923                         | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0xe9e722b0f4542a850f95ffccc634c8720d1e0d76                         |                                                              |
| account           | VARCHAR   | 0xe9e722b0f4542a850f95ffccc634c8720d1e0d76                         |                                                              |

## 6. Table: IMBTC\_event\_MinterRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-25 17:23:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8810434                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x29fb93a3f85bda811f6ce4ccc4ae3cb691229ec324cd4a6202d87ebd00d23b45 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 41                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3212b29e33587a00fb1c83346f5dbfa69a458923                         | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0xe9e722b0f4542a850f95ffccc634c8720d1e0d76                         |                                                              |
| account           | VARCHAR   | 0xe9e722b0f4542a850f95ffccc634c8720d1e0d76                         |                                                              |

## 7. Table: IMBTC\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-25 15:40:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8810012                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x531873e045add22332f0f642672ec70279acbdb6e61b7e9f87721953582bcedf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 39                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3212b29e33587a00fb1c83346f5dbfa69a458923                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0xe9e722b0f4542a850f95ffccc634c8720d1e0d76                         |                                                              |

## 8. Table: IMBTC\_event\_Paused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-19 02:12:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9900045                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9028b4ca12cca387506b0c16317b60df81dcde812494b05a2013c9f88c325706 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 28                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3212b29e33587a00fb1c83346f5dbfa69a458923                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xb9e29984fe50602e7a619662ebed4f90d93824c7                         |                                                              |

## 9. Table: IMBTC\_event\_RevenueAddressSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-05 00:25:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12370966                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa9c5da500eefd5bfce50a739422934bcf80fd893350ec2ac650ac10613d56ba3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 168                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3212b29e33587a00fb1c83346f5dbfa69a458923                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x74c3ca9431c009dc35587591dc90780078174f8a                         |                                                              |

## 10. Table: IMBTC\_event\_RevenueDistributed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-01 13:36:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11366973                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x769c4ab8272365f2ebb651e678b23211b9b8bbec091cec58fad2b95bfaac6a67 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 195                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3212b29e33587a00fb1c83346f5dbfa69a458923                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x41f8d14c9475444f30a80431c68cf24dc9a8369a                         |                                                              |
| exchangeRate      | VARCHAR   | 1020300647132916767                                                |                                                              |
| value             | VARCHAR   | 209630                                                             |                                                              |
| remainder         | VARCHAR   | 0                                                                  |                                                              |

## 11. Table: IMBTC\_event\_RevokedOperator\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| operator          | VARCHAR   |                                                              |             |
| tokenHolder       | VARCHAR   |                                                              |             |

## 12. Table: IMBTC\_event\_Sent\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-19 16:17:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12858061                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7f7537de7dca507dac3ba0c618b81fc017f0189261fabc60f6bbe0eead72b858 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 167                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3212b29e33587a00fb1c83346f5dbfa69a458923                         | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0x95e6f48254609a6ee006f7d493c8e5fb97094cef                         |                                                              |
| from              | VARCHAR   | 0x8d90113a1e286a5ab3e496fbd1853f265e5913c6                         |                                                              |
| to                | VARCHAR   | 0x56178a0d5f301baf6cf3e1cd53d9863437345bf9                         |                                                              |
| amount            | VARCHAR   | 14170000                                                           |                                                              |
| data              | VARCHAR   | 0x                                                                 |                                                              |
| operatorData      | VARCHAR   | 0x                                                                 |                                                              |

## 13. Table: IMBTC\_event\_TransferDisabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-26 03:12:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8812933                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xce47df2264e0e6adef01c6d0c87999edf99edb67c028ca0eb45550580b5424d2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 112                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3212b29e33587a00fb1c83346f5dbfa69a458923                         | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0xb9e29984fe50602e7a619662ebed4f90d93824c7                         |                                                              |

## 14. Table: IMBTC\_event\_TransferEnabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-01 00:35:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8849648                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xba74bb5fc3d63c1729df120a8bf4c10428c5113be45c25519939228416adc53c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 50                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3212b29e33587a00fb1c83346f5dbfa69a458923                         | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0xb9e29984fe50602e7a619662ebed4f90d93824c7                         |                                                              |

## 15. Table: IMBTC\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-05 23:00:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11395467                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd3ec6899a9016836da581e43216943e6ed20828dd0afadfa45542593525655c1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 295                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3212b29e33587a00fb1c83346f5dbfa69a458923                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x41f8d14c9475444f30a80431c68cf24dc9a8369a                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 39546                                                              |                                                              |

## 16. Table: IMBTC\_event\_Unpaused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-19 23:34:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9905851                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa098d093953b88b5a5837cc77dde828de722de656bd00f0e8d16150cf4f78c5f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 15                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3212b29e33587a00fb1c83346f5dbfa69a458923                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xb9e29984fe50602e7a619662ebed4f90d93824c7                         |                                                              |
