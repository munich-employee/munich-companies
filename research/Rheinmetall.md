# Rheinmetall - Full Research Report

_Researched: 2026-11-19_


> **Disqualifiers**
> 1. **No software-engineering roles in Munich.** Rheinmetall's Munich postings belong to Rheinmetall MAN Military Vehicles (military trucks: project management, controlling, sales, ILS), the ARTEC Boxer consortium (programme roles) and Rheinmetall ICEYE Space Solutions (satellite systems engineering and satellite operations). Of 158 Rheinmetall postings retrieved from LinkedIn on 2026-11-19, none was a software-development role in Munich. Software development sits in Bremen (Rheinmetall Electronics / Digital Systems), Kassel and Kiel (Landsysteme), Braunschweig (drones), Düsseldorf (group IT) and Penzberg (drones).
> 2. **German is the working language.** 72 of 85 engineering/IT postings are written in German, and 36 explicitly demand "sehr gute" or "verhandlungssichere" German (the AI Solutions Engineer role asks for German at C1). Both software roles in the Munich commuting area (Penzberg) are German-language postings, and one of them requires very good German.
> 3. **The reachable software roles are embedded C/C++.** Penzberg (Rheinmetall Technical Publications, drone system house) recruits a Software Developer Autopilot ("Sehr gute Kenntnisse in den Programmiersprachen C und C++") and an Avionik-Softwarearchitekt (C/C++, RTOS, ARINC 429/664, certification). Penzberg is also about 50 km south of central Munich.
> 4. **Not software-centric.** The CEO told the 2025 AGM that Rheinmetall employs "more than 1,000 software engineers and programmers worldwide", against 37,262 FTE (about 3%). Revenue comes from vehicles, ammunition, weapons, air defence and ships.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 1889 in Düsseldorf (137 years) |
| Employees | 37,262 FTE at 30 Sep 2026 (Germany 19,892, abroad 17,369). 6,417 of these are in the civil Power Systems business being sold, which leaves about 30,845 FTE in continuing (defence) operations. One year earlier: 31,537 FTE |
| Revenue (FY2025) | €9,935M (+29% on €7,715M). Q1-Q3 2026: €8,376M (+38%). FY2026 sales guidance was cut on 5 Nov 2026 from €14.0-14.5B to about €13.2B |
| Profitability | FY2025 operating result €1,841M (18.5% margin), net income €696M (2024: €717M). Q1-Q3 2026 operating result €1,339M (+68%), result after tax €643M - **PASS** |
| Ownership | Public: Rheinmetall AG, HRB 39401 Düsseldorf, Frankfurt Stock Exchange (RHM), DAX member. Share price €956.40 on 30 Sep 2026 vs €1,984.50 a year earlier (-52%) |
| Software-centric | No. Defence manufacturer (vehicles, ammunition, weapons, air defence, naval). Software is about 3% of headcount; the Digital Systems division is 16% of 9M 2026 sales - **FAIL** |

### Key People

- **Armin Papperger:** CEO since 2013 (at Rheinmetall since 1990), contract extended to 31 Dec 2029. Glassdoor CEO approval 82% globally, 95% in Germany. LinkedIn: no verified profile found.
- **Klaus Neumann:** CFO since 1 Jan 2025.
- **René Gansauge:** COO since 1 Jan 2025 (new board position).
- **Dr. Vera Saal:** CHRO and Arbeitsdirektorin since 1 Sep 2025.
- **Timo Haas:** CEO of the Digital Systems division (owner of the Battlesuite software platform) and managing director of Rheinmetall Electronics GmbH.

LinkedIn URLs for the board were not located through search; the profiles above come from rheinmetall.com.

### Business Model

Since 1 Jan 2026 the group runs six defence divisions: Vehicle Systems, Weapon and Ammunition, Air Defence, Digital Systems, Naval Systems (NVL shipyard, added March 2026) and a new U.S. division. The civil Power Systems division (former automotive supplier Kolbenschmidt/Pierburg) was sold to AEQUITA (Munich) in June 2026 for €350M, closing expected Q4 2026. The order backlog ("Rheinmetall Backlog", including framework agreements) stood at €78.0B on 30 Sep 2026. The customers are governments, chiefly the Bundeswehr.

### Software-Centric Assessment - FAIL

- **Headcount:** "More than 1,000 software engineers and programmers worldwide" (CEO, AGM May 2025) against roughly 31,000-37,000 FTE.
- **Digital Systems** (formerly part of Electronic Solutions) had 9M 2026 sales of €1,328M (16% of the group) at an 8.9% operating margin, against 16-19% for the group. Its growth comes from the TaWAN and D-LBO digitisation programmes and short-range air defence.
- **Battlesuite** is the group's software platform ("digital foundation for the reconnaissance and strike network"), with its interfaces published in September 2026 (GitHub: `Rheinmetall/onboardapi`, `Rheinmetall/tacticalapi`). It is a real software product, but it serves vehicle and weapon-system integration.
- **Engineering mix in postings:** of 85 engineering/IT postings retrieved, the largest groups are system developers (Systementwickler) for weapon stations, vehicles and ships, embedded C/C++, and C#/.NET Windows applications. Pure software-product roles are a minority.

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **Rheinmetall AG** (listed parent) | HRB 39401, Amtsgericht Düsseldorf | Rheinmetall Platz 1, 40476 Düsseldorf | "Die Forschung und Entwicklung, Herstellung, Vertrieb und Service von industriellen Erzeugnissen aller Art, insbesondere des Maschinenbaus, ... der Industrieelektronik, Informationstechnik und verwandter Industrien ..." |
| **Rheinmetall MAN Military Vehicles GmbH** (RMMV, Munich site) | HRB 251132, Amtsgericht München | Dachauer Str. 651, 80995 München | "Entwicklung, Herstellung und Vertrieb von logistischen Radfahrzeugen für einen militärischen Einsatz." JV: Rheinmetall 51%, MAN Truck & Bus 49%. Total assets €705.1M at 31 Dec 2025 |
| **Rheinmetall Technical Publications GmbH** (RTP, Penzberg site) | HRB 24359, Amtsgericht Bremen | Flughafenallee 3, 28199 Bremen (seat). Penzberg site: Grube 29, 82377 Penzberg | "Die Entwicklung, Herstellung und Instandsetzung von unbemannten Luftfahrzeugen und unbemannten Systemen, die Erstellung technischer Dokumentationen ..." |
| **Rheinmetall Electronics GmbH** (software hub, Battlesuite) | HRB 9659, Amtsgericht Bremen | Brüggeweg 54, 28309 Bremen | "Entwicklung, Herstellung, Vertrieb ... von elektronischen ... Systemen ... (insbesondere im Bereich der taktischen Kommunikationsinfrastruktur sowie der Infrastruktur von sog. Führungssystemen)" |
| **Rheinmetall ICEYE Space Solutions GmbH** (RISS) | HRB 24952, Amtsgericht Neuss | Industriestr. 43, 41460 Neuss | "Entwicklung, Herstellung, Integration, Erprobung und der Betrieb von Satelliten, insbesondere im Bereich Low Earth Orbit". Registered 11 Nov 2025; recruits in Munich, but no Munich street address was found |

**Verification:** All five entities were confirmed on NorthData (via CDP). They are operating companies with engineering and manufacturing purposes, not sales shells, and Rheinmetall employs staff directly through them (permanent, full-time contracts in every posting; no PEO/EOR). The Munich entity RMMV is real but builds military trucks: its development and production centre is in Vienna, and its Munich postings are business and programme roles. The ARTEC GmbH consortium (KNDS / Rheinmetall Landsysteme / Rheinmetall Defence Nederland, Boxer programme) also recruits in Munich; its registration was not checked. Rheinmetall Electronics advertised one Softwarearchitekt role with "Bremen/München" as location (ref. DE18488); the posting is closed and redirects to the job search.

**Verdict:** **PASS with CAUTION.** A Munich legal entity exists and employs directly, but it is a truck-making JV with no software-development function in Munich.

---

## Section 3: Office Location

- **Office addresses:**
  - **Munich: RMMV**, Dachauer Straße 651, 80995 München (Allach-Untermenzing, on the north-west edge of the city next to the MAN truck plant). Nominatim: 48.2115, 11.4827, tagged "Rheinmetall MAN Military Vehicles". Confirmed on RMMV's contact and data-protection pages.
  - **Munich: RISS** (Rheinmetall ICEYE Space Solutions) lists "München" on its postings; no street address was published in any source found.
  - **Penzberg: RTP**, Grube 29, 82377 Penzberg (Gewerbegebiet Auf der Grube, Landkreis Weilheim-Schongau), about 50 km south of central Munich. Nominatim: 47.7564, 11.3797, tagged "Rheinmetall". Over 150 staff in Penzberg and Iffeldorf build and maintain the ALADIN, LUNA and LUNA NG reconnaissance drones (Rheinmetall careers page).
- **Nearest public transport (Overpass, 2026-11-19):**
  - **RMMV Munich:** bus stop "Karlsfelder Straße" 645 m (OSM carries no line tags for it); nearest rail halt "Karlsfeld" (S-Bahn, MVV) about 1.7 km.
  - **RTP Penzberg:** bus stop "Penzberg, Kreisel/Grube" 147 m; "Penzberg, Zentrum" 607 m (lines 374, 391, 394, 934, 935, 940-948); Penzberg rail halt (regional line Tutzing-Kochel) about 980 m.
- **Work model:** hybrid at the employee's site, no fully remote contracts. 40+ postings list "Mobiles Arbeiten" as a benefit; two specify "40% mobiles Arbeiten möglich"; others say "anteiliges mobiles Arbeiten" or "Mobiles Arbeiten nach erfolgreicher Einarbeitung". RMMV Munich reviews describe the rule as 2 of 5 days ("Flex Work möglich, jedoch nur an 2 von 5 Wochenarbeitstagen", Kununu, Aug 2023, Angestellte/r oder Arbeiter/in, Forschung / Entwicklung, RMMV München) and say it is frowned on ("Trotz HO Regelung wird man sehr schief angeschaut", Kununu, Feb 2023, Angestellte/r oder Arbeiter/in, Forschung / Entwicklung, RMMV München). Many engineering postings require worldwide travel ("Weltweite Reisebereitschaft": 36 of 85).

---

## Section 4: Reviews

**GPTW:** No Great Place to Work certification and no appearance in "Deutschlands Beste Arbeitgeber 2026" found. Rheinmetall cites other awards instead: Forbes "World's Best Employers", Universum (place 22 among young engineers), Capital training rankings, and a DIN ISO 30414 HR-reporting certificate (Dec 2023).

### Glassdoor

| Metric | Global (654 reviews; summary panel on 169) | Germany (99 reviews) | Munich (2 reviews) | Software Engineers (4 reviews) |
|---|---|---|---|---|
| **Overall** | 3.6 | 4.2 | 3.4 | 3.7 |
| **WLB** | 3.6 | 4.4 | 5.0 | 4.1 |
| **Culture & Values** | 3.5 | 3.8 | 2.0 | 3.6 |
| **Comp & Benefits** | 3.7 | 4.3 | 4.0 | 3.5 |
| **Career Opportunities** | 3.6 | 4.0 | 3.0 | 3.3 |
| **Diversity & Inclusion** | 3.9 | 3.9 | 3.0 | 3.4 |
| **Senior Management** | 3.3 | 3.8 | 2.0 | 3.5 |
| **% Recommend** | 66% | 77% | 67% | 73% |
| **CEO Approval** | 82% | 95% | 69% | 99% |
| **Business Outlook** | 68% positive | 91% positive | 55% positive | 21% positive |

- Munich (2 reviews) and Software Engineers (4 reviews; the "Softwareentwickler" title filter gives 5 reviews and 3.6 overall, 4.1 WLB, 64% recommend) are far below 20 reviews: **directional only**. The CEO-approval and outlook percentages on these small filters are Glassdoor model outputs, not real shares.
- The Germany page shows slightly different sub-scores in its FAQ block (WLB 4.3, Culture 3.9, Career 4.1, 79% recommend); the table uses the summary panel.
- Germany's reviews are mostly from Bremen (26), Düsseldorf (21), Neuss (16) and Unterlüß (15); Munich has 3 tagged reviews.
- Rheinmetall BAE Systems Land (UK JV) has its own Glassdoor page (3.2, 24 reviews) and is not included.

### Kununu

Profile `rheinmetall-group` (covers all German group companies; read via CDP):

- **Overall score:** 3.7 / 5.0 (industry average Maschinenbau 3.7)
- **Recommendation rate (Weiterempfehlung):** 77% (last 2 years)
- **Total reviews:** 2,905 (employee reviews: 1,820)
- **Kununu Top Company:** NO (no seal on the profile; no announcement found)
- **Factor scores:** Karriere & Gehalt 3.6, Unternehmenskultur 3.7, Arbeitsumgebung 3.6, Vielfalt 4.0. Best factor: Umgang mit älteren Kollegen 4.1. Worst: Kommunikation 3.2 (496 reviews). Karriere/Weiterbildung 3.4.

Filtered views of the same profile:

| Filter | Reviews | Score | Recommend |
|---|---|---|---|
| Department IT | 121 | 3.8 | 68% |
| City München | 67 | 3.8 | 58% |
| City Penzberg | 13 | 3.7 | 69% |
| Company Rheinmetall MAN Military Vehicles GmbH | 35 | 3.7 | 51% |
| Company Rheinmetall Technical Publications GmbH (Bremen + Penzberg) | 40 | 3.3 | 68% |

### Blind / Teamblind

No company page (`teamblind.com/company/Rheinmetall/reviews` returns "Page not found"); Blind search returns only a June 2025 news item on a drone partnership with Anduril. **No Blind data.**

### Review Themes (2023-2026)

**Positives:**
- **Job security and a stable employer.** "Großes Unternehmen und dadurch Job Sicherheit." (Glassdoor, Oct 2024, current Software developer, Bremen, 5+ years). "Sichere Arbeitgeber mit viel Potential." (Kununu, Feb 2026, Angestellte/r oder Arbeiter/in, IT, Rheinmetall IT Solutions GmbH, Düsseldorf).
- **Tariff pay, 35-hour week, time accounts.** "gutes Gehalt (IG Metall Tarif)" (Glassdoor, Aug 2024, current Software engineer, Bremen, less than 1 year). "Die 35-Stunden-Woche ist ein echter Vorteil. ... Die daraus entstandenen Überstunden können aber flexibel durch Freizeit ausgeglichen werden." (Kununu, Jul 2026, Angestellte/r oder Arbeiter/in, IT, NVL B.V. & Co. KG, Bremen). "Betriebsrat, Tarifvertrag und eine sehr gute Kantine sind eine tolle Sache." (Glassdoor, Nov 2020, current Software engineer, Hamburg).
- **Interesting work, good pay.** "Interessante und abwechslungsreiche Aufgaben, eine gute Vergütung und grundsätzlich gute Rahmenbedingungen." (Kununu, Aug 2026, Ex-Angestellte/r oder Arbeiter/in, IT, Rheinmetall Electronics GmbH, Bremen).
- **Flexible hours** (Gleitzeit, Vertrauensarbeitszeit) recur across Kununu and Glassdoor. Glassdoor Germany rates WLB 4.4.

**Negatives:**
- **Poor communication and silo culture** (Kununu's lowest factor, 3.2). "Vetternwirtschaft, Silo-Denken, Ich Chef du Nix Mentalität und bitte bitte bitte Kommunikation." (Kununu, Nov 2025, Angestellte/r oder Arbeiter/in, IT, Rheinmetall AG, Düsseldorf). "Informationen für die tägliche Arbeit muss man sich mühsam zusammensuchen." (Kununu, Jul 2026, Angestellte/r oder Arbeiter/in, IT, NVL, Bremen).
- **Growth chaos and overloaded management.** "Viel Chaos durch Wachstum. Das Management ist teilweise stark überfordert" (Glassdoor, Sep 2026, current Projektmanager, München). "Die Integration der steigenden Aufträge ist ziemlich planlos" (Kununu, Apr 2026, role not shown in the overview excerpt).
- **Bureaucracy.** "Wie so oft bei Konzernen fühlt sich alles sehr träge, etwas verstaubt und bürokratisch an. ... Das Beantragen von neuer Software dauert ewig" (Glassdoor, Nov 2020, current Software engineer, Hamburg). "Langsame Großkonzern-Prozesse. Budget organisieren ist ein Albtraum" (Kununu, Mar 2026, Angestellte/r oder Arbeiter/in, Forschung / Entwicklung, RTP, Penzberg).
- **Overtime and availability (WLB red-flag overlap).** "Es herrscht eine Erwartungshaltung wo es inoffiziell heisst, mindestens 80 Stunden Woche." (Kununu, Nov 2025, Angestellte/r oder Arbeiter/in, IT, Rheinmetall AG, Düsseldorf). "Dort arbeiten alle bis zu 60Std. In der Woche. Wochenende, Abends es wird erwartet das man präsent ist und durchgehend erreichbar" (Kununu, Aug 2025, Ex-Führungskraft, RTP, Penzberg). "zu volle Überstundenkonten die lange ignoriert wurden, gerade bei Flugkampagnen wird viel abverlangt" (Kununu, Mar 2026, Angestellte/r oder Arbeiter/in, Forschung / Entwicklung, RTP, Penzberg).
- **Pay inequity and no tariff at some units.** "Keine einheitliche Gehaltsstruktur. Manche Bereiche werden besser bezahlt als andere obwohl die gleiche Arbeit geleistet wird." (Glassdoor, Nov 2024, current Softwareentwickler). "im Vergleich zum Wettbewerb eher niedrig. Unterschiede innerhalb gleicher Rollen/Tätigkeiten. (Noch) kein Haustarif" (Kununu, Mar 2026, Angestellte/r oder Arbeiter/in, Forschung / Entwicklung, RTP, Penzberg).
- **No career paths.** "Leider gibt es keine klar definierten Karrierepfade. Die einzige Aufstiegschance ist es Teamleitung / Abteilungsleitung zu werden." (Kununu, Jul 2026, Angestellte/r oder Arbeiter/in, IT, NVL, Bremen).
- **Munich site (RMMV) is the weakest Kununu sub-profile (51% recommend).** "Schlechtester Standort im ganzen Rheinmetall Konzern" (Kununu, Mar 2026, Führungskraft, Forschung / Entwicklung, RMMV München, 1.4/5). "Vorgesetzte ticken teilweise richtig aus und werden laut." (Kununu, Aug 2023, Angestellte/r oder Arbeiter/in, Forschung / Entwicklung, RMMV München). "Die HR blockiert gerne trotz Freigabe durch Vorgesetzte Schulungsbedarfe/wünsche." (Kununu, Nov 2023, Angestellte/r oder Arbeiter/in, Forschung / Entwicklung, RMMV München).
- **Exits handled badly.** "Dadurch entstand bei mir das Gefühl, eher aussortiert als fair angehört und unterstützt zu werden." (Kununu, Aug 2026, Ex-Angestellte/r oder Arbeiter/in, IT, Rheinmetall Electronics GmbH, Bremen). "Gute Mitarbeiter werden entlassen, trotz Fachkräftemangel." (Kununu, Sep 2022, Ex-Angestellte/r oder Arbeiter/in, Vertrieb / Verkauf, RMMV München).

### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | Localized. RMMV Munich R&D and RTP Penzberg draw the harshest comments: "Vorgesetztenverhalten: Bis vor kurzem - Katastrophe. Es wird jetzt deutlich besser" (Kununu, Mar 2026, Angestellte/r oder Arbeiter/in, Forschung / Entwicklung, RTP, Penzberg). Global Glassdoor: "Senior management are spineless bullies." (Glassdoor highlight, role and location not shown). Senior Management is the lowest Glassdoor global sub-score (3.3). |
| 24/7 Work Expectation | Not for software roles. The only on-call/24/7 posting found is the SOC Analyst ("24/7-Schicht-, Rufbereitschafts- und Eskalationsmodell"). One RTP Penzberg ex-manager reports evening and weekend reachability (quoted above). |
| Internal Surveillance | Minor. "Verbot der Nutzung von privaten Mobiltelefonen während der Arbeit - herausgegeben vom CEO, CHRO, etc" (Kununu, Feb 2026, role not shown in the overview excerpt). Monitoring tools are co-determined by works councils. |
| Fear-driven Management | Isolated: "Man muss dort aufpassen was man sagt, es werden Aussagen auf beruflicher Ebene schnell persönlich genommen" (Kununu, Sep 2022, Ex-Angestellte/r oder Arbeiter/in, Vertrieb / Verkauf, RMMV München). Not a recurring theme in 2025-2026 IT reviews. |
| Communication Breakdown | **Recurring.** Kununu's worst factor (3.2, 496 reviews). "Top-down und auch nur wenn es wirklich sein muss. Meistens erst wenige Tage vor der Betriebsversammlung, z.T. ohne das der Betriebsrat überhaupt etwas davon weiß." (Kununu, Feb 2026, role not shown in the overview excerpt). |
| Unpaid Overtime | Time accounts exist under the tariff (35h, voluntary extension to 40h, "Arbeitszeitkonto"). Complaints concern overfull accounts and workload, not unpaid hours. |
| Silent Firings | Some individual push-out reports (RME Bremen ex-IT, Aug 2026; RMMV sales, 2022). Works councils exist at most units, so dismissals need a §102 hearing. |
| Work-Life Balance issues | Mixed. Germany Glassdoor WLB 4.4, but overtime complaints cluster in group IT Düsseldorf and RTP Penzberg (flight campaigns). |

**Risk level: MODERATE.** The pattern is mainly (b) large-company bureaucracy and top-down communication strained by very fast growth (headcount +18% in a year, guidance cut), plus (c) localized dysfunction at RMMV Munich and at RTP Penzberg, where a reviewer reports a recent management change. Nothing points to systemic toxicity in the software hubs.

---

## Section 5: Compensation

### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| Glassdoor (DE) | Software Engineer | ~€65K (range €60.0-70.2K) | €0 | ~€5.9K (€1-7K) | ~€71K | 24 (mostly Bremen; updated 29 Dec 2025) |
| Glassdoor (DE) | Softwareentwickler | ~€55.4K (range €42-61K) | €0 | ~€2.2K | ~€57.6K | 24 (mostly Bremen) |
| Glassdoor (DE) | Senior Software Engineer | no submissions; model estimate ~$89K | n/a | n/a | n/a | 0 |
| Kununu | Softwareentwickler:in | n/a | n/a | n/a | Ø €72.3K | 30 |
| Kununu | Entwicklungsingenieur:in / Systemingenieur:in / Teamleiter:in | n/a | n/a | n/a | Ø €78.5K / €79.3K / €88.0K | 113 / n.a. / 89 |
| IG Metall Bayern ERA (RMMV Munich grid) | EG 12, Stufe B (top engineer group) | €6,650/month at 35h (from 1 Apr 2026) | €0 | Urlaubsgeld, Weihnachtsgeld, T-ZUG | ~€88-92K at 35h, ~€100-105K at 40h (estimate) | tariff table |
| levels.fyi | n/a | no Rheinmetall company page (404) | | | | 0 |

**Munich reference (market, not this employer):** Senior Software Engineer median ~€85K, 75th ~€100K, 90th ~€115-125K (levels.fyi Munich, as used in prior reports; levels.fyi shows no Rheinmetall data).

Notes: Penzberg (RTP) has no tariff ("Kein Tarif", Kununu, Mar 2026, Forschung / Entwicklung, RTP, Penzberg) and reviewers rate its pay below competitors. The Bavarian metal tariff expired on 31 Oct 2026; a new round is under way, so the 2027 grid is not yet known. Senior engineers at large metal-industry employers are often on AT (above-tariff) contracts; no Rheinmetall AT data points were found.

### Equity / Stock

- **ESPP:** "Mein Stück Rheinmetall 2.0", with a 30% employer subsidy, open after 12 months of service at participating companies. Shares carry voting and dividend rights.
- **Profit sharing:** "Erfolgsbeteiligung" / "Mitarbeiter Erfolgsbeteiligung" listed on most postings.
- **No RSUs** for engineers in evidence. The stock (RHM) roughly halved between Sep 2025 and Sep 2026 (€1,984.50 to €956.40), which shows how volatile ESPP holdings are.
- Company pension ("Rheinmetall Plus"), 30 days' leave, Wellpass, bike leasing.

### Verdict

Observed software salaries (Glassdoor €57-71K total, Kununu €72K) sit **below** the Munich senior median of about €85K. Most data points are Bremen, not Munich. The Bavarian IG Metall grid at RMMV could reach about €90K at 35h (more at 40h or AT), which would be comparable, but there are no Munich software roles to apply it to. Penzberg is untariffed and reviewed as below market.

**BELOW**

---

## Section 6: AI/ML & Tech Stack

### AI Strategy

- **Battlesuite / software-defined defence:** Rheinmetall positions itself as a "systems integrator that orchestrates multi-domain operations through a software-defined Battlesuite" (AFCEA, May 2026). Eurosatory (June 2026) showed an open reconnaissance-and-strike network from orbit to effectors. Battlesuite interfaces (OnboardAPI, TacticalAPI) were published in September 2026.
- **Digital Systems division** (since Jan 2026): TaWAN and D-LBO digitisation programmes, soldier systems, loitering munitions (FV-014), the OHB Rheinmetall Space Networks JV (SATCOMBw Stage 4, founded Nov 2026).
- **Applied AI in postings:** an "AI Applications" group in Bremen (Solution Architect and Technik Manager AI Applications, NLP); AI-based image processing for drones in Braunschweig (detection/tracking on edge devices); a data lakehouse "foundation for machine learning, AI-based applications, and autonomous systems" (Data Engineer, Bremen); an internal enterprise AI platform with LLMs and vector databases (AI Solutions Engineer, Kassel/Kiel/Unterlüß, forward-deployed style).
- **Planned AI and technology centre in Neuss:** the CEO spoke of "500 Wissenschaftler ..., die die künstliche Intelligenz machen" and a reported €250M investment (dpa / Rheinische Post, 2026). Details are still being agreed.
- **Partnerships:** a 2022 AI partnership with a Munich defence-AI software company for land systems; a 2025 drone partnership with Anduril; the ICEYE satellite JV (SPOCK 1, about €1.7B Bundeswehr contract, Dec 2025).

The AI work is genuine but applied and embedded: perception on drones, data fusion, command-and-control integration and enterprise LLM use cases. None of it is in Munich.

### Tech Stack

Derived from 158 current or recent LinkedIn postings in Germany (full text via the voyager API, 2026-11-19), rheinmetall.com job pages and the public GitHub organisation `Rheinmetall` (4 repos: `tacticalapi` in C#, `onboardapi`, `onboardapi-digital-twin`, `onboardapi-inspector`). No engineering blog, StackShare or conference-talk sources were found.

| Category | Technologies |
|---|---|
| **Primary language(s)** | C/C++ (embedded, avionics, data fusion, low-latency), C#/.NET (UWP, MAUI, MVVM Windows apps; TacticalAPI), Java (signal processing), Python (data, AI, scripting, tests), TypeScript/Angular 19 (web UIs). Ada and Rust appear as nice-to-haves (avionics) |
| **AI/ML** | PyTorch, TensorFlow, ONNX, OpenVINO, YOLO, SORT/DeepSORT, Vision Transformers, LLMs, RAG, multi-agent systems, vector databases, NLP |
| **Cloud** | Azure (ARO, AKS) in group IT; mission systems largely on-prem / classified networks |
| **Infrastructure** | Linux (RHEL, embedded Linux), RTOS, OpenShift, Kubernetes, Docker, Terraform, Ansible, GitLab CI, Jenkins, Argo CD, Helm, Tekton, Prometheus/Grafana, CheckMK, Keycloak/Red Hat IdM |
| **Data** | Data lakehouse on object storage, batch and streaming pipelines, SQL, DDS middleware, geospatial/image/sensor data, SAP (BDC, SAC) for enterprise |
| **Other** | MATLAB/Simulink, AUTOSAR (DaVinci), ROS 2, PX4, MAVLink, ARINC 429/664, CAN, MapLibre, deck.gl, Apache ECharts, UML/SysML, DOORS, Teamcenter, V-model |

**Summary:** Polyglot, with a C/C++ and C#/.NET core around weapon, vehicle, avionics and command systems, Java and TypeScript for C2/web front ends, and Python in data, AI and test roles. AI/ML is applied and edge-oriented (PyTorch/ONNX/OpenVINO perception on drones, data fusion) plus an internal LLM platform, on Kubernetes/OpenShift with Azure in group IT. Applied defence engineering in a regulated domain, not research.

---

## Section 7: Language

- **72 of 85** engineering/IT postings are written in German; **36** explicitly require "sehr gute", "fließende" or "verhandlungssichere" German. Examples: Software Developer Autopilot, Penzberg ("Sehr gute Deutsch- und Englischkenntnisse in Wort und Schrift"); AI Solutions Engineer ("Sehr gute Deutsch-, sowie Englischkenntnisse in Wort und Schrift (mind. C.1)"); Software Engineer, Platform Pre-Development, Kassel ("Very good written and spoken German").
- English-only postings exist in two places: Bremen's newer platform/data roles (Data Engineer, Cyber Security Engineer DevSecOps: "strong written and spoken English") and the RISS satellite JV in Munich (all English).
- Kununu reviews, benefits pages and HR communication are German; the group's working culture is German-speaking.

**Verdict:** **FAIL** for the Munich-area software roles (German-language, very good German required). **CONDITIONAL** only for RISS Munich, whose roles are English-language but are systems engineering and satellite operations, not software engineering.

---

## Section 8: Stability

### Financial Position

- **FY2025:** sales €9,935M (+29%), operating result €1,841M (18.5%), net income €696M (slightly down from €717M), dividend proposal €11.50 (from €8.10). Backlog €63.8B at year-end.
- **Q1-Q3 2026:** sales €8,376M (+38%), operating result €1,339M (16.0% margin), result after tax €643M, backlog €78.0B (incl. €23.7B frame backlog).
- **Cash and debt:** operating free cash flow from continuing operations **-€1,698M** for 9M 2026; liquid funds €636M; net financial debt **€2,901M** at 30 Sep 2026 (net liquidity of €369M at 31 Dec 2025), funded by a €1.0B syndicated loan, a €500M bond and €810M short-term deposits. Equity ratio fell to 28.3%. The company dropped its cash-conversion target (>40%).
- **Guidance cut (5 Nov 2026):** FY2026 sales to about €13.2B (from €14.0-14.5B), margin to about 18.5% (from about 19%), citing delays to the Arminius Boxer contract and 155mm ammunition acceptance tests. The share price halved year on year.
- **Trend:** strongly growing and profitable, but working capital is absorbing cash. No credit rating was retrieved.

### Financial Runway

Not applicable: Rheinmetall is a profitable listed company. The relevant liquidity signal is the negative 9M free cash flow funded by new debt, noted above.

### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| Jun 2026 (closing Q4 2026) | Sale of civil Power Systems division to AEQUITA (Munich) for €350M | ~6,250 employees transferred | Divestment, not layoffs. AEQUITA intends to keep all employees. Feb 2026: transition collective agreement with IG Metall and the works councils for job, site and tariff security |
| 2024-2026 | Neuss automotive plant converted to defence (satellites, drones, turrets) | Neuss headcount fell from 1,500 to "well under 1,000" | Shrinkage happened during the automotive decline; the conversion plans +700 jobs |
| 2025-2026 | Berlin Pierburg plant converted to artillery-shell components | 293 employees moved to Rheinmetall Waffe Munition; ~40 development staff stay with Pierburg | Negotiated with works council and IG Metall Berlin (job retention, investment, retraining) |

No layoffs in the defence business were found. Defence headcount is growing fast: group FTE rose from 31,537 to 37,262 in twelve months (Germany 16,156 to 19,892).

### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | **YES** (group-wide; at RMMV Munich; RTP Penzberg not confirmed) | Konzernbetriebsrat since 1972 (chair Sven Schmidt). RMMV's HR replies on Kununu tell reviewers to speak to "dem Betriebsrat". Parity co-determination on the Rheinmetall AG supervisory board; RTP, Nitrochemie Aschau and Rheinmetall IT Solutions became subject to supervisory-board co-determination in 2024 |
| Collective agreement | **Mostly IG Metall.** RMMV Munich: IG Metall Flächentarif (Bayern ERA): "Bezahlung nach IG Metall Tarif" (Kununu, Nov 2023, F&E, RMMV München). Neuss: Metall NRW tariff. Rheinmetall Electronics Bremen: Haustarif with IG Metall since ~2020, renewed spring 2026 with more pay and a new working-time model. **RTP Penzberg: NONE** ("Kein Tarif", "(Noch) kein Haustarif", Kununu, Mar 2026) | Kununu reviews and employer replies; IG Metall Bremen Bezirk newsletter 5/6 2026; Rheinmetall press release 13 Feb 2026 |
| European works council | **YES** | Established May 2000; chaired by Martin Wolfgang Hoffmann since 2023 |
| Conflict signals | No union-busting found. The first RME tariff took four years of negotiation; IG Metall Bremen campaigned publicly in Feb 2026. Kununu reviews mention repeated complaints to the works council in group IT | IG Metall Bremen 3/4 and 5/6 2026; Kununu |

**Verdict:** **PASS** for the group and the Munich entity (works council plus IG Metall tariff). **CAUTION** for RTP Penzberg (no tariff; works council not confirmed).

---

## Section 9: Regulated Industry

Rheinmetall works in the most regulated part of German industry:
- **Export control:** AWG/AWV and the War Weapons Control Act (KWKG); US components bring ITAR exposure.
- **Classified information:** VS-NfD handling and security clearances under the SÜG ("Bereitschaft zur Sicherheitsüberprüfung (VS-Verpflichtung gemäß SÜG)", RTP Penzberg posting); RISS handles "facility security clearances". Several postings require EU or German citizenship.
- **Military airworthiness:** RTP Penzberg is a "zertifizierter militärisch luftfahrttechnischer Betrieb"; the avionics architect must meet "Luftfahrtstandards und Zertifizierungsvorgaben" (real-time, redundancy, V-model).
- **Process overhead:** V-model development, requirements in DOORS, configuration management, AQAP quality standards, safety analyses (FTA, hazard analysis), functional safety for vehicles (system safety engineer for software-defined vehicles).

The practical effect is documentation-heavy, certification-gated delivery with slow tooling approval ("Das Beantragen von neuer Software dauert ewig") and on-site work for classified projects.

**Verdict:** **CAUTION**

---

## Section 10: On-Call

- Only 1 of 158 postings mentions on-call: the Senior Specialist SOC Analyst in Düsseldorf ("24/7-Schicht-, Rufbereitschafts- und Eskalationsmodell").
- No software-development, data or AI posting mentions Rufbereitschaft or on-call. The products are delivered systems (vehicles, drones, C2 software), not a 24/7 SaaS.
- Load comes instead from **travel** (36 of 85 engineering postings ask for worldwide travel), **test and flight campaigns** (RTP Penzberg overtime), and maintenance windows in IT ("Wartungsfenster außerhalb der regulären Arbeitszeit", Kununu, Jul 2026, IT, NVL Bremen).

**Verdict:** **PASS** (no on-call for software roles; travel and campaign overtime are team-dependent)

---

## Section 11: Interview Process

Based on Glassdoor (all roles, Germany site).

| Metric | Value |
|---|---|
| Difficulty | 2.75 / 5 (129 ratings) |
| Positive experience | 75% (131 interviews; 13% negative) |
| Average duration | ~35 days |
| Rounds | Typically 1-2 (phone screen, then an on-site or video interview with the team lead; sometimes a group interview, test or presentation) |

- **Stages reported:** phone interview 21%, group interview 18%, one-to-one 16%, qualification test 11%, background check 11%, presentation 8%, personality test 4%, IQ test 3%, drug test 3%.
- **Software Engineer filter:** only 3 interviews ("mixed", 0% positive, 33% negative).
- **Character:** experience-based conversations with the hiring manager; no LeetCode-style coding rounds reported. Processes are slow: "mindestens 4 Woche wartungzeit für die erste Rückmeldung. Direkt Vor ort Gespräch mit Team lead für 2 Stunden und dann ungefähr 3 Wochen Zeit um die Rückmeldung zu erhalten." and "Bewerbungszeiträume von bis zu einem 1 Jahr" (Glassdoor interview reviews; role and date were not captured). An English-language reviewer left because "the process took significantly longer than expected".
- Defence roles add a background or security check (SÜG) that can delay the start date.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | **FAIL**: defence manufacturer; ~1,000+ software engineers of ~37K FTE; Digital Systems is 16% of sales |
| Not consulting | **PASS**: product and system manufacturer, own payroll |
| Profitable | **PASS**: FY2025 net income €696M; 9M 2026 operating result €1.34B. Caveat: -€1.7B 9M free cash flow, net debt €2.9B, guidance cut |
| Employee count | 37,262 FTE (30,845 continuing after the Power Systems sale) |
| English-speaking | **FAIL**: 72/85 postings in German, 36 require very good German (C1 in one AI role); only the RISS JV is English-language |
| Local entity + engineering contracts | **PASS with CAUTION**: RMMV GmbH (HRB 251132 München) employs directly, but builds military trucks and has no Munich software function |
| Location / work model | Munich-Allach (RMMV) and Munich (RISS, address unknown); software roles nearest Munich are in Penzberg (~50 km south). Hybrid, typically 40% / 2 days mobile |
| Glassdoor | 3.6 global (654), 4.2 Germany (99), Munich 2 reviews, SWE 4 reviews |
| Kununu | 3.7, 77% recommend (1,820 employee reviews); IT 3.8/68%; München 3.8/58%; RMMV 3.7/51%; RTP 3.3/68%; no Top Company |
| Salary | **BELOW**: Glassdoor SWE ~€71K total, Kununu developers Ø €72K (mostly Bremen); Bavarian tariff EG12 ~€90K at 35h; no levels.fyi data |
| AI/ML content | Applied and edge AI (drone perception, data fusion, internal LLM platform), Battlesuite C2 platform; planned 500-person AI centre in Neuss. None in Munich |
| Computer-language/Tech-stack | Polyglot: C/C++, C#/.NET, Java, TypeScript/Angular, Python for data/AI; Kubernetes/OpenShift, Azure in IT |
| No on-call | **PASS**: only the SOC analyst role has 24/7 on-call; software roles do not |
| WLB / Stability | Glassdoor DE WLB 4.4; overtime complaints in group IT and RTP Penzberg; strong order book, rapid growth, no defence layoffs; cash flow negative |
| Works council / collective agreement | **PASS** (group, RMMV Munich: works council + IG Metall); **CAUTION** at RTP Penzberg (no tariff) |
| Regulated industry | **CAUTION**: export control, SÜG clearances, military airworthiness, V-model |
| Review themes | Job security, tariff pay and 35h week vs. poor communication, growth chaos, bureaucracy, localized bad management at RMMV Munich and RTP Penzberg |
| Interview | 2.75/5 difficulty, 75% positive, ~35 days, experience-based, slow; security checks |
| Commute | RMMV Munich-Allach is inside the city; Penzberg (the only nearby software site) is ~50 km south |

---

## Section 13: Verdict

**Exclude.** Rheinmetall is a profitable, fast-growing, union-covered employer, but it offers no English-language software-engineering role in or near Munich, and the software roles that do exist near Munich are German-language embedded C/C++ avionics jobs in Penzberg.

**Strengths:** a €78B backlog and 18% headcount growth with no defence layoffs; works councils, a European works council, parity co-determination and IG Metall tariffs at most German units (including the Munich RMMV entity); a 35-hour tariff week with time accounts; an ESPP with a 30% subsidy; no on-call for software roles; a Glassdoor Germany rating of 4.2 and WLB of 4.4; and genuine investment in software (Battlesuite, Digital Systems, a planned AI centre in Neuss).

**Hard blockers:**
1. **No Munich software roles.** All Munich postings are RMMV truck programme/business roles, ARTEC Boxer programme roles or RISS satellite systems engineering. Software development is concentrated in Bremen, Kassel/Kiel, Braunschweig and Düsseldorf, 500-800 km away, with no fully remote contracts.
2. **German required.** 72 of 85 engineering postings are written in German and 36 require very good German; the nearest software role (Software Developer Autopilot, Penzberg) asks for "Sehr gute Deutsch- und Englischkenntnisse", and the AI Solutions Engineer role asks for German at C1.
3. **Embedded C/C++ in the reachable roles.** The two Penzberg software roles are autopilot and avionics software in C/C++ with RTOS, ARINC and airworthiness certification. Penzberg is also about 50 km south of central Munich, outside a 45-minute peak car commute.
4. **Not software-centric.** About 3% of staff are software engineers; revenue is vehicles, ammunition, weapons and ships.

**Secondary concerns:**
- **Regulation:** export control, SÜG security clearances, military airworthiness and V-model processes slow delivery and tie classified work to the office.
- **Pay:** observed software pay (Glassdoor ~€71K total, Kununu Ø €72K) is below the Munich senior median; RTP Penzberg is untariffed and reviewed as below market.
- **Culture under strain:** communication is Kununu's lowest-rated factor (3.2), reviewers describe growth chaos and overloaded management, and the Munich RMMV sub-profile has only 51% recommendation, with reports of shouting managers and HR blocking training.
- **Finances:** cash flow is negative (-€1.7B in 9M 2026), net debt reached €2.9B, guidance was cut in November 2026 and the share price halved in a year. Not a stability threat given the backlog, but a sign of execution pressure.
- **RISS (Munich):** the satellite JV recruits in English in Munich, but it is a one-year-old joint venture whose postings stress "thrives under pressure" and "sustained drive ... under pressure". Its roles are systems engineering and satellite operations, not software development.

**Recommendation:** Exclude Rheinmetall for senior/staff software roles. No further research is warranted unless Rheinmetall opens an English-language Python, data or AI software role in Munich at a tariff-bound entity with a works council (for example a Digital Systems or RISS software team in Munich). In that case, re-check the specific role's German requirement, security-clearance needs, hybrid days and whether the contract is tariff or AT.

---

## Sources

- [Rheinmetall: Financial report for Q3 2026 (press release, 5 Nov 2026)](https://www.rheinmetall.com/en/media/news-watch/news/2026/11/2026-11-05-rheinmetall-news-quarterly-statement-q3)
- [Rheinmetall Quartalsmitteilung Q3 2026 (PDF)](https://www.rheinmetall.com/Rheinmetall%20Group/Investor%20Relations/Ver%C3%B6ffentlichungen/2026/Q3/Rheinmetall-Quartalsmitteilung-2026-Q3.pdf)
- [Rheinmetall presents annual report for 2025 (11 Mar 2026)](https://www.rheinmetall.com/en/media/news-watch/news/2026/03/2026-03-11-rheinmetall-presents-annual-report-for-2025)
- [Rheinmetall Jahresabschluss 2025 (PDF)](https://ir-api.eqs.com//media/document/ce764c33-fe6e-4a9f-becf-1d3077cb877d/assets/Rheinmetall-Jahresabschluss-2025.pdf)
- [Rheinmetall AGM speech, Armin Papperger, 13 May 2025 (PDF)](https://ir.rheinmetall.com/media/document/50bb9574-5f55-4b13-b4bc-90d7a702ef8b/assets/Rheinmetall_HV-Rede_Herr_Papperger_2025_05_13.pdf)
- [Forecast International: European rearmament drives Rheinmetall sales and backlog in 2025](https://dsm.forecastinternational.com/2026/03/11/european-rearmament-push-drives-rheinmetall-sales-and-record-defense-backlog-in-2025/)
- [defence-industry.eu: Rheinmetall reports record €9.9 billion sales in 2025](https://defence-industry.eu/rheinmetall-reports-record-e9-9-billion-sales-in-2025-as-defence-demand-drives-growth-and-major-order-backlog-expansion/)
- [GuruFocus: Rheinmetall Q3 2026 earnings call highlights (guidance cut)](https://www.gurufocus.com/news/9180626/rheinmetall-ag-rnmbf-q3-2026-earnings-call-highlights-strong-sales-growth-offset-by-guidance-cut-and-contract-delays)
- [Rheinmetall Executive Board overview](https://www.rheinmetall.com/en/company/management/executive-board/executive-board-overview)
- [Rheinmetall: Deal finalised, Rheinmetall divests its civilian division (3 Jun 2026, PDF)](https://www.rheinmetall.com/Rheinmetall%20Group/Presse/News/Documents/2026/06/2026-06-03-deal-finalised-rheinmetall-divests-its-civilian-division.pdf)
- [Defense News: Rheinmetall sells struggling auto division to focus on defense](https://www.defensenews.com/global/europe/2026/06/04/rheinmetall-sells-struggling-auto-division-to-focus-on-defense/)
- [Rheinmetall: Überleitungstarifvertrag Rheinmetall Power Systems (13 Feb 2026)](https://www.rheinmetall.com/de/media/news-watch/news/2026/02/2026-02-13-ueberleitungstarifvertrag-rheinmetall-power-systems)
- [Logistik Heute (dpa): Geplantes KI- und Technologiezentrum in Neuss](https://logistik-heute.de/news/rheinmetall-geplantes-ki-und-technologiezentrum-neuss-soll-zum-jobmotor-werden-281688.html)
- [der Freitag: Rheinmetall im Berliner Wedding](https://www.freitag.de/autoren/peter-nowak/rheinmetall-im-berliner-wedding-wie-eine-autofabrik-zur-ruestungsschmiede-wird)
- [IG Metall Berlin: Beschäftigte dürfen nicht zum Spielball der Rüstungsdebatte werden (2026)](https://www.igmetall.de/berlin/aktuelles/2026/q3/beschaeftigte-duerfen-nicht-zum-spielball-der-ruestungsdebatte-werden)
- [IG Metall Bremen Bezirk newsletter 5/6 2026 (Rheinmetall Electronics tariff, PDF)](https://www.igmetall.de/download/20260422_Bezirk_05_06_2026_400_komplett_1e1d275095dc9cdcf89d0417061ad5a515aefd92.pdf)
- [IG Metall Bremen Bezirk newsletter 3/4 2026 (PDF)](https://www.igmetall.de/download/20260220_Bezirk_03_04_2026_400_komplett_cbcf1add935b260d5cf13b2fae28bf22369fba7b.pdf)
- [Rheinmetall: Mitbestimmung (works councils, European works council)](https://www.rheinmetall.com/de/verantwortung/mitarbeiter/mitbestimmung)
- [Rheinmetall: Arbeitnehmervertreter im Aufsichtsrat](https://www.rheinmetall.com/de/unternehmen/gremien/aufsichtsrat/vertreter-aufsichtsrat)
- [Rheinmetall: Leistung und Vergütung (ESPP "Mein Stück Rheinmetall")](https://www.rheinmetall.com/de/karriere/rheinmetall-als-arbeitgeber/leistung-verguetung)
- [Rheinmetall: Attractive employer (awards)](https://rheinmetall.com/en/responsibility/employees/attractive-employer)
- [NorthData: Rheinmetall AG, HRB 39401 Düsseldorf](https://www.northdata.de/Rheinmetall%20AG,%20D%C3%BCsseldorf/Amtsgericht%20D%C3%BCsseldorf%20HRB%2039401)
- [NorthData: Rheinmetall MAN Military Vehicles GmbH, HRB 251132 München](https://www.northdata.de/Rheinmetall%20MAN%20Military%20Vehicles%20GmbH,%20M%C3%BCnchen/Amtsgericht%20M%C3%BCnchen%20HRB%20251132)
- [NorthData: Rheinmetall Technical Publications GmbH, HRB 24359 Bremen](https://www.northdata.de/Rheinmetall%20Technical%20Publications%20GmbH)
- [NorthData: Rheinmetall Electronics GmbH, HRB 9659 Bremen](https://www.northdata.de/Rheinmetall%20Electronics%20GmbH)
- [NorthData: Rheinmetall ICEYE Space Solutions GmbH, HRB 24952 Neuss](https://www.northdata.de/Rheinmetall%20ICEYE%20Space%20Solutions%20GmbH)
- [Rheinmetall MAN Military Vehicles: About us](https://www.rheinmetall.com/en/company/subsidiaries/rheinmetall-man-military-vehicles/about-us)
- [Rheinmetall MAN Military Vehicles: Data protection (Munich address)](https://www.rheinmetall.com/en/company/subsidiaries/rheinmetall-man-military-vehicles/data-protection)
- [Rheinmetall: Karriere in Penzberg](https://www.rheinmetall.com/de/karriere/inside-rheinmetall-careers/standorte/rheinmetall-in-penzberg)
- [Rheinmetall: RTP GmbH Factsheet Penzberg (PDF)](https://www.rheinmetall.com/Rheinmetall%20Group/Karriere/Rheinmetall%20als%20Arbeitgeber/Menschen-Projekte/penzberg/RTP_GmbH_Factsheet_Penzberg_de.pdf)
- [Rheinmetall: Takeover of drone maker EMT (2021)](https://www.rheinmetall.com/de/media/news-watch/news/2021/2021-11-23_strategische-portfolio-erweiterung)
- [Rheinmetall: RISS provides the Bundeswehr with access to SAR satellites (6 Oct 2026)](https://www.rheinmetall.com/en/media/news-watch/news/2026/10/2026-10-06-rheinmetall-iceye-space-solutions-provides-the-bundeswehr-with-access-to-sar-satellites)
- [ICEYE: ICEYE and Rheinmetall win major contract for space reconnaissance](https://www.iceye.com/newsroom/press-releases/iceye-and-rheinmetall-win-major-contract-worth-billions-for-space-reconnaissance)
- [Rheinmetall: Battlesuite at Eurosatory 2026](https://www.rheinmetall.com/en/media/news-watch/news/2026/06/2026-06-15-rheinmetall-battlesuite-the-digital-foundation-for-reconnaissance-and-strike-network-new-at-eurosatory)
- [Rheinmetall: Battlesuite interfaces published (9 Sep 2026)](https://www.rheinmetall.com/de/media/news-watch/news/2026/09/2026-09-09-rheinmetall-veroeffentlicht-battlesuite-schnittstellen)
- [Rheinmetall at AFCEA 2026](https://www.rheinmetall.com/de/media/news-watch/news/2026/05/2026-05-11-rheinmetall-auf-der-afcea-2026)
- [Rheinmetall Battlesuite product page](https://www.rheinmetall.com/en/products/digital-forces/battlesuite)
- [GitHub: Rheinmetall organisation (tacticalapi, onboardapi)](https://github.com/rheinmetall)
- [Rheinmetall job: Softwareentwickler - Battlesuite (Bremen)](https://www.rheinmetall.com/en/job/softwareentwickler_battlesuite/1216466)
- [Rheinmetall job search (vacancies)](https://www.rheinmetall.com/en/career/vacancies)
- [LinkedIn job: Software Developer Autopilot, Penzberg](https://www.linkedin.com/jobs/view/4455016777)
- [LinkedIn job: Avionik-Softwarearchitekt, Penzberg](https://www.linkedin.com/jobs/view/4452265206)
- [LinkedIn job: Security Systems Engineer, RISS Munich](https://www.linkedin.com/jobs/view/4463197646)
- [LinkedIn job: (Senior) Systems Engineer Ground Segment, RISS Munich](https://www.linkedin.com/jobs/view/4463441266)
- [LinkedIn job: Satellite Operations Specialist, RISS Munich](https://www.linkedin.com/jobs/view/4466968045)
- [LinkedIn job: Abteilungsleiter Rechnungswesen & Treasury, RMMV Munich](https://www.linkedin.com/jobs/view/4476643043)
- [LinkedIn job: Data Engineer, Bremen](https://www.linkedin.com/jobs/view/4473408985)
- [LinkedIn job: AI Solutions Engineer, Kiel/Kassel/Unterlüß](https://www.linkedin.com/jobs/view/4451209001)
- [LinkedIn job: Solution Architect - AI Applications, Bremen](https://www.linkedin.com/jobs/view/4405107243)
- [LinkedIn job: Softwaredeveloper AI-based Imageprocessing, Braunschweig](https://www.linkedin.com/jobs/view/4463954486)
- [LinkedIn job: Softwareentwickler - Datenfusion, Bremen](https://www.linkedin.com/jobs/view/4450576780)
- [LinkedIn job: Webentwickler, Bremen](https://www.linkedin.com/jobs/view/4485830200)
- [LinkedIn job: Softwareentwickler (C#/.NET), Bremen](https://www.linkedin.com/jobs/view/4484687039)
- [LinkedIn job: Cyber Security Engineer - Platform & DevSecOps, Bremen](https://www.linkedin.com/jobs/view/4473407835)
- [LinkedIn job: Expert Solution Architect Linux & Container, Düsseldorf](https://www.linkedin.com/jobs/view/4466970027)
- [LinkedIn job: Software Engineer, Platform Pre-Development, Kassel](https://www.linkedin.com/jobs/view/4429454779)
- [LinkedIn job: Softwarearchitekt - Signalverarbeitung, Bremen](https://www.linkedin.com/jobs/view/4421159931)
- [LinkedIn job: Senior Specialist SOC Analyst, Düsseldorf (on-call)](https://www.linkedin.com/jobs/view/4465527145)
- [LinkedIn job: Safety Manager / Produktsicherheit, Penzberg (SÜG)](https://www.linkedin.com/jobs/view/4441509918)
- [Glassdoor: Rheinmetall overview](https://www.glassdoor.com/Overview/Working-at-Rheinmetall-EI_IE10472.11,22.htm)
- [Glassdoor: Rheinmetall reviews (global)](https://www.glassdoor.de/Bewertungen/Rheinmetall-Bewertungen-E10472.htm)
- [Glassdoor: Rheinmetall reviews (Germany)](https://www.glassdoor.de/Bewertungen/Rheinmetall-Deutschland-Bewertungen-EI_IE10472.0,11_IL.12,23_IN96.htm)
- [Glassdoor: Rheinmetall reviews (Munich)](https://www.glassdoor.de/Bewertungen/Rheinmetall-M%C3%BCnchen-Bewertungen-EI_IE10472.0,11_IL.12,19_IC4990924.htm)
- [Glassdoor: Rheinmetall reviews (Software Engineer)](https://www.glassdoor.de/Bewertungen/Rheinmetall-Software-Engineer-Bewertungen-EI_IE10472.0,11_KO12,29.htm)
- [Glassdoor: Rheinmetall reviews (Softwareentwickler)](https://www.glassdoor.de/Bewertungen/Rheinmetall-Softwareentwickler-Bewertungen-EI_IE10472.0,11_KO12,30.htm)
- [Glassdoor: Rheinmetall Software Engineer salaries](https://www.glassdoor.de/Gehalt/Rheinmetall-Software-Engineer-Geh%C3%A4lter-E10472_D_KO12,29.htm)
- [Glassdoor: Rheinmetall Softwareentwickler salaries](https://www.glassdoor.de/Gehalt/Rheinmetall-Softwareentwickler-Geh%C3%A4lter-E10472_D_KO12,30.htm)
- [Glassdoor: Rheinmetall Senior Software Engineer salaries](https://www.glassdoor.de/Gehalt/Rheinmetall-Senior-Software-Engineer-Geh%C3%A4lter-E10472_D_KO12,36.htm)
- [Glassdoor: Rheinmetall interviews](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/Rheinmetall-Fragen-im-Vorstellungsgespr%C3%A4ch-E10472.htm)
- [Glassdoor: Rheinmetall Software Engineer interviews](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/Rheinmetall-Software-Engineer-Fragen-im-Vorstellungsgespr%C3%A4ch-EI_IE10472.0,11_KO12,29.htm)
- [Kununu: Rheinmetall profile](https://www.kununu.com/de/rheinmetall-group)
- [Kununu: Rheinmetall reviews, IT department](https://www.kununu.com/de/rheinmetall-group/kommentare?department=it)
- [Kununu: Rheinmetall reviews, München](https://www.kununu.com/de/rheinmetall-group/kommentare?city=M%C3%BCnchen)
- [Kununu: Rheinmetall reviews, Penzberg](https://www.kununu.com/de/rheinmetall-group/kommentare?city=Penzberg)
- [Kununu: Rheinmetall reviews, Rheinmetall MAN Military Vehicles GmbH](https://www.kununu.com/de/rheinmetall-group/kommentare?company=Rheinmetall%20MAN%20Military%20Vehicles%20GmbH)
- [Kununu: Rheinmetall reviews, Rheinmetall Technical Publications GmbH](https://www.kununu.com/de/rheinmetall-group/kommentare?company=Rheinmetall%20Technical%20Publications%20GmbH)
- [Kununu: Rheinmetall salaries](https://www.kununu.com/de/rheinmetall-group/gehalt)
- [Teamblind: Rheinmetall search](https://www.teamblind.com/search/rheinmetall)
- [levels.fyi: Software Engineer salaries, Germany](https://www.levels.fyi/Salaries/Software-Engineer/Germany)
- [IG Metall Bayern: Ingenieurgehälter 2025/2026 (PDF)](https://www.igmetall.de/download/20250430_IGM_Bro_Ingenieur_Geh_lter_2025_2026_Bayern_DE_Web_7b2603aa7aac7e46437eed549c1ef53c577ca539.pdf)
- [tarifvertrag-online.de: ERA-Entgelttabelle Metall Bayern](https://tarifvertrag-online.de/entgelttabelle/metall-elektro/ig-metall/bayern)
- [Great Place to Work: Deutschlands Beste Arbeitgeber 2026 (PDF)](https://service.greatplacetowork.de/hubfs/Presse/Rahmeninformationen_Deutschlands%20Beste%20Arbeitgeber%202026.pdf)
- [OpenStreetMap Nominatim (geocoding)](https://nominatim.openstreetmap.org/)
- [Overpass API (public transport stops)](https://overpass-api.de/)
