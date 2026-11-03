# Sureel AI - Full Research Report

_Researched: 2026-11-03_

> **Context.** Sureel AI is a roughly ten-person AI attribution startup that Warner Music Group (WMG) acquired in June 2026. It runs as "an independent, federated company within Warner Music Group". Group-level WMG data (financials, layoffs, group reviews) comes from the companion report `research/WarnerMusicGroup.md` (same date). This report covers Sureel itself and its Munich engineering openings. Every Sureel-specific fact was re-checked today.

> **Critical Disqualifiers / Cautions**
> 1. **No German legal entity.** Sureel's legal notice names only "Sureel Inc. California, USA". NorthData returns no Sureel company in Germany (re-checked 2026-11-03), and no German company is linked to the CEO, the Head of Engineering or the Head of AI. It is **UNVERIFIED** whether a Munich hire would get a direct German contract (through WMG's Hamburg GmbH or a new GmbH) or would be hired through an Employer-of-Record.
> 2. **TypeScript/Node.js-first role.** The Munich Senior SWE posting asks for someone "comfortable working extensively with TypeScript/Node.js. Python experience is a bonus."
> 3. **The Munich SWE role is listed as on-site**, and Sureel publishes no Munich office address. The Munich Product Lead role and the Ontario SWE role are both listed as remote.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 2022 (4 years), per LinkedIn and directories |
| Employees | 10 named team members on sureel.ai/about-us plus 6 advisors. LinkedIn shows "11-50" with 8 associated members (4 in the US, 2-4 in Bavaria/Munich) |
| Revenue | Not disclosed. Known commercial relationships: STIM (Sweden, "preferred attribution provider", Sep 2025), BeatStars (opt-out, Apr 2025), OpenPlay (agreement, 2024), Triple 8 Management, A2IM partnership |
| Profitability | Not disclosed. Probably loss-making: an early-stage startup with paid GPU workloads and minimal disclosed funding, now funded by its parent - **BORDERLINE** (the parent is profitable, the unit almost certainly is not) |
| Ownership | Wholly owned by Warner Music Group Corp. (NASDAQ: WMG) since June 2026, terms undisclosed. WMG is itself controlled by Access Industries |
| Software-centric | AI attribution, detection and licensing software, sold as an enterprise API and platform - **PASS** |

### Key People

- **Dr. Tamay Aykut**: founder and CEO; former visiting assistant professor at Stanford; co-inventor on all Sureel patents.
- **Benji Rogers** and **Aileen Crowley**: Co-Presidents. Both come from the music industry: Rogers founded PledgeMusic, and Crowley has a label and streaming background.
- **Dr. Christopher (Benjamin) Kuhn**: Head of AI, co-inventor on the patents; LinkedIn tagline "Explainable and Ethical AI".
- **Christoph Burgmair**: Head of Engineering (Director).
- Engineering team listed on the website: one AI Engineer, a Senior Full-Stack Engineer (Infrastructure, Cloud & Security) and a Senior Full Stack Engineer (DevOps/MLOps). One of these engineers shares the CEO's surname.
- **Greg Kovacic** (CFO), **Michael Pelczynski** (Head of Licensing).
- Advisors include Bernd Girod (Stanford, image/video coding) and Tom Gruber (Siri co-founder).
- LinkedIn shows three members who studied at the Technical University of Munich, which explains the Munich engineering hub.

### Funding History

| Date | Round | Amount | Investors / Notes |
|---|---|---|---|
| ~2023 | Accelerator / other | ~$100K (Signal Base) | Creative Destruction Lab program (CB Insights) |
| n/d | Startup programs | In-kind credits | AWS Activate, Google for Startups, NVIDIA Inception (sureel.ai footer) |
| 10 Jun 2026 | Acquisition | Undisclosed | Warner Music Group; Sureel stays a standalone platform serving the wider industry |

No disclosed venture rounds beyond these. Bouncewatch lists no funding at all.

### Business Model

Sureel sells "AI rights, licensing, attribution, protection, and intelligence" infrastructure:
- **Attribution:** quantifies how much each training work influenced an AI output, broken down by stem, time segment and confidence. It is patented in three variants: model-based (US 12,013,891 B2, granted June 2024, plus continuation US 12,455,918 B2), output-based (embedding-distance, US 12,314,308 B2, May 2025) and input-based (application 2024/0419949).
- **Detection:** classifies audio as AI-generated, human-made or mixed.
- **Protection:** enforced opt-outs, plus infringement screening during generation.
- **Catalog value analysis** and real-time "attribution share" reporting for rightsholders.

The registry holds "over 12 million fingerprints" (Google Cloud partner page). Sureel is also an official Google Cloud partner. The Hollywood Reporter (quoted in secondary coverage) noted it is "unclear how effective Sureel's technology is in independent testing", and no third-party benchmark of the attribution accuracy was found.

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **Sureel Inc.** | California, USA (per sureel.ai legal notice); no German registration | "California, USA" (no street address published; LinkedIn says Palo Alto) | AI attribution / licensing platform |
| **Sureel (any German entity)** | **None found.** NorthData search for "Sureel" returns only UK and Belgian name matches. NorthData person searches for the CEO, Head of Engineering and Head of AI show no German directorships. The handelsregister.ai search endpoint returned 404 | n/a | n/a |
| **WARNER MUSIC Group Germany Holding GmbH** (possible employing entity) | Amtsgericht Hamburg HRB 87402 | Alter Wandrahm 14, 20457 Hamburg | Media production, music publishing, copyright administration, artist contracts (verbatim in WMG report) |

**Verification.** Sureel's only published legal entity is the US corporation. Two or more team members live in Munich (LinkedIn location facets: "Munich (District), Bavaria, Germany: 2"), but nothing shows which entity employs them. The Lever postings don't name a German employer. The WMG German GmbH could in principle employ Sureel staff, but its registered purpose doesn't cover software development, and it sits in a Hamburg label organisation with which Sureel has no visible connection. The plausible routes are an EOR/contractor arrangement, employment via the WMG GmbH, or a not-yet-registered Sureel GmbH. None can be confirmed from public data.

**Verdict:** **UNVERIFIED / CAUTION.** This is the first question to ask a recruiter: "Which legal entity issues the contract, and is it a permanent German employment contract?"

---

## Section 3: Office Location

- **Office address:** **UNVERIFIED.** The Lever postings say only "Munich". No Munich address appears on sureel.ai (legal notice, about page, privacy policy), on LinkedIn (HQ Palo Alto) or in press coverage. Without an address, the Nominatim/Overpass lookup could not be run. Since the team is rooted at TUM, a co-working or incubator space is plausible, but no evidence was found linking Sureel to UnternehmerTUM or TUM Venture Labs.
- **Nearest public transport:** UNKNOWN (no address).
- **Work model:**
  - Senior Software Engineer, Backend & AI Platform (Munich): **"Full-Time / On-Site"** on the Lever page and `workplaceType: onsite` in the Lever API (re-checked 2026-11-03).
  - Product Lead, Platform & Enterprise (Munich): **Remote**.
  - Senior Software Engineer, Backend & AI Platform (Ontario): **Remote**, with an otherwise identical description.
  - The difference may be deliberate (an engineering hub around the Munich heads of engineering and AI) or a data-entry inconsistency. Verify the expected office days.

---

## Section 4: Reviews

**GPTW:** No Great Place to Work Germany certification or list entry for Sureel, which is too small to be expected there. WMG also has none (see the WMG report).

#### Glassdoor

Sureel has **no Glassdoor profile**: the employer autocomplete and the search for "Sureel" returned nothing (Chromium/CDP, 2026-11-03). Parent-group figures for reference (WMG, E13163):

| Metric | Global | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | Sureel: none / WMG 3.4 (750, English) | Sureel: none / WMG 4.0 (4) | none | Sureel: none / WMG 4.1 (9) |
| **WLB** | WMG 3.7 | WMG 3.1 | n/a | WMG 4.9 |
| **Culture & Values** | WMG 3.2 | WMG 4.9 | n/a | WMG 3.7 |
| **Comp & Benefits** | WMG 3.3 | WMG 3.1 | n/a | WMG 2.8 |
| **Career Opportunities** | WMG 2.9 | WMG 3.0 | n/a | WMG 3.2 |
| **Diversity & Inclusion** | WMG 3.7 | WMG 3.0 | n/a | WMG 4.4 |
| **% Recommend** | WMG 53% | WMG 99% | n/a | WMG 100% |
| **CEO Approval** | WMG 27% | n/a | n/a | WMG 100% |
| **Business Outlook** | WMG 20% positive | WMG 99% positive | n/a | WMG 26% positive |

All WMG Germany and SWE figures rest on fewer than 20 reviews and are directional only. They describe the label group and WMG Global Tech, not Sureel's ten-person team.

#### Kununu

- `kununu.com/de/sureel`: curl returned HTTP 405. The Kununu search for "Sureel" via Chromium/CDP returned no employer.
- **Overall score:** none (no profile)
- **Recommendation rate:** none
- **Total reviews:** 0
- **Kununu Top Company:** NO
- Parent reference: Warner Music Central Europe 3.1 / 5, 55% recommend, 80 employee reviews (German label business, not Sureel).

#### Blind / Teamblind

No Sureel company page (`teamblind.com/company/Sureel` returns "Page not found"). WMG: 3.7 / 5 (15 reviews), WLB 3.9, Compensation 3.0.

#### Review Themes (2024-2026)

No employee reviews of Sureel exist on any platform, so the themes below are drawn from public material about the team and from the parent group.

**Positives:**
- Small, senior, research-heavy team with patented core technology and named heads of AI and engineering in Munich; the posting stresses "high standards and low ego", "kind, intellectually curious, generous with knowledge".
- Very high ownership: the role spans architecture, MLOps, DevOps and enterprise features.
- Well-funded owner that has made AI licensing a strategic pillar (Suno/Udio settlements and licences, Nov 2025).

**Negatives:**
- **Parent-level layoff churn**: WMG is executing a $300M cost programme through end-2026 after cuts in 2023 and 2024, and reviewers describe "continuous layoffs" (Glassdoor, Sep 2026). This overlaps with the **layoffs** red flag at group level.
- **Low trust in parent senior management**: WMG CEO approval 27%, business outlook 20%.
- **Below-market pay** at group level (Glassdoor, Blind, Kununu).
- Unproven technology in independent testing (Hollywood Reporter).
- Startup ambiguity is stated explicitly: "comfortable in a fast-moving startup environment where you will have significant ownership and ambiguity".

#### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | No evidence for Sureel (no reviews). WMG German label management is criticised on Kununu, but Sureel sits outside that organisation |
| 24/7 Work Expectation | Not stated. End-to-end production ownership in a ~5-engineer team is a structural risk |
| Internal Surveillance | No evidence |
| Fear-driven Management | No evidence for Sureel |
| Communication Breakdown | No evidence for Sureel; recurring complaint at WMG group level |
| Unpaid Overtime | No evidence; early-stage startup norms are unknown |
| Silent Firings | No evidence. Group layoffs are announced programmes, not individual push-outs |
| Work-Life Balance issues | No data for Sureel; WMG group WLB is decent (3.7) |

**Risk level: UNVERIFIED, leaning LOW-to-MODERATE.** There is no evidence of systemic toxicity, but there is also no data. The realistic risks are (c) small-team load and founder-driven intensity, and exposure to (b) the parent's restructuring cycles. Probe in interview: team turnover since the acquisition, decision-making between the founder and WMG, and the rhythm of releases and incidents.

---

## Section 5: Compensation

#### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| Lever posting (Ontario, remote) | Sr SWE, Backend & AI Platform, Sureel AI | CAD 110-145K (~€68-90K) | not stated | "performance based annual bonus" (amount not stated) | ~€70-95K est. | 1 |
| Lever posting (Munich, on-site) | Sr SWE, Backend & AI Platform, Sureel AI | **not disclosed** | n/a | n/a | n/a | 1 |
| levels.fyi | Sureel | no company page (404) | | | | 0 |
| levels.fyi | WMG Software Engineer, Germany | locked (<4 submissions) | | | | <4 |
| Glassdoor / Kununu | Sureel | no profile | | | | 0 |

No Munich percentile data exists for Sureel. As reference, the Munich senior software engineer market at large, profitable corporations sits around €85-105K base (median to 75th percentile), with the 90th percentile above €115K.

#### Equity / Stock

Pre-acquisition Sureel equity was presumably converted or cashed out at the June 2026 deal. New hires could at most receive WMG stock (NASDAQ: WMG) under the Omnibus Incentive Plan or an earn-out/retention arrangement. Nothing is disclosed for Munich, and the Ontario posting mentions only base plus bonus. Treat it as **no equity** unless offered.

#### Verdict

Sureel's only published band (Canada, ~€68-90K base plus bonus) sits below the Munich large-corporation senior bracket, and WMG reviewers consistently describe pay as below market. **UNVERIFIED, leaning BELOW.**

---

## Section 6: AI/ML & Tech Stack

#### AI Strategy

This is genuine applied AI, and AI is the product:
- **Attribution models**: model-based (tracing training-data influence inside a generative model), output-based (embedding distance between output and registry items) and input-based (prompt parsing for creator identifiers), all patented.
- **Detection**: AI-generated vs human vs mixed, per segment with confidence.
- **Registry and retrieval**: 12M+ fingerprints, vector search, stem/time-segment breakdowns.
- **Research output**: blog series on synthetic data (CEO, 2025) and a public repo `sureel-labs/sureel-composition-analysis` ("role of composition and recording style in AI-generated music", last push March 2025).
- **Roadmap**: extension from music to video and images (WMG press release), plus a NIL (name, image, likeness) attribution suite for voice clones and avatars.
- **Engineering focus of the role**: moving "experimental models and algorithms into reliable production services", covering model deployment, inference, versioning, evaluation, monitoring and GPU infrastructure, i.e. MLOps for research models.

#### Tech Stack

Derived from the two Sureel Senior SWE postings (Munich and Ontario, Lever API and pages, read in full), the public API documentation (api.sureel.ai, Redocly), HTTP response headers, the sureel-labs GitHub organisation, and the Google Cloud partner page. No StackShare/Himalayas profile, engineering blog or conference talks were found.

| Category | Technologies |
|---|---|
| **Primary language(s)** | TypeScript/Node.js (required, "working extensively"); Python (bonus, presumably the AI research layer) |
| **AI/ML** | Model serving, inference, GPU workloads, embeddings, evaluation, MLOps; audio/image generative-model attribution; agentic development frameworks and coding agents |
| **Cloud** | GCP (named first; official Google Cloud partner; API behind Google's front end, `via: 1.1 google`); AWS (DynamoDB); website on Vercel (Next.js) |
| **Infrastructure** | Kubernetes, Docker, Terraform, CI/CD, infrastructure-as-code |
| **Data** | AWS DynamoDB / NoSQL, Meilisearch, vector search, distributed processing |
| **Other** | Auth0 (OAuth client credentials, EU tenant), Redocly/OpenAPI, React frontend, enterprise SaaS (RBAC, multi-tenancy, audit, bulk operations) |

**Summary:** TypeScript/Node.js-centric backend and platform engineering with a Python ML research layer, on GCP (Kubernetes, Terraform) with DynamoDB, Meilisearch and vector search, plus GPU inference. This is applied production AI: productionising patented attribution and detection models as an enterprise API, in a very small team.

---

## Section 7: Language

- All Sureel postings, including both Munich roles, are in English with no German requirement.
- The team is international (US, Germany, Singapore-educated members; US-based co-presidents and CFO), so English is the working language by necessity.

**Verdict:** **PASS**.

---

## Section 8: Stability

#### Financial Position

- **Sureel standalone:** no financials published. The only disclosed funding is ~$100K plus accelerator and cloud credits (CDL, AWS Activate, Google for Startups, NVIDIA Inception), which suggests a lean, possibly founder- or customer-funded operation before the acquisition.
- **Parent (WMG):** FY2025 revenue $6.707B and net income $370M. For the nine months to 30 Jun 2026, revenue was $5.436B (+12%) and net income $556M. Cash was $618M against net debt of $4.09B; ratings are Moody's Ba1 and Fitch BBB-. The trend is improving (details in the WMG report).

#### Financial Runway

Sureel is loss-making in all likelihood, but after the acquisition its runway depends on WMG's continued strategic backing rather than its own cash. A bottom-up model still shows the scale involved:

| Cost line | Annual estimate |
|---|---|
| Staff (~11 people × ~€140K fully loaded, US/Canada/Germany mix) | ~€1.5M |
| Cloud and GPU (training/inference for attribution, 12M-fingerprint registry) | ~€0.4-0.8M |
| Other (legal/patents, travel, industry events, SaaS) | ~€0.3M |
| **Total gross burn** | **~€2.2-2.6M/year** |

| Revenue source | Est. annual inflow |
|---|---|
| STIM, BeatStars, OpenPlay, Triple 8 and other licences/subscriptions (amounts undisclosed) | ~€0.2-0.8M/year (assumption) |
| WMG internal use (catalogue attribution, AI-licence reporting) | transfer pricing unknown |
| **Total revenue offset** | **~€0.2-0.8M/year** |

| Scenario | Net burn | Cash at hand | Runway | Next round needed by |
|---|---|---|---|---|
| Optimistic | ~€1.4M/year; WMG scales the team (Munich and Ontario hiring) | Parent-funded (WMG cash $618M, 30 Jun 2026) | Indefinite while strategic | n/a |
| Base case | ~€2M/year | Parent-funded | Indefinite; reviewed in WMG's annual budget cycle | n/a |
| Stress | ~€2.4M/year, with WMG's AI-licensing strategy changing or another cost programme | Parent-funded | Unit folded into WMG Global Tech, or wound down, within 12-24 months | n/a |

Cash figure: WMG consolidated cash and equivalents of $618M at 30 June 2026 (10-Q). Sureel's net burn would be about 0.1% of WMG's annual Adjusted OIBDA, so cash isn't the risk. The risk is strategic: an acquired ten-person unit inside a parent that has cut ~20% of headcount in two years.

#### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| none found | Sureel | n/a | No reported Sureel layoffs; the company is hiring (2 engineering roles plus Product Lead, Nov 2026) |
| Mar 2023 | WMG global cost reduction | ~270 / ~4% | Parent |
| Feb 2024 | WMG restructuring | ~600 / ~10% | Parent |
| Jul 2025 - end 2026 | WMG "$300M savings" plan | Not disclosed; $170M from headcount | Parent; $124M severance booked by 30 Jun 2026 |

#### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | **NO** | No German entity; a team of ~2-4 in Munich is far below any realistic council. WMG Germany: no council found (WMG report) |
| Collective agreement | **NONE** | No tariff language in any Sureel posting; no German employer entity |
| European works council | **N/A** | Sureel is a US company |
| Conflict signals | None found | n/a |

**Verdict:** **CAUTION.** The parent is financially solid, but Sureel is an acquired micro-team with no German entity and no co-determination, owned by a group in the middle of its third restructuring in three years.

---

## Section 9: Regulated Industry

The domain is copyright and collecting-society licensing (STIM, GEMA, PROs) and the EU AI Act's training-data transparency obligations for general-purpose AI. Sureel sells compliance tooling for these rules, but none of them imposes an engineering process regime on Sureel itself (no BaFin/DORA, IVDR, ISO 26262 or ITAR). The practical impact is domain complexity: rights metadata, audit trails, provenance records.

**Verdict:** **PASS**.

---

## Section 10: On-Call

- Neither Sureel posting mentions on-call.
- The role does own "DevOps and cloud infrastructure, including CI/CD... observability, and deployment reliability" and systems "from architecture and implementation through deployment, observability, debugging" for an enterprise API used by external partners (STIM, BeatStars, AI companies), in an engineering team of about five.
- In practice this means production responsibility shared among very few people, either informally or as a rotation.

**Verdict:** **CAUTION (team-dependent)**; likely informal on-call. Ask directly.

---

## Section 11: Interview Process

Glassdoor has no Sureel interview data. WMG data as a proxy for the group's hiring machinery (the Lever ATS is shared):

| Metric | Value |
|---|---|
| Difficulty | WMG 2.74 / 5 (all roles); Sureel: UNKNOWN |
| Positive experience | WMG 56.8% (all roles), SWE 47%; Sureel: UNKNOWN |
| Average duration | WMG ~33 days; Sureel: UNKNOWN |
| Rounds | WMG SWE 4-5; Sureel: UNKNOWN |

Sureel will most likely run its own founder- and Head-of-Engineering-led process rather than WMG Global Tech's LeetCode-moderate loop. Based on the posting, expect deep discussion of production systems, MLOps and platform design, reasoning "beneath frameworks", and AI-assisted development workflows. The posting also says AI tools may be used to screen applications and to flag "inconsistencies or verification signals".

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | Yes: AI attribution / licensing API platform |
| Not consulting | Yes: product engineering, occasionally customer- or partner-facing |
| Profitable | Sureel: almost certainly not; parent WMG: yes, improving |
| Employee count | ~10-12 (Sureel); ~5,500 (WMG) |
| English-speaking | Yes |
| Local entity + engineering contracts | **No German entity; contract route UNVERIFIED** |
| Location / work model | Munich, **on-site** per the SWE posting; no office address published |
| Glassdoor | No Sureel profile; WMG 3.4 global, CEO approval 27% |
| Kununu | No Sureel profile; WMG Central Europe 3.1 |
| Salary | Munich undisclosed; Canadian band ~€68-90K plus bonus; leaning BELOW |
| AI/ML content | High: patented attribution models, MLOps, GPU inference, vector search |
| Computer-language/Tech-stack | TypeScript/Node.js-centric, Python bonus; GCP, Kubernetes, Terraform, DynamoDB, Meilisearch |
| No on-call | Not mentioned; production ownership in a ~5-engineer team implies likely on-call |
| WLB / Stability | No WLB data; parent financially strong but restructuring |
| Works council / collective agreement | None |
| Regulated industry | Low engineering burden |
| Review themes | No Sureel reviews; parent: layoffs, weak senior-management trust, below-market pay |
| Acquisition / integration risk | Acquired June 2026; "independent, federated" for now; technology effectiveness questioned in press |

---

## Section 13: Verdict

**Recommendation: Monitor.** Sureel offers some of the most interesting applied-AI work in Munich at the moment, but three basics are unresolved: the employing entity, the stack fit and the on-site requirement. Don't treat it as an active target until a first conversation clarifies them.

**Strengths.** The AI content is high and genuine: patented attribution models, detection, a 12M-fingerprint registry, and MLOps work that turns research models into an enterprise API. The team is small and senior, with its heads of engineering and AI rooted in Munich and TUM, and the role gives very high ownership. English is the working language, regulatory burden is low, and the owner is profitable and strategically committed to AI licensing.

**Hard blockers:**
1. **No verified direct German employment contract.** Sureel Inc. (California) is the only legal entity. No Sureel company exists in the German register, and WMG's German GmbH is a Hamburg label and publishing company. If the Munich hire is through an EOR or as a contractor, the "full-time, permanent, direct employment contract" criterion fails.
2. **TypeScript/Node.js-first stack.** The role requires working "extensively with TypeScript/Node.js" and treats Python only as a bonus. Python would apply only to the AI research layer.

**Secondary concerns:**
- **Pay:** Munich undisclosed. The Canadian band (~€68-90K base) and the parent's reputation point below the Munich large-corporation bracket. No equity is visible.
- **Stability:** this ten-person acquired unit's continuity depends on WMG's AI-licensing strategy, and WMG is still executing a $300M cost programme with 20% business-outlook confidence on Glassdoor.
- **On-site** flag with no published office address.
- **On-call:** full production and DevOps ownership in a ~5-engineer team.
- **No reviews anywhere**, no works council, no collective agreement, and unproven technology in independent tests.

**What would need to change for a positive application recommendation:** confirmation of a permanent German employment contract (WMG GmbH or a new Sureel GmbH); a disclosed Munich salary band at or above the senior bracket; clarity on office days and address; explicit on-call expectations; and comfort with a TypeScript-first backend. If those come back positive, the trade-off is a strong applied-AI/MLOps role in a tiny team against stack fit and acquisition risk.

---

## Sources

- [Sureel AI website](https://www.sureel.ai) (Chromium/CDP)
- [Sureel AI: About Us / team](https://www.sureel.ai/about-us) (Chromium/CDP)
- [Sureel AI: Legal Notice](https://www.sureel.ai/legal-notice) (Chromium/CDP)
- [Sureel AI: Google Cloud partnership](https://www.sureel.ai/developers/google-partnership) (Chromium/CDP)
- [Sureel API documentation](https://api.sureel.ai/documentation) (Chromium/CDP; response headers via curl)
- [Sureel blog: Synthetic Data Part I](https://www.sureel.ai/blog/synthetic-data-part-1)
- [Sureel blog: Creation Without Creators](https://www.sureel.ai/blog/creation-without-creators)
- [WMG Lever job board API](https://api.lever.co/v0/postings/wmg?mode=json) (curl)
- [Sureel AI: Senior Software Engineer, Backend & AI Platform (Munich)](https://jobs.lever.co/wmg/b7f94528-399c-4502-a441-53b2f62957a6) (Chromium/CDP)
- [Sureel AI: Senior Software Engineer, Backend & AI Platform (Ontario)](https://jobs.lever.co/wmg/5d6fdf53-3759-4a2b-a974-4e82c2459d38) (Chromium/CDP)
- [Sureel AI: Product Lead, Platform & Enterprise (Munich)](https://jobs.lever.co/wmg/6d31b5ab-c765-4a9b-a96a-cc4923a88e20) (Chromium/CDP)
- [LinkedIn: Sureel AI about](https://www.linkedin.com/company/sureelx/about/) (Chromium/CDP, logged in)
- [LinkedIn: Sureel AI people](https://www.linkedin.com/company/sureelx/people/) (Chromium/CDP, logged in)
- [GitHub: sureel-labs organisation](https://github.com/sureel-labs) (GitHub API via curl)
- [Google Patents: US12013891B2 model-based attribution](https://patents.google.com/patent/US12013891)
- [Google Patents: US12314308B2 output-based attribution](https://patents.google.com/patent/US12314308)
- [USPTO Official Gazette: US 12,455,918 B2](https://patentsgazette.uspto.gov/week43/OG/html/1539-4/US12455918-20251028.html)
- [Justia: patents assigned to Sureel Inc.](https://patents.justia.com/assignee/sureel-inc)
- [Justia: input-based attribution application](https://patents.justia.com/patent/20240419949)
- [Music Business Worldwide: WMG acquires Sureel AI](https://musicbusinessworldwide.com/warner-music-group-acquires-sureel-ai-the-attribution-startup-that-traces-how-ai-models-use-artists-work/)
- [Billboard: WMG acquires Sureel AI](https://www.billboard.com/pro/warner-music-group-acquires-sureel-ai/)
- [TechCrunch: Warner Music acquires AI attribution startup Sureel AI](https://techcrunch.com/2026/06/10/warner-music-acquires-ai-attribution-startup-sureel-ai)
- [Pulse 2.0: WMG acquires Sureel AI](https://pulse2.com/warner-music-acquires-sureel-ai-to-strengthen-intellectual-property-protection-and-monetization-in-the-ai-era/)
- [Let's Data Science: WMG acquires Sureel (Hollywood Reporter testing remark)](https://letsdatascience.com/news/warner-music-group-acquires-sureel-ai-attribution-platform-2f12eef2)
- [AI Weekly: Warner Music buys Sureel AI](https://aiweekly.co/alerts/warner-music-buys-sureel-ai-song-attribution-startup)
- [Digital Music News: STIM taps Sureel AI](https://www.digitalmusicnews.com/?p=329854)
- [Music Business Worldwide: BeatStars teams up with Sureel](https://www.musicbusinessworldwide.com/beatstars-teams-up-with-sureel-to-block-ai-companies-from-training-on-creator-content/)
- [EIN Presswire: OpenPlay signs agreement with Sureel AI](https://www.einpresswire.com/article/765933251/openplay-signs-agreement-with-sureel-ai)
- [Music Week: Triple 8 Management partners with Sureel](https://www.musicweek.com/digital/read/triple-8-management-partners-with-sureel-to-protect-artists-in-age-of-ai/091732)
- [Hypebot: Sureel AI offers music AI protection](https://www.hypebot.com/hypebot/2024/10/sureel-ai-offers-music-ai-protection.html)
- [A2IM: AMS x Sureel AI](https://a2im.org/ams-sureel-ai/)
- [CB Insights: Sureel.ai financials](https://www.cbinsights.com/company/sureelai/financials)
- [Signal Base: Sureel AI secures $100K](https://www.trysignalbase.com/news/funding/sureel-ai-secures-100k-funding)
- [Bouncewatch: Sureel AI](https://www.bouncewatch.com/explore/startup/sureel-ai)
- [Village.ai: Sureel](https://village.ai/company/sureelx)
- [NorthData search: Sureel](https://www.northdata.de/Sureel) and person searches for the CEO, Head of Engineering and Head of AI (Chromium/CDP)
- [handelsregister.ai search](https://handelsregister.ai/en/search?q=Sureel) (Chromium/CDP; 404)
- [Glassdoor employer search: Sureel](https://www.glassdoor.com/api-web/employer/find.htm?autocomplete=true&term=Sureel) (Chromium/CDP; no result)
- [Kununu search: Sureel](https://www.kununu.com/de/search?q=Sureel) (Chromium/CDP; curl 405; no result)
- [Blind: Sureel](https://www.teamblind.com/company/Sureel/reviews) (Chromium/CDP; not found)
- [levels.fyi: Sureel AI](https://www.levels.fyi/companies/sureel-ai/salaries) (Chromium/CDP; 404)
- [Companion report: Warner Music Group](WarnerMusicGroup.md) (group financials, layoffs, Glassdoor/Kununu/Blind, interview data, WMG German entity)
- [WMG Form 10-Q, quarter ended 30 June 2026](https://www.sec.gov/Archives/edgar/data/0001319161/000131916126000032/wmg-20260630.htm)
- [Glassdoor: WMG reviews (global)](https://www.glassdoor.com/Reviews/Warner-Music-Group-Reviews-E13163.htm)
- [Kununu: Warner Music Central Europe](https://www.kununu.com/de/warner-music-central-europe)
