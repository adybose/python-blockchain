# python-blockchain
A simple blockchain implementation in Python using the Flask micro framework along with HTML, Bootstrap and jQuery.

The implementation has 2 parts:
- A blockchain client to generate wallets and transactions
- A blockchain p2p server with nodes to broadcast and view transactions, mine blocks, etc.

Generation of wallets is offline. So is generation of a transaction.
But to add/propagate the transaction in the  blockchain, we need to run a blockchain server or p2p-node.

## Usage
- Clone the repository and navigate to the root
- Run the blockchain client with `python blockchain-client/blockchain_client.py`
- Run multiple blockchain nodes with `python blockchain/blockchain.py -p <PORT_NUMBER>`
