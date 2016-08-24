# eReputation
A solidity smart contract based reputation system with UI

currently deployed on the ethereum testnet network:

###Contract address: 0x2df0e16b4122cc14dabe5d6ecb2ae24bc9d48dc1

###var contract = web3.eth.contract([{ "constant": false, "inputs": [{ "name": "vendor", "type": "address" }], "name": "trade", "outputs": [], "type": "function" }, { "constant": false, "inputs": [{ "name": "username", "type": "string" }, { "name": "location", "type": "string" }], "name": "addUser", "outputs": [{ "name": "", "type": "string" }], "type": "function" }, { "constant": false, "inputs": [], "name": "burnCoins", "outputs": [{ "name": "", "type": "uint256" }], "type": "function" }, { "constant": false, "inputs": [{ "name": "vendor", "type": "address" }, { "name": "isPositive", "type": "bool" }, { "name": "message", "type": "string" }], "name": "giveReputation", "outputs": [], "type": "function" }, { "constant": false, "inputs": [{ "name": "user", "type": "address" }], "name": "showBurnedCoins", "outputs": [{ "name": "", "type": "uint256" }], "type": "function" }, { "constant": false, "inputs": [{ "name": "burner", "type": "address" }, { "name": "value", "type": "uint256" }], "name": "burnedBitcoin", "outputs": [{ "name": "", "type": "uint256" }], "type": "function" }, { "constant": false, "inputs": [{ "name": "user", "type": "address" }], "name": "viewReputation", "outputs": [{ "name": "", "type": "uint256" }, { "name": "", "type": "uint256" }, { "name": "", "type": "uint256" }], "type": "function" }, { "anonymous": false, "inputs": [{ "indexed": true, "name": "user", "type": "address" }, { "indexed": true, "name": "amountBurned", "type": "uint256" }], "name": "_coinsBurned", "type": "event" }, { "anonymous": false, "inputs": [{ "indexed": true, "name": "user", "type": "address" }, { "indexed": true, "name": "message", "type": "string" }], "name": "_positiveReputation", "type": "event" }, { "anonymous": false, "inputs": [{ "indexed": true, "name": "user", "type": "address" }, { "indexed": true, "name": "message", "type": "string" }], "name": "_negativeReputation", "type": "event" }, { "anonymous": false, "inputs": [{ "indexed": true, "name": "username", "type": "string" }, { "indexed": true, "name": "location", "type": "string" }, { "indexed": true, "name": "user", "type": "address" }], "name": "_addUser", "type": "event" }, { "anonymous": false, "inputs": [{ "indexed": true, "name": "vendor", "type": "address" }, { "indexed": true, "name": "buyer", "type": "address" }], "name": "_newTrade", "type": "event" }, { "anonymous": false, "inputs": [{ "indexed": true, "name": "user", "type": "address" }, { "indexed": true, "name": "positive", "type": "uint256" }, { "indexed": true, "name": "negative", "type": "uint256" }, { "indexed": false, "name": "total", "type": "uint256" }], "name": "_viewedReputation", "type": "event" }]).at("0x2df0e16b4122cc14dabe5d6ecb2ae24bc9d48dc1");

