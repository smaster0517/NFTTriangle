## NFT Marketplace on Ethereum

### Install dependencies
```
yarn add ethers hardhat @nomiclabs/hardhat-waffle ethereum-waffle chai @nomiclabs/hardhat-ethers web3modal @openzeppelin/contracts ipfs-http-client axios
yarn add -D tailwindcss@latest postcss@latest autoprefixer@latest
```
### Run app
```
yarn dev
```
### Compile & Test
```
npx hardhat compile
npx hardhat test
```
### Deploy to localhost
```
npx hardhat node
npx hardhat run scripts/deploy.js --network localhost
```
### Deploy to testnet
```
npx hardhat run scripts/deploy.js --network mumbai
```

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```
