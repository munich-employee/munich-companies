# Zendesk - Full Research Report

_Researched: 2026-11-04_

> **Critical Disqualifiers**
> 1. **No Munich office and no remote-in-Germany engineering.** The only German office is in Berlin (Kreuzberg). Engineering postings in Germany are Berlin hybrid ("must attend our local office for part of the week"); no Munich engineering presence or Germany-remote engineering role was found.
> 2. **Glassdoor below the floor.** Global overall 3.7 (floor 3.8); Software Engineers 3.3 with 51% recommend, Management 2.8 and Career 2.9.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 2007, Copenhagen (19 years); HQ San Francisco |
| Employees | ~6,800 globally (year-end 2025, Revelio Labs via KORE1); ~45% engineering |
| Revenue (FY2024) | ~$1.93B (secondary sources; private company, no filed accounts). Total ARR ~$2B end-2025; AI ARR ~$200M end-2025, CEO targets $400-500M AI ARR in 2026 |
| Profitability | Not disclosed since going private. Cost-discipline narrative since the buyout, LBO debt load unknown - **BORDERLINE (UNVERIFIED)** |
| Ownership | Private, PE-backed: taken private Nov 2022 by Hellman & Friedman and Permira (~$10.2B) |
| Software-centric | Customer-service SaaS (ticketing, messaging, voice, AI agents, WFM/QA) - **PASS** |

### Key People

- **CEO:** Tom Eggemeier (since 2021, led the company through the take-private).
- **Founders:** Mikkel Svane, Morten Primdahl, Alexander Aghassipour (Danish founders; no longer running the company).

### Acquisitions (relevant to engineering footprint)

| Date | Target | What it brought |
|---|---|---|
| Feb 2024 | Klaus (Estonia) | AI quality assurance |
| Mar 2024 | Ultimate (AI agents, Berlin engineering) | The "AI Agents" / GenBot group; source of most Berlin engineering postings |
| May 2025 | Local Measure (Sydney, ~$100M) | AI voice / Amazon Connect contact centre |
| Jul 2025 | HyperArc | AI-native analytics |
| Mar 2026 | Forethought | Self-improving AI agents |

### Business Model

Seat-based SaaS moving to outcome-based pricing (billing per verified AI resolution). Product, not services. Not consulting-adjacent; a few "Forward Deployed Engineer" postings exist in some markets but are not the core engineering track.

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **Zendesk GmbH** | HRB 166170 B, Amtsgericht Charlottenburg (Berlin); EUID DEF1103R.HRB166170B | Neue Schönhauser Str. 3-5, 10178 Berlin (registered) | "Das Marketing, der Vertrieb, die Unterstützung, die Entwicklung sowie die Bereitstellung von technischen Dienstleistungen für die und im Namen der Zendesk, Inc. und ihrer verbundenen Unternehmen" |

**Verification:** Retrieved from NorthData via CDP. Founded 2015 (share capital €25,000), 100% owned within the Zendesk group; managing directors are US group officers. The purpose explicitly includes **development** ("die Entwicklung"), not just sales and distribution, which fits the Berlin engineering postings (AI Agents, ML, data). The Berlin AI Agents posting states location "Berlin, DEU" with a direct hybrid office requirement; no EOR/PEO wording seen. It is a contract-R&D-style entity (services "for and on behalf of" Zendesk, Inc.), which is normal for US subsidiaries. No separate German entity for the acquired Ultimate team was found (NorthData search).

**Verdict:** **PASS** (entity employs engineers directly), but Berlin only.

---

## Section 3: Office Location

- **Office address:** Paul-Lincke-Ufer 39/40, Hof 4, Aufgang 7, 2. OG, 10999 Berlin-Kreuzberg (Zendesk contact page; Nominatim places No. 39 in the Reichenberger Kiez, Kreuzberg, Friedrichshain-Kreuzberg). The registry address (Neue Schönhauser Str. 3-5, Mitte) appears to be the older office. **No Munich office** was found on the careers site, the contact pages, Glassdoor (no Munich reviews) or in job postings. One Ireland-based integration posting listed "Berlin, Munich or Dublin" as possible locations, which is the only Munich mention found (unverified, not engineering).
- **Nearest public transport (Berlin office, straight-line distances from OSM/Overpass):**
  - Bus stop Kottbusser Brücke: ~150 m
  - U Schönleinstraße (U8): ~340 m
  - U Kottbusser Tor (U1, U3, U8): ~420 m
  - U Görlitzer Bahnhof (U1, U3): ~520 m
- **Work model:** Hybrid. Postings: "must attend our local office for part of the week", with the schedule "determined by the hiring manager"; some roles state 1-2 office days. A 2025 Glassdoor review says "Fully remote (old contract, now RTO)"; another (Oct 2025, Senior SWE) says "The company still allows remote work". Current Germany listings on Glassdoor: a home-office SEO role and a Berlin sales role, no engineering. Germany-remote engineering was not observed.

---

## Section 4: Reviews

**GPTW:** Zendesk holds a **Great Place to Work Germany certification** (Berlin; certification period Aug 2025 - Aug 2026) as part of a global 18-country certification (77% of employees say it is a great place to work). Renewal for Aug 2026 onward not yet visible. Positive signal.

#### Glassdoor (via CDP, glassdoor.de)

| Metric | Global | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | 3.7 (2,254 English reviews) | 4.2 (~18: 14 English + 4 German) | No reviews | 3.3 (125 English reviews) |
| **WLB** | 4.0 | 3.8 | n/a | 4.2 |
| **Culture & Values** | 3.7 | 3.8 | n/a | 3.8 |
| **Comp & Benefits** | 4.0 | 3.9 | n/a | 3.7 |
| **Career Opportunities** | 3.4 | 3.7 | n/a | 2.9 |
| **Diversity & Inclusion** | 4.1 | 4.8 | n/a | 3.7 |
| **Senior Management** | 3.3 | 4.2 | n/a | 2.8 |
| **% Recommend** | 66% | 81% | n/a | 51% |
| **CEO Approval** | 61% | 79% | n/a | 43% |
| **Business Outlook** | 57% positive | 81% positive | n/a | 48% positive |

Germany (fewer than 20 reviews, mostly Berlin sales) is directional only. Berlin alone has 12 English reviews. The Software Engineers filter is the most relevant and the weakest.

#### Kununu (via CDP; slug `zendesk4`, curl returned no JSON fields)

- **Overall score:** 4.8 / 5.0 (12 employee reviews)
- **Recommendation rate:** 89% (100% over the last 2 years)
- **Total reviews:** 15 (12 employee, rest applicant); 8 salary entries
- **Kununu Top Company:** NO
- Reviews are mostly Berlin sales staff; no engineering-specific signal. Volume too low to be reliable.

#### Blind (via CDP)

- **Overall:** 3.3 (974 reviews)
- WLB 4.2, Compensation/Benefits 3.4, Company Culture 3.3, Career Growth 3.1, **Management 2.6**
- Recent review text: "pe culture is toxic", "Bloated place".

#### Review Themes (2024-2026)

**Positives:**
- WLB consistently the top category (Glassdoor 4.0 global / 4.2 SWE, Blind 4.2): "Good work life balance", "Recharge Fridays".
- Benefits and flexibility: "Fair salary, good benefits like Recharge Fridays, internet reimbursement".
- Team level: "good manager, great team", "everyone is very helpful".
- Product/AI momentum: "gutes Produkt mit vielen KI-Innovationen (man kann hier hautnah die KI Transformation mitgestalten)".

**Negatives:**
- PE-driven cost cutting and leadership distance: "leadership is getting very detached ... we seldom hear from the C-level, except when they introduce new saving strategies (sabbatical only after 5 years and only for 4 weeks)".
- Understaffing and burnout: "Almost every team (Solutions Consulting, Engineers, ...) is understaffed and personnel is burnt out"; "Workload is way too heavy sometimes" (Berlin SWE).
- Layoffs as a recurring lever (red flag): Berlin Senior SWE, Feb 2025: "when the math ain't mathing they will try to pull everything together by wide layoffs & salaries cutoffs. It's repeated in circles over and over again".
- Career growth weak: SWE Career 2.9, Blind 3.1; "very low chances to grow within the company"; outcome "falls into someone else's mood".
- RTO tightening: "old contract, now RTO"; "In letzter Zeit stark amerikanisiert".
- Strategic narrowing: "The huge focus on integrating with openai can be limiting the innovation".

#### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | Present in reviews but tied to PE cost focus rather than abusive individuals: "company culture is toxic", "pe culture is toxic" (Blind). Management lowest category everywhere (2.6-3.3). |
| 24/7 Work Expectation | Not reported. WLB scores are high. |
| Internal Surveillance | Not reported for employees. |
| Fear-driven Management | Indirect: "we use you as fuel for our own ambitions", career depending on a lead's "mood" (Berlin SWE). |
| Communication Breakdown | "Lack in transparency" (Berlin sales), C-level only visible for "saving strategies". |
| Unpaid Overtime | Not reported explicitly; "workload is way too heavy sometimes", understaffing. |
| Silent Firings | Not reported as such; cuts are executed as layoff rounds, including an unannounced Dublin cut (no press release). |
| Work-Life Balance issues | Not systemic; WLB is the strongest category. Burnout tied to understaffing in some teams. |

**Risk level: MODERATE.** Pattern is (b) PE-owned corporate cost discipline (repeated layoffs, benefit trimming, distant leadership), plus (c) localized team dysfunction, not systemic toxicity.

---

## Section 5: Compensation

#### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| levels.fyi (Germany, via CDP) | Software Engineer | ~€89.5K | €0 | ~€5.1K | ~€94.6K | Germany subset of 383 global |
| levels.fyi (Germany) | Senior Software Engineer | ~€87.7K | ~€11.7K | ~€4.3K | ~€104K | as above |
| levels.fyi (Germany) | Staff Software Engineer | ~€118K | ~€7.7K | ~€11.6K | ~€138K | as above |
| levels.fyi (Berlin, 2026 entries) | Software Engineer, ML/AI (7 yrs) | ~€110K | n/a | n/a | €115K | 1 |
| levels.fyi (Berlin, 2026) | Staff SWE, ML/AI (10 yrs) | ~€148K | n/a | n/a | €163K | 1 |
| levels.fyi (Berlin, 2026) | Staff SWE, Back-End (10 yrs) | ~€110K | n/a | n/a | €137K | 1 |
| Job ad (JobLeads aggregator) | Staff AI Agent Engineer, Berlin | €90-120K | n/a | n/a | n/a | 1 |
| levels.fyi | Germany median, all SWE levels | | | | ~€126K | |

Munich-specific Zendesk data: none (no Munich office). Munich market reference (large profitable employers, Senior SWE, from prior reports in this project): median base ~€85-95K, 75th ~€100-110K, 90th ~€120-130K.

#### Equity / Stock

Private, PE-owned. Levels.fyi shows a modest stock component (~€8-12K/yr) at Senior/Staff, presumably long-term incentive units in the H&F/Permira holding structure. No liquidity until an exit (re-IPO or sale); value depends on PE exit and leverage. No ESPP. Treat stock as illiquid and speculative.

#### Verdict

Senior TC (~€104K) sits around the Munich 75th percentile; Staff base (~€118K, ~€138K TC) sits at the Munich 90th percentile. The ML/AI Staff data point (€163K) is above. **COMPARABLE** (slightly above at Staff), with illiquid equity.

---

## Section 6: AI/ML & Tech Stack

#### AI Strategy

Genuine and central. The "Resolution Platform" and "Autonomous Service Workforce" (Relate, May 2026) run AI agents across messaging, email and voice, priced per verified resolution; AI agents handle ~5B issues/year. AI ARR ~$200M end-2025. Strategy is acquisition-driven (Ultimate, Klaus, Local Measure, HyperArc, Forethought). Berlin is the home of the AI Agents organisation (ex-Ultimate): AI Agent Engineers, ML Engineers, Analytics tribe. Work is applied LLM engineering (multi-step tool-using agents, LangChain/LlamaIndex, evaluation, voice agents), not research. Reviews note heavy dependence on OpenAI.

#### Tech Stack

Sources: job postings (Berlin Software Engineer II, AI Agents, removed Jun 2025; Berlin AI Agent / Staff AI Agent Engineer, Feb 2026 aggregators; Melbourne data-ingestion Senior SWE; Kraków Ruby Staff roles), plus Glassdoor review text.

| Category | Technologies |
|---|---|
| **Primary language(s)** | Ruby (core Support/ticketing, Rails monolith); Python (AI Agents in Berlin, FastAPI); Java, Go, Scala (data/platform); Node.js |
| **AI/ML** | PyTorch, TensorFlow, MLflow, Metaflow, AWS SageMaker, AWS Batch; LLM SDKs (OpenAI), LangChain, LlamaIndex |
| **Cloud** | AWS |
| **Infrastructure** | Kubernetes, ArgoCD, Spinnaker, Docker |
| **Data** | RDS MySQL, Aurora, Redis, S3, Elasticsearch, Kafka, Snowflake (Snowpipe Streaming) |
| **Other** | Datadog, Sentry, PagerDuty |

**Summary:** Polyglot, with a Ruby-centric core product and a Python-centric AI Agents organisation in Berlin (FastAPI, PyTorch, LLM SDKs, LangChain) on AWS (SageMaker, Kubernetes, Kafka, Snowflake). Applied production AI engineering in customer-service SaaS.

---

## Section 7: Language

Engineering postings (Berlin AI Agents and others) are in English and require "fluency in English" only. German is required for customer-facing sales/support roles ("German-speaking" postings), not engineering. The Berlin AI organisation (ex-Ultimate) is international.

**Verdict:** **PASS**

---

## Section 8: Stability

#### Financial Position

Private since Nov 2022; no public financials. Secondary sources: revenue ~$1.93B (2024), ARR ~$2B (end-2025), AI ARR ~$200M growing toward $400-500M (2026 target), ~20,000 AI customers. Headcount grew ~10% in 2025 despite cuts. Net income, debt load and credit rating: **UNKNOWN** (the $10.2B buyout was partly debt-financed; terms not checked). German GmbH accounts on NorthData show only small figures (chart up to ~€1.2M), consistent with a cost-plus service entity.

#### Financial Runway

Not applicable as a startup runway model: a ~$2B ARR SaaS business, PE-owned, not VC-funded. The relevant risk is PE-driven cost-cutting and a future exit (sale or IPO), not cash exhaustion.

#### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| Nov 2022 | Pre-closing reduction | ~5% globally; 84 in California (WARN) | Around the take-private |
| May 2023 | Company-wide layoff | ~8%, ~320 employees | CEO: hiring outpaced business 2020-2022 |
| Feb-Apr 2025 | San Francisco WARN | 51 employees | |
| Jan 2026 | Dublin cut | ~350 roles, about half of Dublin | Business Post via KORE1; no press release |
| Mar 2026 | Reported cut | ~100 | 6figr aggregator only, unverified |

Berlin SWE reviewer (Feb 2025) describes "wide layoffs & salaries cutoffs ... repeated in circles". Pattern: recurring cuts roughly yearly.

#### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | **UNKNOWN** (none found) | No Kununu review mentions "Betriebsrat"/"Tarif" (0 hits); no press or LinkedIn evidence found |
| Collective agreement | **NONE found** | No "Tarif" wording in postings; US-style comp |
| European works council | **UNKNOWN** | Not found |
| Conflict signals | None found | |

No council and no tariff, combined with PE ownership and repeated layoff rounds (including an unannounced Dublin cut), is the risk combination flagged in earlier reports.

**Verdict:** **CAUTION**

---

## Section 9: Regulated Industry

Customer-service SaaS. Compliance is GDPR, SOC 2, ISO 27001, HIPAA for some customers, and EU AI Act exposure for AI agents. No formal safety cases or regulator-gated release processes.

**Verdict:** **PASS**

---

## Section 10: On-Call

No German posting explicitly mentions on-call. The Berlin AI Agents posting asks engineers to "support deployed services to ensure a high level of stability and reliability"; SRE postings list PagerDuty. A globally used 24/7 SaaS (5B issues/year) with engineers owning their services makes product-team on-call rotations likely.

**Verdict:** **CAUTION** (team-dependent, likely present)

---

## Section 11: Interview Process

Based on Glassdoor (875 English interview reports, via CDP).

| Metric | Value |
|---|---|
| Difficulty | UNKNOWN (score did not render on the page) |
| Positive experience | 51% (36% negative) |
| Average duration | UNKNOWN |
| Rounds | UNKNOWN (typically recruiter, hiring manager, technical, final loop) |

Candidates came via online application (61%), referral (19%) and recruiters (13%). The mixed experience score (51% positive) is low for a company of this size. The specific SWE interview page could not be loaded, so the coding vs design balance is **UNVERIFIED**.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | PASS: customer-service SaaS |
| Not consulting | PASS |
| Profitable | UNVERIFIED: private, PE-owned, ~$2B ARR |
| Employee count | ~6,800 globally |
| English-speaking | PASS for engineering |
| Local entity + engineering contracts | PASS: Zendesk GmbH, HRB 166170 B, purpose includes development |
| Location / work model | **FAIL**: Berlin hybrid only, no Munich office, no Germany-remote engineering seen |
| Glassdoor | **FAIL**: 3.7 global (floor 3.8), 3.3 SWE; WLB 4.0 passes |
| Kununu | 4.8, 12 reviews, mostly sales (unreliable) |
| Salary | COMPARABLE; Staff ~€138K TC Germany; illiquid PE equity |
| AI/ML content | Strong: AI agents are the core strategy; Berlin is the AI Agents hub |
| Computer-language/Tech-stack | Polyglot; Python-centric in Berlin AI Agents, Ruby core |
| No on-call | CAUTION |
| WLB / Stability | WLB good; stability CAUTION (recurring layoffs, PE) |
| Works council / collective agreement | None found |
| Regulated industry | PASS |
| Review themes | PE cost cutting, weak management/career scores, RTO tightening |
| GPTW | Certified Germany Aug 2025 - Aug 2026 |
| Acquisition / exit risk | PE ownership since 2022; an exit is expected within a few years |

---

## Section 13: Verdict

**Exclude.**

**Strengths:** Zendesk has real applied-AI work (AI agents across messaging, email and voice, priced on outcomes), and its Berlin AI Agents organisation is Python-centric and English-speaking. It has a German GmbH whose purpose includes development, a GPTW Germany certification, strong WLB scores, and Staff-level pay at or above the Munich 90th percentile.

**Hard blockers:**
1. **Location:** All German engineering is in Berlin-Kreuzberg on a hybrid model where the hiring manager sets office days. No Munich office and no Germany-remote engineering roles were found, and reviews point to a tightening RTO ("old contract, now RTO").
2. **Glassdoor:** Global overall is 3.7, below the 3.8 floor. The Software Engineers view is worse at 3.3, with 51% recommend, Management 2.8, Career 2.9 and 43% CEO approval. Blind matches this: Management 2.6.

**Secondary concerns:** PE ownership with layoffs almost every year (2022, 2023, 2025, a Dublin cut of about half the site in Jan 2026). No works council or collective agreement was found. On-call is likely for product teams. Equity is illiquid until a PE exit. Reviews mention heavy dependence on OpenAI.

**Recommendation:** Exclude, which matches the earlier quick screen. More research is only worth doing if a Zendesk AI Agents role appears that is explicitly open to fully remote work from Munich. If one does, confirm in writing that it is permanently remote, ask about the on-call rotation, and ask the team's attrition since the Jan 2026 cuts.

---

## Sources

- [Glassdoor: Zendesk reviews, global (English)](https://www.glassdoor.de/Bewertungen/Zendesk-Bewertungen-E360923.htm?filter.iso3Language=eng) (CDP)
- [Glassdoor: Zendesk Germany](https://www.glassdoor.de/Bewertungen/Zendesk-Deutschland-Bewertungen-EI_IE360923.0,7_IL.8,19_IN96.htm?filter.iso3Language=eng) (CDP)
- [Glassdoor: Zendesk Munich](https://www.glassdoor.de/Bewertungen/Zendesk-M%C3%BCnchen-Bewertungen-EI_IE360923.0,7_IL.8,15_IC4990924.htm) (CDP)
- [Glassdoor: Zendesk Berlin](https://www.glassdoor.de/Bewertungen/Zendesk-Berlin-Bewertungen-EI_IE360923.0,7_IL.8,14_IC2622109.htm?filter.iso3Language=eng) (CDP)
- [Glassdoor: Zendesk Software Engineer](https://www.glassdoor.de/Bewertungen/Zendesk-Software-Engineer-Bewertungen-EI_IE360923.0,7_KO8,25.htm?filter.iso3Language=eng) (CDP)
- [Glassdoor: Zendesk interviews](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/Zendesk-Fragen-im-Vorstellungsgespr%C3%A4ch-E360923.htm?filter.iso3Language=eng) (CDP)
- [Kununu: Zendesk GmbH](https://www.kununu.com/de/zendesk4/kommentare) (CDP)
- [Blind: Zendesk reviews](https://www.teamblind.com/company/Zendesk/reviews) (CDP)
- [Great Place to Work Germany: Zendesk](https://greatplacetowork.de/beste-arbeitgeber/zendesk/)
- [Zendesk earns 2025 Great Place to Work certification](https://www.zendesk.com/newsroom/articles/zendesk-earns-2025-great-place-to-work-certification/)
- [GPTW global profile: Zendesk](https://www.greatplacetowork.com/certified-company/1315480)
- [NorthData: Zendesk GmbH, HRB 166170 B](https://www.northdata.de/Zendesk+GmbH,+Berlin/Amtsgericht+Charlottenburg+(Berlin)+HRB+166170+B) (CDP)
- [Implisense: Zendesk GmbH](https://implisense.com/en/companies/zendesk-gmbh-berlin-DEHTTC2EC421)
- [Zendesk contact page (Berlin address)](https://www.zendesk.com/sg/contact/)
- [Silicon Allee: Zendesk joins the Factory](https://www.siliconallee.com/news/zendesk-joins-germanys-beating-digital-heart-at-the-factory)
- [Zendesk careers](https://jobs.zendesk.com/us/en/search-results?keywords=engineer&location=Germany) (CDP)
- [levels.fyi: Zendesk SWE Germany](https://www.levels.fyi/companies/zendesk/salaries/software-engineer/locations/germany) (CDP)
- [Built In: Software Engineer II (NodeJS/Python/Ruby), Berlin](https://builtin.com/job/software-engineer-ii-nodejspythonruby/4724113)
- [JobLeads: Staff AI Agent Engineer, Berlin](https://www.jobleads.com/de/job/staff-ai-agent-engineer--berlin--eb3eb54a69b2c35aaf303b03b0a4f9fc9)
- [Fuchsjobs: Senior AI Agent Engineer, Berlin](https://fuchsjobs.de/job/stellenangebote--senior-ai-agent-engineer-berlin-zendesk-a9c40f) (410 at fetch time; search snippet used)
- [Fuchsjobs: AI Agents Engineer, Berlin](https://fuchsjobs.de/job-detail/stellenangebote--ai-agents-engineer-berlin-zendesk-6bbb5e)
- [Felicis job board: Senior ML Engineer (Ultimate/Zendesk)](https://jobs.felicis.com/companies/ultimate-ai/jobs/48162959-senior-machine-learning-engineer)
- [Built In: Senior Software Engineer (data ingestion)](https://builtin.com/job/senior-software-engineer/8281654)
- [Built In: Senior Software Engineer, Site Reliability](https://builtin.com/job/senior-software-engineer-site-reliability/4584838)
- [Just Join IT: Senior Staff Ruby Software Engineer, Kraków](https://justjoin.it/job-offer/zendesk-senior-staff-ruby-software-engineer-krakow-ruby)
- [Built In: Engineering Manager AI Agents (hybrid policy)](https://builtin.com/job/engineering-manager-ai-agents/7046774)
- [Built In: Zendesk work-life balance FAQ](https://builtin.com/company/zendesk/faq/work-life-balance-wellbeing)
- [Technewsday: H&F-led group acquires Zendesk](https://technewsday.com/?p=31662)
- [HRKatha: Zendesk cuts 320 jobs](https://www.hrkatha.com/news/zendesk-cuts-320-jobs-trimming-workforce-by-8/)
- [CX Today: Zendesk cuts staff by 8%](https://cxtoday.com/zendesk-cuts-staff-by-8)
- [WARNTracker: Zendesk](https://www.warntracker.com/company/zendesk)
- [KORE1: Zendesk layoffs 2026](https://www.kore1.com/zendesk-layoffs-2026/)
- [6figr: Zendesk layoffs](https://6figr.com/layoffs/Zendesk)
- [TrueUp: Zendesk](https://www.trueup.io/co/zendesk)
- [The Letter Two: Zendesk AI ARR $400-500M in 2026](https://thelettertwo.com/2025/12/02/zendesk-ai-arr-500m-2026/)
- [NeoFeed: Zendesk AI ARR above $200M](https://neofeed.com.br/negocios/zendesk-ve-receita-recorrente-de-ia-ultrapassar-us-200-milhoes-e-redesenha-modelo-de-atendimento/en/)
- [SQ Magazine: Zendesk statistics 2026](https://sqmagazine.co.uk/zendesk-statistics-2026-power-moves-in-cx-growth/)
- [Zendesk newsroom: Klaus acquisition closed](https://zendesk.com/newsroom/articles/klaus-close24)
- [Zendesk newsroom: Local Measure acquisition](https://www.zendesk.de/newsroom/articles/localmeasure-acquisition/)
- [Capital Brief: Local Measure at ~$100M](https://www.capitalbrief.com/briefing/local-measure-acquired-by-zendesk-at-100m-valuation-6196bbad-1ea0-4984-8bdc-0d27093d0e5e/)
- [eesel: Zendesk HyperArc](https://www.eesel.ai/blog/zendesk-hyperarc)
- [DestinationCRM: Zendesk acquires Forethought](https://www.destinationcrm.com/Articles/CRM-News/CRM-Across-the-Wire/Zendesk-Acquires-Forethought-174144.aspx)
- [CMSWire: Autonomous AI workforce at Relate 2026](https://cmswire.com/customer-experience/zendesk-unveils-autonomous-ai-workforce-at-relate-2026)
- [Diginomica: Zendesk Relate 2026](https://diginomica.com/zendesk-relate-2026-resolution-platform-ai-driven-service-delivery)
- [Compound: Zendesk GDPR and works council note](https://compound-website.pages.dev/en-DE/tools/zendesk/)
- [OSM Nominatim: Paul-Lincke-Ufer 39](https://nominatim.openstreetmap.org/search?q=Paul-Lincke-Ufer+39,+10999+Berlin&format=json&addressdetails=1)
- [Overpass API](https://overpass-api.de/api/interpreter)
