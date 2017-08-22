# Ethereum: Tokens and ICOs

### Table of contents
1. [Topic](#topic)
2. [Requirements](#requirements)
3. [What is Ethereum?](#what_is_ethereum)
4. [What is a Ethereum Token?](#what_is_ethereum_token)
5. [What is a ICO?](#what_is_ico)
6. [What is Embark?](#what_is_embark)
7. [Token Factory](#token_factory)
8. [Conclusion](#conclusion)
9. [References](#references)

### Topic <a name="topic"></a>

To investigate Ethereum ecosystem with focus on token creation and ICOs

### Requirements <a name="requirements"></a>

* [TestRPC](https://github.com/ethereumjs/testrpc): Node.js based Ethereum client for testing and development. It uses ethereumjs to simulate full client behavior and make developing Ethereum applications much faster. It also includes all popular RPC functions and features (like events) and can be run deterministically to make development a breeze.

* [Embark](https://github.com/iurimatias/embark-framework): Framework that allows you to easily develop and deploy Decentralized Applications (DApps)

### What is Ethereum? <a name="what_is_ethereum"></a>

>Ethereum is a decentralized platform that runs smart contracts.

One of the most interesting things about Ethereum are smart contracts which can be described as highly programmable digital money. Imagine automatically sending money from one person to another but only when a certain set of conditions are met.

Many of the centralized systems we use today could be built in a decentralized manner on Ethereum. With Ethereum you can make these transactions trustless which opens up an entire world of decentralized applications

### What is a Ethereum Token? <a name="what_is_ethereum_token"></a>

Ethereum tokens are simply digital assets that are being built on top of the Ethereum blockchain. They benefit from Ethereum’s existing infrastructure instead of developers having to build an entirely new blockchain. They also strengthen the Ethereum ecosystem by driving demand for ether, the native currency of Ethereum, needed to power the smart contracts.

Ethereum tokens can represent anything from a physical object like gold (Digix) to a native currency used to pay transaction fees (Golem). In the future, tokens may even be used to represent financial instruments like stocks and bonds

### What is a ICO? <a name="what_is_ico"></a>

Tokens are often issued to the public through a crowd sale called an initial coin offering (ICO). The creators of the token will issue the token to others in exchange for ether and sometimes bitcoin and other digital currencies. There have been many ICOs recently and in a short time they have completely changed the way projects are funded. There is no requirement that tokens must be well distributed, although if you are building a decentralized application ideally you want the tokens to be owned by as many people as possible.

Example of real ICO:
>The SNT ICO begins on Tuesday, the 20th of June, at 2PM GMT. 10,000 SNT tokens will be created for every ETH sent to the fund, with a maximum amount of 12 million Swiss francs being the ceiling.

### What is Embark? <a name="what_is_embark"></a>

>Embark is a framework that allows you to easily develop and deploy Decentralized Applications (DApps). Embark currently integrates with EVM blockchains (Ethereum), Decentralized Storages (IPFS), and Decentralized communication platforms (Whisper and Orbit).

This project has been developed with Embark.

### Token Factory <a name="token_factory"></a>

In order to issue tokens to the public it is needed a token factory. In app/contracts you can find a smart contract code to issue simple, standards-compliant tokens on Ethereum. It can be used to create any form of asset, currency, coin, hours, usage tokens, vunk, etc. The default is token.sol which ONLY implements the core ERC20 standard functionality.

Once you run testRPC and Embark you can access to the URL provided. You will find an interface that allows you to interact with tokens.

### Conclusion <a name="conclusion"></a>

To develop smart contracts is not a difficult task for simple issues. However, if you want to develop complicated software within a smart contract you will find some difficulties. Solidity (the language chosen to develop smart contracts) is under development and needs more time to become a powerful language.

The proliferation of new decentralization application platforms and independent blockchains has added additional difficulty to surveying the universe of tokens, as investors must not only analyze the application or system, but also the base protocol or infrastructure layer (like ethereum, waves or lisk) in numerous cases.

Still, with proven demand and interest from both entrepreneurial and investor audiences and limited regulatory guidance, ICOs could continue to gain steam as a fundraising mechanism. How the structures, valuations and legalities evolve is a much larger question, but undoubtedly the continued and growing wave of token sales will focus the spotlight on each of these questions and more

### References <a name="references"></a>
* [https://blog.coinbase.com/a-beginners-guide-to-ethereum-tokens-fbd5611fe30b](https://blog.coinbase.com/a-beginners-guide-to-ethereum-tokens-fbd5611fe30b)
* [https://blog.coinbase.com/a-beginners-guide-to-ethereum-46dd486ceecf](https://blog.coinbase.com/a-beginners-guide-to-ethereum-46dd486ceecf)
* [https://www.ethereum.org](https://www.ethereum.org)
* [https://blockgeeks.com/guides/ethereum-token/](https://blockgeeks.com/guides/ethereum-token/)
* [https://hackernoon.com/how-to-create-a-token-factory-with-ethereum-part-1-85e84d1f38fc](https://hackernoon.com/how-to-create-a-token-factory-with-ethereum-part-1-85e84d1f38fc)
* [https://hackernoon.com/how-to-create-a-token-factory-with-ethereum-part-2-ce96a31a5f59](https://hackernoon.com/how-to-create-a-token-factory-with-ethereum-part-2-ce96a31a5f59)
* [https://github.com/iurimatias/embark-framework](https://github.com/iurimatias/embark-framework)
