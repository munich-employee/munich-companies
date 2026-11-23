# UniteLabs - Full Research Report

_Researched: 2026-11-23_

> **Disqualifiers**
>
> 1. **Early-stage, VC-funded startup.** UniteLabs GmbH was registered in February 2024, has ~28 people and has
>    closed only an angel round (2024) and a €2.77M pre-seed (2025). A €9M seed round was "being raised" in April
>    2026; no close has been announced and the commercial register shows no capital increase since March 2025.
> 2. **Pay below the Munich senior market.** Both open senior engineering roles advertise **€70,000-90,000**. The
>    top of that band sits below the levels.fyi Munich **Senior** Software Engineer median (€96K total comp)
>    and near the 25th-75th percentile midpoint for all levels. No equity programme is disclosed.
> 3. **Thin financial runway on public evidence.** A bottom-up model (Section 8) suggests the pre-seed cash is
>    largely spent by late 2026 unless the seed round (or a bridge) has closed quietly.
>
> The full report follows anyway for completeness.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | **2024** (2 years). Gesellschaftsvertrag dated 26.01.2024, registered 27.02.2024 (HRB 291351). Prototype work from 2022 (some directories, e.g. Munich Startup, list 2022 as the founding year) |
| Employees | **~28**: 27 associated LinkedIn members, 27 people (plus the office dog) on the team page, "rund 28 Köpfe" in Q1 2026 (StartingUp), "roughly 30 people" on the company's own fact page (30 Jul 2026). Includes interns and working students |
| Revenue (FY2025) | **Not published.** Founder: "Ein Großteil von Umsatz und Pipeline stammt heute bereits aus den USA" (StartingUp, Apr 2026). No figure disclosed |
| Profitability | Loss-making early-stage startup (no filed accounts visible; see Section 8) - **FAIL** |
| Ownership | Private, VC-backed. Three founders' holding UGs at 23.02% each (~69% combined); 10 further shareholders including NAP (lead investor) and angels |
| Software-centric | Software-only lab-automation platform (connectors, SDK, cloud API, workflow engine); explicitly "manufactures and resells no laboratory hardware" - **PASS** |

### Key People

- **Robert Zechlin** - Co-CEO and co-founder. Strategy, sales, finance, HR, fundraising. Information Systems (TUM),
  business (LMU); earlier roles across automotive, finance and consulting. [LinkedIn](https://www.linkedin.com/in/zechlin/)
- **Dr. Lukas Bromig** - Co-CEO and co-founder. Product vision, customer success, technical sales. TUM doctorate on
  digitalisation of industrial biotechnology; built the open-source SiLA 2 Manager, the platform's first prototype.
  [LinkedIn](https://www.linkedin.com/in/lukas-bromig-8a035a93/)
- **Julian Willand** - CTO and co-founder. Owns platform architecture (connector framework, edge runtime, cloud API,
  workflow engine). Previously co-founder/CIO of Risklio GmbH (2019-2021) and two years as an innovation engineer at
  Siemens. [LinkedIn](https://www.linkedin.com/in/julian-willand/)

All three are registered Geschäftsführer with the right to represent the company.

### Funding History

| Date | Round | Amount | Lead / investors | Notes |
|---|---|---|---|---|
| 2024 (capital increase registered 12.07.2024) | Angel | Undisclosed | Angels | Share capital €25,000 → €28,235 |
| Jan-Mar 2025 (announced 03.04.2025) | Pre-seed | **€2.77M** | **NAP** (formerly Cavalry Ventures); PUSH, Acurio Ventures, OMA Business Angels, LANA Ventures | Capital €28,235 → €34,279 (09.01.2025) → €34,749 (14.03.2025). Legal counsel: honert |
| 2026 (in progress as of Apr 2026) | Seed | **€9M target** | Unknown | "Um diese Dynamik zu finanzieren, hebe man aktuell eine 9-Millionen-Euro-Seed-Runde für die US-Expansion" (StartingUp, KW 16/2026). **No close announced; no capital increase registered through Nov 2026** |
| **Total confirmed** | | **~€3M+** | | Aggregators list $3.0-3.3M |

Valuation: not disclosed for any round.

### Business Model

B2B software sold to biotech/pharma R&D labs, lab system integrators and instrument manufacturers. Priced per
connected device rather than per seat (R&D World), quoted per engagement. Deployment as SaaS, private cloud or
on-premise. Products: the cloud **UniteLabs Platform**, the local **GroundControl** application and the Python
**UniteLabs SDK**, plus a catalogue of ~200 production instrument connectors (800 more "on request", 2-16 weeks
build time). Free access for pre-Series A startups. Named customers: Cradle, DKMS Life Science Lab, LSMC, Tetsuwan
Scientific; unnamed pharma R&D organisations. A first Big Pharma roll-out (Europe + US) was planned for 2026.

### Consulting-Adjacency Assessment

UniteLabs is a product company, but it has a visible services component that matters for engineering roles:

- **Self-identification:** "Software only", "a product a lab could buy rather than a research project". Not consulting.
- **Services sold:** "Professional services: Custom connector development, method development from existing SOPs,
  and integration support for legacy instruments" (company fact page). Connectors "on request" are quoted at 2-16
  weeks each.
- **Engineers on customer deliverables:** the Platform Libraries posting splits the job into "The Builder" (shared
  libraries) and "The Shipper": "Ship production connectors end to end. Spec sheet, physical device, protocol, proof
  of connectivity, tested connector, live customer." and "You want the library work without the customer deadlines.
  Both are in the job."
- **Press challenge:** StartingUp asked directly how the company avoids becoming "eine hochbezahlte IT-Manufaktur";
  the founder's answer is reusable connector abstractions and "Reusable Automation Assets", aiming for a state
  where "Integrationen gemeinsame Infrastruktur sind, nicht Projektgeschäft".
- **No consultant titles, no hourly billing** found.

**Assessment:** not consulting, but connector building per customer instrument is partly project-shaped work with
customer deadlines. The SDK role is the more product-shaped of the two openings.

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **UniteLabs GmbH** | Amtsgericht München **HRB 291351**; LEI 9845006CC378B41ED734; VAT DE368356394 | Mathildenstraße 6, 80336 München (registered and Impressum address) | "Entwicklung und Vertrieb von Software und Hardware sowie Erbringung von Dienstleistungen zur Digitalisierung, Automatisierung und Optimierung von Labor-, Forschungs-, Qualitäts- und Produktionsprozessen." |

The registered purpose explicitly covers software **development**, not just distribution. UniteLabs GmbH is the
only entity and the operating company; all postings are on its own Personio instance as "Permanent employee,
Full-time, München", so engineers are employed directly by the German GmbH. No PEO/EOR. Share capital €34,749 (last
change 14.03.2025). No foreign parent; the company is German-founded and German-headquartered.

**Verdict:** **PASS**

---

## Section 3: Office Location

- **Office address:** **WERK1, Am Kartoffelgarten 14, 81671 München** (Werksviertel München, Berg am Laim, at
  Ostbahnhof). Job postings: "our main office in the vibrant WERK1 Munich hub"; StartingUp: "im Münchner Inkubator
  Werk1"; Bionity lists the company at Am Kartoffelgarten 14; Nominatim resolves the address to Werksviertel
  München, Berg am Laim, 81671. The Impressum/registered address (Mathildenstraße 6, 80336, Klinikviertel,
  Ludwigsvorstadt per Nominatim) is the legal seat, not the workplace described in postings.
- **Nearest public transport** (Overpass, 700 m radius from 48.1234, 11.6075):
  - Ostbahnhof Friedenstraße bus stop, ~380 m
  - **München Ost** railway station, ~500 m: S-Bahn trunk-line services (S1-S4, S6-S8) plus regional and
    long-distance trains
  - Ostbahnhof U-Bahn station (U5), ~590 m
  - Karl-Preis-Platz U-Bahn station (U2), ~620 m; bus stop of the same name (X200), ~630 m
  - Ostbahnhof tram stop, ~660 m
- **Work model:** hybrid with a firm on-site component. Both postings: "an employee-first culture that supports
  flexible remote work and PTO ... Hardware debugging happens there, so being regularly onsite is a must." The
  Platform Libraries posting adds "Located in Munich: The instruments are physically here at WERK1." The SDK posting
  says "Remote work is fine, but big changes start with a written proposal." No fixed number of office days is
  stated. Physical device testing happens in the Munich workshop.

---

## Section 4: Reviews

**GPTW:** UniteLabs does not appear in Great Place to Work Germany listings or certifications (search of
greatplacetowork.de and web search, Nov 2026). **NO.**

**Awards:** "Bestes Münchner Start-up" at the Munich Startup Award 2025 (a startup/product award, not an employer
award).

### Glassdoor

Glassdoor employer ID E2393483 ("1 bis 50 Mitarbeiter", founded 2024). Two reviews in total, both 5.0; the default
German-language view shows "Noch keine Bewertungen", the English-language filter shows both.

| Metric | Global (2 reviews) | Germany (1 review) | Munich (1 review) | Software Engineers (1 review) |
|---|---|---|---|---|
| **Overall** | 5.0 | 5.0 | 5.0 | 5.0 |
| **WLB** | 5.0 | n/a (per-review sub-scores not shown) | n/a | n/a |
| **Culture & Values** | 5.0 | n/a | n/a | n/a |
| **Comp & Benefits** | 5.0 | n/a | n/a | n/a |
| **Career Opportunities** | 5.0 | n/a | n/a | n/a |
| **Diversity & Inclusion** | 5.0 | n/a | n/a | n/a |
| **Senior Management** | 5.0 | n/a | n/a | n/a |
| **% Recommend** | 100% | 100% | 100% | 100% |
| **CEO Approval** | 100% | 100% | 100% | 100% |
| **Business Outlook** | 100% positive | 100% positive | 100% positive | 100% positive |

**Statistically meaningless.** Two reviews is far below the 20-review reliability threshold. The Germany/Munich
column is a single intern. The only "Software Engineer" review is dated **5 Sep 2021, Basel**, "Aktueller
Mitarbeiter, mehr als 1 Jahr", which predates the company's founding (2024) and its Munich base; it is probably
misattributed from another employer or from the pre-company research project. Treat all Glassdoor scores as
**no data**.

### Kununu

- **Overall score:** **UNKNOWN** - no profile
- **Recommendation rate:** UNKNOWN
- **Total reviews:** 0
- **Kununu Top Company:** NO

Tried: `kununu.com/de/unitelabs`, `/unitelabs-gmbh`, `/unitelabs1`, `/unite-labs` (all 404), and the Kununu
search for "UniteLabs" with and without the Germany filter (no results). Substitute signals: GPTW (none), Glassdoor
(2 reviews, unusable), Blind (none).

### Blind / Teamblind

No company page (`teamblind.com/company/UniteLabs` returns "Page not found"). **No data.** Expected for a 28-person
German startup.

### Review Themes (2021-2026)

With two reviews, there are no "themes" in the statistical sense. Below are the only employee statements plus
company-authored signals from the postings, labelled as such.

**Positives:**

- "super nice ambitious people who take responsibility" (Glassdoor, Aug 2026, Intern, current employee, less
  than 1 year, Munich)
- "Flexible Working hours - Remote work possible - Very good team and mission" (Glassdoor, Sep 2021, Junior
  Software Engineer, Software engineer, current employee, more than 1 year, Basel; likely misattributed, see above)
- Founder-stated culture: "I'm responsible for Strategy, Sales, Finance, and HR, and am truly passionate about
  building an amazing company and work environment" (Co-CEO, About page)
- Honest, specific postings: explicit "Probably not a fit if" sections ("Better to say this now than in week 6.")
  and a published salary band are above-average transparency for a Munich startup.
- Moderate after-hours signal in public code: of 243 human commits since Nov 2025 across the four core Python
  repos (python-cdk, python-bus, sila-python, python-sdk; 14 authors), 5.8% were on weekends and 9.9% between
  21:00 and 07:00 (author's local time). This is a weak, indirect signal, not evidence of a norm either way.

**Negatives:**

- No employee complaints exist to report.
- Company-authored signals relevant to workload and WLB:
  - "As one of the first full-time hires, you'll thrive in a fast-paced, dynamic environment and take on
    significant responsibilities from day one." (Platform Libraries posting)
  - "You want the library work without the customer deadlines. Both are in the job." (Platform Libraries posting)
  - "Roughly half the instruments we touch have incomplete or wrong docs. Packet captures, trial and error, vendor
    calls." (Platform Libraries posting)
  - "regular team-building activities including offsites and work-cations" (both postings)
  - US expansion with customers "an beiden Küsten" (StartingUp) implies time-zone overlap with US East and West
    Coast customers.

### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | No evidence either way (two reviews, both 5.0, 100% CEO approval). Founders are publicly visible and consistent in messaging |
| 24/7 Work Expectation | No evidence. Customer-deadline framing and US customers on both coasts are structural risks, not observed behaviour |
| Internal Surveillance | No evidence |
| Fear-driven Management | No evidence |
| Communication Breakdown | No evidence. Postings emphasise written proposals before big changes ("You go quiet for weeks and come back with a big pull request" listed as a misfit) |
| Unpaid Overtime | No evidence. "Fast-paced ... significant responsibilities from day one" is typical early-startup framing |
| Silent Firings | No evidence. No works council, so there is no structural protection either (Section 8) |
| Work-Life Balance issues | No evidence from reviews. Commit timing shows a modest weekend/late share (5.8% / 9.9%). Startup stage, a seed round in progress and a US expansion are the main pressure factors |

**Risk level: UNKNOWN, structurally MODERATE.** There is no systemic toxicity signal, but there is also no review
base to rule it out. The risk comes from the stage: an early-stage company under fundraising pressure, with
customer-deadline-driven connector work and US expansion, has no works council and no review record.

---

## Section 5: Compensation

### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| UniteLabs Personio + Glassdoor (employer-stated) | Senior Python SDK Engineer | **€70-90K** | Not disclosed | Not disclosed | €70-90K | Posted band |
| UniteLabs Personio + Glassdoor (employer-stated) | Senior Python Engineer, Platform Libraries | **€70-90K** | Not disclosed | Not disclosed | €70-90K | Posted band |
| Glassdoor (Munich) | Senior Software Engineer | ~€74-82K | n/a | n/a | ~€74-82K | 1 |
| Glassdoor (Munich) | Software Engineer | ~€77-84K | n/a | n/a | ~€77-84K | 1 |
| Glassdoor (Munich) | Intern | ~€40-43K | n/a | n/a | n/a | 1 |
| levels.fyi | UniteLabs | No company page (404) | | | | 0 |

**Munich reference (levels.fyi, Nov 2026):**

| Population | 25th | Median | 75th | 90th |
|---|---|---|---|---|
| Software Engineer, all levels (600+ data points) | €67.7K | ~€84-87K | €105K | €134K |
| **Senior** Software Engineer (300+ data points) | €81K | ~€96-100K | €118K | €158K |

The posted band's ceiling (€90K) is below the Munich senior median; its midpoint (€80K) sits at the senior 25th
percentile. The single Glassdoor "Senior Software Engineer" report (~€74-82K) is consistent with the band.

### Equity / Stock

**None disclosed.** The postings mention only "Competitive compensation with growth potential in a VC-backed
startup". No VSOP/ESOP is mentioned in postings, press or the company's own fact page. The commercial register
lists 13 shareholders, including a 0.34% holding via "ex Ventures UG", which does not indicate an employee pool. If a
VSOP exists, it is pre-seed-stage paper with no liquidity, so it should be valued at ~€0.

### Verdict

**BELOW** the average bracket of Munich employers hiring senior engineers. The €90K ceiling is ~€6-10K under the
levels.fyi senior median and ~€30K+ under the senior 75th percentile, with no disclosed equity or bonus to
compensate.

---

## Section 6: AI/ML & Tech Stack

### AI Strategy

UniteLabs markets itself as "AI-ready lab automation" infrastructure. In practice it builds the **execution and data
layer** underneath AI rather than AI models:

- Instruments expose self-describing, machine-readable capabilities (SiLA 2 feature definitions), so "an AI agent or
  a developer can discover what an instrument can do"; the company states it supports "AI agents controlling lab
  hardware" through its API.
- The workflow engine is "algorithm-neutral: a lab plugs in its own AI or ML stack" for closed-loop optimisation.
- The data layer captures instrument data "with the context of the run attached" ("science-ready data") for model
  training.
- Planned "UniteLabs Hub" ontology of devices, workflows and capabilities, which the Co-CEO says GenAI "makes ...
  more possible to build" (R&D World).
- Co-hosted an "AI agent runs your next lab experiment" hackathon in Munich with FoodLabs/TUM.ai (OpenAI credits)
  (LinkedIn post).

**Assessment:** genuine lab-automation infrastructure with AI as the downstream use case. The engineering roles are
protocol/SDK/connector work (SiLA 2, gRPC, serial, COM/DLL interop), not ML or LLM engineering. Neither open posting
asks for ML, LLM or data-science skills.

### Tech Stack

Derived from the two current postings (Personio/LinkedIn, Nov 2026), the public GitLab organisation
(`gitlab.com/unitelabs`, 19 projects) and the company fact page.

| Category | Technologies |
|---|---|
| **Primary language(s)** | **Python** (connectors, CDK, Bus, SDK, workflows; "Deep Python: 5+ years ... Async, typing, packaging, testing"); TypeScript (services, web, SiLA-JS); Rust (SiLA library, connector bundler, SiLA Gateway: nice-to-have only); C#/.NET remoting for vendor DLLs |
| **AI/ML** | None in the stack; platform designed for customers to plug in their own AI/ML. LLM-readable device capabilities |
| **Cloud** | AWS, Docker, Kubernetes, Helm, Terraform |
| **Infrastructure** | SiLA 2, gRPC/protobuf, zeroconf, OPC UA, serial/TCP/USB/CAN; COM/DLL interop (ctypes, comtypes, pythonnet); edge runtime (GroundControl); Keycloak (auth) |
| **Data** | PostgreSQL; Prisma ORM |
| **Other** | Prefect (workflows); NestJS (services); Vue 3, Nuxt 3, TailwindCSS (web); GitLab CI; pytest plugins/fixtures, device simulators, hardware-in-the-loop testing |

Public repos with recent activity (Nov 2026): `cdk/python-cdk` (14 stars, "integrates SiLA 2, OPC UA and various
other communication protocols"), `cdk/python-bus`, `sila2/sila-python`, `sila2/sila-js`, `sila2/sila-browser`,
`sdk/python-sdk`, `sdk/cli`, `cdk/connector-factory`, plus vendor connectors (Tecan FluentControl, BlueSens).

**Summary:** Python-centric connector and SDK engineering on the SiLA 2 / gRPC standard, with a TypeScript
(NestJS/Vue) cloud and web layer on AWS/Kubernetes/PostgreSQL and Prefect for workflows; Rust and .NET appear at the
edges (gateway, bundler, vendor DLLs). Applied production engineering against physical lab instruments, not research,
and with no in-house ML component.

---

## Section 7: Language

- All postings, the website, docs and GitLab are in English.
- German is listed only under "Nice to have": "German, for occasional vendor conversations" / "German, for vendor
  conversations".
- The team page and LinkedIn membership show an international team (names spanning German, Turkish, Hungarian,
  Polish, Croatian, North Macedonian, Indian, Azerbaijani, Romanian, Portuguese and English-speaking backgrounds), and
  most revenue comes from US customers.

**Verdict:** **PASS** (English working language, German optional)

---

## Section 8: Stability

### Financial Position

- **No filed accounts visible.** NorthData shows registry events only (no balance sheet or P&L). The first
  Jahresabschluss (FY2024) would have been due by 31.12.2025; as a small/micro GmbH it may have been deposited
  (Hinterlegung) rather than published. Bundesanzeiger full-text search could not be run over CDP (the stateful
  search form navigates away mid-evaluation). handelsregister.ai shows the registry profile but no financials.
- **Revenue:** undisclosed; "most of revenue and pipeline from the US" (Apr 2026). Customers named: Cradle (protein QC
  workflow automation saving ~2,500 hours/year), DKMS Life Science Lab (pilot, May 2026), LSMC, Tetsuwan Scientific
  (SDK integration, Apr 2026).
- **Trend:** commercial traction is improving (US launch at SLAS Boston, Feb 2026; first Big Pharma roll-out planned
  for 2026; ~200 production connectors, up from 40 in Apr 2025), but the company is loss-making and dependent on
  the next round.

### Financial Runway

**Online search:** no runway or burn estimates in press, Crunchbase, Tracxn, Dealroom or PitchBook listings (all
show the €2.77M / ~$3M pre-seed as the latest round). The April 2026 StartingUp interview states a **€9M seed is
being raised**. The commercial register shows **no capital increase after 14.03.2025** (checked 2026-11-23). A
priced round normally appears as a registered capital increase within weeks to a few months of closing, so either
the round has not closed, or it closed recently/after registration lag, or it was structured as convertible loans
(which do not appear in the register).

**Bottom-up model** (all estimates):

| Cost line | Annual estimate |
|---|---|
| Staff (~24 FTE excluding interns/working students × ~€80K fully loaded: €65K average gross + ~22% employer costs) | ~€1.9M |
| Interns / working students (~4) | ~€0.1M |
| Office and workshop (WERK1) | ~€0.15M |
| US go-to-market (SLAS Boston booth, travel, trade fairs, Web Summit) | ~€0.3M |
| Cloud, tooling, test instruments, legal/accounting | ~€0.25M |
| **Total gross burn** | **~€2.7M/year** |

| Revenue source | Est. annual inflow |
|---|---|
| Platform subscriptions (per-device pricing; 4 named customers + unnamed pharma) | ~€0.3-0.8M/year |
| Professional services (custom connectors, method development) | ~€0.1-0.3M/year |
| **Total revenue offset** | **~€0.4-1.1M/year (base €0.6M)** |

**Cash estimate:** confirmed inflows are the undisclosed 2024 angel round plus the €2.77M pre-seed, so roughly
**€3.3-3.8M** raised in total. Estimated cumulative net spend from 2024 to Nov 2026, as the team grew from ~5 to ~28,
is ~€3.0-3.4M. That leaves roughly **€0.2-0.8M** of pre-seed cash today if no new money has arrived. This figure is a
derivation, not an observation: no balance sheet is publicly visible (NorthData/handelsregister.ai, checked
2026-11-23).

| Scenario | Net burn | Cash at hand | Runway | Next round needed by |
|---|---|---|---|---|
| Optimistic: €9M seed has closed (unregistered) | ~€4M/year (US expansion, hiring) | ~€9.5M | ~2.3 years | ~early 2029 (Series A) |
| Base: bridge / convertible (~€2M) in place, seed still open | ~€2.1M/year | ~€2.5M | ~14 months | ~Q1 2028 |
| Stress: no new money since the pre-seed | ~€2.1M/year | ~€0.5M | **~3 months** | Immediately (Q1 2027) |

Hiring two senior engineers in November 2026 suggests money is in hand or firmly committed, which makes the stress
case less likely. This must be verified directly: ask whether the seed has closed, the amount, and the runway in
months.

### Layoffs

**No layoffs found** (TrueUp, press, LinkedIn, Glassdoor). Headcount has only grown (~12-15 at the pre-seed in 2025 →
~28 in 2026).

### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | **NO** (none found) | No mention in postings, press, LinkedIn titles or reviews; a ~28-person founder-led startup |
| Collective agreement | **NONE** | Postings state a free salary band (€70-90K); no "tarifgebunden"/Tarif reference anywhere |
| European works council | N/A | Single German entity |
| Conflict signals | None found | |

**Verdict:** **CAUTION.** The company is early-stage, loss-making and dependent on an unclosed seed round, with
estimated runway ranging from months to ~2 years depending on unannounced financing. There is no works council or
collective agreement, so any downturn would be handled without co-determination. No layoffs so far.

---

## Section 9: Regulated Industry

UniteLabs itself is not a regulated entity (no medical-device, BaFin or ITAR exposure). Its customers are biotech and
pharma R&D labs, and Big Pharma deployments bring **GxP / FDA 21 CFR Part 11** expectations (electronic records,
audit trails, validated software). The Co-CEO addresses this directly: workflows are treated as "ein kontrolliertes
Artefakt mit definierten Inputs, erwarteten Outputs und einem Validierungsnachweis", with "signierten Releases,
Environment-Pinning und klarer Datenlineage", aiming for "compliant by design". Most current work is R&D-lab
automation (non-GxP). As pharma roll-outs grow, validation documentation and controlled release processes will
increase, but nothing resembles safety-case regimes such as ISO 26262 or EN 50128.

**Verdict:** **PASS** (low burden today; GxP validation overhead may grow with pharma customers)

---

## Section 10: On-Call

- Neither posting mentions on-call, Rufbereitschaft, pager duty or incident response.
- The SDK role is library-focused ("Own the SDK as a product ... API design, tests, CI, releases and docs"), which
  normally carries no on-call.
- However: connectors and the edge runtime run in production in customer labs ("connectors already running in
  production"), the company sells SaaS with "Support: Included in every plan, with paid options for priority
  support", customers are on both US coasts, and the Platform Libraries role explicitly includes customer deadlines
  and live customer deployments. With ~28 people there is no separate SRE/support organisation to absorb incidents.

**Verdict:** **CAUTION / UNVERIFIED** (role-dependent; the SDK role is lower-risk than the Platform Libraries role).
Ask explicitly about incident handling for customer-lab outages and US-hours support.

---

## Section 11: Interview Process

| Metric | Value |
|---|---|
| Difficulty | **UNKNOWN** (0 Glassdoor interview reports) |
| Positive experience | UNKNOWN |
| Average duration | UNKNOWN |
| Rounds | UNKNOWN |

The only known steps: the Personio application asks for a CV or LinkedIn profile "along with your responses to the
three questions in the application form". The postings emphasise abstraction judgement, library ownership
(versioning, deprecations, backwards compatibility), written proposals, and debugging protocols against real
hardware. That suggests an experience/design-focused process, possibly with a practical exercise against a connector
or SDK, rather than LeetCode. This is not verified.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | **PASS** - software-only lab-automation platform; hardware workshop is for testing only |
| Not consulting | **PASS with CAUTION** - product company, but custom connector development and customer-deadline connector projects are part of the job (Platform Libraries role especially) |
| Profitable | **FAIL** - loss-making pre-seed/seed startup |
| Employee count | ~28 (founded 2024) |
| English-speaking | **PASS** - English working language; German "nice to have" for vendor calls |
| Local entity + engineering contracts | **PASS** - UniteLabs GmbH, HRB 291351, Munich; direct permanent contracts |
| Location / work model | WERK1, Am Kartoffelgarten 14, Werksviertel (~500 m to München Ost); hybrid, "regularly onsite is a must" |
| Glassdoor | 5.0 from **2 reviews** (one likely misattributed) - no usable data |
| Kununu | **No profile** |
| Salary | **BELOW** - €70-90K posted; Munich senior median ~€96K TC; no disclosed equity |
| AI/ML content | Low - infrastructure for customers' AI; no ML in the roles |
| Computer-language/Tech-stack | Python-centric (SiLA 2, gRPC, async, packaging); TypeScript cloud/web; Rust and .NET at the edges (nice-to-have) |
| No on-call | **CAUTION / UNVERIFIED** - not mentioned; production connectors in customer labs, US customers, tiny team |
| WLB / Stability | **CAUTION** - no WLB data; runway depends on an unannounced €9M seed; startup pace by own description |
| Works council / collective agreement | NONE / NONE |
| Regulated industry | **PASS** - GxP exposure through pharma customers only |
| Review themes | Insufficient data; postings signal "fast-paced", customer deadlines, offsites/work-cations |
| Funding risk | **HIGH** - seed round "being raised" since at least Apr 2026; no registered capital increase since Mar 2025 |

---

## Section 13: Verdict

**Exclude.**

**Strengths.** UniteLabs is a genuine software product company with a clear technical niche: vendor-neutral
connectivity for lab instruments built on the open SiLA 2 standard, with real open-source code that is actively
maintained. The engineering is Python-centric and substantive (async, packaging, API design, backwards
compatibility, protocol work), English is the working language, the office is well connected at München Ost, and the
postings are unusually candid, including a published salary band and explicit "not a fit if" lists. Commercial
traction is real (US launch, named customers, ~200 connectors), and the founders are credible domain experts.

**Hard blockers:**

1. **Startup stage.** The company was registered in February 2024, has ~28 people, and has only an angel round and a
   €2.77M pre-seed confirmed. The postings themselves describe a "fast-paced, dynamic environment" with "significant
   responsibilities from day one" and customer deadlines. This conflicts with a WLB-first, no-startup criterion
   regardless of how pleasant the team is.
2. **Compensation below market.** The €70-90K band tops out below the levels.fyi Munich senior median (~€96K total
   comp) and ~€28K below the senior 75th percentile (€118K), with no disclosed equity or bonus. Large or profitable
   Munich employers routinely pay €90-110K base for senior engineers.
3. **Funding uncertainty.** On public evidence, pre-seed cash is largely consumed by late 2026. The €9M seed has been
   "in progress" since at least April 2026 with no announcement and no registered capital increase. The stress-case
   runway is about a quarter; the optimistic case requires an unannounced close.

**Secondary concerns:**

- No review data at all (Glassdoor 2 reviews, one likely misattributed; no Kununu; no Blind), so culture and WLB
  cannot be verified.
- No works council and no collective agreement, so a restructuring after a failed or down round would carry no
  co-determination safeguards.
- On-call is unaddressed, while connectors run in production in customer labs across US time zones, the team is
  tiny, and paid priority support is sold.
- The Platform Libraries role is half customer-connector delivery ("The Shipper") with deadlines and reverse
  engineering of undocumented instruments. This work is project-like and less predictable than the SDK role.
- Rust appears in the SDK role's scope (Rust SiLA library, bundler, gateway) as "nice to have ... strong enough to
  learn it on the job". This is secondary to Python, but it is part of what the role owns.

**Recommendation:** Do not pursue. If the company announces a closed seed round of ~€9M or more, raises the senior
band to at least ~€95-110K, and clarifies on-call and office-day expectations, it would become worth monitoring. Even
then, its startup stage would still be the deciding issue. No further research is warranted unless one of those
facts changes.

---

## Sources

- [UniteLabs - Official Information (fact page, 30 Jul 2026)](https://unitelabs.io/llm-info/)
- [UniteLabs - Legal Disclosure / Impressum](https://unitelabs.io/legal/disclosure/)
- [UniteLabs - About us / team](https://unitelabs.io/company/about-us/)
- [UniteLabs - Homepage](https://unitelabs.io/)
- [UniteLabs - Docs](https://docs.unitelabs.io/)
- [UniteLabs - Personio careers page](https://unitelabs.jobs.personio.com/)
- [Personio - Senior Python SDK Engineer (m/f/d)](https://unitelabs.jobs.personio.com/job/2838725)
- [Personio - Senior Python Engineer, Platform Libraries (m/f/d)](https://unitelabs.jobs.personio.com/job/2754172)
- [LinkedIn Jobs - Senior Python SDK Engineer](https://www.linkedin.com/jobs/view/4476441676/)
- [LinkedIn Jobs - Senior Python Engineer, Platform Libraries](https://www.linkedin.com/jobs/view/4451225641/)
- [LinkedIn - UniteLabs company page](https://www.linkedin.com/company/unitelabs/)
- [LinkedIn - UniteLabs people](https://www.linkedin.com/company/unitelabs/people/)
- [LinkedIn - UniteLabs posts](https://www.linkedin.com/company/unitelabs/posts/?feedView=all)
- [UniteLabs blog - Debut at SLAS Boston](https://unitelabs.io/resources/blog/unitelabs-debut-slas-boston/)
- [UniteLabs blog - DKMS pilot](https://unitelabs.io/resources/blog/dkms-pilot-unitelabs/)
- [UniteLabs blog - Tetsuwan expands with UniteLabs](https://unitelabs.io/resources/blog/tetsuwan-expands-unitelabs/)
- [UniteLabs blog - Cradle / Benchling case study](https://unitelabs.io/resources/blog/cradle-benchling-case-study/)
- [UniteLabs blog - UniteLabs University](https://unitelabs.io/resources/blog/unitelabs-university-open/)
- [NorthData - UniteLabs GmbH, HRB 291351](https://www.northdata.de/UniteLabs+GmbH,+M%C3%BCnchen/Amtsgericht+M%C3%BCnchen+HRB+291351)
- [handelsregister.ai - UniteLabs GmbH](https://handelsregister.ai/de/unternehmen/UniteLabs%20GmbH)
- [Bundesanzeiger (search attempted)](https://www.bundesanzeiger.de/pub/de/start?0)
- [Glassdoor - UniteLabs overview](https://www.glassdoor.com/Overview/Working-at-UniteLabs-EI_IE2393483.11,20.htm)
- [Glassdoor - UniteLabs reviews (English filter)](https://www.glassdoor.de/Bewertungen/UniteLabs-Bewertungen-E2393483.htm?filter.iso3Language=eng)
- [Glassdoor - UniteLabs salaries](https://www.glassdoor.de/Gehalt/UniteLabs-Geh%C3%A4lter-E2393483.htm)
- [Glassdoor - UniteLabs interviews](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/UniteLabs-Fragen-im-Vorstellungsgespr%C3%A4ch-E2393483.htm)
- [Glassdoor - search "UniteLabs"](https://www.glassdoor.com/Search/results.htm?keyword=UniteLabs)
- [Kununu - search "UniteLabs" (no results)](https://www.kununu.com/de/search?q=UniteLabs)
- [Kununu - /de/unitelabs (404)](https://www.kununu.com/de/unitelabs)
- [Teamblind - UniteLabs (not found)](https://www.teamblind.com/company/UniteLabs)
- [levels.fyi - UniteLabs (not found)](https://www.levels.fyi/companies/unitelabs/salaries)
- [levels.fyi - Software Engineer, Munich Metro Region](https://www.levels.fyi/t/software-engineer/locations/munich-metro-region)
- [levels.fyi - Senior Software Engineer, Munich Metro Region](https://www.levels.fyi/t/software-engineer/levels/senior/locations/munich-metro-region)
- [StartingUp - Gründer*in der Woche: UniteLabs (KW 16/2026)](https://www.starting-up.de/news/gruenderin-der-woche/gruenderin-der-woche-unitelabs.html)
- [R&D World - UniteLabs is building the software layer for automated labs](https://www.rdworldonline.com/unitelabs-is-building-the-software-layer-for-automated-labs/)
- [R&D World - The lab OS wars: 15 companies](https://www.rdworldonline.com/the-lab-os-wars-15-companies-vying-to-enable-the-ai-enabled-labs/)
- [tech.eu - UniteLabs secures €2.77M (Apr 2025)](https://tech.eu/2025/04/03/unitelabs-secures-eur277m-to-become-the-operating-system-for-the-modern-biotech-lab/)
- [Munich Startup - UniteLabs secures €2.77 million](https://www.munich-startup.de/en/news/unitelabs-secures-e2-77-million)
- [Munich Startup - UniteLabs: rethinking laboratory automation](https://www.munich-startup.de/en/news/unitelabs-rethinking-laboratory-automation)
- [Munich Startup - UniteLabs: 7 Fragen](https://www.munich-startup.de/111243/unitelabs-7-fragen/)
- [Munich Startup - UniteLabs profile](https://www.munich-startup.de/de/startups-and-ecosystem/unitelabs)
- [analytica-world - Munich-based lab automation startup raised €2.77M](https://www.analytica-world.com/en/news/1185965/munich-based-lab-automation-startup-raised-2-77m.html)
- [Bionity - UniteLabs company profile](https://www.bionity.com/en/companies/1035265/)
- [SelectScience - UniteLabs debuts at SLAS Boston](https://www.selectscience.net/article/unitelabs-debuts-at-slas-boston-unlocking-ai-ready-lab-automation)
- [honert - advises UniteLabs on pre-seed financing](https://honert.de/en/honert-advises-unitelabs-gmbh-on-pre-seed-financing-round/)
- [Nordic9 - UniteLabs pre-seed led by NAP](https://nordic9.com/news/unitelabs-raised-277m-in-a-pre-seed-funding-round-led-by-nap-joined-by-push-acurio-ventures-oma-business-angels-and-lana-ventures/)
- [Tech Funding News - UniteLabs grabs €2.77M](https://techfundingnews.com/lab-automation-unitelabs-grabs-e2-77m-to-build-the-operating-system-for-ai-driven-biotech-research/)
- [CB Insights - UniteLabs (search listing)](https://www.cbinsights.com/company/unitelabs)
- [Dealroom - UniteLabs (search listing)](https://app.dealroom.co/companies/unitelabs)
- [Tracxn - UniteLabs funding (search listing)](https://tracxn.com/d/companies/unitelabs/__zfzAxUOg1BC57bsZ5YWKzYh8Gm-FtD0dFuA35Z3EQNc/funding-and-investors)
- [PitchBook - UniteLabs (search listing)](https://pitchbook.com/profiles/company/228781-54)
- [deutsche-startups.de - UniteLabs tag](https://www.deutsche-startups.de/tag/UniteLabs/)
- [GitLab - UniteLabs group](https://gitlab.com/unitelabs)
- [GitLab API - UniteLabs projects](https://gitlab.com/api/v4/groups/unitelabs/projects?include_subgroups=true&per_page=100)
- [GitLab - python-cdk](https://gitlab.com/unitelabs/cdk/python-cdk)
- [GitLab - python-bus](https://gitlab.com/unitelabs/cdk/python-bus)
- [GitLab - sila-python](https://gitlab.com/unitelabs/sila2/sila-python)
- [GitLab - SiLA 2 Manager (founder's original prototype)](https://gitlab.com/lukas.bromig/sila2_manager)
- [Stadt München - WERK1 (address)](https://stadt.muenchen.de/service/info/werk1/10214045/)
- [Werksviertel-Mitte - WERK1](https://www.werksviertel-mitte.de/en/offices-studios/werk1-bavaria/)
- [Nominatim - Am Kartoffelgarten 14, 81671 München](https://nominatim.openstreetmap.org/search?q=Am+Kartoffelgarten+14,+81671+M%C3%BCnchen&format=json&addressdetails=1)
- [Nominatim - Mathildenstraße 6, 80336 München](https://nominatim.openstreetmap.org/search?q=Mathildenstra%C3%9Fe+6,+80336+M%C3%BCnchen&format=json&addressdetails=1)
- [Overpass API - stops within 700 m of WERK1](https://overpass-api.de/api/interpreter)
- [TrueUp - layoffs search](https://www.trueup.io/layoffs)
- [Great Place to Work Deutschland - search](https://www.greatplacetowork.de/?s=UniteLabs)
