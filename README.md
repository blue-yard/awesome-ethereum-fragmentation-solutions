# Awesome Ethereum Fragmentation Solutions

A Collection of Article, Talks, and Solutions to Ethereum's Layer 2 Fragmentation Issues.

# Education

## Sites

- [Chain Abstraction Hub](https://ca.dev/)
  - Covers the entire chain abstraction space and all companies/products. Also features explainers of terms and protocols.  

## Talks / Interviews

- [The fundamental problem of state propagation](https://www.youtube.com/watch?v=iWdlTBWXN2k)
  - Logan Jastremski with Espresso Systems CEO Ben Fisch 
- [Are Intents, SUAVE, Account Abstraction, & Cross-Chain Bridging all the same thing?](https://www.youtube.com/watch?v=G0nFyq9DDPw)
  - Uma Roy at Succint
- [The CAKE Framework](https://www.youtube.com/watch?v=2amKtIyF2TE) - Ankit Chiplunkar & Stephane Gosselin

## Articles

- [The Cake Framework](https://frontier.tech/the-cake-framework)
  - Frontier Tech Research. Discussing all the components required and tradeoffs in solving fragmentation
- [How Ethereum can solve L2 liquidity fragmentation](https://paragraph.xyz/@blueyard/how-ethereum-can-solve-l2-liquidity-fragmentation)
  - Tim Robinson from BlueYard.
- [Magic Spend](https://mirror.xyz/bungeexchange.eth/D3HVezTJkaKRyH7lGavJUTGfLBJF0lLq06yWh88DHWM)
  - Bungee/Socket, describing a new wallet type that can spend funds anywhere. 
- [Fusion Module](https://ethresear.ch/t/fusion-module-7702-alternative-with-no-protocol-changes/20949)
  - A module that allows an EOA account to function as a smart contract account with batched sending, chain abstraction etc. 

# Products

## Liquidity Aggregation

- [Agglayer](https://polygon.technology/agglayer)
  - A bridge/chain that aggregates liquidity and ZK proofs from connected chains.
- [Superchain](https://www.superchain.eco/)
  - A bridge/chain that aggregates liquidity and has a shared inbox for connected chains
- [ZKLink](https://zklink.io/)
  - A Layer3 that connects to all Layer 2/3's to aggregate liquidity between them. 

## Chain Abstraction

- [Arcana](https://arcana.network/)
 - A Layer 1 powering chain abstraction. Also has a wallet coming soon.
 
## Intent Protocols

- [Socket](https://www.socket.tech/)
  - A protocol to make a series of actions occur across any chains.

## Tools / SDK's

- [ZKLink Magic Links](https://github.com/zkLinkProtocol/zklink-intent-url/blob/main/docs/develop.md)
  - Tool to turn a cross-chain intent into a simple link. 
- [Orby by Orb Labs](https://docs-orby.orblabs.xyz/)
  - SDK to make your app/wallet chain abstracted
- [Near Chain Signatures](https://docs.near.org/concepts/abstraction/chain-signatures)
  - NEAR Accounts that allow one set of keys to manage assets across most chains, even non-smart contract ones.

## Universal Accounts / Wallets

Wallets that allow spending your tokens on any chain seamlessly

- [Ambire Wallet](https://www.ambire.com/)
- [Avocado Wallet](https://avocado.instadapp.io/login)
- [Brahma](https://brahma.fi/)
- [Magic Newton](https://www.magicnewton.com/)
- [One Balance](https://www.onebalance.io/)
- [Particle Network](https://particle.network/)
- [Polaris](https://polaris.app/)
- [ZeroDev Magic Accounts](https://docs.zerodev.app/magic-account)



# Standards

- [ERC-7683](https://www.erc7683.org/)
  - A standard for cross-chain intents
- [EIP-7702](https://eip7702.io/)
  - Allows EOA accounts to act like a smart contract account giving them batch signing, paymasters, and unlocking full chain abstraction when combined with other services. 