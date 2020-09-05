# Awesome Compendia
 A publicly curated list of awesome Compendia websites, resources, documentation, tools, software, validator & community efforts. Started by Compendia validators [bfx](https://bindscan.io/wallets/cT6Mi5r2qz3GSNkGFjunfM8DLdE9duxRGx) & [cryptomaniac](https://bindscan.io/wallets/cnKNhexcrt8piotBQZfU3URFyrswTtJjAx). Forked from & inspired by [awesome-go](https://github.com/avelino/awesome-go).
 
 ** Disclaimer - All of the resources available below are publicly available, we cannot guarantee the accuracy or efficacy of the resources listed, and are not liable for any submitted content.

## Contributing
 Please take a quick look at the [contribution guidelines](https://github.com/Bx64/awesome-compendia/blob/master/CONTRIBUTING.md) first. Thanks to all [contributors](https://github.com/Bx64/awesome-compendia/graphs/contributors); you rock!

## Sponsorships
 None at this time.
 
#### *If you see a package, tool or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!*

## Contents

- [Compendia Resources](#compendia-resources)
    - Websites*
    - GitHub
    - Mainnet
    - Testnet

- [Compendia Documentation](#compendia-documentation)
    - Bug Bounty & Security Reward Program
    - Economy
    - Introduction
    - Nodes
    - Validators
    - Token Swap
    - Wallet
        
- [Exchanges](#Exchanges)
    - Altilly
    - Switcheo
    
- [Mainnet API Documentation](#mainnet-api-documentation)
    - Blockchain
    - Blocks
    - Delegates (Validators)
    - Locks
    - Nodes
    - Overview
    - Peers
    - Rounds
    - Transactions
    - Votes
    - Wallets

- [Tools (Community)](#tools-community)
    - Compendia JS - Javascript library for sending transactions - by mrmikeo
    - Compendia Crypto - Crypto npm library for Compendia - by mrmikeo
    
- [Tools (Validators)](#tools-validators)
    - Compendia Explorer Mainnet (ARK-based) - by itsanametoo
    - Compendia Monitor Telegram Bot - by cactus1549
    - Compendia Stakes Telegram Bot - by bindie
    - Compendia Tools Website - by arbaro
    - Compendia Validators Info - by the_bobbie_bunch
    - Reward Calculator - by bfx
    - Reward Calculator - by cactus1549
    - Reward Calculator - by dutch_pool
    - Reward Calculator - by maryo
    - Reward Calculator - by the_bobbie_bunch

## Compendia Resources

*Official Compendia Websites. Listed first due to relevance.*

* [Compendia API Documentation](https://docs.compendia.org/api/) - Compendia API Documentation - API's expose resources and data provided by the Core Server (Node).
* [Compendia Documentation](https://docs.compendia.org/) - Compendia Documentation Suite.
* [Compendia Telegram - Announcements](https://t.me/CompendiaAnn) - Compendia Telegram Announcements Channel.
* [Compendia Telegram - Chat](https://t.me/Compendia) - Compendia Telegram Chat Channel.
* [Compendia Twitter](https://twitter.com/Compendia_org) - Compendia Twitter Account.
* [Compendia Website](https://compendia.org/) - Official Compendia Website.
    * [Compendia Blog](https://compendia.org/blog/) - Official Compendia blog.
* [nOS Chat](https://nos.chat/) - nOS-related communications website.
* [nOS Client Website](https://nos.io/) - nOS multi-cryptocurrency wallet client.

*Official Compendia GitHub.*

* [Compendia Github](https://github.com/compendia/) - Official Compendia GitHub.
    * [Compendia Core repository](https://github.com/compendia/core) - Github Repository for Compendia Core.
        * [Mainnet Blockchain Milestones](https://github.com/compendia/core/blob/develop/packages/crypto/src/networks/realmainnet/milestones.json) - Compendia Blockchain Milestones.
    * [Mainnet Core Control](https://github.com/compendia/core-control/tree/main) - Mainnet Core Control (Automated Relay/Core Setup).
    * [Testnet Core Control](https://github.com/compendia/core-control/tree/develop) - Testnet Core Control (Automated Relay/Core Setup).

*Official Mainnet Resources.*

* [Compendia Mainnet API](TBC#########) - Mainnet API - API's expose different resources and data provided by the Core Server (Node).
* [Compendia Mainnet Block Explorer](https://bindscan.io/) - Mainnet Explorer - Viewing tool for Transactions, Blocks, Validators and Wallet Information.
* [Compendia Mainnet Wallet](https://wallet.compendia.org/) - Mainnet Web Wallet for managing your BIND.

*Official Testnet Resources.*

* [Compendia Testnet API](https://api.nos.dev/api/v2) - Compendia Testnet API - API's expose different resources and data provided by the Core Server (Node).
* [Compendia Testnet Block Explorer](https://explorer.nos.dev/) - Testnet Explorer - Viewing tool for Transactions, Blocks, Validators and Wallet Information.
* [Compendia Testnet Wallet](https://wallet.nos.dev/) - Testnet Web Wallet for managing your BIND.

## Compendia Documentation

*Official Compendia Documentation.*

* [Documentation Website](https://docs.compendia.org/) - Official Documentation Website.
    * [Bug Bounty & Security Reward Program](https://docs.compendia.org/guide/bug-bounty.html) - Bug bounty & security vulnerability reward program.
        * [Security Vulnerability Classification](https://docs.compendia.org/guide/bug-bounty.html#security-vulnerability-classifications) - Security vulnerability classifications.
        * [Security Vulnerability Guidelines](https://docs.compendia.org/guide/bug-bounty.html#security-vulnerability-guidelines) - Security vulnerability guidelines.
     * [Economy](https://docs.compendia.org/guide/economy.html) - Economy - Compendia's economic model explained.
        * [Block Rewards & Halvings.](https://docs.compendia.org/guide/economy.html#block-rewards-halvings) - Block rewards & halvings.
        * [Staking](https://docs.compendia.org/guide/economy.html#staking) - Staking.
        * [Transaction Fees](https://docs.compendia.org/guide/economy.html#transaction-fees) - Transaction fees.
        * [Vote Power/Influence](https://docs.compendia.org/guide/economy.html#vote-power) - Vote Power/Influence.
    * [Introduction](https://docs.compendia.org/guide/) - Documentation introduction.
        * [Adoption](https://docs.compendia.org/guide/#adoption) - Adoption.
        * [BIND](https://docs.compendia.org/guide/#bind) - BIND, Compendia's native currency.
        * [Resources](https://docs.compendia.org/guide/#resources) - Resources.
        * [Use-cases](https://docs.compendia.org/guide/#use-cases) - Use-case examples for Compendia/BIND.
        * [What is Compendia?](https://docs.compendia.org/guide/#what-is-compendia) - What is Compendia?
     * [Nodes](https://docs.compendia.org/guide/node.html) - Nodes - BIND network participants.
        * [Create A Forging Node](https://docs.compendia.org/guide/node.html#create-a-forging-node) - Create a forging node.
        * [Create Two Relay Nodes](https://docs.compendia.org/guide/node.html#create-two-relay-nodes) - Create two relay nodes.
        * [Install Core-control](https://docs.compendia.org/guide/node.html#install-core-control) - Install core-control.        
        * [Recommended Node Specs](https://docs.compendia.org/guide/node.html#recommended-node-specs) - Recommended node specs.
        * [Tips](https://docs.compendia.org/guide/node.html#tips) - Tips.
        * [Updating A Node](https://docs.compendia.org/guide/node.html#updating-a-node) - Updating a node.
        * [What Are Nodes?](https://docs.compendia.org/guide/node.html#what-are-nodes) - What are Nodes?
    * [Token Swap](https://docs.compendia.org/guide/token-swap.html) - Token swap (NOS to BIND).
        * [Instruction Video](https://docs.compendia.org/guide/token-swap.html#video) - Instruction video.
        * [Tutorial](https://docs.compendia.org/guide/token-swap.html#tutorial) - Tutorial.	
    * [Validators](https://docs.compendia.org/guide/validators.html) - Validators - BIND network maintainers.
        * [Create A Profile](https://docs.compendia.org/guide/validators.html#create-a-profile) - Create a profile.
        * [Introduction](https://docs.compendia.org/guide/validators.html#introduction) - Introduction.
        * [Registration](https://docs.compendia.org/guide/validators.html#registration) - Registration.
    * [Wallet](https://docs.compendia.org/guide/wallet.html) - Wallet - BIND wallet client.
        * [Create & Log In](https://docs.compendia.org/guide/wallet.html#create-log-in) - Create & log in.
        * [Staking](https://docs.compendia.org/guide/wallet.html#stake) - Staking.
        * [Transfer](https://docs.compendia.org/guide/wallet.html#transfer) - Transfer.
        * [Voting](https://docs.compendia.org/guide/wallet.html#vote) - Voting.

## Exchanges

*Exchanges where BIND can be traded.*

* [Altilly](https://altilly.com/) - Altilly Exchange paired with BTC, ETH, ARK & XQR.
    * [Asset information](https://www.altilly.com/asset/BIND) - General information about BIND and it's trading pairs.
        * [BIND/BTC](https://www.altilly.com/market/BIND_BTC) - BIND/BTC trading pair.
        * [BIND/ETH](https://www.altilly.com/market/BIND_ETH) - BIND/ETH trading pair.
        * [BIND/ARK](https://www.altilly.com/market/BIND_ARK) - BIND/ARK trading pair.
        * [BIND/XQR](https://www.altilly.com/market/BIND_XQR) - BIND/XQR trading pair.
* [Switcheo](https://switcheo.exchange/) - Switcheo Exchange paired with NEO (currently, still NOS/NEO). Will feature BIND markets.
    * [NOS/NEO](https://switcheo.exchange/markets/NOS_NEO) - NOS/NEO trading pair.

## Mainnet API Documentation

*Official Compendia Mainnet API Documentation.*

* [Mainnet API Documentation](https://docs.compendia.org/api/) - Mainnet API Documentation.
    * [Blockchain](https://docs.compendia.org/api/blockchain.html) - Blockchain.
        * [Endpoint](https://docs.compendia.org/api/blockchain.html#endpoint) - Endpoint.
        * [Examples](https://docs.compendia.org/api/blockchain.html#examples) - Examples.
    * [Blocks](https://docs.compendia.org/api/blocks.html) - Blocks.
        * [List all blocks](https://docs.compendia.org/api/blocks.html#list-all-blocks) - List all blocks.
        * [List all transactions in a block](https://docs.compendia.org/api/blocks.html#list-all-transactions-in-a-block) - List all transactions in a block.
        * [Retrieve first block](https://docs.compendia.org/api/blocks.html#retrieve-first-block) - Retrieve first block.
        * [Retrieve last block.](https://docs.compendia.org/api/blocks.html#retrieve-last-block) - Retrieve last block.
        * [Retrieve a block](https://docs.compendia.org/api/blocks.html#retrieve-a-block) - Retrieve a block.
        * [Search all blocks](https://docs.compendia.org/api/blocks.html#search-all-blocks) - Search all blocks.
    * [Delegates (Validators)](https://docs.compendia.org/api/delegates.html) - Delegates (Validators).
        * [List All Delegates](https://docs.compendia.org/api/delegates.html#list-all-delegates) - List all delegates.
        * [List All Blocks Of Delegate](https://docs.compendia.org/api/delegates.html#list-all-blocks-of-a-delegate) - List all blocks of a delegate.
        * [List All Voters Of Delegate](https://docs.compendia.org/api/delegates.html#list-all-voters-of-a-delegate) - List all voters of a delegate.
        * [Retrieve A Delegate](https://docs.compendia.org/api/delegates.html#retrieve-a-delegate) - Retrieve a delegate.
        * [Search For A Delegate](https://docs.compendia.org/api/delegates.html#search-for-a-delegate) - Search for a delegate.
    * [Locks](https://docs.compendia.org/api/locks.html) - Locks.
        * [List All Locks](https://docs.compendia.org/api/locks.html#list-all-locks) - List all locks.
        * [Return Lock By ID](https://docs.compendia.org/api/locks.html#return-lock-by-id) - Return lock by id.
        * [Search Locks](https://docs.compendia.org/api/locks.html#search-locks) - Search locks.
        * [Search Unlocked](https://docs.compendia.org/api/locks.html#search-unlocked) - Search unlocked.
    * [Node](https://docs.compendia.org/api/node.html) - Node.
        * [Node Debug](https://docs.compendia.org/api/node.html#node-debug) - Node debug.
        * [Retrieve The Configuration](https://docs.compendia.org/api/node.html#retrieve-the-configuration) - Retrieve the configuration.
        * [Retrieve The Cryptography Configuration](https://docs.compendia.org/api/node.html#retrieve-the-cryptography-configuration) - Retrieve the cryptography configuration.
        * [Retrieve The Fee Statistics](https://docs.compendia.org/api/node.html#retrieve-the-fee-statistics) - Retrieve the fee statistics.
        * [Retrieve The Status](https://docs.compendia.org/api/node.html#retrieve-the-status) - Retrieve the status.
        * [Retrieve The Syncing Status](https://docs.compendia.org/api/node.html#retrieve-the-syncing-status) - Retrieve the syncing status.
    * [Overview](https://docs.compendia.org/api/#overview) - Overview.
        * [Endpoints](https://docs.compendia.org/api/#endpoints) - Endpoints.
        * [Pagination](https://docs.compendia.org/api/#pagination) - Pagination.
        * [Public Testing Relay](https://docs.compendia.org/api/#public-testing-relay) - Public Testing Relay.
    * [Peers](https://docs.compendia.org/api/peers.html) - Peers.
        * [List All Peers](https://docs.compendia.org/api/peers.html#list-all-peers) - List all peers.
        * [Retreive A Peer](https://docs.compendia.org/api/peers.html#retrieve-a-peer) - Retrieve a peer.
    * [Rounds](https://docs.compendia.org/api/rounds.html) - Rounds.
        * [List Rounds Data](https://docs.compendia.org/api/rounds.html#list-rounds-data) - List rounds data.
    * [Transactions](https://docs.compendia.org/api/transactions.html) - Transactions.
        * [Create A Transacitons](https://docs.compendia.org/api/transactions.html#create-a-transaction) - Create a transaction.
        * [Get An Unconfirmed Transaction](https://docs.compendia.org/api/transactions.html#get-an-unconfirmed-transaction) - Get an unconfirmed transaction.
        * [Get Transaction Fees (Non-Dynamic)](https://docs.compendia.org/api/transactions.html#get-transaction-fees-non-dynamic) - Get transaction fees (non-dynamic).
        * [Get Transaction Schemas](https://docs.compendia.org/api/transactions.html#get-transaction-schemas) - Get transaction schemas.
        * [Get Transaction Types](https://docs.compendia.org/api/transactions.html#get-transaction-types) - Get transaction types.
        * [List All Transactions](https://docs.compendia.org/api/transactions.html#list-all-transactions) - List all transactions.
        * [List All Unconfirmed Transactions](https://docs.compendia.org/api/transactions.html#list-all-unconfirmed-transaction) - List all unconfirmed transactions.
        * [Retrieve A Transactions](https://docs.compendia.org/api/transactions.html#retrieve-a-transaction) - Retrieve a transaction.
        * [Search For Transactions](https://docs.compendia.org/api/transactions.html#search-for-transactions) - Search for transactions.
    * [Votes](https://docs.compendia.org/api/votes.html) - Votes.
        * [List All Votes](https://docs.compendia.org/api/votes.html#list-all-votes) - List all votes.
        * [Retrieve A Vote](https://docs.compendia.org/api/votes.html#retrieve-a-vote) - Retrieve a vote.
    * [Wallets](https://docs.compendia.org/api/wallets.html) - Wallets.
        * [List All Locks Of Wallet](https://docs.compendia.org/api/wallets.html#list-all-locks-of-a-wallet) - List all locks of a wallet.
        * [List All Received Transactions Of Wallet](https://docs.compendia.org/api/wallets.html#list-all-received-transactions-of-a-wallet) - List all received transactions of a wallet.
        * [List All Sent Transaction Of Wallet](https://docs.compendia.org/api/wallets.html#list-all-sent-transactions-of-a-wallet) - List all sent transactions of a wallet.
        * [List All Transactions Of Wallet](https://docs.compendia.org/api/wallets.html#list-all-transactions-of-a-wallet) - List all transactions of a wallet.
        * [List All Votes Of Wallet](https://docs.compendia.org/api/wallets.html#list-all-votes-of-a-wallet) - List all votes of a wallet.
        * [List All Wallets](https://docs.compendia.org/api/wallets.html#list-all-wallets) - List all wallets.
        * [List Top Wallets](https://docs.compendia.org/api/wallets.html#list-all-top-wallets) - List all top wallets.
        * [Retrieve A Wallet](https://docs.compendia.org/api/wallets.html#retrieve-a-wallet) - Retrieve a wallet.
        * [Search All Wallets](https://docs.compendia.org/api/wallets.html#search-all-wallets) - Search all wallets.

## Tools (Community)

***Unofficial** tools developed by Compendia community members.*

* [Compendia JS](https://github.com/mrmikeo/compendia-js) - Javascript library for sending transactions - by mrmikeo.
* [Compendia Crypto](https://github.com/mrmikeo/crypto) - Compendia Crypto - Crypto npm library for Compendia - by mrmikeo

## Tools (Validators)

***Unofficial** tools developed by Compendia validators.*

* [Compendia Explorer - Mainnet](https://compendia.itsadelegatetoo.com/#/) - Mainnet Compendia explorer based on ARK, created by itsanametoo.
* [Compendia Monitor - Telegram Bot](https://t.me/compendiamonitorbot) - BIND voter & validator monitor bot, created by cactus1549.
* [Compendia Stakes - Telegram Bot](https://t.me/CompendiaStakes) - BIND stake monitor Telegram Bot, created by bindie.
* [Compendia Tools Website](https://compendia.arbarodelegate.eu/tools) - Compendia tools website - created by arbaro. 
* [Compendia Validators Info](https://compendiavalidators.com) - Compendia Validator website, created by the_bobbie_bunch.
* [Reward Calculator - bfx](https://bit.ly/3iYOOAG) - Daily BIND reward calculator, created by bfx.
* [Reward Calculator - cactus1549](https://compendiacalculator.online) - Daily BIND reward calculator, created by cactus1549.
* [Reward Calculator - dutch_pool](https://calculator.dutchpool.io/compendia) - Daily BIND reward calculator, created by dutch_pool team.
* [Reward Calculator - maryo](https://bit.ly/3ht3CqW) - Daily BIND reward calculator, created by maryo.
* [Reward Calculator - the_bobbie_bunch](https://www.thebobbiebunch.nl/#calculator) - Daily BIND reward calculator, created by the_bobbie_bunch.
