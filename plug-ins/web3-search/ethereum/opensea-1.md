# opensea

## 1. Table: OpenSeaENSResolver\_event\_ABIChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| node              | VARCHAR   |                                                              |             |
| contentType       | VARCHAR   |                                                              |             |

## 2. Table: OpenSeaENSResolver\_event\_AddrChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-16 01:16:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9113134                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1fd3a75e0acae0d59dfffd4153e1344032357e8b8cb58ade8408785e86b74505 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 166                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9c4e9cce4780062942a7fe34fa2fa7316c872956                         | Address of the contract that produced the log                |
| node              | VARCHAR   | 0x993a0ddcf17bca3cb7dff1a00aa962a5dd75a8e2351a2d0d0d6f0929f2d7a019 |                                                              |
| a                 | VARCHAR   | 0x3e1d499bd92f0622d6f35c49a4d1ff890f467d33                         |                                                              |

## 3. Table: OpenSeaENSResolver\_event\_AuthorisationChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| node              | VARCHAR   |                                                              |             |
| owner             | VARCHAR   |                                                              |             |
| target            | VARCHAR   |                                                              |             |
| isAuthorised      | VARCHAR   |                                                              |             |

## 4. Table: OpenSeaENSResolver\_event\_ContenthashChanged\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-16 01:46:49+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9289288                                                                        | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5f7fe9b0386e0f5d537ccff0cee0872635d1d074a8c3490eacf8585db1a37fc2             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 43                                                                             | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9c4e9cce4780062942a7fe34fa2fa7316c872956                                     | Address of the contract that produced the log                |
| node              | VARCHAR   | 0x5a6eea90990f479df86c4aea5595daee7af8ea379545a3216575a5d668afd13a             |                                                              |
| hash              | VARCHAR   | 0xe301017012205f4c7713acdfc0fb2c4b701b095ad4f3bd6fe1d51998aa6f32cbbc408195835d |                                                              |

## 5. Table: OpenSeaENSResolver\_event\_InterfaceChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| node              | VARCHAR   |                                                              |             |
| interfaceID       | VARCHAR   |                                                              |             |
| implementer       | VARCHAR   |                                                              |             |

## 6. Table: OpenSeaENSResolver\_event\_NameChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| node              | VARCHAR   |                                                              |             |
| name              | VARCHAR   |                                                              |             |

## 7. Table: OpenSeaENSResolver\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-06-27 15:49:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8040871                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaba70d6b413e81a6b86980d853843d97a1053f0c31d5450033faf93f80c6f8f3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 34                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9c4e9cce4780062942a7fe34fa2fa7316c872956                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x30dd12344ce6bb4596c37f68b507028fabfe2e0f                         |                                                              |

## 8. Table: OpenSeaENSResolver\_event\_PubkeyChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| node              | VARCHAR   |                                                              |             |
| x                 | VARCHAR   |                                                              |             |
| y                 | VARCHAR   |                                                              |             |

## 9. Table: OpenSeaENSResolver\_event\_TextChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-09 01:27:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8899550                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0871f3b2217fccc2c4336d285baeff5bb9ebbe8223d6cde6cfb6db06d9ca5fdb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 452                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9c4e9cce4780062942a7fe34fa2fa7316c872956                         | Address of the contract that produced the log                |
| node              | VARCHAR   | 0x31468cae24aa5a6f9bf88241e4ec254c36304c59ee7a77b3ef863dcf83368333 |                                                              |
| indexedKey        | VARCHAR   | url                                                                |                                                              |
| key               | VARCHAR   | url                                                                |                                                              |

## 10. Table: SeaDrop\_event\_AllowListUpdated\_history

| Column             | Type      | Example                                                                                              | Description                                                  |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2023-07-04 08:03:35+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 17619249                                                                                             | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0xe8d8d1b859833217926cf95bdc1fd8597a3154eaa1fd10d22a8ed8b3ae6a54b5                                   | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 429                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x00005ea00ac477b1030ce78506496e8c2de24bf5                                                           | Address of the contract that produced the log                |
| nftContract        | VARCHAR   | 0x9be8ef77078aae6700c0ef5e53c8143d42115c2f                                                           |                                                              |
| previousMerkleRoot | VARCHAR   | 0x9234b33823c07ae7a9ca6a9bb554a8b1e09f14b99b41a543fc47bfe3d9a777fd                                   |                                                              |
| newMerkleRoot      | VARCHAR   | 0xb12d9aed6c5b4ff4cd92e80001843bf8fe40df45e6230e6db21b5baf0cac8cc5                                   |                                                              |
| publicKeyURI       | VARCHAR   | https://opensea.io/.well-known/allowlist-pubkeys/mainnet/ALLOWLIST\_ENCRYPTION\_KEY\_0.txt           |                                                              |
| allowListURI       | VARCHAR   | https://opensea-drops.mypinata.cloud/ipfs/bafkreiguntjyrcscpk47wssf7zmwe2uxx5nxhjuz7wxys6zwuurdfg4dz |                                                              |

## 11. Table: SeaDrop\_event\_AllowedFeeRecipientUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-25 09:51:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17769336                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd0164cfb33caf357782eebb410600fb5aafab734dd83c6993a1cc1e844903c5a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 164                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00005ea00ac477b1030ce78506496e8c2de24bf5                         | Address of the contract that produced the log                |
| nftContract       | VARCHAR   | 0x44d1c4f2378cb47a0f20e78308b34787e89a6df5                         |                                                              |
| feeRecipient      | VARCHAR   | 0x0000a26b00c1f0df003000390027140000faa719                         |                                                              |
| allowed           | VARCHAR   | true                                                               |                                                              |

## 12. Table: SeaDrop\_event\_CreatorPayoutAddressUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-04 08:07:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17405962                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd86742e966b448ab4fa0bc81263061b340db5e985164cffde594883f37da252e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 52                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00005ea00ac477b1030ce78506496e8c2de24bf5                         | Address of the contract that produced the log                |
| nftContract       | VARCHAR   | 0x6824c568aeb2652aadf36fc12af5606b8bcee5ac                         |                                                              |
| newPayoutAddress  | VARCHAR   | 0xbb80803728fb95affa0d7df38774ee6fd9f82e75                         |                                                              |

## 13. Table: SeaDrop\_event\_DropURIUpdated\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-13 18:49:11+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17252932                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7151b77ea148fa787b5f83660ad6bb42b792eb6cb1e1d35888c88ad571401e30                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 182                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00005ea00ac477b1030ce78506496e8c2de24bf5                                                           | Address of the contract that produced the log                |
| nftContract       | VARCHAR   | 0x04e8e4a75eba081854c63fbdef454fe5582aa805                                                           |                                                              |
| newDropURI        | VARCHAR   | https://opensea-drops.mypinata.cloud/ipfs/bafkreiaqshxwmtarrg72ikj3u4xldwtc2l3aquaubezivhjkzleqd3vaa |                                                              |

## 14. Table: SeaDrop\_event\_PayerUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-27 22:54:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17787512                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6f7359ac3962bcf2ec87eea87d1b2b1bef806109432c378a97ca4d4cdcd5b335 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 117                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00005ea00ac477b1030ce78506496e8c2de24bf5                         | Address of the contract that produced the log                |
| nftContract       | VARCHAR   | 0x8df10b1fdea4f75a2c88ec1de57d9ab001d02a40                         |                                                              |
| payer             | VARCHAR   | 0xef0b56692f78a44cf4034b07f80204757c31bcc9                         |                                                              |
| allowed           | VARCHAR   | true                                                               |                                                              |

## 15. Table: SeaDrop\_event\_PublicDropUpdated\_history

| Column                              | Type                                                                                                                                      | Example                                                                                              | Description                                                  |
| ----------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp                    | TIMESTAMP                                                                                                                                 | 2023-05-12 01:33:47+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number                       | INTEGER                                                                                                                                   | 17240914                                                                                             | The block number where this event was emitted                |
| transaction\_hash                   | VARCHAR                                                                                                                                   | 0xbd1c56876b2546b34d7e510a694ae0d75f2a3c3874a9b81dd2da790a1bac915e                                   | Hash of the transactions in which this event was emitted     |
| log\_index                          | INTEGER                                                                                                                                   | 293                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address                   | VARCHAR                                                                                                                                   | 0x00005ea00ac477b1030ce78506496e8c2de24bf5                                                           | Address of the contract that produced the log                |
| nftContract                         | VARCHAR                                                                                                                                   | 0xa99223ca1785cdaceecd37becbe58062a65e8593                                                           |                                                              |
| publicDrop                          | STRUCT\<mintPrice STRING, startTime STRING, endTime STRING, maxTotalMintableByWallet STRING, feeBps STRING, restrictFeeRecipients STRING> | {'mintPrice': '40000000000000000', 'startTime': '1683849600', 'endTime': '1684022400', 'maxTotalMint |                                                              |
| publicDrop.mintPrice                | VARCHAR                                                                                                                                   | 40000000000000000                                                                                    |                                                              |
| publicDrop.startTime                | VARCHAR                                                                                                                                   | 1683849600                                                                                           |                                                              |
| publicDrop.endTime                  | VARCHAR                                                                                                                                   | 1684022400                                                                                           |                                                              |
| publicDrop.maxTotalMintableByWallet | VARCHAR                                                                                                                                   | 4150                                                                                                 |                                                              |
| publicDrop.feeBps                   | VARCHAR                                                                                                                                   | 250                                                                                                  |                                                              |
| publicDrop.restrictFeeRecipients    | VARCHAR                                                                                                                                   | true                                                                                                 |                                                              |

## 16. Table: SeaDrop\_event\_SeaDropMint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-13 17:37:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17252575                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6c679d1f0356b3455e06fe3275112cf284d81e99328e825baac25825e8b0861a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 302                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00005ea00ac477b1030ce78506496e8c2de24bf5                         | Address of the contract that produced the log                |
| nftContract       | VARCHAR   | 0x436ec1e4e9218d2a1bbb8f9da44a11796f9e5965                         |                                                              |
| minter            | VARCHAR   | 0x0e747a5416b7b2f5addad4a9e47a77a1678bf441                         |                                                              |
| feeRecipient      | VARCHAR   | 0x0000a26b00c1f0df003000390027140000faa719                         |                                                              |
| payer             | VARCHAR   | 0x0e747a5416b7b2f5addad4a9e47a77a1678bf441                         |                                                              |
| quantityMinted    | VARCHAR   | 1                                                                  |                                                              |
| unitMintPrice     | VARCHAR   | 25000000000000000                                                  |                                                              |
| feeBps            | VARCHAR   | 1000                                                               |                                                              |
| dropStageIndex    | VARCHAR   | 0                                                                  |                                                              |

## 17. Table: SeaDrop\_event\_SignedMintValidationParamsUpdated\_history

| Column                                                 | Type                                                                                                                                                                           | Example                                                                                             | Description                                                  |
| ------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp                                       | TIMESTAMP                                                                                                                                                                      | 2023-05-02 19:45:47+00:00                                                                           | Timestamp of the block where this event was emitted          |
| block\_number                                          | INTEGER                                                                                                                                                                        | 17175243                                                                                            | The block number where this event was emitted                |
| transaction\_hash                                      | VARCHAR                                                                                                                                                                        | 0xe187b821a3b91493e6f1cfd853c125837fd457d5e2d0aeb84035879648bf605b                                  | Hash of the transactions in which this event was emitted     |
| log\_index                                             | INTEGER                                                                                                                                                                        | 216                                                                                                 | Integer of the log index position in the block of this event |
| contract\_address                                      | VARCHAR                                                                                                                                                                        | 0x00005ea00ac477b1030ce78506496e8c2de24bf5                                                          | Address of the contract that produced the log                |
| nftContract                                            | VARCHAR                                                                                                                                                                        | 0x0264cb26b26a26f4433ebfc368fe3113b74d6ee3                                                          |                                                              |
| signer                                                 | VARCHAR                                                                                                                                                                        | 0x4f04919940ef9f293dce6d13f049bdd06061f447                                                          |                                                              |
| signedMintValidationParams                             | STRUCT\<minMintPrice STRING, maxMaxTotalMintableByWallet STRING, minStartTime STRING, maxEndTime STRING, maxMaxTokenSupplyForStage STRING, minFeeBps STRING, maxFeeBps STRING> | {'minMintPrice': '0', 'maxMaxTotalMintableByWallet': '10000000', 'minStartTime': '0', 'maxEndTime': |                                                              |
| signedMintValidationParams.minMintPrice                | VARCHAR                                                                                                                                                                        | 0                                                                                                   |                                                              |
| signedMintValidationParams.maxMaxTotalMintableByWallet | VARCHAR                                                                                                                                                                        | 10000000                                                                                            |                                                              |
| signedMintValidationParams.minStartTime                | VARCHAR                                                                                                                                                                        | 0                                                                                                   |                                                              |
| signedMintValidationParams.maxEndTime                  | VARCHAR                                                                                                                                                                        | 1840204800                                                                                          |                                                              |
| signedMintValidationParams.maxMaxTokenSupplyForStage   | VARCHAR                                                                                                                                                                        | 1000000                                                                                             |                                                              |
| signedMintValidationParams.minFeeBps                   | VARCHAR                                                                                                                                                                        | 0                                                                                                   |                                                              |
| signedMintValidationParams.maxFeeBps                   | VARCHAR                                                                                                                                                                        | 10000                                                                                               |                                                              |

## 18. Table: SeaDrop\_event\_TokenGatedDropStageUpdated\_history

| Column                             | Type                                                                                                                                                                                            | Example                                                      | Description |
| ---------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp                   | TIMESTAMP                                                                                                                                                                                       | Timestamp of the block where this event was emitted          |             |
| block\_number                      | INTEGER                                                                                                                                                                                         | The block number where this event was emitted                |             |
| transaction\_hash                  | VARCHAR                                                                                                                                                                                         | Hash of the transactions in which this event was emitted     |             |
| log\_index                         | INTEGER                                                                                                                                                                                         | Integer of the log index position in the block of this event |             |
| contract\_address                  | VARCHAR                                                                                                                                                                                         | Address of the contract that produced the log                |             |
| nftContract                        | VARCHAR                                                                                                                                                                                         |                                                              |             |
| allowedNftToken                    | VARCHAR                                                                                                                                                                                         |                                                              |             |
| dropStage                          | STRUCT\<mintPrice STRING, maxTotalMintableByWallet STRING, startTime STRING, endTime STRING, dropStageIndex STRING, maxTokenSupplyForStage STRING, feeBps STRING, restrictFeeRecipients STRING> |                                                              |             |
| dropStage.mintPrice                | VARCHAR                                                                                                                                                                                         |                                                              |             |
| dropStage.maxTotalMintableByWallet | VARCHAR                                                                                                                                                                                         |                                                              |             |
| dropStage.startTime                | VARCHAR                                                                                                                                                                                         |                                                              |             |
| dropStage.endTime                  | VARCHAR                                                                                                                                                                                         |                                                              |             |
| dropStage.dropStageIndex           | VARCHAR                                                                                                                                                                                         |                                                              |             |
| dropStage.maxTokenSupplyForStage   | VARCHAR                                                                                                                                                                                         |                                                              |             |
| dropStage.feeBps                   | VARCHAR                                                                                                                                                                                         |                                                              |             |
| dropStage.restrictFeeRecipients    | VARCHAR                                                                                                                                                                                         |                                                              |             |

## 19. Table: WyvernExchangeWithBulkCancellations\_call\_atomicMatch\_\_history

| Column                         | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp               | TIMESTAMP | 2022-09-18 08:33:23+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number                  | INTEGER   | 15559268                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash              | VARCHAR   | 0x373e38364b9491e25a38473bf1595d238005dddd77c98a7c6f037707f78959c7                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index             | INTEGER   | 320                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address                 | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address                    | VARCHAR   | 0x7f268357a8c2552623316e2562d90e642bb538e5                                                           | Address of the called contract                                                                                         |
| status                         | INTEGER   | 0                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                          | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| addrs                          | VARCHAR   | 0x7f268357A8c2552623316e2562D90e642bB538E5,0x0324Fd4AB4b4a85496A6e75353f38f98BF457Efa,0x8bD0eE15ddD5 |                                                                                                                        |
| uints                          | VARCHAR   | 250,0,0,0,0,0,1647549086,0,8514933634734166870243499955646373987603589825155872990028520830864901597 |                                                                                                                        |
| feeMethodsSidesKindsHowToCalls | VARCHAR   | 1,0,0,1,1,1,0,1                                                                                      |                                                                                                                        |
| calldataBuy                    | VARCHAR   | 0x96809f90000000000000000000000000000000000000000000000000000000000000000000000000000000000000000003 |                                                                                                                        |
| calldataSell                   | VARCHAR   | 0x96809f900000000000000000000000008bd0ee15ddd50b99dc07fedd2008edb7ef4f5c5800000000000000000000000000 |                                                                                                                        |
| replacementPatternBuy          | VARCHAR   | 0x00000000ffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff00000000000000000000000000 |                                                                                                                        |
| replacementPatternSell         | VARCHAR   | 0x000000000000000000000000000000000000000000000000000000000000000000000000ffffffffffffffffffffffffff |                                                                                                                        |
| staticExtradataBuy             | VARCHAR   | 0x                                                                                                   |                                                                                                                        |
| staticExtradataSell            | VARCHAR   | 0x                                                                                                   |                                                                                                                        |
| vs                             | VARCHAR   | 27,27                                                                                                |                                                                                                                        |
| rssMetadata                    | VARCHAR   | 0xd98afb496ca81a432a16ade8e3a36f56c46e723ed84c93ba8f2e9151a2306fe6,0x1086662908728fb7fe9b68c7b6f19e9 |                                                                                                                        |

## 20. Table: WyvernExchangeWithBulkCancellations\_event\_NonceIncremented\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-06 14:59:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14334023                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1c19d7af3a6a1498f2f1427846134ce4bae3bf10caa7a53bc71c17786be3b5b5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 247                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7f268357a8c2552623316e2562d90e642bb538e5                         | Address of the contract that produced the log                |
| maker             | VARCHAR   | 0x236a87fb34a8a8346820c8e17dfd3d411c183c2d                         |                                                              |
| newNonce          | VARCHAR   | 1                                                                  |                                                              |

## 21. Table: WyvernExchangeWithBulkCancellations\_event\_OrderApprovedPartOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-28 03:54:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14472405                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa7e34e9c39c41584960e3ac5f33d5fc1732a791b9fa7fa15d84c6f857ed80791 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 289                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7f268357a8c2552623316e2562d90e642bb538e5                         | Address of the contract that produced the log                |
| hash              | VARCHAR   | 0x5717fad873e8c6a2d083914816b8c05a4b570578ce06c84841c60b6621505f71 |                                                              |
| exchange          | VARCHAR   | 0x7f268357a8c2552623316e2562d90e642bb538e5                         |                                                              |
| maker             | VARCHAR   | 0x2bbe92f7478827a621a9a3e1fc9a6ccc43d1a598                         |                                                              |
| taker             | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| makerRelayerFee   | VARCHAR   | 550                                                                |                                                              |
| takerRelayerFee   | VARCHAR   | 0                                                                  |                                                              |
| makerProtocolFee  | VARCHAR   | 0                                                                  |                                                              |
| takerProtocolFee  | VARCHAR   | 0                                                                  |                                                              |
| feeRecipient      | VARCHAR   | 0x5b3256965e7c3cf26e11fcaf296dfc8807c01073                         |                                                              |
| feeMethod         | VARCHAR   | 1                                                                  |                                                              |
| side              | VARCHAR   | 1                                                                  |                                                              |
| saleKind          | VARCHAR   | 0                                                                  |                                                              |
| target            | VARCHAR   | 0xbaf2127b49fc93cbca6269fade0f7f31df4c88a7                         |                                                              |

## 22. Table: WyvernExchangeWithBulkCancellations\_event\_OrderApprovedPartTwo\_history

| Column                    | Type      | Example                                                                                              | Description                                                  |
| ------------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp          | TIMESTAMP | 2022-06-02 14:08:28+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number             | INTEGER   | 14891425                                                                                             | The block number where this event was emitted                |
| transaction\_hash         | VARCHAR   | 0x7bd8914b733c9fb6e19d38ff99289c034b8d35332f3ab1b63f0ab9044e566976                                   | Hash of the transactions in which this event was emitted     |
| log\_index                | INTEGER   | 426                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address         | VARCHAR   | 0x7f268357a8c2552623316e2562d90e642bb538e5                                                           | Address of the contract that produced the log                |
| hash                      | VARCHAR   | 0xbde350a4410a3ee183efe1cc56ba6da2b75a75816621ea936a08a7854ea8bf96                                   |                                                              |
| howToCall                 | VARCHAR   | 1                                                                                                    |                                                              |
| calldata                  | VARCHAR   | 0xfb16a595000000000000000000000000f94ba7f0bdb3f1c2aff8b1bdd627f3cc45941ef900000000000000000000000000 |                                                              |
| replacementPattern        | VARCHAR   | 0x000000000000000000000000000000000000000000000000000000000000000000000000ffffffffffffffffffffffffff |                                                              |
| staticTarget              | VARCHAR   | 0x0000000000000000000000000000000000000000                                                           |                                                              |
| staticExtradata           | VARCHAR   | 0x                                                                                                   |                                                              |
| paymentToken              | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                                                           |                                                              |
| basePrice                 | VARCHAR   | 675000000000000000                                                                                   |                                                              |
| extra                     | VARCHAR   | 0                                                                                                    |                                                              |
| listingTime               | VARCHAR   | 1654178799                                                                                           |                                                              |
| expirationTime            | VARCHAR   | 1654268892                                                                                           |                                                              |
| salt                      | VARCHAR   | 60767799744436743982601530903522084337359656840810361920947999454867545157297                        |                                                              |
| orderbookInclusionDesired | VARCHAR   | true                                                                                                 |                                                              |

## 23. Table: WyvernExchangeWithBulkCancellations\_event\_OrderCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-03 09:38:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17179358                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x80ce0a3cd520f7fd544fdf6f6e6bac5bbac2b9917ea9ce086bf043599e143f73 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 389                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7f268357a8c2552623316e2562d90e642bb538e5                         | Address of the contract that produced the log                |
| hash              | VARCHAR   | 0x56f928e03646136fd02581ff3be572f942c1d6fe6ed3b6ec83d53fba58459951 |                                                              |

## 24. Table: WyvernExchangeWithBulkCancellations\_event\_OrdersMatched\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-19 19:29:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15174975                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd27d0f90888358e0293feaeec5ef85928cb4346ea0ccc583964ebf9904152a41 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 409                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7f268357a8c2552623316e2562d90e642bb538e5                         | Address of the contract that produced the log                |
| buyHash           | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000 |                                                              |
| sellHash          | VARCHAR   | 0xa71b601510f8fcf624211ecd705765679d71c7b3c54858d19183d830cfce0000 |                                                              |
| maker             | VARCHAR   | 0x0378a8f6280f68e9eb0e3f63a533d2cce2d867ad                         |                                                              |
| taker             | VARCHAR   | 0xd1391e0cea55c1b466c3f6fcd5240aced50d6026                         |                                                              |
| price             | VARCHAR   | 0                                                                  |                                                              |
| metadata          | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000 |                                                              |

## 25. Table: WyvernExchangeWithBulkCancellations\_event\_OwnershipRenounced\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner     | VARCHAR   |                                                              |             |

## 26. Table: WyvernExchangeWithBulkCancellations\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-01 17:23:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14121427                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x25f12ac1726e675647151516d0dac016c75be190b6a75f3f434c244a8019ed1b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 143                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7f268357a8c2552623316e2562d90e642bb538e5                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x939c8d89ebc11fa45e576215e2353673ad0ba18a                         |                                                              |
| newOwner          | VARCHAR   | 0xa839d4b5a36265795eba6894651a8af3d0ae2e68                         |                                                              |

## 27. Table: WyvernExchange\_call\_atomicMatch\_\_history

| Column                         | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp               | TIMESTAMP | 2019-05-23 14:02:09+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number                  | INTEGER   | 7816384                                                                                              | The block number where this event was emitted                                                                          |
| transaction\_hash              | VARCHAR   | 0x04b961985686d8d74e29088f09e5f9155886d62e502bf807ba92b0a8305c9bf2                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index             | INTEGER   | 74                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address                 | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address                    | VARCHAR   | 0x7be8076f4ea4a4ad08075c2508e481d6c946d12b                                                           | Address of the called contract                                                                                         |
| status                         | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                          | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| addrs                          | VARCHAR   | 0x7Be8076f4EA4A4AD08075C2508e481d6C946D12b,0x7C6b920a19aC5E4aAD70b8d9F2f50B09A13A2E62,0x000000000000 |                                                                                                                        |
| uints                          | VARCHAR   | 0,1000,0,0,225000000000000000,0,1558616985,1558876283,2641076077290868041246455376642575478000442899 |                                                                                                                        |
| feeMethodsSidesKindsHowToCalls | VARCHAR   | 1,0,0,0,1,1,0,0                                                                                      |                                                                                                                        |
| calldataBuy                    | VARCHAR   | 0x23b872dd00000000000000000000000000000000000000000000000000000000000000000000000000000000000000007c |                                                                                                                        |
| calldataSell                   | VARCHAR   | 0x23b872dd000000000000000000000000d047b65f54f4aa8eae6bb9f3d9d5d126fe722b9f00000000000000000000000000 |                                                                                                                        |
| replacementPatternBuy          | VARCHAR   | 0x00000000ffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff00000000000000000000000000 |                                                                                                                        |
| replacementPatternSell         | VARCHAR   | 0x000000000000000000000000000000000000000000000000000000000000000000000000ffffffffffffffffffffffffff |                                                                                                                        |
| staticExtradataBuy             | VARCHAR   | 0x                                                                                                   |                                                                                                                        |
| staticExtradataSell            | VARCHAR   | 0x                                                                                                   |                                                                                                                        |
| vs                             | VARCHAR   | 0,0                                                                                                  |                                                                                                                        |
| rssMetadata                    | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000,0x0000000000000000000000000000000 |                                                                                                                        |

## 28. Table: WyvernExchange\_event\_OrderApprovedPartOne\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-23 22:31:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8799341                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf2fb29400c7e2dff5a189c5893e5229572a8bd52faf8ddffddd6ff481a75b5c9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7be8076f4ea4a4ad08075c2508e481d6c946d12b                         | Address of the contract that produced the log                |
| hash              | VARCHAR   | 0xfb080ef4bcf9a683fc450a807908fa90bf25811c8f2e48c5f00d58c937e9f286 |                                                              |
| exchange          | VARCHAR   | 0x7be8076f4ea4a4ad08075c2508e481d6c946d12b                         |                                                              |
| maker             | VARCHAR   | 0x81369699f67ffca0048ac17d7c68107c1b5aad20                         |                                                              |
| taker             | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| makerRelayerFee   | VARCHAR   | 0                                                                  |                                                              |
| takerRelayerFee   | VARCHAR   | 250                                                                |                                                              |
| makerProtocolFee  | VARCHAR   | 0                                                                  |                                                              |
| takerProtocolFee  | VARCHAR   | 0                                                                  |                                                              |
| feeRecipient      | VARCHAR   | 0x5b3256965e7c3cf26e11fcaf296dfc8807c01073                         |                                                              |
| feeMethod         | VARCHAR   | 1                                                                  |                                                              |
| side              | VARCHAR   | 0                                                                  |                                                              |
| saleKind          | VARCHAR   | 0                                                                  |                                                              |
| target            | VARCHAR   | 0x0d8c864da1985525e0af0acbeef6562881827bd5                         |                                                              |

## 29. Table: WyvernExchange\_event\_OrderApprovedPartTwo\_history

| Column                    | Type      | Example                                                                                              | Description                                                  |
| ------------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp          | TIMESTAMP | 2020-03-20 14:32:58+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number             | INTEGER   | 9709101                                                                                              | The block number where this event was emitted                |
| transaction\_hash         | VARCHAR   | 0xec801dc7f34bb0eb0ef37bc646ddef981b5cc58d6177ed77ec99dbec3b536fc2                                   | Hash of the transactions in which this event was emitted     |
| log\_index                | INTEGER   | 75                                                                                                   | Integer of the log index position in the block of this event |
| contract\_address         | VARCHAR   | 0x7be8076f4ea4a4ad08075c2508e481d6c946d12b                                                           | Address of the contract that produced the log                |
| hash                      | VARCHAR   | 0x4a2e6c156e5a409cbea796632548aff683836da5f785b16bcbcb0527937ab35f                                   |                                                              |
| howToCall                 | VARCHAR   | 0                                                                                                    |                                                              |
| calldata                  | VARCHAR   | 0x23b872dd0000000000000000000000005c9602687c65447747510aa429859af3c52ab2da00000000000000000000000000 |                                                              |
| replacementPattern        | VARCHAR   | 0x000000000000000000000000000000000000000000000000000000000000000000000000ffffffffffffffffffffffffff |                                                              |
| staticTarget              | VARCHAR   | 0x0000000000000000000000000000000000000000                                                           |                                                              |
| staticExtradata           | VARCHAR   | 0x                                                                                                   |                                                              |
| paymentToken              | VARCHAR   | 0x09fe5f0236f0ea5d930197dce254d77b04128075                                                           |                                                              |
| basePrice                 | VARCHAR   | 4000000000000000000                                                                                  |                                                              |
| extra                     | VARCHAR   | 0                                                                                                    |                                                              |
| listingTime               | VARCHAR   | 1584712664                                                                                           |                                                              |
| expirationTime            | VARCHAR   | 0                                                                                                    |                                                              |
| salt                      | VARCHAR   | 33678615473066729953784617364363907702072253363772580124039647229810221965294                        |                                                              |
| orderbookInclusionDesired | VARCHAR   | true                                                                                                 |                                                              |

## 30. Table: WyvernExchange\_event\_OrderCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-06 02:30:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10209539                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x85a8d4319dda0e200186ce51b0afe4b38500b84fb64942bed14067970ba3171e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 120                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7be8076f4ea4a4ad08075c2508e481d6c946d12b                         | Address of the contract that produced the log                |
| hash              | VARCHAR   | 0x83c471691f71ed2590dce98c3dc5a0ae8ae89eba3a077da9ae5db6d91b39809e |                                                              |

## 31. Table: WyvernExchange\_event\_OrdersMatched\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-04-30 08:48:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7667802                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbf69101d869f656320cce985adda2ac9c658c388f97f2eb47f2e7ebec4e1a06b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7be8076f4ea4a4ad08075c2508e481d6c946d12b                         | Address of the contract that produced the log                |
| buyHash           | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000 |                                                              |
| sellHash          | VARCHAR   | 0xf55ae31909bf952bfe98828806c110749ed31bda98c010ede9aa702d0276b1c1 |                                                              |
| maker             | VARCHAR   | 0xd99fda417a0afa9117749b5bf15926a3ba2f64a1                         |                                                              |
| taker             | VARCHAR   | 0x04257e9dd2914361a21de973e3604b581ab903e3                         |                                                              |
| price             | VARCHAR   | 1000000000000000000                                                |                                                              |
| metadata          | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000 |                                                              |

## 32. Table: WyvernExchange\_event\_OwnershipRenounced\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner     | VARCHAR   |                                                              |             |

## 33. Table: WyvernExchange\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-06-12 07:43:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5774764                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xebe6bd9d1da992b9a6f816564eafef42e9bf68d3876fae22556cc63da6fc0f66 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7be8076f4ea4a4ad08075c2508e481d6c946d12b                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0084a81668b9a978416abeb88bc1572816cc7cac                         |                                                              |
| newOwner          | VARCHAR   | 0xa839d4b5a36265795eba6894651a8af3d0ae2e68                         |                                                              |

## 34. Table: WyvernProxyRegistry\_event\_OwnershipRenounced\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner     | VARCHAR   |                                                              |             |

## 35. Table: WyvernProxyRegistry\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-06-12 07:43:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5774762                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5403cc61a24ab34213a56527feb7ad8105ee9415a7137db02d6146cb62ff0c09 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 47                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa5409ec958c83c3f309868babaca7c86dcb077c1                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0084a81668b9a978416abeb88bc1572816cc7cac                         |                                                              |
| newOwner          | VARCHAR   | 0xa839d4b5a36265795eba6894651a8af3d0ae2e68                         |                                                              |
