# Employer Evaluation: ADAC

_Researched: 2026-05-19_


**Verdict: NOT RECOMMENDED** - multiple hard-criteria failures

---

## Company Overview

The Allgemeiner Deutscher Automobil-Club (ADAC) is Europe's largest automobile club, founded on 24 May 1903 in Stuttgart and headquartered in Munich. It operates through a three-pillar structure:

- **ADAC e.V.** - the registered non-profit association; membership services, roadside assistance
- **ADAC SE** - the commercial holding entity (insurance, car rental, travel, financial services); revenue ~€1.27B in 2023
- **ADAC IT Service GmbH** - the internal IT subsidiary; ~250 IT specialists serving all ADAC entities

Employment for IT roles would likely be through ADAC IT Service GmbH (Munich District Court HRB 224568).

---

## Criteria Assessment

### Company Type and Culture

| Criterion | Status | Notes |
|---|---|---|
| Own product/software-centric | FAIL | ADAC is a roadside assistance and insurance club. IT is a support function, not a core product differentiator. SAP-heavy enterprise IT environment. |
| No consulting | PASS | Internal-only IT function |
| Full-time permanent | PASS | Standard employment offered |
| Profitable, no VC | PASS | Long-established, self-funded through ~22 million member subscriptions and commercial revenues |
| Number of employees | - | ~2,400 at Munich HQ alone; 5,000-10,000 across all entities |
| English-speaking environment | FLAG | Career page available in English and staff spans 15 nationalities, but virtually all job postings are in German. German is clearly the primary working language. Likely German-first environment internally. |
| Glassdoor score >4.0 | FAIL | 3.6/5 across 87 reviews for ADAC e.V. (69% recommend). Below the 4.0 threshold. No ADAC IT Service GmbH-specific profile found. |
| Kununu score >3.6, >60% Weiterempfehlung | UNVERIFIED | Kununu page not accessible during research. No data retrieved. |
| No toxic leadership / unpaid OT / surveillance | UNVERIFIED | Nothing specific found in press or reviews, but insufficient review volume for ADAC IT Service GmbH specifically. |
| Stability and Work-Life Balance | PASS | As a 120-year-old membership organization with stable funding, continuity risk is near-zero. No "end of runway" scenarios. Collective agreement employment (private insurance sector) suggests regulated hours. |
| Regulated industry caution | LOW | ADAC is not regulated in the same sense as medical devices or finance; insurance subsidiary is regulated but IT roles in the IT Service GmbH are unlikely to be in the compliance critical path. |

**Overall company culture verdict: FAIL** - The Glassdoor score is below threshold, and more fundamentally ADAC is not a software-centric organization. IT is a cost centre serving a club whose core product is roadside rescue and insurance.

---

### Location and Contract

| Criterion | Status | Notes |
|---|---|---|
| Munich location | PASS | Headquarters at Hansastraße 19, 80686 München (Sendling-Westpark district, "Stern von Sendling" building) |
| Office location | - | Nearest U-Bahn: Heimeranplatz (U4/U5), ~5-minute walk from building. |
| Remote option | PARTIAL | Up to 50% hybrid working within Germany (no fully remote). "Workation" abroad up to 15 days/year. |
| German GmbH / direct employment | PASS | ADAC IT Service GmbH is a registered German GmbH (HRB 224568, Munich). Direct Arbeitsvertrag expected. |
| Salary range overlap | UNVERIFIED | No data on levels.fyi. Employment is under the collective agreement for the private insurance sector (Tarifvertrag). This typically caps total compensation well below senior/staff tech company market rates (135k-155k for Staff). Collective agreement salaries in this sector tend to land in the 70k-100k range for senior technical roles. **Strong risk of salary shortfall.** |

---

### Role Level and Type

| Criterion | Status | Notes |
|---|---|---|
| Staff or Senior level | POSSIBLE | Senior and Head-of roles exist within ADAC IT Service GmbH |
| Cloud/backend/platform with AI/ML | FAIL | The tech stack is Java, SQL, SAP S/4HANA, and Microsoft 365/Teams/SharePoint. Cloud migration is in early stages. No Python, no AI/ML platform work, no MLOps. The most advanced mentioned tooling is Microsoft CoPilot and process mining. |
| Python as primary language | FAIL | Java is the dominant language. No Python engineering roles found. |
| No C/C++ | PASS | No embedded or hardware work in this IT subsidiary |
| No regular on-call | LIKELY PASS | Enterprise IT service desk norms; no signals of 24/7 operational on-call typical for product companies |
| No embedded/hardware/blockchain | PASS | None present |

---

## Glassdoor

- **Entity reviewed:** Allgemeiner Deutscher Automobil-Club (ADAC e.V.)
- **Overall rating:** 3.6 / 5 (87 reviews)
- **Recommend to friend:** 69%
- **Interview experience:** 83% positive, difficulty 2.9/5
- **Business outlook:** 67% positive
- **Note:** No separate ADAC IT Service GmbH profile found on Glassdoor. The 3.6 overall score is below the 4.0 minimum threshold. Filtered software engineer scores are unavailable due to low review volume.

---

## Kununu

- Data not accessible during research. No score or Weiterempfehlung rate retrieved.
- This is a notable gap given Kununu is often more informative for Munich-based German employers.

---

## Salary

- No data on levels.fyi for ADAC or ADAC IT Service GmbH.
- Employment falls under the **Tarifvertrag for the private insurance sector (Versicherungsgewerbe)**. Collective agreement salaries in this sector are structured and generally conservative, with senior technical roles typically landing 70k-95k total compensation.

---

## Tech Environment Summary

ADAC IT Service GmbH describes itself as "the central IT service provider for all ADAC entities." With 250+ engineers, it functions as an internal shared-service IT department, not an engineering product team. Current priorities are SAP S/4HANA operation, Microsoft 365 rollout, and an early-stage cloud migration. The role type is closer to enterprise IT/ERP consultant than platform engineer or ML engineer.

---

## Red Flags

1. **Below-threshold Glassdoor score (3.6)**
2. **IT is a cost centre, not a product** - ADAC's value proposition is built on roadside assistance, insurance, and travel services. Engineering is an enabler, not a differentiator. Career growth ceiling for software engineers is structurally lower than at a product company.
3. **SAP/Java/Microsoft monoculture**
4. **German as primary working language** - despite the English career page, all open postings are in German. Likely German-first internal culture.
5. **Collective agreement salary** - expected to be well below market rate for Staff-level tech engineers in Munich.
6. **Small IT team (250 people)** - limited scope for Staff-level impact across a shared-service org.

---

## Overall Recommendation

**Do not pursue.**:

- Glassdoor score below 4.0
- Not a software-centric organization
- Tech stack is Java/SAP, not Python/cloud/ML
- Salary structure (collective agreement insurance sector) very likely below target range
- German-first work environment

The stability is a genuine positive, but it does not outweigh the structural mismatches. ADAC is a great organization for what it does, but it is not the right environment for a Staff engineer whose expertise is Python, ML platform engineering, and cloud-native systems.
