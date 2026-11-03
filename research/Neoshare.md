# neoshare - Full Research Report

_Researched: 2026-11-02_

> **Critical Disqualifiers**
>
> 1. **Mass layoff in progress.** In late October 2026 neoshare announced a restructuring cutting ~40% of ~230 positions (~100 jobs), **mainly in software development** (Finanz-Szene 23.10.2026, Immobilien Zeitung 30.10.2026, bankstil.de 31.10.2026). The cooperative banks (Volksbanken) have exited as investors, and the 85%-owned brokerage subsidiary PTXRE GmbH filed for insolvency in self-administration in spring 2026.
> 2. **German required.** Every engineering posting (Java, Angular, Head of AI Engineering) requires fluent German and English.
> 3. **Java-centric.** Product backend is Java (Spring) and Node.js (NestJS) with an Angular frontend; Python is confined to the ML team.
> 4. **Loss-making, deteriorating.** Net loss grew from €0.7M (2021) to €9.3M (2024); revenue is not disclosed.
>
> The full report follows for completeness.

---

## 1. Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 2019 as Pecunia AG, later Neoloan AG, renamed neoshare AG (7 years) |
| Employees | ~230 before the October 2026 cut (bankstil.de); LinkedIn bracket 201-500 with 189 members; JobsPipe ~188 (Oct 2026). After a ~40% cut: **~130-140** |
| Revenue (FY2024) | **UNKNOWN**: not disclosed (HGB small-format filing). bankstil.de also notes revenue is not publicly available |
| Profitability | Net loss €9.32M (2024), €3.92M (2023), €1.33M (2022), €0.69M (2021). Losses widening every year - **FAIL** |
| Ownership | Private AG. Founder/CEO Nico Singer is majority shareholder; minority stakes held by four savings banks (Haspa, Sparkasse KölnBonn, Sparkasse Hannover, Kreissparkasse Ludwigsburg) plus S Wagnis- und Beteiligungskapital GmbH; a DACH family office and real-estate strategics (e.g. Pöttinger). Volksbanken exited in October 2026 |
| Software-centric | SaaS platform for commercial real estate and corporate lending (modules atrium, atlas, argus) - but the group also ran a brokerage (PTXRE), a valuation business (neoshare Real Estate GmbH, acquired L+P Immobilienbewertungs GmbH) and a debt-advisory team - **BORDERLINE** |

### Key People

- **Nico Singer** - founder, CEO, majority shareholder.
- **Christian Förster** - board member (Vorstand).
- **Dr. Andreas Muschter** - Deputy CEO (joined management December 2024, board from July 2025).
- **Jonas Hohmann** - board member.
- Board turnover since December 2024: Sascha Baran (left 12/2024), Dominik Wilcken (7/2025), Peter Bigelmaier (8/2025), Piotr Bienkowski (2/2026) all left the board. Latest register entry 07.10.2026 concerns the board (Förster, Singer).

### Funding History

| Date | Event | Amount | Investors |
|---|---|---|---|
| Nov 2023 | Strategic stake | undisclosed (combined 10%) | Hannoversche Volksbank, Volksbank Düsseldorf Neuss |
| Apr 2024 | Growth round | €19M | Volksbanken Raiffeisenbanken group and a DACH family office (co-leads); Pöttinger real estate group and other strategics |
| Dec 2024 / Jan 2025 | Capital increase | undisclosed (stakes equal to the Volksbanken) | Haspa, Sparkasse KölnBonn, Sparkasse Hannover, Kreissparkasse Ludwigsburg |
| 2024 total | Capital inflow | ~€23.8M (bankstil.de) | |
| Oct 2026 | Investor exit | - | Volksbanken withdraw |

Share capital rose from €2.75M to €4.06M (April 2025) per the register. No valuation published.

### Business Model

A B2B "Adaptive Platform" that models real estate objects, borrowers and corporate structures independently of a single process: **atrium** (corporate lending origination to portfolio management), **atlas** (location analysis, value indexing, benchmarking), **argus** (shareholder/ownership structures from registers). Customers are banks (the savings and cooperative bank groups were meant to be anchor users), real estate companies and project developers. Around the SaaS core the group built transaction services: a brokerage (PTXRE, now insolvent), property valuation (neoshare Real Estate GmbH) and debt advisory. bankstil.de's October 2026 commentary argues that revenue, product maturity and customer value were never transparently demonstrated, and that the bank-group backing substituted for a proven business model.

### Software-Centric Assessment

The core product is genuine SaaS, and the job postings show a real engineering organisation (Java/NestJS backend, Angular micro-frontends, a 15-20 person ML team). However, revenue composition is unknown and a meaningful part of the group was transaction services (brokerage, valuation, debt advisory). The October 2026 cut falls primarily on software development, so the engineering share of the company is shrinking. **BORDERLINE**.

### Consulting-Adjacency Assessment

Not a consulting firm. The registered purpose includes "IT-, Beratungs- und sonstige Dienstleistungen", and the April 2024 funding announcement mentions a consulting team for debt advisory, but engineers build the internal product, not client deliverables. Low concern for engineering roles.

---

## 2. Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **neoshare AG** | HRB 121485, Amtsgericht Köln (previously HRB 253548, Amtsgericht München); VAT DE328043531 | Mommsenstraße 6, 80805 München | "Die Entwicklung, die Bereitstellung, der Vertrieb und der Betrieb von Plattform- und Software-as-a-Service-Lösungen zur Vermittlung, Umsetzung, Verwaltung und/oder Abwicklung von Finanzierungen und/oder Transaktionen oder zur Optimierung von Geschäftsprozessen sowie die Erbringung von IT-, Beratungs- und sonstigen Dienstleistungen ..." |

The registered seat moved to Cologne in December 2024 (register court Köln), while the Impressum and NorthData both give the operating address as Mommsenstraße 6, Munich. The purpose explicitly covers development and operation of SaaS platforms, so it is not a sales shell. Job postings are issued by neoshare AG for Munich with permanent full-time contracts. Subsidiaries: neoshare Bulgaria Ltd (Sofia, engineering), neoshare Real Estate GmbH, PTXRE GmbH (85%, insolvent).

**Verdict:** PASS (the restructuring is assessed under Stability, not here)

---

## 3. Office Location

- **Office address:** Mommsenstraße 6, 80805 München (Biederstein quarter, Schwabing, district Schwabing-Freimann; confirmed by Nominatim). Other sites: Düsseldorf, Frankfurt, Berlin, Sofia.
- **Nearest public transit (OSM Overpass):** U6 Dietlindenstraße (~720 m straight-line), U3/U6 Münchner Freiheit (~970 m), U6 Nordfriedhof (~1.05 km). Bus 59 stop Osterwaldstraße ~320 m walk (per MVG).
- **Work model:** Hybrid with flexible working hours, plus limited workation (September 2026 Angular posting). 74% of Kununu reviewers confirm home office. Number of office days not stated.
- **Verdict:** **STRONG PASS** (comparable to the Leopoldstraße benchmark).

---

## 4. Reviews

**GPTW:** No Great Place to Work certification or listing found for neoshare (greatplacetowork.de search and web search).

### Glassdoor

Glassdoor employer profile E9712685 exists but has **no employee reviews** ("Noch keine Bewertungen", fetched via CDP). Country, city and SWE filters therefore return nothing. The salary FAQ shows a Comp & Benefits sub-score of 2.4 (presumably from salary submitters; sample unknown). The "5.0" shown in LinkedIn's job-card integration is not backed by any visible review.

| Metric | Global | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | none (0 reviews) | none | none | none |
| **WLB** | - | - | - | - |
| **Culture & Values** | - | - | - | - |
| **Comp & Benefits** | 2.4 (sample unknown) | - | - | - |
| **Career Opportunities** | - | - | - | - |
| **Diversity & Inclusion** | - | - | - | - |
| **% Recommend** | - | - | - | - |
| **CEO Approval** | - | - | - | - |
| **Business Outlook** | - | - | - | - |

### Kununu

Fetched via CDP (curl returned HTTP 405).

- **Overall score:** 3.7 / 5.0 (23 reviews since 2024; matches the Finance sector average 3.7)
- **Recommendation rate:** 55% (last 2 years); 70% shown on the review list
- **Total reviews:** 28 (23 employee reviews)
- **Sub-scores:** Karriere & Gehalt 3.7, Unternehmenskultur 3.6, Arbeitsumgebung 4.1, Vielfalt 3.9
- **Kununu Top Company:** NO
- **Trend:** Sharply bimodal and worsening. 2024 reviews are mostly 4.5-5.0 (several from leadership roles, one ex-reviewer alleges positive reviews were solicited to polish the image). From December 2024 on, detailed reviews are 1.8-2.2: Dec 2024 (2.2), Apr 2025 (2.1), Feb 2026 (1.9), Mar 2026 (2.2), Oct 2026 (1.8, titled "Toxische Führungskräfte, die die Schuld immer bei anderen suchen"). Short 5.0 reviews in Oct 2025 and May 2026 carry no text.

### Blind / Teamblind

No company page (teamblind.com/company/neoshare returns 404). Not covered.

### Review Themes (2024-2026)

**Positives:**
- Strong cohesion within direct teams ("Der Zusammenhalt unter direkten Kolleg*innen war das Highlight", Mar 2026; similar in Feb 2026 and 2024 reviews).
- Pleasant, modern office with terrace, good transit, dog-friendly (several reviews, 70% confirm dogs allowed).
- Working hours generally respected ("Work-Life-Balance ist grundsätzlich okay, da die Arbeitszeiten meist eingehalten werden", Mar 2026).
- Pay described as above market ("Das Gehalt liegt über dem marktüblichen Bereich", Mar 2026; "eher hohes Gehaltsniveau", Jul 2024).

**Negatives:**
- **Leadership quality** is the dominant theme: "autoritär und herablassend: viel Druck, wenig Orientierung" (Feb 2026); "Kontrolle über Vertrauen ... C Level glänzt durch mangelnde Erfahrung" (Mar 2026); "Toxische Führungskräfte" (Oct 2026).
- **Communication breakdown:** "In Neoshare ist 'Kommunikation' praktisch ein Fremdwort" (Feb 2026); "Kommunikation erfolgt gar nicht und wird auch seitens C Level nicht gewünscht" (Mar 2026). Even a positive manager review (Apr 2025) asks for more strategy information from the board.
- **Erratic priorities and chaos:** "Entscheidungen und Prioritäten wechselten im Wochentakt, teils im Tagesrhythmus" (Feb 2026); "Fehlende Prozesse ... führen zu Chaos und häufigen Doppelarbeiten. Eine Investorengeldverbrennungsanlage" (Mar 2026).
- **Push-outs and hire-and-fire:** "Mehrere Mitarbeitende berichten, dass sie gezielt aus dem Unternehmen gedrängt wurden" (Apr 2025); "Hire and Fire ... Angst herrscht wer als Nächstes geführt wird" (Dec 2024).
- **High turnover, loss of experienced staff:** "ein Großteil der erfahrenen Mitarbeitenden ... gegangen" (Feb 2026); "kaum erfahrene Mitarbeitende ... da die Fluktuation relativ hoch ist" (Mar 2026). Matches the board churn in the register.
- **No career development:** "Weiterentwicklung ist faktisch nicht möglich" (Mar 2026), echoed Feb 2026.
- **Spending culture:** "Alle fahren fette Autos aus Kosten der Investoren, man trinkt Champagner" (Dec 2024).

Overlap with hard red flags: toxic leadership, communication breakdown, silent firings, and now layoffs.

### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | **Present, recurring 2024-2026.** "Führung bedeutet hier häufig Machtdemonstration statt Unterstützung" (Mar 2026); "narzisstische Unternehmenskultur" (Apr 2025); "Toxische Führungskräfte" (Oct 2026). Criticism targets the board/C-level specifically |
| 24/7 Work Expectation | Not reported. Hours described as generally within limits |
| Internal Surveillance | Not reported. "Kontrolle über Vertrauen" refers to management style, not tooling |
| Fear-driven Management | **Present.** "Angst herrscht wer als Nächstes gefeuert wird" (Dec 2024); "Atmosphäre aus Unsicherheit, Misstrauen und permanenter Reibung" (Feb 2026) |
| Communication Breakdown | **Present, multiple reviews.** Quotes above; the company's own responses cite newly introduced townhalls and newsletters as remedies |
| Unpaid Overtime | Not reported |
| Silent Firings | **Present.** "gezielt aus dem Unternehmen gedrängt" (Apr 2025); "teils freiwillig, teils durch die Umstände" (Feb 2026) |
| Work-Life Balance issues | Mild: hours fine, but mental load spills into free time ("dass man es nicht einfach nach Feierabend 'abschalten' konnte", Feb 2026) |

**Risk level: HIGH.** This is (a) systemic and top-down: the complaints name the board, span three years and several functions, and line up with objective signals (four board departures in 14 months, subsidiary insolvency, 40% layoff). It is not large-company bureaucracy, and the praise is limited to peer cohesion inside teams.

---

## 5. Compensation

### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| Kununu | Data Scientist (Munich) | ~€76K | - | - | ~€76K | 2 |
| Kununu | Führungskraft (Munich) | ~€80K | - | - | ~€80K | 2 |
| Kununu | IT Spezialist:in (Munich) | ~€50K | - | - | ~€50K | 2 |
| Glassdoor | Senior UX Researcher | €78-83K | - | - | €78-83K | 1 |
| Glassdoor | Transaction Manager | €78-83K | - | - | €78-83K | 1 |
| levels.fyi | - | no company page (HTTP 405 / not listed) | | | | 0 |
| Job postings | - | not disclosed; "performance-driven, above-average compensation" | | | | - |

No Senior Software Engineer data points exist. Munich percentiles not available for this company.

### Equity / Stock

No employee equity programme is advertised. Private AG controlled by the founder; any VSOP would be illiquid and, given widening losses, a restructuring and an investor exit, of speculative value.

### Verdict

**UNVERIFIED.** The sparse data (€76-83K for senior non-engineering and data roles) sits at or slightly below the average bracket of large, profitable Munich corporations for senior engineers. Reviewers describe pay as above market, but sample sizes are tiny.

---

## 6. AI/ML & Tech Stack Fit

### AI Strategy

neoshare markets itself as an "AI-First Company". Concrete evidence: "AI-gestützte Datenerfassung" turning loan and property documents into structured data; a 15-20 person ML team described in the Head of AI Engineering posting as "research-heavy" and to be turned into a "high-throughput, production-grade organization"; plans for an LLM gateway (multi-provider routing across OpenAI, Gemini, Bedrock), RAG pipelines, LLMOps/MLOps and evaluation. The 2025 savings-bank capital was earmarked partly for "AI research". The October 2026 layoffs were publicly justified with AI progress, which press commentary called a convenient reading. A March 2026 reviewer from the research side complained that data-driven, validated input was unwelcome. Net: genuine applied GenAI work exists but is early-stage and its organisational standing is uncertain.

### Tech Stack

Derived from job postings (Head of AI Engineering on Personio, Java and Angular SWE postings on LinkedIn, September 2026). No engineering blog, GitHub organisation or StackShare profile found.

| Category | Technologies |
|---|---|
| **Primary language(s)** | Java (Spring, JDBC, SOAP/REST), Node.js/TypeScript (NestJS), TypeScript/Angular; Python only in the ML team |
| **AI/ML** | Python, PyTorch, LangChain/LlamaIndex or custom orchestration, Pinecone, Qdrant, FAISS, AWS Bedrock, OpenAI, Gemini; nice-to-have vLLM, TGI, Triton, ONNX Runtime |
| **Cloud** | AWS (Bedrock); hosting in Germany, ISO 27001, DORA claims on website |
| **Infrastructure** | Kubernetes, Terraform, CI/CD, event-driven microservices, API gateways |
| **Data** | Relational databases (JDBC), vector databases |
| **Other** | Angular Material, NgRx, Nx monorepo, Module Federation micro-frontends, TailwindCSS, Chart.js; OpenTelemetry, Prometheus/Grafana; MS Teams |

### Current Open Roles

Checked the Personio feed (neoshare.jobs.personio.de, 7 positions on 2026-11-02) and Glassdoor jobs.

| Role | Division/Team | Level | Key Tech | Link |
|---|---|---|---|---|
| Head of AI Engineering (f/m/x) | AI/ML & Data | Head (10-15 yrs; manages 15-20) | Java/NestJS architecture, Python, LLM gateway, RAG, AWS Bedrock, K8s | [Personio 2635122](https://neoshare.jobs.personio.de/job/2635122?language=en) (also Berlin, Frankfurt) |

Other open positions are non-engineering (Data Protection & AI Governance Advisor, Managing Director Business Operations, two working-student roles). The LinkedIn postings for Senior Software Engineer - Java (4455711134, 4450820164) and Senior Software Engineer - Angular (4361055445), captured 2026-09-23, are **no longer on the Personio board** and should be treated as closed, consistent with cuts focused on software development.

---

## 7. Language

Postings are written in English (some in German), but all three engineering postings state German as essential: "Fluency in English and German are essential" (Angular), "You are fluent in German and English" (Java), "Fluent German and English for daily team collaboration, stakeholder management, and technical documentation" (Head of AI Engineering). Customers are German savings and cooperative banks, and roughly half of Kununu reviews are in German. There is an English-speaking component (Sofia team, English Kununu reviews).

**Verdict:** **FAIL** (German listed as a primary requirement for engineering roles)

---

## 8. Stability

### Financial Position

| Year | Net result (HGB) | Total assets |
|---|---|---|
| 2021 | -€0.69M | €2.53M |
| 2022 | -€1.33M | €4.77M |
| 2023 | -€3.92M | €13.7M |
| 2024 | -€9.32M | €29.2M |

31.12.2024 balance sheet (NorthData, filed 30.06.2026): cash €14.1M, intangible assets €11.0M (mostly capitalised development), deferred tax assets €2.8M. Revenue not disclosed. The 2024 accounts were filed 18 months after year-end; 2025 accounts are not yet public. Trend: **declining** (losses more than doubling yearly).

### Financial Runway

No external runway estimate found (searched NorthData, press, Crunchbase-type sources). Bottom-up model:

| Cost line | Annual estimate |
|---|---|
| Staff pre-cut (~230 × ~€85K fully loaded, blended Munich/Sofia) | ~€19.5M |
| Offices (Munich, Düsseldorf, Frankfurt, Berlin, Sofia), cloud, LLM APIs | ~€3M |
| Other opex (sales, events, legal, PTXRE support before insolvency) | ~€2M |
| **Total gross burn (pre-cut)** | **~€24.5M/year** |
| **Total gross burn (post-cut, ~135 staff)** | **~€15M/year** |

| Revenue source | Est. annual inflow |
|---|---|
| SaaS licences (bank and real estate clients), valuation and advisory fees | ~€8-12M (inferred from a €9.3M 2024 loss against ~€18-20M 2024 cost base; not disclosed) |
| **Total revenue offset** | **~€10M/year** |

| Scenario | Net burn | Cash at hand | Runway | Next round needed by |
|---|---|---|---|---|
| Optimistic (post-cut, revenue holds) | ~€4M/year | ~€8M | ~2 years | ~2028 |
| Base case (post-cut, revenue flat, severance costs) | ~€7M/year | ~€8M | ~1.1 years | ~late 2027 |
| Stress (revenue falls with CRE market and investor exit) | ~€11M/year | ~€5M | ~5-6 months | ~Q2 2027 |

Cash used: €14.1M at 31.12.2024 (NorthData). Cash at end of 2026 is **estimated** at €5-8M assuming 2025 losses of ~€10-12M and possible proceeds from the savings-bank stakes (Haspa register entries 2025/2026 suggest further capital movements; amounts unknown). The 40% cut itself signals that runway had become critical.

### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| Dec 2024 - 2026 | Individual exits / push-outs | unknown | Kununu: "Hire and Fire", "gezielt aus dem Unternehmen gedrängt" |
| Spring 2026 | PTXRE GmbH (85% subsidiary, brokerage) files insolvency in self-administration | subsidiary staff | neoshare had cut PTXRE's credit lines (IZ) |
| Oct 2026 | Restructuring | ~100 jobs, ~40% of ~230 | **Mainly software development**; justified with AI progress and the weak commercial real estate finance market; Volksbanken exit as investors |

### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | **NO evidence (UNKNOWN)** | No mention in 28 Kununu reviews, postings, press or web search |
| Collective agreement | **NONE found** | Postings advertise "performance-driven" pay, no tariff wording |
| European works council | N/A | |
| Conflict signals | None found | |

With no visible works council, a 40% cut can proceed with only the statutory minimum; combined with the documented push-outs this offers little protection.

**Verdict:** **FAIL**

---

## 9. Regulated Industry

The software serves BaFin-supervised banks for credit processes; the website lists ISO 27001 and DORA compliance, and neoshare as an ICT third-party provider to banks falls under DORA contractual and audit requirements. The AI Governance posting shows EU AI Act work (credit-related AI may be high-risk under Annex III). neoshare itself is not a regulated institution. Engineering impact: security reviews, audit trails, penetration tests and vendor audits from bank clients; moderate documentation overhead.

**Verdict:** CAUTION (moderate, indirect regulatory burden)

---

## 10. On-Call

The Head of AI Engineering posting explicitly requires organising sub-teams "with clear ownership, SLOs, and on-call" and defining incident response and runbooks. The Java and Angular postings did not mention on-call. As a SaaS platform serving banks under DORA, production support is likely.

**Verdict:** **CAUTION** (on-call explicitly planned for AI platform teams)

---

## 11. Interview Process

From Glassdoor (4 interview reports, last updated May 2025; fetched via CDP).

| Metric | Value |
|---|---|
| Difficulty | not displayed (too few reports) |
| Positive experience | 50% (50% negative) |
| Average duration | ~9 days (3 days for Senior Automation QA Engineer, 14 for Copy Writer) |
| Rounds | 2-3 (inferred) |

Reported stages: group interview (33%), presentation (17%), skills test (17%), one-on-one (17%), background check (17%). 67% applied online. Process appears experience- and presentation-based, not LeetCode-heavy. Sample too small to be reliable.

---

## 12. Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | BORDERLINE: SaaS core, but brokerage/valuation/advisory businesses and engineering being cut |
| Not consulting | PASS: product company (debt-advisory side business only) |
| Profitable | FAIL: €9.3M loss in 2024, losses widening |
| Employee count | ~230 shrinking to ~130-140 |
| English-speaking | FAIL: fluent German required in every engineering posting |
| Local entity + engineering contracts | PASS: neoshare AG, HRB 121485, Munich operating address, SaaS development purpose |
| Glassdoor | No reviews |
| Kununu | 3.7 (23 reviews), 55% recommend; recent detailed reviews 1.8-2.2 |
| Salary | UNVERIFIED: no SWE data; senior non-engineering €76-83K |
| AI/ML content | Moderate: LLM gateway/RAG plans, research-heavy ML team; GenAI cited as reason for cuts |
| Computer-language/Tech-stack | Java/Spring, NestJS, Angular; Python only in ML |
| No on-call | CAUTION: on-call explicitly planned for AI platform teams |
| WLB / Stability | FAIL: 40% layoff, subsidiary insolvency, investor exit, board churn |
| Works council / collective agreement | None found |
| Regulated industry | CAUTION: DORA/BaFin via bank clients, EU AI Act |
| Review themes | Toxic leadership, communication breakdown, push-outs, erratic priorities |
| Open roles | No Senior/Staff SWE role open; SWE postings withdrawn |

---

## 13. Verdict

**Exclude.** neoshare is not a viable target now, and nothing in the research suggests it will become one soon.

**Strengths:** The domain (structured data from lending documents, RAG, an LLM gateway) is interesting applied GenAI work, it has reputable savings-bank shareholders, and reviewers consistently praise peer cohesion and say pay is above market.

**Hard blockers:**

1. **Active mass layoff focused on engineering.** ~100 of ~230 jobs (~40%) are being cut in October 2026, "mainly in software development", alongside the Volksbanken exit and the PTXRE insolvency. Joining a company mid-way through cutting its own engineering team offers no long-term security.
2. **German is a primary requirement.** All engineering postings require fluent German for daily collaboration and documentation, which fails the English-first criterion.
3. **Unprofitable with worsening losses.** The net loss grew to €9.3M in 2024 against €14.1M cash at year-end 2024. The base-case runway after the cut is around one year before more capital is needed.
4. **Toxic leadership risk is HIGH.** Detailed Kununu reviews from 2024-2026 repeatedly describe an authoritarian, non-communicative board, push-outs and hire-and-fire. This is corroborated by four board departures in 14 months.

**Secondary concerns:** The company has no Glassdoor review base. No works council or collective agreement was found. Its bank clients bring DORA and AI-Act overhead. Revenue is undisclosed and filings are late (2024 accounts filed June 2026). Commentary describes the product's market traction as unproven.

**Recommendation:** Do not apply, and do not re-surface neoshare vacancies. Revisit only after a new funding round or a credible profitability path, demonstrably new leadership, and an English-first, Python-centric senior IC opening, all of which are unlikely in the next 12 months.

---

## 14. Sources

- [neoshare website](https://www.neoshare.com/)
- [neoshare Impressum](https://www.neoshare.com/impressum)
- [neoshare Personio job board (XML feed, 2026-11-02)](https://neoshare.jobs.personio.de/?language=en)
- [Head of AI Engineering posting (Personio)](https://neoshare.jobs.personio.de/job/2635122?language=en)
- [LinkedIn: Senior Software Engineer - Angular (4361055445)](https://www.linkedin.com/jobs/view/4361055445/) (captured 2026-09-23, now withdrawn)
- [LinkedIn: Senior Software Engineer - Java (4455711134)](https://www.linkedin.com/jobs/view/4455711134/) (captured 2026-09-23, now withdrawn)
- [LinkedIn: Senior Software Engineer - Java (4450820164)](https://www.linkedin.com/jobs/view/4450820164/) (captured 2026-09-23, now withdrawn)
- [NorthData: neoshare AG, HRB 121485 Köln](https://www.northdata.de/neoshare+AG,+K%C3%B6ln/HRB+121485) (via CDP)
- [Kununu: neoshare AG overview](https://www.kununu.com/de/neoshare) (via CDP)
- [Kununu: neoshare reviews](https://www.kununu.com/de/neoshare/kommentare) (via CDP)
- [Kununu: neoshare salaries](https://www.kununu.com/de/neoshare/gehalt) (via CDP)
- [Glassdoor: neoshare reviews](https://www.glassdoor.de/Bewertungen/neoshare-Bewertungen-E9712685.htm) (via CDP)
- [Glassdoor: neoshare interviews](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/neoshare-Fragen-im-Vorstellungsgespr%C3%A4ch-E9712685.htm) (via CDP)
- [Glassdoor: neoshare salaries](https://www.glassdoor.de/Gehalt/neoshare-Geh%C3%A4lter-E9712685.htm) (via CDP)
- [Glassdoor: neoshare interview review (IE)](https://www.glassdoor.ie/Interview/neoshare-Interview-E9712685-RVW94135865.htm)
- [levels.fyi: neoshare (not listed)](https://www.levels.fyi/companies/neoshare/salaries)
- [Teamblind: neoshare (404)](https://www.teamblind.com/company/neoshare)
- [Great Place to Work Deutschland search](https://www.greatplacetowork.de/?s=neoshare)
- [Finanz-Szene: Neoshare killt 100 Jobs (23.10.2026)](https://finanz-szene.de/fintech/neoshare-krasser-jobabbau-beim-prestige-fintech-von-sparkassen-und-volksbanken/)
- [Immobilien Zeitung: Volksbanken kehren Neoshare den Rücken (30.10.2026)](https://www.iz.de/unternehmen/news/-volksbanken-kehren-neoshare-den-ruecken-2000050043)
- [bankstil.de: Neoshare - Wenn der Verbundgedanke das Geschäftsmodell ersetzt (31.10.2026)](https://bankstil.de/neoshare-wenn-der-verbundgedanke-das-geschaeftsmodell-ersetzt/)
- [Konii: Presse-Statement der neoshare AG zur Insolvenz in Eigenverwaltung der PTXRE GmbH (18.03.2026)](https://www.konii.de/news/presse-statement-der-neoshare-ag-zur-insolvenz-in-eigenverwaltung-der-ptxre-gmbh/)
- [Europe Real Estate: neoshare Real Estate rebrands as PTXRE](https://europe-re.com/neoshare-real-estate-rebrands-as-ptxre-to-scale-advisory-business-and-expand-in-germany-s-big-7/74450)
- [Munich Startup: neoshare secures €19 million](https://www.munich-startup.de/en/141163/neoshare-secures-e19-million/)
- [Munich Startup: four savings banks join as shareholders](https://www.munich-startup.de/en/news/neoshare-four-savings-banks-join-as-shareholders)
- [Munich Startup: neoshare and GSK Stockmann partnership](https://www.munich-startup.de/en/105420/neoshare-gsk-stockmann-partnership/)
- [IT Finanzmagazin: Vier große Sparkassen beteiligen sich bei Neoshare](https://www.it-finanzmagazin.de/vier-grosse-sparkassen-beteiligen-sich-beim-muenchner-start-up-neoshare-220926/)
- [Presseportal: Sparkassen beteiligen sich bei neoshare](https://www.presseportal.de/pm/172537/5946095)
- [Presseportal: neoshare AG newsroom](https://www.presseportal.de/nr/172537)
- [Deutsche Börse: OTS Sparkassen beteiligen sich bei neoshare](https://live.deutsche-boerse.com/nachrichten/OTS-neoshare-AG---Sparkassen-beteiligen-sich-bei-neoshare-724996fe-a4c9-40a0-b8b8-71565b5cc52b)
- [Legal 500: GÖRG berät Sparkassen beim Einstieg bei neoshare](https://www.legal500.com/developments/press-releases/gorg-berat-sparkassen-beim-einstieg-als-neu-aktionare-in-die-neoshare-ag/)
- [Finextra: Volksbanken Raiffeisenbanken joins €19 million round](https://finextra.com/pressarticle/100517/volksbanken-raiffeisenbanken-joins-19-million-financing-round-in-neoshare)
- [Startbase: neoshare AG erhält 19 Millionen EUR](https://www.startbase.com/https:/www.startbase.com/news/neoshare-ag-erhaelt-19-millionen-eur-fuer-wachstum)
- [messe.tv: neoshare at EXPO REAL 2024](https://www.messe.tv/en/2024/expo-real/neoshare-digitalization-commercial-real-estate-loans)
- [CB Insights: neoshare](https://www.cbinsights.com/company/neoshare)
- [Dealroom: neoshare ag](https://datacommons.dealroom.co/companies/neoshare_ag)
- [JobsPipe: neoshare headcount (Oct 2026)](https://jobspipe.dev/hiring/neoshare.de)
- [Indeed: neoshare company page](https://de.indeed.com/cmp/Neoshare)
- [MVG routing API (locations/routes)](https://www.mvg.de/api/bgw-pt/v3/locations?query=Mommsenstra%C3%9Fe%206%2C%2080805%20M%C3%BCnchen) (curl)
- [Nominatim: Mommsenstraße 6, 80805 München](https://nominatim.openstreetmap.org/search?q=Mommsenstra%C3%9Fe+6,+80805+M%C3%BCnchen&format=json&addressdetails=1) (curl)
- [Overpass API (nearby stations)](https://overpass-api.de/api/interpreter) (curl)
