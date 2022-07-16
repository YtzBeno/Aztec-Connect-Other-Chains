# Introduction

Aztec is more than ‘just’ a layer 2 solution for Ethereum. It’s chain agnostics, which means that it is possible to bring Aztec connect (privacy / anonymity) to other chains, both rollups and alt L1´s.

This repository consists of multiple chains which all include the specific code(contracts) and data from that specific chain. This data could be anything from tech (e.g. gas fees) to business (demand from this specific chain for Aztec connect).

Feel free to contribute.

# Suitable chains

- Optimism ✔️
- Arbitrum ✔️
- zkSync ✖️
- Cairo ✖️ (Will be possible soon!)
- Avalanche ✔️
- Solana ✖️
- Binance Smart Chain ✔️
- Polkadot ✖️
- Solana ✔️
- Polygon ✔️
- Fantom ✔️

(The main factor which determines if a chain is suitable or not is that you have the verifier work within the setup. It basically should allow you to perform curve operations as these are used when verifying proofs. In EVM chains this is done by something called a ´precompiler´. Therefor if a chain doesn´t have something similar to this(precompilers), then it isn´t suitable.)
