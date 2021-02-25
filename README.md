# ▲ Curated NFTs resources ⇢ From Zero to Hero ▼ [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

#### TL;DR NFTs are cryptographic tokens that prove authenticity, ownership, and scarcity of digital assets

*A Non-Fungible Token (NFT) is a cryptographically secured token existing on the blockchain representing ownership of something unique. NFTs can represent tokenized ownership claims to real-world assets like a specific piece of land, or actual ownership of digital assets as in a rare digital trading card. Unlike fungible tokens such as Bitcoin where one BTC can be exchanged for any other BTC, each NFT is completely unique and represents verifiable digital scarcity.*


### What is fungibility?

*Fungible goods are equivalent and interchangeable, like Ether, fiat currencies, and voting rights. Non-fungible goods are unique and distinct, like deeds of ownership, or collectibles.*


### What is a token?

*A token is a representation of something in the blockchain: money, time, services, shares in a company, anything. By representing things as tokens, we can allow smart contracts to interact with them, exchange them, create or destroy them.*

*A token contract is an Ethereum smart contract. "Sending tokens" means "calling a method on a smart contract that someone wrote and deployed". A token contract is a mapping of addresses to balances, plus some methods to add and subtract from those balances. It is these balances that represent the tokens themselves. Someone "has tokens" when their balance in the token contract is non-zero.*

* **ERC721**: non-fungible.
* **ERC20**: fungible.





# ✨

----

# Developing on ERC721

*ERC721 is a standard for representing ownership of non-fungible tokens, that is, where each token is unique.*

* [ERC-721 Non-Fungible Token Standard](https://eips.ethereum.org/EIPS/eip-721).
* The ERC721 metadata JSON schema:

```
{
    "title": "Asset Metadata",
    "type": "object",
    "properties": {
        "name": {
            "type": "string",
            "description": "Identifies the asset to which this NFT represents"
        },
        "description": {
            "type": "string",
            "description": "Describes the asset to which this NFT represents"
        },
        "image": {
            "type": "string",
            "description": "A URI pointing to a resource with mime type image/* representing the asset to which this NFT represents. Consider making any images at a width between 320 and 1080 pixels and aspect ratio between 1.91:1 and 4:5 inclusive."
        }
    }
}
```

## Articles 

* [How to get Random numbers in a NFT, Chainlink](https://blog.chain.link/random-numbers-nft-erc721/).
* [How to build a blockchain lotery in Chainlin](https://blog.chain.link/how-to-build-a-blockchain-lottery-2/).


## Solidity



# ✨
----

# Blockchains



## How it works

* Whenever a node wishes to include a new transaction in the blockchain, it sends it to its peers, who then send it to their peers, and so on. In this way, it propagates throughout the network. 
* Certain nodes, called miners, maintain a list of all of these new transactions and use them to create new blocks, which they then send to the rest of the network. 
* Whenever a node receives a block, it checks the validity of the block and of all of the transactions therein and, if valid, adds it to its blockchain and executes all of said transactions. 
* As the network is non-hierarchical, a node may receive competing blocks, which may form competing chains. The network comes to consensus on the blockchain by following the "longest chain rule", which states that the chain with the most blocks at any given time is the canonical chain. This rule achieves consensus because miners do not want to expend their computational work trying to add blocks to a chain that will be abandoned by the network.


## Consensus protocols

* **Proof-of-Work (PoW)**: used by Bitcoin's protocol. Validate transactions to the miners, who are the nodes solve cryptographic, or mathematical problems, using their computers. Miners who solve a problem and validate and enable a block record are rewarded with bitcoin.
* **Proof-Of-Stake (PoS)**: used by Ethereum. Forgers (instead of miners) stake an amount of cryptocurrency which allows them a chance, based on probability, to be a block validator. The successful forger receives the relevant block transaction fees as a reward. 
* **Proof-of-Authority (PoA)**: more centralized, it has predetermined block validators. New blocks on a blockchain are only created when the validators are in majority. Used by a newer blockchain, Elysian.


---

## Ethereum

*Ethereum is a technology that lets you send cryptocurrency to anyone for a small fee.*

*Ethereum is an open-source, public, blockchain-based distributed ledger featuring smart contract (scripting) functionality. It enables developers to build blockchain applications with business logic that execute in a trustless environment, while leveraging the high availability of the Ethereum network.*

* [What's Ethereum](https://ethereum.org/en/what-is-ethereum/)
* [Ethereum Improvement Proposals](https://eips.ethereum.org/).


### Ether (Ξ)

*Ether (ETH) is the cryptocurrency generated by the Ethereum protocol as a reward to miners in a proof of work system for adding blocks to the blockchain.*

### Accounts

* **user accounts**: create transactions, which must be signed using the account's private key, a 64-character hexadecimal string that should only be known to the account's owner (signature algorithm is ECDSA). 

* **contracts**: associated code and storage (the values of the variables at any given time). For instance, it might send ETH, alter its storage values, create temporary storage, call any of its own functions, call any public function of a different contract, create a new contract, and query information about the current transaction or the blockchain.


### Virtual machine

*The Ethereum Virtual Machine (EVM) is the runtime environment for smart contracts in Ethereum. It is a 256-bit register stack designed to run the same code exactly as intended (a fundamental consensus mechanism for Ethereum).*


### Gas

*Ethereum transaction fees: to transact on the network, users pay gas fees in ETH to miners running the computers that validate, or process, every transaction completed (from simple token transfers to more complex engagements with dapps). it's a unit of accounT within the EVM.*

*This fee mechanism is designed to mitigate transaction spam, prevent infinite loops during contract execution, and provide for a market-based allocation of network resources.*


* [Check gas price](https://www.gasnow.org/)
* [eth gas station](https://ethgasstation.info/)


### Smart contracts

* [Chainlink](https://chain.link/)
* [OpenZeppelin](https://openzeppelin.com/): libraries of modular, reusable, secure smart contracts for Ethereum network, written in Solidity.



### Decentralized trading protocols 

* [Uniswap](https://uniswap.org/)


### Ethereum 2.0 (Serenity)

*The main purpose of the upgrade is to increase transaction throughput for the network from the current of about 15 transactions per second to up to tens of thousands of transactions per second.*

*Increase throughput by splitting up the workload into many blockchains running in parallel (sharding), having them all share a common consensus proof of stake blockchain.*


### Security

* In 2016, a flaw in The DAO was exploited to steal $50 million of Ether. As a result, the Ethereum community voted to hard fork the blockchain to reverse the theft. Ethereum Classic (ETC) continued as the original chain.



# ✨
-----------

## Other blockchains

* [Flow](https://www.onflow.org/primer): "smart contracts assembled like lego blocks".



---

# Artist, creators, and collectors

*The lesson of Web 2.0: when the process of sharing content with others is owned entirely by private platforms, the cost of this mediation falls heavily on creators.*

## Collectibles

* [CryptoKitties](https://www.cryptokitties.co/): the first digital asset to use the ERC721 asset standard for NFTs (in 2017).
* [Rare Pepe Wallet](https://rarepepewallet.com/)
* [Non fungible pepes](https://nonfungiblepepe.com/): set of 1069 NFTs.
* [Bullrun Babes](https://www.bullrunbabes.com/rules): set of 888 NTFs, based on Legend cards.
* [CryptoPunks](https://www.larvalabs.com/cryptopunks)
* [Curio Cards](https://curio.cards/)
* [Joy World](https://www.joy.world/)


## Minting Platforms

* [infiNFT](https://infinft.com/): on-chain metadata and image storage, available for 3D, audio, multiple files.


## Upcoming technologies

### Zora Protocol

[Zora Protocol](https://zora.engineering/whitepaper) is a universal market protocol for media ownership. Creators can set a perpetual ownership stake in their work, and are rewarded whenever ownership changes hands. Based on Ethereum blockchain and ERC-721 tokens.

   - Each piece of media is embedded with a market, consisting of a transparent pool of bids.
   - Whenever a bid is accepted, or an ask fulfilled, the piece of media is transferred to the buyer, and the funds from that bid are split amongst its shareholders. There can be up to three shareholders for a piece of media: the owner, the previous owner, and the original creator.
   - Zora protocol introduces integrity checks to ensure that media and its metadata is provably unique. The representation of media on the Zora protocol is two URI pointers: one to the metadata, and one to the content itself (the URI can be updated, but the sha256 checksums representing the data they point to may not).
   - Uses Bids to represent buy-side liquidity for a piece of media and specifies an ERC-20 currency to be bid with (allowing for a market of many currencies to exist for the media):

```
struct Bid {
    // Amount of the currency being bid
    uint256 amount;
    // Address to the ERC20 token being used to bid
    address currency;
    // Address of the bidder
    address bidder;
    // Address of the recipient
    address recipient;
    // % of the next sale to award the previous owner
    Decimal.D256 sellOnFee;
}

struct Ask {
    // Amount of the currency being asked
    uint256 amount;
    // Address to the ERC20 token being asked
    address currency;
    // % of the next sale to award the seller
    Decimal.D256 sellOnFee;
}
```




## Marketplaces on NFTs

- [Known Origin](https://knownorigin.io/): curated marketplace for rare digital work, featuring artists, on Ethereum, files held on IPFS.
- [Foundation](https://foundation.app/): crated marketplace backed on MetaMask wallet, on Ethereum.
- [Digitalax](https://marketplace.digitalax.xyz/): digital fashion engine.
- [Zora.co](https://zora.co/): curated marketplace backed on MetaMask wallet, on Ethereum.
- [Nifty Gateway](https://niftygateway.com/): market place created by [Gemini](https://www.gemini.com/).
- [OpenSea.io](https://opensea.io/): open marketplace on ERC721 and ERC1155.
- [CryptoSlam.io](https://www.cryptoslam.io/): collect digital cards.
- [Rarible](https://rarible.com/): community-owned NFT marketplace.
- [SuperRare](https://superrare.co/): collect digital art work.
- [Wax](https://wax.io/): decentralized video game and entertainment network.
- [NonFungible.com](https://nonfungible.com/): database of blockchain gaming and crypto collectible markets.
- [Data.nyc](https://dada.nyc/artgallery): collection of virtual conversations.
- [Maecenas.co](https://www.maecenas.co/): fine art investments.
- [Portion](https://portion.io/): premier online marketplace.


### Artists worth mention


## Understanding assets

* [NFT Market Overview](https://nonfungible.com/market/history).
* [Crypto slam](https://www.cryptoslam.io/).





# ✨
------


# Socioeconomics of decentralizating the world

## Opinionated articles

* [Some thoughts on token governance and curation](https://medium.com/knownorigin/some-thoughts-on-token-governance-and-curation-a-look-into-a-possible-future-for-knownorigin-41ac900f8a79).
* [Why Decentralization Matters](https://onezero.medium.com/why-decentralization-matters-5e3f79f7638e).
* [Can cryptoart really change the world](https://medium.com/knownorigin/can-cryptoart-really-change-the-world-54f26a4f2821).



## Monetization

*Protocols such as NFTfi and Rocket allow NFTs to be used as collateral for peer-to-peer loans, enabling holders to treat their digital collectibles like any other asset to be monetized.*

* [NFTfi](https://nftfi.com/).
* [Rocket](https://defirate.com/rocket-nft-loans/).
* [nftx.org](https://nftx.org/#/): platform for making ERC20 tokens that are backed by NFTs (funds, fungible, composable).
    - For example, **CryptoPunks NFT funds**: $PUNK, $PUNK-BASIC, $PUNK-FEMALE, $PUNK-ATTR-4, $PUNK-ATTR-5, $PUNK-ZOMBIE.


# ✨
-----

# Acronyms and concepts

* **DeFi**: decentralized finance.
* **DApps**: decentralized applications (which can include games, digital collectibles, online-voting systems, financial products and many others).
* **DAOs**: decentralized autonomous organizations (MakerDao is an example).
* **DEXs**: decentralized exchanges ([Uniswap](https://uniswap.org/) is an example).
* **AMMs**: automated market Mmkers.
* **Stablecoins**: offers users vital means of storing and transferring value on the blockchain, without exposing them to volatility.
* **DAI**: stablecoin cryptocurrency, maintained by MakerDao. 
* **Chainlink VRF**: verifiable randomness function that allow developers to apply random traits to an NFT.
* **minting**: creating of NFTs (the process of validating information, creating a new block, and recording that information into the blockchain).
* **burning**: destruction NFTs.


# ✨
----

# Community

* [ETH Global](https://ethglobal.co/)



