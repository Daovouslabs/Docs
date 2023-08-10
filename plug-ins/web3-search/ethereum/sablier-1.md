# sablier

## 1. Table: Sablier\_event\_CancelStream\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-09 04:09:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12790946                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5fc1a76d7b2ff435f8a601b8a03f591f2f09d924c8ec847bc70b68cdc2f7cbaa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 339                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa4fc358455febe425536fd1878be67ffdbdec59a                         | Address of the contract that produced the log                |
| streamId          | VARCHAR   | 4903                                                               |                                                              |
| sender            | VARCHAR   | 0xbd6a40bb904aea5a49c59050b5395f7484a4203d                         |                                                              |
| recipient         | VARCHAR   | 0x5378224aa4c2c3ab0c4219534aaf2aab4c1cc3fb                         |                                                              |
| senderBalance     | VARCHAR   | 3184052885967704338854                                             |                                                              |
| recipientBalance  | VARCHAR   | 65947114032273914496                                               |                                                              |

## 2. Table: Sablier\_event\_CreateCompoundingStream\_history

| Column                   | Type      | Example                                                      | Description |
| ------------------------ | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp         | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number            | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash        | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index               | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address        | VARCHAR   | Address of the contract that produced the log                |             |
| streamId                 | VARCHAR   |                                                              |             |
| exchangeRate             | VARCHAR   |                                                              |             |
| senderSharePercentage    | VARCHAR   |                                                              |             |
| recipientSharePercentage | VARCHAR   |                                                              |             |

## 3. Table: Sablier\_event\_CreateStream\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-02-17 16:48:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9501748                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0740c2ac7a497dc821acb0fe68f7651c4bd86e17d0c977c86791d87fd9a6f52c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 145                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa4fc358455febe425536fd1878be67ffdbdec59a                         | Address of the contract that produced the log                |
| streamId          | VARCHAR   | 443                                                                |                                                              |
| sender            | VARCHAR   | 0xbd6a40bb904aea5a49c59050b5395f7484a4203d                         |                                                              |
| recipient         | VARCHAR   | 0x0492b9170ec01d91f3aa721ff8ada42dd33fbbb8                         |                                                              |
| deposit           | VARCHAR   | 2999999999998944000                                                |                                                              |
| tokenAddress      | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         |                                                              |
| startTime         | VARCHAR   | 1581958303                                                         |                                                              |
| stopTime          | VARCHAR   | 1584550303                                                         |                                                              |

## 4. Table: Sablier\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-09 01:47:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9243595                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x45f0d8d3892ea4870b908c2792a197d5c9d0f22e6f060161e7a8d9b44ded6b17 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 96                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa4fc358455febe425536fd1878be67ffdbdec59a                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x7c25bb1dd0fb91c69664c461909161a14dee9782                         |                                                              |
| newOwner          | VARCHAR   | 0x217a46aa92afd9f4f4e170bc85aee6f36e14eddf                         |                                                              |

## 5. Table: Sablier\_event\_Paused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |

## 6. Table: Sablier\_event\_PauserAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-12 18:18:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8921858                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6c83edbdca73d59852a032660271d6481decb59682005dd69930091ac57e274f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 23                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa4fc358455febe425536fd1878be67ffdbdec59a                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x7c25bb1dd0fb91c69664c461909161a14dee9782                         |                                                              |

## 7. Table: Sablier\_event\_PauserRemoved\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |

## 8. Table: Sablier\_event\_PayInterest\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| streamId          | VARCHAR   |                                                              |             |
| senderInterest    | VARCHAR   |                                                              |             |
| recipientInterest | VARCHAR   |                                                              |             |
| sablierInterest   | VARCHAR   |                                                              |             |

## 9. Table: Sablier\_event\_TakeEarnings\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| tokenAddress      | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 10. Table: Sablier\_event\_Unpaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |

## 11. Table: Sablier\_event\_UpdateFee\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| fee               | VARCHAR   |                                                              |             |

## 12. Table: Sablier\_event\_WithdrawFromStream\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-23 10:27:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17321341                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcf0f1cd6b18b9d60786685ab6e40ed99df8461051870e91af249eb418a023dc3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 149                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa4fc358455febe425536fd1878be67ffdbdec59a                         | Address of the contract that produced the log                |
| streamId          | VARCHAR   | 3129                                                               |                                                              |
| recipient         | VARCHAR   | 0x6e3aa85db95bba36276a37ed93b12b7ab0782afb                         |                                                              |
| amount            | VARCHAR   | 1263568619989852607382                                             |                                                              |
