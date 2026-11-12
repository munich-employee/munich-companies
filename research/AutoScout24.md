# AutoScout24 - Full Research Report

_Researched: 2026-07-18_

> **Note on identity:** AutoScout24 is frequently conflated with **Scout24 SE** (the listed operator of ImmoScout24). They are separate companies. Scout24 SE **sold** AutoScout24 to Hellman & Friedman in early 2020. Any "Scout24 SE" revenue/EBITDA figures found online (€566M revenue, 61% EBITDA in 2024) belong to the **real-estate** business and are **not** AutoScout24. This report isolates AutoScout24 wherever possible and flags where only group-era or acquisition-era figures are available.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 1998 (as MasterCar AG, Munich) - 28 years |
| Employees | ~2,000 globally (19 countries) |
| Revenue | ~€235M at 2019/2020 acquisition; not separately filed since (est. €300-400M today, unverified) - **UNVERIFIED figure, but scale confirmed** |
| Profitability | Highly likely strongly profitable (see assessment) - **PASS (BORDERLINE on disclosure)** |
| Ownership | Private, PE-backed by **Hellman & Friedman** (since 2020) |
| Software-centric | Pure-play online marketplace / SaaS platform - **PASS** |

### Key People

- **Managing Directors (AutoScout24 GmbH, per NorthData Feb 2026):** Biliana Alabatchka, Felix M. Frank, Coram Williams. Michael Luhnen (long-time CEO) departed as MD as of Feb 2026.
- **Owner:** Hellman & Friedman (H&F), a global private equity firm, acquired AutoScout24 (plus FinanceScout24 and Finanzcheck) from Scout24 AG in a deal valued at **€2.9bn**, announced Dec 2019 and completed early 2020.

### Business Model

AutoScout24 is the **largest pan-European online car marketplace**: ~30M+ monthly users, 2M+ vehicle listings, 45,000+ dealer partners across 19 countries. Revenue comes from dealer subscriptions/listings, consumer lead-gen, and adjacent finance/insurance products. This is a classic high-margin classifieds/marketplace model, not services or consulting. As of end-2024 it also operates in **Canada** (Toronto office, following an acquisition in the automotive dealer-software / CMS space), which explains a cluster of "CMS" and "Fintech" engineering roles there.

**Software-Centric Assessment:** PASS. The product *is* software (a marketplace platform). Engineering, data science, and AI are core cost centres, not support functions. No consulting adjacency: engineers build and operate an internal product, do not bill client hours, and use engineering titles.

---

## Section 2: Local Commercial Entity in Germany

Verified via NorthData (northdata.com).

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **AutoScout24 GmbH** | HRB 128701 (AG München) | Tölzer Str. 16, 82031 Grünwald | "Establishment and operation of a data network to bring together supply and demand in the motor vehicle market, including related areas (information services, vehicle financing and insurance) and all related activities (esp. car trade)" |
| **AutoScout24 Engine GmbH** | HRB 265523 (AG München) | Bothestr. 11-15, 81675 München | "Provision of intra-group company-related services of any kind, in particular in the areas of **technology/infrastructure**, finance, law and human resources" |

**Verification:** Both entities are genuine, directly registered German GmbHs. The operating/marketplace entity (AutoScout24 GmbH) has a corporate purpose that explicitly covers operating the data network, not merely "sales and distribution" - so this is not a sales shell. Critically, **AutoScout24 Engine GmbH** exists specifically to employ technology/infrastructure staff at the Munich office (Bothestr. 11-15). Engineers are employed directly through a German entity (no PEO/EOR indication). Managing directors overlap between the entities, confirming these are integrated group companies, not arms-length vendors.

**Verdict:** PASS

---

## Section 3: Office Location

- **Office address:** Bothestraße 11-15, 81675 München (Bogenhausen/Berg-am-Laim border, eastern Munich). This is the "Campus Munich" and the registered seat of AutoScout24 Engine GmbH (the tech entity). The corporate/marketplace GmbH is registered in Grünwald, but the engineering campus is the Munich Bothestraße site.
- **Nearest public transit:** Tram lines 23 and 59 serve the Bothestraße/Berg am Laim corridor; the site is also reachable via Vogelweideplatz and the S-Bahn/U-Bahn network to the east.
- **Work model:** Hybrid. Current job postings state "Our New Ways of Working require weekly office attendance," with up to ~2 days/week in office. Not fully remote; not fully on-site.

---

## Section 4: Reviews

**GPTW:** No specific Great Place to Work Germany certification surfaced for AutoScout24. However, it holds the **kununu Top Company** award (see below), which the criteria treat as an equivalent strong positive signal.

#### Glassdoor

AutoScout24 overall on Glassdoor: **4.0 / 5** from ~60 reviews; **81%** would recommend to a friend. Sub-scores below are the global figures; Glassdoor's German/Munich/SWE filters do not hold enough reviews to break out reliably (the workforce is Munich-concentrated, so global ≈ Germany ≈ Munich here).

| Metric | Global | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | 4.0 (~60) | ~4.0 (small n) | ~4.0 (small n) | ~4.0+ (7 SWE reviews) |
| **WLB** | 3.9 | directional | directional | "Amazing WLB" (Jan 2024 senior dev review) |
| **Culture & Values** | 4.2 | directional | directional | directional |
| **Comp & Benefits** | 4.0 | directional | directional | directional |
| **Career Opportunities** | 4.0 | directional | directional | directional |
| **Diversity & Inclusion** | UNKNOWN | - | - | - |
| **% Recommend** | 81% | directional | directional | directional |
| **CEO Approval** | UNKNOWN (Glassdoor) | - | - | - |
| **Business Outlook** | UNKNOWN | - | - | - |

Note: With ~60 total reviews and Munich as the primary hub, the country/city/SWE filters overlap heavily and individually fall below the 20-review reliability threshold. Treat sub-splits as directional.

#### Kununu

Fetched via curl (WebFetch blocked by kununu). Slug `autoscout24`:

- **Overall score:** 4.2 / 5.0
- **Recommendation rate (Weiterempfehlung):** 81%
- **Total reviews:** 584 (employee reviews: 367)
- **Kununu Top Company:** **YES** (Top Company 2025, awarded Jan 2025)

This is the strongest single review dataset (584 reviews) and it is solidly positive.

#### Indeed

From Indeed company data (DE):

- **CEO approval:** ~95.4%
- **Interview:** Medium difficulty, average experience, ~1 month process
- **Salary satisfaction:** mixed (8 yes / 5 no); cost-of-living adequacy split (4 yes / 5 no)
- Sector: Internet & Web Services; size band listed as 201-500 on Indeed (understates the ~2,000 global figure, likely Munich-only)

Indeed does not expose enough filtered reviews to break WLB/Management/Culture cleanly by city/SWE; overall signal aligns with Glassdoor/Kununu (positive).

#### Blind / Teamblind

**0 reviews** on teamblind.com. No coverage (Blind skews US-tech; AutoScout24 is a European marketplace). No signal either way.

#### Review Themes (2023-2026)

**Positives:**
- Consistently praised **work-life balance** ("good/amazing work-life balance", calm pace)
- Strong **culture and values** (4.2) - "nice colleagues", "international team", positive team spirit
- **Benefits** repeatedly called out as generous ("wide range of benefits", per kununu Top Company writeup)
- Data-driven, learning-oriented, autonomous ("think in roles rather than functions")

**Negatives:**
- **Compensation "could be higher"** - the most recurring gripe; comp is fine but not top-of-market
- Some reviews cite typical **large-company bureaucracy / pace of change** and "good place to improve" framing (mild)
- No recurring red-flag themes (no toxic-leadership, surveillance, unpaid-overtime, or layoff patterns surfaced)

#### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | No signal. Very high CEO approval (~95% Indeed); culture rated 4.2. |
| 24/7 Work Expectation | No signal. WLB praised ("amazing work-life balance"). |
| Internal Surveillance | No signal. |
| Fear-driven Management | No signal. |
| Communication Breakdown | No systemic signal; minor "bureaucracy" mentions only. |
| Unpaid Overtime | No signal; reviewers describe balanced hours. |
| Silent Firings | No signal; no layoff/silent-firing reports found. |
| Work-Life Balance issues | None; WLB is a consistent *positive*. |

**Risk level: LOW.** The only recurring criticisms are (b) mild large-company bureaucracy and (a-absent) no systemic toxicity. Comp-could-be-higher is a compensation note, not a culture red flag.

---

## Section 5: Compensation

#### Salary Data

Senior Software Engineer, Germany/Munich:

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| TechPays (now levels.fyi) | Senior SWE, DE | ~€90-95K | minimal | ~€10K | **~€104.7K** | 7 |
| Indeed | Senior Software Engineer, DE | ~€87.6K (avg, base-ish) | - | - | ~€87.6K | 3 |
| Glassdoor | Software Engineer, Munich | directional | - | - | market-band | small n |

Munich market reference (levels.fyi, Jan 2026): Senior SWE total comp ranges roughly **€80.8K-€118K**, with broader Munich senior ranges quoted €85K-€124K. AutoScout24's ~€104.7K senior TC sits **mid-band**.

#### Equity / Stock

As a privately held, **PE-owned** company (Hellman & Friedman), there is **no public RSU/ESPP program** of the kind found at listed employers. Any long-term incentive is likely a management/leadership equity or phantom-share scheme concentrated at senior levels, not broad-based engineer RSUs. For an IC Senior Software Engineer, assume comp is **base + modest bonus**, with equity upside effectively zero unless in a leadership track. No pre-IPO option grant is advertised.

#### Verdict

**COMPARABLE.** ~€104.7K senior TC is squarely within the Munich senior band and consistent with a large, profitable, established (non-FAANG) local employer. It is **not above** market and lacks meaningful equity upside, matching the recurring "comp could be higher" review theme. It clears a typical large-profitable-corporate bracket but will not beat Big Tech Munich offices.

---

## Section 6: AI/ML & Tech Stack Fit

#### AI Strategy

AutoScout24 shows **genuine, applied AI investment**, not marketing veneer:
- A dedicated **"AI Enabler"** engineering track (open roles in Munich/Berlin) focused on integrating LLM APIs into products, plus GenAI safety/compliance/risk.
- Multiple **Data Science** roles including **Senior GenAI Data Scientist** and **Principal Data Scientist** in Munich.
- Engineering blog documents production AI tooling: an **AI debugging agent for their Kubernetes platform** (Grafana + Slack integration), and internal adoption of **Claude Code / Codex** agentic coding with token-optimisation practices.
- Core product AI: smart search, price/car valuation models, dealer ranking - all ML-backed marketplace features.

This is **applied/production AI** in a consumer marketplace context, with a live GenAI push, rather than pure research.

#### Tech Stack

Derived from current job postings (primary), the engineering blog (tech.autoscout24.com), and the Scout24/AutoScout24 GitHub org.

| Category | Technologies |
|---|---|
| **Primary language(s)** | Scala (historically primary; Play Framework, Akka actors/streams/http), Java + Spring Boot (backend), Kotlin (Android) |
| **AI/ML** | LLM API integration, GenAI tooling (Claude Code, Codex), Python data science stack, ML-backed search & valuation |
| **Cloud** | AWS ("AWS-first" architecture principle): DynamoDB, Kinesis, Lambda, CloudFormation, SNS, SQS, Aurora, Lex |
| **Infrastructure** | Kubernetes, microservices, GitHub (1000+ repos), Grafana observability |
| **Data** | PostgreSQL, DynamoDB, Apache Kafka, Elasticsearch, AWS QuickSight (BI) |
| **Other** | GraphQL + REST APIs, JS/SCSS front-end, Dagger 2 / Rx / Coroutines / Jetpack Compose (mobile) |

#### Current Open Roles

Verified active on the AutoScout24 Greenhouse board (job-boards.greenhouse.io/autoscout24):

| Role | Division/Team | Level | Key Tech | Link |
|---|---|---|---|---|
| Senior Software Engineer / AI Enabler (m/f/d) | AI Enablement | Senior (5+ yrs) | Java, Spring Boot, AWS, Kafka, PostgreSQL/DynamoDB, Scala, LLM APIs | [greenhouse](https://job-boards.greenhouse.io/autoscout24/jobs/7629457003) |
| Senior Software Engineer - Android, AI Enabler (m/f/d) | Mobile / AI | Senior | Kotlin, Jetpack Compose, GraphQL, AWS | [greenhouse](https://job-boards.greenhouse.io/autoscout24/jobs/7653933003) |
| Senior GenAI Data Scientist (m/f/d) | Data Science | Senior | Python, GenAI/LLMs | Greenhouse (Munich) |
| Principal / Senior Data Scientist (m/f/d) | Data Science | Senior/Principal | Python, ML | Greenhouse (Munich) |
| Salesforce Developer (m/f/d) | Business Systems | Mid/Senior | Salesforce/Apex | Greenhouse (Munich) |

Multiple additional Senior Software Engineer roles are open in **Toronto** (CMS/Fintech) but are not Munich/remote-eligible. The Munich AI Enabler roles are the direct fits.

**Verdict:** Scala- and Java/Spring-Boot-centric backend engineering on an AWS-first, Kubernetes/Kafka platform, with a live, well-resourced GenAI/LLM applied-AI push (AI Enabler track, GenAI data science, internal agentic tooling). This is production/applied engineering at marketplace scale, not research. Strong tech-stack and AI-content fit for a Senior Software Engineer who wants applied GenAI without leaving mainstream JVM/cloud work.

---

## Section 7: Language

Job postings are published in **English**; the AI Enabler role and data science roles are written in English with English as the working language. German is not listed as a hard requirement (application forms are bilingual, but fluency in German is not mandated). The workforce is explicitly described as an "international team." English-required, German-optional.

**Verdict:** PASS

---

## Section 8: Stability

#### Financial Position

AutoScout24 is the **dominant, profitable, cash-generative** online car marketplace in Europe. Directly observed public figures are limited because, since the 2020 H&F take-private, standalone audited accounts are consolidated under H&F holding structures rather than published as a listed entity. Key stability signals:
- **Market position:** #1 pan-European car marketplace, 30M+ monthly users, 45,000+ dealers, 19 countries. Strong network-effect moat.
- **Acquisition economics:** H&F paid **€2.9bn** in 2019/2020 against ~€235M revenue (~12x revenue). PE buyers pay that multiple only for high-EBITDA-margin, durable-cashflow assets. Its former sibling ImmoScout24 (Scout24 SE) runs a ~61% EBITDA margin on the same classifieds model, indicating the marketplace economics here are similarly strong.
- **Expansion:** Actively investing (Canada entry end-2024, GenAI hiring), consistent with a growing, not distressed, business.

#### Financial Runway (PE-backed)

AutoScout24 is PE-backed but is a **mature, profitable operating business, not a cash-burning startup**, so a bottom-up burn model is not the right lens (analogous to the "skip the model for profitable entities" guidance). It funds operations from marketplace subscription revenue.

| Cost line | Annual estimate |
|---|---|
| Staff (~2,000 × ~€110K fully-loaded) | ~€220M |
| Tech/AWS, marketing, G&A | ~€80-120M |
| **Total gross cost** | **~€300-340M/year** |

| Revenue source | Est. annual inflow |
|---|---|
| Dealer subscriptions + listings + consumer + finance/insurance | ~€300-400M+ (grown from €235M in 2019) |

The business is **self-funding and cash-generative**; runway is not a concern. The relevant PE-specific risk is not insolvency but **leverage/exit dynamics** (see below), not a funding cliff. _Cash figures are estimates; standalone audited cash line not publicly filed - marked UNVERIFIED._

#### Layoffs

No layoff events surfaced for AutoScout24 (TrueUp/press search). The company is hiring across Munich, Berlin, and Toronto. **No layoffs on record.**

**Verdict:** PASS. The one caveat is PE ownership: H&F has held since 2020 (a long hold by PE standards), so an **exit event (secondary sale, IPO, or recapitalisation) within the next 1-2 years is plausible** and could bring reorganisation. This is a CAUTION on ownership trajectory, not on financial solvency.

---

## Section 9: Regulated Industry

AutoScout24's core business (online classifieds/marketplace) is **not** a heavily regulated sector: no BaFin/Solvency/DORA safety-case regime governs the listings platform. It touches adjacent **auto finance/insurance lead-gen** (some consumer-finance and GDPR/consumer-protection obligations), and the Canadian CMS/fintech unit carries more compliance, but the Munich engineering roles are on the marketplace/AI platform, not a safety-critical or prudentially-regulated system. Practical engineering impact is light (standard GDPR, no formal safety cases, no ISO 26262/EN 50128-style overhead).

**Verdict:** PASS (low regulatory burden)

---

## Section 10: On-Call

The Munich **Senior Software Engineer / AI Enabler** posting contains **no on-call mention**. AI-enablement and internal-tooling/data-science roles typically do not carry pager duty. That said, AutoScout24 runs a large 24/7 consumer marketplace on AWS, so **product/platform SRE-adjacent teams likely do carry on-call**. For the AI Enabler / data science track specifically, on-call is unlikely.

**Verdict:** CAUTION (team-dependent) - confirm for the specific team; the target AI Enabler role shows no on-call requirement.

---

## Section 11: Interview Process

Based on Glassdoor/Indeed signals:

| Metric | Value |
|---|---|
| Difficulty | Medium (Indeed); ~3/5 directional (Glassdoor, small n) |
| Positive experience | "Average" (Indeed) |
| Average duration | ~1 month |
| Rounds | ~3-4 (typical: recruiter screen → technical/coding → system design → team/culture) |

The process is described as experience- and design-oriented with a moderate technical bar, not an extreme LeetCode gauntlet. Medium difficulty and month-long timeline are typical for a Munich scale-up/marketplace.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | PASS - pure online marketplace/SaaS platform |
| Not consulting | PASS - internal product, no client billing |
| Profitable | PASS (strong marketplace economics; standalone figures not publicly filed) |
| Employee count | PASS - ~2,000 globally |
| English-speaking | PASS - English working language, German optional |
| Local entity + engineering contracts | PASS - AutoScout24 Engine GmbH (HRB 265523) employs tech staff directly in Munich |
| Location / work model | Munich office near tram 23 / bus 59 |
| Glassdoor | 4.0 / 81% recommend (small n) |
| Indeed | Positive; ~95% CEO approval |
| Kununu | 4.2 / 81% / Top Company 2025 / 584 reviews - strong |
| Salary | COMPARABLE - ~€104.7K senior TC, mid-band, no broad equity |
| AI/ML content | PASS - live GenAI/AI Enabler track, GenAI data science, applied ML |
| Computer-language/Tech-stack | PASS - Scala + Java/Spring Boot, AWS-first, Kubernetes/Kafka |
| No on-call | CAUTION - team-dependent; AI Enabler role shows none |
| WLB / Stability | PASS - WLB a consistent positive; financially stable |
| Regulated industry | PASS - low burden |
| Review themes | Positive (WLB, culture, benefits); only "comp could be higher" recurs |
| Ownership/exit risk | CAUTION - H&F-owned since 2020; exit event plausible in 1-2 yrs |

---

## Section 13: Verdict

**Overall recommendation: Actively pursue.** AutoScout24 is a strong fit and currently has a directly relevant open Senior Software Engineer role in Munich.

**Strengths:**
- Europe's #1 car marketplace: a genuinely software-centric, profitable, cash-generative business with a network-effect moat, ~2,000 staff, and no layoff history.
- Consistently positive culture signals: **kununu 4.2 / Top Company 2025 (584 reviews)**, Glassdoor 4.0, ~95% CEO approval, with **work-life balance** as a repeated praise point and **no toxic-leadership red flags** (LOW toxicity risk).
- Strong technical and AI fit: modern JVM stack (Scala, Java/Spring Boot) on an AWS-first, Kubernetes/Kafka platform, plus a live, well-funded **GenAI "AI Enabler"** track and GenAI data science: applied production AI, not marketing.
- Directly employed via a German entity (AutoScout24 Engine GmbH); English working language.

**Hard blockers:** None. Every hard criterion passes.

**Secondary concerns (CAUTION, not disqualifying):**
1. **Compensation is comparable, not above** (~€104.7K senior TC, mid-band) with **no broad-based equity** (PE-owned): matches the only recurring review complaint. Do not expect Big-Tech-Munich comp.
2. **PE ownership / exit risk:** H&F has held since 2020; a sale, IPO, or recap in the next 1-2 years is plausible and could trigger reorganisation. Financial solvency is not at risk; ownership continuity is the uncertainty.
3. **On-call is team-dependent:** the AI Enabler role shows none, but platform/SRE-adjacent teams likely carry it.
4. **Standalone financials are not publicly filed** since the take-private; profitability is inferred from market position and acquisition economics rather than audited public accounts.

**Recommendation:** Apply to the **Senior Software Engineer / AI Enabler (Munich)** role. It is active, hybrid (~2 days/week in office), English-language, and a clean stack/AI fit. During interviews, verify: (a) the exact base+bonus band and whether any long-term incentive applies at IC level, (b) on-call expectations for the specific AI Enabler team, and (c) any near-term ownership/exit plans that could affect team stability.

---

## Sources

- [Hellman & Friedman to Acquire AutoScout24 (hf.com)](https://hf.com/hf-to-acquire-autoscout24/)
- [Hellman & Friedman buys AutoScout24 in €2.9bn deal (Unquote)](https://www.unquote.com/dach/official-record/3017695/hellman-friedman-buys-autoscout24-in-eur29bn-deal)
- [Scout24 AG to sell AutoScout24 (scout24.com)](https://www.scout24.com/en/news-media/news/detail/scout24-ag-to-sell-autoscout24-for-attractive-valuation)
- [AutoScout24 PitchBook profile](https://pitchbook.com/profiles/company/56916-91)
- [AutoScout24 Crunchbase profile](https://www.crunchbase.com/organization/autoscout24)
- [AutoScout24 Owler profile](https://www.owler.com/company/autoscout24)
- [AutoScout24 company portrait](https://www.autoscout24.com/company/company-profile/portrait/)
- [AutoScout24 Campus Munich](https://www.autoscout24.com/company/campus-munich/)
- [NorthData - AutoScout24 GmbH (HRB 128701)](https://www.northdata.com/AutoScout24%20GmbH,%20Gr%C3%BCnwald/Amtsgericht%20M%C3%BCnchen%20HRB%20128701)
- [NorthData - AutoScout24 Engine GmbH (HRB 265523)](https://www.northdata.com/AutoScout24%20Engine%20GmbH,%20M%C3%BCnchen/HRB%20265523)
- [AutoScout24 Glassdoor Reviews](https://www.glassdoor.com/Reviews/AutoScout24-Reviews-E3137050.htm)
- [AutoScout24 Glassdoor Munich Reviews](https://www.glassdoor.com/Reviews/AutoScout24-M%C3%BCnchen-Reviews-EI_IE3137050.0,11_IL.12,19_IC4990924.htm)
- [AutoScout24 Glassdoor Senior Software Engineer Interviews](https://www.glassdoor.com/Interview/AutoScout24-Senior-Software-Engineer-Interview-Questions-EI_IE3137050.0,11_KO12,36.htm)
- [AutoScout24 Kununu profile](https://www.kununu.com/de/autoscout24)
- [AutoScout24 Indeed company page](https://de.indeed.com/cmp/Autoscout24)
- [AutoScout24 Teamblind reviews](https://www.teamblind.com/company/AutoScout24/reviews)
- [TechPays / levels.fyi - AutoScout24 senior engineering salaries](https://techpays.com/europe/germany/autoscout24/senior)
- [TechPays - AutoScout24 engineering salaries](https://techpays.com/europe/germany/autoscout24/eng)
- [levels.fyi - Senior Software Engineer Munich](https://www.levels.fyi/t/software-engineer/levels/senior/locations/munich-deu)
- [AutoScout24 Glassdoor Salaries Munich](https://www.glassdoor.com/Salary/AutoScout24-Munich-Salaries-EI_IE3137050.0,11_IL.12,18_IC4990924.htm)
- [AutoScout24 Engineering Blog](https://tech.autoscout24.com/blog/)
- [AutoScout24 Engineering Blog - First year at AutoScout24](https://tech.autoscout24.com/blog/posts/first-year-at-autoscout24/)
- [Scout24/AutoScout24 hiring & tech (GitHub)](https://github.com/Scout24/hiring)
- [AutoScout24 Greenhouse job board](https://job-boards.greenhouse.io/autoscout24)
- [Senior Software Engineer / AI Enabler (Munich) - Greenhouse](https://job-boards.greenhouse.io/autoscout24/jobs/7629457003)
- [Senior Software Engineer - Android, AI Enabler - Greenhouse](https://job-boards.greenhouse.io/autoscout24/jobs/7653933003)
- [Senior Software Engineer (AI Enabler) - Welcome to the Jungle](https://www.welcometothejungle.com/en/companies/autoscout24/jobs/senior-software-engineer_munich_b7edz6hj)
- [AutoScout24 OfferZen profile](https://www.offerzen.com/companies/autoscout24)
- [Scout24 SE 2024 Annual Report (context: separate real-estate company)](https://www.scout24.com/media/scout24/Investor_Relations/Berichte_und_Praesentationen/2024_EN/Scout24_Annual_Report_2024_EN.pdf)
