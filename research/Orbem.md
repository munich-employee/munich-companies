# Orbem - Full Research Report

_Researched: 2026-06-10_

> **Primary concern: VC-backed, not demonstrably profitable.** Orbem is Series B stage with ~$97-105M raised and an active US expansion. The criteria prefer a profitable, stable employer no longer dependent on VC funding.

---

## Section 1: Company Fundamentals

| Attribute | Detail |
|---|---|
| Founded | November 2019 (TU Munich spin-off) |
| Employees | ~207 (April 2026); ~200+ self-reported |
| Revenue | Not publicly disclosed; "already profitable" per CEO in [Series B press release, Jan 2026](https://www.orbem.ai/newsroom/orbem-secures-eu55-5-million-series-b) |
| Profitability | Claimed profitable (CEO quote, [Series B announcement, Jan 2026](https://www.orbem.ai/newsroom/orbem-secures-eu55-5-million-series-b)); unaudited, no public accounts |
| Ownership | Private; VC-backed (Series B stage) |
| Software-centric | BORDERLINE/FAIL: see assessment below |

**Key People:**
- Pedro Gómez (CEO, PhD biomedical imaging)
- Miguel Molina (CPTO, PhD)
- Maria Laparidou (CSO, PhD)
- Benjamin Rauser (COO)

**Funding History:**

| Round | Date | Amount | Lead Investor(s) | Notable Co-Investors |
|---|---|---|---|---|
| Pre-seed | ~2020 | $1.5M | UnternehmerTUM | 2 undisclosed VCs |
| EIC Grant | 2021 | €2.5M | European Innovation Council | Non-dilutive |
| Seed | 2022 | €5.2M | The Venture Collective | Possible Ventures, angel network |
| Series A | October 2023 | €30M | 83North | La Famiglia, General Catalyst, angel network (Personio founders, Rubin Ritter, Celonis co-founder) |
| Series B | January 2026 | €55.5M | Innovation Industries, Supernova Invest | General Catalyst, 83North, The Venture Collective, Possible Ventures |
| **Total raised** | | **~$97-105M** | | |

**Business Model:** B2B hardware-plus-software sales. Orbem sells physical MRI systems (the Genus product line) combined with AI software to agricultural and biological industries. Revenue comes from hardware unit sales and recurring software/data services. Customers are poultry hatcheries, food producers, and agricultural operators. A US office opened in Houston, TX in 2025 for North American expansion.

**Software-Centric Assessment:**

Orbem is genuinely AI-intensive: MRI data from every scan feeds a large biological dataset, and AI inference is core to the value delivered. The engineering team recruits Machine Learning Engineers, Software Integration Engineers (Python), and cloud/infrastructure engineers. The technology stack includes Python, PyTorch, Docker, GitLab CI, Kubernetes, Terraform, Prometheus, and Grafana.

However, the fundamental commercial product is a physical MRI scanner (Genus Focus, Genus Scale). The hardware is not incidental or a delivery medium: it is what customers purchase and physically install in their production lines. Software Integration Engineer job postings explicitly describe "building software that integrates hardware components, cloud infrastructure, AI algorithms and MRI technology" and communicate via "WebSockets, TCP, OPC-UA, Modbus, PLCs, and industrial PCs." A dedicated Sr. Software Engineer - Hardware Integration role exists in current postings.

**Verdict: BORDERLINE on software-centric criterion.** The revenue-generating asset is a physical MRI device, but AI is the core differentiator and the primary engineering track (Staff ML Engineer) is pure software. The criteria ask whether "software-centric approach is integral to company's strategy" - for Orbem, AI software IS the strategic differentiator, but the thing customers buy and install is hardware. This is a judgment call, not a clear disqualifier.

---

## Section 2: Local Commercial Entity

| Attribute | Detail |
|---|---|
| Entity | Orbem GmbH |
| Registration | Amtsgericht München, HRB 252715 |
| Address | Wilhelmine-Reichard-Straße 7, 2nd floor, 80935 Munich |
| VAT | DE327553341 |
| Share Capital | €64,188 (as of August 2025) |
| Registered Purpose | "Research, development, approval, production and distribution of software and hardware, in particular in the medical, veterinary, agricultural, food and industrial fields" |
| Managing Directors | Dr. Pedro Gomez Damian, Dr. Maria Laparidou, Dr. Miguel Molina Romero |
| Founded | 13 November 2019 |

Verified via NorthData (northdata.com) and the company's own legal notice page (orbem.ai/legal-notice). The entity is a straightforward GmbH with three PhD co-founders as managing directors. The registered purpose explicitly covers both hardware and software, consistent with the product being a physical MRI device. 34 known active shareholders as of latest filings, consistent with multiple VC rounds. EU funding of €2.45M also recorded against the entity.

**Verdict: PASS.** German GmbH entity confirmed, directly employs staff in Munich, engineers would receive a standard Arbeitsvertrag. No EOR/PEO arrangements indicated.

---

## Section 3: Location

**Office address:** Wilhelmine-Reichard-Straße 7, 80935 Munich (Feldmoching-Hasenbergl district, northern Munich)

**Nearest transit:** The office is served by U2 (Feldmoching direction) and bus line 173. The closest U-Bahn stop is Feldmoching (U2) approximately 5-10 minutes on foot.

**Additional location:** Orbem also has a presence in Garching bei München (U6 northern terminus).

**Work model:** Hybrid. Job postings confirm flexible hours and home office, with "Work from Anywhere" for up to 60 days per year. Kununu reviews mention remote flexibility. No mandatory daily on-site requirement evident. Some hardware-adjacent roles (Software Integration Engineer) likely require more frequent on-site presence due to physical MRI hardware.

---

## Section 4: Reviews

**Great Place to Work (GPTW):** No GPTW certification found for Orbem. Only award found: Google for Startups Accelerator member (2022).

### Glassdoor

Data collected via authenticated Playwright session (2026-06-10):

| Filter | Score | Reviews | Recommend |
|---|---|---|---|
| Global (all) | 5.0 | 9 (Glassdoor profile) / 35 (FAQ text) | 100% |
| Munich | 4.9 | 16 | 100% |
| Senior Software Engineers | No dedicated filter; MLE reviews: 5.0 | n/a | n/a |

Note: The Glassdoor review count shown varies between data sources (9-35 reviews depending on which page element is queried). The score of 5.0 / 4.9 on a small sample (9-35 reviews) must be treated with significant caution - it likely reflects a self-selected, enthusiastic early-team sample rather than a stable equilibrium rating. For comparison, both Glassdoor and Kununu place the score well, but the sample size limits statistical confidence.

Sub-category ratings (Glassdoor, Munich-filtered):

| Category | Score |
|---|---|
| Culture & Values | 5.0 |
| Diversity & Inclusion | 5.0 |
| Senior Leadership | 4.9 |
| Career Opportunities | 4.8 |
| Compensation & Benefits | 4.6 |
| Work-Life Balance | 4.4 |

CEO approval: Not disclosed in accessible data. Business outlook: 87% positive (per FAQ text).

Interview difficulty: 2.9 / 5. Positive interview experience: 36%.

### Kununu

URL: https://www.kununu.com/de/orbem2

| Metric | Value |
|---|---|
| Overall score | 3.9 / 5 |
| Total reviews | 40 (27 employee, 13 applicant) |
| Recommendation rate | 100% (last 2 years) |
| Industry comparison | Better than Administration/Verwaltung average (3.4) |
| Salary satisfaction | 85% rate salary as good or very good (27 reviews) |
| Culture assessment | "eher modern" (rather modern), based on 19 culture reviews |

Best-rated category: Arbeitsatmosphäre (work atmosphere) at **4.9** (15 reviews).

Karriere/Weiterbildung (career development): **4.5** (11 reviews).

Salary data (Kununu, 8 reported figures):
- Manager Business Development: Ø €87,200
- Recruiter: Ø €67,700
- Softwareentwickler:in: Ø €47,700

The Softwareentwickler:in salary of €47,700 from Kununu is either very outdated (early-stage salaries from 2020-2021) or reflects junior roles, as advertised job postings now show €60,000-€75,000 + equity for senior positions.

Kununu score of **3.9** exactly meets the stated threshold of 3.6+; the 100% recommendation rate is strong. Score is reliable at 40 reviews.

### Blind / Teamblind

No Orbem-specific page found on Teamblind. The company is too small and too European-focused to have meaningful Blind coverage (Blind is predominantly used by US Big Tech employees).

### Review Themes

**Positives (from Kununu and Glassdoor):**
- Outstanding work atmosphere; "one team" feeling; mutual trust and autonomy
- High-quality colleagues from diverse international backgrounds (40+ nationalities)
- Meaningful mission (animal welfare, food sustainability)
- Transparent communication and modern leadership philosophy
- Good career development opportunities given company growth
- Flexible hours and remote work options praised
- Strong sense of ownership and impact

**Negatives / Areas for improvement:**
- Office space limited given team growth (older reviews, pre-2023)
- "Wish they were more open to remote team members, but I understand many people need to work with hardware onsite" (consistent with hardware integration requirements)
- Startup-typical future uncertainty
- Early reviews (2021) note "limited to hustlers only" - high-pace environment
- Career paths less structured than larger companies

**Toxic Leadership Assessment:**

| Signal | Finding |
|---|---|
| Leadership instability / frequent C-suite changes | None found; same three co-founders lead since 2019 |
| Mass layoffs or RIFs | No evidence found at all |
| WLB red flags (24/7 culture) | No. Glassdoor WLB 4.4, some early "hustler" references |
| Surveillance / micromanagement mentions | None found |
| Discrimination or inclusion concerns | None found; D&I rated 5.0 |
| PIP culture references | None found |
| CEO controversy | None found |

**Risk level: LOW.** No toxic leadership signals detected across Glassdoor or Kununu.

---

## Section 5: Compensation

**Orbem-advertised ranges (from job postings, Jan-Jun 2026):**

| Role | Base Salary | Equity (ESOP) | Benefits |
|---|---|---|---|
| Machine Learning Engineer | €60,000-€65,000 | €10,000-€30,000 | €5,000/yr + €1,750 L&D |
| Senior Software Integration Engineer (Python) | €70,000-€75,000 | €20,000-€40,000 | €5,000/yr + €1,750 L&D |
| CISO | €120,000-€135,000 | Not specified | Standard benefits |

No public data on Staff ML Engineer salary was located. Extrapolating from the Senior band (€70-75K base) and the CISO data point, a Staff ML Engineer band likely falls in the **€80,000-€95,000 base** range with equity of €30,000-€60,000 ESOP. This is consistent with Munich startup market rates at the Series B stage but significantly below Big Tech or established profitable companies.

**Levels.fyi Munich context:**
- Senior SWE Munich median: €84,000-€121,000 total comp
- Staff SWE Munich (no Orbem data): typically €110,000-€140,000+ at larger companies

**Equity:** ESOP (Employee Stock Ownership Plan) rather than RSUs. As a private company, liquidity is event-driven (acquisition or IPO). The €55.5M Series B was led by Innovation Industries and General Catalyst - serious institutional investors that do target exits, but timing is unknown. ESOP at Series B stage typically carries meaningful dilution risk and uncertain vesting timelines.

**Benefits package:**
- Deutschlandticket (full public transit coverage)
- Urban Sports Club or Wellpass fitness membership
- Childcare (Kita/Kindergarten) reimbursement
- €185 home office setup + external monitor
- Work from Anywhere up to 60 days/year
- 30 days paid leave
- Bike leasing
- Pension scheme (deferred compensation)
- Corporate benefits discounts

**Verdict: BORDERLINE.** Base salary at Senior level (€70-75K) is materially below Munich market expectations. Equity upside exists but is illiquid and speculative at Series B stage.

---

## Section 6: AI/ML and Tech Stack Fit

**AI Strategy:** Orbem's core thesis is that AI-powered MRI can unlock biological intelligence at industrial scale. The AI components include deep learning for egg sex determination, fertilization detection, fruit quality assessment, and health applications. The company is building what it describes as "the world's largest biological dataset." AI inference runs in under one second per scan on edge devices. The ML engineering challenge involves training, optimizing, and deploying models for low-latency edge inference on custom MRI hardware - technically demanding work.

**Tech Stack:**

| Layer | Technologies |
|---|---|
| ML / AI | Python, PyTorch, deep learning, model optimization |
| ML Ops | Docker, GitLab CI, experiment tracking (ML tools), Prometheus, Grafana |
| Cloud Infra | Kubernetes (on Proxmox VE hybrid), Terraform, Helm, Ansible |
| Edge / Hardware | Lightweight Kubernetes on-prem, PLCs, OPC-UA, Modbus, TCP, WebSocket |
| CI/CD | GitLab CI, SonarCloud quality gates |
| Monitoring | Prometheus, Grafana, Elasticsearch |

Python is clearly the primary language for ML engineering. The infrastructure layer also uses Terraform (HCL) and Ansible. Hardware integration requires familiarity with industrial protocols (OPC-UA, Modbus, PLC) - this is the "hardware adjacent" layer, though the boundary is fuzzy (it is integration code in Python, not C/C++).

**Current Open Roles (as of June 2026):**

| Role | Level | Notes |
|---|---|---|
| Staff Machine Learning Engineer | Staff | Match |
| Machine Learning Engineer | Mid-Senior | Slightly below target seniority |
| Senior Software Integration Engineer - Python | Senior | Python-based; integrates MRI hardware |
| Senior Staff Software Integration Engineer | Senior/Staff | Same hardware integration focus |
| Senior Software Engineer - Hardware Integration | Senior | Hardware integration focus (borderline exclusion) |
| Senior Software Engineer in Test | Senior | QA/testing focus |
| Senior Software Engineer - Internal Tools | Senior | Internal tooling |
| Chief Information Security Officer | C-level | Not relevant |

The Staff Machine Learning Engineer role is the strongest match. The ML Engineer posting (now closed but cached) described: Python/PyTorch, model training and optimization, edge deployment, monitoring with Prometheus/Grafana.

**Verdict: STRONG FIT on technical stack** (Python, PyTorch, ML engineering, optimization) and **STRONG FIT on role level** (Staff ML Engineer exists). The hardware adjacency concern is the primary disqualifier, not the technology.

---

## Section 7: Language

Orbem is an international team of 200+ people from 40+ nationalities across 5 continents. Job postings confirm:
- English C1 required; German not required
- Team communications, documentation, and engineering work conducted in English
- No German-only requirement found in any engineering posting

This is reinforced by the Kununu and Glassdoor review language mix (English and German both present) and the career page descriptions of "40+ nationalities."

**Verdict: PASS.** English is the working language. No German language requirement for engineering roles.

---

## Section 8: Stability

**Financial Position:**

Orbem is a VC-backed Series B startup, not a profitable established company. The CEO stated in the [January 2026 Series B press release](https://www.orbem.ai/newsroom/orbem-secures-eu55-5-million-series-b) that Orbem is "already profitable and a leading provider of in-ovo sexing in five European countries." This claim of profitability is not independently audited and is typical Series B PR framing. Even if true, it likely means contribution-margin-positive or adjusted EBITDA-positive on existing operations, not GAAP net income positive including R&D spend and the new US expansion.

The company has raised ~$97-105M total across five rounds. The Series B of €55.5M closed January 2026.

**Financial Runway (bottom-up burn rate model):**

| Scenario | Assumptions | Monthly Burn | Runway from Jan 2026 |
|---|---|---|---|
| Conservative | 207 employees x €7,500 avg all-in cost + €500K/mo other costs | ~€2.0M/mo | ~27 months (to Apr 2028) |
| Base | 207 employees x €8,500 all-in + R&D/capex + US expansion | ~€2.5M/mo | ~22 months (to Nov 2027) |
| Aggressive growth | 250 employees within 12 months + US ramp | ~€3.2M/mo | ~17 months (to Jun 2027) |

Hardware companies typically have higher COGS than pure software companies (physical MRI manufacturing, inventory, logistics). This compresses effective runway even if gross margins on installed base are decent. The US expansion (Houston office opened 2025) adds additional burn.

If the company is genuinely profitable on existing operations, the runway extends considerably - the Series B would be used for growth acceleration rather than survival. However, this cannot be independently verified.

**Layoffs:**

| Date | Type | Scale |
|---|---|---|
| No layoffs found | - | - |

No layoffs or RIFs detected in any media coverage, Glassdoor reviews, or LinkedIn activity searches. The company has been in consistent growth mode since founding.

**Verdict: FAIL on stability criterion.** Orbem is VC-backed and not demonstrably profitable by any independently verified metric. Orbem is an early-stage deep tech company with a 2-2.5 year runway at most on current raise. Even with claimed profitability on operations, the US expansion and R&D investments ensure continued VC dependency for several more years.

---

## Section 9: Regulated Industry

Orbem's primary commercial products target:
- **Poultry industry (in-ovo egg sexing):** Not a medically regulated sector; agricultural applications fall outside FDA/CE-MDR device classification. Orbem's poultry MRI is an industrial/agricultural tool, not a medical device.
- **Food quality (fruits, vegetables):** No regulatory oversight equivalent to medical devices.
- **Healthcare (future applications):** Orbem explicitly names healthcare as a future direction, but no current healthcare products are commercially available or approved.

The registered purpose in the Handelsregister explicitly covers "medical, veterinary, agricultural, food and industrial fields," which anticipates regulated sectors. The NorthData filing also records multiple patents and trademarks. However, as of June 2026, Orbem's current revenue is from agricultural applications that are **not regulated as medical devices** under FDA 510(k), CE-MDR, or IVDR.

Orbem's current products do not carry the compliance burden of that prior employer.

**Verdict: PASS (currently).** Orbem operates in agricultural sectors not subject to medical device regulation for its current products. Future healthcare expansion could introduce this, but it is not a present concern.

---

## Section 10: On-Call

No on-call duty requirements were found in any Orbem job posting (ML Engineer, Software Integration Engineer, Senior Software Engineer roles all reviewed). The "no explicit language requirements or on-call duties mentioned" finding from the ML Engineer posting is consistent across all reviewed postings.

Given the industrial/B2B nature of the product (MRI machines in hatcheries), there may be implicit availability expectations for production incidents affecting customer deployments, but this is not formalized as on-call rotations in any public posting.

**Verdict: PASS.** No regular on-call duty found or indicated in job postings.

---

## Section 11: Interview Process

Data from Glassdoor (cached interview reports, 2024-2025):

| Metric | Value |
|---|---|
| Difficulty | 2.9 / 5 |
| Positive experience | 36% |
| Interviews reported | ~21 questions documented |
| Typical duration | ~4 weeks |

**Process stages (reported by candidates):**
1. Initial HR screening call (recruiter or headhunter) - smooth, behavioural questions, e.g. "how would you explain a technical term to a non-technical person"
2. Online assessment (take-home): split into two parts - logical/mathematical assessment (~40 questions, under 20 minutes, no calculator allowed) and a personality questionnaire (~100+ questions, 60-75 minutes total)
3. Technical interview: whiteboard/design questions, system design, conflict resolution scenarios
4. Final rounds with senior leadership or heads of the company

**Notes:** The low positive experience rate (36%) contrasts sharply with the very high employee review scores. This pattern often reflects that rejection is disappointing and candidates attribute the experience negatively regardless of process quality. The process itself is described as fairly standard for a startup. The take-home logical assessment appears to be a standard psychometric test used across all roles.

---

## Section 12: Summary Assessment

| Criterion | Status | Notes |
|---|---|---|
| Own product / not consulting | PASS | Own product (Genus MRI line); no consulting |
| Software-centric company strategy | BORDERLINE | AI is the core differentiator, but the product customers buy is a physical MRI device |
| Profitable / not VC-subsidized | FAIL | Series B VC-backed; profitability unverified |
| Glassdoor above 4.0 | PASS (caution) | 5.0 / 4.9 but only 9-35 reviews - very thin sample |
| Kununu above 3.6ation | PASS | 3.9 / 100% recommendation |
| No repeated red flags in reviews | PASS | No toxic signals detected |
| English working environment | PASS | English-first; German not required |
| Munich-based for hybrid | PASS | HQ in Munich, Feldmoching district |
| Location / work model | - | Feldmoching, on U2 + bus 173 |
| German GmbH entity | PASS | Orbem GmbH, HRB 252715 confirmed |
| German Arbeitsvertrag (not PEO/EOR) | PASS | Direct GmbH employment |
| Full-time permanent | PASS | Standard employment offered |
| Backend/cloud/AI-ML engineering track | PASS | Staff ML Engineer role is direct match |
| Python as primary language | PASS | Python confirmed as core ML stack |
| No embedded C/C++ engineering | PASS (target role) | Staff ML Engineer is Python/PyTorch, no C/C++. Software Integration Engineer roles use Python but interface with industrial protocols (OPC-UA, Modbus) - not the target role. |
| No regular on-call | PASS | No on-call found in postings |
| Staff or Senior level available | PASS | Staff ML Engineer role confirmed open |

---

## Section 13: Verdict

**Not recommended for application at this time.** Orbem is an impressive company with genuinely strong engineering culture and a direct role match.

**Strengths:**
- Exceptional culture signals: Kununu 3.9 (100% recommendation), Glassdoor 4.9 in Munich, no toxic leadership signals anywhere
- Direct role match: Staff Machine Learning Engineer role is open
- English-first international team (40+ nationalities); no German requirement
- Meaningful mission (animal welfare, food sustainability) with proven commercial traction (170M eggs scanned, 5 European countries)
- Good benefits package; hybrid with genuine flexibility; no on-call burden
- Registered German GmbH, direct Arbeitsvertrag, no EOR/PEO complications
- Technically deep ML work: edge inference optimization, large biological dataset, sub-second latency targets
- Target role (Staff ML Engineer) is pure Python/PyTorch with no embedded C/C++ requirement

**Hard blockers:**

1. **VC-backed, not demonstrably profitable.** Orbem is Series B with ~$97-105M raised, dependent on continued institutional backing, and mid-way through an expensive US expansion. The claimed profitability in press statements is not independently verifiable and is inconsistent with the scale of reinvestment being undertaken. Runway on the Series B is estimated at 17-27 months depending on growth trajectory.

**Secondary concerns:**
- Software-centric criterion is borderline: AI is Orbem's core differentiator, but the product customers purchase and install is a physical MRI machine. This is a judgment call rather than a hard disqualifier.
- Salary at Senior level (€70-75K base) is below market expectations; a Staff band would likely reach €85-95K base - still below target at comparable profitable companies.
- Glassdoor score of 5.0/4.9 on 9-35 reviews is statistically unreliable; could regress significantly as headcount scales.
- Software Integration Engineer roles (not the target role) involve hardware protocol integration (OPC-UA, PLCs) - not a concern for the Staff ML Engineer track specifically.

**Recommendation:** If Orbem's claimed profitability is independently confirmed in annual filings (typically available via Bundesanzeiger 12-18 months after fiscal year end) and the US expansion stabilizes burn rate, the calculus changes materially: the role fit, culture, and language profile are all strong. At that point, verifying the actual Staff ML Engineer salary band and clarifying hybrid expectations would be the key remaining items.

---

## Section 14: Sources

1. [Orbem About page](https://www.orbem.ai/about)
2. [Orbem Technology page](https://www.orbem.ai/technology)
3. [Orbem Careers page](https://www.orbem.ai/careers)
4. [Orbem Legal Notice](https://www.orbem.ai/legal-notice)
5. [Orbem Series B announcement](https://www.orbem.ai/newsroom/orbem-secures-eu55-5-million-series-b)
6. [Orbem Series A announcement](https://orbem.ai/orbem-series-a/)
7. [NorthData - Orbem GmbH HRB 252715](https://www.northdata.com/Orbem%20GmbH,%20M%C3%BCnchen/HRB%20252715)
8. [EU-Startups Series B coverage](https://www.eu-startups.com/2026/01/from-eggs-to-avocados-germanys-orbem-raises-e55-5-million-for-ai-powered-mri-expansion)
9. [Trending Topics Series B coverage](https://www.trendingtopics.eu/orbem-raises-e55-5-million-for-ai-powered-mri-technology/)
10. [Munich Startup Series B coverage](https://www.munich-startup.de/en/116370/orbem-series-b/)
11. [Kununu - Orbem](https://www.kununu.com/de/orbem2)
12. [Glassdoor - Working at Orbem](https://www.glassdoor.com/Overview/Working-at-Orbem-EI_IE4172828.11,16.htm)
13. [Glassdoor - Orbem Munich reviews](https://www.glassdoor.com/Reviews/Orbem-Munich-Reviews-EI_IE4172828.0,5_IL.6,12_IC4990924.htm)
14. [Glassdoor - Orbem interview questions](https://www.glassdoor.com/Interview/Orbem-Interview-Questions-E4172828.htm)
15. [Glassdoor - Orbem ML Engineer job listing](https://www.glassdoor.com/job-listing/machine-learning-engineer-fmd-orbem-gmbh-JV_IC4990924_KO0,29_KE30,40.htm?jl=1009862254655)
16. [Orbem Staff ML Engineer posting (cached)](https://orbem.recruitee.com/o/staff-machine-learning-engineer-fmd)
17. [Orbem Senior Software Integration Engineer posting](https://orbem.recruitee.com/o/senior-software-integration-engineer)
18. [ML Engineer job description via jaabz.com (cached)](https://jaabz.com/jobs/146993-machine-learning-engineer-fmd)
19. [Orbem HR career page / Ashby job board](https://jobs.ashbyhq.com/orbem)
20. [Orbem on Tracxn](https://tracxn.com/d/companies/orbem/__usSp6ZiCcaZuhIMBpH8Z_seg_3SmqVmJipZWgQRllp0)
21. [Orbem on Crunchbase](https://www.crunchbase.com/organization/orbem-ff8b)
22. [Orbem on Startup Intros](https://startupintros.com/orgs/orbem)
23. [Orbem pre-seed via Signalbase](https://www.trysignalbase.com/news/funding/orbem-secures-15m-pre)
24. [Netguru case study - Orbem AI-powered imaging](https://www.netguru.com/clients/orbem-ai-powered-imaging)
25. [Orbem - Software Integration Engineer job via Arbeitnow](https://www.arbeitnow.com/jobs/companies/orbem/software-integration-engineer-python-munchen-118924)
26. [Orbem on ZoomInfo](https://www.zoominfo.com/c/orbem-gmbh/563149650)
27. [Orbem on herCAREER](https://www.her-career.com/en/paussteller/orbem-gmbh-hercareer-2025-en/)
28. [Levels.fyi - Senior SWE Munich](https://www.levels.fyi/t/software-engineer/levels/senior/locations/munich-deu)
30. [Orbem Munich Startup profile](https://www.munich-startup.de/en/startups/orbem/)
