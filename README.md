# Smart Contract

The Assessment.sol is a Solidity smart contract designed for basic fund management on the Ethereum blockchain. It features functionalities such as depositing and withdrawing funds, ownership control, and event logging. The contract is created to provide a simple and secure way to manage balances and transactions.

## Description

## Assessment.sol

`Assessment.sol` is a Solidity smart contract tailored for basic financial transactions on the Ethereum blockchain. It ensures secure ownership control, allowing only the designated owner to manage funds. Users can deposit and withdraw funds, with events logged for transparency. The contract provides a simple balance query functionality, and a custom error prevents withdrawals that exceed the available balance.

## index.js

`index.js` complements `Assessment.sol` by offering a user interface through a React-based decentralized application (DApp). Integrated with MetaMask, the DApp enables users to connect their wallets, view account details, and perform transactions. Real-time balance updates and a responsive design enhance user experience, making this DApp an accessible solution for basic financial interactions on Ethereum. Ideal for educational purposes and as a foundation for more advanced decentralized applications.

## Getting Started

### Executing program

To run this program, you can use gitpod, an online Solidity IDE. To get started, go to this website https://gitpod.io/new/#https://github.com/MetacrafterChris/SCM-Starter it is already in template you just need to copy the two file and replace it which is the Assessment.sol and index.js you can find Asessment.sol in contract folder while index.js is in pages.

1. Inside the project directory, in the terminal type: npm i
2. Open two additional terminals in your VS code
3. In the second terminal type: npx hardhat node
4. In the third terminal, type: npx hardhat run --network localhost scripts/deploy.js
5. Back in the first terminal, type npm run dev to launch the front-end.

After this, the project will be running on your localhost. 
Typically at http://localhost:3000/

Now you can acccess the web we should start setting up our metamask wallet go to settings of your metamask wallet click Networks->Add network-> and Manually Add Network, now input this on each field:

Network name:
Localhost gitpod
New RPC URL:
https://8545-metacrafterc-scmstarter-rex3mysx58o.ws-us106.gitpod.io
Chain ID:
31337
Currency symbol:
ETH
Block explorer URL (Optional) (Leave this blank)

## Help

If you encounter any issues or have questions, feel free to open an issue on the GitHub repository.

## Authors

Contributors names and contact info

Charles Christian O. Sapida  
[csapida1](https://www.facebook.com/csapida1)


## License

This project is licensed under the [Charles Christian O. Sapida] License - see the LICENSE.md file for details
