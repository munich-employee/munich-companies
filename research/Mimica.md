# Mimica - Full Research Report

_Researched: 2026-11-11_

> **Critical Disqualifiers**
>
> 1. **No German entity:** Mimica's only operating company we could find is Mimica Automation Limited in London (Companies House 11153050). NorthData and the German registers show no German GmbH or branch. The roles are open to applicants in Germany only as "fully remote", so a Munich hire would be employed through an employer of record (EOR) or as a contractor, not on a direct German contract.
> 2. **Short financial runway on filed figures:** at 31 Dec 2025 the company had **£9.34M cash**. The loss for 2025 was about **£10.0M**, worked out from the change in accumulated losses (from £10.1M to £20.1M). If that burn rate continued, the Sep 2025 Series B would run out around Q4 2026, which is now. The 2026 share allotments filed so far add less than 1% to share capital, so they are not a new priced round. No new funding has been announced.
> 3. **No local work arrangement in Munich:** there is no office in Munich or Germany. Mimica is remote-first, and its stated hubs are not named anywhere public.
>
> The full report follows anyway for completeness.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 2018 (8 years). Mimica Automation Limited was incorporated on 16 Jan 2018 (Companies House 11153050) and came out of the Entrepreneur First programme in London |
| Employees | **~320 associated members on LinkedIn** (company band 201-500). Of these, **146 work in "Operations" and 158 are in Costa Rica**; engineering is 61 and sales 38. Glassdoor's band is 51-200. Job postings describe "a 50+ person team of Senior+ engineers and Product leaders" in "8 cross-functional teams", spread across 16+ countries. The UK entity's average headcount for FY2025 was only **15** (2024: 11), so most staff are employed outside the UK company |
| Revenue (FY2025) | **Not disclosed.** The UK accounts are filleted small-company accounts with no P&L. Company claim (Sep 2025): **ARR +570% in 18 months, 30+ large enterprise customers** "including multiple Fortune 500s". Latka estimated a run rate of **$3.3M for 2023/2024**. Trade debtors were £2.67M at 31 Dec 2025 (2024: £1.04M) |
| Profitability | Loss-making. Accumulated losses went from £5.61M (2023) to £10.12M (2024) to **£20.09M (2025)**, which implies a net loss of **~£4.5M in 2024 and ~£10.0M in 2025**. **FAIL** |
| Ownership | Private and VC-backed. Investors are Paladin Capital Group (Series B lead), Khosla Ventures (Series A lead), LGVP, Entrepreneur First and Episode 1 Ventures. The PSC register states there is **no registrable person with significant control**, so no single holder has more than 25% |
| Software-centric | An enterprise SaaS product (task mining and process intelligence, plus a new agent-generation product). About half the headcount is a Costa Rican operations team that checks the ML output by hand before it is released to customers. **PASS with caution** (see the Consulting-Adjacency Assessment) |

### Key People

- **Tuhin Chakraborty** - co-founder and CEO, director since Jun 2018 (Companies House: American national, also company secretary). Drives go-to-market. The FY2025 accounts show the company **owed him £1,126,704** at year-end (interest-free, no set repayment terms; in 2024 he owed the company £5,356). The accounts do not explain the reason.
- **Dr Raphael Holca-Lamarre** - co-founder and CTO. PhD in Neuroscience and Machine Learning; leads the technology roadmap, signed the FY2025 accounts, and runs the final interview round.
- **Nazo Moosa** - Managing Director at Paladin Capital Group, on the board since 1 Jul 2025 (Series B).
- Past directors: Damien Lane (Episode 1 Ventures, 2018-2021) and Eitai Tsiddon (Feb 2024 - Apr 2025).

### Funding History

| Date | Round | Amount | Valuation | Notes |
|---|---|---|---|---|
| Mar 2018 | Pre-seed / seed | n/d | n/d | Entrepreneur First (CB Insights lists this as "Seed VC") |
| Sep 2019 | Seed (company timeline) / "Series A" (CB Insights) | n/d | n/d | Episode 1 Ventures |
| Nov 2021 | Series A | ~$6M (reported) | n/d | Khosla Ventures led |
| Dec 2024 | Convertible loan | £795K | - | Converted into equity during 2025 (FY2025 note 11) |
| 24 Sep 2025 | Series B | **$26.2M (£19.5M)** | n/d | Paladin Capital Group led, with Khosla Ventures, LGVP and Entrepreneur First. Share premium went from £8.9M to £26.1M in FY2025 |
| Feb - Jun 2026 | Small allotments (five SH01 filings) | Share capital went from ~£165.72 to £165.88 nominal | - | An increase of under 0.6%, consistent with option exercises, not a priced round |

**Total raised:** $36.7M over 7 rounds (CB Insights).

### Business Model

Mimica sells three products to large enterprises:
- **Miner:** task mining. A desktop recorder for Windows and macOS captures employees' clicks and keystrokes. ML then turns them into process maps and ranks automation opportunities by ROI.
- **Mapper:** process maps produced from that data.
- **Maker:** a newer product for "generating the AI agents to execute" the processes it has mapped. Postings say it is being built from scratch.

Mimica's Series B pitch presents its captured workflow data as "the playbook for training effective, context-aware, and compliant AI agents". It sells through partnerships with UiPath and the SAP Store, and has been named Everest Group Leader in Task Mining in 2023, 2024 and 2025. Revenue is recognised on a "rendering of services ... by reference to the stage of completion of the contract" basis (FY2025 note 2.3). This points to project-style enterprise engagements, not pure self-serve subscriptions.

### Consulting-Adjacency Assessment

- **Self-identification:** a product company ("AI-powered process intelligence platform"). It does not describe itself as a consultancy.
- **Billing:** no evidence that engineers bill hours. Mimica positions itself as removing the need for "internal analysts or consultants".
- **Human-in-the-loop delivery:** the **Process Analyst** team (about 146 Operations staff, mostly in Costa Rica) "validate[s] the output of our ML-powered tools", assesses "each map's quality and readiness for release using checklists" and collaborates "with internal and external stakeholders" (Process Analyst posting, Costa Rica). A large part of what the customer receives therefore passes through manual review. There are also customer-engineering roles: Value Engineers and a "Forward Deployed Engineer, Intelligent Automation" who builds client automations (agents, RPA bots, custom Python services) on GCP.
- **Engineering roles in scope:** the Staff Python, Backend and Frontend roles are in product teams (the Maker team, the Data Intelligence team and a Platform team). They build the platform, not client deliverables.
- **Conclusion:** not consulting for the engineering roles in scope. However, the company combines software with a large manual delivery operation, and its gross margins will look less like pure SaaS than its marketing suggests.

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **Mimica Automation Limited** (UK, the only operating entity found) | Companies House **11153050**, incorporated 16 Jan 2018 | 9th Floor, 107 Cheapside, London EC2V 6DN | SIC 62012, "Business and domestic software development" |
| German entity | **NONE FOUND** | - | - |

**Verification:**
- **NorthData** (searched "Mimica" and "Mimica Automation"): the only matches are the London company and an unrelated SIA Mimica in Riga.
- **handelsregister.ai:** no match. **Kununu:** no employer profile.
- **Imprint:** the website footer names only "Mimica Automation Ltd, 107 Cheapside, London". There is no German Impressum.
- **Other "Mimica" companies on Companies House:** Mimica Lab Ltd (10724944, Newmarket, natural-sciences R&D: the food-freshness indicator company) and Mimica Limited (04391266, in liquidation) are unrelated.

**Employment in Germany:**
- The Staff/Senior Backend Engineer (Node.js) posting lists "Germany" as an eligible location, and the Staff/Lead Python Engineer posting lists "Berlin". Both are "fully remote".
- Postings add that "some benefits may vary depending on location".
- The UK entity's average headcount (15) is far below the ~320 people on LinkedIn, so staff outside the UK must be employed through other entities, EORs or contractor agreements. Mimica does not name its EOR provider publicly.

A hire in Munich would not have a direct German employment contract. This means no German works council could apply, and any stock options would come from a UK company held through an EOR (watch the German tax treatment).

**Verdict:** **FAIL** (no German entity; employment would be via EOR or contractor).

---

## Section 3: Office Location

- **Office address:** no Munich or German office. The only address the company publishes is **9th Floor, 107 Cheapside, St Paul's, City of London EC2V 6DN** (website footer, Companies House). The building is a commercial building (Nominatim). Whether Mimica uses it as a working office or only as a registered address is unverified. The careers page shows offsites (Bilbao, Heredia in Costa Rica, Miami, New York QBR) but no permanent offices. The Costa Rica team works around San José, Heredia, Alajuela and Cartago, and some team-lead postings there are marked "In-Office".
- **Nearest public transport (London address, via Nominatim and Overpass):**
  - St. Paul's (Central line), ~290 m
  - Mansion House (District, Circle), ~295 m
  - Bank (Northern, Central, Waterloo & City, DLR), ~320 m
  - Cannon Street (District, Circle, plus National Rail), ~390-450 m
- **Work model:** **fully remote**, with "Work from anywhere - fully remote, in our hubs, or a mix", a co-working budget, a remote setup stipend, and "annual workaways". Location limits vary by role:
  - Staff/Lead Python Engineer: UK, Europe or the Americas, **UTC-7 to UTC+3**.
  - Staff/Senior Backend (Node.js): **UTC-6 to UTC+1**. Munich is UTC+2 in summer, so it sits at the edge of this window.
  - Senior/Lead ML Engineer: UK or Europe, UTC-1 to UTC+3.
  - Some postings ask Americas-based candidates to be on US Eastern time, which implies significant overlap with US-based colleagues.

---

## Section 4: Reviews

**GPTW:** no Great Place to Work certification found for Mimica in Germany, the UK or anywhere else. The only search hit was an unrelated "MICA".

#### Glassdoor

Glassdoor has **two profiles** for this company, and both hold reviews from Mimica staff:
- **"Mimica (United Kingdom)" (E6316961):** 10 reviews, an active-employer profile, and the main one.
- **"Mimica" (E6034363):** 4 reviews, mostly US sales staff. Its salary tab mixes in submissions that look like they belong to the unrelated food-indicator company Mimica Lab (Founder, Manufacturing Engineer, Product Designer).

Neither profile has any review from Germany or Munich. Both profiles were read via Chromium/CDP because the Glassdoor UI defaults to German reviews only; `filter.iso3Language=eng` was needed on glassdoor.co.uk.

| Metric | Global (E6316961) | Global (E6034363) | Germany | Munich | Software Engineers |
|---|---|---|---|---|---|
| **Overall** | 4.9 (10 reviews) | 3.5 (4 reviews) | n/a (0) | n/a (0) | 4.5 (2 reviews: 4.0, 5.0) |
| **WLB** | 4.7 | 4.2 | - | - | - |
| **Culture & Values** | 4.9 | 4.0 | - | - | - |
| **Comp & Benefits** | 4.6 | 3.9 | - | - | - |
| **Career Opportunities** | 4.6 | 3.5 | - | - | - |
| **Diversity & Inclusion** | 4.9 | 4.2 | - | - | - |
| **Senior Management** | 4.9 | 4.0 | - | - | - |
| **% Recommend** | 100% | 81% | - | - | - |
| **CEO Approval** | 100% | n/d | - | - | - |
| **Business Outlook** | 100% positive | 57% positive | - | - | - |

All filters have far fewer than 20 reviews, so these scores are **directional only**. The headline 4.9 on E6316961 has not caught up with recent reviews: the two most recent (Nov 2026) are rated 3.0 and 4.0. Most of the five-star reviews from 2022-2025 come from sales and business-development staff.

#### Kununu

- **Overall score:** n/a
- **Recommendation rate:** n/a
- **Total reviews:** 0
- **Kununu Top Company:** NO

Every slug tried (`mimica`, `mimica-automation`, `mimica-automation-ltd`, `mimica1`) returned HTTP 405 via curl. The Kununu search via CDP returned only Mimecast Germany GmbH. This is expected, since Mimica has no German entity.

#### Blind / Teamblind

No company page exists (teamblind.com/company/Mimica returns "Page not found"). **No data.**

#### Review Themes (2022-2026)

**Positives:**
- **Fully remote and flexible:**
  - "This place used to be great, amazing values and it's fully remote" (Glassdoor, Nov 2026, Anonymous employee, current employee, more than 1 year).
  - "Remote / Flexible / Slow paced / Nice environment" (Glassdoor, May 2026, Process analyst, current employee, more than 1 year, Cartago).
- **Interesting technical problems:**
  - "Good company, Challenging projects, Ambitious team" (Glassdoor, Oct 2025, Senior software engineer, current employee, more than 1 year, London).
  - "Exciting technology, Fast-moving, Flexible schedule, Friendly atmosphere" (Glassdoor, Jan 2026, Engineer, current employee).
- **Open, approachable founders:**
  - "Tuhin and Raphael (our co-founders) are humble and down to earth" (Glassdoor, Mar 2025, Sales enablement lead, current employee, less than 1 year, Pittsburgh, PA).
  - "Supportive leadership. Open about our challenges" (Glassdoor, Jul 2025, Anonymous employee, current employee, more than 1 year).
- **Results-based, not presence-based:** "Mimica is a results based company. No one's monitoring our desktops to ensure we're online for 8 hours a day" (Glassdoor, Mar 2025, Sales enablement lead, Pittsburgh, PA).
- **Wellbeing benefits:** "Healthy and inclusive culture (offers therapy service, unlimited & self-managed holidays, cycling scheme)" (Glassdoor, Jun 2024, Communications manager, current employee, more than 1 year, London).

**Negatives:**
- **Recent management drift and doubts about the future:** "Absolutely no growth opportunities and on the recent months management is super contradictory, honestly I don't see a positive outcome on the near future I think they are going to start to fall" (Glassdoor, Nov 2026, Anonymous employee, current employee, more than 1 year). This is the most recent review and lines up with the runway concern in Section 8.
- **Unstable engineering team and micromanagement:** "A bit of micromanagement, the comp is okay, but not that great. Team composition is quite shaky and unstable, lots of legacy stuff although things are changing" (Glassdoor, Oct 2025, Senior software engineer, current employee, more than 1 year, London). This is the only detailed engineering review.
- **Redundancies alongside hiring:** "It's never a guarantee that your position is safe. Unfortunately, had experiences redundancies as well as new hires within 1.5 years of working here" (Glassdoor, Jun 2024, Communications manager, London).
- **Missing processes:**
  - "We lack processes for rather basic needs" (Glassdoor, Jul 2025, Anonymous employee).
  - "Early stage, processes are still being defined" (Glassdoor, Nov 2026, Bdr, former employee, more than 1 year).
- **Limited internal mobility:** "Growth is slow as not many positions are open" (Glassdoor, May 2026, Process analyst, Cartago).
- **Older criticism of how people are treated:** "Chaotic and don't treat people as well as they say" (Glassdoor, Aug 2022, Associate, former employee, more than 1 year, London).
- **Candidate experience:** see Section 11 (0% positive interview experience).

Overlap with red flags: silent firings and layoffs (the 2024 redundancies), communication breakdown ("management is super contradictory") and micromanagement. Each comes from a single reviewer.

#### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | No direct evidence. Founders are described positively by sales staff from 2022-2025. The one 2022 negative ("don't treat people as well as they say", Associate, London) is old |
| 24/7 Work Expectation | Not reported. Some reviewers mention hard work ("We work hard, but also get rewarded appropriately", Jul 2025). The workforce spans UTC-7 to UTC+3, which can push meetings into European evenings for roles that overlap with US Eastern time |
| Internal Surveillance | Not reported internally ("No one's monitoring our desktops", Mar 2025). Note that the *product* is desktop activity recording at customers. That is a feature of the product, not of how Mimica manages its own staff |
| Fear-driven Management | "It's never a guarantee that your position is safe" (Communications manager, Jun 2024). One signal |
| Communication Breakdown | "On the recent months management is super contradictory" (Anonymous, Nov 2026). Recent and from a current employee |
| Unpaid Overtime | Not reported |
| Silent Firings | Redundancies "as well as new hires within 1.5 years" (Jun 2024). Not publicly reported as layoffs. "Team composition is quite shaky and unstable" (Senior SWE, Oct 2025) |
| Work-Life Balance issues | WLB scores 4.7 / 4.2 and remote flexibility is praised. No WLB complaints |

**Risk level: MODERATE.** There is no evidence of systemic toxicity, and the culture as described is remote, flexible and founder-friendly. However, the review base is tiny (14 reviews, only 2 from engineers) and skewed toward sales, and the newest signals are negative: contradictory management, an unstable engineering team, and earlier redundancies. Taken together with the runway in Section 8, this looks like the kind of dysfunction a stretched startup develops, not a toxic culture.

---

## Section 5: Compensation

#### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| Glassdoor (E6316961, London) | Senior Software Engineer | ~€117-118K (£100-101K) | n/d (options) | n/d | ~€117-118K | 2 |
| Glassdoor (E6316961, London) | Lead Software Engineer | ~€145-158K (£124-135K) | n/d | n/d | ~€145-158K | 1 |
| Glassdoor (E6316961, London) | Lead ML Engineer | ~€113-118K (£97-101K) | n/d | n/d | ~€113-118K | 2 |
| Glassdoor (E6316961, London) | ML Engineer | ~€88-95K (£75-81K) | n/d | n/d | ~€88-95K | 1 |
| levels.fyi | - | - | - | - | - | 0 (no company page: `/companies/mimica` and `/companies/mimica-automation` return 404) |
| Job postings (Ashby, 17 open roles) | All | not disclosed | "stock options" | - | - | 0 |

Conversion: £1 ≈ €1.17. All salary data points are London-based. **No data points exist for Germany or Munich.**

The postings say pay is "aligned with our internal framework, market data, and individual skills". This suggests location-based pay, so London figures may not carry over to Germany. One engineer reviewer said "the comp is okay, but not that great" (Glassdoor, Oct 2025, Senior software engineer, London).

**Munich reference** (levels.fyi Germany, from earlier reports in this project):
- Senior SWE median ~€81.5K total comp.
- 75th percentile ~€96K; 90th percentile ~€115K.
- Large profitable Munich employers pay ~€85-110K base, with the 90th percentile at €120K+.

#### Equity / Stock

The offer includes stock options in Mimica Automation Limited (a private UK company). Grant sizes, vesting and strike prices are not public.

Liquidity risk is high:
- The company is Series B and loss-making, and runway is short (Section 8).
- The 2026 share allotments are tiny, so there is no recent priced round to anchor a valuation.
- For a German resident employed through an EOR, options in a UK company are generally taxed in Germany as income when exercised. EMI tax advantages apply only to UK employees.

#### Verdict

**UNVERIFIED.** The London data points (Senior ~€117K, Lead/Staff ~€145-158K) would be **ABOVE** the Munich bracket if paid in Germany. However, there are no German data points, pay is location-banded, and the EOR route adds employer overhead that often comes out of the salary offered.

---

## Section 6: AI/ML & Tech Stack

#### AI Strategy

The AI work is genuine and central to the product:
- **Proprietary models:** "We started building proprietary ML before the LLM boom, so we don't just consume models - we train them from the ground up" (engineering postings). The CTO has a PhD in ML.
- **Data Intelligence team:** turns raw click/keystroke/screen recordings into "clean, structured, anonymized data", using:
  - LLM-heavy pipelines, LLM evals and **LLM-as-a-judge** systems;
  - OCR and image pipelines;
  - face-related **anonymisation** models;
  - fine-tuning open-source models and replacing LLM calls with smaller, task-specific models (Senior/Lead ML Engineer posting).
- **Maker team:** a new "automation engine" that generates AI agents from the process maps it has mined, being built "from scratch" (Staff/Lead Python Engineer posting).
- **Customer engineering:** Forward Deployed Engineers build client agents and automations on **Vertex AI**, with MCP servers and RPA.
- **AI infrastructure:** owned by the Platform team, covering "training and serving infra, MLOps tooling, Vertex and model access", the "infra and LLM budget", and GPU workloads on Kubernetes (Head of Platform posting).

#### Tech Stack

Sources: Mimica's Ashby job board (17 postings as of 2026-11-11: Staff/Lead Python, Staff/Senior Backend Node.js, Staff/Lead Frontend, Staff/Lead Fullstack, Head of Platform, Senior/Lead ML Engineer, Forward Deployed Engineer), plus older postings syndicated on startup.jobs, builtin.com and bulldogjob.pl (Staff/Lead Platform DevOps, Staff/Lead Python ML Platform & Ops, Staff/Lead Backend FastAPI). No engineering blog, public GitHub organisation or conference talks were found.

| Category | Technologies |
|---|---|
| **Primary language(s)** | **Python** (FastAPI, async/concurrent services, a "Python Chapter") for ML-facing backends and data pipelines. **TypeScript/Node.js** for the web-app backend ("MERN stack"). **React** for the frontend |
| **AI/ML** | Proprietary ML models, LLM APIs, LLM evals / LLM-as-a-judge, fine-tuned open-source models, OCR and image anonymisation, Vertex AI, GPU workloads on Kubernetes |
| **Cloud** | **GCP** (GKE, Vertex AI, Cloud Run, Cloud Functions, BigQuery, Pub/Sub). EKS is mentioned as acceptable experience; multi-region expansion and an installable on-prem component for enterprise are planned |
| **Infrastructure** | Kubernetes (GKE), Terraform, ArgoCD, Crossplane, Docker, Temporal (workflow orchestration, older posting) |
| **Data** | MongoDB, PostgreSQL, BigQuery, Pub/Sub |
| **Other** | Observability with Grafana stack (Prometheus, Loki, Tempo, Alloy) and Honeycomb. Desktop recorder for Windows and macOS (implementation language not disclosed). Integrations with Google services, ERPs/CRMs, UiPath and SAP |

**Summary:** Polyglot. Python carries the ML-facing services, data pipelines and the new agent engine (FastAPI, async), while a TypeScript/Node.js MERN application with MongoDB/PostgreSQL drives the main web product. The work runs on GCP (GKE, Vertex AI, BigQuery) with Terraform/ArgoCD. It is applied, production ML/LLM engineering (proprietary models, LLM evals, anonymisation, agent generation) in an enterprise SaaS setting, not research.

---

## Section 7: Language

- All postings are in English. Each requires "Fluency in English", and none mentions German or any other language.
- The team is distributed across 16+ countries (UK, EU, Americas, Costa Rica), so English is necessarily the working language.

**Verdict:** **PASS**

---

## Section 8: Stability

#### Financial Position

Figures are from Mimica Automation Limited's filleted small-company accounts (FRS 102 1A, unaudited, no P&L filed). FY2025 accounts were signed 09/09/2026; FY2024 accounts are also on Companies House.

| Item | 31 Dec 2023 | 31 Dec 2024 | 31 Dec 2025 |
|---|---|---|---|
| Cash at bank | n/d | £0.76M | **£9.34M** |
| Trade debtors | n/d | £1.04M | £2.67M |
| Other debtors | n/d | £0.14M | £1.50M |
| Creditors due < 1 year | £0.93M | £2.49M | **£7.63M** (of which "other creditors" £7.31M) |
| Convertible loan | - | £0.76M | converted |
| Share premium | £5.69M | £8.88M | £26.09M |
| Accumulated losses | £5.61M | £10.12M | **£20.09M** |
| Net assets | £0.08M | -£1.21M | £5.99M |
| Implied net loss for the year | - | ~£4.5M | **~£10.0M** |
| Average employees (UK entity) | 11 | 11 | 15 |

Notes:
- The directors report no material uncertainty about going concern.
- The jump in "other creditors" to £7.31M most likely includes deferred revenue and accruals. It also includes the **£1.13M owed to the CEO**.
- The accounts cover only the UK company. Costs of staff employed elsewhere (US, Costa Rica, EOR) presumably run through it via recharges, but this is unverified.
- The loss more than doubled in 2025 while trade debtors grew 2.6x. That fits the claimed fast ARR growth, but costs grew faster.

#### Financial Runway

**Search results:**
- No runway estimates or burn commentary in the press.
- The Series B press release (Sep 2025) says the money will go to "turning captured workflows into the training substrate for agentic AI". It gives no runway figure.
- No funding round in 2026 has been announced. The five SH01 filings (Feb-Jun 2026) raise nominal share capital from ~£165.72 to £165.88 (<0.6%), which is not a priced round.

**Bottom-up model (group-wide, annual):**

| Cost line | Annual estimate |
|---|---|
| Costa Rica operations (~150 process analysts and leads × ~€35K loaded) | ~€5.3M |
| US sales, BD, solutions and value engineering (~60 × ~€170K loaded incl. commission) | ~€10.2M |
| Engineering, ML, product, platform in UK/EU (~60 × ~€130K loaded incl. EOR fees) | ~€7.8M |
| G&A, marketing, people, security (~20 × ~€100K) | ~€2.0M |
| Cloud, GPU and LLM spend | ~€2.0M |
| Offsites, travel, tools, partner/marketing programmes | ~€1.5M |
| **Total gross burn** | **~€28.8M/year** |

| Revenue source | Est. annual inflow |
|---|---|
| Subscription and services revenue. Latka's ~$3.3M run rate ×6.7 (the claimed +570% over 18 months) gives ~$22M ARR by Sep 2025. Trade debtors of £2.7M are consistent with ~€15-20M billed per year | ~€17M/year |
| **Total revenue offset** | **~€17M/year** |

This gives a net burn of ~€12M/year, which matches the ~£10.0M (~€11.7M) loss in the filed accounts.

| Scenario | Net burn | Cash at hand | Runway (from 1 Jan 2026) | Next round needed by |
|---|---|---|---|---|
| Optimistic (revenue grows ~50% in 2026, hiring frozen) | ~€6M/year | €10.9M (£9.34M) | ~1.8 years | ~Q3-Q4 2027 |
| Base case (2025 loss repeats) | ~€11.7M/year | €10.9M | ~11 months | **~Q4 2026 (now)** |
| Stress (hiring continues: 17 open roles, Platform team 4 → 10+ planned for 2027) | ~€16M/year | €10.9M | ~8 months | ~Q3 2026 (already passed) |

Cash figure: **£9,335,731 at 31 Dec 2025** from the FY2025 accounts (Companies House, filed Sep 2026), converted at ~€1.17/£. The base and stress cases both require a new round, bridge or venture debt about now. The company is still hiring heavily, including a Head of Platform role that talks about growth in 2027, so either revenue has grown much faster than costs or an undisclosed financing (debt or an unfiled round) is in place. Neither has been confirmed.

#### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| ~2023-2024 | Redundancies alongside new hiring | Unknown | One Glassdoor review only ("had experiences redundancies as well as new hires within 1.5 years", Communications manager, London, Jun 2024). Not covered by the press |

No layoffs are recorded on TrueUp or layoffs.fyi, and no press reports were found. Engineering team instability was reported in Oct 2025 ("Team composition is quite shaky and unstable").

#### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | **NO** | No German entity exists, so there is no establishment where a council could be elected. EOR employees belong to the EOR's establishment |
| Collective agreement | **NONE** | UK private startup; no tariff references in any posting |
| European works council | N/A | Too small, and has no EU entity |
| Conflict signals | None found | - |

**Verdict:** **CAUTION**, close to FAIL. There is no council and no agreement, the runway is short, there were earlier redundancies, and the most recent review warns of a decline. EOR employment makes dismissal procedures less visible.

---

## Section 9: Regulated Industry

Mimica is not itself in a regulated sector. However:
- Its customers include financial services, healthcare, insurance and logistics companies.
- The product records end users' desktop activity, which includes personal data and screenshots. Enterprise sales therefore come with heavy security and privacy reviews: a "Customer Trust Specialist" role, "named technical owner for infrastructure in enterprise deals and security reviews", anonymisation pipelines, and a planned installable/on-prem component.
- In Germany, deploying task mining at a customer requires co-determination under §87(1) Nr. 6 BetrVG at that customer. This is a sales hurdle, not an engineering burden.

The practical effect for engineers is GDPR/SOC 2-style compliance work and data-residency demands (multi-region, "physically separated database environments"). There are no formal safety cases.

**Verdict:** **PASS** (moderate compliance overhead from enterprise data privacy, not sector regulation).

---

## Section 10: On-Call

Postings show some form of on-call:
- **Staff/Lead Python Engineer:** "Being responsive to incidents regarding ML applications - including an understanding of how to triage and resolve issues relating to CPU, memory, and GPU utilisation."
- **Staff/Senior Backend (Node.js):** "taking operational responsibility for what you build".
- **All engineering postings:** "We have a shared responsibility for our production code".
- **Head of Platform:** will "own reliability across engineering: SLOs, **on-call model**, incident process, postmortems" and "set engineering-wide standards for reliability, on-call". This means an on-call model exists or is being formalised for all of engineering, not just the Platform team.

The company sells enterprise SaaS to Fortune 500 customers across time zones from UTC-7 to UTC+3, so production support duty is likely.

**Verdict:** **CAUTION** (team-dependent; incident response is written into the Python role and an engineering-wide on-call model is planned).

---

## Section 11: Interview Process

Based on Glassdoor ("Mimica (United Kingdom)", E6316961).

| Metric | Value |
|---|---|
| Difficulty | 3.0 / 5 (Glassdoor) |
| Positive experience | **0%** (83% negative), based on 6 interviews |
| Average duration | ~33 days (14 days for a Product role up to 56 days for Senior Security Engineer) |
| Rounds | 4 stages per postings, plus an offer call |

**Steps (from the Staff/Lead Python posting):**
1. Recruiter screen with a technical recruiter.
2. Take-home challenge (async) plus a live follow-up with an Engineering Manager and a peer.
3. Live system design with the EM and a close collaborator.
4. Founders/behavioural interview with a Tech Lead and the co-founder/CTO.

The ML Engineer role follows the same pattern: talent partner, take-home with a technical discussion, and so on.

**Candidate reports:**
- **Take-home size and slow feedback:** "A VERY VERY BIG AND COMPLEX take home test which can take several days of full time work ... they clearly say a minimum of 4 hours would be needed". The live round asked for "3 BIG changes to the existing big assignment in 40 mins". Feedback took 10+ days per round (Glassdoor, Aug 2026, Staff Fullstack Engineer candidate, London, declined offer, process 4 weeks).
- **Ghosting after a technical recruiter screen:** "I was ghosted after, wrote a few times but nothing" (Glassdoor, Oct 2026, Full Stack Engineer candidate, no offer).
- **Ghosting after a positive screen:** "after that they just went ghosting despite the fact the interview went very well ... it happened 2 times" (Glassdoor, Nov 2025, Product Team Member candidate, no offer).

**Style:** experience- and design-focused, not LeetCode-heavy. It is centred on a large take-home and a live extension of it, plus system design, so it takes a lot of time. Candidates repeatedly report slow responses or no response at all.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | Enterprise AI SaaS (task mining, process intelligence, agent generation). About half the headcount is manual ML-output validation in Costa Rica. PASS with caution |
| Not consulting | Engineering roles are product work. There are customer-engineering roles (Value Engineers, Forward Deployed Engineer) and service-style revenue recognition. PASS |
| Profitable | FAIL. ~£10.0M loss in 2025 (~£4.5M in 2024); accumulated losses £20.1M |
| Employee count | ~320 on LinkedIn (201-500 band), including ~150 Operations staff in Costa Rica; ~60 in engineering; 15 on the UK payroll |
| English-speaking | PASS. English only, 16+ countries |
| Local entity + engineering contracts | **FAIL.** UK Ltd only; Germany would be via EOR or contractor |
| Location / work model | Fully remote (Germany eligible for some roles). No Munich office; time-zone windows vary (the Node.js role's window ends at UTC+1) |
| Glassdoor | 4.9 (10 reviews) and 3.5 (4 reviews) across two profiles. No Germany or Munich reviews; 2 engineering reviews. Directional only; the newest reviews are 3.0 and 4.0 |
| Kununu | No profile |
| Salary | UNVERIFIED for Germany. London Senior ~€117K and Lead ~€145-158K (Glassdoor, 1-2 data points each); options in a UK company |
| AI/ML content | Strong: proprietary ML, LLM evals/judges, anonymisation, agent generation, Vertex AI, GPU infrastructure |
| Computer-language/Tech-stack | Polyglot: Python (FastAPI, ML services, Python Chapter) plus TypeScript/Node.js MERN, on GCP/GKE |
| No on-call | CAUTION. Incident response in the Python role; engineering-wide on-call model owned by the Head of Platform |
| WLB / Stability | WLB rated well (4.7/4.2). Stability weak: cash £9.3M against ~£10M annual burn at Dec 2025, no 2026 round visible, earlier redundancies |
| Works council / collective agreement | None (no German entity) |
| Regulated industry | PASS (enterprise privacy and security reviews; data residency) |
| Review themes | Remote flexibility and founders praised; recent "contradictory" management, unstable team composition, missing processes |
| Interview experience | 0% positive (6 reports): oversized take-home, 10+ day feedback gaps, ghosting |
| Funding / runway risk | Base-case runway from the filed figures ends ~Q4 2026; a new round or bridge needed now, nothing public yet |

---

## Section 13: Verdict

**Exclude (for a Munich-based Senior/Staff role), or at most monitor.**

**Strengths:**
- The engineering is genuine applied AI, with proprietary ML trained since before the LLM wave and current work on LLM evals, anonymisation and an agent-generation product built from scratch.
- The Staff/Lead Python role is centred on Python (FastAPI, async, observability) on GCP.
- Fully remote, English-speaking, with flexible schedules; WLB is rated well.
- London pay data points are high relative to the Munich market.
- Recognised by Everest Group as a task-mining leader, with SAP and UiPath partnerships and Fortune 500 customers.

**Hard blockers:**
1. **No German employer entity.** Mimica Automation Limited (London, 11153050) is the only operating company found. A Munich hire would be employed through an EOR or as a contractor, with no German establishment, no works council and UK-company options taxed in Germany.
2. **Not profitable, and the filed runway is short.** Mimica had £9.34M cash at 31 Dec 2025 against a ~£10.0M loss in 2025. That covers about 11 months at the 2025 burn rate, ending around now. The only 2026 share allotments are under 0.6% of share capital, and no new round has been announced. Unless revenue has grown much faster than costs, Mimica needs fresh funding in the coming months.

**Secondary concerns:**
- **Thin review base:** 14 Glassdoor reviews across two profiles, mostly from sales, only 2 from engineers and none from Germany. The newest reviews mention "contradictory" management and a fear that the company will "start to fall".
- **Engineering team and job security:** the Oct 2025 engineering review describes "shaky and unstable" team composition and micromanagement, and earlier redundancies are reported.
- **On-call:** incident response is part of the Python role and an engineering-wide on-call model is being set up.
- **Hiring process:** 0% positive interview experience, an oversized take-home, 10+ day feedback gaps and repeated ghosting.
- **Business model:** about half the workforce manually validates ML output, which makes gross margins look less like SaaS than the marketing claims.
- **Unexplained £1.13M owed by the company to the CEO** at the end of 2025.

**Recommendation:** Do not prioritise Mimica. It could be reconsidered only if all of the following hold:
- **New funding:** it announces a new round, or the CTO/founders confirm one during screening, so the runway question is answered before any take-home.
- **Contract:** it offers a German employment contract (a GmbH, or at least a named, reputable EOR with German social security and a clear statutory notice period).
- **Pay:** it confirms the German pay band is in line with the London figures.

If engaging anyway, ask at the recruiter screen and before investing days in the take-home:
- funding status and runway in months;
- the employing entity for Germany;
- the on-call rota for the Python Chapter;
- the location-adjusted salary band;
- the option grant size and strike price.

---

## Sources

- [Mimica - homepage](https://www.mimica.ai/)
- [Mimica - About us (timeline, founders, address)](https://www.mimica.ai/about-us) (read via Chromium/CDP)
- [Mimica - Careers](https://www.mimica.ai/careers) (read via Chromium/CDP)
- [Mimica - Contact](https://www.mimica.ai/contact) (read via Chromium/CDP)
- [Mimica job board (Ashby)](https://jobs.ashbyhq.com/mimica) and [Ashby posting API](https://api.ashbyhq.com/posting-api/job-board/mimica?includeCompensation=true) (curl)
- [Staff/Lead Python Engineer (FastAPI, Orchestration)](https://jobs.ashbyhq.com/mimica/d07d280b-fb3f-46e2-9c45-f5f5f9f5de15) / [LinkedIn copy](https://www.linkedin.com/jobs/view/4445281385/)
- [Staff/Senior Backend Engineer (Node.js)](https://jobs.ashbyhq.com/mimica/8ad48cb5-c741-4faa-9ea6-255c093ce75e) / [LinkedIn copy](https://www.linkedin.com/jobs/view/4446840705/)
- [Staff/Lead Fullstack Engineer (Frontend-focused)](https://jobs.ashbyhq.com/mimica/c50cc802-b399-472a-8ef6-1a56d0e51d8f)
- [Staff/Lead Front-end Engineer](https://jobs.ashbyhq.com/mimica/889b14bc-0661-4139-bbc1-945c6e407df7)
- [Head of Platform (Infrastructure & DevOps)](https://jobs.ashbyhq.com/mimica/bb287245-a114-49be-820e-b602fc220aea)
- [Senior/Lead Machine Learning Engineer](https://jobs.ashbyhq.com/mimica/157112c3-9fbf-440b-a5e4-5c40f0cd2fa0)
- [Forward Deployed Engineer, Intelligent Automation](https://jobs.ashbyhq.com/mimica/c69566a5-bcdf-4380-b40e-a7844acecfd8)
- [Process Analyst, Costa Rica (Khosla Ventures job board)](https://jobs.khoslaventures.com/companies/mimica-automation/jobs/48762009-process-analyst-costa-rica) (read via Chromium/CDP)
- [Process Analysts Team Lead, Costa Rica (builtin)](https://builtin.com/job/process-analysts-team-lead-costa-rica/7141372)
- [Staff/Lead Platform/DevOps Engineer (bulldogjob)](https://bulldogjob.pl/companies/jobs/251216-staff-lead-platform-devops-engineer-warsaw-amsterdam-london-mimica)
- [Staff/Lead Python Engineer, ML Platform & Ops (startup.jobs)](https://startup.jobs/staff-lead-python-engineer-ml-platform-ops-mimica-8122152)
- [Staff/Lead Backend Engineer, FastAPI (startup.jobs)](https://startup.jobs/staff-lead-backend-engineer-fastapi-high-throughput-mimica-8122152)
- [Companies House - Mimica Automation Limited (11153050)](https://find-and-update.company-information.service.gov.uk/company/11153050) (curl)
- [Companies House - filing history](https://find-and-update.company-information.service.gov.uk/company/11153050/filing-history) (curl)
- [Companies House - FY2025 accounts (iXBRL)](https://find-and-update.company-information.service.gov.uk/company/11153050/filing-history/MzU0NDA4ODI1NWFkaXF6a2N4/document?format=xhtml&download=1) (curl)
- [Companies House - FY2024 accounts (iXBRL)](https://find-and-update.company-information.service.gov.uk/company/11153050/filing-history/MzQ4MTU1MzAyNWFkaXF6a2N4/document?format=xhtml&download=1) (curl)
- [Companies House - officers](https://find-and-update.company-information.service.gov.uk/company/11153050/officers) (curl)
- [Companies House - persons with significant control](https://find-and-update.company-information.service.gov.uk/company/11153050/persons-with-significant-control) (curl)
- [Companies House - Mimica Lab Ltd (unrelated, 10724944)](https://find-and-update.company-information.service.gov.uk/company/10724944) (curl)
- [NorthData - search "Mimica Automation"](https://www.northdata.com/search?query=Mimica+Automation) (read via Chromium/CDP)
- [NorthData - "Mimica"](https://www.northdata.com/Mimica) (read via Chromium/CDP)
- [Glassdoor - Mimica (United Kingdom) overview](https://www.glassdoor.com/Overview/Working-at-Mimica-United-Kingdom-EI_IE6316961.11,32.htm) (read via Chromium/CDP)
- [Glassdoor - Mimica (United Kingdom) reviews](https://www.glassdoor.co.uk/Reviews/Mimica-United-Kingdom-Reviews-E6316961.htm?filter.iso3Language=eng&sort.sortType=RD) (read via Chromium/CDP)
- [Glassdoor - Mimica (second profile) overview](https://www.glassdoor.com/Overview/Working-at-Mimica-EI_IE6034363.11,17.htm) (read via Chromium/CDP)
- [Glassdoor - Mimica (second profile) reviews](https://www.glassdoor.co.uk/Reviews/Mimica-Reviews-E6034363.htm?filter.iso3Language=eng&sort.sortType=RD) (read via Chromium/CDP)
- [Glassdoor - Mimica (United Kingdom) salaries](https://www.glassdoor.co.uk/Salary/Mimica-United-Kingdom-Salaries-E6316961.htm) (read via Chromium/CDP)
- [Glassdoor - Mimica (second profile) salaries](https://www.glassdoor.co.uk/Salary/Mimica-Salaries-E6034363.htm) (read via Chromium/CDP)
- [Glassdoor - Mimica (United Kingdom) interviews](https://www.glassdoor.co.uk/Interview/Mimica-United-Kingdom-Interview-Questions-E6316961.htm) (read via Chromium/CDP)
- [Kununu - search "mimica"](https://www.kununu.com/de/search?q=mimica) (curl 405, then Chromium/CDP)
- [Teamblind - Mimica (not found)](https://www.teamblind.com/company/Mimica) (read via Chromium/CDP)
- [levels.fyi - Mimica (404)](https://www.levels.fyi/companies/mimica/salaries) (read via Chromium/CDP)
- [LinkedIn - Mimica company page](https://www.linkedin.com/company/mimica-automation/) and [People insights](https://www.linkedin.com/company/mimica-automation/people/) (read via Chromium/CDP)
- [CB Insights - Mimica financials](https://www.cbinsights.com/company/mimica/financials) (read via Chromium/CDP)
- [Startups Magazine - Mimica raises $26.2M (Sep 2025)](https://startupsmagazine.co.uk/article-mimica-raises-262m-make-ai-agents-actually-work-real-world) (read via Chromium/CDP)
- [Financial IT - Mimica raises $26.2M](https://financialit.net/news/fundraising-news/mimica-raises-262m-make-ai-agents-actually-work-real-world)
- [Paladin Capital Group - Series B announcement](https://www.paladincapgroup.com/?p=9151)
- [Bird & Bird - advises Paladin on Series B in Mimica](https://cm.twobirds.com/en/news-and-deals/2025/uk/bird-and-bird-advises-paladin-capital-on-series-b-in-mimica)
- [BusinessCloud - Mimica raises £19.5m](https://businesscloud.co.uk/news/mimica-raises-19-5m-to-make-ai-useful-for-businesses/)
- [Latka - Mimica revenue estimate](https://getlatka.com/companies/mimica.ai)
- [Entrepreneur First - Mimica](https://www.joinef.com/companies/mimica/?pagenum=2)
- [Built In - Mimica Automation](https://builtin.com/company/mimica-automation/benefits)
- [Process Excellence Network - interview with Mimica](https://www.processexcellencenetwork.com/process-mining/interviews/mimica-transforming-future-process-intelligence)
- [remotely.de - Mimica postings for Germany](https://www.remotely.de/job/mimica-staff-lead-frontend-engineer-de-1274107)
- [Great Place to Work - certified companies directory](https://www.greatplacetowork.com/en/certified-company?start=250)
- [TrueUp - Mimica](https://www.trueup.io/co/mimica) (read via Chromium/CDP, no entry)
- [layoffs.fyi](https://layoffs.fyi/) (read via Chromium/CDP, no entry)
- [OpenStreetMap Nominatim - 107 Cheapside](https://nominatim.openstreetmap.org/search?q=107+Cheapside,+London+EC2V+6DN&format=json&addressdetails=1&limit=1)
- [Overpass API (kumi.systems mirror) - stations around 107 Cheapside](https://overpass.kumi.systems/api/interpreter)
