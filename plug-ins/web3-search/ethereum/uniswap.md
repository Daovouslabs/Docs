# uniswap

## 1. Table: GovernorAlpha\_event\_VoteCast\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-25 07:41:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11124291                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x142d9935f6d2455e91fbd81e7c044836351ff44b786644bb4e0263eca0980d76 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 161                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5e4be8bc9637f0eaa1a755019e06a68ce081d58f                         | Address of the contract that produced the log                |
| voter             | VARCHAR   | 0x13ecdfe02340b23ff482bc5e1bf781a95f1f6def                         |                                                              |
| proposalId        | VARCHAR   | 2                                                                  |                                                              |
| support           | VARCHAR   | true                                                               |                                                              |
| votes             | VARCHAR   | 27093891500675569543                                               |                                                              |

## 2. Table: NonfungiblePositionManager\_call\_Mint\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-09-27 00:46:49+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 13304741                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x07812f9876d17e8393cb15c30dd12aeee38f3f774dbde03426477705fa300197                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 306                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xc36442b4a4522e871399cd717abdd847ab11fe88                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| params             | VARCHAR   | 0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48,0xf3AE5d769e153Ef72b4e3591aC004E89F48107a1,10000,291400,3 |                                                                                                                        |

## 3. Table: NonfungiblePositionManager\_event\_ApprovalForAll\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-01 08:51:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17384890                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcbeb1582cf8a805badce5ce13d37142491ef0f02b032c43199651e25a6d17f5a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 241                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc36442b4a4522e871399cd717abdd847ab11fe88                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xb556a8ef8b172bc3408dcc165caa2c71f39341a5                         |                                                              |
| operator          | VARCHAR   | 0x00000000000111abe46ff893f3b2fdf1f759a8a8                         |                                                              |
| approved          | VARCHAR   | true                                                               |                                                              |

## 4. Table: NonfungiblePositionManager\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-02 00:29:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13724220                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb161080d55b6d9cdaef70b86bf3447e2436fb6df825fb4bc170af9fb49a2eb50 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 184                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc36442b4a4522e871399cd717abdd847ab11fe88                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x05e09d942505764bca4475abf8efdbc21d1c535b                         |                                                              |
| approved          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| tokenId           | VARCHAR   | 161433                                                             |                                                              |

## 5. Table: NonfungiblePositionManager\_event\_Collect\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-31 02:56:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14111092                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xccf70cc6077935c381ce01115a507eb6c71e6efd858b8fbbb2e2106ae8fc9b19 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 255                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc36442b4a4522e871399cd717abdd847ab11fe88                         | Address of the contract that produced the log                |
| tokenId           | VARCHAR   | 84494                                                              |                                                              |
| recipient         | VARCHAR   | 0x1143a839f6a37b0d08e2064bdc37d724c6571da3                         |                                                              |
| amount0           | VARCHAR   | 10618640286891985253                                               |                                                              |
| amount1           | VARCHAR   | 126181145                                                          |                                                              |

## 6. Table: NonfungiblePositionManager\_event\_DecreaseLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-07 21:42:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15698959                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x488cc986c23e4e431720e035941b5f27e19b65a98932cd75bb444c8d7ed9fe6c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc36442b4a4522e871399cd717abdd847ab11fe88                         | Address of the contract that produced the log                |
| tokenId           | VARCHAR   | 304048                                                             |                                                              |
| liquidity         | VARCHAR   | 1660543955184406                                                   |                                                              |
| amount0           | VARCHAR   | 1063394848496                                                      |                                                              |
| amount1           | VARCHAR   | 219930455629474946                                                 |                                                              |

## 7. Table: NonfungiblePositionManager\_event\_IncreaseLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-18 08:14:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13638181                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x92d949c6b33116085b18024fb7fa62003b3aba397ddebd7b55290473068d6d2f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 37                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc36442b4a4522e871399cd717abdd847ab11fe88                         | Address of the contract that produced the log                |
| tokenId           | VARCHAR   | 155490                                                             |                                                              |
| liquidity         | VARCHAR   | 61763146231311911810782                                            |                                                              |
| amount0           | VARCHAR   | 172692009006813698131626                                           |                                                              |
| amount1           | VARCHAR   | 0                                                                  |                                                              |

## 8. Table: NonfungiblePositionManager\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-04 12:36:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15275918                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc306bb6f3b5e05504e65f909f0ff7e6bc1dd34c8ea1d7fe7a441b88c65a4a047 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 33                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc36442b4a4522e871399cd717abdd847ab11fe88                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xa57bd00134b2850b2a1c55860c9e9ea100fdd6cf                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| tokenId           | VARCHAR   | 282513                                                             |                                                              |

## 9. Table: NonfungibleTokenPositionDescriptor\_event\_UpdateTokenRatioPriority\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| token             | VARCHAR   |                                                              |             |
| priority          | VARCHAR   |                                                              |             |

## 10. Table: Uni\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-02 12:12:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17827236                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6ee0a98c43cc7b9acfc4af2449ff9a55890ddfd18b341440a2bfd0a32f6cdda3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 408                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1f9840a85d5af5bf1d1762f925bdaddc4201f984                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x87f36ccbc1e0d70b3331c6f6a438fef87b8fc6d0                         |                                                              |
| spender           | VARCHAR   | 0x000000000022d473030f116ddee9f6b43ac78ba3                         |                                                              |
| amount            | VARCHAR   | 0                                                                  |                                                              |

## 11. Table: Uni\_event\_DelegateChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-13 02:47:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17248199                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0ebb561cef702df9dc364d1e8143ec429bfc099995bf5c16c402ee9805807de8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 197                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1f9840a85d5af5bf1d1762f925bdaddc4201f984                         | Address of the contract that produced the log                |
| delegator         | VARCHAR   | 0x76f780c336dac20a4a5e73677f98b6b3a78fbd86                         |                                                              |
| fromDelegate      | VARCHAR   | 0x8962285faac45a7cbc75380c484523bb7c32d429                         |                                                              |
| toDelegate        | VARCHAR   | 0x8962285faac45a7cbc75380c484523bb7c32d429                         |                                                              |

## 12. Table: Uni\_event\_DelegateVotesChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-05 07:56:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16760857                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9c7c2482db573dd161dcfece58f3573f369288471810b2f3a7fc65c524e38c3f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 516                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1f9840a85d5af5bf1d1762f925bdaddc4201f984                         | Address of the contract that produced the log                |
| delegate          | VARCHAR   | 0x6d8ab1cfbb9ffca2d27545ac8b6a84dcb4609486                         |                                                              |
| previousBalance   | VARCHAR   | 0                                                                  |                                                              |
| newBalance        | VARCHAR   | 1960901552008694019                                                |                                                              |

## 13. Table: Uni\_event\_MinterChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-14 18:11:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10861674                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4b37d2f343608457ca3322accdab2811c707acf3eb07a40dd8d9567093ea5b82 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 24                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1f9840a85d5af5bf1d1762f925bdaddc4201f984                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newMinter         | VARCHAR   | 0x41653c7d61609d856f29355e404f310ec4142cfb                         |                                                              |

## 14. Table: Uni\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-12 19:58:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16170858                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7bfd0eec30a8874a5c2527e4d8cdbf3a68f6d9adc1acd5445ad180d98d38da7a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 74                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1f9840a85d5af5bf1d1762f925bdaddc4201f984                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x01d0b1a17194ea29278d2ab02dcd4ecc27c4fcaa                         |                                                              |
| to                | VARCHAR   | 0x382ffce2287252f930e1c8dc9328dac5bf282ba1                         |                                                              |
| amount            | VARCHAR   | 111255917100000000                                                 |                                                              |

## 15. Table: UniswapV2Factory\_event\_PairCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-14 09:37:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11854041                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x76cb1325af58e5a9968c19295315fb8e63503a90fa6d4a5b9c15b60e05722ce7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 26                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5c69bee701ef814a2b6a3edd4b1652cb9cc5aa6f                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0x21ca39943e91d704678f5d00b6616650f066fd63                         |                                                              |
| token1            | VARCHAR   | 0x3832d2f059e55934220881f831be501d180671a7                         |                                                              |
| pair              | VARCHAR   | 0x0120137e1f0b2c022772c5cad1a53b3e77807b8f                         |                                                              |
| \_uint            | VARCHAR   | 29982                                                              |                                                              |

## 16. Table: UniswapV2Pair\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-29 01:49:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17795522                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3ead707bca945232557e07cb5e40e0e6fe28f81f2a3a74dd525cd91a187a6758 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 108                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x092b6a05b46db79e9b2a09925b546a05f170f97d                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xd710cb52d4a79e1c0b1629c956c032d93bd46e5a                         |                                                              |
| spender           | VARCHAR   | 0x0000000000000000000000000000000000000001                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 17. Table: UniswapV2Pair\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-24 11:30:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15817675                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd4331a75db4187d1af68af774151412c95e492454e8e72a76a54840cda0eee14 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x35c378d57e77da371272a786fb7c102079b2bf50                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x7a250d5630b4cf539739df2c5dacb4c659f2488d                         |                                                              |
| amount0           | VARCHAR   | 1061593518962305503                                                |                                                              |
| amount1           | VARCHAR   | 923304431963240093                                                 |                                                              |
| to                | VARCHAR   | 0xde2ff6cbf860acf8072feb52de7d41e5877ea0fe                         |                                                              |

## 18. Table: UniswapV2Pair\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-19 19:43:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12666751                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc513c893de397af2fb27976f0649f94c2786eaa06eebd20cd9fa999cf4ffb60f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 170                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6af1becb78701f5919adb6f6932965abe4547763                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x0720cd7232c925cd7f23009ae866a30d28504b74                         |                                                              |
| amount0           | VARCHAR   | 4426619590577139                                                   |                                                              |
| amount1           | VARCHAR   | 50000000000000                                                     |                                                              |

## 19. Table: UniswapV2Pair\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-02 16:22:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13147327                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9ccf641a222e1328b508fd423752008ae17399be80b3d421f36417c78615e647 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 73                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6ada49aeccf6e556bb7a35ef0119cc8ca795294a                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x000000000000006f6502b7f2bbac8c30a3f67e9a                         |                                                              |
| amount0In         | VARCHAR   | 0                                                                  |                                                              |
| amount1In         | VARCHAR   | 15999882101163819008                                               |                                                              |
| amount0Out        | VARCHAR   | 104061596643017833891572                                           |                                                              |
| amount1Out        | VARCHAR   | 0                                                                  |                                                              |
| to                | VARCHAR   | 0x000000000000006f6502b7f2bbac8c30a3f67e9a                         |                                                              |

## 20. Table: UniswapV2Pair\_event\_Sync\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-13 20:07:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15335424                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9bfca5498318b0c9114e8200aa8f26713c77be58a5bc9db37a397e1d08ac2eeb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 38                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3854612b93b140726167cca5418b01e832515d42                         | Address of the contract that produced the log                |
| reserve0          | VARCHAR   | 1355035116727631037154923                                          |                                                              |
| reserve1          | VARCHAR   | 1378595400315523882059                                             |                                                              |

## 21. Table: UniswapV2Pair\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-19 16:49:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12665971                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf94442abc7245ab2215a19ecbd72a1799e5b79dbe11283e42d5c80beb090d41c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 321                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00030110a7053083a7a160449a0e8f1adce9438d                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xb0b06d55c2fb4bbf4aa9b86f772807346ff7f181                         |                                                              |
| value             | VARCHAR   | 147174612902290685648                                              |                                                              |

## 22. Table: UniswapV2Router02\_call\_swapExactETHForTokens\_history

| Column             | Type      | Example                                                                               | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-09-17 19:46:59+00:00                                                             | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15555474                                                                              | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xe54cbdb29a86e8939ef64cbe89d3c3f2a8b08ebfc1ae24a6d3398e6842b567af                    | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 634                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x7a250d5630b4cf539739df2c5dacb4c659f2488d                                            | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                                     | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                  | Error in case input parsing failed                                                                                     |
| amountOutMin       | VARCHAR   | 120841128035608885564831806                                                           |                                                                                                                        |
| path               | VARCHAR   | 0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2,0x00C2999c8B2AdF4ABC835cc63209533973718eB1 |                                                                                                                        |
| to                 | VARCHAR   | 0x1701be5b892164c6d8443b76b59d9afb3ed522f6                                            |                                                                                                                        |
| deadline           | VARCHAR   | 1663444163                                                                            |                                                                                                                        |

## 23. Table: UniswapV3Factory\_event\_FeeAmountEnabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-13 01:15:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13604706                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5c84f89a67237db7500538b81af61ebd827c081302dd73a1c20c8f6efaaf4f3c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 352                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1f98431c8ad98523631ae4a59f267346ea31f984                         | Address of the contract that produced the log                |
| fee               | VARCHAR   | 100                                                                |                                                              |
| tickSpacing       | VARCHAR   | 1                                                                  |                                                              |

## 24. Table: UniswapV3Factory\_event\_OwnerChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-04 19:36:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12369662                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x05d1e9c2c48faf82547e00d527923f980576c5d337b6c666d0e91d07517c4b86 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 19                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1f98431c8ad98523631ae4a59f267346ea31f984                         | Address of the contract that produced the log                |
| oldOwner          | VARCHAR   | 0x6c9fc64a53c1b71fb3f9af64d1ae3a4931a5f4e9                         |                                                              |
| newOwner          | VARCHAR   | 0x1a9c8182c09f50c8318d769245bea52c32be35bc                         |                                                              |

## 25. Table: UniswapV3Factory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-15 09:41:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13619587                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x71d5e6f08ec9eec47eb3146bede5d698ed5a0f31fc79c6b94dda12d712fe7fec | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 119                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1f98431c8ad98523631ae4a59f267346ea31f984                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0x1a7e4e63778b4f12a199c062f3efdd288afcbce8                         |                                                              |
| token1            | VARCHAR   | 0x853d955acef822db058eb8505911ed77f175b99e                         |                                                              |
| fee               | VARCHAR   | 500                                                                |                                                              |
| tickSpacing       | VARCHAR   | 10                                                                 |                                                              |
| pool              | VARCHAR   | 0x8ce5796ef6b0c5918025bcf4f9ca908201b030b3                         |                                                              |

## 26. Table: UniswapV3Pool\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-13 06:06:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13015090                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5d647aadda93259c8d2ef8535a149f77902f74d85e4cfc37957607d137cbd662 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 238                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00cef0386ed94d738c8f8a74e8bfd0376926d24c                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xc36442b4a4522e871399cd717abdd847ab11fe88                         |                                                              |
| tickLower         | VARCHAR   | -276330                                                            |                                                              |
| tickUpper         | VARCHAR   | -276320                                                            |                                                              |
| amount            | VARCHAR   | 0                                                                  |                                                              |
| amount0           | VARCHAR   | 0                                                                  |                                                              |
| amount1           | VARCHAR   | 0                                                                  |                                                              |

## 27. Table: UniswapV3Pool\_event\_CollectProtocol\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| sender            | VARCHAR   |                                                              |             |
| recipient         | VARCHAR   |                                                              |             |
| amount0           | VARCHAR   |                                                              |             |
| amount1           | VARCHAR   |                                                              |             |

## 28. Table: UniswapV3Pool\_event\_Collect\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-28 06:28:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14292993                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd50d8b8d0644e0b8da2a39fd3bea12bec6fcca5b80c366062978af47d4268dcd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 115                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9496d107a4b90c7d18c703e8685167f90ac273b0                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x26c2251801d2cfb5461751c984dc3eaa358bdf0f                         |                                                              |
| recipient         | VARCHAR   | 0x26c2251801d2cfb5461751c984dc3eaa358bdf0f                         |                                                              |
| tickLower         | VARCHAR   | -96120                                                             |                                                              |
| tickUpper         | VARCHAR   | -69000                                                             |                                                              |
| amount0           | VARCHAR   | 4055603982130263418708501                                          |                                                              |
| amount1           | VARCHAR   | 3024711487219485744907                                             |                                                              |

## 29. Table: UniswapV3Pool\_event\_Flash\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-11 21:10:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16164064                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x759fb0ba02e8cd0e9ff832941673242e5ef9279c8635bf33965694bff3618cdb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 26                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x88e6a0c2ddd26feeb64f039a2c41296fcb3f5640                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x775c559d9a48ce5a8444c1035c3a8921ab477b8e                         |                                                              |
| recipient         | VARCHAR   | 0x775c559d9a48ce5a8444c1035c3a8921ab477b8e                         |                                                              |
| amount0           | VARCHAR   | 0                                                                  |                                                              |
| amount1           | VARCHAR   | 82522875476194074                                                  |                                                              |
| paid0             | VARCHAR   | 0                                                                  |                                                              |
| paid1             | VARCHAR   | 41261437738098                                                     |                                                              |

## 30. Table: UniswapV3Pool\_event\_IncreaseObservationCardinalityNext\_history

| Column                        | Type      | Example                                                            | Description                                                  |
| ----------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp              | TIMESTAMP | 2022-08-22 23:34:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number                 | INTEGER   | 15393188                                                           | The block number where this event was emitted                |
| transaction\_hash             | VARCHAR   | 0xca111836d0c479bdaed6f5a2b3bfd6ffc5cfa3405e65ca78cc9c3fbd3d2f4cc2 | Hash of the transactions in which this event was emitted     |
| log\_index                    | INTEGER   | 204                                                                | Integer of the log index position in the block of this event |
| contract\_address             | VARCHAR   | 0x742b20bc4e98e457a6e827ce89f50636a938200d                         | Address of the contract that produced the log                |
| observationCardinalityNextOld | VARCHAR   | 1                                                                  |                                                              |
| observationCardinalityNextNew | VARCHAR   | 200                                                                |                                                              |

## 31. Table: UniswapV3Pool\_event\_Initialize\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-25 11:06:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17769701                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd38f1dfde46a577afbefc78c61bfdde23a46b626586398fc165c5aabbb9d1030 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 466                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd69be32f445cf4ae05a3ebfe74dc94fa8872bf99                         | Address of the contract that produced the log                |
| sqrtPriceX96      | VARCHAR   | 25054131037751093162929900172930                                   |                                                              |
| tick              | VARCHAR   | 115135                                                             |                                                              |

## 32. Table: UniswapV3Pool\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-18 07:29:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17072098                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x206fe09dda21f754c9c94aca568b40097fa9f5608a03bcc1cc204f87d3a083ff | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 179                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x020c349a0541d76c16f501abc6b2e9c98adae892                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x3cd02fe9e114611c82f0eb147c74d7b463997d1e                         |                                                              |
| owner             | VARCHAR   | 0x3cd02fe9e114611c82f0eb147c74d7b463997d1e                         |                                                              |
| tickLower         | VARCHAR   | 263400                                                             |                                                              |
| tickUpper         | VARCHAR   | 267800                                                             |                                                              |
| amount            | VARCHAR   | 2913421557903560                                                   |                                                              |
| amount0           | VARCHAR   | 526646837                                                          |                                                              |
| amount1           | VARCHAR   | 174826447066997849954                                              |                                                              |

## 33. Table: UniswapV3Pool\_event\_SetFeeProtocol\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| feeProtocol0Old   | VARCHAR   |                                                              |             |
| feeProtocol1Old   | VARCHAR   |                                                              |             |
| feeProtocol0New   | VARCHAR   |                                                              |             |
| feeProtocol1New   | VARCHAR   |                                                              |             |

## 34. Table: UniswapV3Pool\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-03 07:51:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15464144                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc1c61c8b607c4d4ff888f7998f7d4a3a2844d2914915827ba99d385df28b7e78 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 33                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x298b7c5e0770d151e4c5cf6cca4dae3a3ffc8e27                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x0000000000007f150bd6f54c40a34d7c3d5e9f56                         |                                                              |
| recipient         | VARCHAR   | 0x0000000000007f150bd6f54c40a34d7c3d5e9f56                         |                                                              |
| amount0           | VARCHAR   | 1124719109767693860864                                             |                                                              |
| amount1           | VARCHAR   | -1121761483                                                        |                                                              |
| sqrtPriceX96      | VARCHAR   | 79142856987159422402362                                            |                                                              |
| liquidity         | VARCHAR   | 52040837913240528660                                               |                                                              |
| tick              | VARCHAR   | -276346                                                            |                                                              |

## 35. Table: Uniswap\_Dai\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-02-03 14:36:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7168842                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe726328f7144860a40cdefb0e4157944018a0b00f7128a01134462bc8f83b4e4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 12                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x09cabec1ead1c0ba254b09efb3ee13841712be14                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xfda94e88b2fc3b8527557a158d69ba87b53395de                         |                                                              |
| eth\_amount       | VARCHAR   | 49934242400000000000                                               |                                                              |
| token\_amount     | VARCHAR   | 5416499997337683570477                                             |                                                              |

## 36. Table: Uniswap\_Dai\_event\_EthPurchase\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-02-29 21:33:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9581153                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x528784e67bf47e1019fbd48555096e646628ed1307e1785db18abe5e498e93f5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x09cabec1ead1c0ba254b09efb3ee13841712be14                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x00000000b1786c9698c160d78232c78d6f6474fe                         |                                                              |
| tokens\_sold      | VARCHAR   | 8307990608031945631807                                             |                                                              |
| eth\_bought       | VARCHAR   | 38288366038178705517                                               |                                                              |

## 37. Table: Uniswap\_Dai\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-05-05 12:05:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7700799                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6beffa0e6c196677eb43639f9672a55a3a41ca652ab4dafbdc13527673d06e8b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 48                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x09cabec1ead1c0ba254b09efb3ee13841712be14                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x7c8216425421548e19bb90d7d4295a1ef77a8195                         |                                                              |
| eth\_amount       | VARCHAR   | 1045250354485313554                                                |                                                              |
| token\_amount     | VARCHAR   | 169999999999999992297                                              |                                                              |

## 38. Table: Uniswap\_Dai\_event\_TokenPurchase\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-05-01 19:18:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7677044                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe360c603584782f30f4b4957ffbaf5ae685dc752f759f6f05c561e1e8aaa1686 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 16                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x09cabec1ead1c0ba254b09efb3ee13841712be14                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x00000000aca7ba47149da8a2f0ce02d140ecfa12                         |                                                              |
| eth\_sold         | VARCHAR   | 4512610853430702592                                                |                                                              |
| tokens\_bought    | VARCHAR   | 730352769287459177244                                              |                                                              |

## 39. Table: Uniswap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-16 14:35:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10471095                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6557ed91e6fbcb7953abc23beda79b09e61e169502adcdc2dfa266f21f297da2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 114                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x042dbbdc27f75d277c3d99efe327db21bc4fde75                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0x2d0b0664d55ddc851561678bbe97d538ae78ed72                         |                                                              |
| eth\_amount       | VARCHAR   | 3376219657104671994                                                |                                                              |
| token\_amount     | VARCHAR   | 419434424477                                                       |                                                              |

## 40. Table: Uniswap\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-12 14:31:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11438678                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xed740d6a84a78e71fbd3a3afd03df2dcf0c3e9cbdcc3c9dcc34d7e7ad06779ed | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 147                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe9cf7887b93150d4f2da7dfc6d502b216438f244                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0xd2d7d0c9716237b7cefe5013947a02f0356e0590                         |                                                              |
| \_spender         | VARCHAR   | 0x48d7f315fedcad332f68aafa017c7c158bc54760                         |                                                              |
| \_value           | VARCHAR   | 100000000000000000000000000                                        |                                                              |

## 41. Table: Uniswap\_event\_EthPurchase\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-04 19:19:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16113484                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0d76a78afbf33e984143ce6ff5e209274ff3414bee5a796bdbd2628327da1c31 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 15                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2a1530c4c41db0b0b2bb646cb5eb1a67b7158667                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x0000000000a84d1a9b0063a910315c7ffa9cd248                         |                                                              |
| tokens\_sold      | VARCHAR   | 730202525498611987522                                              |                                                              |
| eth\_bought       | VARCHAR   | 571225826826880502                                                 |                                                              |

## 42. Table: Uniswap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-12-10 02:26:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6858265                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfe97edb229e228b6df770604787628b3ab953908f70189987e3648866cc0a1bc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 64                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x701564aa6e26816147d4fa211a0779f1b774bb9b                         | Address of the contract that produced the log                |
| provider          | VARCHAR   | 0xb86bb5fc804768db34f1a37da8b719e19af9dffd                         |                                                              |
| eth\_amount       | VARCHAR   | 9860498528998177554                                                |                                                              |
| token\_amount     | VARCHAR   | 405783171499                                                       |                                                              |

## 43. Table: Uniswap\_event\_TokenPurchase\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-08 18:29:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7032624                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x62a770c28c9a56c9b2e8a1917a8b8affbfe2e48e1dd845791086b4e9ef228150 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 19                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x069c97dba948175d10af4b2414969e0b88d44669                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xa96dbfd3ef810dd8d13c330a3881e7e9c2aeb6dd                         |                                                              |
| eth\_sold         | VARCHAR   | 494435947368958358                                                 |                                                              |
| tokens\_bought    | VARCHAR   | 993682451704416606935                                              |                                                              |

## 44. Table: Uniswap\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-11-25 12:03:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6769909                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x23cf17d88883695ddba9b0c722e721267f9b151243aa0bba5a942c4b77349e9b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 17                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4e395304655f0796bc3bc63709db72173b9ddf98                         | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_to              | VARCHAR   | 0x395d48020ef5e29168706e16258db6c6c4d7d317                         |                                                              |
| \_value           | VARCHAR   | 538663812024418037                                                 |                                                              |

## 45. Table: Vyper\_contract\_event\_NewExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-04-09 10:35:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7533406                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6f16b3e4241406f5cbbd49fab7cb7dda118843e6720c3ec9cb623c51bcfa836d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 38                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc0a47dfe034b400b47bdad5fecda2621de6c4d95                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x9a8c04e6166c553dc01dd8f36b78904833baeb57                         |                                                              |
| exchange          | VARCHAR   | 0x269cac915ef69d9920a48fd2dc3df5dc5941a779                         |                                                              |
