# mdex

## 1. Table: MdexFactory\_event\_PairCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-06 11:38:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 24549686                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x31b881b6c2848b02a4fa9695e19b5a37c593b9509a9809e9dbd54dd8a6edc43f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 169                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3cd1c46068daea5ebb0d3f55f6915b10648062b8                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0x9c65ab58d8d978db963e63f2bfb7121627e3a739                         |                                                              |
| token1            | VARCHAR   | 0xbec041bc90cae81596df063c3eee4e858fc3903d                         |                                                              |
| pair              | VARCHAR   | 0x6c253bd815dab495d0d6fa6fd909a8bd559def21                         |                                                              |
| unnamedField0     | VARCHAR   | 1966                                                               |                                                              |

## 2. Table: MdexPair\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-25 23:30:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 26784099                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3cc6479692b3fa60e910996531f81ced9a6211ddb374f03b180447444dbd1a16 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 486                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0fb881c078434b1c0e4d0b64d8c64d12078b7ce2                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x5940760382caebf45463cf8845e610820d3c51d5                         |                                                              |
| spender           | VARCHAR   | 0xc48fe252aa631017df253578b1405ea399728a50                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 3. Table: MdexPair\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-06 16:35:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16713825                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6b70449b50966523ed5bfdb3b381838da4adeea6a7e27c5e41441e19484b2cc8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 500                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x03406fffdd9725c6bcca9531b90618af9567298c                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x0384e9ad329396c3a6a401243ca71633b2bc4333                         |                                                              |
| amount0           | VARCHAR   | 94879656225233302714569                                            |                                                              |
| amount1           | VARCHAR   | 173295702405101121672                                              |                                                              |
| to                | VARCHAR   | 0x80ad7e8cdc26606abb84d7da7680466d11db8359                         |                                                              |

## 4. Table: MdexPair\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-19 09:35:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30095723                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdba9e7652c3392e9a86f5bccb55ba0249803af6ec4e9eb38361d8076265de8b0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 106                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0fb881c078434b1c0e4d0b64d8c64d12078b7ce2                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x62c1a0d92b09d0912f7bb9c96c5ecdc7f2b87059                         |                                                              |
| amount0           | VARCHAR   | 25478531901747240482                                               |                                                              |
| amount1           | VARCHAR   | 48631234763968219040656                                            |                                                              |

## 5. Table: MdexPair\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-25 02:08:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 28506998                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb0ae68dcaec207a8156008e440944341937ac440410f28b8f34c36f82f7ad8af | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 201                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x09cb618bf5ef305fadfd2c8fc0c26eecf8c6d5fd                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x0000000000008afdacc486225455281f614843e7                         |                                                              |
| amount0In         | VARCHAR   | 893493706412904092660                                              |                                                              |
| amount1In         | VARCHAR   | 0                                                                  |                                                              |
| amount0Out        | VARCHAR   | 0                                                                  |                                                              |
| amount1Out        | VARCHAR   | 2929411321878429058                                                |                                                              |
| to                | VARCHAR   | 0x0000000000008afdacc486225455281f614843e7                         |                                                              |

## 6. Table: MdexPair\_event\_Sync\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-12 23:10:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 20389314                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9468d610b2c3c733ea52c117a99c7783ed30cd2dd1b2b24af7e0a3191de9cdd7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xab04846adf0404904cea92e47313c6aecda42254                         | Address of the contract that produced the log                |
| reserve0          | VARCHAR   | 166682432364234772959648                                           |                                                              |
| reserve1          | VARCHAR   | 3294575513224559633                                                |                                                              |

## 7. Table: MdexPair\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-19 09:35:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30095723                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdba9e7652c3392e9a86f5bccb55ba0249803af6ec4e9eb38361d8076265de8b0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 103                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0fb881c078434b1c0e4d0b64d8c64d12078b7ce2                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xcea6d1c73733074ed2d3bdd32b9186b60d60e6f5                         |                                                              |
| value             | VARCHAR   | 754369224116917                                                    |                                                              |
