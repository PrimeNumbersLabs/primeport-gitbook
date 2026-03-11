---
description: PrimePort operates on two EVM-compatible networks. Features vary by chain.
---

# Supported Networks

| Feature           | Base | XDC |
| ----------------- | ---- | --- |
| PRFI ONFTs        | ✅    | ❌   |
| NFT Staking       | ✅    | ✅   |
| Trading           | ✅    | ✅   |
| Drops & Minting   | 🔜   | ✅   |
| Auctions & Offers | 🔜   | ✅   |
| LayerZero Bridge  | ✅    | 🔜  |

***

### Base (Chain ID: 8453)

[Base](https://base.org) is an Ethereum Layer 2 built by Coinbase. Full EVM compatibility, low gas fees, and access to the Ethereum liquidity ecosystem.

**Active on Base:**

* PRFI ONFTs, yield-bearing NFT collection from Prime Numbers Labs
* NFT staking via the PRFI Staker contract
* Trading on PrimePort and OpenSea

| Setting        | Value                                      |
| -------------- | ------------------------------------------ |
| Chain ID       | 8453                                       |
| Native token   | ETH                                        |
| RPC URL        | `https://mainnet.base.org`                 |
| Block Explorer | [basescan.org](https://basescan.org)       |
| Bridge         | [bridge.base.org](https://bridge.base.org) |

***

### XDC Network (Chain ID: 50)

The [XDC Network](https://xdc.org) is an enterprise-grade, EVM-compatible blockchain with near-zero gas fees and sub-second block times.

**Active on XDC:**

* XDC Staking NFTs, stake psXDC inside your NFT to earn XDC rewards
* Third-party NFT collections
* Full marketplace features: minting, drops, auctions, offers

| Setting        | Value                              |
| -------------- | ---------------------------------- |
| Chain ID       | 50                                 |
| Native token   | XDC                                |
| RPC URL        | `https://erpc.xinfin.network`      |
| Block Explorer | [xdcscan.com](https://xdcscan.com) |

> **Address format:** XDC uses the `xdc` prefix instead of `0x`. Always replace `0x` with `xdc` when withdrawing from an exchange.

***

### Switching Networks

PrimePort detects your wallet's active network automatically. To switch, change the network directly in your wallet, the interface updates immediately.
