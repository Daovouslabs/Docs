# quickswap

## 1. Table: AlgebraFactory\_event\_FarmingAddress\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-02 20:46:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 32611216                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbc966729798b7f129a6fdc9d828bfdb92bfb0fb92dcca99a1769f7296c04fb17 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 9                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x411b0facc3489691f28ad58c47006af5e3ab3a28                         | Address of the contract that produced the log                |
| newFarmingAddress | VARCHAR   | 0x7f281a8cdf66ef5e9db8434ec6d97acc1bc01e78                         |                                                              |

## 2. Table: AlgebraFactory\_event\_FeeConfiguration\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| alpha1            | VARCHAR   |                                                              |             |
| alpha2            | VARCHAR   |                                                              |             |
| beta1             | VARCHAR   |                                                              |             |
| beta2             | VARCHAR   |                                                              |             |
| gamma1            | VARCHAR   |                                                              |             |
| gamma2            | VARCHAR   |                                                              |             |
| volumeBeta        | VARCHAR   |                                                              |             |
| volumeGamma       | VARCHAR   |                                                              |             |
| baseFee           | VARCHAR   |                                                              |             |

## 3. Table: AlgebraFactory\_event\_Owner\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-02 20:28:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 32610688                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xeef56ffeb56294b1abc2b753638402d0bd1b5134d1b8e654b44a9589ceee1057 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x411b0facc3489691f28ad58c47006af5e3ab3a28                         | Address of the contract that produced the log                |
| newOwner          | VARCHAR   | 0x476307dac3fd170166e007fcaa14f0a129721463                         |                                                              |

## 4. Table: AlgebraFactory\_event\_Pool\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-05 14:10:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 36457633                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdaa4c79b74f0172056d621dc18ba4bc4db9eb7e7e3cb2b4ec89c39da59f177d0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 396                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x411b0facc3489691f28ad58c47006af5e3ab3a28                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         |                                                              |
| token1            | VARCHAR   | 0x0fb760873ad1eca38b778500bd55124e421ca565                         |                                                              |
| pool              | VARCHAR   | 0xbeffc807616fbf30ea430c915eddf768a3fa35cc                         |                                                              |

## 5. Table: AlgebraFactory\_event\_VaultAddress\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-13 17:25:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 34300909                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf1a4671e28edc45572f5b7c2d9b1c1df1cd36a8811137afacf1af1f53a5f9459 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x411b0facc3489691f28ad58c47006af5e3ab3a28                         | Address of the contract that produced the log                |
| newVaultAddress   | VARCHAR   | 0xb771380f912e4b5f6beddf81314c383c13f16ab5                         |                                                              |

## 6. Table: AlgebraPool\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-07 03:44:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 40055849                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x58dee4eb553b8e9b36eaed176328cdfbdeeaada8a52749296669b9c2351265a2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 285                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x479e1b71a702a595e19b6d5932cd5c863ab57ee0                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x02203f2351e7ac6ab5051205172d3f772db7d814                         |                                                              |
| bottomTick        | VARCHAR   | -72180                                                             |                                                              |
| topTick           | VARCHAR   | -71220                                                             |                                                              |
| liquidityAmount   | VARCHAR   | 0                                                                  |                                                              |
| amount0           | VARCHAR   | 0                                                                  |                                                              |
| amount1           | VARCHAR   | 0                                                                  |                                                              |

## 7. Table: AlgebraPool\_event\_Collect\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-11 00:25:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 44929854                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x423351bf80e997b897689faf5cecf181c6d863693d1b8f7d9e691bf15177105b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 116                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x479e1b71a702a595e19b6d5932cd5c863ab57ee0                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x02203f2351e7ac6ab5051205172d3f772db7d814                         |                                                              |
| recipient         | VARCHAR   | 0x02203f2351e7ac6ab5051205172d3f772db7d814                         |                                                              |
| bottomTick        | VARCHAR   | -79440                                                             |                                                              |
| topTick           | VARCHAR   | -77400                                                             |                                                              |
| amount0           | VARCHAR   | 209817974730286044762                                              |                                                              |
| amount1           | VARCHAR   | 102458527823918537                                                 |                                                              |

## 8. Table: AlgebraPool\_event\_CommunityFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-22 07:12:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 44197423                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0dac3b51c3c8e53d9463631923be1a9ff54738609e10f8315c6735b3e8e2d870 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 419                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf705989751aeb6ec7090908ef05a540c93dd001b                         | Address of the contract that produced the log                |
| communityFee0New  | VARCHAR   | 100                                                                |                                                              |
| communityFee1New  | VARCHAR   | 100                                                                |                                                              |

## 9. Table: AlgebraPool\_event\_Fee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-17 23:36:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 38210159                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfbb7cad0d705f0acbb61f13655bbfd51dbefe9d61afd709cec2d10a5e1d9d407 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 298                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x022df0b3341b3a0157eea97dd024a93f7496d631                         | Address of the contract that produced the log                |
| fee               | VARCHAR   | 1513                                                               |                                                              |

## 10. Table: AlgebraPool\_event\_Flash\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-10 18:33:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 37912262                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb2ec7104be88527fd64d70b5ca2370f512908289a2db6e62a7aeb18312ea8947 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 89                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5b1fd9fa139353c5d9eaf459e4bd2f7a6b4812bb                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x95eb76ff99abfef6263bbb359097e8e3917c232d                         |                                                              |
| recipient         | VARCHAR   | 0x95eb76ff99abfef6263bbb359097e8e3917c232d                         |                                                              |
| amount0           | VARCHAR   | 92099475644524337                                                  |                                                              |
| amount1           | VARCHAR   | 0                                                                  |                                                              |
| paid0             | VARCHAR   | 9209947564453                                                      |                                                              |
| paid1             | VARCHAR   | 0                                                                  |                                                              |

## 11. Table: AlgebraPool\_event\_Incentive\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2023-02-04 09:56:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 38896273                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x069d10771da18a00121a7f4f4b52d97a9947b7ad6952ed93634cc5b17f9914e4 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 487                                                                | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x63aefd3aefeedce0860a5ef21c1af548641620dd                         | Address of the contract that produced the log                |
| virtualPoolAddress | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 12. Table: AlgebraPool\_event\_Initialize\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-20 08:56:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 38303360                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3297942788bcf18bcd113509085926732dc5f9687a46e89e6df0da56ef2b1842 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 290                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45ffec411de0c6a100ceb4d9ba0f973aefe86d57                         | Address of the contract that produced the log                |
| price             | VARCHAR   | 769328583893843729950215983823                                     |                                                              |
| tick              | VARCHAR   | 45466                                                              |                                                              |

## 13. Table: AlgebraPool\_event\_LiquidityCooldown\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| liquidityCooldown | VARCHAR   |                                                              |             |

## 14. Table: AlgebraPool\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-06 01:31:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 43578588                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x11f0393aadf3805913f6291b8de777e878be8a5124a56764ff900b2c263bbed8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 160                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x479e1b71a702a595e19b6d5932cd5c863ab57ee0                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x02203f2351e7ac6ab5051205172d3f772db7d814                         |                                                              |
| owner             | VARCHAR   | 0x02203f2351e7ac6ab5051205172d3f772db7d814                         |                                                              |
| bottomTick        | VARCHAR   | -77940                                                             |                                                              |
| topTick           | VARCHAR   | -75900                                                             |                                                              |
| liquidityAmount   | VARCHAR   | 258383674619529115041177                                           |                                                              |
| amount0           | VARCHAR   | 571031244618168218107028                                           |                                                              |
| amount1           | VARCHAR   | 288318211035739760384                                              |                                                              |

## 15. Table: AlgebraPool\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-10 22:38:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 32946295                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc30ea82ae46d0cb1c4b0cd4fc7fa78a7bd2bb1303d646dc8aa69ff7851652d32 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 66                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbd09e295ff30d3f6a8860c38ec8062cc23b890bf                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xf5b509bb0909a69b1c207e495f687a596c168e12                         |                                                              |
| recipient         | VARCHAR   | 0xf5b509bb0909a69b1c207e495f687a596c168e12                         |                                                              |
| amount0           | VARCHAR   | -48909779048979889                                                 |                                                              |
| amount1           | VARCHAR   | 500000000000000000000                                              |                                                              |
| price             | VARCHAR   | 8098613012147076186292593774325                                    |                                                              |
| liquidity         | VARCHAR   | 225313214517610900732                                              |                                                              |
| tick              | VARCHAR   | 92546                                                              |                                                              |

## 16. Table: UniswapV2Factory\_event\_PairCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-26 20:26:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 21833847                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd685a2c7275c68b3b5e8baa7a8f9c121cd9e6446f6499e32c7574d242fa45532 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 40                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5757371414417b8c6caad45baef941abc7d3ab32                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0x0025de834f7d2da4b2f451d99832fa2973efc8fb                         |                                                              |
| token1            | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         |                                                              |
| pair              | VARCHAR   | 0xd59b98acf0789d5c7b7f5f679db4e4fa17059142                         |                                                              |
| \_uint            | VARCHAR   | 23398                                                              |                                                              |

## 17. Table: UniswapV2Pair\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-28 03:59:21+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 39792339                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xab5ca4580305de7c897510a1321c6bd7fcdbb0b9371edc2ca5cfa37ba7d0e0fb             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                              | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x727616964d4c44ce7f0bfbf6e0f5d2c73b1cf7a4                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x43b1cb5630578073cdcd0a13d8d522b142e799f8                                     |                                                              |
| spender           | VARCHAR   | 0x00c186906f72b254080c921b1d05ae596c95e6b1                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 18. Table: UniswapV2Pair\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-13 13:21:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 39246700                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x21715394fbcedfdfc4d05e9e94f7ac7c4fb4097ecbbcf5d2c3738f25eccb0b47 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 184                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00510ea3f8b883282d0cb497ff90f82a310fa962                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xa5e0829caced8ffdd4de3c43696c57f7d7a678ff                         |                                                              |
| amount0           | VARCHAR   | 225844753                                                          |                                                              |
| amount1           | VARCHAR   | 188994369981638285173436                                           |                                                              |
| to                | VARCHAR   | 0x29d6d6d84c9662486198667b5a9fbda3e698b23f                         |                                                              |

## 19. Table: UniswapV2Pair\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-03 22:25:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 24516863                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xae53a3cd62958d6f1b28e1a016244b0d8beba751ea99b763cad11793b122df4c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 283                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3f245c6f18442bd6198d964c567a01bd4202e290                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x04c4322ade51a67f3e34e6a0717a43907a2d94f9                         |                                                              |
| amount0           | VARCHAR   | 21052496286168400641                                               |                                                              |
| amount1           | VARCHAR   | 172398536528997036163                                              |                                                              |

## 20. Table: UniswapV2Pair\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-25 11:26:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 40749769                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x715456ca4f406c35e7dfb5607ea922e3bf98e4b71adea7de4d9a9187047f6ab6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 170                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb1f3555a7c3753ab4e6df1d66cfdb25477a36ce7                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x0000000000ccc3b6ccf20f086a1100f42d6fccc8                         |                                                              |
| amount0In         | VARCHAR   | 0                                                                  |                                                              |
| amount1In         | VARCHAR   | 2553744419405737356499                                             |                                                              |
| amount0Out        | VARCHAR   | 40355129                                                           |                                                              |
| amount1Out        | VARCHAR   | 0                                                                  |                                                              |
| to                | VARCHAR   | 0x0000000000ccc3b6ccf20f086a1100f42d6fccc8                         |                                                              |

## 21. Table: UniswapV2Pair\_event\_Sync\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-28 00:09:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 42037760                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf1d1904a5de1212d86aee4c14d40fe6c1971a2610afc63814174aab654200d5e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 92                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb6fbb59945c7dd8a1282c47a60fba77081c8cc2c                         | Address of the contract that produced the log                |
| reserve0          | VARCHAR   | 52533117028575802152077807                                         |                                                              |
| reserve1          | VARCHAR   | 15175993156974865116821                                            |                                                              |

## 22. Table: UniswapV2Pair\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-06 20:34:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12951186                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x82eebc3b6e754bed8b4ff6e98789e625d5fc834b20f5b66cbdcd112fdee6a4d9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 31                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2a574629ca405fa43a8f21faa64ff73dd320f45b                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x2a574629ca405fa43a8f21faa64ff73dd320f45b                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 167188109963076                                                    |                                                              |

## 23. Table: UniswapV2Router02\_call\_swapExactETHForTokens\_history

| Column             | Type      | Example                                                                               | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-05-05 04:57:11+00:00                                                             | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 27940347                                                                              | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x526ff475e005407c3de9bd5cd31c319468c14dbc071926834b3d58d6c800d608                    | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 0                                                                                     | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xa5e0829caced8ffdd4de3c43696c57f7d7a678ff                                            | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                     | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                  | Error in case input parsing failed                                                                                     |
| amountOutMin       | VARCHAR   | 35551224123739317685                                                                  |                                                                                                                        |
| path               | VARCHAR   | 0x0d500B1d8E8eF31E21C99d1Db9A6444d3ADf1270,0x146e58D34EaB0bFf7e0a63cfe9332908d680c667 |                                                                                                                        |
| to                 | VARCHAR   | 0xa7ad7ff576d3616d24745b70772678f205356850                                            |                                                                                                                        |
| deadline           | VARCHAR   | 3303454373                                                                            |                                                                                                                        |
