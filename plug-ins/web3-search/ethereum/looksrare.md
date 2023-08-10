# looksrare

## 1. Table: FeeSharingSystem\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-18 16:15:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16656643                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0517b0b5d4d714433008812b1d1a4ae0c6da34ad559e357f507df70045b6d3e9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 261                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbcd7254a1d759efa08ec7c3291b2e85c5dcc12ce                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x0bc4419cf787da4286d4eb6e93b81fb55a9af39f                         |                                                              |
| amount            | VARCHAR   | 37499000000000000000000                                            |                                                              |
| harvestedAmount   | VARCHAR   | 0                                                                  |                                                              |

## 2. Table: FeeSharingSystem\_event\_Harvest\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-05 12:02:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17848638                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x171b5403161505afc57328c4fc0563679f6bf92a95586bed21710b108d0d347c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 260                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbcd7254a1d759efa08ec7c3291b2e85c5dcc12ce                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x0d6fa990d38fc57a46e55394261255c5219ea17d                         |                                                              |
| harvestedAmount   | VARCHAR   | 435241384692177532                                                 |                                                              |

## 3. Table: FeeSharingSystem\_event\_NewRewardPeriod\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-13 01:05:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14764396                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xebe9669228aaf0160a551f93f18c308d7ddc1062882b5b7e4766fe73c9c17fbc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 480                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbcd7254a1d759efa08ec7c3291b2e85c5dcc12ce                         | Address of the contract that produced the log                |
| numberBlocks      | VARCHAR   | 6500                                                               |                                                              |
| rewardPerBlock    | VARCHAR   | 30016006177324161                                                  |                                                              |
| reward            | VARCHAR   | 195104040152607050723                                              |                                                              |

## 4. Table: FeeSharingSystem\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-10 02:13:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13975053                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa452ea7e2cd04a7ab9597ff5da568aab26410c308795ac8c768a3591d071c7d1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 45                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbcd7254a1d759efa08ec7c3291b2e85c5dcc12ce                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0xff6c307226343fcf96af2f6b5b05f63f717e68cb                         |                                                              |

## 5. Table: FeeSharingSystem\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-17 17:15:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16427953                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3ab2eed726fb56bced98172da71886c69c8bc3445a12b003602d2041d0f16d7b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 233                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbcd7254a1d759efa08ec7c3291b2e85c5dcc12ce                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x074d4d7011c354e9cbbddf4e1862619e33f2df77                         |                                                              |
| amount            | VARCHAR   | 1385344930415623927992                                             |                                                              |
| harvestedAmount   | VARCHAR   | 0                                                                  |                                                              |

## 6. Table: LooksRareExchange\_call\_matchAskWithTakerBidUsingETHAndWETH\_history

| Column                      | Type                                                                                                                                                                                                                                                                | Example                                                                                              | Description                                                                                                            |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp            | TIMESTAMP                                                                                                                                                                                                                                                           | 2023-06-05 23:15:59+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number               | INTEGER                                                                                                                                                                                                                                                             | 17417499                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash           | VARCHAR                                                                                                                                                                                                                                                             | 0x6c640f71a2a312efc1ce68af488dddf4c56cf3c3d70b34624fdbcc063d7ce359                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index          | INTEGER                                                                                                                                                                                                                                                             | 165                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address              | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address                 | VARCHAR                                                                                                                                                                                                                                                             | 0x59728544b08ab483533076417fbbb2fd0b17ce3a                                                           | Address of the called contract                                                                                         |
| status                      | INTEGER                                                                                                                                                                                                                                                             | 0                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                       | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 | Error in case input parsing failed                                                                                     |
| takerBid                    | STRUCT\<isOrderAsk STRING, taker STRING, price STRING, tokenId STRING, minPercentageToAsk STRING, params STRING>                                                                                                                                                    | {'isOrderAsk': None, 'taker': None, 'price': None, 'tokenId': None, 'minPercentageToAsk': None, 'par |                                                                                                                        |
| takerBid.isOrderAsk         | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| takerBid.taker              | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| takerBid.price              | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| takerBid.tokenId            | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| takerBid.minPercentageToAsk | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| takerBid.params             | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk                    | STRUCT\<isOrderAsk STRING, signer STRING, collection STRING, price STRING, tokenId STRING, amount STRING, strategy STRING, currency STRING, nonce STRING, startTime STRING, endTime STRING, minPercentageToAsk STRING, params STRING, v STRING, r STRING, s STRING> | {'isOrderAsk': None, 'signer': None, 'collection': None, 'price': None, 'tokenId': None, 'amount': N |                                                                                                                        |
| makerAsk.isOrderAsk         | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk.signer             | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk.collection         | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk.price              | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk.tokenId            | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk.amount             | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk.strategy           | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk.currency           | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk.nonce              | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk.startTime          | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk.endTime            | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk.minPercentageToAsk | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk.params             | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk.v                  | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk.r                  | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk.s                  | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |

## 7. Table: LooksRareExchange\_call\_matchAskWithTakerBid\_history

| Column                      | Type                                                                                                                                                                                                                                                                | Example                                                                                              | Description                                                                                                            |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp            | TIMESTAMP                                                                                                                                                                                                                                                           | 2022-02-28 02:11:27+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number               | INTEGER                                                                                                                                                                                                                                                             | 14291871                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash           | VARCHAR                                                                                                                                                                                                                                                             | 0x65423020df8cee2c81596c5016752139e229545c07c5fc494590f2b5cdc3c50d                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index          | INTEGER                                                                                                                                                                                                                                                             | 256                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address              | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address                 | VARCHAR                                                                                                                                                                                                                                                             | 0x59728544b08ab483533076417fbbb2fd0b17ce3a                                                           | Address of the called contract                                                                                         |
| status                      | INTEGER                                                                                                                                                                                                                                                             | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                       | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 | Error in case input parsing failed                                                                                     |
| takerBid                    | STRUCT\<isOrderAsk STRING, taker STRING, price STRING, tokenId STRING, minPercentageToAsk STRING, params STRING>                                                                                                                                                    | {'isOrderAsk': None, 'taker': None, 'price': None, 'tokenId': None, 'minPercentageToAsk': None, 'par |                                                                                                                        |
| takerBid.isOrderAsk         | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| takerBid.taker              | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| takerBid.price              | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| takerBid.tokenId            | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| takerBid.minPercentageToAsk | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| takerBid.params             | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk                    | STRUCT\<isOrderAsk STRING, signer STRING, collection STRING, price STRING, tokenId STRING, amount STRING, strategy STRING, currency STRING, nonce STRING, startTime STRING, endTime STRING, minPercentageToAsk STRING, params STRING, v STRING, r STRING, s STRING> | {'isOrderAsk': None, 'signer': None, 'collection': None, 'price': None, 'tokenId': None, 'amount': N |                                                                                                                        |
| makerAsk.isOrderAsk         | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk.signer             | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk.collection         | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk.price              | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk.tokenId            | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk.amount             | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk.strategy           | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk.currency           | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk.nonce              | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk.startTime          | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk.endTime            | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk.minPercentageToAsk | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk.params             | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk.v                  | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk.r                  | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerAsk.s                  | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |

## 8. Table: LooksRareExchange\_call\_matchBidWithTakerAsk\_history

| Column                      | Type                                                                                                                                                                                                                                                                | Example                                                                                              | Description                                                                                                            |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp            | TIMESTAMP                                                                                                                                                                                                                                                           | 2022-10-10 13:33:47+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number               | INTEGER                                                                                                                                                                                                                                                             | 15718028                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash           | VARCHAR                                                                                                                                                                                                                                                             | 0x50afa04f514ad1018dfb4d5532de5c74bb8aae23b318724a195d456eb3338f66                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index          | INTEGER                                                                                                                                                                                                                                                             | 0                                                                                                    | Integer of the transactions index position in the block                                                                |
| trace\_address              | VARCHAR                                                                                                                                                                                                                                                             | 3                                                                                                    | Comma separated list of trace address in call tree                                                                     |
| to\_address                 | VARCHAR                                                                                                                                                                                                                                                             | 0x59728544b08ab483533076417fbbb2fd0b17ce3a                                                           | Address of the called contract                                                                                         |
| status                      | INTEGER                                                                                                                                                                                                                                                             | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                       | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 | Error in case input parsing failed                                                                                     |
| takerAsk                    | STRUCT\<isOrderAsk STRING, taker STRING, price STRING, tokenId STRING, minPercentageToAsk STRING, params STRING>                                                                                                                                                    | {'isOrderAsk': None, 'taker': None, 'price': None, 'tokenId': None, 'minPercentageToAsk': None, 'par |                                                                                                                        |
| takerAsk.isOrderAsk         | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| takerAsk.taker              | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| takerAsk.price              | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| takerAsk.tokenId            | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| takerAsk.minPercentageToAsk | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| takerAsk.params             | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerBid                    | STRUCT\<isOrderAsk STRING, signer STRING, collection STRING, price STRING, tokenId STRING, amount STRING, strategy STRING, currency STRING, nonce STRING, startTime STRING, endTime STRING, minPercentageToAsk STRING, params STRING, v STRING, r STRING, s STRING> | {'isOrderAsk': None, 'signer': None, 'collection': None, 'price': None, 'tokenId': None, 'amount': N |                                                                                                                        |
| makerBid.isOrderAsk         | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerBid.signer             | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerBid.collection         | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerBid.price              | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerBid.tokenId            | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerBid.amount             | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerBid.strategy           | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerBid.currency           | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerBid.nonce              | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerBid.startTime          | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerBid.endTime            | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerBid.minPercentageToAsk | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerBid.params             | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerBid.v                  | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerBid.r                  | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |
| makerBid.s                  | VARCHAR                                                                                                                                                                                                                                                             | None                                                                                                 |                                                                                                                        |

## 9. Table: LooksRareExchange\_event\_CancelAllOrders\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-30 04:34:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16517283                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3f3fb0b5f887e0500854b40fe62e462341417c71a2a27fbcf92479f20266a815 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 56                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x59728544b08ab483533076417fbbb2fd0b17ce3a                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x165896732df25087eba4e736604559ceafdfc82f                         |                                                              |
| newMinNonce       | VARCHAR   | 634                                                                |                                                              |

## 10. Table: LooksRareExchange\_event\_CancelMultipleOrders\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-12 00:13:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14567517                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x60593634cbc53f57c1ca7b58a3e5840e95943142223cc42cc6b90ae43c919401 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 363                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x59728544b08ab483533076417fbbb2fd0b17ce3a                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xf60e19a4f5f0ea61bef5f4ef34b4288f100ad4dc                         |                                                              |
| orderNonces       | VARCHAR   | 0                                                                  |                                                              |

## 11. Table: LooksRareExchange\_event\_NewCurrencyManager\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| currencyManager   | VARCHAR   |                                                              |             |

## 12. Table: LooksRareExchange\_event\_NewExecutionManager\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| executionManager  | VARCHAR   |                                                              |             |

## 13. Table: LooksRareExchange\_event\_NewProtocolFeeRecipient\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2021-12-27 10:38:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 13886795                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x43ab2e7df95fd327ac80f118c86a5bebaf68378d9adecf2e79c6500a0a5c9b11 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 101                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x59728544b08ab483533076417fbbb2fd0b17ce3a                         | Address of the contract that produced the log                |
| protocolFeeRecipient | VARCHAR   | 0xc43eb2d8bc29da90253b8006f0f38e29bfc1369b                         |                                                              |

## 14. Table: LooksRareExchange\_event\_NewRoyaltyFeeManager\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-31 04:02:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15865521                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2770a15010d903079cf819691591d719e0069c8e77ad4bef3af3385c7d43fb4d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 71                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x59728544b08ab483533076417fbbb2fd0b17ce3a                         | Address of the contract that produced the log                |
| royaltyFeeManager | VARCHAR   | 0xcbfeba41c3e69d24b5c8b04ed60c42cc5d883620                         |                                                              |

## 15. Table: LooksRareExchange\_event\_NewTransferSelectorNFT\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2021-12-27 06:22:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 13885636                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xf9cf93a1a0609e352443b648ba2de9649fe7177bdad813c163c6fe2eaf130a60 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 42                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x59728544b08ab483533076417fbbb2fd0b17ce3a                         | Address of the contract that produced the log                |
| transferSelectorNFT | VARCHAR   | 0x9ba628f27aac9b2d78a9f2bf40a8a6df4ccd9e2c                         |                                                              |

## 16. Table: LooksRareExchange\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-27 08:12:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15838139                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3b5ea495155ebf650669a29ec57264a2f99d93ae793daa195024da992a42aef9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 136                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x59728544b08ab483533076417fbbb2fd0b17ce3a                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0xa6a96fa698a6d5afcef6e8efeacaae7ee43f2486                         |                                                              |
| newOwner          | VARCHAR   | 0xbfb6669ef4c4c71ae6e722526b1b8d7d9ff9a019                         |                                                              |

## 17. Table: LooksRareExchange\_event\_RoyaltyPayment\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-29 11:33:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15044821                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x64bbaff6b103dc9d23b14677790b6a03458f06535cc2b099f27b30d57ea91c6c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 189                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x59728544b08ab483533076417fbbb2fd0b17ce3a                         | Address of the contract that produced the log                |
| collection        | VARCHAR   | 0x020cdc4775366ae436f13a7d333143432e884934                         |                                                              |
| tokenId           | VARCHAR   | 12345                                                              |                                                              |
| royaltyRecipient  | VARCHAR   | 0x14e494ce58a3e1688bb5179e89416d7028da3e3e                         |                                                              |
| currency          | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| amount            | VARCHAR   | 15000000000000000                                                  |                                                              |

## 18. Table: LooksRareExchange\_event\_TakerAsk\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-04 17:42:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16113005                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3a3c86bd6f1a06b600e8ff441aa3af0489d5665c1f4404d988ef3af1ed5a4368 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 182                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x59728544b08ab483533076417fbbb2fd0b17ce3a                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0xd0f0103b40c5d16fed323e219b56b7c2664a0f084a84dafe0f8bd77b051b7179 |                                                              |
| orderNonce        | VARCHAR   | 2276                                                               |                                                              |
| taker             | VARCHAR   | 0x57c8e789548c66adee60a1c956cba7ff0e63d0d0                         |                                                              |
| maker             | VARCHAR   | 0xbde93ab6fcd81158bf3e1da50d6d3ebcd4c31d21                         |                                                              |
| strategy          | VARCHAR   | 0x09f93623019049c76209c26517acc2af9d49c69b                         |                                                              |
| currency          | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| collection        | VARCHAR   | 0xce50f3ca1f1dbd6fa042666bc0e369565dda457d                         |                                                              |
| tokenId           | VARCHAR   | 3385                                                               |                                                              |
| amount            | VARCHAR   | 1                                                                  |                                                              |
| price             | VARCHAR   | 11000000000000000                                                  |                                                              |

## 19. Table: LooksRareExchange\_event\_TakerBid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-31 02:42:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16523891                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6fb77157285b861a1dfd387f3fec435a92d893ac23db9709e3cc95b552793481 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 119                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x59728544b08ab483533076417fbbb2fd0b17ce3a                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0xac97f02d3c052c6141743731fd854e5c308c68d0787ca317e96a267ed33fd31e |                                                              |
| orderNonce        | VARCHAR   | 54                                                                 |                                                              |
| taker             | VARCHAR   | 0xd91ecce1de58aa1b022e1f0d4486c1c723616c90                         |                                                              |
| maker             | VARCHAR   | 0x550e970e31a45b06df01a00b1c89a478d4d5e00a                         |                                                              |
| strategy          | VARCHAR   | 0x579af6fd30bf83a5ac0d636bc619f98dbdeb930c                         |                                                              |
| currency          | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| collection        | VARCHAR   | 0x092bbc993042a69811d23feb0e64e3bfa0920c6a                         |                                                              |
| tokenId           | VARCHAR   | 17290                                                              |                                                              |
| amount            | VARCHAR   | 1                                                                  |                                                              |
| price             | VARCHAR   | 88800000000000000                                                  |                                                              |

## 20. Table: LooksRareProtocolV2\_event\_AffiliatePayment\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-05 05:30:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17846693                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd80404e1aa4e51bb82ac8d9431f1d48b1b90b6494e87aac62108c73c00a2f47c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 136                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0000000000e655fae4d56241588680f86e3b2377                         | Address of the contract that produced the log                |
| affiliate         | VARCHAR   | 0x143f685e4027b95d9a04d391b958686ead71e71e                         |                                                              |
| currency          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| affiliateFee      | VARCHAR   | 23976000000000                                                     |                                                              |

## 21. Table: LooksRareProtocolV2\_event\_CancelOwnershipTransfer\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 22. Table: LooksRareProtocolV2\_event\_CurrencyStatusUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-14 08:06:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16824890                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xff773441b9852dc6a9d39fe1b11f03fbdd2ecd96a1ee89a17a184afa498dedac | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 60                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0000000000e655fae4d56241588680f86e3b2377                         | Address of the contract that produced the log                |
| currency          | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| isAllowed         | VARCHAR   | true                                                               |                                                              |

## 23. Table: LooksRareProtocolV2\_event\_InitiateOwnershipRenouncement\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 24. Table: LooksRareProtocolV2\_event\_InitiateOwnershipTransfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-23 11:44:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16890026                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x519e167a6093ab376979a8923a94aae768e1f8b22e2dfedca9c9b0de2c657212 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 337                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0000000000e655fae4d56241588680f86e3b2377                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x3ab105f0e4a22ec4a96a9b0ca90c5c534d21f3a7                         |                                                              |
| potentialOwner    | VARCHAR   | 0xbfb6669ef4c4c71ae6e722526b1b8d7d9ff9a019                         |                                                              |

## 25. Table: LooksRareProtocolV2\_event\_NewAffiliateController\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2023-06-16 12:20:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 17492360                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x46d6861043838b9bd38c2fb345776cba3ddc803941e9e1d4e4e21d91e7c67387 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 124                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x0000000000e655fae4d56241588680f86e3b2377                         | Address of the contract that produced the log                |
| affiliateController | VARCHAR   | 0xaa27e4fcccbf24b1f745cf5b2ecee018e91a5e5e                         |                                                              |

## 26. Table: LooksRareProtocolV2\_event\_NewAffiliateProgramStatus\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-16 12:20:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17492360                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x46d6861043838b9bd38c2fb345776cba3ddc803941e9e1d4e4e21d91e7c67387 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 123                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0000000000e655fae4d56241588680f86e3b2377                         | Address of the contract that produced the log                |
| isActive          | VARCHAR   | true                                                               |                                                              |

## 27. Table: LooksRareProtocolV2\_event\_NewAffiliateRate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-13 16:11:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17685681                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9830e1047ced44d97945b7b7a0059db5bc23c85d84b971bea1ce783ee9e768ed | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 471                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0000000000e655fae4d56241588680f86e3b2377                         | Address of the contract that produced the log                |
| affiliate         | VARCHAR   | 0x646265a4def400d8feb41795caec5d83af81252e                         |                                                              |
| rate              | VARCHAR   | 2500                                                               |                                                              |

## 28. Table: LooksRareProtocolV2\_event\_NewBidAskNonces\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-21 21:20:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17744161                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x24f3d4a94bc13d1e7862fc104223e58bff324f2d22d422f2aea4d2175f0686e4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 240                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0000000000e655fae4d56241588680f86e3b2377                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x222767d608fa882ce7c1e5ceb1293da8f5b74dd6                         |                                                              |
| bidNonce          | VARCHAR   | 8467108296674012196011326840672155263480                           |                                                              |
| askNonce          | VARCHAR   | 8467108296674012196011326840672155263480                           |                                                              |

## 29. Table: LooksRareProtocolV2\_event\_NewCreatorFeeManager\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| creatorFeeManager | VARCHAR   |                                                              |             |

## 30. Table: LooksRareProtocolV2\_event\_NewDomainSeparator\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 31. Table: LooksRareProtocolV2\_event\_NewGasLimitETHTransfer\_history

| Column              | Type      | Example                                                      | Description |
| ------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp    | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number       | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash   | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index          | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address   | VARCHAR   | Address of the contract that produced the log                |             |
| gasLimitETHTransfer | VARCHAR   |                                                              |             |

## 32. Table: LooksRareProtocolV2\_event\_NewMaxCreatorFeeBp\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| maxCreatorFeeBp   | VARCHAR   |                                                              |             |

## 33. Table: LooksRareProtocolV2\_event\_NewOwner\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-24 09:44:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16896547                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x04e36a9daf1bb99b149934750d21d3a9106ab45d151f9918499faf5b1a925bb8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 166                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0000000000e655fae4d56241588680f86e3b2377                         | Address of the contract that produced the log                |
| newOwner          | VARCHAR   | 0xbfb6669ef4c4c71ae6e722526b1b8d7d9ff9a019                         |                                                              |

## 34. Table: LooksRareProtocolV2\_event\_NewProtocolFeeRecipient\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2023-03-14 08:06:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 16824890                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xe69206290be9d0cbaf2bd5f34abb4469653bdfabb12e6b13e3ca1d7c147fae81 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 57                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x0000000000e655fae4d56241588680f86e3b2377                         | Address of the contract that produced the log                |
| protocolFeeRecipient | VARCHAR   | 0x5924a28caaf1cc016617874a2f0c3710d881f3c1                         |                                                              |

## 35. Table: LooksRareProtocolV2\_event\_NewStrategy\_history

| Column                | Type      | Example                                                            | Description                                                  |
| --------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp      | TIMESTAMP | 2023-03-14 08:06:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number         | INTEGER   | 16824890                                                           | The block number where this event was emitted                |
| transaction\_hash     | VARCHAR   | 0xe69206290be9d0cbaf2bd5f34abb4469653bdfabb12e6b13e3ca1d7c147fae81 | Hash of the transactions in which this event was emitted     |
| log\_index            | INTEGER   | 56                                                                 | Integer of the log index position in the block of this event |
| contract\_address     | VARCHAR   | 0x0000000000e655fae4d56241588680f86e3b2377                         | Address of the contract that produced the log                |
| strategyId            | VARCHAR   | 0                                                                  |                                                              |
| standardProtocolFeeBp | VARCHAR   | 50                                                                 |                                                              |
| minTotalFeeBp         | VARCHAR   | 50                                                                 |                                                              |
| maxProtocolFeeBp      | VARCHAR   | 200                                                                |                                                              |
| selector              | VARCHAR   | 0x00000000                                                         |                                                              |
| isMakerBid            | VARCHAR   | false                                                              |                                                              |
| implementation        | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 36. Table: LooksRareProtocolV2\_event\_OrderNoncesCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-12 18:41:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17245819                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5dc329f5fc0cec7b7dd06507137add537c52404e39dd84aee3054a28407afc27 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 197                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0000000000e655fae4d56241588680f86e3b2377                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xa1f47f4f69b19c39e219dcd3a030640b8cdf05cb                         |                                                              |
| orderNonces       | VARCHAR   | 0                                                                  |                                                              |

## 37. Table: LooksRareProtocolV2\_event\_StrategyUpdated\_history

| Column                | Type      | Example                                                      | Description |
| --------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp      | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number         | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash     | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index            | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address     | VARCHAR   | Address of the contract that produced the log                |             |
| strategyId            | VARCHAR   |                                                              |             |
| isActive              | VARCHAR   |                                                              |             |
| standardProtocolFeeBp | VARCHAR   |                                                              |             |
| minTotalFeeBp         | VARCHAR   |                                                              |             |

## 38. Table: LooksRareProtocolV2\_event\_SubsetNoncesCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-27 07:52:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17349030                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7f29276d52b4ddd0acb079513e979fc141e87654a5a2884bd77d7a3b7071d650 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 217                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0000000000e655fae4d56241588680f86e3b2377                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x1262b2d4578848e5c9b8f70899711e2cd343a092                         |                                                              |
| subsetNonces      | VARCHAR   | 0                                                                  |                                                              |

## 39. Table: LooksRareProtocolV2\_event\_TakerAsk\_history

| Column                                         | Type                                                                    | Example                                                                                              | Description                                                  |
| ---------------------------------------------- | ----------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp                               | TIMESTAMP                                                               | 2023-06-20 10:21:35+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number                                  | INTEGER                                                                 | 17520280                                                                                             | The block number where this event was emitted                |
| transaction\_hash                              | VARCHAR                                                                 | 0x1ecd3df5a7fcc0c09f984f0e1a822c7b3b3493d869537366530e92a7f6301d16                                   | Hash of the transactions in which this event was emitted     |
| log\_index                                     | INTEGER                                                                 | 195                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address                              | VARCHAR                                                                 | 0x0000000000e655fae4d56241588680f86e3b2377                                                           | Address of the contract that produced the log                |
| nonceInvalidationParameters                    | STRUCT\<orderHash STRING, orderNonce STRING, isNonceInvalidated STRING> | {'orderHash': '0x64a373b5fe71dc8a11132b9a18f5257e3db8020172e1b26800ac02e9de012178', 'orderNonce': '0 |                                                              |
| nonceInvalidationParameters.orderHash          | VARCHAR                                                                 | 0x64a373b5fe71dc8a11132b9a18f5257e3db8020172e1b26800ac02e9de012178                                   |                                                              |
| nonceInvalidationParameters.orderNonce         | VARCHAR                                                                 | 0                                                                                                    |                                                              |
| nonceInvalidationParameters.isNonceInvalidated | VARCHAR                                                                 | true                                                                                                 |                                                              |
| askUser                                        | VARCHAR                                                                 | 0x0cd373d4a9e912ce35a5cc18dc5b6546d043bcea                                                           |                                                              |
| bidUser                                        | VARCHAR                                                                 | 0x5411ba681b2d9fc74d2285bbdebfc7c44ec1b8df                                                           |                                                              |
| strategyId                                     | VARCHAR                                                                 | 0                                                                                                    |                                                              |
| currency                                       | VARCHAR                                                                 | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                                                           |                                                              |
| collection                                     | VARCHAR                                                                 | 0x57f1887a8bf19b14fc0df6fd9b2acc9af147ea85                                                           |                                                              |
| itemIds                                        | VARCHAR                                                                 | 110050834856472891498000422767014601990522820322367174992083125725804469744821                       |                                                              |
| amounts                                        | VARCHAR                                                                 | 1                                                                                                    |                                                              |
| feeRecipients                                  | VARCHAR                                                                 | 0x0Cd373D4a9E912cE35a5cc18DC5B6546D043Bcea,0x0000000000000000000000000000000000000000                |                                                              |
| feeAmounts                                     | VARCHAR                                                                 | 99500000000000,0,500000000000                                                                        |                                                              |

## 40. Table: LooksRareProtocolV2\_event\_TakerBid\_history

| Column                                         | Type                                                                    | Example                                                                                              | Description                                                  |
| ---------------------------------------------- | ----------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp                               | TIMESTAMP                                                               | 2023-07-17 07:30:11+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number                                  | INTEGER                                                                 | 17711501                                                                                             | The block number where this event was emitted                |
| transaction\_hash                              | VARCHAR                                                                 | 0x885fee05961da137346ba3bc868e3fda597e393edf6b0e54d6defeb9be70bf55                                   | Hash of the transactions in which this event was emitted     |
| log\_index                                     | INTEGER                                                                 | 406                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address                              | VARCHAR                                                                 | 0x0000000000e655fae4d56241588680f86e3b2377                                                           | Address of the contract that produced the log                |
| nonceInvalidationParameters                    | STRUCT\<orderHash STRING, orderNonce STRING, isNonceInvalidated STRING> | {'orderHash': '0x69f657e67ca82573153c4e80ed13a089446972acddc9e51844a64cdf0994e200', 'orderNonce': '1 |                                                              |
| nonceInvalidationParameters.orderHash          | VARCHAR                                                                 | 0x69f657e67ca82573153c4e80ed13a089446972acddc9e51844a64cdf0994e200                                   |                                                              |
| nonceInvalidationParameters.orderNonce         | VARCHAR                                                                 | 196028                                                                                               |                                                              |
| nonceInvalidationParameters.isNonceInvalidated | VARCHAR                                                                 | true                                                                                                 |                                                              |
| bidUser                                        | VARCHAR                                                                 | 0x38cff3c1cbb819228e5d9992ac67fa6a464e34af                                                           |                                                              |
| bidRecipient                                   | VARCHAR                                                                 | 0x38cff3c1cbb819228e5d9992ac67fa6a464e34af                                                           |                                                              |
| strategyId                                     | VARCHAR                                                                 | 0                                                                                                    |                                                              |
| currency                                       | VARCHAR                                                                 | 0x0000000000000000000000000000000000000000                                                           |                                                              |
| collection                                     | VARCHAR                                                                 | 0xd36008778fb80f7c6d122e9c84b6428e07414b18                                                           |                                                              |
| itemIds                                        | VARCHAR                                                                 | 746                                                                                                  |                                                              |
| amounts                                        | VARCHAR                                                                 | 1                                                                                                    |                                                              |
| feeRecipients                                  | VARCHAR                                                                 | 0x3a7f16B9B260B3D7f4EF55f3E402F253CF589446,0x0000000000000000000000000000000000000000                |                                                              |
| feeAmounts                                     | VARCHAR                                                                 | 4975000000000000,0,25000000000000                                                                    |                                                              |
