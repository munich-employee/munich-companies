# osapiens - Full Research Report

_Researched: 2026-08-05_

> **Critical Disqualifiers**
> 1. **Glassdoor 3,1 / 5** (42 reviews, 43% recommend, 54% CEO approval). **FAIL**
> 2. **Repeated, recent, explicit toxic-leadership red flags.** The five most recent Glassdoor reviews (all July 2026, all current employees) independently allege a co-CEO who "yells at people" / "screams at people regardless of department", "a culture of fear rather than empowerment", "employees are shouted at, brought to tears and driven into burnout", "unpaid overtime is the norm and there is constant pressure to also work weekends", and "very high fluctuation". **FAIL**
> 3. **Not profitable.** VC-backed unicorn (Series C, January 2026); NorthData shows sustained losses at the holding level. **FAIL**
> 4. **Compensation far below the Munich senior bracket.** Glassdoor Germany shows Software Engineer / Software Development Engineer at €54K to €67K. **FAIL**
> 5. **No senior software engineering role in Munich.** The Munich office has exactly one engineering vacancy (Machine Learning Engineer, Geospatial AI, non-senior); all backend / full-stack / platform roles are Mannheim, hybrid at 3 days per week on-site. **FAIL for a Munich-based candidate**
>
> The full report follows for completeness.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 2018 (8 years) |
| Employees | ~550 to 600 globally (job postings say "more than 550"; third-party trackers report 564 in Jan 2026 and ~600 in Apr 2026) |
| Revenue (FY2025) | Not officially disclosed. Company states "almost 100% growth in 2025" and 42 consecutive months of >100% YoY ARR growth. Third-party estimate (GetLatka) puts 2025 revenue at ~$90M; treat as **UNVERIFIED** |
| Profitability | Loss-making. Company explicitly declined to comment on profitability in its 2025 hypergrowth release; NorthData's earnings chart for osapiens Holding GmbH is scaled to −€15M for 2022 to 2024 - **FAIL** |
| Ownership | Private, VC/growth-equity backed. Unicorn valuation (~$1.1B) since January 2026 |
| Software-centric | Multi-tenant B2B SaaS platform (osapiens HUB, 26 enterprise solutions). Registered purpose of the operating entity is "development and distribution of software in the B2B sector" - **PASS** |

### Key People

- **Alberto Zamora Pueyo**, co-founder and co-CEO
- **Stefan Wawrzinek**, co-founder and co-CEO
- **Matthias Jungblut**, co-founder and managing director
- **Jochen Morsbach**, authorised signatory (ppa, since March 2024)

All three founders are registered managing directors of both osapiens Holding GmbH and osapiens Services GmbH. Multiple reviews attribute the cultural problems specifically to "the co-CEO", without naming which of the two.

### Funding History

| Date | Round | Amount | Lead investor(s) | Valuation |
|---|---|---|---|---|
| 2019 to 2022 | Seed / early | undisclosed | NEXT Mannheim, angels | n/a |
| 2022 | Series A | undisclosed (~€10M reported) | Armira Beteiligungen | n/a |
| July 2024 | Series B | €110.7M (~$120M) | Growth Equity at Goldman Sachs Alternatives | n/a |
| January 2026 | Series C | €85.8M (~$100M) | Decarbonization Partners (BlackRock / Temasek JV) | ~$1.1B (unicorn) |
| **Total** | | **~$247M** | | |

### Business Model

Pure-play B2B SaaS. osapiens sells the "osapiens HUB", a multi-tenant platform hosting 26 modular enterprise applications for ESG and supply-chain regulatory compliance (CSRD, LkSG, EUDR, CBAM, product compliance), plus a maintenance/CMMS product line and, since the Lucent AI acquisition (December 2025), financial risk management. Customers number ~2,400 to 2,500 across 50+ countries. Revenue is subscription-based, not project-based.

### Consulting-Adjacency Assessment

osapiens does **not** self-identify as a consultancy, and the core engineering track is product engineering on a shared platform, not client billing. However, the job board carries a meaningful consulting-flavoured population:

- **Senior Solution Engineer** (Mannheim, Munich, Amsterdam, Madrid, Milan, Paris, London) - pre-sales
- **Senior Consultant Product Compliance** (Mannheim, Madrid)
- **Senior Supply Chain Traceability Consultant** (Mannheim, Munich, Madrid)
- **Senior IT Consultant** (Mannheim)

The holding company's registered purpose is "the acquisition and holding of shareholdings in **software and consulting companies**", which confirms consulting is a deliberate part of the group model. The engineering roles themselves (Java backend, Node/TypeScript full-stack, AI Engineer, ML Engineer, Linux platform) are genuine product roles.

**Verdict:** Not a consultancy for engineering purposes, but 4 of the 13 Munich vacancies and a large share of the Mannheim vacancies are consulting or pre-sales titles.

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **osapiens Services GmbH** (operating entity, Impressum entity) | HRB 731132, Amtsgericht Mannheim (EUID DEB8535.HRB731132), share capital €25,000 | Julius-Hatry-Str. 1, 68163 Mannheim | "The development and distribution of software in the B2B sector as well as all services and activities of all kinds related to the company's purpose." |
| **osapiens Holding GmbH** (parent) | HRB 731130, Amtsgericht Mannheim, share capital €25,000 | Julius-Hatry-Str. 1, 68163 Mannheim | "The acquisition and holding of shareholdings in software and consulting companies, the management of such holdings and own assets, the acquisition of personal liability and management, and the provision of management services of all kinds to other undertakings of the above mentioned type." |
| osapiens Hub GmbH | HRB 730871, Mannheim (merged into Services GmbH) | Mannheim | Software |
| osapiens AssetOps GmbH | HRB 737875, Mannheim | Mannheim | Software (maintenance/CMMS line) |
| osapiens Terra GmbH | HRB 751216, Mannheim | Mannheim | Software (geospatial line) |
| fTRACE GmbH | subsidiary of the Holding | Germany | Traceability |

**Verification.** The Impressum on osapiens.com names osapiens Services GmbH, Julius-Hatry-Straße 1, 68163 Mannheim, HRB 731132 Amtsgericht Mannheim, VAT DE319253948, managing directors Alberto Zamora, Stefan Wawrzinek, Matthias Jungblut. This matches the Handelsregister entry exactly. The registered purpose is software development, **not** a sales-and-distribution shell, so engineering employment through this entity is credible. Job postings are permanent full-time German contracts ("Permanent - Full Time") with a German Jobticket benefit confirmed in reviews, i.e. direct employment, not PEO/EOR. Note that Indeed lists a second Mannheim address (Glücksteinallee 69); the Handelsregister and Impressum both give Julius-Hatry-Str. 1 as the registered seat.

The Munich office is not a separate registered entity; it operates as a branch site of the Mannheim entities. Note that osapiens Holding GmbH was originally registered in Munich (as Blitz 18-387 GmbH, HRB 239744 Amtsgericht München) before moving its seat to Mannheim in 2018, so the Munich register entry is historical, not a live local entity.

**Verdict:** **PASS** - genuine German operating entity with a software-development corporate purpose and direct German employment contracts.

---

## Section 3: Office Location

- **Munich office address:** Herzog-Wilhelm-Straße 26, 80331 München (Altstadt-Lehel / Sendlinger Tor). Confirmed from the structured location field of the osapiens careers API for posting "Machine Learning Engineer (m/f/x) - Geospatial AI" (location id 45082: city München, postal code 80331, street Herzog-Wilhelm-Strasse 26). Job text describes it as "our Munich office near Sendlinger Tor".
- **German HQ address:** Julius-Hatry-Straße 1, 68163 Mannheim (location id 45081 on all Mannheim postings).
- **Nearest public transit (Munich):** Sendlinger Tor (U1, U2, U3, U6, U7, U8; tram 16, 17, 18, 27, 28). Walk from Sendlinger Tor to the office is ~270 m.
- **Work model:** Hybrid. Every Munich posting is marked "Hybrid" in the ATS. Mannheim engineering postings state the hybrid model explicitly: **"three days a week in the office"**. Two Mannheim infrastructure roles (Senior Linux Platform Engineer, Senior Linux System Engineer) are marked **Onsite**. Kununu benefit data confirms home office is reported by 77% of reviewers and flexible hours by 71%. One Kununu review complains of "very oldish management style (visiting the office when most of workers prefer more work life balance than visit 3 times or more in some cases)", which corroborates a firm 3-day expectation.

---

## Section 4: Reviews

### Great Place to Work

**No GPTW certification found** for osapiens in Germany. Searches of GPTW Germany listings and osapiens' own newsroom and awards pages return no GPTW certification or "Beste Arbeitgeber" placement. osapiens' awards are business awards, not workplace awards: Deutscher Gründerpreis 2022 ("Aufsteiger" / Rising Star category), Mexi Award 2019 (Mannheimer Existenzgründungspreis), and a TÜV Rheinland certification of its Corporate Carbon Footprint methodology (a product certification, not an employer one). **Absent signal.**

### Glassdoor

Retrieved via **Playwright over CDP** (the logged-in Chromium session); the plain WebFetch and curl paths returned Glassdoor's 404 shell for the English slug. Canonical page: `glassdoor.de/Bewertungen/osapiens-Bewertungen-E5162328.htm`.

| Metric | Global | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | 3,1 (42 reviews) | 3,1 (42 reviews; effectively all reviews are German-site) | UNVERIFIED (8 reviews tagged München) | UNVERIFIED (2 tagged "Senior Software Engineer", 2 "Software Engineer", 2 "Software Development Engineer", 4 "Software Developer", 2 "Full Stack Developer", 2 "Junior Software Engineer") |
| **WLB** | 2,9 | 2,9 | n/a | n/a |
| **Culture & Values** | 3,0 | 3,0 | n/a | n/a |
| **Comp & Benefits** | 3,1 | 3,1 | n/a | n/a |
| **Career Opportunities** | 2,9 | 2,9 | n/a | n/a |
| **Senior Management** | 2,8 | 2,8 | n/a | n/a |
| **Diversity & Inclusion** | 3,3 | 3,3 | n/a | n/a |
| **% Recommend** | 43% | 43% | n/a | n/a |
| **CEO Approval** | 54% | 54% | n/a | n/a |
| **Business Outlook** | 49% positive | 49% positive | n/a | n/a |

Notes and caveats:

- osapiens is a **single Glassdoor profile** (E5162328); the "osapiens" and "osapiens Services" URLs resolve to the same employer. Earlier cached search snippets showing 3,2 / 26 reviews and 3,6 / 23 reviews are stale.
- Glassdoor's own FAQ block on the page cites **86 reviews** for the recommend/overall figures while the review list header says **42**. The discrepancy is Glassdoor counting all review types (employer + interview + salary contributions) versus employer reviews only. Either way the sample is small; treat the sub-scores as directional.
- Munich has only **8** location-tagged reviews and Mannheim **21**, so no reliable city split exists. Note that Munich is predominantly a sales and go-to-market site, so Munich-tagged reviews mostly do not describe engineering.
- **Every single sub-score is below 3,5, and the three that matter most for this search (Senior Management 2,8, WLB 2,9, Career Opportunities 2,9) are the three lowest.**

### Kununu

Retrieved via **Playwright over CDP**. Direct curl to `kununu.com/de/osapiens` returns **HTTP 405** (method/bot rejection), so the fallback chain was needed.

- **Overall score:** **4,4 / 5,0**
- **Recommendation rate (Weiterempfehlung):** **85%** (last 2 years)
- **Total reviews:** **95** since 2021 (employees and applicants combined); 69 culture ratings, 65 salary entries
- **Sub-scores:** Karriere & Gehalt 4,2 · Unternehmenskultur 4,3 · Arbeitsumgebung 4,5 · Vielfalt 4,5
- **Best-rated factor:** Umgang mit älteren Kollegen 4,6 (10 ratings)
- **Worst-rated factor:** **Kommunikation 4,0** (24 ratings)
- **Kununu Top Company:** **NO** badge visible on the profile
- Benefits most confirmed: Homeoffice 77%, flexible hours 71%, employee events 70%

**The 1,3-point gap between Kununu (4,4) and Glassdoor (3,1) is itself a finding.** Kununu's positive reviews cluster around October 2025 and January 2026 and read heavily like onboarding-window and working-student feedback ("The HR team was very friendly during the onboarding session"; "gutes und strukturiertes Onboarding, schneller Hiring prozess"; "Verständnis bei Auszeit (zb. wegen Klausurenphase)"). A Glassdoor review from July 2026 is titled **"You can only silence so many bad reviews..."**. Where a company's two review platforms diverge this sharply, the platform with the negative long-tenure signal (Glassdoor) is the more informative one.

Even inside Kununu's 4,4 average, the free-text negatives are severe:

> "Internationale Mitarbeiter werden 30 % weniger bezahlt als deutsche Mitarbeiter mit genau denselben Erfahrungen und Fähigkeiten. Toxisches Management mit Sündenbock- und Schuldzuweisungsmentalität. Manager schikanieren Mitarbeiter, die berechtigte Bedenken zu irgendwelchen Problemen im Unternehmen äußern. 10-Stunden-Arbeitstag ohne bezahlte Überstunden." (December 2025, updated)

> "Wie er mit Mitarbeitenden umgeht - durch jede Abteilung hinweg. Die hohe Fluktuation schreibt Bände." (January 2026, updated)

> "Beschwerden über Probleme werden ignoriert und manipuliert. Man wird beschuldigt, anstatt dass man Hilfe und Schulungen erhält." (December 2025, updated)

> "Flurfunk oder du erfährst es als Letzter. Auch wenn es um deine eigenen Themen geht." (January 2026, updated)

> "Qualität in der Ausführung wird zum Teil vernachlässigt - was zählt ist 'speed speed speed' und 'did you get it done'." (January 2026)

### Indeed

Retrieved via the Indeed MCP (`de.indeed.com/cmp/Osapiens`). Indeed's German profile for osapiens is **thin and mostly unpopulated**: no overall star rating, no work-life-balance / pay / job-security / management / culture sub-scores, and no salary rows for "Senior Software Engineer" in Germany. No city or job-title breakdown is therefore possible.

| Metric | Global / Germany | Munich | Software Engineers |
|---|---|---|---|
| Overall rating | not published | not published | not published |
| Work-life balance | not published | n/a | n/a |
| Pay and benefits | not published | n/a | n/a |
| Job security and advancement | not published | n/a | n/a |
| Management | not published | n/a | n/a |
| Culture | not published | n/a | n/a |
| **CEO approval** | **41%** | n/a | n/a |
| Salary satisfaction | 9 yes / 3 no | n/a | n/a |
| Salary covers cost of living | 9 yes / 2 no | n/a | n/a |
| Would recommend to a friend | **0 yes / 1 no** | n/a | n/a |
| Interview difficulty | Medium | n/a | n/a |
| Interview experience | Excellent | n/a | n/a |
| Interview process length | ~1 week | n/a | n/a |
| Company size band | 501 to 1,000 | | |

The 41% CEO approval on Indeed is directionally consistent with Glassdoor's 54% and well below what a healthy employer scores. Sample sizes are tiny; treat as directional only.

### Blind / Teamblind

`teamblind.com/company/osapiens` returns **"Page not found"** (fetched via Playwright over CDP). **No Blind coverage.** This is expected: Blind's non-US coverage is sparse and osapiens is a German mid-size SaaS with no significant US engineering presence (New York is a four-person sales and marketing site). **UNAVAILABLE.**

### Review Themes (2023-2026)

**Positives:**

- **Colleagues and immediate teams are consistently praised** across both platforms: "extremely supportive colleagues", "smart, ambitious colleagues", "cooperation within the team", "People are very friendly, collaborative and motivated to move the company forward", "The culture is truly collaborative and international, with people always willing to help and share their knowledge."
- **Genuine mission pull.** Reviewers repeatedly cite "a strong sense of purpose in sustainability" and the growth of the ESG sector as a reason to be there. "Cool products, high-growth, very promising economic future."
- **Heavy, visible AI investment.** Even the harshest 1-star review lists "company invests a lot in AI" as a pro.
- **Nice offices and hardware.** "nice office", "Good people, good offices, nice coffee machine", "sehr schönes Office".
- **Onboarding has improved** and is now described as structured, with a fast hiring process and an internal academy covering the regulations and the product.
- **Flexibility exists on paper and partly in practice:** home office confirmed by 77% of Kununu reviewers, flexible hours by 71%, German Jobticket provided.
- **Ownership from day one** for people who thrive in ambiguity: "The company encourages ownership and initiative from day one, which makes you feel trusted and valued."

**Negatives:**

- **Toxic top-down leadership, named repeatedly and recently.** "CEO yells at people"; "the dictatorship of the co-CEO who exclusively hires yes-men and screams at people regardless of department"; "Employees are shouted at, brought to tears and driven into burnout. Boundaries are not respected. Exemplified by leadership, who rewards managers for this behaviour"; "The company is not being led but rather controlled by the Co-CEO"; "toxische Unternehmenskultur top down". **This appears on both platforms and in at least five separate reviews between December 2025 and July 2026.**
- **Unpaid overtime and weekend pressure.** "unpaid overtime is the norm and there is constant pressure to also work weekends"; "10-Stunden-Arbeitstag ohne bezahlte Überstunden".
- **Micromanagement and a culture of fear.** "wants to be involved in every process, which leads to heavy micromanagement"; "a culture of fear rather than empowerment"; "no union (people are too scared of getting fired to form one)"; "lack of trust in even senior employees".
- **Blame-shifting and no feedback culture.** "processes are left intentionally ambiguous so blame either shifts downwards, across departments, or externally depending on the project"; "management keeps blaming individuals instead of reflecting on their own dysfunctions"; "no employee feedback processes, as feedback is not wanted"; "keine Fehlerkultur"; "Das Management lobt einen nie, ist aber schnell dabei, die Schuld zuzuschieben."
- **Very high attrition, described as self-reinforcing.** "the strategy is to only have 'high performers' but exactly those are leaving in this toxic environment"; "very high fluctuation overall"; "Die hohe Fluktuation schreibt Bände"; "Constant management changes. Senior hires from the outside come in, explain how everything that you've done before was bad and how they will turn things around, but disappear a few months later."
- **No internal mobility, and a loyalty penalty.** "open positions are always for external hires, if you are internal you will be exactly where you started no matter what you accomplish"; "no raises"; "Loyalty tax ... new hires werden besser bezahlt aber halten es meistens nicht lange aus"; Glassdoor Career Opportunities 2,9.
- **Pay below market, plus an alleged nationality pay gap.** "Gehalt deutlich unter Marktwert"; "Poor Benefits and salaries are average"; "The wage are in the mid point but not that attractive when comparing to other SaaS firms in the market"; and the specific allegation that "internationale Mitarbeiter werden 30 % weniger bezahlt als deutsche Mitarbeiter mit genau denselben Erfahrungen und Fähigkeiten". A separate Glassdoor comment alleges the company "preferring to hire German tech leads/managers rather than promote foreign employees".
- **Communication breakdown.** Kununu's own worst-rated factor is Kommunikation (4,0, its lowest); Glassdoor: "Internal communication almost nonexistent"; "Die Kommunikation könnte viel besser sein. Wir werden häufiger von Kollegen über Neuigkeiten informiert als von offiziellen Quellen."
- **Speed over quality, chaotic process.** "absolute chaotic, everything needs to be 'fast' but the quality is usually poor"; "Qualität in der Ausführung wird zum Teil vernachlässigt"; "The work processes are not that transparent and hard to navigate, sometimes they do not exist."
- **Politics and an in-group.** "Everything is political. It's rarely about the performance you deliver but who you are on good terms with"; "Boy's club, almost no women in leadership roles"; "no diversity in leadership roles"; "HR department has no authority to improve any of these conditions".
- **Possible review suppression.** A July 2026 Glassdoor review is titled "You can only silence so many bad reviews...", which combined with the Kununu/Glassdoor divergence and the onboarding-window clustering of Kununu positives is a caution about the reliability of the 4,4 figure.

### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| **Toxic Leadership** | **PRESENT, severe, current, multi-source.** "CEO yells at people" (Glassdoor, 31 Jul 2026); "the dictatorship of the co-CEO who exclusively hires yes-men and screams at people regardless of department" (24 Jul 2026); "Employees are shouted at, brought to tears and driven into burnout. Boundaries are not respected. Exemplified by leadership, who rewards managers for this behaviour" (28 Jul 2026); "Company with lots of potential but toxic leadership ... The company is not being led but rather controlled by the Co-CEO" (9 Jul 2026); "Toxisches Management mit Sündenbock- und Schuldzuweisungsmentalität" (Kununu, Dec 2025); "toxische Unternehmenskultur top down" (Glassdoor, 26 Jul 2026). Glassdoor Senior Management sub-score **2,8**, the company's lowest. |
| **24/7 Work Expectation** | **PRESENT.** "constant pressure to also work weekends" (Jul 2026); "10-Stunden-Arbeitstag" (Dec 2025). Not framed as literal 24/7 on-call, but as sustained overwork with weekend encroachment. |
| **Internal Surveillance** | **NOT FOUND.** No reviewer mentions monitoring software, activity tracking, or badge/keystroke surveillance. The nearest signal is micromanagement by presence ("wants to be involved in every process", office-attendance policing), which is a management-style issue rather than technical surveillance. |
| **Fear-driven Management** | **PRESENT.** "a culture of fear rather than empowerment"; "no union (people are too scared of getting fired to form one)"; "Manager schikanieren Mitarbeiter, die berechtigte Bedenken ... äußern" (managers harass employees who raise legitimate concerns); "no employee feedback processes, as feedback is not wanted". |
| **Communication Breakdown** | **PRESENT.** Kununu's lowest-rated factor is Kommunikation (4,0). "Internal communication almost nonexistent"; "Flurfunk oder du erfährst es als Letzter. Auch wenn es um deine eigenen Themen geht"; "The work processes are not that transparent and hard to navigate, sometimes they do not exist." Partly attributable to headcount doubling, but reviewers in 2026 say it is "only getting worse", not improving. |
| **Unpaid Overtime** | **PRESENT and explicit.** "unpaid overtime is the norm" (Glassdoor, Jul 2026); "10-Stunden-Arbeitstag ohne bezahlte Überstunden" (Kununu, Dec 2025). Two independent platforms, two independent reviewers. |
| **Silent Firings** | **PARTIALLY PRESENT.** No mass-layoff events found (see Section 8), but the pattern described is managed-out attrition rather than announced redundancy: "the strategy is to only have 'high performers' but exactly those are leaving"; "Senior hires from the outside come in ... but disappear a few months later"; "very high fluctuation overall"; "management keeps blaming individuals instead of reflecting on their own dysfunctions". |
| **Work-Life Balance issues** | **PRESENT.** Glassdoor WLB **2,9**. "unnötiger Stress der durch besseres Planen und Kommunizieren absolut vermieden werden kann"; "driven into burnout"; office-attendance friction. Counter-signal: some Kununu reviewers say "I don't feel like anyone is pressured to work above their capacity", suggesting the burden is uneven across teams. |

**Risk level: HIGH.**

This is not (b) ordinary large-company bureaucracy, and it is not credibly (c) localised team-level dysfunction. The negative reports name a **specific individual at the top of the company** (a co-CEO), come from **multiple departments** ("regardless of department", "durch jede Abteilung hinweg"), span **at least three platforms and eight months** (Kununu Dec 2025 and Jan 2026; Glassdoor Jul 2026 x5; Indeed 41% CEO approval), and describe the behaviour as **modelled and rewarded downward** ("Exemplified by leadership, who rewards managers for this behaviour"; "others who mirror this behavior are rewarded"). The trend line is negative: the most recent reviews say "All of these things are only getting worse". This is the systemic-toxicity pattern (a), and it maps directly onto the criteria's hard red flags for toxic leadership, unpaid overtime, and work-life balance.

---

## Section 5: Compensation

### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| Glassdoor DE | Software Engineer | €54K to €67K | €0 | not reported | ~€54K to €67K | 5 |
| Glassdoor DE | Software Development Engineer | €54K to €66K | €0 | not reported | ~€54K to €66K | 6 |
| Glassdoor DE | Software Developer | €55K to €65K | €0 | not reported | ~€55K to €65K | 2 |
| Glassdoor DE | Backend Developer | €55K to €60K | €0 | not reported | ~€55K to €60K | 2 |
| Glassdoor DE | Development Engineer | €50K to €59K | €0 | not reported | ~€50K to €59K | 3 |
| Glassdoor DE | Senior Software Engineer | not separately published (2 salary contributions exist but no band shown) | | | | 2 |
| Glassdoor DE | Sales Representative (for contrast) | €85K to €103K | | commission | ~€85K to €103K | 2 |
| levels.fyi | any | **no company page** (404) | | | | 0 |
| Indeed DE | Senior Software Engineer | **no salary rows returned** | | | | 0 |
| Kununu | (65 salary entries exist behind the Gehaltscheck; no per-title engineering band exposed publicly) | UNVERIFIED | | | | 65 |
| Job postings | all osapiens roles | **compensation not disclosed** (`compensation_visible: false` on all 83 postings in the ATS feed) | | | | 83 |

Munich reference points for a Senior Software Engineer at a large profitable corporate: median ~€85K to €95K base, 75th percentile ~€100K to €110K, 90th percentile ~€120K+ (before equity). osapiens' published engineering bands top out at **€67K**, which sits below even the Munich **25th** percentile for the seniority level.

Caveats: the Glassdoor bands are Germany-wide and therefore Mannheim-weighted (Mannheim's cost base is materially lower than Munich's), the samples are 2 to 6 data points per title, and no Senior-specific band is published. The bands are still consistent enough across six separate titles, and corroborated by free-text reviews ("Gehalt deutlich unter Marktwert", "salaries are average", "not that attractive when comparing to other SaaS firms"), that the conclusion is safe.

### Equity / Stock

- **No employee equity is visible anywhere.** The benefits blocks in all 83 ATS postings list purpose, "room for creativity", hybrid flexibility, events, and a Jobticket. **No VSOP, ESOP, virtual shares, phantom stock, or option pool is mentioned in any posting, on the careers site, or in any review.**
- osapiens is **private and pre-IPO**, valued at ~$1.1B after the January 2026 Series C. Any equity that does exist for senior hires would be illiquid with no announced exit path, and would sit behind three preference stacks (Armira, Goldman Sachs Growth, Decarbonization Partners).
- Glassdoor's Comp & Benefits sub-score is **3,1**, and one reviewer notes "no basic employee benefits are in place".
- Practically: assume **cash-only compensation** unless proven otherwise in an offer.

### Verdict

**BELOW.** The observed engineering band (€50K to €67K, Germany-wide, no equity, no disclosed bonus) is roughly 25% to 40% below the Munich senior bracket for large profitable corporates, and the gap is not offset by equity because none is evident. Reviewers independently confirm below-market pay, a loyalty penalty on internal raises, and an alleged 30% pay differential against non-German employees. Even allowing for Mannheim's lower cost base and the small sample, no plausible reading of this data reaches the target bracket.

---

## Section 6: AI/ML & Tech Stack Fit

### AI Strategy

osapiens' AI investment is **real and multi-stranded**, not marketing veneer. Evidence:

- **Platform AI/NLP.** The Mannheim "AI Engineer" role is a production NLP/LLM role: entity resolution, intelligent search, document understanding, transformer models, prompt engineering, **RAG**, structured output generation, multilingual NLP, Docker-based model packaging and deployment. Minimum 3 years professional AI experience.
- **Geospatial AI / remote sensing.** The Munich role runs **production ML on satellite imagery**: deforestation detection models for EUDR compliance, deep learning on remote-sensing data (SAR, optical, LIDAR), segmentation, classification, change detection, time-series analysis, large-scale distributed data processing. A dedicated legal entity exists for this line (**osapiens Terra GmbH**, HRB 751216).
- **Agentic AI via M&A.** osapiens acquired Berlin-based **Lucent AI** (announced 11 December 2025), an agentic-AI risk-management startup, with full integration into the osapiens HUB and first modules shipping from Q2 2026.
- **Dedicated AI product leadership being hired now:** "Head of AI Product" (Mannheim) to own the interface between "the osapiens AI platform" and the business application teams, including AI cost modelling and usage measurement. This implies an internal AI platform team already exists.
- **AI operations as a function:** "Working Student - AI Operations Engineer" (Mannheim).
- **Publicly funded AI R&D.** NorthData records four German public research grants to osapiens Services GmbH, including **"NeuralPower" (€494,979)**, **"HitchhikeBox" (€438,346)**, an **"AI-based ..." project (€364,668)**, and **"WinOSens" (€262,273, twice)**.
- Marketing positions the whole platform as "the AI-driven osapiens HUB" with 26 solutions, so some of the AI framing is promotional, but the job specs behind it are concrete and production-oriented.

**Assessment: genuine applied AI, weighted toward production ML and LLM application engineering rather than research.** Strong on paper for an AI/ML-leaning senior engineer.

### Tech Stack

Derived from **current job postings** (the osapiens careers ATS feed, 83 live postings, which is the most reliable source here), cross-checked against the **NorthData public-funding record** and **review free-text**. osapiens has no substantial public GitHub organisation or engineering blog, so posting evidence dominates.

| Category | Technologies |
|---|---|
| **Primary language(s)** | **Java** (JavaEE, Spring Framework) for the core HUB backend; **TypeScript / Node.js** with **React** for full-stack product teams (TypeScript is listed as mandatory); **Python** confined to the AI/ML roles; **Bash** for platform work |
| **AI/ML** | PyTorch, TensorFlow, transformer-based NLP models, entity recognition and classification, LLMs, prompt engineering, RAG, structured output generation, Weights & Biases (MLOps), computer vision (segmentation, change detection, time-series), remote-sensing pipelines (SAR / optical / LIDAR), AI-assisted development tooling |
| **Cloud** | **AWS** (named explicitly in the ML Engineer posting); "public cloud environments" and HPC referenced generically elsewhere |
| **Infrastructure** | Linux (Ubuntu), Docker, Ansible (plus Puppet/Chef as alternatives), Infrastructure-as-Code, CI/CD, Grafana, Prometheus, distributed-systems operations (replication, sharding, consistency levels, failover, capacity planning), networking and TLS/load-balancing/firewalling |
| **Data** | **ScyllaDB**, **Apache Cassandra**, **Elasticsearch / OpenSearch**, SQL and NoSQL, large-scale distributed data processing, geospatial data processing libraries |
| **Other** | REST and **GraphQL** APIs, Git, agile squads of 5 to 7 people, multi-tenant SaaS architecture, automated testing |

**Fit note for a Python-first candidate:** osapiens' *product* engineering is **not** Python. The core platform is Java/Spring, the application layer is TypeScript/Node/React. Python appears **only** in the two AI/ML roles (Mannheim AI Engineer, Munich ML Engineer) and the AI-operations working-student role. A Python-primary senior engineer therefore has effectively **one** viable role in the whole company at the right location, and it is not pitched at senior level.

### Current Open Roles

All 83 postings were pulled from the live careers feed (`careers.osapiens.com/postings.json`) on 2026-08-05, so every row below is confirmed active with no expiry date set. Engineering roles in Munich or Germany-relevant locations:

| Role | Division/Team | Level | Key Tech | Link |
|---|---|---|---|---|
| **Machine Learning Engineer (m/f/x) - Geospatial AI** | Geospatial analytics (osapiens Terra) | Mid (not titled Senior) | Python, PyTorch/TensorFlow, W&B, AWS, computer vision, remote sensing | [Munich, Hybrid](https://careers.osapiens.com/en/postings/dfeb8b71-2b14-49e8-a64f-7999296489c3) |
| Senior Software Engineer - Backend (Java) (m/f/x) | Platform / HUB core | Senior | Java, JavaEE, Spring, Cassandra/ScyllaDB, REST, GraphQL, OpenSearch, CI/CD | [Mannheim, Hybrid 3d/wk](https://careers.osapiens.com/en/postings/0596b5c2-3a44-4d13-92fc-5dccb37049ac) |
| Java Backend Engineer (m/f/x) | Platform / HUB core | Mid | Java, Spring | [Mannheim, Hybrid](https://careers.osapiens.com/en/postings/8a458af0-8ab6-404a-ba5e-4ce96932d50f) |
| Software Engineer - Backend (Java) (m/f/x) | Platform / HUB core | Mid | Java, Spring | [Mannheim, Hybrid](https://careers.osapiens.com/en/postings/83e41c0b-4e8c-48d0-b536-55b891adc929) |
| Senior Full-Stack Developer (NodeJS/Typescript) (m/f/x) | Product squads | Senior | TypeScript (mandatory), Node.js, React, REST/GraphQL | [Mannheim, Hybrid 3d/wk](https://careers.osapiens.com/en/postings/35c02674-d498-4448-920f-0bb1953ac0c9) |
| Full-Stack Developer (NodeJS/Typescript) (m/f/x) | Product squads | Mid | TypeScript, Node.js, React | [Mannheim, Hybrid](https://careers.osapiens.com/en/postings/ac97a314-ccdf-472c-b0c9-8cadb83618cf) |
| **AI Engineer (m/f/x)** | AI platform | Mid/Senior (3+ yrs) | Python, transformers, LLMs, RAG, Docker | [Mannheim, Hybrid 3d/wk](https://careers.osapiens.com/en/postings/59293989-d328-4a13-aeec-71f3e95b7cff) |
| Head of AI Product (m/f/x) | AI platform | Head | Product/AI hybrid; requires fluent German | [Mannheim, Hybrid 3d/wk](https://careers.osapiens.com/en/postings/a31c7417-d44f-4c43-bee8-a918b2e736a9) |
| Head of Developer Platform (m/f/x) | Platform / DevRel | Head | SDKs, developer portals; requires fluent German | [Mannheim, Hybrid 3d/wk](https://careers.osapiens.com/en/postings/013bc499-b37c-4ddd-b70b-04ab2bd010c5) |
| Head of Platform Operations (m/f/x) | Platform ops | Head | Platform/SRE leadership | [Mannheim, Hybrid](https://careers.osapiens.com/en/postings/2abc0e9c-74d6-4482-aa71-ef2f31cb7c3e) |
| Senior Linux Platform Engineer (m/f/x) | SysAdmin & Ops | Senior | Linux/Ubuntu, ScyllaDB, Cassandra, OpenSearch, Ansible, Grafana, Prometheus | [Mannheim, **Onsite**](https://careers.osapiens.com/en/postings/aeeca3d1-cf99-46e5-847d-f735b8549bab) |
| Senior Linux System Engineer (m/f/x) | SysAdmin & Ops | Senior | Linux, IaC | [Mannheim, **Onsite**](https://careers.osapiens.com/en/postings/f3616c61-1f67-4ed7-8db7-de1fc46d0efc) |
| Senior Quality Assurance Engineer | QA | Senior | Test automation | [Mannheim, Hybrid](https://careers.osapiens.com/en/postings/3119ae9f-ef9e-4ee2-a7ec-670ce80926ab) |
| Senior Full-Stack Developer (NodeJS/Typescript) | Product squads | Senior | TypeScript, Node.js, React | [Madrid, Hybrid](https://careers.osapiens.com/en/postings/c1cecdf7-848d-48a1-9a4e-93e80077bcfd) |

**Munich, in full:** 13 open roles, of which **exactly one is engineering** (the ML Engineer above). The other 12 are Account Executive x3, Business Development Representative x3, Solution Engineer x4 (pre-sales), Customer Success x2, Team Lead BDR, Demand Generation Lead, and a GTM working student. **Munich is a sales and go-to-market hub with a small geospatial AI team attached, not an engineering centre.**

**No fully remote roles exist anywhere in the company.** All 83 postings are Hybrid or Onsite.

### Verdict

Java/Spring and TypeScript/Node product engineering on AWS with a Cassandra-family and OpenSearch data layer, plus a genuine, separately-funded applied-AI strand: production NLP/LLM/RAG work in Mannheim and production computer vision on satellite imagery in Munich, all applied engineering rather than research. The AI work is legitimately interesting and the geospatial line (deforestation detection at scale for EUDR) is unusually substantive. But for a Python-first senior engineer the fit is narrow: Python exists only in the AI/ML corner of a Java-and-TypeScript company, and the single Python role in Munich is not pitched at senior level. **BORDERLINE on AI/ML content, FAIL on primary-language and level fit for the reachable location.**

---

## Section 7: Language

**English is the working language of engineering.** Evidence:

- All 83 job postings are published in English (the German-language careers toggle exists, but the postings themselves, including Mannheim ones, are English).
- Engineering requirements state **"Excellent communication skills in English (C1). German is a bonus (B1+)"** (Senior Full-Stack) and **"fluent in English (C1+). German skills are a plus"** (ML Engineer, Munich). The Java backend and AI Engineer specs list no German requirement at all.
- Kununu and Glassdoor free text is heavily English-language, written by an international workforce ("The culture is truly collaborative and international").
- Offices in Amsterdam, Madrid, Milan, Paris, London and New York reinforce English as the operating language.

**Exception to note:** the two **Head of** roles (Head of AI Product, Head of Developer Platform) explicitly require **"fluent in both German and English"**. This is consistent with the review complaint that the company prefers "German tech leads/managers" over promoting international staff, and suggests German fluency becomes a gate at leadership level even though it is not one for individual contributors.

**Verdict:** **PASS** for individual-contributor engineering roles. **CONDITIONAL** for any leadership track, where German fluency appears to be a requirement.

---

## Section 8: Stability

### Financial Position

- **Revenue:** not officially disclosed. Company claims ~100% growth in 2025 and 42 consecutive months of >100% YoY ARR growth, with ARR doubling YoY in Q2 2025. Third-party estimate ~$90M for 2025 (GetLatka, **unverified**).
- **Customers:** ~2,400 to 2,500, with 400+ new enterprise customers in H1 2025 alone.
- **Profitability:** **loss-making.** osapiens explicitly declined to comment on profitability in its own 2025 growth release. NorthData's earnings chart for **osapiens Holding GmbH** covers 2022 to 2024 on an axis scaled to **−€15M**, indicating annual losses in the high single-digit to mid-teens millions. The 2024 annual report (Jahresabschluss for FY ending 31/12/2024) was filed on **21 January 2026**; the FY2023 report was filed 22 April 2025.
- **Structure note:** osapiens Services GmbH (the operating and employing entity) has a **profit transfer agreement (Ergebnisabführungsvertrag) with osapiens Holding GmbH**, so all operating results roll up to the holding and the operating entity's own accounts show near-zero standalone earnings. Consolidated group losses therefore sit at the Holding.
- **Cash:** the January 2026 Series C brought in **€85.8M (~$100M)**, on top of the July 2024 Series B of **€110.7M (~$120M)**. Total raised ~$247M. Valuation ~$1.1B.
- **Non-dilutive funding:** four German public research grants totalling **~€1.8M** (NeuralPower €494,979; HitchhikeBox €438,346; an AI-based project €364,668; WinOSens €262,273 recorded twice).
- **Credit rating:** none (private, unrated).

### Financial Runway

Search results: no filed analyst runway estimate or press commentary on burn rate exists for osapiens. NorthData's cash and balance-sheet lines are behind the premium paywall; only the loss-scale axis (−€15M) and the filing dates are visible without a subscription. The model below is therefore **bottom-up and derived**, not observed.

**Bottom-up gross burn** (headcount ~600 as of April 2026, mixed Germany / Spain / Netherlands / Italy / France / UK / US cost base):

| Cost line | Annual estimate |
|---|---|
| Staff (600 employees × ~€95K fully loaded, blended across DE/ES/IT/NL/FR/UK/US) | ~€57M |
| Cloud, infrastructure, satellite imagery and third-party data licensing | ~€6M |
| Sales and marketing non-staff (events incl. network day, demand gen, travel) | ~€7M |
| Offices (Mannheim HQ plus 6 international sites), G&A, legal, audit | ~€6M |
| M&A and integration (Lucent AI, amortised) | ~€3M |
| **Total gross burn** | **~€79M/year** |

**Revenue offset:**

| Revenue source | Est. annual inflow |
|---|---|
| SaaS subscription revenue (ARR, mid-point of the $90M estimate and a more conservative reading) | ~€60M/year |
| German public research grants (NeuralPower, HitchhikeBox, WinOSens, AI project), amortised | ~€0.6M/year |
| **Total revenue offset** | **~€61M/year** |

**Scenario table.** Cash figure used: **~€90M**, being the €85.8M Series C (closed January 2026) plus residual Series B cash and grant inflow, net of the Lucent AI purchase, observed as of the January 2026 funding announcement. This is an estimate; osapiens has not published a cash balance.

| Scenario | Net burn | Cash at hand | Runway | Next round needed by |
|---|---|---|---|---|
| Optimistic (ARR keeps ~100% growth, burn grows slower, approaches breakeven in 2027) | ~€10M/year | €90M | 7+ years | ~2032 or never |
| Base case (growth decelerates to 40 to 60%, burn scales with hiring) | ~€18M/year | €90M | ~5 years | ~2031 |
| Stress (ESG regulatory rollback cuts demand, EU omnibus deregulation bites, growth stalls, burn holds) | ~€35M/year | €90M | ~2.5 years | ~2028 |

**Interpretation:** runway is **not** the concern here. Even the stress case leaves 2.5 years and the base case ~5 years, and the company just raised at unicorn valuation from a BlackRock/Temasek joint venture. The financial risk is not insolvency; it is (a) that the company is **not profitable**, and (b) a genuine **regulatory demand risk**: osapiens' core market is EU sustainability compliance (CSRD, CSDDD, EUDR, LkSG), and the EU's Omnibus simplification package has already delayed and narrowed several of these mandates. One reviewer flags exactly this: "regulations issued by EU can be blocked by the US rules". A large share of osapiens' TAM is created by legislation that is currently being politically renegotiated.

### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| n/a | **No layoff events found** | n/a | TrueUp, press searches, and German-language searches for Entlassungen/Restrukturierung return nothing for osapiens. Headcount has grown continuously (300 in 2023 to ~550 in 2025 to ~600 in April 2026). |

**However:** the absence of announced layoffs is not the absence of churn. Multiple current-employee reviews describe **very high voluntary and managed-out attrition** ("very high fluctuation overall", "Die hohe Fluktuation schreibt Bände", "Senior hires from the outside come in ... but disappear a few months later", "high performers ... are leaving in this toxic environment"). In a company hiring 83 roles at once with ~600 staff, that churn is masked by net growth.

**Verdict:** **CAUTION.** Well-funded with a long runway and no layoff history, but structurally loss-making, dependent on an EU regulatory tailwind that is currently being weakened, and with attrition signals that the headline growth hides.

---

## Section 9: Regulated Industry

osapiens **sells compliance software into regulated processes; it is not itself a regulated entity.** Its products address CSRD, CSDDD, LkSG (German Supply Chain Act), EUDR (deforestation), CBAM, product compliance, and, post-Lucent-AI, financial risk management. Customer sectors include pharmaceuticals and medical products.

Practical engineering impact:

- **No safety-critical certification regime applies.** There is no ISO 26262, EN 50128, FDA/IVDR, or ITAR exposure in the engineering work. The Head of AI Product and platform roles carry no mention of formal safety cases or certification evidence.
- **Enterprise SaaS assurance overhead applies:** multi-tenant isolation, GDPR, customer security questionnaires, and likely ISO 27001 / SOC 2. TÜV Rheinland has certified the Corporate Carbon Footprint *methodology*, which is a product-accuracy certification and does imply audit-traceable calculation logic and documentation discipline in the carbon modules.
- The Lucent AI financial-risk line may pull some future work toward DORA-adjacent expectations if sold to financial institutions, but this is prospective, not current.
- The dominant documentation burden is **regulatory domain complexity** (understanding CSRD/EUDR reporting semantics well enough to model them) rather than **regulatory process burden** on the SDLC. Reviewers describe the opposite of a heavyweight process culture: "everything needs to be 'fast' but the quality is usually poor".

**Verdict:** **PASS** (low regulatory burden on engineering itself).

---

## Section 10: On-Call

- **No on-call, standby, Rufbereitschaft, or 24/7 rotation is mentioned in any of the 83 job postings**, including the Senior Java Backend, Senior Full-Stack, AI Engineer, and Munich ML Engineer roles. This was checked across the full ATS feed text, not just the summaries.
- **Product-nature assessment:** osapiens HUB is a multi-tenant production SaaS with ~2,500 enterprise customers and regulatory reporting deadlines. A platform of that size **must** have a production support rotation somewhere. The likely home for it is the **Mannheim "System Administration & Operations Team"** (Senior Linux Platform Engineer, Senior Linux System Engineer, both marked **Onsite**) and the newly-hired **Head of Platform Operations**, i.e. a separate ops organisation rather than the product squads.
- The **Munich ML Engineer** role is batch geospatial model training and inference over satellite imagery, which is the profile least likely to carry a pager. It does list "deployment, monitoring, and maintenance" of production models, so some production ownership exists, but no rotation is stated.
- **Counter-signal from reviews:** "unpaid overtime is the norm and there is constant pressure to also work weekends". This is not on-call in the formal, compensated sense, but it describes out-of-hours work expectations arriving through culture rather than through a rota, which is arguably worse: an uncompensated version of the same burden.

**Verdict:** **CAUTION (team-dependent).** No formal on-call is advertised for product or ML roles, and dedicated ops roles exist to absorb it, but the reported weekend-work culture means the practical out-of-hours load cannot be assumed to be zero. Would need explicit confirmation in an interview.

---

## Section 11: Interview Process

| Metric | Value |
|---|---|
| Difficulty | **2,8 / 5** (Glassdoor, 29 interview reviews, updated 25 July 2026); Indeed reports "Medium" |
| Positive experience | **24%** (Glassdoor). **55% negative**, 21% neutral. Indeed's much smaller sample reports "Excellent" |
| Average duration | ~1 week (Indeed) |
| Rounds | Not published per-stage on Glassdoor; typical pattern for a company of this size and speed is 3 to 4 |
| How candidates got the interview | 42% online application, 21% other, remainder recruiter/referral |

**Assessment.** Difficulty is **low to moderate** at 2,8/5, and the process is **fast** (roughly a week, corroborated by a Kununu reviewer praising the "schneller Hiring prozess"). It is **not LeetCode-heavy**: the seniority framing in the postings is experience-and-design oriented (scalable distributed systems, architecture ownership, mentoring, product mindset) rather than algorithmic.

The striking number is the **24% positive / 55% negative** experience split. A 55% negative interview experience rate is unusually poor and is roughly the inverse of a healthy company. Combined with the review theme that "open positions are always for external hires" and constant senior churn, the plausible reading is a high-volume, high-speed, low-care recruiting funnel. Note the sample is 29 reviews, so treat the exact percentages as directional.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | **PASS.** Pure B2B SaaS, 26-module multi-tenant platform, registered purpose is software development |
| Not consulting | **PASS with caution.** Engineering roles are genuine product roles, but the holding's registered purpose names "software and consulting companies" and 4 of 13 Munich vacancies are pre-sales Solution Engineer or Consultant titles |
| Profitable | **FAIL.** Loss-making; declined to comment on profitability; NorthData earnings axis to −€15M |
| Employee count | ~550 to 600; growing fast |
| English-speaking | **PASS** for IC engineering (English C1 required, German a bonus). **CONDITIONAL** at leadership level, where German fluency is explicitly required |
| Local entity + engineering contracts | **PASS.** osapiens Services GmbH, HRB 731132 Mannheim, software-development corporate purpose, permanent full-time direct German contracts, no PEO/EOR |
| Location / work model | Munich office near tram 23 / U6. But **no remote roles exist anywhere in the company**, and the reachable engineering roles are in **Mannheim** at 3 days per week on-site |
| Glassdoor | **FAIL. 3,1 / 5** (42 reviews), 43% recommend, 54% CEO approval. Senior Management 2,8, WLB 2,9, Career Opportunities 2,9. |
| Indeed | **Insufficient data.** No published star ratings or sub-scores on the German profile. CEO approval **41%**; 0 of 1 would recommend to a friend |
| Kununu | **4,4 / 5**, 85% recommend, 95 reviews, no Top Company badge. Sharply contradicts Glassdoor; positives cluster in the onboarding window and among working students; severe free-text negatives present even here |
| Salary | **FAIL / BELOW.** Glassdoor DE engineering bands €50K to €67K, no equity found, no bonus disclosed, compensation hidden on all 83 postings. Roughly 25% to 40% below the Munich senior bracket. Reviewers confirm below-market pay and an alleged 30% nationality pay gap |
| AI/ML content | **PASS.** Genuine applied AI: production NLP/LLM/RAG, agentic AI via the Lucent AI acquisition, satellite-imagery deep learning for deforestation detection, a dedicated AI platform team, a Head of AI Product being hired, and ~€1.8M in public AI research grants |
| Computer-language/Tech-stack | **FAIL on Python.** Product engineering is Java/Spring and TypeScript/Node/React. Python appears only in the two AI/ML roles. The one Python role in Munich is not senior-titled |
| No on-call | **CAUTION.** No on-call advertised for product or ML roles; dedicated Linux/platform ops team exists to absorb it. But reviews report weekend-work pressure and unpaid overtime, i.e. out-of-hours load via culture rather than rota |
| WLB / Stability | **FAIL on WLB** (2,9, unpaid overtime, burnout reports). **CAUTION on stability**: no layoffs and 2.5 to 5+ years of runway, but structurally loss-making and exposed to EU deregulation of its own TAM |
| Regulated industry | **PASS.** Sells compliance software but is not itself a regulated entity; no safety-critical certification burden on engineering |
| Review themes | **FAIL.** Toxic leadership named at co-CEO level across multiple departments and platforms (Dec 2025 to Jul 2026), culture of fear, unpaid overtime and weekend pressure, blame-shifting, very high fluctuation, no internal mobility, communication breakdown, and a possible review-suppression signal |
| **No senior engineering role in Munich** | **FAIL.** One engineering vacancy in Munich (mid-level ML Engineer). Munich is a sales and GTM hub with a small geospatial AI team |
| **No remote option** | **FAIL.** All 83 postings are Hybrid or Onsite; zero fully remote roles |
| **Interview experience** | **CAUTION.** 55% negative / 24% positive across 29 Glassdoor interview reviews |

---

## Section 13: Verdict

**Recommendation: EXCLUDE.**

**Strengths.** osapiens is a real company doing real work, and it would be wrong to dismiss it as hype. It is a genuine pure-play B2B SaaS business with ~2,500 enterprise customers, 42 straight months of >100% ARR growth, unicorn status since January 2026, and $247M raised from serious investors (Goldman Sachs Growth Equity, a BlackRock/Temasek JV). Its AI investment is substantive rather than decorative: production NLP/LLM/RAG engineering, an agentic-AI acquisition, a dedicated AI platform team with a Head of AI Product being hired, ~€1.8M in German public AI research grants, and a genuinely interesting geospatial line running deep learning over satellite imagery to detect deforestation at scale for EUDR compliance. The German legal entity is clean and verified: osapiens Services GmbH, HRB 731132 Mannheim, a software-development corporate purpose, direct permanent German contracts, no PEO or EOR games. English is the working language for engineers. And the Munich office is central, at Herzog-Wilhelm-Straße 26 (Sendlinger Tor). Colleagues are praised warmly and consistently on both review platforms.

**Hard blockers (numbered):**

1. **Glassdoor 3,1 / 5 against a 4,0 floor.** 42 reviews, 43% would recommend, 54% CEO approval, 49% positive business outlook. Every sub-score is below 3,5 and the three most relevant to this search are the three lowest: Senior Management **2,8**, Work-Life Balance **2,9**, Career Opportunities **2,9**. Kununu's 4,4 does not rescue it, the Kununu positives cluster in the onboarding window and among working students, and a July 2026 Glassdoor review is literally titled "You can only silence so many bad reviews...".

2. **Repeated toxic-leadership red flags, current and escalating.** The criteria exclude companies with repeated red flags for toxic leadership, 24/7 work culture, and WLB problems. osapiens hits all three, from named current employees, across two platforms, over eight months. Specifically: "CEO yells at people ... heavy micromanagement" (31 Jul 2026); "this is not a flat hierarchy, this is a dictatorship of the co-CEO who exclusively hires yes-men and screams at people regardless of department ... a culture of fear rather than empowerment ... unpaid overtime is the norm and there is constant pressure to also work weekends ... very high fluctuation overall" (24 Jul 2026); "Employees are shouted at, brought to tears and driven into burnout. Boundaries are not respected. Exemplified by leadership, who rewards managers for this behaviour ... All of these things are only getting worse" (28 Jul 2026); "Toxisches Management mit Sündenbock- und Schuldzuweisungsmentalität ... 10-Stunden-Arbeitstag ohne bezahlte Überstunden" (Kununu, Dec 2025). This is systemic and top-down, not localised team dysfunction, and the trend is worsening.

3. **No senior software engineering role in Munich, and none reachable.** Munich has 13 open roles, of which exactly one is engineering: a mid-level Machine Learning Engineer for Geospatial AI. The other 12 are Account Executive, BDR, pre-sales Solution Engineer, and Customer Success. Every backend, full-stack, AI and platform engineering role is in **Mannheim**, roughly 3 hours each way from Munich, with an explicit **3 days per week on-site** requirement. **Zero of the 83 open roles company-wide are fully remote.** With relocation off the table, there is no viable role here.

4. **Compensation roughly 25% to 40% below the Munich senior bracket.** Glassdoor Germany shows Software Engineer €54K to €67K, Software Development Engineer €54K to €66K, Backend Developer €55K to €60K, Development Engineer €50K to €59K. The top of the entire published engineering range, €67K, sits below the Munich **25th** percentile for a senior. **No equity of any kind is visible** in any of the 83 postings, on the careers site, or in any review, so there is no offsetting upside, and the company is private and pre-IPO with three preference stacks ahead of any employee shares that might exist. Compensation is hidden on all 83 postings (`compensation_visible: false`). Reviewers independently confirm: "Gehalt deutlich unter Marktwert", "salaries are average", "not that attractive when comparing to other SaaS firms", plus an allegation that "internationale Mitarbeiter werden 30 % weniger bezahlt als deutsche Mitarbeiter mit genau denselben Erfahrungen und Fähigkeiten".

5. **Not a profitable, post-exit employer.** osapiens is a loss-making, VC-backed Series C company that explicitly declined to comment on profitability, with NorthData showing holding-level losses on an axis scaled to −€15M.

6. **Python is not the primary language.** The product stack is Java/Spring for the core HUB and TypeScript/Node/React for the application layer. Python is confined to the AI/ML corner, and the sole Python role in the reachable location is not pitched at senior level.

**Secondary concerns.** The interview experience is 55% negative against 24% positive across 29 reviews, an unusually poor split. There is no Great Place to Work certification and no Kununu Top Company badge. Career progression is reported as effectively closed to internal candidates ("open positions are always for external hires ... you will be exactly where you started no matter what you accomplish"; "no raises"; "Loyalty tax"), with a specific complaint that the company "prefer[s] to hire German tech leads/managers rather than promote foreign employees" and that both Head-of roles currently open require fluent German. Communication is Kununu's own worst-rated factor. On-call is not advertised but weekend-work pressure is reported, so the practical out-of-hours load is unknown. And there is a structural business risk worth naming: osapiens' TAM is manufactured by EU sustainability legislation (CSRD, CSDDD, EUDR, LkSG) that the EU's Omnibus simplification package is actively delaying and narrowing, a risk one reviewer raises directly.

**Recommendation.** Do not apply, and no further research is warranted. Six hard criteria fail simultaneously, and they are not the kind that resolve with a good recruiter conversation: the location mismatch is structural (Munich is a sales site, engineering is in Mannheim at 3 days on-site, nothing is remote), the compensation gap is too wide to negotiate across, and the leadership-culture evidence is recent, specific, corroborated across platforms, attributed to a named seat at the top of the company, and explicitly described by current employees as getting worse. Were the culture signal clean, the geospatial AI work in Munich would still be worth a look despite the level and pay mismatch; it is not clean. Revisit only if all of the following change together: a Senior or Staff engineering role opens in Munich, the Glassdoor rating recovers above 4,0 on a meaningful volume of post-change reviews, and there is public evidence of a leadership change at co-CEO level.

---

## Sources

- [osapiens - company site](https://osapiens.com/)
- [osapiens - Imprint / Impressum](https://osapiens.com/imprint/)
- [osapiens - Careers](https://osapiens.com/career/)
- [osapiens - Careers portal](https://careers.osapiens.com/)
- [osapiens - live job postings feed (83 postings, retrieved 2026-08-05)](https://careers.osapiens.com/postings.json)
- [osapiens - Machine Learning Engineer (m/f/x) Geospatial AI, Munich](https://careers.osapiens.com/en/postings/dfeb8b71-2b14-49e8-a64f-7999296489c3)
- [osapiens - Senior Software Engineer Backend (Java), Mannheim](https://careers.osapiens.com/en/postings/0596b5c2-3a44-4d13-92fc-5dccb37049ac)
- [osapiens - Senior Full-Stack Developer (NodeJS/TypeScript), Mannheim](https://careers.osapiens.com/en/postings/35c02674-d498-4448-920f-0bb1953ac0c9)
- [osapiens - AI Engineer, Mannheim](https://careers.osapiens.com/en/postings/59293989-d328-4a13-aeec-71f3e95b7cff)
- [osapiens - Head of AI Product, Mannheim](https://careers.osapiens.com/en/postings/a31c7417-d44f-4c43-bee8-a918b2e736a9)
- [osapiens - Head of Developer Platform, Mannheim](https://careers.osapiens.com/en/postings/013bc499-b37c-4ddd-b70b-04ab2bd010c5)
- [osapiens - Senior Linux Platform Engineer, Mannheim](https://careers.osapiens.com/en/postings/aeeca3d1-cf99-46e5-847d-f735b8549bab)
- [osapiens - Working Student Tech Sales & GTM, Munich](https://careers.osapiens.com/postings/268b1f7c-b794-4304-aa30-238e84802bfc)
- [NorthData - osapiens Holding GmbH, HRB 731130 Mannheim](https://www.northdata.com/osapiens+Holding+GmbH,+Mannheim/HRB+731130)
- [NorthData - osapiens Services GmbH, HRB 731132 Mannheim](https://www.northdata.com/osapiens%20Services%20GmbH,%20Mannheim/HRB%20731132)
- [NorthData - osapiens Hub GmbH, HRB 730871 Mannheim](https://www.northdata.com/osapiens%20Hub%20GmbH,%20Mannheim/HRB%20730871)
- [NorthData - osapiens AssetOps GmbH, HRB 737875 Mannheim](https://www.northdata.com/osapiens%20AssetOps%20GmbH,%20Mannheim/HRB%20737875)
- [NorthData - osapiens Terra GmbH, HRB 751216 Mannheim](https://www.northdata.com/osapiens%20Terra%20GmbH,%20Mannheim/HRB%20751216)
- [Webvalid - osapiens Holding GmbH, HRB 731130](https://www.webvalid.de/company/osapiens+Holding+GmbH,+Mannheim/HRB+731130)
- [Webvalid - osapiens Services GmbH, HRB 731132](https://www.webvalid.de/company/osapiens+Services+GmbH,+Mannheim/HRB+731132)
- [Creditreform - osapiens Holding GmbH](https://firmeneintrag.creditreform.de/68163/8171159347/OSAPIENS_HOLDING_GMBH)
- [Creditreform - osapiens Services GmbH](https://firmeneintrag.creditreform.de/68163/7170392850/OSAPIENS_SERVICES_GMBH)
- [Glassdoor - osapiens overview (E5162328)](https://www.glassdoor.com/Overview/Working-at-osapiens-Services-EI_IE5162328.11,28.htm)
- [Glassdoor DE - osapiens reviews, sorted most recent](https://www.glassdoor.de/Bewertungen/osapiens-Bewertungen-E5162328.htm?sort.sortType=RD&sort.ascending=false)
- [Glassdoor DE - osapiens salaries](https://www.glassdoor.de/Gehalt/osapiens-Geh%C3%A4lter-E5162328.htm)
- [Glassdoor DE - osapiens interviews](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/osapiens-Fragen-im-Vorstellungsgespr%C3%A4ch-E5162328.htm)
- [Glassdoor - osapiens jobs](https://www.glassdoor.com/Jobs/osapiens-Jobs-E5162328.htm)
- [Kununu - osapiens](https://www.kununu.com/de/osapiens)
- [Indeed - osapiens company page (DE)](https://de.indeed.com/cmp/Osapiens)
- [Teamblind - osapiens (page not found)](https://www.teamblind.com/company/osapiens)
- [levels.fyi - osapiens (404, no company page)](https://www.levels.fyi/companies/osapiens/salaries)
- [EU-Startups - osapiens raises €110.7M Series B (July 2024)](https://www.eu-startups.com/2024/07/mannheim-based-osapiens-raises-e110-7-million-series-b-to-help-companies-navigate-esg-regulation/)
- [EU-Startups - New German unicorn: osapiens secures €85.8M led by BlackRock-Temasek JV (January 2026)](https://www.eu-startups.com/2026/01/new-german-unicorn-mannheims-osapiens-secures-e85-8m-led-by-blackrock-temasek-jv/)
- [BusinessWire - osapiens raises $120M led by Growth Equity at Goldman Sachs Alternatives](https://www.businesswire.com/news/home/20240729535470/en/osapiens-raises-120-million-funding-round-led-by-Growth-Equity-at-Goldman-Sachs-Alternatives)
- [osapiens - Germany's first unicorn of 2026 (Handelsblatt coverage)](https://osapiens.com/external-news/osapiens-einhorn-handelsblatt-2/)
- [osapiens - continues hypergrowth: over 100% YoY growth](https://osapiens.com/company-news/osapiens-continues-hypergrowth/)
- [osapiens - acquires Lucent AI (December 2025)](https://osapiens.com/company-news/osapiens-acquires-lucent-ai/)
- [ESG Today - osapiens acquires risk management tech startup Lucent AI](https://www.esgtoday.com/sustainability-solutions-provider-osapiens-acquires-risk-management-tech-startup-lucent-ai/)
- [FinTech Global - Osapiens buys Lucent AI to expand compliance automation](https://fintech.global/2025/12/15/osapiens-buys-lucent-ai-to-expand-compliance-automation/)
- [Crunchbase - osapiens](https://www.crunchbase.com/organization/osapiens)
- [PitchBook - osapiens company profile](https://pitchbook.com/profiles/company/460206-64)
- [Tracxn - osapiens company profile, funding, financials](https://tracxn.com/d/companies/osapiens/__IP-82BqPyWa1UtplAQO9AC06TIixjqGqFqMPEMd3krg)
- [Dealroom - osapiens unicorn profile](https://dealroom.co/companies/osapiens/)
- [CB Insights - osapiens financials](https://www.cbinsights.com/company/osapiens/financials)
- [GetLatka - osapiens revenue estimate](https://getlatka.com/companies/osapiens.com)
- [Growjo - osapiens revenue and headcount](https://growjo.com/company/osapiens)
- [Owler - osapiens company profile](https://www.owler.com/company/osapiens)
- [Built In - osapiens careers, perks and culture](https://builtin.com/company/osapiens)
- [osapiens newsroom - about](https://news.osapiens.com/about/?locale=en)
- [osapiens - TÜV Rheinland certifies Corporate Carbon Footprint methodology](https://osapiens.com/company-news/tuev-rheinland-ccf-osapiens/)
- [osapiens - EUDR solution](https://osapiens.com/solutions/eudr/)
- [Great Place to Work - certification directory (no osapiens entry found)](https://www.greatplacetowork.com/solutions/certification/europe)

---

## Retrieval Notes

- **WebFetch** succeeded for: osapiens Impressum, NorthData osapiens Services GmbH (partial), osapiens contact page.
- **curl with browser User-Agent** was required for: the osapiens careers ATS feed (`postings.json`, 83 postings with structured location, workplace type, and compensation-visibility fields).
- **Playwright over CDP** (persistent logged-in Chromium at `localhost:9222`) was required for: **Kununu** (direct curl returns HTTP 405), **Glassdoor** overview, reviews, salaries and interviews (WebFetch and the English slug return Glassdoor's 404 shell), **NorthData** full pages (cookie consent wall), **Teamblind** and **levels.fyi** (both confirmed as having no osapiens page).
- **Indeed MCP** returned a sparse German profile for osapiens: no star ratings, no sub-scores, no salary rows for Senior Software Engineer.
