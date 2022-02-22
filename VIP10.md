---
```
vip: VIP10
title: "Approve Loan For Liquidity Provision"
status: WIP
author: nickbtts [multisig signer]
sponsors/seconders: Core
discussions-to: [here]

created: Mon 21st Feb 2022
```
---

#### Simple Summary

Approve an OTC loan to treasury of $3m with below terms, to be paired with ecosystem fund WeVE and added to Solidly liquidity.

#### Motivation & Rationale

Voting for our own gauge (WeVE><USDC) through Solidex means this pair will attract a significant percentage of Solidly emissions, particularly in the first week. In order to maximise DAO revenue, it is proposed to use the Ecosystem fund WeVE to farm this gauge. As the treasury currrently holds only WeVE, and WeVE is not suitable collateral on decentralised money markets, an OTC loan of USDC provides us the opportunity to earn from our own gauge.  

#### Specification

##### Loan Terms

* OTC Loan of $3m, pre-agreed and provided by a few community & team members.
* Initial loan term of one month with option to extend [delegated to team].
* Repayment can be requested with one week's notice.
* Team can repay at any time.
* 15% of treasury's WeVE - USDC emissions paid to loan provider, daily.
* Loan is repaid for the full USDC amount (veDAO keep any USD upside, and will repay any downside using WeVE from ecosystem fund, up to a maximum of 20% of ecosystem).

##### Strategy

As strategy is already delegated to Core, liquidity can be removed at any point via multisig.
