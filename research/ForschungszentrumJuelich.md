# Forschungszentrum Jülich - Full Research Report

_Researched: 2026-11-04_

> **Critical Disqualifiers / Key Caveats**
> 1. **Compensation is capped by TVöD-Bund E13.** Every software posting found (Garching, Jülich, Aachen) is graded "Pay group 13 TVöD-Bund". A realistic external entry at Stufe 3-4 is **~€72.8k-€78.8k gross per year** including the 75% year-end bonus, with an absolute E13 ceiling of ~€89.6k after ~15 years. There is no equity and no performance bonus. This is roughly 15-25% below the Munich median for senior engineers at large profitable corporations.
> 2. **Only a small Munich presence.** The headquarters and almost all of the ~7,700 staff are in Jülich (NRW). The Munich-area site is the Jülich Centre for Neutron Science (JCNS) outstation at the Heinz Maier-Leibnitz Zentrum (MLZ), Lichtenbergstraße 1, Garching. Software work there is a small Scientific Computing Group plus a cloud-infrastructure group.
> 3. **Fixed-term contracts are the norm for engineering posts.** The current Garching software posting is "limited to 2 years" and project-funded (DFG / NFDI). Permanent posts exist but are rare.
>
> None of these is an absolute exclusion under the selection criteria (the criteria file sets no salary floor or employer-size minimum), but together they define the trade-off. The full report follows.

**Note on scope:** Forschungszentrum Jülich GmbH (FZJ) is one of the 18 legally independent Helmholtz Association research centres. This report covers the FZJ GmbH as employer, with a focus on what applies at its Garching (Munich) outstation, JCNS at MLZ. MLZ is a cooperation between TUM, FZJ and Helmholtz-Zentrum Hereon. Staff of the FZJ groups at MLZ are on the FZJ payroll.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 1956 (as a registered association by the State of North Rhine-Westphalia; 70 years). GmbH since 1967/1974; current name since 1990 |
| Employees | **7,700** (official headcount on 31.12.2025): 4,697 scientific and technical staff (3,020 scientists including 921 doctoral researchers; 1,677 technical), 1,663 in project management (Projektträger Jülich), 1,041 administration, 299 trainees/interns |
| Revenue (FY2025) | No commercial revenue. **Total budget €977M (2025)**: €498M institutional funding (51%) + €479M third-party funds (49%), made up of €184M project-management services, €167M national project funding, €95M R&D/infrastructure contracts, €33M EU funding |
| Profitability | **N/A (non-profit research GmbH).** More than 90% of the budget is public money. No profit objective. Funding stability is high (statutory federal/state allocation under Helmholtz programme-oriented funding, PoF IV) - **PASS on stability, profitability not applicable** |
| Ownership | Public. Federal Republic of Germany 90% / State of North Rhine-Westphalia 10% |
| Software-centric | Research centre; software is instrumental, though FZJ hosts one of Europe's largest HPC centres (JSC, JUPITER exascale system) - **BORDERLINE** (see assessment) |

### Key People

- **Prof. Dr. Astrid Lambrecht** - Chair of the Board of Directors (Glassdoor CEO approval 77%)
- **Dr. Stephanie Bauer** - Vice-Chair (administration/finance)
- **Prof. Dr. Ir. Pieter Jansens** - Board member
- **Prof. Dr. Laurens (Kobus) Kuipers** - Board member
- **Dr. Joachim Wuttke** - Head of the JCNS Scientific Computing Group at MLZ Garching

### Funding History

Not applicable: no venture or private-equity funding. Funding is the Helmholtz 90:10 federal/state allocation plus competitive third-party funds (DFG, EU, BMBF/BMFTR, industry contracts) and project-management fees. JUPITER (Europe's first exascale supercomputer, inaugurated 2025) is half-funded by EuroHPC JU and half by the federal government and NRW.

### Business Model

No commercial business model. FZJ conducts basic and applied research in information (HPC, quantum and neuromorphic computing, neuroscience), energy and climate, and bioeconomy. Outputs are publications, research infrastructure (supercomputers, neutron instruments, electron microscopes) offered to external users, technology transfer and spin-offs, and project-management services on behalf of federal and state ministries.

### Software-Centric Assessment

**BORDERLINE.** FZJ is a research organisation; the bulk of staff are scientists, technicians and administrators, and Glassdoor's reviewer population is dominated by PhD students, postdocs and "Wissenschaftlicher Mitarbeiter". Software is a means to research ends.

That said, software engineering is more substantial here than at most research centres:
- The **Jülich Supercomputing Centre (JSC)** runs JUWELS, JURECA and JUPITER and employs research software engineers, DevOps and HPC staff. Its GitHub organisation `FZJ-JSC` has 100+ repositories (Python is the leading language, then Jupyter, Shell, C++), with commits on the day of research (e.g. `jupyter-jsc-jupyterhub`).
- FZJ advertises **Research Software Engineering** as a named career area on its careers site.
- Institutes such as ICE/IEK-3 publish widely used open-source Python tools (`tsam` 182 stars, `FINE` 102 stars, `HiSim`, `RESKit`).
- At **Garching**, the JCNS Scientific Computing Group is explicitly "a team of research software engineers" building open-source neutron-scattering analysis software (BornAgain, Steca, MIEZEPY, libcerf, lmfit, and others), and JCNS also has a **cloud infrastructure group** running an on-prem Red Hat OpenShift platform for the MLZ data catalogue (SciCat).

Of the ~30 vacancies on the English job board at the time of research, three were software/systems engineering roles (one in Garching). The engineering population in Munich specifically is small.

### Consulting-Adjacency Assessment

The research software roles are **not consulting**: engineers build and operate internal platforms and open-source research software; there are no billable hours or consultant career titles. One posting at JSC is titled **"AI-Consultant im Forschungstransfer"** (AI Transfer Lab / WestAI, Jülich), working with companies on prototypes, but it states explicitly that "klassische Beratungs- oder Vertriebsziele" are not the focus. That role type should be avoided if the no-consulting criterion is strict; the Garching roles are not of this type. **PASS.**

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **Forschungszentrum Jülich GmbH** | Amtsgericht Düren **HRB 3498** (EUID DER3103.HRB3498; LEI 5299001HW55ZYGASLE52; VAT ID DE 122624631) | Wilhelm-Johnen-Straße, 52428 Jülich | "Aufgabe der Gesellschaft ist es, naturwissenschaftlich-technische Forschung und Entwicklung an der Schnittstelle von Mensch, Umwelt und Technologien zu betreiben, weitere nationale und internationale Aufgaben auf dem Gebiet der Grundlagen- und anwendungsnahen Forschung, insbesondere der Vorsorgeforschung, zu übernehmen oder sich hieran zu beteiligen, mit der Wissenschaft und Wirtschaft in diesen Forschungsbereichen zusammenzuarbeiten sowie das Wissen der Gesellschaft im Rahmen von Technologietransfers weiterzugeben. 2. Die Gesellschaft verfolgt als Mitglied der Hermann von [Helmholtz-Gemeinschaft] ..." |

Registry data from NorthData (fetched via Chromium over CDP); entity name, register number, VAT ID and Board confirmed against the FZJ legal notice. NorthData also lists FZJ as "Innovation Champion DE Forschung, Platz 3". The Garching outstation is not a separate legal entity: it is a branch of the same GmbH, and the Garching posting names "Place of Employment: Garching (München)" with the employer Forschungszentrum Jülich GmbH.

**Verification:** The registered purpose is scientific and technical research and development, which covers engineering work directly; it is not a sales shell. Employment is direct with the GmbH under the TVöD-Bund collective agreement, with VBL occupational pension. No PEO/EOR involvement.

**Verdict:** **PASS**

---

## Section 3: Office Location

- **Office address (Munich area):** JCNS outstation at the Heinz Maier-Leibnitz Zentrum (MLZ), **Lichtenbergstraße 1, 85748 Garching bei München**, in the "Hochschul- und Forschungszentrum" quarter of Garching (Landkreis München), on the TUM Garching research campus next to the FRM II research neutron source. Address confirmed from the MLZ Scientific Computing page and the computing.mlz-garching.de context page; Nominatim geocodes it to 48.26664, 11.67300. The headquarters (Wilhelm-Johnen-Straße, 52428 Jülich, NRW) is ~600 km away.
- **Nearest public transport:** **U-Bahn U6 station "Garching-Forschungszentrum"**, ~250 m straight-line from the geocoded address (OSM Overpass; roughly a 5-minute walk, depending on which gate of the site is used). Bus stop **"Garching, Lichtenbergstraße"** ~560 m away, served by lines 230, 292, 690 and X660.
- **Work model:** Hybrid. The FZJ benefits page states remote/home working is offered "aligned with operational requirements and your role", with flexitime and **no fixed core hours**, and overtime recorded and taken as time off. The Garching posting says: "The option of flexible working (in terms of location) is generally available after consultation and in line with upcoming tasks and (on-site) appointments." No fixed number of home-office days is published; this is agreed per team. Software reviewers on Glassdoor list "Flexible Zeiten und Home Office" and "Gleitzeit HomeOffice" as pros. Fully remote is not offered as a standard model.

---

## Section 4: Reviews

**Great Place to Work:** **No GPTW certification found** for FZJ (web search across GPTW and general sources). However, FZJ holds two signals of equivalent weight:
- **Kununu Top Company 2027** badge (plus a Kununu "Top Rated" seal for family-friendliness), shown on the Kununu profile.
- Ranked **6th in Glassdoor's "Best Places to Work Germany" 2023** (cited by FZJ's own careers material and third-party coverage).

### Glassdoor

Reached via glassdoor.de over Chromium/CDP (employer ID E637518). The Germany filter used the location-path URL; the Munich city filter returned "Noch keine Bewertungen" (no reviews). Job-title filters via `filter.jobTitleFTS`.

| Metric | Global | Germany | Munich | Software Engineers* |
|---|---|---|---|---|
| **Overall** | 4.0 (195 reviews) | 4.0 (107 reviews) | **no reviews** | 4.3 (4 reviews) |
| **WLB** | 4.5 | 4.6 | n/a | 4.8 |
| **Culture & Values** | 4.3 | 4.5 | n/a | 4.8 |
| **Comp & Benefits** | 3.9 | 4.1 | n/a | 3.2 |
| **Career Opportunities** | 3.9 | 4.1 | n/a | 3.9 |
| **Diversity & Inclusion** | 4.5 | 4.6 | n/a | 5.0 |
| **Senior Management** | 3.9 | 4.1 | n/a | 3.9 |
| **% Recommend** | 80% | 79% | n/a | 100% |
| **CEO Approval** | 77% | 77% | n/a | 100% |
| **Business Outlook** | 67% positive | 67% positive | n/a | 34% positive |

\* "Softwareentwickler" filter, 4 reviews (2023-2026); the "Software Engineer" filter gave 1 review (4.1). **Directional only**, well below 20 reviews. Glassdoor notes the overall rating rose 4% in the last 12 months.

Observations:
- **4.0 overall and 4.5 WLB** on 195 reviews is strong for a research employer, and well above Helmholtz Munich (3.6 / WLB 3.2).
- **Comp & Benefits** is the weakest category among software reviewers (3.2), consistent with the tariff grid.
- The reviewer base is mainly PhD students and postdocs at the Jülich campus; there are **no Munich/Garching reviews**, so the Garching experience is not directly evidenced.

### Kununu

Fetched via Chromium over CDP (curl returned HTTP 405 for all slugs). Slug: `forschungszentrum-juelich`.

- **Overall score:** **4.0 / 5.0** (higher than the research/development sector average of 3.6)
- **Recommendation rate (Weiterempfehlung):** **83%** (last 2 years)
- **Total reviews:** 386 in total; 332 employee reviews since 2011; 235 salary entries; 177 company-culture entries
- **Kununu Top Company:** **YES (Top Company 2027)**
- Sub-scores: Karriere & Gehalt 3.9, Unternehmenskultur 4.0, Arbeitsumgebung 4.1, Vielfalt 4.3
- **Best factor:** Umgang mit älteren Kollegen 4.4 (41 reviews). **Worst factor:** Kommunikation 3.5 (68 reviews)
- Most-confirmed benefits: flexible working hours 82%, company doctor 80%, canteen 77%
- Salary satisfaction: 56% satisfied (317 ratings). Average full-time gross for "Wissenschaftliche:r Mitarbeiter:in" €64,300 (56 entries)

### Blind / Teamblind

**No company page.** teamblind.com/company slugs (`Forschungszentrum-Jülich`, `Forschungszentrum-Julich`) return 404, and Blind search (via Chromium) returns "No results found for 'Forschungszentrum Jülich'". Expected for a German public research employer.

### Review Themes (2023-2026)

**Positives:**
- **Work-life balance and flexibility:** flexitime without core hours, home office, recorded overtime. "Flexible Zeiten und Home Office" (Software engineer, 2026); "Gleitzeit HomeOffice interessante Themen tolle Umgebung nette Kollegen und gute Teamarbeit" (Softwareentwickler, 2025); "geregelte Arbeitszeiten, faires Zeitmanagementsystem" (2026). Glassdoor WLB 4.5, Kununu flexible-hours benefit confirmed by 82%.
- **Research infrastructure and interesting work:** "hochkarätige Forschungsprojekte ... Zugang zu moderner Hardware/Software ... offenes Umfeld ... familienorientiert" (Softwareentwickler, 2023).
- **Reliable, transparent pay and security:** "die immer zuverlässig passierende Zahlung vom Lohn" (Kununu, 2026); "garantierte Gehaltserhöhung (durch Tarifaufstieg)" (Glassdoor, 2026).
- **Collegial, international environment:** people from 110+ countries; "supportive and collaborative working environment" (Glassdoor, 2025).
- **Works council seen as supportive by some:** "Den Betriebsrat finde ich toll! Er stand zu 100% auf meiner Seite" (Kununu, July 2026).

**Negatives:**
- **Bureaucracy and slow administration** (the dominant theme on both platforms): "Wir sind die Definition von Bürokratie" (Kununu, Sept 2026); "sehr langsame Prozesse. Ich warte schon fast zwei Jahre auf mein Arbeitszeugnis" (Glassdoor, June 2026); "Viel Bürokratie und Verwaltungsaufwand" (Glassdoor, Nov 2026).
- **Fixed-term contracts and limited careers:** "viele befristete Stellen", "Unsicherheiten durch Zeitverträge" (Softwareentwickler, 2023), "wenig Karrierechancen" (Softwareentwickler, 2025).
- **Tariff-capped pay:** "Tarif gebunden" listed as a con by a software engineer (2026); Comp & Benefits 3.2 among software reviewers.
- **Communication** is the lowest-rated Kununu factor (3.5): "Die Kommunikation innerhalb des Unternehmens ist eine Katastrophe".
- **Siloed institutes:** "Es findet keine Zusammenarbeit zwischen den Instituten statt ... Die Institute konkurrieren förmlich miteinander" (Kununu, 2026).
- **HR errors and exit handling:** an April 2026 review describes a sick note not being registered and minus hours being booked; a March 2026 review says "dass Austritte nicht immer im beiderseitig guten Einvernehmen gestaltet werden".
- **Isolated individual reports of bad managers:** "Mobbing, Angstmacherei, Druck und Neid" (Kununu, July 2026); "bessere Möglichkeiten bieten gegen toxische Vorgesetzte vorzugehen" (Kununu, July 2026).

Overlap with hard red flags: communication breakdown (Kununu's lowest factor) and isolated toxic-supervisor reports. No reports of unpaid overtime, 24/7 availability, layoffs or surveillance.

### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | Isolated, institute-level. "Mobbing, Angstmacherei, Druck und Neid" (Kununu, July 2026), "toxische Vorgesetzte" (Kununu, July 2026). Senior management scores 3.9-4.1 on Glassdoor and CEO approval is 77%, so this is not systemic |
| 24/7 Work Expectation | None found. Flexitime without core hours; overtime recorded and taken as time off |
| Internal Surveillance | None reported. One reviewer complains about the *absence* of systematic time recording ("Eine systematische Arbeitszeiterfassung fehlt", Kununu, March 2026), the opposite of surveillance. Monitoring tools would be subject to works council co-determination |
| Fear-driven Management | One report ("Druck von oben", "Angstmacherei"). Not a recurring theme |
| Communication Breakdown | **Recurring.** Kununu's worst factor (Kommunikation 3.5, 68 reviews): "Die Kommunikation innerhalb des Unternehmens ist eine Katastrophe". Mostly about administration and HR processes |
| Unpaid Overtime | None. Overtime is recorded and compensated as time off under TVöD |
| Silent Firings | Not reported. One former employee says exits are "nicht immer im beiderseitig guten Einvernehmen" (about leave entitlement settlement), but no managed-out pattern. Contract non-renewal at the end of fixed terms is the normal attrition mechanism |
| Work-Life Balance issues | None. WLB is the top-rated Glassdoor category (4.5; 4.8 for software reviewers) |

**Risk level: LOW.** The negative signals are (b) large-organisation public-sector bureaucracy and slow administration, which is not a disqualifier, plus (c) localised supervisor problems in individual institutes. No evidence of systemic toxicity.

---

## Section 5: Compensation

### Salary Data

FZJ pays strictly under **TVöD-Bund**. All software postings reviewed state "Pay group 13 TVöD-Bund", 39 h/week, plus a **year-end bonus of 75% of a monthly salary** and capital-forming benefits (VL). Table values: TVöD-Bund 2026 (valid 01.05.2026-31.03.2027), read from oeffentlicher-dienst.info via Chromium.

| Grade / Stufe | Monthly gross | Annual gross (12 × monthly + 75% JSZ) | Typical eligibility |
|---|---|---|---|
| E13 Stufe 1 | €4,901.11 | ~€62.5k | Entry, no relevant experience |
| E13 Stufe 2 | €5,279.32 | ~€67.3k | 1+ year relevant experience |
| E13 Stufe 3 | €5,709.87 | **~€72.8k** | 3+ years: realistic minimum for an experienced hire |
| E13 Stufe 4 | €6,177.31 | **~€78.8k** | 6+ years: best realistic case if prior experience is credited (§16 TVöD) |
| E13 Stufe 5 | €6,727.38 | ~€85.8k | 10+ years in grade |
| E13 Stufe 6 | €7,025.87 | ~€89.6k | 15+ years in grade |
| E14 Stufe 4 | €6,594.12 | ~€84.1k | Group-lead type roles only |
| E15 Stufe 4 | €7,214.39 | ~€92.0k | Department/division-lead roles |

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| FZJ job postings (authoritative) | Research Software Engineer / Developer (Garching, Aachen/Jülich) | E13: €58.8k-€84.3k (Stufe 1-6) | €0 | 75% of one month (JSZ) | ~€62.5k-€89.6k; realistic ~€72.8k-€78.8k | 3 postings |
| Glassdoor (employer-provided on posting) | Research Software Developer / Information Engineer | €4,901-€7,026 / month | €0 | n/a | matches E13 | 1 |
| Glassdoor (employee reports, Germany) | Software Engineer | €48.1k-€61.9k | €0 | n/a | ~€48k-€62k | 11 |
| Glassdoor (employee reports, Germany) | Softwareentwickler | €44.7k-€63.5k | €0 | n/a | ~€45k-€64k | 4 |
| Kununu | Wissenschaftliche:r Mitarbeiter:in | Ø €64.3k | €0 | n/a | Ø €64.3k | 56 |
| levels.fyi | - | **No company page** (`forschungszentrum-julich`, `forschungszentrum-juelich` both 404 via Chromium) | | | | 0 |

The Glassdoor employee figures are lower than the E13 grid because they include part-timers, lower grades (E10-E12 for Bachelor-level roles) and early Stufen.

**Munich reference (large, profitable corporations, Senior Software Engineer):** median ~€85k-€100k total, 75th percentile ~€110k-€120k, 90th percentile ~€130k+ (same bracket used across this project's reports).

**Possible levers (UNVERIFIED for this role):** §16(5) TVöD-Bund allows a higher starting Stufe or a recruitment/retention allowance of up to 20% for specialists; Helmholtz centres may pay additional allowances under the Wissenschaftsfreiheitsgesetz. Whether a Munich cost-of-living allowance applies to FZJ staff in Garching could not be verified. These are discretionary and would need to be raised in negotiation.

### Equity / Stock

**None.** No equity, no RSUs, no ESPP, no performance bonus. The only extras are the tariff year-end payment (75% of a monthly salary), capital-forming benefits, and the **VBL** occupational pension (employer-funded supplementary pension), which has real long-term value that private-sector comparisons often omit.

### Verdict

**BELOW.** A realistic entry of ~€72.8k-€78.8k sits roughly €10k-€25k (15-25%) below the Munich median for senior engineers at large profitable corporations, and the E13 ceiling (~€89.6k, after ~15 years) only reaches the lower half of the median band. There is no variable upside.

---

## Section 6: AI/ML & Tech Stack

### AI Strategy

FZJ's AI investment is genuine and large, but research- and infrastructure-oriented:
- **JUPITER**, Europe's first exascale supercomputer (JSC), positioned for training large AI models; FZJ markets it as part of a European AI factory effort.
- **AI Transfer Lab at JSC** and the federally funded AI service centre **WestAI**, prototyping AI applications with companies.
- **Helmholtz AI** and the "AI in focus" career area on the FZJ careers site; numerous ML postdoc and PhD posts (e.g. "Computational Electron Microscopy and Machine Learning", "Representation and Active Learning for Multi-Scale Scientific Imaging", "Hybrid ML + LLM-based Fault Detection" thesis).
- **Neuromorphic and quantum computing** (PGI-15 Neuromorphic Software Ecosystems, JUNIQ quantum computing infrastructure).

At Garching, the work is **research data infrastructure** (FAIR data catalogues, metadata, cloud platform for experiment data) and scientific data-analysis software, not applied ML. AI/ML is not central to the Munich-area software roles.

### Tech Stack

Derived from current FZJ job postings (recruiting.fz-juelich.de), the MLZ Scientific Computing Group site, and the FZJ GitHub organisations (`FZJ-JSC`, `FZJ-IEK3-VSA`, `scgmlz`).

| Category | Technologies |
|---|---|
| **Primary language(s)** | Python (stated as required or preferred in the Garching and Aachen/Jülich RSE postings; leading language in `FZJ-JSC` and `FZJ-IEK3-VSA` repos); C++ with Qt for neutron data-analysis applications (BornAgain, Steca); C, Fortran for HPC |
| **AI/ML** | Research-grade ML (PyTorch-style deep learning on JUWELS/JUPITER), LLM work in theses and research projects; no single production ML platform |
| **Cloud** | On-premises: **Red Hat OpenShift** (Kubernetes) for the MLZ data platform; JSC cloud and HPC (JUWELS, JURECA, JUPITER) |
| **Infrastructure** | Kubernetes/OpenShift, containers, microservices, CI/CD, version control and code review (all listed in the Garching posting); JupyterHub (`jupyter-jsc-jupyterhub`); identity and access management (Kubernetes ecosystem, per a 2026 DevOps IAM posting) |
| **Data** | **SciCat** metadata catalogue and microservices, ontologies/terminology services, federated search across NFDI and European research-data infrastructures, electronic lab notebooks, FAIR data principles |
| **Other** | Open-source-first culture; contributions upstream are part of the role; scientific publications and workshops |

**Summary:** Python-centric research software engineering with C++/Qt for scientific applications and C/Fortran in HPC. At Garching the work is cloud-native research data infrastructure (SciCat microservices on on-prem Red Hat OpenShift/Kubernetes, metadata models, federated catalogues) plus open-source neutron data-analysis software. AI/ML is substantial at the Jülich campus (JSC, JUPITER, Helmholtz AI) but research-oriented rather than production product engineering.

---

## Section 7: Language

English is the working language for software roles. The English-language postings (Garching RSE, Aachen/Jülich Research Software Developer) require "Very good command of written and spoken English ... (at least B2 level according to the CEFR)" and **do not require German**. FZJ describes itself as "an international, multicultural melting pot with people from over 110 countries", offers an International Advisory Service and German language courses, and Glassdoor has many English-language reviews.

Caveats: some posts are advertised in German only and require "Sehr gute Deutsch- und Englischkenntnisse" (e.g. the AI-Consultant role at JSC), and administration (HR, procurement) runs largely in German, which is relevant given the bureaucracy theme.

**Verdict:** **PASS** for the research software engineering roles (English required, German optional). CONDITIONAL for German-advertised roles.

---

## Section 8: Stability

### Financial Position

- **Budget 2025:** €977M total (€498M institutional + €479M third-party), from the official "Daten, Fakten, Menschen 2025 | 2026" brochure (status August 2026). For comparison: €861M (2021), ~€948M (2022). Trend: **growing**.
- **Headcount:** 7,700 (31.12.2025), up from 6,796 (December 2020).
- More than 90% of funding is public. As a Helmholtz centre it benefits from the federal/state Pakt für Forschung und Innovation (multi-year agreed increases).
- **Audit issue (August 2026):** Aachener Zeitung (07.08.2026) reports that the Bundesrechnungshof found "nicht zuwendungskonforme Praxis" (a form of double funding through incorrect booking) in the hydrogen cluster funded from structural-change (Strukturwandel) funds. The Board told its ~7,600 staff that precautionary provisions have been made for possible repayments "in Millionenhöhe". No staff consequences have been reported. This is a governance/reputation risk to watch, not a solvency risk for a €977M publicly backed organisation.
- No credit rating (not applicable).

### Financial Runway

Not applicable: FZJ is publicly funded, not VC/PE-backed or loss-making in a commercial sense. The relevant "runway" risk is **project funding for individual positions**: the Garching RSE post is funded by the DFG NFDI consortium DAPHNE4NFDI and limited to two years, so the job's continuation depends on project extension rather than on FZJ's overall finances.

### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| - | **No layoffs found** | - | Searches for Stellenabbau, Sparmaßnahmen, Einstellungsstopp 2025-2026 returned nothing. Headcount grew from 6,796 (2020) to 7,700 (2025) |

Attrition happens through non-renewal of fixed-term contracts (the normal mechanism in German research institutions under the WissZeitVG/TzBfG), not through redundancy programmes.

### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | **YES** (Betriebsrat and Gesamtbetriebsrat) | FZJ is currently advertising "Sachbearbeiter:in / administrative:r Assistent:in für den Gesamtbetriebsrat / Betriebsrat"; Kununu (July 2026): "Den Betriebsrat finde ich toll! Er stand zu 100% auf meiner Seite"; one critical Kununu review (Feb 2026): "kein Rückhalt für Kollegen durch den Betriebsrat" |
| Collective agreement | **Sector agreement: TVöD-Bund** (public service, federal level; unions ver.di / dbb) | Every posting: "Pay group 13 TVöD-Bund"; FZJ benefits page: "Salaries are based on the Collective Agreement for the Public Service (TVöD)"; reviewer con "Tarif gebunden" |
| European works council (multinationals) | N/A | Not a multinational group |
| Conflict signals | None found | No reports of blocked elections or union disputes |

Note: as a research organisation FZJ is likely a "Tendenzunternehmen" (§118 BetrVG), which limits co-determination in economic matters, but the §102 hearing before dismissals and §87 co-determination on working time and monitoring still apply. The TVöD also caps senior pay (see Section 5); "außertariflich" contracts are not a realistic option for engineering roles.

**Verdict:** **PASS.** Works council plus sector collective agreement, growing budget and headcount, no layoffs. The fixed-term nature of project-funded posts is the main individual-level stability risk.

---

## Section 9: Regulated Industry

FZJ is a public research institution, not a regulated commercial sector (no BaFin, medical-device, automotive-safety or ITAR regime for software). Practical overhead comes instead from **public-funding rules**: procurement law (Vergaberecht), grant accounting (Zuwendungsrecht, as the Bundesrechnungshof finding shows) and slow approval processes, which reviewers describe as heavy bureaucracy. Research software is open source and not safety-certified.

One site-specific point: MLZ is co-located with the **FRM II research reactor** in Garching. Access to the nuclear site's controlled areas may require an atomic-law reliability check (Zuverlässigkeitsüberprüfung); Glassdoor interview reports list "Hintergrundüberprüfung" (9%) and "Drogentest" (4%) as steps. Whether this applies to office-based software staff could not be verified.

**Verdict:** **PASS** (low regulatory burden on engineering; administrative overhead is bureaucratic, not regulatory).

---

## Section 10: On-Call

No posting mentions on-call, Rufbereitschaft or 24/7 support. The Garching role is "develop and operate" for the MLZ data platform, so some operational responsibility exists, but it serves a scientific user programme rather than a commercial SaaS with uptime SLAs. Any on-call (Rufbereitschaft) under TVöD is regulated, paid, and subject to works council co-determination (§87(1) Nr. 2-3 BetrVG). Neutron instruments run experiments around the clock during reactor cycles, which could create out-of-hours expectations for instrument-facing software in some teams; this is not mentioned in the software postings.

**Verdict:** **PASS** (no on-call found), with CAUTION for platform-operations roles that support beamtime: confirm in interview.

---

## Section 11: Interview Process

Based on Glassdoor (34 interview reports, all roles; zero reports for software roles).

| Metric | Value |
|---|---|
| Difficulty | 2.94 / 5 (Glassdoor) |
| Positive experience | 85.3% |
| Average duration | ~26 days (7 days for Research Assistant, up to 90 days for doctoral positions) |
| Rounds | Typically 1-2 (application screening, then a panel interview, sometimes with a presentation) |

Reported stages: group/panel interview (23%), presentation (21%), one-to-one interview (13%), skills test (11%), background check (9%), phone interview (9%), IQ test (4%), drug test (4%), personality test (2%). The process follows the public-sector pattern: a structured panel (hiring manager, team members, often HR, works council and equal-opportunity representatives) rather than LeetCode rounds. Expect a short talk on past work and a technical discussion. **Experience/design-focused, not LeetCode-heavy.** No software-specific interview reports exist, so treat this as directional.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | BORDERLINE. Research centre; strong RSE/HPC software culture (JSC, Python open source), but software is instrumental |
| Not consulting | PASS. Internal platforms and open-source research software; avoid the "AI-Consultant im Forschungstransfer" type of role |
| Profitable | N/A. Non-profit, >90% public funding; budget €977M (2025) and growing |
| Employee count | 7,700 total; small engineering population at the Garching outstation (exact number unknown) |
| English-speaking | PASS. English B2 required, German not required for RSE postings |
| Local entity + engineering contracts | PASS. FZJ GmbH, HRB 3498 Düren; direct employment, place of work Garching (München) |
| Location / work model | Garching research campus, U6 Garching-Forschungszentrum ~250 m; hybrid by agreement, flexitime with no core hours |
| Glassdoor | 4.0 (195 reviews), WLB 4.5, 80% recommend; Germany 4.0 (107); no Munich reviews; software 4.3 (4 reviews) |
| Kununu | 4.0, 83% recommendation, 332 employee reviews, **Top Company 2027** |
| Salary | BELOW. TVöD-Bund E13: realistic ~€72.8k-€78.8k, ceiling ~€89.6k; no equity or bonus |
| AI/ML content | Strong at Jülich (JUPITER, Helmholtz AI, WestAI), research-oriented; low in Garching software roles |
| Computer-language/Tech-stack | Python-centric; C++/Qt for scientific apps; Kubernetes/OpenShift, SciCat, microservices at Garching |
| No on-call | PASS (none mentioned); confirm for platform-operations roles |
| WLB / Stability | Strong. WLB 4.5-4.8; growing budget and headcount; no layoffs |
| Works council / collective agreement | PASS. Betriebsrat and Gesamtbetriebsrat; TVöD-Bund |
| Regulated industry | PASS. Public-funding bureaucracy rather than regulation; possible nuclear-site access check at Garching |
| Review themes | Positive: WLB, flexibility, infrastructure, security. Negative: bureaucracy, communication, fixed-term contracts, capped pay |
| Contract type | CAUTION. Garching software post limited to 2 years, project-funded |
| Audit risk | Bundesrechnungshof hydrogen-cluster finding (Aug 2026); provisions made; no staff impact reported |

---

## Section 13: Verdict

**Monitor, and apply selectively where a role fits: FZJ is one of the strongest public-sector research employers reachable from Munich on culture and work-life balance, but pay is tariff-capped and Munich-area engineering roles are few and usually fixed-term.**

**Strengths:** Glassdoor 4.0 with 4.5 WLB on 195 reviews, Kununu 4.0 with 83% recommendation and a Top Company 2027 badge, and a 2023 Glassdoor Best Places to Work Germany ranking (6th) put FZJ well ahead of comparable research employers. Flexitime with no core hours, recorded overtime, hybrid work and 30 days' leave (31 from 2027) give dependable WLB. A works council and the TVöD-Bund agreement provide strong employee protection, the budget and headcount are growing, and there are no layoffs. Engineering is Python-centric, English is the working language, the tech is modern and cloud-native at Garching (OpenShift/Kubernetes, microservices, SciCat), and the office is next to a U6 station.

**Hard blockers (numbered):**

None under the current selection criteria file, which sets no salary floor and no employer-size minimum. The issues below are significant but not formally disqualifying:

1. **Compensation (BELOW market).** E13 TVöD-Bund: a realistic ~€72.8k (Stufe 3) to ~€78.8k (Stufe 4), against a Munich senior-engineer median of ~€85k-€100k and a 75th percentile of ~€110k-€120k. The E13 ceiling of ~€89.6k is reached only after ~15 years. No equity, no bonus; VBL pension is the main offset.
2. **Fixed-term, project-funded contract.** The Garching software post is limited to two years under a DFG NFDI project. Permanent posts exist at FZJ (e.g. some JSC scientific-programmer posts) but are rare, and none was found in Garching.

**Secondary concerns:**
- **Bureaucracy and communication** are the dominant complaints across both platforms (Kununu's lowest factor: Kommunikation 3.5). Expect slow procurement, HR and approval processes.
- **Small Munich footprint:** no Glassdoor reviews from Munich; the outstation's culture is not directly evidenced, and career moves inside FZJ mostly mean Jülich.
- **Software is not the product:** engineers serve scientists; career ladders are those of research support (E13 to E14 with group lead), not a staff/principal engineering track.
- **Bundesrechnungshof audit finding** (August 2026) on the hydrogen cluster: watch for consequences, though no staff impact has been reported.
- **Possible security screening** for access to the FRM II/MLZ site.

**Recommendation:** Worth applying to a Garching research-software role if public-sector terms (tariff pay, VBL pension, likely fixed-term start) are acceptable. In the interview process, verify:
- **Stufe placement** under §16 TVöD and whether a §16(5) allowance (up to 20%) or any Munich allowance is available;
- **Contract duration and the realistic path to a permanent contract** (project extension prospects for DAPHNE4NFDI);
- **Home-office arrangement** in days per week for the specific group;
- **Operational duties**: whether running the OpenShift data platform involves out-of-hours support during reactor cycles;
- **Site access requirements** (reliability check) for the MLZ/FRM II campus;
- **Team size and composition** of the JCNS cloud infrastructure and Scientific Computing groups in Garching.

---

## Sources

- [Forschungszentrum Jülich - Legal Notice](https://www.fz-juelich.de/en/legal-notice)
- [FZJ - Daten und Fakten (brochure index)](https://www.fz-juelich.de/de/presse/datenundfakten)
- [FZJ - Daten, Fakten, Menschen 2025 | 2026 (PDF; budget, personnel)](https://www.fz-juelich.de/de/presse/datenundfakten/daten-fakten-menschen-2024-2025-1/@@download/file) (downloaded with curl)
- [FZJ - Facts & Figures](https://www.fz-juelich.de/en/about-us/organization/facts-figures) (Chromium via CDP; content did not render)
- [FZJ - Jülich as an Employer](https://www.fz-juelich.de/en/careers/working-at-forschungszentrum-julich/julich-as-an-employer) (Chromium via CDP)
- [FZJ - Benefits](https://www.fz-juelich.de/en/careers/working-at-forschungszentrum-julich/benefits) (Chromium via CDP)
- [FZJ - Job vacancies (English)](https://www.fz-juelich.de/en/careers/jobs) (Chromium via CDP)
- [FZJ - Stellenangebote (German)](https://www.fz-juelich.de/de/karriere/stellenangebote) (Chromium via CDP)
- [FZJ - Research Software Engineering career area](https://www.fz-juelich.de/en/careers/areas-of-work/research-software-engineering)
- [Posting 2026T-0852: Research Software Engineer for Data Catalogues and Federated Data Infrastructure (JCNS-4, Garching)](https://recruiting.fz-juelich.de/jobposting/9efef2e4b244cc05c7d016b7e38a77fcd018663a0) (Chromium via CDP)
- [Posting 2026T-0815: Research Software Developer / Information Engineer (IAS-9)](https://recruiting.fz-juelich.de/jobposting/7e86db7fc56746cbe645c2763262c6b5a521b5a30) (Chromium via CDP)
- [Posting 2026T-0798: AI-Consultant im Forschungstransfer (JSC)](https://recruiting.fz-juelich.de/jobposting/04e86d2130881d3caf03080353229e7d215114a00) (Chromium via CDP)
- [Posting: Sachbearbeiter:in für den Gesamtbetriebsrat / Betriebsrat](https://recruiting.fz-juelich.de/jobposting/26296e814c331b928823cf76b68800897d10a70c0)
- [FZJ - JCNS-4 Neutron Methods](https://www.fz-juelich.de/en/jcns/jcns-4) (Chromium via CDP)
- [MLZ - Scientific Computing Group](https://mlz-garching.de/englisch/science-und-projects/project-coordination/scientific-computing.html)
- [MLZ Scientific Computing - software projects](https://computing.mlz-garching.de/)
- [MLZ Scientific Computing - Institutional context](https://computing.mlz-garching.de/context)
- [Neutron mailing list: Postdoc / RSE position in scientific computing at MLZ Garching (2024)](https://lists.neutronsources.org/pipermail/neutron/2024/009377.html)
- [Neutron mailing list: RSE in Scientific Computing Group at MLZ Garching (2021)](https://lists.neutronsources.org/pipermail/neutron/2021/008746.html)
- [Wikipedia - Forschungszentrum Jülich](https://en.wikipedia.org/wiki/Forschungszentrum_J%C3%BClich)
- [German Wikipedia - Forschungszentrum Jülich](https://de.wikipedia.org/wiki/Kernforschungszentrum_J%C3%BClich)
- [NorthData - Forschungszentrum Jülich GmbH, HRB 3498](https://www.northdata.de/Forschungszentrum+J%C3%BClich+GmbH,+J%C3%BClich/Amtsgericht+D%C3%BCren+HRB+3498) (Chromium via CDP)
- [Lobbyregister Bundestag - FZJ (R001857)](https://www.lobbyregister.bundestag.de/suche/R001857/47259)
- [Nominatim - Lichtenbergstraße 1, Garching](https://nominatim.openstreetmap.org/search?q=Lichtenbergstra%C3%9Fe+1,+85748+Garching&format=json&addressdetails=1) (curl)
- [Overpass API](https://overpass-api.de/api/interpreter) (curl, transit stops around the geocoded address)
- [Glassdoor - FZJ reviews (global)](https://www.glassdoor.de/Bewertungen/Forschungszentrum-J%C3%BClich-Bewertungen-E637518.htm) (Chromium via CDP)
- [Glassdoor - FZJ reviews (Germany)](https://www.glassdoor.de/Bewertungen/Forschungszentrum-J%C3%BClich-Deutschland-Bewertungen-EI_IE637518.0,24_IL.25,36_IN96.htm) (Chromium via CDP)
- [Glassdoor - FZJ reviews (Munich, none)](https://www.glassdoor.de/Bewertungen/Forschungszentrum-J%C3%BClich-M%C3%BCnchen-Bewertungen-EI_IE637518.0,24_IL.25,32_IC4990924.htm) (Chromium via CDP)
- [Glassdoor - FZJ reviews (Softwareentwickler filter)](https://www.glassdoor.de/Bewertungen/Forschungszentrum-J%C3%BClich-Bewertungen-E637518.htm?filter.jobTitleFTS=Softwareentwickler) (Chromium via CDP)
- [Glassdoor - FZJ reviews (Software Engineer filter)](https://www.glassdoor.de/Bewertungen/Forschungszentrum-J%C3%BClich-Bewertungen-E637518.htm?filter.jobTitleFTS=Software+Engineer) (Chromium via CDP)
- [Glassdoor - FZJ salaries (software filter)](https://www.glassdoor.de/Gehalt/Forschungszentrum-J%C3%BClich-Geh%C3%A4lter-E637518.htm?filter.jobTitleFTS=software) (Chromium via CDP)
- [Glassdoor - FZJ compensation & benefits](https://www.glassdoor.de/Verguetung-und-Zusatzleistungen/Forschungszentrum-J%C3%BClich-E637518) (Chromium via CDP)
- [Glassdoor - FZJ interviews](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/Forschungszentrum-J%C3%BClich-Fragen-im-Vorstellungsgespr%C3%A4ch-E637518.htm) (Chromium via CDP)
- [Kununu - Forschungszentrum Jülich](https://www.kununu.com/de/forschungszentrum-juelich) (Chromium via CDP; curl returned 405)
- [Teamblind - search (no results)](https://www.teamblind.com/search/Forschungszentrum%20J%C3%BClich) (Chromium via CDP)
- [levels.fyi - forschungszentrum-julich (404)](https://www.levels.fyi/companies/forschungszentrum-julich/salaries) (Chromium via CDP)
- [oeffentlicher-dienst.info - TVöD Bund 2026 table](https://oeffentlicher-dienst.info/c/t/rechner/tvoed/bund?id=tvoed-bund-2026&matrix=1) (Chromium via CDP)
- [oeffentlicher-dienst.info - TVöD Bund overview](https://oeffentlicher-dienst.info/tvoed/bund/) (Chromium via CDP)
- [Aachener Zeitung - Forschungszentrum droht Millionen-Rückzahlung (07.08.2026)](https://www.aachener-zeitung.de/lokales/region-dueren/juelich/forschungszentrum-droht-millionen-rueckzahlung/159761792.html) (Chromium via CDP; WebFetch returned 403)
- [basicthinking.de - Forschungszentrum Jülich offene Stellen (Glassdoor 2023 ranking)](https://basicthinking.de/blog/2023/09/11/forschungszentrum-juelich-offene-stellen)
- [GitHub - FZJ-JSC organisation](https://github.com/FZJ-JSC) (GitHub API via curl)
- [GitHub - FZJ-IEK3-VSA organisation](https://github.com/FZJ-IEK3-VSA) (GitHub API via curl)
- [GitHub - scgmlz (MLZ Scientific Computing)](https://github.com/scgmlz) (GitHub API via curl)
- [GitHub - mlz-ictrl (NICOS instrument control)](https://github.com/mlz-ictrl) (GitHub API via curl)
- [Arbeitsagentur - FZJ RSE posting](https://www.arbeitsagentur.de/jobsuche/jobdetail/19380-05fybfnzgz-S)
- [Arbeitsagentur - Data Software Engineer, Weather and Climate Data](https://www.arbeitsagentur.de/jobsuche/jobdetail/19380-d9o71f86pl-S)
- [AlmostHired - DevOps Engineer for Identity and Access Management (FZJ, 2026)](https://www.almosthired.co/jobs/devops-engineer-for-identity-and-access-management-forschungszentrum-juelich-gmbh-p-va-personalabrechnung-juelich-5178a2ae93a56c49b58c08290c998e17)
- [Revelio Labs - FZJ employees (third-party estimate)](https://www.reveliolabs.com/companies/forschungszentrum-julich/employees)
