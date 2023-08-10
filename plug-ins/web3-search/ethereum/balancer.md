# balancer

## 1. Table: AuthorizerAdaptor\_call\_performAction\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-08-03 00:06:35+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17830788                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x6477ec51afd96a2674ae956ec3d495929854e182f3b66d6f69a01ae15ac65a1f | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 57                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 112,3                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x8f42adbba1b16eaae3bb5754915e0d06059add75                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| target             | VARCHAR   | 0x730a168cf6f501cf302b803ffc57ff3040f378bf                         |                                                                                                                        |
| data               | VARCHAR   | 0xc2c4c5c1                                                         |                                                                                                                        |

## 2. Table: BFactory\_event\_LOG\_BLABS\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| caller            | VARCHAR   |                                                              |             |
| blabs             | VARCHAR   |                                                              |             |

## 3. Table: BFactory\_event\_LOG\_NEW\_POOL\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-11 18:44:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12018955                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb779d6275f235b6abc5c04de2adfecc4b7a5ef83e95c6176ef5ba4a380b0714e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 90                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9424b1412450d0f8fc2255faf6046b98213b76bd                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x0dafdc62cd40a34202fa9be0221af1a93e5f4f35                         |                                                              |
| pool              | VARCHAR   | 0xf66f09fa46fa23c2294b1af3aa6d073dd829c1b4                         |                                                              |

## 4. Table: BPool\_call\_bind\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-08-03 07:59:50+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 10585640                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x93cdba97916f4a195158352496b5bee230be95ebbdc65ba68fec08077fe69d25 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 7                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 7                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x71c4f1a8d95ad1faa0f893b74ca67fdf53ee63fb                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| token              | VARCHAR   | 0xc00e94cb662c3520282e6f5717214004a7f26888                         |                                                                                                                        |
| balance            | VARCHAR   | 10069862312601948                                                  |                                                                                                                        |
| denorm             | VARCHAR   | 6693800000000000000                                                |                                                                                                                        |

## 5. Table: BPool\_call\_finalize\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-10-23 17:17:51+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 11113885                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xa53082c3769fcb43dc48b4e7b5b3fee6aaf1f52bab22b4833fb731388a99091d | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 28                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,10                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x09f42e8a9363867283f0eea88fa6c3700e07ef03                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 6. Table: BPool\_call\_rebind\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-03-15 02:04:35+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14388404                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x229c67f40e9e8e60fc3de2815ee86d8de9b5b6a996f1f77472700d66d7bab628 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 65                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 1,0,6                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x7860e28ebfb8ae052bfe279c07ac5d94c9cd2937                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| token              | VARCHAR   | 0xd46ba6d942050d489dbd938a2c909a5d5039a161                         |                                                                                                                        |
| balance            | VARCHAR   | 268451064497180                                                    |                                                                                                                        |
| denorm             | VARCHAR   | 4082579020779489976                                                |                                                                                                                        |

## 7. Table: BPool\_call\_setController\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-01-04 02:45:29+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 11585367                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xa939628be458d5a9275bfd45441cd666cbfc83327db3b447d5b1d192239213b2 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 71                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0,1                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x916c40a707e6c3efd0e6dc95f620250aa68ee182                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| manager            | VARCHAR   | 0x697bbee86494addc623f3717f68971419922ea15                         |                                                                                                                        |

## 8. Table: BPool\_call\_setPublicSwap\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-04-04 13:20:13+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 12173344                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x446b47435fe8ca299fd05921a2eb9775c8d2acc0c4a4dd034d029e93693480d8 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 110                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,8,1                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x249dda6b483f3fde86cd1937e825f0901c1151f3                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| public\_           | VARCHAR   | false                                                              |                                                                                                                        |

## 9. Table: BPool\_call\_setSwapFee\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-03-14 21:28:13+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 12039129                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xf55f9f1e7d76c1c2c07428f2323c9fa0d10d2105aeda53a6dda5499bfff60270 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 49                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,1                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xfc5c34a81d63321e47194761ccfb4b8bdf82da11                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| swapFee            | VARCHAR   | 1000000000000000                                                   |                                                                                                                        |

## 10. Table: BPool\_call\_unbind\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-05-22 09:46:33+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 12483381                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x1ea0c923234854f96ea3a5331e5b60ac04ce3d10e0ae4a5aac2c701be9ead689 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 199                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,1,0,4                                                            | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3bae066c2908ed02d4333d78713e8f4ef6c7d2fb                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| token              | VARCHAR   | 0xba100000625a3754423978a60c9317c58a424e3d                         |                                                                                                                        |

## 11. Table: BPool\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-26 14:31:18+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12510497                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x980351601e74c610b85668616ec9c8de6f7e96a34014138959b8cab5492817b0             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 258                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdb942c0851774bd817e6f4813f1fa64cce6fe25f                                     | Address of the contract that produced the log                |
| src               | VARCHAR   | 0x4398193d60dd9237097880a798dc16fd81802646                                     |                                                              |
| dst               | VARCHAR   | 0x008f3dde2ed44bdc72800108d8309d16d55d6dd5                                     |                                                              |
| amt               | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 12. Table: BPool\_event\_LOG\_CALL\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| sig               | VARCHAR   |                                                              |             |
| caller            | VARCHAR   |                                                              |             |
| data              | VARCHAR   |                                                              |             |

## 13. Table: BPool\_event\_LOG\_EXIT\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-08 23:54:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11017939                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x96d8d8885a45333c4923be5b74d724f5f5569b3062789b3af080d8ca40565c64 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 102                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0e511aa1a137aad267dfe3a6bfca0b856c1a3682                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x3f969504bb7311235773d7bb58292675d606805c                         |                                                              |
| tokenOut          | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| tokenAmountOut    | VARCHAR   | 1235883475630769                                                   |                                                              |

## 14. Table: BPool\_event\_LOG\_JOIN\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-29 18:19:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13901824                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2779b7ba863fa59c09e97fcc7bdf6e033bed6027690dbb6706b1a2fb53d94889 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 36                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc1b10e536cd611acff7a7c32a9e29ce6a02ef6ef                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x05012e34074edc501f21cbfcb5e80bfb07e427ec                         |                                                              |
| tokenIn           | VARCHAR   | 0x33349b282065b0284d756f0577fb39c158f935e6                         |                                                              |
| tokenAmountIn     | VARCHAR   | 42615778116000000029988                                            |                                                              |

## 15. Table: BPool\_event\_LOG\_SWAP\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-06 11:18:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11001891                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x33876075891ec7c91772b0ec70765e9451add3add0628db3a9e299e01aef9826 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 114                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0bdf7efef728308b6f55b1dd8d0c714f0d5d233f                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x8fc5541dbcff9595494fba3ce4cabc5e995935ed                         |                                                              |
| tokenIn           | VARCHAR   | 0xeca82185adce47f39c684352b0439f030f860318                         |                                                              |
| tokenOut          | VARCHAR   | 0x0000000000085d4780b73119b644ae5ecd22b376                         |                                                              |
| tokenAmountIn     | VARCHAR   | 64791811051628797946857                                            |                                                              |
| tokenAmountOut    | VARCHAR   | 1465748899612527466129                                             |                                                              |

## 16. Table: BPool\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-29 13:07:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16290612                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x65f59d0f1df8caca0cfdc46d9ac737990a528d6248fa6bc4cf062378fe73a272 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 166                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x163b4bff56572b55e95085f44ce6939360ef6ae1                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0xc88ac56659412ccdf3493cc764798185b6abf8d5                         |                                                              |
| dst               | VARCHAR   | 0x163b4bff56572b55e95085f44ce6939360ef6ae1                         |                                                              |
| amt               | VARCHAR   | 100000000000000000000                                              |                                                              |

## 17. Table: CRPFactory\_event\_LogNewCrp\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-15 03:07:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11259857                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcdebf6af746a5a95f922072bab917adecdffa16db4f3d9af183422b8423462ad | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 26                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xed52d8e202401645edad1c0aa21e872498ce47d0                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x78e7723e7df6b8d34050f016dfea1145b36908d7                         |                                                              |
| pool              | VARCHAR   | 0x9d6c34173b603b4b2f40ae3ef3bf30d03461dab7                         |                                                              |

## 18. Table: ExchangeProxy2\_call\_batchSwapExactIn\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-09-24 21:18:12+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 10927691                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xa6972acb7d9f22f0de42ca34fe1a4d58dbae93273f5f845976e95eae7eddce75                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 3                                                                                                    | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3e66b66fd1d0b02fda6c811da9e0547970db2f21                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| swaps              | VARCHAR   | 0x930ae255053E40F430a4fda533eAE0de5b131924,0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2,0x1f9840a85d5a |                                                                                                                        |
| tokenIn            | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                                                           |                                                                                                                        |
| tokenOut           | VARCHAR   | 0x1f9840a85d5af5bf1d1762f925bdaddc4201f984                                                           |                                                                                                                        |
| totalAmountIn      | VARCHAR   | 10821375000000000000                                                                                 |                                                                                                                        |
| minTotalAmountOut  | VARCHAR   | 732420840614463143936                                                                                |                                                                                                                        |

## 19. Table: ExchangeProxy2\_call\_batchSwapExactOut\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-11-01 13:47:49+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 11171540                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x8f643280d899a2efba15fed2ca89b181891acb0def0f2f88b9b47dbcaac50e99                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 107                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3e66b66fd1d0b02fda6c811da9e0547970db2f21                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| swaps              | VARCHAR   | 0xaaD387f18E015cF9bE4BDF96854845BE51dDc977,0x6B175474E89094C44Da98b954EedeAC495271d0F,0xE41d2489571d |                                                                                                                        |
| tokenIn            | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                                                           |                                                                                                                        |
| tokenOut           | VARCHAR   | 0xe41d2489571d322189246dafa5ebde1f4699f498                                                           |                                                                                                                        |
| maxTotalAmountIn   | VARCHAR   | 324161180016216833                                                                                   |                                                                                                                        |

## 20. Table: ExchangeProxy2\_call\_multihopBatchSwapExactIn\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-10-27 12:50:23+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 13499495                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xdcd5aea00a04974437868e8b1f130b050587784c340c1b00e3169996c34c1afb                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 322                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3e66b66fd1d0b02fda6c811da9e0547970db2f21                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| swapSequences      | VARCHAR   | 0x4E2579468f414F3B2c683e8562d4c67056d5CB4B,0x24D8C2163D6B13A6B8770B794d00c98Cb4E0cBCa,0xA0b86991c621 |                                                                                                                        |
| tokenIn            | VARCHAR   | 0x24d8c2163d6b13a6b8770b794d00c98cb4e0cbca                                                           |                                                                                                                        |
| tokenOut           | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                                                           |                                                                                                                        |
| totalAmountIn      | VARCHAR   | 5000000000000000000000                                                                               |                                                                                                                        |
| minTotalAmountOut  | VARCHAR   | 3830210006                                                                                           |                                                                                                                        |

## 21. Table: ExchangeProxy2\_call\_multihopBatchSwapExactOut\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-11-01 16:50:51+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 11172364                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x208d324609b909934ba574cede614288dd498c4eca8603bad081d9ec4eb85520                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 71                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3e66b66fd1d0b02fda6c811da9e0547970db2f21                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| swapSequences      | VARCHAR   | 0x1B8874BaceAAfba9eA194a625d12E8b270D77016,0x0E29e5AbbB5FD88e28b2d355774e73BD47dE3bcd,0xA0b86991c621 |                                                                                                                        |
| tokenIn            | VARCHAR   | 0x0e29e5abbb5fd88e28b2d355774e73bd47de3bcd                                                           |                                                                                                                        |
| tokenOut           | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                                                           |                                                                                                                        |
| maxTotalAmountIn   | VARCHAR   | 18153748638877073520948                                                                              |                                                                                                                        |

## 22. Table: ExchangeProxy2\_call\_smartSwapExactIn\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-06-09 03:55:52+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 12598048                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xc3ac1ab0351edb155421d3b91ab9828aef5cbdd7b72f46c2f248096a940c4428 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 121                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3e66b66fd1d0b02fda6c811da9e0547970db2f21                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| tokenIn            | VARCHAR   | 0x8202346458f32ec51e96d7e214ce98fe749e182c                         |                                                                                                                        |
| tokenOut           | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                                                                                        |
| totalAmountIn      | VARCHAR   | 579693957920919263037                                              |                                                                                                                        |
| minTotalAmountOut  | VARCHAR   | 524560097                                                          |                                                                                                                        |
| nPools             | VARCHAR   | 1                                                                  |                                                                                                                        |

## 23. Table: ExchangeProxy2\_call\_smartSwapExactOut\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-02-24 12:53:39+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 11919948                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x948234eb7abc8fa10887d0c679ff713fda04c2f361ea772fcccf6ce98dbadb00 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 101                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,13                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3e66b66fd1d0b02fda6c811da9e0547970db2f21                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| tokenIn            | VARCHAR   | 0x8202346458f32ec51e96d7e214ce98fe749e182c                         |                                                                                                                        |
| tokenOut           | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                                                                                        |
| totalAmountOut     | VARCHAR   | 600000000                                                          |                                                                                                                        |
| maxTotalAmountIn   | VARCHAR   | 742327558997749977226                                              |                                                                                                                        |
| nPools             | VARCHAR   | 1                                                                  |                                                                                                                        |

## 24. Table: ExchangeProxy2\_event\_batchSwapExactIn\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-09-13 09:53:44+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 10852911                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xb6ccee068647fff79650baf5c36c171e64cfb73b2add43d8569c0299fbc73767                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 17                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3e66b66fd1d0b02fda6c811da9e0547970db2f21                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| swaps              | VARCHAR   | 0xf9ab7776C7bAEED1D65f0492fE2bB3951A1787Ef,0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2,0x2260FAC5E554 |                                                                                                                        |
| tokenIn            | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                                                           |                                                                                                                        |
| tokenOut           | VARCHAR   | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599                                                           |                                                                                                                        |
| totalAmountIn      | VARCHAR   | 26068600000000000000                                                                                 |                                                                                                                        |
| minTotalAmountOut  | VARCHAR   | 95367574                                                                                             |                                                                                                                        |

## 25. Table: ExchangeProxy2\_event\_batchSwapExactOut\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-09-12 20:04:19+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 10849201                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x51cd51897dbfa6c34bc3cd889a7ab51efead4de06ba2ef84b443d810b46b71c0                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 51                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3e66b66fd1d0b02fda6c811da9e0547970db2f21                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| swaps              | VARCHAR   | 0xf9ab7776C7bAEED1D65f0492fE2bB3951A1787Ef,0x2260FAC5E5542a773Aa44fBCfeDf7C193bc2C599,0xC02aaA39b223 |                                                                                                                        |
| tokenIn            | VARCHAR   | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599                                                           |                                                                                                                        |
| tokenOut           | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                                                           |                                                                                                                        |
| maxTotalAmountIn   | VARCHAR   | 95309440                                                                                             |                                                                                                                        |

## 26. Table: ExchangeProxy2\_event\_multihopBatchSwapExactIn\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-01-04 21:28:48+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 11590461                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xef7304cca61a89cff7d7a93d18056de7093a404748b2ec2f4c63fcf22e903bd9                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 93                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3e66b66fd1d0b02fda6c811da9e0547970db2f21                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| swapSequences      | VARCHAR   | 0x239C53350Be2B399Fe104F0E207e26dfB24164f3,0xbf70A33A13fBe8D0106Df321Da0Cf654d2E9Ab50,0x9f49ed43C90A |                                                                                                                        |
| tokenIn            | VARCHAR   | 0xbf70a33a13fbe8d0106df321da0cf654d2e9ab50                                                           |                                                                                                                        |
| tokenOut           | VARCHAR   | 0x9f49ed43c90a540d1cf12f6170ace8d0b88a14e6                                                           |                                                                                                                        |
| totalAmountIn      | VARCHAR   | 71209558590028000000                                                                                 |                                                                                                                        |
| minTotalAmountOut  | VARCHAR   | 57947859701492537313                                                                                 |                                                                                                                        |

## 27. Table: ExchangeProxy2\_event\_multihopBatchSwapExactOut\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-01-01 19:45:33+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 11570417                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xa48b0889a5ba63fdca9154cb070c055ec22316efb1bd952f146094b5cfe2a5c8                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 136                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3e66b66fd1d0b02fda6c811da9e0547970db2f21                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| swapSequences      | VARCHAR   | 0x8a649274E4d777FFC6851F13d23A86BBFA2f2Fbf,0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2,0xA0b86991c621 |                                                                                                                        |
| tokenIn            | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                                                           |                                                                                                                        |
| tokenOut           | VARCHAR   | 0x002f0b1a71c5730cf2f4da1970a889207bdb6d0d                                                           |                                                                                                                        |
| maxTotalAmountIn   | VARCHAR   | 421400520000000000                                                                                   |                                                                                                                        |

## 28. Table: ExchangeProxy2\_event\_smartSwapExactIn\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-11-29 21:03:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 11355898                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xa6a66cfcc10faa55274dd6b787ce6146c3efd65d8455e2105b85cfa10976e58e | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 77                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 1,7,0                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3e66b66fd1d0b02fda6c811da9e0547970db2f21                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| tokenIn            | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                                                                                        |
| tokenOut           | VARCHAR   | 0x9f8f72aa9304c8b593d555f12ef6589cc3a579a2                         |                                                                                                                        |
| totalAmountIn      | VARCHAR   | 7985600000000000000                                                |                                                                                                                        |
| minTotalAmountOut  | VARCHAR   | 8163814680329422101                                                |                                                                                                                        |
| nPools             | VARCHAR   | 1                                                                  |                                                                                                                        |

## 29. Table: ExchangeProxy2\_event\_smartSwapExactOut\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-01-26 06:28:48+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14079649                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x2e1753c52ef8aa66f950b2845a6d1a7a5b0c7fd16e5acddca9235c4a8502eacc | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 231                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 12,1                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3e66b66fd1d0b02fda6c811da9e0547970db2f21                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| tokenIn            | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                                                                                        |
| tokenOut           | VARCHAR   | 0xba100000625a3754423978a60c9317c58a424e3d                         |                                                                                                                        |
| totalAmountOut     | VARCHAR   | 51969325968141836833                                               |                                                                                                                        |
| maxTotalAmountIn   | VARCHAR   | 258782362900000000                                                 |                                                                                                                        |
| nPools             | VARCHAR   | 3                                                                  |                                                                                                                        |

## 30. Table: LiquidityGaugeFactory\_event\_GaugeCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-14 00:08:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15742670                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9164de2b7f489ecaf87cde995faa31746a9b7d5708ae31a01c9bf7e96d8750c7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 227                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4e7bbd911cf1efa442bc1b2e9ea01ffe785412ec                         | Address of the contract that produced the log                |
| gauge             | VARCHAR   | 0xcab1921e4fc9f4c26b877b58d9713cd19e9eadd1                         |                                                              |
| pool              | VARCHAR   | 0xe340ebfcaa544da8bb1ee9005f1a346d50ec422e                         |                                                              |

## 31. Table: LiquidityGaugeV5\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-24 16:44:35+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17330315                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa0d3e161990f596feefdaa855973f9424403bd01ce3ee7b00871b891e64c4947             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 112                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2e79d6f631177f8e7f08fbd5110e893e1b1d790a                                     | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0xeb53b5fac1e3c05ea08a5ffd5fada02dc0c13f21                                     |                                                              |
| \_spender         | VARCHAR   | 0x40aa958dd87fc8305b97f2ba922cddca374bcd7f                                     |                                                              |
| \_value           | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 32. Table: LiquidityGaugeV5\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-28 02:14:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17141596                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x32349c4c4a3fd66cad1e5debc40bca0372237d39d0d94d4c25fd9e9ba18f1f00 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 129                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x107a2209883621afe2968da31c03190e0b2782c2                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xaf52695e1bb01a16d33d7194c28c42b10e0dbec2                         |                                                              |
| value             | VARCHAR   | 97556599727437290142899                                            |                                                              |

## 33. Table: LiquidityGaugeV5\_event\_RewardDistributorUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-06 20:15:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14534397                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8a852b8fae088f9bdd6e356d57fd6a098649a3db56a686fd0e81a3aea6317f81 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 147                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcd4722b7c24c29e0413bdcd9e51404b4539d14ae                         | Address of the contract that produced the log                |
| reward\_token     | VARCHAR   | 0x5a98fcbea516cf06857215779fd812ca3bef1b32                         |                                                              |
| distributor       | VARCHAR   | 0xc38c5f97b34e175ffd35407fc91a937300e33860                         |                                                              |

## 34. Table: LiquidityGaugeV5\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-20 03:45:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17731782                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf77f48d412f92b84901c84cf56d0663bc5b08dbe6f23942a42d43cb2304596ae | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 576                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcd4722b7c24c29e0413bdcd9e51404b4539d14ae                         | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0xf82d76303f7bb791c75a8e3d7bc4fb26289ca943                         |                                                              |
| \_to              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_value           | VARCHAR   | 41008374823617414469                                               |                                                              |

## 35. Table: LiquidityGaugeV5\_event\_UpdateLiquidityLimit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-19 09:01:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14614607                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x884587376b15523a5b9c942f193c6e48dcc4101d9e4036e32a9f907363dd18aa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 190                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x31e7f53d27bfb324656facaa69fe440169522e1c                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x1eb8229c85c543c034cf6492fef3906ec2beebd1                         |                                                              |
| original\_balance | VARCHAR   | 0                                                                  |                                                              |
| original\_supply  | VARCHAR   | 33488843048424783680592                                            |                                                              |
| working\_balance  | VARCHAR   | 0                                                                  |                                                              |
| working\_supply   | VARCHAR   | 13817425879738784875585                                            |                                                              |

## 36. Table: LiquidityGaugeV5\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-04 00:31:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17838057                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcbbfda2cfe4cda1e5fede97ce517eb796d4f3b2c2ef52e7242cafb0693fa6c21 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 242                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x79ef6103a513951a3b25743db509e267685726b7                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x3bdea606effc7ba0f50ebaa2bac328dccc08d37f                         |                                                              |
| value             | VARCHAR   | 29735547854641068285                                               |                                                              |

## 37. Table: V1\_stkABPT\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-28 06:05:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17142732                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xec34b236e403b672cbd87f0caf3e47bb9243ca9449ad43766555f768cc697fd3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 271                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa1116930326d21fb917d5a27f1e9943a9595fb47                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x4c9f7207be28278b9dca129f2e211acfff48fb01                         |                                                              |
| value             | VARCHAR   | 40110994177965156454914                                            |                                                              |

## 38. Table: V2\_BalancerPoolToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-13 09:20:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17683657                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7fbfbcdcc57650d18e0be469d25314ab32cddd4604905bf57059ba0c1d2136ba | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 159                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x02d928e68d8f10c0358566152677db51e1e2dc8c                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                         |                                                              |
| to                | VARCHAR   | 0x615e85f2090599ba1df40d62c3a3488a0466c023                         |                                                              |
| value             | VARCHAR   | 34663885001669340                                                  |                                                              |

## 39. Table: V2\_BalancerPool\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-14 14:25:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14204798                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x447c46d0bad9776e1c88353016e5f1aca2530744274145fefa16653253f4938d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 277                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0f3e0c4218b7b0108a3643cfe9d3ec0d4f57c54e                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0x7265027393addfb77661ccae97d2282d58326c41                         |                                                              |

## 40. Table: V2\_BalancerPool\_event\_SwapFeePercentageChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-22 23:59:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17752100                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xce2b58f9840f766abea696bdc1705159209df3509717b711ff41d926e6a7e9c0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 145                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x08775ccb6674d6bdceb0797c364c2653ed84f384                         | Address of the contract that produced the log                |
| swapFeePercentage | VARCHAR   | 3000000000000000                                                   |                                                              |

## 41. Table: V2\_ComposableStablePoolFactory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-02 19:55:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15884558                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9aaa8644476d91b40aec7da10daf268c5679549d93ef5cc1c042ac68bb0284bb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 61                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf9ac7b9df2b3454e841110cce5550bd5ac6f875f                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0x8e85e97ed19c0fa13b2549309965291fbbc0048b                         |                                                              |

## 42. Table: V2\_ComposableStablePool\_event\_AmpUpdateStarted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-10 01:16:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15936279                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc90204e8c23e11af556e27636223bd1fa6f1a4fb251dcb08ce596b4c6c4924e3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 414                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6a9603e481fb8f2c09804ea9adab49a338855b90                         | Address of the contract that produced the log                |
| startValue        | VARCHAR   | 1000000                                                            |                                                              |
| endValue          | VARCHAR   | 20000                                                              |                                                              |
| startTime         | VARCHAR   | 1668042971                                                         |                                                              |
| endTime           | VARCHAR   | 1670616746                                                         |                                                              |

## 43. Table: V2\_ComposableStablePool\_event\_AmpUpdateStopped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-23 16:31:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16033908                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe0c3cefb53ee1d64bd1fa75b73f92f0e2fa4f7f403143ae870ca59dddf748fcb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 215                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4edcb2b46377530bc18bb4d2c7fe46a992c73e10                         | Address of the contract that produced the log                |
| currentValue      | VARCHAR   | 50000                                                              |                                                              |

## 44. Table: V2\_ComposableStablePool\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-06 03:03:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16766525                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf56948d0ed9a80425cd2b3f99eb41e140ff595daf925abe14283509df3fc9d0c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 31                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa13a9247ea42d743238089903570127dda72fe44                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x000000000dfde7deaf24138722987c9a6991e2d4                         |                                                              |
| spender           | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 45. Table: V2\_ComposableStablePool\_event\_PausedStateChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| paused            | VARCHAR   |                                                              |             |

## 46. Table: V2\_ComposableStablePool\_event\_ProtocolFeePercentageCacheUpdated\_history

| Column                | Type      | Example                                                            | Description                                                  |
| --------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp      | TIMESTAMP | 2022-11-21 22:08:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number         | INTEGER   | 16021271                                                           | The block number where this event was emitted                |
| transaction\_hash     | VARCHAR   | 0xa46ab001ffb9449792d5b959e8c973168a812cbe70fc30ae8f08a14cc9275fd9 | Hash of the transactions in which this event was emitted     |
| log\_index            | INTEGER   | 346                                                                | Integer of the log index position in the block of this event |
| contract\_address     | VARCHAR   | 0x81b7f92c7b7d9349b989b4982588761bfa1aa627                         | Address of the contract that produced the log                |
| feeType               | VARCHAR   | 0                                                                  |                                                              |
| protocolFeePercentage | VARCHAR   | 500000000000000000                                                 |                                                              |

## 47. Table: V2\_ComposableStablePool\_event\_RecoveryModeStateChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-06 13:15:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16347980                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7a0c40b4a2b88deee5c04de5969d58a33dd0dffbff41d617c4b8166bda7fd03d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 286                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6a9603e481fb8f2c09804ea9adab49a338855b90                         | Address of the contract that produced the log                |
| enabled           | VARCHAR   | true                                                               |                                                              |

## 48. Table: V2\_ComposableStablePool\_event\_SwapFeePercentageChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-13 23:34:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16179085                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x166f0ad6755208600fad3108c34cd93e0c02c4df87d82d5429c29c30d19bdd2d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 35                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4c8d2e60863e8d7e1033eda2b3d84e92a6418020                         | Address of the contract that produced the log                |
| swapFeePercentage | VARCHAR   | 300000000000000                                                    |                                                              |

## 49. Table: V2\_ComposableStablePool\_event\_TokenRateCacheUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-02 05:04:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17390875                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7d18ed76950fe9ee4da7aeb1d7d6a586659614d787315bb71d98b768944cacdf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 268                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa13a9247ea42d743238089903570127dda72fe44                         | Address of the contract that produced the log                |
| tokenIndex        | VARCHAR   | 1                                                                  |                                                              |
| rate              | VARCHAR   | 1003457699777235956                                                |                                                              |

## 50. Table: V2\_ComposableStablePool\_event\_TokenRateProviderSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-11 21:44:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15949535                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x827f4e913a4f235ebc57b08739dc52864ca7211e1ecbd8ea3a03d6ff066c992d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 301                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbd482ffb3e6e50dc1c437557c3bea2b68f3683ee                         | Address of the contract that produced the log                |
| tokenIndex        | VARCHAR   | 4                                                                  |                                                              |
| provider          | VARCHAR   | 0xf8bbc8c2ced9c24992b6ec9bbd0eddaf3bce70eb                         |                                                              |
| cacheDuration     | VARCHAR   | 0                                                                  |                                                              |

## 51. Table: V2\_ComposableStablePool\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-04 07:12:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17840055                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa810b74ed6399a8ef3204574d36f834dab23862beae4de373a2d6c47332cba2f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 237                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa13a9247ea42d743238089903570127dda72fe44                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x62d7d772b2d909a0779d15299f4fc87e34513c6d                         |                                                              |
| to                | VARCHAR   | 0x0039e762ecd8e8f074e93575dc395abfce4ef8b6                         |                                                              |
| value             | VARCHAR   | 7762171959911777436                                                |                                                              |

## 52. Table: V2\_InvestmentPoolFactory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-15 05:29:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13618508                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xeb09dc88310030df2b1222b5014827808bf23ee733fbd8884c18bef374d5af53 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 265                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x48767f9f868a4a7b86a90736632f6e44c2df7fa9                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0x3b40d7d5ae25df2561944dd68b252016c4c7b280                         |                                                              |

## 53. Table: V2\_InvestmentPool\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-19 13:01:42+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14417017                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x47be508404863d3916a91aa33355e11779f8de1081ad065799239b6316df2cba             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 68                                                                             | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xccf5575570fac94cec733a58ff91bb3d073085c7                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x3cc1a943b27c2af7c6dcf3be0137f66c2f22e712                                     |                                                              |
| spender           | VARCHAR   | 0xb2be281e8b11b47fec825973fc8bb95332022a54                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 54. Table: V2\_InvestmentPool\_event\_GradualWeightUpdateScheduled\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-15 05:29:09+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13618508                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xeb09dc88310030df2b1222b5014827808bf23ee733fbd8884c18bef374d5af53                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 262                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3b40d7d5ae25df2561944dd68b252016c4c7b280                                                           | Address of the contract that produced the log                |
| startTime         | VARCHAR   | 1636954149                                                                                           |                                                              |
| endTime           | VARCHAR   | 1636954149                                                                                           |                                                              |
| startWeights      | VARCHAR   | 250000000000000000,64900000000000000,182500000000000000,93200000000000000,75200000000000000,59600000 |                                                              |
| endWeights        | VARCHAR   | 250000000000000000,64900000000000000,182500000000000000,93200000000000000,75200000000000000,59600000 |                                                              |

## 55. Table: V2\_InvestmentPool\_event\_ManagementFeePercentageChanged\_history

| Column                  | Type      | Example                                                            | Description                                                  |
| ----------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp        | TIMESTAMP | 2021-10-25 13:15:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number           | INTEGER   | 13486828                                                           | The block number where this event was emitted                |
| transaction\_hash       | VARCHAR   | 0x6a20dde2b73657e4e583f7da7a3ddd65513e768097fc4e88634588852f6958b8 | Hash of the transactions in which this event was emitted     |
| log\_index              | INTEGER   | 27                                                                 | Integer of the log index position in the block of this event |
| contract\_address       | VARCHAR   | 0xccf5575570fac94cec733a58ff91bb3d073085c7                         | Address of the contract that produced the log                |
| managementFeePercentage | VARCHAR   | 0                                                                  |                                                              |

## 56. Table: V2\_InvestmentPool\_event\_ManagementFeesCollected\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| tokens            | VARCHAR   |                                                              |             |
| amounts           | VARCHAR   |                                                              |             |

## 57. Table: V2\_InvestmentPool\_event\_PausedStateChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| paused            | VARCHAR   |                                                              |             |

## 58. Table: V2\_InvestmentPool\_event\_SwapEnabledSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-27 08:35:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13306765                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa9dfbac2dc39604fcd1444f05d9b39c890a83e2c43036cbb45355216e3b3fa35 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 136                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe7b1d394f3b40abeaa0b64a545dbcf89da1ecb3f                         | Address of the contract that produced the log                |
| swapEnabled       | VARCHAR   | true                                                               |                                                              |

## 59. Table: V2\_InvestmentPool\_event\_SwapFeePercentageChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-23 02:33:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13279333                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x028236d35ebd2ee9482831963751b3f9633b8b0956f45c02a6abfb14e648df9e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 158                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe7b1d394f3b40abeaa0b64a545dbcf89da1ecb3f                         | Address of the contract that produced the log                |
| swapFeePercentage | VARCHAR   | 5000000000000000                                                   |                                                              |

## 60. Table: V2\_InvestmentPool\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-22 00:51:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16879681                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4b58ba9e069db94d375034ee492f568e0628d63ddb739819435c4e0bb0bcd37f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 614                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xccf5575570fac94cec733a58ff91bb3d073085c7                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xdef7efa38e81c2500190b5290eadb5c83a168ae2                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 37174775715550356488                                               |                                                              |

## 61. Table: V2\_LiquidityBootstrappingPoolFactory\_call\_create\_history

| Column             | Type      | Example                                                                               | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-11-24 17:47:58+00:00                                                             | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 13678594                                                                              | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x3e9c3e50c6cbf1a12085eee5003b09622f46d3e5987f62be77dd84e02aaac624                    | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 109                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x751a0bc0e3f75b38e01cf25bfce7ff36de1c87de                                            | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                     | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                  | Error in case input parsing failed                                                                                     |
| name               | VARCHAR   | c0 Copper Launch                                                                      |                                                                                                                        |
| symbol             | VARCHAR   | c0\_TLA                                                                               |                                                                                                                        |
| tokens             | VARCHAR   | 0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48,0xBb3c2A170FbB8988cDB41c04344F9863b0f71C20 |                                                                                                                        |
| weights            | VARCHAR   | 10000000000000000,990000000000000000                                                  |                                                                                                                        |
| swapFeePercentage  | VARCHAR   | 20000000000000000                                                                     |                                                                                                                        |
| owner              | VARCHAR   | 0x14f705321a201f4f0a0f0ff36d4fe83d37543334                                            |                                                                                                                        |
| swapEnabledOnStart | VARCHAR   | false                                                                                 |                                                                                                                        |

## 62. Table: V2\_LiquidityBootstrappingPoolFactory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-13 03:19:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13407625                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6fcf0e35541ad8945afdaf73cc096e03c604d943c5b3557f0320530d898a8119 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 214                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x751a0bc0e3f75b38e01cf25bfce7ff36de1c87de                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0xc772e7135a3e32a87e148a4f2f5f7493de0a68e7                         |                                                              |

## 63. Table: V2\_LiquidityBootstrappingPool\_event\_GradualWeightUpdateScheduled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-12 02:57:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13787773                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x644daffa9f6e1c26f11991b647770f569da935b7c19efc25689573b567d1d143 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 455                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x38ff18c8322b675aefc74a5cdd7c8c0c461b97df                         | Address of the contract that produced the log                |
| startTime         | VARCHAR   | 1639278001                                                         |                                                              |
| endTime           | VARCHAR   | 1639288800                                                         |                                                              |
| startWeights      | VARCHAR   | 50003814755474175,950011444266422523                               |                                                              |
| endWeights        | VARCHAR   | 500000000000000000,500000000000000000                              |                                                              |

## 64. Table: V2\_LiquidityBootstrappingPool\_event\_PausedStateChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| paused            | VARCHAR   |                                                              |             |

## 65. Table: V2\_LiquidityBootstrappingPool\_event\_SwapEnabledSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-11 01:04:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13591877                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3e44f7e134320ed681d494767fd41ac96231b3e3603194cd74fbb7fb5019a937 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 107                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xede4efcc5492cf41ed3f0109d60bc0543cfad23a                         | Address of the contract that produced the log                |
| swapEnabled       | VARCHAR   | true                                                               |                                                              |

## 66. Table: V2\_LiquidityBootstrappingPool\_event\_SwapFeePercentageChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-13 03:19:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13407625                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6fcf0e35541ad8945afdaf73cc096e03c604d943c5b3557f0320530d898a8119 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 209                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc772e7135a3e32a87e148a4f2f5f7493de0a68e7                         | Address of the contract that produced the log                |
| swapFeePercentage | VARCHAR   | 15000000000000000                                                  |                                                              |

## 67. Table: V2\_LiquidityBootstrappingPool\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-11 18:28:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13596516                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x38cca437af17e6fdff7bf4b50370c9100af9595ab73e710137d46e3a97cb7cee | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 203                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe5769603af1c9ec809dd5cfbc7fee36e7f09a3e6                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 1000000                                                            |                                                              |

## 68. Table: V2\_MetaStablePoolFactory\_call\_create\_history

| Column                 | Type      | Example                                                                               | Description                                                                                                            |
| ---------------------- | --------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp       | TIMESTAMP | 2023-01-26 17:28:47+00:00                                                             | Timestamp of the block where this event was emitted                                                                    |
| block\_number          | INTEGER   | 16492486                                                                              | The block number where this event was emitted                                                                          |
| transaction\_hash      | VARCHAR   | 0x5f79c73333e8a1e83fbd6773d582323b04a8d894f582c0bf165629c04df59954                    | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index     | INTEGER   | 172                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address         | VARCHAR   | None                                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address            | VARCHAR   | 0x67d27634e44793fe63c467035e31ea8635117cd4                                            | Address of the called contract                                                                                         |
| status                 | INTEGER   | 1                                                                                     | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                  | VARCHAR   | None                                                                                  | Error in case input parsing failed                                                                                     |
| name                   | VARCHAR   | Balancer ankrETH-WETH Stable Pool                                                     |                                                                                                                        |
| symbol                 | VARCHAR   | B-ankrETH-WETH-Stable                                                                 |                                                                                                                        |
| tokens                 | VARCHAR   | 0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2,0xE95A203B1a91a908F9B9CE46459d101078c2c3cb |                                                                                                                        |
| amplificationParameter | VARCHAR   | 50                                                                                    |                                                                                                                        |
| rateProviders          | VARCHAR   | 0x0000000000000000000000000000000000000000,0x00F8e64a8651E3479A0B20F46b1D462Fe29D6aBc |                                                                                                                        |
| priceRateCacheDuration | VARCHAR   | 10,10                                                                                 |                                                                                                                        |
| swapFeePercentage      | VARCHAR   | 400000000000000                                                                       |                                                                                                                        |
| oracleEnabled          | VARCHAR   | true                                                                                  |                                                                                                                        |
| owner                  | VARCHAR   | 0x0000000000000000000000000000000000000000                                            |                                                                                                                        |

## 69. Table: V2\_MetaStablePoolFactory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-26 17:28:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16492486                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5f79c73333e8a1e83fbd6773d582323b04a8d894f582c0bf165629c04df59954 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 501                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x67d27634e44793fe63c467035e31ea8635117cd4                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0x8a34b5ad76f528bfec06c80d85ef3b53da7fc300                         |                                                              |

## 70. Table: V2\_MetaStablePool\_event\_AmpUpdateStarted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-30 03:21:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16516921                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaf144f95cacab76a479cf1aa91b2ed73ea3dc62c83f1f7620deb61cd26f7f5f9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 277                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb08885e6026bab4333a80024ec25a1a3e1ff2b8a                         | Address of the contract that produced the log                |
| startValue        | VARCHAR   | 50000                                                              |                                                              |
| endValue          | VARCHAR   | 50000                                                              |                                                              |
| startTime         | VARCHAR   | 1675048919                                                         |                                                              |
| endTime           | VARCHAR   | 1675048919                                                         |                                                              |

## 71. Table: V2\_MetaStablePool\_event\_AmpUpdateStopped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-11 01:11:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16380201                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1a5e9ee7e681dc038fa10c0b537b5aaf8d254fc95cb50c6d7efdc5ccbf02f1ed | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 134                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x063c624672e390363b25f0c6c68ad9067c34595b                         | Address of the contract that produced the log                |
| currentValue      | VARCHAR   | 50000                                                              |                                                              |

## 72. Table: V2\_MetaStablePool\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-30 21:27:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17808523                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x30b004d211769a392426f5aa897e0a10461b24ff814de802f397c16c5372d681 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 137                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb08885e6026bab4333a80024ec25a1a3e1ff2b8a                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x01eeb74efd231e138711bdc2b8aab6dd0f960eba                         |                                                              |
| spender           | VARCHAR   | 0x10a361766e64d7983a97202ac3a0f4cee06eb717                         |                                                              |
| value             | VARCHAR   | 164129019134120036795                                              |                                                              |

## 73. Table: V2\_MetaStablePool\_event\_OracleEnabledChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-21 03:28:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13846138                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2ddc1b117643237193538e5d0fd4c9f565565532a7a85670e6aa42023f44bd68 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 160                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1e19cf2d73a72ef1332c882f20534b6519be0276                         | Address of the contract that produced the log                |
| enabled           | VARCHAR   | true                                                               |                                                              |

## 74. Table: V2\_MetaStablePool\_event\_PausedStateChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| paused            | VARCHAR   |                                                              |             |

## 75. Table: V2\_MetaStablePool\_event\_PriceRateCacheUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-03 10:12:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17833797                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x00c7493a2f98383999f242cdfdb665c162f0fc6874734c6b13e074b629a7dcd7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 319                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9c6d47ff73e0f5e51be5fd53236e3f595c5793f2                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0xbe9895146f7af43049ca1c1ae358b0541ea49704                         |                                                              |
| rate              | VARCHAR   | 1045458304229002964                                                |                                                              |

## 76. Table: V2\_MetaStablePool\_event\_PriceRateProviderSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-30 03:21:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16516921                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaf144f95cacab76a479cf1aa91b2ed73ea3dc62c83f1f7620deb61cd26f7f5f9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 281                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb08885e6026bab4333a80024ec25a1a3e1ff2b8a                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| provider          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| cacheDuration     | VARCHAR   | 10                                                                 |                                                              |

## 77. Table: V2\_MetaStablePool\_event\_SwapFeePercentageChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-21 03:28:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13846138                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2ddc1b117643237193538e5d0fd4c9f565565532a7a85670e6aa42023f44bd68 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 152                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1e19cf2d73a72ef1332c882f20534b6519be0276                         | Address of the contract that produced the log                |
| swapFeePercentage | VARCHAR   | 400000000000000                                                    |                                                              |

## 78. Table: V2\_MetaStablePool\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-11 11:19:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17236771                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc8786501d77ef97773c1f141cf8dd84f52fbf23056a6a4199c25e722538a935c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 449                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x32296969ef14eb0c6d29669c550d4a0449130230                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x8267fdabd1b8c8645138f2de5b0fe24988dc9820                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 9076159388533954388                                                |                                                              |

## 79. Table: V2\_ProtocolFeesCollector\_call\_getFlashLoanFeePercentage\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-07-19 08:22:23+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17726019                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xf7a3af20006c617b4dfd487287046c5c2e1e2765943e3d1feeaa7f542d496404 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 1                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 1                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xce88686553686da562ce7cea497ce749da109f9f                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 80. Table: V2\_ProtocolFeesCollector\_call\_getSwapFeePercentage\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-07-19 20:27:23+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17729611                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xb6798e94565365a71125fe5648feb4be889724ea725740fd678fb29e8a9dff3d | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 111                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xce88686553686da562ce7cea497ce749da109f9f                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 81. Table: V2\_ProtocolFeesCollector\_call\_setSwapFeePercentage\_history

| Column               | Type      | Example                                                            | Description                                                                                                            |
| -------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp     | TIMESTAMP | 2022-01-03 14:07:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number        | INTEGER   | 13932914                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash    | VARCHAR   | 0x8e8005b4262bbe3dc128545956eba25af6de8cc1aa7da5d102f6d8d6f2b1b6c2 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index   | INTEGER   | 259                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address       | VARCHAR   | 0,0                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address          | VARCHAR   | 0xce88686553686da562ce7cea497ce749da109f9f                         | Address of the called contract                                                                                         |
| status               | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| newSwapFeePercentage | VARCHAR   | 100000000000000000                                                 |                                                                                                                        |

## 82. Table: V2\_ProtocolFeesCollector\_event\_SwapFeePercentageChanged\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2022-02-21 15:08:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 14250148                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xc421ff8642bdeb12dd0776015e1e7bcaa6c7430970c9079a14f2c2463d22c437 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 170                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0xce88686553686da562ce7cea497ce749da109f9f                         | Address of the contract that produced the log                |
| newSwapFeePercentage | VARCHAR   | 500000000000000000                                                 |                                                              |

## 83. Table: V2\_StablePoolFactory\_call\_create\_history

| Column             | Type      | Example                                                                               | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-06-09 11:46:04+00:00                                                             | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14932410                                                                              | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x03753e27f36e795aa2b8ae5ea2c2eff6641e3afbd42f6eda3a7e95be97bcfb57                    | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 45                                                                                    | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xc66ba2b6595d3613ccab350c886ace23866ede24                                            | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                     | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                  | Error in case input parsing failed                                                                                     |
| name               | VARCHAR   | Balancer auraBAL Stable Pool                                                          |                                                                                                                        |
| symbol             | VARCHAR   | B-auraBAL-STABLE                                                                      |                                                                                                                        |
| tokens             | VARCHAR   | 0x5c6Ee304399DBdB9C8Ef030aB642B10820DB8F56,0x616e8BfA43F920657B3497DBf40D6b1A02D4608d |                                                                                                                        |
| weights            | VARCHAR   | None                                                                                  |                                                                                                                        |
| swapFeePercentage  | VARCHAR   | 6000000000000000                                                                      |                                                                                                                        |
| owner              | VARCHAR   | 0xfc78f8e1af80a3bf5a1783bb59ed2d1b10f78ca9                                            |                                                                                                                        |

## 84. Table: V2\_StablePoolFactory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-07 12:57:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12780413                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xce92e7063121c0f34280b1fc2599dfca4a7acd4798ed4affb039c5021ab1f8a6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 274                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc66ba2b6595d3613ccab350c886ace23866ede24                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0xfeadd389a5c427952d8fdb8057d6c8ba1156cc56                         |                                                              |

## 85. Table: V2\_StablePool\_event\_AmpUpdateStarted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-09 11:46:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14932410                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x03753e27f36e795aa2b8ae5ea2c2eff6641e3afbd42f6eda3a7e95be97bcfb57 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 148                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6641a8c1d33bd3dec8dd85e69c63cafb5bf36388                         | Address of the contract that produced the log                |
| startValue        | VARCHAR   | 25000                                                              |                                                              |
| endValue          | VARCHAR   | 25000                                                              |                                                              |
| startTime         | VARCHAR   | 1654775164                                                         |                                                              |
| endTime           | VARCHAR   | 1654775164                                                         |                                                              |

## 86. Table: V2\_StablePool\_event\_AmpUpdateStopped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-13 03:00:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12816304                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf47d270a921ec0ec283d8e93511ad019d14eebf2d365e1d350d5ad1adb538c5a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 153                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9f19a375709baf0e8e35c2c5c65aca676c4c7191                         | Address of the contract that produced the log                |
| currentValue      | VARCHAR   | 200000                                                             |                                                              |

## 87. Table: V2\_StablePool\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-18 23:24:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15169528                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x64621cd6c111900e3242821b7cc660af2a25b5c376326fc6071ac2f6df2f9126 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 165                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x06df3b2bbb68adc8b0e302443692037ed9f91b42                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x82bd19e6306635ca9f7781bc63828a3d6fd3dd27                         |                                                              |
| spender           | VARCHAR   | 0x34f33cdaed8ba0e1ceece80e5f4a73bcf234cfac                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 88. Table: V2\_StablePool\_event\_PausedStateChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| paused            | VARCHAR   |                                                              |             |

## 89. Table: V2\_StablePool\_event\_SwapFeePercentageChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-18 22:05:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13641892                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x25a26f4209c495c5485aa26b6ea6377d947b12f8ef1f60dddef755ce33667397 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 290                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfeadd389a5c427952d8fdb8057d6c8ba1156cc56                         | Address of the contract that produced the log                |
| swapFeePercentage | VARCHAR   | 200000000000000                                                    |                                                              |

## 90. Table: V2\_StablePool\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-13 04:54:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14575202                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x69c13312a8068a6bbf87e3835ce693599ae677d7a511bd4bccd05d1875e97d02 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 501                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x06df3b2bbb68adc8b0e302443692037ed9f91b42                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x3a9efa46a461f052d835fa5272220c345cb561d6                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 9872225153506900771423                                             |                                                              |

## 91. Table: V2\_Vault\_call\_batchSwap\_history

| Column             | Type      | Example                                                                                           | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-02-04 13:56:55+00:00                                                                         | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14139921                                                                                          | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x2cc45c9879a101378d05c5085630f606620ef426d3156a16aa6b6f6758074a6c                                | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 126                                                                                               | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                                                        | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                 | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                              | Error in case input parsing failed                                                                                     |
| kind               | VARCHAR   | 1                                                                                                 |                                                                                                                        |
| swaps              | VARCHAR   |                                                                                                   |                                                                                                                        |
| assets             | VARCHAR   |                                                                                                   |                                                                                                                        |
| funds              | VARCHAR   | 0xf3aFc2383a0B45ae73D77B49dF7F2184B1Ad4B90,false,0xf3aFc2383a0B45ae73D77B49dF7F2184B1Ad4B90,false |                                                                                                                        |
| limits             | VARCHAR   |                                                                                                   |                                                                                                                        |
| deadline           | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935                    |                                                                                                                        |

## 92. Table: V2\_Vault\_call\_swap\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-01-03 19:43:35+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16328423                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x0654653c6eab6cabea3d5c411c579db9f68036678fb47d711349b68054289d2a                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 1                                                                                                    | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,2,0,1                                                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| singleSwap         | VARCHAR   | 0x1e19cf2d73a72ef1332c882f20534b6519be0276000200000000000000000112,0,0xae78736Cd615f374D3085123A2104 |                                                                                                                        |
| funds              | VARCHAR   | 0x00000000000747D525E898424E8774F7Eb317d00,false,0x00000000000747D525E898424E8774F7Eb317d00,false    |                                                                                                                        |
| limit              | VARCHAR   | 0                                                                                                    |                                                                                                                        |
| deadline           | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639934                       |                                                                                                                        |

## 93. Table: V2\_Vault\_event\_AuthorizerChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-19 18:36:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12272146                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x28c44bb10d469cbd42accf97bd00b73eabbace138e9d44593e851231fbed1cb7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                         | Address of the contract that produced the log                |
| newAuthorizer     | VARCHAR   | 0xa331d84ec860bf466b4cdccfb4ac09a1b43f3ae6                         |                                                              |

## 94. Table: V2\_Vault\_event\_ExternalBalanceTransfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-27 23:56:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17787822                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x76012bf544cc409915595fdb146046ef7f80837999d7e2608b63934f3ea5806e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 61                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x02d928e68d8f10c0358566152677db51e1e2dc8c                         |                                                              |
| sender            | VARCHAR   | 0x9ad82cf8411e352cdd771febe5f60cb4293a1077                         |                                                              |
| recipient         | VARCHAR   | 0x9008d19f58aabd9ed0d60971565aa8510560ab41                         |                                                              |
| amount            | VARCHAR   | 503185097359594295                                                 |                                                              |

## 95. Table: V2\_Vault\_event\_FlashLoan\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-04 01:26:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16108158                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe110e826b43228a1303dcc8e3d41ae0e7cd4a15c7cd800c613d4656f0ae97ad6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 37                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                         | Address of the contract that produced the log                |
| recipient         | VARCHAR   | 0x2b98ffef9e8477830d96e70efcfe0460349fe923                         |                                                              |
| token             | VARCHAR   | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599                         |                                                              |
| amount            | VARCHAR   | 500000000                                                          |                                                              |
| feeAmount         | VARCHAR   | 0                                                                  |                                                              |

## 96. Table: V2\_Vault\_event\_InternalBalanceChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-10 04:04:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17660775                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4eeecb237f76d67e03644be471f444a2b0eaed64f65e656bd5b9cfd8623d194d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 220                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x000000000dfde7deaf24138722987c9a6991e2d4                         |                                                              |
| token             | VARCHAR   | 0x5a98fcbea516cf06857215779fd812ca3bef1b32                         |                                                              |
| delta             | VARCHAR   | 0                                                                  |                                                              |

## 97. Table: V2\_Vault\_event\_PausedStateChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| paused            | VARCHAR   |                                                              |             |

## 98. Table: V2\_Vault\_event\_PoolBalanceChanged\_history

| Column             | Type      | Example                                                                               | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2023-05-13 00:54:23+00:00                                                             | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 17247641                                                                              | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x070b96527ec56f04a8df35906512c6feb5f09e68f54cb4fd9c7ce474fe4fcfe3                    | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 315                                                                                   | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                                            | Address of the contract that produced the log                |
| poolId             | VARCHAR   | 0xa3c500969accb3d8df08cba313c120818fe0ed9d000200000000000000000471                    |                                                              |
| liquidityProvider  | VARCHAR   | 0x1e3c382f6bf183244abb21020de45ac736d15d57                                            |                                                              |
| tokens             | VARCHAR   | 0x0f2D719407FdBeFF09D87557AbB7232601FD9F29,0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2 |                                                              |
| deltas             | VARCHAR   | 3063618154595821418809,1020000000000000000                                            |                                                              |
| protocolFeeAmounts | VARCHAR   | 51379856735523031984,0                                                                |                                                              |

## 99. Table: V2\_Vault\_event\_PoolBalanceManaged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-04 14:01:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17621022                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2504eac7cd9dbaf09df553bf50c76b2a453b0fa16cd39f36e2e502924f1824a6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 335                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                         | Address of the contract that produced the log                |
| poolId            | VARCHAR   | 0x159cb00338fb63f263fd6f621df619cef71da9540000000000000000000004d5 |                                                              |
| assetManager      | VARCHAR   | 0xcff3f04af1b2c4f81e8d84a1b7399fc2203ffaa6                         |                                                              |
| token             | VARCHAR   | 0xa5269a8e31b93ff27b887b56720a25f844db0529                         |                                                              |
| cashDelta         | VARCHAR   | 0                                                                  |                                                              |
| managedDelta      | VARCHAR   | -19523789478707355569286                                           |                                                              |

## 100. Table: V2\_Vault\_event\_PoolRegistered\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-20 02:00:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17731262                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x236c8d25d4782e7f49db6b334de7a73a483d114d4b7d1a5b2182323dfca3b502 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 171                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                         | Address of the contract that produced the log                |
| poolId            | VARCHAR   | 0xe2d16b0a39f3fbb4389a0e8f1efcbecfb3d1e6e10000000000000000000005a7 |                                                              |
| poolAddress       | VARCHAR   | 0xe2d16b0a39f3fbb4389a0e8f1efcbecfb3d1e6e1                         |                                                              |
| specialization    | VARCHAR   | 0                                                                  |                                                              |

## 101. Table: V2\_Vault\_event\_RelayerApprovalChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-23 08:27:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17320746                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2f8863bb854847b4440f96a614cb1f4129579fc1e0c758db33729b8cab926707 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 301                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                         | Address of the contract that produced the log                |
| relayer           | VARCHAR   | 0xc92e8bdf79f0507f65a392b0ab4667716bfe0110                         |                                                              |
| sender            | VARCHAR   | 0x3eca88b18f86c6910066256f47a051b15b84d57b                         |                                                              |
| approved          | VARCHAR   | true                                                               |                                                              |

## 102. Table: V2\_Vault\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-29 11:07:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16290012                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5fad7214cd0200df2b2678419b35d061279a3f7842d799b334a4c2136445add1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 22                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                         | Address of the contract that produced the log                |
| poolId            | VARCHAR   | 0x6df50e37a6aefb9024a7284ef1c9e1e8e7c4f7b80001000000000000000002e7 |                                                              |
| tokenIn           | VARCHAR   | 0x5a98fcbea516cf06857215779fd812ca3bef1b32                         |                                                              |
| tokenOut          | VARCHAR   | 0x1f9840a85d5af5bf1d1762f925bdaddc4201f984                         |                                                              |
| amountIn          | VARCHAR   | 825949832802042182361                                              |                                                              |
| amountOut         | VARCHAR   | 154654312881528665733                                              |                                                              |

## 103. Table: V2\_Vault\_event\_TokensDeregistered\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| poolId            | VARCHAR   |                                                              |             |
| tokens            | VARCHAR   |                                                              |             |

## 104. Table: V2\_Vault\_event\_TokensRegistered\_history

| Column            | Type      | Example                                                                               | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-09 08:49:42+00:00                                                             | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15307021                                                                              | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x975bb47b3b756643e46af2b3acfaa610371166ce89915838380656d8a64f5930                    | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 210                                                                                   | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                                            | Address of the contract that produced the log                |
| poolId            | VARCHAR   | 0x0947592314bf2bd0f86a74299bc8e534e3c7313f000200000000000000000312                    |                                                              |
| tokens            | VARCHAR   | 0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2,0xf5f06fFa53Ad7F5914F493F16E57B56C8dd2eA80 |                                                              |
| assetManagers     | VARCHAR   | 0x0000000000000000000000000000000000000000,0x0000000000000000000000000000000000000000 |                                                              |

## 105. Table: V2\_WeightedPool2TokensFactory\_call\_create\_history

| Column             | Type      | Example                                                                               | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-11-15 17:40:20+00:00                                                             | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 13621673                                                                              | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x2fc5d90bdba2dd008f7af03f8ce4f215b4ecd7bd9ad669c49035f7f3b260a256                    | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 116                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xa5bf2ddf098bb0ef6d120c98217dd6b141c74ee0                                            | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                     | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                  | Error in case input parsing failed                                                                                     |
| name               | VARCHAR   | ⚗️ Weighted Pool                                                                      |                                                                                                                        |
| symbol             | VARCHAR   | ⚗️\_WEIGHTED                                                                          |                                                                                                                        |
| tokens             | VARCHAR   | 0x88ACDd2a6425c3FaAE4Bc9650Fd7E27e0Bebb7aB,0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2 |                                                                                                                        |
| weights            | VARCHAR   | 800000000000000000,200000000000000000                                                 |                                                                                                                        |
| swapFeePercentage  | VARCHAR   | 10000000000000000                                                                     |                                                                                                                        |
| oracleEnabled      | VARCHAR   | false                                                                                 |                                                                                                                        |
| owner              | VARCHAR   | 0x6480bc106f5a0b13d15f5c3acb97fa9945b34508                                            |                                                                                                                        |

## 106. Table: V2\_WeightedPool2TokensFactory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-15 11:29:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13230041                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8f8a78ba51675ae8a7a22f8eb60ec39233e1c430d06f0642daa77125ad28bc32 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 545                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa5bf2ddf098bb0ef6d120c98217dd6b141c74ee0                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0x56b2811bf75bb258d2234af4f43b479bb55c3b46                         |                                                              |

## 107. Table: V2\_WeightedPool2Tokens\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-20 13:05:55+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14996712                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x21fa343c991928c6ad0262a4fea7c73ee3ccd571cb13753e4ee4e7c7f9f45204             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 472                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe99481dc77691d8e2456e5f3f61c1810adfc1503                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x0c32000a6aac193a0c49dd8643bb412c8e8f8c33                                     |                                                              |
| spender           | VARCHAR   | 0x31e7f53d27bfb324656facaa69fe440169522e1c                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 108. Table: V2\_WeightedPool2Tokens\_event\_PausedStateChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| paused            | VARCHAR   |                                                              |             |

## 109. Table: V2\_WeightedPool2Tokens\_event\_SwapFeePercentageChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-05 23:59:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12377374                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x143f2f2b20b07f7b37143543f7271e4c3e069b7af5ed173a93225e97af12a0c5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 136                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x14bf727f67aa294ec36347bd95aba1a2c136fe7a                         | Address of the contract that produced the log                |
| swapFeePercentage | VARCHAR   | 1000000000000000                                                   |                                                              |

## 110. Table: V2\_WeightedPool2Tokens\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-19 14:38:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17727877                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x638a55dc5295a2f568c7b5893a2c35c448c8868c3bea92a63c6f8fa9cabee229 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 353                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5c6ee304399dbdb9c8ef030ab642b10820db8f56                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x38ec31504f48c7e944567904d519f4059be73387                         |                                                              |
| to                | VARCHAR   | 0x9008d19f58aabd9ed0d60971565aa8510560ab41                         |                                                              |
| value             | VARCHAR   | 1500000000000000000000                                             |                                                              |

## 111. Table: V2\_WeightedPoolFactory\_call\_create\_history

| Column             | Type      | Example                                                                               | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-04-21 22:29:49+00:00                                                             | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 12286276                                                                              | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xcaeab57c348095d8d29a096d94207c3476abc8213825541aa3564cb10583288a                    | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 195                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x8e9aa87e45e92bad84d5f8dd1bff34fb92637de9                                            | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                     | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                  | Error in case input parsing failed                                                                                     |
| name               | VARCHAR   | Balancer 50 WBTC 50 WETH                                                              |                                                                                                                        |
| symbol             | VARCHAR   | B-50WBTC-50WETH                                                                       |                                                                                                                        |
| tokens             | VARCHAR   | 0x2260FAC5E5542a773Aa44fBCfeDf7C193bc2C599,0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2 |                                                                                                                        |
| weights            | VARCHAR   | 500000000000000000,500000000000000000                                                 |                                                                                                                        |
| swapFeePercentage  | VARCHAR   | 4000000000000000                                                                      |                                                                                                                        |
| owner              | VARCHAR   | 0xe4a8ed6c1d8d048bd29a00946bfcf2db10e7923b                                            |                                                                                                                        |

## 112. Table: V2\_WeightedPoolFactory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-03 06:06:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15067826                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd802bc7c98491f2f549f6cfa49561c6bd8e953dda4707c18856dfbeb9101c5db | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 314                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8e9aa87e45e92bad84d5f8dd1bff34fb92637de9                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0x12ede10c2737fdb261387192062d3c69872ec86d                         |                                                              |

## 113. Table: V2\_WeightedPool\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-03 01:08:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17831098                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x911dae84f815165083de512ddfaa455562f2e10d48751288a4fc645e968b523d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 150                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd4f79ca0ac83192693bce4699d0c10c66aa6cf0f                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x1b79e36b553c711a5293ffe9a8ce1203911445ea                         |                                                              |
| spender           | VARCHAR   | 0xa57b8d98dae62b26ec3bcc4a365338157060b234                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 114. Table: V2\_WeightedPool\_event\_PausedStateChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| paused            | VARCHAR   |                                                              |             |

## 115. Table: V2\_WeightedPool\_event\_SwapFeePercentageChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-21 22:52:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12286393                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb7a7fde2d07cc4e1d535f2223c82c8562d3c6c55d1c839a731c38303f48b7535 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 205                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0297e37f1873d2dab4487aa67cd56b58e2f27875                         | Address of the contract that produced the log                |
| swapFeePercentage | VARCHAR   | 3000000000000000                                                   |                                                              |

## 116. Table: V2\_WeightedPool\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-23 09:14:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17541306                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0e2619a0b4ddbc62091a9a0a8cc9d591f05d1cfa5c93215a3dbcb104baa9955f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 214                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0578292cb20a443ba1cde459c985ce14ca2bdee5                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xde67fa32960df9f7087556712ebb93304e42673d                         |                                                              |
| value             | VARCHAR   | 94036344752284646                                                  |                                                              |

## 117. Table: VotingEscrow\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-18 23:51:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16000296                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x661e1ed34fb5941d78c0f2014a327f53bedc5049e1d73e5705f43d352025665e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 418                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc128a9954e6c874ea3d62ce62b468ba073093f25                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xab329745233d1b619f4007cacd0816e2a6b78e41                         |                                                              |
| value             | VARCHAR   | 430753534412579509828                                              |                                                              |
| locktime          | VARCHAR   | 1672272000                                                         |                                                              |
| type              | VARCHAR   | 1                                                                  |                                                              |
| ts                | VARCHAR   | 1668815495                                                         |                                                              |

## 118. Table: VotingEscrow\_event\_Supply\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-15 07:32:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17263720                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x86a01547f525d1de646c5559d2a8087fba0021e034e9d8e7e4899a8362625727 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 143                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc128a9954e6c874ea3d62ce62b468ba073093f25                         | Address of the contract that produced the log                |
| prevSupply        | VARCHAR   | 13377724522791886600116837                                         |                                                              |
| supply            | VARCHAR   | 13377725746734517652681425                                         |                                                              |

## 119. Table: VotingEscrow\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-29 19:42:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17366788                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9a495b190c865f6f687fb233aef6f90c8dc5810de7229daac64d05116b62fb5a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 262                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc128a9954e6c874ea3d62ce62b468ba073093f25                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xc45b95c5ddf369f6baa7f61b21ff275f965c73c4                         |                                                              |
| value             | VARCHAR   | 550911707542202525589                                              |                                                              |
| ts                | VARCHAR   | 1685389355                                                         |                                                              |
