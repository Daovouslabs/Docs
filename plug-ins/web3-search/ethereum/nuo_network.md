# nuo\_network

## 1. Table: KernelEscrow\_event\_LogSetAuthority\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-22 15:44:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7109491                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6047b0e3af2a5aa4b64a035ba0bbb2ef32c8e05ca50ae1e2e13f9c8fa9c0fa95 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xaf38668f4719ecf9452dc0300be3f6c83cbf3721                         | Address of the contract that produced the log                |
| authority         | VARCHAR   | 0xde4a88ef731cc55450c76e9307a64e94146006f7                         |                                                              |

## 2. Table: KernelEscrow\_event\_LogSetOwner\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-22 15:44:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7109493                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x757d75b36511e601c906d2f55f85cb8074a2dbcdd1bf29979d44458d9abe2a79 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xaf38668f4719ecf9452dc0300be3f6c83cbf3721                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 3. Table: KernelEscrow\_event\_LogTransferFromAccount\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-19 02:16:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9309019                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc9ed0f67ba5253788767d7b377f586aca014f26d315d5a5d083cb76bd902c75d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 31                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xaf38668f4719ecf9452dc0300be3f6c83cbf3721                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x64ad72731bfd77fdd564fe860491af7ffc660b17                         |                                                              |
| token             | VARCHAR   | 0x0d8775f648430679a709e98d2b0cb6250d2887ef                         |                                                              |
| to                | VARCHAR   | 0xaf38668f4719ecf9452dc0300be3f6c83cbf3721                         |                                                              |
| value             | VARCHAR   | 200000000000000000000                                              |                                                              |

## 4. Table: KernelEscrow\_event\_LogTransfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-09-05 07:27:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8488705                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x095a9c565e3d3ef89a7dfe85df514d53862f3db0ca5c28404cd6fa65b6a445c3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 45                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xaf38668f4719ecf9452dc0300be3f6c83cbf3721                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x514910771af9ca656af840dff83e8264ecf986ca                         |                                                              |
| to                | VARCHAR   | 0x521550e569bc80f1b4957c4f3fd3d677d9ca31f1                         |                                                              |
| value             | VARCHAR   | 202424700000000000000                                              |                                                              |

## 5. Table: Kernel\_event\_LogErrorWithHintBytes32\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-02-01 00:38:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7156273                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe89857fd15cb9e51a358c51145fdda963830210a0db79702ea001a51c3066d31 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 97                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0f99be6639b1ddfbedf319b4de67e558a41aa6ea                         | Address of the contract that produced the log                |
| bytes32Value      | VARCHAR   | 0x0f22573e7b850eb8cc28e32c1e1d26aba0c31a6c6384c2a0765ac505f3118c7b |                                                              |
| methodSig         | VARCHAR   | Kernel::repay                                                      |                                                              |
| errMsg            | VARCHAR   | INSUFFICIENT\_BALANCE\_IN\_ACCOUNT                                 |                                                              |

## 6. Table: Kernel\_event\_LogOrderCreated\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2019-02-03 00:11:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 7165954                                                            | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x1447ce4cb8d56bcfb7a60774852cab26a9e7d976c214dd3b6611584fcd8d7610 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 115                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x0f99be6639b1ddfbedf319b4de67e558a41aa6ea                         | Address of the contract that produced the log                |
| orderHash           | VARCHAR   | 0xa7237a2927b6bd17bedfb1cdc1aa507b1a74ea1738d369389859bc7891166216 |                                                              |
| account             | VARCHAR   | 0x8de5bc39fd2546945d53288d713f964bbbe812c6                         |                                                              |
| principalToken      | VARCHAR   | 0x1985365e9f78359a9b6ad760e32412f4a445e862                         |                                                              |
| collateralToken     | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| byUser              | VARCHAR   | 0xd88c5cada2aacd7fa866625e77cbbe95463ed67e                         |                                                              |
| principalAmount     | VARCHAR   | 1524800000000000000                                                |                                                              |
| collateralAmount    | VARCHAR   | 308802400000000000                                                 |                                                              |
| premium             | VARCHAR   | 2712328767123288                                                   |                                                              |
| expirationTimestamp | VARCHAR   | 1556928687                                                         |                                                              |
| fee                 | VARCHAR   | 0                                                                  |                                                              |

## 7. Table: Kernel\_event\_LogOrderDefaulted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-18 13:15:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9125752                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdd0a770fdaf8c5c051c6c1b414c8a41c31e469771b18dba0f7d02ac4694c2b2e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 102                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0f99be6639b1ddfbedf319b4de67e558a41aa6ea                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0xb7f0da75fd9c566273dfb5d0c2b706e7fdf10afc5498b0b1bf356403f358cd60 |                                                              |
| reason            | VARCHAR   | COLLATERAL\_UNSAFE                                                 |                                                              |

## 8. Table: Kernel\_event\_LogOrderRepaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-05-02 13:55:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7682051                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6b10bd35e9a1959f9dac1f488fb915724aa81d6af3d7d40aae50ff1946d1e8f9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 91                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0f99be6639b1ddfbedf319b4de67e558a41aa6ea                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0xfdea02a99462a731519a1edb3895c21de1be673b32db0e48d17047c2472e59f1 |                                                              |
| valueRepaid       | VARCHAR   | 10216986301369863300                                               |                                                              |

## 9. Table: Kernel\_event\_LogSetAuthority\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-22 16:02:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7109547                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbbb900becfb300c7146ca000792d1f8b6d60184e81cc74a556a328a96ffb29f7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 19                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0f99be6639b1ddfbedf319b4de67e558a41aa6ea                         | Address of the contract that produced the log                |
| authority         | VARCHAR   | 0xde4a88ef731cc55450c76e9307a64e94146006f7                         |                                                              |

## 10. Table: Kernel\_event\_LogSetOwner\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-22 16:01:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7109544                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc51846393fca94c3e2ce7c4177ae89631667add36b0503e0cceb2f5f05bfd297 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 19                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0f99be6639b1ddfbedf319b4de67e558a41aa6ea                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x3e990e787a88cd4426fb3af9b90dd1d951e2cb87                         |                                                              |

## 11. Table: ReserveEscrow\_event\_LogSetAuthority\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-22 15:39:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7109476                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3e4afbba4510f6129864c2d432da0c769937fe7f5c4223cee67d3ae09cd02807 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x802275979b020f0ec871c5ec1db6e412b72ff20b                         | Address of the contract that produced the log                |
| authority         | VARCHAR   | 0xde4a88ef731cc55450c76e9307a64e94146006f7                         |                                                              |

## 12. Table: ReserveEscrow\_event\_LogSetOwner\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-22 15:39:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7109478                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x63d6df41d62f928316947feb10e9adb16badaa6f2e63d308d4243beeb2314b18 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x802275979b020f0ec871c5ec1db6e412b72ff20b                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 13. Table: ReserveEscrow\_event\_LogTransferFromAccount\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-02-14 08:10:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9479994                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x422d2d54346aad9d75376b881d8e08f35c6311ec4a151324061b5576a27a8ba2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 47                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x802275979b020f0ec871c5ec1db6e412b72ff20b                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xd5868181c4cd1433f0af0dfe77fc162233070fe7                         |                                                              |
| token             | VARCHAR   | 0x0d8775f648430679a709e98d2b0cb6250d2887ef                         |                                                              |
| to                | VARCHAR   | 0x802275979b020f0ec871c5ec1db6e412b72ff20b                         |                                                              |
| value             | VARCHAR   | 99999999000000000000                                               |                                                              |

## 14. Table: ReserveEscrow\_event\_LogTransfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-04-30 22:17:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7671387                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x32dda42e8a43c466e181b6d6aaab6e117b6ec0b82a2809fb5bdeec2d1fbf67f9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 142                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x802275979b020f0ec871c5ec1db6e412b72ff20b                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| to                | VARCHAR   | 0x03d0fbeae332c6b270b3f4c4d22d2f1d3057cf82                         |                                                              |
| value             | VARCHAR   | 2304800000000000000                                                |                                                              |

## 15. Table: Reserve\_event\_LogErrorWithHintAddress\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-07-24 19:20:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8215248                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe9dc77b34e218d010d05ef13a0dc4c14eaa3d73177cdf497f9a9208e29270ca7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 68                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x64d14595152b430cf6940da15c6e39545c7c5b7e                         | Address of the contract that produced the log                |
| addressValue      | VARCHAR   | 0xe41d2489571d322189246dafa5ebde1f4699f498                         |                                                              |
| methodSig         | VARCHAR   | Reserve::updateReserveValues                                       |                                                              |
| errMsg            | VARCHAR   | RESERVE\_VALUES\_UP\_TO\_DATE                                      |                                                              |

## 16. Table: Reserve\_event\_LogErrorWithHintBytes32\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-08 09:08:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8895352                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe81a1781d16b78779bd012afe954bd04242c6ad1697eefd5e4fb2353d862684a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 125                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x64d14595152b430cf6940da15c6e39545c7c5b7e                         | Address of the contract that produced the log                |
| bytes32Value      | VARCHAR   | 0x94363851247fcaed4079d67fda1b627750d34764e9f054533d4b84f1272593d1 |                                                              |
| methodSig         | VARCHAR   | Reserve::updateOrderCumulativeValue                                |                                                              |
| errMsg            | VARCHAR   | ORDER\_DOES\_NOT\_EXIST                                            |                                                              |

## 17. Table: Reserve\_event\_LogLock\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-05-05 18:01:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7702388                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb93247b8b2ad7c4e17c70fc0195bca73150a3021b14871380a19f23781a41f68 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 110                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x64d14595152b430cf6940da15c6e39545c7c5b7e                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599                         |                                                              |
| from              | VARCHAR   | 0x243e8b5823becd4f2702224b195d07d09f186654                         |                                                              |
| value             | VARCHAR   | 300045                                                             |                                                              |
| profit            | VARCHAR   | 45                                                                 |                                                              |
| loss              | VARCHAR   | 0                                                                  |                                                              |
| by                | VARCHAR   | 0x8dc3bcbb4b506fa2becd065ff4425dee32f156a6                         |                                                              |

## 18. Table: Reserve\_event\_LogOrderCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-09 01:20:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10228552                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x19667b530919404accf5df46b561c48be42fdd26a46661b536141324715f7077 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 161                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x64d14595152b430cf6940da15c6e39545c7c5b7e                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0x717ac044fde62236aa6c1b2505ee270331dc126508b05279501366552093772c |                                                              |
| by                | VARCHAR   | 0x8a333c59eab0ad608f857a02c3702b910e24493b                         |                                                              |

## 19. Table: Reserve\_event\_LogOrderCreated\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2019-06-08 07:40:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 7917101                                                            | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x706f63a5e49987aa726b256b6871b52ac2bb6bf47357b11ee594eb05fd2ab7aa | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x64d14595152b430cf6940da15c6e39545c7c5b7e                         | Address of the contract that produced the log                |
| orderHash           | VARCHAR   | 0x95d7e7f4f85de168fd60a4ff9dde7a622dffb41596e9169de403142c31a4275b |                                                              |
| account             | VARCHAR   | 0x9190b6c38c9c6dd2fdd44b734158943218e80fdc                         |                                                              |
| token               | VARCHAR   | 0x0d8775f648430679a709e98d2b0cb6250d2887ef                         |                                                              |
| byUser              | VARCHAR   | 0xadd87482af34527744ea363316d258e37cb06e2a                         |                                                              |
| value               | VARCHAR   | 1501999999000000000000                                             |                                                              |
| expirationTimestamp | VARCHAR   | 2423979649                                                         |                                                              |

## 20. Table: Reserve\_event\_LogOrderCumulativeUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-20 17:52:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8969728                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8fa609eb21b6408d0d75bd4b8c4c243a9177ee451bd5b200cd97ec31ae5263f9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 49                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x64d14595152b430cf6940da15c6e39545c7c5b7e                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0xbdffbdffe8f885a187609ffef370a93c058d4f6301b508293c3cd07baa99339c |                                                              |
| updatedTill       | VARCHAR   | 1574121600                                                         |                                                              |
| value             | VARCHAR   | 183707                                                             |                                                              |

## 21. Table: Reserve\_event\_LogRelease\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-05-15 09:48:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7764198                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x343f01d129c8f92ed16694fd3af210f64b327f92f78e6282086cf1501ada2bee | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 60                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x64d14595152b430cf6940da15c6e39545c7c5b7e                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| to                | VARCHAR   | 0xaf38668f4719ecf9452dc0300be3f6c83cbf3721                         |                                                              |
| value             | VARCHAR   | 307662000000000000                                                 |                                                              |
| by                | VARCHAR   | 0x740f8b58f5562c8379f2a8c2230c9be5c03ac3fc                         |                                                              |

## 22. Table: Reserve\_event\_LogReserveValuesUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-03-12 15:15:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7355056                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9283e2ed7df75eeaf062d312774a9ac6f9460f36c0b9596e1e67989ca4a6d6c2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 49                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x64d14595152b430cf6940da15c6e39545c7c5b7e                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0xe41d2489571d322189246dafa5ebde1f4699f498                         |                                                              |
| updatedTill       | VARCHAR   | 1552262400                                                         |                                                              |
| reserve           | VARCHAR   | 9806053585672267433538                                             |                                                              |
| profit            | VARCHAR   | 0                                                                  |                                                              |
| loss              | VARCHAR   | 0                                                                  |                                                              |

## 23. Table: Reserve\_event\_LogSetAuthority\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-22 15:59:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7109532                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7881806ca64354eb4d9511a00f868ad9c015552ce0a59e02198ac790d078ca6f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x64d14595152b430cf6940da15c6e39545c7c5b7e                         | Address of the contract that produced the log                |
| authority         | VARCHAR   | 0xde4a88ef731cc55450c76e9307a64e94146006f7                         |                                                              |

## 24. Table: Reserve\_event\_LogSetOwner\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-22 15:57:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7109528                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6dd66aa52ba52d94bce1063fa68101b09f033761a52894b0d63c684de41890a5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x64d14595152b430cf6940da15c6e39545c7c5b7e                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x3e990e787a88cd4426fb3af9b90dd1d951e2cb87                         |                                                              |
