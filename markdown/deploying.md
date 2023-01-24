# **:material-account-cowboy-hat: How to Deploy Contracts**
!!! warning
    Document under construction and subject to change. Not to be considered a comprehensive guide.

Deploying smart contracts is easy... ensuring they function as intended is the hard part. Seems like there's a de-peg, bridge exploit, flash loan, or exchange meltdown every week around here.

In order to effectively deploy and manage **anything**, you should have a strong grasp of the EVM's capabilities and limitations.
Take some time to read up on anything you may be unfamiliar with; if you're unsure where to start, try the [Ethereum Development Documentation :material-book-arrow-up-outline:](https://ethereum.org/en/developers/docs/).
You should also take some time to read up on relevant specification details, or at least see what's cooking with [Ethereum Improvement Proposals :material-book-arrow-up-outline:](https://eips.ethereum.org/).
<hr>
### **:material-check-network-outline: Configure your network **

Once you're comfortable with those foundational concepts, go ahead and get yourself set up on the testnet of your choice; you should be able to add a new network connection 
in your wallet settings, then find a faucet to fund your wallet (yes, you may need to do a little research)

??? example
    === "Ethereum Mainnet"
    
        ``` 
            RPC: https://mainnet.infura.io/v3/9aa3d95b3bc440fa88ea12eaa4456161
            Chain ID: 1
            Symbol: ETH
            Explorer: https://etherscan.io
        ```
        
    === "Goerli Testnet"
    
        ``` 
            RPC: https://goerli.infura.io/v3/9aa3d95b3bc440fa88ea12eaa4456161
            Chain ID: 5
            Symbol: ETH
            Explorer: https://goerli.etherscan.io
        ```
    
    - [RPCs for all EVM chains](https://rpc.info/)

    - [Network connection tool for all EVM chains](https://networks.vercel.app/)

### **:material-developer-board: Configure your IDE **

For your first couple contracts, you should need nothing more than [Remix :material-book-arrow-up-outline:](https://remix-project.org/).

Remix allows you to develop, compile, debug, deploy, and interact with contracts; no setup required, no dependencies to install. They offer both web and desktop versions, with plugins to make the process even easier.

Other common editors have some widely used Solidity & Ethereum plugins if you want to try and stick with what you're using, but they're likely not maintained by the Ethereum Foundation, which Remix has going for it.
However, there are dozens of configurations one might prefer, as this technology naturally breeds extension and customization.

Following are links to documentation for several commonly used tools and packages you should take a look at:

- **[Truffle :material-book-arrow-up-outline:](https://trufflesuite.com/docs/)** - A suite of tools for building, testing, and deploying smart contracts. Offers a development environment for building dApps.
- **[Ganache :material-book-arrow-up-outline:](https://trufflesuite.com/docs/ganache/)** - Allows you to build and test on a local blockchain. Provides a simple interface testing contracts, including the ability to generate test data and track execution.
- **[OpenZeppelin :material-book-arrow-up-outline:](https://docs.openzeppelin.com/)** - An open-source framework for building secure contracts. Provides a library of reusable code, as well as tools for testing and deploying.
- **[HardHat :material-book-arrow-up-outline:](https://hardhat.org/docs)** - A framework that covers just about everything listed above; automated testing, debugging, integration with tools like Truffle and Remix, UI for contract interaction, etc.
- **[Geth :material-book-arrow-up-outline:](https://geth.ethereum.org/docs)** - An Ethereum CLI client written in Go. Allows users to run a full Ethereum node and interact with the blockchain.

Each has their own strengths and weaknesses of course, but most of them can get you where you need to go. Take some time to **DYOR**.

### **:material-newspaper-variant-multiple-outline: Configure your contract details **

It would be wise to familiarize yourself with any official library / interface implementations you plan to include in your contract(s).
For example, if you're planning to use the ERC-20 token interface, get comfortable with the specification's offerings and limitations before-hand.

#### Organization / Readability
  - Think carefully about the structure and organization of your contract, as well as its readability for those reviewing or working with it. Good organization and readability makes it easier to understand and maintain the contract.
  - Smart contracts can be written as a single file or as multiple files that are then compiled into one contract. The choice between these options depends on the complexity of the contract and your preference.
  - There are no strict formatting rules, but the most common practice is to put the state variables at the top, then the constructor, then functions.
  - Adopting a consistent naming convention can make it easier to understand and work with the contract. We'd suggest camelCase or snake_case.

#### Bytecode Verification
  - Much of DeFi's appeal is the public immutability of contracts and transactions between them. You should always verify the bytecode of a smart contract you've published on-chain; for obvious reasons
  - Verification is easy to do directly on the official chain explorer, but some the tools we've mentioned have the ability to verify bytecodes automatically, post-deployment

<hr>

#### Contract Parameters
Many contracts require additional setup, post-deployment; all the tools we've covered in this document either have a command line, or graphical user interface that allow you to interact with / operate smart contracts you've deployed. Etherscan and all variations of it have the very same.

#### Contract Security
Many contracts require additional setup, post-deployment; all the tools we've covered in this document either have a command line, or graphical user interface that allow you to interact with / operate smart contracts you've deployed. Etherscan and all variations of it have the very same.
<hr>
As mentioned above, the [Ethereum Development Documentation :material-book-arrow-up-outline:](https://ethereum.org/en/developers/docs/) covers much of what we touched on here in more detail if you are unfamiliar with a particular concept.

!!! success
    ![Cheers!](../extra/img/cheers.png){ align=left } Cheers, you're a deployooor!

<br></br>
[Build the Bear Market :buildthebear-btb-logo-alpha:](https://www.buildthebear.market){ .md-button }
[GitHub :material-git:](https://github.com/Build-the-Bear){ .md-button }
