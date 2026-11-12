# Rosenxt Group - Full Research Report

_Researched: 2026-11-12_

> **Critical Disqualifiers**
> 1. **No Munich office.** All German sites are in Lower Saxony (Wietmarschen-Lohne, Osnabrück, Bremen), Schleswig-Holstein (Kiel), Hesse (Lampertheim), Bavaria-Lower Franconia (Alzenau, ~370 km from Munich), Baden-Württemberg (Stutensee) and Saxony (Dresden). Most engineering roles are listed as in-office or hybrid at one of these sites. Only a few postings (e.g. Engineering Manager Software & AI) offer "fully remote/hybrid in Germany".
> 2. **Not software-centric.** A sensor, robotics, materials and inspection-services group. Software and AI are enabling layers for hardware and field services in subsea, offshore, pipeline and water-network integrity.
> 3. **Compensation well below the Munich large-corporate bracket.** Kununu averages are €66.6K for Data Scientists and €68K for computer-science engineers (Lohne). The best disclosed senior software band is €80K-120K for a Senior Cloud Software Architect.
>
> The full report follows for completeness.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | End of 2023 (≈3 years). It was carved out of the ROSEN Group's "New Ventures" unit, whose engineering lineage the company markets as "45 years". The German R&D entity was registered in January 2023. |
| Employees | ~740 worldwide, ~370 at Wietmarschen-Lohne (Kununu employer profile, 2026). Earlier figures were ~400 (Feb 2024) and 463 (Built In). |
| Revenue (FY2025) | Group revenue is **UNKNOWN** (Swiss AG, not published). The German R&D entity ROSENXT Creation Center GmbH had €65.7M in 2025, up from €37.2M in 2024 (NorthData, from the filed Jahresabschluss). |
| Profitability | Creation Center GmbH: net loss -€3.09M (2023), net loss -€8.34M (2024), **net profit +€1.97M (2025)**, audited by PwC. Group-level P&L is unknown. **BORDERLINE** |
| Ownership | Private and founder-owned. Hermann Rosen funded it after selling his majority stake in the ROSEN Group to Partners Group (Nov 2023). There is no VC or PE. The holding company is Rosenxt Holding AG in Stans, Switzerland. |
| Software-centric | Hardware, sensors, robotics and field inspection services, with an AI/cloud software layer. **FAIL** |

### Key People

- **Hermann Rosen**: founder and Chairman of the Board. He founded the ROSEN Group (pipeline inspection, ~4,000 employees).
- **Dirk van Vinckenroye**: CEO Creation (R&D and manufacturing). He is Geschäftsführer of ROSENXT Creation Center GmbH and ROSENXT Deutschland GmbH.
- **Chris Yoxall**: CEO Realization (deployment and operation of services).
- **Nancy Terwey**: Chief Human Resources Officer (Prokura at Creation Center GmbH).
- The software organisation has a "Head of Software and AI" and a UK-based "Head of AI" (from job postings; names not published).

### Funding History

The company has no external funding rounds. It is funded by the founder from the proceeds of the 2023 ROSEN majority-stake sale to Partners Group. The price was undisclosed. Public R&D grants recorded by NorthData for Creation Center GmbH:

| Date | Grant | Amount |
|---|---|---|
| 2025 | FORE-PAIR | €6.95M |
| 2025 | CIAM | €6.23M |
| 2026 | ReMePho | €1.88M |

### Acquisitions

| Date | Target | Notes |
|---|---|---|
| 2025 | Beam | Subsea technology |
| 2026 | K.U.M. Umwelt- und Meerestechnik Kiel GmbH | Marine/environmental technology, Kiel |
| Jul 2026 | Zupt LLC (Houston) | ~25 employees; subsea metrology and 3D inspection |
| n/a | InQu Solutions GmbH (Dresden), IDS GmbH, CERTivation GmbH, SORONA Inc. (US) | Group companies listed on the locations page |

### Business Model

Rosenxt splits **Creation** (developing and manufacturing new technologies and products) from **Realization** (deploying and operating technology-based services in harsh environments). Its business fields are:

- subsea and offshore (AUVs, metrology, inspection)
- waterline integrity (inspection of water pipelines, "Rosenxt Linegy")
- upstream optimization (oil and gas)
- industrial inspection
- advanced materials

Customers are critical-infrastructure operators. Revenue comes from products, inspection services and public R&D grants.

### Software-Centric Assessment

Software is not the product. The open roles are dominated by:

- sensor development (ultrasound, signal processing, embedded)
- maritime robotics (C++/ROS2 AUV navigation and manipulator control)
- field roles (Offshore Party Chief, AUV Supervisor)
- manufacturing (motor assemblers, machinists)

There is a real Software and AI organisation spanning "data pipelines to autonomous navigation, to customer portals". It covers cloud platforms on Azure/Kubernetes, ML teams in the EU and US, and an AI developer-productivity initiative. It exists to process sensor data and serve inspection customers. This is comparable to an industrial inspection firm with a growing digital arm. **FAIL** against the software-centric criterion.

---

## Section 2: Local Commercial Entity in Germany

Verified on NorthData (northdata.de) from the Amtsgericht Osnabrück register entries.

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **ROSENXT Creation Center GmbH** (formerly ROSEN Creation Center GmbH) | Amtsgericht Osnabrück HRB 218557 (EUID DEP3313.HRB218557) | Lanzstr. 1, 49835 Wietmarschen | "Die Durchführung und/oder Beauftragung von Forschung, Entwicklung, Herstellung und Vertrieb von elektronischen und mechanischen Geräten jeglicher Art sowie aller damit im Zusammenhang stehender Ingenieurdienstleistungen im Bereich der konventionellen als auch erneuerbaren Energien sowie kritischen Infrastrukturen …" plus IP holding and licensing. Share capital €100,000. |
| **ROSENXT Deutschland GmbH** (formerly BluBee GmbH) | Amtsgericht Osnabrück HRB 216494 | Lanzstr. 1, 49835 Wietmarschen | "Die Erbringung von Ingenieursdienstleistungen jeglicher Art, insbesondere … im Bereich der konventionellen als auch erneuerbaren Energien sowie kritischen Infrastrukturen". Share capital €25,000. |
| **ROSENXT Incubation GmbH** | Amtsgericht Osnabrück HRB 219246 | Wietmarschen | Incubation vehicle (purpose not retrieved) |
| Rosenxt Holding AG (parent) | Swiss register CHE-413.627.564, Stans NW | Obere Spichermatt 12, 6370 Stans, Switzerland | Group holding (legal notice) |

The Creation Center's registered purpose is explicitly research, development, manufacturing and engineering services. It is not a sales shell. Job postings name "Rosenxt Creation Center GmbH" as the employer (startup.jobs, itjobboard), so engineers are employed directly by a German GmbH and not through an EOR. The Creation Center also appears as the operating entity at Alzenau, Bremen, Lampertheim, Osnabrück, Stutensee and even Enschede (NL).

**Verdict:** **PASS** (the entity exists and does engineering, but nowhere near the city of interest; see Section 3)

---

## Section 3: Office Location

- **Office addresses** (from the Regions & Locations page): there is **no Munich office**.

  | Site | Address | Entity |
  |---|---|---|
  | Main campus | Lanzstraße 1, 49835 Wietmarschen-Lohne (Gewerbegebiet A31 Lohne, Landkreis Grafschaft Bentheim). This is the new >110,000 m² campus "Nexus / nxt generation" (Nominatim). | |
  | Osnabrück | Albert-Einstein-Straße 8, 49076 Osnabrück (Wissenschaftspark Osnabrück, Westerberg; Nominatim) | |
  | Bremen | Arberger Hafendamm 22, 28309 Bremen | |
  | Stutensee | Kopernikusstraße 6, 76297 Stutensee | |
  | Lampertheim | Wilhelm-Herz-Ring 29, 68623 Lampertheim | |
  | Alzenau | Industriestraße 13, 63755 Alzenau | |
  | Kiel | Wischhofstraße 1-3, 24148 Kiel | K.U.M. |
  | Dresden | Sudhausweg 3, 01099 Dresden | InQu Solutions |

  Abroad: Stans (CH), Enschede (NL), Bristol and Aberdeen (UK), Houston, Columbus and San Luis Obispo (US), Calgary (CA), Ho Chi Minh City (VN).

- **Nearest public transport: UNVERIFIED.** Nominatim geocoded the main campus to 52.4813, 7.2005 and Osnabrück to 52.2892, 8.0187. Both Overpass endpoints (overpass-api.de: HTTP 406 and timeouts; overpass.kumi.systems: timeouts) failed during this session, so stops and lines could not be listed. The Wietmarschen-Lohne campus is in a commercial park next to the A31 motorway in a rural district. Kununu reviewers list "Parkplatz" as the most-confirmed benefit (82%).

- **Work model:** hybrid in most cases.
  - Benefits text: "Flexible Arbeitszeiten, Arbeitszeitkonten und Home Office im Rahmen eines hybriden Systems möglich" (Kununu employer profile).
  - The Osnabrück frontend posting states "HYBRID 40% on-site".
  - Robotics roles: "location in Bremen or Wietmarschen-Lohne with flexible working time models and the option of home office".
  - Exception: Engineering Manager Software & AI is "fully remote/hybrid in Germany (with office options in Wietmarschen-Lohne, Osnabrück, or Bremen)", with 2-3 in-person workshops a year in Germany and 2 in the US.
  - Built In tags most postings as "In-Office".

  Full remote from Munich is the exception, not the policy.

---

## Section 4: Reviews

**GPTW:** No Great Place to Work Germany certification found (greatplacetowork.de search returned nothing; no mention on the company site). Rosenxt holds the **Kununu Top Company** award (2024, announced 21 Nov 2024; the 2027 badge is shown on the profile).

#### Glassdoor

Retrieved via Chromium/CDP (logged-in session), employer ID E10036777.

| Metric | Global | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | 5.0 (11 reviews) | ≈5.0 (all visible reviews are German sites: Wietmarschen, Alzenau) | No data (0 reviews) | 1 review (Software Engineer intern, 2025) |
| **WLB** | 5.0 | ≈5.0 | n/a | n/a |
| **Culture & Values** | 4.8 | ≈4.8 | n/a | n/a |
| **Comp & Benefits** | 4.3 | ≈4.3 | n/a | n/a |
| **Career Opportunities** | 4.6 | ≈4.6 | n/a | n/a |
| **Diversity & Inclusion** | 4.8 | ≈4.8 | n/a | n/a |
| **Senior Management** | 4.7 | ≈4.7 | n/a | n/a |
| **% Recommend** | 100% | ≈100% | n/a | n/a |
| **CEO Approval** | Not shown separately | n/a | n/a | n/a |
| **Business Outlook** | 81% positive | n/a | n/a | n/a |

Only 11 reviews exist, most posted in a cluster on 27-29 April 2026, and all are 5-star. That pattern looks like a solicited review campaign. Treat these numbers as **not reliable**.

#### Kununu

Retrieved via Chromium/CDP; the slug is `rosenxt-group` (curl returned 405).

- **Overall score:** 4.4 / 5.0 (51 employee reviews since 2024; the industry average for Maschinenbau is 3.7)
- **Recommendation rate (Weiterempfehlung):** 91% (last 2 years)
- **Total reviews:** 92 (employee reviews: 51; the rest are applicant reviews)
- **Sub-scores:** Karriere & Gehalt 4.1, Unternehmenskultur 4.4, Arbeitsumgebung 4.4, Vielfalt 4.6
- **Kununu Top Company:** **YES** (2024 award; 2027 badge on the profile)

#### Blind / Teamblind

No company page (teamblind.com/company/Rosenxt returns 404). Coverage is unsurprisingly nil for a 3-year-old industrial group with no US tech presence.

#### Review Themes (2024-2026)

**Positives:**
- Interesting engineering problems: "Paradies für Ingenieure, sehr interessante, einzigartige Aufgaben" (Kununu, Sep 2026, Angestellte/r oder Arbeiter/in, Forschung / Entwicklung, Lingen).
- Flat hierarchy and autonomy: "flache Hierarchie mit sehr viel delegierter Verantwortung und Freiräumen, starkes Teamgefühl, kein Kaputt-Sparen" (Glassdoor, Apr 2026, Engineering, current employee, less than 1 year, Wietmarschen).
- Long-term private ownership: "Privatgeführtes Unternehmen mit langfristigem Fokus, damit folgt Leistung dem Ziel und nicht einem Quartalsdruck" (Kununu, Oct 2024, Führungskraft, Lingen).
- Flexibility: "Man kann sehr flexibel arbeiten, Home-Office ist für die meisten möglich" (Kununu, Sep 2024, Angestellte/r oder Arbeiter/in, Forschung / Entwicklung, Lingen).
- Learning time: "Es wird einem die Zeit gegeben während der Arbeit zu lernen und sich weiterzubilden" (Kununu, Sep 2026, Angestellte/r oder Arbeiter/in, Forschung / Entwicklung, Lingen).

**Negatives:**
- Pay stalls after joining. This is the most consistent theme across platforms:
  - "Benefits super, Gehalt zum Einstieg auch, danach wird es schwierig mehr zu kriegen" (Kununu, Sep 2026, Angestellte/r oder Arbeiter/in, Forschung / Entwicklung, Lingen).
  - "Ich verdiene weniger als der Durchschnitt in Deutschland, besonders nach einigen Jahren im Unternehmen" (Kununu, Jul 2025, Angestellte/r oder Arbeiter/in, Forschung / Entwicklung, Lingen).
  - "Gehalt könnte besser" (Kununu, Sep 2024, Forschung / Entwicklung).
- Communication on personal topics: "Bei persönlichen Themen, wie Weiterbildung, Leistung und Gehalt wird man gerne hingehalten" (Kununu, Sep 2026, Angestellte/r oder Arbeiter/in, Forschung / Entwicklung, Lingen).
- Immature processes. Nearly every Glassdoor review mentions it, e.g. "einige Prozesse noch nicht etabliert und teilweise sind Vorgehensweisen intransparent, Umgang mit Leistung und Verantwortung teilweise laissez-faire" (Glassdoor, Apr 2026, Engineering, current, less than 1 year, Wietmarschen).
- Overtime and growth-first culture (one review): "alles ist nur auf schnelles Wachstum und möglichst viele Neueinstellungen ausgelegt … Bezahlung eher durchschnittlich, dafür sind dauerhaft Überstunden notwendig" (Kununu, Sep 2024, Angestellte/r oder Arbeiter/in, Forschung / Entwicklung, Lingen, title "Hohe Arbeitsbelastung, wenig Work-Life-Balance").
- Strategic uncertainty: "Die Zukunft des Unternehmens ist weiterhin unklar und es nicht viele verschiedene Projekte gibt, an denen man teilnehmen kann" (Kununu, Jul 2025, Angestellte/r oder Arbeiter/in, Forschung / Entwicklung, Lingen).

#### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | No signals. Management is described as "Richtige und korrekte Hands-on Mentalität, volle Unterstützung und Rückenwind" (Kununu, Sep 2024, Administration / Verwaltung). |
| 24/7 Work Expectation | None reported. |
| Internal Surveillance | None reported. |
| Fear-driven Management | None reported. The opposite complaint appears: "laissez-faire" handling of performance. |
| Communication Breakdown | **Moderate.** It recurs on Kununu around pay and development: "Kommunikation ist zu schwach an manchen Stellen" (Sep 2026, F&E) and "zeigt sich das eigentliche Kommunikationsproblem" (Jul 2025, F&E). |
| Unpaid Overtime | One review (Sep 2024, F&E): "dauerhaft Überstunden notwendig". Working-time accounts (Arbeitszeitkonten) are offered, which suggests overtime is tracked. |
| Silent Firings | None reported. |
| Work-Life Balance issues | Mostly positive (Glassdoor WLB 5.0). One dissenting Kununu review from 2024. |

**Risk level: LOW.** The negatives are those of a young, fast-growing organisation: undefined processes and slow answers on salary. They are not systemic toxicity. The near-perfect Glassdoor profile is too thin and clustered to count as strong positive evidence.

---

## Section 5: Compensation

#### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| Kununu (Lohne) | Data Scientist | ~€66.6K | 0 | n/a | ~€66.6K | 8 |
| Kununu (Lohne) | Informatik-Ingenieur:in | ~€68.0K | 0 | n/a | ~€68.0K | 3 |
| Kununu (Lohne) | Solution Architect | ~€72.7K | 0 | n/a | ~€72.7K | 2 |
| Kununu (Lohne) | Teamleiter:in | ~€91.2K | 0 | n/a | ~€91.2K | 6 |
| Kununu (Lohne) | Abteilungsleiter:in | ~€94.5K | 0 | n/a | ~€94.5K | 2 |
| Job posting (aggregator) | Senior Cloud Software Architect, Wietmarschen | €80K-120K | 0 | n/a | €80K-120K | 1 posting |
| Job posting (aggregator) | Software Architect, Water Line Integrity, Wietmarschen | €5,000-6,917/month (~€60K-83K/yr) | 0 | n/a | ~€60K-83K | 1 posting |
| Glassdoor | No titles with salary data (5 salaries filed for Wietmarschen, not broken out) | n/a | n/a | n/a | n/a | 0 |
| levels.fyi | No company page (404) | n/a | n/a | n/a | n/a | 0 |

Munich benchmark for a Senior Software Engineer at a large, profitable corporation: base roughly €85K-105K, rising to €110K-130K+ at Staff level (market reference from earlier reports). No company-specific Munich percentiles exist, since there is no Munich office.

#### Equity / Stock

**None.** This is a privately held, founder-owned group with no employee equity programme mentioned anywhere (postings, Kununu, website). The benefits are:

- company pension (betriebliche Altersvorsorge)
- capital-forming payments (vermögenswirksame Leistungen)
- insurance discounts
- EGYM Wellpass
- bike and IT leasing
- a company daycare and canteen (Wietmarschen only)

A Kununu reviewer asks for "Bonuszahlungen oder ähnliches", which suggests there is no standard bonus.

#### Verdict

**BELOW.** Kununu engineering averages (€66-73K) and the top disclosed senior software band (€80-120K) sit well under the Munich large-corporate bracket. Several reviewers say raises after joining are hard to get.

---

## Section 6: AI/ML & Tech Stack

#### AI Strategy

The AI work is real and applied: AI on sensor data (inspection, signal processing, autonomous navigation), not marketing. The evidence:

- There is a distributed "Software and AI organization" spanning Europe, the US and Southeast Asia. The EU AI/ML team (data scientists and ML engineers) reports to a UK-based Head of AI (Engineering Manager AI posting).
- Teams "develop advanced AI and software solutions that process large sensor datasets, build intelligent cloud services, and power real-time edge applications" (Engineering Manager Software & AI posting). The US team has 13 engineers across AI/ML, cloud backend, frontend and DevOps.
- There is an internal **AI-assisted development initiative**. The Senior AI Engineer for Developer Productivity & SDLC (Enschede plus 4 other locations) works on GitHub Copilot, custom agents, local LLMs, MCP integrations, RAG over internal documentation, ML CI/CD templates and EU AI Act governance.
- An "Intelligent Service Operations Hub" is a centralised Kubernetes/Azure cloud platform for AI-driven services (Senior Cloud Software Architect posting).
- Autonomous underwater vehicles use ROS2 for navigation, manipulation and signal processing for subsea non-destructive testing (Robotics Software Engineer postings).
- Rosenxt was a sponsor and speaker at PyCon DE & PyData 2025 (talk on "how we use Python to measure the performance of our products and technologies under near-real-world conditions"). It is a Platinum sponsor of PyCon DE 2027.

#### Tech Stack

Derived from job postings (Built In, devjobs.de, ZipRecruiter and aggregator snippets, LinkedIn), the devjobs.de team profile and the PyCon DE sponsorship.

| Category | Technologies |
|---|---|
| **Primary language(s)** | Python (ML, data, cloud services, test/measurement), C++ (robotics, embedded), TypeScript/JavaScript (frontends, customer portals), Bash |
| **AI/ML** | LLMs and foundation/embedding models, RAG, agentic frameworks, MCP, GitHub Copilot, local LLMs, MLOps (CI/CD for ML, versioning, monitoring), classical signal processing, computer vision |
| **Cloud** | Microsoft Azure (primary); AWS/GCP mentioned as acceptable experience |
| **Infrastructure** | Kubernetes (AKS, CNCF stack), Terraform, Ansible, GitHub, Azure DevOps, C4/arc42 architecture documentation, "Golden Paths" |
| **Data** | Large sensor datasets (ultrasound, NDT, navigation); specific data platform not named |
| **Other** | ROS2, Nav2, MoveIt (AUVs); STM32, embedded Linux, FPGA (sensor hardware); IoT and edge applications |

**Summary:** Polyglot. The cloud, data and ML layer is Python-centric on Azure/Kubernetes, and the robotics and embedded layer is C++-centric (ROS2, STM32/FPGA). The AI is applied to industrial sensor data, inspection analytics and autonomous underwater navigation, plus an internal LLM developer-productivity programme. The work is production and applied R&D, partly funded by public research grants, in an industrial hardware and services context.

---

## Section 7: Language

- Most engineering postings are written in English with the "(all genders welcome)" suffix. The Senior AI Engineer and Robotics Software Engineer postings list no German requirement.
- The Engineering Manager AI posting requires **"Fluent German and English; Dutch is a plus"**.
- Several postings are German-only, e.g. "Software Entwickler für C# (m/w/d)" in Stutensee and manufacturing roles.
- Most Kununu and Glassdoor reviews are in German. The main campus is in a rural Lower Saxony district, and the website and benefits are bilingual.
- The group is international (UK Head of AI, US teams, Vietnam, NL), so cross-site work is in English.

**Verdict:** **CONDITIONAL.** English works for individual-contributor AI/software roles. Leadership roles and some German-site roles require German.

---

## Section 8: Stability

#### Financial Position

- **Group:** private and unpublished. It is founder-funded from the 2023 sale of the ROSEN majority stake to Partners Group (terms undisclosed; ROSEN had ~4,000 employees, so the proceeds were likely substantial).
- **ROSENXT Creation Center GmbH** (NorthData, from Jahresabschlüsse audited by PwC; the FY2025 accounts were published 2026-09-30):

  | Year | Revenue | Net result |
  |---|---|---|
  | 2023 | n/a | -€3.09M |
  | 2024 | €37.2M | -€8.34M |
  | 2025 | €65.7M | **+€1.97M** |

  Revenue grew 77% year over year, and the entity turned profitable in 2025. It also holds €15M+ in public R&D grants (2025-2026). A parent-financed R&D GmbH turning a profit may partly reflect intra-group charging, so it is not proof that the group is profitable.
- **Trend:** improving. The group is still investing heavily: a >110,000 m² campus for 700 people, and acquisitions of Beam, K.U.M. and Zupt.

#### Financial Runway

The group is neither VC-backed nor reporting losses at its main German entity, but group profitability is unknown. The model below is indicative only, because the group's cash position is **not public**.

| Cost line | Annual estimate |
|---|---|
| Staff (~740 × avg fully-loaded ~€85K, blended DE/US/UK/VN) | ~€63M |
| Facilities (Wietmarschen campus depreciation, 15+ sites) | ~€10M |
| Materials, manufacturing, field operations, R&D equipment | ~€25M |
| **Total gross burn** | **~€98M/year** |

| Revenue source | Est. annual inflow |
|---|---|
| Creation Center GmbH revenue (2025, partly intra-group) | ~€66M |
| US/UK/CA subsidiaries (Zupt, SORONA, Advanced Materials) | ~€15-25M (estimate) |
| Public R&D grants | ~€5M/year |
| **Total revenue offset** | **~€85-95M/year** |

| Scenario | Net burn | Cash at hand | Runway | Next round needed by |
|---|---|---|---|---|
| Optimistic | ~€0/year (break-even) | Unknown (founder capital) | Indefinite | n/a |
| Base case | ~€5-15M/year | Unknown | Depends on owner | n/a (owner-funded) |
| Stress | ~€30M/year | Unknown | Depends on owner | n/a |

Cash figure: **UNKNOWN.** NorthData shows the Creation Center P&L but not its balance-sheet cash line without premium. handelsregister.ai (normally free) timed out in this session. The risk is owner concentration: a single founder funds the group, and the ROSEN precedent shows he can sell. No external investors impose a deadline.

#### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| none | No layoffs found | n/a | Searched news, TrueUp-style trackers and review text. The headcount trend is strongly upward (400 → 550 → 650 → ~740). |

#### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | **UNKNOWN** (no evidence of one) | No mention in the Kununu reviews scanned, Glassdoor reviews, postings or web search ("Rosenxt Betriebsrat" returned nothing). The ~370 staff at Wietmarschen exceed the threshold, but no election is documented. |
| Collective agreement | **NONE found** | No "Tarif", "tarifgebunden" or "AT-Vertrag" in any posting. Pay is individually negotiated (posting salary ranges, reviewer complaints about negotiating raises). |
| European works council | N/A (no EWC found) | n/a |
| Conflict signals | None found | n/a |

**Verdict:** **CAUTION.** Finances are improving at the German entity and there have been no layoffs, but there is no council or tariff evidence, and the structure depends on a single private owner.

---

## Section 9: Regulated Industry

The company works on critical infrastructure (oil and gas pipelines, offshore, water networks, energy) for customers who are themselves regulated. The relevant regimes are:

- KRITIS / NIS2 for customers
- offshore and HSE safety regimes
- pipeline-integrity standards
- the EU AI Act (explicitly mentioned in AI postings)

Defense is listed as relevant background in one posting. Field and offshore work carries HSE overhead. Software for inspection results feeds safety-relevant integrity decisions, which implies validation and documentation overhead. Typically this is not formal safety certification like ISO 26262 or EN 50128.

**Verdict:** **CAUTION** (moderate; domain-driven documentation and safety culture: "Compliance, quality, and safety are no buzzwords for us")

---

## Section 10: On-Call

- No software posting reviewed mentions on-call or Rufbereitschaft.
- The "Intelligent Service Operations Hub" (a central cloud platform for AI services) and the DevOps/Kubernetes roles are the most likely to carry operational duties.
- Field and offshore roles (Offshore Party Chief, AUV Supervisor) involve deployment rotations, but those are not software roles.
- The ML, R&D and developer-productivity roles are internal or R&D-facing and unlikely to have on-call.

**Verdict:** **CAUTION** (team-dependent; unverified for platform roles)

---

## Section 11: Interview Process

| Metric | Value |
|---|---|
| Difficulty | Not shown (2 interviews only) |
| Positive experience | 100% (2 interviews) |
| Average duration | UNKNOWN |
| Rounds | UNKNOWN |

Glassdoor lists four stages, each reported in 25% of its 2 interviews: phone interview, skills test, group interview, and IQ/intelligence test. On Kununu, the applicant reviews (~41 of the 92 total) praise "a well-structured hiring process and smooth onboarding" (Kununu, Apr 2026, Angestellte/r oder Arbeiter/in, Finanzen / Controlling, Lingen). There is no evidence of LeetCode-style rounds. The IQ test is unusual for software roles and worth asking about. The sample is too small to characterise the process reliably.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | **FAIL.** Sensors, robotics, inspection services; software and AI are enabling layers. |
| Not consulting | PASS. Builds its own products and services; "Ingenieurdienstleistungen" in the registered purpose are delivered as inspection services, not staff augmentation. |
| Profitable | BORDERLINE. German R&D entity +€2.0M in 2025 after -€8.3M in 2024; group unknown. |
| Employee count | ~740 worldwide, ~370 at Wietmarschen-Lohne. |
| English-speaking | CONDITIONAL. English for IC AI/software roles; German required for leadership roles. |
| Local entity + engineering contracts | PASS. ROSENXT Creation Center GmbH, HRB 218557, R&D purpose, direct employment. |
| Location / work model | **FAIL.** No Munich office; hybrid at Lower Saxony and other non-Bavarian sites; full remote only for selected roles. |
| Glassdoor | 5.0 (11 reviews, clustered, unreliable); no Munich or SWE data. |
| Kununu | 4.4, 91% recommend, 51 employee reviews, Top Company. |
| Salary | **BELOW.** Kununu engineers €66-73K; senior architect band €80-120K; no equity, no standard bonus. |
| AI/ML content | Genuine applied AI: sensor analytics, AUV autonomy, LLM developer tooling. |
| Computer-language/Tech-stack | Polyglot: Python (ML/cloud/Azure/K8s), C++ (ROS2/embedded), TypeScript. |
| No on-call | CAUTION. Not mentioned; platform roles unverified. |
| WLB / Stability | WLB good per reviews; growing, founder-funded; owner-concentration risk. |
| Works council / collective agreement | None found. |
| Regulated industry | CAUTION. Critical infrastructure, HSE, EU AI Act. |
| Review themes | Interesting problems and flat hierarchy vs. stagnant pay, immature processes, weak communication on pay. |
| Owner concentration | Single founder funds the group; strategy and continuity depend on one person. |

---

## Section 13: Verdict

**Exclude.**

**Strengths:**
- A well-funded, privately owned and fast-growing industrial technology group, with no quarterly pressure and no layoffs.
- Revenue at the German R&D entity grew 77% to €65.7M, and the entity turned profitable in 2025.
- A genuine applied-AI and Python/Azure/Kubernetes software organisation, including an internal LLM developer-productivity initiative.
- Strong Kununu standing (4.4, 91%, Top Company) and a reputation as a "paradise for engineers" with real autonomy.

**Hard blockers:**
1. **No Munich presence.** The nearest German office is Alzenau (Lower Franconia, roughly 370 km away). The main campus is Wietmarschen-Lohne on the Dutch border, about 700 km away. Most engineering roles are hybrid at those sites (e.g. "HYBRID 40% on-site" in Osnabrück). Only isolated postings allow full remote within Germany.
2. **Not software-centric.** The product is sensors, robots, materials and inspection services for pipelines, offshore and water networks. Software and AI serve that hardware and field-services business.
3. **Compensation below the Munich bracket.** Kununu shows €66.6K average for Data Scientists, €68K for computer-science engineers and €91K for team leads. The top disclosed senior software band is €80-120K (Senior Cloud Software Architect). There is no equity and no standard bonus, against a Munich Senior/Staff bracket of roughly €95-130K+. Reviewers add that raises after joining are hard to obtain.

**Secondary concerns:**
- Leadership roles require fluent German.
- The Glassdoor profile is thin and suspiciously clustered (11 five-star reviews, mostly within three days in April 2026).
- No works council or collective agreement was found.
- The group depends on one owner.
- Processes are still immature.
- Unclear on-call for cloud platform roles.
- Regulated critical-infrastructure context.

**Recommendation:** Exclude. Further research is not warranted unless Rosenxt opens a Munich site or advertises a senior Python/AI role explicitly as fully remote within Germany. Even then, the company would need to show compensation of at least €100K+ base for a senior or staff individual-contributor role. If such a fully-remote role appears (the Senior AI Engineer for Developer Productivity & SDLC is the closest fit in substance), verify these before investing time:
- the remote eligibility in writing
- the salary band
- how often travel to Wietmarschen is required
- whether the role carries platform on-call

---

## Sources

- [Rosenxt: Our Management](https://www.rosen-nxt.com/en/this-is-rosenxt/who-we-are/our-management)
- [Rosenxt press release: Focusing on the future with Rosenxt (Feb 2024)](https://www.rosen-nxt.com/en/newsroom/news-and-media/press-release/rosenxt-founded)
- [Rosenxt: Regions and Locations](https://www.rosen-nxt.com/en/this-is-rosenxt/regions-and-locations)
- [Rosenxt: Legal Notice](https://www.rosen-nxt.com/en/global/legal-notice)
- [Rosenxt: Working with us](https://www.rosen-nxt.com/en/join-us/working-with-us)
- [Rosenxt: Jobs](https://www.rosen-nxt.com/en/join-us/jobs)
- [Rosenxt: Honoured as a Kununu Top Company (Nov 2024)](https://www.rosen-nxt.com/en/newsroom/news-and-media/news/2024/rosenxt-honoured-as-a-top-company)
- [Rosenxt at PyCon DE & PyData 2025](https://www.rosen-nxt.com/en/newsroom/news-and-media/news/2025/pycon-darmstadt-2025)
- [PyCon DE 2027: Rosenxt sponsor page](https://2027.pycon.de/sponsors/rosenxt/)
- [Rosenxt press release: Zupt acquisition](https://www.rosen-nxt.com/en/newsroom/news-and-media/press-release/zupt)
- [World Oil: Rosenxt expands offshore capabilities with Zupt acquisition (Jul 2026)](https://worldoil.com/news/2026/7/31/rosenxt-expands-offshore-asset-integrity-capabilities-with-zupt-acquisition/)
- [Ocean News: Rosenxt acquires Zupt](https://oceannews.com/news/subsea-and-survey/rosenxt-acquires-zupt-to-expand-subsea-metrology-and-inspection-capabilities/)
- [Ocean News: Rosenxt acquisition of Beam](https://oceannews.com/?p=103491)
- [Ocean News: Rosenxt leadership with two CEOs](https://oceannews.com/news/milestones/rosenxt-strengthens-leadership-structure-with-two-ceos/)
- [Offshore Energy: Swiss technology group buys another subsea business](https://offshore-energy.biz/swiss-technology-group-strengthens-offering-with-purchase-of-another-subsea-business)
- [PGJ Online: ROSEN founder sells majority stake to Partners Group](https://pre-prodadmin.pgjonline.com/news/2023/november/rosen-founder-sells-majority-stake-to-partners-group)
- [NorthData: search "Rosenxt"](https://www.northdata.de/Rosenxt) (via CDP)
- [NorthData: ROSENXT Creation Center GmbH, HRB 218557](https://www.northdata.de/ROSENXT%20Creation%20Center%20GmbH%2C%20Wietmarschen/Amtsgericht+Osnabr%C3%BCck) (via CDP; P&L, revenue, grants, purpose)
- [NorthData: ROSENXT Deutschland GmbH, HRB 216494](https://www.northdata.de/ROSENXT%20Deutschland%20GmbH%2C%20Wietmarschen/Amtsgericht+Osnabr%C3%BCck) (via CDP)
- [handelsregister.ai: ROSENXT Creation Center GmbH](https://handelsregister.ai/de/unternehmen/ROSENXT%20Creation%20Center%20GmbH) (attempted via CDP; timed out)
- [Glassdoor: Rosenxt reviews](https://www.glassdoor.de/Bewertungen/Rosenxt-Bewertungen-E10036777.htm) (via CDP)
- [Glassdoor: Rosenxt interviews](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/Rosenxt-Fragen-im-Vorstellungsgespr%C3%A4ch-E10036777.htm) (via CDP)
- [Glassdoor: Rosenxt salaries](https://www.glassdoor.com/Salary/Rosenxt-Salaries-E10036777.htm) (via CDP)
- [Glassdoor: Software Engineer (Internship) review](https://www.glassdoor.com.au/Reviews/Employee-Review-Rosenxt-E10036777-RVW98292753.htm)
- [Kununu: Rosenxt Group](https://www.kununu.com/de/rosenxt-group) (via CDP; curl 405)
- [Kununu: Rosenxt Group reviews](https://www.kununu.com/de/rosenxt-group/kommentare) (via CDP)
- [Kununu: Rosenxt Group salaries](https://www.kununu.com/de/rosenxt-group/gehalt) (via CDP)
- [Teamblind: Rosenxt](https://www.teamblind.com/company/Rosenxt) (404)
- [levels.fyi: Rosenxt](https://www.levels.fyi/companies/rosenxt/salaries) (404, via CDP)
- [Great Place to Work Germany search](https://www.greatplacetowork.de/?s=rosenxt) (no result, via CDP)
- [Built In: Rosenxt Group](https://builtin.com/company/rosenxt-group) (curl)
- [Built In: Rosenxt Group jobs](https://builtin.com/company/rosenxt-group/jobs) (curl)
- [Built In: Senior AI Engineer, Developer Productivity & SDLC](https://builtinlondon.uk/job/senior-ai-engineer-all-genders-welcome-developer-productivity-sdlc/11570128) (curl)
- [Built In: Engineering Manager AI](https://builtin.com/job/engineering-manager-ai-all-genders-welcome/10906698) (curl)
- [Built In: Engineering Manager Software & AI](https://builtin.com/job/engineering-manager-software-ai-all-genders-welcome/10908911) (curl)
- [Built In: Robotics Software Engineer, High-Level Navigation Planning (AUV)](https://builtin.com/job/robotics-software-engineer-all-genders-welcome-maritime-robotics-high-level-navigation-planning-auv/10869218) (curl)
- [devjobs.de: Rosenxt Group team profile](https://en.devjobs.de/team/rosenxt-group) (via CDP)
- [ZipRecruiter: Senior Cloud Software Architect, Intelligent Service Operations Hub](https://www.ziprecruiter.de/jobs/580743124-senior-cloud-software-architect-all-genders-welcome-for-our-intelligent-service-operations-hub-bei-rosenxt)
- [ZipRecruiter: Senior Cloud-Native Solution Architect (Kubernetes, CNCF, MLOps)](https://www.ziprecruiter.de/jobs/544180296-senior-cloud-native-solution-architect-all-genders-welcome-kubernetes-cncf-mlops-bei-rosenxt)
- [ZipRecruiter: Software Engineer Frontend, Water Line Integrity Solutions](https://www.ziprecruiter.de/jobs/563735632-software-engineer-frontend-all-genders-welcome-in-the-field-of-water-line-integrity-solutions-bei-rosenxt)
- [ZipRecruiter: Embedded Linux Software Engineer (C++/STM32, Python, FPGA)](https://www.ziprecruiter.de/jobs/580743105-embedded-linux-software-engineer-c-stm32-python-fpga-all-genders-welcome-bei-rosenxt)
- [startup.jobs: Rosenxt Creation Center GmbH, Embedded Linux Software Engineer](https://startup.jobs/embedded-linux-software-engineer-c-stm32-python-fpga-all-genders-welcome-0215-rosenxt-creation-center-8698861)
- [Workwise: Software Entwickler für C# (m/w/d)](https://workwise.io/en/job/101620-software-entwickler-fer-c-m-w-d)
- [Fuchsjobs: Senior Machine Learning Engineer, Wietmarschen](https://fuchsjobs.de/job/stellenangebote--senior-machine-learning-engineer-all-genders-welcome-wietmarschen-rosenxt-group-e585f4)
- [LinkedIn Jobs guest search: Rosenxt, Germany](https://www.linkedin.com/jobs-guest/jobs/api/seeMoreJobPostings/search?keywords=Rosenxt&location=Germany) (curl)
- [Nominatim: Lanzstraße 1, Wietmarschen](https://nominatim.openstreetmap.org/search?q=Lanzstra%C3%9Fe%201%2C%2049835%20Wietmarschen&format=json&addressdetails=1) (curl)
- [Nominatim: Albert-Einstein-Straße 8, Osnabrück](https://nominatim.openstreetmap.org/search?q=Albert-Einstein-Stra%C3%9Fe%208%2C%2049076%20Osnabr%C3%BCck&format=json&addressdetails=1) (curl)
- [Overpass API](https://overpass-api.de/api/interpreter) (attempted; 406 and timeouts)
