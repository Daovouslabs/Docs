# weth

## 1. Table: WETH9\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-07-05 18:41:33+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8092951                                                                        | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1a0a668d94e4101ad3db8d5e966d354aafa5f9aa3a1b1c5a1837945490d2d92b             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                              | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                                     | Address of the contract that produced the log                |
| src               | VARCHAR   | 0x17b4bb0948002e9c275ef6fe597162cd0f479636                                     |                                                              |
| guy               | VARCHAR   | 0x0c77c219a86dc885b640cffeb705f39dd983cc08                                     |                                                              |
| wad               | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 2. Table: WETH9\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-07-22 09:06:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6009004                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x21d7f0dab3c3c6d0a25d9892546ee3e1e0a872b34f046d57576ac7e8f2801b34 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         | Address of the contract that produced the log                |
| dst               | VARCHAR   | 0x56cdc96f10d7047caeb77540ab5faa86f1a15c1b                         |                                                              |
| wad               | VARCHAR   | 200000000000000000                                                 |                                                              |

## 3. Table: WETH9\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-09 00:09:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10422016                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x93695fb3ae42b38174a86eb17ca6c5742cb9e9d70bb174e8f2a51efc6f89ce2f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 41                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0x43ae24960e5534731fc831386c07755a2dc33d47                         |                                                              |
| dst               | VARCHAR   | 0x3d2a167bfa1a9cf1f39531b3f81f7379d98f62c4                         |                                                              |
| wad               | VARCHAR   | 342205544945473039                                                 |                                                              |

## 4. Table: WETH9\_event\_Withdrawal\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-26 14:09:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9357883                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0d076c7dd4344e11f6fdc60907a24a50f27c5d3c0bbe1a216d154aa63738e8d4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 122                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0x0325b41a01bf133fffc875b604369512b9538758                         |                                                              |
| wad               | VARCHAR   | 700000000000000                                                    |                                                              |
