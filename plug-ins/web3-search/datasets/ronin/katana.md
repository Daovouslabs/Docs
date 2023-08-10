# katana

## 1. Table: UniswapV2Factory\_event\_PairCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-27 10:15:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10564608                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8052b813661ecc431ef4c91557b504d2b23114bb70ca10c056fc06a1d24c0119 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb255d6a720bb7c39fee173ce22113397119cb930                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0xc99a6a985ed2cac1ef41640596c5a5f9f4e19ef5                         |                                                              |
| token1            | VARCHAR   | 0xe514d9deb7966c8be0ca922de8a064264ea6bcd4                         |                                                              |
| pair              | VARCHAR   | 0x2ecb08f87f075b5769fe543d0e52e40140575ea7                         |                                                              |
| \_uint            | VARCHAR   | 4                                                                  |                                                              |

## 2. Table: UniswapV2Pair\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-08 09:26:10+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8263647                                                                        | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8077b98bd6d1c8dbfc9efa3be7499095561f512fe07d84345d572a9a1fad17ea             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                              | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc6344bc1604fcab1a5aad712d766796e2b7a70b9                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x064318327e40a789344eefe4f26d7be5bc028682                                     |                                                              |
| spender           | VARCHAR   | 0x487671acdea3745b6dac3ae8d1757b44a04bfe8a                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 3. Table: UniswapV2Pair\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-01 17:14:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 21168911                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf83c7e9b8776e3e131737afc505c4701a7d5ef43afed24f46232fc7f30eb2ec4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2ecb08f87f075b5769fe543d0e52e40140575ea7                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x7d0556d55ca1a92708681e2e231733ebd922597d                         |                                                              |
| amount0           | VARCHAR   | 33925703936169980                                                  |                                                              |
| amount1           | VARCHAR   | 67798372058115333740                                               |                                                              |
| to                | VARCHAR   | 0x7d0556d55ca1a92708681e2e231733ebd922597d                         |                                                              |

## 4. Table: UniswapV2Pair\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-20 08:36:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 26005257                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x400256f9f48216871563872d1e7536c187e1fdb73a4d023387f823bde4cb0937 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2ecb08f87f075b5769fe543d0e52e40140575ea7                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x7d0556d55ca1a92708681e2e231733ebd922597d                         |                                                              |
| amount0           | VARCHAR   | 8018550952725809                                                   |                                                              |
| amount1           | VARCHAR   | 21999999999999999861                                               |                                                              |

## 5. Table: UniswapV2Pair\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-31 13:48:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 18505399                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbad9b0f4e3f8c2f9786c579d54b45f0e874d825d4492d8f7b3a036ea8c60a223 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x306a28279d04a47468ed83d55088d0dcd1369294                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x7d0556d55ca1a92708681e2e231733ebd922597d                         |                                                              |
| amount0In         | VARCHAR   | 241                                                                |                                                              |
| amount1In         | VARCHAR   | 0                                                                  |                                                              |
| amount0Out        | VARCHAR   | 0                                                                  |                                                              |
| amount1Out        | VARCHAR   | 500000000000000                                                    |                                                              |
| to                | VARCHAR   | 0x24e3b9f5cc75135ead9519108261b110c63158c2                         |                                                              |

## 6. Table: UniswapV2Pair\_event\_Sync\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-21 00:32:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 26024367                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xae2b9ce6eeae1ad4453b733bb977d6ebc080327f724258045e89a6f37fd3f386 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x306a28279d04a47468ed83d55088d0dcd1369294                         | Address of the contract that produced the log                |
| reserve0          | VARCHAR   | 1404568840                                                         |                                                              |
| reserve1          | VARCHAR   | 1224431329342895066674                                             |                                                              |

## 7. Table: UniswapV2Pair\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-11 23:57:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16219165                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0cd89df3d90a702af0685989b0364653a5b37b52cfa59c7dd0363ad321aec81d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 24                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x306a28279d04a47468ed83d55088d0dcd1369294                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xe2002b767d828e747c35b88c72be39878a13dce0                         |                                                              |
| to                | VARCHAR   | 0x306a28279d04a47468ed83d55088d0dcd1369294                         |                                                              |
| value             | VARCHAR   | 7289039                                                            |                                                              |
