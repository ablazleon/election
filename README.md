# election

Example of voting using smart contracts and Ethereum

PS: metamask disable privacy option for displaying the account!!!

For testing it:

Election.deployed().then(function(i) { app = i })

web3.eth.getAccounts()

## 1. How to vote in behalf of a candidate?

// app.vote(1, {from: web3.eth.getCoinbase()})


web3.eth.getAccounts().then(function(p){ap = p})
app.vote(1,{from: ap[0]})

truffle migrate --reset


