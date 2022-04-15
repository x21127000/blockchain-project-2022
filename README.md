# Blockchain Concepts and Technologies Project Assignment CA1.

### Introduction

It is a dockerize node js application that shares 5% of the remaining token amount with all accounts in the file.This project does the following: 

* Reads a file which includes 10 different Ethereum accounts
* Calculate total supply for owner account
* Calculate %5 of remaning balance 
* Distribute to each of Ethereum accounts in the file.

#### Requirements:
  * Docker
  * Node (Version 16)
  * Code Editor
  * Npm
  
Clone Code
```
git clone https://github.com/x21127000/blockchain-project-2022.git

```
 
Install dependencies
```
npm install

```

Edit x2112700-Contract.sol file with your token information. And deploy token contract to network using REMIX


Edit conract.js with your ABI from deployed contract, Infura token, Contract address, Ethereum address. 

Check contract and ropsten network

```
node contract.js

```
 
Distribute the token
```
node distribute.js

```

# For Testing with image you can pull and run the my image. 
### Pulling docker image

docker pull x21127000/blockchain-project:0.0.4

### Run the docker image
docker run -ti x21127000/blockchain-project:0.0.4


