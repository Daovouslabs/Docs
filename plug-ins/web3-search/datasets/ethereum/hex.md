# hex

## 1. Table: HEX\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-24 20:22:59+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15820300                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf2d668f8aa9330ab0893bdd8061e180671ad9133bf901cd40641dbf93b90016e             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 390                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2b591e99afe9f32eaa6214f7b7629768c40eeb39                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x0000000000007f150bd6f54c40a34d7c3d5e9f56                                     |                                                              |
| spender           | VARCHAR   | 0x05cde89ccfa0ada8c88d5a23caaa79ef129e7883                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457582075033122046441 |                                                              |

## 2. Table: HEX\_event\_Claim\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-07 02:19:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10215917                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x69c201ffe0eeb6eb701c4aa85047f7f11e7feca0dcf64060ff53fe7ee8e1476c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 82                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2b591e99afe9f32eaa6214f7b7629768c40eeb39                         | Address of the contract that produced the log                |
| data0             | VARCHAR   | 936340860206526640709652974334401191117979661346255981530808       |                                                              |
| data1             | VARCHAR   | 79556758027595337627276805384288209800363917937                    |                                                              |
| btcAddr           | VARCHAR   | 0x3c1e784f44e8c471f6166eef321f19785bf957fa                         |                                                              |
| claimToAddr       | VARCHAR   | 0x0def72cb13f38bfbd231c89ab426aea3829a4271                         |                                                              |
| referrerAddr      | VARCHAR   | 0x53de8e2f9beec1b7efa6c0575a387cb98715a82b                         |                                                              |

## 3. Table: HEX\_event\_DailyDataUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-27 00:02:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16057607                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x394eddf3a7e8957cea5e6f9003af4524ae3ea8c6fd79ab299b0327aaee3be3d8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 133                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2b591e99afe9f32eaa6214f7b7629768c40eeb39                         | Address of the contract that produced the log                |
| data0             | VARCHAR   | 4800910457740818819331                                             |                                                              |
| updaterAddr       | VARCHAR   | 0xde9b1cbfff2d07ad5ef276156aa61acd6f4a9b60                         |                                                              |

## 4. Table: HEX\_event\_ShareRateChange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-15 00:42:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17261710                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8872a7d0263fa1ec6969f8025a514c2b76f88a2c4c9b87089a00dbbd6200a569 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 310                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2b591e99afe9f32eaa6214f7b7629768c40eeb39                         | Address of the contract that produced the log                |
| data0             | VARCHAR   | 298779092392706031                                                 |                                                              |
| stakeId           | VARCHAR   | 786585                                                             |                                                              |

## 5. Table: HEX\_event\_StakeEnd\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-12 12:24:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9266109                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe17e46c73d5876326b418690e938eebb9537b926749e15d252f7f96583d8d396 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 34                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2b591e99afe9f32eaa6214f7b7629768c40eeb39                         | Address of the contract that produced the log                |
| data0             | VARCHAR   | 52151389837657602464688741484703139082234936167984607414103773206  |                                                              |
| data1             | VARCHAR   | 113336795588871485128704                                           |                                                              |
| stakerAddr        | VARCHAR   | 0x0351da4b8a9a4eed837b08c9e78db83933a547aa                         |                                                              |
| stakeId           | VARCHAR   | 58859                                                              |                                                              |

## 6. Table: HEX\_event\_StakeGoodAccounting\_history

| Column            | Type      | Example                                                             | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-16 22:12:19+00:00                                           | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10473132                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcc8178db73c5526e781093356c66d6261adfba7055cbe8554b64a552275b1ce7  | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 173                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2b591e99afe9f32eaa6214f7b7629768c40eeb39                          | Address of the contract that produced the log                |
| data0             | VARCHAR   | 9928185823756821636996120864771700171302216786059448375039235248323 |                                                              |
| data1             | VARCHAR   | 148641467438                                                        |                                                              |
| stakerAddr        | VARCHAR   | 0xb1d7aaf4561ad86ee3f35fd6b62a0431909a5bb4                          |                                                              |
| stakeId           | VARCHAR   | 66503                                                               |                                                              |
| senderAddr        | VARCHAR   | 0xb1d7aaf4561ad86ee3f35fd6b62a0431909a5bb4                          |                                                              |

## 7. Table: HEX\_event\_StakeStart\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-04 16:53:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13740943                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4732801c772cd040427aa82f23a8137468f3d7cad7cbed935fa81fb9368b2794 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 508                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2b591e99afe9f32eaa6214f7b7629768c40eeb39                         | Address of the contract that produced the log                |
| data0             | VARCHAR   | 465878644443255832966483639351850549868954106781204454636          |                                                              |
| stakerAddr        | VARCHAR   | 0x02468d836e3b99a515511fa196ebb7b24adcff93                         |                                                              |
| stakeId           | VARCHAR   | 536545                                                             |                                                              |

## 8. Table: HEX\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-27 18:51:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17572579                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdf1f5d2d06e626f5320b38265e634bdf984cc239747d8f8fb1cbd9f3a1e821eb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2b591e99afe9f32eaa6214f7b7629768c40eeb39                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000cd00001700b10049dfc947103e00e1c62683                         |                                                              |
| to                | VARCHAR   | 0x9e0905249ceefffb9605e034b534544684a58be6                         |                                                              |
| value             | VARCHAR   | 79110145743765                                                     |                                                              |

## 9. Table: HEX\_event\_XfLobbyEnter\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-19 00:50:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9128192                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdcd749d197b93cc1758c4a3b0b28d5768f700b05f6457b8970e52dc0715bf972 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 220                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2b591e99afe9f32eaa6214f7b7629768c40eeb39                         | Address of the contract that produced the log                |
| data0             | VARCHAR   | 345246651121664000001576716633                                     |                                                              |
| memberAddr        | VARCHAR   | 0x88928100967857ce474029a5ad7929b47933b002                         |                                                              |
| entryId           | VARCHAR   | 17592186044416                                                     |                                                              |
| referrerAddr      | VARCHAR   | 0x5e8bc9f76ef5060ebeac12cfd8d31298b9f9a52b                         |                                                              |

## 10. Table: HEX\_event\_XfLobbyExit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-20 07:29:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10495051                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xac48e48666c201ebd03ed972d161d6fa1d07587604bfa13e77a9dfcceb49d6d0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 189                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2b591e99afe9f32eaa6214f7b7629768c40eeb39                         | Address of the contract that produced the log                |
| data0             | VARCHAR   | 929355689889474347878332                                           |                                                              |
| memberAddr        | VARCHAR   | 0xd6f7c94c8e82c7e2e1234c636d509d9065b1c36f                         |                                                              |
| entryId           | VARCHAR   | 229797930205184                                                    |                                                              |
| referrerAddr      | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
