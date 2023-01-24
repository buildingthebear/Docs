# **:material-account-cowboy-hat: How to Mint NFTs**
!!! warning
    Document under construction and subject to change. Not to be considered a comprehensive guide.

So you're looking to mint some NFTs on an EVM blockchain, eh? We can get you squared away. First thing's first... what are you planning to mint?
<hr>
### **:material-package-variant: Choose your concept**

Following are some questions you may want to ask yourself:

- **What will your token(s) be used for?**
    * _Vanity? Private access? Yield farming? Trading? Collecting? Historical references?_
- **Do you intend to publish a collection? Maybe just a handful of NFTs? One?**
    * _Complexity and toolsets can vary greatly depending on the scope of your project_
- **What media/metadata needs to be included?**
    * _Audio/Video NFTs, Collectibles/Traits, Custom data/JSON, etc._
    
Once you have those answers (and any applicable assets), it's time to think about minting.

### **:fontawesome-solid-road-bridge: Choose your platform **

There are many ways to mint an NFT; both free and paid tools are available, with all variety of customizations.
However, publishing your own contract is almost as simple as using those tools... provided you know what you're doing; let's talk about it.

!!! info
    **Be sure that you have an understanding of the difference between on-chain and on-site NFTs. Depending on the platform, you may or may not be interacting directly with the blockchain on every transaction**

So you've got a concept...

<hr>
- **Do you just want to mint something?**
    * _The most widely used platforms support many of the options you may be considering, and may be the path of least resistance - [OpenSea :material-book-arrow-up-outline:](https://opensea.io/), [NiftyKit :material-book-arrow-up-outline:](https://niftykit.com/), more below_
    * _There are many NFT minting services with various strengths, but try to stay away from less known tools until you've done your due diligence_
- **Do you know what type of NFT(s) you want to mint? If you intend to use a third party, be sure they support the type and characteristics you're looking for**
    * _Traditional - [EIP-721 :material-book-arrow-up-outline:](https://eips.ethereum.org/EIPS/eip-721)_
    * _Multi-Token - [EIP-115 :material-book-arrow-up-outline:](https://eips.ethereum.org/EIPS/eip-1155)_
    * _Royalty - [EIP-2981 :material-book-arrow-up-outline:](https://eips.ethereum.org/EIPS/eip-2981)_
<hr>
- **Do you want to be in control of the minting process?**
    * _You could roll your own interface, or use a combination of third-party tools/embeds_
- **Do you want control of the contract?**
    * _If you don't want to manage the overhead, or would prefer to avoid technical burden of any sort... a platform may be best suited for your needs. They will (hopefully) always have an interface for you to easily manage your contract or collection_
    * _If you **DO** want to deploy your own NFT contract, See [Further Reading](#further-reading)_
<hr>

!!! info
    === "Using a Third Party"
        - Pre-built interfaces, mostly customizable
        - Contract likely to be audited, easy setup
        - Low barrier to entry, room to learn more
        - Scalability, built-in audience
    
    === "Rolling Your Own"
        - Lower costs, no third-party stakes
        - Entirely customizable, open-ended flexibility
        - Ownership, transparency, interoperability, branding, etc
        - **You will learn A LOT more**

### **:material-tools: Choose your details**

So you've got a path forward...

Once you've decided on a home for your minting interface, and are hosting the asset data on a distributed filesystem (both of which most common platforms will do for you nowadays), you're ready to fine-tune the details.

- **Are there attributes you need to include?**
- **Do you need to set up royalties?**
- **Who is able to mint? And when?** e.g. Pre-Sale, Whitelist, Pre-Determined Launch Time

Most of the following platforms will cover all of that, wrapped up in a nice GUI. There's usually no need for you to re-invent the wheel unless you want full control of the contract for specific reasons.

- **[OpenSea: :material-book-arrow-up-outline:](https://opensea.io/)** Most popular marketplace with largest selection / community, multi-chain.
- **[Rarible: :material-book-arrow-up-outline:](https://rarible.com/)** Basically the same deal as OpenSea, but they also have their own token.
- **[SuperRare: :material-book-arrow-up-outline:](https://superrare.com/):** More curated marketplace, generally higher quality content.
- **[Nifty Gateway: :material-book-arrow-up-outline:](https://www.niftygateway.com/)** Basically the same deal as SuperRare, just different branding and artists.

This a just to name a few, there are probably dozens of options now. If you're using a third party, take your time to find the right fit for your project. It's important to cultivate the experience you're looking to portray; one platform may have a feature set, or even an aesthetic that suits you better. Browse what's available.

If you're not using a third party, you'll have to add whatever functionality is needed within your contract.
For tips on certain collection management operations, you should check out some verified contracts' source code for popular NFT projects from various platforms on Etherscan.

e.g. [Build the Bear Early Adopters Contract: :material-book-arrow-up-outline:](https://etherscan.io/address/0xa501815a0cc500e6261ff85f3d9af3609d987a59#code)

### **:material-crystal-ball: Choose your future **

So you're ready to get moving...

Perhaps most importantly, you need to **follow through** with your concept. Be true to yourself, and your collectors; do not over-promise, and do not under-deliver.
This technology is as young as it is useful (very); there are many iterations of trends, and phases of improvement yet to be uncovered.

!!! success
    ![Cheers!](../extra/img/cheers.png){ align=left } Cheers, to being non-fungible!

### **:material-page-next: Further Reading**

**[How to Deploy Smart Contracts](/docs/deploying)** : Just your need-to-know(s)

<br></br>
[Build the Bear Market :buildthebear-btb-logo-alpha:](https://www.buildthebear.market){ .md-button }
[GitHub :material-git:](https://github.com/Build-the-Bear){ .md-button }
