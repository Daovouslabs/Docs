# tornado

## 1. Table: ERC20Tornado\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-29 20:18:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14102775                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbcee937bc9eb9bb5fa2e7f9ba163b9ad077509cd70576f9aec2414a719a0e301 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 36                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x07687e702b410fa43f4cb4af7fa097918ffd2730                         | Address of the contract that produced the log                |
| commitment        | VARCHAR   | 0x0d2442ef105089608485263a7f03b1b340deac3dca8d6cf39100503968bb34f9 |                                                              |
| leafIndex         | VARCHAR   | 1717                                                               |                                                              |
| timestamp         | VARCHAR   | 1643487510                                                         |                                                              |

## 2. Table: ERC20Tornado\_event\_Withdrawal\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-07 12:05:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13958233                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf3fcb447c52a3c25031d78eb9d95cee7f044c0f6a791dee740f934c2a8f57a0d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 49                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x610b717796ad172b316836ac95a2ffad065ceab4                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0x4ccfd88f9b0862431c7b1a1411b5836330be76a7                         |                                                              |
| nullifierHash     | VARCHAR   | 0x09624f5b980676755d659b223f6610ef3a00345777088bd3ec3c19152ea1e833 |                                                              |
| relayer           | VARCHAR   | 0x4ccfd88f9b0862431c7b1a1411b5836330be76a7                         |                                                              |
| fee               | VARCHAR   | 0                                                                  |                                                              |

## 3. Table: TornadoCash\_Eth\_01\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-02 02:02:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16538015                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4c1edcb014ceab72262d9a1d84b9d80a664b038d46876150fc6cf7819b856c4e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 101                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x12d66f87a04a9e220743712ce6d9bb1b5616b8fc                         | Address of the contract that produced the log                |
| commitment        | VARCHAR   | 0x2acf809ad7e3d543bcd4a32c0826e33521cbaf3c70b5a0d783af0141c63747df |                                                              |
| leafIndex         | VARCHAR   | 26956                                                              |                                                              |
| timestamp         | VARCHAR   | 1675303379                                                         |                                                              |

## 4. Table: TornadoCash\_Eth\_01\_event\_Withdrawal\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-27 17:05:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17785779                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaf31030c0965dace7151e142d520ae43fb9e2c99f52842fbbef67ce00d1c1051 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 122                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x12d66f87a04a9e220743712ce6d9bb1b5616b8fc                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0x00c8a3dcc18b7d8fce1ad1288b0eeaf3c4793d76                         |                                                              |
| nullifierHash     | VARCHAR   | 0x10227a8d20ac1a7b9b04efa6a28d29ba88369efac0fecf34f038c66e800ceb6c |                                                              |
| relayer           | VARCHAR   | 0xab1723831396351f759d0c8787e5ddaa18f5424c                         |                                                              |
| fee               | VARCHAR   | 42588747683650000                                                  |                                                              |

## 5. Table: TornadoCash\_erc20\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-19 11:39:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10489713                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x81b238107950748ecd026bcacbfb3c60f71006ee16358c8fdd580e0e03b8fc7b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 88                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfd8610d20aa15b7b2e3be39b396a1bc3516c7144                         | Address of the contract that produced the log                |
| commitment        | VARCHAR   | 0x15d9e29ee4ccaff538b466453df3f2d6a5e62099b4653fe6da02b192d912aaaf |                                                              |
| leafIndex         | VARCHAR   | 103                                                                |                                                              |
| timestamp         | VARCHAR   | 1595158761                                                         |                                                              |

## 6. Table: TornadoCash\_erc20\_event\_Withdrawal\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-23 01:21:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10512694                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9f5917b5cdb0b56e7168268b0af484faf5ecd421eed05dcbd15800eed85134c1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 192                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x169ad27a470d064dede56a2d3ff727986b15d52b                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0xbc44acb59444460108fc353ff578d8509fbfb9ff                         |                                                              |
| nullifierHash     | VARCHAR   | 0x0995f522c1663edca452db20cbe5d7f9772c8c751645763271e59c797b09c0ad |                                                              |
| relayer           | VARCHAR   | 0x7d3bb46c78b0c4949639ce34896bfd875b97ad08                         |                                                              |
| fee               | VARCHAR   | 15792817                                                           |                                                              |

## 7. Table: TornadoCash\_eth\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-18 18:47:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10685718                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3417cdd1caccdfbd514dcd0e8997307503dcb4987c0f4adf6aaf839b629f469b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 192                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x47ce0c6ed5b0ce3d3a51fdb1c52dc66a7c3c2936                         | Address of the contract that produced the log                |
| commitment        | VARCHAR   | 0x036842bece24f858cc11d65d50f5ab3ffebc2956a88d2c1b766057193ffb67d6 |                                                              |
| leafIndex         | VARCHAR   | 2731                                                               |                                                              |
| timestamp         | VARCHAR   | 1597776421                                                         |                                                              |

## 8. Table: TornadoCash\_eth\_event\_Withdrawal\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-30 07:01:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12733892                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf2d60e1dc2e6dc761ba2d9dda33ee20be52b417330eb27a87b9814cc286d8423 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 154                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x910cbd523d972eb0a6f4cae4618ad62622b39dbf                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0x62de427f1ba71afdf975552e06fa416f9832ee9b                         |                                                              |
| nullifierHash     | VARCHAR   | 0x138374e7e20dd6a4b3ade075833d12e8f1480f2257333d3cc426ffa49b306352 |                                                              |
| relayer           | VARCHAR   | 0x009610ae32d286d134ac048ca15ff1dd271dcacf                         |                                                              |
| fee               | VARCHAR   | 10620000000000000                                                  |                                                              |

## 9. Table: TornadoCash\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-10 03:12:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17660521                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xca196406f9b7ea84e02bcee2aa7477b0073fefb29ea006f818145cadde2a9f6d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x910cbd523d972eb0a6f4cae4618ad62622b39dbf                         | Address of the contract that produced the log                |
| commitment        | VARCHAR   | 0x1cc6ac0a6b685716fca4ac97167e850752115238e6fe4136dbe8bf3592f126c1 |                                                              |
| leafIndex         | VARCHAR   | 48585                                                              |                                                              |
| timestamp         | VARCHAR   | 1688958779                                                         |                                                              |

## 10. Table: TornadoCash\_event\_Withdrawal\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-27 11:55:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17350226                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x83b381edc3701a1d30db764830492cf7d7f5c05ec767cd7437ac2602f495a09d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 127                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x910cbd523d972eb0a6f4cae4618ad62622b39dbf                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0xf5980573aba1e731714b28ef20ef0b4d84f85525                         |                                                              |
| nullifierHash     | VARCHAR   | 0x2735bc189ebd411a5d484f99aa2b43eea423ddf2ec78806a9b385b8c835c861b |                                                              |
| relayer           | VARCHAR   | 0x36989535f0290eac96692675cbf15a3bd2f42e46                         |                                                              |
| fee               | VARCHAR   | 52210905468200000                                                  |                                                              |

## 11. Table: TornadoProxy\_event\_EncryptedNote\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-19 08:43:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14034964                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x58c7d4b6713d98dd623c1c0120276cbe3a4cd2570d1906eef14771f10edc60af | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 54                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x722122df12d4e14e13ac3b6895a86e84145b6967                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x0465ff6d4edb1d4f876711152a0a30229fcc5a50                         |                                                              |
| encryptedNote     | VARCHAR   | 0x                                                                 |                                                              |

## 12. Table: TornadoProxy\_event\_InstanceStateUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-30 23:53:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12143762                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb0de81a2230a1e255e12fe87324fd97dea0f2ecdfe6340783692872831b886f3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 153                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x722122df12d4e14e13ac3b6895a86e84145b6967                         | Address of the contract that produced the log                |
| instance          | VARCHAR   | 0x610b717796ad172b316836ac95a2ffad065ceab4                         |                                                              |
| state             | VARCHAR   | 1                                                                  |                                                              |

## 13. Table: TornadoProxy\_event\_TornadoTreesUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| addr              | VARCHAR   |                                                              |             |

## 14. Table: cTornado\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-19 22:28:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12667476                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x91db41f9b22354f3b4f1b6e11496e1fa6c2caf985b6ccecbef8a0e17cefb5cc4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 75                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd21be7248e0197ee08e0c20d4a96debdac3d20af                         | Address of the contract that produced the log                |
| commitment        | VARCHAR   | 0x1106e6dead580abd896f4ca20d7196586fe25b009fe52d3b6f89a503bd7a7e9e |                                                              |
| leafIndex         | VARCHAR   | 75                                                                 |                                                              |
| timestamp         | VARCHAR   | 1624141685                                                         |                                                              |

## 15. Table: cTornado\_event\_Withdrawal\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-11 23:33:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13207443                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x091fe2567a043badb8cca3d8cdd41d829afcb7c4c494e48ca48021da7743bf92 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 83                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x03893a7c7463ae47d46bc7f091665f1893656003                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0x3b06f4fcdf17cbcd4dc9681758950f4406475f05                         |                                                              |
| nullifierHash     | VARCHAR   | 0x2367db620fe1dd10a0341b520725d7b0af8e427dba722f68827f498ca13e4932 |                                                              |
| relayer           | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| fee               | VARCHAR   | 0                                                                  |                                                              |
