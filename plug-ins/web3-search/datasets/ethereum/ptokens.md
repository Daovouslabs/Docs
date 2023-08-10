# ptokens

## 1. Table: pBTC\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-13 01:50:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17467927                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa68e1e993a5cdc89d7fe70ca5cb6de8115404cc63d5d4b2aa6c93bf1aa7f0d87 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 245                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5228a22e72ccc52d415ecfd199f99d0665e7733b                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xe66b31678d6c16e9ebf358268a790b763c133750                         |                                                              |
| spender           | VARCHAR   | 0xdef1c0ded9bec7f1a1670819833240f027b25eff                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 2. Table: pBTC\_event\_AuthorizedOperator\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-09 10:46:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9636780                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3ec2fd243625236a1e6adc9f60cce428a1094bd8ac23c5367631dce627f62649 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 72                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5228a22e72ccc52d415ecfd199f99d0665e7733b                         | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0xe95df133c291b045a75aef7c0d81f6d9469dcf33                         |                                                              |
| tokenHolder       | VARCHAR   | 0x9ea22c0da16d1dbb080700874b9b0686fef17179                         |                                                              |

## 3. Table: pBTC\_event\_Burned\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-29 09:24:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11749968                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd439c331e8ea3d23811b13b2bada00657a89ba6d3574112d54fa192de8994953 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 173                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5228a22e72ccc52d415ecfd199f99d0665e7733b                         | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0xfa61794e0581d92c6495b1639266b605f618afbc                         |                                                              |
| from              | VARCHAR   | 0xfa61794e0581d92c6495b1639266b605f618afbc                         |                                                              |
| amount            | VARCHAR   | 14000000000000000                                                  |                                                              |
| data              | VARCHAR   | 0x                                                                 |                                                              |
| operatorData      | VARCHAR   | 0x                                                                 |                                                              |

## 4. Table: pBTC\_event\_Minted\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-11 22:12:18+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11636274                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x93e4a370048cc295e35678c7956650dd7d394e6f26dc76c6b68a3ad2c67fa4fd                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 36                                                                                                   | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5228a22e72ccc52d415ecfd199f99d0665e7733b                                                           | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0x3423fb35149875e965f06c926da8ba82d63f7ddb                                                           |                                                              |
| to                | VARCHAR   | 0xec950b462df976b8e7b18445644f6e0e12c3f51e                                                           |                                                              |
| amount            | VARCHAR   | 100000000000000000                                                                                   |                                                              |
| data              | VARCHAR   | 0x01d2fb24317168a6997a528321efdc25d8a6df98cb2372e2583cbe8817739300da3348345567714551554370576a746841 |                                                              |
| operatorData      | VARCHAR   | 0x                                                                                                   |                                                              |

## 5. Table: pBTC\_event\_Redeem\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2021-04-23 08:36:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 12295415                                                           | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0x54d94172a46139dc8b7a0b040e1564723780de7a361a1f14cded916573d4e437 | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 242                                                                | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0x5228a22e72ccc52d415ecfd199f99d0665e7733b                         | Address of the contract that produced the log                |
| redeemer                 | VARCHAR   | 0xfa61794e0581d92c6495b1639266b605f618afbc                         |                                                              |
| value                    | VARCHAR   | 49654060000000000                                                  |                                                              |
| underlyingAssetRecipient | VARCHAR   | bc1q265c7m45n9cxhu9p3r8k6fv63zsvhfv2jn599r                         |                                                              |

## 6. Table: pBTC\_event\_RevokedOperator\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-14 09:15:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15139863                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7735bcfab1ff8828d12b0d5f06f334f5378f01c85d49889b68b8be0c6615e30e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5228a22e72ccc52d415ecfd199f99d0665e7733b                         | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0x3423fb35149875e965f06c926da8ba82d63f7ddb                         |                                                              |
| tokenHolder       | VARCHAR   | 0x56a090734d40037545d617a5ef56309b3ed499a4                         |                                                              |

## 7. Table: pBTC\_event\_Sent\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-23 01:54:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17318814                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf0721924a6d7b11b516ee796ed1a820dd69650b5b2e51269582b808c6d3c1b6f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 128                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5228a22e72ccc52d415ecfd199f99d0665e7733b                         | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0x8d50d0fd88016ea63229e432803db4069c40db09                         |                                                              |
| from              | VARCHAR   | 0x8d50d0fd88016ea63229e432803db4069c40db09                         |                                                              |
| to                | VARCHAR   | 0xe66b31678d6c16e9ebf358268a790b763c133750                         |                                                              |
| amount            | VARCHAR   | 11049063007424495                                                  |                                                              |
| data              | VARCHAR   | 0x                                                                 |                                                              |
| operatorData      | VARCHAR   | 0x                                                                 |                                                              |

## 8. Table: pBTC\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-15 13:02:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17265350                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x728c50fba3a6e02f139223071f305646bd28c2a6a998cbc8df6b302a59a618b5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 190                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5228a22e72ccc52d415ecfd199f99d0665e7733b                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x92712c03c39c213f6ca4168b6c39ca7368df19ad                         |                                                              |
| to                | VARCHAR   | 0x8d50d0fd88016ea63229e432803db4069c40db09                         |                                                              |
| value             | VARCHAR   | 9166853666085128                                                   |                                                              |
