# Token Management System

The program is designed to facilitate token management on the Ethereum blockchain. It enables users to create (mint) and destroy (burn) tokens based on specific conditions. The main purpose is to provide a foundational understanding of token operations and to serve as a basic template for more complex token management systems.

## Description

This project comprises a basic Ethereum token contract named `Token` that enables the creation and destruction of tokens. The contract allows users to mint tokens to a specified address and burn tokens based on certain conditions. It is a simplistic representation of a token management system built in Solidity.


## Getting Started

### Installing

* Clone this repository to your local machine.

### Executing program

1.) Deployment:

Deploy the contract on the Ethereum blockchain using tools such as Remix or Truffle.

2.) Interaction:
Interact with the deployed contract by calling its functions using an Ethereum wallet or development environment.

3.) Mint Tokens:
Use the mint function to create new tokens. Provide the address where the tokens will be minted and the value to be added.

4.) Burn Tokens:
Utilize the burn function to destroy tokens. Specify the address from which tokens will be burned and the amount to be subtracted.

	Ensure that you have the necessary gas fees and proper network configurations set up to successfully execute the program.

```

Code blocks for commands:

// Mint tokens to an address
Token.mint(address, value);

// Burn tokens from an address
Token.burn(address, value);

## Help

If you encounter any issues during deployment or execution, ensure that you have the appropriate gas fees and proper network settings configured. Additionally, make sure your Ethereum wallet or development environment is compatible with the Solidity version used in this contract.

Advice for common problems or issues:
- Double-check the address and value parameters while minting or burning tokens.
- Ensure that the address has a sufficient balance before burning tokens.

Command to run if the program contains helper info:
Token.help()

## Authors

Contributors names and contact info

Charles Christian O. Sapida  
[csapida1](https://www.facebook.com/csapida1)


## License

This project is licensed under the [Charles Christian Sapida] License - see the LICENSE.md file for details
