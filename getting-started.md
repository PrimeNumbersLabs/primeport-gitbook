# Getting Started

This guide walks you through connecting your wallet to PrimePort so you can start buying, selling, and staking NFTs.

***

## Step 1 — Install a Wallet

PrimePort supports any EVM-compatible wallet. We recommend:

- [**MetaMask**](https://metamask.io) — Browser extension and mobile app
- [**Rabby Wallet**](https://rabby.io) — Multi-chain browser wallet
- **WalletConnect** — Connect any compatible mobile wallet by scanning a QR code

Install your preferred wallet and create or import an account.

***

## Step 2 — Choose Your Network

PrimePort supports two networks. Choose the one that matches the NFTs you want to interact with.

### Base (Ethereum L2)

Base is where **PRFI ONFTs** live. Most modern wallets (MetaMask, Rabby) include Base by default. If you need to add it manually:

| Setting          | Value                           |
| ---------------- | ------------------------------- |
| **Network Name** | Base                            |
| **Chain ID**     | 8453                            |
| **RPC URL**      | `https://mainnet.base.org`      |
| **Currency**     | ETH                             |
| **Explorer**     | `https://basescan.org`          |

You will need a small amount of **ETH on Base** to pay gas fees. You can bridge ETH from Ethereum mainnet using the [Base Bridge](https://bridge.base.org).

### XDC Network

The XDC Network hosts active XDC Staking NFTs, third-party NFT collections, and legacy PRNT Staking NFTs. Minting, drops, and auctions are available on XDC.

| Setting          | Value                                    |
| ---------------- | ---------------------------------------- |
| **Network Name** | XDC Network                              |
| **Chain ID**     | 50                                       |
| **RPC URL**      | `https://erpc.xinfin.network`            |
| **Currency**     | XDC                                      |
| **Explorer**     | `https://xdcscan.com`              |

You will need a small amount of **XDC** for gas. XDC is available on exchanges like [Bitrue](https://www.bitrue.com) and DEXs like [XSwap](https://xswap.com).

> **Note:** XDC addresses start with `xdc` instead of `0x`. When withdrawing from an exchange, replace the `0x` prefix with `xdc`.

***

## Step 3 — Connect to PrimePort

1. Go to [**primeport.xyz**](https://primeport.xyz)
2. Click the **Connect** button in the top-right corner
3. Select your wallet (MetaMask, WalletConnect, etc.)
4. Approve the connection in your wallet
5. Sign the authentication message when prompted

Once connected, you will see your wallet status in the navbar. Click your profile icon to access your NFTs, settings, and profile page.

***

## Step 4 — Fund Your Wallet

To buy NFTs or pay gas fees, you need the native currency of your chosen network:

- **Base** → ETH (bridge from Ethereum via [Base Bridge](https://bridge.base.org) or buy on any exchange)
- **XDC** → XDC (buy on [Bitrue](https://www.bitrue.com), [XSwap](https://xswap.com), or other exchanges listed on [CoinGecko](https://www.coingecko.com))

For PRFI ONFT staking, you also need **$PRFI** tokens on Base.

***

## What's Next?

- [**Browse PRFI ONFTs**](prfi-onfts/README.md) — Learn about yield-bearing NFTs on Base
- [**How to Buy an NFT**](learn/how-to-buy-an-nft-on-primeport.md) — Step-by-step guide
- [**How to Sell an NFT**](learn/how-to-sell-an-nft-on-primeport.md) — List your NFTs for sale
- [**Smart Contracts**](smart-contracts.md) — Verified contract addresses
