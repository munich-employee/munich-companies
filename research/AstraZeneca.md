# AstraZeneca - Full Research Report

_Researched: 2026-08-05_

> **Note: no critical disqualifier found, but two live uncertainties dominate this evaluation.**
> 1. **Merger talks with Bristol Myers Squibb were reported by the Financial Times on 2 August 2026**, three days before this research, valuing a combined company at ~$400bn. AstraZeneca shares fell up to 7%. Neither company has confirmed. This is an unresolved structural risk to any offer signed in the next 12 to 24 months.
> 2. **Compensation for a Senior Software Engineer in Germany could not be verified from any source.** Glassdoor Germany has 188 salary submissions across 121 job titles and **not one software engineering title**; levels.fyi has insufficient German data and its global AstraZeneca software engineering data is India-only.
>
> Everything else lands positively or neutrally. The full report follows.

---

## Section 1: Company Fundamentals

| Criterion | Status |
|---|---|
| Founded | 1999 (27 years) via the merger of Astra AB (Sweden, 1913) and Zeneca Group plc (UK, 1993). Indeed lists the foundation year as 1913 following the Astra lineage |
| Employees | ~90,000 globally across 85+ countries. **~1,200 in Germany** (company statement on its Kununu profile) |
| Revenue (FY2025) | **$58.7bn**, +8% YoY at constant exchange rates. Oncology alone was $25.6bn (44% of total, +14%) |
| Profitability | **$10.2bn net income (FY2025)**; Core EPS $9.16, +11%. Highly and consistently profitable - **PASS** |
| Ownership | **Public.** LSE: AZN, NASDAQ: AZN, OMX Stockholm: AZN. ~$230bn to $250bn market capitalisation. No controlling shareholder |
| Software-centric | **FAIL as a company, PASS for the specific site.** AstraZeneca is a biopharmaceutical company, not a software company. However, the Munich site is a dedicated AI/software engineering unit (see below) with its own software-purpose legal entity - **BORDERLINE overall** |

### Key People

- **Pascal Soriot**, CEO since 2012. Glassdoor CEO approval **89%** globally, **99%** among German reviewers, **68%** on Indeed.
- **Aradhana Sarin**, CFO.
- **Susan Galbraith**, EVP Oncology R&D (the organisation the Munich Computational Pathology team reports into).
- **Alexandra Bishop**, Geschäftsführerin AstraZeneca Deutschland (named on the German Kununu profile).
- Managing directors of the Munich entity per the commercial register: **Nihad Bajraktarević, Hadassah Sumum Sade, Birgit M. H. Hofauer**.

### Funding History

Not applicable. AstraZeneca has been publicly listed since 1999 and is self-funding. Net debt was **$23.374bn** at 31 December 2025, down $1.196bn over twelve months. S&P rates the company **A+**; the company states it targets a strong investment-grade rating and holds solicited ratings from both Moody's and S&P.

### Software-Centric Assessment

AstraZeneca is a pharmaceutical manufacturer: revenue comes from prescription medicines, not from software licences. On a literal reading, the software-centric criterion **fails**. However:

- The Munich site is **"Computational Pathology Munich"**, formed from AstraZeneca's 2018/2019 acquisition of **Definiens AG**, a Munich digital-pathology software company. The legal entity was renamed from Definiens GmbH to **AstraZeneca Computational Pathology GmbH** by shareholder resolution on 29 July 2020.
- That entity's registered corporate purpose is **"Development and use of AI-enabled research, software and services to support and accelerate drug development"** - an explicitly software purpose, not a sales or distribution purpose.
- The role in question builds **Software as a Medical Device (SaMD)**: regulated, shippable AI-enabled diagnostic software subject to FDA, EMA and IVDR submissions. This is product software engineering, not internal IT tooling.
- Group-level, AstraZeneca also owns **Evinova**, a standalone health-tech subsidiary selling an AI-native clinical development platform commercially to other pharma companies (Astellas and Bristol Myers Squibb signed on in February 2026).

So: the parent is not a software company, but the specific Munich unit is a software engineering organisation with a software-purpose legal entity building a regulated software product. Treat this as **BORDERLINE, resolved favourably at site level**.

### Consulting-Adjacency Assessment

**Not consulting.** AstraZeneca does not self-identify as a consultancy, engineers do not bill hours to clients, and the Munich engineering roles build an internal-then-commercial product (regulated computational pathology software), not a client deliverable. The registered purpose of the Munich entity is software development, and the German commercial entity's purpose is "development, manufacture and distribution of chemical-pharmaceutical products".

One caveat on titles: Glassdoor's interview data shows **"Senior Consultant" (85 interviews)** and **"Consultant" (83)** among AstraZeneca's most-interviewed job titles globally. These are internal advisory and IT-consulting functions within a 90,000-person organisation, not a client-billing consultancy model, and none of them appear among the current German or Munich vacancies. **PASS.**

---

## Section 2: Local Commercial Entity in Germany

| Entity | Registration | Address | Purpose |
|---|---|---|---|
| **AstraZeneca Computational Pathology GmbH** (the Munich engineering entity, ex-Definiens) | **HRB 251893, Amtsgericht München** (EUID DED2601V.HRB251893; previously HRB 133088 München as Definiens AG) | **Landsberger Str. 300, 80687 München** (previously Bernhard-Wicki-Str. 5, 80636 München) | **"Development and use of AI-enabled research, software and services to support and accelerate drug development."** |
| AstraZeneca GmbH (German commercial entity) | **HRB 175066, Amtsgericht Hamburg** (previously HRB 5069 PI, Amtsgericht Pinneberg, when seated in Wedel) | Friesenweg 26, 22763 Hamburg-Bahrenfeld | "The object of the company is the development, manufacture and distribution of chemical-pharmaceutical products, in particular under the internationally registered trademarks 'Astra', 'Zeneca' and 'AstraZeneca'." |
| AstraZeneca Holding GmbH | German holding company | Germany | Holds AstraZeneca GmbH; a profit transfer agreement (Ergebnisabführungsvertrag) exists between them |
| AstraZeneca Vertriebs GmbH | HRB 1544 PI, Amtsgericht Pinneberg | Wedel | Distribution |
| Alexion Pharma Germany GmbH | Munich | München | Rare disease commercial arm (AstraZeneca acquired Alexion in 2021); carries a separate careers-site ID (43991) and its own Munich vacancies, all commercial |

**Verification.** The Munich entity is the important one and it verifies cleanly. Its registered corporate purpose names **AI-enabled research, software and services** explicitly. This is not a sales shell: it is the legal successor to a Munich software company (Definiens AG, founded 2000, capital €14M at its peak), renamed rather than dissolved, still registered at Amtsgericht München under HRB 251893, and still at a Munich address. NorthData shows the entity filing accounts through 2024 with a revenue line in the low single-digit millions of euros, consistent with an internal R&D cost centre that recharges to the group rather than selling externally.

Engineering staff at the Munich site are employed on **German contracts through a German GmbH**. The job postings are marked "Munich, Bavaria, Germany" with a German work location and use the German "(m/f/d)" convention, and the benefits described (childcare support, German office site) are direct-employment benefits. **No PEO or EOR arrangement is indicated anywhere.** AstraZeneca does not use employer-of-record structures in Germany; it has run a German legal presence continuously since the Astra era and employs ~1,200 people locally.

One structural note: the Hamburg entity's registered purpose covers "development, manufacture and distribution of chemical-pharmaceutical products" and would, on its own, read as a commercial and manufacturing purpose rather than a software one. The software-purpose entity is specifically the Munich one, which is exactly where the role sits.

**Verdict:** **PASS.** Verified German software-purpose GmbH in Munich with a real corporate history, direct German employment, and no intermediary.

---

## Section 3: Office Location

- **Munich office address:** **Landsberger Straße 300, 80687 München** (Laim). Confirmed via the Handelsregister entry for HRB 251893 and multiple German company registries; the older Bernhard-Wicki-Str. 5, 80636 address is superseded.
- **Nearest public transit:** **S-Bahn Laim** (S1, S2, S3, S4, S6, S8) is the practical station, roughly **220 m** walk. Also within ~700 m per OpenStreetMap/Overpass: tram stops **Agnes-Bernauer-Platz** (tram 19) and **Fürstenrieder Straße**.
- **Work model:** **Hybrid.** The Munich posting promises "Modern office space in Munich enabling collaborative, flexible, and agile work" and describes an on-site culture (after-work events, lunch and learns, a "spacious and sustainable office working environment", family and childcare support) without stating a day count. AstraZeneca's published global policy for office-based roles is a **minimum of three days per week in the office**. Kununu benefit data for the German entity shows flexible working hours confirmed by 69% of reviewers. **Assume three days per week on-site unless negotiated otherwise; verify in interview.**

---

## Section 4: Reviews

### Great Place to Work

**Mixed and partly unverified for Germany specifically.**

- AstraZeneca holds a **Great Place to Work certification** at group level and in several individual countries (Switzerland has been certified five times as of 2023; strong Middle East and North Africa placements in 2024). Its Indeed employer profile states "We're dedicated to being a Great Place to Work."
- The German Kununu profile describes an internal **"Great Place to Work programme"** and repeatedly references it, but a **Great Place to Work Germany certification for AstraZeneca GmbH could not be verified** in the GPTW Germany listings. Treat the German GPTW status as **UNVERIFIED**.
- What **is** verified for Germany: **Top Employer Germany certification (2024)**, plus a Top Employer Europe recognition the same year, awarded by the Top Employers Institute across training and development, company culture, career development, compensation and benefits, and diversity and inclusion. This is a genuine third-party HR certification, roughly equivalent in signal weight to a Kununu Top Company award.
- AstraZeneca also appears on **Glassdoor's Best Places to Work** list for 2026.
- **Kununu Top Company badge: YES** (confirmed present on the German profile, alongside an Open Company badge).

Net: the positive-employer signal for Germany is real and third-party verified, just via Top Employer rather than GPTW Germany.

### Glassdoor

Retrieved via **Playwright over CDP** (logged-in Chromium session). The glassdoor.com URLs redirect to the German locale for this session; the working canonical is `glassdoor.de/Bewertungen/AstraZeneca-Bewertungen-E9214.htm`.

| Metric | Global | Germany | Munich | Software Engineers |
|---|---|---|---|---|
| **Overall** | **4,0** (8.018 reviews) | **4,0** (21 reviews) | **4,6** (2 reviews) | **no reviews (0)** |
| **WLB** | 3,8 | see note | n/a | n/a |
| **Culture & Values** | 3,9 | 3,9 | 4,4 | n/a |
| **Comp & Benefits** | 4,0 | **4,4** | n/a | n/a |
| **Career Opportunities** | 3,7 | see note | n/a | n/a |
| **Diversity & Inclusion** | 4,1 | 4,1 | 4,9 | n/a |
| **Senior Management** | **3,5** | see note | n/a | n/a |
| **% Recommend** | **78%** | **77%** | 70% | n/a |
| **CEO Approval** | **89%** | **99%** | 100% | n/a |
| **Business Outlook** | **78%** positive | 77% positive | 98% positive | n/a |

Notes and caveats:

- **The global figure is good.** 8.018 reviews is a large, statistically meaningful sample, so 4,0 is a solid rather than fragile reading.
- **Germany (21 reviews) is below the 20-review reliability line only marginally and should be treated as directional.** It matches the global 4,0 and shows a *higher* compensation score (4,4) than the global average, which is a useful signal given that German salary data was otherwise unobtainable.
- **Munich (2 reviews) is not usable.** 4,6 from two reviews carries no weight. One of the two is visible and is a July 2026 five-star review from an Associate Director in Munich: "Gutes Team ... Interessante, sinnvolle, spannende Arbeit ... Zentral in München ... Kluge Menschen", with the negatives "Viel Arbeit. Viel Veränderung."
- **Software Engineer filter returns literally zero reviews.** AstraZeneca has no Glassdoor review coverage under that job title anywhere in the world. The nearest engineering-adjacent title in the interview data is "Engineer" (68 interviews). There is therefore **no engineer-specific Glassdoor signal for this company at all**.
- Sub-scores render identically on the global and filtered views for some categories, so where a filtered sub-score could not be independently confirmed it is marked "see note" rather than guessed.
- **Senior Management at 3,5 is the weakest global sub-score**, half a point below the overall rating. This is the single consistent soft spot across every platform.

### Kununu

Retrieved via **Playwright over CDP**. Direct curl returns **HTTP 405**. The slug `astrazeneca` 404s; the correct slug is **`astra-zeneca`** (found by searching kununu through the browser session). The profile covers **AstraZeneca GmbH** (the German commercial entity, Hamburg/Wedel), not the Munich software entity separately.

- **Overall score:** **3,6 / 5,0**, marked **"Aufwärtstrend"** (improving trend)
- **Recommendation rate (Weiterempfehlung):** **83%** (last 2 years)
- **Total reviews:** **358** since 2008, of which **252 employee reviews** and **106 applicant reviews**
- **Employee-only sub-profile:** score **3,8**, recommendation **74%**
- **Sub-scores:** Karriere & Gehalt 3,8 · Unternehmenskultur 3,7 · Arbeitsumgebung 4,0 · Vielfalt 3,9
- **Kununu Top Company:** **YES** (plus Open Company badge)
- Benefits most confirmed by 252 reviewers: company phone 73%, occupational pension (betriebliche Altersvorsorge) 72%, flexible hours 69%
- Industry context: 3,6 is above the Medizin/Pharma sector average of 3,5

**Notable:** AstraZeneca's Talent Acquisition team **responds publicly to essentially every review**, including the critical ones, and the responses are substantive rather than boilerplate (acknowledging specific criticisms about hierarchy, communication and diversity, and offering direct HR contact). That is an unusually engaged employer-brand posture and a mild positive signal in itself.

A **July 2026 review from an employee in Forschung / Entwicklung at AstraZeneca GmbH in München** rates the company **4,0 "Fairer Arbeitgeber"**, satisfied with working atmosphere, colleague cohesion and interesting tasks, with work-life balance flagged as the improvement area. This is the only Munich R&D-side review found on any platform.

### Indeed

Retrieved via the **Indeed MCP** (`de.indeed.com/cmp/Astrazeneca`). Indeed's German profile does **not publish** the five standard sub-scores (work-life balance, pay and benefits, job security and advancement, management, culture) or an overall star rating for the German entity, so no country, city or job-title breakdown is possible from this source.

| Metric | Global / Germany | Munich | Software Engineers |
|---|---|---|---|
| Overall rating | not published on the DE profile | n/a | n/a |
| Work-life balance | not published | n/a | n/a |
| Pay and benefits | not published | n/a | n/a |
| Job security and advancement | not published | n/a | n/a |
| Management | not published | n/a | n/a |
| Culture | not published | n/a | n/a |
| **Would recommend to a friend** | **771 yes / 288 no = 73%** | n/a | n/a |
| **CEO approval** | **68%** | n/a | n/a |
| Salary satisfaction | 15 yes / 4 no (79%) | n/a | n/a |
| Salary covers cost of living | 3 yes / 0 no | n/a | n/a |
| Interview difficulty | **Medium** | n/a | n/a |
| Interview experience | **Average** | n/a | n/a |
| Interview process length | **~1 month** | n/a | n/a |
| Company size / revenue bands | 10,000+ employees; more than $10bn revenue | | |
| Sector | Pharmaceutical & Biotechnology | | |

The 73% recommend rate on ~1,059 responses is consistent with Glassdoor's 78%, and both are in healthy territory for a company this size. **No salary rows were returned for "Senior Software Engineer" in Germany.**

### Blind / Teamblind

Retrieved via **Playwright over CDP** (the page is behind a consent wall for plain fetching).

- **Overall: 3.7 (47 reviews)**
- **Work Life Balance: 3.9** (the strongest sub-score)
- **Compensation / Benefits: 3.4**
- **Company Culture: 3.4**
- **Career Growth: 3.3**
- **Management: 3.0** (the weakest, matching the Glassdoor pattern)
- Listed salary range: $45K to $250K/year; a headline total compensation figure of **US$158,000** is shown, which is US-weighted and not transferable to Germany.

Blind's coverage is 47 reviews and skews to US tech and data roles, so treat as directional. The most-surfaced review is from a **Software Analyst Developer, current employee, March 2025**, rating **2.0**: pros "Promising Pipeline, Flexibility at Work, Multinational, Good office space, A lot to do"; cons "**Poor Leadership, Toxic Mid level Management, Poor Systems and Processes, High Burnout, No career growth, Low Pay, Cheap Labor, No long term strategy**". Blind's AstraZeneca discussion board also carries active Interview, Layoffs, Culture and WLB threads.

### Review Themes (2023-2026)

**Positives:**

- **Compensation and benefits are consistently rated well**, and unusually, better in Germany than globally: Glassdoor Comp & Benefits **4,4 in Germany** versus 4,0 globally. UK reviewers cite "Strong compensation and benefits. Good pension, bonus and car scheme." Indeed salary satisfaction runs 79%.
- **Benefits package in Germany is concrete and substantial:** occupational pension (72% confirmed), company phone/laptop/tablet including private use, flexible working models plus a long-term working-time account (Langzeitkonto), reserved Kita places, EGYM Wellpass, mobility subsidies and Jobrad, group accident insurance, and the company explicitly advertises **"Equal Pay"**.
- **Work-life balance is a relative strength**, which is unusual for a company of this profile: Blind WLB **3.9** is its highest sub-score, and Glassdoor's global WLB is 3,8. Reviewers cite "Flexibility at Work".
- **Talented colleagues and meaningful work** appear in nearly every review, positive or negative: "Talented people across the organisation and strong brands with real patient impact", "You will be working with smart and professional people", "Kluge Menschen", "Interessante, sinnvolle, spannende Arbeit".
- **Internal mobility is genuinely available at scale.** "Good internal mobility ... Opportunities to move into different roles and other functions" (Cambridge, August 2026). Kununu notes "klare Entwicklungschancen" and a lifelong-learning programme.
- **Strong pipeline and business outlook.** 78% positive business outlook globally, 89% CEO approval. AstraZeneca placed top-3 in the IDEA Pharma Pharmaceutical Innovation Index in 2025.
- **Employer engages publicly with criticism** on Kununu, with specific rather than templated responses.
- **Company culture is described as inclusive**, with the highest global sub-score being Diversity & Inclusion at 4,1 (4,9 in the tiny Munich sample).

**Negatives:**

- **Management quality is the consistent weak point across every platform**: Glassdoor Senior Management **3,5** (lowest global sub-score), Blind Management **3.0** (lowest sub-score), and the German Kununu reviews repeatedly flag "Vorgesetztenverhalten - Kommt darauf an wen man bekommt/hat" (depends entirely which manager you get).
- **Localised toxicity reports, team-specific rather than company-wide.** The sharpest is a 1-star August 2026 review from a former UK sales employee of 8+ years: "The culture felt toxic, highly pressured and excessively focused on performance, internal processes and constantly changing expectations. Leadership and communication were poor and inconsistent, and **my direct manager contributed significantly to the toxic environment** ... There was little psychological safety to raise concerns openly, along with a concerning lack of confidentiality that damaged trust." Note the reviewer explicitly scopes it: "**This applies to RIVI**" (a specific business unit). A March 2025 Blind review from a Software Analyst Developer similarly cites "Toxic Mid level Management" and "High Burnout".
- **Experience varies enormously by team.** A 10+ year UK employee titled their August 2026 review "**Strong benefits and talented people, but experience varies by team**". This is the single most representative summary of the review corpus.
- **Hierarchy and top-down communication in the German organisation.** An August 2026 German review: "Starke Hierarchie - Kommunikation immer kurzfristig - keine Einbindung der Mitarbeitenden" (strong hierarchy, always short-notice communication, no employee involvement), and "'speak up' gibt es - gelebt wird es eher weniger" (speak-up exists on paper, is less lived in practice). Also: "Der meist benutzte Satz: 'das nehmen wir mal mit' (danach passiert genau gar nichts)."
- **Constant reorganisation and change fatigue.** "Viel Veränderung" (Munich, July 2026); "constantly changing expectations" (UK); "No long term strategy" (Blind).
- **AI-first messaging is landing badly with some German staff.** An August 2026 German review is titled "**KI über alles - Mitarbeitende, Vielfalt und Praxisnähe bleiben auf der Strecke. Die Stimmung kippt.**" (AI above all; employees, diversity and practical relevance are falling by the wayside; the mood is turning.) Worth noting given that the role under consideration is an AI role.
- **Career progression is the second-weakest global sub-score (3,7)** and reviewers cite "easy to get overlooked" and "No career growth" (Blind). An Austrian reviewer noted "Nur Internationale Führungskräfte. Keine Möglichkeiten lokal" (only international leadership, no local opportunities).
- **Unrealistic targets in the German commercial organisation:** "Manche Ziele sind unerreichbar da in der Theorie gut errechnet aber in der Praxis nicht umsetzbar." This is a field-sales complaint and does not transfer to an R&D engineering role.
- **Corporate slowness.** "Trägheit eines Konzerns", "Manche Prozesse sind zu komplex", "Poor Systems and Processes".

### Toxic Leadership Assessment

| Pattern | Assessment & Quotes |
|---|---|
| **Toxic Leadership** | **PRESENT BUT LOCALISED, not systemic.** The strongest report is scoped by its own author to a single business unit: "The culture felt toxic ... my direct manager contributed significantly to the toxic environment through their management style and behaviour ... **This applies to RIVI**" (UK sales, August 2026). A Blind software reviewer cites "Poor Leadership, Toxic Mid level Management" (March 2025). Against this: 89% global CEO approval, 99% among German reviewers, 78% recommend across 8.018 reviews. **No pattern of named executive misconduct**, no repeated allegations against a specific leader, and nothing resembling a company-wide fear culture. The recurring signal is *variable manager quality across 90,000 people*, which is pattern (c) localised dysfunction, plus pattern (b) large-company bureaucracy. |
| **24/7 Work Expectation** | **NOT FOUND.** The opposite, if anything: Blind rates WLB **3.9** as AstraZeneca's *strongest* sub-score, Glassdoor global WLB is 3,8, and German reviewers confirm flexible hours (69%) and a Langzeitkonto (long-term working-time account). No reviewer describes weekend expectations or always-on availability. The heaviest complaint is "Viel Arbeit" (Munich) and "highly pressured" in one UK sales unit. |
| **Internal Surveillance** | **NOT FOUND.** No reviewer on any platform mentions monitoring, activity tracking, or productivity surveillance. One UK review mentions "a concerning lack of confidentiality that damaged trust", but in the context of HR confidentiality around raised concerns, not technical surveillance. |
| **Fear-driven Management** | **WEAK SIGNAL, ONE SOURCE.** "There was little psychological safety to raise concerns openly" (UK sales, August 2026), and the German "'speak up' gibt es - gelebt wird es eher weniger". Both point to concerns being absorbed rather than acted on, not to intimidation. Not corroborated elsewhere. |
| **Communication Breakdown** | **PRESENT, moderate.** The most consistent German complaint: "Starke Hierarchie - Kommunikation immer kurzfristig - keine Einbindung der Mitarbeitenden"; "Leadership and communication were poor and inconsistent" (UK); "Mehr Transparenz" as a repeated improvement suggestion. This is the classic large-matrix-organisation communication problem, i.e. pattern (b). |
| **Unpaid Overtime** | **NOT FOUND.** No reports of unpaid overtime on Glassdoor, Kununu, Indeed or Blind. German employment law plus works-council structures and a formal Langzeitkonto make this structurally unlikely at the German entity. |
| **Silent Firings** | **NOT APPLICABLE in the covert sense.** Layoffs at AstraZeneca are announced and publicly reported (see Section 8). The nearest signal is "easy to get overlooked" and "No career growth", which is stagnation rather than managed exit. |
| **Work-Life Balance issues** | **LOW.** Global 3,8 (Glassdoor), 3.9 (Blind). The one Munich R&D review (Kununu, July 2026) flags WLB as its improvement area while still rating the employer 4,0 overall. "Viel Arbeit" (Munich Associate Director, July 2026). Nothing approaching a red flag. |

**Risk level: LOW to MODERATE.**

This is predominantly **(b) corporate bureaucracy and slow, variable management typical of a 90,000-person multinational**, with **(c) localised team-level dysfunction** in specific business units (one named UK commercial unit; some mid-level management in the tech/analyst population). It is **not (a) systemic toxicity**: there is no repeated allegation against a named leader, no cross-departmental pattern, no fear culture, no unpaid-overtime reporting, and the aggregate satisfaction metrics (78% recommend, 89% CEO approval, 8.018 reviews) are healthy and stable. The honest caveat is that **the Munich R&D site has almost no independent review coverage** (2 Glassdoor reviews, 1 Kununu R&D review), so the local team culture is effectively unmeasured and must be assessed in interview.

---

## Section 5: Compensation

### Salary Data

| Source | Title | Base (€) | Stock/yr (€) | Bonus (€) | Total Comp (€) | Data Points |
|---|---|---|---|---|---|---|
| Glassdoor DE | **Software Engineer / any engineering title** | **no data whatsoever** | | | | **0** |
| Glassdoor DE | Associate Director | €85.100 to €103.800 | not broken out | not broken out | ~€85K to €104K | 10 |
| Glassdoor DE | Senior Scientist | €70.000 to €100.000 | not broken out | not broken out | ~€70K to €100K | 3 |
| Glassdoor DE | Brand Manager | €87.750 to €121.250 | | | ~€88K to €121K | 4 |
| Glassdoor DE | Medical Science Liaison (MSL) | €84.000 to €107.500 | | | ~€84K to €108K | 9 |
| Glassdoor DE | Key Account Manager | €83.750 to €104.250 | | | ~€84K to €104K | 6 |
| Glassdoor DE | Regionalleiter | €100.000 to €148.000 | | | ~€100K to €148K | 3 |
| levels.fyi | Software Engineer, **Germany** | **insufficient data** ("We only need 4 more Software Engineer submissions at AstraZeneca to unlock") | | | | **<5** |
| levels.fyi | Senior Software Engineer, **global** | **India only:** ~€33.4K base, **€0 stock**, €3.2K bonus, **€36.5K total** | €0 | €3.2K | €36.5K | small |
| Indeed DE | Senior Software Engineer | **no salary rows returned** | | | | 0 |
| Kununu | (138 salary entries exist behind the Gehaltscheck; no engineering title exposed publicly) | UNVERIFIED | | | | 138 |
| Job posting | Senior AI Software Engineer, Munich | **not disclosed** | | | | 1 |

Munich reference points for a Senior Software Engineer at a large profitable corporate: median ~€85K to €95K base, 75th percentile ~€100K to €110K, 90th percentile ~€120K+ (before equity).

**What can be inferred, carefully.** AstraZeneca Germany's *non-engineering* professional bands cluster at **€70K to €110K** for senior individual contributor and first-line-leader roles (Senior Scientist €70K to €100K, Associate Director €85K to €104K, MSL €84K to €108K). A Senior AI Software Engineer in a regulated R&D unit would sit in the Senior Scientist to Associate Director band, implying roughly **€85K to €105K base**. That lands squarely in the Munich market bracket but likely not above it. Supporting signals: Glassdoor's German Comp & Benefits sub-score is **4,4**, notably higher than the 4,0 global figure; Indeed salary satisfaction is 79%; and one German Kununu reviewer describes pay as "Marktgerecht im mittleren Bereich" (market-appropriate, mid-range), another as "Vergleichbar mit anderen". A UK reviewer calls it "Strong compensation and benefits."

Countervailing signal: the Blind software-developer review lists "Low Pay, Cheap Labor" among cons, though that reviewer appears to be in a non-Western location given the phrasing and levels.fyi's India-only engineering data.

**This inference is not a substitute for a number.** It must be treated as an estimate and confirmed early in any process.

### Equity / Stock

- AstraZeneca is publicly listed (**LSE / NASDAQ / OMX: AZN**), so equity is liquid, unlike a private-company grant.
- Group-level plans include **performance share and restricted share awards** and an all-employee share plan; German employees also receive a **betriebliche Altersvorsorge** (occupational pension), confirmed by 72% of Kununu reviewers, plus **"attraktive Boni"** per the company's own German benefits statement.
- **Caution on grant size for engineering roles:** levels.fyi's only AstraZeneca software engineering data (India) records **€0 annual stock** at both Software Engineer and Senior Software Engineer levels. Pharma companies typically reserve meaningful equity for director level and above, with individual-contributor engineers receiving cash bonus rather than shares. **Assume equity is a small or zero component at Senior IC level** until proven otherwise.
- Practical read: expect **base + annual cash bonus + strong pension and benefits**, with equity as a possible but unconfirmed extra. This is a lower-variance, lower-upside package than a tech company at the same level.

### Verdict

**UNVERIFIED, most likely COMPARABLE.**

No source anywhere publishes a Senior Software Engineer salary for AstraZeneca in Germany: Glassdoor has 188 German salary submissions across 121 job titles and zero engineering titles; levels.fyi is short of the submission threshold for Germany; Indeed returns nothing; the job posting does not disclose a range. The adjacent-band inference (**~€85K to €105K base plus bonus and a strong pension**) puts it in line with the Munich bracket for large profitable corporates, and the German Comp & Benefits rating of 4,4 supports that. But the equity component is probably negligible at this level, which caps total compensation below what a comparable tech employer would offer. **This must be established in the first recruiter conversation.**

---

## Section 6: AI/ML & Tech Stack Fit

### AI Strategy

AstraZeneca's AI investment is substantial, funded, and organisationally embedded rather than promotional:

- **Enterprise and R&D AI at scale:** more than **$250M** invested in AI research, with AI embedded from target ideation through clinical trial execution. Generative AI and LLMs are being deployed across enterprise and R&D operations.
- **Centre for Genomics Research:** a target of analysing up to **two million genomes by 2026**, on a scalable analysis platform built with **AWS** and ML tooling.
- **Evinova:** a standalone AstraZeneca health-tech subsidiary selling an **AI-native clinical development platform** commercially. In **February 2026** it announced strategic collaborations with **Astellas, AstraZeneca and Bristol Myers Squibb**, with partners sharing operational data to power benchmarks and recommendations. Published outcomes include up to 60% improvement in patient experience, 6-month acceleration in trial delivery, and 32% cost reduction.
- **Computational Pathology Munich** (the site in question): formed from the **Definiens** acquisition, sitting inside **Oncology Translational Medicine within Oncology R&D**. Its remit is pioneering **AI-enabled computational pathology and multi-modal biomarkers** that change patient selection and drug development, combining imaging with omics and clinical data. Partnership with **Lunit** on AI-powered diagnostics for non-small-cell lung cancer.
- **The Munich roles are regulated product AI**, not research demos: the Senior AI Software Engineer builds the platforms and tooling for **Software as a Medical Device (SaMD)**, and the Senior Test Engineer validates AI models against **FDA / EMA / IVDR** submission standards, including robustness, generalisability, reproducibility, explainability, distribution-shift testing and **fairness/bias evaluation with diverse test data**.
- Internal counter-signal worth noting: a German employee review from **August 2026** is titled "KI über alles - Mitarbeitende, Vielfalt und Praxisnähe bleiben auf der Strecke" (AI above all, employees and practical relevance falling by the wayside). The AI push is real enough that parts of the commercial organisation are pushing back on it.

**Assessment: genuine, well-funded, production-grade applied AI in a regulated medical context.** This is not marketing use of the word "AI".

### Tech Stack

Derived from **current Munich job postings** (the Senior AI Software Engineer and Senior Test Engineer specs, both posted 3 to 4 August 2026, which are the most reliable available evidence), cross-checked against **AstraZeneca's published AI/genomics platform work** and the **Definiens heritage** of the site. AstraZeneca has no public engineering blog or GitHub organisation covering this unit, so posting evidence dominates.

| Category | Technologies |
|---|---|
| **Primary language(s)** | **Python** (named explicitly in the Test Engineer spec: "Proficiency in Python for test automation"); **TypeScript / JavaScript** as beneficial. **The Senior AI Software Engineer posting names no programming language at all**, requiring only "strong hands-on coding and problem-solving ability". Given a computational pathology / deep learning domain, Python is the near-certain primary language, but this is **inferred, not stated** |
| **AI/ML** | AI-enabled software systems, model integration and lifecycle management, **AI model validation** (performance, robustness, generalisability, reproducibility, stability, explainability, subgroup/fairness analysis), distribution-shift and edge-case testing, **MLOps concepts**, model-serving endpoints, data pipelines. Deep learning frameworks are not named in the postings but are implicit in computational pathology (the site's Definiens heritage is image analysis on whole-slide images) |
| **Cloud** | **AWS** (named in the Test Engineer spec, and AstraZeneca's genomics platform partner), with **Azure or GCP** accepted as alternatives in the AI SWE spec |
| **Infrastructure** | **Docker, Kubernetes**, CI/CD (**GitHub Actions** named), git/**GitHub**, production-like containerised test environments, artifact and version management |
| **Data** | Large-scale **whole-slide / digital pathology imaging** and image formats, multi-modal biomarker data (imaging + omics + clinical), data pipelines, synthetic and realistic test data generation, test data governance |
| **Quality / regulatory tooling** | **JIRA** with **Xray or Zephyr**, **pytest**, **SonarQube**, **Playwright / Cypress / Postman** for UI and API testing, requirements-to-test-to-evidence traceability tooling |
| **Regulatory frameworks (a core part of the stack here)** | **IEC 62304** (medical device software lifecycle), **ISO 13485** (QMS), **ISO 14971** (risk management), **SaMD**, **GxP**, **GDPR**, **V-model** development, design controls, formal verification and validation, FDA / EMA / **IVDR** submissions |

### Current Open Roles

Pulled from the AstraZeneca careers portal (`careers.astrazeneca.com`) on 2026-08-05, filtered to Germany and Munich. All Munich engineering roles were **posted 3 to 4 August 2026** (one to two days before this research) and carry no closing date, so all are confirmed active.

| Role | Division/Team | Level | Key Tech | Link |
|---|---|---|---|---|
| **Senior AI Software Engineer (m/f/d) for regulated Computational Pathology products** | Computational Pathology Munich (Oncology R&D) | **Senior IC** | Coding (language unnamed, Python implied), Docker, Kubernetes, AWS/Azure/GCP, GitHub, CI/CD, JIRA, V-model, IEC 62304 / ISO 13485 / ISO 14971, SaMD | [Munich, Hybrid](https://careers.astrazeneca.com/job/munich/senior-ai-software-engineer-m-f-d-for-regulated-computational-pathology-products/7684/98739686496) |
| Senior Test Engineer (m/f/d) for regulated Computational Pathology products | Computational Pathology Munich | Senior IC (5+ yrs w/ MSc) | **Python**, pytest, Playwright/Cypress/Postman, GitHub Actions, SonarQube, JIRA+Xray/Zephyr, AWS, Docker, Kubernetes, MLOps, AI model validation | [Munich, Hybrid](https://careers.astrazeneca.com/job/munich/senior-test-engineer-m-f-d-for-regulated-computational-pathology-products/7684/98707601760) |
| Senior Test Engineer (m/f/d) for regulated Computational Pathology products (second req) | Computational Pathology Munich | Senior IC | as above | [Munich, Hybrid](https://careers.astrazeneca.com/job/munich/senior-test-engineer-m-f-d-for-regulated-computational-pathology-products/7684/98707601728) |
| Associate Director (m/f/d), Computational Pathology Biomarker Lead, Oncology/BioPharma | Computational Pathology Munich | Associate Director | Scientific/biomarker leadership, not a coding role | [Munich](https://careers.astrazeneca.com/job/munich/associate-director-m-f-d-computational-pathology-biomarker-lead-oncology-biopharma/7684/98693421440) |
| Senior Scientist (m/f/d), Computational Pathology Biomarker Lead, Oncology | Computational Pathology Munich | Senior Scientist | Scientific, not a software engineering role | [Munich](https://careers.astrazeneca.com/job/munich/senior-scientist-m-f-d-computational-pathology-biomarker-lead-oncology/7684/95412040560) |

**The rest of AstraZeneca's German vacancies are not relevant:** the remaining ~11 roles on the AstraZeneca career site are Hamburg-based commercial, medical affairs and clinical operations (Therapy Area Specialist / Pharmareferent, Medical Science Liaison, Clinical Research Associate, Policy Affairs, Digital Excellence Manager, Local Study Associate Director). The separate **Alexion** career-site ID carries a further 9 Munich roles, **all commercial** (Regional Account Manager, Medical Advisor, Franchise Lead, Patient Advocacy, Business Services, Medical Science Liaison).

**No fully remote engineering roles are offered in Germany.**

**Bottom line: there is exactly one Senior Software Engineer opening in Munich.** It is senior, individual-contributor, explicitly software-development-focused ("This role has a primary focus on software development, not pure model research or algorithm development"), AI-adjacent, and mentoring-inclusive.

### Verdict

Regulated medical-software engineering with AI at its centre: platform and tooling work for **Software as a Medical Device** in computational pathology, on **AWS with Docker and Kubernetes**, **GitHub Actions CI/CD**, and Python as the near-certain (though not explicitly stated) primary language, executed under **IEC 62304 / ISO 13485 / ISO 14971** with V-model lifecycle, design controls and traceability. This is **applied production engineering, not research**, and the AI dimension is genuine: the platform serves deep-learning models analysing whole-slide pathology images for oncology biomarker discovery and diagnostics. The distinctive character of the role is that **regulatory engineering discipline is as central as the code** - roughly half the requirements list concerns design controls, risk assessment, traceability and lifecycle documentation. Excellent fit for an AI/ML platform engineer who is comfortable with, or actively wants, a formal quality regime; a poor fit for anyone who wants to ship fast and iterate loosely.

---

## Section 7: Language

**English is unambiguously the working language for the Munich engineering roles.**

- The Senior AI Software Engineer and Senior Test Engineer postings are **written entirely in English**, including the Munich site description.
- **Neither posting mentions German at any level** - not as a requirement, not as a "nice to have". The only language requirement is "Strong analytical, problem-solving, written, and verbal communication skills" (in English by implication).
- Contrast with AstraZeneca's German **commercial** roles in Hamburg, which are posted in German and use "(m/w/d)": Therapy Area Specialist, Pharmareferent, Medical Science Liaison. The Munich engineering roles use the international "(m/f/d)" convention and English throughout, marking them as part of the global R&D organisation rather than the German commercial organisation.
- The site reports into **Oncology R&D**, a global function, and collaborates across software engineering, data science, pathology, product, quality and regulatory teams that span AstraZeneca's international R&D footprint (Cambridge UK, Gothenburg, Gaithersburg).
- AstraZeneca's careers site itself offers English, Russian, German, French, Chinese and Swedish, confirming an international-first posture.

**Verdict:** **PASS.** English-required, German not mentioned at all.

---

## Section 8: Stability

### Financial Position

| Metric | FY2025 |
|---|---|
| **Total revenue** | **$58.7bn** (+8% at constant exchange rates) |
| Oncology revenue | $25.6bn (44% of total, +14%) |
| **Net income** | **$10.2bn** |
| **Core EPS** | **$9.16** (+11%) |
| Total assets | $114.074bn |
| Total liabilities | $65.355bn |
| **Net assets** | **$48.719bn** |
| **Cash and cash equivalents (31 Dec 2025)** | **$5.711bn** |
| **Net debt (31 Dec 2025)** | **$23.374bn**, down $1.196bn YoY |
| **R&D spend (2024)** | **$13.6bn**, ~25% of global revenue |
| **Credit rating** | **S&P A+** (upgraded on lower leverage); solicited ratings from both Moody's and S&P; company targets a strong investment-grade rating |
| Germany revenue (2024) | ~$2.5bn |
| Listings | LSE: AZN, NASDAQ: AZN, OMX Stockholm: AZN |

The trend is **improving**: revenue up 8%, net income $10.2bn, EPS up 11%, net debt falling, and an S&P upgrade to A+. Oncology, the division the Munich site serves, is both the largest and the fastest-growing segment. AstraZeneca is one of only three large pharma companies (with Amgen and Eli Lilly) to have *consistently increased* headcount while the sector shed more than 22,000 jobs in 2025.

### Financial Runway

**Not applicable.** AstraZeneca is a profitable, publicly traded, investment-grade company with $10.2bn of annual net income and $5.711bn of cash on the balance sheet at 31 December 2025 (source: FY2025 results announcement / Form 20-F). There is no burn rate to model and no funding event to anticipate. Per the section template, the bottom-up burn model is skipped in favour of the balance-sheet position cited above.

### Layoffs

| Date | Event | Scale | Notes |
|---|---|---|---|
| **Early 2026** | **Boulder and Longmont, Colorado site reduction** | **200+ employees**, last day of employment 22 March | US site consolidation; does not affect European R&D |
| 2025 (sector context) | Large-pharma headcount reduction across the industry | 22,000+ across the sector | **AstraZeneca was one of only three large pharma companies that *grew* headcount in 2025**, alongside Amgen and Eli Lilly |
| Historical (2013 to 2016) | Multi-year restructuring under the current CEO | ~7,300 roles over the period; Montreal and Södertälje sites closed or downsized | Long past; the company has grown substantially since |
| Germany / Munich | **No layoffs found** | n/a | No reports of German or Munich site reductions on TrueUp, in German press, or in reviews |

### Acquisition and Merger Risk (company-specific)

**This is the material stability question, and it is live as of the research date.**

On **2 August 2026**, the **Financial Times reported that AstraZeneca and Bristol Myers Squibb have been in merger talks over recent months**, in a deal that would value the combined company at roughly **$400bn**. On **3 August 2026**, AstraZeneca shares fell as much as **7%**, the second-largest decline on the FTSE 100 that day, while Bristol Myers Squibb rose ~6% in US pre-market trading. Neither company confirmed; AstraZeneca declined to comment. FT sources said a deal may never materialise, and Citi analysts called it a "surprise" given AstraZeneca's "best-in-class pipeline". Axios, CNBC, Quartz and PharmExec all carried the story.

Relevance to this role, stated plainly:

- The two companies **overlap in oncology**, which is precisely the division the Munich Computational Pathology site serves. Their pipelines are described as largely complementary (AstraZeneca stronger in solid tumours, BMS in blood cancers and cell therapy), but a combined oncology portfolio would attract antitrust scrutiny and, historically, post-merger R&D site consolidation.
- The market reaction (AstraZeneca down 7%) indicates investors view the deal as **value-destructive for AstraZeneca shareholders**, which raises the probability that it does not proceed, but also signals meaningful strategic uncertainty at the top of the company.
- A ~180-person specialist R&D site acquired from a startup is exactly the kind of unit that gets reviewed in a mega-merger integration.

This does not disqualify the opportunity. It is a real, dateable, quantified uncertainty that should be raised in interview.

**Verdict:** **PASS with CAUTION.** The financial position is outstanding (A+ rated, $10.2bn net income, growing headcount against a shrinking sector). The caution is entirely about the unresolved BMS merger talks and their potential consequences for oncology R&D site structure.

---

## Section 9: Regulated Industry

**Yes, heavily, and this is the defining practical characteristic of the role rather than an incidental fact.**

The Munich unit builds **Software as a Medical Device (SaMD)** for oncology diagnostics. The applicable regimes named explicitly in the job specifications are:

- **IEC 62304** - medical device software lifecycle processes
- **ISO 13485** - quality management systems for medical devices
- **ISO 14971** - risk management for medical devices
- **IVDR** (EU In Vitro Diagnostic Regulation), **FDA** and **EMA** submission requirements
- **GxP** and **GDPR**
- The parent operates under the full pharmaceutical regulatory apparatus (EMA, FDA, BfArM in Germany)

**Practical engineering impact, taken directly from the postings:**

- **V-model development is mandatory**, not optional: "Follow regulated software development practices for AI-enabled products using the V-model, including definition and management of requirements, design inputs, implementation controls, and support for verification and validation." This is the opposite of continuous-delivery iteration.
- **Formal design controls and traceability**: requirements-to-test-to-evidence traceability chains must be maintained and audit-ready at all times.
- **Structured lifecycle documentation is a named deliverable**: "Experience producing and maintaining structured software lifecycle documentation such as requirements, specifications, design documentation, test documentation, and change records."
- **Risk assessment as engineering work**: "Support functional risk assessment activities ... including identification of risks, definition of mitigations, and linkage of risk controls to design and verification evidence."
- **Change control, configuration management, release governance and defect management** are explicitly part of the role's remit to "establish and improve".
- **Validation packages for regulatory submissions**: the Test Engineer role contributes directly to FDA/EMA/IVDR submissions and maintains audit-ready evidence.
- Deployment cadence will be **slow by tech-industry standards**. Every release into a regulated product carries verification and validation overhead.

An honest reading: roughly **half the requirements in the Senior AI Software Engineer specification concern regulatory process rather than code**. The posting is candid about this, describing the ideal candidate as someone who can "embed quality by design, risk-based thinking, and structured lifecycle execution into day-to-day engineering practice". For an engineer who values this discipline it is a genuine specialisation with strong career durability. For one who wants fast iteration it would be frustrating.

**Verdict:** **CAUTION.** High regulatory burden with direct, daily, documented impact on engineering practice. Not a hidden cost - the postings state it openly - but it must be a deliberate choice.

---

## Section 10: On-Call

- **No on-call, standby, Rufbereitschaft, pager, or 24/7 rotation is mentioned anywhere** in either Munich engineering posting. The full text of the Senior AI Software Engineer posting was searched for on-call, standby and Bereitschaft terms: **zero matches**.
- **Product-nature assessment strongly supports no on-call.** The role builds **platforms, internal tools and engineering frameworks** used to develop regulated products, plus development infrastructure. It is not an SRE, NOC, MDR or production-SaaS operations role. Computational pathology inference runs as batch analysis on whole-slide images in a research and regulated-development context, not as a 24/7 consumer-facing service with an uptime SLA.
- The Test Engineer counterpart is likewise a quality and validation role, not an operations role.
- **No reviewer on any platform** (Glassdoor, Kununu, Indeed, Blind) mentions on-call or out-of-hours duty at AstraZeneca, and work-life balance is one of the company's better-rated dimensions (Glassdoor 3,8; Blind 3.9).
- Residual uncertainty: once a SaMD product ships to clinical customers, *someone* carries production support. Nothing indicates that this sits with the platform engineering team rather than a separate operations function, but it is unstated.

**Verdict:** **PASS** (with one item to confirm in interview: who carries production support once regulated products are in clinical use).

---

## Section 11: Interview Process

| Metric | Value |
|---|---|
| **Difficulty** | **3,04 / 5** (Glassdoor, from 2.125 difficulty submissions). Indeed independently reports "Medium" |
| **Positive experience** | **63%** positive, **19%** negative, ~18% neutral (Glassdoor, 2.185 interview reviews, updated 25 July 2026). Indeed reports "Average" |
| **Average duration** | **~1 month** (Indeed) |
| **Rounds** | Not published per-stage; a ~1 month cycle at this company size typically means 3 to 4 stages |
| **How candidates got the interview** | 67% online application, 11% referral, remainder recruiter and other |

**Assessment.** The process is **moderately difficult and generally well-regarded**: 63% positive against 19% negative is a healthy ratio, and 2.185 interview reviews is a large, reliable sample. Difficulty at 3,04/5 is squarely mid-range.

It is **not LeetCode-heavy**. The most recent published interview experiences describe CV-and-experience-based conversations ("The questions were straightforward and focused on my CV and previous experience. They also provided a detailed explanation of the role, key responsibilities, and the company's profile"). For the Munich engineering role specifically, the posting's emphasis on regulated-development experience, design controls, risk assessment and V-model execution strongly suggests the technical assessment will be **experience-and-scenario-based** (walk me through how you managed traceability on a SaMD release) rather than algorithmic. Expect deep probing on IEC 62304 / ISO 13485 / ISO 14971 practice, since the posting lists prior experience with those standards as **"a must"** twice.

**One caveat:** the ~1 month duration is a global average across a 90,000-person company with a heavy central recruiting apparatus. Large-pharma processes are frequently slower than tech processes; budget for it.

---

## Section 12: Summary Assessment

| Criterion | Summary |
|---|---|
| Software-centric | **BORDERLINE, resolved favourably at site level.** The parent is a pharmaceutical manufacturer. The Munich site is a dedicated AI/software engineering unit (ex-Definiens) with its own software-purpose GmbH, building a shippable regulated software product |
| Not consulting | **PASS.** Product engineering on an internal-then-commercial regulated product. No client billing, no consultant career track in the relevant unit |
| Profitable | **PASS, strongly.** $58.7bn revenue, $10.2bn net income FY2025, S&P A+, net debt falling |
| Employee count | ~90,000 globally, ~1,200 in Germany. Large and growing (one of three large pharma companies that added headcount in 2025) |
| English-speaking | **PASS.** Both Munich engineering postings are entirely in English with **no German requirement of any kind** |
| Local entity + engineering contracts | **PASS.** AstraZeneca Computational Pathology GmbH, HRB 251893 Amtsgericht München, registered purpose "Development and use of AI-enabled research, software and services". Direct German employment, no PEO/EOR |
| Location / work model | Landsberger Str. 300, 80687 München (Laim), near S-Bahn Laim. Hybrid, likely 3 days/week on-site. No remote option |
| Glassdoor | **4,0 global** (8.018 reviews), 78% recommend, 89% CEO approval, 78% positive outlook. **Germany 4,0** (21 reviews), 77% recommend. Munich 4,6 (2 reviews, unusable). **Zero Software Engineer reviews worldwide** |
| Indeed | **PASS, partial data.** 73% would recommend (771/288), 68% CEO approval. Sub-scores not published on the German profile |
| Kununu | 3,6 / 5,0 (358 reviews), **83% recommend**, employee-only 3,8 / 74%, **Top Company badge YES**, "Aufwärtstrend", above the pharma sector average of 3,5 |
| Salary | **UNVERIFIED, likely COMPARABLE.** No engineering salary data exists for AstraZeneca in Germany on any platform. Adjacent bands (Senior Scientist €70K to €100K, Associate Director €85K to €104K) imply ~€85K to €105K base. Equity likely negligible at Senior IC level |
| AI/ML content | **PASS, strongly.** $250M+ AI investment, two-million-genome platform on AWS, Evinova AI clinical platform, and the Munich unit itself pioneering AI-enabled computational pathology and multi-modal biomarkers with a Lunit partnership |
| Computer-language/Tech-stack | **PASS with one gap.** Python is named in the Test Engineer spec and is the near-certain primary language for computational pathology, but **the Senior AI Software Engineer posting names no programming language at all**. AWS, Docker, Kubernetes, GitHub Actions, pytest confirmed |
| No on-call | **PASS.** Zero on-call mentions in either posting; platform/tooling role, not SRE or production SaaS operations |
| WLB / Stability | **PASS on WLB** (Glassdoor 3,8; Blind 3.9 as its strongest sub-score; flexible hours, Langzeitkonto). **CAUTION on stability** solely due to the live BMS merger talks |
| Regulated industry | **CAUTION.** Heavy: IEC 62304, ISO 13485, ISO 14971, SaMD, IVDR, FDA/EMA, GxP, V-model, design controls, formal traceability. Roughly half the role's requirements are regulatory-process rather than code |
| Review themes | **PASS with reservations.** Positives: pay and benefits, WLB, talented colleagues, meaningful work, internal mobility, strong pipeline. Negatives: **variable manager quality (Senior Management 3,5 Glassdoor, 3.0 Blind, the weakest sub-score on both)**, hierarchy and short-notice communication in Germany, constant reorganisation, "experience varies by team" |
| **Merger / acquisition risk** | **CAUTION, live.** FT reported AstraZeneca / Bristol Myers Squibb merger talks on **2 August 2026** at a ~$400bn combined valuation; shares fell 7%. Oncology overlap is exactly where the Munich site sits |
| **Only one matching Munich role** | **NARROW.** Exactly one Senior Software Engineer opening in Munich (plus two Senior Test Engineer reqs). No fallback role if this one closes or is not a fit |
| **No engineer-specific review data** | **BLIND SPOT.** Zero Glassdoor Software Engineer reviews globally; 2 Munich reviews total; 1 Kununu Munich R&D review. The actual local team culture is effectively unmeasured |

---

## Section 13: Verdict

**Recommendation: Actively pursue, with three things to establish before committing.**

This is a substantially better fit than the surface description ("pharma company") suggests, and it clears every hard criterion that could be checked.

**Strengths.** The Munich site is a genuine software engineering organisation, not a pharma IT department. It descends from Definiens AG, a Munich digital-pathology software company, and survives as **AstraZeneca Computational Pathology GmbH** (HRB 251893, Amtsgericht München) with a registered corporate purpose that reads "Development and use of AI-enabled research, software and services to support and accelerate drug development". The open role is a **Senior AI Software Engineer**, individual contributor, explicitly framed as software development rather than model research, building platforms and tooling for AI-enabled Software as a Medical Device in oncology. The posting is entirely in English with **no German requirement whatsoever**, was posted 3 to 4 August 2026 (one to two days before this research), and mentions **no on-call of any kind**. The parent company is about as financially solid as an employer gets: **$58.7bn revenue, $10.2bn net income, S&P A+, net debt falling, R&D spend at 25% of revenue**, and one of only three large pharma companies to grow headcount in 2025 while the sector cut 22,000 jobs. The AI investment is real and funded ($250M+, a two-million-genome AWS platform, the Evinova AI clinical platform now sold to Astellas and BMS, and a Lunit partnership on NSCLC diagnostics). Review data is healthy and consistent across four platforms: **Glassdoor 4,0 global** on 8.018 reviews with 78% recommend and 89% CEO approval, **Kununu 3,6 with 83% recommend, a Top Company badge and an improving trend**, Indeed 73% recommend, Blind 3.7 with work-life balance as its *strongest* sub-score. Germany-specific compensation satisfaction is above the global average (Glassdoor Comp & Benefits 4,4 in Germany versus 4,0 globally), and the German benefits package is substantial: occupational pension, long-term working-time account, reserved Kita places, EGYM Wellpass, Jobrad, mobility subsidies, and an explicit "Equal Pay" commitment. The company holds **Top Employer Germany certification** and responds publicly and substantively to critical Kununu reviews.

**Hard blockers: none.** No criterion produces an outright FAIL. The Glassdoor rating meets the 4,0 floor exactly, on a large enough sample (8.018 reviews) that the reading is stable rather than fragile.

**Secondary concerns, in order of weight:**

1. **Compensation is completely unverified for this role in this country.** Glassdoor Germany carries 188 salary submissions across 121 job titles and **not one engineering title**. levels.fyi is four submissions short of unlocking German data, and its only AstraZeneca software engineering data globally is India-based (where it records **€0 annual stock** at both Software Engineer and Senior Software Engineer levels). Indeed returns nothing. The posting discloses no range. The adjacent-band inference (Senior Scientist €70K to €100K, Associate Director €85K to €104K) suggests roughly **€85K to €105K base**, which is in the Munich bracket but probably not above it, and **equity is likely negligible at Senior IC level**, capping total compensation below a comparable tech employer. This is the first question to ask a recruiter.

2. **Live merger talks with Bristol Myers Squibb.** The Financial Times reported on **2 August 2026**, three days before this research, that the two companies have been discussing a merger valuing the combined entity at ~**$400bn**. AstraZeneca shares fell up to **7%** the following day. The two firms overlap in **oncology**, which is exactly the division the Munich Computational Pathology site reports into. Nothing is confirmed and analysts called the report a surprise, but a ~180-person specialist R&D site inherited from an acquisition is precisely the kind of unit that gets reviewed during mega-merger integration.

3. **Heavy regulatory burden, by design.** IEC 62304, ISO 13485, ISO 14971, SaMD, IVDR, FDA/EMA, GxP, **mandatory V-model development**, design controls, formal risk assessment, and requirements-to-test-to-evidence traceability. Roughly half the requirements in the posting concern regulatory process rather than code. The posting is honest about this and frames it as the core of the role. It is a genuine specialisation with durable career value, but it is the opposite of fast iteration and needs to be a deliberate choice.

4. **Office in Laim, likely three days per week on-site.** Landsberger Str. 300 is served by S-Bahn Laim and the Agnes-Bernauer-Platz / Fürstenrieder Straße tram stops. There is no remote option.

5. **Python is not actually named in the target posting.** The Senior AI Software Engineer spec requires "strong hands-on coding" without specifying a language. The companion Test Engineer spec names Python explicitly, and computational pathology deep learning is Python-dominant in practice, so the inference is safe, but it is an inference.

6. **The local team is effectively unmeasured.** There are **zero Glassdoor reviews under any Software Engineer title for AstraZeneca worldwide**, two Munich reviews in total, and one Kununu review from Munich R&D (July 2026, 4,0, "Fairer Arbeitgeber", with work-life balance as its improvement area). The company-wide pattern is clear and mildly positive, but the specific team culture is not observable from outside. Note the one consistent soft spot across every platform: **management quality is the weakest sub-score everywhere** (Glassdoor Senior Management 3,5, Blind Management 3.0), and multiple reviewers converge on "experience varies by team".

7. **Only one matching vacancy exists.** If this requisition closes or the team is not a fit, there is no second Munich engineering role to fall back on. The rest of AstraZeneca's German openings are Hamburg commercial and clinical roles, and all Alexion Munich roles are commercial.

**Recommendation.** **Apply to the Senior AI Software Engineer role in Munich.** It is one of the better structural matches evaluated in this search: senior, individual contributor, software-development-focused, genuinely AI, English-only, no on-call, in a verified German software-purpose GmbH, backed by an A+ rated employer that is growing headcount while its sector shrinks. Before committing, establish three things in the process: **(a) the actual base and bonus band and whether any equity attaches at this level**, since no external source can answer this; **(b) how the BMS merger talks are being communicated internally and what, if anything, has been said about oncology R&D site structure**; and **(c) the concrete hybrid expectation in days per week, plus who carries production support once a regulated product reaches clinical use.**

---

## Sources

- [AstraZeneca - corporate site](https://www.astrazeneca.com/)
- [AstraZeneca - FY and Q4 2025 results announcement (PDF)](https://www.astrazeneca.com/content/dam/az/PDF/2025/Q4-FY/Full-year-Q4-2025-results-announcement.pdf)
- [AstraZeneca results: FY and Q4 2025 - BioSpace](https://www.biospace.com/press-releases/astrazeneca-results-fy-and-q4-2025)
- [AstraZeneca Final Results - Investegate](https://www.investegate.co.uk/announcement/rns/astrazeneca--azn/final-results/9422484)
- [AstraZeneca 9M and Q3 2025 financial results - BusinessWire](https://www.businesswire.com/news/home/20251105738625/en/AstraZenecas-9M-and-Q3-2025-Financial-Results)
- [AstraZeneca PLC Form 20-F FY2025 - SEC EDGAR](https://www.sec.gov/Archives/edgar/data/901832/000110465926019130/azn-20251231xex15d1.htm)
- [AstraZeneca revenue history - MacroTrends](https://www.macrotrends.net/stocks/charts/AZN/astrazeneca/revenue)
- [AstraZeneca - Debt investors and credit ratings](https://www.astrazeneca.com/investor-relations/debt-investors.html)
- [AstraZeneca PLC upgraded to 'A+' - S&P Global Ratings](https://www.spglobal.com/ratings/en/regulatory/article/-/view/type/HTML/id/3220778)
- [AstraZeneca PLC credit rating - Moody's](https://www.moodys.com/credit-ratings/AstraZeneca-PLC-credit-rating-600011131)
- [Handelsregister - AstraZeneca Computational Pathology GmbH, HRB 251893 München](https://www.online-handelsregister.de/handelsregisterauszug/by/Muenchen/HRB/251893/AstraZeneca-Computational-Pathology-GmbH)
- [NorthData - AstraZeneca Computational Pathology GmbH, HRB 251893 München](https://www.northdata.com/AstraZeneca%20Computational%20Pathology%20GmbH,%20M%C3%BCnchen/HRB%20251893)
- [Webvalid - AstraZeneca Computational Pathology GmbH, HRB 251893](https://www.webvalid.de/company/AstraZeneca+Computational+Pathology+GmbH,+M%C3%BCnchen/HRB+251893)
- [Creditreform - AstraZeneca Computational Pathology GmbH](https://firmeneintrag.creditreform.de/80687/8170550627/ASTRAZENECA_COMPUTATIONAL_PATHOLOGY_GMBH)
- [Firmenwissen - AstraZeneca Computational Pathology GmbH](https://www.firmenwissen.de/az/firmeneintrag/80636/8170550627/ASTRAZENECA_COMPUTATIONAL_PATHOLOGY_GMBH.html)
- [NorthData - AstraZeneca GmbH, HRB 175066 Hamburg](https://www.northdata.com/AstraZeneca+GmbH,+Hamburg/HRB+175066)
- [Handelsregister - AstraZeneca GmbH, HRB 175066 Hamburg](https://www.online-handelsregister.de/handelsregisterauszug/hh/Hamburg/HRB/175066/AstraZeneca-GmbH)
- [Handelsregister - AstraZeneca GmbH, HRB 5069 PI Pinneberg (former Wedel seat)](https://www.online-handelsregister.de/handelsregisterauszug/sh/Pinneberg/HRB/5069PI/AstraZeneca-GmbH)
- [Handelsregister - AstraZeneca Vertriebs GmbH, HRB 1544 PI Wedel](https://www.online-handelsregister.de/handelsregisterauszug/sh/Pinneberg/HRB/1544PI/AstraZeneca-Vertriebs-GmbH)
- [AstraZeneca Deutschland - Unternehmen](https://www.astrazeneca.com/content/az-de/unternehmen.html)
- [AstraZeneca careers - Germany](https://careers.astrazeneca.com/germany)
- [AstraZeneca careers - Germany job listings](https://careers.astrazeneca.com/location/germany-jobs/7684/2921044/2)
- [AstraZeneca careers - Munich job listings](https://careers.astrazeneca.com/location/munich-jobs/7684/2921044-2951839-2867714/4)
- [Senior AI Software Engineer (m/f/d) for regulated Computational Pathology products - Munich](https://careers.astrazeneca.com/job/munich/senior-ai-software-engineer-m-f-d-for-regulated-computational-pathology-products/7684/98739686496)
- [Senior Test Engineer (m/f/d) for regulated Computational Pathology products - Munich](https://careers.astrazeneca.com/job/munich/senior-test-engineer-m-f-d-for-regulated-computational-pathology-products/7684/98707601760)
- [Associate Director, Computational Pathology Biomarker Lead - Munich](https://careers.astrazeneca.com/job/munich/associate-director-m-f-d-computational-pathology-biomarker-lead-oncology-biopharma/7684/98693421440)
- [Director, Team Lead, Computational Pathology Biomarker Development - Munich](https://careers.astrazeneca.com/job/munich/director-team-lead-computational-pathology-biomarker-development-oncology-biopharmaceuticals-m-f-d/7684/95286356752)
- [Glassdoor - AstraZeneca overview (E9214)](https://www.glassdoor.com/Overview/Working-at-AstraZeneca-EI_IE9214.11,22.htm)
- [Glassdoor DE - AstraZeneca reviews (global, English-language filter)](https://www.glassdoor.de/Bewertungen/AstraZeneca-Bewertungen-E9214.htm?filter.iso3Language=eng)
- [Glassdoor DE - AstraZeneca reviews, Germany filter](https://www.glassdoor.de/Bewertungen/AstraZeneca-Deutschland-Bewertungen-EI_IE9214.0,11_IL.12,23_IN96.htm)
- [Glassdoor DE - AstraZeneca reviews, Munich filter](https://www.glassdoor.de/Bewertungen/AstraZeneca-M%C3%BCnchen-Bewertungen-EI_IE9214.0,11_IL.12,19_IC4990924.htm)
- [Glassdoor DE - AstraZeneca reviews, Software Engineer filter (zero results)](https://www.glassdoor.de/Bewertungen/AstraZeneca-Bewertungen-E9214.htm?filter.jobTitleFTS=Software%20Engineer)
- [Glassdoor DE - AstraZeneca salaries](https://www.glassdoor.de/Gehalt/AstraZeneca-Geh%C3%A4lter-E9214.htm)
- [Glassdoor DE - AstraZeneca interviews](https://www.glassdoor.de/Vorstellungsgespr%C3%A4ch/AstraZeneca-Fragen-im-Vorstellungsgespr%C3%A4ch-E9214.htm)
- [Glassdoor - AstraZeneca reviews (global page)](https://www.glassdoor.com/Reviews/AstraZeneca-Reviews-E9214.htm)
- [Kununu - AstraZeneca GmbH](https://www.kununu.com/de/astra-zeneca)
- [Kununu - AstraZeneca GmbH reviews](https://www.kununu.com/de/astra-zeneca/kommentare)
- [Indeed - AstraZeneca company page (DE)](https://de.indeed.com/cmp/Astrazeneca)
- [Indeed - AstraZeneca reviews](https://www.indeed.com/cmp/Astrazeneca/reviews)
- [Teamblind - AstraZeneca](https://www.teamblind.com/company/AstraZeneca)
- [levels.fyi - AstraZeneca Software Engineer salaries, Germany (insufficient data)](https://www.levels.fyi/companies/astrazeneca/salaries/software-engineer/locations/germany)
- [levels.fyi - AstraZeneca Software Engineer salaries (global)](https://www.levels.fyi/companies/astrazeneca/salaries/software-engineer)
- [Great Place To Work - AstraZeneca certified company profile](https://www.greatplacetowork.com/certified-company/1000024)
- [AstraZeneca - Great place to work (careers)](https://www.astrazeneca.com/careers/great-place-to-work.html)
- [AstraZeneca Switzerland - Great Place to Work press release](https://www.astrazeneca.ch/en/media/press-release/2023/Great-place-to-work.html)
- [CNBC - AstraZeneca in talks with Bristol Myers Squibb on $400 billion megadeal, FT reports (2 Aug 2026)](https://www.cnbc.com/2026/08/02/astrazeneca-and-bristol-myers-squibb-mull-400-billion-deal-report-.html)
- [CNBC - AstraZeneca slides after reports of Bristol Myers merger talks leave analysts 'perplexed' (3 Aug 2026)](https://www.cnbc.com/2026/08/03/astrazeneca-bristol-myers-squibb-merger-talks.html)
- [Axios - Pharma giants AstraZeneca and Bristol-Myers in reported merger talks](https://www.axios.com/2026/08/03/pharma-merger-astrazeneca-bristol-myers-squibb)
- [PharmExec - AstraZeneca and Bristol Myers Squibb held merger talks](https://www.pharmexec.com/view/astrazeneca-bristol-myers-squibb-held-merger-talks-report)
- [FiercePharma - Large pharma companies reduced headcounts by more than 22K in 2025](https://www.fiercepharma.com/pharma/large-pharma-companies-reduced-headcount-over-22000-2025-300b-patent-cliff-looms)
- [BioSpace layoff tracker](https://www.biospace.com/biospace-layoff-tracker)
- [TheLayoff - AstraZeneca plc](https://www.thelayoff.com/astrazeneca-plc)
- [Science.org - AstraZeneca layoffs and closings (historical)](https://www.science.org/content/blog-post/astrazeneca-layoffs-and-closings)
- [Evinova - AstraZeneca launches Evinova](https://evinova.com/press-releases/astrazeneca-launches-evinova)
- [Evinova - strategic collaborations with Astellas, AstraZeneca and Bristol Myers Squibb (Feb 2026)](https://www.businesswire.com/news/home/20260218356317/en/Evinova-Announces-Strategic-Collaborations-with-Astellas-AstraZeneca-and-Bristol-Myers-Squibb-Advancing-Its-AI-Native-Platform-to-Accelerate-Global-Clinical-Development)
- [Applied Clinical Trials - Evinova expands AI-native clinical platform](https://www.appliedclinicaltrialsonline.com/view/evinova-expands-ai-native-clinical-platform-strategic-pharma-collaborations)
- [Klover.ai - AstraZeneca's AI strategy analysis](https://www.klover.ai/astrazeneca-ai-strategy-analysis-of-ai-dominance-in-pharmaceutical-biotech/)
- [IntuitionLabs - AstraZeneca's enterprise AI case study](https://intuitionlabs.ai/articles/astrazeneca-chatgpt-case-study)
- [OpenPR - AstraZeneca's AI-driven computational pathology](https://www.openpr.com/news/3935334/astrazeneca-s-ai-driven-computational-pathology)
- [Built In - AstraZeneca work-life balance and wellbeing FAQ](https://builtin.com/company/astrazeneca/faq/work-life-balance-wellbeing)
- [Life Science Nord - AstraZeneca GmbH member profile](https://www.lifesciencenord.de/en/membership/member-directory/detail/astrazeneca-gmbh.html)
- [Alexion Global Site - Germany](https://alexion.com/worldwide/germany)
- [Overpass API - nearby transit stops query](https://overpass-api.de/api/interpreter)

---

## Retrieval Notes

- **WebFetch / WebSearch** succeeded for: AstraZeneca FY2025 financials, credit rating, merger coverage, AI strategy, layoff history, German Handelsregister lookups, and Munich site background.
- **curl with browser User-Agent** was required for the AstraZeneca careers portal (`careers.astrazeneca.com`) job listings and full posting text, since the site returns JSON/HTML fragments that WebFetch summarises away.
- **Playwright over CDP** (persistent logged-in Chromium at `localhost:9222`) was required for: **Kununu** (direct curl returns HTTP 405; the `astrazeneca` slug 404s and the correct slug `astra-zeneca` had to be found via in-browser search), **Glassdoor** overview, filtered reviews, salaries and interviews (glassdoor.com redirects to the German locale for this session; the numeric interview difficulty of 3,04 had to be extracted from the page HTML because it does not render as text), **Teamblind** (consent wall), **levels.fyi**, and **NorthData** (cookie consent wall).
- **Nearest stops** were taken from **OpenStreetMap Overpass** (stops within 700 m of the office coordinates 48.14347 / 11.50249, which returned S-Bahn Laim plus the Agnes-Bernauer-Platz and Fürstenrieder Straße tram stops).
- **Indeed MCP** returned a rich company dossier but **no published star ratings or sub-scores** on the German profile, and **no salary rows** for Senior Software Engineer in Germany.
- **levels.fyi** explicitly reports insufficient data for AstraZeneca software engineers in Germany ("We only need 4 more Software Engineer submissions ... to unlock").
