# To-Do using Solidity, Hardhat and React
To-Do DApp (Decentralized Application) is a web application that allows users to manage tasks on the blockchain. It uses React for the front-end interface, providing a responsive and interactive user experience. Solidity is used to write smart contracts that run on the Ethereum blockchain, ensuring data integrity and decentralization. Users can add, update, and delete tasks, with all actions recorded on the blockchain for transparency and security. This combination leverages the power of decentralized technology to create a reliable and tamper-proof task management system.

This app is provides a simple implementation of ToDo using Solidity, Hardhat and React.
##### Technology/Tools
- HardHat (for local Node and deployment) 
- Solidity (for contracts)
- React and NodeJs (for Frontend)
- Metamask (for transactions)

#### Installation

This app recommends [Node.js](https://nodejs.org/) v16+ to run.

Go to root in directory. Run npm following commands for dependencies installation and run: 

```sh
npm i
npm start
```
Open new terminal and run following commands:
```sh
npx hardhat compile
npx hardhat node 
```
Open new terminal and run following command to deploy contract:
```sh
 npx hardhat run scripts/deploy.js --network localhost
```
Now install Metamask and connect with http://localhost:8545
