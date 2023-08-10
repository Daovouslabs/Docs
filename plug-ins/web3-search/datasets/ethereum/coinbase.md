# coinbase

## 1. Table: StakedTokenV1\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-12 09:20:47+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17243205                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x997e98f0a36c141993b1a369931d258cfe008235415110bdaddd66664ec585a3             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 238                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbe9895146f7af43049ca1c1ae358b0541ea49704                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xec9e4a0ed746b24b0c7ccf22f270be54f725fb4b                                     |                                                              |
| spender           | VARCHAR   | 0x000000000022d473030f116ddee9f6b43ac78ba3                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 2. Table: StakedTokenV1\_event\_AuthorizationCanceled\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| authorizer        | VARCHAR   |                                                              |             |
| nonce             | VARCHAR   |                                                              |             |

## 3. Table: StakedTokenV1\_event\_AuthorizationUsed\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| authorizer        | VARCHAR   |                                                              |             |
| nonce             | VARCHAR   |                                                              |             |

## 4. Table: StakedTokenV1\_event\_Blacklisted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-19 17:42:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17295086                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xeb4d7f6d71c63624692ebcdd92ad5e670d576865f7c467392cf1d58ac5ce9faa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 196                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbe9895146f7af43049ca1c1ae358b0541ea49704                         | Address of the contract that produced the log                |
| \_account         | VARCHAR   | 0x38735f03b30fbc022ddd06abed01f0ca823c6a94                         |                                                              |

## 5. Table: StakedTokenV1\_event\_BlacklisterChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-25 08:00:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15407961                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9045e1c5fa5fa0efae2ffcbdc311104d58e54047f4597744d0df300466069187 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 384                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbe9895146f7af43049ca1c1ae358b0541ea49704                         | Address of the contract that produced the log                |
| newBlacklister    | VARCHAR   | 0xbe3c68821d585cf1552214897a1c091014b1eb0a                         |                                                              |

## 6. Table: StakedTokenV1\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-28 06:40:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17789825                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6b348ebc8047f2e111a780b38dc0c7d76e9a8af1ffb1839112f1bb327ed20e73 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 258                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbe9895146f7af43049ca1c1ae358b0541ea49704                         | Address of the contract that produced the log                |
| burner            | VARCHAR   | 0x9bf90191444f7e0c52da9a4d31c419b4c96ba372                         |                                                              |
| amount            | VARCHAR   | 2672268594261366500                                                |                                                              |

## 7. Table: StakedTokenV1\_event\_ExchangeRateUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-18 16:00:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17721162                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcce8ce4cdb0170aedc3a5adb8a2c44a8ecedb8bf64538949acc59d9914085c5f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 315                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbe9895146f7af43049ca1c1ae358b0541ea49704                         | Address of the contract that produced the log                |
| oracle            | VARCHAR   | 0x9b37180d847b27adc13c2277299045c1237ae281                         |                                                              |
| newExchangeRate   | VARCHAR   | 1043567519650797939                                                |                                                              |

## 8. Table: StakedTokenV1\_event\_MasterMinterChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-02 21:03:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14893169                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfba3390e062269ac34a73b9f1b16236285ec859ab8d01cd911db4198f79cf533 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 67                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbe9895146f7af43049ca1c1ae358b0541ea49704                         | Address of the contract that produced the log                |
| newMasterMinter   | VARCHAR   | 0xd0f73e06e7b88c8e1da291bb744c4eebaf9af59f                         |                                                              |

## 9. Table: StakedTokenV1\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-22 08:57:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16461295                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc749c40c76be64f749ee8c68678a34152555cfa3c2886662f58d192d8392492a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 221                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbe9895146f7af43049ca1c1ae358b0541ea49704                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0x6d44bfb8432d17882bb6e84652f5c3b36fcc8280                         |                                                              |
| to                | VARCHAR   | 0x2f043b4bb857a7f4b6831219184dac3105aca34d                         |                                                              |
| amount            | VARCHAR   | 70611087511997237904                                               |                                                              |

## 10. Table: StakedTokenV1\_event\_MinterConfigured\_history

| Column              | Type      | Example                                                                        | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2022-06-19 19:30:00+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 14992471                                                                       | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x176da48c834aa0e9d9685e36f1487b1bd64feca2611c4803922e260cf8810288             | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 192                                                                            | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0xbe9895146f7af43049ca1c1ae358b0541ea49704                                     | Address of the contract that produced the log                |
| minter              | VARCHAR   | 0x6d44bfb8432d17882bb6e84652f5c3b36fcc8280                                     |                                                              |
| minterAllowedAmount | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 11. Table: StakedTokenV1\_event\_MinterRemoved\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldMinter         | VARCHAR   |                                                              |             |

## 12. Table: StakedTokenV1\_event\_OracleUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-04 15:49:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14140436                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc1cad30c1512e1ee36a19386ca18690acd6d10eec7eedd31e86479ba92e1778d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 232                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbe9895146f7af43049ca1c1ae358b0541ea49704                         | Address of the contract that produced the log                |
| newOracle         | VARCHAR   | 0x9b37180d847b27adc13c2277299045c1237ae281                         |                                                              |

## 13. Table: StakedTokenV1\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-02 21:03:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14893170                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdfdfbcb2d2918a6880c02983fa02e52881a980766ebfa41a705b953baca64eda | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 62                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbe9895146f7af43049ca1c1ae358b0541ea49704                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0xd77c54c9c7f5c6b223652b2fc4ee9bb441aab81f                         |                                                              |
| newOwner          | VARCHAR   | 0xd0f9b590eae80815b81be857a21f69d07453560e                         |                                                              |

## 14. Table: StakedTokenV1\_event\_Pause\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 15. Table: StakedTokenV1\_event\_PauserChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-02 21:02:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14893167                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x310fd21e7509e6167db9c4bfe81ade1af8e43308bf0129a5108fc25cc3fa1d63 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 58                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbe9895146f7af43049ca1c1ae358b0541ea49704                         | Address of the contract that produced the log                |
| newAddress        | VARCHAR   | 0x46574f57f3f5dfccd296f80407b3f4778414f8f5                         |                                                              |

## 16. Table: StakedTokenV1\_event\_RescuerChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newRescuer        | VARCHAR   |                                                              |             |

## 17. Table: StakedTokenV1\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-30 02:12:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16516577                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x53c02dff229a121f04867249b72c7a7bbfa50544fca5809446b860c24b3e5f73 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 172                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbe9895146f7af43049ca1c1ae358b0541ea49704                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x840deeef2f115cf50da625f7368c24af6fe74410                         |                                                              |
| to                | VARCHAR   | 0x8d8aa4f2390dd31add06ce6a9374542020272d6b                         |                                                              |
| value             | VARCHAR   | 999285030690424534                                                 |                                                              |

## 18. Table: StakedTokenV1\_event\_UnBlacklisted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-12 18:44:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15955810                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2332121a35e3ef3d506b410f16526cadfb41ad37eb6ef570bb07e2ef949b7f36 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 238                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbe9895146f7af43049ca1c1ae358b0541ea49704                         | Address of the contract that produced the log                |
| \_account         | VARCHAR   | 0xfa77b7a75b34d0337d3b8c419c5c2db826fc5fff                         |                                                              |

## 19. Table: StakedTokenV1\_event\_Unpause\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
