# Hoffmann Group - Full Research Report

_Researched: 2026-11-12_

> **Critical Disqualifiers**
> 1. **Not software-centric:** Hoffmann Group is a B2B **wholesaler/distributor** of cutting tools, workshop equipment and PPE (registered purpose: "Handel mit und Vertrieb von Werkzeugen und Werkstatteinrichtungen aller Art"). Software is an internal and customer-service function (eShop, ToolScout, data platform), not the product. Of ~70 open roles in November 2026, three are software engineering roles.
> 2. **Language:** two of the three current senior engineering postings require German at "sehr gut" or "verhandlungssicher" level. Only the Senior Platform Engineer role is English-first ("Deutschkenntnisse sind wünschenswert").
> 3. **Engineering model:** several engineering postings describe the senior role mainly as *steering external development partners* ("Technische Steuerung externer Entwicklungspartner", "Fachliche Anleitung und Steuerung externer Entwickler"). The customer platform is built largely by an outside agency (jambit).
>
> The full report follows for completeness.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 1919 (107 years) |
| Employees | "Mehr als 4.000" in 50+ countries (careers page, Nov 2026); ~1,700 of them in sales (Wirtschaftsforum interview). SFS reports 3,413 FTE for its whole Distribution & Logistics (D&L) segment in 2025 (-6.9% YoY, restated). Revelio Labs estimates ~2,200 for Hoffmann SE alone. |
| Revenue (FY2025) | "Mehr als 1,4 Mrd. Euro" worldwide (Hoffmann careers page). D&L segment, which Hoffmann dominates: CHF 1,347.6M third-party sales (+0.3%). |
| Profitability | D&L EBIT CHF 113.5M (8.5% margin), adjusted CHF 131.0M (9.8%) in 2025. SFS Group net income CHF 220.2M. **PASS** |
| Ownership | Wholly owned subsidiary of **SFS Group AG** (SIX: SFSN, Heerbrugg, Switzerland) since 11 May 2022. Previously family/foundation-owned; the former owners received SFS shares and became significant SFS shareholders. |
| Software-centric | Tool wholesaler and distributor with in-house IT, eCommerce and a small digital-products unit. **FAIL** |

### Key People

| Role | Person | Note |
|---|---|---|
| Vorstand, Chair (Hoffmann SE) | Iso Raunjak | Per Impressum, Nov 2026 |
| Vorstand (Hoffmann SE) | Manfred Rosenberger | Per Impressum |
| Chair of Supervisory Board | Jens Breu | SFS Group CEO |
| Sales & Marketing management | Claudia Lenders | Interviewed by Wirtschaftsforum on strategy |
| Head of Platform & Software Services | Christoph Fuchs | Named in jambit case study |
| Managing Directors, Hoffmann IT & General Services GmbH | Steffen Bertram, Alexander Eckert | NorthData, March 2026 change (Max Killinger and Tobias Buck left the board) |

Glassdoor still lists Martin Reichenecker (CEO at acquisition, who joined the SFS Executive Board in 2022) among the leadership, so its CEO approval scores probably refer to him.

### Ownership History

| Date | Event | Detail |
|---|---|---|
| 1919 | Founded | Munich tool dealer |
| 21 Dec 2021 | Agreement | SFS agrees to acquire 100% of Hoffmann SE; consideration partly in SFS shares (1.4M new + 0.2M existing); price not disclosed; Contorion excluded |
| 11 May 2022 | Completion | Hoffmann becomes the core of SFS's D&L segment |
| 2025 | Integration | Local warehouses consolidated into Hoffmann LogisticCity Nuremberg (>€200M investment) |
| Jan-Mar 2026 | Acquisitions | Partner dealers Gödde, Oltrogge and Hch. Perschmann acquired (~€270M third-party sales, ~450 staff); stake in Jellypipe AG (3D printing) |

### Business Model

Hoffmann is a catalogue and eShop distributor (brand GARANT and third-party brands) of cutting tools, measuring tools, workshop furniture and PPE to manufacturing customers (automotive, mechanical engineering; growth areas shipbuilding, aerospace, energy, defence). Revenue comes from product margin. Digital assets (eShop, ToolScout tool-selection platform, "Connected Manufacturing", Simple System procurement platform, connected measuring/torque tools) support the product sale.

### Software-Centric Assessment - FAIL

- Registered purpose of the parent is holding and leading a group active in "Handel mit und Vertrieb von Werkzeugen und Werkstatteinrichtungen aller Art". The IT subsidiary's purpose is internal IT services for the group.
- The careers page lists ~70 openings in November 2026. Software engineering: Senior Software Engineer (ToolScout), Senior Platform Engineer (data platform), Lead Developer Java (Essen). The rest are sales, logistics, warehouse, SAP support, apprenticeships and finance.
- Two of the three engineering postings define the senior role through steering external developers. The Lead Developer role: "Technische Steuerung externer Entwicklungspartner bei der Umsetzung primär Java-basierter Anwendungen - von der Beauftragung bis zur Abnahme". The ToolScout role: "Fachliche Anleitung und Steuerung externer Entwickler".
- jambit has developed the customer portal (ToolScout, Connected Manufacturing, Workstation Configurator) since 2018, including frontend, backend and architecture.
- Kununu's IT reviews describe the department as "Amt" (government office) and say "Wir sind einfach nicht mehr in den 80gern" (Kununu, Aug 2025, Angestellte/r oder Arbeiter/in, IT, Hoffmann Qualitätswerkzeuge München).

Not consulting: engineers build internal systems, and nothing suggests client billing or consultant titles.

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **Hoffmann SE** | Amtsgericht München HRB 237463 (EUID DED2601V.HRB237463) | Registered: Haberlandstr. 55, 81241 München. Impressum: Bodenseestraße 343, 81249 München | Acquiring and managing holdings; "leitet die Unternehmensgruppe Hoffmann" (tool trade and distribution); part of SFS Group as segment "Distribution & Logistics" |
| **Hoffmann IT & General Services GmbH** | Amtsgericht München HRB 234846 | Haberlandstr. 55, 81241 München | "Erbringung von Dienstleistungen und Beratungsleistungen für die Gesellschaft, mit ihr verbundene Unternehmen und Dritten ... insbesondere in den Bereichen der Informationstechnologie sowie sonstiger zentraler Dienste" |
| **Hoffmann Engineering Services GmbH** | Amtsgericht München HRB 234822 | Haberlandstr. 55, 81241 München | Services around catalogue goods: building the product portfolio, product development, catalogue creation and product-data management for the group and third parties |

The current postings name the actual employer. The Senior Platform Engineer is employed by **Hoffmann SE**, the ToolScout Senior Software Engineer and the Embedded working student by **Hoffmann Engineering Services GmbH**, and the Lead Developer Java (Essen) by **Hoffmann IT & General Services GmbH**. All three are German entities with direct employment contracts, and none uses an EOR. The IT GmbH's purpose confirms IT engineering work, though it serves group-internal IT. It is not a sales shell.

**Verdict:** PASS

---

## Section 3: Office Location

- **Office address:** Postings and the Impressum give **Bodenseestraße 343, 81249 München** (Freiham, Aubing-Lochhausen-Langwied). This is the new headquarters designed by kadawittfeldarchitektur for ~1,250 workplaces near the Freiham district centre (competition 2020, construction from 2022, topping-out Nov 2023). A November 2026 Kununu review refers to "dem neuen Gebäude". The older site at **Haberlandstraße 55, 81241 München (Pasing)** is still the registered address and appears in some postings (the Embedded working student; HR contact for Lead Developer). An older Hoffmann office building also sits at Bodenseestraße 113 (Westkreuz).
- **Nearest public transport (Bodenseestraße 343):** OSM has no house number 343. Interpolating between nos. 319 and 351 on the south side places it next to **S-Bahn Freiham (S8)**, about 80-150 m away. Bus stop "Freiham Bahnhof" (lines 57, N77, N81) is about 160 m away, and "Helmut-Schmidt-Allee" (57, N77) about 340 m. S-Bahn halt Neuaubing is about 1 km away.
- **Nearest public transport (Haberlandstraße 55):** bus stop Heimburgstraße about 160 m away. OSM places a "Westkreuz" station node within about 300 m. S-Bahn Westkreuz is served by S6 and S8.
- **Work model:** hybrid. All current postings offer "Deutschlandweite Home-Working Möglichkeit mit max. 10 Tagen im Monat" (about 2.5 days/week) and "Mobiles Arbeiten im EU/EWR-Ausland & CH mit max. 20 Tagen im Kalenderjahr". Not remote. Flexitime with "Überstundenausgleich durch Freizeit" (overtime compensated with time off).

---

## Section 4: Reviews

**GPTW:** No Great Place to Work Germany certification or list placement found for 2025 or 2026. The search returned only "Hofmann Personal", a different company. **Kununu Top Company:** NO (no badge on the profile).

### Glassdoor

Retrieved via **CDP** (glassdoor.de, employer ID E931366). Sub-scores come from the page's embedded rating data.

| Metric | Global | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | 3.8 (110 ratings; 38 text reviews in the default view) | 3.8 (27 ratings / 22 reviews) | 3.7 (19 ratings / 15 reviews) | No reviews (0 for "Software Engineer", "Developer", "IT") |
| **WLB** | 3.8 | 3.7 | 3.3 | - |
| **Culture & Values** | 3.5 | 3.6 | 3.1 | - |
| **Comp & Benefits** | 3.4 | 3.4 | 3.2 | - |
| **Career Opportunities** | 3.0 | 2.7 | 2.7 | - |
| **Senior Management** | 3.0 | 2.8 | 2.7 | - |
| **Diversity & Inclusion** | 3.8 | 3.5 | 3.2 | - |
| **% Recommend** | 81% | 74% | 79% | - |
| **CEO Approval** | 73% | 88% | 100% | - |
| **Business Outlook** | 69% positive | 75% positive | 68% positive | - |

All filters except Global are under 30 reviews and should be read as directional. The most recent Glassdoor review is from October 2025, so Glassdoor misses the 2025-2026 decline visible on Kununu. Munich trails the global figures on every sub-score, and Senior Management and Career Opportunities are weak everywhere (2.7-3.0).

### Kununu

Retrieved via **CDP**; the profile is at `kununu.com/de/hoffmann-group` (plain curl returned no data fields). Review data comes from Kununu's in-page reviews endpoint with year, department and keyword filters.

- **Overall score:** 3.4 / 5.0, the same as the trade-sector average (Handel 3.4)
- **Recommendation rate:** **49% over the last 2 years** (profile headline); 65% all-time (246 of 377)
- **Total reviews:** 516 (employee reviews: 402); 276 salary entries; 192 culture entries
- **Sub-scores:** Karriere & Gehalt 3.2, Unternehmenskultur 3.3, Arbeitsumgebung 3.8, Vielfalt 3.4. Salary satisfaction 58%.
- **Kununu Top Company:** NO

**Trend by year (employee reviews):**

| Year | Reviews | Score | Recommend |
|---|---|---|---|
| 2022 | 25 | 3.4 | 64% |
| 2023 | 30 | 3.9 | 80% |
| 2024 | 44 | 4.0 | 75% |
| 2025 | 38 | 3.1 | 47% |
| 2026 (to Nov) | 51 | 3.1 | 51% |
| IT department, all years | 36 | 3.6 | 75% |
| Munich, all years | 266 | 3.4 | 65% |

Ratings fell sharply between 2024 and 2025, from 4.0 to 3.1, and stayed low in 2026. IT reviews follow the same path: 2023 reviews are almost all 4.5-4.8, while 3 of the 4 IT reviews in 2026 do not recommend the company.

### Blind / Teamblind

`teamblind.com/company/Hoffmann-Group` returns "Page not found" (CDP). No Blind presence, which is expected for a German Mittelstand wholesaler.

### Review Themes (2023-2026)

**Positives:**

- **Free food and benefits,** the most consistent positive across platforms: "Kostenloses Frühstück, Mittagessen und freie Getränke" (Kununu, Aug 2026, Führungskraft, Administration / Verwaltung); "Gute Bezahlung, Work-Life Balance, Betriebsrente, kostenlose Verpflegung" (Glassdoor, Apr 2025, current IT system engineer, 3+ years). Kununu benefit confirmations: canteen 81%, parking 75%, company pension 72%.
- **Flexitime and home office:** "Durch moderne Gleitzeitmodelle und sehr großzügige sowie verlässliche Home-Office-Regelungen lassen sich Privatleben und Beruf hervorragend miteinander vereinbaren" (Kununu, Aug 2026, Führungskraft, Administration / Verwaltung).
- **Modern workplace and equipment:** "Equipment alles top notch, Notebook, Handy, Büro" (Kununu, Aug 2024, Führungskraft, IT, München); "Arbeitsplatz modern und ergonomisch" (Kununu, Dec 2024, Ex-Angestellte/r, IT, München).
- **Team cohesion within teams:** "Man will gemeinsam besser werden, nicht gegeneinander" (Kununu, Aug 2024, Führungskraft, IT, München).
- **Stability:** "Krisensicher" (Kununu, Feb 2023, Ex-Angestellte/r, Logistik / Materialwirtschaft, Nürnberg).

**Negatives:**

- **Pay stagnation through tariff offsetting.** This is the strongest theme in 2025-2026, and IT staff raise it too: "Tarifanpassungen werden auf den tariflichen Gehaltsanteil angerechnet und im gleichen Maße von übertariflichen Gehaltsbestandteil bzw. von der Gehaltszulage wieder abgezogen; diese Praktik wurde jetzt bereits das zweite oder dritte Mal in Folge angewandt" (Kununu, Aug 2026, Angestellte/r oder Arbeiter/in, IT, München). Also: "seit der Übernahme aus der Schweiz vor einigen Jahren komplett indiskutabel. Keinerlei Boni" (Kununu, Nov 2026, Angestellte/r oder Arbeiter/in, Vertrieb / Verkauf, Hoffmann Werkzeuge GmbH München).
- **Decline since the SFS takeover:** "Seit der Übernahme durch SFS ist die allgemeine Arbeitsatmosphäre als sehr angespannt zu bezeichnen" (Kununu, May 2026, Angestellte/r oder Arbeiter/in, Vertrieb / Verkauf, München).
- **Treatment of older and expensive staff:** "ältere Kollegen werden eher ungern gesehen weil sie teilweise deutlich mehr verdienen als jüngere Kollegen" (Kununu, Aug 2026, Angestellte/r, IT, München); "Selbst vor der Kündigung langjähriger Mitarbeiter, auch 60+, macht die Firma nicht Halt" (Kununu, Aug 2025, Angestellte/r, Vertrieb / Verkauf, München).
- **Weak leadership and communication:** "wichtige Informationen verbreiten sich eher über den Flurfunk als über die vorhandenen und offiziellen Kommunikationskanäle" (Kununu, Aug 2026, Angestellte/r, IT, München); "Führungskräfte Unqualifiziert und/oder Überheblich; Keine Strategie ... Fingerzeig Mentalität" (Kununu, Dec 2024, Ex-Angestellte/r, IT, München).
- **Bureaucracy and silos:** "Silos arbeiten gegeneinander" (Kununu, Aug 2025, Angestellte/r, IT, Hoffmann Qualitätswerkzeuge München); "Zunehmende Konzern-Trägheit ... bürokratischen und schwerfälligen Entscheidungswegen" (Kununu, Aug 2026, Führungskraft, Administration / Verwaltung).
- **Rising workload:** "jeder vorgesetzte will am liebsten eine 50Std. Woche" (Kununu, Mar 2026, Angestellte/r, IT, Hoffmann Group System GmbH München); "Überstunden trotz stetig steigender Arbeitsbelastung immer seltener genehmigt" (Kununu, Nov 2026, Angestellte/r, Vertrieb / Verkauf, München).
- **Works council resistance:** "Betriebsrat einführen statt ihn zu unterbinden" (Kununu, May 2026, Angestellte/r oder Arbeiter/in, Product, München). See Section 8.
- **Slow hiring:** a Software Developer applicant reports 5 months and four rounds before rejection (Glassdoor, Sep 2024).

Overlap with red flags: Work-Life Balance pressure (mixed), communication breakdown (yes, recurring), silent or managed-out attrition of older staff (moderate signal), works council suppression (yes, historical and current claims).

### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | Moderate and concentrated in logistics and sales. "Respektlos, Mobbing... nur Bevorzugung durch verpetzen von Arbeitskollegen" (Kununu, Oct 2026, Angestellte/r, Logistik / Materialwirtschaft, Nürnberg). IT: "Mitarbeiter arbeiten gegeneinander ... Das Mobbing muss aufhören!!!" (Kununu, May 2024, Ex-Angestellte/r, IT, München). Other IT reviews in 2023-2024 rate leadership 4-5. |
| 24/7 Work Expectation | Not found. One IT reviewer cites an implicit expectation of 50-hour weeks (Mar 2026). |
| Internal Surveillance | Not found. Complaints mention growing reporting work ("Datensammler", statistics), not monitoring. |
| Fear-driven Management | Weak signal: "jeder soll still schweigend arbeiten und nicht reden" (Kununu, Oct 2026, Logistik, Nürnberg). Not reported in IT. |
| Communication Breakdown | **Recurring.** "Flurfunk" (IT, Aug 2026); "Wichtige Veränderungen werden gerne verschwiegen" (Kununu, 2026, Vertrieb); "Rechtzeitige und klare Kommunikation der Veränderungen" requested (Kununu, Mar 2026, IT, München). |
| Unpaid Overtime | Not reported as unpaid. Postings promise "Überstundenausgleich durch Freizeit"; a 2026 sales review says overtime is "immer seltener genehmigt" (increasingly rarely approved). |
| Silent Firings | Moderate signal. Older employees on expensive contracts are pushed toward early retirement: "Möglichkeit auf vorzeitige Verrentung um der Firma das Geld wegen alter, teurer Verträge zu sparen" (Kununu, Aug 2026, Angestellte/r, Logistik, Nürnberg). A manager frames these as "sozialverträgliche Frühverrentungsprogramme". Dismissals of 60+ staff are reported in sales (2025). |
| Work-Life Balance issues | Mixed. Glassdoor WLB 3.8 globally, 3.3 Munich. Kununu WLB praise from office and IT staff (flexitime, home office) sits alongside rising-workload complaints from sales and logistics. |

**Risk level: MODERATE.** The pattern is post-acquisition cost discipline and corporate bureaucracy (b), plus localised dysfunction in logistics and some sales branches (c). It is not systemic toxicity. For an engineer the most relevant risks are pay stagnation, poor change communication and a heavy-process "Amt" culture in IT, not abusive management.

---

## Section 5: Compensation

### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| Glassdoor (CDP) | Software Engineer | ~€67K-81K | none | not stated | ~€67K-81K | 2 |
| Glassdoor (CDP) | Embedded Software Engineer | ~€67K-73K | none | not stated | ~€67K-73K | 2 |
| Kununu (CDP) | SAP Entwickler:in (München) | ~€87.8K avg | none | incl. | ~€87.8K | 5 |
| levels.fyi | - | No company page (404) | - | - | - | 0 |
| Job postings | - | No ranges published ("Attraktives Gehaltspaket") | - | - | - | - |

**Munich reference (levels.fyi Germany, from earlier reports in this project):** Senior SWE median total ~€81.5K, senior range ~€80.7K-€115.1K. Large, profitable Munich employers pay ~€85-110K base, with the 90th percentile at €120K+. Hoffmann-specific Munich 75th/90th percentiles: **UNAVAILABLE**.

Context: pay is anchored to the **Groß- und Außenhandel tariff** (Bavaria) plus a voluntary above-tariff allowance (übertarifliche Zulage). Several reviews, including an IT reviewer in Aug 2026, report that tariff increases have been fully offset against that allowance two or three years in a row, which works out as zero-growth pay rounds. Glassdoor Comp & Benefits is 3.4 (Munich 3.2) and Kununu salary satisfaction is 58%. A management reviewer claims salaries are ~10% above market and values free meals at a ~€12K gross equivalent per year. That benefit is real but does not count toward cash compensation.

### Equity / Stock

None found. Hoffmann employees receive no RSUs or options. The parent SFS Group AG is listed (SIX: SFSN), but no employee share plan for Hoffmann staff was found. Variable pay: reviewers report target agreements linked to base pay in sales ("Zielvereinbarungen nicht an das Basis Gehalt koppeln", 2022) and "Keinerlei Boni" (2026). Benefits include a company pension (bAV), free canteen, tool discount, bike leasing, EGYM Wellpass and travel subsidy.

### Verdict

**BELOW.** The few engineering data points (€67-88K) and the tariff-anchored structure with offsetting sit at or below the Munich senior median (~€81.5K) and well under the €85-110K base typical for large profitable Munich employers. Low confidence: n is very small.

---

## Section 6: AI/ML & Tech Stack

### AI Strategy

Early-stage and mostly about adopting AI tools. Sources:

- Management interview (Wirtschaftsforum): "several small-scale AI pilots in different areas", defined use cases "mainly repetitive transactions", plus AI support for field sales. Simplified, this is process automation in a distribution business.
- Senior Platform Engineer posting: "Mitwirkung am Aufbau einer sicheren, kontrollierten Grundlage, die es Teams ermöglicht, KI-Workloads auf unserer Plattform zu entwickeln und zu betreiben". The AI infrastructure on the Databricks/Azure data platform ("Nexus") is still being built.
- Lead Developer posting: the role is the "Zentrale Stelle für den Einsatz von KI in der Abteilung - von der Bewertung geeigneter Werkzeuge bis zum Wissensaufbau in den Teams". This is AI tooling adoption, not ML product work.
- ToolScout posting asks for experience with "KI-gestützter Entwicklungstools wie Claude".

There are no AI/ML products, ML engineer roles or MLOps teams, and no AI features were found in the eShop or ToolScout. Data work centres on product, master and customer data quality ("Hoffmann 4.0" per the priint blog) and a Data Mesh on Databricks.

### Tech Stack

Sources: current careers-page postings (Senior Platform Engineer, Senior Software Engineer ToolScout, Lead Developer Java, Embedded working student, SAP Inhouse Consultant), expired postings indexed by devjobs.de (Senior Data Platform Engineer, Lead Developer, Embedded Software Engineer, Senior Full Stack Engineer), and the jambit case study (secondary). Not found: no engineering blog, no public GitHub organisation, no StackShare profile.

| Category | Technologies |
|---|---|
| **Primary language(s)** | Java 17 / Spring Boot (customer platform, integration); TypeScript/React (frontends, Piral microfrontends); Python (data-platform core services, HIL test automation); .NET/C# or Node.js accepted for ToolScout; C/C++ (embedded, connected tools); SAP/ABAP (ERP; SAP developers and inhouse consultants) |
| **AI/ML** | No production ML. AI-workload foundation planned on Databricks; AI coding assistants (Claude named) |
| **Cloud** | Microsoft Azure (primary: Entra ID, Key Vault, Azure Monitor, App hosting); Google Cloud Platform mentioned in the Essen Lead Developer listing |
| **Infrastructure** | Terraform; Azure DevOps pipelines; GitLab CI (Essen); containers; Kubernetes (devjobs tag) |
| **Data** | Databricks (Unity Catalog), dbt, Azure Data Factory, Data Mesh model; PostgreSQL, MongoDB, RabbitMQ (customer platform); SQL; Scala (older Analytics Engineer posting) |
| **Other** | Embedded: Zephyr, Yocto, Linux, ARM Cortex-M, ESP32, BLE/CAN/UART; SAP ERP; Maven |

**Summary:** Java-centric application engineering (Spring Boot + React/TypeScript on Azure), much of it delivered by external partners, with a Python/Terraform data-platform layer on Azure Databricks and dbt, plus a small embedded team for connected tools. The surrounding IT is SAP-centred. The work is applied enterprise IT and eCommerce engineering for a distributor, with no research.

---

## Section 7: Language

- Every engineering posting is written in German.
- Senior Software Engineer (ToolScout): "Sehr gute Deutsch- und Englischkenntnisse".
- Lead Developer (Java, Essen): "Verhandlungssichere Deutsch- und Englischkenntnisse".
- Senior Platform Engineer: "Gute Englischkenntnisse in Wort und Schrift werden vorausgesetzt; Deutschkenntnisse sind wünschenswert". This is the only English-first engineering role.
- The company is German-headquartered and its reviews are overwhelmingly in German. The SAP, sales and logistics environment works in German, and internal communication is German. The data-platform team appears more international.

**Verdict:** CONDITIONAL. Fails for the product and software engineering roles (German required). Passes only for the data-platform team.

---

## Section 8: Stability

### Financial Position

- SFS Group 2025: sales CHF 3,056.6M (+0.6%), EBIT CHF 324.3M (10.6%), adjusted CHF 371.0M (12.2%), net income CHF 220.2M, equity ratio 64.4%, net debt CHF 164.8M (down from 335.1M). Investment-grade-style balance sheet. 2026 guidance: 3-6% growth in local currencies, adjusted EBIT margin 12-15%.
- D&L segment (Hoffmann-dominated) 2025: net sales CHF 1,339.7M (+0.2%), EBIT CHF 113.5M (8.5%), adjusted CHF 131.0M (9.8%). Volumes flat; results held up through "prudent cost management". FTE fell to 3,413 from 3,664 (-6.9%, restated).
- Hoffmann revenue: >€1.4bn in 2024 and 2025. Management described 2025 as starting "bumpily" and ending more positively.
- Trend: flat revenue, stable profitability, strong parent. The company is investing heavily (new Munich HQ, >€200M LogisticCity Nuremberg, three dealer acquisitions in 2026).

Financial runway: not applicable (profitable subsidiary of a listed parent).

### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| 2024-2027 | SFS "production and distribution network" programme | ~650 jobs group-wide | D&L items: Malaysia and Singapore activities moved to distribution partners (done Oct 2025), Allchemet sold (Oct 2025), Asia-Pacific unit changes. Other items are manufacturing plants (Olpe, Turnov, Flawil, Torbalı). No German Hoffmann sites named. |
| 2025 | D&L FTE reduction | -251 FTE (-6.9%) | Includes divestments and APAC transfers; no announced German redundancy programme found |
| 2024-2026 | Early retirement and individual exits (reviews) | Unknown | "sozialverträgliche Frühverrentungsprogramme" (Kununu, Aug 2026, Führungskraft); dismissals of long-tenured 60+ staff reported in sales (Kununu, Aug 2025); Glassdoor FAQ snippet "colleagues is good but 95% are retrenched" (likely APAC) |
| 2024 | Cost savings | Unknown | "Aufgrund der ungewissen Zukunft ... die Ungewissheit inwieweit die Einsparungen noch gehen" (Kununu, Sep 2024, Angestellte/r, IT, München) |

No announced mass layoff at Hoffmann in Germany was found (press and TrueUp-style searches). Headcount is managed through attrition, early retirement and pay restraint.

### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat), Munich | **NO (likely)** | Kununu reviews over 11 years: "Betriebsrat unerwünscht" (2015, München); "kein Betriebsrat" (Mar 2018, Vertrieb, München); "Nurnoch fraglich wann ein Betriebsrat kommt" (Jul 2021, Vertrieb, München); "Betriebsrat einführen statt ihn zu unterbinden" (May 2026, Product, München). No press or LinkedIn evidence of a Munich council. |
| Works council, Nuremberg / Odelzhausen logistics | Existed; current status UNKNOWN | "Betriebsrat, der für die Mitarbeiter da ist" (Kununu, Feb 2023, Ex-Angestellte/r, Logistik, Nürnberg). "Wenn schon der Betriebsrat gerichtlich aufgelöst wird wg. Verletzung der Neutralität" (Kununu, Aug 2024, Angestellte/r, Logistik, Nürnberg/Odelzhausen). No court report found to confirm the dissolution. |
| Collective agreement | Pay **oriented on the Bavarian Groß- und Außenhandel tariff** (ver.di / HBE) with above-tariff allowances. Formal tariff binding (full member vs OT-Mitgliedschaft) UNKNOWN. | "Bezahlung nach Groß- und Außenhandel-Tarif. Tariferhöhung werden meist mit der übertariflichen Zulage abgegolten" (Kununu, Aug 2026, Angestellte/r, Logistik, Nürnberg); IT review on tariff offsetting (Aug 2026). Postings do not say "tarifgebunden". |
| European / SE works council | UNKNOWN | Hoffmann SE is a Societas Europaea, so SEBG employee-involvement rules apply to its formation; no SE works council found publicly |
| Conflict signals | **Yes** | Repeated reviews describing management discouraging a works council (2015-2026); claimed court dissolution of the logistics council (2024, unverified) |

For senior engineers the tariff grid is not binding (AT contracts are likely), but the offsetting practice shows that above-tariff pay erodes over time. Without a Munich works council, individual exits and on-call or monitoring rules lack co-determination.

**Verdict:** CAUTION. The parent is financially very stable, but there is no works council at the HQ, there are signs of resistance to one, attrition is managed through early retirement and pay restraint, and integration of three acquisitions is ongoing.

---

## Section 9: Regulated Industry

Wholesale distribution of tools and PPE. Product-safety rules (PPE Regulation, CE marking, radio-equipment rules for connected tools) fall on product management and suppliers, not on software engineering. The internal IT carries the usual GDPR, NIS2-adjacent and SOX-like controls from the listed parent. No safety-critical software standards apply.

**Verdict:** PASS

---

## Section 10: On-Call

- No posting mentions "Rufbereitschaft", "Bereitschaftsdienst" or 24/7.
- Senior Platform Engineer: "Verantwortung für Monitoring, Alerting und Incident Response der Plattform-Services".
- Senior Software Engineer ToolScout: "Überwachung und Verantwortung für Betrieb, Support, Performance und Verfügbarkeit der Plattform einschließlich Cloud-Infrastruktur und Schnittstellen", effectively a "you build it, you run it" ownership role on a small team, with external developers.
- The customer-facing products (eShop, ToolScout, Connected Manufacturing) serve industrial customers mainly during business hours, which reduces the need for out-of-hours cover. No works council exists to regulate on-call at HQ.

**Verdict:** CAUTION (team-dependent). Ask directly in interviews.

---

## Section 11: Interview Process

Based on Glassdoor (CDP, 20 interviews, all roles).

| Metric | Value |
|---|---|
| Difficulty | 3.05 / 5 |
| Positive experience | 65% (25% negative) |
| Average duration | ~47 days (Software Developer: ~150 days, the slowest role) |
| Rounds | 2-4 typical (Software Developer report: 4 rounds over 5 months) |

Stages reported: phone interview (24%), one-on-one (22%), group interview (12%), skills test (8%), background check (8%), presentation (8%), IQ and personality tests (4% each). The process is experience-focused and conversational, with no LeetCode reported. Typical questions are behavioural ("Was tun Sie, wenn Sie eine Deadline nicht einhalten können", Teamlead Digital Infrastructure, Munich, Feb 2024). The main complaint is slowness: "Sehr professionell und überaus freundlich, aber auch relativ langwierig mit über 10 Wochen bis zur Absage" (Glassdoor, Feb 2024, Teamlead Digital Infrastructure applicant, Munich). A Software Developer applicant: "They took Whole 5 months of lengthy interview process to send a rejection email" (Glassdoor, Sep 2024).

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | **FAIL**: tool wholesaler/distributor; 3 of ~70 open roles are software engineering |
| Not consulting | PASS: in-house IT, no client billing |
| Profitable | PASS: D&L EBIT 8.5% (adj. 9.8%); SFS net income CHF 220M |
| Employee count | PASS: >4,000 group-wide; new Munich HQ for ~1,250 |
| English-speaking | **CONDITIONAL**: German required for software and lead roles; English-first only for the data-platform role |
| Local entity + engineering contracts | PASS: Hoffmann SE (HRB 237463), Hoffmann IT & General Services GmbH (HRB 234846), Hoffmann Engineering Services GmbH (HRB 234822), direct contracts |
| Location / work model | Bodenseestraße 343, Freiham (next to S8 Freiham) or Haberlandstraße 55, Pasing; hybrid, max 10 home-working days/month |
| Glassdoor | 3.8 global (110), 3.7 Munich (19), WLB 3.3 Munich, no SWE reviews, last review Oct 2025 |
| Kununu | 3.4 (402), 49% recommend over last 2 years; fell from 4.0 (2024) to 3.1 (2025-26); not a Top Company |
| Salary | **BELOW** (low confidence): €67-88K engineering data points; tariff-anchored with offsetting; no equity |
| AI/ML content | Minimal: AI pilots and AI-infrastructure groundwork on Databricks; no ML product |
| Computer-language/Tech-stack | Java/Spring Boot + React/TS on Azure; Python/Terraform/Databricks/dbt data platform; SAP; embedded C |
| No on-call | CAUTION: incident response and availability ownership in postings; no explicit on-call |
| WLB / Stability | Financially very stable; WLB mixed (flexitime and HO good, workload rising); post-acquisition cost pressure |
| Works council / collective agreement | CAUTION: no Munich works council, repeated claims it is discouraged; Großhandel tariff orientation with offsetting |
| Regulated industry | PASS |
| Review themes | Pay stagnation, decline since SFS, poor change communication, bureaucracy; strong benefits (free meals, pension) |
| Engineering model | Senior roles largely steer external partners (jambit and others) |

---

## Section 13: Verdict

**Exclude.** Hoffmann Group is a stable, profitable, well-run distribution business. As an employer for a senior or staff software engineer it fails on the core criteria, and the employee trend is negative.

**Strengths:** a very solid financial base (SFS: 64% equity ratio, falling net debt, 12-15% EBIT margin guidance); a brand-new HQ next to S-Bahn Freiham; generous non-cash benefits (free breakfast and lunch, pension, flexitime, up to 10 home-working days a month); a modern Azure/Databricks data platform with an English-friendly team; and a calm, experience-based interview format.

**Hard blockers:**

1. **Not software-centric.** The company trades in tools. Its registered purpose is tool trade and distribution, and engineering is a small internal function: 3 software roles among ~70 openings. Software exists to sell catalogue goods.
2. **Language.** The product and software engineering roles (ToolScout Senior Software Engineer, Lead Developer) require "sehr gute" or "verhandlungssichere" German. Only the Senior Platform Engineer role is English-first.
3. **Compensation below the Munich bracket.** The engineering data points run €67-81K (Glassdoor SWE) up to ~€88K (Kununu SAP developer), against a Munich senior median of ~€81.5K and €85-110K base at large profitable employers. Pay is tied to the wholesale tariff, and several 2025-2026 reviews (including IT) report tariff raises being absorbed by cutting the above-tariff allowance. There is no equity.

**Secondary concerns:**

- Kununu fell from 4.0 (2024) to 3.1 (2025-2026), and only 49% recommend the company over the last two years. Reviewers tie the drop to the SFS takeover and its cost discipline.
- No works council at the Munich HQ, with reviews from 2015 to 2026 describing management discouraging one. A Nuremberg logistics council was reportedly dissolved by court (unverified).
- Older and expensive employees are steered toward early retirement, and dismissals of 60+ staff are reported.
- Senior engineering roles centre on steering external developers rather than building, and IT is described as bureaucratic and siloed ("Amt").
- Incident response and availability ownership appear in postings without a works council to regulate on-call.
- Hiring is slow (Software Developer ~150 days on Glassdoor).
- Post-merger integration of three acquired dealers in 2026 adds organisational churn.

**Recommendation:** Do not pursue. The single partly matching role is the Senior Platform Engineer (Python, Terraform, Azure, Databricks; English-first). Revisit only if a posting of that type appears with a disclosed salary band above €95K base. In that case, verify the AT contract terms, the incident-response or on-call rota, and how pay rounds work for AT employees before investing time in the slow interview process.

---

## Section 14: Sources

- [Hoffmann Group careers: job listings](https://career.hoffmann-group.com/Stellenangebote.html) (CDP)
- [Posting: Senior Platform Engineer (m/w/d)](https://career.hoffmann-group.com/Senior-Platform-Engineer-mwd-de-j2241.html) (CDP)
- [Posting: Senior Software Engineer (m/w/d) - ToolScout](https://career.hoffmann-group.com/Senior-Software-Engineer-mwd-ToolScout-de-j2190.html) (CDP)
- [Posting: Lead Developer (m/w/d) - Java](https://career.hoffmann-group.com/Lead-Developer-mwd-Java-de-j1966.html) (CDP)
- [Posting: Werkstudent (m/w/d) Embedded Software](https://career.hoffmann-group.com/Werkstudent-mwd-Embedded-Software-de-j2182.html) (CDP)
- [Posting (expired, 410): Senior/Lead Data Platform Engineer](https://career.hoffmann-group.com/SeniorLead-Data-Platform-Engineer-mfd-de-j1522.html)
- [Posting (expired): Senior Full Stack Engineer](https://career.hoffmann-group.com/Senior-Full-Stack-Engineer-mfd-it-j1523.html) (curl)
- [devjobs.de: Hoffmann Group team and expired IT jobs](https://en.devjobs.de/team/hoffmann-group/jobs) (CDP)
- [WeAreDevelopers: Senior Software Engineer / Full Stack Engineer (403)](https://www.wearedevelopers.com/en/jobs/ext/6464797/senior-software-engineer-full-stack-engineer)
- [WeAreDevelopers: Senior Analytics Engineer (410)](https://wearedevelopers.com/en/companies/3336/hoffmann-group/37392/senior-analytics-engineer-m-f-d)
- [Hoffmann Group Impressum](https://www.hoffmann-group.com/DE/de/hom/hoffmann-group/impressum/e/116046/) (CDP)
- [NorthData: Hoffmann SE](https://www.northdata.de/Hoffmann%20SE%2C%20M%C3%BCnchen) (CDP)
- [NorthData: Hoffmann Engineering Services GmbH](https://www.northdata.de/Hoffmann%20Engineering%20Services%20GmbH%2C%20M%C3%BCnchen) (CDP)
- [NorthData: Hoffmann IT & General Services GmbH](https://www.northdata.de/Hoffmann%20IT%20%26%20General%20Services%20GmbH%2C%20M%C3%BCnchen) (CDP)
- [SFS Annual Report 2025: Segment report](https://reports.sfs.com/annual-report/2025/en/segment-report)
- [SFS Annual Report 2025: Key figures](https://reports.sfs.com/annual-report/2025/en/key-figures)
- [SFS Annual Report 2025 (PDF)](https://www.sfs.com/downloads/investor-relations/publications/annual-report-2025.pdf)
- [SFS: proves resilience in financial year 2025](https://sfs.biz/ch/en/media-newsroom/sfs-proves-resilience-in-financial-year-2025.html)
- [SFS: completes transaction with Hoffmann](https://www.sfs.com/ch/en/media-newsroom/sfs-completes-transaction-with-hoffmann.html)
- [MarketScreener: SFS agreement to acquire Hoffmann SE](https://www.marketscreener.com/quote/stock/SFS-GROUP-AG-16421371/news/SFS-Group-AG-entered-into-an-agreement-to-acquire-Hoffmann-SE-37447214/)
- [SFS: consolidates market position in trading business (Gödde, Oltrogge, Perschmann)](https://sfs.biz/ch/en/media-newsroom/sfs-consolidates-market-position-in-trading-business.html)
- [Marktpuls: SFS acquisition of three partner companies](https://www.marktpuls.ch/artikel/permalink/649786)
- [StockAnalysis: SFS Group financials](https://stockanalysis.com/quote/swx/SFSN/financials)
- [Wirtschaftsforum: "Einfach mehr für die industrielle Produktion" (Hoffmann SE interview)](https://www.wirtschaftsforum.de/news/hoffmann-se/einfach-mehr)
- [jambit: Digital service platform with Hoffmann Group](https://www.jambit.com/en/innovation-stories/development-of-a-digital-service-platform-with-hoffmann-group/)
- [priint blog: Of rabbits and hedgehogs (Hoffmann 4.0 data project)](https://www.priint.com/en/blog/of-rabbits-and-hedgehogs-the-race-between-data-and-print)
- [kadawittfeldarchitektur: Hoffmann headquarters](https://www.kadawittfeldarchitektur.de/en/projekt/hoffmann/)
- [Konii: Hoffmann topping-out ceremony, Freiham](https://www.konii.de/news/tag/bueschl-gruppe/)
- [Logistik Heute: Hoffmann Group opens >€200M global central warehouse](https://logistik-heute.de/news/logistikimmobilien-hoffmann-group-eroeffnet-mehr-als-200-millionen-euro-teures-globales-zentrallager-122308.html)
- [Revelio Labs: Hoffmann SE employees](https://www.reveliolabs.com/companies/hoffmann-se/employees/)
- [Glassdoor: Hoffmann Group reviews (global)](https://www.glassdoor.de/Bewertungen/Hoffmann-Group-Bewertungen-E931366.htm) (CDP)
- [Glassdoor: Hoffmann Group reviews, Germany](https://www.glassdoor.de/Bewertungen/Hoffmann-Group-Deutschland-Bewertungen-EI_IE931366.0,14_IL.15,26_IN96.htm) (CDP)
- [Glassdoor: Hoffmann Group reviews, Munich](https://www.glassdoor.de/Bewertungen/Hoffmann-Group-Munich-Bewertungen-EI_IE931366.0,14_IL.15,21_IC4990924.htm) (CDP)
- [Glassdoor: Software Engineer filter (0 reviews)](https://www.glassdoor.de/Bewertungen/Hoffmann-Group-Bewertungen-E931366.htm?filter.jobTitleFTS=Software%20Engineer) (CDP)
- [Glassdoor: Hoffmann Group interviews](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/Hoffmann-Group-Fragen-im-Vorstellungsgespr%C3%A4ch-E931366.htm) (CDP)
- [Glassdoor: Hoffmann Group salaries](https://www.glassdoor.de/Gehalt/Hoffmann-Group-Geh%C3%A4lter-E931366.htm) (CDP)
- [Kununu: Hoffmann Group profile](https://www.kununu.com/de/hoffmann-group) (CDP)
- [Kununu: Hoffmann Group reviews](https://www.kununu.com/de/hoffmann-group/kommentare) (CDP + in-page reviews endpoint with filters)
- [Kununu: Hoffmann Group salaries](https://www.kununu.com/de/hoffmann-group/gehalt) (CDP)
- [levels.fyi: Hoffmann Group (404, no data)](https://www.levels.fyi/companies/hoffmann-group/salaries) (CDP)
- [Teamblind: Hoffmann Group (not found)](https://www.teamblind.com/company/Hoffmann-Group) (CDP)
- [Indeed: Hoffmann Group reviews](https://de.indeed.com/cmp/Hoffmann-Group-3/reviews)
- [Statista: Best Employers Germany 2026](https://rankings.statista.com/en/employers/rankings/best-employers-germany-2026)
- [OpenStreetMap Nominatim](https://nominatim.openstreetmap.org/) and [Overpass API](https://overpass-api.de/) (office geocoding and transport stops)
