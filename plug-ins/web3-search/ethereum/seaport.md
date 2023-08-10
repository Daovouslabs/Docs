# seaport

## 1. Table: SeaportV11\_call\_cancel\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-05-23 05:46:59+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17319959                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x6f1fbceb44a86849062b97a5dac8a86fdbaabdca439ed8c11249fee1d258eb90                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 102                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| orders             | VARCHAR   | 0xD3E168445e4C7977354270eE0AF53c57e6bADB48,0x0000000000000000000000000000000000000092,2,0x46FdfCb3Cd |                                                                                                                        |

## 2. Table: SeaportV11\_call\_fulfillAdvancedOrder\_history

| Column              | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp    | TIMESTAMP | 2023-03-18 13:14:11+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number       | INTEGER   | 16854868                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash   | VARCHAR   | 0xea3695c617740e98166a5ad3630e74d1dde3fc826024114e7a90f2fcffb43b5e                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index  | INTEGER   | 11                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address      | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address         | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                                                           | Address of the called contract                                                                                         |
| status              | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error               | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| advancedOrder       | VARCHAR   | 0xcA345a3B6501A82c19dd8a459db0FcD39d123b05,0x0000000000000000000000000000000000000000,3,0xe7bB385693 |                                                                                                                        |
| criteriaResolvers   | VARCHAR   |                                                                                                      |                                                                                                                        |
| fulfillerConduitKey | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000                                   |                                                                                                                        |
| recipient           | VARCHAR   | 0x0000000000000000000000000000000000000000                                                           |                                                                                                                        |

## 3. Table: SeaportV11\_call\_fulfillAvailableAdvancedOrders\_history

| Column                    | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp          | TIMESTAMP | 2023-05-24 14:17:59+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number             | INTEGER   | 17329585                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash         | VARCHAR   | 0x3192067741ba3f4a928a6ea152f5502169bc97d2559f640da8ed02c1ec75fb3e                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index        | INTEGER   | 144                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address            | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address               | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                                                           | Address of the called contract                                                                                         |
| status                    | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                     | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| advancedOrders            | VARCHAR   | 0xD58Ae662065e4Bd16123785A4103c3ECDFb548Cd,0x0000000000000000000000000000000000000000,2,0xd384Ef9015 |                                                                                                                        |
| criteriaResolvers         | VARCHAR   |                                                                                                      |                                                                                                                        |
| offerFulfillments         | VARCHAR   | 0,0,1,0                                                                                              |                                                                                                                        |
| considerationFulfillments | VARCHAR   | 0,0,1,0,0,1,1,1                                                                                      |                                                                                                                        |
| fulfillerConduitKey       | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000                                   |                                                                                                                        |
| recipient                 | VARCHAR   | 0x0000000000000000000000000000000000000000                                                           |                                                                                                                        |
| maximumFulfilled          | VARCHAR   | 2                                                                                                    |                                                                                                                        |

## 4. Table: SeaportV11\_call\_fulfillAvailableOrders\_history

| Column                    | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp          | TIMESTAMP | 2022-08-09 03:22:44+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number             | INTEGER   | 15305580                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash         | VARCHAR   | 0xdf31d9e9c455a6d026963b66070e15c3a41c83a03c3f0ea070cd8034a84c2155                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index        | INTEGER   | 233                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address            | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address               | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                                                           | Address of the called contract                                                                                         |
| status                    | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                     | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| orders                    | VARCHAR   | 0x028a7fED2C0C692349a06c961a04E6064B3E821E,0x004C00500000aD104D7DBd00e3ae0A5C00560C00,2,0xdb7b094FdC |                                                                                                                        |
| offerFulfillments         | VARCHAR   | 0,0,1,0                                                                                              |                                                                                                                        |
| considerationFulfillments | VARCHAR   | 0,0,0,1,1,1,1,0                                                                                      |                                                                                                                        |
| fulfillerConduitKey       | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000                                   |                                                                                                                        |
| maximumFulfilled          | VARCHAR   | 2                                                                                                    |                                                                                                                        |

## 5. Table: SeaportV11\_call\_fulfillBasicOrder\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-04-12 13:51:11+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17032334                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xfa82edc32f4d3cc55e14117937572df324eb28e6990cda3dfc1b1a7f932b7476                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 64                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| parameters         | VARCHAR   | 0x0000000000000000000000000000000000000000,0,3750000000000000000,0xAAA90A5597F21179E4C83F0475DcEBaA7 |                                                                                                                        |

## 6. Table: SeaportV11\_call\_fulfillOrder\_history

| Column              | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp    | TIMESTAMP | 2023-06-06 21:38:59+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number       | INTEGER   | 17424121                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash   | VARCHAR   | 0x9e40222ad0ddd985c2de2ee2d62f345da6ff5099f3256423adfbc862e252c64a                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index  | INTEGER   | 91                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address      | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address         | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                                                           | Address of the called contract                                                                                         |
| status              | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error               | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| order               | VARCHAR   | 0x4E2795EF5999E65a8972Ed819FEd89B33b6b16EA,0x6c0E86b87Bb5AD0da88993A2E2fb56134AEcB183,2,0xED5AF38865 |                                                                                                                        |
| fulfillerConduitKey | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000                                   |                                                                                                                        |

## 7. Table: SeaportV11\_call\_getCounter\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-12-12 20:14:23+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16170939                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x40128151599419ab3580f4ede04ee03ab956891016a948d47456c829ea42e5d2 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 117                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| offerer            | VARCHAR   | 0x73c4818b537a4108d3e90dc83baabe80405c66d8                         |                                                                                                                        |

## 8. Table: SeaportV11\_call\_getOrderHash\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-06-16 05:39:47+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17490376                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xfc4777a04cc1434720e6f7e7f18a65c72fff529d7b0de36b85c33654b7cf0da2                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 103                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,1,6                                                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| order              | VARCHAR   | 0x0a53A4B4E58155ef11032dA214D4902B5783963c,0x0000000000000000000000000000000000000000,2,0xBA627f3d08 |                                                                                                                        |

## 9. Table: SeaportV11\_call\_getOrderStatus\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-06-23 10:59:23+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17541826                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x8d3014dc56a5fc6c8aa3ea840b8e566fe202f7c42ba6422d277799ecd1e4403c | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 70                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,1,0                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| orderHash          | VARCHAR   | 0xfdc9b5e412a570fbd52145844208eeb514cf4e0baf95caebd9e3738a38bcbbb4 |                                                                                                                        |

## 10. Table: SeaportV11\_call\_incrementCounter\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-11-11 15:45:11+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15947753                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x6e6218ec699e78b59fa1761a37e10a6ea88b00e8231942053344d455aea8f269 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 260                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 11. Table: SeaportV11\_call\_information\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-09-26 11:01:11+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15617116                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xaca427a6744bc7c51a1a16c02c02af5ea20bf6834b7781006824c98503471665 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 24                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 12. Table: SeaportV11\_call\_matchAdvancedOrders\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-11-13 19:42:59+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15963268                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xc58d0afed9308e5d7411fb2c829548ec871d454d704f4ee3023b1fb124facdac                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 177                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| advancedOrders     | VARCHAR   | 0xD520F4Fa8F2104630DCa20e0eC143859931381BE,0x004C00500000aD104D7DBd00e3ae0A5C00560C00,3,0xbcd114D425 |                                                                                                                        |
| criteriaResolvers  | VARCHAR   |                                                                                                      |                                                                                                                        |
| fulfillments       | VARCHAR   | 0,0,0,3,1,0,0,0,1,0,0,1,1,0,0,2                                                                      |                                                                                                                        |

## 13. Table: SeaportV11\_call\_matchOrders\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-05-10 18:47:47+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17231868                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x6c938d2a7ac54ec83469474955d15c02999bff457140f67e65629644e35dbb9d                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 11                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| orders             | VARCHAR   | 0xdE66E07518f8C35F80Ef08D50d7943BF9C10d62b,0x004C00500000aD104D7DBd00e3ae0A5C00560C00,2,0x9401518f4E |                                                                                                                        |
| fulfillments       | VARCHAR   | 0,0,0,0                                                                                              |                                                                                                                        |

## 14. Table: SeaportV11\_call\_name\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-12-06 11:02:59+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16125328                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x15886a34f36c56659096e3ba22cf17d998dee59a0730ba422ae14e2617dd8b80 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 7                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 1,5                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 15. Table: SeaportV11\_call\_validate\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-05-18 16:30:47+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17287636                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xc0898240d9fd70e0173d897969a1eb967306ef6e6bc1f922a203459cfdaeb803                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 85                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,1,0,1,0,1,6                                                                                        | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| orders             | VARCHAR   | 0x03FCf6e8B2267E4d307E1f0944c230A03aD49933,0x455AD0f677628ed40E7397Fb41818f474e0E5afE,2,0x9ff70d5288 |                                                                                                                        |

## 16. Table: SeaportV11\_event\_CounterIncremented\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-30 17:22:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15245115                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa12a0ddcf411f7744d09d9a9b4ef4aac00631caadd15edb302ea1f76b6edc541 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 82                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                         | Address of the contract that produced the log                |
| newCounter        | VARCHAR   | 1                                                                  |                                                              |
| offerer           | VARCHAR   | 0x7c393af40654e7948fbfb6cab689f580f6d61d3d                         |                                                              |

## 17. Table: SeaportV11\_event\_OrderCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-25 20:08:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17338432                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1e737167bf4009bb5787672dfe161351aa1960faebafcc6ee22aa36e95ea9d69 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 160                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0x4887dba66bc57b2dd7b7f2f0a72a503d28a57d4983212be5e957ef02337bf4f1 |                                                              |
| offerer           | VARCHAR   | 0x2b4ebc796044f19ecf34526659bbed6c35e3ec11                         |                                                              |
| zone              | VARCHAR   | 0x004c00500000ad104d7dbd00e3ae0a5c00560c00                         |                                                              |

## 18. Table: SeaportV11\_event\_OrderFulfilled\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-03 22:30:23+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17837454                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6f4feec65c493d78ea14c7f48f0a539438d0ed7d7c3cbc0e2503aac9ee392f68                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 417                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                                                           | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0xa7a687cd942da66d092a5695afdb8ddadb46f43fe153ea01336a79a1f7041fa7                                   |                                                              |
| offerer           | VARCHAR   | 0x5fcb010a9e6dcf9907a4b3e306aade814b093bae                                                           |                                                              |
| zone              | VARCHAR   | 0x0000000000000000000000000000000000000000                                                           |                                                              |
| recipient         | VARCHAR   | 0xf5eae2b022e4848da04a616c55cf4ef47cc742c5                                                           |                                                              |
| offer             | VARCHAR   | 2,0xe14320D9BD60A137Ec0FE23CEF8ecBAC9041d3aa,103,1                                                   |                                                              |
| consideration     | VARCHAR   | 0,0x0000000000000000000000000000000000000000,0,20580000000000000,0x5fcB010A9e6Dcf9907a4B3e306aAde814 |                                                              |

## 19. Table: SeaportV11\_event\_OrderValidated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-25 06:59:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16902849                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x333277dfbdc6dd7b1361cde466f2212fc77f3dba7aee8b9ad311ac056a9b5b23 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 738                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0x3dbcb4b18a339869c659cc6e86f1edb676a2f0724c448ec69e637f959d19525f |                                                              |
| offerer           | VARCHAR   | 0x465e8e834132383c31002702c3ba2f40b25f47fe                         |                                                              |
| zone              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 20. Table: SeaportV12\_call\_fulfillAdvancedOrder\_history

| Column              | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp    | TIMESTAMP | 2023-02-09 18:00:11+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number       | INTEGER   | 16592843                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash   | VARCHAR   | 0xbd259a4d8c61c3ed1f84ae9dec7c297aa9657f31ab7b17040bd78efaac4bfbe5                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index  | INTEGER   | 223                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address      | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address         | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                                                           | Address of the called contract                                                                                         |
| status              | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error               | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| advancedOrder       | VARCHAR   | 0x1108f964b384f1dCDa03658B24310ccBc48E226F,0x0000000000000000000000000000000000000000,2,0x399F0c34c0 |                                                                                                                        |
| criteriaResolvers   | VARCHAR   |                                                                                                      |                                                                                                                        |
| fulfillerConduitKey | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000                                   |                                                                                                                        |
| recipient           | VARCHAR   | 0x26faf8ae18d15ed1ca0563727ad6d4aa02fb2f80                                                           |                                                                                                                        |

## 21. Table: SeaportV12\_call\_fulfillAvailableAdvancedOrders\_history

| Column                    | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp          | TIMESTAMP | 2023-02-15 00:24:11+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number             | INTEGER   | 16630542                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash         | VARCHAR   | 0x57f3d70230a261773ba966b255c078fb15595d34390c57b37c48a414ece40099                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index        | INTEGER   | 121                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address            | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address               | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                                                           | Address of the called contract                                                                                         |
| status                    | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                     | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| advancedOrders            | VARCHAR   | 0x1108f964b384f1dCDa03658B24310ccBc48E226F,0x0000000000000000000000000000000000000000,1,0xC02aaA39b2 |                                                                                                                        |
| criteriaResolvers         | VARCHAR   | 0,1,0,15,0x944998273e477b495144fb8794c914197f3ccb46be2900f4698fd0ef743c9695,0xbf77a305b88e4009391844 |                                                                                                                        |
| offerFulfillments         | VARCHAR   | 0,0,1,0,2,0,3,0,4,0                                                                                  |                                                                                                                        |
| considerationFulfillments | VARCHAR   | 0,1,1,1,2,1,3,1,4,1,0,2,1,2,2,2,3,2,4,2,0,0,1,0,2,0,3,0,4,0                                          |                                                                                                                        |
| fulfillerConduitKey       | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000                                   |                                                                                                                        |
| recipient                 | VARCHAR   | 0x0000000000000000000000000000000000000000                                                           |                                                                                                                        |
| maximumFulfilled          | VARCHAR   | 5                                                                                                    |                                                                                                                        |

## 22. Table: SeaportV12\_call\_fulfillAvailableOrders\_history

| Column                    | Type      | Example                                                            | Description                                                                                                            |
| ------------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp          | TIMESTAMP | 2023-02-16 23:41:59+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number             | INTEGER   | 16644643                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash         | VARCHAR   | 0xaa548ade536ee0dc1d54eb9d498cf92390406b9efb35bba14d8d91567994e714 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index        | INTEGER   | 103                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address            | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address               | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                         | Address of the called contract                                                                                         |
| status                    | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                     | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| availableOrders           | VARCHAR   | None                                                               |                                                                                                                        |
| offerFulfillments         | VARCHAR   | 0,0,1,0,2,0                                                        |                                                                                                                        |
| considerationFulfillments | VARCHAR   | 0,0,1,0,1,2,2,0,2,2,0,1,1,1,2,1                                    |                                                                                                                        |
| fulfillerConduitKey       | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000 |                                                                                                                        |
| maximumFulfilled          | VARCHAR   | 3                                                                  |                                                                                                                        |

## 23. Table: SeaportV12\_call\_fulfillBasicOrder\_efficient\_6GL6yc\_history

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
| parameters         | VARCHAR   |                                                                                                                        |             |

## 24. Table: SeaportV12\_call\_fulfillBasicOrder\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-02-10 05:43:23+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16596342                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xed59acb01b2d637ac3c3b48296cdaf418e0c4b908fc446e0b7580261e21105d0                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 40                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| parameters         | VARCHAR   | 0x0000000000000000000000000000000000000000,0,88000000000000000,0x3e6a203ab73C4B35Be1F65461D88Fb21DE2 |                                                                                                                        |

## 25. Table: SeaportV12\_call\_fulfillOrder\_history

| Column              | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp    | TIMESTAMP | 2023-02-09 23:01:59+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number       | INTEGER   | 16594342                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash   | VARCHAR   | 0x17f5e221a42e38c75f47f50089cc08da225c85615983f578dd6be60c62e9ce02                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index  | INTEGER   | 120                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address      | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address         | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                                                           | Address of the called contract                                                                                         |
| status              | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error               | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| order               | VARCHAR   | 0x1108f964b384f1dCDa03658B24310ccBc48E226F,0x0000000000000000000000000000000000000000,2,0x7aEF9E55bA |                                                                                                                        |
| fulfillerConduitKey | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000                                   |                                                                                                                        |

## 26. Table: SeaportV12\_call\_getOrderHash\_history

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
| orderComponents    | VARCHAR   |                                                                                                                        |             |

## 27. Table: SeaportV12\_call\_information\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-03-29 20:12:35+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16935232                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xda270b3b9aa2f1fb3752340dea8fe2786aa9ec9ea925fdd0d3d33b505d790163 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 36                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 28. Table: SeaportV12\_call\_matchAdvancedOrders\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-02-21 02:01:35+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16673782                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x448b3623e0439342f7b938ef82452ff0c42bf1ea9bd02a230938f043e48e309d                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 50                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| advancedOrders     | VARCHAR   | 0x4d41232B0d963AFb52cd0354DA5819b259F133BD,0x0000000000000000000000000000000000000000,1,0xC02aaA39b2 |                                                                                                                        |
| criteriaResolvers  | VARCHAR   | 0,1,0,24,0xbb7b4a454dc3493923482f07822329ed19e8244eff582cc204f8554c3620c3fd,0x34f95582565a5ff11479f6 |                                                                                                                        |
| fulfillments       | VARCHAR   | 1,0,0,0,0,0,0,1,0,0,1,0,0,0,1,1                                                                      |                                                                                                                        |
| recipient          | VARCHAR   | 0x1108f964b384f1dcda03658b24310ccbc48e226f                                                           |                                                                                                                        |

## 29. Table: SeaportV12\_call\_matchOrders\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-02-09 23:14:11+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16594403                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xbcf1621886b00a9b5a7b5553eca0366d6a23e5c250609d54bb8e8e7451b28cbc                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 99                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| orders             | VARCHAR   | 0xfBa662e1a8e91a350702cF3b87D0C2d2Fb4BA57F,0x0000000000000000000000000000000000000000,2,0x0Cdd3Cb3bC |                                                                                                                        |
| fulfillments       | VARCHAR   | 0,0,0,2,0,1,0,3,1,0,0,0,1,0,0,1                                                                      |                                                                                                                        |

## 30. Table: SeaportV12\_call\_validate\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-04-28 03:42:11+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17142025                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xea828d017d436bdb2216108c6f57a9f7fd6e30fa0c44b8376d13f3c619d58be4                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 166                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,1,0,1,0,1,6                                                                                        | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| orders             | VARCHAR   | 0x5E0925DF6949DE85D71cf0C57CC6B6BDAB1D7556,0x455AD0f677628ed40E7397Fb41818f474e0E5afE,2,0xF210D5d9DC |                                                                                                                        |

## 31. Table: SeaportV12\_event\_CounterIncremented\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-14 20:00:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16629234                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x311cc26619aab8894be550b220451e71766cac23a51d969ea180320f1de5f135 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 145                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                         | Address of the contract that produced the log                |
| newCounter        | VARCHAR   | 230792687360512546078323470027220706316                            |                                                              |
| offerer           | VARCHAR   | 0xa1d6ae0d6d7c539fda043bec4eb8c91201071223                         |                                                              |

## 32. Table: SeaportV12\_event\_OrderCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-09 18:20:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16592945                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x96870d72997b2bf463e06693af2055828f6059d5f644c098d0ecc2de80b68359 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 144                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0x56c9302eb1154d45a4cbefe0c0f1f392aec80c4f6151461a92ecd05aecfe6eb6 |                                                              |
| offerer           | VARCHAR   | 0x1108f964b384f1dcda03658b24310ccbc48e226f                         |                                                              |
| zone              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 33. Table: SeaportV12\_event\_OrderFulfilled\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-09 20:19:35+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16593536                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5d05f6f8e6917f095a11c0239f3a6000b1da4e78efa6b830d125a2d7820266dd                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 116                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                                                           | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0xcd3284a67858ac789f16748cf91fc3b056a55d62bb40b726250f29547101a086                                   |                                                              |
| offerer           | VARCHAR   | 0x1108f964b384f1dcda03658b24310ccbc48e226f                                                           |                                                              |
| zone              | VARCHAR   | 0x0000000000000000000000000000000000000000                                                           |                                                              |
| recipient         | VARCHAR   | 0x1108f964b384f1dcda03658b24310ccbc48e226f                                                           |                                                              |
| offer             | VARCHAR   | 2,0x2a0EabeC3d1D3e6990F2974349CC0CeB3e696d48,2,1                                                     |                                                              |
| consideration     | VARCHAR   | 1,0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2,0,2841700000000000,0x1108f964b384f1dCDa03658B24310ccBc4 |                                                              |

## 34. Table: SeaportV12\_event\_OrderValidated\_history

| Column                                          | Type                                                                                                                                                                                                                  | Example                                                                                              | Description                                                  |
| ----------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp                                | TIMESTAMP                                                                                                                                                                                                             | 2023-04-28 03:36:11+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number                                   | INTEGER                                                                                                                                                                                                               | 17141995                                                                                             | The block number where this event was emitted                |
| transaction\_hash                               | VARCHAR                                                                                                                                                                                                               | 0xcfaa33a49faebd871ff5a0bbdee5380af069653c7604e51170ab52765d615114                                   | Hash of the transactions in which this event was emitted     |
| log\_index                                      | INTEGER                                                                                                                                                                                                               | 252                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address                               | VARCHAR                                                                                                                                                                                                               | 0x00000000000006c7676171937c444f6bde3d6282                                                           | Address of the contract that produced the log                |
| orderHash                                       | VARCHAR                                                                                                                                                                                                               | 0xeaf7e233480c436f19f68523b3072fa525fe1d1db720aba32baa5626e8841704                                   |                                                              |
| orderParameters                                 | STRUCT\<offerer STRING, zone STRING, offer STRING, consideration STRING, orderType STRING, startTime STRING, endTime STRING, zoneHash STRING, salt STRING, conduitKey STRING, totalOriginalConsiderationItems STRING> | {'offerer': '0x9a4c64721c59bffb133c109879cb0188c149860b', 'zone': '0x455ad0f677628ed40e7397fb41818f4 |                                                              |
| orderParameters.offerer                         | VARCHAR                                                                                                                                                                                                               | 0x9a4c64721c59bffb133c109879cb0188c149860b                                                           |                                                              |
| orderParameters.zone                            | VARCHAR                                                                                                                                                                                                               | 0x455ad0f677628ed40e7397fb41818f474e0e5afe                                                           |                                                              |
| orderParameters.offer                           | VARCHAR                                                                                                                                                                                                               | 2,0xF210D5d9DCF958803C286A6f8E278e4aC78e136E,512,1,1                                                 |                                                              |
| orderParameters.consideration                   | VARCHAR                                                                                                                                                                                                               | 1,0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2,0,150000000000000000,1000,0x9a4C64721c59bFfb133C109879C |                                                              |
| orderParameters.orderType                       | VARCHAR                                                                                                                                                                                                               | 0                                                                                                    |                                                              |
| orderParameters.startTime                       | VARCHAR                                                                                                                                                                                                               | 1682652971                                                                                           |                                                              |
| orderParameters.endTime                         | VARCHAR                                                                                                                                                                                                               | 1682912171                                                                                           |                                                              |
| orderParameters.zoneHash                        | VARCHAR                                                                                                                                                                                                               | 0x02e7e2afa37a82f80ddccd798b221238e3819088697ad47a05ef97a9fd6407d1                                   |                                                              |
| orderParameters.salt                            | VARCHAR                                                                                                                                                                                                               | 106519435855244136253761551138979972673905645077627796316676077418298561697443                       |                                                              |
| orderParameters.conduitKey                      | VARCHAR                                                                                                                                                                                                               | 0x455ad0f677628ed40e7397fb41818f474e0e5afe000000000000000000000000                                   |                                                              |
| orderParameters.totalOriginalConsiderationItems | VARCHAR                                                                                                                                                                                                               | 2                                                                                                    |                                                              |

## 35. Table: SeaportV12\_event\_OrdersMatched\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-10 17:52:11+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16599965                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcab9df9c497f514cbb16f2808a63f6224ee9d1d684c1473c50ea3a3aebeddf52                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 212                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                                                           | Address of the contract that produced the log                |
| orderHashes       | VARCHAR   | 0x199ee111792388a5dd2fbc6636636c357f77671853442f154b4c2d1fa3c2bb2a,0x9418a22388cc9d1678f37c5aaf69da2 |                                                              |

## 36. Table: SeaportV13\_call\_cancel\_history

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
| orders             | VARCHAR   |                                                                                                                        |             |

## 37. Table: SeaportV13\_call\_fulfillAdvancedOrder\_history

| Column              | Type      | Example                                                                                                                | Description |
| ------------------- | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp    | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number       | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash   | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index  | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address      | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address         | VARCHAR   | Address of the called contract                                                                                         |             |
| status              | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error               | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| advancedOrder       | VARCHAR   |                                                                                                                        |             |
| criteriaResolvers   | VARCHAR   |                                                                                                                        |             |
| fulfillerConduitKey | VARCHAR   |                                                                                                                        |             |
| recipient           | VARCHAR   |                                                                                                                        |             |

## 38. Table: SeaportV13\_call\_fulfillAvailableAdvancedOrders\_history

| Column                    | Type      | Example                                                                                                                | Description |
| ------------------------- | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp          | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number             | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash         | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index        | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address            | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address               | VARCHAR   | Address of the called contract                                                                                         |             |
| status                    | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error                     | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| advancedOrders            | VARCHAR   |                                                                                                                        |             |
| criteriaResolvers         | VARCHAR   |                                                                                                                        |             |
| offerFulfillments         | VARCHAR   |                                                                                                                        |             |
| considerationFulfillments | VARCHAR   |                                                                                                                        |             |
| fulfillerConduitKey       | VARCHAR   |                                                                                                                        |             |
| recipient                 | VARCHAR   |                                                                                                                        |             |
| maximumFulfilled          | VARCHAR   |                                                                                                                        |             |

## 39. Table: SeaportV13\_call\_fulfillAvailableOrders\_history

| Column                    | Type      | Example                                                                                                                | Description |
| ------------------------- | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp          | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number             | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash         | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index        | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address            | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address               | VARCHAR   | Address of the called contract                                                                                         |             |
| status                    | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error                     | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| orders                    | VARCHAR   |                                                                                                                        |             |
| offerFulfillments         | VARCHAR   |                                                                                                                        |             |
| considerationFulfillments | VARCHAR   |                                                                                                                        |             |
| fulfillerConduitKey       | VARCHAR   |                                                                                                                        |             |
| maximumFulfilled          | VARCHAR   |                                                                                                                        |             |

## 40. Table: SeaportV13\_call\_fulfillBasicOrder\_efficient\_6GL6yc\_history

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
| parameters         | VARCHAR   |                                                                                                                        |             |

## 41. Table: SeaportV13\_call\_fulfillBasicOrder\_history

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
| parameters         | VARCHAR   |                                                                                                                        |             |

## 42. Table: SeaportV13\_call\_fulfillOrder\_history

| Column              | Type      | Example                                                                                                                | Description |
| ------------------- | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp    | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number       | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash   | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index  | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address      | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address         | VARCHAR   | Address of the called contract                                                                                         |             |
| status              | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error               | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| order               | VARCHAR   |                                                                                                                        |             |
| fulfillerConduitKey | VARCHAR   |                                                                                                                        |             |

## 43. Table: SeaportV13\_call\_getContractOffererNonce\_history

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
| contractOfferer    | VARCHAR   |                                                                                                                        |             |

## 44. Table: SeaportV13\_call\_getCounter\_history

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
| offerer            | VARCHAR   |                                                                                                                        |             |

## 45. Table: SeaportV13\_call\_getOrderHash\_history

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

## 46. Table: SeaportV13\_call\_getOrderStatus\_history

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
| orderHash          | VARCHAR   |                                                                                                                        |             |

## 47. Table: SeaportV13\_call\_incrementCounter\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-02-17 00:18:35+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16644824                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x09009a86090a1429b728060fc04db57a96eb59f1d612067b4f419d821ae6dd14 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 89                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x0000000000000ad24e80fd803c6ac37206a45f15                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 48. Table: SeaportV13\_call\_information\_history

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

## 49. Table: SeaportV13\_call\_matchAdvancedOrders\_history

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
| orders             | VARCHAR   |                                                                                                                        |             |
| criteriaResolvers  | VARCHAR   |                                                                                                                        |             |
| fulfillments       | VARCHAR   |                                                                                                                        |             |
| recipient          | VARCHAR   |                                                                                                                        |             |

## 50. Table: SeaportV13\_call\_matchOrders\_history

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
| orders             | VARCHAR   |                                                                                                                        |             |
| fulfillments       | VARCHAR   |                                                                                                                        |             |

## 51. Table: SeaportV13\_call\_name\_history

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

## 52. Table: SeaportV13\_call\_validate\_history

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
| orders             | VARCHAR   |                                                                                                                        |             |

## 53. Table: SeaportV13\_event\_CounterIncremented\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-17 00:18:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16644824                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x09009a86090a1429b728060fc04db57a96eb59f1d612067b4f419d821ae6dd14 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 307                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0000000000000ad24e80fd803c6ac37206a45f15                         | Address of the contract that produced the log                |
| newCounter        | VARCHAR   | 273633471673624237170708155612434093579                            |                                                              |
| offerer           | VARCHAR   | 0x939c8d89ebc11fa45e576215e2353673ad0ba18a                         |                                                              |

## 54. Table: SeaportV13\_event\_OrderCancelled\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| orderHash         | VARCHAR   |                                                              |             |
| offerer           | VARCHAR   |                                                              |             |
| zone              | VARCHAR   |                                                              |             |

## 55. Table: SeaportV13\_event\_OrderFulfilled\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| orderHash         | VARCHAR   |                                                              |             |
| offerer           | VARCHAR   |                                                              |             |
| zone              | VARCHAR   |                                                              |             |
| recipient         | VARCHAR   |                                                              |             |
| offer             | VARCHAR   |                                                              |             |
| consideration     | VARCHAR   |                                                              |             |

## 56. Table: SeaportV13\_event\_OrderValidated\_history

| Column                                          | Type                                                                                                                                                                                                                  | Example                                                      | Description |
| ----------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp                                | TIMESTAMP                                                                                                                                                                                                             | Timestamp of the block where this event was emitted          |             |
| block\_number                                   | INTEGER                                                                                                                                                                                                               | The block number where this event was emitted                |             |
| transaction\_hash                               | VARCHAR                                                                                                                                                                                                               | Hash of the transactions in which this event was emitted     |             |
| log\_index                                      | INTEGER                                                                                                                                                                                                               | Integer of the log index position in the block of this event |             |
| contract\_address                               | VARCHAR                                                                                                                                                                                                               | Address of the contract that produced the log                |             |
| orderHash                                       | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters                                 | STRUCT\<offerer STRING, zone STRING, offer STRING, consideration STRING, orderType STRING, startTime STRING, endTime STRING, zoneHash STRING, salt STRING, conduitKey STRING, totalOriginalConsiderationItems STRING> |                                                              |             |
| orderParameters.offerer                         | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters.zone                            | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters.offer                           | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters.consideration                   | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters.orderType                       | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters.startTime                       | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters.endTime                         | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters.zoneHash                        | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters.salt                            | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters.conduitKey                      | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters.totalOriginalConsiderationItems | VARCHAR                                                                                                                                                                                                               |                                                              |             |

## 57. Table: SeaportV13\_event\_OrdersMatched\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| orderHashes       | VARCHAR   |                                                              |             |

## 58. Table: SeaportV14\_event\_CounterIncremented\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-09 17:42:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17444218                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa668c90b4d5dc2ef7bb46ac8027325e9a98bd6bd7c23fb1b4cfbe6a267044193 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 514                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000000adc04c56bf30ac9d3c0aaf14dc                         | Address of the contract that produced the log                |
| newCounter        | VARCHAR   | 5085256096288733776959375897240430596                              |                                                              |
| offerer           | VARCHAR   | 0x2b6ea4917ce701e6b2a916e65b07af608ab390ff                         |                                                              |

## 59. Table: SeaportV14\_event\_OrderCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-13 05:14:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17468931                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6f79ce4ccca89fb76dda5075b9f2a058477d0c7f53dbc15ff423b70a7bc0f95e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 222                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000000adc04c56bf30ac9d3c0aaf14dc                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0xbdfc8b40045894d5960bc71125181289d53fd999da056285f14b7cf1ba593563 |                                                              |
| offerer           | VARCHAR   | 0x092d4d0fdbc90e44a386397932383c9b4c135a52                         |                                                              |
| zone              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 60. Table: SeaportV14\_event\_OrderFulfilled\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-02 01:11:11+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16737536                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd74057bb4f5c33a41f3d20ce89d554259d594ffcfb2ecfa1a3a72acc07c59ec3                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 130                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000001ad428e4906ae43d8f9852d0dd6                                                           | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0x001a7af5a8c623a42951b5f342dfbc74a0871cb2dda7c958e22bcee1cb72e634                                   |                                                              |
| offerer           | VARCHAR   | 0xa55e2aa7c8bdb28c761c64feabb3cbc12ee64cb4                                                           |                                                              |
| zone              | VARCHAR   | 0x004c00500000ad104d7dbd00e3ae0a5c00560c00                                                           |                                                              |
| recipient         | VARCHAR   | 0xf7c5db97cabc4b4d37f5e5846a4d32f7259531b2                                                           |                                                              |
| offer             | VARCHAR   | 2,0xc068efBF9009dCF06a5783f8BB8cac66311DfAB5,3475,1                                                  |                                                              |
| consideration     | VARCHAR   | 0,0x0000000000000000000000000000000000000000,0,9450000000000000,0xA55E2AA7C8BdB28c761C64FeABb3Cbc12E |                                                              |

## 61. Table: SeaportV14\_event\_OrderValidated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-28 11:29:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17791267                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xde70a97638fb2efee048ff18c64c65c68df8e8681b4d31b4f1c85f597c2165a0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 263                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000000adc04c56bf30ac9d3c0aaf14dc                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0x714b431cdebafc1b2dcc60bf5e7ec99154afdcece3dddc6de1eae318e8919da0 |                                                              |
| orderParameters   | VARCHAR   | \[object Object]                                                   |                                                              |

## 62. Table: SeaportV14\_event\_OrdersMatched\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-27 23:23:23+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17573929                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x327d8a3fc7af86c6af8813bad4530c26f271da7b086b0ed5c4eac59c11b4acd1                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000000adc04c56bf30ac9d3c0aaf14dc                                                           | Address of the contract that produced the log                |
| orderHashes       | VARCHAR   | 0xbc1e39d3676886e01fa47dc7d03dd96f7539a49ff295a1ec7a9bf665a2f78b68,0x5e3e9dc736d43a11bc5d1cae0dd4faf |                                                              |

## 63. Table: SeaportV21\_call\_fulfillAdvancedOrder\_history

| Column              | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp    | TIMESTAMP | 2023-02-09 18:00:11+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number       | INTEGER   | 16592843                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash   | VARCHAR   | 0xbd259a4d8c61c3ed1f84ae9dec7c297aa9657f31ab7b17040bd78efaac4bfbe5                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index  | INTEGER   | 223                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address      | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address         | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                                                           | Address of the called contract                                                                                         |
| status              | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error               | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| advancedOrder       | VARCHAR   | 0x1108f964b384f1dCDa03658B24310ccBc48E226F,0x0000000000000000000000000000000000000000,2,0x399F0c34c0 |                                                                                                                        |
| criteriaResolvers   | VARCHAR   |                                                                                                      |                                                                                                                        |
| fulfillerConduitKey | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000                                   |                                                                                                                        |
| recipient           | VARCHAR   | 0x26faf8ae18d15ed1ca0563727ad6d4aa02fb2f80                                                           |                                                                                                                        |

## 64. Table: SeaportV21\_call\_fulfillAvailableAdvancedOrders\_history

| Column                    | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp          | TIMESTAMP | 2023-02-15 00:24:11+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number             | INTEGER   | 16630542                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash         | VARCHAR   | 0x57f3d70230a261773ba966b255c078fb15595d34390c57b37c48a414ece40099                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index        | INTEGER   | 121                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address            | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address               | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                                                           | Address of the called contract                                                                                         |
| status                    | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                     | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| advancedOrders            | VARCHAR   | 0x1108f964b384f1dCDa03658B24310ccBc48E226F,0x0000000000000000000000000000000000000000,1,0xC02aaA39b2 |                                                                                                                        |
| criteriaResolvers         | VARCHAR   | 0,1,0,15,0x944998273e477b495144fb8794c914197f3ccb46be2900f4698fd0ef743c9695,0xbf77a305b88e4009391844 |                                                                                                                        |
| offerFulfillments         | VARCHAR   | 0,0,1,0,2,0,3,0,4,0                                                                                  |                                                                                                                        |
| considerationFulfillments | VARCHAR   | 0,1,1,1,2,1,3,1,4,1,0,2,1,2,2,2,3,2,4,2,0,0,1,0,2,0,3,0,4,0                                          |                                                                                                                        |
| fulfillerConduitKey       | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000                                   |                                                                                                                        |
| recipient                 | VARCHAR   | 0x0000000000000000000000000000000000000000                                                           |                                                                                                                        |
| maximumFulfilled          | VARCHAR   | 5                                                                                                    |                                                                                                                        |

## 65. Table: SeaportV21\_call\_fulfillAvailableOrders\_history

| Column                    | Type      | Example                                                            | Description                                                                                                            |
| ------------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp          | TIMESTAMP | 2023-02-10 17:42:11+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number             | INTEGER   | 16599915                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash         | VARCHAR   | 0x2da21437a3010f49251e581ebb3f6c1a9980b18aa5d27d59a262426bd5029202 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index        | INTEGER   | 111                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address            | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address               | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                         | Address of the called contract                                                                                         |
| status                    | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                     | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| availableOrders           | VARCHAR   | None                                                               |                                                                                                                        |
| offerFulfillments         | VARCHAR   | 0,0,1,0,2,0                                                        |                                                                                                                        |
| considerationFulfillments | VARCHAR   | 0,0,1,0,2,0,0,1,1,1,2,1                                            |                                                                                                                        |
| fulfillerConduitKey       | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000 |                                                                                                                        |
| maximumFulfilled          | VARCHAR   | 3                                                                  |                                                                                                                        |

## 66. Table: SeaportV21\_call\_fulfillBasicOrder\_efficient\_6GL6yc\_history

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
| parameters         | VARCHAR   |                                                                                                                        |             |

## 67. Table: SeaportV21\_call\_fulfillBasicOrder\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-02-13 14:39:47+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16620491                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xa0deb0bdc8f679dcd8f5ed3ed71423370ff0634b31c202ef82a686b171018171                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 100                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| parameters         | VARCHAR   | 0x0000000000000000000000000000000000000000,0,5000000000000000,0x308dbb6F679c4E2c90b49833793fc1Ab08E7 |                                                                                                                        |

## 68. Table: SeaportV21\_call\_fulfillOrder\_history

| Column              | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp    | TIMESTAMP | 2023-02-09 21:16:23+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number       | INTEGER   | 16593818                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash   | VARCHAR   | 0xa277714c6c03d1c8034915e9d2106ec6e01bee22eba37a9595b3d266875493f6                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index  | INTEGER   | 82                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address      | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address         | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                                                           | Address of the called contract                                                                                         |
| status              | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error               | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| order               | VARCHAR   | 0x1108f964b384f1dCDa03658B24310ccBc48E226F,0x0000000000000000000000000000000000000000,2,0xbD115428DD |                                                                                                                        |
| fulfillerConduitKey | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000                                   |                                                                                                                        |

## 69. Table: SeaportV21\_call\_getOrderHash\_history

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
| orderComponents    | VARCHAR   |                                                                                                                        |             |

## 70. Table: SeaportV21\_call\_information\_history

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

## 71. Table: SeaportV21\_call\_matchAdvancedOrders\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-02-14 02:51:23+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16624128                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x3cf77cfe619c5316d3137adb025d9ce006e3a566d52b760bee5891a275dc349e                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 165                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| advancedOrders     | VARCHAR   | 0x4d41232B0d963AFb52cd0354DA5819b259F133BD,0x0000000000000000000000000000000000000000,1,0xC02aaA39b2 |                                                                                                                        |
| criteriaResolvers  | VARCHAR   | 0,1,0,24,0xb10e2d527612073b26eecdfd717e6a320cf44b4afac2b0732d9fcbe2b7fa0cf6,0x2aab0be82a8c66f54ede20 |                                                                                                                        |
| fulfillments       | VARCHAR   | 1,0,0,0,0,0,0,1,0,0,0,2,0,0,1,0                                                                      |                                                                                                                        |
| recipient          | VARCHAR   | 0x1108f964b384f1dcda03658b24310ccbc48e226f                                                           |                                                                                                                        |

## 72. Table: SeaportV21\_call\_matchOrders\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-02-09 23:16:35+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16594415                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xce4dd94595008480f8c4c8385082bc7fb124a164920a11a910d725b619323d18                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 84                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| orders             | VARCHAR   | 0xfBa662e1a8e91a350702cF3b87D0C2d2Fb4BA57F,0x0000000000000000000000000000000000000000,2,0x0Cdd3Cb3bC |                                                                                                                        |
| fulfillments       | VARCHAR   | 0,0,0,2,0,1,0,3,1,0,0,0,1,0,0,1                                                                      |                                                                                                                        |

## 73. Table: SeaportV21\_call\_validate\_history

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
| orders             | VARCHAR   |                                                                                                                        |             |

## 74. Table: SeaportV21\_event\_CounterIncremented\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-13 02:24:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16616833                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xea6d67bff2b37c65476b0ac71c57d026cff6e4ce8e972dfba3fbdb892c87e542 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 281                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                         | Address of the contract that produced the log                |
| newCounter        | VARCHAR   | 188860975044259640985216909915457864484                            |                                                              |
| offerer           | VARCHAR   | 0x3e6a203ab73c4b35be1f65461d88fb21de26446e                         |                                                              |

## 75. Table: SeaportV21\_event\_OrderCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-10 18:15:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16600083                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2ea2503872f35f7ca01c19590c3cf5b985ec0037bfab83c6f0c98cdc6b477877 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 223                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0x628a7a73211fa05f3db877106bee1ae603221a5c8dbe682909dc1dc4258163f0 |                                                              |
| offerer           | VARCHAR   | 0x4d41232b0d963afb52cd0354da5819b259f133bd                         |                                                              |
| zone              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 76. Table: SeaportV21\_event\_OrderFulfilled\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-09 20:19:35+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16593536                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5d05f6f8e6917f095a11c0239f3a6000b1da4e78efa6b830d125a2d7820266dd                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 116                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                                                           | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0xcd3284a67858ac789f16748cf91fc3b056a55d62bb40b726250f29547101a086                                   |                                                              |
| offerer           | VARCHAR   | 0x1108f964b384f1dcda03658b24310ccbc48e226f                                                           |                                                              |
| zone              | VARCHAR   | 0x0000000000000000000000000000000000000000                                                           |                                                              |
| recipient         | VARCHAR   | 0x1108f964b384f1dcda03658b24310ccbc48e226f                                                           |                                                              |
| offer             | VARCHAR   | 2,0x2a0EabeC3d1D3e6990F2974349CC0CeB3e696d48,2,1                                                     |                                                              |
| consideration     | VARCHAR   | 1,0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2,0,2841700000000000,0x1108f964b384f1dCDa03658B24310ccBc4 |                                                              |

## 77. Table: SeaportV21\_event\_OrderValidated\_history

| Column                                          | Type                                                                                                                                                                                                                  | Example                                                      | Description |
| ----------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp                                | TIMESTAMP                                                                                                                                                                                                             | Timestamp of the block where this event was emitted          |             |
| block\_number                                   | INTEGER                                                                                                                                                                                                               | The block number where this event was emitted                |             |
| transaction\_hash                               | VARCHAR                                                                                                                                                                                                               | Hash of the transactions in which this event was emitted     |             |
| log\_index                                      | INTEGER                                                                                                                                                                                                               | Integer of the log index position in the block of this event |             |
| contract\_address                               | VARCHAR                                                                                                                                                                                                               | Address of the contract that produced the log                |             |
| orderHash                                       | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters                                 | STRUCT\<offerer STRING, zone STRING, offer STRING, consideration STRING, orderType STRING, startTime STRING, endTime STRING, zoneHash STRING, salt STRING, conduitKey STRING, totalOriginalConsiderationItems STRING> |                                                              |             |
| orderParameters.offerer                         | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters.zone                            | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters.offer                           | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters.consideration                   | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters.orderType                       | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters.startTime                       | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters.endTime                         | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters.zoneHash                        | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters.salt                            | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters.conduitKey                      | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters.totalOriginalConsiderationItems | VARCHAR                                                                                                                                                                                                               |                                                              |             |

## 78. Table: SeaportV21\_event\_OrdersMatched\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-09 21:28:35+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16593879                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc9cefa07a52bdb1efde40bf4d4b6c0484742cf5689c6abe542d443e680b73962                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 257                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                                                           | Address of the contract that produced the log                |
| orderHashes       | VARCHAR   | 0x49763ddc5d8d02003148f1f3b7344f373bfa85588eed837a9f46eb4ac64213a0,0x18659b1af00d19a282fdb1188a62b57 |                                                              |

## 79. Table: Seaport\_call\_cancel\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-05-24 18:25:55+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14837223                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x39955e10c96688bed575bf7668ef127fea7a9ba106e723bd5edcca88f994dfd9                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 148                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000006cee72100d161c57ada5bb2be1ca79                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| orders             | VARCHAR   | 0x792b8795AFC44b620f9F93Ea42115ae7c773EdB4,0xF397619df7Bfd4D1657EA9bDd9DF7FF888731A11,1,0xC02aaA39b2 |                                                                                                                        |

## 80. Table: Seaport\_call\_fulfillAdvancedOrder\_history

| Column              | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp    | TIMESTAMP | 2022-06-06 19:08:52+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number       | INTEGER   | 14916569                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash   | VARCHAR   | 0xb5658b4302616bfed10e0a2e5f8dfc09efc7bfb8f9bb01a9d8deb9df16d97bdd                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index  | INTEGER   | 120                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address      | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address         | VARCHAR   | 0x00000000006cee72100d161c57ada5bb2be1ca79                                                           | Address of the called contract                                                                                         |
| status              | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error               | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| advancedOrder       | VARCHAR   | 0xA797f42711d317dF7e778B84A19B5783F1544364,0xF397619df7Bfd4D1657EA9bDd9DF7FF888731A11,3,0x3397e734F0 |                                                                                                                        |
| criteriaResolvers   | VARCHAR   |                                                                                                      |                                                                                                                        |
| fulfillerConduitKey | VARCHAR   | 0x939c8d89ebc11fa45e576215e2353673ad0ba18a71286b93e3954e004a000000                                   |                                                                                                                        |

## 81. Table: Seaport\_call\_fulfillAvailableAdvancedOrders\_history

| Column                    | Type      | Example                                                                                                                | Description |
| ------------------------- | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp          | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number             | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash         | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index        | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address            | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address               | VARCHAR   | Address of the called contract                                                                                         |             |
| status                    | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error                     | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| advancedOrders            | VARCHAR   |                                                                                                                        |             |
| criteriaResolvers         | VARCHAR   |                                                                                                                        |             |
| offerFulfillments         | VARCHAR   |                                                                                                                        |             |
| considerationFulfillments | VARCHAR   |                                                                                                                        |             |
| fulfillerConduitKey       | VARCHAR   |                                                                                                                        |             |
| maximumFulfilled          | VARCHAR   |                                                                                                                        |             |

## 82. Table: Seaport\_call\_fulfillAvailableOrders\_history

| Column                    | Type      | Example                                                                                                                | Description |
| ------------------------- | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp          | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number             | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash         | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index        | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address            | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address               | VARCHAR   | Address of the called contract                                                                                         |             |
| status                    | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error                     | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| orders                    | VARCHAR   |                                                                                                                        |             |
| offerFulfillments         | VARCHAR   |                                                                                                                        |             |
| considerationFulfillments | VARCHAR   |                                                                                                                        |             |
| fulfillerConduitKey       | VARCHAR   |                                                                                                                        |             |
| maximumFulfilled          | VARCHAR   |                                                                                                                        |             |

## 83. Table: Seaport\_call\_fulfillBasicOrder\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-06-03 16:55:14+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14898237                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x4e20c29fc60474a0cbd67d4f67432542c5172edb2dd5922547b1f78b6eb170c8                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 208                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000006cee72100d161c57ada5bb2be1ca79                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| parameters         | VARCHAR   | 0x0000000000000000000000000000000000000000,0,90000000000000000,0x5ae1283093f33C5F4C1e3a4F0C97d25EC78 |                                                                                                                        |

## 84. Table: Seaport\_call\_fulfillOrder\_history

| Column              | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp    | TIMESTAMP | 2022-05-20 18:56:58+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number       | INTEGER   | 14812782                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash   | VARCHAR   | 0xeb1e0dfafbfb59fb6569bc042f9fa044d9c869c911694b65684fcd6ee62bdec4                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index  | INTEGER   | 33                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address      | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address         | VARCHAR   | 0x00000000006cee72100d161c57ada5bb2be1ca79                                                           | Address of the called contract                                                                                         |
| status              | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error               | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| order               | VARCHAR   | 0xA797f42711d317dF7e778B84A19B5783F1544364,0xF397619df7Bfd4D1657EA9bDd9DF7FF888731A11,2,0x50075F151A |                                                                                                                        |
| fulfillerConduitKey | VARCHAR   | 0x939c8d89ebc11fa45e576215e2353673ad0ba18a71286b93e3954e004a000000                                   |                                                                                                                        |

## 85. Table: Seaport\_call\_getNonce\_history

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
| offerer            | VARCHAR   |                                                                                                                        |             |

## 86. Table: Seaport\_call\_getOrderHash\_history

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

## 87. Table: Seaport\_call\_getOrderStatus\_history

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
| orderHash          | VARCHAR   |                                                                                                                        |             |

## 88. Table: Seaport\_call\_incrementNonce\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-06-05 12:03:00+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14908993                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x8c24b9779315e63497b0780e6f66e9f359026daa5ae3f4a01bd7a85551221e9d | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 43                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000006cee72100d161c57ada5bb2be1ca79                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 89. Table: Seaport\_call\_information\_history

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

## 90. Table: Seaport\_call\_matchAdvancedOrders\_history

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
| advancedOrders     | VARCHAR   |                                                                                                                        |             |
| criteriaResolvers  | VARCHAR   |                                                                                                                        |             |
| fulfillments       | VARCHAR   |                                                                                                                        |             |

## 91. Table: Seaport\_call\_matchOrders\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-06-10 18:50:23+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14940027                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x6b06e7f9c749c5dc4e792f420ab337c87fd5b10e3973f780f432895219795469                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 109                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000006cee72100d161c57ada5bb2be1ca79                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| orders             | VARCHAR   | 0x4d41232B0d963AFb52cd0354DA5819b259F133BD,0xF397619df7Bfd4D1657EA9bDd9DF7FF888731A11,2,0xbD115428DD |                                                                                                                        |
| fulfillments       | VARCHAR   | 0,0,0,3,1,0,0,0,1,0,0,1,1,0,0,2                                                                      |                                                                                                                        |

## 92. Table: Seaport\_call\_name\_history

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

## 93. Table: Seaport\_call\_validate\_history

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
| orders             | VARCHAR   |                                                                                                                        |             |

## 94. Table: Seaport\_event\_NonceIncremented\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-20 19:27:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14812892                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf387c0acda5445bbcacb96ce4d84cbff7bddbb2c0f2b1ff65eebd88a6aaf1b0d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 414                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000006cee72100d161c57ada5bb2be1ca79                         | Address of the contract that produced the log                |
| newNonce          | VARCHAR   | 1                                                                  |                                                              |
| offerer           | VARCHAR   | 0xdc90062b1202cf30cf2fc6b2cca007af94c8f231                         |                                                              |

## 95. Table: Seaport\_event\_OrderCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-25 23:51:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14844764                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x280255d25557712569753923c5dd2d98262c5d307c6c2eb1f8f2ae78d16f248c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 93                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000006cee72100d161c57ada5bb2be1ca79                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0xb03c549ab9d9bb060e32584aa45d96146dcbbb100e2c80d0f850b25e8c986f12 |                                                              |
| offerer           | VARCHAR   | 0x03090577d239cd4f351db4ed984b34647d8e2046                         |                                                              |
| zone              | VARCHAR   | 0x9b814233894cd227f561b78cc65891aa55c62ad2                         |                                                              |

## 96. Table: Seaport\_event\_OrderFulfilled\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-24 19:27:54+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14837478                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9c263e05bb3b4fef4eb9044e37675cf4aa3a4bc7ad8a52878dd2a55b105dc117                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 181                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000006cee72100d161c57ada5bb2be1ca79                                                           | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0xfea4fc43a5f52ca83157b1585c65453b1ecb9a173f6ed9eb59a613d42da74036                                   |                                                              |
| offerer           | VARCHAR   | 0x792b8795afc44b620f9f93ea42115ae7c773edb4                                                           |                                                              |
| zone              | VARCHAR   | 0xf397619df7bfd4d1657ea9bdd9df7ff888731a11                                                           |                                                              |
| fulfiller         | VARCHAR   | 0xa797f42711d317df7e778b84a19b5783f1544364                                                           |                                                              |
| offer             | VARCHAR   | 1,0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2,0,200000000000000                                       |                                                              |
| consideration     | VARCHAR   | 2,0x50075F151ABC5B6B448b1272A0a1cFb5CFA25828,80,1,0x792b8795AFC44b620f9F93Ea42115ae7c773EdB4,1,0xC02 |                                                              |

## 97. Table: Seaport\_event\_OrderValidated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| orderHash         | VARCHAR   |                                                              |             |
| offerer           | VARCHAR   |                                                              |             |
| zone              | VARCHAR   |                                                              |             |
