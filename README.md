# KaseiCoin

Objective: To create Solidity code files using blockchain technology to define a new cryptocurrency, named KaseiCoin.  KaseiCoin (KS) will be a fungible token and will be ERC-20 compliant. The code will also have a crowdsale contract and a KaseiCoin deployer contract that will allow a user to convert their Ethers to KaseiCoin.
The code will be compiled and deployed in REMIX and validated with a transaction using MetaMask and ganache.
The files with the KaseiCoin Token Contract and KaseiCoin Crowdsale Contract are named KaseCoin.sol and KaseiCoinCrowdslae.sol.  The images shown in the README file can be found in the Image folder of the GitHub repository. 
## KaseiCoin Token Contract

The code starts by defining the KaseiCoin as an ERC 20 token.  First, the OpenZeppelin libraries are imported for ERC20, ERC20 detailed and ERCMintable.  Next, we define the name of the contract as KaseiCoin and connect it to the OpenZeppelin libraries.  I use name, symbol and initial supply as the parameters for this new contract. The contract constructor will also define the Kaseicoin for 18 for the decimal parameter. Finally, the contract was deployed using version 0.5.5 of the compiler.

## KaseiCoin Crowdsale Contract and KaseiCoin Deployer Contract

In this KaseiCoinCrowdsale.sol code file, the KaseiCoin crowdsale contract is defined and the KaseiCoin Deployer Contract is updated.. The code imports the Crowdsale and MintedCrowdsale using OpenZeppelin contracts.  Next, rate, wallet and token are set up as the parameters.

For the KaseiCoin Deployer Contract, (Imbedded in the previous KaseiCoinCrowdsale.sol file)  we add variables to store the KaseiCoin and KaseiCoinCrowdsale contracts. We also create the public addresses needed for deployment. We will use a rate of 1 and set up the wallet and token storage variables. Finally, we set up the minter for the crowdsale.
The contract is the complied using the 0.5.5 version of the compiler and deployed.  

### Compiling, Deployment and Transaction Validation Screenshots

The following screenshots show the successful compiling, deployment of the contracts and subsequent transaction to purchase 15 Kasei Tokens integrating Remix, MetaMask and Ganache.

<img src="/Images/Compileone.png">
<img src="/Images/Compiletwo.png">
<img src="/Images/three.png">
<img src="/Images/four.png">
<img src="/Images/five .png">
<img src="/Images/six.png">
<img src="/Images/seven.png">
<img src="/Images/eight.png">
<img src="/Images/nine.png">
<img src="/Images/ten.png">
<img src="/Images/eleven.png">
<img src="/Images/twelve.png">
<img src="/Images/thirdteen.png">
<img src="/Images/fourteen.png">
<img src="/Images/fifteen.png">
<img src="/Images/sixteen.png">
<img src="/Images/seventeen.png">
<img src="/Images/eighteen.png">
<img src="/Images/twenty.png">
<img src="/Images/twentyone.png">
<img src="/Images/twentytwo.png">
<img src="/Images/twentythree.png">

### Resources ###

UC Berkely Fintech Bootcamp class materials
UC Berkely Fintech Bootcamp Tutoring session 5/14/24 & 5/16/24
