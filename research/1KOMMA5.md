# 1KOMMA5° - Full Research Report

_Researched: 2026-11-11_

> **Critical Disqualifiers**
>
> 1. **Glassdoor below the floors:** overall 3.4 and work-life balance **2.5** (16 German / 28 global reviews), against floors of 3.8 overall and 3.7 WLB.
> 2. **Documented hostility to a works council:** in 2024 IG Metall and CAPITAL reported that the CEO personally tried to stop a works council election at the Rosenheim subsidiary. On the morning of the vote he announced that the site would be dissolved apart from sales and marketing. No works council or collective agreement is known for the software entity.
> 3. **Not Python-centric:** the Heartbeat AI engineering stack is TypeScript (NestJS/Next.js) on GCP, with Go, Java, Flutter and Ruby on Rails. Python appears only as a "bonus" for data work.
>
> The full report follows anyway for completeness.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 2021 (5 years). 1KOMMA5° GmbH, Hamburg, HRB 168900 |
| Employees | **~3,000 globally** (company, Oct 2026). FY2024 filed average: **1,944** (group), of which **183** in the holding |
| Revenue (FY2024) | **€469.3M** group Gesamtleistung (filed consolidated accounts). €514M pro forma including full-year acquisitions. Press figures of €520-540M are pro forma or company-stated |
| Revenue (FY2025 / FY2026) | FY2025 not yet filed. Company guidance: **~€700M (~$750M) for 2026**, +35-40% organic growth; +30% organic in Q1-Q3 2026 |
| Profitability | FY2024 group **net loss €47.4M**, EBITDA **-€29.2M** (prior year: net loss €2.3M, EBITDA +€21.7M). Company now says the "core hardware business" is EBITDA-positive (~€40M expected for 2026) and cash-flow positive. The software arm is excluded from that figure and is deliberately loss-making. **FAIL** on audited figures; **BORDERLINE** on the company's 2026 segment claims |
| Ownership | Private, VC-backed unicorn. Investors include Hamilton Lane, CalSTRS, G2VP, Porsche Ventures, Eurazeo, b2venture, eCapital, 2150, Norrsken, Jan Klatten, plus re-invested owners of the acquired installer businesses |
| Software-centric | Installer roll-up (solar, batteries, heat pumps, wallboxes) with a software arm, Heartbeat AI. Most of the ~3,000 staff are tradespeople and sales. **BORDERLINE** |

### Key People

- **Philipp Schröder** - co-founder and CEO. Formerly Country Director of Tesla Germany & Austria and managing director at sonnen. Very visible on LinkedIn (83k+ followers) and known for public spats with journalists and critics (Sifted, Aug 2025).
- **Wolf Micha Grüber** - co-founder and CFO. Also managing director of Heartbeat AI GmbH.
- **Heartbeat AI GmbH managing directors** (NorthData): Barbara I. Wittenberg, Wolf Micha Grüber, Roman Jannik Schall.

### Funding History

| Date | Round | Amount | Valuation | Notes |
|---|---|---|---|---|
| 2021 | Seed / founding capital | n/d | - | Founded 2021 |
| Apr 2022 | Series A | ~$211M (~€215M) | - | Figures vary by source |
| Jun 2023 | Series B | €215M (equity) / €430M cumulative per tech.eu | ~$1.1B (unicorn) | G2VP lead |
| Dec 2024 - Feb 2025 | Series B 4th closing / "pre-IPO" | €150M announced; **€90.7M cash inflow** registered Feb 2025 (filed accounts, Nachtragsbericht) | ~$1.2B (reported) | |
| Jul 2025 | Pre-IPO extension | Part of the €150M; Sabanci Climate Ventures joins | ~$1.0B pre-money (implied by the +35% in 2026) | |
| Oct 2026 | Heartbeat AI round | **~€70M** (+ ~€35M from operating cash flow) | **$1.35B pre-money** (+35% vs Jul 2025) | b2venture lead; Marunouchi Innovation Partners new; IPO still on ice (Sifted) |

Third-party trackers (CB Insights, Seedtable, Salestools) disagree on several round sizes. The table relies on the filed accounts and the company's own press release where possible.

### Business Model

1KOMMA5° buys regional installer businesses (Meisterbetriebe), rebrands them as "1KOMMA5° <City> GmbH", and sells and installs PV, storage, heat pumps and wallboxes. The filing lists more than 40 subsidiaries. Attached to that is **Heartbeat AI**, an energy-management system and virtual power plant (VPP): it controls the installed devices, buys power when it is cheap and sells it when it is dear, and offers a dynamic tariff ("Dynamic Pulse"). The company says Heartbeat AI aggregates over 1 GW of flexibility across five markets. The software was spun out into its own company in 2024, which is now **Heartbeat AI GmbH**, and it is being opened to systems installed by competitors.

### Software-Centric Assessment

- **Revenue mix:** overwhelmingly hardware and installation. In FY2024 the group's gross profit (€169.9M on €469.3M) and its personnel cost (€129.5M for 1,944 staff, about €67K per head) are typical of a skilled-trades business, not a software company.
- **Hiring mix:** the Personio feed held 326 open postings on 2026-11-11. Of these, **27 are in the "Tech" department**, and only about 8 are hands-on software engineering roles. The rest are plumbing/heat pumps (65), electrical (56), field and inside sales (54), project coordination, and roofing.
- **But the software arm is real and funded:** Heartbeat AI GmbH is a separate company. The Oct 2026 round is the first raised "specifically for our energy AI", with over €100M pledged to Heartbeat AI for 2027. The engineering roles are product engineering on a VPP and IoT platform, not internal IT.
- **Verdict:** BORDERLINE. An engineer would sit in a product-software subsidiary with its own budget, inside a group whose culture, reviews and management attention are dominated by installation and sales.

Not consulting-adjacent: no client billing or consultant titles, and the product is owned in-house.

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **1KOMMA5° GmbH** (holding) | Amtsgericht Hamburg HRB 168900 | Neuer Wall 35, 20354 Hamburg | Group holding; services to subsidiaries (Impressum, filed accounts) |
| **Heartbeat AI GmbH** (formerly 1KOMMA5° Heartbeat GmbH, formerly 1komma5° Services GmbH) | Amtsgericht Hamburg HRB 171852 | Neuer Wall 35, 20354 Hamburg | "Vertrieb sowie die Abwicklung von Dienstleistungen in Verbindung mit Anlagen zur Erzeugung von erneuerbarer Energie, Energiespeicherung, Heizung, Klimatisierung und zur Beladung von Elektrofahrzeugen, die Bereitstellung von Strom ... auch unter Zuhilfenahme von Künstlicher Intelligenz ... insbesondere den Bezug, Handel und Weiterverkauf von Strom, das Energiemanagement ..." |
| **1KOMMA5° Technology GmbH** | Amtsgericht Hamburg HRB 179511 | Neuer Wall 35, 20354 Hamburg | "Einkauf und Verkauf von Komponenten ... sowie Entwicklung von und Handel mit Technologieprodukten im Bereich erneuerbarer Strom und Wärme" |
| **1KOMMA5° München GmbH** (formerly 1KOMMA5° Ingolstadt / Landshut GmbH) | Amtsgericht München HRB 298488 (previously Landshut HRB 13666) | Pacellistr. 2-4, 80333 München | "Planung, Ausführung, Wartung und Reparatur von Energiesystemen im Bereich Photovoltaik, Speicher und E-Mobilität ..." (installer/showroom company) |

**Verification:** the employing entity is named per posting in the Personio feed. Every senior, staff and principal software posting (Principal Software Engineer, Staff Engineer - Heartbeat AI, Staff Engineer - Virtual Assembly Line, Senior Software Engineer - Energy Markets, Senior Backend VPP Engineer, Product Engineer) is **employed by Heartbeat AI GmbH**. One edge/IoT role sits in 1KOMMA5° Commercial Solutions GmbH. These are direct German GmbH contracts, not PEO/EOR. Heartbeat AI GmbH's registered purpose reads as **energy sales, energy trading and energy management services rather than software development**: it is the regulated energy-supplier and VPP-operator vehicle, which also employs the engineers. Software development appears explicitly only in Technology GmbH's purpose. This is not a sales shell (the company builds and runs the platform), but the purpose does not mention engineering. The Munich GmbH is an installer business, not an engineering entity.

**Verdict:** PASS with CAUTION (direct German employment confirmed; the engineering employer is Hamburg-registered, and its purpose is framed as energy services).

---

## Section 3: Office Location

- **Office address:** **1KOMMA5° Showroom München, Pacellistr. 2, 80333 München** (Kreuzviertel, Altstadt-Lehel). Opened Nov 2024 as a flagship showroom and event space "unweit des Bayerischen Hofs" with "rund 30 ... Arbeitsplätze". The registry lists Pacellistr. 2-4 for 1KOMMA5° München GmbH. Nominatim resolves Pacellistraße 2 to Kreuzviertel, Altstadt-Lehel, 80333.
  - Engineering postings list "offices in Hamburg, Berlin or Munich", but no Munich engineering team or engineering floor is documented anywhere. The Munich site is a showroom with sales staff. The engineering hubs visible in postings and reviews are Berlin (most tech postings) and Hamburg (HQ).
- **Nearest public transport** (Nominatim + Overpass, straight-line distances):
  - Lenbachplatz tram stop: ~215 m
  - Karlsplatz (Stachus): U-Bahn ~330 m, S-Bahn ~450 m. S-Bahn trunk line S1-S8, U4/U5, and many tram lines (16-21, 27, 28)
  - Ottostraße tram stop: ~320 m; Marienplatz (Theatinerstraße) tram stop: ~325 m
  - Odeonsplatz U-Bahn (U3/U4/U5/U6): ~430 m; Marienplatz U-Bahn ~445 m, S-Bahn ~500 m
- **Work model:** every engineering posting says **"You work remotely (Germany-wide), with offices in Hamburg, Berlin or Munich."** Some Hamburg-tagged Product Engineer listings on aggregators show hybrid, and one aggregator copy says "No home office possible". Treat the live Personio text (remote Germany-wide) as authoritative. Kununu reviewers confirm the benefits: home office (60%), flexible hours (53%). Remote is limited to Germany.

---

## Section 4: Reviews

**GPTW:** No Great Place to Work certification or listing found for 1KOMMA5° in Germany. The GPTW ID that surfaced in search (102033883) belongs to shopware AG. Awards found are startup and brand awards (German Brand Award, LinkedIn Top Startups 2023), not workplace certifications.

#### Glassdoor

Retrieved via Chromium over CDP (logged-in session; the .com and ASCII slugs return 404, so the working URL uses `1KOMMA5%C2%B0`). Glassdoor shows **16 reviews** on the German profile view and "28 anonymous reviews" in its FAQ text. The difference is most likely the Australian, Nordic and Spanish subsidiaries.

| Metric | Global | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | **3.4** (28 reviews) | 3.4 (16 reviews) | No reviews (best-rated locations list shows Berlin (6) only) | 2 reviews visible: Engineer 1.0, Software Engineering Manager 4.0 |
| **WLB** | **2.5** | 2.5 | - | - |
| **Culture & Values** | 3.3 | 3.3 | - | - |
| **Comp & Benefits** | 2.7 (+7% in 12 months) | 2.7 | - | - |
| **Career Opportunities** | 3.3 | 3.3 | - | - |
| **Diversity & Inclusion** | Not shown | Not shown | - | - |
| **% Recommend** | 61% | 61% | - | - |
| **CEO Approval** | Not shown | Not shown | - | - |
| **Business Outlook** | 66% positive | 66% positive | - | - |

All Glassdoor filters are **far below 20 reviews**, so every figure is directional only. The Germany column equals the profile shown on glassdoor.de. Glassdoor does not separate the sub-scores for the 16- and 28-review sets.

#### Kununu

Retrieved via Chromium over CDP (curl returns a 2 KB bot shell). Slug: `1komma5-deutschland` (a separate small profile exists as `1komma5-lingen`).

- **Overall score:** **3.9 / 5.0** (last 2 years, 310 employee reviews since 2022); above the Energie industry average of 3.7
- **Recommendation rate (Weiterempfehlung):** **68%**
- **Total reviews:** 481 (employee reviews in the score: 310)
- **Sub-areas:** Karriere & Gehalt 3.7, Unternehmenskultur 3.9, Arbeitsumgebung 4.1, Vielfalt 4.2. Best factor: Kollegenzusammenhalt 4.3. Worst factor: Gehalt/Benefits 3.5. Salary satisfaction: 63% (295 ratings)
- **IT department filter:** **3.9, 87% recommendation, 23 reviews**. Recent IT reviews (2025-2026) are markedly more negative than the 2024 ones (see below)
- **Kununu Top Company:** **NO** (no badge shown)

The Kununu profile covers all subsidiaries, including the installer companies. The 3.9 is a blend of HQ, tech and trades staff. The installer-site reviews (Münster, Weimar, Freiburg) are the most negative.

#### Blind / Teamblind

`teamblind.com/company/1KOMMA5` returns "Page not found" (checked via CDP). **No Blind presence**, which is expected for a German scale-up with few US engineers.

#### Review Themes (2024-2026)

**Positives:**

- **Mission and impact.** "Exciting field, lots of impactful projects to work on, strong culture with passionate, skilled team" (Glassdoor, Oct 2026, current Software Engineering Manager, 3+ years). "Primär: das was wir bauen! Mit einem extrem talentierten und motivierten Team nach einer klaren, gemeinsamen Vision." (Kununu, Oct 2024, Werkstudent/in, IT, 1KOMMA5° GmbH, Hamburg).
- **Colleagues and team cohesion** (Kununu's best factor at 4.3). "Die Kollegen in der Zentrale. Die sind alle top und es haben sich sehr gute Freundschaften ergeben." (Kununu, Jan 2026, role not shown in the highlight).
- **Flexibility and remote work.** "Relativ freie Gestaltung der Arbeitszeit und auch der Ort." (Kununu, Mar 2026). "No problems with home office and flexible times." (Kununu, Oct 2025, Ex-Zeitarbeiter/in, IT, 1KOMMA5° Heartbeat GmbH, Hamburg).
- **Fast, conversational hiring.** "Der Bewerbungsprozess war schnell und unkompliziert, fühlte sich eher wie ein Gespräch als eine Prüfung an." (Kununu, May 2024, Angestellte/r oder Arbeiter/in, IT, 1KOMMA5° GmbH, Hamburg).

**Negatives:**

- **Workload, pace and unpaid overtime** (several platforms and years; **red flag: WLB, unpaid overtime**). "Erwartung von Mehrarbeit (Abende/Wochenenden) ohne zusätzliche Vergütung, insbesondere auf höherer Unternehmensebene." (Glassdoor, Apr 2026, former Werkstudent technische Abteilung, Berlin, 1+ year). "Ich habe viele Überstunden gemacht, die mir nicht ausgezahlt wurden." (Kununu, Feb 2026, Ex-Angestellte/r oder Arbeiter/in, IT, 1KOMMA5° Berlin GmbH, Berlin). "A lot of meetings that do delay the tasks and make overtime a quite regular occurence." (Kununu, Oct 2025, Ex-Zeitarbeiter/in, IT, 1KOMMA5° Heartbeat GmbH, Hamburg).
- **Below-market pay and weak equity.** "Paid below market rates and bonus structure full of pitfalls and clawbacks." (Glassdoor, Apr 2026, former Engineer, Berlin, 1+ year). "Es gibt aber keine Mitarbeiterbeteiligung und wenn ja nur eine schlechte. Sollte es zu einem Börsengang kommen, profitiert quasi nur das C Level, die Alteigentümer der Handwerksbetriebe und die Investoren." (Kununu, Gehalt/Benefits highlight, date and role not shown in the highlight).
- **Inexperienced or micromanaging leads** (**red flag: toxic leadership, localized**). "Nachdem ich eine Weile dort gearbeitet hatte, fing mein Chef jedoch an, ständig Mikromanagement zu betreiben ... Grauenhaft, das Schlimmste, was ich in meinem bisherigen Arbeitsleben erlebt habe." (Kununu, Feb 2026, Ex-Angestellte/r oder Arbeiter/in, IT, 1KOMMA5° Berlin GmbH, Berlin). "Viel Arbeit, teils unqualifizierte Führungskräfte" (Glassdoor, Oct 2026, current Talent Management, Hamburg).
- **Stick-only management and a harsh feedback culture.** "Management style relies solely on the stick. No carrots. Not a kind, caring, or consistent place to work." (Glassdoor, Apr 2026, former Engineer, Berlin, 1+ year). "Hoher Stress durch intensive Feedbackkultur, in der selbst kleine Entscheidungen stark hinterfragt werden." (Glassdoor, Apr 2026, former Werkstudent technische Abteilung, Berlin).
- **Poor exits and communication around dismissals** (**red flag: silent firings / communication breakdown**). "Am Tag meiner Kündigung wurde ich erst um 18 Uhr entlassen. Über zwei Monate hinweg ignorierte die Personalabteilung meine Anfragen" (Kununu, Jul 2026, Ex-Angestellte/r oder Arbeiter/in, IT, 1KOMMA5° Berlin GmbH, Berlin). "Im Falle von Trennungen fände ich es angemessen, wenn die Geschäftsführung persönlich in den Prozess eingebunden ist und die Entscheidung nachvollziehbar erläutert wird" (Kununu, May 2026, role not shown in the highlight).
- **CEO rhetoric on hours.** "The founder/CEO whishes on Linkedin that his workers could work up to 70 hours per week like in good companies like Tesla..." (Kununu, Oct 2025, Ex-Zeitarbeiter/in, IT, 1KOMMA5° Heartbeat GmbH, Hamburg). The underlying LinkedIn post could not be found, so this is the reviewer's claim. A Glassdoor engineer separately describes the same "next Tesla ... burnout factories" framing.
- **Burnout at the installer sites (trades/sales, lower relevance for engineering).** "Überstunden sind hier nicht Ausnahme sondern die Regel und werden eingefordert" (Kununu, Sep 2026, Ex-Angestellte/r oder Arbeiter/in, 1KOMMA5° Münster). "Unbezahlte Überstunden Samstags/ Sonntags usw." (Kununu, Sep 2026, Ex-Angestellte/r oder Arbeiter/in, 1KOMMA5° Weimar).

#### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | **Present, localized to teams/leads, in the engineering function too.** Berlin IT reviewers describe a lead "absolut unfähig ... völlig unrealistische Erwartungen" (Kununu, Feb 2026, IT, Berlin) and "so viele Menschen mit einem Ego von der Größe eines Planeten" (Kununu, Jul 2026, IT, Berlin). The 2024 IT reviews from Hamburg are positive, so team variance is high. |
| 24/7 Work Expectation | **Cultural pressure, not a formal 24/7 rule.** "Next Tesla ... move fast and break things" (Glassdoor, Apr 2026, former Engineer). Reported CEO remarks about 70-hour weeks (Kununu, Oct 2025, IT, unverified). No on-call language in postings. |
| Internal Surveillance | **Not reported.** No mentions found. |
| Fear-driven Management | **Some signals.** "Management style relies solely on the stick" (Glassdoor, Apr 2026, former Engineer). "Arbeitsdruck wird teilweise nach unten weitergegeben" (Glassdoor, Apr 2026, former Werkstudent). The 2024 works council episode, where a site was dissolved on the morning of the vote, is the strongest fear signal at company level. |
| Communication Breakdown | **Recurring.** "Es mangelt völlig an Klarheit und Transparenz seitens der Führungsebene" (Kununu, Jul 2026, IT, Berlin). "Vertraglich werden falsche Versprechungen gemacht oder Entscheidungen werden nach kurzer Zeit umgeworfen." (Glassdoor, Apr 2026). |
| Unpaid Overtime | **Reported in IT and trades.** "viele Überstunden ..., die mir nicht ausgezahlt wurden" (Kununu, Feb 2026, IT, Berlin). "Erwartung von Mehrarbeit (Abende/Wochenenden) ohne zusätzliche Vergütung" (Glassdoor, Apr 2026). |
| Silent Firings | **Signals of abrupt, poorly handled dismissals** ("Am Tag meiner Kündigung wurde ich erst um 18 Uhr entlassen", Kununu, Jul 2026, IT, Berlin; calls for leadership to explain separations, Kununu, May 2026). No works council to hear dismissals at the software entity, as far as is known. |
| Work-Life Balance issues | **Yes.** Glassdoor WLB **2.5**. "Pace is consistently high" even from a positive engineering manager (Glassdoor, Oct 2026). Kununu: "45+h Wochen sind der Standard" (Nov 2026, Münster). |

**Risk level: MODERATE-HIGH.** This is not large-company bureaucracy (b). It is a mix of (a) a founder-driven, Tesla-style pressure culture visible at company level (CEO messaging, the works council episode, stick-based management) and (c) strongly team-dependent dysfunction. The Berlin IT reviews from 2025-2026 are the most relevant and among the most negative. Positive engineering voices exist (Hamburg 2024, an engineering manager in Oct 2026), so the risk depends heavily on the specific team and lead.

---

## Section 5: Compensation

#### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| Glassdoor (Germany) | Senior Software Engineer | €75K-€93K range (Glassdoor's average quoted as €87.5K) | Not reported | Not reported | ~€75-93K | 6 |
| Glassdoor (Germany) | Software Engineer | €56K-€88K | - | - | ~€56-88K | 2 |
| Glassdoor (Germany) | Senior Product Manager | €83K | - | - | ~€83K | 2 |
| Kununu | Softwareentwickler:in (Hamburg) | Ø €81.2K gross incl. variable | - | - | ~€81K | 6 |
| levels.fyi | - | No company page (404, checked via CDP) | - | - | - | 0 |
| Job postings | - | No salary ranges in any Personio posting | - | - | - | - |

Glassdoor lists salary submissions by city as Berlin (25), Hamburg (22) and Munich (6); the Munich entries are not broken out by title. For reference, levels.fyi's Germany-wide software engineer average total comp is ~€80K, and its Berlin average is ~€88K. On this data, senior software pay at 1KOMMA5° sits around the German market median, not above it. A Glassdoor reviewer (former Engineer, Apr 2026) says "paid below market rates", and a Kununu IT reviewer (Jul 2026) found a job paying 15% more right after being dismissed.

#### Equity / Stock

No documented employee equity programme. The Kununu salary highlight states there is no meaningful employee participation, and that an IPO would mainly benefit the C-level, the former installer owners (who receive a "Rückbeteiligung", per the company's own boilerplate) and investors. A variable bonus tied to individual goals exists (Kununu, Oct 2024, IT, Hamburg). A Glassdoor reviewer describes it as "full of pitfalls and clawbacks". Benefits listed in postings: EGYM Wellpass, Futurebens discounts and job-bike leasing. **Liquidity risk:** private and IPO-deferred, so any equity, if offered, should be valued at zero.

#### Verdict

Large, profitable Munich corporates typically pay senior/staff engineers ~€95-120K base plus bonus. 1KOMMA5°'s visible senior data tops out at ~€93K with no equity. **BELOW** (directional; 6 senior data points, no Staff/Principal data).

---

## Section 6: AI/ML & Tech Stack

#### AI Strategy

- **Heartbeat AI** is the named product: an energy-management system and VPP that optimizes when connected PV, batteries, heat pumps, EVs and air conditioners draw or feed power against spot prices (EPEX Spot, Montel are named in postings), plus a dynamic tariff. It claims more than 1 GW of aggregated flexibility in five markets, and over 45,000 systems at the FY2024 filing date.
- **Investment:** over €100M pledged for 2027 (the Oct 2026 round plus operating cash flow), described as "AI development, software capabilities and go-to-market speed". The software arm was carved out into its own company to be sold to third parties ("Plattformpartner für Energieversorger, Hersteller und Installateure").
- **What the "AI" is in practice (from postings):** optimization, forecasting and dispatch for energy markets (the Staff Engineer posting asks for "AI/ML-driven or data-intensive systems (e.g. forecasting, real-time data pipelines)"). Data scientists exist, since postings mention collaboration with them, but no ML engineering or data science roles are currently posted. The most prominent current "AI" theme in postings is **agentic engineering**: "Architect our systems and APIs so AI agents operate as first-class users", "Drive the org's transformation to agentic engineering", Cursor/Claude, MCP. This is AI-assisted development and agent-consumable APIs, not model building.
- **Assessment:** genuine applied optimization/forecasting work exists inside the VPP. The "AI" branding stretches across a largely conventional TypeScript product and IoT platform. There is no visible MLOps or ML platform function.

#### Tech Stack

Derived from **current Personio job postings** (Principal Software Engineer, Staff Engineer - Heartbeat AI, Staff Engineer - Virtual Assembly Line, Senior Software Engineer - Energy Markets, Senior Backend VPP Engineer, Product Engineer, Software Engineer - Edge & Cloud, Head of Security; feed retrieved 2026-11-11) and from aggregator copies of the Platform/SRE/IoT Cloud postings (wearedevelopers, startup.jobs, jobgether). The company has no public engineering blog or GitHub organisation.

| Category | Technologies |
|---|---|
| **Primary language(s)** | **TypeScript** (NestJS, Next.js, React, VueJS) dominant; Go (IoT, gateways, platform); Java; Flutter (mobile); Ruby on Rails (growth/ops systems); Lua (edge controllers). Python only as "bonus" for data engineering/ML |
| **AI/ML** | Forecasting/optimization for VPP dispatch and energy trading (no frameworks named); agentic engineering with Cursor, Claude, MCP |
| **Cloud** | **Google Cloud Platform**: GKE, Cloud Run, Cloud Functions, Pub/Sub, Cloud SQL, Firestore; Vercel; some AWS (Fargate) mentions in older platform postings |
| **Infrastructure** | Kubernetes (GKE), Terraform / Terramate, GitHub Actions, Docker, Backstage (aggregator copies), Wiz, Auth0, GitHub Advanced Security |
| **Data** | PostgreSQL, BigQuery, SQLMesh, Looker |
| **Other** | IoT: Eclipse Hono, MQTT, Mender (OTA), Modbus TCP/RTU, REST/gRPC; Observability: Datadog, OpenTelemetry, incident.io; Linear, Notion, Figma, Miro |

**Summary:** TypeScript-centric product engineering (NestJS/Next.js) with Go for the IoT and edge platform, on Google Cloud (GKE, Cloud Run, BigQuery). AI/ML takes the form of applied optimization and forecasting for energy-market dispatch inside a virtual power plant, plus a strong push toward agentic, AI-assisted development. Applied production engineering, not research.

---

## Section 7: Language

- All Heartbeat AI engineering postings are written in English and require "Strong verbal and written communication skills in English, with proficiency in German considered a plus" (Principal, Staff, Senior VPP Engineer, Product Engineer).
- **Exception:** "Software Engineer - Edge & Cloud" (1KOMMA5° Commercial Solutions GmbH) requires "Business-fluent German and English skills". The trades, sales and installer roles are German-only.
- Glassdoor and Kununu IT reviews are partly written in English, and reviewers describe "international, dynamic" teams, especially in Berlin.

**Verdict:** PASS for Heartbeat AI GmbH engineering roles (English required, German a plus). CONDITIONAL for Commercial Solutions/edge roles (German required).

---

## Section 8: Stability

#### Financial Position

From the **filed FY2024 consolidated accounts** (Unternehmensregister extract dated 13.02.2026, published via the Bundestag Lobbyregister; signed 18 May 2025):

| Item | FY2024 | FY2023 |
|---|---|---|
| Gesamtleistung (group) | €469.3M | €364.2M |
| Gross profit (Rohergebnis) | €169.9M | €136.7M |
| Personnel cost | €129.5M (avg 1,944 staff) | €74.8M |
| Other operating expenses | €71.1M | €41.8M |
| EBITDA | **-€29.2M** | +€21.7M |
| Net result | **-€47.4M** | -€2.3M |
| Cash (group) | **€53.2M** (from €143.2M) | €143.2M |
| Equity | ~€231M (61% of €377M balance sheet) | €273.8M |

- Management attributes the 2024 swing to "deutlich ausgeweitete Investitionen in die Ausgliederung und Skalierung der Energiemanagement-Plattform Heartbeat AI sowie der beschleunigte Ausbau des Wärmepumpengeschäfts". It also cites heavy price competition and a market decline (German 5-15 kWp registrations -22%, heat pumps -46%). Its own risk report rates competition and economic risk as "kritisch".
- **Discrepancy:** company press in 2025 described FY2024 as "operativ profitabel" with ~€520M revenue. The audited group accounts show a negative EBITDA and a €47M net loss. The positive figure is the "core hardware business" adjusted for Heartbeat AI and heat-pump investment (holding EBITDA adjusted: -€7.9M). The company also missed its €750M target for 2024 by about €200M (Trending Topics).
- **2025-2026 (company-stated, unaudited):** core hardware EBITDA ~€40M expected for 2026; "profitable and cash-flow positive"; "debt-free"; up to €1.5B in off-balance-sheet bank facilities for customer financing (NORD/LB and Deutsche Bank: up to €500M for public-sector customers); 2026 revenue ~€700M. The FY2025 accounts are not yet published.
- Credit rating: none found.

#### Financial Runway

Cash after FY2024 is not published. Estimate:

- End-2024 cash: **€53.2M** (filed accounts, observed 2026-11-11).
- Feb 2025 capital increase (Series B 4th closing): **+€90.7M** (filed accounts, Nachtragsbericht).
- Jul 2025 pre-IPO extension: amount not separately disclosed; assumed €0-60M beyond the €90.7M.
- Oct 2026 round: **+~€70M** (press release).
- FY2025 burn: unknown. The company says the hardware business turned cash-flow positive during 2025-2026.

**Bottom-up model (2026, group level, estimates):**

| Cost line | Annual estimate |
|---|---|
| Staff (~3,000 × ~€70K fully loaded, scaled from €129.5M / 1,944 in FY2024 plus inflation) | ~€210M |
| Cost of goods / subcontractors (~63% of revenue, FY2024 ratio) | ~€440M |
| Other operating expenses (marketing, IT, logistics, scaled from €71M) | ~€90M |
| Heartbeat AI investment, 2027 run-rate (company pledge) | ~€100M |
| **Total gross cost (2027 with Heartbeat pledge)** | **~€840M/year** |

| Revenue source | Est. annual inflow |
|---|---|
| Group revenue (2026 guidance ~€700M; +20-35% for 2027) | ~€840-945M |
| **Total revenue offset** | **~€840-945M/year** |

| Scenario | Net burn | Cash at hand (est., end-2026) | Runway | Next round needed by |
|---|---|---|---|---|
| Optimistic (hardware EBITDA €40M+, Heartbeat spend €100M, revenue +35%) | ~€0-30M/year | ~€150M | 5+ years | Not required; IPO optional |
| Base case (hardware EBITDA €25M, Heartbeat €100M) | ~€60-75M/year | ~€120M | ~1.5-2 years | ~2028 |
| Stress (2024-style market drop: hardware EBITDA ~€0, Heartbeat spend cut to €60M) | ~€60-90M/year | ~€90M | ~1-1.5 years | ~2027-2028 |

Cash figures for end-2026 are **estimates** built from the filed end-2024 balance (€53.2M), the registered €90.7M inflow (Feb 2025) and the ~€70M Oct 2026 round, less an assumed 2025-2026 net outflow of €70-110M. The real figure could be materially different. The company's €1.5B bank facilities fund customer installations and are not available as operating liquidity.

#### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| May 2024 | Rosenheim site partly dissolved "with the exception of sales and marketing", announced by the CEO on the morning of the works council election | Unknown; company denied a "Standortschließung" and declined to say how many were dismissed | IG Metall called it intimidation (Trending Topics / CAPITAL, 28 Jun 2024) |
| 2024-2025 | "Umstrukturierung in der Zusammenarbeit einzelner Standorte" to pool regional resources (filed Lagebericht) | Unknown | Synergy programme across installer branches |
| 2025-2026 | Individual dismissals in tech described in Kununu IT reviews (Berlin) | Individual | No announced programme |

No announced group-wide layoff round was found for 2025-2026. Hiring is active (326 open postings). Competitor Enpal cut staff in 2026, which shows the sector-wide pressure.

#### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | **YES at 1KOMMA5° Rosenheim GmbH (elected 2024); UNKNOWN / likely NO at Heartbeat AI GmbH, the holding and Munich** | Trending Topics, 28 Jun 2024 (citing CAPITAL): "Der Betriebsrat ist inzwischen trotzdem gewählt". No Kununu review, posting or press item mentions a council at the Hamburg/Berlin tech entities |
| Collective agreement | **NONE found** | No "Tarif", "tarifgebunden" or "AT-Vertrag" in any of the 326 Personio postings; no union press items |
| European works council | **NO / not found** | Group operates in 7 countries; no EWC found |
| Conflict signals | **Serious: documented resistance to a works council.** | The CEO "reiste persönlich an, um die Initiatoren von ihrem Vorhaben abzubringen", allegedly encouraged staff by email to seek an injunction against the vote (rejected by the Landesarbeitsgericht München), then announced the partial dissolution of the site on election morning. IG Metall: "Wir gehen davon aus, dass 1Komma5° hier ein Signal senden möchte, um Mitarbeiter:innen von einer Betriebsratsgründung abzuschrecken." (Trending Topics, 28 Jun 2024) |

**Verdict:** **FAIL.** There is no council or agreement covering the software entity. Management has a documented record of fighting a council at a subsidiary, and engineering reviews describe abrupt dismissals and unpaid overtime. This is the pattern that the past reports associate with silent firings.

---

## Section 9: Regulated Industry

- Heartbeat AI GmbH operates as an **energy supplier and VPP/flexibility aggregator** (dynamic tariff, power trading, balancing services). This brings EnWG and BNetzA rules, market communication (MaKo; the company is hiring "Experte Energiewirtschaft / Marktkommunikation"), smart-meter-gateway (BSI TR-03109) rules via the metering rollout, §14a EnWG controllable devices, and transmission-system-operator prequalification for balancing reserve. NIS2/KRITIS-adjacent security expectations apply to device-control platforms, and a Head of Security is being hired.
- **Engineering impact:** protocol and integration constraints (MaKo formats, smart-meter rollout delays, which the CEO blamed for the 2024 revenue miss), security hardening, and audit expectations on the control plane. This is not formal safety certification (no ISO 26262/IEC 61508-style safety cases), and day-to-day web/backend work deploys continuously.

**Verdict:** CAUTION (moderate: energy-market regulation shapes the domain and the release pace on integration work, but there is no formal safety-case regime).

---

## Section 10: On-Call

- No posting in the Personio feed mentions on-call, Rufbereitschaft or pager duty. Product Engineer postings say "Cloud Architects and SREs will enable you to easily deliver and run software", which implies a dedicated SRE function. Aggregator postings exist for "(Senior) Site Reliability Engineer - Platform & Agentic Operations". incident.io is in the stack.
- **Nature of the product:** a real-time VPP that controls customer hardware and trades on spot and balancing markets. Market positions and device dispatch run 24/7, and balancing-market participation requires operational availability. Backend and VPP engineers who own production services ("Own feature development end-to-end, from problem framing through production deployment to long-term maintenance") are likely to share incident duty, even if SRE carries primary on-call.

**Verdict:** CAUTION (team-dependent; not stated, but structurally likely for VPP/energy-market and IoT platform teams; less likely for growth/ops "Virtual Assembly Line" teams).

---

## Section 11: Interview Process

Based on Glassdoor (retrieved via CDP; 18 interview reports across all roles).

| Metric | Value |
|---|---|
| Difficulty | 2.5 / 5 (Glassdoor); Senior Software Engineer and Software Engineer interviews rated "very easy"; Platform Engineer rated "very hard" |
| Positive experience | 38.9% |
| Average duration | ~18 days overall; Software Engineer reports quickest (~1 day reported) |
| Rounds | Not stated; stage mix: skills test 24%, one-to-one 24%, group interview 19%, phone screen 14%, background check 10%, presentation 5% |

**Typical process:** recruiter or phone screen, then a skills/qualification test (often a take-home or technical exercise), one-to-one interviews with the hiring manager and team, sometimes a group interview, and a background check. A Kununu IT reviewer (May 2024, Hamburg) described the process as "schnell und unkompliziert ... eher wie ein Gespräch als eine Prüfung". The process looks **experience- and conversation-focused rather than LeetCode-heavy**. The low positive-experience share (39%) is driven mostly by sales and platform candidates. Too few engineering reports exist to characterize Staff/Principal loops.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | BORDERLINE: installer roll-up of ~3,000 staff; software is a funded subsidiary (Heartbeat AI GmbH) with roughly 8 open hands-on engineering roles |
| Not consulting | PASS: own product, no client billing |
| Profitable | FAIL on audited FY2024 (net loss €47.4M, EBITDA -€29.2M); company claims core hardware EBITDA ~€40M in 2026 while investing €100M+ in software |
| Employee count | ~3,000 global (1,944 FY2024 average); 183 in the holding |
| English-speaking | PASS for Heartbeat AI roles (English required, German a plus); German required in Commercial Solutions edge roles |
| Local entity + engineering contracts | PASS with CAUTION: Heartbeat AI GmbH, HRB 171852 Hamburg, direct employment; purpose framed as energy services |
| Location / work model | Remote Germany-wide; Munich location is a showroom at Pacellistr. 2 (Altstadt, ~330 m to Stachus); no documented Munich engineering team |
| Glassdoor | FAIL: 3.4 overall, WLB 2.5, 61% recommend (16-28 reviews, directional) |
| Kununu | 3.9, 68% recommend (310 reviews, all subsidiaries); IT filter 3.9 / 87% (23), recent IT reviews negative; no Top Company badge |
| Salary | BELOW: Senior SWE €75-93K (Glassdoor, 6 pts), Kununu SWE Ø €81K; no meaningful equity |
| AI/ML content | Moderate: applied optimization/forecasting in the VPP plus an agentic-engineering push; no ML platform or MLOps function visible |
| Computer-language/Tech-stack | TypeScript-centric (NestJS/Next.js) with Go/IoT on GCP; Python bonus only |
| No on-call | CAUTION: not stated; likely for VPP/IoT platform teams |
| WLB / Stability | WLB poor (2.5); financially well-capitalized but loss-making at group level in the last audited year; IPO deferred |
| Works council / collective agreement | FAIL: documented resistance to a works council (Rosenheim 2024); none known at the software entity; no Tarif |
| Regulated industry | CAUTION: energy-market regulation (EnWG, MaKo, smart-meter rules) |
| Review themes | Mission and colleagues praised; workload, unpaid overtime, inexperienced leads, below-market pay and abrupt exits criticised, including by 2025-2026 IT reviewers |
| Founder-driven culture risk | High: Tesla-style "next Tesla" messaging, reported 70-hour-week remarks, public combativeness |

---

## Section 13: Verdict

**Exclude.**

**Strengths.** 1KOMMA5° is a well-capitalized climate-tech unicorn ($1.35B pre-money, Oct 2026) with real scale (~€700M expected 2026 revenue) and a genuinely interesting software problem. Heartbeat AI is a virtual power plant that controls more than 1 GW of household flexibility and trades it on energy markets, and it has a fresh €100M+ budget for 2027. Engineering roles are English-speaking, remote within Germany and employed directly by a German GmbH. The mission draws consistent praise, and Kununu's 3.9 overall (310 reviews) is above the energy-industry average.

**Hard blockers:**

1. **Glassdoor floors failed.** Overall 3.4 and work-life balance 2.5 against floors of 3.8 and 3.7. The data set is small (16-28 reviews), but the engineering-specific reviews from 2025-2026 on both platforms point the same way: unpaid overtime, micromanaging or inexperienced leads, and "stick-only" management.
2. **Works council hostility.** In 2024 the CEO personally intervened against a works council election at the Rosenheim subsidiary. An injunction attempt failed at the Landesarbeitsgericht München, and parts of the site were dissolved on the morning of the vote (IG Metall: "Einschüchterungstaktik"). There is no known council or collective agreement at the software entity, and IT reviewers describe abrupt dismissals ("erst um 18 Uhr entlassen") and an unresponsive HR. This is the silent-firing pattern the criteria screen for.
3. **Stack mismatch.** Engineering is TypeScript-centric (NestJS/Next.js) with Go for IoT, on GCP. Python appears only as a bonus skill for data engineering. There is no ML engineering or MLOps function to anchor a Python-centred AI role.

**Secondary concerns:**

- Compensation is **below** the large-corporate Munich bracket (Senior SWE ~€75-93K, no equity worth counting, bonus described as having clawbacks).
- The Munich "office" is a sales showroom. Engineering hubs are Berlin and Hamburg, so a Munich-based engineer would be remote with no local team.
- Group-level losses in the last audited year (-€47M) contrast with "operativ profitabel" messaging. The company also missed its 2024 revenue target by about €200M, and its IPO is deferred.
- Likely on-call exposure for VPP and IoT platform teams. Energy-market regulation shapes the integration work.
- A founder-driven, Tesla-style pressure culture with high variance between teams.

**Recommendation:** Do not apply. If 1KOMMA5° ever resurfaces (for example, through a Heartbeat AI role explicitly built around Python forecasting or optimization), three things would need to change: (a) Glassdoor recovering to at least 3.8 overall and 3.7 WLB on a larger review base, (b) evidence of a works council or at least a clean employee-relations record at Heartbeat AI GmbH, and (c) a documented Python/ML team with a written no-on-call scope and a salary band above €100K base.

---

## Sources

- [1KOMMA5° Impressum](https://1komma5.com/impressum) (CDP)
- [Unternehmensregister extract: 1KOMMA5° GmbH Jahresabschluss and Konzernlagebericht 2024 (Lobbyregister PDF, HRB 168900)](https://www.lobbyregister.bundestag.de/media/94/86/697493/Hamburg_HRB_168900_20-02-2026.pdf) (curl)
- [1KOMMA5° GmbH Jahresabschluss 2023 (Lobbyregister)](https://www.lobbyregister.bundestag.de/media/e4/13/597163/JA-2023-1Komma5-GmbH.pdf)
- [NorthData: Heartbeat AI GmbH, HRB 171852](https://www.northdata.de/Heartbeat%20AI%20GmbH) (CDP)
- [NorthData: 1KOMMA5° Technology GmbH, HRB 179511](https://www.northdata.de/1Komma5%C2%B0%20Technology%20GmbH) (CDP)
- [NorthData: 1KOMMA5° München GmbH, HRB 298488](https://www.northdata.de/1Komma5%C2%B0%20M%C3%BCnchen%20GmbH) (CDP)
- [1KOMMA5° Standort München (Pacellistr. 2)](https://1komma5.com/de/standorte/muenchen/) (CDP)
- [Press release: 1KOMMA5° eröffnet ersten Standort in München (Nov 2024)](https://1komma5.com/de/magazin/pressemitteilungen/tandort-in-muenchen-flagship-store-fuer-die-energiewelt-der-zukunft-im-herzen-der-innenstadt1komma5-eroeffnet-ersten-s/) (CDP)
- [Press release: new funding at 35% higher valuation, €100M+ for Heartbeat AI (Oct 2026)](https://1komma5.com/en/press/press-releases/1komma5-secures-new-funding-for-its-energy-ai-at-a-35-percent-higher-valuation) (CDP)
- [Press release: 1KOMMA5° steigert Umsatz und Profitabilität (Sep 2026)](https://1komma5.com/de/magazin/pressemitteilungen/1komma5-steigert-umsatz-und-profitabilitaet/)
- [pv magazine: 1Komma5° erwartet für 2026 ein Umsatzwachstum von 35 bis 40 Prozent](https://www.pv-magazine.de/2026/09/22/1komma5-erwartet-fuer-2026-ein-umsatzwachstum-von-35-bis-40-prozent/)
- [Solarserver: 1Komma5° macht mehr Umsatz und steigert Profit](https://www.solarserver.de/2026/09/22/photovoltaik-1komma5-macht-mehr-umsatz-und-steigert-profit/)
- [Börsen-Zeitung: 1KOMMA5° erwartet deutliches Umsatzplus](https://www.boersen-zeitung.de/unternehmen-branchen/1komma5-erwartet-deutliches-umsatzplus)
- [Sifted: Energy unicorn 1Komma5 raises €70m as IPO plans remain on ice](https://sifted.eu/articles/energy-unicorn-1komma5-raises-e70m-as-ipo-plans-remain-on-ice/) (CDP)
- [Sifted: Philipp Schröder profile](https://sifted.eu/articles/philipp-schroeder-brunch)
- [Tech Funding News: 1KOMMA5 raises €70M at $1.35B valuation](https://techfundingnews.com/german-energy-unicorn-1komma5-raises-e70m-at-1-35b-valuation-as-it-eyes-us-expansion-and-ipo/)
- [tech.eu: 1KOMMA5° raised €430 million and became a unicorn (2023)](https://tech.eu/2023/06/23/hamburg-s-1komma5-has-raised-430-million-and-just-become-a-unicorn-at-just-23-months-old)
- [StartupHub: 1KOMMA5 extends €150M pre-IPO round (Jul 2025)](https://www.startuphub.ai/news/1komma5-extends-150m-pre-ipo-round-for-energy-software)
- [Trending Topics: operativ profitabel, 520 Mio. Euro Umsatz für 2024](https://www.trendingtopics.eu/operativ-profitabel-1komma5-berichtet-520-mio-euro-umsatz-fuer-2024/)
- [Trending Topics: Umsatzziele um 200 Mio. Euro verpasst](https://www.trendingtopics.eu/1komma5-umsatzziele-um-200-mio-euro-verpasst-und-trotzdem-profitabel)
- [Trending Topics: 1Komma5°: Scale-up soll hart gegen Betriebsrat vorgehen (28 Jun 2024)](https://www.trendingtopics.eu/1komma5-scale-up-soll-hart-gegen-betriebsrat-vorgehen/) (CDP)
- [NORD/LB: NORD LB and Deutsche Bank provide up to EUR 500 million (May 2026)](https://www.nordlb.com/fileadmin/redaktion/Presse/pdf/2026/20260518_1KOMMA5____NORD_LB_and_Deutsche_Bank_provide_up_to_EUR_500_million_for_the_public_sector.pdf)
- [pv magazine: Enpal schließt Vertriebsstandort Hamburg (Jul 2026)](https://www.pv-magazine.de/2026/07/29/enpal-schliesst-vertriebsstandort-hamburg-mit-knapp-85-mitarbeitern/)
- [Glassdoor: 1KOMMA5° overview](https://www.glassdoor.de/%C3%9Cberblick/Arbeit-bei-1KOMMA5%C2%B0-EI_IE5747703.11,19.htm) (CDP)
- [Glassdoor: 1KOMMA5° reviews](https://www.glassdoor.de/Bewertungen/1KOMMA5%C2%B0-Bewertungen-E5747703.htm) (CDP)
- [Glassdoor: 1KOMMA5° salaries](https://www.glassdoor.de/Gehalt/1KOMMA5%C2%B0-Geh%C3%A4lter-E5747703.htm) (CDP)
- [Glassdoor: 1KOMMA5° interviews](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/1KOMMA5%C2%B0-Fragen-im-Vorstellungsgespr%C3%A4ch-E5747703.htm) (CDP)
- [Kununu: 1KOMMA5° GmbH profile](https://www.kununu.com/de/1komma5-deutschland) (CDP)
- [Kununu: reviews, IT department filter](https://www.kununu.com/de/1komma5-deutschland/kommentare?department=it) (CDP)
- [Kununu: all reviews](https://www.kununu.com/de/1komma5-deutschland/kommentare) (CDP)
- [Kununu: salaries](https://www.kununu.com/de/1komma5-deutschland/gehalt) (CDP)
- [Indeed: 1KOMMA5˚ reviews](https://de.indeed.com/cmp/1komma5/reviews)
- [Teamblind: 1KOMMA5 (not found)](https://www.teamblind.com/company/1KOMMA5/) (CDP)
- [levels.fyi: 1komma5 (not found)](https://www.levels.fyi/companies/1komma5/salaries/software-engineer) (CDP)
- [levels.fyi: Software Engineer salaries, Germany](https://www.levels.fyi/Salaries/Software-Engineer/Germany)
- [levels.fyi: Software Engineer salaries, Berlin](https://www.levels.fyi/Salaries/Software-Engineer/Berlin-Germany)
- [1KOMMA5° Personio careers XML feed (326 postings, 2026-11-11)](https://1komma5grad.jobs.personio.de/xml?language=en) (curl)
- [Personio: Staff Engineer - Heartbeat AI](https://1komma5grad.jobs.personio.com/job/2740345?display=en)
- [Personio: (Senior) Product Engineer - Heartbeat](https://1komma5grad.jobs.personio.com/job/2645786)
- [Personio: (Senior) Platform Engineer, Berlin, Munich, or Hamburg](https://1komma5grad.jobs.personio.de/job/2040319)
- [wearedevelopers: (Senior) Site Reliability Engineer - Platform & Agentic Operations](https://www.wearedevelopers.com/en/jobs/ext/6496166/senior-site-reliability-engineer-platform-agentic-operations)
- [startup.jobs: Senior Software Engineer - Device Connectivity (Go)](https://startup.jobs/senior-software-engineer-device-connectivity-go-m-f-d-1komma5-8731172)
- [jobgether: Senior IoT Cloud Engineer](https://jobgether.com/offer/6a3df2622da8cde35c743ace-senior-iot-cloud-engineer-m-f-d)
- [Great Place to Work: certified company search result (shopware AG, not 1KOMMA5°)](https://www.greatplacetowork.com/certified-company/102033883) (CDP)
- [OpenStreetMap Nominatim: Pacellistraße 2, 80333 München](https://nominatim.openstreetmap.org/search?q=Pacellistra%C3%9Fe+2,+80333+M%C3%BCnchen&format=json&addressdetails=1) (curl)
- [Overpass API (nearby stops query)](https://overpass-api.de/api/interpreter) (curl)
