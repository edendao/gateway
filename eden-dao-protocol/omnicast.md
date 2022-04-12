---
description: A public goods protocol for omnichain message reading and writing.
---

# 📻 Omnicast

> _From Cyrus, April 8th, 2022_
>
> **To my fellow Eden Daoists,**
>
> Like other DAOs, we spent a lot of time weighing the tradeoffs of different chains. As a long-term thinker, I felt dissatisfied with being locked in on a single chain. This caused its fair share of deliberation, which no doubt other DAOs are familiar with.&#x20;
>
> We can't onboard the next billion users in crypto if we each spend months deciding where to launch on. On-chain data is fragmented. Users can't carry their data with them across chains.&#x20;
>
> We wanted to build an NFT that users could take with themselves across the omnispace. As is often the case in crypto, we needed infrastructure that hadn't been built yet.
>
> So we built it.&#x20;

At the foundation of the Eden Dao Protocol is public goods infrastructure to **harmonize data across the **_**omnispace**_** — the space on, between, and around the chains.** This unlocks the power that was required for Web3 users to travel cross-chain, while facilitating adoption and amplifying the impact of mission-driven protocols.&#x20;

Without further ado, here are the first releases of our developing ecosystem. We're excited to see what you build with it!

## **Omnicast: Unified On-Chain Identity in Omnispace**&#x20;

Omnicast unifies on-chain identity in the omnispace. A first of its kind soulbound, omnichain NFT, Omnicast unlocks a fascinating frontier that has yet to be explored.

At launch, users can carry their favorite profile picture across the omnispace with themselves by syncing the `tokenURI` across chains. They can leave messages on each other's Omnicasts to be read by their friends.

This is but the tip of the iceberg — we're excited to see how builders use Omnicast and Omnichannel to unlock new abilities in omnispace.

### A new primitive for smart contract developers

Builders can use Omnicast for reading and writing data across chains. It's like a two-way omnispace radio — you can use it to send and receive messages on specific channels. What you use this for is up to you, dear builder!&#x20;

You can upgrade your existing contracts to write messages on another chain with `sendMessage(toChainId, toOmnicastId, toOmnichannelId, payload)`, and read received messages with `readMessageFor(omnicastId, onOmnichannelId)`.

IDs are `uint256(uint160(anAddress))` — every address has its own omnicast ID and its own omnichannel ID.

### **Omnichannel — Your Branded Omnispace Channel**

An **Omnichannel** NFT can be minted to reserve access to a branded channel ID. These are ENS-style domains, like `prosperity.eden.dao` or `fwb.eden.dao`. The holder of an Omnichannel NFT has exclusive write access to that omnichannel.

These will initially be sold on the Ethereum network, and the owner is free to bridge these to any of the LayerZero chains to write data to the channel from another chain.



## A Note of Gratitude

When minting an Omnicast or an Omnichannel, you will additionally receive EDN as a note of our gratitude. We have lots in store for this token in the future, but for now, take it as a memento of our hope for a regenerative renaissance on Planet Eden.

_We have to make it absolutely clear that by making a contribution to the Eden Dao through its payable contract methods ON CONTRACTS X, Y, and Z, you, the Contributor, donate Ethereum tokens (ETH) in order to receive EDN tokens solely for the Contributor’s own benefit and account, for the purposes of personal consumption and utilization of EDN tokens on the many chains and not for any speculative purpose or with an expectation of profit, and not with a view to, or for resale in connection with, a public offering or other distribution of EDN tokens, whether in exchange for other any other digital asset, any currency, any security or otherwise, and all of the foregoing remains true, accurate and complete on and as of the date of the contribution._

__

{% embed url="https://github.com/edendao/protocol" %}
Dive into the GitHub to learn more!
{% endembed %}
