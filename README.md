sjcx-tipbot
===========

Tip anyone with SJCX, the coin used in http://storj.io/. For security and lower server demands there is no bitcoin/counterparty node on the server. All the blockchain information is collected from blockchain.info and blockscan.com. All withdrawal requests are downloaded and handled on a separate system. Another benefit is that there is no BTC fee for tips. All commands and configuration is documented on the sjcx-tipbot [wiki](https://github.com/Pippp/sjcx-tipbot/wiki)

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
git clone https://github.com/tipsjcx/sjcx-tipbot.git
cd sjcx-tipbot
npm install
Enter your twitter api tokens in twitterbot.js
Change the nick name in ircbot.js
node app.js
```  



