# Kuro (Kuro Technology GmbH) - Full Research Report

_Researched: 2026-11-24_

> **Disqualifiers** (full report follows for completeness):
> 1. **No Munich presence: on-site in Berlin every day.** All 8 open roles on Kuro's Ashby board are `OnSite` in Berlin. The Staff Software Engineer - AI posting says "Enjoy working onsite with the team at our office in Factory Berlin Mitte every day". No remote or hybrid option and no Munich office exist.
> 2. **Pre-revenue-scale, VC-funded seed startup, not profitable.** Founded November 2024, 16 employees, one €10M seed round (announced 30 Sep 2026). No annual accounts are visible yet.
> 3. **No independent review signal.** Glassdoor: profile exists, 0 reviews. Kununu: 4 reviews (4.8), three of them posted in July 2026. Blind: no profile. The review criteria cannot be assessed.
>
> Counterweight: strong applied-AI work (document understanding, entity resolution, knowledge graph, evals) with real production volume (1M+ pages/month), a Staff role that is explicitly IC with no direct reports, and a Python pipeline layer next to a TypeScript product.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 2024 (UG entered 04.09.2024, converted to GmbH 04.11.2024; press gives "November 2024"), ~2 years |
| Employees | 16 in Berlin (UVC press release, Sep 2026; CEO interview, Oct 2026). LinkedIn: 27 associated members (incl. working students), 8 in "Engineering". Engineering team "currently 5 engineers" (Head of Engineering posting, Mar 2026) |
| Revenue (FY2025/26) | Not disclosed. 12 paying customers (Sep 2026), "rolled out to several hundred users" at each large customer. No filed accounts visible on NorthData |
| Profitability | Not profitable: seed-stage, VC-funded - **FAIL** |
| Ownership | Private, founder-majority. NorthData network shows the two founders' holding UGs (ELIL Ventures UG, L. Scherer Ventures UG) at 30% each; investors UVC Partners (lead), Foundamental, Realyze Ventures, helloworld |
| Software-centric | SaaS AI platform for general contractors - **PASS** |

### Key People

- **Lea Scherer** (formerly Leibold) - co-founder & CEO, Geschäftsführerin. Previously an early employee and part of the leadership team at alcemy (AI control systems for cement and concrete production). Studied business and computer science in Munich (CDTM). [LinkedIn](https://www.linkedin.com/in/lea-leibold/)
- **Jonas Philipp Minkler** - co-founder & CPO, Geschäftsführer. Previously an early employee and part of the leadership team at Capmo (construction management software, Munich). [LinkedIn](https://www.linkedin.com/in/jonas-minkler/)
- **Head of Engineering:** vacant. The role has been advertised since March 2026. In an October 2026 interview the CEO said an early technical key-role hire was reversed (see Section 7).

### Funding History

| Date | Round | Amount | Investors | Valuation |
|---|---|---|---|---|
| 2024/2025 | Pre-seed | Undisclosed | Foundamental (lead), helloworld | Undisclosed |
| 2024 | Public grant | One-year founder grant (amount undisclosed) | WISTA Management / Berlin Senate (Adlershof Founder's Lab) | n/a |
| Registered 05.05.2026, announced 30.09.2026 | Seed | €10M | UVC Partners (lead), Foundamental, Realyze Ventures, helloworld | Undisclosed. Inference: share capital rose from €25,000 to €41,632 (16,632 new shares = ~40% of post-money capital, incl. any pre-seed conversion), and the founders hold 30% each, so investors hold roughly 40%. That is consistent with a post-money in the ~€25-30M range, but this is an estimate, not a reported figure |

### Business Model

Kuro sells a SaaS platform to general contractors (Generalunternehmer) in DACH. It ingests all tender and project documents (plans, building specifications, bills of quantities, reports, 3D/IFC models), links them into a per-customer data model ("context graph"), layers the contractor's own rules on top, and flags contradictions and risks in bid estimation (Angebotskalkulation). It plans to expand into procurement, accounting, compliance and execution management. Named customers: Goldbeck, Hochtief Infrastructure, Köster, Implenia, Geiger, Riedel. Claimed outcomes: ~90 hours saved per bid, 70% of users found information they would otherwise have missed (company figures, not independently verified, as Startbase notes).

### Consulting-Adjacency Assessment

Kuro uses a **forward-deployed engineering** motion: FDE postings describe building PoCs and customer-specific ontologies ("Co-developed interior and shell construction ontologies with enterprise customers"), and the Head of Engineering posting mentions "module abstractions for forward-deployed motion". However:
- Kuro self-identifies as a software platform ("KI-Fundament für Generalunternehmer"), not as a consultancy.
- No hourly billing, consultant titles or project staffing appear anywhere.
- The registered purpose is "development and distribution of Software-as-a-Service" (plus services to the construction industry).
- The Staff role targets the shared platform (workflow harness, ontology, ingestion, eval tooling) "so a new use case ships in ~1 month", rather than one-off client deliverables.

**Conclusion:** product company with a customer-embedded delivery layer. Not consulting. The FDE role carries the customer-specific work; the Staff role is platform-facing.

---

## Section 2: Local Commercial Entity in country of interest

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **Kuro Technology GmbH** (formerly Kuro Technology UG) | HRB 267384 B, Amtsgericht Charlottenburg (Berlin); EUID DEF1103R.HRB267384B; VAT DE450252454 | c/o Factory Works, Rheinsberger Str. 76/77, 10115 Berlin | "Die Entwicklung und der Vertrieb von Software-as-a-Service sowie die Erbringung von Dienstleistungen in der Bauindustrie." |

The registered purpose explicitly names **development** of SaaS, so this is the operating engineering entity, not a sales shell. The company is headquartered in Germany and all staff are in Berlin, so contracts are direct German employment contracts with the GmbH (no PEO/EOR). Managing directors: Lea Scherer and Jonas Philipp Minkler. Share capital €41,632 (after the May 2026 increase). The entity is **in Berlin, not Munich**; there is no Munich branch or second registered office.

**Verdict:** PASS (German entity with engineering purpose). The location does not match the city of interest, which is assessed in Section 3.

---

## Section 3: Office Location

- **Office address:** Factory Berlin Mitte (Factory Works), Rheinsberger Straße 76/77, 10115 Berlin, Mitte (Arkonakiez quarter). Confirmed by the Impressum, NorthData, and the job postings ("our office in Factory Berlin Mitte"). Nominatim geocodes it to 52.5368, 13.3950.
- **Nearest public transport** (OSM Overpass, straight-line distance):
  - **U Bernauer Straße** (U8), ~135 m
  - **U Bernauer Straße** tram stop (M10) and bus stop (247, N8), ~150-235 m
  - **Gedenkstätte Berliner Mauer** tram stop, ~290-320 m
  - U Voltastraße and Brunnenstraße/Invalidenstraße bus/tram stops, ~480-540 m
- **Work model:** **Fully on-site, 5 days/week, in Berlin.** Ashby `workplaceType: OnSite` for all 8 roles; the Staff and Software Engineer postings say "working onsite ... every day"; the Head of Engineering posting says "Based in Berlin or willing to relocate; Full-time, onsite in Berlin Mitte". The careers page explains why: "Walking over to a colleague and solving it now beats any Slack thread. That's why Kuro is built onsite." The page's "Where we work" panel shows the words "Munich" and "Berlin", but no Munich office, Munich posting or Munich address was found. It reads as a nod to the founders' Munich background (CDTM, Capmo), not a work location.
- **Remote eligibility:** none.

**Verdict for the city of interest (Munich): FAIL** - relocation to Berlin required.

---

## Section 4: Reviews

**GPTW:** No Great Place to Work Germany certification or listing found (search of greatplacetowork.de returned no Kuro entry). Unsurprising at 16 employees.

#### Glassdoor

The Glassdoor profile "Kuro Technology" (EI_IE11125886, HQ Berlin) exists with **0 reviews, 0 salaries, 0 interviews** and 8 job listings. A separate profile simply called "Kuro" (EI_IE2789251, 3.0, 3 reviews, 48% recommend) has no location or industry and cannot be tied to this company, so it is not used.

| Metric | Global (0 reviews) | Germany (0) | Berlin (0) | Software Engineers (0) |
|---|---|---|---|---|
| **Overall** | UNKNOWN | UNKNOWN | UNKNOWN | UNKNOWN |
| **WLB** | UNKNOWN | UNKNOWN | UNKNOWN | UNKNOWN |
| **Culture & Values** | UNKNOWN | UNKNOWN | UNKNOWN | UNKNOWN |
| **Comp & Benefits** | UNKNOWN | UNKNOWN | UNKNOWN | UNKNOWN |
| **Career Opportunities** | UNKNOWN | UNKNOWN | UNKNOWN | UNKNOWN |
| **Diversity & Inclusion** | UNKNOWN | UNKNOWN | UNKNOWN | UNKNOWN |
| **% Recommend** | UNKNOWN | UNKNOWN | UNKNOWN | UNKNOWN |
| **CEO Approval** | UNKNOWN | UNKNOWN | UNKNOWN | UNKNOWN |
| **Business Outlook** | UNKNOWN | UNKNOWN | UNKNOWN | UNKNOWN |

No Munich filter is applicable (no Munich staff).

#### Kununu

Slug: `kuro-technology` (found via Kununu search; `kuro`, `kuro1`, `kuro-technology1` return 404).

- **Overall score:** 4.8 / 5.0 (Karriere & Gehalt 4.8, Unternehmenskultur 4.8, Arbeitsumgebung 4.6, Vielfalt 4.9)
- **Recommendation rate (Weiterempfehlung):** 100%
- **Total reviews:** 4 (all employee reviews; no applicant reviews)
- **Kununu Top Company:** NO
- **Pattern note:** three of the four reviews were posted in July 2026, the fourth in October 2026. Only one is from the IT department. Four reviews in one cluster at a 16-person company are **not a reliable signal**; treat them as directional at best.
- Benefits confirmed by reviewers: accessible office (50%), coaching (50%), dogs allowed (50%).

#### Blind / Teamblind

No company page (`/company/Kuro` returns "Page not found") and search for "Kuro Technology" returns "No results found". **No data.**

#### Review Themes (2026)

**Positives:**
- Team and flat hierarchy: "The open culture, great team atmosphere, and flat hierarchy are the biggest strengths. Everyone is approachable, feedback is valued, and there is a strong sense of collaboration." (Kununu, Jul 2026, current Angestellte/r oder Arbeiter/in, Berlin)
- Interesting problems: "truly fun bunch, interesting challenges, promising business domain" (Kununu, Jul 2026, current Angestellte/r oder Arbeiter/in, IT, Berlin)
- Learning and customers: "Great culture - learning curve - unique product - best clients" (Kununu, Jul 2026, current Angestellte/r oder Arbeiter/in, Berlin)
- Engineer statements on the company's own engineering page (company-curated, not independent reviews): end-to-end feature ownership, an "AI-tooling culture, any dev tool we need", hackathon ideas that "actually become product" (kuro.build, team voices, 2026, engineering).

**Negatives:**
- Benefits are thin: "With the company's future growth, there is potential to further improve flexibility and introduce additional benefits over time." (Kununu, Jul 2026, current Angestellte/r oder Arbeiter/in, Berlin). "Flexibility" here matches the every-day on-site policy.
- No independent negative reviews exist; absence of evidence at this sample size says little.
- **Signals from the company's own material** (not reviews), relevant to the red-flag criteria:
  - Intensity language in values and postings: "Hustlers with a Heart ... we step in when it counts", "not interested in corporate comfort", "still hungry and driven - not coasting" (careers page; Head of Engineering posting).
  - On-site every day with no stated flexibility (all postings).
  - A reversed early technical leadership hire (CEO interview, Oct 2026; see Section 7).

#### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | No evidence. Kununu reviews praise approachability and feedback. Sample: 4 reviews. |
| 24/7 Work Expectation | No explicit evidence. "We step in when it counts" and "not coasting" signal an intense early-stage pace. Customers work to hard tender deadlines, which can push urgency onto the team. UNVERIFIED. |
| Internal Surveillance | No evidence. |
| Fear-driven Management | No evidence. |
| Communication Breakdown | No evidence. Flat hierarchy and on-site co-location cited as strengths. |
| Unpaid Overtime | No evidence either way. German startup contracts usually include overtime in the salary; verify in the contract. |
| Silent Firings | One related data point: the CEO said publicly that an early technical key role was filled by "someone who was technically outstanding but did not speak German", called it "a mistake in the requirements profile" and said "We have corrected the decision" (deutsche-startups.de, Oct 2026, CEO). This indicates a quick, founder-led exit decision for a senior technical hire. The person is not named; no further details. |
| Work-Life Balance issues | Structural: 5 days/week on-site, no remote flexibility; one reviewer hopes for more "flexibility". No WLB score exists anywhere. |

**Risk level: UNVERIFIED, tentatively LOW-MODERATE.** Too few reviews for a systemic judgement. Category (a) systemic toxicity: no evidence. Category (b) bureaucracy: not applicable at 16 people. Category (c) localized dysfunction: the reversed technical leadership hire and the Head of Engineering role open since March 2026 point to churn in engineering leadership at an early stage, with the founders deciding directly.

---

## Section 5: Compensation

#### Salary Data

No Glassdoor, levels.fyi (`/companies/kuro-technology` returns 404) or Blind salary entries exist. The only data are ranges published with job postings.

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| Startup Insider (posting) | Staff Software Engineer - AI (6+ yrs) | Not disclosed | Not disclosed | n/a | Not disclosed | 0 |
| Startup Insider / ZipRecruiter (posting) | Fullstack Software Engineer (AI) (3+ yrs) | €80K-120K | Not disclosed | n/a | ~€80-120K + equity | 1 range |
| Startup Insider (posting) | Founding Forward Deployed Engineer (2+ yrs) | €72K-100K | 0.05%-0.2% equity | n/a | ~€72-100K + equity | 1 range |
| Startup Insider (posting) | Senior Product Manager | €85K-110K | Not disclosed | n/a | ~€85-110K | 1 range |
| ZipRecruiter (posting) | Head of Engineering (~10 yrs, player-coach) | 145K-210K (listed as "$", likely EUR from the source posting) | Not disclosed | n/a | ~145-210K | 1 range |
| Startup Insider (aggregate) | All Kuro postings | $87.6K-124.6K average (9 jobs), +22% vs board mid-level average | - | - | - | 9 postings |

**Estimate for Staff Software Engineer - AI:** between the Fullstack range (top €120K) and Head of Engineering (bottom ~€145K), so roughly **€110-145K base** plus virtual equity. This is an estimate, not a disclosed number.

**Munich reference bracket** (Senior Software Engineer, from prior research in this project): median ~€85-95K base, 75th percentile ~€105-115K, 90th percentile ~€125-140K total comp. The Berlin and Munich averages on the Startup Insider board are similar ($79.6-104.7K vs $80.9-108.7K).

#### Equity / Stock

- Equity is offered: the FDE posting lists **0.05%-0.2%**. The instrument is not stated; German seed startups usually issue **virtual shares (VSOP)**, which pay out only on an exit and are taxed as salary. Verify instrument, vesting (typically 4 years, 1-year cliff), and good/bad-leaver terms.
- Paper value, using the inferred ~€25-30M post-money (Section 1): 0.1% is ~€25-30K before dilution, over four years. Not liquid; depends on an exit.
- No public listing, no ESPP, no bonus mentioned.

#### Verdict

The disclosed ranges for the more junior engineering roles (€80-120K for 3+ years) already reach the Munich 75th percentile at the top. A Staff range of roughly €110-145K would sit around the Munich 75th-90th percentile, plus illiquid seed equity. Only the Staff band itself is unconfirmed.

**COMPARABLE** (Staff band UNVERIFIED; ask for the range in the first call).

---

## Section 6: AI/ML & Tech Stack

#### AI Strategy

AI is the core of the product, not a marketing layer:
- **Document understanding at volume:** 1M+ pages/month, 11B tokens/month, 97k containerized pipeline jobs/month (kuro.build). Pages are routed to different readers (Adobe, Datalab, Gemini Vision); A0 drawings are tiled. Cost per page and quality optimisation are named open problems.
- **Knowledge graph / ontology:** a construction ontology and project graph with evidence-linked edges ("every fact traceable to the page it came from"), versioning as a primitive, and contradiction surfacing (e.g. 2.60 m in a drawing vs 2.75 m in a change order).
- **Entity resolution:** context-aware, reversible matching of companies, rooms, positions and prices across BoQs, contracts, drawings and bids; must be able to say "not sure".
- **BIM integration:** parsing IFC models (from Revit/ArchiCAD) and linking document passages to individual 3D elements; native BIM/DWG ingestion is a listed project.
- **Agentic workflows and evals:** an agentic chat, a "workflow harness" and "decision-trace standard", human review/approval surfaces, evaluation and error analysis on shipped AI features (Langfuse).
- **German-language search:** a German tokenizer for construction-specific search.
- Build-or-buy on models is part of the Staff role ("which models we use, and which retrieval and orchestration stack we build on").

This is applied AI engineering on top of foundation-model APIs (no model training mentioned), in production with enterprise customers.

#### Tech Stack

Derived from the current job postings (Staff Software Engineer - AI, Software Engineer - AI, Forward Deployed Engineer, Head of Engineering on Ashby), the company engineering page kuro.build, and LinkedIn employee skills. No public GitHub organisation, StackShare or Himalayas profile was found.

| Category | Technologies |
|---|---|
| **Primary language(s)** | TypeScript (web app; Fastify API + Prisma ORM backend), Python (Prefect workflows, ML services) |
| **AI/ML** | Azure OpenAI, Google Gemini (incl. Gemini Vision), Cohere, AWS model services; OCR/document parsing via Adobe and Datalab; LLM agents, embeddings, vision models; Langfuse for evals and tracing |
| **Cloud** | AWS (RDS, S3, Elastic Beanstalk, ECS); migration from Railway to AWS in progress or completed during 2026 |
| **Infrastructure** | Prefect orchestration on ECS (containerized jobs), Elastic Beanstalk hosting, Datadog observability |
| **Data** | Postgres (Supabase, centralizing to AWS RDS + pgvector), Turbopuffer (vector DB), S3; construction ontology / project graph |
| **Other** | IFC/BIM and DWG parsing, React (5 employees list React.js on LinkedIn), integrations with customer document management and ERP/AVA systems, ISO 27001 certified, EU data hosting |

**Summary:** TypeScript-centric product engineering (Fastify/Prisma backend, TypeScript web app) with a Python pipeline and ML-services layer (Prefect, LLM and vision APIs from OpenAI/Azure, Gemini and Cohere) on AWS with Postgres/pgvector and Turbopuffer. Applied, production AI on unstructured construction documents (document understanding, entity resolution, knowledge graph, evals), not research.

---

## Section 7: Language

- **Postings:** all postings are in English. The Staff Software Engineer - AI and Software Engineer - AI postings require "Communicate fluently in both spoken and written English" and list "German-speaking (definitely not a must, we're fully international)" as a bonus. The Head of Engineering posting requires English only.
- **Customer-facing roles require German:** Forward Deployed Engineer ("at least able to speak C1 german"), Product Manager, Key Account Manager, GTM Manager and Marketing Manager ("Fluent in German").
- **Composition:** LinkedIn shows 17 of 27 members in Germany plus members in Indonesia and Saudi Arabia; engineers on kuro.build have mixed international names. Customers are DACH construction firms working in German; the product includes a "German tokenizer for construction-specific search", and documents (Leistungsverzeichnisse, tenders) are German.
- **CEO statement (deutsche-startups.de, Oct 2026):** "We filled a technical key role early with someone who was technically outstanding but did not speak German. In a market where our customers explain their tenders, their processes and their problems in German, we had made a mistake in the requirements profile. We underestimated how important it is at this stage that everyone in a leadership position sits in front of the customer themselves and understands the problem first-hand. ... We have corrected the decision." (translated)

**Verdict: CONDITIONAL.** On paper English is the working language for engineering and German is optional for the Staff role, so the threshold is met. In practice the CEO has stated that German is required for technical leadership positions, and the Staff role is meant to turn customer requests into scoped plans and influence product decisions. Expect German to matter for growth beyond pure IC work; ask directly whether customer sessions for this role run in German.

---

## Section 8: Stability

#### Financial Position

- **Revenue:** not disclosed. 12 customers (Sep 2026), five or six among the 20 largest DACH general contractors, each with "several hundred users". "Kuro is no longer a pilot there but part of daily operations" (CEO, Oct 2026).
- **Net income:** not disclosed; a 2024-founded seed startup hiring 8 roles is loss-making.
- **Filed accounts:** NorthData lists register publications only (shareholder lists 2024-2026, articles of association, capital increase 05.05.2026). No balance sheet or P&L is visible; the first full financial year accounts (2025) were not yet published or not yet indexed.
- **Cash:** the €10M seed is the only disclosed cash event. The capital increase was registered 05.05.2026, so the money was likely received in spring 2026.
- **Trend:** improving commercially (customer growth from "initial customers for individual processes" in 2024 to 12 enterprise customers in 2026; page volume expected to grow 10x in six months per postings).

#### Financial Runway

**Online search:** NorthData (no financials), Bundesanzeiger (no Jahresabschluss found under HRB 267384 B), TechCrunch/Crunchbase/PitchBook-style coverage (dealroom, nordic9, FundedIQ: seed of ~$11.3-11.5M only). No analyst runway estimates exist. The seed press release states the use of funds: expand the platform from estimation into procurement, accounting and compliance.

**Bottom-up model** (estimates; headcount grows from 16 to ~28-30 as the 8 open roles fill):

| Cost line | Annual estimate |
|---|---|
| Staff (~28 employees × ~€105K fully-loaded Berlin average, incl. employer social costs) | ~€2.9M |
| LLM/OCR/cloud (11B tokens and 1M+ pages/month today, growing; Adobe/Datalab/Gemini, AWS, Datadog) | ~€0.4-0.8M |
| Office (Factory Berlin Mitte membership, ~30 desks) | ~€0.15M |
| Sales, marketing, travel to customer sites, legal, recruiting, ISO 27001 | ~€0.5M |
| **Total gross burn** | **~€4.0-4.4M/year** |

| Revenue source | Est. annual inflow |
|---|---|
| Enterprise SaaS subscriptions (12 customers × ~€60-150K ACV, assumption) | ~€0.7-1.8M/year |
| **Total revenue offset** | **~€0.7-1.8M/year** |

| Scenario | Net burn | Cash at hand | Runway | Next round needed by |
|---|---|---|---|---|
| Optimistic (ARR ~€2M+ and growing, hiring as planned) | ~€2.2M/year | ~€9M | ~4 years | Series A on growth, ~2028 |
| Base case (ARR ~€1.2M, 28-30 staff) | ~€3.0M/year | ~€9M | ~3 years | ~2028-early 2029 |
| Stress (hiring to ~40, revenue flat at ~€0.7M, rising AI costs) | ~€4.5M/year | ~€9M | ~2 years | ~late 2028 |

Cash figure used: **~€9M**, derived from the €10M seed (registered 05.05.2026, announced 30.09.2026) minus roughly six months of 2026 burn at ~16 people; no balance sheet has been published. Pre-seed cash is assumed spent. Observed 2026-11-24.

#### Layoffs

No layoffs found (TrueUp, press, Kununu, LinkedIn). The company is hiring (8 open roles). One documented individual exit: the reversed early technical key-role hire described by the CEO (Section 7), not a layoff.

#### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | NO (none found) | No mention in the 4 Kununu reviews, postings, press or LinkedIn titles. A council is legally possible from 5 employees but typical 16-person startups have none |
| Collective agreement | NONE | Postings and careers page contain no "Tarif", "tarifgebunden" or "AT-Vertrag"; software startup, no employer association membership found |
| European works council | N/A | Single-country, 16-person company |
| Conflict signals | None found | Web search for "Kuro" + Betriebsrat / layoffs returned nothing |

No council and no agreement is the norm at this stage. Weighed with the founder-led reversal of a technical leadership hire, dismissals at Kuro are a founder decision without a council hearing (§102 BetrVG does not apply), and the Kündigungsschutzgesetz applies only after 6 months' employment and with more than 10 employees (now met).

**Verdict: CAUTION** - seed-stage runway (~2-4 years) depending on Series A, no co-determination.

---

## Section 9: Regulated Industry

Construction software for general contractors. No sector regulator (no BaFin, MDR/IVDR, ISO 26262, EN 50128, ITAR). Relevant obligations: GDPR, customer security requirements (Kuro is **ISO 27001 certified** with EU data hosting), and the EU AI Act's general obligations (decision support for estimators is not a high-risk use case under Annex III). Practical impact: enterprise security reviews and auditability requirements, which Kuro has already built into the product ("every answer ... grounded" with source links), not formal safety cases or slow release gates.

**Verdict:** PASS

---

## Section 10: On-Call

- No posting mentions on-call, pager duty, standby or Rufbereitschaft.
- Product nature: a multi-tenant SaaS with a pipeline running 97k jobs/month, used daily by several hundred users per customer under tender deadlines. The engineering team is ~5-8 people with no SRE/platform team, and the Staff role includes CI/CD and tooling. Incidents during business hours will land on the engineers; whether there is an out-of-hours rotation is not stated.
- Construction back-office users work business hours, which limits night-time urgency.

**Verdict:** CAUTION (informal, team-dependent; ask whether an out-of-hours rotation exists and how incidents during bid deadlines are handled).

---

## Section 11: Interview Process

Glassdoor has **no interview reports** for Kuro Technology. The process below comes from the Staff Software Engineer - AI posting.

| Metric | Value |
|---|---|
| Difficulty | UNKNOWN (no Glassdoor data) |
| Positive experience | UNKNOWN |
| Average duration | UNKNOWN |
| Rounds | 5 interviews + reference calls (per posting) |

**Steps (Staff Software Engineer - AI):**
1. Talent Acquisition Call: intro, motivation, logistics and fit (30 min)
2. Impact Interview: deep dive into experience, ownership and impact (60 min)
3. **On-site day in Berlin:**
   - System Design: "Designing under ambiguity & LLM craft" (45 min)
   - AI-Native Coding: "Hands-on coding with AI" (45 min), i.e. coding with AI assistants allowed or expected
   - Final Culture Interview (~60 min)
4. Reference calls
5. Decision

The FDE process starts with calls with the CEO (intro, logistics, fit) and the CPO (product and tech), so founders are involved early. The format is **experience and design focused**, with practical AI-assisted coding rather than LeetCode-style algorithm rounds.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | PASS: SaaS AI platform for general contractors |
| Not consulting | PASS: product company; customer-specific work sits in the FDE role |
| Profitable | FAIL: seed-stage, VC-funded (€10M seed, Sep 2026), loss-making |
| Employee count | 16 (Berlin), ~5-8 engineers; very small |
| English-speaking | CONDITIONAL: English for engineering, German optional on paper; CEO says technical leadership needs German |
| Local entity + engineering contracts | PASS: Kuro Technology GmbH, HRB 267384 B Berlin, SaaS development purpose, direct contracts |
| Location / work model | **FAIL: on-site 5 days/week in Berlin Mitte; no Munich office, no remote** |
| Glassdoor | UNKNOWN: profile with 0 reviews |
| Kununu | 4.8 / 100% recommend, 4 reviews (3 in July 2026); not reliable |
| Salary | COMPARABLE: junior-to-mid ranges €72-120K; Staff estimated ~€110-145K + 0.05-0.2%-type equity (UNVERIFIED) |
| AI/ML content | Strong: production document AI, entity resolution, knowledge graph, evals, build-or-buy on models |
| Computer-language/Tech-stack | TypeScript-centric (Fastify, Prisma) with a Python pipeline/ML layer (Prefect) on AWS, Postgres/pgvector, Turbopuffer |
| No on-call | CAUTION: none stated; small team runs a daily-use SaaS pipeline |
| WLB / Stability | CAUTION: every-day on-site, intensity language; ~2-4 years runway |
| Works council / collective agreement | None / none |
| Regulated industry | PASS |
| Review themes | Too few reviews; positives on team, flat hierarchy, interesting problems; one wish for more flexibility and benefits |
| Engineering leadership | Head of Engineering open since March 2026; an earlier technical key-role hire was reversed |

---

## Section 13: Verdict

**Exclude** for a Munich-based search: the role cannot be done from Munich.

**Strengths:** Kuro has some of the most substantive applied-AI work found in this search: messy multi-format document ingestion at a million pages a month, context-aware entity resolution, an evidence-linked and versioned knowledge graph, BIM integration, and eval-driven agentic workflows. The Staff role is a true IC position ("You have no direct reports") with ownership of architecture, RFCs, build-or-buy decisions and a 2-3 quarter roadmap. Customers are large, named DACH contractors using the product daily, the founders have 14 years in construction tech, and pay for engineers is market-level for a seed startup. Python plays a real role in the pipeline layer (Prefect, ML services).

**Hard blockers:**
1. **Location.** All 8 roles are on-site in Berlin Mitte "every day"; the Head of Engineering posting asks candidates to be "Based in Berlin or willing to relocate". There is no Munich office and no remote eligibility. The founders explain on-site as a deliberate cultural choice ("That's why Kuro is built onsite"), so an exception is unlikely.
2. **Not profitable, seed-stage.** Founded November 2024 with one €10M seed round and an estimated ~2-4 years of runway that depends on a Series A around 2028.
3. **Review criteria cannot be met.** Glassdoor has 0 reviews (no overall or WLB score to check against floors); Kununu has 4 reviews clustered in one month.

**Secondary concerns:**
- **German in practice:** the CEO publicly described reversing a technical leadership hire because the person did not speak German; customer-facing technical roles require C1 German.
- **Engineering leadership in flux:** the Head of Engineering role has been open since March 2026, and the Staff hire would set technical direction alongside founders until it is filled.
- **Stack centre of gravity:** the product core is TypeScript (Fastify/Prisma); Python is the pipeline/ML layer, and the Staff role is "full-stack" through to the chat UI.
- **Intensity and on-site culture:** "Hustlers with a Heart", "not coasting", 5 on-site days, informal incident handling with a small team.
- **No works council or collective agreement**, and illiquid VSOP-style equity.

**Recommendation:** Do not pursue while the search is limited to Munich. Kuro would only become relevant if it opened a Munich site or accepted remote work for senior engineers, which its stated culture argues against. If relocation to Berlin were ever on the table, it would be worth a first call, and the points to verify would be: the Staff salary band and equity instrument, whether customer work for this role runs in German, the Head of Engineering hiring status and who the Staff engineer reports to, how much of the role is Python pipeline work versus TypeScript product work, and out-of-hours incident expectations.

---

## Section 14: Sources

- [Kuro - company website (kuro.technology)](https://kuro.technology/)
- [Kuro - Impressum](https://kuro.technology/impressum)
- [Kuro - About / Unternehmen](https://kuro.technology/about)
- [Kuro - Join us / careers page](https://kuro.technology/join-us)
- [Kuro - Engineering at Kuro (kuro.build)](https://kuro.build/)
- [Kuro - Ashby job board](https://jobs.ashbyhq.com/kuro)
- [Ashby posting API - Kuro job board (JSON)](https://api.ashbyhq.com/posting-api/job-board/kuro?includeCompensation=true)
- [Ashby - Staff Software Engineer - AI](https://jobs.ashbyhq.com/kuro/73521464-8c93-4cc3-a158-21442a65c864)
- [Ashby - Software Engineer - AI](https://jobs.ashbyhq.com/kuro/446f292f-534d-425f-9bfa-e12f71271444)
- [Ashby - Head of Engineering](https://jobs.ashbyhq.com/kuro/5a167bb8-6e74-42c9-b724-6961a5adce2a)
- [Ashby - Forward Deployed Engineer](https://jobs.ashbyhq.com/kuro/857837dc-1532-40a4-84e3-e01745c2d04e)
- [Ashby - Product Manager](https://jobs.ashbyhq.com/kuro/01fac96a-07e3-48e0-9473-74cf10fea1ff)
- [Ashby - Founding Key Account Manager](https://jobs.ashbyhq.com/kuro/9ca49bb6-0e86-483f-9796-95f6776a0803)
- [Ashby - GTM Manager](https://jobs.ashbyhq.com/kuro/2188b16c-49e8-4301-aa3c-2bd2fc6824dd)
- [Ashby - Founding Marketing Manager](https://jobs.ashbyhq.com/kuro/ec50d9a2-094c-4a7f-8fed-8953ba32d49d)
- [Arbeitnow - Staff Software Engineer - AI (Kuro Technology)](https://www.arbeitnow.com/jobs/companies/kuro-technology/staff-software-engineer-ai-berlin-377555)
- [Arbeitnow - Head of Engineering (Kuro Technology)](https://www.arbeitnow.com/jobs/companies/kuro-technology/head-of-engineering-berlin-172007)
- [Startup Insider - Kuro company page](https://jobs.startup-insider.com/unternehmen/kuro)
- [Startup Insider - Kuro salaries](https://jobs.startup-insider.com/unternehmen/kuro/gehalt)
- [Startup Insider - Staff Software Engineer - AI](https://jobs.startup-insider.com/unternehmen/kuro/jobs/staff-software-engineer---ai)
- [Startup Insider - Fullstack Software Engineer](https://jobs.startup-insider.com/unternehmen/kuro/jobs/fullstack-software-engineer)
- [Startup Insider - Founding Forward Deployed Engineer](https://jobs.startup-insider.com/companies/kuro/jobs/founding-forward-deployed-engineer-3)
- [ZipRecruiter - Head of Engineering bei Kuro Technology](https://www.ziprecruiter.de/jobs/565492575-head-of-engineering-bei-kuro-technology)
- [ZipRecruiter - Full Stack Software Engineer AI bei Kuro Technology](https://www.ziprecruiter.de/jobs/582994861-full-stack-software-engineer-ai-bei-kuro-technology)
- [Built In - Head of Engineering](https://builtin.com/job/head-engineering/9797370)
- [Built In - AI Engineer](https://builtin.com/job/ai-engineer/9797346)
- [Built In - Founding Forward Deployed Engineer](https://builtin.com/job/founding-forward-deployed-engineer/9797369)
- [WeAreDevelopers - Fullstack Software Engineer](https://www.wearedevelopers.com/jobs/ext/7176643/fullstack-software-engineer)
- [NorthData - Kuro Technology GmbH, Berlin](https://www.northdata.de/Kuro+Technology+GmbH,+Berlin/Amtsgericht+Charlottenburg+(Berlin)+HRB+267384+B)
- [UVC Partners - €10 million for Kuro (press release)](https://www.uvcpartners.com/blog/eu10-million-for-kuro-germanys-largest-general-contractors-bet-on-this-berlin-based-ai-company-)
- [Startbase - 10 Millionen Euro Finanzierungsrunde für Kuro](https://www.startbase.de/news/10-millionen-euro-finanzierungsrunde-fuer-kuro/)
- [Pulse 2.0 - Kuro Raises €10 Million](https://pulse2.com/kuro-raises-e10-million-to-build-ai-platform-for-general-contractors/)
- [Dealroom - Kuro raises €10M](https://dealroom.co/news/157842-kuro-raises-10m-to-build-the-ai-backbone-for-construction-contractors/)
- [Dealroom - Kuro company profile](https://app.dealroom.co/companies/kuro)
- [Nordic9 - Kuro seed round](https://nordic9.com/news/kuro-raised-10m-in-a-seed-funding-round-led-b/)
- [Nordic9 - Kuro pre-seed led by Foundamental](https://nordic9.com/news/kuro-to-raise-a-pre-seed-funding-round-led-by/)
- [FundedIQ - Kuro Technology funding](https://fundediq.co/kuro-technology-kuro-technology-funding/)
- [startupvalley.news - Kuro seed (30 Sep 2026)](https://startupvalley.news/de/?p=127584)
- [deutsche-startups.de - "Am Ende zählt, was steht" (CEO interview, Oct 2026)](https://www.deutsche-startups.de/2026/10/05/am-ende-zaehlt-was-steht/)
- [deutsche-startups.de - 5 neue Startups: Kuro Technology](https://www.deutsche-startups.de/2026/10/13/5-neue-startups-kuro-technology-kibundo-sapientec-bezlad-zopaai/)
- [Adlershof - KURO: A new start-up is breathing life into the construction industry](https://adlershof.de/en/news/kuro-a-new-start-up-is-breathing-life-into-the-construction-industry)
- [Glassdoor - Kuro Technology overview (0 reviews)](https://www.glassdoor.com/Overview/Working-at-Kuro-Technology-EI_IE11125886.11,26.htm)
- [Glassdoor - search "Kuro Technology"](https://www.glassdoor.com/Search/results.htm?keyword=Kuro%20Technology)
- [Glassdoor - unrelated "Kuro" profile (not used)](https://www.glassdoor.com/Overview/Working-at-Kuro-EI_IE2789251.11,15.htm)
- [Kununu - Kuro Technology](https://www.kununu.com/de/kuro-technology)
- [Kununu - Kuro Technology reviews](https://www.kununu.com/de/kuro-technology/kommentare)
- [Teamblind - Kuro (no page)](https://www.teamblind.com/company/Kuro)
- [Teamblind - search "Kuro Technology" (no results)](https://www.teamblind.com/search/Kuro%20Technology)
- [levels.fyi - Kuro Technology (404)](https://www.levels.fyi/companies/kuro-technology/salaries)
- [Great Place to Work Germany - search](https://www.greatplacetowork.de/?s=Kuro)
- [TrueUp - layoffs search](https://www.trueup.io/layoffs?q=kuro)
- [LinkedIn - Kuro company page](https://www.linkedin.com/company/kuro-ai/)
- [LinkedIn - Kuro people](https://www.linkedin.com/company/kuro-ai/people/)
- [LinkedIn - Lea Scherer](https://www.linkedin.com/in/lea-leibold/)
- [LinkedIn - Jonas Minkler](https://www.linkedin.com/in/jonas-minkler/)
- [OpenStreetMap Nominatim - Rheinsberger Straße 76, Berlin](https://nominatim.openstreetmap.org/search?q=Rheinsberger+Stra%C3%9Fe+76,+10115+Berlin&format=json&addressdetails=1)
- [Overpass API (OSM) - transit stops and routes near the office](https://overpass-api.de/api/interpreter)
