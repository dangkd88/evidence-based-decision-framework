# Evidence-Based Decision Framework

A practical framework for making high-confidence decisions under uncertainty.

This project started as a way to improve AI-assisted purchase decisions, but the underlying principles apply to many kinds of decisions where information is incomplete and trade-offs exist.

The framework focuses on:

- Solving the real problem instead of comparing products
- Separating objective evidence from subjective preference
- Reducing uncertainty before optimizing price
- Evaluating value instead of cost
- Treating brand as evidence rather than status
- Weighting decisions based on real-world impact
- Knowing when enough evidence exists to stop researching

The goal is not to find the perfect decision.

The goal is to make the highest-confidence decision supported by available evidence while minimizing future regret.

---

## Why?

Many recommendation systems optimize for:

- cheapest
- most popular
- most premium
- feature-rich

This framework optimizes for something different:

> Maximum expected value under uncertainty.

---

## Core Principles

- Start from the problem, not the product.
- Evidence always overrides assumptions.
- Reduce uncertainty before optimizing price.
- Optimize total value, not purchase price.
- Weight criteria according to the consequence of being wrong.
- Treat brands as evidence, not status.
- Stop researching once decision sufficiency has been reached.

---

## Typical Workflow

```text
Problem
    ↓
Must-have criteria
    ↓
Reduce uncertainty
    ↓
Research market
    ↓
Find market sweet spot
    ↓
Evaluate brands
    ↓
Apply impact weighting
    ↓
Find benchmark
    ↓
Compare value
    ↓
Estimate regret
    ↓
Decision
```

---

## Current Status

This framework reflects my personal decision-making process.

It has helped me make decisions with greater confidence and significantly reduced second-guessing after making a purchase.

While the framework itself has been refined through many real-world decisions, it has **not yet been systematically tested as an AI skill or agent workflow**.

This repository is an experiment to see how well these principles translate into AI-assisted decision making.

---

## Possible Applications

Although it was originally developed around purchasing decisions, the framework can also be applied to:

- Technology selection
- Vendor evaluation
- Tool selection
- Equipment purchasing
- Business decisions
- Personal decision making

Any situation involving uncertainty, incomplete information, and trade-offs.

---

## Philosophy

> Do not seek the perfect option.
>
> Seek the option with the highest expected value supported by available evidence.

Evidence always wins.
