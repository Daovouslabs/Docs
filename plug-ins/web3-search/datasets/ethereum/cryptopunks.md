# cryptopunks

## 1. Table: CryptoPunksMarket\_event\_Assign\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2017-06-23 21:09:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 3919720                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x230be13b98acb15d9233f34af76016e7ae597b14aef86d684615ff35170448ad | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 26                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb47e3cd837ddf8e4c57f05d70ab865de6e193bbb                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0x5b098b00621eda6a96b7a476220661ad265f083f                         |                                                              |
| punkIndex         | VARCHAR   | 1416                                                               |                                                              |

## 2. Table: CryptoPunksMarket\_event\_PunkBidEntered\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-10 19:42:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9084827                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcc1a8b9491cb859fd417531fca3216ce6bc2e09322579aa7a6922b5c33002e28 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 17                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb47e3cd837ddf8e4c57f05d70ab865de6e193bbb                         | Address of the contract that produced the log                |
| punkIndex         | VARCHAR   | 7158                                                               |                                                              |
| value             | VARCHAR   | 500000000000000000                                                 |                                                              |
| fromAddress       | VARCHAR   | 0x8e662143178bb8c797620a3a61f34a71832475b0                         |                                                              |

## 3. Table: CryptoPunksMarket\_event\_PunkBidWithdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-19 16:36:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15174154                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3ebec82544b7dd25f22ccfb8aa1bf16606a5b7d3c2cea9a9c14b0f92e1298dfe | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb47e3cd837ddf8e4c57f05d70ab865de6e193bbb                         | Address of the contract that produced the log                |
| punkIndex         | VARCHAR   | 1531                                                               |                                                              |
| value             | VARCHAR   | 97100000000000000000                                               |                                                              |
| fromAddress       | VARCHAR   | 0x08b571c651b185cffae8d4c75d504232e9167edc                         |                                                              |

## 4. Table: CryptoPunksMarket\_event\_PunkBought\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-30 09:07:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10366186                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x24f370e284aaf2609ab49226338b109b538369c943a4daea7e0a3a438f82d7ca | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb47e3cd837ddf8e4c57f05d70ab865de6e193bbb                         | Address of the contract that produced the log                |
| punkIndex         | VARCHAR   | 2937                                                               |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |
| fromAddress       | VARCHAR   | 0xd387a6e4e84a6c86bd90c158c6028a58cc8ac459                         |                                                              |
| toAddress         | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 5. Table: CryptoPunksMarket\_event\_PunkNoLongerForSale\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2017-12-14 08:11:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4730131                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1eaeb81576b5af7f69a3550cf0b2b7d5e112b072a6d34ec4de05c101f2014344 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 8                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb47e3cd837ddf8e4c57f05d70ab865de6e193bbb                         | Address of the contract that produced the log                |
| punkIndex         | VARCHAR   | 3305                                                               |                                                              |

## 6. Table: CryptoPunksMarket\_event\_PunkOffered\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-24 09:26:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9155050                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5a7417de6bf7991eaed0fcd354d4e5dee4540bb6850af9e4e23a4f228911aad0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 93                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb47e3cd837ddf8e4c57f05d70ab865de6e193bbb                         | Address of the contract that produced the log                |
| punkIndex         | VARCHAR   | 3543                                                               |                                                              |
| minValue          | VARCHAR   | 1500000000000000000                                                |                                                              |
| toAddress         | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 7. Table: CryptoPunksMarket\_event\_PunkTransfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-03 05:22:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17832359                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x87dbc345a3ac2af69a63118e8a3b542e1193e01053916192d9564244cf7566d5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 88                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb47e3cd837ddf8e4c57f05d70ab865de6e193bbb                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x1919db36ca2fa2e15f9000fd9cdc2edcf863e685                         |                                                              |
| to                | VARCHAR   | 0x0232d1083e970f0c78f56202b9a666b526fa379f                         |                                                              |
| punkIndex         | VARCHAR   | 819                                                                |                                                              |

## 8. Table: CryptoPunksMarket\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-30 02:05:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10364367                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7775771a8d7bbbd808eb894c1f81341f15f33fccaed52d37cd2c435112b22909 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 47                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb47e3cd837ddf8e4c57f05d70ab865de6e193bbb                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x3a844195fefd2dd02ba61f5a2de45a95bba0cb5a                         |                                                              |
| to                | VARCHAR   | 0xc35a5fec6be6957899e15559be252db882220b37                         |                                                              |
| value             | VARCHAR   | 1                                                                  |                                                              |
