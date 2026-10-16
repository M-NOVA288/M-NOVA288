## Hi, I'm Monisa 👋

I build software and financial models: Java systems for energy trading, full-stack TypeScript services, Python data and machine-learning tools, and Excel/Python models for financial planning. I come from data analytics and business operations, so I start with the business workflow and build the technical solution around it.

**B.S. Computer Information Systems, University of Houston · FMVA® certified (Corporate Finance Institute) · Houston, TX**

---

## Projects

Listed alphabetically. Each README states what the project covers and what it doesn't.

### Deal Liaison
[Code](https://github.com/M-NOVA288/Deal-liaison-w-Vercel-Supabase) · [Live](https://deal-engine-rose.vercel.app)

A production full-stack service that takes real payments, built with reliability as a first-class requirement.
- SBA loan analyzer and e-commerce funnel diagnostic on one Next.js codebase
- Idempotent, signature-verified Stripe webhooks; SLOs with an error budget; health checks
- Structured logs with request tracing, OpenTelemetry, failure-mode tests, k6 load tests, postmortems

**Stack:** TypeScript · Node.js · Next.js · PostgreSQL (Supabase) · Stripe · Docker · Vercel · GitHub Actions · OpenTelemetry

### Endur ETRM Toolkit
[Code](https://github.com/M-NOVA288/endur-etrm-toolkit)

A Java toolkit modeled on OpenLink Endur workflows for gas, power, swaps and futures.
- Deal lifecycle with versioned amendments and audit trail; pre-booking trade validation rules
- Valuation and risk: MtM, P&L explain, positions, historical VaR, credit exposure; gas scheduling and nominations
- Settlements, confirmations, GL extract, broker reconciliation, EOD batch; 48 automated tests and CI

**Stack:** Java 17 · Maven · JUnit 5 · SQL · GitHub Actions

### Inventory CLI
[Code](https://github.com/M-NOVA288/Elemapi-EDA-and-Regression/tree/main/01-inventory-system)

A command-line app for recording stock items in a local database.
- Add and list items with name, quantity, location and timestamp
- Parameterized SQL queries to prevent injection
- Database created automatically on first run

**Stack:** Python · SQLite

### Machine Learning Classifiers
[Code](https://github.com/M-NOVA288/Elemapi-EDA-and-Regression/tree/main/Cat_Dog_Classification)

Image classification networks built and compared in notebooks.
- Cat-vs-dog CNN with a custom rotation-augmentation function, compared across learning rates
- MNIST network with L2 regularization, dropout, early stopping and checkpointing
- Course examples in PyTorch and scikit-learn text features

**Stack:** Python · TensorFlow/Keras · PyTorch · scikit-learn · Jupyter/Colab

### Retirement Stress Test Model
[Code](https://github.com/M-NOVA288/retirement-stress-test-model-) · [Live planner](https://m-nova288.github.io/retirement-stress-test-model-/planner/)

A formula-driven financial planning model with an interactive web planner.
- Retirement projection with portfolio risk from a covariance matrix and a 1,000-run Monte Carlo probability of success
- Traditional IRA vs Roth vs 401(k) vs taxable comparison; business cash-flow simulation with runway and breakeven
- Practice ROI model with a 10-year client lifetime value DCF; Excel, Python and web results reconcile to the dollar

**Stack:** Excel · Python · openpyxl · NumPy · matplotlib · JavaScript · Chart.js

### SLO & Log Analyzer
[Code](https://github.com/M-NOVA288/Elemapi-EDA-and-Regression/tree/main/02-slo-log-analyzer)

A tool that reads service logs and reports reliability against targets.
- SLO compliance and error-budget reporting
- Multiwindow burn-rate alert replay and anomaly detection on log data
- Standard-library Python with 13 tests and CI

**Stack:** Python · GitHub Actions

### VoxBook
[Code](https://github.com/M-NOVA288/Vox-book-engine)

A React app that turns a manuscript into audiobook chapters through a resilient generation pipeline.
- Retries with exponential backoff and full jitter; honors rate-limit `Retry-After`
- Circuit breaker, per-call timeouts, bounded concurrency and idempotent job ids
- Dead-letter queue with manual requeue; latency and failure metrics; tests and CI

**Stack:** TypeScript · React · Vite · Tailwind CSS · GitHub Actions

---

## Tech stack

| Area | Tools |
|---|---|
| **Languages** | Java · JavaScript/TypeScript · Python · SQL (T-SQL, PL/SQL) |
| **Web and backend** | Next.js · Node.js · React · REST APIs · Stripe webhooks · Tailwind CSS · Vite |
| **Databases** | PostgreSQL · Snowflake · SQL Server · SQLite · Supabase |
| **Data and analytics** | Excel (financial modeling) · matplotlib · NumPy · openpyxl · pandas · Power BI (DAX, Power Query) · Tableau |
| **Machine learning** | PyTorch · scikit-learn · TensorFlow/Keras |
| **Testing and reliability** | Docker · GitHub Actions · JUnit 5 · k6 · Maven · OpenTelemetry · SLOs and error budgets |
| **Domain knowledge** | Energy trading (ETRM/CTRM, OpenLink Endur workflows) · financial modeling and valuation · financial planning · site reliability |

## How I work

- **Business requirements first.** Understand the workflow, then translate it into a technical design.
- **Fail safe.** A defect should stop bad data or a bad transaction, never let it through.
- **Own production support.** Clear audit trails, root-cause analysis and fixes that stick.
- **Test what matters.** Business rules and calculations are covered by automated tests and checked in CI.
- **Be honest about limits.** Every project README states what isn't covered.

## Contact

[LinkedIn](https://linkedin.com/in/monisa-nova) · Houston, TX
