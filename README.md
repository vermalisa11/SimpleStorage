# SimpleStorage
simple storage smart contract
### launch
- npm install -g truffle  =>g for global , install truffle
- truffle init => initialize a truffle project, get truffle_config.js, get version details
- npm init -y => intialise npm project and get all dependencies,  y for yes
- npm install @openzepellin/contracts 

### deploy
- write smart contract in contracts folder
-  2_deploy.js in migrations folder
- truffle develop => launch ganache
- migrate --reset => to compile and deploy, reset flag to delete previous deployments, create build folder 

### test
- write contract.js in tests folder
- truffle test => check the test file 

### frontend
- in public/bundle.js !![[Pasted image 20210514155941.png]] create a web3 instance
-  npm install -g static-server => as decribes in package.json, "scripts": {    "start": "static-server public",
-  npm start => to get the node run

