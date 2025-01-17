## Header
This is the course header. This will be added on top of every page. Go to [DoDAO.io](https://www.dodao.io) to know more.

 ---
 
 ## Security and Risks
 
 **Introduction to Blockchain**        
- What is Blockhain ?
  * Blockchain are basically software protocols that help multiple parties to work under a set of shared data without trusting each other.
  * These data can be of any form that one can consider.For examples, location destination account information, transaction history of a particular token.
  * The term blockchain emerges from the "chaining" of "blocks" of data crytographically and allowing the audit of prior history.

- Early days of blockchain
  * Blockchain was born 20 years before the world was introduced to Bitcoin.
  * The blockchain technology was introduced by Haber and Stornetta in the year 1991. They invented this technique for efficient time-stamping of digital documents.
  * Adam Back in 2002 invents the idea of Proof of Work idea.
  * Proof of Work was based on the paper work by Cynthia Dwork and Moni Naor (1992) that was aimed at eliminating junk mail.
  * The sender needs to do some computational task before sending the mail. This was easy to do when done once but becomes infeasible to do for millions of recipients.
  * Moreover, Blockchain is not Bitcoin rather Bitcoin employs the technology of Blockchain.  
 
 **Working of Blockchain**        
- Blockchain ledger
  * The ledger which is present in blockchain is more than a simple ledger. This ledger is quickly and easily accessbile by anyone and further shared by many which explains its distributive nature.
  * These ledgers are responsible for process of recording transactions and tracking assets in a business network.
  * These are responsible for storing data and assets such as tangible (a house, car, cash, land) or intangible (intellectual property, patents, copyrights, branding).
  * Blockchain ledger is distributed. All network participants have access to the distributed ledger and its immutable record of transactions.
  * Due to this distributed mechanism the transactions are recorded only for once, eliminating the duplication of data something which is very frequent in traditional business mechanisms.
  * Tampering or changing these transactions in the ledger is impossible for a particiapnt to do so.
  * Thus, these records ensure proper immutability.

- Blockchain Transactions and Blocks
  * Whenever a transaction occurs it is stored as a "block" of data.
  * These transactions show the movement of assets tangible (a product) or intangible (intellectual).
  * These data blocks store a variety of information such as who, what, when, where and also conditions such as temperature.
  * Each block is connected to one before and after it. The blocks represent the flow of ownership of some data.
  * Each of these blocks have a hashed reference to the block before it so you can trace every transaction all the way back to genesis block.
  * These block are securely linked to each other to prevent any block from being altered or a block being inserted between two existing blocks.
  * Blockchain hashes are highly secure. They strengthen the verification of the previous block and hence the entire blockchain.
 
 **Types of Blockchain Networks**        
These blockhain networks can be primarily of `four` types : `Public`, `Private` , `Permissioned` and `Consortium`.

- Public Blockchain Network
  * A network where anyone can join and participate in such as Bitcoin.
  * This network needs a lot of computational power.
  * Little or no privacy for transactions and weak security.
  * Generally used by enterprise blockchain.

- Private Blockchain Network
  * Similar to Private, it is a decentralised peer-to-peer to network.
  * One organisation governs the network and controls who is permitted to participate in the network.
  * This organisation provides consensus protocol and maintain the shared ledger.
  * A private blockchain can be run behind a corporate firewall and even be hosted on premises.

- Permissioned (Hybrid) Blockchain Network
  * Businesses who setup private Network also setup a permissioned blockchain network.
  * Public blockchain can be permissioned.
  * Sets up restrictions on who is allowed to participate in the network and in what transactions.
  * Participants need to obtain an invitation or permission to join.

- Consortium Blockchain Network
  * Multiple organisations can share the responsibilities to share the blockchain.
  * These pre-selected organizations determine who may submit transactions or access the data.
  * A consortium blockchain is ideal for business when all participants need to be permissioned.
 
 **Hashing**        
- What is Hashing ?
  * A cryptographic hash function is an computational algorithm that takes an arbitrary amount of data input—a credential—and produces a fixed-size output of enciphered text called a hash value, or just hash.
  * The process of creating this hash value is known as Hashing. 
  * That enciphered text can then be stored instead of the password itself, and later used to verify the user.
 
 **Properties of Hashing**        
- Non Reversibility - One way functions
  * A good hash makes it impossible to crack the original password from the output or hash.

- Diffusion or Avalanche Effect
  * If there is a change in one bit of the original password then it should result change in half of the bits of its hash.
  * This means even the smallest change in the original text brings about significant and unpredictable changes.

- Deterministic 
  * A given password must generate the same hash value or enciphered text whenever the same input is being passed to it.

- Collision Resistance
  * When two different inputs give the same hash value it is known as collision.
  * It should be hard to find two different passwords that hash to the same enciphered text. 
  * A good hash is considered to have a lot of zeros as the starting of the hash.

- Non-predictable
  * It should not be obvious enough to derive original text from the hash value. 
  * Hence the original text must be unpredictable. 
 
 **Merits and Demerits of Hashing**        
- The Good Effects
  * Cryptographic hashes take in clear and simple text passwords and convert them into enciphered text for storage.
  * It becomes difficult for Attackers to decipher original text from the hash value if they wish to exploit that information. Thus hashing creates great deal of security. 

- The Bad Effects
  * Attackers who have fast hardware can easily "crack" hash values to original text.
  * Good hash alogrithms are made to be collission resistant. But it is impossible to eliminate collissions completely. Algorithms like MD5 , SHA-1 are known to contain collsions-produce same hash value for two different input credentials.
  * Rainbow tables are “optimized lookup tables” that can be used to reverse-engineer one-way hash functions. A rainbow table is basically a pre-computed set of plaintext strings and their corresponding hashes.
  *  Large rainbow tables are publicly available, and attackers can use one of these tables to retrieve cleartext data that has been hashed.
 
 **Popular Hashing Algorithms**        
- SHA-256 
  * SHA stands for Secure Hashing Algorithm. It is one of the most secured hashing algorithm currently available.
  * SHA-256 is a successor SHA-2, which was created by National Security Agency in 2001.
  * SHA-256 is a patented cryptographic hash function that outputs a value that is 256 bits long.
  * It is built with a Merkle-Damgard structure.
  * Bitcoin employs SHA-256 as its hashing algorithm.

- Keccak-256 (SHA-3 Family)
  * Keccak has arbitrary input and infinite input space.
  * Employed to create hashes for very big files.
  * Results in 32 bytes data type as the result.
  * Ethereum uses Keccak-256 as its hashing algorithm.
 
 
