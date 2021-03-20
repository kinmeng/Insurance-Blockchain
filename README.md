# Insurance Blockchain Application

This repository is forked from sijo0703/PythonEthereumSmartContracts as linked and modified for the project's purpose

In case the setup instructions don't work, please refer to this link: 
https://medium.com/swlh/develop-test-and-deploy-your-first-ethereum-smart-contract-with-truffle-14e8956d69fc

Setup environment
python3 -m venv <env name>
source <env_name>/bin/activate to activate virtual environment

Setup instructions:
Major modules required for this project
1. Install NodeJS (https://nodejs.org/en/) used for compilation
Installation guide: https://www.geeksforgeeks.org/installation-of-node-js-on-linux/
3. Install Truffle
npm install -g truffle
3. Install Ganache
4. Setup the necessary flask modules 
5. Run pip3 install web3

Three main parts to modify this project:
1.Create solidity project file, put in the folder ./contracts (make sure it's tested on remix)
2. If it's the first time you are using truffle, run truffle init
3. Subsequently, simply run "truffle compile" and "truffle migrate" which will create a JS deployment file which you do not need to edit

Now, run flask by issuing the command python3 insurance.py

Take note:
1. Everytime Ganache is restarted, you should change the private key address in the insurance.py file
2. To find a key for use, you need to replace the address with your own private key from Ganache.
Open up Ganache > for each ADDRESS you can find a corresponding key icon on the right. Click on it and you will find a private key. Replace the key where appropriate in the code



