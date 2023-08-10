# exactly

## 1. Table: ExactlyMarketDAI\_event\_BorrowAtMaturity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-31 18:24:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15869812                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3ccae36e85e3b5c310b97398b288058c5e666a91b0e7766ea98812ef57ae456c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 298                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x163538e22f4d38c1eb21b79939f3d2ee274198ff                         | Address of the contract that produced the log                |
| maturity          | VARCHAR   | 1669248000                                                         |                                                              |
| caller            | VARCHAR   | 0xb999d16abd6bec7f8eb2454df58bf2ea053005ca                         |                                                              |
| receiver          | VARCHAR   | 0xb999d16abd6bec7f8eb2454df58bf2ea053005ca                         |                                                              |
| borrower          | VARCHAR   | 0xb999d16abd6bec7f8eb2454df58bf2ea053005ca                         |                                                              |
| assets            | VARCHAR   | 50000000000000000000                                               |                                                              |
| fee               | VARCHAR   | 221390735953029300                                                 |                                                              |

## 2. Table: ExactlyMarketDAI\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-02 03:51:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16538556                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb1c8dcf05cc2177bc7a5afc364081c28b350b67bc8e8f1cfbec09873d98ca33f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 217                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x163538e22f4d38c1eb21b79939f3d2ee274198ff                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x586634c272dfa3894ee9b99836541dee35660f34                         |                                                              |
| receiver          | VARCHAR   | 0x586634c272dfa3894ee9b99836541dee35660f34                         |                                                              |
| borrower          | VARCHAR   | 0x586634c272dfa3894ee9b99836541dee35660f34                         |                                                              |
| assets            | VARCHAR   | 750000000000000000000                                              |                                                              |
| shares            | VARCHAR   | 744819600413944490597                                              |                                                              |

## 3. Table: ExactlyMarketDAI\_event\_DepositAtMaturity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-11 08:32:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16604348                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xacf87efe6f4e15f40699c6679f7708cdb8e28829455f5fe7e9b0415cb843dc53 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 144                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x163538e22f4d38c1eb21b79939f3d2ee274198ff                         | Address of the contract that produced the log                |
| maturity          | VARCHAR   | 1676505600                                                         |                                                              |
| caller            | VARCHAR   | 0xc76a51e1d29771c846828e21ed4de04dea76b748                         |                                                              |
| owner             | VARCHAR   | 0xc76a51e1d29771c846828e21ed4de04dea76b748                         |                                                              |
| assets            | VARCHAR   | 101000000000000000000                                              |                                                              |
| fee               | VARCHAR   | 3167333840870711                                                   |                                                              |

## 4. Table: ExactlyMarketDAI\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-26 04:52:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16266659                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd126aaf57de1cdfdf8d10c45312ca7a4224486d3fd2f46c66ef0dfcda542df42 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 151                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x163538e22f4d38c1eb21b79939f3d2ee274198ff                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x83a05e2f45105d88ea0f505544cd8df0b547c1d0                         |                                                              |
| owner             | VARCHAR   | 0x83a05e2f45105d88ea0f505544cd8df0b547c1d0                         |                                                              |
| assets            | VARCHAR   | 1101000000000000000000                                             |                                                              |
| shares            | VARCHAR   | 1099844341344783001984                                             |                                                              |

## 5. Table: ExactlyMarketDAI\_event\_Liquidate\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| receiver          | VARCHAR   |                                                              |             |
| borrower          | VARCHAR   |                                                              |             |
| assets            | VARCHAR   |                                                              |             |
| lendersAssets     | VARCHAR   |                                                              |             |
| seizeMarket       | VARCHAR   |                                                              |             |
| seizedAssets      | VARCHAR   |                                                              |             |

## 6. Table: ExactlyMarketDAI\_event\_RepayAtMaturity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-19 21:39:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16443589                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9ed08b5fb6cb75bd78f38dc3bb53b76ce729b92523c7e4511bcb0148b0f57e3d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 264                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x163538e22f4d38c1eb21b79939f3d2ee274198ff                         | Address of the contract that produced the log                |
| maturity          | VARCHAR   | 1674086400                                                         |                                                              |
| caller            | VARCHAR   | 0x9a38d7d4b5e45e98dc08481bb9a223750987dc5e                         |                                                              |
| borrower          | VARCHAR   | 0x9a38d7d4b5e45e98dc08481bb9a223750987dc5e                         |                                                              |
| assets            | VARCHAR   | 306573420133773190306                                              |                                                              |
| positionAssets    | VARCHAR   | 301138771512618231600                                              |                                                              |

## 7. Table: ExactlyMarketDAI\_event\_Repay\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-19 21:59:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16443687                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xda9339b5ec90f8917520f777c1b4bff7869a0299ea08ae99f47630d2e749ab3c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 106                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x163538e22f4d38c1eb21b79939f3d2ee274198ff                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x9a38d7d4b5e45e98dc08481bb9a223750987dc5e                         |                                                              |
| borrower          | VARCHAR   | 0x9a38d7d4b5e45e98dc08481bb9a223750987dc5e                         |                                                              |
| assets            | VARCHAR   | 100325725662030935908                                              |                                                              |
| shares            | VARCHAR   | 99716805594727444101                                               |                                                              |

## 8. Table: ExactlyMarketDAI\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-03 19:55:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17836687                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6e33f66515d5185d69a88e4ec047258f14dc4f6b477aed062993b7f43da0f76c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 271                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x163538e22f4d38c1eb21b79939f3d2ee274198ff                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x8a6134ecba73d51f64794f93c6d0c057893d328d                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| amount            | VARCHAR   | 87946657403882204460830                                            |                                                              |

## 9. Table: ExactlyMarketDAI\_event\_WithdrawAtMaturity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-23 10:27:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16246820                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3e58ca319cc66598f1ba45c079928dae9cdb24ac03c3cc0c958abe065f7bce1d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 129                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x163538e22f4d38c1eb21b79939f3d2ee274198ff                         | Address of the contract that produced the log                |
| maturity          | VARCHAR   | 1671667200                                                         |                                                              |
| caller            | VARCHAR   | 0x9a38d7d4b5e45e98dc08481bb9a223750987dc5e                         |                                                              |
| receiver          | VARCHAR   | 0x9a38d7d4b5e45e98dc08481bb9a223750987dc5e                         |                                                              |
| owner             | VARCHAR   | 0x9a38d7d4b5e45e98dc08481bb9a223750987dc5e                         |                                                              |
| positionAssets    | VARCHAR   | 502333403298171419665                                              |                                                              |
| assets            | VARCHAR   | 502333403298171419665                                              |                                                              |

## 10. Table: ExactlyMarketDAI\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-21 10:54:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17094303                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0cdfe63232681c8c69ace437c4df424cef0942de292dde1e2ddd3862220404ea | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 96                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x163538e22f4d38c1eb21b79939f3d2ee274198ff                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x789c8ab61f73b2dc3a45dec67b63e46de1666503                         |                                                              |
| receiver          | VARCHAR   | 0x789c8ab61f73b2dc3a45dec67b63e46de1666503                         |                                                              |
| owner             | VARCHAR   | 0x789c8ab61f73b2dc3a45dec67b63e46de1666503                         |                                                              |
| assets            | VARCHAR   | 1276344341946759970615                                             |                                                              |
| shares            | VARCHAR   | 1265475055936028634556                                             |                                                              |

## 11. Table: ExactlyMarketUSDC\_event\_BorrowAtMaturity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-23 06:47:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16467804                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xffdcad47e1caff087b4d6ec9ae5866d33d4a4723ebd9653b0197c3df8552c6a8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 137                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x660e2fc185a9ffe722af253329ceaad4c9f6f928                         | Address of the contract that produced the log                |
| maturity          | VARCHAR   | 1681344000                                                         |                                                              |
| caller            | VARCHAR   | 0xff180948d613baba1959b8d8c9e96b94959828f9                         |                                                              |
| receiver          | VARCHAR   | 0xff180948d613baba1959b8d8c9e96b94959828f9                         |                                                              |
| borrower          | VARCHAR   | 0xff180948d613baba1959b8d8c9e96b94959828f9                         |                                                              |
| assets            | VARCHAR   | 600000000                                                          |                                                              |
| fee               | VARCHAR   | 224295                                                             |                                                              |

## 12. Table: ExactlyMarketUSDC\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-23 02:15:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16466451                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd59bb678d00b3ce0832166b94c4734dd90aac77c96e50655689d1575c6a1df65 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 164                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x660e2fc185a9ffe722af253329ceaad4c9f6f928                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0xff180948d613baba1959b8d8c9e96b94959828f9                         |                                                              |
| receiver          | VARCHAR   | 0xff180948d613baba1959b8d8c9e96b94959828f9                         |                                                              |
| borrower          | VARCHAR   | 0xff180948d613baba1959b8d8c9e96b94959828f9                         |                                                              |
| assets            | VARCHAR   | 600000000                                                          |                                                              |
| shares            | VARCHAR   | 598391605                                                          |                                                              |

## 13. Table: ExactlyMarketUSDC\_event\_DepositAtMaturity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-02 03:03:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16738092                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6e14a390bf48e141f01cc7e4a418f54c8282b83c585127d5aea540631f289353 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 83                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x660e2fc185a9ffe722af253329ceaad4c9f6f928                         | Address of the contract that produced the log                |
| maturity          | VARCHAR   | 1678924800                                                         |                                                              |
| caller            | VARCHAR   | 0x5853ed4f26a3fcea565b3fbc698bb19cdf6deb85                         |                                                              |
| owner             | VARCHAR   | 0x5853ed4f26a3fcea565b3fbc698bb19cdf6deb85                         |                                                              |
| assets            | VARCHAR   | 1000000                                                            |                                                              |
| fee               | VARCHAR   | 109                                                                |                                                              |

## 14. Table: ExactlyMarketUSDC\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-12 09:41:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16611849                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf31fa73373ca0107e615b9eed8ce74cd1680c7461e97646f888a0e262e71dae4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 107                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x660e2fc185a9ffe722af253329ceaad4c9f6f928                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x32eb30cae36e1c2e9271ca1c02da64e5c27cb465                         |                                                              |
| owner             | VARCHAR   | 0x32eb30cae36e1c2e9271ca1c02da64e5c27cb465                         |                                                              |
| assets            | VARCHAR   | 502931064                                                          |                                                              |
| shares            | VARCHAR   | 502319143                                                          |                                                              |

## 15. Table: ExactlyMarketUSDC\_event\_Liquidate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-18 21:34:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15999613                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1c0fd335988125332c29dab7543457a42d592bb8eed4ad3b583dfd44351cf86a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 66                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x660e2fc185a9ffe722af253329ceaad4c9f6f928                         | Address of the contract that produced the log                |
| receiver          | VARCHAR   | 0x98f4df6736aa6c5d26f0f9678102376ac06b55d4                         |                                                              |
| borrower          | VARCHAR   | 0xd64c36ff379816dc40043ac64c7c83a360f2359c                         |                                                              |
| assets            | VARCHAR   | 262723669                                                          |                                                              |
| lendersAssets     | VARCHAR   | 656809                                                             |                                                              |
| seizeMarket       | VARCHAR   | 0x163538e22f4d38c1eb21b79939f3d2ee274198ff                         |                                                              |
| seizedAssets      | VARCHAR   | 278241996565583461283                                              |                                                              |

## 16. Table: ExactlyMarketUSDC\_event\_RepayAtMaturity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-07 12:22:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17428469                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd9a0a3c16b16b0174cbe9fb0a45377c9b269fdae8afb19f4bb0effa7f91609f0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 72                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x660e2fc185a9ffe722af253329ceaad4c9f6f928                         | Address of the contract that produced the log                |
| maturity          | VARCHAR   | 1681344000                                                         |                                                              |
| caller            | VARCHAR   | 0x8149dc18d39fdba137e43c871e7801e7cf566d41                         |                                                              |
| borrower          | VARCHAR   | 0x8149dc18d39fdba137e43c871e7801e7cf566d41                         |                                                              |
| assets            | VARCHAR   | 625197721                                                          |                                                              |
| positionAssets    | VARCHAR   | 500229981                                                          |                                                              |

## 17. Table: ExactlyMarketUSDC\_event\_Repay\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-16 10:00:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16839678                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xed27c233d55927c2f579db5fdaf4911335b9c6c26a3a7ab604142051533b1edb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 376                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x660e2fc185a9ffe722af253329ceaad4c9f6f928                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x26fdc242eccc144971e558ff458a4ec21b75d4e8                         |                                                              |
| borrower          | VARCHAR   | 0x26fdc242eccc144971e558ff458a4ec21b75d4e8                         |                                                              |
| assets            | VARCHAR   | 601157091                                                          |                                                              |
| shares            | VARCHAR   | 598211307                                                          |                                                              |

## 18. Table: ExactlyMarketUSDC\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-20 07:39:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16446578                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3094ad0ea93ede08e28bfb7c37df59c0798bab467e3ba08f72614864911e3bff | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 129                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x660e2fc185a9ffe722af253329ceaad4c9f6f928                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xff180948d613baba1959b8d8c9e96b94959828f9                         |                                                              |
| amount            | VARCHAR   | 249773213                                                          |                                                              |

## 19. Table: ExactlyMarketUSDC\_event\_WithdrawAtMaturity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-24 19:13:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16478683                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1a31a3df42da8e7942c093594f59d7a594b20d37d4bb15e6991340735f5fdd7e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 237                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x660e2fc185a9ffe722af253329ceaad4c9f6f928                         | Address of the contract that produced the log                |
| maturity          | VARCHAR   | 1669248000                                                         |                                                              |
| caller            | VARCHAR   | 0xfff70e29029dab2393f165d0c0b830dc53d40e25                         |                                                              |
| receiver          | VARCHAR   | 0xfff70e29029dab2393f165d0c0b830dc53d40e25                         |                                                              |
| owner             | VARCHAR   | 0xfff70e29029dab2393f165d0c0b830dc53d40e25                         |                                                              |
| positionAssets    | VARCHAR   | 1000106079                                                         |                                                              |
| assets            | VARCHAR   | 1000106079                                                         |                                                              |

## 20. Table: ExactlyMarketUSDC\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-28 13:51:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17357928                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb2688159d0e2206513c213ca7b58a6ec8042194148332d04ccc64cbeae549561 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 324                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x660e2fc185a9ffe722af253329ceaad4c9f6f928                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0xbebdfd8683f88ceb04c2d8be56ec244106c0d8e2                         |                                                              |
| receiver          | VARCHAR   | 0xbebdfd8683f88ceb04c2d8be56ec244106c0d8e2                         |                                                              |
| owner             | VARCHAR   | 0xbebdfd8683f88ceb04c2d8be56ec244106c0d8e2                         |                                                              |
| assets            | VARCHAR   | 503034105                                                          |                                                              |
| shares            | VARCHAR   | 498788925                                                          |                                                              |

## 21. Table: ExactlyMarketWBTC\_event\_BorrowAtMaturity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-11 02:08:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15943699                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe62bb2a8c1dc68f88b2a48887cad91529c6bfc0775db9af157a93ddd24d53a65 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 162                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8644c0fded361d1920e068ba4b09996e26729435                         | Address of the contract that produced the log                |
| maturity          | VARCHAR   | 1671667200                                                         |                                                              |
| caller            | VARCHAR   | 0x9a38d7d4b5e45e98dc08481bb9a223750987dc5e                         |                                                              |
| receiver          | VARCHAR   | 0x9a38d7d4b5e45e98dc08481bb9a223750987dc5e                         |                                                              |
| borrower          | VARCHAR   | 0x9a38d7d4b5e45e98dc08481bb9a223750987dc5e                         |                                                              |
| assets            | VARCHAR   | 2000000                                                            |                                                              |
| fee               | VARCHAR   | 7125                                                               |                                                              |

## 22. Table: ExactlyMarketWBTC\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-06 19:21:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15913035                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb80c1a326bbf975e058218007bd4fb85dd86d5cdec2efe023a65fbcbed420e52 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 370                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8644c0fded361d1920e068ba4b09996e26729435                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x9a38d7d4b5e45e98dc08481bb9a223750987dc5e                         |                                                              |
| receiver          | VARCHAR   | 0x9a38d7d4b5e45e98dc08481bb9a223750987dc5e                         |                                                              |
| borrower          | VARCHAR   | 0x9a38d7d4b5e45e98dc08481bb9a223750987dc5e                         |                                                              |
| assets            | VARCHAR   | 1000000                                                            |                                                              |
| shares            | VARCHAR   | 999828                                                             |                                                              |

## 23. Table: ExactlyMarketWBTC\_event\_DepositAtMaturity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-08 23:53:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15928720                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4b6ee9903664584f98a88acdb0aaa36bc709b966af4c4f9099af83a918cc9736 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 302                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8644c0fded361d1920e068ba4b09996e26729435                         | Address of the contract that produced the log                |
| maturity          | VARCHAR   | 1669248000                                                         |                                                              |
| caller            | VARCHAR   | 0x9a38d7d4b5e45e98dc08481bb9a223750987dc5e                         |                                                              |
| owner             | VARCHAR   | 0x9a38d7d4b5e45e98dc08481bb9a223750987dc5e                         |                                                              |
| assets            | VARCHAR   | 9300000                                                            |                                                              |
| fee               | VARCHAR   | 199863                                                             |                                                              |

## 24. Table: ExactlyMarketWBTC\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-16 17:47:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16420942                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x404410cd829bd0e91cd103f1f6fca295c92649b055158c9268f60df954977fc4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 183                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8644c0fded361d1920e068ba4b09996e26729435                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x5d1124fb77c539ec92e3ef853053bbce1e98271b                         |                                                              |
| owner             | VARCHAR   | 0x5d1124fb77c539ec92e3ef853053bbce1e98271b                         |                                                              |
| assets            | VARCHAR   | 400000000                                                          |                                                              |
| shares            | VARCHAR   | 397985175                                                          |                                                              |

## 25. Table: ExactlyMarketWBTC\_event\_Liquidate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-20 22:43:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17523950                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7818cf3b09f5ae6dc07b6ba6fe66d4746d6b4dfae0e7b9b8a82137123bc58f0c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 52                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8644c0fded361d1920e068ba4b09996e26729435                         | Address of the contract that produced the log                |
| receiver          | VARCHAR   | 0x98f4df6736aa6c5d26f0f9678102376ac06b55d4                         |                                                              |
| borrower          | VARCHAR   | 0x9f61823ea509cc7817601a9734c915b4f53d5c69                         |                                                              |
| assets            | VARCHAR   | 2503725                                                            |                                                              |
| lendersAssets     | VARCHAR   | 6259                                                               |                                                              |
| seizeMarket       | VARCHAR   | 0x3843c41da1d7909c86fad51c47b9a97cf62a29e1                         |                                                              |
| seizedAssets      | VARCHAR   | 366158463753113938                                                 |                                                              |

## 26. Table: ExactlyMarketWBTC\_event\_RepayAtMaturity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-17 15:02:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16649187                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf1586830f9bd0e00d16aff0e69261a10bd021ee74befa3a7f689cf88878fbae8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 231                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8644c0fded361d1920e068ba4b09996e26729435                         | Address of the contract that produced the log                |
| maturity          | VARCHAR   | 1676505600                                                         |                                                              |
| caller            | VARCHAR   | 0x9a38d7d4b5e45e98dc08481bb9a223750987dc5e                         |                                                              |
| borrower          | VARCHAR   | 0x9a38d7d4b5e45e98dc08481bb9a223750987dc5e                         |                                                              |
| assets            | VARCHAR   | 2067668                                                            |                                                              |
| positionAssets    | VARCHAR   | 2002510                                                            |                                                              |

## 27. Table: ExactlyMarketWBTC\_event\_Repay\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-25 19:30:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16049096                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcca337d679b3617d1fca78a979401630fb5ee8bec79eb64aa1e4b7a1f049ca25 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 128                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8644c0fded361d1920e068ba4b09996e26729435                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x8a6134ecba73d51f64794f93c6d0c057893d328d                         |                                                              |
| borrower          | VARCHAR   | 0x8a6134ecba73d51f64794f93c6d0c057893d328d                         |                                                              |
| assets            | VARCHAR   | 195212656                                                          |                                                              |
| shares            | VARCHAR   | 194850268                                                          |                                                              |

## 28. Table: ExactlyMarketWBTC\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-04 00:34:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15893099                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1f166f6f1c48d5b2a1dc7624cf9df77c597a51aca40577be1ab8e3ccd4ed3822 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 172                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8644c0fded361d1920e068ba4b09996e26729435                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x9a38d7d4b5e45e98dc08481bb9a223750987dc5e                         |                                                              |
| amount            | VARCHAR   | 5000000                                                            |                                                              |

## 29. Table: ExactlyMarketWBTC\_event\_WithdrawAtMaturity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-28 05:18:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16724533                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6d3a0cc291b246493ec4d89fef489ad45e755013d6d83a1a46b0ab1693957cf6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 314                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8644c0fded361d1920e068ba4b09996e26729435                         | Address of the contract that produced the log                |
| maturity          | VARCHAR   | 1676505600                                                         |                                                              |
| caller            | VARCHAR   | 0x1e7561744b07906968fe38f13547a6d73300f9b3                         |                                                              |
| receiver          | VARCHAR   | 0x1e7561744b07906968fe38f13547a6d73300f9b3                         |                                                              |
| owner             | VARCHAR   | 0x1e7561744b07906968fe38f13547a6d73300f9b3                         |                                                              |
| positionAssets    | VARCHAR   | 474699                                                             |                                                              |
| assets            | VARCHAR   | 474699                                                             |                                                              |

## 30. Table: ExactlyMarketWBTC\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-28 10:19:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16504678                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0a2742a6aa3dcab63bf0ac5dad5547999e12875250aa27b37f3f3c4b09fa4f17 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 158                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8644c0fded361d1920e068ba4b09996e26729435                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0xc8884ede1ae44bdff60da4b9c542c34a69648a87                         |                                                              |
| receiver          | VARCHAR   | 0x5ecfa1580d2c080d7ed1ccb602f567390bacc53d                         |                                                              |
| owner             | VARCHAR   | 0xc8884ede1ae44bdff60da4b9c542c34a69648a87                         |                                                              |
| assets            | VARCHAR   | 136792                                                             |                                                              |
| shares            | VARCHAR   | 136097                                                             |                                                              |

## 31. Table: ExactlyMarketWETH\_event\_BorrowAtMaturity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-03 22:19:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15892427                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x47035fa97c5796f0838dd8723d6f96eb8f6c2f188fb16d5136c89fcc3362521e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 478                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc4d4500326981eacd020e20a81b1c479c161c7ef                         | Address of the contract that produced the log                |
| maturity          | VARCHAR   | 1669248000                                                         |                                                              |
| caller            | VARCHAR   | 0x29babff3eba7b517a75109ea8fd6d1eab4a10258                         |                                                              |
| receiver          | VARCHAR   | 0x29babff3eba7b517a75109ea8fd6d1eab4a10258                         |                                                              |
| borrower          | VARCHAR   | 0xb999d16abd6bec7f8eb2454df58bf2ea053005ca                         |                                                              |
| assets            | VARCHAR   | 1000000000000000000                                                |                                                              |
| fee               | VARCHAR   | 9294871326815572                                                   |                                                              |

## 32. Table: ExactlyMarketWETH\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-07 17:57:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15919787                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8f9fc2a496831a53ebe17b123af8a92b7e8d553f6f925af0890fc871d6825177 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 266                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc4d4500326981eacd020e20a81b1c479c161c7ef                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x29babff3eba7b517a75109ea8fd6d1eab4a10258                         |                                                              |
| receiver          | VARCHAR   | 0x29babff3eba7b517a75109ea8fd6d1eab4a10258                         |                                                              |
| borrower          | VARCHAR   | 0x4ba0cf5477e2e29cfa603b2280fd9848e3ec80e1                         |                                                              |
| assets            | VARCHAR   | 1000000000000000000                                                |                                                              |
| shares            | VARCHAR   | 999514805820409814                                                 |                                                              |

## 33. Table: ExactlyMarketWETH\_event\_DepositAtMaturity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-12 02:28:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15950952                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8595d3a5bc678ad774439ec474ef88f44c381cd6503d02b4b50a73429d83d1f9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 107                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc4d4500326981eacd020e20a81b1c479c161c7ef                         | Address of the contract that produced the log                |
| maturity          | VARCHAR   | 1671667200                                                         |                                                              |
| caller            | VARCHAR   | 0x29babff3eba7b517a75109ea8fd6d1eab4a10258                         |                                                              |
| owner             | VARCHAR   | 0xe6ea861295af4e0d0d7f331c7b950f7da3a9d265                         |                                                              |
| assets            | VARCHAR   | 100000000000000000                                                 |                                                              |
| fee               | VARCHAR   | 341793931247552                                                    |                                                              |

## 34. Table: ExactlyMarketWETH\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-19 21:17:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16443481                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfab0a5b1009034a2f121fc0dca4d877527f3fa298c0ba4c936b0ff797e99920d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 287                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc4d4500326981eacd020e20a81b1c479c161c7ef                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x29babff3eba7b517a75109ea8fd6d1eab4a10258                         |                                                              |
| owner             | VARCHAR   | 0xc0ffee22f360792a89db39f159f103daafe9c57d                         |                                                              |
| assets            | VARCHAR   | 1000000000000000000                                                |                                                              |
| shares            | VARCHAR   | 998676267491857413                                                 |                                                              |

## 35. Table: ExactlyMarketWETH\_event\_Liquidate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-14 00:44:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16401539                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x518bbfe6d319eecd3cd560d9e67f5fa8ef1c020348698ebd61e8229996550b0a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 295                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc4d4500326981eacd020e20a81b1c479c161c7ef                         | Address of the contract that produced the log                |
| receiver          | VARCHAR   | 0x98f4df6736aa6c5d26f0f9678102376ac06b55d4                         |                                                              |
| borrower          | VARCHAR   | 0x767a60f295aedd958932088f9cd6a4951d8739b6                         |                                                              |
| assets            | VARCHAR   | 591372026309563010                                                 |                                                              |
| lendersAssets     | VARCHAR   | 1478430065773907                                                   |                                                              |
| seizeMarket       | VARCHAR   | 0x660e2fc185a9ffe722af253329ceaad4c9f6f928                         |                                                              |
| seizedAssets      | VARCHAR   | 966345423                                                          |                                                              |

## 36. Table: ExactlyMarketWETH\_event\_RepayAtMaturity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-16 03:44:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16416746                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x413a56ffe5e4d02e25e1a1c4bddd82acdfb34362896e36bdff05e1b27343bcf6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 245                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc4d4500326981eacd020e20a81b1c479c161c7ef                         | Address of the contract that produced the log                |
| maturity          | VARCHAR   | 1678924800                                                         |                                                              |
| caller            | VARCHAR   | 0x29babff3eba7b517a75109ea8fd6d1eab4a10258                         |                                                              |
| borrower          | VARCHAR   | 0x767a60f295aedd958932088f9cd6a4951d8739b6                         |                                                              |
| assets            | VARCHAR   | 408798298611983073                                                 |                                                              |
| positionAssets    | VARCHAR   | 409641885011277433                                                 |                                                              |

## 37. Table: ExactlyMarketWETH\_event\_Repay\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-02 10:03:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16740167                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2012d4c69c4b59a68d47f34134be70d32047578ce59234397ce341547ef6b80a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 209                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc4d4500326981eacd020e20a81b1c479c161c7ef                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x29babff3eba7b517a75109ea8fd6d1eab4a10258                         |                                                              |
| borrower          | VARCHAR   | 0x21e75bd06d45dafc0c73b72edcfcc34f51a5d9a0                         |                                                              |
| assets            | VARCHAR   | 35063401344582267                                                  |                                                              |
| shares            | VARCHAR   | 34874921710530632                                                  |                                                              |

## 38. Table: ExactlyMarketWETH\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-21 07:31:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17740043                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7b2ff4a54c8dc34ee8cce714f07d3de0e79364d96c64693ba8c9831c0243fa42 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 310                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc4d4500326981eacd020e20a81b1c479c161c7ef                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x1bda0a00d113eee140757aa5603c7cca15295153                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| amount            | VARCHAR   | 99420863563237578                                                  |                                                              |

## 39. Table: ExactlyMarketWETH\_event\_WithdrawAtMaturity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-17 14:55:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16649154                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x71b885edc5db47b1ea7af3d6024adc3d9294e95d66c839941db10f3df644ccae | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 186                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc4d4500326981eacd020e20a81b1c479c161c7ef                         | Address of the contract that produced the log                |
| maturity          | VARCHAR   | 1676505600                                                         |                                                              |
| caller            | VARCHAR   | 0x29babff3eba7b517a75109ea8fd6d1eab4a10258                         |                                                              |
| receiver          | VARCHAR   | 0x29babff3eba7b517a75109ea8fd6d1eab4a10258                         |                                                              |
| owner             | VARCHAR   | 0x9a38d7d4b5e45e98dc08481bb9a223750987dc5e                         |                                                              |
| positionAssets    | VARCHAR   | 450168522769168384                                                 |                                                              |
| assets            | VARCHAR   | 450168522769168384                                                 |                                                              |

## 40. Table: ExactlyMarketWETH\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-02 23:42:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15885685                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3c8a9510d2ea87502f0c4010400be9b0de97e6b62a0c329cef8c1871d320ac0e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 50                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc4d4500326981eacd020e20a81b1c479c161c7ef                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x660e2fc185a9ffe722af253329ceaad4c9f6f928                         |                                                              |
| receiver          | VARCHAR   | 0x6c6b87d44d239b3750bf9badce26a9a0a3d2364e                         |                                                              |
| owner             | VARCHAR   | 0xb999d16abd6bec7f8eb2454df58bf2ea053005ca                         |                                                              |
| assets            | VARCHAR   | 839087628297186799                                                 |                                                              |
| shares            | VARCHAR   | 839038840471528946                                                 |                                                              |

## 41. Table: ExactlyMarketWstETH\_event\_BorrowAtMaturity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-03 22:36:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15892513                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3a0e122d9ef7d1d1d43a66fb76dc41306e96dd5fb62fadd5d285329e893fc0ea | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 139                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3843c41da1d7909c86fad51c47b9a97cf62a29e1                         | Address of the contract that produced the log                |
| maturity          | VARCHAR   | 1674086400                                                         |                                                              |
| caller            | VARCHAR   | 0xb999d16abd6bec7f8eb2454df58bf2ea053005ca                         |                                                              |
| receiver          | VARCHAR   | 0xb999d16abd6bec7f8eb2454df58bf2ea053005ca                         |                                                              |
| borrower          | VARCHAR   | 0xb999d16abd6bec7f8eb2454df58bf2ea053005ca                         |                                                              |
| assets            | VARCHAR   | 400000000000000000                                                 |                                                              |
| fee               | VARCHAR   | 8821829201267246                                                   |                                                              |

## 42. Table: ExactlyMarketWstETH\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-02 15:52:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16741884                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb916a40482cf1c8d491f1ae1f1067ee1019a180e4e8f2dac9e43f1ae7cb4995f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 278                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3843c41da1d7909c86fad51c47b9a97cf62a29e1                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x7a65824d74b0c20730b6ee4929abcc41cbe843aa                         |                                                              |
| receiver          | VARCHAR   | 0x0000000000000000000000000000000000000666                         |                                                              |
| borrower          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| assets            | VARCHAR   | 0                                                                  |                                                              |
| shares            | VARCHAR   | 0                                                                  |                                                              |

## 43. Table: ExactlyMarketWstETH\_event\_DepositAtMaturity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-15 19:49:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15977621                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc446821d6e945d144b060004070868ea25cff58c33351b12e2ea775851b5d9ef | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 56                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3843c41da1d7909c86fad51c47b9a97cf62a29e1                         | Address of the contract that produced the log                |
| maturity          | VARCHAR   | 1674086400                                                         |                                                              |
| caller            | VARCHAR   | 0x93cea50fbce3b97146698e1e07f0b1ada810bfd7                         |                                                              |
| owner             | VARCHAR   | 0x93cea50fbce3b97146698e1e07f0b1ada810bfd7                         |                                                              |
| assets            | VARCHAR   | 500000000000000000                                                 |                                                              |
| fee               | VARCHAR   | 1213051006389844                                                   |                                                              |

## 44. Table: ExactlyMarketWstETH\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-03 19:33:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15891603                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe809c4f7b3f3f9ac440d070bd0cd806040f4823d4f43bbc0d6fea45481e4d8ad | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 211                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3843c41da1d7909c86fad51c47b9a97cf62a29e1                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0xb999d16abd6bec7f8eb2454df58bf2ea053005ca                         |                                                              |
| owner             | VARCHAR   | 0xb999d16abd6bec7f8eb2454df58bf2ea053005ca                         |                                                              |
| assets            | VARCHAR   | 2970000000000000000                                                |                                                              |
| shares            | VARCHAR   | 2969468570996093260                                                |                                                              |

## 45. Table: ExactlyMarketWstETH\_event\_Liquidate\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| receiver          | VARCHAR   |                                                              |             |
| borrower          | VARCHAR   |                                                              |             |
| assets            | VARCHAR   |                                                              |             |
| lendersAssets     | VARCHAR   |                                                              |             |
| seizeMarket       | VARCHAR   |                                                              |             |
| seizedAssets      | VARCHAR   |                                                              |             |

## 46. Table: ExactlyMarketWstETH\_event\_RepayAtMaturity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-23 10:24:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16246806                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x06d320572c2b642887acb39f6eb2e3b7a9e61a8390a5be39e73739db2e46520d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 34                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3843c41da1d7909c86fad51c47b9a97cf62a29e1                         | Address of the contract that produced the log                |
| maturity          | VARCHAR   | 1671667200                                                         |                                                              |
| caller            | VARCHAR   | 0x9a38d7d4b5e45e98dc08481bb9a223750987dc5e                         |                                                              |
| borrower          | VARCHAR   | 0x9a38d7d4b5e45e98dc08481bb9a223750987dc5e                         |                                                              |
| assets            | VARCHAR   | 206488090833271912                                                 |                                                              |
| positionAssets    | VARCHAR   | 200731059009168839                                                 |                                                              |

## 47. Table: ExactlyMarketWstETH\_event\_Repay\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-31 20:12:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15870351                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x157b583a328f5fd58906a095b5fe8b76000b1c16edd32b8a47f19cfa49afc1ec | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 241                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3843c41da1d7909c86fad51c47b9a97cf62a29e1                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0xb999d16abd6bec7f8eb2454df58bf2ea053005ca                         |                                                              |
| borrower          | VARCHAR   | 0xb999d16abd6bec7f8eb2454df58bf2ea053005ca                         |                                                              |
| assets            | VARCHAR   | 40000000000000000                                                  |                                                              |
| shares            | VARCHAR   | 39999895331204691                                                  |                                                              |

## 48. Table: ExactlyMarketWstETH\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-01 13:52:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17599618                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1fd569c84873a6701ef51d32580cba6b7df74c52de5be86457a4d6696227fde4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 306                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3843c41da1d7909c86fad51c47b9a97cf62a29e1                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x1d59bcc9836c6fda59cc240827232de9007f80f4                         |                                                              |
| amount            | VARCHAR   | 10320304322472488423                                               |                                                              |

## 49. Table: ExactlyMarketWstETH\_event\_WithdrawAtMaturity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-23 15:31:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16033609                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x763b3fee870c4084d3d6e3bb80948e7bfa3c851305e88b55ca0bfc171c4fd4e0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 166                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3843c41da1d7909c86fad51c47b9a97cf62a29e1                         | Address of the contract that produced the log                |
| maturity          | VARCHAR   | 1669248000                                                         |                                                              |
| caller            | VARCHAR   | 0xb999d16abd6bec7f8eb2454df58bf2ea053005ca                         |                                                              |
| receiver          | VARCHAR   | 0xb999d16abd6bec7f8eb2454df58bf2ea053005ca                         |                                                              |
| owner             | VARCHAR   | 0xb999d16abd6bec7f8eb2454df58bf2ea053005ca                         |                                                              |
| positionAssets    | VARCHAR   | 802545245799413579                                                 |                                                              |
| assets            | VARCHAR   | 802540451188496352                                                 |                                                              |

## 50. Table: ExactlyMarketWstETH\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-27 15:43:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16720495                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1cace1bf037e12b6322c57acc71a20b3031174458451bbf247a5512081d12018 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 126                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3843c41da1d7909c86fad51c47b9a97cf62a29e1                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x8a6134ecba73d51f64794f93c6d0c057893d328d                         |                                                              |
| receiver          | VARCHAR   | 0x8a6134ecba73d51f64794f93c6d0c057893d328d                         |                                                              |
| owner             | VARCHAR   | 0x8a6134ecba73d51f64794f93c6d0c057893d328d                         |                                                              |
| assets            | VARCHAR   | 30000000000000000000                                               |                                                              |
| shares            | VARCHAR   | 29936932603354652316                                               |                                                              |
