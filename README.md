# StarNotary-Ethereum
**Decentralized Star Notary (DAPP on Ethereum)**
****
StarNotary smart contract allows for the ownership and transfer of stars, that is deployed on the Rinkeby public test network. The star notary contract is inherited from ERC721 , that is a minimum interface smart contract that allows for unique tokens to be managed, owned and traded.
****
**Contract Functions**  
--- 
### Name and Symbol 
    string public constant name   = "NotaryStar";
    string public constant symbol = "NSR";
### exchangeStars  
### transferStar
### lookUptokenIdToStarInfo
****
**Frontend**  
---  
![image](https://github.com/DavidCLi/StarNotary-Ethereum/blob/master/pics/Frontend.JPG)
****  
### Quick Start
    npm install
    truffle compile
    truffle migrate --network development  --reset --all / truffle migrate --network rinkeby  --reset --all
    truffle test
    npm run dev
****  
**DAPP information**  
Truffle version: v5.0.28 (core: 5.0.28)  
OpenZeppelin version: v2.1.2  
ERC-721 Token Name: NotaryStar  
ERC-721 Token Symbol: NSR  
Token Address on the Rinkeby Network: 0xDfe0fB6fC1956Bc53850F24B6a185370C388B9dc  
