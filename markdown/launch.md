# **:material-account-cowboy-hat: Token Launch Guide**
!!! warning
    Document under construction and subject to change. Additional resources and diagrams coming soon

Depending on your project/expectations/goals, items listed may not be applicable.
Further, this is not a guaranteed path to launching or running a successful token, and this documentation should never be treated as law.
Information below is outlined as a checklist of sorts; actions a builder may want to consider before launching a tokenized project.

### **:material-package-variant: Create your concept**

There isn't a right or wrong answer when it comes to your concept. Folks are interested in just about anything you can imagine, and there's plenty of room at the table for everyone to eat.

Think about the scope of your project...

- Trend tokens -
    * _Predict the future - [Quantumrun :material-book-arrow-up-outline:](https://www.quantumrun.com/future-timeline/2023)_
    * _Ride the coattails of success (Mini, Baby, v2, Community, etc.) - [CoinMarketCap :material-book-arrow-up-outline:](https://coinmarketcap.com/best-cryptos/)_
    * _Create the trend with unique tokenomics or a new meta - [Concept Generators :material-book-arrow-up-outline:](https://www.google.com/search?q=concept+generator)_
    * _Make a degenerate, deep-fried meme_
    * **_'Shib' and 'Floki' are off-limits_**
2. Utility tokens -
    * _Yield; rewards/reflections; staking, access, etc._
    * _Ecosystem; governance, tools, p2e, etc._
    * _Miscellaneous; charity, non-profit, third-party support, etc._

### **:material-account-multiple: Create your social profiles**

There should be a gateway (or two) for your community to interact, get in touch with the team, and feel heard as investors.
No room for fear, uncertainty, and doubt (FUD) when the team & community members move with confidence, certainty, and conviction (CCC™).

- E-mail address - [Gmail :material-book-arrow-up-outline:](https://www.gmail.com/)
2. Google Voice phone number (use that ⤴) - [Google Voice :material-book-arrow-up-outline:](https://voice.google.com/)
3. Telegram account and channel (use that ⤴) - [Telegram :material-book-arrow-up-outline:](https://telegram.org/apps)
    * _Start setting up Rose (filters, chat settings, etc.) - [Rose Guide :material-book-arrow-up-outline:](https://missrose.org/guide/)_
    * _Find a couple moderators you trust_
4. Twitter - [Twitter :material-book-arrow-up-outline:](https://twitter.com/)
5. Discord (if applicable)

### **:material-view-dashboard-edit: Create your website**

There are many factors to consider when building your site; representation, usability, a11y, branding, UI-UX, etc.
**Take your time.** Present the project how you intend for it to be presented.

- Purchase domain name - [Name.com :material-book-arrow-up-outline:](https://www.name.com/), [Google Domains :material-book-arrow-up-outline:](https://domains.google/)
    * _Be sure to protect registrar_
    * _Optionally get domain/hosting from same provider; many offer WYSIWYG editors_
        1. [GoDaddy :material-book-arrow-up-outline:](https://www.godaddy.com/)
        * [SquareSpace :material-book-arrow-up-outline:](https://www.squarespace.com/)
        * [Wix :material-book-arrow-up-outline:](https://www.wix.com/)
2. Set up hosting (if separate) - [AWS :material-book-arrow-up-outline:](https://aws.amazon.com/amplify/)
3. Design and Build your website (details, socials, roadmap, tooling, etc.) -
    * _SPA Hosting_
        1. [GitHub Pages: :material-book-arrow-up-outline:](https://pages.github.com/)
        * [Amplify :material-book-arrow-up-outline:](https://docs.amplify.aws/)
    * _De-Fi Integrations_
        1. [Web3 :material-book-arrow-up-outline:](https://web3js.readthedocs.io/en/v1.8.0/)
        * [WalletConnect :material-book-arrow-up-outline:](https://docs.walletconnect.com/)
    * _There are tons of free embedded widgets you can find to spruce up your content, but don't go overboard_
    * _If you need something more complex than a single-page application, AWS can cover just about anything, for a relatively cheap price_

### **:material-map-legend: Create your roadmap**

Set realistic goals for your project and make detailed plans to achieve them. The more detail you share, the more confidence you will instill in your investors.

- Utilities - what do you have to offer?
    * _Lottery systems, NFTs with perks_
    * _Staking pool, Rewards calculator_
    * _Telegram/Discord/Twitter bots_
2. Marketing -
    * _Only share top-level strategies (don't show all the cards)_
    * _Traditional cryptosphere advertising (shilling, calls, ads, etc.)_
    * _Real-world presence (charity, merch, billboards/flyers, etc.)_
3. Milestones & Goals (realistic metrics)
4. White Paper (if applicable)

### **:material-palette-swatch: Create your artwork**

One of the largest factors in successfully marketing a project is branding. Advertisements and artwork need to be eye-catching (at least for the type of eyes you're hoping to catch).

- Palette for marketing materials - [Coolors :material-book-arrow-up-outline:](https://coolors.co/)
2. Set of emojis that embody your theme - [Picker :material-book-arrow-up-outline:](https://www.freetool.dev/emoji-picker)
3. Logo, banners, message thumbnails - [DALL·E 2 :material-book-arrow-up-outline:](https://openai.com/dall-e-2/)
4. Sticker pack(s) and memes - [Telegram Sticker Bot :material-book-arrow-up-outline:](https://telegram.me/stickers)
5. Fancy motion graphics - [Fiverr :material-book-arrow-up-outline:](https://www.fiverr.com/search/gigs?query=logo%20animation&source=drop_down_filters&ref_ctx_id=ae09311835cd8acb81d23b7b7e49f78e&search_in=category&search-autocomplete-original-term=logo%20animation&sub_category=104&ref=animation_type%3A2d_reveal%2C3d_reveal%7Cprice_buckets%3A0%7Cdelivery_time%3A1)
6. Art for potential NFTs - [Deforum's Stable Diffusion :material-book-arrow-up-outline:](https://colab.research.google.com/github/deforum/stable-diffusion/blob/main/Deforum_Stable_Diffusion.ipynb)

### **:material-file-document-edit: Create your contract(s)**

Attention to detail is essential during the contract development phase. Ensure your features have been well-tested, and don't become another exploit statistic.

- Decide on tokenomics and liquidity amount -
    * _Unique features tend to do well_
    * _Long-term, would be wise to hold a small % of supply in your deployer wallet_
        1. Fund widget/app pools, listings
        * Giveaways, aidrops, competitions, chat games
2. Decide on anti-abuse measures -
    * _Low max hold, even lower max amount transferred per transaction would be wise_
    * _Optionally blacklist txs within X blocks of launch block, or implement the Pausable Context_
    * _Let potential searchers surrender their trades_
    * _Gradually lower sell tax post-launch_
3. Include your social links, ASCII masterpieces, and easter eggs :material-egg-easter: in the comments
4. Finish any other contracts that need to be prepared at launch
5. Triple-test everything
6. Ensure commonly used tools show no red flags (post-launch) -
    * _[SafeAnalyzerBot :material-book-arrow-up-outline:](https://t.me/SafeAnalyzerbot)_
    * _[TokenSniffer :material-book-arrow-up-outline:](https://t.me/SafeAnalyzerbot)_
    * _[Moonarch :material-book-arrow-up-outline:](https://eth.moonarch.app/)_

***Contract Repo Coming Soon**

### **:material-file-chart: Create your marketing material**

Get ready to present your project. Have informative descriptions/details pre-written for quick posts and rapid sharing.

- Short, medium, and long format copy-texts, variations with and without links -
    * Be brief and genuine, don't oversell yourself or appear desperate for a pump
2. Scheduled tweets/posts for steady engagement
3. Lore/larp -
    * _Anonymous team_
    * _Link some whale wallets_
    * _"For the culture", "Based", "King", etc. You get the point_
4. Script options for potential AMAs; what you've done, are doing, and will do

### **:material-notebook: Create your marketing plan**

Another critically important phase of a healthy project launch is outlining a detailed marketing plan. You're steering the ship; you should know where it's headed... and when. 

- Find a trustworthy group of flooring enthusiasts
2. First pump-to-floor should be from word-of-mouth ONLY
3. Group attitude should highlight the importance of working for your bags, developers are not here to bail you out -
    * _Respectful, honest, clean, clear, and concise communication_
    * _No tolerance for violence, racism, bigotry, or nudity_
    * _Remember that your users & community are a large part of your marketing presence. They represent you_
4. Various competitions, 0% tax bonanzas, active participant giveaways - [Gleam :material-book-arrow-up-outline:](https://gleam.io/app/competitions)
5. Play chat games with the community; bots, polls, media and such, all create entertaining content and can support your project's concept
6. Host or get involved in AMAs/Spaces
7. Costly options -
    * _Calls should be spaced to bring the right volume, at the right time, for the right price. We'd advise against calling your project on launch day_ _**(if they can't hold 24hrs, they won't)**_
        1. Callers rankings - [BSC Grow :material-book-arrow-up-outline:](https://bscgrow.com/who-do-you-follow/)
    * _'SHILL Team Six' (twitter and telegram sers). There are plenty of services you can purchase for a reasonable price. Take care to make sure you choose correctly; and be wary, a wise man once said, "when you see 'RAID IN 3 2 1' in the chat... it's over."_
    * _Message-board posts: [De-Fi Subreddits :material-book-arrow-up-outline:](https://www.reddit.com/search/?q=Fair%20Launch&include_over_18=1&type=sr), [4chan :material-book-arrow-up-outline:](https://boards.4channel.org/biz/), etc._
    * _Relevant Ad Spaces: [Cameo :material-book-arrow-up-outline:](https://www.cameo.com/), [4chan :material-book-arrow-up-outline:](https://www.4channel.org/advertise), [Moonarch :material-book-arrow-up-outline:](https://t.me/MoonarchPromo)_
    * _Farm [coin-voting websites :material-book-arrow-up-outline:](https://tokpie.io/blog/best-token-voting-platforms-free-listing/)_
8. Deliver on roadmap items and spread news of advances
9. Put everything on the calendar

### **:material-package-variant-closed-check: Create your launch plan**

Regardless of scope, nobody wants their token chart to be pumped and dumped from the jump. Pay close attention when constructing your launch formula.

- Be ready with a handful of releases to space out over launch week -
    * _Degenerates need to see new developments every day, or they lose interest/confidence_
    * _Create mini-marketing plans to share new developments (organized shills, community posts, etc.)_
2. Determine whether it will be a public/private presale, or fair launch -
    * _Trusted presaling options - [Pinksale :material-book-arrow-up-outline:](https://www.pinksale.finance/), [Gempad :material-book-arrow-up-outline:](https://gempad.app/presales)_
3. Do a couple dry-runs on the test network, ensure that your contracts are entirely functional
4. Pick a time and date, start the clock - [Embeddable Countdown :material-book-arrow-up-outline:](https://countingdownto.com/)
5. Make sure your flooring enthusiasts are ready

### **:material-rocket-launch: Create your token**

Double check everything you've done up to this point, and everything you plan to do once trading is live. There's no going back (unless you launch a v2 LOL)

- Fund a fresh wallet address with liquidity and deployment funds from a CEX
2. Deploy contract early and unannounced to deter fakes -
    * _Verify contract bytecode at the last minute to deter snipers_
    * _Perform anti-abuse actions_
    * _See [Further Reading](#further-reading)_
3. Lock liquidity pool tokens immediately after adding liquidity - [Unicrypt :material-book-arrow-up-outline:](https://app.unicrypt.network/)
4. Configure telegram bots -
    * _Update Rose's settings for chat, filters for contract, liquidity, tokenomics, swap, etc._
    * _Add and configure buy alert & pricing bots_
        1. [Bog Bot :material-book-arrow-up-outline:](https://tgbot.bogged.finance/home) 
5. Try to be present in your groups chat while people are excited -
    * _Poll to see what your community wants_
    * _Share previews of upcoming releases_
    * _Host events (AMAs, giveaways, games, etc.)_
6. Continue with your marketing plan
7. Work on your roadmap items

!!! success
    ![Cheers!](../extra/img/cheers.png){ align=left } Cheers, to building in the bear market!

### **:material-page-next: Further Reading**

**[How to Deploy Smart Contracts](/docs/deploying)** : Just your need-to-know(s)

<br></br>
[Build the Bear Market :buildthebear-in-progress:](https://www.buildthebear.market){ .md-button }
[GitHub :material-git:](https://github.com/Build-the-Bear){ .md-button }
[Twitter :material-twitter:](https://twitter.com/BuildingtheBear){ .md-button }
[Telegram :material-alert-octagram:](https://www.t.me/BuildtheBear){ .md-button }
