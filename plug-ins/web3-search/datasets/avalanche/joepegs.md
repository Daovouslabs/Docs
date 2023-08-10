# joepegs

## 1. Table: JoepegExchange\_event\_CancelAllOrders\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-02 02:13:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 18100256                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe46393f8364495c050e3e3ef3cf92e2c48ab5fe412a689ace29ab9a63dfb177d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xae079eda901f7727d0715aff8f82ba8295719977                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x567ed903a3db164a19af18d45b9067feff59bce4                         |                                                              |
| newMinNonce       | VARCHAR   | 83                                                                 |                                                              |

## 2. Table: JoepegExchange\_event\_CancelMultipleOrders\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-17 13:25:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30137150                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x08d2bc76260746e9361caa41372c035e3e9e21c081c234e5189f8511ac577e8b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xae079eda901f7727d0715aff8f82ba8295719977                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x038673370955eb929d94f9d0c7992bb48137e998                         |                                                              |
| orderNonces       | VARCHAR   | 881                                                                |                                                              |

## 3. Table: JoepegExchange\_event\_NewCurrencyManager\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| currencyManager   | VARCHAR   |                                                              |             |

## 4. Table: JoepegExchange\_event\_NewExecutionManager\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| executionManager  | VARCHAR   |                                                              |             |

## 5. Table: JoepegExchange\_event\_NewProtocolFeeManager\_history

| Column             | Type      | Example                                                      | Description |
| ------------------ | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number      | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index         | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address  | VARCHAR   | Address of the contract that produced the log                |             |
| protocolFeeManager | VARCHAR   |                                                              |             |

## 6. Table: JoepegExchange\_event\_NewProtocolFeeRecipient\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2022-05-04 07:23:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 14252119                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x3b5bb236dcd468ecb695fc7a92370dfda57407f5c11a5c98cb2606d3977907ee | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 16                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0xae079eda901f7727d0715aff8f82ba8295719977                         | Address of the contract that produced the log                |
| protocolFeeRecipient | VARCHAR   | 0x64c4607ad853999ee5042ba8377bfc4099c273de                         |                                                              |

## 7. Table: JoepegExchange\_event\_NewRoyaltyFeeManager\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| royaltyFeeManager | VARCHAR   |                                                              |             |

## 8. Table: JoepegExchange\_event\_NewTransferSelectorNFT\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2022-04-29 02:22:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 14033363                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xbb9a38ed21ebc5ff1fdf04b531647cab671e1e07a72a0afe84b19a1a8fe536c9 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 29                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0xae079eda901f7727d0715aff8f82ba8295719977                         | Address of the contract that produced the log                |
| transferSelectorNFT | VARCHAR   | 0x6817f284319dd8fed56a8577d9a29b5685eb6915                         |                                                              |

## 9. Table: JoepegExchange\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-03 14:11:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14222079                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe951e199f2f26708213965fea820c180bfd9e845573c0c8a7fb4f425aee15a08 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xae079eda901f7727d0715aff8f82ba8295719977                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x336c61f5ee471c645d24133accc88ad7b63e3a42                         |                                                              |
| newOwner          | VARCHAR   | 0x2fbb61a10b96254900c03f1644e9e1d2f5e76dd2                         |                                                              |

## 10. Table: JoepegExchange\_event\_RoyaltyPayment\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-31 20:04:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 25663890                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x815a8bbd7df1cf13957e039e3367861bf85c9a54de96b39b1b04ca6cc6df800a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 11                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xae079eda901f7727d0715aff8f82ba8295719977                         | Address of the contract that produced the log                |
| collection        | VARCHAR   | 0x006d36dfb318ec1b3a87b2cad4210698090717dd                         |                                                              |
| tokenId           | VARCHAR   | 5420                                                               |                                                              |
| royaltyRecipient  | VARCHAR   | 0x278af0aad5549b91a7a94985bd499a8463246ef0                         |                                                              |
| currency          | VARCHAR   | 0xb31f66aa3c1e785363f0875a1b74e27b85fd66c7                         |                                                              |
| amount            | VARCHAR   | 29950000000000000                                                  |                                                              |

## 11. Table: JoepegExchange\_event\_TakerAsk\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-15 13:20:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 22409473                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb63a22944868cec9ecfe7bc558002be6bbbd92172a4807ac38985be9624a8a9e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xae079eda901f7727d0715aff8f82ba8295719977                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0xb99c2a28619a823f728b581aa1da7699b04798dcb8d10aef7b57cceea87952e5 |                                                              |
| orderNonce        | VARCHAR   | 361                                                                |                                                              |
| taker             | VARCHAR   | 0xb66d123b0024761e6c4eb10eeb87e0276bfbc57a                         |                                                              |
| maker             | VARCHAR   | 0x4d6f1c49cafa58b4ef05d9617c18bce9b3875f91                         |                                                              |
| strategy          | VARCHAR   | 0x24ab13f8b58be64a91a7291b5e0cf32fcddcc62b                         |                                                              |
| currency          | VARCHAR   | 0xb31f66aa3c1e785363f0875a1b74e27b85fd66c7                         |                                                              |
| collection        | VARCHAR   | 0x00f5d01d86008d14d04e29efe88dffc75a9cac47                         |                                                              |
| tokenId           | VARCHAR   | 185                                                                |                                                              |
| amount            | VARCHAR   | 1                                                                  |                                                              |
| price             | VARCHAR   | 10000000000000000000                                               |                                                              |

## 12. Table: JoepegExchange\_event\_TakerBid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-10 05:49:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 19725890                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbff670eb70d705f8ae86dbe80b7509bfdfe00b2f952b54f33cf2e100a0a5d99c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 11                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xae079eda901f7727d0715aff8f82ba8295719977                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0x469ced0b9acc7de91e8b256c4f7a7d7927160fa60a2dadc467b3171a98246a1f |                                                              |
| orderNonce        | VARCHAR   | 452                                                                |                                                              |
| taker             | VARCHAR   | 0x17fcdd289a3431cb9be3facbda08a26f15b7938a                         |                                                              |
| maker             | VARCHAR   | 0xcd49c22c4324486109f94f0bad59c360fc242bd9                         |                                                              |
| strategy          | VARCHAR   | 0x24ab13f8b58be64a91a7291b5e0cf32fcddcc62b                         |                                                              |
| currency          | VARCHAR   | 0xb31f66aa3c1e785363f0875a1b74e27b85fd66c7                         |                                                              |
| collection        | VARCHAR   | 0x048c939bea33c5df4d2c69414b9385d55b3ba62e                         |                                                              |
| tokenId           | VARCHAR   | 219                                                                |                                                              |
| amount            | VARCHAR   | 1                                                                  |                                                              |
| price             | VARCHAR   | 2150000000000000000                                                |                                                              |
