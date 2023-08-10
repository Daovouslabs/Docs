# origin\_protocol

## 1. Table: OriginToken\_event\_AddCallSpenderWhitelist\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-10-01 23:07:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6436159                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbf896e9f06eee7d01aec63c02fd469ed2af4dae505a50c536fdd72e7d6257666 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8207c1ffc5b6804f6024322ccf34f29c3541ae26                         | Address of the contract that produced the log                |
| enabler           | VARCHAR   | 0xaed9fdc9681d61edb5f8b8e421f5cee8d7f4b04f                         |                                                              |
| spender           | VARCHAR   | 0x819bb9964b6ebf52361f1ae42cf4831b921510f9                         |                                                              |

## 2. Table: OriginToken\_event\_AllowedTransactorAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-02-16 00:50:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7225654                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb4c1c50a7b7b0a7e16df0445a5bb493c81cc4ca0bd57201bdba7d21ed4b884a1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 14                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8207c1ffc5b6804f6024322ccf34f29c3541ae26                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x3ddb21eff50640af57bcea41374001aff245bf28                         |                                                              |

## 3. Table: OriginToken\_event\_AllowedTransactorRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-09-26 18:24:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8626068                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5d6a13392a0baba83ac05f7647f371a994f096d49ef9b0a7cbf3fcda1b2c60ba | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8207c1ffc5b6804f6024322ccf34f29c3541ae26                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x705ea5f4a50fcd8ef5cdfa9d3647b582a196cb5a                         |                                                              |

## 4. Table: OriginToken\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-27 17:45:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17785977                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7285f4085f5e7fd5eaa7640ebf646f696130aafb78a8a68f09c4772fdd96c656 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 420                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8207c1ffc5b6804f6024322ccf34f29c3541ae26                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x34da8ad494cf29bfbbe325d3125aff16e2281b57                         |                                                              |
| spender           | VARCHAR   | 0x000000000022d473030f116ddee9f6b43ac78ba3                         |                                                              |
| value             | VARCHAR   | 505798388295176464782920                                           |                                                              |

## 5. Table: OriginToken\_event\_Burn\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| burner            | VARCHAR   |                                                              |             |
| value             | VARCHAR   |                                                              |             |

## 6. Table: OriginToken\_event\_MintFinished\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 7. Table: OriginToken\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-10-01 23:06:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6436154                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9b8a3a8db40b02078f89cec2eed569682a23e37b36c3e462190ef391ebdd1d11 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8207c1ffc5b6804f6024322ccf34f29c3541ae26                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0xaed9fdc9681d61edb5f8b8e421f5cee8d7f4b04f                         |                                                              |
| amount            | VARCHAR   | 1000000000000000000000000000                                       |                                                              |

## 8. Table: OriginToken\_event\_OwnershipRenounced\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner     | VARCHAR   |                                                              |             |

## 9. Table: OriginToken\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-28 17:32:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12723873                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa2be22ad6e086700ad1d336f21dba9df8fe428754ba7c102a33c8751713de67f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 55                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8207c1ffc5b6804f6024322ccf34f29c3541ae26                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0xe011fa2a6df98c69383457d87a056ed0103aa352                         |                                                              |
| newOwner          | VARCHAR   | 0xbe2ab3d3d8f6a32b96414ebbd865dbd276d3d899                         |                                                              |

## 10. Table: OriginToken\_event\_Pause\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 11. Table: OriginToken\_event\_RemoveCallSpenderWhitelist\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| disabler          | VARCHAR   |                                                              |             |
| spender           | VARCHAR   |                                                              |             |

## 12. Table: OriginToken\_event\_SetWhitelistExpiration\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-28 21:20:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9177673                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd18e85e996ea66e922422d1c56adf97a3103301ed5cf4895892cd5a6c86f2882 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 214                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8207c1ffc5b6804f6024322ccf34f29c3541ae26                         | Address of the contract that produced the log                |
| expiration        | VARCHAR   | 1580428800                                                         |                                                              |

## 13. Table: OriginToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-26 08:11:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12508809                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6bdabb18e2cdbe193aa7cd5db4a56086ae68140aa2ffce0cb9934a770b19ce06 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 251                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8207c1ffc5b6804f6024322ccf34f29c3541ae26                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xfa72bce5544871bce67a1b9487c8edc85e09258c                         |                                                              |
| to                | VARCHAR   | 0xc7807e24338b41a34d849492920f2b9d0e4de2cd                         |                                                              |
| value             | VARCHAR   | 496980000000000000000                                              |                                                              |

## 14. Table: OriginToken\_event\_Unpause\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
