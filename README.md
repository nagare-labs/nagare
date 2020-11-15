# nagare (流れ)

A github home for the `nagare (流れ)` ecosystem. It is a culmination of several projects curated for its unique stance in the web3 world.

A web3 **on-chain RPC** (ocRPC) framework for decentralised applications (DApps) to establish streams inter/intra blockchain networks.

## Mascot

![Mascot](images/nagare-mascot-00.png)

## Contents

1. [Executive Summary](#executive-summary)
1. [Demo Video](#demo-video)
1. [Architecture](#architecture)
1. [Details](#details)
1. [Ecosystem Roadmap](#ecosystem-roadmap)
1. [Live Demo](#live-demo)
1. [Built With](#built-with)
1. [Authors](#authors)
1. [License](#license)
1. [Acknowledgements](#acknowledgements)

## Executive Summary

### Context

The year 2020 has seen unprecidented amount of build activity in the web3 space across several blockchain projects. One such category is `DeFi` and many layer-1 blockchain networks are seeking to attract developers to build on their respective chain(s) and web3 technology stack.

There are only a select few number of web3 engineers globally available and they tend to stick with the chain &/ technology stack they first discovered, built on, and continued to invest their time.

For web3 to break out of its current niche or micro-niche bubble, and gain mass adoption, us founders and engineers have to create pathways and remove hurdles (if any) for developers (across web3 and web2) to be able to build as many ideas, on any chain/network, using their preferred technology stack.

### Problem

Developers often pick a network (with big marketcap), a technology stack (with largest community), a category/idea (with a propensity for transaction flow) ...assuming they will be able to attract and retain a large number of users/customers.

This limits their ability to experiment on other innovative chains and technology stacks, so as to build & launch a web3 product that might be closer to achieving `problem-solution` | `product-market` | `founder-industry` fit.

What if there was a way and means for developers and DApps to be able to connect to other interesting chains (using bridges) and establish continuous streams per Time cycles (seconds, minutes, hours, days, week, months).

### Solution

The thesis being multiple chains are here to stay and one of many ways to integrate/inter-operate them and allow web3 product transactions to flow in-between them is by building and using bridges.

For DApps to be able to `stream` transactions across chains, we offer an on-chain RPC (ocRPC) framework and easy to connect set of smart contracts that enables DApps to direct their cross-chain streams through them.

Imagine Over-The-Top (OTT) cross-chain streaming framework for web3 products & services using the already existing and proven layer-1 blockchain networks and bridges.

### Technology

There are several technology platforms to choose from. However, we are going with projects that have used or planning to use `Rust` as one of their core tenants. Additionally we love learning and building on Rust 🦀.

For streaming to be fast, seamless, cost effective we chose `Solana` & `Wormhole` as the cornerstone building blocks (chain & bridge respectively) and we love their passion for shipping code on a weekly basis.

### Idea

Our biggest assumption here is, Wormhole will be(come) the cross-chain specifications and standards for any/all bridges from/to the `Solana` network.

Using `Wormhole` as a catalyst, we intend to big-bang the `nagare (流れ)` ecosystem.

What `Wormhole` does for cross-chain bridges -- `nagare` does for cross-chain streams.

## Demo Video

Coming Soon ...due to some unforeseen issues, rebuilding it now.

## Architecture

![Architecture](archs/nagare-arch-00.png)

## Details

...details will be available soon and progressively.

## Ecosystem Roadmap

In `Phase-0` we intend to work with `Wormhole` team to bootstrap the testing and deployment of **Solana - Etherem** bridge in their respective testnets and mainnets.

In `Phase-1` as and when the `Wormhole` bridge is operational between Solana testnet and Ethereum testnet, we shall deploy our Solana smart contract `sNAGARE` and deploy our Ethereum smart contract `eNAGARE`.

In `Phase-2` as and when a bridge (Wormhole preferred) becomes available between Solana testnet and Cosmos testnet, we shall enhance our Solana smart contract `sNAGARE` and deploy our Cosmos smart contract `cNAGARE`.

In `Phase-3` as and when a bridge (Wormhole preferred) becomes available between Solana testnet and Polkadot testnet, we shall enhance our Solana smart contract `sNAGARE` and deploy our Polkadot smart contract `pNAGARE`.

nagare (流れ) smart contacts:
```
sNAGARE (in Solana network)
eNAGARE (in Ethereum network)
cNAGARE (in Cosmos network)
pNAGARE (in Polkadot network)
```

## Live Demo

Work In Progress (WIP) ...awaiting for certain projects to be deployed onto their respective testnets and/or mainnets.

## Built With

* [Solana](https://solana.com/)
* [Ethereum](https://ethereum.org/en/)
* [Wormhole](https://github.com/certusone/wormhole)
* [Superfluid](https://www.superfluid.finance/)
* [Chainlink](https://chain.link/)
* [API3](https://api3.org/)
* Coming Soon
* Coming Soon

## Authors

* **PK Rasam** - *Initial work* - [pkrasam](https://github.com/pkrasam)

## License

The `nagare (流れ)` ecosystem is licensed under the Apache 2 License - see the [LICENSE](LICENSE) file for details. For the list of projects that were used to build this ecosystem, please do refer to their individual license terms.

## Acknowledgments

* [PK Rasam](https://github.com/pkrasam)