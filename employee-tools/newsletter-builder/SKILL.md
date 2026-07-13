---
name: idm-newsletter-builder
description: >
  Build B2B industrial newsletters for Industrie du Maroc Magazine subscribers.
  Use when creating weekly/monthly newsletters covering Moroccan industry, investment,
  policy, and sector developments. Includes trilingual support, editorial structure,
  and subscriber engagement frameworks.
version: 1.0.0
author: IDM Editorial Department
domain: industrial journalism, newsletter, Morocco
license: MIT (adapted from jamditis/claude-skills-journalism + ur-grue/autopunk-media-skills)
---

# IDM Newsletter Builder

Create professional B2B industrial newsletters that keep Morocco's industrial community informed, engaged, and connected.

## When to Use This Skill

- Creating weekly or monthly industry newsletters
- Building special edition newsletters (event coverage, annual reviews)
- Distributing sector-specific updates (automotive, mining, energy)
- Creating investor-focused newsletters
- Building internal company newsletters for industrial firms

## Newsletter Types

### 1. IDM Weekly Digest
**Frequency:** Weekly
**Length:** 800-1,200 words
**Audience:** General industrial readership
**Language:** French (primary), Arabic and English summaries

### 2. IDM Sector Focus
**Frequency:** Monthly
**Length:** 1,500-2,500 words
**Audience:** Sector specialists
**Language:** Trilingual

### 3. IDM Investment Brief
**Frequency:** Bi-weekly
**Length:** 600-1,000 words
**Audience:** Investors, executives
**Language:** English/French

### 4. IDM Policy Update
**Frequency:** As needed
**Length:** 500-800 words
**Audience:** Government relations, policy analysts
**Language:** French/Arabic

---

## Newsletter Structure

### Standard Template

```markdown
# [IDM Newsletter Title]
## [Issue Number] — [Date]

---

### À la Une / Highlights / أبرز العناوين

[1-2 sentence summary of the most important story]

---

### This Week's Stories

#### [Story 1 Headline]
[2-3 sentence summary with key data point]
[Link to full article]

#### [Story 2 Headline]
[2-3 sentence summary with key data point]
[Link to full article]

#### [Story 3 Headline]
[2-3 sentence summary with key data point]
[Link to full article]

---

### Data Point of the Week / Donnée de la Semaine / بيانات الأسبوع

**[Key statistic]**
[1-2 sentences explaining context and source]

---

### Upcoming Events / Événements à Venir / الأحداث القادمة

- **[Date]** — [Event name] — [Location] — [Brief description]
- **[Date]** — [Event name] — [Location] — [Brief description]

---

### From the Editor / De la Rédaction / من المحرر

[2-3 sentences of editorial commentary or perspective]

---

**Industrie du Maroc**
[Contact information]
[Social media links]
[Subscription management]
```

---

## Content Guidelines

### Story Selection Criteria

| Priority | Type | Weight |
|----------|------|--------|
| 1 | Major industrial announcements | 30% |
| 2 | Investment and trade data | 25% |
| 3 | Policy and regulatory changes | 20% |
| 4 | Sector-specific developments | 15% |
| 5 | Events and community | 10% |

### Writing Style

- **Headlines:** Sentence case, under 10 words
- **Summaries:** 2-3 sentences, include one specific number
- **Tone:** Professional, authoritative, concise
- **Attribution:** Always cite source and date
- **Links:** Always link to full articles or original sources

### Data Points

Include one data point per newsletter:
- Production figures (monthly/quarterly)
- Investment announcements
- Employment data
- Trade statistics
- Energy data

**Format:**
```
**[Number]** — [What it measures]
[1-2 sentences of context]
Source: [Official source], [Date]
```

---

## Trilingual Guidelines

### Headlines
- French: "La production automobile augmente de 8%"
- Arabic: "الإنتاج الصناعي يرتفع 8%"
- English: "Automotive production rises 8%"

### Summaries
- Write in the primary language of the newsletter
- Provide key data in the same format across languages
- Use terminology from IDM-TERMINOLOGY.md

### Event Listings
- List event name in original language
- Provide brief description in newsletter language
- Include location in both local and international formats

---

## Newsletter Sections

### Section 1: Top Story (300-400 words)

**Structure:**
1. Headline (sentence case, under 10 words)
2. Lede (2-3 sentences, most newsworthy element)
3. Key data (specific numbers with source)
4. Context (why this matters)
5. What's next (forward-looking element)
6. Link to full article

### Section 2: Sector Updates (200-300 words each)

**Structure:**
1. Sector name as subhead
2. 2-3 bullet points of key developments
3. One data point per sector
4. Link to full coverage

### Section 3: Data Spotlight (150-200 words)

**Structure:**
1. Bold statistic
2. Source and date
3. Context explanation
4. Comparison to previous period
5. What this means for the industry

### Section 4: Events Calendar (100-200 words)

**Structure:**
- Date
- Event name
- Location
- Brief description (1-2 sentences)
- Registration link if available

### Section 5: Editorial Voice (100-150 words)

**Structure:**
1. Observation or insight
2. Connection to broader trends
3. Forward-looking thought

---

## Email Best Practices

### Subject Line
- Under 50 characters
- Include one specific number or keyword
- No all caps
- No exclamation marks

**Examples:**
- "IDM Weekly: Morocco auto production up 8%"
- "IDM Brief: New phosphate plant opens in Safi"
- "IDM Focus: Renewable energy reaches 4 GW"

### Preview Text
- 40-90 characters
- Complement, don't repeat, subject line
- Create curiosity

### Send Time
- Tuesday or Wednesday, 8-10 AM Morocco time
- Avoid Mondays and Fridays
- Avoid Ramadan and Eid periods

### Formatting
- Mobile-first design
- Short paragraphs (2-3 sentences)
- Bullet points for lists
- Bold for key data
- One clear CTA per section

---

## Subscriber Management

### Audience Segments

| Segment | Content Focus | Language |
|---------|---------------|----------|
| General Industrial | All sectors | French |
| Automotive | Automotive sector | French/English |
| Mining & Energy | Mining, energy | French/Arabic |
| Investment | FDI, financial | English/French |
| Government | Policy, regulation | French/Arabic |

### Personalization

- Use recipient's first name
- Segment by sector interest
- Track engagement for content optimization
- A/B test subject lines

---

## Quality Checklist

Before sending any newsletter:

### Content
- [ ] All stories are from the past 7 days (or relevant time period)
- [ ] All data points are sourced and dated
- [ ] All links work and point to correct destinations
- [ ] No AI writing patterns (idm-ai-writing-detox)
- [ ] Headlines follow IDM style (sentence case, under 10 words)

### Style
- [ ] Consistent tone throughout
- [ ] Professional language
- [ ] No typos or grammatical errors
- [ ] Proper attribution for all claims
- [ ] Data formatted correctly (DH/درهم/MAD, %, etc.)

### Technical
- [ ] Mobile-friendly formatting
- [ ] Images load correctly
- [ ] Unsubscribe link works
- [ ] Physical address included (CAN-SPAM compliance)
- [ ] Test email sent and reviewed

### Trilingual
- [ ] Key terms match IDM-TERMINOLOGY.md
- [ ] Company names use official registered names
- [ ] Government names use official trilingual versions
- [ ] Language is appropriate for audience

---

## Related IDM Skills

- **idm-article-builder** — Build full articles for newsletter links
- **idm-newsroom-style** — Apply style conventions
- **idm-ai-writing-detox** — Remove AI patterns
- **idm-content-repurposer** — Repurpose newsletter content for other channels
- **idm-social-media-publisher** — Promote newsletter on social channels

---

## Skill Metadata

| Field | Value |
|-------|-------|
| version | 1.0.0 |
| created | 2026-07-13 |
| updated | 2026-07-13 |
| author | IDM Editorial Department |
| domain | industrial journalism, newsletter, Morocco |
| complexity | beginner |
| sources adapted from | jamditis/claude-skills-journalism, ur-grue/autopunk-media-skills |
| source license | MIT |
