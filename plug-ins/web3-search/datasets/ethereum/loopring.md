# loopring

## 1. Table: ExchangeV3\_event\_BlockSubmitted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-18 14:39:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14411029                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xae96adc743c2536423ae518369d25f3d081309f5755f5880f48db76c53a6d8a2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 422                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0baba1ad5be3a5c0a66e7ac838a129bf948f1ea4                         | Address of the contract that produced the log                |
| blockIdx          | VARCHAR   | 18113                                                              |                                                              |
| merkleRoot        | VARCHAR   | 0x05d4f0910a34ee3532ba7bf643bc24f0383b7767d87b5fb0d70d16e8c56948f9 |                                                              |
| publicDataHash    | VARCHAR   | 0x08217e73907a1412f3fb39c1db6684106c17489b40a0b58b4daa884156507f30 |                                                              |
