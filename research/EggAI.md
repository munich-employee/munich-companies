# EggAI - Full Research Report

_Researched: 2026-11-03_

> **Critical Disqualifiers**
> 1. **Consulting / forward-deployed engineering model.** EggAI Technologies GmbH's registered purpose starts with "Beratung von Unternehmen" (business consulting). Its own pages sell "forward-deployed engineering", "asset-based services", "outcome-based partnership" and "managed services". The Senior Software/AI Engineer posting puts engineers "in a team of 2 to 6 engineers on a client project". A finance posting calls the company a "100% remote AI consulting and development startup". This is a direct hit on the criterion "No consultant/forward-deployed/solution-engineer type of arrangement".
> 2. **On-call is named in the postings.** The engineering roles ask for "deployment, monitoring, on-call or equivalent" and "SLOs, observability, incident response" for platforms "you own in production, not just at handover". The services page also offers managed operations of client AI systems.
> 3. **No review data and a very small, young company.** Founded late 2024, roughly 30 people on LinkedIn (company size bucket "2-10", plausibly because many are freelancers). It has no Glassdoor, Kununu or Blind profile. No disclosed funding and no public financials.
>
> The full report follows for completeness.
>
> **Name collision:** `eggai.tech` ("EGGai-v1 Large Behavior Model", customer digital twin) is a different product. Its contact address is `eggai@amity.co`, so it belongs to Amity, not to EggAI Technologies (`egg-ai.com`). It is not covered here.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | Articles of association Nov 2024, register entry 16 Jan 2025 (~2 years) |
| Employees | 32 associated LinkedIn members (LinkedIn size bucket "2-10 employees"). Postings mention "employees and freelancers" across several European countries |
| Revenue (FY2025) | Not disclosed. No annual accounts visible yet on NorthData |
| Profitability | UNKNOWN. Consulting revenue model (client engagements), no disclosed VC round - **BORDERLINE / UNVERIFIED** |
| Ownership | Private, founder-held. Two shareholder holdings shown on NorthData (28.8% and 47.9%) via founders' holding companies. Small capital increase from €25,000 to €26,069 (Aug 2025), which suggests a minor angel or partner stake. No external VC round found |
| Software-centric | Builds an open-source multi-agent framework and reusable "accelerators", but revenue comes from client engagements - **FAIL** (see Consulting-Adjacency Assessment) |

**What the company does:** EggAI sells "agentic workforce" transformation to large enterprises: AI-first process re-engineering, building and integrating agentic systems in client environments (SAP, Salesforce, ServiceNow, custom systems), setting up agent platforms on the client's cloud, and then running them as a managed service. Its engineering assets are the MIT-licensed EggAI Multi-Agent Meta Framework (Python SDK), a "composable multi-agent platform", agentic QualOps / code-review tooling and an "AI-powered SW development framework". A reference case on its site is a QualOps agent workforce reviewing a 145k-line Angular codebase, deployed on Kubernetes on Azure. It also presented an "EggAI Technologies Foundry@STACKIT" sovereign agent platform with Schwarz Digits / STACKIT. In October 2026 it registered a UK establishment (Companies House FC043646) and is opening "EggAI Labs" in Tübingen.

**Key People**
- **Dr. Jürgen Laartz** - Co-founder and Managing Director; ex-McKinsey Director (senior partner) per LinkedIn titles; writes the company blog.
- **Marcus Purzer** - Managing Director.
- **Dr. Jan Heurich** - Managing Director (appointed 2025); ex-McKinsey, PhD Physics per LinkedIn.
- **Robin Prothmann** - Business leadership.
- **Technology leadership:** Damian Beresford, Leo Casarsa, Koji Wakayama, Kentaro Wakayama. Kentaro Wakayama was a founding managing director and left that role in April 2026. The Wakayamas and several engineers are linked to Veryfront / TOMcode / Coder Society (Berlin dev agencies).
- A CAIO (ex-McKinsey) leads the new Tübingen Labs.

**Funding History**

| Date | Event | Amount | Notes |
|---|---|---|---|
| Nov 2024 / Jan 2025 | Incorporation | €25,000 share capital | Founders |
| Aug 2025 | Capital increase | to €26,069 (+€1,069 nominal, ~4.1% new shares) | Investor not disclosed; premium unknown |
| - | VC rounds | None found | Startup-directory listing says "funding rounds not available"; no press coverage |

**Business Model:** Consulting and delivery firm with reusable IP. Clients are "make-type" (Plan, Build, Operate, Transfer) or "buy-type" (Plan, Integrate, Operate + managed service). Senior management advisers and "outcome managers" sell and steer engagements; engineers are forward-deployed into client organisations.

### Software-Centric Assessment

The open-source framework is real (Python, 56 stars, active commits by EggAI engineers through Nov 2026) and the company invests in internal assets and a Labs unit. However, the website states plainly: "EggAI provides asset-based services ... We forward-deploy these engineers to your organization to make AI work for you - our service." The product is the engagement; the framework is "glue code" (their words) that accelerates delivery. **FAIL** on software-centric.

### Consulting-Adjacency Assessment

| Test | Evidence |
|---|---|
| Self-identifies as consulting? | **Yes.** Senior Accountant posting: "EggAI is a fast-growing, 100% remote AI consulting and development startup". LinkedIn industry: "IT Services and IT Consulting". |
| Registered purpose | "Beratung von Unternehmen und die SW-Entwicklung" (consulting first). |
| Engineers bill to clients / work on client deliverables? | **Yes.** "You will work in a team of 2 to 6 engineers on a client project"; "Work directly with the client's engineers and with our project manager / product owner"; "Client-facing ability" is a requirement. Platform role: "one project at a time". |
| Consultant career titles? | **Yes.** LinkedIn titles include "Managing Consultant" (x2), "Senior Associate ... ex-Deloitte", "Partner@EggAI", "Senior Management Advisors", "Outcome Managers". |
| External deliverable vs internal product? | External: "We design, implement and operate agentic systems" for enterprise clients; "Forward-deployed engineering" is a named service. |

Verdict: **consulting firm with an engineering arm**, founded and led by former McKinsey partners.

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **EggAI Technologies GmbH** | Amtsgericht München HRB 299037 (EUID DED2601V.HRB299037; LEI 529900SDW8RCN5LAMI98) | Seidlstraße 5, 80335 München | "Beratung von Unternehmen und die SW-Entwicklung einschließlich damit verbundener Tätigkeiten, wobei erlaubnispflichtige Tätigkeiten hiervon explizit ausgenommen sind." |
| EggAI Technologies GmbH (UK establishment) | Companies House FC043646 (registered 14 Oct 2026) | UK | Overseas branch, 3 directors |

The German GmbH is the operating entity (imprint, managing directors, register court Munich). The purpose covers software development, so engineering work is covered, but consulting is listed first and matches the actual business. Postings are "Full-time Remote (EU & UK)" and the accounting posting mentions "local payroll providers" and "freelancers" across Europe, so some staff are contracted outside the GmbH. A Germany-based hire would most likely sit on the German GmbH payroll (German payroll is handled by the external tax advisor), but whether senior engineers are hired as employees or freelancers is not stated.

**Verdict:** PASS with CAUTION (a real Munich GmbH, but the purpose is consulting-led and part of the workforce is freelance)

---

## Section 3: Office Location

- **Office address:** Seidlstraße 5, 80335 München (Maxvorstadt, St. Benno-Viertel), per the imprint and NorthData (address updated 22 Apr 2026). LinkedIn still lists an older HQ at Prinzregentenstraße 61, 81675 München (Bogenhausen). Nominatim geocodes Seidlstraße 5 to 48.14329, 11.55640.
- **Nearest public transport** (OSM Overpass):
  - Hopfenstraße tram stop: ~180 m (lines not resolved, Overpass rate-limited)
  - München Hbf / Starnberger Bahnhof (regional rail, platforms 27-36): ~200 m
  - Karlstraße tram stop: ~290 m (tram 20, 21; bus 68; night tram N20)
  - München Hauptbahnhof (long-distance, S-Bahn trunk line): ~290-350 m
  - Hauptbahnhof Nord tram stops: ~315-385 m
  - Hauptbahnhof U-Bahn: ~495 m; Stiglmaierplatz U-Bahn: ~515 m; Königsplatz U-Bahn: ~540 m
- **Work model:** Fully remote. Engineering postings: "Full-time Remote (EU & UK)" and "Full-time Remote (EU only)". Accountant posting: "100% remote work". The exception is the Tübingen Labs working-student role (in person). Client engagements may require on-site presence at the client; not stated.

---

## Section 4: Reviews

**GPTW:** Not listed on greatplacetowork.de; no certification found.

#### Glassdoor

No company profile. A search on glassdoor.de (via CDP) for "EggAI" returns: "Wir haben keine Unternehmen gefunden, die mit „EggAI" übereinstimmen" (no companies, no salaries, no interviews).

| Metric | Global | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | n/a (0 reviews) | n/a | n/a | n/a |
| **WLB** | n/a | n/a | n/a | n/a |
| **Culture & Values** | n/a | n/a | n/a | n/a |
| **Comp & Benefits** | n/a | n/a | n/a | n/a |
| **Career Opportunities** | n/a | n/a | n/a | n/a |
| **Diversity & Inclusion** | n/a | n/a | n/a | n/a |
| **% Recommend** | n/a | n/a | n/a | n/a |
| **CEO Approval** | n/a | n/a | n/a | n/a |
| **Business Outlook** | n/a | n/a | n/a | n/a |

#### Kununu

- **Overall score:** UNKNOWN. No profile.
- **Recommendation rate:** UNKNOWN
- **Total reviews:** 0
- **Kununu Top Company:** NO

Tried slugs `eggai`, `eggai-technologies`, `eggai-technologies-gmbh` with curl (HTTP 405, bot wall), then the Kununu search via CDP: "EggAI" only returns unrelated Swiss companies (ZAUGG AG Eggiwil, Bergrestaurant Eggalm).

#### Blind / Teamblind

`teamblind.com/company/EggAI/` returns "Page not found!". No data.

#### Review Themes (2025-2026)

No employee reviews exist on any platform. The only signals come from postings and LinkedIn:

**Positives:**
- Postings are unusually concrete and honest about the work ("you own it in production, not just at handover"; "one project at a time, so you go deep").
- Short interview process stated up front (3 steps, see Section 11), with a choice of technical format.
- Senior, experienced leadership network; investment in open source and an internal R&D Labs unit.
- Fully remote, English working language.

**Negatives:**
- Client-project delivery model with client-facing duties (consulting hard red flag).
- On-call / incident response is expected of engineers.
- Hiring "through our network only" (company page), so access depends on referrals; LinkedIn now shows Easy Apply postings too.
- Processes are still forming ("We don't have fully established processes yet").
- Mixed employee/freelancer workforce spread across Europe; headcount evidence is inconsistent (2-10 bucket vs 32 members).

#### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | No data. No reviews exist. |
| 24/7 Work Expectation | Not stated. Consulting with managed operations of client AI systems raises the risk. |
| Internal Surveillance | No data. |
| Fear-driven Management | No data. Culture language is "high standards, take ownership of outcomes ... candid feedback". |
| Communication Breakdown | No data. |
| Unpaid Overtime | No data. Typical exposure in outcome-based consulting contracts. |
| Silent Firings | No data. No works council (see Section 8). |
| Work-Life Balance issues | No data. On-call and incident response are listed requirements. |

**Risk level: UNKNOWN (no evidence either way)**. Structural risk is MODERATE: a young consulting firm led by former strategy consultants, with outcome-based client commitments, on-call duties and no works council.

---

## Section 5: Compensation

#### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| levels.fyi | - | - | - | - | - | 0 (no company page; HTTP 403 on `levels.fyi/companies/eggai`) |
| Glassdoor | - | - | - | - | - | 0 (no company profile) |
| Job postings | Senior Software/AI Engineer | not disclosed | - | - | - | 0 |

No Munich percentile data exists for this company. Working-student posting promises "competitive compensation, including recognition for exceptional contributions".

#### Equity / Stock

No equity programme mentioned in any posting. Ownership is concentrated in founder holding companies; the small 2025 capital increase may reflect a partner stake. Any equity offered would be illiquid in a services firm without a VC exit path.

#### Verdict

**UNVERIFIED.** Consulting firms can pay senior engineers well per day rate (especially freelance), but there is no data at all.

---

## Section 6: AI/ML & Tech Stack

#### AI Strategy

Genuine applied AI: the whole business is LLM-based agentic systems for enterprises (triage/routing agents, matching agents, document "de-/codification", agentic code review and SDLC automation, EvalOps). They publish an "Agentic Architecture Doctrine" and a meta-framework whitepaper, write about agent control planes and governance, and are starting a Tübingen Labs unit on evaluation of non-deterministic AI systems. The AI is delivered into client environments rather than into an EggAI product.

#### Tech Stack

Sources: current LinkedIn postings (Senior Software/AI Engineer, Senior Platform Engineer, AI Builder working student, retrieved via LinkedIn voyager API over CDP), the GitHub organisation `eggai-tech` (15 public repos, GitHub API), the SDK `pyproject.toml`, and the company technology / AI-for-IT pages.

| Category | Technologies |
|---|---|
| **Primary language(s)** | Python (stated as "primary"), TypeScript/JavaScript; Go/Java/C#/Rust engineers "in scope" if willing to work in Python |
| **AI/ML** | LLM / agentic systems; EggAI SDK (async multi-agent messaging), integrations with DSPy, LangChain, LlamaIndex, LiteLLM; A2A SDK, FastMCP; OpenTelemetry tracing; evals / EvalOps |
| **Cloud** | AWS, GCP, Azure (client's choice); STACKIT (sovereign); reference case on Azure |
| **Infrastructure** | Kubernetes, Terraform, Helm/Kustomize, ArgoCD/Flux, Prometheus/Grafana, OpenTelemetry, Docker |
| **Data** | Kafka and Redis (via FastStream), databases with schema/query/migration work, Databricks (buy-type clients) |
| **Other** | Pydantic, AnyIO, Poetry; client platforms SAP, Salesforce, ServiceNow; Angular in client codebases; Odoo internally |

**Summary:** Python-centric applied LLM/agent engineering, with a TypeScript secondary layer and a Kubernetes/Terraform platform layer on whichever hyperscaler the client uses (Azure, AWS, GCP, STACKIT). Production engineering for client deployments rather than research.

---

## Section 7: Language

All engineering postings are in English. The AI Builder posting states "communicate fluently in English, our company language". The Senior Accountant posting requires German C1/C2 for German accounting but notes "English is often the working language". No German requirement for engineering roles, although clients are largely German/European enterprises and client-facing work may favour German speakers.

**Verdict:** PASS

---

## Section 8: Stability

#### Financial Position

No annual accounts visible on NorthData yet (the first fiscal year after a Nov 2024 incorporation would be filed in late 2026 at the earliest). Revenue, profit and cash are UNKNOWN. Signals of commercial traction: hiring a Senior Accountant for multi-country finance operations, a UK establishment (Oct 2026), a Labs unit opening, a STACKIT partnership, and blog claims of production systems in banking, insurance, asset management, health data, medtech and the public sector.

#### Financial Runway

No funding round, cash figure or burn data is public. NorthData shows only the register history; Bundesanzeiger has no filing yet. Bottom-up model under explicit assumptions:

| Cost line | Annual estimate |
|---|---|
| Staff and freelancers (~30 people × ~€130K blended fully-loaded cost) | ~€3.9M |
| Tooling, LLM/cloud, travel, office, admin | ~€0.4M |
| **Total gross burn** | **~€4.3M/year** |

| Revenue source | Est. annual inflow |
|---|---|
| Client engagements (~15-20 billable staff × ~€1,200/day × ~180 days) | ~€3.2M-4.3M/year |
| **Total revenue offset** | **~€3-4M/year** |

| Scenario | Net burn | Cash at hand | Runway | Next round needed by |
|---|---|---|---|---|
| Optimistic | ~€0 (break-even on billings) | UNKNOWN | Indefinite while utilisation holds | Not needed |
| Base case | ~€0.5-1M/year | UNKNOWN | Depends on founders' capital | ~2027 if cash < €1M |
| Stress (lost anchor client) | ~€2M/year | UNKNOWN | < 1 year without new capital | ~2027 |

Cash at hand: **not observable** (no filing; share capital only €26,069). A services firm can run near break-even from day rates, so the main risk is client concentration and utilisation, not a VC cliff.

#### Layoffs

No layoffs found. Kentaro Wakayama left the managing-director role in April 2026 (remains in technology leadership on the website).

#### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | NO (very likely) | No mention anywhere; ~30 people, mostly remote across Europe, founded 2025 |
| Collective agreement | NONE | No tariff wording in any posting |
| European works council | N/A | - |
| Conflict signals | None found | No reviews exist |

**Verdict:** CAUTION (young, unaudited, consulting revenue; no co-determination)

---

## Section 9: Regulated Industry

EggAI itself is not regulated. Its clients are (banking, insurance, asset management, health data, medtech, public sector), so engineers would face client security reviews, BaFin/DORA-style controls, data residency (sovereign cloud) and governance documentation inside engagements.

**Verdict:** CAUTION (client-driven regulatory overhead varies per engagement)

---

## Section 10: On-Call

Explicit in the postings:
- Senior Software/AI Engineer: "Has owned code in production - deployment, monitoring, on-call or equivalent"; "you own what you ship, including after it's reached production".
- Senior Platform Engineer: "you own it in production, not just at handover"; "Own reliability for what you run - SLOs, observability, incident response, cost"; "on-call incident response".
- Services page: "Operations Management ... providing full managed services".

**Verdict:** FAIL (on-call / incident response is part of the role)

---

## Section 11: Interview Process

No Glassdoor interview data. The Senior Software/AI Engineer posting describes the process:

| Metric | Value |
|---|---|
| Difficulty | UNKNOWN (no Glassdoor data) |
| Positive experience | UNKNOWN |
| Average duration | UNKNOWN |
| Rounds | 3 |

1. Introductory call (30 min)
2. Behavioural / management interview (60 min)
3. Technical interview (60 min): choice of walking through own code, live coding, or a take-home exercise

Experience-focused, not LeetCode-heavy. The company page says it hires "through our network only" with a referral; the current LinkedIn postings have Easy Apply.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | FAIL: framework and accelerators exist, but revenue is client engagements |
| Not consulting | **FAIL**: self-described "AI consulting and development startup"; forward-deployed engineers on client projects; consultant titles |
| Profitable | UNKNOWN: no filings yet, no disclosed funding |
| Employee count | ~30 (LinkedIn members; bucket 2-10), founded 2025 |
| English-speaking | PASS: "English, our company language" |
| Local entity + engineering contracts | PASS with CAUTION: HRB 299037 Munich, consulting-first purpose, mixed freelancer workforce |
| Location / work model | Fully remote (EU & UK); registered office Seidlstraße 5 near Munich Hbf |
| Glassdoor | No profile |
| Kununu | No profile |
| Salary | UNVERIFIED: no data |
| AI/ML content | Strong: enterprise LLM agents, multi-agent framework, EvalOps |
| Computer-language/Tech-stack | Python-centric, TypeScript secondary, Kubernetes/Terraform on any hyperscaler |
| No on-call | **FAIL**: on-call and incident response named in postings |
| WLB / Stability | UNKNOWN WLB; young unaudited services firm |
| Works council / collective agreement | None |
| Regulated industry | CAUTION: regulated clients |
| Review themes | No reviews on any platform |
| Founder background | Ex-McKinsey partners; strategy-consulting operating model |

---

## Section 13: Verdict

**Exclude.** EggAI is a consulting firm by its own description, and the engineering roles carry on-call.

**Strengths:** genuine, current applied LLM / multi-agent work; an actively maintained open-source framework; fully remote with English as company language; an unusually transparent and short interview process; experienced leadership with access to large German enterprises; growth signals (UK branch, Tübingen Labs, STACKIT partnership).

**Hard blockers:**
1. **Consulting / forward-deployed arrangement.** Registered purpose starts with "Beratung von Unternehmen"; the services page names "Forward-deployed engineering" as a product; the engineering posting places hires "in a team of 2 to 6 engineers on a client project" working with the client's engineers and requires "client-facing ability"; the company describes itself as an "AI consulting and development startup". This fails "No consultant/forward-deployed/solution-engineer type of arrangement" directly.
2. **On-call.** Both engineering postings ask for production ownership including "on-call" / "on-call incident response", and the company sells managed operations of client AI systems.

**Secondary concerns:** no reviews anywhere (Glassdoor, Kununu, Blind, GPTW), so culture and WLB cannot be assessed; no financial filings or disclosed funding; ~2-year-old company with a partly freelance, multi-country workforce and processes still being built; no works council or collective agreement; no salary data; client-driven regulatory overhead.

**Recommendation:** Do not apply. No further research is warranted unless EggAI spins its platform or Labs into a product business with internal (non-client) engineering roles and drops the on-call requirement. The Tübingen Labs is explicitly "not a client-facing role", so a future senior Labs or platform-product position would be the only variant worth re-checking.

---

## Sources

- [EggAI website (egg-ai.com)](https://egg-ai.com/) (CDP)
- [EggAI Company / Leadership / Career](https://egg-ai.com/company) (CDP)
- [EggAI Imprint](https://egg-ai.com/legal/imprint) (CDP)
- [EggAI Services](https://egg-ai.com/services) (CDP)
- [EggAI Technology](https://egg-ai.com/technology) (CDP)
- [EggAI Approach](https://egg-ai.com/approach) (CDP)
- [EggAI AI for IT](https://egg-ai.com/ai-for-it) (CDP)
- [EggAI Blog: The agentic platform market has split into planes](https://egg-ai.com/blog) (CDP)
- [eggai.tech (unrelated Amity product, name collision)](https://www.eggai.tech) (CDP)
- [NorthData: EggAI Technologies GmbH, HRB 299037](https://www.northdata.de/EggAI+Technologies+GmbH,+M%C3%BCnchen/Amtsgericht+M%C3%BCnchen+HRB+299037) (CDP)
- [OpenRegister: HRB 299037](https://openregister.de/company/DE-HRB-D2601-299037) (search snippet; page behind Cloudflare)
- [UK Companies House search: EggAI Technologies GmbH](https://find-and-update.company-information.service.gov.uk/search/companies?q=EggAI) (curl)
- [LinkedIn: EggAI Technologies](https://www.linkedin.com/company/eggai-technologies/) (CDP)
- [LinkedIn: EggAI Technologies About](https://www.linkedin.com/company/eggai-technologies/about/) (CDP)
- [LinkedIn: EggAI Technologies People](https://www.linkedin.com/company/eggai-technologies/people/) (CDP)
- [LinkedIn: EggAI Technologies Jobs](https://www.linkedin.com/company/eggai-technologies/jobs/) (CDP)
- [LinkedIn job: Senior Software/AI Engineer (4482481654)](https://www.linkedin.com/jobs/view/4482481654/) (voyager API over CDP)
- [LinkedIn job: Platform Engineer, Senior (4482495114)](https://www.linkedin.com/jobs/view/4482495114/) (voyager API over CDP)
- [LinkedIn job: AI Builder, Working Student (4482499621)](https://www.linkedin.com/jobs/view/4482499621/) (voyager API over CDP)
- [LinkedIn job: Senior Accountant, Finance Operations (4482480915)](https://www.linkedin.com/jobs/view/4482480915/) (voyager API over CDP)
- [LinkedIn: unrelated "EggAI" page (12 followers)](https://www.linkedin.com/company/eggai/) (CDP)
- [LinkedIn: Jürgen Laartz](https://www.linkedin.com/in/j%C3%BCrgen-laartz-15a5312/)
- [LinkedIn: Jan Heurich](https://www.linkedin.com/in/jan-heurich-98975b49/)
- [Agentic Engineering Jobs: EggAI AI Software Engineer](https://agentic-engineering-jobs.com/jobs/eggai-ai-software-engineer-Y-1Tnu) (HTTP 500, search snippet only)
- [Catalitium: EggAI Data Discovery Lead](https://catalitium.com/jobs/155954-eggai-technologies-hiring-data-discovery-lead) (404, search snippet only)
- [Startup Seeker: egg-ai.com](https://startup-seeker.com/company/egg-ai~com)
- [GitHub: eggai-tech organisation](https://github.com/eggai-tech) (GitHub API)
- [GitHub: EggAI Multi-Agent Meta Framework](https://github.com/eggai-tech/EggAI)
- [EggAI SDK pyproject.toml](https://raw.githubusercontent.com/eggai-tech/EggAI/main/sdk/pyproject.toml)
- [EggAI Docs](https://docs.egg-ai.com/)
- [PyPI Stats: eggai](https://pypistats.org/packages/eggai)
- [Glassdoor search: EggAI](https://www.glassdoor.de/Search/results.htm?keyword=EggAI) (CDP, no results)
- [Kununu search: EggAI](https://www.kununu.com/de/search?q=EggAI) (CDP, no results; direct slugs HTTP 405 via curl)
- [Teamblind: EggAI](https://www.teamblind.com/company/EggAI/) (CDP, page not found)
- [levels.fyi: EggAI](https://www.levels.fyi/companies/eggai/salaries) (HTTP 403, no data)
- [Great Place to Work Germany search](https://www.greatplacetowork.de/?s=EggAI) (CDP, no results)
- [Nominatim: Seidlstraße 5, München](https://nominatim.openstreetmap.org/search?q=Seidlstra%C3%9Fe+5,+80335+M%C3%BCnchen&format=json&addressdetails=1)
- [Overpass API (transit stops)](https://overpass-api.de/api/interpreter)
- [Kai Waehner: Enterprise Agentic AI Landscape Q2 2026](https://www.kai-waehner.de/blog/2026/04/06/enterprise-agentic-ai-landscape-2026-trust-flexibility-and-vendor-lock-in/)
