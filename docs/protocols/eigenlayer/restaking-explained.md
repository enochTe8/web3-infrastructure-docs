# EigenLayer Restaking Explained

EigenLayer introduces a mechanism called **restaking**, which allows Ethereum validators to reuse their staked ETH to secure additional decentralized services beyond the Ethereum base layer.

Instead of creating a new validator network from scratch, protocols can leverage the existing economic security of Ethereum.

These external services are known as **Actively Validated Services (AVSs)**.

---

## Overview

In the Ethereum proof-of-stake system, validators lock ETH to participate in network consensus and earn rewards.

EigenLayer extends this concept by allowing validators to **opt into additional validation responsibilities** using the same staked ETH.

This effectively transforms Ethereum's validator set into a **shared security layer** for other decentralized systems.

---

## The Core Idea

Restaking allows ETH already committed to Ethereum’s consensus layer to also secure additional protocols.

Validators who opt in agree to follow the rules of the external service. If they behave maliciously, they may face **additional slashing conditions**.

This mechanism creates a marketplace where new protocols can access Ethereum’s security without bootstrapping their own validator network.

---

## Key Participants

### Restakers
ETH stakers who opt into EigenLayer and allow their staked assets to secure additional services.

### Operators
Infrastructure providers who run validator nodes and perform validation tasks for Actively Validated Services.

### Actively Validated Services (AVSs)
Protocols that rely on EigenLayer’s restaked validators to perform verification tasks such as data availability checks, oracle validation, or off-chain computation.

---

## Why Restaking Matters

Launching a secure decentralized protocol is difficult because it requires:

• a large validator set  
• strong economic incentives  
• reliable infrastructure  

EigenLayer lowers this barrier by allowing new protocols to inherit the security of Ethereum’s existing validator ecosystem.

This can significantly accelerate the development of new decentralized infrastructure.

---

## Potential Use Cases for AVSs

Restaked validators could secure a wide range of services, including:

• decentralized oracle networks  
• data availability layers  
• cross-chain bridges  
• rollup sequencing systems  
• off-chain computation verification

---

## Risks and Tradeoffs

While restaking introduces powerful new capabilities, it also introduces new risks.

Validators who opt into multiple services may face **compounded slashing risks** if any of those services fail or behave maliciously.

There are also concerns about:

• validator centralization  
• systemic risk across multiple protocols  
• complex incentive structures

Understanding these risks is an important part of designing secure Actively Validated Services.

---

## Summary

EigenLayer introduces a new primitive for Web3 infrastructure: **shared cryptoeconomic security**.

By allowing Ethereum validators to restake their ETH, new protocols can bootstrap strong security guarantees without building their own validator ecosystems.

If widely adopted, restaking could become a foundational layer for the next generation of decentralized infrastructure.
EigenLayer allows them to inherit security from Ethereum's validator network.
