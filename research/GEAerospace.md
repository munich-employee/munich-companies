# GE Aerospace - Full Research Report

_Researched: 2026-10-05_

> **Key caveats (not hard disqualifiers)**
> 1. The Munich-area site (Garching, ~100 people) is an aero-thermal **engine R&D** centre (aerodynamics, combustion, acoustics, hybrid-electric). It does not hire software engineers in any visible volume; no Garching role of any kind is open today.
> 2. German pay data is thin but consistently **low** (Lead/Senior Engineer €57-79K on Glassdoor).

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | GE founded 1892; aircraft engine business since 1917 (GE Aviation). Standalone **GE Aerospace** since 2 April 2024 after the GE HealthCare and GE Vernova spin-offs (109 years of aero-engine history) |
| Employees | ~57,000 globally (FY2025 release; +7.5% YoY) |
| Revenue (FY2025) | $45.9B GAAP (+18%), adjusted $42.3B (+21%); orders $66.2B (+32%); backlog ~$190B |
| Profitability | GAAP profit $10.0B (21.8% margin), net income ~$8.7B, FCF $7.7B (+24%). Q2 2026: revenue $13.3B (+21%), FCF $3.0B (+43%), full-year guidance raised - **PASS** |
| Ownership | Public, NYSE: GE. CEO H. Lawrence (Larry) Culp Jr. |
| Software-centric | No. Jet engine and aero-components manufacturer; software is an enabling function (Digital Technology / IT, engine controls, MRO analytics) - **FAIL** (company) / **BORDERLINE** (for the specific remote digital role) |

### Key People
- **H. Lawrence Culp Jr.** - Chairman & CEO (GE CEO since 2018; architect of the three-way split and the FLIGHT DECK lean operating model).
- Garching site: GE Aerospace Advanced Technology (GE AAT), part of Engineering / Technology & Operations. Managing directors of the German entity (NorthData): Roman Seele, Patrick W. E. Sigmund and others.

### Software-Centric Assessment
GE Aerospace sells engines (LEAP, GE9X, GEnx, CFM56, military engines) and earns most of its profit from aftermarket services (shop visits, spare parts). Software work falls into three buckets:
1. **Safety-critical embedded software** (FADEC/engine controls, avionics in Grand Rapids): C/C++/Ada, DO-178C. Not a fit.
2. **Digital Technology (enterprise IT / data / AI)**: Python, Java, AWS, Databricks, LLM apps for supply chain, commercial engine services, MRO.
3. **Industrial software inside products** (Colibrium Additive machine software in Lichtenfels): .NET/Python/Node.js, imaging, German-speaking.

Bucket 2 is real and well funded (Databricks medallion architecture, MLflow, MCP servers, RAG), but it is a cost centre serving an industrial business, not the product.

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **GE Aviation Deutschland GmbH** (formerly General Electric Neunundzwanzigste Beteiligungs GmbH) | HRB 291056, Amtsgericht München (previously HRB 11072 Regensburg, HRB 43010 Offenbach); LEI OHGBTNUC0BP08T44K345 | Freisinger Landstr. 50, 85748 Garching b. München | "Engineering and technical research for aircraft engine components and digital services for the aviation sector, as well as sales and provision of digital products and services, including software, software as a service, professional services and hardware." |
| Colibrium Additive (formerly GE Additive / Concept Laser GmbH) | Lichtenfels entity (not individually verified on NorthData) | Rudolf-Diesel-Str. 14, 96215 Lichtenfels | Additive manufacturing machines; campus sized for up to 700 employees |

Shareholder chain (NorthData): General Electric Deutschland Holding GmbH; merger history with GE Business Services GmbH and General Electric Finance Holding GmbH.

**Verification:** The registered purpose explicitly includes engineering, technical research **and** software/SaaS/digital services, so it is not a sales shell. Garching job postings (e.g. Engineering Working Student Turbine Aerodynamics) are issued for this location, and the Garching careers page describes ~100 directly employed engineers. The home-based "Software Engineer (m/f/d)" posting does not name the employing entity; it is very likely GE Aviation Deutschland GmbH, but this is **UNVERIFIED** (ask the recruiter; make sure it is a direct German contract, not an EOR).

**Verdict: PASS** (entity for the remote role to be confirmed)

---

## Section 3: Office Location

- **Office address:** Freisinger Landstraße 50, 85748 Garching bei München (Hochschul- und Forschungszentrum, TUM Garching campus). Nominatim confirms the address on the research campus.
- **Nearest public transit (OSM Overpass):** bus stop *Garching, Lichtenbergstraße* 192 m; U6 *Garching-Forschungszentrum* ~700 m straight line (~10 min walk); bus stop *Anna-Boyksen-Straße* 840 m.
- **Work model:**
  - Garching: R&D lab site; the careers page describes an on-site team. No hybrid policy stated.
  - Lichtenfels (Colibrium): hybrid, up to 2 home-office days/week (job posting).
  - **Remote "Software Engineer (m/f/d)": "home-based, preferably located in Germany", occasional travel.** LinkedIn tags it "This is a remote position".
  - Globally, reviewers report RTO pressure (one 2026 review: in office four days a week).

---

## Section 4: Reviews

**GPTW:** No Great Place to Work Germany certification found for GE Aerospace or its German entities. GE Germany was a "Top Arbeitgeber für Ingenieure" in 2009/2010 (pre-split, not relevant today). Glassdoor shows "Best Place to Work / Best CEO" badges on the global profile.

### Glassdoor

Data via Chromium over CDP (glassdoor.de, logged-in session; embedded page data). Employer ID E8674.

| Metric | Global | Germany | Munich (München) | Software Engineers (global) |
|---|---|---|---|---|
| **Overall** | 4.1 (3,694 rated; 4,768 total) | 4.8 (12) | 5.0 (4) | 3.7 (71-76) |
| **WLB** | 3.7 | 4.8 | 4.5 | 4.6* |
| **Culture & Values** | 4.0 | 4.8 | 4.9 | 4.3* |
| **Comp & Benefits** | 3.9 | 4.6 | 3.5 | 3.3* |
| **Career Opportunities** | 3.9 | 4.6 | 3.3 | 3.3* |
| **Diversity & Inclusion** | 4.1 | 4.8 | 4.7 | 4.5* |
| **Senior Management** | 3.6 | 4.7 | 4.7 | 3.6* |
| **% Recommend** | 83% | 92% | 100% | 56% |
| **CEO Approval** | 91% | 92% | 100% | 60% |
| **Business Outlook** | 83% positive | 91% positive | 86% positive | 92% positive |

Garching b. München filter: **2.0 (2 reviews)**, 0% recommend, Comp 1.0, Career 1.0, Senior Management 1.0.

\* The SWE sub-scores come from the page's embedded data and may reflect the recent six-month window; the 3.7 / 56% / 60% headline figures are confirmed in the page text. The Germany, Munich and Garching filters all have far fewer than 20 reviews: **directional only**. The SWE filter (71-76 reviews, mostly US/UK/India) is reliable and notably weaker than the company average: 56% recommend vs 83%.

### Kununu

No dedicated GE Aerospace profile. Profiles found (Chromium over CDP; curl got HTTP 405):

| Profile | Score | Recommend | Reviews | Relevance |
|---|---|---|---|---|
| `general-electric-dach-ge` (GE Germany, all pre-split businesses) | **3.6** | 67% (59% last 2 yrs) | 414 (445 incl. applicants) | Low. Recent reviews are dominated by **GE Vernova** wind (Salzbergen) and GE Transport. None from Garching found |
| `concept-laser` (now Colibrium Additive, Lichtenfels) | 3.2 | 20% | 42 | Medium (GE Aerospace subsidiary in Bavaria) |
| `colibrium-additive-a-ge-company1` | 4.0 | 100% | 4 | Too few |
| `colibrium-additive-a-ge-aerospace-company1` | 3.1 | n/a | 2 | Too few |

- **Kununu Top Company:** NO (none of the profiles).

### Blind / Teamblind

No separate GE Aerospace page (slugs `GE-Aerospace`, `GE-Aviation` return 404). The combined **GE** page: **3.3 / 5 (400 reviews)**. Career Growth 3.0, **WLB 4.1**, Compensation 2.8, Culture 3.2, **Management 2.8**. Recent senior SWE reviews: "Great wlb, avg pay"; "Petty politics, frustrating stagnation... seniority counts for a lot" (March 2026).

Indeed (US, Software Engineer filter, via the Indeed connector): 3.7 overall, WLB 3.6, Management 3.2, Comp 3.9, CEO approval 63%, 59% would recommend (294 of 501).

### Review Themes (2024-2026)

**Positives:**
- Stability and job security ("my job feels secure", SWE, Sept 2026); strong financial momentum and confidence in the CEO (91% global approval).
- Benefits and people: "Corporate environment, benefits and people" (SWE, London, June 2026).
- WLB is generally good outside manufacturing: Blind WLB 4.1; "Great wlb" (senior SWE, Blind).
- Global projects and exposure: "opportunities to work on global projects" (SWE, April 2026).
- German reviewers (few) are very positive: Germany 4.8, Frankfurt field service "Work-life balance; customer relationship".

**Negatives:**
- **Bureaucracy and slow decisions** is the dominant SWE complaint: "extremely bureaucratic structure between levels of management" (SWE, Cheltenham, Sept 2026); "bureaucracy is very high... decision-making... very slow" (SWE, April 2026).
- **Politics / seniority-based advancement:** "To much politics, hard to get up the ladder unless you stay for years and years" (SWE, June 2026); "Petty politics", "Seniority counts for a lot" (Blind).
- **Below-market software pay:** Blind Compensation 2.8; SWE Comp 3.3 on Glassdoor; "avg pay".
- **Leadership not open to feedback / production pressure** (manufacturing reviews, 2026): "Leadership is not accepting of feedback... continue to ask for more production with no change in the process."
- **RTO:** reports of 4 office days/week at some sites.
- **Colibrium/Concept Laser (Bavaria):** "3rd restructuring (= headcount reduction) within 4 years" (Jan 2025); "American pay system"; loss of reputation and benefits since the GE takeover; 20% recommend.
- Overlap with hard red flags: **layoffs/restructuring** (Colibrium, historic 2020 cuts); no evidence of 24/7, surveillance or unpaid overtime in the software population.

### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | Not systemic. Blind Management 2.8 and Glassdoor Senior Management 3.6 point to weak middle management, but CEO approval is 91%. A 2026 review says the CEO "is doing the best he can to reverse decades of poor leadership". |
| 24/7 Work Expectation | Not found for software or engineering roles. |
| Internal Surveillance | Not found. One Kununu Concept Laser reviewer *asks* for more control of home-office staff (the opposite signal). |
| Fear-driven Management | Production pressure in manufacturing ("ask for more production with no change in the process"); not reported for digital teams. |
| Communication Breakdown | Bureaucracy and slow decisions across management layers (multiple SWE reviews 2026). Colibrium: "Isolated from the main decision making hub" (field service, Germany). |
| Unpaid Overtime | Not found for GE Aerospace. The Kununu GE DACH "excessive hours" complaints concern GE Vernova wind. |
| Silent Firings | Not found. Cuts at GE have historically been announced programmes (WARN notices, restructurings). |
| Work-Life Balance issues | Global WLB 3.7 is acceptable; Blind WLB 4.1; field-service roles travel heavily ("you were never home"). |

**Risk level: LOW-MODERATE.** The pattern is (b) large-company bureaucracy and politics, plus (c) localized pressure in manufacturing and in the Colibrium additive unit. It is not systemic toxicity.

---

## Section 5: Compensation

### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| Glassdoor (Germany) | Lead Engineer | €59-75K | - | - | €59-75K | 4 |
| Glassdoor (Germany) | Senior Engineer | €57-67K | - | - | €57-67K | 2 |
| Glassdoor (Germany) | Advanced Lead Engineer | €65-70K | - | - | €65-70K | 1 |
| Glassdoor (Germany) | Sr Staff Technical Product Manager | €128-137K | - | - | €128-137K | 1 |
| Glassdoor (Germany) | Senior Product Manager | €100-130K | - | - | €100-130K | 3 |
| Glassdoor (Garching) | Lead Engineer / Senior Engineer | €57-79K / €61-67K | - | - | - | 2 / 2 |
| Glassdoor (Garching, search snippet) | Software Engineer | ~€64K | - | - | ~€64K | n/a |
| levels.fyi (Germany) | Testing (SDET), Munich, 11 YOE, 2022 | €78K | 0 | 0 | €78K | 1 (others locked; "4 more submissions needed") |
| levels.fyi (US, reference) | Software Engineer, median | - | - | - | $130K (PB $103K, LPB $124K, EB $156K, max $200K) | 238 |
| GE posting (US, AI/ML SWE, Evendale) | AI Engineer | $112-150K | - | discretionary % | - | posting |

Munich percentiles (median / 75th / 90th) for GE Aerospace software roles: **not available**; Germany data covers aero/mechanical engineers, not software.

The remote Germany posting discloses no salary. GE's band naming (PB / LPB / SPB / EB = Professional, Lead Professional, Senior Professional, Executive Band) means a "Senior/Staff" level software role would be **LPB or SPB**; the LinkedIn "Entry level" tag on the remote role suggests it may be pitched at PB/LPB.

### Equity / Stock
Public (NYSE: GE). RSUs are granted mainly from SPB/executive bands upwards, typically as an annual long-term incentive with a 3-year vest at GE. For LPB-level engineers equity is usually small or absent; compensation is base + discretionary annual bonus (% of base). ESPP-style matching for German employees: **UNVERIFIED**. A strong share price run (FY2025 EPS +32%) makes any RSU grant valuable, but grant sizes for Germany are unknown.

### Verdict
The available German data (€57-79K for Lead/Senior *engineers*) sits well below the large, profitable Munich corporations (senior SWE typically ~€85-105K base at BMW, Siemens, Allianz, MunichRE, and above with AT contracts). Software-specific German data is essentially absent, and US data places GE in the lower-middle of US big-company tech pay.

**BELOW** (low-confidence; verify the band for the remote role before investing time)

---

## Section 6: AI/ML & Tech Stack Fit

### AI Strategy
- **AI Wingmate** (2024): company-wide GenAI assistant built with Microsoft on Azure OpenAI, ~52K employees, 500K+ interactions in the first months; a FLIGHT DECK lean-operations module is planned. Built in six weeks by internal Digital Technology.
- **Applied AI in operations:** automated inspection (blade inspection tools for narrow-body engine components), predictive maintenance, MRO shop-visit optimisation, supply-chain forecasting.
- **Commercial Engine Services BI team** (posting R5034608): production LLM apps, RAG/vector databases, **MCP servers** "that package domain-specific AI capabilities for reuse across the enterprise", forecasting/anomaly detection, MLflow/W&B MLOps on AWS + Databricks.
- **Robotic Services (Bristol, UK):** AI-driven inspection robotics software on AWS.
- Assessment: genuine **applied/enterprise AI**, not marketing, but focused on internal operations (supply chain, services BI, inspection) rather than an AI product.

### Tech Stack
Derived from job postings (remote Germany SWE, US AI/ML SWE R5034608, Lichtenfels R5040044, US Staff/Sr SWE postings via WeAreDevelopers/BuiltIn) and company press releases. No public engineering blog; the GE GitHub org is not representative of Aerospace.

| Category | Technologies |
|---|---|
| **Primary language(s)** | Python, Java (enterprise/data); JavaScript/TypeScript (Angular, React); C# / .NET (Colibrium machine software, some BI); C/C++/Ada (embedded controls, not relevant) |
| **AI/ML** | LLM apps, RAG, vector DBs, MCP servers, MLflow, Weights & Biases, SHAP/LIME, Azure OpenAI (AI Wingmate), FastAPI/Flask model serving |
| **Cloud** | AWS (primary for digital/data/AI workloads); Azure (Microsoft 365 / Azure OpenAI) |
| **Infrastructure** | Docker, Kubernetes, Git/GitHub, Gradle/Maven, CI/CD |
| **Data** | Databricks (medallion architecture), ETL/ELT pipelines, enterprise data architecture |
| **Other** | Compliance frameworks (NIST, GDPR, SOX), export control; imaging/frame grabbers in additive |

### Current Open Roles

Checked: GE Aerospace careers portal (Phenom, keyword searches for Garching, Munich, Germany, m/f/d, Software Engineer) and the LinkedIn guest job search (Germany, Munich). Verified 2026-10-05.

| Role | Division/Team | Level | Key Tech | Link |
|---|---|---|---|---|
| Software Engineer (m/f/d), **home-based, Germany** ✅ posted ~3 days ago | Digital Technology (supply chain / enterprise platforms) | LinkedIn: "Entry level" (unconfirmed) | Python, Java, Angular/React, AWS, data pipelines, Docker/K8s, AI/ML deployment, MCP | [LinkedIn 4474371873](https://www.linkedin.com/jobs/view/software-engineer-m-f-d-at-ge-aerospace-4474371873) |
| Senior Software Engineer Signal & Image Processing (m/f/d) ✅ posted 2026-09-22 | Colibrium Additive, **Lichtenfels** (hybrid, 2 HO days) | Mid-Career | .NET, Python, Node.js, camera/imaging; **fluent German required** | [R5040044](https://careers.geaerospace.com/global/en/job/R5040044/Senior-Software-Engineer-Signal-Image-Processing-m-f-d) |

**No open roles in Garching or Munich.** Lichtenfels is ~260 km from Munich and requires German, so it is out.

**Verdict:** Python/Java enterprise engineering on AWS + Databricks, with an applied-GenAI layer (LLM apps, RAG, MCP servers, MLflow) serving internal aerospace operations (supply chain, engine services, inspection). It is applied production engineering in an industrial IT organisation, not research and not product software. The remote Germany role is a reasonable stack fit (Python, AWS, AI integration), but it is a generalist full-stack + data role with a frontend component.

---

## Section 7: Language

- The remote Germany SWE posting is in English and lists no German requirement. English is the corporate language (US parent; reviews note GE trainings and tools are English-only).
- The Lichtenfels (Colibrium) posting requires **fluent German and English**.
- The Garching AAT team is international (TUM campus, global engineering programmes such as RISE/CFM).

**Verdict: CONDITIONAL.** PASS for the remote/Digital Technology role and Garching; FAIL for Colibrium Lichtenfels.

---

## Section 8: Stability

### Financial Position
- FY2025: revenue $45.9B (+18%), GAAP profit $10.0B, net income ~$8.7B, FCF $7.7B, orders $66.2B, backlog ~$190B.
- Q2 2026 (16 July 2026): revenue $13.3B (+21%), adjusted revenue $12.6B (+24%), FCF $3.0B (+43%), orders $16.5B; full-year adjusted EPS guidance raised to $7.65-7.85 (from $7.10-7.40).
- Trend: **strongly improving**, driven by aftermarket services (LEAP fleet ageing, shop visits). Investment-grade credit (A-range ratings). Adding ~$1B/year in US manufacturing capex.
- Financial runway model: not applicable (highly profitable public company).

### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| 2020 | GE Aviation COVID cuts | ~13,000 / up to 25% of Aviation workforce | Announced programme, global |
| Dec 2024 | Schenectady, NY shared services | 72 | Post-split transition roles (WARN notice) |
| 2021-2025 | Concept Laser / GE Additive / Colibrium, Lichtenfels | Not disclosed | Kununu (Jan 2025): "third restructuring (= headcount reduction) in 4 years" |
| 2025 | UAW strike at Evendale and Erlanger | ~600 hourly workers | Labour dispute, not layoffs |
| 2025-2026 | No Aerospace-wide layoffs found | - | Headcount +7.5% in 2025; expansion mode |

### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | **UNKNOWN** for GE Aviation Deutschland GmbH (Garching, ~100 staff, so it is legally eligible). **YES** at Colibrium/Concept Laser Lichtenfels | Kununu Concept Laser (July 2026): "Kompetentes Betriebsratsgremium". No Garching-specific evidence found in press, Kununu or LinkedIn searches |
| Collective agreement | **Likely NONE / UNKNOWN**. No "tarifgebunden" wording in any German posting; Colibrium reviewers describe an "American pay system" and call for a tariff ("Tarifvertrag annehmen!", Dec 2023) | Kununu Concept Laser; postings R5040044 and the remote SWE role |
| European works council | Likely YES at General Electric group level (EU-scale multinational); not verified for post-split GE Aerospace | - |
| Conflict signals | US: UAW strike 2025. Germany: none found for GE Aerospace | Press |

**Verdict: CAUTION.** Financially very stable and growing, but the German footprint is small (Garching ~100, Lichtenfels hundreds) with no confirmed tariff binding. Colibrium has shown repeated restructuring. A small R&D outpost of a US group is exposed to portfolio decisions in Evendale (the former GE Global Research Europe in the same building shrank from ~250 researchers to the current ~100-person AAT team after GE's breakup).

---

## Section 9: Regulated Industry

- Aviation: **FAA / EASA** certification, **DO-178C** (airborne software), **AS9100** quality, plus **export control (ITAR/EAR)** on engine technical data. Postings demand compliance with "quality, safety, cybersecurity, export control" and frameworks such as NIST, GDPR, SOX.
- Practical impact by role:
  - Embedded/controls: heavy (formal verification, certification artefacts). Not relevant.
  - Enterprise Digital Technology (remote role): moderate. Export-controlled data handling, SOX controls, security reviews, enhanced hiring screening ("enhanced security screening measures to detect and prevent against fraudulent hires"). Not safety-case work.
  - Defence programmes: security clearance (US-only roles).

**Verdict: CAUTION** (moderate compliance overhead for enterprise roles; heavy for anything touching engine data or controls)

---

## Section 10: On-Call

- The remote Germany SWE posting mentions "Troubleshoot production issues... implement durable fixes" and "operational resilience", but no on-call rota.
- The AI/ML SWE posting covers monitoring and alerting for model degradation; no on-call mentioned.
- Internal enterprise platforms (supply chain, BI) in a lean operating model typically run business-hours support; MRO/shop systems running 24/7 can have rota coverage.

**Verdict: UNVERIFIED / CAUTION (team-dependent).** Ask explicitly.

---

## Section 11: Interview Process

Glassdoor, via Chromium over CDP.

| Metric | Value |
|---|---|
| Difficulty | **2.9 / 5** (984 ratings; global) |
| Positive experience | **74%** (global, 1,014 interviews); 76% for Software Engineer (25 interviews) |
| Average duration | **~29 days** (hiring process average); many reviews report 2 weeks to 1 month |
| Rounds | 3-4 typical |

**Typical process:** recruiter screen (sometimes HireVue) → hiring-manager technical/behavioural (STAR format) → panel of 2-4 interviews over Teams (technical + behavioural), sometimes an in-person final. Software Engineer reports vary widely: many are resume-driven with OOP fundamentals ("polymorphism, inheritance, encapsulation") and aerospace development standards; one 2026 report describes a big-tech-style loop (DSA phone screen, two LeetCode medium/hard sessions, system design, HM behavioural). India: online assessment with two medium coding questions.

**Character:** mostly experience/behavioural-focused with moderate coding. Prepare for LeetCode-medium coding and a system-design round for senior roles. Expect relocation and salary-expectation questions in the first call.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | **FAIL** at company level (engine manufacturer); BORDERLINE for Digital Technology roles |
| Not consulting | **PASS**: internal product/IT work, no client billing |
| Profitable | **PASS**: $10.0B GAAP profit FY2025, guidance raised 2026 |
| Employee count | **PASS**: ~57,000 globally; ~100 in Garching |
| English-speaking | **CONDITIONAL**: remote/Digital roles English; Colibrium requires German |
| Local entity + engineering contracts | **PASS**: GE Aviation Deutschland GmbH, HRB 291056, purpose includes engineering + software (employer of the remote role unconfirmed) |
| Location / work model | Garching; remote role home-based in Germany |
| Glassdoor | Global 4.1 / WLB 3.7 (**PASS**); SWE 3.7 / 56% recommend (**BORDERLINE**); DE/Munich too few reviews |
| Kununu | No GE Aerospace profile; GE DACH 3.6 (Vernova-dominated); Concept Laser 3.2 / 20% (**BORDERLINE / weak**) |
| Salary | **BELOW**: German engineer data €57-79K; no SWE band visible |
| AI/ML content | Applied enterprise GenAI (LLM apps, RAG, MCP, MLflow) on AWS/Databricks: **good** in the right team |
| Computer-language/Tech-stack | Python + Java + Angular/React on AWS: **PARTIAL PASS** (Python central but shared with Java/frontend) |
| No on-call | **UNVERIFIED** |
| WLB / Stability | Financially excellent; WLB reasonable (Blind 4.1); small German footprint |
| Works council / collective agreement | **UNKNOWN** for Garching; Betriebsrat at Lichtenfels; no tariff evidence: **CAUTION** |
| Regulated industry | **CAUTION**: aviation + export control + SOX |
| Review themes | Bureaucracy, politics, seniority-driven promotion, below-market software pay; strong stability and benefits |
| Munich engineering roles | **None open**; Garching is an aero-thermal R&D site, not a software hub |
| Role level risk | Remote role tagged "Entry level"; may be below Staff/Senior |

---

## Section 13: Verdict

**Monitor; apply selectively only to the home-based Germany Software Engineer role, and only if the band is LPB/SPB with a competitive salary.**

**Strengths:** GE Aerospace is one of the most financially secure industrial companies in the world right now: revenue and free cash flow up 20%+, a ~$190B backlog, guidance raised, headcount growing, and a respected CEO (91% approval). Its Digital Technology organisation runs a modern applied-AI stack (Python, AWS, Databricks, LLM/RAG, MCP servers, MLflow) on meaningful operational problems. The German entity is real, has an engineering-and-software corporate purpose, and the one relevant opening is fully home-based in Germany in English.

**Hard blockers:**
1. **No software engineering presence in Munich.** The Garching site (~100 staff) does aero-thermal engine R&D: aerodynamics, combustion, acoustics, hybrid-electric. No Garching or Munich role of any kind is open, and no software role has been visible there historically.
2. **Compensation appears below the Munich large-corporate bracket.** German Glassdoor data for Lead/Senior Engineers is €57-79K, against the €85-105K+ senior SWE base at comparable large Munich employers. Equity is limited below senior bands. Low confidence, because there are no German software data points.

**Secondary concerns:**
- The only fitting role is a **generalist full-stack + data engineer** (Angular/React plus Python/Java plus pipelines) tagged "Entry level" on LinkedIn.
- Software is a cost centre in a lean manufacturing culture: SWE reviewers consistently cite bureaucracy, politics and seniority-driven promotion (SWE 56% recommend vs 83% company-wide; Blind Management 2.8).
- No confirmed works council or collective agreement for the Garching entity. The German footprint is small and exposed to US portfolio decisions (Colibrium: three restructurings in four years).
- Regulatory and compliance overhead: export control, SOX, enhanced background screening.
- On-call is unverified.

**Recommendation:** Do not target GE Aerospace as a Munich employer. Treat the home-based Germany "Software Engineer (m/f/d)" as an opportunistic application, and before investing in interviews confirm with the recruiter:
- the band (LPB minimum, ideally SPB) and the salary range;
- that the employer is GE Aviation Deutschland GmbH on a permanent, direct German contract (not EOR);
- the team (Supply Chain Digital vs Commercial Engine Services AI) and the Python-vs-Java/frontend split;
- the on-call expectations and the travel frequency.

If a Staff/Senior AI/ML role in Digital Technology opens with remote-Germany eligibility, it would be a stronger fit than the current posting.

---

## Section 14: Sources

- [GE Aerospace Q4 2025 results](https://www.geaerospace.com/news/press-releases/ge-aerospace-announces-fourth-quarter-2025-results)
- [GE Aerospace Q2 2026 results](https://geaerospace.com/news/press-releases/ge-aerospace-announces-second-quarter-2026-results)
- [GE Q2 2026 earnings release (SEC 8-K)](https://www.sec.gov/Archives/edgar/data/0000040545/000004054526000047/ge2q2026earningsrelease.htm)
- [GE Q4 2025 earnings release (SEC 8-K)](https://www.sec.gov/Archives/edgar/data/40545/000004054526000005/ge4q2025earningsrelease.htm)
- [Quartz: GE Aerospace Q2 2026 raised guidance](https://qz.com/ge-aerospace-q2-2026-earnings-raised-guidance-071626)
- [Nasdaq: GE Aerospace Q2 earnings call highlights](https://www.nasdaq.com/articles/ge-aerospace-q2-earnings-call-highlights)
- [MacroTrends: GE Aerospace revenue](https://secure.macrotrends.net/stocks/charts/GE/ge-aerospace/revenue)
- [MacroTrends: GE Aerospace net income](https://www.macrotrends.net/stocks/charts/GE/ge-aerospace/net-income)
- [NorthData: GE Aviation Deutschland GmbH, HRB 291056](https://www.northdata.com/GE%20Aviation%20Deutschland%20GmbH,%20Garching%20b%C2%B7%20M%C3%BCnchen/Amtsgericht%20M%C3%BCnchen%20HRB%20291056) (Chromium/CDP)
- [Bloomberg LEI: GE Aviation Deutschland GmbH](https://lei.bloomberg.com/leis/view/OHGBTNUC0BP08T44K345)
- [Eulerpool: GE Aviation Deutschland GmbH (Regensburg, lapsed)](https://eulerpool.com/en/company/DE/GE%20AVIATION%20DEUTSCHLAND%20GMBH,REGENSBURG,HRB%2011072)
- [GE Aerospace careers: Garching site](https://careers.geaerospace.com/global/en/garching)
- [GE Aerospace careers: R5040044 Senior Software Engineer Signal & Image Processing, Lichtenfels](https://careers.geaerospace.com/global/en/job/R5040044/Senior-Software-Engineer-Signal-Image-Processing-m-f-d) (Chromium/CDP)
- [GE Aerospace careers: R5034608 Software Engineer AI/ML, Evendale](https://careers.geaerospace.com/global/en/job/R5034608/Software-Engineer-AI-ML) (Chromium/CDP)
- [GE Aerospace careers search (Phenom)](https://careers.geaerospace.com/global/en/search-results) (Chromium/CDP)
- [LinkedIn: Software Engineer (m/f/d), GE Aerospace, remote Germany](https://www.linkedin.com/jobs/view/software-engineer-m-f-d-at-ge-aerospace-4474371873) (curl, guest API)
- [LinkedIn: Senior Software Engineer Signal & Image Processing](https://www.linkedin.com/jobs/view/senior-software-engineer-signal-image-processing-m-f-d-at-ge-aerospace-4470426396) (curl)
- [BuiltIn: Software Engineer (m/f/d) GE Aerospace](https://www.builtincolorado.com/job/software-engineer-m-f-d/11459129)
- [BuiltIn Bristol: GE Aerospace Software Engineer (Robotic Services)](https://builtinbristol.uk/job/software-engineer/8974644)
- [WeAreDevelopers: GE Aerospace Staff Software Engineer](https://www.wearedevelopers.com/jobs/ext/7192669/staff-software-engineer)
- [Glassdoor: GE Aerospace reviews (global)](https://www.glassdoor.de/Bewertungen/GE-Aerospace-Bewertungen-E8674.htm) (Chromium/CDP)
- [Glassdoor: GE Aerospace reviews Germany](https://www.glassdoor.de/Bewertungen/GE-Aerospace-Deutschland-Bewertungen-EI_IE8674.0,12_IL.13,24_IN96.htm) (Chromium/CDP)
- [Glassdoor: GE Aerospace reviews Munich](https://www.glassdoor.de/Bewertungen/GE-Aerospace-M%C3%BCnchen-Bewertungen-EI_IE8674.0,12_IL.13,20_IC4990924.htm) (Chromium/CDP)
- [Glassdoor: GE Aerospace reviews Garching](https://www.glassdoor.de/Bewertungen/GE-Aerospace-Garching-b-M%C3%BCnchen-Bewertungen-EI_IE8674.0,12_IL.13,31_IC4991443.htm) (Chromium/CDP)
- [Glassdoor: GE Aerospace Software Engineer reviews](https://www.glassdoor.sg/Reviews/GE-Aerospace-Software-Engineer-Reviews-EI_IE8674.0,12_KO13,30.htm) (Chromium/CDP)
- [Glassdoor: GE Aerospace salaries Germany](https://www.glassdoor.com/Salary/GE-Aerospace-Germany-Salaries-EI_IE8674.0,12_IL.13,20_IN96.htm) (Chromium/CDP)
- [Glassdoor: GE Aerospace salaries Garching](https://www.glassdoor.com/Salary/GE-Aerospace-Garching-b-M%C3%BCnchen-Salaries-EI_IE8674.0,12_IL.13,31_IC4991443.htm) (Chromium/CDP)
- [Glassdoor: GE Aerospace interviews](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/GE-Aerospace-Fragen-im-Vorstellungsgespr%C3%A4ch-E8674.htm) (Chromium/CDP)
- [Glassdoor: GE Aerospace Software Engineer interviews](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/GE-Aerospace-Software-Engineer-Fragen-im-Vorstellungsgespr%C3%A4ch-EI_IE8674.0,12_KO13,30.htm) (Chromium/CDP)
- [Kununu: GE Germany (DACH)](https://www.kununu.com/de/general-electric-dach-ge) (Chromium/CDP)
- [Kununu: Concept Laser](https://www.kununu.com/de/concept-laser) (Chromium/CDP)
- [Kununu: Colibrium Additive (a GE company)](https://www.kununu.com/de/colibrium-additive-a-ge-company1) (Chromium/CDP)
- [Kununu: Colibrium Additive (a GE Aerospace company)](https://www.kununu.com/de/colibrium-additive-a-ge-aerospace-company1) (Chromium/CDP)
- [Blind: GE company reviews](https://www.teamblind.com/company/GE/reviews) (Chromium/CDP)
- [Indeed: GE Aerospace company page](https://www.indeed.com/cmp/GE-Aerospace-1) (Indeed connector)
- [levels.fyi: GE Aerospace Software Engineer (US)](https://www.levels.fyi/companies/ge-aerospace/salaries/software-engineer)
- [levels.fyi: GE Aerospace Software Engineer Germany](https://www.levels.fyi/companies/ge-aerospace/salaries/software-engineer/locations/germany) (Chromium/CDP)
- [GE Aerospace: company-wide generative AI platform (AI Wingmate)](https://www.geaerospace.com/news/press-releases/ge-aerospace-launches-company-wide-generative-ai-platform-employees)
- [GE Aerospace: AI Wingmate built in six weeks](https://geaerospace.com/news/articles/ge-aerospace-created-ai-wingmate-six-weeks-can-you-say-next-level)
- [Turbomachinery Mag: GE Aerospace and Microsoft AI Wingmate](https://www.turbomachinerymag.com/view/ge-aerospace-microsoft-deliver-ai-wingmate-to-employee-workforce)
- [GE: GE schafft mehr als 30 neue Arbeitsplätze in Garching](https://www.ge.com/news/press-releases/ge-schafft-mehr-als-30-neue-arbeitspl%C3%A4tze-garching)
- [GE: GE opens first European research center in Germany](https://www.ge.com/news/press-releases/general-electric-ge-open-its-first-european-research-center-germany-ge-ceo-immelt)
- [BDLI: GE Aviation Advanced Technology](https://www.bdli.de/en/mitglied/ge-aviation-advanced-technology)
- [GE Aerospace: GE Additive rebrands as Colibrium Additive](https://www.geaerospace.com/news/press-releases/ge-additive-rebrands-colibrium-additive)
- [Metal AM: GE Aerospace annual report on Colibrium Additive](https://www.metal-am.com/ge-aerospace-annual-report-highlights-slow-adoption-of-am-and-critical-importance-of-colibrium-additive/)
- [AviTrader: 13,000 jobs to go at GE Aviation (2020)](https://avitrader.com/2020/05/05/%EF%BB%BF13000-jobs-to-go-as-ge-aviation-cuts-workforce-by-up-to-25/)
- [Daily Gazette: GE Aerospace Schenectady cuts](https://www.dailygazette.com/news/ge-aerospace-schenectady/article_22c30538-84da-11ef-8e64-a317a9e23816.html)
- [WARN Tracker: GE Aerospace Schenectady, Dec 2024](https://www.warntracker.com/layoff/general-electric-2024-12-31)
- [Yahoo News: UAW strike at GE Aerospace facilities](https://www.yahoo.com/news/articles/uaw-members-ges-evendale-facility-035914080.html)
- [OpenStreetMap Nominatim](https://nominatim.openstreetmap.org/) and [Overpass API (kumi.systems mirror)](https://overpass.kumi.systems/api/interpreter) (curl)
