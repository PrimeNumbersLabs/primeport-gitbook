# Smart Contracts

All PrimePort and Prime Numbers smart contracts are deployed on-chain and verified on their respective block explorers.

***

## Base (Chain ID: 8453)

### PRFI ONFTs — Staker Contract

The single contract that handles PRFI ONFT ownership, staking, leveling, and merging on Base.

|              |                                                                                                     |
| ------------ | --------------------------------------------------------------------------------------------------- |
| **Contract** | `0x693A3A45Ff596024f844Be1cc6845d59F778dCF5`                                                        |
| **Standard** | ERC-721 (ONFT via LayerZero)                                                                        |
| **Explorer** | [View on BaseScan](https://basescan.org/address/0x693a3a45ff596024f844be1cc6845d59f778dcf5)         |
| **Source**   | [GitHub](https://github.com/PrimeNumbersLabs/prfi-nft-contracts/blob/develop/contracts/Staker.sol) |

***

## XDC Network (Chain ID: 50) — Legacy

> The XDC staking NFT contracts below are legacy and no longer actively used. The ecosystem has migrated to PRFI ONFTs on Base. These contracts remain on-chain for existing holders.

### PRNT Staking NFTs v3

|              |                                                                                                     |
| ------------ | --------------------------------------------------------------------------------------------------- |
| **Contract** | `0x134279d46ce98cCa734d9a43cc3DdA63A1AC755D`                                                        |
| **Explorer** | [View on XDCScan](https://xdcscan.com/address/xdc134279d46ce98cCa734d9a43cc3DdA63A1AC755D) |

### PRNT Staking NFTs v2

Legacy PRNT staking contract (v2).

|              |                                                                                                     |
| ------------ | --------------------------------------------------------------------------------------------------- |
| **Contract** | `0xf87f7dd4e47dd5bcac902c381ea0d2730db5c6ad`                                                        |
| **Explorer** | [View on XDCScan](https://xdcscan.com/address/xdcf87f7dd4e47dd5bcac902c381ea0d2730db5c6ad) |

### PRNT Staking NFTs v1

Legacy PRNT staking contract (v1).

|              |                                                                                                     |
| ------------ | --------------------------------------------------------------------------------------------------- |
| **Contract** | `0x38c6ca76dC02d353E5a33D4dB916187eFe5A1473`                                                        |
| **Explorer** | [View on XDCScan](https://xdcscan.com/address/xdc38c6ca76dC02d353E5a33D4dB916187eFe5A1473) |

### XDC Staking NFTs v2

|              |                                                                                                     |
| ------------ | --------------------------------------------------------------------------------------------------- |
| **Contract** | `0x9D458330e458f11fd1cE7E44B3a66568af8076a0`                                                        |
| **Explorer** | [View on XDCScan](https://xdcscan.com/address/xdc9D458330e458f11fd1cE7E44B3a66568af8076a0) |

### XDC Staking NFTs v1

|              |                                                                                                     |
| ------------ | --------------------------------------------------------------------------------------------------- |
| **Contract** | `0x2204E4Db4D45A290e284daa6f6fb52273593B293`                                                        |
| **Explorer** | [View on XDCScan](https://xdcscan.com/address/xdc2204E4Db4D45A290e284daa6f6fb52273593B293) |

### Vault Diamond

|              |                                                                                                     |
| ------------ | --------------------------------------------------------------------------------------------------- |
| **Contract** | `0xEb7bCbdCb6152e8f6b368F3843381c1F75bf247D`                                                        |
| **Explorer** | [View on XDCScan](https://xdcscan.com/address/xdcEb7bCbdCb6152e8f6b368F3843381c1F75bf247D) |

***

## Marketplace Contracts

PrimePort uses on-chain marketplace contracts for listings, offers, and auctions on the XDC Network. These are managed internally and interact with the NFT contracts above for approvals and transfers.

***

## Security

All contracts are deployed from verified source code. The PRFI ONFT Staker contract source is publicly available on [GitHub](https://github.com/PrimeNumbersLabs/prfi-nft-contracts). If you have security concerns, please contact the team via [Telegram](https://t.me/PrimeNumbersFi).
