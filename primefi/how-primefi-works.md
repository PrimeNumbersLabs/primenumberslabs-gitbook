# How PrimeFi Works

PrimeFi follows the standard lending and borrowing model used by protocols\
like Aave, but extends it across multiple chains simultaneously.

#### Lend

Deposit supported assets into PrimeFi liquidity pools. Lenders earn variable\
APY paid by borrowers. 90% of borrowing fees go to lenders; 10% goes to\
the protocol treasury and PRFI NFT holders.

#### Borrow

Deposit collateral on any supported chain and borrow against it, on the\
same chain or a different one. Loan-to-value ratios (LTV) vary by asset and\
are governed by $PRFI holders.

#### Liquidations

If a position falls below the liquidation threshold, it can be liquidated by\
any user. A 15% liquidation fee is split equally between the liquidator and\
the protocol.

#### Cross-Chain Architecture

PrimeFi uses LayerZero's messaging layer to communicate collateral positions\
and loan states across chains. Users interact with a single interface, the\
protocol handles the cross-chain complexity in the background.

Supported assets, LTV ratios, and chain-specific parameters are maintained\
in the full documentation.

→ docs.primefi.xyz
