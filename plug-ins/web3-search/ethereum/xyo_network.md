# xyo\_network

## 1. Table: TokenERC20\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-09 12:43:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15108411                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x26a5f51afe8c54425bda37e4e9a5996998cf17836216f460f052eaef08a805ef | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 325                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x55296f69f40ea6d20e478533c15a6b08b654e758                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xa23c7a1ef71a717f6aaa3ad0fbf168d500da7c30                         |                                                              |
| value             | VARCHAR   | 157814                                                             |                                                              |

## 2. Table: TokenERC20\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-28 22:45:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17794609                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbe06d1adcfc970fad3edee84d89535a311684e02c573355fee263c7613dbbd87 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 126                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x55296f69f40ea6d20e478533c15a6b08b654e758                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x601779b5d82c901b99fd186a611ec47dc9ed681e                         |                                                              |
| to                | VARCHAR   | 0xa9d1e08c7793af67e9d92fe308d5697fb81d3e43                         |                                                              |
| value             | VARCHAR   | 41435945782140000000000                                            |                                                              |
