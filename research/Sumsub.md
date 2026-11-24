# Sumsub - Full Research Report

_Researched: 2026-10-01_

> **Critical Concerns** (no single hard FAIL; the full report follows):
> 1. **Python is not the main language.** The core platform is Java 17 (Dropwizard, Kafka, MongoDB, ClickHouse). Python appears only in the ML/CV team (PyTorch, FastAPI, Airflow).
> 2. **The Glassdoor rating has been inflated by a review campaign.** 48 of the 118 English reviews (41%) were posted between 1 Aug and 29 Sep 2026: 41 of those are 5.0 and 13 were posted on 28 to 29 Sep alone. The 6-month trend climbs from 4.1 to 4.6. The independent signals are lower: Glassdoor Germany is 4.0 with 62% recommend (6 reviews), and Kununu is 3.4 with 60% recommend (7 reviews).
> 3. **The employment route is unclear.** The German entity exists and is profitable, but reviews mention "B2B contract" (Cyprus), "no healthcare" (Leipzig, Germany) and one-year fixed-term contracts renewed annually (Berlin). The UK accounts state that payroll costs "include ... independent contractors engaged under service agreements". A permanent, unbefristet contract with Sumsub GmbH has to be confirmed in writing.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 2015, London (11 years) |
| Employees | ~1,048 (Tracxn, May 2026); job postings say "1,000+ people", across 25+ countries. LinkedIn/Glassdoor band still shows 501-1,000 |
| Revenue (FY2025) | Group revenue is **not published**: the group parent is Raritex Trade Ltd in Cyprus (HE 369578), which files no public accounts. Third-party estimates are ~$85-95M (GetLatka, 2024), not verified. The UK distributor, Sum and Substance Ltd, reported turnover of **£48.8M in FY2025, down from £67.2M in FY2024 (-27%)** |
| Profitability | Group P&L **UNVERIFIED**. All subsidiaries that were checked are profitable, but they run on transfer-pricing margins: UK Ltd profit £1.72M (FY2024: £1.84M), Sumsub GmbH net profit €517K (2025). Total disclosed external funding is only $7.5M to $36.6M, depending on the source, for a company of 1,000+ people that now has unicorn status. A largely bootstrapped company of that size has to be cash-generative, so the group is very likely profitable (an inference, not a filing) - **BORDERLINE (likely PASS)** |
| Ownership | Private, founder-owned. The three Sever brothers (Andrew, Jacob, Peter; registered surname Severiukhin) are the sole UBOs via Raritex Trade Ltd (Cyprus). There are four minority shareholders (MetaQuotes led the 2020 Series A). Joined the WEF Unicorn Community in Jan 2026 (valuation >$1B; figure undisclosed) |
| Software-centric | Yes. SaaS/PaaS KYC, KYB, AML, transaction monitoring, fraud prevention and deepfake detection platform with proprietary CV/OCR/liveness models - **PASS** |

**Key People:**
- **Andrew Sever** - co-founder, CEO (95% CEO approval on Glassdoor)
- **Vyacheslav (Viacheslav) Zholudev, Dr.** - co-founder, CTO; sole Geschäftsführer of Sumsub GmbH since Aug 2021
- **Jacob (Yakov) Sever** - co-founder, Chief Innovation Officer; sole director of Sum and Substance Ltd (UK)
- **Peter Sever** - co-founder, Chief Strategy Officer

**Funding History:**

| Date | Round | Amount | Valuation | Lead |
|---|---|---|---|---|
| Oct 2017 | Seed | $0.6M | - | - |
| Jul 2018 | Accelerator | - | - | WeXelerate |
| Sep 2020 | Series A | $6M | - | MetaQuotes |
| Dec 2022 | Series B (Tracxn) | undisclosed | - | - |
| Sep 2025 | Accelerator (Grow London) | - | - | Grow London |
| Jan 2026 | WEF Unicorn Community membership | - | >$1B (implied) | - |
| **Total disclosed** | | **$7.5M to $36.6M** (sources disagree) | | |

**Business Model:** This is a pure B2B SaaS verification and compliance platform with 4,000+ clients (Bybit, Bitpanda, Wirex, Avis, Vodafone, Duolingo, Kaizen Gaming). It is named a Leader in the Gartner MQ for Identity Verification (2024 and 2025), the Forrester Wave (Q3 2025) and the IDC MarketScape. Revenue skews heavily toward crypto, trading and iGaming clients, which ties it to the crypto cycle. That is one plausible explanation for the 27% drop in UK turnover in 2025.

**Corporate structure and reputational context:** IP sits with Raritex Trade Ltd (Cyprus). The UK Ltd and the German GmbH are distributors or service entities paid on a cost-plus or target-margin basis: the UK Ltd paid Raritex a £35.7M "Distribution and License Fee" in 2025. In May 2026 the Belarusian outlet Nasha Niva reported that the founders are Russian-born, that the original development offices were in Russia, and that a Russian OCR vendor (Smart Engines) was used until at least 2021. Sumsub "categorically" denied any connection to the Russian state, and the Belarusian Coordination Council kept using it. A Glassdoor review from Mar 2026 (Marketing Manager, London, 2.0) describes leadership as "heavily dominated by Russian executives" with a "hierarchical and centralized style". Glassdoor salary data still lists 3 data points in Saint Petersburg.

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **Sumsub GmbH** | Amtsgericht Charlottenburg (Berlin) HRB 204951 B, registered Feb/Mar 2019, share capital €25,000 (€12,500 paid in) | Scharnhorststraße 8 B, 10115 Berlin (Mitte) | "Software development and sales" (NorthData, register extract). handelsregister.ai summarises the current activity as provision of an AI-supported platform for identity verification, KYC/AML compliance, fraud prevention and transaction monitoring; WZ 62.01.9 (other software development) |

**Verification:**
- **Shareholder:** Raritex Trade Ltd (Cyprus, HE 369578) owns 100%. The managing director is Dr. Viacheslav Zholudev (group CTO).
- **Size and financials (FY2025, handelsregister.ai, rendered via CDP):** total assets €1.97M, cash €417K, equity €1.22M, net profit €517K, provisions €505K. This is a small, profitable cost-plus entity.
- **Engineering purpose:** "Software development and sales" includes development, so this is not a pure sales shell, and the CTO is the managing director. However, the German entity's visible workforce is mostly operations: video-identification operators, customer support (Leipzig) and administration (Berlin). The one ML engineer review that is located in Berlin (Sep 2026, former employee) shows that some engineers were based there.
- **Contract type:** This is the weak point. A Kununu review from a Berlin admin employee (Jul 2026) says their contract "is extended once a year for another year", meaning rolling fixed-term contracts after four years of service. A Leipzig customer service representative (Glassdoor, Aug 2026) lists "no healthcare" as a con. In Germany, employees are always covered by statutory health insurance, so this suggests either a freelance arrangement or simply no private top-up. A Cyprus analyst (Glassdoor, Jul 2025) mentions a "B2B contract". The UK accounts explicitly include "independent contractors engaged under service agreements" in wage costs. No evidence of an EOR (Deel/Oyster/Remote) was found for Germany.

**Verdict:** **PASS with CAUTION.** The GmbH is real, profitable and registered for software development. Before going further, confirm that an engineering hire in Germany gets a direct, **unbefristet** Arbeitsvertrag with Sumsub GmbH (not a freelance/B2B or annual fixed-term contract).

---

## Section 3: Office Location

- **Office address:** There is no Munich office. The only German hub is Scharnhorststraße 8 B, 10115 Berlin-Mitte. Other hubs: London, Limassol, Riga, Singapore, Miami, Dubai, Tel Aviv, plus coworking spaces.
- **Nearest public transit:** Not applicable for Munich (no Munich office).
- **Work model:** **Remote-first.** Every current posting says: "Remote-first, trust-based culture ... No mandatory office days, no attendance trackers." Flexible hours, plus "team offsites ... a few times a year", fully paid. Engineering postings are labelled "European Union (Remote)". A Kununu reviewer (Jul 2026) notes that working from anywhere is no longer allowed: staff now have to work from Germany or Europe.

---

## Section 4: Reviews

**GPTW:** Sumsub is **Great Place to Work Certified in the USA** (profile updated Jun 2026, "93% say it is a great place to work"). There is **no GPTW Germany certification**.

#### Glassdoor

Glassdoor employer ID E5315113. The data was retrieved via CDP (logged-in Chromium). Direct pagination URLs redirect to a broken internal host, so pages were read by clicking "Next" in the page itself. 48 of the most recent reviews and the 15 lowest-rated reviews were read in full.

| Metric | Global | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | 4.5 (118 English reviews; 120 to 164 across all languages) | 4.0 (6 reviews) | No reviews | SWE: 2 reviews (4.0, 4.0); Senior SWE: 1 review (5.0) |
| **WLB** | 4.3 | n/a | n/a | n/a |
| **Culture & Values** | 4.5 | n/a | n/a | n/a |
| **Comp & Benefits** | 4.3 ("up 19% in the last 12 months") | n/a | n/a | n/a |
| **Career Opportunities** | 4.4 | n/a | n/a | n/a |
| **Diversity & Inclusion** | not shown without unlock | n/a | n/a | n/a |
| **% Recommend** | 88% | 62% | n/a | 100% |
| **CEO Approval** | 95% | 100% | n/a | 100% |
| **Business Outlook** | 88% positive | 62% positive | n/a | 48% positive |

All filtered views (Germany, SWE) have far fewer than 20 reviews, so treat them as directional only.

**Review-integrity warning:** The global 4.5 is not a reliable signal.
- 48 English reviews were posted in Aug to Sep 2026 alone: 12 in August (6 on 4 Aug) and 36 in September (8 on 28 Sep, 5 on 29 Sep). 41 of the 48 are 5.0, 6 are 4.0, and 1 is 2.0.
- Glassdoor's own 6-month trend line climbs from 4.1 (May) to 4.6 (Oct). Search-engine snippets of the same page still show "67 reviews", so the count nearly doubled within months.
- The burst reviews are short and generic ("I can't say anything bad", "no downsides"), and the company replies to most of them.
- The rating before the campaign appears to have been about 4.1. The pages sorted by lowest rating contain 1.0 to 3.0 reviews from 2024 to 2026 with consistent themes (see below).

#### Kununu

Kununu `sumsub` (Sumsub GmbH, Berlin). curl returns HTTP 405, so the page was retrieved via CDP.

- **Overall score:** 3.4 / 5.0, below the IT industry average of 4.0
- **Recommendation rate (Weiterempfehlung):** 60% over the last 2 years (71% across all reviews)
- **Total reviews:** 7 employee reviews since 2023
- **Sub-scores:** Karriere & Gehalt 3.4, Unternehmenskultur 3.3, Arbeitsumgebung 3.2, Vielfalt 3.7
- **Confirmed benefits:** Homeoffice 100%, flexible hours 29%
- **Kununu Top Company:** NO (the profile is not maintained by the employer)

#### Blind / Teamblind

There is no Sumsub company page on teamblind.com (`/company/Sumsub` returns 404 via WebFetch and CDP). The only search hit is a 2024 referral request for London. Coverage: none.

#### Review Themes (2024-2026)

**Positives:**
- A genuinely remote-first culture: "Fully remote setup that actually works: clear communication, sensible processes" (Senior SWE, Yerevan, Sep 2026); "No micromanagement" appears across several years and platforms.
- Flexible hours, extra personal days, a birthday holiday, and paid team offsites.
- Interesting, fast-moving product work: "At the cutting edge of technology - constantly trying new things".
- Competitive pay for sales, product and engineering roles in lower-cost locations ("Great pay and supportive team", "competitive salary"). Comp & Benefits was rated 4.3.
- Engineers report ownership and input: "engineers have genuine input on how things are built".

**Negatives:**
- **Sudden terminations and job insecurity:** "No guarantees you won't be kicked off suddenly without compensation, the company does this regularly" (Support, Belgrade, 3+ years, Jun 2026); "The company has a policy of firing employees without notice" (CSR, Jul 2024).
- **Cost-cutting and replacing support staff with AI:** "Heavy cost-cutting in the Support department, active replacement of employees by AI - Strategic decisions are made on the fly, rules of the game shift overnight" (Jun 2026).
- **Top-down, opaque leadership:** "hierarchical and centralized style, with decisions made top-down and often with little transparency ... priorities can change quickly without much explanation" (Marketing Manager, London, Mar 2026); "Sometimes strange decisions are made" (SWE, Limassol, Aug 2026).
- **KPI pressure in operations:** "performance KPI versessen" with a 95-100% KPI needed for a bonus (Kununu, Berlin, Jul 2026); "unachievable quality rates to earn bonuses ... they focus on how they can make you lose your bonus" (Leipzig, Aug 2026).
- **Isolation and fragmentation:** "no team meetings. you are totally alone" (Leipzig); "team fragmentation" and "distributed team" across time zones.
- **Overtime and burnout (older and sparse):** "Excessive unpaid overtime, no work-life boundaries ... deeply toxic, exploitative culture" (Apr 2025, 1.0).
- **Weak onboarding:** "Limited support for new joiners, with a high-pressure environment for underperformers" (Dec 2025); "no structured training program" (2024).
- **Contract precarity:** rolling annual contracts (Kununu); "B2B contract" (Glassdoor 2025).

The overlap with hard red flags is concentrated in **operations/support** roles (silent firings, KPI pressure, cost-cutting). Engineering-specific reviews are few and positive, but most of them fall inside the solicitation window.

#### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | Isolated: "deeply toxic, exploitative culture" (Apr 2025, anonymous, 1.0). Most reviews call managers approachable. **Low-moderate** |
| 24/7 Work Expectation | No evidence for engineering. Shift work for support. Flexible hours are praised. **Low** |
| Internal Surveillance | Postings promise "no attendance trackers". Operations staff report QA teams hunting for bonus deductions. **Low for engineering** |
| Fear-driven Management | "high-pressure environment for underperformers" (Dec 2025); KPI-driven operations. **Moderate (operations)** |
| Communication Breakdown | "decisions made top-down and often with little transparency" (Mar 2026); "rules of the game shift overnight" (Jun 2026); "some people just refuse to check Slack" (Jul 2025). **Moderate** |
| Unpaid Overtime | One 1.0 review (Apr 2025): "Excessive unpaid overtime". Kununu: overtime used to be paid and was replaced by a KPI bonus. **Low-moderate** |
| Silent Firings | Repeated: "kicked off suddenly without compensation, the company does this regularly" (2026); "firing employees without notice" (2024). Contractor status would make this legally easy. **Moderate-high (non-German contracts)** |
| Work-Life Balance issues | WLB rated 4.3 globally. Complaints are concentrated in support and sales. **Low for engineering** |

**Risk level: MODERATE.** This is not systemic toxicity in engineering. The pattern is (c) localized dysfunction in support and operations (KPI pressure, cost-cutting, abrupt terminations), combined with a founder-centralized, top-down decision style. The abrupt-termination pattern is tied to contractor or B2B status, so it matters only if the German contract is not a proper unbefristet Arbeitsvertrag.

---

## Section 5: Compensation

#### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| Glassdoor (Berlin) | Machine Learning Engineer | ~€108-120K (€9-10K/month) | - | - | ~€108-120K | 1 |
| Glassdoor (Berlin) | Data Scientist | ~€60K (€5K/month) | - | - | ~€60K | 1 |
| Glassdoor (Berlin) | Software Engineer | ~€48K (€4K/month) | - | - | ~€48K | 1 |
| Glassdoor (Berlin) | Principal Talent Acquisition Partner | ~€72-84K | - | - | - | 1 |
| Glassdoor (UK) | DevSecOps Engineer | ~€101-108K (£87-93K) | - | - | - | 1 |
| Glassdoor (UK) | Senior Product Manager | ~€134-145K (£115-125K) | - | - | - | 1 |
| levels.fyi | - | No company page (404) | - | - | - | 0 |
| Job postings | Senior ML Engineer (EU) | Not disclosed: "compensation differs based on the candidate's confirmed work location ... shared in writing" early in the process | - | - | - | - |

Munich median, 75th and 90th percentiles: **not available** (no Munich data points). Glassdoor shows 14 salary entries in Berlin, almost all operations roles.

#### Equity / Stock

No employee equity programme was found in postings, reviews or filings. The company is founder-owned through a Cyprus holding, with no evidence of an ESOP/VSOP. Treat the offer as **cash-only** (base plus possible bonus) unless the offer says otherwise.

#### Verdict

**UNVERIFIED.** The single Berlin ML Engineer data point (~€108-120K) is **COMPARABLE** to the Munich bracket of large, profitable corporations for senior engineers (~€90-115K base). The Software Engineer and Data Scientist points (€48-60K) are well **BELOW** it. There is no equity to lift total compensation. Pay is location-adjusted, so ask for the Germany band at the TA screening.

---

## Section 6: AI/ML & Tech Stack Fit

#### AI Strategy

AI is the core of the product, not marketing:
- In-house **CV models** for document segmentation, OCR (AllDocs, 140+ languages), liveness and **deepfake detection**. Liveness is iBeta Level 2 certified. Sumsub published the "Deepfake-Detectors-in-the-Wild" research repository (Python).
- **Summy AI Copilot**: an LLM-based agent for compliance case summaries and recommended actions (Case Management, 2025).
- ML-based fraud scoring, anomaly detection and dynamic risk scoring. An "Agentic AI Council" was launched in APAC (Sep 2026).
- The current Senior ML Engineer posting describes production ownership: "Own the full ML lifecycle ... Train CV/ML models to detect deepfakes, segment documents ... Serve models efficiently with FastAPI and PyTorch, integrating cleanly with our high-load Java backend."

This is applied, production CV/ML at high volume (millions of verifications per day), not research.

#### Tech Stack

Derived from current LinkedIn job postings (primary source), the GitHub organisation `sumsub`, and the FY2025 UK strategic report.

| Category | Technologies |
|---|---|
| **Primary language(s)** | **Java 17** (backend: Dropwizard / Restler, Feign); Python (ML/CV only); Swift / Kotlin (mobile SDKs) |
| **AI/ML** | PyTorch, FastAPI model serving, Triton (nice to have), CV (deepfake, liveness, document segmentation, OCR), LLM copilot |
| **Cloud** | AWS (preferred per DevSecOps posting) |
| **Infrastructure** | Kubernetes, GitLab CI / GitHub Actions, Kyverno/OPA, Nessus/Trivy, osquery/FleetDM |
| **Data** | MongoDB, ClickHouse, Redis, Kafka / Kafka Streams, ElasticSearch / OpenSearch (k-NN), Airflow, Superset, Trino/Flink (nice to have) |
| **Other** | SOC 2, ISO 27001, PCI DSS, GDPR, eIDAS QES |

#### Current Open Roles

Roles were collected via the LinkedIn voyager API: Germany search (7 Sumsub roles) and worldwide search (37 roles), then checked individually. All roles listed below are `LISTED` and not closed as of 2026-10-01.

| Role | Division/Team | Level | Key Tech | Link |
|---|---|---|---|---|
| Senior Machine Learning Engineer | ML / anti-fraud (deepfake, document CV) | Senior (4+ yrs ML/CV) | Python, PyTorch, FastAPI, Airflow, ClickHouse, Superset; Triton, Kafka/Flink nice to have | [LinkedIn 4436267062](https://www.linkedin.com/jobs/view/4436267062/) - **European Union (Remote), the only Python-centric role** |
| Senior Backend Developer - External Integrations | External Integrations | Senior | Java 17, Dropwizard, MongoDB, ClickHouse, Kafka, OpenSearch, Airflow | [LinkedIn 4451413092](https://www.linkedin.com/jobs/view/4451413092/) - Limassol (Remote); Java, poor fit |
| DevSecOps Engineer (Vulnerability & Fleet) | Security / Platform | Senior | Python/Go/Bash, AWS, Kubernetes, Nessus, Trivy, osquery | [LinkedIn 4452987695](https://www.linkedin.com/jobs/view/4452987695/) - Limassol (Remote); security ops, poor fit |
| Marketing Automation Engineer | Marketing | - | - | [LinkedIn 4457625998](https://www.linkedin.com/jobs/view/4457625998/) - not a software engineering fit |

The other ~33 open roles are product, sales, go-to-market, support, legal and HR.

**Verdict:** The platform is Java-centric (Dropwizard, Kafka, MongoDB/ClickHouse on AWS), with a Python/PyTorch CV and ML team serving models via FastAPI. The work is applied, production-scale computer vision (deepfake, liveness, document AI) in a compliance domain.The Senior ML Engineer role - production CV pipelines, PyTorch, FastAPI, inference optimisation, regression monitoring of model metrics. Any backend or platform role would be Java-first and fails the "Python as main language" criterion.

---

## Section 7: Language

- All postings are in English. The only language requirement is "Good command of the English language".
- The workforce is spread across 25+ countries (Cyprus, Georgia, Armenia, Serbia, Latvia, Portugal, Poland, Malaysia, etc.), and English is the working language.
- German-language reviews come only from German operations staff (video-ident, support).

**Verdict:** **PASS.**

---

## Section 8: Stability

#### Financial Position

- **Group:** Not public. Raritex Trade Ltd (Cyprus) consolidates the group and owns the IP, and no group accounts were found. The company has 1,000+ staff on very little external capital ($6M Series A in 2020; at most $36.6M disclosed in total), achieved unicorn status (WEF, Jan 2026), and is still hiring across sales and product. Together these strongly suggest a profitable, self-funding business.
- **Sum and Substance Ltd (UK, 09688671), FY2025 audited (RSM Ireland):** turnover £48.8M (-27% YoY from £67.2M), operating profit £2.25M (FY2024: £2.46M), net profit £1.72M, cash £1.63M (FY2024: £2.09M), equity £6.76M. Average headcount was 58 (FY2024: 87, -33%): Sales and Marketing fell from 48 to 34, Legal and Compliance from 14 to 5, Product/Design/Tech from 7 to 3. The report says marketing spend increased.
- **Sumsub GmbH (Berlin), 2025:** net profit €517K, equity €1.22M, total assets €1.97M, cash €417K.
- **Security incident:** A threat actor had unauthorised access to a support environment from Jul 2024 and went undetected for about 18 months, until a Jan 2026 review. The breach was disclosed in Feb 2026, and the exposed data was mostly names, emails and phone numbers. There was an earlier customer-related incident involving Merkur AG (Mar 2025). For an identity-verification vendor these are reputational risks, though not existential ones.

#### Financial Runway

The company is not VC-dependent and has no evidence of losses, so a runway model is not required. The cash figures above are entity-level only (UK £1.63M at 31 Dec 2025; GmbH €417K at 31 Dec 2025), because group cash is held at the Cyprus parent and is not disclosed.

#### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| 2024 | UK entity headcount reduction | 87 to 58 average (-33%), FY2024 to FY2025 | UK Ltd only; sales, legal and compliance roles cut (Companies House accounts) |
| 2025-2026 | Support cost-cutting and AI replacement | Unknown | Glassdoor (Belgrade Support, Jun 2026): "Heavy cost-cutting in the Support department, active replacement of employees by AI". Not publicly announced; no WARN or press record (Workopia, TrueUp) |
| Ongoing | Abrupt individual terminations | Unknown | Repeated in reviews in 2024 and 2026, consistent with contractor arrangements |

No announced company-wide layoffs were found.

**Verdict:** **CAUTION.** The business is almost certainly profitable and self-funded, but the group financials are opaque, UK revenue fell 27% in 2025, support headcount is being cut quietly, and the security incidents and the Russia-ties controversy carry reputational risk.

---

## Section 9: Regulated Industry

Sumsub is a RegTech vendor to regulated firms (banks, EMIs, crypto/MiCA, iGaming), not itself a BaFin-supervised entity. The practical impact:
- SOC 2, ISO 27001, PCI DSS audits, GDPR, and eIDAS QES (a qualified trust service partner) bring evidence and compliance automation work, especially in platform and security roles.
- Clients under DORA will treat Sumsub as an ICT third party, which means due diligence, uptime SLAs (the CTO cites 99.996%) and incident reporting.
- For the ML role, the burden is model quality and fairness rather than formal safety cases.

**Verdict:** **PASS** (moderate compliance overhead, no formal safety-case regime).

---

## Section 10: On-Call

- None of the four engineering postings mentions on-call explicitly.
- The product is real-time, high-load SaaS with a 99.996% uptime claim. The ML posting says the engineer must "see your models protect millions of users in real time ... you don't go quiet if something breaks - you find the solution". The backend posting includes "Monitoring, troubleshooting, and performance tuning of cloud infrastructure".
- Production ML model ownership in a real-time verification path usually carries some incident responsibility.

**Verdict:** **CAUTION (team-dependent, UNVERIFIED).** Ask explicitly whether the ML team has a rota and how incidents in model serving are handled.

---

## Section 11: Interview Process

From Glassdoor (88 interview reports, updated 29 Sep 2026, retrieved via CDP):

| Metric | Value |
|---|---|
| Difficulty | 2.94 / 5 |
| Positive experience | 74% (15% negative) |
| Average duration | ~20 days |
| Rounds | 3-4 |

The process stated in the current postings:
- **Senior ML Engineer:** TA screening, then Hiring Manager interview, then **Case study interview**, then Final interview.
- **Backend / DevSecOps:** TA screening, then Hiring Manager interview, then Final interview.

The process is experience- and case-based rather than LeetCode-heavy. Glassdoor stage mix: one-on-one interviews 26%, skills test 22%, background check 14%, phone 12%, panel 8%, presentation 7%. 57% of candidates applied online and 25% came through referrals. Location and compensation are confirmed early, in writing.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | PASS: B2B SaaS identity verification and anti-fraud platform with in-house CV/ML |
| Not consulting | PASS: product company; "Solutions Architect/Engineer" titles exist only in pre-sales |
| Profitable | BORDERLINE (likely PASS): all filed subsidiaries profitable; group (Cyprus) unpublished but largely bootstrapped to unicorn status |
| Employee count | PASS: ~1,048 |
| English-speaking | PASS |
| Local entity + engineering contracts | CAUTION: Sumsub GmbH HRB 204951 B (software development and sales, profitable); contractor, B2B and annual fixed-term patterns in reviews and accounts |
| Location / work model | PASS: remote-first, EU-restricted; no Munich office; offsites a few times a year |
| Glassdoor | CAUTION: 4.5 headline inflated by a 48-review burst in Aug to Sep 2026; Germany 4.0 / 62% (6 reviews); underlying ~4.1 |
| Kununu | FAIL-leaning: 3.4, 60% recommend (7 reviews), below the IT average |
| Salary | UNVERIFIED: one Berlin ML Engineer data point at ~€108-120K (comparable); no equity |
| AI/ML content | STRONG: production deepfake, liveness and document CV models, LLM copilot |
| Computer-language/Tech-stack | FAIL for the company overall (Java 17 core); PASS only for the Senior ML Engineer role (Python/PyTorch/FastAPI) |
| No on-call | CAUTION / UNVERIFIED: real-time production model ownership |
| WLB / Stability | WLB 4.3 (inflated); stability CAUTION: UK revenue -27%, quiet support cuts, abrupt terminations |
| Regulated industry | PASS: RegTech vendor; SOC 2 / ISO / PCI overhead only |
| Review themes | Remote freedom and no micromanagement vs. top-down opaque decisions, KPI pressure in operations, abrupt firings, contract precarity |
| Reputational risk | CAUTION: 18-month undetected breach (disclosed Feb 2026); Russia-ties allegations (May 2026), denied |
| Open local roles | 1 matching role: Senior Machine Learning Engineer, EU remote |

---

## Section 13: Verdict

**Monitor, and apply selectively only to the Senior Machine Learning Engineer (EU remote) role, with the contract and Glassdoor caveats verified first.**

**Strengths:** Sumsub is a real, growing product company with serious AI content: production CV models for deepfake, liveness and document understanding at millions of verifications a day, served via PyTorch and FastAPI.It is founder-owned, has run largely on its own revenue to unicorn status, has profitable subsidiaries, is genuinely remote-first with no attendance tracking, and works in English. The interview process is short (~20 days) and case-study based rather than LeetCode.

**Hard blockers:**
1. **Python is not the company's main language.** The platform is Java 17 (Dropwizard, Kafka, MongoDB/ClickHouse), and Python is confined to the ML/CV team. Only one of ~37 open roles fits. If that role closes or the team is small, there is no second Python track, and internal mobility would mean moving to Java.

**Secondary concerns:**
- **Glassdoor cannot be taken at face value.** 41% of English reviews were posted in the last two months, nearly all 5.0, and the trend rose from 4.1 to 4.6. The independent German signals are weaker: Glassdoor Germany 4.0 with 62% recommend, Kununu 3.4 with 60% recommend.
- **Employment route.** There is evidence of contractor/B2B arrangements and rolling one-year fixed-term contracts. A German engineer must get a direct, permanent contract with Sumsub GmbH.
- **Opaque group finances.** IP and profits sit in a Cyprus holding. UK turnover fell 27% in 2025 and UK headcount fell by a third. Profitability is probable but cannot be verified from filings.
- **Leadership style and churn.** Top-down, founder-centralised decisions, "rules of the game shift overnight", and abrupt terminations (mostly in operations).
- **Reputational exposure.** The 18-month undetected breach (2024-2026) and the May 2026 Russia-ties allegations (denied) are relevant for a long-term commitment and for future CV optics.
- **No equity.** Cash-only compensation. The only comparable salary data point is a single Berlin MLE entry.

**Recommendation:** Apply to the Senior Machine Learning Engineer role only if all of the following are confirmed at the TA screening:
- (a) a permanent, unbefristet Arbeitsvertrag with Sumsub GmbH (not B2B, freelance, EOR or annual fixed-term);
- (b) a Germany salary band of at least ~€100K base, given there is no equity;
- (c) the ML team's size and whether it has an on-call rota;
- (d) what share of the work is Python vs. Java integration.

For engineering-wide fit, the company stays a monitor-only employer until it runs a second Python-centric engineering track.

---

## Sources

- [Sumsub - About](https://sumsub.com/about/)
- [Sumsub - Careers](https://sumsub.com/careers/)
- [Sumsub - Our Journey](https://sumsub.com/our-journey/)
- [Sumsub - Announcing $6M in funding (Sep 2020)](https://sumsub.com/blog/announcing-6m-in-funding/)
- [Sumsub joins WEF Unicorn Community (Jan 2026)](https://sumsub.com/newsroom/sumsub-joins-world-economic-forum-unicorn-community-to-tackle-ai-fraud-and-advance-inclusive-digital-identity/)
- [Sumsub - Security Incident Update](https://sumsub.com/newsroom/security-incident-update/)
- [Sumsub - Summy AI Copilot (PR Newswire)](https://www.prnewswire.com/news-releases/sumsub-debuts-ai-copilot-to-transform-compliance-workflows-and-fraud-investigations-302689386.html)
- [Sumsub Agentic AI Council APAC (PR Newswire)](https://www.prnewswire.com/apac/news-releases/sumsub-agentic-ai-council-launches-in-apac-and-invites-experts-to-advance-trusted-ai-adoption-302891551.html)
- [fintech.global - Sumsub council tests whether AI agents can be trusted](https://fintech.global/2026/09/29/sumsub-council-tests-whether-ai-agents-can-be-trusted/)
- [Companies House - Sum and Substance Ltd (09688671) filing history](https://find-and-update.company-information.service.gov.uk/company/09688671/filing-history)
- [Companies House - Sum and Substance Ltd full accounts FY2025 (PDF, curl)](https://find-and-update.company-information.service.gov.uk/company/09688671/filing-history/MzUzMDYwNjcwOGFkaXF6a2N4/document?format=pdf&download=0)
- [NorthData - Sumsub GmbH, HRB 204951 B](https://www.northdata.com/Sumsub+GmbH,+Berlin/Amtsgericht+Charlottenburg+(Berlin)+HRB+204951+B)
- [handelsregister.ai - Sumsub GmbH (CDP)](https://handelsregister.ai/de/unternehmen/Sumsub%20GmbH)
- [Creditreform - Sumsub GmbH](https://firmeneintrag.creditreform.de/10115/2012871768/SUMSUB_GMBH)
- [companyhouse.de - Sumsub GmbH](https://www.companyhouse.de/en/Sumsub-GmbH-Berlin)
- [Tracxn - Sumsub profile](https://tracxn.com/d/companies/sumsub/__YS0jdcYteRPRu6nShgIHV1QzejJiyR2ebOaT-Ak5lfE)
- [Tracxn - Sumsub funding](https://tracxn.com/d/companies/sumsub/__YS0jdcYteRPRu6nShgIHV1QzejJiyR2ebOaT-Ak5lfE/funding-and-investors)
- [Crunchbase - Sumsub](https://www.crunchbase.com/organization/sum-substance)
- [PitchBook - Sumsub](https://pitchbook.com/profiles/company/221537-80)
- [GetLatka - Sumsub revenue estimate](https://getlatka.com/companies/sumsub)
- [Reform.news - Sumsub denies ties to Russia (May 2026)](https://reform.news/en/sumsub-denies-ties-to-russia)
- [Nasha Niva - Passports of Belarusians ... processed by a company whose founders are Russians](https://nashaniva.com/en/394881)
- [Reform.news - Coordination Council to continue cooperation with Sumsub](https://reform.news/en/coordination-council-to-continue-cooperation-with-sumsub-elections-to-start-on-may-11)
- [Crowdfund Insider - Sumsub security incident with Merkur AG (Mar 2025)](https://www.crowdfundinsider.com/2025/03/237486-regtech-sumsub-addresses-security-incident-with-german-firm-merkur-ag/)
- [Zyphe - Sumsub breach: 18 months undetected](https://www.zyphe.com/resources/blog/sumsub-security-breach-kyc-provider-lessons)
- [Fincrime Central - The Sumsub incident](https://fincrimecentral.com/sumsub-incident-cloud-aml-risk-management/)
- [Glassdoor - Sumsub overview (CDP)](https://www.glassdoor.com/Overview/Working-at-Sumsub-EI_IE5315113.11,17.htm)
- [Glassdoor - Sumsub reviews, global (CDP)](https://www.glassdoor.co.uk/Reviews/Sumsub-Reviews-E5315113.htm)
- [Glassdoor - Sumsub reviews, Germany (CDP)](https://www.glassdoor.co.uk/Reviews/Sumsub-Germany-Reviews-EI_IE5315113.0,6_IL.7,14_IN96.htm)
- [Glassdoor - Sumsub Software Engineer reviews (CDP)](https://www.glassdoor.co.uk/Reviews/Sumsub-Software-Engineer-Reviews-EI_IE5315113.0,6_KO7,24.htm)
- [Glassdoor - Sumsub Senior Software Engineer reviews (CDP)](https://www.glassdoor.co.uk/Reviews/Sumsub-Senior-Software-Engineer-Reviews-EI_IE5315113.0,6_KO7,31.htm)
- [Glassdoor - Sumsub interviews (CDP)](https://www.glassdoor.co.uk/Interview/Sumsub-Interview-Questions-E5315113.htm)
- [Glassdoor - Sumsub salaries (CDP)](https://www.glassdoor.co.uk/Salary/Sumsub-Salaries-E5315113.htm)
- [Glassdoor - Sumsub Berlin salaries (CDP)](https://www.glassdoor.co.uk/Salary/Sumsub-Berlin-Salaries-EI_IE5315113.0,6_IL.7,13_IC2622109.htm)
- [Kununu - Sumsub GmbH (CDP)](https://www.kununu.com/de/sumsub)
- [Kununu - Sumsub GmbH reviews (CDP)](https://www.kununu.com/de/sumsub/kommentare)
- [Great Place to Work - Sumsub (USA)](https://www.greatplacetowork.com/certified-company/7094035)
- [Teamblind - Sumsub search (CDP; no company page)](https://www.teamblind.com/search/Sumsub)
- [levels.fyi - Sumsub (404, no data)](https://www.levels.fyi/companies/sumsub/salaries)
- [LinkedIn - Senior Machine Learning Engineer (voyager API)](https://www.linkedin.com/jobs/view/4436267062/)
- [LinkedIn - Senior Backend Developer, External Integrations (voyager API)](https://www.linkedin.com/jobs/view/4451413092/)
- [LinkedIn - DevSecOps Engineer (voyager API)](https://www.linkedin.com/jobs/view/4452987695/)
- [LinkedIn - Marketing Automation Engineer (voyager API)](https://www.linkedin.com/jobs/view/4457625998/)
- [GitHub - sumsub organisation](https://github.com/sumsub)
- [GitHub - Deepfake-Detectors-in-the-Wild](https://github.com/sumsub/Deepfake-Detectors-in-the-Wild)
- [Workopia - Sumsub layoffs tracker](https://workopia.io/hi/companies/sumsub)
