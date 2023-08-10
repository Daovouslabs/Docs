# thena

## 1. Table: ThenaPairFactory\_event\_PairCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-13 11:16:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29063971                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb396449e5c8e3257afc38ba876acfda7c8fc960eeb36138e15a88e8551063b10 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 135                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xafd89d21bdb66d00817d4153e055830b1c2b3970                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0x8ac76a51cc950d9822d68b83fe1ad97b32cd580d                         |                                                              |
| token1            | VARCHAR   | 0xd069599e718f963bd84502b49ba8f8657faf5b3a                         |                                                              |
| stable            | VARCHAR   | false                                                              |                                                              |
| pair              | VARCHAR   | 0x16184ec3a17285b33c22b6252c2d94ca54d03341                         |                                                              |
| noname            | VARCHAR   | 264                                                                |                                                              |

## 2. Table: ThenaPair\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-22 11:44:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30184473                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbc2dc1c72aa9f31a83fd7a3ff1812938dd19fc2a955c1b04fb6457eb03af4651 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 166                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfd66a4a4c921cd7194abab38655476a06fbaea05                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xe0578d897e85176f68759194136b1fbdfb876357                         |                                                              |
| spender           | VARCHAR   | 0x0cb5c6f56176a6acf5d5b381773b8b1065576e32                         |                                                              |
| amount            | VARCHAR   | 0                                                                  |                                                              |

## 3. Table: ThenaPair\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-04 14:20:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 27917787                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7a9a01f7c0407055e940bfeafdabb5302e1dcdefd17e01c08844eaee48b4f42b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 404                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x618f9eb0e1a698409621f4f487b563529f003643                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x1f5247c524c2c438d743c1c2f254b1bf62e0b5ce                         |                                                              |
| amount0           | VARCHAR   | 18796571150273062359                                               |                                                              |
| amount1           | VARCHAR   | 21201314931445803315                                               |                                                              |
| to                | VARCHAR   | 0x2201daa87a41802fa31379cd39ab05c852ccadf2                         |                                                              |

## 4. Table: ThenaPair\_event\_Claim\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-18 10:58:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29207262                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaa6c11c2bd6352b1ff194ef84c61726e744fd572be2631df8d932f0812da8933 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 146                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9798a3835c8c87bd92803c3a248ae0042fbe4c6c                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xc4dd018f8c281bd4a7df9777546d1c0fde3826f9                         |                                                              |
| recipient         | VARCHAR   | 0xc4dd018f8c281bd4a7df9777546d1c0fde3826f9                         |                                                              |
| amount0           | VARCHAR   | 13699681685775250                                                  |                                                              |
| amount1           | VARCHAR   | 39758442365350                                                     |                                                              |

## 5. Table: ThenaPair\_event\_Fees\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-29 12:01:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 28633856                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf7e3dfb38db6a9c42eddec650fb569999f952f6b16423f16456173cf3210ce36 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 235                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x948c553d8c25ad7bd034086f0aae9a9d3c028b90                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x0000000000008afdacc486225455281f614843e7                         |                                                              |
| amount0           | VARCHAR   | 393011717522829247                                                 |                                                              |
| amount1           | VARCHAR   | 0                                                                  |                                                              |

## 6. Table: ThenaPair\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-07 20:46:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 28902918                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe54a1502de3ffb5dfe07e004bf2c6a0ad609e3a9b80fa1f7d7e3b7ea4e8e3b62 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 284                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x075e794f631ee81df1aadb510ac6ec8803b0fa35                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x20a304a7d126758dfe6b243d0fc515f83bca8431                         |                                                              |
| amount0           | VARCHAR   | 1690004301495044060                                                |                                                              |
| amount1           | VARCHAR   | 24612787329933436                                                  |                                                              |

## 7. Table: ThenaPair\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-04 12:42:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30558840                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8195ca419729170e58a65f31ab686a34529aec57409c5d059671677112dbafdc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 285                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x93b32a8dfe10e9196403dd111974e325219aec24                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x00000000000e8716b4e2d12400a01474cdfad760                         |                                                              |
| amount0In         | VARCHAR   | 0                                                                  |                                                              |
| amount1In         | VARCHAR   | 790500000000000000000                                              |                                                              |
| amount0Out        | VARCHAR   | 790882953081535037482                                              |                                                              |
| amount1Out        | VARCHAR   | 0                                                                  |                                                              |
| to                | VARCHAR   | 0x00000000000e8716b4e2d12400a01474cdfad760                         |                                                              |

## 8. Table: ThenaPair\_event\_Sync\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-30 04:52:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 28654050                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x596457470710c2c497abd285f9474bbf30c6ff0e91d77acbb9c585de7d6f1ee3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 87                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x150990b9630ffe2322999e86905536e2e7e8d93f                         | Address of the contract that produced the log                |
| reserve0          | VARCHAR   | 170634546                                                          |                                                              |
| reserve1          | VARCHAR   | 138924421634315171484                                              |                                                              |

## 9. Table: ThenaPair\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-23 23:44:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30227566                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcabfa1dcb16beb2fc827ec32612ea80dc39ca885c8a49d198a5b781dca34d69f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 112                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x04d6115703b0127888323f142b8046c7c13f857d                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x04d6115703b0127888323f142b8046c7c13f857d                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| amount            | VARCHAR   | 750000000000000000000                                              |                                                              |
