# tokenRaj Smart Contract

This is a basic implementation of an ERC-20 token smart contract called MyToken, written in Solidity language. The contract includes functionality for minting and burning tokens, as well as a mapping of addresses to balances.


## Requirements

1. The contract has public variables for storing the details about the token, such as its name, abbreviation, and total supply.
2. The contract has a mapping of addresses to balances, which allows for keeping track of token ownership and transactions.
3. The contract includes a mint function, which increases the total supply by a given amount and increases the balance of the sender address by the same amount.
4. The contract includes a burn function, which decreases the total supply by a given amount and decreases the balance of the sender address by the same amount.
5. The burn function includes conditionals to make sure that the balance of the sender address is greater than or equal to the amount that is supposed to be burned.


## Usage

This is just a basic smart contract. But this learning is a game changer for me.

To use this smart contract, you can deploy it on a blockchain platform that supports Solidity smart contracts, such as Ethereum or Binance Smart Chain. Once deployed, you can interact with the contract by calling its functions from a wallet or a DApp.

The mint function can be used to add tokens to the supply, while the burn function can be used to remove tokens from the supply. The balances mapping can be used to check the balance of a specific address.