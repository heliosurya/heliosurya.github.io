# Apex Pragmatika

> Fractional CMO (Build · Operate · Transfer) & Owner P&L Workbench — powered by Surya Narayanan.

**Live site:** https://heliosurya.github.io/

This repository publishes the public website for [Apex Pragmatika](https://heliosurya.github.io), the fractional CMO practice built for business owners and second-generation entrepreneurs who measure success in multi-decade cash flow and EBITDA.

## What's inside

- **Hero** — topline-vs-bottom-line framing with the Build · Operate · Transfer architecture
- **The Thesis** — the incentive mismatch between 24-month executives/agencies and multi-decade owners
- **Build · Operate · Transfer** — the operating architecture (3-phase growth engine)
- **Engagement Architectures** — fixed-horizon diagnostic sprint, fractional CMO mandate, startup equity+milestone-gated retainer, and boardroom offsites
- **P&L Workbench (Interactive)** — 5 live tools:
  1. CAC Payback, 24-month Honest LTV & 3-Lever Sensitivity Simulator
  2. True nCAC vs. Blended ROAS & Contribution Margin (CM2) Calculator
  3. Pincode Pareto & Bharat Bimodal Simulator (Xpert + Redseer benchmarks)
  4. FCMO Growth Scorecard (WoW · MoM · QoQ · YoY) with CSV export
  5. Weekly 1-Page CMO Governance Dashboard with kill-rules
- **Case Studies & Ecosystem** — public milestones, client logos, and confidential owner patterns
- **About** — founder pedigree, operating principles, and a 90-day multi-generational change protocol
- **Owner Briefing (FAQ)** — AEO/GEO-optimised Q&A for answer engines and GEP
- **Final CTA block** — 30-minute complimentary owner diagnostic

## Hosting

- **Repo:** `heliosurya/heliosurya.github.io` (GitHub Pages user-site repo)
- **Pages source:** `main` branch, root directory
- **Subdomain:** `heliosurya.github.io`
- **Custom domain:** None (user subdomain in use)

## Notes for Surya

- The interactive workbench is pure client-side JS (no build step, no backend). All calculations run 100% locally in the browser; nothing is persisted to a server.
- Currency switching is built in (INR / USD) via the top-right toggle in the Tools section.
- Sample P&L scenarios are available via the "Load Sample P&L Scenario" bar (01 · Baseline B2B, 02 · 2nd-Gen Mfg/SME, 03 · B2B SaaS Scaleup, 04 · Consumer D2C).
- Opt-in analytics (Google Tag Manager GTM-553T8B5G → GA4 + Microsoft Clarity) and a DPDP Act 2023 consent banner are included. All P&L inputs carry `data-clarity-mask="true"`.
- The site includes an accessibility overlay: mobile slide-over drawer, focus trapping, skip link, and a live a11y announcer.
- A privacy modal covers DPDP Act 2023 compliance, zero-server-storage of calculator inputs, and personal data processing details.
