---
name: idm-article-builder
description: >
  Build complete industrial journalism articles for Industrie du Maroc Magazine from
  research, angle, and source material. Produces structured articles with verified data,
  proper attribution, trilingual support, and industrial journalism standards. Use when
  you have a story angle and need to develop it into a publishable article.
version: 1.0.0
author: IDM Editorial Department
domain: industrial journalism, article writing, Morocco
license: MIT (adapted from ComposioHQ/awesome-claude-skills)
---

# IDM Article Builder

This skill acts as your writing partner for developing industrial journalism articles from research, angle, and source material into publishable content for Industrie du Maroc Magazine.

## When to Use This Skill

- You have a story angle from idm-story-angle-finder and need to develop it
- You have research and source material and need to structure an article
- You need to create articles with proper industrial data and attribution
- You want to ensure trilingual consistency in your article
- You need section-by-section feedback on an industrial article draft

## What This Skill Does

1. **Structured Outlining:** Helps structure industrial content into coherent outlines
2. **Data Integration:** Incorporates verified industrial data with proper sources
3. **Source Attribution:** Ensures proper attribution for all claims and statistics
4. **Section Feedback:** Reviews each section as you write
5. **Trilingual Consistency:** Maintains terminology from IDM-TERMINOLOGY.md
6. **Citation Management:** Adds and formats references properly
7. **Iterative Refinement:** Helps you improve through multiple drafts

## Article Structures for IDM

### News Article (Inverted Pyramid)

```
# [Headline: Sentence case, present tense]

[LEDE: Who, what, when, where, why — 35 words max]

## Key Facts
- [Most important data point with source]
- [Second data point with source]
- [Third data point with source]

## Context
[Background information, previous developments, industry context]

## Official Response
[Quote from official/executive with full attribution]

## Impact
[What this means for the industry, region, or sector]

## What's Next
[Forward-looking information if available]

---
*Source: [Primary source]*
*Published: [Date]*
```

### Feature Article

```
# [Headline: Engaging, specific, under 12 words]

[HOOK: Anecdote, scene, or question that draws reader in]

## The Situation
[Current state of affairs with data points]

## The Context
[Historical background, industry trends, policy environment]

## The Human Element
[Profiles, quotes, experiences from people involved]

## The Data
[Statistics, charts, analysis with proper sources]

## Expert Analysis
[Industry expert interpretation and context]

## What It Means
[Implications for Moroccan industry]

## What's Next
[Forward-looking conclusion]

---
*Sources: [List of primary sources]*
*Published: [Date]*
```

### Data/Analysis Article

```
# [Headline: Specific finding, not generic]

## Key Finding
[One-sentence summary of the main insight]

## The Data
[Source, methodology, time period]

## Analysis
[Detailed breakdown with charts/graphics]

## Comparison
[Benchmarks, historical trends, regional context]

## Expert Interpretation
[What analysts say about the numbers]

## Implications
[What this means for the industry]

## Methodology Note
[How data was collected and analyzed]

---
*Data Source: [Primary source]*
*Period: [Time frame]*
*Published: [Date]*
```

## Article Building Process

### Step 1: Understand the Assignment

Before writing, clarify:

1. **What is the story about?** (topic/angle)
2. **Who is the audience?** (IDM section, reader profile)
3. **What language?** (FR / AR / EN)
4. **What structure?** (news, feature, analysis)
5. **What is the word count target?**
6. **What is the deadline?**
7. **What sources do you have?**
8. **What sources do you need?**

### Step 2: Build the Outline

Use this template:

```markdown
## Article Outline: [Working Title]

### Headline Options
1. [Option 1]
2. [Option 2]
3. [Option 3]

### Lede (35 words max)
[Draft lede]

### Key Data Points
1. [Data point + source]
2. [Data point + source]
3. [Data point + source]

### Structure
1. [Section 1: Title] — [Word count target]
   - Key point
   - Source needed: [What you need]
2. [Section 2: Title] — [Word count target]
   - Key point
   - Source available: [What you have]
3. [Section 3: Title] — [Word count target]
   - Key point
   - Source needed: [What you need]

### Quotes Needed
1. [Who] — [What perspective]
2. [Who] — [What perspective]

### Research To-Do
- [ ] Find data on [topic]
- [ ] Get quote from [person]
- [ ] Verify [claim]
```

### Step 3: Research and Gather Data

**Primary sources for industrial articles:**

| Data Type | Primary Source |
|-----------|---------------|
| Production figures | HCP industrial indices, company reports |
| Investment data | ANPIMC, CRI records |
| Employment | CNSS, HCP employment surveys |
| Financial | Audited statements, stock exchange filings |
| Policy | Journal Officiel, ministry circulars |
| Trade | EXTT statistics, customs data |
| Energy | ONEE, MASEN data |

**Always document:**
- Source name and date
- Original language of data
- Whether data is preliminary or final
- Any caveats or methodology notes

### Step 4: Write the Lede

The lede is the most important sentence. It must:
- Answer: Who? What? When? Where? Why?
- Be under 35 words
- Include the most newsworthy element
- Use present tense for past events
- Include a specific number if possible

**Good ledes:**

*French:*
> Le secteur automobile marocain a produit 560 000 véhicules au premier semestre 2026, en hausse de 8 %, porté par les exportations vers l'Europe.

*Arabic:*
> أproduced قطاع السيارات المغربي 560 ألف وحدة في النصف الأول من 2026، بزيادة 8% مدفوعةً بالصادرات إلى أوروبا.

*English:*
> Morocco's automotive sector produced 560,000 vehicles in the first half of 2026, up 8%, driven by European exports.

**Bad ledes:**

*Too long:*
> In a significant development for Morocco's industrial sector, which has been growing steadily over the past decade, the automotive industry announced record production figures for the first half of 2026.

*No specifics:*
> The automotive sector continues to grow in Morocco.

*Editorializing:*
> Morocco's automotive sector proved once again why it is one of the most important in Africa.

### Step 5: Build Each Section

For each section of the article:

1. **Start with the key point** — what should the reader remember?
2. **Support with data** — statistics, quotes, documents
3. **Attribute properly** — who said it, when, where
4. **Provide context** — what does this mean?
5. **Transition** — connect to the next section

**Section template:**

```markdown
## [Section Title]

[Key point in 1-2 sentences]

[Supporting data with source]

[Quote from relevant source]

[Context and analysis]

[Transition to next section]
```

### Step 6: Add Proper Attribution

**French:**
- "a déclaré M. [Name], [title] de [organization]"
- "selon les données de [source], datant de [date]"
- "a ajouté Mme [Name], [title]"

**Arabic:**
- "صرح السيد [الاسم]، [المنصب] في [المؤسسة]"
- "ووفقاً لبيانات [المصدر]، بتاريخ [التاريخ]"
- "أضافت السيدة [الاسم]، [المنصب]"

**English:**
- "said [Name], [title] of [organization]"
- "according to [source] data from [date]"
- "added [Name], [title]"

**Always include:**
- Full name on first reference
- Title and organization
- Date of statement (if not in article text)
- Language of original statement (if different from article)

### Step 7: Write the Conclusion

**For news articles:**
- What happens next?
- When is the next decision/meeting/deadline?

**For features:**
- Return to the human element
- Forward-looking statement
- Industry implications

**For analysis:**
- Key takeaway
- What to watch
- Broader context

### Step 8: Add Source List

At the end of every article, document:

```markdown
## Sources

### Primary Sources
1. [Source name] — [What data/info] — [Date] — [Language]
2. [Source name] — [What data/info] — [Date] — [Language]

### Interviews
1. [Name], [Title], [Organization] — [Date] — [Language of interview]
2. [Name], [Title], [Organization] — [Date] — [Language of interview]

### Data
1. [Dataset name] — [Source] — [Period] — [Access date]
2. [Dataset name] — [Source] — [Period] — [Access date]
```

## Quality Checklist

Before submitting any article:

### Content
- [ ] Lede is under 35 words and answers key questions
- [ ] All statistics are sourced and dated
- [ ] All quotes are attributed with full identification
- [ ] Company names use official registered names (IDM-TERMINOLOGY.md)
- [ ] Government names use official trilingual versions
- [ ] All claims are verified (idm-source-verification)

### Style
- [ ] Follows IDM newsroom style guide
- [ ] Headline is sentence case, under 12 words
- [ ] Paragraphs are 1-3 sentences
- [ ] No AI writing patterns (idm-ai-writing-detox)
- [ ] Numbers follow language-specific rules

### Attribution
- [ ] Every statistic has a source and date
- [ ] Every quote has a name, title, and organization
- [ ] Every claim has supporting evidence
- [ ] Sources are credible and independent where possible

### Trilingual
- [ ] Terminology matches IDM-TERMINOLOGY.md
- [ ] Language is appropriate for target audience
- [ ] Technical terms are consistent
- [ ] Currency and units are correctly formatted

### Structure
- [ ] Article follows chosen structure (news/feature/analysis)
- [ ] Sections flow logically
- [ ] Transitions are smooth
- [ ] Conclusion provides closure

## Example: Building a Short News Article

### Input
Topic: New phosphate processing plant opens in Safi
Angle: Government investment in value-added mining
Language: French
Structure: News (inverted pyramid)

### Outline

```markdown
## Article Outline: Nouvelle usine de traitement de phosphates à Safi

### Lede
Une nouvelle usine de traitement de phosphates a été inaugurée mardi à Safi, avec une capacité de 1 million de tonnes par an.

### Key Data Points
1. Capacity: 1 million tonnes/year
2. Investment: 2 billion DH
3. Jobs: 500 direct, 1,200 indirect

### Structure
1. Lede (key facts)
2. Government context (ministry response)
3. Company details (ONHYM, operator)
4. Industry impact (phosphate sector)
5. What's next (expansion plans)

### Quotes Needed
1. Minister of Industry — policy perspective
2. ONHYM director — technical details
3. Plant manager — operational details
```

### Final Article

```markdown
# Nouvelle usine de traitement de phosphates inaugurée à Safi

Une nouvelle usine de traitement de phosphates a été inaugurée mardi à Safi, avec une capacité de production de 1 million de tonnes par an, a annoncé l'Office National des Hydrocarbures et des Mines (ONHYM).

L'installation, qui a coûté 2 milliards de dirhams, créera 500 emplois directs et 1 200 emplois indirects, selon les chiffres officiels.

« Ce projet s'inscrit dans la stratégie nationale de valorisation des ressources minières », a déclaré le ministre de l'Industrie et du Commerce lors de l'inauguration. « Nous voulons passer de l'exportation de matières premières à la production de produits à valeur ajoutée. »

L'usine, exploitée par [Company Name], traitera des phosphates bruts pour produire de l'acide phosphorique et des engrais destinés au marché africain.

Le Maroc est le deuxième producteur mondial de phosphates, avec des réserves estimées à 50 milliards de tonnes, selon les données de l'ONHYM.

La nouvelle installation fait partie d'un programme d'investissement de 10 milliards de dirhams dans le secteur minier, prévu jusqu'en 2030.

---
*Sources: ONHYM, Ministère de l'Industrie et du Commerce, données officielles*
*Publié: [Date]*
```

## Known Limitations

- The assistant does not have access to real-time industrial data — verify all statistics before publication
- The quality of the article depends on the quality of the input sources and research
- For specialized technical content, additional expert review may be needed
- Always verify that company names and government names are current and accurate

## Related IDM Skills

- **idm-story-angle-finder** — Generate angles before building the article
- **idm-source-verification** — Verify claims during research
- **idm-fact-checker** — Fact-check the completed article
- **idm-newsroom-style** — Apply style conventions
- **idm-ai-writing-detox** — Clean AI patterns from the text
- **idm-interview-prep** — Prepare for source interviews

---

## Skill Metadata

| Field | Value |
|-------|-------|
| version | 1.0.0 |
| created | 2026-07-13 |
| updated | 2026-07-13 |
| author | IDM Editorial Department |
| domain | industrial journalism, article writing, Morocco |
| complexity | intermediate |
| source adapted from | ComposioHQ/awesome-claude-skills content-research-writer |
| source license | MIT |
