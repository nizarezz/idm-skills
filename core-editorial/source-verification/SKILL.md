---
name: idm-source-verification
description: >
  Source verification and fact-checking workflows for Industrie du Maroc Magazine.
  Use when verifying industrial claims, checking source credibility, investigating
  company statements, validating production data, or building verification trails
  for articles about Moroccan industry. Adapted from journalism-core source-verification
  with IDM-specific industrial verification frameworks.
version: 1.0.0
author: IDM Editorial Department
domain: industrial journalism, verification, Morocco
license: MIT (adapted from jamditis/claude-skills-journalism)
---

# IDM Source Verification Methodology

Systematic approaches for verifying sources, claims, and data in industrial journalism for the Moroccan market.

## When to Use This Skill

- Verifying company production claims or financial figures
- Checking government statistics on industrial output
- Validating investment announcements
- Investigating executive statements about company performance
- Building verification trails for articles about Moroccan industry
- Confirming regulatory compliance claims
- Verifying employment and workforce data
- Checking environmental impact claims

## The SIFT Method (Adapted for IDM)

**S — Stop**: Never immediately use unverified industrial claims. Production figures, investment amounts, and employment numbers require verification before publication.

**I — Investigate the source**: Who is making this claim? What is their position? Does the company have a track record of accuracy?

**F — Find better coverage**: What do official Moroccan industrial databases say? What do other credible sources report?

**T — Trace claims**: Find the original source — official press release, government gazette, audited financial statements.

## Source Credibility Checklist for Industrial Journalism

```markdown
## Source Evaluation Template — IDM

### Basic Identification
- [ ] Full name of company or organization identified
- [ ] Official registered name verified (use IDM-TERMINOLOGY.md)
- [ ] Contact information verifiable
- [ ] Company registration number confirmed (RC, IF, CNSS)
- [ ] Legal status confirmed (SA, SARL, SAS, etc.)

### Corporate Verification
- [ ] Verified in Registre du Commerce (ONSSA or ONPIMC databases)
- [ ] Tax identification number (IF) confirmed
- [ ] Company actually exists at stated address
- [ ] Not a shell company or dormant entity
- [ ] Industry classification matches claimed activity

### Source Motivation
- [ ] Why is this information being released now?
- [ ] Is this a press release timed to a competitor's announcement?
- [ ] Is the source seeking investment, publicity, or regulatory favor?
- [ ] Does this claim benefit the source commercially?
- [ ] Is there a political motivation?

### Expertise Assessment (for human sources)
- [ ] Title and position verified
- [ ] Relevant expertise for the claim being made
- [ ] Track record in this specific industrial sector
- [ ] Recognized by peers in the Moroccan industrial community
- [ ] No history of spreading misinformation

### Corroboration
- [ ] Can claims be independently verified through official data?
- [ ] Do other credible sources confirm?
- [ ] Is documentary evidence available?
- [ ] Are there contradicting sources?
```

## Moroccan Official Data Sources

### Government Databases

| Source | What It Contains | URL |
|--------|-----------------|-----|
| HCP (Haut-Commissariat au Plan) | National statistics, industrial production indices, census data | `hcp.ma` |
| ANPIMC (Agence Nationale de la Promotion de l'Industrie) | Industrial investment data, company registrations | `invest.gov.ma` |
| ONHYM (Office National des Hydrocarbures et des Mines) | Mining permits, production data, reserves | `onhym.ma` |
| MASEN (Agence Marocaine de l'Énergie Durable) | Renewable energy projects, capacity data | `masen.ma` |
| ONEE (Office National de l'Électricité et de l'Eau Potable) | Electricity production, water supply data | `one.org.ma` |
| ONPIMC (Office de la Propriété Industrielle et Commerciale) | Trademarks, patents, company filings | `ompic.org.ma` |
| Ministère de l'Industrie et du Commerce | Policy documents, regulations, sectoral data | `commerce.gov.ma` |

### International Data Sources

| Source | What It Contains | Use For |
|--------|-----------------|---------|
| World Bank | Morocco country data, industry indicators | Comparative analysis |
| IMF | Morocco economic outlook, investment data | Macroeconomic context |
| UNIDO | Industrial development statistics | International comparisons |
| OECD | Morocco investment policy reviews | Policy analysis |
| ILO | Employment and labor statistics | Workforce data |
| OICA | Global automotive production data | Automotive sector |

### Industry Association Data

| Association | Sector | Use For |
|-------------|--------|---------|
| AMIF (Association des Constructeurs Automobiles) | Automotive | Vehicle production, exports |
| CCG (Casa Blanca Chamber of Commerce) | General | Regional economic data |
| FME (Fédération Marocaine des Entreprises) | General | Business surveys, policy positions |
| AMDIE (Agence Marocaine pour le Développement des Investissements et des Exportations) | Cross-sector | Investment and export data |

## Verification Framework for Industrial Claims

### Production Figures

```markdown
## Production Claim Verification

### Claim Details
- **Company:** [Name]
- **Product:** [What is claimed to be produced]
- **Quantity:** [Number claimed]
- **Period:** [Time frame]
- **Source of claim:** [Where this was stated]

### Verification Steps

1. **Check company's own data**
   - Annual report (if publicly listed)
   - Press release (archived)
   - Official website claims

2. **Cross-reference with government data**
   - HCP industrial production index for the sector
   - Ministry of Industry sectoral reports
   - ONHYM production data (for mining)

3. **Industry context**
   - Does this figure align with sector trends?
   - Is this consistent with known capacity?
   - Compare with similar companies in the sector

4. **Physical verification**
   - Has IDM visited the facility?
   - Can the claim be verified through observable evidence?
   - Are there satellite images, shipping records, or other independent evidence?

### Confidence Assessment
- [ ] Verified through official documents
- [ ] Corroborated by multiple independent sources
- [ ] Consistent with sector data
- [ ] Unverified (cannot confirm or deny)
- [ ] Contradicted by available evidence
```

### Investment Claims

```markdown
## Investment Claim Verification

### Claim Details
- **Investor:** [Company or individual]
- **Amount:** [DH or EUR/USD amount]
- **Sector:** [Industrial sector]
- **Location:** [City/region in Morocco]
- **Timeline:** [When announced]
- **Jobs promised:** [Employment figure if stated]

### Verification Steps

1. **Distinguish committed vs. disbursed**
   - "Announced" ≠ "invested" ≠ "operational"
   - Clarify the stage: announcement, agreement, construction, production

2. **Check official records**
   - ANPIMC investment statistics
   - Regional investment center (CRI) data
   - Free zone authority records (for zones franches)

3. **Verify the investor**
   - Company exists and has financial capacity
   - Track record of similar investments
   - No history of announced but never-executed projects

4. **Timeline verification**
   - When was this originally announced?
   - Is the project on schedule?
   - Has the timeline been revised?

5. **Job claims**
   - Direct vs. indirect employment
   - Permanent vs. temporary positions
   - Compare with industry benchmarks for similar facilities

### Common Pitfalls
- Announced investment ≠ actual investment
- Capacity announced ≠ capacity operational
- "Will create X jobs" often inflated
- Groundbreaking ceremony ≠ construction start
- MOU ≠ binding commitment
```

### Employment Data

```markdown
## Employment Claim Verification

### Claim Details
- **Company:** [Name]
- **Headcount:** [Number claimed]
- **Type:** Direct / Indirect / Temporary
- **Period:** [Date of claim]

### Verification Steps

1. **Company records**
   - CNSS (Caisse Nationale de Sécurité Sociale) registrations
   - Annual report (if listed company)
   - Official company statements

2. **Government data**
   - HCP employment statistics
   - ANPIMC employment data by sector
   - Regional employment office data

3. **Industry benchmarks**
   - Compare with similar companies
   - Check sector employment ratios (employees per unit of production)

4. **Distinguish categories**
   - Direct employees (on company payroll)
   - Indirect employment (supply chain, services)
   - Temporary/contract workers
   - Interns/apprentices

### Red Flags
- Company claims large employment but CNSS registrations are low
- "Job creation" figures include indirect/induced employment without disclosure
- Temporary positions counted as permanent
- Subcontractors' employees counted as direct employees
```

## Digital Verification Techniques

### Company Verification (Morocco-Specific)

```markdown
## Company Verification Checklist

### Legal Status
- [ ] Confirmed in Registre du Commerce (ONSSA)
- [ ] Tax ID (IF) verified
- [ ] Company actually exists and is operational
- [ ] Legal form matches claimed status (SA, SARL, etc.)
- [ ] Registered address matches stated location

### Financial Standing
- [ ] Annual accounts filed (if required by law)
- [ ] No recent bankruptcy or insolvency proceedings
- [ ] Credit rating available (if applicable)
- [ ] Bank references (if claiming financial capacity)

### Operational Status
- [ ] Facility physically exists and is operational
- [ ] Employees are present
- [ ] Products/services are actually being delivered
- [ ] Website and contact information are current

### Sources for Verification
- ONSSA (Registre du Commerce): `registrecommerce.ma`
- ONPIMC: `ompic.org.ma`
- Company website (verify domain registration date)
- LinkedIn company page
- Google Maps/Street View for facility verification
```

### Image and Video Verification for Industrial Content

```markdown
## Industrial Image Verification

### Common Issues with Industrial Images
1. **Old factory photos** used to represent new facilities
2. **Stock photos** presented as actual company operations
3. **Rendered images** presented as completed construction
4. **Other companies' facilities** used to represent claimed operations
5. **AI-generated images** of industrial scenes

### Verification Steps

1. **Reverse image search**
   - Google Images, TinEye, Yandex
   - Check if image appears elsewhere with different context

2. **Metadata analysis**
   - EXIF data: camera, date, GPS coordinates
   - Software used to edit

3. **Content analysis**
   - Does the facility match the claimed location?
   - Are the machines/equipment consistent with the claimed production?
   - Is the signage correct (language, company name)?
   - Do weather/shadows match the claimed date?

4. **Construction progress verification**
   - Satellite imagery (Google Earth, Planet Labs)
   - Construction progress photos over time
   - Compare with announced timeline

### Tools
- Google Earth (historical imagery)
- InVID/WeVerify browser extension
- FotoForensics
- Yandex Images (best for faces if people are in image)
```

### Social Media Verification for Industrial Sources

```markdown
## Social Media Verification for Industrial Accounts

### Account Analysis
- Account age (older = more credible)
- Posting history and consistency
- Follower quality (real accounts vs. bots)
- Interaction patterns

### Content Patterns
- Original content vs. reshared only
- Topics discussed consistently
- Geographic indicators (Morocco-specific content)
- Language consistency (FR/AR/EN)

### Red Flags for Industrial Accounts
- Recently created account making major claims
- Sudden pivot in topics (e.g., from food to automotive)
- Coordinated behavior with other suspicious accounts
- Generic stock photo profile picture
- No verifiable employees behind the account
- Claims production figures that don't match HCP data

### Cross-Reference
- LinkedIn company page (employees, history)
- Company website
- Government registries
- Industry association membership
```

## Building a Verification Trail

### Documentation Template

```markdown
## IDM Verification Record

**Claim being verified:**
[State the specific claim in the original language]

**Source of claim:**
- Name/organization:
- Official position:
- Platform/media:
- Date first seen:
- URL (archived):
- Language of original claim: [FR / AR / EN]

**Verification steps taken:**

### Step 1: [Description]
- Action taken:
- Tool/method used:
- Result:
- Evidence saved: [filename]

### Step 2: [Description]
- Action taken:
- Tool/method used:
- Result:
- Evidence saved: [filename]

[Continue for each step]

**Corroborating sources:**
1. [Source 1] - [What it confirms] - [Language]
2. [Source 2] - [What it confirms] - [Language]
3. [Source 3] - [What it confirms] - [Language]

**Contradicting information:**
1. [Source] - [What it contradicts]

**Official data cross-reference:**
- HCP data: [relevant statistics]
- Ministry data: [relevant data]
- Industry association data: [relevant data]

**Confidence assessment:**
- [ ] Verified true (official documents confirm)
- [ ] Likely true (multiple independent sources)
- [ ] Unverified (insufficient evidence)
- [ ] Likely false (contradicting evidence)
- [ ] Verified false (official sources contradict)

**Reasoning:**
[Explain conclusion based on evidence]

**Verification completed by:**
**Date:**
**Language of article:** [FR / AR / EN]
```

## Archiving Evidence

### Web Archiving Best Practices

Archive every primary-source URL the moment you decide it might appear in the story. Pages disappear, get edited, or go behind paywalls.

**Minimum: archive to two services simultaneously:**

1. **Wayback Machine:** `web.archive.org/save/[URL]`
2. **Archive.today:** `archive.ph/submit/?url=[URL]`

**For official Moroccan government pages:**
- Government websites change without notice
- Archive ministerial announcements immediately
- Save PDFs of official gazette (Journal Officiel) articles

**For company announcements:**
- Archive press releases from company websites
- Save LinkedIn posts from company executives
- Capture social media announcements

### Screenshot Documentation

For critical evidence:
1. Full-page screenshot with URL bar visible
2. Timestamp visible or noted
3. Save as PNG (lossless)
4. Note exact date and time of capture
5. Store with verification record

## Verification Resources for Moroccan Industry

### Tools

| Tool | Purpose | URL |
|------|---------|-----|
| ONSSA Registre du Commerce | Company verification | `registrecommerce.ma` |
| ONPIMC | IP and company filings | `ompic.org.ma` |
| HCP Statistics | Industrial data | `hcp.ma` |
| Google Earth | Facility verification | `earth.google.com` |
| InVID/WeVerify | Video/image verification | `weverify.eu` |
| TinEye | Reverse image search | `tineye.com` |
| Yandex Images | Reverse image search | `yandex.com/images` |
| Wayback Machine | Web archives | `web.archive.org` |
| Archive.today | Web archives | `archive.ph` |
| FotoForensics | Image analysis | `fotoforensics.com` |

### Training Resources

- Bellingcat guides: `bellingcat.com/resources`
- Verification Handbook: `verificationhandbook.com`
- Google News Initiative: `newsinitiative.withgoogle.com`
- SPJ ethics resources: `spj.org/ethics`
- Moroccan Press Code (Code de la Presse)

## Related IDM Skills

- **idm-fact-checker** — Structured claim verification and rating workflows
- **idm-ai-writing-detox** — Eliminate AI patterns from verified content
- **idm-newsroom-style** — IDM house style for final output
- **idm-interview-prep** — Pre-interview research for industrial sources
- **idm-pre-publication-review** — Final verification before publication

---

## Skill Metadata

| Field | Value |
|-------|-------|
| version | 1.0.0 |
| created | 2026-07-13 |
| updated | 2026-07-13 |
| author | IDM Editorial Department |
| domain | industrial journalism, verification, Morocco |
| complexity | intermediate |
| source adapted from | jamditis/claude-skills-journalism source-verification |
| source license | MIT |
