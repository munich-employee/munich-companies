# ottonova - Full Research Report

_Researched: 2026-11-09_

> **Critical Disqualifiers**
> 1. **Python is not the main engineering language.** The core platform is PHP 8 / Symfony microservices plus a TypeScript layer (Angular frontends, NestJS backends), with Go, Kotlin and Swift around it. Python appears only in the small Data & Analytics / AI unit (an AI team of one lead, one PM and two engineers, per the 2026 AI Engineer posting). **FAIL** against the Python-central criterion.
> 2. **The only Python-adjacent engineering work requires German.** The 2026 Senior AI Engineer posting (the only engineering vacancy on the board) lists "Fluent in German (at least B2) and English". Core software engineering postings are English-first, but those are PHP/TypeScript roles. **FAIL / CONDITIONAL**
> 3. **Not profitable, and stability depends on rolling shareholder top-ups.** Group net loss **€16.3M in FY2025**, accumulated balance-sheet loss **€186.0M**, Solvency II group ratio **181%** (eligible own funds €19.0M vs SCR €10.5M, i.e. ~€8.5M headroom, about half a year of losses). 2025 required €10M of fresh equity plus a €12.7M Debeka loan-to-equity conversion. Break-even is still described as "in naher Zukunft", nine years after launch. **FAIL** against "stable business strategy, looking to commit long-term".
>
> The full report follows for completeness.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 2015 (holding registered 2016; insurance licence and market launch 2017), ~10 years |
| Employees | **192 in Germany** (GPTW profile); "~200 employees" (Senior AI Engineer posting, 2026); Kununu says 100-200. Offices in Munich (HQ) and Cologne |
| Revenue (FY2025) | **Gross written premiums €53.98M**, net premiums €48.93M (SFCR group report 2025) |
| Profitability | Group net loss **-€16.3M** (FY2025); underwriting result -€0.38M; accumulated balance-sheet loss -€186.0M - **FAIL** |
| Ownership | Private, VC- and strategic-backed. Shareholders include Debeka (Germany's largest private health insurer, ~10% stake since 2017, lead in the 2019 round), Holtzbrinck Ventures, Vorwerk Ventures, btov, Earlybird, HV Capital. Supervisory board chaired by Karl-Heinz Naumann |
| Software-centric | No. A BaFin-regulated private health insurer (PKV) with an in-house digital platform. Revenue is insurance premiums, not software - **BORDERLINE** |

### Key People

- **Dr. Bernhard Brühl**, CEO since 1 January 2023 (mathematician and actuary; COO from 2018). Succeeded founder Roman Rittweger, who moved to the supervisory board at end of 2022.
- **Martin Betzwieser**, CFO.
- **Christopher Koker**, Chief Marketing & Sales Officer.
- **No CTO on the management board** since the IT board member (Peter Bauer) left at end of 2022 / start of 2023; the board shrank from six to four, then three members after the Chief Marketing & Sales Officer Jesko Kannenberg left in June 2024 (seat not refilled).
- Engineering entity ottonova Technology Services GmbH is run by managing directors Dr. Stefan Strobl, Christopher Koker and Philip Lönneker.

### Funding History

| Date | Round | Amount | Investors | Valuation |
|---|---|---|---|---|
| 2016 | Seed / A | ~€20M | Debeka, Holtzbrinck Ventures, Vorwerk Ventures, Tengelmann Ventures, btov, STS Ventures | n/a |
| June 2017 | Extension | €10M | Debeka (~10% stake) | n/a |
| Nov 2019 | Series E (reported) | €60M | Debeka (lead), Holtzbrinck Ventures, btov, Vorwerk Ventures | n/a |
| Sep 2022 | Series F | ~€34M | existing investors incl. Earlybird, HV Capital, btov; billed as "the last financing round before break-even" | n/a |
| 2025 | Capital measures | €6.5M (two capital strengthenings) + €3.5M (extension of earlier round) + **€12.69M Debeka subordinated loan converted to equity** | existing shareholders | n/a |
| **Total** | | **~€160M+ equity** (Munich Startup cites ~€159M through 2022) | | undisclosed |

Remaining debt: subordinated loan from Debeka Krankenversicherungsverein a.G. of **€11.14M** (prior year €22.84M), maturing 2030.

### Business Model

ottonova is a full-licence private health insurer (Krankheitskostenvollversicherung, Pflegepflichtversicherung, Beihilfe, supplementary dental/hospital, student and expat tariffs, company health insurance "CrewCare"). It differentiates through a mobile app (claims submission, doctor video calls, concierge chat, appointment booking) and an all-digital back office. The product engineering is internal, building systems used by the company's own claims, underwriting and customer-service staff and by its customers. The SFCR notes that the 2025 loss is "hauptsächlich auf den Aufwand im Zusammenhang mit dem Ausbau des Versicherungsbestandes zurückzuführen und daher beabsichtigt".

### Software-Centric Assessment

ottonova is an insurer that builds its own software, not a software company:

- **Revenue:** 100% insurance premiums. "Das Versicherungsgeschäft wird ausschließlich durch die ottonova Krankenversicherung AG generiert" (SFCR 2025).
- **Engineering scale:** "five software-engineering teams" plus a Data & Analytics unit with a small AI team (JavaScript and PHP postings 2025-2026). With ~192 staff, engineering is a substantial minority; claims handling, customer support, underwriting, actuarial and sales make up the rest (the open-vacancy list on 2026-11-09 is 7 roles, of which only one is engineering).
- **Positive:** genuine in-house product engineering (microservices, DDD/CQRS, event sourcing, Kubernetes on AWS, own mobile apps, public tech radar and tech blog). Not outsourced.
- **Restructuring 2026:** from 1 January 2026 ottonova services GmbH was renamed **ottonova Technology Services GmbH** and now performs **only IT**; claims, customer service, marketing and B2B sales moved into the insurer AG. Engineering is therefore isolated in a dedicated tech subsidiary.

Verdict: **BORDERLINE**. A credible in-house engineering organisation, but in a regulated insurer whose product is the insurance policy.

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **ottonova Technology Services GmbH** (engineering employer; formerly ottonova services GmbH, renamed 01.01.2026) | HRB 227447, Amtsgericht München; share capital €25,000; profit-and-loss transfer agreement with ottonova Holding AG | Ottostraße 4, 80333 München | "Planung, Entwicklung und Betrieb digitaler Produkte und Dienstleistungen jeglicher Art sowie Übernahme von Vertriebs- und Verwaltungstätigkeit für Finanzdienstleistungsunternehmen im In- und Ausland." |
| **ottonova Holding AG** (group parent, insurance holding under § 7 Nr. 31 VAG since 28.07.2025) | HRB 223275, Amtsgericht München; share capital €570,926 | Ottostraße 4, 80333 München | Management of a group of private insurance, intermediary, financial-services and similar companies; holding of participations; services for third parties |
| **ottonova Krankenversicherung AG** (BaFin-licensed insurer) | HRB 227378, Amtsgericht München | Ottostraße 4, 80333 München | Private health insurance |
| on Beratungs- und Vertriebs-GmbH | Munich | Ottostraße 4, 80333 München | B2C sales |
| KVpro.de GmbH | Freiburg | Bismarckallee 2a, 79098 Freiburg | PKV comparison portal |
| ottonova AG | Munich | Ottostraße 4 | Reserved for a future life-insurance line (no operations) |

**Verification.** The ottonova.de Impressum names all three main entities with the HRB numbers above, and NorthData confirms HRB 227447 and its corporate purpose. The engineering subsidiary's purpose explicitly covers "Planung, Entwicklung und Betrieb digitaler Produkte", which is engineering, not a sales shell. Per the SFCR, 60% of permanent employees sat in this entity at 31.12.2025, and the 2026 AI Engineer posting is issued by "ottonova Technology Services GmbH". Postings are "Vollzeit, Festanstellung" in Munich, i.e. direct German employment, no PEO/EOR. Note the entity's history of running sales, claims and customer service until end of 2025 explains the "Vertriebs- und Verwaltungstätigkeit" clause.

**Verdict:** **PASS**

---

## Section 3: Office Location

- **Office address:** Ottostraße 4, 80333 München, district **Maxvorstadt** (Nominatim: "4, Ottostraße, Maxvorstadt, München, Bayern, 80333"), next to Lenbachplatz between Stachus and Hauptbahnhof. Confirmed by the Impressum and the SFCR group structure table. A second office exists in **Cologne** (careers page: "An unseren Standorten München und Köln").
- **Nearest public transport** (Overpass, 700 m radius):

  | Stop | Type | Distance |
  |---|---|---|
  | Lenbachplatz | Tram stop | 72 m |
  | Karlsplatz (Stachus) | U-Bahn station (U4/U5), S-Bahn trunk line | 114 m |
  | Ottostraße | Tram stop | 123 m |
  | Karlsplatz (Stachus) Nord | Tram stop | 273 m |
  | Hauptbahnhof | U-Bahn / S-Bahn / regional rail, trams | ~500 m |
  | Königsplatz | U-Bahn station (U2/U8) | 535 m |
  | Odeonsplatz | U-Bahn station (U3/U4/U5/U6) | 659 m |

  Overpass returned the stop nodes; the route-relation query timed out, so line numbers above come from the MVV network map rather than OSM.
- **Work model:** Hybrid ("ottonova Balance - Mobile working" in postings). Kununu reviewers describe it as up to 60% remote: "ottonova balance ist toll, jeder kann bis zu 60% von zu Hause arbeiten." (Kununu, Mar 2025, Angestellte/r oder Arbeiter/in, Bereich: Sonstige, current) and "Home Office ist hier zum großen Teil problemlos möglich, verbunden jedoch mit normal 2 Bürotagen in der Woche." (Kununu, Sep 2023, Angestellte/r oder Arbeiter/in, Bereich: Sonstige, ottonova services GmbH, current). So roughly **2 office days per week** in Munich. Not a remote company; postings are Munich-only.

---

## Section 4: Reviews

**GPTW: YES, strong.** ottonova Gruppe is **Great Place to Work certified (Oct 2025 - Oct 2026)** and has won **Beste Arbeitgeber in Bayern** (2021, 2022, 2023, 2024, 2025, 2026), **Beste Arbeitgeber ITK** (2021-2026) and **Deutschlands Beste Arbeitgeber 2021**. The GPTW profile reports 192 employees in Germany; the headline survey statements show 97%, 94%, 93%, 92%, 92% agreement (counters rendered without labels in the browser). Retrieved via Chromium/CDP.

#### Glassdoor

Glassdoor coverage is very thin: the overview page gives 3.8 "based on 16 reviews", the search result says 18, and the ratings block is computed from 8. All reviews with a location are Munich, so the Germany and Munich filters are identical to Global. Retrieved via Chromium/CDP (glassdoor.de).

| Metric | Global | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | 3.8 (8-18 reviews) | 3.8 (same set) | 3.8 (same set) | ~3.3 (3 engineering reviews: 4.0, 1.0, 5.0) |
| **WLB** | 3.7 | 3.7 | 3.7 | n/a |
| **Culture & Values** | 4.0 | 4.0 | 4.0 | n/a |
| **Comp & Benefits** | 3.3 | 3.3 | 3.3 | n/a |
| **Career Opportunities** | 3.6 | 3.6 | 3.6 | n/a |
| **Senior Management** | 3.0 | 3.0 | 3.0 | n/a |
| **Diversity & Inclusion** | 4.3 | 4.3 | 4.3 | n/a |
| **% Recommend** | 65% | 65% | 65% | n/a |
| **CEO Approval** | not displayed | not displayed | not displayed | n/a |
| **Business Outlook** | 66% positive | 66% positive | 66% positive | n/a |

All filters fall far below 20 reviews: **directional only**. Glassdoor is not a useful signal for this German-language employer; Kununu and GPTW carry the weight.

#### Kununu

Slug `ottonova`. curl returned HTTP 405; data retrieved via Chromium/CDP from the page's embedded `__NEXT_DATA__`.

- **Overall score:** **4.2 / 5.0** (industry "Versicherung" average 4.0)
- **Recommendation rate (Weiterempfehlung, last 2 years):** **91%** (all-time: 80%)
- **Total reviews:** 216 (employee reviews: 140; the rest are applicant reviews)
- **Factor scores:** Work-Life-Balance 4.4, Arbeitsatmosphäre 4.4, Kollegenzusammenhalt 4.4, Arbeitsbedingungen 4.4, Kommunikation 4.1, Vorgesetztenverhalten 4.1, Karriere/Weiterbildung 4.0, **Gehalt/Sozialleistungen 3.9** (lowest)
- **Kununu Top Company:** **YES**, 2022, 2023, 2024, 2025, 2026 and 2027 (`topCompanyYears` on profile; `isTopCompanyPaid: false`)
- Department mix of the 63 reviews pulled (all IT reviews plus all reviews scored below 4): IT 23, Sonstige 13, Administration 4, Sales 4, Management 3, Product 3. The HR team answers nearly every review (99 responses).

#### Blind / Teamblind

No company page exists (`teamblind.com/company/ottonova/reviews` returns "Page not found"). **UNKNOWN**: no Blind coverage, as expected for a ~200-person German insurer.

#### Review Themes (2022-2026)

**Positives:**

- **Atmosphere and team cohesion**, consistently across years and departments: "Tolles Team, Teamspirit, Change-Willen, erfolgreiches Wachstum, tolle Büros" (Kununu, Mar 2026, Führungskraft / Management, Bereich: Management, ottonova Krankenversicherung AG, current). "The IT team is collaborative and supportive, and knowledge sharing is encouraged" (Glassdoor, Sep 2025, IT engineer, current employee, more than 1 year, Munich).
- **Flexible hours and hybrid work**: "Flexible Arbeitszeiten, keine oder nur selten Überstunden, die ausgeglichen werden können, Homeoffice" (Kununu, Nov 2024, Angestellte/r oder Arbeiter/in, Bereich: IT, ottonova services GmbH, current).
- **Modern engineering environment**: "From a tech perspective, the environment is modern and dynamic. We work with up-to-date tools and technologies, and there's plenty of room to suggest improvements" (Glassdoor, Sep 2025, IT engineer, current employee, more than 1 year, Munich). The 2023 Software engineer who rated 1.0 still lists "Tech Stack" as a pro.
- **Recent trend is strongly positive**: every 2025-2026 Kununu review except two (Apr 2025, Apr 2026) recommends the employer; the last-2-years recommendation rate is 91% versus 80% all-time, and GPTW scores sit in the 90s.

**Negatives:**

- **Pay and pay rises** (multi-year, multiple platforms): "Gehaltsanpassungen über voraussichtlich 4 Jahre hinweg nicht einzuplanen ist einfach nicht tragbar." (Kununu, Sep 2024, Angestellte/r oder Arbeiter/in, Bereich: Sonstige, ottonova services GmbH, current). "kein Budget für Gehaltserhöhungen" (Glassdoor, Dec 2023, Software engineer, current employee, more than 3 years, Munich). "Erhöhungen gibts kaum" (Kununu, Apr 2025, Angestellte/r oder Arbeiter/in, Bereich: Forschung/Entwicklung, ottonova services GmbH, current). No Urlaubs-/Weihnachtsgeld (Kununu, Nov 2024, IT). Salary is the lowest Kununu factor (3.9) and the lowest Glassdoor category after management (3.3).
- **No works council / no collective agreement**: "The employer does not pay according to the collective agreement. People would rather be laid off and replaced at high cost rather than keep the old employees. There is no works council." (Kununu, Dec 2023, Angestellte/r oder Arbeiter/in, Bereich: IT, ottonova AG, current). "kein Betriebstat [sic] - Mitarbeiter werden klein gehalten - Zukunft des Unternehmens ungewiss - Finanzierung unklar ... mushroom management" (Glassdoor, Dec 2023, Software engineer, current employee, more than 3 years, Munich).
- **Funding uncertainty felt by staff**: the 2023 Glassdoor engineer above ("Finanzierung unklar"); "Start Up mit total unterirdischen IT Prozessen, läuft auf Verlust" (Kununu, Jan 2022, Angestellte/r oder Arbeiter/in, Bereich: Vertrieb/Verkauf, ottonova Holding AG, title only).
- **Signed contracts cancelled before start (mid-2022)**: three separate reviewers describe being told ~3 weeks before their start date that the contract would be terminated "auf Grund veränderter wirtschaftlicher und betrieblicher Lage" (Kununu, Jul 2022, position not given, ottonova Holding AG, former; Kununu, Jul 2022, position not given, ottonova Holding AG, former; Kununu, Jun 2022, Angestellte/r oder Arbeiter/in, Bereich: Sonstige, ottonova Holding AG, former). This coincides with the Series F round.
- **Uneven line management, fluctuation**: "Fluktuation recht hoch ... Arbeitsatmosphäre schlecht" and "respektloser Ton, wenig wertschätzend" (Kununu, Apr 2026, Angestellte/r oder Arbeiter/in, Bereich: Finanzen/Controlling, ottonova Holding AG, former). "There is to much pressure, To much workload" (Kununu, Nov 2024, Angestellte/r oder Arbeiter/in, Bereich: IT, ottonova Krankenversicherung AG, former). "Too pressure from team leads" (Kununu, Jan 2024, Angestellte/r oder Arbeiter/in, Bereich: IT, ottonova, current).
- **Hard-red-flag overlap:** no works council (structural), salary freezes, and one older internal-tracking complaint (2022, see below). No evidence of on-call, 24/7 expectation, layoffs or unpaid overtime as a pattern in 2024-2026.

#### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | Isolated. "respektloser Ton, wenig wertschätzend" (Kununu, Apr 2026, Angestellte/r oder Arbeiter/in, Finanzen/Controlling, former); "Vorgesetzte mit Napoleonkomplex" (Kununu, Jan 2022, Vertrieb/Verkauf, title only). Counterweight: Kununu leadership 4.1, GPTW-certified with 90%+ agreement. Localised, not systemic. |
| 24/7 Work Expectation | Not found. One 2023 sales reviewer lists "ständige Erreichbarkeit" under communication as a positive (reachability of colleagues), not a demand. |
| Internal Surveillance | Historic, single source: "Es wird getrackt wo man nur kann ... wenn einem Mitarbeiter dieses tracking als Instrumente des Teambuildings ... verkauft werden" (Kununu, Feb 2022, Angestellte/r oder Arbeiter/in, Bereich: Sonstige, ottonova services GmbH, former). Context suggests customer-service ticket/time tracking. Nothing since 2022 and nothing from engineers. |
| Fear-driven Management | Weak signal: "Anstatt Mitarbeiter zu fördern wird einem klar gesagt, dass man gehen darf!" (Kununu, May 2023, Angestellte/r oder Arbeiter/in, Bereich: Produktmanagement, ottonova services GmbH, current). |
| Communication Breakdown | Recurring but mild: "non-transparent kommunication in the company all hands update" (Kununu, Nov 2024, IT, ottonova Krankenversicherung AG, former); "Wichtiges wird einem vorenthalten" (Kununu, Apr 2025, Forschung/Entwicklung, current); "mushroom management" (Glassdoor, Dec 2023, Software engineer). |
| Unpaid Overtime | Older complaints only: "Es herrscht Arbeitszeit auf Vertrauensbasis. Überstunden gehen letztlich verloren." (Kununu, Nov 2020, Angestellte/r oder Arbeiter/in, Sonstige, ottonova Krankenversicherung AG, former). The 2024 IT reviewer says overtime is rare and can be compensated. |
| Silent Firings | Some signal, structurally enabled by the absence of a works council: "People would rather be laid off and replaced at high cost rather than keep the old employees" (Kununu, Dec 2023, IT, ottonova AG, current); the 2022 pre-start contract cancellations. No reports since 2024. |
| Work-Life Balance issues | Low. Kununu WLB 4.4, Glassdoor WLB 3.7. One 2024 IT reviewer: "ottonova Balance wird nicht eingehalten" under leadership. Workload peaks mentioned in the Sep 2025 Glassdoor IT review. |

**Risk level: LOW** for systemic toxicity. The pattern is (c) localised team-level dysfunction plus a structural weakness (no works council, cost pressure from losses translating into pay freezes), not a toxic top. The negative cluster is concentrated in 2020-2024; 2025-2026 reviews and the GPTW survey are markedly better.

---

## Section 5: Compensation

#### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| Glassdoor (glassdoor.de, Germany/Munich) | Senior Software Engineer | €70.3K - €77.5K | none reported | none reported | ~€70K - €78K | 5 |
| Glassdoor | Software Engineer | €68.0K - €75.0K | none | none | ~€68K - €75K | 7 |
| Glassdoor | Staff Engineer | €84.9K - €93.5K | none | none | ~€85K - €94K | 2 |
| Glassdoor | Team Lead | €79.9K - €83.3K | none | none | ~€80K - €83K | 2 |
| Kununu | Softwareentwickler:in | Ø €75.2K | n/a | n/a | Ø €75.2K | 5 |
| Kununu | DevOps Engineer | Ø €69.2K | n/a | n/a | Ø €69.2K | 2 |
| Kununu | Teamleiter:in | Ø €87.7K | n/a | n/a | Ø €87.7K | 2 |
| levels.fyi (Munich) | Software Engineer (5-10 yrs exp) | €68.6K | €0 | €0 | €68.6K | 1 (Feb 2024) |

Glassdoor and levels.fyi retrieved via Chromium/CDP. Glassdoor rates Comp & Benefits 3.3; Kununu Gehalt/Sozialleistungen 3.9.

**Munich reference (levels.fyi, Munich metro, as recorded in earlier research):** tech median ~€109K total compensation; a Senior Software Engineer at a large profitable Munich employer typically sits at ~€85K-€95K base (median), ~€100K-€110K (75th percentile) and €120K+ (90th percentile) before equity. The Munich page did not render in this session, so these figures were not re-fetched today.

#### Equity / Stock

**None advertised.** The 2026 benefits list (sports subsidy, company health insurance, company pension, travel subsidy, corporate benefits, training, mobile working, 30 days' leave plus 24/31 December, bike leasing, Ticket Plus City Card, referral bonus) contains no VSOP, ESOP or phantom shares, and no salary source reports stock. Reviewers also note no Urlaubs- or Weihnachtsgeld. One 2024 Kununu reviewer mentions colleagues being motivated by "Bonus", and a 2017 reviewer mentions "Bonifikationen für besondere Leistungen", so occasional bonuses may exist. Not a public company; no liquidity event in sight.

#### Verdict

**BELOW.** The best senior IC data points (Glassdoor Senior SWE €70K-€78K, Staff Engineer €85K-€94K) sit at or below the median of a large, profitable Munich employer, with no equity and no 13th-month pay to close the gap, and with reviewers reporting multi-year raise freezes. (The selection criteria file sets no salary floor; this is a comparison, not a blocker.)

---

## Section 6: AI/ML & Tech Stack

#### AI Strategy

- **Genuine but small applied-AI effort.** The AI team is "the newest division within Data & Analytics", with production use cases already shipped: "automated email routing, intelligent document processing, and semi-automated chat support" (Senior AI Engineer posting, Jun 2026). Team size: AI Team Lead, a Product Manager and two AI Engineers.
- **Platform:** AWS Bedrock (tech radar: ADOPT), Lambda, Fargate, EKS; SageMaker under ASSESS; scikit-learn and XGBoost (ADOPT); spaCy, Tesseract, OpenCV, ML Kit under ASSESS (document/OCR work). Claude Code is in TRIAL for engineering.
- **Management intent:** for 2026 the board names "der verstärkte Einsatz generativer und agentenbasierter KI" as a basis for further growth (Versicherungsbote board interview, Dec 2025).
- Assessment: real internal applied GenAI (claims documents, chat, email triage) on AWS, not marketing. It is a cost-reduction tool for the insurer, not an AI product, and the team is tiny.

#### Tech Stack

Sources: ottonova Tech Radar 2026/Q4 (tech-radar.ottonova.de, updated Oct 2026), engineering blog ottonova.tech, Personio postings (current XML feed plus Wayback snapshots of 2025-2026 postings: Software Engineer - JavaScript, Professional PHP Software Engineer, (Senior) Cloud Security Engineer, Data Engineer, Senior AI Engineer), GitHub org `ottonova` (4 public repos, mostly dormant).

| Category | Technologies |
|---|---|
| **Primary language(s)** | **PHP 8 / Symfony** (backend microservices, "most of them written in PHP"), **TypeScript** (Angular + NgRx/RxJS frontends, NestJS backends, Node.js), Go (some services), Kotlin / Kotlin Multiplatform (Android), Swift (iOS), Python (data/ML), Java |
| **AI/ML** | AWS Bedrock, scikit-learn, XGBoost, LLMs / RAG / agentic workflows, vector databases; assessing SageMaker, spaCy, Tesseract, OpenCV |
| **Cloud** | AWS (EC2, Lambda, CloudFront, Route53, SSO, Amazon MQ, Fargate, EKS) |
| **Infrastructure** | Kubernetes, Helm, Docker, Flatcar Linux, Terraform + Terragrunt, Vault, Traefik, Nginx, FluxCD (trial), GitLab CI, Backstage, Prometheus, Grafana, Sentry, SonarQube |
| **Data** | MySQL, PostgreSQL, Oracle Database, RabbitMQ / Amazon MQ, Redis, Google BigQuery, AWS QuickSight, Pentaho Data Integration, Open Metadata; assessing Redshift, AWS Glue |
| **Other** | DDD, CQRS, Event Sourcing, hexagonal architecture, microservices, OpenAPI/AsyncAPI, ADRs, Cypress/Jest/Vitest/Selenium, Craft CMS, chapters per craft, regular "hackotton" hackathons |

**Summary:** Polyglot web-platform engineering centred on PHP (Symfony microservices) and TypeScript (Angular/NestJS), with Go services, native Kotlin/Swift mobile apps and a small Python layer for data science and GenAI (scikit-learn, XGBoost, AWS Bedrock). Runs on AWS with self-managed Kubernetes, Terraform and GitLab. Applied, production engineering for an insurer's internal and customer-facing systems; no research.

---

## Section 7: Language

- **Core software engineering:** the Software Engineer - JavaScript and Professional PHP Software Engineer postings (2025-2026) require "a proficient level of written and spoken English" and list "Deutschkenntnisse / Gute Deutschkenntnisse" only as a plus. Several engineering blog authors and Kununu IT reviewers write in English, and English-language IT reviews appear on Kununu from 2019 onwards, which points to an international engineering team.
- **Data & AI:** the Senior AI Engineer posting (2026) requires **"Fluent in German (at least B2) and English"**; the Data Engineer posting (2025) requires "fließend Deutsch und/oder Englisch (mindestens B2)".
- **Company context:** German-language insurer; most postings, the careers page and nearly all non-IT communication are German. Claims, underwriting and business stakeholders work in German.

**Verdict:** **CONDITIONAL.** English works for the PHP/TypeScript product teams; the Data & AI unit, where the Python work sits, requires German B2.

---

## Section 8: Stability

#### Financial Position

Source: SFCR ottonova Gruppe 2025 (first group SFCR, adopted 18.05.2026) and SFCR ottonova Krankenversicherung AG 2025.

| Item | FY2025 |
|---|---|
| Gross written premiums | €53.98M |
| Net premiums (after reinsurance) | €48.93M |
| Underwriting result (insurer) | -€0.38M |
| Other non-technical expenses (personnel, marketing, B2B sales) | €16.71M |
| Result from ordinary activities | -€16.54M |
| **Group net loss** | **-€16.32M** |
| **Accumulated balance-sheet loss** | **-€185.95M** |
| Group Solvency II ratio | **181%** (own funds €19.01M / SCR €10.50M) |
| Insurer solo MCR ratio | 679% (prior year 398%) |
| Cash and equivalents (group) | €1.92M plus €3.32M overnight deposits |
| Subordinated Debeka loan | €11.14M (to 2030) |

Trend: the insurer's underwriting result is close to break-even, but the group still loses ~€16M a year on personnel, marketing and sales. Management "plant mit effizienterem Wachstum bei gleichzeitiger Erhöhung der Profitabilität" and targets break-even "in naher Zukunft", the same language used for the 2022 Series F ("last financing round before break-even"). The group SFCR states plainly: "Das Finanzierungsrisiko auf der Gruppen-Ebene ist nicht ausgeschlossen und wird ständig beobachtet." Positive signal: the board claims a top-five position in net customer growth in the PKV market, and solvency ratios improved through the 2025 capital measures. No credit rating.

#### Financial Runway

No analyst runway estimate exists; the model below is built from the FY2025 SFCR P&L. Because ottonova is an insurer, the binding constraint is not cash but **Solvency II own funds**: investments of ~€50M are tied to policyholder ageing reserves and cannot fund losses. The relevant "cash at hand" is own funds above the 100% SCR line.

| Cost line | Annual estimate (FY2025 actual) |
|---|---|
| Net claims incl. claims handling | ~€24.8M |
| Additions to technical reserves (ageing reserves) | ~€15.6M |
| Policyholder premium-refund reserve | ~€1.8M |
| Acquisition costs (commissions, sales) | ~€13.2M |
| Insurer administration costs | ~€1.8M |
| Group personnel, marketing, B2B sales (non-technical) | ~€16.7M |
| Investment expenses | ~€0.2M |
| **Total gross burn** | **~€74.1M/year** |

| Revenue source | Est. annual inflow |
|---|---|
| Net premiums | ~€48.9M/year |
| Reinsurance commissions | ~€3.4M/year |
| Other technical income | ~€3.4M/year |
| Investment income | ~€1.4M/year |
| Other non-technical income | ~€0.9M/year |
| **Total revenue offset** | **~€58.0M/year** |

Net ~-€16.1M, consistent with the reported -€16.3M. Staff cross-check: ~192 employees at ~€80K fully loaded is ~€15M, i.e. most of the non-technical line plus part of claims handling.

| Scenario | Net burn | Capital buffer | Runway without new capital | Next round needed by |
|---|---|---|---|---|
| Optimistic (premium growth plus cost discipline halves the loss) | ~€8M/year | €8.5M | ~1.1 years | ~early 2027 |
| Base case (loss as in 2025) | ~€16M/year | €8.5M | ~0.5 years | ~mid-2026 (already covered by top-ups) |
| Stress (2026 premium increases hurt new business and lapses) | ~€20M/year | €8.5M | ~0.4 years | ~mid-2026 |

Capital buffer = eligible group own funds €19.0M minus SCR €10.5M at 31.12.2025 (SFCR group report, observed 2026-11-09). The capital buffer does not cover even one year of losses, so ottonova depends on its shareholders re-capitalising it every year. This has happened reliably so far (2025: €10M cash plus a €12.7M Debeka debt-to-equity swap), and Debeka's role as strategic anchor is the main mitigant. A shareholder fatigue scenario would mean a forced sale, most plausibly to Debeka or another insurer, rather than an abrupt shutdown, because BaFin would require an orderly solution for policyholders.

#### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| Jun-Jul 2022 | Signed employment contracts cancelled ~3 weeks before start | at least 3 reported on Kununu | "auf Grund veränderter wirtschaftlicher und betrieblicher Lage"; during the Series F raise |
| Late 2022 / early 2023 | Board reduced from 6 to 4 (CEO to supervisory board, IT board member left) | management only | No CTO on the board since |
| Jun 2024 | Chief Marketing & Sales Officer left, seat not refilled | management only | Board now 3 |
| 01.01.2026 | Reorganisation: claims, customer service, marketing and B2B sales moved from ottonova services GmbH into the insurer AG; services GmbH becomes IT-only Technology Services GmbH | entity transfer, not reported as job cuts | Probably a § 613a BGB transfer of undertaking |

No publicly reported layoffs found (TrueUp has no entry; press searches return nothing). Reviewer comments about high fluctuation and replacing staff (2020-2023, 2026) are the only attrition signals.

#### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | **NO** | "There is no works council." (Kununu, Dec 2023, Angestellte/r oder Arbeiter/in, IT, ottonova AG, current); "kein Betriebstat" (Glassdoor, Dec 2023, Software engineer, current, 3+ years, Munich); earlier reviewers ask for one: "Ein Betriebsrat wäre sehr wichtig" (Kununu, Nov 2020, Sonstige, former) and "Mit steigendem Wachstum und Unternehmensgröße ist ein Betriebsrat nicht nur wünschenswert!!!" (Kununu, Feb 2022, Sonstige, former). No newer review contradicts it. |
| Collective agreement | **NONE** | "The employer does not pay according to the collective agreement" (Kununu, Dec 2023, IT). No "tarifgebunden" or AGV Versicherungen reference in postings; no Urlaubs-/Weihnachtsgeld. Not found in the AGV member context. |
| European works council | N/A | German-only operations |
| Conflict signals | None found | No union press, no reports of blocked elections |
| Co-determination | Supervisory board appears shareholder-only (Naumann, Clemens, Jung, Pothmann, Nagel, Feurstein, Grimmeisen); below the 500-employee one-third threshold | SFCR 2025 |

**Verdict:** **CAUTION.** A loss-making, shareholder-funded employer with no works council and no tariff binding, with past reports of pay freezes and staff replacement. GPTW certification partly offsets this.

---

## Section 9: Regulated Industry

Heavily regulated. ottonova Krankenversicherung AG is supervised by **BaFin** under the VAG and **Solvency II** (SFCR/ORSA, key functions, governance reviews); the holding is a regulated insurance holding since July 2025. IT is subject to **DORA** (applicable to insurers since January 2025; the Cloud Security posting lists DORA and ISO 27001), the outsourcing rules for the core systems, and the special category health-data rules (GDPR Art. 9, § 203 StGB confidentiality). Integration with the telematics infrastructure / e-prescription (gematik) appears on the engineering blog.

Practical impact: ISMS aligned to ISO 27001, external pen tests, documented outsourcing, change governance and audit trails. The engineering culture (microservices on Kubernetes, CI/CD, quarterly tech radar) suggests continuous delivery is still possible, but compliance overhead is real and the regulatory frame limits risk appetite.

**Verdict:** **CAUTION**

---

## Section 10: On-Call

No posting mentions Rufbereitschaft, on-call or 24/7 duty (all keyword hits for "Bereitschaft" were "Bereitschaft, dich ... weiterzuentwickeln"). The JavaScript posting expects "Übernahme von Verantwortung für Produktionsprobleme in deinem Bereich", which signals you-build-it-you-run-it ownership during working hours. The product is a customer app and claims back office of an insurer; outages matter but are not life-critical, and the infrastructure is self-managed Kubernetes run by a DevOps/staff systems group. Reviewers report no on-call burden.

**Verdict:** **UNVERIFIED**, likely PASS for product engineers; ask during interviews whether DevOps/platform-adjacent roles carry a rota.

---

## Section 11: Interview Process

Based on Glassdoor (11 interviews, all roles; retrieved via Chromium/CDP):

| Metric | Value |
|---|---|
| Difficulty | 3.0 / 5 (Software Engineer and QA Automation Engineer interviews rated "very hard") |
| Positive experience | 27% (64% negative) |
| Average duration | ~23 days overall; **~60 days for Software Engineer** |
| Rounds | ~4 (HR call, take-home, tech screen, on-site) |

Glassdoor stage mix: group interview 25%, skills test 25%, phone interview 19%, personality test 13%, IQ test 6%, presentation 6%, one-on-one 6%.

The backend team's own description (ottonova.tech, "Recruiting Backend Engineers at ottonova", May 2022): short HR call, a **take-home coding assignment** (a couple of hours, judged on clean design, OOP, correctness and tests), a **30-minute technical screening** with objectively answerable questions, and a **1-2 hour in-person interview** in Munich covering experience, open-ended discussion (REST, microservices, web security, design patterns), and **live coding of a few straightforward problems**, followed by meeting another team. Hiring requires a unanimous "hire".

Assessment: **experience- and clean-code-focused, not LeetCode-heavy**, but slow and with a poor candidate-experience score (27% positive on a small sample).

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | BORDERLINE: BaFin-licensed health insurer with a strong in-house engineering organisation (five SWE teams, dedicated tech subsidiary since 2026) |
| Not consulting | PASS: internal product engineering, no client billing |
| Profitable | **FAIL**: FY2025 group loss €16.3M, accumulated loss €186M, break-even still pending |
| Employee count | ~192 in Germany (no threshold in the selection criteria) |
| English-speaking | CONDITIONAL: English for PHP/TypeScript teams; German B2 required in Data & AI |
| Local entity + engineering contracts | PASS: ottonova Technology Services GmbH, HRB 227447 München, purpose covers development of digital products; direct permanent contracts |
| Location / work model | PASS: Ottostraße 4, Maxvorstadt, 72 m from Lenbachplatz tram, 114 m from Karlsplatz U/S; hybrid, ~2 office days a week |
| Glassdoor | 3.8 on 8-18 reviews (65% recommend); too thin to be reliable |
| Kununu | 4.2, 91% recommendation (last 2 years), Top Company 2022-2027 |
| Salary | BELOW: Senior SWE €70K-€78K, Staff €85K-€94K, no equity, raise freezes reported |
| AI/ML content | Small but real applied GenAI (Bedrock, document processing, chat support) in a 4-person team |
| Computer-language/Tech-stack | **FAIL**: PHP/Symfony and TypeScript-centric; Python limited to data/ML |
| No on-call | UNVERIFIED, likely PASS |
| WLB / Stability | WLB good (Kununu 4.4, GPTW); stability weak (loss-making, ~0.5 years solvency headroom, annual shareholder top-ups) |
| Works council / collective agreement | CAUTION: neither |
| Regulated industry | CAUTION: BaFin, Solvency II, DORA, health data |
| Review themes | Positive culture and hybrid flexibility; recurring pay/raise complaints, no works council, 2022 cancelled contracts |
| Strategic anchor | Debeka (largest German PKV) is shareholder and lender, which makes an absorption scenario more likely than a collapse |

---

## Section 13: Verdict

**Exclude.** ottonova is a well-liked employer with an unusually transparent engineering organisation, but it misses the selection criteria on language fit and business stability.

**Strengths.** Consistently strong culture signals: GPTW certified, Beste Arbeitgeber in Bayern and ITK every year 2021-2026, Kununu 4.2 with 91% recommendation over the last two years and Top Company 2022-2027, Kununu WLB 4.4. The engineering is serious (DDD/CQRS, event sourcing, microservices on Kubernetes/AWS, a public quarterly tech radar, chapters, hackathons), the office is one of the best-connected addresses in Munich, the hybrid model is real, and the applied GenAI work is in production rather than on slides.

**Hard blockers:**

1. **Python is not central.** The platform is PHP 8/Symfony plus TypeScript (Angular, NestJS), per the 2026 tech radar and every 2025-2026 software-engineering posting. Python exists only in Data & Analytics, where the AI team is four people in total. A senior Python role would at best be the one AI engineer slot.
2. **That Python-adjacent slot requires German B2.** The Senior AI Engineer posting asks for fluent German (B2+) alongside English, so the only part of the company where Python matters is also the part that is not English-first.
3. **Business stability does not support a long-term commitment.** Nine years after launch, the group still loses ~€16M a year (accumulated €186M), holds only ~€8.5M of Solvency II own funds above its SCR, and depends on yearly shareholder top-ups (2025: €10M equity plus a €12.7M Debeka debt-to-equity swap). The 2022 Series F was billed as the last round before break-even; three more capital measures followed. The SFCR itself flags group-level financing risk.

**Secondary concerns:** no works council and no collective agreement, with past reports of multi-year raise freezes and staff being replaced rather than retained; compensation clearly below the Munich senior bracket (Senior SWE €70K-€78K, Staff €85K-€94K, no equity, no 13th salary); no CTO on the management board since 2023; a regulated insurer environment (BaFin, DORA, health data) with compliance overhead; a slow, poorly rated hiring process (27% positive, ~60 days for SWE); and the 2022 episode of contracts cancelled weeks before start, which shows what happens to hires when funding tightens.

**Recommendation:** do not apply. Revisit only if ottonova reaches sustained profitability or is absorbed by a larger, profitable insurer (Debeka is the obvious candidate) **and** the Data & AI unit grows into a Python-centred team that hires in English. At that point, verify in the interview the senior/staff pay band, whether the AI team's German B2 requirement is firm, and whether any on-call rota covers the self-managed Kubernetes platform.

---

## Sources

- [ottonova Impressum](https://www.ottonova.de/impressum) (curl)
- [ottonova careers page](https://www.ottonova.de/unternehmen/jobs) (curl)
- [ottonova Personio job feed (XML, EN)](https://ottonova.jobs.personio.de/xml?language=en) (curl)
- [Senior AI Engineer – Architecture & Platform (Personio, 2026)](https://ottonova.jobs.personio.de/job/2690964) (via XML feed)
- [Software Engineer (m/w/d) - JavaScript (Wayback, Jul 2026)](http://web.archive.org/web/20260708063110/https://ottonova.jobs.personio.de/job/2563474) (curl via Wayback)
- [Professional PHP Software Engineer (Wayback, Jun 2025)](http://web.archive.org/web/20250627071607/https://ottonova.jobs.personio.de/job/2032940?display=en) (curl via Wayback)
- [(Senior) Cloud Security Engineer (Wayback, Jun 2025)](http://web.archive.org/web/20250604153843/https://ottonova.jobs.personio.de/job/1955275?language=de) (curl via Wayback)
- [Data Engineer (Wayback, Jun 2025)](http://web.archive.org/web/20250604153843/https://ottonova.jobs.personio.de/job/2044549?language=de) (curl via Wayback)
- [SFCR ottonova Gruppe 2025 (PDF)](https://assets.ottonova.de/assets/img/documents/SFCR_ottonova_Gruppe_2025.pdf) (curl)
- [SFCR ottonova Krankenversicherung AG 2025 (PDF)](https://assets.ottonova.de/assets/img/documents/SFCR_2025.pdf) (curl)
- [NorthData: ottonova Technology Services GmbH, HRB 227447](https://www.northdata.de/ottonova+Technology+Services+GmbH,+M%C3%BCnchen/Amtsgericht+M%C3%BCnchen+HRB+227447) (Chromium/CDP)
- [NorthData: ottonova Holding AG, HRB 223275](https://www.northdata.de/ottonova+Holding+AG,+M%C3%BCnchen/Amtsgericht+M%C3%BCnchen+HRB+223275) (Chromium/CDP)
- [NorthData: ottonova LEI record](https://www.northdata.de/967600QOQM1EYJDEFT44)
- [Nominatim: Ottostraße 4, München](https://nominatim.openstreetmap.org/search?q=Ottostra%C3%9Fe+4,+80333+M%C3%BCnchen&format=json&addressdetails=1) (curl)
- [Overpass API](https://overpass-api.de/api/interpreter) (curl)
- [Kununu: ottonova overview](https://www.kununu.com/de/ottonova) (Chromium/CDP)
- [Kununu: ottonova reviews](https://www.kununu.com/de/ottonova/kommentare) (Chromium/CDP, filters department=it, score, category)
- [Kununu: ottonova IT reviews](https://www.kununu.com/de/ottonova/kommentare?department=it) (Chromium/CDP)
- [Kununu: ottonova salaries](https://www.kununu.com/de/ottonova/gehalt) (Chromium/CDP)
- [Glassdoor: ottonova overview](https://www.glassdoor.de/%C3%9Cberblick/Arbeit-bei-ottonova-EI_IE1526704.11,19.htm) (Chromium/CDP)
- [Glassdoor: ottonova reviews](https://www.glassdoor.de/Bewertungen/ottonova-Bewertungen-E1526704.htm) (Chromium/CDP)
- [Glassdoor: ottonova salaries](https://www.glassdoor.de/Gehalt/ottonova-Geh%C3%A4lter-E1526704.htm) (Chromium/CDP)
- [Glassdoor: ottonova interviews](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/ottonova-Fragen-im-Vorstellungsgespr%C3%A4ch-E1526704.htm) (Chromium/CDP)
- [levels.fyi: ottonova salaries](https://www.levels.fyi/companies/ottonova/salaries) (Chromium/CDP)
- [levels.fyi: ottonova Software Engineer](https://www.levels.fyi/companies/ottonova/salaries/software-engineer) (Chromium/CDP)
- [Teamblind: ottonova (no page)](https://www.teamblind.com/company/ottonova/reviews) (Chromium/CDP)
- [Great Place to Work: ottonova Gruppe](https://greatplacetowork.de/beste-arbeitgeber/ottonova-gruppe/) (Chromium/CDP)
- [ComputerWoche: Die besten ITK-Arbeitgeber 2022](https://www.computerwoche.de/article/2811579/die-besten-itk-arbeitgeber-2022.html)
- [ottonova Tech Radar 2026/Q4](https://tech-radar.ottonova.de/) (Chromium/CDP)
- [ottonova engineering blog](https://ottonova.tech/) (Chromium/CDP)
- [ottonova.tech: Recruiting Backend Engineers at ottonova](https://ottonova.tech/recruiting-backend-engineers-at-ottonova/) (Chromium/CDP)
- [ottonova.tech: TechStack](https://ottonova.tech/techstack/) (Chromium/CDP)
- [GitHub: ottonova organisation](https://api.github.com/orgs/ottonova/repos) (curl)
- [Munich Startup: €34 million, ottonova closes Series F](https://www.munich-startup.de/en/news/34-million-euros-ottonova-closes-series-f)
- [Munich Startup: ottonova 60 Millionen](https://munich-startup.de/news/ottonova-60-millionen)
- [Versicherungsbote: Debeka steckt 10 Millionen Euro in Ottonova](https://www.versicherungsbote.de/id/4855593/Debeka-Ottonova-Beteiligung/)
- [Versicherungsbote: Ottonova sammelt 60 Millionen Euro ein](https://www.versicherungsbote.de/id/4887176/Ottonova-sammelt-60-Millionen-Euro-ein/)
- [Unquote: Debeka and VC firms in €20m round for ottonova](https://www.unquote.com/dach/official-record/3005499/debeka-and-vc-firms-in-eur20m-round-for-ottonova)
- [Dealroom: ottonova](https://dealroom.co/companies/ottonova/)
- [Cash Online: Ottonova baut Vorstand um, Rittweger wechselt in den Aufsichtsrat](https://www.cash-online.de/a/ottonova-baut-vorstand-um-roman-rittweger-wechselt-in-aufsichtsrat-630477/)
- [Versicherungsbote: Ottonova bekommt neuen CEO](https://www.versicherungsbote.de/id/4909009/Ottonova-bekommt-neuen-CEO/)
- [Cash Online: Ottonova-Vertriebsvorstand Kannenberg geht](https://www.cash-online.de/a/ottonova-vertriebsvorstand-kannenberg-geht-676507)
- [Versicherungsbote: ottonova-Vorstandsteam, "Im Netto-Kundenwachstum liegen wir unter den Top fünf"](https://www.versicherungsbote.de/id/4947264/Vorstandsteam-ottonova-Im-Netto-Kundenwachstum-liegen-wir-unter-den-Top-fuenf/)
- [Versicherungsbote: Ausblick 2026, ottonova board](https://www.versicherungsbote.de/id/4947309/Ausblick-2026-Worauf-sich-Vorstaende-einstellen-und-was-die-Branche-erwartet-Teil-3/?gallery=sdsdf)
- [Versicherungsbote: PKV, die niedrigsten Solvenzquoten 2025](https://www.versicherungsbote.de/id/4950219/PKV-Die-niedrigsten-Solvenzquoten-2025/?gallery=indzq)
- [kvoptimal: ottonova PKV Beitragserhöhung 2026](https://kvoptimal.de/blog/beitragsanpassung/ottonova-pkv-beitragserhoehung-2026/)
- [AGV Versicherungen: Tarifverträge private Versicherungswirtschaft (context)](https://tarifvertrag-online.de/tarifvertraege/versicherungen)
