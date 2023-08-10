# uniswap

## 1. Table: GovernorAlpha\_event\_VoteCast\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| voter             | VARCHAR   |                                                              |             |
| proposalId        | VARCHAR   |                                                              |             |
| support           | VARCHAR   |                                                              |             |
| votes             | VARCHAR   |                                                              |             |

## 2. Table: NonfungiblePositionManager\_event\_ApprovalForAll\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-22 15:36:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 38394026                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5906bbdd5f530aae1489f17259626ec6f9716fca9d6abd992c8c6063616b49f3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 139                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc36442b4a4522e871399cd717abdd847ab11fe88                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x8790590e4cf3fa9826fdf28f7ecfc19476bb4781                         |                                                              |
| operator          | VARCHAR   | 0x12adea6cfc72c42e879f8552ce4ac24ca0afea41                         |                                                              |
| approved          | VARCHAR   | false                                                              |                                                              |

## 3. Table: NonfungiblePositionManager\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-07 09:46:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 24651658                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x513982cf467214c2eb9778d71bfc2d2ff4e7d3c7ffd8f7be8be1052923213e1c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc36442b4a4522e871399cd717abdd847ab11fe88                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x29b146cdde52992973302e0535f4ef4f8ae707f9                         |                                                              |
| approved          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| tokenId           | VARCHAR   | 43777                                                              |                                                              |

## 4. Table: NonfungiblePositionManager\_event\_Collect\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-13 05:01:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 42641416                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb9f7821544a4eec91168e3f92f419978e579308dda94f655966495a258cdcc4b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 257                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc36442b4a4522e871399cd717abdd847ab11fe88                         | Address of the contract that produced the log                |
| tokenId           | VARCHAR   | 879587                                                             |                                                              |
| recipient         | VARCHAR   | 0x7870646d9a19e5a67da884eef32a6e69a61f0f7d                         |                                                              |
| amount0           | VARCHAR   | 2933                                                               |                                                              |
| amount1           | VARCHAR   | 687917994441430                                                    |                                                              |

## 5. Table: NonfungiblePositionManager\_event\_DecreaseLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-19 16:11:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 42900927                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbbef8aa242b9d8c58cd2c8138130a13c96df6026a62741cac65479e5f426bc60 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 512                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc36442b4a4522e871399cd717abdd847ab11fe88                         | Address of the contract that produced the log                |
| tokenId           | VARCHAR   | 879615                                                             |                                                              |
| liquidity         | VARCHAR   | 824520562076684                                                    |                                                              |
| amount0           | VARCHAR   | 873327674                                                          |                                                              |
| amount1           | VARCHAR   | 671504829286543729                                                 |                                                              |

## 6. Table: NonfungiblePositionManager\_event\_IncreaseLiquidity\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-22 12:39:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45382629                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x61fe6688f7d26ee5845e58ee7d91fdb8a7124f838c8dc229c015d24ee96285d3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc36442b4a4522e871399cd717abdd847ab11fe88                         | Address of the contract that produced the log                |
| tokenId           | VARCHAR   | 975879                                                             |                                                              |
| liquidity         | VARCHAR   | 252470205665021430546                                              |                                                              |
| amount0           | VARCHAR   | 2962441362344333733                                                |                                                              |
| amount1           | VARCHAR   | 2000000000000000000                                                |                                                              |

## 7. Table: NonfungiblePositionManager\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-13 11:06:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 31841240                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5f5716fdb88b3595c8dc8f3b7fe20f70748d4e05b0f50588868e1e4c99c20641 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc36442b4a4522e871399cd717abdd847ab11fe88                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x7c574171b57cd1d0b11b6e3536285b4275d6047d                         |                                                              |
| tokenId           | VARCHAR   | 235609                                                             |                                                              |

## 8. Table: NonfungibleTokenPositionDescriptor\_event\_UpdateTokenRatioPriority\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| token             | VARCHAR   |                                                              |             |
| priority          | VARCHAR   |                                                              |             |

## 9. Table: Uni\_event\_Approval\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| owner             | VARCHAR   |                                                              |             |
| spender           | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 10. Table: Uni\_event\_DelegateChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| delegator         | VARCHAR   |                                                              |             |
| fromDelegate      | VARCHAR   |                                                              |             |
| toDelegate        | VARCHAR   |                                                              |             |

## 11. Table: Uni\_event\_DelegateVotesChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| delegate          | VARCHAR   |                                                              |             |
| previousBalance   | VARCHAR   |                                                              |             |
| newBalance        | VARCHAR   |                                                              |             |

## 12. Table: Uni\_event\_MinterChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| minter            | VARCHAR   |                                                              |             |
| newMinter         | VARCHAR   |                                                              |             |

## 13. Table: Uni\_event\_Transfer\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| from              | VARCHAR   |                                                              |             |
| to                | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 14. Table: UniswapV2Factory\_event\_PairCreated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| token0            | VARCHAR   |                                                              |             |
| token1            | VARCHAR   |                                                              |             |
| pair              | VARCHAR   |                                                              |             |
| \_uint            | VARCHAR   |                                                              |             |

## 15. Table: UniswapV2Pair\_event\_Approval\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| owner             | VARCHAR   |                                                              |             |
| spender           | VARCHAR   |                                                              |             |
| value             | VARCHAR   |                                                              |             |

## 16. Table: UniswapV2Pair\_event\_Burn\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| sender            | VARCHAR   |                                                              |             |
| amount0           | VARCHAR   |                                                              |             |
| amount1           | VARCHAR   |                                                              |             |
| to                | VARCHAR   |                                                              |             |

## 17. Table: UniswapV2Pair\_event\_Mint\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| sender            | VARCHAR   |                                                              |             |
| amount0           | VARCHAR   |                                                              |             |
| amount1           | VARCHAR   |                                                              |             |

## 18. Table: UniswapV2Pair\_event\_Swap\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| sender            | VARCHAR   |                                                              |             |
| amount0In         | VARCHAR   |                                                              |             |
| amount1In         | VARCHAR   |                                                              |             |
| amount0Out        | VARCHAR   |                                                              |             |
| amount1Out        | VARCHAR   |                                                              |             |
| to                | VARCHAR   |                                                              |             |

## 19. Table: UniswapV2Pair\_event\_Sync\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| reserve0          | VARCHAR   |                                                              |             |
| reserve1          | VARCHAR   |                                                              |             |

## 20. Table: UniswapV2Pair\_event\_Transfer\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| from              | VARCHAR   |                                                              |             |
| to                | VARCHAR   |                                                              |             |
| value             | VARCHAR   |                                                              |             |

## 21. Table: UniswapV2Router02\_call\_swapExactETHForTokens\_history

| Column             | Type      | Example                                                                               | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-11-12 03:36:55+00:00                                                             | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 21268552                                                                              | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xba68a1f63da674270fef2d7e266c2ebe28ea492c422e212f1d8cbff3e008040a                    | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 76                                                                                    | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x7a250d5630b4cf539739df2c5dacb4c659f2488d                                            | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                     | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                  | Error in case input parsing failed                                                                                     |
| amountOutMin       | VARCHAR   | 446641074190961231                                                                    |                                                                                                                        |
| path               | VARCHAR   | 0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2,0x8B3192f5eEBD8579568A2Ed41E6FEB402f93f73F |                                                                                                                        |
| to                 | VARCHAR   | 0xa1069981268ccc52229a7c200445ad4693cd555c                                            |                                                                                                                        |
| deadline           | VARCHAR   | 1636689978                                                                            |                                                                                                                        |

## 22. Table: UniswapV3Factory\_event\_FeeAmountEnabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-20 17:39:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 22757547                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x45e77864249b0a388df4f98fc04203d6cd11ab6f1f4746cbf600d6055b376276 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 200                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1f98431c8ad98523631ae4a59f267346ea31f984                         | Address of the contract that produced the log                |
| fee               | VARCHAR   | 500                                                                |                                                              |
| tickSpacing       | VARCHAR   | 10                                                                 |                                                              |

## 23. Table: UniswapV3Factory\_event\_OwnerChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-20 17:39:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 22757547                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x45e77864249b0a388df4f98fc04203d6cd11ab6f1f4746cbf600d6055b376276 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 199                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1f98431c8ad98523631ae4a59f267346ea31f984                         | Address of the contract that produced the log                |
| oldOwner          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x6c9fc64a53c1b71fb3f9af64d1ae3a4931a5f4e9                         |                                                              |

## 24. Table: UniswapV3Factory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-12 23:20:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 27065945                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa8a6116ad64f45ecc469ee693fda34d2c886f30c8d1b0517a6a35eaefc3c631f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 121                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1f98431c8ad98523631ae4a59f267346ea31f984                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                         |                                                              |
| token1            | VARCHAR   | 0xc2132d05d31c914a87c6611c10748aeb04b58e8f                         |                                                              |
| fee               | VARCHAR   | 100                                                                |                                                              |
| tickSpacing       | VARCHAR   | 1                                                                  |                                                              |
| pool              | VARCHAR   | 0xdac8a8e6dbf8c690ec6815e0ff03491b2770255d                         |                                                              |

## 25. Table: UniswapV3Pool\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-06 19:44:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45990477                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd0cd50d4f07ea49ae3b61a83c99605a018951a59720b72e5825a5f9aceb89fca | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 384                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x017a7fda4d32cdeb5c66d813919eeb05bbe2d530                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xc36442b4a4522e871399cd717abdd847ab11fe88                         |                                                              |
| tickLower         | VARCHAR   | -200                                                               |                                                              |
| tickUpper         | VARCHAR   | 0                                                                  |                                                              |
| amount            | VARCHAR   | 656305605654626054732                                              |                                                              |
| amount0           | VARCHAR   | 0                                                                  |                                                              |
| amount1           | VARCHAR   | 6530025021564936716                                                |                                                              |

## 26. Table: UniswapV3Pool\_event\_CollectProtocol\_history

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

## 27. Table: UniswapV3Pool\_event\_Collect\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-06 17:23:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 37750105                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x521f612c5f0804f2d6e7400705eb6cc44083a328a6fc5897d5000d44c11dadcf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 372                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdac8a8e6dbf8c690ec6815e0ff03491b2770255d                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xc36442b4a4522e871399cd717abdd847ab11fe88                         |                                                              |
| recipient         | VARCHAR   | 0x1f86c9bff76bc12b7bfd10988e4796243b4f833a                         |                                                              |
| tickLower         | VARCHAR   | -3                                                                 |                                                              |
| tickUpper         | VARCHAR   | 2                                                                  |                                                              |
| amount0           | VARCHAR   | 4604                                                               |                                                              |
| amount1           | VARCHAR   | 2103706                                                            |                                                              |

## 28. Table: UniswapV3Pool\_event\_Flash\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-18 04:34:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 41659383                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc0c9edb482cd47c320fefa80c0ae5881445966824df3b49556904385d7e81266 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 189                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5645dcb64c059aa11212707fbf4e7f984440a8cf                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xd43d0bfafb74fc510a2a8253f6e57917d2951171                         |                                                              |
| recipient         | VARCHAR   | 0xd43d0bfafb74fc510a2a8253f6e57917d2951171                         |                                                              |
| amount0           | VARCHAR   | 2000000                                                            |                                                              |
| amount1           | VARCHAR   | 0                                                                  |                                                              |
| paid0             | VARCHAR   | 200                                                                |                                                              |
| paid1             | VARCHAR   | 0                                                                  |                                                              |

## 29. Table: UniswapV3Pool\_event\_IncreaseObservationCardinalityNext\_history

| Column                        | Type      | Example                                                            | Description                                                  |
| ----------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp              | TIMESTAMP | 2023-07-17 11:58:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number                 | INTEGER   | 45186096                                                           | The block number where this event was emitted                |
| transaction\_hash             | VARCHAR   | 0xeef1390cd16fff70182b9435c2d952335623bdb2bdf8b1c7798ee282a44ea6eb | Hash of the transactions in which this event was emitted     |
| log\_index                    | INTEGER   | 234                                                                | Integer of the log index position in the block of this event |
| contract\_address             | VARCHAR   | 0x3c61b4c0af70b6de7205bad8f63364ddd4f8ba5f                         | Address of the contract that produced the log                |
| observationCardinalityNextOld | VARCHAR   | 1                                                                  |                                                              |
| observationCardinalityNextNew | VARCHAR   | 30                                                                 |                                                              |

## 30. Table: UniswapV3Pool\_event\_Initialize\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-29 03:03:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 37403687                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5b9ef522163ef54a03d5d8e4977d85308bc545361492bbe40ff70d47c041fcaa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 257                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x51a14d3404523eb294d8732aeace95d256b8ed0b                         | Address of the contract that produced the log                |
| sqrtPriceX96      | VARCHAR   | 698746903083757944967918                                           |                                                              |
| tick              | VARCHAR   | -232783                                                            |                                                              |

## 31. Table: UniswapV3Pool\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-12 12:39:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 41445476                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x20703450c88f311f364f56eb9fe73ce64ccab54a660f33a35ca41672f66eb0d0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 243                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0260c206d80381445b38321361fe9ca0cf13190f                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xc36442b4a4522e871399cd717abdd847ab11fe88                         |                                                              |
| owner             | VARCHAR   | 0xc36442b4a4522e871399cd717abdd847ab11fe88                         |                                                              |
| tickLower         | VARCHAR   | 200                                                                |                                                              |
| tickUpper         | VARCHAR   | 14000                                                              |                                                              |
| amount            | VARCHAR   | 4856058511343738691                                                |                                                              |
| amount0           | VARCHAR   | 1000000000000000000                                                |                                                              |
| amount1           | VARCHAR   | 2007373431552208305                                                |                                                              |

## 32. Table: UniswapV3Pool\_event\_SetFeeProtocol\_history

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

## 33. Table: UniswapV3Pool\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-24 07:34:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 26297866                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa6e8e5400552b051ba60e2b12a737d381f3eba041c546bed4d54c776bcd79bf0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 195                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x52c27b0a548b39754953690f1eca54433fed548f                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xe592427a0aece92de3edee1f18e0157c05861564                         |                                                              |
| recipient         | VARCHAR   | 0x0000000000085a12481aedb59eb3200332aca597                         |                                                              |
| amount0           | VARCHAR   | -3297279800761691717926                                            |                                                              |
| amount1           | VARCHAR   | 56032710                                                           |                                                              |
| sqrtPriceX96      | VARCHAR   | 10361008177035391804782                                            |                                                              |
| liquidity         | VARCHAR   | 26072389271238101                                                  |                                                              |
| tick              | VARCHAR   | -317012                                                            |                                                              |

## 34. Table: Uniswap\_Dai\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| provider          | VARCHAR   |                                                              |             |
| eth\_amount       | VARCHAR   |                                                              |             |
| token\_amount     | VARCHAR   |                                                              |             |

## 35. Table: Uniswap\_Dai\_event\_EthPurchase\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| buyer             | VARCHAR   |                                                              |             |
| tokens\_sold      | VARCHAR   |                                                              |             |
| eth\_bought       | VARCHAR   |                                                              |             |

## 36. Table: Uniswap\_Dai\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| provider          | VARCHAR   |                                                              |             |
| eth\_amount       | VARCHAR   |                                                              |             |
| token\_amount     | VARCHAR   |                                                              |             |

## 37. Table: Uniswap\_Dai\_event\_TokenPurchase\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| buyer             | VARCHAR   |                                                              |             |
| eth\_sold         | VARCHAR   |                                                              |             |
| tokens\_bought    | VARCHAR   |                                                              |             |

## 38. Table: Uniswap\_event\_AddLiquidity\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| provider          | VARCHAR   |                                                              |             |
| eth\_amount       | VARCHAR   |                                                              |             |
| token\_amount     | VARCHAR   |                                                              |             |

## 39. Table: Uniswap\_event\_Approval\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_owner           | VARCHAR   |                                                              |             |
| \_spender         | VARCHAR   |                                                              |             |
| \_value           | VARCHAR   |                                                              |             |

## 40. Table: Uniswap\_event\_EthPurchase\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| buyer             | VARCHAR   |                                                              |             |
| tokens\_sold      | VARCHAR   |                                                              |             |
| eth\_bought       | VARCHAR   |                                                              |             |

## 41. Table: Uniswap\_event\_RemoveLiquidity\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| provider          | VARCHAR   |                                                              |             |
| eth\_amount       | VARCHAR   |                                                              |             |
| token\_amount     | VARCHAR   |                                                              |             |

## 42. Table: Uniswap\_event\_TokenPurchase\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| buyer             | VARCHAR   |                                                              |             |
| eth\_sold         | VARCHAR   |                                                              |             |
| tokens\_bought    | VARCHAR   |                                                              |             |

## 43. Table: Uniswap\_event\_Transfer\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_from            | VARCHAR   |                                                              |             |
| \_to              | VARCHAR   |                                                              |             |
| \_value           | VARCHAR   |                                                              |             |

## 44. Table: Vyper\_contract\_event\_NewExchange\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| token             | VARCHAR   |                                                              |             |
| exchange          | VARCHAR   |                                                              |             |
