# General Motors - Full Research Report

_Researched: 2026-11-03_

> **Scope note.** General Motors runs two German legal entities. **General Motors Germany GmbH** (Frankfurt) is the Cadillac sales company. **GM Munich GmbH** (Ottobrunn, Landkreis München), formerly Astyx GmbH and then Cruise Munich GmbH, is an imaging-radar R&D centre and the only GM entity in the Munich area that employs engineers. GM's own careers site (Workday) lists zero German vacancies. The Munich postings appear only on LinkedIn. This report evaluates GM as the parent company and GM Munich GmbH as the local employer.

> **Critical Disqualifiers**
> 1. **Glassdoor below a "strong" score:** 3.5 global (11,906 English reviews) and **3.2 for Software Engineers** (1,485 reviews), with Senior Management at 2.3, 41% recommend and 29% positive business outlook for software engineers. There are no meaningful Germany or Munich Glassdoor data (5 and 1 reviews).
> 2. **Repeated software/IT layoffs and stack ranking:** >1,000 software and services staff (Aug 2024), about half of Cruise's 2,300 staff (Feb 2025), >200 at the Warren Technical Center (Oct 2025), 500-600 IT staff (May 2026). Blind reviews from 2026 describe "constant layoffs" and "forced ranking". This conflicts with the "stable business strategy, long-term commitment" criterion.
> 3. **Not software-centric:** GM is an automaker. The Munich site builds radar sensor hardware, embedded DSP code and radar ML models, and about half of its current postings are hardware roles (PCB design, mechatronics).

Full report included below for completeness.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 1908 (118 years). GM Munich GmbH's predecessor (MTS Mikrowellen-Technologie und Sensoren GmbH, later Astyx) was registered in 1997 |
| Employees | ~155,000 globally (FY2025 10-K: ~88,000 hourly, ~68,000 salaried). GM Munich GmbH: **UNKNOWN**, estimated low hundreds (see Section 2) |
| Revenue (FY2024) | $187.4B. Q3 2026: $50.0B (+2.9% YoY) |
| Profitability | Net income attributable to stockholders $3.3B in Q3 2026 and $7.3B in the first nine months. FY2026 guidance $8.9-9.5B net income, $11.5-12.5B automotive free cash flow - **PASS** |
| Ownership | Public, NYSE: GM. New $20B buyback authorised in October 2026 |
| Software-centric | Vehicle manufacturer. The Munich site does sensor hardware plus embedded and ML work - **FAIL** |

### Key People

- **Mary Barra:** Chair and CEO (since 2014)
- **Sterling Anderson:** Chief Product Officer (joined mid-2025). Since late 2025 he owns vehicle engineering, global product and all software. The co-founder of Aurora Innovation, he previously led Tesla Autopilot.
- **Software leadership turnover:** Dave Richardson (SVP Software and Services Engineering) left on 31 Oct 2025. Baris Cetinok (SVP Software and Services Product) left in Dec 2025. Barak Turovsky (head of AI) also left.
- **GM Munich GmbH managing directors (NorthData):** Andrew Gunn Beck (since June 2025) and Michael Doncev (since April 2022).

### Software-Centric Assessment

GM makes and sells vehicles. Software is a strategic investment area: Super Cruise, the software-defined vehicle platform, "eyes-off" driving on the 2028 Cadillac Escalade IQ, and a personal-autonomy programme that inherited Cruise's technology and part of its staff. It is still not the product. The Munich centre's own description is "we design advanced high-resolution imaging radar sensors that power Personal Autonomous Vehicles (PAVs)". Its five current postings are:

- Senior Machine Learning Engineer (Radar & AI)
- Staff Machine Learning Engineer (Radar & AI)
- Embedded DSP Engineer (C/C++ on NVIDIA SoCs / AMD Versal)
- Mechatronics Engineer (hardware integration, CNC milling, 3D printing)
- Printed Circuit Board Designer

That is a sensor hardware company with an ML layer. Software engineers there serve a physical product. The ML roles are applied production ML, which is real AI work, but the business is not software-centric. **FAIL.**

### Consulting-Adjacency Assessment

Not applicable. GM is not a consultancy. One nuance: GM Munich GmbH's registered purpose includes "Erbringung von Ingenieurdienstleistungen" (engineering services). Its revenue (€27.7M in 2024) against a small, steady profit (€1.4M) looks like an intra-group cost-plus R&D service provider billing the US parent, not an external consulting business. Engineers build GM's own product. **PASS.**

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **GM Munich GmbH** (formerly Cruise Munich GmbH 2021-2026, Astyx GmbH 2006-2021, MTS Mikrowellen-Technologie und Sensoren GmbH) | HRB 116461, Amtsgericht München (EUID DED2601V.HRB116461) | Caroline-Herschel-Str. 2, 85521 Ottobrunn | "Entwicklung, Fertigung und Vermarktung von Hochfrequenzsensoren und die Erbringung von Ingenieurdienstleistungen für kommerzielle Anwendungen aller Art, die Entwicklung, Fertigung und Vermarktung von Soft- und Hardware und die Erbringung von Ingenieurdienstleistungen im Bereich des autonomen Fahrens und das Halten, Verwalten sowie die Veräußerung von Beteiligungen..." |
| General Motors Germany GmbH | HRB 129604, Amtsgericht Frankfurt am Main | Amelia-Mary-Earhart-Str. 8, 60549 Frankfurt am Main | "An- und Verkauf und Vertrieb von Fahrzeugen und Fahrzeugteilen, die Bereitstellung von Fahrzeugleasing, Fahrzeug-Sharing und Mobilitätsdienstleistungen in Europa..." (Cadillac Europe sales, Impressum of cadillaceurope.com) |

**Verification:** GM Munich GmbH's registered purpose explicitly covers developing and manufacturing high-frequency sensors and software/hardware for autonomous driving. It is a genuine engineering entity, not a sales shell. History:

- **2020:** Cruise acquired Astyx from ZF Friedrichshafen and the founding management.
- **28 Sep 2021:** renamed Cruise Munich GmbH.
- **26 May 2026:** renamed GM Munich GmbH, after GM folded Cruise into its own organisation.
- The NorthData network shows **GM Deutschland Holdings GmbH** as a related holding entity.

Financials filed with the Bundesanzeiger (via NorthData):

| Year | Revenue | Net result |
|---|---|---|
| 2020 | €15.7M | −€17.8M |
| 2021 | €18.1M | +€16.5M |
| 2022 | €21.0M | +€0.76M |
| 2023 | €29.3M | +€1.34M |
| 2024 | €27.7M | +€1.38M |

The thin, stable margin since 2022 fits a cost-plus R&D service arrangement with the parent. Total assets were €20.9M on the latest balance sheet NorthData shows.

The current Munich postings (LinkedIn, all "Munich, Bavaria, Germany (Hybrid)") describe "General Motors' world-class development center in Munich". They are permanent, full-time roles. There is no sign of a PEO/EOR arrangement. Postings do not name the contracting entity, but GM Munich GmbH is the only GM entity in Bavaria with an engineering purpose.

General Motors Germany GmbH (Frankfurt) is a pure sales and retail entity for Cadillac and has no engineering relevance.

**Headcount:** not disclosed in the accessible data. At €27.7M revenue with cost-plus billing and a typical €150-180K fully loaded cost per engineer, the estimate is roughly 120-180 staff. **UNVERIFIED.**

**Verdict:** PASS with CAUTION. The engineering entity is real and registered in the Munich area. The caution is that it is a small captive R&D centre whose sole customer is the US parent, so its existence depends on a single GM programme decision (see Section 8).

_Retrieval: NorthData and the Cadillac Impressum via Chromium over CDP. GM Workday via its JSON API (curl). LinkedIn postings via the in-page voyager API over CDP._

---

## Section 3: Office Location

- **Office address:** Caroline-Herschel-Straße 2, 85521 Ottobrunn (Landkreis München), outside Munich's south-eastern city boundary. Confirmed by the registry address and by OSM: Nominatim returns a "cruise" tenant object at this address (48.05263, 11.66010). Isar Aerospace is also tagged at the same building complex.
- **Nearest public transport:** bus stop **Einsteinstraße**, about 40 m from the office (straight-line), served by MVV bus lines **210 and 214** (plus 214V). Further stops:
  - Röntgenstraße, ~350 m: 210, 214
  - Lilienthalstraße, ~390 m: 210, 214, 222, 241 and X200 express
  - Marie-Curie-Straße, ~510 m: 222, 241

  OpenStreetMap shows no S-Bahn, U-Bahn or tram station within 1.5 km, so rail access needs a bus connection. _Retrieval: Nominatim for geocoding, then Overpass around (48.05263, 11.66010), retried after the main Overpass server returned 502 at capacity._
- **Work model:** Hybrid. The Munich postings state: "This role is categorized as hybrid. This means the selected candidate is expected to report to a specific location on a minimum of 3 days per week." This matches GM's corporate return-to-office policy since January 2024 (Tuesday to Thursday on site for US salaried staff). No remote option is offered for the Munich roles.

---

## Section 4: Reviews

**GPTW:** No Great Place to Work certification found for General Motors Germany GmbH, GM Munich GmbH or its predecessors (Cruise Munich, Astyx). GM Philippines holds a GPTW certification, which is not relevant to Germany.

### Glassdoor

Glassdoor (employer E279, "General Motors (GM)"). The German domain shows only German-language reviews by default (8 reviews), so all figures below use the English-language filter. All languages combined total 14,599 reviews.

| Metric | Global (English) | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | 3.5 (11,906 reviews) | 4.0 (5 reviews) | 5.0 (1 review) | 3.2 (1,485 reviews) |
| **WLB** | 3.5 | 4.9 | 3.0 | 3.8 |
| **Culture & Values** | 3.1 | 5.0 | 5.0 | 2.8 |
| **Comp & Benefits** | 3.9 | 5.0 | 4.0 | 3.7 |
| **Career Opportunities** | 3.2 | 4.0 | 5.0 | 2.9 |
| **Diversity & Inclusion** | 3.7 | 4.0 | n/a | 3.6 |
| **Senior Management** | 2.7 | 4.0 | 4.0 | 2.3 |
| **% Recommend** | 55% | 100% | 100% | 41% |
| **CEO Approval** (Mary Barra) | 47% | 100% | 100% | 30% |
| **Business Outlook** | 43% positive | 100% positive | 100% positive | 29% positive |

**The Germany and Munich filters are not usable.** The five Germany reviews date from 2012 to 2022 and come from Rüsselsheim (Opel era), Frankfurt and Berlin, all in non-engineering functions. The single Munich review (2020) is from a "Psychology" role. None comes from the Ottobrunn radar team.

The Software Engineer filter is the most relevant signal. It is clearly weaker than the global figure: Senior Management 2.3, Culture 2.8, 29% positive outlook. The most recent SWE reviews (October 2026) are friendlier (3-4 stars, "great work life balance", "slower pace"). They also note "Laid off due to closing AZ IT department" and "jumping from project to project".

The separate **Cruise** Glassdoor profile could not be reliably resolved. Search matched "Cruise.com", an unrelated company with 21 reviews.

_Retrieval: Chromium over CDP (glassdoor.de, English-language filter)._

### Kununu

No single Kununu profile covers the Munich engineering entity. Three profiles are relevant:

| Profile | Score | Recommendation | Reviews | Note |
|---|---|---|---|---|
| **Cruise LLC** (München, `cruise1`) | 4.4 / 5 | 75% | 4 (+1 applicant) | R&D and admin staff in Munich, 2022-2024 |
| **Astyx GmbH** (Ottobrunn, `astyx1`) | 3.8 / 5 | 64% | 11 employee reviews (14 total) | Predecessor entity, reviews since 2015 |
| General Motors Germany GmbH (Frankfurt, `general-motors-germany`) | 2.2 / 5 | 33% overall, 20% last 2 years | 6 | Cadillac retail/sales, not engineering |

- **Overall score for the Munich engineering site:** 3.8-4.4 / 5.0 on 4 and 11 reviews. **Directional only.**
- **Kununu Top Company:** NO (none of the profiles carries the badge)
- Opel (3.5, 590 reviews) is a Stellantis company since 2017 and is not relevant.

Two March 2022 reviews, one on the Cruise profile ("Alte Zöpfe", 2.3) and one on the Astyx profile ("Kein Glanzlicht", 1.8), are near-identical texts, apparently by the same R&D employee. Both complain about growing workload with shrinking headcount, training that was promised but never delivered, and team leads communicating less than the rumour mill. Three positive Cruise reviews (2022-2024, two from managers in R&D) praise the "Silicon Valley feeling", image and cohesion, while noting "noch etwas zu wenig Struktur".

The Frankfurt sales entity's reviews (2025) are harsh: "Sehr amerikanische Hire and Fire Mentalität", "Die allermeisten bestehen die Probezeit nicht", "Standorte werden von heute auf morgen geschlossen", "Toxischer Ja-Sager Verein, mit 80er Jahre Management Kultur". These are retail staff, not engineers, but they show how GM's US management style lands in a German subsidiary.

_Retrieval: curl returned HTTP 405 for every slug, so Kununu was read through Chromium over CDP (search pages and `/kommentare` with scrolling)._

### Blind / Teamblind

**General Motors: 3.4 / 5 (706 reviews)**

| Sub-score | Rating |
|---|---|
| Work Life Balance | 4.3 |
| Company Culture | 3.3 |
| Career Growth | 3.0 |
| Compensation / Benefits | 3.0 |
| Management | 3.0 |

Recent reviews (2026), mostly US software and engineering staff:

- "GM has taken a nosedive in so many ways--poor SLT, constant layoffs, and forced ranking just to name a few. Forced ranking has destroyed the work culture" (Software Engineer, Nov 2026)
- "The culture has been on a downward trajectory for 3 years. Endless layoffs and stack ranking make people very difficult to work with." (Electrical Engineer, Jul 2026)
- "Culture is getting worse all the time. Decisions change every 3 months it's exhausting." (Software Engineer, Apr 2026)
- "Warren SWE is mostly systems, integration, test, validation ... You don't code but debug." (Senior SWE, Apr 2026)
- "Pay has increased really well the last two years" (Staff Systems Engineer, Oct 2026)

A 2023 Blind post noted Cruise job ads for Munich/Ottobrunn with no information on Cruise's own website, the same pattern as today's GM postings.

_Retrieval: Chromium over CDP._

### Review Themes (2024-2026)

**Positives:**
- **Benefits and time off:** "Amazing benefits, huge number of holidays", strong 401k (US-specific). Comp & Benefits is the strongest Glassdoor category at 3.9.
- **Work-life balance** at team level: Blind WLB 4.3, Glassdoor SWE WLB 3.8. "Great work environment with minimal stress", "slower pace which is expected from a very big company".
- **Interesting domain** for people who like vehicles and sensors. Munich Kununu reviewers describe an attractive, "Silicon Valley feeling" job with good pay ("Bezahlung ist gut!").
- **Financial strength:** record free cash flow, buybacks, profitable core business.

**Negatives:**
- **Layoffs** are the most frequent complaint on Glassdoor and Blind in 2025-2026: "constant layoffs of tech employees", "increasingly volatile job security", "Laid off due to closing AZ IT department". **Overlaps with hard red flag: layoffs.**
- **Forced ranking / stack ranking** introduced in recent years, cited as destroying team culture. **Overlaps with fear-driven management and silent firings.**
- **Senior leadership:** Glassdoor Senior Management 2.7 global and 2.3 for SWEs. "Upper level is a joke", "poor SLT". Frequent strategy changes ("Decisions change every 3 months").
- **Career growth:** 2.9-3.2 on Glassdoor, 3.0 on Blind. "Hard to get promoted", "slow to promote".
- **Munich site specifics (2022):** workload rising while headcount falls, poor communication from team leads, promised training not delivered. **Overlaps with communication breakdown.**

### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | Corporate level: SWE Senior Management 2.3/5, CEO approval 30% among SWEs. "Poor SLT", "terrible management terrible office politics" (Blind 2026). Munich site: one 2021 Astyx review (pre-Cruise) describes "Aggressionsbewältigungstherapie, Wahrheitsverdrängung" in leadership, but that predates both acquisitions. |
| 24/7 Work Expectation | Not reported for engineering. "Little stress comes with release stress", "times with poor WLB" (team-dependent). The 6-day weeks and 12-hour shifts in Frankfurt Kununu reviews concern Cadillac retail staff. |
| Internal Surveillance | Not reported. |
| Fear-driven Management | **Yes, corporate-wide since ~2024:** forced ranking. "Managers creating narratives to justify ranking employees low while team members becoming snakes in peer review in order to survive. It's like the hunger games out here" (Blind, Nov 2026). |
| Communication Breakdown | Munich 2022: "Mehr Infos über den Flurfunk als vom Teamlead", "Viel reden aber nichts entscheiden". Corporate: frequent direction changes. |
| Unpaid Overtime | Munich 2022: "Überstunden wachsen an da es immer mehr Arbeit gibt aber die Leute eher weniger als mehr werden." No systematic evidence. |
| Silent Firings | Forced ranking functions as a performance-managed exit mechanism in the US. Frankfurt sales: "Die allermeisten bestehen die Probezeit nicht." Not evidenced for the Munich engineering site. |
| Work-Life Balance issues | Generally rated well (Blind 4.3), team-dependent. Not a primary complaint. |

**Risk level: MODERATE.**
- **(a) Systemic, corporate:** repeated tech layoffs combined with a forced-ranking performance system is a systemic pattern at GM's US software organisation. It is a deliberate HR policy, not team-level dysfunction.
- **(b) Large-company bureaucracy:** slow pace, shifting priorities and politics are typical of a 155,000-person automaker and not a disqualifier on their own.
- **(c) Localized at the Munich site:** the small review sample (2021-2024) shows a mixed picture. A start-up-like "Silicon Valley feeling" sits alongside workload and communication complaints. German employment law (Section 8) blunts the US-style ranking and exit mechanics, but only if a works council exists, which could not be verified.

---

## Section 5: Compensation

### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| levels.fyi (Cruise, Munich, May 2023) | L5 Senior Software Engineer II | ~€98K | ~€10K | €0 | ~€108K | 1 |
| levels.fyi (GM, Berlin, Dec 2024) | Software Engineer 1 | ~€120K | - | - | ~€120K | 1 (entity and role unclear) |
| levels.fyi (GM, US, for reference only) | SWE 3 (L7) / SWE 4 (L8) | €130K / €192K | €3K / €57K | €19K / €43K | €151K / €292K | 1,772 total |
| Glassdoor (Munich / Germany) | Software Engineer | UNAVAILABLE | - | - | - | 0 |

Levels.fyi needs four more Germany submissions before it shows GM averages. No Glassdoor salary data exist for GM in Germany. No Munich posting discloses a salary range.

**Munich reference** (large, profitable local employers, Senior SWE, from prior research in this project): median base ~€85-95K, 75th percentile ~€100-110K, 90th percentile ~€120-130K total compensation.

### Equity / Stock

GM is publicly traded (NYSE: GM). US salaried engineers receive RSU grants that become material from SWE 4 (L8) upward (€57K/yr). At lower levels stock is negligible (€0-3K/yr). There is a US-only salaried savings plan with company match. There is no broad ESPP.

Cruise employees held Cruise equity, which GM bought out when it took full ownership of Cruise in 2025. The single Cruise Munich data point shows ~€10K/yr stock at L5. Whether GM Munich GmbH employees receive GM RSUs after the 2026 rename is **UNVERIFIED**. The Kununu reviews mention "Bezahlung ist gut!" and "Gehalt ist Ok".

### Verdict

The only relevant Munich data point (~€108K total at Senior SWE II in 2023) sits around the 75th percentile of the Munich reference band. The sample is one data point, three years old, from the Cruise era. **COMPARABLE (UNVERIFIED).**

---

## Section 6: AI/ML & Tech Stack

### AI Strategy

GM's AI investment is real but centred on driving automation:

- **Super Cruise:** hands-free highway assist, in production.
- **Eyes-off driving:** the 2028 Cadillac Escalade IQ will get eyes-off, hands-off highway driving. It combines Super Cruise with Cruise's driverless know-how, using lidar, radar, centralised compute and redundant hardware. GM reaffirmed it at its second "GM Forward" event in October 2026.
- **Personal Autonomous Vehicles (PAVs):** the stated purpose of the Munich radar centre.
- **AI talent shift:** the May 2026 IT layoffs were explicitly framed as replacing traditional IT roles with AI infrastructure and model training talent.
- **Leadership churn:** GM's head of AI and two software SVPs left in late 2025.

The Munich work is genuine applied ML:

- radar perception models trained in PyTorch
- data pipelines in Spark
- synthetic radar data generation
- AI-driven validation frameworks
- resource-aware deployment onto the vehicle

It is not "AI" as a marketing word. It is closer to sensor ML/perception than to LLM, platform or MLOps work, and it requires "strong experience in radar signal processing".

### Tech Stack

Derived from the five current GM Munich postings on LinkedIn (October 2026). GM's own careers site has no German postings. Secondary sources: GM Munich GmbH patent filings on NorthData (imaging radar, MIMO and polarimetric radar, 3D radar object detection), and public reporting on Cruise's 2021 Microsoft Azure partnership.

| Category | Technologies |
|---|---|
| **Primary language(s)** | Python (ML roles), C/C++ (embedded DSP roles), MATLAB (algorithm prototyping) |
| **AI/ML** | PyTorch, NumPy, Pandas, multi-modal sensor fusion (camera, radar, lidar), perception pipelines, synthetic data generation, model validation and error analysis |
| **Cloud** | Not named in the postings. Cruise historically used Microsoft Azure as its preferred cloud (2021 partnership) - **UNVERIFIED** for GM Munich today |
| **Infrastructure** | NVIDIA SoCs (vehicle compute), AMD Versal (adaptive SoC), CUDA, Linux, CI, Jira |
| **Data** | Apache Spark, large-scale data workflows and training pipelines |
| **Other** | Radar hardware: high-frequency PCB design, mechatronics, CNC prototyping, metrology, environmental testing |

**Summary:** A polyglot site. Python for radar ML and data tooling (PyTorch, NumPy/Pandas, Spark), C/C++ and CUDA for embedded radar signal processing on NVIDIA and AMD Versal SoCs, and a substantial hardware engineering group. Applied, production-bound perception ML for autonomous driving in a sensor-hardware R&D context, not research and not a cloud product.

---

## Section 7: Language

All GM Munich postings are written in English. The DSP posting asks for "Good communication skills in English; You should be able to work effectively in a cross-functional, international team". The Mechatronics posting requires "Creating technical documents and reports in english language". No posting asks for German. The ML roles require regular alignment with "the GM-US team". The Kununu reviews of the Cruise-era site are in German, so German is spoken socially, but English is the working language with the US parent.

**Verdict:** PASS

---

## Section 8: Stability

### Financial Position

- **Q3 2026** (reported 20 Oct 2026): revenue $50.0B (+2.9%), net income attributable $3.34B (vs $1.33B), EBIT-adjusted $4.1B (+21.6%), adjusted automotive free cash flow $5.9B.
- **Guidance:**
  - FY2026 guidance raised: net income $8.9-9.5B, EBIT-adjusted $14.5-15.5B, automotive FCF $11.5-12.5B.
  - New $20B multi-year buyback after completing a $6B programme.
  - Shares fell ~6.8% after the report on doubts about 2027 momentum.
- **Headwinds:**
  - EV strategic realignment charges: $7.9B in 2025 and $3.6B in the first nine months of 2026.
  - Possible further restructuring charges in China.
  - Cruise's wind-down costs now sit inside GMNA.
- **Trend:** improving. The parent is clearly profitable with large cash generation. Not loss-making or VC-backed, so no runway model is needed.
- **GM Munich GmbH:** profitable every year since 2021 (€1.4M in 2024) on intra-group revenue. Its financial health is entirely a function of GM's continued funding of the in-house radar programme.

### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| Aug 2024 | Software and Services division cuts | >1,000 globally, ~600 at Warren Tech Center | After a review of the software organisation |
| Dec 2024 | Cruise robotaxi programme ended | Programme closure | GM stopped funding Cruise's robotaxi business and folded it into personal-autonomy work |
| Feb 2025 | Cruise layoffs | ~50% of Cruise's ~2,300 staff | A GM spokesperson told electrive the **Munich site was not affected** |
| Oct 2025 | Warren Technical Center cuts | >200 salaried | Mostly engineering/tech |
| Late 2025 | Software leadership overhaul | SVP Software Engineering, SVP Software Product and head of AI left | Consolidated under the CPO |
| May 2026 | IT reorganisation | 500-600 IT roles (>10% of IT) | Austin, Warren and Arizona (Chandler IT office closed). Framed as a skills swap towards AI talent |
| 2025-2026 | EV-related production cuts | Thousands of hourly workers (US plants) | Not engineering, but part of the same EV strategy reset |

No layoffs at the Munich/Ottobrunn site were found. The site was explicitly spared in Feb 2025 and is hiring in October 2026. Each rename (Astyx to Cruise Munich in 2021, Cruise Munich to GM Munich in 2026) followed a strategic change at the parent. The site's survival through the Cruise shutdown shows that GM values its radar capability. But a captive centre whose only customer is the US parent can be closed by a single programme decision, as the US Cruise sites were.

### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | **UNKNOWN** | No mention in any Kununu review of Astyx, Cruise Munich or GM Germany. Web searches for "Astyx / Cruise Munich / GM Munich Betriebsrat Ottobrunn" found nothing. No LinkedIn evidence found. |
| Collective agreement | **Probably NONE** | A 2021 Astyx review compares pay unfavourably to the metal-industry tariff: "Im Vergleich: IG mit 35 h/W wird für die Meisten sich mehr lohnen", which implies the company was not IG Metall-bound. No posting mentions "Tarif". |
| European works council (multinationals) | N/A in practice | GM's European Employee Forum was tied to Opel/Vauxhall, which were sold to PSA (now Stellantis) in 2017. GM's remaining European headcount is small. |
| Conflict signals | None found | |

With an estimated 120-180 staff, a works council is legally possible but unconfirmed. The site sits outside any sector tariff. Given GM's US forced-ranking regime and recent layoff history, whether a Betriebsrat exists matters a lot. It is the main protection against individual push-outs (§102 BetrVG), and it would make any closure a negotiated social plan (§§111-112 BetrVG).

**Verdict:** CAUTION. The parent is strong financially, but the local entity is a small captive R&D centre, the parent has a 2024-2026 pattern of repeated tech layoffs and stack ranking, and no works council or collective agreement could be confirmed.

---

## Section 9: Regulated Industry

Automotive, with safety-critical driver-assistance and autonomous driving:

- **Functional safety:** ISO 26262
- **SOTIF:** ISO 21448
- **UNECE regulations:** R155 (cybersecurity), R156 (software updates), R157 (ALKS) for European homologation
- **US:** NHTSA oversight; FMVSS and the standing general order on ADS/ADAS crash reporting
- **Radar spectrum:** 77-81 GHz type approval (the Frankfurt entity's purpose explicitly includes "Tests, Typengenehmigungen und Zulassungen")

The Munich postings emphasise "the highest standards of safety", "safety targets" and "production readiness". Expect documentation overhead, formal verification and validation, and slow hardware-bound release cycles, especially for the embedded roles. The ML roles sit somewhat upstream, but their models feed a safety case.

**Verdict:** CAUTION

---

## Section 10: On-Call

None of the five Munich postings mentions on-call, standby or incident rotation. The work is sensor R&D, embedded signal processing and offline ML training/validation, with no customer-facing SaaS service to keep alive. Pressure comes from "release stress", hardware bring-up and vehicle test campaigns rather than pager duty. Vehicle test campaigns can involve occasional off-hours work, which is not evidenced.

**Verdict:** PASS (UNVERIFIED, confirm in interview)

---

## Section 11: Interview Process

Based on Glassdoor (English-language reviews, global, mostly US/Canada/Ireland). No interview reviews exist for the Munich site.

| Metric | Value |
|---|---|
| Difficulty | 2.5 / 5 for Software Engineers (423 ratings). 2.8 / 5 overall (3,162 ratings) |
| Positive experience | 71% Software Engineers (8% negative). 68% overall (13% negative) |
| Average duration | **UNKNOWN** (Glassdoor did not render an average). Candidate reports range from ~2 weeks to several months |
| Rounds | 3-4 |

**Typical steps:**
1. Recruiter screen (~30 min). GM uses an AI scheduling assistant, and candidates receive an "interview toolkit" explaining the STAR behavioural format.
2. Online coding assessment (Codility or similar). Some teams use a take-home algorithmic task (Ireland).
3. One to three technical rounds (~45 min each): coding (LeetCode easy/medium, string manipulation), debugging an existing codebase, and system design and DevOps for senior roles.
4. Hiring-manager / panel round, sometimes with a director and two senior engineers.

The process is moderate, not LeetCode-heavy, with strong STAR behavioural weighting. "More focused on behavioral, not as much technical depth as other companies." For the Munich radar ML roles, expect domain depth (radar signal processing, perception metrics, sensor fusion) to matter more than algorithm puzzles, and likely an interviewer from the US perception team.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | FAIL: automaker. The Munich site is a radar sensor hardware and ML R&D centre |
| Not consulting | PASS: captive intra-group R&D, own product |
| Profitable | PASS: ~$9B 2026 net income guidance, $11.5-12.5B automotive FCF |
| Employee count | ~155,000 globally. GM Munich GmbH estimated ~120-180 (unverified) |
| English-speaking | PASS: English postings, no German requirement |
| Local entity + engineering contracts | PASS with CAUTION: GM Munich GmbH, HRB 116461, Ottobrunn, engineering purpose; small captive centre |
| Location / work model | Ottobrunn (Landkreis München), hybrid with a minimum of 3 days/week on site |
| Glassdoor | FAIL: 3.5 global, 3.2 SWE (1,485 reviews), Senior Management 2.3 for SWEs. No usable Germany/Munich data |
| Kununu | Directional only: Cruise Munich 4.4 (4 reviews), Astyx 3.8 (11 reviews), Frankfurt sales entity 2.2 (6 reviews). No Top Company |
| Salary | COMPARABLE (UNVERIFIED): ~€108K total at Senior SWE II (Cruise Munich, 2023, single data point) |
| AI/ML content | Strong and genuine: radar perception ML for autonomous driving (PyTorch, Spark, synthetic data) |
| Computer-language/Tech-stack | Polyglot: Python (ML), C/C++/CUDA (embedded DSP), MATLAB; NVIDIA/AMD Versal SoCs |
| No on-call | PASS (unverified): R&D, no service operations |
| WLB / Stability | Mixed: WLB rated well (Blind 4.3, Glassdoor SWE 3.8), but stability is undermined by four tech layoff rounds in 2024-2026 and forced ranking |
| Works council / collective agreement | UNKNOWN works council, probably no tariff |
| Regulated industry | CAUTION: ISO 26262, SOTIF, UNECE R155/R156/R157 |
| Review themes | Layoffs, forced ranking and senior leadership dominate negatives. Benefits and team-level WLB dominate positives |
| Captive-centre risk | Sole customer is the US parent. Site has survived two ownership changes, but its future depends on GM's in-house radar strategy |

---

## Section 13: Verdict

**Recommendation: Exclude** (monitor only if a Python-centred ML role at the Munich radar centre appears and a works council can be confirmed).

**Strengths.** GM is a highly profitable, cash-generative public company raising its guidance in 2026, so parent-level insolvency risk is negligible. The Munich (Ottobrunn) radar centre is a real engineering entity with a clear mission. It does genuine applied ML (radar perception, synthetic data, validation frameworks in PyTorch and Spark) feeding a high-profile programme (eyes-off driving from 2028, personal autonomous vehicles). It works in English, has no visible on-call, and survived the 2025 Cruise layoffs intact. The one Munich pay data point is competitive.

**Hard blockers:**
1. **Glassdoor is not "strong".** Global 3.5 and Software Engineers 3.2 (1,485 reviews), with SWE Senior Management at 2.3, 41% recommend and 29% positive business outlook. There are no Germany or Munich data to offset this: 5 and 1 reviews, none from the radar team.
2. **The business strategy is not stable for software staff.** GM cut software and IT staff in August 2024, February 2025 (half of Cruise), October 2025 and May 2026, replaced most of its software leadership in late 2025, and runs a forced-ranking performance system that 2026 reviewers describe as "hunger games". This contradicts the "stable business strategy, looking to commit long-term" criterion, even though the Munich site has been spared so far.
3. **Not software-centric.** The parent is a vehicle manufacturer, and the Munich entity is a radar sensor company: two of its five current postings are pure hardware roles, and the software roles serve a physical sensor.

**Secondary concerns:**
- GM Munich GmbH is a captive R&D centre whose only customer is the US parent, and it has been renamed twice after strategic shifts (2021, 2026).
- No works council or collective agreement could be confirmed. The only evidence suggests no tariff binding.
- Hybrid with a minimum of 3 office days/week in Ottobrunn, outside the Munich city boundary.
- Regulated automotive safety domain (ISO 26262, SOTIF) with hardware-bound release cycles.
- The ML roles require deep radar signal processing experience, a narrow specialisation.
- The site is polyglot, with C/C++/CUDA on the embedded side.

**If a role is considered anyway:** verify in the interview process
- that the contract is with GM Munich GmbH directly
- whether a Betriebsrat exists
- whether GM's forced-ranking system applies to the German entity
- the salary band and whether GM RSUs are granted
- the actual Python share of the role
- the medium-term roadmap commitment to in-house radar
- whether any on-call or vehicle-test duty applies

---

## Sources

- [GM careers - Germany location page](https://search-careers.gm.com/en/locations/germany/)
- [GM Workday careers site (Careers_GM)](https://generalmotors.wd5.myworkdayjobs.com/Careers_GM)
- [LinkedIn - Staff Machine Learning Engineer (Radar & AI), Munich](https://www.linkedin.com/jobs/view/4480218535)
- [LinkedIn - Senior Machine Learning Engineer (Radar & AI), Munich](https://www.linkedin.com/jobs/view/4480225224)
- [LinkedIn - Embedded DSP Engineer, Munich](https://www.linkedin.com/jobs/view/4479357615)
- [LinkedIn - Mechatronics Engineer, Munich](https://www.linkedin.com/jobs/view/4480214835)
- [LinkedIn - Printed Circuit Board Designer, Munich](https://www.linkedin.com/jobs/view/4480218714)
- [LinkedIn - Cruise Staff Radar Engineer, Ottobrunn (historical)](https://de.linkedin.com/jobs/view/staff-radar-engineer-all-genders-at-cruise-3492923947)
- [NorthData - GM Munich GmbH, Ottobrunn, HRB 116461](https://www.northdata.de/GM+Munich+GmbH,+Ottobrunn/Amtsgericht+M%C3%BCnchen+HRB+116461)
- [NorthData - Cruise Munich GmbH (English)](https://www.northdata.com/Cruise%20Munich%20GmbH,%20Ottobrunn/Amtsgericht%20M%C3%BCnchen%20HRB%20116461)
- [NorthData - General Motors Germany GmbH, Frankfurt, HRB 129604](https://www.northdata.de/General+Motors+Germany+GmbH,+Frankfurt+am+Main/HRB+129604)
- [companyhouse.de - Cruise Munich GmbH](https://www.companyhouse.de/en/Cruise-Munich-GmbH-Ottobrunn)
- [Cadillac Europe - Impressum (General Motors Germany GmbH)](https://www.cadillaceurope.com/de-de/impressum)
- [Law.com - Sale of Astyx radar tech company to GM Cruise (2020)](https://law.com/international-edition/2020/07/13/dla-piper-german-firms-advise-on-sale-of-radar-tech-company-to-gm-cruise)
- [electrive - GM entlässt Hälfte des Personals von Cruise (Feb 2025)](https://www.electrive.net/2025/02/05/gm-entlaesst-haelfte-des-personals-von-cruise/)
- [Glassdoor - General Motors (GM) reviews](https://www.glassdoor.de/Bewertungen/General-Motors-GM-Bewertungen-E279.htm?filter.iso3Language=eng)
- [Glassdoor - GM reviews, Germany filter](https://www.glassdoor.de/Bewertungen/General-Motors-GM-Bewertungen-E279.htm?filter.iso3Language=eng&filter.locationId=96&filter.locationType=COUNTRY)
- [Glassdoor - GM reviews, Munich filter](https://www.glassdoor.de/Bewertungen/General-Motors-GM-Bewertungen-E279.htm?filter.iso3Language=eng&filter.locationId=4990924&filter.locationType=CITY)
- [Glassdoor - GM reviews, Software Engineer filter](https://www.glassdoor.de/Bewertungen/General-Motors-GM-Bewertungen-E279.htm?filter.iso3Language=eng&filter.jobTitleFTS=Software%20Engineer)
- [Glassdoor - GM interviews](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/General-Motors-GM-Fragen-im-Vorstellungsgespr%C3%A4ch-E279.htm?filter.iso3Language=eng)
- [Glassdoor - GM Software Engineer interviews](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/General-Motors-GM-Fragen-im-Vorstellungsgespr%C3%A4ch-E279.htm?filter.iso3Language=eng&filter.jobTitleFTS=Software%20Engineer)
- [Kununu - Cruise LLC (München)](https://www.kununu.com/de/cruise1)
- [Kununu - Astyx GmbH (Ottobrunn)](https://www.kununu.com/de/astyx1)
- [Kununu - General Motors Germany GmbH](https://www.kununu.com/de/general-motors-germany)
- [Kununu - search "General Motors"](https://www.kununu.com/de/search?q=General%20Motors)
- [Blind - General Motors](https://www.teamblind.com/company/General-Motors)
- [Blind - General Motors reviews](https://www.teamblind.com/company/General-Motors/reviews)
- [Blind - Cruise Munich Ottobrunn thread](https://www.teamblind.com/post/cruise-munich-ottobrunn-sonpskei)
- [levels.fyi - GM Software Engineer (US)](https://www.levels.fyi/companies/general-motors/salaries/software-engineer)
- [levels.fyi - GM Software Engineer, Germany](https://www.levels.fyi/companies/general-motors/salaries/software-engineer/locations/germany)
- [levels.fyi - Cruise Software Engineer, Germany](https://www.levels.fyi/companies/cruise/salaries/software-engineer/locations/germany)
- [GM FY2025 Form 10-K (SEC)](https://www.sec.gov/Archives/edgar/data/1467858/000146785826000013/gm-20251231.htm)
- [Beancount - GM FY2026 Q3 earnings analysis](https://beancount.io/blog/2026/10/21/general-motors-fy2026-q3-earnings-analysis)
- [DBusiness - GM reports $50B Q3 revenue, $4.1B EBIT](https://www.dbusiness.com/daily-news/general-motors-reports-50b-in-q3-revenue-4-1b-in-ebit/)
- [FMP - GM beats Q3 estimates, announces $20B buyback](https://site.financialmodelingprep.com/market-news/general-motors-q3-2026-earnings-20-billion-buyback)
- [INDmoney - Why GM stock fell despite higher profits](https://www.indmoney.com/blog/us-stocks/general-motors-q3-earnings-analysis)
- [Business Today - GM cuts IT jobs by 10% (May 2026)](https://www.businesstoday.in/technology/story/general-motors-cuts-it-jobs-by-10-as-it-shifts-focus-to-ai-talent-530953-2026-05-12)
- [just-auto - GM cuts 500-600 salaried IT roles](https://www.just-auto.com/newsletters/gm-cuts-500-600-salaried-it-roles)
- [Outlook Business - GM slashes over 1,000 jobs, 600 at Detroit tech campus (2024)](https://www.outlookbusiness.com/corporate/gm-slashes-over-1000-jobs-globally-600-positions-cut-at-detroit-tech-campus)
- [Motor1 - GM's software boss steps down amid major overhaul](https://www.motor1.com/news/777926/general-motors-software-leadership-changes/)
- [WardsAuto - GM reshuffles software organisation under Sterling Anderson](https://www.wardsauto.com/news/GM-reshuffles-software-services-organization-names-sterling-anderson/804602)
- [WardsAuto - SVP Software Baris Cetinok stepping down](https://www.wardsauto.com/news/gm-svp-software-services-baris-cetinok-stepping-down/806704/)
- [GM Authority - GM restructuring tech team with new hires](https://gmauthority.com/blog/2025/11/gm-restructuring-tech-team-with-new-hires/)
- [TechCrunch - GM to introduce eyes-off, hands-off driving in 2028](https://techcrunch.com/2025/10/22/gm-to-introduce-eyes-off-hands-off-driving-system-in-2028)
- [Automotive World - GM sets 2028 target for Escalade IQ eyes-off deployment](https://www.automotiveworld.com/news/gm-sets-2028-target-for-escalade-iq-eyes-off-deployment/)
- [Axios - GM plans eyes-off self-driving system](https://www.axios.com/2025/10/22/gm-self-driving-cars-ai)
- [Fortune - GM RTO hybrid mandate, three days per week](https://fortune.com/2023/12/05/gm-rto-hybrid-mandate-three-days-per-week-mary-barra)
- [Benefit News - GM ends flexible work policy](https://www.benefitnews.com/articles/gm-ends-flexible-policy-with-mandatory-three-days-in-office)
- [Interview Query - GM Software Engineer interview guide](https://www.interviewquery.com/guides/general-motors-software-engineer)
- [Taro - GM Senior Software Engineer interview (Markham, 2024)](https://www.jointaro.com/interviews/companies/general-motors/work-experiences/senior-software-engineer-markham-on-november-22-2024-1-ee0897d5/)
- [OpenStreetMap Nominatim - Caroline-Herschel-Straße 2, Ottobrunn](https://nominatim.openstreetmap.org/search?q=Caroline-Herschel-Stra%C3%9Fe+2,+85521+Ottobrunn&format=json&addressdetails=1)
- [Overpass API (OpenStreetMap) - transit stops near the office](https://overpass-api.de/api/interpreter)
