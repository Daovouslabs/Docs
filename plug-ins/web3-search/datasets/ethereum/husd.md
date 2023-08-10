# husd

## 1. Table: HUSDToken\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-11 18:53:30+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14367226                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2f5cf6e3568889a28364705ce02117e49c08d0438291fbd1d6890a681393002e             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 18                                                                             | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdf574c24545e5ffecb9a659c229253d4111d87e1                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x3982c74bde2ffbe023f392d46d76245b2ce183fb                                     |                                                              |
| spender           | VARCHAR   | 0x4c8cfe078a5b989cea4b330197246ced82764c63                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457575520676367639935 |                                                              |

## 2. Table: HUSDToken\_event\_BlacklistAdded\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |

## 3. Table: HUSDToken\_event\_BlacklistAdminAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-07-18 13:10:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8174895                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcb369bde289733f1d11843a9bdb1181e6764bdd6be4349505bffd52d8e1ece6e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 23                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdf574c24545e5ffecb9a659c229253d4111d87e1                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x2bd9caa19a724608bef32dd3c10c0fd1f70b309d                         |                                                              |

## 4. Table: HUSDToken\_event\_BlacklistAdminRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-07-18 13:16:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8174919                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x33f9d974d71ae64072db6664879067713ccd0c6e92306d3531dd8ddd98f3186d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdf574c24545e5ffecb9a659c229253d4111d87e1                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x6dc4b37ad025441ebc092f0f53ca6933fa1a3511                         |                                                              |

## 5. Table: HUSDToken\_event\_BlacklistRemoved\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |

## 6. Table: HUSDToken\_event\_CoinFactoryAdminRoleAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-23 09:20:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13281152                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x24666bf1cbe56195c47359e3ee41c2b9a6a15567f90417589ca28845946d8dce | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 52                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdf574c24545e5ffecb9a659c229253d4111d87e1                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x2bd9caa19a724608bef32dd3c10c0fd1f70b309d                         |                                                              |

## 7. Table: HUSDToken\_event\_CoinFactoryAdminRoleRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-23 09:29:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13281193                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbe3b7412209ddfa894c326535aed2173acc6b66493dd60cdc57453383b059d2f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 89                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdf574c24545e5ffecb9a659c229253d4111d87e1                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x2bd9caa19a724608bef32dd3c10c0fd1f70b309d                         |                                                              |

## 8. Table: HUSDToken\_event\_Issue\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-09 01:08:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10422293                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa30a37d2b2dd5b874e381439e04d87d2d904315982400da25db8261372ad3ba9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 26                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdf574c24545e5ffecb9a659c229253d4111d87e1                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x27856590347116b65915183c79a91ff7c37dc4b9                         |                                                              |
| amount            | VARCHAR   | 252190000000                                                       |                                                              |

## 9. Table: HUSDToken\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-07-18 13:13:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8174910                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x77c7819edbbfc513519bcd8ef93fe455e47945dd96e8a3fb9ee64d28672376da | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdf574c24545e5ffecb9a659c229253d4111d87e1                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x6dc4b37ad025441ebc092f0f53ca6933fa1a3511                         |                                                              |
| newOwner          | VARCHAR   | 0x2bd9caa19a724608bef32dd3c10c0fd1f70b309d                         |                                                              |

## 10. Table: HUSDToken\_event\_Paused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |

## 11. Table: HUSDToken\_event\_PauserAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-07-18 13:07:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8174882                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4eb79ea6f95f45edd817b0ca4499c80f226bbe5df190cc928a8112fea3663129 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 8                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdf574c24545e5ffecb9a659c229253d4111d87e1                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x2bd9caa19a724608bef32dd3c10c0fd1f70b309d                         |                                                              |

## 12. Table: HUSDToken\_event\_PauserRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-07-18 13:15:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8174916                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb218bd77c8ea87d9fd2b8d2cbaa87a7d1b698d76cea53120e4a662b64005436b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 32                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdf574c24545e5ffecb9a659c229253d4111d87e1                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x6dc4b37ad025441ebc092f0f53ca6933fa1a3511                         |                                                              |

## 13. Table: HUSDToken\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-16 07:42:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10469300                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x142aaa3072c4eabccec2c72956a1e39b9651ead9462227f5d1ba726ce2e9277e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdf574c24545e5ffecb9a659c229253d4111d87e1                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x13c9f04d7718845ac8c3e6844710cc5ede8902fb                         |                                                              |
| value             | VARCHAR   | 5992300000000                                                      |                                                              |

## 14. Table: HUSDToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-09 19:27:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14354462                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8c9839b0a1cd27296dc1574bf3239a419a4a88762fbde699cc8931008a5aaf82 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdf574c24545e5ffecb9a659c229253d4111d87e1                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x348937ee16cf28b7657d0b3d8f02c2264b245187                         |                                                              |
| value             | VARCHAR   | 350000000000                                                       |                                                              |

## 15. Table: HUSDToken\_event\_Unpaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |
