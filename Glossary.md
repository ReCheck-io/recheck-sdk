__(blockchain) address__- This is the address of the user given by the blockchain that is used (re_… or 0x...)  

__baseUrl__ - the web address of the service provider that is being used. 

__blockchain__ - a digital ledger that records data and is distributed across a network of computer systems that maintain its security and consistency.

__blockchain record__ - an immutable record of data that is stored on blockchain and usually created in relation to a smart contract function. Once stored such a record cannot be edited or deleted and has a digital trail that leads to the initiating identity.

__blockHash__ - The hash of the block in the blockchain

__blockNumber__ - The number of the block where the data has been stored in the blockchain

__Computed trail__ - anonymized sequence of data denoting the sender, the recipient, the data and the type of transaction executed.

__Computed trail__ - hash (fingerprint) representing a sequence of anonymized data denoting the sender, the recipient, the data and the type of transaction executed.

__contractAddress__ - the address of the contract that has been used for manipulation of the data. 

__cumulativeGasUsed__ - the gas that has been used for the blockchain operation 

__dataId__ - the hash of the data (usually file) stored on the blockchain. If it is a file it is created by taking it as a byte array and then hashing it. 

__decentralised digital identity__ - a set of identifiers and cryptographic keys that identify the acting user on the blockchain. It is owned and operated by the user and not ReCheck.

__digital evidence__ - an electronic claim that consist of information related to the execution of a digital transaction reflecting a user action or system event. A claim typically includes time of execution, participants, and type of transaction. 

__executorId__ - the user that has executed the operation on the blockchain. Usually this is the backend, which specifies the addresses of initiator/sender and receiver users. 

__extraTrailHashes__ - extra (usually external) facts/arguments that are added to the trail hash.  

__File identifier__ - a unique sequence of hexadecimal numbers that precisely represents the contents of the file. It is derived through cryptographic hash algorithms based on the byte sequence of the contents of the file. 

__gasUsed__ - the amount of gas used for the blockchain operation (usually on Ethereum) 

__payload__ - the result of some function. Usually this would be an encrypted file in the form of a String. 

__phrase__ - 12 words that are really important as they are the only means of recovering the user’s digital identity. 

__publicKey__ - the public key of the user

__publicEncKey__ - the public encryption key. A second key pair is used in our encryption for the purpose of more symmetric and asymmetric encryption to be included in the protocol.

__recipientId__ - hash of the user that is about to receive a shared file. 

__recipientEmail__ - the email that is about to receive a shared file. 

__recordId__ - the hash of the dataId (with keccak256).

__requestBodyHashSignature__ - this is the data put in and sent into the POST request and then hashed and signed, so that when it is received by the backend a checksum can be done and to verify that the request hasn’t been tampered with. 

__requestId__ -  a reference that the client specifies for tracking purposes at the moment of POST request.

__requestType__ - the type of POST request, or action, that has been sent. 

__secretKey__ - the private key of the user, the one that they can verify specific information with it. Very important, shouldn’t be known to anyone but the user. 

__secretEncKey__ - the private key of the second pair. Used in our encryption for the purpose of more symmetric and asymmetric encryption to be included in the protocol.

__smart contract__ - a digital, programmable agreement that is embedded in the computer code and managed by a blockchain. The smart contract consists of a set of rules under which the parties agree to interact with each other.

__trailHash__ - - hash (fingerprint) representing a sequence of anonymized data denoting the sender, the recipient, the data and the type of transaction executed.

__trailHashSignatureHash__ - the trailHash is being signed so that the backend checksum. 

__transactionHash__ - the hash of the transaction presented and stored in the blockchain

__transactionIndex__ - 

__txAttempts__ - the attempts being made to finalize the transaction and store it on the blockchain. The max is 4. 

__txAttemptTimestamp__ - the time at which the attempt has been made 

__txHash__ - the hash of the transaction presented and stored in the blockchain

__txReceipt__ - the receipt given by the blockchain as a result of the operation done

__txReceiptTimestamp__ - the time at which the receipt has been given

__txRowId__ - 

__txStatus__ - transaction status

__userEmail__ - the email used for sending encrypted message 

__userId__ - the blockchain address of the user. 

