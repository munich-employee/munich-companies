# 4flow - Full Research Report

_Researched: 2026-08-31_

> **Critical caveats (details in the relevant sections):**
> 1. 4flow is, by public identity and external recognition, a **management consulting firm** (Lünendonk top-10 German management consultancy 2026, Gartner Magic Quadrant for supply chain consulting, Glassdoor industry classification "Unternehmensberatung"). Software is one of three pillars, not the company's centre of gravity.
> 2. **Compensation for engineering roles is well below the Munich senior bracket**: Glassdoor shows Senior Software Developer at EUR 68,000 to 80,000 and Senior Java Engineer at EUR 70,190 to 75,320; levels.fyi shows Software Engineer at ~USD 75.2K total comp.
> 3. The **primary engineering language is Java**, not Python. Python appears in the AI/data roles and "in our repositories", but the product platform is Spring Boot plus Angular.
>
> Countervailing: the company has a Munich office, and two currently open, English-language, Python-centric product roles list Munich.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 2000 (26 years), Berlin, by Kai Althoff |
| Employees | 1,500+ globally at 20+ locations (company's own 2026 figure); Revelio Labs estimates 1,583 for 2025, up 20.2% year on year |
| Revenue (FY2024) | **EUR 60.8M** for the 4flow SE parent entity (unconsolidated HGB filing, published 2026-01-28). Prior years: 59.9M (2023), 50.7M (2022), 39.5M (2021), 26.2M (2020), 33.6M (2019). Group-wide revenue including the GmbH subsidiaries is not published |
| Profitability | Jahresüberschuss EUR 4.05M (2024), 9.44M (2023), 8.44M (2022), 7.91M (2021), -2.33M (2020), 4.40M (2019). Profitable in every year except the pandemic year 2020 - **PASS**, with a caution that 2024 earnings fell 57% on flat revenue |
| Ownership | Private, founder and management owned. The VC investor DEWB exited its 44.4% stake in 2008; no external funding since. Legal form converted 4flow AG to **4flow SE** on 2023-12-29; share capital raised to EUR 581,189 in September 2024 |
| Software-centric | **BORDERLINE, leaning FAIL** - see assessment below |

### Key People

- **Kai Althoff** - founder, CEO, Management Board since 2012
- **Stephan Kappel** - CFO (since 2016)
- **Sören Hagen** - COO (Board seat renewed 2026-04-09)
- **Julian Caspar Schulcz** - COO (since 2020)
- **Dr. Stefan Wolff** - Chairman of the Supervisory Board
- Andreas Kick left the Management Board in April 2026

### Funding History

Not applicable in the venture sense. The only external equity event on record is the 2008 DEWB exit. The company does draw research subsidies: an EU Horizon grant of EUR 3,997,553 (2023, "Resilient Multimodal freight Transport"), plus German federal grants of EUR 359,573 (2025) and EUR 444,596 (2026). These are research co-funding, not operating dependence.

### Business Model

Three pillars plus a research arm:

1. **4flow consulting** - supply chain and logistics strategy through implementation, several hundred client projects a year.
2. **4flow software** - standard products (4flow vista for network design and transportation planning, iTMS/iTM transportation management, and the newly trademarked "optaire", registered 2026-03-27). Genuine product engineering with its own division ("Software Products & Development", 15 open roles at time of research).
3. **4flow management** - 4PL managed services, running clients' transportation networks (Gartner named 4flow a Leader in the 2025 Magic Quadrant for Fourth-Party Logistics).
4. **4flow research** - a small applied-research group, funded partly by the grants above.

### Software-Centric Assessment

The software division is real and substantial, not a marketing veneer. It ships standard products sold to third parties, employs its own product managers and engineers, runs a modern service-based stack, and staffs 15 of the 78 currently open positions. The careers-site FAQ answers a genuine engineering question ("Which programming language and technology do you use?") with real detail. A candidate in Software Products and Development would build a product, not a client deliverable.

However, at company level the balance is against software. Of 78 open roles, 31 are Transport and Supply Chain Management, 17 Supply Chain Consulting, 7 Software Consulting and 15 Software Products and Development, with several of those 15 being sales roles (Account Executive software, Sales Manager software, Presales Consultant). Externally, 4flow is classified and awarded as a consultancy. Glassdoor lists its industry as "Unternehmensberatung" (management consulting) and benchmarks it against the Management and Consulting sector.

**Verdict: BORDERLINE.** The division fits; the company does not.

### Consulting-Adjacency Assessment

- **Does the company self-identify as consulting?** Yes. Its own German career copy opens: "4flow consulting berät weltweit Unternehmen im Bereich Logistik und Supply Chain Management von der Strategie bis zur Umsetzung." Kununu profile: "4flow ist ein führender Anbieter von Logistikberatung, Logistiksoftware und 4PL-Dienstleistungen."
- **External recognition as consulting:** Lünendonk List 2026 "Leading Management Consulting Agencies in Germany" (top 10); Gartner Magic Quadrant for Specialist Supply Chain Strategy, Planning and Operations Consulting 2026 (Leader); FOCUS/ServiceValue "Germany's Best 2026" for management consulting; Gartner Market Guide 2026 for Supply Chain Planning **System Integrators**.
- **Consultant titles in the career track?** Yes, extensively: Associate Consultant, Senior Consultant, Principal Consultant, Director of Consulting, Software Consultant, Technical Software Consultant, Presales Consultant.
- **Do engineers bill hours to clients?** In the consulting and Software Consulting tracks, yes by construction. In Software Products and Development, no: those roles build the standard products.
- **Evidence of consulting culture bleeding across:** the one Munich-eligible AI role that is *not* in the product division ("AI Engineer (d/w/m) im Bereich Consulting") explicitly demands "ein ausgeprägtes Consulting-Mindset" and supports "Presales-Aktivitäten, Kundenworkshops und AI-gestützte Angebotsprozesse".

**Verdict: FAIL at company level, PASS for the specific product-division roles.** This distinction matters more than the headline, because the roles actually open in Munich are in the product division.

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **4flow SE** (parent, employer of record for all German roles) | Amtsgericht Charlottenburg (Berlin), **HRB 259422 B**, EUID DEF1103R.HRB259422B, VAT DE 813013913 | Hallerstrasse 1, 10587 Berlin | "Services and products for the design and realization of logistic systems" (NorthData, verbatim translation of the registered Unternehmensgegenstand) |
| 4flow management GmbH | Amtsgericht Charlottenburg, HRB 119008 B | Berlin | 4PL managed services operations |
| 4flow management Control Tower GmbH | Amtsgericht Charlottenburg, HRB 228851 B | Berlin | Logistics control tower operations |
| 4flow digital GmbH | Amtsgericht Charlottenburg, HRB 248744 B | Berlin | Digital/software subsidiary |

**Verification.** The registered purpose ("services **and products** for the design and realization of logistic systems") is a genuine operating purpose covering product development, not a sales-shell formulation such as "marketing and distribution of software". Every German job posting, including the Munich-eligible ones, names **4flow SE** as the hiring entity directly, so contracts are with the German SE and not through a PEO or EOR. Filings are audited (Forvis Mazars GmbH & Co. KG, formerly Mazars), with the FY2024 Jahresabschluss published 2026-01-28. Predecessor registration HRB 75560 B (as 4flow AG) dates back to 2000-06-08.

**Verdict:** **PASS.**

---

## Section 3: Office Location

- **Office address:** Lyonel-Feininger-Strasse 28, 80807 Munich. Nominatim resolves this to node 2393547495, neighbourhood Alte Heide, district Schwabing-Freimann.
- **Nearest public transit** (Overpass, 700 m radius): **Alte Heide** (U6, plus bus stop), **Am Münchner Tor**, **Anni-Albers-Strasse** and **Domagkstrasse** (tram 23).
- **Work model:** All German postings are marked **Hybrid**, and the benefit list states "Flexibility and the opportunity to work remotely." Kununu benefit confirmations put Homeoffice at 70% (confirmed by 173 employees). No fixed office-day count is published; that is worth clarifying in interview.

---

## Section 4: Reviews

**Great Place to Work:** 4flow has a strong but **historical** GPTW record: 3rd best employer in Germany (2008) and 2nd place in "Beste Arbeitgeber Deutschlands 2010". No current GPTW Germany certification was found for 2024 to 2026. The company's live employer awards are instead **Leading Employer 2026** (top 1% of German employers, meta-study of 2.35 million companies, second consecutive year) and inclusion for the second year running on the **F.A.Z. Institute / ServiceValue list of Germany's preferred employers**. Treat these as positive but weaker signals than a current GPTW certification.

#### Glassdoor

Employer ID E948354. Retrieved via Playwright over CDP (WebFetch and curl both hit the bot wall; glassdoor.com redirects to the German locale for this session).

| Metric | Global | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | 4,5 (46 reviews) | 4,5 (46 reviews, filter returns the same set) | **no reviews** | **no reviews** |
| **WLB** | 4,2 | n/a | n/a | n/a |
| **Culture & Values** | 4,7 | n/a | n/a | n/a |
| **Comp & Benefits** | 3,9 to 4,0 | n/a | n/a | n/a |
| **Career Opportunities** | 4,0 | n/a | n/a | n/a |
| **Diversity & Inclusion** | UNVERIFIED (chart-only, no numeric value exposed) | n/a | n/a | n/a |
| **% Recommend** | 93% | 93% | n/a | n/a |
| **CEO Approval** | 99% (Kai Althoff) | 99% | n/a | n/a |
| **Business Outlook** | 84% positive | 84% | n/a | n/a |

Notes and caveats:
- The German-locale page reports **46 reviews**; Glassdoor's US-locale snippets reference larger bases (77 and 206 reviews for individual sub-ratings). The sub-ratings above come from those US-locale snippets and rest on a different, larger base than 46. Treat all Glassdoor figures here as **directional, not reliable**: even the largest cited base is small for a 1,500-person company, and 4,5 with 99% CEO approval on 46 reviews is a profile that small-sample selection effects can easily produce.
- **There is not a single Glassdoor review from Munich, and not a single one from a Software Engineer.** Every rating above describes consultants and supply chain staff, overwhelmingly in Berlin. Glassdoor tells us essentially nothing about the job actually on offer.
- Glassdoor's own comparison set for 4flow is BASF, Zalando, Lear, Booz Allen Hamilton, PwC: a consulting and industrial peer group, not a software one.

#### Kununu

Retrieved via Playwright over CDP (curl returns HTTP 405; the plain WebFetch path is blocked).

- **Overall score:** **4,1 / 5,0** (industry average Transport/Verkehr/Logistik: 3,4)
- **Recommendation rate (Weiterempfehlung):** **82%** (last 2 years), trend described as stable
- **Total reviews:** **270** since 2012, of which 80 culture ratings and 101 salary entries
- **Kununu Top Company:** **YES**
- Sub-scores: Karriere & Gehalt 4,1 / Unternehmenskultur 4,2 / Arbeitsumgebung 4,2 / Vielfalt 4,5
- Best-rated factor: **Kollegenzusammenhalt 4,6** (41 ratings). Worst-rated factor: **Work-Life-Balance 3,6** (45 ratings)
- Salary satisfaction: 66% satisfied (169 ratings). Kununu's own averages: Berater:in EUR 73,000; Supply Chain Manager:in EUR 63,400; Analyst:in EUR 51,900

Kununu is the better-populated source here (270 versus 46) and gives a distinctly cooler picture than Glassdoor: 4,1 rather than 4,5, and 82% rather than 93% recommendation.

#### Blind / Teamblind

**No company page exists** (teamblind.com/company/4flow returns "Page not found"). Expected: Blind coverage is US-tech skewed and 4flow has no US engineering presence to speak of (its US sites in Atlanta and Royal Oak are sales and 4PL operations).

#### Review Themes (2024-2026)

**Positives:**
- Colleague solidarity is the single strongest and most consistent theme (Kununu's top factor at 4,6). Reviews from August 2026: "Gegenseitiger Respekt, Spass bei der Arbeit und Innovationsgeist" and "Bester Arbeitgeber, für den ich je arbeiten durfte".
- Genuinely international work and named blue-chip clients: "Interessante Projekte und die Möglichkeit, international tätig zu sein", "Je nach Projekt internationale Teams" (March 2026).
- Early responsibility: "man kriegt schnell sehr viel Verantwortung" appears repeatedly, echoed by the company's own pitch.
- Perceived employer stability: "Sicherheit und Zuverlässigkeit von 4flow als Arbeitgeber" (July 2026).
- Offices, equipment and benefits are praised; Kununu benefit confirmations: Mitarbeiter-Events 72%, Diensthandy 71%, Homeoffice 70%.
- Career development rated 4,2, with one August 2026 reviewer noting specifically: "Nur im Software-Bereich gute fachliche Karrieremöglichkeiten" (good specialist, non-managerial career paths exist **only** in the software division). That is a favourable detail for the roles in question.

**Negatives:**
- **Workload and hours** are the dominant complaint and appear across every year and both platforms. August 2026: "Teilweise sehr hohe Arbeitsbelastung mit langen Arbeitszeiten. Hier fehlt eine Regelung, die Ausgleich für intensive Phasen schafft." November 2025: "Manchmal zu viel Arbeit." August 2026: "die Arbeit ist oft sehr viel, lange Arbeitszeiten."
- **Consulting-specific hours culture.** March 2026: "Ich hatte im Consulting nicht den Eindruck, dass Leben ausserhalb der Arbeit beim Staffing und der Projektplanung eine Rolle spielt... Wer das anspricht, bekommt klassische Consulting-ist-halt-hart-Sprüche." The most severe account (August 2024) describes 08:00 to 21:00/22:00 as routine in consulting, with "unangebrachte Kommentare, wenn man vor 20 Uhr nach Hause ging". Note the date and the division.
- **Culture-versus-image gap.** May 2026: "Im Bewerbungsprozess wird vieles sehr offen, modern und herzlich dargestellt... allerdings merkt man mit der Zeit schnell, dass vieles davon eher Fassade ist."
- **One explicit toxicity and inclusion allegation** (September 2025): "Die toxischen Aspekte des Unternehmens sind nicht sofort offensichtlich... darunter kann sich eine verschlossene und starre Kultur verbergen. Es gibt wenig Offenheit für neue Ideen... Mitarbeiter aus anderen Niederlassungen oder mit anderem Hintergrund sind im Vergleich zu ihren deutschen Kollegen [benachteiligt]." The same reviewer describes unstructured onboarding. **This is directly relevant to a non-German-native candidate** and is the single most concerning item in the corpus, though it is one review against a Vielfalt score of 4,5.
- **Uneven application of flexibility** (May 2026): "Viele hatten die Möglichkeit, flexibel zu arbeiten... Mir wurde diese Flexibilität allerdings nicht wirklich zugestanden."
- **Rigid hierarchy and promotion bottlenecks.** March 2026: "Das Unternehmen ist streng hierarchisch strukturiert", and training time must be fought for. February 2025: long waits for promised promotions, with too few intermediate levels and too few non-manager tracks.
- **Networks over merit** (February 2026): "Was man kann zählt weniger als Kontakte."
- **Strategic incoherence and internal competition** (July 2026): the suggestion that 4flow must settle internally "welcher Strategie genau man folgen will, welche Produkte und Leistungen an Kunden verkauft werden sollten... Damit kein internes Wettbewerb entsteht", plus "Auslastung und Projektgewinnung bleiben leider ein Problem" in the SAP area. Utilisation pressure is a consultancy signal, and it lines up with the 2024 earnings drop.
- **Pay and retention** (May 2026): "Dafür reichen Benefits wie ein Obstkorb, Müsliriegel, kostenloses Frühstück... nicht aus. Viel wichtiger wären ein faires Gehalt, bessere Sozialleistungen und mehr Rücksicht auf das Privatleben." Also "Lästereien müssen endlich abgemahnt werden."
- **Estimation failures pushed downward** (March 2026): "nicht alles von den unteren Ebenen auffangen lassen" when project effort is misjudged.

#### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | **Low to moderate.** No pattern of abusive management. CEO approval 99%, and the founder has run the company for 26 years. One September 2025 review alleges a "verschlossene und starre Kultur" with poor integration of non-German employees; it stands largely alone. |
| 24/7 Work Expectation | **Moderate, consulting-localized.** No always-on or weekend-availability expectation is described, but the August 2024 account of 08:00 to 22:00 days with peer pressure against leaving before 20:00 is a genuine red flag. Every such account is tagged to consulting projects, not the software division. |
| Internal Surveillance | **None found.** No mention of monitoring, tracking or activity metrics in any review across either platform. |
| Fear-driven Management | **Not evidenced.** The nearest signals are "klassische Consulting-ist-halt-hart-Sprüche" when raising workload, and reluctance to admit misestimated project effort. Dismissive rather than punitive. |
| Communication Breakdown | **Moderate.** Strategic ambiguity between divisions, internal competition over what to sell, and inconsistent onboarding ("keine klaren Standards dafür, wie die Aufgabenbereiche zu erlernen waren"). |
| Unpaid Overtime | **Moderate and explicit.** August 2026: "Hier fehlt eine Regelung, die Ausgleich für intensive Phasen schafft" - overtime in intense phases is compensated by nothing. |
| Silent Firings | **None found.** No reviews describe managed exits or PIP-driven attrition. |
| Work-Life Balance issues | **Confirmed, the company's weakest dimension.** Kununu's lowest factor at 3,6 across 45 ratings, and the theme recurs in every year sampled. Glassdoor's global 4,2 is inconsistent with this and rests on a smaller, more favourable base. |

**Risk level: MODERATE.** The pattern is **(c) localized dysfunction**, specifically the consulting and 4PL project organisation, layered over **(b) ordinary mid-size-company hierarchy** (rigid levels, slow promotions, contacts mattering). It is not systemic toxicity: colleague solidarity at 4,6, 82% recommendation and a stable trend do not coexist with a genuinely toxic organisation. The material unknown is whether the software division inherits the consulting hours culture. No review in the corpus is identifiably from a product engineer in Munich, so this cannot be settled from public data and must be asked directly.

---

## Section 5: Compensation

#### Salary Data

| Source | Title | Base (EUR) | Stock/yr (EUR) | Bonus (EUR) | Total Comp (EUR) | Data Points |
|---|---|---|---|---|---|---|
| Glassdoor DE | Senior Software Developer | 68,000 to 80,000 | 0 | included in range | ~68K to 80K | 3 |
| Glassdoor DE | Senior Java Engineer (Developer) | 70,190 to 75,320 | 0 | included | ~70K to 75K | 1 |
| Glassdoor DE | Software Developer | 52,000 to 59,700 | 0 | included | ~52K to 60K | 3 |
| Glassdoor DE | Softwareentwickler | 50,000 to 56,000 | 0 | included | ~50K to 56K | 3 |
| Glassdoor DE | Junior Softwareentwickler | 49,240 to 53,190 | 0 | included | ~49K to 53K | 1 |
| Glassdoor DE | Data Scientist | 56,000 to 68,003 | 0 | included | ~56K to 68K | 3 |
| Glassdoor DE | Manager Software Development | 74,345 to 79,838 | 0 | included | ~74K to 80K | 1 |
| Glassdoor DE | Software Consultant | 63,680 to 68,000 | 0 | included | ~64K to 68K | 3 |
| Glassdoor DE | Senior Consultant | 80,000 to 94,939 | 0 | included | ~80K to 95K | 22 |
| Glassdoor DE | Principal Consultant | 130,000 to 178,000 | 0 | included | ~130K to 178K | 3 |
| levels.fyi | Software Engineer (Germany) | n/a | n/a | n/a | ~USD 75,202 (~EUR 69K) | very few |
| levels.fyi | Management Consultant (Germany) | n/a | n/a | n/a | ~USD 93,337 (~EUR 86K) | very few |
| Kununu | Berater:in | 73,000 (avg) | 0 | n/a | ~73K | 11 |

No Munich-specific engineering figures exist on any platform: the German salary data is overwhelmingly Berlin. Munich median, 75th and 90th percentile for 4flow are **UNVERIFIED** for lack of any data points. The best available read of the senior engineering band is **EUR 68,000 to 80,000**, with the sample too thin (3 data points) to treat as a firm band.

The structural pattern is unambiguous even so: at 4flow, the consulting track pays materially more than the engineering track at every level. Senior Consultant (80K to 95K) sits above Senior Software Developer (68K to 80K), and Principal Consultant (130K to 178K) has no engineering counterpart on the board at all. Engineers are not where the value is captured.

#### Equity / Stock

**None.** 4flow SE is privately held by its founder and management with share capital of EUR 581,189, and there is no employee share scheme, option plan or ESPP mentioned in any job posting, benefit list or review. Postings offer "competitive base salary, an attractive bonus system, and a great benefits package". Total compensation is therefore base plus a cash bonus, full stop. Benefits named in postings: permanent contract, individual training budget, Employee Assistance Program, sports and team events, organic fruit and snacks. Kununu adds company phone (71%) and home office (70%); company cars exist but reviewers call them poor value ("die Dienstwägen billiger bzw. so attraktiv machen, damit man diese tatsächlich als Benefit betrachten").

#### Verdict

**BELOW.** A senior software engineer at a large, profitable Munich corporation is in the EUR 85,000 to 110,000 base region, typically with a bonus and often with equity or a share-matching plan. 4flow's observed senior engineering ceiling of ~EUR 80,000 sits below the *floor* of that bracket, in a city with Germany's highest cost of living, and with zero equity to offset it. Even allowing for the thin sample and a possible Munich uplift over Berlin data, closing a gap of that size would require an offer well outside the observed distribution.

---

## Section 6: AI/ML & Tech Stack Fit

#### AI Strategy

The AI investment is real and recent, not marketing language. Concrete evidence:

- An **AI Architect** role charged with owning "the architectural vision and strategic direction for AI and machine learning systems across a distributed team in India and Europe", selecting the LLMOps platform, and building "unified, scalable and secure AI systems that support international data sovereignty and regional privacy regulations". A company that is only AI-washing does not hire an architect to pick its LLMOps stack.
- Named agentic frameworks in requirements: **LangGraph, AutoGen, CrewAI**, plus LLMOps, prompt engineering and RAG architectures.
- A **Senior Software Engineer - AI** role (Budapest) integrating ML models into production backends with TensorFlow, PyTorch, scikit-learn and Hugging Face Transformers.
- A greenfield **AI-driven supply chain product** being built from scratch in the new Bangalore office ("we are building a next-generation, AI-driven supply chain product from the ground up").
- A new trademark, **"optaire"**, filed 2026-03-27, alongside the existing 4flow vista, iTM and iTMS marks.
- Publicly co-funded applied research (EU Horizon EUR 4.0M on resilient multimodal freight transport; federal grants in 2025 and 2026).
- The domain content is optimisation-heavy rather than LLM-only: the Senior Data Engineer role covers "data architecture to mathematical optimization and simulation".

The counterweight: much of the deep AI build-out is being staffed **in Bangalore and Budapest**, not Germany. The German-located AI roles are an architect (leadership, distributed across India and Europe) and a data engineer. The German AI Engineer opening is inside consulting, building AI agents for client projects and Microsoft 365 or Power Platform integrations, which is closer to internal automation and presales support than to product ML.

#### Tech Stack

Sources: the 4flow careers-site engineering FAQ (authoritative, written by the engineering organisation), plus six current job descriptions. No public GitHub organisation or engineering blog was found.

| Category | Technologies |
|---|---|
| **Primary language(s)** | **Java** and **JavaScript/TypeScript** (FAQ: "We do most of our programming in Java and JavaScript/TypeScript"). Also present: **Python**, Bash, Groovy, Go |
| **AI/ML** | TensorFlow, PyTorch, scikit-learn, Hugging Face Transformers; LangGraph, AutoGen, CrewAI; LLMOps, RAG, prompt engineering; pandas, NumPy, Matplotlib, Seaborn; n8n and Make.com for workflow automation (consulting side) |
| **Cloud** | AWS, Azure, GCP (all three named; "our services run in containers in various cloud environments") |
| **Infrastructure** | Docker, Kubernetes, **HashiCorp Nomad** for orchestration, Ansible, CI/CD pipelines, Grafana for monitoring |
| **Data** | MySQL, PostgreSQL, Apache Kafka, dbt, Airflow, analytical databases and data warehouses |
| **Other** | Spring Boot and Angular as the main application frameworks; React and Next.js in the newer Bangalore product; REST API design, domain-driven design, microservices |

Two notes. First, HashiCorp Nomad rather than Kubernetes for the core platform is an unusual, slightly dated choice that suggests a long-lived platform carried forward rather than rebuilt. Second, the stack is coherent and modern for a product organisation of this size; nothing here is legacy in a worrying sense, but nothing is leading-edge either.

#### Current Open Roles

Verified live on 2026-08-31 via careers.4flow.com (the site returns 78 open positions; each URL below resolved to an active posting with an open application form).

| Role | Division/Team | Level | Key Tech | Link |
|---|---|---|---|---|
| **Senior Data Engineer (d/f/m)** | 4flow software (Software Products & Development) | Senior | **Python**, pandas, NumPy, scikit-learn, dbt, Airflow, analytical DBs, DevOps/DataOps, mathematical optimisation and simulation | [posting](https://careers.4flow.com/offer/senior-data-engineer-d-f-m/948a0420-ca88-411b-81d3-ece3ff326c25) |
| **AI Architect (d/f/m)** | 4flow software (Software Products & Development) | Staff/Principal (~8 yrs, 4+ in AI/ML architecture) | **Python**, TensorFlow, PyTorch, Hugging Face, LangGraph/AutoGen/CrewAI, LLMOps, AWS/Azure/GCP, Docker, Kubernetes | [posting](https://careers.4flow.com/offer/ai-architect-d-f-m/b2d8bc0d-d4e7-44ac-84ed-9eeacbddc757) |
| AI Engineer (d/w/m) im Bereich Consulting | Supply Chain **Consulting** | Mid to senior | Python, LangChain/LangGraph/AutoGen/CrewAI, RAG, n8n, Make.com, Azure/AWS/GCP, M365 and Power Platform | [posting](https://careers.4flow.com/offer/ai-engineer-d-w-m-im-bereich-consul/911995c8-ba22-480e-bc90-6ab8636cd0c6) |

Both product-division roles list **Munich** among their locations (Senior Data Engineer: Bad Nauheim, Berlin, Budapest, Dresden, Düsseldorf, Hamburg, Heidelberg, **Munich**, Rüsselsheim, Stuttgart; AI Architect: the same plus Paris, Pilsen, Zaragoza), both are Hybrid, both are English-language postings, and both are permanent 4flow SE contracts. The third is Munich-eligible but consulting and German-required, and is not a fit.

Everything else in Software Products & Development is in Bangalore (Senior Lead Full Stack Engineer, two Senior Software Engineer Fullstack, Lead Software Engineer Frontend), Budapest (Software Developer Backend, Senior Software Engineer AI) or is a sales role in the US or China. **There is no plain "Senior Software Engineer" opening in Germany.**

**Verdict:** Java-and-TypeScript product engineering (Spring Boot plus Angular, Nomad, Kafka) with a genuine and recently funded Python AI/ML layer on top (PyTorch, Hugging Face, agentic frameworks, LLMOps) across AWS, Azure and GCP. The work is applied production engineering on commercial standard software for logistics and transport optimisation, with a real optimisation and simulation core, not research. For a Python-first candidate the fit is narrow but genuine: it exists precisely in the two open Munich-eligible product roles (Senior Data Engineer, AI Architect) and essentially nowhere else in the German organisation. A generalist backend move here would mean writing Java.

---

## Section 7: Language

- Job postings for the product division are written **in English** (Senior Data Engineer, AI Architect, and every Software Products & Development posting worldwide).
- Neither Munich-eligible product role lists German at any level, and neither mentions it at all.
- By contrast, the consulting-side postings are in German and demand it: the AI Engineer role requires "Sehr gute Deutsch- und Englischkenntnisse", and other openings are explicitly titled "German skills required" or "German Speaker".
- The engineering organisation is genuinely distributed across Berlin, Budapest, Pilsen, Bangalore, Zaragoza and Paris, and the AI Architect role is defined as leading "a distributed team in India and Europe", which forces English as the working language.
- Countervailing: the internal and corporate culture is German-language (Kununu profile, employer branding and most reviews are in German), and one September 2025 review alleges that employees "aus anderen Niederlassungen oder mit anderem Hintergrund" are disadvantaged relative to German colleagues. English will carry the job; German will likely matter for informal integration and internal visibility.

**Verdict:** **PASS** for the two product roles (English-required, German not requested). **FAIL** for the consulting track, which is German-first and should be excluded outright.

---

## Section 8: Stability

#### Financial Position

Figures from the audited HGB Jahresabschluss filings of **4flow SE** (the parent entity only; the group's 4PL and digital subsidiaries file separately, so group revenue is higher than shown). Retrieved from NorthData, auditor Forvis Mazars GmbH & Co. KG, latest publication 2026-01-28 for FY2024.

| Year | Revenue | Net income (Jahresüberschuss) | Margin |
|---|---|---|---|
| 2019 | EUR 33.6M | EUR 4.40M | 13.1% |
| 2020 | EUR 26.2M | EUR -2.33M | loss |
| 2021 | EUR 39.5M | EUR 7.91M | 20.0% |
| 2022 | EUR 50.7M | EUR 8.44M | 16.6% |
| 2023 | EUR 59.9M | EUR 9.44M | 15.8% |
| 2024 | EUR 60.8M | EUR 4.05M | 6.7% |

The 2019 to 2023 record is excellent: revenue up 78% in four years at mid-to-high-teens net margins, self-funded, with a single pandemic loss year fully recovered the following year. The company also appears on the FT/Statista "Europe's Long-Term Growth Champions" list (2025 and 2026 editions) and on FOCUS Business's fastest-growing German companies list.

**FY2024 is the caution.** Revenue was essentially flat (+1.5%) while net income fell 57%, from EUR 9.44M to EUR 4.05M, compressing the margin from 15.8% to 6.7%. Headcount over the same period grew sharply (Revelio: 1,293 in 2024 to 1,583 in 2025, +20.2%). Flat revenue against a 20% larger workforce is precisely the utilisation squeeze that reviewers describe from the inside: "Auslastung und Projektgewinnung bleiben leider ein Problem" (July 2026). Simultaneously, the company is funding new engineering hubs in Bangalore and Budapest and a greenfield AI product. Some of the margin compression is deliberate investment; some looks like a consulting business hiring ahead of demand.

FY2025 figures will not be published until roughly early 2027, so whether this is a one-year investment dip or the start of a trend cannot yet be established.

#### Financial Runway

**Not applicable.** 4flow SE is neither VC-backed nor loss-making. It has taken no external equity since the 2008 DEWB exit, is profitable in nine of the last ten filed years, and is funded from retained earnings. Its only external money is research co-funding (EU Horizon EUR 4.0M, federal grants of EUR 0.36M and EUR 0.44M), which offsets rather than sustains costs. A burn-rate model would be meaningless. The relevant financial risk here is margin compression, not runway.

#### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| - | **None found** | - | No layoffs, restructuring or redundancy programmes at 4flow appear in press coverage, TrueUp-style layoff trackers, or any Glassdoor or Kununu review from 2024 to 2026. Headcount grew ~20% in 2025. Reviewers cite "Sicherheit und Zuverlässigkeit von 4flow als Arbeitgeber" as a positive, and postings advertise "job security at a company with German roots" |

**Verdict:** **PASS**, with a watch item on the FY2024 margin compression. This is a 26-year-old, founder-owned, consistently profitable, debt-free company with no layoff history and a growing workforce. It is one of the more stable employers evaluated in this project.

---

## Section 9: Regulated Industry

4flow operates in logistics and supply chain, one of the least regulated domains for software engineering. There is no BaFin, no medical device regime, no EN 50128, no ISO 26262 functional safety, and no ITAR or defence classification. No job posting mentions a safety case, formal certification, or regulatory documentation obligation.

The compliance surface that does exist is ordinary commercial:
- **GDPR and data sovereignty.** The AI Architect role explicitly covers "international data sovereignty and regional privacy regulations", which matters because 4flow processes client shipment and network data across the EU, US, China, Brazil and India. This is architecture work, not a compliance burden on day-to-day engineering.
- **Customs and trade compliance** appears in the consulting services (international supply chains, customs processes), but as domain subject matter, not as a constraint on the software lifecycle.
- Product postings describe working "at the intersection of logistics, technology, and compliance", which in context means building compliance features into the product, not being slowed by an external regulator.

Practical engineering impact: negligible. No documentation overhead, no gated release process, no formal verification.

**Verdict:** **PASS** (low regulatory burden).

---

## Section 10: On-Call

- **No job posting mentions on-call, standby, Rufbereitschaft, pager duty, or a 24/7 rotation.** This holds for the Senior Data Engineer, AI Architect, Senior Software Engineer AI, Software Developer Backend and Senior Lead Full Stack Engineer postings.
- **No review on Glassdoor or Kununu mentions on-call, night work or weekend incident duty**, across 270 Kununu reviews and the Glassdoor corpus. Given how freely reviewers complain about long hours, silence on on-call is meaningful evidence of absence.
- The two Munich-eligible roles are the least on-call-shaped work in the company: a data engineer building pipelines and optimisation features, and an architect setting AI direction. Neither owns a production incident surface.
- The offsetting consideration: 4flow's 4PL and control-tower business (4flow management Control Tower GmbH) runs live client transportation networks, which somewhere must carry operational cover. There are also "Logistics Analyst (Early shift)" postings, confirming shift work exists in the 4PL organisation. That burden sits in transport and supply chain management, a different division with different contracts, not in product engineering.
- Also relevant: the software is largely delivered to enterprise clients rather than run as a mass-market always-on SaaS, which lowers the structural need for engineer-carried pagers.

**Verdict:** **PASS** for the product-engineering roles, with the caveat that no posting states this explicitly, so it is inference from strong negative evidence rather than a documented policy. Confirm in interview whether the software division carries any production support rotation for hosted client deployments.

---

## Section 11: Interview Process

| Metric | Value |
|---|---|
| Difficulty | ~3,0 / 5 (Glassdoor, "durchschnittliches Gespräch" is the modal rating; the scale is displayed as a slider without a numeric value, so this is read off the distribution) |
| Positive experience | **67% positive**, 20% negative, remainder neutral |
| Average duration | UNVERIFIED (Glassdoor does not expose a numeric average for this employer; individual reports describe two to three weeks) |
| Rounds | **2 to 3** |
| Sample size | **61 interview reports**, last updated 2026-08-11 |
| Route in | 82% online application, 6% via recruiter |

**Typical process**, reconstructed from the reports:

1. **HR screening call**, roughly 30 minutes. Self-introduction, motivation, walk through prior roles and biggest challenges. Conducted in English where the role requires it (one São Paulo candidate in August 2026 notes "Pediram para falar em inglês", they asked me to speak English).
2. **Case study**, roughly 60 minutes, frequently performed live and unseen ("eine Case Study on the fly"). This is a consulting-firm instrument, and its presence across the process is the clearest cultural tell in the whole report.
3. **Personal fit interview**, roughly 45 minutes, with the hiring team.

The company's own published process is: online application, confirmation of receipt, document review, "first get to know" call, then further interviews.

**Character:** **Not LeetCode-heavy.** No report in the corpus describes algorithmic screening, take-home coding, or a live coding round. The process is experience-, communication- and case-focused. Caveat: the interview corpus is dominated by consulting and supply chain candidates (the 61 reports are overwhelmingly Consultant, Supply Chain Consultant, Analyst and intern roles), so it may not describe what the software division does for a senior data engineer or AI architect. Expect at minimum a technical deep-dive on architecture and past systems; ask up front whether a coding exercise is part of the loop.

The 67% positive rate is unremarkable, neither a red flag nor a selling point. The 20% negative share is on the high side for a company with a 4,5 Glassdoor rating, which fits the recurring "image versus reality" theme in the reviews.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | **BORDERLINE.** Real product division (4flow vista, iTMS, optaire) with 15 open roles, but 4flow is externally classified and awarded as a management consultancy; 55 of 78 open roles are consulting, 4PL or supply chain |
| Not consulting | **FAIL at company level, PASS for the specific roles.** Lünendonk top-10 German management consultancy 2026, Gartner MQ consulting Leader, consultant career ladder throughout. The two Munich-eligible openings sit in the product division, not consulting |
| Profitable | **PASS with caution.** EUR 60.8M revenue and EUR 4.05M net income (FY2024, SE entity); profitable in 9 of 10 filed years. FY2024 margin fell from 15.8% to 6.7% on flat revenue |
| Employee count | **PASS.** 1,500+ globally, 20+ locations, ~20% headcount growth in 2025 |
| English-speaking | **PASS** for the two product roles (English postings, no German requested). The consulting track is German-first and excluded |
| Local entity + engineering contracts | **PASS.** 4flow SE, HRB 259422 B, registered purpose "services and products for the design and realization of logistic systems"; direct permanent German contracts, no PEO/EOR |
| Location / work model | Lyonel-Feininger-Strasse 28, 80807 Munich (Alte Heide, U6). Hybrid with 70% home-office confirmation on Kununu |
| Glassdoor | **PASS, but uninformative.** 4,5 with 93% recommend and 99% CEO approval, on only 46 reviews in the German locale, **zero from Munich and zero from software engineers** |
| Kununu | **PASS.** 4,1 / 5,0, 82% recommendation, 270 reviews, Top Company seal, stable trend, versus a 3,4 industry average |
| Salary | **FAIL.** Senior Software Developer EUR 68K to 80K, Senior Java Engineer EUR 70K to 75K, levels.fyi SWE ~USD 75.2K. Below the EUR 85K to 110K Munich senior bracket, with **no equity of any kind** |
| AI/ML content | **PASS.** Funded, concrete and current: AI Architect owning LLMOps direction, agentic frameworks (LangGraph, AutoGen, CrewAI), PyTorch and Hugging Face, greenfield AI supply chain product, EU-funded research. Caveat: much of the build-out is staffed in Bangalore and Budapest |
| Computer-language/Tech-stack | **BORDERLINE.** Company-wide the stack is Java plus TypeScript (Spring Boot, Angular, Nomad, Kafka). Python is first-class only in the AI and data roles, which happen to be exactly the two Munich-eligible openings |
| No on-call | **PASS (inferred).** No posting and no review across 270+ Kununu reviews mentions on-call or standby; shift work exists only in the separate 4PL organisation |
| WLB / Stability | **Stability PASS, WLB CAUTION.** Founder-owned, 26 years old, no layoffs ever recorded, headcount growing. But WLB is the weakest rated factor on Kununu (3,6) with consistent long-hours complaints, concentrated in consulting |
| Regulated industry | **PASS.** Logistics: no BaFin, no ISO 26262, no medical or rail regime. Only ordinary GDPR and data sovereignty work |
| Review themes | **MIXED.** Strong colleague solidarity (4,6), international projects, early responsibility, perceived job security. Against: long hours without time-off-in-lieu, rigid hierarchy, slow promotions, "image versus reality" complaints, one 2025 allegation that non-German employees are less well integrated |
| **No senior SWE role in Germany** | Only two Munich-eligible product openings exist (Senior Data Engineer, AI Architect). There is no generic Senior Software Engineer opening in Germany; all fullstack and backend hiring is in Bangalore and Budapest |
| **Munich office is a satellite** | The engineering centre of gravity is Berlin, and increasingly Bangalore and Budapest. Munich colleagues are likely to be consultants, not product engineers |

---

## Section 13: Verdict

**Overall recommendation: Monitor, with one narrowly conditional application worth making.** This is not a company to pursue on its merits as a software employer, but the AI Architect posting is an unusually specific coincidence of profile and geography, and the cost of one application is low.

**Strengths.** The company is genuinely stable, founder-owned for 26 years, profitable in nine of the last ten filed years, self-funded since 2008, with no layoff history and 20% headcount growth in 2025. The German legal entity is unambiguous, with a real operating purpose and direct permanent contracts. Kununu, the better-populated review source, gives 4,1 with 82% recommendation, a Top Company seal and a stable trend well above its industry average. The AI investment is concrete and recently funded rather than aspirational, and the two Munich-eligible product roles are English-language, Python-centric, permanent, hybrid, and carry no on-call. One reviewer notes that meaningful specialist (non-manager) career paths exist specifically in the software division.

**Hard blockers (numbered):**

1. **Compensation fails, and by a wide margin.** The observed senior engineering ceiling is EUR 80,000 (Senior Software Developer, 3 data points), with Senior Java Engineer at EUR 70,190 to 75,320 and levels.fyi's Software Engineer figure at ~USD 75,202 (~EUR 69K). The Munich bracket for a senior engineer at a large profitable corporation starts around EUR 85,000 and runs to EUR 110,000 plus bonus and equity. 4flow's ceiling sits below that bracket's floor. There is **no equity component of any kind**, so nothing offsets it. Worse, the internal structure is against engineering: Senior Consultant (EUR 80K to 95K, 22 data points) outpays Senior Software Developer, and Principal Consultant reaches EUR 130K to 178K with no engineering equivalent on the board. This is a company where the pay ladder is built for consultants.
2. **The company is a consulting firm, and the criteria exclude consulting-adjacent employers.** Lünendonk top-10 "Leading Management Consulting Agencies in Germany" 2026, Leader in the 2026 Gartner Magic Quadrant for supply chain consulting, Glassdoor industry "Unternehmensberatung", benchmarked against PwC and Booz Allen. Of 78 open roles, 55 are consulting, 4PL or supply chain against 15 in software (several of those being sales). The interview process runs on live case studies, a consulting instrument. The specific roles in question sit inside the product division and would not involve client billing, but the surrounding organisation, pay ladder, promotion norms and culture are consulting's.
3. **Python is not the primary language of the organisation.** The engineering FAQ is explicit: "We do most of our programming in Java and JavaScript/TypeScript", with Spring Boot and Angular as the application frameworks. Python is real but confined to the AI and data layer. Any move outside the two AI/data openings means writing Java, and if either role were later reshaped or the team reorganised, the fallback position is a Java shop.

**Secondary concerns:**

- **FY2024 margin compression.** Net income fell 57% (EUR 9.44M to EUR 4.05M) on flat revenue while headcount grew ~20%. Reviewers independently report that "Auslastung und Projektgewinnung bleiben leider ein Problem". Not a solvency question for a debt-free profitable company, but it is the classic precondition for utilisation pressure and hiring freezes, and FY2025 figures will not publish until ~early 2027.
- **Work-life balance is the company's weakest measured dimension** (Kununu 3,6 across 45 ratings), with long-hours complaints in every year sampled and an explicit note that intense phases carry no compensating time off. The most severe accounts are tagged to consulting projects, but whether the product division is insulated cannot be verified from public data.
- **Zero visibility into the actual job.** There is not one Glassdoor review from Munich and not one from a software engineer, and no Blind page exists. Everything known about working at 4flow describes Berlin consultants.
- **Munich is a satellite for engineering.** The product organisation's centre is Berlin, and new engineering capacity is going to Bangalore and Budapest. A product engineer in Munich would likely sit among consultants and work with a remote team.
- **One 2025 review alleges that employees with non-German backgrounds are less well integrated than German colleagues,** alongside a "verschlossene und starre Kultur". Single-sourced and set against a 4,5 diversity score, but directly relevant here and worth probing.
- **Rigid hierarchy, slow promotions, and "contacts matter more than ability"** recur across 2025 and 2026 reviews.

**Recommendation.** Do not pursue 4flow as a general employer target: on the criteria as written it fails on salary and on consulting-adjacency, and it is not a Python-first organisation. The single exception worth acting on is the **AI Architect (d/f/m)** posting, which is English-language, Python and LLMOps-centred, senior enough (~8 years, 4+ in AI/ML architecture) to plausibly command an exception to the observed pay bands, permanent, hybrid, on-call-free, and based in Munich. Treat it as a one-application, low-investment probe, and **open with the compensation question before investing in a case-study loop**: if the offered band does not clear EUR 90,000 base, withdraw, because nothing else about the company justifies a below-market senior salary. The Senior Data Engineer posting is the same geography and stack but a level lower and correspondingly worse on pay, so it is not worth pursuing. If interviewing, verify: the actual band and bonus structure for the role; how many product engineers sit in Munich versus Berlin, Bangalore and Budapest; whether the software division shares the consulting division's hours culture and how overtime is compensated; how many fixed office days the hybrid model requires; whether the division carries any production support rotation for hosted client deployments; and what the specialist (non-manager) career track actually looks like above senior.

---

## Sources

- [4flow company homepage](https://www.4flow.com/)
- [4flow imprint (legal entity, board, HRB)](https://www.4flow.com/imprint)
- [4flow office locations](https://www.4flow.com/about-4flow/locations)
- [4flow awards and recognitions](https://www.4flow.com/about-4flow/references/awards-recognitions)
- [4flow careers portal](https://careers.4flow.com/)
- [4flow careers: Software Products & Development category (incl. tech stack FAQ)](https://careers.4flow.com/category/software-products-and-development/85aef15b-1d1d-4fd9-a42f-ed2bae51e01b)
- [Job posting: Senior Data Engineer (d/f/m)](https://careers.4flow.com/offer/senior-data-engineer-d-f-m/948a0420-ca88-411b-81d3-ece3ff326c25)
- [Job posting: AI Architect (d/f/m)](https://careers.4flow.com/offer/ai-architect-d-f-m/b2d8bc0d-d4e7-44ac-84ed-9eeacbddc757)
- [Job posting: AI Engineer (d/w/m) im Bereich Consulting](https://careers.4flow.com/offer/ai-engineer-d-w-m-im-bereich-consul/911995c8-ba22-480e-bc90-6ab8636cd0c6)
- [Job posting: Senior Software Engineer - AI (Budapest)](https://careers.4flow.com/offer/senior-software-engineer-ai/3450cac7-0274-4492-bc55-0b9d08585bb0)
- [Job posting: Software Developer - Backend (Budapest)](https://careers.4flow.com/offer/software-developer-backend/e62918cd-0beb-43c4-8b52-c8db60bb2697)
- [Job posting: Senior Lead Full Stack Engineer (Bangalore)](https://careers.4flow.com/offer/senior-lead-full-stack-engineer/a6aba087-06c0-4036-8c87-bbe1b248c00a)
- [NorthData: 4flow SE, HRB 259422 B (revenue, earnings, purpose, history)](https://www.northdata.com/4flow%20SE,%20Berlin/Amtsgericht%20Charlottenburg%20(Berlin)%20HRB%20259422%20B)
- [NorthData: 4flow AG predecessor entity, HRB 75560 B](https://www.northdata.com/4flow+AG,+Berlin/Amtsgericht+Charlottenburg+(Berlin)+HRB+75560+B)
- [NorthData: 4flow management GmbH, HRB 119008 B](https://www.northdata.com/4flow%20management%20GmbH,%20Berlin/Amtsgericht%20Charlottenburg%20(Berlin)%20HRB%20119008%20B)
- [NorthData: 4flow management Control Tower GmbH, HRB 228851 B](https://www.northdata.com/4flow%20management%20Control%20Tower%20GmbH,%20Berlin/Amtsgericht%20Charlottenburg%20(Berlin)%20HRB%20228851%20B)
- [NorthData: 4flow digital GmbH, HRB 248744 B](https://www.northdata.de/4flow%20digital%20GmbH,%20Berlin/Amtsgericht%20Charlottenburg%20(Berlin)%20HRB%20248744%20B)
- [Creditreform: 4flow SE Firmenauskunft](https://firmeneintrag.creditreform.de/10587/2011191765/4FLOW_SE)
- [Glassdoor: 4flow reviews (E948354)](https://www.glassdoor.de/Bewertungen/4flow-Bewertungen-E948354.htm)
- [Glassdoor: 4flow company overview](https://www.glassdoor.de/%C3%9Cberblick/Arbeiten-bei-4flow-EI_IE948354.11,16.htm)
- [Glassdoor: 4flow reviews (US locale)](https://www.glassdoor.com/Reviews/4flow-Reviews-E948354.htm)
- [Glassdoor: 4flow reviews in Berlin](https://www.glassdoor.com/Reviews/4flow-Berlin-Reviews-EI_IE948354.0,5_IL.6,12_IM1020.htm)
- [Glassdoor: 4flow Consultant reviews](https://www.glassdoor.com/Reviews/4flow-Consultant-Reviews-EI_IE948354.0,5_KO6,16.htm)
- [Glassdoor: 4flow salaries](https://www.glassdoor.de/Gehalt/4flow-Geh%C3%A4lter-E948354.htm)
- [Glassdoor: 4flow interview questions](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/4flow-Fragen-im-Vorstellungsgespr%C3%A4ch-E948354.htm)
- [Glassdoor: 4flow jobs in Germany](https://www.glassdoor.com/Jobs/4flow-Germany-Jobs-EI_IE948354.0,5_IL.6,13_IN96.htm)
- [Kununu: 4flow employer profile](https://www.kununu.com/de/4flow)
- [levels.fyi: 4flow salaries](https://www.levels.fyi/companies/4flow/salaries)
- [levels.fyi: 4flow salaries (structured data)](https://www.levels.fyi/companies/4flow/salaries.md)
- [Teamblind: 4flow (no company page exists)](https://www.teamblind.com/company/4flow)
- [Revelio Labs: 4flow headcount data](https://www.reveliolabs.com/companies/4flow/employees/)
- [Craft.co: 4flow company profile](https://craft.co/4flow)
- [Crunchbase: 4flow](https://www.crunchbase.com/organization/4flow)
- [Tracxn: 4flow company profile](https://tracxn.com/d/companies/4flow/__O2vNtRfcdH_dTJCRFwogv6L87jqPgjEkNPeWt_2BCsg)
- [PitchBook: 4flow profile](https://pitchbook.com/profiles/company/125576-11)
- [ZoomInfo: 4flow SE](https://www.zoominfo.com/c/4flow-se/395459001)
- [wer-zu-wem.de: 4flow Firmenprofil](https://www.wer-zu-wem.de/firma/four-flow.html)
- [4flow among Europe's Long-Term Growth Champions by FT and Statista](https://www.4flow.com/news/4flow-among-europes-long-term-growth-champions-2025-by-financial-times-and-statista)
- [4flow named Leading Employer 2026 (top 1% of German employers)](https://www.instagram.com/p/DVMR8tbjsV3/)
- [openPR: 4flow AG among Germany's three best employers (Great Place to Work, 2008)](https://www.openpr.de/news/188646/4flow-AG-gehoert-zu-den-drei-besten-Arbeitgebern-Deutschlands.html)
- [openPR: 4flow AG second-best employer in Germany (Great Place to Work, 2010)](https://www.openpr.de/news/402051/Logistikspezialist-4flow-AG-ist-zweitbester-Arbeitgeber-Deutschlands.html)
- [openPR: 4flow press releases archive](https://www.openpr.de/pressemitteilungen/4flow-ag-0005662/)
- [connecticum: 4flow SE employer profile](https://www.connecticum.de/arbeitgeber/4flow-se-141151)
- [OpenStreetMap Nominatim (office geocoding, district confirmation)](https://nominatim.openstreetmap.org/search?q=Lyonel-Feininger-Stra%C3%9Fe+28%2C+80807+M%C3%BCnchen&format=json&addressdetails=1)
- [Overpass API (nearby transit stops)](https://overpass-api.de/api/interpreter)

### Retrieval notes

- **Kununu** was retrieved via **Playwright over CDP**. Plain curl returns HTTP 405 and WebFetch is blocked.
- **Glassdoor** (reviews, overview, salaries, interviews, filtered views) was retrieved via **Playwright over CDP** using the authenticated browser session. WebFetch and curl are blocked; note that glassdoor.com redirects to the German locale in this session, and the German locale reports a smaller review base (46) than the US-locale snippets (77 and 206).
- **NorthData** financial series were retrieved via **Playwright over CDP** and extracted from the embedded chart JSON, which exposes the exact filed figures and their audit sources without a premium subscription.
- **careers.4flow.com** job listings and descriptions were retrieved via **Playwright over CDP** (the site is JavaScript-rendered and WebFetch returns only the shell).
- **Nominatim and Overpass** were queried directly with curl.
- The configured **Playwright MCP server failed to connect** in this session (CONNECTION_CLOSED); the CDP endpoint at localhost:9222 was driven directly with a Python Playwright script instead.
