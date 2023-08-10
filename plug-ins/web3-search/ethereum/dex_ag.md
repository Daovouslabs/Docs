# dex\_ag

## 1. Table: DexTrading\_v1\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-08-20 20:57:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8389512                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9f9e249c6590de7590c0dbac5e9e96ce539bda4aac23284b2d0d2df59b70ce3f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd3bed3a8e3e6b24b740ead108ba776e0ad298588                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0xd0c81e82abddf29c6505d660f5bebe60cdff03c5                         |                                                              |

## 2. Table: DexTrading\_v1\_event\_Trade\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-09-16 20:35:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8562701                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x831b36e5429b3efd95aa0cbad95af1a3bc803fbfa40f6368999ece9e16c24b36 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 41                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd3bed3a8e3e6b24b740ead108ba776e0ad298588                         | Address of the contract that produced the log                |
| fromToken         | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| toToken           | VARCHAR   | 0x89d24a6b4ccb1b6faa2625fe562bdd9a23260359                         |                                                              |
| amount            | VARCHAR   | 1000000000000000033                                                |                                                              |
| trader            | VARCHAR   | 0xb806c4d481d29a73e394a7d22de04ade3d1d4780                         |                                                              |
| exchanges         | VARCHAR   | 0x76481cAa104B5f6BCcB540Dae4CEfaF1c398EBea                         |                                                              |

## 3. Table: DexTrading\_v2\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-09-25 19:57:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8620106                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x877bdfe7f39ed613f9a390e164cd532ec5730795300d20127ee9977a1d08bf12 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 27                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x932348df588923ba3f1fd50593b22c4e2a287919                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0xd0c81e82abddf29c6505d660f5bebe60cdff03c5                         |                                                              |

## 4. Table: DexTrading\_v2\_event\_Trade\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-07 12:01:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8694812                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x708b387c9989c60f2562188d8da3a0ef9d2a57e0756de1149e09e1b36e4e5a9f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 47                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x932348df588923ba3f1fd50593b22c4e2a287919                         | Address of the contract that produced the log                |
| fromToken         | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| toToken           | VARCHAR   | 0x0cf0ee63788a0849fe5297f3407f701e122cc023                         |                                                              |
| amount            | VARCHAR   | 862171263786468742                                                 |                                                              |
| trader            | VARCHAR   | 0xeefd4ec15437568210e77181a3f61c3201f8554e                         |                                                              |
| exchanges         | VARCHAR   | 0x4F0d6E2179938828CfF93dA40a8BA1Df7519Ca8C                         |                                                              |

## 5. Table: DexTrading\_v3\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-14 18:46:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8741163                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2e91105f67124dcc4aab41a6d1e78f444f0073e3e277a7b01fd548b192b994b2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa540fb50288cc31639305b1675c70763c334953b                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0xd0c81e82abddf29c6505d660f5bebe60cdff03c5                         |                                                              |

## 6. Table: DexTrading\_v3\_event\_Trade\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-27 17:39:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9365397                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x78f8367a78543b16d46a13cbb6017e3196b6987c502bedbbb5febdd61aa61040 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 29                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa540fb50288cc31639305b1675c70763c334953b                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         |                                                              |
| to                | VARCHAR   | 0x0f5d2fb29fb7d3cfee444a200298f468908cc942                         |                                                              |
| toAmount          | VARCHAR   | 200000000000000000000                                              |                                                              |
| trader            | VARCHAR   | 0x56b00d1911086cc3872991eeb875e6ae017c4bb2                         |                                                              |
| exchanges         | VARCHAR   | 0x2a1530C4C41db0B0b2bB646CB5Eb1A67b7158667                         |                                                              |
| tradeType         | VARCHAR   | 1                                                                  |                                                              |

## 7. Table: DexTrading\_v4\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-27 17:46:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9365425                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa88b24fc81c54f3feb261f30c27ebb5e3a7cf26c8043e9f4928b53ea62de0f33 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 35                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x745daa146934b27e3f0b6bff1a6e36b9b90fb131                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0xd0c81e82abddf29c6505d660f5bebe60cdff03c5                         |                                                              |

## 8. Table: DexTrading\_v4\_event\_Trade\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-23 21:25:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10518099                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6d86769e5a116327cfec445fbf2be3e4b89c9bc0ed0fe0a7497135b69bb6305a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 56                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x745daa146934b27e3f0b6bff1a6e36b9b90fb131                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| to                | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         |                                                              |
| toAmount          | VARCHAR   | 1060350243996125227                                                |                                                              |
| trader            | VARCHAR   | 0x2d8849eaab159d20abf10d4a80c97281a12448cc                         |                                                              |
| exchanges         | VARCHAR   | 0x2a1530C4C41db0B0b2bB646CB5Eb1A67b7158667                         |                                                              |
| tradeType         | VARCHAR   | 0                                                                  |                                                              |
