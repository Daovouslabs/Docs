# clearpool

## 1. Table: PoolFactory\_event\_CurrencySet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-16 09:55:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14785551                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x47c13f07c41ba78136f2012c5b49d52d5b1e2ce61088166c852abddb69693eca | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 295                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xde204e5a060ba5d3b63c7a4099712959114c2d48                         | Address of the contract that produced the log                |
| currency          | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| allowed           | VARCHAR   | true                                                               |                                                              |

## 2. Table: PoolFactory\_event\_InsuranceFactorSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-16 08:49:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14785271                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x48fb3ac2288f7049fbeae731440bd46b8d686a8fdeb96f68d729fcfc064f755f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 236                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xde204e5a060ba5d3b63c7a4099712959114c2d48                         | Address of the contract that produced the log                |
| factor            | VARCHAR   | 50000000000000000                                                  |                                                              |

## 3. Table: PoolFactory\_event\_InterestRateModelSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-01 07:20:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17384443                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xeca0cf87b1a3375ee9dfd7b2b6b7eb35e8d8004a37cd5613cb4c0bb6bb467004 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 137                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xde204e5a060ba5d3b63c7a4099712959114c2d48                         | Address of the contract that produced the log                |
| newModel          | VARCHAR   | 0x0e5c0cf338bfcbbeb2b2c4f6811aafe5e29d4a1e                         |                                                              |

## 4. Table: PoolFactory\_event\_ManagerInfoSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| manager           | VARCHAR   |                                                              |             |
| ipfsHash          | VARCHAR   |                                                              |             |

## 5. Table: PoolFactory\_event\_MaxInactivePeriodSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-16 09:54:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14785549                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd9c17c141e8f21db9e2e16fba47819fcb418bad16dcb5e12f7e885d18495ad9a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 342                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xde204e5a060ba5d3b63c7a4099712959114c2d48                         | Address of the contract that produced the log                |
| period            | VARCHAR   | 1209600                                                            |                                                              |

## 6. Table: PoolFactory\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-16 08:34:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14785206                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1b18e228f4917aa11621eb6267e03e9acc6506b8f3bb04cd6c8705d04e9f0d45 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 89                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xde204e5a060ba5d3b63c7a4099712959114c2d48                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x1bb8bb8291a2afb1bf81bf51be2c2f093513311f                         |                                                              |

## 7. Table: PoolFactory\_event\_PeriodToStartAuctionSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-16 09:54:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14785550                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3edc28a5231b6390a5f0245749a55e5efc93549c83a6fcd23d12facd35454530 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 467                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xde204e5a060ba5d3b63c7a4099712959114c2d48                         | Address of the contract that produced the log                |
| period            | VARCHAR   | 1209600                                                            |                                                              |

## 8. Table: PoolFactory\_event\_PoolBeaconSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newPoolBeacon     | VARCHAR   |                                                              |             |

## 9. Table: PoolFactory\_event\_PoolClosed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-18 15:26:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14799607                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd649af797754b916c63dec9c71d236daf126b459c7452ed437f235ce8a745d75 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 339                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xde204e5a060ba5d3b63c7a4099712959114c2d48                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0xc5d55dca587d26cdbf1841d72b61f7f74241960c                         |                                                              |
| manager           | VARCHAR   | 0xa1614ec01d13e04522ed0b085c7a178ed9e99bc9                         |                                                              |

## 10. Table: PoolFactory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-16 10:53:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14785823                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x26cb7302b1c00799ee26d499bf51cc4cec531caf37eda59deba6ab1bf08ffe9d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 154                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xde204e5a060ba5d3b63c7a4099712959114c2d48                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0xe3d20a721522874d32548b4097d1afc6f024e45b                         |                                                              |
| manager           | VARCHAR   | 0x948d589df907c3f5cef1c62eeb051428fccbc709                         |                                                              |
| currency          | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |

## 11. Table: PoolFactory\_event\_PoolRewardPerSecondSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-25 10:02:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17335442                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8746f7213ae91a474f222ae248dbe9dae7f19090ce7b0bce71870df0d2a98dbc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 122                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xde204e5a060ba5d3b63c7a4099712959114c2d48                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0x4a90c14335e81829d7cb0002605f555b8a784106                         |                                                              |
| rewardPerSecond   | VARCHAR   | 270000000000000000                                                 |                                                              |

## 12. Table: PoolFactory\_event\_PoolTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-19 04:26:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14802918                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5627666c82a3c80065a3578ee677a62d99991800e615eb34f05c538bd1c7aceb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 192                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xde204e5a060ba5d3b63c7a4099712959114c2d48                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0x7b7e4ab1ecf7a69c1f15b186f9af11bb53e764cb                         |                                                              |
| oldManager        | VARCHAR   | 0xa337321a3b9909aec6e7053ef8e8fdb24e4614f2                         |                                                              |
| newManager        | VARCHAR   | 0x4bf2c1a46a6246ca99e55fd6372d65f63c67be28                         |                                                              |

## 13. Table: PoolFactory\_event\_ProvisionalDefaultUtilizationSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-16 09:53:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14785546                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbdf54b9cb74b2633e5340c44ece72e6ca46989a5611292856d5fdd3b97d3c22c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 143                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xde204e5a060ba5d3b63c7a4099712959114c2d48                         | Address of the contract that produced the log                |
| utilization       | VARCHAR   | 990000000000000000                                                 |                                                              |

## 14. Table: PoolFactory\_event\_ReserveFactorSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-16 08:47:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14785267                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x715823c3d4e23ef3322b9e697d5f77fe5d96044622823e723b469542ba353bd4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 268                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xde204e5a060ba5d3b63c7a4099712959114c2d48                         | Address of the contract that produced the log                |
| factor            | VARCHAR   | 50000000000000000                                                  |                                                              |

## 15. Table: PoolFactory\_event\_TreasurySet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-16 08:47:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14785266                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x02eb230435bba81723ea2a3c4e12867290a77de630cc4785826f6aea075c0c9a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 174                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xde204e5a060ba5d3b63c7a4099712959114c2d48                         | Address of the contract that produced the log                |
| newTreasury       | VARCHAR   | 0x455011f2704c6e192b09d9cc1430299c70af3454                         |                                                              |

## 16. Table: PoolFactory\_event\_WarningGracePeriodSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-16 09:54:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14785548                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x05aafe0146d358eda445d0c2ed22fd5e6da39d786223fe73d263f5f03145740e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 346                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xde204e5a060ba5d3b63c7a4099712959114c2d48                         | Address of the contract that produced the log                |
| period            | VARCHAR   | 432000                                                             |                                                              |

## 17. Table: PoolFactory\_event\_WarningUtilizationSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-16 09:53:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14785545                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x09d8c797a876afd39b1a3cbcdeb952c9682c68baa1faa451281a71aaf6664c72 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 186                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xde204e5a060ba5d3b63c7a4099712959114c2d48                         | Address of the contract that produced the log                |
| utilization       | VARCHAR   | 950000000000000000                                                 |                                                              |

## 18. Table: PoolMaster\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-24 04:53:23+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15600954                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2b9275e28eda84b800f72cd95c045094955181cca3ec54dbba88e541386c9e5d             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 46                                                                             | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcb288b6d30738db7e3998159d192615769794b5b                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x1bd7cb1ea390aa2bcd7983a5ca789f8b101eb380                                     |                                                              |
| spender           | VARCHAR   | 0x68b3465833fb72a70ecdf485e0e4c7bd8665fc45                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 19. Table: PoolMaster\_event\_Borrowed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-12 10:06:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17463279                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7f7c2755e075065d08390c7939457a9d43ccc4e5a803fb7cea1ad309c7082331 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 138                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4a90c14335e81829d7cb0002605f555b8a784106                         | Address of the contract that produced the log                |
| amount            | VARCHAR   | 924559061126                                                       |                                                              |
| receiver          | VARCHAR   | 0xd2f9d4bb47e6d65ceb0cbc4f618bf36fbf187645                         |                                                              |

## 20. Table: PoolMaster\_event\_Closed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-18 15:26:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14799607                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd649af797754b916c63dec9c71d236daf126b459c7452ed437f235ce8a745d75 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 340                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc5d55dca587d26cdbf1841d72b61f7f74241960c                         | Address of the contract that produced the log                |

## 21. Table: PoolMaster\_event\_Provided\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-01 10:38:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17385416                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2034964efe9e68849a2d7a851436d106249dce5a28ca67b4083f0dde84ca22c0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 147                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4a90c14335e81829d7cb0002605f555b8a784106                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xecae704097df715a1fcc8dcb9793f29e068cf171                         |                                                              |
| currencyAmount    | VARCHAR   | 194400000000                                                       |                                                              |
| tokens            | VARCHAR   | 190564058696                                                       |                                                              |

## 22. Table: PoolMaster\_event\_Redeemed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-18 08:36:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17505522                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x262ce032c2c95bb2e542c808eb949a639d1a899fe89ea47cc04cd3efc3e66aba | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 271                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4a90c14335e81829d7cb0002605f555b8a784106                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0x931c080c7ed6b3c6988576654e5d56753dc92181                         |                                                              |
| currencyAmount    | VARCHAR   | 5319554572                                                         |                                                              |
| tokens            | VARCHAR   | 5194224221                                                         |                                                              |

## 23. Table: PoolMaster\_event\_Repaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-11 07:04:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17235508                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb7be6d78bb1eb54847ecd14d921ba1b1f4414b0c7a7639f23eb5b35747caf507 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 236                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4a90c14335e81829d7cb0002605f555b8a784106                         | Address of the contract that produced the log                |
| amount            | VARCHAR   | 450193267076                                                       |                                                              |

## 24. Table: PoolMaster\_event\_RewardPerBlockSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-02 07:11:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14889606                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x96bc906f4531882073d381334dd5426a07a68d60a1c8f6565c6a17aaefe259f2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 392                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcb288b6d30738db7e3998159d192615769794b5b                         | Address of the contract that produced the log                |
| newRewardPerBlock | VARCHAR   | 500000000000000000                                                 |                                                              |

## 25. Table: PoolMaster\_event\_RewardWithdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-24 23:26:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17332297                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9ea6fb111e1bde1e5325e9e0ce0acd1cf543666eb76564020d040d9f0c76b369 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 189                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x68f311351e7196d71f8e6372e4a1d2e725669bf2                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x186cf5714316f47bc59e30a850615a3f938d7d79                         |                                                              |
| amount            | VARCHAR   | 13120675095042274799235                                            |                                                              |

## 26. Table: PoolMaster\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-29 10:19:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17584318                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x07602016d146b01c8083ec9165a4432ddcb56b692290816269dc1f027bf37bd6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 187                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1a1d778776542c2efed161ba1fbcfe6e09ba99fb                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xc8e2fad99061407e947485c846bd05eae9de1991                         |                                                              |
| value             | VARCHAR   | 39721349402                                                        |                                                              |
