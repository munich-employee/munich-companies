# Filigran - Full Research Report

_Researched: 2026-11-13_

> **Critical Disqualifiers**
> 1. **No German legal entity.** NorthData lists no Filigran company in Germany (the only German hits are an unrelated Berlin non-profit, Filigran gGmbH, and a construction-supplies maker, Filigran Trägersysteme). The group's entities are Filigran SAS (Paris, parent), Filigran Inc. (Dover, Delaware), and subsidiaries in Sydney and Singapore. A Germany-based engineer would almost certainly be employed through an Employer of Record (not confirmed which provider), not by Filigran directly.
> 2. **No office anywhere, including Munich.** Filigran is fully remote. Even the Paris head office is a domiciliation address (HelloDom, 66 Avenue des Champs-Élysées) since June 2025.
> 3. **Not profitable.** VC-backed scale-up (>$100M raised in three years) growing headcount ~90% per year. Only 2022 accounts are public (small profit, before any fundraising).
>
> Full report follows for completeness. Note that, unlike most EOR-only companies, Filigran is otherwise a strong technical and product fit, so these blockers are worth weighing rather than treating as automatic exclusions.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | Legal entity created 18 June 2021 (SIREN 901 384 479); company launched September 2022 (4 years) |
| Employees | 200+ (company timeline, March 2026); ~230 (IT Reseller, April 2026); 281 (matcha.fm, Nov 2026). Engineering ~60-80 (postings say "60+ engineers" and "~80 engineers") |
| Revenue | Not disclosed. Estimates: ~$19.7M 2025 (GetLatka, modelled); $38.5M 2026 (Dealroom, unsourced). Company: "90% growth in 2025", North American ARR "nearly 4x" YoY to March 2026, 119% net revenue retention |
| Profitability | Last public accounts (2022, pre-funding): net profit €849K, cash €626K. Later accounts filed confidential. Hypergrowth, VC-funded - **FAIL** (not demonstrably profitable) |
| Ownership | Private, VC-backed (Eurazeo, Insight Partners, Accel, Moonfire, T.Capital / Deutsche Telekom, Motier, Kima) |
| Software-centric | Open-source cybersecurity software vendor (OpenCTI, OpenAEV, OpenCRQ, XTM One); revenue from Enterprise Editions, SaaS hosting, support and training - **PASS** |

### Key People

- **Samuel Hassine** - co-founder and CEO. Five years at ANSSI (French national cybersecurity agency), latterly Head of Cyber Threat Intelligence; then Tanium. Created OpenCTI as a side project while at ANSSI.
- **Julien Richard** - co-founder and CTO. 20+ years in engineering (VP Engineering at YOOI, Director of Engineering at Axway).
- **Sahar Sabouni** - Chief People Officer.
- **VP of Technology**, a CISO, a Director of Platform Engineering and several Principal/Staff engineers in an "XTM Foundation" group (named in postings).

### Funding History

| Date | Round | Lead | Amount | Valuation |
|---|---|---|---|---|
| Jun 2023 | Seed | Moonfire (with Motier, Kima, Raise Sherpas, Zebox) | €5M | Undisclosed |
| Feb 2024 | Series A | Accel | €15M (~$16M) | Undisclosed |
| Oct 2024 | Series B | Insight Partners | $35M | Undisclosed |
| Oct 2025 | Series C | Eurazeo (with T.Capital, Accel, Insight) | $58M | Undisclosed |
| **Total** | | | **>$100M (~€100M)** | |

The Series C was described in French press as the largest raise in French cybersecurity history at the time. Use of funds: US/EU expansion, a third product (OpenCRQ / OpenGRC) and the AI-native platform XTM One.

### Business Model

Open-core: OpenCTI (threat intelligence platform, ~10K GitHub stars, 6,000+ user organisations) and OpenAEV (breach and attack simulation, formerly OpenBAS) are free to self-host. Filigran monetises via Enterprise Editions, SaaS hosting (including FedRAMP / SecNumCloud-oriented environments), support plans and Filigran Academy training. Named users include the FBI, European Commission, Rivian, Airbus, Thales, Marriott. ~35% of revenue from North America (Sifted, Oct 2025).

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **Filigran SAS** (parent) | RCS Paris 901 384 479, LEI 969500X02THV4GVWDW77 | 66 Avenue des Champs-Élysées, 75008 Paris (domiciliation via HelloDom since 17 June 2025) | "Développement et conception de logiciels informatiques" (NAF 62.01Z, computer programming) |
| **Filigran Inc.** | Delaware | Dover, DE, USA | US subsidiary (listed as HQ on the GPTW profile) |
| Sydney and Singapore subsidiaries | n/a | n/a | Regional sales/support |
| **Germany** | **None found** | - | - |

**Verification:** NorthData search for "Filigran" (method: CDP browser) returns Filigran SAS (Paris) and no German Filigran software entity. A web search for a Filigran GmbH or German subsidiary found nothing. The April 2026 DACH market entry (IT Reseller / CRN) is a **sales** push led by a Channel Director working with partners Bechtle and Cancom, with no mention of a German company. Current German-eligible postings (Principal SWE XTM One, Senior SWE AI-Native Engineering, Staff AppSec) are "Remote" with Germany as one of several countries; the legal employer is not named. matcha.fm lists the legal entities as Paris, Delaware, Sydney and Singapore only.

Conclusion: German hires are almost certainly employed via an EOR (provider not identified). The French parent's corporate purpose is genuine software development, so engineering is real, but there is no local employing entity.

**Verdict:** **FAIL** (no German entity; EOR employment presumed, provider and contract terms unverified)

---

## Section 3: Office Location

- **Office address:** None. Filigran is "fully remote" ("We're a fast-growing, global, and fully remote company", careers page). The registered Paris seat is a domiciliation service address (Pappers: "Domiciliation : HelloDom"), geocoded via Nominatim to 66 Avenue des Champs-Élysées, Quartier du Faubourg-du-Roule, Paris 8e (48.8708, 2.3054). There is no Munich or German office.
- **Nearest public transport:** Not applicable (no office). The Overpass query for the Paris address timed out; not retried since it has no bearing on a Munich-based remote role.
- **Work model:** Fully remote, async-first, teams across EMEA, North America and APJ. Two in-person gatherings per year (one global get-together, e.g. 220 people in Barcelona in March 2026, and one team get-together). Remote eligibility is country-restricted per posting: the current German-eligible engineering roles list France, Germany, Italy, Portugal, Spain and the UK (plus Belgium, Netherlands, Sweden for AppSec). Some roles (Senior Platform Engineer, Senior SWE OpenCRQ) are France-only.

---

## Section 4: Reviews

**GPTW:** **Certified** (August 2026) in the US, France and Australia. 83% say it is a great place to work (vs 57% US benchmark); 96% "management hires people who fit in well", 92% "I am able to take time off when I think it's necessary", 92% "people avoid politicking and backstabbing". No Germany-specific certification (no German entity).

#### Glassdoor

Retrieved via CDP browser (glassdoor.de redirect; country and language filters applied via URL). Profile: 4.5, ~20-21 reviews (company FAQ says "basierend auf 20 anonymen Bewertungen"; 7 English, 13 French).

| Metric | Global | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | 4.5 (~20 reviews) | n/a (0 reviews) | n/a (0 reviews) | ~4.8 (5 visible reviews, computed manually; no Glassdoor filter result) |
| **WLB** | 4.5 | n/a | n/a | n/a |
| **Culture & Values** | 4.7 | n/a | n/a | n/a |
| **Comp & Benefits** | 4.3 | n/a | n/a | n/a |
| **Career Opportunities** | 4.4 | n/a | n/a | n/a |
| **Senior Management** | 4.4 | n/a | n/a | n/a |
| **Diversity & Inclusion** | 4.8 | n/a | n/a | n/a |
| **% Recommend** | 87% | n/a | n/a | n/a |
| **CEO Approval** | 100% (Samuel Hassine) | n/a | n/a | n/a |
| **Business Outlook** | 91% positive | n/a | n/a | n/a |

Sub-scores were displayed on the English-language view but match the company-wide headline figures (4.5 / 87% / 91%), so they are treated as global. With ~20 reviews, all scores are **directional only**. Germany and Munich have zero reviews.

#### Kununu

No Filigran (cybersecurity) profile. Searched `kununu.com/de/search?q=Filigran` (CDP): results are only Filigran Trägersysteme GmbH & Co. KG (Leese / Coswig, construction industry, 2.4-2.5) and FILIGRAN C.E.E. GmbH, all unrelated. `kununu.com/de/filigran` does not resolve to a company profile.
- **Overall score:** n/a
- **Recommendation rate:** n/a
- **Total reviews:** 0
- **Kununu Top Company:** NO (no profile). GPTW certification substitutes as the positive signal.

#### Blind / Teamblind

`teamblind.com/company/Filigran` returns "Page not found". No coverage.

#### Review Themes (2025-2026)

**Positives:**
- **Full remote done well**, the dominant theme: "Full remote done the right way, with highly skilled people. There's a lot to learn every day and that's thrilling!" (Glassdoor, Feb 2025, current Senior Platform Engineer, <1 year); "The Full Remote is a HUGE avantage here, such as values of the company" (Glassdoor, Mar 2026, current Software Engineer I, Paris, 3+ years); "Full remote Confiance dans les employés" (Glassdoor, Jan 2026, current Software Engineer I).
- **Strong product and technical leadership**: "CEO/CTO approval with a technical given direction that relies on strong seniority in their field (CTI)... strong technicality of the product and teams, pretty good work atmosphere" (Glassdoor, Mar 2026, former Platform Engineer Manager, Lyon, <1 year).
- **Atmosphere and interesting work**: "full remote - projet intéressant - bonne mentalité et bonne ambiance" (Glassdoor, Dec 2025, current Software Engineer).
- **Momentum**: "I am amazed by how quickly Filigran is moving... while keeping its opensource DNA and culture" (Glassdoor, Jul 2025, current Senior Account Executive, 1+ year).

**Negatives:**
- **High, uneven pace and expectations**: "Attente parfois très élevée, besoin d'aller toujours plus vite" (Glassdoor, Mar 2026, current Senior Developer, 1+ year); "pace of work is pretty high but also uneven" (former Platform Engineer Manager, above).
- **Scaling pains: inner circle, information flow**: "as a new joiner you will feel an inner circle of 60/70 people who know each other very well... communication and information sharing is not explicitly/consciously done and you will sometimes learn about things with a lag of a few days or weeks" (Glassdoor, Mar 2026, former Platform Engineer Manager, Lyon, <1 year).
- **Uneven management and pay**: "management skills of VPs/EM is very uneven between teams (micro-management, no clear expectations for role, very uneven pay for same seniority level within the same team (15k difference))... I've seen a lot of come and go in my 6 months over there (even for C-level where somebody stayed for a month)" (same reviewer).
- **French culture and language gaps**: "very french culture with strong hierarchy (could depend on the team), top down culture... very uneven english speaking capacities within teams" (same reviewer). Corroborated by an interview review: "They wanted to make their team 'international' but many people don't speak English, just French... they asked me how I would manage a team where 3 people don't speak English" (Glassdoor interview, Dec 2025, anonymous Engineering Manager candidate, no offer).
- **Evaluation and role industrialisation**: "Grosse industrialisation des postes en cours et difficile d'être évalué de manière objective..." (Glassdoor, Jan 2026, current Software Engineer I).

Overlap with hard red flags: communication breakdown (one detailed review), uneven pace (WLB-adjacent). No reports of layoffs, surveillance or unpaid overtime.

#### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | Not found. CEO approval 100%; founders praised. One former manager reports "micro-management" in some teams and uneven VP/EM skills. |
| 24/7 Work Expectation | Not found for product engineering. Platform/SRE has a compensated on-call rotation. Time-zone spread acknowledged ("Time zone differences can be a challenge, but the flexibility helps mitigate this", Glassdoor, Feb 2025, current Senior Customer Success Engineer, Sydney). |
| Internal Surveillance | Not found. |
| Fear-driven Management | Not found. "Top down culture... strong hierarchy (could depend on the team)" (former Platform Engineer Manager, Mar 2026). |
| Communication Breakdown | **Moderate signal**: info lag of "days or weeks", multiple channels (Gather/Teams/email), closed circles (former Platform Engineer Manager, Mar 2026). Interview process for an EM role described as "chaotic" with no-shows and no final answer (Dec 2025). |
| Unpaid Overtime | Not found. |
| Silent Firings | Not found. "A lot of come and go" in a six-month window, including a C-level departure after a month (single source). |
| Work-Life Balance issues | Mild: WLB 4.5; "need to always go faster" and high expectations mentioned by two reviewers. |

**Risk level: LOW to MODERATE.** No systemic toxicity; the negatives are (c) localised, team-dependent scaling dysfunction typical of a startup tripling headcount in 18 months, concentrated in one detailed former-manager review. The French-language undercurrent matters more than management style for a German-based hire.

---

## Section 5: Compensation

#### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| Glassdoor (Paris) | Senior Software Engineer | ~€62-82K | n/a | n/a | ~€62-82K | 3 |
| Glassdoor (Paris) | Senior Software Engineer (typo variant) | ~€67-72K | n/a | n/a | ~€67-72K | 1 |
| Glassdoor (Paris) | Senior Platform Engineer | ~€65-71K | n/a | n/a | ~€65-71K | 1 |
| Glassdoor (Paris) | Data Engineer | ~€63-68K | n/a | n/a | ~€63-68K | 1 |
| Glassdoor (Paris) | Engineering Manager | ~€48-52K | n/a | n/a | ~€48-52K | 1 |
| levels.fyi | any | no data | | | | 0 |
| Job postings | all | not disclosed ("Competitive compensation + equity") | | | | - |

No Germany or Munich data. Paris senior SWE figures (~€62-82K) are French scale-up levels. A former manager reports pay differences of ~€15K for the same seniority within one team. Munich market reference used across these reports: median senior SWE ~€79K, with large profitable corporates in the ~€85-110K range for senior/staff and higher at the 75th/90th percentile. Principal/Staff postings at Filigran may sit above the Paris senior band, but there is no evidence.

#### Equity / Stock

Equity "in every country and every function" ("everyone shares in our success"). As a French SAS, likely BSPCE options (not confirmed); for German EOR hires, the instrument and tax treatment are unknown. Private, no disclosed valuation, no liquidity before an exit; treat as lottery-ticket value.

#### Verdict

Paris senior SWE pay (~€62-82K) is **below** the average bracket of large, profitable Munich corporates. Pay for a Germany-based principal/staff hire via EOR is undisclosed.

**BELOW / UNVERIFIED** for a Munich hire; ask for the band up front.

---

## Section 6: AI/ML & Tech Stack

#### AI Strategy

Genuine applied-LLM investment, not marketing:
- **XTM One** (released June 2026): "AI platform for threat informed defense", creates and runs cybersecurity expert agents across OpenCTI, OpenAEV, OpenGRC. The Principal posting names agent runtime and orchestration, tool and MCP integrations, data/context layers, RAG and vector search, evaluations and guardrails, "LLM latency and inference cost", SaaS plus on-prem from day one.
- **OpenCRQ**: probabilistic cyber-risk quantification, with "the agentic surface" (contracts used by XTM One agents) as an explicit squad responsibility.
- **AI-native engineering**: a dedicated Senior SWE role to define tooling and practices for ~80 engineers (coding agents, MCP servers, AI in CI pipelines); the platform team "has made AI agents a core part of how it works".
- Public repos: `xtm-mcp` (Python MCP server), `xtm-browser-extension`.

This is applied LLM/agent engineering in a product, not ML model training or MLOps.

#### Tech Stack

Sources: current Ashby postings (API `api.ashbyhq.com/posting-api/job-board/filigran`, via curl), GitHub orgs OpenCTI-Platform, OpenAEV-Platform and FiligranHQ (GitHub API), matcha.fm profile.

| Category | Technologies |
|---|---|
| **Primary language(s)** | TypeScript / Node.js (OpenCTI core: 36M bytes TS vs 2.8M Python; OpenCRQ "TypeScript end to end"); Python (connectors: 260+ in OpenCTI-Platform/connectors, client-python, XTM One, MCP); Java (OpenAEV backend); Rust (xtm-composer) |
| **AI/ML** | LLM agents, tool calling, MCP, RAG, vector search, evaluations (XTM One); coding agents in engineering workflow |
| **Cloud** | Own bare-metal Kubernetes cloud (OVH Ansible module in GitHub), AWS, Azure, GCP; sovereign/regulated environments (FedRAMP, SecNumCloud) |
| **Infrastructure** | Kubernetes, Helm, Ansible, Terraform, GitHub Actions, Docker, Cilium; OpenTelemetry, Prometheus, Grafana, continuous profiling |
| **Data** | Elasticsearch/OpenSearch, PostgreSQL (Drizzle ORM), Redis, RabbitMQ, S3-compatible storage (MinIO); STIX 2.1, OCSF, MITRE ATT&CK |
| **Other** | React, Vite, TanStack Router, Fastify, tRPC, GraphQL (OpenCTI API), monorepos |

**Summary:** TypeScript-centric full-stack engineering (Node.js/React, GraphQL, PostgreSQL/Elasticsearch) with a substantial Python layer for connectors, MCP and the XTM One agent platform, and Java for OpenAEV. Applied LLM-agent product engineering on a mix of own bare-metal Kubernetes and public clouds, shipped both as SaaS and on-prem. Production engineering, not research.

---

## Section 7: Language

- All postings are in English; "Fluent English is required" / "Full professional proficiency in English" / "Excellent written communication in English".
- None of the German-eligible engineering postings require French. French appears as a plus for sales and competitive-intelligence roles, and "Fluent in French" is a nice-to-have on the France-only Senior Platform Engineer role.
- **But**: the company is French-founded, ~60-70 early employees form an "inner circle", and two independent Glassdoor sources describe "very uneven english speaking capacities within teams" and team members who "don't speak English, just French".

**Verdict:** **CONDITIONAL.** English is the official working language and no German-eligible role lists French; in practice, some teams lean French. Ask which language the target squad actually uses day to day.

---

## Section 8: Stability

#### Financial Position

- Only public accounts: 2022 (net result +€849K, equity €864K, cash €626K), pre-funding. 2023+ accounts filed with confidentiality (Pappers).
- Revenue growth: +90% in 2025; NA ARR ~4x YoY to March 2026; NRR 119%; partner-attached revenue +200%.
- Funding: >$100M raised, $58M of it in October 2025.
- Recognition: French Tech 120 (2025), IT-Harvest Cyber 150 top-30 two years running, G2 Leader (Winter 2026).

#### Financial Runway

No cash figure after 2022 is public; no analyst runway estimate found. Bottom-up model (all estimates, observed 2026-11-13):

| Cost line | Annual estimate |
|---|---|
| Staff (~250 avg in 2026 × ~€105K fully-loaded, mix of France, US, UK, APJ) | ~€26M |
| Cloud/hosting (own bare metal + public cloud SaaS) | ~€2-3M |
| Sales & marketing programmes, events, partner programmes | ~€4-5M |
| Offsites (2/yr), travel, G&A, EOR fees, tooling | ~€3M |
| **Total gross burn** | **~€35-37M/year** |

| Revenue source | Est. annual inflow |
|---|---|
| Enterprise Edition / SaaS / support / training (2026, assuming ~$20M in 2025 grown 50-90%) | ~€25-33M/year |
| **Total revenue offset** | **~€25-33M/year** |

Cash estimate: Series C ~€50M (Oct 2025) plus an assumed ~€10-15M remainder of the Series B, minus ~13 months of net burn → **~€45-55M** (estimate, no filing).

| Scenario | Net burn | Cash at hand | Runway | Next round needed by |
|---|---|---|---|---|
| Optimistic | ~€4M/year | ~€55M | >10 years (near break-even) | Optional |
| Base case | ~€10M/year | ~€50M | ~5 years | ~2030 (likely raised earlier for growth) |
| Stress (growth stalls, hiring continues) | ~€20M/year | ~€45M | ~2.2 years | ~2028-2029 |

Runway looks comfortable; strong NRR and open-source adoption reduce risk. The main uncertainty is the undisclosed revenue base.

#### Layoffs

No layoffs found (web search, TrueUp-style queries, French press). Headcount grew from ~15 (early 2023) to ~230-280 (2026). North American team reported zero voluntary attrition in the year to March 2026. One reviewer notes high turnover in a six-month window in 2025-2026.

#### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | **NO** (no German entity; an EOR's own works council, if any, would not cover Filigran's management practices) | NorthData, careers page |
| Collective agreement | **NONE for Germany.** French SAS applies the Syntec agreement (IDCC 1486, "Bureaux d'études techniques...") to French staff | Pappers: "Convention collective : ... IDCC 1486" |
| French CSE (works council equivalent) | UNKNOWN; mandatory with full powers at 50+ French employees, which Filigran exceeds | French labour code; no public evidence found |
| European works council | N/A (below thresholds) | - |
| Conflict signals | None found | - |

**Verdict:** **CAUTION.** Strong funding and growth, no layoffs, but EOR employment in Germany with no works council and no collective agreement leaves a German hire with the least structural protection of any arrangement.

---

## Section 9: Regulated Industry

Cybersecurity software vendor, not a regulated entity. Compliance work is customer-driven: SOC 2 Type 2, ISO 27001:2022, GDPR, and platform hardening for FedRAMP and SecNumCloud environments (Platform and AppSec postings). Product engineering impact: secure SDLC (SAST/SCA, SBOMs, signed releases), but no formal safety cases or regulator approval of releases.

**Verdict:** **PASS** (low burden for product engineering; compliance concentrated in platform/security teams)

---

## Section 10: On-Call

- **Senior Platform Engineer** (France-only): "On-call: a shared rotation of around one daytime shift and one night shift every two weeks, plus one weekend every six weeks or so. Night and weekend on-call is compensated."
- **Senior SWE OpenCRQ, Senior SWE AI-Native, Principal SWE XTM One, Staff AppSec**: no on-call mention. The Principal role expects "production operations, monitoring, incident response" familiarity, and the AppSec role owns "the product side of security incidents".
- Product is SaaS, so product engineers may be escalation points even without a formal rotation.

**Verdict:** **CAUTION (team-dependent).** Platform carries on-call; product/AI engineering roles do not mention it. Confirm escalation expectations for the specific squad.

---

## Section 11: Interview Process

Glassdoor (all languages, CDP browser):

| Metric | Value |
|---|---|
| Difficulty | 2.3 / 5 |
| Positive experience | 33% (33% negative, 3 interviews) |
| Average duration | ~4 weeks to 2 months |
| Rounds | ~4 (EM candidate) |

Steps reported: online application (67%) or agency (33%), recruiter screen on Ashby with scorecards, then several conversational rounds with team members across functions. Reviews describe interviews as "more like a conversation rather than fixed questions" and "conversational". Negatives: a "chaotic" EM process with a no-show, a late interviewer and no final answer after four rounds (Dec 2025); a designer candidate who had to chase for feedback and never heard back (Mar 2025). Positive: a smooth, multi-round PMM process ending in an offer (Feb 2025, London).

Experience/design-focused, not LeetCode-heavy (no algorithmic questions reported). Sample is three interviews, none for software engineering.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | PASS: open-core cybersecurity product company |
| Not consulting | PASS: product revenue (EE, SaaS, support); "ad-hoc development services" mentioned historically on Glassdoor but marginal |
| Profitable | FAIL: VC-funded hypergrowth, no recent accounts |
| Employee count | ~230-280 globally; ~60-80 engineers |
| English-speaking | CONDITIONAL: English official, French undercurrent in some teams |
| Local entity + engineering contracts | **FAIL**: no German entity, EOR presumed |
| Location / work model | Fully remote, Germany eligible for current SWE roles; no office; 2 offsites/year |
| Glassdoor | 4.5 (~20 reviews, directional), 87% recommend, 100% CEO; 0 Germany/Munich reviews |
| Kununu | No profile |
| Salary | BELOW / UNVERIFIED: Paris senior SWE ~€62-82K; German band undisclosed |
| AI/ML content | Strong: XTM One agent platform, MCP, RAG, evals, AI-native engineering role |
| Computer-language/Tech-stack | TypeScript-centric with significant Python (connectors, XTM One, MCP) and Java (OpenAEV) |
| No on-call | CAUTION: platform yes, product SWE roles not mentioned |
| WLB / Stability | WLB 4.5; fast pace; ~€50M estimated cash, no layoffs |
| Works council / collective agreement | NONE in Germany (Syntec applies in France only) |
| Regulated industry | PASS |
| Review themes | Full remote praised; scaling pains, uneven management/pay, French culture |
| GPTW | Certified Aug 2026 (US, France, Australia), 83% |
| Open source | Core products public on GitHub (OpenCTI ~10K stars): work can be inspected before applying |

---

## Section 13: Verdict

**Monitor; apply only if EOR employment is acceptable and a Germany salary band clears the Munich market.**

**Strengths:** A real product company with fast growth (+90% in 2025, 119% NRR), heavy funding (>$100M, last round October 2025) and a widely used open-source core. AI work is concrete: XTM One is an agent platform (runtime, MCP, RAG, evaluations, SaaS plus on-prem) and the open Principal and Senior roles centre on it, with Python and TypeScript as the core languages. Fully remote with Germany explicitly eligible, GPTW-certified, CEO approval 100%, no layoffs, and product engineering roles with no on-call mentioned.

**Hard blockers:**
1. **No local commercial entity.** There is no Filigran company in Germany; legal entities exist only in France, the US (Delaware), Australia and Singapore. A Munich-based engineer would be employed through an EOR, with no works council, no collective agreement and a contract whose terms Filigran does not control directly. German EOR arrangements also carry legal friction (AÜG licensing, 18-month limits at some providers).
2. **No office in Munich (or anywhere).** Fully remote is the operating model; even Paris is a mailbox address.
3. **Not profitable.** Hypergrowth funded by venture capital; the last public accounts are from 2022. Runway looks healthy (~5 years in the base case), but profitability is not established.

**Secondary concerns:**
- **Compensation:** the only data is Paris senior SWE at ~€62-82K, below the Munich large-corporate bracket; ~€15K intra-team pay spread reported; equity value illiquid.
- **Language and culture:** French-founded with an early "inner circle" of 60-70 people; two independent sources report teams with limited English and a top-down style in places.
- **Scaling pains:** communication lags, uneven management quality, high turnover reported in one detailed review; chaotic interview logistics in two of three interview reports.
- **Thin review base:** ~20 Glassdoor reviews, none from Germany, no Kununu or Blind coverage.

**Recommendation:** Do not treat Filigran as a standard target, because it fails the local-entity criterion. If the remote-EOR model is acceptable for an exceptionally good role match (the Principal SWE XTM One or Senior SWE AI-Native Engineering postings, both Germany-eligible), verify early with the recruiter: (1) the named German employer (EOR provider) and contract type (permanent, any AÜG time limits); (2) the salary band for Germany and the equity instrument for EOR employees; (3) the working language inside the target squad; (4) whether product engineers take part in any incident escalation; (5) whether a German entity is planned as part of the April 2026 DACH expansion.

---

## Sources

- [Filigran - Our Story](https://filigran.io/our-story/) (CDP browser)
- [Filigran - Careers](https://filigran.io/careers/) (CDP browser)
- [Filigran Ashby job board API](https://api.ashbyhq.com/posting-api/job-board/filigran?includeCompensation=true) (curl)
- [Filigran Series C press release ($58M)](https://filigran.io/press-releases/filigran-announces-a-new-58-million-funding-round-to-accelerate-its-growth-and-international-expansion/)
- [Filigran €5M seed press release](https://filigran.io/press-releases/filigran-5m-seed-funding/)
- [Filigran accelerates US expansion (press release)](https://filigran.io/press-releases/filigran-accelerates-us-expansion)
- [Business Wire: Filigran nearly 4x North American revenue growth (Mar 2026)](https://www.businesswire.com/news/home/20260323540876/en/Filigran-Accelerates-U.S.-Expansion-with-Nearly-4x-North-American-Revenue-Growth-Major-Enterprise-Wins-and-Independent-Recognition-as-a-Top-Cybersecurity-Company)
- [Sifted: Cybersecurity startup Filigran raises $58M](https://sifted.eu/articles/cybersecurity-startup-filigran-raises-58m)
- [SiliconANGLE: Filigran raises $58M](https://siliconangle.com/2025/10/06/filigran-raises-58m-expand-ai-driven-threat-management-platform/)
- [TechCrunch: Filigran secures $35M Series B](https://techcrunch.com/2024/10/27/filigran-secures-35-million-for-its-cybersecurity-threat-management-suite)
- [Siècle Digital: Filigran levée de 58 millions](https://siecledigital.fr/2025/10/06/filigran-la-pepite-francaise-de-la-cybertech-soffre-une-levee-de-58-millions-de-dollars-pour-conquerir-le-monde/)
- [L'Essentiel de l'Eco: Filigran](https://lessentieldeleco.fr/3916-filigran/)
- [Jeantet advises T.Capital on Filigran Series C](https://www.jeantet.fr/en/2025/10/jeantet-advises-t-capital-on-the-eur-58-millions-series-c-fundraising-of-filigran)
- [Fintechnews.ch: Filigran Series C](https://fintechnews.ch/funding/filigran-series-c-funding-cybersecurity-expansion/78579/)
- [Dealroom: Filigran](https://dealroom.co/companies/filigran/)
- [GetLatka: Filigran revenue estimate](https://getlatka.com/companies/filigran.io)
- [matcha.fm: Filigran careers, entities, stack](https://matcha.fm/company/filigran) (CDP browser)
- [IT Reseller: Filigran wagt Markteintritt in der DACH-Region (Apr 2026)](https://www.itreseller.ch/Artikel/105328/Filigran_wagt_Markteintritt_in_der_DACH-Region.html) (CDP browser)
- [NorthData search: Filigran](https://www.northdata.com/Filigran) (CDP browser)
- [Pappers: FILIGRAN SAS 901 384 479](https://www.pappers.fr/entreprise/filigran-901384479) (CDP browser)
- [Recherche d'entreprises API (data.gouv.fr): 901384479](https://recherche-entreprises.api.gouv.fr/search?q=901384479) (curl)
- [Nominatim geocode: 66 Avenue des Champs-Élysées](https://nominatim.openstreetmap.org/search?q=66+Avenue+des+Champs-%C3%89lys%C3%A9es,+75008+Paris&format=json) (curl)
- [Glassdoor: Filigran overview](https://www.glassdoor.de/%C3%9Cberblick/Arbeit-bei-Filigran-EI_IE10182061.11,19.htm) (CDP browser)
- [Glassdoor: Filigran reviews, global English](https://www.glassdoor.de/Bewertungen/Filigran-Bewertungen-E10182061.htm?filter.countryId=0&filter.iso3Language=eng) (CDP browser)
- [Glassdoor: Filigran reviews, global French](https://www.glassdoor.de/Bewertungen/Filigran-Bewertungen-E10182061.htm?filter.countryId=0&filter.iso3Language=fra) (CDP browser)
- [Glassdoor: Filigran reviews, Germany (0)](https://www.glassdoor.de/Bewertungen/Filigran-Bewertungen-E10182061.htm) (CDP browser)
- [Glassdoor: Filigran interviews](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/Filigran-Fragen-im-Vorstellungsgespr%C3%A4ch-E10182061.htm) (CDP browser)
- [Glassdoor: Filigran salaries, Paris](https://www.glassdoor.de/Gehalt/Filigran-Paris-Geh%C3%A4lter-EI_IE10182061.0,8_IL.9,14_IC2881970.htm) (CDP browser)
- [Kununu search: Filigran](https://www.kununu.com/de/search?q=Filigran) (CDP browser)
- [Teamblind: Filigran (not found)](https://www.teamblind.com/company/Filigran) (CDP browser)
- [levels.fyi: Filigran (no data)](https://www.levels.fyi/companies/filigran/salaries) (CDP browser)
- [Great Place to Work: Filigran certified company profile](https://www.greatplacetowork.com/certified-company/110000987) (CDP browser)
- [GitHub: OpenCTI-Platform organisation](https://github.com/OpenCTI-Platform) (GitHub API)
- [GitHub: OpenCTI repository](https://github.com/OpenCTI-Platform/opencti) (GitHub API)
- [GitHub: OpenAEV-Platform/openaev](https://github.com/OpenAEV-Platform/openaev) (GitHub API)
- [GitHub: FiligranHQ organisation](https://github.com/FiligranHQ) (GitHub API)
- [Filigran customer story: Controlware](https://filigran.io/customer-stories/opencti-controlware-scalable-threat-hunting/)
- [Taylor Wessing: 10 pitfalls when using an EOR in Germany](https://www.taylorwessing.com/en/insights-and-events/insights/2022/02/10-pitfalls-when-using-an-eor-in-germany)
- [Omnipresent: Hiring employees in Germany (EOR 18-month limit)](https://help.omnipresent.com/en/articles/10589056-hiring-employees-in-germany-a-comprehensive-guide)
