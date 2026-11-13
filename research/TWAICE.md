# TWAICE - Full Research Report

_Researched: 2026-11-12_

> **Critical Disqualifiers**
> 1. **Not profitable, and losses grew every year through the latest filing.** TWAICE Technologies GmbH lost €17.4M in FY2024 (after -€13.3M in 2023 and -€11.9M in 2022). Accumulated losses reached €55.1M against €75.0M of paid-in capital reserves. Liquidity at 31.12.2024 was €17.5M (cash plus securities). The only financing announced since the April 2022 round is a €24M **venture debt** loan from the EIB (February 2026), not new equity.
> 2. **The company is shrinking, and reviewers describe repeated layoffs.** Revelio Labs puts headcount at 159 (June 2026), down 32% from 234 in 2023 and down 15% year over year. Glassdoor reviewers wrote "Layoffs have become a new normal" (Sep 2024) and listed "layoffs, high people turnover, lack of product market fit" (Nov 2025). None of these cuts appeared in the press.
> 3. **No senior engineering opening.** The careers page lists one engineering role, a Full-Stack Software Engineer aimed at "around 1-4 years of professional experience", working "with guidance from the senior engineers in your team". Revelio counts one active posting in 2026, down from about 10 new postings a month in 2023.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 2018 (8 years). Registered at Amtsgericht München on 28.06.2018 as a TU Munich spin-off |
| Employees | ~159 globally (Revelio Labs, June 2026). LinkedIn shows 51-200. 90.6% of staff are in Western Europe, 6.3% in North America |
| Revenue (FY2024) | **UNKNOWN.** NorthData hides revenue. The FY2024 HGB accounts show a gross result (Rohergebnis) of €3.57M, so revenue is probably in the mid single-digit millions. The company says its "BESS business nearly tripled in 2025" but gives no absolute figure |
| Profitability | Net loss of €17.4M in FY2024. Losses grew every year: -€0.2M (2018), -€1.4M (2019), -€4.3M (2020), -€6.5M (2021), -€11.9M (2022), -€13.3M (2023), -€17.4M (2024) - **FAIL** |
| Ownership | Private and VC-backed (Creandum, Cherry Ventures, Speedinvest, UVC Partners, Energize Ventures, Coatue, Lip-Bu Tan). The founders' holding companies (MiB-Tec Holding GmbH, SR Holding GmbH) each appear with 12.8% on NorthData. EIB venture debt (2026) |
| Software-centric | Cloud SaaS analytics platform for battery energy storage (BESS) operators, plus a "Battery Experts" business unit serving battery makers and EV OEMs - **PASS** (see the consulting note below) |

### Key People

- **Dr. Stephan Rohr**: co-founder and Co-CEO, managing director (Geschäftsführer). Approved by 92% of Glassdoor reviewers (global).
- **Dr. Michael Baumann**: co-founder and Co-CEO, managing director.
- **Jeff Glasson**: appointed CTO in February 2022 (previously HP, Apple, NeXT). Whether he is still in the role is **UNVERIFIED**.
- **Marc Paczian**: Chief Customer Officer since July 2022.
- A September 2024 Glassdoor review criticises the "twin CEO model" for "ambiguous direction".

### Funding History

| Date | Round | Amount | Lead / Investors | Valuation |
|---|---|---|---|---|
| 2018-2019 | Seed | UNVERIFIED | UVC Partners, Cherry Ventures | Not disclosed |
| 2020 | Series A | €11M | Creandum | Not disclosed |
| May 2021 | Series B | $26M (total raised then $45M) | Energize Ventures; Creandum, Cherry, Speedinvest, UVC | Not disclosed |
| Apr 2022 | Series B extension | $30M (total raised then $75M) | Coatue; Lip-Bu Tan, existing investors | Not disclosed |
| Oct 2022 | EU grant | €2.16M ("TWAICE Predictive Analytics und Digital ...") | EU | n/a |
| Feb 2024 | Capital increase (registry only, not announced) | Share capital €85,391 → €90,522 (+6%) | Undisclosed, probably existing investors | Not disclosed |
| Feb 2026 | Venture debt | €24M | European Investment Bank (InvestEU) | n/a |

Aggregator totals disagree (tech.eu: €88M over 6 rounds; ZoomInfo: $100.8M, which mixes in the EIB debt). The FY2024 balance sheet shows €75.0M of capital reserves, which matches roughly $75M+ of equity raised. No Series C exists. The last announced equity round was 4.5 years ago, and the 2026 financing was debt.

### Business Model

TWAICE sells a cloud analytics platform for grid-scale BESS operators. The modules are Health Monitoring & Analytics, Safety Monitoring & Analytics, Warranty Manager, Performance Manager, Digital Commissioning and a Storage Dashboard (June 2026). Separately, the "Battery Experts" unit works with "leading battery companies and electric vehicle manufacturers to embed battery insights into commercial products, from cell-level analysis through in-life performance." The company started with an automotive/EV battery focus and pivoted toward stationary storage around 2023-2024. The Glassdoor complaints of "no product market fit" (Feb 2025, Nov 2025) date from this period.

### Consulting-Adjacency Assessment

The registered purpose includes "Beratung" alongside hardware and software. The Battery Experts unit is project and service work for OEMs (simulation, cell analysis). The core engineering organisation builds the SaaS product, though. Software postings describe "product teams" shipping "our SaaS product" through CI/CD, there are no consultant titles, and no reviewer describes billing hours. Software engineering here is product engineering, not client delivery. Revelio's functional split shows only 24.4% of staff in Engineering, against 53.6% in Finance & Operations (which probably includes battery analysts and customer success) and 22.0% in Sales & Marketing.

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **TWAICE Technologies GmbH** | Amtsgericht München HRB 241903 (EUID DED2601V.HRB241903; LEI 984500D66AF98B86DB15; VAT DE319410966) | Rosenheimer Str. 143 C, 81671 München (address registered 22.07.2026) | "Erforschung, Entwicklung, Herstellung und Vermarktung von Produkten, Lösungen und Dienstleistungen (Hardware, Software, Beratung, Wartung sowie Inhalte) zur Erfassung, Weiterverarbeitung und Analyse von Daten von elektrischen Systemen und deren Optimierung mit Schwerpunkt auf Batterieanalytiksoftware ..." |

The GmbH is the parent and operating company, not a sales shell. Its purpose starts with research and development of battery analytics software. It carried €13.5M of personnel costs in FY2024 (€11.6M salaries plus €1.9M social security), so the German workforce is employed directly. A French establishment was registered in 2021 (SIREN 902712322), and the balance sheet shows €0.93M in shares in affiliated companies (US operation). Engineering roles are advertised on the GmbH's own Personio board for Munich or remote within Germany. The Impressum (twaice.com/imprint) confirms the registration and names Dr. Stephan Rohr and Dr. Michael Baumann as representatives.

**Verdict:** PASS

---

## Section 3: Office Location

- **Office address:** Rosenheimer Str. 143C, 81671 München (Werksviertel, Berg am Laim), as stated in the Impressum. Nominatim places the address in the **Design Offices** building (a flexible workspace/co-working operator). The registered address changed on 22.07.2026. Reviews up to December 2025 complain that the old office was "a bit far off the city centre". Directories list the earlier address as Joseph-Dollinger-Bogen 26, 80807 München (Freimann). A July 2026 posting describes the new space as a "Central Munich office with views of the Alps".
- **Nearest public transport** (OSM Overpass, straight-line distances from 48.12274, 11.60458):
  - Bus stop "Ostbahnhof Friedenstraße": ~520 m
  - **München Ost** station (S-Bahn trunk line S1-S8, U5, regional and long-distance trains): ~560-600 m
  - **Karl-Preis-Platz** (U2) station: ~610 m; bus stop with line X200: ~660 m
  - Ostbahnhof tram stop: ~670 m
- **Work model:** Flexible. The careers page and postings say: "options to work remotely, onsite or hybrid. Everyone comes together at our Munich HQ twice a year." Earlier senior postings were tagged "Remote (DE)" with "flexible home office within Germany" plus "Working from within the EU is also possible for up to 90 calendar days a year". The current Full-Stack role is labelled "Munich, Hybrid". Remote work is restricted to Germany, with EU work limited to 90 days a year.

---

## Section 4: Reviews

**GPTW:** No Great Place to Work Germany certification or list entry was found (greatplacetowork.de site search and web search). TWAICE has no Kununu Top Company badge either.

### Glassdoor

Data via Chromium/CDP (glassdoor.co.uk shows the English reviews, glassdoor.de the German ones). The company has 33 reviews across languages: 22 on the English site and 11 on the German site.

| Metric | Global | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | 4.4 (33 reviews) | 4.2 (15) | 4.2 (15) | ~4.3 (4 written SWE/Senior SWE reviews, read manually: 5.0, 4.0, 5.0, 3.0). Glassdoor's "Software Engineer" filter: 5.0 (1); "Senior Software Engineer" filter: 1 review |
| **WLB** | 4.3 | n/a | n/a | 5.0 (SWE, 1) / 3.0 (Senior SWE, 1) |
| **Culture & Values** | 4.4 | n/a | n/a | 5.0 / 5.0 |
| **Comp & Benefits** | 4.2 | n/a | n/a | 4.0 / 5.0 |
| **Career Opportunities** | 3.7 | n/a | n/a | 4.0 / 3.0 |
| **Senior Management** | 3.8 | n/a | n/a | 4.0 / 1.0 |
| **Diversity & Inclusion** | 4.2 | n/a | n/a | 3.0 / 5.0 |
| **% Recommend** | 86% | 83% | 83% | 100% (1) |
| **CEO Approval** | 92% (Stephan Rohr) | 90% | 90% | 100% (1) |
| **Business Outlook** | 77% positive | 81% positive | 81% positive | 100% (1) |

Every filter has fewer than 20 reviews, so all of these figures are **directional only**. The Germany and Munich filters return the same 15 reviews. Glassdoor does not show category sub-ratings below the global level. **The all-time average hides a downward trend.** The 9 written reviews from September 2024 onward average **~3.6**, and the five English ones average **2.8** (2.0, 4.0, 3.0, 4.0, 1.0). Revelio Labs also rates "overall employee sentiment" as "negative and declining".

### Kununu

Data via Chromium/CDP (curl returned HTTP 405). Slug: `twaice-technologies1`.

- **Overall score:** 4.7 / 5.0 (industry average for "Industrie": 3.4)
- **Recommendation rate (Weiterempfehlung):** 100% over the last 2 years. 97% across all employee reviews
- **Total reviews:** 85 (employee reviews: 58)
- **Sub-scores:** Karriere & Gehalt 4.6, Unternehmenskultur 4.7, Arbeitsumgebung 4.8, Vielfalt 4.7
- **Most-confirmed benefits:** Homeoffice 81%, flexible hours 78%, employee events 74%
- **Kununu Top Company:** NO (no badge shown)
- **Salaries:** 34 entries (see Section 5)

Recent volume is very low. Only about four employee reviews were posted between October 2024 and November 2026, two of them by the same sales employee ("Mehrfachbewertung"). The People team (Kerstin Angerer) replies to every review. The Kununu score therefore mostly reflects the 2021-2023 growth period. Note that it also diverges sharply from the recent Glassdoor reviews.

### Blind / Teamblind

`teamblind.com/company/TWAICE` returns "Page not found" (via Chromium/CDP). **No Blind presence.** That is expected for a ~160-person German company.

### Review Themes (2024-2026)

**Positives:**
- **Flexibility and trust.** "I've never seen such flexibility in a company. You can make private appointments and work as you like. I've never felt like I was being monitored or controlled. ... the workload can be high at times ... but everything is within the 40-hour-a-week framework." (Kununu, Oct 2024, Angestellte/r oder Arbeiter/in, Vertrieb / Verkauf, Munich). "Full flexibility between remote and on-site work ... Full trust into everyone to get things done." (Kununu, May 2026, Angestellte/r oder Arbeiter/in, Munich)
- **Benefits.** Free breakfast and lunch, Wellpass, JobRad, a 100% matched company pension, pool EVs for private use, a training budget and VSOP. "Nice set of benefits, fro fitness to fully substituted pension plan, VSOPs, free meals and snacks." (Kununu, May 2026, Angestellte/r oder Arbeiter/in, Munich)
- **Colleagues and team spirit.** "Good work culture and people" (Glassdoor, Sep 2026, former Senior Software Engineer, Munich). "great colleagues decent pay free lunch" (Glassdoor, Sep 2024, former Anonymous Employee, Munich, 1+ years). "Good and multi cultural team." (Glassdoor, Oct 2025, former Battery Engineer, Munich)
- **Interesting domain.** "Working in the intersection of batteries and software supporting major energy & EV companies globally" (Kununu, Oct 2024, employee, Munich)
- **Pay is described as decent.** "Great compensation and work life balance" (Glassdoor, Sep 2025, former Anonymous Employee, 1+ years)

**Negatives:**
- **Recurring layoffs and attrition** (hard red flag). "Layoffs have become a new normal unfortunately" (Glassdoor, Sep 2024, former Anonymous Employee, Munich, 1+ years). "layoffs, high people turnover, lack of product market fit, very stagnant mindset for a startup company, challenges to hire really capable and experienced employees and leaders, no company strategy / strategy changes every month" (Glassdoor, Nov 2025, current Anonymous Employee, Munich, 1+ years). Revelio's headcount series (-32% since 2023) corroborates this.
- **Leadership direction and stability.** "Management lacks stability and direction" (Glassdoor, Sep 2025, former Anonymous Employee, 1+ years). "Management Issues, internal conflicts and visiblity" (Glassdoor, Sep 2026, former Senior Software Engineer, Munich). "Ambiguous direction with the twin ceo model ... politics have become deeply routed in the upper management" (Glassdoor, Sep 2024, former Anonymous Employee, Munich). "Klarerer Fokus und mehr enablement" (Glassdoor, Nov 2025, former Software Engineer).
- **Product-market fit.** "terrible management / no product market fit / treating bad" plus "low salary" (Glassdoor, Feb 2025, current Senior Software Engineer, Munich).
- **Communication during restructuring and a broken promise.** "bei den letzten großen Veränderungen war die Kommunikation und die Planung super schlecht" and "ein mir bekannter Fall bei dem eine Person trotz vollmundiger Versprechen gekündigt wurde" (Kununu, Sep 2024, Angestellte/r oder Arbeiter/in, Munich, rating 2.8, not recommended).
- **A toxic manager in the product organisation (2024).** "Gerade scheint die Organisation (Produkt-bereich) um eine narzisstische Person herum reorganisiert zu werden. Diese stellt sich mit Vorgesetzten gut und behandelt Teammitglieder und andere Kollegen ohne Respekt" and "Vorgesetztenverhalten: Je nach Vorgesetzten unterirdisch, meist ok, wenige hervorragende Chefs" (same Kununu review, Sep 2024). "some managers have zero empathy for their employees resulting in burndown of the workforce" (Glassdoor, Sep 2024, former Anonymous Employee, Munich).
- **Growing performance pressure.** "increasing focus on individual and company performance" (Kununu, Oct 2024, employee, Munich).

Overlap with hard red flags: **layoffs** (multiple platforms, 2024 and 2025), **communication breakdown** (Kununu 2024, Glassdoor 2025-2026) and **toxic leadership pockets** (product organisation, 2024).

### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | **Localized, 2024.** One Kununu reviewer describes the product area being "reorganised around a narcissistic person" who treats colleagues "ohne Respekt". A Glassdoor review from the same month says "some managers have zero empathy". No later reviews repeat this, though few later reviews exist at all. |
| 24/7 Work Expectation | **Not found.** Reviewers stress flexibility and say the workload stays "within the 40-hour-a-week framework". |
| Internal Surveillance | **Not found.** "I've never felt like I was being monitored or controlled." (Kununu, Oct 2024) |
| Fear-driven Management | **Indirect signals.** Recurring layoffs, "increasing focus on individual and company performance" and "treating bad" (Feb 2025). No explicit fear culture is described. |
| Communication Breakdown | **Present.** "die Kommunikation und die Planung super schlecht" during the last big changes (Kununu, Sep 2024). "no company strategy / strategy changes every month" (Glassdoor, Nov 2025). "Kommunikationswege sind manchmal unklar" (Glassdoor, Jul 2024, current Software Engineer). Weekly all-hands exist, and "in 4 weeks a lot of things can and will change" (Kununu, Oct 2024). |
| Unpaid Overtime | **Not found.** |
| Silent Firings | **Partial signal.** A person was dismissed "trotz vollmundiger Versprechen" (Kununu, Sep 2024). Layoffs happened without any press announcement, and there is no works council (Section 8). |
| Work-Life Balance issues | **Not found.** WLB is consistently praised (Glassdoor 4.3, Kununu flexibility quotes). One reviewer adds that flexibility "wird leider auch ausgenutzt". |

**Risk level: MODERATE.** WLB and day-to-day culture look healthy. The main risks are (a) strategic instability at the top (twin-CEO ambiguity, pivots, "strategy changes every month") and (b) repeated, unannounced downsizing at a shrinking startup. A localized toxic-manager episode in the product organisation in 2024 adds to this. None of it looks like systemic 24/7 or surveillance toxicity, and it is not big-company bureaucracy either. It is the instability of a startup searching for product-market fit.

---

## Section 5: Compensation

### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| levels.fyi | n/a | n/a | n/a | n/a | n/a | 0 (no company page: 404) |
| Kununu | Softwareentwickler:in, München | ~€71.8K avg | VSOP (not valued) | low variable | ~€71.8K | 4 |
| Kununu | Engineering Manager:in, München | ~€103.7K avg | VSOP | n/a | ~€103.7K | 2 |
| Kununu | Solution Architect, München | ~€85.0K avg | VSOP | n/a | ~€85.0K | 3 |
| Kununu | Ingenieur:in, München | ~€73.2K avg | VSOP | n/a | ~€73.2K | 2 |
| Kununu | Produktmanager:in, München | ~€80.0K avg | VSOP | n/a | ~€80.0K | 4 |
| JobLeads (estimate, not company-stated) | Senior Backend Engineer, München/Hybrid | €65-85K | n/a | n/a | n/a | aggregator estimate |
| Revelio Labs | All roles, Western Europe | ~$99K median (~€85K) | n/a | n/a | n/a | modelled |
| Glassdoor | n/a | No engineering salaries shown (6 salaries company-wide, none in engineering; "Munich (44)" count without titles) | | | | 0 |

**Munich reference (levels.fyi Germany, from earlier reports in this project):** the Senior SWE median total is ~€81.5K. Seed and Series A startups typically pay ~€75-95K base plus VSOP. Large, profitable Munich employers pay ~€85-110K base, with the 90th percentile at €120K+. TWAICE-specific 75th/90th percentiles: **UNAVAILABLE**.

### Equity / Stock

"Every employee is offered a stock-option plan" (VSOP, per the careers page and the Kununu reviews). The terms are not disclosed. The last priced equity round was April 2022, at the peak of 2021-2022 climate-tech valuations. With €55M of accumulated losses, a headcount down by a third and new money coming as debt (which ranks ahead of equity), the VSOP is very likely underwater relative to the 2022 price and illiquid. Treat it as zero.

### Verdict

Engineer pay averages ~€72K on Kununu (4 points, mixed seniority), and an aggregator estimates the Senior Backend Engineer band at €65-85K. Reviewers rate pay as fair ("pay pretty well for a company of this size", Comp & Benefits 4.2), but one 2025 Senior SWE review lists "low salary". Strong benefits (free meals, 100% pension match) close part of the gap. For a senior engineer, cash pay is at or below the startup norm and below the €85-110K base bracket of large, profitable Munich employers.

**BELOW** (startup-typical, data thin)

---

## Section 6: AI/ML & Tech Stack

### AI Strategy

The AI here is applied, domain-specific ML for battery state estimation, not LLM products:
- **Battery health and aging models.** Patents filed or granted 2023-2026 cover "Bestimmung eines Alterungswerts für Batterien", "Bestimmung des Gesundheitszustands von Batterien", "Verfahren zum Trainieren eines Maschinenmodells ..." and "Zustandswert für wiederaufladbare Batterien". The company combines physics-based battery simulation (its TUM research origin) with data-driven models ("TWAICE combines battery expertise with artificial intelligence", Munich Startup).
- **Product use:** predictive degradation, safety anomaly detection, warranty tracking and performance KPIs across BESS fleets. In 2025 the company announced 15+ product updates, including Penalty Risk Assessment. The Storage Dashboard followed in June 2026.
- **Insurance partnership:** Munich Re's aiSure battery-warranty product builds on TWAICE analytics.
- **No LLM or agentic product** turned up in any press release, newsroom item or posting. A 2026 working-student posting mentions "using AI tools and techniques" for analyses.
- In the postings, the ML and analytics work sits with battery engineers and data/energy-systems engineers. Software engineers build the SaaS product (APIs, pipelines, frontend) around those models.

### Tech Stack

Sources: current and recent job postings (Full-Stack Software Engineer 2026; Senior Backend Engineer and Energy Systems Data Engineer 2025, via Personio, Speedinvest/Getro mirrors and aggregators); the TWAICE GitHub organisation (3 public repos); the careers page. There is no engineering blog, and no StackShare or Himalayas profile with product data (techlist.ai only covers the marketing website).

| Category | Technologies |
|---|---|
| **Primary language(s)** | Python (backend, data pipelines, analytics), TypeScript (backend services: NestJS per GitHub `nestjs-kinesis-producer` / `node-kinesis-producer`; frontend), SQL |
| **AI/ML** | Battery aging / state-of-health ML models (patents), Python data science, physics-based battery simulation |
| **Cloud** | AWS (Kinesis, plus the general AWS requirement in postings) |
| **Infrastructure** | CI/CD with daily deploys, Infrastructure as Code (tool not named), "modern observability solutions" |
| **Data** | Databricks, Apache Spark, SQL, time-series operational data (SCADA, BEMS, inverter logs), AWS Kinesis streaming |
| **Other** | Angular (primary frontend; React named as an alternative), pytest, RESTful APIs, data visualisation |

**Summary:** Polyglot Python/TypeScript SaaS engineering. Python carries the data pipelines and battery analytics on Databricks/Spark, and TypeScript (NestJS, Angular) carries the services and frontend, all on AWS. Applied, production analytics in the energy-storage domain, with ML centred on battery health models built largely by domain specialists rather than software engineers.

---

## Section 7: Language

All postings, the careers page and most reviews are in English. Postings require "Excellent English verbal and written communication skills" and mention no German requirement. Reviewers describe an "international team" and a "multi cultural team", and the company recruits across Germany, France, the Netherlands and the US.

**Verdict:** PASS

---

## Section 8: Stability

### Financial Position

From the HGB annual accounts (TWAICE Technologies GmbH, single entity), via NorthData, read from the embedded chart data through Chromium/CDP:

| Item | FY2024 (31.12.2024) |
|---|---|
| Net loss (Jahresfehlbetrag) | **-€17.45M** (2023: -€13.34M; 2022: -€11.92M) |
| Gross result (Rohergebnis) | €3.57M |
| Personnel costs | €13.48M (salaries €11.57M + social €1.90M) |
| Other operating expenses | €7.02M |
| Write-downs on financial assets/securities | €0.79M |
| Cash and bank balances | €11.37M |
| Securities (current assets) | €6.10M |
| Total assets | €22.06M |
| Equity | €20.04M (capital reserves €75.04M, loss carried forward -€37.64M, current loss -€17.45M) |
| Liabilities | €0.93M (no bank debt at that date) |

The losses grew every year through 2024. The FY2024 accounts were filed late (27.03.2026), and FY2025 is not yet filed. Positive signals: the BESS business "nearly tripled in 2025", customer wins (e.g. Fullmark Energy, 290 MWh in California), and the EIB's due diligence ahead of its February 2026 loan. Negative signals: no equity round since 2022, the shift to venture debt, a headcount down 32%, and a hiring freeze in all but name.

### Financial Runway

**Online sources:** No analyst runway estimate exists. The EIB press release does not state the expected runway. Bundesanzeiger, handelsregister.ai (Cloudflare block) and unternehmen24 (paywall) gave no further detail.

**Bottom-up model (2026):**

| Cost line | Annual estimate |
|---|---|
| Staff (~159 employees × ~€90K fully loaded; the German entity paid ~€13.5M in 2024 with more staff, US salaries are higher) | ~€14M |
| Other opex (cloud, office, travel, marketing, US entity) | ~€5-6M |
| EIB loan interest (venture debt, ~€24M) | ~€1-2M |
| **Total gross burn** | **~€20-22M/year** |

| Revenue source | Est. annual inflow |
|---|---|
| BESS SaaS subscriptions (assumes the 2025 "nearly tripled" growth continues more slowly) | ~€7-10M/year |
| Battery Experts services (OEM projects) | ~€2-3M/year |
| **Total revenue offset** | **~€9-13M/year** |

**Cash at hand, early 2026:** €17.5M liquidity at 31.12.2024 (NorthData, FY2024 balance sheet, observed 2026-11-12), minus an estimated FY2025 net burn of €10-13M, leaves ~€5-7M at the end of 2025. Adding the €24M EIB loan (February 2026, assumed fully drawn; EIB venture debt is often paid out in milestone tranches) gives **~€29-31M**.

| Scenario | Net burn | Cash at hand | Runway | Next round needed by |
|---|---|---|---|---|
| Optimistic (revenue keeps doubling, cost flat) | ~€6M/year | ~€30M | ~4-5 years (breakeven possible in 2028) | ~2029-2030, or never if breakeven |
| Base case | ~€10M/year | ~€30M | ~3 years | ~2028 (amortisation of the loan brings this forward) |
| Stress (growth stalls, second EIB tranche not drawn) | ~€14M/year | ~€17M | ~1.2 years | ~mid-2027 |

Cash figure used: €11.37M bank plus €6.10M securities at 31.12.2024 (NorthData, FY2024 accounts published 2026-03-27), adjusted by estimates. The base case gives runway into 2028. The company would then need equity, profitability, or a sale (strategic acquirers in energy, insurance or industrial software are plausible).

### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| 2023-2024 | Reorganisation and layoffs during the pivot from EV/automotive to BESS | Not disclosed | Glassdoor (Sep 2024): "Layoffs have become a new normal". Kununu (Sep 2024): restructuring of the product area, poor communication "bei den letzten großen Veränderungen", a person dismissed despite promises. No press coverage. |
| 2025 | Further layoffs and attrition | Not disclosed | Glassdoor (Nov 2025, current employee): "layoffs, high people turnover". Revelio: ~199 in Q1 2025, ~162 at year-end. |
| 2023 → Jun 2026 | Net headcount decline | 234 → 159 (-32%); -15% YoY (-28) in 2026 | Revelio Labs. Postings per month fell from ~10 (2023) to ~1 (2026). |
| Jul 2026 | Office move | n/a | Registered address moved to Design Offices Werksviertel (flexible workspace), consistent with a smaller, remote-heavy organisation. |

### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | **NO evidence** (likely none) | No mention in any Kununu or Glassdoor review text, posting, or web search for "TWAICE Betriebsrat" |
| Collective agreement | **NONE found** | Postings describe individual benefits (100% pension match, VSOP, 30 vacation days) with no tariff reference. Startup without employer-association membership |
| European works council | N/A | Below the threshold |
| Conflict signals | None found | n/a |

There is no works council and no collective agreement, at a company with recurring, unannounced layoffs and a reported dismissal "trotz vollmundiger Versprechen". This is the pattern this project has linked to silent firings and managed-out attrition.

**Verdict:** FAIL on profitability. CAUTION on stability (runway of ~3 years in the base case on debt, a shrinking headcount, no works council).

---

## Section 9: Regulated Industry

TWAICE sells analytics software to BESS operators and battery/EV OEMs. The software is not itself a safety-certified control system: it monitors and advises rather than controlling the batteries. Customers in grid infrastructure may bring security requirements (NIS2/KRITIS supply-chain questionnaires, possibly ISO 27001). One Feb 2025 Senior SWE review lists "compliance" as a con, without detail. There is no evidence of ISO 26262, IEC 61508-style safety cases or heavy documentation regimes in the engineering work.

**Verdict:** PASS (low regulatory burden, with some customer-driven security compliance)

---

## Section 10: On-Call

No posting mentions on-call, standby (Rufbereitschaft) or rotations. However:
- The product includes **Safety Monitoring & Analytics** and "real-time insights" for operating BESS fleets, where alerts on safety anomalies are customer-critical.
- The Senior Backend Engineer posting includes "Ensure and extend system reliability across new feature releases, data availability and individual customer issues" and daily production deployments.
- The engineering organisation is small (~24% of ~159 staff, so roughly 35-40 people across battery and software engineering), which means any rotation would be shared among few people.
- Customers span Europe and the US (Fullmark Energy, California), so US working hours overlap.

No reviewer mentions on-call or out-of-hours incidents.

**Verdict:** CAUTION (UNVERIFIED; plausible for the product teams given real-time monitoring and safety alerting)

---

## Section 11: Interview Process

Based on Glassdoor (19 interview reports, last updated June 2025, via Chromium/CDP) and the process published on the TWAICE careers page.

| Metric | Value |
|---|---|
| Difficulty | 2.74 / 5 (Glassdoor). Software Engineer and Data Analyst interviews were rated the hardest |
| Positive experience | 53% (42% negative) |
| Average duration | ~31 days (Battery Modeling Engineer fastest at 5 days; Senior Data Scientist slowest at 60 days) |
| Rounds | 4 |

**Typical process (careers page):**
1. **First Chat** with People & Culture (motivation, environment, two-way Q&A).
2. **Meet Your Team Lead**: a deeper conversation about experience and the role.
3. **Challenge**: "For technical positions, a short coding challenge is coming your way". The exercise mirrors real work.
4. **Experience Day**: several focused conversations with team members and people from outside the team (in person or remote), including a presentation of the case study, plus collaboration and culture-fit topics.

Glassdoor stage mix: phone interview 35%, one-on-one 25%, panel 15%, skills test 15%, presentation 10%. 79% of candidates applied online. The process is experience- and practical-exercise-focused, not LeetCode-heavy. The 42% negative candidate experience is high and suggests uneven follow-through.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | PASS. Cloud SaaS for BESS analytics, plus a smaller Battery Experts services unit |
| Not consulting | PASS. Product teams. The Battery Experts unit is project work but separate from software engineering |
| Profitable | **FAIL.** -€17.4M in FY2024, with losses growing every year. €55M accumulated deficit |
| Employee count | ~159 (June 2026), down 32% since 2023 |
| English-speaking | PASS. English-only postings, international team |
| Local entity + engineering contracts | PASS. TWAICE Technologies GmbH, HRB 241903, the parent and R&D entity |
| Location / work model | Rosenheimer Str. 143C (Werksviertel, Design Offices), ~600 m from München Ost. Remote/hybrid within Germany, HQ meet-ups twice a year |
| Glassdoor | 4.4 all-time (33 reviews), but ~2.8-3.6 since Sep 2024. Germany/Munich 4.2 (15) |
| Kununu | 4.7 (58 employee reviews), 100% recommend over 2 years, but only ~4 reviews since Oct 2024 |
| Salary | BELOW. Engineers average ~€72K (Kununu, 4 points). VSOP likely worthless |
| AI/ML content | Applied battery-health ML (patented), mostly built by domain specialists. No LLM work |
| Computer-language/Tech-stack | Polyglot Python/TypeScript (NestJS, Angular) on AWS with Databricks/Spark |
| No on-call | CAUTION/UNVERIFIED. Real-time safety monitoring product, small team |
| WLB / Stability | WLB good. Stability weak: repeated layoffs, debt-financed runway of ~3 years |
| Works council / collective agreement | None found |
| Regulated industry | PASS. Low burden |
| Review themes | Flexibility, benefits and colleagues praised. Layoffs, unstable strategy, twin-CEO ambiguity and lack of PMF criticised |
| Open roles | Only a mid-level (1-4 years) Full-Stack role. No senior/staff engineering opening |
| Acquisition / exit risk | Moderate. A sale or acqui-hire is a plausible outcome if equity cannot be raised by ~2028 |

---

## Section 13: Verdict

**Exclude for now (monitor only if a senior/staff role appears after a new equity round).**

**Strengths.** TWAICE works on a meaningful climate-tech problem: keeping grid-scale battery storage safe, available and profitable. It has real IP in battery-aging analytics and a market (BESS) that is growing fast; its own BESS revenue nearly tripled in 2025. Day-to-day working conditions are good. Remote and hybrid work within Germany is genuinely flexible, reviewers on both platforms praise WLB and trust, and benefits are generous (free meals, a 100% matched pension, EV pool cars). English is the working language, the German GmbH is the real R&D entity, and the stack (Python, TypeScript, AWS, Databricks/Spark) is a mainstream modern data-SaaS stack. The interview process is practical and not LeetCode-driven.

**Hard blockers:**
1. **Not profitable, with deepening losses.** Net losses rose every year to -€17.4M in FY2024, against a gross result of only €3.6M. Accumulated losses of €55.1M have consumed most of the €75M of paid-in capital. Runway now depends on a €24M EIB **loan**, not new equity. In the base case it lasts to about 2028, and to about mid-2027 under stress.
2. **Repeated layoffs and a shrinking organisation.** Headcount is down from 234 (2023) to 159 (June 2026). Reviewers on Glassdoor in 2024 and 2025 describe layoffs as "a new normal" and report "high people turnover". There is no works council or collective agreement to make cuts announced and negotiated, and a Kununu reviewer reports a dismissal despite explicit promises.
3. **No senior-level role exists.** The only engineering opening targets 1-4 years of experience and pays (by Kununu averages) ~€72K. That is below the €85-110K base bracket of large, profitable Munich employers, and the VSOP is unlikely to have value.

**Secondary concerns:**
- Leadership and strategy instability ("no company strategy / strategy changes every month", "ambiguous direction with the twin ceo model", "Management lacks stability and direction"), plus a 2024 toxic-manager episode in the product organisation.
- The Kununu 4.7 score rests mainly on pre-2024 reviews. Recent Glassdoor reviews are markedly worse, and Revelio flags sentiment as "negative and declining".
- On-call is unverified for a real-time safety-monitoring product run by a small engineering team.
- 42% negative candidate experience on Glassdoor.

**Recommendation:** Do not apply now. Re-evaluate only if TWAICE (a) announces a priced equity round or reaches breakeven (the FY2025 accounts, likely filed in 2027, will show whether the loss has narrowed), and (b) opens a senior or staff engineering role. If both happen, verify during interviews: the salary band against the €85-110K bracket, the VSOP strike price relative to the 2022 round, the EIB loan covenants and the runway management communicates internally, whether layoffs are planned, on-call expectations for the monitoring platform, and how much of the role is Python versus TypeScript.

---

## Sources

- [TWAICE - Impressum / Legal notice](https://www.twaice.com/imprint)
- [TWAICE - Careers](https://www.twaice.com/careers)
- [TWAICE Personio XML job feed](https://twaice.jobs.personio.com/xml?language=en)
- [TWAICE - Full-Stack Software Engineer (Personio)](https://twaice.jobs.personio.com/job/2800467?language=de&display=en)
- [TWAICE - Working Student Battery & Data Analytics (Personio)](https://twaice.jobs.personio.com/job/2709378?language=de&display=en)
- [TWAICE - Senior Backend Engineer (Speedinvest/Getro mirror)](https://careers.speedinvest.com/companies/twaice/jobs/64706464-senior-backend-engineer-m-f-x-permanent-employees-full-time-remote-de)
- [TWAICE - Energy Systems Data Engineer (Speedinvest/Getro mirror)](https://careers.speedinvest.com/companies/twaice/jobs/77184519-energy-systems-data-engineer)
- [JobLeads - Senior Backend Engineer, TWAICE (salary estimate)](https://www.jobleads.com/de/job/senior-backend-engineer-mfx--munchen--e322376adefc3ff8ed76a8b5fe3a37054)
- [WeAreDevelopers - Energy Systems Data Engineer](https://www.wearedevelopers.com/jobs/ext/7055747/energy-systems-data-engineer)
- [TWAICE GitHub organisation (API)](https://api.github.com/orgs/twaice/repos)
- [NorthData - TWAICE Technologies GmbH, HRB 241903](https://www.northdata.de/TWAICE+Technologies+GmbH,+M%C3%BCnchen/Amtsgericht+M%C3%BCnchen+HRB+241903)
- [Handelsregister - HRB 241903 search](https://www.handelsregister.de/rp_web/search.do?registergericht=D2601&registerArt=HRB&registerNummer=241903)
- [handelsregister.ai - TWAICE (blocked by Cloudflare)](https://handelsregister.ai/de/unternehmen/TWAICE%20Technologies%20GmbH)
- [unternehmen24 - TWAICE annual accounts (paywalled)](https://www.unternehmen24.info/Handelsregister/Deutschland/Bilanz/Firma/4484186/Jahresabschluss%20zum%20Gesch%C3%A4ftsjahr%20vom%2001_01_2023%20bis%20zum%2031_12_2023)
- [GlobeNewswire - EIB Invests €24 Million in TWAICE (Feb 2026)](https://www.globenewswire.com/news-release/2026/02/05/3233053/0/en/EIB-Invests-24-Million-in-TWAICE-to-Accelerate-the-Energy-Transition-with-Predictive-Battery-Analytics.html)
- [electrive - Battery analytics startup Twaice secures €24 million](https://www.electrive.com/2026/02/05/battery-analytics-startup-twaice-secures-e24-million/)
- [EU-Startups - TWAICE secures €24M EIB loan](https://www.eu-startups.com/2026/02/munich-based-twaice-secures-e24-million-eib-loan-to-scale-predictive-battery-analytics-for-europes-energy-transition/)
- [Munich Startup - 24 million euros fill Twaice's coffers](https://www.munich-startup.de/en/news/24-million-euros-fill-twaices-coffers)
- [Energy-Storage.news - TWAICE gets US$26m funding](https://www.energy-storage.news/battery-software-startup-twaice-gets-us26m-funding-aiming-at-ev-and-energy-storage-markets)
- [tech.eu - TWAICE $26M Series B](https://tech.eu/brief/munich-based-battery-analytics-company-twaice-powers-up-with-26-million-in-series-b-round)
- [TWAICE newsroom - Series B funding](https://www.twaice.com/newsroom/series-b-funding)
- [TWAICE newsroom - New funding (Coatue)](https://www.twaice.com/newsroom/new-funding)
- [UVC Partners - TWAICE $30M led by Coatue](https://uvcpartners.com/blog/battery-analytics-platform-twaice-announces-30-million-funding-led-by-coatue)
- [Energize - Why We're Investing in TWAICE](https://medium.com/energize-insight/why-were-investing-in-twaice-8cc387ce32a3)
- [TechCrunch - Twaice raises €11M Series A led by Creandum](https://techcrunch.com/?p=1964518)
- [tech.eu funding database - TWAICE](https://funding.tech.eu/companies/2F1D16DA-7060-4E8B-9AD8-81F4C3BD6C16)
- [ZoomInfo - TWAICE funding](https://zoominfo.com/financial/twaice-technologies-gmbh/451237040)
- [Revelio Labs - TWAICE employees](https://www.reveliolabs.com/companies/twaice/employees)
- [LinkedIn - TWAICE company page](https://www.linkedin.com/company/twaice/)
- [electrive - Twaice ernennt neuen CTO (2022)](https://www.electrive.net/2022/02/03/twaice-ernennt-neuen-cto/)
- [TWAICE - Marc Paczian appointed CCO](https://www.twaice.com/newsroom/twaice-appoints-marc-paczian-as-cco)
- [Munich Startup - TWAICE combines battery expertise with AI](https://www.munich-startup.de/en/news/twaice-combines-battery-expertise-with-artificial-intelligence)
- [Munich Re - aiSure case study TWAICE](https://www.munichre.com/content/dam/munichre/contentlounge/website-pieces/documents/aiSure_Case_Study_Twaice_Factsheet.pdf/_jcr_content/renditions/original./aiSure_Case_Study_Twaice_Factsheet.pdf)
- [Energy-Storage.news - TWAICE software launch](https://www.energy-storage.news/german-startup-launches-software-aimed-at-balancing-battery-degradation-ver)
- [Glassdoor - TWAICE reviews (English)](https://www.glassdoor.co.uk/Reviews/TWAICE-Reviews-E2528930.htm)
- [Glassdoor - TWAICE Bewertungen (German)](https://www.glassdoor.de/Bewertungen/TWAICE-Bewertungen-E2528930.htm)
- [Glassdoor - TWAICE Germany reviews](https://www.glassdoor.co.uk/Reviews/TWAICE-Germany-Reviews-EI_IE2528930.0,6_IL.7,14_IN96.htm)
- [Glassdoor - TWAICE Munich reviews](https://www.glassdoor.co.uk/Reviews/TWAICE-Munich-Reviews-EI_IE2528930.0,6_IL.7,13_IC4990924.htm)
- [Glassdoor - TWAICE Software Engineer reviews](https://www.glassdoor.co.uk/Reviews/TWAICE-Software-Engineer-Reviews-EI_IE2528930.0,6_KO7,24.htm)
- [Glassdoor - TWAICE Senior Software Engineer reviews](https://www.glassdoor.co.uk/Reviews/TWAICE-Senior-Software-Engineer-Reviews-EI_IE2528930.0,6_KO7,31.htm)
- [Glassdoor - TWAICE interviews](https://www.glassdoor.co.uk/Interview/TWAICE-Interview-Questions-E2528930.htm)
- [Glassdoor - TWAICE salaries](https://www.glassdoor.co.uk/Salary/TWAICE-Salaries-E2528930.htm)
- [Kununu - TWAICE Technologies](https://www.kununu.com/de/twaice-technologies1)
- [Kununu - TWAICE reviews](https://www.kununu.com/de/twaice-technologies1/kommentare)
- [Kununu - TWAICE salaries](https://www.kununu.com/de/twaice-technologies1/gehalt)
- [levels.fyi - TWAICE (404)](https://www.levels.fyi/companies/twaice/salaries)
- [Teamblind - TWAICE (not found)](https://www.teamblind.com/company/TWAICE)
- [Great Place to Work Germany - search](https://www.greatplacetowork.de/?s=twaice)
- [Nominatim - Rosenheimer Str. 143C geocode](https://nominatim.openstreetmap.org/search?q=Rosenheimer+Stra%C3%9Fe+143C,+81671+M%C3%BCnchen&format=json&addressdetails=1)
- [Overpass API](https://overpass-api.de/api/interpreter)
