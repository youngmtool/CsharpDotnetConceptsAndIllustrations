Illustrations: 4

LargeviewOfBlockchain.png![](/assets/LargeviewOfBlockchain.png)

================================================================================================

Blockheader.png![](/assets/Blockheader.png)================================================================================================

TransactionSendReceiveCoins.png

![](/assets/TransactionSendReceiveCoins.png)

================================================================================================

TransactionPartOfBlock.png

![](/assets/TransactionPartOfBlock.png)

Note that one block can have multiple transactions.

A transaction is composed of several data:

1.TxIn.

A TxIn can have input\(s\). One input is composed of "prev\_out" pointing to unspent output located in different transaction by specifying that output with the hash value of that transaction and the index number of that output in the correspond transaction and "scriptSig" playing a role of the signature.

2.TxOut.

A TxOut is composed of output\(s\). One output is composed of the value for an amount of coins which will be sent and a value of ScriptPubKey.

3.Other minimal data.

\(1\)hash is a transaction ID which is generated by twice hashing the entire of transaction\(TxOut, TxIn, other minimal data\) by SHA256 cryptocraphic hash function. So that, it's Transaction ID = SHA256\(SHA256\(EntireOfTransaction\)\).

\(2\)ver indicates the version of the transaction.

\(3\)vin\_sz indicates the size of the TxIn.

\(4\)vout\_sz indicates the size of the TxOut.

\(5\)lock\_time

\(6\)size indicates the entire size of the transaction.

===========================================================================================

![](/assets/BitcoinSecretIsSerializedToBase58Check.png)===========================================================================================



