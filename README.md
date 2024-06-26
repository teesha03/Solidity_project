# My Token Contract

This is a simple ERC20 token contract written in Solidity. It has the following features:
- Public variable to store the token name, abbreviation and total supply
- a mapping of addresses to balances
- a mint function to increase the total supply and balance of a specified address
- a burn function to decrease the total supply and balance of a specified address

## Getting Started

### Usage

To use this contract, simply deploy it to the Ethereum blockchain and interact with it using the `mint` and `burn` functions.

```javascript
// Mint 100 tokens to address 0x123456...
myToken.mint(0x123456..., 100);

// Burn 50 tokens from address 0x123456...
myToken.burn(0x123456..., 50);

```

## License

This project is licensed under the MIT License.
