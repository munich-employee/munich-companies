# Grafana Labs - Full Research Report

_Researched: 2026-11-12_

> **Critical Disqualifiers** (none absolute, but two near-blockers for the target profile)
> 1. **On-call is the norm in engineering.** 32 of 47 open engineering postings (all countries) mention on-call; the Germany Alerting and Database Observability postings require joining on-call rotations.
> 2. **Go-centric product engineering.** Most backend roles are Go. The one clearly Python- and AI-aligned Germany role (Staff SWE, OpenTelemetry Python instrumentation for GenAI) is the exception, not the pattern. The "Staff AI Engineer" role is US/Canada only.

---

## 1. Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 2014 (12 years) |
| Employees | ~1,400-1,800 globally (TrueUp 1,400; PitchBook 1,600; Glassdoor band 1,001-5,000); 100% remote across 40+ countries |
| Revenue (ARR, Aug 2026) | "Significantly surpassed" **$600M ARR** (company press release, 26 Aug 2026), up from $400M (Sep 2025) and $250M (Aug 2024). ~50% YoY growth |
| Profitability | Not disclosed. Third-party (Sacra) says cash-flow break-even was reached "early in its journey"; no GAAP figures published. German GmbH is a cost-plus subsidiary - **BORDERLINE** (growth-stage, well-funded, no confirmed profit) |
| Ownership | Private, VC-backed (Lightspeed, Sequoia, GIC, Coatue, J.P. Morgan, CapitalG, Lead Edge) |
| Software-centric | Observability SaaS (Grafana Cloud) plus open-source projects (Grafana, Loki, Mimir, Tempo, Pyroscope, k6, Alloy) - **PASS** |

### Key People

- **Raj Dutt** - co-founder and CEO (93% Glassdoor approval globally)
- **Torkel Ödegaard** - creator of Grafana, co-founder
- **Anthony Woods** - co-founder
- German GmbH managing directors (NorthData): Irene Li, Bryant Smick (current), earlier Wailun Chan, Afshin Mazhari, David Kaltschmidt; Prokura: Alice Farrell

### Funding History

| Date | Round | Amount | Valuation |
|---|---|---|---|
| 2019 | Series A | $24M | n/a |
| Oct 2020 | Series B | $50M | n/a |
| Aug 2021 | Series C | $220M | $3B |
| Jan 2022 | Series D | $240M | not disclosed |
| Aug 2024 | Primary + secondary | $270M | $6B |
| Sep 2025 | New investors / tender (~$150M liquidity) | n/a | ~$6.6B |
| Mar 2026 | Series E (GIC lead) | ~$250M | ~$9B (reported, not company-confirmed) |

No IPO filing. IPO-tracking sites list it as "pre-IPO"; a site claiming an S-1 at $12.5B conflicts with every other source and is disregarded.

### Business Model

Open-core: free OSS (AGPLv3 for core projects) drives adoption; revenue comes from Grafana Cloud (usage-based SaaS), Grafana Enterprise and enterprise plugins. 10,000+ customers, 500,000+ Cloud signups over two years, average 4.4 products per contracted customer.

---

## 2. Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **Grafana Labs GmbH** | Amtsgericht Charlottenburg (Berlin), **HRB 210049 B** (EUID DEF1103R.HRB210049B) | Maximiliansplatz 22, 80333 München | "Software development." Share capital €25,000; 100% owned by Grafana Labs Ltd. (UK) |

The registered purpose is **software development**, not sales and distribution. The entity was founded in 2019 and has moved between Berlin and Munich (NorthData history: Munich → Berlin → Munich → Berlin → Munich; registry court still Charlottenburg). Germany postings are advertised as "Germany | Remote" with EUR salary bands and German benefits, and a Munich-based senior SWE reviewer (Glassdoor) and a Munich-based R&D Führungskraft (Kununu) confirm engineers are employed directly via the GmbH. A reviewer noted Grafana "stopped hiring in regions where they don't have legal entity", which confirms direct employment rather than EOR for Germany.

**Verdict:** PASS

---

## 3. Office Location

- **Office address:** Maximiliansplatz 22, 80333 München (Kreuzviertel, Altstadt-Lehel), confirmed via Nominatim. This is the registered address from NorthData; Grafana advertises **no physical office**. The company states it is "a 100% remote company with team members across 40+ countries". The grafana.com imprint URL now returns a 404 (fetched via CDP).
- **Nearest public transport** (straight-line from the registered address, OSM Overpass):
  - Lenbachplatz (tram stop) - 130 m
  - Ottostraße (tram stop) - 220 m
  - Karlsplatz (Stachus) (U-Bahn U4/U5, S-Bahn trunk line) - 260 m
  - Odeonsplatz (U-Bahn station) - 480 m
  - Marienplatz (U-Bahn/S-Bahn station) - 540 m
- **Work model:** Fully remote. All Germany roles are posted as "Germany | Remote". Germany is in Grafana's EMEA hiring set (Germany, UK, Ireland, Spain, Sweden). Remote eligibility is restricted to countries with a Grafana entity; work-visa sponsorship is not offered (Glassdoor review, Aug 2026). Occasional team and company off-sites.

---

## 4. Reviews

**GPTW:** Not found. No Great Place to Work Germany listing or certification found for Grafana Labs (any country). Past awards: Inc. Best Workplaces 2020 and 2023, Forbes America's Best Startup Employers 2021.

### Glassdoor

Fetched via CDP (logged-in session); glassdoor.com review URLs 404, glassdoor.co.uk worked.

| Metric | Global | Germany | Munich | Software Engineers | Senior Software Engineers |
|---|---|---|---|---|---|
| **Overall** | 4.0 (233 EN / 245 all) | 4.2 (8) | 5.0 (1) | 4.2 (21) | 4.2 (15) |
| **WLB** | 4.2 | 4.3 | 5.0 | 3.7 | 4.3 |
| **Culture & Values** | 4.0 (down 6% YoY) | 4.6 | 5.0 | 3.7 | 4.3 |
| **Comp & Benefits** | 4.1 | 3.5 | 4.0 | 3.2 | 4.0 |
| **Career Opportunities** | 3.6 | 4.7 | 5.0 | 2.6 | 3.3 |
| **Senior Management** | 3.7 | 3.9 | 4.0 | n/a | n/a |
| **Diversity & Inclusion** | 4.1 | 4.2 | 5.0 | 3.7 | 4.1 |
| **% Recommend** | 73% | 97% | 100% | 98% (sic) | 77% (down 22% in 12 months) |
| **CEO Approval** | 93% | 99% | 100% | 98% | 78% |
| **Business Outlook** | 76% positive | 97% | 100% | 98% | 77% |

Notes:
- Germany (8), Munich (1), SWE (21) and Senior SWE (15) are all **below 20 reviews: directional only**. The SWE filter is internally inconsistent (98% recommend alongside 2.6 career and 3.2 comp sub-scores), which suggests Glassdoor computes the percentages and sub-scores over different subsets.
- The 6-month trend for the global overall rating moves between 3.9 and 4.3. The Senior SWE recommend rate falling 22% in a year is the clearest negative trend.
- Top reviewed job titles are SDR (24), Software Engineer (21), Senior SWE (18), Account Executive (13): a large share of negative global reviews come from go-to-market roles.

### Kununu

Fetched via CDP (`https://www.kununu.com/de/grafana-labs1`; slugs `grafana-labs`, `grafanalabs`, `grafana-labs-gmbh` returned 405 via curl).

- **Overall score:** 2.7 / 5.0 (last 2 years)
- **Recommendation rate (Weiterempfehlung):** 50%
- **Total reviews:** 6 total; 2 employee reviews in the last 2 years
- **Kununu Top Company:** NO (profile not claimed: "nicht auf kununu aktiv")
- Sub-scores: Karriere & Gehalt 5.0, Unternehmenskultur 4.1, Arbeitsumgebung 5.0, Vielfalt 5.0. Two reviews: one 4.9 from R&D management (Oct 2025), one 1.0 from sales (Aug 2026). Statistically meaningless.

### Blind / Teamblind

Fetched via CDP.

| Metric | Score |
|---|---|
| Overall | **4.0** (45 reviews) |
| Work Life Balance | 4.1 |
| Career Growth | 3.7 |
| Company Culture | 3.8 |
| Management | 3.6 |
| Compensation / Benefits | 3.5 (lowest) |

### Review Themes (2025-2026)

**Positives:**
- **Remote work done properly, autonomy, WLB.** "Great work life balance and autonomy on your work. Full remote." (Blind, Jun 2026, current Staff Software Engineer). "remote culture ... very supportive and professional team members ... you don't feel stressed out most of the times" (Glassdoor, May 2025, current Senior Software Engineer, Munich, 3+ years).
- **Strong colleagues and open-source profile.** "A genuine perk for engineers is the opportunity to contribute to open source, which translates directly into a stronger public profile" (Blind, Jun 2026, current Software Engineer).
- **Pay and benefits (global view).** "Outstanding remote work with great compensation and culture ... Remote, great compensation, WLB and culture" (Glassdoor, Oct 2026, current Anonymous Employee, 1+ year). 30 days PTO is cited repeatedly.
- **Principal-level freedom.** "At principal level, you are expected to figure out what's the most impactful work you can do" (Glassdoor, Aug 2024, current Principal Engineer, Berlin, 3+ years).
- **Financially solid.** "Good sales growth, so financials are solid" (Blind, Jun 2026, current Engineering Manager).

**Negatives:**
- **Promotion is hard and political** (multi-platform, multi-year). "Promotions will be heavily driven on the team / manager advocating for you ... there's always an excuse or reason to not promote despite meeting certain criteria" (Glassdoor, Sep 2026, current Software Engineer, 5+ years). "career growth depends more on which faction you align with than on merit" (Blind, Jun 2026, current Software Engineer). "very high requirements for promoting to a higher position" (Glassdoor, May 2025, current Senior SWE, Munich).
- **Management quality and politics.** "a gap in trust between leadership and individual contributors ... management politics sometimes overshadowed input from the people doing the work" (Glassdoor, Oct 2026, former Senior Software Engineer, 1+ year). "Managers are incompetent and contribute no meaningful leadership" (Glassdoor, Mar 2026, current Software Engineer). "Broken promotion culture, blaming, inadequate management, inter-competing teams" (Blind, Jun 2026, current Staff Software Engineer).
- **Unexplained departures / PIPs** (silent-firing signal). "Company doesn't do layoffs but folks will randomly disappear with no explanation. Uses a PIP system which conveniently is super generic and impossible to attain" (Glassdoor, Oct 2026, former SDR, New York). "No transparency as to which reason people get fired, when it happens." (Glassdoor, Jan 2026, current Senior Software Engineer, 3+ years). "coasting will earn you a PIP" (Blind, May 2026, current Digital Marketing).
- **On-call weighs on WLB.** Review titled "Good work-life balance if you don't count on-calls"; "IPO hungry, 'we're all in sales', changing priorities, management has very little clues about technical challenges" (Glassdoor, Dec 2025, former Senior Software Engineer, 3+ years).
- **European pay below US; equity skewed to early staff.** "if you're in Europe you'll get paid less than someone in US despite doing the same work" (Glassdoor, May 2025, current Senior SWE, Munich). "Equity is heavily skewed toward early employees ... recent hires receive little to no meaningful ownership" (Blind, Jun 2026, current Software Engineer).
- **High pace / stress.** "high stress, too much expectations beyond your level" (Glassdoor, Jul 2026, former Software Engineer 1, Berlin, 1+ year).
- **GTM/sales culture is markedly worse** than engineering (SDR, Finance, SE management reviews); "Leaders exhibited toxic behavior" style quotes cluster in non-engineering orgs.

Overlap with hard red flags: **silent firings** (repeated, multi-platform), **on-call**, and **communication breakdown** between leadership and ICs.

### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| Toxic Leadership | Present but concentrated in GTM/Finance. Engineering complaints are about weak or political middle management rather than abuse. "Benefits and pay overshadowed by toxic management" (Glassdoor, Oct 2026, former Anonymous Employee, Finance). One extreme Blind review (Apr 2026, former Product Manager) calls leadership "psychopaths and narcissists". |
| 24/7 Work Expectation | Not reported as a norm. Fast pace and high expectations, but WLB scores 4.1-4.3. |
| Internal Surveillance | No reports found. |
| Fear-driven Management | Some: PIPs described as generic and unattainable (sales); "coasting will earn you a PIP" (marketing); "no psychological safety" (Glassdoor FAQ excerpt, role not shown). |
| Communication Breakdown | Moderate: "gap in trust between leadership and individual contributors" (former Senior SWE, Oct 2026); "No real strategy" (Blind, EM, Jun 2026); "constantly changing goals" (Blind, Staff SWE, Jun 2026). |
| Unpaid Overtime | Not reported explicitly; "Long Hours" (Glassdoor, Mar 2025, former Senior Engineering Manager, Berlin). |
| Silent Firings | **Yes, recurring.** "folks will randomly disappear with no explanation" (Oct 2026, SDR); "No transparency as to which reason people get fired" (Jan 2026, Senior SWE); 2023 GTM review: "The way people are being let go is inhumane" (Glassdoor, Oct 2023, former GTM, Berlin). |
| Work-Life Balance issues | Mostly positive; the on-call caveat is the main engineering complaint. |

**Risk level: MODERATE.** Not systemic toxicity in engineering, but (c) localized dysfunction that is widespread enough to recur across platforms: political promotions, uneven middle management, and quiet performance-based exits without a works council to make them visible. GTM is clearly worse than engineering.

---

## 5. Compensation

### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| levels.fyi (Germany) | Senior Software Engineer 1 | ~€108K | ~€7.6K | 0 | ~€115K | averaged, count not shown |
| levels.fyi (Germany) | Senior Software Engineer 2 | ~€122K | ~€10.7K | 0 | ~€133K | averaged |
| levels.fyi (Germany) | Staff Software Engineer | n/a | n/a | 0 | ~€159K | averaged |
| levels.fyi (Germany, single) | Staff SWE, Berlin, Feb 2026 | €140K | ~€20K | 0 | €160K | 1 |
| levels.fyi (Germany, single) | L5, Frankfurt, Sep 2026 | €148K | ~€50K | 0 | €198K | 1 |
| Job posting (Glassdoor/Greenhouse) | Staff SWE, OpenTelemetry Python | €113K-141K | RSUs | n/a | n/a | posted band |
| Job posting | Staff Backend Engineer, Alerting / Staff SWE Databases SRE | €109.7K-131.7K | RSUs | n/a | n/a | posted band |
| Job posting | Senior Full Stack, Databases Analytics | €109.7K-131.7K | equity | if applicable | n/a | posted band |
| Job posting | Senior Full Stack, Database Observability | €100K-125K | RSUs | n/a | n/a | posted band |
| Job posting | Senior SWE, Security Assurance | €97.0K-116.4K | RSUs | n/a | n/a | posted band |

The levels.fyi German median across levels is **€137K** total. levels.fyi averages dropped versus March 2026 (Senior 1: €135K → €115K; Senior 2: €156K → €133K), while Staff stays ~€159-160K.

**Munich market reference** (levels.fyi, Senior Software Engineer, Munich metro; figures as observed in an earlier 2026 run, page did not render this run): median ~€99K, 75th ~€117K, 90th ~€158K total compensation.

### Equity / Stock

All roles include **RSUs** in a private company (no ticker). Liquidity comes only from periodic tender offers (e.g. ~$150M in 2025) or an eventual IPO, which has no announced timeline. Grants are small relative to cash in Germany (~€8-20K/yr at Senior/Staff by levels.fyi). Reviewers say equity is "heavily skewed toward early employees". No bonus for engineers.

### Verdict

Staff total comp (~€160K, base €113-141K posted for the Python role) sits around the Munich 90th percentile and is **comparable to or above** large, profitable Munich corporations (typically ~€85-110K base senior, €120K+ at the 90th percentile). Senior bands (€97-132K base) are comparable. The risks are down-leveling (Staff vs Senior is a ~€25-40K swing), illiquid RSUs, and lower EU-vs-US pay.

**COMPARABLE** (ABOVE at Staff if the level holds)

---

## 6. AI/ML & Tech Stack

### AI Strategy

Genuine and central to the product roadmap, not marketing:
- **Grafana Assistant** - context-aware LLM agent for exploring and troubleshooting observability data; GA Oct 2025, used by 18,000+ organizations (Aug 2026).
- **Assistant Investigations** - multi-agent incident investigation correlating metrics, logs and traces.
- **Agent Observability / AI Observability** - monitoring LLMs and agents (latency, token cost, agent decisions).
- **Grafana Cloud MCP server** and **gcx** (Grafana Cloud CLI) for AI agents and coding tools.
- **OpenTelemetry GenAI instrumentation** - the Germany Staff Python role builds OTel Python instrumentation for AI agents and agent workflows.
- **Knowledge graph / agent-facing retrieval** - the Germany "Databases - Analytics" role builds APIs for "AI agents, MCP tools, CLIs" to retrieve context, provenance and confidence signals.

This is applied AI engineering (LLM agents, tooling, instrumentation), not model training. The dedicated "Staff AI Engineer" posting (Python/Node, RAG, multi-agent) is US/Canada only and sits in Marketing Ops.

### Tech Stack

Derived from 47 current engineering postings on Greenhouse (all countries), the 5 Germany engineering postings in full text, and the grafana GitHub org (523 public repos).

| Category | Technologies |
|---|---|
| **Primary language(s)** | Go (30 of 47 postings; "We use Go" for backend teams); TypeScript/React (frontend, plugins: ~20); Python (21 mentions; primary only in OTel Python instrumentation and parts of AI work); Rust (mentioned as a plus in 18) |
| **AI/ML** | LLM agents, MCP, RAG, prompt engineering, agent evaluation; OpenTelemetry GenAI semantic conventions; LangChain/LangGraph mentioned in 2 postings; company-funded AI coding assistant budget |
| **Cloud** | Multi-cloud Grafana Cloud on GCP, AWS and Azure |
| **Infrastructure** | Kubernetes, Jsonnet/Tanka, Terraform, Argo; Prometheus, Loki, Mimir, Tempo, Pyroscope, Alloy (own OSS stack) |
| **Data** | Object-storage-backed time-series/log/trace databases (Mimir, Loki, Tempo), MySQL, Kafka, BigQuery (internal analytics) |
| **Other** | OpenTelemetry, k6 (load testing), on-call rotations owned by product teams |

**Summary:** Go-centric distributed-systems engineering (TSDB, logs, traces, alerting) with a TypeScript/React frontend and a growing Python/LLM agent layer on multi-cloud Kubernetes. Applied production engineering on an open-source observability platform, not research.

---

## 7. Language

All postings are in English; no German requirement anywhere; engineers work in a 40+ country remote team where English is the only common language.

**Verdict:** PASS

---

## 8. Stability

### Financial Position

- ARR >$600M (Aug 2026), roughly +50% YoY; 10,000+ customers; product attach rising (2.3 → 4.4 products per contracted customer).
- ~$250M Series E (Mar 2026) at ~$9B valuation, on top of $270M (2024) and earlier rounds: likely $500M+ cash on hand, though not disclosed.
- Third-party claim of cash-flow break-even; no audited figures. The German GmbH's NorthData earnings chart shows only a small figure (scale up to ~€1.2M), consistent with a cost-plus service subsidiary.

### Financial Runway

Grafana is VC-backed and does not publish profitability, so a rough model:

| Cost line | Annual estimate |
|---|---|
| Staff (~1,700 × ~$220K fully loaded, global mix) | ~$375M |
| Cloud infrastructure for Grafana Cloud (~25-30% of revenue) | ~$160M |
| Sales & marketing programmes, events, G&A, other | ~$100M |
| **Total gross burn** | **~$635M/year** |

| Revenue source | Est. annual inflow |
|---|---|
| ARR (Aug 2026, run-rate) | ~$600M |
| **Total revenue offset** | **~$600M/year** |

| Scenario | Net burn | Cash at hand | Runway | Next round needed by |
|---|---|---|---|---|
| Optimistic (ARR +40%, cost +20%) | ≈ cash-flow positive | ~$500M (est.) | Indefinite | Not needed |
| Base case | ~$35M/year | ~$500M (est.) | 10+ years | Not needed |
| Stress (growth stalls, costs keep rising) | ~$150M/year | ~$500M (est.) | ~3+ years | ~2029-2030 |

Cash figure is an **estimate** (sum of 2024 primary and 2026 Series E proceeds less assumed historic burn); no balance sheet is published. Even the stress case leaves years of runway; the company is near break-even on any reasonable assumption.

### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| - | No announced layoffs | - | TrueUp: "No known layoffs". |
| Mar 2025 | Customer Success cuts (reported in reviews) | Unknown | Not announced; inferred from reviews (from the March 2026 research run). |
| 2023-2026 | Recurring individual exits via PIP / unexplained departures | Unknown | "Company doesn't do layoffs but folks will randomly disappear" (Glassdoor, Oct 2026). |

No formal layoffs, but managed-out attrition is a recurring theme.

### Works Council & Collective Agreement

| Item | Finding | Evidence |
|---|---|---|
| Works council (Betriebsrat) | **NO evidence** (likely none) | No mention in Kununu/Glassdoor reviews, postings or press; web search "Grafana Labs Betriebsrat / works council" returned nothing relevant. A fully remote GmbH with no office makes one unlikely. |
| Collective agreement | **NONE** (likely) | Postings show individual EUR bands, no tariff wording. |
| European works council | NO evidence | Below likely thresholds; none found. |
| Conflict signals | None found | - |

No council and no agreement, together with the recurring silent-firing reports, means individual exits can happen quietly with only statutory KSchG protection.

**Verdict:** CAUTION

---

## 9. Regulated Industry

Not regulated. Observability SaaS carries standard compliance work (SOC 2, ISO 27001, FedRAMP for US government cloud, GDPR); the Security Assurance role covers this. No safety-critical or financial-regulatory engineering overhead for product teams.

**Verdict:** PASS

---

## 10. On-Call

- 32 of 47 open engineering postings mention on-call.
- Germany: **Staff Backend Engineer, Alerting**: "Be a part of your team's on-call rotations and take ownership of the services you're running." **Senior Full Stack, Database Observability**: "Participate in on-call for the software you help build" and "You have experience being on-call".
- Germany **Staff SWE, OpenTelemetry Python** (SDK/library work) and **Security Assurance** postings do not mention on-call.
- Review: "Good work-life balance if you don't count on-calls" (Glassdoor, Dec 2025, former Senior SWE, 3+ years).

You-build-it-you-run-it is the default for Grafana Cloud backend teams. Library/SDK teams (OpenTelemetry instrumentation) are the realistic exception.

**Verdict:** CAUTION (team-dependent; effectively FAIL for Cloud backend teams)

---

## 11. Interview Process

| Metric | Value |
|---|---|
| Difficulty | 2.9 / 5 (Glassdoor, all roles) |
| Positive experience | 29.5% (all roles, 193 interviews); 25% for Senior Software Engineer (16 interviews) |
| Average duration | ~24 days |
| Rounds | 5 (recruiter + 4 stages) |

Process for backend/distributed systems engineers (Grafana engineering blog):
1. Recruiter call
2. Hiring manager interview (45 min)
3. Collaborative coding exercise (60 min, two engineers, your language, a real problem; "the code itself isn't the pass criteria")
4. Non-Abstract Large System Design (NALSD, 60 min, two engineers)
5. Final/cross-functional conversation

Some roles add a code screen (Security Assurance posting). **Not LeetCode-heavy**: collaborative coding plus Google-style NALSD design. The low positive-experience rate is driven by recruiter communication (weeks of silence, impersonal rejections), not by interview content.

---

## 12. Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | PASS - observability SaaS + OSS |
| Not consulting | PASS |
| Profitable | BORDERLINE - private, near break-even claimed, >$600M ARR, well funded |
| Employee count | PASS - ~1,400-1,800 |
| English-speaking | PASS |
| Local entity + engineering contracts | PASS - Grafana Labs GmbH, HRB 210049 B, purpose "Software development" |
| Location / work model | PASS - fully remote in Germany; registered address Maximiliansplatz 22, Munich |
| Glassdoor | PASS - 4.0 global (233), SWE 4.2 (21), Germany 4.2 (8); Senior SWE recommend down 22% YoY |
| Kununu | UNRELIABLE - 2.7, 2 recent reviews |
| Salary | COMPARABLE (Staff ~€160K TC; posted Staff base €110-141K) |
| AI/ML content | PARTIAL - strong AI product strategy; one Germany role (OTel Python for GenAI) and one agent-retrieval role are AI-adjacent |
| Computer-language/Tech-stack | Go-centric; Python primary only in OTel Python / some AI roles |
| No on-call | CAUTION / FAIL for Cloud backend teams |
| WLB / Stability | GOOD WLB (4.2); strong growth and funding; no layoffs but silent exits |
| Works council / collective agreement | CAUTION - none found |
| Regulated industry | PASS |
| Review themes | Remote/autonomy/colleagues vs political promotions, uneven management, silent exits |
| Down-leveling risk | Recurring theme; strict promotion bar |

---

## 13. Verdict

**Monitor, and apply selectively to the OpenTelemetry Python (GenAI instrumentation) Staff role only.**

**Strengths:** Grafana is a fast-growing (>$600M ARR, ~+50% YoY), well-funded ($9B valuation) open-source observability company with a real, shipped AI agent strategy (Assistant, Investigations, Agent Observability, MCP). It hires directly through a German GmbH registered for software development, fully remote, in English. Engineering reviews consistently praise autonomy, WLB and colleagues, and Staff total comp (~€160K) is at the Munich 90th percentile.

**Hard blockers:**
1. **On-call:** Cloud backend and full-stack teams in Germany require on-call rotations (Alerting, Database Observability postings). Only library/SDK teams such as OpenTelemetry instrumentation appear exempt.
2. **Go-centric stack:** 30 of 47 engineering postings use Go as the main language. Python-first work is limited to the OTel Python team and parts of the AI layer.

**Secondary concerns:**
- Silent exits via PIPs and unexplained departures, without a works council or collective agreement to make them visible.
- Political, manager-dependent promotions; Glassdoor SWE career score 2.6, Senior SWE recommend rate down 22% in a year.
- Down-leveling risk: a Staff→Senior placement costs ~€25-40K/yr.
- RSUs in a private company with no IPO timeline; equity reportedly skewed to early employees.
- Poor candidate experience (25-30% positive), driven by recruiter communication.

**Recommendation:** Apply only to the **Staff Software Engineer - OpenTelemetry Python instrumentation (Germany, €113-141K base + RSUs)** role, which avoids both blockers (Python-first, GenAI agent instrumentation, no on-call listed). Verify during the process:
- the team's on-call expectations in writing;
- that the offer is at Staff level, not Senior;
- the RSU grant size and the tender-offer cadence;
- how the team handles performance management and promotions.

Skip the Go backend and full-stack roles.

---

## 14. Sources

- [Grafana Labs press: 10,000 customers, $600M ARR (Aug 2026)](https://grafana.com/press/2026/08/26/grafana-labs-crosses-10000-customer-milestone-as-ai-adoption-accelerates-growth-across-the-platform/)
- [Grafana Labs press: Breakout year (Feb 2026)](https://grafana.com/press/2026/02/03/grafana-labs-caps-a-breakout-year-of-growth-and-product-innovation/)
- [Grafana Labs press: $400M ARR, 7,000 customers (Sep 2025)](https://grafana.com/about/press/2025/09/30/grafana-labs-surpasses-400m-arr-and-7000-customers-gains-new-investors-to-accelerate-global-expansion/)
- [Grafana Labs press: $250M ARR, $270M transaction (Aug 2024)](https://grafana.com/press/2024/08/21/grafana-labs-soars-past-250m-arr-and-5000-customers-completes-270m-primary-and-secondary-transaction-and-named-a-leader-in-the-gartner-magic-quadrant-for-observability-platforms/)
- [SiliconANGLE: Grafana raising at $9B valuation (Feb 2026)](https://siliconangle.com/2026/02/13/grafana-labs-reportedly-raising-funding-9b-valuation/)
- [CB Insights: Grafana Labs financials](https://www.cbinsights.com/company/grafana-labs/financials)
- [PitchBook: Grafana Labs profile](https://pitchbook.com/profiles/company/109176-76)
- [Sacra: Grafana Labs](https://sacra.com/c/grafana-labs/)
- [Pulse 2.0: $600M ARR coverage](https://pulse2.com/grafana-labs-surpasses-600-million-arr-and-10000-customers-as-ai-assistant-reaches-18000-organizations/)
- [IT Brief UK: Grafana tops 10,000 customers](https://itbrief.co.uk/story/grafana-labs-tops-10-000-customers-as-ai-demand-rises)
- [Wikipedia: Grafana](https://en.wikipedia.org/wiki/Grafana)
- [TechStackIPO: Grafana Labs (disregarded S-1 claim)](https://www.techstackipo.com/ipo/grafana-labs)
- [NorthData: Grafana Labs GmbH, HRB 210049 B](https://www.northdata.com/Grafana%20Labs%20GmbH,%20Berlin/Amtsgericht%20Charlottenburg%20(Berlin)%20HRB%20210049%20B) (CDP)
- [Grafana imprint (404 at time of research)](https://grafana.com/legal/imprint/) (CDP)
- [Nominatim: Maximiliansplatz 22](https://nominatim.openstreetmap.org/search?q=Maximiliansplatz+22,+80333+M%C3%BCnchen&format=json&addressdetails=1) (curl)
- [Overpass API (mail.ru mirror)](https://maps.mail.ru/osm/tools/overpass/api/interpreter) (curl; main instance returned 406)
- [Glassdoor: Grafana Labs overview](https://www.glassdoor.com/Overview/Working-at-Grafana-Labs-EI_IE2300269.11,23.htm) (CDP)
- [Glassdoor: Global reviews](https://www.glassdoor.co.uk/Reviews/Grafana-Labs-Reviews-E2300269.htm) (CDP)
- [Glassdoor: Germany reviews](https://www.glassdoor.co.uk/Reviews/Grafana-Labs-Germany-Reviews-EI_IE2300269.0,12_IL.13,20_IN96.htm) (CDP)
- [Glassdoor: Munich reviews](https://www.glassdoor.co.uk/Reviews/Grafana-Labs-Munich-Reviews-EI_IE2300269.0,12_IL.13,19_IC4990924.htm) (CDP)
- [Glassdoor: Software Engineer reviews](https://www.glassdoor.co.uk/Reviews/Grafana-Labs-Software-Engineer-Reviews-EI_IE2300269.0,12_KO13,30.htm) (CDP)
- [Glassdoor: Senior Software Engineer reviews](https://www.glassdoor.co.uk/Reviews/Grafana-Labs-Senior-Software-Engineer-Reviews-EI_IE2300269.0,12_KO13,37.htm) (CDP)
- [Glassdoor: Interviews](https://www.glassdoor.co.uk/Interview/Grafana-Labs-Interview-Questions-E2300269.htm) (CDP)
- [Glassdoor: Senior SWE interviews](https://www.glassdoor.co.uk/Interview/Grafana-Labs-Senior-Software-Engineer-Interview-Questions-EI_IE2300269.0,12_KO13,37.htm) (CDP)
- [Kununu: Grafana Labs GmbH](https://www.kununu.com/de/grafana-labs1) (CDP)
- [Kununu: Grafana Labs reviews](https://www.kununu.com/de/grafana-labs1/kommentare) (CDP)
- [Blind: Grafana Labs reviews](https://www.teamblind.com/company/Grafana-Labs/reviews) (CDP)
- [levels.fyi: Grafana SWE Germany](https://www.levels.fyi/companies/grafana/salaries/software-engineer/locations/germany) (CDP)
- [levels.fyi: Senior SWE Munich market](https://www.levels.fyi/t/software-engineer/levels/senior/locations/munich-metro-area) (CDP, did not render)
- [Greenhouse API: Grafana Labs jobs](https://boards-api.greenhouse.io/v1/boards/grafanalabs/jobs?content=true) (curl)
- [Staff SWE - OpenTelemetry Python instrumentation, Germany](https://job-boards.greenhouse.io/grafanalabs/jobs/6250645004)
- [Staff Backend Engineer - Grafana Alerting, Germany](https://job-boards.greenhouse.io/grafanalabs/jobs/6105872004)
- [Senior Full Stack Engineer - Database Observability, Germany](https://job-boards.greenhouse.io/grafanalabs/jobs/6250631004)
- [Senior Full Stack Engineer - Databases Analytics, Germany](https://job-boards.greenhouse.io/grafanalabs/jobs/6200027004)
- [Senior SWE - Security Assurance, Germany](https://job-boards.greenhouse.io/grafanalabs/jobs/6228511004)
- [Staff AI Engineer, USA](https://job-boards.greenhouse.io/grafanalabs/jobs/6092955004)
- [Grafana blog: Hiring process for backend engineers](https://grafana.com/blog/inside-grafana-labs-hiring-process-for-backend-engineers/) (CDP)
- [Grafana blog: Inc. Best Workplaces 2023](https://grafana.com/blog/2023/05/09/grafana-labs-named-to-the-inc.-best-workplaces-2023-list)
- [TrueUp: Grafana layoffs](https://www.trueup.io/co/grafana) (CDP)
- [GitHub: grafana organisation](https://github.com/grafana) (API via curl)
- [Grafana Assistant GA (Oct 2025)](https://grafana.com/about/press/2025/10/08/grafana-labs-revolutionizes-ai-powered-observability-with-ga-of-grafana-assistant-and-introduces-assistant-investigations/)
