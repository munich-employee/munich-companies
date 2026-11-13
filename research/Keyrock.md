# Keyrock - Full Research Report

_Researched: 2026-11-13_

> **Critical Disqualifiers**
> 1. **No German legal entity.** NorthData lists no Keyrock company in Germany. The group's entities are Keyrock N.V./S.A. (Belgium, parent), Keyrock UK Ltd., Keyrock CH GmbH (Switzerland), Keyrock FR SAS (France, MiCA CASP), a US entity and Keyrock Asset Management (Luxembourg). Deel's own case study states that Keyrock uses Deel's **Employer of Record** to hire "in countries where it lacks a legal presence". A Germany-based hire would be employed by Deel's German EOR entity, not by Keyrock.
> 2. **No Munich office.** Hubs are London, Brussels, Singapore and Paris. Germany appears only as a remote location tag (Berlin, Frankfurt) on postings.
> 3. **Not software-centric in the product sense.** Keyrock is a crypto market maker and proprietary trading / asset management group. Revenue comes from trading, not from selling software.
> 4. **Profitability unproven at group level.** The Belgian parent lost €11.4M in FY2024 and earned €1.8M in FY2025 (to 30 June 2025). The group is VC-backed (Series C at $1.1B, March 2026) and no consolidated accounts are public.
>
> Full report follows for completeness.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | December 2017, Brussels (registered 11/12/2017 as Keyrock SPRL) - ~9 years |
| Employees | ~220-250 globally (company: "220+" on About page, "over 250 team members" in the newest posting; TrueUp 210). Only **19.7 FTE** on the Belgian parent's own payroll (NBB filing FY2025) |
| Revenue | Belgian parent: €46.0M turnover FY2025 (to 30/06/2025), €31.2M FY2024. Group revenue undisclosed; aggregator estimates $66-72M |
| Profitability | Belgian parent: +€1.8M FY2025, -€11.4M FY2024, -€1.3M 2022, +€6.2M 2021. No consolidated group accounts found - **BORDERLINE** |
| Ownership | Private, VC-backed (SC Ventures/Standard Chartered, Ripple, SIX Fintech Ventures, Middlegame Ventures, Volta Ventures) |
| Software-centric | Crypto market maker / trading firm with an in-house Rust trading stack. Revenue is trading income, not software sales - **BORDERLINE** |

### Key People

- **Kevin de Patoul** - co-founder and CEO (ex-Roland Berger strategy consultant)
- **Jeremy de Groodt** - co-founder and CTO (previously led software teams building secure applications for European institutions and banks)
- **Juan David Mendieta** - co-founder and Chief Strategy Officer
- **Eric Beckwith** - Chief Investment Officer (ex-Managing Director, Bank of America Merrill Lynch)
- **Francesco Adiliberti** - COO (ex-Goldman Sachs, UBS, Nomura, HSBC, Amber Group)
- **Stef Wynendaele** - Chief Commercial Officer

### Funding History

| Date | Round | Amount | Valuation |
|---|---|---|---|
| ~2019-2021 | Series A (SIX Fintech Ventures, Middlegame, Volta Ventures - single source) | Undisclosed | - |
| Jan 2022 | Series B (Ripple, SIX Fintech Ventures, Middlegame Ventures) | $72M | ~$275M implied ("valuation quadrupled" to $1.1B per tech.eu) |
| 31 Mar 2026 | Series C, open round led by SC Ventures, Ripple participating | Undisclosed; "could reach ~$100M" by mid-2026 per The Block / Cointelegraph | $1.1B |
| **Total** | | **~$78M-$176M** (aggregators disagree) | **$1.1B** |

### Acquisitions

| Date | Target | Notes |
|---|---|---|
| Sept 2025 | Turing Capital (Luxembourg fund manager) | ~$27.8M; became Keyrock Asset and Wealth Management |
| 2026 | Fija Finance | On-chain reach (About page) |
| Jul 2026 | BlockFills trading and brokerage assets (Chapter 11) | ~$3.25M, paid in two tranches; adds a CIMA-regulated Cayman entity and a proposed FCA-regulated UK entity |

### Business Model

Keyrock is a **digital-asset market maker and investment group**. Business lines: algorithmic market making on 80-85+ exchanges and ~1,400 markets, OTC trading, an options desk, on-chain (DeFi) liquidity, validator services, an accelerator / ecosystem-development programme, and since 2025 asset and wealth management (Absolute Alpha, Smart Beta funds). Income comes from token-issuer retainers and loans, trading spreads and P&L, and fund management fees.

### Software-Centric Assessment

Engineering is central to how Keyrock makes money: the market-making engine, exchange connectors, HFT stack and risk systems are built in-house in Rust, and the company calls itself a "pioneer in adopting Rust for algorithmic trading" (in production since 2020). However:

- The **product is liquidity and trading P&L**, not software sold to customers. Software is an internal cost centre serving the trading desks.
- Engineering roles are explicitly attached to trading divisions ("join our core Capital Markets division ... a highly-profitable, fast-paced division").
- Hiring emphasises trading-domain experience: "Hands-on experience in a systematic trading environment (HFT, Market Making, Quantitative Trading, or similar)".

This is the same profile as a proprietary trading firm: engineering-heavy, but the business is finance. **BORDERLINE.**

---

## Section 2: Local Commercial Entity in country of interest

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **Keyrock N.V. / S.A.** (parent) | KBO/BCE 0685.795.245, LEI 213800A4ELK21IF12133 | Avenue Louise / Louizalaan 480, 15th floor, 1050 Ixelles (Brussels), Belgium | NACE 66.12 securities and commodity brokerage; 62.10 / 62.01 computer programming |
| Keyrock UK Ltd. | UK (subsidiary per NBB filing 2022) | London | Trading / UK hub |
| Keyrock CH GmbH | Switzerland (subsidiary per NBB filing 2022) | Switzerland | Swiss operations |
| Keyrock FR SAS | France, AMF-authorised MiCA CASP (12/15 June 2026) | Paris | EU-regulated crypto-asset services; passporting to other EU states in progress |
| Keyrock Asset Management | Luxembourg (ex-Turing Capital) | Luxembourg | Fund management |
| **Germany** | **None found** | - | - |

**Verification.** NorthData (searched via CDP on northdata.de and northdata.com, filtered to Germany) returns only the Belgian parent. No Handelsregister entry for a "Keyrock GmbH" was found by web search. The privacy notice names Keyrock S.A., Brussels, as the sole data controller for recruitment. Deel's published case study states that Keyrock uses **Deel EOR and Deel Mobility** "to hire talent quickly and compliantly in countries where it lacks a legal presence". Postings tagged "Berlin" and "Frankfurt" are remote location tags on Brussels-headquartered roles (Ashby lists ~35 secondary locations per role), not German offices.

A German resident would therefore have an employment contract with Deel's German EOR entity, with Keyrock as the client. That is the PEO/EOR arrangement this criterion screens out: no direct contract with Keyrock, no German entity to hold accountable, and no works council (see Section 8).

**Verdict:** **FAIL**

---

## Section 3: Office Location

- **Office address:** No office in Munich or anywhere in Germany. The registered HQ is Avenue Louise 480, 15th floor, 1050 Ixelles, Brussels (privacy notice, NorthData). Nominatim geocodes it to 50.8171, 4.3721 (La Cambre / Ter Kameren, Ixelles). Other hubs: London, Paris, Singapore; Zurich/Zug/Geneva for Swiss compliance roles.
- **Nearest public transport (Brussels HQ):** "Legrand" tram stop on Avenue Louise, ~50 m (OSM node; line numbers are not tagged on the node). "Abbaye - Abdij" tram stop ~220 m, "Cambre-Étoile - Ter Kameren-Ster" bus/tram stop ~270-310 m, "Bascule" tram and bus 38 ~340-380 m. There is no rail station within 900 m. Source: Nominatim plus Overpass queries.
- **Work model:** **Remote-first.** Postings say "Predominantly remote, we have hubs in London, Brussels, Singapore and Paris", "collaborating with a global, fully-remote team", and "This role is open to candidates located in European time zones". The Senior Data Engineer posting adds "a yearly onsite where everyone's in the same room". From Munich the work would be fully remote under a Deel EOR contract. Glassdoor reviewers mention isolation: "do consider if remote working is 100% for you as it does get lonely" (Glassdoor, Apr 2026, former Trader, Singapore, 1+ years).

---

## Section 4: Reviews

**GPTW:** No Great Place to Work certification for Keyrock was found by web search. Direct searches on greatplacetowork.de and greatplacetowork.be returned nothing readable, so treat this as **not found** rather than confirmed absent.

### Glassdoor

Retrieved via Chromium/CDP (logged-in session, glassdoor.de, employer E1937140). Glassdoor reports **26 reviews** overall. 19 English-language reviews and 1 German review were readable (18 read in full).

| Metric | Global | Germany | Munich | Software Engineers (computed from 5 SWE-titled reviews read) |
|---|---|---|---|---|
| **Overall** | 4.0 (26 reviews) | No reviews | No reviews | ~3.4 (5 reviews: 1.0, 2.0, 4.0, 5.0, 5.0) |
| **WLB** | 4.4 | - | - | n/a |
| **Culture & Values** | 3.9 | - | - | n/a |
| **Comp & Benefits** | 3.7 (down 3% in the last 12 months) | - | - | n/a |
| **Career Opportunities** | 3.5 | - | - | n/a |
| **Senior Management** | 3.6 | - | - | n/a |
| **Diversity & Inclusion** | 4.2 | - | - | n/a |
| **% Recommend** | 70% | - | - | n/a |
| **CEO Approval** | Not shown | - | - | n/a |
| **Business Outlook** | 72% positive | - | - | n/a |

All filters fall well below 20 reviews; every score here is **directional only**. None of the readable reviews is tagged with a German location. The SWE column is computed by hand from the individual reviews and is the least reliable figure in the table.

### Kununu

**Not listed.** `kununu.com/de/keyrock`, `/keyrock1` and `/keyrock-sa` returned HTTP 405 via curl. A Kununu search via CDP returned "No results found for 'Keyrock'". This is expected: Keyrock has no DACH entity. Kununu Top Company: **NO**.

### Blind / Teamblind

**No company page** (`teamblind.com/company/Keyrock` returns "Page not found", via CDP). No scores available.

### Review Themes (2022-2026)

**Positives:**
- **Remote-first flexibility and WLB** (WLB 4.4 is the highest sub-score): "Friendly, remote-first, international company where you can have good work-life balance" (Glassdoor, Apr 2026, current Software Engineer). "Work-life balance. Intelligent, kind, open-minded colleagues. Rust backend." (Glassdoor, Nov 2025, current Engineer).
- **Strong colleagues and brand:** "Smart, technically capable colleagues across trading and engineering who genuinely understand the space" and "Keyrock's reputation opens doors with top-tier counterparties and exchanges globally" (Glassdoor, Jul 2026, former Trading, 1+ years).
- **Modern stack:** "on the cutting edge of technology and use some of the newest languages and frameworks" (Glassdoor, Jul 2024, current Senior Software Developer, Los Angeles, 1+ years).
- **Pay progression and bonus cadence:** "comp at market rate + bonus paid every 6mnth" (Glassdoor, Apr 2026, former Trader, Singapore, 1+ years). "Pay starts low but does go up consistently" (Glassdoor, Jan 2025, former Algorithmic Trader, Brussels, 3+ years).

**Negatives:**
- **Management and top-down culture (engineering-specific):** "Very toxic environment multiple management levels on top of few developers, very vertical top to bottom culture, poor management, basically they take and impose decision to all level putting a lot of pressur on the developers." (Glassdoor, Jun 2026, former Senior Software Engineer, Zurich).
- **Reorganisations, micro-management, nepotism:** "Bad and inexperienced management that changes team structures constantly. A lot of micro-management No room for growth at all Nepotism" (Glassdoor, Dec 2024, current anonymous employee; 6 "helpful" votes).
- **Unclear structure and shifting strategy:** "Organizational structure and internal communication can be unclear, making it hard to know where decisions are actually made ... Career pathing and growth frameworks are underdeveloped ... Strategic direction shifted frequently" (Glassdoor, Jul 2026, former Trading, 1+ years).
- **Becoming more corporate / TradFi:** "Working to become more like a traditional finance institution, the culture is getting very corporate." (Glassdoor, Apr 2026, current Software Engineer).
- **Silos and isolation:** "a bit silo in BUs" (Glassdoor snippet via web search, 2025, role not shown). The loneliness quote under Work model.
- **Older outlier:** "Stay away. They are total scammers." (Glassdoor, May 2021, former Senior Software Developer, German-language review; no detail given).
- **Candidate experience** (Section 11): only 36% positive, with repeated reports of long processes followed by silence.

Overlap with hard red flags: **communication breakdown** and **toxic / top-down management** both appear, and both come from engineering reviewers. Each rests on a small number of reviews.

### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | Two engineering-adjacent 1-2 star reviews (Dec 2024, Jun 2026) describe "toxic environment", "poor management", "inexperienced management". Positive reviews from engineers in 2024-2026 contradict this. Mixed signal from a small sample. |
| 24/7 Work Expectation | Crypto markets trade 24/7, and Deel's case study says "operations running around the clock". Postings describe "business-hours on-call shared across the team" for data. No reviewer complains about 24/7 availability. |
| Internal Surveillance | No evidence. Background checks are mandatory for all hires ("passing which is a prerequisite to join Keyrock"), which is standard for regulated trading. |
| Fear-driven Management | "putting a lot of pressur on the developers" (Jun 2026, former Senior SWE). "Don't expect to be treated with respect unless you're part of management" (Dec 2024 review title). Isolated. |
| Communication Breakdown | "hard to know where decisions are actually made" (Jul 2026). Candidate reviews repeatedly describe silence after final rounds. Recurring theme. |
| Unpaid Overtime | No evidence. "Challenging, hard work" (Feb 2024, Compliance Officer, Brussels) is the closest mention. |
| Silent Firings | No evidence found. With no works council (Section 8) there is no structural protection either. |
| Work-Life Balance issues | None. WLB 4.4 is the highest sub-score. |

**Risk level: MODERATE.** This is (c) localised dysfunction plus scale-up growing pains (frequent reorganisations, unclear decision rights, a shift from crypto-native to TradFi culture), not (a) systemic toxicity: WLB and recommendation scores remain good. The two engineering complaints are recent (2024, 2026) and specific, so this is worth probing in interviews: team stability, who sets technical direction, and how many management layers sit above ICs.

---

## Section 5: Compensation

### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| levels.fyi (Belgium) | Software Engineer, median (L4, Ghent, 8 yrs exp) | ~€119K | ~€4.9K | €0 | **~€124K** | small (most entries masked) |
| levels.fyi (Belgium) | Senior, Distributed Systems (Back-End), Brussels, 15 yrs exp | €175K | - | - | €175K | 1 (Jul 2026) |
| levels.fyi (Belgium) | Senior, Distributed Systems (Back-End), Brussels, 15 yrs exp | €174K | - | - | €174K | 1 (Jun 2026) |
| levels.fyi (global) | Software Engineering Manager | - | - | - | ~$233K | small |
| Glassdoor | All roles | - | - | - | - | 27 salaries (Brussels 23, London 4); no Germany or Munich data; no SWE breakdown exposed |
| Job postings | Rust / Data roles | Not disclosed ("A competitive salary package") | - | - | - | 3 postings |

**Munich reference bracket** (levels.fyi Germany, from earlier reports in this project): Senior SWE median ~€81.5K total, senior range ~€80.7K-€115.1K. Large, profitable Munich employers pay ~€85-110K base, with the 90th percentile at €120K+. No Keyrock data exists for Munich or Germany.

Caveats: the Belgian figures may be gross employer cost or self-employed day-rate equivalents (common for Belgian trading firms), and they come from 2-3 visible submissions. Pay for a Germany-based Deel EOR hire may be benchmarked to the local market rather than Brussels. Reviews describe semi-annual bonuses for traders. There is no evidence of a bonus for engineers.

### Equity / Stock

Private company. levels.fyi shows a small stock component (~€4.9K/yr at the median), suggesting options or a phantom-share plan exists for some employees. Details (strike, vesting, liquidity) are not public. Liquidity risk is high: there is no IPO announcement, and the valuation depends on crypto market cycles.

### Verdict

The visible data (€124K median, €174-175K senior back-end) sits **above** the Munich large-corporation bracket. It rests on very few data points, in a different country, under an unknown contract type, and pay for an EOR hire in Germany is unconfirmed. **UNVERIFIED (indicatively ABOVE).**

---

## Section 6: AI/ML & Tech Stack

### AI Strategy

There is no AI product. AI shows up in two places:
1. **Agentic engineering as a working practice.** Rust postings require "Familiarity with agentic engineering tools and concepts: LLMs, MCP APIs, AI-First IDEs (e.g. Cursor, Claude Code), harness engineering, and workflow automation" and ask engineers to "help evolve the team's agentic tooling".
2. **Internal data platform for AI agents.** The new Central Data Team is "building the Keyrock Data Platform to give Keyrockers, and the AI agents working alongside them, the data and context they need to act fast and autonomously", including "self-serve tooling (SDKs, patterns, templates, AI agents)".

Quant research (pricing, market-making models) is the core modelling work, but it sits with Trading & Research, not engineering. This is applied internal tooling, not ML platform or MLOps engineering.

### Tech Stack

Sources: current Ashby postings (Rust Engineer - Trading Systems, Senior Rust Engineer - HFT, Senior Data Engineer; fetched via the Ashby public posting API), aggregator copies of older postings (Rust Engineer - Platform, Technical Lead (Rust/C++), SRE, C++ Engineer - Trading), Glassdoor reviews. No public engineering blog or GitHub organisation was found.

| Category | Technologies |
|---|---|
| **Primary language(s)** | **Rust** (Tokio; in production since 2020) for trading, HFT, exchange connectivity and platform. Python for strategy development, automation and data. C++ in some trading roles. TypeScript/Node.js (Technical Lead posting) |
| **AI/ML** | LLM-assisted development (Cursor, Claude Code), MCP, internal AI agents on the data platform. Quant models in Python |
| **Cloud** | AWS (EKS, MSK and Kinesis mentioned), with latency-sensitive tuning |
| **Infrastructure** | Kubernetes (EKS, K3s), Terraform, Docker, CI/CD, Linux; low-latency networking (TCP/UDP, DPDK kernel bypass); FIX / REST / WebSocket exchange connectivity |
| **Data** | Kafka / Redpanda / MSK / Kinesis streaming with schema registry; ClickHouse (preferred) or TimescaleDB / QuestDB time-series; lakehouse architecture; SQL |
| **Other** | Observability (logs, metrics, traces) as a stated default; background checks for all hires |

**Summary:** Rust-centric low-latency trading engineering (Tokio, FIX/WebSocket connectivity, DPDK) on AWS/Kubernetes, with Python for strategy tooling and a newly forming Python/SQL data platform (Kafka, ClickHouse, lakehouse). AI is limited to agentic developer tooling and internal data agents. This is applied, production trading-systems engineering, not research.

---

## Section 7: Language

All postings are in English, with no German or French requirement. The team spans 42 nationalities, and reviewers describe a "multi cultural" remote team. The Brussels HQ works in English despite the bilingual city. Postings and reviews mention no German.

**Verdict:** **PASS**

---

## Section 8: Stability

### Financial Position

Belgian parent Keyrock N.V. (NBB filings via CompanyWeb, retrieved via CDP; NorthData publication list):

| Year | Turnover | Gross margin | Net result | Balance sheet total | Equity | FTE (BE) |
|---|---|---|---|---|---|---|
| FY to 30/06/2025 | €46.0M | €20.1M | **+€1.8M** | €250.2M | €30.8M | 19.7 |
| 2024 (period to 30/06/2024) | €31.2M | €0.2M | **-€11.4M** | €192.7M | €28.9M | 26.6 |
| 2022 | - | €4.6M | -€1.3M | €92.0M | €25.3M | 21.8 |
| 2021 | - | €8.5M | +€6.2M | €98.2M | €11.6M | 19.3 |

The balance sheet is mostly trading inventory funded by €219M of liabilities (token loans, counterparty and exchange balances), which is typical for a market maker. Equity is a thin ~12% of assets. Results swing with the crypto cycle (a profit in the 2021 bull market, losses in 2022-2024, a small profit in the year to mid-2025). The Belgian parent's 20 FTE show that most of the ~230 staff sit in other entities or on Deel EOR, so these accounts are **not the group P&L**. No consolidated accounts were found.

Positive signals: the Series C at a 4x valuation step-up (March 2026), a MiCA CASP licence (June 2026), a Deutsche Bank partnership, acquisitions in 2025-2026, and postings describing Capital Markets as "a highly-profitable ... division". Negative signals: a February 2026 crypto crash severe enough to bankrupt peer BlockFills, and the group's cyclical P&L.

### Financial Runway

No cash figure or runway estimate is public. The model below uses: Belgian parent equity €30.8M (30/06/2025, NBB), Series C cash assumed at ~$50-100M (undisclosed; "could reach ~$100M"), and group revenue at the aggregator estimate of ~$66-72M (~€60-65M).

| Cost line | Annual estimate |
|---|---|
| Staff (~240 × ~€140K fully loaded, incl. EOR fees and trader bonuses) | ~€34M |
| Exchange fees, co-location, AWS, market data | ~€8M |
| Legal, compliance, licences (MiCA, FCA, FINMA, CIMA), audit | ~€5M |
| Offices, G&A, events, acquisition integration | ~€4M |
| **Total gross burn** | **~€51M/year** |

| Revenue source | Est. annual inflow |
|---|---|
| Market making, OTC, options, DeFi trading income and retainers | ~€55-60M |
| Asset / wealth management fees (Turing Capital, since 2025) | ~€2-5M |
| **Total revenue offset** | **~€57-65M/year** (highly cyclical) |

| Scenario | Net burn | Cash at hand | Runway | Next round needed by |
|---|---|---|---|---|
| Optimistic (bull market, revenue ~€70M) | +€19M/year (cash generative) | ~€30M equity + ~€80M Series C | Indefinite | Not needed |
| Base case (revenue ~€55M) | ~break-even (+€4M) | ~€30M + ~€50M | Indefinite at current size | Not needed; M&A funded from Series C |
| Stress (crypto winter, revenue ~€30M) | -€21M/year | ~€30M + ~€50M | ~3.5-4 years | ~2029-2030 (sooner if trading losses hit inventory) |

Cash figure used: Belgian parent equity of €30.8M at 30/06/2025 (CompanyWeb/NBB, observed 2026-11-13) plus an undisclosed Series C, modelled at €50-80M. The real risk for a market maker is not opex burn but **trading or counterparty losses** (exchange failures, token collapses), which this model cannot capture.

### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| - | None found | - | TrueUp lists "No known layoffs". No press coverage of Keyrock cuts during the 2022-2023 crypto winter (peers such as GSR cut 5-10%). The Belgian parent's FTE fell from 26.6 to 19.7 between FY2024 and FY2025, which may reflect staff moving to other entities. |

Glassdoor mentions "changes team structures constantly" (Dec 2024) and a role "placed on hold" mid-process (May 2026 candidate review). These point to churn without formal layoffs.

### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | **NO** | No German entity exists. German staff would be on Deel EOR. In Belgium a works council (conseil d'entreprise) is mandatory only from 100 employees, and the parent has ~20 FTE. No reviewer mentions one. |
| Collective agreement | **NONE** (Germany). Belgian sector joint committee (likely PC 200) applies only to Belgian employees | No German Tarif. Postings offer only "A competitive salary package" |
| European works council | **N/A** | Below the EWC thresholds (1,000 EU employees) |
| Conflict signals | None found | - |

No council, no agreement and EOR employment together mean there is no structural protection against individual dismissals beyond statutory German law (KSchG would apply via the Deel EOR employer after 6 months). Weighed with the "constantly changing team structures" theme.

**Verdict:** **CAUTION** (financially resilient for now, but a cyclical, thin-equity crypto business with no employee-representation structures)

---

## Section 9: Regulated Industry

Heavily regulated financial services:
- **MiCA** CASP authorisation via Keyrock FR SAS (AMF, June 2026), being passported EU-wide
- **FCA** (proposed UK entity via BlockFills), **CIMA** (Cayman), Swiss / Liechtenstein compliance and MLRO roles (FINMA / VQF context), US entity
- **AML/CFT** obligations, mandatory background checks for all hires
- **DORA** applies to MiCA CASPs: ICT risk management, incident reporting, third-party risk and resilience testing obligations will reach engineering

Engineering impact: production-readiness testing, change control on trading systems, audit trails and data governance ("Own data contracts ... lineage, ownership" in the data posting). The direction of travel is explicitly towards TradFi norms ("Working to become more like a traditional finance institution", Apr 2026 review).

**Verdict:** **CAUTION**

---

## Section 10: On-Call

- Senior Data Engineer posting: "**business-hours on-call shared across the team**" (explicit).
- Rust trading postings: "Own key trading stack components end-to-end - from architecture through to production operation" and "Troubleshoot complex production issues across exchange connectivity, execution, and market data handling". No on-call wording, but production ownership of 24/7 trading systems implies an incident rota.
- Deel case study: "With operations running around the clock they require a globally distributed workforce to cover diverse time zones", which suggests follow-the-sun coverage rather than night pages.
- SRE / Platform postings (older, aggregator copies) cover the AWS/Kubernetes infrastructure behind 24/7 markets.

**Verdict:** **CAUTION (team-dependent)**. On-call is explicit for data (business hours only) and implied for trading systems. Out-of-hours coverage for crypto markets is not documented.

---

## Section 11: Interview Process

Based on Glassdoor (glassdoor.de, CDP, 36 interview reports, English filter).

| Metric | Value |
|---|---|
| Difficulty | 2.94 / 5 |
| Positive experience | 36% (47% negative) |
| Average duration | ~37 days (Developer roles reported as fastest; SOC Analyst ~90 days) |
| Rounds | 4-6 typical (recruiter, hiring manager / head of desk, technical, case study or take-home, presentation, background check) |

Typical steps reported: recruiter screen, then technical and behavioural interviews, a take-home or case study (the "Rust challenge" in Rust roles per older postings), a final presentation to leadership (e.g. "recruiter, CISO, Head of Security, CTO, plus a detailed case study and presentation", SOC Analyst, May 2026), then a background check. Trading roles add pressure questions ("You are holding a large position in an illiquid market, how do you manage the risk?").

The process is **experience- and design-focused with a take-home**, not LeetCode-heavy. The dominant complaint is process hygiene: "Several rounds in quick succession with positive momentum and then silence... almost 5 weeks of silence... followed by a fluffy 'we've re-defined the role' rejection" (Glassdoor, Mar 2026, Quant Researcher candidate). "The challenge seemed disproportionate to the role as presented" (Glassdoor, Mar 2026, HR Ops/Payroll candidate, Brussels). Roles being put on hold mid-process recur.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | BORDERLINE: in-house Rust trading stack, but the business is crypto market making and trading |
| Not consulting | PASS: no client billing; services are liquidity provision |
| Profitable | BORDERLINE: Belgian parent +€1.8M (FY to 06/2025) after -€11.4M; no group accounts; VC-backed |
| Employee count | ~220-250 globally; ~20 FTE on the Belgian parent payroll |
| English-speaking | PASS |
| Local entity + engineering contracts | **FAIL**: no German entity; Deel EOR in countries without presence |
| Location / work model | No Munich or German office; fully remote within European time zones; Brussels / London / Paris hubs; yearly onsite |
| Glassdoor | 4.0 (26 reviews), WLB 4.4, Comp 3.7, Career 3.5, 70% recommend; SWE-only ~3.4 (5 reviews) |
| Kununu | Not listed |
| Salary | UNVERIFIED, indicatively ABOVE: levels.fyi Belgium SWE median €124K, senior back-end €174-175K (2-3 points) |
| AI/ML content | Low: agentic dev tooling and an internal data platform for AI agents; no ML product |
| Computer-language/Tech-stack | Rust-centric (Tokio, low latency, AWS/EKS, Terraform); Python/SQL data platform (Kafka, ClickHouse) |
| No on-call | CAUTION: business-hours on-call for data; production ownership of 24/7 trading systems |
| WLB / Stability | WLB good; cyclical crypto revenue, thin equity; no layoffs found |
| Works council / collective agreement | NONE |
| Regulated industry | CAUTION: MiCA/AMF, FCA, CIMA, Swiss regulation, AML, DORA |
| Review themes | Positive on remote flexibility, colleagues and the Rust stack; negative on top-down management, constant reorgs, unclear decision rights, and the drift to corporate/TradFi culture |
| Crypto-market exposure | Revenue and job security tied to crypto cycles; the Feb 2026 crash bankrupted peer BlockFills |
| Candidate experience | 36% positive; long processes and ghosting reported repeatedly |

---

## Section 13: Verdict

**Recommendation: Exclude.**

**Strengths.** Keyrock is a well-funded ($1.1B valuation, March 2026), MiCA-licensed, growing crypto market maker with one of the most serious production Rust stacks in Europe. It is remote-first with strong work-life-balance scores (4.4) and pays well by the limited Belgian data (€124K SWE median, ~€175K senior back-end). The engineering work (low-latency Rust, exchange connectivity, a greenfield Kafka/ClickHouse data platform) is real production engineering, and English is the only working language.

**Hard blockers:**
1. **No German employing entity.** No Keyrock company is registered in Germany (NorthData). Keyrock's own testimonial for Deel confirms that it hires through Deel's Employer of Record where it has no legal presence. A Munich-based engineer would sign with Deel's German EOR entity, not Keyrock: no direct contract, no works council, and employment that depends on a third-party service agreement.
2. **No office in Munich or Germany.** The work would be 100% remote with a yearly onsite. The nearest hubs are Brussels, Paris and London.
3. **Profitability not established.** The Belgian parent's last two results are -€11.4M and +€1.8M, with no consolidated group accounts. The company is VC-backed and its results swing with the crypto cycle.

**Secondary concerns:**
- **Not a software business:** engineering serves trading desks. Postings require prior HFT, market-making or quant trading experience, a domain filter most candidates will not meet.
- **Crypto-cycle exposure** and a balance sheet that is ~88% liabilities. Peer BlockFills went bankrupt after the February 2026 crash.
- **Regulatory load** is rising (MiCA, DORA, FCA) and the culture is shifting towards a "traditional finance institution".
- **On-call:** explicit business-hours rota for data; production ownership of 24/7 trading systems.
- **Management signals:** two recent engineering reviews describe top-down, multi-layered management, and others mention constant restructuring. All on small samples.
- **Low AI/ML content:** limited to agentic developer tooling.
- **Poor candidate experience:** 36% positive, with repeated reports of silence after final rounds.

**What would need to change:** Keyrock would need to open a German GmbH that employs engineers directly (or the EOR criterion would need relaxing) and publish group accounts showing sustained profitability. Even then, the trading-domain requirement and crypto-cycle risk remain. If the EOR and remote criteria were ever relaxed, the Senior Data Engineer role (greenfield Python/SQL streaming and lakehouse platform, business-hours on-call only) would be the closest fit. In interviews, verify: the employing entity and contract type for Germany, the pay band for a German EOR hire versus Brussels, the out-of-hours on-call rota, and team stability under the current reorganisation pace.

---

## Sources

- [Keyrock - About us](https://keyrock.com/about-us/) (CDP)
- [Keyrock - Careers](https://keyrock.com/careers/) (CDP)
- [Keyrock - Privacy & Complaint notice](https://keyrock.com/privacy-complaints-notice/) (CDP)
- [Keyrock - Terms and Conditions](https://keyrock.com/terms-and-conditions/)
- [Ashby job board API - Keyrock](https://api.ashbyhq.com/posting-api/job-board/keyrock?includeCompensation=true) (curl)
- [Ashby - Keyrock jobs](https://jobs.ashbyhq.com/keyrock)
- [Keyrock - Series C funding from SC Ventures](https://keyrock.com/keyrock-secures-series-c-funding-from-sc-ventures/)
- [Keyrock - MiCA licence](https://keyrock.com/keyrock-secures-mica-license/)
- [Keyrock - BlockFills assets acquisition](https://keyrock.com/keyrock-acquires-blockfills-assets/)
- [Keyrock - Deutsche Bank partnership](https://keyrock.com/keyrock-enters-strategic-partnership-with-deutsche-bank/)
- [NorthData - Keyrock N.V., Elsene](https://www.northdata.com/Keyrock+N.V.,+Elsene/KBO+0685.795.245) (CDP)
- [NorthData - search Keyrock (DE)](https://www.northdata.de/Keyrock) (CDP)
- [CompanyWeb - Keyrock financials (NBB)](https://www.companyweb.be/en/0685795245/keyrock) (CDP)
- [Trendstop - Keyrock](https://trendstop.knack.be/en/detail/685795245/keyrock.aspx)
- [AMF white list - Keyrock FR SAS (CASP)](https://www.amf-france.org/en/warnings/white-lists/casp/keyrock-fr-sas)
- [Deel case study - Keyrock](https://www.deel.com/case-studies/keyrock) (CDP)
- [Glassdoor - Keyrock overview](https://www.glassdoor.com/Overview/Working-at-Keyrock-EI_IE1937140.11,18.htm) (CDP)
- [Glassdoor - Keyrock reviews (English filter)](https://www.glassdoor.de/Bewertungen/Keyrock-Bewertungen-E1937140.htm?filter.iso3Language=eng) (CDP)
- [Glassdoor - Keyrock interviews](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/Keyrock-Fragen-im-Vorstellungsgespr%C3%A4ch-E1937140.htm) (CDP)
- [Glassdoor - Keyrock salaries](https://www.glassdoor.de/Gehalt/Keyrock-Gehälter-E1937140.htm) (CDP)
- [Glassdoor - Rust Engineer Dream review](https://www.glassdoor.com.au/Reviews/Employee-Review-Keyrock-E1937140-RVW101132884.htm)
- [Glassdoor - Quantitative Trader review](https://www.glassdoor.ie/Reviews/Employee-Review-Keyrock-E1937140-RVW99882706.htm)
- [Kununu - search Keyrock](https://www.kununu.com/de/search?q=Keyrock) (CDP; no results)
- [Teamblind - Keyrock](https://www.teamblind.com/company/Keyrock) (CDP; page not found)
- [levels.fyi - Keyrock salaries](https://www.levels.fyi/companies/keyrock/salaries) (CDP)
- [levels.fyi - Keyrock Software Engineer](https://www.levels.fyi/companies/keyrock/salaries/software-engineer) (CDP)
- [TrueUp - Keyrock](https://trueup.io/co/keyrock-crypto)
- [The Block - SC Ventures, Ripple back Keyrock's Series C](https://www.theblock.co/post/395769/sc-ventures-ripple-keyrock-series-c-1-1-billion-valuation)
- [Cointelegraph - Keyrock $1.1B valuation](https://cointelegraph.com/news/crypto-market-maker-keyrock-1-1b-valuation-sc-ventures-funding)
- [tech.eu - Keyrock hits unicorn status](https://tech.eu/2026/03/31/belgium-crypto-startup-keyrock-hits-unicorn-status-says-valuation-quadrupled/)
- [FinTech Global - Keyrock Series C](https://fintech.global/2026/03/31/keyrock-secures-series-c-funding-at-1-1bn-valuation/)
- [SC Ventures - Keyrock Series C](https://scventures.io/keyrock-secures-series-c-funding-from-sc-ventures/)
- [The Block - Keyrock closes BlockFills deal](https://www.theblock.co/post/408639/keyrock-closes-deal-blockfill-institutional-trading-brokerage-assets)
- [Crowdfund Insider - BlockFills integration](https://www.crowdfundinsider.com/2026/07/292460-keyrock-strengthens-institutional-digital-assets-trading-capabilities-with-blockfills-integration/)
- [Cooley - Keyrock acquires BlockFills assets](https://www.cooley.com/news/coverage/2026/2026-07-20-keyrock-acquires-blockfills-trading-and-brokerage-assets)
- [BTC-Echo - Keyrock erhält MiCA-Lizenz](https://www.btc-echo.de/schlagzeilen/keyrock-erhaelt-mica-lizenz-fuer-gesamte-eu-232520/)
- [CoinDesk (mirror) - Keyrock launches US entity](https://cryptonewz.pages.dev/crypto-news-coindesk.com/de/business/2025/03/18/crypto-market-maker-keyrock-launches-u-s-entity-as-regulatory-climate-set-to-improve)
- [Bitscale - Keyrock profile](https://bitscale.ai/directory/keyrock)
- [StartupHub - Keyrock](https://www.startuphub.ai/startups/keyrock.md)
- [WeAreDevelopers - Technical Lead (Rust/C++)](https://www.wearedevelopers.com/en/jobs/ext/5067431/technical-lead-rust-c)
- [WeAreDevelopers - Rust Engineer - Platform](https://www.wearedevelopers.com/en/jobs/ext/5535866/rust-engineer-platform)
- [Nejo - Keyrock SRE posting](https://mynejo.com/en-ch/job/sre-site-reliability-engineer~f3ea6aa8-ad7a-4cc4-a6e6-a00256df6d41)
- [Built In - Rust Engineer - Platform Trading](https://builtin.com/job/rust-engineer-platform-trading/7989263)
- [Indeed DE - Keyrock jobs](https://de.indeed.com/cmp/Keyrock-1/jobs)
- [The Block - GSR layoffs (peer context)](https://www.theblock.co/post/210136/crypto-market-maker-gsr-makes-further-layoffs-as-bear-market-bites)
- [Nominatim - Louizalaan 480 geocode](https://nominatim.openstreetmap.org/search?q=Louizalaan+480+Brussel&format=json&limit=1)
- [Overpass API - stops near HQ](https://overpass-api.de/api/interpreter)
- [Great Place to Work Germany](https://www.greatplacetowork.de/) (CDP; no Keyrock entry found)
