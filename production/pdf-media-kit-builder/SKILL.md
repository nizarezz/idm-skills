---
name: idm-pdf-media-kit-builder
description: >
  Create professional PDF documents and media kits for Industrie du Maroc Magazine.
  Use when building industrial reports, company profiles, event materials, media kits,
  proposals, or any branded PDF document. Includes IDM brand guidelines, layout templates,
  and trilingual support.
version: 1.0.0
author: IDM Editorial Department
domain: industrial journalism, document design, Morocco
license: MIT (adapted from anthropics/skills)
---

# IDM PDF & Media Kit Builder

Create professional, branded PDF documents that represent Industrie du Maroc Magazine's visual identity and editorial standards.

## When to Use This Skill

- Creating industrial reports or white papers
- Building company profiles or factory reports
- Designing event materials (programs, brochures)
- Creating media kits for IDM
- Building proposals or presentations
- Designing newsletters for print

## IDM Brand Elements

### Colors

| Color | Hex | Use |
|-------|-----|-----|
| Primary Blue | #003366 | Headers, primary elements |
| Secondary Blue | #0066CC | Links, accents |
| Gold | #CC9900 | Highlights, awards |
| Dark Gray | #333333 | Body text |
| Light Gray | #F5F5F5 | Backgrounds |
| White | #FFFFFF | Backgrounds, text on dark |

### Typography

| Element | Font | Size | Weight |
|---------|------|------|--------|
| Main Title | Arial/Helvetica | 28-36pt | Bold |
| Section Title | Arial/Helvetica | 18-24pt | Bold |
| Subsection | Arial/Helvetica | 14-16pt | Semi-bold |
| Body Text | Arial/Helvetica | 10-12pt | Regular |
| Captions | Arial/Helvetica | 8-9pt | Regular |
| Footer | Arial/Helvetica | 7-8pt | Regular |

### Layout Rules

- **Margins:** 2.5 cm (1 inch) on all sides
- **Line spacing:** 1.15-1.5 for body text
- **Paragraph spacing:** 6pt after each paragraph
- **Column width:** Maximum 70 characters per line
- **Page numbers:** Bottom center or bottom right
- **Headers:** Top of each page (except first)

---

## Document Types

### 1. Industrial Report

**Structure:**
```
Cover Page
├── Title
├── Subtitle
├── Date
├── IDM Logo
└── confidentiality notice (if needed)

Table of Contents
├── Executive Summary (1 page)
├── Methodology (if applicable)
├── Main Content (5-20 pages)
├── Data/Charts
├── Conclusions
└── Recommendations

Back Matter
├── Sources
├── About IDM
├── Contact Information
└── Credits
```

**Cover Page Template:**
```markdown
[IDM Logo — top left]

[MAIN TITLE]
[Subtitle in smaller font]

[Date]
[Confidentiality notice if needed]

---
Industrie du Maroc Magazine
www.industriedumaroc.com
```

### 2. Company Profile

**Structure:**
```
Cover Page
├── Company Name
├── Logo (if provided)
├── IDM Branding
└── Date

Company Overview
├── History
├── Mission/Vision
├── Key Figures
└── Leadership

Operations
├── Products/Services
├── Facilities
├── Capacity
└── Markets

Financial Summary
├── Revenue
├── Growth
└── Investment

Sustainability
├── Environmental
├── Social
└── Governance

Contact
├── Headquarters
├── Key Contacts
└── Social Media
```

### 3. Event Materials

**Conference Program:**
```
Cover
├── Event Name
├── Date/Location
├── IDM Branding

Schedule
├── Day 1
├── Day 2
├── Speakers
├── Sponsors

Maps/Floor Plans
├── Venue layout
├── Session rooms
└── Networking areas

Contact
├── Registration
├── Information
└── Emergency
```

### 4. Media Kit

**IDM Media Kit Structure:**
```
Cover
├── IDM Logo
├── "Media Kit 2026"
├── Tagline

About IDM
├── Founded
├── Circulation
├── Readership
├── Mission

Audience
├── Demographics
├── Sectors
├── Geography
├── Decision-makers

Advertising
├── Rates
├── Formats
├── Specifications
├── Deadlines

Editorial Calendar
├── Monthly themes
├── Special issues
├── Events

Contact
├── Sales
├── Editorial
├── Advertising
```

---

## Creating PDF Documents

### Step 1: Plan the Document

```markdown
## Document Plan

### Purpose
- [What is this document for?]
- [Who is the audience?]
- [What action should readers take?]

### Content Outline
1. [Section 1]
2. [Section 2]
3. [Section 3]

### Visual Elements
- [ ] Charts/Graphs needed
- [ ] Photos needed
- [ ] Tables needed
- [ ] Logos needed

### Specifications
- **Page count:** [Number]
- **Language:** [FR / AR / EN]
- **Format:** [A4 / Letter / Custom]
- **Orientation:** [Portrait / Landscape]
```

### Step 2: Create Content

**Writing Guidelines:**
- Use IDM newsroom style
- Follow IDM-TERMINOLOGY.md
- Write in appropriate language for audience
- Keep paragraphs short (2-3 sentences)
- Use bullet points for lists
- Include data sources

### Step 3: Design Layout

**Layout Checklist:**
- [ ] Cover page with IDM branding
- [ ] Consistent headers and footers
- [ ] Page numbers on all pages (except cover)
- [ ] Consistent typography throughout
- [ ] Proper margins and spacing
- [ ] Visual hierarchy (titles → subtitles → body)

### Step 4: Add Visual Elements

**Charts and Graphs:**
- Use IDM color palette
- Include data source attribution
- Simple, clear design
- Labels in appropriate language
- High contrast for readability

**Photos:**
- High resolution (300 DPI minimum)
- Relevant to content
- Properly credited
- IDM brand colors in overlays

**Tables:**
- Clear headers
- Alternating row colors (optional)
- Consistent formatting
- Data sources noted

### Step 5: Review and Export

**Review Checklist:**
- [ ] All text proofread
- [ ] All data verified
- [ ] All images clear
- [ ] All links work (if interactive)
- [ ] Page numbers correct
- [ ] Headers/footers consistent
- [ ] Brand guidelines followed

**Export Settings:**
- Format: PDF
- Quality: High (for print) or Standard (for web)
- Compression: Balance quality and file size
- Security: Password if confidential

---

## Trilingual Document Guidelines

### Cover Pages

**French:**
```
[Logo IDM]
Industrie du Maroc

[TITRE PRINCIPAL]
[Sous-titre]

[Date]
```

**Arabic:**
```
[شعار IDM]
صناعة المغرب

[العنوان الرئيسي]
[العنوان الفرعي]

[التاريخ]
```

**English:**
```
[IDM Logo]
Industrie du Maroc

[MAIN TITLE]
[Subtitle]

[Date]
```

### Headers and Footers

| Element | French | Arabic | English |
|---------|--------|--------|---------|
| Page number | Page [N] | صفحة [N] | Page [N] |
| Date | [Date] | [التاريخ] | [Date] |
| Source | Source: [Name] | المصدر: [الاسم] | Source: [Name] |

---

## Quality Checklist

Before finalizing any PDF document:

### Content
- [ ] All text proofread
- [ ] All data verified and sourced
- [ ] All company names use official registered names
- [ ] All government names use official trilingual versions
- [ ] No AI writing patterns

### Design
- [ ] IDM brand colors used correctly
- [ ] Typography follows brand guidelines
- [ ] Layout is consistent throughout
- [ ] Visual hierarchy is clear
- [ ] White space is used effectively

### Visual Elements
- [ ] All charts/graphs are clear
- [ ] All photos are high resolution
- [ ] All images are properly credited
- [ ] All tables are well-formatted
- [ ] Data sources are attributed

### Technical
- [ ] Page numbers correct
- [ ] Headers/footers consistent
- [ ] File size appropriate
- [ ] PDF is searchable (not scanned image)
- [ ] Links work (if interactive)

### Trilingual
- [ ] Language appropriate for audience
- [ ] Terminology matches IDM-TERMINOLOGY.md
- [ ] Formatting correct for language
- [ ] Right-to-left layout correct (Arabic)

---

## Related IDM Skills

- **idm-newsroom-style** — Apply style conventions
- **idm-article-builder** — Create content for documents
- **idm-editorial-translation** — Translate document content
- **idm-ai-writing-detox** — Remove AI patterns

---

## Skill Metadata

| Field | Value |
|-------|-------|
| version | 1.0.0 |
| created | 2026-07-13 |
| updated | 2026-07-13 |
| author | IDM Editorial Department |
| domain | industrial journalism, document design, Morocco |
| complexity | intermediate |
| source adapted from | anthropics/skills |
| source license | MIT |
