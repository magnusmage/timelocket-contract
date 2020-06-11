Open Command Line Shell inside root directory of project and then perform following steps


Step 1. Install require modules
1. You need npm
https://www.npmjs.com/get-npm
npm install npm@latest -g

2. install truffle:
http://truffleframework.com/
npm install -g truffle

3. install npm packages
npm install


4. Compile Truffle Project
truffle compile


5. Migrate Truffle Project

truffle migrate --reset --network development



After last command 1 contracts will be deployed. For Live you need to change at your side and deploy contract.

After response visible on command shell, you can see three transaction hashes , you can search it on rinkeby.etherscan.io for verification.
