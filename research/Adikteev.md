# Adikteev - Full Research Report

_Researched: 2026-11-12_

> **Critical Disqualifiers** (full report follows for completeness):
> 1. **No German legal entity.** The only German subsidiary, **Adikteev GmbH (formerly Trademob GmbH), HRB 129239 B, Amtsgericht Charlottenburg**, went into liquidation in September 2021 and has since been deleted from the register (NorthData marks it ✝︎ with "Löschung"). No other German Adikteev entity exists. A direct German employment contract is not possible.
> 2. **No Munich or German office, and remote hiring excludes Germany.** The current offices are Paris, Barcelona, San Francisco and Seoul. The structured job data on the careers site limits remote engineering applicants to **France and Spain** (`applicantLocationRequirements`). The one remote engineering posting that says "100% Teleworking" also requires EU residency and is tied to Paris/Barcelona.
> 3. **The engineering is ad-tech for mobile gaming (real-time bidding, retargeting).** The infrastructure roles carry explicit on-call duty ("Participate in our on-call rotations") on a platform that handles about 4M requests per second across 6 AWS regions.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 2012 (~14 years). Legal entity Keep Nation SA, renamed Adikteev SA |
| Employees | ~120 (CFNews, Oct 2025; careers page says "over 120"). Revelio Labs estimates 155-170 |
| Revenue (FY2024) | **$89M (~€86M)** in 2024; **$150M (~€128M) expected for 2025** (+68%), per CFNews and Ventech |
| Profitability | **Profitable**: EBITDA margin 18% (2024) rising to 20% (2025E), **~$30M EBITDA expected in 2025**. Senior debt is 2x 2024 EBITDA - **PASS** |
| Ownership | Private. Founder-controlled (~60%) after a **management buyout closed 30 Apr 2025**, with **AgilaCapital** (€28M from a pool of 70 tech entrepreneurs) as a large minority holder. Kennet Partners keeps a residual stake. Ventech and Ring Capital exited |
| Software-centric | Ad-tech platform (DSP for retargeting and user acquisition, ML bidding models). Revenue is media spend, not software licences - **PASS** (product company; see Business Model) |

**Key People**
- **Xavier Mariani** - Co-founder and CEO (Glassdoor CEO approval 89% globally, 94% in Paris).
- **Emilien Eychenne** - Co-founder (Directeur Général / director of Adikteev SA).
- **Cédric** - CTO (first name only, from job postings: final-round interviewer).
- **Aldenis** - VP / Head of Engineering. **Loïc** - Chief Product Officer.
- **Laurent Foata** - Founding partner, AgilaCapital.

**Funding History**

| Date | Event | Amount | Notes |
|---|---|---|---|
| Early 2013 | Seed | €600K | Ventech |
| 2015 | Acquisition of MotionLead | n/a | Rich-media mobile ad units |
| Feb 2017 | Acquisition of Trademob (Berlin) | All-share deal | Kennet Partners enters the cap table |
| Feb 2018 | Series B | ~$12M (€10M) | Ring Capital entered late 2017 / 2018 (TechCrunch) |
| Early 2022 | Sponsorless MBO | n/a | Founders and employees became majority holders; Arkéa senior debt |
| 30 Apr 2025 | MBO with AgilaCapital | €28M equity + €30M senior debt (Arkéa) | Reported as a ~€60M transaction. Ventech exits at ~7x |

**Business Model:** Adikteev is a mobile-app performance-marketing platform. It runs ML-driven retargeting (re-engaging lapsed app users) and, since 2025, user acquisition campaigns. It buys inventory programmatically (real-time bidding) on behalf of app publishers, about 80% of them mobile games. Revenue comes from managed campaigns. Account managers and campaign managers run campaigns, but engineers build an internal product (DSP, bidder, ML models), not client deliverables. 98% of revenue is generated outside France (EMEA 62%, US 33%, South Korea 5%).

**Consulting-Adjacency Assessment:** Not consulting. The French registry classifies Adikteev SA under NAF 62.02 ("Computer consultancy activities") and the CSE agreement names the **Syntec** collective agreement, which covers both consultancies and software publishers in France. The registered purpose ("development of tools in web and mobile universes ... advertising space management") and all job postings describe an in-house product. Engineers do not bill hours.

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **Adikteev GmbH** ✝︎ (formerly Trademob GmbH, briefly "Aditkteev GmbH") | HRB 129239 B, Amtsgericht Charlottenburg (Berlin). EUID DEF1103R.HRB129239B | Berlin (deleted) | "Beratung, Vermarktung und Realisierung von in- und ausländischen Internet- und Technologieprojekten und deren Webseiten" |
| **Adikteev SA** (parent, formerly Keep Nation SA) | SIREN 789514619, LEI 894500DOJY1RAJIP3I75 | Registered: 224 Quai de la Bataille de Stalingrad, 92130 Issy-les-Moulineaux, France | "Innovation, research and technical development of tools in web and mobile universes, development of CRM tools ... advertising space management" (NAF 62.02) |

**Verification:** NorthData shows the German GmbH's timeline: Trademob GmbH registered on 22.09.2010. It was renamed Adikteev GmbH in July 2017 after the acquisition, with Adikteev SA as shareholder (2018 filing). It entered **liquidation on 07.09.2021** (liquidator Clement Favier). Final accounts were filed up to 31.12.2022, the last balance sheet showed a **"nicht durch Eigenkapital gedeckter Fehlbetrag"** (deficit not covered by equity) of €431K, and the company was then **deleted (Löschung)**. A former Berlin employee's Glassdoor review lists the con "The company relocated to Paris" (Mar 2022). No other German Adikteev entity appears on NorthData. Today any German resident could only be hired through an EOR or as a contractor, and the job postings do not even offer that for Germany.

**Verdict:** **FAIL** (no German entity. The only one was liquidated and deleted.)

_Retrieval: NorthData via Chromium over CDP._

---

## Section 3: Office Location

- **Office address:** **No Munich or German office.** The company lists its offices as **Paris, Barcelona, San Francisco and Seoul** (careers page "WHERE ARE WE?"). The New York office was closed (CFNews, Oct 2025). The Barcelona office opened in 2025/2026. The London office was closed about seven months after it opened, around 2015 (The Drum, via Briefly). The Paris EMEA office named on the website is **51 rue Saint-Georges, 75009 Paris** (9e arrondissement, Nouvelle Athènes). Nominatim geocodes it to 48.87814, 2.33740, at the Théâtre Saint-Georges building. Job postings use postal code 75009, which matches. The legal seat of the SA is registered in Issy-les-Moulineaux, which differs from the operating office. The former German office was in Berlin (10115). It is closed.
- **Nearest public transport (Paris office, for reference):** Métro **Saint-Georges** (line 12), about 35 m away on Place Saint-Georges. A bus stop "Saint-Georges" on Rue Notre-Dame-de-Lorette is about 30-50 m away. Métro **Notre-Dame-de-Lorette** (line 12) is about 230 m away. Distances come from Nominatim bounded searches. The Overpass API calls (overpass-api.de and kumi mirror) timed out or returned errors, so line numbers come from general knowledge of the Paris network, not from OSM.
- **Work model:** "Flexible remote working policy" and a **4.5-day week (Friday afternoons off)**. Engineering postings are labelled "Remote, Hybrid". The schema.org `applicantLocationRequirements` restricts candidates to **France and/or Spain** (Staff SRE: France + Spain; Principal ML Engineer, Senior Data Engineer: Spain only). A WeLoveDevs listing for Senior Data Engineer (Applied AI) says "100% Teleworking" but requires "residency ... in the European Union" and lists Paris/Barcelona. Benefits for staff outside France are "aligned with local laws", which suggests remote staff are on local contracts in France or Spain. **No evidence of hiring in Germany.**

---

## Section 4: Reviews

**GPTW:** Great Place to Work USA lists a certification profile for Adikteev (ID 7010862), but the certification dates from **September 2018** and is not current. Adikteev is **not** on any GPTW Germany list. Adikteev also holds a **ChooseMyCompany HappyIndex@Work** certification (France, International, March 2026, 83 certified reviews), which is a French equivalent signal. It is not a German award.

#### Glassdoor

_Retrieval: Chromium over CDP (glassdoor.co.uk with all languages, glassdoor.de). Glassdoor rate-limited the session after a few page loads, so per-review pagination and job-title filters could not be retrieved._

| Metric | Global | Germany | Munich | Software Engineers | Paris (ref.) |
|---|---|---|---|---|---|
| **Overall** | 4.4 (57 reviews) | ~3 visible reviews (Berlin, 2019-2022; German-language) | **No data** (0 reviews) | UNKNOWN aggregate (~11 engineering reviews: Data Engineer 3, Engineering Manager 3, Senior Backend Engineer 3, Software Engineer 2) | 4.5 (28 reviews) |
| **WLB** | 4.4 | n/a | n/a | n/a | n/a |
| **Culture & Values** | 4.2 | n/a | n/a | n/a | n/a |
| **Comp & Benefits** | 4.5 | n/a | n/a | n/a | n/a |
| **Career Opportunities** | 4.3 | n/a | n/a | n/a | n/a |
| **Diversity & Inclusion** | 4.6 | n/a | n/a | n/a | n/a |
| **Senior Management** | 4.0 | n/a | n/a | n/a | n/a |
| **% Recommend** | 78% | n/a | n/a | n/a | 78% |
| **CEO Approval** | 89% | n/a | n/a | n/a | 94% |
| **Business Outlook** | 55% positive | n/a | n/a | n/a | 64% positive |

The Germany and Munich filters cannot be applied meaningfully: Germany has only a handful of pre-2022 Berlin reviews and Munich has none. The engineering subset is under 20 reviews and could not be aggregated, so it is directional at best. The global figure (57 reviews) is the only statistically usable one, and it is dominated by account and campaign managers.

#### Kununu

_Retrieval: Kununu over CDP (curl returned HTTP 405). The slug `adikteev` returns 404. The profile lives under the legacy slug `trademob`, titled "Adikteev GmbH, Berlin"._

- **Overall score:** **3.6 / 5.0** (below the Internet industry average of 4.1)
- **Recommendation rate (Weiterempfehlung):** k.A. (no reviews in the last 2 years)
- **Total reviews:** 30 entries. **23 employee reviews** since 2011, mostly from the Trademob era and the 2019 wind-down
- **Sub-scores:** Unternehmenskultur 3.8, Arbeitsumgebung 3.4, Vielfalt 4.0. Weakest factor: **Kommunikation 3.1**
- **Kununu Top Company:** **NO**

This profile reflects the defunct Berlin entity, not the current Paris/Barcelona organisation.

#### Blind / Teamblind

Teamblind company page exists ("Adikteev", Paris, 51-200 employees) with **0 reviews** and no sub-scores. No usable data.

#### Review Themes (2019-2026)

**Positives:**
- **4.5-day week and flexibility:** "Half-day Fridays" (Glassdoor, Dec 2025, current Account Coordinator, San Francisco). "Flexible Arbeitszeiten mit Home Office Möglichkeit, 30 Tage Urlaub im Jahr, junges und dynamisches Team" (Glassdoor, Jul 2019, current Motion Designer, Berlin, 1+ years).
- **Engineering challenge and team quality:** "Performant and motivated team, Tech and product challenges, Good tooling, Mario Kart lunches, Friday afternoon off" (Glassdoor, Apr 2025, current Software Engineering Manager, Paris, <1 year). "high level of difficulty, multi-disciplinary tech stack, nice coworkers" (Glassdoor, Feb 2026, former Software Engineer, Paris, 10+ years).
- **Flat, accessible leadership:** "Great horizontal atmosphere where everyone's voice is heard ... You are encouraged to take ownership of your projects" (Glassdoor, Oct 2025, current Sales Director, 1+ years). "very nice founders, friendly people" (Glassdoor, Mar 2026, current Account Manager, Paris, 1+ years).
- **Smooth recruiting:** "The recruiting process was super smooth (including quick and insightful answer and feedback from the recruiters and hiring managers)" (Glassdoor, Mar 2026, current Campaign Manager, Barcelona, <1 year).

**Negatives:**
- **Benefits below what profits would allow (engineering voice):** "the benefits are very low compared to company's gains" (Glassdoor, Feb 2026, former Software Engineer, Paris, 10+ years). Also: "Not that good for the industry despite what they proclaim" (Kununu, Sep 2019, Ex-Angestellte/r oder Arbeiter/in, Vertrieb / Verkauf, Berlin).
- **Cross-office friction and frequent process churn:** "Varying leaders (in different timezones) and directives make everyday work messy • Processes change more frequently than any stable company would like • Distance between HQ and US teams make knowledge sharing difficult • Quick to let go" (Glassdoor, Dec 2025, current Account Coordinator, San Francisco).
- **Dismissals during long probation, high turnover (customer success):** "the company uses an enormous trial period of 7 months, so they can easily dismiss you ... So don't be surprised to get fired even if you are doing a good job and delivering results" and "people turnover is also huge" (Glassdoor, Dec 2022, former Customer Success team member, Paris, <1 year).
- **Berlin wind-down and location-based treatment (2019):** "wie Arbeitsergebnisse, Leistungen und Fähigkeiten innerhalb einer Firma allein aufgrund des Standorts bewertet werden" and "wie undurchsichtig und unehrlich kommuniziert wird" (Kununu, May 2019, Ex-Angestellte/r oder Arbeiter/in, IT, Berlin, rated 1.0). "100% Top-Bottom without involving team members" (Kununu, Sep 2019, Ex-Angestellte/r oder Arbeiter/in, Vertrieb / Verkauf, Berlin).
- **French as a second office language:** "Es wird sehr viel französisch gesprochen - Bürosprache ist englisch und französisch" (Glassdoor, Jul 2019, current Motion Designer, Berlin).

Overlap with hard red flags: **silent firings / "quick to let go"** (two reviews, both non-engineering) and **communication breakdown** (Berlin era, plus HQ/US friction). These are not engineering-specific.

#### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | Localised. One account-management mid-manager is described as "the classic toxic boss without any leading skills" (Glassdoor, Dec 2022, former Customer Success, Paris). Founders are consistently praised (CEO approval 89-94%). |
| 24/7 Work Expectation | Not reported in reviews. The ad platform runs 24/7 and SRE roles carry on-call (Section 10). Paris/SF/Seoul time zones create some cross-time-zone load: "Communication across global offices can sometimes be challenging due to time zone differences" (Glassdoor, Oct 2025, Sales Director). |
| Internal Surveillance | No reports found. |
| Fear-driven Management | One customer-success review describes demanding micromanagement before client meetings (Dec 2022). Not reported for engineering. |
| Communication Breakdown | Moderate. Berlin 2019 ("undurchsichtig und unehrlich kommuniziert") and HQ/US friction in 2025. Kununu's weakest factor is Kommunikation (3.1). |
| Unpaid Overtime | Not reported. The 4.5-day week is a counter-signal. |
| Silent Firings | **Signals present (non-engineering):** "Quick to let go" (Dec 2025, SF) and "get fired even if you are doing a good job" during a 7-month trial period (Dec 2022, Paris). London (2015, all 5 staff) and New York were closed, and Berlin was wound down in 2019-2021. |
| Work-Life Balance issues | Low. WLB 4.4 globally, Friday afternoons off, 30 days' leave reported in Berlin. |

**Risk level: LOW-MODERATE.** There is no evidence of systemic toxicity. The negative signals are (c) localised dysfunction in account management/customer success and the "quick to let go" pattern of a lean, founder-led ad-tech company that has repeatedly opened and closed offices. Engineering reviews are neutral to positive.

---

## Section 5: Compensation

#### Salary Data

No German data is possible (no German entity). Figures below are **posted OTE ranges for France/Spain** from current job postings on jobs.adikteev.com (OTE = base + quarterly performance bonus):

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| Careers page (Barcelona) | Senior Data Engineer | incl. in OTE | none | quarterly, incl. | €80-90K OTE | 1 posting |
| Careers page (Barcelona) | Senior Data Engineer (ML focus) | incl. in OTE | none | quarterly, incl. | €80-90K OTE | 1 posting |
| WeLoveDevs (Paris/Barcelona, remote EU) | Senior Data Engineer (Applied AI) | n/a | none | n/a | €80-100K | 1 posting |
| Careers page (Paris/Barcelona) | Staff Site Reliability Engineer | incl. in OTE | none | quarterly, incl. | €90-120K OTE | 1 posting |
| Careers page (Barcelona/Paris) | Team Lead, Reliability Engineering | incl. in OTE | none | quarterly, incl. | €100-130K OTE | 1 posting |
| Careers page (Barcelona) | Principal ML Engineer / ML Team Lead | incl. in OTE | none | quarterly, incl. | €125/130-150K OTE | 2 postings |
| Glassdoor | All roles | n/a | n/a | n/a | Salary list empty for UK and France views. Cities with data: Paris (96), SF (11), Berlin (9), NY (7), Barcelona (3) | n/a |
| levels.fyi | n/a | n/a | n/a | n/a | No company page (404) | 0 |

**Munich Senior SWE market reference** (from prior research in this project): median ~€85-95K base, 75th percentile ~€105-115K, 90th percentile ~€125-140K total comp at large profitable employers.

#### Equity / Stock

No equity is offered to new hires in the postings. Listed extras are a profit-sharing scheme (French "participation"), a longevity bonus and meal vouchers. Employees co-invested in the 2022 sponsorless MBO, so some long-tenured staff hold shares, but this is not a standard grant. The company is private and founder-controlled, with no IPO path stated.

#### Verdict

Senior IC roles at €80-90K OTE (bonus included) sit **below** the Munich large-profitable-corporation base median. Staff level at €90-120K OTE is roughly **comparable** to the Munich median-to-75th band, but bonus-inclusive and without equity. Principal/lead at €125-150K OTE reaches the Munich 90th percentile. These are French/Spanish salaries and no German contract is available.

**BELOW to COMPARABLE (level-dependent); UNVERIFIED for Germany.**

---

## Section 6: AI/ML & Tech Stack

#### AI Strategy

ML is core to the product. Adikteev bids in real-time auctions, and its models directly price every bid. The ML team owns "predictive models for CTR, CR, VTA, bid shading, and auction-win probability across display and video inventory", "sub-10ms inference at high QPS through model optimization (ONNX)", and an ML platform with "feature stores, training pipelines, model versioning, A/B experimentation". Models "directly influence billions of real-time decisions every day" (Principal ML Engineer posting). The team is small: a company blog post describes the ML team as four people, two of them PhDs, with a tailored model per campaign KPI. Current postings name a Staff ML Engineer and a Senior ML Engineer as interviewers and add a Principal and a Team Lead. This is genuine applied ML (tabular CTR/CVR prediction, bid optimisation, MLOps), not LLM or GenAI product work. GenAI shows up only as "AI-native developer" tooling (Copilot, Cursor).

#### Tech Stack

_Sources: current job postings on jobs.adikteev.com (Principal ML Engineer, ML Team Lead, Senior Data Engineer, Senior Data Engineer ML-focus, Staff SRE, SRE Team Lead), WeLoveDevs posting, search snippets of earlier Senior Backend Engineer postings, the GitHub organisation `adikteev` (90 repos, mostly forks), and the company ML blog post._

| Category | Technologies |
|---|---|
| **Primary language(s)** | **Scala** (Spark, http4s, doobie, fs2, scala-openrtb forks), **Go** (openrtb, go-gdpr, ec2-price-exporter, all pushed 2025-2026), **Python** (ML, data), Node.js/TypeScript (backend: "strong experience with NodeJS or Go"). Legacy Clojure (Trademob) and Rust experiments (rust-openrtb, actix-web-prom, 2019-2020) |
| **AI/ML** | Python, PyTorch or TensorFlow, scikit-learn, MLflow or Weights & Biases, ONNX (low-latency inference), feature store, A/B experimentation |
| **Cloud** | **AWS**, multi-region (6 regions, "thousands of instances"). GCP is mentioned as an alternative in one data posting |
| **Infrastructure** | Terraform (terraform-aws-alternat fork), Kubernetes ("a plus"), Linux, Prometheus/Grafana-style observability, HAProxy (SPOE Go fork). About 4M requests/second |
| **Data** | Apache Spark, Kafka (real-time), Airflow, Cassandra, Redis, Apache Beam (WeLoveDevs tags). Historically Druid, Flink, Superset |
| **Other** | OpenRTB, GDPR consent handling, mobile SDKs (iOS/Android/Unity "crossdk"), Jira/Confluence |

**Summary:** Polyglot, with JVM (Scala/Spark) for data, Go (and Node.js) for the real-time bidding backend, and a Python ML layer (PyTorch/TensorFlow, scikit-learn, MLflow, ONNX serving) on multi-region AWS with Kafka, Airflow, Cassandra and Redis. This is applied, production ML in high-throughput programmatic advertising (CTR/CVR prediction, bid shading), not research.

---

## Section 7: Language

All engineering postings are in English and require "Fluent in English". French is listed only as optional ("Notions of French can be a plus"). The team spans 18-23 nationalities, with offices in Spain, Korea and the US. However, a Berlin-era review notes "Es wird sehr viel französisch gesprochen - Bürosprache ist englisch und französisch" (2019). French will likely be heard socially at the Paris HQ, and part of the company documentation (CSE agreements, French benefits) is in French. German is irrelevant: there is no German presence.

**Verdict:** **PASS** (English-required, French optional)

---

## Section 8: Stability

#### Financial Position

- Revenue **$89M (2024)**, and **$150M expected in 2025** (+68%) after two flat years (2022-2023) when mobile-gaming spend fell about 10%. Growth is currently "autour de 50%".
- **EBITDA ~18% (2024), ~20% (2025E)**, about $30M expected in 2025. The company is profitable ("Etre dans une entreprise rentable", a 2025 ChooseMyCompany review).
- **€30M senior debt** (Arkéa, ESG-indexed), about 2x 2024 EBITDA, which is low leverage for an LBO.
- Customer concentration risk: **~80% of clients are mobile games**. A €3M bet on the start-up Tempr (2022-2023) failed and that company was liquidated.
- The company is profitable and not VC-dependent, so a runway model does not apply. The debt service burden is light relative to EBITDA.

#### Financial Runway

Not applicable. The company is profitable (EBITDA-positive, with ~$30M 2025E EBITDA) and since April 2025 has been founder-controlled with a minority growth investor, not VC-burn-funded. The main financial risk is the leveraged MBO structure (€30M debt) combined with dependence on mobile-gaming ad budgets.

#### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| ~2015 | London office closed seven months after opening | 5 employees (100% of office) | EMEA activities moved back to Paris (The Drum) |
| 2019-2021 | Berlin (ex-Trademob) wound down; GmbH liquidated 09/2021, then deleted | Whole German entity (Glassdoor salary data shows 9 Berlin entries) | Kununu reviews from 2019 titled "R.I.P." and "An end easy to foresee"; "The company relocated to Paris" (Glassdoor, Mar 2022) |
| 2024-2025 | New York office closed | Unknown | Staff consolidated into SF (CFNews, Oct 2025) |
| Ongoing | Individual dismissals during 7-month probation | Individual | "Quick to let go" (Glassdoor, Dec 2025), "get fired even if you are doing a good job" (Glassdoor, Dec 2022). Both non-engineering |

No mass layoff or PSE (plan de sauvegarde de l'emploi) found. TrueUp was not checked separately. A web search for Adikteev layoffs / licenciements / plan social returned nothing company-specific.

#### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | **N/A in Germany** (no entity). **YES in France:** Adikteev SA has a **CSE** (Comité social et économique) | Company agreement dated 3 May 2022 between Adikteev and the CSE's elected members on the CSE social and cultural budget (Maitredata) |
| Collective agreement | **France: Syntec** sector agreement (Bureaux d'études techniques, cabinets d'ingénieurs-conseils et sociétés de conseil) | Same CSE agreement text (Maitredata) |
| European works council | N/A (about 120 staff, below the threshold) | n/a |
| Conflict signals | None found | Web search, Kununu text |

In Germany a 2019-era Berlin team existed without any known Betriebsrat. The entity was wound down by liquidation, and reviewers describe opaque communication around it.

**Verdict:** **CAUTION.** Financially healthy and growing, with French co-determination (CSE plus Syntec) at HQ. But the company has a record of closing secondary offices (London, Berlin, New York), and it now carries LBO debt and depends on mobile gaming.

---

## Section 9: Regulated Industry

Ad-tech is not a licensed sector, but it is privacy-regulated: GDPR/ePrivacy and IAB TCF consent strings (the `go-gdpr` repo), Apple ATT/SKAdNetwork and Google Privacy Sandbox on Android shape what data the models can use. The practical impact is product and compliance constraints on data use, not formal safety cases or slow release processes.

**Verdict:** **PASS** (low regulatory burden on engineering process)

---

## Section 10: On-Call

Both infrastructure postings say explicitly: **"Participate in our on-call rotations."** (Staff Site Reliability Engineer; Team Lead, Reliability Engineering). The platform is a real-time bidder handling about 4M requests per second across 6 AWS regions, 24/7, so revenue stops when it is down. The ML and data postings do not mention on-call, but they ask candidates to "own the reliability and scalability of the systems you build" and to handle "monitoring, alerting, and error recovery". Backend/bidder engineers are very likely on a rotation too.

**Verdict:** **FAIL** for SRE/infrastructure. **CAUTION (team-dependent)** for ML/data roles.

---

## Section 11: Interview Process

Based on Glassdoor (glassdoor.co.uk, all roles) and the process sections in current job postings.

| Metric | Value |
|---|---|
| Difficulty | 2.98 / 5 (Glassdoor) |
| Positive experience | 75% (16% negative) |
| Average duration | ~22 days (all roles). SRE roles average **~97 days** |
| Rounds | 4-5 |

**Typical engineering process (from postings):**
1. HR interview with a Senior Talent Acquisition Partner.
2. Take-home technical test, done remotely (Principal ML Engineer).
3. Technical interview (1h) with two engineers (e.g. Staff ML Engineer + Senior ML Engineer, or Staff Engineer + Engineering Team Lead).
4. Team-fit interview with the VP/Head of Engineering or an Engineering Team Lead.
5. Final interview with the CTO and CPO (the Principal role adds a "Comex" interview).

Glassdoor stage mix: one-on-one 28%, phone 27%, presentation 18%, panel 8%, skills test 4%. Most-interviewed titles include Senior Data Engineer (3) and Senior Backend Engineer (3). The process is experience- and system-design-focused with a take-home, not LeetCode-heavy.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | PASS: in-house DSP / retargeting platform with ML bidding |
| Not consulting | PASS: product company (NAF 62.02 and Syntec are formalities) |
| Profitable | PASS: $89M revenue 2024, ~20% EBITDA margin, ~$30M EBITDA 2025E |
| Employee count | ~120 (small) |
| English-speaking | PASS: English required, French optional |
| Local entity + engineering contracts | **FAIL**: Adikteev GmbH (HRB 129239 B) liquidated in 2021 and deleted. No German entity |
| Location / work model | **FAIL**: Paris, Barcelona, SF, Seoul only. Remote limited to France/Spain |
| Glassdoor | 4.4 global (57), 4.5 Paris (28). No Germany/Munich data |
| Kununu | 3.6 (23 reviews, legacy Berlin profile, inactive). Not a Top Company |
| Salary | BELOW to COMPARABLE: Senior €80-90K OTE, Staff €90-120K OTE, Principal €125-150K OTE (France/Spain). No equity |
| AI/ML content | Strong applied ML: CTR/CVR, bid shading, ONNX sub-10ms inference, feature store |
| Computer-language/Tech-stack | Polyglot: Scala/Spark, Go, Node.js, Python ML on AWS (Kafka, Airflow, Cassandra) |
| No on-call | **FAIL** (SRE explicit) / CAUTION (ML, data) |
| WLB / Stability | Good WLB (4.5-day week). Profitable, but a history of closing offices plus LBO debt |
| Works council / collective agreement | France: CSE + Syntec. Germany: N/A |
| Regulated industry | PASS (privacy rules only) |
| Review themes | Positive culture and founders. "Quick to let go" and cross-office friction in non-engineering teams |
| Sector concentration | ~80% mobile-gaming clients. Revenue was flat when gaming spend dropped 10% in 2022 |
| Office-closure history | London (~2015), Berlin (2019-2021), New York (2024/25) |

---

## Section 13: Verdict

**Exclude.** Adikteev is a healthy, profitable, founder-led ad-tech company with real applied-ML work, but it has no way to employ someone in Germany, let alone in Munich.

**Strengths:** A profitable growth trajectory ($89M to an expected $150M revenue, ~20% EBITDA margin) and low-leverage financing. A genuinely ML-centric product: models price billions of real-time bids per day, with sub-10ms ONNX inference, feature stores and A/B experimentation. Strong employee sentiment at HQ (Glassdoor 4.4-4.5, CEO approval ~90%, a current ChooseMyCompany certification), a 4.5-day week, transparent salary ranges, and English as the working language.

**Hard blockers:**
1. **No German legal entity.** Adikteev GmbH (formerly Trademob GmbH, HRB 129239 B Charlottenburg) entered liquidation on 07.09.2021 and has been deleted. The parent is a French SA. No direct German employment contract exists.
2. **No Munich or German office, and remote hiring is limited to France and Spain.** Current postings' structured data restricts applicant location to France and/or Spain. The company's German footprint ended with the Berlin wind-down after "The company relocated to Paris".
3. **On-call.** Infrastructure postings require participation in on-call rotations for a 24/7 real-time bidding platform (about 4M requests per second across 6 AWS regions). Backend and ML-platform engineers own production reliability on the same revenue-critical path.

**Secondary concerns:** Compensation at senior level (€80-90K OTE, bonus-inclusive, no equity) is below the Munich large-corporation base median. Only staff/principal bands (€90-150K OTE) reach the Munich 75th-90th percentile. The business is concentrated in mobile gaming (~80% of clients) and was flat in 2022-2023 when gaming ad spend fell. The company has repeatedly closed secondary offices (London, Berlin, New York), and two reviews describe a "quick to let go" pattern during a 7-month probation. The stack is polyglot (Scala, Go, Node.js, Python) rather than centred on one language. Kununu (3.6) reflects only the defunct Berlin entity.

**Recommendation:** Exclude. No further research is warranted unless Adikteev re-establishes a German entity, or opens Germany as a remote-eligible country with a German employment contract (not EOR). Even then, an ML or data role (not SRE/backend) with on-call excluded in writing, at Staff or Principal level (€120K+ OTE), would be needed to clear the remaining criteria.

---

## Sources

- [NorthData: Adikteev GmbH, Berlin (HRB 129239 B)](https://www.northdata.de/Adikteev+GmbH,+Berlin) (Chromium over CDP)
- [NorthData: Adikteev SA, Issy-les-Moulineaux](https://www.northdata.com/Adikteev) (Chromium over CDP)
- [CFNews: Adikteev joue avec un fonds de growth minoritaire (Oct 2025)](https://www.cfnews.net/L-actualite/LBO/Operations/MBO/Adikteev-joue-avec-un-fonds-de-growth-minoritaire-542986) (Chromium over CDP)
- [Ventech: Success Story, 7x return upon Adikteev's LBO (Oct 2025)](https://ventechvc.com/stories/success-story-ventech-realizing-7x-return-upon-adikteevs-lbo) (curl)
- [MergerLinks: Adikteev MBO 2025-04-30](https://app.mergerlinks.com/transactions/2025-04-30-adikteev)
- [CB Insights: Adikteev financials](https://www.cbinsights.com/company/adikteev/financials)
- [Dealroom: Adikteev](https://dealroom.co/companies/adikteev/)
- [Revelio Labs: Adikteev employees](https://www.reveliolabs.com/companies/adikteev/employees)
- [Mergr: Keep Nation SA](https://mergr.com/company/keep-nation-sa)
- [TechCrunch: Adikteev raises $12 million (Feb 2018)](https://techcrunch.com/2018/02/14/adikteev-raises-12-million-for-its-mobile-marketing-platform)
- [FinSMEs: Adikteev acquires Trademob (Feb 2017)](https://finsmes.com/2017/02/french-adtech-company-adikteev-acquires-trademob.html)
- [HTGF: Trademob wird Teil von Adikteev](https://www.htgf.de/erfolgreicher-exit-trademob-wird-teil-des-franzoesischen-adtech-unternehmens-adikteev/)
- [ExchangeWire: Adikteev startet in Deutschland (2017)](https://www.exchangewire.com/blog/2017/07/24/smaato-und-adsquare-kooperieren-adikteev-startet-in-deutschland/)
- [Briefly / The Drum: Adikteev closes London office](https://briefly-prod.herokuapp.com/anchor/Marketing_tech/story/french-ad-tech-startup-adikteev-closes-london-office) (curl)
- [dasauge: Adikteev GmbH (Berlin listing)](https://dasauge.com/-adikteev-gmbh)
- [Adikteev website](https://www.adikteev.com/) (Chromium over CDP)
- [Adikteev careers](https://jobs.adikteev.com/) (Chromium over CDP)
- [Posting: Principal ML Engineer](https://jobs.adikteev.com/o/principal-ml-engineer) (Chromium over CDP)
- [Posting: Machine Learning Team Lead](https://jobs.adikteev.com/o/machine-learning-team-lead-1) (Chromium over CDP)
- [Posting: Senior Data Engineer](https://jobs.adikteev.com/o/senior-data-engineer-8) (Chromium over CDP)
- [Posting: Senior Data Engineer (ML focus)](https://jobs.adikteev.com/o/senior-data-engineer-machine-learning-focus-1) (Chromium over CDP)
- [Posting: Staff Site Reliability Engineer](https://jobs.adikteev.com/o/staff-site-reliability-engineer) (Chromium over CDP)
- [Posting: Team Lead, Reliability Engineering](https://jobs.adikteev.com/o/team-lead-reliability-engineering) (Chromium over CDP)
- [WeLoveDevs: Senior Data Engineer (Applied AI)](https://welovedevs.com/app/job/-OvspBVUZTdj9N71n017) (Chromium over CDP)
- [Jobgether: Senior Backend Engineer (expired)](https://jobgether.com/offer/69ff1aec8444a8266553e6e4-senior-backend-engineer) (curl)
- [WeAreDevelopers: Senior Backend Engineer](https://www.wearedevelopers.com/en/jobs/ext/6348413/senior-backend-engineer) (blocked by Cloudflare)
- [Adikteev blog: How the machine learning team enhances performance](https://www.adikteev.com/blog/how-the-machine-learning-team-enhances-performance)
- [AWS Startups Blog: Mobile app retargeting with Adikteev](https://aws.amazon.com/blogs/startups/mobile-app-retargeting-adikteev)
- [GitHub API: adikteev organisation repos](https://api.github.com/orgs/adikteev/repos?per_page=100) (curl)
- [Glassdoor: Adikteev reviews (global)](https://www.glassdoor.co.uk/Reviews/Adikteev-Reviews-E1253453.htm) (Chromium over CDP)
- [Glassdoor: Adikteev reviews (glassdoor.de)](https://www.glassdoor.de/Bewertungen/Adikteev-Bewertungen-E1253453.htm) (Chromium over CDP)
- [Glassdoor: Adikteev Paris reviews](https://www.glassdoor.co.uk/Reviews/Adikteev-Paris-Reviews-EI_IE1253453.0,8_IL.9,14_IC2881970.htm) (Chromium over CDP)
- [Glassdoor: Adikteev interviews](https://www.glassdoor.co.uk/Interview/Adikteev-Interview-Questions-E1253453.htm) (Chromium over CDP)
- [Glassdoor: Adikteev salaries](https://www.glassdoor.co.uk/Salary/Adikteev-Salaries-E1253453.htm) (Chromium over CDP)
- [Glassdoor review: Software Engineer, Feb 2026](https://www.glassdoor.com/Reviews/Employee-Review-Adikteev-E1253453-RVW102950669.htm)
- [Kununu: Adikteev GmbH (slug trademob)](https://www.kununu.com/de/trademob) (Chromium over CDP; curl returned 405)
- [Kununu review: "It's a shame" (May 2019)](https://www.kununu.com/de/trademob/bewertung/47c7e94c-2ba6-4320-9bc8-4d815de776eb) (Chromium over CDP)
- [Kununu review: "An end easy to foresee" (Sep 2019)](https://www.kununu.com/de/trademob/bewertung/02718103-cb14-4382-aabb-201ebea449a9) (Chromium over CDP)
- [Teamblind: Adikteev](https://www.teamblind.com/company/Adikteev) (Chromium over CDP)
- [Great Place to Work: Adikteev certification (2018)](https://www.greatplacetowork.com/certified-company/7010862) (curl)
- [ChooseMyCompany: Adikteev certified reviews (Mar 2026)](https://choosemycompany.com/en/adikteev/employees/int/certified-reviews) (curl)
- [Maitredata: Accord d'entreprise Adikteev (CSE, Syntec)](https://www.maitredata.com/app/accords-entreprise/adikteev/275359)
- [levels.fyi: Adikteev (404)](https://www.levels.fyi/companies/adikteev/salaries) (Chromium over CDP)
- [OSM Nominatim: 51 rue Saint-Georges, Paris](https://nominatim.openstreetmap.org/search?q=51+rue+Saint-Georges,+75009+Paris&format=json&addressdetails=1) (curl)
- [Similarweb: adikteev.com](https://www.similarweb.com/company/adikteev.com)
