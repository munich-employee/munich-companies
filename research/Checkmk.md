# Checkmk - Full Research Report

_Researched: 2026-11-03_

> **No critical disqualifier found.** The main caveats are compensation (the only published ranges top out around €90-95K), PE ownership since 2025 (PSG) with no works council or collective agreement found, and possible on-call duty for the SaaS platform team (not for product development). Details follow.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 2007 (19 years). Founded by Mathias Kettner as a Linux and monitoring consultancy in Munich; the open-source Check_MK add-on followed in 2009, the first commercial release in 2012 |
| Employees | 164 on average in 2024 (+23 from 141 in 2023), per the FY2024 filing for Checkmk GmbH. The company now claims "250+ team members" from "more than 35 countries" (careers page); Glassdoor lists 201-500 |
| Revenue (FY2024) | €28.49M (Checkmk GmbH, filed annual accounts). Deferred revenue of €18.7M on the balance sheet, consistent with annual subscription/licence billing |
| Profitability | Net income €5.16M in 2024 (18% net margin), after €2.55M income tax. Equity €5.2M, cash €19.7M. Self-description: "sustainable growth and strong profitability" - **PASS** |
| Ownership | **PE-backed (growth equity).** PSG Equity invested in February 2025 (terms undisclosed). Since then Checkmk GmbH is 100% owned by Checkmk Holding GmbH (formerly "Contern Bidco GmbH", HRB 298050), a typical PE acquisition vehicle, with a profit-transfer agreement registered 9 Jul 2025. PSG Managing Director Christian Stein is a managing director of the holding |
| Software-centric | Sells its own IT infrastructure monitoring / observability product (open core: GPLv2 Community edition plus commercial Pro, Ultimate and Cloud/SaaS editions) - **PASS** |

### Key People

- **Jan Justus:** CEO since 2018 (managing director of Checkmk GmbH since 14 Mar 2018), took over from the founder.
- **David Christoph Nießen:** Managing director since 17 Jun 2025 (previously Prokurist).
- **Mathias Kettner:** Founder; left the managing-director role on 8 Jan 2024.
- **Christian Stein, Francois-Xavier Joyeux (and others):** Managing directors of Checkmk Holding GmbH (PSG side).

### Funding History

| Date | Event | Amount | Valuation |
|---|---|---|---|
| 2007-2024 | Bootstrapped, founder-owned, self-funded from profits | n/a | n/a |
| 26 Feb 2025 | Strategic investment from PSG Equity (growth equity) via Contern Bidco GmbH (now Checkmk Holding GmbH). "To fuel research and development and accelerate international expansion" | Undisclosed | Undisclosed |

The bidco/midco structure, the 100% shareholding of the holding over the operating company and the profit-transfer agreement point to a **majority (control) investment**, not a minority stake. This is inferred from the register structure; PSG and Checkmk do not state the stake size.

### Business Model

Open-core software vendor. Checkmk Community (formerly Raw) is free and open source, while Checkmk Pro (data centre infrastructure), Checkmk Ultimate (self-hosted full-stack observability) and Checkmk Cloud (SaaS on AWS) are sold as subscriptions. More than 4,000 enterprise customers (up from about 1,000 a few years ago). Additional revenue comes from support, training and a consulting team that helps customers roll out the product. Offices: Munich HQ, Atlanta and Minneapolis (USA), plus branches/subsidiaries in Milan (registered Nov 2025), France and the UK.

### Consulting-Adjacency Assessment

Checkmk employs a small "Checkmk Consultant" team (Kununu shows 6 salary entries for "Berater:in", and the registry lists IT consulting among its NACE codes). That team implements the company's own product for customers. Engineering is organised in product teams (named "Nile, Rubicon, Main, Yukon" in a current posting) building one product in one codebase on two-week sprints. Engineers do not bill hours and do not build client deliverables. **Not consulting.**

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **Checkmk GmbH** (formerly tribe29 GmbH until Apr 2023, Mathias Kettner GmbH until Apr 2019) | Amtsgericht München HRB 165902, VAT DE253181382, registered 10 Jan 2007 | Kellerstraße 27, 81667 München | "Development, marketing and operation of software solutions for IT monitoring and observability (SaaS and self-hosted platforms); development and sale of software; trading of EDP hardware; advice and support in the construction and operation of computer systems" (current wording on handelsregister.ai; the older NorthData wording is "development, marketing and operation of electronic information, communication and trading platforms. Development and sale of software...") |
| **Checkmk Holding GmbH** (formerly Contern Bidco GmbH) | Amtsgericht München HRB 298050, founded 13 Nov 2024 | c/o Checkmk GmbH, Kellerstraße 27, 81667 München | Holding and management of participations (PE acquisition vehicle) |

The operating company is the German HQ and the product owner. Its registered purpose explicitly covers development of the monitoring software, it carries €16.9M of personnel cost in Germany, and the postings are for permanent employment contracts via its own Personio board. No sign of PEO/EOR for Munich staff. (Remote hires abroad in "7 countries" per a Kununu review may go through the local subsidiaries.)

**Verdict:** PASS

---

## Section 3: Office Location

- **Office address:** Kellerstraße 27, 81667 München, in Haidhausen-Süd (district Au-Haidhausen). Confirmed by the imprint, Nominatim (`27, Kellerstraße, Haidhausen-Süd, Haidhausen, Au-Haidhausen`), and reviewers ("Office am Rosenheimer Platz", "mitten in Haidhausen").
- **Nearest public transport:** **Rosenheimer Platz** S-Bahn station is about 220 m away (S-Bahn trunk line: S1, S2, S3, S4, S5, S6, S8), with a tram stop and bus stop of the same name at about 200 m. The **Wörthstraße** tram stop is about 225 m away. Further tram stops within 500 m are Am Gasteig (~380 m), Wiener Platz (~400 m) and Max-Weber-Platz (~480 m). Tram routes through stops within 500 m: 17, 21, 25 (night trams N17, N19). Distances come from OSM Overpass.
- **Work model:** "Remote is available for everyone. Employees based in Munich can choose hybrid or on-site" (careers page). Postings: "Full remote work or high flexibility between mobile work and an office in one of Munich's most beautiful central districts". No core hours. Workation of up to 6 weeks within the EU. Kununu reviewers report 92% home office and "100% Home Office". One Kununu review says remote hiring is possible in 7 countries. LinkedIn tags engineering roles as "Hybrid". There are 3-4 company events a year in person (summer party, end-of-year party, Checkmk Conference).

---

## Section 4: Reviews

**GPTW:** No Great Place to Work certification or Germany ranking found (web search plus greatplacetowork.de site search through the browser).

#### Glassdoor

Retrieved via Chromium/CDP (employer ID E3188169).

| Metric | Global | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | 4.8 (27 reviews in all languages; the filtered review view shows 10) | Not reliable: under 20 reviews | Not reliable: under 20 reviews | Not reliable: only 3 job titles with reviews |
| **WLB** | 4.8 | - | - | - |
| **Culture & Values** | 4.9 | - | - | - |
| **Comp & Benefits** | 4.5 | - | - | - |
| **Career Opportunities** | 4.5 | - | - | - |
| **Diversity & Inclusion** | 4.6 | - | - | - |
| **Senior Management** | 4.9 | - | - | - |
| **% Recommend** | 95% | - | - | - |
| **CEO Approval** | 100% (Jan Justus) | - | - | - |
| **Business Outlook** | 94% positive | - | - | - |

With 27 reviews in total, mostly from 2020-2024 and almost all from Munich, the country, city and job-title filters are effectively the same set or empty. Treat all Glassdoor scores as **directional**. Visible reviews skew toward working students, sales and managers. The only engineering-flavoured negative: "it is hard to work with old code" (working student, 2024).

#### Kununu

Retrieved via Chromium/CDP (slug `checkmk`; curl's grep extraction returned nothing because the page is client-rendered).

- **Overall score:** 4.3 / 5.0 (60 employee reviews since 2018; IT industry average 4.0)
- **Recommendation rate (Weiterempfehlung):** 83% (last 2 years); 90% across all employee reviews
- **Total reviews:** 90 (employee reviews: 60; the rest are applicant reviews)
- **Sub-scores:** Karriere & Gehalt 4.2, Unternehmenskultur 4.3, Arbeitsumgebung 4.5, Vielfalt 4.6, Gehalt & Benefits 4.1
- **Salary satisfaction:** 87%
- **Confirmed benefits:** Home office 92%, flexible hours 87%, employee events 78%
- **Kununu Top Company:** NO (no badge on the profile)

#### Blind / Teamblind

No company page (`teamblind.com/company/Checkmk` returns "Page not found"). Not available; expected for a ~250-person German company.

#### Review Themes (2020-2026)

**Positives:**
- Flexibility: "Die extrem flexiblen Arbeitzeiten zusammen mit 100% Home Office machen Work-Life-Balance zu einem non-issue" (IT, Dec 2025). "Great flexibility" (R&D, Jun 2025). Glassdoor WLB 4.8.
- R&D culture: "A truly tech-driven, transparent, and multicultural company... Nice 'geeky' pragmatic culture, great work-life balance, good salary" (R&D, Jun 2025). "Bester AG bei dem ich bislang arbeiten durfte" (R&D lead, Nov 2025).
- Transparent leadership communication: monthly all-hands where "der Vorstand klar und offen darlegt wie die aktuelle Marktsituation aussieht" (Dec 2025). Management described as "sehr professionell und ruhig... ohne unnötig zu micromanagen" (Apr 2026).
- Office: "wirklich starkes Office am Rosenheimer Platz" (several reviews).
- Long tenures and internal mobility mentioned. The product is respected and has a loyal community ("users... willing to travel thousands of kilometers to be part of our conferences").

**Negatives:**
- **Workload in sales/commercial teams:** "Overtime is part of our daily routine... Constant work overload is a main issue... micromanagement is increasing. Upper management... holds completely unrealistic expectations" (international sales, Mar 2026). "Gefühlt jeder Mitarbeiter war chronisch überarbeitet" (ex-sales, Oct 2025). "Workload ist viel zu hoch. Keinerlei Unterstützung vom Management" (IT, Mar 2026).
- **Retention/management complaints (one IT review, 2026):** "Management ist nicht in der Lage die fähigen Leute zu halten und ersetzt nach und nach durch Platzwarmhalter"; training budget below the cost of the company's own courses.
- **Silos and unclear ownership in tech:** "multiple teams inadvertently working on similar initiatives, or... a lack of clear ownership"; "some tech teams lean towards an elitist stance" (R&D, Jun 2025).
- **Career paths:** promised but not delivered ("Working on career plans for two years now"; "career path... nie mit einem persönlich besprochen").
- **Flat pay structure:** "keine Boni oder sonstige Sondervergütungen" (Dec 2025). Benefits for staff outside Germany are thin.
- **Legacy code:** "hard to work with old code" (Glassdoor). The Senior Python posting itself mentions reshaping "large parts of the codebase" grown over many years.
- **Tone shift since the PE investment:** the negative reviews cluster in Oct 2025 - Mar 2026, after the PSG deal. It is too few data points to call a trend, but worth probing.

Overlap with hard red flags: overtime/WLB complaints exist but are concentrated in **sales**. R&D reviews consistently report good WLB.

#### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | Localised to sales: "schlechte Kommunikation und... unfairer Umgang mit Fehlern" from the sales lead (ex-working student, until 2023); "'Außergewöhnliche' Arbeitskultur oder doch eher toxisch?!" (ex-sales, 2025). R&D and HR reviews describe calm, professional leadership |
| 24/7 Work Expectation | None reported for engineering. A 2025 support expansion into APAC was explicitly for "round-the-clock" customer support, done by adding a region rather than through rotations |
| Internal Surveillance | None reported |
| Fear-driven Management | Not reported. "Recently micromanagement is increasing" (sales, Mar 2026) |
| Communication Breakdown | Mixed: monthly all-hands praised; "Wer nicht ständig nachfragt erfährt hier gar nichts" (IT, Mar 2026); "vor vollendeten Tatsachen gestellt" (sales, 2025) |
| Unpaid Overtime | "Overtime is part of our daily routine" (sales, 2026). Not reported in engineering |
| Silent Firings | Not reported. One review alleges capable people are not retained and are replaced over time; no reports of push-outs |
| Work-Life Balance issues | Sales: yes. R&D: consistently positive (Glassdoor WLB 4.8) |

**Risk level: LOW for engineering, MODERATE for sales/commercial teams.** The pattern is (c) localized dysfunction in the commercial organisation during a PE-driven growth push, not systemic toxicity. Watch whether pressure from PSG growth targets spreads to R&D.

---

## Section 5: Compensation

#### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| levels.fyi | Any | No Checkmk profile (404) | - | - | - | 0 |
| Glassdoor (employer-stated in posting) | Teamlead Product Management | €90K | 0 | - | €90K | 1 |
| Job aggregator (jobleads, 2025) | AI Software Engineer | €70-95K | 0 | - | €70-95K | 1 |
| Job aggregators (2025) | Senior Data Engineer / C++ Windows Developer | €60-80K | 0 | - | €60-80K | 2 |
| Kununu | IT Berater:in | €77.2K | - | - | €77.2K | 2 |
| Kununu | Teamleiter:in | €79.7K | - | - | €79.7K | 4 |
| Kununu | Qualitätsmanager:in (QA) | €81.9K | - | - | €81.9K | 2 |
| Kununu | Berater:in | €66.3K | - | - | €66.3K | 6 |
| Filed accounts (FY2024) | All staff average (wages and salaries / 164) | ~€88.7K | - | - | ~€103K fully loaded | 164 |

The aggregator ranges are often estimates, not company-published bands. Glassdoor's salary tab did not render. No Senior/Staff Software Engineer data point exists.

**Munich reference (levels.fyi, Software Engineer, all levels, 642 data points, updated 3 Nov 2026):** median €85.8K total comp, 25th percentile €68.1K, 75th €104K, 90th €132K.

#### Equity / Stock

No employee equity programme is advertised. Reviewers confirm "keine Boni oder sonstige Sondervergütungen" and ask for profit sharing. The holding structure includes "Contern MEP GP GmbH", a management equity plan vehicle typical of PE deals. It most likely covers senior management only; no evidence that individual contributors participate. Private, PE-owned: any equity would only pay out at a PSG exit (typically 4-6 years after the 2025 deal).

#### Verdict

The only engineering figures (€60-95K) sit around the Munich median and below the 75th percentile (€104K). Large, profitable Munich corporations typically pay senior engineers €95-120K and staff-level engineers more. The 2024 average personnel cost (~€88.7K gross across all roles, including management) suggests a mid-market pay level. A Staff-level band has not been published.

**BELOW** (indicative; Staff band UNVERIFIED, so ask for the band early).

---

## Section 6: AI/ML & Tech Stack

#### AI Strategy

AI is an applied product feature layered on monitoring, not a research or ML-platform business:

- **"Explain with AI"** (Checkmk Cloud only, 2.5, Apr 2026): one-click plain-language root-cause explanations of alerts, usable as incident summaries.
- **Ask Checkmk AI** chatbot (chat.checkmk.com) for documentation/help.
- **Built-in MCP server** (Werk #22263, Aug 2026, experimental, read-only, off by default) so agents such as Claude Code or Codex can query monitoring data.
- **AI assistant in the product:** the current Senior Python posting asks the engineer to "help shape what our AI assistant can do for people who run complex IT environments" and lists "experience building LLM-based features, such as agents and their tool integrations" as a plus. A 2025 "AI Software Engineer" posting covered "integrating GenAI and LLM models for efficient IT monitoring". There is also a "Senior Product Manager AI" role.
- **AI in the dev workflow:** postings state that Claude Code is "already part of how we build software" and ask for hands-on AI-assisted development.

The LLM provider and any in-house ML (anomaly detection, forecasting) are not documented publicly. Expect LLM integration work (agents, tool use, MCP), not model training or MLOps.

#### Tech Stack

Sources: current postings (Personio XML feed and LinkedIn voyager API), the `Checkmk/checkmk` GitHub monorepo language breakdown, other Checkmk GitHub repos, the 2.5 release blog and conference material.

| Category | Technologies |
|---|---|
| **Primary language(s)** | **Python** (backend, APIs, monitoring plugins; ~72% of the main repo by bytes), TypeScript + Vue.js (frontend), C++ (Checkmk Micro Core, Windows agent), Rust (agent controller, Kubernetes agent, `otter`, `csm`) |
| **AI/ML** | LLM features (Explain with AI, AI assistant, agents and tool integrations), MCP server; Claude Code in development. Provider not disclosed |
| **Cloud** | AWS for Checkmk Cloud (EKS, IAM boundaries, Service Control Policies, GuardDuty, Macie); Marketplace images on AWS/Azure |
| **Infrastructure** | Kubernetes (EKS), Terraform, Docker, Linux, Ansible collection, Bazel (hermetic builds, remote caching/execution), Jenkins, Gerrit, git, GitHub Actions |
| **Data** | OpenTelemetry Collector/OTLP ingest, Prometheus scraping, a high-cardinality metrics backend (conference slides cited by search results name ClickHouse; not confirmed on the product page), RRD-based classic metrics |
| **Other** | Pytest, Pylint, Robot Framework (Robotmk synthetic monitoring), Grafana data-source plugin, Weblate (localisation), GPLv2 open core |

**Summary:** Python-centric product engineering on a large, long-lived open-core monorepo, with a Vue.js/TypeScript frontend and C++/Rust for the monitoring core and agents. Checkmk Cloud runs on AWS EKS with Terraform. AI work is applied LLM product integration (root-cause explanations, an assistant, an MCP server for agents) on top of an observability data platform (OpenTelemetry, Prometheus). It is production engineering, not research.

---

## Section 7: Language

- Postings are published in both English and German (some only with German titles, e.g. "Python Software Entwickler"). Every engineering posting asks for **"business fluent English" / "verhandlungssicheres Englisch"**, and German is "a plus" (Cloud Security Engineer, Teamlead PM) or not mentioned.
- 35+ nationalities. One R&D reviewer describes colleagues from "Germans, Italians, Spanish, French, Central Europeans, the USA, and India". English-language reviews exist on Kununu. Offices in the US, Italy and APAC support staff.
- Commercial roles (SDR DACH, Billing, Renewal) are German-first, but these are not engineering roles.

**Verdict:** PASS

---

## Section 8: Stability

#### Financial Position

Checkmk GmbH, FY2024 (filed 13 Oct 2025, read on handelsregister.ai through CDP):

| Item | FY2024 |
|---|---|
| Revenue | €28.49M |
| Other operating income | €3.04M |
| Personnel cost | €16.87M (wages €14.54M, social €2.33M) |
| Other operating expenses | €6.12M |
| Net income | €5.16M |
| Cash and bank | €19.74M |
| Receivables from affiliated companies | €5.74M |
| Deferred revenue (passive RAP) | €18.73M |
| Total assets | €29.72M |
| Employees (avg) | 164 (2023: 141) |

The company has been profitable and cash-generative without outside funding for most of its history. Prior-year revenue figures did not load (the handelsregister.ai year tabs failed to render). Growth is visible in headcount (+16% in 2024, from about 20 to 250+ over several years) and in the customer count (about 1,000 to more than 4,000). Since July 2025 a profit-transfer agreement sends profits up to Checkmk Holding GmbH, which will hold the acquisition debt, if any. This is the standard PE structure: future cash may be used to service holding-level debt rather than kept in the operating company. The size of any acquisition debt is UNKNOWN.

#### Financial Runway (PE-backed)

Profitable, so runway is not a constraint. A bottom-up check for 2026 assumes PSG-funded growth investment:

| Cost line | Annual estimate |
|---|---|
| Staff (~250 employees × ~€105K fully loaded) | ~€26M |
| Other opex (marketing, events, cloud hosting for Checkmk Cloud, offices, partners) | ~€8-9M |
| Material/third-party services | ~€1.5M |
| **Total gross burn** | **~€36M/year** |

| Revenue source | Est. annual inflow |
|---|---|
| Subscriptions/licences, support, consulting (2024: €28.5M; assume 15-25% growth/year) | ~€37-44M (2026) |
| **Total revenue offset** | **~€37-44M/year** |

| Scenario | Net burn | Cash at hand | Runway | Next round needed by |
|---|---|---|---|---|
| Optimistic (25% growth) | +€8M/year surplus | €19.7M | Unlimited | Not needed |
| Base case (15-20% growth) | +€1-4M/year surplus | €19.7M | Unlimited | Not needed |
| Stress (flat revenue at ~€30M, growth hiring continues) | -€6M/year | €19.7M | ~3 years | ~2029, or hiring cuts first |

Cash figure: €19.74M at 31 Dec 2024 (Checkmk GmbH annual accounts, observed 3 Nov 2026 on handelsregister.ai). The realistic risk is not insolvency but cost discipline if PSG growth targets are missed. In a PE context that usually means a hiring freeze or a targeted reduction, not a cash crisis.

#### Layoffs

No layoffs found (TrueUp has no Checkmk profile; web search for 2025-2026 layoffs found nothing; no reviewer mentions redundancies). One 2026 Kununu review alleges capable people leave and are replaced, which is attrition, not layoffs.

#### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | UNKNOWN, likely NO | No mention in the 90 Kununu reviews (searched "Betriebsrat", "Tarif", "Kündigung"), job postings, the careers page or press. Web search returned nothing Checkmk-specific |
| Collective agreement | NONE found | Postings offer "an attractive salary", with no "tarifgebunden" or "Tarifvertrag"; reviewers describe individually negotiated pay ("je nach Verhandlungsgeschick") |
| European works council | N/A (well below the thresholds) | - |
| Conflict signals | None found | - |

Neither a works council nor a collective agreement exists, and since 2025 the company is PE-owned with an aggressive growth plan. Together with the 2026 reviews about retention and rising micromanagement in sales, this combination calls for caution, even though there is no evidence of silent firings today.

**Verdict:** CAUTION

---

## Section 9: Regulated Industry

IT infrastructure monitoring is not a regulated sector. Customers in finance, public sector and critical infrastructure bring security expectations (the Cloud Security Engineer posting cites "world-class resilience", SOC/compliance work; one IT reviewer complains of "mainly bureaucracy so that compliance fits"), and NIS2/ISO 27001-style controls apply to the SaaS. None of this means formal safety cases or slow regulated releases for product engineering.

**Verdict:** PASS

---

## Section 10: On-Call

- **Product development (Python/Vue teams):** current postings mention no on-call. The product is mostly self-hosted software shipped in versioned releases, so a feature team does not run production. Customer incidents go to Support, which was expanded to APAC in 2025 for round-the-clock coverage.
- **SaaS platform (Checkmk Cloud on AWS EKS):** a May 2025 Platform/Cloud Engineer posting asked for candidates "open to on-call duties". Platform, SRE and cloud-security roles are therefore likely to carry on-call.
- **CI/build platform:** internal developer tooling; no on-call indicated.

**Verdict:** CAUTION (team-dependent): PASS for product development roles, likely FAIL for Checkmk Cloud platform/SRE roles. Confirm in the interview whether product engineers working on Cloud-only features (e.g. Explain with AI) join an incident rotation.

---

## Section 11: Interview Process

Glassdoor (15 interview reports, updated 29 Apr 2026, via CDP):

| Metric | Value |
|---|---|
| Difficulty | 3.3 / 5 |
| Positive experience | 60% (13% negative) |
| Average duration | ~25 days (Software Developer slowest at ~42 days) |
| Rounds | Not stated; reported stages suggest 3-4 |

Reported stages: skills test 26%, phone interview 20%, one-on-one 20%, presentation 11%, background check 9%, group interview 6%. 69% of candidates applied online. Software Engineer interviews are rated "very easy", while Senior QA and Business Development are rated "very hard". The pattern points to an experience- and take-home/skills-test-based process, not LeetCode-heavy. The Senior Python posting emphasises evolving a long-lived codebase, cross-team technical decisions, web API design and LLM/agent features, so expect design and code-review style discussions around those.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | PASS: own open-core monitoring/observability product |
| Not consulting | PASS: small product-consulting team exists; engineering builds the product |
| Profitable | PASS: €5.16M net income on €28.5M revenue (2024), €19.7M cash |
| Employee count | 164 average in 2024; 250+ claimed in 2026 |
| English-speaking | PASS: business-fluent English required, German a plus; 35+ nationalities |
| Local entity + engineering contracts | PASS: Checkmk GmbH, HRB 165902, Munich HQ with R&D |
| Location / work model | Kellerstraße 27, Haidhausen; Rosenheimer Platz S-Bahn ~220 m. Remote for everyone, hybrid or on-site optional |
| Glassdoor | 4.8 (27 reviews, directional only); WLB 4.8, 95% recommend |
| Kununu | 4.3 (60 employee reviews), 83% recommend (last 2 years), no Top Company badge |
| Salary | BELOW (indicative): published engineering ranges €60-95K; no equity or bonus |
| AI/ML content | Moderate: LLM product features (Explain with AI, assistant, MCP server), agents/tool integration in the senior role |
| Computer-language/Tech-stack | Python-centric (Vue.js/TypeScript frontend, C++/Rust core and agents, AWS EKS) |
| No on-call | CAUTION: none for product teams; SaaS platform roles "open to on-call duties" |
| WLB / Stability | Good WLB in R&D; profitable; PE-owned since 2025 |
| Works council / collective agreement | CAUTION: none found |
| Regulated industry | PASS |
| Review themes | R&D positive (flexibility, geeky pragmatic culture); sales overload and micromanagement in 2025-2026; legacy code; flat pay |
| PE ownership | PSG control investment Feb 2025; profit-transfer to holding; growth push |

---

## Section 13: Verdict

**Actively pursue, conditional on compensation.** Checkmk is a profitable Munich software product company with a Python-centric codebase, a real LLM/agent product layer, English as the working language, remote-first flexibility and strong R&D work-life balance.

**Strengths:**
- Product company with an 18% net margin, €19.7M cash, a growing customer base (4,000+) and a respected open-source community.
- Python is the core language. The current Senior Python role explicitly covers AI assistant and agent/tool-integration features, API design and architecture evolution of a large codebase.
- Remote for everyone, no core hours, 6-week EU workation, central office next to Rosenheimer Platz S-Bahn.
- Engineering reviews are consistently positive on WLB and culture; negatives cluster in sales.

**Hard blockers:**
1. None confirmed. Compensation is the closest to a blocker: the only published engineering ranges are €60-95K (AI Software Engineer €70-95K), and the Teamlead PM posting shows €90K. That is below the levels.fyi Munich 75th percentile (€104K) and below what large profitable Munich corporations pay at senior/staff level. There is no equity or bonus for individual contributors. If the Staff band stays under ~€100K, treat this as a hard blocker.

**Secondary concerns:**
- PE ownership since 2025 (PSG, bidco structure, profit transfer), with growth targets and possible holding-level debt. A small cluster of negative 2025-2026 reviews (overload, micromanagement, retention) follows the deal.
- No works council or collective agreement found, so restructurings would not have to go through a social plan.
- On-call is likely for Checkmk Cloud platform/SRE roles; product roles appear free of it.
- Legacy codebase (Nagios roots, many years of growth) and reported silos/unclear ownership between tech teams.
- The title ladder may top out at Senior: only a "Staff Software Engineer" posting from May 2026 (now expired) shows a staff level exists, and nothing is known about its scope.

**Recommendation:** Apply to the Senior Python Software Engineer role (or a Staff role if one reopens) if the recruiter confirms a band of at least ~€100K in the first call. In interviews, verify: (1) the salary band and whether any management equity plan extends to senior ICs, (2) that the role has no on-call rotation for Checkmk Cloud, (3) how PSG's growth plan affects R&D headcount and expectations, (4) whether a Staff-level IC track with defined scope exists, and (5) how much of the AI assistant/agent work is real roadmap versus a single Cloud feature.

---

## Sources

- [Checkmk Imprint](https://checkmk.com/imprint)
- [Checkmk About Us](https://checkmk.com/company/about-us)
- [Checkmk Work at Checkmk](https://checkmk.com/company/work-at-checkmk)
- [Checkmk Personio job board](https://checkmk-gmbh.jobs.personio.de/) (XML feed via curl: https://checkmk-gmbh.jobs.personio.de/xml)
- [Checkmk announces strategic investment from PSG (newsroom)](https://checkmk.com/company/newsroom/checkmk-announces-strategic-investment-psg)
- [Business Wire: Checkmk Announces Strategic Investment from PSG](https://www.businesswire.com/news/home/20250226585299/en/Checkmk-Announces-Strategic-Investment-from-PSG)
- [Checkmk Forum: The next phase for Checkmk](https://forum.checkmk.com/t/the-next-phase-for-checkmk/52512)
- [Startbase: Checkmk sichert sich strategisches Investment von PSG Equity](https://www.startbase.de/news/checkmk-sichert-sich-strategisches-investment-von-psg-equity/)
- [Preqin: Checkmk GmbH](https://www.preqin.com/data/profile/asset/checkmk-gmbh/728278)
- [NorthData: Checkmk GmbH (via CDP)](https://www.northdata.com/Checkmk+GmbH,+M%C3%BCnchen/HRB+165902)
- [NorthData: Checkmk Holding GmbH (via CDP)](https://www.northdata.com/Checkmk+Holding+GmbH,+M%C3%BCnchen/HRB+298050)
- [handelsregister.ai: Checkmk GmbH, FY2024 accounts (via CDP)](https://handelsregister.ai/de/unternehmen/Checkmk%20GmbH)
- [webvalid: Checkmk Holding GmbH](https://www.webvalid.de/company/Checkmk+Holding+GmbH,+M%C3%BCnchen/HRB+298050)
- [Kununu: Checkmk GmbH (via CDP)](https://www.kununu.com/de/checkmk)
- [Kununu: Checkmk reviews (via CDP)](https://www.kununu.com/de/checkmk/kommentare)
- [Kununu: Checkmk salaries (via CDP)](https://www.kununu.com/de/checkmk/gehalt)
- [Glassdoor: Checkmk GmbH overview (via CDP)](https://www.glassdoor.com/Overview/Working-at-Checkmk-GmbH-EI_IE3188169.11,23.htm)
- [Glassdoor: Checkmk GmbH reviews (via CDP)](https://www.glassdoor.de/Bewertungen/Checkmk-GmbH-Bewertungen-E3188169.htm)
- [Glassdoor: Checkmk GmbH interviews (via CDP)](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/Checkmk-GmbH-Fragen-im-Vorstellungsgespr%C3%A4ch-E3188169.htm)
- [Teamblind: Checkmk (no page, via CDP)](https://www.teamblind.com/company/Checkmk)
- [levels.fyi: Checkmk (no profile, via CDP)](https://www.levels.fyi/companies/checkmk/salaries)
- [levels.fyi: Software Engineer, Munich Metro Region (via CDP)](https://www.levels.fyi/t/software-engineer/locations/munich-metro-region)
- [JobRise: Tech jobs Munich salary guide 2026](https://jobrise.io/en/blog/tech-jobs-munich-salary-guide-2026/)
- [jobleads: AI Software Engineer, Checkmk Munich](https://www.jobleads.com/de/job/ai-software-engineer-m-f-d--munchen--e53d30eb4a24e51072be5470b483835ec)
- [jobgether: AI Software Engineer, Checkmk (expired)](https://jobgether.com/offer/686c759fbd58473134d4a3d8-ai-software-engineer-m-f-d)
- [jobgether: Staff Software Engineer, Checkmk (expired)](https://jobgether.com/offer/69fd12cff77bd3019866d2d6-staff-software-engineer-m-f-d)
- [MisuJob: Staff Software Engineer, Checkmk Munich (expired)](https://misujob.com/jobs-public/staff-software-engineer-m-f-d-munich-1712709/)
- [bayern.jobs: Platform/Cloud Engineer, Checkmk (expired)](https://www.bayern.jobs/job/platform-cloud-engineer-m-f-d-13541939)
- [remotely.de: Engineering Manager SaaS, Checkmk (expired)](https://www.remotely.de/job/checkmk-gmbh-engineering-manager-mfd-saas)
- [arc.dev: Senior Python Engineer, Checkmk](https://arc.dev/remote-jobs/j/checkmk-senior-python-engineer-m-f-d-llg5wgk0vd)
- [arbeitnow: Senior Software Developer in CI, Checkmk](https://www.arbeitnow.com/jobs/companies/checkmk-gmbh/senior-software-developer-in-ci-munich-52426)
- LinkedIn Jobs (voyager API via CDP): postings 4483062508 (Senior Python Software Engineer), 4450139215 (Senior Software Developer in CI), 4476631519 (Python Software Engineer), 4450128803 (Team Lead Product Management)
- [GitHub: Checkmk/checkmk repository](https://github.com/Checkmk/checkmk) (language stats via GitHub API)
- [GitHub: Checkmk organisation](https://github.com/Checkmk)
- [Checkmk 2.5 key highlights](https://checkmk.com/blog/key-highlights-checkmk-25)
- [Checkmk 2.5 newsroom release](https://checkmk.com/company/newsroom/checkmk-25-unifies-monitoring-and-observability-speed-issue-resolution-across-hybrid-environments)
- [Checkmk Werk #22263: built-in MCP server](https://checkmk.com/werk/22263)
- [APMdigest: Checkmk 2.5 released](https://www.apmdigest.com/checkmk-25-released)
- [Checkmk Conference material](https://conference.checkmk.com/download_file/view/b9a2a294-c681-4049-b473-0c293425d493/243)
- [TrueUp: Checkmk (no profile, via CDP)](https://www.trueup.io/co/checkmk)
- [Great Place to Work Germany search (via CDP)](https://www.greatplacetowork.de/?s=checkmk)
- [Nominatim: Kellerstraße 27 geocode](https://nominatim.openstreetmap.org/search?q=Kellerstra%C3%9Fe+27,+81667+M%C3%BCnchen&format=json&addressdetails=1)
- [Overpass API (transit stops and routes)](https://overpass-api.de/api/interpreter)
