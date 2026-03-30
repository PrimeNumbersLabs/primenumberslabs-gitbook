# How PrimeFi Works

PrimeFi follows the standard lending and borrowing model used by protocols like Aave, but extends it across **multiple chains simultaneously**.

***

#### <mark style="color:purple;">Lend</mark>

Users can deposit supported assets into PrimeFi liquidity pools.

* Earn variable APY paid by borrowers
* 90% of borrowing fees go to lenders
* 10% goes to:
  * Protocol treasury
  * PRFI NFT holders

***

#### <mark style="color:purple;">Borrow</mark>

Users can borrow against deposited collateral.

* Deposit collateral on any supported chain
* Borrow on the same chain or a different one
* Loan-to-value (LTV) ratios vary by asset
* Parameters are governed by $PRFI holders

***

#### <mark style="color:purple;">Liquidations</mark>

If a position falls below the required threshold, it becomes eligible for liquidation.

* Any user can trigger a liquidation
* 15% liquidation fee applied
* Fee distribution:
  * 50% → Liquidator
  * 50% → Protocol

***

#### <mark style="color:purple;">Cross-Chain Architecture</mark>

PrimeFi uses LayerZero to synchronize positions across chains.

* Collateral and loan states are communicated cross-chain
* Users interact with a single unified interface
* Cross-chain complexity is handled at the protocol level

***

#### <mark style="color:purple;">Additional Parameters</mark>

Supported assets, LTV ratios, and chain-specific configurations are maintained in the full documentation.

[→ https://docs.primefi.xyz](https://docs.primefi.xyz/)
