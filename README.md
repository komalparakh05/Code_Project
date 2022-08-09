# Blockchain
Decentralised Twitter
This is the repository to contain DecTweet app which is a Twitter Clone using React and Solidity.

first make two different directories for backend and front end
started working with back end

-> npm init
-> npx hardhat
-> npm install ethers hardhat @nomiclabs/hardhat-waffle \
 ethereum-waffle chai @nomiclabs/hardhat-ethers \
 @openzeppelin/contracts dotenv
 -> npx hardhat
 
 Then writing solidity programs and running following commands for unit test.
 
 -> npx hardhat test
 
 Deploying it on Rinkeby testnet 
 
 -> npx hardhat run scripts/deploy.js --network rinkeby
 
 Start working on front end
 
 ->  npx create-react-app frontend
 
 installing important features
 
 -> npm install axios ethers
 -> npm install @material-ui/core
 -> npm install @material-ui/icons
 -> npm install avataaars
 -> npm install --save react-twitter-embedded-timeline
 -> npm install --save react-flip-move
 
 After completion of front end styling, type following command to run front end server
 
 ->npm start
 
