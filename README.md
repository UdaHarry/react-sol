# react-sol

### Playlist
1. *[Full Stack Hello World Voting Ethereum Dapp Tutorial — Part 1](https://medium.com/@mvmurthy/full-stack-hello-world-voting-ethereum-dapp-tutorial-part-1-40d2d0d807c2)*
2. *xxxxx*

### CLI Use
1. Install gnache-cli :\
    `npm install ganache-cli web3@1.2.6`
2. Gnache Account :\
    `node_modules/.bin/ganache-cli`
3. Install Solc :\
    `npm install solc@0.6.4`
4. Compiling Voting.sol :\
    `node_modules/.bin/solcjs --bin --abi Voting.sol`
5. a

### Information
1. Compiling Voting.sol
``` 
    When you compile the code successfully using the command above,
    the compiler outputs 2 files that are important to understand:

    1.  Voting_sol_Voting.bin: This is the bytecode you get when the source
        code in Voting.sol is compiled. This is the code which will be deployed
        to the blockchain.

    2.  Voting_sol_Voting.abi: This is an interface or template of the contract
        (called abi) which tells the contract user what methods are available in the
        contract. Whenever you have to interact with the contract in the future,
        you will need this abi definition. You can read more details about ABI here
```