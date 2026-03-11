---
description: >-
  All PrimePort and Prime Numbers contracts are deployed on-chain and verified
  on their respective block explorers.
---

# Smart Contracts

### Base (Chain ID: 8453)

#### PRFI ONFTs. Staker Contract

Handles PRFI ONFT ownership, staking, leveling, and merging on Base. This is the primary contract for all PRFI ONFT interactions.

|              |                                                                                                                 |
| ------------ | --------------------------------------------------------------------------------------------------------------- |
| **Address**  | `0x693A3A45Ff596024f844Be1cc6845d59F778dCF5`                                                                    |
| **Standard** | ERC-721 (ONFT via LayerZero)                                                                                    |
| **Explorer** | [BaseScan](https://basescan.org/address/0x693a3a45ff596024f844be1cc6845d59f778dcf5)                             |
| **Source**   | [GitHub — Staker.sol](https://github.com/PrimeNumbersLabs/prfi-nft-contracts/blob/develop/contracts/Staker.sol) |

***

### XDC Network (Chain ID: 50)

#### PRFI Staking NFTs v2 _(active)_

Current active staking NFT contract on XDC Network.

|              |                                                                                    |
| ------------ | ---------------------------------------------------------------------------------- |
| **Address**  | `0x9D458330e458f11fd1cE7E44B3a66568af8076a0`                                       |
| **Explorer** | [XDCScan](https://xdcscan.com/address/xdc9D458330e458f11fd1cE7E44B3a66568af8076a0) |

#### PRFI Staking NFTs v1

|              |                                                                                    |
| ------------ | ---------------------------------------------------------------------------------- |
| **Address**  | `0x2204E4Db4D45A290e284daa6f6fb52273593B293`                                       |
| **Explorer** | [XDCScan](https://xdcscan.com/address/xdc2204E4Db4D45A290e284daa6f6fb52273593B293) |

#### Vault Diamond

On-chain vault contract used for staking mechanics on XDC Network.

|              |                                                                                    |
| ------------ | ---------------------------------------------------------------------------------- |
| **Address**  | `0xEb7bCbdCb6152e8f6b368F3843381c1F75bf247D`                                       |
| **Explorer** | [XDCScan](https://xdcscan.com/address/xdcEb7bCbdCb6152e8f6b368F3843381c1F75bf247D) |

***

### XDC Network — Legacy PRNT Contracts

> PRNT Staking NFTs are legacy contracts and no longer actively used. They remain on-chain for existing holders.

| Contract             | Address                                      | Explorer                                                                           |
| -------------------- | -------------------------------------------- | ---------------------------------------------------------------------------------- |
| PRNT Staking NFTs v3 | `0x134279d46ce98cCa734d9a43cc3DdA63A1AC755D` | [XDCScan](https://xdcscan.com/address/xdc134279d46ce98cCa734d9a43cc3DdA63A1AC755D) |
| PRNT Staking NFTs v2 | `0xf87f7dd4e47dd5bcac902c381ea0d2730db5c6ad` | [XDCScan](https://xdcscan.com/address/xdcf87f7dd4e47dd5bcac902c381ea0d2730db5c6ad) |
| PRNT Staking NFTs v1 | `0x38c6ca76dC02d353E5a33D4dB916187eFe5A1473` | [XDCScan](https://xdcscan.com/address/xdc38c6ca76dC02d353E5a33D4dB916187eFe5A1473) |

***

### Marketplace Contracts

PrimePort's on-chain marketplace contracts handle listings, offers, auctions, and transfers on XDC Network. These contracts interact with the NFT contracts above for ownership approvals and settlement. Addresses are managed internally.

***

### Security

All active contracts are deployed from verified source code. The PRFI ONFT Staker contract is publicly available on [GitHub](https://github.com/PrimeNumbersLabs/prfi-nft-contracts).

To report a security concern, contact the team via [Telegram](https://t.me/PrimeNumbersFi).
