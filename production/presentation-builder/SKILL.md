---
name: idm-presentation-builder
description: >
  Create professional HTML presentations for Industrie du Maroc Magazine.
  Use when building industrial reports, company profiles, sector analyses,
  event presentations, or any multi-page visual content. Follows IDM brand
  guidelines with trilingual support (French, Arabic, English).
version: 1.0.0
author: IDM Editorial Department
domain: industrial journalism, presentation design, Morocco
license: MIT (adapted from ppt-agent-skill)
---

# IDM Presentation Builder

Create professional, branded presentations that represent Industrie du Maroc Magazine's visual identity.

## When to Use This Skill

- Creating industrial sector reports with data visualization
- Building company profiles or factory presentations
- Designing event materials (conferences, workshops)
- Preparing editorial team presentations
- Creating investor-facing industry overviews
- Building training materials for staff

## Core Principles

1. **Research first** — Use real data from Moroccan sources, never fabricate
2. **Content drives design** — Layout follows content, not the reverse
3. **Brand consistency** — IDM colors and typography throughout
4. **Trilingual support** — French primary, Arabic and English as needed
5. **Data visualization** — Charts and graphs for industrial data

---

## IDM Brand Guidelines

### Colors

| Color | Hex | Use |
|-------|-----|-----|
| Primary Blue | #003366 | Headers, primary elements |
| Secondary Blue | #0066CC | Links, accents, interactive |
| Gold | #CC9900 | Highlights, awards, emphasis |
| Dark Gray | #333333 | Body text |
| Light Gray | #F5F5F5 | Backgrounds, subtle elements |
| White | #FFFFFF | Backgrounds, text on dark |

### Typography

| Element | Font | Size | Weight |
|---------|------|------|--------|
| Main Title | Arial/Helvetica | 36-48pt | Bold |
| Section Title | Arial/Helvetica | 24-32pt | Bold |
| Subsection | Arial/Helvetica | 18-20pt | Semi-bold |
| Body Text | Arial/Helvetica | 14-16pt | Regular |
| Data Labels | Arial/Helvetica | 12-14pt | Regular |
| Captions | Arial/Helvetica | 10-12pt | Regular |

### Layout Rules

- **Slide size:** 1280x720px (16:9)
- **Margins:** 60px on all sides
- **Line spacing:** 1.4 for body text
- **Maximum lines per slide:** 8-10
- **Color usage:** Never hardcode — use CSS variables

---

## 6-Step Workflow

### Step 1: Requirements Gathering

**Always ask before creating.** Never skip this step.

**Questions to ask:**

| Layer | Question | Purpose |
|-------|----------|---------|
| Context | What is the presentation for? (conference, report, training) | Information density |
| Audience | Who will see this? (executives, engineers, investors) | Technical depth |
| Content | What data/sections should be included? | Structure |
| Style | Any specific visual preferences? | Design direction |
| Languages | French, Arabic, English, or multilingual? | Text handling |

**Output:** Requirements JSON with topic, audience, sections, languages

---

### Step 2: Research & Data Collection

**Use all available sources.**

1. Search for topic background (3-5 queries)
2. Find relevant Moroccan industrial data
3. Identify key statistics from official sources:
   - HCP (Haut-Commissariat au Plan)
   - ONHYM (Office National des Hydrocarbures et des Mines)
   - AMIF (Agence Marocaine d'Investissement et de Exportations)
   - Ministry of Industry
   - Sector associations (AMIF, CCG, FME, etc.)

**Output:** Research summary with data points and sources

---

### Step 3: Outline Creation

**Structure using pyramid principle:** Conclusion first, grouped by theme, logical progression.

**Typical IDM presentation structure:**

```
1. Cover Slide
2. Executive Summary (1 slide)
3. Section 1: Context/Background (2-3 slides)
4. Section 2: Data & Analysis (3-5 slides)
5. Section 3: Key Findings (2-3 slides)
6. Section 4: Recommendations (1-2 slides)
7. Sources & Methodology (1 slide)
8. Contact/End Slide
```

**Output:** `[PRESENTATION_OUTLINE]` JSON

---

### Step 4: Content Planning

**Map research to each slide.**

For each slide, define:
- **Title:** Clear, concise header
- **Content:** Key points (3-5 per slide)
- **Data:** Statistics, charts, or figures
- **Visual:** Chart type, image placement, or layout

**Card types available:**
- `text` — Standard text content
- `data` — Statistics and numbers
- `chart` — Visual data representation
- `quote` — Executive or expert quotes
- `list` — Bullet points or steps
- `comparison` — Before/after, side-by-side
- `timeline` — Chronological data

**Output:** `planning.json` with slide-by-slide content

---

### Step 5: Design Generation

#### 5a. Style Decision

**IDM Default Style:**
```json
{
  "name": "idm-professional",
  "colors": {
    "primary": "#003366",
    "secondary": "#0066CC",
    "accent": "#CC9900",
    "background": "#FFFFFF",
    "text": "#333333"
  },
  "typography": {
    "heading": "Arial, Helvetica, sans-serif",
    "body": "Arial, Helvetica, sans-serif"
  }
}
```

#### 5b. Slide Generation

**Generate one HTML file per slide.**

**Canvas:** 1280x720px, overflow:hidden

**CSS Variables (required):**
```css
:root {
  --idm-primary: #003366;
  --idm-secondary: #0066CC;
  --idm-accent: #CC9900;
  --idm-bg: #FFFFFF;
  --idm-text: #333333;
  --idm-light: #F5F5F5;
}
```

**Layout options:**
- `single-focus` — One main point, centered
- `two-column` — Split content
- `hero-image` — Large image with text overlay
- `data-dashboard` — Multiple charts/metrics
- `timeline` — Chronological progression

**Output:** One HTML file per slide in `slides/` directory

---

### Step 6: Post-Processing

**After all slides are generated:**

1. **Create preview** — Combine slides into scrollable preview
2. **Export options:**
   - HTML files (individual slides)
   - Combined preview.html
   - Screenshots for social media
   - PDF export (if tool available)

**Output structure:**
```
presentation-output/
  slides/           # Individual HTML slides
  preview.html      # Combined scrollable view
  images/           # Any images used
  presentation.pdf  # PDF export (if available)
```

---

## Slide Templates

### Cover Slide

```html
<div class="slide cover">
  <div class="logo">Industrie du Maroc</div>
  <h1 class="main-title">[TITLE]</h1>
  <p class="subtitle">[SUBTITLE]</p>
  <div class="divider"></div>
  <p class="date">[DATE]</p>
  <p class="footer">Industrie du Maroc Magazine</p>
</div>
```

### Data Slide

```html
<div class="slide data-slide">
  <h2 class="slide-title">[TITLE]</h2>
  <div class="data-grid">
    <div class="metric-card">
      <span class="value">[VALUE]</span>
      <span class="label">[LABEL]</span>
    </div>
    <!-- Repeat for each metric -->
  </div>
  <p class="source">Source: [SOURCE]</p>
</div>
```

### Content Slide

```html
<div class="slide content-slide">
  <h2 class="slide-title">[TITLE]</h2>
  <div class="content-area">
    <ul class="points">
      <li>[Point 1]</li>
      <li>[Point 2]</li>
      <li>[Point 3]</li>
    </ul>
    <div class="chart-area">
      <!-- Chart or image -->
    </div>
  </div>
</div>
```

---

## Chart Types for Industrial Data

| Chart Type | Use Case | Example |
|------------|----------|---------|
| Bar Chart | Production comparison | Vehicle output by factory |
| Line Chart | Trends over time | Investment growth 2020-2025 |
| Pie Chart | Market share | Export destinations |
| KPI Card | Key metrics | Revenue, employees, capacity |
| Table | Detailed data | Financial comparisons |
| Timeline | Milestones | Project phases |

---

## Moroccan Data Sources

Always cite official sources:

| Source | Data Type | Website |
|--------|-----------|---------|
| HCP | Statistics, GDP, employment | hcp.ma |
| ONPIMC | Trade data | onpimc.org |
| AMIF | Foreign investment | amif.ma |
| ONHYM | Mining, energy | onhym.ma |
| MASEN | Renewable energy | masen.ma |
| ONEE | Electricity, water | onee.ma |
| Ministry of Industry | Policy, regulations | mi.gov.ma |

---

## Quality Checklist

Before finalizing:

### Content
- [ ] All data sourced and dated
- [ ] Company names use official registered names
- [ ] Government names use official trilingual versions
- [ ] No AI writing patterns

### Design
- [ ] IDM brand colors used correctly
- [ ] Typography consistent throughout
- [ ] Layout follows visual hierarchy
- [ ] White space used effectively

### Technical
- [ ] CSS variables used (no hardcoded colors)
- [ ] All slides 1280x720px
- [ ] Images are high resolution
- [ ] Source citations included

---

## Example Prompts

**Create sector report:**
```
Create a 12-slide presentation on Morocco's automotive sector in 2025.
Include production data, key players, export destinations, and investment outlook.
Use IDM brand guidelines.
```

**Company profile:**
```
Build a company profile presentation for OCP Group.
Cover history, operations, financials, sustainability, and contact information.
French language, 10 slides.
```

**Event presentation:**
```
Create a conference presentation on renewable energy in Morocco.
15 slides, include statistics from MASEN and ONEE.
Bilingual French/Arabic.
```

---

## Skill Metadata

| Field | Value |
|-------|-------|
| version | 1.0.0 |
| created | 2026-07-13 |
| updated | 2026-07-13 |
| author | IDM Editorial Department |
| domain | industrial journalism, presentation design, Morocco |
| complexity | intermediate |
| source adapted from | ppt-agent-skill |
| source license | MIT |

*Professional presentations for Moroccan industrial journalism.*
