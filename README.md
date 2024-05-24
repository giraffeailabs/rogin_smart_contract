## Install
### URL : https://www.npmjs.com/package/hardhat

if your node version is too low. please upgrade your node version > 14.*.*
```shell
nvm install 18
nvm use 18
npm install -g hardhat
npm install
npm install @openzeppelin/contracts
```
## Compile
```shell
npx hardhat compile
```

## Deploy (If you add new network, Please add something in "hardhat.config.js")
```shell
npx hardhat run --network local scripts/deploy.js
npx hardhat run --network goerli scripts/deploy.js
npx hardhat run --network mainnet scripts/deploy.js
npx hardhat run --network baobab scripts/deploy.js
npx hardhat run --network klaytn scripts/deploy.js
```

## Clean(Option)
```shell
npx hardhat clean
```