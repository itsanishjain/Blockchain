# How to create your first DAPP - Decentralized Application

### Workign App

https://itsanishjain.github.io/Blockchain/

# Tools needed

- Remix IDE
- Metamask
- Testnet Faucet

Go theh Remix IDE and create a new project.
name your project: DappOne.sol

This is Soldity's Code which is a smart contract. and it is deployed on the Rinkeby Testnet.

```
// SPDX-License-Identifier: MIT

pragma solidity ^0.8.1;

contract Mood{
    uint256 public number;

    // set a number to a blockchain
    function setNumber(uint256 _number) public {
        number = _number;
    }

    // get a number from a blockchain
    function getNumber() public view returns(uint256){
        return number;
    }
}

```

## Deploying the contract

- Click the "Deploy" button

## GETTING THE CONTRACT ADDRESS

- Click the "View Contract" button
- Copy the address

## GETTING THE CONTRACT ABI

    - Click the Solidity Compiler button
    - Click on Complition Details
    - Copy the ABI

Save Address AND API in a file. You need them for the next steps.

## Create index.html

- you need to create an index.html file for your Dapp interface
  - copy the code form index.html file
  - paste the code in the index.html file
  - save the file

## Run the Dapp

- Need a live server to run the Dapp
- So install vscode extension "Live Server"
- Click on live-server button at the bottom of the screen

## References

- ### Code

  - https://github.com/BlockDevsUnited/BasicFrontEndTutorial

- https://www.youtube.com/watch?v=M576WGiDBdQ [To learn how More about Solidity,Remix IDE,Metamask,Testnet Faucet]

- follow this Guy
  https://twitter.com/Haezurath

## Thanks

    https://twitter.com/Haezurath
    Github Copilot for the amazing autocompletion

## Final words

I know it seems simple but we learn a lot. about Smart Contracts and Dapps. and basics of solidity.
there a tones of resource out there so I will try to share them.Thnaks
