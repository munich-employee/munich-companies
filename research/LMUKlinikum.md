# LMU Klinikum München - Full Research Report

_Researched: 2026-11-17_

> **Critical Disqualifiers**
> 1. **Not software-centric.** LMU Klinikum is a university hospital (about 11,900 staff, about 2,000 beds) run by the Free State of Bavaria as a public-law institution (Anstalt des öffentlichen Rechts). Software is a support function in the central IT department (Medizintechnik und IT, MIT), the Medical Data Integration Center (MeDIC LMU) and research groups. Of 144 open vacancies on 2026-11-17, three are IT or software roles.
> 2. **Pay is capped by the TV-L collective agreement.** Every IT posting says "Die Vergütung richtet sich nach dem Tarifvertrag für den Öffentlichen Dienst der Länder (TV-L)". A realistic experienced hire at E13 Stufe 3-4 earns **€66.9K-€73.2K** a year including the annual bonus. That is 24-31% below the levels.fyi Munich Senior Software Engineer median (€96.4K). There is no equity and no performance bonus.
> 3. **Loss-making, with cost cutting under way.** The FY2025 loss was **€75.1M** (FY2024: €10.5M loss). In 2025 the board started a cost-cutting programme that included "einen Stellenabbau in fast allen Berufsgruppen" (job cuts in almost all occupational groups). A former IT manager on Glassdoor (Jan 2026) describes a very difficult financial situation and very thin staffing in IT.
> 4. **Many AI and data roles are fixed-term.** Both current analytics and AI postings offer "Ein zunächst auf ein Jahr befristeter Arbeitsvertrag" (a contract initially limited to one year). This fails the full-time, permanent role criterion for that part of the organisation.
>
> The full report follows for completeness.

**Note on scope:** "LMU Klinikum" is the hospital: the Klinikum der Ludwig-Maximilians-Universität München, formerly "Klinikum der Universität München", renamed in 2019. It is a separate legal entity from the university (LMU München), which has its own administration, IT and its own September 2026 data-protection incident. The Medical Faculty's chairs and institutes are university bodies, but the hospital employs most clinical, IT and data staff. This report covers the hospital as an employer of software engineers.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | Medical faculty roots back to 1826 (Glassdoor "Gegründet 1826"). It became a self-governing public-law institution under the Bavarian University Hospitals Act (BayUniKlinG) in 2006, about 20 years ago. |
| Employees | **11,908 headcount** at 31.12.2025 (9,948.6 average FTE in 2025). Postings say "rund 12.000 Mitarbeiterinnen und Mitarbeiter". |
| Revenue (FY2025) | Operating income **€1,545.9M**: €1,154.3M hospital revenue, €293.5M public grants and subsidies, €98.0M other operating income |
| Profitability | **FY2025 net loss €75.1M**; FY2024 loss €10.5M; FY2023 profit €2.5M; FY2022 €4.9M; FY2021 €4.5M. The institution is non-profit by statute (gemeinnützig, Art. 1(4) BayUniKlinG). **FAIL** |
| Ownership | Public: run by the Free State of Bavaria, which carries unlimited liability (Gewährträgerschaft, Art. 3(1) BayUniKlinG). Legal oversight by the Bavarian Ministry of Science and the Arts (StMWK). |
| Software-centric | Hospital; IT is a support function - **FAIL** |

### Key People

- **Prof. Dr. med. Markus M. Lerch** - Chair of the Board and Medical Director (Ärztlicher Direktor)
- **Markus Zendler** - Commercial Director (Kaufmännischer Direktor). He heads the "Dienststelle" under the Bavarian Staff Representation Act (BayPVG) and is the line superior of all non-scientific staff, IT included.
- **Carolin Werner** - Nursing Director (Pflegedirektorin)
- **Prof. Dr. med. Thomas Gudermann** - Dean, Medical Faculty (board member)
- **Dr. Kurt Kruber** - Head of the IT department, Medizintechnik und IT (MIT)
- **Reinhard Thasler, Dr. Fady Albashiti** - MeDIC LMU leadership
- **PD Dr. med. Hans Christian Stubbe** - Chief Medical Information Officer, Digital Medicine unit (Stabsstelle Digitale Medizin)
- **Prof. Dr. Bjoern Eskofier** - Head of the new Institute for AI in Medicine (since 1 Oct 2025, about 30 staff)

(Sources: lmu-klinikum.de imprint and department pages, retrieved with curl and CDP; Jahresbericht 2025.)

### Funding History

Not applicable: there is no venture or private-equity funding. Financing is set by statute (Art. 3(2) BayUniKlinG). Patient care must cover its own costs from hospital fees and other revenue. The Free State funds research and teaching through the Medical Faculty and pays for major construction, such as the planned **about €2.2bn Großhadern new build** (first phase: 600 beds, heart-lung-vascular centre, oncology, diagnostics). Third-party research funding was €136.0M in 2025 (DFG, BMBF, EU, foundations).

### Business Model

A maximum-care university hospital. It earns revenue through DRG and outpatient billing to statutory and private health insurers (€1.15bn) and receives state grants for research and teaching (€293M). In 2025 it treated 78,509 inpatient cases and about 460,000 cases in total. It is a member of the M1 Munich Medicine Alliance (with TUM Klinikum, Helmholtz Munich and both universities) and of the Medical Informatics Initiative through the DIFUTURE consortium.

### Software-Centric Assessment

**FAIL.** Software is a means to clinical and research ends, not the product:

- **Headcount mix.** Of 9,948.6 average FTE in 2025, the largest groups are medical-technical staff (2,748.5 incl. third-party-funded), nursing (2,116.0), physicians (1,790.7), functional services (1,154.5) and administration (869.6). The annual report has no IT category; IT staff sit inside administration or technical services.
- **Vacancies.** On 2026-11-17 the careers site listed **144** vacancies. Keyword searches ("Software", "Informatik", "IT", "Data", "KI", "Developer", "Engineer") found three IT roles: an IT system administrator in laboratory medicine, an IT service and support role, and a fixed-term computer scientist for AI and computer vision in surgery. LinkedIn (voyager API sweep, Munich geo) showed the same mix: overwhelmingly nursing and clinical.
- **Real in-house engineering exists**, mostly in pockets:
  - **MeDIC LMU** is building the hospital's data integration centre for the Medical Informatics Initiative.
  - The **Institute for Laboratory Medicine** runs its own servers and "ein selbstentwickeltes Laborinformations- und Managementsystem (LIMS)", maintained by a ten-person IT team.
  - **MIT** runs hospital IT and has advertised LLM engineering work, described in Section 6.
  - A Glassdoor IT manager writes "Das meiste wird Inhouse gemacht" (most work is done in-house).
- Strategically, the hospital's competitive position rests on clinical excellence (Newsweek World's Best Hospitals 2026: #17 worldwide), not on software.

### Consulting-Adjacency Assessment

Not applicable. Engineers build internal systems for the hospital and its research; there is no client billing and there are no consultant titles. One related note: a service subsidiary, **KMD Klinikum der Universität München Dienstleistungs GmbH** (HRB 152516), handles cleaning, patient transport, catering and security. It is an outsourcing vehicle for facility services, not an IT consultancy. **PASS** on the not-consulting criterion.

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **Klinikum der Ludwig-Maximilians-Universität München (LMU Klinikum)**, Anstalt des öffentlichen Rechts | **Not in the commercial register.** It was created by statute, Art. 1(1) Nr. 3 BayUniKlinG. VAT ID DE 813536017. Supervisory authority: Bayerisches Staatsministerium für Wissenschaft und Kunst. | Marchioninistraße 15, 81377 München (Campus Großhadern); Campus Innenstadt: Ziemssenstraße 5 / Pettenkoferstraße 8a, 80336 München | Art. 2(1) BayUniKlinG: "es dient der universitären Forschung und Lehre und dem wissenschaftlichen Fortschritt und nimmt daran ausgerichtet Aufgaben der Krankenversorgung wahr" (it serves university research, teaching and scientific progress, and provides patient care in line with these). Art. 1(4): exclusively charitable purposes under § 52 AO. |
| KMD Klinikum der Universität München Dienstleistungs GmbH (subsidiary) | Amtsgericht München **HRB 152516** | Marchioninistr. 15, 81377 München | "Durchführung von Reinigungsleistungen aller Art, Tätigkeiten des klinischen Hauspersonals … Transport von Sachgütern … Wach- und Schließdiensten" (cleaning, ward help, goods transport, security) |

Verification: The imprint ([lmu-klinikum.de/imprint](https://lmu-klinikum.de/imprint), curl) confirms the legal form "Anstalt des Öffentlichen Rechts … vertreten durch den Vorstand". The statute ([BayUniKlinG](https://www.gesetze-bayern.de/Content/Document/BayUniKlinG/true), curl) confirms the legal basis. NorthData (CDP) has no register entry for the hospital itself, which is expected for a statutory public-law institution, but lists the KMD subsidiary.

The registered purpose explicitly covers patient care, research and teaching; this is not a sales shell. Engineers are hired directly by the hospital. Every IT posting runs on the hospital's own application form and pays under TV-L, and staff are enrolled in the VBL public-sector pension fund (Art. 15(1) BayUniKlinG). There is no employer-of-record or PEO arrangement. Art. 15(3) also counts prior service with the Free State of Bavaria as the hospital's own, and vice versa.

**Verdict:** **PASS** (direct public-sector employment; the service GmbH is not relevant to IT roles)

---

## Section 3: Office Location

- **Office address:**
  - **Campus Großhadern**, Marchioninistraße 15, 81377 München (district Hadern, Stadtbezirk 20). This is the address of the IT department, Medizintechnik und IT (MIT) (department page, CDP), and the work location of the current laboratory IT and surgical AI postings. The new Institute for AI in Medicine is "in Laufweite zum Klinikgebäude in Großhadern" (within walking distance of the Großhadern building).
  - **MeDIC LMU**, Fraunhoferstraße 20, 82152 Planegg-Martinsried (Landkreis München, just outside the city boundary, about 1.8 km west of the Großhadern clinic building). Nominatim places it in Martinsried, Planegg.
  - **Campus Innenstadt**, Ziemssenstraße 5 / Pettenkoferstraße 8a, 80336 München (Ludwigsvorstadt-Isarvorstadt), for some central functions (for example the University Medicine office).
- **Nearest public transport:**
  - Campus Großhadern: U-Bahn station **Klinikum Großhadern** (U6) about 40 m from the geocoded entrance. The same stop serves bus lines 56, 266, 269, X208, X910 and night bus N40. Großhadern station (U6) is about 660 m away.
  - MeDIC Martinsried: bus stop **Fraunhoferstraße** about 120 m away, and **Martinsried, Nord** about 160 m away. Lines 259, 266 and 267 serve the area. U6 Klinikum Großhadern is about 1.8 km away.
  - (Nominatim geocoding and Overpass stop and route-relation queries, curl.)
- **Work model:** Hybrid, at the employer's discretion. Postings list "Mobile Arbeit (bei Eignung)" (mobile work where suitable), and MeDIC postings add "Flexible Arbeitszeiten bei einer 38,5-Stunden-Woche, Möglichkeit des mobilen Arbeitens und 30 Tage Urlaub". LinkedIn tags every LMU Klinikum posting "On-site". Kununu reviewers describe fixed rather than flexible home-office days in administration ("Option auf feste Homeoffice Tage", Kununu, Mar 2024, Ex-Angestellte/r oder Arbeiter/in, Administration / Verwaltung). They also describe home office as arriving only slowly ("Sehr langsam finden auch Zugeständnisse wie Homeoffice … einen Platz", Kununu, Oct 2024, Angestellte/r oder Arbeiter/in, department not stated). No posting offers fully remote work.

---

## Section 4: Reviews

**Great Place to Work:** **No GPTW certification found.** I searched the web and greatplacetowork.de; the awarded-companies page renders only a search shell over CDP, and no LMU Klinikum entry turned up. LMU Klinikum is **not a Kununu Top Company**. The only employer award found is nursing-specific: stern's "Deutschlands Ausgezeichnete Arbeitgeber Pflege 2023/24" (Oct 2023), which covers nursing working conditions. It is not equivalent to GPTW.

### Glassdoor

Retrieved over CDP from glassdoor.de; glassdoor.com redirects there. Glassdoor has **two profiles**:

- **"LMU Klinikum"** (EI 3943883, current name): 164 reviews in total and 130 with ratings. The default German-locale view shows 76 written reviews.
- **"Klinikum der Universität München"** (EI 932293, legacy name): 32 reviews.

The table uses the current profile. Location and job-title filters were applied with Glassdoor's own filter URLs (`_IL…_IN96`, `_IL…_IC4990924`, `_KO…`), and they do return different aggregates.

| Metric | Global | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | 3.6 (130 rated / 164 total) | 3.8 (75 rated, 39 written) | 3.8 (74 rated, 39 written) | 3.4 (2 rated, 1 written) |
| **WLB** | 3.9 | 3.8 | 3.8 | n/a |
| **Culture & Values** | 3.8 | 3.9 | 3.9 | n/a |
| **Comp & Benefits** | 3.2 | 3.3 | 3.3 | n/a |
| **Career Opportunities** | 3.5 | 3.5 | 3.5 | n/a |
| **Diversity & Inclusion** | 4.0 | 4.0 | 4.0 | n/a |
| **Senior Management** | 3.2 | 3.4 | 3.4 | n/a |
| **% Recommend** | 65% | 75% | 75% | n/a |
| **CEO Approval** | Not rated (no CEO on profile; `ceoRating: null`) | Not rated | Not rated | n/a |
| **Business Outlook** | 54% positive | 68% positive | 68% positive | n/a |

Observations:
- **Low recent volume.** Glassdoor reports only **5 reviews in the last 12 months** on the default view, so the trend is directional. Glassdoor's own FAQ says WLB ratings "um 10 % gesunken" (fell 10%) over the last year and Culture fell 4%.
- **Germany and Munich are the same population.** Almost all reviews are from Munich (Glassdoor lists "München (57)" as the top location), so the two filters return essentially the same set.
- **The reviewer base is research and clinical**: PhD students (10), postdocs (12), research staff, student assistants and physicians. The single Software Engineer review rates the employer 3.0.
- **The legacy profile is older and much worse**: 3.6 overall, but WLB 2.3, Culture 2.7, Senior Management 2.4 and 60% recommend. Its CEO approval (81%) is attributed to Karl-Walter Jauch, a former medical director, which dates those reviews. They are pre-rebrand and are not used in the table.

### Kununu

Fetched over CDP (curl returned HTTP 405). Slug: `klinikum-der-universitaet-muenchen`.

- **Overall score:** **3.3 / 5.0** - Kununu flags this as "niedriger als der Durchschnitt der Branche Gesundheit/Soziales/Pflege (3,6)" (below the health/social/care sector average)
- **Recommendation rate (Weiterempfehlung):** **59%** (last 2 years); 56% all-time (165 of 295)
- **Total reviews:** 343 including applicants; **310 employee reviews** since 2012. There were 35 in 2026 and 53 in 2025.
- **Kununu Top Company:** **NO**
- Sub-scores: Karriere & Gehalt 3.2, Unternehmenskultur 3.3, Arbeitsumgebung 3.0, Vielfalt 3.8
- Most-confirmed benefits: Betriebsarzt (company doctor) 71%, betriebliche Altersvorsorge (occupational pension) 60%, Kantine (canteen) 58%
- **IT department filter (`?department=it`):** 4 reviews (Feb 2025, Apr 2025, Jul 2025, May 2020), scored 3.2, 2.8, 3.9 and 2.9 (mean about 3.2). Only the student review has text.
- Kununu's own AI summary of the reviews: "insbesondere auf höheren Führungsebenen berichten Mitarbeiter:innen von autoritärem Führungsstil und Vetternwirtschaft, wenngleich einzelne direkte Vorgesetzte als freundlich und unterstützend beschrieben werden" (staff report an authoritarian style and favouritism, especially at higher management levels, though some direct managers are described as friendly and supportive).

### Blind / Teamblind

**No company profile.** `teamblind.com/company/LMU-Klinikum` and two variants return 404, and Blind search returns "No results found for 'LMU Klinikum'" (CDP). This is expected for a German public hospital. **No data.**

### Review Themes (2022-2026)

**Positives:**
- **Job security and public-sector terms.** "Sicherer Arbeitgeber mit klaren Regeln und klaren Strukturen. Unbefristete Verträge genießen viele Vorteile und Rechte." (secure employer with clear rules; permanent contracts carry many advantages and rights) (Kununu, Oct 2024, Angestellte/r oder Arbeiter/in, department not stated). "38,5 h Woche mit flexiblen Arbeitszeiten" (38.5-hour week with flexible hours) and "Führungskräfte nehmen sich Zeit für Gespräche" (managers take time to talk) (Kununu, Nov 2025, Angestellte/r oder Arbeiter/in, Personal / Aus- und Weiterbildung, current).
- **Varied in-house IT with a security focus.** "Das zweitgrößte Krankenhaus in Deutschland bietet in der IT sehr vielfältige Aufgaben. Das meiste wird Inhouse gemacht und auf Security und Sorgfalt wird großen Wert gelegt." (the second-largest hospital in Germany offers very varied IT work; most is done in-house, with strong emphasis on security and care) (Glassdoor, Jan 2026, former IT Manager, München, more than 1 year).
- **Flexible hours and decent WLB outside shift work.** Glassdoor WLB is 3.9. "moderne Dateninfrastruktur, flexible Arbeitszeiten" (modern data infrastructure, flexible hours) (Glassdoor, Nov 2025, current Werkstudent Data Analytics). "Work-Life-Balance … Hier gibt es nichts auszusetzen" (nothing to criticise on WLB) (Kununu, Jul 2026, Angestellte/r oder Arbeiter/in, Administration / Verwaltung, current).
- **Research infrastructure and reputation.** "Gute Infrastruktur für die medizinische Forschung (excellente Core-Facilities)" (good infrastructure for medical research, excellent core facilities) (Glassdoor, Sep 2026, current Wissenschaftlicher Mitarbeiter, München, more than 1 year).

**Negatives:**
- **Finances and thin IT staffing (IT-specific).** "Leider ist die finanzielle Lage momentan sehr schwierig und die Personaldecke besonders dünn. Da sind gerade neue Projekte schwierig umzusetzen. Es gibt viele 'Altlasten', die längst abgelöst werden sollen, was aber in diesem großen Haus oft eine Sisyphos-Aufgabe darstellt." (the financial situation is very difficult and staffing especially thin, so new projects are hard to deliver; there is much legacy that should long since have been replaced, often a Sisyphean task here) (Glassdoor, Jan 2026, former IT Manager, München, more than 1 year).
- **Slow, hierarchical and outdated (the only Software Engineer review).** Cons: "Langsam, Gehalt, Veraltet, Hierarchie, Mangelnde Aufstiegsmöglichkeiten" (slow, pay, outdated, hierarchy, few promotion prospects) (Glassdoor, Jan 2024, current Software Engineer, 3.0). Similar: "eingeschränkte Nutzung moderner Tools außerhalb des Kliniknetzwerks, und Entscheidungswege manchmal etwas langsam" (limited use of modern tools outside the clinic network, and slow decision paths) (Glassdoor, Nov 2025, current Werkstudent Data Analytics).
- **Communication breakdown is the most frequent complaint on Kununu.** "Es wir[d] quasi nicht kommuniziert, weder fachlich-inhaltlich noch organisatorisch oder über Hierarchieebene hinweg." (there is practically no communication, on content, organisation or across hierarchy levels) (Kununu, Sep 2026, Ex-Angestellte/r oder Arbeiter/in, Administration / Verwaltung). "Es werden kaum Informationen an die Beschäftigten weitergegeben. Gleichzeitig werden sie aber dafür verantwortlich gemacht" (staff get hardly any information but are held responsible for the consequences) (Kununu, Aug 2026, Angestellte/r oder Arbeiter/in, Administration / Verwaltung, current).
- **Harsh treatment by top management.** "die oberste Leitung die Oberhand hat und schrecklich mit Menschen umgeht. Mein Vorgesetzter wurde in mehreren Gesprächen, bei denen ich dabei war, richtig runtergemacht." (top management has the upper hand and treats people terribly; my manager was torn into in several meetings I attended) (Kununu, Aug 2026, Angestellte/r oder Arbeiter/in, Administration / Verwaltung, current). Nursing management drew a cluster of complaints in Oct-Nov 2025: "Pflegedirektorin führt veraltet autoritär und nach Sympathie" (the nursing director leads in an outdated, authoritarian way, by personal favour) (Kununu, Nov 2025, Angestellte/r oder Arbeiter/in, department not stated, current). "Es ist keine Überraschung dass die Fluktuation in der Direktion massiv angestiegen ist" (no surprise that turnover in the directorate has risen massively) (Kununu, Oct 2025, Führungskraft / Management, department not stated, current).
- **Rigid TV-L grading.** "Nach TVL, somit kaum Verhandlungsspielraum" (under TV-L, so hardly any room to negotiate) (Kununu, Oct 2024, Angestellte/r oder Arbeiter/in, department not stated). "Verdienst ist im TV-L deutlich schlechter als in anderen städtischen Kliniken die unter TVöD laufen" (TV-L pay is clearly worse than at municipal hospitals under TVöD) (Kununu, Aug 2024, Ex-Angestellte/r oder Arbeiter/in, Produktion, until 2018).
- **Overtime in some units.** "Es werden viele Überstunden verlangt … Viele Beschäftigen bleiben nur 1/2 Jahre und verlassen die Personalabteilung dann wieder." (much overtime is demanded; many stay only half a year to a year and then leave the HR department) (Kununu, Oct 2024, Ex-Angestellte/r oder Arbeiter/in, Personal / Aus- und Weiterbildung). "Unbezahlte Überstunden und fehlende Dankbarkeit" (unpaid overtime and no appreciation; review title) (Kununu, Sep 2022, Angestellte/r oder Arbeiter/in, department not stated, current).
- **Bureaucracy and slow HR.** "langsame, sehr bürokratische Personalabteilung, wenig flexibel" (slow, very bureaucratic, inflexible HR department) (Glassdoor, Sep 2026, current Wissenschaftlicher Mitarbeiter, München).

Overlap with hard red flags: communication breakdown (multiple years and platforms), unpaid or undocumented overtime (several reviews, none from IT), one surveillance claim, job cuts (2025 cost-cutting programme), and one short-notice non-renewal of a fixed-term contract (see below). WLB complaints are concentrated in nursing and shift-based roles.

### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | **Present, concentrated in nursing management and some administrative units.** Kununu's own summary cites "autoritärem Führungsstil und Vetternwirtschaft" (authoritarian leadership and favouritism) at higher levels. Several Oct-Nov 2025 reviews target the nursing directorate. "Teamleitung … Vorschläge werden als Angriff betrachtet. Es wurde auch in Meetings geschrien." (team leads treat suggestions as attacks; there was shouting in meetings) (Kununu, Dec 2024, Ex-Angestellte/r oder Arbeiter/in, department not stated). No IT-specific leadership complaint was found. |
| 24/7 Work Expectation | **Inherent to clinical roles, and IT operations carry on-call duty.** The current laboratory IT administrator posting lists "Teilnahme an der Rufbereitschaft" (participation in the on-call rota). Nursing reviews describe constant short-notice shift cover ("Ständiges Einspringen und Veränderungen im Dienstplan", constantly covering shifts and roster changes, Kununu, Nov 2025, Angestellte/r oder Arbeiter/in, current). No evidence of after-hours expectations for MeDIC or research software roles. |
| Internal Surveillance | **One claim:** "Toxisch. Mitarbeiter werden überwacht und ständig kontrolliert ob sie auch arbeiten." (toxic; staff are monitored and constantly checked to see whether they are working) (Kununu, Dec 2024, Ex-Angestellte/r oder Arbeiter/in, department not stated). Under Art. 75a BayPVG, technical monitoring systems are subject to staff council co-determination. Isolated. |
| Fear-driven Management | **Some signals:** "Solange man still und ruhig ist kann man machen was man will." (as long as you keep quiet you can do what you like) and "bossingverhalten, machtausübung" (bossing, exercise of power) (Kununu, Aug 2025, Angestellte/r oder Arbeiter/in, Administration / Verwaltung, current). Localised. |
| Communication Breakdown | **Systemic.** This is the most consistent complaint on Kununu, across 2020-2026 and across nursing, administration and physicians. Example: "Gibt kaum klinikumsübergreifende Kommunikation seitens des Vorstand" (hardly any hospital-wide communication from the board) (Kununu, Mar 2024, Angestellte/r oder Arbeiter/in, department not stated; the reviewer's title says they are a physician). |
| Unpaid Overtime | **Reported in several non-IT units:** "Überstunden werden zum Teil nicht erfasst" (overtime is partly not recorded) (Kununu, Dec 2024, Ex-Angestellte/r oder Arbeiter/in, department not stated). "viele Überstunden, unvergütet" (lots of unpaid overtime) (Kununu, Nov 2021, Angestellte/r oder Arbeiter/in, Forschung / Entwicklung, current). Working time is recorded and flexitime is standard ("Gleitzeit"), which limits this for salaried TV-L staff. |
| Silent Firings | **Low for permanent staff, real for fixed-term staff.** Permanent TV-L staff have strong protection: hearing of the staff council (Personalrat) before dismissal, and after 15 years and age 40, ordinary notice is excluded under § 34(2) TV-L. Fixed-term non-renewal is the soft exit route instead: "nach zwei Monaten Arbeit wurde mir mitgeteilt, dass mein Vertrag nicht verlängert würde, weil ich eine ruhige Person sei" (after two months I was told my contract would not be extended because I am a quiet person) (Kununu, Nov 2025, Angestellte/r oder Arbeiter/in, Institut für Labormedizin, current). |
| Work-Life Balance issues | **Split by role.** Glassdoor WLB is 3.9 (Germany 3.8) and Kununu reviewers in administration and HR praise flexitime and the 38.5-hour week. Nursing and physician reviews report poor WLB ("Arbeiten mit vielen Diensten", working many shifts, Kununu, Mar 2024). For office-based IT and data roles the evidence leans positive, apart from on-call in operations. |

**Risk level: MODERATE.** The pattern is mainly (b), the bureaucracy and slow, hierarchical management typical of a large public institution, plus (c), localised dysfunction in the nursing directorate and some administrative units such as HR. There is no evidence of systemic toxicity in IT: the four Kununu IT reviews average about 3.2 with no leadership complaints, and the Glassdoor IT manager rates the employer 4.0. That IT evidence is thin, though. The 2025 cost-cutting programme raises pressure across all units.

---

## Section 5: Compensation

### Salary Data

Pay is **set by the TV-L** (collective agreement for the federal states, Länder). Every IT posting says so, and Art. 15(1) BayUniKlinG applies the Free State's rules to hospital staff. The posting phrase "einschließlich aller im Öffentlichen Dienst üblichen Zulagen" (including all customary public-service allowances) adds little at senior grades. The Munich allowance under TV-EL (€154.76/month from 1 Apr 2026) is paid only while the table salary is below **€4,503.47/month** (§ 2(3) TV-EL). Every E13+ step is above that, so the allowance does not apply.

None of the postings reviewed states a pay grade. The TV-L IT pay rules place degree-level software and data roles at **E13**, with E14/E15 for heightened responsibility or leadership. External hires with relevant experience normally start at **Stufe 3**.

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| TV-L table from 01.04.2026 | E13 Stufe 3 (typical external senior hire) | €64.4K (€5,366.89 × 12) | 0 | €2.5K (Jahressonderzahlung 46.47%) | **€66.9K** | Tariff |
| TV-L | E13 Stufe 4 | €70.5K | 0 | €2.7K | **€73.2K** | Tariff |
| TV-L | E13 Stufe 6 (end step) | €81.2K | 0 | €3.1K | **€84.3K** | Tariff |
| TV-L | E14 Stufe 3 / Stufe 6 | €69.9K / €86.3K | 0 | €1.9K / €2.3K (32.53%) | **€71.8K / €88.7K** | Tariff |
| TV-L | E15 Stufe 3 / Stufe 6 (lead or head of unit) | €75.4K / €94.3K | 0 | €2.0K / €2.6K | **€77.4K / €96.8K** | Tariff |
| Glassdoor (LMU Klinikum, Germany) | Software Engineer / Data Scientist | No figures shown for either title | - | - | - | 0 visible (414 salaries overall, dominated by PhD students, postdocs and physicians) |
| levels.fyi | LMU Klinikum | No company page (404) | - | - | - | 0 |

Table source: [TV-L Entgelttabelle 2026](https://oeffentlicher-dienst-news.de/oeffentlicher-dienst-laender-die-neuen-entgelttabellen-tv-l-2026-bis-2028/), valid 01.04.2026-28.02.2027 (+2.8%). The next rises are +2.0% from 1 Mar 2027 and +1.0% from 1 Jan 2028. Jahressonderzahlung (annual bonus) rates for TV-L West have been unchanged since 2021: 46.47% (E12-13) and 32.53% (E14-15).

**Negotiation lever:** § 16(5) TV-L lets the employer pay up to **two steps ahead**, or a supplement of up to 20% of Stufe 2 at the end step, "zur Deckung des Personalbedarfs" (to cover staffing needs). TV-EL itself refers to such "vorweggewährte Stufen". At E13 this would lift a Stufe 3 entry to Stufe 5 (**€81.9K**). Approval is discretionary and less likely during a cost-cutting year.

**Munich reference (levels.fyi, Senior Software Engineer, Munich, 300+ data points, updated 17 Nov 2026):** median **€96.4K** total comp; 25th percentile €81K; 75th €117K; 90th €159K.

### Equity / Stock

**None.** A public-law hospital has no shares, options or performance bonus. The only extras are the Jahressonderzahlung (above) and the **VBL occupational pension** (Versorgungsanstalt des Bundes und der Länder), a mandatory employer-funded public-sector pension (Art. 15(1) BayUniKlinG). Other benefits: 30 days' leave, a 38.5-hour week, MVV job ticket, JobRad, childcare places, and staff housing "soweit verfügbar" (where available; a Landtag answer of 28.11.2025 confirms the state is building more).

### Verdict

**BELOW.** The realistic offer is €66.9K-€73.2K at E13 Stufe 3-4 (up to €81.9K if two steps are granted ahead under § 16(5)). That is **24-31% below the Munich Senior SWE median (€96.4K)**, at or below the 25th percentile (€81K), and far below the 75th-90th percentile (€117K-€159K). Even E15 at the end step (€96.8K, after many years) only reaches the median. Large profitable Munich corporations pay a senior engineer roughly €85K-€110K base plus bonus. The only part of TV-L pay that compares well is the employer-funded VBL pension and the stability of the scale.

---

## Section 6: AI/ML & Tech Stack

### AI Strategy

AI work is real but **research-led and project-funded**, spread across several units:

- **Institute for AI in Medicine (Institut für Künstliche Intelligenz in der Medizin)**, founded 1 Oct 2025 under Prof. Bjoern Eskofier (from FAU Erlangen's machine learning and data analytics chair) with about 30 staff. It "eine übergeordnete Funktion haben wird und alle Aktivitäten in diesem wichtigen Zukunftsfeld bündelt" (will have an overarching role and bundle all activity in this field). It is also building an e-health core facility with sensor, motion-analysis and VR measurement equipment (Jahresbericht 2025).
- **Clinical LLM work in MIT, the central IT department.** An LLM Engineer / LLM Data Scientist posting (now expired) covered "Design und Integration einer LLM-basierten Chat-Applikation zur Unterstützung klinischer und administrativer Prozesse" (designing and integrating an LLM-based chat application for clinical and administrative processes) and testing and rolling out new models for "ein klinisches LLM-System" (a clinical LLM system). A companion Linux/Kubernetes administrator posting ran "ein Kubernetes-Cluster für LLM-Deployments". (Both from search-result snippets; the posting PDFs now redirect to the job list.)
- **MeDIC LMU** builds the hospital's data integration centre under the Medical Informatics Initiative (DIFUTURE consortium). This is a FHIR-oriented clinical data platform for research use, with a use-and-access committee for data requests. The MeDIC GitHub organisation (`mediclmu`, created Aug 2025) has no public repositories.
- **Applied research AI in clinical departments**: surgical computer vision (the NAOMI project in general, visceral and transplant surgery, using PyTorch on GPUs), a Clinical Research Software Engineer post in Radiology, AI explanation studies in radiology, and AI in cell therapy and haematology.

The distinction matters. The production-facing AI (LLM platform, data integration) sits in a cost-pressured central IT function with legacy systems to replace. The innovative AI sits in research units staffed on fixed-term, grant-funded contracts.

### Tech Stack

Derived mainly from **job postings**: current postings (CDP), expired postings via search snippets, and the archived MeDIC Junior Software Engineer text on rapidjob.de. Secondary sources: the Jahresbericht 2024/2025, Glassdoor and Kununu reviews, GitHub organisations, and the website imprint.

| Category | Technologies |
|---|---|
| **Primary language(s)** | MeDIC: "Sehr gute Kenntnisse in mindestens einer dieser Sprachen: Java, C#, Python, R, Scala und SQL" (very good knowledge of at least one of these). Research AI: Python. MIT web team: Ruby (GitHub `KUMteamIM`, "MIT Web-Anforderungen und -Dienste"; the website runs on the Scrivito CMS). |
| **AI/ML** | PyTorch, deep learning, computer vision, GPU training (surgical AI); an LLM-based clinical chat application and a "klinisches LLM-System" (MIT); Kubernetes for LLM deployments |
| **Cloud** | No public cloud found in any posting. Infrastructure is on-premise ("eingeschränkte Nutzung moderner Tools außerhalb des Kliniknetzwerks", limited use of modern tools outside the clinic network, Glassdoor, Nov 2025). Bavarian hospital data-protection law (Art. 27 BayKrG) restricts processing patient data outside the hospital. |
| **Infrastructure** | Docker, Kubernetes, VMware and Proxmox virtualisation, Windows plus Linux (SLES/Ubuntu), Veeam backup, GitLab CI/CD, high-availability database clusters (laboratory IT) |
| **Data** | Apache Kafka, Apache NiFi, PostgreSQL, RDBMS/NoSQL (MeDIC); MariaDB with MaxScale, MongoDB (laboratory IT); HL7 FHIR, IHE, LOINC (medical informatics standards); CentraXX biobank system and SAS (University Medicine office) |
| **Other** | Self-developed laboratory information system (LIMS); OR-management partnership with the startup sqior medical (Jahresbericht 2024); agile DevOps teams at MeDIC |

**Summary:** Polyglot. MeDIC's data integration platform accepts Java, C#, Python, R or Scala around Kafka, NiFi, PostgreSQL and FHIR on on-premise Docker/Kubernetes. Research AI groups are Python-centric (PyTorch, computer vision, LLMs). Hospital IT operations are Windows/Linux, VMware and Proxmox. There is no public cloud. The work is applied clinical data engineering and research AI in a regulated hospital setting, with a large legacy estate in central IT.

---

## Section 7: Language

- **All postings are in German**, including the AI and software ones. The careers site has an "Englisch" language filter, but none of the IT roles found were posted in English.
- Requirements vary by unit:
  - **Laboratory IT administrator (current):** "Sehr gute Deutschkenntnisse (Niveau C1 oder höher) sowie Englischkenntnisse (Niveau B2 oder höher)" (very good German at C1 or above, English at B2 or above).
  - **Laboratory medicine Software Engineer (2024, ref. 2024-K-0095):** German C1, English B1 (search snippet).
  - **MeDIC Software Engineer (archived):** "Gute Deutsch- und Englischkenntnisse in Wort und Schrift" (good written and spoken German and English).
  - **Surgical AI / computer vision (current, research):** "Sehr gute Deutsch- und/oder Englischkenntnisse" (very good German **and/or** English). Here English alone is enough.
- The working environment is a German public hospital: clinicians, the staff council, HR, TV-L paperwork and almost all Kununu and Glassdoor reviews are in German. English is the language of the research groups, not of hospital IT.

**Verdict:** **CONDITIONAL**, leaning FAIL for central IT. Research AI groups accept English only. Central IT (MIT) and laboratory IT require German at C1, which fails the English-first threshold. MeDIC asks for both German and English without stating a level; confirm with the hiring manager.

---

## Section 8: Stability

### Financial Position

From the condensed P&L in the [Jahresbericht 2025](https://cdn.lmu-klinikum.de/349235d86f461e6a/4b448ed1875e/JAHRESBERICHT-2025_Webversion.pdf) (curl, extracted with pypdf):

| (T€) | 2025 | 2024 |
|---|---|---|
| Hospital revenue | 1,154,346 | 1,084,235 |
| Public grants and subsidies | 293,486 | 285,166 |
| Other operating income | 98,034 | 131,415 |
| **Operating income** | **1,545,866** | **1,500,816** |
| Personnel costs | -903,063 | -837,692 |
| Materials | -506,556 | -485,687 |
| Other operating costs | -208,453 | -188,920 |
| Investment effects, financial result, taxes | -2,877 | 937 |
| **Net result** | **-75,083** | **-10,546** |

Five-year net results: 2021 +€4.5M, 2022 +€4.9M, 2023 +€2.5M, 2024 -€10.5M, 2025 -€75.1M. **The trend is deteriorating sharply.** Personnel costs rose 7.8% in 2025 while hospital revenue rose 6.1%.

The board's foreword says growth after Covid "war mit einem Aufbau von Personal verbunden … [der] nicht vollständig gegenfinanziert war" (involved hiring that was not fully funded). It blames price inflation, "die leeren Kassen der Kostenträger" (empty insurer coffers) and regulation. The 2026 TV-L rise (+2.8% from April) adds roughly €19M to 2026 personnel costs. The 2027 federal hospital reform cuts (reported nationally at €5.1bn) add further pressure.

**Backstop:** the Free State is liable without limit for the hospital's obligations (Art. 3(1) BayUniKlinG, Gewährträgerschaft). Insolvency is therefore not a realistic risk. The risk is budget discipline: hiring freezes, non-replacement and cost cutting. Short-term cash credit is capped at one tenth of planned revenue, about €155M (Art. 3(4)); anything beyond needs ministry approval. Credit rating: not applicable (the hospital is covered by the state guarantee).

### Financial Runway (VC-backed and loss-making companies only)

The hospital is loss-making, so the model is included. A "runway" in the start-up sense does not apply because of the unlimited state guarantee. The model therefore estimates deficit size and how long the statutory short-term credit ceiling alone could absorb it.

**Searched:**
- The annual report contains only a condensed P&L, no balance sheet or cash line.
- A Bundesanzeiger full-text search over CDP returned a technical error page.
- NorthData has no entry for the institution, as a statutory public-law body.
- **Cash at hand: UNKNOWN.**

Bottom-up, FY2025 actuals:

| Cost line | Annual estimate |
|---|---|
| Staff (9,948.6 avg FTE × about €90.8K fully-loaded) | €903.1M |
| Materials (medical supplies, drugs, energy) | €506.6M |
| Other operating costs | €208.5M |
| Investment effects, financial result, taxes | €2.9M |
| **Total gross burn** | **€1,621.0M/year** |

| Revenue source | Est. annual inflow |
|---|---|
| Hospital revenue (DRG and outpatient billing) | €1,154.3M |
| Public grants (Free State: research, teaching, other duties) | €293.5M |
| Other operating income | €98.0M |
| **Total revenue offset** | **€1,545.9M/year** |

| Scenario | Net burn | Cash at hand | Runway (statutory credit ceiling of about €155M only, ignoring unknown cash) | Next round needed by |
|---|---|---|---|---|
| Optimistic: cost cuts bring the deficit back to the 2024 level | about €10M/year | UNKNOWN | more than 10 years | No "round": the deficit is absorbed within the budget |
| Base case: cuts offset TV-L rises only partly | about €50M/year | UNKNOWN | about 3 years | Ministry-approved credit or a state injection by about 2029 |
| Stress: 2025 deficit grows with TV-L rises and reform cuts | about €100M/year | UNKNOWN | about 1.5 years | Ministry intervention by about 2028 |

Cash figure used: none available. Observed figures are the FY2025 P&L (Jahresbericht 2025, retrieved 2026-11-17). The model's conclusion: in every scenario the employer survives through the state guarantee, but sustained deficits mean continued cost cutting, so new permanent IT positions will be scarce.

### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| 2025 | Board's cost-cutting programme ("Sparkurs") | Not disclosed | "Stellenabbau in fast allen Berufsgruppen, den Abbau von Leiharbeit in der Pflege und schmerzhafte Einsparungen in allen Bereichen" (job cuts in almost all occupational groups, cuts to agency nursing, painful savings in all areas) (Jahresbericht 2025 foreword). Net headcount still rose: average FTE went from 9,832.7 (2024) to 9,948.6 (2025) and headcount from 11,766 to 11,908, administration from 827.9 to 869.6 FTE. That suggests cuts through non-replacement and fewer agency staff, not dismissals. No forced redundancies were reported. |
| Dec 2025 | Medical Director at the staff Christmas party | - | "Der Vorstand hat sich sehr genau überlegt, ob wir uns bei einem Defizit von 54 Millionen Euro eine Weihnachtsfeier leisten können." (the board thought very carefully about whether it could afford a Christmas party with a €54M deficit) The final figure was €75.1M. |
| Nov 2011 | Deficit of €6.5M, the first in ten years | 340 positions (225 physicians and laboratory, 115 administration) | Through "natürliche Fluktuation" (natural attrition), meaning positions were not refilled ([Abendzeitung, 28.11.2011](https://www.abendzeitung-muenchen.de/muenchen/so-krank-sind-muenchens-krankenhaeuser-art-154484)). |

The institution has historically cut through attrition rather than forced dismissal. A practical consequence of the 2025 programme is that fixed-term contracts are not renewed, which hits new hires on fixed-term contracts first.

### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | **YES, as a Personalrat** (the public-sector equivalent under the Bavarian Staff Representation Act, BayPVG) | The [Personalvertretung page](https://lmu-klinikum.de/das-klinikum/wir-uber-uns/personalvertretung/8681ead93b4538e5) (CDP) names chair Curtis Warren Puckett and a severely-disabled-employee representative. The board acts as the employer and the Commercial Director heads the Dienststelle under Art. 7 BayPVG. The 2025 headcount table lists released Personalrat members. Under BayPVG the Personalrat co-determines rules for "Rufbereitschaft, Mehrarbeit und Überstunden" (on-call, extra work and overtime) and technical monitoring systems (Art. 75a), and must be involved before dismissals (Art. 77). |
| Collective agreement | **Sector agreement (Flächentarif): TV-L** for employees, TV-Ärzte for physicians, negotiated by ver.di and the dbb with the employers' association of the federal states (TdL). The Bavarian TV-EL Munich allowance also applies. | Every posting: "Die Vergütung richtet sich nach dem … TV-L". Art. 15(1) BayUniKlinG applies the Free State's rules. A Landtag answer (19/9099, 28.11.2025) says pay rises follow "die im Tarifvertrag der Länder (TV-L) vereinbarten Entgeltsteigerungen". Kununu reviewers: "Nach TVL, somit kaum Verhandlungsspielraum" (under TV-L, hardly any room to negotiate). |
| European works council (multinationals) | **N/A** | Single-country public body |
| Conflict signals | **Minor.** ver.di warning strikes during TV-L pay rounds (hospital press release "Warnstreiks am LMU Klinikum"). One reviewer finds the Personalrat ineffective ("Personalrat hat einem auch nicht wirklich weiter geholfen, da diese mehr Angst um ihren eigenen Hintern hatten", the staff council didn't really help because they were more afraid for their own skins; Kununu, Jul 2023, Ex-Angestellte/r oder Arbeiter/in, Personal / Aus- und Weiterbildung). Another notes "beginnende gewerkschaftliche Organisation und Unterstützung durch Personalrat" (union organising beginning, with staff council support) (Kununu, Aug 2024, Ex-Angestellte/r oder Arbeiter/in, Produktion). No union-busting or blocked elections found. | Kununu (query filters "Personalrat", "Tarif"), lmu-klinikum.de |

Senior engineers get **no außertariflich (AT) escape**: TV-L E15 at the end step is the ceiling for non-executive staff, which caps senior pay (Section 5). Collective-agreement protection is otherwise among the strongest in Germany: staff council involvement, social plans for restructuring, and protection from ordinary notice after 15 years' service at age 40 or over (§ 34(2) TV-L).

**Verdict:** **CAUTION.** Job protection for permanent staff is excellent (public employer, Personalrat, TV-L, unlimited state guarantee). The caution comes from the deteriorating finances (€75.1M loss), the 2025 cost-cutting programme that will constrain new permanent IT positions, and the prevalence of fixed-term contracts outside the core.

---

## Section 9: Regulated Industry

Heavily regulated:

- **KRITIS critical infrastructure** (BSI-KritisV hospital threshold: 30,000 inpatient cases a year; LMU Klinikum had 78,509 in 2025), plus the NIS2 implementation and the hospital IT-security duty under the statutory health insurance code (formerly § 75c, now § 391 SGB V). This means mandatory security standards (B3S Krankenhaus), audits and incident reporting.
- **Health-data protection:** GDPR Art. 9 together with **Art. 27 of the Bavarian Hospital Act (BayKrG)**, which restricts processing patient data outside the hospital and in practice pushes systems on-premise. MeDIC data use runs through a Use and Access Committee.
- **Medical Device Regulation (MDR, EU 2017/745)** for in-house clinical software and AI (including the in-house exemption under Art. 5(5)), plus the **EU AI Act** high-risk category for medical AI. The Medical Device Operator Ordinance (MPBetreibV) applies to MIT, which provides a "Beauftragter für Medizinproduktesicherheit" (medical device safety officer).
- **Public procurement and budget law** for purchasing (most of the Bavarian Budget Code does not apply under Art. 5(1) BayUniKlinG, but public procurement still does).

Practical engineering impact: change control on clinical systems, security reviews, slow procurement and tooling restrictions. One reviewer notes "eingeschränkte Nutzung moderner Tools außerhalb des Kliniknetzwerks" (limited use of modern tools outside the clinic network). Expect documentation overhead for anything touching patient data or clinical decisions.

**Verdict:** **CAUTION**

---

## Section 10: On-Call

- **IT operations carry on-call duty.** The current laboratory IT administrator posting explicitly lists "Teilnahme an der Rufbereitschaft" (participation in the on-call rota). Laboratory and clinical systems run 24/7 in a KRITIS hospital, so central infrastructure, network, LIS/LIMS and clinical application teams in MIT almost certainly run on-call rotas.
- **No on-call language** was found in the MeDIC (data integration), research AI or radiology software postings, which describe development and research work.
- On-call rules are co-determined by the Personalrat, and Rufbereitschaft is paid under TV-L (§ 8(3) TV-L). One clinical reviewer calls it "Rufbereitschaften schlecht bezahlt" (on-call is poorly paid) (Kununu, Mar 2024, Angestellte/r oder Arbeiter/in, department not stated).

**Verdict:** **CAUTION (team-dependent).** FAIL for infrastructure and operations roles in MIT and laboratory IT; likely PASS for MeDIC development and research software roles. Verify per posting.

---

## Section 11: Interview Process

Based on Glassdoor (current profile, CDP).

| Metric | Value |
|---|---|
| Difficulty | 2.83 / 5 (12 interviews) |
| Positive experience | 91.7% |
| Average duration | about 52 days (fastest 1 day for a Bioinformatician; slowest about 120 days for a Postdoctoral Fellow) |
| Rounds | Not aggregated by Glassdoor; individual reports describe 1-2 rounds |

Process steps reported, as share of the 12 reports: one-to-one interview 26%, qualification test 13%, background check 13%, personality test 13%, group interview 9%, phone interview 9%, presentation 9%, IQ test 9%. **There are no reports from software or IT candidates.** The available reports (nursing, PhD, postdoc, study coordinator) describe short, friendly, conversation-based interviews about background, motivation and the role. Research groups add a presentation of past work followed by a team meeting.

Glassdoor gives no evidence of LeetCode-style coding rounds or formal system-design interviews. The format is experience and motivation-based, the usual German public-sector selection interview. The hospital does not reimburse travel costs for interviews (stated in every posting).

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | **FAIL.** University hospital; software is a support function. 3 of 144 vacancies are IT roles. |
| Not consulting | **PASS.** In-house work only. |
| Profitable | **FAIL.** FY2025 loss €75.1M (2024: -€10.5M); non-profit by statute, with an unlimited state guarantee. |
| Employee count | About 11,900 headcount, 9,949 FTE (2025) |
| English-speaking | **CONDITIONAL.** Research AI accepts English only; central and laboratory IT require German C1; MeDIC wants both. |
| Local entity + engineering contracts | **PASS.** Direct public-law employer, TV-L contracts, VBL pension. |
| Location / work model | Campus Großhadern (U6 Klinikum Großhadern) or MeDIC Martinsried (bus 259/266/267); hybrid "bei Eignung" (where suitable), no fully remote work |
| Glassdoor | 3.6 global (130 rated) / 3.8 Germany and Munich; WLB 3.9 / 3.8; only 5 reviews in the last 12 months; 1 Software Engineer review (3.0) |
| Kununu | 3.3 / 5, 59% recommend, 310 employee reviews, below the sector average of 3.6, not a Top Company; IT department about 3.2 (4 reviews) |
| Salary | **BELOW.** TV-L E13 Stufe 3-4 = €66.9K-€73.2K, 24-31% below the Munich Senior SWE median (€96.4K); no equity |
| AI/ML content | Real but research-led: new Institute for AI in Medicine (2025), clinical LLM chat platform in central IT, surgical computer vision, MeDIC FHIR data platform |
| Computer-language/Tech-stack | Polyglot: Java/C#/Python/R/Scala at MeDIC (Kafka, NiFi, PostgreSQL, FHIR); Python/PyTorch in research; on-premise Docker/Kubernetes, VMware/Proxmox; no public cloud |
| No on-call | **CAUTION.** On-call in IT operations and laboratory IT; none found for MeDIC or research development |
| WLB / Stability | WLB good for office IT (flexitime, 38.5-hour week, 30 days' leave). Stability: insolvency-proof, but deficits are rising and a 2025 cost-cutting programme cuts jobs. |
| Works council / collective agreement | **YES / YES.** Personalrat under BayPVG plus TV-L (Flächentarif). Strong protection for permanent staff. |
| Regulated industry | **CAUTION.** KRITIS/NIS2, GDPR Art. 9 + BayKrG Art. 27, MDR/AI Act |
| Review themes | Communication breakdown (systemic), authoritarian upper management (nursing, some admin units), bureaucracy and legacy IT; positives are security, flexitime and in-house IT variety |
| Contract type | Fixed-term is common in research and AI roles (both current analytics/AI postings: 1 year initially). Permanent ("unbefristet") roles are mostly in core IT operations. |
| Hiring volume | Low. 3 IT roles open on 2026-11-17, during a cost-cutting year. MeDIC and LLM roles seen in 2024-2025 are closed. |

---

## Section 13: Verdict

**Overall recommendation: Exclude under the standard criteria; at most Monitor, narrowly, under a public-sector track that accepts TV-L pay.**

**Strengths:**
- One of Germany's largest and best-ranked university hospitals (Newsweek #17 worldwide in 2026).
- An insolvency-proof public employer with an unlimited state guarantee.
- Strong collective protection: Personalrat, TV-L, the employer-funded VBL pension, 30 days' leave, a 38.5-hour week and flexitime. WLB for office-based IT staff is rated well (Glassdoor 3.9).
- Genuinely interesting applied work: a FHIR-based clinical data integration platform (MeDIC), a clinical LLM platform in central IT, surgical computer vision, and a new Institute for AI in Medicine.

**Hard blockers:**
1. **Not software-centric.** Software engineering is a small support function inside a hospital of about 12,000 staff. On the review date, 3 of 144 openings were IT roles, and two of the three are operations or research positions.
2. **Pay below the market bracket by design.** TV-L E13 Stufe 3-4 gives €66.9K-€73.2K. Even two steps granted ahead under § 16(5) TV-L reach only €81.9K, the Munich 25th percentile. The median is €96.4K and the 75th percentile €117K. There is no equity, no performance bonus and no AT route above E15.
3. **Not profitable, and getting worse.** The loss widened from €10.5M (2024) to €75.1M (2025). The board responded with job cuts across almost all occupational groups. New permanent IT headcount is unlikely while the programme runs.
4. **Fixed-term contracts dominate the AI and data roles.** Both current analytics and AI postings start at one year fixed-term. This fails the full-time, permanent role criterion for exactly the roles closest to an AI/ML profile.

**Secondary concerns:**
- German C1 is required in central and laboratory IT; only research groups accept English alone.
- Infrastructure and operations roles carry on-call duty.
- KRITIS, GDPR + BayKrG and MDR regulation, with on-premise-only tooling.
- Legacy systems and thin staffing in central IT (Glassdoor IT manager, Jan 2026).
- Kununu at 3.3 and 59% recommend, with persistent communication complaints. These are mostly from non-IT units.
- A polyglot stack where Python is one option among five at MeDIC.

**Recommendation:** Do not pursue LMU Klinikum as an engineering employer under the standard criteria. If a public-sector track that trades salary for TV-L stability is in play, only one kind of posting is worth considering: a **permanent ("unbefristet") MeDIC or MIT software or data-platform role** that states English is acceptable and has no Rufbereitschaft. Before applying, verify:

1. The contract type in writing.
2. The grade (E13 vs E14) and Stufe placement, including whether § 16(5) steps ahead are on offer.
3. The German level actually required in the team.
4. Whether the team runs an on-call rota.
5. The home-office share.
6. Whether the post is funded from the hospital budget or a time-limited grant.

---

## Section 14: Sources

**Company, legal, finance**
- [LMU Klinikum - Impressum](https://lmu-klinikum.de/imprint) (curl)
- [LMU Klinikum - Impressum (alternate)](https://lmu-klinikum.de/impressum/4831ded15b84833d)
- [BayUniKlinG - Bayerisches Universitätsklinikagesetz (full text)](https://www.gesetze-bayern.de/Content/Document/BayUniKlinG/true) (curl)
- [LMU Klinikum Jahresbericht 2025](https://cdn.lmu-klinikum.de/349235d86f461e6a/4b448ed1875e/JAHRESBERICHT-2025_Webversion.pdf) (curl + pypdf)
- [LMU Klinikum Jahresbericht 2024](https://cdn.lmu-klinikum.de/1d24f1896b4f4f11/1c10e9245ffb/JAHRESBERICHT-2024_NEU_23092025.pdf) (curl + pypdf)
- [LMU Klinikum Jahresbericht 2024 (older link, now S3 AccessDenied)](https://cdn.lmu-klinikum.de/df3e0654709b50d0/75ea64537951/JAHRESBERICHT-2024.pdf)
- [LMU Klinikum Jahresbericht 2022](https://cdn.lmu-klinikum.de/0ac0de341c830f63/6fc21386b2e4/JAHRESBERICHT-2022_web.pdf)
- [Bayerischer Landtag Drucksache 19/9099 (28.11.2025): Pflegekräfte an staatlichen Kliniken in München](https://www.bayern.landtag.de/www/ElanTextAblage_WP19/Drucksachen/Schriftliche%20Anfragen/19_0009099.pdf) (curl + pypdf)
- [NorthData - search "Klinikum der Universität München"](https://www.northdata.de/Klinikum%20der%20Universit%C3%A4t%20M%C3%BCnchen) (CDP)
- [NorthData - KMD Klinikum der Universität München Dienstleistungs GmbH, HRB 152516](https://www.northdata.de/KMD%20Klinikum%20der%20Universit%C3%A4t%20M%C3%BCnchen%20Dienstleistungs%20GmbH,%20M%C3%BCnchen/HRB%20152516) (CDP)
- [Bundesanzeiger full-text search (returned a technical error)](https://www.bundesanzeiger.de/pub/de/suchergebnis?0&fulltext=LMU+Klinikum) (CDP)
- [Abendzeitung, 28.11.2011: So krank sind Münchens Krankenhäuser](https://www.abendzeitung-muenchen.de/muenchen/so-krank-sind-muenchens-krankenhaeuser-art-154484) (curl)
- [LMU Klinikum among the world's 20 best hospitals (Newsweek 2026)](https://lmu-klinikum.de/newscenter/news/lmu-university-hospital-munich-among-the-world-s-20-best-hospitals/79b8609f92d0e5ef)
- [Warnstreiks am LMU Klinikum (press release)](https://www.lmu-klinikum.de/aktuelles/pressemitteilungen/warnstreiks-am-lmu-klinikum/52f0ed278998fd38)
- [LMU Klinikum unter den besten Arbeitgebern in der Pflege (stern 2023/24)](https://www.lmu-klinikum.de/aktuelles/newsmeldungen/lmu-klinikum-unter-den-besten-arbeitgebern-in-der-pflege/b6b0eb2ff155af8c) (CDP)

**Organisation and departments**
- [Medizintechnik und IT (MIT)](https://lmu-klinikum.de/das-klinikum/zentrale-bereiche/medizintechnik-und-it/0f3f8dbd577a93eb) (CDP)
- [Zentrum für Medizinische Datenintegration und -analyse (MeDIC LMU)](https://lmu-klinikum.de/das-klinikum/zentrale-bereiche/zentrum-fur-medizinische-datenintegration-und-analyse-mediclmu/bbd95a62ce3a8f9b) (CDP)
- [Digitale Medizin und LMU MedBiobank](https://lmu-klinikum.de/das-klinikum/zentrale-bereiche/digitale-medizin-und-lmu-medbiobank/5a4e3a7d8658089c) (CDP)
- [Personalvertretung (Personalrat)](https://lmu-klinikum.de/das-klinikum/wir-uber-uns/personalvertretung/8681ead93b4538e5) (CDP)
- [Medizininformatik-Initiative - Datenintegrationszentren](https://www.medizininformatik-initiative.de/de/konsortien/datenintegrationszentren)
- [MII Symposium 2024 - MeDIC LMU presentation](https://www.medizininformatik-initiative.de/sites/default/files/2025-01/MII-Symposium_2024_Albashiti_Havla.pdf)
- [GitHub org mediclmu](https://github.com/mediclmu) (GitHub API, curl)
- [GitHub org KUMteamIM (MIT Web-Anforderungen und -Dienste)](https://github.com/KUMteamIM) (GitHub API, curl)
- [GitHub org lmu-data-lab](https://github.com/lmu-data-lab) (GitHub API, curl)

**Job postings (stack, language, contract and pay evidence only)**
- [LMU Klinikum Stellenanzeigen (144 vacancies, 2026-11-17)](https://www.lmu-klinikum.de/jobs) (CDP)
- [Informatiker - KI und Computer Vision in der Chirurgie (2026-K-0432)](https://www.lmu-klinikum.de/stellenanzeigen/informatiker-ki-und-computer-vision-in-der-chirurgie/bdf7cd7e488113e4) (CDP)
- [IT-Systemadministrator, Institut für Laboratoriumsmedizin (2026-K-0420)](https://www.lmu-klinikum.de/stellenanzeigen/it-systemadministrator/a3e3ffbc7dfd54c9) (CDP)
- [Projektmanager - Analyse und Integration (2026-K-0424)](https://www.lmu-klinikum.de/stellenanzeigen/projektmanager-analyse-und-integration/62904ab3ae723b33) (CDP)
- [Senior Software Engineer, MeDIC (expired)](https://lmu-klinikum.de/stellenanzeigen/senior-software-engineer/43a37bdb17ae3e4d.pdf) (search snippet; URL now redirects)
- [Senior Software Engineer, MeDIC (expired, 2nd version)](https://lmu-klinikum.de/stellenanzeigen/senior-software-engineer/e87c035685d369a7.pdf)
- [Senior Software Engineer (expired, 3rd version)](https://www.lmu-klinikum.de/stellenanzeigen/senior-software-engineer/e07958375ec2afd0.pdf)
- [Software Engineer, MeDIC (expired)](https://www.lmu-klinikum.de/stellenanzeigen/software-engineer/1fdfed28a7f2f2d1.pdf)
- [Junior Software Engineer, MeDIC (archived copy on rapidjob.de)](https://rapidjob.de/job/i4fn3hc) (CDP)
- [LLM Engineer / LLM Data Scientist (expired)](https://lmu-klinikum.de/stellenanzeigen/llm-engineer-llm-data-scientist/dba74bc1b0b60f6a.pdf) (search snippet)
- [DevOps Engineer, MeDIC (expired)](https://lmu-klinikum.de/stellenanzeigen/devops-engineer/026aa5af67cd3e25.pdf) (search snippet)
- [Systemadministrator Linux/Kubernetes (expired)](https://lmu-klinikum.de/stellenanzeigen/systemadministrator-linux-kubernetes/f64475e79b88b062.pdf) (search snippet)
- [Clinical Research Software Engineer, Radiology (expired)](https://lmu-klinikum.de/stellenanzeigen/clinical-research-software-engineer/9618184849b4bf76.pdf) (search snippet)
- [Data Engineer, MeDIC (expired)](https://lmu-klinikum.de/stellenanzeigen/data-engineer/dddb7d2bdcfd288f.pdf) (search snippet)
- [Senior Webentwickler, MIT (expired)](https://www.lmu-klinikum.de/stellenanzeigen/senior-webentwickler/fc34212673e3a1f5.pdf) (search snippet)
- [Software Engineer, Institut für Laboratoriumsmedizin, 2024-K-0095 (expired)](https://www.klinikum.uni-muenchen.de/Institut-fuer-Laboratoriumsmedizin/download/de/stellenangebote/2024-K-0095.pdf) (search snippet)
- LinkedIn Jobs, voyager API sweep for "LMU Klinikum", Munich geo 100477049 (CDP, logged-in session)

**Reviews**
- [Glassdoor - company search "LMU Klinikum"](https://www.glassdoor.com/Search/results.htm?keyword=LMU%20Klinikum) (CDP)
- [Glassdoor - LMU Klinikum overview](https://www.glassdoor.de/%C3%9Cberblick/Arbeit-bei-LMU-Klinikum-EI_IE3943883.11,23.htm) (CDP)
- [Glassdoor - LMU Klinikum reviews (global)](https://www.glassdoor.de/Bewertungen/LMU-Klinikum-Bewertungen-E3943883.htm) (CDP)
- [Glassdoor - LMU Klinikum reviews, Germany](https://www.glassdoor.de/Bewertungen/LMU-Klinikum-Deutschland-Bewertungen-EI_IE3943883.0,12_IL.13,24_IN96.htm) (CDP)
- [Glassdoor - LMU Klinikum reviews, München](https://www.glassdoor.de/Bewertungen/LMU-Klinikum-M%C3%BCnchen-Bewertungen-EI_IE3943883.0,12_IL.13,20_IC4990924.htm) (CDP)
- [Glassdoor - LMU Klinikum reviews, Software Engineer](https://www.glassdoor.de/Bewertungen/LMU-Klinikum-Software-Engineer-Bewertungen-EI_IE3943883.0,12_KO13,30.htm) (CDP)
- [Glassdoor - Klinikum der Universität München (legacy profile)](https://www.glassdoor.de/Bewertungen/Klinikum-der-Universit%C3%A4t-M%C3%BCnchen-Bewertungen-E932293.htm) (CDP)
- [Glassdoor - LMU Klinikum interviews](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/LMU-Klinikum-Fragen-im-Vorstellungsgespr%C3%A4ch-E3943883.htm) (CDP)
- [Glassdoor - LMU Klinikum salaries](https://www.glassdoor.de/Gehalt/LMU-Klinikum-Geh%C3%A4lter-E3943883.htm) (CDP)
- [Kununu - Klinikum der Universität München](https://www.kununu.com/de/klinikum-der-universitaet-muenchen) (CDP; curl returned 405)
- [Kununu - reviews](https://www.kununu.com/de/klinikum-der-universitaet-muenchen/kommentare) (CDP)
- [Kununu - reviews, IT department](https://www.kununu.com/de/klinikum-der-universitaet-muenchen/kommentare?department=it) (CDP)
- [Kununu - reviews mentioning "Personalrat"](https://www.kununu.com/de/klinikum-der-universitaet-muenchen/kommentare?query=Personalrat) (CDP)
- [Kununu - reviews mentioning "Tarif"](https://www.kununu.com/de/klinikum-der-universitaet-muenchen/kommentare?query=Tarif) (CDP)
- [Kununu - reviews mentioning "Überstunden"](https://www.kununu.com/de/klinikum-der-universitaet-muenchen/kommentare?query=%C3%9Cberstunden) (CDP)
- [Kununu - reviews mentioning "Homeoffice"](https://www.kununu.com/de/klinikum-der-universitaet-muenchen/kommentare?query=Homeoffice) (CDP)
- [Kununu - reviews mentioning "Digitalisierung"](https://www.kununu.com/de/klinikum-der-universitaet-muenchen/kommentare?query=Digitalisierung) (CDP)
- [Kununu - reviews 2026](https://www.kununu.com/de/klinikum-der-universitaet-muenchen/kommentare?year=2026) (CDP)
- [Kununu - reviews 2025](https://www.kununu.com/de/klinikum-der-universitaet-muenchen/kommentare?year=2025) (CDP)
- [Teamblind - search "LMU Klinikum" (no results)](https://www.teamblind.com/search/LMU%20Klinikum) (CDP)
- [Great Place to Work Deutschland - awarded companies](https://www.greatplacetowork.de/unternehmen-mit-auszeichnung/) (CDP)

**Compensation**
- [TV-L Entgelttabellen 2026-2028](https://oeffentlicher-dienst-news.de/oeffentlicher-dienst-laender-die-neuen-entgelttabellen-tv-l-2026-bis-2028/) (curl)
- [TV-L Tarifrunde 2026 (increases)](https://oeffentlichen-dienst.de/tarifrunden/2026-tv-l.html)
- [Weihnachtsgeld öffentlicher Dienst 2026 (TV-L Jahressonderzahlung rates)](https://oeffentlicher-dienst-news.de/weihnachtsgeld-oeffentlicher-dienst-2026/)
- [TV-EL - Bavarian Munich allowance (ergänzende Leistung)](https://www.gesetze-bayern.de/Content/Document/BayTV_EL/true) (curl)
- [BayPVG - Bayerisches Personalvertretungsgesetz](https://www.gesetze-bayern.de/Content/Document/BayPVG/true) (curl)
- [levels.fyi - Senior Software Engineer, Munich](https://www.levels.fyi/t/software-engineer/levels/senior/locations/munich-deu) (CDP)
- [levels.fyi - LMU Klinikum (404)](https://www.levels.fyi/companies/lmu-klinikum/salaries) (CDP)

**Location**
- [Nominatim - Marchioninistraße 15, 81377 München](https://nominatim.openstreetmap.org/search?q=Marchioninistra%C3%9Fe+15%2C+81377+M%C3%BCnchen&format=json&addressdetails=1) (curl)
- [Nominatim - Fraunhoferstraße 20, 82152 Planegg](https://nominatim.openstreetmap.org/search?q=Fraunhoferstra%C3%9Fe+20%2C+82152+Planegg&format=json&addressdetails=1) (curl)
- [Overpass API (stops and route relations)](https://overpass-api.de/api/interpreter) (curl)
