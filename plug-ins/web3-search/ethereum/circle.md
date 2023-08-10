# circle

## 1. Table: EuroCoin\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-15 15:46:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15976424                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x45585ae006482ff95ffed299eee44b01a05349c05af577ba6f1560d2c0b9793a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 347                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1abaea1f7c830bd89acc67ec4af516284b1bc33c                         | Address of the contract that produced the log                |
| burner            | VARCHAR   | 0x55fe002aeff02f77364de339a1292923a15844b8                         |                                                              |
| amount            | VARCHAR   | 1000000000                                                         |                                                              |

## 2. Table: EuroCoin\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-18 10:41:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15996367                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7a55e9dc40b0ae7de20fd7f7fcea5c96abfc14e9e7ef37d7eea9c070a92eadb8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 240                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1abaea1f7c830bd89acc67ec4af516284b1bc33c                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0x716d4d9efc15bbe2dd81d2da31dccc4e2c69ccbb                         |                                                              |
| to                | VARCHAR   | 0x55fe002aeff02f77364de339a1292923a15844b8                         |                                                              |
| amount            | VARCHAR   | 10000000000000                                                     |                                                              |

## 3. Table: EuroCoin\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-01 10:11:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16953625                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4e3095543fd4a03662292513472f010fedbe859eec3eb130a3376b11d605d29b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 38                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1abaea1f7c830bd89acc67ec4af516284b1bc33c                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x150ec72d0e0b9ad6a75340640e5dbb0ee9b1b995                         |                                                              |
| to                | VARCHAR   | 0x382ffce2287252f930e1c8dc9328dac5bf282ba1                         |                                                              |
| value             | VARCHAR   | 995319                                                             |                                                              |

## 4. Table: MessageTransmitter\_event\_AttesterDisabled\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| attester          | VARCHAR   |                                                              |             |

## 5. Table: MessageTransmitter\_event\_AttesterEnabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-01 01:18:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16730458                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3b36bf8a22e677c99a21ee3bfe1bfe844a8463e253a4b90deb97b9bc1f56ad55 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 80                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0a992d191deec32afe36203ad87d7d289a738f81                         | Address of the contract that produced the log                |
| attester          | VARCHAR   | 0xe2fefe09e74b921cbbff229e7cd40009231501ca                         |                                                              |

## 6. Table: MessageTransmitter\_event\_AttesterManagerUpdated\_history

| Column                  | Type      | Example                                                            | Description                                                  |
| ----------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp        | TIMESTAMP | 2023-03-01 01:18:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number           | INTEGER   | 16730458                                                           | The block number where this event was emitted                |
| transaction\_hash       | VARCHAR   | 0xb6b7b744348845f9b9a8c03b57b7240f919e0b3a17213bb66e03b5e1c9d9350d | Hash of the transactions in which this event was emitted     |
| log\_index              | INTEGER   | 82                                                                 | Integer of the log index position in the block of this event |
| contract\_address       | VARCHAR   | 0x0a992d191deec32afe36203ad87d7d289a738f81                         | Address of the contract that produced the log                |
| previousAttesterManager | VARCHAR   | 0x6bf89579ff3fc3f2b57c0231e93ee78d35fbddac                         |                                                              |
| newAttesterManager      | VARCHAR   | 0x358a85e032aa9507a1303683b2b6a1d1cac3c252                         |                                                              |

## 7. Table: MessageTransmitter\_event\_MaxMessageBodySizeUpdated\_history

| Column                | Type      | Example                                                      | Description |
| --------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp      | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number         | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash     | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index            | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address     | VARCHAR   | Address of the contract that produced the log                |             |
| newMaxMessageBodySize | VARCHAR   |                                                              |             |

## 8. Table: MessageTransmitter\_event\_MessageReceived\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-06 08:41:47+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17420296                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0238a13324dcf8f1623289dc39b480590d21c0f5eb7252a951d7c02c68324260                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 259                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0a992d191deec32afe36203ad87d7d289a738f81                                                           | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x4718964ab638787283f14a0ef4a2b0d61298e6b5                                                           |                                                              |
| sourceDomain      | VARCHAR   | 1                                                                                                    |                                                              |
| nonce             | VARCHAR   | 429                                                                                                  |                                                              |
| sender            | VARCHAR   | 0x0000000000000000000000006b25532e1060ce10cc3b0a99e5683b91bfde6982                                   |                                                              |
| messageBody       | VARCHAR   | 0x00000000000000000000000000000000b97ef9ef8734c71904d8002f8b6bc66dd9c48a6e00000000000000000000000092 |                                                              |

## 9. Table: MessageTransmitter\_event\_MessageSent\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-15 06:38:11+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17697074                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9081a0282f24337518f5b0b2f90f46d0d8a4ca2e68f844985724f8fb8cc4f037                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 126                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0a992d191deec32afe36203ad87d7d289a738f81                                                           | Address of the contract that produced the log                |
| message           | VARCHAR   | 0x00000000000000000000000300000000000003f0000000000000000000000000bd3fa81b58ba92a82136038b25adec7066 |                                                              |

## 10. Table: MessageTransmitter\_event\_RescuerChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-28 23:51:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16730028                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x11ad531804edc6d6d8e5655d09a32adbb5fab7aa1034da74c6409472e1902138 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 49                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0a992d191deec32afe36203ad87d7d289a738f81                         | Address of the contract that produced the log                |
| newRescuer        | VARCHAR   | 0x6fa60a88b42afb0aee6488826a58864b192442ad                         |                                                              |

## 11. Table: MessageTransmitter\_event\_SignatureThresholdUpdated\_history

| Column                | Type      | Example                                                            | Description                                                  |
| --------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp      | TIMESTAMP | 2023-03-01 01:18:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number         | INTEGER   | 16730458                                                           | The block number where this event was emitted                |
| transaction\_hash     | VARCHAR   | 0x76197d00ecaf4aef1680b4f2ab391c19867ad4d44e50f37be258aea83936e63b | Hash of the transactions in which this event was emitted     |
| log\_index            | INTEGER   | 81                                                                 | Integer of the log index position in the block of this event |
| contract\_address     | VARCHAR   | 0x0a992d191deec32afe36203ad87d7d289a738f81                         | Address of the contract that produced the log                |
| oldSignatureThreshold | VARCHAR   | 1                                                                  |                                                              |
| newSignatureThreshold | VARCHAR   | 2                                                                  |                                                              |

## 12. Table: TokenMessenger\_event\_DepositForBurn\_history

| Column                    | Type      | Example                                                            | Description                                                  |
| ------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp          | TIMESTAMP | 2023-05-21 08:02:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number             | INTEGER   | 17306432                                                           | The block number where this event was emitted                |
| transaction\_hash         | VARCHAR   | 0x3407f3d8a276503d46e9453add83cfe3bf662cbe7780d264f3495ac08936eddf | Hash of the transactions in which this event was emitted     |
| log\_index                | INTEGER   | 295                                                                | Integer of the log index position in the block of this event |
| contract\_address         | VARCHAR   | 0xbd3fa81b58ba92a82136038b25adec7066af3155                         | Address of the contract that produced the log                |
| nonce                     | VARCHAR   | 117                                                                |                                                              |
| burnToken                 | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| amount                    | VARCHAR   | 3483689226                                                         |                                                              |
| depositor                 | VARCHAR   | 0x3a23f943181408eac424116af7b7790c94cb97a5                         |                                                              |
| mintRecipient             | VARCHAR   | 0x0000000000000000000000006922fb0a00c638707445c10c6a5cf5a5f65661eb |                                                              |
| destinationDomain         | VARCHAR   | 1                                                                  |                                                              |
| destinationTokenMessenger | VARCHAR   | 0x0000000000000000000000006b25532e1060ce10cc3b0a99e5683b91bfde6982 |                                                              |
| destinationCaller         | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000 |                                                              |

## 13. Table: TokenMessenger\_event\_LocalMinterAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-28 23:52:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16730036                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa8cfe3934eddbd7b1d752dd8a999a0d5c44899b8d5c3ad85f6522ccab545dab5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 24                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbd3fa81b58ba92a82136038b25adec7066af3155                         | Address of the contract that produced the log                |
| localMinter       | VARCHAR   | 0xc4922d64a24675e16e1586e3e3aa56c06fabe907                         |                                                              |

## 14. Table: TokenMessenger\_event\_LocalMinterRemoved\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| localMinter       | VARCHAR   |                                                              |             |

## 15. Table: TokenMessenger\_event\_MintAndWithdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-31 09:05:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17377852                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf1c9e0a330ac65ca17be80702a1644e0005d049417688124f58f5ca8f8f7870d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 89                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbd3fa81b58ba92a82136038b25adec7066af3155                         | Address of the contract that produced the log                |
| mintRecipient     | VARCHAR   | 0x0b9ffe93fe40e5879cd42ac998ca237b72e91162                         |                                                              |
| amount            | VARCHAR   | 270576087111                                                       |                                                              |
| mintToken         | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |

## 16. Table: TokenMessenger\_event\_RemoteTokenMessengerAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-12 16:09:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17465062                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfa985713da53dc0a7e4892a0304900063758f72232eb9439467a677378e3cbb1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbd3fa81b58ba92a82136038b25adec7066af3155                         | Address of the contract that produced the log                |
| domain            | VARCHAR   | 3                                                                  |                                                              |
| tokenMessenger    | VARCHAR   | 0x00000000000000000000000019330d10d9cc8751218eaf51e8885d058642e08a |                                                              |

## 17. Table: TokenMessenger\_event\_RemoteTokenMessengerRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-01 00:31:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16730225                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe8212e16d39eabf6167d677a30709b4c9a95afa7dfc0aac0c2ecbc0dd14b231c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 64                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbd3fa81b58ba92a82136038b25adec7066af3155                         | Address of the contract that produced the log                |
| domain            | VARCHAR   | 1                                                                  |                                                              |
| tokenMessenger    | VARCHAR   | 0x000000000000000000000000684e3bb8522083676adf3219fdd0cbf9d1c2aa13 |                                                              |

## 18. Table: TokenMessenger\_event\_RescuerChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-28 23:51:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16730030                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb3f0cb2fe27bf10d038e17642e15b6cc68e988e6d0b02161a5f27770b0c4aca6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 71                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbd3fa81b58ba92a82136038b25adec7066af3155                         | Address of the contract that produced the log                |
| newRescuer        | VARCHAR   | 0x65cbcdbe95567a8f9519242f9c52f65e8067021b                         |                                                              |
