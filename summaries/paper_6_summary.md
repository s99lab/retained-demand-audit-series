# Paper 6 Summary

## Title

**After User Abstraction: Backend Retained Demand and Just-in-Time Liquidity in Institutionally Connected Digital Assets**

## Core Proposition

**Use without inventory is weak retained demand.**

This paper extends the retained-demand framework into the post-user-abstraction environment.

As digital asset infrastructure becomes more usable, end users may no longer directly hold, see, or manage the assets that support backend settlement, liquidity, routing, collateral, or treasury functions.

The paper therefore asks where retained demand appears after the asset disappears from the user interface.

## Role in the Series

Paper 6 is the backend retained-demand paper of the series.

It extends Paper 1’s retained-demand framework by shifting the question from end-user usage to operator-layer balance sheets.

Instead of asking whether users hold the asset, it asks whether infrastructure operators must retain, pre-position, collateralize, or buffer the asset in order to deliver the service.

## Key Concepts

### User Abstraction

User abstraction means that the end user may no longer directly interact with the asset.

A user may receive a smooth payment, custody, treasury, trading, or settlement experience without knowing which asset, ledger, or liquidity mechanism is used in the background.

This makes end-user holding a weaker signal of asset demand.

### Backend Retained Demand

Backend retained demand refers to retained demand that appears on the balance sheets or operating books of infrastructure actors.

Possible holders include:

- wallets
- exchanges
- custodians
- payment providers
- market makers
- liquidity providers
- clearing operators
- treasury operators
- prime brokers
- settlement infrastructure providers

The key question is whether these operators need to hold or reserve the asset in advance.

### Backend Capability vs. Retained Demand

The paper distinguishes backend capability from retained demand.

An operator may be technically able to support, route, display, custody, or transact with an asset without needing to retain it as inventory, collateral, or liquidity buffer.

Capability alone is not demand.

### Customer Utility vs. Asset Necessity

The paper also distinguishes customer utility from asset necessity.

A service may create real value for customers through faster settlement, better treasury visibility, automation, cost reduction, or improved routing.

However, customer value does not prove that any specific asset is necessary unless removing that asset worsens cost, liquidity, reliability, reach, collateral efficiency, or customer outcomes.

### Just-in-Time Liquidity

Just-in-time liquidity is a major falsification condition.

If an operator can acquire the asset only when needed, use it briefly, and release it without maintaining meaningful inventory, then retained demand is weak.

Pre-positioned inventory matters only when just-in-time procurement is more costly, risky, unreliable, or operationally difficult than holding the asset in advance.

## What This Paper Does

This paper provides a framework for auditing retained demand after user abstraction.

It helps identify whether asset demand has moved from the user layer to the infrastructure layer, or whether usage has become too transient to create meaningful retained demand.

It also introduces a stricter interpretation of backend demand by requiring evidence of pre-positioned inventory, collateral demand, liquidity-buffer demand, or removal-sensitive operator dependence.

## What This Paper Does Not Claim

This paper does not claim that backend retained demand already exists for any specific asset.

It does not claim that user abstraction is automatically bullish or bearish.

It does not claim that technical support, customer utility, or infrastructure integration alone proves asset necessity.

It also does not reject the possibility of backend retained demand.

Instead, it asks for evidence that backend operators must retain the asset rather than merely touch it temporarily.

## How to Read It

Read Paper 6 as the series’ post-abstraction extension.

Its central question is:

**After the asset disappears from the user interface, does it reappear as retained inventory, collateral, liquidity buffer, or operational necessity on the backend?**

If the answer is no, then usage may exist without strong retained demand.

## Falsification / Audit Relevance

A backend retained-demand thesis weakens if:

- users benefit from the service but the asset is not retained by operators
- operators can rely on just-in-time procurement
- the asset is only touched temporarily
- internal netting or outsourced liquidity removes inventory need
- customer utility remains strong even if the asset is removed
- technical support does not create balance-sheet demand
- the asset is replaceable by stablecoins, fiat rails, tokenized deposits, internal ledgers, or other liquidity sources

A backend retained-demand thesis strengthens if:

- operators pre-position the asset
- market makers hold inventory for the workflow
- custodians or prime brokers support institutional retained exposure
- the asset is used as collateral or liquidity buffer
- just-in-time procurement is unreliable or inefficient
- removal of the asset worsens operator cost, failure risk, liquidity access, or settlement performance

## Relationship to Other Papers

Paper 1 defines retained demand.

Paper 2 distinguishes expansion from closure.

Paper 3 translates retained demand into required liquidity density.

Paper 4 applies the framework through compression, bypass, and amplification.

Paper 5 turns the framework into an evidence-gated operational protocol.

Paper 6 extends the framework to the backend operator layer after user abstraction.

## Link to Full PDF

[Read the full PDF](../papers/Paper_6_After_User_Abstraction_v5_0.pdf)
