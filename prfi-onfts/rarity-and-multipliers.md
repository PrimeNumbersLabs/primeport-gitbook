# Rarity & Multipliers

Every PRFI ONFT has a **rarity tier** that determines its **base multiplier**. Higher rarity means a higher base multiplier, which means a larger share of the monthly reward pool.

***

## Rarity Tiers

Each NFT's global rarity is calculated by averaging the rarity scores of its five art elements (rounded up).

| Rarity        | Base Multiplier |
| ------------- | --------------- |
| **Common**    | 1               |
| **Uncommon**  | 2               |
| **Rare**      | 3               |
| **Epic**      | 4               |
| **Legendary** | 5               |
| **Mythic**    | 6               |
| **Godly**     | 7               |
| **Unique**    | 8               |

> **Example:** An NFT with Vegetation (Mythic, 7), Figure (Epic, 5), Shape (Legendary, 6), Lines (Rare, 4), and Background (Godly, 8) has an average of (7+5+6+4+8)/5 = 6.0, which rounds to **Legendary** with a base multiplier of **5**.

***

## Total Multiplier

Your NFT's **total multiplier** combines two components:

```
Total Multiplier = Base Multiplier + Added Multiplier
```

- **Base Multiplier** — Fixed by your NFT's rarity (see table above)
- **Added Multiplier** — Increases by **+0.1** for each level you complete (max +2.0 at level 20)

**Example:** A Legendary NFT (base 5) at level 12 has an added multiplier of 1.2, giving a total multiplier of **6.2**.

***

## Why Multipliers Matter

The monthly reward distribution is proportional to your total multiplier relative to all other stakers. A higher multiplier means you receive a larger slice of the 100,000 PRFI monthly pool.

```
Your Share = (Your Total Multiplier / Sum of All Multipliers) × 100,000 PRFI
```

This creates a direct incentive to:
- Acquire higher-rarity NFTs for a stronger base multiplier
- Stake more $PRFI to level up and increase the added multiplier
- Merge lower-rarity NFTs to create rarer ones

***

## Merge System

You can combine **two NFTs of the same rarity** into **one NFT of the next rarity tier**. This burns the two input NFTs and mints a new one, making the collection more scarce over time.

Merging is the only way to obtain higher-rarity NFTs beyond what was originally minted.

***

## See Also

- [**Staking Mechanics**](staking-mechanics.md) — Levels, PRFI requirements, and daily limits
- [**Rewards**](rewards.md) — How the reward pool is distributed
