# stakewise

## 1. Table: Pool\_call\_stakeOnBehalf\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-03-27 23:29:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16921990                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xe5a3c79e5f02fd65627277eae1350759904772df62e6fac63ab3f5347edc78b1 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 57                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xc874b064f465bdd6411d45734b56fac750cda29a                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| recipient          | VARCHAR   | 0xe134971b6c87414007e0fd5abe2b6b8c339c5e91                         |                                                                                                                        |

## 2. Table: Pool\_call\_stakeWithPartnerOnBehalf\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| partner            | VARCHAR   |                                                                                                                        |             |
| recipient          | VARCHAR   |                                                                                                                        |             |

## 3. Table: Pool\_call\_stakeWithPartner\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| partner            | VARCHAR   |                                                                                                                        |             |

## 4. Table: Pool\_call\_stakeWithReferrerOnBehalf\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-06-07 13:50:11+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17428900                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x77cbb4fcb7937b6dc0a69a90dfbaf8e984dfd87f10b6145a360be9699bbe3a6a | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 48                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xc874b064f465bdd6411d45734b56fac750cda29a                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| referrer           | VARCHAR   | 0xeafbdfca5d8346f409b7c322c77692f89d061c78                         |                                                                                                                        |
| recipient          | VARCHAR   | 0xa6d258aa7f1db627dc0c560858b26a07f40ac9b1                         |                                                                                                                        |

## 5. Table: Pool\_call\_stakeWithReferrer\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-11-30 15:27:23+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16083689                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x894a40591a45571f84184c6e7176c5192c1f5df4e6a8de7f4572ece25fa59288 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 189                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xc874b064f465bdd6411d45734b56fac750cda29a                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| referrer           | VARCHAR   | 0xa7ec9b215a1047b60664345277a30be0491d4545                         |                                                                                                                        |

## 6. Table: Pool\_call\_stake\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-06-08 17:16:35+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17436994                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xb8306594c96e08d6ef268a59e0c7e7dc35a78b01c5e9b30e15f075eea5f37dea | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 116                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xc874b064f465bdd6411d45734b56fac750cda29a                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 7. Table: Pool\_event\_ActivatedValidatorsUpdated\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2023-08-06 19:41:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 17858065                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xcb8335e96ac7fe72d66ccc5f2e027dd6524a05a725767492bd79e5ad06cf7e91 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 356                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0xc874b064f465bdd6411d45734b56fac750cda29a                         | Address of the contract that produced the log                |
| activatedValidators | VARCHAR   | 2510                                                               |                                                              |
| sender              | VARCHAR   | 0x8a887282e67ff41d36c0b7537eab035291461acd                         |                                                              |

## 8. Table: Pool\_event\_Activated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-03 21:43:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12563994                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf031c0b6a7ac99a96f4afadc3388d2b422eedb761986312694e4a84d1969687a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 174                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc874b064f465bdd6411d45734b56fac750cda29a                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xfeaebb44cb843cb761c53952cd9bd1ab25977695                         |                                                              |
| validatorIndex    | VARCHAR   | 743                                                                |                                                              |
| value             | VARCHAR   | 93246382597580227175                                               |                                                              |
| sender            | VARCHAR   | 0xfeaebb44cb843cb761c53952cd9bd1ab25977695                         |                                                              |

## 9. Table: Pool\_event\_ActivationScheduled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-01 16:18:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14121136                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xae5b0a27c2c43daa01985a52b0ac8e8787f8178b1bf096a18e61897404234995 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 276                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc874b064f465bdd6411d45734b56fac750cda29a                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xd1b27ca830a9aecb65eadfe9634d4f1a8cd6edc2                         |                                                              |
| validatorIndex    | VARCHAR   | 1131                                                               |                                                              |
| value             | VARCHAR   | 35000000000000000000                                               |                                                              |

## 10. Table: Pool\_event\_MinActivatingDepositUpdated\_history

| Column               | Type      | Example                                                                        | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2022-03-25 12:13:06+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 14455360                                                                       | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x87d96c60fdff2e16a3adfd01b56147d59abc788bfee84aa37595d31edb5572dc             | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 502                                                                            | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0xc874b064f465bdd6411d45734b56fac750cda29a                                     | Address of the contract that produced the log                |
| minActivatingDeposit | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |
| sender               | VARCHAR   | 0x144a98cb1cdbb23610501fe6108858d9b7d24934                                     |                                                              |

## 11. Table: Pool\_event\_Paused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-18 17:47:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12659847                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x03885c141b0ecf91dce55ce350641114f6dcddff9554d98cd0c6501d037e2ffd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 231                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc874b064f465bdd6411d45734b56fac750cda29a                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x144a98cb1cdbb23610501fe6108858d9b7d24934                         |                                                              |

## 12. Table: Pool\_event\_PendingValidatorsLimitUpdated\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2021-03-23 12:31:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 12095149                                                           | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0xc4e4fa24cd90596953af269962b2d544c3b9fcf8119e7b6d4b20ab89186fee07 | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 291                                                                | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0xc874b064f465bdd6411d45734b56fac750cda29a                         | Address of the contract that produced the log                |
| pendingValidatorsLimit | VARCHAR   | 500                                                                |                                                              |
| sender                 | VARCHAR   | 0x144a98cb1cdbb23610501fe6108858d9b7d24934                         |                                                              |

## 13. Table: Pool\_event\_Refunded\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| sender            | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 14. Table: Pool\_event\_RoleAdminChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| role              | VARCHAR   |                                                              |             |
| previousAdminRole | VARCHAR   |                                                              |             |
| newAdminRole      | VARCHAR   |                                                              |             |

## 15. Table: Pool\_event\_RoleGranted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-25 17:52:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11726346                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6a1a1572c0fc21404b66626f1218d1b9341990257ac5bc5fa6a0506411dd5581 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 280                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc874b064f465bdd6411d45734b56fac750cda29a                         | Address of the contract that produced the log                |
| role              | VARCHAR   | 0x65d7a28e3265b37a6474929f336521b332c1681b933f6cb9f3376673440d862a |                                                              |
| account           | VARCHAR   | 0x144a98cb1cdbb23610501fe6108858d9b7d24934                         |                                                              |
| sender            | VARCHAR   | 0x1867c96601bc5fe24f685d112314b8f3fe228d5a                         |                                                              |

## 16. Table: Pool\_event\_RoleRevoked\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| role              | VARCHAR   |                                                              |             |
| account           | VARCHAR   |                                                              |             |
| sender            | VARCHAR   |                                                              |             |

## 17. Table: Pool\_event\_StakedWithPartner\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| partner           | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 18. Table: Pool\_event\_StakedWithReferrer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-18 12:46:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14609268                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x733d4f13e3f819012f914c2356c17c109292d09e04982b7381b1f0a36c4e98aa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 19                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc874b064f465bdd6411d45734b56fac750cda29a                         | Address of the contract that produced the log                |
| referrer          | VARCHAR   | 0xeafbdfca5d8346f409b7c322c77692f89d061c78                         |                                                              |
| amount            | VARCHAR   | 221784125576033117                                                 |                                                              |

## 19. Table: Pool\_event\_Unpaused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-05 17:03:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13946681                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xeaa63d71aee68329346897f1a2f0d29a761c190406db4fb457f3edd9110afaec | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 323                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc874b064f465bdd6411d45734b56fac750cda29a                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x144a98cb1cdbb23610501fe6108858d9b7d24934                         |                                                              |

## 20. Table: Pool\_event\_ValidatorRegistered\_history

| Column            | Type      | Example                                                                                            | Description                                                  |
| ----------------- | --------- | -------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-22 18:17:59+00:00                                                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17750404                                                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdca3c5298c20232d77421581ee822c427fc757bb52b594de7224a914c6a9976f                                 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 286                                                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc874b064f465bdd6411d45734b56fac750cda29a                                                         | Address of the contract that produced the log                |
| publicKey         | VARCHAR   | 0x831d2d8185ac57b32cfd2df7130887540b694b05845e472a705c0ef55962dd2a9cfb359a11bd1d1e93b900ad7f2ab935 |                                                              |
| operator          | VARCHAR   | 0x59ecf48345a221e0731e785ed79ed40d0a94e2a5                                                         |                                                              |

## 21. Table: RewardEthToken\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-06 07:24:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17854409                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa3745ec156b1b04c25cfb79ec10d369d9c70bb96da75e1b675cdee66531a563a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 87                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x20bc832ca081b91433ff6c17f85701b6e92486c5                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x24b32193cff0a68ecb3eb606d74d6358ca25d799                         |                                                              |
| spender           | VARCHAR   | 0xe592427a0aece92de3edee1f18e0157c05861564                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 22. Table: RewardEthToken\_event\_ProtocolFeeRecipientUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-06 14:01:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14532743                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8ee162082223ba86cf57431486bfae3069219cbbf399dc989d1e87bae07cc743 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 311                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x20bc832ca081b91433ff6c17f85701b6e92486c5                         | Address of the contract that produced the log                |
| recipient         | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 23. Table: RewardEthToken\_event\_ProtocolFeeUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| protocolFee       | VARCHAR   |                                                              |             |

## 24. Table: RewardEthToken\_event\_RewardsToggled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-30 20:13:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13716850                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x43a4241d11d5db44f5051d37c463589708d11b9e1a11555dc64f63b576cf3b3e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 449                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x20bc832ca081b91433ff6c17f85701b6e92486c5                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x992f534fcc87864875224d142d6bf054b1882160                         |                                                              |
| isDisabled        | VARCHAR   | true                                                               |                                                              |

## 25. Table: RewardEthToken\_event\_RewardsUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-25 00:59:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16901068                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0609108bb7c7a2b3048ba0b5e92757c13955d2e0bcb8baa6fa23ded36e306b5b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 258                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x20bc832ca081b91433ff6c17f85701b6e92486c5                         | Address of the contract that produced the log                |
| periodRewards     | VARCHAR   | 9392037255280017031                                                |                                                              |
| totalRewards      | VARCHAR   | 5246707694112598655282                                             |                                                              |
| rewardPerToken    | VARCHAR   | 109374451804580309                                                 |                                                              |
| distributorReward | VARCHAR   | 4112481162721261960                                                |                                                              |
| protocolReward    | VARCHAR   | 939203725528001703                                                 |                                                              |

## 26. Table: RewardEthToken\_event\_RoleAdminChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| role              | VARCHAR   |                                                              |             |
| previousAdminRole | VARCHAR   |                                                              |             |
| newAdminRole      | VARCHAR   |                                                              |             |

## 27. Table: RewardEthToken\_event\_RoleGranted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-25 17:52:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11726348                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8a32c9fbb2ed851edf6814f621b3f70a2983989c6bc0802aa575de874662ebaa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 198                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x20bc832ca081b91433ff6c17f85701b6e92486c5                         | Address of the contract that produced the log                |
| role              | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000 |                                                              |
| account           | VARCHAR   | 0x144a98cb1cdbb23610501fe6108858d9b7d24934                         |                                                              |
| sender            | VARCHAR   | 0x1867c96601bc5fe24f685d112314b8f3fe228d5a                         |                                                              |

## 28. Table: RewardEthToken\_event\_RoleRevoked\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| role              | VARCHAR   |                                                              |             |
| account           | VARCHAR   |                                                              |             |
| sender            | VARCHAR   |                                                              |             |

## 29. Table: RewardEthToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-13 23:59:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13019958                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4da6a9c334b5b8f61b51206840d1b0574aaec20e115b5e89094452d8d3ccd74f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 249                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x20bc832ca081b91433ff6c17f85701b6e92486c5                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x64667bd4fe5e1e0ee085a7c54c0822abf6ed0858                         |                                                              |
| value             | VARCHAR   | 303799998636518439                                                 |                                                              |

## 30. Table: RewardEthToken\_event\_Unpaused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-05 17:03:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13946681                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xeaa63d71aee68329346897f1a2f0d29a761c190406db4fb457f3edd9110afaec | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 326                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x20bc832ca081b91433ff6c17f85701b6e92486c5                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x144a98cb1cdbb23610501fe6108858d9b7d24934                         |                                                              |

## 31. Table: StakeWiseToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-26 08:48:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16053068                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3142b29758375e4f54bceaeebb441f3a7739bd77e4f1763a870e85e2749daf9b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x48c3399719b582dd63eb5aadf12a40b4c3f52fa2                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0d166b58f9c2862e3e0ddbeecd3eec791a40bc40                         |                                                              |
| to                | VARCHAR   | 0x15d12305d0f57c99d947e66d4164094ffccf78fc                         |                                                              |
| value             | VARCHAR   | 30009615308142614887841                                            |                                                              |

## 32. Table: StakedEthToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-01 20:00:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17388187                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x07a873ecb2b09898282fa9d9a7eeb10863dad0761feded93bbd9f10112de47fc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 540                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfe2e637202056d30016725477c5da089ab0a043a                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x9e687e8c9c5ac7b3799243d9ac0e523128f02902                         |                                                              |
| to                | VARCHAR   | 0xdadcf64babfb566785f1e9dfc4889c5e593dddc7                         |                                                              |
| value             | VARCHAR   | 466842477410063286                                                 |                                                              |
