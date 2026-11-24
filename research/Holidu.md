# Holidu - Full Research Report

_Researched: 2026-09-01_

> **Note on retrieval methods:** Kununu, Glassdoor, NorthData, levels.fyi and the Holidu careers portal all block plain HTTP clients (Kununu returns HTTP 405 to curl, Glassdoor serves a bot wall). All of these were retrieved with **Playwright over CDP** against the persistent authenticated Chromium instance on `localhost:9222`. Office location data came from **OSM Nominatim/Overpass**. Everything else used WebFetch or WebSearch.

> **Material change since the previous evaluation (May 2026):** the earlier report concluded Holidu had no Python and no AI/ML engineering roles. That is no longer true. As of September 2026 Holidu has a dedicated Agentic Experience department reporting to the CTO and a Python-first data platform organisation with open Senior and Staff roles. The tech-stack and role-type blockers from the previous report are now resolved. The compensation blocker is not.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 2014 (12 years) |
| Employees | ~700 globally (company careers page, Sept 2026); Kununu profile states 700; Glassdoor bracket "501 to 1,000"; third-party trackers cite ~792 (March 2026) |
| Revenue (FY2024) | ~$144.7M (up from ~$102.9M in FY2023) |
| Profitability | Claimed EBIT-positive since 2020 with "seven-digit positive EBIT", but still raising growth capital (Series F, mid-2025) and Kununu reviews describe an active "push for profitability" as of mid-2026 - **BORDERLINE** |
| Ownership | Private, VC-backed (83North, Prime Ventures, Vintage Investment Partners, Bessemer, HV Holtzbrinck Ventures, MAIRDUMONT VENTURES, Key1 Capital, Senovo, Team8) |
| Software-centric | Own two-sided marketplace plus a proprietary PMS, ~170-200 person engineering org, no client billing - **PASS** |

### Key People

- **Johannes Siebers** - Co-founder and CEO. 99% CEO approval on Glassdoor.
- **Michael Siebers** - Co-founder and CTO. The Agentic Experience team reports directly to him.
- Both brothers are the registered Geschäftsführer of Holidu GmbH (confirmed via NorthData and the Impressum).

### Funding History

Round labelling is inconsistent across trackers (Crunchbase calls the 2025 round a "Venture Round"; Tracxn and PitchBook call it Series F). Figures below are the best cross-referenced view.

| Date | Round | Amount | Valuation |
|---|---|---|---|
| 2014-2016 | Seed / Series A | undisclosed | - |
| 2018 | Series B | undisclosed | - |
| 2019 | Series C | undisclosed | - |
| Sept 2020 | Extension (Kees Koolen, ex-Booking.com CEO) | ~EUR 5M (EUR 4M+ from Koolen personally) | - |
| 2021 | Series D | ~$45M | - |
| Oct 2022 | Series E | ~EUR 100M | - |
| Apr-Jun 2025 | Series F / Late VC | ~EUR 46M / ~$53M (same round, differing reports) | ~EUR 375M |
| **Total** | | **~$275M-$323M depending on source** | |

Also of note: acquisition of **Cybevasion SAS** (France) and holdings in Spain Holiday Online Rentals SL, September 2022 ApS, Holidu Hosts GmbH and Holidu Hosts France SAS. The group is running an active M&A consolidation strategy (there are two dedicated M&A roles open in Munich).

### Business Model

Two products under one roof: **Holidu**, a curated vacation-rental search and booking marketplace for guests (~4M guests/year, ~100M website users/year, ~6.7M average monthly active EU users per the DSA disclosure in the Impressum), and **Bookiply**, a property management system and distribution service for hosts (60,000+ rentals, 55k+ hosts). Revenue comes from booking commission and host subscription/service fees. This is a genuine product company, not a services business.

### Consulting-Adjacency Assessment

Not applicable. Holidu does not self-identify as consulting, has no client-billing model, no consultant career track, and engineers build an internal product used by Holidu's own guests and hosts. **Not consulting-adjacent.**

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **Holidu GmbH** | Amtsgericht München **HRB 213215**, EUID DED2601V.HRB213215, incorporated 27 July 2014, active | Riesstr. 24, 80992 München | *"Online-Vermittlung von Reisen aller Art"* (online brokerage of travel of all kinds) |
| **Holidu Hosts GmbH** | Amtsgericht München HRB 227317 | Munich | Host-side / Bookiply operations; profit-transfer agreement with Bookiply GmbH since 2022 |

Verified against NorthData (HRB 213215) and the Holidu Impressum (VAT ID DE295937815, register court AG München, HRB 213215, managing directors Johannes and Michael Siebers).

**Verification note:** the registered corporate purpose reads as a *travel brokerage* purpose rather than an explicit software-development purpose. This is normal for a marketplace operator and is not a sales-shell pattern: the same entity is the sole employer named on every Munich engineering job posting, the Munich office at Riesstr. 24 is the engineering headquarters (~170-200 techies), the entity holds its own trademarks (holidu, Fewodata, BESTFEWO, Urlaubär), and it has received German **Forschungszulage** (R&D tax credit) state aid of EUR 60,000-500,000 plus a separate EUR 1,141,445 state-aid entry, which is only available against qualifying in-house R&D. Engineers are employed directly by the GmbH on German contracts. No PEO/EOR arrangement is in evidence.

**Verdict:** PASS

---

## Section 3: Office Location

- **Office address:** Riesstraße 24, 80992 München (Moosach district, north-west Munich). Geocoded to 48.17894 N, 11.53825 E.
- **Nearest public transit:** **Olympia-Einkaufszentrum** (U1, U3, plus a large bus and tram hub) and **Georg-Brauchle-Ring** (U1) are the nearest rail stations per OSM Overpass, both within roughly 600-700 m of the office. The office is not directly on top of a U-Bahn entrance, so the last leg is either a ~390 m walk from a bus stop or a longer walk from the U-Bahn.
- **Work model:** **Hybrid, 50% in-office** (stated explicitly in every current Munich engineering job posting; the Staff Data Engineer posting says "50%+"). Kununu reviewers describe "a maximum of two days in the office per week", though a June 2026 review complains about "more office days" being introduced. Up to 8 weeks per year may be worked from any of the ~29 other European offices. Fully-remote Germany roles are **not** currently offered. This is a change: the May 2026 evaluation recorded **5 active remote-Germany roles** on the careers page. Today the portal lists remote roles only for **Remote Italy (2 positions)**, with every German position tied to Munich, Hamburg, Freiburg, Flensburg, Friedrichshafen or Dresden. Combined with the reviewer complaint about "more office days" being introduced, the direction of travel on remote work is toward the office, not away from it.

---

## Section 4: Reviews

### Great Place to Work

**Not certified.** A search of the Great Place to Work Germany company directory (H listing) returned no Holidu entry, and no GPTW certification appears on Holidu's own careers or press pages. Holidu does market itself as being among the German startups with the highest employee satisfaction "according to Kununu and Glassdoor", but it does not claim a GPTW seal. **No GPTW signal, positive or negative.**

### Glassdoor

Retrieved 2026-09-01 via the authenticated Glassdoor session. Employer ID E1460824.

| Metric | Global | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | **4.6** (149 reviews) | **4.6** (33 reviews) | no separate data | **no reviews** |
| **WLB** | 4.5 | 4.6 | - | - |
| **Culture & Values** | 4.8 | 4.8 | - | - |
| **Comp & Benefits** | 4.1 | 4.2 | - | - |
| **Career Opportunities** | 4.3 | 4.4 | - | - |
| **Senior Management** | 4.4 | 4.4 | - | - |
| **Diversity & Inclusion** | 4.7 | 4.7 | - | - |
| **% Recommend** | 95% | 95% | - | - |
| **CEO Approval** | 99% | 95%+ | - | - |
| **Business Outlook** | 88% positive | 88% positive | - | - |

Notes and caveats:
- The Germany filter yields only **33 reviews**. Treat the German sub-scores as directional only.
- The **Software Engineer job-title filter returns zero reviews**, and the Munich city-filtered review page 404s. There is therefore **no engineer-specific or Munich-specific Glassdoor evidence at all**. Individual reviews from engineering staff do exist in the global pool (a Senior Backend Developer, a Software Engineering Manager and a Senior QA Manager all appear on the overview page, all rating 4-5 stars), but they are too few to aggregate.
- Comp & Benefits is the lowest-rated category on Glassdoor, consistent with every other source.
- Glassdoor's own AI pay summary states: *"salaries are generally low, especially for roles in Munich, with calls for better pay to match the cost of living."*

### Kununu

Retrieved from `kununu.com/de/holidu1` via Playwright (curl returns HTTP 405).

- **Overall score:** **4.1 / 5.0** (exactly the Internet-industry average of 4.1)
- **Recommendation rate (Weiterempfehlung):** **82%** (last 2 years)
- **Total reviews:** **242** (153 employee reviews since 2015, plus applicant reviews; 83 salary entries, 70 culture entries)
- **Kununu Top Company:** **No seal shown** on the profile as of Sept 2026
- Sub-scores: Vielfalt 4.3, Unternehmenskultur 4.1, Arbeitsumgebung 4.1, **Karriere & Gehalt 3.8**
- Best-rated factor: **Kollegenzusammenhalt 4.4**. Worst-rated factor: **Gehalt/Benefits 3.5**.
- 72% say they are satisfied with their salary (152 responses), but the salary figures published are for non-technical roles: Account Manager EUR 46.5K, Sales Manager EUR 51.5K, Buchhalter EUR 45.5K.

**Trend signal, and why it is weaker than it first looks.** Comparing against the May 2026 evaluation of this company (its figures, not independently re-verifiable today, since neither platform exposes rating history):

| Platform | May 2026 | Sept 2026 | Change |
|---|---|---|---|
| Kununu overall | 4.3 (238 reviews) | **4.1** (242 reviews) | **-0.2** on ~4 new reviews |
| Kununu recommendation | 81% | 82% | +1pp |
| Glassdoor overall | 4.4 (146 reviews) | **4.6** (149 reviews) | **+0.2** on ~3 new reviews |
| Glassdoor % recommend | 90% | 95% | +5pp |
| Glassdoor WLB | 4.4 | 4.5 | +0.1 |
| Glassdoor Culture & Values | 4.7 | 4.8 | +0.1 |
| Glassdoor Comp & Benefits | 3.9 | 4.1 | +0.2 |

**The two platforms moved 0.2 in opposite directions over the same three months, each on three to four new reviews.** Three new reviews cannot shift a true mean of 146 by 0.2; both displayed scores are recency-weighted, so both movements are artifacts of a very small recent cohort being weighted heavily. The honest reading is that **neither move is evidence of a sentiment trend**, and the earlier framing of a Kununu "decline" does not survive being put next to the Glassdoor figures. What the divergence does confirm is that the two samples measure different populations: Kununu is German-language and Munich-weighted, Glassdoor skews international and English-language across the ~29 European offices. Treat both absolute scores as good, and disregard the deltas.

### Blind / Teamblind

**No company page exists.** `teamblind.com/company/Holidu` returns "Page not found". Blind coverage is US-centric and Holidu has no US engineering presence. **No data.**

### Review Themes (2024-2026)

**Positives:**
- **Team cohesion is the standout theme** across both platforms and is Kununu's highest-rated factor (4.4). "The team spirit at Holidu is exceptional. Collaboration within and across teams is truly impressive, people are approachable, supportive, and always willing to help each other."
- **Genuinely international and modern culture**: 60+ nationalities, English-language workplace, "young, dynamic", "professional but relaxed atmosphere".
- **Real learning investment**: personal learning budget, 2 dedicated self-study days per year, internal workshops, structured bi-directional feedback. "Every employee gets a learning budget and access to multiple internal trainings. There is a focus on enabling everyone to use AI."
- **Work-life balance is defensible but not automatic**: "the company fosters a good work-life balance, *if you actively seek it out and demand it*". Hybrid with max two office days is repeatedly praised.
- **Strong technology identity**: "Great culture, strong tech focus and very supportive team" (Software Engineering Manager, Glassdoor). "People are passionate about the product and technology."
- Benefits confirmed by reviewers: Homeoffice 79%, employee events 78%, flexible hours 76%, 28 vacation days + 13 Bavarian public holidays, up to 10 additional unpaid days, gym discount.

**Negatives:**
- **Compensation is the single most consistent complaint**, and it is specific rather than generic: *"Compared to the competition, the salary is simply at the lower end of the salary bands and is incredibly opaque. While new hires are hired here at a rate 15k higher than existing staff members in the same position, the company cites salary bands (which no one publicly discloses)."* Also *"big pay gap for same work"* and *"Employees are not valued financially. Every year, more and more is demanded, without any corresponding compensation."*
- **Profitability pressure is being felt on the floor (2026 reviews):** *"the current push for profitability is putting significant pressure on employees, with many teams already feeling overworked and stretched to their limits... more office days, reduced bonus opportunities, and increasing workloads are likely continuing to drive higher employee turnover."*
- **Top-down communication gap:** *"Feedback isn't passed up the chain. There's a lack of transparency regarding priorities and a lack of communication from (all the way) at the top down."* Echoed by *"negative Entwicklungen werden oft nicht ernst genommen"* (negative developments are often not taken seriously) and *"mehr auf Mitarbeiterstimmen/Feedback hören"*.
- **Shipping half-finished work:** *"Products are released before they're fully developed which causes so so so much work."* This is the one negative theme with direct engineering relevance.
- **Career progression can be structural rather than merit-based:** *"Whether you can be promoted... often depends on the size of the team rather than on your skills or performance."* Also allegations of favouritism in internal hiring.
- **Process immaturity:** *"Some processes are still being built (or re-built), so you need to be comfortable with ambiguity."*
- **Cost-cutting via outsourcing:** a Nov 2024 review reports *"Employees from two external companies were hired in order to save costs"* to handle simple inbound support requests.
- **Caveat:** the bonus-structure, cold-calling and unreachable-target complaints (the most severe negatives by tone) are almost entirely from **Sales and Account Management**, not engineering. They should be weighted down for an engineering role, but they do evidence a management style that changes incentive structures unilaterally.

### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | **Not evidenced.** CEO approval 99% on Glassdoor; senior management rated 4.4. The 2026 criticism is of transparency and prioritisation, not of conduct. The previous (May 2026) report noted isolated historical allegations of sexist remarks and managers intoxicated during work hours; no such reports appear in the current review pool. |
| 24/7 Work Expectation | **Not evidenced.** No reviewer describes always-on availability. WLB rated 4.5-4.6 on Glassdoor. |
| Internal Surveillance | **Not evidenced.** No mentions on either platform. |
| Fear-driven Management | **Not evidenced** as fear, but target pressure is real: *"the targets are getting higher and unreachable. The company wants every day more but gives every day less."* (Customer Support, Nov 2024.) |
| Communication Breakdown | **Present, moderate.** Repeated 2026 theme: feedback not passed upward, priorities not transparent, internal survey results not acted on. This is the most credible negative signal. |
| Unpaid Overtime | **Not directly evidenced.** "Teams already feeling overworked and stretched to their limits" (June 2026) is workload, not unpaid hours. |
| Silent Firings | **Not evidenced** in current reviews. Historical reviews referenced "rounds of cuts in different departments" and, more pointedly, **"fast downsizing decisions without early communication"** (captured May 2026); see Section 8. The pattern described is abruptness and poor notice rather than concealment. |
| Work-Life Balance issues | **Low but conditional.** WLB scores are strong and hybrid is protected, but reviewers qualify it: WLB is good *"if you actively seek it out and demand it"*, and workload pressure is rising with the profitability push. |

**Risk level: LOW to MODERATE.** There is no systemic toxicity and no conduct red flag. What is present is (b) growth-stage dysfunction: a company mid-transition from growth-at-all-costs to profitability, with a top-down communication gap, rising workload, and compensation that has not kept pace. This is localized to the transition, not to any one team, and it is trending in the wrong direction on Kununu.

---

## Section 5: Compensation

### Salary Data

| Source | Title | Base (EUR) | Stock/yr | Bonus | Total Comp | Data Points |
|---|---|---|---|---|---|---|
| levels.fyi (Germany, median) | Software Engineer, **Senior** level, 8 yrs exp | ~EUR 77.4K | EUR 0 | EUR 0 | **~EUR 77.4K** | median of visible set |
| levels.fyi (submission, Mar 2025) | **Senior**, Distributed Systems / Back-End, 8 yrs exp | EUR 87K | none | none | EUR 87K | 1 |
| levels.fyi (submission) | API Development / Back-End, 6 yrs exp | EUR 80K | none | none | EUR 80K | 1 |
| levels.fyi (submission, Sep 2025) | **Middle**, API Development / Back-End, 5 yrs exp | EUR 73K | none | none | EUR 73K | 1 |
| levels.fyi (company-wide) | Software Engineer (all levels) | - | - | - | ~EUR 78-83K (site shows $90.8K) | small sample |
| levels.fyi (company-wide) | Software Engineering Manager | - | - | - | ~EUR 110-115K (site shows $127.2K) | small sample |
| Glassdoor salary tab | Software Engineer, Munich | **no data** | - | - | - | 0 |
| Kununu (Gehälter) | technical roles | **no data** (only Account Manager EUR 46.5K, Sales Manager EUR 51.5K, Buchhalter EUR 45.5K) | - | - | - | 83 total, none technical |
| Job postings | all Munich engineering roles | **no range disclosed** | - | - | - | - |

**Longitudinal check.** The May 2026 evaluation recorded levels.fyi figures of Software Engineer ~EUR 79K-91K, Senior Software Engineer ~EUR 91K base (8 yrs experience), and Software Engineering Manager EUR 88K-103K. Against today's median of EUR 77.4K and a top Senior submission of EUR 87K, **Senior pay has not risen in the intervening period and the median has drifted slightly down.** Only the Engineering Manager band appears to have moved up. For a company running a stated profitability push, this is the expected pattern and it corroborates the reviewer complaint that "every year, more and more is demanded, without any corresponding compensation from the employer."

Reviewers in the earlier capture also specifically flagged a **missing 13th salary** (13. Monatsgehalt). That matters for comparison shopping in the German market: many large Munich employers pay 13 or 13.5 months, so a EUR 87K Holidu base is not equivalent to a EUR 87K base elsewhere. On a 13-month basis the effective gap widens by roughly 8%.

Munich percentile reference for a Senior Software Engineer is not directly retrievable from the same sources for Holidu specifically. The useful comparison: levels.fyi's own Munich Senior Software Engineer market medians sit meaningfully above EUR 90K total, and large profitable Munich employers (automotive OEMs, enterprise software, US tech) pay Senior engineers in the EUR 95K-130K+ total range. Holidu's observed Senior data points cluster at **EUR 77K-87K, base-only**.

### Equity / Stock

**Effectively none for engineers.** Every levels.fyi submission for Holidu records **EUR 0 stock and EUR 0 bonus**: the packages are pure base salary. The company is private and pre-IPO, so any equity that does exist is illiquid. One Glassdoor reviewer (Senior Product Manager, May 2026) lists *"No clear strategy of stocks buybacks"* as a con, which implies some employees do hold instruments but have no defined liquidity path. Sales roles have a variable bonus, and reviewers report it has been restructured roughly eight times in 18 months, always unfavourably. The AI Engineer posting promises "a very competitive senior package" but discloses no numbers.

### Verdict

**BELOW.** Holidu's Senior Software Engineer packages (EUR 77K-87K, base only, no stock, no bonus) sit clearly below what large, profitable Munich corporations pay at the same level, and below the Munich market median for a Senior engineer. This is not an inference from a single source: levels.fyi submissions, the Glassdoor Comp & Benefits score (4.1, its lowest category), the Kununu Gehalt/Benefits score (3.5, its lowest factor), Glassdoor's own AI pay summary, and multiple 2026 free-text reviews all say the same thing independently. The pay-band opacity and the reported 15K gap between new hires and incumbents in the same role are an additional concern: they mean a strong negotiated entry offer is possible, but subsequent raises are unlikely to track the market.

---

## Section 6: AI/ML & Tech Stack Fit

### AI Strategy

Holidu's AI investment is real and recently formalised, not marketing veneer. Three distinct strands:

1. **Agentic Experience department** (the significant development since the last evaluation). A small team inside the ~200-person engineering org reporting **directly to the co-founder/CTO**. It runs production LLM agents handling "thousands of real conversations across WhatsApp, email, in-product chat, and the help center", with the surface area expanding into adjacent products and internal tools. The posting explicitly describes "multi-agent systems with tool calling, handoffs, and production evals" and the **Model Context Protocol** stitching agents to the rest of the platform. This is genuine production agentic engineering, not a proof of concept.
2. **Applied ML in the core marketplace**: a new **Dynamic Pricing & Revenue Management** team (data scientist + data analyst + software engineer), plus **Rankings & Recommendations** data science. Model lifecycle runs on MLflow and SageMaker with deployment APIs.
3. **Internal AI adoption**: an in-house **HoliduGPT**, company-wide access to Claude, Copilot and Codex, internal AI trainings, and learning budgets with "a strong focus on AI". The AI Engineer role lists "deep fluency with AI coding tools like Claude Code" as a hard requirement.

The company value statement is explicit: *"we use artificial intelligence and machine learning to develop our own technology."* Cross-referenced against job postings, this holds up.

**The important nuance:** the AI work splits along a language line. The **agentic/LLM product work is Kotlin/Java**. The **ML platform, pricing models, and data platform work is Python-first**. These are different teams with different stacks.

### Tech Stack

Derived from: current Munich job postings (Senior AI Engineer, Senior Software Engineer Revenue Management, Senior DataOps Engineer, Staff Data Engineer, DevOps Engineer), the Holidu careers tech page, and the Holidu tech blog at medium.com/@holidu.

| Category | Technologies |
|---|---|
| **Primary language(s)** | **Kotlin** and **Java 21+** (backend product, Spring Boot, Gradle; the May 2026 capture recorded Java 11+, so the platform has been kept current rather than left to age); **Python** (data platform, ML, DataOps, pricing); TypeScript / ReactJS (frontend); SQL |
| **AI/ML** | LLM multi-agent systems with tool calling and handoffs, production evals, **Model Context Protocol (MCP)**, HoliduGPT (internal), **MLflow**, **AWS SageMaker**, model-serving APIs; Claude Code / Copilot / Codex as everyday dev tooling |
| **Cloud** | AWS throughout (EKS, Lambda, ELB, S3, Kinesis, SNS, EventBridge, DynamoDB, RDS, Redshift, Athena, Firehose) |
| **Infrastructure** | Kubernetes (EKS), **Terraform**, Docker, Jenkins, Nginx, ArgoCD-style CI/CD |
| **Data** | **Airflow + dbt-core**, Redshift (provisioned and serverless), Athena, **DuckDB**, PySpark, Kafka, Airbyte, Fivetran, S3 lakehouse, Elasticsearch, Valkey/Redis, PostgreSQL |
| **Other** | GraphQL, SQS/ActiveMQ, ELK, Grafana, Datadog, Looker, **OpsGenie**, Figma |

### Current Open Roles

Verified live on the Holidu careers portal (`holidu.com/careers/list?location=Munich, Germany`) on 2026-09-01. 30 open Munich positions total, of which 4 are tagged Engineering/IT and 11 Data Science/Analytics.

| Role | Division/Team | Level | Key Tech | Link |
|---|---|---|---|---|
| **Senior Software Engineer - Revenue Management** | Dynamic Pricing & Revenue Management | Senior | **Python**, Airflow, dbt, MLflow, SageMaker, Terraform, Docker, AWS EKS, Redshift/Athena/DuckDB | [link](https://www.holidu.com/careers/senior-software-engineer-revenue-management-all-genders) |
| **Staff Data Engineer** | Data Engineering (BI dept, team of 5) | **Staff** | **Python-first**, Airflow, dbt-core, Redshift, Athena, DuckDB, PySpark, Kafka, Terraform, EKS | [link](https://www.holidu.com/careers/staff-data-engineer-all-genders) |
| **Senior DataOps Engineer / Software Engineer - Revenue Management** | Dynamic Pricing & Revenue Management | Senior | **Python**, MLflow, SageMaker, Terraform, CI/CD, AWS (near-identical to the SWE role above) | [link](https://www.holidu.com/careers/senior-dataops-engineer-software-engineer-revenue-management-all-genders) |
| **Senior AI Engineer - Agentic Experience** | Agentic Experience (CTO team) | Senior | **Kotlin/Java**, AWS, Kubernetes, ReactJS, PostgreSQL, DynamoDB, Redis, MCP, LLM agents | [link](https://www.holidu.com/careers/senior-ai-engineer-agentic-experience-all-genders) |
| AI Engineer - Agentic Experience | Agentic Experience (CTO team) | Mid | as above | [link](https://www.holidu.com/careers/ai-engineer-agentic-experience-all-genders) |
| (Senior) DevOps Engineer | Platform / Infrastructure | Senior | Terraform, Kubernetes, AWS, CI/CD; **explicitly mentions on-call rotations** | [link](https://www.holidu.com/careers/senior-devops-engineer-all-genders) |
| Senior Data Scientist - Dynamic Pricing & Revenue Management | Revenue Management | Senior | Python, ML | [link](https://www.holidu.com/careers/senior-data-scientist-dynamic-pricing-revenue-management-all-genders) |
| Senior Data Scientist - Rankings & Recommendations | Search / Ranking | Senior | Python, ML | [link](https://www.holidu.com/careers/senior-data-scientist-rankings-recommendations-all-genders) |
| Staff Data Scientist | Data Science | Staff | Python, ML | [link](https://www.holidu.com/careers/staff-data-scientist-all-genders) |

An earlier "Senior AI Product Engineer - Agentic Experience (CTO Team)" posting on the Northzone job board is **closed** ("no longer accepting applications") and is superseded by the Senior AI Engineer role above.

**Verdict:** Holidu runs two parallel stacks. The product backend and the headline agentic-LLM work are **Kotlin/Java on AWS EKS**, which does not match a Python-primary profile. But the **data platform, MLOps and pricing side is explicitly Python-first** (Airflow, dbt-core, PySpark, MLflow, SageMaker, Terraform, EKS) and is hiring at both **Senior and Staff** level.

---

## Section 7: Language

English is the working language of engineering. Every Munich engineering and data job posting is written in English with no German requirement; the only German-language postings in Munich are Sales/Account Management internships and two accounting roles (Debitorenbuchhalter, Junior Buchhalter). The engineering org is "over 170 techies from +40 nations" and the company overall spans 60+ nationalities. Employee reviews are written predominantly in English. Company values, principles, and the internal AI tooling are all presented in English.

**Verdict:** PASS

---

## Section 8: Stability

### Financial Position

| Metric | Value | Source |
|---|---|---|
| Revenue FY2023 | ~$102.9M | third-party tracker |
| Revenue FY2024 | ~$144.7M (~+41% YoY) | third-party tracker |
| Group total assets (31.12.2022) | **EUR 112.7M** | NorthData, consolidated |
| Cash and bank balances (31.12.2022) | **EUR 79M** | NorthData, consolidated |
| Goodwill (31.12.2022) | EUR 22.2M | NorthData, consolidated |
| Latest filing | Consolidated Jahresabschluss to **31.12.2024** filed 22-23 April 2026 | NorthData publications list |
| Valuation (2025 round) | ~EUR 375M | Tracxn / press |
| Stated profitability | EBIT-positive since 2020, "seven-digit positive EBIT" | company statement, 2020-2022 era |

NorthData's free view exposes the **2022 consolidated balance sheet** in detail. The 2023 and 2024 consolidated filings exist (filed June 2025 and April 2026 respectively) but their line items sit behind the NorthData paywall and were not retrievable. **The EUR 79M cash figure is therefore as of 31 December 2022 and is four years stale.** Since then the company has closed a ~EUR 46M round (2025) and made at least one acquisition (Cybevasion, 2025).

The share capital has been increased repeatedly and steadily: EUR 256,653 (Oct 2022) > 268,733 (Jan 2023) > 278,737 (Jun 2024) > 297,311 (Jan 2025) > 311,241 (Mar 2025) > **317,901 (Mar 2026)**. Six capital increases in under four years is a company continuously issuing new shares, which is consistent with ongoing financing activity and with dilution of existing holders.

### Financial Runway

Holidu is VC-backed and its profitability claim is contested by its own 2026 employee reviews ("the current push for profitability"), so a runway model is warranted. **All figures below are estimates built on the last publicly visible cash position; treat them as a sanity check, not as accounts.**

| Cost line | Annual estimate |
|---|---|
| Staff: ~700 employees, blended fully-loaded cost ~EUR 75K (mix of ~200 Munich engineers at ~EUR 100-110K loaded and ~500 sales/ops staff across Southern Europe at ~EUR 55-65K loaded) | ~EUR 52M |
| Performance marketing / SEA (metasearch is paid-traffic dependent; Holidu runs a full Performance Marketing department) | ~EUR 35-50M |
| Cloud, tooling, data platform (AWS-heavy, 29 offices) | ~EUR 6-9M |
| Offices, travel, G&A across 29 locations | ~EUR 8-12M |
| **Total gross burn** | **~EUR 101M-123M/year** |

| Revenue source | Est. annual inflow |
|---|---|
| Booking commission + Bookiply host fees (FY2024 revenue ~$144.7M, i.e. ~EUR 133M) | ~EUR 133M/year |
| German Forschungszulage R&D credit | ~EUR 0.06M-0.5M/year |
| **Total revenue offset** | **~EUR 133M/year** |

| Scenario | Net burn | Cash at hand | Runway | Next round needed by |
|---|---|---|---|---|
| Optimistic (revenue continues +40%, costs flat, genuinely EBIT-positive) | net **positive** ~EUR 10-30M/year | EUR 79M (2022) + ~EUR 46M (2025 round) | indefinite | not needed |
| Base case (revenue growth slows to +15-20%, marketing spend scales with it, roughly breakeven) | ~EUR 0 to -EUR 10M/year | ~EUR 60-100M plausible | Years | ~2032 or never |
| Stress (travel demand softens, paid-traffic costs rise, EUR 25M/year net burn) | -EUR 25M/year | ~EUR 60M | ~2.4 years | ~2029 |

**Cash figure used:** EUR 79.0M "Kassenbestand, Guthaben bei Kreditinstituten und Schecks", consolidated group balance sheet as at **31.12.2022**, observed on NorthData 2026-09-01. The 2025 round adds roughly EUR 46M; three intervening years of operations are unmodelled because the 2023 and 2024 line items are paywalled.

**Interpretation:** even in the stress scenario Holidu has years, not months. This is not a company at risk of running out of money. The genuine stability question is not solvency but the **cost discipline that the profitability push is imposing on staff**, which is what 2026 reviewers are actually describing.

### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| 2020 (COVID) | Pandemic-era cost reduction | undisclosed | Referenced indirectly; company reached profitability in May 2020 during the pandemic |
| ~2023-2024 | "Rounds of cuts in different departments" | undisclosed | **Review-sourced only.** Cited in Glassdoor reviews captured in the May 2026 evaluation ("unstable company, struggling numbers leading to rounds of cuts in different departments"); not corroborated by any press report |
| ~2023-2024 | Downsizing decisions made without advance notice | undisclosed | **Review-sourced only.** Multiple reviewers in the May 2026 capture described "fast downsizing decisions without early communication". Consistent with the separate 2026 theme of poor top-down communication |
| Nov 2024 | Support work partially outsourced to two external companies "in order to save costs" | undisclosed | Kununu review, Customer Support |
| 2025-2026 | **No layoffs found** | - | No entries on TrueUp, no press coverage, no German-language reporting located |

There is **no verified public record of a mass layoff at Holidu**. What exists is review-sourced evidence of departmental cost-cutting and outsourcing, concentrated in support and sales rather than engineering, plus an active profitability drive in 2026. Headcount reported by third parties has drifted slightly downward (~816 in April 2026 per the earlier evaluation, ~792 in March 2026, ~700 stated by the company today), which is consistent with attrition and selective non-replacement rather than a cutting event. **The headcount trend is flat to slightly down while the company says it is scaling.**

**Verdict:** **CAUTION.** Solvency is not in question and the business model is proven. But this is a private, VC-backed, still-consolidating scale-up on its sixth-plus financing round, mid-transition to profitability, with flat-to-declining headcount, an unresolved liquidity path for any equity, and reviewers reporting rising workload and turnover as a direct result of the cost discipline. It is a stable *business*; it is not yet the *mature, settled employer* profile that a long-term commitment implies.

---

## Section 9: Regulated Industry

Holidu operates in consumer travel and vacation-rental distribution. The applicable regulatory surface is:

- **GDPR** (large consumer data estate, ~6.7M average monthly active EU users)
- **EU Digital Services Act** as an online platform: Holidu publishes DSA Art. 24(2) MAU figures and maintains Art. 11/12 contact points (compliance@holidu.com, contactpoint-dsa@holidu.com). A whistleblower system is linked from the site footer.
- **PSD2 / payment handling** for booking flows
- **EU Short-Term Rental Regulation (EU 2024/1028)**, phasing in, which obliges platforms to collect and transmit host registration data to member states. This is a genuine future engineering workload for the host-side platform.

None of this is heavy regulation in the engineering sense. There is no safety case, no formal certification regime (no ISO 26262, EN 50128, IEC 62304, BaFin/DORA), no documentation-driven release process. Deployment is continuous ("Ship improvements continuously - from idea to impact", "We build it, we run it, we own it").

**Verdict:** PASS (low regulatory burden)

---

## Section 10: On-Call

- The **(Senior) DevOps Engineer** posting explicitly asks for *"Experience with incident response, on-call rotations, or SRE practices (SLOs, error budgets)"*. That role clearly carries on-call.
- **No other Munich engineering posting mentions on-call, standby, Bereitschaft, or 24/7 availability.** The AI Engineer, Senior Software Engineer Revenue Management, Senior DataOps Engineer and Staff Data Engineer postings contain no such language.
- However, the engineering principle is *"We build it, we run it, we own it - we independently keep track of what we build, track results post-release, and improve where needed."* That is a you-run-your-own-service culture.
- **OpsGenie** (a paging and alert-routing product whose entire purpose is on-call schedules and escalation) appears in the monitoring stack of both the Revenue Management and Staff Data Engineer postings, alongside ELK and Grafana. Pipelines that page someone imply a rota.
- The Staff Data Engineer role explicitly includes owning SLAs and keeping "pipeline performance under continuous watch".
- No reviewer on either platform complains about on-call, night work, or weekend paging.

**Verdict:** **CAUTION (team-dependent).** DevOps is a definite yes. For the Python data-platform and Revenue Management roles it is not advertised, but the combination of OpsGenie in the stack, explicit SLA ownership, and a "you run it" principle makes some form of business-hours-plus rota likely. **This must be asked about directly in a first interview**, since it is not resolvable from public sources.

---

## Section 11: Interview Process

Retrieved from Glassdoor (166 interview reports, last updated 10 Aug 2026) via the authenticated session.

| Metric | Value |
|---|---|
| Difficulty | **2.87 / 5** (Glassdoor, "average") |
| Positive experience | **73.5%** (20% negative) |
| Average duration | **~20.7 days** (Glassdoor figure captured May 2026; not surfaced in today's scrape) |
| Rounds | **4 interview stages** for permanent engineering roles (5 steps including the offer) |
| Application route | 83% online application, 4% recruiter |

Glassdoor notes that **Software Engineer - Java Developer** and Accounts Manager candidates rated their interviews as the hardest, while Data Scientist and Frontend Intern candidates rated theirs as the easiest.

Against the May 2026 capture (69.4% positive, difficulty 2.69/5, ~20.7 days average), both the positive-experience rate and the rated difficulty have ticked up slightly. The process appears to be getting somewhat more rigorous without becoming less pleasant.

The process, per the company careers page and corroborated by a detailed Back End Developer interview report:

1. **Apply online**, receipt confirmed.
2. **HR screen** (remote, conversational): background, motivation, why Holidu, the project you are most proud of and one you are less proud of, plus behavioural questions mapped to the company values. The recruiter walks through the company, role, and full process. Reported as "warm, engaging, and welcoming".
3. **Deep-dive with two senior engineers** (remote): the proud project revisited technically, impact in prior projects, level of ownership, collaboration style, involvement across a project lifecycle. Reported as patient, clear, and comfortable.
4. **Technical interview**: **live coding / pair programming** on a problem, followed by backend technical questions. For some roles this stage is a **prepared presentation or a take-home task**, sometimes assigned on the spot.
5. **Team fit conversation** ("more like a coffee chat"), remote or onsite.
6. **Offer.**

**Character:** this is **experience-and-design-focused, not LeetCode-heavy.** Two of the four stages are pure experience and ownership discussions; only one is live coding, and it is described as pair programming on a problem rather than algorithm drilling. Behavioural questions mapped explicitly to company values ("situations in which you have acted according to our company values") are a stated part of stage 2, so value-mapped STAR answers matter here more than at a typical algorithm-first company.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | **PASS.** Own marketplace plus proprietary PMS, ~170-200 engineers, no client billing. |
| Not consulting | **PASS.** No consulting model, no client deliverables, no consultant titles. |
| Profitable | **BORDERLINE.** Claims EBIT-positive since 2020 and revenue grew ~41% to ~$144.7M in FY2024, but raised ~EUR 46M in 2025 and 2026 reviewers describe an active "push for profitability". |
| Employee count | ~700 globally per the company (third parties cite up to ~792); ~170-200 in engineering, Munich-headquartered. Trend is flat to slightly down. |
| English-speaking | **PASS.** All engineering postings in English, 40+ nationalities in tech, no German requirement. |
| Local entity + engineering contracts | **PASS.** Holidu GmbH, HRB 213215 München, direct German employment, R&D tax credits confirm in-house engineering. |
| Location / work model | Riesstraße 24 (Moosach). Hybrid 50% in-office. No fully-remote Munich engineering roles. |
| Glassdoor | **PASS.** 4.6 global (149 reviews), 95% recommend, 99% CEO approval. But zero Software Engineer reviews and no Munich-filtered data. |
| Kununu | **PASS.** 4.1 (242 reviews, 153 employee), 82% recommendation, no Top Company seal. Nominally down from 4.3 in May 2026, but Glassdoor rose 0.2 over the same window on a similarly tiny new-review count; both deltas are recency-weighting noise. |
| Salary | **FAIL.** Senior SWE observed at EUR 77K-87K base, no stock, no bonus. Below the Munich market for the level and below large profitable Munich employers. Lowest-rated category on both review platforms. |
| AI/ML content | **PASS.** Production agentic LLM systems (MCP, multi-agent, evals) under the CTO, plus dynamic pricing and rankings ML on MLflow/SageMaker, plus internal HoliduGPT and org-wide AI tooling. |
| Computer-language/Tech-stack | **SPLIT PASS.** Product backend and the agentic-AI team are Kotlin/Java. The data platform, MLOps and Revenue Management side is explicitly **Python-first** and hiring at Senior and Staff. |
| No on-call | **CAUTION.** Only DevOps advertises on-call, but OpsGenie in the stack, SLA ownership, and a "we run it" principle suggest a rota exists. Must be asked. |
| WLB / Stability | **CAUTION.** WLB scores strong (4.5-4.6) and hybrid protected, but 2026 reviews report rising workload, more office days, and turnover driven by the profitability push. |
| Regulated industry | **PASS.** GDPR, DSA and the EU short-term-rental regulation only. No safety case, no certification regime, continuous deployment. |
| Review themes | Outstanding team cohesion and learning culture; consistent, specific, cross-platform complaints about pay, pay-band opacity, top-down communication, and shipping half-finished product. |
| **Equity liquidity** | **CAUTION.** Private, pre-IPO, sixth-plus financing round, six share-capital increases since 2022. levels.fyi records EUR 0 stock in every submission; a Senior PM cites "no clear strategy of stocks buybacks". |
| **Acquisition / consolidation activity** | Acquired Cybevasion (2025), holds Spain Holiday Online Rentals SL and September 2022 ApS; two M&A roles open in Munich. Active consolidator, which also makes it a plausible target. |
| **Engineer-specific review evidence** | **UNVERIFIED.** Zero Software Engineer reviews on Glassdoor, no technical salary entries on Kununu, no Teamblind page. The strong culture scores are drawn overwhelmingly from non-engineering staff. |

---

## Section 13: Verdict

**Recommendation: Monitor.** This is a genuine upgrade from the previous evaluation, which concluded "do not pursue" partly on grounds that no longer hold.

**Strengths.** Holidu is a real product company with a proven, revenue-generating two-sided marketplace, a clean German GmbH employing engineers directly, an English-first international engineering org, and a hybrid 50% cadence. The culture evidence is genuinely strong and specific rather than generic: 4.6 on Glassdoor with 95% recommending and 99% CEO approval, team cohesion as the single most praised attribute on Kununu, a real learning budget and dedicated study days, and no evidence at all of toxic leadership, surveillance, or always-on expectations. The interview process is experience-and-design-led rather than LeetCode-driven, which suits a 20-year engineering background. And crucially, the technical fit has changed: there is now a Python-first data platform.

**Hard blockers (numbered):**

1. **Compensation.** Every observable Senior Software Engineer data point at Holidu is base-only in the **EUR 77K-87K** range, with **EUR 0 stock and EUR 0 bonus** in every levels.fyi submission. That is below the Munich market median for a Senior engineer and well below what large, profitable Munich employers pay at Senior, let alone at Staff. This is corroborated five ways independently: levels.fyi submissions, Glassdoor's lowest category score (Comp & Benefits 4.1), Kununu's lowest factor (Gehalt/Benefits 3.5), Glassdoor's own AI pay summary ("salaries are generally low, especially for roles in Munich"), and multiple 2026 free-text reviews. Two of those reviews add a compounding detail: salary bands are undisclosed, new hires are reportedly brought in ~EUR 15K above incumbents in the same role, and the only raise mechanism is the annual performance review. A strong negotiated entry offer might be achievable; keeping pace with the market afterwards looks unlikely.

**Secondary concerns:**

- **Remote-Germany roles have disappeared.** Five were open in May 2026; today the portal offers remote positions only in Italy, and every German role is tied to an office. With "more office days" also appearing as a 2026 reviewer complaint, the hybrid 50% arrangement should be treated as a floor that may tighten, not a ceiling.
- **The profitability squeeze is being felt.** June 2026: *"the current push for profitability is putting significant pressure on employees, with many teams already feeling overworked and stretched to their limits... more office days, reduced bonus opportunities, and increasing workloads are likely continuing to drive higher employee turnover."* Combined with headcount that has drifted from ~816 to ~700 in six months while the company describes itself as scaling, this reads as a company tightening, not expanding.
- **No engineer-specific review evidence exists anywhere.** Zero Software Engineer reviews on Glassdoor, zero technical salary entries on Kununu, no Teamblind page. The excellent culture scores come overwhelmingly from Sales, Account Management and Support, and so do the worst complaints. What engineering life is actually like at Holidu is effectively unmeasured.
- **Communication from the top is a repeated 2026 theme**, as is releasing products "before they're fully developed which causes so so so much work" - the one negative with direct engineering relevance.
- **Equity is illiquid and possibly absent.** Private, pre-IPO, sixth-plus round, six share-capital increases since 2022 (steady dilution), EUR 0 stock recorded in every salary submission, and a Senior PM publicly citing the lack of a buyback strategy.
- **On-call is unresolved.** Not advertised for the Python roles, but OpsGenie sits in their monitoring stack alongside explicit SLA ownership and a "we build it, we run it, we own it" principle.
- **Stability is scale-up stability, not corporate stability.** The business is not at solvency risk (multi-year runway even under stress), but this is a company still consolidating via M&A, still raising, and still transitioning its cost base. That is a different proposition from a mature, settled employer.

**Recommendation.** Do not rule Holidu out, as the previous evaluation did. The Python and AI/ML blockers are genuinely gone. But do not apply on the posted terms either: the compensation evidence is unusually consistent and the pay-band opacity means the gap is structural rather than negotiable after entry. Three things would move this to an active pursue: a Senior/Staff offer at or above the Munich market median, a clear answer that the Python platform roles carry no out-of-hours rota, and a Kununu score that stabilises rather than continuing to slide. Three things to verify during interviews regardless: the on-call arrangement for the specific team, whether equity is offered at all at Staff level and what the liquidity path is, and how the "50%+ in-office" wording in the Staff Data Engineer posting differs in practice from the flat 50% in the other postings.

---

## Sources

- [Holidu Careers - overview](https://www.holidu.com/careers)
- [Holidu Careers - Tech](https://www.holidu.com/careers/tech)
- [Holidu Careers - open positions, Munich](https://www.holidu.com/careers/list?location=Munich%2C%20Germany)
- [Senior AI Engineer - Agentic Experience (Munich)](https://www.holidu.com/careers/senior-ai-engineer-agentic-experience-all-genders)
- [AI Engineer - Agentic Experience (Munich)](https://www.holidu.com/careers/ai-engineer-agentic-experience-all-genders)
- [Senior Software Engineer - Revenue Management (Munich)](https://www.holidu.com/careers/senior-software-engineer-revenue-management-all-genders)
- [Senior DataOps Engineer / Software Engineer - Revenue Management (Munich)](https://www.holidu.com/careers/senior-dataops-engineer-software-engineer-revenue-management-all-genders)
- [Staff Data Engineer (Munich)](https://www.holidu.com/careers/staff-data-engineer-all-genders)
- [(Senior) DevOps Engineer (Munich)](https://www.holidu.com/careers/senior-devops-engineer-all-genders)
- [Senior Data Scientist - Dynamic Pricing & Revenue Management](https://www.holidu.com/careers/senior-data-scientist-dynamic-pricing-revenue-management-all-genders)
- [Senior Data Scientist - Rankings & Recommendations](https://www.holidu.com/careers/senior-data-scientist-rankings-recommendations-all-genders)
- [Staff Data Scientist (Munich)](https://www.holidu.com/careers/staff-data-scientist-all-genders)
- [Holidu Imprint (Impressum)](https://www.holidu.com/imprint)
- [Holidu Tech Blog](https://medium.com/@holidu)
- [Senior AI Product Engineer - Agentic Experience (closed, Northzone board)](https://opportunities.northzone.com/companies/holidu/jobs/73296286-senior-ai-product-engineer-agentic-experience-cto-team)
- [Senior Backend Developer (Northzone board)](https://opportunities.northzone.com/companies/holidu/jobs/71864191-senior-backend-developer-all-genders)
- [NorthData - Holidu GmbH, HRB 213215](https://www.northdata.de/Holidu+GmbH,+M%C3%BCnchen/HRB+213215)
- [Glassdoor - Holidu reviews (global)](https://www.glassdoor.com/Reviews/Holidu-Reviews-E1460824.htm)
- [Glassdoor - Holidu overview](https://www.glassdoor.com/Overview/Working-at-Holidu-EI_IE1460824.11,17.htm)
- [Glassdoor - Holidu interview questions](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/Holidu-Fragen-im-Vorstellungsgespr%C3%A4ch-E1460824.htm)
- [Glassdoor - Holidu pay & benefits](https://www.glassdoor.com/Salary/Holidu-Salaries-E1460824.htm)
- [Kununu - Holidu GmbH](https://www.kununu.com/de/holidu1)
- [levels.fyi - Holidu salaries](https://www.levels.fyi/companies/holidu/salaries)
- [levels.fyi - Holidu Software Engineer salaries](https://www.levels.fyi/companies/holidu/salaries/software-engineer)
- [Teamblind - Holidu (no page exists)](https://www.teamblind.com/company/Holidu)
- [Great Place to Work Germany - company directory](https://www.greatplacetowork.de/great/company)
- [PitchBook - Holidu company profile](https://pitchbook.com/profiles/company/101789-02)
- [Crunchbase - Holidu 2025 funding round](https://www.crunchbase.com/funding_round/holidu-series-unknown--53cacdf9)
- [Tracxn - Holidu funding rounds and investors](https://tracxn.com/d/companies/holidu/__eDS6HwRXHZi7kJPFRQ8jW0ITCUcZFKVan5H_w8TBjy4/funding-and-investors)
- [CB Insights - Holidu](https://www.cbinsights.com/company/holidu)
- [Dealroom - Holidu](https://app.dealroom.co/companies/holidu)
- [Seedtable - Holidu](https://www.seedtable.com/startups/holidu)
- [GetLatka - Holidu revenue](https://getlatka.com/companies/holidu)
- [TechCrunch - Holidu Series E (Oct 2022)](https://www.techcrunch.com/2022/10/19/holidu-series-e)
- [Silicon Canals - Holidu profitable in the pandemic, raises from Kees Koolen](https://siliconcanals.com/holidu-profitable-pandemic-raises-funding-kees-koolen/)
- [Holidu Magazine - Kees Koolen investment](https://www.holidu.com/magazine/kees-koolen-holidu-investment)
- [Holidu Magazine - Series D financing round](https://www.holidu.com/magazine/holidu-series-d-financing-round)
- [FinSMEs - Holidu raises over $4M from Kees Koolen](https://www.finsmes.com/2020/09/holidu-raises-over-4m-from-kees-koolen.html)
- [OpenStreetMap Overpass API (last-mile stop verification)](https://overpass-api.de/api/interpreter)
