# balancer

## 1. Table: V2\_BalancerPoolToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-02 07:06:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 34641461                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x94fb2999aad70b7f49705950f2ef5187c1876ec437dd15de5b8c40446b5bd611 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x045c5480131eef51aa1a74f34e62e7de23136f24                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x574375868f76f49a9eeeb6a5720b984298c216be                         |                                                              |
| to                | VARCHAR   | 0xb82e0d688a8b2c9c2219b9ca5c7776a16f3f65b2                         |                                                              |
| value             | VARCHAR   | 1337913620939525144254                                             |                                                              |

## 2. Table: V2\_MetaStablePoolFactory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-11 17:43:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 52358696                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3db22ef611ab75436e22b3e0960a961a422597755d5cfd22ade0848571395ef3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 9                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xebfd5681977e38af65a7487dc70b8221d089ccad                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0x36bf227d6bac96e2ab1ebb5492ecec69c691943f                         |                                                              |

## 3. Table: V2\_MetaStablePoolFactory\_event\_PoolCreated\_test\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| pool              | VARCHAR   |                                                              |             |

## 4. Table: V2\_MetaStablePool\_event\_AmpUpdateStarted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-11 17:43:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 52358696                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3db22ef611ab75436e22b3e0960a961a422597755d5cfd22ade0848571395ef3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x36bf227d6bac96e2ab1ebb5492ecec69c691943f                         | Address of the contract that produced the log                |
| startValue        | VARCHAR   | 50000                                                              |                                                              |
| endValue          | VARCHAR   | 50000                                                              |                                                              |
| startTime         | VARCHAR   | 1673459039                                                         |                                                              |
| endTime           | VARCHAR   | 1673459039                                                         |                                                              |

## 5. Table: V2\_MetaStablePool\_event\_AmpUpdateStopped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-11 17:43:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 52358696                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3db22ef611ab75436e22b3e0960a961a422597755d5cfd22ade0848571395ef3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x36bf227d6bac96e2ab1ebb5492ecec69c691943f                         | Address of the contract that produced the log                |
| currentValue      | VARCHAR   | 50000                                                              |                                                              |

## 6. Table: V2\_MetaStablePool\_event\_PriceRateCacheUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-04 08:53:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 57903851                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x55a4193e20c21e8d0da98bf1c5d6e61a98ddf69f3023ce3b4aaca24cd1384df6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x36bf227d6bac96e2ab1ebb5492ecec69c691943f                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x5979d7b546e38e414f7e9822514be443a4800529                         |                                                              |
| rate              | VARCHAR   | 1108106511566486344                                                |                                                              |

## 7. Table: V2\_MetaStablePool\_event\_SwapFeePercentageChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-07 19:21:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 23432109                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0ad3125d28557fda785d086c217fdf4079b53dd0f47a1d00bc2d39474469fba7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7bceaa9c5e7f4836fec3bce2d5346637c9b13970                         | Address of the contract that produced the log                |
| swapFeePercentage | VARCHAR   | 300000000000000                                                    |                                                              |

## 8. Table: V2\_ProtocolFeesCollector\_event\_FlashLoanFeePercentageChanged\_history

| Column                    | Type      | Example                                                      | Description |
| ------------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp          | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number             | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash         | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index                | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address         | VARCHAR   | Address of the contract that produced the log                |             |
| newFlashLoanFeePercentage | VARCHAR   |                                                              |             |

## 9. Table: V2\_ProtocolFeesCollector\_event\_SwapFeePercentageChanged\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2021-12-13 17:20:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 3825712                                                            | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x939a9caa396093603479b6096f412f250e0fdc4c5d84619b8942ae6b14fea585 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0xce88686553686da562ce7cea497ce749da109f9f                         | Address of the contract that produced the log                |
| newSwapFeePercentage | VARCHAR   | 100000000000000000                                                 |                                                              |

## 10. Table: V2\_StablePoolFactory\_event\_FactoryDisabled\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 11. Table: V2\_StablePoolFactory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-03 13:28:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 19285530                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc9d65b02bfb5c07c2948ddbcbad64e88253d5bce0e285bc246f686a5dd8982aa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xef44d6786b2b4d544b7850fe67ce6381626bf2d6                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0xd89746affa5483627a87e55713ec190511439495                         |                                                              |

## 12. Table: V2\_StablePool\_event\_AmpUpdateStarted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-11 17:43:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 52358696                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3db22ef611ab75436e22b3e0960a961a422597755d5cfd22ade0848571395ef3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x36bf227d6bac96e2ab1ebb5492ecec69c691943f                         | Address of the contract that produced the log                |
| startValue        | VARCHAR   | 50000                                                              |                                                              |
| endValue          | VARCHAR   | 50000                                                              |                                                              |
| startTime         | VARCHAR   | 1673459039                                                         |                                                              |
| endTime           | VARCHAR   | 1673459039                                                         |                                                              |

## 13. Table: V2\_StablePool\_event\_AmpUpdateStopped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-07 19:21:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 23432109                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0ad3125d28557fda785d086c217fdf4079b53dd0f47a1d00bc2d39474469fba7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7bceaa9c5e7f4836fec3bce2d5346637c9b13970                         | Address of the contract that produced the log                |
| currentValue      | VARCHAR   | 100000                                                             |                                                              |

## 14. Table: V2\_StablePool\_event\_SwapFeePercentageChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-07 17:34:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 23415617                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x767deb3b4b3350eb789e77e9b37187ada1bf813df1f11afc2818d9a118bae983 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xed420d58d6efa85d63926966cd1ec9eba4e57b11                         | Address of the contract that produced the log                |
| swapFeePercentage | VARCHAR   | 300000000000000                                                    |                                                              |

## 15. Table: V2\_Vault\_event\_AuthorizerChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-10 11:40:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 89245179                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3d4a472b436428674341b139c168d39023b76f4d5ca6b8ee07e44ba5a6eeea82 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                         | Address of the contract that produced the log                |
| newAuthorizer     | VARCHAR   | 0x6b1da720be2d11d95177ccfc40a917c2688f396c                         |                                                              |

## 16. Table: V2\_Vault\_event\_ExternalBalanceTransfer\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| token             | VARCHAR   |                                                              |             |
| sender            | VARCHAR   |                                                              |             |
| recipient         | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 17. Table: V2\_Vault\_event\_FlashLoan\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-15 08:45:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 38244945                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6c6c6f768504a459558b51548bbc2ccea19de288b7d470a8a14bde994899614f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 16                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                         | Address of the contract that produced the log                |
| recipient         | VARCHAR   | 0x05ac1261aa2cc8bf3630650b85a7c34da23a3140                         |                                                              |
| token             | VARCHAR   | 0xff970a61a04b1ca14834a43f5de4533ebddb5cc8                         |                                                              |
| amount            | VARCHAR   | 279081                                                             |                                                              |
| feeAmount         | VARCHAR   | 0                                                                  |                                                              |

## 18. Table: V2\_Vault\_event\_InternalBalanceChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-19 17:32:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 18037063                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe26aa435f002bc1a2e148fd674ed4bac34805a90482389d6ec7692fdbbd8720a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x751a0bc0e3f75b38e01cf25bfce7ff36de1c87de                         |                                                              |
| token             | VARCHAR   | 0x040d1edc9569d4bab2d15287dc5a4f10f56a56b8                         |                                                              |
| delta             | VARCHAR   | -2327576740000000000                                               |                                                              |

## 19. Table: V2\_Vault\_event\_PausedStateChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| paused            | VARCHAR   |                                                              |             |

## 20. Table: V2\_Vault\_event\_PoolBalanceChanged\_history

| Column             | Type      | Example                                                                                              | Description                                                  |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2023-04-12 07:51:35+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 79614319                                                                                             | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x02a2bf199e0d143c994df3b3d5b5b12adcf414a0da5388511c3fca3526e35f03                                   | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 2                                                                                                    | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                                                           | Address of the contract that produced the log                |
| poolId             | VARCHAR   | 0x64541216bafffeec8ea535bb71fbc927831d0595000100000000000000000002                                   |                                                              |
| liquidityProvider  | VARCHAR   | 0xc6c8a4c5d7a8f0173e6cefef154d08a3b2258675                                                           |                                                              |
| tokens             | VARCHAR   | 0x2f2a2543B76A4166549F7aaB2e75Bef0aefC5B0f,0x82aF49447D8a07e3bd95BD0d56f35241523fBab1,0xFF970A61A04b |                                                              |
| deltas             | VARCHAR   | 0,-4655613045995490,0                                                                                |                                                              |
| protocolFeeAmounts | VARCHAR   | 0,0,0                                                                                                |                                                              |

## 21. Table: V2\_Vault\_event\_PoolBalanceManaged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-10 12:06:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 68523885                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4a8831125a21e494b146d1482ea2fb724e0fcaa4e35500c566e6067b61e4a1da | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                         | Address of the contract that produced the log                |
| poolId            | VARCHAR   | 0x894c82800526e0391e709c0983a5aea3718b7f6d00000000000000000000034f |                                                              |
| assetManager      | VARCHAR   | 0x3bcebcc0d3b495cc68cd3949c791c622ba49a9a5                         |                                                              |
| token             | VARCHAR   | 0xfd086bc7cd5c481dcc9c85ebe478a1c0b69fcbb9                         |                                                              |
| cashDelta         | VARCHAR   | -142628783487                                                      |                                                              |
| managedDelta      | VARCHAR   | 142628783487                                                       |                                                              |

## 22. Table: V2\_Vault\_event\_PoolRegistered\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-06 11:20:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 67269953                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5ada5f872743384c643548451f11dbe47c3261a8e6abb4227c0b1eccba35fdf6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                         | Address of the contract that produced the log                |
| poolId            | VARCHAR   | 0x46804462f147ff96e9cafb20ca35a3b2600656df00020000000000000000038a |                                                              |
| poolAddress       | VARCHAR   | 0x46804462f147ff96e9cafb20ca35a3b2600656df                         |                                                              |
| specialization    | VARCHAR   | 2                                                                  |                                                              |

## 23. Table: V2\_Vault\_event\_RelayerApprovalChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-28 22:51:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 115917803                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3f437a41a42098b6a202dd2e7b99beb2711615ed68cfc7198d3e2da12b5ed2e6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                         | Address of the contract that produced the log                |
| relayer           | VARCHAR   | 0x598ce0f1ab64b27256759ef99d883ee51138b9bd                         |                                                              |
| sender            | VARCHAR   | 0x7d873fbfe8e16f5f55740a52a356c2f52c613cdf                         |                                                              |
| approved          | VARCHAR   | true                                                               |                                                              |

## 24. Table: V2\_Vault\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-21 06:44:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4850321                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x11cf7c05805c9c01d0a595ee026352dbe0106ebf9eadad6c1b13db6325e19689 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                         | Address of the contract that produced the log                |
| poolId            | VARCHAR   | 0xcc65a812ce382ab909a11e434dbf75b34f1cc59d000200000000000000000001 |                                                              |
| tokenIn           | VARCHAR   | 0x82af49447d8a07e3bd95bd0d56f35241523fbab1                         |                                                              |
| tokenOut          | VARCHAR   | 0x040d1edc9569d4bab2d15287dc5a4f10f56a56b8                         |                                                              |
| amountIn          | VARCHAR   | 6147992296045906993                                                |                                                              |
| amountOut         | VARCHAR   | 1273936185894860432634                                             |                                                              |

## 25. Table: V2\_Vault\_event\_TokensDeregistered\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| poolId            | VARCHAR   |                                                              |             |
| tokens            | VARCHAR   |                                                              |             |

## 26. Table: V2\_Vault\_event\_TokensRegistered\_history

| Column            | Type      | Example                                                                               | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-19 09:26:39+00:00                                                             | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 47282028                                                                              | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x27b70c93db452212d71ed992caa24f059a9c86f9a7596cc1f0ce4d985e2877af                    | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                                     | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                                            | Address of the contract that produced the log                |
| poolId            | VARCHAR   | 0x52fb2085b9ee49928435e9d11acf643858b563990002000000000000000002b6                    |                                                              |
| tokens            | VARCHAR   | 0x2f2a2543B76A4166549F7aaB2e75Bef0aefC5B0f,0x82aF49447D8a07e3bd95BD0d56f35241523fBab1 |                                                              |
| assetManagers     | VARCHAR   | 0x0000000000000000000000000000000000000000,0x0000000000000000000000000000000000000000 |                                                              |
