# oasis

## 1. Table: MatchingMarket\_event\_LogBump\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-07-06 20:53:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8100012                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0fcdfefc688424c83e79aaa238b71df27da55d5945920a6ea788b221e5c8bcf8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 31                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x39755357759ce0d7f32dc8dc45414cca409ae24e                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000045f23 |                                                              |
| pair              | VARCHAR   | 0x10aed75aa327f09ef87e5bdfaedf498ca260499a251ae5e049ddbd5e1633cd9c |                                                              |
| maker             | VARCHAR   | 0xa4da0f347c6abe0e8bc71b5981fd92b364eda4c2                         |                                                              |
| pay\_gem          | VARCHAR   | 0x89d24a6b4ccb1b6faa2625fe562bdd9a23260359                         |                                                              |
| buy\_gem          | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| pay\_amt          | VARCHAR   | 6153000000000000000                                                |                                                              |
| buy\_amt          | VARCHAR   | 21000000000000000                                                  |                                                              |
| timestamp         | VARCHAR   | 1562446107                                                         |                                                              |

## 2. Table: MatchingMarket\_event\_LogInsert\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-03-12 07:27:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7352952                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd42e7dbf03aff8bdca2fbfe3c0be6043c7ab00df3401b4d767d0d13cb28fa7d8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 51                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x39755357759ce0d7f32dc8dc45414cca409ae24e                         | Address of the contract that produced the log                |
| keeper            | VARCHAR   | 0x3a32292c53bf42b6317334392bf0272da2983252                         |                                                              |
| id                | VARCHAR   | 36242                                                              |                                                              |

## 3. Table: MatchingMarket\_event\_LogItemUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-10 01:44:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9080576                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8258aaf1a5b325a35dc387bfe4bcccb62f36f496f55ecedc39304497950d8df5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 25                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x39755357759ce0d7f32dc8dc45414cca409ae24e                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 673806                                                             |                                                              |

## 4. Table: MatchingMarket\_event\_LogKill\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-03-24 17:40:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7432769                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3830b1bf0bba614f6c015a77a07a1dadaf296e2e4f90fb779641aefd4580c3fa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 55                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x39755357759ce0d7f32dc8dc45414cca409ae24e                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 0x000000000000000000000000000000000000000000000000000000000000a572 |                                                              |
| pair              | VARCHAR   | 0x7509deda9e17580c94915865c0c0c56190cc733e6c835a6ca2e497c1e4a50a5d |                                                              |
| maker             | VARCHAR   | 0x65693adb7ef9d49cbc0cb5004e7dfc73b14c9297                         |                                                              |
| pay\_gem          | VARCHAR   | 0x9f8f72aa9304c8b593d555f12ef6589cc3a579a2                         |                                                              |
| buy\_gem          | VARCHAR   | 0x89d24a6b4ccb1b6faa2625fe562bdd9a23260359                         |                                                              |
| pay\_amt          | VARCHAR   | 10000000000000000000                                               |                                                              |
| buy\_amt          | VARCHAR   | 7699374536311206361650                                             |                                                              |
| timestamp         | VARCHAR   | 1553449209                                                         |                                                              |

## 5. Table: MatchingMarket\_event\_LogMake\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-23 19:17:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9339811                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x85ab9e4a86e18295195433116bca44de1c03e956fc538f7be9072b0f16b0950a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 69                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x39755357759ce0d7f32dc8dc45414cca409ae24e                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 0x00000000000000000000000000000000000000000000000000000000000b9283 |                                                              |
| pair              | VARCHAR   | 0x203e3b62e033f1548774797f9135c574dddd995f86e1c55fe1bab1610d35094f |                                                              |
| maker             | VARCHAR   | 0x2b13d1463b3821dd8a625e8935ab079251f1376d                         |                                                              |
| pay\_gem          | VARCHAR   | 0x9f8f72aa9304c8b593d555f12ef6589cc3a579a2                         |                                                              |
| buy\_gem          | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| pay\_amt          | VARCHAR   | 9422010000000000000                                                |                                                              |
| buy\_amt          | VARCHAR   | 27418049100000000000                                               |                                                              |
| timestamp         | VARCHAR   | 1579807049                                                         |                                                              |

## 6. Table: MatchingMarket\_event\_LogMinSell\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-09-23 16:50:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8606584                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8fd43df5cb6d0ccb2daae50b80530974372563eb1de1bd0074ddafd7af21e03c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 75                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x39755357759ce0d7f32dc8dc45414cca409ae24e                         | Address of the contract that produced the log                |
| pay\_gem          | VARCHAR   | 0xe41d2489571d322189246dafa5ebde1f4699f498                         |                                                              |
| min\_amount       | VARCHAR   | 5350000000000000000                                                |                                                              |

## 7. Table: MatchingMarket\_event\_LogSetOwner\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-02-06 15:26:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7183773                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xafdd6a144164f5ad63c859b3ef0c2044f848dfd781875c6a9c5defc09dd9af04 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x39755357759ce0d7f32dc8dc45414cca409ae24e                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xdb33dfd3d61308c33c63209845dad3e6bfb2c674                         |                                                              |

## 8. Table: MatchingMarket\_event\_LogSortedOffer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-26 14:06:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9357870                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9525c90527d57eaf322e184132a4c1badcbfd2d1d1a42f48f327e41ccdf2390f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 58                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x39755357759ce0d7f32dc8dc45414cca409ae24e                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 764072                                                             |                                                              |

## 9. Table: MatchingMarket\_event\_LogTake\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-07-29 00:09:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8242271                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcc253033115a328d1b7e6194fe831d26bd26787497fb9f34fe492f0a01d3ed72 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 158                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x39755357759ce0d7f32dc8dc45414cca409ae24e                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000058d45 |                                                              |
| pair              | VARCHAR   | 0x10aed75aa327f09ef87e5bdfaedf498ca260499a251ae5e049ddbd5e1633cd9c |                                                              |
| maker             | VARCHAR   | 0x1f487a4435f3b730d742aa4b6ef8c9e0a6b9a027                         |                                                              |
| pay\_gem          | VARCHAR   | 0x89d24a6b4ccb1b6faa2625fe562bdd9a23260359                         |                                                              |
| buy\_gem          | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| taker             | VARCHAR   | 0xab33e884ec8fed4f5867246e4300228f3d666561                         |                                                              |
| take\_amt         | VARCHAR   | 1238767859999999999947                                             |                                                              |
| give\_amt         | VARCHAR   | 5933333333333333332                                                |                                                              |
| timestamp         | VARCHAR   | 1564358991                                                         |                                                              |

## 10. Table: MatchingMarket\_event\_LogTrade\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-06-27 10:39:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8039467                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9f70cf6b70cc6c61e2b2806d6769e9d7c81ea1f25ddaa17fdb30283b99e0bbfc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 64                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x39755357759ce0d7f32dc8dc45414cca409ae24e                         | Address of the contract that produced the log                |
| pay\_amt          | VARCHAR   | 4205600000000000000                                                |                                                              |
| pay\_gem          | VARCHAR   | 0x89d24a6b4ccb1b6faa2625fe562bdd9a23260359                         |                                                              |
| buy\_amt          | VARCHAR   | 42056                                                              |                                                              |
| buy\_gem          | VARCHAR   | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599                         |                                                              |

## 11. Table: MatchingMarket\_event\_LogUnsortedOffer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-04-16 14:52:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7579586                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xed7df9cf0594510626cf274967b482a1441cd4eaabbb3f47293a896dac283d20 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 100                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x39755357759ce0d7f32dc8dc45414cca409ae24e                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 78050                                                              |                                                              |

## 12. Table: MatchingMarket\_v2\_event\_LogItemUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-14 20:11:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9872660                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd3e573629a3d24512e0636d2ddd9bfcb3b68b406749f69fddfcb6ef78d64fcaf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 9                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794e6e91555438afc3ccf1c5076a74f42133d08d                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 249812                                                             |                                                              |

## 13. Table: MatchingMarket\_v2\_event\_LogKill\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-06 19:54:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11205771                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb36b7e4241036738caa260495bbd242e0cb0292252509cd6ef6e4cb4edce48b8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 109                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794e6e91555438afc3ccf1c5076a74f42133d08d                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000067248 |                                                              |
| pair              | VARCHAR   | 0x7bda8b27e891f9687bd6d3312ab3f4f458e2cc91916429d721d617df7ac29fb8 |                                                              |
| maker             | VARCHAR   | 0x5f5d1f7e529e56b2fd530ded0812f766229eec4a                         |                                                              |
| pay\_gem          | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         |                                                              |
| buy\_gem          | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| pay\_amt          | VARCHAR   | 90488681346717164                                                  |                                                              |
| buy\_amt          | VARCHAR   | 205371374564167                                                    |                                                              |
| timestamp         | VARCHAR   | 1604692447                                                         |                                                              |

## 14. Table: MatchingMarket\_v2\_event\_LogMake\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-15 18:52:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10465809                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x421cc27129535297915f594b0b6dd728c781a5c47dbfeedced8a7378514afd9d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 39                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794e6e91555438afc3ccf1c5076a74f42133d08d                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 0x000000000000000000000000000000000000000000000000000000000005ecd4 |                                                              |
| pair              | VARCHAR   | 0x144a00af3eb275ca2d209b2689fd51eadf25b43bf75f76c00799093cf2ea566c |                                                              |
| maker             | VARCHAR   | 0x38caa9a43c911a5bd745c5ba8d40dbaad26f90e1                         |                                                              |
| pay\_gem          | VARCHAR   | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599                         |                                                              |
| buy\_gem          | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         |                                                              |
| pay\_amt          | VARCHAR   | 170000000                                                          |                                                              |
| buy\_amt          | VARCHAR   | 15453573852000000000000                                            |                                                              |
| timestamp         | VARCHAR   | 1594839132                                                         |                                                              |

## 15. Table: MatchingMarket\_v2\_event\_LogMinSell\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-02-04 16:28:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9417210                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfb1088a9bbfd4705ad53196e57c77027e30968ee47de6dc3e2ed88ed2cec0d4b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 18                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794e6e91555438afc3ccf1c5076a74f42133d08d                         | Address of the contract that produced the log                |
| pay\_gem          | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| min\_amount       | VARCHAR   | 2000000                                                            |                                                              |

## 16. Table: MatchingMarket\_v2\_event\_LogSetOwner\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-02-04 16:22:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9417183                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x24b49b60552eefdac8e96b2889c6aaab2fe0acb60e961c120cc940dba07c6850 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 46                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794e6e91555438afc3ccf1c5076a74f42133d08d                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xdb33dfd3d61308c33c63209845dad3e6bfb2c674                         |                                                              |

## 17. Table: MatchingMarket\_v2\_event\_LogSortedOffer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-29 12:57:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10554639                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x078d1ff26de4f8f5b1c697f0a82362d2a81b9157733b6f0af428216837a2b724 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794e6e91555438afc3ccf1c5076a74f42133d08d                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 403830                                                             |                                                              |

## 18. Table: MatchingMarket\_v2\_event\_LogTake\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-03 11:25:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10788049                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcdbffd90bbc9831c9dbe9a301f6b8a1e7647c888007cfe4b949beefa9747e27d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 179                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794e6e91555438afc3ccf1c5076a74f42133d08d                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000066e10 |                                                              |
| pair              | VARCHAR   | 0x7bda8b27e891f9687bd6d3312ab3f4f458e2cc91916429d721d617df7ac29fb8 |                                                              |
| maker             | VARCHAR   | 0xd404e9e88d6ffffa8d92cb20415cd73919c2ead6                         |                                                              |
| pay\_gem          | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         |                                                              |
| buy\_gem          | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| taker             | VARCHAR   | 0x0d73aa7e8a3bdbd5aff0a8b4502f5bee5b72ad82                         |                                                              |
| take\_amt         | VARCHAR   | 2283105000000000000000                                             |                                                              |
| give\_amt         | VARCHAR   | 5500000000000000000                                                |                                                              |
| timestamp         | VARCHAR   | 1599132357                                                         |                                                              |

## 19. Table: MatchingMarket\_v2\_event\_LogTrade\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-23 20:15:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10324136                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8b19be59994318053ff8e25bd0f8f1ad7edac127e8ec2a000ff30ca4e5497aea | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 143                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794e6e91555438afc3ccf1c5076a74f42133d08d                         | Address of the contract that produced the log                |
| pay\_amt          | VARCHAR   | 1722652851260300428356                                             |                                                              |
| pay\_gem          | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         |                                                              |
| buy\_amt          | VARCHAR   | 6815154828597549081697                                             |                                                              |
| buy\_gem          | VARCHAR   | 0x0d8775f648430679a709e98d2b0cb6250d2887ef                         |                                                              |
