# seaport

## 1. Table: SeaportV14\_event\_CounterIncremented\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-24 12:35:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 104433095                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x299285838299d3d3a9c7ec843ec6614a6be1eede68bbd0e6c594971083f38d92 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000001ad428e4906ae43d8f9852d0dd6                         | Address of the contract that produced the log                |
| newCounter        | VARCHAR   | 130227902372806636584582739408712507167                            |                                                              |
| offerer           | VARCHAR   | 0x457244a384d08b781b40087923748db6545bb7d9                         |                                                              |

## 2. Table: SeaportV14\_event\_OrderCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-12 15:39:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 89983423                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xeef4555bb15a7f97b69efabe4e626d68c6217cf8354f23d6034f334e4c283ccc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 31                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000000adc04c56bf30ac9d3c0aaf14dc                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0x19a27f9f94daea7939e40bc468f7beae5237e33467b0bf7f823d065b243efeb5 |                                                              |
| offerer           | VARCHAR   | 0x0274507b22d08458fdbe38fe6a3abc9294854d23                         |                                                              |
| zone              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 3. Table: SeaportV14\_event\_OrderFulfilled\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-29 10:34:20+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 95630593                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe3b97eff82d3bbfe9ceabbfb28006de456c9f5b360495b317dd68444efdd93c1                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                                                    | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000000adc04c56bf30ac9d3c0aaf14dc                                                           | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0x9f935c3904b5dfca98bd3a9065e8924a1c5a2fa41d19c111db70bf01b4f747df                                   |                                                              |
| offerer           | VARCHAR   | 0x4f637c244b74dc15cb43bbfc8cd3e18e6256e017                                                           |                                                              |
| zone              | VARCHAR   | 0x0000000000000000000000000000000000000000                                                           |                                                              |
| recipient         | VARCHAR   | 0xa1434a89fd35874205a8f52fec758fefc35dc7ee                                                           |                                                              |
| offer             | VARCHAR   | 2,0x62aE32c10D0bbAa3D8222856816a22AC4C98b4De,3180,1                                                  |                                                              |
| consideration     | VARCHAR   | 0,0x0000000000000000000000000000000000000000,0,136900000000000000,0x4f637C244b74dc15CB43BBfC8Cd3E18E |                                                              |

## 4. Table: SeaportV14\_event\_OrderValidated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-13 15:25:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 80062838                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbfc6eecfd2bea9b0e1641f5c372428ecf9f5ff76901968b2f923e927641c7e5b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 26                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000001ad428e4906ae43d8f9852d0dd6                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0xdf55b40d8ec77e271794f30f4142abcc68ae26565435dd91bc94a25ebc140127 |                                                              |
| orderParameters   | VARCHAR   | \[object Object]                                                   |                                                              |

## 5. Table: SeaportV14\_event\_OrdersMatched\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-14 21:59:00+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 111257896                                                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0c46ff8e16cf44ba9108991303b015d359e5daf6c74844fe6ba36c284e538270                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                                                    | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000000adc04c56bf30ac9d3c0aaf14dc                                                           | Address of the contract that produced the log                |
| orderHashes       | VARCHAR   | 0x07a0a1740f49ed81b70f7a94ada4904e816a36c0f71765c758e3e9d1d62cf551,0x76307c45b0481fd1057515e39c6f9f1 |                                                              |

## 6. Table: Seaport\_event\_CounterIncremented\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-20 14:18:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 62783915                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0988359389693503ec050cf26d085fe27b9f9db7d5186e26bf694389d423f88a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 15                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                         | Address of the contract that produced the log                |
| newCounter        | VARCHAR   | 3                                                                  |                                                              |
| offerer           | VARCHAR   | 0x489d69939b4aca357f630055e351a81f1fbb7fb6                         |                                                              |

## 7. Table: Seaport\_event\_OrderCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-23 11:51:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 31940400                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x304c7d7e24718d6e2561866bc3e5b3f3bf06b968bb56995b723326d16da7dbe3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0x6db943e47079d9a1e5a5479554581cdb5c6e717b45404535eba8734f124ab939 |                                                              |
| offerer           | VARCHAR   | 0x014bd2092b57b0ab1a0df6ec6df615e4822a2c21                         |                                                              |
| zone              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 8. Table: Seaport\_event\_OrderFulfilled\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-28 05:49:50+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 27133176                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0ea9376f9a07564c9d1ab87df46e264ec026c41e50956efbe3942d1b6f7ad2e1                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                                                    | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                                                           | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0xcbe20d005e67281a2530d8ab8b5282b8d4593f33f7d23130d0308b160d57b675                                   |                                                              |
| offerer           | VARCHAR   | 0xb2b9300475af157676c44ee64d39a5eb3c294dbd                                                           |                                                              |
| zone              | VARCHAR   | 0x0000000000000000000000000000000000000000                                                           |                                                              |
| recipient         | VARCHAR   | 0x12c162d1a60b518fee11686044210fffc14b71d4                                                           |                                                              |
| offer             | VARCHAR   | 2,0xFE7891aE8951b702a59E70DA44447bD9D7efEfcd,377,1                                                   |                                                              |
| consideration     | VARCHAR   | 0,0x0000000000000000000000000000000000000000,0,9550000000000,0xb2b9300475aF157676C44eE64d39a5eB3C294 |                                                              |

## 9. Table: Seaport\_event\_OrderValidated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| orderHash         | VARCHAR   |                                                              |             |
| offerer           | VARCHAR   |                                                              |             |
| zone              | VARCHAR   |                                                              |             |
