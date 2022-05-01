- Download https://trufflesuite.com/ganache/
- Install truffle@5.0.2 npm module.
- Create the file smart contract file -> contracts/file.sol
- Compile the smart contract -> sudo truffle compile. 
- JSON representation of the smart contract will be created -> build/contracts/file.json
    - bytecode -> run on ETH virtual machine
- Create the migration file to get Smart Contract on the Blockchain.
    - Eqivalent to Database DDL
    - Each deployment of SC modifies the Blockchain State
    - Blockchain is nothing but the database.
- Deploye the smart contract -> sudo truffle deploy.
    - It will bring down the ETH on Ganache. Means deployment SC to the Blockchain costs some ETH, need some gas.
    



