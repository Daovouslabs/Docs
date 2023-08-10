# gusd

## 1. Table: GUSD\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-17 14:11:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13043181                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x60c0296bb55d8513c74379976c13fdec22719323c353a3f3cb661247fbdd75df | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 20                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x056fd409e1d7a124bd7017459dfea2f387b6d5cd                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x316c387ec14a0d0c15ed8167ba98352059e568c6                         |                                                              |
| \_spender         | VARCHAR   | 0x7d2768de32b0b80b7a3454c06bdac94a69ddc7a9                         |                                                              |
| \_value           | VARCHAR   | 0                                                                  |                                                              |

## 2. Table: GUSD\_event\_CustodianChangeConfirmed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-09-09 20:05:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6301912                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x39e2cc095ea3f392819b8b67bbf943509e6d0fd20a0965265512219614f3ff21 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 12                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x056fd409e1d7a124bd7017459dfea2f387b6d5cd                         | Address of the contract that produced the log                |
| \_lockId          | VARCHAR   | 0x596c4c0e2d180de58b4cd1ba0c7300b5ca8924414c5411c26e0acd7eda553bc4 |                                                              |
| \_newCustodian    | VARCHAR   | 0x9a7b5f6e453d0cda978163cb4a9a88367250a52d                         |                                                              |

## 3. Table: GUSD\_event\_CustodianChangeRequested\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2019-05-08 21:55:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 7722535                                                            | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x7ac0783ce90fdc9543452e770ba61d0fee0a2ff0cafc4cc6f102c0f7ef7966b9 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 71                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x056fd409e1d7a124bd7017459dfea2f387b6d5cd                         | Address of the contract that produced the log                |
| \_lockId            | VARCHAR   | 0xc97e8f7f96a105da4f26021b89509d027cbe9a668b22fbd862b4b69267ac517e |                                                              |
| \_msgSender         | VARCHAR   | 0xcaec24669d6544c3b7c37b888b505cbd381d7059                         |                                                              |
| \_proposedCustodian | VARCHAR   | 0x37abd12b4c6af090a49408ba07d08c485a0b890b                         |                                                              |

## 4. Table: GUSD\_event\_ImplChangeConfirmed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-09-09 20:05:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6301912                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x39e2cc095ea3f392819b8b67bbf943509e6d0fd20a0965265512219614f3ff21 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 8                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x056fd409e1d7a124bd7017459dfea2f387b6d5cd                         | Address of the contract that produced the log                |
| \_lockId          | VARCHAR   | 0xf3add4d8825d90ad64898d4311c897af3ed9ee07e518dd7d2d77689a617619c6 |                                                              |
| \_newImpl         | VARCHAR   | 0x6704ba24b8640bccee6bf2fd276a6a1b8edf4ade                         |                                                              |

## 5. Table: GUSD\_event\_ImplChangeRequested\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-09-09 22:39:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6302567                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0d2667ced14c1c3e7d35bcae0159138af96cc39b451abfb5ad6799d44e496e58 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x056fd409e1d7a124bd7017459dfea2f387b6d5cd                         | Address of the contract that produced the log                |
| \_lockId          | VARCHAR   | 0xbfb47d60a214f99c85937862a5d5c5485d20770987529802a68fcadbcb4c4599 |                                                              |
| \_msgSender       | VARCHAR   | 0xd24400ae8bfebb18ca49be86258a3c749cf46853                         |                                                              |
| \_proposedImpl    | VARCHAR   | 0x516af4cce2e940aca3d28c1d5ff37a4146896755                         |                                                              |

## 6. Table: GUSD\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-27 23:57:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11141712                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc1b776cd41653574085930d46141955ef79eac877ff863a7b4a0114aa8fa6909 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 104                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x056fd409e1d7a124bd7017459dfea2f387b6d5cd                         | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0xec0d8d3ed5477106c6d4ea27d90a60e594693c90                         |                                                              |
| \_to              | VARCHAR   | 0x38148ecc2078da7f65e6233dda28efaf4c51e96f                         |                                                              |
| \_value           | VARCHAR   | 0                                                                  |                                                              |
