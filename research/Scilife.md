# Scilife - Full Research Report

_Researched: 2026-11-05_

> **Critical Disqualifiers**
> 1. **No German entity; Germany-based staff are hired through an Employer of Record.** Scilife's own careers FAQ: "As we have legal entities in the United States, Belgium, and Spain, we hire directly in these countries. In other locations where we do not have a legal entity, we hire through an Employer of Record (EOR)." No Scilife entity exists in the German register (NorthData shows only Scilife N.V., Brussels). A contract in Germany would be with a third-party EOR, not with Scilife. The criteria require a direct, permanent employment contract. **FAIL**
> 2. **PHP-centric product engineering.** The core eQMS runs on a LAMP stack (PHP 8.2 on AWS Elastic Beanstalk, MySQL, MongoDB). Python is used only in a small AI & Data Analytics team. The criteria require Python as the main language. **FAIL** for core engineering, **BORDERLINE** for the AI/ML team.
> 3. **Loss-making, with losses growing and equity shrinking.** Scilife N.V. lost €3.09M in 2025 (2024: €1.61M; 2023: €0.91M); equity fell from €4.68M to €1.59M in one year, now below a quarter of subscribed capital (€7.69M). **FAIL** on profitability and stability.
> 4. **Glassdoor 3.5 / 5 on only 11 English reviews, with recent toxicity allegations** (mobbing, micromanagement, unfair dismissals, unpaid overtime, bias against the Indian team). Below the 4.0 floor used in these reports. **FAIL**
> 5. **No engineering vacancy at all right now.** The careers page lists four roles, all in sales (BDR Manager, two BDRs, Account Executive).
>
> The full report follows for completeness.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 2017 (9 years). Incorporated 10 May 2017 as a spin-off of the Belgian life-sciences consultancy QbD Group ("QbD Software"); rebranded to Scilife in June 2021 |
| Employees | "90+ Scilifers" (careers and About pages, 2026); "more than 70" in Sep 2024. LinkedIn: 51-200 band, 122 associated members. The Belgian N.V. itself reports only ~1 FTE on its balance sheet (2022), so most staff are employed via the Spanish/US subsidiaries or EOR providers |
| Revenue (FY2025) | Not disclosed. Belgian abbreviated accounts do not show turnover. Glassdoor lists "1 to 5 million USD"; 240+ customers and 22,500+ users (About page). **UNVERIFIED** |
| Profitability | Net loss €3.09M (2025), €1.61M (2024), €0.91M (2023), €0.20M (2022), per NBB filings via Companyweb. Loss roughly doubling each year - **FAIL** |
| Ownership | Private equity: growth investment by Five Elms Capital (Jun 2024). NorthData's 29 Sep 2026 filing lists **Five Elms V BidCo B.V.** as shareholder, and a Five Elms partner (Joseph Onofrio) sits on the board, consistent with a control buyout through a bid vehicle rather than a minority stake. LinkedIn still shows QbD Group as "parent" (stale) |
| Software-centric | Pure B2B SaaS: an electronic Quality Management System (eQMS) for pharma, biotech, medical devices, healthcare logistics and medicinal cannabis. Registered NACE codes 62.01/62.10 (computer programming) - **PASS** |

### Key People

- **Sebastien Sepierre**, CEO since 2 Sep 2024 (ex-Managing Director at Fourth, workforce-management SaaS; earlier IBM). Appointed after the Five Elms deal with a mandate to "prioritize growth by driving both new customer acquisition and the expansion of existing customer relationships"
- **Filip Heitbrink**, co-founder and former CEO, now board member (Glassdoor's 88% CEO approval still refers to him)
- **Roozbeh Farahbod**, CTO (LinkedIn location: Germany)
- **George Mamaladze**, VP of Engineering (LinkedIn location: Germany)
- **Marina Hoffmann**, CISO (LinkedIn location: Germany)
- **Board (NorthData):** Joseph Onofrio (Five Elms partner), Elly De Bruyn, Sara Kockx. Founders on record: Mark Kockx, Marian Moens, Martijn Reniers, Bart Van Acker (QbD Group founders)

### Funding History

| Date | Round | Amount | Investor | Valuation |
|---|---|---|---|---|
| 2017 to 2021 | Bootstrapped inside QbD Group | n/a | QbD Group | n/a |
| Jun 2024 | Strategic growth investment (control via Five Elms V BidCo B.V.) | Undisclosed. Subscribed capital rose from €325K to €7.69M (NorthData, 27 Jun 2024) | Five Elms Capital (US growth equity, $2.4B AUM, software only) | Undisclosed |

### Business Model

Subscription SaaS sold per module/tier (pharma & biotech, medical devices, ATMP plans). Products: Smart QMS (document control, CAPA, change control, deviations, audits, training, risk, equipment, KPIs), a Design & Development module for MedTech (launched Jul 2025), and Controlled Printing & Reconciliation (21 CFR Part 11). Distribution is partly through life-sciences consultancies and validation partners (35+ partners). Customers include Novartis, Biocartis, Yusen Logistics, Polpharma and Pendulum.

### Consulting-Adjacency Assessment

Scilife itself is a product company: engineers build one multi-tenant product, and nobody bills hours. The origin is consulting-adjacent (spun out of QbD Group, a compliance consultancy, which LinkedIn still lists as parent) and implementation/validation services are delivered by partners, not by engineering. **Not consulting** for engineering roles.

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **Scilife N.V.** (Belgium) | KBO/BCE 0675.685.469 (EUID BEKBOBCE.0675.685.469) | Kantersteen 47, Central Gate, 1000 Brussels (moved from Wilrijk/Antwerp; Staatsblad 2 Jul 2026) | NACE 62.01 / 62.10 computer programming |
| **Scilife Inc.** (USA) | US subsidiary, established 2023 | 228 E 45th St. RM 9E, New York, NY 10017 | US sales and support |
| Spanish entity | Name not verified | Barcelona area (inferred from staff locations) | Named in the careers FAQ as a direct-hiring entity |
| **German entity** | **None found** | n/a | n/a |

NorthData search for "Scilife" returns only the Belgian N.V.; a web search for "Scilife GmbH" in the Handelsregister returned no match. The careers FAQ is explicit that direct hiring happens only in Belgium, Spain and the US, and everywhere else via an Employer of Record. LinkedIn shows 5 Scilife members in Germany, among them the CTO, VP of Engineering, CISO, an IT Ops Manager and a Backend Staff Engineer, so senior engineers in Germany exist, but on EOR contracts. An EOR contract is legally an employment contract with the EOR provider (e.g. a Deel/Remote-type GmbH), not with Scilife: the employer's obligations and any dismissal decision sit with a third party acting on Scilife's instruction.

**Verdict:** **FAIL** (no German entity; EOR employment only)

---

## Section 3: Office Location

- **Office address:** No office in Munich or anywhere in Germany. Scilife states it is "100% remote since day one" and "We do not have traditional physical offices where employees are required to work on-site." The registered EMEA address is Kantersteen 47 (Central Gate), 1000 Brussels, Quartier du Centre / Pentagone (Nominatim confirms postcode 1000, Bruxelles-Ville). It is a registered/administrative address, not a workplace.
- **Nearest public transport:** For reference only: Bruxelles-Central / Brussel-Centraal railway station is ~90-110 m from Kantersteen 47 (Nominatim geocode of both points; the Overpass query timed out on two mirrors, so the full stop list with lines was not retrieved).
- **Work model:** Fully remote, "freedom to work remotely within your country", flexible hours, two all-expenses-paid team gatherings per year (one in Europe, one in India). Working from Munich would be possible in principle, via EOR. Staff distribution on LinkedIn: Spain ~40, India ~20, Pakistan ~16, Germany 5.

---

## Section 4: Reviews

**GPTW:** Glassdoor's awards list shows "Great Place to Work Certified, 2023" and LinkedIn says "we've earned our title as a Great Place to Work". The certifying country could not be verified: a search of greatplacetowork.de and greatplacetowork.com found no Scilife certificate page. Not in any German GPTW ranking. Scilife was also in the **Flexa100 (2024)** list of flexible employers (85% Flexa score). The 2023 certification is three years old and predates the PE deal and CEO change.

#### Glassdoor

Retrieved via Chromium over CDP (glassdoor.de, logged in; the English-language filter had to be set explicitly, since the German-locale default shows 0 reviews). 14 reviews in total across languages, 11 in English.

| Metric | Global | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | 3.5 (11 English reviews) | no reviews | no reviews | 2.5 (2 "Software developer" reviews: 4.0 and 1.0); 4.0 incl. 2 "Software test engineer" reviews (5.0, 3.0) |
| **WLB** | 3.8 | n/a | n/a | n/a |
| **Culture & Values** | 3.7 | n/a | n/a | n/a |
| **Comp & Benefits** | 3.9 | n/a | n/a | n/a |
| **Career Opportunities** | 3.3 | n/a | n/a | n/a |
| **Senior Management** | 3.4 | n/a | n/a | n/a |
| **Diversity & Inclusion** | 3.8 | n/a | n/a | n/a |
| **% Recommend** | 69% | n/a | n/a | n/a |
| **CEO Approval** | 88% (attributed to former CEO Filip Heitbrink) | n/a | n/a | n/a |
| **Business Outlook** | 78% positive | n/a | n/a | n/a |

All filters are far below 20 reviews: treat every score as directional. Reviewer locations are Jodhpur, Mumbai, Pune, Karachi, Barcelona; none from Germany. Rating trend over the last 6 months: ~3.4 to 3.8, flat.

#### Kununu

Fetched `kununu.com/de/scilife`, `scilife1` and `scilife-nv` via curl (HTTP 405, bot block) and via Chromium/CDP (404 "Seite nicht gefunden"); the Kununu search for "Scilife" returned no employer.

- **Overall score:** NONE (no profile)
- **Recommendation rate:** n/a
- **Total reviews:** 0
- **Kununu Top Company:** NO

Expected for a company with no German entity and 5 people in Germany.

#### Blind / Teamblind

`teamblind.com/company/Scilife` returns "Page not found" (via CDP). No profile, no reviews.

#### Review Themes (2023-2026)

**Positives:**

- **Fully remote and flexible hours.** "Good Environment to work, 100% Remote" (Glassdoor, Sep 2024, current Software test engineer, Mumbai, 1+ years). "Flexible hours, remote work, transparency, young teams, getting-things-done mindset, competitive salary" (Glassdoor, Feb 2024, current Product manager, Barcelona, <1 year).
- **Supportive colleagues.** "Great group of people, Supportive environment" (Glassdoor, Sep 2026, former Technical support engineer, Barcelona). "Good environment Flexible hours to work Remote company ... Supportive team and manager" (Glassdoor, Aug 2024, current Finance and accounting, Jodhpur, <1 year).
- **Team gatherings and diversity** appear in pros even of negative reviews: "Team building Flexible working hours Diversity" (Glassdoor, Aug 2026, former Software developer, 5+ years).

**Negatives:**

- **Bias and a two-tier team (India vs. Europe).** "Huge racism between Indian employees and European people Less respect for Indian team No growth and no exposure for Indian team Huge biasing in all fronts" (Glassdoor, Aug 2026, former Software developer, 5+ years). Echoed mildly by "Sometimes bit biased towards fav employees" (Glassdoor, Apr 2025, current Software developer, Jodhpur, 3+ years). Both are engineers.
- **Toxic environment, mobbing, micromanagement, unfair dismissals.** "I quit my job because mobbing, sexism and micromanagement were my day-to-day and I had no support at all once my manager was fired for no reason ... Some people are intouchable and they can bully you, but if you speak up you will be punished ... Most valuable people I've met in this company have quit for the same reasons or have been fired" (Glassdoor, Jan 2024, former UX designer, <1 year). "Too often, valuable people are unfairly fired, with managers lacking industry experience at the helm. The management is absolutely dehumanizing, promoting micromanagement, unpaid overtime, and a tense environment. Don't be deceived by ... the title 'best place to work'" (Glassdoor, Nov 2023, current Anonymous Employee).
- **Micromanagement** recurs even in positive reviews: "Too much of micro management" (Glassdoor, May 2023, current Anonymous Employee, Karachi, 5+ years, rated 5.0).
- **Job security.** "No job security at scilife" (Glassdoor, Nov 2024, former Software test engineer, Pune).
- **Shift to corporate after the PE deal.** "Shifting from start-up mentality to corporate enterprise" (Glassdoor, Sep 2026, former Technical support engineer, Barcelona).

Overlap with hard red flags: toxic leadership, unpaid overtime, silent firings/unfair dismissals and a communication/respect breakdown each appear at least once; the strongest allegations are from 2023-early 2024 (pre-PE, pre-new CEO), the bias allegation from Aug 2026.

#### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | Two strongly negative reviews (Nov 2023, Jan 2024) allege "dehumanizing" management, mobbing and bullying by "untouchable" people. Both predate the 2024 leadership change. Not repeated by engineers |
| 24/7 Work Expectation | Not reported. The global time-zone spread (India, Pakistan, Spain, US) is a structural risk for late/early calls |
| Internal Surveillance | Not reported |
| Fear-driven Management | "if you speak up you will be punished" (Glassdoor, Jan 2024, former UX designer) |
| Communication Breakdown | Reported as a cultural split: "Less respect for Indian team ... No growth and no exposure" (Glassdoor, Aug 2026, former Software developer) |
| Unpaid Overtime | "promoting micromanagement, unpaid overtime" (Glassdoor, Nov 2023, current Anonymous Employee). Single mention |
| Silent Firings | "valuable people are unfairly fired" (Nov 2023); "my manager was fired for no reason" (Jan 2024); "No job security" (Nov 2024, Software test engineer). Three independent mentions over a year |
| Work-Life Balance issues | WLB rated 3.8; flexible hours and leave policy praised; no WLB complaints apart from the unpaid-overtime mention |

**Risk level: MODERATE.** The pattern is (c) localized dysfunction rather than systemic toxicity, but on a very small sample: 5 of 11 reviews are 1-3 stars, and unfair dismissals are mentioned three times. Without a works council or German employer of its own, there is no structural protection against the dismissal pattern (see Section 8). The 2024 CEO change could have reset the culture, but the Aug 2026 bias review suggests problems persist in engineering.

---

## Section 5: Compensation

#### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| Glassdoor (CDP) | All titles | not shown (2 total-comp entries, 0 visible titles) | n/a | n/a | n/a | 27 salaries listed in search; by city: Jodhpur 7, Barcelona 6, Madrid 5; none in Germany |
| levels.fyi | n/a | no company page (404 via CDP) | n/a | n/a | n/a | 0 |
| Job postings | Senior Software Engineer (LAMP), AI/ML Engineer | not disclosed | n/a | n/a | n/a | 0 |

Munich percentiles: not retrieved for this report. With no Scilife data point in Germany, there is nothing to compare against them.

Glassdoor's own AI summary of pay: "Reviews mention 'sometimes good salary,' but another flags it as not reliably great." One reviewer (Barcelona PM) calls salary "competitive"; another calls pay "fair".

#### Equity / Stock

No evidence of an employee equity or option plan in postings or reviews. As a PE-controlled company, any management incentive plan is likely limited to leadership. Treat as **no equity** for an IC role.

#### Verdict

The salary base is Spain/India/Pakistan-weighted and the company is loss-making under PE ownership; there is no German data point. Likely below the Munich large-company bracket for a Staff role, but not verifiable. **UNVERIFIED (likely BELOW)**

---

## Section 6: AI/ML & Tech Stack

#### AI Strategy

Modest and early. Scilife has an **AI & Data Analytics team** that hired an AI/ML Engineer (posting ~2025; Glassdoor interview review Aug 2025, New York) to build LLM features: "semantic search techniques, retrieval-augmented generation (RAG) methods, and advanced LLM-based frameworks", analysing "text-based documents and event records" (deviations, CAPAs). The privacy policy now mentions "logging of user inputs and AI model outputs", retained 45 days, so some AI features are live. Marketing still centres on "Smart Quality" (analytics, gamification, learning) rather than a named AI product, and a third-party vendor review (rfp.wiki) notes "limited public evidence" of AI copilot use cases. Applied LLM integration on top of a document-heavy domain, not ML platform or research work.

#### Tech Stack

Derived from job postings (Senior Software Engineer (LAMP Stack) via Weekday; AI/ML Engineer via scilife.io/Arc.dev), DNS of the production hosts (`demo.scilife.io` CNAMEs to `qms-prod-val3.scilife.io` → `qms-prod-php82-al2023.eba-pu2ykpeb.eu-west-1.elasticbeanstalk.com`; `scilife.io` DNS on Route 53), and LinkedIn skills of Germany-based staff. GitHub org `scilife` exists (created 2019) with 0 public repos. No engineering blog, StackShare or conference talks found.

| Category | Technologies |
|---|---|
| **Primary language(s)** | **PHP 8.2** (LAMP stack; Laravel/CodeIgniter likely but unconfirmed); JavaScript front end. Java and Go appear in the skills of a Germany-based Backend Staff Engineer ("DDD, Event-Driven Architecture, Modular Systems \| PHP, Java, Go"), possibly signalling a modularisation effort |
| **AI/ML** | Python, TensorFlow, PyTorch, scikit-learn, pandas, NumPy, LLM APIs, RAG, semantic search, vector databases |
| **Cloud** | AWS (EC2, RDS, S3, Lambda, CloudFormation, Elastic Beanstalk on Amazon Linux 2023, Route 53), region eu-west-1 (Ireland) |
| **Infrastructure** | Linux, Apache, Elastic Beanstalk environments per validation stage ("prod-val3"), CI/CD pipelines |
| **Data** | MySQL, MongoDB |
| **Other** | Git, Jira; HubSpot for the website; GAMP 5 / 21 CFR Part 11 validation |

**Summary:** PHP-centric LAMP engineering (PHP 8.2, MySQL, MongoDB) on AWS Elastic Beanstalk, with a small Python AI & Data Analytics team adding LLM/RAG features on AWS. Applied, production engineering in a GxP-validated domain; no research.

---

## Section 7: Language

All postings are in English, and the company works across 25+ nationalities and 13+ languages with English as the common language. The only German-language requirement is in a sales role ("Business Development Representative (German)"). Engineering leadership is partly German-based but works in English.

**Verdict:** **PASS**

---

## Section 8: Stability

#### Financial Position

From Scilife N.V. abbreviated annual accounts (NBB, via Companyweb; NBB's own PDF/CSV endpoints returned 403 to curl and to the browser):

| Year | Net result | Gross margin* | Total assets | Equity | Debts |
|---|---|---|---|---|---|
| 2022 | −€0.20M | €0.12M | €1.56M | −€0.16M | €1.72M |
| 2023 | −€0.91M | −€0.44M | €1.42M | −€1.07M | €2.48M |
| 2024 | −€1.61M | −€1.26M | €8.22M | €4.68M | €3.54M |
| 2025 | **−€3.09M** | −€1.63M | €6.52M | **€1.59M** | €4.93M |

\* In the Belgian abbreviated scheme, "gross margin" is turnover minus purchased goods and services. A negative figure means services bought in (which here include EOR fees and contractor costs for most of the workforce) exceed revenue.

Loss is accelerating (~doubling each year) while the Five Elms capital injection of 2024 (subscribed capital raised to €7.69M) is being consumed. Equity of €1.59M is below half and below a quarter of subscribed capital, which under Belgian company law (art. 7:228 WVV) triggers the "alarm bell" procedure: the board must convene shareholders to decide on continuity. With a PE owner this normally ends in a further capital injection, but it marks the company as dependent on Five Elms funding.

#### Financial Runway

No cash line was obtainable (NBB filings blocked; NorthData shows charts only; no press commentary on burn). Model below is bottom-up and should be read as an order of magnitude.

| Cost line | Annual estimate |
|---|---|
| Staff (~90 people; ~45% Spain, ~40% India/Pakistan, ~15% DE/BE/US/other; blended fully-loaded ~€55K incl. EOR fees) | ~€5.0M |
| Cloud hosting (AWS), SaaS tooling, validation | ~€0.4M |
| Sales & marketing (HubSpot, events, partner commissions, G2) | ~€0.6M |
| Two all-expenses team gatherings, G&A, legal | ~€0.4M |
| **Total gross burn** | **~€6.4M/year** |

| Revenue source | Est. annual inflow |
|---|---|
| Subscriptions (240+ customers × ~€15-25K ACV) | ~€3.6-6.0M/year |
| **Total revenue offset** | **~€3.5-6M/year** |

Net burn implied: ~€0.5-3M/year, consistent with the reported 2025 loss of €3.1M at the upper end.

| Scenario | Net burn | Cash at hand | Runway | Next round needed by |
|---|---|---|---|---|
| Optimistic | €1.0M/year | ~€3M (assumed; ~half of 2025 total assets) | ~3 years | ~2029 |
| Base case | €3.0M/year (2025 actual loss) | ~€3M (assumed) | ~1 year | ~late 2026 / 2027 |
| Stress | €4.5M/year (loss keeps growing at 2024-25 rate) | ~€2M (assumed) | <6 months | now |

Cash figure: **not observed**; assumed from total assets of €6.52M at 31 Dec 2025 (NBB filing published 29 Sep 2026). In the base case, Scilife needs fresh capital from Five Elms during 2026-2027, which is plausible (growth-equity owners usually fund to plan) but makes the company's continuity a decision of one investor.

#### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| 2023-2024 | Individual dismissals described in reviews | Unknown | "valuable people are unfairly fired" (Nov 2023), "my manager was fired for no reason" (Jan 2024), "No job security" (Nov 2024) |

No announced layoffs found (TrueUp/press searches returned nothing). Headcount grew from 70+ (Sep 2024) to 90+ (2026).

#### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | **NO** (structurally impossible at Scilife in Germany) | No German entity; German staff employed by an EOR. Any Betriebsrat would belong to the EOR provider, which is unlikely to have one. Belgian N.V. has ~1 FTE, below the threshold for a Belgian ondernemingsraad |
| Collective agreement | **NONE** | No tariff mention in postings, reviews or filings |
| European works council | N/A | Below thresholds |
| Conflict signals | None found | No union/press coverage |

Combined with three review mentions of unfair dismissals and PE ownership, the absence of any co-determination is a material risk.

**Verdict:** **FAIL** (loss growing, equity below a quarter of capital, dependence on one PE owner, no works council)

---

## Section 9: Regulated Industry

Scilife's customers are regulated (GMP/GDP/GLP, FDA 21 CFR Part 11, EU Annex 11, ISO 13485, EU MDR/IVDR), and the product is marketed as validated and GAMP 5-aligned. Scilife itself is not a regulated entity, but it delivers validation packages to customers, which means documented releases, validation environments (the "prod-val3" hostname), change control and audit trails in the product. Expect release documentation overhead and slower release cadence than a typical SaaS, but no formal safety cases.

**Verdict:** **CAUTION** (moderate validation overhead)

---

## Section 10: On-Call

No posting mentions on-call. The Senior Software Engineer (LAMP) posting asks engineers to "Troubleshoot complex production issues, optimizing server configurations (Linux, Apache)", and there is a dedicated IT Ops Manager. Customers are in EMEA, the Americas and Latin America (Soluciones GxP partnership, 2025), and the team spans India to the US, so follow-the-sun coverage is likely more than formal on-call rotations; for a ~90-person company with a small engineering team, senior backend engineers are probably the escalation path.

**Verdict:** **UNVERIFIED** (likely CAUTION for backend roles)

---

## Section 11: Interview Process

From Glassdoor (9 interview reviews, all roles, via CDP) and the Scilife careers FAQ.

| Metric | Value |
|---|---|
| Difficulty | 2.3 / 5 (Glassdoor) |
| Positive experience | 33% (44% negative) |
| Average duration | ~34 days (fastest 21 days, Functional Analyst) |
| Rounds | 3-4 |

Steps (careers FAQ): HR screening (culture fit) → technical interview with the hiring manager → practical assignment "if applicable" → final leadership interview with the VP or department head (sometimes the CEO). Several candidates were first asked to record a 2-3 minute self-introduction video; one sales candidate was ghosted after submitting it (Glassdoor, Jul 2024), and a Product Designer candidate was given an "unpaid case study" (Glassdoor, Jan 2025, Barcelona). The AI/ML Engineer candidate (Glassdoor, Aug 2025, New York) reported a 15-minute HR call plus the video. No evidence of LeetCode-style rounds; experience and assignment based.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | PASS: pure eQMS SaaS |
| Not consulting | PASS: product company (spun out of the QbD consultancy, partners do implementation) |
| Profitable | FAIL: −€3.09M in 2025, loss doubling yearly |
| Employee count | ~90, 5 in Germany |
| English-speaking | PASS |
| Local entity + engineering contracts | FAIL: no German entity; EOR employment only |
| Location / work model | Fully remote, within your country; no Munich office |
| Glassdoor | FAIL: 3.5 on 11 English reviews, 69% recommend; no Germany data |
| Kununu | NONE: no profile |
| Salary | UNVERIFIED, likely BELOW (Spain/India-weighted pay base, no equity) |
| AI/ML content | Small applied LLM/RAG team in Python; core product non-AI |
| Computer-language/Tech-stack | PHP-centric LAMP on AWS; Python only in AI & Data Analytics |
| No on-call | UNVERIFIED |
| WLB / Stability | WLB 3.8 and flexible; stability FAIL (equity €1.59M against €7.69M capital, PE-dependent) |
| Works council / collective agreement | NONE (EOR) |
| Regulated industry | CAUTION: GxP validation overhead |
| Review themes | Remote flexibility praised; micromanagement, unfair dismissals and India/Europe bias recur |
| PE ownership | Five Elms Capital control since Jun 2024; new CEO with a growth mandate; "shifting from start-up mentality to corporate enterprise" |

---

## Section 13: Verdict

**Exclude.**

**Strengths:** Genuinely remote with flexible hours and a generous leave policy, a focused vertical SaaS product with established pharma customers, an English working language, a growth-equity owner that specialises in software, and an AI & Data Analytics team doing applied LLM/RAG work on regulated documents. Engineering leadership (CTO, VP Engineering) is itself based in Germany.

**Hard blockers:**

1. **No direct employment in Germany.** Scilife has entities only in Belgium, Spain and the US and hires everyone else through an Employer of Record. A Munich-based engineer would be employed by a third-party EOR, with no Scilife works council, no German employer of record of its own, and dismissal decisions taken abroad.
2. **Wrong main language.** The core product is PHP 8.2 / MySQL / MongoDB on Elastic Beanstalk. Python exists only in the AI & Data Analytics team, which has hired at most one or two engineers.
3. **Not profitable and getting less so.** Losses went from €0.2M (2022) to €3.1M (2025); equity is down to €1.59M against €7.69M of subscribed capital, below the Belgian alarm-bell threshold, so continuity depends on Five Elms putting in more money.
4. **Weak and thin review base.** Glassdoor 3.5 on 11 reviews (69% recommend), with allegations of mobbing, unfair dismissals and unpaid overtime (2023-2024) and of bias against the Indian engineering team (Aug 2026). No Kununu, no Blind.
5. **No engineering opening.** Current vacancies are sales-only.

**Secondary concerns:** GxP validation overhead on releases; likely informal production support across a global team; compensation base anchored in Spain and India with no equity; culture in transition under a PE-appointed CEO; one-third positive interview experience with video-first screening.

**Recommendation:** Exclude. The EOR-only presence in Germany and the PHP core each disqualify on their own, and the finances add a third reason. No further research is warranted unless Scilife opens a German GmbH and posts a Python-centred Staff role in its AI & Data Analytics team, and even then the loss trend would need to reverse.

---

## Sources

- [Scilife careers page and FAQ (curl)](https://www.scilife.io/jobs)
- [Scilife About us (curl)](https://www.scilife.io/about-us)
- [Scilife legal notice (curl)](https://www.scilife.io/legal-notice)
- [Scilife privacy policy, KBO number and AI logging clause (curl)](https://www.scilife.io/privacy-policy)
- [Scilife press releases (curl)](https://www.scilife.io/press-releases)
- [Scilife and Five Elms Capital partnership, Jun 2024 (curl)](https://www.scilife.io/press-releases/scilife-five-elms-capital-partnership)
- [Scilife appoints Sebastien Sepierre as CEO, Sep 2024 (curl)](https://www.scilife.io/press-releases/new-ceo-sebastien-sepierre)
- [Scilife llms.txt (curl)](https://www.scilife.io/llms.txt)
- [Scilife AI/ML Engineer posting](https://www.scilife.io/jobs/ai-ml-engineer)
- [Scilife AI/ML Engineer on Arc.dev (curl)](https://arc.dev/remote-jobs/j/scilife-ai-ml-engineer-nb9253alis)
- [Scilife Senior Software Engineer (LAMP Stack) on Weekday (curl)](https://jobs.weekday.works/scilife-nv-senior-software-engineer-(lamp-stack))
- [FinSMEs: Scilife receives growth investment from Five Elms](https://finsmes.com/2024/06/scilife-receives-growth-investment-from-five-elms-capital.html)
- [PR Newswire: Scilife secures growth investment from Five Elms](https://prnewswire.com/news-releases/scilife-secures-growth-investment-from-five-elms-capital-to-propel-smart-quality-innovation-302167145.html)
- [Techleap: Scilife gains investment from Five Elms](https://finder.techleap.nl/news/feed/scilife-gains-investment-from-five-elms)
- [QbD Group: Scilife rebranding from QbD Software](https://qbdgroup.com/en/news/introducing-scilife-qbd-softwares-major-rebranding-initiative)
- [NorthData: Scilife N.V. (CDP)](https://www.northdata.de/Scilife)
- [Companyweb: Scilife SA financial data (CDP)](https://www.companyweb.be/en/0675685469/scilife)
- [NBB CBSO published deposits API (curl)](https://consult.cbso.nbb.be/api/rs-consult/published-deposits?page=0&size=10&enterpriseNumber=0675685469)
- [NBB Consult: Scilife filings](https://consult.cbso.nbb.be/consult-enterprise/0675685469)
- [Glassdoor overview (CDP)](https://www.glassdoor.de/%C3%9Cberblick/Arbeit-bei-Scilife-EI_IE8308116.11,18.htm)
- [Glassdoor reviews, English (CDP)](https://www.glassdoor.de/Bewertungen/Scilife-Bewertungen-E8308116.htm?filter.iso3Language=eng&sort.sortType=RD&sort.ascending=false)
- [Glassdoor interviews (CDP)](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/Scilife-Fragen-im-Vorstellungsgespr%C3%A4ch-E8308116.htm?filter.iso3Language=eng)
- [Glassdoor salaries (CDP)](https://www.glassdoor.de/Gehalt/Scilife-Geh%C3%A4lter-E8308116.htm)
- [Kununu: no Scilife profile (curl 405, CDP 404)](https://www.kununu.com/de/scilife)
- [levels.fyi: no Scilife page (CDP 404)](https://www.levels.fyi/companies/scilife/salaries)
- [Teamblind: no Scilife page (CDP)](https://www.teamblind.com/company/Scilife)
- [Great Place to Work Germany search (CDP)](https://www.greatplacetowork.de/suche?q=scilife)
- [Flexa: Scilife profile](https://flexa.careers/companies/scilife)
- [LinkedIn: Scilife about (CDP)](https://www.linkedin.com/company/scilife/about/)
- [LinkedIn: Scilife people, Germany filter (CDP)](https://www.linkedin.com/company/scilife/people/?facetGeoRegion=101282230)
- [GitHub: scilife organisation API](https://api.github.com/orgs/scilife)
- [Google DNS-over-HTTPS: demo.scilife.io CNAME chain](https://dns.google/resolve?name=demo.scilife.io&type=CNAME)
- [Nominatim: Kantersteen 47, Brussels](https://nominatim.openstreetmap.org/search?q=Kantersteen+47,+1000+Brussels&format=json&addressdetails=1&limit=1)
- [Nominatim: Bruxelles-Central station](https://nominatim.openstreetmap.org/search?q=Bruxelles-Central&format=json&limit=5&countrycodes=be)
- [CB Insights: Scilife competitors](https://www.cbinsights.com/company/scilife/alternatives-competitors)
- [G2: Scilife](https://www.g2.com/products/scilife/discuss)
- [rfp.wiki: Scilife vendor review](https://www.rfp.wiki/vendors/scilife)
- [TrustRadius: Scilife](https://www.trustradius.com/products/scilife/details)
