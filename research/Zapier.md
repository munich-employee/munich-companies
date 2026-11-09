# Zapier - Research Report

_Researched: 2026-03-12_

## Company Basics
- **Founded**: 2011 (YC 2012), San Francisco (registered address only - fully remote)
- **Founders**: Wade Foster (CEO), Bryan Helmig (CTO), Mike Knoop (CPO) - all still active
- **Employees**: ~800-1,200
- **Revenue**: $310M (2024), projected ~$400M (2025). Historical: $100M (2020), $140M (2021), $199M (2022), $251M (2023)
- **Profitable since 2014** - only raised ~$1.4-2.7M total (seed). Sequoia bought secondary shares at $5B valuation in 2021
- **Private**, founder-controlled (~80% equity retained)
- **Business model**: Subscription SaaS - workflow automation platform connecting 8,000+ apps

## German GmbH

No German GmbH found. Zapier uses **Deel (EOR)** for international employees. Germany isn't even listed in salary bands for current job postings (only UK, Ireland, Spain).

## Remote Policy
- 100% remote since founding, no offices anywhere
- Asynchronous-first communication culture
- Employees work across 40+ countries, 17+ time zones
- However: AI roles require **working US Eastern Time hours 3 days/week** - that's until 11 PM-midnight from Munich

## Glassdoor & Culture
- **Glassdoor**: 4.1/5 (288 reviews) - passes the 4.0 threshold numerically
- **Compensation & Benefits**: 4.5/5
- **78%** would recommend to a friend
- **Kununu**: No profile (no German entity)
- **Concerning trajectory since 2023**:
  - Multiple reviews describe sharp cultural downturn starting mid-2023
  - Layoffs after promising none; support outsourced to contractors in Philippines
  - Engineers evaluated on "lines of code written and completed tickets"
  - "Emoji reactions" used to assess engagement
  - Capable engineers and leaders leaving in significant numbers
  - Pressure to tie all roles to pipeline and revenue
  - CEO mandate: "100% of new hires must be fluent in AI"

## Tech Stack - Strong Fit
- **Backend**: Python/Django (core), Celery (distributed task processing)
- **Data**: MySQL (primary), Redis, RabbitMQ/Kafka (Amazon MSK)
- **Infrastructure**: AWS (EC2, RDS, MSK, Lambda, Redshift), Kubernetes, Terraform, Puppet, Ansible
- **Frontend**: React + Redux
- **AI/ML**: Heavy investment - LLM orchestration, RAG systems, vector databases, semantic search. AI Capabilities team building unified AI execution platform. Mike Knoop appointed Head of Zapier AI

## Open Roles (as of 2026-03-12)

| Role | Region | Salary |
|------|--------|--------|
| Staff Engineer, Applied AI | NAMER + EMEA | US: $274.8K-$412.2K; UK: GBP157.2K-235.8K; IE/ES: EUR162.6K-244K |
| Sr. Director, Engineering - Applied AI | NAMER + EMEA | Not listed |
| Staff Machine Learning Engineer | NAMER + EMEA (likely) | Not confirmed |
| Sr. Applied AI Engineer | Americas + EMEA | US: $206.6K-$309.8K; UK: GBP118.1K-177.1K; ES: EUR134.5K-201.7K |
| Sr. Manager, AI & Machine Learning | NAMER + EMEA | Not listed |

Germany not listed in any salary band.

## Salary
- **Levels.fyi (US)**: L2 $131K, L3 $188K, L4 (Senior) $219K
- **European Staff AI band**: EUR162.6K-244K (Spain/Ireland)
- Germany not explicitly listed

## Interview Process
9 steps, ~25 days:
1. Application (6-10 long-form questions, no resume required)
2. Application review (guaranteed response within 7 days)
3. Recruiter interview (may be AI-led, 15-20 min)
4. Hiring manager interview (45-60 min)
5. Skills assessment (take-home + Zoom)
6. Cross-functional interviews
7. Final/executive interview (soft skills focus)
8. References (automated via HiPeople) + background check (Certn)
9. Offer

## On-Call
Unknown - could not be confirmed or denied. Likely exists given platform uptime requirements.

## Criteria Evaluation

| Criterion | Status |
|-----------|--------|
| Age (6+ years) | PASS (14 years) |
| Profitable | PASS (since 2014) |
| Number of employees | ~800-1,200 |
| German GmbH with local contracts | **FAIL - uses Deel EOR** |
| English-speaking | PASS |
| Remote/Munich accessible | PASS (fully remote) |
| Software-centric, not consulting | PASS |
| Glassdoor >= 4.0 | PASS (4.1, declining trajectory) |
| Salary | Likely PASS at Staff level |
| No on-call | UNKNOWN |
| Python prominent | PASS (Python/Django core) |
| AI/ML content | PASS (strong investment) |
| Staff/Senior roles available | PASS |
| WLB / ET hours requirement | CONCERN |

## Summary

Zapier fails the non-negotiable German GmbH criterion - they use Deel EOR for international employees and have no German legal entity. Otherwise a strong technical fit (Python/Django, genuine AI platform work, profitable, remote-first). Additional concerns: cultural deterioration since 2023, ET-hours requirement for AI roles, and borderline employee count. Do not pursue unless Zapier establishes a German GmbH.
