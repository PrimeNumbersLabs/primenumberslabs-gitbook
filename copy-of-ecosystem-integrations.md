---
hidden: true
---

# Copy of Ecosystem Integrations

## Audits

> Last updated: June 10, 2025

***

### Overview

Independent audits safeguard the ecosystem’s **security**, **transparency**, and **community trust**. Every Prime Numbers component undergoes a thorough review both before and after deployment.

***

### Audit Summary

| Module / Contract        | Auditor                    | Status          | Date (completed / started) | Report / Reference                                                                               |
| ------------------------ | -------------------------- | --------------- | -------------------------- | ------------------------------------------------------------------------------------------------ |
| **PRFI Token**           | QuillAudits                | ✅ Completed     | 24 Apr 2025                | [See report](https://www.quillaudits.com/leaderboard/prime-number/prime-number-token-contract)   |
| **XDC Staking**          | QuillAudits                | ✅ Completed     | 06 Apr 2025                | [See report](https://www.quillaudits.com/leaderboard/prime-number/prime-number-staking-contract) |
| **PRFI ONFTs (ERC-721)** | _TBD_                      | 🔄 In progress  | Starts Q3 2025             | —                                                                                                |
| **PrimeFi – Pre-audit**  | Gerard Persoon / Code4rena | ✅ Completed     | Feb 2025                   | [Warden profile](https://code4rena.com/@gpersoon)                                                |
| **PrimeFi – Full audit** | PeckShield                 | ✅ Completed     | May 2025                   | Internal PDF (public release pending)                                                            |
| **PrimeFi – AI audit**   | QuillShield                | 🔄 Final review | Jun 2025                   | [https://shield.quillai.network](https://shield.quillai.network)                                 |
| **PrimeFi Repository**   | —                          | —               | —                          | [https://github.com/gpersoon/PrimeFi](https://github.com/gpersoon/PrimeFi)                       |

***

### Audit Details

#### PRFI Token — QuillAudits

:::info Outcome

* **Scope:** ERC-20 contract with _mint/lock/burn_ functions.
* **Score:** 100 % — no critical vulnerabilities found.
* **Status:** Live on mainnet since 27 Apr 2025.\
  :::

#### XDC Staking — QuillAudits

:::info Outcome

* **Scope:** deposits, reward calculations, and APR oracle.
* **Score:** 98.8 % — zero critical findings; all issues fixed.\
  :::

#### PRFI ONFTs — audit in progress

:::note In progress

* **Goal:** ERC-721 contracts that tokenize staking positions.
* **Estimated start:** August 2025.
* Report will be published after the _Fix Review_ phase.\
  :::

#### PrimeFi — pre-audit by Gerard Persoon

:::info Summary

* Early manual review to spot design-level risks.
* **Coverage:** `PrimeFiCore.sol`, `LiquidityManager.sol`, and utility libraries.
* Findings addressed before the formal audit.\
  :::

#### PrimeFi — PeckShield audit

:::info Summary

* **Status:** completed; PDF shared internally.
* **Key results:** no critical vulnerabilities; two medium gas-optimization issues resolved.\
  :::

#### PrimeFi — QuillShield (AI) audit

:::note Under review

* Automated semantic analysis for logical errors.
* Currently in _Fix Review_; a comparative report with PeckShield will follow.\
  :::

***

### Continuous-Audit Policy

1. **Re-audit** required after any change that alters > 5 % of contract logic.
2. External audits **annually** for contracts with TVL > USD 100 000.
3. Immediate publication of reports and code diffs for community verification.

***

### Next Steps

* Add **PRFI ONFTs** to the bug-bounty program.
* Publish the PeckShield PDF as soon as it’s publicly available.
* Integrate continuous scans via **QuillShield** in the CI/CD pipeline.
