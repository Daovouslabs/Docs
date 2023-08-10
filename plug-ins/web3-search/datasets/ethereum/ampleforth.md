# ampleforth

## 1. Table: UFragmentsPolicy\_event\_LogRebase\_history

| Column                    | Type      | Example                                                            | Description                                                  |
| ------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp          | TIMESTAMP | 2020-11-19 02:00:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number             | INTEGER   | 11285555                                                           | The block number where this event was emitted                |
| transaction\_hash         | VARCHAR   | 0x6561bfe60449a3aeb0b0375036c8350c15a2debc45bc787d0bc124ea3a0f8bc0 | Hash of the transactions in which this event was emitted     |
| log\_index                | INTEGER   | 206                                                                | Integer of the log index position in the block of this event |
| contract\_address         | VARCHAR   | 0x1b228a749077b8e307c5856ce62ef35d96dca2ea                         | Address of the contract that produced the log                |
| epoch                     | VARCHAR   | 509                                                                |                                                              |
| exchangeRate              | VARCHAR   | 1002959143281955322                                                |                                                              |
| cpi                       | VARCHAR   | 111442000000000008636                                              |                                                              |
| requestedSupplyAdjustment | VARCHAR   | 0                                                                  |                                                              |
| timestampSec              | VARCHAR   | 1605751208                                                         |                                                              |

## 2. Table: UFragments\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-21 18:40:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17743366                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4c905eccfef29f03bad71e8a89c276d0c6c0dba1c043c15c565142a2784bc3ae | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 378                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd46ba6d942050d489dbd938a2c909a5d5039a161                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x8b5f86f1ce7d0985c96d2f91275d8e4feb6badd6                         |                                                              |
| spender           | VARCHAR   | 0x000000000022d473030f116ddee9f6b43ac78ba3                         |                                                              |
| value             | VARCHAR   | 2760072181595                                                      |                                                              |

## 3. Table: UFragments\_event\_LogMonetaryPolicyUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-06-14 02:00:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7953968                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4ee46e5f2d4ac333c91f887bb61d517fa719ff323a55778d537c74cd7b73d724 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd46ba6d942050d489dbd938a2c909a5d5039a161                         | Address of the contract that produced the log                |
| monetaryPolicy    | VARCHAR   | 0x1b228a749077b8e307c5856ce62ef35d96dca2ea                         |                                                              |

## 4. Table: UFragments\_event\_LogRebasePaused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-06-15 00:37:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7960008                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3079d7abc2ff965ebc162799227cd7470a7ea365143e89e481cb54ed5f72e777 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 8                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd46ba6d942050d489dbd938a2c909a5d5039a161                         | Address of the contract that produced the log                |
| paused            | VARCHAR   | true                                                               |                                                              |

## 5. Table: UFragments\_event\_LogRebase\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-23 02:00:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17318840                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1547b8eba731d2f87a613e05dd734d7b7b3e0471c7fa36fcf210aa04fc1fbb73 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 415                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd46ba6d942050d489dbd938a2c909a5d5039a161                         | Address of the contract that produced the log                |
| epoch             | VARCHAR   | 1423                                                               |                                                              |
| totalSupply       | VARCHAR   | 31124348368469942                                                  |                                                              |

## 6. Table: UFragments\_event\_LogTokenPaused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-06-26 17:03:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8034825                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x13f9b1119d9f2a8ac135bf55816028f8e99412e5e60d389a9de5bb530f9c301d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 95                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd46ba6d942050d489dbd938a2c909a5d5039a161                         | Address of the contract that produced the log                |
| paused            | VARCHAR   | false                                                              |                                                              |

## 7. Table: UFragments\_event\_OwnershipRenounced\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner     | VARCHAR   |                                                              |             |

## 8. Table: UFragments\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-06-14 02:02:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7953982                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x951f4a11d6c66250da646c4d9781300cf7934de2857cb6aa384e4255e49511e1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 8                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd46ba6d942050d489dbd938a2c909a5d5039a161                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0xd8461bd73f19e3d789ac0e5dbf1ad62fbbd15c22                         |                                                              |
| newOwner          | VARCHAR   | 0xa847dc227d3f3e86fa01406279c1e88cb6950c3a                         |                                                              |

## 9. Table: UFragments\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-21 10:59:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17741077                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf8c7dda93e93fd7ae083a99fb7a12098190d060b05396cae73be70f3afc74432 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 108                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd46ba6d942050d489dbd938a2c909a5d5039a161                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x42d6ff162528619f46fb1f1b5edcb38170344fcd                         |                                                              |
| to                | VARCHAR   | 0x64e5464181885967c86a1ec5aecc9725ecad2086                         |                                                              |
| value             | VARCHAR   | 57646888053                                                        |                                                              |
