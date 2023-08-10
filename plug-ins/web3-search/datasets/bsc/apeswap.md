# apeswap

## 1. Table: ApeFactory\_event\_PairCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-14 00:33:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4859169                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5054ab3959db539452b1696b188036a7711657583fef2ba5bf4280405f3357a1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 85                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0841bd0b734e4f5853f0dd8d7ea041c241fb0da6                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0x603c7f932ed1fc6575303d8fb018fdcbb0f39a95                         |                                                              |
| token1            | VARCHAR   | 0xbb4cdb9cbd36b01bd1cbaebf2de08d9173bc095c                         |                                                              |
| pair              | VARCHAR   | 0xf65c1c0478efde3c19b49ecbe7acc57bb6b1d713                         |                                                              |
| unnamedField0     | VARCHAR   | 4                                                                  |                                                              |

## 2. Table: ApePair\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-01 02:45:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 28709022                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x74cd33faa90f64884c5fee87d0ea11c9deb9338a292784f3473a64b44b94d620 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 179                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x79f1868a47532542687ca019447dfb150b03a682                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x571baca19e11f6e49c6f21923f1555930532340a                         |                                                              |
| spender           | VARCHAR   | 0x0000000000000000000000000000000000000001                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 3. Table: ApePair\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-28 14:49:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30360417                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2464fd27f8190e186263a7dc86c9af176896aa37a00399e03b1a5ec6ddc93702 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 92                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0d70924695b6ae496f0a74a36bf79d47307dd519                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xcf0febd3f17cef5b47b0cd257acf6025c5bff3b7                         |                                                              |
| amount0           | VARCHAR   | 264729927707825251                                                 |                                                              |
| amount1           | VARCHAR   | 367778302                                                          |                                                              |
| to                | VARCHAR   | 0x0783f67f30e7a520b55e22eb78d65508ad0a1245                         |                                                              |

## 4. Table: ApePair\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-11 10:41:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 28114737                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x160514fb6a719e6ec6cc6b210ff26a5847c4515d2c6696f9e588ab33069c7032 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 222                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x01eed6e622fa2e652b0796a29d98fe82056fb8f0                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xcf0febd3f17cef5b47b0cd257acf6025c5bff3b7                         |                                                              |
| amount0           | VARCHAR   | 4226835347                                                         |                                                              |
| amount1           | VARCHAR   | 64649999992641241888                                               |                                                              |

## 5. Table: ApePair\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-28 01:52:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30344947                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa23735fdd5b03fd225d797725071be232e76b7f2a0ac3a2739ad0d5b04d1e8ff | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 128                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x56def80e01dfd3ff1bfcb41bbdc380887d56d946                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x00000000000061ab74e8283239e8c4e9d2dfed3e                         |                                                              |
| amount0In         | VARCHAR   | 0                                                                  |                                                              |
| amount1In         | VARCHAR   | 58511248193704256926971                                            |                                                              |
| amount0Out        | VARCHAR   | 302960841523875973                                                 |                                                              |
| amount1Out        | VARCHAR   | 0                                                                  |                                                              |
| to                | VARCHAR   | 0x00000000000061ab74e8283239e8c4e9d2dfed3e                         |                                                              |

## 6. Table: ApePair\_event\_Sync\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-05 21:36:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30598113                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb57587ae2af23171848c2d157c4166549bf47d3e1a5960382f1a66bcb68b2bad | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 235                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x004f72d474ee262701205e3637b4367594efb11d                         | Address of the contract that produced the log                |
| reserve0          | VARCHAR   | 775558627048090003052692                                           |                                                              |
| reserve1          | VARCHAR   | 1743623680186896484453                                             |                                                              |

## 7. Table: ApePair\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-05 19:29:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30595591                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa49ed4505bf6b849be43f74b30ecfc99e96144bd4eac5eb466ea5902a7151bef | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 39                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0deb588c1ec6f1d9f348126d401f05c4c7b7a80c                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x7bfcd7d5d95b7ce2c4cf30d9e0ab535ed5d34968                         |                                                              |
| value             | VARCHAR   | 53049714330923691                                                  |                                                              |

## 8. Table: MasterApeAdmin\_event\_AddFarm\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-06 20:02:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 19322284                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7c5123c4e19ea7a7cd35775769dc84e3f322a6c4939fa50d97f401da6fc64b8e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 508                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9fed2bc7f0b4f4350b52e29e0a3c2bf5ebc3cc0a                         | Address of the contract that produced the log                |
| lpToken           | VARCHAR   | 0xe6ff591f818664865ecab584b1fe679dbb4904db                         |                                                              |
| allocation        | VARCHAR   | 700                                                                |                                                              |

## 9. Table: MasterApeAdmin\_event\_AddFixedPercentFarm\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2022-02-16 18:15:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 15313091                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x6fbdec3b3a1005f7289d00c53557666a1fc45c673149a81a2b7b1787dcf0a41f | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 222                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x9fed2bc7f0b4f4350b52e29e0a3c2bf5ebc3cc0a                         | Address of the contract that produced the log                |
| pid                  | VARCHAR   | 112                                                                |                                                              |
| allocationPercentage | VARCHAR   | 155                                                                |                                                              |

## 10. Table: MasterApeAdmin\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-09 23:33:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15118304                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xab4fe0676146801c5e3259a43bc8da45079a5aa7456fbf6c7ebafc5dd06bef6b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9fed2bc7f0b4f4350b52e29e0a3c2bf5ebc3cc0a                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0xae9e0ca1f4424edc2fc49e47be9a4f6448a0d251                         |                                                              |
| newOwner          | VARCHAR   | 0x211cbf06441beb429677a011ead947eb6716054e                         |                                                              |

## 11. Table: MasterApeAdmin\_event\_SetFarm\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-16 15:24:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 18741889                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb5f8ad8492c3f89609960fc9cddbd333057d993db8ff57faf7c6b8fc150d60f7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 555                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9fed2bc7f0b4f4350b52e29e0a3c2bf5ebc3cc0a                         | Address of the contract that produced the log                |
| pid               | VARCHAR   | 178                                                                |                                                              |
| allocation        | VARCHAR   | 46                                                                 |                                                              |

## 12. Table: MasterApeAdmin\_event\_SetFixedPercentFarm\_history

| Column                       | Type      | Example                                                            | Description                                                  |
| ---------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp             | TIMESTAMP | 2023-01-24 19:17:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number                | INTEGER   | 25071862                                                           | The block number where this event was emitted                |
| transaction\_hash            | VARCHAR   | 0xdc9f20969e152d5d2e1081976ae2305a881fbbb3e4f8bc9f0e0c8cadf2da9615 | Hash of the transactions in which this event was emitted     |
| log\_index                   | INTEGER   | 212                                                                | Integer of the log index position in the block of this event |
| contract\_address            | VARCHAR   | 0x9fed2bc7f0b4f4350b52e29e0a3c2bf5ebc3cc0a                         | Address of the contract that produced the log                |
| pid                          | VARCHAR   | 112                                                                |                                                              |
| previousAllocationPercentage | VARCHAR   | 155                                                                |                                                              |
| allocationPercentage         | VARCHAR   | 0                                                                  |                                                              |

## 13. Table: MasterApeAdmin\_event\_SetPendingMasterApeOwner\_history

| Column                | Type      | Example                                                            | Description                                                  |
| --------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp      | TIMESTAMP | 2023-01-27 17:32:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number         | INTEGER   | 25155061                                                           | The block number where this event was emitted                |
| transaction\_hash     | VARCHAR   | 0xb7906a88b75b5dfe4812efa63905b38c88943c68f89b969edc3e5c964a7ac041 | Hash of the transactions in which this event was emitted     |
| log\_index            | INTEGER   | 188                                                                | Integer of the log index position in the block of this event |
| contract\_address     | VARCHAR   | 0x9fed2bc7f0b4f4350b52e29e0a3c2bf5ebc3cc0a                         | Address of the contract that produced the log                |
| pendingMasterApeOwner | VARCHAR   | 0x7b26a27af246b4e482f37ef24e9a3f83c3fc7f1c                         |                                                              |

## 14. Table: MasterApeAdmin\_event\_SweepWithdraw\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| to                | VARCHAR   |                                                              |             |
| token             | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 15. Table: MasterApeAdmin\_event\_SyncFixedPercentFarm\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-01 21:30:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15690020                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4a72ad84b42d968169a992262b7218fd54a5e1ec5aa97aba6be675afed7db7c2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9fed2bc7f0b4f4350b52e29e0a3c2bf5ebc3cc0a                         | Address of the contract that produced the log                |
| pid               | VARCHAR   | 112                                                                |                                                              |
| allocation        | VARCHAR   | 365                                                                |                                                              |

## 16. Table: MasterApeAdmin\_event\_TransferredFarmAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousFarmAdmin | VARCHAR   |                                                              |             |
| newFarmAdmin      | VARCHAR   |                                                              |             |

## 17. Table: MasterApe\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-02 22:56:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 25331095                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd9074cb0a9f3423c837fb073316606f355241b69af15e4bc83904b010ddb3a19 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 42                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5c8d727b265dbafaba67e050f2f739caeeb4a6f9                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x1386ac5f7f6a866fdf2a38d2d56ebd315e48aaab                         |                                                              |
| pid               | VARCHAR   | 0                                                                  |                                                              |
| amount            | VARCHAR   | 95397545785989                                                     |                                                              |

## 18. Table: MasterApe\_event\_EmergencyWithdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-11 17:37:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9069071                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb7ef282953716e229fc938bd74b9be84e5df215b991f00d40907541c428fa055 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 400                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5c8d727b265dbafaba67e050f2f739caeeb4a6f9                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xf0eee33f9382cc5c93b833765189e085e0b81bad                         |                                                              |
| pid               | VARCHAR   | 90                                                                 |                                                              |
| amount            | VARCHAR   | 977641400656758                                                    |                                                              |

## 19. Table: MasterApe\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-27 20:05:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 25158062                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4bd9a1cccaae1f2432b28d79275f2364657cb3e634deca9a867b93fa49f1499f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 62                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5c8d727b265dbafaba67e050f2f739caeeb4a6f9                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x9fed2bc7f0b4f4350b52e29e0a3c2bf5ebc3cc0a                         |                                                              |
| newOwner          | VARCHAR   | 0x7b26a27af246b4e482f37ef24e9a3f83c3fc7f1c                         |                                                              |

## 20. Table: MasterApe\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-28 11:25:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 28604365                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xface91130060b14df769173e426203aab3b81b1d1080b8d8e188f1992d159c5c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 117                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5c8d727b265dbafaba67e050f2f739caeeb4a6f9                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xfdc1def4465eb71b920d7b040aa897e80bfa8f4e                         |                                                              |
| pid               | VARCHAR   | 0                                                                  |                                                              |
| amount            | VARCHAR   | 0                                                                  |                                                              |
