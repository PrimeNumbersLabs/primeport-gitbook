# Staking Mechanics

Stake $PRFI tokens inside your PRFI ONFT to level it up, increase your multiplier, and earn a larger share of the monthly reward pool.

***

## How Staking Works

1. Connect your wallet to the staking platform at [primestaking.xyz](https://primestaking.xyz)
2. Select your PRFI ONFT
3. Enter the amount of $PRFI you want to stake
4. Confirm the transaction

The staked $PRFI is held inside the NFT's smart contract. Your level is computed automatically based on how much $PRFI is staked.

***

## Levels

There are **20 levels**. Each level requires a cumulative total of staked $PRFI and adds **+0.1** to your multiplier.

| Level | Added Multiplier | Total $PRFI Required |
| ----- | ---------------- | -------------------- |
| 0     | 0.0              | 0                    |
| 1     | 0.1              | 3                    |
| 2     | 0.2              | 7.5                  |
| 3     | 0.3              | 15                   |
| 4     | 0.4              | 25.5                 |
| 5     | 0.5              | 37.5                 |
| 6     | 0.6              | 70                   |
| 7     | 0.7              | 94                   |
| 8     | 0.8              | 120                  |
| 9     | 0.9              | 152                  |
| 10    | 1.0              | 192                  |
| 11    | 1.1              | 300                  |
| 12    | 1.2              | 360                  |
| 13    | 1.3              | 430                  |
| 14    | 1.4              | 500                  |
| 15    | 1.5              | 575                  |
| 16    | 1.6              | 792                  |
| 17    | 1.7              | 900                  |
| 18    | 1.8              | 1,020                |
| 19    | 1.9              | 1,200                |
| 20    | 2.0              | 1,500                |

> The "Total $PRFI Required" column shows the cumulative amount needed to reach that level. You can check your current level and the PRFI needed to reach the next level on the NFT detail page on PrimePort.

***

## Key Contract Functions

The staking logic lives in the verified smart contract on Base. Key functions include:

| Function                  | Description                                              |
| ------------------------- | -------------------------------------------------------- |
| `getNFTData(tokenId)`     | Returns the staked amount, multiplier, and lock status   |
| `getTokenLevel(tokenId)`  | Returns the current level (computed from staked amount)   |
| `getAmountToLevelUp(tokenId)` | Returns how much more $PRFI is needed for the next level |
| `checkLevel(staked)`      | Given a staked amount, returns the corresponding level    |

> **Note:** The level is not stored on-chain — it is computed dynamically from the staked balance. This means your level updates instantly when you stake more $PRFI.

***

## Locking

You can optionally **lock** your PRFI ONFT for a period of time. Locking may provide additional benefits in the future (e.g., boosted rewards from PrimeFi). The lock status is visible on the NFT detail page.

***

## Viewing Your Staking Data

On PrimePort, navigate to any PRFI ONFT detail page and click the **Staking** tab. You will see:

- **Total PRFI** — The total amount of $PRFI staked inside the NFT
- **Level** — The current level (0–20)
- **Added Multiplier** — The multiplier bonus from leveling
- **PRFI to Level Up** — How much more $PRFI is needed to reach the next level
- **Total Multiplier** — Base multiplier + added multiplier
- **Locked** — Whether the NFT is currently locked

***

## See Also

- [**Rarity & Multipliers**](rarity-and-multipliers.md) — How rarity affects your base multiplier
- [**Rewards**](rewards.md) — Monthly reward distribution details
- [**Staking Docs (Prime Staking)**](https://docs.primestaking.xyz/products/prfi-staking-nfts/prfi-nfts-staking-mechanics) — Detailed staking mechanics
