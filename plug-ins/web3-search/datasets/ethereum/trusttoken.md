# trusttoken

## 1. Table: TrueAUD\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-07 07:54:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14338524                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x518960dc8c6644d8b2a4eab5f7c8989cbe8fec181e5aa011003847f822783dc6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 103                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00006100f7090010005f1bd7ae6122c3c2cf0090                         | Address of the contract that produced the log                |
| burner            | VARCHAR   | 0x0000000000000000000000000000000000002768                         |                                                              |
| value             | VARCHAR   | 1000000000000000000000                                             |                                                              |

## 2. Table: TrueAUD\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-17 08:32:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13631891                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x84c8be27c10b468581eeeced1e51f2a4038edfab7458c14f1e8f4ec311169d81 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 15                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00006100f7090010005f1bd7ae6122c3c2cf0090                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0x60631917901e4d02a069923edd711c6d79669ecb                         |                                                              |
| value             | VARCHAR   | 24982000000000000000000                                            |                                                              |

## 3. Table: TrueAUD\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-06 21:46:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11004688                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x94abcbafee2e573b62de9c11ccdb121a5adb49705e8418775598629d62002ecd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 50                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00006100f7090010005f1bd7ae6122c3c2cf0090                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x57723e44795380108b331359f1355be82ba74742                         |                                                              |
| to                | VARCHAR   | 0xe95cf808de0bc4b1d9eeb7ae5d11803a8f834477                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 4. Table: TrueCAD\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-01 15:54:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14501289                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x70e39b6994c1173134b3484f19174b8d5802a2fab118a6d933fa573a14708534 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 58                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000100f2a2bd000715001920eb70d229700085                         | Address of the contract that produced the log                |
| burner            | VARCHAR   | 0x00000000000000000000000000000000000013aa                         |                                                              |
| value             | VARCHAR   | 8731840000000000000000                                             |                                                              |

## 5. Table: TrueCAD\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-15 05:48:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10068952                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd11b2191e825ede381f32891a48e7d5cc14b570976830af7f57657abc54dccfd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 53                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000100f2a2bd000715001920eb70d229700085                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0x855d1320a5144671830894a693b9180e4b00ea38                         |                                                              |
| value             | VARCHAR   | 864680000000000000000                                              |                                                              |

## 6. Table: TrueCAD\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-06 10:03:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11984199                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xeda310f9dc9fffb137f4794492121f8e1d29aba0ab2d0b058140eca4e3c900b3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 226                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000100f2a2bd000715001920eb70d229700085                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x6765764a46f69871bd4b854230c33cd1c81c6313                         |                                                              |
| to                | VARCHAR   | 0x6262998ced04146fa42253a5c0af90ca02dfd2a3                         |                                                              |
| value             | VARCHAR   | 150147131481555046584                                              |                                                              |

## 7. Table: TrueGBP\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-08 02:54:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16137139                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x17f8835b849939c179b350fa2bf73dc79b9b032863e3153674b5d6e8515d01d2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 37                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000441378008ea67f4284a57932b1c000a5                         | Address of the contract that produced the log                |
| burner            | VARCHAR   | 0x0000000000000000000000000000000000001b2f                         |                                                              |
| value             | VARCHAR   | 1500000000000000000000000                                          |                                                              |

## 8. Table: TrueGBP\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-31 04:01:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12144850                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x72a9974df6a42a6a689583c0063619d5772c51460e79c2f0ef62ca1b27d1f87b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 45                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000441378008ea67f4284a57932b1c000a5                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0xef2a4650299bb152681a1b6c685962ee49a6a2c6                         |                                                              |
| value             | VARCHAR   | 5904340000000000000000                                             |                                                              |

## 9. Table: TrueGBP\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-11 17:23:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13985578                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe3d55f7ac17caf18cb5366aeba9645592795f33e8167fc439d846529aa829d15 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 315                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000441378008ea67f4284a57932b1c000a5                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x2d187a560cfbd28e1eb2f68534754b0f120459a9                         |                                                              |
| to                | VARCHAR   | 0x9bbce7cd919f11e13bd2a642c88966af551ff05a                         |                                                              |
| value             | VARCHAR   | 2638661443372225751380                                             |                                                              |

## 10. Table: TrueHKD\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-11 04:32:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14182611                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0c04327a11627e80f5f40ab187a399725f29932d850da97571e96c2dea45e540 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 331                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0000852600ceb001e08e00bc008be620d60031f2                         | Address of the contract that produced the log                |
| burner            | VARCHAR   | 0x000000000000000000000000000000000000261c                         |                                                              |
| value             | VARCHAR   | 10200000000000000000000                                            |                                                              |

## 11. Table: TrueHKD\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-04 04:18:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11969550                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x24ebbd69d3945f2f2d32b344f149e0d297bd487280541a66ea92830987ba0147 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 128                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0000852600ceb001e08e00bc008be620d60031f2                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0x43e8a94ecd7819546f0d3383e41787536f4d9de7                         |                                                              |
| value             | VARCHAR   | 20000000000000000000000                                            |                                                              |

## 12. Table: TrueHKD\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-17 09:32:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13041929                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5bb5a02c0c15815d98cdd7f8606528043eacdefdaed2e75e93a194009ad5bd97 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 498                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0000852600ceb001e08e00bc008be620d60031f2                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x6f13badb04d0c65889bee666770642ace78bbab2                         |                                                              |
| to                | VARCHAR   | 0x4f6742badb049791cd9a37ea913f2bac38d01279                         |                                                              |
| value             | VARCHAR   | 62000000000000000000000                                            |                                                              |

## 13. Table: TrueUSDLegacy\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-09-30 23:24:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6430122                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdbe5f902abd85b67052f096607ae16683eb074cfe6f3b66b380872b0e32cb1c5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 16                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8dd5fbce2f6a956c3022ba3663759011dd51e73e                         | Address of the contract that produced the log                |
| burner            | VARCHAR   | 0x5afd2e05b52b950f73dfe7cd2728d0bad06587b4                         |                                                              |
| value             | VARCHAR   | 499996000000000000000000                                           |                                                              |

## 14. Table: TrueUSDLegacy\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-11-29 02:28:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6791718                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb97cc77ded72b80cdca9d360e2c80073850aa688b716153e7460714ec794489b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8dd5fbce2f6a956c3022ba3663759011dd51e73e                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0x619f27498ae534a14877b05034b0ae7773394fb9                         |                                                              |
| amount            | VARCHAR   | 250000000000000000000000                                           |                                                              |

## 15. Table: TrueUSDLegacy\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-04-30 18:59:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5533627                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0add252af1e190f6a8af3488305c56fbb845b1167f6f48a204bd4d03b5b9a815 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 37                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8dd5fbce2f6a956c3022ba3663759011dd51e73e                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xc486d1d6933041c9c1f86c7d663da9fdb93c51af                         |                                                              |
| to                | VARCHAR   | 0xe4c89b9fcab29c5bee3971b698cca4528f2644e2                         |                                                              |
| value             | VARCHAR   | 63170314000000000000                                               |                                                              |

## 16. Table: TrueUSD\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-07 15:09:22+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15491006                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb71bdfe9cec3bbd7c1d2b5356391d92aeba92d7d9f2f0169e94653182a7593c3             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 343                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0000000000085d4780b73119b644ae5ecd22b376                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xd41997923dbd65c5a20ebc3b759cc0136f6eb9f7                                     |                                                              |
| spender           | VARCHAR   | 0x11111112542d85b3ef69ae05771c2dccff4faa26                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 17. Table: TrueUSD\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-11 08:53:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12805047                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe12c080686225ed6ba001ecee4de27e932ba82c837d0590b019ea001a79ae673 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 46                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0000000000085d4780b73119b644ae5ecd22b376                         | Address of the contract that produced the log                |
| burner            | VARCHAR   | 0x0000000000000000000000000000000000000bc8                         |                                                              |
| value             | VARCHAR   | 173596000000000000000000                                           |                                                              |

## 18. Table: TrueUSD\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-06 02:41:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17418515                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1ea5ccd48e36c34802044b804da03c06322963494437ea809c22b852091c8ed4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 193                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0000000000085d4780b73119b644ae5ecd22b376                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0x17ddc84bfb988452adb561ed5f80eea8ed48f848                         |                                                              |
| value             | VARCHAR   | 100000000000000000000000                                           |                                                              |

## 19. Table: TrueUSD\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-04 02:59:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7006712                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x81c880de8f67362cb4792990560a6adf9aab819bbe28e334867ce8e4f88415a6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 97                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0000000000085d4780b73119b644ae5ecd22b376                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0xcdbd95534b5a980f33d1acdee4db7cc1eb8a31de                         |                                                              |
| newOwner          | VARCHAR   | 0x000000eade0fe9269d0412a6055b6f3c5d968488                         |                                                              |

## 20. Table: TrueUSD\_event\_SetBurnBounds\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-21 20:50:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7105482                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc82da213228c4eff77039d53b676c81e805ff0d41ae75ada37656a4a50e4cf06 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 168                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0000000000085d4780b73119b644ae5ecd22b376                         | Address of the contract that produced the log                |
| newMin            | VARCHAR   | 1000000000000000000000                                             |                                                              |
| newMax            | VARCHAR   | 1000000000000000000000000000                                       |                                                              |

## 21. Table: TrueUSD\_event\_SetRegistry\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-04 02:59:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7006712                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x81c880de8f67362cb4792990560a6adf9aab819bbe28e334867ce8e4f88415a6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 110                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0000000000085d4780b73119b644ae5ecd22b376                         | Address of the contract that produced the log                |
| registry          | VARCHAR   | 0x0000000000013949f288172bd7e36837bddc7211                         |                                                              |

## 22. Table: TrueUSD\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-17 09:47:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15358027                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7b8589146ad51071730a097124c3d677592738c662c60acea7280bd0e23b1bcb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 210                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0000000000085d4780b73119b644ae5ecd22b376                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xc8de1ec4b29c774470814b257418f787a55946c4                         |                                                              |
| to                | VARCHAR   | 0x39f6a6c85d39d5abad8a398310c52e7c374f2ba3                         |                                                              |
| value             | VARCHAR   | 96980000000000000000                                               |                                                              |

## 23. Table: TrueUSD\_event\_WipeBlacklistedAccount\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |
| balance           | VARCHAR   |                                                              |             |
