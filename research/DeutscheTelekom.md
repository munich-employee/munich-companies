# Deutsche Telekom - Full Research Report

_Researched: 2026-11-18_

> **Scope note.** "Deutsche Telekom" is a group, not one employer. Software engineers in Germany are hired by several legal entities: **Deutsche Telekom AG** (group functions, including Group Network Technology), **Deutsche Telekom IT GmbH** (internal IT), **Telekom Deutschland GmbH** (the German operator), **Deutsche Telekom Technik GmbH** (network engineering and operations) and **T-Systems International GmbH** (business-customer IT services, including the Industrial AI Cloud). Kununu folds all German subsidiaries except T-Systems into one Deutsche Telekom AG profile. Where the data differs by entity, this report says so. Entity-level differences matter more here than for most companies: T-Systems is an IT services business and reads very differently from the internal engineering units.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 1995 as Deutsche Telekom AG, from the privatised Deutsche Bundespost Telekom; IPO 1996 (**31 years**) |
| Employees | **~200,000** globally (31 Dec 2025; 201,336 at Q3 2025). Germany: **70,751 FTE** at end 2025, down from ~74,550 a year earlier and 85,200 in 2021 (HR Factbook 2025) |
| Revenue (FY2025) | **€119.1B** (+2.9% reported, +4.2% organic). Germany segment €25.6B (-0.4%). Q3 2026: €31.1B (+7.5% YoY) |
| Profitability | Net profit **€9.6B (FY2025)**, €11.2B (FY2024); adjusted net profit €9.7B (+3.7%). Adjusted EBITDA AL €44.2B, free cash flow AL €19.5B. Q3 2026 net profit €2.76B (+13.8%); FY2026 adjusted EBITDA AL guidance raised to €47.6B - **PASS** |
| Ownership | **Public** (Xetra: DTE; part of the DAX). The German federal government is the largest shareholder, directly and through KfW (exact current percentage not verified). Holds 52.8% of T-Mobile US |
| Software-centric | Integrated telecom operator (mobile, fixed line, broadband, TV) plus an IT services arm (T-Systems). Software serves the network, IT and business-customer services; it is not the product - **BORDERLINE** |

### Key People

- **Timotheus Höttges**: CEO since 2014; contract extended (heise). He pushed the 2023 return-to-office guidance (see Section 3).
- **Ferri Abolhassan**: CEO of T-Systems.
- **Srini Gopalan**: former Deutsche Telekom board member (Germany segment), now CEO of T-Mobile US.

### Software-Centric Assessment

Deutsche Telekom earns its money from network access: mobile and fixed contracts, broadband and fibre in Germany and Europe, and T-Mobile US. Software engineering sits in four places:

1. **Group Network Technology (GNT)**, which builds the on-premises **telco cloud** for Europe: a Go/Kubernetes platform built on Cluster API and OpenStack (posting "Software Engineer VI", Bonn, 2026). This is genuine platform engineering.
2. **Deutsche Telekom IT GmbH**: internal IT for the German operator (billing, CRM, ordering, customer apps). Registered purpose: "Design, Entwicklung und Betrieb von IT-Anwendungen".
3. **T-Systems**: IT services for business customers (SAP, cloud migration, public sector, defence cloud), plus the **Industrial AI Cloud** in Munich with NVIDIA (see Section 6).
4. **Consumer AI product** teams in Bonn and Berlin (Product Manager / Technical Product Manager "Consumer AI" postings, 2026).

Reviewers describe the IT estate as large and legacy-heavy: "slow processes etc. all you can imagine for a big corporation with huge codebase and systems which were originally designed long ago" (Glassdoor, Sep 2024, current Software Engineer). Much engineering work is also offshored to group delivery centres in Hungary, Slovakia and India ("Es werden viele Kollegen von Ungarn, Slowakei etc eingestellt, damit Kosten gespart werden", Kununu, Oct 2026, Ex-Angestellte/r oder Arbeiter/in, IT, Deutsche Telekom Business Solutions GmbH, Mannheim).

**Verdict: BORDERLINE.** It is a telco with large in-house engineering, not a software company. GNT (telco cloud) and the Industrial AI Cloud are the most software-centric parts.

### Consulting-Adjacency Assessment (T-Systems only)

T-Systems is consulting-adjacent; the rest of the group is not.

- **Registered purpose** (T-Systems International GmbH): "Kunden- und branchenspezifische Lösungen ... zu entwickeln, zu realisieren, zu betreiben und zu vermarkten ... sowie ... die Beratung in allen genannten Bereichen".
- **Consultant career titles**: current postings include "Senior Consultant SAP CO / PS für S/4HANA Transformationen", "Lead Consultant SAP Kasse & Zahlungsverkehr", "Senior KI Consultant" and "Principal KI Consultant" (telekom.com job search, Glassdoor job widget).
- **Client deliverables**: the "Senior Cloud Architect for Multi-Cloud & Enterprise Transformation" posting describes "Cloud- und Softwarearchitekturen für anspruchsvolle Enterprise-Kundenprojekte" and advising customers in German and English. The Industrial AI Cloud DevOps roles centre on customer onboarding, PoCs and training.
- Deutsche Telekom AG (GNT), Deutsche Telekom IT and Telekom Deutschland build internal products and platforms. They are not consulting.

**Verdict:** T-Systems roles = **CAUTION (consulting-adjacent)**. Other entities = **PASS**.

---

## Section 2: Local Commercial Entity in Germany

Verified via NorthData (CDP) and the 2025 annual report.

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **Deutsche Telekom AG** | Amtsgericht Bonn **HRB 6794** | Friedrich-Ebert-Allee 140, 53113 Bonn | "Betätigung im gesamten Bereich der Telekommunikation, Informationstechnologie, Multimedia, Information und Unterhaltung ..., der Sicherheitsdienstleistungen, Vertriebs- und Vermittlungsdienstleistungen ..." Annual accounts 31 Dec 2025: 8,285 employees in the AG itself |
| **Deutsche Telekom IT GmbH** | Amtsgericht Bonn **HRB 8522** | Landgrabenweg 149, 53227 Bonn | "Das Design, die Entwicklung und der Betrieb von IT-Anwendungen sowie die Bereitstellung einer leistungsfähigen IT-Infrastruktur." |
| **Deutsche Telekom Technik GmbH** | Amtsgericht Bonn **HRB 14190** | Bonn (Munich site: Marsplatz 4) | "Die Technikeinführung, das Planen, Bauen und Betreiben von Einrichtungen und Systemen der technischen Infrastruktur innerhalb des Konzerns Deutsche Telekom im In- und Ausland" |
| **Telekom Deutschland GmbH** | Amtsgericht Bonn **HRB 5919** | Landgrabenweg 149, 53227 Bonn | "Betätigung im gesamten Bereich der Telekommunikation, Mobilkommunikation, Informationstechnologie ..." |
| **T-Systems International GmbH** | Amtsgericht Frankfurt am Main **HRB 55933** | Friedrich-Ebert-Allee 140, 53113 Bonn | "Kunden- und branchenspezifische Lösungen im Bereich der Informationsverarbeitung und Telekommunikation ... zu entwickeln, zu realisieren, zu betreiben und zu vermarkten ... sowie die Beratung ..." |

All five are operating German companies with engineering purposes. None of them is a sales shell. Engineers are employed directly on German contracts: 2026 LinkedIn postings name "Deutsche Telekom AG" (Bonn, Berlin) and "T-Systems International GmbH" (Hamburg, Munich, Dresden and others) as the employer. There is no EOR or PEO. One caution: many group engineering postings are with **foreign subsidiaries** (Deutsche Telekom IT Solutions Hungary, T-Systems Iberia, Deutsche Telekom System Solutions Slovakia, T-Systems India). These carry the group brand but say, for example, that "unsere Möglichkeit der Telearbeit aufgrund der europäischen Steuervorschriften nur in Ungarn verfügbar ist". Check the employing entity on every posting.

**Verdict:** **PASS**

---

## Section 3: Office Location

- **Office address:** **Marsplatz 4, 80335 München** (Arnulfpark, Maxvorstadt). Telekom's careers page lists "Deutsche Telekom, Marsplatz 4, 80335 Munich" as its Munich location. Nominatim tags the building "Deutsche Telekom Technik GmbH" (48.1469, 11.5495). The T-Systems Innovation Center moved there on 10 Feb 2026 after 15 years at the Euro-Industrie-Park. Separately, the **Industrial AI Cloud** data centre (NVIDIA, about 10,000 Blackwell GPUs) went live on 4 Feb 2026 at **Tucherpark**, Munich. It is a data centre, and no evidence was found of an engineering office there.
- **Nearest public transport:** From an Overpass query for the same coordinates earlier on 2026-11-18; re-runs later that day timed out on overpass-api.de, overpass.kumi.systems, maps.mail.ru and private.coffee. Straight-line distances: Hackerbrücke bus stop ~365 m and tram stop ~375 m (trams 16, 17); Deroystraße tram stop ~425 m; München ZOB bus stop ~450 m; Maillingerstraße (U1) ~450 m; **S-Bahn Hackerbrücke ~560 m** (all S-Bahn trunk lines); Stiglmaierplatz (U1/U7) ~565 m.
- **Munich job mix:** Most Munich postings are sales, SAP consulting, project management, IT governance, apprenticeships and fibre civil works. The engineering hubs are Bonn, Berlin, Darmstadt and Dresden. Most posts list many cities, so Munich is often one of 7-13 eligible locations. Glassdoor's Munich reviews come mostly from retail staff, sales associates and dual students (see Section 4).
- **Work model:** **Hybrid.** In Oct 2023 Höttges told managers that office staff should be on site three days a week, and executives four (Business Punk, Oct 2023, updated May 2025; ZfK, Feb 2024). Mobile work is governed by a works-council agreement ("Betriebsvereinbarung Flexible Work", Hans-Böckler-Stiftung portrait). 2026 postings offer "Vertrauensarbeitszeit und ... mobilen Arbeiten" (Software Engineer VI, Bonn) and "Hybrides Arbeitsmodell ... sowie deutschlandweiten Standortoptionen" (T-Systems Senior Cloud Architect). One SWE review reports: "Man kann Deutschlandsweit remote arbeiten + 20 Tage in der EU" (Glassdoor, Nov 2024, current Software Engineer). Some roles require presence: "Anwesenheit am Standort Bonn zwingend erforderlich" (System Engineer IP Transport, 2026). Fully remote within Germany is team-dependent, not the stated policy.

---

## Section 4: Reviews

**GPTW:** No Great Place to Work Germany 2026 certification found for Deutsche Telekom AG or T-Systems. In the past, T-Systems Multimedia Solutions (now Telekom MMS) appeared on GPTW lists. Substitute signals: **Kununu Top Company 2027** for both Deutsche Telekom AG and T-Systems; T-Systems is a **Top Employers Institute "Top Employer Germany 2026"** (a different scheme from GPTW); and the internal 2025 survey reports 81% satisfaction with Deutsche Telekom as an employer (CR report 2025).

### Glassdoor

Retrieved via **CDP** (authenticated Chromium, `glassdoor.de`, employer ID E4092, `filter.iso3Language=all`). Ratings were read from the page's embedded JSON; the counts are the rated-review totals shown on the page.

| Metric | Global | Germany | Munich | Software Engineers | Senior Software Engineers |
|---|---|---|---|---|---|
| **Overall** | **3.7** (1,016 reviews) | **4.0** (637) | 4.3 (36) | 3.8 (22) | 3.5 (7) |
| **WLB** | 3.9 | **4.3** | 4.0 | 3.9 | 4.1 |
| **Culture & Values** | 3.7 | 3.9 | 4.0 | 3.5 | 3.7 |
| **Comp & Benefits** | 3.6 | 3.9 | 3.8 | 3.7 | 3.2 |
| **Career Opportunities** | 3.5 | 3.6 | 3.5 | 3.7 | 3.3 |
| **Senior Management** | 3.2 | 3.6 | 4.0 | 3.4 | 3.0 |
| **Diversity & Inclusion** | 3.9 | 4.3 | 4.1 | 3.8 | 3.7 |
| **% Recommend** | 73% | 86% | 99% | 76% | 73% |
| **CEO Approval (Höttges)** | 82% | 89% | 100% | 81% | 96% |
| **Business Outlook** | 61% positive | 57% positive | 84% positive | 75% positive | 66% positive |

Notes:
- The global figure counts only reviews with ratings. The page's JSON reports 2,512 reviews across all languages, and English-language snapshots show ~1,455.
- **Munich (36)** is above the 20-review threshold, but the recent reviews come from customer service, sales associates, retail sellers and dual students. It says little about engineering.
- **Software Engineer (22)** is borderline. **Senior Software Engineer (7)** is directional only.
- Glassdoor lists 195 Software Engineer and 82 Senior Software Engineer job-title reviews. These include non-German group units (India, Hungary), so the filtered ratings mix countries.

### Kununu

Retrieved via **CDP**. The slugs `deutsche-telekom-it`, `telekom-deutschland` and `deutsche-telekom-technik` all redirect to the Deutsche Telekom AG profile. `t-systems-international` returned 404; `t-systems` is the T-Systems profile.

| Profile | Score | Recommendation | Reviews | Top Company |
|---|---|---|---|---|
| **Deutsche Telekom AG** (`deutsche-telekom`) | **4.0** | **79%** | 8,193 (7,944 employee) | **YES (2027)**; also Top Rated "Gehaltszufriedenheit" and "Familienfreundlichkeit" |
| Deutsche Telekom AG, **IT department filter** | 3.9 | 77% | 1,759 employee reviews | - |
| **T-Systems** (`t-systems`) | **3.8** | **70%** | 2,014 (1,942 employee) | **YES (2027)**; Top Rated "Familienfreundlichkeit" |

- Deutsche Telekom AG sub-scores: Karriere & Gehalt 3.9, Unternehmenskultur 3.9, Arbeitsumgebung 4.0, Vielfalt 4.2. The industry average (Telekommunikation) is 3.6.
- T-Systems sub-scores: Karriere & Gehalt **3.4**, Unternehmenskultur 3.8.
- **Kununu Top Company:** YES for both.

### Blind / Teamblind

Retrieved via **CDP**. **No company page.** `/company/Deutsche-Telekom`, `/company/DeutscheTelekom` and `/company/T-Systems` all return "Page not found". A search for "Deutsche Telekom" returns 13 posts, mostly India offer comparisons from 2020. Blind coverage: **UNKNOWN / none**.

### Review Themes (2024-2026)

**Positives:**

- **Job security and the collective agreement.** "Sehr guter Tarifvertrag, Vorteile eines Konzerns" (Glassdoor, Sep 2026, current Strategic Purchaser, Bonn, 5+ years). "Sicherer Job, man kann einfach Mitlaufen" (Glassdoor, Sep 2025, former Software Engineer, Neustadt an der Weinstraße, 10+ years).
- **WLB, flexible hours, generous leave.** "Jobsicherheit - Arbeitsklima - Kollegen - Work Life Balance - 44 Urlaubstage - Gleitzeit - Mobile work" (Glassdoor, Aug 2026, current Senior Software Engineer, Dresden, 10+ years). "the company is really 'social', supportive to employees. good work life balance" (Glassdoor, Sep 2024, current Software Engineer). Glassdoor WLB is 4.3 in Germany.
- **Flexible, modern offices.** "Sehr flexibel, Home Office möglich, Gutes Gehalt (im Vergleich zu Region Köln-Bonn), Nette Kollegen, Moderne Gebäude" (Glassdoor, Aug 2026, current Software Engineer, Bonn, 1+ year).
- **Team cohesion**, mentioned even in negative reviews: "Kollegenzusammenhalt ... Sehr gut" (Kununu, Oct 2026, Ex-Angestellte/r oder Arbeiter/in, IT, Deutsche Telekom Business Solutions GmbH, Mannheim). "Im Team Top" (Kununu, Oct 2026, Angestellte/r oder Arbeiter/in, IT, Deutsche Telekom IT GmbH, Bonn).

**Negatives:**

- **Continuous headcount reduction and restructuring, with job anxiety** (layoff red flag, but handled through voluntary programmes; see Section 8). "Konstanter Personalabbau, steigender Workload und Stress" (Glassdoor, Oct 2026, current Data Scientist, Bremen, 5+ years). "Dauernde Umorganisationen mit Job Ängsten" (Kununu, Oct 2026, Angestellte/r oder Arbeiter/in, IT, Deutsche Telekom IT GmbH, Bonn). "Es wird nur personal abgebaut und umstrukturiert. Man hat ständig Sorgen um den Arbeitsplatz, Doppelbelastung, da viele Kollegen gehen" (Kununu, Oct 2026, Ex-Angestellte/r oder Arbeiter/in, IT, Deutsche Telekom Business Solutions GmbH, Mannheim).
- **Pay below the tech market, and the tariff flattens performance pay.** "Gehalt - Prozesse & Bürokratie - Management - Eintönigkeit" (Glassdoor, Aug 2026, current Senior Software Engineer, Dresden). "Tarifverträge - keine Anreize für Highperformer, oft Fragwürdige management Entscheidungen" (Glassdoor, Aug 2026, current Software Engineer, Bonn). Glassdoor Comp & Benefits is 3.2 for Senior SWEs; Kununu Karriere & Gehalt for T-Systems is 3.4.
- **Limited career progression.** "Keine Aufstiegschancen, Keine Möglichkeit besonderes Engagement belohnt zu bekommen" (Glassdoor, Sep 2025, former Software Engineer, 10+ years). "Karriereentwicklung und damit Gehaltsentwicklung" (Glassdoor, Nov 2024, current Software Engineer). On Kununu, development is described as "stark standortabhängig" (DT AG profile summary).
- **Bureaucracy, legacy systems and unclear management structure.** "Wer ist mein Vorgesetzter ? Man weiß es nicht so genau." and "Management Dauergeschwurbel" (Kununu, Oct 2026, Angestellte/r oder Arbeiter/in, IT, Deutsche Telekom IT GmbH, Bonn). "Großraumbüro mit 'Mietschreibtischen'" (same review).
- **Offshoring to group delivery centres.** "Es werden viele Kollegen von Ungarn, Slowakei etc eingestellt, damit Kosten gespart werden" (Kununu, Oct 2026, Ex-Angestellte/r oder Arbeiter/in, IT, Deutsche Telekom Business Solutions GmbH, Mannheim).
- **Partial retirement promised, then refused.** "ATZ wird angeboten und dann unter Vorwänden abgelehnt" (Kununu, Oct 2026, Angestellte/r oder Arbeiter/in, IT, Deutsche Telekom IT GmbH, Bonn).

### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | **Localized.** "Die neue Teamleitung ist arrogant. Man bekommt keine Unterstützung. Es kommt alles von oben herab." (Kununu, Oct 2026, Ex-Angestellte/r oder Arbeiter/in, IT, Deutsche Telekom Business Solutions GmbH, Mannheim). CEO approval is high (82% global, 89% Germany), and Senior Management scores 3.6 in Germany |
| 24/7 Work Expectation | **Low for software roles, present in operations.** Network operations and some DevOps teams run 24/7 (see Section 10). No reviewer reports always-on expectations in German engineering roles |
| Internal Surveillance | **No evidence.** Monitoring tools fall under works-council co-determination (§87(1) Nr. 6 BetrVG) |
| Fear-driven Management | **Present as restructuring anxiety, not as management by fear.** "Dauernde Umorganisationen mit Job Ängsten" (Kununu, Oct 2026, Deutsche Telekom IT GmbH, Bonn). Operational dismissals are excluded until end 2028 by the collective agreement |
| Communication Breakdown | **Moderate.** "Es werden nur die Ziele von oben kommuniziert." (Kununu, Oct 2026, Deutsche Telekom Business Solutions GmbH, Mannheim). "Management Dauergeschwurbel" (Kununu, Oct 2026, Deutsche Telekom IT GmbH, Bonn) |
| Unpaid Overtime | **Low.** Tariff staff have defined hours and flexitime ("Gleitzeit", Glassdoor, Aug 2026, Senior Software Engineer, Dresden). AT roles use "Vertrauensarbeitszeit" (trust-based hours), where overtime is not recorded |
| Silent Firings | **No evidence.** Cuts run through announced programmes with partial retirement, severance and a transfer company; there is a works council and a dismissal ban until 2028 |
| Work-Life Balance issues | **Low.** WLB 4.3 Germany / 3.9 global (Glassdoor); Kununu Top Rated "Familienfreundlichkeit". Exceptions are teams absorbing leavers' workload ("Doppelbelastung") |

**Risk level: LOW-MODERATE.** The pattern is mainly (b): large-company bureaucracy, frequent reorganisations and a long, negotiated headcount reduction that creates anxiety and extra workload for those who stay. (c), hostile team leadership, appears in individual units, notably Deutsche Telekom Business Solutions. There is no sign of (a), systemic toxicity.

---

## Section 5: Compensation

### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| levels.fyi (Germany, CDP) | Senior Software Engineer | ~€81.8K | ~€0.1K | ~€2.7K | **~€84.6K** | Not shown; median all SWE €69.2K |
| levels.fyi (Germany) | Lead Software Engineer | ~€102K | €0 | €0 | **~€102K** | Not shown |
| levels.fyi (Germany) | Principal Software Engineer | - | - | - | **~€127K** | Not shown |
| levels.fyi submissions (Bonn, 2026) | Senior SWE, ML/AI, 7 yrs | €73K | - | - | €77K | 1 |
| levels.fyi submissions (Bonn, Apr 2026) | Senior SWE, DevOps, 9 yrs | €90K | - | - | €102K | 1 |
| Glassdoor (Germany, CDP) | Senior Software Engineer | €63.5K-€86.75K, avg **€80.5K** | - | avg €4.2K (range €0.5K-€20K) | ~€85K | 21 |
| Employer-stated bands (Glassdoor job widget, Berlin, 2026) | Senior Cloud & DevOps Engineer | €55K-€65K | - | - | - | 1 posting |
| Employer-stated bands (Berlin, 2026) | (Senior) Observability Architekt | €60K-€75K | - | - | - | 1 posting |
| Employer-stated bands (Dresden, 2026) | IT Architekt Betriebs- & Plattformarchitektur | €70K-€85K | - | - | - | 1 posting |
| Employer-stated bands (Berlin, 2026) | Principal KI Consultant | €80K-€100K | - | - | - | 1 posting |

Munich percentiles: **not available**. Glassdoor returned no Munich page for Senior SWE, and levels.fyi has no Munich page for Deutsche Telekom. Most data points come from Bonn and Dresden, so Munich offers may sit slightly higher, but the group negotiates pay nationally and the tariff grid is national. For reference, large, profitable Munich employers in earlier reports pay ~€85-110K base for senior engineers, with the 90th percentile at €120K+.

**Collective-agreement context:** The May 2026 ver.di agreement covers ~60,000 tariff employees for 33 months to 31 Dec 2028. It adds a monthly supplement of €340 from Aug 2026 and €480 from Jul 2027, then raises the tables by 2.4% in Jun 2028 (about 8.5% in total per ver.di). Senior and architect roles are typically **AT** (außertariflich): the T-Systems Senior Cloud Architect posting offers "ein marktgerechtes Gehaltspaket im außertariflichen Bereich (AT)". Benefits include a company pension (bAV), vermögenswirksame Leistungen and, per one reviewer, 44 days of leave at Telekom MMS Dresden (an older tariff entitlement; not universal).

### Equity / Stock

Listed on Xetra (DTE). There are **no RSUs for non-executive engineers**: levels.fyi shows €0-122/yr in stock. Executives receive long-term incentives. The group has run employee share purchase offers (Share.Plus), but current terms were not verified. Equity is not a material part of pay.

### Verdict

**BELOW** the large, profitable Munich corporate bracket for senior individual contributors. Senior SWE total comp clusters at €80-85K. Lead (~€102K) and Principal (~€127K) reach the bracket only at the top grades, and employer-stated bands for senior engineering roles in Berlin and Dresden are €55K-€85K. Glassdoor reviewers in Cologne-Bonn call pay "gut ... im Vergleich zu Region Köln-Bonn", which supports the view that the grid is set nationally rather than for Munich.

---

## Section 6: AI/ML & Tech Stack

### AI Strategy

- **Industrial AI Cloud** (T-Systems, with NVIDIA; announced Nov 2025, live 4 Feb 2026 at Tucherpark, Munich): about €1B, more than 1,000 DGX B200 systems and RTX PRO servers, up to 10,000 Blackwell GPUs. It is marketed as sovereign AI compute for industry, SMEs, the public sector and research, with SAP, Agile Robots and Perplexity as named partners. 2026 postings for it cover LLM inference serving (vLLM, SGLang), Kubernetes GPU platforms and customer onboarding. This is **genuine AI infrastructure / MLOps work**, though much of it is customer-facing (PoCs, onboarding).
- **Agentic AI and RAG at T-Systems / T Cloud Public**: postings for "AI Software Engineer (Agentic Workflows)" (Hamburg, München, Berlin, Bonn and others) ask for Python, RAG, tool calling and LangGraph/AutoGen/CrewAI/LlamaIndex. Also "Sovereign AI Platform Engineer, T Cloud Public" and "AI Software Engineer / Agentic SDLC Workflow Engineer, T Cloud Public".
- **Consumer AI**: Bonn product teams ("Technical Product Manager VI Consumer AI", "Senior Product Manager - Consumer AI", 2026), building on the Perplexity partnership.
- **AI as a cost lever**: group delivery centres use AI coding tools ("Cursor, Windsurf und Claude Code", Deutsche Telekom IT Solutions Hungary posting) to modernise legacy .NET estates. Deutsche Telekom described AI as integral to its group cost-saving drive (SDxCentral, 2026).
- Much of the hands-on applied-AI hiring (AI Engineer, AI Lead Engineer, Senior Java Developer) sits in Hungary, India, Austria and Spain rather than in Germany.

### Tech Stack

Sources: 2026 LinkedIn postings via the voyager API (Deutsche Telekom AG, T-Systems International, Germany), careers.telekom.com postings (German and foreign group units), search-result excerpts of expired postings, and the GitHub organisation `telekom` (269 public repos; the 100 most recently pushed: Go 24, Java 17, Python 10, TypeScript 7, Kotlin 2, Rust 1).

| Category | Technologies |
|---|---|
| **Primary language(s)** | **Go** (telco cloud, Kubernetes operators), **Java** / Spring Boot / Quarkus (IT backends), **Python** (AI, automation), C#/.NET (legacy internal tools), **SAP ABAP / S/4HANA** (large T-Systems practice), TypeScript |
| **AI/ML** | LLM inference (vLLM, SGLang), NVIDIA DGX B200/B300, RAG, LangGraph, LangChain, LlamaIndex, AutoGen, CrewAI, FastAPI, Azure AI (Austria) |
| **Cloud** | On-prem telco cloud (OpenStack, Kubernetes via Cluster API), Open Telekom Cloud / T Cloud Public, AWS, Azure, GCP (multi-cloud consulting) |
| **Infrastructure** | Kubernetes, OpenShift, Helm, Flux, Argo CD, GitLab CI/CD, GitHub Actions, Terraform, Ansible, Prometheus, Grafana |
| **Data** | Kafka, ActiveMQ, Oracle, PostgreSQL, SQL |
| **Other** | Apache Camel / Red Hat Fuse, Playwright, Selenium, TOGAF (architecture roles) |

**Summary:** Polyglot. Go is the centre of the platform engineering (telco cloud, Kubernetes operators), and Java/Spring the centre of IT and operator backends, alongside a large SAP practice. Python leads the AI work: LLM inference and agentic/RAG systems on Deutsche Telekom's own sovereign GPU cloud (Industrial AI Cloud, NVIDIA) and on T Cloud Public, with multi-cloud (AWS/Azure/GCP) consulting at T-Systems. The work is production and customer-delivery engineering, not research.

---

## Section 7: Language

- Most German postings are **written in German**, with German titles ("Entwicklungsleiter", "Experte für IT-Governance"), even when the requirement is English.
- **English only required:** "Software Engineer VI" (GNT telco cloud, Bonn) asks for "Verhandlungssichere Englischkenntnisse", with no German requirement. GNT describes "internationale Teams". The Industrial AI Cloud student role asks for "Gute Englischkenntnisse".
- **German required:** "Principal Enterprise Architect Defense Cloud Services" asks for "verhandlungssichere Deutsch- und Englischkenntnisse". The T-Systems "Senior Cloud Architect" must argue technical decisions "auf Deutsch und Englisch". The SAP and public-sector roles, and nearly all customer-facing T-Systems roles in Germany, require German.
- Internal communication, works-council material, the collective agreement and HR processes are in German. Kununu (8,193 reviews) is overwhelmingly German-language.

**Verdict:** **CONDITIONAL.** International platform and AI teams (GNT, parts of the Industrial AI Cloud and T Cloud Public) work in English. Customer-facing T-Systems roles, public-sector and defence roles, SAP roles and much of the domestic IT require business-fluent German. Check each posting.

---

## Section 8: Stability

### Financial Position

- FY2025: revenue **€119.1B** (+2.9% reported, +4.2% organic); net profit **€9.6B** (-14.3%, after one-offs); adjusted net profit €9.7B (+3.7%); adjusted EBITDA AL €44.2B; FCF AL €19.5B. Germany segment revenue €25.6B (-0.4%), adjusted EBITDA up ~1.7%.
- Q3 2026: revenue €31.1B (+7.5%), net profit €2.76B (+13.8%); 9M adjusted net profit €8.4B (+10.2%). FY2026 adjusted EBITDA AL guidance raised to €47.6B, with a record dividend planned.
- Trend: **stable and improving**. One of Europe's largest and most profitable telcos; financial risk is negligible.

### Financial Runway

Not applicable: public and highly profitable.

### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| 2018-2020 | T-Systems restructuring | ~10,000 globally, ~6,000 in Germany | Offshoring to Hungary, Slovakia, India; negotiated with ver.di |
| Oct 2023-2024 | **Vector4IT** at Deutsche Telekom IT | ~1,300 of 5,400 German Telekom IT jobs (about 2,000 group-wide reported) | Transfer company, early retirement and partial retirement; the works council reported "Wut und Entsetzen". ver.di petition "Stoppt den Stellenabbau in der Telekom IT" |
| 2025 | Ongoing German reduction | Germany FTE **74,550 to 70,751 (-5%)** | 2,294 partial retirements, **1,016 severance agreements** (up from 760 in 2024), 595 civil-servant early retirements (HR Factbook 2025); "socially responsible" only |
| 2021-2025 | Multi-year trend | Germany FTE **85,200 to 70,751 (-17%)** | Mainly fixed-line infrastructure ("Systemgeschäft") and IT |
| 2026 | T-Mobile US (subsidiary) | -4,671 in H1 2026 | US only, not German staff |
| 2026 (Germany) | No new named programme found | - | The May 2026 collective agreement **excludes operational dismissals until 31 Dec 2028**. Oct 2026 Kununu reviews still describe ongoing "Personalabbau" and reorganisations |

### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | **YES** (local works councils, a Gesamtbetriebsrat and a Konzernbetriebsrat) | Konzernbetriebsrat statements on Vector4IT (2023); 2026 works-council elections completed across Telekom businesses (DPVKOM); Kununu: "Der Betriebsrat ist absolut keine Unterstützung und weiß Bescheid über die Probleme" (Oct 2026, Ex-Angestellte/r oder Arbeiter/in, IT, Deutsche Telekom Business Solutions GmbH, Mannheim) |
| Collective agreement | **Company agreement (Haustarif) with ver.di** for ~60,000 employees, May 2026, running to 31 Dec 2028; also a DPVKOM presence. Senior roles are often **AT** (außertariflich) | Telekom press release May 2026; DGB Tarifmeldung; 2026 posting "Gehaltspaket im außertariflichen Bereich (AT)"; Glassdoor "Sehr guter Tarifvertrag" (Sep 2026, Bonn) |
| European works council (multinationals) | **YES** (Deutsche Telekom European Works Council) | Group-level EWC; it does not cover T-Mobile US |
| Supervisory board co-determination | **YES, parity** (more than 2,000 German employees) | MitbestG |
| Conflict signals | **Collective, not hostile:** ver.di warning strikes in 2026 (more than 32,000 participants) before the agreement; protests against the Vector4IT cuts. No union-busting or blocked council elections found | DGB, Börse Global, Campact petition |

This is the textbook "both present" case. Headcount falls through announced, negotiated programmes (partial retirement, severance, transfer company), and the 2026 agreement bans operational dismissals until end 2028. The flip side is permanent restructuring pressure and workload shifted onto those who stay.

**Verdict:** **PASS.** Very strong financials, full co-determination and a dismissal ban to 2028. The German workforce is shrinking steadily but only through voluntary means.

---

## Section 9: Regulated Industry

- **Telecom regulation:** TKG (Telekommunikationsgesetz), Bundesnetzagentur oversight, lawful-intercept obligations, telecom secrecy and data-retention rules.
- **Critical infrastructure:** KRITIS / NIS2 (the network is critical infrastructure), with BSI security requirements and change control on network and customer-data systems.
- **Public sector and defence (T-Systems):** "Defense Cloud Services", Public Sector SAP and sovereign cloud work can require security clearance (Sicherheitsüberprüfung), BSI C5 attestations and VS-NfD handling.
- The engineering impact is security reviews, documented change processes and slower releases on network systems. That is moderate: not medical or automotive safety-case overhead.

**Verdict:** **CAUTION** (moderate; higher for defence and public-sector T-Systems roles)

---

## Section 10: On-Call

- A network operator runs 24/7 operations: network operations centres, Deutsche Telekom Technik field services, and the operator IT for billing and ordering.
- A group DevOps posting (Tolling Services, Hungary) explicitly requires "Bereitschaft zur Teilnahme an Rotationen rund um die Uhr auf Abruf und gelegentlichem Wochenend-Support".
- GNT telco cloud teams "entwickeln und betreiben" (build and operate) the platform, so a production platform with on-call is likely. The German posting does not mention on-call explicitly.
- Industrial AI Cloud roles include "Monitoring, Observability und Kapazitätsplanung" for customer GPU workloads.
- Mitigation: in German entities, on-call (Rufbereitschaft) is co-determined by the works council (§87(1) Nr. 2-3 BetrVG) and paid under the collective agreement.
- Product, consulting and AI-application roles show no on-call signal.

**Verdict:** **CAUTION (team-dependent)**. Ask about it for platform and operations roles; it is unlikely for product and AI-application roles.

---

## Section 11: Interview Process

Based on Glassdoor data (retrieved via CDP).

| Metric | Software Engineer | All roles |
|---|---|---|
| Difficulty | **3.0 / 5** (31 submissions) | 2.9 / 5 (408 submissions) |
| Positive experience | **45%** (35% negative) | 61% (22% negative) |
| Average duration | ~2 weeks (few reports; 14 days in the SWE samples) | ~1-2 weeks |
| Rounds | 2-3 | - |

How SWE candidates got an interview: 32% via a recruiter, 23% via an agency, 18% by applying online. A typical German process is a recruiter or HR screen, then one or two technical/experience interviews with the team and hiring manager, sometimes with a case or architecture discussion. Reports describe it as **experience- and conversation-focused** ("they asked about previous experience", Glassdoor, Jul 2025, Software Developer, Berlin, 2 weeks). LeetCode-style DSA rounds appear mainly in the India delivery centres ("2 Tech rounds, 1 HR round ... Java basics, 2 DSA Problems ... A little bit of system design", Glassdoor, Apr 2025, Software Engineer, Gurgaon). Complaints focus on **ghosting**: "after that initial outreach, there has been complete silence. For the past 15 days, I have been consistently following up" (Glassdoor, May 2026, Software Engineer candidate, no offer).

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | **BORDERLINE**: telco; GNT telco cloud and the Industrial AI Cloud are the software-centric parts |
| Not consulting | **PASS** for DT AG / DT IT / Telekom Deutschland; **CAUTION** for T-Systems (consultant titles, client projects) |
| Profitable | **PASS**: €9.6B net profit FY2025; Q3 2026 +13.8%; guidance raised |
| Employee count | ~200,000 globally; 70,751 FTE in Germany (shrinking ~5% a year) |
| English-speaking | **CONDITIONAL**: platform and AI teams English; T-Systems customer, SAP and public-sector roles need German |
| Local entity + engineering contracts | **PASS**: DT AG HRB 6794, DT IT HRB 8522, DT Technik HRB 14190, Telekom Deutschland HRB 5919, T-Systems HRB 55933; direct German contracts |
| Location / work model | Marsplatz 4, Munich (S-Bahn Hackerbrücke ~560 m); hybrid with a 3-days-in-office norm since 2023; engineering hubs mostly outside Munich |
| Glassdoor | **PASS**: 3.7 global, **4.0 Germany**, WLB 3.9 / **4.3 Germany**; SWE 3.8 (22); Senior SWE 3.5 (7, directional) |
| Kununu | **PASS**: DT AG 4.0 / 79% / Top Company 2027; IT dept 3.9 / 77%; T-Systems 3.8 / 70% / Top Company 2027 |
| Salary | **BELOW**: Senior SWE ~€80-85K TC; Lead ~€102K; Principal ~€127K; stated bands for senior roles €55-85K |
| AI/ML content | Moderate to strong: Industrial AI Cloud (NVIDIA, Munich), agentic/RAG at T-Systems and T Cloud Public, Consumer AI; much hands-on AI hiring offshore |
| Computer-language/Tech-stack | Polyglot: Go (platform), Java/Spring (IT), Python (AI), SAP; Kubernetes, OpenStack, multi-cloud |
| No on-call | **CAUTION**: platform and operations teams likely; co-determined and paid |
| WLB / Stability | WLB strong (Glassdoor DE 4.3, Kununu family-friendly seal); financially very stable; constant restructuring anxiety |
| Works council / collective agreement | **PASS**: works councils at every level, ver.di Haustarif to 2028 with a ban on operational dismissals; senior roles AT |
| Regulated industry | **CAUTION**: TKG/BNetzA, KRITIS/NIS2; defence and public-sector clearance at T-Systems |
| Review themes | Security, tariff, WLB, flexibility vs. reorganisations, headcount reduction, pay, slow careers, bureaucracy |
| Offshoring | Much engineering hiring goes to Hungary, Slovakia, India, Spain; the German IT headcount shrinks year on year |

---

## Section 13: Verdict

**Monitor, and apply selectively** to English-first engineering roles employed by a German entity (Deutsche Telekom AG GNT, the T-Systems Industrial AI Cloud, T Cloud Public AI teams). Do not pursue the group broadly.

**Strengths.** Deutsche Telekom is among the most stable employers in Germany: €9.6B net profit, rising guidance, full co-determination, and a ver.di collective agreement that bans operational dismissals until 31 Dec 2028. WLB is a consistent strength: Glassdoor WLB 4.3 in Germany, Kununu Top Company 2027 plus the family-friendliness seal, flexitime, trust-based hours and mobile work. Headcount cuts happen through announced, negotiated, voluntary programmes, not silent firings. Munich has a central site (Marsplatz 4, next to Hackerbrücke) and hosts the group's flagship AI asset, the NVIDIA Industrial AI Cloud.

**Hard blockers:** none at group level for internal engineering roles. For specific roles:

1. **German-language requirement on many roles.** T-Systems customer-facing, SAP, public-sector and defence roles require business-fluent German ("verhandlungssichere Deutsch- und Englischkenntnisse"), and those roles are excluded by the language threshold. GNT and the AI platform teams require English only.
2. **Consulting-adjacency at T-Systems.** Consultant titles ("Senior/Principal KI Consultant", "Senior Consultant SAP") and client-project architecture work fail the no-consulting criterion. Engineering roles on Deutsche Telekom's own platforms do not.

**Secondary concerns:**

- **Pay is below the Munich bracket.** Senior SWE total comp is ~€80-85K (levels.fyi €84.6K; Glassdoor base average €80.5K), and only Principal (~€127K) reaches the large-corporate senior range. Stated bands for senior engineering roles in Berlin and Dresden are €55-85K. There is no meaningful equity, and the grid is national.
- **Permanent restructuring.** Germany FTE fell 17% from 2021 to 2025 and 5% in 2025 alone, with 1,016 severance agreements in 2025. Reviewers in 2026 describe "Dauernde Umorganisationen mit Job Ängsten" and extra workload from leavers. The 2028 dismissal ban limits the personal risk, but the climate is unsettled.
- **Offshoring.** Many engineering and AI roles are hired in Hungary, Slovakia, India and Spain, and German IT shrinks year on year. That limits the scope and seniority of the work that stays in Germany.
- **Munich is not an engineering hub.** Most engineering posts are tied to Bonn, Berlin, Darmstadt or Dresden, with Munich as one of many listed locations. Check that the team accepts a Munich base and that the 3-day office norm can be met at Marsplatz rather than in Bonn.
- **Telco, not software.** Legacy-heavy IT and bureaucracy; a borderline software-centric fit.
- **On-call** for platform and operations teams (co-determined and paid, but present).
- **Interview experience** is mixed for SWE candidates (45% positive), with ghosting complaints.

**Recommendation:** Tier B. Keep Deutsche Telekom on the watch list for **specific** roles: Deutsche Telekom AG GNT (telco cloud platform, Go/Kubernetes, English) and T-Systems Industrial AI Cloud / T Cloud Public AI platform roles (Python, LLM inference, English) that list Munich as a location and are employed by a German entity. Skip T-Systems consulting, SAP, public-sector and defence roles. If a matching role comes up, verify during the process:
1. the pay grade (AT vs. tariff) and the actual band, and push for Principal/Lead-equivalent grading, since Senior bands are well below the Munich bracket;
2. that the team is based in Munich, or accepts Munich, and how the 3-day office norm applies;
3. whether the team has on-call (Rufbereitschaft) and how it is compensated;
4. whether the team is exposed to the next restructuring or offshoring wave (e.g. whether delivery is shared with Hungary or India);
5. the working language of the team day to day.

---

## Sources

- [Deutsche Telekom - Q3 2026: more growth, raised guidance, record dividend](https://www.telekom.com/en/newsroom/latest-updates/media-information/2026/11/more-growth-raised-guidance-record-dividend)
- [Deutsche Telekom - Financial results Q3 2026](https://www.telekom.com/en/investor-relations/publications/financial-results?wcmmode=disabled)
- [Tech Insider - Deutsche Telekom Q3 2026 revenue €31.1B](https://tech-insider.org/deutsche-telekom-q3-2026-revenue-31-1-billion-capex-falls-2026/)
- [Quartr - Deutsche Telekom Q3 2026 earnings summary](https://quartr.com/events/deutsche-telekom-ag-dte-q3-2026_3s914Tbt)
- [Deutsche Telekom - Bericht zum Geschäftsjahr 2025](https://www.telekom.com/de/medien/medieninformationen/detail/bericht-zum-geschaeftsjahr-2025-1102176)
- [Deutsche Telekom - Telekom übertrifft die Ziele für 2025](https://www.telekom.com/de/newsroom/aktuelles/medieninformationen/2026/02/deutsche-telekom-uebertrifft-ziele-fuer-2025)
- [Geschäftsbericht 2025 - Konzernabschluss (PDF)](https://bericht.telekom.com/geschaeftsbericht-2025/_assets/downloads/cfs-financial-statements-dtag-gb25.pdf)
- [Geschäftsbericht 2025 - Konzernlagebericht (PDF)](https://bericht.telekom.com/geschaeftsbericht-2025/_assets/downloads/cmr-management-report-dtag-gb25.pdf)
- [HR Factbook 2025 - Our employees (PDF)](https://bericht.telekom.com/hr-factbook/2025/_assets/downloads/emp-our-employees-dtag-hrfb25.pdf)
- [HR Factbook 2025 - Socially responsible staff reduction](https://report.telekom.com/hr-factbook/2025/costs-productivity/recruitment-mobility-and-attrition/socially-responsible-staff-reduction.html)
- [HR Factbook for the 2025 financial year](https://www.telekom.com/en/newsroom/latest-updates/news/2026/4/hr-factbook-for-the-2025-financial-year)
- [CR Report 2025 - Employees](https://report.telekom.com/cr-report/2025/social/employees.html)
- [NorthData - Deutsche Telekom AG, Bonn (HRB 6794)](https://www.northdata.de/Deutsche+Telekom+AG,+Bonn/Amtsgericht+Bonn+HRB+6794)
- [NorthData - Deutsche Telekom IT GmbH, Bonn (HRB 8522)](https://www.northdata.de/Deutsche+Telekom+IT+GmbH,+Bonn/Amtsgericht+Bonn+HRB+8522)
- [NorthData - search Deutsche Telekom Technik GmbH (HRB 14190)](https://www.northdata.de/search?query=Deutsche%20Telekom%20Technik%20GmbH)
- [NorthData - T-Systems International GmbH (HRB 55933 Frankfurt)](https://www.northdata.de/T-Systems+International+GmbH,+Bonn/Amtsgericht+Frankfurt+am+Main+HRB+55933)
- [NorthData - search Telekom Deutschland GmbH (HRB 5919)](https://www.northdata.de/search?query=Telekom%20Deutschland%20GmbH)
- [Telekom Careers - Our Munich location](https://telekom.com/en/careers/contact/office-locations/munich)
- [Telekom - Innovation Center: Tech zum Anfassen (Jan 2026)](https://www.telekom.com/de/newsroom/aktuelles/medieninformationen/2026/01/innovation-center-tech-zum-anfassen)
- [T-Systems - Innovation at your fingertips at the Innovation Center München](https://www.t-systems.com/de/en/insights/newsroom/news/innovation-at-your-fingertips-at-the-innovation-center-muenchen-1141924)
- [Stadt München - Klimapakt: PV-Anlage und Großspeicher am Telekom-Standort München](https://stadt.muenchen.de/lhm-ms-wirtschaftsfoerderung/aktuelles/erfolgsgeschichten/klimapakt-erfolgsgeschichte-telekom.html)
- [Business Punk - Telekom-Chef drängt Mitarbeitende ins Büro zurück (Oct 2023)](https://www.business-punk.com/trotz-wachsender-zufriedenheit-durch-homeoffice-telekom-chef-draengt-mitarbeitende-ins-buero-zurueck/)
- [ZfK - In Firmen werden die Vorgaben für Homeoffice strenger (Feb 2024)](https://www.zfk.de/karriere/in-firmen-werden-die-vorgaben-fuer-homeoffice-strenger)
- [Hans-Böckler-Stiftung - New Work bei Telekom Deutschland (PDF)](https://www.boeckler.de/data/mbf_bvd_portrait_new_work_telekom_deutschland.pdf)
- [Glassdoor - Deutsche Telekom reviews (global)](https://www.glassdoor.de/Bewertungen/Deutsche-Telekom-Bewertungen-E4092.htm?filter.iso3Language=all)
- [Glassdoor - Deutsche Telekom reviews, Germany](https://www.glassdoor.de/Bewertungen/Deutsche-Telekom-Deutschland-Bewertungen-EI_IE4092.0,16_IL.17,28_IN96.htm?filter.iso3Language=all)
- [Glassdoor - Deutsche Telekom reviews, Munich](https://www.glassdoor.de/Bewertungen/Deutsche-Telekom-M%C3%BCnchen-Bewertungen-EI_IE4092.0,16_IL.17,24_IC4990924.htm?filter.iso3Language=all)
- [Glassdoor - Deutsche Telekom reviews, Software Engineer](https://www.glassdoor.de/Bewertungen/Deutsche-Telekom-Bewertungen-E4092.htm?filter.iso3Language=all&filter.jobTitleFTS=Software%20Engineer)
- [Glassdoor - Deutsche Telekom reviews, Senior Software Engineer](https://www.glassdoor.de/Bewertungen/Deutsche-Telekom-Bewertungen-E4092.htm?filter.iso3Language=all&filter.jobTitleFTS=Senior%20Software%20Engineer)
- [Glassdoor - Deutsche Telekom reviews (English, glassdoor.com)](https://www.glassdoor.com/Reviews/Deutsche-Telekom-Reviews-E4092.htm)
- [Glassdoor - Deutsche Telekom Senior Software Engineer salaries, Germany](https://www.glassdoor.de/Gehalt/Deutsche-Telekom-Senior-Software-Engineer-Deutschland-Geh%C3%A4lter-EJI_IE4092.0,16_KO17,41_IL.42,53_IN96.htm)
- [Glassdoor - Deutsche Telekom interviews, Software Engineer](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/Deutsche-Telekom-Fragen-im-Vorstellungsgespr%C3%A4ch-E4092.htm?filter.jobTitleFTS=Software%20Engineer)
- [Glassdoor - Deutsche Telekom interviews, all roles](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/Deutsche-Telekom-Fragen-im-Vorstellungsgespr%C3%A4ch-E4092.htm)
- [Kununu - Deutsche Telekom AG](https://www.kununu.com/de/deutsche-telekom)
- [Kununu - Deutsche Telekom AG reviews, IT department](https://www.kununu.com/de/deutsche-telekom/kommentare?department=it&sort=newest)
- [Kununu - T-Systems](https://www.kununu.com/de/t-systems)
- [Blind - search "Deutsche Telekom"](https://www.teamblind.com/search/Deutsche%20Telekom)
- [levels.fyi - Deutsche Telekom Software Engineer salaries, Germany](https://www.levels.fyi/companies/deutsche-telekom/salaries/software-engineer/locations/germany)
- [Great Place to Work - Deutschlands Beste Arbeitgeber 2026 (Rahmeninformationen)](https://service.greatplacetowork.de/hubfs/Presse/Rahmeninformationen_Deutschlands%20Beste%20Arbeitgeber%202026.pdf)
- [ChannelPartner - IT-Dienstleister unter den Top Employers 2026](https://www.channelpartner.de/article/4118487/it-dienstleister-unter-den-top-employers-2026.html)
- [T-Systems - Careers (Top Employer 2026)](https://www.t-systems.com/de/en/careers)
- [Deutsche Telekom und ver.di erzielen Tarifeinigung (May 2026)](https://www.telekom.com/de/newsroom/aktuelles/medieninformationen/2026/05/deutsche-telekom-und-ver-di-erzielen-tarifeinigung)
- [DGB - Tarifergebnis Deutsche Telekom: Mehr Entgelt, Kündigungsschutz, Mitgliederbonus](https://www.dgb.de/service/weiterer-service/tarifmeldungen/tarifmeldung/tarifergebnis-deutsche-telekom-mehr-entgelt-kuendigungsschutz-und-erstmals-mitgliederbonus/)
- [DGB - Tarifrunde Telekom 2026: Bundesweite Warnstreiks](https://www.dgb.de/service/weiterer-service/tarifmeldungen/tarifmeldung/tarifrunde-telekom-2026-bimdesweite-warnstreiks-und-kundgebung-in-potsdam/)
- [Börse Global - Tarifeinigung nach 32.000 Streiks](https://www.boerse-global.de/deutsche-telekom-aktie-tarifeinigung-nach-32-000-streiks/790690)
- [Berliner Zeitung - Einigung im Telekom-Tarifstreit](https://www.berliner-zeitung.de/article/einigung-im-telekom-tarifstreit-mehr-geld-und-kuendigungsschutz-fuer-beschaeftigte-10040611)
- [WinFuture - Massiver Stellenabbau bei Deutscher Telekom (Telekom IT, 2023)](https://winfuture.de/news,138919.html)
- [Handelsblatt - Höttges will Tausende Stellen abbauen](https://www.handelsblatt.com/technik/it-internet/deutsche-telekom-timotheus-hoettges-will-tausende-stellen-abbauen/29431018.html)
- [betriebsrat.de - Telekom: Stellenabbau hier, Personalaufbau dort](https://www.betriebsrat.de/news/digitaler-wandel/telekom-stellenabbau-hier-personalaufbau-dort-2937259)
- [Campact WeAct - Stoppt den Stellenabbau in der Telekom IT](https://weact.campact.de/petitions/digitalisierung-ohne-it-stoppt-den-stellenabbau-in-der-telekom-it)
- [DPVKOM - Telekommunikation (Betriebsratswahlen 2026)](https://www.dpvkom.de/berufspolitik/telekommunikation/)
- [Light Reading - DT will cut 10k jobs at T-Systems](https://www.lightreading.com/operations/dt-will-cut-10k-jobs-at-t-systems-report)
- [CIO.de - T-Systems streicht weltweit 10.000 Stellen](https://www.cio.de/article/3688593/t-systems-streicht-weltweit-10-000-stellen.html)
- [SDxCentral - T-Mobile US cut more than 4,500 jobs in 2026 as Deutsche Telekom drives modernization](https://www.sdxcentral.com/news/t-mobile-us-cut-more-than-4500-jobs-in-2026-as-deutsche-telekom-drives-modernization/)
- [The Local - Major German companies cutting jobs at the end of 2026](https://www.thelocal.de/20261109/listed-the-major-german-companies-cutting-jobs-at-the-end-of-2026)
- [Telekom - Telekom startet Industrial AI Cloud mit NVIDIA](https://www.telekom.com/de/newsroom/aktuelles/medieninformationen/2025/11/fuer-ein-souveraenes-deutschland)
- [Telekom - KI-Souveränität für Deutschland und Europa](https://www.telekom.com/de/newsroom/aktuelles/medieninformationen/2025/11/ki-souveraenitaet-fuer-deutschland-und-europa)
- [Telekom - Einfach erklärt: Industrial AI Cloud](https://www.telekom.com/de/newsroom/aktuelles/erklaerstuecke/2025/12/industrial-ai-cloud)
- [ingenieur.de - Industrial AI Cloud gestartet (Feb 2026)](https://www.ingenieur.de/technik/fachbereiche/ittk/sap-telekom-und-nvidia-bauen-europas-erste-industrial-ai-cloud-auf/)
- [RCR Wireless - Deutsche Telekom launches industrial AI factory in Munich](https://www.rcrwireless.com/?p=428188)
- [Telekom Careers - AI Software Engineer (Agentic Workflows), T-Systems](https://careers.telekom.com/de/jobs/913399)
- [Telekom Careers - AI Software Engineer / Agentic SDLC Workflow Engineer, T Cloud Public](https://careers.telekom.com/en/jobs/ki-softwareentwickler-agentic-sdlc-workflow-engineer-m-w-d-t-cloud-public-744000141713006)
- [Telekom Careers - Sovereign AI Platform Engineer, T Cloud Public](https://careers.telekom.com/en/jobs/sovereign-ai-platform-engineer-m-f-d-t-cloud-public-744000137891180)
- [Telekom Careers - Senior System Engineer for IT Infrastructure & Cloud, T-Systems](https://careers.telekom.com/en/jobs/714850)
- [Telekom Careers - Principal DevOps Engineer for Industrial AI Cloud (T-Systems Iberia)](https://careers.telekom.com/de/jobs/principal-devops-engineer-m-f-d-for-industrial-ai-cloud-744000153443654)
- [Telekom Careers - DevOps Engineer, German-speaking (Hungary, 24/7 on-call)](https://careers.telekom.com/de/jobs/devops-engineer-m-f-d-german-speaking-563465374941425)
- [Telekom Careers - QA Automation Engineer / SDET, AI & Parity (Hungary)](https://careers.telekom.com/de/jobs/qa-automation-engineer-sdet-m-f-d-ai-parity-focus-563465374941481)
- [Telekom Careers - Senior Java Developer (Hungary)](https://careers.telekom.com/en/jobs/senior-java-developer-m-f-d-744000128655189)
- [Telekom Careers - AI Engineer (Hungary)](https://careers.telekom.com/de/jobs/ai-engineer-m-f-d-744000129417414)
- [Telekom Careers - global job search](https://www.telekom.com/de/karriere/jobsuche)
- [LinkedIn - Software Engineer VI, Deutsche Telekom AG, Bonn (GNT telco cloud)](https://www.linkedin.com/jobs/view/4486379390)
- [LinkedIn - Senior Cloud Architect for Multi-Cloud & Enterprise Transformation, T-Systems](https://www.linkedin.com/jobs/view/4485092479)
- [LinkedIn - Principal Enterprise Architect Defense Cloud Services](https://www.linkedin.com/jobs/view/4486245403)
- [LinkedIn - Werkstudent AI Inference & Platform Engineering, T-Systems](https://www.linkedin.com/jobs/view/4482085713)
- [LinkedIn - System Engineer IP Transport, Deutsche Telekom AG, Bonn](https://www.linkedin.com/jobs/view/4489751968)
- [GitHub - telekom organisation](https://github.com/telekom)
- [heise - Contract of Telekom CEO Höttges extended](https://heise.de/-10258264)
- [OpenStreetMap Nominatim](https://nominatim.openstreetmap.org/) and [Overpass API](https://overpass-api.de/) (office geocoding and transit stops)
