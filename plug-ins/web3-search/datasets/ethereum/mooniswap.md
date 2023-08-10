# mooniswap

## 1. Table: MooniFactory\_event\_Deployed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-08 02:53:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12391052                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1ef539b0be4351aafff182465d36ac2ca5bde95cde44d3086c27e780926ff3f4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 63                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x71cd6666064c3a1354a3b4dca5fa1e2d3ee7d303                         | Address of the contract that produced the log                |
| mooniswap         | VARCHAR   | 0x36c0a1cdb4af2db71610e8612c74acd20540e3c1                         |                                                              |
| token1            | VARCHAR   | 0x1f9840a85d5af5bf1d1762f925bdaddc4201f984                         |                                                              |
| token2            | VARCHAR   | 0xbf4a2ddaa16148a9d0fa2093ffac450adb7cd4aa                         |                                                              |

## 2. Table: MooniFactory\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-10 21:01:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10634502                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x874890ff017f7506bc4b37437f5d0b3bcbadf8fe7b73fae3c717bbb3ad4816ca | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 54                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x71cd6666064c3a1354a3b4dca5fa1e2d3ee7d303                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x68a17b587caf4f9329f0e372e3a78d23a46de6b5                         |                                                              |

## 3. Table: MooniswapDeployer\_call\_deploy\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-01-05 02:36:34+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 11591834                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x4e0889398b437f3840aa7e35fe73e3b97094ee694737d8ccc4b3218e6ad48289 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 272                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 2                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xa31bb36c5164b165f9c36955ea4ccbab42b3b28e                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| token1             | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         |                                                                                                                        |
| token2             | VARCHAR   | 0xb6c4267c4877bb0d6b1685cfd85b0fbe82f105ec                         |                                                                                                                        |
| name               | VARCHAR   | 1inch Liquidity Pool (DAI-REL)                                     |                                                                                                                        |
| symbol             | VARCHAR   | 1LP-DAI-REL                                                        |                                                                                                                        |
| poolOwner          | VARCHAR   | 0x5e89f8d81c74e311458277ea1be3d3247c7cd7d1                         |                                                                                                                        |

## 4. Table: MooniswapFactory\_event\_DefaultDecayPeriodVoteUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-08 18:59:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11615860                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9394b950a7c27b51a35f6c500c4eb018e71f527f76bb806f68237570007d28c8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 259                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc4a8b7e29e3c8ec560cd4945c1cf3461a85a148d                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x82404770c338c8502d9afbaad786ac24abd6cc24                         |                                                              |
| decayPeriod       | VARCHAR   | 60                                                                 |                                                              |
| isDefault         | VARCHAR   | true                                                               |                                                              |
| amount            | VARCHAR   | 0                                                                  |                                                              |

## 5. Table: MooniswapFactory\_event\_DefaultFeeVoteUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-07 04:05:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11605311                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbcba41adf326ffff5245f04bd8b8a5542493be56062372249ddfea30fc70a35e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc4a8b7e29e3c8ec560cd4945c1cf3461a85a148d                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xb0af2b368c51fa50117c2978390dc3fda1691a52                         |                                                              |
| fee               | VARCHAR   | 0                                                                  |                                                              |
| isDefault         | VARCHAR   | true                                                               |                                                              |
| amount            | VARCHAR   | 1376022044552494721366                                             |                                                              |

## 6. Table: MooniswapFactory\_event\_DefaultSlippageFeeVoteUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-06 06:01:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11599272                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x45070e790d64ec69dd74779851daa1230c3e16dc14c286628da1b07a9d1bf70e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc4a8b7e29e3c8ec560cd4945c1cf3461a85a148d                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xd799f16d365bd525e0cb0ed625c499b220b70ca8                         |                                                              |
| slippageFee       | VARCHAR   | 1000000000000000000                                                |                                                              |
| isDefault         | VARCHAR   | true                                                               |                                                              |
| amount            | VARCHAR   | 10707392388396770910348                                            |                                                              |

## 7. Table: MooniswapFactory\_event\_Deployed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-31 05:13:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11559921                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa8c80c264e8f670e337e412a046bf30e249751ae5df71b283251e3c28ace179a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 29                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc4a8b7e29e3c8ec560cd4945c1cf3461a85a148d                         | Address of the contract that produced the log                |
| mooniswap         | VARCHAR   | 0x6b53a595b194854c9e876073bcf922d6c04a6362                         |                                                              |
| token1            | VARCHAR   | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599                         |                                                              |
| token2            | VARCHAR   | 0x595832f8fc6bf59c85c527fec3740a1b7a361269                         |                                                              |

## 8. Table: MooniswapFactory\_event\_GovernanceFeeReceiverUpdate\_history

| Column                | Type      | Example                                                            | Description                                                  |
| --------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp      | TIMESTAMP | 2020-12-24 17:40:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number         | INTEGER   | 11517716                                                           | The block number where this event was emitted                |
| transaction\_hash     | VARCHAR   | 0x1ff815db40c8cf1d4cf02ba141970667d11ce2337bc21395736852757de35b7b | Hash of the transactions in which this event was emitted     |
| log\_index            | INTEGER   | 15                                                                 | Integer of the log index position in the block of this event |
| contract\_address     | VARCHAR   | 0xc4a8b7e29e3c8ec560cd4945c1cf3461a85a148d                         | Address of the contract that produced the log                |
| governanceFeeReceiver | VARCHAR   | 0x4dfa40fdaa7694676899f8887a45603922609af4                         |                                                              |

## 9. Table: MooniswapFactory\_event\_GovernanceShareVoteUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-07 04:05:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11605311                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbcba41adf326ffff5245f04bd8b8a5542493be56062372249ddfea30fc70a35e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 25                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc4a8b7e29e3c8ec560cd4945c1cf3461a85a148d                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xb0af2b368c51fa50117c2978390dc3fda1691a52                         |                                                              |
| governanceShare   | VARCHAR   | 0                                                                  |                                                              |
| isDefault         | VARCHAR   | true                                                               |                                                              |
| amount            | VARCHAR   | 1376022044552494721366                                             |                                                              |

## 10. Table: MooniswapFactory\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-24 17:38:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11517708                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xec7cf0101cdd2efc190544a9a890524962298cee19cbe43dfd59f736d2e86225 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 115                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc4a8b7e29e3c8ec560cd4945c1cf3461a85a148d                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x11799622f4d98a24514011e8527b969f7488ef47                         |                                                              |

## 11. Table: MooniswapFactory\_event\_Paused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |

## 12. Table: MooniswapFactory\_event\_ReferralFeeReceiverUpdate\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2020-12-24 17:41:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 11517720                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x16ae0c324ac78ec288ad095bc72b771c43e7e0de6e461f26c655f2e76626d81b | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 70                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0xc4a8b7e29e3c8ec560cd4945c1cf3461a85a148d                         | Address of the contract that produced the log                |
| referralFeeReceiver | VARCHAR   | 0x735247fb0a604c0adc6cab38ace16d0dba31295f                         |                                                              |

## 13. Table: MooniswapFactory\_event\_ReferralShareVoteUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-06 06:39:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11599438                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8106f546af02aeaa92d26fe7443afea2ec7f5338b5071f0b2146ccfc545bcc14 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 201                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc4a8b7e29e3c8ec560cd4945c1cf3461a85a148d                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x727268ed5d7d06da58b0e59de0f8d8dcc6a7dfa3                         |                                                              |
| referralShare     | VARCHAR   | 100000000000000000                                                 |                                                              |
| isDefault         | VARCHAR   | true                                                               |                                                              |
| amount            | VARCHAR   | 0                                                                  |                                                              |

## 14. Table: MooniswapFactory\_event\_Unpaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |

## 15. Table: Mooniswap\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-13 01:47:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11643787                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xce73d97ff7c58ccbc545a46f1c36a38551bbfd53de3635b991cf6e6589461f7b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 194                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x75116bd1ab4b0065b44e1a4ea9b4180a171406ed                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x36d682015029d304041c9fe757f48f8adba8efd5                         |                                                              |
| spender           | VARCHAR   | 0x111111125434b319222cdbf8c261674adb56f3ae                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 16. Table: Mooniswap\_event\_Deposited\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-08 15:12:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11412880                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa6ab2be8cc0e4a6a002810a802a4f76419c98f817f274a5ea866c92b25183e7b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 110                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0f502b9685519b9e1a70a1b8252da71e15b0e87f                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x46b1a1f1d2aeec4abd6b914742467ca39cf240a5                         |                                                              |
| amount            | VARCHAR   | 27230821934341298653                                               |                                                              |

## 17. Table: Mooniswap\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-26 22:18:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10940837                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x463ee8dc7140a2e5ca909afd3c70a8ce9a15d5f2106be6efc7647af5ced81c46 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 166                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x312bf8c6ba1c9054a0e2ddaa91d0a1b0ca7accf3                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x71cd6666064c3a1354a3b4dca5fa1e2d3ee7d303                         |                                                              |

## 18. Table: Mooniswap\_event\_Swapped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-04 12:48:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11588066                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x16035ed94d7356191fcc030b146e05075a0c27742ae4792ef9e49b95cc38ef98 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 297                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0e6f6c7b6aaa35db1d3dbdabb35312ee0d4954fb                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xe069cb01d06ba617bcdf789bf2ff0d5e5ca20c71                         |                                                              |
| src               | VARCHAR   | 0x674c6ad92fd080e4004b2312b45f796a192d27a0                         |                                                              |
| dst               | VARCHAR   | 0x9d79d5b61de59d882ce90125b18f74af650acb93                         |                                                              |
| amount            | VARCHAR   | 5000000000000000000000                                             |                                                              |
| result            | VARCHAR   | 1292605168                                                         |                                                              |
| srcBalance        | VARCHAR   | 81229032164489747048288                                            |                                                              |
| dstBalance        | VARCHAR   | 22355206325                                                        |                                                              |
| totalSupply       | VARCHAR   | 48776725011007559665577                                            |                                                              |
| referral          | VARCHAR   | 0x910bf2d50fa5e014fd06666f456182d4ab7c8bd2                         |                                                              |

## 19. Table: Mooniswap\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-23 02:58:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17319126                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaed65ccb2a5ce6e4b1ba514614d72eb8b341551eedd7f47b34421567855cd6c7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 270                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd0a38cb0a67fa4ea83cac1f441e5aedfa9ba1155                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x1657a2c8561662268c383a81f27d1148272ee8d1                         |                                                              |
| to                | VARCHAR   | 0x18ba5ccc7ab89204fdd66e96e3554eb80a2f27a6                         |                                                              |
| value             | VARCHAR   | 37405479                                                           |                                                              |

## 20. Table: Mooniswap\_event\_Withdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-17 17:38:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12453341                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xacb75c1f4183643178f019ad4ac13fedf5e9bde1d418000c052305bf72892cc5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 163                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbeabef3fc02667d8bd3f702ae0bb2c4edb3640cc                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x0fbaaac9d4e870bd9b09e3abbff04488153c2478                         |                                                              |
| amount            | VARCHAR   | 980999105983870220                                                 |                                                              |

## 21. Table: Mooniswap\_v2\_event\_Swapped\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2022-02-04 15:01:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 14140209                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x957b0294a50f3d52b9a6ff630c9bcf714ec111c276bc1e9b0f9c0ed558f4ce46 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 103                                                                | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0xb741626918cdf8fef9ec4d2a365d218427a1ba70                         | Address of the contract that produced the log                |
| sender             | VARCHAR   | 0x220bda5c8994804ac96ebe4df184d25e5c2196d4                         |                                                              |
| receiver           | VARCHAR   | 0x220bda5c8994804ac96ebe4df184d25e5c2196d4                         |                                                              |
| srcToken           | VARCHAR   | 0xdac17f958d2ee523a2206206994597c13d831ec7                         |                                                              |
| dstToken           | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| amount             | VARCHAR   | 133332000                                                          |                                                              |
| result             | VARCHAR   | 48678647271360315                                                  |                                                              |
| srcAdditionBalance | VARCHAR   | 5728907971                                                         |                                                              |
| dstRemovalBalance  | VARCHAR   | 2150170918084076337                                                |                                                              |
| referral           | VARCHAR   | 0x1611c227725c5e420ef058275ae772b41775e261                         |                                                              |
