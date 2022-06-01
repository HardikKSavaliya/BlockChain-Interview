## Private-BlockChain-Interview

# What is Blockchain?
The blockchain is a decentralized distributed ledger technology(DLT). The purpose behind of is to provide a network of transparency, immutability, and trust. The blockchain is open source and provides equal opportunities for anyone to improve and implement it in their system.

Blockchain is a system of multiple nodes which acts as a distributed network over the internet, all over the world each node has the authority to make a transaction, verify a transaction, receive a transaction and create a block.
 
# What do you mean by blocks in the blockchain technology?
A block in the Blockcahin is nothing but just a list of records. When these lists are joined with each other, they are known as Blockchain.

# What do you mean by node in the blockchain technology?
A blockchain exists out of blocks of data. These blocks of data are stored on nodes (compare it to small servers). Nodes can be any kind of device (mostly computers, laptops or even bigger servers). Nodes form the infrastructure of a blockchain. All nodes on a blockchain are connected to each other and they constantly exchange the latest blockchain data with each other so all nodes stay up to date. They store, spread and preserve the blockchain data, so theoretically a blockchain exists on nodes. A full node is basically a device (like a computer) that contains a full copy of the transaction history of the blockchain.

# What are the various types of Blockchains?
* Public - A public blockchain is a non-restrictive, permission-less distributed ledger system. (e.g. Bitcoin, Ethereum,..)
* Private - A private blockchain is a restrictive or permission blockchain operative only in a closed network. (e.g. Hyper Ledger, Corda,...)
* Consortium - A consortium blockchain is a semi-decentralized type where more than one organization manages a blockchain network. (e.g. Energy Web Foundation, R3,..)
* Hybrid - A hybrid blockchain is a combination of the private and public blockchain. It uses the features of both types of blockchains that is one can have a private permission-based system as well as a public permission-less system. (e.g. Dragonchain,..)

# What was the difference between blockchain and tradiditonal database?
  | Blockchain | Traditional Database |
  | -----------| ---------------------|
  | Centralized| Decentralized        |
  | only insert operations | Data manipulation is possible |
  | stored in block | stored in table |
  | Full Replication of block on every peer | Master Slave Multi-Master |
  | Majority of peers agree on the outcome of transactions |  Distributed Transactions (2 phase commit) |
  
# Please describle block structure of bitcoin blockchain
 | Field |	Description |	Size (Bytes) |
 | ------ | ------------ | ------|
 | Magic no |  value always 0xD9B4BEF9 |	4 bytes |
 | Blocksize |	number of bytes following up to end of block  |	4 bytes and onwords(up to 2 GB)|
 | Blockheader |	consists of 6 items  |	80 bytes |
 | Transaction counter | positive integer VI = VarInt |	1 - 9 bytes |
 | transactions	| list of transactions	 | x number of transactions |

# Please describe blockheader structure of bitcoin blockchain header
 | Field |	Purpose	| Updated when |	Size (Bytes) |
 | ------- | ------ | ---------- | ------------| 
 | Version	| Block version number |	You upgrade the software and it specifies a new version |	4 |
 | hashPrevBlock	| 256-bit hash of the previous block header |	A new block comes in |	32 |
 | hashMerkleRoot |	256-bit hash based on all of the transactions in the block |	A transaction is accepted |	32 |
 | Time	| Current block timestamp as seconds since 1970-01-01T00:00 UTC	| Every few seconds |	4 |
 | Bits	| Current target in compact format |	The difficulty is adjusted |	4 |
 | Nonce	| 32-bit number (starts at 0)	| A hash is tried (increments)	| 4 |
 
# Even when all 21 million bitcoins have been generated then after will create a new block?
Yes. The blocks are for proving that transactions existed at a particular time. Transactions will still occur once all the coins have been generated, so blocks will still be created as long as people are trading Bitcoins.
  
 # Characterstics of Blockchain?
  * Decentralized Systems
  * Distributed ledger 
  * Safer & Secure Ecosystem 
  * Minting 

# what the mean of address in blockchain(as aspect of bitcoin)?
These are usually used to receive and send transactions on the network. Associate degree address may be a string of alphanumerical characters.

# Type of addresses(as aspect of bitcoin)?
* P2PKH-Pay To Public Key Hash(start with 1)
* P2SH-Pay To Script Hash(start with 3)
* Bech32-(start with bc1)

# If wrong address will be putted as recipient address. what happen?
Whenever you paste an address in your bitcoin wallet, it checks the prefix and calculates the checksum. If it doesn’t match, it rejects the address. This makes it impossible to send funds to a wrong address due to a typing error.

# What is altcoin?
An altcoin is any digital cryptocurrency similar to Bitcoin. The term is said to stand for “alternative to bitcoin” and is used describe any cryptocurrency that is not a Bitcoin.
 
# What is encryption? What is its role in Blockchain?
Data security always matters. Encryption is basically an approach that helps organizations to keep their data secure. The encrypted data is encoded or changed up to some extent before it is sent out of a network by the sender and only authorized parties can access that information.In Blockchain, this approach is useful because it simply adds more to the overall security and authenticity of blocks and helps to keep them secure.

# Is it possible to modify the data once it is written in a block?
No, it’s not possible to do so. In case any modification is required, the organization simply has to erase the information from all other blocks too.

# What are Block Identifiers?
In Blockchain, blocks can be identified by the block header hash and the block height.

# What exactly do you know about the security of a block?
Well, a block or the entire blockchain is protected by a strong cryptographic hash algorithm. Each block has a unique hash pointer. Any modification in the block constituents will result in the change in the hash identifier of the block.  Therefore, it offers an excellent level of security.

# What are Merkle trees? How important are Merkle trees in Blockchains?
Named after Ralph Merkle,Merkle Tree also is a data structure in cryptography in which each leaf node is a hash of a block of data, and each non-leaf node is a hash of its child nodes. 

# How is a blockchain ledger different from an ordinary one?
The first and in fact the prime difference is Blockchain is a digital ledger that can be decentralized very easily. The chances of error in this approach are far less than that in an ordinary ledger. An ordinary ledger is what that is prepared by hands or by human efforts while the Blockchain performs all its tasks automatically. You just need to configure it in a proper manner and by following all the guidelines.

# What type of records can be kept in a Blockchain? Is there any restriction on same?
There is no restriction on keeping records of any type in the Blockchain approach. Industries are using Blockchain for securing all types of records.

The common types of records (to name a few) that can be kept on the Blockchains are:
* Records of medical transactions
* Identity management
* Transaction processing
* Business transactions,
* Management activities
* Documentation

# A distributed digital ledger is used for recording transaction in Blockchain. What does the system rely on?
The system relies on the network servicing protocol and the nodes of the network.

# What’s is the difference between blockchain and centralized network?
The main difference between a centralized network and blockchain is how they are controlled. The blockchain is completely decentralized and doesn’t require a central authority. Inadvertently, it also brings benefits to blockchain such as trust, transparency, immutability and so on.

# What is a cryptocurrency?
Cryptocurrency is a digital currency that works without any centralized control. Cryptocurrency powers a lot of blockchain networks out there. They are also known as virtual currencies and differ from the likes of fiat currencies. For example, Bitcoin, Ethereum, and Litecoin are the example of cryptocurrencies.

# Are blockchain more trustworthy?
The blockchain is trustworthy because of many reasons. The first reason is the security that blockchain offers. It is the most secure technology solution right now. Next, it is entirely decentralized. This removes the need for a centralized entity and the risks associated with it.

The last feature that makes blockchain more trustworthy is immutability. Data once stored cannot be changed.

# What are the two types of records that Blockchain database support?
Blockchain database supports "transactional" and "block" record. Both the records can be accessed without any issues.

# What are the key elements of the blockchain ecosystem? Explain each of them briefly.
The blockchain has four key elements. They are as follows.
* Shared Ledger: Shared ledger is the logical component of a blockchain. It is decentralized in nature.
* Node Application: A node application is a software/solution that lets a computer connect with the blockchain. For example, Bitcoin uses a Bitcoin wallet application to identify each node on the network.
* Virtual Machine: The virtual machine handles all the tasks that a blockchain undertakes. It is part of the node application and provides an environment where instructions can run.
* Consensus Algorithm: The Consensus algorithm is used to set the blockchain rules by which every node can come to a conclusion. There are different consensus algorithm used in the blockchain.

# What is a Shared ledger? Explain in detail.
A Shared ledger is the data structure that is stored in a blockchain’s node application. It holds the content of the blockchain and ensures that every node can have access to it. Shared ledger is distributed in nature.

One of the good examples includes the Ethereum client where it has a ledger that interacts with other components such as payments, smart contracts etc. Each blockchain has its own way of managing its shared ledger keeping the basics intact.

# Can you share the names of platforms are that are actively developing Blockchain apps?
There are many organization or platform that are actively improving the blockchain ecosystem. Hyperledger community is one of the leading open source platforms that is working towards developing enterprise-grade blockchain solution.

Ethereum platform is also active in blockchain app development. They do differ in their approach. Ethereum provides developers, organization, and business to create blockchain apps, whereas Hyperledger is creating tools, techniques and other methods to empower the different blockchains.

# What is double spending?
Double spending is a process through which a digital currency is spent more than once. In other words, it also means a digital currency can be cloned. In blockchain technology, double spending is not possible.

# What cryptographic algorithms are frequently used in blockchain?
There are many cryptographic algorithms used in the blockchain. They are as follows:

* RSA
* Blowfish
* TripleDES
* AES

# What makes RSA a secure cryptographic algorithm?
RSA provides state of the security algorithm for applications to use. It stands for Riverst, Shamir, and Adelman. They are the developer of this algorithm. RSA offers public-key encryption and hence is applicable in a variety of use-cases including blockchain. It is also the first encryption that is widely used for signing data and encryption. It works by using both private and public key.

# Explain blind signature and how it is useful?
A blind signature is an essential part of cryptography where the information is blinded or encrypted. The information is signed and hence become encrypted. The approach is verified and ensure that privacy protocols are maintained in the network.

# Can RSA be attacked? If so, how?
Yes, hackers can attack RSA. However, being attacked is not equal to weak protection. It is just the methods that can be used to attack it and take a chance to break it. There are two ways, one can attack RSA, i.e., brutal force and mathematical attacks.

#  What are the key principles that need to be followed to make blockchain secure?
Even though blockchain is secure, it still needs to be implemented correctly. The following principles need to be followed for proper implementation.
* Auditing
* Security testing
* Securing applications
* Continuity planning
* Database security
* Digital workforce training.

# Explain a real-time blockchain use case?
Healthcare can use blockchain to their advantage. Many startups are currently working on a blockchain powered health app that lets patients store their information on the blockchain. The decentralized nature means that they don’t have to carry documents. Healthcare specialist can also take advantage of it as they can access the patient’s data anytime they want. Researchers also benefit from public blockchain where they can access large public data.

# What is the difference between public and private key?
A private key is used to encrypt a message or a transaction that is sent on the blockchain.  The sender can send a message using the public key of the receiver. The receiver, on the other hand, can decrypt the message or the transaction using his private key. This way the communication or transaction is kept safe from any temper.

# Will blockchain change the world?
The blockchain is going to revolutionize our daily life. It has the potential to change how we spend and transact. Also, it is already changing various sectors such as transport, education, business, and so on. As it allows a peer-to-peer network, it will become easier to do business without any geographical restrictions.

Healthcare, for example, will also benefit from it by providing a place to store information for seamless access by authorities and patients.

# What is Secret Sharing? Does it have any benefit in Blockchain technology?
It is a well-understood that security matters a lot in digital transactions. Secret sharing in Blockchain technology is an approach that divides secret or personal information into different units and sent them to the users on the network. The original information can only be combined when a member to whom a share of the secret is allocated agree to combine them together with others. There are several security-related advantages it can offer in Blockchain technology.

# Why Blockchain is a trusted approach?
Blockchain can be trusted due to several reasons. The very first thing is its compatibility with other business applications because of its open-source nature. Second one is its security. As it was intended for online transactions, the developers have paid special attention in keeping up the pace when it comes to its security. It really doesn’t matter what type of business one owns, Blockchain can easily be considered.

# What is Blockchain Durability and robustness?
Blockchain technology is like the internet in that it has a built-in robustness. By storing blocks of information that are identical across its network, the blockchain cannot:
1. Be controlled by any single entity.
2. Has no single point of failure.
Bitcoin was invented in 2008. Since that time, the Bitcoin blockchain has operated without significant disruption. (To date, any of problems associated with Bitcoin have been due to hacking or mismanagement. In other words, these problems come from bad intention and human error, not flaws in the underlying concepts.)
The internet itself has proven to be durable for almost 30 years. It’s a track record that bodes well for blockchain technology as it continues to be developed

# What is Transparent and incorruptible in blockchain?
The blockchain network lives in a state of consensus, one that automatically checks in with itself every ten minutes. A kind of self-auditing ecosystem of a digital value, the network reconciles every transaction that happens in ten-minute intervals. Each group of these transactions is referred to as a “block”. Two important properties result from this:
Transparency data is embedded within the network as a whole, by definition it is public. It cannot be corrupted altering any unit of information on the blockchain would mean using a huge amount of computing power to override the entire network.

# How does Bitcoin use Blockchain?
A transaction is a transfer of value between Bitcoin wallets that gets included in the blockchain. Bitcoin wallets keep a secret piece of data called a private key or seed, which is used to sign transactions, providing a mathematical proof that they have come from the owner of the wallet.

# What are the business benefits of blockchain?
Blockchain consensus mechanisms provide the benefits of a consolidated, consistent dataset with reduced errors, near-real-time reference data, and the flexibility for participants to change the descriptions of the assets they own.

Because no one participating member owns the source of origin for information contained in the shared ledger, blockchain technologies lead to increased trust and integrity in the flow of transaction information among the participating members.

Immutability mechanisms of blockchain technologies lead to lowered cost of audit and regulatory compliance with improved transparency. And because contracts being executed on business networks using blockchain technologies are smart, automated, and final, businesses benefit from increased speed of execution, reduced costs, and less risk, all of which enables businesses to build new revenue streams to interact with clients.

# What are blockchain requirements?
Blockchain is a truly disruptive technology that can transform business networks. We also believe that this innovation has to happen in the open, collaborating with other technology companies and industries. To this end, IBM continues to contribute code to the Hyperledger Project.

From IBM’s perspective, industrial-grade blockchain technologies have the following characteristics:

A shared, permissioned ledger is the append-only system of record (SOR) and single source of truth. It is visible to all participating members of the business network.
A consensus protocol agreed to by all participating members of the business network ensures that the ledger is updated only with network-verified transactions.
Cryptography ensures tamper-proof security, authentication, and integrity of transactions.
Smart contracts encapsulate participant terms of agreements for the business that takes place on the network; they are stored on the validating nodes in the blockchain and triggered by transactions.

# what is ASIC miner?
An Application Specific Integrated(ASIC) miner is a device that is designed for the sole purpose of crypto mining only. Generally, each ASIC miner is constructed to mine a specific algorithm(e.g.SHA256,..). So, A SHA256 ASIC miner can mine only that particualar algorithm depdendent coin only.

# what is block heights?
Sequential number of block that already connected to blockchain network is called an blockheight.

# what is an genesis block height?
it will be 0. eventually intial block of blockchain will be called an genesis block and it will be always 0.

# what is block reward?
Block reward means predefined amount of coin and transaction cost of that particular block. In bitcoin it is 12.5 as of now in november 2019. it will be halfed at every 210000 successfull block mining.

# On which algorithm bitcoin blockchain works?
In SHA256

# what is consensus algorithm?
A consensus algorithm is a procedure through which all the peers of the Blockchain network reach a common agreement about the present state of the distributed ledger. In this way, consensus algorithms achieve reliability in the Blockchain network and establish trust between unknown peers in a distributed computing environment. Essentially, the consensus protocol makes sure that every new block that is added to the Blockchain is the one and only version of the truth that is agreed upon by all the nodes in the Blockchain.

# Types of consensus algorithm?
below is some of most popular
* PoW(proof of work)- Bitcoin, Ethereum(soon to PoS), Litecoin,..
* PoS(proof of stack)- Peer, Decred,..
* DPoS(delegated proof of stake)- eos,steemit,..
* PoA (proof of authority)- ethereum kovan testnet
* BFT (Byzantine Fault Tolerance)- Hyperledger, Stellar, Ripple,.
and many more like PBFT,FBA, DAGs,..

# what is IBD?
IBD stands for initial block download. it refers to the process where nodes synchronize themselves to the network by downloading blocks that are new to them. This will happen when a node is far behind the tip of the best block chain. In the process of IBD, a node does not accept incoming transactions nor request mempool transactions.

# what is mainnet and testnet?(as aspect of bitcoin)
Mainnet is the main ledger that everybody operates on. If somebody is talking about the value of Bitcoin, she refers to this particular network and all Bitcoins stored there have real value. while test node is intended for test transactions and the development process. 

# Is it possible that if-else can be used on contract level?
No, if-else cant allowed direct inside of contract. must needs to create an funtion for that.
