# ribbon

## 1. Table: Auction\_event\_ApprovalForAll\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| owner             | VARCHAR   |                                                              |             |
| operator          | VARCHAR   |                                                              |             |
| approved          | VARCHAR   |                                                              |             |

## 2. Table: Auction\_event\_Approval\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| owner             | VARCHAR   |                                                              |             |
| approved          | VARCHAR   |                                                              |             |
| tokenId           | VARCHAR   |                                                              |             |

## 3. Table: Auction\_event\_AuctionDurationSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| duration          | VARCHAR   |                                                              |             |

## 4. Table: Auction\_event\_AuctionEndSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| pool              | VARCHAR   |                                                              |             |
| end               | VARCHAR   |                                                              |             |

## 5. Table: Auction\_event\_AuctionStarted\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| pool              | VARCHAR   |                                                              |             |
| bidder            | VARCHAR   |                                                              |             |

## 6. Table: Auction\_event\_Bid\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| pool              | VARCHAR   |                                                              |             |
| bidder            | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 7. Table: Auction\_event\_Initialized\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-23 21:59:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15598891                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8c8e22f4c75c10a118c465bf67316210ed041f5d2d1ae0d234547c25e1b27af7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 128                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3b383d8e92cc922539f9e9f4d64da119e250334a                         | Address of the contract that produced the log                |
| version           | VARCHAR   | 1                                                                  |                                                              |

## 8. Table: Auction\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-23 22:00:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15598893                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6713521be8238b3a0b3d067a3225f2a444b0d098e0743663ddc566bfa0d0d4dc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 506                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3b383d8e92cc922539f9e9f4d64da119e250334a                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x76153d209f2e780721c665f24435d54a14315eaa                         |                                                              |
| newOwner          | VARCHAR   | 0x77da011d5314d80be59e939c2f7ec2f702e1dcc4                         |                                                              |

## 9. Table: Auction\_event\_Transfer\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| from              | VARCHAR   |                                                              |             |
| to                | VARCHAR   |                                                              |             |
| tokenId           | VARCHAR   |                                                              |             |

## 10. Table: Auction\_event\_WhitelistedBidderSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| bidder            | VARCHAR   |                                                              |             |
| whitelisted       | VARCHAR   |                                                              |             |

## 11. Table: PoolFactory\_event\_CurrencySet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-23 22:05:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15598918                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd25cc118e123aeec40605b932f37cc6ad2d009c3845c2f8ec296e3356611c352 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 282                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x312853485a41f76f20a14f927cd0ea676588936c                         | Address of the contract that produced the log                |
| currency          | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| allowed           | VARCHAR   | true                                                               |                                                              |

## 12. Table: PoolFactory\_event\_Initialized\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-23 22:02:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15598905                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x87a0e9b791c6fffeca419bf8a8a7e9ad5682c2bfcc0153f546ea1b0d4ca0e109 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 326                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x312853485a41f76f20a14f927cd0ea676588936c                         | Address of the contract that produced the log                |
| version           | VARCHAR   | 1                                                                  |                                                              |

## 13. Table: PoolFactory\_event\_InsuranceFactorSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-23 22:03:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15598910                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc6c3dcdf0399d69eb66f28b88f52fb4654040314b545dde018dc5a701130664d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 170                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x312853485a41f76f20a14f927cd0ea676588936c                         | Address of the contract that produced the log                |
| factor            | VARCHAR   | 50000000000000000                                                  |                                                              |

## 14. Table: PoolFactory\_event\_InterestRateModelSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newModel          | VARCHAR   |                                                              |             |

## 15. Table: PoolFactory\_event\_KeeperSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-23 22:02:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15598906                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe05ebc630412a03369712c29e517c7a95aa781ce7a8cfc7aecda1fdefd33f8ee | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 171                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x312853485a41f76f20a14f927cd0ea676588936c                         | Address of the contract that produced the log                |
| newKeeper         | VARCHAR   | 0xa1c309653362f4a55b1d35db3b0b7aaa402cfa87                         |                                                              |

## 16. Table: PoolFactory\_event\_ManagerInfoSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| manager           | VARCHAR   |                                                              |             |
| ipfsHash          | VARCHAR   |                                                              |             |

## 17. Table: PoolFactory\_event\_MaxInactivePeriodSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-23 22:04:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15598916                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa7d9d6c090e1acf333a1672abc23d81d5ac7d4817e1bdf6c87e4465c27b40bef | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 204                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x312853485a41f76f20a14f927cd0ea676588936c                         | Address of the contract that produced the log                |
| period            | VARCHAR   | 1209600                                                            |                                                              |

## 18. Table: PoolFactory\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-23 22:02:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15598905                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x87a0e9b791c6fffeca419bf8a8a7e9ad5682c2bfcc0153f546ea1b0d4ca0e109 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 325                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x312853485a41f76f20a14f927cd0ea676588936c                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x76153d209f2e780721c665f24435d54a14315eaa                         |                                                              |

## 19. Table: PoolFactory\_event\_PeriodToStartAuctionSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-23 22:04:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15598917                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc46258d65fc9aee779cc939035a524bc7cdf8c6621158154aac7892e869935dd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 200                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x312853485a41f76f20a14f927cd0ea676588936c                         | Address of the contract that produced the log                |
| period            | VARCHAR   | 1209600                                                            |                                                              |

## 20. Table: PoolFactory\_event\_PoolBeaconSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newPoolBeacon     | VARCHAR   |                                                              |             |

## 21. Table: PoolFactory\_event\_PoolClosed\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| pool              | VARCHAR   |                                                              |             |
| manager           | VARCHAR   |                                                              |             |

## 22. Table: PoolFactory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-23 22:15:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15598971                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x93a48973250f97113412cb5fb49587ba82388b91ed1db6312c6610bf0a46348b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 122                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x312853485a41f76f20a14f927cd0ea676588936c                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0x0aea75705be8281f4c24c3e954d1f8b1d0f8044c                         |                                                              |
| manager           | VARCHAR   | 0xa1614ec01d13e04522ed0b085c7a178ed9e99bc9                         |                                                              |
| currency          | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |

## 23. Table: PoolFactory\_event\_PoolRewardPerSecondSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-05 23:00:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15906955                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x28a5f5298bf42d4cd9a6443b725d57f9cc50ef1446f2f7790f553cf833a015ff | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 51                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x312853485a41f76f20a14f927cd0ea676588936c                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0x0aea75705be8281f4c24c3e954d1f8b1d0f8044c                         |                                                              |
| rewardPerSecond   | VARCHAR   | 149620564523315491                                                 |                                                              |

## 24. Table: PoolFactory\_event\_PoolTransferred\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| pool              | VARCHAR   |                                                              |             |
| oldManager        | VARCHAR   |                                                              |             |
| newManager        | VARCHAR   |                                                              |             |

## 25. Table: PoolFactory\_event\_ProvisionalDefaultUtilizationSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-23 22:04:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15598914                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5b0070bd661f4c52e73c1a2a93648125cd7c439380996aca6e54cfe11a505569 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 294                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x312853485a41f76f20a14f927cd0ea676588936c                         | Address of the contract that produced the log                |
| utilization       | VARCHAR   | 990000000000000000                                                 |                                                              |

## 26. Table: PoolFactory\_event\_ReserveFactorSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-23 22:03:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15598909                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0dd4c017f39353615ece99686f483e217c1b19d6bb670909fed8211e994d7670 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 109                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x312853485a41f76f20a14f927cd0ea676588936c                         | Address of the contract that produced the log                |
| factor            | VARCHAR   | 50000000000000000                                                  |                                                              |

## 27. Table: PoolFactory\_event\_TreasurySet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-23 22:02:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15598907                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x39dc8e4bc79a90132f1d69c24f89c0793a08fb0e2e9ac70023576b766f3b55a1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 108                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x312853485a41f76f20a14f927cd0ea676588936c                         | Address of the contract that produced the log                |
| newTreasury       | VARCHAR   | 0xdaeada3d210d2f45874724beea03c7d4bbd41674                         |                                                              |

## 28. Table: PoolFactory\_event\_WarningGracePeriodSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-23 22:04:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15598915                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x726b1389841830e7fc906345d53b27988599a479ab0dd7685a183e1f9ce2d89b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 272                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x312853485a41f76f20a14f927cd0ea676588936c                         | Address of the contract that produced the log                |
| period            | VARCHAR   | 432000                                                             |                                                              |

## 29. Table: PoolFactory\_event\_WarningUtilizationSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-23 22:03:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15598912                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x899cc2885f1c46ec6814e04e8644f3b23664c349497e96b89e5d99ba886ee447 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 187                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x312853485a41f76f20a14f927cd0ea676588936c                         | Address of the contract that produced the log                |
| utilization       | VARCHAR   | 950000000000000000                                                 |                                                              |

## 30. Table: PoolMaster\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-06 04:09:11+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15686582                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3b218e905cb23159ab549b7684e8d82532a0dc8ac76ec5343d5ee3ef098936c7             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 225                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0aea75705be8281f4c24c3e954d1f8b1d0f8044c                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xcb738ec976ccae04315e11e6afe3ab8aa4433e81                                     |                                                              |
| spender           | VARCHAR   | 0xd152f549545093347a162dce210e7293f1452150                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 31. Table: PoolMaster\_event\_Borrowed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-08 10:48:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15702873                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7a63a5b3f056a3fae2177dad56c2b9284230ac59a6e356e2b0874755b65b5720 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 225                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3cd0ecf1552d135b8da61c7f44cefe93485c616d                         | Address of the contract that produced the log                |
| amount            | VARCHAR   | 55000000000                                                        |                                                              |
| receiver          | VARCHAR   | 0x44c8e19bd59a8ea895fff60dbb4e762028f2fb71                         |                                                              |

## 32. Table: PoolMaster\_event\_Closed\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 33. Table: PoolMaster\_event\_Initialized\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-08 02:01:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15922191                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4dac874e49f173940190d326452f6c6c883cc08bccbcd6add0c040b92d2418bd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 377                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x559548340350d4211e637b242da25549337a61df                         | Address of the contract that produced the log                |
| version           | VARCHAR   | 1                                                                  |                                                              |

## 34. Table: PoolMaster\_event\_Provided\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-14 07:01:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15966651                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x23033fe83b900c8cbf27fe0b56124af1d107316efe97e8c3d312f314d25a591c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 287                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0aea75705be8281f4c24c3e954d1f8b1d0f8044c                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x3ec7968d1622d6950db90f7b023477a4f94bcc63                         |                                                              |
| referral          | VARCHAR   | 0x3ec7968d1622d6950db90f7b023477a4f94bcc63                         |                                                              |
| currencyAmount    | VARCHAR   | 1600000000000                                                      |                                                              |
| tokens            | VARCHAR   | 1587337681034                                                      |                                                              |

## 35. Table: PoolMaster\_event\_Redeemed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-15 14:14:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17699305                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x93295164aae7e65fa517319b188625c5d184ff98c10392d43ed2c828aeeff419 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 140                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0aea75705be8281f4c24c3e954d1f8b1d0f8044c                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0xc4839c439a8646a64c7ce5a7da008a5d0062d4bc                         |                                                              |
| currencyAmount    | VARCHAR   | 121155404                                                          |                                                              |
| tokens            | VARCHAR   | 119771259                                                          |                                                              |

## 36. Table: PoolMaster\_event\_Repaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-11 12:49:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15946881                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8661e81763e0313f7a4af01138583355dfdc9caf25f136a62763a6c54eaee1da | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 212                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0aea75705be8281f4c24c3e954d1f8b1d0f8044c                         | Address of the contract that produced the log                |
| amount            | VARCHAR   | 2723389647714                                                      |                                                              |

## 37. Table: PoolMaster\_event\_RewardPerSecondSet\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2022-10-28 18:53:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 15848476                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0xecddc2a27378e9a3339b3be4698b0e43bf0535e97332bc866957e1b973d2bd99 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 131                                                                | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x0aea75705be8281f4c24c3e954d1f8b1d0f8044c                         | Address of the contract that produced the log                |
| newRewardPerSecond | VARCHAR   | 128342101942444335                                                 |                                                              |

## 38. Table: PoolMaster\_event\_RewardWithdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-12 12:39:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15732088                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x230cb7f96273575bff7d07c13a936de23536162a4d527b1c217d03dd4b6a6a06 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 402                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3cd0ecf1552d135b8da61c7f44cefe93485c616d                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x45d80fb72b9757f33f9a1b77730226a97c958032                         |                                                              |
| amount            | VARCHAR   | 7525725044092301340                                                |                                                              |

## 39. Table: PoolMaster\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-24 21:13:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17765570                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc40d8ff2aadc759ada220b9123090d011f248297f9af1c830ebc533c451c85c6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 280                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0aea75705be8281f4c24c3e954d1f8b1d0f8044c                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x59511e5b333d7ca552bb32384424b34a45b972b8                         |                                                              |
| value             | VARCHAR   | 494286702                                                          |                                                              |
