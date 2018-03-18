# PWrCoin
Cryptocurrency based on Litecoin fork made for Team Project course at Wrocław University of Science and Technology.





## Proofs

### Proof of work
Proof of work is nothing else than searching for the appropriate function of a shortcut that meets specific criteria. The operation of searching for the appropriate hash is digging BTC (mining).

Solving the problem is difficult to find, but it’s easy to verify by the rest of the network. 

When one miner gets a solution, he provides the solution to others. The next step is to verify this solution and reach the consensus. Mines must iterate through many numbers to find a solution.

PoW encourages you to centralize your strength instead of focusing on a distributed network.
The most famous Cryptocurrency that uses Proof of Work is Bitcoin.

__DISADVANTAGES:__ 
- time-consuming
- energy consumption (large computing power)
- 51% risk - every attacker with 51% or more of mining resources (mining mine) will control the network.
- more and more efficient digging equipment is needed

### Proof of stake
In proof of stake miners have no reason to exist. Their place replaces validates, but their task is the same – they must confirm the transactions and place them on the chain.

For a private network may be better than proof of work, but still does not provide us with a level of control and security, because anyone in the chain can become a validator, if it links enough ether to the validator contract.

Unlike PoW, proof of stake does not generate new coins.

__DISADVANTAGES:__
- concentration of power in the hands of the largest holders, which is in contradiction with the concept of decentralization of cryptocurrencies
- be a validator and have the ability to influence the future of a given coin

The most famous Cryptocurrency that uses Proof of Stake is Ethereum.

### Proof of authority
Proof of authority delivers fast and immediate transactions through a consensus mechanism based on identity as a stake.

PoA only allows non-consecutive block approval from any one validator, meaning that the risk of serious damage is minimized.

Almost perfect solution for private networks, but is not suitable for public networks, where trust should be as scattered as possible.

__ADVANTAGES__ for private networks:
- safer due to the way of adding authorization nodes
- provides more configurability in terms of blocking times and delays
- it is not costly in terms of calculation

New concept in the blockchain where you have a number of pre-approved authority nodes (sealers). When you want to add new node, it has to be voted by the currently approved set of authority nodes. This gives you full control over nodes which can seal blocks.

In proof of authority the identity must be true, so we need to verify the validators and check if they are who they claim they are. Eligibility for staking identity should be difficult to obtain. The procedure of establishing the authority needs to be the same for all validators.

The Proof of authority consensus need to ensure independency of validators and the necessity of giving them the means to protect their nodes. 

### Proof of research
Proof of research delivers fast and cheap transactions.

Consensus is achieved with the democracy - the main decisions in the network are made by voting on the network participants.

Users are compensated for having a currency which can potentially affect its value.

__DISADVANTAGES:__
- needs confirmation of its stability


### Proofs links
#### Proof of work
[1] http://kryptopolonia.info/bitcoin-proof-of-work/

#### Proof of stake
[1] https://medium.com/@smallcapcrypto/proof-of-stake-coins-list-2018-top-5-long-term-proof-of-stake-coins-with-great-potential-2a1496e6127e

[2] https://dowbit.pl/proof-of-stake-vs-proof-of-work/

[3] https://blockgeeks.com/guides/proof-of-work-vs-proof-of-stake/

#### Proof of authority
[1] http://blog.enuma.io/update/2017/08/29/proof-of-authority-ethereum-networks.html

[2] https://medium.com/poa-network/proof-of-authority-consensus-model-with-identity-at-stake-d5bd15463256

[3] https://cointelegraph.com/news/why-blockchain-needs-proof-of-authority-instead-of-proof-of-stake




## Wallet
Cyrptocurrency wallet is a software or device that allows user to store, receive and send digital currency. 
Money itself is not stored in wallet, instead it stores both private and public key of currency client, allowing to exchange currency and acts as a personal ledger. 
Typically, for given currency there is one official wallet, that is most widely used. For example, there is Bitcoin Core Wallet, Litecoin Core or Etherum Wallet. 
There are also universal wallets, that can be used for many (but not all) cryptocurrencies. The examples of them are Coinomi or Holytransaction. This is also called multicurrency.  
After all, there are hardware wallets, that are especially reliable and secure physical devices, that are used for storing coins. They offer a lot, but require extra money spend on device. 
Some software advertised as wallets can be mallware trying to take advantage of people willing to download and use unoficiall wallets, so users must be aware and careful when choosing one. 

Software wallets can exist in form of application that is installed locally on computer, or web wallet that is menaged by a third party.
There is distinction of "hot" and "cold" wallets. A hot one is connected to Internet, so can be used at any time, but is constantly vulnerable to attacks. 
On the other hand, a cold wallet is for example hardware wallet, which cannot be accessed without pluging it into computer. 

A reasonable choice for a newly created cryptocurrency would be to opt for one of universal wallets that are already available. 
It might be somehow limited in configuration but doesn't require developing solution from ground up and offers reliable and much more tested functionality. 

### Wallet links 
[1] https://cryptocurrencyfacts.com/what-is-a-cryptocurrency-wallet/

[2] https://en.wikipedia.org/wiki/Cryptocurrency_wallet





## Features

### Privacy - who is allowed to participate in network?
Possible solutions
- anyone can join network
- potential participants need an invitation or permission (for example every student with valid identity card is permitted to join the network)
- existing participants could decide future entrants
- consortium could make the decisions
- regulatory authority could issue licenses for participation

### Hashing Algorithm 
#### Scrypt 
- Litecoin uses a simplified version of Scrypt
- initially designed to make it costly to perform large-scale custom hardware attacks
- less widely used and analyzed than the SHA2 hashing algorithm used in Bitcoin, so there is some concern about possible weaknesses in its cryptographic scheme being discovered in the future

#### X11
- composite function of multiple hashing algorithms
- the algorithm uses eleven hashing functions from the Blake algorithm to the Keccak algorithm making it very secure
- algorithm is not as long-term as some expect it to be. Some scientists give it a maximum of two years before this algorithm gets ASIC’d

#### SHA3-256
- quantum-proof, should last billions of years
- used by POA network, other Proof Of Authority network 
- probably best choice right now

### Mining time
“In private networks, a block time as low as three seconds works well.” ~ Building Blockchain Projects by Naryan Prusty

### Anonymity
Project is dedicated to scientific institutions so transactions should be transparent for all network participants by definition


### Features links
[1] https://www.ibm.com/blogs/blockchain/2017/05/the-difference-between-public-and-private-blockchain/

[2] https://themerkle.com/scrypt-vs-x11-vs-sha-256/

[3] https://en.bitcoin.it/wiki/Scrypt_proof_of_work

[4] https://en.bitcoin.it/wiki/Comparison_of_cryptocurrencies

[5] https://www.theregister.co.uk/2016/10/18/sha3256_good_for_beelions_of_years_say_boffins/

[6] https://hackmd.io/s/HkV8Vw7_-

[7] https://www.safaribooksonline.com/library/view/building-blockchain-projects/9781787122147/





## Law restrictions
As the cryptocurrencies gained more interest and hype recently, the government response was to prepare and regulate laws related to them. The situation is still under development, because there 
are projects and legal acts being currently discused and processed.   
Creating cyrptocurrencies per se is not forbidden by polish law. Although there are specified policies regulating digital cash and its transactions. 
When the cryptocurrency is designed so that for creation of it user must first pay an equivalent of traditional money - then the chance of interpreting it as digital money is extremely high. 
In such situation, creators can be accused of issuing money without required legitimation, and consequences might be serious. 
As long as the cryptocurrency serves as an alternative to  medium of exchange and is not exchanged for regular money there are little  to no laws considered in it and it should be safe to create and exchange it. 





## Economy of PWrCoin

### Value of coins
Initial value of PWrCoin would be set by Authorities during configuration of cryptocurrency. Because PWrCoin will be exchangable with different cryptocurrencies its real value will be determined by people trading this crypto

### Amount of coins
As value - maximum amount of coins would be set by Authorities during configuration.   

### PWrCoin Acceptance
For a while any official institution don't accept PWrCoin, but we hope that we will find providers who will put their interest in our project.

### PWrCoin Editions
Configuration script should give possiblity to add year postfix to crypto name.

### Exchange
Exchange for real currencies is in discussion. Although we would like to create whole system of University cryptocurrencies with coins of equal value, so there would be no problem with exchanging coins between different univeristies.

### Economy links
[1] https://www.quora.com/What-determines-the-value-of-cryptocurrencies

[2] https://www.chapman.edu/research/institutes-and-centers/economic-science-institute/_files/ifree-papers-and-photos/koeppel-april2017.pdf
