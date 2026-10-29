
# SNA Protocol

## Overview and Guiding Principles

This protocol operationalizes the assessment methodology for solo auditor use. The primary data collection instrument is two questionnaires administered digitally to all female employees and a stratified sample of male employees. Email metadata, if obtainable, is treated as a supplementary data source — valuable when available, not required.

The protocol rests on three empirical commitments:

1. **Representation ≠ inclusion.** Headcount metrics are necessary but insufficient. This assessment measures structural position, not demographic ratios alone.
2. **ONA is valid at all sizes, but makes different claims at different sizes.** Below 50 employees, ONA is descriptive and map-grade. Above 50, it is statistically inferential. The scoring model reflects this.
3. **In the Japanese context, passive communication data requires preprocessing and may be unavailable.** CC-all email culture inflates connection counts artificially. If email metadata is provided, only FROM and TO fields are used. CC is discarded entirely. If unavailable, the survey-elicited network graph is the sole ONA input.

---

## Tier Classification

Before beginning any assessment, classify the company by headcount. This determines method weighting applied throughout.

| Tier | Headcount | ONA Role | Perception Survey Role |
|------|-----------|----------|------------------------|
| **Tier 1** | < 20 | Descriptive mapping only — provides structure for interpretation | Primary evidence carrier |
| **Tier 2** | 20–50 | Directional signal — centrality trends interpreted with caution | Co-equal with ONA |
| **Tier 3** | 50+ | Full inferential analysis — centrality, E-I index, path length | Contextual and validating |

Document the tier in the assessment file before any data collection begins.

---

## Phase 0 — Onboarding

**Estimated time: 1 meeting, 60–90 minutes**

**Who attends:** Most senior HR contact plus one C-suite sponsor. Do not include direct managers of assessed employees.

**Data access request — primary:** Two digital questionnaires will be sent to employees. Survey responses are processed by the external auditor only. No individual response is shared with the company. You need from the company: org chart with formal reporting lines, titles, tenure, and gender (self-reported); a complete department list for dropdown construction; a distribution list to send the surveys to.

**Data access request — supplementary (optional):** If IT infrastructure permits, a 90-day email metadata export limited to FROM, TO, and timestamp fields. No subject lines, no body content, no CC or BCC. If this is not technically feasible or creates legal concern, proceed without it. Its absence does not degrade the assessment.

**Survey distribution:** All female employees receive both questionnaires. Male employees receive both questionnaires on a stratified sample basis (see Phase 1). Completion is expected as part of the company's participation in the program. Non-participation by individual employees is noted in the compliance profile.

**Document:** Consent obtained, expected response timeline (target: 10 business days), department list confirmed, any constraints on data access.

---

## Phase 1 — Data Collection

### The two questionnaires

Both questionnaires are sent together as a single digital form (Google Forms or equivalent). They appear to the respondent as one unified instrument. Estimated completion time: 15–18 minutes.

---

### Questionnaire 1 — Network Mapping

*Purpose: Elicit the relational graph for ONA. Seven named-network questions covering formal collaboration, communication, influence, bridging, formal reporting, informal pre-meeting consultation, and after-work networks.*

**Name entry format — applies to all questions in this section:**

For each person nominated, the respondent completes three fields:
- **Family name** (free text — enter in romaji, e.g. Yamamoto)
- **Given name** (free text — enter in romaji, e.g. Kenji)
- **Department** (dropdown — populated from the company department list provided at onboarding)

*Instruction shown at the top of this section:*
> *For each question below, enter the names of colleagues who come to mind using the name entry fields provided. Please enter names in romaji (roman letters). Use the department dropdown to select their team. You may add as many people as you like using the "add another person" button. There are no right or wrong answers — we are interested in how work actually happens, not how it is supposed to happen on paper. You do not need to include your direct manager unless they genuinely come to mind for that question.*

---

**Q1 — Collaboration**

*"Who do you regularly work with on projects, tasks, or initiatives?"*

For each person nominated, select interaction frequency: daily / a few times a week / weekly / less than weekly.

Name entry fields per nomination. Frequency selector per nomination.

---

**Q2 — Communication**

*"Who do you most frequently communicate with about work matters — through any channel (email, messaging, meetings)?"*

For each person nominated, select interaction frequency: daily / a few times a week / weekly / less than weekly.

Name entry fields per nomination. Frequency selector per nomination.

---

**Q3 — Influence and Advice**

*"When you face an important decision or need guidance on something that matters for your work, who do you turn to?"*

Name entry fields per nomination.

---

**Q4 — Bridging Connections**

*"Who do you rely on to connect you with other teams, departments, or resources outside your immediate group?"*

Name entry fields per nomination.

---

**Q5 — Formal Reporting**

*"Who do you directly report to in your current role?"*

Name entry fields. Single nomination only.

---

**Q6 — Informal Pre-Meeting Consultation**

*"In your experience, important decisions in this organization are sometimes shaped before the official meeting takes place — through informal conversations beforehand. If this happens in your team or area, who is typically part of those conversations?"*

*If this does not happen in your experience, leave blank.*

Name entry fields per nomination.

*Translator note: Frame this as a neutral cultural observation, not a criticism. The phrasing in Japanese should reflect that this is a recognized and normal feature of how decisions are made, not an accusation of improper conduct. Response rate on this question is sensitive to tone.*

---

**Q7 — After-Work Network**

*"Do you participate in work-related social gatherings outside of office hours — for example drinks, dinners, or informal get-togethers with colleagues? If yes, who tends to be part of those gatherings?"*

*If you do not participate in such gatherings, leave blank.*

Name entry fields per nomination.

---

**Questionnaire 1 — edge weight reference:**

| Question | What it captures | Edge weight |
|----------|-----------------|-------------|
| Q1 — Collaboration | Regular working relationships | Frequency-mapped: daily=4, few times/week=3, weekly=2, less=1 |
| Q2 — Communication | Communication volume | Frequency-mapped: daily=4, few times/week=3, weekly=2, less=1 |
| Q3 — Influence / Advice | Intentional trust and guidance ties | 3 |
| Q4 — Bridging | Cross-boundary connector ties | 2 |
| Q5 — Formal reporting | Structural hierarchy baseline | 1 |
| Q6 — Informal pre-meeting consultation | Informal decision-shaping ties | 3 |
| Q7 — After-work network | Informal social network ties | 2 |

---

### Questionnaire 2 — Perception Survey

*Purpose: Measure subjective experience of inclusion, influence, and structural fairness. 18 questions on a 5-point agreement scale.*

Scale shown to respondent:
**1 = Strongly disagree / 2 = Disagree / 3 = Neither agree nor disagree / 4 = Agree / 5 = Strongly agree**

Instructions shown to respondent:
> *The following statements are about your day-to-day experience at work. Please respond based on what you actually observe and experience, not what you think should be the case.*

---

**Block A — Collaboration and Project Access**

*A1.* "I am included in project teams and working groups that match my skills and level of seniority."

*A2.* "When important projects are being staffed, I find out through formal channels rather than hearing about it after the fact through informal ones."
*(Reverse indicator: disagreement suggests informal network exclusion)*

*A3.* "I have the same opportunities to take on high-visibility work as my peers at the same level."

---

**Block B — Communication and Information Access**

*B1.* "I receive information relevant to my work at the same time as my peers."

*B2.* "I have the same access to senior leadership as colleagues at my level."

*B3.* "Important context or decisions about my work are sometimes communicated to others before they reach me."
*(Reverse indicator: agreement suggests structural information asymmetry)*

---

**Block C — Influence and Voice**

*C1.* "My opinions are genuinely considered before decisions are made in my team."

*C2.* "When I raise an idea or concern in a meeting, it is taken seriously."

*C3.* "I can think of at least one senior person in this organization who actively supports my professional growth and advocates for me."
*(Sponsorship proxy)*

*C4.* "Decisions in my team are sometimes made in informal settings I am not part of — before the official meeting takes place."
*(Reverse indicator: agreement signals exclusion from informal decision nodes)*

---

**Block D — Bridging and Organizational Visibility**

*D1.* "I am aware of opportunities — projects, roles, cross-functional work — that arise in other parts of the organization."

*D2.* "I have useful working relationships with people outside my immediate team."

---

**Block E — Formal Control and Responsibility**

*E1.* "My level of actual responsibility matches my formal title and seniority."

*E2.* "I have meaningful decision-making authority in my role — for example over budgets, team direction, or client relationships."

---

**Block F — Fairness and Psychological Safety**

*F1.* "The criteria for advancement in this organization are clear and applied consistently across people."

*F2.* "My contributions are recognized in the same way as peers who do similar work."

*F3.* "I feel comfortable raising a concern about unfair treatment in this organization without fear of negative consequences."

*F4.* "In my experience, informal social connections — such as personal relationships or after-work socializing — influence who gets opportunities here."
*(Structural indicator: agreement signals that informal network access is a driver of opportunity allocation — a structural equity problem regardless of how individual respondents experience it personally)*

---

### Distribution targeting

**All female employees** receive both questionnaires, without exception.

**Male employees:** Stratified sample as follows:

| Tier | Male sample |
|------|-------------|
| Tier 1 (<20) | All male employees |
| Tier 2 (20–50) | All male employees |
| Tier 3 (50+) | 40% stratified by seniority band — ensure at least 3 respondents per seniority level |

*Rationale for sampling all men at Tier 1 and 2:* At small scale, the male perspective is needed to construct a valid network graph. Sampling at small n risks too many missing nodes to produce a readable map.

---

### Optional supplementary — email metadata

If the company provides a FROM/TO/timestamp CSV:

1. Strip all external domains
2. Remove auto-generated senders
3. Deduplicate to weighted edge list (weight = log of frequency over 90 days)
4. Map email addresses to anonymized IDs
5. Merge with survey-derived edge list, with survey ties given higher weight on the influence and advice dimensions (they represent intentional relationship naming, not just communication volume)

If not provided: proceed with survey-elicited graph only. Note the absence in the report but do not treat it as a compliance flag unless the company refuses to cooperate with the questionnaires as well.

---

## Phase 2 — Analysis

### 2A. Build the network graph

From the seven network questions, construct a directed weighted edge list using the weights defined in the Questionnaire 1 edge weight reference table above.

If email metadata is available, add those edges with weight = log(frequency), capped at 3.

Build two versions:
- **Full graph:** all respondents
- **Gender overlay:** same graph, nodes color-coded by gender

For Tier 1, produce the map and use it as a structuring device for interpretation. Do not report numerical centrality scores as findings.

### 2B. Network metrics

Calculate for Tier 3 (inferential), label as directional for Tier 2, map-only for Tier 1.

**Degree centrality (in/out)**
Who initiates vs. who receives. Flag female employees whose in-degree is low relative to their formal seniority.

**Betweenness centrality**
Who brokers between otherwise disconnected groups. Low betweenness in senior women = structural bypass finding.

**E-I Index**

The E-I (External-Internal) Index measures whether a person's ties go predominantly outside their gender group (external) or within it (internal).

`E-I = (external ties − internal ties) / (external ties + internal ties)`

The index runs from −1 (all ties within own gender group) to +1 (all ties outside own gender group). A score near 0 indicates a balanced mix.

The index is not interpreted as an absolute score. A woman with an E-I of −0.4 is not a finding in isolation — it becomes a finding when compared to men at the same seniority level. The operative measure is the **gender delta per seniority band**: women's mean E-I minus men's mean E-I, calculated separately for each seniority level present in the sample.

Interpretation thresholds:

| Delta (women's E-I − men's E-I) | Interpretation                                                                                               |
| ------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| 0 to −0.2                       | Within normal variation — not a structural signal                                                            |
| −0.3 to −0.5                    | Directional signal — women's ties are more gender-homophilous than men's at the same level                   |
| Below −0.5                      | Structural signal — women are forming predominantly same-gender networks while men at the same level are not |

A negative delta means women are more relationally contained within their own gender group than men at equivalent seniority — which in an organization where senior roles are male-dominated structurally limits their access to influence, information, and sponsorship.

Flag as a finding in the report when the delta reaches −0.3 or below at any seniority band. Flag as a significant finding when it reaches −0.5 or below.

**NOTE**:
- In highly male-dominated organizations, **women may have fewer same-gender ties simply because there are fewer women**. The protocol adjusts by seniority band, but small numbers in senior bands can still distort comparisons.
- Homophily is not always negative; it can reflect **support networks** or **mentorship** among women. The protocol acknowledges this implicitly by not interpreting E-I in isolation, but the “structural signal” framing still leans toward seeing same-gender clustering as problematic.

In other words:

- Same-gender clustering can be protective or empowering.
- The concern is when it **co-occurs with** exclusion from influence, projects, and information.

**Average path length by gender**
Steps required to reach a C-suite node, by gender, controlling for seniority level. Longer paths = structural distance from power.

**Informal network metrics (Q6 and Q7)**

Calculate degree centrality separately on the Q6 subgraph (informal pre-meeting consultation ties) and the Q7 subgraph (after-work network ties). Compare gender distributions at each seniority level. A senior woman with high overall degree centrality but low Q6/Q7 degree centrality is structurally included in formal work but excluded from informal influence networks — this is the mechanism finding, not merely the outcome finding.

### 2C. Perception survey scoring

For each block (A through F), calculate:
- Mean score for female respondents
- Mean score for male respondents
- Delta (female mean − male mean)

A negative delta (women scoring lower than men) on any block is a structural signal. The magnitude matters: a delta of −0.5 or more on any block warrants inclusion as a finding. A delta of −1.0 or more is a significant finding.

Reverse-coded items (A2, B3, C4) are flipped before averaging: score = 6 − raw response.

**Triangulation rule:** Any finding presented in the report must be supported by at least two of the three available data sources — network graph structure, perception survey delta, and (if available) email metadata. Single-source signals are noted as preliminary observations.

### 2D. Optional follow-up

Where the perception survey reveals a strong negative delta on any block (≥ −1.0), or where the network graph shows a clear female isolate at a senior level, you may offer a brief 20–30 minute optional call with willing female respondents to probe the specific mechanism. This is not mandatory, does not disrupt business operations, and is strictly opt-in from the respondent's side. It is offered as an opportunity for respondents to add context to the quantitative findings, not as a structured interview. Notes from these calls inform the qualitative narrative in the report but are never attributed.

---

## Phase 3 — Scoring

### Score components Example

**Quantitative component (base 50 points)**

| Criterion | Points | Source | Benchmark basis |
|-----------|--------|--------|-----------------|
| Women hold ≥30% of managerial roles | 20 | HR data | Japan Fifth Basic Plan for Gender Equality (2021), section chief level target |
| Women's average tenure matches or exceeds men's | 15 | HR data | Internal comparator |
| Male parental leave uptake ≥85% of eligible employees | 15 | HR data | Japanese government 2030 target (Cabinet Office) |

**Network and perception component (base 50 points)**

| Criterion | Points | Source |
|-----------|--------|--------|
| Women lead ≥30% of key projects (Q1 collaboration network + E3 survey) | 20 | Network + survey |
| Women report to C-suite at comparable rates to men (Q5 formal control) | 15 | Network |
| Evidence of meaningful responsibility — budget authority or team leadership (E1, E2) | 15 | Survey |

### Tier weighting adjustment

| Tier | Quantitative weight | Network/Perception weight |
|------|--------------------|-----------------------------|
| Tier 3 (50+) | 50% | 50% |
| Tier 2 (20–50) | 40% | 60% |
| Tier 1 (<20) | 30% | 70% |

Multiply each component's raw score by its tier weight before summing. Document the tier weighting applied in the report.

### Score interpretation

| Score | Interpretation |
|-------|---------------|
| 85–100 | Strong alignment. Approved Vendor candidate. |
| 70–84 | Adequate alignment. Minor structural gaps identified. |
| 50–69 | Partial alignment. Significant structural interventions recommended. |
| Below 50 | Poor alignment. Systemic exclusion patterns present. |

Pass threshold for Phase 3 public listing: **70 points.**

---

## Phase 4 — Delivery

### The assessment report

Target length: 12–15 pages excluding appendices.

**Section 1 — Structural snapshot (2 pages)**
The network maps — full graph and gender overlay. Two or three key metrics in plain language. An executive reading this in 3 minutes should understand whether women are structurally central or peripheral.

**Section 2 — Findings by metric (5 pages)**
One page per metric (Collaboration, Communication, Influence, Bridging, Formal Control). Each page: what the network shows, what the perception survey confirms, what structural mechanism is driving the pattern. Where Q6 and Q7 subgraph analysis reveals informal network exclusion as the mechanism, name it explicitly. No individual attribution. Systems, not people.

**Section 3 — Score and rationale (2 pages)**
The score. Tier weighting applied. Which criteria were met and which were not. Note on data quality (response rate, whether email metadata was available).

**Section 4 — Recommended structural interventions (3 pages)**
Three to five specific, actionable recommendations. Not "improve inclusion culture." Specific: *"Restructure project scoping meetings to require written pre-read distribution 48 hours in advance, ensuring all senior employees have equal access to context before decisions are made regardless of informal network proximity."* Structural interventions, not behavioral coaching.

### Delivery meeting

90 minutes. Same attendees as Phase 0 plus owners of the identified structural problems.

- 20 min: walk the network maps live — group reactions to the graph are data
- 30 min: findings by metric, pause for questions after each
- 20 min: score and procurement eligibility implications
- 20 min: recommended interventions and Q&A

---

## Operational Notes for Deployment

**Time budget per assessment by tier:**

| Phase | Tier 1 (<20) | Tier 2 (20–50) | Tier 3 (50+) |
|-------|-------------|----------------|--------------|
| Onboarding | 1.5h | 1.5h | 1.5h |
| Survey prep and distribution | 1h | 1.5h | 2h |
| Data cleaning and graph building | 2–3h | 4–6h | 8–12h |
| Metric calculation and survey analysis | 1–2h | 3–5h | 6–10h |
| Report writing | 4–5h | 5–7h | 7–10h |
| Delivery meeting | 1.5h | 1.5h | 1.5h |
| **Total** | **11–14h** | **17–23h** | **27–38h** |

*Survey prep time increased from v2.0 to account for department dropdown construction from HR org chart data.*

**Response rate floor:** Target 80% of all female employees. Below 70% female response rate, flag the assessment as having degraded validity and note it in the report. Below 50%, escalate to the TMG — this likely reflects a compliance problem, not an operational one.

**Re-identification risk at Tier 1:** In a 12-person company with 3 women, any finding about "women" is potentially re-identifiable by the company. Do not report individual-level perception scores at Tier 1. Report group-level deltas and structural patterns only.

**File hygiene:** Three separate files per assessment: (1) raw survey responses + ID mapping, encrypted; (2) anonymized graph and analysis files; (3) report drafts. Never merge identifiable data with analysis files.

---
