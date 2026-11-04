# Goldman Sachs - Full Research Report

_Researched: 2026-11-04_

> **Critical Disqualifiers**
> 1. **No software engineering in Munich, and none currently open in Germany.** The Munich site (Maximilianstraße 35, opened 2024) has investment banking, asset management and wealth management teams only. On 2026-11-04 the Goldman careers site listed exactly **one** Munich vacancy (an Investment Banking TMT Analyst) and **six** Frankfurt vacancies (risk, audit, private bank, client relationship, HR recruiter), with **no engineering roles**. LinkedIn shows the same 7 postings. Goldman's engineering hubs in Europe are London, Warsaw and Birmingham. **FAIL**
> 2. **Not software-centric.** Goldman Sachs is an investment bank. Engineering is a large internal function (the "first line of defence" reporting to the COO in the German entity), not the product. **FAIL**
> 3. **Work-life balance is the weakest Glassdoor dimension:** 2.9 globally (20,134 rated reviews), with the 1-2 star bucket the largest group of WLB ratings. Blind WLB is 3.1. Glassdoor software engineers recommend the firm at only 56%. **FAIL against a dependable-WLB requirement**
> 4. **Firm-wide five-day office mandate** (August 2023, described as long-term) and a culture of **rolling, performance-based culls** (annual "strategic resource assessment" of roughly 3-5%, moved to continuous rounds in 2026 under the AI-driven "OneGS 3.0" programme). **FAIL / HIGH CAUTION**
>
> The full report follows for completeness.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 1869 (157 years) |
| Employees | 47,500 globally (end of Q3 2026, SEC 8-K); 48,300 a year earlier. Germany (Goldman Sachs Bank Europe SE, Frankfurt + Munich): **431 FTE** (31 Dec 2025, country-by-country report) |
| Revenue (FY2025) | Net revenues **$58.28B** (+9% YoY); 9M 2026 net revenues $56.24B |
| Profitability | Net earnings **$17.18B** FY2025; $17.55B for 9M 2026; Q3 2026 annualised ROE 18.7% - **PASS** |
| Ownership | Public, NYSE: GS. Wholly owns Goldman Sachs Bank Europe SE (GSBE) |
| Software-centric | Investment banking, markets, asset and wealth management. Software is an internal enabler - **FAIL** |

### Key People

- **David M. Solomon**, Chairman and CEO (Glassdoor CEO approval 67% overall, 56% among software engineers)
- **John Waldron**, President and COO
- **Denis Coleman**, CFO
- **Marco Argenti**, Chief Information Officer (leads the AI programme: GS AI Assistant, Devin pilot)
- **Dr. Wolfgang Fink**, CEO of Goldman Sachs Bank Europe SE (signed the FY2025 German annual accounts)

### Business Model

Three segments: **Global Banking & Markets** (investment banking, FICC, equities; $41.45B of FY2025 net revenues), **Asset & Wealth Management** (~$16.7B), and **Platform Solutions** (consumer cards, being wound down; Q3 2026 net revenues $170M after Apple Card markdowns). Revenue is fees, trading and interest income, not software.

### Software-Centric Assessment

Goldman markets itself as having engineers who "make things possible" and states that "in an era defined by AI, Engineering isn't just central, it's the driving force behind our business". In practice:

- Engineering builds **internal** trading, risk, regulatory-reporting, data and research platforms (SecDB/Slang, Legend, Marquee, GIR tooling). The client-facing software products (Marquee, Transaction Banking) are adjuncts to banking services.
- The German entity's annual report places "Engineering" inside the **first line of defence** reporting to the COO, alongside Controllers and Treasury: a support function in a bank.
- GSBE's average 2025 headcount split was 861 revenue-generating staff vs. 404 support functions; there is no separate engineering line, and no German engineering vacancies exist.

**Verdict:** a technology-heavy bank, not a software company. **FAIL** on the software-centric criterion.

### Consulting-Adjacency Assessment

Not applicable. Goldman does not self-identify as a consultancy, engineers do not bill hours, and engineering titles are bank corporate titles (Analyst, Associate, Vice President, Managing Director). Note that the corporate-title ladder means a senior engineer is hired as **Vice President** and a staff-equivalent as **Executive Director / Managing Director**.

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **Goldman Sachs Bank Europe SE** | HRB 114190, Amtsgericht Frankfurt am Main (EUID DEM1201.HRB114190; previously Goldman Sachs AG, HRB 91313, merged January 2019) | Marienturm, Taunusanlage 9-10, 60329 Frankfurt am Main | "The operation of banking and financial services, with the exception of transactions referred to in Section 1 (1) sentence 2 Nos 1a, 3, 7, 9 and 12 and Section 1 paragraph 1a sentence 2 Nos 1b, 1d, 7, 9, 10 and 12 of the Banking Act. In addition, the company operates payment services within the meaning of the Payment Services Supervision Act." |
| Goldman Sachs Bank Europe SE, Munich office | Branch site of the above (named "Niederlassung in München" in the FY2025 annual report) | Maximilianstraße 35, 80539 München | As above |
| Goldman Sachs Asset Management B.V., German Branch | Branch of a Dutch entity | Maximilianstraße 35, 80539 München | Asset management |

**Verification.** The NorthData entry (retrieved via Chromium over CDP) confirms HRB 114190, the Marienturm address, share capital of €328.6M and the banking-services purpose. Goldman's own Germany page confirms the entity holds a German banking licence, is a member of the Bundesverband deutscher Banken, and that "since 2024" a second German site in Munich hosts "teams from investment banking, asset management and wealth management". The FY2025 German GAAP annual report (Lobbyregister copy, decrypted and read locally) reports 431 FTE for "GSBE Deutschland" (Frankfurt and Munich combined) and 240 FTE in the Warsaw branch.

The registered purpose is **banking**, not software development. Employment in Germany is a direct contract with a licensed bank, not PEO/EOR. However, there is **no evidence of software engineers employed in Germany** beyond the bank's internal first-line engineering function, and no German engineering vacancies at all.

**Verdict:** **PASS with CAUTION** (genuine, large local entity with direct contracts, but its purpose and staffing are banking, and the Munich branch has no engineering).

---

## Section 3: Office Location

- **Office address (Munich):** Maximilianstraße 35, 80539 München, Graggenauerviertel, Altstadt-Lehel. Confirmed from the Goldman Sachs "Locations" page (both Goldman Sachs Bank Europe and Goldman Sachs Asset Management B.V. German Branch, phone +49 89 8 393 29000) and geocoded with Nominatim (48.13913, 11.58379; building tagged "office").
- **German HQ:** Marienturm, Taunusanlage 9-10, 60329 Frankfurt am Main.
- **Nearest public transport (Overpass, 700 m radius, straight-line distances):**
  - **Kammerspiele** tram stop, ~90 m (tram 19)
  - **Lehel** U-Bahn station, ~310 m (U4, U5; Lehel tram stop ~360 m, tram 16)
  - **Maxmonument** tram/bus stop, ~330-390 m (tram 16, 19)
  - **Nationaltheater** tram stop, ~370 m (tram 19)
  - **Isartor** S-Bahn station, ~550 m (S-Bahn trunk line)
  - **Marienplatz** U-/S-Bahn station, ~570 m (U3, U6, S-Bahn trunk line)
  - **Odeonsplatz** U-Bahn station, ~630 m (U3, U4, U5, U6)
- **Work model:** **On-site, five days a week.** Goldman asked all staff in August 2023 to return to the office five days a week and described it as a long-term policy (Fortune, Feb 2024). Frankfurt staff were already called back to full-time office work from March 2022. Recent German Glassdoor reviews confirm it: "Forget about any remote work" (Analyst, Frankfurt, May 2025); "Es sollte Maßnahmen zu einer 100 Prozent Remote Tätigkeit geben" (Frankfurt, 2024). A Blind review from November 2026 cites a "Five day in office mandate". No fully-remote option for Germany exists.

---

## Section 4: Reviews

### Great Place to Work

**No GPTW Germany certification found** for Goldman Sachs Bank Europe SE or any German Goldman entity. The only GPTW-related signal is the US parent's long-running presence on the Fortune/GPTW "100 Best Companies to Work For" list, which is a US list and says nothing about the German entity. **Absent signal for Germany.**

### Glassdoor

Retrieved via **Chromium over CDP** (logged-in session) from glassdoor.de, employer E2800, reading the filtered `ratings` block of the page data.

| Metric | Global | Germany | Munich | Software Engineers (global, title "Software Engineer") |
|---|---|---|---|---|
| **Overall** | 3.7 (20,134 rated reviews; 24,402 total) | 4.1 (52 rated reviews) | 5.0 (1 review) | 3.7 (536 reviews) |
| **WLB** | 2.9 | 3.6 | 3.0 | 3.3 |
| **Culture & Values** | 3.6 | 4.2 | 5.0 | 3.4 |
| **Comp & Benefits** | 3.6 | 4.5 | 5.0 | 3.3 |
| **Career Opportunities** | 3.9 | 4.4 | 5.0 | 3.7 |
| **Senior Management** | 3.3 | 4.1 | 4.0 | 3.2 |
| **Diversity & Inclusion** | 4.0 | 4.2 | n/a | 4.0 |
| **% Recommend** | 67% | 73% | 100% | 56% |
| **CEO Approval** | 67% | 94% | n/a | 56% |
| **Business Outlook** | 68% positive | 79% positive | 100% | 65% positive |

Notes and caveats:

- **Germany (52 reviews)** is directional only, and almost all of it is **Frankfurt investment banking, PWM and analyst/intern** reviews, not engineering. A Germany + "Software Engineer" filter returns **1** review (overall 3.0).
- **Munich has a single review**: no usable signal.
- The global WLB distribution is bottom-heavy: 1,191 one-star and 1,103 two-star WLB ratings vs. 1,030 five-star.
- Peer context (same page): J.P. Morgan 3.9, Morgan Stanley 3.9, Bank of America 3.8, Citi 3.6.
- Most recent software-engineer reviews (Sep-Oct 2026): "toxic environment with consistent micromanagement" (New York, 1 star); "boring work" (Warsaw, 2 stars); "Low growth, low total compensation" (Dallas, 4 stars); "Minimal room to grow technically" (Singapore); "Not the most tech-focused. Tech is secondary" (Bengaluru).

### Kununu

Plain curl returned **HTTP 405** for all slugs; the Kununu search and profile were read via **Chromium over CDP**. Slug: `goldman-sachs1` (profile "Goldman Sachs AG", Frankfurt am Main; "nicht auf kununu aktiv", i.e. no employer-managed profile).

- **Overall score:** 3.7 / 5.0 (below the Kununu banking-sector average of 3.8)
- **Recommendation rate (Weiterempfehlung):** 87% (last 2 years); 72% across all reviews
- **Total reviews:** 37 (employee reviews: 32, since 2008)
- **Sub-scores:** Karriere & Gehalt 4.2, Unternehmenskultur 3.4, Arbeitsumgebung 3.5, Vielfalt 3.7
- **Kununu Top Company:** **NO** (no Top Company seal on the profile; score below threshold)
- A second, unrelated stub profile `goldman-sachs-bank` (2 reviews, Münster) was ignored.

Kununu review text: "Lange Arbeitszeiten meist mit Überstunden", "Überdurchschnittlich hohes Gehalt mit mäßigen Sozialleistungen", "Die Kollegen sind einander relativ egal", "Flexiblere Arbeitszeiten, weniger Überstunden" (Finanzen/Controlling, Frankfurt). The latest review (November 2026) is placeholder text with no content.

### Blind / Teamblind

Retrieved via **Chromium over CDP**. **3.4 / 5 (1,768 reviews)**: Career Growth 3.4, Work Life Balance 3.0, Compensation/Benefits 3.1, Company Culture 3.2, Management 3.0. Recent reviews: "Five day in office mandate. Very long working hours, and you're expected to work weekends and even during vacation... Layoffs happen on an ad hoc basis, which creates constant uncertainty" (Associate Auditor, 2 Nov 2026); "No opportunities to learn. Micromanagement. Toxic culture. They mostly work on the legacy tech stack" (Associate Software Engineer, 30 Oct 2026). Blind skews US-heavy; no Germany-specific reviews.

### Review Themes (2024-2026)

**Positives:**

- **Pay, especially the bonus:** "Super Gehalt, super Benefit Package" (Frankfurt, Oct 2026); "Money is good, but mostly because of the annual bonus" (Frankfurt, 2025); Kununu Karriere & Gehalt 4.2.
- **Calibre of colleagues and learning curve:** "surrounded by the brightest and most hard working people", "Steep learning curve", "Incredible people who are hardworking" (Frankfurt, 2024-2025).
- **Brand and exit options:** "gutbezahlter Job mit vielen Exitmöglichkeiten"; "new technology that make your resume strong".
- **Career Opportunities** is the highest-rated dimension globally (3.9) after D&I.
- Some engineering teams report good WLB (Dallas and Singapore software engineers, 5-star WLB, Oct 2026), so WLB varies by team.

**Negatives:**

- **Long hours and overtime** across platforms and years: "Work on Sunday nearly unavoidable" (IBD intern, Frankfurt); "Lange Arbeitszeiten"; "poor work life balance, Überstunden"; Blind "12 hour days, seven days a week, for over a month". Overlaps the **WLB** and **unpaid overtime** red flags.
- **Rigid, office-bound, hierarchical culture:** "Very stale structure, old management, extremely not flexible... Forget about any remote work"; "Typical american corporation". Overlaps the **five-day office** constraint.
- **Toxic individuals and micromanagement:** "A lot of credit is given to incapable and clueless EDs. You would have to navigate a lot of toxic personalities" (Jan 2026); "toxic environment with consistent micromanagement" (SWE, Oct 2026); Blind "Toxic culture".
- **Engineering as second-class / legacy stack:** "Tech is secondary"; "Minimal room to grow technically"; "legacy tech stack"; "boring work".
- **Job insecurity from rolling culls:** "Layoffs happen on an ad hoc basis" (Blind, Nov 2026), consistent with press on the annual performance-based cuts. Overlaps the **layoffs / silent firings** red flag.

### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | Localized, recurring. "navigate a lot of toxic personalities", "incapable and clueless EDs" (Glassdoor, Jan 2026); "toxic environment with consistent micromanagement" (SWE, Oct 2026); Blind Management 3.0. Senior management itself is sometimes praised ("Senior management is impressive"). |
| 24/7 Work Expectation | Present in banking divisions: "expected to work weekends and even during vacation" (Blind, Nov 2026), "Work on Sunday nearly unavoidable" (Frankfurt). Engineering production-support roles describe "24*7 rotational shift (weekend on-call support as necessary)". |
| Internal Surveillance | Regulated-bank monitoring of communications and devices is standard (MiFID II record-keeping); no reports of performance surveillance specifically. Moderate by industry norm. |
| Fear-driven Management | Moderate. Annual 3-5% performance culls and the 2026 shift to "rolling" cuts tied to tightened AI-era performance criteria create a fear signal; "constant uncertainty" (Blind). |
| Communication Breakdown | Some signals in hiring ("Interviewers didn't see the resume", "interviewers didn't even join the meeting") and "Scope is rarely defined upfront"; not a dominant theme. |
| Unpaid Overtime | Present. Overtime is expected and compensated via discretionary bonus rather than paid: "You have to overwork yourself to get a good bonus"; Kununu "Lange Arbeitszeiten meist mit Überstunden". |
| Silent Firings | **Elevated.** The annual "strategic resource assessment" culls the bottom 3-5% by performance rating; in 2026 these became continuous rounds across divisions (Reuters/Nasdaq). This is managed-out attrition by design. |
| Work-Life Balance issues | **Systemic.** WLB is the lowest global sub-score (2.9); Blind 3.0; varies by team in engineering (SWE WLB 3.3). |

**Risk level: MODERATE to HIGH.** The pattern is (a) a systemic, institutional high-intensity culture (long hours, five-day office, forced-ranking culls) rather than one abusive leader, combined with (c) localized toxic managers. It is more than (b) ordinary large-company bureaucracy: the performance-cull mechanism is a deliberate, recurring feature.

---

## Section 5: Compensation

### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| levels.fyi (Germany) | Software Engineer | locked | locked | locked | **UNAVAILABLE** ("We only need 4 more Software Engineer submissions... to unlock") | <4 |
| Job posting (Frankfurt) | Engineering Data Governance Officer, Vice President | €100K-125K (advertised range, via job board) | n/a | discretionary | n/a | 1 |
| levels.fyi (Warsaw) | Software Engineer, Vice President | n/a | n/a | n/a | PLN 333K (~€78K) median TC | n/a |
| levels.fyi (Warsaw) | Software Engineer, Associate | n/a | n/a | n/a | PLN 254K (~€59K) | n/a |
| levels.fyi (US) | Software Engineer, Vice President | n/a | n/a | n/a | $218K (~€190K) median TC; overall median $131K; 3,365 submissions | 3,365 |
| Glassdoor (Germany) | Software Engineer | UNAVAILABLE (salary page did not render via CDP; no Germany engineering salaries surfaced) | | | | 0 |

Notes:

- The levels.fyi "Greater London" summary returned **identical** medians to the US page, so it appears to fall back to US data; it was not used.
- Munich market reference percentiles (levels.fyi Munich metro page) returned **404** this session; **UNVERIFIED**.
- Goldman pay is base plus a **discretionary year-end bonus** that reviewers describe as the main lever ("Money is good, but mostly because of the annual bonus").

### Equity / Stock

Public company (NYSE: GS). levels.fyi reports RSUs on a **3-year vesting schedule** (33% per year). In practice, stock is part of the year-end discretionary award and becomes material mainly from Vice President upward, partly as deferred, restricted stock. There is no ESPP-style broad grant comparable to big tech; the bulk of variable pay is cash bonus.

### Verdict

The only German data point (a Frankfurt VP posting at €100-125K base) is in line with the base bracket of large, profitable Munich corporations for senior engineers, with a discretionary bonus on top. No German engineering TC data exists, and no Munich engineering roles exist to benchmark. **UNVERIFIED** (likely COMPARABLE on base at VP level).

---

## Section 6: AI/ML & Tech Stack

### AI Strategy

Genuine and large-scale, but internal-productivity focused:

- **GS AI Assistant**, rolled out firm-wide in June 2025 after a 10,000-employee pilot; it can call several approved LLMs (CIO Marco Argenti memo).
- **Devin (Cognition)** pilot as an "AI software engineer" for routine work such as legacy-code updates, "hundreds of Devins... might go into the thousands", supervised by human developers (2025).
- **OneGS 3.0** (late 2025 memo from Solomon, Waldron, Coleman): AI-driven re-engineering of client onboarding, lending, regulatory reporting and vendor management, explicitly paired with "limited" job cuts and constrained headcount growth.
- Job postings confirm applied GenAI work: GIR "Agentic Systems" engineers building RAG pipelines and multi-agent workflows with **Google ADK, LangChain, LangGraph, AWS Bedrock**, evaluation with **Braintrust / AgentCore Eval**; Regulatory Engineering asks for **MCP**, **RAG**, fine-tuning, **LangGraph/CrewAI**. The Core Engineering VP posting lists "Agentic AI coding tools, e.g. Claude Code, Co-Pilot Agent Mode, Devin".

This is applied AI engineering inside a bank (research tooling, reporting, developer productivity), not ML platform/product work sold to customers.

### Tech Stack

Derived from **current job postings** (higher.gs.com: Core Engineering VP London #186815, GIR Agentic Systems #187976, Regulatory Engineering VP Warsaw #184757, Data Engineer Lakehouse/AI Warsaw #179762; no German engineering postings exist), plus press coverage of SecDB/Slang and Legend (FINOS) and third-party stack trackers (komo.ai, rfp.wiki; directional only).

| Category | Technologies |
|---|---|
| **Primary language(s)** | **Java and Python** ("Hands-on programming experience in Java or Python", "polyglot Java and Python stacks"); C++ in some low-latency/regulatory teams; proprietary **Slang** on the legacy SecDB risk platform; TypeScript/React for front ends |
| **AI/ML** | AWS Bedrock, Google ADK, LangChain, LangGraph, CrewAI, RAG, vector databases, MCP, Braintrust, AgentCore Eval; GS AI Assistant (multi-LLM); Devin, Claude Code, Copilot agent mode |
| **Cloud** | **AWS** (S3, SQS, Lambda, ECS/Fargate, EventBridge, API Gateway, IAM, CloudWatch, Glue) alongside on-premise for regulated data |
| **Infrastructure** | Docker, Kubernetes, CI/CD, microservices, event-driven architecture |
| **Data** | Kafka, Apache Spark, Snowflake, Apache Iceberg, Databricks, Hadoop, Sybase IQ, Elasticsearch, RDBMS, Avro/Parquet/JSON; Legend (open-sourced data modelling platform) |
| **Other** | FastAPI, Spring Boot, React, BPMN workflow logic, RabbitMQ; SecDB (pricing/risk) |

**Summary:** Polyglot Java and Python backend engineering, with Java historically dominant on core banking systems and Python strong in data, research and GenAI work, plus a proprietary Slang/SecDB legacy layer. AI/ML tooling is AWS Bedrock with LangGraph/ADK-style agent frameworks; data runs on Spark/Kafka into Snowflake/Iceberg/Databricks lakehouses on AWS. The work is applied, production engineering for internal banking functions in a regulated domain, not research.

---

## Section 7: Language

English is Goldman's working language: all engineering postings and the Frankfurt/Munich postings are in English, and the global teams (New York, London, Warsaw, Bengaluru) operate in English. Some German client-facing roles (private bank, investment banking coverage of German Mittelstand) require German, but engineering roles do not.

**Verdict:** **PASS** (moot for Germany, as no engineering roles exist there).

---

## Section 8: Stability

### Financial Position

- FY2025: net revenues $58.28B (+9%), net earnings $17.18B, EPS $51.32.
- Q3 2026: net revenues $18.68B (+23% YoY), net earnings $5.29B, diluted EPS $17.01, annualised ROE 18.7%, efficiency ratio 60.5%. 9M 2026 net earnings $17.55B already exceed full-year 2025.
- Balance sheet (30 Sep 2026): total assets $2.18T, CET1 12.4% (standardised), book value per share $372.64 (up from $353.79 a year earlier).
- German entity GSBE: FY2025 IFRS net income €610M (2024: €730M, below the bank's own expectation); HGB net income €460M; German FTE up 12% in 2025.
- Trend: **strong and improving** at group level. A globally systemic bank (G-SIB) with a decades-long record. Financial runway model not applicable (publicly traded and highly profitable).

### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| Jan 2023 | Largest post-2008 cut | ~3,200 employees (~6.5%) | Firm-wide, after the failed consumer-banking push |
| 2023-2025 (annual) | "Strategic resource assessment" | ~3-5% per year | Annual performance-based cull of low-rated staff; routine at Goldman |
| Late 2025 | OneGS 3.0 memo | "limited" cuts + hiring constraint | AI-driven re-engineering; constrained headcount growth through year-end |
| Apr 2026 onwards | Rolling performance-based cuts | Not disclosed (~700 by end of Q2 per one report) | Shift from one annual round to continuous rounds across divisions, incl. investment banking and asset management; tightened performance criteria "in light of AI" |
| Q3 2025 to Q3 2026 | Net headcount change | 48,300 to 47,500 (-1.7%) | Q2 2026 trough of 46,200; Q3 rise attributed to campus hires |

### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | **UNKNOWN** (no evidence found) | No hits for "Goldman Sachs" + Betriebsrat in press or Kununu review text; the FY2025 GSBE annual report mentions no works council; no LinkedIn evidence searched successfully |
| Collective agreement | **UNKNOWN, likely NONE for senior staff** | Kununu and Glassdoor reviews do not mention Tarif; Goldman is a member of the Bundesverband deutscher Banken (a lobby association), and membership in the AGV Banken employer association (the private-banking ver.di/DBV tariff) was not confirmed. Investment-bank professional staff are typically AT (außertariflich) |
| European works council (multinationals) | **UNKNOWN** | Not found in searches; GSBE is an SE, which normally requires an employee-involvement agreement, but none was located |
| Conflict signals | None found | No union-busting or council-election disputes reported |

The recurring performance culls are exactly the pattern that a German works council would make harder (the §102 BetrVG hearing before every dismissal). Without evidence of a council in the German entity, there is no protection signal to offset the firm's forced-ranking culture.

**Verdict:** **CAUTION** (financially very stable, but recurring forced-ranking cuts, continuous 2026 cull rounds, and no evidence of a works council or tariff).

---

## Section 9: Regulated Industry

Heavily regulated. GSBE is supervised by the **ECB (SSM), BaFin and the Deutsche Bundesbank**; the group is a US G-SIB under the Federal Reserve. Applicable engineering-relevant regimes include **DORA** (ICT risk, incident reporting, third-party risk), **MaRisk / BAIT**, **MiFID II** (record-keeping, communications surveillance), **EMIR/SFTR** trade reporting (the Regulatory Engineering team exists to feed these), Basel/CRR capital calculations and model-risk governance (SR 11-7 equivalents). Practical impact: change-management controls and approvals, segregation of duties, the "first line of defence" control ownership placed on Engineering, cloud usage gated by regulators for regulated data, and communications monitoring.

**Verdict:** **CAUTION**

---

## Section 10: On-Call

Postings show on-call is common for production-facing engineering: "24*7 rotational shift (weekend on-call support as necessary)" (Transaction Banking Mission Control, Dallas); "participation in an on-call rotation and acting as the escalation point for... L3 escalations" (VP, Dallas); "may require participation in an on-call rotation and may need to work outside of standard hours during critical incidents or outages" (Runtime Platform Engineer VP, Warsaw); dedicated Production Support and SRE teams exist. The GIR Agentic Systems role lists "triage production incidents" as a duty. Research/data roles appear lighter. Third-party interview-prep sites describe rotations "every few weeks" (anecdotal).

**Verdict:** **CAUTION (team-dependent)**, leaning towards on-call for any platform or production-facing role.

---

## Section 11: Interview Process

Based on Glassdoor (Software Engineer filter, 660 interview reports), retrieved via **Chromium over CDP**.

| Metric | Value |
|---|---|
| Difficulty | **3.1 / 5** (641 ratings, sum 2,016) |
| Positive experience | **47%** (negative 21%, rest neutral) |
| Average duration | **UNKNOWN** (not exposed; individual reports cite ~14 days) |
| Rounds | 3-5 |

Sources of interviews: online application 50%, campus recruiting 19%, recruiter 18%. Typical process: **HackerRank online assessment** or **CoderPad** live coding, often a **HireVue** recorded behavioural screen, then a **"Super Day"** of back-to-back 45-minute interviews (coding, data structures, system design, behavioural, sometimes SQL/APIs/Kafka). Reported questions are LeetCode easy-to-medium plus one system-design round. Some candidates report disorganised panels ("Interviewers didn't see the resume", "interviewers didn't even join the meeting"). **LeetCode-style, moderately algorithmic**, with design added for VP level.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | **FAIL**: investment bank; engineering is an internal first-line function |
| Not consulting | PASS |
| Profitable | **PASS**: $17.18B net earnings FY2025, ROE ~19-21% in 2026 |
| Employee count | PASS: 47,500 globally; 431 FTE in Germany (Frankfurt + Munich) |
| English-speaking | PASS for engineering (moot in Germany) |
| Local entity + engineering contracts | PASS with CAUTION: GSBE (HRB 114190) is a licensed bank; no German engineering roles |
| Location / work model | **FAIL**: Munich office (Maximilianstraße 35) has no engineering; five-day office mandate; no remote |
| Glassdoor | 3.7 global / 4.1 Germany (52, mostly Frankfurt banking) / 1 Munich review / 3.7 SWE (56% recommend); WLB 2.9 global |
| Kununu | 3.7 (32 employee reviews), 87% recommend (last 2 years), no Top Company |
| Salary | UNVERIFIED: Frankfurt VP posting €100-125K base + discretionary bonus; no German SWE data on levels.fyi |
| AI/ML content | Substantial applied GenAI (agents, RAG, Bedrock, LangGraph) in research/regulatory/internal tools |
| Computer-language/Tech-stack | Polyglot Java and Python, AWS, Kafka/Spark/Snowflake/Iceberg; legacy Slang/SecDB |
| No on-call | CAUTION: on-call rotations common in production and platform teams |
| WLB / Stability | Financially rock-solid; WLB weak (2.9); recurring forced-ranking culls |
| Works council / collective agreement | UNKNOWN; no evidence of either |
| Regulated industry | CAUTION: ECB/BaFin/Bundesbank, DORA, MiFID II |
| Review themes | Pay and smart colleagues vs. long hours, rigidity, toxic pockets, "tech is secondary" |
| Rolling performance culls | **HIGH CAUTION**: annual 3-5% cull, continuous rounds since April 2026 |

---

## Section 13: Verdict

**Exclude.** Goldman Sachs is an exceptionally profitable, stable institution with serious applied-AI engineering, but it fails the core criteria for a Munich-based senior or staff software engineering search.

**Strengths:** record-level profitability and capital strength; a large, genuine German entity with direct contracts; real investment in applied GenAI (agentic research tooling, regulatory-reporting modernisation, AI-assisted development); a Java/Python stack on AWS with modern data platforms; strong pay driven by the bonus; highly capable colleagues.

**Hard blockers:**

1. **No engineering in Munich, none open in Germany.** The Munich branch hosts investment banking, asset management and wealth management only; on 2026-11-04 the careers site showed one Munich role (IB Analyst) and six Frankfurt roles, none in engineering. Goldman's European engineering sits in London, Warsaw and Birmingham, all requiring relocation.
2. **Not software-centric.** Engineering is an internal control-owning support function of a bank (first line of defence reporting to the COO), and current engineers describe it as "Tech is secondary".
3. **Work-life balance.** The lowest global sub-score at 2.9 across 20,134 reviews, Blind WLB 3.0, and only 56% of software-engineer reviewers recommend the firm. Long hours and weekend work recur across platforms and years.
4. **Five-day office mandate** firm-wide since 2023, with no remote option.

**Secondary concerns:** rolling, forced-ranking performance culls that became continuous in 2026 under OneGS 3.0; no evidence of a works council or collective agreement in the German entity; heavy regulatory overhead (DORA, MiFID II, ECB/BaFin supervision); team-dependent on-call; a corporate-title ladder (VP/ED/MD) that can blur engineering seniority; legacy Slang/SecDB exposure in markets technology; a LeetCode-style interview loop with mixed candidate experience (47% positive).

**Recommendation:** No further research is warranted. The only thing that would change this verdict is Goldman opening a genuine engineering hub in Munich (or offering fully-remote German engineering contracts), and even then the five-day office mandate, the weak WLB scores and the forced-ranking culls would still have to be verified as not applying to that team.

---

## Sources

- [Goldman Sachs 2025 Q4 / FY2025 earnings results (SEC 8-K)](https://www.sec.gov/Archives/edgar/data/886982/000088698226000008/a4q25gsearningsresults.htm)
- [Goldman Sachs 2025 Q4 results (PDF)](https://www.goldmansachs.com/pressroom/press-releases/current/pdfs/2025-q4-results.pdf)
- [Goldman Sachs 2025 Annual Report](https://www.goldmansachs.com/investor-relations/financials/current/annual-reports/2025-annual-report)
- [Goldman Sachs Q3 2026 earnings results (SEC 8-K)](https://www.sec.gov/Archives/edgar/data/0000886982/000088698226000529/a3q26gsearningsresults.htm)
- [Goldman Sachs Q3 2026 Form 10-Q](https://www.sec.gov/Archives/edgar/data/0000886982/000088698226000532/gs-20260930.htm)
- [Family Wealth Report: Goldman Sachs Asset, Wealth revenues rise 14% in Q3 2026](https://www.familywealthreport.com/article.php/Goldman-Sachs-Asset%2C-Wealth-Revenues-Rise-14-Per-Cent-In-Q3-2026)
- [GSBE FY2025 German GAAP Annual Report (Lobbyregister copy)](https://www.lobbyregister.bundestag.de/media/8d/28/795704/GSBE-FY25-German-GAAP-Annual-Report-DE.pdf)
- [GSBE FY2025 Non-Financial Report](https://d3cobg6h0snvt3.cloudfront.net/disclosures/pdfs/GSBE-FY25-Non-Financial-Report-DE.pdf)
- [GSBE Q1 2024 Pillar 3 disclosure](https://d3cobg6h0snvt3.cloudfront.net/disclosures/pdfs/GSBE-Q1-2024-Pillar-3-DE.pdf)
- [NorthData: Goldman Sachs Bank Europe SE, HRB 114190 (via CDP)](https://www.northdata.com/Goldman+Sachs+Bank+Europe+SE,+Frankfurt+am+Main/HRB+114190)
- [LEI lookup: Goldman Sachs Bank Europe SE](https://www.lei-lookup.com/record/8IBZUGJ7JPLH368JE346/)
- [Goldman Sachs in Deutschland](https://www.goldmansachs.com/worldwide/germany/goldman-sachs-in-deutchland/index.html)
- [Goldman Sachs office locations](https://www.goldmansachs.com/our-firm/locations)
- [Bloomberg: Goldman Sachs to boost Germany presence with Munich office (2022)](https://www.bloomberg.com/news/articles/2022-11-25/goldman-sachs-to-boost-germany-presence-with-munich-office)
- [Börsen-Zeitung: Goldman zieht es nach München](https://www.boersen-zeitung.de/banken-finanzen/goldman-zieht-es-nach-muenchen-d265980c-6ca9-11ed-83b7-dc92fc6846c5)
- [Private Banker International: Goldman Sachs office Munich](https://www.privatebankerinternational.com/news/goldman-sachs-office-munich/)
- [Private Banking Magazin: Goldman Sachs Wealth Management in München](https://www.private-banking-magazin.de/goldman-sachs-eroeffnet-weiteren-standort-in-muenchen/)
- [Nominatim geocode: Maximilianstraße 35, München](https://nominatim.openstreetmap.org/search?q=Maximilianstra%C3%9Fe+35,+80539+M%C3%BCnchen&format=json&addressdetails=1)
- [Overpass API (public transport around the office)](https://overpass-api.de/api/interpreter)
- [Goldman Sachs careers: Munich results (via CDP)](https://higher.gs.com/results?LOCATION=Munich&page=1&sort=RELEVANCE)
- [Goldman Sachs careers: Frankfurt results (via CDP)](https://higher.gs.com/results?LOCATION=Frankfurt&page=1&sort=RELEVANCE)
- [Job posting: Core Engineering, VP Software Engineering, London](https://higher.gs.com/roles/186815)
- [Job posting: Software Engineer, GIR Agentic Systems, Associate](https://higher.gs.com/roles/187976)
- [Job posting: GBM Regulatory Engineering, VP, Warsaw](https://higher.gs.com/roles/184757)
- [Job posting: Data Engineer, Lakehouse and AI Data Platform, Warsaw](https://higher.gs.com/roles/179762)
- [LinkedIn jobs: Goldman Sachs in Germany (guest API via curl)](https://www.linkedin.com/jobs-guest/jobs/api/seeMoreJobPostings/search?f_C=1382&location=Germany&start=0)
- [Glassdoor: Goldman Sachs reviews, global (via CDP)](https://www.glassdoor.de/Bewertungen/Goldman-Sachs-Bewertungen-E2800.htm?filter.iso3Language=eng&filter.countryId=0)
- [Glassdoor: Goldman Sachs reviews, Germany (via CDP)](https://www.glassdoor.de/Bewertungen/Goldman-Sachs-Bewertungen-E2800.htm?filter.locationId=96&filter.locationType=N)
- [Glassdoor: Goldman Sachs reviews, Munich (via CDP)](https://www.glassdoor.de/Bewertungen/Goldman-Sachs-Bewertungen-E2800.htm?filter.locationId=4990924&filter.locationType=C)
- [Glassdoor: Goldman Sachs reviews, Software Engineer (via CDP)](https://www.glassdoor.de/Bewertungen/Goldman-Sachs-Bewertungen-E2800.htm?filter.iso3Language=eng&filter.jobTitleFTS=Software+Engineer)
- [Glassdoor: Goldman Sachs Software Engineer interviews (via CDP)](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/Goldman-Sachs-Fragen-im-Vorstellungsgespr%C3%A4ch-E2800.htm?filter.jobTitleFTS=Software+Engineer)
- [Kununu: Goldman Sachs AG (via CDP)](https://www.kununu.com/de/goldman-sachs1)
- [Kununu: Goldman Sachs AG reviews (via CDP)](https://www.kununu.com/de/goldman-sachs1/kommentare)
- [Blind: Goldman Sachs reviews (via CDP)](https://www.teamblind.com/company/Goldman-Sachs/reviews)
- [levels.fyi: Goldman Sachs Software Engineer, Germany (via CDP)](https://www.levels.fyi/companies/goldman-sachs/salaries/software-engineer/locations/germany)
- [levels.fyi: Goldman Sachs Software Engineer, Warsaw (via CDP)](https://www.levels.fyi/companies/goldman-sachs/salaries/software-engineer/locations/warsaw-metropolitan-area)
- [levels.fyi: Goldman Sachs Software Engineer, United States (via CDP)](https://www.levels.fyi/companies/goldman-sachs/salaries/software-engineer)
- [Jobijoba: Goldman Sachs Frankfurt VP posting with salary range](https://www.jobijoba.de/detailanzeige/9/fb26740653b336e9ac001f57d8f81e6d)
- [Outlook Business: Goldman Sachs warns of job cuts and hiring slowdown amid AI push](https://www.outlookbusiness.com/corporate/amid-push-for-ai-goldman-sachs-warn-employees-of-job-cuts-and-hiring-slowdown)
- [Reuters via TradingView: Goldman eyes job cuts and hiring slowdown amid AI push, memo shows](https://www.tradingview.com/news/reuters.com,2025:newsml_L3N3VV1FA:0-goldman-sachs-eyes-job-cuts-and-hiring-slowdown-amid-ai-push-memo-shows)
- [Nasdaq: GS' rolling layoffs in 2026](https://www.nasdaq.com/articles/gs-rolling-layoffs-2026-strategic-shift-workforce-management)
- [People Matters: Goldman Sachs to begin layoffs under OneGS 3.0](https://me.peoplemattersglobal.com/news/strategic-hr/goldman-sachs-to-begin-layoffs-under-new-onegs-30-plan-46857)
- [Banking Dive: Goldman limited cuts, AI, Q3 earnings](https://www.bankingdive.com/news/goldman-sachs-limited-cuts-ai-acquisition-industry-ventures-965-million-solomon-q3-earnings/802869/)
- [eFinancialCareers: Goldman Sachs cutting in 2025](https://www.efinancialcareers.com/news/goldman-sachs-cutting-2025)
- [Fortune: Deutsche Bank managers return to office (cites Goldman five-day policy)](https://fortune.com/europe/2024/02/16/deutsche-bank-managers-return-to-the-officeproductivity-remote-work)
- [Fortune: Goldman Sachs return to work, David Solomon (2022)](https://fortune.com/2022/03/11/goldman-sachs-return-to-work-employees-david-solomon)
- [eFinancialCareers: Goldman Sachs remote working developers (2022)](https://www.efinancialcareers.co.uk/news/2022/03/goldman-sachs-remote-working-developers)
- [FOX Business: Goldman Sachs announces firmwide launch of AI assistant](https://foxbusiness.com/technology/goldman-sachs-announces-firmwide-launch-ai-assistant)
- [Quartz: Goldman Sachs just hired its first AI coder (Devin)](https://qz.com/goldman-sachs-ai-coder-devin-cognition)
- [eFinancialCareers: SecDB and Slang at Goldman Sachs](https://www.efinancialcareers.com/news/2017/02/secdb-goldman-sachs-slang)
- [Fortune: Goldman Sachs software (2016)](https://fortune.com/2016/09/07/goldman-sachs-software)
- [komo.ai: Goldman Sachs tech stack (directional)](https://komo.ai/directory/goldman-sachs-tech-stack)
- [rfp.wiki: Goldman Sachs technology stack (directional)](https://www.rfp.wiki/investment/goldman-sachs)
- [Recruiter.com: Transaction Banking Mission Control posting (on-call)](https://jobs.recruiter.com/jobs/11317876992-systems-engineering-transaction-banking-mission-control-dallas-associate)
- [Runtime Platform Engineer VP, Warsaw posting (on-call)](https://hw.glich.co/jobboard/jobs/engineering-runtime-platform-engineer-vice-president-warsaw-at-goldman-sachs-zev49n)
- [CleverPrep: Goldman Sachs software engineer (on-call, anecdotal)](https://www.cleverprep.com/companies/goldman-sachs/software-engineer)
