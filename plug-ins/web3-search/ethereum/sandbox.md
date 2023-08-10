# sandbox

## 1. Table: AssetSignedAuction\_event\_OfferClaimed\_history

| Column            | Type      | Example                                                                       | Description                                                  |
| ----------------- | --------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-18 18:23:25+00:00                                                     | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13251282                                                                      | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0059aa2531925e0b10228c67f1ba9823a793e6e4f57f496a0b755b0be9e26c9e            | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 336                                                                           | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x921fd42f147b26b51aa3c7fa3f2e2ce7704c2858                                    | Address of the contract that produced the log                |
| seller            | VARCHAR   | 0x000d5f1fcb853d1124f6f95167061ce096381992                                    |                                                              |
| buyer             | VARCHAR   | 0x9094576e38cd96fad35b79f60c214f22336b3550                                    |                                                              |
| offerId           | VARCHAR   | 40087662594196225882768246500897305565052667363902083975668740040633157572034 |                                                              |
| amount            | VARCHAR   | 1                                                                             |                                                              |
| pricePaid         | VARCHAR   | 50000000000000000000                                                          |                                                              |
| feePaid           | VARCHAR   | 2500000000000000000                                                           |                                                              |

## 2. Table: Asset\_event\_TransferBatch\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-07 09:31:04+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15294359                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb01f46e85bb8fc4f3bd1b26a694484fca220595c609548e0993ba8a104e44cee                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 662                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa342f5d851e866e18ff98f351f2c6637f4478db5                                                           | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0x3acf54f6a787c7e8bfc854b44f35d9aa2f218ab4                                                           |                                                              |
| from              | VARCHAR   | 0xff98f34ae0e3009a21ebbb32af4e96537d4e22e9                                                           |                                                              |
| to                | VARCHAR   | 0xf2c452547004ede3c28384917924032c4904b3d5                                                           |                                                              |
| ids               | VARCHAR   | 24236049391276693894126346244543877987602349526693355805231833288213599891456,2423604939127669389412 |                                                              |
| values            | VARCHAR   | 1,1                                                                                                  |                                                              |

## 3. Table: Asset\_event\_TransferSingle\_history

| Column            | Type      | Example                                                                       | Description                                                  |
| ----------------- | --------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-28 05:10:59+00:00                                                     | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17355356                                                                      | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x82c5fe33f3f08f5e282b23d7712bc7e4365555f8295110f0057ab4d5405c672b            | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 54                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa342f5d851e866e18ff98f351f2c6637f4478db5                                    | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0x00000000000000adc04c56bf30ac9d3c0aaf14dc                                    |                                                              |
| from              | VARCHAR   | 0xf645877ab54e5856f39dc90425ae21748f52b5d4                                    |                                                              |
| to                | VARCHAR   | 0x4c6b689c23eda1a135213c1186d05dfacb09f14a                                    |                                                              |
| id                | VARCHAR   | 55464657044963196816950587289035428064568320970692304673817341489688755669030 |                                                              |
| value             | VARCHAR   | 1                                                                             |                                                              |

## 4. Table: Asset\_event\_Transfer\_history

| Column            | Type      | Example                                                                       | Description                                                  |
| ----------------- | --------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-09 22:56:56+00:00                                                     | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14935124                                                                      | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7314f8dd8692d33940ba2349727857e2d0e073444e9cc5140a05a689da332330            | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 210                                                                           | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa342f5d851e866e18ff98f351f2c6637f4478db5                                    | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0x0000000000000000000000000000000000000000                                    |                                                              |
| \_to              | VARCHAR   | 0x35951e2ab472c8f55c89d4d7544b89c3f112b193                                    |                                                              |
| \_tokenId         | VARCHAR   | 24236049391276693894126346244543877987602349526732969886488965457010388641797 |                                                              |

## 5. Table: Land\_event\_AdminChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-04 07:53:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9048224                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2667572e4a9186d8953739f1e4ae76edf9df6c1afac363bf7af0244413501f27 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 39                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x50f5474724e0ee42d9a4e711ccfb275809fd6d4a                         | Address of the contract that produced the log                |
| oldAdmin          | VARCHAR   | 0x18dd4e0eb8699ea4fee238de41ecfb95e32272f8                         |                                                              |
| newAdmin          | VARCHAR   | 0xeaa0993e1d21c2103e4f172a20d29371fbaf6d06                         |                                                              |

## 6. Table: Land\_event\_ApprovalForAll\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-09 11:00:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14932223                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa81f322befcd06bcdb8aaa8e4213458cc9880fbb3f2fc62bcf768f8e90a6d7ba | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 205                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x50f5474724e0ee42d9a4e711ccfb275809fd6d4a                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x208b82b04449cd51803fae4b1561450ba13d9510                         |                                                              |
| \_operator        | VARCHAR   | 0x48d504f394614c0b7112c6dfc65aa96b2f43c756                         |                                                              |
| \_approved        | VARCHAR   | false                                                              |                                                              |

## 7. Table: Land\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-13 07:13:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13606286                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x97c5a185b613c921293525070431d7e29fbdb5f7405bc67a5a9dd51eec8aa733 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 600                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x50f5474724e0ee42d9a4e711ccfb275809fd6d4a                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x20f0a717f8eaec816fa700a1d1bfe7da0f7904ce                         |                                                              |
| \_approved        | VARCHAR   | 0xa055c2c792b6b2a346453830688f2d4a83b6d4ab                         |                                                              |
| \_tokenId         | VARCHAR   | 157969                                                             |                                                              |

## 8. Table: Land\_event\_MetaTransactionProcessor\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2019-12-04 07:51:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 9048219                                                            | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0x001e8ec0f9436eb1544559fc71d6aa9bdfd0c998adff4b3e5e57fa533ed3bdc8 | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 89                                                                 | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0x50f5474724e0ee42d9a4e711ccfb275809fd6d4a                         | Address of the contract that produced the log                |
| metaTransactionProcessor | VARCHAR   | 0x3845badade8e6dff049820680d1f14bd3903a5d0                         |                                                              |
| enabled                  | VARCHAR   | true                                                               |                                                              |

## 9. Table: Land\_event\_Minter\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-04 19:53:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12960632                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x469c9e9ff9a91668fd7636ae308920ce4b3acad878d3105452053469c47fd645 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 48                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x50f5474724e0ee42d9a4e711ccfb275809fd6d4a                         | Address of the contract that produced the log                |
| superOperator     | VARCHAR   | 0x8be6e20c047cdab60d74eeb929ea8e3b24e10649                         |                                                              |
| enabled           | VARCHAR   | true                                                               |                                                              |

## 10. Table: Land\_event\_SuperOperator\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-17 14:40:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11874934                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1c840b6a6caf86f460c63e53d1b14a4078b4ce5459db121232c7e96fe21ac1e6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 137                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x50f5474724e0ee42d9a4e711ccfb275809fd6d4a                         | Address of the contract that produced the log                |
| superOperator     | VARCHAR   | 0xeaa0993e1d21c2103e4f172a20d29371fbaf6d06                         |                                                              |
| enabled           | VARCHAR   | true                                                               |                                                              |

## 11. Table: Land\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-26 15:05:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13101714                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8276d9fd4b0021a5f97535cb39bc17c370e583e29204439e4ace80c63758dee6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 217                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x50f5474724e0ee42d9a4e711ccfb275809fd6d4a                         | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_to              | VARCHAR   | 0x5b3513da99c0572a510334c4256b99ac3a8eb72e                         |                                                              |
| \_tokenId         | VARCHAR   | 21634                                                              |                                                              |
