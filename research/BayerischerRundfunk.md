# Bayerischer Rundfunk (BR) - Full Research Report

_Researched: 2026-11-10_

> **Critical Disqualifiers**
> 1. **German is a primary requirement.** The only open software role (Data / Integration Platform Engineer, Fachgruppe KI und Datentechnologien) is posted in German only and asks for "Sehr gute Deutsch- und Englischkenntnisse". Every other IT posting (network admin, broadcast engineering) asks for "sehr gute Deutsch-" and only "gute Englischkenntnisse". This fails the English-first criterion.
> 2. **Not a profitable company, and loss-making on its own terms.** BR is a public-law broadcaster (Anstalt des öffentlichen Rechts) funded by the Rundfunkbeitrag. It closed 2025 with a deficit of €44.4M. The Bavarian Court of Audit (ORH, Oct 2026) found it "durchgehend bilanziell überschuldet" (balance-sheet overindebted throughout the review period) and expects reserves to be fully used up by the end of 2028.
> 3. **Pay is set by a house tariff.** "Faire tarifliche Bezahlung" with no published band, no bonus and no equity. Available data points for engineers cluster around €70k to €87k, below the Munich bracket for senior engineers at large profitable corporations.
>
> The full report follows for completeness.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 1949 (77 years). Glassdoor lists 1949 as founding year; BR took over from Radio München |
| Employees | ~3,500 permanent staff (BR's own Kununu profile, "3.500 feste Mitarbeitende"); "rund 5.000 Mitarbeitende" including freelancers (Kununu and Glassdoor profile texts) |
| Revenue (FY2025) | ~€1.02B. Rundfunkbeitrag income allocated to BR: €1,021.8M in 2025 vs €1,019.1M in 2024 (Beitragsservice annual report 2025, including the share passed on to the state media authority). Annual budget "rund 1 Milliarde Euro" (Intendantin, Oct 2024) |
| Profitability | **FAIL.** Not a profit-seeking entity. 2025 result **-€44.4M** (planned gap had been ~€70M). ORH projects a cumulative shortfall of **€106.4M by 31 Dec 2028** and calls BR "durchgehend bilanziell überschuldet" |
| Ownership | Public. Anstalt des öffentlichen Rechts under Bavarian law, member of the ARD. Legal supervision (Rechtsaufsicht) by the Bavarian State Ministry of Science and the Arts. Governed by the Rundfunkrat and Verwaltungsrat |
| Software-centric | Public broadcaster: radio, TV, BR24, ARD Mediathek contributions, orchestras and choir. **FAIL**, see below |

### Key People

- **Dr. Katja Wildermuth**: Intendantin and legal representative (Impressum, Nov 2026)
- **Thomas Hinrichs**: Programmdirektor Information
- **Björn Wilhelm**: Programmdirektor Kultur
- **Ilse Aigner**: Chair of the Verwaltungsrat
- **Prof. Dr. Dr. habil. Godehard Ruppert**: Chair of the Rundfunkrat

The Glassdoor CEO rating (15%) is attached to **Ulrich Wilhelm**, who left the Intendant post years ago; the figure is stale and does not reflect the current leadership.

### Funding History

Not applicable: no venture or private-equity funding. BR is financed by the Rundfunkbeitrag (licence fee), fixed by the Länder on the recommendation of the KEF.

| Date | Event | Effect |
|---|---|---|
| Feb 2024 | KEF recommends raising the fee from €18.36 to €18.94 from 1 Jan 2025 | Länder block the increase |
| Nov 2024 | ARD and ZDF file constitutional complaints (1 BvR 2524/24, 2525/24) | Hearing at the BVerfG on 23 Jun 2026; decision not found as of this research |
| 2026 | New KEF recommendation: €18.64 from 1 Jan 2027 | Fee still €18.36 until a new state treaty or court decision |

BR attributes €32.6M of the 2025 deficit directly to the increase that did not happen.

### Business Model

A statutory public-service broadcaster for Bavaria: two TV channels (BR Fernsehen, ARD alpha), several radio stations (Bayern 1/2/3, BR-Klassik, BR24, BR Heimat), digital offerings (BR24, contributions to the ARD Mediathek and ARD Audiothek), plus the BR Symphony Orchestra, BR Radio Orchestra and BR Choir. Revenue is not earned in a market: it is a fee allocation.

### Software-Centric Assessment

**FAIL.** Software and IT are a support function inside the Produktions- und Technikdirektion (Hauptabteilung IT und Medientechnik). Out of 38 open postings on 10 Nov 2026, exactly **one** is a software engineering role (Data / Integration Platform Engineer). The other technical postings are a network administrator (Cisco/Arista, SMPTE ST 2110) and a strategy/process role; recent technical postings on germantechjobs are broadcast engineers. The AI + Automation Lab and BR Data (journalism-tech teams) publish prototypes and proofs of concept on GitHub, several of which are explicitly labelled "not ready for production use". There is genuine engineering (an internal AI Platform with a Knowledge Gateway is being built), but the organisation's product is media content.

### Consulting-Adjacency Assessment

**PASS.** BR does not bill clients or use consultant titles. However, the target team describes itself as an "Umsetzungs- und Brückenteam zwischen Anforderungen, Technik und Betrieb" (implementation and bridging team between requirements, technology and operations) that "begleitet KI-, Automatisierungs- und Datenvorhaben" for internal departments. This is internal platform work with a strong stakeholder-facing element, not external consulting.

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **Bayerischer Rundfunk, Anstalt des öffentlichen Rechts** | No Handelsregister entry (public-law body created by Bavarian statute, the Bayerisches Rundfunkgesetz). USt-IdNr. **DE 129 523 494** (Impressum) | Rundfunkplatz 1, 80335 München | Production and distribution of public-service radio, TV and online content for Bavaria ("informieren, unterhalten und bilden"), as a member of the ARD |

Verification: as a public-law Anstalt, BR has no HRB number; the Impressum gives legal form, legal representative, supervisory bodies and VAT ID. The statute text (BayRG) could not be retrieved from gesetze-bayern.de (JavaScript-rendered page returned no text via curl or CDP), so the purpose above is paraphrased from the Impressum and BR's own employer profile. Engineers are employed **directly by BR** on permanent, tariff-bound contracts (the posting states "Befristung: unbefristet", 38.5 h/week). There is no PEO/EOR. The purpose is not a sales shell.

**Verdict:** **PASS**

---

## Section 3: Office Location

The posting names two sites: **"München - Funkhaus, München - Freimann"**.

- **Funkhaus:** Rundfunkplatz 1, 80335 München (Maxvorstadt, St. Benno-Viertel). Confirmed by the Impressum; Nominatim resolves it to "BR Haus 1, Rundfunkplatz" (48.1442, 11.5547).
- **Freimann:** Floriansmühlstraße 60, 80939 München (Schwabing-Freimann). Nominatim resolves it to the "Bayerischer Rundfunk" campus (48.1897, 11.6278). The BR careers site describes it as "der kreative Campus in Freimann"; production and technology roles (e.g. the strategy role in the Produktions- und Technikdirektion, the network admin role) are posted for Freimann only.

**Nearest public transport** (Overpass, straight-line distances):

| Site | Stop | Type / lines | Distance |
|---|---|---|---|
| Funkhaus | Hopfenstraße | Tram stop | ~200 m |
| Funkhaus | Hauptbahnhof Nord | Bus (100) and tram | ~210 to 470 m |
| Funkhaus | München Hauptbahnhof (incl. Starnberger Bahnhof platforms) | S-Bahn, U-Bahn, regional and long-distance rail | ~300 to 420 m |
| Funkhaus | Stiglmaierplatz | U-Bahn (U1/U7) and tram | ~450 m |
| Freimann | Unterföhring, Alte Münchner Straße | Bus 188, 231 | ~660 m |
| Freimann | Unterföhring, Siedlerstraße | Bus 188, 189, 231, 232 | ~780 m |
| Freimann | Freimann | U-Bahn (U6) | ~1.0 km |
| Freimann | Unterföhring | S-Bahn (S8) | ~1.4 km |

BR also advertises free parking at the workplace.

**Work model:** Hybrid. The posting offers "Attraktive Arbeitszeit- und Homeoffice-Regelungen"; the benefits page says "Hybrides Arbeiten: im Büro oder Zuhause, abhängig von der jeweiligen Tätigkeit" and "Gleitzeit- oder Schichtmodell, je nach Arbeitsplatz". No fixed day count is published. A Kununu IT reviewer (June 2026) writes that "in großem Maß Home Office möglich ist". No fully remote option is advertised.

---

## Section 4: Reviews

**GPTW:** BR does not appear in Great Place to Work Germany listings or "Bayerns Beste Arbeitgeber" results found in search. **No GPTW certification.**

### Glassdoor

Retrieved via Chromium over CDP (glassdoor.com redirects to glassdoor.de; ratings read from the page's embedded JSON).

| Metric | Global | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | 3.6 (36 shown / 42 total reviews) | 3.8 (27 reviews) | 3.8 (27 reviews) | 5.0 (1 rating, no review text) |
| **WLB** | 4.0 | 3.8 | 3.8 | 5.0 |
| **Culture & Values** | 3.5 | 3.6 | 3.6 | 5.0 |
| **Comp & Benefits** | 3.7 | 3.8 | 3.8 | 3.0 |
| **Career Opportunities** | 2.6 | 2.8 | 2.8 | 5.0 |
| **Senior Management** | 2.6 | 2.9 | 2.9 | 4.0 |
| **Diversity & Inclusion** | 3.7 | 3.9 | 3.9 | 5.0 |
| **% Recommend** | 71% | 69% | 69% | n/a |
| **CEO Approval** | 15% (rated CEO: Ulrich Wilhelm, stale) | 17% | 17% | n/a |
| **Business Outlook** | 19% positive | 22% positive | 22% positive | n/a |

All filters are under 50 reviews and the Software Engineer filter has a single rating: **directional only**. The Germany and Munich filters return identical data (nearly all reviews are from Munich). Glassdoor's industry average for Media & Communication is 3.7.

### Kununu

Slug `bayerischer-rundfunk2` (the obvious slugs `bayerischer-rundfunk`, `br`, `bayerischerrundfunk` returned nothing via curl; found through Kununu search over CDP). Data via Chromium over CDP.

- **Overall score:** 3.6 / 5.0 (equal to the media industry average of 3.6)
- **Recommendation rate (Weiterempfehlung):** 70% (last 2 years)
- **Total reviews:** 442 (employee reviews: 393; 229 salary entries)
- **Sub-scores:** Karriere & Gehalt 3.3, Unternehmenskultur 3.6, Arbeitsumgebung 3.6, Vielfalt 3.8; Gehalt & Benefits 3.6 with 57% salary satisfaction (374 ratings)
- **IT department filter:** **4.0 / 5.0, 90% recommend, 33 reviews**
- **Low-score filter (1 to 2 stars):** 36 of 393 reviews, avg 1.5
- **Kununu Top Company:** **NO**

### Blind / Teamblind

`teamblind.com/company/Bayerischer-Rundfunk` returns "Page not found". **No Blind presence**, as expected for a German public broadcaster.

### Review Themes (2023-2026)

**Positives:**
- **Work-life balance, especially for families, and time tracking.** "Gerade für Familien mit Kindern eine super Sache. Überstunden passieren, können aber abgefeiert werden. Zeitaufschreibung sorgt für einen fairen Ausgleich." (Kununu, Jun 2026, Angestellte/r oder Arbeiter/in, IT, München). Glassdoor's strongest sub-score is WLB (4.0 global).
- **Working conditions and benefits are rated highly in IT.** "Man geht sehr gerne zu Arbeit und die Arbeitsbedingungen sind wirklich hervorragend" (Kununu, Jun 2026, Führungskraft, IT, München).
- **Purpose and security.** "Garant für faire Arbeitsbedingungen, tarifgebunden mit sozialer und gesellschaftlicher Verantwortung." (Kununu, Feb 2026, reviewer role not shown in the overview excerpt). "Stabil, sicher, interessant, groß und sympathisch" (Glassdoor, Jan 2025, current Leitender Redakteur, München).
- **Technical innovation in IT.** "Viel Innovation in der Technik" (Kununu, Jun 2026, Angestellte/r oder Arbeiter/in, IT, München).

**Negatives:**
- **Slow, bureaucratic decision-making and resistance to change.** "Teilweise zu langsame Entscheidungsprozesse, lieber absichern und das 5x bevor etwas einfach mal ausprobiert wird." (Kununu, Jun 2026, Angestellte/r oder Arbeiter/in, IT, München). "Viele alte Strukturen mit Bürokratie und teilweise wenig Bereitschaft zur Veränderung" (Kununu, Jun 2026, Führungskraft, IT, München). "Viel 'Apparat' wenig agil" (Glassdoor, Jan 2025, current Leitender Redakteur, München).
- **Rigid tariff grading and limited career paths.** "Karriere hängt an den Aufgaben + Tarifvertrag." and "Karriere nicht nur dadurch möglich machen, dass man Führungskraft wird." (Kununu, Jun 2026, Angestellte/r oder Arbeiter/in, IT, München). "Bezahlung nach Tätigkeit - nicht nach Hochschulabschluss" (Kununu, Apr 2023, Angestellte/r oder Arbeiter/in, IT, München). Career Opportunities is the weakest Glassdoor score (2.6).
- **Internal communication.** "Manche Führungskräfte filtern sehr" (Kununu, Jun 2026, Angestellte/r oder Arbeiter/in, IT, München). "man wird bei den vielen Neuerungen nicht in Entscheidungen eingebunden sondern bekommt die Ergebnisse in Meetings präsentiert" (Glassdoor, Oct 2024, current Sachbearbeiter, München).
- **Austerity and contract insecurity (non-IT).** "Keine Planbarkeit für viele da fast nur noch befristete Verträge." (Kununu, Jun 2026, role not shown in the overview excerpt). "Es geht nur noch um Abbau und Sparmaßnahmen und das auf dem Rücken vieler Mitarbeiter." (Kununu, Jun 2026, Ex-Angestellte/r oder Arbeiter/in, München, department not stated).
- **Poor leadership in parts of the house (non-IT).** "Es wird erpresst, gedisst und man wird regelrecht weggeekelt." (Kununu, Jun 2026, Ex-Angestellte/r oder Arbeiter/in, München, department not stated). "furchtbar, man wird klein gehalten" (Kununu, Jun 2026, Angestellte/r oder Arbeiter/in, Administration / Verwaltung, München). "Es wird einem immer wieder gezeigt wer am längeren Hebel sitzt." (Kununu, Nov 2026, Angestellte/r oder Arbeiter/in, Produktion, München).
- **Age-related treatment.** Several low-score reviews complain about treatment of older staff: "Nein - vor allem Altersdikriminierung" (Kununu, Jun 2026, Angestellte/r oder Arbeiter/in, München, department not stated).

Overlap with hard red flags: layoffs (via non-replacement, see Section 8), communication breakdown and, in some non-IT departments, fear-driven leadership. None of the IT-department reviews raises these.

### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | Present in a minority of non-IT reviews (production, administration, unspecified). "Immer schön von oben nach unten treten" (Kununu, Jun 2026, Angestellte/r oder Arbeiter/in, München). Not reported in IT, where reviewers describe "ein sehr vertrauensvolles Verhalten auf Augenhöhe" (Kununu, Jun 2026, Angestellte/r oder Arbeiter/in, IT, München) |
| 24/7 Work Expectation | Not reported for IT. Shift rosters are criticised in production ("Mit den disponierten Dienstplänen wirklich schwierig", Kununu, Nov 2026, Angestellte/r oder Arbeiter/in, Produktion, München) |
| Internal Surveillance | None found. Time recording exists and is described positively as ensuring overtime compensation |
| Fear-driven Management | Isolated: "Nur nicht gegen den Strom schwimmen. Immer schön die Hierarchie einhalten" (Kununu, Nov 2026, Angestellte/r oder Arbeiter/in, Produktion, München) |
| Communication Breakdown | Recurring across departments and platforms: filtering by managers, too many channels ("Intranet, Teams, Chats, Mail"), decisions presented rather than consulted |
| Unpaid Overtime | No. Overtime is recorded and "kann abgefeiert werden" (Kununu, Jun 2026, IT) |
| Silent Firings | Not reported as dismissals. Non-IT reviewers describe chains of fixed-term contracts and being made to feel "überflüssig"; headcount reduction runs through non-replacement |
| Work-Life Balance issues | Not in IT (WLB rated "Top" / "Könnte nicht wirklich besser sein"). Issues in shift-rostered production roles |

**Risk level: MODERATE overall, LOW for IT.** The negatives are mostly (b) public-sector bureaucracy and slow change management, made sharper by an austerity programme since 2024, plus (c) localised leadership problems in production and administration. The 33 IT-department reviews average 4.0 with 90% recommendation.

---

## Section 5: Compensation

### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| Job posting (Nov 2026) | Data / Integration Platform Engineer | "Faire tarifliche Bezahlung", no band | 0 | 0 | UNVERIFIED | 1 |
| germantechjobs via devjobsscanner (2026) | Broadcast Engineer / Medieningenieur / Systemingenieur (several postings) | €70k to €80k | 0 | 0 | €70k to €80k | 5 postings |
| Kununu | Ingenieur:in (München) | Ø €87.0k | 0 | 0 | ~€87k | 6 |
| Kununu | Systemingenieur:in (München) | Ø €86.5k | 0 | 0 | ~€87k | 4 |
| Kununu | Abteilungsleiter:in (München) | Ø €120.1k | 0 | 0 | ~€120k | 5 |
| Glassdoor | Software Engineer | €27 to €32/h (≈€54k to €64k/yr at 38.5 h) | 0 | 0 | ≈€54k to €64k | 2 |
| Glassdoor | Systems Engineer | €26 to €37/h (≈€52k to €74k/yr) | 0 | 0 | ≈€52k to €74k | 4 |
| levels.fyi | n/a | n/a | n/a | n/a | n/a | 0 (company page 404) |

Notes:
- BR has its own house tariff (Haustarif) negotiated with ver.di, BJV (the Bavarian DJV) and unisono. The pay grid (Vergütungsgruppen) is not public and was not found in search; the grade for this role is **UNVERIFIED**.
- Agreed raises (July 2026 settlement): **+1.23% from Feb 2026, +2.5% from Apr 2027, up to +2% from Apr 2028**.
- Benefits from BR's benefits page: 31 days leave plus Urlaubsgeld, 38.5 h week, Familienzuschlag €164/month per child, employer-financed occupational pension (scheme details UNVERIFIED), canteen, childcare, free parking.
- Kununu reviewers note grading is tied to formal degrees: "Flexibler in der Eingruppierung auch in höhere Gehaltsgruppen ohne Studienabschluss" (Kununu, Jun 2026, Angestellte/r oder Arbeiter/in, IT, München). The posting requires a university degree, so degree-based placement in a higher grade should apply.

Munich reference (large, profitable corporations, Senior Software Engineer, same bracket as earlier reports): median ~€85k to €100k total, 75th percentile ~€110k to €120k, 90th percentile ~€130k+.

### Equity / Stock

None. A public-law broadcaster has no equity, RSUs, ESPP or bonus. The offsets are the occupational pension, Urlaubsgeld, family allowance and very high job security on a permanent contract. Note the ORH finding that the pension fund (Deckungsstock) has a gap of €512.8M; the pension promise is backed by the institution, not fully funded.

### Verdict

**BELOW.** Engineering data points cluster at €70k to €87k with no variable pay, which reaches at most the bottom of the Munich median band for senior engineers. The exact tariff grade for this role could not be verified and should be asked for during the process.

---

## Section 6: AI/ML & Tech Stack

### AI Strategy

- **Internal AI Platform (in build).** The open role belongs to the new "Fachgruppe KI und Datentechnologien" and is to design "das Knowledge Gateway unserer AI Platform", including retrieval, indexing, permission architecture, connectors and "API-, Event- und Tool-Anbindungen für Fachsysteme, Datenquellen und KI-Anwendungen", with MCP named as a plus. This is genuine applied platform engineering (RAG, data pipelines, lineage, integration contracts).
- **AI + Automation Lab and BR Data.** Interdisciplinary journalism-tech teams (BR Data founded 2015). Public GitHub work: `rag-tools-library` (Python RAG helper library published to PyPI as `brdata-rag-tools`), `brbuddy-api-service` (RAG chat for BR employees, built at a Microsoft hackathon in July 2024 on Azure), `second-opinion` (LLM hallucination checking for summaries), `schnittmaister-service` (Nov 2026: Gemini-based video cut proposals, FastAPI). Several repos are labelled proofs of concept.
- **Model use.** A product developer at the lab said in a KAS interview that Claude was the preferred model over GPT, with Gemini possibly next, and that AI use is "aktuell auf Standardvorgänge" (standard tasks such as shortening news items) limited. Any directional step must be agreed with the Personalrat, a KI-Ethik-Board and a KI-Beirat.
- **ARD context.** Press reports describe an ARD AI network led provisionally by BR and WDR. BR's Impressum states that AI tools are used in creating editorial content.

Assessment: real applied-AI and platform work exists, but it is small (one open role) and governance-heavy.

### Tech Stack

Derived from the current posting (primary), the `br-data` GitHub organisation (51 public repos), expired BR postings (.NET developer, AI agent developer, via devjobs.de) and germantechjobs tags for broadcast-engineering roles.

| Category | Technologies |
|---|---|
| **Primary language(s)** | Python (AI/data group; required "sehr gute Python-Kenntnisse"); SQL; TypeScript/JavaScript (news apps, frontends); .NET/C# (expired developer posting for central applications) |
| **AI/ML** | RAG, NLP (spaCy German models), generative AI; LLM APIs: Google Gemini (`google-genai`), OpenAI (older PoCs), Claude (per interview); FAISS, SQLite; MCP and agent interfaces |
| **Cloud** | Microsoft Azure (posting, 2024 hackathon); Databricks; also on-prem ("Cloud- oder lokale Plattformumgebungen") |
| **Infrastructure** | Kubernetes, containers, Git, CI/CD, logging and monitoring; Linux (Debian, RHEL) and Windows; Cisco Catalyst Center, Arista CloudVision; Media over IP (SMPTE ST 2110) |
| **Data** | Event streaming/messaging (posting: "Messaging- oder Event-Streaming-Technologien"), REST APIs, data modelling, metadata and lineage; MariaDB/MySQL (broadcast systems); Datasette, Elasticsearch (BR Data) |
| **Other** | FastAPI, Pydantic, httpx, uv, ruff, pyright, pytest (Nov 2026 repo); Datawrapper; ffmpeg |

**Summary:** Python-centric applied AI and data-integration work (RAG, knowledge gateway, event-driven pipelines, MCP connectors) on Azure / Databricks / Kubernetes, inside a broadcaster whose wider IT is polyglot (.NET, TypeScript, broadcast systems). Applied production engineering for internal users, not research.

---

## Section 7: Language

- The posting is **in German only** and requires "Sehr gute Deutsch- und Englischkenntnisse".
- The network administrator posting requires "Sehr gute Deutsch- und gute Englischkenntnisse"; all other postings and the careers site are German-only.
- All Kununu and nearly all Glassdoor reviews are in German. Stakeholders are German editorial and administrative departments, the Personalrat and German-language governance boards.

German is a primary working language, not an optional one.

**Verdict:** **FAIL**

---

## Section 8: Stability

### Financial Position

- **Income:** ~€1.02B Rundfunkbeitrag allocation in 2025, flat versus 2024 (+0.3%).
- **Result:** 2025 deficit of **€44.4M** (planned gap ~€70M; reduced by higher financial income and "sparsame Haushaltsführung"). €32.6M of it attributed to the blocked fee increase.
- **Reserves:** Finanzmittelbestand **€226.4M** at 31 Dec 2024 (thanks to locked surplus fee income).
- **ORH report (27 Oct 2026):** cumulative shortfall of **€106.4M by 31 Dec 2028** at the current fee; "durchgehend bilanziell überschuldet"; reserves "Ende 2028 vollständig aufgebraucht"; pension cover gap **€512.8M**, with income "in keinem der betrachteten Jahre" sufficient to fund pension payments. ORH asks for further staff reductions and leaner structures.
- **Fee outlook:** €18.36/month unchanged since 2021. KEF now recommends €18.64 from Jan 2027; BVerfG decision on the ARD/ZDF complaint pending as of the latest sources found.
- **Insolvency risk:** effectively nil. Public broadcasters have a constitutional funding guarantee; the practical consequence of the gap is further cuts, not closure.

### Financial Runway

BR is loss-making but not VC-backed, and its financing is statutory, so "runway" means how long reserves cover deficits before further cuts become unavoidable.

| Item | Figure | Source |
|---|---|---|
| Cash / reserves | €226.4M at 31 Dec 2024 | ORH report via epd, 27 Oct 2026 |
| 2025 deficit | €44.4M | BR to epd, via turi2, 20 Jul 2026 |
| Estimated reserves end 2025 | ~€182M (226.4 minus 44.4; estimate) | Derived |

| Scenario | Net burn | Cash at hand | Runway | Consequence by |
|---|---|---|---|---|
| Optimistic (fee to €18.64 from 2027, adds ~€15M/yr; 2025-level deficits shrink) | ~€25M/yr | ~€182M | 7 years | Cuts continue at today's pace |
| Base case (ORH projection) | ~€80M/yr average over 2025 to 2028 implied by reserves exhausted plus €106.4M uncovered | ~€182M | to end 2028 | Further structural cuts needed before 2028 |
| Stress (no fee increase, pension cover gap starts to bite) | >€80M/yr | ~€182M | ~2 years | Accelerated staff reduction 2027 to 2028 |

The base case is the auditor's own view. All scenarios point to continued headcount reduction through attrition, not to job loss for permanent staff.

### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| Mar 2016 | Plan to cut posts by 2025 | ~450 posts | Eurofound restructuring record; via attrition |
| Jan 2020 | Tariff deal after strikes | n/a | BR committed to no betriebsbedingte Kündigungen until end of 2024 |
| Oct 2024 | 2025 savings programme | 3% of every directorate's budget, material budgets frozen | No general hiring freeze; "Zielbilder" for each department's future headcount |
| 2025 | Programmdirektion Information | 50 FTE (~3% of the directorate) | "Sozialverträglich": vacated posts not refilled; no compulsory redundancies |
| 2025 to 2026 | ARD reform channel closures | n/a | Puls (youth station), BR Schlager, BR Verkehr, BR24live closed or being closed |
| Oct 2026 | ORH demands further Stellenabbau | Not quantified | Pressure for more cuts through 2028 |

No compulsory dismissals of permanent staff found. Reductions run through non-replacement and fixed-term contracts not being renewed.

### Works Council & Collective Agreement

BR is a public-law body, so it has a **Personalrat** under the Bavarian Personnel Representation Act (BayPVG), not a Betriebsrat under the BetrVG. Art. 84 BayPVG contains special rules for BR (the Dienststelle is BR itself, represented by the Intendant). The Personalrat has participation rights in dismissals, working-time rules and the introduction of technical monitoring comparable to a works council.

| Item | Finding | Evidence |
|---|---|---|
| Works council (Personalrat) | **YES** (local Personalrat München and a Gesamtpersonalrat) | Art. 84 BayPVG; VG München decisions on BR Personalrat elections (2022, 2023); KAS interview: AI steps "müssen mit dem Personalrat abgesprochen werden"; Kununu: "Der Personalrat behindert leider viele notwendige Änderungen." (Jun 2026, Führungskraft, IT, München) |
| Collective agreement | **Haustarif** (company agreement) with ver.di, BJV and unisono | turi2, 22 Jul 2026: raises of 1.23% / 2.5% / up to 2% (2026 to 2028); posting: "Faire tarifliche Bezahlung"; Kununu: "tarifgebunden" (Feb 2026) |
| European works council | N/A | Single-country public body |
| Conflict signals | Strikes with programme outages in the 2019/2020 round; VG München annulled the 2021 Personalrat München election and the Gesamtpersonalrat election (procedural breaches) and both were re-held. No union-busting reports found | turi2, 30 Jan 2020; gesetze-bayern.de court decisions |

**Verdict:** **PASS.** A strong Personalrat plus a house tariff: cuts are negotiated and social, not silent. The flip side, mentioned by an IT manager, is slower change.

---

## Section 9: Regulated Industry

Broadcasting is regulated by the Medienstaatsvertrag and the Bayerisches Rundfunkgesetz, with oversight by the Rundfunkrat, Verwaltungsrat and the Bavarian Court of Audit. Engineering-relevant obligations are data protection (BR has its own data-protection supervision as a broadcaster), public procurement rules for purchases, IT security for critical broadcast infrastructure, and internal AI governance (KI-Ethik-Board, KI-Beirat, Personalrat consent). There are no safety-critical certification regimes (no ISO 26262 / EN 50128 / FDA style safety cases).

**Verdict:** **PASS** (low engineering regulatory burden; governance and approval overhead for AI rollouts is noticeable)

---

## Section 10: On-Call

The posting does not mention Rufbereitschaft or on-call. However, the role includes "Verantwortung für die Sicherstellung eines stabilen Betriebs" from idea "bis zum stabilen Betrieb", and BR runs 24/7 broadcast operations with shift models in some departments ("Gleitzeit- oder Schichtmodell, je nach Arbeitsplatz"). An internal AI/knowledge platform used by editorial staff is less likely to need night cover than playout systems, but this is not stated. If on-call exists, it would be governed by a Personalrat-agreed arrangement with recorded time.

**Verdict:** **UNVERIFIED** (ask explicitly)

---

## Section 11: Interview Process

Based on Glassdoor (glassdoor.de, via CDP).

| Metric | Value |
|---|---|
| Difficulty | ~2.6 / 5 (Glassdoor search summary; interview page: "Durchschnittlich") |
| Positive experience | 80% (5 interviews) |
| Average duration | 5 days (Werkstudent) to 3 weeks (Regisseur); 2 data points |
| Rounds | 2 to 3 |

Typical steps reported: HR phone call, a ~20-minute call with the department head, then a video interview with several team members (4 interviewers in one Teams call). Questions are motivational and fit-based ("Wieso habe ich meine Bewerbung ... geschickt?", "Was ist deine Motivation für diesen Job?"). No technical interview reports exist for engineering roles, and none of the 5 reports is for a software role. Nothing suggests LeetCode-style testing; expect an experience- and stakeholder-focused conversation, possibly with a panel including HR and the equal-opportunity or Personalrat side, as is common in German public-sector hiring. All reported interviews were in German except one Werkstudent report written in English.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | **FAIL.** Public broadcaster; IT and AI are support functions. One software role among 38 postings |
| Not consulting | **PASS.** Internal platform team, no client billing |
| Profitable | **FAIL.** Public-law body; 2025 deficit €44.4M; ORH: balance-sheet overindebted, reserves gone by end 2028 |
| Employee count | ~3,500 permanent, ~5,000 with freelancers |
| English-speaking | **FAIL.** German-only posting, "sehr gute Deutschkenntnisse" required |
| Local entity + engineering contracts | **PASS.** Direct, permanent (unbefristet), tariff-bound employment with BR (AöR) |
| Location / work model | Funkhaus (Rundfunkplatz 1, next to Hauptbahnhof) and/or Freimann campus (Floriansmühlstraße 60, U6 Freimann ~1 km, buses 188/231 ~660 m); hybrid, extent depends on role |
| Glassdoor | 3.6 global (42 reviews), 3.8 Munich (27); WLB 4.0; Career 2.6; directional only |
| Kununu | 3.6 (393 employee reviews), 70% recommend; **IT department 4.0, 90% (33 reviews)**; not a Top Company |
| Salary | **BELOW.** House tariff, no band published; engineering data points €70k to €87k; no bonus or equity |
| AI/ML content | Real but small: internal AI Platform Knowledge Gateway, RAG, MCP connectors, event pipelines |
| Computer-language/Tech-stack | Python-centric for the AI/data group; Azure, Databricks, Kubernetes; wider IT polyglot (.NET, TS) |
| No on-call | **UNVERIFIED.** Not mentioned; role includes operational responsibility |
| WLB / Stability | Very good WLB in IT (time recording, overtime compensated); institution permanent, but austerity and ongoing headcount reduction |
| Works council / collective agreement | **PASS.** Personalrat (BayPVG) plus Haustarif with ver.di, BJV, unisono |
| Regulated industry | **PASS.** Media law, data protection, AI governance boards |
| Review themes | Bureaucracy, slow decisions, degree-bound grading, communication; leadership complaints concentrated outside IT |
| Austerity exposure | **CAUTION.** ORH wants further cuts; channel closures; non-IT reviewers report chains of fixed-term contracts |

---

## Section 13: Verdict

**Recommendation: Monitor (exclude under the standard criteria).**

**Strengths:** For its IT staff, BR looks like a good employer: the IT slice of Kununu scores 4.0 with 90% recommendation, reviewers praise work-life balance, recorded and compensated overtime, family support and "viel Innovation in der Technik". The open role is a real, permanent platform-engineering job (knowledge gateway, retrieval, permissions, connectors, MCP, event-driven pipelines) in a newly formed AI and data group, with a Python-centric stack on Azure / Databricks / Kubernetes. A Personalrat and a house tariff protect against silent firings, and job security on a permanent contract is about as high as it gets in Germany.

**Hard blockers:**
1. **German-first working language.** The posting is German-only and requires very good German alongside English; stakeholders are German editorial, administrative and governance bodies. This fails the English-first criterion outright.
2. **Not profitable, and structurally in deficit.** €44.4M loss in 2025, reserves of €226.4M (end 2024) projected by the Court of Audit to be exhausted by end 2028 with a further €106.4M uncovered, and a €512.8M pension cover gap.
3. **Not software-centric.** One software role among 38 postings; IT is a support function in a media organisation.
4. **Compensation below the Munich senior bracket.** The house tariff has no published grid; engineering data points of €70k to €87k (Kununu Ingenieur Ø €87.0k, Systemingenieur Ø €86.5k, broadcast-engineer postings €70k to €80k) sit at or below the bottom of the €85k to €100k median band, with no bonus or equity and raises of only 1.23% / 2.5% / up to 2% for 2026 to 2028.

**Secondary concerns:** Austerity is ongoing and the auditor wants more cuts; reductions run through non-replacement, which tends to increase workload and slow projects. AI adoption needs approval from the Personalrat, an ethics board and an advisory board, which slows delivery. Career progression is the weakest-rated theme on both platforms and is tied to tariff grades and formal degrees. On-call for the operational part of the role is unknown.

**Recommendation:** Under the standard criteria this is an exclude, driven mainly by language and pay rather than by culture. If the language requirement is acceptable in this case and the lower pay is weighed against permanent tariff employment, pension and job security, the role itself is a credible technical fit and worth pursuing; in that case verify during the process: (1) the exact Vergütungsgruppe and step and whether placement above entry level is possible, (2) the home-office share for this team, (3) whether the "stabiler Betrieb" responsibility includes Rufbereitschaft, (4) whether the AI Platform is funded beyond the current austerity period, and (5) the working language inside the Fachgruppe KI und Datentechnologien.

---

## Sources

- [BR job posting: Data / Integration Platform Engineer (w/m/d)](https://jobs.br.de/Vacancies/1424/Description/1)
- [BR job posting: Netzwerkadministrator (w/m/d)](https://jobs.br.de/Vacancies/1425/Description/1)
- [BR job posting: Referent Strategie, Prozessmanagement und Service-Governance](https://jobs.br.de/Vacancies/1427/Description/1)
- [BR job posting: Ausbildung Fachinformatiker Anwendungsentwicklung](https://jobs.br.de/Vacancies/598/Description/1)
- [BR jobs listing (38 postings, 10 Nov 2026)](https://jobs.br.de/Jobs/All)
- [BR careers: benefits overview](https://www.br.de/extra/karriere/br-als-arbeitgeber/alle-br-benefits-100.html)
- [BR careers home](https://www.br.de/extra/karriere/index.html)
- [BR Impressum](https://www.br.de/unternehmen/service/impressum/index.html)
- [Kununu: Bayerischer Rundfunk](https://www.kununu.com/de/bayerischer-rundfunk2)
- [Kununu: IT-department reviews](https://www.kununu.com/de/bayerischer-rundfunk2/kommentare?department=it)
- [Kununu: low-score reviews](https://www.kununu.com/de/bayerischer-rundfunk2/kommentare?score=subpar)
- [Kununu: salaries](https://www.kununu.com/de/bayerischer-rundfunk2/gehalt)
- [Glassdoor: overview](https://www.glassdoor.de/%C3%9Cberblick/Arbeit-bei-Bayerischer-Rundfunk-EI_IE934721.11,31.htm)
- [Glassdoor: reviews (global)](https://www.glassdoor.de/Bewertungen/Bayerischer-Rundfunk-Bewertungen-E934721.htm)
- [Glassdoor: reviews (Munich)](https://www.glassdoor.de/Bewertungen/Bayerischer-Rundfunk-M%C3%BCnchen-Bewertungen-EI_IE934721.0,20_IL.21,28_IC4990924.htm)
- [Glassdoor: reviews (Germany)](https://www.glassdoor.de/Bewertungen/Bayerischer-Rundfunk-Deutschland-Bewertungen-EI_IE934721.0,20_IL.21,32_IN96.htm)
- [Glassdoor: reviews (Software Engineer)](https://www.glassdoor.de/Bewertungen/Bayerischer-Rundfunk-Software-Engineer-Bewertungen-EI_IE934721.0,20_KO21,38.htm)
- [Glassdoor: salaries](https://www.glassdoor.de/Gehalt/Bayerischer-Rundfunk-Geh%C3%A4lter-E934721.htm)
- [Glassdoor: interviews](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/Bayerischer-Rundfunk-Fragen-im-Vorstellungsgespr%C3%A4ch-E934721.htm)
- [Glassdoor: company search](https://www.glassdoor.com/Search/results.htm?keyword=Bayerischer%20Rundfunk)
- [levels.fyi: Bayerischer Rundfunk (404)](https://www.levels.fyi/companies/bayerischer-rundfunk/salaries)
- [Teamblind: Bayerischer Rundfunk (not found)](https://www.teamblind.com/company/Bayerischer-Rundfunk)
- [devjobsscanner: Bayerischer Rundfunk postings with salary ranges](https://www.devjobsscanner.com/company/bayerischer-rundfunk/)
- [devjobs.de: BR .NET software developer (expired)](https://en.devjobs.de/job/93ce7968196847460650eab3de3d367b)
- [devjobs.de: BR AI agent developer (expired)](https://en.devjobs.de/job/dd38ecc899fb79ee7fdaec958363fbd9)
- [GitHub: br-data organisation](https://github.com/br-data)
- [GitHub: br-data/schnittmaister-service](https://github.com/br-data/schnittmaister-service)
- [GitHub: br-data/rag-tools-library](https://github.com/br-data/rag-tools-library)
- [GitHub: br-data/brbuddy-api-service](https://github.com/br-data/brbuddy-api-service)
- [GitHub: br-data/second-opinion-summarisation](https://github.com/br-data/second-opinion-summarisation)
- [KAS interview: ChatGPT im Journalismus (BR AI + Automation Lab)](https://www.kas.de/de/interview/detail/-/content/chatgpt-im-journalismus)
- [AI + Automation Lab: Blackbox Reporting brochure](https://www.film-tv-video.de/wp-content/uploads/2023/08/AI_Automation_Lab_Blackbox_Reporting.pdf)
- [epd/Sonntagsblatt: Rechnungshof fordert weiteren Stellenabbau beim BR (27 Oct 2026)](https://www.sonntagsblatt.de/artikel/epd/rechnungshof-fordert-weiteren-stellenabbau-beim-bayerischen-rundfunk)
- [epd/Sonntagsblatt: BR muss 2025 Finanzloch von 70 Millionen Euro schließen (8 Oct 2024)](https://www.sonntagsblatt.de/artikel/epd/br-muss-2025-finanzloch-von-70-millionen-euro-schliessen)
- [epd/Sonntagsblatt: BR rechnet 2025 mit einem Defizit von 70 Millionen Euro](https://www.sonntagsblatt.de/artikel/epd/br-rechnet-2025-mit-einem-defizit-von-70-millionen-euro)
- [turi2: BR weist Defizit aus (20 Jul 2026)](https://www.turi2.de/?p=4114052)
- [turi2: BR und Gewerkschaften erzielen Tarifeinigung (22 Jul 2026)](https://www.turi2.de/aktuell/der-br-und-verdi-erzielen-tarifeinigung/)
- [turi2: Nach Streiks und Sendeausfällen BR gelingt eine Tarifeinigung (30 Jan 2020)](https://www.turi2.de/aktuell/nach-streiks-und-sendeausfaellen-br-gelingt-eine-tarifeinigung/)
- [turi2: 50 Stellen in der Programmdirektion Information](https://www.turi2.de/?p=4069883)
- [turi2: Wirtschaftsplan 2025](https://www.turi2.de/aktuell/wirtschaftsplan-2025-br-spart-sich-eigenen-teletext-und-einige-tv-formate/)
- [Horizont: BR will Mediathek und Netzangebote stärken](https://www.horizont.net/medien/nachrichten/umstrukturierung-br-will-mediathek-und-netzangebote-staerken--kuerzungen-in-tv-und-radio-204754)
- [WinFuture: ARD und ZDF schalten Sender ab](https://winfuture.de/news,159032.html)
- [Beitragsservice: Jahresbericht 2025 presentation](https://www.rundfunkbeitrag.de/pxy/assets/25987015aead9669fbb723a08671637420753e2c/02_Pr%C3%A4sentation_Jahresbericht%202025.pdf)
- [ORH Bayern: Weiteres Sparen dringend nötig (earlier report)](https://www.orh.bayern.de/mam/aktuelles/medieninformationen/aktuell/22-09-23_weiteres_sparen_dringend_n%C3%B6tig.pdf)
- [Eurofound restructuring event: BR](https://restructuringeventsprod.azurewebsites.net/restructuring-events/detail/86671)
- [LTO: BVerfG verhandelt im Juni zum Rundfunkbeitrag](https://www.lto.de/recht/nachrichten/n/bverfg-verhandelt-nun-doch-im-juni-zum-rundfunkbeitrag?r=rss)
- [LTO: Neue KEF-Empfehlung zum Rundfunkbeitrag](https://www.lto.de/recht/hintergruende/h/neue-empfehlung-kef-kommission-rundfunkbeitrag)
- [Art. 84 BayPVG (Bayerischer Rundfunk)](https://gesetze.legal/bayern/baypvg/84)
- [VG München, 10.10.2023, M 20 P 23.1359 (Gesamtpersonalrat election)](https://www.gesetze-bayern.de/Content/Document/Y-300-Z-BECKRS-B-2023-N-30433?hl=true)
- [VG München, 26.07.2022, M 20 P 21.4005 (Personalrat election)](https://www.gesetze-bayern.de/Content/Rtf/Y-300-Z-BECKRS-B-2022-N-19315?all=False)
- [Wageindicator: new agreements for broadcasting corporations (Sep 2026)](https://wageindicator.org/ai/work/collective-bargaining-agreement/updates/2026/germany-new-agreements-for-broadcasting-corporations-september-30-2026/)
- [Wikipedia: Bayerischer Rundfunk](https://en.wikipedia.org/wiki/Bayerischer_Rundfunk)
- [OSM Nominatim](https://nominatim.openstreetmap.org/) and [Overpass API](https://overpass-api.de/)

### Retrieval method notes

- **Chromium over CDP:** Kununu (all pages; curl returned no data for the guessed slugs), Glassdoor (all pages and filters; ratings read from embedded JSON), BR jobs portal and postings, BR careers and benefits pages, Teamblind, levels.fyi, devjobs.de, devjobsscanner.
- **curl:** BR Impressum, turi2 and Sonntagsblatt/epd articles, GitHub API and raw READMEs, Nominatim. Overpass: the main endpoint returned "server at capacity" several times; results came from retries with backoff (the private.coffee and kumi.systems mirrors also failed).
- **Not retrieved:** Bayerisches Rundfunkgesetz text on gesetze-bayern.de (no text via curl or CDP); BR Haustarif pay grid (not public); BR Geschäftsbericht 2025 (not found).
- **Job postings were used only as stack and policy evidence.**
