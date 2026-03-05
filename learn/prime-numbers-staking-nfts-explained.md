# Staking NFTs Explained

Prime Numbers Labs pioneered the concept of **staking NFTs** — NFTs that act as vaults for cryptocurrency tokens. By staking tokens inside your NFT, you earn a share of a monthly reward pool, and your NFT becomes a yield-generating asset.

***

## PRFI ONFTs (Base)

The latest generation of staking NFTs lives on the **Base** network (Ethereum L2). These are called **PRFI ONFTs** (Omnichain NFTs via LayerZero).

|                         |                                                                 |
| ----------------------- | --------------------------------------------------------------- |
| **Token staked**        | $PRFI                                                           |
| **Monthly reward pool** | 100,000 PRFI distributed across all staked NFTs                 |
| **Additional rewards**  | Marketplace royalties + 40% of PrimeFi profits                  |
| **Max level**           | 20                                                              |
| **Network**             | Base (Chain ID 8453)                                            |
| **Marketplace**         | [PrimePort](https://primeport.xyz) · [OpenSea](https://opensea.io/collection/primenumbers-prfi-onft) |

Each PRFI ONFT has a base multiplier determined by its rarity. By staking $PRFI, you increase your level and added multiplier, which increases your share of the reward pool.

**Key differences from the XDC staking NFTs:**
- The **level is computed on-chain** from the staked balance (not stored as a separate value)
- There is no "Stake in Level" field — only total staked and PRFI needed to reach the next level
- The **merge system** allows you to combine two same-rarity NFTs into a higher-tier NFT
- PRFI ONFTs are **omnichain** — they can be bridged to other chains via LayerZero

→ [Full PRFI ONFT Documentation](../prfi-onfts/README.md)

***

## Legacy: PRNT Staking NFTs (XDC)

> **Historical:** PRNT Staking NFTs on XDC are the original staking collection and are no longer actively used. The ecosystem has migrated to **PRFI ONFTs on Base**. These contracts remain on-chain for existing holders.

|                         |                                                                 |
| ----------------------- | --------------------------------------------------------------- |
| **Token staked**        | $PRNT                                                           |
| **Network**             | XDC Network (Chain ID 50)                                       |
| **Status**              | Legacy — no longer actively used                                |
| **Staking platform**    | [staking.primenumbers.xyz](https://staking.primenumbers.xyz)    |

***

## XDC Staking NFTs (XDC) — Active

Stake $XDC tokens inside your NFT. These NFTs have 20 levels and earn from a dedicated XDC reward pool.

|                         |                                                                 |
| ----------------------- | --------------------------------------------------------------- |
| **Token staked**        | $XDC                                                            |
| **Network**             | XDC Network (Chain ID 50)                                       |
| **Max level**           | 20                                                              |
| **Additional feature**  | XDC Masternode locking for 7% APY                               |
| **Staking platform**    | [staking.primenumbers.xyz](https://staking.primenumbers.xyz)    |

XDC Staking NFTs include a merge feature to combine two same-rarity NFTs into a higher-rarity one. Rewards are paid on the last day of each calendar month.

***

## How Staking Rewards Work

All staking NFTs follow the same core principle:

1. **Stake tokens** inside your NFT
2. **Level up** as your staked balance grows
3. **Earn monthly rewards** proportional to your total multiplier
4. **Claim rewards** through the staking platform at the end of each month

Your **total multiplier** = base multiplier (from rarity) + added multiplier (from levels). A higher total multiplier means a bigger share of the reward pool.

***

## Where to Stake

| Collection                  | Platform                                                          |
| --------------------------- | ----------------------------------------------------------------- |
| **PRFI ONFTs** (active)     | [primestaking.xyz](https://primestaking.xyz)                      |
| **XDC Staking NFTs** (active) | [staking.primenumbers.xyz](https://staking.primenumbers.xyz)   |
| **PRNT NFTs** (legacy)      | [staking.primenumbers.xyz](https://staking.primenumbers.xyz)      |

***

## See Also

- [**PRFI ONFTs**](../prfi-onfts/README.md) — Full documentation for PRFI ONFTs on Base
- [**Staking Mechanics**](../prfi-onfts/staking-mechanics.md) — Levels, multipliers, and requirements
- [**Smart Contracts**](../smart-contracts.md) — All verified contract addresses
