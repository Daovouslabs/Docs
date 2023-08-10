# nexus\_mutual

## 1. Table: PooledStaking\_event\_Staked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-14 11:03:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12824763                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9d6a639ba14de4c3b889b03033fede248acc85f6f028eed7b6a076b093d03b45 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 234                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x84edffa16bb0b9ab1163abb0a13ff0744c11272f                         | Address of the contract that produced the log                |
| contractAddress   | VARCHAR   | 0x0000000000000000000000000000000000000012                         |                                                              |
| staker            | VARCHAR   | 0x55b72e024679d8cff3b68fc39be26b1f3fe453e0                         |                                                              |
| amount            | VARCHAR   | 500000000000000000000                                              |                                                              |

## 2. Table: PooledStaking\_event\_Unstaked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-08 03:41:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15922691                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6b096d1149b95dc8eaffd3ced2db6afbad9e34ea118b4c9982dd094d6b07333e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 177                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x84edffa16bb0b9ab1163abb0a13ff0744c11272f                         | Address of the contract that produced the log                |
| contractAddress   | VARCHAR   | 0x00000000219ab540356cbb839cbe05303d7705fa                         |                                                              |
| staker            | VARCHAR   | 0x96182047553d3c45ae54e5669ed63cfeb5420514                         |                                                              |
| amount            | VARCHAR   | 20000000000000000000                                               |                                                              |
