# Degen Token (ERC-20): Unlocking the Future of Gaming
Degen Gaming 🎮, a renowned game studio, has approached you to create a unique token that can reward players and take their game to the next level. You have been tasked with creating a token that can be earned by players in their game and then exchanged for rewards in their in-game store. A smart step towards increasing player loyalty and retention 🧠

To support their ambitious plans, Degen Gaming has selected the Avalanche blockchain, a leading blockchain platform for web3 gaming projects, to create a fast and low-fee token. With these tokens, players can not only purchase items in the store, but also trade them with other players, providing endless possibilities for growth📈

# Introduction
In this project of module 4 of [ETH + AVAX PROOF: Intermediate EVM Course](https://academy.metacrafters.io/content/solidity-avax-intermediate) by Metacrafters our  task is to create a ERC20 token and deploy it on the Avalanche network for Degen Gaming. The smart contract should have the following functionality:
* Minting new tokens: The platform should be able to create new tokens and distribute them to players as rewards. Only the owner can mint tokens.
* Transferring tokens: Players should be able to transfer their tokens to others.
* Redeeming tokens: Players should be able to redeem their tokens for items in the in-game store.
* Checking token balance: Players should be able to check their token balance at any time.
* Burning tokens: Anyone should be able to burn tokens, that they own, that are no longer needed.

# Getting Started
## Installing
1. Copy the file DegenGamingToken.sol from this repo and paste it in your [Remix IDE](https://remix.ethereum.org/).
2. You can change the name and symbol for your own token and add your own functions if you wish to!!!!

## Executing Program
1. Open this link in your browser to connect you metamask wallet with Avalanche Fuji network: https://core.app/en/tools/testnet-faucet/
2. Scroll down on click on "Add Subnet to Wallet" and choose the address on which you want to deploy your contract.
3. Refresh the page and paste your address and in coupon code write "avaxstrong" and click on "Request 2 Avax".
4. In deploy section of Remix IDE choose environment as "Injected Provider- MetaMask" and choose account on which you connected the Fuji Network.
5. Then Deploy your transcations and perform the actions of your smartcontract and confirm all the metamask transactions.
6. Open the [Snowtrace Testnest](https://testnet.snowtrace.io/) and paste the address on which yo deployed the contract and search for it. You will be able to see your all transactions there !!!

# Help
If You face any error please ensure the following steps:
1. Ensure you have written the correct pragma solidity version ```pragma solidity ^0.8.20;```
2. Ensure the your account on which you are deploying the contract should connected to metamask.
3. Insure to import the files for ERC20 token:
   ```
   import "@openzeppelin/contracts/token/ERC20/ERC20.sol";
   import "@openzeppelin/contracts/access/Ownable.sol";
   import "@openzeppelin/contracts/token/ERC20/extensions/ERC20Burnable.sol";
   ```
4. Ensure to change the test network to Fuji network.

# Author
Rahul Berwal <br /> 
[tobiasrahul](https://github.com/tobiasrahul)

# License
This project is licensed under the MIT License - see the LICENSE.md file for details
