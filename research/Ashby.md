# Ashby - Full Research Report

_Researched: 2026-09-23_

> **Critical Disqualifiers** (full report follows for completeness):
> 1. **No German legal entity.** Ashby's only verified entities are the US parent (Ashby, Inc., San Francisco) and a UK subsidiary created in January 2026 (ASHBY TECHNOLOGIES UK LTD, Companies House 16940261). NorthData has no Ashby GmbH or German branch registration. Germany-based staff therefore cannot be on a contract with a German Ashby entity. This points to an Employer-of-Record setup, which the criteria exclude.
> 2. **TypeScript everywhere, no Python.** Ashby's stated stack is "TypeScript (frontend & backend), Node.js, React, Apollo GraphQL, Postgres, Redis". Python is not used anywhere in the product stack.
> 3. **Mandatory on-call.** Ashby's own platform-engineering postings say: "all engineers are on call in a follow-the-sun model."
> 4. **VC-funded, not profitable.** Series D (July 2025). Efficient (burn multiple under 1x), but still burning cash and funded by venture capital. It is not the mature, profitable company the criteria ask for.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | Late 2018 (~8 years); public launch September 2022 after four years in stealth |
| Employees | ~491 (Tracxn, 31 Jul 2026); 220 at the Series D in July 2025 ("across 20+ countries"). Headcount has more than doubled in a year |
| Revenue | Not disclosed. ~$28.2M ARR est. for 2024 (Latka); ARR +135% YoY at the Series D; job ads (Sept 2026) say "tens of millions in ARR, growing >100% year over year" |
| Profitability | Not profitable. Burn multiple "under 1x"; "most of Series C capital untouched" at the Series D - **FAIL** |
| Ownership | Private, VC-backed (Y Combinator alumnus; Alkeon, Lachy Groom, F-Prime, Elad Gil) |
| Software-centric | Pure SaaS product (applicant tracking system plus CRM, scheduling, analytics, onboarding) - **PASS** |

**Key People**

- **Benjamin (Benji) Encz**: co-founder and CEO
- **Abhik Pramanik**: co-founder and VP of Engineering (writes the engineering job ads himself)
- **Colin Howe**: Head of EMEA Engineering (UK-based)

Both co-founders are directors of the new UK subsidiary.

**Funding History**

| Date | Round | Amount | Lead / notes |
|---|---|---|---|
| ~2019-2021 | Seed + Series A | ~$18M combined (derived: ~$70M total at the Series C minus the B and C) | Seed led by Lachy Groom; YC |
| Sep 2022 | Series B | $21.5M | Led by F-Prime; Elad Gil, Lachy Groom, Semper Virens, Base Case, Gaingels, 100+ customers/operators |
| Jun 2024 | Series C | $30M | Led by Lachy Groom; F-Prime, Elad Gil, YC. Revenue 6x since the Series B; 1,300+ customers |
| Jul 2025 | Series D | $50M | Led by Alkeon (Mark McLaughlin), co-led by Lachy Groom; F-Prime, Elad Gil, Gaingels. Valuation "2x Series C" (figure not disclosed); 2,700+ customers |
| **Total** | | **~$120-142M** | Sources differ: Crunchbase/Tracxn ~$130.6M, Multiples $142.5M |

**Business Model:** Ashby sells an all-in-one recruiting platform (ATS, candidate CRM and sourcing, interview scheduling, analytics, AI-assisted workflows) by subscription. In 2026 it expanded into HR/talent management: People Workflows for onboarding (May 2026), plus performance-management products. Customers include Notion, Linear, Shopify, Snowflake, Reddit and Deel. The company is not consulting-adjacent. It does have an implementation/professional services function ("Strategic Implementation Specialist", "Solutions Architect"), but engineering roles build the product itself.

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **Ashby, Inc.** (parent) | US (Delaware corp., per Bloomberg profile) | 548 Market Street, San Francisco, CA | Recruiting software |
| **ASHBY TECHNOLOGIES UK LTD** | Companies House 16940261, incorporated 2 Jan 2026 | Birchin Court, 5th Floor, 19-25 Birchin Lane, London EC3V 9DU | SIC 62012 "Business and domestic software development"; directors B. D. Encz and A. B. Pramanik; company secretary Zedra CoSec (UK) Ltd |
| **German entity** | **None found** | - | - |

**Verification:** NorthData searches for "Ashby", "Ashby GmbH", "Ashby Technologies", "Ashby Technologies GmbH", "Ashby Deutschland" and "Ashby Europe" (all result pages) return no German registration for this company. The only German hit is "Ashby UG" in Weingarten (Amtsgericht Ulm HRB 742355), which is unrelated. The UK subsidiary was only set up in January 2026. Before that, Ashby ran its UK/EMEA workforce (the Head of EMEA Engineering and several UK engineers) without a local entity. That is the classic Employer-of-Record pattern.

Ashby does employ engineers in Germany: its team page lists at least two Germany-flagged engineers. It also advertises Germany as an eligible location (Berlin/Stuttgart for sales; "Germany" for the Staff Platform Engineer and Engineering Manager EU roles). Without a German GmbH or registered branch, these hires must go through an EOR or a contractor setup. Which EOR vendor Ashby uses is **UNVERIFIED**; no public source names it. One indirect sign: the benefits line reads "In other countries, we provide high-quality supplemental health insurance." That is typical EOR wording.

**Verdict:** **FAIL** - no German entity; a Germany-based hire would almost certainly be employed through an EOR, not on a direct German Arbeitsvertrag with Ashby.

---

## Section 3: Office Location

- **Office address:** No office in Germany. The HQ address (548 Market Street, San Francisco) is a registered/mail address. Ashby is fully remote ("remote-first company with colleagues working from 24 different countries").
- **Nearest public transit:** N/A (no physical office).
- **Work model:** Fully remote. In-person meetups "at least twice a year, once as a department and once as a company", plus a small budget for local meetups.
- **Remote eligibility for Germany:** Mixed signals.
  - The **Staff Platform Engineer - EU** and **Engineering Manager - EU** postings explicitly list "Germany".
  - The **Senior/Staff Software Engineer, Product Engineering - EU** postings on Ashby's own board list Berlin but not "Germany" as a country (Spain, Italy, Switzerland, Croatia, Ireland, Sweden, Romania, Portugal, Estonia, Berlin).
  - LinkedIn shows the Product Engineering roles as "Munich" and "Remote (DE)" (reposted 3-5 days ago).
  - Confirm eligibility for a Munich-based hire with the recruiter.

---

## Section 4: Reviews

**GPTW:** No Great Place to Work Germany certification or listing found (greatplacetowork.de search returned nothing for Ashby). No other GPTW country certification found.

#### Glassdoor

Retrieved via Chromium/CDP (logged-in session); sub-ratings extracted from the page state. All 18 reviews were read (4 pages).

| Metric | Global | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | 4.7 (18 reviews) | no reviews (0) | no reviews (0) | 4.8 (4 reviews) |
| **WLB** | 4.8 | - | - | n/a |
| **Culture & Values** | 5.0 | - | - | n/a |
| **Comp & Benefits** | 4.3 (down 8% in last 12 months) | - | - | n/a |
| **Career Opportunities** | 4.9 | - | - | n/a |
| **Senior Management** | 5.0 | - | - | n/a |
| **Diversity & Inclusion** | 4.9 | - | - | n/a |
| **% Recommend** | 100% | - | - | 100% |
| **CEO Approval** | 100% | - | - | n/a |
| **Business Outlook** | 100% positive | - | - | 100% positive |

The global figures are **directional only**: 18 reviews over four years for a ~490-person company. The score looks unusually uniform (no review below 3 stars). There are no reviews from Germany or Munich, and only four from software engineers, located in Toronto, New Delhi and unspecified locations.

#### Kununu

Tried the slugs `ashby`, `ashbyhq`, `ashby1` and `ashby-technologies` (curl returned HTTP 405; Chromium/CDP returned 404), plus the Kununu employer search for "Ashby" via CDP (no results). **No Kununu profile.** This fits a company with no German entity.

- **Overall score:** N/A
- **Recommendation rate:** N/A
- **Total reviews:** 0
- **Kununu Top Company:** NO

#### Blind / Teamblind

`teamblind.com/company/Ashby/` returns "Page not found" (checked via CDP), and a web search found no Ashby company page or substantive threads. **No Blind coverage.**

#### Review Themes (2022-2026)

**Positives:**
- Leadership consistently praised: "Great leadership in place who know what they're doing", "Top notch leadership", "Leadership truly invests in its employees".
- Talent density and low ego: "Smart, driven, and humble employees", "A great team of rigorous engineers who don't suffer from hero syndrome", "refreshingly low ego and down-to-earth culture".
- Transparency: "our financials are visible for everyone within the business, founders regularly communicate their vision".
- Product-market fit and momentum: "Really strong product market fit", "Customers Love Ashby", "Lots of runway".
- Remote culture done well: "Great culture, especially for a remote company". The engineering JD cites fewer than 2 hours of meetings per week and unlimited PTO that is actually used.

**Negatives:**
- Startup growing pains: "Regular growing pains for scaling organization", "some systems and processes could be ironed out", "scrappy at times", "a bit understaffed ... in some key functions".
- Fully remote and isolating for some: "100% remote so there aren't a ton of opportunities to interact with people outside my department".
- Steep onboarding: "Onboarding is a steep learning curve."
- Self-selection and churn by design: "those who don't fit that usually wash out". The JD itself says "Not everyone succeeds in our culture".
- Comp & Benefits sub-score fell 8% in the past 12 months.
- No review touches the criteria's hard red flags. The only on-call signal comes from the job postings (see Section 10), not from reviews.

#### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | No evidence. Senior Management 5.0, CEO approval 100%. |
| 24/7 Work Expectation | Not in reviews. The JD states "work regular hours", "marathon, not a sprint", with occasional launch intensity. Follow-the-sun on-call applies (Section 10). |
| Internal Surveillance | No evidence. The AI tooling post says engineers have unlimited token budgets "but are not measured on it". |
| Fear-driven Management | No evidence. There is a high-bar culture ("we'd rather an engineer fail a bit and coach up their skills"; "those who don't fit... wash out"), which is performance pressure, not fear. |
| Communication Breakdown | No evidence. Transparency and "deliberate communication" are recurring praise. |
| Unpaid Overtime | No evidence. |
| Silent Firings | No direct evidence. Watch the "wash out" comment; the 30/60/90-day reviews imply early performance filtering. |
| Work-Life Balance issues | None reported (WLB 4.8); unlimited PTO reportedly used (~30 days/year by some engineers). |

**Risk level: LOW.** No systemic toxicity signals. The main caveat is the small, possibly self-selected review base (18 reviews, none below 3 stars) and a demanding, high-autonomy culture that openly filters out people who do not fit. That is localized pressure, not dysfunction.

---

## Section 5: Compensation

#### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| Ashby job board / LinkedIn (EU, employer-stated) | Senior Software Engineer, Product Engineering - EU | €108K-145K | options (grant undisclosed) | none stated | €108K-145K + options | posted range |
| Ashby job board / LinkedIn (EU, employer-stated) | Staff Software Engineer, Product Engineering - EU | €154K-250K | options (grant undisclosed) | none stated | €154K-250K + options | posted range |
| Ashby job board (EU, employer-stated) | Staff Platform Engineer - EU | €154K-250K | options | none stated | €154K-250K + options | posted range |
| Ashby job board (EU) | Engineering Manager - EU | €110K-185K | options | bonus offered | - | posted range |
| levels.fyi | Software Engineer | locked | - | - | - | "2 more submissions needed to unlock"; no Germany data |
| Glassdoor | Software Engineer (Germany/Munich) | no data | - | - | - | 0 |

It is not stated whether the EU ranges are gross employer-contract salaries or EOR-paid amounts. The same bands apply across all EU countries (Romania through Switzerland).

**Munich reference (large, profitable local employers, Senior SWE):** median base ~€85-95K, 75th percentile ~€100-110K, 90th percentile ~€120-130K. This is a market reference derived from prior research reports in this project, not Ashby-specific.

#### Equity / Stock

Pre-IPO stock options with an unusually generous **10-year post-departure exercise window**. The Series D was at 2x the Series C valuation (amount undisclosed). The options are illiquid, with no known secondary programme. Their value depends on a future exit, and later rounds will dilute them. Note: German tax treatment of US-parent options for an EOR-employed person is complex (taxed at exercise under the Dry-Income rules unless structured under §19a EStG, which requires a German employer).

#### Verdict

**ABOVE** on cash. Even the bottom of the Senior EU band (€108K) is at or above the Munich 75th percentile for base, and the Staff band (€154-250K) is far above local large-employer levels. The caveats: bands are employer-stated with no verified offers, and they are probably paid through an EOR.

---

## Section 6: AI/ML & Tech Stack Fit

#### AI Strategy

Ashby markets itself as an "AI-powered" hiring platform. Its AI features are applied LLM features inside the product: AI-assisted application review and candidate screening, AI notetaker/interview summaries, AI-drafted emails, and AI search/sourcing (TechCrunch, June 2024). Internally, AI is a productivity lever for engineers. Over 50% of production code has been AI-generated since August 2025, using Cursor, Claude, Codex and CodeRabbit plus in-house review and auto-triage tools. There is no evidence of in-house model training, an ML platform/MLOps team, or an applied-ML engineering track. No posting targets AI/ML engineers.

#### Tech Stack

Derived from current Ashby job postings (primary), the Ashby engineering blog ("AI, Ashby Engineering, and the Future"), and the LinkedIn postings saved on 2026-09-23.

| Category | Technologies |
|---|---|
| **Primary language(s)** | TypeScript (frontend and backend), Node.js |
| **AI/ML** | Third-party LLM APIs for product features; Claude, Cursor, Codex, CodeRabbit for engineering productivity. No training stack |
| **Cloud** | AWS (100% cloud) |
| **Infrastructure** | Kubernetes (per platform JD), Datadog, Sentry; CI/CD ~10 min, 15+ deploys/day; feature flags, canary deploys |
| **Data** | PostgreSQL, Redis; in-house recruiting DSL-to-SQL query compiler; planned event-driven architecture and data warehouse |
| **Other** | React, Apollo GraphQL; in-house workflow engine, policy engine, analytics modelling/query language, design system |

The JD says prior stack experience is not required ("a love of typed languages is helpful"). Engineers switching from Swift, Kotlin and Windows are cited.

#### Current Open Roles

Verified live on 2026-09-23 via Ashby's public job-board API (`api.ashbyhq.com/posting-api/job-board/ashby`, 71 open roles) and LinkedIn (CDP; "Reposted 3-5 days ago", apply button active).

| Role | Division/Team | Level | Key Tech | Link |
|---|---|---|---|---|
| Senior Software Engineer, Product Engineering - EU | EMEA Engineering | Senior (€108-145K) | TypeScript, React, GraphQL, Node.js, Postgres | [Ashby](https://jobs.ashbyhq.com/ashby/3b9b0141-86e7-46b2-b6b4-ed039b84cdc4) / [LinkedIn Remote DE](https://www.linkedin.com/jobs/view/4403621481/) / [LinkedIn Munich](https://www.linkedin.com/jobs/view/4403399909/) |
| Staff Software Engineer, Product Engineering - EU | EMEA Engineering | Staff (€154-250K) | TypeScript, React, GraphQL, Node.js, Postgres | [Ashby](https://jobs.ashbyhq.com/ashby/c3c7125d-7883-4dff-a2bf-f5a55de4a364) / [LinkedIn Remote DE](https://www.linkedin.com/jobs/view/4403613672/) / [LinkedIn Munich](https://www.linkedin.com/jobs/view/4403603917/) |
| Staff Platform Engineer - EU (lists Germany) | EMEA Engineering | Staff (€154-250K) | AWS, Kubernetes, Postgres, TypeScript, Datadog; **on-call follow-the-sun** | [Ashby](https://jobs.ashbyhq.com/ashby/fa001346-ea81-41b2-bfbe-2271d3faac1a) |
| Staff Design Engineer - EU | EMEA Engineering | Staff (€154-250K) | TypeScript, React, design systems (front-end) | [Ashby](https://jobs.ashbyhq.com/ashby/87b96eef-edc1-4de4-adb6-d460126d02f8) |

**Verdict:** A TypeScript/Node.js/React/GraphQL product-engineering stack on AWS and Postgres, where AI means LLM API features in the product and heavy AI-assisted coding. This is applied SaaS product engineering, not AI/ML platform or MLOps work, and Python is absent. The Staff Platform Engineer role is the closest match to infrastructure profile, but it is TypeScript/Kubernetes/AWS and carries on-call. Poor fit on both the Python-primary and AI/ML-platform criteria.

---

## Section 7: Language

All postings are in English. None mentions German, except sales roles targeting DACH/French-speaking markets. The engineering team is distributed across 24 countries and works asynchronously in writing, in English.

**Verdict:** **PASS**

---

## Section 8: Stability

#### Financial Position

Private; no filed accounts (no German or UK filings yet; the UK subsidiary is from January 2026 and has not filed accounts). Known indicators:

- ARR ~$28M (2024 est.); +135% YoY at the Series D in July 2025; still "growing >100% year over year" per September 2026 postings. This implies ARR of roughly $60-90M in 2026 ("tens of millions").
- Burn multiple under 1x (Series D announcement); "most of Series C capital untouched" as of July 2025.
- Customers: 500 (Sep 2022) → 1,300 (Jun 2024) → 2,700+ (Jul 2025) → "over 2,500" in current postings (probably stale boilerplate).
- Job ads claim "many years of runway".
- Trend: improving. Growth is fast and efficient, but the company is not profitable.

#### Financial Runway

No filed balance sheet exists (NorthData and Bundesanzeiger not applicable). The cash estimate below is derived from funding totals and public burn statements.

**Gross burn (2026 estimate)**

| Cost line | Annual estimate |
|---|---|
| Staff (~491 employees × ~$180K avg fully-loaded, US-heavy remote mix) | ~$88M |
| Cloud (AWS), SaaS tooling, AI token budgets | ~$8M |
| Sales & marketing programmes, annual user conference, events | ~$10M |
| G&A, EOR fees, legal, offsites (2 in-person meetups/year) | ~$7M |
| **Total gross burn** | **~$113M/year** |

**Revenue offset**

| Revenue source | Est. annual inflow |
|---|---|
| Subscription revenue (2026, ARR ~$60-90M, recognised ~$55-80M) | ~$55-80M/year |
| **Total revenue offset** | **~$55-80M/year** |

**Scenarios**

| Scenario | Net burn | Cash at hand | Runway | Next round needed by |
|---|---|---|---|---|
| Optimistic (ARR ~$90M, near breakeven by 2027) | ~$25M/year | ~$100M | 4+ years (or self-sustaining) | not needed |
| Base case | ~$40M/year | ~$90M | ~2.3 years | ~late 2028 |
| Stress (growth halves, hiring continues) | ~$60M/year | ~$80M | ~1.3 years | ~early 2028 |

**Cash figure used:** ~$80-100M as of mid-2026. This is derived, not observed: ~$130-142M total raised; "most of Series C untouched" as of July 2025 plus the $50M Series D; minus an assumed ~$20-40M net burn since then while headcount doubled. No audited cash figure is public.

#### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| - | None found | - | TrueUp, Blind layoff tracker, press and review searches show no Ashby layoffs. Headcount grew from 220 to ~491 in a year |

**Verdict:** **CAUTION** - healthy, capital-efficient, fast-growing, with no layoffs. But it is still VC-funded and not profitable, and headcount doubled in a year, a pace that often leads to later corrections. It does not meet the "mature, profitable company" criterion.

---

## Section 9: Regulated Industry

HR-tech SaaS processing candidate personal data. GDPR applies, with SOC 2/ISO 27001-style customer security expectations. The EU AI Act classifies AI systems used in recruitment and candidate screening as **high-risk** (Annex III), with obligations phasing in from August 2026. This will add documentation, bias-testing and human-oversight requirements to Ashby's AI features for EU customers. Still, this is far lighter than BaFin, medical-device or safety-critical regimes. Deploy velocity (15+ deploys/day) shows no formal release gates.

**Verdict:** **PASS** (low regulatory burden; watch EU AI Act compliance work on AI screening features)

---

## Section 10: On-Call

The Staff Platform Engineer postings (EU, UK, Americas) state verbatim: *"We take developer experience and reliability seriously: all engineers are on call in a follow-the-sun model, and everyone contributes to developer tooling."* The Product Engineering postings add: *"Customer issues and investigations are distributed across the team, including our high-level ICs."* A follow-the-sun rotation across the Americas, EMEA and APAC should keep pages within European working hours for an EMEA engineer. It is still a formal on-call duty for every engineer, product engineers included.

**Verdict:** **FAIL** - company-wide on-call for all engineers (follow-the-sun softens the out-of-hours impact; confirm rotation frequency and whether it is limited to business hours)

---

## Section 11: Interview Process

| Metric | Value |
|---|---|
| Difficulty | 3.1 / 5 (Glassdoor, 115 interview reports) |
| Positive experience | 26% (55% negative) |
| Average duration | ~13 days |
| Rounds | 3 (optionally preceded by a 30-min recruiter screen) |

Process as stated in the engineering postings:

1. Intro call with the hiring manager (15-30 min).
2. Technical screen pairing in Ashby's actual codebase (1 h, live).
3. Three non-coding interviews on product thinking, technical design and infrastructure (Platform: design, incident debugging, infrastructure), 3 h 15 min in total, which can be split across days.

The candidate meets 4-6 engineers and gets written guidance for each round and feedback on rejection.

**No LeetCode or whiteboard exercises.** The process is experience- and product-thinking-focused.

Glassdoor experiences are notably negative (only 26% positive) for a company that sells interview software. Recurring complaints:

- The hiring-manager screen is essentially "pick a single project and walk me through it", and the outcome depends on picking the "right" project.
- Rejection for "poor signals regarding product thinking" after the first screen.
- A rejection email in September 2026 that also invited the candidate to a one-way video interview.

Several candidates credited the useful post-rejection feedback. Product thinking (writing specs, making product decisions) is a hard filter for engineering roles.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | PASS - pure SaaS recruiting/HR platform |
| Not consulting | PASS - product engineering; separate implementation/PS team exists but engineers build the product |
| Profitable | FAIL - VC-funded (Series D, ~$130-142M raised), efficient (burn multiple <1x) but loss-making |
| Employee count | ~491 (201-500 band), doubled in 12 months |
| English-speaking | PASS - English-only, fully distributed |
| Local entity + engineering contracts | **FAIL** - no German entity; only US parent + UK Ltd (Jan 2026); German hires presumably via EOR |
| Location / work model | Fully remote; Germany eligibility varies per posting |
| Glassdoor | 4.7 global (18 reviews), WLB 4.8, CEO 100%; directional only; 0 Germany/Munich reviews |
| Kununu | No profile |
| Salary | ABOVE - EU Senior €108-145K, Staff €154-250K + options (10-year exercise window) |
| AI/ML content | Weak - LLM-API product features and AI-assisted coding; no ML platform/MLOps work |
| Computer-language/Tech-stack | **FAIL** - TypeScript/Node.js/React/GraphQL; no Python |
| No on-call | **FAIL** - "all engineers are on call in a follow-the-sun model" |
| WLB / Stability | WLB strong (reviews, <2h meetings/week); stability CAUTION (VC-backed, no layoffs, strong growth) |
| Regulated industry | PASS - GDPR, EU AI Act high-risk classification for screening AI |
| Review themes | Positive: leadership, transparency, talent density, remote culture. Negative: growing pains, fully remote isolation, high-bar "wash out" culture |
| Interview process | No LeetCode, but 26% positive experience; heavy product-thinking filter |

---

## Section 13: Verdict

**Exclude.** Ashby is a well-run, fast-growing, well-reviewed company, but it fails several hard criteria at once.

**Strengths:**

- Genuinely strong engineering culture: very little process, fewer than 2 hours of meetings a week, engineers own features end to end, 15+ deploys a day.
- Leadership and transparency are praised everywhere (CEO approval 100%, Senior Management 5.0).
- Capital-efficient growth (burn multiple under 1x, ARR growing more than 100% a year) and no layoffs.
- Cash compensation well above Munich market levels, with a candidate-friendly 10-year option exercise window.
- No LeetCode interviews.

**Hard blockers:**

1. **No German legal entity.** The corporate structure is Ashby, Inc. (US) plus ASHBY TECHNOLOGIES UK LTD (Companies House 16940261, formed January 2026). NorthData shows no Ashby GmbH or German branch. A Munich-based hire would be employed through an Employer-of-Record rather than on a direct German contract. The criteria rule this out, and it also blocks §19a EStG-friendly option taxation.
2. **No Python.** The product is TypeScript front to back (Node.js, React, Apollo GraphQL, Postgres, Redis). The criteria require Python as the main language; Ashby's postings do not mention Python at all.
3. **Mandatory on-call.** Ashby's own postings say "all engineers are on call in a follow-the-sun model." Follow-the-sun limits night pages, but on-call is explicitly universal.
4. **Not profitable.** A Series D, VC-funded company (~$130-142M raised, estimated net burn ~$25-60M a year) with an estimated 2-4 years of runway. This is not the mature, profitable, long-term employer the criteria target.

**Secondary concerns:**

- The AI work is LLM-API product features and AI-assisted coding, not AI/ML platform engineering.
- The review base is tiny (18) and uniformly positive, with no German reviews.
- Interview experience is 26% positive, with product thinking as a hard filter.
- The high-bar culture openly filters people out ("those who don't fit that usually wash out").
- Headcount doubled in a year.
- The Product Engineering EU roles do not list Germany as an eligible country on Ashby's own board.

**Recommendation:** Do not apply. Even if a German contract were offered, the TypeScript-only stack and universal on-call would each disqualify the role on their own. For Ashby to become viable it would need:

- a German GmbH offering direct contracts,
- a Python-centric or AI/ML-platform team,
- on-call-free roles.

None of these is on any public roadmap. No further research is warranted. Do not re-surface Ashby vacancies.

---

## Section 14: Sources

- [Ashby - Announcing Ashby's $50 Million Series D](https://www.ashbyhq.com/blog/culture/series-d)
- [Ashby - Announcing Ashby's $30M Series C](https://www.ashbyhq.com/blog/culture/series-c)
- [PR Newswire - Ashby Announces $30M Series C](https://www.prnewswire.com/news-releases/ashby-announces-30m-series-c-302161967.html)
- [PR Newswire - Ashby Launches Publicly With over 500 Customers (Series B)](https://www.prnewswire.com/news-releases/all-in-one-recruiting-platform-ashby-launches-publicly-with-over-500-customers-301622759.html)
- [TechCrunch - Ashby lands $21.5M to automate key aspects of recruiting](https://techcrunch.com/2022/09/13/ashby-21-5-million-recruiting-platform-startup-raises/)
- [TechCrunch - Ashby injects recruiting with a dose of AI](https://techcrunch.com/2024/06/03/ashby-injects-recruiting-with-a-dose-of-ai/)
- [American Bazaar - Ashby secures $50 million](https://americanbazaaronline.com/2025/07/23/ai-hiring-platform-ashby-secures-50-million-to-streamline-recruitment-465454/)
- [Reworked - Ashby Announces $30M Series C](https://www.reworked.co/the-wire/ashby-announces-30m-series-c/)
- [Hunt Scanlon - Recruiting Platform Ashby Secures $30 Million](https://huntscanlon.com/recruiting-platform-ashby-secures-30-million-in-funding/)
- [Tracxn - Ashby company profile](https://tracxn.com/d/companies/ashby/__hzSC-b0F7MQYYHj8ElwlD-CZAzAkkXzZNTco38f78JM)
- [Crunchbase - Ashby](https://www.crunchbase.com/organization/ashby)
- [PitchBook - Ashby profile](https://pitchbook.com/profiles/company/438877-63)
- [Multiples - Ashby valuation and funding](https://multiples.vc/private-comps/ashby)
- [Latka - Ashby revenue estimate](https://getlatka.com/companies/ashbyhq.com)
- [CB Insights - Ashby](https://www.cbinsights.com/company/ashby)
- [Bloomberg - Ashby Inc profile](https://www.bloomberg.com/profile/company/2156170D:US)
- [Y Combinator - Ashby](https://www.ycombinator.com/companies/ashby)
- [Companies House - ASHBY TECHNOLOGIES UK LTD (16940261)](https://find-and-update.company-information.service.gov.uk/company/16940261) (curl)
- [Companies House - 16940261 officers](https://find-and-update.company-information.service.gov.uk/company/16940261/officers) (curl)
- [Companies House - 16940261 persons with significant control](https://find-and-update.company-information.service.gov.uk/company/16940261/persons-with-significant-control) (curl)
- [NorthData - search "Ashby"](https://www.northdata.com/search?query=Ashby) (curl, all listing pages)
- [NorthData - search "Ashby Technologies GmbH"](https://www.northdata.com/search?query=Ashby%20Technologies%20GmbH) (curl)
- [NorthData - Ashby UG, Weingarten (unrelated)](https://www.northdata.com/Ashby%20UG,%20Weingarten/Amtsgericht%20Ulm%20HRB%20742355)
- [Ashby - Meet the Team](https://www.ashbyhq.com/team)
- [Ashby public job board API](https://api.ashbyhq.com/posting-api/job-board/ashby?includeCompensation=true) (curl)
- [Ashby - Senior Software Engineer, Product Engineering - EU](https://jobs.ashbyhq.com/ashby/3b9b0141-86e7-46b2-b6b4-ed039b84cdc4)
- [Ashby - Staff Software Engineer, Product Engineering - EU](https://jobs.ashbyhq.com/ashby/c3c7125d-7883-4dff-a2bf-f5a55de4a364)
- [Ashby - Staff Platform Engineer - EU](https://jobs.ashbyhq.com/ashby/fa001346-ea81-41b2-bfbe-2271d3faac1a)
- [Ashby - Staff Design Engineer - EU](https://jobs.ashbyhq.com/ashby/87b96eef-edc1-4de4-adb6-d460126d02f8)
- [LinkedIn - Staff Software Engineer, Product Engineering - EU (Remote DE)](https://www.linkedin.com/jobs/view/4403613672/) (CDP)
- [LinkedIn - Staff Software Engineer, Product Engineering - EU (Munich)](https://www.linkedin.com/jobs/view/4403603917/)
- [LinkedIn - Senior Software Engineer, Product Engineering - EU (Munich)](https://www.linkedin.com/jobs/view/4403399909/) (CDP)
- [LinkedIn - Senior Software Engineer, Product Engineering - EU (Remote DE)](https://www.linkedin.com/jobs/view/4403621481/)
- [Ashby blog - AI, Ashby Engineering, and the Future](https://www.ashbyhq.com/blog/engineering/ai-ashby-engineering-and-the-future)
- [Glassdoor - Ashby overview](https://www.glassdoor.com/Overview/Working-at-Ashby-EI_IE6016688.11,16.htm) (CDP)
- [Glassdoor - Ashby reviews (global, English)](https://www.glassdoor.de/Bewertungen/Ashby-Bewertungen-E6016688.htm?filter.iso3Language=eng) (CDP)
- [Glassdoor - Ashby reviews, Germany filter](https://www.glassdoor.de/Bewertungen/Ashby-Deutschland-Bewertungen-EI_IE6016688.0,5_IL.6,17_IN96.htm) (CDP)
- [Glassdoor - Ashby reviews, Software Engineer filter](https://www.glassdoor.de/Bewertungen/Ashby-Software-Engineer-Bewertungen-EI_IE6016688.0,5_KO6,23.htm) (CDP)
- [Glassdoor - Ashby interviews](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/Ashby-Fragen-im-Vorstellungsgespr%C3%A4ch-E6016688.htm) (CDP)
- [Kununu - search "Ashby"](https://www.kununu.com/de/search?q=Ashby) (CDP; no profile)
- [Teamblind - Ashby company page](https://www.teamblind.com/company/Ashby/) (CDP; not found)
- [levels.fyi - Ashby Software Engineer salaries](https://www.levels.fyi/companies/ashby/salaries/software-engineer) (CDP; locked)
- [Great Place to Work Germany - search](https://www.greatplacetowork.de/?s=Ashby) (CDP; no results)
- [TrueUp - Ashby](https://www.trueup.io/co/ashby) (CDP; no layoff data)
- [Deel blog - Hiring globally with Ashby's VP of People](https://www.deel.com/blog/hiring-globally-with-ashby/)
