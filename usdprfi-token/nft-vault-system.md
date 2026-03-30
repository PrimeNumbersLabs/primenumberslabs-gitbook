# NFT Vault System

The NFT vault system is the core mechanism that connects $PRFI holders to ecosystem revenue. It works differently from standard staking, and that difference matters.

#### <mark style="color:purple;">How It Works</mark>

1. You lock $PRFI inside a PRFI NFT. The NFT becomes a vault. Any $PRFI staked inside it begins accumulating rewards from all three ecosystem protocols.
2.  The vault collects revenue from three sources.

    * A share of PrimeFi borrowing fees (soon)
    * A share of PrimeStaking rewards
    * A share of PrimePort marketplace fees (1.5% secondary sales)

    No NFT = no rewards. The staking contract distributes only to wallets holding a PRFI NFT with staked $PRFI inside.
3. Your position is fully transferable. Because the stake lives inside the NFT, not in a separate staking contract tied to your wallet, you can transfer, sell, or trade your staked position on PrimePort at any time. The rewards accumulation moves with the NFT.

***

#### <mark style="color:purple;">The Tier System</mark>

Staking more $PRFI inside your NFT raises its tier. Higher tiers unlock a larger share of the ecosystem revenue pool.

| Tier | $PRFI Staked  | Revenue Share   |
| ---- | ------------- | --------------- |
| 1    | Base amount   | Standard share  |
| 2    | Higher amount | Increased share |
| 3    | Higher amount | Greater share   |
| 4    | Higher amount | Premium share   |
| 5    | Maximum       | Maximum share   |

\[Note for implementation: fill in exact tier thresholds from PrimeStaking docs]

Burning additional $PRFI also contributes to tier progression, creating deflationary pressure on the total supply over time.

***

#### <mark style="color:purple;">Why This Design?</mark>

Most DeFi tokens offer staking rewards paid in the same token, creating sell pressure as stakers claim and sell. The PRFI NFT vault system distributes rewards from real protocol revenue (borrowing fees, marketplace fees, staking yields) rather than from token emissions. This means rewards are backed by actual economic activity, not by inflating the supply.
