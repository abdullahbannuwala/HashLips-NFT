## dApp -- Full Stack Web3 developer environment setup

## Steps --cmd commands
1. npx create-react-app dapp
2. cd dapp
3. npm install ethers hardhat @nomiclabs/hardhat-waffle ethereum-waffle chai @nomiclabs/hardhat-ethers
4. npx hardhat
5. Select "Create a basic sample project" Option.
6. Set the hardhat.config.js file configuration --paths + networks(to solve matamask issue)
7. npx hardhat compile
8. Open new terminal node -- run cd dapp & npx hardhat node
9. import the account into matamask with one of the private key
![image](https://user-images.githubusercontent.com/74914096/165829974-0f7990ed-97f6-4d8a-a687-cdf0e231f837.png)
10. change the name of that script to deploy.js
11. npx hardhat run scripts/deploy.js --network localhost
12. npx hardhat test
