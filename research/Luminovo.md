# Luminovo - Full Research Report

_Researched: 2026-09-01_

> **Critical Disqualifiers**
> 1. **Not a mature, profitable company.** Seed-stage SaaS, ~88 employees, last publicly disclosed funding round August 2022 (over four years ago). NorthData shows €3.18M cash at 31.12.2024 against an annual loss in the low single-digit millions.
> 2. **No engineering roles open, in Munich or anywhere.** All five current openings sit in the "Revenue" department (business development, solutions engineering, growth marketing intern).
> 3. **Rust-first tech stack.** The monolith is Rust/actix-web with React/TypeScript on the front end; Python covers exactly one stateless FastAPI service. This fails the "Python as the main language" criterion.
>
> The full report follows for completeness.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 2017 (registered as Luminovo Artificial Intelligence GmbH; pivoted to SaaS in 2020). 9 years. |
| Employees | ~88 globally (April 2026); company site says "80+ team members, 30+ remote locations, 20+ nationalities" |
| Revenue (FY2024) | Not published. NorthData shows no disclosed Umsatz line (small-company filing exemption). Estimated €5M to €9M ARR from 300+ customers. **UNVERIFIED** |
| Profitability | Loss-making. NorthData P&L chart shows negative Gewinn every year 2019 to 2024, bottoming around -€3.0M. **FAIL** |
| Ownership | Private, VC-backed. Investors: Chalfen Ventures, Cherry Ventures, La Famiglia, Tencent, Verve Ventures, Khadjavi Capital Partners, plus 8 angels. Founders hold significant stakes via Leap Forward Ventures UG, Zazu Ventures UG, Schaal Technology Ventures UG, Schaal Investments UG, Ummen Beteiligungs UG (two ~18.8% blocks visible on NorthData). |
| Software-centric | Pure B2B SaaS for the electronics supply chain. No hardware, no services billing. **PASS** |

### Key People

- **Sebastian (Valentin S. F.) Schaal** - co-founder, CEO, Geschäftsführer
- **Timon Dominik Ruban** - co-founder, Geschäftsführer
- **Benedikt Ummen** - Prokurist

Both founders are ex-Stanford. The team is described as including graduates from Stanford, Cambridge, ETH Zurich, WHU, TUM and CDTM.

### Funding History

| Date | Amount | Round | Lead / Investors |
|---|---|---|---|
| Apr 2020 | ~$8.67M | Seed | Cherry Ventures + 1 other |
| Feb 2021 | ~$1.52M | Angel | Carsten Thoma |
| Aug 2022 | €11M (~$4.43M new money per Tracxn's split) | Seed | Chalfen Ventures; with Tencent, Verve Ventures, Khadjavi Capital Partners, La Famiglia, Cherry Ventures |
| **Total** | **$16.3M / €13.5M** (company's own Glassdoor profile states €13.5M total) | | 15 investors (7 institutional, 8 angel) |

**No Series A has been announced.** Tracxn's "most recent round" is the August 2022 seed. Some aggregators list a February 2025 "Early VC" event, but this appears to be a re-dating of the 2022 round rather than new capital; no press release, CMS/legal advisory note, or Handelsregister capital increase after 2022 was found. Registered share capital stands at €54,850.

Non-dilutive funding is material and visible on NorthData: four German public research grants totalling roughly €1.34M (CEleRA €244,658; progressivKI €559,522; two "HT: Hybrid" grants at €266,800 each).

### Business Model

SaaS for the electronics value chain, sold to EMS providers (quoting intelligence) and OEMs (procurement intelligence). Add-ons cover customer portal, manufacturing, PCB pricing, supply chain risk (SCRM), strategic sourcing and SRM. Software automates BOM ingestion and cleanup, component availability and alternates, PCB and manufacturing cost calculation, and quote generation. In January 2026 the company launched **ElectronicsGPT**, a free AI agent for electronics procurement search. Claimed reach: 300+ global companies (up from "120+ active customers and 35+ product partners" on the older Glassdoor profile blurb and "50+" at the 2022 seed).

The company originated in 2017 as an AI engineering services business and converted to a product company in 2020. The registered corporate purpose still carries the old services wording, discussed in Section 2. In practice today it is a product company, not a consultancy.

### Consulting-Adjacency Assessment

- Self-identification: no. Positions itself as "a global, remote-first software company redefining the electronics supply chain".
- Billable hours: no evidence. Pricing is SaaS subscription (listed on Capterra, GetApp, Software Advice).
- Career track: no consultant titles. The one client-facing engineering title is "Solutions Engineer", which sits in the **Revenue** department and is a pre-sales role, not a delivery role.
- Deliverable: an internal product platform, not per-client bespoke work.
- Residue: the Handelsregister purpose ("Ingenieurdienstleistungen und die technische Beratung auf dem Gebiet der Künstlichen Intelligenz") is a leftover from the 2017-2020 AI services era and has never been amended.

**Verdict:** not consulting-adjacent as an employer. The only caution is that if Marek were to be hired, the sole open customer-facing technical role (Solutions Engineer) *is* the kind of pre-sales arrangement the criteria exclude.

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **Luminovo GmbH** (formerly Luminovo Artificial Intelligence GmbH) | Amtsgericht München **HRB 237378**; EUID DED2601V.HRB237378; VAT DE315880264 | Schellingstr. 29, 80799 München (earlier Sitz: Gilching, then München) | "Ingenieurdienstleitungen und die technische Beratung auf dem Gebiet der Künstlichen Intelligenz sowie die Entwicklung von Software für die Elektronikbranche." (Engineering services and technical consulting in the field of artificial intelligence, and the development of software for the electronics industry.) |

Verified via the company Impressum (HRB 237378, Schellingstr. 29, GF Sebastian Schaal and Timon Ruban) and cross-checked on NorthData, which returns the same HRB, the same address, the former name, both Geschäftsführer, the Prokura, share capital of €54,850, and the merger of Electronic Fellows GmbH into Luminovo GmbH.

The registered purpose explicitly names **software development** ("die Entwicklung von Software für die Elektronikbranche"), so this is not a sales-and-distribution shell. The German GmbH is the headquarters and the operating entity, not a subsidiary of a foreign parent. Salary ranges on the job board are quoted in EUR by a German entity with German employment terms; there is no sign of PEO or EOR intermediation for German hires. Non-German remote staff (Nairobi, Valencia, Verona, London) are likely on contractor or local arrangements, but that does not affect a Munich-based hire.

One caveat: the "Ingenieurdienstleistungen und technische Beratung" half of the purpose is legacy wording from the pre-2020 AI consultancy. It has not been amended, but nothing in current operations suggests it is still exercised.

**Verdict:** **PASS** - German GmbH, HQ entity, software development in the registered purpose, direct German employment.

---

## Section 3: Office Location

- **Office address:** Schellingstr. 29, 80799 München (Maxvorstadt, on the edge of Schwabing-West, in the university quarter)
- **Nearest public transit** (Overpass, 500m radius around 48.15027 / 11.57565): **Universität** (U3/U6, subway station), **Schellingstraße** (tram 27/28), **Pinakotheken** (tram 27/28). Bus 154 also stops adjacent.

- **Work model:** **Remote-first.** The company describes itself as "a global, remote-first software company", with physical offices in Munich and New York, "regular in-person retreats", an annual "LumiWeek", and co-working weeks. The Glassdoor profile states remote work is fully supported with the only constraint being CET ±2 hours. Current Munich postings are labelled "hybrid" on the Ashby board. One 2025 Munich reviewer explicitly complains of "relativ geringe Office attendance trotz guter Lage" (relatively low office attendance despite the good location), which corroborates that the office is lightly used.

  Remote eligibility for Germany is unrestricted (there is an explicitly "🇪🇺 Germany (remote)" posting). The CET ±2h band is the only geographic constraint.

---

## Section 4: Reviews

### Great Place to Work

**NOT CERTIFIED / NOT LISTED.** No GPTW Germany certification or ranking entry was found for Luminovo. Searches of GPTW Deutschland listings and general web searches returned nothing. Given the company's size (~88), absence from GPTW is unremarkable and is not a negative signal, but it also provides no independent corroboration.

### Glassdoor

Retrieved via Playwright over CDP against the logged-in browser session (WebFetch and curl both returned HTTP 403).

| Metric | Global | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | 4.9 (27 reviews) | **4.9 (8 reviews)** | insufficient data | **no data** |
| **WLB** | 4.7 | 4.7 | - | - |
| **Culture & Values** | 4.9 | 4.9 | - | - |
| **Comp & Benefits** | 4.3 | 4.3 | - | - |
| **Career Opportunities** | 4.6 | 4.6 | - | - |
| **Diversity & Inclusion** | 5.0 | 5.0 | - | - |
| **Senior Management** | 4.8 | 4.8 | - | - |
| **% Recommend** | 100% | 100% | - | - |
| **CEO Approval** | 100% (Sebastian Schaal) | 100% | - | - |
| **Business Outlook** | 93% positive | 93% positive | - | - |

Notes on reliability, and they matter a great deal here:

- The headline "27 reviews" from Glassdoor's public US-facing page and the "8 Bewertungen" from the logged-in German view return **identical sub-ratings**, which indicates the 27 figure aggregates review types (reviews plus interviews plus salary submissions) rather than distinct employee reviews. Either way the sample is far below the 20-review threshold for reliability.
- Reviews by job title: only **3 distinct titles** across the whole set. Visible reviewer roles are Customer Enablement Specialist, Senior Legal Specialist, Finance Operations Specialist, Product Manager, and one anonymous Munich employee. **Not a single engineering review exists.**
- Company profile: 1 office, "Softwareentwicklung" industry, 51 to 200 employees, private, HQ Munich, founded 2020 (Glassdoor's date reflects the SaaS pivot, not the 2017 registration).
- A 4.9 average across 8 reviews at an 88-person company is directionally positive but statistically thin, and the near-perfect scores plus 100%/100% recommend and CEO approval carry the usual small-startup selection bias.

### Kununu

Retrieved via Playwright over CDP (curl returned HTTP 405).

- **Overall score:** **4.8 / 5.0**
- **Recommendation rate (Weiterempfehlung):** **100%** (last 2 years)
- **Total reviews:** **40** (employee reviews: **32**, since 2018; plus 4 salary entries and 9 culture entries)
- **Sub-scores:** Karriere & Gehalt 4.6, Unternehmenskultur 4.8, Arbeitsumgebung 4.7, Vielfalt 5.0
- **Industry comparison:** 4.8 versus IT sector average of 4.0
- **Salary satisfaction:** 100% satisfied (based on 32 reviews)
- **Most-confirmed benefits:** Mitarbeiter-Events 84%, Homeoffice 84%, Flexible Arbeitszeiten 78%
- **Kununu Top Company:** **NO** badge displayed on the profile as of this research
- Salary entries on Kununu cover only HR Generalist (Ø €56,800, n=2) and Vertriebsmitarbeiter:in (Ø €86,700, n=2). **No engineering salaries.**

Kununu is the better dataset here (32 employee reviews versus Glassdoor's 8) and it agrees closely with Glassdoor. That consistency across two independent platforms is the strongest culture signal available.

### Blind / Teamblind

**NO PROFILE.** `teamblind.com/company/Luminovo` returns "Page not found". Blind's coverage of sub-100-person German startups is effectively nil. No data.

### Review Themes (2022-2026)

**Positives:**

- **Psychological safety, repeatedly and independently.** "Psychological safety ensures a vivid feedback and praise culture" (Finance Operations Specialist, 2022); "Psychological safety: Only started to appreciate it as soon as I experienced it, it's overall a very nice and safe working environment" (Product Manager, 2022); "gutes Arbeitsklima, psychology safety, es macht Spaß zu arbeiten" (Senior Legal Specialist, 2024). This is the single most consistent theme across four years.
- **Genuine remote flexibility.** "It doesn't really matter from where people work, as long as they are roughly in the same timezone. Allowed me to stay longer at holiday destinations and to work from there." Kununu confirms Homeoffice at 84% and flexible hours at 78%.
- **Fast product iteration.** "Never worked on a product where we iterated so quickly. On a daily basis, we bring new improvements live for our users."
- **Learning and growth.** "Angenehme Arbeitskultur mit einem Drang schnell zu lernen und zu wachsen" (Munich, Oct 2025). Glassdoor's own AI summary notes "no fixed budgets when it comes to things that will further your personal growth... just ask and we usually say yes".
- **International culture.** 20+ nationalities, 30+ remote locations. D&I scores 5.0 on both platforms.
- **High autonomy.** "High freedom to drive and to improve any aspect: everyone can (and does) bring up ideas."

**Negatives:**

- **Below-market compensation, named explicitly.** "woanders würde ich wahrscheinlich sehr viel mehr verdienen" (elsewhere I would probably earn a great deal more) - Senior Legal Specialist, Jan 2024. And from 2022: "There are various improvement opportunities... For example, salaries become more competitive." Comp & Benefits is the lowest Glassdoor sub-score at 4.3.
- **Chaotic and unstructured.** "Chaotic and sometimes unstructured" - former Customer Enablement Specialist, Berlin, Oct 2025. This is the only clearly negative review in the visible set and it is recent.
- **Thin office culture.** "Relativ geringe Office attendance trotz guter Lage" - Munich, Oct 2025. Also from the Glassdoor AI summary: remote-first "may lack typical startup energy".
- **Office quality.** "The location is cool, but I worked in nicer office spaces."

None of these overlap with the criteria's hard red flags. The compensation complaint is the one that matters materially, and it is corroborated by the published salary bands (Section 5).

### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | **None found.** 100% CEO approval on Glassdoor, Senior Management 4.8. Reviews describe "routine 1:1's with your supervisor, retrospectives, and insight hours". No negative leadership comment appears in any review across four years and two platforms. |
| 24/7 Work Expectation | **None found.** Company statement: "we work hard, but we also know you have a family, friends, hobbies, and a life outside the office." WLB 4.7. No overtime or availability complaints. |
| Internal Surveillance | **None found.** The opposite: fully remote with the sole constraint being CET ±2h. No monitoring mentions. |
| Fear-driven Management | **None found.** "Psychological safety" is the dominant review theme; one operating principle is "Foster productive conflict". |
| Communication Breakdown | **Minor, localised.** One former Berlin employee: "Chaotic and sometimes unstructured" (Oct 2025). Reads as growth-stage process immaturity, not a communication failure. |
| Unpaid Overtime | **None found.** No mentions on either platform. |
| Silent Firings | **None found.** No layoff or dismissal complaints. |
| Work-Life Balance issues | **None found.** WLB 4.7 on Glassdoor; Kununu Arbeitsumgebung 4.7. |

**Risk level: LOW.** The culture signal is unusually clean and consistent across Glassdoor (8 German reviews) and Kununu (32 employee reviews since 2018), spanning multiple functions and four years. The only dysfunction reported is (c) growth-stage process immaturity at team level, not systemic toxicity. The caveat is sample size and the absence of any engineering voice: not one review comes from a software engineer, so nothing here speaks to what the engineering org is actually like.

---

## Section 5: Compensation

### Salary Data

No engineering salary data exists for Luminovo on any platform. What follows is what does exist, plus the company's own published bands.

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| Luminovo (employer-published, Ashby) | Solutions Engineer - DACH, Munich | €73K - €107.7K | Equity offered, unquantified | Commission | €73K - €108K + commission | published band |
| Luminovo (employer-published, Ashby) | Business Development (BDR) DACH | €64K - €110K | Equity offered | Commission | €64K - €110K + commission | published band |
| Kununu | Vertriebsmitarbeiter:in | ~€86.7K | - | - | ~€86.7K | 2 |
| Kununu | Human Resource Generalist | ~€56.8K | - | - | ~€56.8K | 2 |
| Glassdoor | Director (US) | $176K - $263K | - | - | $176K - $263K | 1 |
| **Glassdoor - Software Engineer, Munich** | - | **no data** | - | - | - | **0** |
| **levels.fyi - Luminovo** | - | **no company profile** | - | - | - | **0** |

**Munich market reference (levels.fyi, Sept 2026):**

- Software Engineer, Munich: €68,423 to €105,481
- **Senior Software Engineer, Munich: €80,122 to €118,233** (median-to-75th band)

Luminovo has no levels.fyi profile at all. Its highest published German band tops out at **€107.7K including commission** for a revenue-carrying role. Engineering bands are not published, but the company states salary ranges are "determined based on market benchmarks and a comprehensive leveling framework" and applies them uniformly, so a Senior Software Engineer band is very unlikely to exceed the Solutions Engineer ceiling by much. That places the realistic engineering top end at roughly **€100K to €115K base**, against a Munich large-corporate senior bracket that starts around €95K to €110K base and reaches €130K to €160K total at profitable large employers (SAP, Google, Celonis, Apple, and similar).

The employee testimony is consistent with this reading: "woanders würde ich wahrscheinlich sehr viel mehr verdienen."

### Equity / Stock

"All full-time Luminerds receive strong and fair stock option packages" (company statement on Glassdoor). Structure is German **virtual or real stock options in a private, seed-stage GmbH**. Practical assessment:

- **No liquidity.** No IPO path, no secondary market, no announced acquisition interest. The last priced round was August 2022 at seed valuation; any options granted now would strike against a four-year-old or a fresh, likely flat or down, valuation.
- **German option taxation** is unfavourable relative to US RSUs; §19a EStG deferral helps but the shares remain illiquid.
- **Dilution risk is high.** With €13.5M raised, a Series A or a bridge would materially dilute existing option holders, and a down round could wipe out option value entirely.
- **Expected value should be treated as near zero** for planning purposes. This is not RSU compensation; it is a lottery ticket on an unfunded Series A.

### Verdict

**BELOW.** The published German bands cap at €107.7K for a commission-carrying revenue role, and no engineering band or data point exists at any level. Against the Munich Senior Software Engineer market (levels.fyi €80K to €118K, with profitable large employers well above that on total comp) Luminovo sits at or below the midpoint on base, with equity that carries no realistic near-term value. Two separate reviewers, in 2022 and 2024, flagged pay as the company's weak point. Marked **BELOW** with the caveat that the engineering-specific figure is **UNVERIFIED** because no such role is open and no such data exists.

---

## Section 6: AI/ML & Tech Stack Fit

### AI Strategy

Genuine and product-central, not marketing veneer, but narrow in scope.

- **Origin:** the company was founded in 2017 as an **AI engineering services** business (the Handelsregister purpose still says so) before pivoting in 2020 to SaaS. AI is in the founding DNA.
- **ElectronicsGPT** (launched January 2026): a free AI agent purpose-built for electronics procurement, answering component queries with technical data, alternates and supply chain information, "grounded in verifiable supply chain data". This is a retrieval-grounded domain agent, that is, applied LLM work with a strong RAG and data-quality component.
- **Core platform ML:** automated BOM ingestion and cleanup from messy customer files (document/table extraction, entity resolution, part-number matching against a component database), component availability and risk scoring, alternate-part suggestion, and cost/quote generation. The BOM matching and part-resolution problem is a real applied ML problem at meaningful scale.
- **Public research funding** corroborates the substance: four German grants totalling ~€1.34M, including **progressivKI** (€559,522), a BMWK-funded project on AI methods in electronics design, and **CEleRA** (€244,658).
- **Presented at Focus on PCB 2026** (May 2026) on AI reshaping PCBA quoting for European EMS providers.

The honest read: this is applied AI/ML in a narrow vertical (electronics supply chain data), heavy on data engineering, extraction and matching, with a recent LLM-agent layer. It is not platform/MLOps work and it is not research.

### Tech Stack

Derived from: an archived Luminovo job posting ("Product Engineer - Rust & React", now expired on DEVjobs.de), the company's own hiring page copy, and secondary aggregation of prior Luminovo engineering postings. **No public GitHub organisation or engineering blog with technical posts was found**, so the stack could not be corroborated from first-party engineering writing. Treat it as accurate as of the last engineering hiring cycle, not as of today.

| Category | Technologies |
|---|---|
| **Primary language(s)** | **Rust** (main monolith, actix-web); **TypeScript** (front end); **Python** (one stateless service only, FastAPI) |
| **AI/ML** | LLM agents (ElectronicsGPT), retrieval grounded on supply chain data, BOM extraction/matching and entity resolution. Specific frameworks not disclosed. |
| **Cloud** | **Azure** |
| **Infrastructure** | Kubernetes, Kubestack, Terraform, Flux (GitOps), Flagger (progressive delivery), garden.io (dev-on-Kubernetes) |
| **Data** | PostgreSQL (primary persistence), Redis (caching and queues) |
| **Front end** | React |
| **Observability** | Honeycomb, LogRocket |

### Current Open Roles

Verified live against the Ashby board (`jobs.ashbyhq.com/luminovo`) via Playwright over CDP on 2026-09-01, cross-checked against the company careers page and Glassdoor's job feed. All three sources agree.

**Open positions: 5. All five are in the "Revenue" department. Zero engineering roles.**

| Role | Division/Team | Level | Key Tech | Link |
|---|---|---|---|---|
| Business Development (BDR) DACH Remote | Revenue | IC | none (sales) | [Ashby](https://jobs.ashbyhq.com/luminovo) |
| Business Development (BDR) DACH - Spain | Revenue | IC | none (sales) | [Ashby](https://jobs.ashbyhq.com/luminovo) |
| Business Development (BDR) DACH (Berlin/Munich hybrid) | Revenue | IC | none (sales) | [Ashby](https://jobs.ashbyhq.com/luminovo) |
| Growth Marketing Intern / Working Student | Revenue | Intern | none | [Ashby](https://jobs.ashbyhq.com/luminovo) |
| Solutions Engineer - DACH (Munich/Berlin hybrid) | **Revenue** | IC, full-time | pre-sales technical, not product engineering | [Ashby](https://jobs.ashbyhq.com/luminovo) |

**Expired / closed engineering roles found (NOT applicable):**

- "Product Engineer - Rust & React", Munich - DEVjobs.de returns "Sorry, the job Product Engineer - Rust & React in Munich at Luminovo GmbH is no longer available."
- "Software Engineer" on the legacy `join.luminovo.com` board - the posting URL now redirects to the generic careers landing page; the posting itself is gone.

The Solutions Engineer role is a **pre-sales solutions/forward-deployed arrangement inside the Revenue org**, which the selection criteria explicitly exclude ("No consultant/forward-deployed/solution-engineer type of arrangement"). It is not a substitute.

**Verdict:** Rust-first product engineering (actix-web monolith) with React/TypeScript on the front end, PostgreSQL and Redis for data, Kubernetes/Terraform/Flux GitOps on **Azure**, and Honeycomb/LogRocket for observability. Python appears exactly once, in a single stateless FastAPI service. The AI/ML content is genuine applied work (BOM extraction and matching, component entity resolution, a retrieval-grounded LLM procurement agent) in a narrow vertical, and it is production engineering rather than research. Rust is the main language and Python is a rounding error in the stack. Separately, the entire question is currently moot, because **no engineering role of any kind is open**.

---

## Section 7: Language

- All job postings on the Ashby board are written in English, including the DACH-facing sales roles.
- Company-internal communication is English: 20+ nationalities across 30+ remote locations (Nairobi, Valencia, Verona, London, Amsterdam, Berlin, Cologne, Munich), operating principles published in English, Glassdoor and Kununu company blurbs in English.
- German is a **customer-facing** requirement in the DACH revenue roles (the market is German-speaking EMS/OEM manufacturers). This is a sales requirement, not an engineering one.
- Historic engineering postings ("Product Engineer - Rust & React") were English-language and did not require German.
- Reviews are written in both German and English, consistent with a genuinely bilingual but English-operating company.

**Verdict:** **PASS.** English is unambiguously the working language for engineering. German is required only for revenue-side, DACH-market-facing roles.

---

## Section 8: Stability

This is where the company fails, and it fails hard.

### Financial Position

From NorthData, Jahresabschluss as at **31.12.2024** (partial balance sheet visible without subscription, retrieved via Playwright over CDP):

| Aktiva (31.12.2024) | Amount |
|---|---|
| Immaterielle Vermögensgegenstände (intangibles) | €252,469 |
| Forderungen und sonstige Vermögensgegenstände (receivables) | €624,149 |
| **Kassenbestand, Guthaben bei Kreditinstituten (cash and bank)** | **€3,183,638** |
| **Total Aktiva** | **€4,195,156** |

- **Profitability:** negative in every year 2019 through 2024. The NorthData Gewinn chart's y-axis runs to **-€3,000K**, with the trough in that region. No revenue (Umsatz) figure is disclosed; as a small GmbH the company files an abbreviated Jahresabschluss.
- **Revenue:** undisclosed. Bottom-up: 300+ customers on a mid-market B2B SaaS platform at a plausible €20K to €30K ACV implies roughly **€6M to €9M ARR**, but this is an estimate, not a filed figure. Marked **UNVERIFIED**.
- **Capital raised:** €13.5M equity total (company's own figure), plus ~€1.34M in German public research grants.
- **Last disclosed round: August 2022.** Four years and one month ago as of this research. Registered share capital of €54,850 shows no post-2022 capital increase in the Handelsregister history.
- **Credit rating:** none (private, sub-€10M revenue).

### Financial Runway

**Cash figure used: €3,183,638, source NorthData Jahresabschluss, Stand 31.12.2024, observed 2026-09-01.** No 2025 filing was available at the time of research (German small-GmbH filings typically appear 12 to 18 months after year end, so FY2025 may surface in late 2026).

Online search found no analyst runway estimate, no post-2022 funding press release, no CMS or comparable legal advisory note for a Series A, and no Crunchbase or PitchBook entry for new capital (both returned 403; Tracxn and Dealroom were used instead and both show August 2022 as the most recent round).

**Bottom-up gross burn model** (headcount ~88, April 2026; geography-weighted since roughly a third of staff sit in lower-cost locations such as Nairobi, Valencia and Verona):

| Cost line | Annual estimate |
|---|---|
| Staff: ~88 employees × ~€92K blended fully-loaded cost | ~€8.1M |
| Cloud (Azure), data/component-database licensing, SaaS tooling | ~€0.9M |
| Sales, marketing, trade shows (Focus on PCB and similar), travel, retreats/LumiWeek | ~€0.8M |
| Munich and New York office, legal, finance, insurance | ~€0.4M |
| **Total gross burn** | **~€10.2M/year** |

| Revenue source | Est. annual inflow |
|---|---|
| SaaS subscription revenue (300+ customers, est. €20K to €30K ACV) | ~€6.0M to €9.0M |
| German public research grants (CEleRA, progressivKI, 2× HT: Hybrid; ~€1.34M spread over multi-year projects) | ~€0.3M |
| **Total revenue offset** | **~€6.3M to €9.3M/year** |

The residual net burn of roughly €1M to €4M/year brackets the observed FY2024 loss of approximately €3M, which is a reasonable consistency check on the model.

| Scenario | Net burn | Cash at hand (31.12.2024) | Runway from Jan 2025 | Next round needed by |
|---|---|---|---|---|
| Optimistic (ARR ~€9M, burn narrows to ~€1M/yr on continued growth) | €1.0M/yr | €3.18M | ~3.2 years | ~Q1 2028 |
| Base case (loss holds near the FY2024 level of ~€3M) | €3.0M/yr | €3.18M | **~1.1 years** | **~Q1 2026 (already past)** |
| Stress (ARR ~€6M, burn widens with the 2026 sales push) | €4.0M/yr | €3.18M | ~0.8 years | ~Q4 2025 (already past) |

**This is the central finding of the report.** Under the base case, the cash on the last filed balance sheet was exhausted around the first quarter of 2026. The company is demonstrably still operating in September 2026: it launched ElectronicsGPT in January 2026, presented at Focus on PCB in May 2026, and is actively hiring five revenue roles right now. So one of the following must be true, and **which one is unknown**:

1. It raised an **undisclosed** bridge or Series A during 2025 or 2026 (plausible; not every German round is announced, though a €10M+ round from this investor set almost certainly would have been).
2. It reached or approached **break-even** during 2025, which the aggressive 2026 revenue hiring would be consistent with (five of five openings are revenue roles, which is what a company pushing for profitable growth or preparing a Series A story does).
3. It is running on **debt, venture debt, or founder/investor bridge financing** not visible in the Handelsregister.

Option 2 is the most favourable reading and is genuinely plausible. But it is an inference, not a verified fact, and the alternative readings are materially worse. **This must be asked directly in any conversation with the company.**

### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| - | **No layoffs found.** | - | TrueUp, thelayoff.com, press searches and review platforms return nothing. No "silent firings" theme in 32 Kununu employee reviews or 8 Glassdoor reviews. |
| (2023, approx.) | **Acquisition, not a layoff:** Electronic Fellows GmbH merged into Luminovo GmbH (NorthData shows "⚭ Electronic Fellows GmbH", Verschmelzung; the entity is marked dissolved) | small | Headcount-additive. The Munich Startup article covering it now 404s. |

Headcount trend is flat to slightly up: 80+ (company site), 83 (one aggregator), ~88 (April 2026), "100 as of 30 June 2026" per one source. No contraction signal.

**Verdict:** **FAIL.** Loss-making in every year on record; last disclosed equity round over four years old; filed cash of €3.18M against a ~€3M annual loss implies the balance-sheet runway ran out around early 2026; and the current funding and profitability position cannot be verified from any public source. Against the criterion "at a mature, profitable company, with stable business (looking to commit long-term)", this is a clear fail. The absence of layoffs and the flat-to-growing headcount are genuine mitigants, and the possibility that the company reached break-even is real, but it is unverified.

---

## Section 9: Regulated Industry

Luminovo sells software **to** manufacturers in regulated end markets (medical devices, clean energy, automotive electronics), but it is not itself a regulated entity.

- No BaFin, DORA or Solvency II exposure (not financial services).
- No FDA or IVDR obligation (it does not make medical devices; its customers may, but Luminovo's BOM and quoting software is not in a device's safety chain).
- No ISO 26262 or EN 50128 functional-safety obligation on the product.
- No ITAR or defence classification.
- The realistic compliance surface is commercial: SOC 2 / ISO 27001-style customer security reviews (the platform has a dedicated "Security" page, which signals enterprise procurement questionnaires), GDPR, and export-control or supply-chain-provenance data handling in the SCRM add-on.

Practical engineering impact: normal B2B SaaS security and privacy overhead. No formal safety cases, no regulatory documentation burden, no certification-gated release cycles. Deployment velocity is unconstrained by regulators, and reviews confirm this ("On a daily basis, we bring new improvements live for our users").

**Verdict:** **PASS.** Low regulatory burden.

---

## Section 10: On-Call

**UNVERIFIED**, leaning acceptable.

- No engineering job posting is currently open, so no posting could be checked for on-call language.
- The archived "Product Engineer - Rust & React" posting is no longer retrievable in full; its cached summary made no mention of on-call, pager duty, or rotation.
- No review on Glassdoor or Kununu mentions on-call, pager, night work, weekend duty or availability expectations. Across 40 Kununu reviews and 8 Glassdoor reviews, WLB scores 4.7 and no reviewer raises availability, which would be unusual if a heavy rotation existed. But no reviewer is an engineer, so this is weak evidence.
- Product-nature inference: Luminovo is a **business-hours B2B SaaS** platform (quoting and procurement workflows for EMS and OEM buyers), not consumer-facing infrastructure and not a 24/7 transactional system. It runs on Kubernetes on Azure with Flux and Flagger for progressive delivery and Honeycomb for observability, which is a mature enough setup to imply some production ownership, but the business criticality does not demand round-the-clock coverage.
- Counter-consideration: at ~88 people with an engineering team likely in the 20 to 30 range, **any** production incident coverage falls on a small group. Small teams often have informal, unpaid, "you built it, you carry it" arrangements that are worse than a formal compensated rotation, and which never appear in job postings.

**Verdict:** **CAUTION (team-dependent), UNVERIFIED.** The product shape argues against a heavy rotation; the team size argues for informal ad-hoc coverage. Must be asked directly.

---

## Section 11: Interview Process

**NO DATA.** The Glassdoor interview page for Luminovo (`/Interview/Luminovo-Interview-Questions-E2039308.htm`) returns a 404 in both the German and US locales, which means **zero interview reviews have been submitted**. Kununu shows 40 total reviews against 32 employee reviews, implying ~8 applicant (Bewerber) reviews, but no aggregate difficulty or process metrics are exposed on the free profile.

| Metric | Value |
|---|---|
| Difficulty | **UNKNOWN** (no Glassdoor interview page exists) |
| Positive experience | **UNKNOWN** |
| Average duration | **UNKNOWN** |
| Rounds | **UNKNOWN** |

What can be inferred, with low confidence:

- The company publishes a "comprehensive leveling framework" and market-benchmarked bands, which suggests a structured, level-calibrated process rather than ad-hoc offers.
- Culture is heavily values-forward (six named operating principles: trust each other, foster productive conflict, have fun, focus on impact, be proactive, keep learning). Expect a substantial values or behavioural round.
- Historical engineering postings were for full-stack "Product Engineers", a generalist product-ownership framing, which typically maps to practical take-home or pair-programming exercises and system design rather than competitive-programming screens.
- At 88 people with no dedicated engineering-recruiting scale, a LeetCode-heavy gauntlet is unlikely.

**Assessment:** likely experience and design focused with a strong culture-fit component, not LeetCode-heavy. This is inference from company shape and published materials, not from any interview report, because none exist.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | **PASS.** Pure B2B SaaS, no hardware, no services revenue model. |
| Not consulting | **PASS** as an employer. Caveat: the only technical opening (Solutions Engineer) sits in the Revenue org and is exactly the forward-deployed/pre-sales shape the criteria exclude. |
| Profitable | **FAIL.** Loss-making every year 2019-2024, trough around -€3M. No disclosed revenue. |
| Employee count | **~88.** Seed-stage scale, not a mature company. |
| English-speaking | **PASS.** English throughout engineering and internal comms; German only for DACH revenue roles. |
| Local entity + engineering contracts | **PASS.** Luminovo GmbH, Amtsgericht München HRB 237378, Schellingstr. 29. HQ entity, software development named in the registered purpose, direct German employment. |
| Location / work model | Schellingstr. 29 (Maxvorstadt). Remote-first; CET ±2h is the only constraint. |
| Glassdoor | **4.9**, but only **8 German reviews** (27 aggregated), **zero from engineers**, 3 distinct job titles. Directionally excellent, statistically thin. |
| Kununu | **4.8 / 5.0**, 100% Weiterempfehlung, **32 employee reviews** since 2018 (the better dataset). No Top Company badge. |
| Salary | **BELOW.** Published German bands cap at €107.7K for a commission-carrying revenue role; no engineering data anywhere; no levels.fyi profile. Two reviewers name pay as the weak spot. Options are illiquid seed-stage paper. |
| AI/ML content | **PASS on substance.** Genuine applied AI: BOM extraction and component entity resolution, ElectronicsGPT retrieval agent (Jan 2026), ~€1.34M in German AI research grants. Narrow vertical, production not research. |
| Computer-language / Tech stack | **FAIL.** Rust-first (actix-web monolith) + React/TypeScript. Python is one stateless FastAPI service. Azure, Kubernetes, PostgreSQL, Redis, Flux/Flagger, Honeycomb. |
| No on-call | **UNVERIFIED / CAUTION.** No posting to check, no engineer reviews. Business-hours B2B SaaS argues against heavy rotation; a ~25-person eng team argues for informal coverage. |
| WLB / Stability | **Split.** WLB is excellent (4.7 both platforms, no red flags of any kind, LOW toxicity risk). Company stability is the opposite: **FAIL**. |
| Regulated industry | **PASS.** Sells into regulated end markets but carries no regulatory burden itself. Normal SaaS security and GDPR overhead only. |
| Review themes | Psychological safety (four years, multiple functions), real remote flexibility, fast iteration, high autonomy. Negatives: below-market pay (named twice), "chaotic and sometimes unstructured", thin office attendance. |
| **No engineering roles open** | **HARD BLOCKER.** All 5 openings are Revenue department. Prior Rust/React engineering postings are expired. |
| **Funding gap** | **HARD BLOCKER.** Last disclosed round Aug 2022. Filed cash €3.18M (31.12.2024) against ~€3M/yr loss implies balance-sheet runway ended ~Q1 2026. Current position unverifiable. |
| Interview process | **NO DATA.** Glassdoor interview page 404s; zero interview reviews exist. |

---

## Section 13: Verdict

**Recommendation: Monitor, do not pursue now.** Not a permanent exclusion, because the culture and location signals are genuinely strong and the AI/ML work is real, but there is nothing to apply to today and two of the hard criteria fail outright.

### Strengths

Luminovo has the best culture signal of almost anything in this research set, and unusually, it is corroborated. Kununu carries 32 employee reviews since 2018 at 4.8/5.0 with 100% Weiterempfehlung; Glassdoor independently shows 4.9 with 100% recommend and 100% CEO approval. "Psychological safety" recurs as the dominant theme across four years and across finance, legal, product and customer-facing roles. Toxic-leadership risk is LOW on every pattern checked, with no unpaid overtime, no surveillance, no 24/7 expectation, and no layoffs in the company's history. The German entity is clean and is the headquarters, not a sales shell, with software development written into the registered purpose. The office at Schellingstr. 29 is in Maxvorstadt, and the remote-first policy makes it optional. English is the working language without qualification. The AI/ML work is substantive rather than decorative: BOM extraction and component entity resolution are hard applied problems, ElectronicsGPT is a real retrieval-grounded agent shipped in January 2026, and roughly €1.34M in German public AI research grants corroborates the technical depth.

### Hard blockers

1. **There is no engineering job to apply for.** All five open positions are in the Revenue department: three business development roles, one growth marketing intern, and one Solutions Engineer. The Solutions Engineer role is not an alternative, it is a pre-sales, customer-facing arrangement inside the sales org, which the selection criteria exclude by name. The two engineering postings that once existed, "Product Engineer - Rust & React" and a legacy "Software Engineer", are both confirmed dead (DEVjobs.de returns "no longer available"; the join.luminovo.com URL redirects to a landing page). A company hiring five revenue people and zero engineers is telling you where its constraint is, and it is not engineering capacity.

2. **The company is not profitable and its funding position cannot be verified.** This is not a soft "startups burn money" caution. The last disclosed equity round closed in **August 2022, over four years ago**. The last filed balance sheet (31.12.2024, NorthData) shows **€3,183,638 in cash** and €4,195,156 in total assets, against a P&L that has been negative every year since 2019 with a trough near **-€3M**. On the base case that is roughly **13 months of runway from January 2025**, meaning the balance-sheet cash was gone around the first quarter of 2026. The company is plainly still trading, so it either raised quietly, hit break-even, or took on debt, and **no public source establishes which**. The criterion is "a mature, profitable company, with stable business, looking to commit long-term". Committing long-term to a company whose funding status is a matter of inference is the opposite of that.

3. **Rust is the main language, not Python.** The monolith is Rust on actix-web; the front end is React and TypeScript; Python appears in exactly one stateless FastAPI service. The criterion is Python as the main language, optionally combined with Go, Rust or TypeScript. Here the ratio is inverted: Rust is the job and Python is incidental. This one is a fail on the letter of the criterion even though the surrounding stack (Kubernetes, Terraform, PostgreSQL, Flux) is otherwise modern and appealing.

4. **Scale.** At ~88 employees, with an engineering org plausibly in the 20s, this is a seed-stage company by headcount as well as by funding stage. It does not meet "mature" on any reading.

### Secondary concerns

- **Compensation is below market and the company knows it.** Published German bands top out at €107.7K for a commission-carrying revenue role, against a Munich Senior Software Engineer market of €80K to €118K on levels.fyi and considerably higher total comp at profitable large employers. There is no engineering salary data point for Luminovo on Glassdoor, Kununu or levels.fyi, and no levels.fyi company profile at all. Two separate reviewers named pay directly: "woanders würde ich wahrscheinlich sehr viel mehr verdienen" (2024) and "salaries become more competitive" as a work-in-progress (2022). The equity offered is illiquid seed-stage option paper with no IPO path, a four-year-old last valuation, and high dilution risk; treat its expected value as near zero.
- **The review sample contains no engineers.** Only three distinct job titles appear across the entire Glassdoor set, and none is an engineering role. Everything known about the culture comes from finance, legal, product and customer-facing staff. The engineering org could be a different place and the data would not show it.
- **Zero interview data.** The Glassdoor interview page 404s, meaning not one interview review has ever been submitted.
- **On-call is unverifiable.** No engineering posting exists to check, and no engineer has reviewed the company. The business-hours B2B SaaS product shape argues against a heavy rotation, but a ~25-person engineering team supporting a Kubernetes platform on Azure will have production coverage of some kind, and small teams frequently run informal uncompensated arrangements.
- **One recent negative worth noting:** a former Berlin employee in October 2025 described the company as "chaotic and sometimes unstructured", and a Munich employee the same month noted low office attendance despite the good location. Neither is disqualifying; both are consistent with a growth-stage company that is remote-first and still building process.

### Recommendation

**Do not apply now; monitor the Ashby board.** There is literally no eligible role open, so the question is academic until that changes.

Revisit if **all three** of the following occur together: (a) a Rust/Python product or platform engineering role opens in Munich or Germany-remote, ideally one where the AI/ML and data-extraction work is central rather than the Rust monolith; (b) the company announces a Series A or otherwise publicly confirms profitability, closing the four-year funding gap; and (c) the posted band reaches at least €110K base for a senior level.

If contact ever does happen, three things must be established before anything else, because public sources cannot answer them: **the current cash and funding position** (has a round closed since August 2022, or is the company break-even), **the actual Python-versus-Rust split** in the specific team's day-to-day work, and **the on-call arrangement**, including whether it is formal and compensated or informal. Add the engineering-specific salary band, since none exists in any public dataset.

The culture here is genuinely good. That is not enough to offset a company that has been loss-making for six straight years, has not announced funding since 2022, has a balance sheet that on its own numbers should have run dry in early 2026, and is not hiring engineers.

---

## Sources

**Company and product**
- [Luminovo homepage](https://luminovo.com/)
- [Luminovo Impressum](https://luminovo.com/imprint)
- [Luminovo careers](https://luminovo.com/careers)
- [Luminovo careers (legacy join.com board / About)](https://join.luminovo.com/en/postings/938c3bfb-24c9-4fc5-bf54-1acf02ecfd10)
- [Luminovo Ashby job board](https://jobs.ashbyhq.com/luminovo)
- [Luminovo Ashby - Product Engineer (archived posting)](https://jobs.ashbyhq.com/luminovo/7b456029-ea41-47a0-8ff1-367019b7f7e4)
- [Luminovo - Procurement Intelligence platform](https://luminovo.com/platform/procurement-intelligence)
- [Luminovo - Risk Management for Electronics (SCRM)](https://luminovo.com/platform/risk)
- [Luminovo - BOM Management Software](https://luminovo.com/solutions/bom-management)
- [Luminovo - Solutions overview](https://luminovo.com/solutions)
- [Luminovo introduces ElectronicsGPT (press)](https://luminovo.com/about/press/luminovo-introduces-electronicsgpt)
- [Meet ElectronicsGPT: the first AI agent for electronics procurement (blog)](https://luminovo.com/resources/blog/meet-electronicsgpt-the-first-ai-agent-for-electronics-procurement)
- [Luminovo LinkedIn](https://www.linkedin.com/company/luminovo)

**Funding and financials**
- [Luminovo raises €11 million in seed funding (company blog, 18 Aug 2022)](https://luminovo.com/resources/blog/luminovo-raises-eu11-million-in-seed-funding-to-fix-the-broken-electronics-value-chain-with-transformative-software-suite)
- [Munich Startup - Luminovo secures 11 million euros](https://www.munich-startup.de/en/85193/luminovo-secures-11-million-euros/)
- [Munich Startup - Luminovo takes over Electronic Fellows](https://www.munich-startup.de/en/76774/luminovo-takes-over-electronic-fellows/) (now 404)
- [Silicon Canals - Munich SaaS startup Luminovo gets €11M boost](https://siliconcanals.com/munich-saas-startup-luminovo-gets-11m/)
- [Private Equity Wire - Luminovo raises €11m led by Chalfen Ventures](https://www.privateequitywire.co.uk/luminovo-raises-eu11m-seed-funding-round-led-chalfen-ventures/)
- [CMS - advises Luminovo on EUR 11 million seed financing](https://cms.law/en/deu/news-information/cms-advises-software-start-up-luminovo-on-eur-11-million-seed-financing-round)
- [Financial IT - Luminovo Raises €11 Million in Seed Round](https://financialit.net/news/fundraising-news/luminovo-raises-eu11-million-seed-round)
- [Tracxn - Luminovo funding rounds and investors](https://tracxn.com/d/companies/luminovo/__2coao2CKC1gJ4WlkgViVK2G1N07J2wwfcByoS__a49E/funding-and-investors)
- [Tracxn - Luminovo company profile](https://tracxn.com/d/companies/luminovo/__2coao2CKC1gJ4WlkgViVK2G1N07J2wwfcByoS__a49E)
- [Dealroom - Luminovo Artificial Intelligence GmbH](https://app.dealroom.co/companies/luminovo_artificial_intelligence_gmbh)
- [PitchBook - Luminovo profile](https://pitchbook.com/profiles/company/277351-57) (403, not retrieved)
- [Crunchbase - Luminovo](https://www.crunchbase.com/organization/luminovo) (403, not retrieved)
- [Raising.fi - Luminovo profile](https://raising.fi/company/luminovo)

**German company registry**
- [NorthData - Luminovo GmbH, München, HRB 237378](https://www.northdata.de/Luminovo+GmbH,+M%C3%BCnchen/HRB+237378) (retrieved via Playwright/CDP; source of the 31.12.2024 balance sheet, grant history, Geschäftsführer, Prokura, share capital, and the Electronic Fellows merger)
- [NorthData search - Luminovo](https://www.northdata.de/?query=Luminovo)

**Reviews**
- [Glassdoor - Luminovo reviews (global)](https://www.glassdoor.com/Reviews/Luminovo-Reviews-E2039308.htm) (403 via WebFetch; retrieved via Playwright/CDP)
- [Glassdoor DE - Luminovo Bewertungen](https://www.glassdoor.de/Bewertungen/Luminovo-Bewertungen-E2039308.htm) (retrieved via Playwright/CDP, logged-in session)
- [Glassdoor - Working at Luminovo (overview)](https://www.glassdoor.com/Overview/Working-at-Luminovo-EI_IE2039308.11,19.htm) (retrieved via Playwright/CDP)
- [Glassdoor - Luminovo reviews page 2](https://www.glassdoor.com/Reviews/Luminovo-Reviews-E2039308_P2.htm)
- [Glassdoor - Luminovo Munich office](https://www.glassdoor.com/Location/luminovo-ai-Munich-Location-EI_IE2039308.0,11_IL.12,18_IC4990924.htm)
- [Glassdoor - Luminovo interview questions](https://www.glassdoor.com/Interview/Luminovo-Interview-Questions-E2039308.htm) (404, no interview reviews exist)
- [Kununu - Luminovo GmbH](https://www.kununu.com/de/luminovo) (HTTP 405 via curl; retrieved via Playwright/CDP)
- [Teamblind - Luminovo](https://www.teamblind.com/company/Luminovo) (404, no profile)
- [Great Place to Work Deutschland](https://www.greatplacetowork.de/) (searched, no Luminovo entry)

**Compensation**
- [Glassdoor - Luminovo salaries](https://www.glassdoor.com/Salary/Luminovo-Salaries-E2039308.htm) (retrieved via Playwright/CDP; 1 US Director data point only)
- [Glassdoor - Luminovo Software Engineer salaries, Munich](https://www.glassdoor.com/Salary/luminovo-ai-Software-Engineer-Munich-Salaries-EJI_IE2039308.0,11_KO12,29_IL.30,36_IC4990924.htm) (404, no data)
- [levels.fyi - Senior Software Engineer, Munich](https://www.levels.fyi/t/software-engineer/levels/senior/locations/munich-metro-region)
- [levels.fyi - Software Engineer, Munich](https://www.levels.fyi/t/software-engineer/locations/munich-deu)
- [levels.fyi - Tech industry salaries, Munich](https://www.levels.fyi/industry/tech/locations/munich-deu)

**Tech stack and jobs**
- [DEVjobs.de - Product Engineer Rust & React at Luminovo GmbH](https://en.devjobs.de/job/49c390edb219166b7d5230d7b661e676) (confirmed expired)
- [DevJobsScanner - Luminovo developer job openings](https://www.devjobsscanner.com/company/luminovo/)
- [StartupSucht - Luminovo Rust & React posting](https://startupsucht.com/startup-job/startup-praktika-luminovo-muenchen-remote-tech-talent-wanted-rust-und-react)
- [SimplyHired DE - Luminovo Software Engineer](https://www.simplyhired.de/job/MuM0D_5gXfYeImJDuIqp6pYDR4jV9dOwkuatxDzpz_TosDagr_kWzA)

**Market and industry**
- [Atlas PCB - Focus on PCB 2026: AI-powered inspection and multi-agent systems](https://www.atlaspcb.com/news/news-focus-pcb-2026-europe-ai-manufacturing-inspection/)
- [Capterra - Luminovo pricing and alternatives](https://www.capterra.com/p/10022525/Luminovo/)
- [GetApp - Luminovo 2026 pricing, features, reviews](https://www.getapp.com/operations-management-software/a/luminovo/)
- [Software Advice - Luminovo reviews, demo and pricing](https://www.softwareadvice.com/product/521291-Luminovo/)
- [ZoomInfo - Luminovo GmbH overview](https://www.zoominfo.com/c/luminovo-gmbh/481377019)
- [LeadIQ - Luminovo company overview](https://leadiq.com/c/luminovo/5b63843536000076312c3cab)

**Location**
- [OpenStreetMap Overpass API - transit stops within 500m of Schellingstr. 29](https://overpass-api.de/api/interpreter)
