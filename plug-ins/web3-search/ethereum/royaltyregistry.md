# royaltyregistry

## 1. Table: RoyaltyRegistry\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-23 21:40:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13476288                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8788c66b4b3201ba2f40461af0d60b8fc8f1f2b4802062bad021b7dec89124a0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 507                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xad2184fb5dbcfc05d8f056542fb25b04fa32a95d                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0xa8863bf1c8933f649e7b03eb72109e5e187505ea                         |                                                              |
| newOwner          | VARCHAR   | 0xa70e7ef659c209d977f0f5ab932f3f775a94502f                         |                                                              |

## 2. Table: RoyaltyRegistry\_event\_RoyaltyOverride\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-13 22:44:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17474123                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x66688b0ea1cbe96b4576815dc097d76e456e73ca663b7b0632e170ccc4a16c5c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 171                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xad2184fb5dbcfc05d8f056542fb25b04fa32a95d                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x14254028d2d13e02d9af0ad5f64dc7444cf1c311                         |                                                              |
| tokenAddress      | VARCHAR   | 0x21a33bd03bbdae981b20da5cc8cfae86511511ff                         |                                                              |
| royaltyAddress    | VARCHAR   | 0xe82149c4cf61f70f6d839d674ca9519eb587a2f7                         |                                                              |
