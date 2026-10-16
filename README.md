## Hi, I'm Monisa 👋

I'm a **Java developer focused on energy and commodity trading systems (ETRM/CTRM)**. I build the code that sits around a trading platform: trade validation rules, valuation and risk, settlements, interfaces, and the production support that keeps them running through end of day.

I come to engineering from data analytics and business operations, so I think in terms of the business workflow first — how a trade moves from capture to confirmation, scheduling, settlement and the general ledger — and then build the technical solution around it.

### Featured: Endur ETRM Toolkit

[**endur-etrm-toolkit**](https://github.com/M-NOVA288/endur-etrm-toolkit) — a Java 17 toolkit modeled on **OpenLink Endur** workflows for gas, power, swaps and futures:

- **Trading:** deal capture and lifecycle (book, validate, amend with versioning, cancel, mature) with a full audit trail
- **Ops-service rules:** pre-booking checks for mandatory fields, duplicate trades, counterparty status, trader authorization, price tolerance and credit limits
- **Valuation & risk:** realized and unrealized MtM, P&L explain, positions, historical VaR, credit exposure
- **Gas scheduling:** supply-to-market pathing, NAESB nomination cycles, pipeline cuts and re-nominations, imbalance cash-out
- **Back office & interfaces:** settlements and netted invoices, trade feed import, XML confirmations, balanced GL extract, broker reconciliation
- **Production support:** EOD batch, failure isolation, safe re-runs and a support runbook; 48 automated tests and CI

### Other projects

| Project | What it shows |
|---|---|
| [**Deal Liaison**](https://github.com/M-NOVA288/Deal-liaison-w-Vercel-Supabase) · [live](https://deal-engine-rose.vercel.app) | Production service taking real payments: idempotent payment webhooks, SLOs, structured logging, failure-mode tests, CI, and postmortems from real incidents. |
| [**VoxBook**](https://github.com/M-NOVA288/Vox-book-engine) | Job pipeline for an unreliable upstream API: retries with backoff, timeouts, circuit breaker, dead-letter queue — the same patterns trading-system interfaces need. |
| [**SLO & Log Analyzer**](https://github.com/M-NOVA288/Elemapi-EDA-and-Regression/tree/main/02-slo-log-analyzer) | Python tool that reads service logs and reports SLO compliance, error-budget burn and anomalies — root-cause analysis from data. |
| [**ML projects**](https://github.com/M-NOVA288/Elemapi-EDA-and-Regression) | CNN and MNIST classifiers in TensorFlow/Keras. |

### How I work

- **Business requirements first.** Understand the trading, risk or operations workflow, then translate it into a technical design.
- **Fail safe.** In a trading system a defect should stop a bad trade, never let it through.
- **Own production support.** Clear audit trails, root-cause analysis, and fixes that stick.
- **Test what matters.** Business rules and calculations are covered by automated tests and checked in CI.
- **Be honest about limits.** Every project README states what isn't covered.

### Tech stack

**Languages:** Java · SQL · Python · TypeScript/JavaScript<br>
**ETRM domain:** deal lifecycle · ops-service trade rules · MtM valuation · VaR · credit · gas scheduling & nominations · settlements · confirmations · GL<br>
**Java & tooling:** Java 17 · Maven · JUnit 5 · GitHub Actions CI<br>
**Data & backend:** PostgreSQL · REST APIs · Docker · structured logging · OpenTelemetry<br>
**Data & ML:** pandas · scikit-learn · TensorFlow/Keras

**Currently learning:** OpenLink Endur (OpenComponents / JVS plugin development) · power scheduling (ERCOT)

### Open to

**ETRM / Endur developer**, **Java developer in energy and commodity trading**, and **trading-systems production support** roles — Houston, TX.
