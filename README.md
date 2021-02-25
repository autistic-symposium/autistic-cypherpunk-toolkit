# Awesome Curated NFTs ⇢ From Zero to Hero [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

#### *Musing for that vision of community ownership and token governance*


*"A Non-Fungible Token (NFT) is a cryptographically secured token existing on the blockchain that represents ownership of something unique. NFTs can represent tokenized ownership claims to real-world assets like a specific piece of land, or actual ownership of digital assets as in a rare digital trading card. Unlike fungible tokens such as Bitcoin where one BTC can be exchanged for any other BTC, each NFT is completely unique and represents verifiable digital scarcity."*


### But what is a token?

*"A token is a representation of something in the blockchain: money, time, services, shares in a company, anything. By representing things as tokens, we can allow smart contracts to interact with them, exchange them, create or destroy them."*

*"A token contract is an Ethereum smart contract. "Sending tokens" means "calling a method on a smart contract that someone wrote and deployed". A token contract is a mapping of addresses to balances, plus some methods to add and subtract from those balances. It is these balances that represent the tokens themselves. Someone "has tokens" when their balance in the token contract is non-zero."*

### What is fungibility?

*"Fungible goods are equivalent and interchangeable, like Ether, fiat currencies, and voting rights. Non-fungible goods are unique and distinct, like deeds of ownership, or collectibles."*




----

# Developing on ERC721

*"ERC721 is a standard for representing ownership of non-fungible tokens, that is, where each token is unique."*

* [EIP-721: ERC-721 Non-Fungible Token Standard](https://eips.ethereum.org/EIPS/eip-721).
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




----


# Ethereum

*"Ethereum is a technology that lets you send cryptocurrency to anyone for a small fee."*

*"Ethereum is an open-source, public, blockchain-based distributed ledger featuring smart contract (scripting) functionality. It enables developers to build blockchain applications with business logic that execute in a trustless environment, while leveraging the high availability of the Ethereum network."*

## Start here

* [What's Ethereum](https://ethereum.org/en/what-is-ethereum/)
* [Ethereum Improvement Proposals](https://eips.ethereum.org/).


## Gas

*"Ethereum transaction fees: to transact on the network, users pay gas fees in ETH to miners running the computers that validate, or process, every transaction completed (from simple token transfers to more complex engagements with dapps)."*


* [Check gas price](https://www.gasnow.org/)
* [eth gas station](https://ethgasstation.info/)


## Decentralized trading protocols / Smart contracts

* [Uniswap](https://uniswap.org/)
* [Chainlink](https://chain.link/)
* [OpenZeppelin](https://openzeppelin.com/): libraries of modular, reusable, secure smart contracts for Ethereum network, written in Solidity.


## Ethereum 2.0 (Serenity)


-----------

# Other blockchains

* [Flow](https://www.onflow.org/primer) - "smart contracts assembled like lego blocks".



---

# Artist, creators, and collectors

*"The lesson of Web 2.0: when the process of sharing content with others is owned entirely by private platforms, the cost of this mediation falls heavily on creators."*

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

- [Known Origin](https://knownorigin.io/) - Curated marketplace for rare digital work, featuring artists, on Ethereum, files held on IPFS.
- [Foundation](https://foundation.app/) - Curated marketplace backed on MetaMask wallet, on Ethereum.
- [Digitalax](https://marketplace.digitalax.xyz/): digital fashion engine.
- [Zora.co](https://zora.co/) - Curated marketplace backed on MetaMask wallet, on Ethereum.
- [Nifty Gateway](https://niftygateway.com/) - Market place created by [Gemini](https://www.gemini.com/).
- [OpenSea.io](https://opensea.io/) - Open marketplace on ERC721 and ERC1155.
- [CryptoSlam.io](https://www.cryptoslam.io/)
- [Rarible](https://rarible.com/)
- [Portion](http://portion.io/)
- [SuperRare](https://superrare.co/)
- [Wax](https://wax.io/)
- [NonFungible.com](https://nonfungible.com/)
- [Data.nyc](https://dada.nyc/artgallery)


## Understanding assets

* [NFT Market Overview](https://nonfungible.com/market/history).
* [Crypto slam](https://www.cryptoslam.io/).


## Conceptual collections

* [Rare Pepe Wallet](https://rarepepewallet.com/).
* [CryptoPunks](https://www.larvalabs.com/cryptopunks)
* [Curio Cards](https://curio.cards/)
* [CryptoKitties](https://www.cryptokitties.co/)
* [Maecenas.co](https://www.maecenas.co/) - Fine art investments.

## Competition based NFTs


## Artists worth mention


------


# Socioeconomics of decentralizating the world

## Opinionated articles

* [Some thoughts on token governance and curation](https://medium.com/knownorigin/some-thoughts-on-token-governance-and-curation-a-look-into-a-possible-future-for-knownorigin-41ac900f8a79).
* [Why Decentralization Matters](https://onezero.medium.com/why-decentralization-matters-5e3f79f7638e).
* [Can cryptoart really change the world](https://medium.com/knownorigin/can-cryptoart-really-change-the-world-54f26a4f2821).



## Monetization

*"Protocols such as NFTfi and Rocket allow NFTs to be used as collateral for peer-to-peer loans, enabling holders to treat their digital collectibles like any other asset to be monetized."*

* [NFTfi](https://nftfi.com/).
* [Rocket](https://defirate.com/rocket-nft-loans/).
* [nftx.org](https://nftx.org/#/): platform for making ERC20 tokens that are backed by NFTs (funds, fungible, composable).
    - For example, **CryptoPunks NFT funds**: $PUNK, $PUNK-BASIC, $PUNK-FEMALE, $PUNK-ATTR-4, $PUNK-ATTR-5, $PUNK-ZOMBIE.

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
* **minting**: creating of NFTs. 
* **burning**: destruction NFTs.

----

# Community

* [ETH Global](https://ethglobal.co/)



