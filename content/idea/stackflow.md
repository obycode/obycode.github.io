---
title: "Stackflow Intro"
date: 2025-02-08T09:32:34-05:00
---

# Stackflow

Stacks needs a p2p payment channel system, to enable off-chain, instant
transfers that are still secured on-chain. Stackflow enables this, using SIP-018
structured data signatures to allow users to verify the state of a channel
on-chain when necessary. After opening a channel, to make a transfer, a user
would just send a signature to the recipient, along with the balances it is
confirming. If the balances look good, then the recipient can reply with a
signature, so that both parties have a pair of signatures to verify the channel
state. These signatures are only needed if something goes wrong and either party
needs to prove the true state of the channel. The contract can support STX
transfers as well as approved SIP-010 tokens.

I put together
[some slides](https://docs.google.com/presentation/d/1nWzpz06K8NzB7CEUGDd-fTfCrRZqyQqIG2TOY01RmEU/edit?usp=sharing)
to help explain this a bit more.

Check the repo for more details: https://github.com/obycode/stackflow. I've got
a version of the contract that I'm happy with, and the beginnings of a
[server implementation](https://github.com/obycode/stackflow-server), but that
part still needs work.
