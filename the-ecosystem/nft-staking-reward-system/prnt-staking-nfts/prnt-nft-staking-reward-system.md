---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# PRNT NFT Staking Reward System

## <mark style="color:purple;">PRNT NFT STAKING REWARDS:</mark> <a href="#b642" id="b642"></a>

### 1- 20,000 PRNT Fixed Rewards

1.5M from the allocation is dedicated to rewarding PRNT NFT holders.&#x20;

Each month, 20,000 PRNT is distributed as a reward to these holders.

### 2- Prime Numbers NFTs Royalties <a href="#id-6649" id="id-6649"></a>

Using the NFT Royalty Standard, NFT holders will receive 50% of all royalties on presales.

The royalties percentage is set at 10%, which means 5% of the sales price of each sold NFT is distributed over all NFT holders.

### 3- Prime Finance <a href="#id-7896" id="id-7896"></a>

Prime Numbers NFTs will receive 40% of Prime Finance profits.&#x20;

{% hint style="info" %}
To be eligible for these rewards, you need to lock your NFT for a period of time on Prime Finance.
{% endhint %}

***

## <mark style="color:purple;">Calculating NFT Rewards with PRNT Staking Rewards Pool and Extra Rewards</mark>

### <mark style="color:blue;">Variables Overview</mark>

* **X**: The total number of NFTs in consideration.
* **a**: Rarity of the NFT.
* **b**: Level of the NFT.
* **t**: PRNT tokens assigned per NFT.
* **Tx**: Total multiplier for an NFT, calculated as (Tx = a + b).
* **Extra Rewards**: Additional rewards coming from Primeport and Prime Finance fees, added to the initial 20,000 PRNT rewards pool.

A total of 20,000 PRNT tokens, plus Extra Rewards, are to be distributed, taking into account both the NFTs' total multiplier and the product of the total multiplier and PRNT tokens per NFT.

***

### <mark style="color:blue;">Reward Distribution Formula</mark>

#### Part 1: Based on Total Multiplier

To distribute the first portion of PRNT tokens plus a share of the Extra Rewards, we calculate each NFT's share based on its total multiplier (Tx).

1. **Calculate the accumulated total multiplier**:

$$
T_{total} = \sum_{i=1}^{X} Tx_i
$$

2. **Determine the reward for each NFT**, also considering a portion of the Extra Rewards:

$$
R_{1,i} = \left(\frac{Tx_i}{T_{total}} \times 10000\right) + \left(\frac{Tx_i}{T_{total}} \times \text{Extra Rewards}_{\text{portion}}\right)
$$

#### Part 2: Based on Total Multiplier and PRNT Tokens

For the second distribution of PRNT tokens plus another share of the Extra Rewards, we include the product of the total multiplier and PRNT tokens (Tx \* t).

1. **Calculate the total of the product of total multipliers and PRNT tokens (Ptotal)**:

$$
P_{total} = \sum_{i=1}^{X} (Tx_i \times t_i)
$$

2. **Determine the reward for each NFT**, incorporating a portion of the Extra Rewards:

$$
R_{2,i} = \left(\frac{Tx_i \times t_i}{P_{total}} \times 10000\right) + \left(\frac{Tx_i \times t_i}{P_{total}} \times \text{Extra Rewards}_{\text{portion}}\right)
$$

***

### <mark style="color:blue;">Conclusion</mark>

By applying these formulas, each NFT's reward is determined by its unique characteristics (rarity and level) and the assigned PRNT tokens. This dual approach ensures a balanced reward distribution that considers both the intrinsic qualities of the NFTs and the PRNT tokens allocated to them.



