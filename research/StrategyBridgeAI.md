# StrategyBridgeAI - Full Research Report

_Researched: 2026-10-15_

> **Critical Disqualifiers**
> 1. **Not mature, not profitable.** Founded in 2022 with about 25-30 staff, the company has raised only one disclosed round: a seven-figure pre-seed in December 2024. Its two open LinkedIn roles (Oct 2026) are "Founder's Associate | Fundraising", and the posting says the hire's "first and most important topic is our next financing round". The company is mid-fundraise with an unknown runway.
> 2. **No senior engineering role open.** The only engineering posting found ("Backend Engineer - Fintech", Munich hybrid, LinkedIn 4466082626) is **CLOSED**. It was also pitched at "at least 2 years of professional experience", not at Senior/Staff level.
> 3. **No employer reviews worth the name.** Glassdoor has 0 reviews and one interview report, rated negative. Kununu has 6 reviews, mostly from interns, all written between April 2024 and January 2025.
>
> The full report follows for completeness.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 2022 (4 years) |
| Employees | ~25-30 (About page: "25+ experts"; Oct 2026 job ads: "a focused team of 30", "rund 30 ambitionierte Menschen"; LinkedIn API staffCount 29, +45% employee growth; "knapp 20" in Mar 2025 per VC Magazin). LinkedIn function split: Business Development 12, Engineering 6, Finance 4, Marketing 3, Sales 3 |
| Revenue (FY2025) | Not disclosed. Self-reported traction: "100 Clients. Market Leader in DACH" (2025), "2K+ users", and a fivefold customer base in the 12 months before Dec 2024 |
| Profitability | Not disclosed. Pre-seed funded, actively fundraising, receives the R&D tax subsidy (Forschungszulage). Almost certainly loss-making - **FAIL** |
| Ownership | Private, founder-controlled, VC-backed (D11Z. Ventures, Bayern Kapital, business angels, family offices) |
| Software-centric | SaaS platform for company and market analysis (database, AI longlists, outside-in analyses, market reports) - **PASS** (see Consulting-Adjacency below) |

### Key People

- **Deniz Schütz**, Co-Founder & CEO. Former investment banker, who described "bootstrapping without a safety net" in an April 2026 company podcast.
- **Louis (Alexander) Flach**, Co-Founder, COO/CFO. Former M&A project manager at the same bank.
- **Original CTO: Jan Scheffler** (ex-Google Software Engineer, Munich, 2019-2021). Listed as "CTO" next to the two co-founders on the July 2022 website (Wayback). His LinkedIn (`/in/jschfflr`) gives CTO from Oct 2021 to Apr 2024, held alongside a part-time Senior SWE job at COM.lounge (Dec 2021 to Dec 2023). He has been founder of PEQY (AI code review for AL / Business Central, Münster) since Apr 2024. He was never a managing director, and his shareholding is unknown. The company podcast article says the technical co-founder left "after the first year", which does not match his LinkedIn dates; possibly his role became part-time or nominal first. No successor CTO is named on the website or in the press.
- NorthData's shareholder network shows two holding companies, TripleHelix Capital UG and Godman Capital UG, holding 46% and 30.7% (presumably the founders' holding vehicles), so the founders retain control.

### Funding History

| Date | Round | Amount | Investors | Valuation |
|---|---|---|---|---|
| 2022-2024 | Bootstrapped | - | Founders | - |
| Dec 2024 | Pre-seed (oversubscribed) | "Seven-figure", undisclosed | D11Z. Ventures (lead), Bayern Kapital, angels incl. a DealCircle co-founder | Undisclosed. Share capital rose from €25,000 to €32,608 in Nov 2024 (+30.4% new shares, ~23% dilution). At €1-2M raised, that implies roughly €4.5-9M post-money (derived, not reported) |
| Jan 2026 | State aid | €100,000-500,000 | BMF R&D tax credit (Forschungszulage) | - |
| 2026 (in progress) | Next round (likely seed) | Unknown | Being prepared; the Founder's Associate role owns deck, data room and investor pipeline | - |

### Business Model

The company sells B2B SaaS seat and enterprise subscriptions to M&A advisors, Big 4 / audit and valuation firms, PE funds, corporate M&A teams and banks. Named client testimonials come from mid-market advisory and audit firms in DACH. It says it is "Recommended by IDW" (the German auditors' institute), and it won Best Solution in Corporate Banking and Best Solution Overall (LBBW Prize) at FinTraWorld 2026. It aggregates data on "50M companies" from public registers, websites and licensed business databases, and layers deterministic financial logic, ML and LLMs on top.

### Consulting-Adjacency Assessment

- **Registered purpose** explicitly includes consulting: "...sowie die Durchführung von Dienstleistungen jeglicher Art auf dem Gebiet der Informationstechnologie und der **Unternehmensberatung, insbesondere Managementberatung, Strategieberatung und Technologieberatung**."
- **History:** "Deniz and Louis began by solving problems manually, close to client needs". Early analyses were largely produced by hand before being automated (podcast article). A 2024 Kununu review mentions "transparent service delivery processes for clients".
- **Today:** the website, product names (Database, Longlist, Hawk Eye, Eagle Scope) and the engineering JD all describe a product company. Engineers build the company's own platform, not client deliverables. The Backend JD asks engineers to "collaborate directly with clients... and turn them into features", which is a product-discovery duty in a small startup, not billable work.
- **Assessment:** product company with a consulting origin. Not consulting-adjacent for engineers, but the registered purpose leaves room for analysis-as-a-service work.

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **StrategyBridgeAI GmbH** | Amtsgericht München HRB 273777 (EUID DED2601V.HRB273777), VAT DE351190245 | Am Kartoffelgarten 14, 81671 München (registered); office WERK1, Friedenstraße 6a, 81671 München | "Die Entwicklung und der Vertrieb von Software zur datenbasierten Unternehmensanalyse, sowie die Durchführung von Dienstleistungen jeglicher Art auf dem Gebiet der Informationstechnologie und der Unternehmensberatung, insbesondere Managementberatung, Strategieberatung und Technologieberatung." |

The registered purpose starts with **development** of software, so it is an engineering entity, not a sales shell. Managing directors are Deniz Schütz and Louis Alexander Flach. Share capital is €32,608 after the Nov 2024 capital increase, and the address changed in Jan 2025. Both addresses are in the Werksviertel. Nominatim confirms Am Kartoffelgarten 14 and Friedenstraße 6a are about 300 m apart in Werksviertel / Berg am Laim. This is the only entity: it is a Munich GmbH and hires directly, with a second office in Heilbronn (Campus Founders). The 2024 Kununu reviews mention a "team spread across different parts of the EU", so some staff may be contractors abroad. The Munich engineering role was advertised as a direct, full-time hire.

**Verdict:** **PASS with CAUTION.** The engineering entity is real, but the registered purpose also covers management and strategy consulting.

---

## Section 3: Office Location

- **Office address:** WERK1 Startup Hub, Friedenstraße 6a, 81671 München (Werksviertel, Berg am Laim), directly east of Ostbahnhof. Nominatim: 48.12419, 11.60386. WERK1 is a shared startup hub (coworking-style), not a dedicated company office.
- **Work model:** **Hybrid**, both on the LinkedIn tag and in the JD text ("Setup: Munich, hybrid. Modern office..."). The number of office days is not stated: **UNVERIFIED**. Kununu reviews from 2024 describe "100% homeoffice möglich", but that predates the Munich office.

---

## Section 4: Reviews

**GPTW:** No Great Place to Work Germany certification or list entry found.

### Glassdoor

Retrieved via Chromium/CDP (logged-in profile). Employer ID E9886029, profile "1 to 50 employees", HQ München.

| Metric | Global | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | No reviews (0) | No reviews | No reviews | No reviews |
| **WLB** | - | - | - | - |
| **Culture & Values** | - | - | - | - |
| **Comp & Benefits** | - | - | - | - |
| **Career Opportunities** | - | - | - | - |
| **Diversity & Inclusion** | - | - | - | - |
| **% Recommend** | - | - | - | - |
| **CEO Approval** | - | - | - | - |
| **Business Outlook** | - | - | - | - |

The profile has no reviews and no salary entries (the search page counts "1 salary", but the salaries tab shows "0 job titles"). It has **one interview report**: Frontend Engineer, interview Aug 2026, posted 8 Sept 2026, difficulty "average" (3/5), **negative experience, no offer**. The review text was extracted from the page's embedded JSON via CDP, since it isn't rendered as visible text:

> "Had a 10 minutes technical interview with some marketing guy. Very impersonal and right to the business. On the first email they mention there will be a short technical interview and if it goes well then you earn the right to have the first HR talk. It was very impersonal and the guy just ask the AI for the questions and answers and when you answer he compares you answer to what the AI told him. How can you have a tech conversation with some marketing/product guy. [...] This is a company full of red flags from the moment the send you the email."

Interview questions: "What is a link list? what is the O of search in an array? what is the O of document.getElementById("x"); and of document.getQuerySelector("x")".

### Other sources checked

| Source | Result | Method |
|---|---|---|
| Kununu (second slug `strategybridgeai1`) | Same 6 reviews. Sub-scores: Karriere & Gehalt 4.6, Unternehmenskultur 4.7, Arbeitsumgebung 4.7, Vielfalt 4.8. Benefits confirmed: flexible hours 67%, home office 67%, employee participation 50% | CDP |
| Kununu Kulturkompass | 3 culture ratings (all July 2024 or earlier): "modern", in line with the IT average. 100% picked "Mitarbeitenden Freiräume geben", "Neue Dinge ausprobieren", "Kollegen helfen", "Andere Meinungen respektieren". The WLB comment comes from the one IT employee (July 2024) | CDP |
| Indeed | No company page (404) | CDP |
| Teamblind, levels.fyi, Comparably, Welcome to the Jungle, Reddit | Nothing found | curl / web search |
| LinkedIn People tab | 29 staff (company API), 28 associated members: **Business Development 12, Engineering 6, Finance 4, Marketing 3, Sales 3**. 20 in Greater Munich. Top schools: TUM School of Management, LMU, Bocconi, Frankfurt School. Top skills: M&A, Excel, PowerPoint | CDP |
| LinkedIn past employees | ~25 people list StrategyBridgeAI as a past company. Most are students or business graduates (M&A, finance), so the company leans heavily on interns and working students. About 9 had engineering or data roles: ML Engineer, Product Engineer (full-stack), Java/Python knowledge-graph developer, Software Developer, Data Scientist, Applied AI Engineer, UX/UI, Quant Dev, AI Engineer intern. Individual tenures are not visible (all profiles show as out-of-network "LinkedIn Member"), so **engineering attrition is UNVERIFIED** | CDP |
| LinkedIn posts (content search) | Only marketing and conference posts (CEO at the Merger Integration Management Forum, Amsterdam, Oct 2026). No employee posts about culture, farewells or team life found | CDP |
| VC Magazin case study (Mar 2025) | Team "knapp 20-köpfig", having "nahezu verdoppelt" in the preceding months. "Wir wollen bestenfalls 2026 Profitabilität erreichen, priorisieren aktuell aber Wachstum." The founders hold the majority | WebFetch |
| Podcast "Hope Is Not a Strategy" (Jun 2026, CEO guest) | On hiring: "Two engineers with AI are still faster than one engineer with AI", "our data engineering team is obviously growing", "your sales team still needs to grow". Nothing about working hours or culture | Podscan transcript via CDP |
| Company podcast article "All In" (Apr 2026) | The CEO describes February 2026 as one of his most overloaded periods. The company's "existence was at risk" at points. The technical co-founder left after the first year | WebFetch |
| Data Engineer internship ad (workingstudentjobs.de) | €3,000/month, hybrid. Same culture copy as the Backend JD; "strong interns are the first people we talk to about a full-time role" | WebFetch |

### Kununu

Retrieved via Chromium/CDP (curl got HTTP 405). Slug: `strategybridgeai`.

- **Overall score:** 4.7 / 5.0
- **Recommendation rate (Weiterempfehlung):** 100%
- **Total reviews:** 6 (all employee reviews, no applicant reviews)
- **Kununu Top Company:** NO

**Quality caveat:** 5 of the 6 reviews are from interns or working students in M&A / finance. One is from an employee in IT. They were posted in a tight cluster (April 2024 x2, May 2024, July 2024, October 2024, January 2025), and there have been none since the team grew to ~30. Their tone is uniformly glowing and generic ("I have nothing to complain about", "Ich hab nichts auszusetzen"), which is typical of solicited reviews. The IT review, for example, is boilerplate praise in every category. **Not reliable** for judging the engineering culture.

### Blind / Teamblind

`teamblind.com/company/StrategyBridgeAI/` returns HTTP 404, so there is no company page and no data.

### Review Themes (2024-2026)

**Positives:**
- Responsibility from day one ("Möglichkeit, von Tag 1 an Verantwortung zu übernehmen", "take on significant responsibilities").
- Open, friendly communication ("open, supportive communication culture", "offenen und freundlichen Umgang im Team").
- Supportive managers ("My managers were always helpful").
- Flexible hours and remote work (2024: "100% homeoffice möglich").
- Clients praise the team's speed and service ("very strong service mindset with very fast response times").

**Negatives:**
- Almost no signal: no engineer reviews, nothing written after January 2025.
- The single Glassdoor interview report (Frontend Engineer, Aug 2026) describes a 10-minute technical screen run by a "marketing/product guy" who read the questions and expected answers from ChatGPT. A technical pass was required before even an HR call ("you earn the right to have the first HR talk"). The candidate calls the company "full of red flags". This is one data point, but it fits the staffing mix: 6 engineers against 12 business-development staff, and no named CTO.
- Business-heavy, junior-heavy organisation: most current and past staff are M&A/finance graduates, interns and working students. The engineering team is ~6 people, without a visible engineering leader since the technical co-founder left.
- Missed profitability target: in March 2025 the company aimed for profitability "bestenfalls 2026". By Oct 2026 it is instead preparing a new funding round.
- The CEO describes extreme founder load in his own podcast. February 2026 was "one of his most overloaded periods", with sales, hiring, internationalisation, onboarding and personal challenges coinciding, and the company's "existence was at risk" at points. The engineering JD asks for "the motivation and ownership of a founder" and advertises "one of the steepest [learning curves] you'll find in Germany". In a 30-person startup, this usually means long hours (**WLB risk**, inferred, not reviewed).

### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | No evidence. Reviews praise empathetic, helpful supervisors, but those are interns writing in 2024. |
| 24/7 Work Expectation | Unverified risk. "Motivation and ownership of a founder", "steepest learning curve"; the CEO publicly describes overload. |
| Internal Surveillance | No evidence. |
| Fear-driven Management | No evidence. |
| Communication Breakdown | Mixed. Internal reviews (2024) praise open communication. The 2026 interview report describes an impersonal, ChatGPT-scripted technical screen run by non-engineers. |
| Unpaid Overtime | Unverified. No data. Startup-typical all-in contracts likely. |
| Silent Firings | No data. No works council (see Section 8). The technical co-founder left after year one. |
| Work-Life Balance issues | Unverified risk. The only WLB comment (2024) is positive, but it predates the growth and fundraising phase. |

**Risk level: MODERATE (low evidence).** There is no sign of systemic toxicity, but also almost no data from engineers or from after January 2025. Every employee review is from the ~10-person phase and mostly from interns. The real risk is not toxicity but early-stage startup intensity during a fundraise (pattern c: localized, founder-driven pressure). Add to that a business-led organisation where engineering is a small minority without a named technical leader, which the one recent candidate report reflects.

---

## Section 5: Compensation

### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| Glassdoor | - | No data | - | - | - | 0 |
| levels.fyi | - | No company page (HTTP 404) | - | - | - | 0 |
| Kununu | - | No engineering salaries; one intern review calls the pay "Faire Praktikumsvergütung" | - | - | - | 0 |
| Job posting (Backend Engineer) | Backend Engineer, 2+ yrs | Not disclosed ("competitive compensation - base + bonus + VSOP") | VSOP | Yes | - | - |

For reference, Munich senior backend / Python engineers in software companies typically earn ~€80K at the median, ~€90-95K at the 75th percentile and ~€105-110K at the 90th (base). Pre-seed and seed Munich startups hiring a "2+ years" backend profile usually budget around €65-85K base.

### Equity / Stock

**VSOP** (virtual stock option plan). These are phantom shares that pay out only on an exit (sale or IPO), are taxed as income, and carry no voting rights. At pre-seed or seed stage, with a fundraise in progress, their value is highly speculative and illiquid. Also offered: a performance bonus, EGYM Wellpass, tax-free benefits, and a company apartment in Munich on request (for relocation).

### Verdict

Large, profitable Munich employers pay senior engineers roughly €85-110K base plus a bonus and liquid equity or pension. This company has disclosed nothing, and its only engineering role targeted a mid-level profile at a pre-seed startup. Likely **BELOW**, formally **UNVERIFIED**.

---

## Section 6: AI/ML & Tech Stack Fit

### AI Strategy

The company's AI work is genuine and applied. It runs AI longlists ("chat-driven target and buyer search that goes beyond rigid industry codes"), automated outside-in company analysis (peers, benchmarking, SWOT, valuation, forecasting), and generated niche market reports. The Data & Security page describes "deterministic, rule-based logic" combined with selective ML and LLM use, says customer data is never used to train foundation models, and says it hosts in the EEA with a focus on Germany. The engineering JD asks engineers to "develop agentic workflows and AI-powered pipelines" and to "decide when an LLM is the right tool and when deterministic code is the better answer". This is production LLM application engineering over a large company-data corpus, not model research. No LLM provider is named. Internally, the operations team uses Claude, n8n and HubSpot.

### Tech Stack

Derived mainly from the (closed) Backend Engineer JD, plus the Founder's Associate JD and the Data & Security page. The GitHub organisation `strategybridgeai` exists but has no public repositories. No engineering blog, StackShare or Himalayas profile was found.

| Category | Technologies |
|---|---|
| **Primary language(s)** | Python (backend); TypeScript, React/Next.js (frontend, nice-to-have) |
| **AI/ML** | LLMs in production, agentic orchestration (LangChain, LangGraph, CrewAI or similar), ML alongside deterministic financial models |
| **Cloud** | Not named; "enterprise-grade cloud environments" in the EEA with a focus on Germany |
| **Infrastructure** | Docker, Kubernetes, CI/CD, observability |
| **Data** | PostgreSQL, Elasticsearch, Qdrant (vector store); Apache Spark and Dagster (nice-to-have) |
| **Other** | REST API design, third-party data integrations; ISO 27001 certification in progress; n8n, HubSpot (internal ops) |

### Current Open Roles

Checked the LinkedIn voyager job search (keywords "StrategyBridgeAI" and "StrategyBridge", Germany) plus the posting API for each result, and the company website (it has no careers page). Personio and join.com both return 404.

| Role | Division/Team | Level | Key Tech | Link |
|---|---|---|---|---|
| Backend Engineer - Fintech | Engineering | Mid (2+ yrs) | Python, LLM/agents, Postgres, Elasticsearch, Qdrant, K8s | [LinkedIn 4466082626](https://www.linkedin.com/jobs/view/4466082626/), **CLOSED**, excluded |
| Founder's Associate, Fundraising | Founder's Office | Entry/associate | Non-engineering | [LinkedIn 4479062857](https://www.linkedin.com/jobs/view/4479062857/), open (non-SWE) |
| Founder's Associate Intern, Fundraising | Founder's Office | Intern | Non-engineering | [LinkedIn 4479051940](https://www.linkedin.com/jobs/view/4479051940/), open (non-SWE) |

**No Senior/Staff software engineering roles are currently open.**

**Verdict:** Python-centric applied LLM engineering: agentic pipelines over a company and financial data corpus, on PostgreSQL / Elasticsearch / Qdrant with Docker / Kubernetes and an unnamed EU cloud. This is production engineering, not research. The stack is a strong match to Python, LLM and data-platform profile. The fit is limited by scale (a tiny team, so a wide generalist remit including frontend and client contact) and by the absence of a senior-level opening.

---

## Section 7: Language

The engineering JD is in English and states "English is our company language; German is nice to have." The Founder's Associate postings are in German, but those are founder-office roles facing German financial clients. The customer base is overwhelmingly DACH (German testimonials, IDW, German audit firms), so some client-facing contact may be in German. The JD expects engineers to "collaborate directly with clients".

**Verdict:** **PASS** for engineering. German would help with client-facing parts of the role.

---

## Section 8: Stability

### Financial Position

- **Filed accounts (NorthData, partial, read via CDP):** Jahresabschluss for 31.12.2024 (small GmbH, deposited 09.01.2026). **Total assets €1,133,307**, of which current assets €1,097,491. That date falls a few weeks after the pre-seed closed, so the current assets are most likely mostly cash from the round. Revenue and net loss are not visible (small-company HGB filings omit the P&L). handelsregister.ai, which usually renders these filings, did not load the profile: it hung on "Wir laden offizielle Registerdaten" and then the CDP session timed out.
- **R&D tax credit:** €100,000-500,000 granted (BMF Forschungszulage, published 15.01.2026).
- **Revenue:** not disclosed. "100 clients" (2025) and "2K+ users". At a plausible €10-25K average contract value for DACH advisory and audit firms, that suggests roughly **€1-2.5M ARR** (derived estimate, not reported).
- **Profitability target:** "Wir wollen bestenfalls 2026 Profitabilität erreichen, priorisieren aktuell aber Wachstum" (VC Magazin, Mar 2025). Hiring a fundraising lead in Oct 2026 indicates the target was not reached, or that growth was chosen over it.
- **Trend:** growing (customer base 5x by Dec 2024, headcount +45% on LinkedIn, international expansion, two FinTraWorld 2026 awards). Burn is presumably growing too.

### Financial Runway

No runway estimate exists in the press, on CB Insights (stage: pre-seed), or elsewhere. Bottom-up model:

| Cost line | Annual estimate |
|---|---|
| Staff (~30 people × ~€70K fully loaded; many are juniors, working students and interns) | ~€2.1M |
| Licensed company / financial data (business databases feeding "50M companies") | ~€0.3-0.6M |
| Cloud, LLM APIs, tooling | ~€0.2-0.3M |
| Offices (WERK1 Munich, Campus Founders Heilbronn), sales, events, travel | ~€0.2-0.3M |
| **Total gross burn** | **~€2.8-3.3M/year** |

| Revenue source | Est. annual inflow |
|---|---|
| SaaS subscriptions (~100+ clients, derived ARR) | ~€1.0-2.5M/year |
| Forschungszulage (R&D tax credit) | ~€0.1-0.3M/year |
| **Total revenue offset** | **~€1.1-2.8M/year** |

| Scenario | Net burn | Cash at hand | Runway | Next round needed by |
|---|---|---|---|---|
| Optimistic | ~€0.3M/year (near break-even) | ~€0.5-1.0M (est.) | 2+ years | Optional (growth round) |
| Base case | ~€1.0M/year | ~€0.5-1.0M (est.) | ~6-12 months | ~H1 2027 |
| Stress | ~€1.8M/year | ~€0.5M (est.) | ~3-4 months | Q1 2027 |

Cash figure used: current assets of €1.10M at 31.12.2024 (NorthData, observed 2026-10-15), taken as a proxy for post-pre-seed cash. Current cash at Oct 2026 is unknown. The estimate above assumes 22 months of net burn partly offset by growing revenue. The strongest real-world signal is that the company is hiring a dedicated person whose "first and most important" task is the next financing round. The round is clearly being prepared now, which fits the base case.

### Layoffs

No layoffs were found (press, Kununu, LinkedIn). The technical co-founder departed after the first year (2023).

### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | NO (presumed) | No mention in any review, posting or press. Typical for a ~30-person startup |
| Collective agreement | NONE | Postings mention "base + bonus + VSOP", with no Tarif reference |
| European works council | N/A | Single German entity |
| Conflict signals | None found | - |

**Verdict:** **FAIL** on stability. A pre-seed startup with an unknown, probably short runway, in the middle of a fundraise, without a works council or collective agreement. This does not meet the criterion of a mature, profitable company with a stable business.

---

## Section 9: Regulated Industry

The company itself is not regulated. Its customers are: auditors (IDW standards), banks (BaFin, and DORA third-party risk for ICT suppliers) and PE funds. In practice, this brings enterprise security and procurement requirements: ISO 27001 certification is in progress, data-room and due-diligence questionnaires come up in sales, and outputs must be traceable and audit-grade ("Reliable results, full transparency and traceability"). There is no formal safety or regulatory engineering process like IVDR or ISO 26262.

**Verdict:** **PASS** (low burden). ISO 27001 and DORA-driven customer audits add moderate security and documentation work.

---

## Section 10: On-Call

The Backend JD requires engineers to "Own your services in production - deployment, monitoring, and knowing first when something breaks" and to "ship and operate your own services". No formal rotation is mentioned, but with a small team running a SaaS platform for thousands of finance professionals, that "knowing first" is effectively informal on-call during business-critical periods (deal deadlines).

**Verdict:** **CAUTION** (implicit you-build-it-you-run-it; formal on-call is unverified).

---

## Section 11: Interview Process

Based on data from Glassdoor (glassdoor.de, via CDP) and the job posting.

| Metric | Value |
|---|---|
| Difficulty | 3.0 / 5 (Glassdoor, 1 interview: "average") |
| Positive experience | 0% (1 interview: Frontend Engineer, Aug 2026, negative, no offer) |
| Average duration | UNKNOWN |
| Rounds | 3 plus offer (from the JD) |

The JD lists the process as "Intro chat → Technical deep dive → Case Study & Team interviews → Offer. We value your time & move fast." The application asks for a CV, GitHub/portfolio and "a short note about a project you're proud of". The one real candidate report describes something different. The first step was a 10-minute technical screen run by a marketing/product person reading questions and expected answers from ChatGPT, with textbook CS trivia (linked lists, Big-O of array search, `getElementById` vs `querySelector`). Passing it was a condition for the HR call. Expect a junior-style gate before any experience-focused conversation. There is too little data to generalise, but it is a negative signal for how engineering is valued in hiring.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | PASS: SaaS company-analysis platform |
| Not consulting | PASS with CAUTION: product company, but the registered purpose includes management and strategy consulting, and analyses started as manual work |
| Profitable | **FAIL**: pre-seed funded, fundraising, almost certainly loss-making |
| Employee count | ~25-30 (LinkedIn 11-50) |
| English-speaking | PASS: "English is our company language" |
| Local entity + engineering contracts | PASS: StrategyBridgeAI GmbH, HRB 273777 München, direct hire |
| Location / work model | Werksviertel area (U5); hybrid with unknown office days |
| Glassdoor | **No data**: 0 reviews; 1 interview report, negative |
| Kununu | 4.7 / 100% (6 reviews, mostly interns, 2024-Jan 2025); unreliable |
| Salary | UNVERIFIED, likely BELOW: base + bonus + VSOP, undisclosed |
| AI/ML content | Strong: production LLM and agentic pipelines in Python |
| Computer-language/Tech-stack | Strong fit: Python, PostgreSQL, Elasticsearch, Qdrant, LangGraph, K8s |
| No on-call | CAUTION: "own your services in production... knowing first when something breaks" |
| WLB / Stability | **FAIL**: early-stage intensity, fundraise under way, runway unknown |
| Works council / collective agreement | None |
| Regulated industry | PASS: clients regulated, the company is not |
| Review themes | Too thin to judge; intern praise only |
| No suitable open role | The Backend role is closed and was mid-level; only the fundraising roles are open |

---

## Section 13: Verdict

**Exclude.** StrategyBridgeAI is a promising young product company, but it is the opposite of the mature, profitable, stable employer the criteria require.

**Strengths:** The engineering work is attractive. Python backend, production LLM and agentic pipelines, and search and vector stores over a large financial-data corpus, plus a pragmatic philosophy ("Simple beats clever", "decide when an LLM is the right tool and when deterministic code is the better answer"). English is the company language. The company shows real traction: around 100 clients, recognition from IDW, awards in 2026, and a Munich office in the Werksviertel.

**Hard blockers:**
1. **Stability and profitability.** The only disclosed external funding is an undisclosed seven-figure pre-seed from December 2024. Total assets were €1.13M at end-2024. The company is now hiring someone whose main job is to run the next financing round. Under the base-case model (~€1M net burn), runway ends around H1 2027 unless the round closes. That is incompatible with a long-term commitment.
2. **No suitable vacancy.** The only engineering role found is closed and was scoped at "at least 2 years of professional experience", not Senior/Staff. Nothing at the right level is open.
3. **No review evidence.** Glassdoor has zero reviews. Kununu's six reviews are almost all from interns and stop in January 2025. Indeed, Blind, Comparably and Reddit have nothing, and LinkedIn alumni tenures are hidden. The only recent first-hand account (Glassdoor interview, Aug 2026) is negative: a ChatGPT-scripted technical screen run by a marketing/product person. With 6 engineers among ~29 staff and no named technical leader, the engineering culture cannot be verified and looks business-led.

**Secondary concerns:** a coworking hub as the office; VSOP-only equity with likely below-market cash pay; implicit production ownership and on-call; founder-level intensity openly described by the CEO; no works council or collective agreement; a registered purpose that includes consulting; and the technical co-founder left after year one, with no named CTO.

**Recommendation:** Do not apply now. No further research is warranted unless two things change: the company closes a substantial seed or Series A round (giving 24+ months of runway) and posts a Senior/Staff backend or AI-engineering role. If both happen, verify in interviews the salary band against the Munich senior market, the number of office days, how production incidents are handled, and who leads engineering.

---

## Sources

- [StrategyBridgeAI - Homepage](https://www.strategybridge.ai/) (via CDP)
- [StrategyBridgeAI - Imprint](https://www.strategybridge.ai/legal/imprint) (via CDP)
- [StrategyBridgeAI - About](https://www.strategybridge.ai/about) (via CDP)
- [StrategyBridgeAI - Data & Security](https://www.strategybridge.ai/data-security)
- [StrategyBridgeAI - Platform](https://www.strategybridge.ai/platform)
- [StrategyBridgeAI - Company News](https://www.strategybridge.ai/resources/company-news) (via CDP)
- ["All In" - What Building StrategyBridgeAI Really Looks Like (Apr 2026)](https://www.strategybridge.ai/resources/all-in-what-building-strategybridgeai-really-looks-like)
- [StrategyBridgeAI wins double at FinTraWorld 2026](https://www.strategybridge.ai/resources/strategybridgeai-wins-double-at-fintraworld-2026-best-solution-in-corporate-banking-and-overall)
- [StrategyBridgeAI's biggest platform update yet (Jun 2026)](https://www.strategybridge.ai/resources/strategybridgeai-s-biggest-platform-update-yet-deeper-analysis-better-decisions)
- [NorthData - StrategyBridgeAI GmbH, HRB 273777](https://www.northdata.de/StrategyBridgeAI+GmbH,+M%C3%BCnchen/Amtsgericht+M%C3%BCnchen+HRB+273777) (via CDP)
- [handelsregister.ai - StrategyBridgeAI GmbH](https://handelsregister.ai/de/unternehmen/StrategyBridgeAI%20GmbH) (via CDP; profile did not load)
- [LinkedIn - StrategyBridgeAI company page](https://www.linkedin.com/company/strategybridgeai/) (via CDP)
- [LinkedIn - Backend Engineer - Fintech (closed)](https://www.linkedin.com/jobs/view/4466082626/) (voyager API via CDP)
- [LinkedIn - Founder's Associate, Fundraising](https://www.linkedin.com/jobs/view/4479062857/) (voyager API via CDP)
- [LinkedIn - Founder's Associate Intern, Fundraising](https://www.linkedin.com/jobs/view/4479051940/) (voyager API via CDP)
- [Glassdoor - StrategyBridgeAI Overview](https://www.glassdoor.com/Overview/Working-at-StrategyBridgeAI-EI_IE9886029.11,27.htm) (via CDP)
- [Glassdoor - StrategyBridgeAI Salaries](https://www.glassdoor.com/Salary/StrategyBridgeAI-Salaries-E9886029.htm) (via CDP)
- [Glassdoor.de - StrategyBridgeAI Interviews](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/StrategyBridgeAI-Fragen-im-Vorstellungsgespr%C3%A4ch-E9886029.htm) (via CDP)
- [Glassdoor - Search results](https://www.glassdoor.com/Search/results.htm?keyword=StrategyBridgeAI) (via CDP)
- [Kununu - StrategyBridgeAI](https://www.kununu.com/de/strategybridgeai) (via CDP; curl returned 405)
- [Kununu - StrategyBridgeAI reviews](https://www.kununu.com/de/strategybridgeai/kommentare) (via CDP)
- [Teamblind - StrategyBridgeAI (404)](https://www.teamblind.com/company/StrategyBridgeAI/) (curl)
- [levels.fyi - StrategyBridgeAI (404)](https://www.levels.fyi/companies/strategybridgeai/salaries) (curl)
- [GitHub - strategybridgeai organisation (no public repos)](https://github.com/strategybridgeai)
- [Munich Startup - Successful pre-seed round for Munich fintech StrategyBridgeAI](https://www.munich-startup.de/en/news/successful-pre-seed-round-for-munich-fintech-strategybridgeai)
- [Munich Startup - StrategyBridgeAI Finanzierung (DE)](https://www.munich-startup.de/106373/strategybridgeai-finanzierung/)
- [Munich Startup - StrategyBridgeAI tag](https://www.munich-startup.de/en/day/strategybridgeai/)
- [Startbase - StrategyBridgeAI sichert sich siebenstellige Pre-Seed-Finanzierung (DE)](https://www.startbase.de/news/strategybridgeai-sichert-sich-siebenstellige-pre-seed-finanzierung/)
- [Startbase - StrategyBridgeAI secures seven-figure pre-seed financing (EN)](https://www.startbase.com/news/strategybridgeai-sichert-sich-siebenstellige-pre-seed-finanzierung/)
- [Trending Topics - Münchner Fintech erhält Millioneninvestment](https://www.trendingtopics.eu/strategybridgeai-muenchner-fintech-erhaelt-millioneninvestment)
- [Techleap - StrategyBridgeAI secures seven-figure funding](https://finder.techleap.nl/news/feed/strategybridgeai-secures-seven-figure-funding)
- [Nordic9 - StrategyBridgeAI raised pre-seed funding](https://nordic9.com/news/strategybridgeai-raised-pre-seed-funding-with-d11zventures-gmbh-co-kg-bayern-kapital-kai-hesselmann/)
- [CB Insights - StrategyBridgeAI](https://www.cbinsights.com/company/strategybridgeai)
- [CB Insights - StrategyBridgeAI financials](https://www.cbinsights.com/company/strategybridgeai/financials)
- [Nominatim - Friedenstraße 6a, 81671 München](https://nominatim.openstreetmap.org/search?q=Friedenstra%C3%9Fe+6a,+81671+M%C3%BCnchen&format=json&addressdetails=1)
- [Nominatim - Am Kartoffelgarten 14, 81671 München](https://nominatim.openstreetmap.org/search?q=Am+Kartoffelgarten+14,+81671+M%C3%BCnchen&format=json)
- [Overpass API (failed: HTTP 406; kumi.systems mirror HTTP 502)](https://overpass-api.de/api/interpreter)
- [Kununu - StrategyBridgeAI (slug strategybridgeai1)](https://www.kununu.com/de/strategybridgeai1) (via CDP)
- [Kununu - StrategyBridgeAI Kulturkompass](https://www.kununu.com/de/strategybridgeai/kultur) (via CDP)
- [Indeed - StrategyBridgeAI (404)](https://de.indeed.com/cmp/Strategybridgeai/reviews) (via CDP)
- [LinkedIn - StrategyBridgeAI People](https://www.linkedin.com/company/strategybridgeai/people/) (via CDP)
- [LinkedIn - past employees search](https://www.linkedin.com/search/results/people/?pastCompany=%5B%2279802540%22%5D) (via CDP)
- [LinkedIn - content search "StrategyBridgeAI"](https://www.linkedin.com/search/results/content/?keywords=StrategyBridgeAI&sortBy=%22date_posted%22) (via CDP)
- [VC Magazin - Wissen ist Macht: Case Study StrategyBridgeAI (Mar 2025)](https://www.vc-magazin.de/blog/2025/03/18/case-study-strategybridgeai/)
- [Campus Founders - StrategyBridgeAI AI Founders Chat](https://campusfounders.de/de/startups-de/strategybridgeai-ai-founders-chat/)
- [IT Finanzmagazin - Strategy Bridge AI will Unternehmensanalysen datenbasiert vereinfachen](https://www.it-finanzmagazin.de/strategy-bridge-ai-will-unternehmensanalysen-datenbasiert-vereinfachen-219693/)
- [Unternehmeredition - StrategyBridgeAI schließt Pre-Seed-Finanzierungsrunde ab](https://www.unternehmeredition.de/strategybridgeai-schliesst-pre-seed-finanzierungsrunde-ab/)
- [Starting-up.de - StrategyBridgeAI schließt Finanzierungsrunde ab](https://www.starting-up.de/news/news-investments/strategybridgeai-schliesst-finanzierungsrunde-in-siebenstelliger-hoehe-ab.html)
- [Podscan - Hope Is Not a Strategy: "AI Won't Fix Your Business. Your Data Will." (Jun 2026)](https://www.podscan.fm/podcasts/hope-is-not-a-strategy/episodes/ai-wont-fix-your-business-your-data-will-1) (via CDP)
- [Podigee - Hope Is Not a Strategy episode 15](https://hope-is-not-a-strategy.podigee.io/15-ai-won-t-fix-your-business-your-data-will)
- [workingstudentjobs.de - StrategyBridgeAI Data Engineer Internship](https://www.workingstudentjobs.de/jobs/strategybridgeai-data-engineer-internship-fintech-1420b599)
- [Prospeo - StrategyBridgeAI company profile](https://prospeo.io/c/strategybridgeai-email-format)
- [WERK1 Startup Hub](https://werk1.com)
- [Campus Founders Heilbronn](https://campusfounders.de)
