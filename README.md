# Awesome-Marketing-Attribution

# Top Marketing Attribution Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Multi-Touch Attribution, Mobile Measurement & Unified Marketing Measurement*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Marketing Attribution Tools**. These tools connect ad impressions and clicks to downstream conversions, distribute credit across marketing channels, and provide budget optimization insights — using rule-based models, Markov chains, Shapley values, and causal inference.

**Examples** include Salesforce Bizible, Rockerbox, Dreamdata, AppsFlyer, Adjust, Singular, Attribution App, FullCircle Insights, HockeyStack, and Windsor.ai (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom attribution logic, and transparent mobile measurement — ideal for growth engineers, data teams, and developers building data-sovereign marketing analytics.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce Bizible](https://www.salesforce.com/)**  
  B2B marketing attribution platform within Salesforce that connects ad spend to revenue with multi-touch attribution models.

- **[Rockerbox](https://www.rockerbox.com/)**  
  Marketing attribution and measurement platform unifying cross-channel data with custom attribution models.

- **[Dreamdata](https://dreamdata.io/)**  
  B2B revenue attribution platform connecting marketing touchpoints to pipeline and revenue.

- **[AppsFlyer](https://www.appsflyer.com/)**  
  Mobile attribution and marketing analytics platform with deep linking, fraud protection, and audience segmentation.

- **[Adjust](https://www.adjust.com/)**  
  Mobile measurement partner with attribution, fraud prevention, and audience builder for app marketers.

- **[Singular](https://www.singular.net/)**  
  Marketing analytics platform with unified attribution across mobile, web, and CTV channels.

- **[Attribution App](https://attributionapp.com/)**  
  Multi-touch attribution and marketing analytics for e-commerce and SaaS businesses.

- **[FullCircle Insights](https://www.fullcircleinsights.com/)**  
  B2B marketing attribution and funnel analytics natively built on Salesforce.

- **[HockeyStack](https://hockeystack.com/)**  
  Revenue attribution platform correlating marketing touches with closed revenue for B2B teams.

- **[Windsor.ai](https://windsor.ai/)**  
  Marketing data connector and attribution platform unifying 100+ data sources for custom reporting.

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
