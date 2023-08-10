# livepeertoken

## 1. Table: LivepeerToken\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-06-13 01:34:08+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7947423                                                                        | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3bb83642c58f4dd1218b7c92f4d938ac07ccde2dbc1785ce36557c145c1db543             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 124                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x58b6a8a3302369daec383334672404ee733ab239                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x513b23eefaeb51c7097f71f4bfab1139779082d1                                     |                                                              |
| spender           | VARCHAR   | 0x2240dab907db71e64d3e0dba4800c83b5c502d4e                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 2. Table: LivepeerToken\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-08-14 13:36:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8348925                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xeaf5df880dc1a0f356d71eca80abd8cd70b30d61ce9a498bc36ffad6efb17cd0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 88                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x58b6a8a3302369daec383334672404ee733ab239                         | Address of the contract that produced the log                |
| burner            | VARCHAR   | 0xe118f6f9d1ba8680a6e901f0d21b3426c02c1c54                         |                                                              |
| value             | VARCHAR   | 2                                                                  |                                                              |

## 3. Table: LivepeerToken\_event\_MintFinished\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 4. Table: LivepeerToken\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-02-14 01:47:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7217484                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8e25ea47e531a45bbb50f93ddfda84000dbcd087589ac2e7b4deea7dd0395853 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 56                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x58b6a8a3302369daec383334672404ee733ab239                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0x8573f2f5a3bd960eee3d998473e50c75cdbe6828                         |                                                              |
| amount            | VARCHAR   | 1774949786647754704525                                             |                                                              |

## 5. Table: LivepeerToken\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-04-30 21:43:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5534334                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x542f09dae9233f47c33159e51b0d17214fefd10bb9aa83c1b382f93e25d4d16a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 86                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x58b6a8a3302369daec383334672404ee733ab239                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x3a9543d4767b2c914ea22fd0b07e17b0901aaebf                         |                                                              |
| newOwner          | VARCHAR   | 0x8573f2f5a3bd960eee3d998473e50c75cdbe6828                         |                                                              |

## 6. Table: LivepeerToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-25 22:01:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11525377                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x040a02579495341f6838eed0450d13cf90b75c87135d7d308dc3822d4bec4244 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 294                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x58b6a8a3302369daec383334672404ee733ab239                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x755c1a8f71f4210cd7b60b9439451efcbeba33d1                         |                                                              |
| to                | VARCHAR   | 0xfed8eac5c0a82c3291977fb3bcf1ad52e57b1b9b                         |                                                              |
| value             | VARCHAR   | 65900732260261178150                                               |                                                              |
