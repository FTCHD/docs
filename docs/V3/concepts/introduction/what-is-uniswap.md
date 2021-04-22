---
id: what-is-uniswap
title: What Is Uniswap
---

The Uniswap protocol is a peer-to-peer system designed for exchanging cryptocurrencies [(**ERC-20 Tokens**)](https://ethereum.org/en/developers/docs/standards/tokens/erc-20/) on the [**Ethereum**](https://ethereum.org/) blockchain. The protocol is implemented as a set of persistent, non-upgradable smart contracts democratically governed by [**Uniswap Governance**](https://gov.uniswap.org/).

The Uniswap protocol is built to prioritize censorship resistance, security, self-custody and to function without any trusted intermediaries who may seek to collect fees or selectively restrict access. 

There are currently three versions of the Uniswap protocol. V1 and V2 are open source and licensed under GPL. V3 is open source with slight modifications, which are viewable [**here**](https://github.com/Uniswap/uniswap-v3-core/blob/main/LICENSE). Each version of Uniswap, once deployed, will function in perpetuity providing the continued existence of the Ethereum blockchain. 

## How does the Uniswap protocol compare to a typical market?

To understand how the Uniswap protocol differs from traditional markets, it is helpful to first look at two subjects: How Automated Market Maker design deviates from traditional order book markets, and how permissionless system design departs from conventional permissioned systems.

### Order Book VS AMM

Most publicly accessible markets use an [**order book**](https://www.investopedia.com/terms/o/order-book.asp) style of exchange, where buyers and sellers create orders organized by price level that are progressively filled as demand shifts. Anyone who has traded stocks on the public markets will be familiar with an order book system.

The Uniswap protocol approaches the problem differently, using an Automated Market Maker (AMM), sometimes referred to as a Constant Function Market Maker, in place of an order book.

At a very high level, an AMM replaces the buy and sell orders in an order book market with a liquidity pool of two assets, both valued relative to each other. As one asset is traded for the other, the relative price of the two assets shift, and a new market rate for both is determined. In this dynamic, a buyer or seller trades directly with the pool, rather than with specific orders left by other parties. The advantages and disadvantages of automated market makers versus their traditional order book counterparts are under active research by a growing number of institutions and universities. We have collected some notable examples on our research page.

### Permissionless Systems

The second primary departure from traditional markets is the permissionless design of the Uniswap protocol. Permissionless design means there are fundamental mechanisms within the protocol that are entirely open for public use, with no selective restriction on who can or cannot use them.

Permissionless systems are a little tricky to intuitively understand at first, some light research will give plenty of examples of permissionless systems that will help build context. We will be exploring the details of permissionless functionality within the Uniswap Protocol in future docs.

## Where can I find more information

For research into the economics of AMMs, game theory, or optimization research, check out our [**research**](https://docs.uniswap.org/concepts/advanced/research) page. 

For new features implemented in V3 that expand and refine AMM design, see the [**V3 Concepts**](https://docs.uniswap.org/concepts/V3-overview/concentrated-liquidity) page.