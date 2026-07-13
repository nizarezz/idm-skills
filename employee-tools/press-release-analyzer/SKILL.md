---
name: idm-press-release-analyzer
description: >
  Analyze incoming press releases for Industrie du Maroc Magazine. Extract key claims,
  verify facts, assess newsworthiness, and identify angles for editorial coverage.
  Includes fact-checking frameworks for industrial claims and trilingual support.
version: 1.0.0
author: IDM Editorial Department
domain: industrial journalism, press release analysis, Morocco
license: MIT (custom IDM skill)
---

# IDM Press Release Analyzer

Analyze incoming press releases systematically to determine newsworthiness, extract claims for verification, and identify potential editorial angles.

## When to Use This Skill

- Receiving a press release from a company or government agency
- Evaluating whether to cover a story based on a press release
- Extracting claims that need verification
- Identifying angles for editorial coverage
- Determining if content is genuinely newsworthy or purely promotional

## The Press Release Analysis Framework

### Step 1: Initial Assessment

```markdown
## Press Release Assessment

### Basic Information
- **Source:** [Company/Agency name]
- **Date received:** [Date]
- **Language:** [FR / AR / EN]
- **Contact person:** [Name, title, email, phone]
- **Embargo:** [Yes/No — if yes, until when?]

### Source Classification
- [ ] Government agency
- [ ] Publicly listed company
- [ ] Private company
- [ ] Industry association
- [ ] International organization
- [ ] Other: _______________

### Topic Classification
- [ ] Investment announcement
- [ ] Production milestone
- [ ] Policy announcement
- [ ] Partnership/agreement
- [ ] Executive appointment
- [ ] Event announcement
- [ ] Financial results
- [ ] Other: _______________
```

### Step 2: Claim Extraction

Extract all factual claims that can be verified:

```markdown
## Claims to Verify

### Claim 1
- **Statement:** [Exact quote]
- **Type:** [Production / Investment / Employment / Financial / Policy]
- **Verifiable:** [Yes/No]
- **Source cited:** [What source does the PR cite?]
- **Priority:** [High / Medium / Low]

### Claim 2
- **Statement:** [Exact quote]
- **Type:** [Production / Investment / Employment / Financial / Policy]
- **Verifiable:** [Yes/No]
- **Source cited:** [What source does the PR cite?]
- **Priority:** [High / Medium / Low]

[Continue for all claims]
```

### Step 3: Newsworthiness Assessment

| Criterion | Score (1-5) | Notes |
|-----------|-------------|-------|
| **Timeliness** | | Is this new or just rehashed? |
| **Impact** | | How many people/enterprises affected? |
| **Significance** | | Does this change the industry landscape? |
| **Proximity** | | Is this relevant to Morocco? |
| **Prominence** | | How important is the source? |
| **Conflict/Controversy** | | Is there disagreement or debate? |

**Scoring:**
- 25-30: Major story, cover immediately
- 18-24: Worth covering, develop angle
- 12-17: Consider if other news is slow
- Below 12: Not newsworthy, skip or file for reference

### Step 4: Fact-Check Preparation

```markdown
## Verification Plan

### Claims Requiring Verification
1. [Claim 1] — Check with [Source]
2. [Claim 2] — Check with [Source]
3. [Claim 3] — Check with [Source]

### Official Data Sources to Check
- [ ] HCP (statistical data)
- [ ] Ministry of Industry (policy data)
- [ ] ONHYM (mining/energy data)
- [ ] ANPIMC (investment data)
- [ ] Company official records

### Other Sources to Contact
- [ ] Competitors (for perspective)
- [ ] Industry analysts
- [ ] Government officials
- [ ] Customers/suppliers

### Timeline
- Initial verification: [Date]
- Follow-up with source: [Date]
- Editorial decision: [Date]
```

### Step 5: Editorial Angle Identification

```markdown
## Potential Editorial Angles

### Angle 1: [Name]
- **Perspective:** [How to frame this story]
- **Target audience:** [Who cares about this?]
- **Key questions:** [What readers want to know]
- **Sources needed:** [Who to interview]

### Angle 2: [Name]
- **Perspective:** [How to frame this story]
- **Target audience:** [Who cares about this?]
- **Key questions:** [What readers want to know]
- **Sources needed:** [Who to interview]

### Angle 3: [Name]
- **Perspective:** [How to frame this story]
- **Target audience:** [Who cares about this?]
- **Key questions:** [What readers want to know]
- **Sources needed:** [Who to interview]
```

---

## Claim Verification Checklist

### Investment Claims

| Claim | Verification Method |
|-------|---------------------|
| "Investment of X million DH" | Check ANPIMC, CRI records |
| "Will create X jobs" | Compare with industry benchmarks |
| "Operational by [date]" | Check construction status, previous timelines |
| "First of its kind in Morocco" | Verify against existing facilities |

### Production Claims

| Claim | Verification Method |
|-------|---------------------|
| "Produced X units" | Check HCP industrial indices, company reports |
| "Capacity of X tons/year" | Verify against known facility size |
| "Exported to X countries" | Check EXTT trade data |
| "Record production" | Compare with historical data |

### Policy Claims

| Claim | Verification Method |
|-------|---------------------|
| "Government announced X" | Check Journal Officiel, ministry website |
| "Effective from [date]" | Verify with official gazette |
| "Will benefit X companies" | Check eligibility criteria |
| "Budget of X million DH" | Verify with finance ministry |

### Partnership Claims

| Claim | Verification Method |
|-------|---------------------|
| "Strategic partnership with [Company]" | Verify both companies confirm |
| "Joint venture worth X" | Check official announcements from both parties |
| "MOU signed" | Distinguish MOU from binding agreement |

---

## Red Flags in Press Releases

### Language Red Flags

- "Revolutionary" / "révolutionnaire" / "ثوري" — likely overstated
- "First ever" / "premier" / "أول" — verify against existing facilities
- "World-class" / "de classe mondiale" — vague, often unsubstantiated
- "Game-changer" / "révolution" — editorializing, not fact
- "Groundbreaking" / "innovant" / "مبتكر" — describe what's actually new

### Data Red Flags

- Numbers without sources
- Percentages without base numbers
- Investment amounts without timeline (committed vs. disbursed)
- Employment numbers without category (direct vs. indirect)
- Growth rates without comparison period

### Structural Red Flags

- No contact information for follow-up
- No source cited for key claims
- Embargo with no clear reason
- Timing suspicious (before competitor announcement, during crisis)
- Heavy on superlatives, light on specifics

---

## Press Release Response Template

### If Covering the Story

```markdown
## Coverage Decision: [Topic]

**Source:** [Company/Agency]
**Date:** [Date]
**Decision:** Cover

### Editorial Angle
[Chosen angle from analysis]

### Verification Status
- [ ] Key claims verified
- [ ] Sources contacted for comment
- [ ] Data cross-referenced

### Article Plan
- **Headline:** [Working headline]
- **Structure:** [News/Feature/Analysis]
- **Word count:** [Target]
- **Deadline:** [Date]
- **Author:** [Name]
```

### If Not Covering

```markdown
## Non-Coverage Decision: [Topic]

**Source:** [Company/Agency]
**Date:** [Date]
**Decision:** Do not cover

### Reason
- [ ] Not newsworthy (score below 12)
- [ ] Claims cannot be verified
- [ ] Too promotional, no news value
- [ ] Already covered by other media
- [ ] Not relevant to IDM audience
- [ ] Other: _______________

### Action
- [ ] File for reference
- [ ] Respond to source explaining decision
- [ ] Monitor for future developments
```

---

## Trilingual Analysis

### When Analyzing Press Releases in Different Languages

1. **Extract claims in original language** — preserve exact wording
2. **Verify using official sources** — which may be in different language
3. **Translate key claims for editorial use** — use IDM-TERMINOLOGY.md
4. **Note language of original source** — important for attribution

### Translation Considerations

- Company names: use official registered name (IDM-TERMINOLOGY.md)
- Government names: use official trilingual versions
- Technical terms: use terminology from IDM-TERMINOLOGY.md
- Currency: note original currency, convert if needed

---

## Quality Checklist

Before making editorial decision:

### Assessment
- [ ] Source identified and classified
- [ ] All claims extracted
- [ ] Newsworthiness scored
- [ ] Verification plan created

### Verification
- [ ] Key claims verified against official data
- [ ] Sources contacted for comment
- [ ] Cross-referenced with other sources

### Decision
- [ ] Editorial angle identified
- [ ] Story plan created (if covering)
- [ ] Response to source prepared

---

## Related IDM Skills

- **idm-source-verification** — Verify claims in press releases
- **idm-fact-checker** — Fact-check specific claims
- **idm-story-angle-finder** — Develop editorial angles
- **idm-article-builder** — Build article from verified claims
- **idm-newsroom-style** — Apply style to coverage

---

## Skill Metadata

| Field | Value |
|-------|-------|
| version | 1.0.0 |
| created | 2026-07-13 |
| updated | 2026-07-13 |
| author | IDM Editorial Department |
| domain | industrial journalism, press release analysis, Morocco |
| complexity | beginner |
| source | Custom IDM skill |
| license | MIT |
