# Go-Ethereum-Basic-Commands
Basic geth commands

### To execute a command:

`./file_name.sh`

### If necessary on Linux, change the permissions to each file:

`chmod +x file_name.sh`

# List of each file command:

- ## generate.account
### Generates a wallet keyfile with the provided password on the path ./dir/keystore 

- ## list.account

### Lists the account files on the ./dir/keystore directory

- ## live.miner

### Activates the miner at the 0 index wallet. If you want to specify an address, try the following command: geth --identity "minerNode" --fast --mine --etherbase < YOUR-ADDRESS >

- ## testnet.rpc

### Opens a javascript console on the rinkeby testnet with JSON rpc access on localhost:8545

- ## testnet

### Opens a javascript console on the rinkeby testnet

- ## net

### Opens a javascript console on the live ethereum network

- ## net.rpc

### Opens a javascript console on the ethereum live network with JSON rpc access on localhost:8545
