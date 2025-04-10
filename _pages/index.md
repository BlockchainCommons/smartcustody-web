---
cover: false
header:
  overlay_color: "#000"
  overlay_filter: "0.00"
  overlay_image: /assets/images/qr-background-lock.jpg
  og_image: /assets/images/sc-card.jpg
title: #SmartCustody Overview
hide_description: true
classes:
  - wide
permalink: /
sidebar:
  nav: subpages
---

_**Latest News:** Added [Improving Multisig Custody with Request & Response](https://github.com/BlockchainCommons/SmartCustody/blob/master/Docs/Scenario-Multisig-RR.md) (2/28/24)._
{: .notice--warning}

<a href="https://bit.ly/SmartCustodyBookV101"><img src="http://www.smartcustody.com/assets/images/book-cover-v1-med.jpg" width=300 align="right"></a>*"The use of advanced cryptographic tools to improve the care, maintenance, control, and protection of digital assets."*

Our goals:

1. Raise the bar on best practices for digital-asset custodianship by building a greater understanding of different custody use cases, risk models, and adversary analyses.
2. Prepare for newer custody technologies that break older models for custodianship.

_#SmartCustody is a project of [Blockchain Commons](https://www.BlockchainCommons.com), who advocates for the creation of open, interoperable, secure & compassionate digital infrastructure to enable people to control their own digital destiny and to maintain their human dignity online._

## The Book

#SmartCustody supports our shared blockchain infrastructure, improving the security of cryptocurrencies, identity wallets, and other digital assets. The first edition of our book on the topic is now out, covering the topic in 186 pages. Thanks to our early patrons, this first edition is free: you can download a [PDF](https://bit.ly/SmartCustodyBookV101) or you can get a [hardcopy from Lulu](https://bit.ly/SmartCustodyBookViaLulu) at cost.

> #SmartCustody Contents
> 
> I. Risk Modeling<br>
> II. Cold Storage Self-Custody Scenario<br>
> III. Adversaries<br>
> IV. Digital Custodianship Responsibilities<br>
> V. The Frank Family Fund Example
>
> [Download the Book](https://bit.ly/SmartCustodyBookV101)<br>
> [Order a Print Copy](https://bit.ly/SmartCustodyBookViaLulu)

We are also preparing to work on [the second edition of the book](https://github.com/BlockchainCommons/SmartCustodyBook/blob/master/TODO.md), which will dramatically expand the content and include new hardware wallets, a multisignature scenario, and information on fidicuary multisigs. You can help us realize this new edition by becoming a [sponsor](https://www.smartcustody.com/sponsors/), either as a [recurring patron at GitHub](https://github.com/sponsors/BlockchainCommons) or by [supporting #SmartCustody with Bitcoins through our BTCPay](https://btcpay.blockchaincommons.com/). Let us know that it's #SmartCustody that interests you!

## The Articles

In advance of the new edition of the book, we are also researching and publishing other articles on #SmartCustody, which can all be found at our [Smart Custody Repo](https://github.com/BlockchainCommons/SmartCustody). These articles focus on some of the newer technologies, which allow even better #SmartCustody.

### New Scenario

A new scenario on multisigs will be the heart of a new book.

* [Multi-sig Self Custody Scenario](https://github.com/BlockchainCommons/SmartCustody/blob/master/Docs/Scenario-Multisig.md) (April 2022) — Scenario for using multisigs (first draft; undergoing review).
    * [Improving Multsigs with Request/Response](https://github.com/BlockchainCommons/SmartCustody/blob/master/Docs/Scenario-Multisig-RR.md) (February 2024) — Why Request/Response methods are needed to create the next generation of more accessible self-sovereign scenarios.

### Multisigs

Multisigs help ensure the resilience of #SmartCustody by eliminating single points of failure and single points of compromise.

* [Designing Multisig for Indepedence & Resilience](https://github.com/BlockchainCommons/SmartCustody/blob/master/Docs/Multisig.md) (March 2021) - Design process & sample multisigs (released).

### SSKR Shares

Shamir's Secret Sharing and other sharding schemes attack resilience from a different direction while maintaining your independence. They allow you to backup your cryptography seeds in a safe, distributed manner.

* [Designing SSKR Share Scenarios](https://github.com/BlockchainCommons/SmartCustody/blob/master/Docs/SSKR-Sharing.md) (August 2021) - How to manage SSKR shares (preliminary)
* [The Dangers of Secret-Sharing Schemes](https://github.com/BlockchainCommons/SmartCustody/blob/master/Docs/SSKR-Dangers.md) (August 2021) - How secret-sharing can be subverted (preliminary)

### Timelocks

Timelocks are the next generation #SmartCustody solution, creating ways to retrieve digital assets if a seed (or even a principal!) is no longer available. 

* [Using Timelocks to Protect Digital Assets](https://github.com/BlockchainCommons/SmartCustody/blob/master/Docs/Timelocks.md) (July 2021) - Using Timelocks (very preliminary).

Also see our experimental [mori-cli](https://github.com/BlockchainCommons/mori-cli) app for a real usage of Timelocks.

### Case Studies

A look at how manufactured hardware devices and released software apps meet #SmartCustody and Gordian ideals.

* [Overview](https://github.com/BlockchainCommons/SmartCustody/blob/master/Docs/Case-Studies-Overview.md) — Details of case study criteria.
   * [Blockchain Commons Seed Tool](https://github.com/BlockchainCommons/SmartCustody/blob/master/Docs/Case-Study-SeedTool.md) — Airgapped Hardware Wallet.
   * [Foundation Devices Passport](https://github.com/BlockchainCommons/SmartCustody/blob/master/Docs/Case-Study-Passport.md) — Airgapped Hardware Wallet.
   * [Sparrow Bitcoin Wallet](https://github.com/BlockchainCommons/SmartCustody/blob/master/Docs/Case-Study-Sparrow.md) — Software Wallet & Transaction Coordinator.
