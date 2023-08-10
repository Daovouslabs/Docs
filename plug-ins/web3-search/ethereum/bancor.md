# bancor

## 1. Table: BancorConverterFactory\_event\_NewConverter\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-02 10:24:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9792026                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x636dbb66dd0412f58e2aee7a8d816a6576667c18f1fd4fd43f7a37bd80e2da3b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbef6a44d3500fb314a88359a5791fcdcb104d259                         | Address of the contract that produced the log                |
| \_converter       | VARCHAR   | 0x485852a29c529dfe21e1871566af2d68738171d7                         |                                                              |
| \_owner           | VARCHAR   | 0xcf057a4ce6d27da5f0320d4e2a5b3deaf608971c                         |                                                              |

## 2. Table: BancorConverter\_event\_ConversionFeeUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-06-11 07:26:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5769024                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9f40d9779784c9edd4c0cd34d553a2911b1c08fd351f5613d13e14f158dd0ae6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 28                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3839416bd0095d97be9b354cbfb0f6807d4d609e                         | Address of the contract that produced the log                |
| \_prevFee         | VARCHAR   | 0                                                                  |                                                              |
| \_newFee          | VARCHAR   | 0                                                                  |                                                              |

## 3. Table: BancorConverter\_event\_Conversion\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-20 03:01:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9705997                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa58aebe3cf1c0bd5b921d372c9666c74a8ee49f85a59ae57b915cbf523553b91 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 92                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa260306fe5e57cae7bdcc7ff0488061eace32b58                         | Address of the contract that produced the log                |
| \_fromToken       | VARCHAR   | 0xe3818504c1b32bf1557b16c238b2e01fd3149c17                         |                                                              |
| \_toToken         | VARCHAR   | 0x1f573d6fb3f13d689ff844b4ce37794d79a7ff1c                         |                                                              |
| \_trader          | VARCHAR   | 0x3ab6564d5c214bc416ee8421e05219960504eead                         |                                                              |
| \_amount          | VARCHAR   | 33594000000000000000000                                            |                                                              |
| \_return          | VARCHAR   | 3071189226719822556474                                             |                                                              |
| \_conversionFee   | VARCHAR   | 6151604321251106252                                                |                                                              |

## 4. Table: BancorConverter\_event\_ConversionsEnable\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2019-11-20 13:58:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 8968733                                                            | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x2d5cf48f77e1bd1f63094a9a8ed25f1eedb32fddaf0bed65b3dc93d837b454cf | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 217                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x78d951e60129b17e29eda5faf4b2d7e4b1621e37                         | Address of the contract that produced the log                |
| \_conversionsEnabled | VARCHAR   | false                                                              |                                                              |

## 5. Table: BancorConverter\_event\_ManagerUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-06-23 20:00:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5841931                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdb57515e5b26bbb8f8261b2f9963ba3b63c2b7314e5ebdbbda1ccfe6dbe7f130 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 55                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2d56d1904bb750675c0a55ca7339f971f48d9dda                         | Address of the contract that produced the log                |
| \_prevManager     | VARCHAR   | 0x0a8079ce1fd9b1ae682d9f1b709609a05bf9b236                         |                                                              |
| \_newManager      | VARCHAR   | 0xe727b18e8d4ec97c508e46baa5b0d59d80a3429f                         |                                                              |

## 6. Table: BancorConverter\_event\_OwnerUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-10 19:18:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11029542                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfdf0afd15bb846c2af3b62d018fb455a803632472526ed7edc7e09d1e7ee687a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 49                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2d56d1904bb750675c0a55ca7339f971f48d9dda                         | Address of the contract that produced the log                |
| \_prevOwner       | VARCHAR   | 0xc7a965dcec421b8423de2d7b26eb83aac8070acc                         |                                                              |
| \_newOwner        | VARCHAR   | 0xdfee8dc240c6cadc2c7f7f9c257c259914dea84e                         |                                                              |

## 7. Table: BancorConverter\_event\_PriceDataUpdate\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2019-11-07 20:46:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 8892170                                                            | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0xbd1502724e46e90696dc38d3bd9bcc2ff0321d9f9c03093eb1d58d11d0434d66 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 11                                                                 | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x9db89726ae2683d21a71ff1417638e72e6d8c0d9                         | Address of the contract that produced the log                |
| \_connectorToken   | VARCHAR   | 0x5d60d8d7ef6d37e16ebabc324de3be57f135e0bc                         |                                                              |
| \_tokenSupply      | VARCHAR   | 139710000000000000000000                                           |                                                              |
| \_connectorBalance | VARCHAR   | 12622156309200577563051029                                         |                                                              |
| \_connectorWeight  | VARCHAR   | 500000                                                             |                                                              |

## 8. Table: BancorNetworkV3\_event\_FlashLoanCompleted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-06 20:00:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17423634                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5944a406276e0f690064dc2de6fa39212be974347cc3d2f86b1035b0cfd6c19e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 239                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeef417e1d5cc832e619ae18d2f140de2999dd4fb                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x1f573d6fb3f13d689ff844b4ce37794d79a7ff1c                         |                                                              |
| borrower          | VARCHAR   | 0x41eeba3355d7d6ff628b7982f3f9d055c39488cb                         |                                                              |
| amount            | VARCHAR   | 23130208411199903000000                                            |                                                              |
| feeAmount         | VARCHAR   | 0                                                                  |                                                              |

## 9. Table: BancorNetworkV3\_event\_FundsMigrated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-23 12:02:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14829469                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x001e9353c9f891903337deeade281ddf855548d6a745d1c925ac041d61001db5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 250                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeef417e1d5cc832e619ae18d2f140de2999dd4fb                         | Address of the contract that produced the log                |
| contextId         | VARCHAR   | 0x427939e80bf6f981e305823dd89437093d6ee64b7d578b2981ea42d66d0e266b |                                                              |
| token             | VARCHAR   | 0x1f573d6fb3f13d689ff844b4ce37794d79a7ff1c                         |                                                              |
| provider          | VARCHAR   | 0x993d1b2e40064a1a160759fcfc41ab5b7da40e5d                         |                                                              |
| amount            | VARCHAR   | 2017122209760571734564                                             |                                                              |
| availableAmount   | VARCHAR   | 2017122209760571734564                                             |                                                              |
| originalAmount    | VARCHAR   | 2001106761564007042530                                             |                                                              |

## 10. Table: BancorNetworkV3\_event\_NetworkFeesWithdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-29 14:20:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15639558                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x94b0497c56d088a123cf3d7c8d2b5d0e1f96fa26386045aa5c43a1de159365b6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 173                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeef417e1d5cc832e619ae18d2f140de2999dd4fb                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x7e3692a6d8c34a762079fa9057aed87be7e67cb8                         |                                                              |
| recipient         | VARCHAR   | 0x1f573d6fb3f13d689ff844b4ce37794d79a7ff1c                         |                                                              |
| amount            | VARCHAR   | 1002457296990992659044648                                          |                                                              |

## 11. Table: BancorNetworkV3\_event\_Paused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-23 15:59:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14830490                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf37bc82651f727f7705063094f41fadbac4b13ed19c20c421ba3d4d9ea484330 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 150                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeef417e1d5cc832e619ae18d2f140de2999dd4fb                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x5beba4d3533a963dedb270a95ae5f7752fa0fe22                         |                                                              |

## 12. Table: BancorNetworkV3\_event\_PoolAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-14 18:31:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16827990                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7ec32b224f4a0ad37478f389a1b54df646148491326b0344344359762a73c647 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 91                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeef417e1d5cc832e619ae18d2f140de2999dd4fb                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0x8f8221afbb33998d8584a2b05749ba73c37a938a                         |                                                              |
| poolCollection    | VARCHAR   | 0xb67d563287d12b1f41579cb687b04988ad564c6c                         |                                                              |

## 13. Table: BancorNetworkV3\_event\_PoolCollectionAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-23 08:15:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15197800                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb7fe921840d21d68886043cedb1c71863a73cd1b0e024ce03f7f4262d5794d39 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 126                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeef417e1d5cc832e619ae18d2f140de2999dd4fb                         | Address of the contract that produced the log                |
| poolType          | VARCHAR   | 1                                                                  |                                                              |
| poolCollection    | VARCHAR   | 0x5ce51256651aa90eee24259a56529affcf13a3d0                         |                                                              |

## 14. Table: BancorNetworkV3\_event\_PoolCollectionRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-23 08:18:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15197814                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x817fcf415360b5194c6542960ab0cf201f7f80ad6b5cc39e1340b7f4d22b53c2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 190                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeef417e1d5cc832e619ae18d2f140de2999dd4fb                         | Address of the contract that produced the log                |
| poolType          | VARCHAR   | 1                                                                  |                                                              |
| poolCollection    | VARCHAR   | 0xd2a572fefdbd719605334df5cba9746e02d51558                         |                                                              |

## 15. Table: BancorNetworkV3\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-04 09:58:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15275230                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcb7aa50c57f4f43e4011b1808b839334016d687dc172a03ecc68362fba440ce7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 67                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeef417e1d5cc832e619ae18d2f140de2999dd4fb                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0xb2cabf797bc907b049e4ccb5b84d13be3a8cfc21                         |                                                              |
| poolCollection    | VARCHAR   | 0xd982e001491d414c857f2a1aaa4b43ccf9f642b4                         |                                                              |

## 16. Table: BancorNetworkV3\_event\_PoolRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-19 20:34:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14992742                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbeab957619a6961da3499e517a1acf1cdb17f0c80a2a0148313719ff9e111c0b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 98                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeef417e1d5cc832e619ae18d2f140de2999dd4fb                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0xdd974d5c2e2928dea5f71b9825b8b646686bd200                         |                                                              |
| poolCollection    | VARCHAR   | 0xb8d8033f7b2267feffdbaa521cd8a86df861da69                         |                                                              |

## 17. Table: BancorNetworkV3\_event\_RoleAdminChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-18 13:22:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14609418                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd681fbdd23d3a0fa59678e57704450e25076cc9693380262cff6ce1489965880 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 212                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeef417e1d5cc832e619ae18d2f140de2999dd4fb                         | Address of the contract that produced the log                |
| role              | VARCHAR   | 0x2172861495e7b85edac73e3cd5fbb42dd675baadf627720e687bcfdaca025096 |                                                              |
| previousAdminRole | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000 |                                                              |
| newAdminRole      | VARCHAR   | 0x2172861495e7b85edac73e3cd5fbb42dd675baadf627720e687bcfdaca025096 |                                                              |

## 18. Table: BancorNetworkV3\_event\_RoleGranted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-18 13:22:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14609418                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd681fbdd23d3a0fa59678e57704450e25076cc9693380262cff6ce1489965880 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 213                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeef417e1d5cc832e619ae18d2f140de2999dd4fb                         | Address of the contract that produced the log                |
| role              | VARCHAR   | 0x2172861495e7b85edac73e3cd5fbb42dd675baadf627720e687bcfdaca025096 |                                                              |
| account           | VARCHAR   | 0x5beba4d3533a963dedb270a95ae5f7752fa0fe22                         |                                                              |
| sender            | VARCHAR   | 0x5beba4d3533a963dedb270a95ae5f7752fa0fe22                         |                                                              |

## 19. Table: BancorNetworkV3\_event\_RoleRevoked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-09 10:10:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14741817                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x903b90f6270924944419bcbee542eccabd08e3eb434d5ac08604d8a04cda00b9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 143                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeef417e1d5cc832e619ae18d2f140de2999dd4fb                         | Address of the contract that produced the log                |
| role              | VARCHAR   | 0xdf8c9529ea4b244b569bac557a549516f317e7b5cf82dc5e0d8b6d874930a3f5 |                                                              |
| account           | VARCHAR   | 0x843bd7a811dc26874cb2ad9f4a04a8652f65d8e6                         |                                                              |
| sender            | VARCHAR   | 0x5beba4d3533a963dedb270a95ae5f7752fa0fe22                         |                                                              |

## 20. Table: BancorNetworkV3\_event\_TokensTraded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-02 05:12:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16959263                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd051090e34420362f3ec1aac8fc3aaf4d15b36fcbdf76cb4fd4e96fe0aed7a01 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 38                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeef417e1d5cc832e619ae18d2f140de2999dd4fb                         | Address of the contract that produced the log                |
| contextId         | VARCHAR   | 0x0cda53a4b0324992026321d7b12c678151bc7b7235c67632c536300637f6ceb4 |                                                              |
| sourceToken       | VARCHAR   | 0x0954906da0bf32d5479e25f46056d22f08464cab                         |                                                              |
| targetToken       | VARCHAR   | 0x5218e472cfcfe0b64a064f055b43b4cdc9efd3a6                         |                                                              |
| sourceAmount      | VARCHAR   | 99219433786840583161                                               |                                                              |
| targetAmount      | VARCHAR   | 26092793006711144588895                                            |                                                              |
| bntAmount         | VARCHAR   | 306929033455417838298                                              |                                                              |
| targetFeeAmount   | VARCHAR   | 131119562847794696426                                              |                                                              |
| bntFeeAmount      | VARCHAR   | 1542356952037275569                                                |                                                              |
| trader            | VARCHAR   | 0xfd0000000100069ad1670066004306009b487ad7                         |                                                              |

## 21. Table: BancorNetworkV3\_event\_Unpaused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-14 18:32:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16827995                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1c12404732248bfe6a2764ca91324d5fbdc48f431384362bbab6cff7847cffce | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 59                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeef417e1d5cc832e619ae18d2f140de2999dd4fb                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x5beba4d3533a963dedb270a95ae5f7752fa0fe22                         |                                                              |

## 22. Table: BancorNetwork\_event\_TokensTraded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-13 04:39:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17468757                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc770ec9253574f0233b374f1d065c98aa2fd056a46c2126bf5ae22702f998f85 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 14                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeef417e1d5cc832e619ae18d2f140de2999dd4fb                         | Address of the contract that produced the log                |
| contextId         | VARCHAR   | 0x33be1d02db8fb62d477cd207cd8bdc91e4c670722814f3bfa20aa94a99e5308f |                                                              |
| sourceToken       | VARCHAR   | 0xb9ef770b6a5e12e45983c5d80545258aa38f3b78                         |                                                              |
| targetToken       | VARCHAR   | 0x1f573d6fb3f13d689ff844b4ce37794d79a7ff1c                         |                                                              |
| sourceAmount      | VARCHAR   | 55248278066696                                                     |                                                              |
| targetAmount      | VARCHAR   | 1895600351953773194755                                             |                                                              |
| bntAmount         | VARCHAR   | 1895600351953773194755                                             |                                                              |
| targetFeeAmount   | VARCHAR   | 9525629909315443189                                                |                                                              |
| bntFeeAmount      | VARCHAR   | 9525629909315443189                                                |                                                              |
| trader            | VARCHAR   | 0x0000000000a84d1a9b0063a910315c7ffa9cd248                         |                                                              |

## 23. Table: ContractRegistry\_event\_AddressUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-11 18:42:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12018948                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xee3822d7f69e94c48e212114987193db24490a94e91d776d343c4818705f3348 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 162                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x52ae12abe5d8bd778bd5397f99ca900624cfadd4                         | Address of the contract that produced the log                |
| \_contractName    | VARCHAR   | 0x5374616b696e6752657761726473000000000000000000000000000000000000 |                                                              |
| \_contractAddress | VARCHAR   | 0xeb69bd39f3df1cc329b1a141d78263c43b1f2f2b                         |                                                              |

## 24. Table: ContractRegistry\_event\_OwnerUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-30 21:33:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14688013                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x58ed5d36a19abf34f60b045d382b2244463095b8500d5dec4e7ee9455a191893 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 223                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x52ae12abe5d8bd778bd5397f99ca900624cfadd4                         | Address of the contract that produced the log                |
| \_prevOwner       | VARCHAR   | 0xdfee8dc240c6cadc2c7f7f9c257c259914dea84e                         |                                                              |
| \_newOwner        | VARCHAR   | 0x5beba4d3533a963dedb270a95ae5f7752fa0fe22                         |                                                              |

## 25. Table: ConverterFactory\_event\_NewConverter\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-11 12:42:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8914474                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc339518cfe205e39a1786f202ed3274265277b5f86d89eed7d75f3d9fdf58ec3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 82                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa75f62388028c1d0b1c0c6e846c6124a17511abe                         | Address of the contract that produced the log                |
| \_converter       | VARCHAR   | 0x9c248517b92ae226b88a0a0c28de02b9b7b039d3                         |                                                              |
| \_owner           | VARCHAR   | 0x20412bd6d146309c55cc607d30c5aad07fbf6148                         |                                                              |

## 26. Table: ConverterFactory\_event\_OwnerUpdate\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_prevOwner       | VARCHAR   |                                                              |             |
| \_newOwner        | VARCHAR   |                                                              |             |

## 27. Table: ConverterFactory\_v2\_event\_NewConverter\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-14 14:35:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12037262                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x43475294ab3c1f2978e557c473e84e85498c700d12f49e196bbfca41100f9758 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 24                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4ade0e57bc2e129f62547af4d620fb40d28ea269                         | Address of the contract that produced the log                |
| \_type            | VARCHAR   | 3                                                                  |                                                              |
| \_converter       | VARCHAR   | 0x5505cf19fefbfae5d6405949ff673fccf483126d                         |                                                              |
| \_owner           | VARCHAR   | 0xc0205e203f423bcd8b2a4d6f8c8a154b0aa60f19                         |                                                              |

## 28. Table: ConverterFactory\_v2\_event\_OwnerUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-05 09:43:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10994987                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x58ab995ec963586f8521a8fec901acceef6384992b6b9a16fbfff154e55ca7cc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 31                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4ade0e57bc2e129f62547af4d620fb40d28ea269                         | Address of the contract that produced the log                |
| \_prevOwner       | VARCHAR   | 0xb93081c32befda94168483c78b780e601f07b192                         |                                                              |
| \_newOwner        | VARCHAR   | 0xdfee8dc240c6cadc2c7f7f9c257c259914dea84e                         |                                                              |

## 29. Table: ConverterUpgrader\_event\_ConverterOwned\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-02-14 12:26:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9481111                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xde073006a52b0bacf70530175ec20e12502fcc93cf724a3510ed0f60b9b2c17a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 22                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x20412bd6d146309c55cc607d30c5aad07fbf6148                         | Address of the contract that produced the log                |
| \_converter       | VARCHAR   | 0x9f547e89078b24d0e2269ba08eb411102e98ca14                         |                                                              |
| \_owner           | VARCHAR   | 0x20412bd6d146309c55cc607d30c5aad07fbf6148                         |                                                              |

## 30. Table: ConverterUpgrader\_event\_ConverterUpgrade\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-10 18:50:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12213896                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc7091e3d22b65d6b857c39844ba5186c6d75d77b0aafa97638ba6f76e9157375 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 26                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7dfb5180878b43c6ff5aa6a2ea55db20bcc87410                         | Address of the contract that produced the log                |
| \_oldConverter    | VARCHAR   | 0xb3f0d58dcd8be52ca7f629832e62948c3863828d                         |                                                              |
| \_newConverter    | VARCHAR   | 0xe807f9ead3408b3770d3110097cd78b94160f86c                         |                                                              |

## 31. Table: ConverterUpgrader\_event\_OwnerUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-30 21:11:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14687924                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xac35db45ac3b22362a74f6a0facc7740ad272c2e456bcaf6cbd978787c016649 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 381                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7dfb5180878b43c6ff5aa6a2ea55db20bcc87410                         | Address of the contract that produced the log                |
| \_prevOwner       | VARCHAR   | 0xdfee8dc240c6cadc2c7f7f9c257c259914dea84e                         |                                                              |
| \_newOwner        | VARCHAR   | 0x5beba4d3533a963dedb270a95ae5f7752fa0fe22                         |                                                              |

## 32. Table: LiquidityPoolV1Converter\_event\_Activation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-11 12:47:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10438305                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc2c765e807c27327f55e23640d258b65429de4b32bfc7e6684d9b617dc117d4f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 14                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7834d96bd681e43740e6da513638504174040010                         | Address of the contract that produced the log                |
| \_anchor          | VARCHAR   | 0x5cf2f6387c4f551316e1e422acf1025a539825c3                         |                                                              |
| \_activated       | VARCHAR   | true                                                               |                                                              |

## 33. Table: LiquidityPoolV1Converter\_event\_ConversionFeeUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-16 17:37:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7077148                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3fbadea98fe1a315cc1eda81f6f2553ab5b8097d82a10c5f52bd2efc6a9c01d9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 20                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9db89726ae2683d21a71ff1417638e72e6d8c0d9                         | Address of the contract that produced the log                |
| \_prevFee         | VARCHAR   | 0                                                                  |                                                              |
| \_newFee          | VARCHAR   | 1000                                                               |                                                              |

## 34. Table: LiquidityPoolV1Converter\_event\_Conversion\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-02 07:30:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8857632                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x72b6c04bdb042d847b353585e20a769c0baf35a5bc18d046fcc2281a11843bd0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 136                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9dce7c9767863110e4fa01410a35b5471aece64e                         | Address of the contract that produced the log                |
| \_fromToken       | VARCHAR   | 0x1f573d6fb3f13d689ff844b4ce37794d79a7ff1c                         |                                                              |
| \_toToken         | VARCHAR   | 0x744d70fdbe2ba4cf95131626614a1763df805b9e                         |                                                              |
| \_trader          | VARCHAR   | 0x0e936b11c2e7b601055e58c7e32417187af4de4a                         |                                                              |
| \_amount          | VARCHAR   | 179997302368452311077                                              |                                                              |
| \_return          | VARCHAR   | 4107254426366291882461                                             |                                                              |
| \_conversionFee   | VARCHAR   | 8226847065590332548                                                |                                                              |

## 35. Table: LiquidityPoolV1Converter\_event\_LiquidityAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-06 19:39:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10407784                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x78b0a783a7c6d7eda12c6efb19fa3600930649372653c9cb9df002a0f2b8eaf8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 8                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe870d00176b2c71afd4c43cea550228e22be4abd                         | Address of the contract that produced the log                |
| \_provider        | VARCHAR   | 0x680c668ead0c3a5662143b69ef7de688a1d9d9ea                         |                                                              |
| \_reserveToken    | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| \_amount          | VARCHAR   | 1676757063500240061                                                |                                                              |
| \_newBalance      | VARCHAR   | 25202905286351220638774                                            |                                                              |
| \_newSupply       | VARCHAR   | 12984256348111435582819574                                         |                                                              |

## 36. Table: LiquidityPoolV1Converter\_event\_LiquidityRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-27 12:28:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11340563                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd611a31b08c466e4bbb8d5b1e53e07837099b31594ceb602d33d78f0765e509d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 294                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe18b18b6f5c07fef86cf0f1c9d0de7fd94869c24                         | Address of the contract that produced the log                |
| \_provider        | VARCHAR   | 0x9acf50ab22004cf09b2461c71447f1d776188fa8                         |                                                              |
| \_reserveToken    | VARCHAR   | 0x1f573d6fb3f13d689ff844b4ce37794d79a7ff1c                         |                                                              |
| \_amount          | VARCHAR   | 400000000000000027799                                              |                                                              |
| \_newBalance      | VARCHAR   | 148892268667728111929                                              |                                                              |
| \_newSupply       | VARCHAR   | 443965785613859463220                                              |                                                              |

## 37. Table: LiquidityPoolV1Converter\_event\_OwnerUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-13 13:42:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9864305                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x68045847811cdc3489efe9676e00ea0cc9d15d64b02a3f5dbc3c088a34954a01 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 82                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xba8ecf0080ed377e04c2b6761154e8777538f2dc                         | Address of the contract that produced the log                |
| \_prevOwner       | VARCHAR   | 0xbef6a44d3500fb314a88359a5791fcdcb104d259                         |                                                              |
| \_newOwner        | VARCHAR   | 0xc724bc5f3dd616c8fadb75a23c00c13880a6268f                         |                                                              |

## 38. Table: LiquidityPoolV1Converter\_event\_PriceDataUpdate\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2019-12-29 16:31:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 9181696                                                            | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0xd90ac954deebbc6b644fa8b37daaac43a30bc88cefea29d6b56e601c69dd528c | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 66                                                                 | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x9c248517b92ae226b88a0a0c28de02b9b7b039d3                         | Address of the contract that produced the log                |
| \_connectorToken   | VARCHAR   | 0xc0829421c1d260bd3cb3e0f06cfe2d52db2ce315                         |                                                              |
| \_tokenSupply      | VARCHAR   | 68590962894453888383699621                                         |                                                              |
| \_connectorBalance | VARCHAR   | 13492790164582807103221                                            |                                                              |
| \_connectorWeight  | VARCHAR   | 100000                                                             |                                                              |

## 39. Table: LiquidityPoolV1Converter\_event\_TokenRateUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-29 02:07:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12726233                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc48342b5630137d74d959532aca1b9e2f8a8c11add75a6be9976568674d5e5f3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 12                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5c8c7ef16dac7596c280e70c6905432f7470965e                         | Address of the contract that produced the log                |
| \_token1          | VARCHAR   | 0x309627af60f0926daa6041b8279484312f2bf060                         |                                                              |
| \_token2          | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| \_rateN           | VARCHAR   | 107501417911023670000000                                           |                                                              |
| \_rateD           | VARCHAR   | 460516552035521062503500000                                        |                                                              |

## 40. Table: PoolCollection\_event\_DefaultTradingFeePPMUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-19 20:18:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14992665                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x24efd7acbed7df10d56a06c2d9da76ecfcafdff77e05fd08d35d83db6478fa90 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 94                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x05e29f07b9710368a1d5658750e9b4b478c15bb8                         | Address of the contract that produced the log                |
| prevFeePPM        | VARCHAR   | 0                                                                  |                                                              |
| newFeePPM         | VARCHAR   | 2000                                                               |                                                              |

## 41. Table: PoolCollection\_event\_DepositingEnabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-09 21:33:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14934777                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd9100665bcd7f977950dd65200df1e3d4d3fc0182e13c9632badf3157199c606 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 56                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb8d8033f7b2267feffdbaa521cd8a86df861da69                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0x505a84a03e382331a1be487b632cf357748b65d6                         |                                                              |
| newStatus         | VARCHAR   | true                                                               |                                                              |

## 42. Table: PoolCollection\_event\_OwnerUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-09 20:30:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14934546                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3a9614e2f7bf256478b4b9841dde2eea348ac6ad09d0a7d6ba1f5433baf54390 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 191                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb8d8033f7b2267feffdbaa521cd8a86df861da69                         | Address of the contract that produced the log                |
| prevOwner         | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x5beba4d3533a963dedb270a95ae5f7752fa0fe22                         |                                                              |

## 43. Table: PoolCollection\_event\_TokensDeposited\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-28 07:04:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15630222                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x947ee6759a456473ba9e716685a163f7bed22efe34236fe50e58095393228024 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 222                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd982e001491d414c857f2a1aaa4b43ccf9f642b4                         | Address of the contract that produced the log                |
| contextId         | VARCHAR   | 0x54d569a01b51b54b00cc522c519935f9e13d4dd9eb9c8ef39bb9ca0db3d4898b |                                                              |
| provider          | VARCHAR   | 0x07579a76c42e16b11a4eb2802359f654f3244c81                         |                                                              |
| token             | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| baseTokenAmount   | VARCHAR   | 219909461                                                          |                                                              |
| poolTokenAmount   | VARCHAR   | 219221532                                                          |                                                              |

## 44. Table: PoolCollection\_event\_TokensWithdrawn\_history

| Column                            | Type      | Example                                                            | Description                                                  |
| --------------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp                  | TIMESTAMP | 2022-10-15 13:11:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number                     | INTEGER   | 15753731                                                           | The block number where this event was emitted                |
| transaction\_hash                 | VARCHAR   | 0xa2991c2b46bb6a35e7ac91dd73e946ac1154baaf1f3af2987f43d1f78d1344f5 | Hash of the transactions in which this event was emitted     |
| log\_index                        | INTEGER   | 145                                                                | Integer of the log index position in the block of this event |
| contract\_address                 | VARCHAR   | 0xd982e001491d414c857f2a1aaa4b43ccf9f642b4                         | Address of the contract that produced the log                |
| contextId                         | VARCHAR   | 0xc8b30a3e18bacedaff0d232582d0964f666d67e75fbe58b36c4bc4e7eb9a54e5 |                                                              |
| provider                          | VARCHAR   | 0x01c09ca19bc2fdbbfe2f911331b3224a00dc4c79                         |                                                              |
| token                             | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| baseTokenAmount                   | VARCHAR   | 240847533                                                          |                                                              |
| poolTokenAmount                   | VARCHAR   | 478380996                                                          |                                                              |
| externalProtectionBaseTokenAmount | VARCHAR   | 0                                                                  |                                                              |
| bntAmount                         | VARCHAR   | 0                                                                  |                                                              |
| withdrawalFeeAmount               | VARCHAR   | 0                                                                  |                                                              |

## 45. Table: PoolCollection\_event\_TotalLiquidityUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-07 01:30:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15487475                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd918eb6cb5acbe24b2b967c22931e2afcb5449ceebfc1cd4d83f96c9b81da2c6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 194                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd982e001491d414c857f2a1aaa4b43ccf9f642b4                         | Address of the contract that produced the log                |
| contextId         | VARCHAR   | 0x2c6d09caf913e5ed433f89ea197ecddffcae4f1f5960460e6f5ff6f4e9171cda |                                                              |
| pool              | VARCHAR   | 0x0d8775f648430679a709e98d2b0cb6250d2887ef                         |                                                              |
| liquidity         | VARCHAR   | 819993809554723952970837                                           |                                                              |
| stakedBalance     | VARCHAR   | 2410607826614640286131127                                          |                                                              |
| poolTokenSupply   | VARCHAR   | 2408114958168119666960223                                          |                                                              |

## 46. Table: PoolCollection\_event\_TradingEnabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-11 17:38:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14945537                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4e45581b5a2027a669d5f5f1443a0df8591435bfc903fe0e80db6f360493e20c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 265                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb8d8033f7b2267feffdbaa521cd8a86df861da69                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0x232fb065d9d24c34708eedbf03724f2e95abe768                         |                                                              |
| newStatus         | VARCHAR   | true                                                               |                                                              |
| reason            | VARCHAR   | 1                                                                  |                                                              |

## 47. Table: PoolCollection\_event\_TradingFeePPMUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-19 09:48:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15370575                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf485f004ec92783c2424d992e1e7e2045dc620a650851f5f4585b12e2d05a0e9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 87                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd982e001491d414c857f2a1aaa4b43ccf9f642b4                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| prevFeePPM        | VARCHAR   | 2000                                                               |                                                              |
| newFeePPM         | VARCHAR   | 1000                                                               |                                                              |

## 48. Table: PoolCollection\_event\_TradingLiquidityUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-03 05:29:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15665545                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x03412ca053f95dc01b6f0135eb9a317e5a2e4ad3a5303c4b1a20b8833d659ca0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 61                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd982e001491d414c857f2a1aaa4b43ccf9f642b4                         | Address of the contract that produced the log                |
| contextId         | VARCHAR   | 0x3c835cb41badfee390cf7921c61200a73ba5426910bcabf860722dc255022f33 |                                                              |
| pool              | VARCHAR   | 0x4a220e6096b25eadb88358cb44068a3248254675                         |                                                              |
| token             | VARCHAR   | 0x4a220e6096b25eadb88358cb44068a3248254675                         |                                                              |
| prevLiquidity     | VARCHAR   | 1150335717590417049792                                             |                                                              |
| newLiquidity      | VARCHAR   | 1143775937460557339463                                             |                                                              |

## 49. Table: SmartToken\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-22 11:26:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16462034                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1e0e078f06d5e4cee2628697de71194c67f72f933ef62cafdeba7ecf99a33ebd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1f573d6fb3f13d689ff844b4ce37794d79a7ff1c                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x0000e0ca771e21bd00057f54a68c30d400000000                         |                                                              |
| \_spender         | VARCHAR   | 0x2f9ec37d6ccfff1cab21733bdadede11c823ccb0                         |                                                              |
| \_value           | VARCHAR   | 23740380132199659278899                                            |                                                              |

## 50. Table: SmartToken\_event\_Destruction\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-03-14 00:13:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7363865                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x27efb63ae5e7e9bcb6379ba573e39b1668cb6b7719779b5d8ac7466809de5695 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1f573d6fb3f13d689ff844b4ce37794d79a7ff1c                         | Address of the contract that produced the log                |
| \_amount          | VARCHAR   | 668133132891000000000                                              |                                                              |

## 51. Table: SmartToken\_event\_Issuance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-27 00:25:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17780820                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5c673fa5f536e74b9d7189e553425e4a41099d6ae674fdc5450ac22b0dfbecec | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 321                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1f573d6fb3f13d689ff844b4ce37794d79a7ff1c                         | Address of the contract that produced the log                |
| \_amount          | VARCHAR   | 28504200000000000000000                                            |                                                              |

## 52. Table: SmartToken\_event\_NewSmartToken\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2017-06-10 16:02:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 3851136                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x750f6632f7884defd40b79be8174bbb44de9ef21ca4172a249d7a4fe10b45e8e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1f573d6fb3f13d689ff844b4ce37794d79a7ff1c                         | Address of the contract that produced the log                |
| \_token           | VARCHAR   | 0x1f573d6fb3f13d689ff844b4ce37794d79a7ff1c                         |                                                              |

## 53. Table: SmartToken\_event\_OwnerUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-07-10 02:43:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5936591                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x30fbe0199fbededf641382ae6765b587c56684c6a4b381811b6f79cd4c46d2e5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1f573d6fb3f13d689ff844b4ce37794d79a7ff1c                         | Address of the contract that produced the log                |
| \_prevOwner       | VARCHAR   | 0x00fb651570a39c5076f136e58ccd8e2378708960                         |                                                              |
| \_newOwner        | VARCHAR   | 0x9d0357d184122b85dbc095d196b5ebbafc7f3010                         |                                                              |

## 54. Table: SmartToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-11 06:31:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17668608                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x908bb0563eba9bd63315c60d77edd615e4c7792c756cf664b65317a4415f7c55 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 172                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1f573d6fb3f13d689ff844b4ce37794d79a7ff1c                         | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0x93334ab8a64b24df7b2fd2132e0e087239a21b63                         |                                                              |
| \_to              | VARCHAR   | 0x92f3f71cef740ed5784874b8c70ff87ecdf33588                         |                                                              |
| \_value           | VARCHAR   | 7502807804313069040310                                             |                                                              |

## 55. Table: StandardPoolConverter\_event\_Activation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-02 19:11:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10978366                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3540e331d43d60a33d6eaee0a152984003d0fc63ffa7694a2566aa1beb2eef93 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 31                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x604989e3cb3f4e77c29c220182d75a99531acf3a                         | Address of the contract that produced the log                |
| \_type            | VARCHAR   | 1                                                                  |                                                              |
| \_anchor          | VARCHAR   | 0x2d5add875442023ec83718bb03d866c9f4c6e8ce                         |                                                              |
| \_activated       | VARCHAR   | true                                                               |                                                              |

## 56. Table: StandardPoolConverter\_event\_ConversionFeeUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-17 17:47:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13044132                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x22709800bb89f3dd4dac5714067285f4991775bbd809534aab3054ea2517f7d8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 72                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb068bfea5ab7852fe437e361e73963900a96fa71                         | Address of the contract that produced the log                |
| \_prevFee         | VARCHAR   | 0                                                                  |                                                              |
| \_newFee          | VARCHAR   | 2000                                                               |                                                              |

## 57. Table: StandardPoolConverter\_event\_Conversion\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-04 21:43:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16114203                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x35da42a4bf84cc04827d5c98720bde5153d5ceb8f4e3b24962d768a574ea93b1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 65                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa1ffea4366a1da2357a59c220eb719b8d4d5b1d8                         | Address of the contract that produced the log                |
| \_fromToken       | VARCHAR   | 0x1f573d6fb3f13d689ff844b4ce37794d79a7ff1c                         |                                                              |
| \_toToken         | VARCHAR   | 0x5b09a0371c1da44a8e24d36bf5deb1141a84d875                         |                                                              |
| \_trader          | VARCHAR   | 0x0000e0ca771e21bd00057f54a68c30d400000000                         |                                                              |
| \_amount          | VARCHAR   | 648619420031482437983                                              |                                                              |
| \_return          | VARCHAR   | 24779897571573291414526                                            |                                                              |
| \_conversionFee   | VARCHAR   | 24804702273847138553                                               |                                                              |

## 58. Table: StandardPoolConverter\_event\_LiquidityAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-24 12:11:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13480113                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8756a4657c97c474363c651ebeab7adf26d43f553b7fc819cdf3a5a420fd88dd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 297                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe345e2f93c28ec6ac2fef45eb1a9fc715601355a                         | Address of the contract that produced the log                |
| \_provider        | VARCHAR   | 0x853c2d147a1bd7eda8fe0f58fb3c5294db07220e                         |                                                              |
| \_reserveToken    | VARCHAR   | 0x8c543aed163909142695f2d2acd0d55791a9edb9                         |                                                              |
| \_amount          | VARCHAR   | 1722045599999999999999270                                          |                                                              |
| \_newBalance      | VARCHAR   | 1749378960900235612118556                                          |                                                              |
| \_newSupply       | VARCHAR   | 287511809964550327201843                                           |                                                              |

## 59. Table: StandardPoolConverter\_event\_LiquidityRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-02 00:15:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16537482                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x057177ac0fa7342ace0413db902ff77ad4b7d943a5d4d65b1d8589ce0af17faf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 90                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8df51a9714ae6357a5b829cc8d677b43d7e8bd53                         | Address of the contract that produced the log                |
| \_provider        | VARCHAR   | 0x85cbbb1ede2b3e389235ae56ec54bec8159001e5                         |                                                              |
| \_reserveToken    | VARCHAR   | 0x514910771af9ca656af840dff83e8264ecf986ca                         |                                                              |
| \_amount          | VARCHAR   | 2150262095256879583994                                             |                                                              |
| \_newBalance      | VARCHAR   | 115293763729032374624171                                           |                                                              |
| \_newSupply       | VARCHAR   | 885212090967160596296320                                           |                                                              |

## 60. Table: StandardPoolConverter\_event\_OwnerUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-26 11:16:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11730971                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xddc2fe209b7cbc76a6453b6fac233ab365767eba02f5d3c59737affb7fd15df7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 68                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xec0536ef95498e3e29ff37e85fd6c821b8f4d439                         | Address of the contract that produced the log                |
| \_prevOwner       | VARCHAR   | 0xdbc3c64508e3fae19b0bcc2472f8811b9d8fa9f2                         |                                                              |
| \_newOwner        | VARCHAR   | 0x4ade0e57bc2e129f62547af4d620fb40d28ea269                         |                                                              |

## 61. Table: StandardPoolConverter\_event\_TokenRateUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-23 06:52:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17540616                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcfcba85db8655a89b1249827c16ed221479f7cbb95bea1cfb1511d81ee52ec31 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 187                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x02e18840fa1fd108be043c3a1a8fa6dd638bc8f1                         | Address of the contract that produced the log                |
| \_token1          | VARCHAR   | 0x34c4dd2ab5e94a9a6e2a1625d7cf2ce180c180de                         |                                                              |
| \_token2          | VARCHAR   | 0x1f573d6fb3f13d689ff844b4ce37794d79a7ff1c                         |                                                              |
| \_rateN           | VARCHAR   | 736646515547351208933                                              |                                                              |
| \_rateD           | VARCHAR   | 49437593793494501882                                               |                                                              |
