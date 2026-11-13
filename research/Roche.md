# Roche - Full Research Report

_Researched: 2026-06-19_

> **Critical Disqualifier**
> 1. **Location.** Roche's only substantial German software/AI engineering site relevant is **Penzberg** (Nonnenwald 2, 82377 Penzberg), ~50 km south of Munich. It is reached by RB66 (Werdenfelsbahn) from München Hbf. R&D roles at Penzberg are site-based hybrid, not fully remote.

The remainder of the report is completed for the record, because the company and the AI/ML work are an unusually strong match and a fully-remote Germany role (rare, but possible) would flip the verdict.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 1896 (130 years) - **PASS** |
| Employees | >100,000 globally - **PASS** |
| Revenue (FY2025) | ~CHF 70B / ~$76-80B - very large |
| Profitability | Strongly profitable; IFRS net income +50% in CHF in 2025, core net income +4% - **PASS** |
| Ownership | Public. Bearer shares on SIX Swiss Exchange (RO/ROG); ADR RHHBY. Founding families (Hoffmann/Oeri) hold a controlling voting pool. |
| Software-centric | **BORDERLINE.** Roche is a pharmaceutical and diagnostics manufacturer, not a software company. However, software/AI is now strategically integral to both divisions (digital pathology, navify cloud platform, AI drug discovery, lab automation). Software is a genuine and growing engineering discipline, but it is not the company's product in the way it is at a SaaS firm. |

**Key People:** CEO Thomas Schinecker (Group), historically a Diagnostics leader. Two divisions: Pharmaceuticals (incl. Genentech in the US) and Diagnostics (Penzberg/Mannheim/Rotkreuz are the European hubs).

**Business Model:** Sells medicines and diagnostic instruments/assays/digital solutions.

**Software-Centric Assessment:** This is the one structural caveat at the company level. Roche is software-*enabled*, not software-*centric*. For an AI/ML engineer the distinction is softer than for a generic backend role: the digital pathology and diagnostics-software organisations are real product-engineering groups shipping cloud SaaS in a regulated domain. Treat as **BORDERLINE PASS**, **not** a generic "software company".

---

## Section 2: Local Commercial Entity

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **Roche Diagnostics GmbH** | HRB 3962, Amtsgericht Mannheim | Sandhofer Str. 116, 68305 Mannheim (Penzberg works: Nonnenwald 2, 82377 Penzberg) | Development, manufacture and distribution of diagnostic and pharmaceutical products and related software/services |
| Roche Diagnostics Deutschland GmbH | HRB 708167, Mannheim | Mannheim | Sales/distribution arm |
| Roche Pharma AG | (Grenzach-Wyhlen) | Grenzach-Wyhlen, BW | German pharma operations |

**Verification:** Roche Diagnostics GmbH is a long-established operating entity (HRB 3962, Mannheim) that directly employs engineers and runs major R&D and manufacturing at the Penzberg works (the largest biotech site in Europe). This is **not** a sales shell - Penzberg is a genuine R&D centre with software and AI engineering. German employment is via a direct Arbeitsvertrag with the GmbH, not PEO/EOR.

**Verdict:** **PASS** (genuine German legal entity with direct engineering employment).

---

## Section 3: Location

- **Office address (relevant site):** Roche Diagnostics GmbH, Nonnenwald 2, 82377 Penzberg (Weilheim-Schongau district, Bavaria).
- **Nearest public transit:** Penzberg station (RB66/Werdenfelsbahn, Munich-Kochel line). The Nonnenwald campus is ~2-3 km from the station, requiring a local bus or shuttle (last-mile gap).
- **Work model:** Roche offers hybrid for office/R&D roles but tied to the physical site; it is not a remote-first company. Some individual roles are advertised as remote-eligible (via aggregators such as Jobgether), but diagnostics R&D and software roles at Penzberg are predominantly on-site/hybrid.

---

## Section 4: Reviews

**GPTW:** Roche appears on Great Place to Work "World's Best Workplaces" and holds multiple national Best Workplaces awards (Belgium, Brazil, Denmark, Finland, Greater China, South Korea, etc.). A Germany-specific 2025 certification for the Penzberg site could not be confirmed, but the global GPTW presence is a positive signal.

#### Glassdoor

| Metric | Global | Germany | Penzberg/Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | 4.1 (6,447) | 4.2 (131) | data sparse | 3.8 (44) |
| **WLB** | ~4.0 | 4.4 | - | - |
| **Comp & Benefits** | ~3.9 | 4.3 | - | 4.4 |
| **% Recommend / CEO** | high | high | - | - |

Notes: The Germany filter (4.2, 131 reviews) and the global score (4.1) are solid. The **Software Engineer** filter (3.8, 44 reviews), suggests the engineering experience is somewhat weaker than the company average (typical for a non-software-first company where engineers are a minority function). Penzberg/Munich-specific SWE data is too sparse to be reliable.

**Verdict:** Global/Germany **PASS** (>4.0); SWE-specific **BORDERLINE FAIL** (3.8).

#### Kununu

Fetched via curl (slug `roche-diagnostics-penzberg`):
- **Overall score:** 4.0 / 5.0
- **Recommendation rate (Weiterempfehlung):** 84%
- **Total reviews:** 1,555 (employee reviews: 1,388)
- **Kununu Top Company:** Likely (4.0 / 84% with high volume) - not separately confirmed.

**Verdict:** **PASS** (score 4.0 >= 3.6, recommend 84% >= 60%, very high review volume = reliable). This is one of the strongest Kununu profiles among Munich-area large employers.

#### Blind / Teamblind

Limited German coverage; Blind skews to US tech. A few panel-interview threads exist but no reliable aggregate German engineering score. Treat as **insufficient data**.

#### Review Themes

**Positives:**
- Strong work-life balance (Germany WLB 4.4), generous benefits, job security at a stable blue-chip.
- Meaningful mission (healthcare, oncology, diagnostics) - high purpose.
- Good compensation-and-benefits perception (4.3-4.4), strong pension/social benefits typical of a Swiss/German blue-chip.
- Large, well-resourced R&D environment; Penzberg viewed positively (84% recommend).

**Negatives:**
- Large-company bureaucracy, slow decision-making, matrixed reporting.
- Periodic restructuring/reorganisations in Diagnostics and Pharma (see Section 8).
- Career progression can be slow; engineering is a support function relative to science in parts of the org.

#### Toxic Leadership Assessment

| Pattern | Roche (Penzberg) |
|---|---|
| Toxic leadership as pattern | Not evident; no systemic signal |
| 24/7 work expectation | No; WLB rated highly (4.4 Germany) |
| Surveillance culture | No evidence |
| Fear-driven management | No systemic signal |
| Employee autonomy | Moderate; constrained by regulated processes and matrix |
| Communication breakdown | Localised complaints around reorgs, not systemic |
| Unpaid overtime | Not a recurring theme |

**Risk level: LOW.** Negatives are corporate-bureaucracy and reorg-related (typical large pharma), not systemic toxicity.

---

## Section 5: Compensation

#### levels.fyi Data

| Level | Title | Total Comp (€) | Data Points |
|---|---|---|---|
| Software Engineer (Germany, median) | Software Engineer | ~€67.3K | small sample |
| Software Engineer (Germany, top reported) | Software Engineer | ~€103K | - |

For context, the Munich market average SWE total comp is ~€82.5K (range ~€67K-€101K), so Roche's reported SWE median (~€67K) sits at the **bottom of the Munich band**. Senior/Staff levels will be higher than the generic "Software Engineer" median, but pharma/diagnostics comp generally trails pure-tech and the Munich big-tech employers (Apple, Google, NVIDIA, Datadog, etc.).

#### Equity / Stock

Roche is public (SIX: ROG). Compensation is predominantly cash (base + bonus) with German blue-chip benefits (strong pension, social benefits). Equity/share programs exist but are a small fraction of comp versus US-tech RSU packages.

#### Verdict

**BORDERLINE.** Roche pays solid, stable blue-chip cash comp with excellent benefits and security, but total comp for senior software engineers is below the Munich tech-sector bracket. The criteria file specifies no salary floor, so this is informational rather than disqualifying. Source: levels.fyi (small sample) - treat as directional.

---

## Section 6: AI/ML & Tech Stack Fit

#### AI Strategy

Roche has one of the most serious AI investments in pharma/diagnostics:
- **Drug discovery:** Genentech's "lab-in-the-loop" methodology; ~90% of eligible small-molecule programs integrate AI. Internal data platform **Apollo**.
- **Infrastructure:** "Build, buy, partner" with **NVIDIA** (AI factories / Omniverse) and **AWS** for compute.
- **Diagnostics:** **navify** digital solutions (cloud SaaS), **navify Digital Pathology**, AI-driven cancer diagnostics - an "open ecosystem" platform.

This is genuine applied AI/ML at production scale in a regulated domain, not marketing "AI".

#### Tech Stack (from job postings + AWS case study + StackShare)

| Category | Technologies |
|---|---|
| **Primary language(s)** | Python (data/AI/ML, backend), Java (enterprise/diagnostics platforms), some JS/TS frontend |
| **AI/ML** | PyTorch-class DL, classical ML, foundation models; digital pathology models |
| **Cloud** | AWS (Lambda, API Gateway, S3, IAM - navify), also GCP/Azure in places |
| **Infrastructure** | Kubernetes, Terraform, Ansible, GitLab CI/CD |
| **Data** | S3, standard RDBMS, large-scale experiment/clinical data platforms (Apollo) |
| **Observability** | Prometheus, Grafana |

#### Current Open Roles

| Role | Division/Team | Level | Key Tech | Fit? |
|---|---|---|---|---|
| Internship AI-ML Engineering / GenAI & LLM (Penzberg) | Diagnostics | Intern | Python, LLMs | **Exclude** (wrong level) |
| Senior Data Engineer (Weilheim/near Penzberg) | Diagnostics | Senior | data platform | **Partial** (location FAIL, data-eng not core AI/ML) |
| Senior Machine Learning Engineer (Santa Clara, US) | R&D | Senior | Python/ML | **Exclude** (US location) |
| Senior Cloud DevOps Software Engineer | Diagnostics/digital | Senior | Python, K8s, AWS, GitLab | **Partial** (good tech; location + DevOps/on-call caveats) |

No Senior/Staff Python AI/ML **product** role in Munich proper was found currently open; the Bavaria openings are Penzberg-tied.

---

## Section 7: Language

Roche's working language for R&D, diagnostics software, and international teams is **English**. Job postings for engineering/AI roles are in English; German is helpful but not a hard requirement for these roles. Penzberg is highly international.

**Verdict:** **PASS.**

---

## Section 8: Stability

#### Financial Position

Roche is one of the most financially stable companies in the world: ~CHF 70B revenue, strongly profitable (IFRS net income +50% in CHF in 2025), founding-family controlled, decades of dividend increases, AA-area credit profile. No runway concern (not VC-backed).

#### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| 2024-2025 | Pharma product-development restructuring | ~300-400 roles flagged; majority external **contractors** (<340 FTE) | Genentech/PD focused |
| 2025 | Genentech restructuring | ~489 roles (US) | Pharma side, US |
| ~2024 | Diagnostics restructuring | ~170 roles | Diagnostics reorg |
| 2019 | Mannheim reorg | >1,000 affected | Historical |
| 2013 | Penzberg/Branford | ~110 Penzberg / 60 Branford | Historical (Applied Science wind-down) |

Roche reorganises periodically like all large pharma, but it is not a distressed company; cuts are strategic/portfolio-driven, often hitting contractors first, and Roche is simultaneously investing in German sites.

**Verdict:** **STRONG PASS** on financial stability; **CAUTION** only for periodic reorg churn (normal for the sector).

---

## Section 9: Regulated Industry

Roche is **heavily regulated**: FDA, CE-IVDR, ISO 13485, ISO 14971, plus GxP for pharma. Practical engineering impact: formal design controls, documentation overhead, validation, slower deployment cadence, regulatory acceptance testing.

**Verdict:** **CAUTION** (high regulatory burden in absolute terms).

---

## Section 10: On-Call

Pure AI/ML and data-platform R&D roles at Roche typically do **not** carry on-call. However, the relevant currently-open openings lean toward **Cloud DevOps / SRE-adjacent** roles (navify is production SaaS), which **can** carry on-call rotation. Team-dependent.

**Verdict:** **CAUTION (team-dependent).** AI/ML research-engineering roles: likely no on-call. navify SaaS/DevOps roles: possible on-call.

---

## Section 11: Interview Process

| Metric | Value |
|---|---|
| Difficulty | ~average (Glassdoor) |
| Positive experience | ~66% |
| Rounds | 2-3 (phone screen + panel; sometimes HR + hiring manager + technical SMEs) |

Process is described as smooth and well-structured. Technical bar is "easy-to-medium LeetCode" plus system design and behavioral, with strong emphasis on team-specific research.

---

## Section 12: Summary Assessment

| Criterion | Result |
|---|---|
| Software-centric | **BORDERLINE** (software-enabled pharma/diagnostics; genuine product-eng in diagnostics digital/AI, but not a software company) |
| Not consulting | **PASS** (own products) |
| Profitable | **PASS** (130 yrs, ~CHF 70B rev, strongly profitable, family-controlled) |
| Employee count | **PASS** (>100,000) |
| English-speaking | **PASS** |
| Local entity + engineering contracts | **PASS** (Roche Diagnostics GmbH, HRB 3962 Mannheim; Penzberg R&D) |
| Location / work model | **FAIL** (Penzberg; no Munich-city engineering site) |
| Glassdoor | **PASS global/DE (4.1/4.2), BORDERLINE FAIL SWE (3.8)** |
| Kununu | **PASS** (4.0, 84% recommend, 1,555 reviews) |
| Salary | **BORDERLINE** (SWE comp at bottom of Munich band; no floor in criteria) |
| AI/ML content | **PASS** (strong: applied AI in clinical diagnostics, navify, NVIDIA/AWS) |
| Computer-language-primary | **PASS** (Python core for AI/ML/data; some Java in platforms) |
| No on-call | **CAUTION** (team-dependent; navify SaaS roles may have it) |
| WLB / Stability | **PASS** (WLB 4.4 DE; rock-solid financials) |
| Regulated industry | **CAUTION** (high burden) |
| Toxic leadership risk | **LOW** |

---

## Section 13: Verdict

**Recommendation: Exclude for a Munich-based hybrid arrangement; monitor only for a genuinely fully-remote Germany role.**

**Strengths.** Roche is excellent: a 130-year, deeply profitable, family-controlled blue-chip; a strong culture (Kununu 4.0 / 84% recommend over 1,555 reviews; Germany WLB 4.4; LOW toxicity risk); a serious, production-grade applied-AI program (navify digital pathology, lab-in-the-loop, NVIDIA/AWS); a Python-centric AI/ML stack on AWS/Kubernetes; English working language. The interview process is experience/design-led rather than a LeetCode gauntlet.

**Hard blockers (numbered).**

**Secondary concerns (not individually disqualifying).**
- Software-centric is only BORDERLINE: engineering is a strong but supporting discipline inside a pharma/diagnostics company.
- SWE-specific Glassdoor (3.8) is below the 4.0 threshold, hinting the engineering experience trails the company average.
- Salary for senior SWE sits at the bottom of the Munich band.
- The currently-open Bavaria roles skew toward Cloud DevOps/data-engineering (possible on-call; not pure AI/ML) rather than a Senior/Staff AI/ML product role.

**Recommendation sentence.** Do not pursue a Penzberg-based role. The only scenario worth acting on is a **fully-remote (Germany) Senior/Staff AI/ML or ML-platform role** in Diagnostics/digital pathology - if one appears, it would be a top-tier content-and-culture fit and worth applying immediately, verifying at interview that (a) the contract is genuinely remote (not Penzberg-presence-required), (b) the role is AI/ML engineering rather than SRE/on-call DevOps, and (c) the salary band reaches the market levels.

---

## Sources

- [Roche Annual Report 2025](https://www.roche.com/investors/annualreport25)
- [Roche Finance Report 2025 (PDF)](https://assets.roche.com/f/176343/x/fca190f63e/fb25e.pdf)
- [Roche Holding AG Revenue - MacroTrends](https://www.macrotrends.net/stocks/charts/RHHBY/roche-holding-ag/revenue)
- [Roche Group net income - Statista](https://www.statista.com/statistics/266520/roche-group-net-profit-since-2007/)
- [Roche Diagnostics GmbH - Handelsregister HRB 3962 Mannheim](https://www.online-handelsregister.de/handelsregisterauszug/bw/Mannheim/HRB/3962/Roche-Diagnostics-GmbH)
- [Roche Diagnostics Deutschland GmbH - NorthData (HRB 708167)](https://www.northdata.com/Roche%20Diagnostics%20Deutschland%20GmbH,%20Mannheim/HRB%20708167)
- [Roche Diagnostics GmbH Werk Penzberg](https://www.praxis-depesche.de/firmen/roche-diagnostics-gmbh/)
- [Roche Diagnostics R&D - Penzberg](https://www.roche.com/innovation/structure/rnd-locations/dia-penzberg)
- [Roche Reviews - Glassdoor](https://www.glassdoor.com/Reviews/Roche-Reviews-E3480.htm)
- [Roche Reviews in Germany - Glassdoor](https://www.glassdoor.com/Reviews/Roche-Germany-Reviews-EI_IE3480.0,5_IL.6,13_IN96.htm)
- [Roche Software Engineer Reviews - Glassdoor](https://www.glassdoor.com/Reviews/Roche-Software-Engineer-Reviews-EI_IE3480.0,5_KO6,23.htm)
- [Roche Diagnostics Penzberg - Kununu](https://www.kununu.com/de/roche-diagnostics-penzberg)
- [Roche - Great Place To Work profile](https://www.greatplacetowork.com/worlds-best-profile/roche)
- [Roche Software Engineer Salary Germany - levels.fyi](https://www.levels.fyi/companies/roche/salaries/software-engineer/locations/germany)
- [Software Engineer Salary Munich - levels.fyi](https://www.levels.fyi/t/software-engineer/locations/munich-deu)
- [Roche AI & machine learning - drug discovery](https://www.roche.com/stories/ai-revolutionising-drug-discovery-and-transforming-patient-care)
- [Roche scales NVIDIA AI factories - NVIDIA Blog](https://blogs.nvidia.com/blog/roche-ai-factories-omniverse/)
- [Roche AI drug discovery - AI Magazine](https://aimagazine.com/news/ai-drug-discovery-how-roche-accelerates-health-innovation)
- [navify digital solutions](https://navify.roche.com/)
- [Roche NAVIFY on AWS - case study](https://aws.amazon.com/solutions/case-studies/roche-case-study-video/)
- [Senior Cloud DevOps Software Engineer for Roche - Built In](https://builtin.com/job/senior-cloud-devops-software-engineer/6584241)
- [Roche careers - Germany Penzberg](https://careers.roche.com/global/en/germany-penzberg)
- [Roche to shrink product development team - Fierce Biotech](https://www.fiercebiotech.com/biotech/roche-shrink-product-development-team-mainly-impacting-contractors)
- [Roche to shut down Applied Sciences, cut jobs - GenomeWeb](https://www.genomeweb.com/sequencing/roche-shut-down-applied-sciences-business-area-cut-jobs-germany-and-connecticut)
- [Roche Software Engineer Interview Questions - Glassdoor](https://www.glassdoor.com/Interview/Roche-Software-Engineer-Interview-Questions-EI_IE3480.0,5_KO6,23.htm)
- [Roche Software Engineer interview guide - InterviewQuery](https://www.interviewquery.com/interview-guides/roche-software-engineer)
