
# Defender Dao

DefenderDao , its a Decentralized Autonomous Organization, the main goal is protect the Web3 ecosystem from scammers and malicious bad actors , allowing Defenders vote for blacklisted and build a decentralized database including phishing Urls , scam tokens and  any  bad actor who put in risk the ecosystem users.  


## Features

- Erc20 Voting  (https://docs.openzeppelin.com/contracts/4.x/api/token/erc20#ERC20Votes)
- Snapshots (https://docs.openzeppelin.com/contracts/4.x/api/token/erc20#ERC20Snapshot-Snapshot-uint256-)
- Timelock Managment (https://docs.openzeppelin.com/contracts/4.x/governance#timelock)
- Governor from OpenZeppelin (https://docs.openzeppelin.com/contracts/4.x/governance)
- Compound compatible (https://docs.openzeppelin.com/contracts/4.x/governance)
- Tally supported (https://docs.openzeppelin.com/contracts/4.x/governance)


## DefenderDao Appendix

DefenderDao project , its a non production project demostrating a Dao functionality , the project was done with help Openzeppelin library , the logic for the DAO is follow:

- User fill a form  for join the DAO and grab tokens
- User have a metemask wallet and use rinkeby testnet
- User connect wallet to our Dapp or Tally 
- User delegate votes himself or  to another wallet .
- User start voting or creating a  proposal.

 


## Tech Stack

**Client:** React, Etherjs , Tally

**Backend:** Node,hardhat,solidity,Ethereum EVM


## Testnet Smart Contracts Deployed

can check deployment on Rinkeby Etherscan

DefenderToken

```bash
  https://rinkeby.etherscan.io/address/0x3b9DDa9a2e6FA88A2402105C4fEb0b044F71Ff5c
```

Timelock
```bash
  https://rinkeby.etherscan.io/address/0x767fa811cAc7c211bDFD226FE4856f9256bF276f
```

DefenderGovernor
```bash
  https://rinkeby.etherscan.io/address/0x039e6a8D47Bf0db69476B567C80eE1bb6ab6e0eE
```
DefenderBox
```bash
  https://rinkeby.etherscan.io/address/0x29027C6Ba306B61212Ee26531B6aF804d26DD961
```




## Demo


Dapp 

https://dreamy-speculoos-e8196d.netlify.app/

DAO  https://www.tally.xyz/governance/eip155:4:0x039e6a8D47Bf0db69476B567C80eE1bb6ab6e0eE


## Run Locally

Clone the project

```bash
  git clone https://github.com/DefenderDao/defenderdao-contracts.git
```

Go to the project directory

```bash
  cd defenderdao-contracts
```

Install dependencies

```bash
  yarn install
```

Start the server

```bash
  yarn hardhat run --
```


## Roadmap

- Integration with frontend Dapp

- Build the graph api for  start creating a phishing and scammer urls database

- Testing 

- Unit testing 

- Build Treasury


## Authors

- [@mivgubel](https://github.com/mivgubel)
- [@technoGecko](https://github.com/TechnoGecko)
- [@robtabamo9292](https://github.com/robtabamo9292)
- [@0xefrain](https://github.com/0xefrain)



##  Special Acknowledgements

 - [Encodeclub Bootcamp](https://www.encode.club/encode-bootcamps)
 - [Our amazing tutor Matheus ](https://github.com/MatheusDaros)
 


## License

[MIT](https://choosealicense.com/licenses/mit/)

