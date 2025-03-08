---
title: "Ssats"
date: 2025-03-08T15:34:28-05:00
---

# sSats

![sSats Logo](/images/sSats.png)

Once we've got a way to instantly send tokens for free (with
[Stackflow](/ideas/stackflow)), completely new business models open up,
including micropayments. sBTC brings Bitcoin to Stacks, but just like native
BTC, sBTC is only divisible into Satoshis (1/100,000,000 BTC). With Stacks's
smart contract functionality, we can create a completely trustless way to
convert sBTC in and out of a new token, sSats, which can be further divided into
millionths of Sats. These sSats can then be sent via Stackflow.

The sSats contract is deployed
[here](https://explorer.hiro.so/txid/SP1X6WY8XG3A0ZFDJPFWG6CNK0ZT4EY6XN9PHQ4F8.ssats?chain=mainnet)
-- send sBTC to the contract and get sSats, then burn sSats and get sBTC back!
See the [sSats repo](https://github.com/obycode/ssats) for more info about how
to peg-in and out.
