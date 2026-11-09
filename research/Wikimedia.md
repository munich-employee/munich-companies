# Wikimedia - Full Research Report

_Researched: 2026-11-09_

> **Scope note.** "Wikimedia" covers two separate employers that are relevant here:
> - **Wikimedia Foundation, Inc. (WMF)**: US 501(c)(3) nonprofit that runs Wikipedia's infrastructure and software, remote-first, ~685 staff. Hires in Germany only through a third-party **Employer of Record (EOR)**.
> - **Wikimedia Deutschland e.V. (WMDE)**: independent German chapter (registered association) in Berlin, ~190 staff, which develops **Wikidata and Wikibase**. Direct German employment, hybrid in Berlin.
>
> The report covers both. Where a section does not say which one, it refers to WMF.

> **Critical Disqualifiers**
> 1. **WMF: no direct German employment contract.** Every current posting states: "Our non-US employees are hired through a local third party Employer of Record (EOR)". The criteria require a direct contract.
> 2. **WMDE: Berlin office, hybrid.** Recent WMDE engineering postings are Berlin hybrid or on-site. There is no Munich office, and no fully remote-in-Germany model was found.
> 3. **The engineering is centred on PHP, not Python.** MediaWiki and Wikibase are PHP. Python is limited to the data, ML and research teams.
> 4. **WMF labour conflict in 2026.** The Foundation declined to voluntarily recognise the union and retained Littler Mendelson. In May 2026 it disbanded the Community Tech team, whose members were largely union organisers.

---

## 1. Company Fundamentals

### Wikimedia Foundation (WMF)

| Criterion | Status |
|---|---|
| Founded | 2003 (23 years) |
| Employees | 685 headcount at end of Dec 2025 (employees, EOR staff and fixed-term contractors of 6+ months), per the FY2026-27 Budget Overview. Postings say "staff members including contractors based in 40+ countries" |
| Revenue (FY2024-25, to 30 Jun 2025) | $208.6M audited (+13%), of which $189.5M donations; Wikimedia Enterprise $8.3M |
| Profitability | Expenses $190.9M, so a surplus of ~$17.7M. Net assets $296.6M (up from $271.6M). Reserves equal 17.1 months of operating expenses - **PASS** |
| Ownership | US 501(c)(3) nonprofit, donation-funded (average gift ~$15). A separate Wikimedia Endowment holds $169.4M |
| Software-centric | Runs and develops MediaWiki and Wikipedia's own bare-metal infrastructure. Per a volunteer Signpost guide, at least ~48% of the plan and budget is technical - **PASS** |

### Wikimedia Deutschland (WMDE)

| Criterion | Status |
|---|---|
| Founded | 2004 (22 years), Berlin |
| Employees | 190 paid staff, 110,000+ members (WMDE posting, Nov 2026) |
| Revenue (2025) | €26.6M (2024: €24.6M) |
| Profitability | Expenses €26.6M (2024: €22.8M), so break-even. A nonprofit, funded by donations and membership fees - **PASS (non-profit, balanced)** |
| Ownership | Registered nonprofit association (e.V.), independent of WMF |
| Software-centric | Mixed. Its Software Development department builds Wikidata and Wikibase, but the organisation also covers politics, education, fundraising and volunteer support - **BORDERLINE** |

**Key People**
- WMF: Maryana Iskander, CEO since 2022 (83% Glassdoor approval). Chris Albon, Director of Machine Learning. Leila Zia, Head of Research.
- WMDE: elected volunteer Präsidium plus an executive board (Vorstand). Name not retrieved.

**Business Model.** Both are donation-funded nonprofits. The only commercial line is Wikimedia Enterprise (paid API access for large reusers such as AI and search companies): $8.3M revenue in FY24-25, up 148%. Neither has equity, investors or a funding history.

**Software-Centric Assessment (WMDE).** About a third of WMDE's activity is software (Wikidata, Wikibase Suite, Wikibase Cloud, Wikidata for Wikimedia Projects, Technical Wishes). The rest is policy, education, GLAM and fundraising. Engineering is a real product function, not an internal IT function, but it does not dominate the organisation.

---

## 2. Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **Wikimedia Deutschland - Gesellschaft zur Förderung Freien Wissens e. V.** | VR 23855 B, Amtsgericht Charlottenburg; USt-ID DE263757776 | Tempelhofer Ufer 23/24, 10963 Berlin | Nonprofit association promoting free knowledge. Develops free software (Wikidata, Wikibase) and supports Wikipedia volunteers |
| **Gemeinnützige Wikimedia Fördergesellschaft mbH** | (registration no. not retrieved) | Berlin | WMDE's nonprofit subsidiary. It shares fundraising and admin costs with WMDE (WMDE 2025 annual report) |
| **Wikimedia Foundation, Inc.** | No German entity found | San Francisco, USA | Hires German residents through a third-party EOR |

**Verification.** The WMDE Impressum gives the Vereinsregister number (retrieved with curl). WMDE employs engineers directly: its postings on its own Softgarden portal are permanent ("unbefristet") Berlin contracts. WMF, in contrast, states on every current Greenhouse posting: "Countries: ... Germany ... Our non-US employees are hired through a local third party Employer of Record (EOR)". A WMF engineer in Germany would be employed by the EOR, not by WMF. Also, two of the three current WMF senior engineering postings (Android, iOS) are **contract** roles paid hourly.

**Verdict:** WMDE **PASS** (direct contracts, but in Berlin). WMF **FAIL** (EOR only, no German entity).

---

## 3. Office Location

- **Office address:**
  - WMF: no office in Germany. The organisation is remote-first, and its legal office is in San Francisco.
  - WMDE: Tempelhofer Ufer 23-24, 10963 Berlin (Kreuzberg, Tempelhofer Vorstadt / Möckernkiez). Confirmed by the Impressum, the job postings ("Tempelhofer Ufer, Berlin") and Nominatim (52.4983, 13.3811). No Munich location.
- **Nearest public transport:** **U Möckernbrücke** (U1, U3, U7), about 140 m away (geocoded with Nominatim). The Overpass API returned "at capacity" errors on three attempts, so bus stops were not listed.
- **Work model:**
  - **WMF:** fully remote. Postings require overlap with UTC, for example "at least four hours of your workday ... between 15:00 UTC and 21:00 UTC" (Android role) or "15:00-18:00 UTC" (Data Platforms GPM). That means working until 17:00-23:00 Munich time on some days. Some roles need up to 4 international trips a year. Germany is on the list of hiring countries, but only through an EOR. A 2025 Glassdoor reviewer (Senior Product Manager) was based in Munich, so WMF has employed people remotely from Munich before.
  - **WMDE:** hybrid with presence in Berlin. The current posting requires "wöchentliche[r] Präsenz (mind. 2x Woche)". Recent engineering-manager postings (2026) were listed as on-site, and earlier SWE postings as hybrid. A 2025 Kununu reviewer (former employee, IT) wrote: "Es besteht der Wunsch dass Mitarbeiter ins Büro kommen". There is a "WorkingAbroad@WMDE" benefit of up to 4 weeks a year. Not compatible with Munich.

---

## 4. Reviews

**GPTW:** No Great Place to Work certification found for WMF or WMDE (Germany or US).

#### Glassdoor (Wikimedia Foundation, E38331)

Retrieved through Chromium over CDP (glassdoor.de, logged in). Glassdoor has one employer page for both WMF and WMDE: the German and Berlin reviews on it are WMDE staff.

| Metric | Global (EN, 179 reviews) | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | 3.7 | 4 reviews (scores not separated) | 1 review (4.0) | 3.6 (17 reviews) |
| **WLB** | 4.2 | - | - | 4.5 |
| **Culture & Values** | 3.7 | - | - | 4.1 |
| **Comp & Benefits** | 3.7 | - | - | 3.2 |
| **Career Opportunities** | 3.5 | - | - | 3.8 |
| **Diversity & Inclusion** | 3.8 | - | - | 3.6 |
| **Senior Management** | 3.2 | - | - | 3.0 |
| **% Recommend** | 60% | - | - | 83% |
| **CEO Approval** | 83% | - | - | 92% |
| **Business Outlook** | 47% positive | - | - | 61% positive |

- 260 reviews in all languages. Glassdoor notes the Comp & Benefits score has fallen 2% over the last 12 months.
- The Germany and Munich filters return 4 and 1 reviews, which is too few to read. Glassdoor lists Berlin (6), Leipzig (1) and München (1) as German locations.
- The SWE sample (17) is directional only.

#### Kununu

Retrieved through Chromium over CDP. The kununu.com curl request returned 405.

**Wikimedia Deutschland - Gesellschaft zur Förderung Freien Wissens e.V.** (`/de/wikimedia-deutschland-gesellschaft-zur-foerderung-freien-wissens-e-v`):
- **Overall score:** 4.2 / 5.0 (industry average for associations: 3.7)
- **Recommendation rate (Weiterempfehlung):** 83% over the last 2 years (78% shown in the review list)
- **Total reviews:** 367 (employee reviews: 96, since 2015)
- **Sub-scores:** Karriere & Gehalt 3.8, Unternehmenskultur 4.3, Arbeitsumgebung 4.2, Vielfalt 4.6
- **Benefits confirmed:** Homeoffice 93%, flexible hours 84%, company pension 71%
- **Kununu Top Company:** NO / UNKNOWN (no badge shown)
- WMDE's Softgarden page shows 4.65/5 from 425 candidate ratings.

WMF has no Kununu profile. The subsidiary "Gemeinnützige Wikimedia Fördergesellschaft mbH" has a separate profile, not reviewed.

#### Blind / Teamblind

Retrieved through Chromium over CDP. **Wikimedia Foundation: 3.9 / 5 (18 reviews).**

| Sub-score | Value |
|---|---|
| Work Life Balance | 4.3 |
| Company Culture | 3.7 |
| Career Growth | 2.9 |
| Compensation / Benefits | 2.9 |
| Management | 2.8 |

The sample is small. Management is the lowest score, which matches Glassdoor (Senior Management 3.2).

#### Review Themes (2022-2026)

**Positives:**
- **Work-life balance is the strongest and most consistent theme** (Glassdoor 4.2 globally and 4.5 for SWE, Blind 4.3). "Veteran software engineer, and this is my favourite job I've had ... I am free to choose the work/life balance that I want" (Glassdoor, Dec 2024, current Software Engineer, Dublin, 5+ years). "Extremely good work life balance and mission driven company, nice people" (Blind, 2025-26, WMF employee).
- **Mission and colleagues.** "Great people working on important issues", "Amazing colleagues, mission driven, global company, truly cares" (Glassdoor summary highlights). "Love the place overall, great colleagues, respectful environment and some complex stuff to work on. WLB is great. Great onboarding." (Kununu, Jun 2026, WMDE, Bereich IT, Berlin).
- **WMDE working-time rules.** "Flex-Time, 1:1 Überstunden-Ausgleich, Wochenstunden-Änderungen jederzeit möglich ... 30 Tage Urlaub + 24.12. + 31.12." (Kununu, Apr 2024, Angestellte/r oder Arbeiter/in, WMDE Berlin). Postings confirm "Alle Überstunden werden erfasst und in Freizeitausgleich umgewandelt".
- **Transparent pay structure at WMF.** "The pay range for each role and level within that role is set at -/+20% around the median for that role/level within an individual country/region" (Glassdoor, Dec 2024, current Software Engineer, Dublin, 5+ years).

**Negatives:**
- **Pay below market, especially outside the US.** "Very low pay compared to industry rates, and even worse is the location-based pay scheme that ensures non-US employees are second class" (Glassdoor, Dec 2022, former Software Engineer, San Francisco, 3+ years). "Salary not competitive as other companies in their league" (Glassdoor, Mar 2025, former Senior Product Manager, Munich). "Salary pay-bands are not very competitive compared to the rest of the market" (Kununu, Jun 2026, WMDE, Bereich IT, Berlin).
- **Management quality and harassment complaints (recent).** "Toxic environment where harrasment is allowed" (Glassdoor, Aug 2026, current Senior Site Reliability Engineer, Madrid, 10+ years). "Very difficult management to work with" (Glassdoor, Aug 2026, current Software Engineer, Lagos). "This is the worst management experience I've had in my career. The VP of SRE consistently leaves even the most talented people feeling frustrated and close to rage quitting" (Blind, Nov 2025, former Site Reliability Engineer).
- **Slow, consensus-driven decisions, too many meetings.** "It can be chaotic. Decision-making is often consensus-driven, with lots of involvement from the volunteer community ... it can be v difficult to decide on priorities" (Glassdoor, Dec 2024, current Software Engineer, Dublin). "Too much meetings, not enough doing" (Glassdoor, Sep 2026, former Anonymous Employee). WMDE: "Alles muss im Minutentakt abgestimmt werden" and "Zumindest in der IT ist relativ schnell Schluss wenn man nicht ins Management wechseln möchte" (Kununu, Feb 2025, Ex-Angestellte/r, Bereich IT, WMDE Berlin, until 2024).
- **Bureaucracy and unclear hierarchy at WMDE.** "Lots of redundancy and unnecessary bureaucracy. Some rules and policies are established and communicated, but are not being followed" (Kununu, Jun 2024, WMDE, Bereich IT, Berlin). "Micro-Management und nicht nachvollziehbare Hierarchien" (Kununu, Nov 2024, Ex-Angestellte/r, PR / Kommunikation, WMDE Berlin).
- **Culture conflict and hostility (older, engineering).** "Meetings can get very tense due to hostile behavior, some technical teams have a long & well-documented history of bullying too" (Glassdoor, Dec 2022, former Software Engineer, San Francisco, 3+ years; 45 "helpful" votes).
- **The work may not transfer well, and AI is viewed sceptically.** "AI as a trend is not very much endorsed and its maybe because the community doesn't welcome it with open hands either" (Kununu, Jun 2026, WMDE, Bereich IT, Berlin).
- **Overlap with hard red flags:** layoffs (May 2026 Community Tech disbanding, see Section 8), communication breakdown (management scores 2.8-3.2), and contested union relations. Work-life balance itself is **not** a red flag.

#### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | **Localized.** Repeated complaints about SRE leadership: Blind, Nov 2025, former SRE ("VP of SRE ... very limited emotional intelligence"); Glassdoor, Aug 2026, current Senior SRE, Madrid ("Toxic environment where harrasment is allowed"). Leadership scores are low (Glassdoor 3.2, Blind 2.8), but CEO approval is 83%. |
| 24/7 Work Expectation | Not reported for product engineering. SRE roles state "24/7 incident response and be on-call rotation". |
| Internal Surveillance | No reports found. |
| Fear-driven Management | Indirect. The 2026 dismissal of union organisers (Community Tech, and a long-time MediaWiki developer about a week earlier) was described by critics as anti-union. WMF denies any link. |
| Communication Breakdown | Moderate. "Senior leadership is extremely siloed", "Change can be very slow" (Glassdoor highlights). WMDE: "keinen echten Plan, wer letztendlich was zu sagen hat" (Kununu, Nov 2024, ex-PR). |
| Unpaid Overtime | No. WMDE logs all overtime and converts it to time off 1:1. WMF reviews describe a manageable workload. |
| Silent Firings | No pattern of quiet push-outs found. The 2026 cuts were announced, with severance and a chance to apply for internal roles. |
| Work-Life Balance issues | No. WLB is the highest-rated category on every platform. |

**Risk level: MODERATE.** This is mostly **(c) localized dysfunction** (SRE leadership, some engineering teams) and **(b) slow, consensus-driven nonprofit bureaucracy**. On top of that comes an **organisation-level labour conflict in 2026** (union recognition refused, organisers' team disbanded). It is not systemic toxicity, but leadership-staff relations at WMF are strained right now. WMDE looks lower-risk (Kununu 4.2, Betriebsrat), with bureaucracy as its main complaint.

---

## 5. Compensation

#### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| levels.fyi (via Chromium) | WMF Software Engineer, Italy (L6, page default location) | ~€95K | €0 | €0 | median €95.5K, max €101K | 22 SWE submissions in total, all countries |
| levels.fyi | WMF Software Engineer, Germany | - | - | - | **locked: "4 more submissions" needed** | <4 |
| levels.fyi (search snippet) | WMF Software Engineering Manager, Germany | - | €0 | €0 | median ~€113K, max ~€161K | few |
| levels.fyi (search snippet) | WMF Product Designer, Germany | - | €0 | €0 | median ~€69K | few |
| Glassdoor (US data) | WMF Senior Software Engineer | ~$210K-289K (US) | 0 | - | US only | 15 |
| Glassdoor (US data) | WMF Software Engineer | ~$150K-213K (US) | 0 | - | US only | 27 |
| WMF Greenhouse posting | Group Product Manager, Data Platforms (US range) | $132K-206K | 0 | 0 | adjusted "to the country of hire" outside the US | posting |
| WMF Greenhouse posting | Senior SWE Android (Contract), US | $56-87/hour | 0 | 0 | contract | posting |
| WMDE posting (2026) | Interim Engineering Manager, Wikibase Cloud (12-month contract) | **€60K-80K** | 0 | 0 | €60K-80K | posting |
| Kununu | WMDE, all roles | 8 salary entries; "Karriere & Gehalt" 3.8 | - | - | - | 8 |

**Market reference (levels.fyi):** median Senior SWE total comp is ~€92K in Berlin and ~€83K for all SWE in Germany. Munich medians run slightly above Berlin. Percentile figures for Munich were not retrieved for this report.

**Estimate.** WMF pay for a Senior SWE in Germany is likely around **€85K-105K base, no equity, no bonus**. This is extrapolated from Italy SWE (€95K), German EM (€113K) and the ±20% band rule. WMDE senior engineers are likely **€60K-75K**, since its engineering-manager band tops out at €80K.

#### Equity / Stock

**None.** Both are nonprofits: no RSUs, options or bonus. WMF benefits outside the US depend on the EOR's local package. A reviewer noted "Good benefits if you are located in the U.S." WMDE offers a company pension subsidy, a public-transport ticket, 30 days' leave plus 24/31 Dec, and home-office allowances.

#### Verdict

- **WMF: BELOW to COMPARABLE.** Base may match the median of large Munich corporations at the senior level, but there is no bonus, equity or 13th salary. Several reviews say pay is below market and that non-US staff get location-discounted pay.
- **WMDE: BELOW.** About €60-80K even at management level.

---

## 6. AI/ML & Tech Stack

#### AI Strategy

- **WMF "humans first" AI strategy (30 Apr 2025)**, a three-year plan by Chris Albon (Director of ML) and Leila Zia (Head of Research). AI is used to support editors rather than generate content: moderation and anti-vandalism, translation, onboarding, and discovery.
- **Production ML:** **Lift Wing**, WMF's KServe/Kubernetes model-serving platform, which replaced ORES around 2023. It serves revert-risk, article-quality and similar models.
- **Current AI hiring signals:** the Senior Data Scientist, Safety & Security posting refers to a Product Safety & Integrity team "built around bringing cutting-edge AI and machine learning techniques" to bot and sockpuppet detection, plus "AI models to find malicious user-authored code". Mobile postings list "agentic coding to scale the work of small engineering teams" as a plus.
- **Wikimedia Enterprise** sells structured Wikipedia data to AI and search companies.
- **WMDE: Wikidata Embedding Project (Oct 2025)**, a vector-search layer over Wikidata for LLM and RAG use, built with Jina AI and DataStax (TechCrunch).
- **Assessment:** this is genuine applied ML (moderation models, embeddings, a serving platform). It is a small part of total engineering, and the community is sceptical of generative AI ("AI as a trend is not very much endorsed", Kununu, Jun 2026, WMDE IT).

#### Tech Stack

Sources: the current WMF Greenhouse postings (Data Platforms GPM, Senior Data Scientist, Android, iOS, Software Quality Manager, 2027 internship), past WMF postings for SRE and MediaWiki engineers, conference talks (FOSDEM 2026 "Running Wikipedia on Bare Metal", SREcon19, the Kubernetes-on-bare-metal deck), mediawiki.org and Wikitech, and the WMDE GitHub (wmde, wbaas-deploy).

| Category | Technologies |
|---|---|
| **Primary language(s)** | **PHP** (MediaWiki core, extensions, Wikibase), JavaScript/**Vue.js** and TypeScript (front end, Codex design system, Wikibase design system), Python (data, ML, tooling), Go (named in the QA manager posting), Kotlin and Jetpack Compose (Android), Swift/SwiftUI (iOS), Java (Search and Query Service) |
| **AI/ML** | Lift Wing (KServe on Kubernetes), revert-risk and quality models, ML anti-abuse, Wikidata vector embeddings (Jina AI, DataStax, WMDE) |
| **Cloud** | **Own bare-metal data centres** (Ashburn, Carrollton, plus caching sites in Amsterdam, Marseille, San Francisco, Singapore, São Paulo). No public cloud for core services. WMDE's Wikibase Cloud runs on **Google Kubernetes Engine** with Terraform and Helm |
| **Infrastructure** | Kubernetes (bare metal, Calico, Helm), Puppet, Varnish/ATS CDN, MariaDB/MySQL, Memcached, Envoy |
| **Data** | Kafka, Flink, Hadoop, Spark, Airflow, Iceberg, Hive, Presto, Druid, Superset, dbt, OpenSearch/Elasticsearch, GrowthBook |
| **Other** | Phabricator, Gerrit/GitLab, Codex (Vue), Wikibase Suite (Docker), wikibase.cloud |

**Summary:** PHP-centric web platform engineering (MediaWiki and Wikibase) with a Vue/TypeScript front end, a Python data, ML and research layer (Spark, Airflow, Iceberg, Lift Wing/KServe), and native Kotlin/Swift mobile apps. It runs on self-operated bare-metal Kubernetes, while WMDE runs Wikibase Cloud on GKE. This is open-source production engineering at very large scale, with applied (not research-first) ML.

---

## 7. Language

- **WMF:** English is the only working language. All postings are in English, and the organisation is globally distributed across 40+ countries.
- **WMDE:** officially bilingual: "unsere Unternehmenssprachen [sind] Deutsch und Englisch". Engineering postings (Senior SWE Wikibase Suite, SWE Wikidata, Director of Engineering) are written in English, and engineering reviews on Kununu are in English. The non-engineering posting requires "verbindlich und sicher auf Deutsch und Englisch". Internal all-hands and organisation communication is partly German.

**Verdict:** WMF **PASS**. WMDE **CONDITIONAL** (the engineering team works in English, the wider organisation is bilingual).

---

## 8. Stability

#### Financial Position

- **WMF:** FY2024-25 revenue $208.6M (+13%), expenses $190.9M (+7%), surplus ~$17.7M. Net assets $296.6M, of which $292.7M is unrestricted. Reserves of 17.1 months of operating expenses. A separate Endowment holds $169.4M. Twentieth consecutive clean KPMG audit. Revenue depends on small donations; Wikimedia Enterprise is growing (+148%). A longer-term risk is that AI answer engines reduce Wikipedia page views and therefore fundraising-banner reach.
- **WMDE:** 2025 revenue €26.6M, expenses €26.6M (break-even after a €1.8M surplus in 2024). The 2026 Wirtschaftsplan grows by 7.9%. WMDE is mostly self-funded through German donation campaigns and membership fees.
- Both are very stable financially for nonprofits. The runway model is not applicable (not VC-backed, not loss-making).

#### Financial Runway

Not applicable. Both organisations are donation-funded and run surpluses or break even. WMF holds about 17 months of operating reserves plus a separate $169M endowment.

#### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| Mid-May 2026 | WMF dismisses a long-time MediaWiki developer and union organiser | 1 | Reported by Gigazine, based on an essay by former staffer Jake Orlowitz |
| 20 May 2026 | WMF disbands the **Community Tech** team (Community Wishlist, moderation tools) | 6 (5 engineers + 1 manager) | WMF says the plan dated from Sep 2025, staff could apply internally, and those not placed received severance. Several were Wiki Workers United organisers. 700+ volunteers signed a solidarity statement and an editor strike was threatened |
| 2023-2025 | No WMF-wide layoffs found | - | Headcount stable at around 650-700 |
| WMDE | No layoffs found | - | Headcount grew to 190 |

#### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) at WMDE | **YES (likely)** | "aktiver Betriebsrat" (Glassdoor, Jan 2018, current Referent, WMDE Berlin, 3+ years). No more recent confirmation found |
| Collective agreement at WMDE | **NONE found / UNKNOWN** | No "Tarif" or "TVöD" mention in postings or reviews. WMDE uses its own pay bands. A reviewer asks for "ein transparentes Gehaltssystem" (Kununu, Nov 2024, ex-PR) |
| WMF in Germany | **N/A**: staff are employed by an EOR, so any works council would be the EOR's, not WMF's | Greenhouse postings |
| WMF union (US) | **YES (2026)**: US staff voted to join CWA Local 9415 (reported 158-14, ballots counted 3 Sep 2026). Wiki Workers United went public in Feb 2026. UK staff are seeking recognition through the CWU | CWA press releases, KQED, Novara Media, Signpost |
| Conflict signals | **YES**: WMF declined voluntary recognition, retained Littler Mendelson (a well-known management-side labour firm) and disbanded a team of organisers. Critics, including a former staffer, describe this as union-busting; WMF denies it | CWA, Der Standard, Signpost (Jun 2026 opinion), The Register |

**Verdict: CAUTION.** The money is solid. WMF's labour relations are in active conflict, and a German WMF employee would sit outside both the US bargaining unit and German co-determination (because of the EOR). WMDE individually would rate PASS (works council likely, no layoffs).

---

## 9. Regulated Industry

Not a regulated industry in the BaFin, medical, automotive or defence sense. The relevant regimes are the **EU Digital Services Act** (Wikipedia is a designated Very Large Online Platform), GDPR and privacy (WMF stores no IP-linked reader data and runs no ad tracking), and US Section 230 and content litigation. The effect on engineers is privacy reviews and occasional legal or compliance work. There are no formal safety cases or certification gates.

**Verdict:** PASS.

---

## 10. On-Call

- **WMF SRE roles:** explicitly on-call: "participate in 24/7 incident response and be on-call rotation" (Senior SRE, Service Operations). Infrastructure Foundations and Cloud Services SRE postings say the same.
- **WMF product and platform SWE roles** (MediaWiki, mobile, data): no on-call clause in the current postings (Android, iOS, Data Platforms, Data Scientist). Production deploys run through a "train" and backport windows, so a backend platform team may still have rota-based incident duties.
- **WMDE:** no on-call mentioned. Wikidata production runs on WMF infrastructure, and WMF SRE handles incidents. Wikibase Cloud (GKE) is run by the WMDE team, so occasional duty there is possible.

**Verdict:** **CAUTION (team-dependent)**. On-call is mandatory for SRE and infrastructure roles, and absent from the current product and data SWE postings.

---

## 11. Interview Process

Glassdoor, WMF, 192 English-language interview reports (retrieved through Chromium over CDP):

| Metric | Value |
|---|---|
| Difficulty | 2.91 / 5 |
| Positive experience | 61.3% (26% negative) |
| Average duration | ~42 days |
| Rounds | 4-5 typical |

**Typical process (SWE):**
1. Recruiter screen
2. Interview with two engineers or the hiring manager
3. A technical challenge or take-home, followed by a technical interview. Several reports describe **pair-programming and refactoring of existing code**; one Senior SWE report mentions working through TODOs in an `api.php` file
4. Final values and team interview with two staff members

How applicants reach interviews: 82% online application, 9% referral.

It is **experience- and practical-code-focused, not LeetCode-heavy**. The common complaints are length (one 2021 report: 3 months) and ghosting after the final round. SRE interviews are rated the hardest.

WMDE: no Glassdoor interview data split out. Its Softgarden page shows 4.65/5 from candidate ratings. WMDE asks for a motivation letter ("ja, wir lesen Motivationsschreiben").

---

## 12. Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | WMF: yes (runs Wikipedia's stack). WMDE: borderline (one department of many) |
| Not consulting | PASS: builds its own products |
| Profitable | Nonprofit with surplus. WMF reserves of 17 months, net assets $297M |
| Employee count | WMF ~685 globally. WMDE ~190 in Berlin |
| English-speaking | WMF PASS. WMDE conditional (bilingual, engineering in English) |
| Local entity + engineering contracts | WMF **FAIL** (EOR only, senior mobile roles are contract). WMDE PASS (direct, permanent) |
| Location / work model | WMF fully remote but needs late UTC overlap (to 21:00 UTC = 22:00-23:00 Munich). WMDE **FAIL** (Berlin hybrid, 2+ days a week on site) |
| Glassdoor | 3.7 global (179), 3.6 SWE (17), 60% recommend, WLB 4.2, Senior Management 3.2 |
| Kununu | WMDE 4.2, 83% recommend, 96 employee reviews |
| Salary | WMF below to comparable (est. €85-105K, no equity or bonus). WMDE below (est. €60-75K) |
| AI/ML content | Applied ML for moderation and anti-abuse (Lift Wing), Wikidata embeddings. A minority of the work, and the community is sceptical of AI |
| Computer-language/Tech-stack | **PHP-centric** (MediaWiki/Wikibase) with Vue/TS. Python only in data, ML and research teams |
| No on-call | Team-dependent: SRE always, product and data SWE not stated |
| WLB / Stability | WLB excellent (4.2-4.5). Financially very stable. 2026 labour conflict and organisers' team disbanded |
| Works council / collective agreement | WMDE: works council likely, no tariff found. WMF Germany: EOR, no co-determination. WMF US: new CWA union in conflict with management |
| Regulated industry | PASS (DSA/GDPR only) |
| Review themes | + WLB, mission, colleagues. − Below-market pay (non-US especially), weak senior and SRE leadership, slow consensus, bureaucracy |
| Employment form | WMF: EOR and contract roles are common in current postings |

---

## 13. Verdict

**Overall recommendation: Exclude for now, and monitor WMF for a permanent Python-centred data or ML role.**

**Strengths.** WMF is one of the most financially secure nonprofits in tech: 17 months of reserves, a $169M endowment, steady donation growth, and no investor pressure. Work-life balance is the best-rated category on every platform (Glassdoor 4.2, SWE 4.5, Blind 4.3). The mission is unusual, and the engineering problems are real: one of the world's top-10 websites on self-run bare metal, large data platforms (Kafka, Flink, Spark, Iceberg), and applied anti-abuse ML. Interviews focus on practical work rather than LeetCode. WMDE adds a well-rated (Kununu 4.2) German employer with a works council and strict overtime compensation.

**Hard blockers:**
1. **No direct employment contract with WMF in Germany.** Every posting routes non-US hires through a third-party EOR, and the current senior engineering openings (Android, iOS) are hourly contracts. The criteria require a full-time, permanent, direct contract.
2. **WMDE is Berlin-based and hybrid.** The current posting requires at least 2 office days a week in Kreuzberg, and recent engineering-manager roles were on-site. That is incompatible with Munich or fully remote work in Germany.
3. **Python is not the main language.** The core product engineering (MediaWiki, Wikibase) is PHP with Vue/TypeScript. Python is the main language only in the Data Platform, Product Analytics, Research and ML (Lift Wing) teams, which hire senior engineers rarely. None is open as of 9 Nov 2026.
4. **Glassdoor is below a "strong" threshold.** Overall 3.7 and SWE 3.6 (17 reviews), 60% recommend, Senior Management 3.2, and only 47% positive business outlook.

**Secondary concerns:**
- **2026 labour conflict at WMF:** voluntary union recognition refused, Littler Mendelson retained, the Community Tech team of organisers disbanded, and recent reviews alleging harassment and poor SRE leadership. Leadership-staff trust is low right now.
- **Location-adjusted pay with no equity or bonus.** Reviewers call non-US pay "second class", and WMDE pay tops out around €80K even for engineering managers.
- **Timezone:** required overlap until 18:00-21:00 UTC means some working evenings (up to 23:00 Munich time in winter).
- **On-call** is mandatory for SRE and infrastructure roles.
- **Organisational pace:** consensus-driven, volunteer-community veto, "too many meetings".

**What would need to change for a positive recommendation:** a WMF posting that (a) is permanent full-time, not a contract, (b) sits in a Python-centred team (Data Platform Engineering, ML/Lift Wing, Research, Product Safety & Integrity), and (c) comes with confirmation that the German EOR contract is permanent with standard German protections. A visible settlement of the union dispute (a first contract with CWA, no further cuts of organisers) would reduce the leadership risk. For WMDE, only a fully remote-in-Germany Wikidata or AI-embedding role with an English-first team would make it viable, though salary would remain below market.

**If a matching WMF role appears, verify in interviews:** the EOR provider and contract terms (permanence, notice periods, pension, sick pay, whether the role is "contract" or "employee"); the German pay band (median ±20%); the exact UTC overlap window; whether the team has an on-call or incident rota; and the manager's view of the 2026 restructuring.

---

## 14. Sources

- [WMF Greenhouse job board API (15 open postings, 9 Nov 2026)](https://boards-api.greenhouse.io/v1/boards/wikimedia/jobs?content=true) - retrieved with curl
- [WMF: Group Product Manager, Data Platforms](https://job-boards.greenhouse.io/wikimedia/jobs/8346045)
- [WMF: Senior Software Engineer, Android (Contract)](https://job-boards.greenhouse.io/wikimedia/jobs/8268142)
- [WMF: Senior Software Engineer, iOS (Contract)](https://job-boards.greenhouse.io/wikimedia/jobs/8223856)
- [WMF: Senior Data Scientist, Safety & Security](https://job-boards.greenhouse.io/wikimedia/jobs/8210560)
- [WMF: Software Quality Manager](https://job-boards.greenhouse.io/wikimedia/jobs/8137733)
- [WMF: Software Engineering Internship Program (2027)](https://job-boards.greenhouse.io/wikimedia/jobs/8268853)
- [WMF: Senior Site Reliability Engineer (on-call)](https://job-boards.greenhouse.io/wikimedia/jobs/6964680)
- [WMF FY24-25 Audit Report (KPMG)](https://upload.wikimedia.org/wikipedia/foundation/3/3f/Wikimedia_Foundation_FY_24-25_Audit_Report.pdf)
- [WMF 2024-2025 audit FAQ](https://meta.wikimedia.org/wiki/Wikimedia_Foundation_reports/Financial/Audits/2024-2025_-_frequently_asked_questions)
- [WMF 2024 Form 990 FAQ](https://meta.wikimedia.org/wiki/IRS_tax_related_information/2024_Wikimedia_Foundation_Form_990_Frequently_Asked_Questions)
- [Wikimedia Endowment 2024-2025 audit FAQ](https://meta.wikimedia.org/wiki/Wikimedia_Endowment_reports/Financial/Audits/2024-2025_-_frequently_asked_questions)
- [WMF Annual Plan 2026-2027: Budget Overview (headcount 685)](https://meta.wikimedia.org/wiki/Wikimedia_Foundation_Annual_Plan/2026-2027/Budget_Overview)
- [WMF Annual Plan 2025-2026](https://meta.wikimedia.org/wiki/Wikimedia_Foundation_Annual_Plan/2025-2026)
- [Wikimedia Enterprise financial report FY2024-25](https://diff.wikimedia.org/wikimedia-enterprise-financial-report-fiscal-year-2024-2025/)
- [WMDE Impressum](https://www.wikimedia.de/impressum/) - retrieved with curl
- [WMDE careers (Softgarden)](https://wikimedia-deutschland.career.softgarden.de/) - retrieved through Chromium over CDP
- [WMDE: Leitung Kampagnen und Fundraising (current posting, hybrid, 190 staff)](https://wikimedia-deutschland.career.softgarden.de/jobs/67381160/Leitung-Kampagnen-und-Fundraising-all-genders-/)
- [WMDE: Senior Software Engineer, Wikibase Suite (deactivated)](https://wikimedia-deutschland.career.softgarden.de/jobs/58843265/Senior-Software-Engineer-all-genders---Wikibase-Suite-)
- [WMDE: Software Engineer, Wikidata for Wikimedia Projects (deactivated)](https://wikimedia-deutschland.career.softgarden.de/jobs/60560805/Software-Engineer-Wikidata-for-Wikimedia-Projects-all-genders-)
- [WMDE: Director of Engineering](https://wikimedia-deutschland.career.softgarden.de/jobs/61646562/Director-of-Engineering-all-genders-)
- [WMDE: Interim Engineering Manager, Wikibase Cloud (€60-80K)](https://hw.glich.co/jobboard/jobs/interim-engineering-manager-all-genders-wikibase-cloud-12-month-contract-at-wikimedia-deutschland-e-v-abchjd)
- [WMDE Jahresbericht 2025](https://www.wikimedia.de/2025/wp-content/uploads/sites/43/2026/05/Jahresbericht-2025-Wikimedia-Deutschland.pdf)
- [WMDE Wirtschaftsplan 2026](https://meta.wikimedia.org/wiki/Wikimedia_Deutschland/Plan_2026/Wirtschaftsplan_2026)
- [WMDE Finanzbericht 2024](https://meta.wikimedia.org/wiki/Wikimedia_Deutschland/Plan_2024/Finanzbericht_2024)
- [Wikimedia Deutschland on Meta-Wiki](https://meta.wikimedia.org/wiki/Wikimedia_Deutschland)
- [Glassdoor: WMF reviews (global, EN)](https://www.glassdoor.de/Bewertungen/Wikimedia-Foundation-Bewertungen-E38331.htm?filter.iso3Language=eng&filter.countryId=0) - Chromium over CDP
- [Glassdoor: WMF reviews, Germany filter](https://www.glassdoor.de/Bewertungen/Wikimedia-Foundation-Bewertungen-E38331.htm?filter.countryId=96) - Chromium over CDP
- [Glassdoor: WMF reviews, Software Engineer filter](https://www.glassdoor.de/Bewertungen/Wikimedia-Foundation-Bewertungen-E38331.htm?filter.iso3Language=eng&filter.jobTitleFTS=Software%20Engineer&filter.countryId=0) - Chromium over CDP
- [Glassdoor: WMF reviews, newest first](https://www.glassdoor.de/Bewertungen/Wikimedia-Foundation-Bewertungen-E38331.htm?filter.iso3Language=eng&filter.countryId=0&sort.sortType=RD) - Chromium over CDP
- [Glassdoor: WMF salaries](https://www.glassdoor.com/Salary/Wikimedia-Foundation-Salaries-E38331.htm) - Chromium over CDP
- [Glassdoor: WMF interviews](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/Wikimedia-Foundation-Fragen-im-Vorstellungsgespr%C3%A4ch-E38331.htm?filter.iso3Language=eng) - Chromium over CDP
- [Glassdoor: WMF interview report, Apr 2026](https://www.glassdoor.com.au/Interview/Wikimedia-Foundation-Interview-E38331-RVW104963433.htm)
- [Kununu: Wikimedia Deutschland](https://www.kununu.com/de/wikimedia-deutschland-gesellschaft-zur-foerderung-freien-wissens-e-v) - Chromium over CDP (curl returned 405)
- [Kununu: Wikimedia Deutschland reviews](https://www.kununu.com/de/wikimedia-deutschland-gesellschaft-zur-foerderung-freien-wissens-e-v/kommentare) - Chromium over CDP
- [Blind: Wikimedia Foundation reviews](https://www.teamblind.com/company/Wikimedia-Foundation/reviews) - Chromium over CDP
- [levels.fyi: WMF Software Engineer](https://www.levels.fyi/companies/wikimedia-foundation/salaries/software-engineer) - Chromium over CDP
- [levels.fyi: WMF Software Engineer, Germany (locked)](https://www.levels.fyi/companies/wikimedia-foundation/salaries/software-engineer/locations/germany) - Chromium over CDP
- [levels.fyi: WMF Software Engineering Manager](https://www.levels.fyi/he-il/companies/wikimedia-foundation/salaries/software-engineering-manager)
- [levels.fyi: WMF Product Designer](https://www.levels.fyi/companies/wikimedia-foundation/salaries/product-designer)
- [levels.fyi: Senior SWE, Berlin](https://levels.fyi/t/software-engineer/levels/senior/locations/berlin-deu)
- [CWA: Wikimedia Foundation workers vote to form union](https://cwa-union.org/news/releases/wikimedia-foundation-workers-overwhelmingly-vote-form-union-cwa)
- [CWA: Wiki Workers United will file NLRB election after WMF declines](https://cwa-union.org/news/releases/wiki-workers-united-uscwa-will-file-nlrb-election-after-wikimedia-foundation-declines)
- [KQED: Wikipedia staff demand union recognition](https://www.kqed.org/news/12092335/staff-of-san-francisco-based-wikipedia-demand-union-recognition-raise-concerns-over-ai)
- [Der Standard: WMF will not voluntarily recognise union](https://www.derstandard.at/story/3000000333253/wikimedia-foundation-moechte-gewerkschaft-nicht-freiwillig-anerkennen)
- [The Register: Wikipedia editors plot strike after Wikimedia layoffs (30 May 2026)](https://www.theregister.com/software/2026/05/30/wikipedia-editors-plot-strike-and-banner-sabotage-after-wikimedia-layoffs/5248491)
- [heise: Unionization at Wikimedia, community protest after layoffs](https://heise.de/-11309504)
- [Gigazine: Wikipedia fired union organizers](https://gigazine.net/gsc_news/en/20260527-wikipedia-anti-labor-fired-union-organizers)
- [Novara Media: Wikipedia workers in the UK move to unionise](https://novaramedia.com/2026/06/25/wikipedia-workers-in-the-uk-move-to-unionise-amid-feud-over-sackings/)
- [Wikipedia: 2026 Wikipedia editorial strike threat](https://en.wikipedia.org/wiki/2026_Wikipedia_editorial_strike_threat)
- [Signpost: News and notes, 22 May 2026](https://signpost.news/2026-05-22/News_and_notes)
- [Signpost: Opinion, 21 Jun 2026](https://signpost.news/2026-06-21/Opinion)
- [Signpost: News and notes, 24 Aug 2026](https://signpost.news/2026-08-24/News_and_notes)
- [Meta-Wiki: Wiki Workers United](https://meta.wikimedia.org/wiki/WWU)
- [WMF AI strategy brief (Meta-Wiki)](https://meta.wikimedia.org/wiki/Strategy/multigenerational/artificial_intelligence_for_editors)
- [Meta-Wiki: Artificial intelligence (Lift Wing)](https://meta.wikimedia.org/wiki/Artificial_intelligence)
- [Neowin: Wikipedia announces new AI strategy](https://www.neowin.net/news/wikipedia-announces-new-ai-strategy-but-it-wont-sacrifice-human-editors/)
- [TechCrunch: New project makes Wikipedia data more accessible to AI](https://techcrunch.com/2025/10/01/new-project-makes-wikipedia-data-more-accessible-to-ai)
- [FOSDEM 2026: Running Wikipedia on bare metal](https://fosdem.org/2026/schedule/event/YDLGLN-running_wikipedia_on_bare_metal_open_source_and_a_healthy_dose_of_caching/)
- [Kubernetes at Wikipedia (bare metal, GRNOG)](https://grnog.gr/wp-content/uploads/2018/07/Kosiaris-Wikipedia-Kubernetes.pdf)
- [mediawiki.org: Wikimedia Site Reliability Engineering](https://www.mediawiki.org/wiki/Wikimedia_Site_Reliability_Engineering)
- [The New Stack: Wikipedia's infrastructure](https://thenewstack.io/what-wikipedias-infrastructure-is-like-behind-the-firewall/)
- [WMDE GitHub organisation](https://github.com/wmde/)
- [wmde/wbaas-deploy (Wikibase Cloud IaC)](https://github.com/wmde/wbaas-deploy)
- [Remote Work Europe: remote-first Wikimedia Foundation](https://remoteworkeurope.eu/insights/remote-first-wikimedia-foundation)
- [Nominatim: Tempelhofer Ufer 23, Berlin](https://nominatim.openstreetmap.org/search?q=Tempelhofer+Ufer+23,+10963+Berlin&format=json&addressdetails=1)
- [Nominatim: U Möckernbrücke](https://nominatim.openstreetmap.org/search?q=U-Bahnhof+Möckernbrücke+Berlin&format=json)
