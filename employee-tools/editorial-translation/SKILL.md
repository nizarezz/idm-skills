---
name: idm-editorial-translation
description: >
  Translate and localize industrial journalism content between French, Arabic, and English
  for Industrie du Maroc Magazine. Preserves editorial voice, industrial terminology,
  and Moroccan institutional context. Includes rules for company names, government names,
  technical terms, numbers, currencies, and cultural adaptation.
version: 1.0.0
author: IDM Editorial Department
domain: industrial journalism, translation, trilingual, Morocco
license: MIT (custom IDM skill)
---

# IDM Editorial Translation

Translate industrial journalism content between French, Arabic, and English while preserving editorial voice, accuracy, and Moroccan industrial context.

## When to Use This Skill

- Translating articles from one language to another
- Adapting content for different language audiences
- Ensuring terminology consistency across languages
- Translating quotes from interview sources
- Localizing international content for Moroccan audience

## Translation Principles

### 1. Accuracy First
- Preserve meaning, not literal words
- Verify all facts remain correct after translation
- Maintain numerical accuracy
- Keep dates and times correct

### 2. Terminology Consistency
- Use terms from IDM-TERMINOLOGY.md
- Never translate company names
- Never translate government ministry names
- Use official trilingual versions for institutions

### 3. Editorial Voice
- Match the tone of the target language
- Adapt idioms, don't translate literally
- Maintain professional industrial journalism style
- Follow IDM newsroom style in target language

### 4. Cultural Adaptation
- Adapt examples where relevant
- Consider reader context in target language
- Maintain relevance to Moroccan industrial audience

---

## What Never Translates

### Company Names

**Rule:** Never translate company names. Use the official registered name.

| Original | Translation |
|----------|-------------|
| Renault Maroc | رينو المغرب (Arabic) / Renault Morocco (English) |
| OCP Group | مجموعة OCP (Arabic) / OCP Group (English) |
| PSA Maroc | PSA المغرب (Arabic) / PSA Morocco (English) |

### Government Ministry Names

**Rule:** Use official trilingual versions from IDM-TERMINOLOGY.md.

| French | Arabic | English |
|--------|--------|---------|
| Ministère de l'Industrie et du Commerce | وزارة الصناعة والتجارة | Ministry of Industry and Commerce |
| Ministère de l'Économie et des Finances | وزارة الاقتصاد والمالية | Ministry of Economy and Finance |

### Agency and Institution Names

**Rule:** Use official trilingual versions from IDM-TERMINOLOGY.md.

| French | Arabic | English |
|--------|--------|---------|
| ONHYM | المكتب الوطني للهيدروكربونات والمعادن | ONHYM |
| ANPIMC | الوكالة الوطنية لترويج الصناعة والتجارة | ANPIMC |
| MASEN | الوكالة المغربية للطاقة المستدامة | MASEN |

### Acronyms

**Rule:** Spell out on first reference, use abbreviation thereafter. Keep acronyms in original language.

| First Reference | Subsequent References |
|-----------------|----------------------|
| Office National des Hydrocarbures et des Mines (ONHYM) | ONHYM |
| المكتب الوطني للهيدروكربونات والمعادن (ONHYM) | ONHYM |
| National Office of Hydrocarbons and Mines (ONHYM) | ONHYM |

---

## What Translates with Rules

### Numbers

| Language | Thousands Separator | Decimal | Percent |
|----------|---------------------|---------|---------|
| French | 1 000 (space) | 3,14 (comma) | 5 % (space) |
| Arabic | 1٬000 (Arabic comma) | 3٫14 (Arabic decimal) | 5٪ |
| English | 1,000 (comma) | 3.14 (period) | 5% |

### Currency

| Language | Format | Example |
|----------|--------|---------|
| French | [amount] DH | 100 DH |
| Arabic | [amount] درهم | 100 درهم |
| English | [amount] MAD | 100 MAD |

### Dates

| Language | Format | Example |
|----------|--------|---------|
| French | [day] [month] [year] | 13 juillet 2026 |
| Arabic | [day] [month] [year] | 13 يوليو 2026 |
| English | [Month] [day], [year] | July 13, 2026 |

### Units

Follow SI conventions in all languages. Use language-appropriate abbreviations:

| Unit | French | Arabic | English |
|------|--------|--------|---------|
| Kilometers | km | كم | km |
| Tons | t | طن | tons |
| Megawatts | MW | ميغاواط | MW |
| Barrels | bbl | برميل | bbl |

---

## Translation Modes

### Mode 1: Literal Translation (Faithful)

**Use when:** Legal documents, official statements, technical specifications

**Rules:**
- Preserve exact meaning
- Keep sentence structure where possible
- Use direct equivalents from IDM-TERMINOLOGY.md
- Note any untranslatable terms

**Example:**
- French: "L'usine a produit 50 000 véhicules au premier semestre 2026."
- Arabic: "أproduced المصنع 50 ألف وحدة في النصف الأول من 2026."
- English: "The plant produced 50,000 vehicles in the first half of 2026."

### Mode 2: Editorial Localization

**Use when:** Articles, features, newsletters, social media

**Rules:**
- Preserve meaning and tone
- Adapt expressions for target language
- Maintain professional journalism style
- Use natural phrasing in target language

**Example:**
- French: "Le secteur automobile connaît une croissance soutenue."
- Arabic: "يشهد قطاع汽车行业 نموًا مستمرًا وملحوظًا."
- English: "The automotive sector is growing steadily."

### Mode 3: Quote Translation

**Use when:** Translating quotes from interview sources

**Rules:**
- Preserve the speaker's meaning
- Note original language in parentheses
- Use natural speech patterns
- Maintain attribution accuracy

**Example:**
- French: "Nous visons 10 GW d'ici 2030," a déclaré le ministre.
- Arabic: "صرح الوزير: 'نستهدف 10 جيجاواط بحلول عام 2030'."
- English: "We are targeting 10 GW by 2030," the minister said.

---

## Translation Workflow

### Step 1: Prepare

```markdown
## Translation Preparation

### Source Material
- **Original language:** [FR / AR / EN]
- **Document type:** [Article / Press release / Quote / Data]
- **Word count:** [Number]
- **Technical content:** [Yes/No]

### Target Language
- **Target language:** [FR / AR / EN]
- **Audience:** [General / Specialist / Executive]
- **Platform:** [Magazine / Newsletter / Social media / Website]

### Reference Materials
- [ ] IDM-TERMINOLOGY.md loaded
- [ ] IDM-BRAND.md loaded
- [ ] IDM newsroom style guide loaded
- [ ] Previous articles in target language reviewed
```

### Step 2: Translate

```markdown
## Translation Process

### First Pass: Meaning
- Translate core meaning
- Preserve all facts and data
- Note any untranslatable terms

### Second Pass: Style
- Apply IDM newsroom style
- Check terminology against IDM-TERMINOLOGY.md
- Ensure natural phrasing

### Third Pass: Quality
- Verify all numbers are correct
- Check company/government names
- Review for AI writing patterns
- Confirm trilingual consistency
```

### Step 3: Review

```markdown
## Translation Review

### Accuracy
- [ ] All facts preserved
- [ ] All numbers correct
- [ ] All dates correct
- [ ] All names correct

### Terminology
- [ ] Company names use official registered names
- [ ] Government names use official trilingual versions
- [ ] Technical terms from IDM-TERMINOLOGY.md
- [ ] Acronyms handled correctly

### Style
- [ ] Follows IDM newsroom style in target language
- [ ] No AI writing patterns
- [ ] Professional tone maintained
- [ ] Natural phrasing in target language

### Formatting
- [ ] Numbers formatted correctly
- [ ] Currency formatted correctly
- [ ] Dates formatted correctly
- [ ] Units correct
```

---

## Common Translation Challenges

### Challenge 1: Technical Terms with No Direct Equivalent

**Solution:**
1. Use the term from IDM-TERMINOLOGY.md
2. If not in glossary, use the most common Arabic/French/English equivalent
3. Note the term on first reference if uncertain
4. Consult with editorial team

### Challenge 2: Idiomatic Expressions

**Solution:**
1. Translate the meaning, not the words
2. Use equivalent expressions in target language
3. Avoid literal translations that sound unnatural
4. Maintain professional tone

### Challenge 3: Company-Specific Jargon

**Solution:**
1. Use the company's official translation (if available)
2. If not, use the most common industry usage
3. Keep consistent within the article
4. Note any ambiguity

### Challenge 4: Numbers and Data

**Solution:**
1. Convert number formatting per language rules
2. Keep currencies in original unless conversion needed
3. Maintain precision (don't round unless original does)
4. Verify all calculations remain correct

---

## Quality Checklist

Before finalizing any translation:

### Accuracy
- [ ] All facts preserved
- [ ] All numbers correct
- [ ] All dates correct
- [ ] All names spelled correctly

### Terminology
- [ ] Company names use official registered names
- [ ] Government names use official trilingual versions
- [ ] Technical terms from IDM-TERMINOLOGY.md
- [ ] Acronyms spelled out on first reference

### Style
- [ ] Follows IDM newsroom style in target language
- [ ] No AI writing patterns
- [ ] Professional tone maintained
- [ ] Natural phrasing

### Formatting
- [ ] Numbers formatted correctly per language
- [ ] Currency formatted correctly
- [ ] Dates formatted correctly
- [ ] Units correct

### Consistency
- [ ] Consistent terminology throughout
- [ ] Consistent style throughout
- [ ] Consistent formatting throughout

---

## Related IDM Skills

- **idm-newsroom-style** — Apply style conventions in target language
- **idm-ai-writing-detox** — Remove AI patterns from translation
- **idm-source-verification** — Verify facts in translation
- **idm-fact-checker** — Fact-check translated content

---

## Skill Metadata

| Field | Value |
|-------|-------|
| version | 1.0.0 |
| created | 2026-07-13 |
| updated | 2026-07-13 |
| author | IDM Editorial Department |
| domain | industrial journalism, translation, trilingual, Morocco |
| complexity | intermediate |
| source | Custom IDM skill |
| license | MIT |
