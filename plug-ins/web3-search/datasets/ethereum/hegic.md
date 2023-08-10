# hegic

## 1. Table: HegicERCPool\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-27 02:02:09+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11936544                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xddebe11e80ee8aebb4710dbe59856237bfc7bc1111556d62140787e9b619b790             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 82                                                                             | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x20dd9e22d22dd0a6ef74a520cb08303b5fad5de7                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x12b6966160c37660effb630320f5a3cd1fb808f5                                     |                                                              |
| spender           | VARCHAR   | 0x493134a9eabc8d2b5e08c5ab08e9d413fb4d1a55                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640563934831630065211510096026 |                                                              |

## 2. Table: HegicERCPool\_event\_Loss\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-04 19:54:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11791804                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x552bd0808c6e5bf53d8e72b57b816d5c5c28658fea7c7762c44f3125c28fecc4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 276                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x20dd9e22d22dd0a6ef74a520cb08303b5fad5de7                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 1307                                                               |                                                              |
| amount            | VARCHAR   | 243957                                                             |                                                              |

## 3. Table: HegicERCPool\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-10 19:33:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11029620                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xee36f6adf0087fba0f6a090507a41891402e16ba8424e06469f8c3951c019627 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 138                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x20dd9e22d22dd0a6ef74a520cb08303b5fad5de7                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x3961245db602ed7c03eeccda33ea3846bd8723bd                         |                                                              |

## 4. Table: HegicERCPool\_event\_Profit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-29 17:06:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11354872                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x414c7bc578a07e5cba57f0f28590f2f07ba07edfd273c31f9335dfa768d13478 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 31                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x20dd9e22d22dd0a6ef74a520cb08303b5fad5de7                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 683                                                                |                                                              |
| amount            | VARCHAR   | 4206                                                               |                                                              |

## 5. Table: HegicERCPool\_event\_Provide\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-16 23:45:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11069991                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3b3ea67b9ee1010b27016a3af56835898f7d640cc2fc08e5ffe055e50d158c7b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 118                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x20dd9e22d22dd0a6ef74a520cb08303b5fad5de7                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x036e0be744a12cf1d2c290e4447c920f7517a7d0                         |                                                              |
| amount            | VARCHAR   | 272500000                                                          |                                                              |
| writeAmount       | VARCHAR   | 2724780283159397391769                                             |                                                              |

## 6. Table: HegicERCPool\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-19 07:05:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11084984                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3201e745c5d1f6813e65195fa95d47f25b4965c5d14a550db92e08496e768277 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 173                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x20dd9e22d22dd0a6ef74a520cb08303b5fad5de7                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x535a129e2f69d85605f0598b69d0929636e71500                         |                                                              |
| value             | VARCHAR   | 81941403094103877339                                               |                                                              |

## 7. Table: HegicERCPool\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-27 06:14:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11534133                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1632a5c6b725b64c77413cd5e62f69f726915474efdb89256988ce564a7d7199 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 228                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x20dd9e22d22dd0a6ef74a520cb08303b5fad5de7                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x33f9df1e680a8f71a708ef6cef01cb87b2c41e04                         |                                                              |
| amount            | VARCHAR   | 185502                                                             |                                                              |
| writeAmount       | VARCHAR   | 2083400091745594589                                                |                                                              |

## 8. Table: HegicETHOptions\_event\_Create\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-16 22:04:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12448080                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x99abe1c5d634ed0950b059fa939799c7fa106b11d19b008edf90933734c6f83d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 164                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xefc0eeadc1132a12c9487d800112693bf49ecfa2                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 3432                                                               |                                                              |
| account           | VARCHAR   | 0x394844b29a26c892bd5aa9575c683f19233f2098                         |                                                              |
| settlementFee     | VARCHAR   | 50000000000000000                                                  |                                                              |
| totalFee          | VARCHAR   | 689350000000000000                                                 |                                                              |

## 9. Table: HegicETHOptions\_event\_Exercise\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-27 15:02:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11738540                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xab993f6b37996d1da36f9a29f2e3c9e45f1ae4d75b7b757622ece01e3cf312ed | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 240                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xefc0eeadc1132a12c9487d800112693bf49ecfa2                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 2668                                                               |                                                              |
| profit            | VARCHAR   | 540977667786243321                                                 |                                                              |

## 10. Table: HegicETHOptions\_event\_Expire\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-04 08:17:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11189554                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa41a79cd20e1c9ed8b67621d98b7dde00b81c4346abe01292d017b96658a20eb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 212                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xefc0eeadc1132a12c9487d800112693bf49ecfa2                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 328                                                                |                                                              |
| premium           | VARCHAR   | 1611500000000000                                                   |                                                              |

## 11. Table: HegicETHOptions\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-14 14:57:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11054458                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbb286096656d3a7109049bcc8e59526b0af314e809953ddc0a0413bd428b5010 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 40                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xefc0eeadc1132a12c9487d800112693bf49ecfa2                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x8ac7de95ff8d0ee72e0b54f781ab2e18f27108fb                         |                                                              |

## 12. Table: HegicETHPool\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-10 04:49:26+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11826705                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6617ac126d5eb26e07033a0d3ea230de7ba87bcbfb4377110ac37df35c91970c             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 199                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x878f15ffc8b894a1ba7647c7176e4c01f74e140b                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xb9b67fc388e5afb4bbde6990d7d79c5cdb1affde                                     |                                                              |
| spender           | VARCHAR   | 0x8fcaef0dbf40d36e5397ae1979c9075bf34c180e                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564038128755290923865857608 |                                                              |

## 13. Table: HegicETHPool\_event\_Loss\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-04 02:03:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11786957                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf261ea664af345359820d86a1bdb1980a48c960afa4f4c62cdb8689b50b87928 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 17                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x878f15ffc8b894a1ba7647c7176e4c01f74e140b                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 2346                                                               |                                                              |
| amount            | VARCHAR   | 672825951665340389                                                 |                                                              |

## 14. Table: HegicETHPool\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-14 14:50:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11054425                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x01168c28e37cc01389d6e300456ae9f1e5a2c9cde2ec00e9a35cc828678036f5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 338                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x878f15ffc8b894a1ba7647c7176e4c01f74e140b                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0xd7a157c4edb886a0296e32c5421ee1c65c1c363d                         |                                                              |
| newOwner          | VARCHAR   | 0x8ac7de95ff8d0ee72e0b54f781ab2e18f27108fb                         |                                                              |

## 15. Table: HegicETHPool\_event\_Profit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-09 23:33:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11421706                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaeb822e6484a00a6ef1e657231b5c756ca9e6c5ebed5ecc45d524210fd359c88 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 105                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x878f15ffc8b894a1ba7647c7176e4c01f74e140b                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 1579                                                               |                                                              |
| amount            | VARCHAR   | 407925000000000000                                                 |                                                              |

## 16. Table: HegicETHPool\_event\_Provide\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-14 01:37:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11050866                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0148ae88f8209d4c4e544e431a39f197e9fa4d8c04c57ca3c4aa48a5258bcb55 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 191                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x878f15ffc8b894a1ba7647c7176e4c01f74e140b                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x81c7bf1cf300e1b4f47b10b5c782e9a730aaf479                         |                                                              |
| amount            | VARCHAR   | 10000000000000000                                                  |                                                              |
| writeAmount       | VARCHAR   | 9993360818616768373                                                |                                                              |

## 17. Table: HegicETHPool\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-25 11:59:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12107956                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x114c3166650d669be2e587a02f951565a6d087a625e305dcae01de84e3f9c9bf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 225                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x878f15ffc8b894a1ba7647c7176e4c01f74e140b                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x8fcaef0dbf40d36e5397ae1979c9075bf34c180e                         |                                                              |
| to                | VARCHAR   | 0x66a3bd05e7ee207cb4688c56a4aa055708994ecf                         |                                                              |
| value             | VARCHAR   | 253376842702757000836                                              |                                                              |

## 18. Table: HegicETHPool\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-24 10:32:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11919299                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5c97ba2862809bbc6b77bc3dd0c2630f9cd3d569aaad2ebcfe9950c03e437f02 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 219                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x878f15ffc8b894a1ba7647c7176e4c01f74e140b                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xe09f694da87b33632bca61e825eb9e3f54e15170                         |                                                              |
| amount            | VARCHAR   | 10834393606321725036                                               |                                                              |
| writeAmount       | VARCHAR   | 12039832892907053076578                                            |                                                              |

## 19. Table: HegicStakingETH\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-09 18:11:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11224870                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0e481e5bcda7204d3689af8e866f04453983ae50ea4d7db5333c2c09931afe97 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 340                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1ef61e3e5676ec182eed6f052f8920fd49c7f69a                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x5a6c8d2194a0113ca127f4576f3292fcf7a4c48a                         |                                                              |
| spender           | VARCHAR   | 0x5a6c8d2194a0113ca127f4576f3292fcf7a4c48a                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 20. Table: HegicStakingETH\_event\_Claim\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-20 05:41:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12669426                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7d9629dd9b12bf124b83e1e7a0f57dae3a535228800231ca8ddb5f95baf2fe4d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 143                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1ef61e3e5676ec182eed6f052f8920fd49c7f69a                         | Address of the contract that produced the log                |
| acount            | VARCHAR   | 0xf4128b00afda933428056d0f0d1d7652af7e2b35                         |                                                              |
| amount            | VARCHAR   | 2419354838709677                                                   |                                                              |

## 21. Table: HegicStakingETH\_event\_Profit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-19 14:18:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11086924                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xabab86d51079bd084006f264126fa82472c617c630b3feb8c9f1ad5795e08c29 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 220                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1ef61e3e5676ec182eed6f052f8920fd49c7f69a                         | Address of the contract that produced the log                |
| amount            | VARCHAR   | 100000000000000000                                                 |                                                              |

## 22. Table: HegicStakingETH\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-21 18:17:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11700374                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7797ae98b49987535f4af6fd9462dfa7e6e38a48366979e7d96bf664712c39ae | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 74                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1ef61e3e5676ec182eed6f052f8920fd49c7f69a                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xe8478b603380e0094bbd307d62129b004a559476                         |                                                              |
| value             | VARCHAR   | 1                                                                  |                                                              |

## 23. Table: HegicStakingWBTC\_event\_Approval\_history

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

## 24. Table: HegicStakingWBTC\_event\_Claim\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-30 17:57:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11758747                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbda315b851002f9ecc71c75d4542cde024a49c1f65392490f1e5a1f921f7f423 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 123                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x840a1ae46b7364855206eb5b7286ab7e207e515b                         | Address of the contract that produced the log                |
| acount            | VARCHAR   | 0xb6445c82abe0695ba9b27b70381d62cbfe049e12                         |                                                              |
| amount            | VARCHAR   | 26409846                                                           |                                                              |

## 25. Table: HegicStakingWBTC\_event\_Profit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-14 18:37:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12239870                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0aca3ea60d99e42a745f1c0f86b099776ba56b876e4002c4cbefa9fa0bbe0895 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 224                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x840a1ae46b7364855206eb5b7286ab7e207e515b                         | Address of the contract that produced the log                |
| amount            | VARCHAR   | 250000                                                             |                                                              |

## 26. Table: HegicStakingWBTC\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-14 03:55:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11253524                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb1818dcddc8cb2abb28569f77cc0f8e29ef54794c063ee2afef255f18035eb3b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 157                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x840a1ae46b7364855206eb5b7286ab7e207e515b                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x93b220bc7c36ea8e4c64192301b680273a184ec3                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 1                                                                  |                                                              |

## 27. Table: HegicWBTCOptions\_event\_Create\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-10 00:07:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11226472                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfa6370e736ee943bdff7337693bab4f8cdec3409f0da33e4f5e06f9c67ce73c0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 317                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3961245db602ed7c03eeccda33ea3846bd8723bd                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 248                                                                |                                                              |
| account           | VARCHAR   | 0xa68119904fcb1072befe3692d5cdd29fdbeea5de                         |                                                              |
| settlementFee     | VARCHAR   | 10000                                                              |                                                              |
| totalFee          | VARCHAR   | 163413                                                             |                                                              |

## 28. Table: HegicWBTCOptions\_event\_Exercise\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-07 21:19:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12980352                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5cc1a2501b5090744859babe27e736be1ac129537920e67238b5072f4067e047 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 209                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3961245db602ed7c03eeccda33ea3846bd8723bd                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 1959                                                               |                                                              |
| profit            | VARCHAR   | 24146411                                                           |                                                              |

## 29. Table: HegicWBTCOptions\_event\_Expire\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-14 10:53:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11255395                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xedeb5815368f3a29c63e063c9bc292b3a2e85a475fc6d6e3a3c61b7cd8ec42d4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3961245db602ed7c03eeccda33ea3846bd8723bd                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 45                                                                 |                                                              |
| premium           | VARCHAR   | 4665000                                                            |                                                              |

## 30. Table: HegicWBTCOptions\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-10 19:33:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11029620                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xee36f6adf0087fba0f6a090507a41891402e16ba8424e06469f8c3951c019627 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 137                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3961245db602ed7c03eeccda33ea3846bd8723bd                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x8ac7de95ff8d0ee72e0b54f781ab2e18f27108fb                         |                                                              |
