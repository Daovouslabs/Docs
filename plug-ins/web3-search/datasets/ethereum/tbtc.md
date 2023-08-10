# tbtc

## 1. Table: TBTCToken\_call\_burnFrom\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-05-18 02:28:09+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 10087307                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xb3907484f1399295108b9771a2fffcfa498e961d9661120c0aed1a86ab651968 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 156                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 2                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x1bbe271d15bb64df0bc6cd28df9ff322f2ebd847                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_account          | VARCHAR   | 0x0554a200988cf265b3aa35436a903d51fac47112                         |                                                                                                                        |
| \_amount           | VARCHAR   | 1000000000000000000                                                |                                                                                                                        |

## 2. Table: TBTCToken\_call\_burn\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| \_amount           | VARCHAR   |                                                                                                                        |             |

## 3. Table: TBTCToken\_call\_mint\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-05-17 06:59:16+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 10082049                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x39cc4340e675653f45659c13ebc5a2644fe02e327314f7d743773d3c1f59760b | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 25                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 6                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x1bbe271d15bb64df0bc6cd28df9ff322f2ebd847                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_account          | VARCHAR   | 0xddfc2e10702d8a781727a34d83b3bb3ca94a3e91                         |                                                                                                                        |
| \_amount           | VARCHAR   | 999500000000000                                                    |                                                                                                                        |

## 4. Table: TBTCToken\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-03 22:54:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10195662                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbbb252a5c40ef8869b41213daef26d5df3a09f1ba55738f953aa04787ba4a994 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1bbe271d15bb64df0bc6cd28df9ff322f2ebd847                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x3e90284b16e2b549e668d573de02b57c971de92b                         |                                                              |
| spender           | VARCHAR   | 0xcd1a594a65e9135ec40d2dc89b66a80557149aad                         |                                                              |
| value             | VARCHAR   | 166666666668                                                       |                                                              |

## 5. Table: TBTCToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-19 01:41:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10093498                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa80a9db56c5b87d891d68e782960ae684064512f60bb12f52b319682a282a025 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 83                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1bbe271d15bb64df0bc6cd28df9ff322f2ebd847                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x92fc8b525874bee082fedfc929e26add3f54003e                         |                                                              |
| to                | VARCHAR   | 0x26f9d36d03f0f7efcdd734566d5247f71935be4a                         |                                                              |
| value             | VARCHAR   | 9929359201104                                                      |                                                              |

## 6. Table: TBTC\_V1\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-28 23:55:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15234036                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2b0ad6bba886f3c34d4b8ee3fc12fd95718f13afcc88069ff1c53d04496d0acf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 14                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8daebade922df735c38c80c7ebd708af50815faa                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000e0ca771e21bd00057f54a68c30d400000000                         |                                                              |
| to                | VARCHAR   | 0x854056fd40c1b52037166285b2e54fee774d33f6                         |                                                              |
| value             | VARCHAR   | 4646890631239392                                                   |                                                              |

## 7. Table: TBTC\_V2\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-07 22:47:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15492991                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x806be9ee06cd79a984fc58f71d3ce16c191919fe900abfb0b0ddffd58f4cd781 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 111                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x18084fba666a33d37592fa2633fd49a74dd93a88                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x82e075129a96812a9430664fb0c6c4063cb84ccc                         |                                                              |
| to                | VARCHAR   | 0x6590dff6abed7c077839e8227a4f12ec90e6d85f                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |
