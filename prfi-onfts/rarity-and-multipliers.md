# Rarity & Multipliers

Every PRFI ONFT has a **rarity tier** that determines its **base multiplier**. Higher rarity means a higher base multiplier, which means a larger share of the monthly reward pool.

***

## Rarity Tiers

Each NFT's global rarity is calculated by averaging the rarity scores of its five art elements (rounded up). The collection originally had 4,331 possible NFTs, of which only 2,333 were minted.

| Rarity Level | Base Multiplier | Rarity Name | Minted | Original Supply |
| ------------ | --------------- | ----------- | ------ | --------------- |
| 0            | 0.1             | OG NFTs     | 220    | 220             |
| 1            | 0.3             | Plentiful   | 34     | 47              |
| 2            | 0.4             | Common      | 442    | 911             |
| 3            | 0.5             | Uncommon    | 678    | 1,326           |
| 4            | 0.7             | Rare        | 394    | 767             |
| 5            | 0.9             | Epic        | 299    | 553             |
| 6            | 1.2             | Legendary   | 172    | 391             |
| 7            | 1.5             | Mythic      | 78     | 93              |
| 8            | 1.9             | Godly       | 1      | 8               |
| 9            | 2.0             | Handmade    | 15     | 15              |

> **Example:** A Legendary NFT has a base multiplier of **1.2**. At level 12, the added multiplier is 1.2, giving a total multiplier of **2.4**.

***

## Total Multiplier

Your NFT's **total multiplier** combines two components:

```
Total Multiplier = Base Multiplier + Added Multiplier
```

* **Base Multiplier**&#x20;

&#x20;Fixed by your NFT's rarity (see table above)

* **Added Multiplier**&#x20;

Increases by **+0.1** for each level you complete (max +2.0 at level 20)

**Example:** A Legendary NFT (base 1.2) at level 12 has an added multiplier of 1.2, giving a total multiplier of **2.4**.

***

## Why Multipliers Matter

The 100,000 PRFI monthly pool is split 50/50: half based on your total multiplier alone, half based on multiplier × staked amount. A higher multiplier and more staked PRFI means a larger share of both halves.

This creates a direct incentive to:

* Acquire higher-rarity NFTs for a stronger base multiplier
* Stake more $PRFI to level up and increase the added multiplier
* Merge lower-rarity NFTs to create rarer ones

***

## Merge System

You can combine **two NFTs of the same rarity** into **one NFT of the next rarity tier**. This burns the two input NFTs and mints a new one, making the collection more scarce over time.

Merging is the only way to obtain higher-rarity NFTs beyond what was originally minted.

***

## See Also

* [**Staking Mechanics**](staking-mechanics.md) — Levels, PRFI requirements, and daily limits
* [**Rewards**](rewards.md) — How the reward pool is distributed
