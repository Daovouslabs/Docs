# akropolis

## 1. Table: CompoundProtocol\_DAI\_event\_DefiOperatorAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-26 09:50:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10735354                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x00a56d6c6c9e4a52aa493d30b3267f7e7086c4ee4401004a0ad5e886671999ba | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 176                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x08ddb58d31c08242cd444bb5b43f7d2c6bca0396                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x4454fc25daf515d1237d0ea76ac3ea931118eef0                         |                                                              |

## 2. Table: CompoundProtocol\_DAI\_event\_DefiOperatorRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-12 08:59:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13009369                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf53dc74a681da6fce327ff06a23e90e47a2f8afb8fae9302b69ad96259df578c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 41                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x08ddb58d31c08242cd444bb5b43f7d2c6bca0396                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x4454fc25daf515d1237d0ea76ac3ea931118eef0                         |                                                              |

## 3. Table: CompoundProtocol\_DAI\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-12 08:58:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13009365                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1c92247cc44b9d20129af7b19195dbc91e32c1224a03af660c56a5d43142e21d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 82                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x08ddb58d31c08242cd444bb5b43f7d2c6bca0396                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x4454fc25daf515d1237d0ea76ac3ea931118eef0                         |                                                              |
| newOwner          | VARCHAR   | 0xc5af91f7d10dde118992ecf536ed227f276ec60d                         |                                                              |

## 4. Table: CompoundProtocol\_DAI\_event\_PoolAddressChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-12 09:48:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10644395                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x657cdcc3472b47548fad30b50ed3209dc51fc4feb763f9adb25bbf6d4f08e6f8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 185                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x08ddb58d31c08242cd444bb5b43f7d2c6bca0396                         | Address of the contract that produced the log                |
| newPool           | VARCHAR   | 0x4c39b37f5f20a0695bfdc59cf10bd85a6c4b7c30                         |                                                              |

## 5. Table: CompoundProtocol\_DAI\_event\_RewardTokenClaimed\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| token             | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 6. Table: CompoundProtocol\_USDC\_event\_DefiOperatorAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-26 09:50:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10735356                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe4879628ea44460e4778b2414a26cb054184888d37e7c63fb3d4e63b48cb9500 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 144                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9984d588ef2112894a0513663ba815310d383e3c                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x4454fc25daf515d1237d0ea76ac3ea931118eef0                         |                                                              |

## 7. Table: CompoundProtocol\_USDC\_event\_DefiOperatorRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-12 09:18:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13009457                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x090ab9fdc8a74604390ec62fa9f12dc9169a1b2724992104db5553afe243ce40 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 85                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9984d588ef2112894a0513663ba815310d383e3c                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x4454fc25daf515d1237d0ea76ac3ea931118eef0                         |                                                              |

## 8. Table: CompoundProtocol\_USDC\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-12 09:16:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13009453                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfae2ca8fbc47b5e3dc0227daa1361d3633d721a6067b250107741b707cca257b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9984d588ef2112894a0513663ba815310d383e3c                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x4454fc25daf515d1237d0ea76ac3ea931118eef0                         |                                                              |
| newOwner          | VARCHAR   | 0xc5af91f7d10dde118992ecf536ed227f276ec60d                         |                                                              |

## 9. Table: CompoundProtocol\_USDC\_event\_PoolAddressChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-12 09:50:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10644402                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf44ccb8aeb5d772a616f4860d661429412bbf3f497bc7cc73e671635dd270529 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 56                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9984d588ef2112894a0513663ba815310d383e3c                         | Address of the contract that produced the log                |
| newPool           | VARCHAR   | 0x4c39b37f5f20a0695bfdc59cf10bd85a6c4b7c30                         |                                                              |

## 10. Table: CompoundProtocol\_USDC\_event\_RewardTokenClaimed\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| token             | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 11. Table: CurveFiProtocol\_BUSD\_event\_CurveFiSetup\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-24 12:34:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10723130                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x38c032a7c68dc439f9c23b89346bddc54ea27a0c5cbf663d61935f7591d04a05 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 211                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeae1a8206f68a7ef629e85fc69e82cfd36e83ba4                         | Address of the contract that produced the log                |
| swap              | VARCHAR   | 0x79a8c46dea5ada233abaffd40f3a0a2b1e5a4f27                         |                                                              |
| deposit           | VARCHAR   | 0xb6c057591e073249f2d9d88ba59a46cfc9b59edb                         |                                                              |
| liquidityGauge    | VARCHAR   | 0x69fb7c45726cfe2badee8317005d3f94be838840                         |                                                              |

## 12. Table: CurveFiProtocol\_BUSD\_event\_DefiOperatorAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-12 08:49:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13009330                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa6bd55b03263e2d48ddaf362431cee7bc915ec03c330c0402680c751d4cdd647 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 58                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeae1a8206f68a7ef629e85fc69e82cfd36e83ba4                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xc5af91f7d10dde118992ecf536ed227f276ec60d                         |                                                              |

## 13. Table: CurveFiProtocol\_BUSD\_event\_DefiOperatorRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-26 10:18:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10735484                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x227b50248c2724907e0faf8783fd8076fd01c58e09310d2c29ec3d8066d1bd39 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 220                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeae1a8206f68a7ef629e85fc69e82cfd36e83ba4                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x043500bb7086c4b6457cd8362fd7306b1c90db00                         |                                                              |

## 14. Table: CurveFiProtocol\_BUSD\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-12 08:50:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13009335                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0c34b435e45430ff1d19e3a9786e248749a428aa400b2a9b45c96e37d5c95938 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 11                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeae1a8206f68a7ef629e85fc69e82cfd36e83ba4                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x4454fc25daf515d1237d0ea76ac3ea931118eef0                         |                                                              |
| newOwner          | VARCHAR   | 0xc5af91f7d10dde118992ecf536ed227f276ec60d                         |                                                              |

## 15. Table: CurveFiProtocol\_BUSD\_event\_PoolAddressChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-24 11:35:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10722831                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x713b457d9922fb9ad16901b7f62b5f3fbcf9e2eb77a71030be28cf740236fa09 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 141                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeae1a8206f68a7ef629e85fc69e82cfd36e83ba4                         | Address of the contract that produced the log                |
| newPool           | VARCHAR   | 0x4c39b37f5f20a0695bfdc59cf10bd85a6c4b7c30                         |                                                              |

## 16. Table: CurveFiProtocol\_BUSD\_event\_RewardTokenClaimed\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| token             | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 17. Table: CurveFiProtocol\_BUSD\_event\_TokenRegistered\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-24 12:34:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10723130                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x38c032a7c68dc439f9c23b89346bddc54ea27a0c5cbf663d61935f7591d04a05 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 204                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeae1a8206f68a7ef629e85fc69e82cfd36e83ba4                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         |                                                              |

## 18. Table: CurveFiProtocol\_BUSD\_event\_TokenUnregistered\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| token             | VARCHAR   |                                                              |             |

## 19. Table: CurveFiProtocol\_SUSD\_event\_CurveFiSetup\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-20 08:53:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10696096                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x69a71ca53416209665d1309a70c6c3d7513201bd226a6a2f1bceccc7862baade | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 179                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x91d7b9a8d2314110d4018c88dbfdcf5e2ba4772e                         | Address of the contract that produced the log                |
| swap              | VARCHAR   | 0xa5407eae9ba41422680e2e00537571bcc53efbfd                         |                                                              |
| deposit           | VARCHAR   | 0xfcba3e75865d2d561be8d220616520c171f12851                         |                                                              |
| liquidityGauge    | VARCHAR   | 0xa90996896660decc6e997655e065b23788857849                         |                                                              |

## 20. Table: CurveFiProtocol\_SUSD\_event\_DefiOperatorAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-20 11:47:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10696862                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf28d4830b58d232b016a1a3bb438e962c4c5d00fca2ef07c2a4eb7deccf892d5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 50                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x91d7b9a8d2314110d4018c88dbfdcf5e2ba4772e                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x73fc3038b4cd8ffd07482b92a52ea806505e5748                         |                                                              |

## 21. Table: CurveFiProtocol\_SUSD\_event\_DefiOperatorRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-12 08:42:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13009304                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf54fd73749c3a8daec21db3d4212ef4e309eae4e628dc7848e903fb61aa8192b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 163                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x91d7b9a8d2314110d4018c88dbfdcf5e2ba4772e                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x4454fc25daf515d1237d0ea76ac3ea931118eef0                         |                                                              |

## 22. Table: CurveFiProtocol\_SUSD\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-12 08:42:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13009304                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1895d1b0cd1391721bde07c8ddf9add44e4c4f6a3c7961adaede4f2b681f18da | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 158                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x91d7b9a8d2314110d4018c88dbfdcf5e2ba4772e                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x4454fc25daf515d1237d0ea76ac3ea931118eef0                         |                                                              |
| newOwner          | VARCHAR   | 0xc5af91f7d10dde118992ecf536ed227f276ec60d                         |                                                              |

## 23. Table: CurveFiProtocol\_SUSD\_event\_PoolAddressChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-20 08:11:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10695910                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2073fc78973a2a317d74863a0bf2a529bc6ae52f371d7c97f6b00a1a51f9e74b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 38                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x91d7b9a8d2314110d4018c88dbfdcf5e2ba4772e                         | Address of the contract that produced the log                |
| newPool           | VARCHAR   | 0x4c39b37f5f20a0695bfdc59cf10bd85a6c4b7c30                         |                                                              |

## 24. Table: CurveFiProtocol\_SUSD\_event\_RewardTokenClaimed\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| token             | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 25. Table: CurveFiProtocol\_SUSD\_event\_TokenRegistered\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-20 08:53:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10696096                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x69a71ca53416209665d1309a70c6c3d7513201bd226a6a2f1bceccc7862baade | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 177                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x91d7b9a8d2314110d4018c88dbfdcf5e2ba4772e                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x57ab1ec28d129707052df4df418d58a2d46d5f51                         |                                                              |

## 26. Table: CurveFiProtocol\_SUSD\_event\_TokenUnregistered\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| token             | VARCHAR   |                                                              |             |

## 27. Table: CurveFiProtocol\_Y\_event\_CurveFiSetup\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-21 11:00:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10703171                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb91ee7373a863621c6273bfea8d45ae665ed770cd9130b240148c63d15bfd955 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 159                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7967ada2a32a633d5c055e2e075a83023b632b4e                         | Address of the contract that produced the log                |
| swap              | VARCHAR   | 0x45f783cce6b7ff23b2ab2d70e416cdb7d6055f51                         |                                                              |
| deposit           | VARCHAR   | 0xbbc81d23ea2c3ec7e56d39296f0cbb648873a5d3                         |                                                              |
| liquidityGauge    | VARCHAR   | 0xfa712ee4788c042e2b7bb55e6cb8ec569c4530c1                         |                                                              |

## 28. Table: CurveFiProtocol\_Y\_event\_DefiOperatorAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-12 08:21:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13009227                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x902e652ff65b889b3d1cd5a6d0257f74fe77fe0ece91cb1993cc4973b7ea3780 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 215                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7967ada2a32a633d5c055e2e075a83023b632b4e                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xc5af91f7d10dde118992ecf536ed227f276ec60d                         |                                                              |

## 29. Table: CurveFiProtocol\_Y\_event\_DefiOperatorRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-26 10:17:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10735479                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc02825eaf766582491bf68f4eb39de58d67fa6cba4801fca9a86c88ac2e3c204 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 60                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7967ada2a32a633d5c055e2e075a83023b632b4e                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x043500bb7086c4b6457cd8362fd7306b1c90db00                         |                                                              |

## 30. Table: CurveFiProtocol\_Y\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-21 09:36:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10702808                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd2dab5ffe5e874b5b50bf3cf428227d0b214282f3ee61a84bafac30ec447d8ae | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 129                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7967ada2a32a633d5c055e2e075a83023b632b4e                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x043500bb7086c4b6457cd8362fd7306b1c90db00                         |                                                              |

## 31. Table: CurveFiProtocol\_Y\_event\_PoolAddressChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-21 09:36:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10702808                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd2dab5ffe5e874b5b50bf3cf428227d0b214282f3ee61a84bafac30ec447d8ae | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 130                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7967ada2a32a633d5c055e2e075a83023b632b4e                         | Address of the contract that produced the log                |
| newPool           | VARCHAR   | 0x4c39b37f5f20a0695bfdc59cf10bd85a6c4b7c30                         |                                                              |

## 32. Table: CurveFiProtocol\_Y\_event\_RewardTokenClaimed\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| token             | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 33. Table: CurveFiProtocol\_Y\_event\_TokenRegistered\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-21 11:00:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10703171                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb91ee7373a863621c6273bfea8d45ae665ed770cd9130b240148c63d15bfd955 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 158                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7967ada2a32a633d5c055e2e075a83023b632b4e                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x0000000000085d4780b73119b644ae5ecd22b376                         |                                                              |

## 34. Table: CurveFiProtocol\_Y\_event\_TokenUnregistered\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| token             | VARCHAR   |                                                              |             |

## 35. Table: PoolToken\_Compound\_DAI\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-05 19:30:57+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10997644                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd1b66a9b8819ea4c52b803e3ac0c45e266699778ed051dfa66688b78fd04534d             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 62                                                                             | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9fca734bb62c20d2cf654705b8fbf4f49ff5cc31                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x7e2b6a9227554f4e217c591a34df023124b4a83c                                     |                                                              |
| spender           | VARCHAR   | 0x7a250d5630b4cf539739df2c5dacb4c659f2488d                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 36. Table: PoolToken\_Compound\_DAI\_event\_DistributionAccumulatorIncreased\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-12 04:59:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10845078                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb7bad8ef8a65d57de2d2b3c919bc159c1b08865dcd89ad163d642a4eb5ff826a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 105                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9fca734bb62c20d2cf654705b8fbf4f49ff5cc31                         | Address of the contract that produced the log                |
| amount            | VARCHAR   | 102860500                                                          |                                                              |

## 37. Table: PoolToken\_Compound\_DAI\_event\_DistributionCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-18 12:10:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10886074                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb96218a5323a6461e0a5de438435a4992f6a7b7ec4b0f797fa90ede5802b9d46 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 77                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9fca734bb62c20d2cf654705b8fbf4f49ff5cc31                         | Address of the contract that produced the log                |
| amount            | VARCHAR   | 19940236203951079145                                               |                                                              |
| totalSupply       | VARCHAR   | 291140218931739081742049                                           |                                                              |

## 38. Table: PoolToken\_Compound\_DAI\_event\_DistributionsClaimed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-13 02:20:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10850870                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5bec241393bccba33332baa211eb9c33f8d541bbce991283f0ac52b7cb9c599a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 179                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9fca734bb62c20d2cf654705b8fbf4f49ff5cc31                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x668d775dc3ee120510e76fe0476bb943e8b756de                         |                                                              |
| amount            | VARCHAR   | 10061848077851053117                                               |                                                              |
| fromDistribution  | VARCHAR   | 13                                                                 |                                                              |
| toDistribution    | VARCHAR   | 23                                                                 |                                                              |

## 39. Table: PoolToken\_Compound\_DAI\_event\_MinterAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-26 09:56:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10735381                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x507bcf0b1069219e1bbaf53639a7fb35fa2444b771ea5d147c8a6f30948a5209 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 114                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9fca734bb62c20d2cf654705b8fbf4f49ff5cc31                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x4454fc25daf515d1237d0ea76ac3ea931118eef0                         |                                                              |

## 40. Table: PoolToken\_Compound\_DAI\_event\_MinterRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-12 09:14:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13009440                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb1ab8641908efe4fa10e3f758fd9552599e738d82d59dd9c4ea5b7203370ab6e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 90                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9fca734bb62c20d2cf654705b8fbf4f49ff5cc31                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x4454fc25daf515d1237d0ea76ac3ea931118eef0                         |                                                              |

## 41. Table: PoolToken\_Compound\_DAI\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-12 09:13:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13009438                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0370dd5c55e41c321a4069786c7a955e1d354d4ee88c755da69f8d1d269ef25a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 54                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9fca734bb62c20d2cf654705b8fbf4f49ff5cc31                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x4454fc25daf515d1237d0ea76ac3ea931118eef0                         |                                                              |
| newOwner          | VARCHAR   | 0xc5af91f7d10dde118992ecf536ed227f276ec60d                         |                                                              |

## 42. Table: PoolToken\_Compound\_DAI\_event\_PoolAddressChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-12 09:49:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10644398                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe4c9aebfc8c98335fabb4b0b3235ab5843ced8c4413d1c28b891377ab3fa01e3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 40                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9fca734bb62c20d2cf654705b8fbf4f49ff5cc31                         | Address of the contract that produced the log                |
| newPool           | VARCHAR   | 0x4c39b37f5f20a0695bfdc59cf10bd85a6c4b7c30                         |                                                              |

## 43. Table: PoolToken\_Compound\_DAI\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-24 02:30:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10922581                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbe737adb980e62fa9c2a139eb5e97d792ec536abee2ebf8d7dd3bedd0860a449 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 101                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9fca734bb62c20d2cf654705b8fbf4f49ff5cc31                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x9fca734bb62c20d2cf654705b8fbf4f49ff5cc31                         |                                                              |
| value             | VARCHAR   | 16863894213818370396                                               |                                                              |

## 44. Table: PoolToken\_Compound\_USDC\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-05 19:31:50+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10997649                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8f7902e3759d864a7a5d0e1e7b38ccf16d5985813a233ae79d0ebf8761d00efd             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 260                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5ad76e93a3a852c9af760da3fdb7983c265d8997                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x7e2b6a9227554f4e217c591a34df023124b4a83c                                     |                                                              |
| spender           | VARCHAR   | 0x7a250d5630b4cf539739df2c5dacb4c659f2488d                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 45. Table: PoolToken\_Compound\_USDC\_event\_DistributionAccumulatorIncreased\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-04 07:54:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10793658                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x686754749ec6924707dc040b6680dafbaaf9efc5314af2516ed0e31260d99cb5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 260                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5ad76e93a3a852c9af760da3fdb7983c265d8997                         | Address of the contract that produced the log                |
| amount            | VARCHAR   | 49808484000000000000                                               |                                                              |

## 46. Table: PoolToken\_Compound\_USDC\_event\_DistributionCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-14 05:27:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10858259                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf188d82b2ab5ce41bbcf918a21f5024182a1d040dbd285f728a5c5489208c60a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5ad76e93a3a852c9af760da3fdb7983c265d8997                         | Address of the contract that produced the log                |
| amount            | VARCHAR   | 51453696000000000000                                               |                                                              |
| totalSupply       | VARCHAR   | 523048493479000000000000                                           |                                                              |

## 47. Table: PoolToken\_Compound\_USDC\_event\_DistributionsClaimed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-04 16:23:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10990415                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9bb3393a727f9838ade310f8c1325bb135a99295b2986ada9564af6ebf55e8ef | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 110                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5ad76e93a3a852c9af760da3fdb7983c265d8997                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xcfc50541c3deaf725ce738ef87ace2ad778ba0c5                         |                                                              |
| amount            | VARCHAR   | 5544323386423824807                                                |                                                              |
| fromDistribution  | VARCHAR   | 39                                                                 |                                                              |
| toDistribution    | VARCHAR   | 44                                                                 |                                                              |

## 48. Table: PoolToken\_Compound\_USDC\_event\_MinterAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-26 09:59:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10735388                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x25402d8e6795108a192ca213c5b1d9a4185e6e2048f6c3cab16898879148c973 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 314                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5ad76e93a3a852c9af760da3fdb7983c265d8997                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x4454fc25daf515d1237d0ea76ac3ea931118eef0                         |                                                              |

## 49. Table: PoolToken\_Compound\_USDC\_event\_MinterRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-12 09:21:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13009472                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa1fc5fe0d3c70c07c3ee00d5c7308cd9786b6f2e2ad70d1d0053c72ab005dad4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 63                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5ad76e93a3a852c9af760da3fdb7983c265d8997                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x4454fc25daf515d1237d0ea76ac3ea931118eef0                         |                                                              |

## 50. Table: PoolToken\_Compound\_USDC\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-26 11:10:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10735712                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2f9de6b418764258f43bd7f4adc16453d7d6b082022d1e209972732bbcd3c718 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 184                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5ad76e93a3a852c9af760da3fdb7983c265d8997                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x043500bb7086c4b6457cd8362fd7306b1c90db00                         |                                                              |
| newOwner          | VARCHAR   | 0x4454fc25daf515d1237d0ea76ac3ea931118eef0                         |                                                              |

## 51. Table: PoolToken\_Compound\_USDC\_event\_PoolAddressChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-12 09:51:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10644408                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x75d6e5e9350e3bebda5747ad93b67fca749149af2df9eaba03083c847134e092 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 34                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5ad76e93a3a852c9af760da3fdb7983c265d8997                         | Address of the contract that produced the log                |
| newPool           | VARCHAR   | 0x4c39b37f5f20a0695bfdc59cf10bd85a6c4b7c30                         |                                                              |

## 52. Table: PoolToken\_Compound\_USDC\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-04 07:54:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10793658                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x686754749ec6924707dc040b6680dafbaaf9efc5314af2516ed0e31260d99cb5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 261                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5ad76e93a3a852c9af760da3fdb7983c265d8997                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x5ad76e93a3a852c9af760da3fdb7983c265d8997                         |                                                              |
| value             | VARCHAR   | 67447607000000000000                                               |                                                              |

## 53. Table: PoolToken\_CurveFi\_BUSD\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-20 11:29:05+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10898932                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x274cbefc5fe12d9e3a9525e744f7fc486d137a50c161f862552ebcd6f0269dd7             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 118                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8367af78444c5b57bc1cf38ded331d03558e67bb                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xf53feaeb035361c046e5669745695e450ebb4028                                     |                                                              |
| spender           | VARCHAR   | 0x7a250d5630b4cf539739df2c5dacb4c659f2488d                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 54. Table: PoolToken\_CurveFi\_BUSD\_event\_DistributionAccumulatorIncreased\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-09 14:59:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11223974                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1f483b0ad45e020f9dc182e5d4b6f9980845501b710fb3de7fe9adafdce556d4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 176                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8367af78444c5b57bc1cf38ded331d03558e67bb                         | Address of the contract that produced the log                |
| amount            | VARCHAR   | 732299518371871413                                                 |                                                              |

## 55. Table: PoolToken\_CurveFi\_BUSD\_event\_DistributionCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-26 21:06:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11935196                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd5820971521080656d949320bed134a03083a3d53c52d8e779dcf871bd500780 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 121                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8367af78444c5b57bc1cf38ded331d03558e67bb                         | Address of the contract that produced the log                |
| amount            | VARCHAR   | 189101281346189357627                                              |                                                              |
| totalSupply       | VARCHAR   | 10753513885431190915737                                            |                                                              |

## 56. Table: PoolToken\_CurveFi\_BUSD\_event\_DistributionsClaimed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-26 21:06:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11935196                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd5820971521080656d949320bed134a03083a3d53c52d8e779dcf871bd500780 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 138                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8367af78444c5b57bc1cf38ded331d03558e67bb                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x4202e733eb2d17a92401fd75148d04ac1b28f1c3                         |                                                              |
| amount            | VARCHAR   | 409826646944999012202                                              |                                                              |
| fromDistribution  | VARCHAR   | 5                                                                  |                                                              |
| toDistribution    | VARCHAR   | 52                                                                 |                                                              |

## 57. Table: PoolToken\_CurveFi\_BUSD\_event\_MinterAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-24 11:45:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10722881                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5496e60c5bab0cf06066876bc6adee9b56225d423619aea9c5daa7881a1223ff | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 69                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8367af78444c5b57bc1cf38ded331d03558e67bb                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x043500bb7086c4b6457cd8362fd7306b1c90db00                         |                                                              |

## 58. Table: PoolToken\_CurveFi\_BUSD\_event\_MinterRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-26 10:59:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10735648                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb9a95fc1db26e24217fb692d401bb3bfef85d45df630aa38166e054c26fd2305 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 186                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8367af78444c5b57bc1cf38ded331d03558e67bb                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x043500bb7086c4b6457cd8362fd7306b1c90db00                         |                                                              |

## 59. Table: PoolToken\_CurveFi\_BUSD\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-12 08:55:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13009355                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x310a7c35f7142129f387482afbb206a72949f95569fc8419e8956d3447a5bc1e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 29                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8367af78444c5b57bc1cf38ded331d03558e67bb                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x4454fc25daf515d1237d0ea76ac3ea931118eef0                         |                                                              |
| newOwner          | VARCHAR   | 0xc5af91f7d10dde118992ecf536ed227f276ec60d                         |                                                              |

## 60. Table: PoolToken\_CurveFi\_BUSD\_event\_PoolAddressChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-24 11:45:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10722881                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5496e60c5bab0cf06066876bc6adee9b56225d423619aea9c5daa7881a1223ff | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 68                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8367af78444c5b57bc1cf38ded331d03558e67bb                         | Address of the contract that produced the log                |
| newPool           | VARCHAR   | 0x4c39b37f5f20a0695bfdc59cf10bd85a6c4b7c30                         |                                                              |

## 61. Table: PoolToken\_CurveFi\_BUSD\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-15 03:19:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10864142                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3a2ede854340779d7dec362b3b9b6a5330f49d154980ec9bb180dcaf9d72a6f2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 27                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8367af78444c5b57bc1cf38ded331d03558e67bb                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x94141ffd2af58dd11f5c390815bbc390e30282fb                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 5333157373000000000000                                             |                                                              |

## 62. Table: PoolToken\_CurveFi\_SUSD\_event\_Approval\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| owner             | VARCHAR   |                                                              |             |
| spender           | VARCHAR   |                                                              |             |
| value             | VARCHAR   |                                                              |             |

## 63. Table: PoolToken\_CurveFi\_SUSD\_event\_DistributionAccumulatorIncreased\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-03 21:18:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11186578                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3419b611141e45d29f0f861f979e4ed67d1ff5184d04996c95795110b076d9f7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 159                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x520d25b08080296db66fd9f268ae279b66a8effb                         | Address of the contract that produced the log                |
| amount            | VARCHAR   | 308219353428459437419                                              |                                                              |

## 64. Table: PoolToken\_CurveFi\_SUSD\_event\_DistributionCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-20 00:37:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11089785                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7e5def1abe3a175ecd5510b202f070233408a4b43349f2d061e90e6eebcefb05 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 204                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x520d25b08080296db66fd9f268ae279b66a8effb                         | Address of the contract that produced the log                |
| amount            | VARCHAR   | 1875922927829612474                                                |                                                              |
| totalSupply       | VARCHAR   | 1572744753363285305928313                                          |                                                              |

## 65. Table: PoolToken\_CurveFi\_SUSD\_event\_DistributionsClaimed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-14 01:40:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10857216                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xefde255f384bb5191591ed5e141ac86161a58bda2a0c4a6a8939766e827165a5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 166                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x520d25b08080296db66fd9f268ae279b66a8effb                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x1e1a575fe7bdf0d6265e4127787d3ac93d539239                         |                                                              |
| amount            | VARCHAR   | 28987532553973179184                                               |                                                              |
| fromDistribution  | VARCHAR   | 2                                                                  |                                                              |
| toDistribution    | VARCHAR   | 16                                                                 |                                                              |

## 66. Table: PoolToken\_CurveFi\_SUSD\_event\_MinterAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-20 11:00:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10696647                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x93f6de076c8066ba0b1fc231864ec78956db110497b891587a736dc92fc5f892 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 107                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x520d25b08080296db66fd9f268ae279b66a8effb                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x73fc3038b4cd8ffd07482b92a52ea806505e5748                         |                                                              |

## 67. Table: PoolToken\_CurveFi\_SUSD\_event\_MinterRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-12 08:48:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13009328                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5bfbff7a3cd1d30a55a062d53f2f33be87dd6a49aa724a60dbc4db9c29ef53c3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 142                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x520d25b08080296db66fd9f268ae279b66a8effb                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x4454fc25daf515d1237d0ea76ac3ea931118eef0                         |                                                              |

## 68. Table: PoolToken\_CurveFi\_SUSD\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-12 08:47:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13009325                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x512edba2eab0369424928de815a19ef092f9ba841f4070557580366ecbc0243c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 20                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x520d25b08080296db66fd9f268ae279b66a8effb                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x4454fc25daf515d1237d0ea76ac3ea931118eef0                         |                                                              |
| newOwner          | VARCHAR   | 0xc5af91f7d10dde118992ecf536ed227f276ec60d                         |                                                              |

## 69. Table: PoolToken\_CurveFi\_SUSD\_event\_PoolAddressChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-20 10:38:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10696537                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc35014dd95f0e2a03cc7e0b9663bdcb1cdadd2e3eb5f370e03c5c523ebd9d43d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 165                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x520d25b08080296db66fd9f268ae279b66a8effb                         | Address of the contract that produced the log                |
| newPool           | VARCHAR   | 0x4c39b37f5f20a0695bfdc59cf10bd85a6c4b7c30                         |                                                              |

## 70. Table: PoolToken\_CurveFi\_SUSD\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-18 09:55:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11079196                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0b0bb6d5d6f1f25fbe3ecc4f50a5f45bd831bbf36bfa3d86c1be481cf0e98430 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 78                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x520d25b08080296db66fd9f268ae279b66a8effb                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xd9233c98d84e50f07b122ee0de0a6a50f49127e0                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 502997516000000000000                                              |                                                              |

## 71. Table: PoolToken\_CurveFi\_Y\_event\_Approval\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| owner             | VARCHAR   |                                                              |             |
| spender           | VARCHAR   |                                                              |             |
| value             | VARCHAR   |                                                              |             |

## 72. Table: PoolToken\_CurveFi\_Y\_event\_DistributionAccumulatorIncreased\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-12 12:27:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10847123                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa58e49ec83a21c57ecfcae940d79c41baa80434aaf3942775f07a8f553864095 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 140                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2afa3c8bf33e65d5036cd0f1c3599716894b3077                         | Address of the contract that produced the log                |
| amount            | VARCHAR   | 3142773418578974703                                                |                                                              |

## 73. Table: PoolToken\_CurveFi\_Y\_event\_DistributionCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-03 02:55:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11181641                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x63ac5ff530e4a9dceec09afb8afdf6ab42ea138438b15b170704fed4006c4f31 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 177                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2afa3c8bf33e65d5036cd0f1c3599716894b3077                         | Address of the contract that produced the log                |
| amount            | VARCHAR   | 56080441865417529520                                               |                                                              |
| totalSupply       | VARCHAR   | 704120790896006962569983                                           |                                                              |

## 74. Table: PoolToken\_CurveFi\_Y\_event\_DistributionsClaimed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-16 16:18:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10874180                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb0b270ae5696505276fd047e3e2da2c32fd04a6c22567ea6d2551f2ae70f62e6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 129                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2afa3c8bf33e65d5036cd0f1c3599716894b3077                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x71e1d6e6f8da5295d6ff161bb22e9183120c9a15                         |                                                              |
| amount            | VARCHAR   | 434225814920376305076                                              |                                                              |
| fromDistribution  | VARCHAR   | 5                                                                  |                                                              |
| toDistribution    | VARCHAR   | 19                                                                 |                                                              |

## 75. Table: PoolToken\_CurveFi\_Y\_event\_MinterAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-26 09:59:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10735391                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x42cb21592e54ec2d2fde927e2595ab0eef77f1b2ac843dabad09ed46b32e9576 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 99                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2afa3c8bf33e65d5036cd0f1c3599716894b3077                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x4454fc25daf515d1237d0ea76ac3ea931118eef0                         |                                                              |

## 76. Table: PoolToken\_CurveFi\_Y\_event\_MinterRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-12 08:28:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13009254                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6d8e2454382cc3229464c18984fe89dc76977cab087f475e8184fc916bb5cde6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 116                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2afa3c8bf33e65d5036cd0f1c3599716894b3077                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x4454fc25daf515d1237d0ea76ac3ea931118eef0                         |                                                              |

## 77. Table: PoolToken\_CurveFi\_Y\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-21 12:05:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10703458                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8a0e22251fc818587e9a407fed7270020feca94e09d30618acb50cab98e49817 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 260                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2afa3c8bf33e65d5036cd0f1c3599716894b3077                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x043500bb7086c4b6457cd8362fd7306b1c90db00                         |                                                              |

## 78. Table: PoolToken\_CurveFi\_Y\_event\_PoolAddressChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-21 12:05:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10703458                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8a0e22251fc818587e9a407fed7270020feca94e09d30618acb50cab98e49817 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 261                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2afa3c8bf33e65d5036cd0f1c3599716894b3077                         | Address of the contract that produced the log                |
| newPool           | VARCHAR   | 0x4c39b37f5f20a0695bfdc59cf10bd85a6c4b7c30                         |                                                              |

## 79. Table: PoolToken\_CurveFi\_Y\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-09 15:22:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11224073                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd32c4365c5fd773bc6db00b2b59613807381aa5c879415f07cd3744df53b429b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 62                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2afa3c8bf33e65d5036cd0f1c3599716894b3077                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x52cc6357cebe1b5114aea23e62cd773d6004b71d                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 1031361625000000000000                                             |                                                              |

## 80. Table: SavingsModule\_event\_CapperAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-26 09:48:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10735348                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x254cb56684f45682c04638bfafb9c9c62faafe80679a3393bffab13e73085c58 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 187                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73fc3038b4cd8ffd07482b92a52ea806505e5748                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x4454fc25daf515d1237d0ea76ac3ea931118eef0                         |                                                              |

## 81. Table: SavingsModule\_event\_CapperRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-12 19:38:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10647081                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0ce89e0440da4f5a78ee1b813d5e3766273b59b962b094ea4b5c470ab40d3a95 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 197                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73fc3038b4cd8ffd07482b92a52ea806505e5748                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x35f9573d1998725e871736f1d08274d3ea55cdd9                         |                                                              |

## 82. Table: SavingsModule\_event\_DefaultUserCapChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-09 22:05:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10830153                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x18caa9ec42e0774b3cf7902015fb94313a85f6493007c9f2ad701d5a0282520c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 245                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73fc3038b4cd8ffd07482b92a52ea806505e5748                         | Address of the contract that produced the log                |
| protocol          | VARCHAR   | 0x91d7b9a8d2314110d4018c88dbfdcf5e2ba4772e                         |                                                              |
| newCap            | VARCHAR   | 5000000000000000000000000                                          |                                                              |

## 83. Table: SavingsModule\_event\_DepositToken\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-22 08:49:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10911362                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd4918824078ae469b350a4bbda748264d2973907849932ccbc879b7b56d6858a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 223                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73fc3038b4cd8ffd07482b92a52ea806505e5748                         | Address of the contract that produced the log                |
| protocol          | VARCHAR   | 0x91d7b9a8d2314110d4018c88dbfdcf5e2ba4772e                         |                                                              |
| token             | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| dnAmount          | VARCHAR   | 500000000                                                          |                                                              |

## 84. Table: SavingsModule\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-18 09:21:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11079051                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7a0df756d5a008f8422a9901742bac5827602bdeb615bf2786d81fdf08a8ac4c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 288                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73fc3038b4cd8ffd07482b92a52ea806505e5748                         | Address of the contract that produced the log                |
| protocol          | VARCHAR   | 0x08ddb58d31c08242cd444bb5b43f7d2c6bca0396                         |                                                              |
| user              | VARCHAR   | 0x7b7d9ce0df9cbde17cd6eb6d19e4c7941bd99978                         |                                                              |
| nAmount           | VARCHAR   | 100000000000000000000                                              |                                                              |
| nFee              | VARCHAR   | 24274295                                                           |                                                              |

## 85. Table: SavingsModule\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-01 12:37:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10775310                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xac354c817833181f94f36239e929f8ca68f7ea9f884870cf3d7ca9dd931c6ab6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 22                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73fc3038b4cd8ffd07482b92a52ea806505e5748                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x4454fc25daf515d1237d0ea76ac3ea931118eef0                         |                                                              |
| newOwner          | VARCHAR   | 0x509e16558f1fdc4733efa73846da891a29797e43                         |                                                              |

## 86. Table: SavingsModule\_event\_PoolAddressChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-12 09:46:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10644381                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1c2cf30aba46c2706b69fa88337525de9a79c422060b4288c0a5d99060d06f88 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 102                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73fc3038b4cd8ffd07482b92a52ea806505e5748                         | Address of the contract that produced the log                |
| newPool           | VARCHAR   | 0x4c39b37f5f20a0695bfdc59cf10bd85a6c4b7c30                         |                                                              |

## 87. Table: SavingsModule\_event\_ProtocolCapChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-24 13:07:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10723282                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x39c2bc911e5cc0fcfd59a6bc6d12dec6d149ea1e9822c8f95ecf9deab31a341c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 205                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73fc3038b4cd8ffd07482b92a52ea806505e5748                         | Address of the contract that produced the log                |
| protocol          | VARCHAR   | 0xeae1a8206f68a7ef629e85fc69e82cfd36e83ba4                         |                                                              |
| newCap            | VARCHAR   | 1000000000000000000000                                             |                                                              |

## 88. Table: SavingsModule\_event\_ProtocolCapEnabledChange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-24 11:55:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10722928                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcdc5f2b96b8278f3394a7d4d81eee003d4c54e73e078f79c675ddc3d2f7dc6bb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 294                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73fc3038b4cd8ffd07482b92a52ea806505e5748                         | Address of the contract that produced the log                |
| enabled           | VARCHAR   | true                                                               |                                                              |

## 89. Table: SavingsModule\_event\_ProtocolRegistered\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-12 10:21:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10644554                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa6a8a0d22817ab89c763a7d63a27cd0a3b2b5c3e4197502e61eec0718c1f0465 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 24                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73fc3038b4cd8ffd07482b92a52ea806505e5748                         | Address of the contract that produced the log                |
| protocol          | VARCHAR   | 0x9984d588ef2112894a0513663ba815310d383e3c                         |                                                              |
| poolToken         | VARCHAR   | 0x5ad76e93a3a852c9af760da3fdb7983c265d8997                         |                                                              |

## 90. Table: SavingsModule\_event\_RewardDistribution\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-27 18:53:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10744360                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf8a89d295cd375805faa65a9ae9cd01a53368fb18e1f686f74ee8f6fd43a64c2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 73                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73fc3038b4cd8ffd07482b92a52ea806505e5748                         | Address of the contract that produced the log                |
| poolToken         | VARCHAR   | 0x2afa3c8bf33e65d5036cd0f1c3599716894b3077                         |                                                              |
| rewardToken       | VARCHAR   | 0xd533a949740bb3306d119cc777fa900ba034cd52                         |                                                              |
| amount            | VARCHAR   | 27931184016192711822                                               |                                                              |
| totalShares       | VARCHAR   | 50008227796997972397780                                            |                                                              |

## 91. Table: SavingsModule\_event\_RewardWithdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-26 12:46:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10736173                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbd63336acf2c0b09a23659f12b0a5a52c52aeabfc4f4d3bd0e4a82d63df74f5e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 112                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73fc3038b4cd8ffd07482b92a52ea806505e5748                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x5780837c1d9ac3cd9b72203c8a0cfac73a9fc0b8                         |                                                              |
| rewardToken       | VARCHAR   | 0xc00e94cb662c3520282e6f5717214004a7f26888                         |                                                              |
| amount            | VARCHAR   | 15623271047047232                                                  |                                                              |

## 92. Table: SavingsModule\_event\_UserCapChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-13 11:22:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10651311                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2f1c01a3a1ab31a8734f10a9765a71000ee95f1a5abdd20d23d51646783a023b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 258                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73fc3038b4cd8ffd07482b92a52ea806505e5748                         | Address of the contract that produced the log                |
| protocol          | VARCHAR   | 0x9984d588ef2112894a0513663ba815310d383e3c                         |                                                              |
| user              | VARCHAR   | 0x93b00d86bf12edb5fa833715fce8a4972b007ef0                         |                                                              |
| newCap            | VARCHAR   | 0                                                                  |                                                              |

## 93. Table: SavingsModule\_event\_UserCapEnabledChange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-12 10:54:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10644713                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xabc501e9b959f73b4a3d6546c19f803677f06a41fe7bcea4de4f95dea116998b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 82                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73fc3038b4cd8ffd07482b92a52ea806505e5748                         | Address of the contract that produced the log                |
| enabled           | VARCHAR   | true                                                               |                                                              |

## 94. Table: SavingsModule\_event\_WithdrawToken\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-23 20:20:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11114682                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x840ea8a2bc177b906c525c7fcae2bdc6302b0d6ced56521ef541850442e69482 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 112                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73fc3038b4cd8ffd07482b92a52ea806505e5748                         | Address of the contract that produced the log                |
| protocol          | VARCHAR   | 0x91d7b9a8d2314110d4018c88dbfdcf5e2ba4772e                         |                                                              |
| token             | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         |                                                              |
| dnAmount          | VARCHAR   | 232756618876789573866                                              |                                                              |

## 95. Table: SavingsModule\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-14 19:11:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11452937                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5570ebde058a74d7eed25398647b97f74044c3de884dba74f05faff3251ddc27 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 75                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73fc3038b4cd8ffd07482b92a52ea806505e5748                         | Address of the contract that produced the log                |
| protocol          | VARCHAR   | 0x051e3a47724740d47042edc71c0ae81a35fdede9                         |                                                              |
| user              | VARCHAR   | 0x8b9fa7432c73c7135e3ec3014cc0b39720634fc2                         |                                                              |
| nAmount           | VARCHAR   | 10061461643076670436357                                            |                                                              |
| nFee              | VARCHAR   | 0                                                                  |                                                              |

## 96. Table: SavingsModule\_event\_YieldDistribution\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-05 23:09:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10998623                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x08a9eb72dbf63dc6645bbc8061f85cceb1f0037baa92a2a3fc45b696a7106d03 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 91                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73fc3038b4cd8ffd07482b92a52ea806505e5748                         | Address of the contract that produced the log                |
| poolToken         | VARCHAR   | 0x2afa3c8bf33e65d5036cd0f1c3599716894b3077                         |                                                              |
| amount            | VARCHAR   | 34882122686697945073                                               |                                                              |

## 97. Table: StakingPool\_event\_CapperAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-31 15:36:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10769533                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9cf0c8669b02097a110f4e54c6310f28dca0d39ae2238a7c6a0d0e0e2d0b89d7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 104                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3501ec11d205fa249f2c42f5470e137b529b35d0                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x043500bb7086c4b6457cd8362fd7306b1c90db00                         |                                                              |

## 98. Table: StakingPool\_event\_CapperRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-02 10:23:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12945401                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8e4f30eaca40c40475ccad8956986fe0d2ea90b0841d5a8f459d6693336b94eb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 24                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3501ec11d205fa249f2c42f5470e137b529b35d0                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xe8b87679bf143ddc835ced7670b6f594a501fd80                         |                                                              |

## 99. Table: StakingPool\_event\_DefaultUserCapChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-31 19:50:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10770726                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x91c8976d661c333d40bfb8ee24b0368324d8e22e792fc8459375383953c4d81b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 198                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3501ec11d205fa249f2c42f5470e137b529b35d0                         | Address of the contract that produced the log                |
| newCap            | VARCHAR   | 2000000000000000000000000                                          |                                                              |

## 100. Table: StakingPool\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-12 09:46:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10644388                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x070208edd526063374d593e1f145a1abaa0d0aa5b2beff354384d004b09e88ea | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 9                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3501ec11d205fa249f2c42f5470e137b529b35d0                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x043500bb7086c4b6457cd8362fd7306b1c90db00                         |                                                              |

## 101. Table: StakingPool\_event\_PoolAddressChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-12 09:46:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10644388                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x070208edd526063374d593e1f145a1abaa0d0aa5b2beff354384d004b09e88ea | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3501ec11d205fa249f2c42f5470e137b529b35d0                         | Address of the contract that produced the log                |
| newPool           | VARCHAR   | 0x4c39b37f5f20a0695bfdc59cf10bd85a6c4b7c30                         |                                                              |

## 102. Table: StakingPool\_event\_Staked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-27 05:20:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13497499                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x126cd915f5fb08c43cddc2a83c5b85cc6ed477d207d457164aa7da58ad3ccff6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 547                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3501ec11d205fa249f2c42f5470e137b529b35d0                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x0f7b4f65d19911cd4e47b618bbbcce07b6ceeda5                         |                                                              |
| amount            | VARCHAR   | 13560481592675520610939                                            |                                                              |
| totalStacked      | VARCHAR   | 16869129690522378932764                                            |                                                              |
| data              | VARCHAR   | 0x00                                                               |                                                              |

## 103. Table: StakingPool\_event\_StakingCapChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-31 19:52:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10770732                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfe01efcb9d4ba541e75cf4656f99fbada5eb9425a1a2bd4ce4bc814b497a5e5d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 117                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3501ec11d205fa249f2c42f5470e137b529b35d0                         | Address of the contract that produced the log                |
| newCap            | VARCHAR   | 433000000000000000000000000                                        |                                                              |

## 104. Table: StakingPool\_event\_StakingCapEnabledChange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-11 15:51:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10841493                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4912296c7460817a8a74881a85fed8eb35cf2e5ac8dd988956c6abc4a19ac00c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 90                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3501ec11d205fa249f2c42f5470e137b529b35d0                         | Address of the contract that produced the log                |
| enabled           | VARCHAR   | false                                                              |                                                              |

## 105. Table: StakingPool\_event\_Unstaked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-29 13:24:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17798972                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd2b1f16b342868ce22c0733b1853d8c9bcf329215d215c12ab36fce86dd8a275 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 109                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3501ec11d205fa249f2c42f5470e137b529b35d0                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xb156f1962fe738d22eba5658a927157a869e719a                         |                                                              |
| amount            | VARCHAR   | 26667352516271756676135                                            |                                                              |
| totalStacked      | VARCHAR   | 0                                                                  |                                                              |
| data              | VARCHAR   | 0x00                                                               |                                                              |

## 106. Table: StakingPool\_event\_UserCapChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-23 05:09:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10714581                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf5ad6559ff9542de2dbcb8d1f0d0f28fe5de1cdd79b7dc4b4e76925c851cc6da | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 120                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3501ec11d205fa249f2c42f5470e137b529b35d0                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xdd45f56bd7b0390a31e3c5ee88a200a9591bc361                         |                                                              |
| newCap            | VARCHAR   | 0                                                                  |                                                              |

## 107. Table: StakingPool\_event\_UserCapEnabledChange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-12 10:57:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10644728                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3f04a214d7d30acd46fd499beb5cdeba3a1d9607b113f7e127914c6584f3f09e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 199                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3501ec11d205fa249f2c42f5470e137b529b35d0                         | Address of the contract that produced the log                |
| enabled           | VARCHAR   | true                                                               |                                                              |

## 108. Table: StakingPool\_event\_setLockInDuration\_history

| Column                | Type      | Example                                                      | Description |
| --------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp      | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number         | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash     | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index            | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address     | VARCHAR   | Address of the contract that produced the log                |             |
| defaultLockInDuration | VARCHAR   |                                                              |             |
