# Hi, I'm Yuqi (Jeff) Ge

### AI · Data · Product Builder

I turn ambiguous requirements into systems that run. I have been working on connecting data pipelines, backend APIs, applied AI, and product experience. I've built healthcare monitoring infrastructure, automated semiconductor data workflows, and taken my own product from concept to a live beta.

**USC M.S. Spatial Data Science, expected December 2026 · Los Angeles · Open to 2027 full-time roles**

[Portfolio](https://jeffge.dev) · [LinkedIn](https://www.linkedin.com/in/jeff911) · [Email](mailto:jeff152152@gmail.com) · [DuoSky live](https://duosky.app)

## Engineering in practice

**xHealth Group — Summer AI Engineering Intern · June–August 2026**

Owned an always-on wearable-monitoring platform from problem framing to GCP deployment: self-service OAuth, ingestion of 6+ biometric streams, canonical data models, scheduled processing, and explainable care-team alerts.

- Migrated SQLite to PostgreSQL with **zero behavior drift across 398,802 synthetic evaluation readings and 166 alerts**, backed by row-level parity and a frozen evaluation fingerprint.
- Built versioned JSON contracts for a four-project ecosystem, encrypted token storage, least-privilege access, and **300+ automated tests**, including checks inside the deployed container images.
- Built the AI-CRM analytics and decision loop: scheduling → measurement → enrollment attribution → next-best actions → feedback, with organization-scoped APIs and small-cell privacy controls.
- Researched personalized anomaly detection with cross-signal corroboration and conformal scoring, using patient-level splits and bootstrap confidence intervals. This was research evaluation, not a claim of clinical validation.

**UNIM Innovation — Data Science Intern · June–August 2025**

- Built reproducible Python/SQL workflows over **50K+ wafer-test samples and 270+ weekly batches**, supporting manufacturing analysis and forecasting.
- Automated raw test-archive parsing into ERP-ready outputs, preserving lot, wafer, and BIN granularity; reduced manual processing by **~90%** and made the workflow usable by Finance and Operations.

**IDXExchange — Data Scientist (Internship) · January–April 2026**

Led a five-model comparison for California home-price prediction, using geospatial features and forward holdout validation; selected XGBoost with **R² = 0.8843**.

## Selected builds

### [DuoSky · 双辰](https://github.com/JeffGe911/DuoSky) — Founder & Product Lead · August 2026–present

A trilingual BaZi × Western astrology product combining deterministic calculation, explainable readings, global place data, and shareable geographic portraits.

- Owned scope, architecture, UX, validation, and release decisions; shipped the live product on **Cloudflare Workers**.
- Built birthplace resolution covering **170,949 places across 246 countries and territories**, with historical timezone handling and 256 lazy-loaded data shards.
- Added GIS-based city portraits and geometry fallbacks; built regression coverage across **720 chart profiles and 5,760 yearly cases**. These are test-coverage counts.

**JavaScript · Python · Cloudflare Workers · GIS · Automated QA**  
[Try DuoSky](https://duosky.app)

### [Health Pipeline Prototype](https://github.com/JeffGe911/Health-Pipeline-Prototype)

A public, synthetic-data prototype demonstrating device-data validation, deduplication, time-series aggregation, layered anomaly detection, and prioritized alerts. Includes sensor faults, duplicates, gaps, and calibration drift.

**Python · pandas · NumPy · SQLite**

### [AIvestor](https://github.com/JeffGe911/AIvestor-AuriteAI-Project)

Built User Preference and Portfolio Optimization agents in a five-person multi-agent investment-research project, connecting macroeconomic data, market analysis, and personalized portfolio workflows with structured JSON/Markdown reporting.

**Python · LangChain · LLM APIs · FRED · Agent orchestration**

I also build spatial ML workflows: **H3-based Los Angeles crash-hotspot forecasting**, time-based model evaluation, and ArcGIS prediction maps.

## Tools I work with

| Area | Toolkit |
| --- | --- |
| Data & backend | Python, SQL, PostgreSQL, pandas, SQLAlchemy, FastAPI |
| Cloud & delivery | GCP, Cloud Run, Cloud SQL, Cloud Scheduler, Docker, GitHub Actions |
| AI & ML | XGBoost, scikit-learn, LangChain, OpenAI / Anthropic APIs |
| Product & spatial | JavaScript, React, GeoPandas, H3, ArcGIS Pro |

I use Codex, Claude Code, and Cursor to accelerate implementation, with explicit acceptance criteria, independent review, regression checks, and human release decisions.

---

**Let's build something useful.** I'm looking for roles in **Forward-Deployed Engineering, Applied Data Science, and AI Product** starting in 2027.

Outside engineering, I make R&B, hip-hop, and soul as **JEdoubleF911**. [Explore both sides →](https://jeffge.dev)
