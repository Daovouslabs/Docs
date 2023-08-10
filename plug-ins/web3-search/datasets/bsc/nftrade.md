# nftrade

## 1. Table: NFTrade\_event\_Fill\_history

| Column                 | Type      | Example                                                                                              | Description                                                  |
| ---------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2022-03-28 16:11:51+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 16456933                                                                                             | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0xda0426446d6034de04f795b2a1a4886a9c251976f597382e29f946fc6207b488                                   | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 575                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0xcfb6ee27d82beb1b0f3ad501b968f01cd7cc5961                                                           | Address of the contract that produced the log                |
| makerAddress           | VARCHAR   | 0x8a532825f258456f3ef07185ee6bedaaf2b2b8a8                                                           |                                                              |
| feeRecipientAddress    | VARCHAR   | 0x0000000000000000000000000000000000000000                                                           |                                                              |
| makerAssetData         | VARCHAR   | 0xf47261b0000000000000000000000000bb4cdb9cbd36b01bd1cbaebf2de08d9173bc095c                           |                                                              |
| takerAssetData         | VARCHAR   | 0xa7cb5fb70000000000000000000000001ddcd5b73afb734b4ae6b1c139858f36311ed4d300000000000000000000000000 |                                                              |
| makerFeeAssetData      | VARCHAR   | 0x                                                                                                   |                                                              |
| takerFeeAssetData      | VARCHAR   | 0x                                                                                                   |                                                              |
| orderHash              | VARCHAR   | 0x6514449dae305f5ebb437593c89a453338b46a0093c2ec17aee3908756396d0a                                   |                                                              |
| takerAddress           | VARCHAR   | 0x78b7b45e9801a01494489e7aae553369ddc791c3                                                           |                                                              |
| senderAddress          | VARCHAR   | 0x78b7b45e9801a01494489e7aae553369ddc791c3                                                           |                                                              |
| makerAssetFilledAmount | VARCHAR   | 10000000000000000                                                                                    |                                                              |
| takerAssetFilledAmount | VARCHAR   | 1                                                                                                    |                                                              |
| makerFeePaid           | VARCHAR   | 0                                                                                                    |                                                              |
| takerFeePaid           | VARCHAR   | 0                                                                                                    |                                                              |
| protocolFeePaid        | VARCHAR   | 0                                                                                                    |                                                              |
