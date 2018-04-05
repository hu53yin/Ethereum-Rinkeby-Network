# Ethereum Rinkeby Test Network
Running Ethereum on Rinkeby-test-network by step by step instructions

1) Create your Ethereum project folder.
2) Create an empty folder it given "chaindata" name.
3) Start geth on Rinkeby network with this command:
  geth --rinkeby --ipcpath <YourProjectFolderPath>/chaindata/geth.ipc
  
  Example:
  geth --rinkeby --ipcpath /Users/huseyingurkan/Documents/Projects/ethereum-rinkeby/chaindata/geth.ipc

4) And then start your Mist wallet:
  /Applications/Mist.app/Contents/MacOS/Mist --rpc <YourProjectFolderPath>/chaindata/geth.ipc
  
  Example: 
  /Applications/Mist.app/Contents/MacOS/Mist --rpc /Users/huseyingurkan/Documents/Projects/ethereum-rinkeby/chaindata/geth.ipc
  
  !!!Attention!!! : For security reasons, I recommend to use Ethereum Wallet app.

5) Also, you can use Ethereum Wallet app on Rinkeby network:
  /Applications/'Ethereum Wallet'.app/Contents/MacOS/'Ethereum Wallet' --rpc <YourProjectFolderPath>/chaindata/geth.ipc
  
  Example: 
  /Applications/'Ethereum Wallet'.app/Contents/MacOS/'Ethereum Wallet' --rpc /Users/huseyingurkan/Documents/Projects/ethereum-rinkeby/chaindata/geth.ipc

https://www.rinkeby.io/#stats
