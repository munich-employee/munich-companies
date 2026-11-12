# Revolut - Full Research Report

_Researched: 2026-11-12_

> **Critical Disqualifiers**
> 1. **Systemic work-life-balance and performance-exit culture.** CEO-endorsed "exit underperformers fast" policy, quarterly performance reviews that reviewers describe as a firing mechanism, recurring 10-14 hour days and weekend work across engineering reviews on Glassdoor, Kununu and Blind (Blind WLB 2.3/5). Former engineers on Glassdoor rate WLB 2.3/5.
> 2. **Headline Glassdoor score is not representative.** The displayed 4.3 is driven by roughly 300 new reviews per month, 92% from current employees, most in their first weeks ("onboarding" reviews). The all-time average of rated reviews is 3.9, Blind is 3.0, Kununu is 2.5.
> 3. **No Munich office.** Germany presence is a Berlin branch; Munich work would be remote-first only, and current German engineering openings are Berlin-tagged and few (2 found).
>
> The full report follows for completeness.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 2015 (11 years) |
| Employees | ~12,000 globally (Mar 2026 press), "15,000+" per current job postings (Nov 2026) |
| Revenue (FY2025) | $6.0bn (£4.5bn), +46% YoY |
| Profitability | Profit before tax $2.3bn (£1.7bn, +57%), net profit $1.7bn, PBT margin 38%, fifth consecutive profitable year - **PASS** |
| Ownership | Private (Revolut Group Holdings Ltd, UK). Founder-led, VC/growth-equity backed. Latest secondary valuation $115bn (Jul 2026). IPO not expected before 2028 |
| Software-centric | Digital bank / financial "super app"; all products delivered through its own software stack - **PASS** (see Business Model) |

### Key People

- **Nik Storonsky** - co-founder and CEO since 2015; largest shareholder.
- **Vlad Yatsenko** - co-founder, first employee, CTO until 1 Jul 2026; now Non-Executive Director on the board.
- **Donato Lucia** - VP of Technology (title replaced CTO) since Jul 2026; joined 2018 as a senior software engineer, Head of Technology from Apr 2025.

### Funding History

| Date | Round | Amount | Valuation |
|---|---|---|---|
| 2016 | Series A (Balderton) | ~$10M | n/a |
| Apr 2017 | Series B (Index, Ribbit) | ~$66M | n/a |
| Apr 2018 | Series C (DST Global) | $250M | $1.7bn |
| Feb-Jul 2020 | Series D (TCV) + extension | $500M + $80M | $5.5bn |
| Jul 2021 | Series E (SoftBank, Tiger) | $800M | $33bn |
| Aug 2024 | Secondary (employee/investor) | ~$500M | $45bn |
| Nov 2025 | Secondary (Coatue, Greenoaks, Dragoneer, Fidelity; Nvidia, a16z new) | undisclosed | $75bn ($1,381/share) |
| Jul 2026 | Secondary (Glade Brook, Coatue, Durable, T. Rowe Price, Baillie Gifford) | ≥$750M | $115bn ($2,017/share) |

Secondaries since 2024 are liquidity events for staff and early investors; no primary capital has been needed since 2021.

### Business Model

Revolut is a licensed bank in the EEA (Revolut Bank UAB, Lithuania; operating in 30 EEA markets), launched full UK banking in 2026 after the mobilisation period, and in 2026 also launched in Mexico, Australia and New Zealand, gained licences in France, Colombia and Argentina, and obtained conditional US OCC charter approval. Revenue is from cards/interchange, FX, subscriptions (Premium/Metal/Ultra), interest on $67.5bn of customer balances, trading/crypto, and business accounts (767K business customers). Engineering builds the core banking, payments, fraud and app stack in-house. Not consulting.

---

## Section 2: Local Commercial Entity in Germany

Verified on NorthData (via Chromium/CDP) and on Revolut's own German legal pages.

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **Revolut Ltd. Zweigniederlassung Deutschland** | HRB 211556 B, Amtsgericht Charlottenburg (registered Oct 2019) | Unter den Linden 40, 10117 Berlin | "Technologieentwicklung für die Revolut Ltd. sowie allgemeine Tätigkeiten, wie Übersetzungen für die App und die Entwicklung von Funktionen für den europäischen Markt, Unterstützung beim Aufbau und der Entwicklung von Prozessen ... (keine regulierten Finanzdienstleistungen)" |
| **Revolut Bank UAB, Zweigniederlassung Deutschland** | HRB 249024 B, Amtsgericht Charlottenburg; LEI 984500B51DA59678DA35 | Unter den Linden 40 (Fora Linden Palais), 10117 Berlin | Banking services of the Lithuanian bank in Germany (deposits, lending, payments, e-money, FX); BaFin-supervised for German branch activity |

**Verification:** The Revolut Ltd branch was registered in 2019 alongside the announced Berlin tech hub, and its registered purpose explicitly names technology development and feature development for the European market. This is an engineering entity, not a sales shell. It is a branch (Zweigniederlassung) of a UK Ltd, not a German GmbH, so German employment contracts run through the branch of the UK parent; it files only an exempting annual statement ("Befreiender Jahresabschluss") in Germany. Glassdoor reviews from engineers located in Berlin, Munich, Oberhausen, Frankfurt and Berchtesgaden, and levels.fyi submissions from Berlin engineers, confirm that engineers are employed in Germany directly (no EOR signal found).

**Verdict:** PASS (Berlin branch with a technology-development purpose; no Munich entity or office)

---

## Section 3: Office Location

- **Office address:** Unter den Linden 40, 10117 Berlin (Dorotheenstadt, Mitte), inside the Fora Linden Palais flexible-office building. Confirmed by Revolut's German legal notice and NorthData; Nominatim geocodes it to the Fora building (52.5172, 13.3864). The 2019 tech-hub announcement placed the hub on Friedrichstraße, a few hundred metres away; no current source shows a separate engineering office. **There is no Munich office.** The only Revolut presence in Munich is a card self-service machine at Munich Airport.
- **Nearest public transport (OSM Overpass):**
  - U Unter den Linden (U5, U6) - ~170 m
  - Bus stops Unter den Linden/Glinkastraße (~110 m) and U Unter den Linden (~120 m)
  - U Französische Straße - ~320 m
  - S+U Friedrichstraße (S-Bahn, U6, regional rail) - ~340-380 m
  - S+U Brandenburger Tor (U5, S-Bahn) - ~370 m
- **Work model:** Remote-first for existing (non-graduate) employees, confirmed by Revolut in June 2026 when it moved 2027 graduates and interns to 3 office days a week. Staff can work from abroad up to 120 days a year. Glassdoor reviews from Germany-based engineers repeatedly cite remote work ("They really mean the remote-first approach", Glassdoor, Nov 2026, current Software Engineer, Oberhausen). However, job postings list specific "Remote: <country>" eligibility per role; current engineering postings on revolut.com list Poland, Portugal, Spain, UAE, UK, Cyprus, Romania, Serbia, not Germany. The two German engineering postings found (LinkedIn) are tagged Berlin. Remote-from-Munich is therefore possible in principle but depends on whether a given role is opened for Germany.

---

## Section 4: Reviews

**GPTW:** Revolut is Great Place to Work certified in the UK (profile updated Oct 2025: "99% of employees at Revolut say it is a great place to work"), and job postings claim GPTW certification company-wide. No GPTW Germany certification or Best Workplaces listing found on greatplacetowork.de. The 99% figure is hard to reconcile with Glassdoor's all-time 74% recommend rate and Blind's 3.0; treat it as a weak signal.

### Glassdoor

Retrieved via Chromium/CDP using Glassdoor's in-page reviews endpoint (the reviews page defaults to German-language reviews only for this logged-in profile; the API was queried with all English-language reviews worldwide plus location and job-title filters). "Displayed" = Glassdoor's recency-weighted headline rating.

| Metric | Global | Germany | Munich | Software Engineers | Senior Software Engineers |
|---|---|---|---|---|---|
| **Overall** | 4.3 (7,165 rated) | 4.5 (62) | 4.7 (5) | 4.5 (231) | 4.3 (114) |
| **WLB** | 4.0 | 4.1 | 3.9 | 4.0 | 3.7 |
| **Culture & Values** | 4.2 | 4.6 | 3.9 | 4.4 | 4.1 |
| **Comp & Benefits** | 4.4 | 4.6 | 4.0 | 4.7 | 4.6 |
| **Career Opportunities** | 4.4 | 4.7 | 4.6 | 4.7 | 4.4 |
| **Diversity & Inclusion** | 4.5 | 4.7 | 4.7 | 4.6 | 4.5 |
| **Senior Management** | 4.2 | 4.5 | 4.6 | 4.4 | 4.3 |
| **% Recommend** | 84% | 95% | 100% | 92% | 83% |
| **CEO Approval** | 94% | 98% | 100% | 96% | 94% |
| **Business Outlook** | 80% positive | 86% positive | 100% positive | 82% positive | 86% positive |

Munich (5 reviews) and Germany Software Engineers (6 reviews, all 5.0) are too small to be meaningful. Germany (62) is directional.

**The headline numbers are inflated by review volume from new joiners.** Analysis of the underlying data:

| Signal | Value |
|---|---|
| All-time mean of rated reviews (global, 7,113 with stars) | **3.90** overall, **3.59** WLB, **3.76** culture, **3.67** senior management, 74% recommend |
| All-time mean, Germany (59 rated) | 4.05 overall, **3.38** WLB, 80% recommend |
| Last 300 global reviews (12 Oct - 10 Nov 2026, i.e. ~300/month) | 4.49 average, 73% five-star, **92% current employees**, most with under 1 year tenure; titles dominated by "onboarding" |
| Engineering reviews (SWE + Senior SWE + Backend, 360 reviews) - **current** employees (309) | 4.37 overall, 3.67 WLB |
| Engineering reviews - **former** employees (51) | **3.33** overall, **2.32** WLB |

Engineering reviews by year (same 360-review sample):

| Year | Reviews | Overall | WLB |
|---|---|---|---|
| 2020 | 15 | 2.87 | 2.00 |
| 2021 | 15 | 3.40 | 2.67 |
| 2022 | 14 | 3.50 | 2.69 |
| 2023 | 29 | 3.97 | 3.15 |
| 2024 | 37 | 4.00 | 3.10 |
| 2025 | 75 | 4.25 | 3.35 |
| 2026 | 164 | 4.55 | 4.02 |

The 2026 jump coincides with a 4x increase in volume, almost entirely from current employees in their first months. Reviews from engineers who have stayed long enough to go through quarterly performance cycles, or who have left, are materially lower.

### Kununu

Fetched via Chromium/CDP (curl returned HTTP 405). Slug: `revolut` (Berlin profile, unclaimed, no logo).

- **Overall score:** 2.5 / 5.0 (industry average for banks: 3.8)
- **Recommendation rate (Weiterempfehlung):** 43% (last 2 years); 50% across all employee reviews
- **Total reviews:** 27 (employee reviews: 10; rest are applicant reviews)
- **Sub-scores:** Karriere & Gehalt 2.5, Unternehmenskultur 2.6, Arbeitsumgebung 2.3, Vielfalt 2.6
- **Kununu Top Company:** NO

Mostly sales, finance and operations staff in Berlin; one Führungskraft in IT (4.5, Sep 2025).

### Blind / Teamblind

Fetched via Chromium/CDP. **3.0 / 5** (130 reviews): Career Growth 3.3, **Work Life Balance 2.3**, Compensation/Benefits 3.4, Company Culture 2.4, Management 2.4. Blind is the platform least affected by the onboarding-review wave and is consistent with the Glassdoor former-employee numbers.

### Review Themes (2024-2026)

**Positives:**

- **Compensation above local markets**, with bonuses and RSUs: "Salary is in the top range of the market. Potential bonuses for middle are up to 40% of yearly salary (50% cash and 50% stocks)" (Glassdoor, May 2026, former Software Engineer, Kraków); "High compensation, excellent RSU package, and very fast career growth" (Glassdoor, Oct 2026, current ML Scientist, Berlin, 2 years).
- **Strong engineering bar and practices:** "strong technical culture, all tech decisions are challenged and reviewed by experienced engineers" (Glassdoor, Jun 2025, current Senior Software Engineer, Berlin, 4 years); "production deployments happen every day ... pretty strict code quality rules" (Glassdoor, Feb 2026, current Senior Software Engineer, Kraków, 2 years).
- **Remote-first and structured onboarding:** "I just joined but my onboarding process was very well structured ... They really mean the remote-first approach" (Glassdoor, Nov 2026, current Software Engineer, Oberhausen, ~1 year); "Great opportunities to learn and grow ... High standard of engineering practices ... Ability to work remotely" (Glassdoor, Nov 2026, current Software Engineer, München).
- **Meritocratic, data-driven promotion:** "Career progress based on merit Good pay Interesting projects no bureaucracy" (Blind, Jul 2026, current Software Engineer).

**Negatives:**

- **Long hours and weekend work (red flag: WLB, 24/7):** "Intense pressure 60+ hours per week work ... Not a place for people with kids" (Glassdoor, Jul 2026, current Senior Software Engineer, London, 1 year); "People work here for more than 10 hours a dey. You usually see PRs submitted at nigth" (Glassdoor, Aug 2026, current Software Engineer, Kraków, 1 year); "Work-life balance is non-existent. Expect long hours and pings on weekends" (Glassdoor, Mar 2026, former Senior Software Engineer, Dubai). Blind WLB 2.3.
- **Expected unpaid overtime (red flag):** "The head of my department explicitly told me the expectation is to work overtime ... consistently need to work 10+ hours per day (some days even 12-14 hours) ... Covering dinner delivery at the office only if staying to work very late" (Glassdoor, Nov 2025, former Product Owner, Berlin, 1 year).
- **Performance reviews used to push people out, failed probations (red flag: silent firings):** "Management keeps giving low performance grades even if you have done well with non transparent calibration process to push you to work more" (Glassdoor, Mar 2026, current Senior Software Engineer, 2 years); "A good percentage of the employees don't make it past the probation. And trust me, it is not about those employees" (Glassdoor, Oct 2025, current Senior Software Engineer, 1 year); "Gefühlt wurden alle drei Monate Leute aus dem Team entlassen ... Auch ich wurde nach sechs Monaten gekündigt - gerade einmal drei Tage vor dem Ende meiner Probezeit" (Kununu, Sep 2026, Ex-Angestellte/r oder Arbeiter/in, Vertrieb / Verkauf, Berlin).
- **Fear and public shaming:** "Standard management practice includes 'public floggings' in Slack. If a metric drops ... they will tag you in front of hundreds of people in a public channel ... a 'hire and fire' culture" (Blind, Jun 2026, current Financial Accountant); "stress, mobbing, humiliation, working in constant fear" (Glassdoor, Feb 2026, current Software Engineer, 2 years).
- **KPI-driven, low-collaboration culture:** "You're not rewarded to help and are evaluated based on goals ... This creates a competitive unhealthy environment. We don't implement the best engineer solution - because that requires collaboration" (Glassdoor, Oct 2026, former Software Engineer, Portugal).
- **Homegrown framework constraints for seniors:** "Revolut widely uses a homegrown framework ... based on a CQRS-style approach ... designed primarily for ledger-like web services ... it becomes inadequate in use cases that are not ledger-like ... you may then be compared to teams that don't face the same constraints and be blamed" - review titled "Great for Mids, Awful for Seniors+" (Glassdoor, Feb 2026, current Senior Software Engineer, Kraków, 2 years).
- **Micromanagement and untrained managers:** "A lot of people with no management training somehow become managers and then ruin the life of the people they are meant to manage" (Glassdoor, Oct 2025, current Senior Software Engineer, 2 years).

These themes recur across Glassdoor, Kununu and Blind, in every year from 2020 to 2026, and in engineering as well as sales/ops reviews.

### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | **Present, top-down.** CEO publicly advocates "exiting underperformers as fast as possible" with six weeks to reach "above bar" (2024 QuantumLight report). Reviewers: "Some Toxic managers" (Glassdoor, Nov 2025, former Middle Frontend Developer, 3+ years); "Die Struktur innerhalb des Teams habe ich als extrem toxisch und belastend erlebt, insbesondere im Zusammenspiel mit dem Management" (Kununu, Sep 2026, Ex-Angestellte/r, Vertrieb / Verkauf, Berlin). |
| 24/7 Work Expectation | **Present.** "pings on weekends" (Glassdoor, Mar 2026, former Senior SWE, Dubai); "most of them worked all weekends constantly" (Glassdoor, May 2026, former SWE, Kraków). |
| Internal Surveillance | **Some signal.** Revolut publicly promoted an employee compliance-tracking system (employeebenefits.co.uk); a reviewer reports output measured by lines of code: "They evaluate your performance based on how many lines of code you have written" (Glassdoor, Aug 2026, current SWE, Kraków). No direct monitoring-software reports found. |
| Fear-driven Management | **Present.** "No sense of safety if you do mistakes" (Glassdoor, Mar 2026, current Senior SWE); "Toxic culture where people compete to save their jobs" (Glassdoor, May 2026, current SWE, London); Slack "public floggings" (Blind, Jun 2026). |
| Communication Breakdown | **Moderate.** "All the communication is top down" (Glassdoor, Mar 2026, current Senior SWE); "Everyone too busy to help or give context" (Glassdoor, Jul 2026, current Senior SWE, London). |
| Unpaid Overtime | **Present.** Explicit overtime expectation from a department head (Glassdoor, Nov 2025, former PO, Berlin); "Workload 10x times the average" (Glassdoor, Feb 2026, current SWE). |
| Silent Firings | **Present and systemic.** Quarterly performance-review exits (Nov 2026 press: Revolut says exits "align with routine quarterly performance assessments ... and do not constitute a formal layoff program"); 2020 Wired investigation of ~50 staff pushed to resign; repeated reports of failed probations. |
| Work-Life Balance issues | **Present.** Blind WLB 2.3; Glassdoor former engineers 2.3; Germany all-time WLB 3.4; Kununu "Man arbeitet 12 Stunden oder noch mehr" (Kununu, Jul 2021, Angestellte/r, Vertrieb / Verkauf, Berlin). |

**Risk level: HIGH.** This is (a) systemic and set from the top: the performance philosophy is articulated by the CEO, embedded in the "Never Settle / 10x people" values on the careers page, and visible across countries, departments and years. It is not (b) large-company bureaucracy, and not merely (c) localised team dysfunction, although several reviewers note intensity varies by team (FinCrime, crypto and retail named as hardest).

---

## Section 5: Compensation

### Salary Data

levels.fyi and Glassdoor fetched via Chromium/CDP.

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| levels.fyi (Germany) | Middle Software Engineer | ~€87K | ~€3K | ~€5K | ~€96K | small (Germany ~10, 3 unlocked) |
| levels.fyi (Germany) | Senior Software Engineer | ~€121K | ~€31K | ~€7K | ~€158K | small |
| levels.fyi (Germany) | Lead Software Engineer | ~€120K | ~€4K | €0 | ~€124K | small |
| levels.fyi (Germany) | All SWE, median | - | - | - | ~€130K | - |
| levels.fyi (Berlin, unlocked) | Senior SWE, Back-End, 12 yrs | €132K | - | - | €157K | 1 (Nov 2025) |
| levels.fyi (Berlin, unlocked) | Senior SWE, Front-End, 10 yrs | €133K | - | - | €133K | 1 (Jan 2026) |
| levels.fyi (UK, reference) | Senior / Lead SWE | €126K / €143K | €18K / €45K | €3K / €3K | €147K / €191K | 435 SWE globally |
| Glassdoor (Germany) | Senior Software Engineer | - | - | - | €110K-€165K range, ~€115K average | 21 |
| Glassdoor (Germany) | Software Engineer | - | - | - | €90K-€123K | 18 |
| Glassdoor (Germany) | Backend Software Engineer | - | - | - | €91K-€197K | 3 |
| Job postings | Software Engineer (Python/Java), Poland | PLN 9.5-40K / 25.5-40K gross monthly | - | - | - | Germany: "discussed during the interview" |

Munich-specific median/75th/90th percentiles: not available (no Munich office; 5 Munich Glassdoor reviews and no Munich salary submissions). Reference used across this research set: Munich senior SWE market **€100-150K+ base**, staff **€130-180K+**; median total comp at large, profitable Munich employers ~€95-130K.

### Equity / Stock

Private-company share options/RSUs with a 4-year schedule, 25% per year (levels.fyi vesting chart, employee reports). Part of the performance bonus is paid in shares (reviewer: bonus "50% cash and 50% stocks"). Stock averaged ~32% of total comp for engineers in an earlier levels.fyi analysis, but only for a subset. **Liquidity is real but episodic:** five employee secondary sales to date (2021, 2024, Nov 2025, Jul 2026...), typically allowing up to 20% of vested holdings, restricted to staff with 1+ year tenure not on gardening leave. The valuation rose from $45bn to $115bn in two years, which has made recent grants valuable on paper. Reviewers flag the risk: "stocks are not real money ... good compensation puts you in a golden cage" (Glassdoor, Jun 2025, current Senior Software Engineer, Berlin, 4 years); a 2026 report described ex-staff being offered a discounted exit price for their shares. No IPO before 2028.

### Verdict

Senior total comp of ~€130-160K in Germany (base ~€120-133K) sits in the upper half of the large, profitable Munich corporate bracket; including equity at current valuation it is above it. Staff/Lead-level German data is too thin to judge (the one Lead average, €124K, is below Senior). Note that German pay is "discussed during the interview" rather than banded, and comp is weighted to variable bonus and illiquid stock dependent on quarterly performance ratings.

**COMPARABLE to ABOVE** (cash comparable at senior level, above with equity; staff band UNVERIFIED)

---

## Section 6: AI/ML & Tech Stack

### AI Strategy

Substantial and genuine:

- **Revolut Research** (launched Aug 2025): dedicated AI research division building **PRAGMA**, a family of foundation models for banking event sequences, reported to outperform production models on historical data.
- **Production ML at scale:** fraud/security models review nearly one billion transactions a month; credit, FinCrime alerting and transaction monitoring are ML-driven (much of it run from the India capability centre).
- **AI platform:** Berlin posting for a Senior AI Platform Engineer building self-service model training, distributed training and inference on shared GPU infrastructure (Flyte/Ray on Kubernetes), with multi-tenant isolation and cost visibility.
- **AI-assisted engineering:** ~2,000 engineers moved from Claude Code / Codex to self-hosted open-weight GLM models on 56 Nvidia B200 GPUs (2026), cutting inference cost ~90% and reporting 60% faster coding time (company-reported at the AI Engineer conference).
- **Product AI:** AI assistant and AI automation platforms (Applied AI Engineer posting, Berlin).

Nvidia became an investor in Nov 2025. This is applied, production AI plus a research arm, not marketing.

### Tech Stack

Derived from job postings (revolut.com careers and LinkedIn, Germany and other EU hubs, Nov 2026), Glassdoor engineer reviews, and conference coverage.

| Category | Technologies |
|---|---|
| **Primary language(s)** | Java 17/21 (backend microservices, payments, risk, fraud), Python (APIs, data pipelines, event consumers, ML platform), Kotlin/Scala (nice to have), Swift/Kotlin (mobile), TypeScript/web |
| **AI/ML** | PyTorch, TensorFlow/Keras, LLMs (self-hosted GLM; Claude/Codex as exceptions), Flyte, Ray, in-house foundation models (PRAGMA) |
| **Cloud** | GCP (primary), own bare-metal Kubernetes and GPU clusters (hybrid cloud) |
| **Infrastructure** | Kubernetes, Docker, Ansible, TeamCity, Ceph, MinIO, IaC; Grafana, Prometheus, New Relic |
| **Data** | PostgreSQL, Redis, jOOQ, Flyway, SQL-heavy data pipelines, event-driven (CQRS-style homegrown framework) |
| **Other** | Spock (testing), TDD/DDD, daily production deploys, homegrown application framework |

**Summary:** Java-centric backend engineering with a large Python layer for APIs, data pipelines and the ML/AI platform, on GCP plus self-operated bare-metal Kubernetes and GPU infrastructure. Applied production AI in a regulated banking domain, with a smaller in-house foundation-model research effort.

---

## Section 7: Language

All engineering postings are in English and require "Fluency in English"; German appears only for customer-facing roles (e.g. "FinCrime Escalations Officer - German", "Account Executive (SMB) - German"). Engineering teams are distributed across 40+ offices with English as the working language; reviewers from Berlin note "langsame Entwicklungschancen, wenn man nicht in UK sitzt" (Glassdoor, Oct 2025, former Product Marketing Manager, Berlin), i.e. the centre of gravity is London, not Germany.

**Verdict:** PASS

---

## Section 8: Stability

### Financial Position

- FY2025: revenue $6.0bn (+46%), PBT $2.3bn (+57%), net profit $1.7bn, PBT margin 38%. Fifth consecutive profitable year.
- Customer balances $67.5bn (+66%); 68.3M retail and 767K business customers at end-2025; 80M+ retail by Nov 2026.
- Valuation $115bn (Jul 2026 secondary), Europe's most valuable private company.
- Regulatory expansion in 2026: full UK banking, Mexico, Australia, New Zealand; licences in France, Colombia, Argentina; conditional US national bank charter (activation targeted H1 2027).
- Cash/CET1 not retrieved from the annual report text; not material given profitability and absence of funding needs.

### Financial Runway

Not applicable: the company is profitable and has not raised primary capital since 2021.

### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| May-Jun 2020 | COVID redundancies | 62 announced (~3%) | Plus ~50 staff in Poland and Portugal reportedly pushed to resign or accept "mutual agreements" (Wired investigation); Revolut said it complied with local law |
| Sep 2022 | Cost review | Graduate offers withdrawn | Sweeping cost-cutting review (Irish Times) |
| Mar 2026 | Reported cut | ~200 (~2.5%) | Listed on Blind's layoff tracker per search snippet; tracker page now returns 404; **UNVERIFIED** |
| Mar 2026 | India shift | n/a | Plan to base ~40% of global workforce (5,500) in its India capability centre by end-2026, incl. product development, payments and fraud functions |
| Nov 2026 | Performance-based exits | "Dozens" | Mainly Revolut Business (SME) sales roles in UK and Europe; Revolut: aligned with "routine quarterly performance assessments ... not a formal layoff program". Concurrent with AI-efficiency push |

TrueUp lists "No known layoffs" because most exits run through performance reviews rather than announced programmes, which is exactly the pattern of concern.

### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | **UNKNOWN (no evidence found)** | Web search "Revolut Betriebsrat Berlin" returned nothing; no Kununu review mentions one; no LinkedIn/press reference. Small German headcount, remote-first and mostly sales/ops in Berlin |
| Collective agreement | **NONE found** | No posting mentions Tarif/AT-Vertrag; German pay "discussed during the interview"; branch of a UK Ltd, no sign of AGV Banken membership |
| European works council (multinationals) | **NO evidence found** | None referenced in annual-report coverage or press |
| Conflict signals | Historical: 2020 Wired report of coerced resignations in Poland/Portugal; Polish lawyers said practice could breach local law | fintechfutures, fintech.global, Wired |

No council and no collective agreement, combined with a documented performance-exit culture and quarterly review cycles, is the configuration that earlier research associated with silent firings.

**Verdict:** CAUTION (financially very stable; employment stability per individual is low)

---

## Section 9: Regulated Industry

Heavily regulated: Revolut Bank UAB is a Lithuanian/ECB-supervised credit institution (Bank of Lithuania), with BaFin supervision of the German branch's activities; Revolut NewCo UK Ltd is PRA/FCA regulated; MiFID II for trading; DORA applies. The Bank of Lithuania fined Revolut Bank €3.5M in Apr 2025 for AML monitoring failures (largest in its history). Engineering impact: compliance and FinCrime controls are a large part of the workload (the Python posting describes "heavily regulated financial systems" and "automated financial crime quality controls"); a reviewer complains about "stupid forms all the time" (Glassdoor, Sep 2026, current Frontend developer, Berlin, 1+ year). Despite this, engineers report daily production deploys, so the regulatory overhead does not appear to slow delivery much.

**Verdict:** CAUTION

---

## Section 10: On-Call

The Java and Python SWE postings and the Berlin AI Platform posting do not mention an on-call rota explicitly, but the AI Platform role requires "operational ownership", DevOps/SRE roles list incident response and postmortems, and Revolut runs a 24/7 consumer bank where product teams own their services. Reviews mention "pings on weekends" and night-time PRs. Expect on-call or at least out-of-hours incident involvement for backend and platform teams; ML research or internal tooling may be lighter.

**Verdict:** CAUTION (team-dependent, likely present for backend/platform)

---

## Section 11: Interview Process

Glassdoor (3,979 interviews, all roles; via Chromium/CDP).

| Metric | Value |
|---|---|
| Difficulty | 3.1 / 5 (sum 12,083 over 3,927 ratings) |
| Positive experience | 37% (negative 42%, neutral 21%) |
| Average duration | ~2-8 weeks in recent SWE reports (aggregate not exposed) |
| Rounds | ~5 for SWE |

Typical SWE process (Glassdoor, Oct-Nov 2026): recruiter screen, online coding assessment, HR interview on experience and projects, recruiter preparation call, live-coding interview (small project build plus a tech talk on SQL, SOLID, design), and for senior roles a system-design round and a "bar raiser". A Warsaw SWE who accepted an offer reported "about 5 rounds, most of them were surprisingly sensible, no blind leetcode grinding" (Glassdoor, Nov 2026). Others describe it as "very long and exhausting" (Glassdoor, Apr 2026, current SWE, Vilnius). Practical coding and design rather than LeetCode-heavy; the negative-experience share (42%) is high, largely from non-engineering candidates citing rushed or ghosted processes.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | PASS - digital bank built entirely in-house |
| Not consulting | PASS |
| Profitable | PASS - $2.3bn PBT 2025, 38% margin |
| Employee count | ~12,000-15,000 globally; small German headcount |
| English-speaking | PASS - English working language |
| Local entity + engineering contracts | PASS - Revolut Ltd. Zweigniederlassung Deutschland (HRB 211556 B), purpose "Technologieentwicklung" |
| Location / work model | No Munich office; Berlin (Unter den Linden 40). Remote-first contracts, but German eligibility is per role and rarely offered for engineering |
| Glassdoor | Displayed 4.3 global / 4.5 SWE, but inflated by new-joiner reviews; all-time 3.9, former engineers 3.3 (WLB 2.3) - **FAIL in substance** |
| Kununu | 2.5, 43% recommend (10 reviews) - FAIL |
| Salary | COMPARABLE to ABOVE (~€130-160K senior TC in Germany; staff band unverified) |
| AI/ML content | Strong - AI platform (Flyte/Ray/GPU), foundation-model research, self-hosted LLM tooling |
| Computer-language/Tech-stack | Java-centric with a substantial Python layer; GCP + bare-metal K8s |
| No on-call | CAUTION - likely for backend/platform |
| WLB / Stability | Company very stable; WLB poor (Blind 2.3), individual job security low |
| Works council / collective agreement | None found - CAUTION |
| Regulated industry | CAUTION - EU/UK bank, BaFin branch, AML fine 2025 |
| Review themes | Long hours, unpaid overtime, fear-driven quarterly reviews, failed probations, public shaming; offset by pay, strong engineers, remote work |
| Leadership change | CTO co-founder stepped down Jul 2026; VP Technology now leads engineering |
| Offshoring | 40% of workforce to be based in India by end-2026, including product development |

---

## Section 13: Verdict

**Exclude.** Revolut is one of the most financially successful software companies in Europe and has genuine, interesting AI platform work, but its working culture fails the work-life-balance and silent-firing criteria in a way that is systemic, documented over six years, and stated openly by its leadership.

**Strengths.** Highly profitable and growing fast ($6bn revenue, 38% PBT margin, $115bn valuation, regular employee liquidity). A real German engineering entity in Berlin. English working language. Senior compensation in Germany at or above the Munich large-corporate bracket, with equity that has tripled in value in two years. Serious applied AI: a GPU-backed AI platform team (Flyte, Ray, Kubernetes) hiring in Berlin, a foundation-model research division, and fraud ML at a billion transactions a month. Remote-first contracts for experienced hires.

**Hard blockers:**

1. **Work-life balance.** Blind WLB 2.3/5 (130 reviews); former engineers on Glassdoor 2.3/5 (51 reviews); Germany all-time Glassdoor WLB 3.4; repeated, specific reports of 10-14 hour days, weekend work, explicit overtime expectations from department heads, and dinner provided only for staying late. The displayed 4.0 Glassdoor WLB comes from a wave of reviews written in the first weeks of employment (300/month, 92% current, mostly "onboarding").
2. **Silent firings / performance-managed exits.** The CEO's published philosophy is to exit underperformers within six weeks; Revolut itself describes the Nov 2026 exits as "routine quarterly performance assessments"; reviewers report non-transparent calibration, failed probations "not about those employees", and dismissals days before probation ends. No works council or collective agreement provides a check on this in Germany.
3. **Toxic leadership risk HIGH and systemic**, embedded in company values ("Never Settle ... Revolut is for 10x people") rather than confined to teams.

**Secondary concerns.** No Munich office, and current German engineering openings are Berlin-tagged and rare (2 found), with most engineering hiring in Poland, Portugal, Spain, UAE and India. Java-centric core with a homegrown CQRS framework that a senior reviewer says penalises teams whose domain does not fit it. Likely on-call for backend/platform roles. Heavily regulated bank with recent AML enforcement. Engineering leadership transition (co-founder CTO left the executive role Jul 2026). Workforce shift to India (40% by end-2026) and an AI-efficiency push that the press links to headcount discipline.

**Recommendation:** Do not apply. Nothing short of a verifiable change in performance-management practice (published review criteria, end of quarterly exit cycles) and a sustained improvement in former-employee and Blind ratings would change this. If an AI Platform role in Germany is nonetheless considered for its technical content, verify in interviews: remote eligibility from Munich, the team's actual hours and on-call rota, quarterly rating distribution and probation pass rate for the team, the Germany salary band for the level, and the bonus/stock split.

---

## Sources

- [Revolut 2025 Annual Report (PDF)](https://assets.revolut.com/pdf/annualreport2025.pdf)
- [Revolut: record profit of $2.3bn for 2025 as revenue surges to $6bn](https://www.revolut.com/en-AT/news/revolut_reports_record_profit_of_2_3bn_for_2025_as_revenue_surges_to_6bn/)
- [Payment Expert: Revolut 2025 annual report](https://paymentexpert.com/2026/03/24/revolut-2025-annual-report/)
- [Irish Examiner: Pre-tax profit at Revolut up 57%](https://www.irishexaminer.com/business/companies/arid-41815694.html)
- [Crowdfund Insider: Revolut reaches $115B valuation amid performance-driven staff reductions (Nov 2026)](https://www.crowdfundinsider.com/2026/11/321476-revolut-reaches-115b-valuation-amid-performance-driven-staff-reductions-and-ai-efficiency-push/)
- [tech.eu: Revolut confirms secondary share sale at $115BN (Jul 2026)](https://tech.eu/2026/07/22/revolut-confirms-fresh-secondary-share-sale-at-reported-115bn-valuation/)
- [Sifted: Revolut $115bn valuation secondary share sale](https://sifted.eu/articles/revolut-115-valuation-secondary-share-sale/)
- [tech.eu: Revolut valued at $75BN, Nvidia and a16z join](https://tech.eu/2025/11/24/revolut-valued-at-75bn-with-nvidia-and-a16z-joining-investor-roster/)
- [The Block: Revolut reaches $75 billion valuation](https://www.theblock.co/news/business/2025-11-24-revolut-75-billion-usd-valuation-380141)
- [The Next Web: Revolut co-founder steps down as CTO](https://thenextweb.com/news/revolut-cto-yatsenko-steps-down)
- [Sifted: Revolut cofounder Vlad Yatsenko quits CTO role](https://sifted.eu/articles/revolut-cofounder-vlad-yatsenko-quits-cto/)
- [NorthData: Revolut Ltd. Zweigniederlassung Deutschland, HRB 211556 B](https://www.northdata.de/Revolut%20Ltd%C2%B7%20Zweigniederlassung%20Deutschland,%20Berlin/Amtsgericht%20Charlottenburg%20(Berlin)%20HRB%20211556%20B)
- [NorthData: Revolut Bank UAB, Zweigniederlassung Deutschland, HRB 249024 B](https://www.northdata.de/Revolut+Bank+UAB,+Zweigniederlassung+Deutschland,+Berlin/Amtsgericht+Charlottenburg+(Berlin)+HRB+249024+B)
- [LEI record: Revolut Bank UAB, Zweigniederlassung Deutschland](https://www.leinumber.com/leicert/984500B51DA59678DA35/)
- [Revolut German legal notice (MiFID terms)](https://www.revolut.com/de-DE/legal/mifid/)
- [TechCrunch: Revolut opens tech hub in Berlin (2019)](https://techcrunch.com/2019/07/10/revolut-opens-tech-hub-in-berlin)
- [Finextra: Revolut to open tech centre in Berlin](https://finextra.com/newsarticle/34103/revolut-to-open-tech-centre-in-berlin)
- [Munich Airport: Revolut self-service machine](https://www.munich-airport.com/revolut-self-service-machine-40355900)
- [OpenStreetMap Nominatim](https://nominatim.openstreetmap.org/) and [Overpass API](https://overpass-api.de/)
- [Irish Times: Revolut scraps remote-first working for graduate hires (Jun 2026)](https://www.irishtimes.com/business/2026/06/26/revolut-scraps-remote-first-working-for-graduate-hires/)
- [Fortune: Revolut makes office compulsory for new grads](https://fortune.com/2026/06/30/remote-first-fintech-company-revolut-office-compulsory-for-new-gen-z-grads-earn-flexibility-one-year/)
- [Glassdoor: Revolut overview](https://www.glassdoor.com/Overview/Working-at-Revolut-EI_IE1176471.11,18.htm)
- [Glassdoor: Revolut reviews](https://www.glassdoor.de/Bewertungen/Revolut-Bewertungen-E1176471.htm)
- [Glassdoor: Revolut interviews](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/Revolut-Fragen-im-Vorstellungsgespr%C3%A4ch-E1176471.htm)
- [Glassdoor: Revolut salaries Germany](https://www.glassdoor.de/Gehalt/Revolut-Deutschland-Geh%C3%A4lter-EI_IE1176471.0,7_IL.8,19_IN96.htm)
- [Glassdoor review: Great for Mids, Awful for Seniors+](https://www.glassdoor.com/Reviews/Employee-Review-Revolut-E1176471-RVW102838451.htm)
- [Kununu: Revolut](https://www.kununu.com/de/revolut)
- [Kununu: Revolut reviews](https://www.kununu.com/de/revolut/kommentare)
- [Blind: Revolut reviews](https://www.teamblind.com/company/Revolut/reviews)
- [Great Place to Work UK: Revolut](https://www.greatplacetowork.co.uk/certified-company/1573841)
- [levels.fyi: Revolut SWE Germany](https://www.levels.fyi/companies/revolut/salaries/software-engineer/locations/germany)
- [levels.fyi: Revolut SWE UK](https://www.levels.fyi/companies/revolut/salaries/software-engineer/locations/united-kingdom)
- [levels.fyi: Revolut SWE (all)](https://www.levels.fyi/companies/revolut/salaries/software-engineer)
- [Revolut careers](https://www.revolut.com/careers/)
- [Revolut careers: Engineering team](https://www.revolut.com/careers/team/engineering/)
- [Revolut posting: Software Engineer (Python)](https://www.revolut.com/careers/position/software-engineer-python-7d3a7425-fe1a-456c-9dde-d19aba0cde88/)
- [Revolut posting: Software Engineer (Java)](https://www.revolut.com/careers/position/software-engineer-java-530d3bfd-bdca-4390-8f8a-bc88ddc1eb51/)
- [Revolut posting: Compute Engineer](https://www.revolut.com/careers/position/compute-engineer-dee80f98-c583-4a32-952e-1690cf9ea6be/)
- [LinkedIn: AI Platform Engineer (Serverless Training and Inference), Berlin](https://de.linkedin.com/jobs/view/ai-platform-engineer-serverless-training-and-inference-at-revolut-4487603165)
- [LinkedIn: Applied AI Engineer, Berlin](https://de.linkedin.com/jobs/view/applied-ai-engineer-at-revolut-4474604819)
- [Revolut posting: Software Engineer (DevOps) - Observability Platform](https://www.revolut.com/careers/position/software-engineer-devops-observability-platform-4eabb087-408d-4dc7-811d-141544ba4991/)
- [Computing: Revolut turns to self-hosted AI to cut coding costs](https://www.computing.co.uk/news/2026/ai/revolut-turns-to-self-hosted-ai-to-cut-coding-costs-tenfold-over-claude)
- [Revolut: launch of Revolut Research AI division](https://www.revolut.com/de-LU/news/revolut_announces_launch_of_dedicated_ai_research_division_revolut_research/)
- [Sifted: Revolut AI research unit](https://sifted.eu/articles/revolut-ai-research-unit/)
- [Air Street Press: How Revolut runs AI at scale](https://press.airstreet.com/p/nikolay-donets-revolut)
- [Crowdfund Insider: Revolut to base 40% of workforce in India](https://www.crowdfundinsider.com/2026/03/269395-digital-bank-revolut-set-to-base-40-of-its-workforce-in-india-by-2026/)
- [RTÉ: Revolut to base 40% of global workforce in India](https://www.rte.ie/news/business/2026/0326/1565268-revolut-to-base-40-of-global-workforce-in-india-by-2026)
- [UKTN: Underperformers get six weeks to improve or must go, says Storonsky](https://www.uktech.news/growth-strategy/underperformers-get-six-weeks-to-improve-or-must-go-revoluts-nik-storonsky-tells-startups-20240910)
- [Fintech Futures: Revolut accused of coercing 50 workers to quit](https://www.fintechfutures.com/job-cuts-new-hires/revolut-accused-of-coercing-50-workers-to-quit-their-jobs)
- [fintech.global: Revolut allegedly coerced staff into quitting](https://fintech.global/2020/06/05/revolut-allegedly-coerced-staff-into-quitting-or-being-fired/)
- [Irish Times: Revolut axes graduate jobs in cost-cutting review (2022)](https://www.irishtimes.com/business/2022/09/07/revolut-axes-graduate-jobs-as-it-conducts-sweeping-cost-review)
- [TrueUp: Revolut](https://www.trueup.io/co/revolut)
- [employeebenefits.co.uk: Revolut employee compliance tracking system](https://employeebenefits.co.uk/pay-strategy/revolut-hails-employee-compliance-tracking-system/280667.article)
- [The Block: Revolut growth shares for employees](https://www.theblock.co/post/94999/revolut-growth-shares-employees-plan-neobank)
- [Finance Magnates: Revolut offers ex-staff discounted exit](https://www.financemagnates.com/fintech/revolut-offers-ex-staff-30-discounted-exit-after-75-billion-valuation/amp)
- [LRT: Revolut Bank fined €3.5m for AML breaches](https://www.lrt.lt/en/news-in-english/19/2531818/revolut-bank-fined-eur3-5m-for-breaching-anti-money-laundering-rules)
- [tech.eu: Revolut fined €3.5M by Bank of Lithuania](https://tech.eu/2025/04/08/revolut-slapped-with-3-5m-fine-by-lithuania-s-central-bank-over-money-laundering-prevention-failings/)
