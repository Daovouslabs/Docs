# fetchai

## 1. Table: Staking\_event\_BindStake\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2020-10-30 21:03:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 11160465                                                           | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0xc815e18972015295ee4709b157937b67ba002cd6bc2bfe0572df89e3d3c79cdf | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 253                                                                | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0x351bac612b50e87b46e4b10a282f632d41397de2                         | Address of the contract that produced the log                |
| stakerAddress          | VARCHAR   | 0x9c5d508c76dfc9b49c0debbb5cf2e859eed17cf1                         |                                                              |
| sinceInterestRateIndex | VARCHAR   | 0                                                                  |                                                              |
| principal              | VARCHAR   | 6197000000000000000000                                             |                                                              |
| compoundInterest       | VARCHAR   | 0                                                                  |                                                              |

## 2. Table: Staking\_event\_DeleteContract\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 3. Table: Staking\_event\_ExcessTokenWithdrawal\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| targetAddress     | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 4. Table: Staking\_event\_LiquidityDeposited\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-10 13:45:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12799993                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7da302b9576800732a55375e4df9b54b57a357ac94c120b985c613f96965436d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 77                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x351bac612b50e87b46e4b10a282f632d41397de2                         | Address of the contract that produced the log                |
| stakerAddress     | VARCHAR   | 0x05271853224d839a9bc6a342f27821e7fb32b001                         |                                                              |
| amount            | VARCHAR   | 76606000000000000000000                                            |                                                              |

## 5. Table: Staking\_event\_LiquidityUnlocked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-16 21:21:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12253546                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2edf6ea14021298aa48d6e1a6f4f1dcb5b523bbf8f6b6cf8867bc2ad6c536596 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 325                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x351bac612b50e87b46e4b10a282f632d41397de2                         | Address of the contract that produced the log                |
| stakerAddress     | VARCHAR   | 0x586157a6b845f7dbc63c76cd15462f3655ef9106                         |                                                              |
| principal         | VARCHAR   | 183538561505211132894242                                           |                                                              |
| compoundInterest  | VARCHAR   | 16461438494788867105758                                            |                                                              |

## 6. Table: Staking\_event\_LockPeriod\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-15 19:50:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12641059                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x85eb9987c55923b87f2543eb1d11e0aca99c3d973cb21dd4f126c276a5b75635 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 57                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x351bac612b50e87b46e4b10a282f632d41397de2                         | Address of the contract that produced the log                |
| numOfBlocks       | VARCHAR   | 45750                                                              |                                                              |

## 7. Table: Staking\_event\_NewInterestRate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-15 16:28:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11061460                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3efedb60fcba7663faf3662c62de56836a40b8299a7b1f93057173b3f50ce37d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 137                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x351bac612b50e87b46e4b10a282f632d41397de2                         | Address of the contract that produced the log                |
| index             | VARCHAR   | 0                                                                  |                                                              |
| rate              | VARCHAR   | 39803243689                                                        |                                                              |

## 8. Table: Staking\_event\_Pause\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-15 19:01:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11062171                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x97fbaacab0d5c802a17eec6525cdb34b19fcd8c9551a0a73bb89db6cb46cfe44 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x351bac612b50e87b46e4b10a282f632d41397de2                         | Address of the contract that produced the log                |
| sinceBlock        | VARCHAR   | 12231447                                                           |                                                              |

## 9. Table: Staking\_event\_RewardsPoolTokenTopUp\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-25 11:28:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12703013                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbdf0ebd2f85bebc4e8163055c906f4e13da28898d4699cfb887df5deac48d645 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 324                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x351bac612b50e87b46e4b10a282f632d41397de2                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x423d37bbc27ecbf678182875805f258ee0f7a18f                         |                                                              |
| amount            | VARCHAR   | 1000000000000000000000000                                          |                                                              |

## 10. Table: Staking\_event\_RewardsPoolTokenWithdrawal\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| targetAddress     | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 11. Table: Staking\_event\_RoleAdminChanged\_history

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

## 12. Table: Staking\_event\_RoleGranted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-15 16:28:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11061460                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3efedb60fcba7663faf3662c62de56836a40b8299a7b1f93057173b3f50ce37d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 135                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x351bac612b50e87b46e4b10a282f632d41397de2                         | Address of the contract that produced the log                |
| role              | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000 |                                                              |
| account           | VARCHAR   | 0xc2e109affd2fefd5b313350a4b2adc75ec2e96b1                         |                                                              |
| sender            | VARCHAR   | 0xc2e109affd2fefd5b313350a4b2adc75ec2e96b1                         |                                                              |

## 13. Table: Staking\_event\_RoleRevoked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-27 08:58:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13306864                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x01e7fdc70f0c16cff8f52e8246276531e0855335f48165e0b383b51e938a61d4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 306                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x351bac612b50e87b46e4b10a282f632d41397de2                         | Address of the contract that produced the log                |
| role              | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000 |                                                              |
| account           | VARCHAR   | 0x8400ac235ed4f139a3e05670a9a3c724e448129b                         |                                                              |
| sender            | VARCHAR   | 0x8400ac235ed4f139a3e05670a9a3c724e448129b                         |                                                              |

## 14. Table: Staking\_event\_StakeCompoundInterest\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2020-10-19 01:28:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 11083405                                                           | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0xb337ac84f6d1f9f6ff24b351574794928ea9776c2876d70a22fbdf20825de38a | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 156                                                                | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0x351bac612b50e87b46e4b10a282f632d41397de2                         | Address of the contract that produced the log                |
| stakerAddress          | VARCHAR   | 0x9791b60c72b872e1f6bc82fddc0fc3816058c7f1                         |                                                              |
| sinceInterestRateIndex | VARCHAR   | 0                                                                  |                                                              |
| principal              | VARCHAR   | 0                                                                  |                                                              |
| compoundInterest       | VARCHAR   | 0                                                                  |                                                              |

## 15. Table: Staking\_event\_TokenWithdrawal\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| targetAddress     | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 16. Table: Staking\_event\_UnbindStake\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-14 20:17:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12240291                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x18cdae1efc38ccda866d1bace534f81b47785cace1f1f66f5ebf7c502818b2ec | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 186                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x351bac612b50e87b46e4b10a282f632d41397de2                         | Address of the contract that produced the log                |
| stakerAddress     | VARCHAR   | 0xd9f37162a92a7195457b9cf7f51e40b76a9f9ce3                         |                                                              |
| liquidSinceBlock  | VARCHAR   | 12378058                                                           |                                                              |
| principal         | VARCHAR   | 9737247000344352613635                                             |                                                              |
| compoundInterest  | VARCHAR   | 348752999655647386365                                              |                                                              |

## 17. Table: Staking\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-09 07:14:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11417272                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe1fc22f541f675162e9edefd999af3e302f60266d311b81f5ae0e620cfb8459f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 274                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x351bac612b50e87b46e4b10a282f632d41397de2                         | Address of the contract that produced the log                |
| stakerAddress     | VARCHAR   | 0xe9c2c98e2433cdfa0dfb18bb17decc46f6b4f769                         |                                                              |
| principal         | VARCHAR   | 70212961626529164769452                                            |                                                              |
| compoundInterest  | VARCHAR   | 578038373470835230548                                              |                                                              |
