# Zencoder - Full Research Report

_Researched: 2026-11-13_

> **Critical Disqualifiers**
> 1. **No German legal entity and no Munich office.** The operating company is For Good AI Inc. (dba Zencoder Inc.), a US corporation with a mailbox-style address in Campbell, California. The only European entity found is For Good AI Cyprus Ltd. (Nicosia, HE 455543), run by Cypriot corporate-service directors. NorthData returns no German or Spanish For Good AI / Zencoder entity, and `zencoder.ai/imprint` is a 404. A Germany-based hire would be via an Employer of Record or contractor agreement, not a direct German contract.
> 2. **Stack is TypeScript and Kotlin/Java, not Python.** Every current engineering posting names "TypeScript and Kotlin" or "JavaScript, JVM-based (Java/Kotlin)" as the core languages. Python does not appear in any posting.
> 3. **Glassdoor is statistically meaningless and looks campaign-driven.** 5 reviews in total, 4 of them posted within one week (6-13 May 2026). Zero reviews from Germany or Munich. No Kununu or Blind profile exists.
> 4. **Funding, revenue and runway are undisclosed, and the company has just pivoted part of its engineering to a non-coding product.** On 10 Nov 2026 the same team launched Hops, a collaborative AI workspace for business teams, which the press release says was built by "a team of 30 engineers". There is no announced VC round; aggregator records ($100K seed in Mar 2026) look like data noise.
>
> The full report follows for completeness.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 2023 (3 years; LinkedIn "Founded 2023"; emerged from stealth 24 Oct 2024) |
| Employees | ~70 globally ("a team of 70+ engineers, researchers, and builders", zencoder.ai/about); press releases in 2024 and Apr 2026 say "50+ engineers"; LinkedIn 51-200 band, 44 associated members; Caplight: 46 to 54 employees by Aug 2025 |
| Revenue (FY2025) | UNKNOWN. No ARR, revenue or customer count disclosed. Holds SOC 2 Type II, ISO 27001 and ISO 42001, which suggests enterprise sales effort |
| Profitability | UNKNOWN; almost certainly loss-making (early-stage AI agent company with heavy LLM inference costs and free tiers) - **FAIL (UNVERIFIED)** |
| Ownership | Private. Legal entity For Good AI Inc. (dba Zencoder Inc.). Founder-led; investor list undisclosed (aggregators cite Geek Ventures, Quonota Investments, AAL VC, all unconfirmed) |
| Software-centric | Pure software product (AI coding agents, IDE plugins, Zenflow orchestration app, now Hops workspace) - **PASS** |

### Key People

- **Andrew Filev** - Founder & CEO. Founded Wrike in 2006, bootstrapped it for about seven years, sold majority to Vista (2018); Citrix acquired Wrike for $2.25B in 2021.
- **Archie Sharma** - COO, GTM (previously COO at HappyFox), per Crunchbase and Caplight.
- A CTO is referenced as the final interviewer in a Feb 2026 Glassdoor interview report but is not publicly named.

### Funding History

| Date | Round | Amount | Valuation |
|---|---|---|---|
| 2023-2024 | Founding capital | UNDISCLOSED | UNKNOWN |
| Unknown | Seed (Crunchbase lists 2 seed rounds, amounts obfuscated; investor shown: Quonota Investments) | UNDISCLOSED | UNKNOWN |
| 23 Mar 2026 | "Seed" per Caplight / StartupHub / Signalbase, led by Geek Ventures | $100K (aggregator figure, not credible as company funding) | UNKNOWN |
| **Total** | | **UNKNOWN** | |

No funding announcement exists on PR Newswire, TechCrunch or the Zencoder blog. Several aggregators (Tracxn, parts of Crunchbase) mix Zencoder up with the unrelated 2010-era Zencoder video-encoding company (YC, a16z $2M Series A, acquired by Brightcove) and should be ignored. The most plausible reading, given the founder's Wrike exit and the absence of any announced round, is that the company is largely founder-financed with small angel/seed participation. This is an inference, not verified.

### Business Model

- **Zencoder** (developer tooling): IDE agents for VS Code and JetBrains, CLI, and Zenflow (Code), a desktop orchestration app that runs several coding agents against specs and tests. Seat subscriptions plus usage/consumption charges ("Top-Up Credits", "Consumption Charges" in the Terms of Service). Acquired **Machinet** (JetBrains AI plugin, 100K+ downloads) in Apr 2025, terms undisclosed.
- **Zenflow Work** (Apr 2026): extended the orchestration product to non-coding teams.
- **Hops** (GA 10 Nov 2026): a collaborative AI workspace (chat, docs, slides, custom apps) for whole business teams, no per-seat fee, pay-per-AI-credit. Built by For Good AI, "the same team builds Zencoder". The Zencoder website now carries a "New: Hops" banner, and several LinkedIn profiles of Zencoder staff now name Hops.ai as their employer.

This is a clean product company, not consulting. The strategic concern is focus: a ~70-person company is now running two products in two very crowded markets (AI coding agents against Cursor, Claude Code, Codex, Copilot; team AI workspaces against Notion, Slack, Microsoft and Google).

---

## Section 2: Local Commercial Entity in Germany

Searched NorthData for "Zencoder" and "For Good AI" (all countries, then filtered to DE and ES), retrieved via Chromium/CDP. Checked zencoder.ai legal pages (Terms of Service, Privacy Policy, `/imprint`) via CDP.

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **For Good AI Inc. (dba Zencoder Inc.)** | US corporation (state not stated on the site) | 500 W Hamilton Ave, 112550, Campbell, CA 95008, USA | Operating company; contracting party in the Terms of Service and Privacy Policy |
| **For Good AI Cyprus Ltd.** | Cyprus DRCOR **HE 455543** | 25 Martiou 27, D. Michael Tower, Office 105A, CY-2408 Nicosia | Not visible on NorthData. Registered 2024. Directors/secretaries include corporate-service providers (Fiscusserve Ltd., Lorcam Business Consultants Ltd., Inistra Ltd., Clementius Ltd., Orosoft Ltd., Infiano Ltd.) and one named individual |
| German entity | **None found** | - | - |

No GmbH, no Zweigniederlassung and no German Impressum. The Cyprus company has the profile of a holding/IP or payroll vehicle administered by a corporate-service firm, not an engineering subsidiary. The "112550" in the Campbell address reads like a mailbox number at a shipping-store address. A Germany-based engineer would almost certainly be engaged via an Employer of Record (Deel/Remote-type) or as an independent contractor; the postings do not say which.

**Verdict: FAIL**

---

## Section 3: Office Location

- **Office address:** No Munich or German office. HQ address is Campbell, California (500 W Hamilton Ave, mailbox 112550). Current postings say: "Remote-First ... Prefer in-person? We have a hub in Barcelona with weekly co-working." The Barcelona hub address is not published; no Spanish entity was found on NorthData. LinkedIn member locations: Spain 7 (Barcelona 5), Serbia 5, United States 5; schools are dominated by St Petersburg universities (SPbU, Polytechnic, ITMO), consistent with a relocated Russian-speaking engineering core.
- **Nearest public transport:** N/A (no Munich office; Barcelona hub address unknown, so no Nominatim/Overpass lookup possible).
- **Work model:** Fully remote. All four open engineering roles (Senior Software Engineer, Staff Software Engineer, Staff Platform Engineer, Staff Security Engineer) are listed "Europe, Remote" on Greenhouse. Postings: "We hire talent, not coordinates." Germany is not excluded, but there is no German employing entity (see Section 2).

---

## Section 4: Reviews

**GPTW:** Not certified. No Zencoder or For Good AI result on greatplacetowork.de or greatplacetowork.com.

### Glassdoor

Retrieved via Chromium/CDP (`glassdoor.co.uk`, employer ID E10126235; `glassdoor.com` redirected to a 404 page and `glassdoor.de` showed 0 reviews under its default language filter). Do not confuse with "Zencode" (E2932035, 3.7), an unrelated company.

| Metric | Global | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | 4.8 (5 reviews) | no reviews | no reviews | 4.5 (2 reviews: 5.0 and 4.0, read off the full list) |
| **WLB** | 4.5 | - | - | - |
| **Culture & Values** | 5.0 | - | - | - |
| **Comp & Benefits** | 4.7 | - | - | - |
| **Career Opportunities** | 5.0 | - | - | - |
| **Diversity & Inclusion** | 5.0 | - | - | - |
| **Senior Management** | 5.0 | - | - | - |
| **% Recommend** | 100% | - | - | - |
| **CEO Approval** | Not enough data | - | - | - |
| **Business Outlook** | 100% positive | - | - | - |

**Reliability:** 5 reviews is far below the 20-review level needed for even directional use. Four of the five were posted between 6 and 13 May 2026 (three current employees with under or just over 1 year tenure, plus one anonymous), a pattern typical of an internal review drive. The only location shown is Palo Alto (2024). Treat these scores as uninformative.

### Kununu

`https://www.kununu.com/de/zencoder` and `/de/for-good-ai` return HTTP 405 via curl and a 404 page via CDP; the Kununu search for "zencoder" returns no employer. **No Kununu profile exists.**

- **Overall score:** N/A
- **Recommendation rate:** N/A
- **Total reviews:** 0
- **Kununu Top Company:** NO

### Blind / Teamblind

`teamblind.com/company/Zencoder` returns "Page not found" (CDP). No Blind presence.

### Review Themes (2024-2026)

**Positives:**
- Talent density and autonomy: "Very strong engineering talent density and smart, hands-on people ... High ownership and ability to influence product and technical direction directly." (Glassdoor, May 2026, Anonymous employee, current, more than 1 year)
- Supportive colleagues: "Exceptional colleagues who consistently strive to deliver a top-quality product, paying close attention to both design and technical details." (Glassdoor, May 2026, Senior software engineer, current, less than 1 year)
- Flexibility: "flexible work environment, flexible hours, nice management, nice equipment, CEO is responsive" (Glassdoor, Sep 2024, Software engineer, former employee, Palo Alto, CA)

**Negatives:**
- Pace and shifting priorities: "Fast pace and shifting priorities can feel chaotic at times ... Priorities may evolve quickly as the company and market change." (Glassdoor, May 2026, Anonymous employee, current, more than 1 year)
- Immature process: "Clearer success metrics and roadmap visibility would make it easier to prioritize the highest-impact work." (Glassdoor, May 2026, Developer advocate, current, more than 1 year)
- Intensity: "the intensity of the industry means there is a lot to learn every day. It can be demanding at times" (Glassdoor, May 2026, Senior software engineer, current, less than 1 year)
- HR / PM: "Absolutely awful HR departments and project managers, quite stiff" (Glassdoor, Sep 2024, Software engineer, former employee, Palo Alto, CA)

The recurring theme, even within the positive reviews, is shifting priorities, which the Nov 2026 Hops launch confirms at company level. No red-flag theme (layoffs, surveillance, 24/7) is reported, but the sample cannot rule anything out.

### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | No evidence. One 2024 complaint about HR and project managers ("Absolutely awful HR departments and project managers"), not about the CEO ("CEO is responsive"). |
| 24/7 Work Expectation | No direct evidence. "It can be demanding at times" and "Startup pace can be intense" (May 2026). |
| Internal Surveillance | No evidence. |
| Fear-driven Management | No evidence. |
| Communication Breakdown | Mild: "Processes are still maturing ... cross-functional alignment may still be evolving" and wish for "roadmap visibility" (May 2026, Developer advocate). |
| Unpaid Overtime | No evidence. |
| Silent Firings | No evidence; no reviews from leavers except one in 2024. |
| Work-Life Balance issues | WLB is the lowest sub-score (4.5) on 5 reviews; "Fast pace and shifting priorities". |

**Risk level: LOW on available evidence, but effectively UNVERIFIED.** Five reviews, four from one week, are not a basis for a leadership assessment. What is visible is (c) localized startup immaturity (process, priorities), not systemic toxicity.

---

## Section 5: Compensation

### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| levels.fyi | - | No company page (`levels.fyi/companies/zencoder` 404, CDP) | - | - | - | 0 |
| Glassdoor | - | "0 job titles" on the salary tab | - | - | - | 0 |
| Job postings (Greenhouse) | Senior / Staff SWE, Europe Remote | Not disclosed | "Aligned Incentives: Our equity plan" | - | - | 0 |

Munich median / 75th / 90th percentile for this company: not available. Pay is likely set per country for a Europe-remote hiring pool whose centre of gravity is Spain and Serbia, which typically sits below Munich large-corporate levels; this is an inference, not data.

### Equity / Stock

Postings mention an "equity plan" and "real scope, autonomy, and equity", i.e. stock options in a US C-corp. Valuation, strike price, vesting and the share count are undisclosed. With no announced institutional round and no secondary market, liquidity risk is high. Option tax treatment for an EOR-employed German resident would also need checking.

### Verdict

No data points at all. **UNVERIFIED** (expected BELOW the Munich large-profitable-corporation bracket for a Europe-remote, Spain/Serbia-weighted startup).

---

## Section 6: AI/ML & Tech Stack

### AI Strategy

Genuine applied-AI product work, not marketing AI:
- **Zencoder agents** for VS Code and JetBrains with "Repo Grokking" context retrieval, coding, unit-testing and custom agents; marketed claims of deep syntactic/semantic code analysis to reduce hallucinations.
- **Zenflow (Dec 2025):** a free desktop orchestration app that runs multiple models (Claude, GPT, Gemini) against specs and tests and has LLMs verify each other's work; publishes SWE-Bench Pro comparisons.
- **Zenflow Work (Apr 2026)** and **Hops (Nov 2026):** agent orchestration and a collaborative AI workspace for non-engineering teams, with an app-builder agent.
- The company consumes frontier LLM APIs rather than training foundation models. The ISO 42001 (AI management) certification signals enterprise AI-governance positioning. The Staff Security Engineer posting describes real agent-security problems (prompt injection, sandboxed code execution, cross-session access).

### Tech Stack

Derived from the 4 current Greenhouse postings (fetched via the Greenhouse boards API), the LinkedIn People skills breakdown (CDP), the Machinet acquisition coverage and product docs. No public GitHub organisation exists (`github.com/zencoder` belongs to the unrelated video company).

| Category | Technologies |
|---|---|
| **Primary language(s)** | TypeScript / JavaScript and Kotlin / Java ("Our stack currently consists of TypeScript and Kotlin"; "Expert in at least one of: JavaScript, JVM-based (Java/Kotlin)"). Kotlin fits the JetBrains plugin line (Machinet). Python is listed as a skill by 21 of 44 LinkedIn members but appears in no posting |
| **AI/ML** | Third-party LLM APIs (Anthropic, OpenAI, Google models in Zenflow), agent orchestration, retrieval over codebases, MCP integrations |
| **Cloud** | AWS or Google Cloud ("cloud environments such as AWS or Google Cloud") |
| **Infrastructure** | Monorepo with a platform-owned pipeline, CI/CD, IaC, observability, sandboxed agent execution, containers |
| **Data** | Not specified in postings ("compute and data layers") |
| **Other** | VS Code and JetBrains extension platforms, React Native (earlier postings and a 2026 interview report), real-time collaborative systems (Hops), SOC 2 / ISO 27001 / ISO 42001 |

**Summary:** TypeScript- and Kotlin-centric (polyglot JS/JVM) product engineering of IDE extensions, a desktop orchestration app and a real-time collaborative web workspace, built on third-party frontier LLM APIs on AWS or GCP. Applied/production engineering, not research.

---

## Section 7: Language

All postings, the website, docs and Glassdoor reviews are in English; no German or other language requirement appears. The team is distributed (Spain, Serbia, US, others) with a Russian-speaking core, so English is the only possible common working language.

**Verdict: PASS**

---

## Section 8: Stability

### Financial Position

No revenue, net income or cash disclosed anywhere. For Good AI Inc. is a US private company with no filings in European registers apart from the Cyprus entity (whose accounts are not shown on NorthData). The founder's Wrike exit gives a plausible deep-pocketed backer, but how much he has committed is unknown. Crunchbase Growth Score fell 10 points and Heat Score 6 points in the last quarter (CDP, Nov 2026).

### Financial Runway

Searched: NorthData (no German entity, Cyprus entity has no published financials), Bundesanzeiger (not applicable, no German entity), Crunchbase (2 seed rounds, amounts obfuscated), Caplight / Tracxn / StartupHub ($100K seed, Mar 2026, not credible), web search for runway or burn-rate commentary (none found).

**Bottom-up burn model** (all inputs are estimates):

| Cost line | Annual estimate |
|---|---|
| Staff (~70 people × ~€95K average fully loaded, Europe-remote mix weighted to Spain/Serbia plus a few US GTM roles) | ~€6.7M |
| LLM inference for free tiers, trials and Hops early access (2,500 teams) | ~€2-5M |
| Cloud, tooling, SOC 2 / ISO audits, EOR fees | ~€0.7M |
| Marketing, PR, events | ~€1M |
| **Total gross burn** | **~€10-13M/year** |

| Revenue source | Est. annual inflow |
|---|---|
| Zencoder seat and usage subscriptions (no ARR disclosed; small share of a market dominated by Cursor, Copilot, Claude Code) | ~€2-6M/year (guess) |
| Hops (GA only on 10 Nov 2026) | ~€0 so far |
| **Total revenue offset** | **~€2-6M/year** |

| Scenario | Net burn | Cash at hand | Runway | Next round needed by |
|---|---|---|---|---|
| Optimistic | €4M/year | UNKNOWN (assume €20M founder-committed) | ~5 years | ~2031 |
| Base case | €7M/year | UNKNOWN (assume €15M) | ~2 years | ~2028 |
| Stress | €11M/year | UNKNOWN (assume €8M) | <1 year | ~2027 |

**Cash figure used:** none observed. The cash column is an assumption because no balance sheet, funding amount or runway statement is public (checked 2026-11-13). Runway is therefore **UNVERIFIED**; the decisive variable is the founder's willingness to keep funding, which cannot be researched.

### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| - | None found | - | No reports in press, TrueUp-type trackers or reviews. The 2025-2026 "Zencoder layoffs" search hits concern Brightcove/Vimeo (unrelated). |

No layoffs reported. Note the Nov 2026 shift of ~30 engineers onto Hops, which is a reallocation, not a cut, but it signals a bet that the coding-agent product alone was not enough.

### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | NO | No German entity exists, so no German establishment for a Betriebsrat |
| Collective agreement | NONE | US C-corp with Europe-remote hiring; no Tarif mention in postings |
| European works council | N/A | Far below EWC thresholds |
| Conflict signals | None found | - |

With no German entity, German employees (via EOR) would have only the statutory protections of the EOR's own employment contract, no works council and no social-plan mechanism. Weighed together with undisclosed funding and the strategic pivot, this is a material stability concern.

**Verdict: FAIL** (no local entity, no disclosed financials, pivot in progress)

---

## Section 9: Regulated Industry

Developer tooling and productivity SaaS. No sector regulator. Voluntary SOC 2 Type II, ISO 27001 and ISO 42001 certifications add some process (access reviews, change management, security controls) but no safety cases or formal verification.

**Verdict: PASS**

---

## Section 10: On-Call

No posting mentions on-call explicitly. However: "Product teams own their services, pipelines, and tests"; the platform role covers "deployment, observability"; the Staff Security Engineer will "lead incident response". A small team running a production SaaS (Zencoder cloud agents, Zenflow, now Hops with 2,500+ teams) with service ownership by product teams very likely shares production support among engineers. status.zencoder.ai shows an incident history, i.e. a live service that needs operating.

**Verdict: CAUTION (likely shared service ownership; UNVERIFIED)**

---

## Section 11: Interview Process

Based on Glassdoor (2 interview reports, `glassdoor.co.uk`, CDP).

| Metric | Value |
|---|---|
| Difficulty | "Average" (numeric score not shown; 2 reports) |
| Positive experience | 50% (other 50% neutral, 0% negative) |
| Average duration | ~1 week (single report) |
| Rounds | 5 (single report) |

Software Engineer interview, Belgrade, Feb 2026 (Glassdoor, Mar 2026, anonymous candidate, declined offer): "an initial HR screening, followed by a technical coding interview, a system design round, a behavioral interview, and a final interview with the CTO ... The coding and system design interviews covered a wide range of topics without a clear focus, jumping between areas such as LeetCode-style problems, object-oriented programming and even React Native concepts." Stage mix across both reports: skills test, phone interview, one-on-one, group panel. Mixed LeetCode-style and design; reported as unstructured.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | PASS: pure AI software products |
| Not consulting | PASS |
| Profitable | FAIL (UNVERIFIED): no revenue or funding disclosed; almost certainly loss-making |
| Employee count | ~70 (company claim); 44 on LinkedIn |
| English-speaking | PASS |
| Local entity + engineering contracts | FAIL: US Inc. plus Cyprus Ltd. only; no German entity; EOR/contractor route |
| Location / work model | Fully remote (Europe); Barcelona co-working hub; no Munich office |
| Glassdoor | 4.8 on 5 reviews (4 in one week of May 2026); no Germany/Munich data |
| Kununu | No profile |
| Salary | UNVERIFIED: no data on any platform |
| AI/ML content | Strong applied AI: coding agents, multi-model orchestration, agent security |
| Computer-language/Tech-stack | TypeScript and Kotlin/Java; Python absent from postings |
| No on-call | CAUTION: service ownership by product teams; incident response in a small team |
| WLB / Stability | WLB 4.5 (5 reviews); stability FAIL on disclosure, pivot to Hops |
| Works council / collective agreement | NONE (no German entity) |
| Regulated industry | PASS |
| Review themes | Talent density, autonomy; shifting priorities, immature process |
| Strategic focus risk | Two products (coding agents, Hops workspace) in two crowded markets with ~70 people |

---

## Section 13: Verdict

**Exclude.** Zencoder is a credible applied-AI product company led by a founder with a proven exit, and its engineering problems (multi-agent orchestration, agent sandboxing and security, real-time collaborative systems) are interesting. But it fails several hard criteria at once, and the research gaps are not ones that more research can close.

**Strengths:** genuine applied-AI product work rather than AI marketing; a small, senior, autonomous team where "Individual Contributors are the highest-status role"; English-only; no regulatory overhead; an experienced founder-CEO who reviewers describe as responsive.

**Hard blockers:**
1. **No German employing entity.** For Good AI Inc. (Campbell, CA) and For Good AI Cyprus Ltd. (HE 455543, administered by corporate-service providers) are the only entities found. A Munich-based engineer would be employed through an EOR or as a contractor, with no works council, no collective agreement and no German Impressum.
2. **No Munich office.** The only physical presence in Europe is a co-working hub in Barcelona; the model is fully remote.
3. **Language stack mismatch.** Every engineering posting is TypeScript plus Kotlin/Java (or "JavaScript, JVM-based"); Python, the required central language, does not appear at all.
4. **Profitability and runway cannot be established.** No revenue, ARR, cash or institutional round is public; the only "funding" records are a $100K aggregator entry and obfuscated Crunchbase seeds. The runway model above rests entirely on assumed cash.

**Secondary concerns:**
- Glassdoor evidence is unusable: 5 reviews, 4 in one week, none from Germany. No Kununu or Blind presence.
- Strategic drift: the company has moved from coding agents (2024) to multi-agent orchestration (Dec 2025) to non-coding work (Apr 2026) to a general team workspace, Hops (Nov 2026), now built by about 30 of its engineers. Reviewers already describe priorities as "shifting".
- No salary data at all; Europe-remote pay pegged to a Spain/Serbia-weighted pool is likely below Munich levels.
- Probable shared production ownership in a small SaaS team.
- An interview process candidates describe as unfocused (LeetCode, OOP and React Native in one loop).

**Recommendation:** Do not apply. Zencoder would only be worth revisiting if it (a) set up a German GmbH or offered a direct German employment contract, (b) opened Python-centred roles (for example agent evaluation or ML infrastructure), and (c) disclosed an institutional funding round or revenue that establishes a multi-year runway. None of these is in sight today, so no further research is warranted.

---

## Sources

- [Zencoder - About us](https://zencoder.ai/about) (CDP)
- [Zencoder - Terms of Service](https://zencoder.ai/legal/terms-of-service) (CDP)
- [Zencoder - Privacy Policy](https://zencoder.ai/legal/privacy-policy) (CDP)
- [Zencoder - Imprint (404)](https://zencoder.ai/imprint) (CDP)
- [Zencoder - Blog](https://zencoder.ai/blog) (CDP)
- [Zencoder Status - incident history](https://status.zencoder.ai/history)
- [Greenhouse job board API - Zencoder](https://boards-api.greenhouse.io/v1/boards/zencoder/jobs?content=true) (curl)
- [Greenhouse - Senior Software Engineer, Europe Remote](https://job-boards.greenhouse.io/zencoder/jobs/4976789007)
- [Greenhouse - Staff Software Engineer, Europe Remote](https://job-boards.greenhouse.io/zencoder/jobs/5136449007)
- [Greenhouse - Staff Platform Engineer, Europe Remote](https://job-boards.greenhouse.io/zencoder/jobs/5117063007)
- [Greenhouse - Staff Security Engineer, Europe Remote](https://job-boards.greenhouse.io/zencoder/jobs/5272103007)
- [Remote Rocketship - Zencoder jobs](https://www.remoterocketship.com/company/zencoder/jobs/staff-software-engineer-europe-remote/)
- [NorthData - search "Zencoder"](https://www.northdata.de/?query=Zencoder) (CDP)
- [NorthData - search "For Good AI"](https://www.northdata.de/?query=For+Good+AI) (CDP)
- [NorthData - For Good AI Cyprus Ltd., HE 455543](https://www.northdata.de/For%20Good%20AI%20Cyprus%20Ltd.,%20Nikosia/MCIT%20%CE%97%CE%95%20455543) (CDP)
- [Glassdoor - Zencoder reviews](https://www.glassdoor.co.uk/Reviews/Zencoder-Reviews-E10126235.htm) (CDP)
- [Glassdoor DE - Zencoder Bewertungen](https://www.glassdoor.de/Bewertungen/Zencoder-Bewertungen-E10126235.htm) (CDP)
- [Glassdoor - Zencoder interviews](https://www.glassdoor.co.uk/Interview/Zencoder-Interview-Questions-E10126235.htm) (CDP)
- [Glassdoor - Software Engineer interview, Feb 2026](https://www.glassdoor.co.uk/Interview/Zencoder-Interview-E10126235-RVW103246152.htm) (CDP)
- [Glassdoor - Zencoder salaries](https://www.glassdoor.co.uk/Salary/Zencoder-Salaries-E10126235.htm) (CDP)
- [Glassdoor - Zencode (unrelated company)](https://www.glassdoor.com/Reviews/Zencode-Reviews-E2932035.htm)
- [Kununu - zencoder (not found)](https://www.kununu.com/de/zencoder) (curl, CDP)
- [Kununu - search "zencoder"](https://www.kununu.com/de/search?q=zencoder) (CDP)
- [Teamblind - Zencoder (not found)](https://www.teamblind.com/company/Zencoder) (CDP)
- [Great Place to Work Germany - search](https://www.greatplacetowork.de/?s=zencoder) (CDP)
- [levels.fyi - Zencoder (404)](https://www.levels.fyi/companies/zencoder/salaries) (CDP)
- [LinkedIn - Zencoder People](https://www.linkedin.com/company/zencoderai/people/) (CDP)
- [LinkedIn - Zencoder About](https://www.linkedin.com/company/zencoderai/about/) (CDP)
- [LinkedIn - For Good AI People](https://www.linkedin.com/company/for-good-ai/people/) (CDP)
- [Crunchbase - Zencoder](https://www.crunchbase.com/organization/zencoder-2c99) (CDP)
- [Caplight - Zencoder](https://www.caplight.com/company/zencoder-ai) (curl)
- [Tracxn - Zencoder (conflates the old video company)](https://tracxn.com/d/companies/zencoder/__pbl4JcE1ER6EMRa7BZEMpF_Sv2DaLWuQ3HG-wnwte5U)
- [StartupHub - Zencoder](https://www.startuphub.ai/startups/zencoder)
- [PR Newswire - Zencoder emerges from stealth (Oct 2024)](https://www.prnewswire.com/news-releases/ai-startup-zencoder-emerges-from-stealth-to-deliver-ai-coding-agents-aimed-at-developers-302285158.html) (curl)
- [PR Newswire - Zencoder launches Zenflow Work (Apr 2026)](https://www.prnewswire.com/news-releases/zencoder-launches-zenflow-work-for-the-rest-of-the-work-302737866.html) (curl)
- [PR Newswire - Andrew Filev launches Hops (Nov 2026)](https://www.prnewswire.com/news-releases/ai-promised-10x-most-companies-got-1-2x-wrike-founder-andrew-filev-launches-hops-to-close-the-gap-302934936.html) (curl)
- [Hops - Collaborative AI for your whole team](https://www.hops.ai/) (CDP)
- [Zencoder acquires Machinet (Zencoder blog)](https://zencoder.ai/blog/zencoder-acquires-machinet)
- [SD Times - Zencoder acquires Machinet](https://sdtimes.com/ai/zencoder-acquires-machinet-to-further-improve-its-ai-coding-agents)
- [VentureBeat - Zencoder buys Machinet](https://venturebeat.com/ai/zencoder-buys-machinet-to-challenge-github-copilot-as-ai-coding-assistant-consolidation-accelerates)
- [VentureBeat - Zencoder drops Zenflow](https://venturebeat.com/ai/zencoder-drops-zenflow-a-free-ai-orchestration-tool-that-pits-claude-against)
- [SiliconANGLE - Zenflow gets LLMs to verify each other's work (Dec 2025)](https://siliconangle.com/2025/12/16/zencoders-zenflow-gets-llms-verify-others-work-accelerate-ai-code-automation/)
- [SiliconANGLE - Zencoder launches coding agent platform (May 2025)](https://siliconangle.com/2025/05/09/ai-startup-zencoder-launches-coding-agent-platform/)
- [The New Stack - Zencoder goes beyond coding](https://thenewstack.io/zencoder-goes-beyond-coding/)
- [Product Market Fit Show - Andrew Filev on Wrike and Zencoder](https://www.pmf.show/blog/andrew-filev-wrike-2-25b-citrix-exit-zencoder-ai-coding-agents) (curl)
- [BigDATAwire - Zencoder launches AI coding and testing agents](https://www.bigdatawire.com/this-just-in/zencoder-launches-ai-coding-and-testing-agents-with-deep-ide-and-devops-integration)
