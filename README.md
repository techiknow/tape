# T.A.P.E.

> **T**iered **A**mortization & **P**repayment **E**ngine

A zero-dependency, client-side mortgage acceleration simulator designed to model multi-tier recurring monthly prepayments and discrete one-time lump-sum principal curtailments.

---

## Features

- **Discrete Simulation Engine**: Month-by-month deterministic calculation ($r = \text{APR}/1200$) with terminal balance clamping.
- **Polymorphic Prepayment Scheduler**:
  - **Recurring Monthly Tiers**: Custom prepayment schedules spanning arbitrary year intervals (e.g. Year 1: +$2,000/mo, Year 2: +$3,000/mo).
  - **One-Time Lump Sums**: Discrete capital injections targeting any specific Year and Month.
- **Dual Trajectory SVG Chart**: Plots Remaining Debt Balance and Cumulative Interest Paid simultaneously on an auto-ranging unified vertical scale.
- **Milestone Inspector**: Interactive scrub and click-to-pin crosshair with two-way chart-to-table synchronization.
- **Amortization Ledger**: Annual rollup view with lazy 12-month accordion expansion and RFC-4180 CSV export.
- **Zero Dependencies**: Pure HTML, CSS, and Vanilla JavaScript with strict CSP compliance.

---

## Source & Repository

- **GitHub Repository**: [https://github.com/techiknow/tape](https://github.com/techiknow/tape)
- **License**: MIT

