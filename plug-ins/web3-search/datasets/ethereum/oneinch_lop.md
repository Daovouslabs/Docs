# oneinch\_lop

## 1. Table: AggregationRouterV4\_call\_fillOrderRFQToWithPermit\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-06-07 07:05:52+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14919467                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x70911dc3539005db78ac238ea5ecf575d6c23281ac52161d09cd6fc7f1e35573                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 119                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x1111111254fb6c44bac0bed2854e76f90643097d                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| order              | VARCHAR   | 57896044618658097711785492504343953926634992332850803732431265333026272709015,0xC02aaA39b223FE8D0A0e |                                                                                                                        |
| signature          | VARCHAR   | 0x1be8bd5f5470bc02ae0cbac0914a230c13b09a155d50be707f050c617de01dba35686d6c14a0fec8a4ad1bfd2c649a320b |                                                                                                                        |
| makingAmount       | VARCHAR   | 0                                                                                                    |                                                                                                                        |
| takingAmount       | VARCHAR   | 199004239499796375                                                                                   |                                                                                                                        |
| target             | VARCHAR   | 0x6c4cde76cacaf67b00d471e4c5fa45c0c2a526f6                                                           |                                                                                                                        |
| permit             | VARCHAR   | 0x0000000000000000000000006c4cde76cacaf67b00d471e4c5fa45c0c2a526f60000000000000000000000001111111254 |                                                                                                                        |

## 2. Table: AggregationRouterV4\_call\_fillOrderRFQTo\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-08-19 11:06:20+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15370906                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xac80c663f9020556070325e9e8be5fad569dab4ab72613d06bd9b92e76fa899f                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 49                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 3,0                                                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x1111111254fb6c44bac0bed2854e76f90643097d                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| order              | VARCHAR   | 30638331930149420506160306246,0xdAC17F958D2ee523a2206206994597C13D831ec7,0xC02aaA39b223FE8D0A0e5C4F2 |                                                                                                                        |
| signature          | VARCHAR   | 0xdb1ed1668c186a9fdd84e89266ea55cb85000eefb0eebcd99c84376422281f2c385cfd6c92efb079faa8518e5f02dff178 |                                                                                                                        |
| makingAmount       | VARCHAR   | 0                                                                                                    |                                                                                                                        |
| takingAmount       | VARCHAR   | 168062356929674608640                                                                                |                                                                                                                        |
| target             | VARCHAR   | 0xb0273284f69bee017b5332b81b668aebeea22532                                                           |                                                                                                                        |

## 3. Table: AggregationRouterV4\_call\_fillOrderRFQ\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-09-02 11:30:22+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15458899                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x6e019ac514a8904b69c47d81dee32f7595b197b68aedba272d0a28dea8052a8c                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 296                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,1                                                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x1111111254fb6c44bac0bed2854e76f90643097d                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| order              | VARCHAR   | 57896044618658097711785492504343953926634992332850942673030927353925517976623,0x3845badAde8e6dFF0498 |                                                                                                                        |
| signature          | VARCHAR   | 0x0f5697fb4b46fd2b40a8b4182e99191c19e624083d0b2ca1d0ec5ba4d472a7745e57e840d797be2beef1a265d9f1edc26a |                                                                                                                        |
| makingAmount       | VARCHAR   | 0                                                                                                    |                                                                                                                        |
| takingAmount       | VARCHAR   | 133841938717842559                                                                                   |                                                                                                                        |

## 4. Table: LimitOrderProtocolV2\_call\_fillOrderRFQToWithPermit\_history

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
| order              | VARCHAR   |                                                                                                                        |             |
| signature          | VARCHAR   |                                                                                                                        |             |
| makingAmount       | VARCHAR   |                                                                                                                        |             |
| takingAmount       | VARCHAR   |                                                                                                                        |             |
| target             | VARCHAR   |                                                                                                                        |             |
| permit             | VARCHAR   |                                                                                                                        |             |

## 5. Table: LimitOrderProtocolV2\_call\_fillOrderRFQTo\_history

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
| order              | VARCHAR   |                                                                                                                        |             |
| signature          | VARCHAR   |                                                                                                                        |             |
| makingAmount       | VARCHAR   |                                                                                                                        |             |
| takingAmount       | VARCHAR   |                                                                                                                        |             |
| target             | VARCHAR   |                                                                                                                        |             |

## 6. Table: LimitOrderProtocolV2\_call\_fillOrderRFQ\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-12-21 11:32:16+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 13848282                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xa9a3835417067a0fbc1a83eba09569c683720097bb8ef21fb3f6d239b3c76b12                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 275                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x119c71d3bbac22029622cbaec24854d3d32d2828                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| order              | VARCHAR   | 30254262134958361267766432636,0xdAC17F958D2ee523a2206206994597C13D831ec7,0xC02aaA39b223FE8D0A0e5C4F2 |                                                                                                                        |
| signature          | VARCHAR   | 0x53cc6f188aac39772e1e3e8ccb68954f4bd64d35be951058a032bf695e6afe5a0c6786755abbc98fe43009ba50a7e808f7 |                                                                                                                        |
| makingAmount       | VARCHAR   | 0                                                                                                    |                                                                                                                        |
| takingAmount       | VARCHAR   | 20000000000000                                                                                       |                                                                                                                        |

## 7. Table: LimitOrderProtocolV2\_call\_fillOrderToWithPermit\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-03-01 09:47:12+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14300383                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xb456e13590723eead397615e4cac6448177f47415fa52044f6652f8af14a13f7                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 144                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x119c71d3bbac22029622cbaec24854d3d32d2828                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| order              | VARCHAR   | 133209602213,0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2,0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48,0 |                                                                                                                        |
| signature          | VARCHAR   | 0xeee10ceb69508a8e21b0cdf248e8c7a4304859cac0a6b7307c108eac0db7447a40cf52dd0ff785565c2137d345a148842f |                                                                                                                        |
| makingAmount       | VARCHAR   | 0                                                                                                    |                                                                                                                        |
| takingAmount       | VARCHAR   | 2884698                                                                                              |                                                                                                                        |
| thresholdAmount    | VARCHAR   | 1000000000000000                                                                                     |                                                                                                                        |
| target             | VARCHAR   | 0x04d3b2c70208f3fb196affef78080b3cc05ee1cb                                                           |                                                                                                                        |
| permit             | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb4800000000000000000000000004d3b2c70208f3fb196affef78080b3cc0 |                                                                                                                        |

## 8. Table: LimitOrderProtocolV2\_call\_fillOrderTo\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-09-17 04:20:59+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15550892                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x851fd75261dbbd701a0989832cb521df74753e2f21b9325d6020e41ceb96dbe0                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 177                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,2                                                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x119c71d3bbac22029622cbaec24854d3d32d2828                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| order              | VARCHAR   | 891916110869,0x27054b13b1B798B345b591a4d22e6562d47eA75a,0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2,0 |                                                                                                                        |
| signature          | VARCHAR   | 0x61a45a32d9415c38f70806e35b815f581e7b3dbf92a54453855b3be96ad93252f4a4c43c1b69b12d75835291505f9c99ee |                                                                                                                        |
| makingAmount       | VARCHAR   | 0                                                                                                    |                                                                                                                        |
| takingAmount       | VARCHAR   | 10000000000000000                                                                                    |                                                                                                                        |
| thresholdAmount    | VARCHAR   | 942856                                                                                               |                                                                                                                        |
| target             | VARCHAR   | 0x1111111254fb6c44bac0bed2854e76f90643097d                                                           |                                                                                                                        |

## 9. Table: LimitOrderProtocolV2\_call\_fillOrder\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-05-11 19:57:39+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14756863                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xb5bb1424c4033ad642084ba83b26b291070352cb45d31cdd5fb42369dfdfde69                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 3                                                                                                    | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 1,1                                                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x119c71d3bbac22029622cbaec24854d3d32d2828                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| order              | VARCHAR   | 986672811895,0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48,0xf3b9569F82B18aEf890De263B84189bd33EBe452,0 |                                                                                                                        |
| signature          | VARCHAR   | 0x9ae9a2963ff6eb7d398af9b1a9f435912e6d3147dd8a8853351fb9e76f9ea21606f38bda09d1607c23a51a147f13e90beb |                                                                                                                        |
| makingAmount       | VARCHAR   | 0                                                                                                    |                                                                                                                        |
| takingAmount       | VARCHAR   | 58101624370437730000000000000                                                                        |                                                                                                                        |
| thresholdAmount    | VARCHAR   | 1                                                                                                    |                                                                                                                        |

## 10. Table: LimitOrderProtocolV2\_event\_OrderFilledRFQ\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-21 11:32:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13848282                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa9a3835417067a0fbc1a83eba09569c683720097bb8ef21fb3f6d239b3c76b12 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 509                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x119c71d3bbac22029622cbaec24854d3d32d2828                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0x9514e34614d3ff2faf73c80b51d90ac5e655e46fdab4ad99c12f7bfcfa347392 |                                                              |
| makingAmount      | VARCHAR   | 1000000                                                            |                                                              |

## 11. Table: LimitOrderProtocolV2\_event\_OrderFilled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-04 22:29:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17844604                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1084d30844fafd9000ba23cc63fcb42b4f5fe2630ad6ea68b6a4e79ac7f423bf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 15                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x119c71d3bbac22029622cbaec24854d3d32d2828                         | Address of the contract that produced the log                |
| maker             | VARCHAR   | 0x9dd864d39fbfdf7648402746263e451cd4f36af0                         |                                                              |
| orderHash         | VARCHAR   | 0x0cfa7982f6af89dc720d6381730da94222f4e73fcdbc1d7765fb33f9f0c0675a |                                                              |
| remaining         | VARCHAR   | 890640                                                             |                                                              |

## 12. Table: LimitOrderProtocol\_call\_fillOrderRFQ\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-09-22 22:12:37+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 13278206                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x015c4c5b9667d22c3dbfb88641479b2e6718ce1e2c0a72ea858459ba3136fea0                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 217                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 1,2                                                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3ef51736315f52d568d6d2cf289419b9cfffe782                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| order              | VARCHAR   | 30111445419038285926235374597,0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2,0x6B175474E89094C44Da98b954 |                                                                                                                        |
| signature          | VARCHAR   | 0xa794650730ffe0849a9fb4660cde4f929f898801b0ffbd8d51b1f0e26528d5fb7af92f6e8ff910c73f916e9c14aaab367f |                                                                                                                        |
| makingAmount       | VARCHAR   | 0                                                                                                    |                                                                                                                        |
| takingAmount       | VARCHAR   | 9000000000000000000000                                                                               |                                                                                                                        |

## 13. Table: LimitOrderProtocol\_call\_fillOrder\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-11-18 03:47:58+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 13637021                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xf1fcde878218422509d1f28cadefc074cf7d4539d9b42e41cc42f630db52be84                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 34                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3ef51736315f52d568d6d2cf289419b9cfffe782                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| order              | VARCHAR   | 511746172086,0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48,0xcAfE001067cDEF266AfB7Eb5A286dCFD277f3dE5,0 |                                                                                                                        |
| signature          | VARCHAR   | 0x0c5119f12f2069fc8c2af49a003b28426f8b4a23d3b98c0c080d596301104f3969314154222d9673106b9d97569e68594d |                                                                                                                        |
| makingAmount       | VARCHAR   | 0                                                                                                    |                                                                                                                        |
| takingAmount       | VARCHAR   | 7536594930552462901288                                                                               |                                                                                                                        |
| thresholdAmount    | VARCHAR   | 11429057317                                                                                          |                                                                                                                        |

## 14. Table: LimitOrderProtocol\_event\_OrderFilledRFQ\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-04 16:53:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13160397                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9e3c5f0b84ba4eace5efdc037d4435d335687b721b32a6782e4f6cfddfa5852c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3ef51736315f52d568d6d2cf289419b9cfffe782                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0xba53cf219f48062325cd23f97b0e371ef284811d60c3f1fac8ffe2c24d0fe035 |                                                              |
| makingAmount      | VARCHAR   | 14639974640326125568                                               |                                                              |

## 15. Table: LimitOrderProtocol\_event\_OrderFilled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-18 10:46:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17719612                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x29f2d685c8193b241acbde8b3dbd2b9b8e0108635d0d3d92c0083e70ab23436e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 283                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3ef51736315f52d568d6d2cf289419b9cfffe782                         | Address of the contract that produced the log                |
| maker             | VARCHAR   | 0xce487fc30de2ff3c9241722d24466a407ed2dc2f                         |                                                              |
| orderHash         | VARCHAR   | 0xf6f3ccf938c539a2786d9b16781cb435e43fa6151b5354512071dacc12bb33ed |                                                              |
| remaining         | VARCHAR   | 0                                                                  |                                                              |
