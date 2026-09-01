# Awesome-Product-Analytics-Platform

## Top Product Analytics Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Event Tracking, Funnels, Retention, Cohorts, User Behavior Insights, Feature Flags & Product Growth Analytics*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Product Analytics**. These tools help product, growth, and engineering teams understand how users interact with digital products — through event tracking, funnel analysis, retention cohorts, path analysis, session insights, and experimentation.

**Examples** include Amplitude, Mixpanel, Heap, PostHog, Pendo, FullStory, Glassbox, Quantum Metric, Countly, Indicative, June, Gainsight PX, Userpilot, June.so, and Firebase Analytics (the category leaders).

**Open-source emphasis**: Product analytics has strong open-source representation. **PostHog** stands out as the most complete all-in-one open-source platform (analytics + session replay + feature flags + experiments). Other strong options include OpenPanel, Countly Community, Matomo, Umami, and related privacy-first tools. This section is heavily expanded with every major active project.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Amplitude](https://amplitude.com/)**  
  Leading product analytics platform known for deep behavioral analysis, cohorting, North Star metrics, experimentation, and AI-assisted insights. Strong for growth and data teams at scale.

- **[Mixpanel](https://mixpanel.com/)**  
  Classic event-based product analytics tool excelling at funnels, retention, and self-serve exploration. Popular for its speed, transparent event-based pricing, and generous free tier.

- **[Heap](https://www.heap.io/)**  
  Autocapture-focused product analytics platform that records user interactions without heavy manual instrumentation, enabling retroactive analysis.

- **[PostHog Cloud](https://posthog.com/)**  
  Cloud version of the open-source platform offering product analytics, session replay, feature flags, experiments, surveys, and more in one place.

- **[Pendo](https://www.pendo.io/)**  
  Product experience platform combining analytics with in-app guidance, NPS, and feedback tools for product-led growth and adoption.

- **[FullStory](https://www.fullstory.com/)**  
  Digital experience analytics platform with high-fidelity session replay, frustration signals, and behavioral insights.

- **[Glassbox](https://www.glassbox.com/)**  
  Enterprise digital experience and session analytics platform often used in regulated industries.

- **[Quantum Metric](https://www.quantummetric.com/)**  
  Continuous product design and digital experience platform focused on quantifying the impact of user experience issues.

- **[Countly](https://count.ly/)**  
  Product analytics platform with strong mobile support, available in both community (open-source) and commercial editions.

- **[June / June.so](https://june.so/)**  
  Product analytics tools oriented toward B2B SaaS and company-level insights, often praised for simplicity and speed of setup.

- **[Gainsight PX, Userpilot, Indicative, Firebase Analytics](https://www.gainsight.com/)**  
  Additional platforms covering product experience, in-app guidance, event analytics, and mobile/app analytics (Firebase is tightly integrated with Google’s ecosystem).

## Open-Source GitHub Projects

- **[PostHog](https://github.com/PostHog/posthog)**  
  The leading open-source product analytics platform. Includes event analytics, funnels, retention, session replay, feature flags, A/B testing, surveys, error tracking, and a data warehouse. Fully self-hostable (MIT core) with a generous free cloud tier.

- **[OpenPanel](https://github.com/Openpanel-dev/openpanel)**  
  Privacy-first, open-source web + product analytics platform designed as a Mixpanel-style alternative. Supports funnels, retention, user tracking, and self-hosting (AGPL).

- **[Countly Community Edition](https://github.com/Countly/countly-server)**  
  Open-source product analytics and engagement platform with strong mobile and web support, dashboards, crash reporting, and push capabilities.

- **[Matomo](https://github.com/matomo-org/matomo)**  
  Mature open-source analytics platform (formerly Piwik). Primarily web analytics but extensible with plugins for goals, funnels, heatmaps, and more. Excellent for data ownership and GDPR compliance.

- **[Umami](https://github.com/umami-software/umami)**  
  Simple, fast, privacy-focused open-source analytics. Lightweight alternative that supports custom events and basic product insights alongside web metrics.

- **[Rybbit](https://github.com/rybbit-io/rybbit)**  
  Open-source, cookieless web and product analytics with session replays, funnels, journeys, and real-time dashboards.

- **[Swetrix](https://github.com/Swetrix/swetrix-api)**  
  Open-source analytics platform offering cookieless tracking, funnels, events, performance monitoring, and self-hosting options.

- **[OpenReplay](https://github.com/openreplay/openreplay)**  
  Open-source session replay and product analytics suite focused on debugging and understanding user sessions with full data control.

- **[Plausible Analytics](https://github.com/plausible/analytics)**  
  Lightweight, privacy-first open-source web analytics (more traffic-focused than deep product analytics) that is easy to self-host.

### Additional Strong Open-Source Options

- **Ingestion & CDP layers**: RudderStack, Jitsu, and similar open-source event pipelines that can feed multiple analytics destinations.
- **Privacy-first trackers**: GoatCounter, Ackee, and other minimalist self-hosted analytics tools.
- **Session replay companions**: Tools that pair with analytics platforms for qualitative insights.
- **Feature flag & experiment engines**: Open-source projects that complement pure analytics (many overlap with PostHog’s capabilities).
- **BI & warehouse query layers**: Metabase, Apache Superset, and similar tools used when product data already lives in a warehouse.
- Community SDKs and autocapture libraries for instrumenting web and mobile apps.

**Frameworks for building custom systems**:  
For most teams seeking a full product analytics replacement, start with **PostHog** (self-hosted or Cloud).  
It covers analytics, replay, flags, and experiments in one platform.  
For lighter or more privacy-centric needs, evaluate **OpenPanel**, **Countly Community**, **Umami**, or **Matomo**.  
Pair any of these with an open-source event pipeline (RudderStack/Jitsu) if you need multi-destination routing.  
Commercial platforms (Amplitude, Mixpanel, Heap, Pendo) still lead in polished UX, advanced cohorting, predictive analytics, and enterprise support for large-scale product organizations.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Product analytics tools collect detailed user behavior data. Proper consent, privacy notices, data minimization, retention policies, and compliance with regulations (GDPR, CCPA, etc.) are essential.
- Self-hosted open-source solutions give full data ownership but require infrastructure, security hardening, scaling expertise, and ongoing maintenance. Teams remain responsible for the lawful and ethical use of collected data.

---

**Made for product managers, growth teams, engineers, and data analysts who want to understand real user behavior.**  
Let's make insightful, privacy-respecting product analytics accessible through powerful open-source tools.
