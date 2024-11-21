# blockchain-workshop-setup

## NPM and NodeJs
Make sure you have valid versions or install:
* npm >= 7.10.0
* NodeJs >= 16.0.0
* https://docs.npmjs.com/downloading-and-installing-node-js-and-npm

## Hardhat 
* In a new project folder, run
  ```npm install --save-dev hardhat```
* ```npx hardhat init```
* Start the blockchain by ```npx hardhat node```

## Remix IDE
https://remix.ethereum.org
* Click "Deploy and run transactions"
* <img src="https://github.com/user-attachments/assets/9ab6535b-f7e3-4e4d-8f32-53bdf889468e" width="300">
* Under "Environment", select "Dev - Hardhat provider"
* <img src="https://github.com/user-attachments/assets/ca857690-fa9f-440a-abf0-64dc32a961b1" width="300">
* Address should be ```http://127.0.0.1:8545```. Click OK.
* The Remix IDE is now connected to your locally running blockchain and you are ready to deploy and test contracts.


  
