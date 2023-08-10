# maker

## 1. Table: DAI\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-10 02:29:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11824048                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x98d337c3f7bbb2cab347e02ca975c97eae5c0aeb38980672ec23ad3bb51aa910 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8f3cf7ad23cd3cadbd9735aff958023239c6a063                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x050ee024a0ffd8b9bd383271835b27dd66c3fec3                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 4675762902056981670274                                             |                                                              |
