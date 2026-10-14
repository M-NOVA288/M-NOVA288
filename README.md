## Hi, I'm Monisa 👋

I build software that keeps working when the things it depends on don't. My focus is **reliability
engineering**: designing for failure, measuring what users actually experience, and turning incidents into
fixes that stick.

I come to engineering from data analytics and business operations, so I care about the numbers behind
a system: what "reliable" means in SLOs, where the error budget went, and which fix buys the most.

### What I've built

| Project | Reliability work |
|---|---|
| [**Deal Liaison**](https://github.com/M-NOVA288/Deal-liaison-w-Vercel-Supabase) · [live](https://deal-engine-rose.vercel.app) | Production service taking real payments. SLOs and error budget, health checks, structured logs with request IDs, OpenTelemetry, idempotent Stripe webhooks, failure-mode tests, Docker, CI, and blameless postmortems from real incidents. |
| [**VoxBook**](https://github.com/M-NOVA288/Vox-book-engine) | Job pipeline for an unreliable upstream API: retries with jittered backoff, timeouts, circuit breaker, dead-letter queue, plus a fault-injection lab to break it on purpose. |
| [**SLO & Log Analyzer**](https://github.com/M-NOVA288/Elemapi-EDA-and-Regression/tree/main/02-slo-log-analyzer) | Python tool that reads service logs and reports SLO compliance, error-budget burn, when burn-rate alerts would have paged, and anomalies. |
| [**ML projects**](https://github.com/M-NOVA288/Elemapi-EDA-and-Regression) | CNN and MNIST classifiers in TensorFlow/Keras with augmentation, regularization and early stopping. |

### How I work

- **Design for failure first.** Every dependency gets a timeout, a retry policy that only retries what can succeed, and a plan for when it's down.
- **Measure what users feel.** SLIs and SLOs before dashboards; alerts on symptoms, not causes.
- **Learn from incidents, blamelessly.** Timeline, root cause, action items with owners and status.
- **Automate the toil.** If I check it by hand twice, it goes into CI.
- **Be honest about limits.** Every project README lists what isn't done yet.

### Tech stack

**Languages:** TypeScript · JavaScript (Node.js) · Python · SQL<br>
**Backend & data:** Next.js · REST APIs · PostgreSQL (Supabase, row-level security) · SQLite · Stripe<br>
**Reliability & ops:** Docker · GitHub Actions CI · OpenTelemetry · structured logging · health checks · k6 load testing · SLOs/error budgets<br>
**Cloud & hosting:** Vercel (serverless) · Supabase<br>
**Frontend:** React · Vite · Tailwind CSS<br>
**Data & ML:** pandas · scikit-learn · TensorFlow/Keras · PyTorch basics · Jupyter

**Currently learning:** Kubernetes · Google Cloud Run · Prometheus and Grafana

### Open to

Entry-level **Site Reliability**, **Platform** and **Backend** engineering roles.
