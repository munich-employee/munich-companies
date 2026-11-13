# Apheris - Full Research Report

_Researched: 2026-11-12_

> **Critical Disqualifiers**
> 1. **Not profitable, and the cash cushion is thin.** apheris AI GmbH lost €3.57M in FY2024 (after -€3.90M in 2023 and -€2.24M in 2022). Cash at 31.12.2024 was €4.53M. The last announced equity round was the $8.25M Series A in January 2025, and no new round has been announced since. On the base-case model below, the company needs fresh capital or a large step up in consortium revenue during 2027.
> 2. **No senior software engineering opening right now.** The 9 open roles (Personio feed, 12.11.2026) are ML engineering, ML science, commercial and one Quality Engineer. The last Senior Software Engineer posting ("Drug Discovery Workflow", Python) has been taken down (Personio 404).
> 3. **Very small review base.** 7 Glassdoor reviews over 6 years, no Kununu profile, no Blind page. Every review score below is directional only.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 2019 (7 years). Registered 08.02.2019 (originally Amtsgericht Köln HRB 97119, moved to Berlin in October 2020) |
| Employees | ~68 associated LinkedIn members (LinkedIn bracket 51-200); a June 2026 profile says "~50 employees". The 2022 press release said "more than 30" |
| Revenue (FY2024) | **UNKNOWN.** The small-company HGB filing does not disclose revenue. Customers are big-pharma consortium members (AbbVie, AstraZeneca, BMS, J&J, Boehringer Ingelheim, Sanofi, Lundbeck, Orion, Recursion, Servier, Takeda and others) |
| Profitability | Net loss of €3.57M in FY2024. History: +€33K (2020), -€0.29M (2021), -€2.24M (2022), -€3.90M (2023), -€3.57M (2024) - **FAIL** |
| Ownership | Private, VC-backed. Investors: OTB Ventures, eCAPITAL (Series A leads), Octopus Ventures, LocalGlobe, Heal Capital, Dig Ventures, Another.VC; angels including Patrick Pichette (ex-CFO Google), Ross Mason (MuleSoft), Mirko Novakovic (Instana), Ian Hogarth. Founder vehicles (Robin Röhm Ventures UG, Michael Höh Ventures UG) each show 19.4% on NorthData |
| Software-centric | Federated computing platform (Apheris Gateway, Foundry, ApherisFold) operated as a product, with revenue from federated data networks for pharma - **PASS**, but see the consulting note and the ML-science weighting of current hiring |

### Key People

- **Robin Röhm**: Co-founder and CEO, managing director. Background in medicine, philosophy and mathematics, banking at UBS, then earlier life-sciences data startups.
- **Michael Höh**: Co-founder and CTO, managing director. PhD in physics and computer science, formerly at BCG. Per the About page he leads "platform architecture and design, the engineering target picture, technical customer commitments, and contractual scoping".
- **Bojana Ivanovic**: Prokurist (registered authorised signatory).
- **Scientific Advisory Board**: Mohammed AlQuraishi (OpenFold, Columbia), Pamela Carroll (ex-COO Isomorphic Labs), Darren Green (ex-GSK, MELLODDY), Richard Bickerton (Exscientia co-founder), Andreas Bender, Woody Sherman, Joseph Lehár (ex-Owkin).

### Funding History

| Date | Round | Amount | Lead / Investors | Valuation |
|---|---|---|---|---|
| 2020 | Seed | €2.5M | LocalGlobe and angels (tech.eu) | Not disclosed |
| 2020-2026 | Public grants | €0.79M (federated platform, 2020), €0.74M (SPELL, 2021), €0.42M (OpenFLaaS, 2023), €0.11M (KI-Anwendungshub), €0.44M EU (clinical multi-agent framework, June 2026) | BMWK / EU | n/a |
| 8 Nov 2022 | Seed extension | €8.7M | Octopus Ventures; LocalGlobe, Dig Ventures, Another.VC, Patrick Pichette, Heal Capital, Berthold von Freyberg, Mirko Novakovic | Not disclosed |
| Dec 2024 / announced 2 Jan 2025 | Series A | $8.25M (total raised $20.8M) | OTB Ventures, eCAPITAL | Not disclosed |
| May 2026 | R&D tax allowance (Forschungszulage) | €0.5M - €1.0M | BMF state aid register | n/a |

The FY2024 balance sheet shows €16M of capital reserves, consistent with the three equity rounds. The Series A appears in the registry as a capital increase (new articles 29.11.2024, new shareholder lists 17.12.2024 and 31.01.2025), so it is very likely already inside the 31.12.2024 balance sheet. No Series B or later round has been announced (searches of TechCrunch, Bio-IT World, the company newsroom and press aggregators, November 2026).

### Business Model

Apheris "operates the industry's federated data networks and runs no drug programs of its own" (About page). Pharma members contribute proprietary data to a network; training runs inside each member's environment and only model weights are aggregated by an Apheris-run orchestrator (NVIDIA FLARE based). Current networks:

- **AI Structural Biology (AISB) Network**: co-folding (OpenFold3, Boltz-2 fine-tuning). AbbVie, AstraZeneca, BMS and J&J. First AISB-1 results published September 2026; AISB Bind (binding affinity) launched October 2026.
- **ADMET Network**: launched 25 Feb 2026 with Lundbeck, Orion Pharma, Recursion, Servier and one undisclosed member. Run 3 completed October 2026.
- **Antibody Developability Network**: founding members announced October 2026 with Ginkgo Datapoints.
- **RWE / clinical network**: with T-Systems on German sovereign AI infrastructure (October 2026), >50,000 patients across several hospitals.
- **Virtual Cell Network**: listed on the website, no details found.

Models reach customers through **Foundry** ("modular, agent-callable building blocks") and **ApherisFold** (hosted co-folding incl. Protenix-v1, NVIDIA MSA NIM).

The company pivoted from a horizontal "collaborative data ecosystems" platform (2022 customers included BASF, BMW Group and BCG) to drug discovery only.

### Consulting-Adjacency Assessment

- The registered purpose includes "projektbezogener Dienstleistungen und Beratung" alongside software development and operation.
- Several roles are customer-facing and project-shaped: the "Forward-Deployed ML Engineer" "carr[ies] out case-studies ... providing scientific and technical expertise to our customers ... from scoping through to results delivery", and the ML Engineer "deliver[s] results packages for consortium partners".
- Reviewers mention "Changing requests from customers are a challenge" (Glassdoor, Oct 2021, current Software Engineer, Berlin) and "Focus can change from day to day" (Glassdoor, Jul 2020, current Business Manager).
- But: no consultant titles, no billable hours, and the deliverables are shared models and a platform owned by Apheris that every network member uses. The revenue model is network membership rather than client delivery.

Verdict: product company with a strong forward-deployed component. Not consulting.

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **apheris AI GmbH** | Amtsgericht Charlottenburg (Berlin) HRB 221842 B (EUID DEF1103R.HRB221842B; VAT DE323035966); formerly AG Köln HRB 97119; UK establishment Companies House FC039871 | Kolonnenstr. 8, 10827 Berlin | "Die Entwicklung, die Herstellung sowie der Betrieb und der Vertrieb von Softwareanwendungen sowie projektbezogener Dienstleistungen und Beratung im Bereich der Informationstechnologie, der künstlichen Intelligenz und verwandten Bereichen. Ferner ... der Kauf, das Halten, die Administration, das Bewirtschaften, die Entwicklung, die Weiterentwicklung, der Verkauf, die Lizenzierung und die Unterlizenzierung von Immaterialgüterrechten." |

The German GmbH is the parent and the operating company: it holds the IP, develops the software and files the accounts. The purpose explicitly covers development and operation of software, not just distribution. Managing directors are the two founders; share capital €59,360. German employees are employed directly by the GmbH (Berlin HQ, BMWK grants and the Forschungszulage are all booked to this entity); the UK staff (~21 on LinkedIn) sit under the UK establishment. No sign of PEO/EOR use for Germany. Postings are "Remote (UTC +/- 2 hrs)", so non-German hires elsewhere in Europe may go through an EOR, but that does not affect a German hire.

**Verdict:** PASS

---

## Section 3: Office Location

- **Office address:** Kolonnenstraße 8, 10827 Berlin-Schöneberg (Rote Insel, Tempelhof-Schöneberg). Nominatim resolves this address to "CoWoS", a co-working space, so the HQ is a co-working base rather than a dedicated office. There is **no Munich office**.
- **Nearest public transport** (OSM Nominatim + Overpass):
  - S-Bahn **Julius-Leber-Brücke** (S1): bus stop of the same name 57 m away (the S-Bahn halt itself is tagged as a halt and was not returned by the station query)
  - Bus stops Richard-von-Weizsäcker-Platz (196 m), Gustav-Müller-Platz (290 m)
  - U-Bahn **Kleistpark** (U7): 455 m
  - U-Bahn Eisenacher Straße (U7): 755 m
- **Work model:** **Remote-first.** All engineering postings are "Remote (UTC +/- 2 hrs)", full-time, permanent. Benefits list "Remote-first working: work where you work best, whether from home or a co-working space near you", a co-working stipend, a work-from-home budget, and a "Quarterly All Hands meet-up at our Berlin HQ or a different European location". Of ~68 LinkedIn members, 25 are in Germany (17 in Berlin) and 21 in the UK. Working from Munich is compatible with the stated model; expect roughly four trips a year.

---

## Section 4: Reviews

**GPTW:** Apheris does not appear in Great Place to Work Germany listings, and its website and careers page claim no GPTW certification (greatplacetowork.de search and web search, November 2026). **NO**.

#### Glassdoor

Retrieved via Chromium over CDP (glassdoor.de, logged-in profile). Employer ID E3480790 ("apheris AI"). Glassdoor counts 7 reviews: 6 in English and 1 in German. The 6th English review could not be loaded (pagination did not render).

| Metric | Global | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | 4.8 (6-7 reviews) | ~4.8 (5 Berlin reviews, no country filter offered) | N/A (0 reviews) | 4.0 and 5.0 (2 reviews: "Senior software engineer", "Software engineer") |
| **WLB** | 4.8 | n/a | n/a | n/a |
| **Culture & Values** | 5.0 | n/a | n/a | n/a |
| **Comp & Benefits** | 4.0 | n/a | n/a | n/a |
| **Career Opportunities** | 4.7 | n/a | n/a | n/a |
| **Diversity & Inclusion** | 5.0 | n/a | n/a | n/a |
| **Senior Management** | 4.7 | n/a | n/a | n/a |
| **% Recommend** | 100% | n/a | n/a | 100% |
| **CEO Approval** | Not shown (too few ratings) | n/a | n/a | n/a |
| **Business Outlook** | 100% positive | n/a | n/a | n/a |

All filters yield far fewer than 20 reviews. Treat every number as directional. The most recent review is from October 2025; there is nothing from 2026, a year in which headcount grew.

#### Kununu

Tried slugs `apheris`, `apheris-ai`, `apheris-ai-gmbh`, `apheris1` via curl (all HTTP 405, Kununu's bot block), then the Kununu search page via Chromium over CDP: **no Apheris profile exists**.

- **Overall score:** N/A
- **Recommendation rate:** N/A
- **Total reviews:** 0
- **Kununu Top Company:** NO

#### Blind / Teamblind

`teamblind.com/company/Apheris` returns "Page not found" (Chromium over CDP). No Blind presence.

#### levels.fyi

`levels.fyi/companies/apheris` returns 404 (Chromium over CDP). No data.

#### Review Themes (2020-2025)

**Positives:**
- Mission and impact: "The problem you are working on has real impact, in the grand scheme of things." (Glassdoor, Oct 2025, former Senior Software Engineer, Berlin, 1+ years)
- Team quality and leadership: "Culture that embodies growth mindset - Cutting-edge AI lifesciences use cases with high impact - Strong leadership and a kind & committed team" (Glassdoor, Jan 2025, former Senior Customer Solutions Engineer, London, 3+ years)
- Flexibility: "Amazing team, flexible hours, unique product" (Glassdoor, Jul 2024, current Team Lead, Berlin)
- Hard technical problems with clear ownership: "Dynamic environment, high growth, we solve very challenging tasks together, clear responsibilities" (Glassdoor, Oct 2021, current Software Engineer, Berlin, 1+ years)
- Self-directed development: "You can chose yourself the direction of your personal and professional development - it is supported big time by management. - Open and friendly communication and culture." (Glassdoor, Jul 2020, current Business Manager)

**Negatives:**
- **Slow commercial traction**, raised by both reviewers who have left: "The business deals are complicated to make. The company is growing in terms of clients, but it might be slower then they would like it to be." (Glassdoor, Oct 2025, former Senior Software Engineer, Berlin, 1+ years) and "Market for federation is growing, but slowly" (Glassdoor, Jan 2025, former Senior Customer Solutions Engineer, London, 3+ years). This lines up with the losses and the pivot from a horizontal platform to pharma only.
- **Shifting priorities driven by customers**: "Changing requests from customers are a challenge - structure comes with time though" (Glassdoor, Oct 2021, current Software Engineer, Berlin, 1+ years); "Focus can change from day to day" (Glassdoor, Jul 2020, current Business Manager).
- **Founders work long hours**: "Sehr schnelles Wachstum und dadurch manchmal viel Änderung. Gründer arbeiten viel dafür trotzdem ein sehr stabiles Umfeld zu haben." (Glassdoor, Jul 2020, current Data Scientist, Berlin)
- **Comp & Benefits is the lowest sub-score** (4.0 vs 4.7-5.0 elsewhere).
- No hard red flag (toxic leadership, unpaid overtime, surveillance, 24/7 availability, layoffs) is mentioned anywhere, but the sample is too small to rule them out.

#### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | None reported. "Strong leadership and a kind & committed team" (Glassdoor, Jan 2025, former Senior Customer Solutions Engineer, London) |
| 24/7 Work Expectation | None reported. "flexible hours" (Glassdoor, Jul 2024, current Team Lead, Berlin). UTC±2 window limits time-zone spread |
| Internal Surveillance | None reported |
| Fear-driven Management | None reported |
| Communication Breakdown | None reported; "Open and friendly communication and culture" (Glassdoor, Jul 2020, current Business Manager) |
| Unpaid Overtime | Not reported for employees. The 2020 German review notes the founders themselves "arbeiten viel" |
| Silent Firings | None reported. No 2026 reviews exist to check |
| Work-Life Balance issues | None reported; WLB 4.8 |

**Risk level: LOW (low confidence).** All signals are positive, but they rest on 7 reviews, none from 2026, and the company is too small to have any corporate bureaucracy. The real risks here are commercial (slow deal cycles, runway) and customer-driven reprioritisation, not leadership behaviour.

---

## Section 5: Compensation

#### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| Glassdoor | Any (7 Berlin salary reports, no titles shown) | not displayed | n/a | n/a | n/a | 7 (hidden) |
| levels.fyi | n/a (no company page) | - | - | - | - | 0 |
| Job postings | All roles | not disclosed ("Industry-competitive compensation") | Virtual share options | none mentioned | - | 0 |

No Munich or Germany salary data for Senior/Staff engineers at Apheris could be found. Glassdoor reviewers rate Comp & Benefits 4.0/5.

#### Equity / Stock

"Early-stage virtual share options" (VSOP) on every posting. Virtual options in a German GmbH pay out only on an exit (sale or IPO), carry no voting rights, and are taxed as salary at payout. With ~$21M raised over 7 years and no exit in sight, treat them as having no near-term liquidity.

#### Verdict

**UNVERIFIED**, and probably **BELOW** the bracket of large, profitable Munich corporations. A ~60-person, loss-making Series A startup with €3.6M annual losses and an implied personnel budget of roughly €5-6M has little room for large-corporate senior/staff base salaries. Confirm the band in the first recruiter call.

---

## Section 6: AI/ML & Tech Stack

#### AI Strategy

Genuine, core-of-the-business applied AI, not marketing use of the term:

- Federated training of foundation models on proprietary pharma data: fine-tuning OpenFold3, Boltz-2, ESM/ESMFold for co-folding, binding affinity, antibody modelling and developability; ADMET property prediction (small molecules, expanding to PROTACs, peptides, macrocycles).
- Privacy engineering: privacy assessment of outputs, model reverse-engineering risk ("Work with our privacy team to understand potential for model reverse-engineering").
- Delivery as agent-callable model building blocks via Foundry; ApherisFold with Protenix-v1 and NVIDIA MSA NIM.
- Published results: AISB-1 federated co-folding results (September 2026, Bio-IT World coverage), a CEO newsletter (FederatedMinds).
- Partnerships: NVIDIA (GTC Berlin 2026 presentation), AWS, T-Systems (sovereign AI infrastructure), Ginkgo Datapoints, AlQuraishi Lab (OpenFold3).

The ML work is science-heavy. Three of the eight non-student postings sit in a "Drug Discovery Science" department, and the ML engineering roles require hands-on experience with biomolecular models, not just general ML.

#### Tech Stack

Derived from current Personio postings (ML Engineer Large Molecules, Forward-Deployed ML Engineer, Senior ML Research Engineer, Quality Engineer), the archived Senior Software Engineer "Drug Discovery Workflow" posting (via aggregators), earlier Senior Software Engineer (Go backend) and Senior Cloud Platform Engineer postings (via aggregators), the Apheris Gateway documentation, the GitHub org `apheris`, and LinkedIn skill aggregates.

| Category | Technologies |
|---|---|
| **Primary language(s)** | Python (ML, workflows, test automation; 37 of 68 LinkedIn members list Python); Go for backend services and APIs of the federated platform ("primarily in Golang, with Python where appropriate"); Vue.js on the frontend |
| **AI/ML** | PyTorch, multi-GPU/distributed training, OpenFold/OpenFold3, Boltz-2, AlphaFold, ESM/ESMFold, Protenix, NVIDIA FLARE (federated orchestration: NVFlare server on the orchestrator, NVFlare clients on Compute Gateways), NVIDIA MSA NIM |
| **Cloud** | AWS (product core built on "AWS services and cloud-agnostic services"; 17 LinkedIn members list AWS), plus customer on-prem and other clouds (Azure, GCP, OpenStack mentioned) |
| **Infrastructure** | Docker, Kubernetes (k8s 1.30+ for the Gateway, K3s for on-prem), Helm (OCI chart on quay.io), Cilium network policies, GitOps with Flux, Terraform, CI/CD pipelines as code |
| **Data** | Workflow engines: Nextflow, Prefect, Argo Workflows (nice-to-haves); protein-ligand structure data formats |
| **Other** | Compliance stack: ISO/IEC 27001, SOC 2 Type 1 and Type 2, CSA STAR, HIPAA, GDPR (Trust Center); AI coding tools expected in the SWE posting; open-source tools on GitHub (Python) |

**Summary:** Python-centric engineering with a Go platform backend, built around PyTorch fine-tuning of biomolecular foundation models (OpenFold3, Boltz-2, ESM) orchestrated with NVIDIA FLARE on Kubernetes, on AWS and inside customers' own environments. Applied, production ML in the drug-discovery domain, with a strong research and customer-delivery component.

---

## Section 7: Language

All postings, the website, the documentation and the Glassdoor reviews (6 of 7) are in English. Postings require "fluency in English (verbal and written)"; none mention German. The team spans Germany and the UK (25 and 21 LinkedIn members) with Oxford and Cambridge as the most common schools, and customers are global pharma companies. English is clearly the working language.

**Verdict:** PASS

---

## Section 8: Stability

#### Financial Position

From the FY2024 HGB accounts (filed 18.09.2025, via NorthData, Chromium over CDP):

| Item (31.12.2024) | Value |
|---|---|
| Total assets | €7.40M |
| Cash and bank | €4.53M |
| Receivables and other assets | €2.71M |
| Equity | €6.01M (capital reserves €16M, accumulated losses -€10.1M) |
| Liabilities | €0.43M |
| Deferred income (PRAP) | €0.89M (likely prepaid consortium fees) |
| Net loss FY2024 | -€3.57M (FY2023: -€3.90M) |

The loss narrowed slightly in 2024 while the company kept growing. FY2025 accounts are not yet filed (deadline 31.12.2026). There is no debt and no credit rating.

#### Financial Runway

Searches for runway or burn-rate commentary (TechCrunch, SiliconANGLE, press aggregators) found none. Bundesanzeiger was not needed separately; NorthData renders the filed balance sheet. Bottom-up model:

| Cost line | Annual estimate |
|---|---|
| Staff (~60 FTE average in 2026 × ~€95K fully loaded; mix of Berlin and UK salaries) | ~€5.7M |
| Compute (GPU training for co-folding and ADMET runs, hosting of the orchestrator and Foundry) | ~€0.8M |
| Compliance and security (SOC 2, ISO 27001, pen tests), legal, travel, quarterly all-hands, events, co-working | ~€0.8M |
| **Total gross burn** | **~€7.3M/year** |

| Revenue source | Est. annual inflow |
|---|---|
| Network memberships and projects (AISB: 4 big pharma; ADMET: 5 members; antibody developability and RWE networks starting) | ~€3.0M - €4.5M/year |
| Grants and R&D tax allowance (EU €0.44M over the project, Forschungszulage €0.5M - €1.0M) | ~€0.5M/year |
| **Total revenue offset** | **~€3.5M - €5.0M/year** |

The FY2024 loss of €3.57M at a smaller headcount implies revenue plus grants of roughly €2.5M - €3M that year, which anchors the estimate above.

| Scenario | Net burn | Cash at hand | Runway | Next round needed by |
|---|---|---|---|---|
| Optimistic (revenue ~€5M, burn held flat) | ~€2.3M/year | €7.2M | ~3 years from Jan 2025 | ~early 2028 |
| Base case | ~€3.5M/year | €7.2M | ~2 years from Jan 2025 | ~early 2027 |
| Stress (revenue flat at 2024 level, headcount growth continues) | ~€4.8M/year | €7.2M | ~1.5 years from Jan 2025 | ~mid 2026 (i.e. already due) |

Cash figure used: €4.53M cash plus €2.71M receivables at 31.12.2024 (NorthData, FY2024 accounts filed 18.09.2025, observed 12.11.2026). The receivables may include outstanding Series A tranches; if the Series A cash arrived only in 2025, the starting cash would be ~€2M higher and every runway extends by roughly 6 months.

Reading: Apheris is either generating meaningfully more revenue in 2025-2026 than in 2024 (plausible given four big-pharma AISB members and a new ADMET network), or it is raising quietly. The 2026 hiring of 8 roles points to the first, but there is no public evidence either way. Ask directly about runway and Series B timing.

#### Layoffs

No layoffs found (press search, Glassdoor reviews, TrueUp-style aggregators). Headcount grew from "more than 30" (Nov 2022) to ~50-68 (2026). The pivot away from horizontal use cases (BASF, BMW, BCG era) to pharma only did not surface as reported cuts.

#### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | NO (none found) | No mention in reviews, postings, LinkedIn titles or press; Glassdoor German review and web search for "Apheris Betriebsrat" returned nothing. With ~25 German employees spread remotely, a council is unlikely |
| Collective agreement | NONE | Postings offer "industry-competitive compensation" with VSOP; no "Tarif" wording anywhere |
| European works council | N/A | Below thresholds |
| Conflict signals | None found | - |

No council and no collective agreement is normal for a startup of this size. Combined with an unclear runway, it means any future cost cuts would be decided by management alone, without a social plan.

**Verdict:** CAUTION (runway unverified, no new equity since Dec 2024, no employee-representation safeguards)

---

## Section 9: Regulated Industry

Apheris works in pharma R&D (drug discovery), upstream of GxP-regulated clinical and manufacturing processes, so FDA/EMA validation rules do not apply directly to the discovery networks. The RWE/clinical network handles patient data, which brings GDPR and HIPAA obligations. The company holds ISO/IEC 27001, SOC 2 Type 1 and Type 2 and CSA STAR, and lists HIPAA compliance. Practical engineering impact: security reviews by big-pharma customers, audit logging, privacy assessments of every output, and change control linked to SOC 2. A new Quality Engineer role points to growing process maturity. This is security-compliance overhead, not formal safety cases or regulatory submissions.

**Verdict:** PASS (moderate security-compliance overhead, no product regulation)

---

## Section 10: On-Call

No posting mentions on-call, pager duty or support rotations. The architecture shifts most runtime into customer environments (Compute Gateways run inside each pharma's infrastructure), while Apheris hosts the orchestrator and Foundry. Federated training runs are batch jobs across consortium members, not real-time consumer traffic. SOC 2 Type 2 and enterprise customers usually do require some incident-response arrangement, and a ~33-person engineering team would share it if it exists.

**Verdict:** UNVERIFIED (likely light or none; ask in the interview)

---

## Section 11: Interview Process

Based on Glassdoor (3 interview reports, Chromium over CDP).

| Metric | Value |
|---|---|
| Difficulty | 2.7 / 5 |
| Positive experience | 67% (0% negative) |
| Average duration | ~1 week (only one report gives a duration) |
| Rounds | 3 |

Process as described by a Forward Deployed Scientist candidate (Glassdoor, Dec 2025, offer declined): "Very structured three step process. Initial Screening: ... 45 minutes interview ... Deep Dive: Your second video call will be with a domain expert from our team ... asking you about meaningful experiences or your solutions for specific scenarios in line with the role ... Final Interview: two to three hours of interviewing with our founders, talking about our culture and meeting future co-workers on the ground."

Other reports: a Machine Learning Scientist candidate (Dec 2025, interview Aug 2025) had an intro call with "basic questions about my experience ... as well as an open-ended technical question". A Growth Marketing Manager candidate (Mar 2026) noted fast CV screening but "after the intro call the process slowed down considerably ... I did not hear back at all".

Glassdoor's stage breakdown: phone interview 50%, skills test 50%. The process is experience and scenario-based with a founder round, not LeetCode-heavy. No engineering-specific (SWE) interview report exists.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | PASS: federated computing platform plus model delivery (Gateway, Foundry, ApherisFold); current hiring weighted toward ML science |
| Not consulting | PASS with note: forward-deployed, customer-project work is part of ML roles, but revenue comes from network memberships and a shared platform |
| Profitable | FAIL: -€3.57M (FY2024), losses since 2021 |
| Employee count | ~50-68 (LinkedIn 68 associated members; ~33 in engineering) |
| English-speaking | PASS |
| Local entity + engineering contracts | PASS: apheris AI GmbH, HRB 221842 B, the operating parent company |
| Location / work model | Remote-first (UTC±2), Berlin co-working HQ, quarterly all-hands; no Munich office but Munich-compatible |
| Glassdoor | 4.8 (7 reviews, none from 2026): directional only |
| Kununu | No profile |
| Salary | UNVERIFIED; VSOP only; likely below large-corporate bracket |
| AI/ML content | Strong: federated fine-tuning of OpenFold3/Boltz-2/ESM, ADMET models, privacy-preserving ML |
| Computer-language/Tech-stack | Python-centric (PyTorch, NVFlare) with Go backend, Kubernetes, AWS |
| No on-call | UNVERIFIED, likely light |
| WLB / Stability | WLB 4.8 (small sample); stability CAUTION: runway to ~2027 in base case, no Series B announced |
| Works council / collective agreement | Neither |
| Regulated industry | PASS: security compliance (SOC 2, ISO 27001, HIPAA), no product regulation |
| Review themes | Mission, team and leadership praised; slow deal-making and shifting customer priorities |
| Open senior SWE role | None currently; last Senior Software Engineer posting closed |
| Commercial traction | Improving in 2026 (AISB-1 results, AISB Bind, ADMET network, antibody network, T-Systems RWE) |

---

## Section 13: Verdict

**Monitor.** Apheris is a credible, technically serious applied-AI company, but at the moment it fails the profitability criterion, its runway cannot be verified, and it has no open senior software engineering role.

**Strengths:** The product is genuinely hard and differentiated: federated fine-tuning of state-of-the-art biomolecular foundation models across competitors' proprietary data, with privacy engineering on top. 2026 brought real traction: four big-pharma companies in the AISB Network with published results, a new ADMET network with five members, an antibody developability network and a sovereign-cloud clinical network with T-Systems. The stack is Python and PyTorch with a Go/Kubernetes platform, English is the only working language, the work model is remote-first and fits Munich, and the few reviews are uniformly positive about the team, leadership and flexibility. The founders have stayed and are visibly engaged, and the advisory board is strong.

**Hard blockers:**
1. **Not profitable.** Net losses of €3.90M (2023) and €3.57M (2024), with €10.1M of accumulated losses against €16M raised. The last announced equity was the $8.25M Series A, registered in December 2024. Cash of €4.53M (plus €2.71M receivables) at end-2024 gives roughly two years at the base-case net burn, so a Series B or a large revenue jump is needed around early 2027.
2. **No suitable opening.** The only engineering-department postings are ML Engineer roles requiring hands-on biomolecular modelling (OpenFold, Boltz, ESM, protein structure data) and a Quality Engineer role. The Python "Drug Discovery Workflow" Senior Software Engineer role and the earlier Go backend role are closed.

**Secondary concerns:**
- Seven Glassdoor reviews, none from 2026, no Kununu, no Blind: culture risk cannot be assessed with confidence.
- Two departing reviewers independently describe slow commercial traction ("The business deals are complicated to make"; "Market for federation is growing, but slowly").
- Compensation is undisclosed and equity is VSOP in a company with no visible exit path.
- No works council or collective agreement, so any downturn would be handled without negotiated protections.
- Engineering work includes customer-driven, forward-deployed delivery, with priorities that "can change from day to day".
- On-call is unverified for a SOC 2 Type 2 platform.

**Recommendation:** Watch the Personio feed (apheris.jobs.personio.com) for a Senior or Staff Software Engineer, platform or workflow role, and watch for a Series B announcement. If both appear, apply. In the process, verify: (1) cash runway and Series B timing, (2) the salary band and VSOP terms (strike, vesting, exit-only payout), (3) whether the role is platform product engineering or forward-deployed customer delivery, (4) any on-call or incident rotation for the hosted orchestrator and Foundry, and (5) how often travel to Berlin or customer sites is expected beyond the quarterly all-hands.

---

## Sources

- [Apheris: Imprint](https://www.apheris.com/imprint) (Chromium over CDP)
- [Apheris: About](https://www.apheris.com/about-apheris) (Chromium over CDP)
- [Apheris: Trust Center](https://trust.apheris.com/) (Chromium over CDP)
- [Apheris Personio job feed (XML)](https://apheris.jobs.personio.com/xml) (curl)
- [Personio: Forward-Deployed ML Engineer, Cofolding](https://apheris.jobs.personio.com/job/2591406) (curl)
- [Personio: ML Engineer, Large Molecules](https://apheris.jobs.personio.com/job/2823682) (curl)
- [Personio: Quality Engineer](https://apheris.jobs.personio.com/job/2881389) (curl)
- [Personio: Senior ML Research Engineer](https://apheris.jobs.personio.com/job/2763175) (curl)
- [Personio: Senior Software Engineer (closed, 404)](https://apheris.jobs.personio.com/job/2538177) (curl)
- [Remote Rocketship: Senior Software Engineer, Drug Discovery Workflow](https://www.remoterocketship.com/company/apheris/jobs/senior-software-engineer-drug-discovery-workflow-europe-remote/)
- [WeAreDevelopers: Senior Software Engineer, Drug Discovery Workflow](https://www.wearedevelopers.com/jobs/ext/7174591/senior-software-engineer-drug-discovery-workflow)
- [Jobgether: Senior Software Engineer, Drug Discovery Workflow](https://jobgether.com/offer/6a62339e1b23f4f87b3398f9-senior-software-engineer---drug-discovery-workflow)
- [Remotive: Senior Software Engineer (closed)](https://remotive.com/remote/jobs/software-development/senior-software-engineer-3777563)
- [Octopus Ventures talent: Senior Software Engineer](https://talent.octopusventures.com/companies/apheris/jobs/72434113-senior-software-engineer)
- [Jobgether: Senior Cloud Platform Engineer](https://jobgether.com/offer/66f78033a00f00c4dee0147a-senior-cloud-platform-engineer)
- [Apheris docs: Gateway architecture](https://www.apheris.com/docs/gateway/latest/general/architecture.html)
- [Apheris docs: Deploy on Kubernetes with Helm](https://www.apheris.com/docs/gateway/latest/gateway/deploy-on-kubernetes-with-helm.html)
- [Apheris docs: Compute specs](https://www.apheris.com/docs/gateway/latest/general/compute-specs.html)
- [GitHub: apheris organisation](https://github.com/apheris)
- [NorthData: apheris AI GmbH, HRB 221842 B](https://www.northdata.de/apheris+AI+GmbH,+Berlin/Amtsgericht+Charlottenburg+(Berlin)+HRB+221842+B) (Chromium over CDP)
- [Handelsregister: HRB 221842 B](https://www.handelsregister.de/rp_web/search.do?registergericht=F1103&registerArt=HRB&registerNummer=221842B)
- [Förderkatalog: OpenFLaaS](https://foerderportal.bund.de/foekat/jsp/SucheAction.do?actionMode=view&fkz=01MD23001B)
- [Förderkatalog: SPELL](https://foerderportal.bund.de/foekat/jsp/SucheAction.do?actionMode=view&fkz=01MK21005J)
- [Glassdoor: apheris AI overview](https://www.glassdoor.com/Overview/Working-at-apheris-AI-EI_IE3480790.11,21.htm) (Chromium over CDP)
- [Glassdoor: apheris AI reviews (English)](https://www.glassdoor.de/Bewertungen/apheris-AI-Bewertungen-E3480790.htm?filter.iso3Language=eng) (Chromium over CDP)
- [Glassdoor: apheris AI reviews (all)](https://www.glassdoor.de/Bewertungen/apheris-AI-Bewertungen-E3480790.htm) (Chromium over CDP)
- [Glassdoor: apheris AI interviews](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/apheris-AI-Fragen-im-Vorstellungsgespr%C3%A4ch-E3480790.htm) (Chromium over CDP)
- [Glassdoor: apheris AI salaries](https://www.glassdoor.com/Salary/apheris-AI-Salaries-E3480790.htm) (Chromium over CDP)
- [Kununu search: apheris](https://www.kununu.com/de/search?q=apheris) (Chromium over CDP; no profile)
- [Teamblind: Apheris](https://www.teamblind.com/company/Apheris) (Chromium over CDP; not found)
- [levels.fyi: Apheris](https://www.levels.fyi/companies/apheris/salaries) (Chromium over CDP; not found)
- [Great Place to Work Germany: certified companies](https://www.greatplacetowork.de/zertifizierte-unternehmen/) (Chromium over CDP)
- [LinkedIn: Apheris company page](https://www.linkedin.com/company/apheris/) (Chromium over CDP)
- [LinkedIn: Apheris people](https://www.linkedin.com/company/apheris/people/) (Chromium over CDP)
- [TechCrunch: Apheris rethinks the AI data bottleneck in life science (Jan 2025)](https://techcrunch.com/2025/01/02/apheris-rethinks-the-ai-data-bottleneck-in-life-science-with-federated-computing)
- [SiliconANGLE: Apheris raises $8.25M (Jan 2025)](https://siliconangle.com/2025/01/02/apheris-raises-8-25m-healthcare-focused-federated-ai-platform/)
- [Apheris: Series A announcement](https://apheris.com/resources/blog/apheris-announces-series-a-fundraise-to-power-the-world-s-leading-life-sciences-d)
- [eCAPITAL: Series A investment](https://ecapital.vc/news/apheris-announces-series-a-fundraise-to-power-the-worlds-leading-life-sciences-data-networks/)
- [Heuking: advises apheris AI GmbH on Series A](https://www.heuking.de/en/news-events/latest-news/article/heuking-advises-apheris-ai-gmbh-on-its-series-a-financing-round.html)
- [Apheris: raises €8.7m seed extension (Nov 2022)](https://www.apheris.com/resources/apheris-raises-eu8-7m-to-power-development-of-smarter-ai) (Chromium over CDP)
- [tech.eu: Apheris seed funding €2.5M](https://tech.eu/brief/apheris-seed-funding)
- [eCAPITAL: AISB Consortium partners / OpenFold3](https://ecapital.vc/news/alquraishi-labs-openfold3-to-be-fine-tuned-with-pharma-industry-data-in-a-secure-ai-collaboration-powered-by-apheris/)
- [Apheris: Launches ADMET Network](https://www.apheris.com/resources/apheris-launches-admet-network)
- [GEN: ADMET Predictions Get AI Boost](https://www.genengnews.com/topics/artificial-intelligence/admet-predictions-get-ai-boost-federated-data-network-unites-pharma/)
- [BiopharmaTrend: Five drugmakers team up on ADMET network](https://www.biopharmatrend.com/news/five-drugmakers-including-recursion-servier-team-up-on-privacy-preserving-admet-ai-1514/)
- [Bio-IT World: Apheris federated co-folding results (Sep 2026)](https://www.bio-itworld.com/news/2026/09/22/apheris-announced-the-results-of-their-federated-learning-co-folding-initiative-now-four-big-pharma-are-betting-bigger)
- [EuropaWire: Apheris and T-Systems expand federated medical research (Oct 2026)](https://news.europawire.eu/apheris-and-t-systems-expand-federated-medical-research-on-sovereign-german-ai-infrastructure/eu-press-release/2026/10/21/08/47/05/183677/)
- [7wData: Apheris profile](https://7wdata.be/company/apheris/)
- [CB Insights: Apheris vs Rhino Federated Computing](https://www.cbinsights.com/compare/apheris-ai-vs-rhino-health)
- [NVIDIA FLARE: Helm chart deployment](https://nvflare.readthedocs.io/en/main/user_guide/admin_guide/deployment/helm_chart.html)
- [OSM Nominatim: Kolonnenstraße 8, Berlin](https://nominatim.openstreetmap.org/search?q=Kolonnenstra%C3%9Fe+8,+10827+Berlin&format=json&addressdetails=1)
- [Overpass API](https://overpass-api.de/api/interpreter)
