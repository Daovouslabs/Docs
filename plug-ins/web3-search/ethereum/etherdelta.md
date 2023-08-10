# etherdelta

## 1. Table: EtherDelta2\_event\_Cancel\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-12 03:57:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16166092                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9c910648d06495867f5f6f5e8a8feb035df174b93689ae7cb8b3e61369469203 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 171                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8d12a197cb00d4747a1fe03395095ce2a5cc6819                         | Address of the contract that produced the log                |
| tokenGet          | VARCHAR   | 0xc27a2f05fa577a83ba0fdb4c38443c0718356501                         |                                                              |
| amountGet         | VARCHAR   | 30000000000000000000000                                            |                                                              |
| tokenGive         | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| amountGive        | VARCHAR   | 37035000000000000                                                  |                                                              |
| expires           | VARCHAR   | 16465189                                                           |                                                              |
| nonce             | VARCHAR   | 3450718096                                                         |                                                              |
| user              | VARCHAR   | 0x23f6992498d5aad0f79ab8cf2e1bff650891a28e                         |                                                              |
| v                 | VARCHAR   | 27                                                                 |                                                              |
| r                 | VARCHAR   | 0x2dde64b7866234365e7c3ca4d68013e2eef97bacb8f1b55b5db5a9a2425ea9e2 |                                                              |
| s                 | VARCHAR   | 0x0367d40c64bbf040ed93213e01ea63bb54f3807892d8045fa475a61c7c9d56c3 |                                                              |

## 2. Table: EtherDelta2\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-11 07:42:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11833978                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3efc137b1c422f688f18ed4c42cf7527073c7535d2223799fe2304dbc8ed6611 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 186                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8d12a197cb00d4747a1fe03395095ce2a5cc6819                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| user              | VARCHAR   | 0x0000000000007f150bd6f54c40a34d7c3d5e9f56                         |                                                              |
| amount            | VARCHAR   | 120374999999999999                                                 |                                                              |
| balance           | VARCHAR   | 120375000000000000                                                 |                                                              |

## 3. Table: EtherDelta2\_event\_Order\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-03-07 13:34:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5212849                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x017efa2c8e63c09332a37d1d637f4deee9c7893129e4b1b12b30ed604aff0d78 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 83                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8d12a197cb00d4747a1fe03395095ce2a5cc6819                         | Address of the contract that produced the log                |
| tokenGet          | VARCHAR   | 0xd26114cd6ee289accf82350c8d8487fedb8a0c07                         |                                                              |
| amountGet         | VARCHAR   | 1000000000000000                                                   |                                                              |
| tokenGive         | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| amountGive        | VARCHAR   | 30000000000000000                                                  |                                                              |
| expires           | VARCHAR   | 5213791                                                            |                                                              |
| nonce             | VARCHAR   | 12                                                                 |                                                              |
| user              | VARCHAR   | 0x25fbd417c40efef45d5e96d0681900000006a32a                         |                                                              |

## 4. Table: EtherDelta2\_event\_Trade\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-04 20:25:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11590154                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x78f4770c5e25e4284f10f2cd188d293db37d4aa9db00dd25b7767fe0b245f2a3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 196                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8d12a197cb00d4747a1fe03395095ce2a5cc6819                         | Address of the contract that produced the log                |
| tokenGet          | VARCHAR   | 0x0d8775f648430679a709e98d2b0cb6250d2887ef                         |                                                              |
| amountGet         | VARCHAR   | 398803589232303090604                                              |                                                              |
| tokenGive         | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| amountGive        | VARCHAR   | 103038484546360917                                                 |                                                              |
| get               | VARCHAR   | 0xb288b361fa44d8c8f27b57e459ac22e622cfb3f8                         |                                                              |
| give              | VARCHAR   | 0x0000000000007f150bd6f54c40a34d7c3d5e9f56                         |                                                              |

## 5. Table: EtherDelta2\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-21 11:23:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16676556                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x60b872dc74cd5777135f57c282899c299a546831039b98719f1f4e4f6db02e35 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 120                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8d12a197cb00d4747a1fe03395095ce2a5cc6819                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| user              | VARCHAR   | 0x2359548e0db093a33989d5097b2ea57e2efdc8fa                         |                                                              |
| amount            | VARCHAR   | 5600000000000000                                                   |                                                              |
| balance           | VARCHAR   | 0                                                                  |                                                              |

## 6. Table: EtherDelta\_event\_Cancel\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2016-09-11 16:01:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 2240585                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0922ece682700c3779fd6db2e09322b38f6ef7ae423d64dd4528a560e1d842c3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4aea7cf559f67cedcad07e12ae6bc00f07e8cf65                         | Address of the contract that produced the log                |
| tokenGet          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| amountGet         | VARCHAR   | 24000000000000000000                                               |                                                              |
| tokenGive         | VARCHAR   | 0xd8912c10681d8b21fd3742244f44658dba12264e                         |                                                              |
| amountGive        | VARCHAR   | 60000000000000000000                                               |                                                              |
| expires           | VARCHAR   | 2243055                                                            |                                                              |
| nonce             | VARCHAR   | 164557414                                                          |                                                              |
| user              | VARCHAR   | 0xeedf910b780cd988192f122c24310fd375b31f44                         |                                                              |
| v                 | VARCHAR   | 27                                                                 |                                                              |
| r                 | VARCHAR   | 0xe1f66130f67ee4c5209dcc5080c2721c310a4b4371578687f7464c6a846bbf0c |                                                              |
| s                 | VARCHAR   | 0x3fe44c4fea646fb0d1266963996e7323858aeb7ba3014f6666f852b4ff4d228b |                                                              |

## 7. Table: EtherDelta\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2017-08-12 14:01:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4148761                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe0503e8beccf7693649055085078c0691cd6a64edadf1fd43940f30f50505a25 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 75                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4aea7cf559f67cedcad07e12ae6bc00f07e8cf65                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x9159d16045ccc62f097999959da7e4881d846375                         |                                                              |
| user              | VARCHAR   | 0x2a56adb5110c5bf431892a8366b3045803bbe050                         |                                                              |
| amount            | VARCHAR   | 500000000000                                                       |                                                              |
| balance           | VARCHAR   | 500000000000                                                       |                                                              |

## 8. Table: EtherDelta\_event\_Trade\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2016-09-15 19:03:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 2265556                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2744cd27ba12c46115d17e5836d4a253f816b8deed0c69abca00800c18f81ff9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4aea7cf559f67cedcad07e12ae6bc00f07e8cf65                         | Address of the contract that produced the log                |
| tokenGet          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| amountGet         | VARCHAR   | 500000000000000000                                                 |                                                              |
| tokenGive         | VARCHAR   | 0x01a7018e6d1fde8a68d12f59b6532fb523b6259d                         |                                                              |
| amountGive        | VARCHAR   | 595000000                                                          |                                                              |
| get               | VARCHAR   | 0xac75b73394c329376c214663d92156afa864a77f                         |                                                              |
| give              | VARCHAR   | 0x118c191228cc79cfc886086fc346d1d47e29c2b1                         |                                                              |

## 9. Table: EtherDelta\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2016-10-23 03:02:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 2490726                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0a5e6af262726cbdeaad16c1d053b29dc69e161c68b4a8cc2b426c1616b67dc7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4aea7cf559f67cedcad07e12ae6bc00f07e8cf65                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| user              | VARCHAR   | 0x57da9495bd34f38aaf3530dcaa9bf42136e2a352                         |                                                              |
| amount            | VARCHAR   | 56000000000000000000                                               |                                                              |
| balance           | VARCHAR   | 0                                                                  |                                                              |
