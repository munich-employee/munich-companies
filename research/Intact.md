# Intact - Full Research Report

_Researched: 2026-11-13_

> **Identity note:** "Intact" here is **Intact GmbH** (Lebring, Austria, intact-systems.com), the audit and certification workflow software vendor for the Testing, Inspection and Certification (TIC) industry. It is unrelated to Intact Financial / Intact Insurance (Toronto), whose data dominates Glassdoor, Blind and levels.fyi under the same name. Every figure below was checked to belong to the Austrian company; mixed-up data is flagged.

> **Critical Disqualifiers**
> 1. **No German entity and no Munich office.** Intact has no German registration. Its only German presence is "Intact Sales Partner Global" in Tutzing (a sales partner, per LinkedIn). Engineering roles are advertised as "DACH (Remote)", but the contracting entity for a German resident is unstated (Austrian GmbH as foreign employer, or an EOR).
> 2. **Three layoff rounds in 2026, with silent-firing reports.** Kununu reviews from June to October 2026 (IT and sales staff) describe "die dritte Entlassungsrunde in diesem Jahr", people who "verschwinden teilweise von einem Tag auf den anderen", and cold, unannounced dismissals, while management says the company is financially stable.
> 3. **Pay floors are Austrian and below the Munich large-company bracket.** Senior engineering postings start at €64,554 to €80,000 (Austria), and "for other locations, in line with local market conditions". Kununu developer salaries average €63-66K.
>
> The full report follows for completeness.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 2001 (25 years); Firmenbuch registration 15 Feb 2002 |
| Employees | 98 at Intact GmbH (FY2024 Jahresabschluss, via NorthData), up from 92 (FY2023); LinkedIn: 51-200, 145 associated members (82 in Austria, 17 in the US) |
| Revenue (FY2024) | **UNVERIFIED.** Not published. Austria-Forum (c. 2018) gave "knapp 4,5 Millionen Euro"; Similarweb estimates $10-15M. Balance sheet total of Intact GmbH grew from €6.7M (2023) to €11.3M (2024) |
| Profitability | **UNVERIFIED.** No profit figure visible on NorthData or wirtschaft.at (paywalled). 2026 reviews report repeated layoffs "aufgrund der wirtschaftlichen Rahmenbedingungen" - **BORDERLINE** |
| Ownership | PE-backed. Majority owned since 30 Sep 2024 by CGE Partners (European mid-market fund) and Five Arrows (Rothschild & Co); IMCap Partners and management hold minorities. Held via Intact Holding GmbH (formerly Sagitta BidCo Holding GmbH, FN 628563h), 100% owner since Feb 2026 |
| Software-centric | Pure B2B SaaS / on-prem software vendor (Intact Platform) - **PASS** |

### Key People

- **Thomas Lorber** - co-founder and long-time CEO; still listed as Geschäftsführer in the Firmenbuch.
- **Michael Schunder** - Geschäftsführer of Intact GmbH since 17/24 April 2026 (Firmenbuch), and of the holding. Arrival coincides with the 2026 restructuring described in reviews.
- **Markus Friesacher** - Prokurist.
- **Fabian** (CPO), **Nishya** (Head of Data & AI), **Armin** (CRO) - first names only, from current job postings.
- **Jochen Kleboth** - Head of Data, Analytics and AI in the SoftwareOne case study (earlier period).

### Funding History

| Date | Event | Amount | Valuation |
|---|---|---|---|
| 2018 | IMCap Partners acquires majority | Undisclosed | Undisclosed |
| 30 Sep 2024 | CGE Partners + Five Arrows acquire majority from IMCap (advisers: Arma Partners, Baird) | Undisclosed | Undisclosed. Intact Holding GmbH balance sheet total €118.9M (2024) suggests an enterprise value of roughly €100M+ (inference) |

### Business Model

Intact sells a modular platform (formerly "Ecert") used by certification bodies, scheme owners and accreditation bodies to plan audits, run them, manage non-conformities, issue certificates and invoice. Claimed scale: 10M+ audits, 50K+ auditors, 160+ countries, 3K+ standards, "more than 100 TIC organizations". Named customers include TÜV SÜD, IAQG, MSC, Kiwa, USDA. About 90% export, roughly a third of revenue from the US (Austria-Forum, c. 2018). Delivered both cloud and on-premise, with "hundreds of per-tenant databases" (DevOps posting).

Not consulting: engineers build the company's own product. There are implementation specialists and project managers on the customer side, but no consultant career track or billable-hours model.

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **Intact GmbH** (Austria) | Firmenbuch FN 218078d, LG Graz | Parkring 6, 8403 Lebring, Austria | "Entwicklung von Kontrollsystemen" |
| **Intact Holding GmbH** (Austria) | Firmenbuch FN 628563h | Parkring 6, 8403 Lebring (previously Vienna) | "Beteiligungsverwaltung" |
| **Intact US, Inc.** | US | 401 N. Michigan Ave, Suite 1300, Chicago | US subsidiary |
| **Intact Switzerland GmbH** | Swiss register | Riedli 2, Brüttelen | Swiss subsidiary |
| German entity | **None found** | - | - |

NorthData's German register search for "Intact GmbH" returns only unrelated firms (INTACT GmbH Hamburg, sanotact Münster, etc.). The Legal Notice lists only the Austrian GmbH and the US Inc. LinkedIn's location list shows Germany only as "Intact Sales Partner Global, Tutzing 82327", which is a sales partner, not an employing entity.

Engineering postings (Senior Platform Engineer, Senior Product Designer, etc.) are listed on LinkedIn as "DACH (Remote)" and promise "100% remote work option within the location scope of this role". The careers page names the employer for at least one role as "Intact Austria". For a German resident this means either an Austrian contract with German social-security registration, or an Employer of Record. Neither is stated.

**Verdict:** **FAIL** (no German entity; remote-from-Germany is possible but the contracting setup is unverified)

---

## Section 3: Office Location

- **Office address:** Parkring 6, 8403 Lebring-Sankt Margarethen, Bezirk Leibnitz, Styria, Austria (Legal Notice; Nominatim resolves the address to an "Intact" building at 46.8514, 15.5268). Second Austrian location: "Intact Vienna" (LinkedIn, no street address). No office in Munich or anywhere in Germany. Lebring is about 25 km south of Graz, roughly 4.5 hours by car from Munich.
- **Nearest public transport (Overpass):** Lebring rail halt, ~630 m (on the Graz - Spielfeld-Straß Südbahn line; OSM carries no line tags for it). Bus stops "Lebring Mittelschule" ~470 m and "Sankt Margarethen Schule" ~520 m.
- **Work model:** Flexible working hours, flextime, and "100% remote work option within the location scope of this role" in all current engineering postings; LinkedIn lists these roles as "DACH (Remote)". Kununu confirms Homeoffice (86% of reviewers list it as a benefit). Remote eligibility is restricted to the DACH region for the platform roles.

---

## Section 4: Reviews

**GPTW:** No Great Place to Work certification found for Intact GmbH in Austria or Germany. GPTW hits for "Intact" belong to Intact Software (Ireland/UK) and Intact Technology (US), which are different companies.

### Glassdoor

Glassdoor profile EI_IE1184292 (Lebring-Sankt Margarethen HQ) is the correct company. It holds only **2 reviews** (2016, 2023). Its interview tab (39 interviews) is contaminated with Intact Financial data (it mentions "Insurance Sales Agent" and "Senior GRC Specialist" roles). Retrieved via Chromium/CDP.

| Metric | Global | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | 4.1 (2 reviews) | N/A (no reviews) | N/A | N/A |
| **WLB** | 4.0 | - | - | - |
| **Culture & Values** | 4.3 | - | - | - |
| **Comp & Benefits** | 4.0 | - | - | - |
| **Career Opportunities** | 4.1 | - | - | - |
| **Diversity & Inclusion** | 4.3 | - | - | - |
| **Senior Management** | 3.9 | - | - | - |
| **% Recommend** | 86% | - | - | - |
| **CEO Approval** | Not shown | - | - | - |
| **Business Outlook** | 85% positive | - | - | - |

Two reviews from 2016 and 2023 are not a usable signal, and they predate the PE acquisition and the 2026 restructuring.

### Kununu

Profile: `kununu.com/at/intact-consult1` ("Intact GmbH, Lebring", legacy slug from the former name Intact Consult GmbH). curl returned HTTP 405; retrieved via Chromium/CDP.

- **Overall score:** 3.9 / 5.0 (all-time, since 2011)
- **Recommendation rate (Weiterempfehlung):** 67% (last 2 years); 85% all-time
- **Total reviews:** 52 entries (43 employee reviews, plus applicant reviews)
- **Kununu Top Company:** NO
- **Sub-scores:** Karriere & Gehalt 3.8, Unternehmenskultur 3.8, Arbeitsumgebung 4.3, Vielfalt 4.2
- **Trend:** The 10 reviews since September 2025 average **3.3**, with 5 of 10 "Nicht empfohlen". The 5 reviews from April to October 2026 that include text average **2.2**, all "Nicht empfohlen"; the only positive 2026 reviews (5.0 March, 4.1 September) carry no text.
- **Salaries (7 entries):** Softwareentwickler:in Ø €65,500 (3), C# Entwickler:in Ø €63,200 (2), IT-Supporter Ø €42,200 (2), all Lebring.

### Blind / Teamblind

`teamblind.com/company/Intact` is Intact Financial (Toronto, 10,000+ employees, 3.3 from 43 reviews). No Blind profile exists for Intact GmbH. A Blind "Intact layoffs" thread refers to the Canadian insurer. **UNAVAILABLE.**

### Review Themes (2023-2026)

**Positives:**

- Work-life balance and flexibility, consistently, even in negative reviews: "Work-Life-Balance: sehr gut" (Kununu, Oct 2026, Angestellte/r oder Arbeiter/in, Lebring, current); "Die Work-Life-Balance war insgesamt positiv. Homeoffice war möglich" (Kununu, Jul 2026, Ex-Angestellte/r oder Arbeiter/in, Lebring).
- Strong peer cohesion: "Die Zusammenarbeit im Team ist sehr gut." (Kununu, Jun 2026, Angestellte/r oder Arbeiter/in, IT, Lebring, current); "Der Zusammenhalt ist enorm" (Kununu, Jul 2023, Marketing / Produktmanagement, Lebring, former).
- Niche market leadership and meaningful domain: "Leider nicht sehr bekannt obwohl Marktführer in der Branche" (Kununu, Oct 2026, Angestellte/r oder Arbeiter/in, Lebring).
- Good equipment and office: "Sehr gut ausgestattete Büros, gute Verkehrsanbindung" (Kununu, Oct 2026, Angestellte/r oder Arbeiter/in, Lebring).
- Earlier years were positive: "Entwickelt Power Tools in einem spitzen Team mit geselligem Umgang und vielen Freiheiten für Mitarbeiter" (Kununu, Dec 2025, Angestellte/r oder Arbeiter/in, IT, Lebring, current; title only).

**Negatives:**

- **Repeated layoffs while management claims stability (layoffs, communication breakdown):** "Obwohl kommuniziert wird, dass die finanzielle Situation des unternehmens stabil ist, wurden weitere Personalmaßnahmen aufgrund der wirtschaftlichen Rahmenbedingungen angekündigt. Dies wäre bereits die dritte Entlassungsrunde in diesem Jahr." (Kununu, Jun 2026, Angestellte/r oder Arbeiter/in, IT, Lebring, current)
- **Silent firings:** "Mitarbeiter verschwinden teilweise von einem Tag auf den anderen. Dadurch entstehen Angst, Unsicherheit" (Kununu, Oct 2026, Ex-Angestellte/r oder Arbeiter/in, IT, Lebring, until 2026); "Teilweise erfuhr das Team erst, dass eine Person das Unternehmen verlassen hatte, weil sie plötzlich nicht mehr im internen Netzwerk auffindbar war." (Kununu, Jul 2026, Ex-Angestellte/r oder Arbeiter/in, Lebring)
- **Cold, disrespectful management:** "Kündigungen werden teilweise von heute auf morgen und ohne jegliche Empathie ausgesprochen." (Kununu, Oct 2026, Ex-Angestellte/r oder Arbeiter/in, IT, Lebring); errors "per E-Mail vor mehreren Mitarbeitenden und Führungskräften thematisiert ... als würde die betroffene Person öffentlich bloßgestellt" and "Informationen, die in einem vertraulichen Rahmen geteilt wurden, schienen später gegen Mitarbeitende verwendet zu werden." (Kununu, Jul 2026, Ex-Angestellte/r oder Arbeiter/in, Lebring)
- **No clear direction since the leadership change:** "Seit es keine klare Direktion mehr gibt, fehlt es an einer klaren Vision und Richtung." (Kununu, Oct 2026, Ex-Angestellte/r oder Arbeiter/in, IT, Lebring); "Fehlende Ownership, schwache Entscheidungsfähigkeit des Managements" (Kununu, Oct 2026, Angestellte/r oder Arbeiter/in, Lebring, current).
- **High churn:** "In meiner Abteilung ist fast niemand mehr von meinen Kolleginnen und Kollegen da" (Kununu, Apr 2026, Ex-Angestellte/r oder Arbeiter/in, Vertrieb / Verkauf, Lebring).
- **Pay below average, raises delayed:** "Eher unter Branchendurchschnitt" (Kununu, Oct 2026, Angestellte/r oder Arbeiter/in, Lebring); "Gehaltsanpassungen werden auch oft verschoben" (Kununu, Jul 2026, Ex-Angestellte/r oder Arbeiter/in, Lebring).
- **Long-standing weak strategic communication** predates the PE deal: "keine gute Kommunikation bei strategischen Themen" (Kununu, Feb 2023, Angestellte/r oder Arbeiter/in, IT, Lebring).

Several of these overlap with hard red flags: layoffs, silent firings, communication breakdown and fear-driven management. Two of the most damning reviews come from IT staff.

### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | Present in 2026: "Der Umgang der Vorgesetzten mit den Mitarbeitern ist sehr kalt und wenig wertschätzend." (Kununu, Oct 2026, IT, former); public shaming by email (Kununu, Jul 2026, former) |
| 24/7 Work Expectation | Not reported. Only "Teilweise kommt es zu längeren Arbeitszeiten." (Kununu, Jun 2026, IT, current) |
| Internal Surveillance | Not reported as tooling; one review says confidential conversations were later used against staff (Kununu, Jul 2026) |
| Fear-driven Management | Yes: "Dadurch entstehen Angst, Unsicherheit, weniger Motivation und zunehmend Misstrauen." (Kununu, Oct 2026, IT, former) |
| Communication Breakdown | Yes, multi-review, multi-year (2023 to 2026); "wenig Transparenz, wenig Vertrauen" (Kununu, Oct 2026, current) |
| Unpaid Overtime | Not reported; flextime is consistently praised |
| Silent Firings | Yes: people disappear from the internal network before any announcement (Kununu, Jul 2026 and Oct 2026) |
| Work-Life Balance issues | No; WLB is the most consistent positive, even in 1-2 star reviews |

**Risk level: HIGH.** This is not generic big-company bureaucracy (the company has about 100 people). It is a fresh, PE-era pattern (April to October 2026, after the September 2024 buyout and the April 2026 management change): multiple layoff rounds, abrupt and uncommunicated dismissals, and distrust of management. It is reported by IT and sales staff alike, so it is systemic rather than one team. WLB itself remains good.

---

## Section 5: Compensation

### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| Careers page (Nov 2026) | Senior Data Engineer | from €80,000 (Austria) | - | - | from €80K | posting |
| Careers page | Senior AI/ML Engineer | from €75,000 (Austria) | - | - | from €75K | posting |
| Careers page | Engineering Manager | from €76,216 (Austria) | - | - | from €76K | posting |
| Careers page | Senior Platform Engineer / DevOps | from €64,554 (Austria, KV minimum) | - | - | from €65K | posting |
| Careers page | Frontend Engineer | from €55,356 | - | - | - | posting |
| karriere.at (May 2026) | (Senior) AI Engineer | from €4,611/month × 14 = ~€64.6K | - | - | - | posting |
| Kununu | Softwareentwickler:in, Lebring | Ø €65,500 | - | - | - | 3 |
| Kununu | C# Entwickler:in, Lebring | Ø €63,200 | - | - | - | 2 |
| levels.fyi | Software Engineer | $61.6K median: **Intact Financial (Canada), not this company** | - | - | - | - |
| Glassdoor | - | Profile salary data mixed with Intact Financial; not usable | - | - | - | - |

All Austrian figures are minimums by law ("Überzahlung" is negotiable). For other locations the postings say "in line with local market conditions", so a Munich-based remote hire would negotiate separately. No German data points exist.

Munich reference (from earlier reports in this series): senior software engineer at large profitable corporates is typically ~€85-100K base, with 75th percentile around €100-110K.

### Equity / Stock

No equity is mentioned in any posting. PE-owned with management co-investment; a broad employee participation plan is not evident. Assume **no equity**.

### Verdict

**BELOW** (based on Austrian floors and Kununu averages). A Munich-indexed offer is possible in principle but unverified; the posted floors are €65-80K, and reviewers call pay "eher unter Branchendurchschnitt".

---

## Section 6: AI/ML & Tech Stack

### AI Strategy

Genuine, recent applied-AI investment, but early stage:

- **Intact Analytics** (launched 2020, "AI-powered") for anomaly detection on audit data, co-developed with SoftwareOne (formerly Crayon), validated on 4,562 food-safety recertification audits and published in *Food Control*. Used NLP/LLMs on free-text non-conformity descriptions (AWS listed as platform in the case study).
- A new **Data & AI team** (Head of Data & AI, Senior Data Engineer, Senior Analytics Engineer, Senior AI/ML Engineer) is being built from scratch: "There is no warehouse or metric catalogue yet." The CPO's AI/ML posting says the aim is "not to add AI features to an existing product" but to build an "intelligence layer": RAG, document understanding, agentic workflows, predictive models, MLOps, evaluation datasets.
- Platform roles mention "access control and tenant isolation for AI features" and AI-assisted engineering workflows.

This is applied, production-oriented AI engineering, not marketing. It is also fragile, given the 2026 layoffs.

### Tech Stack

Derived from the current careers page postings (primary), the expired karriere.at / usemimi posting for (Senior) AI Engineer (May 2026), Kununu salary titles, and the SoftwareOne case study.

| Category | Technologies |
|---|---|
| **Primary language(s)** | C#/.NET (established platform "IPF"; Kununu "C# Entwickler:in"; EM posting nice-to-have), TypeScript/React (frontend), Python (data and AI/ML) |
| **AI/ML** | Python, RAG (chunking, embeddings, re-ranking), vector DBs, LangChain/LangGraph, agentic workflows and function calling, MLflow, Langfuse, OpenTelemetry; Azure OpenAI / AI Search (nice-to-have), Databricks / Microsoft Fabric |
| **Cloud** | Azure (AI posting: "Python, Azure"); AWS (SoftwareOne analytics case study); move to "sovereign or regional hosting" planned |
| **Infrastructure** | Containers, IaC (Terraform or similar), OpenTelemetry observability, CI/CD, ISO 27001 |
| **Data** | PostgreSQL (hundreds of per-tenant databases), SQL; planned warehouse (Snowflake/BigQuery/Databricks/Fabric under evaluation), dbt, Airflow/Dagster, CDC (Debezium/DMS) |
| **Other** | Domain-driven design, OAuth 2.0/OIDC, RBAC/ABAC, OpenAPI, transactional outbox, event-driven messaging; on-prem deployments still supported |

**Summary:** C#/.NET-centric legacy SaaS platform (IPF) on PostgreSQL, being re-architected into a domain-driven, multi-tenant SaaS with a React front end. A new Python data and AI layer (RAG, agents, MLOps on Azure) is being built from a greenfield start. Applied production engineering in a compliance-heavy domain, not research.

---

## Section 7: Language

- Engineering postings (Platform, DevOps, EM, Frontend): "Fluent in English; German is a plus".
- Data and AI postings (Senior Data Engineer, Senior AI/ML Engineer): "Fluent English", German only as nice-to-have.
- **Exception:** the earlier (Senior) AI Engineer posting on karriere.at (May 2026) required "Very good German and English skills".
- Sales, contracts, HR and Head of Sales roles require German C1.
- Team composition: LinkedIn shows 82 of 145 members in Austria (72 in Styria), 17 in the US. International customers (90% export) make English the business language, but internal day-to-day communication at the Lebring HQ is very likely German. Most Kununu reviews are in German.

**Verdict:** **PASS** for current engineering/AI postings (English required, German optional); **CONDITIONAL** in practice, since the core team is Styrian and German-speaking.

---

## Section 8: Stability

### Financial Position

- Intact GmbH balance sheet total: €1.3M (2016), €3.0M (2018), €3.7M (2020), €6.2M (2022), €6.7M (2023), **€11.3M (2024)** (NorthData, from Firmenbuch Jahresabschlüsse). Employees 92 (2023), 98 (2024). FY2024 accounts filed 25 Aug 2025.
- Profit/loss and revenue: not visible without a paid extract. **UNVERIFIED.**
- Intact Holding GmbH (acquisition vehicle, ex Sagitta BidCo): balance sheet total **€118.9M** (2024), 13 employees. A large holding balance sheet over a ~100-person operating company is typical of a leveraged buyout; acquisition debt servicing would explain cost-cutting pressure (inference).
- Grant: €625,500 public funding (2020, Beihilfentransparenz).
- Reviews (2026) say management describes the finances as "stabil" while announcing cuts "aufgrund der wirtschaftlichen Rahmenbedingungen".

### Financial Runway

Not loss-making by any visible evidence and PE-owned with a mature customer base; a VC-style runway model does not apply. The relevant risk is **PE cost discipline** (headcount cuts, management turnover, eventual exit in ~2028-2030) rather than cash running out. Cash line: **UNKNOWN** (not visible on NorthData free tier; wirtschaft.at paywalled).

### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| H1 2026 (before June) | First and second layoff rounds | UNKNOWN | Kununu, Jun 2026 (IT): "bereits viele Entlassungen" |
| ~June 2026 | Third round announced | UNKNOWN | "Dies wäre bereits die dritte Entlassungsrunde in diesem Jahr" (Kununu, Jun 2026, IT) |
| Through Oct 2026 | Ongoing individual dismissals | UNKNOWN | "Viele Mitarbeiter werden entlassen" (Kununu, Oct 2026, IT, former) |
| Apr 2026 | Management change | - | Michael Schunder added as Geschäftsführer (Firmenbuch) |

No press coverage of these layoffs was found (TrueUp and news searches return only Intact Financial). Employee-reported only. The company is nonetheless hiring heavily for a platform rebuild (Nov 2026: ~13 open roles), which suggests a skills swap (legacy roles out, new platform/AI roles in).

### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | **UNKNOWN** (no evidence of one) | No mention in any Kununu review; the silent-dismissal reports suggest no effective council hearing (§105 ArbVG in Austria) |
| Collective agreement | **Sector (Austria): IT-Kollektivvertrag** for the Austrian GmbH (mandatory through WKO membership) | Postings cite "in Austria due to legal requirements from €64,554" (KV minimum). Does **not** apply to a Germany-based remote employee |
| European works council | N/A (too small) | - |
| Conflict signals | None found | - |

For a Germany-resident employee: no German entity, no Betriebsrat, no German Tarif. **Verdict: FAIL** (layoffs plus silent firings in 2026, no council found, PE-leveraged structure).

---

## Section 9: Regulated Industry

Intact itself is not a regulated entity, but it serves regulated and accreditation-bound customers (certification bodies, accreditation bodies, aerospace (IAQG), food safety, medical (TÜV SÜD Medical Health Services)). The platform has been "approved by 20+ accreditation & control bodies"; ISO 27001 and ISO 9001 certified. Postings mention "regulated, audit-ready environment", GDPR, EU AI Act. Practical impact: change control, audit trails and security-audit work, but no formal safety cases (no ISO 26262 / IEC 62304-style burden).

**Verdict:** **PASS** (moderate compliance overhead, no heavy regulation)

---

## Section 10: On-Call

- Senior Platform Engineer, DevOps: explicit: "Lead the incident process, including the on-call rota" and "On-call duties are compensated in line with local regulations".
- Other platform roles: "Enable squads to design, build, deploy, monitor, and operate reliable domain services end to end" (EM posting) points to "you build it, you run it", so squad engineers likely join a rota.
- AI/ML Engineer: no on-call mentioned; the earlier AI posting lists "Incident ownership: You analyze production issues, fix them sustainably".

**Verdict:** **CAUTION** (an on-call rota exists and is being formalised; exposure depends on the role)

---

## Section 11: Interview Process

Glassdoor EI_IE1184292 shows 39 interviews, but its summary mixes in Intact Financial roles (Insurance Sales Agent, GRC Specialist). The numbers below are **not reliable** for Intact GmbH.

| Metric | Value |
|---|---|
| Difficulty | 2.95 / 5 (Glassdoor; contaminated) |
| Positive experience | 54% (contaminated) |
| Average duration | ~15 days (contaminated) |
| Rounds | UNKNOWN |

Applications go by email to `karriere@intact-systems.com` or LinkedIn Easy Apply. LinkedIn shows "Company response time is typically 1 week". The AI/ML posting says "We care more about what you've built than about which frameworks you've used", which suggests an experience/design-led process rather than LeetCode, but this is **UNVERIFIED**.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | PASS: pure B2B SaaS / on-prem vendor for the TIC industry |
| Not consulting | PASS: own product; implementation specialists exist but engineers build the platform |
| Profitable | UNVERIFIED: no P&L visible; balance sheet growing; layoffs "aufgrund der wirtschaftlichen Rahmenbedingungen" |
| Employee count | ~98 (FY2024), 145 on LinkedIn |
| English-speaking | PASS for engineering/AI postings ("German is a plus"); HQ culture German-speaking |
| Local entity + engineering contracts | FAIL: no German entity; "DACH (Remote)" with unstated contracting setup |
| Location / work model | Lebring (Styria, Austria); 100% remote within DACH; no Munich office |
| Glassdoor | 4.1 from 2 reviews (2016, 2023): no signal |
| Kununu | 3.9 all-time, 67% recommend (2 yrs); 2026 text reviews avg ~2.2, all not recommended |
| Salary | BELOW: Austrian floors €65-80K; Kununu dev Ø €63-66K; no equity |
| AI/ML content | Strong on paper: greenfield Data & AI team, RAG/agents/MLOps in Python |
| Computer-language/Tech-stack | C#/.NET legacy + React; Python for data/AI; Azure + PostgreSQL |
| No on-call | CAUTION: on-call rota being set up for platform roles |
| WLB / Stability | WLB good; stability poor (three layoff rounds in 2026) |
| Works council / collective agreement | Austrian IT-KV for Austrian staff only; no Betriebsrat found; nothing for German remote staff |
| Regulated industry | PASS: compliance-heavy customers, not regulated itself |
| Review themes | Silent firings, fear, management distrust (2026); good peers and WLB |
| PE / exit risk | Leveraged buyout (Sept 2024); new management April 2026; exit likely within 3-5 years |

---

## Section 13: Verdict

**Exclude.** The Senior AI/ML Engineer role reads attractively, with a greenfield applied-AI layer, Python, English-first and fully remote within DACH. But the company around it does not meet the core criteria.

**Strengths:** Intact is a genuine niche market leader with a sticky, international customer base (10M+ audits, TÜV SÜD, IAQG, MSC, USDA). It is investing post-buyout in a domain-driven SaaS rebuild and a new Data & AI team, and the AI agenda (RAG over proprietary audit data, anomaly detection, agentic workflows, evaluation discipline) is concrete and product-embedded. Engineering postings are English-first with German optional, and work-life balance and flexible remote work are consistently praised even by unhappy reviewers.

**Hard blockers:**

1. **No German entity, no Munich office.** Intact operates only through the Austrian GmbH (FN 218078d) plus US and Swiss subsidiaries; the German "location" is a sales partner in Tutzing. A Munich-based hire would be a remote employee of a foreign company or an EOR, without a German Betriebsrat or Tarif.
2. **Systemic 2026 instability with silent firings.** Kununu reviews from April to October 2026, including two from IT, report three layoff rounds in one year, colleagues vanishing from the internal network before any announcement, empathy-free dismissals and fear. This coincides with the leveraged PE structure (holding balance sheet €118.9M over a ~€11M operating company) and the April 2026 management change.
3. **Compensation below the Munich bracket.** Posted Austrian floors for senior engineering are €64.5-80K, Kununu developer averages are €63-66K, and there is no equity, against a Munich senior large-company base of roughly €85-100K. "Local market conditions" for Germany is unquantified.

**Secondary concerns:** The platform is C#/.NET-centric, with Python confined to the new data/AI team. An on-call rota is being formalised for platform roles. Profitability is unverified. Glassdoor and interview data are effectively absent. Post-buyout PE exit risk remains within 3-5 years.

**Recommendation:** Do not pursue now. If the Senior AI/ML Engineer role is still of interest, three things would have to change first: (a) a German employment contract (own GmbH or a named EOR) with a Munich-market salary of at least the large-company bracket in writing, (b) evidence that the restructuring has ended, such as several 2027 Kununu reviews from IT staff that are positive again, and (c) confirmation that the AI role carries no on-call. Re-check Kununu in about six months.

---

## Sources

- [Intact - Legal Notice](https://intact-systems.com/legal-notice/) (Chromium/CDP)
- [Intact - Careers (all current postings, Nov 2026)](https://intact-systems.com/company/careers/) (Chromium/CDP)
- [Intact - Homepage](https://intact-systems.com/) (Chromium/CDP)
- [LinkedIn - Intact company page / About / Locations](https://www.linkedin.com/company/intact-gmbh/about/) (Chromium/CDP)
- [LinkedIn - Intact People (locations, functions)](https://www.linkedin.com/company/intact-gmbh/people/) (Chromium/CDP)
- [LinkedIn - Intact Jobs ("DACH (Remote)")](https://www.linkedin.com/company/intact-gmbh/jobs/) (Chromium/CDP)
- [NorthData - Intact GmbH, Lebring, FN 218078d](https://www.northdata.de/Intact+GmbH,+Lebring/218078d) (Chromium/CDP)
- [NorthData - Intact Holding GmbH, FN 628563h](https://www.northdata.de/Intact+Holding+GmbH,+Lebring/628563h) (Chromium/CDP)
- [NorthData - German register search "Intact GmbH"](https://www.northdata.de/search?query=Intact+GmbH&countries=DE) (Chromium/CDP)
- [wirtschaft.at - Intact GmbH (FN 218078d)](https://www.wirtschaft.at/u/218078d)
- [wirtschaft.at - Intact Holding GmbH (FN 628563h)](https://www.wirtschaft.at/u/628563h)
- [Firmenbuch / evi.gv.at - FN 218078d](https://www.evi.gv.at/f/218078d)
- [IMCap Partners press release (30 Sep 2024, PDF)](https://imcap-partners.com/wp-content/uploads/2024/09/Akquisition-INTACT_Pressemitteilung_300924_final_german.pdf)
- [POELLATH - advises Intact's management on sale](https://www.pplaw.com/en/transactions/poellath-advises-intacts-management-sale-cge-partners-and-five-arrows)
- [Shoosmiths - CGE Partners and Five Arrows majority acquisition](https://shoosmiths.com/insights/news/cge-partners-and-five-arrows-announce-majority-acquisition)
- [Heuking - advises Five Arrows and CGE Partners](https://www.heuking.de/en/news-events/latest-news/article/five-arrows-and-cge-partners-announce-majority-acquisition-of-intact-from-imcap-partners-with-support-of-heuking.html)
- [Stax - supports CGE Partners on Intact](https://www.stax.com/news/stax-supports-cge-partners-on-its-investment-in-intact-systems-in-partnership-with-five-arrows)
- [Rothschild & Co Five Arrows - Intact portfolio page](https://www.rothschildandco.com/en/five-arrows/corporate-private-equity/portfolio/intact/)
- [Baird - Intact sells majority stake](https://www.rwbaird.com/transactions/investment-banking/dealcard/6418/)
- [CB Insights - Intact Systems financials](https://www.cbinsights.com/company/intact-systems/financials)
- [Austria-Forum - Intact GmbH](https://austria-forum.org/af/Unternehmen/Intact_GmbH)
- [TU Graz Meet Hidden Champions 2023 - Intact presentation (PDF)](https://www.tugraz.at/fileadmin/user_upload/Events/Mhc2016/Praesentationen_Firmen_2023/Intact.pdf)
- [SoftwareOne case study - Intact Data & AI](https://www.softwareone.com/en/case-studies/global/information-technology/intact-data-and-ai) (Chromium/CDP)
- [BRCGS - Intact partner page](https://www.brcgs.com/partners/partner-organisations/intact/)
- [Kununu - Intact GmbH overview](https://www.kununu.com/at/intact-consult1) (Chromium/CDP; curl returned 405)
- [Kununu - Intact GmbH reviews (newest)](https://www.kununu.com/at/intact-consult1/kommentare?sort=newest) (Chromium/CDP)
- [Kununu - Intact GmbH salaries](https://www.kununu.com/at/intact-consult1/gehalt) (Chromium/CDP)
- [Kununu - search "intact"](https://www.kununu.com/at/search?q=intact) (Chromium/CDP)
- [Glassdoor - Intact (Lebring) overview](https://www.glassdoor.com/Overview/Working-at-Intact-EI_IE1184292.11,17.htm) (Chromium/CDP)
- [Glassdoor - Intact (Lebring) reviews](https://www.glassdoor.de/Bewertungen/Intact-Bewertungen-E1184292.htm) (Chromium/CDP)
- [Glassdoor - Intact (Lebring) interviews](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/Intact-Fragen-im-Vorstellungsgespr%C3%A4ch-E1184292.htm) (Chromium/CDP)
- [Glassdoor - company search "Intact GmbH"](https://www.glassdoor.com/Search/results.htm?keyword=Intact%20GmbH) (Chromium/CDP)
- [Teamblind - Intact (Intact Financial, not this company)](https://www.teamblind.com/company/Intact/) (Chromium/CDP)
- [levels.fyi - Intact (Intact Financial, not this company)](https://www.levels.fyi/companies/intact/salaries) (Chromium/CDP)
- [karriere.at - Intact GmbH jobs (expired postings with salaries)](https://www.karriere.at/jobs/intact) (Chromium/CDP)
- [usemimi - AI Engineer at Intact GmbH](https://usemimi.com/jobs/ai-engineer-at-intact-gmbh-mpcpwubk)
- [Great Place to Work Austria - Best Small & Medium Workplaces 2025](https://www.greatplacetowork.at/beste-arbeitgeber/europa/europes-best-workplaces-2025/best-small-and-medium-workplaces-in-europe)
- [Nominatim - Parkring 6, Lebring](https://nominatim.openstreetmap.org/search?q=Parkring+6,+8403+Lebring,+Austria&format=json&addressdetails=1)
- [Overpass API - transit stops near HQ](https://overpass-api.de/api/interpreter)
