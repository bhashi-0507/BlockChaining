# BlockChaining
#Step 1: Importing Libraries
The first step is to import the required libraries. We will be using the hashlib library to create a cryptographic hash of the blocks, and the datetime library to timestamp each block.

#Step 2: Creating the Block Class
Next, we will create a Block class that will define the structure of each block in the blockchain. Each block will have the following attributes:

Index: This is the position of the block in the blockchain.
Timestamp: This is the time at which the block was added to the chain.
Data: This is the data that is stored in the block.
Previous Hash: This is the cryptographic hash of the previous block in the chain.
Hash: This is the cryptographic hash of the current block.

#Step 3: Creating the Blockchain Class
   Now, we will create a Blockchain class that will define the structure of the blockchain. Each blockchain will have the following attributes:
Chain: This is the list of blocks in the blockchain.

#Step 4: Testing the Blockchain
     Now that we have defined the Block and Blockchain classes, let’s test our blockchain by creating some blocks and adding them to the chain.
     
As we can see, the blockchain has been successfully created and we have added some blocks to it. The hash of each block is based on the data of the block and the hash of the previous block, which ensures the integrity and security of the blockchain.
