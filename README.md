# Client-Side-Relayer-with-ERC-4337-Compatibility

This is a project addressing the problems of the Wormhole Client Side Relayer. In spite of its benefits, its still restricted by the following problems: 
1. Users must sign all transactions required with their own wallet.
2. Users must have funds to pay the transaction fees on every chain involved.

ERC-4337 addresses these difficultties by providing :
1. Payment Abstraction - through a Paymaster smart contract.
2. Signature abstraction - The use of Smart Contract Wallets to eliminate overeliance on ECDSA and introduce multisignatures. 
