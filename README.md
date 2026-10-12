# Awesome-Marketing-Attribution

## Top Marketing Attribution Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Multi-Touch Attribution, Mobile Measurement & Unified Marketing Measurement*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Marketing Attribution Tools**. These tools connect ad impressions and clicks to downstream conversions, distribute credit across marketing channels, and provide budget optimization insights — using rule-based models, Markov chains, Shapley values, and causal inference.

**Examples** include Salesforce Bizible, Rockerbox, Dreamdata, AppsFlyer, Adjust, Singular, Attribution App, FullCircle Insights, HockeyStack, and Windsor.ai (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom attribution logic, and transparent mobile measurement — ideal for growth engineers, data teams, and developers building data-sovereign marketing analytics.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global marketing attribution software market is valued at approximately **$4.6B – $5.5B** and projected to surpass **$15B – $17.7B by the mid-2030s**, expanding at a CAGR of ~**13.5% – 14.6%**. The sector is **moderately fragmented**: mega-cap enterprise cloud ecosystems (Salesforce, Adobe, AppLovin) hold major aggregate footprint, while agile specialized attribution and mobile measurement providers (AppsFlyer, Dreamdata, HockeyStack, Rockerbox) vigorously compete and command high market share across multi-touch attribution, mobile measurement (MMPs), and product-led growth pipelines.

## SaaS/Hosted Platforms

| Platform | Company Size (Valuation / Revenue) | Pricing (Starting Tier) | Free Tier / Free Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Salesforce Bizible](https://www.salesforce.com/)** | **~$260B+ Market Cap** (Salesforce; Bizible/Marketo Measure unit within Adobe/Salesforce ecosystem; Marketo acquired Bizible then acquired by Adobe for $4.75B) | Starts at **~$20,000 – $35,000/year** (Standard tier for single CRM instance, billed annually) | **No free tier or trial**; vendor evaluation requires a guided sales consultation and custom sandbox demo | B2B marketing attribution platform within Salesforce that connects ad spend to revenue with multi-touch attribution models. |
| **[AppsFlyer](https://www.appsflyer.com/)** | **$2.7B Valuation** (~$500M ARR; Series E) | Starts at **$0.07/conversion** (Growth plan pay-as-you-go after introductory allocation) | **Forever Free Zero plan** (organic installs unlimited; up to **12,000 free non-organic conversions** in Welcome Package for first 12 months + 30-day premium add-ons trial) | Mobile attribution and marketing analytics platform with deep linking, fraud protection, and audience segmentation. |
| **[Adjust](https://www.adjust.com/)** | **$1B Valuation** (Acquired by AppLovin for $1B; part of AppLovin software segment) | Core plans custom quoted (typically starting at **~$0.04 – $0.06/conversion** or minimum annual commitments) | **Free Base Plan** capped at **1,500 monthly conversions** (up to 18,000 annual conversions) for the first year with core Datascape reporting and unlimited organic installs | Mobile measurement partner with attribution, fraud prevention, and audience builder for app marketers. |
| **[Rockerbox](https://www.rockerbox.com/)** | **$85M Valuation** (Acquired by DoubleVerify for $85M) | Starts at **$1,500/month** ($18,000/year minimum contract for entry mid-market tier) | **No free tier or self-serve trial**; guided enterprise product pilot and demo provided upon qualification | Marketing attribution and measurement platform unifying cross-channel data with custom attribution models. |
| **[Dreamdata](https://dreamdata.io/)** | **$55M+ Valuation** (~$3M – $8.9M ARR; Series B funded) | Starts at **$1,250/month** ($15,000/year billed annually for Growth/Attribution tier) | **Forever Free plan** with **5 user seats, 2 months of historical data**, unlimited IP-to-company identification, up to 3 stage models, and 1 audience sync | B2B revenue attribution platform connecting marketing touchpoints to pipeline and revenue. |
| **[HockeyStack](https://hockeystack.com/)** | **~$50M Valuation** (~$9M+ ARR; $50M total funding raised) | Starts at **$1,400/month** (billed annually for core B2B tracking plan) | **No free tier or trial**; access requires scheduling a custom data architecture evaluation demo | Revenue attribution platform correlating marketing touches with closed revenue for B2B teams. |
| **[Singular](https://www.singular.net/)** | **~$50M – $55M Valuation** (~$50M+ ARR) | Starts at **~$0.05/conversion** (Growth plan starting tiers) | **Forever Free Starter tier** capped at **15,000 attributed conversions** lifetime with unlimited organic tracking, standard integrations, and reporting | Marketing analytics platform with unified attribution across mobile, web, and CTV channels. |
| **[Windsor.ai](https://windsor.ai/)** | **~$15.4M Valuation** (~$2M – $4.8M ARR) | Starts at **$19/month** (Basic tier billed annually, or $23/month billed monthly) | **Forever Free plan** for **1 user, 1 data source, 1 account**, and 5 destination tasks (following an all-inclusive 30-day free trial with 10 data sources and 15 accounts) | Marketing data connector and attribution platform unifying 100+ data sources for custom reporting. |
| **[FullCircle Insights](https://www.fullcircleinsights.com/)** | **~$10M Valuation** (~$5M ARR; $9.5M total funding) | Starts at **$4,166/month** (~$50,000/year base contract + setup fees) | **No free tier or trial**; deployment requires custom scoping and guided 1–8 week Salesforce deployment | B2B marketing attribution and funnel analytics natively built on Salesforce. |
| **[Attribution App](https://attributionapp.com/)** | **~$2M – $4M Valuation** (~$880K ARR) | Starts at **$199/month** (Shopify plan) or **$399/month** (Pro plan for up to 10k monthly visitors) | **14-day free trial** on Pro plan (full access to ad connectors and models); no permanent free tier | Multi-touch attribution and marketing analytics for e-commerce and SaaS businesses. |

## Open-Source GitHub Projects

- **[adsat](https://pypi.org/project/adsat/)**  
  Python marketing attribution toolkit implementing Shapley value, Markov chain, and data-driven logistic regression models. Features auto-switching between exact and Monte Carlo Shapley for high channel counts, model evaluation across five dimensions, and ROI-weighted budget allocation advice. [citation:1]

- **[LinkForty Flutter SDK](https://pub.dev/packages/linkforty_flutter)**  
  Open-source alternative to AppsFlyer OneLink and Branch for Flutter apps. Provides deferred deep linking, mobile attribution via privacy-compliant fingerprinting, event tracking with offline queue, and last-click attribution. No IDFA/GAID collection by default. [citation:2]

- **[LinkForty Expo SDK](https://www.npmjs.com/package/@linkforty/mobile-sdk-expo)**  
  Expo SDK for LinkForty enabling deferred deep linking, mobile attribution, and conversion tracking in React Native/Expo apps. Self-hosted, privacy-first, with revenue tracking and programmatic link creation. [citation:6]

- **[OpenAttribution](https://github.com/OpenAttribution/open-attribution)**  
  Open-source Mobile Measurement Platform (MMP) for true ownership of mobile ad data. Features impression/click/event tracking on your own domain, ClickHouse analytics database with custom SQL attribution logic, and iOS/Android SDKs. Alpha stage. [citation:10]

- **[Prosper202](https://github.com/tracking202/prosper202)**  
  Open-source PPC conversion tracking software with attribution capabilities. PHP/MySQL stack with Docker deployment, shared hosting support, and Coolify integration. Tracks clicks, conversions, and ROI for paid campaigns. [citation:9]

- **[Attributor](https://github.com/Crynge/Attributor)**  
  Go-based multi-touch attribution and Bayesian media mix modeling engine. Implements Shapley values, Markov chains, and Bayesian MMM with adstock/saturation. Includes REST API and budget simulation. [citation:17]

- **[Causal MMM + MTA Platform](https://github.com/Crynge/causal-mmm-mta-platform)**  
  Python research platform unifying Bayesian Marketing Mix Modeling, multi-touch attribution (Markov, Shapley), and causal inference. Includes hierarchical MMM scaffolding, adstock/saturation transforms, and causal graph discovery. [citation:19]

- **[MultiTouchAttribution (GregMurray30)](https://github.com/GregMurray30/MultiTouchAttribution)**  
  Models for multi-touch attribution with simulation methodology. Implements DLAW (Data-driven Last-touch Attribution Weighting) with documented MAE comparisons against last-touch, first-touch, and 50/50 models. [citation:7]

- **[Multi-Touch Attribution (GitHub Topic)](https://github.com/topics/multi-touch-attribution)**  
  Collection of 13+ public repositories implementing MTA models including Markov chains, Shapley values, and deep learning approaches. Includes end-to-end pipelines with MTA vs MMM reconciliation frameworks. [citation:3]

- **[caddy-utm-tracker](https://pkg.go.dev/github.com/xor22h/caddy-utm-tracker)**  
  Caddy v2 middleware plugin that transparently captures UTM parameters and marketing attribution data from incoming requests. Zero code changes required — fires events to OpenPanel asynchronously. [citation:5]

### Additional Strong Open-Source Options

- **[Snowplow](https://github.com/snowplow/snowplow)** — First-party event tracking infrastructure for building custom attribution pipelines. [citation:4]
- **[Open Pixel](https://github.com/openpixel/OpenPixel)** — Open-source pixel tracking library for web attribution. [citation:4]
- **[UTM.io](https://github.com/utmio/utm.io)** — Open-source UTM parameter management at scale. [citation:4]
- **[Button Merchant Library](https://developer.usebutton.com/docs/button-merchant-library-overview)** — Open-source Android/iOS library for mobile attribution capture, deferred deep linking, and tap-through tracking. [citation:18]
- **[Mautic Media Bundle](https://packagist.org/packages/thedmsgroup/mautic-media-bundle)** — Pulls cost data from media advertising services into Mautic for ROI calculation. [citation:8]
- **[Robyn](https://github.com/facebookexperimental/Robyn)** — Meta's open-source Marketing Mix Modeling package with budget allocator. [citation:16]
- **[PyMC-Marketing](https://github.com/pymc-labs/pymc-marketing)** — Bayesian marketing analytics with MMM, CLV, and custom priors. [citation:16]

**Frameworks for building custom systems**: Combine **adsat** for Python attribution modeling, **LinkForty** for mobile attribution SDK, **OpenAttribution** for self-hosted MMP, **caddy-utm-tracker** for server-side UTM capture, and **ClickHouse + Grafana** for attribution analytics to build a complete self-hosted attribution stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Marketing attribution tools must comply with data protection regulations (GDPR, CCPA), platform policies (Apple ATT, Google Privacy Sandbox), and consent requirements.
- Self-hosted open-source solutions require proper security hardening, data governance, and attribution model validation.

---

**Made for growth engineers, marketing analysts, data teams, and developers building transparent marketing attribution platforms.**  
Let's make marketing attribution more open, privacy-conscious, and developer-friendly.
