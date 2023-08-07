# common

## 1. Table: All\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-25 10:58:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 18414745                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x172383056250b511e70affcfa7c4a2213258f1bf578db6011987e5ed476c16a1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc94b947a1b2958c68150bcaa630f011765ac18e9                         | Address of the contract that produced the log                |
| dst               | VARCHAR   | 0x7690fc16c64b14db384f31f92358e897c8436edc                         |                                                              |
| wad               | VARCHAR   | 2999999000000000000000                                             |                                                              |

## 2. Table: All\_event\_TransferBatch\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-24 13:48:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7393168                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe31d6f4a00af91bdeb2484883819c7029984a930feb77eb43fdee66c5d53e533 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7793aff72be83b603ddcf42153be44f8fefba90f                         | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0xf460ee4ffe9e1eb3e489a83b5c4d0dcbb5336989                         |                                                              |
| from              | VARCHAR   | 0x29069824b4af0c77e1ac86632a88c942e4d12cd9                         |                                                              |
| to                | VARCHAR   | 0x2ad6d354e3ab2a196b64964a788534fdf7932e2b                         |                                                              |
| ids               | VARCHAR   | 1                                                                  |                                                              |
| values            | VARCHAR   | 1                                                                  |                                                              |

## 3. Table: All\_event\_TransferSingle\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-12 16:46:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 19248352                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc919f669c938839cc9ca4840beecf2a295e8b44714b4235a0e31806bf58fe0a9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x980a493a00149ba2cef62a51697bfe6ea1115e6a                         | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0x7d3a2ebb15c74d760e182ddebf05c00faba76872                         |                                                              |
| from              | VARCHAR   | 0x7d3a2ebb15c74d760e182ddebf05c00faba76872                         |                                                              |
| to                | VARCHAR   | 0x0cd61abdd7985ef9baa84a9a8b48e2f75212040c                         |                                                              |
| id                | VARCHAR   | 10                                                                 |                                                              |
| value             | VARCHAR   | 1                                                                  |                                                              |

## 4. Table: All\_event\_Withdrawal\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-22 23:50:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 19426234                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1c2e2f657e79d8488e7dbce142b495508d4813a5220e8af926476255a05a1c53 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 14                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9aeb36a13954c104d5a20a608278909c0880e5d5                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0x0849321b1fd97b12f8d9cb1d1dcb28ca2a5edf72                         |                                                              |
| wad               | VARCHAR   | 4100000000000000000                                                |                                                              |
