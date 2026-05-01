# Hope & Harmony Farms — USDA Grant & Subsidy Prospecting ADE

Five-phase interactive prototype of an Autonomous Digital Employee deployed for Hope & Harmony Farms — a fourth-generation Virginia peanut grower and processor in Wakefield, VA. Aquila (codename for the deployed ADE) continuously monitors 47 federal, state, and private funding sources, pre-screens eligibility, drafts applications, and manages post-award reporting. Submission authority remains with the owner.

**Live demo:** https://vmgcompanies.github.io/hope-harmony-farms-prototype/

## Phases

- **Phase 1** — Operations Console foundation: master Autonomous Mode toggle, live opportunity stream over 22 real programs (USDA VAPG, REAP, EQIP, NRCS CSP, AFID, Tobacco Region Grant, etc.), drill-down with eligibility match / draft / activity / award history tabs
- **Phase 2** — Application Editor workspace, filter & search controls, owner approval dialog, document upload modal, overnight summary banner
- **Phase 3** — Top-nav view switcher introducing Financial Impact (capital flow chart, before/after ADE, per-program ROI, cost-of-capital comparison) and Compliance Center (registrations, certifications, match obligations, audit trail)
- **Phase 4** — Award Lifecycle Manager: awarded programs table with drawdown progress, planned-vs-actual drawdown chart, performance metrics tracking, 12-month reporting calendar
- **Phase 5** — Settings & Integrations drawer: 11 connected integrations (Grants.gov OAuth, SAM.gov, USDA eAuth, VDACS, NRCS, QuickBooks, John Deere Operations Center, Microsoft 365, DocuSign), team & RBAC, notification preferences, SOC 2 Type II security posture, itemized billing

Phase 5 is the recommended starting point — it includes all earlier features.

## Stack

Single-file React per phase. Tailwind / Recharts / inline SVG icons via CDN. No build step. No external API calls. Self-contained for sharing.

---

Hope & Harmony Farms · Wakefield, Virginia · Powered by Neuralogic Group
