# ecoplanet - Full Research Report

_Researched: 2026-10-13_

> **Critical Disqualifiers**
> 1. **Not a mature, profitable company.** EcoPlanet Green Operations GmbH was registered in July 2022 and has lost money in every filed year: -€0.19M (2022), -€0.94M (2023) and -€2.85M (2024). Cash was €2.0M at 31.12.2024. It is a Series A startup (€16M from EQT Ventures in January 2025) with an estimated 2 to 3 years of runway.
> 2. **No review base at all.** There is no Kununu profile. Glassdoor has one star rating (5.0) with no written review and no interview reports. Blind and levels.fyi have no entry, and there is no GPTW certification.
> 3. **On-call exists in engineering.** The September 2026 Head of Engineering JD lists "Operations. Reliability, **on-call**, incidents" among the role's responsibilities. The Platform Engineer JD asks "what you actually do at 3am when a consumer group is hours behind", and both IC JDs mention "the occasional early morning debugging a pipeline". The rotation is spread across only 11 to 12 engineers.
> 4. **Python is not the main language.** The platform is TypeScript on Kafka and GCP. Earlier postings listed Kotlin/Java/Spring with Vue/React. Python appears only in the Data Engineer role (data pipelines plus anomaly-detection data science).

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | Registered 27 July 2022, Amtsgericht München (**4 years**) |
| Employees | Inconsistent across sources. The company's own September 2026 JDs say "**around 40 people**", with 11 to 12 engineers in two squads. The careers page says "70+ Teammitglieder", Dealroom says 85, and Welcome to the Jungle says 101-200. LinkedIn shows 106 associated members, but 25 of them are in Colombia and belong to an unrelated "Ecoplanet SAS / LTDA", which leaves about 81, of whom 47 list Germany. Best estimate: **~45-75**, including working students and interns |
| Revenue (FY2024) | Not disclosed; small GmbHs file only a balance sheet. Munich Startup (2024) reports "seven-figure revenue in the first year after product launch". The company claims 150+ active customers, more than 2,000 sites and more than 5 TWh of energy under management |
| Profitability | Net losses (Jahresfehlbetrag, NorthData chart data): **-€194.7K (2022), -€938.9K (2023), -€2,851.3K (2024)**. Losses are widening as the company scales - **FAIL** |
| Ownership | **Private, VC-backed.** The founders' holding vehicles hold ~30.7% and ~20.3% (NorthData, 2024). HV Capital Fund IX is a registered shareholder (shareholder-list publications of 06.01.2025 and 02.12.2025), and EQT Ventures led the Series A |
| Software-centric | Mostly. The core product is the "ecoplanet Cockpit" SaaS: metering/IoT integration, consumption analytics, ISO 50001 workflows and procurement tooling. Revenue also depends on human energy-procurement and advisory services ("Kostenfreie Beratung", "Kompetent beraten werden"), so it is a "software-enabled service" hybrid - **BORDERLINE (leaning PASS)** |

### Key People

- **Maximilian Dekorsy**: co-founder and Co-CEO (Geschäftsführer). Ex-BCG; previously ran MXD Consulting GmbH, now in liquidation.
- **Dr. Henry Keppler**: co-founder and Co-CEO (Geschäftsführer). Ex-McKinsey Engagement Manager, previously an energy auditor for the German Energy Agency (dena).
- **No CTO.** The Head of Engineering JD (Personio, posted 2 September 2026) says: "This is the most senior engineering role in the company. There is no CTO above you." Engineering currently has two squad leads / engineering managers reporting into a vacant head role.
- Michaela Grädener (Head of R&D) and Jannis Zipp (Product Lead) appear on the careers page.

### Funding History

| Date | Round | Amount | Valuation | Investors |
|---|---|---|---|---|
| 2023 | Seed | €2.6M | n/a | HV Capital (lead); angels including Dr. Gerhard Cromme and founders of FlixBus and sennder |
| Apr 2024 | Seed extension / early VC | €3.5M (~$3.9M) | ~$15M (Dealroom) | HV Capital |
| Jan 2025 | Series A | €16M (~$18M) | ~$70M post-money (Dealroom) | EQT Ventures (lead), HV Capital |
| **Total** | | **~€22M** | | |

The capital increase to €59,193 nominal was registered on 17 December 2024. Some aggregators list a "$28M Series A" (Signalbase) or a "$38.5M" 2026 figure (Dealroom, without explanation); neither is backed by a press release. No round after January 2025 was found.

### Business Model

ecoplanet sells a subscription to its Cockpit platform. The platform connects meters and utility data feeds for real-time consumption transparency, uses an AI layer ("KI Ember") to flag savings, provides ISO 50001 / EnEfG compliance workflows, and runs structured electricity and gas procurement (tranche, spot or fixed contracts; PPAs). Procurement draws on bundled volume ("über 5 TWh verwaltetes Energievolumen verschaffen Verhandlungsstärke"). A newer channel is the "Preferred Partner Platform": energy consultancies license the Cockpit white-label "im Abo-Modell". The company also offers a free consumer-facing "EnergieGPT" assistant. Customers are German Mittelstand manufacturers, healthcare and real estate.

### Consulting-Adjacency Assessment

- **Self-identification:** "Die führende All-in-One Energie-Software ... Mit KI, Strategie und einem Partner an Ihrer Seite." It presents itself as software plus advisory, not as a consultancy.
- **Registered purpose** includes "Softwarelösungen, Unternehmensberatung, Energieberatung, Unterstützung bei der Beantragung von Fördermitteln ... Vermittlung von klimarelevanten Produkten".
- **Billing:** No evidence that anyone bills hours. Revenue comes from subscriptions and procurement services.
- **Career track:** Customer-facing roles are "Value Engineer", "Customer Success Manager" and "Solution Engineer". Engineering roles are product squads.
- **Engineers' output:** an internal product (Cockpit, the data platform, forecasting services), not client deliverables.

**Conclusion:** The company is not a consultancy for engineers. The advisory layer sits in the commercial teams.

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **EcoPlanet Green Operations GmbH** | HRB 277961, Amtsgericht München; LEI 39120087GRSFBFAG9X77; USt-ID DE354824020 | Marsstraße 46, 80335 München (Maxvorstadt / Marsfeld) | "Softwarelösungen, Unternehmensberatung, Energieberatung, Unterstützung bei der Beantragung von Fördermitteln, Marketingservices, Merchandise, Vermittlung von klimarelevanten Produkten & dazu gehörender Dienstleistungen und Unterstützung bei der kundenseitigen Kommunikation zum erfolgreichen Klimaschutz in Unternehmen ..." |

The company's Impressum names the same entity, address and register number, represented by both founders. The registered purpose puts "Softwarelösungen" first, and all job postings are issued by this GmbH through its own Personio portal (ecoplanet-green-operations-gmbh.jobs.personio.de) as "permanent" positions. This is the operating company with direct German employment, not a sales shell and not an EOR arrangement. The Berlin office has no separate registered entity.

**Verdict:** PASS

---

## Section 3: Office Location

- **Office address:** Marsstraße 46, 80335 München (Marsfeld, Maxvorstadt), north of the main-station tracks between Hauptbahnhof and Hackerbrücke. Nominatim places the building at 48.14502, 11.55425, shared with Public Value Technologies GmbH. There is also a Berlin office.
- **Nearest public transit (OSM Overpass, straight-line distance):** tram stop Hopfenstraße (~300 m; tram 17); bus stop Hauptbahnhof Nord (~305 m); **U-Bahn Stiglmaierplatz (U1/U7, ~380 m)**; München Hbf Starnberger Bahnhof / S-Bahn platforms (~400 m); Hackerbrücke S-Bahn trunk line (~545 m).
- **Work model:** Mixed signals. Both live LinkedIn engineering postings are tagged **On-site**. The careers page and Welcome to the Jungle say "Büros in München & Berlin – oder remote arbeiten". The JDs advertise "Central office, easy commute, free lunch every Tuesday and Thursday", which suggests at least two expected office days. Only the SDR role on Personio is listed as Remote. Treat the arrangement as office-centric hybrid until confirmed: **UNVERIFIED**.

---

## Section 4: Reviews

**GPTW:** No Great Place to Work certification or list appearance found for ecoplanet in Germany.

#### Glassdoor

Retrieved via Chromium over CDP. The relevant profile is "EcoPlanet Green Operations GmbH" (E10903041; 51-200 employees, HQ Munich). Two unrelated namesakes exist: "Ecoplanet" (E9464753, Florianópolis, Brazil) and "Ecoplanet Renewable Energy" (E7295384). The profile's job tab also shows misattributed vacancies (orthopaedic-technician jobs in Kiel).

| Metric | Global | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | 5.0 (1 rating, no written review) | same | same | no data |
| **WLB** | n/a | n/a | n/a | n/a |
| **Culture & Values** | n/a | n/a | n/a | n/a |
| **Comp & Benefits** | n/a | n/a | n/a | n/a |
| **Career Opportunities** | n/a | n/a | n/a | n/a |
| **Diversity & Inclusion** | n/a | n/a | n/a | n/a |
| **% Recommend** | 100% (1) | same | same | n/a |
| **CEO Approval** | n/a | n/a | n/a | n/a |
| **Business Outlook** | n/a | n/a | n/a | n/a |

Every category filter returns "Noch keine Bewertungen". A single rating has no statistical value.

#### Kununu

Direct slugs (`ecoplanet`, `ecoplanet1`, `ecoplanet-green-operations`, `ecoplanet-green-operations-gmbh`) all returned HTTP 405 via curl. A browser search on kununu.com for "ecoplanet" and "EcoPlanet Green Operations" (CDP) found only the unrelated ECOPLANT Services GmbH (Esslingen) and ECOPLANT Management GmbH (Waiblingen).

- **Overall score:** UNKNOWN (no profile)
- **Recommendation rate:** UNKNOWN
- **Total reviews:** 0
- **Kununu Top Company:** NO

#### Blind / Teamblind

No company page (`teamblind.com/company/ecoplanet` returns 404). No data.

#### Review Themes (2022-2026)

There are no independent employee reviews to draw themes from. The only available signals are company-authored or structural:

**Positives (company-stated or structural):**
- Small, senior-leaning engineering team with real ownership: "what you build reaches customers in weeks rather than quarters"; "Keep enough processes to be reliable and no more."
- Pragmatic engineering culture in the JDs: "prefer one cron job over a distributed system"; "A company our size cannot afford clever answers to problems that did not need solving."
- Tier-1 investors (EQT Ventures, HV Capital) and a real market need (energy costs, EnEfG / ISO 50001 compliance for the Mittelstand).
- Benefits: bonus and VSOP, JobRad, Wellpass, free lunch twice a week, quarterly on-sites and off-sites.

**Negatives / risk signals (structural, not from reviews):**
- **Leadership gap in engineering:** no CTO, and the Head of Engineering role is vacant (posted 2 September 2026). The JD asks for someone who has "managed people out when that was the right call".
- **Headcount messaging is inconsistent** (70+ on the careers page, "around 40" in current JDs). This could mean the careers page counts students and part-timers, or it could reflect shrinkage. **Unverified.**
- **Founder-led by two ex-strategy consultants** (BCG, McKinsey) with a strongly sales-driven GTM (HubSpot, Clay, n8n, SDR funnel). The commercial side dominates the LinkedIn function mix: business development, sales and operations outnumber engineering roughly 2:1 in Germany.
- **On-call and early-morning pipeline debugging** are named in the JDs (see Section 10).

#### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | No data: no reviews on any platform |
| 24/7 Work Expectation | Partial signal: "what you actually do at 3am when a consumer group is hours behind" (Platform Engineer JD) |
| Internal Surveillance | No data |
| Fear-driven Management | No data. "Regular 1:1s and retros focused on your growth" is advertised |
| Communication Breakdown | No data |
| Unpaid Overtime | No data. Startup norms and Series A growth pressure make it plausible, but nothing is evidenced |
| Silent Firings | No data. No works council exists to constrain individual exits (Section 8) |
| Work-Life Balance issues | Partial signal: "the occasional early morning debugging a pipeline" in both IC engineering JDs |

**Risk level: UNKNOWN (no evidence base), structurally MODERATE.** There is no evidence of systemic toxicity, and no evidence against it. The structural profile (founder-run startup of ~50, no works council, vacant engineering leadership, on-call on a small team) is the one where localized dysfunction would go unreported.

---

## Section 5: Compensation

#### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| Glassdoor (EcoPlanet Green Operations GmbH, via CDP) | Senior Software Engineer | €81.4K-88.2K | VSOP (unvalued) | n/a | ~€81-88K | 1 |
| Glassdoor (same) | Revenue Operations Manager | €60.3K-65.5K | | | | 1 |
| Glassdoor (same) | Account Executive | €133.2K-145.6K (incl. commission) | | | | 1 |
| Glassdoor (same) | Growth Analyst | €31.4K-33.5K | | | | 1 |
| levels.fyi | n/a | no company entry (404) | | | | 0 |
| Personio JDs | all engineering roles | "Competitive salary"; no range published | | | | n/a |

**Munich reference bracket (levels.fyi Germany, from earlier reports in this project):** Senior SWE median ~€81.5K total. Seed and Series A startups typically pay ~€75-95K base plus VSOP. Large, profitable Munich employers pay ~€85-110K base, with the 90th percentile at €120K+. Munich-specific 75th/90th percentiles for ecoplanet: **UNAVAILABLE**.

#### Equity / Stock

**VSOP** (virtual stock option plan), per the careers page and Welcome to the Jungle. A VSOP is a contractual cash claim on an exit, not real shares. It pays only on an exit or liquidity event, typically vests over four years with a one-year cliff, and is taxed as income when paid. The Series A post-money was ~$70M (Dealroom), so a typical senior grant (0.05-0.2%) is worth very little unless the valuation rises many times over. Liquidity risk: high (private, Series A, no secondary market).

#### Verdict

**COMPARABLE TO BELOW, mostly UNVERIFIED.** The single Glassdoor Senior SWE data point (€81-88K) sits at the startup norm and below the €85-110K base bracket of large, profitable Munich employers. VSOP upside does not offset that on a risk-adjusted basis. Salary would have to be confirmed directly.

---

## Section 6: AI/ML & Tech Stack Fit

#### AI Strategy

AI is a product feature on top of the data platform, not the core of the business:
- **"KI Ember"** in the Cockpit flags savings potential from meter data. The Data Engineer JD makes this concrete: "a meter drifting, a machine left running overnight, consumption that does not fit the pattern". This is classical anomaly detection on time series.
- **AI-driven procurement timing:** "KI-gestützte Marktbeobachtung mit automatisierten Empfehlungen für den optimalen Beschaffungszeitpunkt", plus "forecasting and optimization services" (Head of Engineering JD).
- **EnergieGPT** (energiegpt.ecoplanet.tech): an LLM assistant for energy prices, regulation and documents, used mainly for lead generation.
- **Internal AI tooling:** the GTM Engineer role expects agents and dashboards "shipped with Claude Code, Codex, or similar" and LLM call analysis and deal scoring on HubSpot data.

There is no ML platform or MLOps team. Data science sits partly in an R&D team and partly in the Data Engineer role. This is applied, production analytics on a small scale: real, but thin.

#### Tech Stack

Derived from the current Personio JDs (primary), an older Welcome to the Jungle Senior Full Stack posting (closed), and the website's tracking stack. The GitHub org `ecoplanet-tech` holds only one public fork ("cyclone-ai") and reveals nothing.

| Category | Technologies |
|---|---|
| **Primary language(s)** | **TypeScript** (backend services, ingestion, APIs; Platform Engineer must-have). Earlier posting: Kotlin/Java with Spring. Python and SQL for data engineering and data science. Kotlin is still named as a "second language" option |
| **AI/ML** | Time-series anomaly detection, forecasting and optimization services; LLM assistant (EnergieGPT); stack not named |
| **Cloud** | **GCP** (current Platform JD). The older full-stack posting listed AWS/Azure/GCP generically |
| **Infrastructure** | **Kafka** ("the spine of the system"), Kubernetes, infrastructure as code, CI/CD, observability |
| **Data** | High-volume meter time series; Postgres, MongoDB, MySQL and RabbitMQ in the older posting |
| **Other** | Frontend Vue.js / React / Angular (older posting); HubSpot, Clay, n8n, PostHog, RudderStack (GTM / analytics) |

#### Current Open Roles

Checked on the Personio XML feed (13 October 2026) and via LinkedIn voyager (`jobState: LISTED`, `closed: false` for both LinkedIn IDs).

| Role | Division/Team | Level | Key Tech | Link |
|---|---|---|---|---|
| Data Engineer (m/f/d) | Engineering (12 engineers, 2 squads) | Experienced, 5-7 yrs DE + hands-on data science | **Python, SQL**, cloud data infra, time-series; nice to have: TypeScript/Kotlin, IoT/metering, streaming | [Personio](https://ecoplanet-green-operations-gmbh.jobs.personio.de/job/2771235) / [LinkedIn](https://www.linkedin.com/jobs/view/4458005615/) |
| Platform Engineer (m/f/d) | Engineering | Senior (6-8 yrs) | **TypeScript**, Kafka, GCP, Kubernetes, IaC; Python/Go/Kotlin nice to have | [Personio](https://ecoplanet-green-operations-gmbh.jobs.personio.de/job/2789101) / [LinkedIn](https://www.linkedin.com/jobs/view/4463018528/) |
| Head of Engineering (m/f/d) | Engineering leadership (11 engineers, 2 EMs) | Executive, hands-on | Multi-tenant SaaS, time-series, IoT, ML in production; owns on-call | [Personio](https://ecoplanet-green-operations-gmbh.jobs.personio.de/job/2777720) |
| GTM Engineer (m/f/d) | G&A / RevOps | 2-5 yrs | HubSpot, Clay, n8n, AI agents; **fluent German required** | [Personio](https://ecoplanet-green-operations-gmbh.jobs.personio.de/job/2775119) |

The **Data Engineer** role is the only Python-central opening. It is a data engineering and applied data science role, not a software or ML platform role.

**Verdict:** A TypeScript-on-Kafka/GCP event-driven SaaS backend that ingests industrial meter data, with Python limited to the data pipeline and anomaly/forecasting layer. This is applied production engineering in a small team (11-12 engineers), not research. The AI/ML component is modest: time-series anomaly detection and forecasting, plus an LLM front-end used for marketing.

---

## Section 7: Language

- All engineering JDs are in English and require "Clear written and spoken English. **German is a plus**". The Head of Engineering JD says "German is a strong plus: most of our customers are German Mittelstand".
- The GTM Engineer role requires "Fluent German and English". The website, LinkedIn posts, webinars and customer material are German-first.
- The careers page lists 13+ nationalities. The engineering JDs are written in fluent, idiomatic English.

**Verdict:** **PASS for engineering roles** (English required, German optional). Expect German in company-wide meetings and customer-facing contexts.

---

## Section 8: Stability

#### Financial Position

From NorthData chart data, sourced from the filed annual accounts (published 17.09.2024 and 11.11.2025):

| Year | Net result (Jahresfehlbetrag) | Total assets (Bilanzsumme) |
|---|---|---|
| 2022 | -€194.7K | €422.5K |
| 2023 | -€938.9K | €1,546.5K |
| 2024 | **-€2,851.3K** | €2,553.8K |

The balance sheet at 31.12.2024 shows cash of **€2,017.8K**, receivables of €376.9K and inventories of €74.0K. Revenue and headcount are censored (small-company filing). The €16M Series A closed in January 2025 and is therefore not in the 2024 balance sheet. The 2025 accounts are not yet filed (expected around Q4 2026). Trend: losses roughly tripled each year while the team grew from ~27 to ~40, consistent with deliberate VC-funded growth. No credit rating.

#### Financial Runway

No public runway or burn-rate statement exists. The March 2025 coverage (deutsche-startups.de via Techleap) said the money is for European expansion, go-to-market and product, with a target of 500 customers within a year. The site now claims 150+ active customers.

**Bottom-up model (estimates, 2026):**

| Cost line | Annual estimate |
|---|---|
| Staff (~55 FTE × ~€85K fully loaded; mix of engineers, sales, energy experts, students) | ~€4.7M |
| Cloud, software, data feeds (GCP, Kafka, HubSpot, market-data licences) | ~€0.5M |
| Offices (Munich Marsstraße, Berlin) | ~€0.4M |
| Marketing, events, lead-gen tooling, recruiting | ~€0.6M |
| **Total gross burn** | **~€6.2M/year** |

| Revenue source | Est. annual inflow |
|---|---|
| Cockpit subscriptions and procurement fees (150+ customers; seven-figure revenue already in the first product year, 2023/24) | ~€2.5-4M/year |
| **Total revenue offset** | **~€3M/year** |

Starting cash: €2.0M (31.12.2024, filed balance sheet) + €16M Series A (January 2025) = ~€18M. Assumed net burn in 2025: ~€4.5M (2024 loss of €2.85M plus growth). Assumed burn January to September 2026: ~€2.5M. **Estimated cash at hand in October 2026: ~€10-11M.**

| Scenario | Net burn | Cash at hand | Runway | Next round needed by |
|---|---|---|---|---|
| Optimistic (revenue ~€4.5M) | ~€2M/year | ~€11M | ~5 years | ~2031 (or break-even first) |
| Base case | ~€3.5M/year | ~€10.5M | ~3 years | ~2028-2029 (a raise would start ~mid-2028) |
| Stress (revenue flat, hiring continues) | ~€6M/year | ~€10M | ~1.7 years | ~mid-2028 (process starts early 2027) |

Cash figure: €2,017,805, balance sheet at 31.12.2024 (NorthData, observed 2026-10-13), plus the announced €16M Series A. Every later figure is a model estimate.

#### Layoffs

No layoffs reported in the press, on TrueUp, or anywhere else found. One unexplained discrepancy: the careers page says "70+ Teammitglieder", while the company's own September 2026 JDs say "around 40 people". Not evidence of a layoff, but worth asking about.

#### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | **NO (none found)** | No Kununu profile to search; no LinkedIn title mentioning one; nothing in press or JDs. Typical for a ~50-person startup |
| Collective agreement | **NONE** | JDs say "Competitive salary" with bonus/VSOP; no "tarifgebunden" or AT language |
| European works council | N/A | Single German entity |
| Conflict signals | None found | n/a |

**Verdict:** **FAIL (as a "mature, stable" employer).** The company is a 4-year-old, loss-making Series A startup with roughly 2-3 years of modelled runway. It has no works council or collective agreement, and engineering leadership is vacant. The financing is solid for its stage.

---

## Section 9: Regulated Industry

ecoplanet operates in the German energy market but is not itself a regulated utility, balancing-responsible party or metering-point operator. The product's selling point is helping customers comply with EnEfG (Energieeffizienzgesetz), ISO 50001, energy-tax relief rules and procurement regulation. The Head of Engineering JD mentions "real physical and regulatory constraints" and owning "security and compliance". Expect B2B security questionnaires (possibly ISO 27001 later) and customer data-protection work, but no formal safety case, BaFin or medical-device process.

**Verdict:** PASS (low regulatory burden on engineering)

---

## Section 10: On-Call

- Head of Engineering JD: "**Operations. Reliability, on-call, incidents, security posture, and cloud spend**" and "Run incidents properly: fast response, honest postmortems".
- Platform Engineer JD: "Hands-on with Kafka in production ... and **what you actually do at 3am when a consumer group is hours behind**"; "You run what you build: monitoring, alerting, and the occasional early morning debugging a pipeline."
- Data Engineer JD: the same "You run what you build ... the occasional early morning debugging a pipeline" line (as a nice-to-have).
- The product ingests real-time meter data from industrial sites and drives "automation that acts on customer assets", so an outage is customer-visible quickly. With 11-12 engineers, any rotation comes around often.

**Verdict:** **FAIL** for the Platform Engineer role (on-call is explicit). **CAUTION** for the Data Engineer role (run-what-you-build pipeline ownership; on-call participation unconfirmed).

---

## Section 11: Interview Process

| Metric | Value |
|---|---|
| Difficulty | UNKNOWN (0 interview reports on Glassdoor for E10903041) |
| Positive experience | UNKNOWN |
| Average duration | UNKNOWN |
| Rounds | UNKNOWN |

The JDs give the only hints: "We don't do long forms. We don't do generic cover letters. Send us your CV and surprise us." The JD language ("what it looked like before and after", "how to make a call with incomplete information", "can a change somewhere else in the chain make this easy?") suggests an experience- and judgement-focused process rather than LeetCode, but this is **UNVERIFIED**. The unrelated "Ecoplanet Renewable Energy" Glassdoor profile (3 interviews, 3.0 difficulty) must not be confused with this company.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | Mostly: Cockpit SaaS plus a procurement and advisory service layer - BORDERLINE/PASS |
| Not consulting | Engineers build an internal product; advisory sits in commercial teams - PASS |
| Profitable | Net loss of €2.85M (2024), widening each year - **FAIL** |
| Employee count | ~45-75 (company says "around 40" in current JDs); 11-12 engineers |
| English-speaking | English required, German a plus for engineering - PASS |
| Local entity + engineering contracts | EcoPlanet Green Operations GmbH, HRB 277961 München; permanent contracts via own Personio - PASS |
| Location / work model | Marsstraße 46 (Maxvorstadt); LinkedIn says on-site, careers page says remote possible - model UNVERIFIED |
| Glassdoor | 1 rating, no reviews - **FAIL (no evidence base)** |
| Kununu | No profile - UNKNOWN |
| Salary | One Senior SWE data point at €81-88K, VSOP - COMPARABLE/BELOW, UNVERIFIED |
| AI/ML content | Time-series anomaly detection, forecasting, LLM assistant; no ML platform - modest |
| Computer-language/Tech-stack | TypeScript, Kafka, GCP, K8s; Python only in the Data Engineer role - **FAIL for Python-main**, partial for the Data Engineer role |
| No on-call | On-call explicit in the Head of Engineering and Platform JDs - **FAIL** |
| WLB / Stability | Series A, ~2-3 years modelled runway; no WLB data - **FAIL** on maturity |
| Works council / collective agreement | None - CAUTION |
| Regulated industry | Low burden - PASS |
| Review themes | None available; structural risk moderate |
| Engineering leadership | No CTO; Head of Engineering vacant since September 2026 - CAUTION |
| Headcount consistency | 70+ (careers page) vs "around 40" (JDs) - unexplained |

---

## Section 13: Verdict

**Recommendation: Exclude** (at most, monitor the Data Engineer role).

**Strengths.** ecoplanet addresses a real, durable pain point for German industry (energy costs and EnEfG / ISO 50001 compliance), has top-tier investors (EQT Ventures, HV Capital), and runs a small engineering team with a refreshingly pragmatic culture as written in the JDs. The office is central and reachable in about 42 minutes. Engineering works in English. The registered GmbH employs engineers directly on permanent contracts.

**Hard blockers:**
1. **Not mature or profitable.** The company is four years old, losses grew from €0.19M (2022) to €2.85M (2024), and it depends on a single €16M Series A. Modelled runway is about 3 years in the base case and under 2 in the stress case, so a further round or break-even is needed by roughly 2028.
2. **No review evidence.** There is no Kununu profile, one star rating on Glassdoor, and nothing on Blind or GPTW.
3. **On-call.** The Platform Engineer posting, the closest senior engineering role, explicitly includes 3am Kafka incidents. The Head of Engineering owns an on-call rotation across 11-12 engineers.
4. **Python is not the main language.** The platform and backend are TypeScript (historically Kotlin/Java). The only Python-central opening is a Data Engineer role combining pipelines with hands-on data science.

**Secondary concerns:** No CTO and a vacant Head of Engineering, so the incoming engineer's manager and technical direction are both unknown. The headcount claims are inconsistent (70+ vs ~40). There is no works council or collective agreement. VSOP-only equity at a ~$70M Series A valuation. The one salary data point (€81-88K) is at the startup norm, below large-employer pay. LinkedIn tags the roles "On-site" while the careers page promises remote flexibility.

**Recommendation sentence:** Do not prioritise ecoplanet. If the search widens to Series A startups, the **Data Engineer** role is the only one worth a look, and only if the following are confirmed in a first call: (a) no formal on-call rotation for data roles, (b) at least two remote days a week, (c) a base of €90K+ (the published Glassdoor data point is lower), (d) who the Head of Engineering will be, and (e) current headcount, 2025 revenue and the timeline for the next financing round.

---

## Sources

- [ecoplanet - Impressum](https://www.ecoplanet.tech/impressum) (CDP)
- [ecoplanet - Karriere](https://www.ecoplanet.tech/karriere) (CDP)
- [ecoplanet - Energie günstig einkaufen](https://www.ecoplanet.tech/loesungen/einkauf) (CDP)
- [ecoplanet - Preferred Partner Platform](https://www.ecoplanet.tech/unternehmen/partner) (CDP)
- [ecoplanet - Personio job board](https://ecoplanet-green-operations-gmbh.jobs.personio.de/) (XML feed via curl)
- [Personio - Data Engineer (m/f/d)](https://ecoplanet-green-operations-gmbh.jobs.personio.de/job/2771235)
- [Personio - Platform Engineer (m/f/d)](https://ecoplanet-green-operations-gmbh.jobs.personio.de/job/2789101)
- [Personio - Head of Engineering (m/f/d)](https://ecoplanet-green-operations-gmbh.jobs.personio.de/job/2777720)
- [Personio - GTM Engineer (m/f/d)](https://ecoplanet-green-operations-gmbh.jobs.personio.de/job/2775119)
- [LinkedIn - Data Engineer posting 4458005615](https://www.linkedin.com/jobs/view/4458005615/) (voyager API via CDP)
- [LinkedIn - Platform Engineer posting 4463018528](https://www.linkedin.com/jobs/view/4463018528/) (voyager API via CDP)
- [LinkedIn - ecoplanet company page](https://www.linkedin.com/company/88905156/) (CDP)
- [LinkedIn - ecoplanet people tab](https://www.linkedin.com/company/88905156/people/) (CDP)
- [NorthData - EcoPlanet Green Operations GmbH, HRB 277961](https://www.northdata.de/EcoPlanet%20Green%20Operations%20GmbH,%20M%C3%BCnchen/Amtsgericht%20M%C3%BCnchen%20HRB%20277961) (CDP, chart data via JS)
- [Glassdoor - search "ecoplanet"](https://www.glassdoor.com/Search/results.htm?keyword=ecoplanet) (CDP)
- [Glassdoor - EcoPlanet Green Operations GmbH overview](https://www.glassdoor.com/Overview/Working-at--EcoPlanet-Green-Operations-GmbH-EI_IE10903041.11,43.htm) (CDP)
- [Glassdoor - EcoPlanet Green Operations GmbH reviews](https://www.glassdoor.de/Bewertungen/-EcoPlanet-Green-Operations-GmbH-Bewertungen-E10903041.htm) (CDP)
- [Glassdoor - EcoPlanet Green Operations GmbH salaries](https://www.glassdoor.de/Gehalt/-EcoPlanet-Green-Operations-GmbH-Geh%C3%A4lter-E10903041.htm) (CDP)
- [Glassdoor - EcoPlanet Green Operations GmbH interviews](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/-EcoPlanet-Green-Operations-GmbH-Fragen-im-Vorstellungsgespr%C3%A4ch-E10903041.htm) (CDP)
- [Glassdoor - Ecoplanet (Brazil, unrelated)](https://www.glassdoor.com/Overview/Working-at-Ecoplanet-EI_IE9464753.11,20.htm) (CDP)
- [Kununu - search "ecoplanet"](https://www.kununu.com/de/search?q=ecoplanet) (CDP; direct slugs returned 405 via curl)
- [Teamblind - ecoplanet](https://www.teamblind.com/company/ecoplanet) (404 via curl)
- [levels.fyi - ecoplanet](https://www.levels.fyi/companies/ecoplanet/salaries) (404 via curl)
- [Dealroom - Ecoplanet](https://dealroom.co/companies/ecoplanet/) (CDP)
- [Techleap / Dealroom - Ecoplanet secures €22M for energy platform](https://finder.techleap.nl/news/feed/ecoplanet-secures-22m-for-energy-platform) (CDP)
- [Tracxn - Ecoplanet profile](https://tracxn.com/d/companies/ecoplanet/__OPh5CA8GNCaanUu3Y4lQgoU3hgRSX2yuGLb9bWNtCcs)
- [tech.eu - ecoplanet secures €16M Series A led by EQT Ventures](https://tech.eu/2025/01/20/ecoplanet-secures-16m-series-a-led-by-eqt-ventures/)
- [ESG Today - Ecoplanet raises €16 million](https://www.esgtoday.com/ecoplanet-raises-e16-million-for-solution-for-companies-to-optimize-use-of-green-and-affordable-energy/)
- [Munich Startup - ecoplanet secures €16 million](https://www.munich-startup.de/en/news/ecoplanet-secures-e16-million)
- [Munich Startup - €3.5 million for ecoplanet](https://www.munich-startup.de/en/news/e3-5-million-for-ecoplanet)
- [Munich Startup - ecoplanet: the cockpit for energy management](https://www.munich-startup.de/en/news/ecoplanet-the-cockpit-for-energy-management)
- [Munich Startup - ecoplanet 7 questions](https://www.munich-startup.de/en/101646/ecoplanet-7-questions/)
- [Munich Startup - startup profile](https://www.munich-startup.de/en/startups/ecoplanet-green-operations-gmbh/)
- [Startbase - ecoplanet sammelt 2,6 Millionen Euro Startkapital ein](https://www.startbase.de/news/ecoplanet-sammelt-26-millionen-euro-startkapital-ein/)
- [Startbase - ecoplanet sichert sich 16 Millionen Euro Series A](https://www.startbase.com/news/ecoplanet-sichert-sich-16-millionen-euro-series-a/)
- [Heidelberg24 - Energiekosten: So bekommt der Mittelstand die Kontrolle zurück](https://www.heidelberg24.de/politik-und-wirtschaft/energiekosten-so-bekommt-der-mittelstand-die-kontrolle-zurueck-zr-94512907.html)
- [Welcome to the Jungle - ecoplanet company page](https://app.welcometothejungle.com/companies/ecoplanet-1)
- [Welcome to the Jungle - Senior Full Stack Engineer (closed)](https://app.welcometothejungle.com/jobs/XZlAIZyW/company)
- [Arbeitnow - Platform Engineer, ecoplanet](https://arbeitnow.com/jobs/companies/ecoplanet-green-operations-gmbh/platform-engineer-munchen-481409)
- [Crunchbase - Maximilian Dekorsy](https://www.crunchbase.com/person/maximilian-dekorsy)
- [GitHub - ecoplanet-tech organisation](https://github.com/ecoplanet-tech) (GitHub API via curl)
- [OpenStreetMap Nominatim - Marsstraße 46](https://nominatim.openstreetmap.org/search?q=Marsstra%C3%9Fe+46,+80335+M%C3%BCnchen&format=json&addressdetails=1) (curl)
- [Overpass API - transit stops within 700 m](https://overpass.kumi.systems/api/interpreter) (curl)
