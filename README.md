<p align="center">
  <img src="creeper.png" width="420" />
</p>

<h1 align="center">$Creeper</h1>

<p align="center">
A volume-triggered detonation token.
</p>

---

## Overview

$Creeper is a token mechanism built around a single event: detonation.

When market activity reaches a predefined threshold, the system executes a full distribution event where the entire token supply is redistributed proportionally to holders.

There are no staking systems, no claim functions, and no reward schedules.

Ownership alone determines participation.

---

## Motivation

Most token reward systems attempt to simulate incentives through staking contracts, emissions schedules, and complicated distribution logic.

These systems introduce friction and behavioral distortions.

$Creeper removes these abstractions entirely.

Instead of continuous emissions, the system accumulates pressure through trading activity until a single distribution event occurs.

When the threshold is reached, the system detonates.

All tokens are distributed to holders based on their ownership at the moment of execution.

---

## Core Mechanism

The Creeper system consists of three phases:

1. Activity
2. Pressure
3. Detonation

Market activity increases system pressure.

When pressure reaches the configured trigger point, the Creeper executes a detonation event.

During this event, the entire distributable supply is allocated across holders proportionally to their live balances.

---

## Volume Trigger

The detonation event is activated by trading volume.

As trading occurs, the system tracks cumulative volume.

Once the predefined threshold is reached, the Creeper triggers.

This design links the distribution event directly to market participation.

Higher activity accelerates the detonation cycle.

---

## Detonation Event

When the trigger threshold is reached, the system performs the following actions:

1. Reads current holder balances
2. Calculates proportional ownership
3. Allocates the entire distributable token supply
4. Distributes tokens directly to holder wallets

This event resets the system.

The next cycle begins immediately.

---

## Holder Participation

Participation is automatic.

If a wallet holds tokens at the moment the detonation occurs, it participates in the distribution.

There are no registrations, claims, or additional steps required.

Ownership is the only requirement.

---

## Allocation Model

Distribution is proportional to live ownership.

If a wallet holds 2 percent of circulating supply at the moment of detonation, it receives approximately 2 percent of the distributed tokens.

There are no multipliers, bonuses, or historical weighting.

Only the current state of ownership matters.

---

## Behavioral Properties

The system encourages sustained participation in the token ecosystem.

Since distributions occur only during detonation events, ownership at the moment of execution is what determines allocation.

The token itself becomes the interface.

Holding during the detonation event is the only condition.

---

## What This Is Not

$Creeper is not:

- A staking system
- A yield protocol
- A farming mechanism
- A passive income promise

It is a single-event redistribution model triggered by market activity.

---

## Full Mechanics Explanation

$Creeper converts trading activity into a detonation event.

As market volume accumulates, the system approaches a predefined trigger threshold.

When this threshold is reached, the Creeper activates.

At activation, the contract evaluates the current holder set and calculates proportional ownership relative to circulating supply.

The entire distributable token pool is then allocated across holders based on these proportions.

Tokens are sent directly to holder wallets during execution.

No claim function exists.

Once distribution is complete, the system resets and begins tracking the next detonation cycle.

---

## Disclaimer

This software is experimental.

The system mechanics are novel and may evolve.

No guarantees are provided.

Use at your own risk.
