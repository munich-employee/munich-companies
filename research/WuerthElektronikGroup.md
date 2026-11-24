# Würth Elektronik Group - Full Research Report

_Researched: 2026-06-16_

> Würth Elektronik is one of Europe's largest manufacturers of **passive electronic components** (inductors, transformers, capacitors, connectors, EMC parts, PCBs). It is a hardware/electronics company, not a software-centric one. The Munich "Applied AI Developer" roles are real Python/applied-AI positions, but they are **internal enablement functions** (AI over engineering and product knowledge, internal process support) inside a components manufacturer, not product software engineering where software is the strategic differentiator. This is the company's primary fit problem; everything else (no embedded, no on-call, Python-primary, stable employer, decent reviews) is actually reasonable.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | Würth Elektronik eiSos roots from 1971; part of Würth Group (founded 1945) - **PASS** |
| Employees | ~7,300 (Würth Elektronik Group, worldwide); ~88,000 (Würth Group) - **PASS** |
| Revenue (FY2024) | ~€1.24B (Würth Elektronik); €20.2B (Würth Group) |
| Profitability | Profitable. Würth Group operating result FY2024 ~€940M (down from €1.46B in 2023, but 4th-highest ever) - **PASS** |
| Ownership | Private, family-owned (Würth family, Reinhold Würth). Not VC/PE-backed. |
| Software-centric | Electronic components manufacturer - **FAIL** (see assessment) |

**Key people:** Reinhold Würth (patriarch/chairman of the supervisory board of the Würth Group family trusts). Würth Elektronik eiSos is led by its own management; the eiSos division is the components business (EMC & Inductive Solutions).

**Business model:** Develops, manufactures and distributes passive and electromechanical electronic components and modules (inductors, transformers, RF, capacitors, varistors, connectors, power modules, sensors, wireless power transfer). Revenue comes from selling physical components to the electronics industry across 50 countries with 23 production sites. This is a hardware manufacturing and distribution business.

### Software-Centric Assessment

**FAIL.** The company's strategic differentiator is its component portfolio and manufacturing/distribution reach, not software. The Munich Hightech Innovation Center (HIC) explicitly works on component development (MagI³C power modules, custom transformers, wireless power transfer, energy harvesting, sensors), with "cloud & software services and big data" listed as supporting topics. The two open Munich AI roles confirm this orientation: both describe building AI solutions for **internal users** to make "engineering and product knowledge" more accessible and to support processes, combined with electrical-engineering (Elektrotechnik) domain logic. This is applied AI as an internal enabling function within a hardware company, not a software product line. Per criteria ("own product or service where differentiating software factor is integral to company's strategy") and the hardware-adjacent flag, this is the central mismatch.

It is **not** an embedded/C++ role, so the separate "exclude embedded" criterion is satisfied; the concern is strategic centrality of software, not the language of these specific roles.

---

## Section 2: Local Commercial Entity

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **Würth Elektronik eiSos GmbH & Co. KG** | Amtsgericht Stuttgart HRA 580801 | Max-Eyth-Str. 1, 74638 Waldenburg (Munich site: Clarita-Bernhard-Str. 9, 81249 München) | Development, production and distribution of electronic and electromechanical components |
| General partner | Würth Elektronik eiSos Verwaltungs-GmbH, Amtsgericht Stuttgart HRB 581033 | Waldenburg | Komplementär-GmbH |

**Verification:** The hiring entity for the Munich AI roles is **Würth Elektronik eiSos GmbH & Co. KG** directly (named verbatim on the job postings with the Munich Freiham address and a named in-house HR contact, Stefan Mager). This is a genuine German operating entity with engineering activity, not a PEO/EOR or a pure sales shell. Employment is a direct German Arbeitsvertrag. **Verdict: PASS.** (Registration retrieved via NorthData listing; entity confirmed on the job postings themselves via curl.)

---

## Section 3: Location

- **Office address:** Hightech Innovation Center (HIC), Clarita-Bernhard-Straße 9, 81249 München (Freiham, far west Munich). The Munich site relocated from Garching to Freiham; first phase houses ~250 staff.
- **Nearest public transit:** S-Bahn Freiham (S8).
- **Work model:** Hybrid. The Applied AI Developer / Data Engineer posting states "Möglichkeit, tageweise im Homeoffice oder Büro zu arbeiten" (option to work some days from home or office).

---

## Section 4: Reviews

**GPTW:** No Great Place to Work certification found for the German Würth Elektronik eiSos entity. A US subsidiary (Würth Electronics Midcom Inc.) held a GPTW certification (2023), and Würth International AG (Switzerland) appears on GPTW. No direct German-entity signal.

#### Glassdoor

Glassdoor aggregates "Würth Elektronik Group" (E609985). Filtered breakdowns by city/SWE were not separately available (limited review volume per filter); figures below are the global aggregate.

| Metric | Global (Würth Elektronik Group) |
|---|---|
| **Overall** | 4.0 (114 reviews) |
| **WLB** | 4.3 |
| **Culture & Values** | 4.2 |
| **Comp & Benefits** | 3.4 |
| **Career Opportunities** | 3.4 |
| **% Recommend** | 84% |

Country/City/SWE-specific filters: **insufficient review volume** to report reliably (treat global as directional). The separate "Würth" (parent, E12888) entity has 972 reviews but mixes the trade/fastener business and is not representative of the electronics engineering site.

**Verdict:** **BORDERLINE PASS.** Exactly 4.0 global meets the ">4.0" criterion only at the boundary (technically the criterion says "above 4.0", so 4.0 is a marginal miss on a strict reading). WLB and culture are strong; comp and career growth are the weak spots.

#### Kununu

Fetched via curl (slug `wuerth-elektronik`):
- **Overall score:** 3.8 / 5.0
- **Recommendation rate (Weiterempfehlung):** 74%
- **Total reviews:** 354 (employee reviews: 303)
- **Kununu Top Company:** Not confirmed

**Verdict:** **PASS.** 3.8 and 74%, on a healthy review volume.

#### Blind / Teamblind

No meaningful coverage. Blind skews to US tech; a German passive-components manufacturer has effectively no presence. Treat as no data.

#### Review Themes

**Positives:**
- Strong work-life balance (Glassdoor 4.3), stable family-owned employer
- Positive culture and team spirit ("Creating Together", "Teamgeist" emphasised heavily in postings)
- Job security, solid benefits (company pension, Job-Bike, Würth Akademie training, corporate benefits)

**Negatives:**
- Below-market compensation (comp rating 3.4) and limited career progression (3.4)
- Traditional/manufacturing corporate culture; pace and structures typical of a large family conglomerate
- No recurring hard red flags (no systemic toxic-leadership or 24/7 patterns surfaced)

#### Toxic Leadership Assessment

| Pattern | Würth Elektronik |
|---|---|
| Toxic leadership as pattern | Not evident |
| 24/7 work expectation | Not evident (strong WLB scores) |
| Surveillance culture | Not evident |
| Fear-driven management | Not evident |
| Employee autonomy | Moderate (large, structured organisation) |
| Communication breakdown | Not a recurring theme |
| Unpaid overtime | Not a recurring theme |

**Risk level: LOW.** Typical large-conglomerate bureaucracy and conservative pace, not systemic toxicity.

---

## Section 5: Compensation

#### levels.fyi Data

**No levels.fyi data** for Würth Elektronik (the company does not have a tech-compensation presence on levels.fyi). Using Glassdoor as the source instead.

- Glassdoor comp & benefits rating: 3.4/5 (the weakest dimension).
- Würth Elektronik Group salaries in Germany span roughly €50K (junior/support) to ~€180K (senior sales engineer); these AI/data roles are not separately benchmarked with reliable volume.
- The Munich AI postings disclose no salary band.

#### Equity / Stock

**None.** Privately held family company; no RSUs, ESPP, or options. Compensation is base salary plus standard German benefits (vermögenswirksame Leistungen, betriebliche Altersvorsorge).

#### Verdict

**BORDERLINE FAIL / UNVERIFIED.** No transparent data for the specific role, but the 3.4 comp rating, manufacturing-sector pay norms, and absence of equity strongly suggest compensation below Munich product-tech/AI market rates (where staff/senior AI engineers at software-centric firms reach materially higher total comp). Would need to be verified directly in interview.

---

## Section 6: AI/ML & Tech Stack Fit

#### AI Strategy

Würth Elektronik is building an internal Applied AI / Data Engineering & Science function (a Teamlead role and two developer roles are open). The stated mission is pragmatic, internal-facing applied AI: making engineering and product knowledge more accessible to internal users, supporting processes, and combining data architecture with electrical-engineering business logic. This reads as internal LLM/RAG + data-platform enablement, not a customer-facing AI product and not research. There is no published external AI product roadmap.

#### Tech Stack (from the Munich job postings)

| Category | Technologies |
|---|---|
| **Primary language(s)** | Python (explicitly "sehr gute Python-Kenntnisse"), SQL |
| **AI/ML** | Applied AI / ML methods, prototyping to production; (specific frameworks not named) |
| **Cloud** | Not named in postings; "deployment-orientierte Implementierung", APIs |
| **Infrastructure** | Version control, testing, APIs, data pipelines, integrations |
| **Data** | Data pipelines, transformations, system integrations, enterprise data architecture |
| **Other** | Electrical-engineering domain (Elektrotechnik) context |

#### Current Open Roles (Munich, verified active via curl, 2026-06-16)

| Role | Division/Team | Level | Key Tech | Fit? |
|---|---|---|---|---|
| Applied AI Developer (m/w/d) [j5137] | Applied AI (eiSos, Munich) | Experienced (Senior-ish) | Python, applied AI, APIs, deployment | **Partial** |
| Applied AI Developer / Data Engineer (m/w/d) [j5139] | Applied AI / Data Eng (eiSos, Munich) | Experienced | Python, SQL, data pipelines, ML | **Partial** |
| Teamlead Applied Data Engineering & Science [j5046] | Applied Data (Munich) | Lead | (people leadership) | **Exclude** (German "verhandlungssicher" required; primarily disciplinary leadership, not hands-on) |

Both developer roles are non-embedded, Python-primary, applied-AI, no on-call. They are rated **Partial** rather than Strong because the work is internal-enablement AI inside a hardware company (not product software engineering) and is framed around electrical-engineering domain support.

**Verdict:** **BORDERLINE.** The stack is genuinely Python-centric applied AI / data engineering with modern practices (version control, testing, APIs, deployment). The fit problem is not the technology but the context: this is applied AI as an internal cost-center function within an electronic-components manufacturer, not production software where software is the strategic product. It is materially better aligned than a typical Würth hardware role, but well short of an AI/ML product company.

---

## Section 7: Language

Mixed by role:
- **Applied AI Developer / Data Engineer (j5139):** "Sehr gutes Englisch in Wort und Schrift; Deutsch ist für die Zusammenarbeit mit internen Stakeholdern von Vorteil." English required, German advantageous. **PASS.**
- **Applied AI Developer (j5137):** Posting is German; no explicit English-only path stated, communication is with internal/electrical-engineering stakeholders. **CONDITIONAL.**
- **Teamlead (j5046):** "Verhandlungssichere Deutschkenntnisse" required. **FAIL.**

**Verdict:** **CONDITIONAL PASS.** The Data Engineer variant (j5139) is English-friendly; the broader environment is German-first (all postings authored in German, internal stakeholders in a German manufacturing firm), so day-to-day German is realistically expected over time.

---

## Section 8: Stability

#### Financial Position

Very strong. Würth Group: FY2024 sales €20.2B (vs €20.4B 2023), operating result ~€940M (down from €1.46B but still 4th-highest ever), consistently profitable, family-owned with conservative financing (Würth Finance, investment-grade profile historically). Würth Elektronik division: ~€1.24B revenue. No VC dependency, no liquidity risk. Financial runway modeling not applicable (profitable, privately held, deep parent backing).

#### Layoffs

No mass layoffs identified for Würth Elektronik. The Würth Group flagged a sharp profit drop for 2024 amid weak industrial demand and signaled cost discipline, but no large-scale redundancy program at the electronics division surfaced. **No layoffs on record.**

**Verdict:** **STRONG PASS.** One of the most stable employers in scope: large, profitable, family-owned, no funding risk.

---

## Section 9: Regulated Industry

Not a heavily regulated employer for these roles. Component manufacturing carries product-compliance/quality regimes (RoHS, automotive AEC-Q / IATF 16949 on the manufacturing side), but the internal Applied AI/data roles are not safety-critical software under FDA/BaFin/EN-50128-type regimes. Low regulatory burden for the candidate's role.

**Verdict:** **PASS** (low regulatory burden).

---

## Section 10: On-Call

No on-call mentioned in any of the three Munich postings. The roles are internal applied-AI/data development (knowledge access, process support, data pipelines), not 24/7 SaaS infrastructure, SRE, or NOC/MDR. On-call is not expected.

**Verdict:** **PASS.**

---

## Section 11: Interview Process

| Metric | Value |
|---|---|
| Difficulty | UNKNOWN (insufficient Glassdoor interview data for the electronics entity) |
| Positive experience | UNKNOWN |
| Average duration | UNKNOWN |
| Rounds | Not disclosed; postings mention a **"Probetag"** (trial day) as part of the application process |

The notable feature is a paid/structured trial day ("Probetag zum Kennenlernen des Jobs") plus comprehensive onboarding. This suggests an experience- and fit-focused, practical process rather than a LeetCode gauntlet. Specifics are unverified.

---

## Section 12: Summary Assessment

| Criterion | Result |
|---|---|
| Software-centric | **FAIL** (electronic-components manufacturer; AI roles are internal enablement, not product software) |
| Not consulting | **PASS** (own products) |
| Profitable | **PASS** (Würth Group ~€940M operating result FY2024; ~€20B revenue; family-owned, no VC) |
| Employee count | **PASS** (~7,300 Würth Elektronik; ~88,000 Würth Group) |
| English-speaking | **CONDITIONAL PASS** (j5139 English-required/German-advantageous; environment German-first) |
| Local entity + engineering contracts | **PASS** (Würth Elektronik eiSos GmbH & Co. KG, HRA 580801 Stuttgart; direct hire) |
| Location / work model | Freiham (far west); hybrid |
| Glassdoor | **BORDERLINE** (4.0 global; exactly at/just under the ">4.0" line; city/SWE filters too sparse) |
| Kununu | **PASS** (3.8 score, 74% recommend, 354 reviews) |
| Salary | **BORDERLINE FAIL / UNVERIFIED** (comp rating 3.4, no equity, manufacturing pay norms; likely below Munich AI market) |
| AI/ML content | **BORDERLINE PASS** (genuine applied AI/data, but internal-enablement scope) |
| Computer-language-primary | **PASS** (Python primary, SQL) |
| No on-call | **PASS** |
| WLB / Stability | **PASS** (strong WLB 4.3; very stable employer) |
| Regulated industry | **PASS** (low burden for these roles) |
| Toxic leadership risk | **LOW** |
| Embedded excluded | **PASS** (these are Python AI roles, not C/C++ embedded) |

---

## Section 13: Verdict

**Overall recommendation: Monitor / weak fit. Not an active-pursue, but not a hard exclude either.**

**Strengths.** This is a financially rock-solid, family-owned employer with strong work-life balance, low toxicity risk, a direct German contract through a real engineering entity, no on-call, and (unusually for this company) genuinely Python-centric applied-AI/data-engineering openings in Munich that are explicitly non-embedded. Culture and WLB scores are good, and one role (j5139) is English-required with German only advantageous. Kununu passes cleanly; stability is best-in-class.

**Hard blockers (numbered):**
1. **Not software-centric.** Würth Elektronik is a passive-electronic-components manufacturer; its strategic differentiator is hardware, not software. The Munich AI roles are internal enablement (AI over engineering/product knowledge, process support) inside that hardware business, not product software engineering. This fails the core criteria requirement that the differentiating software factor be integral to company strategy, and matches the project's hardware-adjacent disqualifier.

**Secondary concerns (not individually disqualifying, but additive):**
- **Compensation:** comp rating 3.4, no equity, manufacturing pay norms; realistically below Munich product-AI market for a staff/senior engineer.
- **Glassdoor 4.0** sits exactly at the boundary of the ">4.0" criterion.
- **Language/career:** German-first environment and modest career-progression scores (3.4); the strongest-fit role (Teamlead) requires fluent German and is people-leadership, not hands-on.

**Recommendation.** The company comes with stability, strong WLB, and a low-pressure applied-AI/data role over comp and software-product centrality. For a positive application recommendation, two things would need to change: confirmation in interview that the comp band reaches Munich senior-AI levels, and confidence that the role is hands-on production AI engineering with real scope rather than internal tooling support. As it stands, it is a weaker fit than software-product employers already in the pipeline.

---

## Section 14: Sources

- [Würth Elektronik official site](https://www.we-online.com/en/)
- [Würth Elektronik company profile (ConnectorSupplier)](https://connectorsupplier.com/company-profile/connector-manufacturers/wurth-elektronik/)
- [Würth Elektronik Group on LinkedIn](https://www.linkedin.com/company/wuerth-elektronik-group)
- [Würth Elektronik eiSos on NorthData (HRA 580801)](https://www.northdata.com/W%C3%BCrth%20Elektronik%20eiSos%20GmbH%20&%20Co%C2%B7%20KG,%20Waldenburg/Amtsgericht%20Stuttgart%20HRA%20580801)
- [Würth Elektronik imprint](https://www.we-online.com/en/service/imprint)
- [Würth Elektronik Munich location page](https://www.we-online.com/en/company/locations/muenchen)
- [Würth Elektronik moves into HIC Freiham (press)](https://www.we-online.com/en/news-center/press?d=move-to-hic-freiham)
- [Würth Elektronik opens Design & Application Center Munich (PresseBox)](https://www.pressebox.de/pressemitteilung/wuerth-elektronik-eisos-gmbh-co-kg/Wuerth-Elektronik-eroeffnet-Electronic-Design-Application-Center-in-Muenchen/boxid/623841)
- [Careers portal](https://jobs.we-online.com/)
- [Applied AI Developer (j5137)](https://jobs.we-online.com/Applied-AI-Developer-mwd-de-j5137.html)
- [Applied AI Developer / Data Engineer (j5139)](https://jobs.we-online.com/Applied-AI-Developer-mwd-de-j5139.html)
- [Teamlead Applied Data Engineering & Science (j5046)](https://jobs.we-online.com/Teamlead-Applied-Data-Engineering-Science-mwd-de-j5046.html)
- [Glassdoor - Würth Elektronik Group reviews](https://glassdoor.com/Reviews/W%C3%BCrth-Elektronik-Reviews-E609985.htm)
- [Glassdoor - Würth Elektronik Germany salaries](https://www.glassdoor.com/Salary/W%C3%BCrth-Elektronik-Germany-Salaries-EI_IE609985.0,16_IL.17,24_IN96_IP3.htm)
- [Kununu - Würth Elektronik](https://www.kununu.com/de/wuerth-elektronik)
- [Würth Group FY2024 sales (news.wuerth.com)](https://news.wuerth.com/wuerth-group-sales-in-the-2024-fiscal-year-almost-at-previous-years-level/)
- [Würth family-owned profit drop (Yahoo Finance/Reuters)](https://finance.yahoo.com/news/german-family-owned-fastener-giant-112726228.html)
- [Würth on Wikipedia](https://en.wikipedia.org/wiki/W%C3%BCrth)
- [Würth Elektronik eiSos on Bloomberg](https://www.bloomberg.com/profile/company/7150077Z:GR)
- [Würth Elektronik on Elektor Magazine](https://www.elektormagazine.com/WuerthElektronik)
