# Professional work & additional studies

[← Project directory](../PROJECTS.md) · [Profile](../README.md)

These summaries connect my business and quantitative background to data-system delivery, applied AI, and product work. They describe my contribution and delivery scope; employer code and datasets are not published here.

## xHealth wearable-monitoring platform

**Summer AI Engineering Intern · June to August 2026**

I independently owned a wearable-monitoring backend from problem framing to GCP deployment, working with a mentor and downstream teammates. The work covered OAuth enrollment, device-data ingestion, canonical models, Python/SQL processing, and structured outputs for a care-team workflow.

- Made SQLite and PostgreSQL workflows consistent, verifying row-level parity and preserving an evaluation fingerprint across the migration.
- Delivered scheduled processing on GCP, versioned JSON contracts, encrypted token handling, and least-privilege access.
- Added checks inside built containers to catch deployment-specific failures beyond ordinary source tests.
- Used automated tests and real-device data to investigate irregular readings, missing data, and operational reminders.

This was an engineering deployment and research prototype. It was not a clinically validated patient-alerting product.

**Public code example:** [Health Pipeline Prototype](https://github.com/JeffGe911/Health-Pipeline-Prototype) is a separate, synthetic-data exercise illustrating validation, aggregation, and alerting concepts; it is not the source of the later internship deployment.

## xHealth AI-CRM analytics & decision layer

**Team platform · My scope: analytics and decision workflows**

I owned scheduling, measurement, enrollment attribution, recommendation, and feedback components within a team healthcare-outreach platform.

- Connected reporting and decision outputs through organization-scoped APIs and shared data contracts.
- Built geographic reporting and small-cell privacy controls.
- Delivered merged contributions across scheduling, attribution, recommendations, and reporting.

The platform was built by a team; I did not own every generation or publishing component. Seeded demo reach and enrollment counts are not customer-acquisition outcomes.

## Personalized alert evaluation

**Research work within the xHealth project**

I researched interpretable personalized deviation scoring, cross-signal corroboration, and conformal approaches. Evaluation included patient-level splits, baseline comparisons, ablation, and bootstrap confidence intervals.

I focused on interpretable methods and explicit evaluation boundaries. Retrospective public-data evaluation and synthetic experiments do not establish clinical effectiveness.

## UNIM operational data tools

**Data Science Intern · June to August 2025**

The work began with Finance, Operations, and Sales definitions: part-number mappings, customer/distributor relationships, quantity reconciliation, and forecast-versus-actual reporting.

- **Test archives → ERP-ready outputs:** built Python parsing and bilingual Excel preparation preserving lot, wafer, and BIN detail; reduced manual preparation by approximately 90%, with operating guides and staff training.
- **Sales reporting:** built Python/Dash customer and distributor views, filters, and weekly/monthly quantity and revenue summaries.
- **Capacity planning:** built a 52-week tool spanning fabrication, wafer testing, and final testing/packaging.

The ERP-related delivery prepared validated import files; it did not directly post transactions into an ERP.

## IDXExchange home-price modeling

**Data Scientist (Internship) · January to April 2026**

I worked on California home-price prediction with a small team, covering property-data preparation, geospatial and statistical features, model comparison, and forward holdout evaluation.

My [spatial AVM pipeline](https://github.com/samvishnevskiy/IDX_Exchange_DS47/blob/main/idx-spatial-avm_JeffGe.py) included forward monthly holdouts and training-only ZIP-level price features. My [authored contribution](https://github.com/samvishnevskiy/IDX_Exchange_DS47/commit/7566136f4ac5ebcbd69d33507d37c1456248a1a9) covered data processing, spatial features, and model evaluation within the [team repository](https://github.com/samvishnevskiy/IDX_Exchange_DS47).

The team's [saved January 2026 holdout results](https://github.com/samvishnevskiy/IDX_Exchange_DS47/blob/main/outputs/tables/model_results_2026-01.csv) report **XGBoost price R² of 0.8843**, with July to December 2025 training data. That result uses the project's price-trimming procedure on the test set. The later team notebook extends the model comparison; I do not claim sole implementation of those additions. These are saved modeling results, not evidence of a deployed valuation service or measured business uplift.

## Los Angeles H3 collision analysis

**Spatial-data coursework · Coauthored project**

The work examined Los Angeles collision records through coordinate validation, spatial processing, H3-based units, and a time-based forecasting/evaluation design.

This entry preserves the spatial-analysis project as coursework and analysis design. It does not claim a deployed forecasting service, verified forecast accuracy, or public-safety impact.
