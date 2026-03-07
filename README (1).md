# ESG Supply Chain Due Diligence Dashboard

> An interactive portfolio project built to demonstrate supply chain ESG due diligence competencies — aligned with the OECD 6-step framework, EU CSDDD requirements, and Supplier Lifecycle Management best practices.

🔗 **Live Demo:** [esg-supply-chain-dashboard.vercel.app](https://esg-supply-chain-dashboard.vercel.app)

---

## Overview

This dashboard simulates the tools and processes a Supply Chain Due Diligence Specialist would use daily — from supplier risk assessment and corrective action tracking to regulatory compliance monitoring and audit readiness.

It was built as a portfolio project targeting roles in responsible sourcing, ESG compliance, and sustainable procurement.

---

## Features

### 📊 Dashboard
- KPI overview: total suppliers, high-risk flags, active CAPs, CSDDD readiness score, average ESG score
- Interactive OECD 6-step framework — click each step to view description, action items, and live KPIs
- Supplier Risk Register with filtering (All / High Risk / Medium / CAP Active) and sortable columns
- ESG pillar breakdown (E / S / G) per supplier with animated SVG rings
- Active Corrective Action Plans tracker
- CSDDD compliance readiness meter with line-item checklist
- ESG score trend chart (6 months, Chart.js)
- Risk distribution by region
- Regulatory tracker: CSDDD, CSRD, LkSG, Forced Labour Regulation, EUDR

### 🏢 Supplier Detail
- Per-supplier ESG score history (12 months, interactive chart)
- Audit & assessment timeline
- Corrective Action Plan items with progress bars
- E / S / G pillar breakdown

### ⚙️ Onboarding Simulator
- Simulates OECD Step 02 — adverse impact identification for new suppliers
- Inputs: country, sector, supply chain tier, annual spend, ESG certifications
- Auto-generates E, S, G scores and overall risk rating
- Outputs risk flags and recommended actions based on profile

### ✅ Audit Readiness (CSDDD)
- Interactive checklist across 6 compliance domains
- Click to cycle items between Done / Partial / Missing
- Live readiness score with animated SVG progress ring
- Covers: governance, risk identification, prevention, monitoring, disclosure, remediation

### 📄 Export & Reporting
- 4 report types generated dynamically:
  - Supplier Risk Register
  - CSDDD Gap Analysis
  - OECD 6-Step Status Summary
  - CAP Status Report

---

## Regulatory Alignment

| Framework | Coverage |
|---|---|
| OECD Due Diligence Guidance for RBC | 6-step framework fully mapped |
| EU Corporate Sustainability Due Diligence Directive (CSDDD) | Readiness tracker + gap analysis |
| EU Corporate Sustainability Reporting Directive (CSRD) | Disclosure checklist |
| German Supply Chain Act (LkSG) | Tracked in regulatory monitor |
| UN Guiding Principles on Business & Human Rights | Embedded in audit checklist |
| EU Forced Labour Regulation | Tracked in regulatory monitor |

---

## Tech Stack

- **Vanilla HTML / CSS / JavaScript** — no framework dependencies, single file deployment
- **Chart.js** — ESG trend and supplier score history charts
- **Google Fonts** — Syne (display) + DM Mono (body)
- **Deployed on Vercel** via GitHub integration

---

## Skills Demonstrated

- Supply chain due diligence process design (OECD 6-step)
- ESG risk scoring and supplier segmentation
- Corrective action plan lifecycle management
- CSDDD / CSRD regulatory knowledge
- Cross-functional data presentation (procurement, compliance, audit)
- KPI definition and tracking for ESG targets

---

## Project Context

Built as a portfolio project for a **Supply Chain Due Diligence Specialist** application at Vestas Wind Systems. The dashboard reflects real workflows described in the role — supplier onboarding ESG assessment, CAP follow-up, regulatory readiness, and audit preparation.

---

## License

This project is for portfolio and demonstration purposes only. Data is entirely simulated.
