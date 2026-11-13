# Leibniz-Rechenzentrum (LRZ, Leibniz Supercomputing Centre) - Full Research Report

_Researched: 2026-09-24_

> **Critical Disqualifiers**
> 1. **Not a company, and not profitable by construction.** LRZ is an institute of the Bavarian Academy of Sciences and Humanities (BAdW), a public-law corporation (Körperschaft des öffentlichen Rechts) funded by the Free State of Bavaria and the federal government. It has no revenue model, no profit and no equity. The "mature, profitable company" criterion cannot be met.
> 2. **Every current IT role is fixed-term.** The three HammerHAI AI Factory roles end "End of Q1/2028, further employment is intended"; the wiki sysadmin role ends 31.12.2028. This fails the "full-time, permanent" criterion.
> 3. **Pay is capped at TV-L E13**, roughly €67k to €85k gross per year depending on the pay step. No bonus, no equity. That is well below the Munich senior-engineer range at large profitable companies.
> 4. **No Senior Software Engineer role with Python at its core is open.** The closest posting, *Data Platform Engineer*, centres on the piveau data catalogue (a Java/Kotlin Vert.x stack), FAIR metadata workflows and stakeholder work. Software engineering itself is listed only as "basic knowledge" under preferred qualifications.
> 5. **Too few reviews to verify a strong reputation.** Glassdoor has 3 reviews and Kununu 14. The scores are good (4.4 on both) but statistically meaningless.
>
> This is an **EXCLUDE**. The full report follows for completeness.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 1962, as the BAdW "Kommission für elektronisches Rechnen" (64 years) |
| Employees | ~300 (2023 annual report: 298 staff from 50 countries; 155 scientific staff, 86 technical/administrative, 50 student assistants, 7 apprentices). LRZ now says "more than 300" |
| Revenue (FY2025) | No commercial revenue. Funding comes from the BAdW budget line (Free State of Bavaria), federal/state co-funding for national HPC through the Gauss Centre for Supercomputing (GCS), and project grants (EuroHPC, BMBF/BMFTR, Hightech Agenda Bayern). No consolidated annual budget is published; the latest annual report (2023) does not state one |
| Profitability | **N/A: FAIL.** A public-law institute cannot pursue profit |
| Ownership | Public. An institute of BAdW (K.d.ö.R.), under the Bavarian State Ministry of Science and the Arts (StMWK) |
| Software-centric | IT service provider and HPC operator for the Munich and Bavarian universities, with a research arm. **BORDERLINE / FAIL**, see below |

### Key People

LRZ is run by a Board of Directors (Direktorium) of professors:
- **Prof. Dr. Dieter Kranzlmüller**: Chair of the Board and head of LRZ (named in the Impressum)
- **Prof. Dr. Helmut Reiser**: Deputy head, responsible for operations
- **Prof. Dr. Hans-Joachim Bungartz**, **Prof. Dr. Martin Schulz**, **Prof. Dr. Thomas Seidl**: Board members (all TUM/LMU professors)

### Funding History

Not applicable: there is no venture or private-equity funding. Major capital programmes:

| Date | Programme | Amount | Funders |
|---|---|---|---|
| 2018/2019 | SuperMUC-NG (Lenovo/Intel) | amount not verified in this research | BMBF + StMWK via GCS |
| Dec 2024 | **Blue Lion** (HPE Cray + NVIDIA, live early 2027) | **€250M** including operating costs 2027 to 2032 | BMBF and StMWK, 50/50 |
| 2023 | AQT 20-qubit ion-trap quantum computer (Munich Quantum Valley) | ~€9.8M | StMWK + StMWi, Hightech Agenda Bayern |
| 2023 | terrabyte (joint with DLR) | multi-€M (DLR-funded hardware, LRZ covers operations and staff) | DLR / LRZ |
| 2025 to 2028 | **HammerHAI** EuroHPC AI Factory (led by HLRS Stuttgart; LRZ is a partner) | €85M consortium-wide | EuroHPC JU, BMBF, Baden-Württemberg, Bavaria, Lower Saxony |

### Business Model

LRZ has three mandates: (1) the computing centre for all Munich universities (LMU, TUM, HM and others: network, email, storage, cloud, identity, collaboration tools); (2) the regional computing centre for all Bavarian universities; and (3) one of Germany's three national supercomputing centres within the Gauss Centre for Supercomputing, alongside HLRS Stuttgart and JSC Jülich. It also runs research groups (quantum computing integration, AI systems, energy efficiency, environmental computing). Customers are researchers and universities, served under a statutory mandate, not a market.

### Software-Centric Assessment

**BORDERLINE leaning FAIL.** The organisation's centre of gravity is **operating infrastructure**: supercomputers, network (the Munich Scientific Network, MWN), storage, data centre facilities, desktop and collaboration services, plus user support and training. Software development does happen (HPC tooling, the Rust `avina` project and Python `ai-systems` / `lrzcc-py` repos on the LRZ-BADW GitHub, portals, research software for the quantum integration centre), but it serves operations and research. It is not a software product organisation. The open postings confirm this: data-platform integration, AI training/education, customer success, and a Confluence administrator.

### Consulting-Adjacency Assessment

**Moderately consulting-adjacent in the AI Factory roles.** LRZ does not bill hours or use consultant titles. However, the HammerHAI roles explicitly include "educational (and consultancy) offers for, primarily, manufacturing and engineering SMEs and start-ups", "analysing the requirements and needs of targeted user groups with respect to training (and consulting)", and "supporting and enabling customers to publish, access and share their own AI data sets". The AI Factory is designed as a service-and-advisory hub for external industry users. Core LRZ operations roles are **not** consulting. **Verdict: PASS for core LRZ, CAUTION for the HammerHAI roles** (the external-facing enablement work comes close to the solutions-engineer pattern).

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **Bayerische Akademie der Wissenschaften (BAdW)**, acting through its institute Leibniz-Rechenzentrum | No Handelsregister entry. A public-law corporation (K.d.ö.R.) established under Bavarian state law; listed on BayernPortal as a Bavarian authority ("Bayerische Akademie der Wissenschaften Leibniz-Rechenzentrum") | Boltzmannstraße 1, 85748 Garching bei München (LRZ); BAdW seat: Alfons-Goppel-Str. 11, 80539 München | Per the BAdW "Geschäftsordnung für das Leibniz-Rechenzentrum": IT service centre for the Munich universities and BAdW, regional computing centre for Bavarian universities, and national high-performance computing centre. LRZ has its own budget line within the BAdW budget and manages its affairs independently |

**Verification:** NorthData and the Handelsregister do not apply, because a public-law corporation is not a commercial company and is not entered in the commercial register (confirmed through the LRZ Impressum, which points to BAdW, and the BAdW statutes). Employment is **direct, with the public employer, under the TV-L collective agreement** (Tarifvertrag für den öffentlichen Dienst der Länder), with VBL occupational pension. No PEO/EOR is involved, and there is no sales-shell concern. The purpose is clearly engineering/operations.

**Verdict:** **PASS.** This is the most secure possible employer entity, though it is a public authority, not a company.

---

## Section 3: Office Location

- **Office address:** Boltzmannstraße 1, 85748 Garching bei München, in the Hochschul- und Forschungszentrum Garching campus, next to TUM's Faculty of Informatics/Mathematics. Nominatim geocodes it to 48.26149, 11.66789 and labels it "Leibnitz-Rechenzentrum, Boltzmannstraße 1, Hochschul- und Forschungszentrum".
- **Nearest public transit:** **U6 Garching-Forschungszentrum** (northern terminus), ~560 m walk. Job postings advertise "Bus und U-Bahn (U6) vor der Haustür" (bus and U6 at the door) and free parking.
- **Work model:** "Up to 60% mobile work for suitable tasks" (HammerHAI and sysadmin postings, Sept 2026), flexitime with electronic time recording, overtime compensated with time off. Mostly two-person offices, no open-plan.

---

## Section 4: Reviews

**GPTW:** LRZ does **not** appear on the Great Place to Work Germany lists and holds no GPTW certification (searched greatplacetowork.de lists and the web). It has no Kununu Top Company award either.

### Glassdoor

Profile: *Leibniz Supercomputing Centre* (E308233), retrieved via Chromium over CDP (logged-in session, glassdoor.de). Only **3 reviews** are shown (search-engine snippets mention 7 to 10 historically; the rest appear to have been removed or merged).

| Metric | Global | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | 4.4 (3 reviews) | 4.4 (3; all reviews are Germany-based) | 3.0 (1 review, "HPC engineer", Oct 2024) | 3.0 (1, HPC engineer) |
| **WLB** | 4.6 | 4.6 | n/a | n/a |
| **Culture & Values** | 4.7 | 4.7 | n/a | n/a |
| **Comp & Benefits** | 4.3 | 4.3 | n/a | n/a |
| **Career Opportunities** | 3.6 | 3.6 | n/a | n/a |
| **Diversity & Inclusion** | 4.8 | 4.8 | n/a | n/a |
| **% Recommend** | 100% | 100% | n/a | n/a |
| **CEO Approval** | not shown | not shown | n/a | n/a |
| **Business Outlook** | 100% positive | 100% positive | n/a | n/a |

**Well below 20 reviews in every column; the scores are anecdotal, not directional.** The three reviews: an HPC engineer (2024, 3.0: "Good colleagues, hybrid work possible" / "Expensive city, relatively low salary"), a student assistant (2021, 5.0, noting "Schichtarbeit im 3-Schichtbetrieb 24/7" (24/7 three-shift work) for the operator desk), and an employee (2015, 4.0: "Paradise for nerds"... "the public-service factor limits career opportunities, but most stay for life").

### Kununu

Retrieved via Chromium over CDP (curl returned HTTP 405 bot-block for every slug). There are two profiles:

- **leibniz-rechenzentrum-der-bayerischen-akademie-der-wissenschaften** (main)
  - **Overall score:** 4.4 / 5.0
  - **Recommendation rate:** 92% overall (review list); "k.A." (no data) for the last 2 years
  - **Total reviews:** 16 (14 employee reviews, since 2013)
  - Sub-scores: Career & Salary 3.7, Company culture 4.2, Work environment 4.3, Diversity 4.8
  - Most confirmed benefits: accessibility 86%, flexible hours 86%, internet use 79%
- **leibnitz-rechenzentrum-muenchen** (misspelled duplicate): 4.6 / 5.0, 3 reviews since 2024, 100% recommend, Career & Salary 4.6
- **Kununu Top Company:** NO (profile is not claimed; "nicht auf kununu aktiv")

Salary data points on Kununu: 3 (not broken down by role).

### Blind / Teamblind

`teamblind.com/company/Leibniz-Supercomputing-Centre` returns 404; no company profile exists. This is expected for a ~300-person German public institute.

### Review Themes (2015-2026)

**Positives:**
- **Relaxed, collegial atmosphere, no pressure.** "Kein Druck von oben" (no pressure from above); "Selbstbestimmtes Arbeiten, sehr lockeres Betriebsklima, viel Einfluss auf die eigenen Tätigkeiten" (self-directed work, a very relaxed climate, a lot of influence over one's own tasks) (Kununu, 2023)
- **Work-life balance:** flexitime, no restrictions on holiday planning, overtime compensated with time off, 30 days leave plus 24.12 and 31.12 off, up to 60% mobile work
- **Two-person offices, excellent equipment, modern building**, cutting-edge hardware (supercomputers, quantum, Cerebras)
- **International and diverse:** 50 nationalities; Diversity scored 4.8 on both Kununu and Glassdoor
- **Job security:** "most stay for life"

**Negatives:**
- **Salary:** "relatively low salary" in an "expensive city" (Glassdoor HPC engineer, 2024); "leistungsunabhängiges Gehalt" (pay unrelated to performance) (Kununu, 2023)
- **Career progression:** "kaum Aufstiegschancen" (hardly any promotion chances), "wenig Weiterbildung" (little training), "Karriere/Weiterbildung: abgesehen von Video-Schulungen kaum" (hardly any apart from video courses); Career sub-scores of 3.6 (Glassdoor) and 3.7 (Kununu) are the lowest on both platforms
- **Internal communication and long-term prospects for new staff:** "Kommunikation verbessern, langfristige Perspektiven für junge/neue Mitarbeiter schaffen" (improve communication, create long-term prospects for young/new staff) (Kununu, 2023). This ties directly to the fixed-term contract pattern.
- **24/7 shift operation** exists for the operator/service desk (student reviewer)

Red-flag overlap: none of the hard red flags (toxic leadership, surveillance, unpaid overtime, silent firings, layoffs) appear. The fixed-term contract culture is the structural concern.

### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | None reported. "Sehr freundliche, lösungsorientierte Vorgesetzte" (very friendly, solution-oriented supervisors) (Kununu) |
| 24/7 Work Expectation | No expectation for regular staff. A 24/7 three-shift operator desk exists (staffed partly by students) |
| Internal Surveillance | None. Electronic time recording is standard public-sector flexitime, not monitoring |
| Fear-driven Management | None. "Kein Druck von oben" (no pressure from above) |
| Communication Breakdown | Mild: one 2023 review asks for better communication |
| Unpaid Overtime | No. Overtime is compensated with time off (stated in postings and reviews) |
| Silent Firings | None. Contract expiry of fixed-term staff is the (non-silent) attrition mechanism: in 2023, 76 people joined and 49 left, out of ~298 |
| Work-Life Balance issues | None. WLB is the strongest theme (Glassdoor WLB 4.6) |

**Risk level: LOW.** What negativity exists is (b) public-sector structure (tariff-bound pay, flat career ladder, project-funded fixed terms), not systemic toxicity. Sample sizes are very small.

---

## Section 5: Compensation

### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| Job postings (Sept 2026) | Data Platform Engineer / AI Education Expert / Customer Success Expert (HammerHAI) | "up to E13 TV-L" | 0 | 0 | see TV-L rows | 3 postings |
| Job posting (Sept 2026) | Systemadministrator Enterprise Wiki | "up to E11 TV-L" | 0 | 0 | ~€59k to €75k | 1 posting |
| TV-L 2026 table (from 1 Apr 2026) | E13 Stufe 3 | €64.4k (€5,366.89/mo) | 0 | ~€2.7k annual special payment | **~€67k** | Tariff table |
| TV-L 2026 | E13 Stufe 4 | €70.5k (€5,873.56/mo) | 0 | ~€2.9k | **~€73k** | Tariff table |
| TV-L 2026 | E13 Stufe 5 | €78.9k (€6,573.97/mo) | 0 | ~€3.3k | **~€82k** | Tariff table |
| TV-L 2026 | E13 Stufe 6 (ceiling) | €81.2k (€6,764.69/mo) | 0 | ~€3.4k | **~€85k** | Tariff table |
| Glassdoor | HPC Specialist | €79.9k to €85.9k | 0 | 0 | ~€80k to €86k | 1 |
| Glassdoor | Wissenschaftlicher Mitarbeiter (research staff) | €60.1k to €72.0k | 0 | 0 | ~€60k to €72k | 6 |
| Glassdoor | IT Administrator | €55.7k to €60.4k | 0 | 0 | ~€56k to €60k | 1 |
| levels.fyi | n/a | n/a | n/a | n/a | n/a | 0 (no company page: 404) |

Notes: The annual special payment (Jahressonderzahlung, TV-L §20) for E13 is roughly 50% of one monthly salary (percentage to be confirmed against the 2026 agreement). A hire from outside the public sector is usually placed at Stufe 1 to 3. §16(5) TV-L allows a higher step or an allowance of up to 20% for "Fachkräftegewinnung" (recruiting skilled staff), which is the only negotiation lever. Tariff raises: +2.0% on 1 Mar 2027 and +1.0% on 1 Jan 2028. The E13 ceiling after full step progression (over 15 years) is ~€85k.

Munich reference (large, profitable corporations, Senior Software Engineer): median ~€85k to €100k total, 75th percentile ~€110k to €120k, 90th percentile ~€130k+ (same bracket as earlier reports in this project). LRZ's realistic entry of ~€67k to €73k sits **roughly €15k to €30k (20 to 30%) below the median**, and the €85k ceiling only reaches the bottom of the median band.

### Equity / Stock

None. A public institute has no equity, RSUs, ESPP or bonus. The offsets are the VBL occupational pension (employer-funded supplementary pension, worth roughly 5 to 6% of salary), 30 days leave plus 2 extra days, and very high job security (once permanent).

### Verdict

**BELOW.** The TV-L E13 ceiling (~€85k, reached only after years of step progression) is below the Munich median for senior engineers at large profitable corporations, and a realistic entry at Stufe 3 to 4 (~€67k to €73k) is far below it.

---

## Section 6: AI/ML & Tech Stack Fit

### AI Strategy

LRZ's AI work is **infrastructure provision for researchers**, not applied AI product development:
- **LRZ AI Systems:** NVIDIA GPU clusters with JupyterHub, Slurm and container-based access (Enroot/Charliecloud-style), serving the Munich universities and MCML
- **Cerebras CS-2** (WSE-2) system, integrated with HPE Superdome Flex
- **BayernKI:** Bavarian AI compute infrastructure shared with NHR@FAU
- **Blue Lion** (from 2027): HPE Cray + NVIDIA next-generation accelerators, €250M, ~30× SuperMUC-NG, explicitly aimed at AI + HPC
- **HammerHAI:** EuroHPC AI Factory (HLRS-led; the AI supercomputer sits in Stuttgart). LRZ contributes the data facility (piveau-based data catalogue/dataspace), education and training, and customer success for SMEs/start-ups
- **terrabyte** (with DLR): Earth-observation high-performance data analytics
- Membership of the Trillion Parameter Consortium

This is genuine AI **platform operations** work (GPU clusters, schedulers, data services), but the posted roles are data-catalogue integration, training delivery and customer success. Nobody is building ML systems or MLOps software as a product.

### Tech Stack

Sources: current job postings (primary), LRZ AI & Big Data technology page, LRZ-BADW GitHub organisation, piveau project documentation.

| Category | Technologies |
|---|---|
| **Primary language(s)** | Python (AI education, `ai-systems`, `lrzcc-py`), Rust (`avina`, most recently pushed repo, 2026-09-23), C/C++/Fortran (HPC, `DPEcho`, `OMMOP`, `RINF`); piveau data platform is Java/Kotlin (Vert.x) |
| **AI/ML** | PyTorch, JAX (AI Education posting), NVIDIA GPU clusters, Cerebras CS-2, JupyterHub |
| **Cloud** | On-premise only: LRZ Compute Cloud (OpenStack-based, accessed via `lrzcc-py`), no hyperscaler |
| **Infrastructure** | Slurm, Kubernetes, containers, Linux, GitLab, CI/CD, HPE Cray (Blue Lion), Lenovo/Intel (SuperMUC-NG) |
| **Data** | Data Science Storage (DSS), LRZ Cloud Storage, piveau (dataspaces, FAIR metadata, DCAT-AP), Common European Data Spaces |
| **Other** | Atlassian Confluence Data Center (BayernCollab), Windows/Debian server administration, ITIL-style certified service management |

### Current Open Roles

Checked: the LRZ careers page (`lrz.de/karriere/aktuelle-stellenangebote`) and each Personio posting, via Chromium CDP, on 2026-09-24. LinkedIn job search for "Leibniz Supercomputing Centre" returned **no matching jobs**. All four roles are active, with an application deadline of **12.10.2026**.

| Role | Division/Team | Level | Key Tech | Link |
|---|---|---|---|---|
| Data Platform Engineer (f/m/d) for the European AI Factory HammerHAI | HammerHAI / data facility | "up to E13", fixed-term to end of Q1/2028 | piveau (Java/Kotlin), FAIR metadata, Linux, GitLab, CI/CD, dataspaces | [Personio 2805900](https://lrz.jobs.personio.de/job/2805900?language=en) |
| AI Education Expert (m/f/d) for HammerHAI | HammerHAI / education & training | "up to E13", fixed-term to end of Q1/2028 | Python, PyTorch, JAX, Linux; mainly designing trainings | [Personio 2805857](https://lrz.jobs.personio.de/job/2805857?language=en) |
| Customer Success Expert (m/f/d) for HammerHAI | HammerHAI / customer success | "up to E13", fixed-term to end of Q1/2028 | CRM, B2B sales (not an engineering role) | [Personio 2805891](https://lrz.jobs.personio.de/job/2805891?language=en) |
| Systemadministratorin (m/w/d) Enterprise Wiki | BayernCollab | "up to E11", fixed-term to 31.12.2028 | Confluence DC, Windows/Debian, Kubernetes | [Personio 2795292](https://lrz.jobs.personio.de/job/2795292) |

**Verdict:** On-premise research infrastructure with a mixed stack (Python and PyTorch for AI user support, Rust/C++/Fortran for HPC tooling, Java/Kotlin piveau for the data catalogue) on Slurm, Kubernetes and NVIDIA GPU clusters. The work is **operations, user enablement and research-project delivery** for academic and SME users, not production software engineering. The one engineering-flavoured posting is data-platform integration with software design as a secondary skill. The fit with a senior Python AI/ML platform engineer profile is weak.

---

## Section 7: Language

- The HammerHAI postings are in English and require "**Excellent English and preferably German** presentation and writing skills" (German preferred, not mandatory) for the Data Platform Engineer and AI Education Expert roles.
- The Customer Success Expert role requires "Excellent English **and German**" (mandatory).
- The Systemadministrator posting is German-only and requires "Sichere Deutsch- und Englischkenntnisse (**Level C**)" (confident German and English, level C).
- The careers site is German-first. Staff come from ~50 countries, and English is common in HPC and research groups. Core university IT services (serving German institutions) are German-dominant.

**Verdict:** **CONDITIONAL.** International HPC/AI project roles are English-workable with German preferred. Service and operations roles for the Bavarian universities typically require C-level German.

---

## Section 8: Stability

### Financial Position

This is institutional funding by the Free State of Bavaria and the federal government. There is no revenue, net income or credit rating to report. The multi-year capital commitments are the clearest signal: **€250M for Blue Lion covering 2027 to 2032**, continuous GCS national funding since 2007, and a headcount that grew from ~260 (2019) to 300+ (2023). LRZ is a statutory institution. Its existence is not at risk.

**Individual role stability is lower than institutional stability.** The HammerHAI roles are funded by a EuroHPC project grant that currently runs to ~Q1/2028. Beyond that, "further employment is intended" is an intention, not a commitment. Under the German WissZeitVG and TzBfG, conversion to a permanent contract depends on a new budget line or follow-on funding.

### Financial Runway

Not applicable. LRZ is neither VC-backed nor loss-making in a commercial sense. It is a publicly funded institute without equity financing, so a burn-rate/runway model has no meaning. The relevant analogue is **project-funding runway**: HammerHAI to ~2028, Blue Lion operations to 2032, BAdW core budget indefinite.

### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| None | No layoffs found (TrueUp has no profile; no press coverage) | n/a | Attrition happens through fixed-term contract expiry: 2023 saw 76 joiners and 49 leavers out of ~298 staff (~16% outflow, including students and apprentices) |

**Verdict:** **PASS with CAUTION.** Institutionally among the most stable employers in Germany, but every currently offered role is project-funded and fixed-term.

---

## Section 9: Regulated Industry

LRZ is a public authority. The obligations are: public procurement law (VgV/EU tenders for systems, which explains the long hardware cycles), GDPR and the Bavarian data protection law (BayDSG) for university user data, the Bavarian public-sector IT security rules, and certified service management (postings mention "zertifizierte, transparente Prozesse" (certified, transparent processes); LRZ publicises ISO/IEC 20000-style certified IT service management; the exact certificate scope was not verified). HammerHAI adds data-privacy/AI-regulation awareness ("secure and compliant data management, including AI models as well as data privacy standards and legislation").

The practical impact is process documentation and change management, not formal safety cases or regulator approval of releases.

**Verdict:** **PASS** (low regulatory burden; public-sector process overhead applies).

---

## Section 10: On-Call

No current posting mentions Rufbereitschaft (on-call) or on-call. However, LRZ runs 24/7 national infrastructure (supercomputer, Munich Scientific Network, storage, email for 120k students). A 24/7 three-shift operator desk exists (Glassdoor student review), and in German public computing centres, operations teams for core services commonly have paid Rufbereitschaft rotations. The HammerHAI data platform and education roles are unlikely to carry on-call.

**Verdict:** **CAUTION (team-dependent) / UNVERIFIED.** Likely none for the HammerHAI roles, possible for infrastructure/operations teams. Confirm in interview.

---

## Section 11: Interview Process

| Metric | Value |
|---|---|
| Difficulty | UNKNOWN (1 Glassdoor interview report, July 2024; no difficulty value shown) |
| Positive experience | 100% (1 report) |
| Average duration | UNKNOWN |
| Rounds | ~2 to 3 (phone interview, one-to-one, and group/panel interview, each reported once) |

The process follows the German public-service pattern: a single PDF application (cover letter, CV, **certificates**) submitted by a fixed deadline (12.10.2026 for the current roles), shortlisting, then a panel interview. The panel typically includes the hiring manager, HR, and a staff council (Personalrat) and equality officer (Gleichstellungsbeauftragte) representative, with a possible technical presentation. The TV-L grade and step are set after the offer based on degree and recognised prior experience. The process is **experience- and fit-focused, not LeetCode**. Expect a slow timeline (several weeks between deadline and decision).

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | **BORDERLINE/FAIL.** An HPC/IT infrastructure operator and university IT provider. Software is a supporting activity |
| Not consulting | **PASS for core LRZ, CAUTION for HammerHAI** (external SME consultancy/training/enablement) |
| Profitable | **FAIL.** A public-law institute; profit is not applicable |
| Employee count | ~300 (no minimum in the criteria file) |
| English-speaking | **CONDITIONAL.** AI Factory roles are English-first with German preferred; ops/service roles need C-level German |
| Local entity + engineering contracts | **PASS.** Direct TV-L employment with BAdW (K.d.ö.R.); no Handelsregister entry, as expected |
| Location / work model | Boltzmannstraße 1, Garching (U6 Garching-Forschungszentrum); up to 60% mobile work |
| Glassdoor | **UNVERIFIABLE.** 4.4 on only 3 reviews |
| Kununu | 4.4 (14 employee reviews), 92% recommend; not a Top Company |
| Salary | **BELOW.** TV-L E13 cap, ~€67k to €73k at a realistic entry step, ceiling ~€85k; no equity or bonus |
| AI/ML content | GPU/Cerebras/Blue Lion infrastructure for researchers. Open roles are data-catalogue integration and AI training, not ML engineering |
| Computer-language/Tech-stack | Mixed: Python (user side), Rust/C++/Fortran (HPC), Java/Kotlin (piveau). Not Python-centric for the open engineering role |
| No on-call | UNVERIFIED. Likely none for HammerHAI, possible in ops teams |
| WLB / Stability | Excellent WLB; institution highly stable; **every open role fixed-term** (to 2028) |
| Regulated industry | PASS. Public procurement and data protection only |
| Review themes | Relaxed, collegial, no pressure; weaknesses are pay, career progression and fixed terms |
| Permanent contract | **FAIL.** All four open roles are befristet (fixed-term) |
| Senior Python SWE role open | **FAIL.** None |

---

## Section 13: Verdict

**Recommendation: Exclude.**

**Strengths:** LRZ offers a genuinely pleasant, low-pressure work environment with excellent work-life balance: flexitime, up to 60% mobile work, overtime compensated with time off, two-person offices, 30+2 days leave. It works with world-class hardware (SuperMUC-NG, the €250M Blue Lion system arriving in 2027, a Cerebras CS-2, quantum computers) in an international team of ~50 nationalities. The institution will outlast any private employer.

**Hard blockers:**
1. **Not a profitable company.** LRZ is a public-law institute of the Bavarian Academy of Sciences. The "mature, profitable company" criterion is structurally unmet.
2. **Fixed-term contracts only.** All three HammerHAI roles end at the end of Q1/2028, and the wiki sysadmin role at 31.12.2028. "Further employment is intended" is not a permanent contract. This fails the "full-time, permanent" criterion and the long-term-commitment goal.
3. **Compensation capped by the tariff.** "Up to E13 TV-L" means about €67k (Stufe 3) to €73k (Stufe 4) at a realistic entry point and €85k at the ceiling, which is reached only after years of step progression. There is no bonus or equity. That is roughly 20 to 30% below the Munich median for senior engineers at large profitable companies (~€85k to €100k). The only lever is a §16(5) TV-L recruiting allowance of up to 20%, which is discretionary and rare.
4. **No matching role.** No Senior/Staff Software Engineer role with Python at its core exists. The Data Platform Engineer role centres on the Java/Kotlin piveau catalogue, FAIR metadata workflows and partner relationships, with software engineering as a "basic knowledge" preferred skill. The AI Education role is training delivery, and Customer Success is sales.

**Secondary concerns:** HammerHAI's SME-facing enablement/consultancy element comes close to the excluded solutions-engineer pattern. Glassdoor (3 reviews) and Kununu (14 reviews) are too thin to confirm a strong reputation. Career progression is the weakest review theme on both platforms. Operations teams may carry 24/7 Rufbereitschaft. Infrastructure and university-service roles typically require C-level German.

**Recommendation:** Do not apply. The blockers are structural to the public sector (tariff pay, project-funded fixed terms, no profit motive) and would not change with a different posting. Only a combination of a **permanent (unbefristet)** Python platform-engineering post, a **higher starting step** under §16(5) TV-L, and an explicit statement that no on-call applies would justify a second look. Even then, the pay ceiling stays far below the market.

---

## Sources

- [LRZ Impressum](https://www.lrz.de/impressum/)
- [LRZ: Das LRZ / The LRZ (key facts, board)](https://www.lrz.de/en/the-lrz)
- [LRZ Karriere: Arbeiten am LRZ](https://www.lrz.de/karriere) (via CDP)
- [LRZ Aktuelle Stellenangebote](https://www.lrz.de/karriere/aktuelle-stellenangebote) (via CDP)
- [Personio: Data Platform Engineer, HammerHAI](https://lrz.jobs.personio.de/job/2805900?language=en) (via CDP)
- [Personio: AI Education Expert, HammerHAI](https://lrz.jobs.personio.de/job/2805857?language=en) (via CDP)
- [Personio: Customer Success Expert, HammerHAI](https://lrz.jobs.personio.de/job/2805891?language=en) (via CDP)
- [Personio: Systemadministratorin Enterprise Wiki](https://lrz.jobs.personio.de/job/2795292) (via CDP)
- [LRZ Download Centre (annual reports)](https://www.lrz.de/en/service-center/download-centre)
- [LRZ Jahresbericht 2023 (PDF)](https://www.lrz.de/fileadmin/Medien/Downloadbereich/Jahresberichte/LRZ-Jahresbericht-2023.pdf) (downloaded with curl, text extracted with pypdf)
- [LRZ: AI and Big Data](https://www.lrz.de/en/technologies/ai-and-big-data)
- [LRZ: HPE builds next-generation supercomputer (Blue Lion)](https://www.lrz.de/en/news/detail/2024-12-13-bluelion-en)
- [BAdW press release: HPE baut den nächsten Supercomputer am LRZ](https://badw.de/en/die-akademie/presse/pressemitteilungen/pm-einzelartikel/detail/hewlett-packard-enterprise-baut-den-naechsten-supercomputer-am-leibniz-rechenzentrum-der-bayerischen-akademie-der-wissenschaften.html)
- [HPE newsroom: Blue Lion](https://www.hpe.com/us/en/newsroom/press-release/2024/12/hewlett-packard-enterprise-builds-next-generation-100-direct-liquid-cooled-supercomputer-at-the-leibniz-supercomputing-center.html)
- [The Next Platform: LRZ adopts Nvidia engines for €250M Blue Lion](https://www.nextplatform.com/2024/12/16/lrz-adopts-nvidia-engines-for-e250-million-blue-lion-supercomputer-in-2027/)
- [HPCwire: HPE to build Blue Lion for LRZ](https://www.hpcwire.com/off-the-wire/hpe-to-build-blue-lion-supercomputer-for-lrz-supporting-german-hpc-infrastructure/)
- [HammerHAI: About](https://www.hammerhai.eu/about/)
- [HammerHAI: Hosting agreement signed at HLRS](https://www.hammerhai.eu/2025/03/12/hosting-agreement-signed-for-new-ai-optimized-supercomputer-at-hlrs/)
- [EuroHPC JU: AI Factories, Germany](https://www.eurohpc-ju.europa.eu/ai-factories/germany_en)
- [EuroHPC JU: Contract signed to deploy HammerHAI (2026-03-16)](https://www.eurohpc-ju.europa.eu/eurohpc-ju-signs-contract-deploy-ai-supercomputer-hammerhai-2026-03-16_en)
- [Gauß-Allianz: HammerHAI, AI Factory für Wissenschaft und Industrie](https://gauss-allianz.de/en/info_letter/123/article/HammerHAI:%20AI%20Factory%20f%C3%BCr%20Wissenschaft%20und%20Industrie)
- [HPCwire: GCS centers in EuroHPC AI Factory network](https://www.hpcwire.com/off-the-wire/gcs-centers-play-central-roles-in-eurohpc-ai-factory-network/)
- [Wikipedia (de): Leibniz-Rechenzentrum](https://de.wikipedia.org/wiki/Leibniz-Rechenzentrum)
- [Wikipedia (en): Leibniz Supercomputing Centre](https://en.wikipedia.org/wiki/Leibniz_Supercomputing_Centre)
- [Wikipedia (en): SuperMUC](https://en.wikipedia.org/wiki/SuperMUC)
- [Wikipedia (de): Bayerische Akademie der Wissenschaften](https://de.wikipedia.org/wiki/Bayerische_Akademie_der_Wissenschaften)
- [BAdW: Geschäftsordnung für das Leibniz-Rechenzentrum](https://badw.de/en/die-akademie/satzungen-und-statuten/geschaeftsordnung-fuer-das-leibniz-rechenzentrum-lrz.html)
- [BAdW: Satzung der BAdW](https://badw.de/en/die-akademie/satzungen-und-statuten/satzung-der-badw.html)
- [BayernPortal: BAdW Leibniz-Rechenzentrum](https://www.bayernportal.de/dokumente/behoerde/15776034376)
- [StMWK: Forschungseinrichtungen in Bayern](https://www.stmwk.bayern.de/wissenschaftler/forschung/einrichtungen.html)
- [Nominatim: Boltzmannstraße 1, 85748 Garching](https://nominatim.openstreetmap.org/search?q=Boltzmannstra%C3%9Fe+1,+85748+Garching&format=json&addressdetails=1)
- [Glassdoor: Leibniz Supercomputing Centre reviews](https://www.glassdoor.de/Bewertungen/Leibniz-Supercomputing-Centre-Bewertungen-E308233.htm) (via CDP)
- [Glassdoor: Overview](https://www.glassdoor.com/Overview/Working-at-Leibniz-Supercomputing-Centre-EI_IE308233.11,40.htm) (via CDP)
- [Glassdoor: Salaries](https://www.glassdoor.de/Gehalt/Leibniz-Supercomputing-Centre-Geh%C3%A4lter-E308233.htm) (via CDP)
- [Glassdoor: Interviews](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/Leibniz-Supercomputing-Centre-Fragen-im-Vorstellungsgespr%C3%A4ch-E308233.htm) (via CDP)
- [Kununu: Leibniz-Rechenzentrum der Bayerischen Akademie der Wissenschaften](https://www.kununu.com/de/leibniz-rechenzentrum-der-bayerischen-akademie-der-wissenschaften) (via CDP; curl returned 405)
- [Kununu: reviews](https://www.kununu.com/de/leibniz-rechenzentrum-der-bayerischen-akademie-der-wissenschaften/kommentare) (via CDP)
- [Kununu: Leibnitz Rechenzentrum München (duplicate profile)](https://www.kununu.com/de/leibnitz-rechenzentrum-muenchen) (via CDP)
- [Teamblind: Leibniz Supercomputing Centre](https://www.teamblind.com/company/Leibniz-Supercomputing-Centre) (404, no profile)
- [levels.fyi: Leibniz Supercomputing Centre](https://www.levels.fyi/companies/leibniz-supercomputing-centre/salaries) (404, no profile)
- [Great Place to Work Deutschland: Beste Arbeitgeber](https://greatplacetowork.de/beste-arbeitgeber-liste/)
- [LinkedIn Jobs search: Leibniz Supercomputing Centre](https://www.linkedin.com/jobs/search/?keywords=Leibniz%20Supercomputing%20Centre&location=Germany) (via CDP, no results)
- [LinkedIn: Leibniz Supercomputing Centre](https://www.linkedin.com/company/leibniz-supercomputing-centre)
- [GitHub: LRZ-BADW organisation](https://github.com/LRZ-BADW) (via GitHub API)
- [TV-L Entgelttabelle 2026 (oeffentlichen-dienst.de)](https://www.oeffentlichen-dienst.de/entgelttabelle/tv-l.html) (via CDP)
- [TV-L 2026-2028 agreement summary](https://oeffentlicher-dienst-news.de/tv-laender/)
- [TV-L E13: Gehalt, Stufen (akademische-jobs.de)](https://akademische-jobs.de/ratgeber/tv-l-e13/)

### Retrieval method notes

- **Chromium over CDP** (`.claude/tools/cdp.py`): LRZ careers pages, all Personio postings, Glassdoor (the logged-in glassdoor.de session; glassdoor.com returned a "page not found" interstitial), Kununu (curl got HTTP 405 on every slug), LinkedIn Jobs, and the TV-L table.
- **curl:** Kununu slug probes (405), levels.fyi and Teamblind (both 404), the LRZ 2023 annual report PDF, Nominatim, and the GitHub API.
- **Overpass API:** failed twice with a non-JSON response, so nearby stops were not listed from OSM (see Section 3).
