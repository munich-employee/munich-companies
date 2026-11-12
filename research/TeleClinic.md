# TeleClinic - Full Research Report

_Researched: 2026-11-12_

> **Critical Disqualifiers**
> 1. **Compensation is below the Munich large-corporation bracket.** Every senior engineering data point found (Glassdoor, Kununu) sits at roughly €70K-€94K base, with no bonus and only a small stock-option plan. The best single data point (€86K-€94K, n=1) is around the lower edge of what large, profitable Munich employers pay senior engineers.
> 2. **Silent-firing signals in 2026 Kununu reviews.** Former employees describe abrupt dismissals, immediate system lockout, departed colleagues being badmouthed afterwards, and "complete departments" let go overnight (Apr 2026, Jul 2026). No works council was found that would make this harder.
>
> The full report follows for completeness.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 2015 (company's own "About us"); GmbH articles of association dated 05.01.2016 (~10-11 years) |
| Employees | ~120 (company "About us"); LinkedIn: 51-200, 161 associated members; PitchBook: 91 |
| Revenue (FY2024) | ~CHF 11M (DocMorris: "doubled... to around CHF 11 million"). H1 2026: **€17.6M (+48% YoY)**; 9M 2026 roughly +40%. FY2025 not published separately; extrapolating from H1 2026 growth gives roughly €24-25M (**estimate**) |
| Profitability | TeleClinic: EBITDA positive since 2024, EBITDA doubled again in H1 2026; HGB net loss narrowed from -€11.8M (2021) to **-€1.38M (2024)**. Parent DocMorris: net loss CHF 134.4M (FY2025), adj. EBITDA positive for the first time in Q3 2026 (CHF 0.6M) - **BORDERLINE** (subsidiary near or at break-even, parent still loss-making) |
| Ownership | Wholly owned subsidiary (99.2% per NorthData) of **DocMorris AG** (SIX: DOCM, formerly Zur Rose Group), acquired 2021 for €43.5M (€38.6M cash, rest in shares) |
| Software-centric | Telemedicine platform (patient apps, doctor desktop app, e-prescription flow); the product is the software - **PASS** |

### Key People

- **Benedikt Luber** - Managing Director (co-MD since 2024)
- **Julian Simon** - Managing Director since Jan 2025 (previously Prokurist). NorthData lists a "Julian Dittel" as MD and former COO from Feb 2024. These may be the same person after a name change, but that is **UNVERIFIED**
- **Maximilian (Max) Müller** - former CEO (Mar 2022 - Mar 2024), left at his own request
- **Katharina Jünger** - co-founder and CEO until 2022; **Patrick Palacín** and **Reinhard Meier** - co-founders
- **Walter Hess** - DocMorris CEO (group level)

### Funding History

| Date | Event | Amount | Notes |
|---|---|---|---|
| 2016-2020 | Seed / early rounds | Undisclosed (small) | Founders plus angels; capital grew stepwise from €25K to ~€116K nominal per register history |
| 2021 | Acquisition by Zur Rose Group (now DocMorris) | €43.5M | €38.6M cash + shares; trade press called it a "record price" |
| Nov 2026 | TeleClinic acquires **Medi24** (Switzerland) from Allianz Partners | EV "low double-digit CHF millions" | Closing expected Dec 2026. Medi24 revenue roughly equal to TeleClinic's, so the combined unit nearly doubles revenue; both stay operationally separate in their home markets |

### Business Model

B2C and B2B2C telemedicine. Patients book video or chat consultations with ~6,500-7,000 affiliated doctors (paid per consultation; the doctors are not employees). Revenue comes from statutory health-insurer (GKV) reimbursement via KV billing, private patients and self-payers, and insurer partnerships. The strategic value to DocMorris is the e-prescription funnel: TeleClinic prescriptions can be routed to the DocMorris online pharmacy, which has drawn criticism and litigation from pharmacists and KVs. 1.3M treatments in H1 2026 (+51%).

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **TeleClinic GmbH** | HRB 223627, Amtsgericht München; USt-ID DE305174929 | c/o Design Offices München, Brienner Straße 45a-d, 80333 München | "Digitale Gesundheitsversorgung" (digital healthcare) |

TeleClinic GmbH is the operating company itself, not a sales shell of a foreign parent: the platform is built and run in Germany, and the job postings (Workday tenant `zrg/teleclinic-jobs`) hire directly into TeleClinic GmbH in München with German benefits (bAV company pension, JobRad, 30 vacation days). The registered purpose is brief but broad and covers the whole operating business. HR services are partly provided by DocMorris group infrastructure (a Dec 2025 Kununu reviewer asks for "ein In-House HR Team... statt der Nutzung der DocMorris-Infrastruktur"). No PEO/EOR is involved for Germany.

**Verdict:** **PASS**

---

## Section 3: Office Location

- **Office address:** TeleClinic GmbH, c/o Design Offices München, Brienner Straße 45a-d, 80333 München (Maxvorstadt, Kunstareal, St. Benno-Viertel). This is a coworking space (Design Offices), confirmed by the Impressum and NorthData. Nominatim geocodes it to 48.14655, 11.56189. The earlier registered address was Rüdesheimer Straße 5, 80686 München.
- **Nearest public transport** (Overpass, straight-line distances):
  - **Karlstraße** bus stop: ~190 m
  - **Königsplatz** U-Bahn station (U2/U8): ~200 m
  - **Stiglmaierplatz** tram stop: ~240 m; **Karlstraße** tram stop: ~260 m
  - **Stiglmaierplatz** U-Bahn station (U1/U7): ~390 m
  - **Hauptbahnhof Nord** tram stop: ~490 m; **München Hauptbahnhof** (S-Bahn trunk line, regional, long-distance): ~600 m
- **Work model:** **Remote-first / fully remote.** Careers page: "Remote-First", with two company-wide "Co-Working Weeks" per year (recent ones in Lisbon, Barcelona, Prague, Innsbruck, Berlin). Workday tags engineering postings as `remoteType: Remote` (#LI-Remote). Kununu (IT employee, Jul 2026): "100% Remote First. Bis zu 6 Monate aus dem EU-Ausland arbeiten und 2x3 Wochen auch außerhalb der EU". Core hours are 10:00-16:00. The Munich coworking space is optional. JDs say salaries are "aligned with the local market standards of your specific hiring country", so hiring outside Germany is possible, though some benefits are Germany-only.

---

## Section 4: Reviews

**GPTW:** No Great Place to Work certification found for TeleClinic or DocMorris Germany. No Kununu Top Company seal.

#### Glassdoor

Employer ID E1777443. Glassdoor shows 7 reviews on the German site (its FAQ text cites 15 in total). This is far too few for any filter to be meaningful.

| Metric | Global | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | 4.2 (7 shown / 15 counted) | ≤7 reviews, not separately reported | ≤7 reviews, not separately reported | 0-1 reviews (one iOS Engineer, 5.0) |
| **WLB** | 4.2 | - | - | - |
| **Culture & Values** | 4.3 | - | - | - |
| **Comp & Benefits** | 3.8 | - | - | - |
| **Career Opportunities** | 3.8 | - | - | - |
| **Diversity & Inclusion** | 4.4 | - | - | - |
| **Senior Management** | 4.1 | - | - | - |
| **% Recommend** | 90% | - | - | - |
| **CEO Approval** | not shown | - | - | - |
| **Business Outlook** | 76% positive | - | - | - |

All reviews are Munich-based or remote within Germany, so Global ≈ Germany ≈ Munich. **Directional only** (well under 20 reviews). Retrieved via CDP browser (WebFetch is not available in this session).

#### Kununu

Slug: `teleclinic2` (`teleclinic` returns 404). Retrieved via CDP browser (curl returned no data).

- **Overall score:** **3.9 / 5.0** (IT industry average 4.0)
- **Recommendation rate (Weiterempfehlung):** **68%** (last 2 years); 73% on the review list filter
- **Total reviews:** 133 (employee reviews: **86**, since 2017)
- **Sub-scores:** Karriere & Gehalt 3.8, Unternehmenskultur 3.9, Arbeitsumgebung 4.1, Vielfalt 4.3
- **Most-confirmed benefits:** Mitarbeiter-Events 83%, Flexible Arbeitszeiten 65%, Homeoffice 64%
- **Kununu Top Company:** **NO**

#### Blind / Teamblind

`teamblind.com/company/TeleClinic` returns "Page not found". No Blind presence (expected for a ~120-person German company).

#### Review Themes (2024-2026)

**Positives:**
- **Remote-first flexibility is real and consistently praised, even by critics.** "100% Remote First... Kernarbeitszeit 10 - 16 Uhr, flexibler Umgang mit persönlichen Termin und gelebte Vertrauensarbeitszeit. Besser kann man es in einem Angestelltenverhältnis wohl nicht umsetzen." (Kununu, Jul 2026, Angestellte/r oder Arbeiter/in, IT, München, current). The critical Apr 2026 reviewer agrees: "Flexible Arbeitszeiten, 100% Remote, keine Präsenzpflicht. Das ist real" (Kununu, Apr 2026, Ex-Angestellte/r oder Arbeiter/in, Vertrieb / Verkauf, München).
- **Transparency, as seen by tech staff.** "Das Unternehmen ist extrem datengetrieben und alle unternehmensrelevanten Daten (Finanzen, Nutzerzahlen, interne und externe Targets) können von jedem Mitarbeiter eingesehen werden." (Kununu, Jul 2026, Angestellte/r oder Arbeiter/in, IT, München, current)
- **Modern tooling and engineering autonomy.** "Du suchst dir deine Hard- und Software selbst aus, egal ob MacOS, Windows oder Linux... AI-Tooling mit Claude und Gemini top-modern und wirklich sehr üppiges Token Budget." (Kununu, Jul 2026, Angestellte/r oder Arbeiter/in, IT, München, current)
- **Tech teams describe good leadership.** "In den Tech/Product Missions habe ich es bisher durchweg als gut empfunden. Es gibt wenige Hidden Agendas" and "Man hört auf die 'einfachen Angestellten', auch wenn Führungskräfte kritisiert werden." (Kununu, Dec 2025, Angestellte/r oder Arbeiter/in, IT, München, current)
- **Mission and growth.** "The company is growing fast and shows no signs of slowing down... Fantastic team culture" (Glassdoor, Oct 2025, current Senior Product Designer, München)
- **Women in leadership** is mentioned positively across both platforms, including by critical reviewers.

**Negatives:**
- **Abrupt dismissals and badmouthing of people who left** (overlaps the silent-firings red flag). "Leute wurden plötzlich entlassen und verschwanden ohne sich zu verabschieden, im Nachhinein wurde über diese Kollegen komplett gelästert... Auch komplette Abteilungen werden von heute auf morgen gekündigt" (Kununu, Jul 2026, Ex-Angestellte/r oder Arbeiter/in, München, department not stated). "Der Zugang zu allen Systemen wird sofort und vollständig gesperrt... Wer geht, wird intern kurzerhand schlechtgeredet." (Kununu, Apr 2026, Ex-Angestellte/r oder Arbeiter/in, Vertrieb / Verkauf, München)
- **Micromanagement and inexperienced or external managers**, recurring since 2024 and mostly from non-engineering functions. "Absolutes Mikromanagement. Kontrolle pur." (Kununu, Jan 2026, former, München, role not stated). "Statt gute Leute im Team zu fordern und fördern, werden externe Personen in Führungsrollen gesteckt" (Kununu, Jan 2026, Ex-Angestellte/r oder Arbeiter/in, München, until 2025). "Little Training Unexperienced Bosses Micromanagement" (Glassdoor, Aug 2024, former Patient Support Specialist, München, 1+ year)
- **High pressure and daily progress checks** in at least one team. "Es wird viel abverlangt und kontrolliert durch hohe Zielvorgaben, tägliche status quo Abfragen" (Kununu, Feb 2026 updated, Ex-Angestellte/r oder Arbeiter/in, IT, München, until 2025)
- **Pay below market** (disputed). "Gute Arbeit wird nicht marktgerecht bezahlt. Stattdessen wird man immer auf später vertröstet." (Kununu, Jan 2026, former, München). A current IT employee counters: "Marktüblich, für fully remote sogar leicht überm Durchschnitt" (Kununu, Jul 2026)
- **Culture marketed better than it is lived.** "Das Image ist sorgfältig gepflegt und hat mit der gelebten Realität wenig zu tun." (Kununu, Apr 2026, Ex-Angestellte/r oder Arbeiter/in, Vertrieb / Verkauf)
- **Regulatory and legal friction** ("rechtliches Behörden-Ping-Pong", Kununu Jul 2026 IT reviewer), which tech teams describe as mostly absorbed by Legal/Ops.

Pattern: engineers (Kununu "IT" reviews, Dec 2025 and Jul 2026) are clearly positive. The severe complaints come mainly from sales/partnerships and support functions. The one negative IT review (Feb 2026) concerns a specific micromanaging manager.

#### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | **Present in parts of the org.** Jul 2026 ex-employee: "Die aktuelle Führung ist einfach nur respektlos"; Apr 2026: "Feedback wird nicht konstruktiv eingesetzt, sondern als Druckmittel." Tech reviewers report the opposite ("Durchweg Top, auch auf den höheren Ebenen", Jul 2026, IT) |
| 24/7 Work Expectation | Not reported. Core hours 10-16 and flexible time are consistently confirmed |
| Internal Surveillance | Not reported as tooling. "Daily status checks" by one manager (Feb 2026, IT) is micromanagement, not surveillance |
| Fear-driven Management | **Some signals.** "Wer in einem Feedbackgespräch hört, dass er 'jetzt richtig Gas geben muss' - nach wochenlanger Führungslosigkeit und mitten in der Probezeit - versteht schnell, wohin das führt." (Apr 2026, Vertrieb) |
| Communication Breakdown | **Mixed.** Strong routine transparency (KPIs and finances visible, Friday demos), but "Wenn es unangenehm wird - Führungswechsel, Kündigungen, Zieländerungen - herrscht entweder Schweigen" (Apr 2026). Glassdoor 2020: "Häufige Strategiewechsel und intransparente Kommunikation" |
| Unpaid Overtime | Not explicitly reported. "Es wird nur verlangt dass du mehr machst aber ohne dafür mehr Geld zu bekommen" (Jul 2026) is about workload versus pay |
| Silent Firings | **Yes, multiple signals in 2026.** Sudden dismissals during probation, immediate lockout, whole departments let go, ex-colleagues framed as "the problem" afterwards, and "so viele Klagen" (lawsuits) mentioned (Jul 2026). The employer response acknowledges "Trennungen" and offboarding complaints. This coincides with DocMorris's June 2026 AI-First cost programme |
| Work-Life Balance issues | Mostly positive. One former IT employee found balancing family hard because of "die vielen Meetings, hoher Pace, und die enge Kontrolle" (Feb 2026) |

**Risk level: MODERATE.** This is not systemic toxicity across the whole company: the engineering and product "missions" are consistently reviewed well, and reviewers describe C-level correcting middle management. There is **localized dysfunction** in sales, partnerships and support (external managers, micromanagement), plus a **company-level pattern in how separations are handled** (abrupt, lockout, no works council), which matters regardless of team.

---

## Section 5: Compensation

#### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| Glassdoor (DE) | Senior Software Engineer | ~€71K-€79K | n/a | none reported | ~€71K-€79K | 4 |
| Glassdoor (DE) | Senior Software Engineer (second entry) | ~€86K-€94K | n/a | n/a | ~€86K-€94K | 1 |
| Glassdoor (DE) | Senior Developer | ~€75K-€82K | n/a | n/a | ~€75K-€82K | 1 |
| Glassdoor (DE) | Senior iOS Engineer | ~€77K-€83K | n/a | n/a | ~€77K-€83K | 1 |
| Glassdoor (DE) | Software Engineer | ~€60K-€70K | n/a | n/a | ~€60K-€70K | 3 |
| Kununu | Softwareentwickler:in (München) | Ø €69.6K | n/a | n/a | Ø €69.6K | 5 |
| Kununu | Produktmanager:in (München) | Ø €82.7K | n/a | n/a | Ø €82.7K | 2 |
| levels.fyi | - | **UNAVAILABLE** (no TeleClinic company page; `levels.fyi/companies/teleclinic` returns 404) | | | | 0 |
| Job postings | Fullstack Engineer (Oct 2026) | Not disclosed: "Your dedicated recruiter will be happy to provide detailed information about the relevant salary bands prior to your first interview" | | | | - |

Munich reference percentiles for Senior Software Engineer: not retrieved from levels.fyi for this report (**UNVERIFIED**). Glassdoor's Comp & Benefits score is 3.8, and Kununu's Karriere & Gehalt is 3.8.

#### Equity / Stock

The benefits list "Möglichkeit zur Teilnahme am Mitarbeiterbeteiligungsprogramm (Aktienoptionen)", i.e. a stock-option plan, presumably on DocMorris shares (listed, SIX: DOCM, so liquid). A Dec 2025 Kununu reviewer also mentions the "Möglichkeit vergünstigt DocMorris-Aktien zu erwerben" (a discounted share purchase). Grant sizes are not disclosed. No reviewer cites equity as a meaningful share of pay. No bonus is mentioned in postings. Reviewers describe annual raises tied to individual yearly goals.

#### Verdict

All senior engineering data points cluster at **€70K-€94K base with negligible variable pay**. Large, profitable Munich employers typically pay senior software engineers roughly €85K-€100K+ base plus bonus and/or RSUs (general market reference, not from a single dataset). TeleClinic's median senior point (~€75K) sits well below that, and even its top data point only reaches the lower edge.

**BELOW**

---

## Section 6: AI/ML & Tech Stack

#### AI Strategy

- **AI-first engineering process, not an AI product company.** Current postings (Fullstack Engineer, QA Specialist, Oct 2026) describe an "AI-first development cycle" / "AI-SDLC" in which "AI writes the automated tests" and engineers "consistently leverage AI to build". A Jul 2026 Kununu IT reviewer confirms Claude and Gemini tooling with "sehr üppiges Token Budget". The posted role structure (one Architect, Full-Stack Engineers, QA) suggests a lean team amplified by coding agents.
- **Product AI is claimed but thinly evidenced.** The Medi24 announcement (Nov 2026) says Medi24 will get access to "der Plattform- und KI-Technologie von TeleClinic". A Glassdoor interview report shows a **Machine Learning Engineer** hiring process in Nov 2025, so ML roles have existed. No product page, paper or posting describing a specific model (triage, anamnesis, documentation) was found.
- **Group context:** DocMorris's "AI-First" strategy (Jun 2026) is primarily a cost programme (~100 FTE cut group-wide, ≥CHF 15M annual savings by end-2027) plus AI health assistants on the customer side.
- An open "Growth Automation & AI Manager" role is a marketing/growth automation position, not ML engineering.

Assessment: AI is used heavily as a **development tool** and is marketed as a platform capability. Genuine applied-ML/MLOps engineering appears to be small or occasional.

#### Tech Stack

Sources: TeleClinic's own tech-stack page (jobs.teleclinic.com/en/tech_stack), full Workday JDs (Fullstack Engineer JR04584, QA Specialist JR04585, Oct 2026), aggregator copies of 2025-2026 (Senior) Backend Engineer and Cloud Engineer postings, Glassdoor interview reports, Twilio case study, GitHub organisation mirror.

| Category | Technologies |
|---|---|
| **Primary language(s)** | **Python** (Django, Celery) backend; **TypeScript** (React, Vite, Electron, React Native) frontend/desktop; Kotlin/Jetpack Compose (Android); Swift/SwiftUI (iOS); Bash |
| **AI/ML** | AI coding agents (Claude, Gemini, NotebookLM); no ML framework named in any posting |
| **Cloud** | AWS (primary) |
| **Infrastructure** | Docker, Terraform, CloudFormation, GitLab CI, Bitrise (mobile CI); REST + WebSockets; video historically via Twilio / Jitsi (WebRTC) |
| **Data** | PostgreSQL, Valkey (Redis fork); "strong SQL skills and ORM" in JDs |
| **Other** | Datadog, Sentry, Grafana, CloudWatch, Firebase Crashlytics; Jest, Playwright, Cypress, Pytest; Jira, Confluence; Figma |

**Summary:** Python-centric (Django/Celery) backend engineering with a substantial TypeScript/React/Electron frontend and native mobile apps, on AWS with Postgres/Valkey and Terraform. Engineers own modules end to end, including infrastructure. AI shows up mainly as an AI-assisted development process; product-side ML is claimed but unverified. Applied production engineering in a regulated healthcare domain, not research.

---

## Section 7: Language

- Engineering JDs (Fullstack, QA, Backend, Cloud) are written in **English** and require "Fluent in English". None requires German.
- A Jul 2026 Kununu IT reviewer states: "Unternehmenssprache Englisch, Kollegen aus allen möglichen Ländern Europas". A Dec 2025 reviewer mentions "Kolleg:innen aus vielen verschiedenen Ländern mit unterschiedlichen Sprachen".
- Business-facing roles (Head of Doctor Partnerships, Product Manager roles) are posted in German and require "Deutsch auf Muttersprachen-Niveau", which is expected given KV/insurer stakeholders. Some product-side interviews (PM, 2025) were conducted in German.

**Verdict:** **PASS** (English for engineering; German helpful for close product/regulatory collaboration)

---

## Section 8: Stability

#### Financial Position

**TeleClinic GmbH (HGB single-entity accounts, via NorthData; values read from the page's chart data through CDP):**

| Year | Net result (Jahresfehlbetrag) | Balance sheet total |
|---|---|---|
| 2019 | -€3.63M | €3.7M |
| 2020 | -€8.34M | €6.7M |
| 2021 | -€11.8M | €5.9M |
| 2022 | -€9.74M | €18.0M |
| 2023 | -€4.83M | €23.1M |
| 2024 | **-€1.38M** | €27.6M |

Balance sheet at 31.12.2024: intangible assets €4.1M, receivables €5.4M, so cash is at most ~€0.4M. **Negative equity of €17.2M** ("nicht durch Eigenkapital gedeckter Fehlbetrag") and liabilities of €26.8M, almost certainly intercompany funding from DocMorris. TeleClinic is therefore **financed by the parent** and holds no meaningful cash of its own. The loss trend is sharply improving. DocMorris reports EBITDA-positive contributions since 2024, EBITDA doubling in H1 2026, and revenue €17.6M in H1 2026 (+48%), so TeleClinic is likely at or near net break-even in 2025-2026.

**DocMorris AG (parent, SIX: DOCM):**
- FY2025: external revenue CHF 1,185.7M; **net loss CHF 134.4M**; adj. EBITDA -CHF 48.2M.
- H1 2026: revenue CHF 599.2M (+13.4% LC); operating cash flow -CHF 21.1M (vs -55.7M); cash and equivalents CHF 69.2M (CHF 99.2M including current financial assets) at 30 Jun 2026, down from CHF 119.9M at YE2025.
- Q3 2026: adj. EBITDA +CHF 0.6M, the first positive quarter, ahead of the H2 2026 target. FY2026 revenue guidance raised (Capital Markets Day, 12 Nov 2026). Free-cash-flow break-even targeted "in the course of 2027".
- Financing: CHF 200-250M capital raise (2025), CHF 49.6M 2028 bonds placed Oct 2025 to buy back the 2026 convertible, further 2026 convertible repurchases in Jan 2026. Remaining 2026 convertible outstanding: **UNVERIFIED** (≤ CHF 73M by subtraction).

#### Financial Runway

TeleClinic has no standalone cash and depends on DocMorris, so runway is assessed at **group level** (listed company: cash line and guidance used instead of a full bottom-up model). For reference, a TeleClinic-level sketch:

| Cost line | Annual estimate |
|---|---|
| Staff (~120 × ~€85K fully loaded) | ~€10M |
| Doctor fees (variable, per consultation) | ~€15-18M (estimated from ~2.6M treatments/yr; **assumption**) |
| Marketing, cloud, video, legal, other | ~€5-7M |
| **Total gross cost** | **~€30-35M/year** |

| Revenue source | Est. annual inflow |
|---|---|
| Consultations (GKV via KV, private, self-pay), insurer partnerships | ~€35M (2026 run rate: H1 €17.6M × 2) |
| **Total revenue offset** | **~€35M/year** |

TeleClinic alone is roughly break-even to slightly positive at EBITDA level. Group-level scenarios:

| Scenario | Net burn (group operating cash) | Cash at hand | Runway | Next financing needed by |
|---|---|---|---|---|
| Optimistic | ~0 (FCF break-even reached early 2027 as guided) | CHF 99.2M | Indefinite | None |
| Base case | ~CHF 20-30M/yr (H1 2026 OCF annualised, improving) | CHF 99.2M | ~3-4 years | ~2029, or earlier if the 2026 convertible remainder and Medi24 consume cash |
| Stress | ~CHF 60M/yr (FY2025-like burn returns) | CHF 69.2M (excluding financial assets) | ~1-1.5 years | ~2027-2028 |

Cash figure: CHF 69.2M cash and equivalents / CHF 99.2M including current financial assets, DocMorris Half-Year Report 2026, as of 30 June 2026.

#### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| Jun 2026 | DocMorris "AI-First" acceleration | ~100 FTE group-wide | ≥CHF 15M annual savings by end-2027; CHF 4.3M one-off cost in Q2. Units not disclosed; impact on TeleClinic **UNVERIFIED** |
| ~H1 2026 | TeleClinic: departments and individuals let go (per Kununu reviews) | Unknown | "komplette Abteilungen werden von heute auf morgen gekündigt" (Jul 2026 review); leaders "verschwinden von heute auf morgen" (Apr 2026). Not covered by press |
| 2025-2026 | DocMorris German site closure (logistics moved to Heerlen, NL) | ~100 | Pharmacy logistics, not TeleClinic |

No public TeleClinic-specific layoff announcement was found (press, TrueUp-style trackers).

#### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | **UNKNOWN, likely NO** | No mention in 133 Kununu reviews (searched "Betriebsrat", "Tarif"), in postings, or in press searches for "TeleClinic Betriebsrat" / "DocMorris Betriebsrat". Reviewers describing dismissals mention lawyers and lawsuits, not a council |
| Collective agreement | **NONE found** | Postings say salaries are "determined based on objective and role-related criteria"; no "tarifgebunden" or AT language |
| European works council | **UNKNOWN** | DocMorris (~1,600 staff in DE, NL, ES, FR, CH) is below the EWC threshold in most member states; nothing found |
| Conflict signals | Employee lawsuits after dismissals mentioned in a Jul 2026 review ("brauchen sich nicht wundern das die so viele Klagen am Hals haben"); no union-busting reports found | Kununu |

No council and no agreement, combined with the 2026 silent-firing signals and the parent's cost programme, is the riskier combination identified in past reports.

**Verdict:** **CAUTION** (TeleClinic close to break-even and growing fast, but financed by a still loss-making parent that is cutting costs; separation practices are an active concern)

---

## Section 9: Regulated Industry

Telemedicine in Germany is heavily regulated, although TeleClinic is not a medical-device manufacturer for its core booking and video platform:
- Medical professional law (Berufsordnung, remote-treatment rules), KV billing rules and disputes with KVs (e.g. a KV Nordrhein dispute settled out of court), and political lobbying (TeleClinic is in the Bundestag lobby register).
- E-prescription and gematik Telematikinfrastruktur integration, data protection for health data (DSGVO Art. 9), patient-data security.
- Litigation risk around prescription routing to DocMorris (Landgericht Köln ruling, Apr 2026, on online prescriptions for ED drugs).
- Any product-side AI triage or anamnesis would risk MDR classification.

Practical engineering impact: compliance-driven quality gates ("high risk integration points given their compliance exposure", QA JD), legal back-and-forth that occasionally reaches tech ("rechtliches Behörden-Ping-Pong"), and "highly regulated environment, which can sometimes add complexity or slow processes down" (Glassdoor, Oct 2025, Senior Product Designer). Lighter than medical-device (IEC 62304) or banking (BaFin/DORA) engineering.

**Verdict:** **CAUTION** (moderate)

---

## Section 10: On-Call

- No posting found (Workday, aggregators) mentions on-call, Rufbereitschaft or pager duty.
- However, the platform is a 7-day consumer health service with ~1.3M treatments per half-year. Engineers are expected to be "comfortable owning the infrastructure your module runs on, including how it is distributed and operated in production" (Fullstack JD, Oct 2026), and the engineering team is small. Some form of production incident responsibility is therefore likely.
- One Kununu reviewer explicitly praises freedom from out-of-hours pressure (core hours 10-16).

**Verdict:** **UNVERIFIED** (no on-call stated; "you build it, you run it" ownership plus a small team makes it plausible). Ask directly in interviews.

---

## Section 11: Interview Process

| Metric | Value |
|---|---|
| Difficulty | 2.5 / 5 (Glassdoor) |
| Positive experience | 40% (50% negative) |
| Average duration | ~2-3 weeks (PM) to ~3 months (Backend Developer, Nov 2025) |
| Rounds | 5-6 for engineering |

Based on 10 Glassdoor interview reports (directional only):

- **Backend Developer (Nov 2025, rejected, negative):** (1) HR call, (2) technical interview about experience and current challenges, (3) **4-hour take-home**: "A simple Django application with CSV processing, expected to be 'production ready' with tests", (4) technical review of the task, then planned (5) team interview and (6) CTO/CEO. Long gaps (2-3 weeks) between rounds. The reviewer notes the same posting "keeps reappearing on LinkedIn every month" for 7+ months. Sample question: "How to optimise and scale DB on different levels?"
- **Machine Learning Engineer (Nov 2025, neutral):** three consecutive in-person interviews (technical; two PMs, behavioural; team).
- **Product Manager (Apr 2026, positive):** recruiter screen, hiring manager, 3-4h take-home business case, case review, team call, CPO.

**Experience- and design-focused with a practical take-home; not LeetCode-heavy.** The process is slow and candidates rate communication between rounds poorly.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | PASS: telemedicine platform, software is the product |
| Not consulting | PASS: own product, no client billing |
| Profitable | BORDERLINE: TeleClinic EBITDA positive since 2024, HGB net loss down to -€1.4M (2024); parent DocMorris net loss CHF 134M (2025), adj. EBITDA positive only since Q3 2026 |
| Employee count | ~120 (company); LinkedIn 51-200 |
| English-speaking | PASS: English company language for engineering |
| Local entity + engineering contracts | PASS: TeleClinic GmbH, HRB 223627 München, direct German employment |
| Location / work model | Fully remote-first; optional coworking at Brienner Str. 45 (Königsplatz U2/U8 ~200 m); 2 company weeks/year |
| Glassdoor | 4.2 overall, 90% recommend, but only 7-15 reviews (directional) |
| Kununu | 3.9, 68% recommend, 86 employee reviews; no Top Company |
| Salary | **BELOW**: senior engineers ~€70K-€94K base, no bonus, small stock-option plan |
| AI/ML content | Low-moderate: AI-first coding process (Claude/Gemini); product ML claimed, unverified |
| Computer-language/Tech-stack | Python/Django + TypeScript/React/Electron on AWS, Postgres, Terraform |
| No on-call | UNVERIFIED: none stated; production ownership expected |
| WLB / Stability | WLB strong (flexible, remote). Stability: fast growth, but dependent on a loss-making parent in a cost programme |
| Works council / collective agreement | None found |
| Regulated industry | CAUTION: telemedicine law, KV, e-prescription, health-data protection |
| Review themes | Engineers positive; 2026 reviews from other functions report abrupt dismissals, micromanagement, external inexperienced managers |
| Acquisition / integration risk | Medi24 acquisition closing Dec 2026 (doubles revenue, adds Swiss integration work); TeleClinic exists as a strategic e-prescription funnel for DocMorris, so priorities follow the parent |

---

## Section 13: Verdict

**Monitor; do not actively pursue unless a role comes with a senior/staff salary band confirmed up front.**

**Strengths:** TeleClinic is a real software product company and Germany's leading telemedicine platform. It is growing fast (+48% revenue H1 2026, 1.3M treatments per half-year) and expanding internationally (Medi24). It has moved from heavy losses to EBITDA-positive. The engineering setup is attractive on paper: a Python/Django and TypeScript stack on AWS, English as the working language, genuinely remote-first with flexible hours, generous AI-tooling budgets, end-to-end module ownership, and consistently positive reviews from engineers about transparency and tech leadership.

**Hard blockers:**
1. **Compensation.** All senior engineering data points (Glassdoor n=7, Kununu n=5) sit at €70K-€94K base with no bonus and an undisclosed, apparently minor stock-option component. That is below the €85K-€100K+ base plus bonus/RSU typical of large, profitable Munich employers for senior engineers. A staff-level band is not visible at all, and the posted engineering titles (Fullstack Engineer, Architect) suggest a flat ladder.
2. **Separation practices and silent-firing signals.** 2026 Kununu reviews describe abrupt dismissals (including during probation), immediate lockout, whole departments let go, departed colleagues badmouthed internally, and employee lawsuits. No works council or collective agreement was found to constrain this, and it coincides with the parent's ~100-FTE AI-First cost programme.

**Secondary concerns:**
- The parent DocMorris is still loss-making (net loss CHF 134M in 2025), only just reached adjusted-EBITDA break-even (Q3 2026), and holds CHF 69-99M of cash. TeleClinic has negative equity of €17M funded by intercompany loans, so its stability depends on the parent.
- Small engineering team running a 7-day consumer health platform with "own the infrastructure in production" expectations: on-call is plausible but unconfirmed.
- AI/ML depth is mostly AI-assisted development, not ML engineering.
- The hiring process is slow (up to ~3 months) with a 4-hour take-home, and backend postings have been reposted for months.
- Moderate regulatory friction (KV disputes, e-prescription litigation).
- Kununu 3.9 / 68% recommend is below the IT average, with a negative 2026 trend outside engineering.

**What would need to change for a positive recommendation:** a disclosed salary band at or above Munich senior/staff market rates (for example ≥€100K base for a staff-equivalent role), and clear answers on on-call and on how the 2026 separations were handled. If engaging anyway, verify in the first recruiter call: the salary band (the JD promises it before the first interview), whether a staff/principal level exists, on-call or incident rotation, where engineering sits in the DocMorris AI-First programme, and whether there is a Betriebsrat.

---

## Sources

- [TeleClinic Impressum](https://www.teleclinic.com/impressum/)
- [TeleClinic - About Us](https://www.teleclinic.com/en/about-us/)
- [TeleClinic Karriere (careers page, via CDP)](https://www.teleclinic.com/karriere/)
- [TeleClinic jobs portal (EN)](https://jobs.teleclinic.com/en)
- [TeleClinic Tech Stack page](https://jobs.teleclinic.com/en/tech_stack/Tech_Stack)
- [Workday - TeleClinic jobs (zrg tenant; JSON API via curl)](https://wd3.myworkdaysite.com/de-DE/recruiting/zrg/teleclinic-jobs)
- [Workday - Fullstack Engineer (m/f/d) JR04584](https://wd3.myworkdaysite.com/de-DE/recruiting/zrg/teleclinic-jobs/job/Mnchen/Fullstack-Engineer--m-f-d-_JR04584)
- [Workday - Quality Assurance Specialist JR04585](https://wd3.myworkdaysite.com/de-DE/recruiting/zrg/teleclinic-jobs/job/Mnchen/Quality-Assurance-Specialist--m-f-d-_JR04585)
- [Workday - Head of Doctor Partnerships JR04181](https://wd3.myworkdaysite.com/de-DE/recruiting/zrg/teleclinic-jobs/job/Mnchen/Head-of-Product---Doctor-Partnerships--m-w-d-_JR04181)
- [devjobs.de - TeleClinic (Senior) Backend Engineer](https://en.devjobs.de/job/6b858be9fc36b3ac634848c5019ce417)
- [WeAreDevelopers - (Senior) Backend Engineer](https://www.wearedevelopers.com/jobs/ext/5920395/senior-backend-engineer)
- [WeAreDevelopers - (Senior) Cloud Engineer](https://www.wearedevelopers.com/en/jobs/ext/5256516/senior-cloud-engineer)
- [Jobgether - Fullstack Engineer](https://jobgether.com/offer/6a70c218e9f5b7865864f573-fullstack-engineer-m-f-d)
- [Jobgether - Senior Android Developer](https://jobgether.com/offer/69a4cc157f0cfae7f1251ced-senior-android-developer-m-f-d)
- [NorthData - TeleClinic GmbH, HRB 223627 (EN)](https://www.northdata.com/TeleClinic%20GmbH,%20M%C3%BCnchen/HRB%20223627)
- [NorthData - TeleClinic GmbH (DE, financial chart data via CDP)](https://www.northdata.de/TeleClinic%20GmbH,%20M%C3%BCnchen/HRB%20223627)
- [Online-Handelsregister - HRB 223627](https://www.online-handelsregister.de/handelsregisterauszug/by/Muenchen/HRB/223627/TeleClinic-GmbH)
- [Creditreform - TeleClinic GmbH](https://firmeneintrag.creditreform.de/80333/8171084306/TELECLINIC_GMBH)
- [Companyhouse - TeleClinic GmbH](https://www.companyhouse.de/TeleClinic-GmbH-Muenchen)
- [Lobbyregister Bundestag - TeleClinic GmbH](https://www.lobbyregister.bundestag.de/suche/R005826)
- [PitchBook - TeleClinic profile](https://pitchbook.com/profiles/company/222353-38)
- [Munich Startup - TeleClinic GmbH](https://www.munich-startup.de/startups/teleclinic-gmbh/)
- [Munich Startup - TeleClinic acquired by Zur Rose Group](https://www.munich-startup.de/news/teleclinic-von-zur-rose-gruppe-uebernommen)
- [apotheke adhoc - Zur Rose: Rekordpreis für TeleClinic](https://www.apotheke-adhoc.de/nachrichten/detail/markt/zur-rose-rekordpreis-fuer-teleclinic-versandapotheken/)
- [apotheke adhoc - TeleClinic: Zur Rose schreibt Millionen ab](https://www.apotheke-adhoc.de/nachrichten/detail/markt/teleclinic-zur-rose-schreibt-millionen-ab/)
- [apotheke adhoc - Wechsel bei Zur Rose-Tochter (Müller übernimmt von Gründerin)](https://www.apotheke-adhoc.de/nachrichten/detail/markt/teleclinic-mueller-uebernimmt-von-gruenderin/)
- [DocMorris IR - Change in the management of TeleClinic](https://ir-corporate.docmorris.com/en/news/change-in-the-management-of-teleclinic/b79a4c44-0dbe-4c16-8e80-fee715eb4474)
- [DocMorris 2024 results (finanzen.ch) - TeleClinic doubled revenue to ~CHF 11M](https://images.finanzen.ch/nachrichten/aktien/docmorris-grows-6-7-per-cent-in-2024-and-accelerates-rx-growth-in-the-fourth-quarter-1034247563)
- [DocMorris Half-Year Report 2026 (PDF)](https://ir-corporate.docmorris.com/media/document/56165b60-e937-4f4c-a214-2f124cdf87ba/assets/DocMorris_HJB2026_en_Web.pdf?disposition=inline)
- [Investing.com - DocMorris H1 2026 slides](https://www.investing.com/news/company-news/docmorris-h1-2026-slides-rx-growth-accelerates-guidance-raised-93CH-4866932)
- [TradingView/EQS - DocMorris H1 2026 release](https://www.tradingview.com/news/eqs:26990ce04094b:0-docmorris-with-strong-growth-momentum-in-rx-and-digital-services-in-the-first-half-of-the-year-and-guidance-increase/)
- [ntg24 - DocMorris Q3 2026 / guidance raise](https://www.ntg24.de/DocMorris-hebt-Jahresprognose-dank-Rx-Boom-auf-rund-15-12112026-KIR)
- [ARIVA/EQS-Adhoc - DocMorris raises revenue guidance at Capital Markets Day](https://www.ariva.de/news/eqs-adhoc-anhaltend-starkes-rx-wachstum-docmorris-erhoeht-12204124)
- [ppc.land - DocMorris CMD analysis (TeleClinic 9M growth)](https://ppc.land/docmorris-expects-ad-unit-dmr-to-double-revenue-to-over-eur20m-in-2026/)
- [heise - TeleClinic übernimmt Medi24](https://www.heise.de/news/TeleClinic-uebernimmt-Schweizer-Telemedizin-Anbieter-Medi24-11521595.html)
- [medinside - DocMorris kauft Medi24](https://www.medinside.ch/de/telemedizin-docmorris-kehrt-mit-der-ubernahme-von-medi24-in-die-schweiz-zurueck-20261105)
- [cash.ch - DocMorris shares / Medi24](https://www.cash.ch/news/top-news/zweijahreshoch-die-valoren-von-docmorris-setzen-hohenflug-fort-983767)
- [finanznachrichten - DocMorris kündigt Stellenabbau infolge "AI-First"-Strategie an](https://www.finanznachrichten.de/nachrichten-2026-06/68858291-docmorris-kuendigt-stellenabbau-infolge-von-ai-first-strategie-an-095.htm)
- [Pharmazeutische Zeitung - DocMorris streicht 100 Stellen](https://www.pharmazeutische-zeitung.de/doc-morris-streicht-100-stellen-166297/)
- [cio.de - DocMorris streicht 100 Jobs infolge neuer KI-Strategie](https://www.cio.de/article/4189241/docmorris-streicht-100-jobs-infolge-neuer-ki-strategie.html)
- [moneycab - DocMorris bleibt 2025 in den tiefroten Zahlen](https://www.moneycab.com/schweiz/docmorris-bleibt-2025-in-den-tiefroten-zahlen/amp/)
- [finanzen.net - DocMorris repurchases 2026 convertible bonds (CHF 14.4M)](https://www.finanzen.net/nachricht/aktien/docmorris-repurchases-convertible-bonds-maturing-in-2026-with-a-nominal-value-of-around-chf-14-4-million-15437081)
- [StockAnalysis - DocMorris financials](https://stockanalysis.com/quote/swx/DOCM/financials/)
- [Ärzte Zeitung - KV Nordrhein und TeleClinic einigen sich außergerichtlich](https://www.aerztezeitung.de/Wirtschaft/Streit-um-telemedizinische-Angebote-KV-Nordrhein-und-TeleClinic-einigen-sich-aussergerichtlich-461776.html)
- [Ärzteblatt - Kritik an Übernahme durch DocMorris-Mutterkonzern](https://www.aerzteblatt.de/nachrichten/115890/Kritik-an-Uebernahme-eines-Telemedizin-Anbieters-durch-Doc-Morris-Mutterkonzern)
- [Glassdoor - TeleClinic reviews (DE, via CDP)](https://www.glassdoor.de/Bewertungen/TeleClinic-Bewertungen-E1777443.htm)
- [Glassdoor - TeleClinic overview](https://www.glassdoor.de/%C3%9Cberblick/Arbeit-bei-TeleClinic-EI_IE1777443.11,21.htm)
- [Glassdoor - TeleClinic salaries](https://www.glassdoor.de/Gehalt/TeleClinic-Geh%C3%A4lter-E1777443.htm)
- [Glassdoor - TeleClinic interviews](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/TeleClinic-Fragen-im-Vorstellungsgespr%C3%A4ch-E1777443.htm)
- [Glassdoor - iOS Engineer review (Apr 2025)](https://www.glassdoor.ca/Reviews/Employee-Review-TeleClinic-E1777443-RVW96436017.htm)
- [Kununu - TeleClinic (via CDP)](https://www.kununu.com/de/teleclinic2)
- [Kununu - TeleClinic reviews](https://www.kununu.com/de/teleclinic2/kommentare)
- [Kununu - TeleClinic salaries](https://www.kununu.com/de/teleclinic2/gehalt)
- [Teamblind - TeleClinic (not found)](https://www.teamblind.com/company/TeleClinic)
- [levels.fyi - TeleClinic (404)](https://www.levels.fyi/companies/teleclinic/salaries)
- [LinkedIn - TeleClinic company page](https://www.linkedin.com/company/teleclinic/about/)
- [Twilio customer story - TeleClinic](https://customers.twilio.com/en-us/teleclinic)
- [GitHub TeleClinic organisation (mirror)](https://github.imc.re/TeleClinic)
- [OpenStreetMap Nominatim - Brienner Straße 45 geocode](https://nominatim.openstreetmap.org/search?q=Brienner+Stra%C3%9Fe+45,+80333+M%C3%BCnchen&format=json&addressdetails=1)
- [Overpass API (nearby stops query)](https://overpass-api.de/api/interpreter)
