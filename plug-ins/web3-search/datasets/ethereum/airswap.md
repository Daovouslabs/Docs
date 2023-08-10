# airswap

## 1. Table: AirSwapExchange\_event\_Canceled\_history

| Column            | Type      | Example                                                                      | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-11-08 20:28:35+00:00                                                    | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6668290                                                                      | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9a27c2e96e75d62a8d38afb5599c92e0b653cb15024f1652cc82af337ea8a074           | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 24                                                                           | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8fd3121013a07c57f0d69646e86e7a4880b467b7                                   | Address of the contract that produced the log                |
| makerAddress      | VARCHAR   | 0x0f8aa39a58adcc3df98d826ac798ab837cc0833c                                   |                                                              |
| makerAmount       | VARCHAR   | 8207683348531251200                                                          |                                                              |
| makerToken        | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                                   |                                                              |
| takerAddress      | VARCHAR   | 0x71f35825a3b1528859dfa1a64b24242bc0d12990                                   |                                                              |
| takerAmount       | VARCHAR   | 4967363799999999639552                                                       |                                                              |
| takerToken        | VARCHAR   | 0x0d8775f648430679a709e98d2b0cb6250d2887ef                                   |                                                              |
| expiration        | VARCHAR   | 1541708954                                                                   |                                                              |
| nonce             | VARCHAR   | 3825928732768821759571057242742757345040408692932717017446265063420864588423 |                                                              |

## 2. Table: AirSwapExchange\_event\_Failed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-07-19 20:51:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8183342                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x87cb92375bc6859d4a78e85e1610da000f5fb521a2bb995ec04a9d1a87c987ba | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 17                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8fd3121013a07c57f0d69646e86e7a4880b467b7                         | Address of the contract that produced the log                |
| code              | VARCHAR   | 2                                                                  |                                                              |
| makerAddress      | VARCHAR   | 0x1550d41be3651686e1aeeea073d8d403d0bd2e30                         |                                                              |
| makerAmount       | VARCHAR   | 50000000000000000000                                               |                                                              |
| makerToken        | VARCHAR   | 0x89d24a6b4ccb1b6faa2625fe562bdd9a23260359                         |                                                              |
| takerAddress      | VARCHAR   | 0x00ace6f9c2d01981b709e6b24334bbefe83ace9c                         |                                                              |
| takerAmount       | VARCHAR   | 225395700083256289                                                 |                                                              |
| takerToken        | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| expiration        | VARCHAR   | 1563569453                                                         |                                                              |
| nonce             | VARCHAR   | 19333449                                                           |                                                              |

## 3. Table: AirSwapExchange\_event\_Filled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-09-07 07:23:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6286990                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc29dd776703e0de2f2da990cad5ffaa65653a148a4a23b7377d776b5e90c32eb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 124                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8fd3121013a07c57f0d69646e86e7a4880b467b7                         | Address of the contract that produced the log                |
| makerAddress      | VARCHAR   | 0x2c88496eb96c7779ece9d280d0be87f96daddc27                         |                                                              |
| makerAmount       | VARCHAR   | 100                                                                |                                                              |
| makerToken        | VARCHAR   | 0x08711d3b02c8758f2fb3ab4e80228418a7f8e39c                         |                                                              |
| takerAddress      | VARCHAR   | 0xc12cc48d7b313c504ce6fbf97e2ae06e9f92f2a9                         |                                                              |
| takerAmount       | VARCHAR   | 87772716842588347                                                  |                                                              |
| takerToken        | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| expiration        | VARCHAR   | 1536305121                                                         |                                                              |
| nonce             | VARCHAR   | 19951924                                                           |                                                              |

## 4. Table: LightV2\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-13 05:02:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13014798                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb080168dc0f9d5eba696d868bb29889cd2590c64178dd5536b937b91a88cc6ce | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 80                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc549a5c701cb6e6cbc091007a80c089c49595468                         | Address of the contract that produced the log                |
| nonce             | VARCHAR   | 1628827507369                                                      |                                                              |
| timestamp         | VARCHAR   | 1628830969                                                         |                                                              |
| signerWallet      | VARCHAR   | 0x00000000000080c886232e9b7ebbfb942b5987aa                         |                                                              |
| signerToken       | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| signerAmount      | VARCHAR   | 15072225090842845                                                  |                                                              |
| signerFee         | VARCHAR   | 7                                                                  |                                                              |
| senderWallet      | VARCHAR   | 0x74de5d4fcbf63e00296fd95d33236b9794016631                         |                                                              |
| senderToken       | VARCHAR   | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599                         |                                                              |
| senderAmount      | VARCHAR   | 104201                                                             |                                                              |

## 5. Table: Light\_event\_CancelUpTo\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| nonce             | VARCHAR   |                                                              |             |
| signerWallet      | VARCHAR   |                                                              |             |

## 6. Table: Light\_event\_Cancel\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| nonce             | VARCHAR   |                                                              |             |
| signerWallet      | VARCHAR   |                                                              |             |

## 7. Table: Light\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-24 05:02:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11917865                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x01c115575029015817e1078e1c953a9a51bc9461c64fd556c7c8f23e24bf1bad | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 265                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc50cb225e0f45e814fd41bcb3a120463ab1f04c3                         | Address of the contract that produced the log                |
| nonce             | VARCHAR   | 1614142879                                                         |                                                              |
| timestamp         | VARCHAR   | 1614142942                                                         |                                                              |
| signerWallet      | VARCHAR   | 0xa5d07e978398eb1715056d3ca5cb31035c02fdad                         |                                                              |
| senderWallet      | VARCHAR   | 0x74de5d4fcbf63e00296fd95d33236b9794016631                         |                                                              |
| signerToken       | VARCHAR   | 0x0bc529c00c6401aef6d220be8c6ea1667f6ad93e                         |                                                              |
| senderToken       | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| signerAmount      | VARCHAR   | 13771726518151570                                                  |                                                              |
| senderAmount      | VARCHAR   | 299100000000000000                                                 |                                                              |

## 8. Table: SwapOld\_event\_Authorize\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| approverAddress   | VARCHAR   |                                                              |             |
| delegateAddress   | VARCHAR   |                                                              |             |
| expiry            | VARCHAR   |                                                              |             |

## 9. Table: SwapOld\_event\_Cancel\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-08-30 20:49:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8453798                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbb49fe62a455a48387cc3891f045db1f7943b348bc772d001ee66c5bcb255d34 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 42                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x54d2690e97e477a4b33f40d6e4afdd4832c07c57                         | Address of the contract that produced the log                |
| nonce             | VARCHAR   | 1567198054892                                                      |                                                              |
| makerWallet       | VARCHAR   | 0x7c675fd4d6ee644a7d758ab1c03b3312976d0103                         |                                                              |

## 10. Table: SwapOld\_event\_Invalidate\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| nonce             | VARCHAR   |                                                              |             |
| makerWallet       | VARCHAR   |                                                              |             |

## 11. Table: SwapOld\_event\_Revoke\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| approverAddress   | VARCHAR   |                                                              |             |
| delegateAddress   | VARCHAR   |                                                              |             |

## 12. Table: SwapOld\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-08-25 22:16:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8422040                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2898f1e0c3530396eba32bad577228a072ae67d5d7f1547bc565158bff76d5e5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 145                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x54d2690e97e477a4b33f40d6e4afdd4832c07c57                         | Address of the contract that produced the log                |
| nonce             | VARCHAR   | 1566771096128                                                      |                                                              |
| timestamp         | VARCHAR   | 1566771378                                                         |                                                              |
| makerWallet       | VARCHAR   | 0x1b616b7e05c21801c91461e31f5c22c2a4cf0fef                         |                                                              |
| makerParam        | VARCHAR   | 1000000000000000000                                                |                                                              |
| makerToken        | VARCHAR   | 0x89d24a6b4ccb1b6faa2625fe562bdd9a23260359                         |                                                              |
| takerWallet       | VARCHAR   | 0x0b604d6342087f46b817d3232b41d7a147a3b38c                         |                                                              |
| takerParam        | VARCHAR   | 1000000                                                            |                                                              |
| takerToken        | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| affiliateWallet   | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| affiliateParam    | VARCHAR   | 0                                                                  |                                                              |
| affiliateToken    | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 13. Table: SwapV3\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-29 01:53:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16287259                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4077c48253442b87e657445249acadd1046b60eb0566324e8be614118bfb865b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 77                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x522d6f36c95a1b6509a14272c17747bbb582f2a6                         | Address of the contract that produced the log                |
| nonce             | VARCHAR   | 1672278772                                                         |                                                              |
| timestamp         | VARCHAR   | 1672278815                                                         |                                                              |
| signerWallet      | VARCHAR   | 0x945bcf562085de2d5875b9e2012ed5fd5cfab927                         |                                                              |
| signerToken       | VARCHAR   | 0x0f5d2fb29fb7d3cfee444a200298f468908cc942                         |                                                              |
| signerAmount      | VARCHAR   | 6660957312817142000000                                             |                                                              |
| protocolFee       | VARCHAR   | 7                                                                  |                                                              |
| senderWallet      | VARCHAR   | 0x74de5d4fcbf63e00296fd95d33236b9794016631                         |                                                              |
| senderToken       | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| senderAmount      | VARCHAR   | 1687369000000000000                                                |                                                              |

## 14. Table: Swap\_event\_AuthorizeSender\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-16 06:02:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11866068                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9ca934852695ee0713f146b88d5ed4656df8be52465dd7c25c94aa4df2b8b339 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 36                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4572f2554421bd64bef1c22c8a81840e8d496bea                         | Address of the contract that produced the log                |
| authorizerAddress | VARCHAR   | 0x0fe85948329dcedd0236535ad9b5570f79c1b870                         |                                                              |
| authorizedSender  | VARCHAR   | 0x28de5c5f56b6216441ee114e832808d5b9d4a775                         |                                                              |

## 15. Table: Swap\_event\_Cancel\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-28 14:40:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9760558                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6c2402b5511831fee7e6f6f1d05d28b82a45efbef7aa5b3a4ff4a9134d91e65e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4572f2554421bd64bef1c22c8a81840e8d496bea                         | Address of the contract that produced the log                |
| nonce             | VARCHAR   | 1585313469372                                                      |                                                              |
| signerWallet      | VARCHAR   | 0x6a668661d579049e3ad7cbd0bdef371f95d751a4                         |                                                              |

## 16. Table: Swap\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-15 09:51:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14390442                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe45cf5646d2d443a2733a4da52204606ecc878bf4a951bb1858c887d37a9ef44 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 53                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4572f2554421bd64bef1c22c8a81840e8d496bea                         | Address of the contract that produced the log                |
| nonce             | VARCHAR   | 1647337743797                                                      |                                                              |
| timestamp         | VARCHAR   | 1647337890                                                         |                                                              |
| signerWallet      | VARCHAR   | 0x47b0a469cdf3618677968e9830595270f24abf26                         |                                                              |
| signerAmount      | VARCHAR   | 428820075105220000000000                                           |                                                              |
| signerId          | VARCHAR   | 0                                                                  |                                                              |
| signerToken       | VARCHAR   | 0xaf1250fa68d7decd34fd75de8742bc03b29bd58e                         |                                                              |
| senderWallet      | VARCHAR   | 0x0604e3ba11cc7c07df78465cafc85c0548585942                         |                                                              |
| senderAmount      | VARCHAR   | 218355000000                                                       |                                                              |
| senderId          | VARCHAR   | 0                                                                  |                                                              |
| senderToken       | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| affiliateWallet   | VARCHAR   | 0xff98f0052bda391f8fad266685609ffb192bef25                         |                                                              |
| affiliateAmount   | VARCHAR   | 0                                                                  |                                                              |
| affiliateId       | VARCHAR   | 0                                                                  |                                                              |
| affiliateToken    | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
