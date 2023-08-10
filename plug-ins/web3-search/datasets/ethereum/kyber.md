# kyber

## 1. Table: DMMFactory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-29 07:04:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12919283                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3a79ef811f209fdaecf3c0ce82c81c7881e159adcd55fa73ed1d558b643e7f48 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 129                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x833e4083b7ae46cea85695c4f7ed25cdad8886de                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0xbcd515d6c5de70d3a31d999a7fa6a299657de294                         |                                                              |
| token1            | VARCHAR   | 0xdac17f958d2ee523a2206206994597c13d831ec7                         |                                                              |
| pool              | VARCHAR   | 0x5d6e3ff93142aa2fc2063465e8e75b957b310351                         |                                                              |
| ampBps            | VARCHAR   | 13000                                                              |                                                              |
| totalPool         | VARCHAR   | 51                                                                 |                                                              |

## 2. Table: DMMPool\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-29 10:22:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13899642                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd14300217ed8503a32454ebfee0017c061b1c9b913be3570ae510da7355d90ea | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 36                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9a56f30ff04884cb06da80cb3aef09c6132f5e77                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x0000000000007f150bd6f54c40a34d7c3d5e9f56                         |                                                              |
| amount0In         | VARCHAR   | 18034645771959603302122                                            |                                                              |
| amount1In         | VARCHAR   | 0                                                                  |                                                              |
| amount0Out        | VARCHAR   | 0                                                                  |                                                              |
| amount1Out        | VARCHAR   | 4203714971074849413                                                |                                                              |
| to                | VARCHAR   | 0xdfee68a9adb981cd08699891a11cabe10f25ec44                         |                                                              |
| feeInPrecision    | VARCHAR   | 3831169406951060                                                   |                                                              |

## 3. Table: Factory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-05 10:15:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15281692                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x16ba2ecce1ffb3432ce60bd35d1662d87b78b7303b7e9db2b6351f1b26592563 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 109                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5f1dddbf348ac2fbe22a163e30f99f9ece3dd50a                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         |                                                              |
| token1            | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| swapFeeUnits      | VARCHAR   | 8                                                                  |                                                              |
| tickDistance      | VARCHAR   | 1                                                                  |                                                              |
| pool              | VARCHAR   | 0x496e02edb8ab781ca1a4db2e038e5730191c03dd                         |                                                              |

## 4. Table: FeeBurner\_event\_AdminClaimed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-15 06:58:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7069144                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3e8c93abcb7e646a03ee7711c23632df652dcbbe0a8d10067454c634912e358e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 56                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x52166528fcc12681af996e409ee3a421a4e128a3                         | Address of the contract that produced the log                |
| newAdmin          | VARCHAR   | 0xd0643bc0d0c879f175556509dbcee9373379d5c3                         |                                                              |
| previousAdmin     | VARCHAR   | 0x405a5fae110c86eb2e5a76809a17fc5bee2d3ccd                         |                                                              |

## 5. Table: FeeBurner\_event\_AssignBurnFees\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-05-15 17:28:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7766273                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xeabe8594a2570f48ce7a40c3e3a6f79b1997f0a1989bfeec1412a2ee8f99793a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 117                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x52166528fcc12681af996e409ee3a421a4e128a3                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x04a487afd662c4f9deacc07a7b10cfb686b682a4                         |                                                              |
| burnFee           | VARCHAR   | 376636159321030561                                                 |                                                              |

## 6. Table: FeeBurner\_event\_AssignFeeToWallet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-12-14 02:38:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6882575                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0d648fbab3905f42cabe9637cf33c961187b459f292eb991fa02504cce1c9f01 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xed4f53268bfdff39b36e8786247ba3a02cf34b04                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x21433dec9cb634a23c6a4bbcce08c83f5ac2ec18                         |                                                              |
| wallet            | VARCHAR   | 0x4247951c2eb6d0ba38d233fe7d542c8c80c9d46a                         |                                                              |
| walletFee         | VARCHAR   | 354007088265600                                                    |                                                              |

## 7. Table: FeeBurner\_event\_BurnAssignedFees\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-05-06 06:07:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5564683                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xce663a69b56dc7ad0b21b8ac75f84e03830e4ac5bedbabf8599f650579b852be | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 119                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x07f6e905f2a1559cd9fd43cb92f8a1062a3ca706                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x2aab2b157a03915c8a73adae735d0cf51c872f31                         |                                                              |
| sender            | VARCHAR   | 0xc86aabab79b3903320a91a873c6eba12c176732a                         |                                                              |
| quantity          | VARCHAR   | 424265309380721244441                                              |                                                              |

## 8. Table: FeeBurner\_event\_KNCRateSet\_history

| Column                | Type      | Example                                                            | Description                                                  |
| --------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp      | TIMESTAMP | 2020-06-30 12:08:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number         | INTEGER   | 10367029                                                           | The block number where this event was emitted                |
| transaction\_hash     | VARCHAR   | 0xd167e7e61f9d8dc080cb223af0c4c8e586de7b097c51097299a36e82b007c936 | Hash of the transactions in which this event was emitted     |
| log\_index            | INTEGER   | 112                                                                | Integer of the log index position in the block of this event |
| contract\_address     | VARCHAR   | 0x8007aa43792a392b221dc091bdb2191e5ff626d1                         | Address of the contract that produced the log                |
| ethToKncRatePrecision | VARCHAR   | 187351779661199539176                                              |                                                              |
| kyberEthKnc           | VARCHAR   | 187351779661199539176                                              |                                                              |
| kyberKncEth           | VARCHAR   | 5300306749631999                                                   |                                                              |
| updater               | VARCHAR   | 0x13809169a1e34ebb7c8a3665585dc0e353de7c54                         |                                                              |

## 9. Table: FeeBurner\_event\_OperatorAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-14 18:08:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7066077                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x194c6074c6862240d1fc2e2b7eade1fb0426c5b289c595100191bd84425e29d1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 222                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x52166528fcc12681af996e409ee3a421a4e128a3                         | Address of the contract that produced the log                |
| newOperator       | VARCHAR   | 0x24ad087a20548148fd8eed564a99f97b6254c4ba                         |                                                              |
| isAdd             | VARCHAR   | false                                                              |                                                              |

## 10. Table: FeeBurner\_event\_ReserveDataSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-08-16 03:57:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8359209                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x58da87349a777d305486d800e0e02fd5b811cc9e857c04dce6e0e158e9db7212 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x52166528fcc12681af996e409ee3a421a4e128a3                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0xd049aeb6662e74d568dc4652f962fc387d9183a7                         |                                                              |
| feeInBps          | VARCHAR   | 25                                                                 |                                                              |
| kncWallet         | VARCHAR   | 0xd049aeb6662e74d568dc4652f962fc387d9183a7                         |                                                              |

## 11. Table: FeeBurner\_event\_SendTaxFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-07-16 13:25:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5974942                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcb1a7d06d202d905d9693eb050a2bba31700287f0f9280726485cdc6194d53dc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 218                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xed4f53268bfdff39b36e8786247ba3a02cf34b04                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x21433dec9cb634a23c6a4bbcce08c83f5ac2ec18                         |                                                              |
| sender            | VARCHAR   | 0xc86aabab79b3903320a91a873c6eba12c176732a                         |                                                              |
| taxWallet         | VARCHAR   | 0xc065900403f9ff07dfaecc0d08978c2e0dee1578                         |                                                              |
| quantity          | VARCHAR   | 92085980838124888928                                               |                                                              |

## 12. Table: FeeBurner\_event\_SendWalletFees\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-02-03 18:58:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7169707                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4e264dd946d3ae0c85f377d6e987d5371e778d6420c5de0e62f897cb753a4eea | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 41                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x52166528fcc12681af996e409ee3a421a4e128a3                         | Address of the contract that produced the log                |
| wallet            | VARCHAR   | 0xb9e29984fe50602e7a619662ebed4f90d93824c7                         |                                                              |
| reserve           | VARCHAR   | 0x21433dec9cb634a23c6a4bbcce08c83f5ac2ec18                         |                                                              |
| sender            | VARCHAR   | 0xc86aabab79b3903320a91a873c6eba12c176732a                         |                                                              |

## 13. Table: FeeBurner\_event\_TaxFeesSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-07-26 10:43:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6032959                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x821f0fb21b501dd7dfba284e28cd9ba52290aa8349e5c0ee3b34b519085181df | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xed4f53268bfdff39b36e8786247ba3a02cf34b04                         | Address of the contract that produced the log                |
| feesInBps         | VARCHAR   | 0                                                                  |                                                              |

## 14. Table: FeeBurner\_event\_TaxWalletSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-07-05 19:23:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5911606                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdcabd324a5e07dd1a3ebbfcb24d465df7eb4cc882ab409453a596ffc4abffaa3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 148                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xed4f53268bfdff39b36e8786247ba3a02cf34b04                         | Address of the contract that produced the log                |
| taxWallet         | VARCHAR   | 0xc065900403f9ff07dfaecc0d08978c2e0dee1578                         |                                                              |

## 15. Table: FeeBurner\_event\_TokenWithdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-06-04 07:57:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5729704                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7d712030bbcc58d970a65fec620bc75c76528dc49e50b84006f120724ec478ab | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x07f6e905f2a1559cd9fd43cb92f8a1062a3ca706                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0xdd974d5c2e2928dea5f71b9825b8b646686bd200                         |                                                              |
| amount            | VARCHAR   | 100000000000000000000                                              |                                                              |
| sendTo            | VARCHAR   | 0x0fb2482f26db50c91a141bc2cd6930a8158b03d4                         |                                                              |

## 16. Table: FeeBurner\_event\_TransferAdminPending\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-26 15:45:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9004965                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5cd2fbb3f97d44b575938438e0757091c3e0df090b5475b7b68b5a354789442a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 193                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8007aa43792a392b221dc091bdb2191e5ff626d1                         | Address of the contract that produced the log                |
| pendingAdmin      | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 17. Table: FeeBurner\_event\_WalletFeesSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-07-20 04:19:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8185349                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfc1e472ff8d12e208b6649976d6b3fb2c06d34e5e213f192ca83f1d339973ece | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 27                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x52166528fcc12681af996e409ee3a421a4e128a3                         | Address of the contract that produced the log                |
| wallet            | VARCHAR   | 0xbd3bf40beebea315327cf69ece02431338f7efe7                         |                                                              |
| feesInBps         | VARCHAR   | 3000                                                               |                                                              |

## 18. Table: KyberFeeHandler\_event\_BRRUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-19 03:25:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10688122                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9f0ae0b85436a437f8f171d0e109903c7beb7cc6fa86312c04062a42d82f8304 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 158                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xec30037c9a8a6a3f42734c30dfa0a208af71b40c                         | Address of the contract that produced the log                |
| rewardBps         | VARCHAR   | 10                                                                 |                                                              |
| rebateBps         | VARCHAR   | 9990                                                               |                                                              |
| burnBps           | VARCHAR   | 0                                                                  |                                                              |
| expiryTimestamp   | VARCHAR   | 1597809599                                                         |                                                              |
| epoch             | VARCHAR   | 1536                                                               |                                                              |

## 19. Table: KyberFeeHandler\_event\_BurnConfigSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-06 11:27:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10405628                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x08d1b59127d81a964010cc16cee16e39dbcafc294f3804fa1a6f94ed2b0e5292 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 203                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd3d2b5643e506c6d9b7099e9116d7aaa941114fe                         | Address of the contract that produced the log                |
| sanityRate        | VARCHAR   | 0xd0e785973390ff8e77a83961efdb4f271e6b8152                         |                                                              |
| weiToBurn         | VARCHAR   | 2000000000000000000                                                |                                                              |

## 20. Table: KyberFeeHandler\_event\_EthReceived\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-02 09:22:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11574148                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc89a7c04721b50035d6e5768f210f1d270972d8c46ffbabe1f5324026667e8f1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 285                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd3d2b5643e506c6d9b7099e9116d7aaa941114fe                         | Address of the contract that produced the log                |
| amount            | VARCHAR   | 0                                                                  |                                                              |

## 21. Table: KyberFeeHandler\_event\_FeeDistributed\_history

| Column                    | Type      | Example                                                            | Description                                                  |
| ------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp          | TIMESTAMP | 2020-12-25 19:24:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number             | INTEGER   | 11524689                                                           | The block number where this event was emitted                |
| transaction\_hash         | VARCHAR   | 0x2cbfaa3726069333b016fde32055b74af9a7a0a7f908b4aaffc4843281a3c7f1 | Hash of the transactions in which this event was emitted     |
| log\_index                | INTEGER   | 134                                                                | Integer of the log index position in the block of this event |
| contract\_address         | VARCHAR   | 0xd3d2b5643e506c6d9b7099e9116d7aaa941114fe                         | Address of the contract that produced the log                |
| token                     | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| platformWallet            | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| platformFeeWei            | VARCHAR   | 0                                                                  |                                                              |
| rewardWei                 | VARCHAR   | 2943396998664060                                                   |                                                              |
| rebateWei                 | VARCHAR   | 0                                                                  |                                                              |
| rebateWallets             | VARCHAR   |                                                                    |                                                              |
| rebatePercentBpsPerWallet | VARCHAR   |                                                                    |                                                              |
| burnAmtWei                | VARCHAR   | 194552893301890                                                    |                                                              |

## 22. Table: KyberFeeHandler\_event\_KncBurned\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-03 19:00:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10984670                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2923dd538b4b6fca8be3f73670a069fe6fe60baaebf8dea16f605b7529c81885 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 229                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd3d2b5643e506c6d9b7099e9116d7aaa941114fe                         | Address of the contract that produced the log                |
| kncTWei           | VARCHAR   | 710173138979952875576                                              |                                                              |
| token             | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| amount            | VARCHAR   | 1915005762091460116                                                |                                                              |

## 23. Table: KyberFeeHandler\_event\_KyberDaoAddressSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-02 02:56:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10377456                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc9a8bdc25e82a45fb5b0badaa4f2ed26d99ed6b116334c865485653e94456bd3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 44                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xec30037c9a8a6a3f42734c30dfa0a208af71b40c                         | Address of the contract that produced the log                |
| kyberDao          | VARCHAR   | 0x39e507f4f7c3e85ed799fdbdf04e42104a8f6b9a                         |                                                              |

## 24. Table: KyberFeeHandler\_event\_KyberNetworkUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| kyberNetwork      | VARCHAR   |                                                              |             |

## 25. Table: KyberFeeHandler\_event\_KyberProxyUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| kyberProxy        | VARCHAR   |                                                              |             |

## 26. Table: KyberFeeHandler\_event\_PlatformFeePaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-28 14:07:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10749621                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x43638f6911ec0da2ecd956dce0df1394917fc1612e2bd9a281b60fd92b8f745d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 53                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd3d2b5643e506c6d9b7099e9116d7aaa941114fe                         | Address of the contract that produced the log                |
| platformWallet    | VARCHAR   | 0x68a17b587caf4f9329f0e372e3a78d23a46de6b5                         |                                                              |
| token             | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| amount            | VARCHAR   | 2347619691481926271                                                |                                                              |

## 27. Table: KyberFeeHandler\_event\_RebatePaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-21 01:09:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11695770                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0903e22eb2a51f74cdeccd068bb613d1a779f68b76b879cbe61795a94d241260 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 95                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd3d2b5643e506c6d9b7099e9116d7aaa941114fe                         | Address of the contract that produced the log                |
| rebateWallet      | VARCHAR   | 0x76043f4d08e2f3f2da6be61f43b637dd7eabf586                         |                                                              |
| token             | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| amount            | VARCHAR   | 6636344953586434693                                                |                                                              |

## 28. Table: KyberFeeHandler\_event\_RewardPaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-28 04:01:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10746900                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7a7eee7aafeb1ead0220ba01980478b0a4583965f6ff24c116f54f9be9e084bd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 78                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd3d2b5643e506c6d9b7099e9116d7aaa941114fe                         | Address of the contract that produced the log                |
| staker            | VARCHAR   | 0xeac446a86091dac36348df5fec35a09d0bd8e7d7                         |                                                              |
| epoch             | VARCHAR   | 1                                                                  |                                                              |
| token             | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| amount            | VARCHAR   | 612009418034645996                                                 |                                                              |

## 29. Table: KyberFeeHandler\_event\_RewardsRemovedToBurn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-25 08:16:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10527486                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7cb3370554ce6d319f363e42838c35ce9b3e7ae8cd827e1a535f53b7e5ed42fa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 76                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd3d2b5643e506c6d9b7099e9116d7aaa941114fe                         | Address of the contract that produced the log                |
| epoch             | VARCHAR   | 0                                                                  |                                                              |
| rewardsWei        | VARCHAR   | 171630696598748044259                                              |                                                              |

## 30. Table: KyberNetworkCrystal\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-08 09:20:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7030498                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x87c9cc8ccf07676fbd33dfdea47a7554bf5f21df729ecac5e93898229281f0a4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 112                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdd974d5c2e2928dea5f71b9825b8b646686bd200                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x8fa07f46353a2b17e92645592a94a0fc1ceb783f                         |                                                              |
| \_spender         | VARCHAR   | 0x818e6fecd516ecc3849daf6845e3ec868087b755                         |                                                              |
| \_value           | VARCHAR   | 0                                                                  |                                                              |

## 31. Table: KyberNetworkCrystal\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-08-12 06:01:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6132523                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc1570cd2f83a6ecdf92f2398ea70f8a852d6d11e246e982312b413dfcbcbcc7b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 163                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdd974d5c2e2928dea5f71b9825b8b646686bd200                         | Address of the contract that produced the log                |
| \_burner          | VARCHAR   | 0xed4f53268bfdff39b36e8786247ba3a02cf34b04                         |                                                              |
| \_value           | VARCHAR   | 2673004638658380591285                                             |                                                              |

## 32. Table: KyberNetworkCrystal\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-01 23:01:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17389074                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf557bce090b35f225cc91cda22b11e6c282146f78286063c18540ae5641cc4d0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 88                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdd974d5c2e2928dea5f71b9825b8b646686bd200                         | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0x76838fd2f22bdc1d3e96069971e65653173edb2a                         |                                                              |
| \_to              | VARCHAR   | 0xa80a7cfe6c01a13357bf26eebcf5ef5d5e05998f                         |                                                              |
| \_value           | VARCHAR   | 27908780304425618790                                               |                                                              |

## 33. Table: KyberNetworkProxyV2\_event\_ExecuteTrade\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-06 21:11:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13954222                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd58267d3636b0489c54149d2af4392e28f01cec4c28189953015227ffc5a1888 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9aab3f75489902f3a48495025729a0af77d4b11e                         | Address of the contract that produced the log                |
| trader            | VARCHAR   | 0x0000000000007f150bd6f54c40a34d7c3d5e9f56                         |                                                              |
| src               | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| dest              | VARCHAR   | 0x4a220e6096b25eadb88358cb44068a3248254675                         |                                                              |
| destAddress       | VARCHAR   | 0x0000000000007f150bd6f54c40a34d7c3d5e9f56                         |                                                              |
| actualSrcAmount   | VARCHAR   | 3634686690000000000                                                |                                                              |
| actualDestAmount  | VARCHAR   | 72380403650623185492                                               |                                                              |
| platformWallet    | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| platformFeeBps    | VARCHAR   | 0                                                                  |                                                              |

## 34. Table: KyberNetworkProxy\_event\_AdminClaimed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-07-05 18:45:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5911453                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xebe99a404e531c2aa77853a9cbd6c797722b824f123b55f5135de31e5a03cfb5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 179                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x818e6fecd516ecc3849daf6845e3ec868087b755                         | Address of the contract that produced the log                |
| newAdmin          | VARCHAR   | 0xd0643bc0d0c879f175556509dbcee9373379d5c3                         |                                                              |
| previousAdmin     | VARCHAR   | 0x73501f785ef90ad7490fe3b34e4f2b3461de3ac2                         |                                                              |

## 35. Table: KyberNetworkProxy\_event\_ExecuteTrade\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-16 00:57:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10870054                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2ca0bbc2ee9692ab32602ac783ff83bac0b2134a58c948e40561217640dd7aa5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 209                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x818e6fecd516ecc3849daf6845e3ec868087b755                         | Address of the contract that produced the log                |
| trader            | VARCHAR   | 0x860bd2dba9cd475a61e6d1b45e16c365f6d78f66                         |                                                              |
| src               | VARCHAR   | 0x0f5d2fb29fb7d3cfee444a200298f468908cc942                         |                                                              |
| dest              | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| actualSrcAmount   | VARCHAR   | 27347933349523702689706                                            |                                                              |
| actualDestAmount  | VARCHAR   | 5837121550626210300                                                |                                                              |

## 36. Table: KyberNetworkProxy\_event\_KyberNetworkSet\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2019-12-02 11:01:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 9037721                                                            | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0xaa45035562d9ccf2885fde48be03b467e1f112cfaebc84852e19805c9e7b4a06 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 104                                                                | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x818e6fecd516ecc3849daf6845e3ec868087b755                         | Address of the contract that produced the log                |
| newNetworkContract | VARCHAR   | 0x65bf64ff5f51272f729bdcd7acfb00677ced86cd                         |                                                              |
| oldNetworkContract | VARCHAR   | 0x9ae49c0d7f8f9ef4b864e004fe86ac8294e20950                         |                                                              |

## 37. Table: KyberNetworkProxy\_event\_TokenWithdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-18 22:27:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10292367                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaca721763b0489c7530ef52f56afce4dbf4639b0b9a09f2c8ffa28535d5cdfd9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 46                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x818e6fecd516ecc3849daf6845e3ec868087b755                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x8e870d67f660d95d5be530380d0ec0bd388289e1                         |                                                              |
| amount            | VARCHAR   | 165000000000000000000                                              |                                                              |
| sendTo            | VARCHAR   | 0x70f450d11faa8740604ae40d8034d190ce171771                         |                                                              |

## 38. Table: KyberNetworkProxy\_event\_TransferAdminPending\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-07-05 18:45:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5911453                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xebe99a404e531c2aa77853a9cbd6c797722b824f123b55f5135de31e5a03cfb5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 178                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x818e6fecd516ecc3849daf6845e3ec868087b755                         | Address of the contract that produced the log                |
| pendingAdmin      | VARCHAR   | 0xd0643bc0d0c879f175556509dbcee9373379d5c3                         |                                                              |

## 39. Table: KyberNetwork\_v1\_event\_AddReserveToNetwork\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-02-26 07:28:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5158358                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x849061985ce67cf42c809ba3db17e9ba48e0247462b2d6e582577b7f669c04ae | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 22                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x964f35fae36d75b1e72770e244f6595b68508cf5                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x2aab2b157a03915c8a73adae735d0cf51c872f31                         |                                                              |
| add               | VARCHAR   | true                                                               |                                                              |

## 40. Table: KyberNetwork\_v1\_event\_AdminClaimed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-02-26 07:28:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5158358                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x849061985ce67cf42c809ba3db17e9ba48e0247462b2d6e582577b7f669c04ae | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 8                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x964f35fae36d75b1e72770e244f6595b68508cf5                         | Address of the contract that produced the log                |
| newAdmin          | VARCHAR   | 0x83472f108363fd63626b130b50273282fe4a7c87                         |                                                              |
| previousAdmin     | VARCHAR   | 0xbc33a1f908612640f2849b56b67a4de4d179c151                         |                                                              |

## 41. Table: KyberNetwork\_v1\_event\_AlerterAdded\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newAlerter        | VARCHAR   |                                                              |             |
| isAdd             | VARCHAR   |                                                              |             |

## 42. Table: KyberNetwork\_v1\_event\_EtherReceival\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-06-02 21:18:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5721603                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xefe320268f8093ba5e6dc8645e696b95cc8e5fc3ca48407826bd8fe93bf1577b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 57                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x964f35fae36d75b1e72770e244f6595b68508cf5                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x2aab2b157a03915c8a73adae735d0cf51c872f31                         |                                                              |
| amount            | VARCHAR   | 152477809400000000                                                 |                                                              |

## 43. Table: KyberNetwork\_v1\_event\_EtherWithdraw\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| amount            | VARCHAR   |                                                              |             |
| sendTo            | VARCHAR   |                                                              |             |

## 44. Table: KyberNetwork\_v1\_event\_ExecuteTrade\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-05-06 09:28:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5565476                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc24da776d36d6159f3b3ed006245717ba33445d7a9fef2b1ba6489415ed543b5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 55                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x964f35fae36d75b1e72770e244f6595b68508cf5                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xe4ac23287891db9f38d055b422e8312f9ec63df0                         |                                                              |
| src               | VARCHAR   | 0x05f4a42e251f2d52b8ed15e9fedaacfcef1fad27                         |                                                              |
| dest              | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| actualSrcAmount   | VARCHAR   | 380000000000000                                                    |                                                              |
| actualDestAmount  | VARCHAR   | 65224797263511400                                                  |                                                              |

## 45. Table: KyberNetwork\_v1\_event\_ListReservePairs\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-05-30 15:31:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5703302                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9b14678c1008ee75297d0b9b19a24e7ea6ef6248968ae1a3276a177798761204 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 24                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x964f35fae36d75b1e72770e244f6595b68508cf5                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x2aab2b157a03915c8a73adae735d0cf51c872f31                         |                                                              |
| src               | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| dest              | VARCHAR   | 0x86fa049857e0209aa7d9e616f7eb3b3b78ecfdb0                         |                                                              |
| add               | VARCHAR   | false                                                              |                                                              |

## 46. Table: KyberNetwork\_v1\_event\_OperatorAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-02-07 21:28:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5049265                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8f07542f697055b83419e72fd6bbb09d0485ca29d8e5d1432036645b2d7c3d08 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 28                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x964f35fae36d75b1e72770e244f6595b68508cf5                         | Address of the contract that produced the log                |
| newOperator       | VARCHAR   | 0x8007ce15acda724689760b4ba493d4766f973649                         |                                                              |
| isAdd             | VARCHAR   | true                                                               |                                                              |

## 47. Table: KyberNetwork\_v1\_event\_TokenWithdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-07-08 07:22:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5926097                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xca84a6567c76f482e7baabef334fdff6cb50655693310aaa398e931f89102ae0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 14                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x964f35fae36d75b1e72770e244f6595b68508cf5                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x4f3afec4e5a3f2a6a1a411def7d7dfe50ee057bf                         |                                                              |
| amount            | VARCHAR   | 87963957051                                                        |                                                              |
| sendTo            | VARCHAR   | 0x818e6fecd516ecc3849daf6845e3ec868087b755                         |                                                              |

## 48. Table: KyberNetwork\_v1\_event\_TransferAdminPending\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-03-29 14:46:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5343519                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc80167432fa977bb0fa492df58cc52fd955940aaae359d126517058c215ac671 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 34                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x964f35fae36d75b1e72770e244f6595b68508cf5                         | Address of the contract that produced the log                |
| pendingAdmin      | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 49. Table: KyberNetwork\_v2\_event\_AddReserveToNetwork\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-08-09 04:34:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6114426                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd897b5a35a385de3b6a46e4e4164ccd9931ab26449d3461208dda3f9004cb3f2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x91a502c678605fbce581eae053319747482276b9                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x8bf5c569ecfd167f96fae6d9610e17571568a6a1                         |                                                              |
| add               | VARCHAR   | true                                                               |                                                              |

## 50. Table: KyberNetwork\_v2\_event\_AdminClaimed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-08-06 18:27:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6100102                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xda96e1fe28961be3783f5bef9a7c17a9781cc2d83f2a25d08567c1b20bc04509 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 16                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x91a502c678605fbce581eae053319747482276b9                         | Address of the contract that produced the log                |
| newAdmin          | VARCHAR   | 0xd0643bc0d0c879f175556509dbcee9373379d5c3                         |                                                              |
| previousAdmin     | VARCHAR   | 0xbc33a1f908612640f2849b56b67a4de4d179c151                         |                                                              |

## 51. Table: KyberNetwork\_v2\_event\_AlerterAdded\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newAlerter        | VARCHAR   |                                                              |             |
| isAdd             | VARCHAR   |                                                              |             |

## 52. Table: KyberNetwork\_v2\_event\_EtherReceival\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-12-03 07:19:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6817188                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1d9c26d40b7540f441c5ff14511cc110d76404386be279281e8b72814078a03f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 40                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x91a502c678605fbce581eae053319747482276b9                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x21433dec9cb634a23c6a4bbcce08c83f5ac2ec18                         |                                                              |
| amount            | VARCHAR   | 1827560176313045742                                                |                                                              |

## 53. Table: KyberNetwork\_v2\_event\_EtherWithdraw\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| amount            | VARCHAR   |                                                              |             |
| sendTo            | VARCHAR   |                                                              |             |

## 54. Table: KyberNetwork\_v2\_event\_KyberProxySet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-07-05 18:46:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5911455                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9e17eb5889dba5f9643f1c2880aeb026dbfacba7afae1c6951c06d6e592242fd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 111                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x91a502c678605fbce581eae053319747482276b9                         | Address of the contract that produced the log                |
| proxy             | VARCHAR   | 0x818e6fecd516ecc3849daf6845e3ec868087b755                         |                                                              |
| sender            | VARCHAR   | 0x73501f785ef90ad7490fe3b34e4f2b3461de3ac2                         |                                                              |

## 55. Table: KyberNetwork\_v2\_event\_KyberTrade\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-10-13 11:14:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6507018                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x122e5517450cae10f5cf2bf18ef283c730e9bb4f33591b40499fa4af8716b542 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 18                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x91a502c678605fbce581eae053319747482276b9                         | Address of the contract that produced the log                |
| srcAddress        | VARCHAR   | 0xed15e46c98d9ab221845c6a5798f3f3115d33cdf                         |                                                              |
| srcToken          | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| srcAmount         | VARCHAR   | 559000000000000000                                                 |                                                              |
| destAddress       | VARCHAR   | 0xed15e46c98d9ab221845c6a5798f3f3115d33cdf                         |                                                              |
| destToken         | VARCHAR   | 0xf0ee6b27b759c9893ce4f094b49ad28fd15a23e4                         |                                                              |
| destAmount        | VARCHAR   | 20065904604                                                        |                                                              |

## 56. Table: KyberNetwork\_v2\_event\_ListReservePairs\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-12-28 10:27:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6967482                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf2a213dfe62bf2bbba58fa3435cc89b3a9fa711b9f9e209126bac53149e985e5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 28                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x91a502c678605fbce581eae053319747482276b9                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0xa9312cb86d1e532b7c21881ce03a1a9d52f6adb1                         |                                                              |
| src               | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| dest              | VARCHAR   | 0x9389434852b94bbad4c8afed5b7bdbc5ff0c2275                         |                                                              |
| add               | VARCHAR   | true                                                               |                                                              |

## 57. Table: KyberNetwork\_v2\_event\_OperatorAdded\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newOperator       | VARCHAR   |                                                              |             |
| isAdd             | VARCHAR   |                                                              |             |

## 58. Table: KyberNetwork\_v2\_event\_TokenWithdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-07 08:16:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7024648                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8ed06a5d1f4c05376207c6464c8bf5002ab78e155628f44584a32ef6ba6fd734 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 19                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x91a502c678605fbce581eae053319747482276b9                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x4f3afec4e5a3f2a6a1a411def7d7dfe50ee057bf                         |                                                              |
| amount            | VARCHAR   | 9618107645                                                         |                                                              |
| sendTo            | VARCHAR   | 0x9ae49c0d7f8f9ef4b864e004fe86ac8294e20950                         |                                                              |

## 59. Table: KyberNetwork\_v3\_event\_AddReserveToNetwork\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-03-19 19:46:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7401231                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x12e62bdd678a9f35082c487bdb20381b2d2b52d2e2ff7695fc463248317da7e3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ae49c0d7f8f9ef4b864e004fe86ac8294e20950                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0xee29a0825bfd7ee2f40ff87ad0b0485884be98aa                         |                                                              |
| add               | VARCHAR   | true                                                               |                                                              |
| isPermissionless  | VARCHAR   | true                                                               |                                                              |

## 60. Table: KyberNetwork\_v3\_event\_AdminClaimed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-03 12:03:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7003226                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x22e79faabedf624872715893a0c7d351dbfff839807b5f43e97b86343c30e9fe | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 198                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ae49c0d7f8f9ef4b864e004fe86ac8294e20950                         | Address of the contract that produced the log                |
| newAdmin          | VARCHAR   | 0xd0643bc0d0c879f175556509dbcee9373379d5c3                         |                                                              |
| previousAdmin     | VARCHAR   | 0xabbbcdba6b65c429dc7bb90a65d6ded9b74e15a6                         |                                                              |

## 61. Table: KyberNetwork\_v3\_event\_EtherReceival\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-02-17 19:13:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7233072                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe5ca4b68d8a51b740d8b259af40a30ba3acd100c1dc2738512196fefff3e2103 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 43                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ae49c0d7f8f9ef4b864e004fe86ac8294e20950                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x04a487afd662c4f9deacc07a7b10cfb686b682a4                         |                                                              |
| amount            | VARCHAR   | 2562513641944030406                                                |                                                              |

## 62. Table: KyberNetwork\_v3\_event\_ExpectedRateContractSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-03-11 12:21:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7347830                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x44419212b2c8bfbc7eb1fbe4121356e184e9b8f91a027f1db40b520bc1600361 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 19                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ae49c0d7f8f9ef4b864e004fe86ac8294e20950                         | Address of the contract that produced the log                |
| newContract       | VARCHAR   | 0x10e6b432ae166401046511092c73aa8de71675f4                         |                                                              |
| currentContract   | VARCHAR   | 0x8bc9927e473acd8ec6c9f4432276233c185586a5                         |                                                              |

## 63. Table: KyberNetwork\_v3\_event\_FeeBurnerContractSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-03 11:39:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7003128                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x115affa56a6187b6d3f6553061c405abf0954346b511b817a14f631bd4f46727 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 107                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ae49c0d7f8f9ef4b864e004fe86ac8294e20950                         | Address of the contract that produced the log                |
| newContract       | VARCHAR   | 0x52166528fcc12681af996e409ee3a421a4e128a3                         |                                                              |
| currentContract   | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 64. Table: KyberNetwork\_v3\_event\_KyberNetworkSetEnable\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-03 12:02:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7003220                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x92eb22c7a86fb82ff230a15e921ef28d4fe5f4f2e763d4cfbd29be5d0d6a3767 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 68                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ae49c0d7f8f9ef4b864e004fe86ac8294e20950                         | Address of the contract that produced the log                |
| isEnabled         | VARCHAR   | true                                                               |                                                              |

## 65. Table: KyberNetwork\_v3\_event\_KyberNetwrokParamsSet\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2019-01-03 12:02:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 7003220                                                            | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0xbfb5c3c64e3c6cf51a6dde541621d2b7b1ab0c0e1a8862062b354485975f5d27 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 65                                                                 | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x9ae49c0d7f8f9ef4b864e004fe86ac8294e20950                         | Address of the contract that produced the log                |
| maxGasPrice        | VARCHAR   | 100000000000                                                       |                                                              |
| negligibleRateDiff | VARCHAR   | 20                                                                 |                                                              |

## 66. Table: KyberNetwork\_v3\_event\_KyberProxySet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-03 11:39:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7003126                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x67033d209394e3a7aac7448a955b6516620fdac174dd7b0bcdd22ec957b9b31a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 26                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ae49c0d7f8f9ef4b864e004fe86ac8294e20950                         | Address of the contract that produced the log                |
| proxy             | VARCHAR   | 0x818e6fecd516ecc3849daf6845e3ec868087b755                         |                                                              |
| sender            | VARCHAR   | 0xabbbcdba6b65c429dc7bb90a65d6ded9b74e15a6                         |                                                              |

## 67. Table: KyberNetwork\_v3\_event\_KyberTrade\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-03-21 16:28:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7413191                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8486e0cac7bbcb13b3da95195044fec9e739f78d0ffc8b63689aeaf56f049cc4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 124                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ae49c0d7f8f9ef4b864e004fe86ac8294e20950                         | Address of the contract that produced the log                |
| trader            | VARCHAR   | 0x3608e0e442f1d2bda33506a46f583f6930cd22fd                         |                                                              |
| src               | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| dest              | VARCHAR   | 0x05f4a42e251f2d52b8ed15e9fedaacfcef1fad27                         |                                                              |
| srcAmount         | VARCHAR   | 134884760000000000                                                 |                                                              |
| dstAmount         | VARCHAR   | 999999982339559                                                    |                                                              |
| destAddress       | VARCHAR   | 0x3608e0e442f1d2bda33506a46f583f6930cd22fd                         |                                                              |
| ethWeiValue       | VARCHAR   | 134884760000000000                                                 |                                                              |
| reserve1          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| reserve2          | VARCHAR   | 0x63825c174ab367968ec60f061753d3bbd36a0d8f                         |                                                              |
| hint              | VARCHAR   | 0x                                                                 |                                                              |

## 68. Table: KyberNetwork\_v3\_event\_ListReservePairs\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-03-01 22:56:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7286567                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1c2174abae8b1097a7fbd05f757b8703e97913103837b1dd4f2aac6dfdf5f36a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 46                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ae49c0d7f8f9ef4b864e004fe86ac8294e20950                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x74aea03f03366019db1ed8230fb7942f1bfa8b20                         |                                                              |
| src               | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| dest              | VARCHAR   | 0xbb0ef9e617faddf54b8d16e29046f72b4d3ec77f                         |                                                              |
| add               | VARCHAR   | true                                                               |                                                              |

## 69. Table: KyberNetwork\_v3\_event\_OperatorAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-03-03 10:01:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7295896                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x355afde6f88506d8172cde31cf2ae40dccc4f8988eea9f1f0c99897c93b08954 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 39                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ae49c0d7f8f9ef4b864e004fe86ac8294e20950                         | Address of the contract that produced the log                |
| newOperator       | VARCHAR   | 0x7c8cff2c659a3ee23869497a56129f3da92e8f38                         |                                                              |
| isAdd             | VARCHAR   | true                                                               |                                                              |

## 70. Table: KyberNetwork\_v3\_event\_RemoveReserveFromNetwork\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-07-17 10:21:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8167697                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb4574a9febfc883a151dd8e9c91ce4ae97b9c27b9b741e5035112c4ae87b9ef2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 119                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ae49c0d7f8f9ef4b864e004fe86ac8294e20950                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x13032deb2d37556cf49301f713e9d7e1d1a8b169                         |                                                              |

## 71. Table: KyberNetwork\_v3\_event\_TokenWithdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-08-26 14:41:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8426446                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf8be26866513cab62160835ec441b5e5361e121985253095f239fe6644a4dedf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 90                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ae49c0d7f8f9ef4b864e004fe86ac8294e20950                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0xbf2179859fc6d5bee9bf9158632dc51678a4100e                         |                                                              |
| amount            | VARCHAR   | 1616380000000000000000                                             |                                                              |
| sendTo            | VARCHAR   | 0x7389692a261c498c964a35aa521d90ef6984075d                         |                                                              |

## 72. Table: KyberNetwork\_v3\_event\_TransferAdminPending\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-03-11 06:29:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7346269                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2b253dfb1e21a03afe945f533547e446824c9e88698f7802cb96deb4d5f8876c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 43                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ae49c0d7f8f9ef4b864e004fe86ac8294e20950                         | Address of the contract that produced the log                |
| pendingAdmin      | VARCHAR   | 0xbc33a1f908612640f2849b56b67a4de4d179c151                         |                                                              |

## 73. Table: KyberNetwork\_v4\_event\_AddReserveToNetwork\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-09 08:39:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9636219                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xabf4464c164ad5ce18cb89c2a0b826068137d4d44ebb959556d7b24830598f3c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 46                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x65bf64ff5f51272f729bdcd7acfb00677ced86cd                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x0ce59e811024c4aa040389fb8917dd9edaef1693                         |                                                              |
| add               | VARCHAR   | true                                                               |                                                              |
| isPermissionless  | VARCHAR   | false                                                              |                                                              |

## 74. Table: KyberNetwork\_v4\_event\_AdminClaimed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-02 10:53:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9037689                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x442b3b8ceec618ab873dddf7d114b651f3cf8288b3c18b6621ec671d4d2c607e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 108                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x65bf64ff5f51272f729bdcd7acfb00677ced86cd                         | Address of the contract that produced the log                |
| newAdmin          | VARCHAR   | 0xbc33a1f908612640f2849b56b67a4de4d179c151                         |                                                              |
| previousAdmin     | VARCHAR   | 0xd3cc03c1d1e9d46f28aebc4ba26c5990c7ffbc3e                         |                                                              |

## 75. Table: KyberNetwork\_v4\_event\_EtherReceival\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-23 18:55:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9339705                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa09b14d48dcc869fd60098ebd87531b1c60bdca6abb803c0986bc3ca704401e2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 105                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x65bf64ff5f51272f729bdcd7acfb00677ced86cd                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x05461124c86c0ad7c5d8e012e1499fd9109ffb7d                         |                                                              |
| amount            | VARCHAR   | 174610987034680647                                                 |                                                              |

## 76. Table: KyberNetwork\_v4\_event\_ExpectedRateContractSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-26 10:00:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9003573                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb1758f8099570641d5b416eae0a94f7d91a93416bcbd7d1cb563a1a1def77384 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 22                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x65bf64ff5f51272f729bdcd7acfb00677ced86cd                         | Address of the contract that produced the log                |
| newContract       | VARCHAR   | 0x38a5cf926a0b9b5fe3a265c57d184ad8c0af05b6                         |                                                              |
| currentContract   | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 77. Table: KyberNetwork\_v4\_event\_FeeBurnerContractSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-26 10:00:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9003573                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x414902d78c203bf61c68102fe5dd487f5c0a94ee77455f143ceff585cdb6cd40 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 23                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x65bf64ff5f51272f729bdcd7acfb00677ced86cd                         | Address of the contract that produced the log                |
| newContract       | VARCHAR   | 0x050ad7965f96e9ff595021845e45746b2b4b5f91                         |                                                              |
| currentContract   | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 78. Table: KyberNetwork\_v4\_event\_KyberNetworkSetEnable\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-02 07:25:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9036844                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdcd78d936e92282de159f04ed74f8316b764f7f7dc46025a23dae8a8ebe0f82b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 123                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x65bf64ff5f51272f729bdcd7acfb00677ced86cd                         | Address of the contract that produced the log                |
| isEnabled         | VARCHAR   | false                                                              |                                                              |

## 79. Table: KyberNetwork\_v4\_event\_KyberNetwrokParamsSet\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2020-03-20 07:41:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 9707285                                                            | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0xb23abd198db7b17ce1b4d359bc1dcd5dadc14029aa6d35ffa44e0eb5d63ac2fc | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 67                                                                 | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x65bf64ff5f51272f729bdcd7acfb00677ced86cd                         | Address of the contract that produced the log                |
| maxGasPrice        | VARCHAR   | 100000000000                                                       |                                                              |
| negligibleRateDiff | VARCHAR   | 1                                                                  |                                                              |

## 80. Table: KyberNetwork\_v4\_event\_KyberProxySet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-02 11:34:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9037854                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x14b195b0f39c297163c20e817eebda2e0c6e5c6fd5eb90cb873f93e1c75a43ca | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 245                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x65bf64ff5f51272f729bdcd7acfb00677ced86cd                         | Address of the contract that produced the log                |
| proxy             | VARCHAR   | 0x818e6fecd516ecc3849daf6845e3ec868087b755                         |                                                              |
| sender            | VARCHAR   | 0xbc33a1f908612640f2849b56b67a4de4d179c151                         |                                                              |

## 81. Table: KyberNetwork\_v4\_event\_KyberTrade\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-02 00:13:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9789206                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9f36e6b7c70f79b75d08d15641fb8e35b7bc42fd7c896f02d221c01377961e38 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 24                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x65bf64ff5f51272f729bdcd7acfb00677ced86cd                         | Address of the contract that produced the log                |
| trader            | VARCHAR   | 0x521550e569bc80f1b4957c4f3fd3d677d9ca31f1                         |                                                              |
| src               | VARCHAR   | 0x0d8775f648430679a709e98d2b0cb6250d2887ef                         |                                                              |
| dest              | VARCHAR   | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599                         |                                                              |
| srcAmount         | VARCHAR   | 6095035656045677845321                                             |                                                              |
| dstAmount         | VARCHAR   | 12922100                                                           |                                                              |
| destAddress       | VARCHAR   | 0x521550e569bc80f1b4957c4f3fd3d677d9ca31f1                         |                                                              |
| ethWeiValue       | VARCHAR   | 6337073473722704585                                                |                                                              |
| reserve1          | VARCHAR   | 0x31e085afd48a1d6e51cc193153d625e8f0514c7f                         |                                                              |
| reserve2          | VARCHAR   | 0x485c4ec93d18ebd16623d455567886475ae28d04                         |                                                              |
| hint              | VARCHAR   | 0x                                                                 |                                                              |

## 82. Table: KyberNetwork\_v4\_event\_ListReservePairs\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-02-20 09:29:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9519296                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6a28449e8b261dd7c0e08e319f79f497e86f72c81083deff497a2dde8eec2d38 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 108                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x65bf64ff5f51272f729bdcd7acfb00677ced86cd                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x55a8fda671a257b80258d2a03abd6e0e1e3dbe79                         |                                                              |
| src               | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| dest              | VARCHAR   | 0x6710c63432a2de02954fc0f851db07146a6c0312                         |                                                              |
| add               | VARCHAR   | true                                                               |                                                              |

## 83. Table: KyberNetwork\_v4\_event\_OperatorAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-26 15:44:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9004963                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3bbe103faeeb29c9fc95baecca9aa9f75efbe12f3c1c6c50b119b9cb61e29851 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 194                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x65bf64ff5f51272f729bdcd7acfb00677ced86cd                         | Address of the contract that produced the log                |
| newOperator       | VARCHAR   | 0x3f9ccdff24631203a05d069efde6a0c0715aeb1e                         |                                                              |
| isAdd             | VARCHAR   | false                                                              |                                                              |

## 84. Table: KyberNetwork\_v4\_event\_RemoveReserveFromNetwork\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-08 08:59:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10024618                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcb9e1d863e7b84a4f6c8a5e686a32536cb13ddddd07b711900e6ab0fbdba1ee5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 20                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x65bf64ff5f51272f729bdcd7acfb00677ced86cd                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x742e8bb8e6bde9cb2df5449f8de7510798727fb1                         |                                                              |

## 85. Table: KyberNetwork\_v4\_event\_TransferAdminPending\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-26 06:52:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9164554                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8e16afc1f5efac5ce7ec8b2ff83a0c4b48c0330c95c6cb28c4dcfd2e0d4c835a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 116                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x65bf64ff5f51272f729bdcd7acfb00677ced86cd                         | Address of the contract that produced the log                |
| pendingAdmin      | VARCHAR   | 0x9f2807356cbd4b1ebd28b1c53850248aafb3a29b                         |                                                              |

## 86. Table: KyberNetwork\_v5\_event\_AdminClaimed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-06 03:51:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10403556                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x155f27a94e9c939ba30ab2da46ffaba8a024eaf78a0fe63a2da9a1714630c9b9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 127                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7c66550c9c730b6fdd4c03bc2e73c5462c5f7acc                         | Address of the contract that produced the log                |
| newAdmin          | VARCHAR   | 0x8180a5ca4e3b94045e05a9313777955f7518d757                         |                                                              |
| previousAdmin     | VARCHAR   | 0xbdd33f411da0b40018922a3bc69001b458227f5c                         |                                                              |

## 87. Table: KyberNetwork\_v5\_event\_AlerterAdded\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newAlerter        | VARCHAR   |                                                              |             |
| isAdd             | VARCHAR   |                                                              |             |

## 88. Table: KyberNetwork\_v5\_event\_EtherReceival\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-16 01:10:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12834929                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5f741a1ee625dc439088a6c99e5ccbb2485c9473c0bbdb858ecd48641e32e679 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 300                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7c66550c9c730b6fdd4c03bc2e73c5462c5f7acc                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x0994c18ed0c328f38d2c451b2a2e1ceb1ae6a812                         |                                                              |
| amount            | VARCHAR   | 537179514133640582                                                 |                                                              |

## 89. Table: KyberNetwork\_v5\_event\_EtherWithdraw\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| amount            | VARCHAR   |                                                              |             |
| sendTo            | VARCHAR   |                                                              |             |

## 90. Table: KyberNetwork\_v5\_event\_GasHelperUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newGasHelper      | VARCHAR   |                                                              |             |

## 91. Table: KyberNetwork\_v5\_event\_KyberDaoUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-06 02:50:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10403272                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3506236fcc01671b734571f86ad877dcc2ff57e09d4d52fe30388efd4b50c0c4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 33                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7c66550c9c730b6fdd4c03bc2e73c5462c5f7acc                         | Address of the contract that produced the log                |
| newKyberDao       | VARCHAR   | 0x49bdd8854481005bba4acebabf6e06cd5f6312e9                         |                                                              |

## 92. Table: KyberNetwork\_v5\_event\_KyberFeeHandlerUpdated\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2020-07-06 02:50:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 10403272                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x9686f1bb1e05dcb772c5e77e480fbc96e284004d5488a61db9b29596dcea2c84 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 31                                                                 | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x7c66550c9c730b6fdd4c03bc2e73c5462c5f7acc                         | Address of the contract that produced the log                |
| newKyberFeeHandler | VARCHAR   | 0xd3d2b5643e506c6d9b7099e9116d7aaa941114fe                         |                                                              |

## 93. Table: KyberNetwork\_v5\_event\_KyberMatchingEngineUpdated\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2020-07-06 02:50:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 10403272                                                           | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0x9686f1bb1e05dcb772c5e77e480fbc96e284004d5488a61db9b29596dcea2c84 | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 32                                                                 | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0x7c66550c9c730b6fdd4c03bc2e73c5462c5f7acc                         | Address of the contract that produced the log                |
| newKyberMatchingEngine | VARCHAR   | 0xa1c0fa73c39cfbcc11ec9eb1afc665aba9996e2c                         |                                                              |

## 94. Table: KyberNetwork\_v5\_event\_KyberNetworkParamsSet\_history

| Column                | Type      | Example                                                            | Description                                                  |
| --------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp      | TIMESTAMP | 2020-08-04 10:16:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number         | INTEGER   | 10592654                                                           | The block number where this event was emitted                |
| transaction\_hash     | VARCHAR   | 0x1a3990196936ae31820b871b193f1a26e8d4aeabe794e6f9a1311bed2672821c | Hash of the transactions in which this event was emitted     |
| log\_index            | INTEGER   | 115                                                                | Integer of the log index position in the block of this event |
| contract\_address     | VARCHAR   | 0x7c66550c9c730b6fdd4c03bc2e73c5462c5f7acc                         | Address of the contract that produced the log                |
| maxGasPrice           | VARCHAR   | 150000000000                                                       |                                                              |
| negligibleRateDiffBps | VARCHAR   | 1                                                                  |                                                              |

## 95. Table: KyberNetwork\_v5\_event\_KyberNetworkSetEnable\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-07 06:18:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10410610                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x185617f6ab3bb25428f1e004691dcc765039facbaf19073b671753b933eee4d8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 67                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7c66550c9c730b6fdd4c03bc2e73c5462c5f7acc                         | Address of the contract that produced the log                |
| isEnabled         | VARCHAR   | true                                                               |                                                              |

## 96. Table: KyberNetwork\_v5\_event\_KyberProxyAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-06 02:50:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10403272                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2671c52443779ee418ea9343699db8df1ba2016f5bbfd8ceac0ca4da8da96b4b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 35                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7c66550c9c730b6fdd4c03bc2e73c5462c5f7acc                         | Address of the contract that produced the log                |
| kyberProxy        | VARCHAR   | 0x9aab3f75489902f3a48495025729a0af77d4b11e                         |                                                              |

## 97. Table: KyberNetwork\_v5\_event\_KyberProxyRemoved\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| kyberProxy        | VARCHAR   |                                                              |             |

## 98. Table: KyberNetwork\_v5\_event\_KyberTrade\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2023-07-28 19:35:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 17793670                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xdd65dfefaa82fc34b5074f7c7e925bc9d9c480bdd52cc53447c9cc8b57858774 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 24                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x7c66550c9c730b6fdd4c03bc2e73c5462c5f7acc                         | Address of the contract that produced the log                |
| src                  | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| dest                 | VARCHAR   | 0x4a220e6096b25eadb88358cb44068a3248254675                         |                                                              |
| ethWeiValue          | VARCHAR   | 1900000000000000000                                                |                                                              |
| networkFeeWei        | VARCHAR   | 1900000000000000                                                   |                                                              |
| customPlatformFeeWei | VARCHAR   | 0                                                                  |                                                              |
| t2eIds               | VARCHAR   |                                                                    |                                                              |
| e2tIds               | VARCHAR   | 0xaa514e5452657365727665000000000000000000000000000000000000000000 |                                                              |
| t2eSrcAmounts        | VARCHAR   |                                                                    |                                                              |
| e2tSrcAmounts        | VARCHAR   | 1898100000000000000                                                |                                                              |
| t2eRates             | VARCHAR   |                                                                    |                                                              |
| e2tRates             | VARCHAR   | 17892410057350763089                                               |                                                              |

## 99. Table: KyberNetwork\_v5\_event\_ListedReservesForToken\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| token             | VARCHAR   |                                                              |             |
| reserves          | VARCHAR   |                                                              |             |
| add               | VARCHAR   |                                                              |             |

## 100. Table: KyberNetwork\_v5\_event\_OperatorAdded\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newOperator       | VARCHAR   |                                                              |             |
| isAdd             | VARCHAR   |                                                              |             |

## 101. Table: KyberNetwork\_v5\_event\_TokenWithdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-08 08:37:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11996800                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9f0f8cb8505604677e7f44ba12e8f73c6f6de9753c9686c0653b1baeba575986 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 98                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7c66550c9c730b6fdd4c03bc2e73c5462c5f7acc                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x1f9840a85d5af5bf1d1762f925bdaddc4201f984                         |                                                              |
| amount            | VARCHAR   | 400000000000000000000                                              |                                                              |
| sendTo            | VARCHAR   | 0x8180a5ca4e3b94045e05a9313777955f7518d757                         |                                                              |

## 102. Table: KyberNetwork\_v5\_event\_TransferAdminPending\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-06 03:51:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10403556                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x155f27a94e9c939ba30ab2da46ffaba8a024eaf78a0fe63a2da9a1714630c9b9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 126                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7c66550c9c730b6fdd4c03bc2e73c5462c5f7acc                         | Address of the contract that produced the log                |
| pendingAdmin      | VARCHAR   | 0x8180a5ca4e3b94045e05a9313777955f7518d757                         |                                                              |

## 103. Table: Pool\_event\_Flash\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-14 17:49:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17046973                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf85bd7b9faa68f35c0007808e1832cdbab3b40358e8d6feda4e8ff703cf706b7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 28                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xebfe63ba0264ad639b3c41d2bfe1ad708f683bc8                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x27cc12685d31d713ca8a00d8f8ea1f3761b56f9f                         |                                                              |
| recipient         | VARCHAR   | 0x27cc12685d31d713ca8a00d8f8ea1f3761b56f9f                         |                                                              |
| qty0              | VARCHAR   | 4594984897332158000                                                |                                                              |
| qty1              | VARCHAR   | 0                                                                  |                                                              |
| paid0             | VARCHAR   | 367598791786572                                                    |                                                              |
| paid1             | VARCHAR   | 0                                                                  |                                                              |

## 104. Table: Pool\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-28 04:34:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16066122                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf2aad31efbb61a7251f57bd41b780aadbe998d6ca35470e6f0d20eca1e6b4fe6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 176                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xebfe63ba0264ad639b3c41d2bfe1ad708f683bc8                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x0773edc0438b2ef18fc535b21d0ac77912c308c0                         |                                                              |
| recipient         | VARCHAR   | 0x0773edc0438b2ef18fc535b21d0ac77912c308c0                         |                                                              |
| deltaQty0         | VARCHAR   | -11066079820358652383                                              |                                                              |
| deltaQty1         | VARCHAR   | 11959657355668357120                                               |                                                              |
| sqrtP             | VARCHAR   | 82363675855577012442746346560                                      |                                                              |
| liquidity         | VARCHAR   | 226263790260290245680040                                           |                                                              |
| currentTick       | VARCHAR   | 776                                                                |                                                              |
