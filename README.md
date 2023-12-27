# Blockchain-with-Transactions
Combining transactions with block creation in a blockchain.
class Block:
    def __init__(self, index, previous_hash, timestamp, transactions, proof, hash):
        self.index = index
        self.previous_hash = previous_hash
        self.timestamp = timestamp
        self.transactions = transactions
        self.proof = proof
        self.hash = hash

# Assume create_genesis_block and create_new_block functions include transactions
