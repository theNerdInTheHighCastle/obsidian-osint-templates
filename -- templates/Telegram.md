---
tags: telegram socialmedia osint  
---

# {{title}}
Report created on: {{date}} {{time}}

## Standard Operating Procedures

- [ ] VALIDATION

- [ ] Get Metadata 

- [ ] OSINT

- [ ] TONCOIN CRYPTOCURRENCY ANALYSIS

- [ ] SOCIAL NETWORK ANALYSIS


## Step 1 -Validation
- if user check https://t.me/<user>
- if group / channel check https://t.me/<user> and Telegram Search Channel (https://xtea.io) or Telegago
- [https://cse.google.com/cse?cx=006368593537057042503:ig4r3rz35qi#gsc.tab=0](https://cse.google.com/cse?cx=006368593537057042503:ig4r3rz35qi#gsc.tab=0)
- If a phone number, both real or anonymous, add it on your address book, to check if it is really linked to a Telegram account.


### Result
The Telegram user / phone number / channel / groupis alive and real

## Step 2 - Get Metadata
- Check @username_to_id_bot to get ID from username;
- Check @tgscanrobot to search for the username / ID;
- Check @ChatSearchRobot to scan username within chats crawled;
- Check @creationdatebot for creation date;
- Check https://t.me/SangMataInfo_bot for username history;
- Check harpoon CLI to get other metadata such as the phone number if available.
- Implement this bookmarklet in your browser to get interesting data from the source code of a Telegram profile: javascript:(function()%7Bvar a %3D document.getElementsByClassName('tgme_page_description')%5B0%5D%3B alert(a.innerText)%7D)() ---> credit to: @hatless1der

### Add Selectors
[]
[]
[]

## Step 3 -OSINT
- Check @telesint_bot;
- Check @TgAnalyst_bot;
- Check @maigret_osint_bot;
- Check @SovaAppBot
- Check Whats my Name App for username reverse search;
- Check IDCrawl for username reverse search
- Check Google Cache for historical views of a user or a channel / group

### Add Selectors (social media, interesting links, etc)
[]
[]
[]

## Step 4 - Toncoin blockchain forensics

### Basically each cryptocurrency has to be checked within Telegram, so to begin let's focus on a general research:
- In Google, Bing, and DuckDuckGo –> site:t.me cryptocurrency
- In Yandex –> url:t.me cryptocurrency
Credit to https://hatless1der.com/telegram-osint-basics-5-tips-anyone-can-do-right-now/#:~:text=Skip%20to%20content-,%40hatless1der,-%7C%20Blog

### Then it's time to boil down to our beloved cryptocurrency. You can move back and forth, from a Telegram account:
- check it on Ton Wine ---> https://ton.wine/<telegram account>
- check it on Fox Tails ---> https://foxtails.io/<telegram account>
- Check it on Tonex ---> https://tonex.app/@<telegram account>
- Check TON Dns for a Domain search ---> https://dns.ton.org/#<telegram account>. 
- Check Ton Limo https://ton.limo/ for other TON Domain;
- Check the phone number on https://fragment.com/ to discover if you are dealing with an anonymous Telegram number. 

#### If you get a match with TON Domain or a TON anonymous phone number, then you will have a smart contract and you have connected the investigated account to the TON Blockchain

### Or from a TON address:
- Perform a Google / Yandex general search;
- Check explorers:
	- https://tonscan.org/
	- https://ton.page/
	- https://ton.sh/
	- https://nkr413.github.io/
	- https://toncoin.tonscan.io/
	- https://tonmoon.org/explorer/
	- https://youton.org/
	- https://tonwhales.com/staking (staking)
	- https://ton.cx/
	- https://explorer.toncoin.org/
	- https://tonapi.io/
- Check the availability of NFT:
	- https://explorer.tonnft.tools/
	- https://beta.disintar.io/marketplace
	- https://getgems.io/
- If you got usernames or Internet domain act accordingly following the domain_IP template.
- If you got some TON blockchain based altcoin check repeat the process from the beginning of Step 4. 

### Add Selectors (TON address, juicy transaction hash, dates, TON domains, TON usernames, TON NFTs, TON anonymous phone numbers)
[]
[]
[]

## Step 5 - Social Network analysis
- build your graph with:
1. Maltego also using Maigret local transform for Telegram usernames;
2. Gephi to import eventual csv data scraped.
3.  Scrape your data using bookmarklets from https://gist.github.com/fabledowl/ and Telegram Legacy from Desktop.
4. You can also build a network diagram using the template networkDiagram


Other useful resources goes here:
- https://github.com/ItIsMeCall911/Awesome-Telegram-OSINT;
- https://awesomeopensource.com/project/ItIsMeCall911/Awesome-Telegram-OSINT
## Add here your images / screenshot