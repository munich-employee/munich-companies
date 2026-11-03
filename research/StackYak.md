# StackYak - Full Research Report

_Researched: 2026-11-03_

> **Critical Disqualifiers**
> 1. **No path to a Munich-based role.** A LinkedIn post by the CEO about a week before this report says hiring requires the applicant to live in the SF/Bay Area or Israel and work 2-3 days a week in the office: "NOTE: All applicants must reside in SF/Bay Area or Israel and be in our 2-3 day office hybrid schedule." Every open posting is tagged "San Francisco / Israel, Remote".
> 2. **No German entity.** StackYak, Inc. is a US corporation with no registration in Germany. The postings say "Whether a role is an employment or a contract engagement depends on where you are", so anyone in Germany would be a contractor or hired through an EOR at best.
> 3. **Pre-seed startup with 2-10 people.** The only public funding is an undisclosed pre-seed round (StartupStream lists $200K). There is no revenue disclosure and no runway visibility.
> 4. **On-call for everyone.** Each posting says "Everyone shares responsibility for production and on-call."
>
> The rest of the report is completed for the record.

---

## 1. Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | ~2025 (the year is hidden on Crunchbase; the company came out of stealth in 2025-2026) |
| Employees | 2-10 (LinkedIn: 3 associated members, 2 in the US and 1 in Israel, all in business development or marketing titles; Crunchbase: 1-10) |
| Revenue | UNKNOWN. The Control Plane posting says "customers can buy GPU capacity, deploy models, connect privately, and pay for it", so some early revenue exists, but no amount is given |
| Profitability | Not profitable (pre-seed) - **FAIL** |
| Ownership | Private, VC-backed (pre-seed, led or joined by FoundersEdge) |
| Software-centric | Software platform: control plane, inference serving, GPU and network orchestration - **PASS** |

### Key People

- **Danny Davis**, Co-Founder & CEO. Profiles describe a serial founder from telecom and enterprise IT ("taking a technology company public in 2018 for $100M+"), former Chairman and Founder of W3box, and the holder of logistics, blockchain and membership patents. His background is business development, not engineering.
- **Adam Hopkins**, Co-Founder / CTO (according to Crunchbase).

### Funding History

| Date | Round | Amount | Valuation | Investors |
|---|---|---|---|---|
| ~2025 | Pre-Seed | Undisclosed (StartupStream: $200,000; CEO: "60% oversubscribed") | UNKNOWN | FoundersEdge |
| Planned | Seed | The CEO says they are "accelerating toward our seed round" | - | - |

### Business Model

StackYak sells a unified "orchestration layer for AI infrastructure" that combines hosted inference and model access, GPU compute (some owned, some rented), and private networking under one control plane and one bill. Storage and security are on the roadmap. The target customers are enterprises, developers and MSPs or resellers. The website lists NVIDIA, AMD, AWS, GCP, Azure, Oracle, Dell, HPE, IBM and Megaport as partners. Part of the business is reselling infrastructure (a "neocloud" or aggregator model), which carries hardware and capacity risk alongside the software.

---

## 2. Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **StackYak, Inc.** (only known entity) | US corporation (state not disclosed) | San Francisco, CA | AI infrastructure software |
| German entity | **None found** | - | - |

A NorthData search for "StackYak" (via CDP) returns only unrelated UK "Stackyard/Stackyat" companies. The website has no Impressum, only "© 2026 StackYak, Inc." and a privacy policy. The postings describe employment-or-contract "depending on where you are", which in Germany would mean a freelance contract or an EOR, not a direct local contract.

**Verdict:** FAIL

---

## 3. Office Location

- **Office address:** San Francisco, California (LinkedIn HQ; no street address published). One team member is in Israel. There is **no Munich or German office**.
- **Nearest public transport:** Not applicable. There is no Munich office to geocode, and no street address is published for the SF office.
- **Work model:** The job board shows every engineering role as "San Francisco / Israel, Remote", and the postings say "We are remote and distributed across time zones." The CEO's hiring post (LinkedIn, about a week before this report) is more restrictive: "All applicants must reside in SF/Bay Area or Israel and be in our 2-3 day office hybrid schedule." **Remote work from Germany is not offered.**

---

## 4. Reviews

**GPTW:** Not listed in GPTW Germany and holds no certification.

#### Glassdoor

Glassdoor has a StackYak company profile with **0 reviews, 0 salaries and 0 interview reports** (search via CDP).

| Metric | Global | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| All metrics | No data (0 reviews) | No data | No data | No data |

#### Kununu

`kununu.com/de/stackyak` returns HTTP 405 to curl. A Kununu search via CDP finds no employer profile. **UNKNOWN / not listed.** Kununu Top Company: NO.

#### Blind / Teamblind

`teamblind.com/company/StackYak` returns "Page not found". No data.

#### Review Themes (2025-2026)

No employee reviews exist on any platform. The signals below come only from the company's own postings and the CEO's LinkedIn posts.

**Positives:**
- Small, senior team "with direct access to the founders" and "very little bureaucracy".
- Hiring is "a few real conversations with the people you would actually work with, not a recruiter screen followed by a panel of strangers".
- A modern, explicit stack with written standards, design records and enforced CI gates. The team works "agent-first with AI coding tools".
- Large ownership scope: "founding role in its discipline".

**Negatives:**
- Universal on-call ("Everyone shares responsibility for production and on-call").
- Intensity framing: "We do not have months for someone to learn the fundamentals", "The pace is high", "take ground early and are not asked to give it back".
- Inconsistent messaging: the postings say "remote and distributed across time zones", while the CEO requires SF/Israel residence and 2-3 office days.
- LinkedIn shows no engineers among the associated members, so the actual engineering team size cannot be verified.

#### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | No evidence either way (no reviews). Culture post: "Challenge leadership. Challenge each other. Bring data, not opinions." |
| 24/7 Work Expectation | Possible. Distributed across US Pacific and Israel time zones with shared on-call. |
| Internal Surveillance | No evidence. |
| Fear-driven Management | No evidence. The tone is demanding ("We do not want your spam", "not yes people") but not fear-based. |
| Communication Breakdown | Minor signal: the remote eligibility in the postings contradicts the CEO's post. |
| Unpaid Overtime | UNKNOWN. A US startup pace is implied ("The pace is high"). |
| Silent Firings | UNKNOWN. With no German contract, no German employment protection would apply. |
| Work-Life Balance issues | Likely pressure from the early-stage pace and on-call, but unverified. |

**Risk level: UNKNOWN / MODERATE (by structure).** There is no evidence of systemic toxicity. The risk comes from the company's stage (pre-seed, founder-led, on-call for everyone, US/Israel time-zone spread), not from observed behaviour.

---

## 5. Compensation

#### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| Glassdoor | - | - | - | - | - | 0 |
| levels.fyi | - | (404, company not listed) | - | - | - | 0 |
| Job postings | Senior SWE / Inference / Compute / Network | Not disclosed: "Competitive compensation plus meaningful equity. Exact structure will depend on location, engagement model, and experience." | - | - | - | 4 postings |

There are no Munich percentile figures for this company.

#### Equity / Stock

"Meaningful equity" in a pre-seed US C-corp, most likely stock options. Liquidity risk is very high: the company is several rounds away from any exit. For a contractor outside the US, how options would be granted and taxed is unclear.

#### Verdict

**UNVERIFIED.** A pre-seed company with about $200K of disclosed funding is unlikely to match the cash pay of large, profitable Munich corporations.

---

## 6. AI/ML & Tech Stack

#### AI Strategy

The AI work is real infrastructure. StackYak serves frontier open-weight models (dense and MoE, "tens to hundreds of billions of parameters") on heterogeneous NVIDIA/AMD GPUs. The inference role owns quantization, tensor/pipeline/expert parallelism, batching and the choice of serving runtime (vLLM, SGLang, TensorRT-LLM). The control plane is adding agent access over MCP and scoped machine credentials. This is applied production AI infrastructure, not model research and not marketing.

#### Tech Stack

Derived from the four current postings on jobs.gem.com/stackyak (read in full via CDP). The company has no engineering blog, GitHub organisation or StackShare profile.

| Category | Technologies |
|---|---|
| **Primary language(s)** | Python 3.14 ("across services, workflows, and tooling"); Go "where it is the right tool"; TypeScript on the frontend |
| **AI/ML** | vLLM, SGLang, TensorRT-LLM; quantization; tensor/pipeline/expert parallelism; MoE serving; MCP for agent access |
| **Cloud** | GCP for their own infrastructure; customer capacity on AWS/Azure/GCP/Oracle plus owned and rented GPUs |
| **Infrastructure** | Terraform (including a planned Terraform provider), Kubernetes, NVIDIA/AMD drivers and firmware, data-center partners, private networking (Megaport) |
| **Data** | PostgreSQL (SQL-first, row-level security for tenancy, "not an ORM shop"), ClickHouse for analytics, Temporal for durable workflows |
| **Other** | GraphQL; React 19, Vite, TanStack Router/Query, Relay, Tailwind; AI coding tools ("agent-first") |

**Summary:** Python-centric backend and control-plane engineering on Postgres, Temporal and GraphQL, with Go where needed and a TypeScript/React frontend. The infrastructure runs on GCP and Terraform, and the inference layer serves open-weight LLMs with vLLM, SGLang and TensorRT-LLM. The work is applied production engineering (multi-tenant GPU cloud, billing, inference serving), not research.

---

## 7. Language

All postings and company material are in English. The team spans the US and Israel, so English is the working language, and no other language is required.

**Verdict:** PASS

---

## 8. Stability

#### Financial Position

Pre-seed. StartupStream lists total funding of $200,000; Crunchbase hides the amount. The CEO says the round was "60% oversubscribed" and that the company is "accelerating toward our seed round with significant early traction". There are no filed accounts (US private company, no German filing).

#### Financial Runway

No filed accounts, analyst estimates or press coverage of burn or runway were found (searched Crunchbase, StartupStream, and the web for funding, seed and runway). The model below uses the only public figure and should be read as indicative.

| Cost line | Annual estimate |
|---|---|
| Staff (~6 people; US/Israel senior engineers plus founders, mixed salaries and founder underpay, ~$150K fully loaded on average) | ~$0.9M |
| GPU capacity, colocation, cloud (GCP) and network commitments | ~$0.3-1.0M (highly variable; partly passed through to customers) |
| Tooling, legal, G&A | ~$0.1M |
| **Total gross burn** | **~$1.3-2.0M/year** |

| Revenue source | Est. annual inflow |
|---|---|
| Early customer GPU / inference / network revenue (gross margin only) | ~$0.1-0.3M/year (unverified) |
| **Total revenue offset** | **~$0.1-0.3M/year** |

| Scenario | Net burn | Cash at hand | Runway | Next round needed by |
|---|---|---|---|---|
| Optimistic (pre-seed was actually ~$2M, lean team) | ~$1.0M/year | ~$2M | ~2 years | ~2027-2028 |
| Base case (pre-seed ~$1M, hiring 4 senior engineers) | ~$1.5M/year | ~$1M | <1 year | ~H1 2027 |
| Stress (only the listed $200K) | ~$1.5M/year | ~$0.2M | ~2 months | Immediately |

Cash figure: $200K total funding from StartupStream.io, observed 2026-11-03. The real amount is probably higher, since four senior hires cannot be funded on $200K, but it is unverified. Hiring four senior engineers now suggests either a larger round than disclosed or a seed round that is imminent.

#### Layoffs

No layoffs reported (TrueUp and press: none found).

#### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | NO | No German entity; 2-10 employees |
| Collective agreement | NONE | US startup, no German employer |
| European works council | N/A | - |
| Conflict signals | None found | - |

**Verdict:** FAIL (pre-seed, runway unverifiable, no German employment protection)

---

## 9. Regulated Industry

General enterprise AI infrastructure, not a regulated sector. The practical burden is contractual (tenant isolation "precise enough that it can go in a contract", billing correctness, security), not regulatory.

**Verdict:** PASS

---

## 10. On-Call

All four postings say "Everyone shares responsibility for production and on-call." The Control Plane posting lists "Production. On-call, reliability" under ownership and asks for experience having "Carried production on-call for a system you built". The product is a GPU cloud and inference service sold to customers, so on-call is part of the job.

**Verdict:** FAIL

---

## 11. Interview Process

| Metric | Value |
|---|---|
| Difficulty | UNKNOWN (0 Glassdoor interview reports) |
| Positive experience | UNKNOWN |
| Average duration | UNKNOWN |
| Rounds | "A few real conversations" (per postings) |

The company describes the process as "a few real conversations with the people you would actually work with, not a recruiter screen followed by a panel of strangers". It hires on experience ("The bar is what you have already done, not what you could learn"). There is no sign of LeetCode-style screening. Agencies are explicitly rejected.

---

## 12. Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | PASS: AI infrastructure platform (control plane, inference, GPU and network orchestration) |
| Not consulting | PASS: product company |
| Profitable | FAIL: pre-seed |
| Employee count | 2-10 |
| English-speaking | PASS |
| Local entity + engineering contracts | FAIL: no German entity; contract or EOR at best |
| Location / work model | FAIL: the CEO requires SF/Bay Area or Israel residence and 2-3 office days |
| Glassdoor | No data (0 reviews) |
| Kununu | Not listed |
| Salary | UNVERIFIED: "competitive plus meaningful equity", no ranges |
| AI/ML content | Strong: LLM serving (vLLM/SGLang/TensorRT-LLM), MoE parallelism, MCP agent access |
| Computer-language/Tech-stack | Python 3.14-centric, Postgres/Temporal/GraphQL, GCP/Terraform, Go, TS/React |
| No on-call | FAIL: on-call for everyone |
| WLB / Stability | FAIL / UNKNOWN: pre-seed, runway unverifiable, high pace |
| Works council / collective agreement | NONE |
| Regulated industry | PASS |
| Review themes | No reviews; self-described as fast, senior and demanding |
| Remote eligibility consistency | CAUTION: the postings say "remote", the CEO post says SF/Israel hybrid |

---

## 13. Verdict

**Exclude.** The engineering content is strong: a Python-centric, SQL-first control plane on Postgres and Temporal, LLM inference serving on vLLM, SGLang and TensorRT-LLM, MCP-based agent access, a small senior team with enforced standards, and an interview process built on conversations with the people you would work with.

**Hard blockers:**
1. **Location:** The CEO's hiring post requires residence in the SF/Bay Area or Israel plus 2-3 office days a week. No role can be done from Munich.
2. **No German entity:** StackYak, Inc. has no registration in Germany. Any engagement from Germany would be a contract or EOR arrangement with no German employment protection, works council or social security employer.
3. **On-call:** "Everyone shares responsibility for production and on-call", and the product is a customer-facing GPU cloud.
4. **Stability:** Pre-seed with an undisclosed round (the only public figure is $200K), 2-10 people, and the seed round still ahead. Runway cannot be verified.

**Secondary concerns:** No reviews on any platform. Equity is illiquid. Founder-led US/Israel team spanning about 10 hours of time-zone difference. The founder's background is business development. The postings and the CEO contradict each other on remote eligibility.

**Recommendation:** No further research is warranted. Things would only change if StackYak raised a sizeable seed round, opened genuine EU-remote hiring with a German employment or EOR route, and offered a role without on-call; even then, the stability concerns would remain.

---

## 14. Sources

- [StackYak website](https://stackyak.ai)
- [StackYak careers page](https://stackyak.ai/careers)
- [StackYak job board (Gem), via CDP](https://jobs.gem.com/stackyak)
- [Senior Software Engineer, Control Plane (Gem), via CDP](https://jobs.gem.com/stackyak/am9icG9zdDrS1VXoPwsfjxegCRTHTd2b)
- [Senior AI Inference Engineer (Gem), via CDP](https://jobs.gem.com/stackyak/am9icG9zdDrauilGE5SD2AfJ04PacNuT)
- [Senior Compute Infrastructure Engineer (Gem), via CDP](https://jobs.gem.com/stackyak/am9icG9zdDol51Q0fZUUabpYWXXbSqok)
- [Senior Network Engineer (Gem), via CDP](https://jobs.gem.com/stackyak/am9icG9zdDqNdIFd6zGLLTjMYvNVkYXT)
- [StackYak LinkedIn company page, via CDP](https://www.linkedin.com/company/stackyak/)
- [StackYak LinkedIn people page, via CDP](https://www.linkedin.com/company/stackyak/people/)
- [Danny Davis LinkedIn profile and hiring post, via CDP](https://www.linkedin.com/in/dannydavis12/)
- [Crunchbase: StackYak, via CDP (WebFetch 403)](https://www.crunchbase.com/organization/stackyak-7411)
- [Crunchbase: Danny Davis (WebFetch 403)](https://www.crunchbase.com/person/danny-davis-mccallon)
- [StartupStream: StackYak, via CDP](https://www.startupstream.io/startup/stackyak)
- [FoundersEdge investor portfolio](https://foundersedge.com/investor.md)
- [NorthData search "StackYak", via CDP](https://www.northdata.de/StackYak)
- [Glassdoor search "StackYak", via CDP](https://www.glassdoor.com/Search/results.htm?keyword=StackYak)
- [Kununu (curl 405; search via CDP)](https://www.kununu.com/de/search?q=StackYak)
- [Teamblind: StackYak (404), via CDP](https://www.teamblind.com/company/StackYak)
- [levels.fyi: StackYak (404), via CDP](https://www.levels.fyi/companies/stackyak)
- [Fortune: Gordon Ritter, who owns the intelligence economy (linked by the CEO)](https://fortune.com)
