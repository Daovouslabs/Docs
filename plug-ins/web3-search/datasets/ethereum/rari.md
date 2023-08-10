# rari

## 1. Table: AdminUpgradeabilityProxy\_event\_AdminChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousAdmin     | VARCHAR   |                                                              |             |
| newAdmin          | VARCHAR   |                                                              |             |

## 2. Table: AdminUpgradeabilityProxy\_event\_Upgraded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-20 22:05:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12865992                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1a79dacaa2771ae3621a4c780a7a4beda9df45c136878757c465faf663c2a0cd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 173                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd291e7a03283640fdc51b121ac401383a46cc623                         | Address of the contract that produced the log                |
| implementation    | VARCHAR   | 0xf00d7dd883ca85cc39f89d077e563fbcafaf3117                         |                                                              |

## 3. Table: RariFundController\_event\_CurrencyTrade\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2021-03-01 19:55:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 11954336                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x6ffb8e17227849521ed167155095707d11d6fac73132d055196b3f15753b082d | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 143                                                                | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x369855b051d1b2dbee88a792dcfc08614ff4e262                         | Address of the contract that produced the log                |
| inputCurrencyCode  | VARCHAR   | 0xd6aca1be9729c13d677335161321649cccae6a591554772516700f986f942eaa |                                                              |
| outputCurrencyCode | VARCHAR   | 0x33d80a03b5585b94e68b56bdea4f57fd2e459401902cb2f61772e1b630afb4b2 |                                                              |
| inputAmount        | VARCHAR   | 378735668314                                                       |                                                              |
| inputAmountUsd     | VARCHAR   | 378735668314000000000000                                           |                                                              |
| outputAmount       | VARCHAR   | 378735668314000000000000                                           |                                                              |
| outputAmountUsd    | VARCHAR   | 378735668314000000000000                                           |                                                              |
| exchange           | VARCHAR   | 1                                                                  |                                                              |

## 4. Table: RariFundController\_event\_FundDisabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-05 02:51:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12371615                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7ad74d0256f1fa03a3fb1041c57841c258b37960c0cf1c3b201428b8229807ed | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 207                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x369855b051d1b2dbee88a792dcfc08614ff4e262                         | Address of the contract that produced the log                |

## 5. Table: RariFundController\_event\_FundEnabled\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 6. Table: RariFundController\_event\_FundManagerSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-09 08:11:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11821087                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xba6b18d6bba0693105e3667e9f6c61d0ebcbc8ad3b4b7d575b0d99dea19e3d36 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 73                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x369855b051d1b2dbee88a792dcfc08614ff4e262                         | Address of the contract that produced the log                |
| newAddress        | VARCHAR   | 0xc6bf8c8a55f77686720e0a88e2fd1feef58ddf4a                         |                                                              |

## 7. Table: RariFundController\_event\_FundRebalancerSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-09 08:13:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11821101                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe7673ccdc3c81e5a17508f0c1b96ade57405553c01f87ccfa03cd5216c7d5533 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 221                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x369855b051d1b2dbee88a792dcfc08614ff4e262                         | Address of the contract that produced the log                |
| newAddress        | VARCHAR   | 0x1e87ebbe2e02037dd4697d443c5507ff97959c99                         |                                                              |

## 8. Table: RariFundController\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-28 23:00:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12331752                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf48dd982cc6028321cca578cae5700e4c37994bd494323eb91f5da91d776e2b1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 84                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x369855b051d1b2dbee88a792dcfc08614ff4e262                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x5ea4a9a7592683bf0bc187d6da706c6c4770976f                         |                                                              |
| newOwner          | VARCHAR   | 0x10db6bce3f2ae1589ec91a872213dae59697967a                         |                                                              |

## 9. Table: RariFundController\_event\_PoolAllocation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-12 07:28:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11840449                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xda591d1992e0ac7b07c28c130715430a5f860ef01f587aef5b5d024ad8e5c9ec | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 225                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x369855b051d1b2dbee88a792dcfc08614ff4e262                         | Address of the contract that produced the log                |
| action            | VARCHAR   | 1                                                                  |                                                              |
| pool              | VARCHAR   | 1                                                                  |                                                              |
| currencyCode      | VARCHAR   | 0xd6aca1be9729c13d677335161321649cccae6a591554772516700f986f942eaa |                                                              |
| amount            | VARCHAR   | 11464960468                                                        |                                                              |

## 10. Table: RariFundProxy\_event\_FundManagerSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-25 19:03:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11329300                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb56b8bd4f467782c6d414eca934bae67412bd3a2577aa5803aa925f46a1a9224 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 38                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe4dee94233dd4d7c2504744ee6d34f3875b3b439                         | Address of the contract that produced the log                |
| newContract       | VARCHAR   | 0xc6bf8c8a55f77686720e0a88e2fd1feef58ddf4a                         |                                                              |

## 11. Table: RariFundProxy\_event\_GsnTrustedSignerSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-25 19:03:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11329301                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x82694d40f91944059ee4825abd8ef2f0580d9d6d49035b0f1d38fe146ed45ea5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 83                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe4dee94233dd4d7c2504744ee6d34f3875b3b439                         | Address of the contract that produced the log                |
| newAddress        | VARCHAR   | 0x6beaaac7c5c094fd2a6e9f498bd8431b22b548d5                         |                                                              |

## 12. Table: RariFundProxy\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-20 16:42:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12076802                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0cc822a362f680da90069edf2bba224539c96e1f3e5d24a159d16d379ac678c8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 91                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe4dee94233dd4d7c2504744ee6d34f3875b3b439                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x10db6bce3f2ae1589ec91a872213dae59697967a                         |                                                              |
| newOwner          | VARCHAR   | 0x5ea4a9a7592683bf0bc187d6da706c6c4770976f                         |                                                              |

## 13. Table: RariFundProxy\_event\_PostWithdrawalExchange\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2021-03-02 22:11:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 11961475                                                           | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0xeb911a8e8b0a4977da53c7c32b49b647916b21d911adc06e7c730fb6d6e7c508 | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 194                                                                | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0xe4dee94233dd4d7c2504744ee6d34f3875b3b439                         | Address of the contract that produced the log                |
| inputCurrencyCode        | VARCHAR   | 0x33d80a03b5585b94e68b56bdea4f57fd2e459401902cb2f61772e1b630afb4b2 |                                                              |
| outputErc20Contract      | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| payee                    | VARCHAR   | 0xf7411a3f727b36f56ff3a871163c21e56d672656                         |                                                              |
| withdrawalAmount         | VARCHAR   | 164822467750000000000000                                           |                                                              |
| withdrawalAmountAfterFee | VARCHAR   | 164822467750000000000000                                           |                                                              |
| makerAssetFilledAmount   | VARCHAR   | 164723574270                                                       |                                                              |

## 14. Table: RariFundProxy\_event\_PreDepositExchange\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2021-02-12 18:38:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 11843486                                                           | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0x42d4ea877fbc0393af2642e03230cf4c606b4587871b5ac3456229391345caa3 | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 235                                                                | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0xe4dee94233dd4d7c2504744ee6d34f3875b3b439                         | Address of the contract that produced the log                |
| inputErc20Contract     | VARCHAR   | 0xdac17f958d2ee523a2206206994597c13d831ec7                         |                                                              |
| outputCurrencyCode     | VARCHAR   | 0xd6aca1be9729c13d677335161321649cccae6a591554772516700f986f942eaa |                                                              |
| payee                  | VARCHAR   | 0xaed55b0ebb566e4ed491f68ef0ec4e705c7a1523                         |                                                              |
| takerAssetFilledAmount | VARCHAR   | 50347870000                                                        |                                                              |
| depositAmount          | VARCHAR   | 50637349176                                                        |                                                              |

## 15. Table: RariFundProxy\_event\_RelayHubChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-25 19:03:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11329297                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4cd9234d3eeb494d1ad4d4c4e1df9c0234f9f7ed1bd6198b0befbdebd62572c1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 32                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe4dee94233dd4d7c2504744ee6d34f3875b3b439                         | Address of the contract that produced the log                |
| oldRelayHub       | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newRelayHub       | VARCHAR   | 0xd216153c06e857cd7f72665e0af1d7d82172f494                         |                                                              |
