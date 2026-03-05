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

| Level | Added Multiplier | Total PRFI Staked | PRFI Needed to Level Up |
| ----- | ---------------- | ----------------- | ----------------------- |
| 0     | 0.0              | 0                 | 15                      |
| 1     | 0.1              | 15                | 22.5                    |
| 2     | 0.2              | 37.5              | 37.5                    |
| 3     | 0.3              | 75                | 75                      |
| 4     | 0.4              | 150               | 127.5                   |
| 5     | 0.5              | 277.5             | 187.5                   |
| 6     | 0.6              | 465               | 350                     |
| 7     | 0.7              | 815               | 470                     |
| 8     | 0.8              | 1,285             | 600                     |
| 9     | 0.9              | 1,885             | 760                     |
| 10    | 1.0              | 2,645             | 960                     |
| 11    | 1.1              | 3,605             | 1,500                   |
| 12    | 1.2              | 5,105             | 1,800                   |
| 13    | 1.3              | 6,905             | 2,150                   |
| 14    | 1.4              | 9,055             | 2,500                   |
| 15    | 1.5              | 11,555            | 2,875                   |
| 16    | 1.6              | 14,430            | 3,960                   |
| 17    | 1.7              | 18,390            | 4,500                   |
| 18    | 1.8              | 22,890            | 5,100                   |
| 19    | 1.9              | 27,990            | 6,000                   |
| 20    | 2.0              | 33,990            | 7,500                   |

> **PRFI needed to max out an NFT = 41,490.** You can check your current level and the PRFI needed to reach the next level on the NFT detail page on PrimePort.

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

You can optionally **lock** your PRFI ONFT on PrimeFi for a specified period. Locking is required to be eligible for the **40% PrimeFi profit sharing** rewards. The lock status is visible on the NFT detail page.

***

## Interface Actions

| Action | Description |
| ------ | ----------- |
| **Stake** | Deposit PRFI into the NFT to earn rewards and level up |
| **Get Surplus** | Withdraw PRFI above 41,490 for free once the NFT reaches max level |
| **Burn to Redeem** | Destroy the NFT to withdraw all staked PRFI |
| **Withdraw PRFI** | Remove PRFI with a 20% fee (redistributed to other holders) |
| **Claim PRFI** | Claim monthly rewards |
| **Transfer** | Move the NFT to another wallet |
| **Sell** | List or auction the NFT on [OpenSea](https://opensea.io/collection/primenumbers-prfi-onft) (Base) |
| **Merge** | Combine two same-rarity NFTs into a higher-rarity NFT |

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
