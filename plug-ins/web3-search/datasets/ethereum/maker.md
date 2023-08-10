# maker

## 1. Table: Cat\_call\_bite\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-05-04 06:00:33+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 9997980                                                            | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x037bbdedf16460eb2c204f9fd5916fd5d3d6e2cdbaefce8ae7cd9af78d4106ba | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 42                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 12                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x78f2c2af65126834c51822f56be0d7469d7a523e                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| ilk                | VARCHAR   | 0x4554482d41000000000000000000000000000000000000000000000000000000 |                                                                                                                        |
| urn                | VARCHAR   | 0xad67dead22840f6062fe0f3b2d2f7a898f8b29db                         |                                                                                                                        |

## 2. Table: Cat\_event\_Bite\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-19 16:03:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9903845                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9239aab41be995e98281ac0e366acc565f00c54aa01cea5d0ca4cc562ee6abb5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 137                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x78f2c2af65126834c51822f56be0d7469d7a523e                         | Address of the contract that produced the log                |
| ilk               | VARCHAR   | 0x4241542d41000000000000000000000000000000000000000000000000000000 |                                                              |
| urn               | VARCHAR   | 0x05a2249934dcf574d1d2978cc899f675f0c5295b                         |                                                              |
| ink               | VARCHAR   | 2124000000000000000000                                             |                                                              |
| art               | VARCHAR   | 230444484219962674068                                              |                                                              |
| tab               | VARCHAR   | 235049020387847083110232759194103471617525346260                   |                                                              |
| flip              | VARCHAR   | 0xaa745404d55f88c108a28c86abe7b5a1e7817c07                         |                                                              |
| id                | VARCHAR   | 467                                                                |                                                              |

## 3. Table: Clipper\_event\_Deny\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-23 14:19:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14830058                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd891445bf62cb9df39a07be390f2650be820d4cb2c8efe51b4506e1763435f97 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 539                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0227b54adbfaeec5f1ed1dfa11f54dcff9076e2c                         | Address of the contract that produced the log                |
| usr               | VARCHAR   | 0xbb856d1742fd182a90239d7ae85706c2fe4e5922                         |                                                              |

## 4. Table: Clipper\_event\_File\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-06 14:20:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16126313                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2f56e494f9ce43861ad0b70bb9aa5cdbd60445089b3cc891fbdb4d5ab6016b63 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 466                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbcb396cd139d1116bd89562b49b9d1d6c25378b0                         | Address of the contract that produced the log                |
| what              | VARCHAR   | 0x63616c6300000000000000000000000000000000000000000000000000000000 |                                                              |
| data              | VARCHAR   | 0xa2a4aefed398661b0a873d3782da121c194a0201                         |                                                              |

## 5. Table: Clipper\_event\_Kick\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-25 06:00:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14840204                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbeee5db7e99eaa6db82400e9f82cacd3808232ba12b497edd0fa90fcdf63b647 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9dacc11dcd0aa13386d295eaeebbd38130897e6f                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 27                                                                 |                                                              |
| top               | VARCHAR   | 10746489937300000000000000000000                                   |                                                              |
| tab               | VARCHAR   | 11522964355496697445914443263394994034103448765743                 |                                                              |
| lot               | VARCHAR   | 1984000000000000000                                                |                                                              |
| usr               | VARCHAR   | 0xf0c8b6ccfddb894560710b4c3b0512a9045bc50c                         |                                                              |
| kpr               | VARCHAR   | 0x521752d41a21d027d09ebb0654e9541e3118439e                         |                                                              |
| coin              | VARCHAR   | 311522964355496697445914443263394994034103448765                   |                                                              |

## 6. Table: Clipper\_event\_Redo\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-14 05:41:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16824180                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf78d0ec8a98f5d852ef7cb1d936ad2bda389f1839b91951030572fd4393d2acc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 23                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x046b1a5718da6a226d912cfd306ba19980772908                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 244                                                                |                                                              |
| top               | VARCHAR   | 1000000000000000000000000000                                       |                                                              |
| tab               | VARCHAR   | 20372317649222502284512227419843190781322890332                    |                                                              |
| lot               | VARCHAR   | 25000000000000000000                                               |                                                              |
| usr               | VARCHAR   | 0x74b45102238ad157eab4ea5be069e41ffadfca9a                         |                                                              |
| kpr               | VARCHAR   | 0x007e31eaae82c452b121d93248092ba926d625ef                         |                                                              |
| coin              | VARCHAR   | 0                                                                  |                                                              |

## 7. Table: Clipper\_event\_Rely\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-15 18:52:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12246413                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe7c95007b074caea4925722e61695be975b5c925a5289874e49a08fde4b2b42f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 44                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x832dd5f17b30078a5e46fdb8130a68cbc4a74dc0                         | Address of the contract that produced the log                |
| usr               | VARCHAR   | 0xbe8e3e3618f7474f8cb1d074a26affef007e98fb                         |                                                              |

## 8. Table: Clipper\_event\_Take\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-14 03:48:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12822867                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb30534d18796eaf30b63a527043255eb7ea8e7f27c3797e60859157d24e179df | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 35                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x832dd5f17b30078a5e46fdb8130a68cbc4a74dc0                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 45                                                                 |                                                              |
| max               | VARCHAR   | 15710123950306058300286546257                                      |                                                              |
| price             | VARCHAR   | 15710123950306058300286546257                                      |                                                              |
| owe               | VARCHAR   | 6607318787444991354026429546388065976719223264858                  |                                                              |
| tab               | VARCHAR   | 0                                                                  |                                                              |
| lot               | VARCHAR   | 191278435383962777324                                              |                                                              |
| usr               | VARCHAR   | 0x05547c48ef56ea24e9453fce5528be0bfd61b7e7                         |                                                              |

## 9. Table: Clipper\_event\_Yank\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| id                | VARCHAR   |                                                              |             |

## 10. Table: DSChief\_event\_Etch\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-13 04:41:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8731092                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2d8c5c9f363637d4c05260ab27d5c157216822fea645f38de12f6cbe626fe662 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 130                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ef05f7f6deb616fd37ac3c959a2ddd25a54e4f5                         | Address of the contract that produced the log                |
| slate             | VARCHAR   | 0xc5d2460186f7233c927e7db2dcc703c0e500b653ca82273b7bfad8045d85a470 |                                                              |

## 11. Table: DSChief\_event\_LogSetOwner\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-05-06 05:22:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7705361                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x004dc1881628216d15c769bf6047ba1a6c0f1316cd313bc51fd82324d42b0a70 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 15                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ef05f7f6deb616fd37ac3c959a2ddd25a54e4f5                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xad469ea2813264475abe13bb5e4656ee8725a2dd                         |                                                              |

## 12. Table: DSChief\_old\_event\_Etch\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-08 10:00:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7030664                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x62e1c83299e354dcc2250bc242c9fb40d7ccdeb4688309bcf8741ff7df5ae71a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 11                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8e2a84d6ade1e7fffee039a35ef5f19f13057152                         | Address of the contract that produced the log                |
| slate             | VARCHAR   | 0xbec99c130344ae112435b31df55d72010736b623069d3753857d2d77f396de2c |                                                              |

## 13. Table: DSChief\_old\_event\_LogSetOwner\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2017-12-17 16:10:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4749331                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x564ec0d334333117c4bf4fa95f4b4fd8ce273d13055ce76eb7c105f2e8a6af43 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 44                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8e2a84d6ade1e7fffee039a35ef5f19f13057152                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x4f26ffbe5f04ed43630fdc30a87638d53d0b0876                         |                                                              |

## 14. Table: DSGuard\_event\_LogPermit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2017-12-18 03:12:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4752020                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5e9650d385807b339446b874125907c110e061f8d458c6f9b753ced5eae5bb26 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 30                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x315cbb88168396d12e1a255f9cb935408fe80710                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0x0000000000000000000000009b0ccf7c8994e19f39b2b4cf708e0a7df65fa8a3 |                                                              |
| dst               | VARCHAR   | 0x000000000000000000000000448a5065aebb8e423f0896e6c5d525c040f59af3 |                                                              |
| sig               | VARCHAR   | 0x8ceedb4700000000000000000000000000000000000000000000000000000000 |                                                              |

## 15. Table: DSGuard\_event\_LogSetOwner\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2017-12-18 03:12:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4752020                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5e9650d385807b339446b874125907c110e061f8d458c6f9b753ced5eae5bb26 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 12                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x315cbb88168396d12e1a255f9cb935408fe80710                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x01c1103d765f62a0d909499d7b615c382cdb072d                         |                                                              |

## 16. Table: DSPause\_event\_LogSetAuthority\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-07 14:01:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11406096                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe8fb340e75944772ad179e5a1cd25516fe000220bf7ca5d2fdb2c0d543c5d0b1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 216                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbe286431454714f511008713973d3b053a2d38f3                         | Address of the contract that produced the log                |
| authority         | VARCHAR   | 0x0a3f6849f78076aefadf113f5bed87720274ddc0                         |                                                              |

## 17. Table: DSPause\_event\_LogSetOwner\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-13 19:20:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8928171                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x60215e5c38f8d02a64b4c029619d9efe88671dd7468ad84997f0812fe0ae6cc6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 35                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbe286431454714f511008713973d3b053a2d38f3                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x84f2b4648990d93c0f478d5d82d3c38d98a4ee91                         |                                                              |

## 18. Table: DSProxyFactory\_event\_Created\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-03 03:48:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11579174                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe52d583856132d7e0b21969ba435c898f89636bece88e427045e844851b06560 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 258                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa26e15c895efc0616177b7c1e7270a4c7d51c997                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x4678f0a6958e4d2bc4f1baf7bc52e8f3564f3fe4                         |                                                              |
| owner             | VARCHAR   | 0xe4c65d7deccbeef7c339e292a557e681111c46d1                         |                                                              |
| proxy             | VARCHAR   | 0xbe7cb08af0a9fb19fe30c841148a0a9940ffac9f                         |                                                              |
| cache             | VARCHAR   | 0x271293c67e2d3140a0e9381eff1f9b01e07b0795                         |                                                              |

## 19. Table: DSProxy\_event\_LogSetOwner\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-07-03 23:07:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5900857                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1deceb53f49a3a97316b5635cdd1d52f8aeee95c62647693a2c84e737d4b78f6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 146                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfb8c6679c45067fc95f6b4b675608c822c00f453                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xa26e15c895efc0616177b7c1e7270a4c7d51c997                         |                                                              |

## 20. Table: DSToken\_MKR\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-13 14:37:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17251690                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcb4a0f9ddc02b98eb25e3af004724692658ec7cc1962720b44448f9334174351 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 585                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9f8f72aa9304c8b593d555f12ef6589cc3a579a2                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x9a6cdf8221636d503773aad48dd3998e4ae03a5d                         |                                                              |
| spender           | VARCHAR   | 0xcfe1e539acb2d489a651ca011a6eb93d32f97e23                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 21. Table: DSToken\_MKR\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-24 12:08:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12496906                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x98f69864416dea6bfabc62cbbb79686f37187a16f5765a959bcb94505908c164 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 267                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9f8f72aa9304c8b593d555f12ef6589cc3a579a2                         | Address of the contract that produced the log                |
| guy               | VARCHAR   | 0xc4269cc7acdedc3794b221aa4d9205f564e27f0d                         |                                                              |
| wad               | VARCHAR   | 8493962515741906807                                                |                                                              |

## 22. Table: DSToken\_MKR\_event\_LogSetAuthority\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-13 20:42:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9274872                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6c3e56c4b99b280dddbff4f087c25d89c054421a202503fd49c36c6683e48fa1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 47                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9f8f72aa9304c8b593d555f12ef6589cc3a579a2                         | Address of the contract that produced the log                |
| authority         | VARCHAR   | 0x6eeb68b2c7a918f36b78e2db80dcf279236ddfb8                         |                                                              |

## 23. Table: DSToken\_MKR\_event\_LogSetOwner\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-25 15:18:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9741254                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x94e271b7ff6737363edda6fead1f65a597094bfa5515ad821556dfc968e5a519 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 191                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9f8f72aa9304c8b593d555f12ef6589cc3a579a2                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 24. Table: DSToken\_MKR\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-20 20:41:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9710799                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe4afda06001bf260d801a8efbfbb878dd31bb455433a102f011e9b9c90169c1a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 33                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9f8f72aa9304c8b593d555f12ef6589cc3a579a2                         | Address of the contract that produced the log                |
| guy               | VARCHAR   | 0x198ad6c547d20d70f2f656a4f48e6c7cfb7b4325                         |                                                              |
| wad               | VARCHAR   | 172668237613803692892                                              |                                                              |

## 25. Table: DSToken\_MKR\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-05-15 02:39:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5615527                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x05d159ba1c35516a4f3417739f895d4730cca0f2ba682d6655f628eaf2875f52 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 42                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9f8f72aa9304c8b593d555f12ef6589cc3a579a2                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x000723754dd766a5f5c9fb2924d0dff51169109d                         |                                                              |
| to                | VARCHAR   | 0x4969358e80cdc3d74477d7447bffa3b2e2acbe92                         |                                                              |
| value             | VARCHAR   | 1508000000000000000                                                |                                                              |

## 26. Table: DSToken\_SAI\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-13 08:55:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17683534                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x377e3d04430d477f92788cf02b2ad80524b3f416ae0eee1f1864e3e81679d4d8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 64                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x89d24a6b4ccb1b6faa2625fe562bdd9a23260359                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0x562f21ba442976ab97892c25f56771050cc93129                         |                                                              |
| guy               | VARCHAR   | 0x09cabec1ead1c0ba254b09efb3ee13841712be14                         |                                                              |
| wad               | VARCHAR   | 0                                                                  |                                                              |

## 27. Table: DSToken\_SAI\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-17 13:13:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15358908                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x66934c617707d14165583824eeeec6d6845bd1cad1570e02109efa9a9bf19456 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 150                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x89d24a6b4ccb1b6faa2625fe562bdd9a23260359                         | Address of the contract that produced the log                |
| guy               | VARCHAR   | 0x9fdc15106da755f9ffd5b0ba9854cfb89602e0fd                         |                                                              |
| wad               | VARCHAR   | 16303992822457594321                                               |                                                              |

## 28. Table: DSToken\_SAI\_event\_LogSetAuthority\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2017-12-18 03:12:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4752020                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5e9650d385807b339446b874125907c110e061f8d458c6f9b753ced5eae5bb26 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 20                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x89d24a6b4ccb1b6faa2625fe562bdd9a23260359                         | Address of the contract that produced the log                |
| authority         | VARCHAR   | 0x315cbb88168396d12e1a255f9cb935408fe80710                         |                                                              |

## 29. Table: DSToken\_SAI\_event\_LogSetOwner\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2017-12-18 03:12:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4752020                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5e9650d385807b339446b874125907c110e061f8d458c6f9b753ced5eae5bb26 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x89d24a6b4ccb1b6faa2625fe562bdd9a23260359                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 30. Table: DSToken\_SAI\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-04-16 18:48:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5452423                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x424fac18815f6e2735aa133880e98af74b12fcc724385fe6f0fad518c9e5aa3b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 110                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x89d24a6b4ccb1b6faa2625fe562bdd9a23260359                         | Address of the contract that produced the log                |
| guy               | VARCHAR   | 0x48413d529ff56310128dc91fb9fc833bb0aef449                         |                                                              |
| wad               | VARCHAR   | 2000000000000000000                                                |                                                              |

## 31. Table: DSToken\_SAI\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-11 07:01:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14183283                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x11375bed4495af0aea4ea1ce527b75b70511e3260477ea0dbce77cdcfc4f0a32 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 416                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x89d24a6b4ccb1b6faa2625fe562bdd9a23260359                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0xa2c1b488c8eadf161d95c9b3de614ed8cf5fe96c                         |                                                              |
| dst               | VARCHAR   | 0x8f9a0935b26097a1fc15d4919e0b9e466edc1c57                         |                                                              |
| wad               | VARCHAR   | 4999963086539999974                                                |                                                              |

## 32. Table: DSValue\_event\_LogSetOwner\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-13 19:29:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8928207                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4882096060bf714a4adc29a7a73f5d2e5ce9d7622ec0b8097b91bc237fb9be27 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x54003dbf6ae6cba6ddae571ccdc34d834b44ab1e                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xddb108893104de4e1c6d0e47c42237db4e617acc                         |                                                              |

## 33. Table: Dai\_call\_burn\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-12-01 23:06:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16093131                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xf58a2b5b5d06cc23e69509a1e033805b530ce676ca488e34dc8442f62787c632 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 9                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 1,1,6,1,1                                                          | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| usr                | VARCHAR   | 0x89b78cfa322f6c5de0abceecab66aee45393cc5a                         |                                                                                                                        |
| wad                | VARCHAR   | 853285845000000000000                                              |                                                                                                                        |

## 34. Table: Dai\_call\_mint\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-09-04 09:12:30+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 10793997                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x67203c1a647694bb27d9a1c56f3f0bb92414770c8468acfa9f5983bfb007f5c7 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 130                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 1                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| usr                | VARCHAR   | 0xc2f61a6eeec48d686901d325cde9233b81c793f3                         |                                                                                                                        |
| wad                | VARCHAR   | 909642690000000000000000                                           |                                                                                                                        |

## 35. Table: Dai\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-24 08:02:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15816644                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0d3f25624ac25d5eee35a97108bfaf2b3d1c3de5f5a7362187cff616c2a078af | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 170                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0x5b9045adfaf64f84f9e7eefc32cafd7a5ebf0fa3                         |                                                              |
| guy               | VARCHAR   | 0x0449f65a5e09f0f30aa504b8474d1d4d0e10b8b8                         |                                                              |
| wad               | VARCHAR   | 1199870000000000000000                                             |                                                              |

## 36. Table: Dai\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-13 06:54:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17682936                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdf405f56e7b51dc73146888953758561d305e412b1ace2df3fc0bb935819c6f9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 108                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0x8f22f49eb82cf0bcf0e2c3f061ff9105465083ab                         |                                                              |
| dst               | VARCHAR   | 0x120707691885539be27c5762c8f1db4b987e07ec                         |                                                              |
| wad               | VARCHAR   | 2746667504000000000000                                             |                                                              |

## 37. Table: Dog\_event\_Bark\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-14 03:02:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12822656                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd2b9f0376e119192cae2a417d72bb7cdca94017d892940d6a8957f5f884cd483 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 35                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x135954d155898d42c90d2a57824c690e0c7bef1b                         | Address of the contract that produced the log                |
| ilk               | VARCHAR   | 0x4c494e4b2d410000000000000000000000000000000000000000000000000000 |                                                              |
| urn               | VARCHAR   | 0x05547c48ef56ea24e9453fce5528be0bfd61b7e7                         |                                                              |
| ink               | VARCHAR   | 611855561850000000000                                              |                                                              |
| art               | VARCHAR   | 5709164020802406416019                                             |                                                              |
| due               | VARCHAR   | 5847184767650434826572061545476164581167454216689                  |                                                              |
| clip              | VARCHAR   | 0x832dd5f17b30078a5e46fdb8130a68cbc4a74dc0                         |                                                              |
| id                | VARCHAR   | 45                                                                 |                                                              |

## 38. Table: Dog\_event\_Cage\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 39. Table: Dog\_event\_Deny\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-23 14:19:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14830058                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd891445bf62cb9df39a07be390f2650be820d4cb2c8efe51b4506e1763435f97 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 509                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x135954d155898d42c90d2a57824c690e0c7bef1b                         | Address of the contract that produced the log                |
| usr               | VARCHAR   | 0xbb856d1742fd182a90239d7ae85706c2fe4e5922                         |                                                              |

## 40. Table: Dog\_event\_Digs\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-25 18:27:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17337934                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0b51485d7debb4a16fa28fe3812cea01c94995f784fd30d871a8548b063a696b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 69                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x135954d155898d42c90d2a57824c690e0c7bef1b                         | Address of the contract that produced the log                |
| ilk               | VARCHAR   | 0x4c494e4b2d410000000000000000000000000000000000000000000000000000 |                                                              |
| rad               | VARCHAR   | 15741021128749678455363962057231844092395318913497                 |                                                              |

## 41. Table: Dog\_event\_File\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-02 14:01:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13537931                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf91cdba571422ba3da9e7b79cbc0d51e8208244c2679e4294eec4ab5807acf7f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 372                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x135954d155898d42c90d2a57824c690e0c7bef1b                         | Address of the contract that produced the log                |
| ilk               | VARCHAR   | 0x4449524543542d4141564556322d444149000000000000000000000000000000 |                                                              |
| what              | VARCHAR   | 0x636c697000000000000000000000000000000000000000000000000000000000 |                                                              |
| clip              | VARCHAR   | 0xa93b98e57dde14a3e301f20933d59dc19bf8212e                         |                                                              |

## 42. Table: Dog\_event\_Rely\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-16 18:11:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14787779                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xafd7a7df690b9ff90300b1904a6295a8b863b5631d518c87d793c47948de31bd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 71                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x135954d155898d42c90d2a57824c690e0c7bef1b                         | Address of the contract that produced the log                |
| usr               | VARCHAR   | 0x3ea60191b7d5990a3544b6ef79983fd67e85494a                         |                                                              |

## 43. Table: DssCdpManager\_event\_NewCdp\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-15 12:41:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8938479                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf93d2e20e113342b98d91fbca8471239eba6d5b1f883428ed260ce6d1ffe0860 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 44                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5ef30b9986345249bc32d8928b7ee64de9435e39                         | Address of the contract that produced the log                |
| usr               | VARCHAR   | 0x23e91332984eed55c88131c58295c8dce379e2ab                         |                                                              |
| own               | VARCHAR   | 0x23e91332984eed55c88131c58295c8dce379e2ab                         |                                                              |
| cdp               | VARCHAR   | 115                                                                |                                                              |

## 44. Table: DssDeploy\_event\_LogSetOwner\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-13 19:15:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8928141                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa4e10b0578187107bf533d0a6c1106c79cc9ce91a1fd662961d9b2a97c80634b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbaa65281c2fa2baacb2cb550ba051525a480d3f4                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xddb108893104de4e1c6d0e47c42237db4e617acc                         |                                                              |

## 45. Table: DssPsm\_event\_BuyGem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-08 21:02:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15927871                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x195b1cd7d9ef1eb9712aacaa538a26042fa6ca7a66e05623413842e7ef3d96e2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 15                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x89b78cfa322f6c5de0abceecab66aee45393cc5a                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x079b68be414c6401e23ecd836f22f64be4b3b5d6                         |                                                              |
| value             | VARCHAR   | 2880097000000                                                      |                                                              |
| fee               | VARCHAR   | 0                                                                  |                                                              |

## 46. Table: DssPsm\_event\_SellGem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-20 20:05:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16450290                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xde3612fd067b85df6d91a1b686b3caf37dfd9fdc287cb540a9c5d32151bdc522 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 125                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x89b78cfa322f6c5de0abceecab66aee45393cc5a                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x00000000000747d525e898424e8774f7eb317d00                         |                                                              |
| value             | VARCHAR   | 3600712865                                                         |                                                              |
| fee               | VARCHAR   | 0                                                                  |                                                              |

## 47. Table: Flapper\_event\_Kick\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-02-12 20:03:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9470224                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xebef7ce1d39b0f6e49caa40188ffabe1d155ed1135f0c38f850dde97180ce957 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdfe0fb1be2a52cdbf8fb962d5701d7fd0902db9f                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 15                                                                 |                                                              |
| lot               | VARCHAR   | 10000000000000000000000000000000000000000000000000                 |                                                              |
| bid               | VARCHAR   | 0                                                                  |                                                              |

## 48. Table: Flipper\_BAT\_call\_deal\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2019-12-29 15:29:55+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 9181466                                                            | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xeaa74862fb1481fd8527863e352c3666f252429fb3fe5781ff853b5734fc9e9b | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 20                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xaa745404d55f88c108a28c86abe7b5a1e7817c07                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| id                 | VARCHAR   | 50                                                                 |                                                                                                                        |

## 49. Table: Flipper\_BAT\_call\_dent\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-01-15 15:10:51+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 9286435                                                            | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x815bebc76c03c557e62d18c4e4c39fe96941b4612ae4b2837defe970be6cb11c | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 6                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xaa745404d55f88c108a28c86abe7b5a1e7817c07                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| id                 | VARCHAR   | 53                                                                 |                                                                                                                        |
| lot                | VARCHAR   | 236530937168710607371                                              |                                                                                                                        |
| bid                | VARCHAR   | 52329752161807972586973055007873649405417231671                    |                                                                                                                        |

## 50. Table: Flipper\_BAT\_call\_tend\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2019-12-18 14:10:33+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 9125940                                                            | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xeb59afa16b6c82ea958cee1f3e3630961370c2936d85598d12cdce319dc12a23 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 91                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xaa745404d55f88c108a28c86abe7b5a1e7817c07                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| id                 | VARCHAR   | 45                                                                 |                                                                                                                        |
| lot                | VARCHAR   | 250000000000000000000                                              |                                                                                                                        |
| bid                | VARCHAR   | 28312987200561938600683999538591953185482388881                    |                                                                                                                        |

## 51. Table: Flipper\_BAT\_event\_Kick\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-02-26 03:00:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9556543                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6664c1e0bf7d4d2063a8682a5b325680b77a6b64ae368ba9d2c7e02b931c13b7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 96                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xaa745404d55f88c108a28c86abe7b5a1e7817c07                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 70                                                                 |                                                              |
| lot               | VARCHAR   | 130000000000000000000                                              |                                                              |
| bid               | VARCHAR   | 0                                                                  |                                                              |
| tab               | VARCHAR   | 22661260419724981571133038427454985944464216985                    |                                                              |
| usr               | VARCHAR   | 0xfe31553fbd7dd18f2e48760c44cdbfba9a8f373c                         |                                                              |
| gal               | VARCHAR   | 0xa950524441892a31ebddf91d3ceefa04bf454466                         |                                                              |

## 52. Table: Flipper\_ETH\_call\_deal\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-04-02 00:42:29+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 9789356                                                            | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xb7b9713be2f0b57261c05fc5122a3369b13f38d13f2715d844eb04a6326f11d3 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 103                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xd8a04f5412223f513dc55f839574430f5ec15531                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| id                 | VARCHAR   | 4851                                                               |                                                                                                                        |

## 53. Table: Flipper\_ETH\_call\_dent\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-01-12 14:21:12+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 9266623                                                            | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x7ca5cd7177c3109819d8713c78e84fb4bb529534af93dc2ccb2029f5a6ea2355 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 0                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xd8a04f5412223f513dc55f839574430f5ec15531                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| id                 | VARCHAR   | 304                                                                |                                                                                                                        |
| lot                | VARCHAR   | 153554170483004466                                                 |                                                                                                                        |
| bid                | VARCHAR   | 22600007057087215748800393370165444196375529738                    |                                                                                                                        |

## 54. Table: Flipper\_ETH\_call\_tend\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-07-10 02:02:34+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 10428953                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x09988ba68cce2043b988276f742e12216021783917dab1120fb94ac8a16509af | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 70                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xd8a04f5412223f513dc55f839574430f5ec15531                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| id                 | VARCHAR   | 4979                                                               |                                                                                                                        |
| lot                | VARCHAR   | 150000000000000000                                                 |                                                                                                                        |
| bid                | VARCHAR   | 27266900000000000000394826094363059863151979396                    |                                                                                                                        |

## 55. Table: Flipper\_ETH\_event\_Kick\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-06 21:00:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10408163                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3063fabe16b9663a96ebbb834f4355c57cc0c3756afea9f608131b4b6778dded | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 42                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd8a04f5412223f513dc55f839574430f5ec15531                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 4977                                                               |                                                              |
| lot               | VARCHAR   | 169900000000000000                                                 |                                                              |
| bid               | VARCHAR   | 0                                                                  |                                                              |
| tab               | VARCHAR   | 30532600000000000000135919257917219333416383985                    |                                                              |
| usr               | VARCHAR   | 0xadf1390b59e3bf1fcd672efcda9305c2b4dd42e0                         |                                                              |
| gal               | VARCHAR   | 0xa950524441892a31ebddf91d3ceefa04bf454466                         |                                                              |

## 56. Table: Flipper\_call\_deal\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2019-12-25 19:21:41+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 9162174                                                            | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xef68df1b30d27e5086e6bfd759f4f7b559fc57fccc4f177f3aa59dde2b0b7c0c | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 5                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xd8a04f5412223f513dc55f839574430f5ec15531                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| id                 | VARCHAR   | 274                                                                |                                                                                                                        |

## 57. Table: Flipper\_call\_dent\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-06-15 12:55:43+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 10270430                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x0c66e8072f3b9f2f3309af03a128c14da9e819bd61b9900db194736624a38e9a | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 1                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 2                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xd8a04f5412223f513dc55f839574430f5ec15531                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| id                 | VARCHAR   | 4934                                                               |                                                                                                                        |
| lot                | VARCHAR   | 238984666507402375                                                 |                                                                                                                        |
| bid                | VARCHAR   | 50850000000000000000080701078281722214109302029                    |                                                                                                                        |

## 58. Table: Flipper\_call\_kick\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2019-12-28 02:51:11+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 9173777                                                            | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xbb3015eb1db8c68f7e5161b44b5d4a2d6bf2486737de7402fdfbf2c0f99632b8 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 12                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 4                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xd8a04f5412223f513dc55f839574430f5ec15531                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| usr                | VARCHAR   | 0x51e7d092e85b9a2c7d8a8c34550fdf86a0544537                         |                                                                                                                        |
| gal                | VARCHAR   | 0xa950524441892a31ebddf91d3ceefa04bf454466                         |                                                                                                                        |
| tab                | VARCHAR   | 2987370412266355527287769464064990072440682600890                  |                                                                                                                        |
| lot                | VARCHAR   | 31000000000000000000                                               |                                                                                                                        |
| bid                | VARCHAR   | 0                                                                  |                                                                                                                        |

## 59. Table: Flipper\_call\_tend\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2019-12-11 12:08:39+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 9088629                                                            | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xdef0be712f095537bc7af72b0df331d2db5a02b5991f4808676821fd5e3d70b7 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 33                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xaa745404d55f88c108a28c86abe7b5a1e7817c07                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| id                 | VARCHAR   | 7                                                                  |                                                                                                                        |
| lot                | VARCHAR   | 17914041068092846784769                                            |                                                                                                                        |
| bid                | VARCHAR   | 2387899377214436766728775879803975357457688112679                  |                                                                                                                        |

## 60. Table: Flipper\_event\_Kick\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-31 07:00:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10767181                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdac9a5d8f0e8ac35a83c4ea3b79ce6196cc9891d058279bb75fc2146b19dca82 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 51                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0f398a2daaa134621e4b687fccfee4ce47599cc1                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 55                                                                 |                                                              |
| lot               | VARCHAR   | 1235952758123546544                                                |                                                              |
| bid               | VARCHAR   | 0                                                                  |                                                              |
| tab               | VARCHAR   | 395500000000000000000858799990562985454201380269                   |                                                              |
| usr               | VARCHAR   | 0xa0be0b36cfd52c3d8c6abf08f61306fa52c9ec20                         |                                                              |
| gal               | VARCHAR   | 0xa950524441892a31ebddf91d3ceefa04bf454466                         |                                                              |

## 61. Table: IlkRegistry\_call\_add\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-12-13 14:01:11+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16176238                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x1833f4ee3f6b25b256b7a2d1b0648db550eced2a7cc455260f9a501c191f2b9b | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 221                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0,0,43,30                                                        | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x5a464c28d19848f44199d003bef5ecc87d090f87                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| adapter            | VARCHAR   | 0x7bd3f01e24e0f0838788bc8f573cea43a80cabb5                         |                                                                                                                        |

## 62. Table: JoinFab\_event\_NewJoin\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-02 21:04:11+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17395584                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf3ac8f230795072c3e9490d1828318588dcf6ecb3a20fb56c9fc123c5f9c28ec                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 91                                                                                                   | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf1738d22140783707ca71cb3746e0dc7bf2b0264                                                           | Address of the contract that produced the log                |
| join              | VARCHAR   | 0x8938988f7b368f74bebdd3dcd8d6a3bd18c15c0b                                                           |                                                              |
| data              | VARCHAR   | 0x00000000000000000000000035d1b3f3d7966a1dfe207aa4514c12a259a0492b5257413031352d41000000000000000000 |                                                              |

## 63. Table: OSM\_BAT\_event\_LogValue\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-25 12:01:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13094441                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3ff4094a20d411d2043e242fbd94051a850f5736da77eeab87190b4f8d1780f9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 199                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb4eb54af9cc7882df0121d26c5b97e802915abe6                         | Address of the contract that produced the log                |
| val               | VARCHAR   | 0x0000000000000000000000000000000000000000000000000b386d3511109e00 |                                                              |

## 64. Table: OSM\_ETH\_event\_LogValue\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-14 15:10:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9670314                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xeb58a1c926ed81fc761412233d5132cc65a1c6a734ce2fb7d9353bef20cf658f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 219                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x81fe72b5a8d1a857d176c3e7d5bd2679a9b85763                         | Address of the contract that produced the log                |
| val               | VARCHAR   | 0x000000000000000000000000000000000000000000000006dad8a50a08250000 |                                                              |

## 65. Table: Redeemer\_event\_LogSetOwner\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2017-11-25 18:24:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4620855                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5c9b0f9c6c32d2690771169ec62dd648fef7bce3d45fe8a6505d99fdcbade27a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 39                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x642ae78fafbb8032da552d619ad43f1d81e4dd7c                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x731c6f8c754fa404cfcc2ed8035ef79262f65702                         |                                                              |

## 66. Table: SaiTub\_event\_LogNewCup\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-06-08 00:48:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7915319                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7ece5820592c802cf75b4a80fc7d639c70dbfb8455a80383096f532d330df6bc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 59                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x448a5065aebb8e423f0896e6c5d525c040f59af3                         | Address of the contract that produced the log                |
| lad               | VARCHAR   | 0x4139d17b1cf38ce819fa0de2e82197c7cb27b607                         |                                                              |
| cup               | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000004705 |                                                              |

## 67. Table: SaiTub\_event\_LogSetAuthority\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2017-12-18 03:12:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4752020                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5e9650d385807b339446b874125907c110e061f8d458c6f9b753ced5eae5bb26 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 16                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x448a5065aebb8e423f0896e6c5d525c040f59af3                         | Address of the contract that produced the log                |
| authority         | VARCHAR   | 0x315cbb88168396d12e1a255f9cb935408fe80710                         |                                                              |

## 68. Table: SaiTub\_event\_LogSetOwner\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2017-12-18 03:12:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4752020                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5e9650d385807b339446b874125907c110e061f8d458c6f9b753ced5eae5bb26 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 17                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x448a5065aebb8e423f0896e6c5d525c040f59af3                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 69. Table: Spotter\_event\_Poke\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-26 13:03:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11731461                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2b3b51965d640efc70be212a0510ab642b4bffb8b630ce2f326adbd613879702 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 227                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x65c79fcb50ca1594b025960e539ed7a9a6d434a3                         | Address of the contract that produced the log                |
| ilk               | VARCHAR   | 0x4554482d41000000000000000000000000000000000000000000000000000000 |                                                              |
| val               | VARCHAR   | 0x00000000000000000000000000000000000000000000004780cd57a3743c0000 |                                                              |
| spot              | VARCHAR   | 879333333333333333333333333333                                     |                                                              |

## 70. Table: Vat\_call\_fold\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-07-19 05:02:13+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 10487922                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xe8531a684f79ffa2d739ab34825a992073fa2218b3136618010f84120454ee28 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 52                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,9,1                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x35d1b3f3d7966a1dfe207aa4514c12a259a0492b                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| i                  | VARCHAR   | 0x4554482d41000000000000000000000000000000000000000000000000000000 |                                                                                                                        |
| u                  | VARCHAR   | 0xa950524441892a31ebddf91d3ceefa04bf454466                         |                                                                                                                        |
| rate               | VARCHAR   | 0                                                                  |                                                                                                                        |

## 71. Table: Vat\_call\_frob\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-06-12 14:15:32+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 10251362                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xee64a816e8b50e3d3b1bd889a21c8229711e7cdee3e59243d81b665874c79b73 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 14                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,10                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x35d1b3f3d7966a1dfe207aa4514c12a259a0492b                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| i                  | VARCHAR   | 0x4241542d41000000000000000000000000000000000000000000000000000000 |                                                                                                                        |
| u                  | VARCHAR   | 0x5bd9c5a95357c8fbffc3a637056a3c6de02f2841                         |                                                                                                                        |
| v                  | VARCHAR   | 0xcc0a2331e5671498cdc7d6ccc01d843879a4a64c                         |                                                                                                                        |
| w                  | VARCHAR   | 0xcc0a2331e5671498cdc7d6ccc01d843879a4a64c                         |                                                                                                                        |
| dink               | VARCHAR   | 5000000000000000000000                                             |                                                                                                                        |
| dart               | VARCHAR   | 0                                                                  |                                                                                                                        |

## 72. Table: Vat\_call\_grab\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-02-14 15:00:06+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 9481819                                                            | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x19ce57714a81472ffa2bccf0ec44333a4cc01da2b4454b906bbdc57c054c2673 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 0                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 6,2                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x35d1b3f3d7966a1dfe207aa4514c12a259a0492b                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| i                  | VARCHAR   | 0x4554482d41000000000000000000000000000000000000000000000000000000 |                                                                                                                        |
| u                  | VARCHAR   | 0xc084f3e0c630702f73e266dfc27960979b5a14d8                         |                                                                                                                        |
| v                  | VARCHAR   | 0x78f2c2af65126834c51822f56be0d7469d7a523e                         |                                                                                                                        |
| w                  | VARCHAR   | 0xa950524441892a31ebddf91d3ceefa04bf454466                         |                                                                                                                        |
| dink               | VARCHAR   | -2444191256443570024                                               |                                                                                                                        |
| dart               | VARCHAR   | -435595614845832467506                                             |                                                                                                                        |

## 73. Table: Vat\_call\_move\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-03-07 04:52:17+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 11989311                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xe505028c88c17f0b4a6750ae50ddefee8a9b5c964608cb58fdaecdc746c13c03 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 92                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 2,0,1,0,1,2                                                        | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x35d1b3f3d7966a1dfe207aa4514c12a259a0492b                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| src                | VARCHAR   | 0x89b78cfa322f6c5de0abceecab66aee45393cc5a                         |                                                                                                                        |
| dst                | VARCHAR   | 0xa950524441892a31ebddf91d3ceefa04bf454466                         |                                                                                                                        |
| rad                | VARCHAR   | 187062031411000000000000000000000000000000000000                   |                                                                                                                        |

## 74. Table: mcdFab\_call\_exit\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-10-31 16:30:11+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15869245                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x5d6f98cb6ad34ab2dd542afb0b0d4405c315f578a22b6f295928a9de82aad3a6 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 206                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,3                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x10cd5fbe1b404b7e19ef964b63939907bdaf42e2                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| usr                | VARCHAR   | 0xa75c6a6af1757f543546be1d472d0acb1981d0db                         |                                                                                                                        |
| wad                | VARCHAR   | 80000000000000000000                                               |                                                                                                                        |

## 75. Table: mcdFab\_call\_join\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-10-15 06:45:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15751812                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x289f479b40d0f9fe891ebcb84afa9b698a62462116a353f64f397805a2afd697 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 11                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 13,5                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x7f62f9592b823331e012d3c5ddf2a7714cfb9de2                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| usr                | VARCHAR   | 0xabc64889601f01e7b26277ef8756250d6abf8c18                         |                                                                                                                        |
| wad                | VARCHAR   | 150707                                                             |                                                                                                                        |

## 76. Table: mcdIlk\_call\_exit\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-03-14 10:02:50+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 9668931                                                            | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xd4019897a60bd9adc4ec13c5ff090f0fa56c131472ff9ac89f30a0fc02f3ebc5 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 65                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,14                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x2f0b23f53734252bda2277357e97e1517d6b042a                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| usr                | VARCHAR   | 0x00c0cd38791d7d3667ddaf1aa7cd990f0634a5e0                         |                                                                                                                        |
| wad                | VARCHAR   | 330200000000000000000                                              |                                                                                                                        |

## 77. Table: mcdIlk\_call\_join\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-05-13 07:11:23+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17249496                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x6fcbf26176d3d842da2e2ae5f53e6e53f59413f1cd21bda2b34db99b8e074483 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 121                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,4                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x248ccbf4864221fc0e840f29bb042ad5bfc89b5c                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| usr                | VARCHAR   | 0x80299ecece63e49dbd9b9a1d210c9b99ae02fc1f                         |                                                                                                                        |
| wad                | VARCHAR   | 2669731055544030359                                                |                                                                                                                        |

## 78. Table: mcdPSM\_call\_exit\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-04-12 06:28:58+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14569114                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x3c9c827ff47ebbfcf43f471c945d2183015168dabde64b9659e459e5aa732702 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 1                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,3                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x0a59649758aa4d66e25f08dd01271e891fe52199                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| guy                | VARCHAR   | 0x0000006daea1723962647b7e189d311d757fb793                         |                                                                                                                        |
| wad                | VARCHAR   | 5000000000000                                                      |                                                                                                                        |

## 79. Table: mcdPSM\_call\_join\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-03-22 03:40:50+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 12086261                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x2fd187bb9fae7aa989c17ddb9e4fde3d6a98a772c7d4021a51521499f1bf3469 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 115                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x0a59649758aa4d66e25f08dd01271e891fe52199                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| urn                | VARCHAR   | 0x89b78cfa322f6c5de0abceecab66aee45393cc5a                         |                                                                                                                        |
| wad                | VARCHAR   | 97890000000                                                        |                                                                                                                        |
| \_msgSender        | VARCHAR   | 0x92e74e50edce4573d181c03ca889f72640cd3a94                         |                                                                                                                        |

## 80. Table: mcd\_call\_exit\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-08-07 00:39:18+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 12974703                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x2fd1a1a5866c0754f4977503203902f313857bbea84741d4c08050e38fbd3036 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 24                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x9759a6ac90977b93b58547b4a71c78317f391a28                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| usr                | VARCHAR   | 0x067fb6b6ff920e3ed9eee13808009bc2a6d5d736                         |                                                                                                                        |
| wad                | VARCHAR   | 100000000000000000000                                              |                                                                                                                        |

## 81. Table: mcd\_call\_join\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-12-25 21:41:29+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 11525290                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x070deee1c994ed573358ebdf98875e60692c21506a3718d1484e549ab1464aa6 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 42                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,5                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x9759a6ac90977b93b58547b4a71c78317f391a28                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| usr                | VARCHAR   | 0x262c39a8c8ab8b4d50f941dcbd1d89c8aae41b90                         |                                                                                                                        |
| wad                | VARCHAR   | 0                                                                  |                                                                                                                        |
