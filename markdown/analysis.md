# **:material-account-cowboy-hat: Token Analysis Guide**
!!! warning
    Document under construction and subject to change. Additional resources and diagrams coming soon

Depending on the project, your risk-tolerance, and goals... items listed may not be applicable.
Further, this is not a guaranteed path to finding safe "investments", and this documentation should never be treated as law.
Information below is outlined as a list of details an investor may want to consider before entering a liquidity pool. 

### **:material-file-document-edit: Check the contract **

There are many metrics you can measure on-chain, and many ways to obscure those metrics. It's important to understand what you're looking for, and to know how to verify what you're looking at.

- Use trusted analysis tools and telegram bots for high-level details on the current state of the token. Useful for liquidity metrics,
    * _[Moonarch :material-book-arrow-up-outline:](https://moonarch.app/)_
    * _[Token Sniffer :material-book-arrow-up-outline:](https://tokensniffer.com/)_
    * _[SafeAnalyzerBot :material-book-arrow-up-outline:](https://t.me/SafeAnalyzerbot)_
- Check the explorer, has the contract been verified? → **Read it.**
    * _Are there any suspicious looking operations?_
        1. Official solidity libraries are very readable by nature and well-written contracts should make it easy to follow the logic 
        2. Red flags are different for everyone but might include blacklisting operations, enabling/disabling trade functionality, unnecessary obfuscation etc.
    * _What are some of the first events/transactions that were triggered with the contract?_
    * _What does the holder distribution look like? (top 100)_
        1. Be wary of multi-wallets, liquidity swingers, and shady developers
        2. Some platforms will show you volume by address
    * _How much value is held in the deployer/developer/marketing wallets?_
    * _What does the transaction history of the deployer look like?_
        1. Have they published any token contracts in the past? How recently? How'd that go?
        2. Where was the wallet funded from? If applicable, what is the transaction history of said address(es)?

***Transaction Analysis Guide Coming Soon**

### **:material-account-multiple: Check the social profiles**

One of the easiest ways to tell if a team intends to maintain further development is to follow their social media.

- Does the project have a website?
    * _Does the roadmap consist of anything other than "marketing"? Think about what's realistic and deliverable in any given timeframe_
    * _Listen to your gut... does the quality or contents of the website match your confidence in the team's ability to deliver?_
    * _Check the developers tools, what frameworks are they using?_
- How active is their twitter, when was it created?
- How active is their telegram group or discord server?
    * _What quality of discourse is being had?_
    * _How much attention to detail does the team have when sharing updates? (grammar, attitude, frequency, etc.)_

### **:material-chart-bell-curve-cumulative: Check the chart**

Don't trust a massive green candle until you've done enough research to validate the activity and justify an entry.

- What is the scope of your investment? Flip or Hold?
    * _Traditional charting patterns may not matter much in micro-caps, but can be useful for larger altcoins_
- Are there any suspiciously timed trades in the order book? Many for the same amount? MEV bots?
- How active is their telegram group or discord server?
    * _What quality of discourse is being had?_
    * _How much attention to detail does the team have when sharing updates? (grammar, attitude, etc.)_

### **:material-data-matrix-scan: Check the transaction**

If you've covered all your green flags and are ready to add to a liquidity pool, keep the following tips in mind:

- Always check the contract address **AND** your input parameters before submitting a transaction (if hundred-million-dollar companies can blacklist their own router, you can easily miss a zero)
- Make sure the suggested gas cost and slippage are agreeable, don't get too comfortable hitting 'Confirm'
- When approving a token for trade, make sure you're really approving _that_ token

### **:material-progress-wrench: Check the progress**

So you've been hodling a while, and it's time to check back in on your investment. Here are some things to think about:

- Is progress being made by the team? Are they active in group chats? Check pinned messages before asking any questions
- Check out whatever the team has released
    * _Does it look good? Is it usable? Is it being used? Would **you** use it?_ 

!!! success
    ![Cheers!](../extra/img/cheers.png){ align=left } Cheers, you performed an audit!

<br></br>
[Build the Bear Market :buildthebear-in-progress:](https://www.buildthebear.market){ .md-button }
[GitHub :material-git:](https://github.com/Build-the-Bear){ .md-button }
[Twitter :material-twitter:](https://twitter.com/BuildingtheBear){ .md-button }
[Telegram :material-alert-octagram:](https://www.t.me/BuildtheBear){ .md-button }
