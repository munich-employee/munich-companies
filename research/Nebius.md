# Nebius - Full Research Report

_Researched: 2026-06-15_

> **Critical Disqualifiers / Cautions**
> 1. **Not profitable in the criteria sense.** Nebius is a hypergrowth, capex-heavy AI-cloud builder. FY2025 reported a small net income (~$29M) only because of one-off gains from divesting non-core stakes; Q4 2025 alone was a $249.6M net loss with $2.1B of capex. It is capital-markets-subsidized growth, not the stable, steady, no-longer-subsidized profitable employer the criteria target.
> 2. **No Munich office.** The German legal entity (Nebius GmbH) is in **Berlin** (Kurfürstendamm 11). Engineering roles are Berlin-based hybrid or "Remote - Europe." A Berlin hybrid role fails the Munich location criterion outright; only a genuinely fully-remote German contract would qualify.
> 3. **On-call risk.** This is a hyperscale cloud-infrastructure provider; backend/storage/network/SRE roles building and operating production cloud services typically carry on-call.

The technical fit (Python/Go, distributed systems, AI/ML infrastructure, profiling/optimization) is excellent, so the full report follows.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | Carve-out completed 2024 (rebranded from Yandex N.V. to Nebius Group N.V. after divesting all Russian operations). Underlying tech lineage dates to ~2013. - **borderline/young as an independent company** |
| Employees | ~1,500 globally (hundreds of engineers) - **PASS** (no minimum in criteria, ample size) |
| Revenue (FY2025) | US$529.8M (up ~351-479% YoY from ~$91-118M FY2024); ARR exiting 2025 ~$1.25B; guidance $7-9B ARR for 2026 |
| Profitability | FY2025 net income ~$29M (driven by one-off divestiture gains); Q4 2025 net loss $249.6M; deeply negative operating margin; $2.1B Q4 capex - **FAIL** (not steadily profitable) |
| Ownership | Public - Nasdaq: **NBIS**, incorporated in the Netherlands (Amsterdam HQ). NVIDIA agreed to invest $2B; large institutional backing |
| Software-centric | Full-stack AI cloud platform (IaaS/PaaS for AI training and inference) - **PASS** (software/infrastructure is the product) |

**Key People:** Arkady Volozh (CEO, Yandex co-founder); John Boynton (Chairman).

**Business Model:** Vertically integrated AI cloud provider. Builds and operates its own data centers and servers (NVIDIA Hopper/Blackwell + InfiniBand) and sells GPU compute, managed Kubernetes, managed PostgreSQL, storage, and AI/ML platform services to AI developers and enterprises across Europe and the US. Revenue is recurring cloud consumption, not project/consulting billing.

**Software-Centric Assessment:** Clear PASS. Differentiating software (the cloud control plane, virtualization, storage, scheduling, MLOps tooling) is integral to strategy. Not consulting-adjacent: no client-billed hours, no consultant career track, engineers build an internal product platform consumed by external customers as a service.

---

## Section 2: Local Commercial Entity

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **Nebius GmbH** | Amtsgericht Charlottenburg (Berlin) **HRB 155425 B** | Kurfürstendamm 11, 10719 Berlin | "The development of computer-aided technology programs, products and applications" (software development) |

**Verification:** The registered corporate purpose confirms genuine engineering/software-development activity (not a sales/distribution shell). The entity has a real lineage: registered 2013 as Yandex.Technology GmbH, renamed DoubleCloud GmbH (2022), now Nebius GmbH, with annual filings 2013-2023. German engineering roles run through this Berlin entity. There is **no Munich entity or office**.

**Verdict:** **PASS** as a genuine German engineering entity - but it is in **Berlin, not Munich**, which drives the location problem below.

---

## Section 3: Location

- **Office address:** Kurfürstendamm 11, 10719 Berlin (Charlottenburg). Global HQ is Amsterdam; further R&D hubs across Europe, UK, North America, and Israel.
- **Nearest public transit (Berlin office):** U-Bahn Kurfürstendamm (U1/U9) / Uhlandstraße - central West Berlin, well connected.
- **Work model:** Hybrid is the norm (typically 1-2 days WFH; a few teams allow more). Some roles are advertised explicitly as "Remote - Europe." A fully-remote German contract through Nebius GmbH would be required to satisfy the location criterion.

---

## Section 4: Reviews

**GPTW:** No Great Place to Work certification found for Nebius in Germany (or elsewhere). As a 2024 carve-out with a small German footprint, it does not appear in German GPTW listings. **No GPTW signal.**

#### Glassdoor

Only a global aggregate is meaningful; review volume is too low (46 total) to break out by country, city, or SWE title. Country/city/SWE-specific filters yield too few reviews to report reliably.

| Metric | Global | Candidate's Country | Candidate's City | Senior Software Engineers |
|---|---|---|---|---|
| **Overall** | 4.2 (46 reviews) | n/a (too few) | n/a (too few) | n/a (too few) |
| **WLB** | 3.2 | - | - | - |
| **Culture & Values** | 3.7 | - | - | - |
| **Comp & Benefits** | 4.3 | - | - | - |
| **Career Opportunities** | 4.1 | - | - | - |
| **Diversity & Inclusion** | UNKNOWN | - | - | - |
| **% Recommend** | 80% | - | - | - |
| **CEO Approval** | UNKNOWN | - | - | - |
| **Business Outlook** | 91% positive | - | - | - |

**Verdict:** **PASS (global)** on the 4.0 threshold (4.2), but treat as **directional only** - 46 reviews is a thin sample and there is no Germany/Munich/SWE breakout. The WLB sub-score (3.2) is a soft flag.

#### Kununu

Fetched via curl (WebFetch blocked). The Nebius slug returned **0 reviews** - Nebius has effectively no German Kununu footprint, consistent with a small, recently-rebranded Berlin entity.

- **Overall score:** UNVERIFIED (no reviews)
- **Recommendation rate:** UNVERIFIED
- **Total reviews:** 0
- **Kununu Top Company:** No

The Kununu threshold from the criteria **cannot be applied** (no data). This is itself a mild negative: no independent German-employee sentiment signal exists.

#### Predecessor-Entity Reviews (Yandex / DoubleCloud, Germany, pre-carve-out)

Nebius GmbH is the same Berlin legal entity as Yandex.Technology GmbH (2013-2022) and DoubleCloud GmbH (2022-2024), so the pre-carve-out German reviews of those names are the closest thing to a longer track record. All fetched 2026-11-13 over CDP with the logged-in browser.

**Glassdoor: Yandex (EI 218706), location filter Deutschland.** glassdoor.de applies a review-language filter by default, so the Germany view shows 1 review unfiltered but 6 with `filter.iso3Language=eng`; 7 distinct reviews in total (6 English, 1 German), dated 2015-2022. The second "YANDEX" employer page (EI 5335821, 296 reviews) has no German-located reviews.

| Metric | Yandex, Germany (Glassdoor) |
|---|---|
| Reviews | 7 (Berlin 6, Munich 1); 4 tagged Software Engineer / Frontend |
| Star ratings | 5, 5, 5, 5, 4, 4, 2 (mean 4.3) |
| Headline shown by Glassdoor | 4.8, 100% recommend, sub-scores 4.4-5.0 |

The headline 4.8 does not match the individual ratings (it includes a 2-star review yet shows 100% recommend), so the sub-scores are not reliable; treat the star list as the data. Sample is far too small for a verdict, directional only.

Quotes:
- "Amazing colleagues who are really experienced professionals. Top management is really good in planning and problem solving." / Cons: "You can't work from Europe and it may be cons for somebody" (Glassdoor, Feb 2022, current Senior Frontend Engineer, Berlin)
- "Complicated deployment process, some internal processes are not very well adapted for English-speakers. Software development practices vary between the teams." (Glassdoor, Oct 2015, current Software Engineer (C++), Berlin, less than 1 year)
- "A lot of bureaucracy and processes" (Glassdoor, Sep 2021, current Software Engineer, Berlin, 8+ years)
- "not the best people mannagment" [sic], 2 stars (Glassdoor, Jun 2021, former Software Engineer (C++), Berlin)
- "interesting work and good management" (Glassdoor, Nov 2020, current IT Programmer/Analyst, München)

**Kununu: DoubleCloud (slug `doublecloud2`, Berlin).** kununu Score 4.8, 100% recommendation, 3 employee reviews (7 entries overall), all Oct-Nov 2022, i.e. the launch phase of the spin-off. Fetched over CDP (curl gets HTTP 405).

- "Wie bei einem StartUp üblich sind viele Aufgaben zu erledigen und der Job ist nie vorbei. Allerdings [...] auch im Urlaub wird man nicht gestört (wie es sein soll!)" (Kununu, Nov 2022, Angestellte/r oder Arbeiter/in, IT, Berlin)
- "Kommunikation ist sehr transparent, als internationales Unternehmen aber ist englisch Pflicht!" (same review); it also describes DoubleCloud as "Remote first", with most staff working from home.
- 4.9 stars, "Fully Remote - Flexible Hours - Coworking space benefit" (Kununu, Nov 2022, Angestellte/r oder Arbeiter/in, Marketing / Produktmanagement, Berlin)

The Kununu `yandex` profile (1 review, Stuttgart, 2018) is not the Berlin entity and is ignored.

**Read-across to Nebius:** the German predecessor reviews are mildly positive (colleagues, interesting large-scale problems, transparent English-language communication) and repeat two themes from the current Nebius reviews: bureaucracy/processes not fully adapted to non-Russian speakers (matches "not really international") and a startup-style "job is never over" intensity (matches WLB 3.2). Nothing indicates toxic leadership. Caveats: 10 reviews across 11 years, mostly written before the 2022-2024 restructuring, and DoubleCloud's "remote first" set-up says nothing about Nebius's current hybrid policy.

#### Blind / Teamblind

No Nebius-specific Blind company page or reviews surfaced. Coverage is absent (Blind skews US-tech and Nebius is small/new). **UNVERIFIED.**

#### Review Themes (2024-2026)

**Positives:**
- Strong compensation and benefits (Glassdoor Comp 4.3).
- Talented colleagues, interesting cutting-edge AI-infrastructure problems.
- Positive business outlook (91%) - employees see strong growth momentum.

**Negatives:**
- Work-life balance is the recurring complaint (Glassdoor WLB 3.2; at least one review titled "Worst work-life balance"). Consistent with a fast-scaling, capex-and-deadline-driven hyperscaler.
- A review flagged the company as "not really international" - possible cultural carryover from its Yandex origins.
- Thin overall sample - themes are directional, not robust.

#### Toxic Leadership Assessment

| Pattern | Nebius |
|---|---|
| Toxic leadership as pattern | No clear systemic signal (sample too small) |
| 24/7 work expectation | Not evidenced as policy; WLB complaints suggest high intensity |
| Surveillance culture | No evidence |
| Fear-driven management | No evidence |
| Employee autonomy | No clear signal; engineering-heavy culture implied |
| Communication breakdown | Some mixed-interview / "not really international" comments |
| Unpaid overtime | Not specifically evidenced; WLB pressure noted |

**Risk level: LOW-MODERATE.** No systemic toxicity evidence, but a thin review base plus consistent WLB pressure in a hyper-scaling environment warrants caution rather than a clean pass.

---

## Section 5: Compensation

#### levels.fyi Data

Data is Nebius-wide (Amsterdam-weighted); Germany/Berlin-specific points are sparse, so treat as directional for a German contract.

| Level | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| G16 | Software Engineer (mid) | ~€80-90K | varies | varies | ~€98.8K median (range €80.6K-€133K) | few |
| G17 | Software Engineer (senior) | ~€120-150K | RSUs (NBIS) | varies | ~€157.7K median (range €125K-€182K+) | few |

For reference, levels.fyi puts the typical German senior SWE band at ~€80.6K-€114.3K. Nebius G17 (~€158K median TC) sits **well above** that band.

#### Equity / Stock

Public company (Nasdaq: NBIS). Compensation includes RSUs in a listed, liquid stock - a genuine equity component (unlike pre-IPO option lottery tickets). NBIS has been highly volatile, so RSU value carries market risk, but it is real and tradable.

#### Verdict

**PASS (BORDERLINE on data confidence).** Senior-level total comp (~€155-160K) comfortably exceeds the local large-profitable-corporate bracket for Munich/Germany seniors. The caveat is that the data points are few and Amsterdam-weighted; a German remote contract should be confirmed during the process.

---

## Section 6: AI/ML & Tech Stack Fit

#### AI Strategy

Genuine, deep AI investment - this is the company's entire reason to exist. Nebius builds and operates large NVIDIA GPU clusters (Hopper/Blackwell + InfiniBand) and a full AI cloud: managed Kubernetes, managed PostgreSQL, distributed storage, plus AI/ML platform/MLOps tooling for training and inference. NVIDIA's $2B investment and the 5GW compute roadmap underline that this is real applied AI-infrastructure engineering, not "AI" marketing veneer.

#### Tech Stack (from job postings)

| Category | Technologies |
|---|---|
| **Primary language(s)** | **Python** (primary in backend postings), **Go** (strong plus / required on some teams) |
| **AI/ML** | GPU cloud (NVIDIA H100/H200/Blackwell), training & inference platform, MLOps tooling |
| **Cloud** | Own vertically-integrated cloud (IaaS/PaaS); data centers in EU and US |
| **Infrastructure** | Kubernetes, distributed fault-tolerant systems, virtualization, storage systems |
| **Data** | Managed PostgreSQL, distributed storage; high-throughput services |
| **Other** | Rust appears in some systems/infra contexts (lineage includes Rust-heavy infra); InfiniBand/networking |

Source: Nebius careers postings (Senior/Staff Backend Engineer, Storage Virtualization, Hardware Infrastructure, Managed PostgreSQL, Managed Kubernetes) plus aggregator listings.

**Language match:** **PASS.** Python is the stated primary backend language; Go is a strong plus; Rust appears in systems contexts. No C/C++ embedded focus in the software roles.

#### Current Open Roles

| Role | Division/Team | Level | Key Tech | Fit? |
|---|---|---|---|---|
| Senior/Staff Software Engineer (Backend) | Cloud services | Senior/Staff | Python (Go a plus), distributed systems | **Strong fit** |
| Senior Backend Engineer (Storage Virtualization) | Storage | Senior | Distributed fault-tolerant storage, Python/Go | **Strong fit** (Remote-Europe advertised) |
| Senior Software Engineer (Managed PostgreSQL for AI) | Data platform | Senior | Python/Go, Postgres, K8s | **Good fit** |
| Staff Software Engineer (Hardware Infrastructure) | DC/HW lifecycle | Staff | Python or Go | **Partial** (hardware/data-center-lifecycle adjacency; verify scope is software, not embedded/HW) |
| Senior Network Engineer | Networking | Senior | Networking/InfiniBand | **Exclude** (network engineering, not the backend/AI-ML SWE track) |
| SRE roles | Reliability | Senior | K8s, ops | **Exclude** (SRE = on-call by definition) |

**Verdict:** **PASS (technical).** Python-centric backend/distributed-systems engineering on a self-built AI cloud, with Go and Rust in the mix and deep production AI/ML-infrastructure work (GPU scheduling, storage, MLOps). This is applied production engineering, not research, and aligns strongly with Python, Rust/Go, profiling and optimization, productionizing AI/ML, distributed cloud platforms, prior multi-tenant IIoT-on-AWS and ML-tooling/infrastructure experience. The hardware-infrastructure role needs scope-checking to ensure it is software (not embedded/electronics); SRE/network roles are excluded.

---

## Section 7: Language

English is the working language: job postings are in English, the team is multinational across EU/UK/North America/Israel, and no posting requires German for engineering. One reviewer's "not really international" comment may reflect a Russian/Yandex cultural heritage, but operationally English is the engineering language.

**Verdict:** **PASS.**

---

## Section 8: Stability

#### Financial Position

- FY2025 revenue ~$529.8M (up ~351-479% YoY).
- FY2025 net income ~$29.0M - but materially inflated by one-off gains on divesting non-core assets (e.g., ClickHouse, Toloka, Avride stakes); core operations are loss-making.
- Q4 2025: revenue $227.7M (+547% YoY) yet net loss $249.6M; capex $2.1B in the quarter for H200/Blackwell GPUs.
- Total assets ~$12.45B; total equity ~$4.6B.
- ARR ~$1.25B exiting 2025; guidance $7-9B ARR for 2026.
- NVIDIA agreed to invest $2B; broad institutional backing; large convertible/raise activity.

So: **not profitable** (FAIL on the profitability criterion), but **financially very well-capitalized** with a marquee strategic backer.

#### Financial Runway (loss-making / capex-heavy company)

Nebius is a public company with quarterly earnings, so a bottom-up burn model is unnecessary; the relevant figures come directly from the balance sheet.

| Indicator | Value (as observed, FY2025 filings) | Note |
|---|---|---|
| Total assets | ~$12.45B | Large, asset-heavy (data centers, GPUs) |
| Total equity | ~$4.6B | Strong equity cushion |
| Strategic capital | NVIDIA $2B investment + convertible/equity raises | Active access to capital markets |
| Operating cash burn driver | Multi-billion annual capex on GPUs/data centers | Growth capex, not distress |

The "burn" here is **deliberate growth capex**, funded by strong capital-markets access and a $2B NVIDIA injection, against $1.25B ARR scaling toward a guided $7-9B. Bankruptcy/insolvency risk is **low**; the risk is strategic (execution on a very aggressive scale-up, share-price volatility affecting RSU value, dependence on continued capital access), not a near-term runway cliff.

#### Layoffs

No Nebius layoffs identified post carve-out. (Historical Yandex/DoubleCloud restructuring during the 2024 carve-out is a separate, pre-Nebius event.) **No current layoff signal.**

**Verdict:** **CAUTION.** Financially well-funded and low insolvency risk, but it fails the "stable, steady, profitable, no-longer-subsidized" intent of the criteria: it is a high-velocity, capex-intensive, loss-from-operations growth company whose strategy and headcount could shift quickly with market conditions.

---

## Section 9: Regulated Industry

Not a regulated-sector employer in the BaFin/FDA/EN-50128 sense. As a cloud provider it must meet security/compliance certifications (ISO 27001, SOC 2, GDPR, sovereignty for EU customers), but this is standard cloud compliance, not safety-critical regulatory engineering. Low practical regulatory burden on engineering.

**Verdict:** **PASS (low regulatory burden).**

---

## Section 10: On-Call

Not explicitly confirmed per role, but this is a hyperscale cloud-infrastructure provider. Backend/storage/network teams that build and **operate** production cloud services typically carry on-call rotations, and SRE roles always do. An internal-tooling/MLOps role might avoid it, but most of the open backend roles own live customer-facing infrastructure.

**Verdict:** **CAUTION (likely on-call for most relevant roles); UNVERIFIED per specific role.** Must be clarified before applying - this is a real risk against the "no regular on-call" criterion.

---

## Section 11: Interview Process

| Metric | Value |
|---|---|
| Difficulty | Moderate-to-hard (LeetCode Medium-Hard); ~3.x/5 reported |
| Positive experience | Mixed |
| Average duration | ~55 days (some report 8-9 weeks) |
| Rounds | Recruiter call → coding (DS&algorithms) → system design → hiring manager |

The process is **LeetCode-heavy** (Medium-Hard, array/string emphasis) plus a system-design round. This is a coding-puzzle-centric process rather than purely experience/design-focused - a senior candidate with two decades of production experience would need deliberate LeetCode preparation. Candidate experiences are mixed (some smooth, some report unclear requirements and long gaps).

---

## Section 12: Summary Assessment

| Criterion | Result |
|---|---|
| Software-centric | **PASS** (full-stack AI cloud platform; software is the product) |
| Not consulting | **PASS** (recurring cloud consumption, no client-billed hours) |
| Profitable | **FAIL** (loss from operations; FY2025 net income only via one-off divestiture gains; Q4 net loss $249.6M) |
| Employee count | **PASS** (~1,500 globally) |
| English-speaking | **PASS** |
| Local entity + engineering contracts | **PASS but Berlin** (Nebius GmbH, HRB 155425 B, Amtsgericht Charlottenburg) - no Munich entity |
| Location / work model | Berlin office (~500 km from Munich) hybrid; fully-remote German role only possibility |
| Glassdoor | **PASS (directional)** (4.2 global, 46 reviews; no DE/Munich/SWE breakout) |
| Kununu | **UNVERIFIED** (0 reviews for Nebius; predecessor DoubleCloud 4.8 on 3 reviews from 2022, directional only) |
| Salary | **PASS (borderline data confidence)** (G17 senior ~€158K median TC, above local senior band) |
| AI/ML content | **PASS** (deep applied AI-infrastructure; GPU cloud, MLOps, NVIDIA-backed) |
| Computer-language-primary | **PASS** (Python primary; Go strong plus; Rust in systems contexts) |
| No on-call | **CAUTION / likely FAIL** (cloud-infra operational roles typically on-call; UNVERIFIED per role) |
| WLB / Stability | **CAUTION** (WLB 3.2; capex-heavy hypergrowth; well-funded but not steady-state) |
| Regulated industry | **PASS** (standard cloud compliance only) |
| Toxic leadership risk | **LOW-MODERATE** |

---

## Section 13: Verdict

**Overall recommendation: Monitor, do not actively pursue as a primary target - pursue only on a specific fully-remote German-contract role with on-call explicitly excluded.**

**Strengths.** The technical fit is one of the best in the search set: Python-primary backend/distributed-systems work on a self-built AI cloud, with Go and Rust in play, deep production AI/ML-infrastructure (GPU scheduling, storage virtualization, MLOps, profiling/optimization), English working language, senior comp well above the local band, a genuine German engineering entity, and standard (low) regulatory burden. The work itself maps almost perfectly onto the candidate's productionization-of-AI/ML and performance-optimization background.

**Hard blockers (numbered):**
1. **Location.** The German office is in **Berlin** (Kurfürstendamm 11), ~500 km from Munich. Berlin hybrid roles fail the Munich location criterion outright. Only a confirmed **fully-remote (Remote - Europe) role on a German contract through Nebius GmbH** can satisfy this.
2. **Profitability.** The company is not profitably self-sustaining: operating losses, Q4 2025 net loss of $249.6M, FY net income positive only because of one-off asset-sale gains, multi-billion capex funded by capital raises and a $2B NVIDIA investment. This fails the "profitable, no-longer-subsidized, stable steady strategy" criterion - the business model is high-velocity, capital-intensive hypergrowth.

**Secondary concerns (aggregate):**
- **On-call** is likely for most relevant backend/infra roles and must be ruled out per role (criterion: no regular on-call).
- **WLB** sub-score (3.2) and a thin, mostly-positive-but-mixed review base; **no Kununu/Blind/GPTW** signal for Nebius itself. Pre-carve-out German reviews of the same entity (Yandex Glassdoor Germany, 7 reviews, mean 4.3; DoubleCloud Kununu 4.8 on 3) are mildly positive but echo the bureaucracy, English-adaptation and intensity themes.
- **Interview** is LeetCode-heavy (Medium-Hard), requiring deliberate prep.
- **Share-price volatility** affects the (real, liquid) RSU component.

**Recommendation sentence.** Keep Nebius on the watchlist for its outstanding technical alignment, but only convert to an application if a **fully-remote German-contract senior/staff backend or AI-platform role with no on-call** appears - in which case verify, during the process: (a) remote eligibility and a direct German Arbeitsvertrag via Nebius GmbH (not EOR/contractor), (b) explicit on-call expectations for the specific team, (c) the German/Berlin-adjusted salary band, and (d) WLB realities given the hypergrowth phase. Absent a fully-remote, no-on-call role, the Berlin-hybrid + not-profitable combination makes it a pass.

---

## Sources

- [Nebius - About](https://nebius.com/about)
- [Nebius - Careers](https://nebius.com/careers)
- [Nebius - Careers portal (open roles)](https://careers.nebius.com/)
- [Nebius - AI Cloud](https://nebius.com/ai-cloud)
- [Nebius - Backend interview guide](https://nebius.com/careers/interviews/backend)
- [Nebius - SRE interview guide](https://nebius.com/careers/interviews/sre)
- [Nebius Group - Wikipedia](https://en.wikipedia.org/wiki/Nebius_Group)
- [Nebius Group - Crunchbase](https://www.crunchbase.com/organization/nebius)
- [Nebius Group - PitchBook](https://pitchbook.com/profiles/company/11445-49)
- [Nebius Group - Tracxn](https://tracxn.com/d/companies/nebius/__GZURgWq1TUMSTdnbaT_Xc6TjA8v2qxjGlfBMAlN6xs8)
- [Nebius Group - Simply Wall St](https://simplywall.st/stocks/us/software/nasdaq-nbis/nebius-group)
- [Nebius Group (NBIS) revenue - StockAnalysis](https://stockanalysis.com/stocks/nbis/revenue/)
- [Nebius Group (NBIS) - WallStreetZen revenue](https://www.wallstreetzen.com/stocks/us/nasdaq/nbis/revenue)
- [Nebius Group N.V. - SEC FY2025 6-K filings](https://www.sec.gov/Archives/edgar/data/0001513845/000110465925015480/tm257185d1_ex99-1.htm)
- [Nebius Group - Form 20-F FY2025 (SEC)](https://www.sec.gov/Archives/edgar/data/1513845/000110465926052948/nbis-20251231x20f.htm)
- [Nebius Q4 & FY2025 results - Alpha Spread](https://www.alphaspread.com/market-news/earnings/nebius-group-reports-q4-and-2025-financial-results-focuses-on-ai-cloud-expansion)
- [NVIDIA invests $2 billion in Nebius - TNW](https://thenextweb.com/news/nvidia-invests-2-billion-in-nebius)
- [Nebius GmbH, Berlin - NorthData](https://www.northdata.com/Nebius%20GmbH,%20Berlin/Amtsgericht%20Charlottenburg%20(Berlin)%20HRB%20155425%20B)
- [Nebius - Glassdoor overview](https://www.glassdoor.com/Overview/Working-at-Nebius-EI_IE8479624.11,17.htm)
- [Nebius - Glassdoor reviews](https://www.glassdoor.com/Reviews/Nebius-Reviews-E8479624.htm)
- [Nebius - Glassdoor interview questions](https://www.glassdoor.com/Interview/Nebius-Software-Engineer-Interview-Questions-EI_IE8479624.0,6_KO7,24.htm)
- [Nebius Salaries - Levels.fyi](https://www.levels.fyi/companies/nebius/salaries)
- [Nebius G17 Software Engineer - Levels.fyi](https://www.levels.fyi/companies/nebius/salaries/software-engineer/levels/g17)
- [Nebius G16 Software Engineer - Levels.fyi](https://www.levels.fyi/companies/nebius/salaries/software-engineer/levels/g16)
- [Senior SWE salary in Germany - Levels.fyi](https://www.levels.fyi/t/software-engineer/levels/senior/locations/germany)
- [Senior SWE (Storage Virtualization), Remote - Arbeitnow](https://www.arbeitnow.com/jobs/companies/nebius/remote-senior-software-engineer-storage-virtualization-team-364385)
- [Senior Network Engineer, Berlin/Remote-Europe - aijobs.net](https://aijobs.net/job/1085760-senior-network-engineer/)
- [Senior Backend Engineer (Remote-Europe) - Himalayas](https://himalayas.app/companies/nebius/jobs/senior-backend-engineer)
- [Nebius interview experiences - JoinTaro](https://www.jointaro.com/interviews/companies/nebius/experiences/senior-software-engineer-amsterdam-february-1-2025-no-offer-negative-99ac2a65/)
- [Nebius - Kununu (0 reviews, fetched via curl)](https://www.kununu.com/de/nebius)
- [Yandex - Glassdoor reviews, Germany, English (CDP)](https://www.glassdoor.de/Bewertungen/Yandex-Deutschland-Bewertungen-EI_IE218706.0,6_IL.7,18_IN96.htm?filter.iso3Language=eng)
- [Yandex - Glassdoor reviews, Germany, default language (CDP)](https://www.glassdoor.de/Bewertungen/Yandex-Deutschland-Bewertungen-EI_IE218706.0,6_IL.7,18_IN96.htm)
- [DoubleCloud - Kununu reviews, Berlin (CDP)](https://www.kununu.com/de/doublecloud2/kommentare)
