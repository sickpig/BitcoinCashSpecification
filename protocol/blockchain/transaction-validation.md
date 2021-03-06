# Transaction Validation

Transaction validation in Bitcoin Cash involves a variety of checks that determine what happens to a transactions that has been received by a given node.  Some transactions may be considered invalid and rejected outright, others may be considered valid by some nodes but invalid by other nodes, and some valid transactions may not be distributed throughout the network as readily as others.  Each of these cases culminate in a network consensus by way of the [blockchain](/protocol/blockchain).  That is to say that although these rules clearly impact what transactions appears in blocks, any uncertainty about the validity of a transaction are quickly be resolved as new blocks are mined.

Transaction validation can be broken down into three major categories:

 - [Script](/protocol/blockchain/script) Execution Rules which determine whether the inputs of a transaction are considered spendable by the transaction
 - [Block-Level Validation Rules](/protocol/blockchain/transaction-validation/block-level-validation-rules) which determine whether transactions are valid in a given blockchain context (i.e. in a given block with a given history)
 - [Network-Level Validation Rules](/protocol/blockchain/transaction-validation/network-level-validation-rules) which determine whether transactions are relayed from node to node

The three of these are closely intertwined but often result in different behavior when they are violated.  For details, see the linked pages for definitions of each.