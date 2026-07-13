---
name: idm-fact-checker
description: >
  Structured workflow for fact-checking industrial claims for Industrie du Maroc Magazine.
  Use when verifying production figures, investment claims, employment data, government
  statistics, or executive statements for publication. Includes claim extraction, evidence
  gathering, rating scales, and correction protocols adapted for Moroccan industrial journalism.
version: 1.0.0
author: IDM Editorial Department
domain: industrial journalism, fact-checking, Morocco
license: MIT (adapted from jamditis/claude-skills-journalism)
---

# IDM Fact-Checker Workflow

Fact-checking is systematic, not intuitive. This skill provides structure for claim verification, evidence documentation, and rating decisions specific to industrial journalism in Morocco.

## When to Use This Skill

- Pre-publication fact-checking of articles
- Verifying executive statements during reporting
- Checking government statistics on industrial output
- Validating investment and employment claims
- Building fact-checking protocols for the IDM newsroom
- Training staff on verification standards for industrial content

## The IDM Fact-Check Process

```
1. Identify claim → 2. Classify claim type → 3. Research claim →
4. Gather evidence → 5. Contact sources → 6. Rate/verify → 7. Document → 8. Publish/correct
```

## Step 1: Claim Extraction

### What to Check (Industrial Claims)

**Check:**
- Production quantities and volumes
- Investment amounts and timelines
- Employment figures (direct, indirect, temporary)
- Export/import volumes and values
- Financial performance (revenue, profit, growth)
- Government policy effects on industry
- Technical specifications of facilities
- Regulatory compliance claims
- Market share claims
- Environmental impact claims

**Don't Check (Opinions):**
- "This policy is good/bad for industry"
- "We should invest more in renewables"
- Predictions about future market conditions
- Matters of editorial judgment

### Claim Extraction Template

```markdown
## IDM Claim Log

**Article/Source:** [Title of article or source]
**Date:** [Date of claim]
**Language:** [FR / AR / EN]
**Sector:** [Automotive, Mining, Energy, etc.]

### Claim 1
- **Statement:** [Exact quote or paraphrase]
- **Speaker:** [Who said it]
- **Position:** [Title and organization]
- **Context:** [Surrounding context]
- **Type:** [Production / Investment / Employment / Financial / Policy / Technical]
- **Priority:** [High / Medium / Low]
- **Status:** [Pending / Verified / False / Unverifiable]

### Claim 2
[Same structure]
```

### Prioritizing Claims

| Priority | Criteria |
|----------|----------|
| **High** | Central to the story's thesis, easily checkable, high consequence if wrong |
| **Medium** | Supporting detail, takes more effort to verify |
| **Low** | Peripheral detail, commonly accepted, minimal consequence |

**Always check high-priority claims first. Check all claims if time allows.**

## Step 2: Classify Claim Type

### Industrial Claim Categories

| Claim Type | Examples | Primary Sources |
|------------|----------|-----------------|
| **Production** | "We produced 50,000 vehicles last month" | Company reports, HCP industrial indices, AMIF data |
| **Investment** | "We invested 2 billion DH in this facility" | ANPIMC records, CRI data, company filings |
| **Employment** | "We employ 3,000 workers" | CNSS registrations, company records, HCP data |
| **Financial** | "Revenue grew 15% year-over-year" | Audited financial statements, Casablanca Stock Exchange filings |
| **Policy** | "This regulation will create 10,000 jobs" | Official government gazette, ministry statements |
| **Technical** | "This plant produces 200,000 tons annually" | Engineering specifications, capacity studies |
| **Environmental** | "We reduced carbon emissions by 30%" | Environmental impact assessments, ONEE data |
| **Trade** | "Exports to Europe increased 25%" | ONPIMC customs data, EXTT (Office des Changes) |

## Step 3: Research the Claim

### Primary Sources First

| Claim Type | Primary Sources |
|------------|-----------------|
| Production figures | Company annual report, HCP industrial production index |
| Investment data | ANPIMC investment statistics, CRI records, official announcements |
| Employment | CNSS registrations, company payroll records, HCP employment surveys |
| Financial | Audited financial statements, stock exchange filings |
| Policy | Journal Officiel (official gazette), ministry circulars |
| Technical | Engineering reports, capacity assessments, technical documentation |
| Environmental | Environmental impact assessments, ONEE data, ministry reports |
| Trade | EXTT (Office des Changes) statistics, customs data |

### Secondary Source Evaluation

If primary sources unavailable:
- How close is the secondary source to the original?
- Does it cite its sources?
- Do multiple independent sources confirm?
- Is there contradicting coverage?
- Is the source's track record reliable?

### Research Documentation Template

```markdown
## Research for Claim: [Brief description]

### Primary sources checked
| Source | What it says | Confirms/Contradicts | Language |
|--------|--------------|---------------------|----------|
| [source] | [finding] | [confirms/contradicts/partial] | [FR/AR/EN] |

### Secondary sources checked
| Source | What it says | Reliability | Language |
|--------|--------------|-------------|----------|
| [source] | [finding] | [high/medium/low] | [FR/AR/EN] |

### Official data cross-reference
- HCP data: [relevant statistics]
- Ministry data: [relevant data]
- Industry association: [relevant data]

### Gaps in evidence
- [What you couldn't find]
- [What you still need]
```

## Step 4: Evidence Gathering

### Types of Evidence (Ranked by Strength)

| Evidence Type | Strength | Notes |
|---------------|----------|-------|
| Audited financial statements | Strong | Verified by independent auditor |
| Official government data | Strong | HCP, ministries, ONHYM |
| Primary datasets | Strong | Original data, your own analysis |
| On-record expert sources | Medium | Named source with direct knowledge |
| Company press releases | Medium | Official but self-serving |
| Contemporary news accounts | Medium | Coverage from the time |
| Off-record sources | Weak | Use to guide reporting, not as evidence |
| Social media posts | Weak | Can be deleted, context matters |
| Anonymous claims | Very weak | Cannot be used as sole evidence |

### Evidence Checklist

```markdown
## Evidence for: [Claim]

### Documentary evidence
- [ ] Company official records (annual report, press release)
- [ ] Government records (HCP, ministry, ONHYM)
- [ ] Industry association data (AMIF, CCG, FME)
- [ ] International organization data (World Bank, IMF, UNIDO)
- [ ] Audited financial statements (if company is listed)

### Human sources
- [ ] Direct witnesses (employees, managers)
- [ ] Subject matter experts (industry analysts, academics)
- [ ] Involved parties (on record)
- [ ] Involved parties (for response)

### Data verification
- [ ] Original dataset obtained
- [ ] Methodology reviewed
- [ ] Calculations independently verified
- [ ] Sample size adequate (for surveys)

### Contradicting evidence
- [ ] Searched for conflicting sources
- [ ] Contradictions documented
- [ ] Discrepancies explained
```

## Step 5: Contact Sources

### Right of Response

**Always contact:**
- People/organizations being fact-checked
- Give specific claims you're checking
- Give reasonable deadline (24-48 hours minimum)
- Document their response (or non-response)

### Source Contact Template (Trilingual)

**French:**
```
Objet: Demande de commentaire — Vérification factuelle [Industrie du Maroc]

Madame, Monsieur,

Je suis [nom] de la rédaction d'Industrie du Maroc et je travaille sur une vérification factuelle de [contexte].

Plus spécifiquement, j'examine cette affirmation :

« [Citation exacte de l'affirmation] »

Je souhaite vous donner l'opportunité de fournir des éléments de preuve, de clarifier le contexte ou d'apporter des corrections.

Ma date limite est le [date/heure]. N'hésitez pas à me contacter si vous avez besoin de plus de temps.

Cordialement,
[Votre nom]
[Coordonnées]
```

**Arabic:**
```
الموضوع: طلب تعليق — التحقق من الوقائع [صناعة المغرب]

سيدتي / سيدي،

أنا [الاسم] من تحرير مجلة صناعة المغرب وأعمل على التحقق من الوقائع المتعلقة بـ [السياق].

على وجه التحديد، أدرس هذا الادعاء:

"[الاقتباس الدقيق من الادعاء]"

أريد أن أمنحك الفرصة لتقديم أي أدلة داعمة، أو توضيح السياق، أو تقديم أي تصحيحات.

موعد النهاية هو [التاريخ/الوقت]. يرجى التواصل معي إذا كنت بحاجة إلى مزيد من الوقت.

مع تحياتي،
[اسمك]
[معلومات الاتصال]
```

**English:**
```
Subject: Request for comment — Fact-check [Industrie du Maroc]

Dear [Name],

I am a journalist with Industrie du Maroc working on a fact-check of [context].

Specifically, I am examining this claim:

"[Exact claim being checked]"

I want to give you the opportunity to provide evidence supporting this claim, clarify the context, or offer any corrections.

My deadline is [date/time]. Please let me know if you need more time.

Best regards,
[Your name]
[Contact information]
```

### Document Responses

```markdown
## Source Response Log

### [Source name]
- **Organization:** [Company/institution]
- **Position:** [Title of person contacted]
- **Contacted:** [Date/time, method]
- **Deadline given:** [Date/time]
- **Response received:** [Date/time] / No response
- **Language of response:** [FR / AR / EN]
- **Summary:** [What they said]
- **Evidence provided:** [Any documentation]
- **Direct quote for publication:** "[Quote in original language]"
```

## Step 6: Rating the Claim

### Standard Rating Scales

**Binary (internal fact-checking):**
- Verified
- False
- Unverifiable

**Graduated (for fact-check articles):**

| Rating | Criteria |
|--------|----------|
| **True (Vrai / صحيحة)** | Accurate and complete, nothing significant omitted |
| **Mostly true (Plutôt vrai / صحيحة في الغالب)** | Accurate but needs context or minor clarification |
| **Half true (Mi-true / نصف صحيحة)** | Partially accurate but leaves out critical context |
| **Mostly false (Plutôt faux / خاطئة في الغالب)** | Contains some truth but overall misleading |
| **False (Faux / خاطئة)** | Not accurate; contradicted by evidence |
| **Pants on fire (Faux grotesque / خاطئة كلياً)** | Not accurate AND deliberately misleading |

### Rating Decision Template

```markdown
## Rating Decision: [Claim]

**Claim:** [Exact statement]
**Speaker:** [Who said it]
**Our rating:** [Rating in FR / AR / EN]

### Evidence supporting the claim
- [Evidence 1]
- [Evidence 2]

### Evidence contradicting the claim
- [Evidence 1]
- [Evidence 2]

### Key context missing from the claim
- [Context 1]
- [Context 2]

### Source response
[What they said when contacted]

### Official data cross-reference
- HCP data: [relevant finding]
- Ministry data: [relevant finding]

### Reasoning
[Explain why this rating, not another]

### Confidence level
[High / Medium / Low and why]
```

## Step 7: Documentation

### The IDM Fact-Check File

For every claim verified, maintain:

```markdown
## IDM Fact-Check Record

**Claim:** [Exact statement]
**Source:** [Who said it, where, when]
**Language:** [FR / AR / EN]
**Sector:** [Industrial sector]
**Checked by:** [Your name]
**Date checked:** [Date]

### Verification
**Rating:** [Rating]
**Primary evidence:** [List with links/locations]
**Supporting evidence:** [List]
**Contradicting evidence:** [If any]

### Official data cross-reference
- HCP: [Relevant data]
- Ministry: [Relevant data]
- Industry association: [Relevant data]

### Sources contacted
- [Name]: [Response summary]

### Notes
[Any additional context, caveats]

### Files
[List of saved documents, screenshots, archives]
```

### Archiving Evidence

- Save screenshots with timestamps
- Archive web pages (Wayback Machine, Archive.today)
- Download documents (don't just link)
- Keep original files separate from analysis
- Note language of each piece of evidence

## Step 8: Corrections

### When to Correct

| Situation | Action |
|-----------|--------|
| Factual error | Correct immediately, note correction |
| Missing context | Add context, may not need formal correction |
| Updated information | Update, note "Mis à jour: [date]" |
| Source disputes characterization | Evaluate claim, correct if warranted |

### Correction Template (Trilingual)

**French:**
```
Correction [date] : Une version précédente de cet article affirmait [affirmation incorrecte].
Or, [information correcte]. Nous regrettons l'erreur.
```

**Arabic:**
```
تصحيح [التاريخ]: ذكرت نسخة سابقة من هذا المقال [الادعاء غير الصحيح].
في الواقع، [المعلومات الصحيحة]. نأسف للخطأ.
```

**English:**
```
Correction [date]: An earlier version of this article stated [incorrect claim].
In fact, [correct information]. We regret the error.
```

### Correction Log

```markdown
## Correction Record

**Article:** [Title / URL]
**Original publication:** [Date]
**Error discovered:** [Date]
**Error type:** [Factual / Context / Attribution / Other]

**Original text:**
[What was published]

**Corrected text:**
[What it now says]

**How discovered:**
[Reader tip, internal review, source complaint, etc.]

**Correction published:** [Date]
**Location:** [In article, separate correction page, both]
**Language(s):** [FR / AR / EN]
```

## Pre-Publication Checklist

Before any story publishes:

```markdown
## IDM Pre-Publication Fact-Check

**Article:** [Title]
**Language(s):** [FR / AR / EN]
**Reporter:** [Name]
**Editor:** [Name]
**Fact-checker:** [Name, if separate]
**Publish date:** [Date]

### Claims verified
| Claim | Status | Evidence | Notes |
|-------|--------|----------|-------|
| [Claim 1] | Verified | [Source] | |
| [Claim 2] | Verified | [Source] | |

### Sources contacted for comment
| Source | Contacted | Response |
|--------|-----------|----------|
| [Name] | [Date] | [Received / No response] |

### Numbers and statistics
- [ ] All statistics sourced and dated
- [ ] Calculations independently verified
- [ ] Context provided (per capita, adjusted, etc.)
- [ ] Currency correctly stated (DH, EUR, USD)
- [ ] Units correct (tons, kW, vehicles, etc.)

### Quotes
- [ ] All quotes verified against recording/transcript
- [ ] Attribution is accurate
- [ ] Context preserved
- [ ] Original language preserved (if translated)

### Names and titles
- [ ] All names spelled correctly (use IDM-TERMINOLOGY.md)
- [ ] Titles current and accurate
- [ ] Company names use official registered names
- [ ] Ministry names use official trilingual versions

### Legal review (if applicable)
- [ ] Defamation risk assessed
- [ ] All claims supported by evidence
- [ ] Response from subjects documented

### Language consistency
- [ ] Terminology matches IDM-TERMINOLOGY.md
- [ ] Trilingual consistency (if applicable)
- [ ] Numbers formatted per IDM brand guide

### Sign-off
**Reporter:** [Name, date]
**Editor:** [Name, date]
**Fact-checker:** [Name, date]
```

## Fact-Check Article Structure

For dedicated fact-check stories:

```markdown
# [Headline: Claim being checked]

**Claim (FR):** [Exact claim in French]
**Claim (AR):** [Exact claim in Arabic]
**Claim (EN):** [Exact claim in English]
**Source:** [Who said it, where, when]
**Our rating (FR):** [Rating]
**Our rating (AR):** [Rating]
**Our rating (EN):** [Rating]

## What was said (Ce qui a été dit / ما قيل)
[Context of the claim, full quote, circumstances]

## What the evidence shows (Ce que montrent les preuves / ما تظهره الأدلة)
[Present evidence for and against]

## The verdict (La conclusion / الخلاصة)
[Explanation of rating decision]

## Sources (Sources / المصادر)
[List all sources with links]

---
*Publié: [date] | Mis à jour: [date if applicable]*
*نُشر: [التاريخ] | تم التحديث: [التاريخ]*
*Published: [date] | Updated: [date if applicable]*
```

---

## Skill Metadata

| Field | Value |
|-------|-------|
| version | 1.0.0 |
| created | 2026-07-13 |
| updated | 2026-07-13 |
| author | IDM Editorial Department |
| domain | industrial journalism, fact-checking, Morocco |
| complexity | intermediate |
| source adapted from | jamditis/claude-skills-journalism fact-check-workflow |
| source license | MIT |

*The goal is accuracy. Vérifier avant de publier. تحقق قبل النشر.*
