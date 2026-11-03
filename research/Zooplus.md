# Zooplus - Full Research Report

_Researched: 2026-07-17_

> **Critical caution (not a hard disqualifier, but decision-defining):** Zooplus is headquartered in Munich, but its **software engineering IC roles are almost entirely located in Madrid, Kraków, Wrocław and Vienna, not Munich**. A live scan of the company's SmartRecruiters board (80 open positions) showed Munich carrying business, marketing, category, supply-chain and a handful of engineering-leadership roles (Engineering Director, Lead AI Systems Engineer), while every currently-open **Senior Software Engineer IC** posting sits outside Germany. The great commute to the Munich HQ is largely moot for an IC engineer unless a Munich-based IC opening appears.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 1999 (27 years) |
| Employees | ~1,615 globally (2025); Munich HQ ~650 |
| Revenue (FY2023) | €2.68bn net sales (+12% YoY); ~€3.0bn guided for 2024; 9M-2025 €1.80bn (+18% YoY) |
| Profitability | Adjusted EBITDA positive (€80.4m FY2023, roughly doubled), but pre-tax result a net **loss** of ~€110.5m (warehouse-closure impairment ~€141m) - **BORDERLINE** |
| Ownership | Private, PE-backed (Hellman & Friedman + EQT), taken private 2021 for ~€3.7bn, delisted Jan 2022 |
| Software-centric | Online pet-supplies retailer; large in-house engineering org but core business is e-commerce/logistics - **BORDERLINE** |

### Key People

- **CEO:** Lionel Desclee (appointed September 2025, succeeding Geoffroy Lefebvre).
- **Owners:** Hellman & Friedman and EQT (joint control since the 2021 take-private).

### Business Model

Zooplus is Europe's largest pure-play online pet-supplies retailer: 8,000+ products, ~28 countries. Revenue is retail (product sales plus a growing marketplace and retail-media arm). It is not a software vendor; software is the enabling layer for a retail/logistics business.

### Software-Centric Assessment

BORDERLINE. Zooplus runs a genuinely substantial engineering platform (reported ~2,500 microservices, ~20,000 containers, ~40 Kubernetes clusters, ~600 AWS accounts, 70+ AWS services, ~2TB logs/day). That is a real, modern, at-scale engineering estate, so this is not a "retailer with a small IT team." However, the company's economic identity is retail margin on pet food, not licensing or selling software. It qualifies as software-enabled retail rather than a software-centric company.

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **zooplus SE** | Amtsgericht München, **HRB 273759** | Herzog-Wilhelm-Str. 18, 80331 München | Trade in pet supplies at home and abroad, especially via the internet (food and accessories), acquisition and manufacture of pet supplies, **planning and implementation of internet-specific services**, and trade in IT-specific goods |

Verification: zooplus SE is the operating parent and is registered directly in Munich (verified via NorthData). Capital line ~€7.27m (filing dated Dec 2024). The registered purpose is retail-primary but explicitly includes "planning and implementation of internet-specific services," which supports direct in-house engineering rather than a pure sales shell. Munich-based staff (including the HQ engineering-leadership roles) are employed directly through zooplus SE, not via a PEO/EOR. This is a real operating headquarters, not a distribution front.

**Verdict:** PASS.

---

## Section 3: Office Location

- **Office address:** Herzog-Wilhelm-Str. 18, 80331 München (Altstadt, city centre, between Sendlinger Tor and Karlsplatz/Stachus).
- **Nearest public transit:** Sendlinger Tor (U1/U2/U3/U6/U7/U8, plus trams) ~3-4 min walk; Karlsplatz-Stachus (S-Bahn trunk, U4/U5) nearby.
- **Work model:** Hybrid, stated as ~60% office / 40% remote, plus up to 20 days/year working abroad in approved countries (from job postings and reviews).
- **Verdict:** **STRONG PASS**. Caveat: this only matters if a Munich-based role exists; see the report's top caution.

---

## Section 4: Reviews

**GPTW:** No Great Place to Work certification for Germany found. Marked **UNVERIFIED** (nothing located; absence is not proof).

### Glassdoor

Retrieved via the authenticated Glassdoor.de session (Playwright/CDP). Glassdoor lists **309 total reviews** but the analytic panel and rating breakdown are computed on a **filtered subset of 43 English-language reviews** (heavily Munich-based, spanning 2023-2026); the granular scores below are that subset and are directional.

| Metric | Value (43-review analytic subset) |
|---|---|
| **Overall** | 3.2 |
| **WLB** | 3.7 |
| **Culture & Values** | 2.9 |
| **Comp & Benefits** | 2.8 (down 8% in the last 12 months) |
| **Career Opportunities** | 2.6 |
| **% Recommend** | 37% |
| **CEO Approval** | **24%** (Geoffroy Lefebvre; note he was replaced by Lionel Desclee in Sept 2025) |
| **Business Outlook** | **19% positive** |

The clean country/city/SWE split could not be isolated, but the analytic subset is majority Munich, so it is a reasonable proxy for the German experience. Standout signals: very low CEO approval (24%) and business outlook (19% positive), and a comp score falling (2.8, down 8% YoY).

### Kununu

Kununu blocked every retrieval path attempted: curl returned an empty body (bot wall), WebFetch was refused by the host, and targeted web searches surfaced no cached score. **Kununu score UNVERIFIED.** Secondary signals (Glassdoor, Indeed) used as substitutes below.

### Indeed

From Indeed company data (Germany): CEO approval ~**52.5%**; salary satisfaction mixed (6 yes / 3 no); interview difficulty **medium**, average process ~**two weeks**. Detailed 1-5 sub-scores (WLB, pay, security, management, culture) were not returned by the API in this pass and are marked UNVERIFIED. Company page: https://de.indeed.com/cmp/Zooplus

### Blind / Teamblind

No Zooplus company page found on Blind (404). Coverage effectively **none** (Blind skews US tech; expected for a European retailer).

### Review Themes (2023-2026)

**Positives (consistent across reviews):**
- Modern, maturing tech stack; freedom to choose and try new technologies (repeatedly praised by engineers).
- Genuinely good work-life balance (WLB 3.7): flexible hours, hybrid WFH, up to 20 days work-from-abroad, "zero micromanagement" (working student). This is the single most consistent positive.
- Beautiful, modern Munich city-centre office; office dogs; friendly colleagues; strong team spirit ("sehr guter Zusammenhalt").
- Strong company mission/purpose (pets) and learning opportunities, especially for juniors/working students.

**Negatives (recurring, multi-year, multiple reviewers):**
- **Low / uncompetitive pay** is the most repeated complaint: "Poor salary," "Low Pay," "salaries not competitive for munich," "Gehalt unterdurchschnittlich," "low pay and no chance to advance." Comp score falling (2.8, down 8% YoY).
- **Weak, favouritism-driven management:** "management often picks their favorites... if you're not on the cool list, it's hard to get recognition"; "a lot of managers have a poor leadership style and have their favorites"; "extremely unprofessional... put in a position without the minimum knowledge of what means to be a leader."
- **Culture degraded after the PE takeover:** "After the takeover by investors, the great corporate culture was lost"; "short-term focus of shareholders"; "Fokus zu stark auf Profitabilität" hurting employee satisfaction.
- **Chaos / no direction / constant restructuring:** "lots of different things going on with no direction," "ziemlich chaotisch," "too many structural changes," a still-forming C-level ("the customers and employees are the guinea pigs"), and a cumbersome matrix org.
- **Unfair, non-transparent pay and performance reviews:** "salaries and annual performance reviews are extremely unfair, non-transparent, and purely subjective."
- **Rare promotions and layoffs** explicitly named (see Section 8).
- Low overall recommend (37%), very low CEO approval (24%) and business outlook (19% positive).

### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | **RECURRING, multi-year.** Multiple direct hits: "Toxisch" with "Management, Führung, Kommunikation, toxische Arbeitsbedingungen" (Teamlead, >3yr, Munich, Mar 2026); "very toxic mid level managers" (Apr 2024); "Toxic Political Culture, Ineffective Leadership" (Nov 2025); "the atmosphere is incredibly demoralizing, and leadership shows little regard for employee well-being." Concentrated at mid-level management; several reviews tie the decline to the PE takeover. |
| 24/7 Work Expectation | No evidence. WLB (3.7) is consistently praised; flexible hours and work-from-abroad repeatedly cited. |
| Internal Surveillance | No evidence. Opposite signal: "zero micromanagement" noted by a working student. |
| Fear-driven Management | Some: favouritism / "in-crowd" dynamics ("if you're not on the cool list"); the July 2026 account describes an HR-less accusation meeting and being told not to discuss it with colleagues. |
| Communication Breakdown | **Recurring:** "no direction," "ziemlich chaotisch," "too many structural changes," matrix-org friction ("challenging to find synergies between teams"), C-level "still in the finding phase." |
| Unpaid Overtime | No explicit unpaid-overtime claims, but **workload/pressure** is cited: "a lot of pressure to meet ambitious company targets," "endless backlog... could work there for days," "hohe workload," "some teams need additional resources." Pressure, not documented unpaid overtime. |
| Silent Firings | **One detailed account (Corporate IT, Munich, 2 July 2026, RVW104622914):** after passing probation with a raise, employee says they were set up on a business-critical Azure project without PM title/support, called to an HR-less "performance" meeting with unevidenced accusations, told they were "not senior enough," pressured to resign voluntarily, asked not to discuss it, and exited via negotiated garden leave. Classic managed push-out / constructive-dismissal pattern. Single, one-sided account; note it is **Corporate IT (internal enterprise Azure/Microsoft), not the product-engineering org**. |
| Layoffs | **Confirmed** (previously "not found"): a current Munich Product Owner (Nov 2025) lists "lay offs" as a con, and **Zooplus's own official reply acknowledged "recent layoffs"** and the need to ensure "stability for our teams." See Section 8. |
| Work-Life Balance issues | Low risk; WLB is the strongest positive (3.7), flexibility widely praised. |

Risk level: **MODERATE-to-HIGH** (raised from MODERATE after deeper review). The toxic-leadership and weak-management theme is not one isolated review: it recurs across 2024-2026 from Teamlead, manager, and IC reviewers, is concentrated at mid-level management, and is widely attributed to the culture shift after the Hellman & Friedman / EQT takeover and the resulting short-term profitability focus. Very low CEO approval (24%) and business outlook (19%) corroborate poor confidence in leadership. Mitigating factors keep it out of clear "HIGH/systemic-abuse" territory: work-life balance and flexibility are genuinely good, there is no 24/7 or surveillance signal, the company posts engaged public responses to negative reviews, and much of the pain reads as (b) PE-transition bureaucracy/instability plus (c) localized mid-management dysfunction rather than (a) top-down systemic cruelty. Net: management quality and culture are a real, recurring concern; work intensity and monitoring are not. Verify the specific hiring team's manager and org stability carefully in interviews.

---

## Section 5: Compensation

### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| levels.fyi | Software Engineer (Munich metro) | ~€63-75K | €0 | ~€0 | **~€75K median** (max ~€88K) | few |
| levels.fyi | Software Engineer (Germany) | ~€64-71K | €0 | ~€0 | **~€71K median** | few |
| Employer-stated (Glassdoor job) | Lead AI Systems Engineer, Munich | €74.7-112.1K | €0 | n/a | **€74.7-112.1K band** | employer figure |
| Employer-stated (Glassdoor job) | Engineer, Warehouse Automation, Munich | €69.5-84.9K | €0 | n/a | **€69.5-84.9K band** | employer figure |
| Employer-stated (Glassdoor job) | Engineering Director - Ecommerce, Munich | €145.4-218K | €0 | n/a | **€145.4-218K band** | employer figure |
| Market ref | Senior Software Engineer, Munich | - | - | - | **€85-124K** range | levels.fyi market |

Zooplus's levels.fyi SWE aggregate (~€75K Munich median) sits **below the Munich senior-engineer market band (€85-124K)**. However, the employer's own posted Munich bands are more encouraging: the **Lead AI Systems Engineer band (€74.7-112.1K)** reaches well into senior-market territory at the top, and the Engineering Director band is clearly competitive. The realistic read: entry/mid IC comp is below market, but senior/lead technical roles can approach the market band at the top of range. Sample sizes are small, so treat as directional. The weak Glassdoor comp score (2.9) still reflects genuine dissatisfaction, likely concentrated at IC level.

### Equity / Stock

No public equity (private, PE-owned since 2022). levels.fyi shows €0 stock component for engineers. Any equity-style upside would be a management incentive plan, unlikely to reach IC engineers, and illiquid until a sale/IPO event. Effectively treat this as a **cash-only** package with no RSU/ESPP.

### Verdict

**BELOW to COMPARABLE** for the bracket of large Munich corporates: below-market at IC level (levels.fyi ~€75K aggregate, cash-only, no equity), but the employer-stated senior/lead technical bands (e.g. Lead AI Systems Engineer up to ~€112K) can reach the lower-to-mid senior market at the top of range.

---

## Section 6: AI/ML & Tech Stack Fit

### AI Strategy

Genuine and expanding applied-AI investment: an **Agentic Commerce** programme, multiple **Senior AI Engineer** roles (Agentic Commerce, SDLC), and a Munich **Lead AI Systems Engineer** posting. Focus is applied GenAI/agentic features for e-commerce and AI-assisted software delivery, plus ML-driven observability (Elastic). This is production applied AI, not research, and it is corroborated by live job postings rather than marketing alone.

### Tech Stack

Derived from current job postings (SmartRecruiters/Built In), the Elastic customer story, and StackShare.

| Category | Technologies |
|---|---|
| **Primary language(s)** | Kotlin, Java (JVM core), Python, TypeScript/React |
| **AI/ML** | Applied GenAI / agentic systems, AI in SDLC, ML-assisted observability |
| **Cloud** | AWS (600+ accounts, 70+ services; SQS/SNS heavily used) |
| **Infrastructure** | Kubernetes (~40 clusters, ~20k containers, ~2,500 microservices), Terraform, Jenkins/CI |
| **Data** | PostgreSQL, Oracle, event-driven streaming; Elastic (observability, ~2TB/day) |
| **Other** | Microservices, event-driven architecture, cloud-native |

### Current Open Roles

Munich-based technical roles (verified live on the company SmartRecruiters board, July 2026):

| Role | Division/Team | Level | Key Tech | Link |
|---|---|---|---|---|
| Lead AI Systems Engineer | AI/Platform | Lead (IC-ish) | AI systems, cloud | https://careers.smartrecruiters.com/ZooplusSE |
| Engineering Director - Ecommerce | Ecommerce (loyalty/pricing) | Director | Strategy, AI/automation | https://careers.smartrecruiters.com/ZooplusSE |
| Engineer, Warehouse Automation & Solution Design | Supply chain | IC (logistics/automation, not software) | Automation design | https://careers.smartrecruiters.com/ZooplusSE |

Senior Software Engineer IC roles (Java/Kotlin/Python/React) are currently open only in **Madrid, Kraków, Wrocław and Vienna**, not Munich. No Munich-based IC SWE opening was live at the time of research.

**Verdict:** Modern JVM-first engineering (Kotlin/Java) with Python and React, on AWS + Kubernetes with an event-driven microservice architecture, and a real, growing applied-GenAI/agentic-commerce effort. Strong, current, production-grade stack. The fit problem is geographic, not technical: the IC engineering work is concentrated outside Munich.

---

## Section 7: Language

English is the working language for engineering: postings are in English, teams span 15+ nationalities across European hubs, and no engineering posting reviewed required German. German is optional.

**Verdict:** PASS.

---

## Section 8: Stability

### Financial Position

Revenue growing steadily (€2.68bn FY2023, +12%; ~€3bn guided FY2024; +18% in 9M-2025). Adjusted EBITDA positive and roughly doubling (€42.7m to €80.4m). However, the bottom line was a net **loss** (~€110.5m pre-tax in FY2023), driven substantially by a ~€141m warehouse-closure impairment. So the trajectory is improving operations against a still-negative statutory result.

### Financial Runway

Not a cash-burning startup: this is a >€2.6bn-revenue business with positive adjusted EBITDA, backed by two large PE owners (Hellman & Friedman, EQT). Detailed balance-sheet cash could not be read (NorthData figures are paywalled; the company is delisted so no public quarterly balance sheet). Runway risk here is not "will the cash run out" but **ownership transition**: the owners are publicly weighing a sale in 2025 or an IPO in 2026. A change of control could bring strategy shifts, cost programmes, or org restructuring.

| Scenario | Driver | Outlook |
|---|---|---|
| Optimistic | IPO 2026 at strong valuation | Fresh capital, stability, possible equity upside |
| Base case | Trade sale to new PE/strategic | Continuity with a new cost/strategy overlay |
| Stress | Valuation-driven "shrink to sell" continues | Further restructuring, reorg churn (already reported) |

Cash figure used: none directly observed (paywalled/private); assessment based on revenue scale, positive EBITDA, and PE backing.

### Warehouse-closure impairment (FY2023): cause

The €141.24m FY2023 charge was a **non-cash impairment triggered by a logistics-network overhaul**, not a cash loss. Through 2022-2023 Zooplus shifted fulfilment toward newer **outsourced, highly automated third-party centres** (GXO opened a ~60,000 sqm automated centre in Bor, Czech Republic in October 2023; FIEGE launched a Hungary centre), consolidating away from older, less-efficient facilities. Closing/exiting a facility whose fit-out and assets were no longer used forced a write-down of those assets, which is what produced the impairment. Mechanically, this single one-off charge is what turned an operationally-improving year (adjusted EBITDA nearly doubled to €80.4m) into a €110.5m pre-tax loss. It aligns with the reviewer theme of a "short-term focus on profitability" and the owners running the business leaner ahead of a sale. Caveat: the **exact closed site is not disclosed** in publicly accessible sources (the detail sits in the full 2023 consolidated report, register/paywall-only), so the specific location is UNVERIFIED; the *cause* (network optimisation / migration to automated GXO/FIEGE fulfilment) is well supported.

### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| 2023 | Fulfilment-centre closure (network optimisation) | ~€141m non-cash impairment | Logistics footprint; affected warehouse staff at the exited site (headcount figure not disclosed) |
| 2024-2025 | Corporate/office layoffs | Not disclosed | **Confirmed via reviews:** a current Munich Product Owner (Nov 2025) lists "lay offs" as a con; Zooplus's own official Glassdoor reply acknowledged "recent layoffs" and the need to ensure "stability for our teams." Also consistent with garden-leave/managed-exit accounts. Scale unquantified. |

Correction to the prior draft: layoffs **were** found. They are not a single large publicly-announced tech RIF, but a combination of the 2023 logistics-network write-down and quieter 2024-2025 corporate headcount reductions, corroborated directly by employee reviews and by Zooplus's own review responses. This fits the PE exit-grooming pattern (cost discipline to improve EBITDA before a sale).

**Verdict:** **CAUTION** - solid revenue and improving EBITDA, but net losses, confirmed (if unquantified) layoffs, active ownership-transition uncertainty, and ongoing restructuring/reorg churn.

---

## Section 9: Regulated Industry

E-commerce retail of pet supplies. No heavy sector-specific regime (no BaFin, FDA/IVDR, ISO 26262, EN 50128). Standard GDPR/consumer/e-commerce compliance only.

**Verdict:** PASS (low regulatory burden).

---

## Section 10: On-Call

Not explicitly addressed in the postings reviewed. Given a large customer-facing e-commerce platform (~2,500 microservices, high-volume ordering), backend/platform teams very likely carry some on-call rotation; internal AI-tooling or non-customer-path teams likely less so.

**Verdict:** CAUTION (team-dependent) - verify per team during interviews.

---

## Section 11: Interview Process

| Metric | Value |
|---|---|
| Difficulty | Medium (Glassdoor / Indeed) |
| Positive experience | ~Average (Indeed) |
| Average duration | ~2 weeks (Indeed) |
| Rounds | Not precisely retrieved (typically HR screen, technical/coding, system-design, team/hiring-manager) |

Reported as experience/design-oriented with a coding component, not extreme LeetCode grinding. Treat round count as UNVERIFIED.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | BORDERLINE: large modern engineering estate, but core business is retail |
| Not consulting | PASS: product/retail engineering, no client billing |
| Profitable | BORDERLINE: positive adjusted EBITDA, but statutory net loss |
| Employee count | PASS: ~1,615 globally, ~650 in Munich |
| English-speaking | PASS |
| Local entity + engineering contracts | PASS: zooplus SE, HRB 273759, direct employment |
| Glassdoor | 3.2 overall; **CEO approval 24%, outlook 19% positive**, 37% recommend; weak comp (2.8, falling)/career (2.6) |
| Indeed | CEO approval ~52.5%, medium interview, sub-scores unverified |
| Kununu | UNVERIFIED (blocked) |
| Salary | BELOW-to-COMPARABLE: IC ~€75K (below), employer senior/lead bands reach ~€112K; cash-only, no equity |
| AI/ML content | PASS: real applied GenAI / agentic commerce, growing |
| Computer-language/Tech-stack | STRONG: Kotlin/Java/Python/React, AWS, Kubernetes, event-driven |
| No on-call | CAUTION (team-dependent) |
| WLB / Stability | WLB genuinely good (3.7); stability CAUTION (net loss, confirmed layoffs, ownership transition, reorgs) |
| Regulated industry | PASS |
| Management culture | **CAUTION (raised):** recurring 2024-2026 toxic-mid-management / favouritism / "no direction" theme, tied to the PE takeover; no overtime or surveillance signal |
| Review themes | Mixed: praised WLB/flexibility/tech/mission; criticised pay, mid-management toxicity, chaos, layoffs |
| **No local IC engineering roles** | **CAUTION/FAIL for IC:** Senior SWE ICs are in Madrid/Kraków/Vienna, not Munich |

---

## Section 13: Verdict

**Overall recommendation: Monitor, do not actively pursue right now (as a Munich-based Senior Software Engineer IC).**

**Strengths.** Zooplus has a genuinely strong, modern engineering platform (Kotlin/Java/Python and React on AWS + Kubernetes, event-driven microservices at real scale) and a credible, growing applied-AI effort (agentic commerce, AI in the SDLC). English is the working language, hybrid is generous (60/40 plus 20 days abroad), and work-life balance reviews are among the better scores. The local entity is a real operating headquarters with direct employment.

**Hard blockers (numbered):**
1. **No Munich-based IC software-engineering role.** A live scan of 80 open positions showed every current Senior Software Engineer IC opening in Madrid, Kraków, Wrocław or Vienna. Munich carries only engineering **leadership** (Director, Lead AI Systems Engineer) and non-software (warehouse) technical roles. For a Senior Software Engineer IC seeking a Munich seat, there is effectively nothing to apply to today. This is the single decisive issue.
2. **Compensation below market.** Reported SWE total comp (~€75K Munich median, max ~€88K) sits below the Munich senior band (€85-124K), with no equity and cash-only structure. Corroborated by the weak Glassdoor comp score (2.9). Even with a senior premium, the ceiling looks short of the market floor for the target level.

**Secondary concerns (not individually disqualifying):**
- **Management culture (raised to a real concern after deeper review):** a recurring 2024-2026 theme of toxic/weak mid-management, favouritism, unfair and non-transparent pay/reviews, and "no direction," widely attributed to the culture shift after the Hellman & Friedman / EQT takeover. Very low CEO approval (24%) and business outlook (19% positive) corroborate weak confidence in leadership. Offsetting this: work-life balance and flexibility are genuinely good, and there is no 24/7 or surveillance signal. Net risk is MODERATE-to-HIGH on management quality, but localized to teams/managers rather than clearly systemic top-down abuse.
- Profitability is borderline (positive adjusted EBITDA, statutory net loss driven by a one-off FY2023 logistics impairment).
- Ownership-transition uncertainty (owners weighing a 2025 sale or 2026 IPO) plus ongoing restructuring, reorg churn, and **confirmed (if unquantified) 2024-2025 layoffs**.
- Weak career-opportunity score (2.6) and low overall recommend rate (37%).
- Kununu, GPTW, and the granular Glassdoor/Indeed breakdowns could not be verified.

**Recommendation.** Keep Zooplus on a watch list rather than applying now. It would flip to a genuine if: (a) a **Munich-based Senior Software Engineer / Staff-level IC** role opens (ideally in the AI/agentic-commerce or platform area, where the Munich Lead AI Systems Engineer posting hints at a growing local tech presence), **and** (b) the compensation for that role clears the ~€85K+ senior floor. If open to relocation, the Madrid/Kraków/Vienna IC roles are technically strong and worth considering on their own merits, but that defeats the Munich-commute advantage. If interviewing, verify: the specific Munich team and whether it is IC or lead-track, on-call expectations, the salary band against the senior market, and how the pending ownership change affects roadmap and headcount.

---

## Sources

- [Zooplus - Wikipedia](https://en.wikipedia.org/wiki/Zooplus)
- [Zooplus owners weighing 2025 sale or 2026 IPO - Mainsights](https://www.mainsights.io/ma-news/the-owners-of-pet-food-retailer-zooplus-hellman-and-friedman-and-eqt-substantiate-a-sale-in-2025-or-ipo-in-2026-amid-profitability-improvements)
- [Zooplus owners considering sale - GlobalPETS](https://globalpetindustry.com/news/zooplus-owners-reportedly-considering-sale-amid-valuation-projections-decline/)
- [Zooplus makes itself smaller to find new owner - RetailDetail EU](https://www.retaildetail.eu/news/leisure/zooplus-makes-itself-smaller-to-find-new-owner/)
- [zooplus and GXO open automated fulfilment centre in Bor, Czech Republic (Oct 2023) - GlobeNewswire](https://www.globenewswire.com/news-release/2023/10/05/2755546/0/en/zooplus-and-GXO-Open-Innovative-Logistics-Centre-to-Increase-Value-Proposition-for-Pet-Parents-in-Central-and-Western-Europe.html)
- [FIEGE launches new logistics centre for zooplus (Hungary)](https://www.fiege.com/en/newsroom/new-logistics-centre-hungary-fiege-launches-operations-zooplus)
- [Zooplus reviews (sorted, Munich, 2023-2026, via authenticated session) - Glassdoor.de](https://www.glassdoor.de/Bewertungen/Zooplus-Bewertungen-E257895.htm)
- [Zooplus employee count - Revelio Labs](https://www.reveliolabs.com/companies/zooplus-se/employees/)
- [zooplus SE stock overview - Roic AI](https://www.roic.ai/quote/ZO1.DE)
- [Zooplus revenue - CompaniesMarketCap](https://companiesmarketcap.com/zooplus/revenue/)
- [Zooplus financial statements - Macroaxis](https://www.macroaxis.com/financial-statements/ZOPLY)
- [Zooplus company profile - PitchBook](https://pitchbook.com/profiles/company/57240-28)
- [zooplus SE Investor Relations](https://corporate.zooplus.com/en/investor-relations/)
- [zooplus SE - NorthData](https://www.northdata.com/zooplus+SE,+M%C3%BCnchen)
- [Zooplus Careers - Our Locations](https://careers.zooplus.com/our-locations)
- [Zooplus Careers on SmartRecruiters](https://careers.smartrecruiters.com/ZooplusSE)
- [zooplus jobs - Built In](https://builtin.com/company/zooplus/jobs)
- [Senior Backend Engineer Java/Kotlin (Madrid) - SmartRecruiters](https://jobs.smartrecruiters.com/ZooplusSE/744000131877579-senior-backend-engineer-java-or-kotlin-all-genders-)
- [Software Engineer Java/Kotlin (Kraków) - SmartRecruiters](https://jobs.smartrecruiters.com/ZooplusSE/744000113740388-software-engineer-java-kotlin-12-months-ftc-all-genders-)
- [Engineering Director - Ecommerce (Munich) - Built In](https://builtin.com/job/engineering-director-ecommerce-all-genders/9715076)
- [Zooplus prepares for growth with Elastic Observability](https://www.elastic.co/customers/zooplus)
- [zooplus AG Tech Stack - StackShare](https://stackshare.io/zooplus-ag/zooplus-ag)
- [Zooplus Reviews - Glassdoor](https://www.glassdoor.com/Reviews/Zooplus-Reviews-E257895.htm)
- [Zooplus Software Engineer Reviews - Glassdoor](https://www.glassdoor.com/Reviews/Zooplus-Software-Engineer-Reviews-EI_IE257895.0,7_KO8,25.htm)
- [Zooplus review "Passed probation, then workplace mobbing" (Glassdoor DE, Jul 2026, RVW104622914)](https://www.glassdoor.de/Bewertungen/Bewertungen-Zooplus-E257895-RVW104622914.htm)
- [Zooplus Munich Office - Glassdoor](https://www.glassdoor.com/Location/Zooplus-Munich-Location-EI_IE257895.0,7_IL.8,14_IC4990924.htm)
- [Zooplus on Indeed (Germany)](https://de.indeed.com/cmp/Zooplus)
- [Zooplus Software Engineer Salary (Munich) - levels.fyi](https://www.levels.fyi/companies/zooplus/salaries/software-engineer/locations/munich-metro-region)
- [Zooplus Software Engineer Salary - levels.fyi](https://www.levels.fyi/companies/zooplus/salaries/software-engineer)
- [Senior Software Engineer Salary in Munich - levels.fyi](https://www.levels.fyi/t/software-engineer/levels/senior/locations/munich-deu)
- [Zooplus on Kununu (blocked at time of research)](https://www.kununu.com/de/zooplus)
