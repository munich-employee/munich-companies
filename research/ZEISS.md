# ZEISS - Full Research Report

_Researched: 2026-11-03_

> **Critical Disqualifiers**
> 1. **Not software-centric.** ZEISS is an optics, optoelectronics and medical-device manufacturer (semiconductor lithography optics, metrology, microscopy, ophthalmology, lenses). Software is built to support hardware products and internal processes. It is not the product.
> 2. **The ZEISS software office in Munich that is easiest to find is a consultancy.** Carl Zeiss Digital Innovation GmbH (Kistlerhofstraße 75) calls itself a "technology consultancy and (AI) software engineering partner" serving external pharma, medtech, semiconductor and labtech clients. Kununu files it under "Beratung/Consulting". Only ZEISS Digital Partners (internal digital unit) and the Medical Technology robotics team are non-consulting engineering employers in Munich.
> 3. **The group is restructuring in 2026.** On 9 June 2026 ZEISS announced a group-wide cost programme ("several hundred million euros" a year, job cuts expected, no number given). Separately, Carl Zeiss Meditec's "ProfitUp" programme (12 May 2026) puts up to 1,000 jobs at risk worldwide, later reported as 600-700. LinkedIn shows only 3 ZEISS postings in Munich today, none of them in engineering.
>
> The full report follows for completeness.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 1846 in Jena (180 years) |
| Employees | 46,622 globally (30 Sep 2025), about 47,400 (31 Mar 2026). Over 22,000 in Germany (Kununu company profile) |
| Revenue (FY2024/25, Oct-Sep) | €11.896bn (+9% from €10.894bn). Segments: Semiconductor Manufacturing Technology €5.055bn (+23%), Medical Technology €2.704bn (+4%), Industrial Quality & Research €2.334bn (-1%), Consumer Markets €1.569bn (+2%) |
| Profitability | EBIT €1.552bn (13% margin), R&D €1.731bn (15% of revenue), equity ratio 48%. H1 2025/26: revenue €5.841bn (+1%), EBIT €955M (+€33M). Net income is not stated in the press releases - **PASS** |
| Ownership | Foundation-owned. The Carl-Zeiss-Stiftung is the sole owner of the parent, Carl Zeiss AG. The subsidiary Carl Zeiss Meditec AG is listed on the Frankfurt stock exchange and majority-held by the group |
| Software-centric | Hardware, optics and medical-device manufacturer. Software is an enabling function - **FAIL** |

### Key People

- **Andreas Pecher:** President and CEO of the ZEISS Group (succeeded Karl Lamprecht in 2025).
- **Stefan Müller:** CFO.
- **Dr. Michael Bolle:** Chairman of the Supervisory Board of Carl Zeiss AG.

### Business Model

The group has four segments. Semiconductor Manufacturing Technology (SMT, lithography optics for ASML) generates 42% of revenue and is the only segment still growing in 2026. The three segments that sell directly to the market (Industrial Quality & Research, Medical Technology, Consumer Markets) are flat or shrinking, and the cost programme is aimed at them. Each segment has its own software organisation. On top of these sit a central Corporate IT (CIT) and ZEISS Digital Partners (ZDP), which builds digital solutions and runs the group AI programme ("Empowerment with AI") for the business units.

### Software-Centric Assessment

ZEISS sells physical products: EUV optics, coordinate measuring machines, microscopes, surgical microscopes, intraocular lenses, spectacle lenses and camera lenses. Software appears in four forms:

1. **Device and embedded software** (C++ and C# in medical robotics, metrology, microscopy and spectroscopy), often under IEC 62304.
2. **Application software sold alongside the devices** (e.g. ZEISS INSPECT, PiWeb in metrology, ZEN in microscopy, and the ophthalmology data platform).
3. **Internal digital and IT platforms** (ZDP, Corporate IT, SMT data governance).
4. **External custom software consulting** (ZEISS Digital Innovation).

None of these makes ZEISS a software company. The roadmap is set by hardware product cycles and segment economics. Software is described as a "driver" of digitalisation, not as the business. **FAIL.**

### Consulting-Adjacency Assessment

| Unit | Self-description | Client | Verdict |
|---|---|---|---|
| **Carl Zeiss Digital Innovation GmbH** (Dresden HQ, Munich office) | "Technology consultancy and (AI) software engineering partner", "over 300 consultants and tech professionals", building "custom digital solutions" (zeiss.com/digital-innovation/about-us). Registered purpose: "development of individual software solutions and software products **for customers** in various industries" | External: pharma, medtech, semiconductor, labtech | **Consulting.** Kununu classifies it as "Beratung/Consulting". Excluded |
| **ZEISS Digital Partners (ZDP)** (Munich, Oberkochen, Jena) | "Enabling and accelerating the digital transformation of ZEISS @speed and @scale ... developing digital solutions jointly with the ZEISS business units" | Internal ZEISS business units | Internal product and platform work, not billable consulting. Some roles are change management or design thinking rather than engineering |
| **Segments (SMT, IQR, MED, CON) and Corporate Research** | Product R&D | ZEISS customers via products | Not consulting |

A side note: the ZDI headcount on its own pages fell from "600+ consultants and tech professionals" (older version of the about page, quoted by search engines) to "over 300" (current page). No press coverage of cuts at ZDI was found. Treat the drop as UNVERIFIED but notable.

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **Carl Zeiss AG** (group parent and employer for Corporate IT, ZDP and Corporate Research) | HRB 501555, Amtsgericht Ulm. LEI 5299000XH7YX33EJZP65 | Carl-Zeiss-Str. 22, 73447 Oberkochen | "Development, manufacture, processing, and distribution of optical, precision mechanical and optoelectronic products, as well as instruments and other equipment, including the provision of related services", plus holding powers |
| **Carl Zeiss Digital Innovation GmbH** (formerly Saxonia Systems AG) | HRB 40189, Amtsgericht Dresden (previously HRB 225217, Amtsgericht München, and HRB 18796, Dresden) | Fritz-Foerster-Platz 2, 01069 Dresden. Munich office: Kistlerhofstraße 75, 81379 München | "Planning, conception, development of individual software solutions and software products for customers in various industries, including medical technology, industry, trade & logistics and energy ... complete life cycle of a software application" |
| Carl Zeiss Meditec AG (Medical Technology; likely employer of the Munich medical robotics team) | Jena. Registration number **UNVERIFIED** in this research | Jena | Medical technology. Which legal entity employs the Munich robotics team is **UNVERIFIED** |

**Verification:** No ZEISS company is registered in Munich today. NorthData shows that ZDI was once registered at Amtsgericht München (HRB 225217) before it moved its seat to Dresden. Munich staff are employed directly through German entities registered in Oberkochen, Jena or Dresden, working from Munich branch offices. This is a normal German group set-up with direct Arbeitsverträge, not a PEO/EOR arrangement. Carl Zeiss AG's registered purpose covers development, so it is not a sales shell. ZDI's purpose shows it is a customer-project software house. Several current postings are fixed-term (e.g. "fixed-term until November 2027", "befristet für 2 Jahre", "Fixed Term (2 Years)"). A Glassdoor candidate (Software Engineer, Oberkochen, Dec 2024) reports being told only at the end of the interview that the role was a two-year fixed-term contract.

**Verdict:** PASS with CAUTION. The local entities are real engineering employers. However, no entity has its seat in Munich, the ZDI branch is a consultancy, and a visible share of new roles is fixed-term.

---

## Section 3: Office Location

- **Office address:** Kistlerhofstraße 75, 81379 München, in Obersendling (city district Thalkirchen-Obersendling-Forstenried-Fürstenried-Solln). The ZEISS Digital Innovation about page gives this address for its Munich office. OpenStreetMap/Nominatim tags the building "Carl Zeiss Microscopy" (48.0950, 11.5243). Business directories list Carl Zeiss MicroImaging/Microscopy and ZDI at the same address. No public street address was found for ZEISS Digital Partners or the Munich medical robotics team. Postings list only "München". Confirm the office for any specific role.
- **Nearest public transport (Overpass, 700 m radius):**
  - **U3 Aidenbachstraße** (U-Bahn station), about 330 m.
  - **Geisenhausenerstraße** bus stop (line 51), about 560 m.
  - **Siemenswerke** S-Bahn halt (S7), about 630 m.
- **Work model:** Hybrid. ZDP Munich postings advertise a 40-60% hybrid option (about 2-3 office days a week). Kununu reviewers report "Homeoffice mit Einschränkungen (abhängig vom Vorgesetzten)" (Meditec R&D, Aug 2026) and say home office at SMT "wurde etwas zu weit zurückgefahren" (Aug 2026). Some Munich engineering postings (medical robotics C++, Corporate IT Lead DevOps) are listed as in-office. No fully remote engineering roles were found.

---

## Section 4: Reviews

**GPTW:** No group-wide Great Place to Work certification for ZEISS in Germany was found. ZEISS Vision Care Germany was certified in 2023 and named among the "Best Employers Manufacturing & Industry 2024". Carl Zeiss Vision (US) has a GPTW profile, updated March 2026, in which 72% of employees call it a great place to work. **Kununu Top Company 2027:** YES (badge on the profile, plus "Top Rated" seals for salary satisfaction and family friendliness).

### Glassdoor

Source: glassdoor.de employer profile E9052 ("ZEISS Group"), read through the persistent browser (CDP) from the embedded rating JSON and checked against the visible headline, with the language filter set to "all". Glassdoor shows two counts per view: the total number of reviews behind the rating, and a smaller "insgesamt" count in the headline (a recent window). Both are given below.

| Metric | Global | Germany | Munich | Software Engineers (global) | Software Engineers (Germany) |
|---|---|---|---|---|---|
| **Overall** | 3.9 (1,746 reviews; headline 314) | 4.1 (352; headline 210) | 3.9 (76; headline 29) | **2.8** (38; headline 8) | 4.1 (14; headline 5) |
| **WLB** | 3.9 | 4.2 | 4.2 | 3.2 | 4.1 |
| **Culture & Values** | 3.7 | 4.0 | 3.8 | 2.4 | 4.0 |
| **Comp & Benefits** | 3.7 | 4.1 | 3.5 | 2.7 | 4.0 |
| **Career Opportunities** | 3.4 | 3.6 | 3.0 | 2.6 | 3.8 |
| **Diversity & Inclusion** | 3.8 | 4.0 | 3.5 | 3.3 | 4.1 |
| **Senior Management** | 3.3 | 3.6 | 2.9 | 2.9 | 3.8 |
| **% Recommend** | 74% | 87% | 78% | 42% | 99% (5 recent reviews, unreliable) |
| **CEO Approval** (Andreas Pecher) | 74% | 89% | 70% | 7% | n/a |
| **Business Outlook** | 60% positive | 63% positive | 38% positive | 9% positive | 14% positive |

Notes:
- The Germany and Munich figures rest on enough reviews to be usable. Both Software Engineer views (8 and 5 recent reviews) are **directional only**. The global SWE view mixes Bangalore, Lisbon and Berlin raters. Glassdoor ignored a "Software Developer" filter and returned the same data.
- The Munich SEO text on the page says "3,5 von 5", while the visible headline and the rating JSON both say 3.9. 3.9 is used here.
- Business outlook is weak in every view (38% in Munich, 9-14% among software engineers). This matches the 2026 cost programme.
- Indeed (via search): 3.7 from 803 reviews, WLB 3.6.

### Kununu

Slug: `carl-zeiss` (curl returned no rating fields, so the page was read through CDP).

- **Overall score:** 4.1 / 5.0 (industry average for Forschung/Entwicklung: 3.6)
- **Recommendation rate (Weiterempfehlung):** 85% over the last 2 years (83% shown on the reviews tab)
- **Total reviews:** 2,750 (employee reviews: 1,978)
- **Factor groups:** Karriere & Gehalt 4.2, Unternehmenskultur 4.0, Arbeitsumgebung 4.2, Vielfalt 4.3
- **Most confirmed benefits:** flexible working hours (73%), company pension (61%), canteen (60%)
- **Kununu Top Company:** YES (Top Company 2027)

Separate profile `carl-zeiss-digital-innovation`: 4.3 / 5.0, 93% recommend, 168 reviews (101 employee reviews), industry "Beratung/Consulting".

### Blind / Teamblind

"Carl Zeiss AG" on teamblind.com (read via CDP): **3.9 / 5 from 15 reviews**. Career Growth 3.6, **Work Life Balance 4.8**, Compensation/Benefits 3.0, Company Culture 3.6, Management 3.7. The sample is too small to rely on, but the pattern (excellent WLB, weak pay) matches Glassdoor and Kununu.

### Review Themes (2024-2026)

**Positives:**
- **Work-life balance and flexibility.** This is the most consistent theme on every platform: Glassdoor WLB 4.2 in Germany and Munich, Blind WLB 4.8, Kununu "Flexible Arbeitszeiten" 73%. Typical comments: "Good Work life balance and flexible", "kein Stress. Sehr gute und einladende Umgebung" (Software Engineer, Braunschweig, Jan 2025), "Work-life-Balance super" (IT, Jena, Sep 2026).
- **Stability and foundation ownership.** "Stable, secure job, smart people to work with" (Senior UX Designer, Munich, May 2026). Kununu reviewers repeatedly cite the "besondere Eigentümerstruktur".
- **Collective-agreement pay and benefits in Germany.** "Tarif IGM" (Meditec R&D, Aug 2026). "Weiterbildung und Gehalt ist der große Pluspunkt des Konzerns" (IT, Jena, Sep 2026). "Ab nächsten Monat auch 35 Std. Woche" (GOM Braunschweig, Sep 2026).
- **Interesting high-tech work, especially at SMT.** "An einem der beeindruckensten Projekte der Menschheitsgeschichte beteiligt" (SMT R&D, Aug 2026).
- **Friendly colleagues** within teams.

**Negatives:**
- **Slow, hierarchical corporate processes.** "Slow process, slow decisions making, little room for career growth" (Munich, May 2026). "Großer Konzern, langsame Prozesse" (SWE Berlin, Aug 2026). "Hierarchically oriented and political philosophy" (Munich, Jun 2026). This is typical large-company bureaucracy.
- **Pay for software engineers below tech-market level.** "pay not high enough for software engineers" (SWE Berlin, Aug 2025). "Gehalt könnte besser sein" (SWE Berlin, Aug 2026). Blind Comp 3.0, Glassdoor SWE Comp 2.7. AT (above-tariff) pay is described as arbitrary: "Bezahlung geht nach der Nase... AT Regelungen sollten standardisiert werden" (Kununu, Oct 2026).
- **Morale hit from the 2026 job-cut announcements.** "Noch ganz gut, wird mit dem angedrohten Stellenabbau schlechter ... Seitens des obersten Managements unterirdisch, siehe Thema Stellenabbau" (Meditec R&D, Aug 2026, titled "Ein Stiftungsunternehmen im Sinkflug"). "Verlagerung nach Asien (Indien)".
- **Weak upper management and communication in some areas, notably IT.** "Die Vorgesetzten erinnern sich teilweise nicht an Absprachen. Also wenn es die IT sein soll, dann alles gut festhalten ... Kommunikation findet nicht auf geregelten Bahnen statt sondern oft nur auf Zuruf" (IT, Oberkochen, Oct 2026). "Direkter Vorgesetzter super, je näher am obersten Management, desto gruseliger" (Meditec, Aug 2026). Senior Management is rated 2.9 in Munich.
- **Isolated toxic-team reports.** "Micromanagement, toxic attitude, fluctuation" (Software Developer, under 1 year, Jun 2026). Munich test automation engineer: "Work load is stressful and QA department team leads are not evaluating the effort" (Dec 2025).
- **Older employees sidelined** (SMT logistics, Oct 2026: "Ältere Mitarbeiter auf dem Abstellgleis").

Overlap with hard red flags: layoffs (yes, announced and negotiated), communication breakdown (localised, IT), WLB issues (no).

### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | **Low, localised.** One former software developer (Jun 2026): "Micromanagement, toxic attitude". No systemic pattern. Upper management is criticised for its handling of the job-cut communication, not for abuse |
| 24/7 Work Expectation | **None found.** WLB is the strongest category everywhere. 35-hour IG Metall week at tariff sites |
| Internal Surveillance | **None found.** Monitoring tools would require co-determination by the works council (§87(1) Nr. 6 BetrVG) |
| Fear-driven Management | **Low to moderate, rising.** The 2026 job-cut programmes create uncertainty: "wird mit dem angedrohten Stellenabbau schlechter werden, wenn es um den eigenen Arbeitsplatz geht" |
| Communication Breakdown | **Moderate, localised.** IT Oberkochen: "Kommunikation findet nicht auf geregelten Bahnen statt". Meditec: "Kommunikation verbessern und ehrlich sein, alles andere demotiviert". Working student (Sep 2026): "often unclear who to contact or escalate issues to" |
| Unpaid Overtime | **None found.** Flexitime and tariff working-time rules apply |
| Silent Firings | **None found.** Cuts are being handled through announced programmes negotiated with employee representatives |
| Work-Life Balance issues | **Low.** Isolated workload complaint (Munich QA, Dec 2025). Otherwise consistently praised |

**Risk level: LOW.** The negatives fit pattern (b), corporate bureaucracy and slow decision-making in a large German industrial group, plus some localised (c) team-level problems in IT and QA. Nothing points to systemic toxicity.

---

## Section 5: Compensation

### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| Glassdoor.de (Germany, via CDP) | Senior Software Engineer | €68.5-88.5K (avg €80K) | 0 | ~€4K (range €2-16.5K) | ~€84K | 15 |
| Glassdoor.de (Germany, via CDP) | Software Architect | €82.5-90K (avg €86.5K) | 0 | ~€9K | ~€95.5K | 17 |
| Glassdoor.de (Germany, via CDP) | Software Engineer | €60.9-81K (avg €70K) | 0 | ~€4K | ~€74K | 70 |
| Glassdoor.de (Germany, via CDP) | Software Developer | €63-80K (avg €67.7K) | 0 | ~€4.5K | ~€72K | 71 |
| Glassdoor.de (Germany, via CDP) | Softwareentwickler | €50-69.5K (avg €61.5K) | 0 | ~€3.6K | ~€65K | 70 |
| levels.fyi (Germany, via CDP) | Software Engineer (all levels) | n/a | €0 | ~€2.3K | median **€68.7K**, range €60.2-103K | 40 |
| levels.fyi (Munich, via CDP) | Software Engineer | €66.3K avg | €0 | €2.2K | €68.5K avg. Latest Munich entries: €114K (Jul 2026), €71K (Apr 2026), €78K (Dec 2025), €60K | 40 (company-wide) |
| levels.fyi (Germany) | Software Engineering Manager | n/a | €0 | n/a | median ~€89K (via search snippet) | n/a |

levels.fyi publishes no Senior/Lead/Principal level figures for ZEISS ("€ --"), and no Munich 75th or 90th percentile is available. The highest Germany data point is €103K and the highest Munich entry is €114K.

Benefits that add to cash pay: an annual bonus tied to business results ("Beteiligung am Unternehmensergebnis", "Jahresprämie"), an employer-funded company pension, and IG Metall tariff structures (35-hour week at tariff sites).

### Equity / Stock

**None.** Carl Zeiss AG is foundation-owned and not listed, so there are no RSUs or stock options. Carl Zeiss Meditec AG is listed, but no broad employee equity or ESPP programme was found. Upside comes only from the annual profit-sharing bonus, which will likely shrink while the cost programme runs.

### Verdict

**BELOW.** Large, profitable Munich corporations typically pay senior engineers €90-110K base plus bonus. ZEISS's Senior Software Engineer band averages €80K base (~€84K total). Even Software Architect averages only ~€95K total, and the company-wide median is under €70K. As in other IG Metall-bound groups, senior engineers are paid außertariflich (AT), and reviewers describe AT pay as non-standardised and dependent on the manager. The collective agreement brings defined hours and a pay floor but not a high ceiling.

---

## Section 6: AI/ML & Tech Stack

### AI Strategy

- **Group AI programme.** ZDP runs an "Empowerment with AI" programme that turns "the ZEISS AI strategy into tangible measures to drive AI adoption (e.g., AI fluency for all, domain-based training)". A Munich Change Manager posting for it is fixed-term until November 2027. This is AI adoption and change work, not platform engineering.
- **Applied AI in products.**
  - Medical: AI-powered applications in the ophthalmology data ecosystem.
  - Microscopy: an automated ML and computer-vision toolset (the Munich ML internship asks for production Python and Docker).
  - SMT: "operational AI applications" built on a data-governance programme. A Head of Data Strategy leads 25 people in MDM, data quality and "Governance/Data as Code".
- **Corporate Research.**
  - The ZEISS Innovation Hub @ KIT (Eggenstein) works on vision foundation models, quantization-aware training and edge deployment.
  - Research Scientist roles cover "AI-Driven Transformation of Optical System Development" (Oberkochen/Ulm) and "Next-Generation Computing Architectures" for AI training and inference hardware (fixed-term, 2 years).
- **AI infrastructure.** Corporate IT operates "three productive cloud systems" including GPU infrastructure (Lead DevOps posting, removed Mar 2026). An "SW architect AI Infrastructure" role in Munich appears on aggregators, but its details could not be retrieved.

Overall, this is genuine applied AI spread across many business units, plus a group-level AI-adoption programme. There is no central ML platform or MLOps product organisation comparable to a software company's.

### Tech Stack

Derived from: current and recent job postings (LinkedIn voyager API via CDP, BuiltIn, aggregator snippets), the ZEISS GitHub organisations (GitHub API), and the ZDI and PiWeb repositories.

| Category | Technologies |
|---|---|
| **Primary language(s)** | C# / .NET (.NET 10, ASP.NET Core in a Carl Zeiss AG Aalen posting; 13 of 40 ZDI repos; PiWeb SDKs). C++17/20 (medical robotics Munich, metrology, microscopy). Python (data engineering, ML, test automation, research). Go and TypeScript in the central `ZEISS` GitHub org (114 repos: Go 28, TypeScript 11, Python 7, C++ 6, with recently active Go Fiber libraries such as `fiber-authz`, `fiber-htmx`). Java at ZDI. PLC languages (Beckhoff TwinCAT, Siemens TIA) in SMT manufacturing automation |
| **AI/ML** | PyTorch, vision foundation models, quantization-aware training, edge deployment, synthetic data generation, computer vision. GPU infrastructure in Corporate IT. GitHub Copilot sample apps at ZDI |
| **Cloud** | Microsoft Azure (dominant: AKS, Azure Container Apps, Azure DevOps). AWS mentioned as an alternative in Data Engineer postings |
| **Infrastructure** | Kubernetes, Docker, Terraform, Ansible, Azure DevOps Pipelines, GitHub Actions, Jenkins. Prometheus, Grafana, Loki, Promtail. Embedded Linux, Yocto, real-time Linux |
| **Data** | Python, SQL, PySpark, Bash. Postgres, Redis. MDM, data governance, digital twins of manufacturing processes |
| **Other** | Angular (Munich SWE interview question), UML/SysML, MISRA C/C++, IEC 62304 Class C. ServiceNow (several Senior Application Specialist and Architect roles). Python/Django or Go for REST microservices in Corporate IT |

**Summary:** Polyglot. Device and product software is centred on C#/.NET and C++. Python is used in data engineering, ML and research. A central platform team works in Go and TypeScript. The cloud is Azure with Kubernetes, and data engineering runs on PySpark and SQL. The work is applied production engineering spread across business units (much of it embedded and regulated medical or industrial software), plus applied AI and research in Corporate Research.

---

## Section 7: Language

The evidence is mixed and depends on the unit:
- **English only:** Lead DevOps Engineer (Corporate IT), Research Scientist Next-Generation Computing ("Business-fluent English is required"), Head of Data Strategy ("German language skills are advantageous"), and the Munich medical robotics C++ role ("Fluency in English").
- **German required:** SDET Spectroscopy, Jena ("Gute Deutsch- und Englischkenntnisse"). Data Management Architect SMT ("sicher auf Deutsch und Englisch"). Change Manager ZDP Munich ("Business fluent German and English"). Senior Software Developer, Medical Munich ("German at least B1 Level"). Kununu company profile: "je nach Stelle gute Deutsch- und Englischkenntnisse".
- A Glassdoor candidate (Oberkochen, Dec 2024) was interviewed entirely in English without notice, which shows that English-speaking teams exist.
- Reviews and internal culture are predominantly German. More than half of the workforce is in Germany, mostly in Oberkochen, Jena and Aalen.

**Verdict:** CONDITIONAL. English-only engineering roles exist (Corporate IT, Corporate Research, some Medical Technology), but many postings, including ZDP Munich ones, require business-fluent German. Check each posting.

---

## Section 8: Stability

### Financial Position

- **FY2024/25:** revenue €11.896bn (+9%), EBIT €1.552bn (13%), equity €8.78bn (48% equity ratio). Net liquidity was **-€263M** (slightly net debt) per the annual report key-figure table. Net income is not given in the press release.
- **H1 2025/26 (to 31 Mar 2026):** revenue €5.841bn (+1%), EBIT €955M (+€33M), equity €9.5bn (51%). Growth comes only from SMT (+6%). Medical Technology fell 7% (-1% adjusted), Industrial Quality & Research fell 3%, and Consumer Markets grew 1%.
- **Outlook:** management "must prepare for further revenue decline in the direct-to-market segments". CEO Pecher: "We are acting from a position of strength before the circumstances force us to act."
- **Carl Zeiss Meditec (listed subsidiary):**
  - H1 2025/26 revenue €991M (-5.7%). EBITA margin 3.9%, against 10.8% a year earlier.
  - Full-year guidance is €2.15-2.20bn.
  - Target: more than €200M in annual earnings improvement by FY2028/29, with up to €150M in one-off costs.
- **Ownership:** the Carl-Zeiss-Stiftung structure rules out a PE exit or takeover risk, and the group is solidly profitable. The trend is weakening outside semiconductors.

Financial runway modelling is not applicable: ZEISS is profitable and not VC-backed.

### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| Summer 2025 | Göttingen site (microscopy) reduction | About 1/3 of ~400 jobs by 2030; ~20 already gone | Some production may move abroad (Eurofound restructuring database) |
| Date UNVERIFIED (2025-2026) | ZEISS Microscopy "Blueprint for the Future" structural measures | 215 jobs affected in Germany (130 cuts, ~150 relocations) | Reported by instrumentbusinessoutlook.com (page returned 403; known only from the search snippet) |
| 12 May 2026 | Carl Zeiss Meditec "ProfitUp" | Up to 1,000 jobs worldwide over 3 years, later reported as 600-700 (Aug 2026) | Medical Technology. Germany share still open. Negotiations with employee representatives under way. Production build-up in China and a new site in India. IG Metall Jena-Saalfeld expressed concern |
| 9 Jun 2026 | ZEISS Group cost programme | "Several hundred million euros" in annual savings over 3 years. Job cuts expected, no number given | Covers segments, corporate administration and country organisations. Measures are to be "developed ... with the Executive Board, management, and employee representatives". The Meditec programme is separate |

### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | **YES** | Employee representatives sit on the Carl Zeiss AG Supervisory Board (Heike Madan, Torsten Martin, Uwe Frey named in the FY2024/25 Supervisory Board report). The board has a **Vermittlungsausschuss**, a committee that exists only under parity co-determination (MitbestG §27(3)), which fits a group with more than 22,000 German employees. Both 2026 job-cut programmes are being negotiated with "Arbeitnehmervertretungen und zuständigen Gremien" (company spokesperson, May 2026) |
| Collective agreement | **Sector (Flächentarif), IG Metall** metal and electrical industry | August 2021 Eckpunktepapier between ZEISS and IG Metall Baden-Württemberg to bring all German employees under the regional metal and electrical Flächentarifverträge (chemie.de). Kununu: "Tarif IGM" (Meditec Jena, Aug 2026), "ab nächsten Monat auch 35 Std. Woche" (GOM Braunschweig, Sep 2026), "AT Regelungen sollten standardisiert werden" (Oct 2026). Senior engineers are typically paid AT |
| European works council (multinationals) | **UNVERIFIED** | No source found |
| Conflict signals | None found | No union-busting or blocked-election reports. IG Metall Jena-Saalfeld/Gera publicly expressed concern about the Meditec cuts, which is normal union engagement |

**Verdict:** CAUTION. The works council, parity co-determination and the IG Metall tariff are strong structural protections: any cuts will be announced, negotiated and covered by a social plan, not done through silent push-outs. Foundation ownership adds long-term stability. However, two separate job-reduction programmes are live in 2026, the outlook for three of four segments is declining, and hiring in Munich is close to zero. The caution is about the next 12-24 months, not about the company's survival.

---

## Section 9: Regulated Industry

- **Medical Technology (including Munich medical robotics):** CE/MDR, FDA, IEC 62304 (Class C named in the robotics posting), MISRA C/C++, "documentation to support ... regulatory submissions", safety-critical real-time software. Heavy documentation overhead and slow release cycles.
- **Semiconductor Manufacturing Technology:** export controls (dual-use, ASML/EUV supply chain). Functional safety roles exist (Functional Safety Engineer, PLC).
- **Defence-adjacent:** one Munich posting mentions software for connecting military command capabilities.
- **ZDP, Corporate IT and Corporate Research:** low regulatory burden. These are internal tools and platforms.

**Verdict:** CAUTION. The burden is high in Medical Technology, which hosts one of the two Munich engineering groups, and low in ZDP and Corporate IT.

---

## Section 10: On-Call

None of the postings reviewed mention on-call or Rufbereitschaft. Corporate IT's Lead DevOps role covers "the operation and maintenance of three productive cloud systems", and Workload Automation roles deliver "global and business-critical ... services (EMEA, APAC, AMER) within agreed SLAs". Both suggest some operational duty in Corporate IT. Device and product R&D teams (medical robotics, metrology software) and Corporate Research carry no on-call by the nature of the work. Where on-call exists, the works council co-determines it (§87(1) Nr. 2-3 BetrVG) and the tariff regulates it.

**Verdict:** CAUTION (team-dependent). Product R&D and research teams: very likely none. Corporate IT and cloud operations: possible, so ask during interviews.

---

## Section 11: Interview Process

Based on Glassdoor (glassdoor.de, via CDP).

| Metric | Value |
|---|---|
| Difficulty | 2.82 / 5 overall (456 interviews). 3.2 / 5 for Software Engineer (15 interviews) |
| Positive experience | 57% overall (22% negative). Software Engineer: 53% positive and 33% negative in the visible stats, but 67% positive per the Glassdoor FAQ text |
| Average duration | ~39-50 days overall. ~38 days for Software Engineer (6 reports) |
| Rounds | 2-3 typical |

**Typical process for software roles:**
1. Application, mostly online (64%) or via a recruiter (10%).
2. A video interview with technical questions, often with a panel of three.
3. A take-home code challenge with 1-2 days to complete (Softwareentwickler, Munich, Jan 2025, offer accepted: "Video-Interview mit technischen Fragen und dann eine Code Challenge").
4. A further technical or team interview.

**Sample questions:**
- "Worauf ist beim Design einer API zu achten?"
- "Was sind Microservices und was sind ihre Vorteile"
- "Welche Angular Lifecycle Hooks gibt es?"
- Scenario-based service and operations questions (Bangalore, Oct 2026).

**Complaints:**
- Slow or absent feedback (Lisbon, Feb 2024).
- Interviewers with cameras off.
- Interview language switched to English without notice.
- A two-year fixed term disclosed only at the end of the interview (Oberkochen, Dec 2024).

The process is **experience- and fundamentals-focused**, with a practical take-home. It is not LeetCode-heavy.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | **FAIL.** Optics, semiconductor-optics and medical-device manufacturer. Software supports the hardware |
| Not consulting | **SPLIT.** ZEISS Digital Innovation (Munich, Kistlerhofstraße) is a consultancy and is excluded. ZDP, Medical Technology and Corporate Research are internal or product engineering and pass |
| Profitable | **PASS.** EBIT €1.55bn (13%) in FY2024/25. H1 2025/26 EBIT up |
| Employee count | 46,622 globally, more than 22,000 in Germany |
| English-speaking | **CONDITIONAL.** English-only roles exist, but many postings (including ZDP Munich) require business-fluent German |
| Local entity + engineering contracts | **PASS with CAUTION.** Direct contracts via Carl Zeiss AG (HRB 501555 Ulm) and other German entities. No entity has its seat in Munich. Several new roles are fixed-term (2 years) |
| Location / work model | Kistlerhofstraße 75, Obersendling (U3 Aidenbachstraße ~330 m). Hybrid 40-60% at ZDP. Some Munich roles are in-office. No fully remote engineering roles |
| Glassdoor | 3.9 global, **4.1 Germany**, 3.9 Munich (WLB 4.2). Software Engineers 2.8 globally (8 recent reviews, directional only). Business outlook weak (38% in Munich) |
| Kununu | **4.1, 85% recommend**, 1,978 employee reviews, **Top Company 2027** |
| Salary | **BELOW.** Senior Software Engineer avg €80K base (~€84K total, 15 data points). levels.fyi Germany median €68.7K. No equity |
| AI/ML content | Applied AI spread across units (vision foundation models, edge ML, data governance for AI), a group AI-adoption programme, and AI-hardware research. No central ML platform organisation |
| Computer-language/Tech-stack | Polyglot: C#/.NET and C++ for device and product software, Python for data, ML and research, Go and TypeScript in a central platform team. Azure and Kubernetes |
| No on-call | **CAUTION.** None in product R&D or research. Possible in Corporate IT and cloud operations |
| WLB / Stability | WLB **strong** on every platform (Glassdoor DE 4.2, Blind 4.8). Stability **CAUTION**: group cost programme with job cuts (Jun 2026), Meditec ProfitUp (600-1,000 jobs), declining direct-to-market segments |
| Works council / collective agreement | **YES / IG Metall Flächentarif**, with parity co-determination on the Supervisory Board. Senior pay is AT |
| Regulated industry | **CAUTION** for Medical Technology (IEC 62304 Class C, MDR). Low for ZDP and Corporate IT |
| Review themes | Positive: WLB, stability, tariff benefits, interesting technology. Negative: slow and hierarchical processes, below-market software pay, upper-management communication about job cuts |
| Munich hiring activity | **Very low.** 3 ZEISS postings on LinkedIn in Munich (none in engineering). Recent Munich software postings (medical robotics C++, Lead DevOps) were removed in Feb-Mar 2026 |
| Fixed-term contracts | **CAUTION.** Several current postings are fixed-term (2 years, or until Nov 2027) |

---

## Section 13: Verdict

**Monitor. Do not actively pursue now.**

**Strengths:**
- ZEISS is one of the most stable employers in Germany: foundation-owned, solidly profitable (€1.55bn EBIT), with no exit or takeover risk.
- It has a works council, parity co-determination and the IG Metall tariff.
- Work-life balance is excellent and consistent: Glassdoor Germany 4.1 with WLB 4.2, Kununu 4.1 with 85% recommending and Top Company 2027, Blind WLB 4.8.
- The work is technically deep (EUV optics, medical robotics, computer vision), and applied AI is growing across units.
- The interview process is practical: technical conversation plus a take-home task, not LeetCode.

**Hard blockers:**

1. **Not software-centric.** ZEISS earns its money from optics and devices. Software engineers serve hardware roadmaps (often C++ and C# embedded or device software) or internal digital transformation. The engineering culture and career paths follow an industrial group, not a software company.
2. **The main software office in Munich is a consultancy.** ZEISS Digital Innovation at Kistlerhofstraße 75 builds custom software for external clients with a "consultants" workforce, and Kununu classifies it as consulting. It fails the no-consulting criterion. Its own headcount figure also fell from "600+" to "over 300" without public explanation.
3. **No relevant Munich vacancies, and a hiring climate shaped by cuts.** Since the 9 June 2026 group cost programme and the Meditec ProfitUp programme, ZEISS has only 3 postings in Munich, none in engineering. The last Munich software postings (medical robotics C++, Corporate IT Lead DevOps) were removed in February-March 2026.

**Secondary concerns:**
- **Compensation is below the Munich large-corporation bracket.** Senior Software Engineer averages €80K base (~€84K total). The levels.fyi median is €68.7K with no equity. AT pay is described as non-standardised.
- **Many new roles are fixed-term** (2 years, or until November 2027). One candidate learned of the fixed term only at the end of the interview.
- **German is often required**, including on ZDP Munich postings.
- **Medical Technology roles carry IEC 62304 Class C and MDR overhead**, and that segment is the one being cut (ProfitUp).
- **Business outlook ratings are low** (38% positive in Munich, 9-14% among software engineers), and reviewers report that morale is deteriorating because of the announced cuts.
- **Software Engineer Glassdoor scores are weak** (2.8 globally) and **Munich Senior Management is rated 2.9**, although both samples are small.

**Recommendation:** Do not apply now. Re-check in 6-12 months, once the group cost programme's measures are defined and the Meditec cuts are complete. A ZEISS application only makes sense for a **permanent** role in **ZEISS Digital Partners, Corporate IT or Corporate Research** (not ZEISS Digital Innovation, not fixed-term) where the posting is in English or treats German as optional. In that case, verify during the process:
- the AT salary band (aim above €95K base) and how the annual bonus is calculated;
- whether the unit is in scope of the June 2026 cost programme;
- the exact Munich office and hybrid quota;
- whether the team carries any on-call duty for production cloud systems.

---

## Section 14: Sources

- [ZEISS - Press release: FY2024/25 results (18 Dec 2025)](https://www.zeiss.com/corporate/en/about-zeiss/present/newsroom/press-releases/2025/end-of-year.html)
- [ZEISS - Press release: Half-year figures 2025/26 and cost programme (9 Jun 2026)](https://www.zeiss.com/corporate/en/about-zeiss/present/newsroom/press-releases/2026/half-year-figures.html)
- [ZEISS - Facts & figures](https://www.zeiss.com/corporate/en/about-zeiss/present/facts-figures.html)
- [ZEISS Annual Report 2024/25 key figures (mamcache)](https://mamcache.zeiss.com/019b3022-95d0-7af1-8c34-e13a6651715d.original.html)
- [ZEISS Annual Report - Bericht des Aufsichtsrats](https://www.zeiss.com/geschaeftsbericht/bericht-des-aufsichtsrats.html)
- [Carl Zeiss Meditec - Half-year communication 2025/26](https://www.zeiss.com/meditec-ag/de/presse-und-aktuelles/pressemitteilungen/2026/halbjahreskommunikation-geschaeftsjahr-2025-26.html)
- [EQS News - Carl Zeiss Meditec lower H1 earnings, package of measures planned](https://live.deutsche-boerse.com/news/EQS-News-Carl-Zeiss-Meditec-reports-lower-earnings-in-the-first-half-of-2025-26--Comprehensive-package-of-measures-planned-c1131607-b945-442e-b2b2-15831f2c8b3b)
- [Wochenblatt Reporter - Stellenabbau bei Zeiss in Oberkochen: 1000 Jobs weltweit auf dem Prüfstand (12 May 2026)](https://www.wochenblatt-reporter.de/c-wirtschaft-handel/stellenabbau-bei-zeiss-in-oberkochen-1000-jobs-weltweit-auf-dem-pruefstand_a773272)
- [MedTech Dive - Carl Zeiss says restructuring could affect up to 1,000 jobs](https://www.medtechdive.com/news/carl-zeiss-says-restructuring-could-affect-up-to-1000-jobs/820375/)
- [Kettner Edelmetalle - Zeiss-Schock in Jena: bis zu 700 Stellen (17 Aug 2026)](https://www.kettner-edelmetalle.de/news/zeiss-schock-in-jena-bis-zu-700-stellen-fallen-weg-17-08-2026)
- [jura.cc - Stellenabbau bei der Carl Zeiss AG](https://www.jura.cc/?p=32873)
- [Schwäbische - Traditionsunternehmen will massiv sparen](https://www.schwaebische.de/wirtschaft/hunderte-stellen-betroffen-traditionsunternehmen-will-massiv-sparen-4569800)
- [Eurofound restructuring event - Carl Zeiss Göttingen](https://restructuringeventsprod.azurewebsites.net/restructuring-events/detail/203959)
- [Instrument Business Outlook - Blueprint for the Future of the ZEISS Microscopy Business Group (403, snippet only)](https://instrumentbusinessoutlook.com/?p=155028)
- [EW Intelligence - ZEISS Group launches cost-reduction program and job cuts](https://www.ewintelligence.com/financial-results/zeiss-group-launches-cost-reduction-program-and-job-cuts-after-mixed-h1-results/121583.article)
- [EW Intelligence - ZEISS establishes competence center in Munich (2016)](https://www.ewintelligence.com/zeiss-has-established-a-new-competence-center-in-munich-as-/57214.article)
- [chemie.de - Zeiss will künftig Tarifbindung für alle Beschäftigten (12 Aug 2021)](https://www.chemie.de/news/1172315/zeiss-will-kuenftig-tarifbindung-fuer-alle-beschaeftigten.html)
- [chemie.de - CEO-Wechsel bei ZEISS in 2025](https://www.chemie.de/news/1184556/ceo-wechsel-bei-zeiss-in-2025.html)
- [NorthData - Carl Zeiss AG, Oberkochen (via CDP)](https://www.northdata.com/Carl+Zeiss+AG,+Oberkochen)
- [NorthData - Carl Zeiss Digital Innovation GmbH, Dresden (via CDP)](https://www.northdata.com/Carl+Zeiss+Digital+Innovation+GmbH,+Dresden)
- [ZEISS Digital Innovation - About us](https://www.zeiss.com/digital-innovation/about-us.html)
- [ZEISS Digital Innovation - Legal information](https://www.zeiss.com/digital-innovation/imprint/publisher.html)
- [orte.muenchen.de - Carl Zeiss Digital Innovation GmbH, Kistlerhofstraße 75](https://orte.muenchen.de/30991.html)
- [OpenStreetMap Nominatim - Kistlerhofstraße 75 geocode](https://nominatim.openstreetmap.org/search?q=Kistlerhofstra%C3%9Fe+75,+81379+M%C3%BCnchen&format=json&addressdetails=1)
- [Overpass API - transit stops within 700 m](https://overpass-api.de/api/interpreter)
- [Glassdoor - ZEISS Group reviews, global (via CDP)](https://www.glassdoor.de/Bewertungen/ZEISS-Group-Bewertungen-E9052.htm)
- [Glassdoor - ZEISS Group reviews, Germany (via CDP)](https://www.glassdoor.de/Bewertungen/ZEISS-Group-Deutschland-Bewertungen-EI_IE9052.0,11_IL.12,23_IN96.htm)
- [Glassdoor - ZEISS Group reviews, München (via CDP)](https://www.glassdoor.de/Bewertungen/ZEISS-Group-M%C3%BCnchen-Bewertungen-EI_IE9052.0,11_IL.12,19_IC4990924.htm)
- [Glassdoor - ZEISS Group reviews, Software Engineer (via CDP)](https://www.glassdoor.de/Bewertungen/ZEISS-Group-Bewertungen-E9052.htm?filter.jobTitleFTS=Software+Engineer)
- [Glassdoor - ZEISS Group interviews (via CDP)](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/ZEISS-Group-Fragen-im-Vorstellungsgespr%C3%A4ch-E9052.htm)
- [Glassdoor - ZEISS Senior Software Engineer salaries (via CDP)](https://www.glassdoor.de/Gehalt/ZEISS-Group-Senior-Software-Engineer-Geh%C3%A4lter-E9052_D_KO12,36.htm)
- [Glassdoor - ZEISS Software Engineer salaries (via CDP)](https://www.glassdoor.de/Gehalt/ZEISS-Group-Software-Engineer-Geh%C3%A4lter-E9052_D_KO12,29.htm)
- [Glassdoor - ZEISS Software Architect salaries (via CDP)](https://www.glassdoor.de/Gehalt/ZEISS-Group-Software-Architect-Geh%C3%A4lter-E9052_D_KO12,30.htm)
- [Kununu - ZEISS (carl-zeiss, via CDP)](https://www.kununu.com/de/carl-zeiss)
- [Kununu - ZEISS reviews (via CDP)](https://www.kununu.com/de/carl-zeiss/kommentare)
- [Kununu - ZEISS Digital Innovation (via CDP)](https://www.kununu.com/de/carl-zeiss-digital-innovation)
- [Teamblind - Carl Zeiss AG reviews (via CDP)](https://www.teamblind.com/company/Carl-Zeiss-AG/reviews)
- [levels.fyi - Zeiss Group Software Engineer, Germany (via CDP)](https://www.levels.fyi/companies/zeiss-group/salaries/software-engineer/locations/germany)
- [levels.fyi - Zeiss Group Software Engineer, Munich Metro Region (via CDP)](https://www.levels.fyi/companies/zeiss-group/salaries/software-engineer/locations/munich-metro-region)
- [levels.fyi - Zeiss Group Software Engineering Manager](https://www.levels.fyi/companies/zeiss-group/salaries/software-engineering-manager)
- [ZEISS Vision Care - Great Place to Work certification 2024](https://www.zeiss.com/vision-care/en/newsroom/news/2024/great-place-to-work-certification.html)
- [Great Place to Work - Carl Zeiss Vision profile](https://www.greatplacetowork.com/certified-company/102036589)
- [Indeed - ZEISS Group reviews](https://de.indeed.com/cmp/Zeiss-Group/reviews)
- [BuiltIn - ZEISS Lead DevOps Engineer, Corporate IT (removed Mar 2026)](https://builtin.com/job/lead-devops-engineer/7204073)
- [BuiltIn - ZEISS Software Developer C++ Medical Robotics, Munich (removed Feb 2026)](https://builtin.com/job/software-developer-c-f-m-x/8242799)
- [BuiltIn - ZEISS Senior Software Developer as Tech Lead, Munich (removed Jun 2025)](https://builtin.com/job/senior-software-developer-fmx/4177736)
- [LinkedIn - ZEISS postings in Germany and Munich (voyager API via CDP): SDET Spectroscopy Jena, Internship AI & ML (KIT), Research Scientist AI-Driven Optical Design, Data Management Architect SMT, Head of Data Strategy SMT, Change Manager Empowerment with AI (ZDP Munich), Research Scientist Next-Gen Computing](https://www.linkedin.com/jobs/search/?keywords=ZEISS&location=Germany)
- [GitHub - ZEISS organisation](https://github.com/ZEISS)
- [GitHub - zeiss-digital-innovation organisation](https://github.com/zeiss-digital-innovation)
- [GitHub - ZEISS-PiWeb organisation](https://github.com/ZEISS-PiWeb)
- [GitHub - zeiss-microscopy organisation](https://github.com/zeiss-microscopy)
