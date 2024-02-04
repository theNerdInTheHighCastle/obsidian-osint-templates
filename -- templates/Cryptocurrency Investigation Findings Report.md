---
tags: crypto cryptocurrency currency  
---

# {{title}}
Report created on: {{date}} {{time}}


The objective of this report is to analyze the cryptocurrency addresses provided in the referral to determine the source of funds and/or the destination of funds

BTC: <>;
ETH: <>;
Others: <>

## Executive summary and key findings


## Standard Operating Procedures

- [ ] VALIDATION

- [ ] Get Metadata

- [ ] OSINT

- [ ] BLOCKCHAIN ANALYTICS


## Step 1 -Validation
- check https://awebanalysis.com/en/bitcoin-address-validate/
- lenschulwitz.com/base58
- for altcoins check various explorers to confirm that they exist

### Result
The crypto address is / is not valid.


## Step 2 - Get Metadata
- Check current balance;
- Check data creation
- Check any other metadata of interest (tags, etc.)

### Add Selectors
[]
[]
[]

### Result
The balance of the address/addresses provided is ____

## Step 3 -OSINT
- Check Bitcoin Abuse;
- Check Bitcoin Who's Who;
- Check ChainAbuse (TRM Labs)
- Check Google
- Check Darkweb search engines (Ahmia, Torch)

### Add Selectors (social media, interesting links, etc)
[]
[]
[]

### Result
The collection of any open source information related to the address/addresses provided has indicate that ____ (in case of any information it is important to assess the reliability of the source and the accuracy of the information)

## Step 4 - Transaction analysis
- If Bitcoin check:
	- Wallet Explorer (to get clustered wallet linked to the address);
	- Blockchair (to understand transaction patterns and change address).
	- OXT (it has many tagged wallet and also it is very useful to get change address and proceed with clustering);
	- Breacrumbs to start using some visualizion tool;
	- If available Arkham Intelligence same for visualization techniques;
	- CryptoSleuth investigation platfotm for an expanded graphical views of incoming and outgoing transactions, up to potential identification sources;

- If Altcoin or DeFi check:
	- Etherscan (review balance, transactions and tokens held. Be careful to observe if the wallet has balance on other blockchains, like Arbitrum, Binance Smart Chain, Avalanche and so on)
	- Try to find useful transaction IN and OUT from central providers like CEXs;
	- Follow the money if you find transaction OUT to other External Owned Account;
	- If there are interaction with smart contracts, look the method used and be careful if there are bridging operations to other chains
	- Use some free visualization tool like:
		- https://www.ethtective.com/
		- https://watchers.pro
		- https://platform.arkhamintelligence.com/
		- https://metasleuth.io


- If other altcoin check explorers. You can find a great like on Bitinfocharts.

### Result
The transaction analysis indicated that ___

### Add selectors (transactions, wallets, tag, entity etc.)
[]
[]
[]
## Step 5 - Analysis wrap-up

Report here a conclusion sum-up related to your findings also making some recommendation to address further operations.




## Add here your images / screenshot or below any result paragraphs to be more concise


##### Investigator name/ID: 


### Process overview to adopt in certain circumstances:

An intesting technique is wallet clusterization through time correlation:
- get all the transactions for each address;
- for each transaction from a wallet:
	- look for other transaction from other wallets within a predefined time window;
	- Graph the data with weighted relation based on the frequency of close interactions between addresses;
The purpose is:
- differentiate multiple users behind a list of highly connected addresses;
- find all wallets controlled by a single user.