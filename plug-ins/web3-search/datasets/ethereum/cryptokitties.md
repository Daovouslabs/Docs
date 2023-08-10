# cryptokitties

## 1. Table: KittyCore\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-29 03:06:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15234901                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x26bee97eb1114432ff606d27d4c9f9a08dcf443efabfdd435c5e0cafbb2059a8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 99                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x06012c8cf97bead5deae237070f9587f8e7a266d                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x1a9fb86111a05353ddd0ce58f8d9368cef8a2b40                         |                                                              |
| approved          | VARCHAR   | 0x09fe5f0236f0ea5d930197dce254d77b04128075                         |                                                              |
| tokenId           | VARCHAR   | 1195519                                                            |                                                              |

## 2. Table: KittyCore\_event\_Birth\_history

| Column            | Type      | Example                                                                  | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-24 13:31:55+00:00                                                | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9155930                                                                  | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x18e36112e3ee533314568ad6f56f156950c70dbadb578c2ed49eb18d9865603c       | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 34                                                                       | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x06012c8cf97bead5deae237070f9587f8e7a266d                               | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x018ff336578ba559a9b6840647daad1ccded24db                               |                                                              |
| kittyId           | VARCHAR   | 1787468                                                                  |                                                              |
| matronId          | VARCHAR   | 1784601                                                                  |                                                              |
| sireId            | VARCHAR   | 1784602                                                                  |                                                              |
| genes             | VARCHAR   | 235163245181268516067168117735514527804840524432897423969931576287273538 |                                                              |

## 3. Table: KittyCore\_event\_ContractUpgrade\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newContract       | VARCHAR   |                                                              |             |

## 4. Table: KittyCore\_event\_Pregnant\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-25 06:55:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11521272                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1818e22ecb6891f6b643222a1d8cecaee7ecf52f3563a04269c7b7ca52f6c4ca | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 332                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x06012c8cf97bead5deae237070f9587f8e7a266d                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x0e706d98614a085e82bdf2cbb919f452581a9799                         |                                                              |
| matronId          | VARCHAR   | 1912847                                                            |                                                              |
| sireId            | VARCHAR   | 1806614                                                            |                                                              |
| cooldownEndBlock  | VARCHAR   | 11561592                                                           |                                                              |

## 5. Table: KittyCore\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-17 17:43:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15554865                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4f2da4051ad69f3779e13d6cbd0768a769f340260128d5f01c41f13e64ce5c8e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 236                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x06012c8cf97bead5deae237070f9587f8e7a266d                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x7477e2cd7584a33be8d568a7862bd218e6db9ffb                         |                                                              |
| to                | VARCHAR   | 0x09fe5f0236f0ea5d930197dce254d77b04128075                         |                                                              |
| tokenId           | VARCHAR   | 1998060                                                            |                                                              |
