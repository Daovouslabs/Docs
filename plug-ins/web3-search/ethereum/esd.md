# esd

## 1. Table: Implementation\_event\_Advance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-13 08:00:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12624901                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x099bba40b1f4b3c4ea7d8313408dd1808e8a32180d7889f0f0b2072af7746e3c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x443d2f2755db5942601fa062cc248aaa153313d3                         | Address of the contract that produced the log                |
| epoch             | VARCHAR   | 848                                                                |                                                              |
| block             | VARCHAR   | 12624901                                                           |                                                              |
| timestamp         | VARCHAR   | 1623571201                                                         |                                                              |

## 2. Table: Implementation\_event\_Bond\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-14 11:59:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11854681                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xffba79d7015ad7ba5400783f08abf20a7ae3a6121036e995a88bd0a2c63e88a1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 107                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x443d2f2755db5942601fa062cc248aaa153313d3                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x43719c2b68685ddf182644229098acef7c840f16                         |                                                              |
| start             | VARCHAR   | 492                                                                |                                                              |
| value             | VARCHAR   | 136283601956959502904693                                           |                                                              |
| valueUnderlying   | VARCHAR   | 41645351588678944092115                                            |                                                              |

## 3. Table: Implementation\_event\_Commit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-19 08:18:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16002818                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc1824b00279b8bb2ae93cad3ffed50a23f74e9c803b3c0de86b284bb3089bf7d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 86                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x443d2f2755db5942601fa062cc248aaa153313d3                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x1bba92f379375387bf8f927058da14d47464cb7a                         |                                                              |
| candidate         | VARCHAR   | 0xdc8c5d7645a7a1b4968ec9e1d983940a259b0adf                         |                                                              |

## 4. Table: Implementation\_event\_CouponApproval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-20 19:40:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11694321                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd17b9658be8e31b000a99e3c23493f1721ae67ed3129ab5ec66a899a4cdedb4b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 274                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x443d2f2755db5942601fa062cc248aaa153313d3                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x7cfed2a2d4a98680dac6aa55120f5af2ec562ebd                         |                                                              |
| spender           | VARCHAR   | 0xb4027eeea4b2d91616c63dc3e37075e69f36b457                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 5. Table: Implementation\_event\_CouponExpiration\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-20 16:00:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11295945                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2750adbd949767b0c274f1f482fc90cba8679954c097368bc029dbb23552b2bd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x443d2f2755db5942601fa062cc248aaa153313d3                         | Address of the contract that produced the log                |
| epoch             | VARCHAR   | 144                                                                |                                                              |
| couponsExpired    | VARCHAR   | 0                                                                  |                                                              |
| lessRedeemable    | VARCHAR   | 0                                                                  |                                                              |
| lessDebt          | VARCHAR   | 0                                                                  |                                                              |
| newBonded         | VARCHAR   | 0                                                                  |                                                              |

## 6. Table: Implementation\_event\_CouponPurchase\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-01 03:10:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11565919                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x87aa6f3805a53d38b74ad121ee16559f1ce3b3a884996df7a6d6e2c8db6a33ea | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 292                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x443d2f2755db5942601fa062cc248aaa153313d3                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xfa54dab921c65050ccb7ed5afffdd2178cedeb91                         |                                                              |
| epoch             | VARCHAR   | 358                                                                |                                                              |
| dollarAmount      | VARCHAR   | 1200000045449881931960                                             |                                                              |
| couponAmount      | VARCHAR   | 1764413905922306283798                                             |                                                              |

## 7. Table: Implementation\_event\_CouponRedemption\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-07 00:00:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11005328                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe1adcb2e5ba22197f49e7fdcba2e002a1ccc587c93fbd913f691a434e40d05e6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 152                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x443d2f2755db5942601fa062cc248aaa153313d3                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xffff0c6febddbab590ad077096d87ce806aace47                         |                                                              |
| epoch             | VARCHAR   | 100                                                                |                                                              |
| couponAmount      | VARCHAR   | 80809996530612244860000                                            |                                                              |

## 8. Table: Implementation\_event\_CouponTransfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-10 16:00:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11426122                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa1f9c29e94637cb461b111da1629182281384d84ebe2736d6276d1438d27492c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 8                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x443d2f2755db5942601fa062cc248aaa153313d3                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xc8482e19c3fcd56b499d376ab1aad069442ba0cb                         |                                                              |
| to                | VARCHAR   | 0xb4027eeea4b2d91616c63dc3e37075e69f36b457                         |                                                              |
| epoch             | VARCHAR   | 245                                                                |                                                              |
| value             | VARCHAR   | 2490669005272317100176541                                          |                                                              |

## 9. Table: Implementation\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-03 02:04:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11780462                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa8c4f80ddb974510c8fb072e38937be6054f9d2b2b6a44ecb70c3de150313f2b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 290                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x443d2f2755db5942601fa062cc248aaa153313d3                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x99f7da04a349e7cb2d5a9e57e8f531387c14be75                         |                                                              |
| value             | VARCHAR   | 10843224998541525058                                               |                                                              |

## 10. Table: Implementation\_event\_Incentivization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-08 16:00:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11413088                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5519fe224cb0e2f6428baf1bb17a8c3badd0a08643498f02789f5a691956496b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x443d2f2755db5942601fa062cc248aaa153313d3                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x53901c969d13c3e17fa89a86598d21b78803a531                         |                                                              |
| amount            | VARCHAR   | 100000000000000000000                                              |                                                              |

## 11. Table: Implementation\_event\_Proposal\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-28 23:06:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11545339                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x168f24d3b1625f81f4b6a1d9568e0b1af86fec818dd179eeabfc2a1a2b207763 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 317                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x443d2f2755db5942601fa062cc248aaa153313d3                         | Address of the contract that produced the log                |
| candidate         | VARCHAR   | 0xf7752941cb46785a51b23859deb36fdf1e18af4d                         |                                                              |
| account           | VARCHAR   | 0x9726041047644626468922598128349778349982                         |                                                              |
| start             | VARCHAR   | 348                                                                |                                                              |
| period            | VARCHAR   | 9                                                                  |                                                              |

## 12. Table: Implementation\_event\_SupplyDecrease\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-21 00:00:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11695475                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x750c940c6be45c6a2a8a6bf5f5bfc53578f17ef919525bf230985f2b450ab5e1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x443d2f2755db5942601fa062cc248aaa153313d3                         | Address of the contract that produced the log                |
| epoch             | VARCHAR   | 418                                                                |                                                              |
| price             | VARCHAR   | 508408000000000000                                                 |                                                              |
| newDebt           | VARCHAR   | 3912384647594570914623639                                          |                                                              |

## 13. Table: Implementation\_event\_SupplyIncrease\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-25 16:00:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11523734                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1d3f49e32023aed71c7486f781943d649abf1eaad96e5384927e1732eeecc2a3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 86                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x443d2f2755db5942601fa062cc248aaa153313d3                         | Address of the contract that produced the log                |
| epoch             | VARCHAR   | 339                                                                |                                                              |
| price             | VARCHAR   | 1197714000000000000                                                |                                                              |
| newRedeemable     | VARCHAR   | 0                                                                  |                                                              |
| lessDebt          | VARCHAR   | 100000000000000000000                                              |                                                              |
| newBonded         | VARCHAR   | 12961108205636294056505980                                         |                                                              |

## 14. Table: Implementation\_event\_SupplyNeutral\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| epoch             | VARCHAR   |                                                              |             |

## 15. Table: Implementation\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-19 16:08:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11087464                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8e4f83e69371e39a33143fbd295e9ba244968b0880744107a839dd2dbd35c08f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 267                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x443d2f2755db5942601fa062cc248aaa153313d3                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x0006e4548aed4502ec8c844567840ce6ef1013f5                         |                                                              |
| value             | VARCHAR   | 2636358494709920999945302                                          |                                                              |

## 16. Table: Implementation\_event\_Unbond\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-03 06:57:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11378137                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6895a0bba017f20a81b019b748c999d2377db340c00349280b46d0eee85f9dbd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 259                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x443d2f2755db5942601fa062cc248aaa153313d3                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x4f1dcfb5d1634c1dcdb0f338e7a5a97f2be91e4c                         |                                                              |
| start             | VARCHAR   | 272                                                                |                                                              |
| value             | VARCHAR   | 8690157405597184043898                                             |                                                              |
| valueUnderlying   | VARCHAR   | 802150196188670875438                                              |                                                              |

## 17. Table: Implementation\_event\_Upgraded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-28 08:01:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11143923                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc8b5d2fbdf434e1eee7a2b51b1266d0a94390365c07d128a742235b36733c1cb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 30                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x443d2f2755db5942601fa062cc248aaa153313d3                         | Address of the contract that produced the log                |
| implementation    | VARCHAR   | 0xdaf2593aaf8ef040e279c806aab8dedfe534d421                         |                                                              |

## 18. Table: Implementation\_event\_Vote\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-20 09:22:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11691423                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0bdb8d5ae18ba7b9d165081c073cbe554756475a3310a82e277c7dd4bc1840aa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 34                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x443d2f2755db5942601fa062cc248aaa153313d3                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xdbc46c788f7249251fa6b49303babcb1c519f608                         |                                                              |
| candidate         | VARCHAR   | 0xef9c0c8cb6d7c5d36cb9ea0d6a1a4fca4e21aa20                         |                                                              |
| vote              | VARCHAR   | 1                                                                  |                                                              |
| bonded            | VARCHAR   | 6343384568507788595594934                                          |                                                              |

## 19. Table: Implementation\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-04 19:53:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11791799                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4ae486b9e8e37d8f735c47b0124b2faaf36cebe95cf69867314b7ab845ef5230 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 118                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x443d2f2755db5942601fa062cc248aaa153313d3                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xee5a52661bd9073d30f13c25569b67ffd8176ff0                         |                                                              |
| value             | VARCHAR   | 5953094603382290281522                                             |                                                              |
