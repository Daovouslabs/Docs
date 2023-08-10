# starknet

## 1. Table: GpsStatementVerifier\_call\_verifyProofAndRegister\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-04-10 04:30:11+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17015447                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x9367963a0457ba848b536220bb037e6897ea4abe40d31388a1e10de53bcb5918                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 97                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0                                                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x6cb3ee90c50a38a0e4662bb7e7e6e40b91361bf6                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| proofParams        | VARCHAR   | 16,4,32,6,9,0,3,3,3,3,3,3,2,2                                                                        |                                                                                                                        |
| proof              | VARCHAR   | 48488856519350703515060005979127781229861398472573122181866202071585595064320,1017062185439925988649 |                                                                                                                        |
| taskMetadata       | VARCHAR   | 128,2396,3068850377810731364250169858796291952506855863903938200658516448366463400202,2,2,1,0,2,2394 |                                                                                                                        |
| cairoAuxInput      | VARCHAR   | 24,0,65535,8319381555716711796,1,5,565,4517575,4517575,4775101,4775101,5593330,6347965,6469698,73965 |                                                                                                                        |
| cairoVerifierId    | VARCHAR   | 6                                                                                                    |                                                                                                                        |

## 2. Table: StarknetCore\_event\_LogStateUpdate\_history

| Column            | Type      | Example                                                                      | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-06 13:59:35+00:00                                                    | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17421855                                                                     | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf42107d720badfac30f9ddbbe2f6af89ff2c86c27a20ed136eea1b4e9dbde019           | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                          | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc662c410c0ecf747543f5ba90660f6abebd9c8c4                                   | Address of the contract that produced the log                |
| globalRoot        | VARCHAR   | 974600605052568976696799594291058732645519805380679531421682081634608217141  |                                                              |
| blockNumber       | VARCHAR   | 74268                                                                        |                                                              |
| blockHash         | VARCHAR   | 3106649194848932463703900609573628395353111282292397381002165760737615407846 |                                                              |

## 3. Table: Starknet\_event\_LogStateUpdate\_history

| Column            | Type      | Example                                                                     | Description                                                  |
| ----------------- | --------- | --------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-06 21:03:59+00:00                                                   | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16350307                                                                    | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbf1d440eb6127ccea8aa21eccc797399a9332342de2d45e6c3ba143738dda10d          | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 258                                                                         | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc662c410c0ecf747543f5ba90660f6abebd9c8c4                                  | Address of the contract that produced the log                |
| globalRoot        | VARCHAR   | 777961419439313192940650267424580120071500377497201357660634093454537042582 |                                                              |
| blockNumber       | VARCHAR   | 18289                                                                       |                                                              |
