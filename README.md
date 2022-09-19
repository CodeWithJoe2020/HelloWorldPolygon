# HelloWorldPolygon
Simple Hello World contract on polygon with alchemy

1. Sign up for Account on Alchemy.com https://bit.ly/3x67pnF   
1.1 Get API Key from alchemy
2. Install Nodejs
3. Install Npm
4. Get metamask wallet  - www.metamask.io


5. in metamask connect to 
Network Name: Polygon Mumbai Testnet
New RPC URL: https://polygon-mumbai.g.alchemy.com/v2/yourAPIKEY   - from alchemy.com
ChainID: 80001
Symbol: MATIC
Block Explorer URL: https://mumbai.polygonscan.com/


6. Get Free Mumbai testnet Token
https://faucet.polygon.technology/

#NodeJs Hardhat 
Make sure nodeJs and npm is installed!!

1. create project folder
for example hello-world 
1.1 run npm init
1.2 install hardhat:  npm install --save-dev hardhat   and than run  npx hardhat
1.3 create 2 folders: contracts & scripts
1.4 create .env file,  run npm install dotenv --save and than create .env in /root/ folder
1.5 Get Alchemy API key & Privatekey from metamask and put them inside your .env file

2. Inside the hello-world/contracts folder create a HelloWorld.sol file (copy from repository)
