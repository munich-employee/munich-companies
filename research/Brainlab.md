# Brainlab - Employer Research Report

_Researched: 2026-05-21_


**Verdict: NOT RECOMMENDED** - fails on salary, C++ stack, and regulated industry (caution flag). Glassdoor/culture scores are acceptable but not enough to overcome structural mismatches.

---

## Company Basics

| Attribute | Detail |
|-----------|--------|
| Founded | 1989 (37 years old - stable) |
| Legal entity | Brainlab SE (converted from AG in June 2025; HRB 303366, District Court of Munich) |
| HQ address | Olof-Palme-Str. 9, 81829 München (Messestadt Riem district) |
| Employees | ~1,979-2,400 globally, ~541 R&D developers in Munich HQ |
| Revenue | €429.2M (FY 2022/23) |
| Ownership | Privately held; founder Stefan Vilsmeier stepped down as CEO in 2025, became Chairman |
| Profitable / VC-backed | Yes, profitable; no VC funding - bootstrapped since 1989 |
| Global footprint | 25 locations worldwide, operates in 121 countries |

**Pass:** Old enough, large enough, profitable, not VC-backed, stable.

---

## Legal Entity

Brainlab converted from an AG to a Societas Europaea (SE) in June 2025. An SE is a valid European Company form registered under German law - engineers would be employed under a standard German Arbeitsvertrag directly through the Munich entity. The registration (HRB 303366, Munich District Court) confirms a genuine German legal seat.

**Pass:** German legal entity with direct employment. Not a GmbH but SE is equivalent for contract purposes.

---

## Industry and Product

Brainlab makes software-driven medical technology for:
- Image-guided surgery (neurosurgery, ENT, spine, trauma)
- Radiosurgery and radiation therapy systems
- Digital operating room integration
- Mixed reality patient visualization

This is a **regulated industry** (FDA, CE, ISO). Per criteria, caution is advised. The product includes significant hardware components - robotic devices (Loop-X, Cirq), tracking instruments, imaging systems - making Brainlab hardware-adjacent. The software is not standalone SaaS or platform product; it is deeply coupled to proprietary medical hardware.

In June 2025, Brainlab spun off Snke Holding SE (digital health platforms, Level Ex, Mint Medical, VisionTree) - the more software-only, SaaS-oriented part of the business is now a separate company.

**Flag (regulated industry):** Medical devices under FDA/CE/ISO. Same regime as previously encountered.  
**Flag (role type):** Core R&D roles are C++ dominant with hardware integration context. No Python-first platform or AI/ML engineering track is visible.

---

## Tech Stack

This is the **most significant mismatch**. Brainlab's primary engineering language is **C++**, not Python. Current open positions confirm:

- "Software Engineer (C++) - R&D Tracking Technologies"
- "(Advanced) C++ Software Engineer - Medical Image Processing Algorithms" (Python used only for rapid prototyping; final implementation in C++)
- "Advanced Software Engineer - Digital Patient Model Services (C++)"

Python appears as a secondary prototyping language in some R&D roles, not as the primary stack. There is no visible AI/ML platform, MLOps, cloud backend, or data engineering function. The engineering organisation is structured around Surgery, Radiotherapy, and Digital O.R. product lines rather than platform or infrastructure.

**Hard fail:** The entire Brainlab R&D operation is C++-dominant.

---

## Location

**Office:** Messestadt Riem, far east Munich (Olof-Palme-Str. 9).

- U2 from Scheidplatz south through the city and east to Messestadt Ost: approximately 35-40 minutes
- Walk from Messestadt Ost station: ~13 minutes
- **Total: approximately 50-55 minutes each way**

**Hybrid policy:** Reviews report 3 days/week in office is required. Several reviews specifically flag that home office is "not appreciated" and was only tolerated during COVID.

---

## Salary - Critical Fail

This is the clearest disqualifier.

| Source | Reported Range |
|--------|----------------|
| Levels.fyi (Software Engineer, Munich) | €60.9K - €68.1K median; max reported €84.6K |
| Levels.fyi (Software Engineering Manager) | ~€98K median |
| Glassdoor (Software Engineer, Munich) | Comp & benefits: 2.5 / 5 (based on 20 SE ratings) |
| Glassdoor (all Munich employees) | "Low salary" appears in 21 of 81 Munich reviews as top con |

**Criteria thresholds:**
- Senior Software Engineer: 110k-140k
- Staff Software Engineer: 135k-155k

Brainlab's senior-level compensation (estimated €70-85K total) is **40-50% below the minimum threshold for a senior role**. Even their Software Engineering Manager level sits at ~€98K.

Multiple reviews explicitly state: "Low pay compared to companies in similar field," "no bonus for extra effort," compensation rated 2.5/5 by software engineers specifically.

**Hard fail (critical):** Salary is roughly half of the target range. Not negotiable into range.

---

## Glassdoor Ratings

| Metric | Score |
|--------|-------|
| Overall (worldwide) | 4.0 / 5 (339 reviews) |
| Overall (Munich) | 4.1 / 5 (81 reviews) |
| Work-life balance | 4.2-4.3 / 5 |
| Culture & values | 4.1-4.2 / 5 |
| Career opportunities | 3.7 / 5 |
| Compensation & benefits (Munich) | 3.5 / 5 |
| Compensation & benefits (SWE Munich) | 2.5 / 5 |
| Recommend to a friend (Munich) | 88% |

**Overall rating:** Passes the 4.0 threshold (barely). Munich-specific rating is 4.1 - acceptable.

**Positive themes across reviews:**
- Strong work-life balance, manageable hours
- On-site perks: gym with personal trainers, subsidised restaurant
- Friendly, multi-national colleagues
- Meaningful work (medical impact)
- Stable employer, low risk of layoffs

**Negative themes:**
- Salary consistently flagged as below market (top con in Munich reviews)
- Management quality inconsistent - some reviews cite micromanagement, lack of transparency, and political dynamics
- Career progression slow and unclear
- Home office inflexibility despite hybrid branding
- Smart people leave due to poor team leadership (turnover concern)

**Notable negative review (older but cited):** "Avoid this company like the plague" - mentions toxic dynamics in some teams. This appears to be an outlier given the overall 4.0+ score, but worth noting.

No evidence of systemic 24/7 work culture, unpaid overtime as a pattern, or internal surveillance. Work-life balance is genuinely well-rated.

**Pass on culture:** No disqualifying red flags for toxic leadership at systemic level. Management is inconsistent but not a pattern of toxicity. WLB is a genuine strength.

---

## Kununu

Direct access to Kununu was blocked. No reliable score found via search. **Data gap - could not verify Kununu score or Weiterempfehlung percentage.** Recommend checking kununu.com/de/brainlab manually before any further steps.

---

## Great Place to Work

No evidence of GPTW certification for Brainlab. Not listed in search results. Not present in the Great-Place-To-Work-Der-Report-2025 findings in the workspace context.

---

## Criteria Scorecard

| Criterion | Status | Notes |
|-----------|--------|-------|
| Own product (not consulting) | PASS | Medical technology product company |
| Large company | PASS | ~2,000 globally |
| Profitable, not VC-backed | PASS | Privately held, profitable since 1989 |
| Permanent, full-time roles | PASS | Standard employment model |
| Glassdoor (Germany) | PASS (marginal) | 4.1 Munich, 4.0 overall |
| Kununu | UNKNOWN | Data gap |
| No toxic culture red flags | PASS | WLB good; some mgmt inconsistency but not systemic |
| English-speaking environment | PASS | International team, 83 nationalities |
| German legal entity (SE/AG/GmbH) | PASS | Brainlab SE, HRB 303366 Munich |
| Location / work model | - | Messestadt Riem; 3 days/week office |
| Salary | HARD FAIL | €70-85K vs. 110k-155k target |
| Role type (cloud/backend/AI/ML) | HARD FAIL | No visible roles matching profile |
| Python as main language | HARD FAIL | C++ dominant across all R&D |
| No Python/AI/ML roles; C++ dominant | HARD FAIL | All R&D is C++ (see above); no Python-first platform or AI/ML track visible |
| Not regulated industry | CAUTION | FDA/CE/ISO medical devices |
| No C/C++ requirement | HARD FAIL | C++ is the primary language |
| No on-call duty | LIKELY PASS | No evidence of on-call in reviews |

---

## Summary

Brainlab is a stable, well-run Munich medical tech company with 37 years of history, a genuine German legal entity, good work-life balance, and an internationally friendly culture. On those dimensions it is a reasonable employer. 

1. **Salary.** ~€70-85K for senior engineers.
2. **C++ is the core language.** Essentially all R&D engineering is C++.
3. **No role alignment.** There are no cloud backend, MLOps, AI/ML platform, or Python-first roles visible. The R&D structure is product-line-oriented (Surgery, Radiotherapy) not platform-oriented.
4. **No role alignment + C++ dominant.** All R&D roles are C++ first, with no visible Python-first backend, AI/ML platform, or MLOps track. The deeper reason the role type fails is that engineering is structured around hardware-coupled products, but the criterion that applies is the C/C++ exclusion and absence of matching roles.

Do not pursue.
