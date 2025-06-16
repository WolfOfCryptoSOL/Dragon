DRAGON
======

The all-in-one tool to help you find profitable wallets on Solana, Ethereum and Binance Smart Chain.

IMPORTANT NOTE:
-------------
The GMGN.ai domain is cloudflare protected, meaning some requests will fail to get access to an unprotected endpoint.
Join the Discord Server and request access: https://discord.gg/xxWqZppjht

SUGGESTIONS
----------
Drop Suggestions! (and a follow): https://x.com/DragonWallets/status/1853618085149778392

TUTORIAL
--------
YouTube Video: https://youtu.be/ab17qHh2P-o?si=vIKSK2lbY-UdaqGP

SETUP
-----
1. pip install -r requirements.txt
2. python dragon.py

FEATURES
--------

1. BUNDLE CHECKER
----------------
Check if a Solana contract has had multiple buys bundled into one transaction.
- Enter a contract address
- Receive the bundle data
Note: This will only recognise a bundle if the bundled wallets are shown under the "DEV" tab on GMGN.ai
Example: https://gmgn.ai/sol/token/231Y5yfc5aeajFfqaM5P9WvwqSiMG5CyuwSib9Pbpump?tag=creator

2. BULK WALLET CHECKER
---------------------
Check a large list of wallets to receive their PnL, winrate and more data.
- Select your .txt file or enter your own directory
- Enter the amount of threads you'd like to use
- Select whether you'd like to use proxies or not
- Enter whether you'd like to skip certain wallets
- Receive your wallet data

3. TOP TRADERS SCRAPER
---------------------
Scrape the top 100 traders of Solana tokens to receive their PnL, winrate and more data.
- Load data/Solana/TopTraders/tokens.txt with contract addresses
- Enter the amount of threads you'd like to use
- Select whether you'd like to use proxies or not
- Receive your top traders data

4. ALL TRANSACTION SCAN
----------------------
Grab every single wallet address that made a buy transaction of a Solana token. Not recommended for large market cap tokens.
- Enter a contract address
- Enter the amount of threads you'd like to use
- Select whether you'd like to use proxies or not
- Wait and receive your wallet addresses

5. GET TRANSACTION BY TIMESTAMP
-----------------------------
Grab every single wallet address that made a buy transaction of a Solana token between 2 timestamps.
- Enter a contract address
- Enter the amount of threads you'd like to use
- Select whether you'd like to use proxies or not
- Enter first & second timestamps
- Wait and receive your wallet addresses

6. COPY WALLET FINDER
--------------------
Use This: https://github.com/1f1n/solana-check-contested-wallets

7. TOP HOLDERS SCRAPER
---------------------
Scrape the top 100 holders of Solana tokens to receive their PnL, winrate and more data.
- Load data/Solana/TopHolders/tokens.txt with contract addresses
- Enter the amount of threads you'd like to use
- Select whether you'd like to use proxies or not
- Receive your top traders data

8. EARLY BUYERS SCRAPER
----------------------
Scrape the early buyers, excluding the dev, of Solana tokens to receive their PnL and more data.
- Load data/Solana/EarlyBuyers/tokens.txt with contract addresses
- Enter the amount of early buyers you'd like to scrape per contract address
- Enter the amount of threads you'd like to use
- Select whether you'd like to use proxies or not
- Receive your top traders data

9. GMGN MODULES
--------------
Scrape the contract addresses of new, soaring, completing and bonding tokens on Pump.Fun and Moonshot.
- Select the module you want to use from the four listed
- Enter the amount of threads you'd like to use
- Select whether you'd like to use proxies or not
- Receive your contract addresses

Data sources:
- New Token: https://gmgn.ai/meme?chain=sol&tab=new_creation
- Completing Token: https://gmgn.ai/meme?chain=sol&tab=completing
- Soaring Token: https://gmgn.ai/meme?chain=sol&tab=soaring
- Bonded Token: https://gmgn.ai/meme?chain=sol&tab=complete

RECENT UPDATES
-------------
12/04/2025
- Added global ratelimit handling
- Fixed Get Transaction By Timestamp
- Fixed fake user agent prompting a browser error
- Optimised code and removed repeated and unnecessary code

23/03/2025
- Added automatic updater

22/03/2025
- Added Cloudflare bypass to Ethereum modules
- Added BSC chain modules
- Various other small improvements and fixes

03/02/2025
- Removed Cloudscraper
- Fixed Bundle Checker
- Various other small fixes

[Previous updates available in the original README.md]

DONATIONS
---------
Donations are appreciated! (Solana)
FF3gkF88aJ6DayFHVmUw7TvNYJnXzmGBu6P5RrEcoins

CREDITS
-------
- Me: https://github.com/1f1n
- Azek: https://github.com/azek10 