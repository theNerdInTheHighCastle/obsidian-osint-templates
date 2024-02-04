---
tags: crypto cryptocurrency currency  
---

# Untitled
Report created on: 2022-06-23 21:27

## Standard Operating Procedures

- [ ] VALIDATION

- [ ] Get Metadata

- [ ] OSINT

- [ ] BLOCKCHAIN ANALYTICS



## Step 1 -Validation (this step is aimed at making an assessment of the NFT as a potential SCAM)
- check https://twitter.com/rugpullfinder or https://www.rugpullfinder.io
- check https://twitter.com/zachxbt
- google about the NFT project in order to checking their reliability. A common guide to use is the 10 Red Flags by Rug Pull Finder:
	 ![[Pasted image 20220623214857.png]]
- https://www.twitteraudit.com/ analyze Twitter followers to get to know if there are a majority of possible bots
### Result
The NFT project is / is not 
 a scam.


## Step 2 - Get Metadata
- Check availability on marketplace (OpenSea, Rarible etc.)
- Search collection or NFT wiith https://nftgo.io (free);
- Search collection or NFT with https://www.nftscan.com (free)
- Search NFT and ID with NFT Item Profiler https://pro.nansen.ai/ (mostly commercial)

### Add Selectors
[]
[]
[]

## Step 3 -OSINT
- Check Website with Internet Domain OSINT techniques (nslookup, whois etc);
- Check Social Media with SOCMINT (Twitter, Instagram etc.);
- Search team member with reverse username search or checking directly their profile if available as well as collection name (https://whatsmyname.app/);
-  check username, looking at every site where username can be linked to an address;
 - also the username has to be checked if it is an ENS domain or an handle on NFT marketplaces. In case we find an NFT what is the owner address?
- checking its posts (from a user to an address) if maybe they show an NFT and then what address owns that. With regard posts take a look on information about activity such as payments, buying with and therefore transactions on chain that move to an address;
- finally looking up the bio if it is mentioning any address or blockchain domain.
- Search the NFT with reverse image search or with the user profile image. Some tools:
	- https://fingible.nftport.xyz/;
	- https://www.nyckel.com/nft-finder/
	- trait filtering on OpenSea;
	- Google Image Search
- Perform again the previous search if you find something other of interest like other social media or websites.

### Add Selectors (social media, interesting links, etc)
[]
[]
[]


## Step 4 - Transaction analysis
- Before to start check the conctract/address with https://debank.com.

- Check Etherscan (https://etherscan.io):
1. Make transaction analysis;
2. Control contracts section and user nerdydata to found similar coding or check https://ipfsbrowser.com/ to lookup for IPFS resources
3. If you will find an interesting transaction to an ENS domain use ens.domains app (https://ens.domains/it/) to identify it or opensea.io/GoodNames

- If Ethereum check Ethective (https://www.ethtective.com) or MetaSleuth.
- You can also find other transaction information on https://nftgo.io or [https://ethplorer.io,](https://ethplorer.io,)
- to verify you findings use Breadcrumbs



### Add selectors (transactions, wallets, tag, entity etc.)
[]
[]
[]


## Add here your images / screenshot




### Process overview with cryptocurrencies and NFT OSINT:


First thing first with Smart contracts > look the deployer to get an EoA related to the smart contracts.
 Maybe one is linkable to a Twitter account.
 On-chain activity. Where the scammer was connecting?
 ENS service > maybe is linked to a Web2 username? Here OSINT...
 NFT POAP - Proof of Attendance Protocol, given to someone to have participated to an event. This should be used as a potential source also to identify potential victims.
 Off-chain analysis: from an address look to:
 - web3 websites (connection with wallets); here you can check NFT marketplaces like Opensea or Rarible. You can also check quests known platforms like Galxe or Zealy.
 - make use of Google Dorks to find out an address mentioned on a blog or Github;
 - look on Twitter for that address, for example a Tweet with a mention;
 - analysis tools like Etherscan, Arkham or Metasleuth to get labels;
 - darkweb forums or marketplaces use by seller for donation.
 
 User to Wallet Address - Process overview
 
 From a user we can move to:
 - username, looking at every site where username can be linked to an address;
 - also the username has to checked if it is a ENS domain or an handle on NFT marketplaces. In case we find an NFT what is the owner address
- checking its posts if maybe they show an NFT and then what address owns that. With regard posts take a look on information about activity such as payments, buying with and therefore transactions on chain that move to an address;
- finally looking up the bio if it is mentioning any address or blockchain domain.

Some tools we can use for NFT reverse image search is Fingible, NFT Finder or Bing.ly, or AI image similarity APIs. Also Google Image Search and trait filtering on OpenSea.

Another intesting technique is wallet clusterization through time correlation:
- get all the transactions for each address;
- for each transaction from a wallet:
	- look for other transaction from other wallets within a predefined time window;
	- Graph the data with weighted relation based on the frequency of close interactions between addresses;
The purpose is:
- differentiate multiple users behind a list of highly connected addresses;
- find all wallets controlled by a single user.