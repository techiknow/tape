# T.A.P.E.

> **T**iered **A**mortization & **P**repayment **E**ngine

A zero-dependency, client-side mortgage acceleration simulator designed to model multi-tier recurring monthly prepayments and discrete one-time lump-sum principal curtailments.

---

## Features

- **Discrete Simulation Engine**: Month-by-month deterministic calculation ($r = \text{APR}/1200$) with terminal balance clamping.
- **PITI & Escrow Carry Modeling**: Integrated Annual Property Taxes and Homeowners Insurance parameters with dynamic %-of-loan telemetry and monthly PITI outflow breakdowns.
- **Polymorphic Prepayment Scheduler**:
  - **Recurring Tiers (Years & Weeks)**: Custom intervals defined by loan years or discrete week spans with live calendar decomposition telemetry (e.g., `433 weeks → 8 years, 4 months, 1 week`) and frequency toggles (`$/wk` or `$/mo`).
  - **One-Time Lump Sums**: Discrete capital injections targeting any specific Year and Month.
- **Dual Trajectory SVG Chart**: Plots Remaining Debt Balance and Cumulative Interest Paid simultaneously on an auto-ranging unified vertical scale.
- **Milestone Inspector**: Interactive scrub and click-to-pin crosshair with two-way chart-to-table synchronization.
- **Expanded Amortization Ledger**: 880px height view with annual rollup, lazy 12-month accordion expansion, 9-column PITI/Escrow ledger, and RFC-4180 CSV export.
- **Zero Dependencies**: Pure HTML, CSS, and Vanilla JavaScript with strict CSP compliance.

---

## Source & Repository

- **GitHub Repository**: [https://github.com/techiknow/tape](https://github.com/techiknow/tape)
- **License**: MIT

