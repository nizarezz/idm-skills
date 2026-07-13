# Industrie du Maroc — Skills Catalogue

## Overview

This catalogue contains AI-assisted skills adapted for Industrie du Maroc Magazine's industrial journalism needs. Each skill is a self-contained Markdown prompt that can be used in Claude, ChatGPT, or any AI assistant.

**Total skills:** 15 skills + 2 reference documents
**Languages:** French, Arabic, English
**License:** MIT (adapted from open-source repositories)

---

## Guide en français

**[Guide des Compétences IDM →](GUIDE-COMPETENCES.md)**

Comment et quand utiliser chaque compétence — en français pour les employés.

---

## How to Use These Skills

### Option 1: Copy and Paste
1. Open the skill file you want
2. Copy the content (skip the YAML frontmatter at the top)
3. Paste it into Claude, ChatGPT, or your preferred AI assistant
4. Add your own material (article draft, data, questions)

### Option 2: Reference in Your Project
Add the skill path to your project's configuration so it loads automatically.

---

## Core Editorial Skills (8)

### 1. Source Verification
**File:** `core-editorial/source-verification/SKILL.md`
**Use when:** Verifying industrial claims, checking source credibility, investigating company statements, validating production data
**Adapted from:** jamditis/claude-skills-journalism

### 2. Fact Checker
**File:** `core-editorial/fact-checker/SKILL.md`
**Use when:** Verifying production figures, investment claims, employment data, government statistics, executive statements
**Adapted from:** jamditis/claude-skills-journalism

### 3. AI Writing Detox
**File:** `core-editorial/ai-writing-detox/SKILL.md`
**Use when:** Eliminating AI-generated writing patterns in French, Arabic, and English
**Adapted from:** jamditis/claude-skills-journalism

### 4. Newsroom Style
**File:** `core-editorial/newsroom-style/SKILL.md`
**Use when:** Writing news articles, editing drafts, creating headlines, converting notes into publishable copy
**Adapted from:** jamditis/claude-skills-journalism

### 5. Story Angle Finder
**File:** `core-editorial/story-angle-finder/SKILL.md`
**Use when:** You have a topic but not yet a story, or when pitching and need to see the full range of angles
**Adapted from:** ur-grue/autopunk-media-skills

### 6. Article Builder
**File:** `core-editorial/article-builder/SKILL.md`
**Use when:** You have a story angle and need to develop it into a publishable article
**Adapted from:** ComposioHQ/awesome-claude-skills

### 7. Interview Prep
**File:** `core-editorial/interview-prep/SKILL.md`
**Use when:** Preparing for interviews with industrial executives, government officials, or industry experts
**Adapted from:** jamditis/claude-skills-journalism

### 8. Pre-Publication Review
**File:** `core-editorial/pre-publication-review/SKILL.md`
**Use when:** Final review before publishing any article
**Source:** Custom IDM skill

---

## Employee Tools (5)

### 9. Newsletter Builder
**File:** `employee-tools/newsletter-builder/SKILL.md`
**Use when:** Creating weekly/monthly newsletters covering Moroccan industry
**Adapted from:** jamditis/claude-skills-journalism + ur-grue/autopunk-media-skills

### 10. Content Repurposer
**File:** `employee-tools/content-repurposer/SKILL.md`
**Use when:** Transforming magazine articles into social media, newsletters, and other formats
**Adapted from:** ur-grue/autopunk-media-skills + coreyhaines31/marketingskills

### 11. Social Media Publisher
**File:** `employee-tools/social-media-publisher/SKILL.md`
**Use when:** Creating and scheduling social media content across platforms
**Adapted from:** coreyhaines31/marketingskills

### 12. Press Release Analyzer
**File:** `employee-tools/press-release-analyzer/SKILL.md`
**Use when:** Analyzing incoming press releases for newsworthiness and verification
**Source:** Custom IDM skill

### 13. Editorial Translation
**File:** `employee-tools/editorial-translation/SKILL.md`
**Use when:** Translating content between French, Arabic, and English
**Source:** Custom IDM skill

---

## Production Tools (2)

### 14. PDF & Media Kit Builder
**File:** `production/pdf-media-kit-builder/SKILL.md`
**Use when:** Creating branded PDF documents, reports, and media kits
**Adapted from:** anthropics/skills

### 15. Presentation Builder
**File:** `production/presentation-builder/SKILL.md`
**Use when:** Creating professional HTML presentations, industrial reports, company profiles, event materials
**Adapted from:** ppt-agent-skill

---

## Reference Documents

### IDM Brand Guide
**File:** `IDM-BRAND.md`
**Purpose:** Editorial voice, content categories, trilingual guidelines, fact-checking standards

### IDM Industrial Terminology
**File:** `IDM-TERMINOLOGY.md`
**Purpose:** Standardized trilingual terminology for industrial journalism (200+ terms)

---

## Workflows

### Editorial Workflow (Core Skills)

```
1. Story Angle Finder → Generate angles from a topic
        ↓
2. Interview Prep → Prepare for source interviews
        ↓
3. Article Builder → Develop the chosen angle
        ↓
4. Source Verification → Verify all claims
        ↓
5. Fact Checker → Fact-check the complete article
        ↓
6. AI Writing Detox → Remove AI patterns
        ↓
7. Newsroom Style → Apply style conventions
        ↓
8. Pre-Publication Review → Final approval
```

### Distribution Workflow (Employee Tools)

```
Published Article
        ↓
┌───────┼───────┬───────┐
↓       ↓       ↓       ↓
Newsletter  Social    Press     Translation
Builder     Media     Release   for other
            Publisher Analyzer  languages
```

### Production Workflow

```
Final Article
        ↓
PDF/Media Kit Builder → Branded documents
        ↓
Presentation Builder → Professional slides
        ↓
Distribution to stakeholders
```

---

## Sources

These skills were adapted from the following open-source repositories:

| Repository | License | Skills Used |
|------------|---------|-------------|
| jamditis/claude-skills-journalism | MIT | Source verification, fact-check, AI detox, newsroom style, interview prep |
| ur-grue/autopunk-media-skills | MIT | Story angle finder, content repurposer |
| ComposioHQ/awesome-claude-skills | MIT | Article builder |
| coreyhaines31/marketingskills | MIT | Social media publisher |
| anthropics/skills | MIT | PDF/media kit builder |
| ppt-agent-skill | MIT | Presentation builder |

---

## Maintenance

This catalogue should be reviewed quarterly. New skills must be approved by the Editorial Director before use. When updating skills, maintain backward compatibility with existing workflows.

**Last updated:** July 2026
**Maintained by:** IDM Editorial Department
