sjcx-tipbot
===========

Tip anyone with SJCX, the coin used in http://storj.io/. For security and lower server demands there is no bitcoin/counterparty node on the server. All the blockchain information is collected from blockchain.info and blockscan.com. All withdrawal requests are downloaded and handled on a separate system. Another benefit is that there is no BTC fee for tips. All commands and configurations are documented in the sjcx-tipbot [wiki](https://github.com/Pippp/sjcx-tipbot/wiki).

###Dependencies
1. MongoDB
2. Node.js
3. bitcoind
4. counterpartyd


###Currently Supported Platforms
Twitter  
Reddit  
IRC  
Slack


###Install
```
git clone
cd sjcx-tipbot
npm install
Enter your bot credentials in config.js
node app.js
```  



