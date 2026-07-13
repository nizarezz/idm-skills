---
name: idm-story-angle-finder
description: >
  Generates 6-8 distinct editorial angles from a broad industrial topic or news event
  for Industrie du Maroc Magazine. Each angle has a unique perspective, target audience,
  and reporting approach tailored to Moroccan industrial journalism. Use when you have a
  topic but not yet a story, or when pitching and need to see the full range of angles.
version: 1.0.0
author: IDM Editorial Department
domain: industrial journalism, ideation, Morocco
license: MIT (adapted from ur-grue/autopunk-media-skills)
---

# IDM Story Angle Finder

Generates 6-8 distinct editorial angles from a broad industrial topic or news event, each with a unique perspective, target audience, and reporting approach tailored to Moroccan industrial journalism.

## When to Use This Skill

- You have a topic but not yet a story — you know the subject but not the specific angle
- You are pitching and need to see the full range of angles before deciding which to develop
- An editor has given you a sector beat and you need to identify the most compelling entry point
- You want to see how the same event could be covered differently across IDM sections

## What You Need to Provide

**Required:**
- The broad topic, subject area, or news event you are working with
- IDM section or target audience (or describe your audience if no specific section)

**Optional:**
- Angles you have already considered and want to avoid
- Specific sources or data you already have access to
- Geographic scope (Tangier, Casablanca, national, international)
- Timeframe (breaking, evergreen, anniversary)
- Whether you need a pitch-ready one-liner for each angle

## How the Assistant Approaches This

1. Identifies at least six distinct editorial lenses through which the topic can be approached:
   - The **company/factory profile** (operational focus)
   - The **policy/regulation analysis** (government action focus)
   - The **data/story** (statistics and trends focus)
   - The **supply chain** (logistics and trade focus)
   - The **workforce** (employment and skills focus)
   - The **investment** (financial and FDI focus)
   - The **sustainability** (environmental and energy focus)
   - The **technology/innovation** (R&D and modernization focus)

2. For each angle, specifies:
   - The core question the story would answer
   - The primary type of reporting required (documents, sources, data, observation)
   - The most likely IDM section or publication home
   - Which Moroccan institutions or sources to approach

3. Marks which angles are time-sensitive versus evergreen
4. Notes where angles overlap with common coverage so the journalist can differentiate
5. Closes with a "Next Step" recommendation: which angle to develop first

## Output Format

6-8 numbered angle briefs. Each brief includes:

- **Angle Name** (3-5 words)
- **Core Question**
- **Reporting Approach** (2 sentences)
- **Ideal IDM Section**
- **Key Sources** (Moroccan institutions, companies, experts)
- **Pitch Line** (one sentence, ready to drop into a pitch email)
- **Language Recommendation** (FR / AR / EN / Multilingual)

Total length: 600-800 words. Output ends with a "Next Step" note.

## Quality Criteria

- [ ] Each angle has a genuinely distinct editorial perspective
- [ ] Every angle includes a concrete reporting approach
- [ ] At least one angle is counterintuitive or challenges conventional framing
- [ ] At least one angle is suitable for long-form feature treatment
- [ ] Pitch lines are publication-ready
- [ ] Time-sensitive versus evergreen distinction is made
- [ ] Moroccan institutional sources are identified for each angle

## Example

### Input
Topic: The growing number of automotive parts suppliers establishing operations in northern Morocco
Publication type: IDM feature section
Avoid: Any angle that's essentially "Tangier has cheap labor" (done to death)

### Output

**1. The Tier 1 Effect**
*Core Question: How are Tier 1 suppliers transforming the supplier ecosystem in northern Morocco?*
*Reporting Approach: Interview 3-4 Tier 1 suppliers (Renault, Stellantis partners) and compare with Tier 2-3 companies. Focus on technology transfer and quality requirements.*
*IDM Section:* Supply Chain
*Key Sources:* AMIF, Tangier Automotive City officials, supplier company managers
*Pitch Line:* "When Renault moved to Tangier, it brought its suppliers. Now those suppliers have their own suppliers — and the effects are spreading through the region's economy."
*Language:* French
*Timeframe:* Evergreen

---

**2. The Skills Bottleneck**
*Core Question: Can the Moroccan workforce supply enough skilled technicians for the expanding automotive sector?*
*Reporting Approach: Compare training output from IFP, OFPPT, and private academies with industry demand. Interview HR directors at major plants and training officials.*
*IDM Section:* Workforce
*Key Sources:* OFPPT, IFP, AMIF, HR directors at automotive plants
*Pitch Line:* "The automotive sector plans to add 20,000 jobs by 2028. Training institutions are struggling to produce 8,000 graduates per year. The math doesn't work."
*Language:* French/Arabic
*Timeframe:* Evergreen with news hooks

---

**3. The Local Content Question**
*Core Question: What percentage of components used in Moroccan-assembled vehicles are actually made in Morocco?*
*Reporting Approach: Analyze import data from EXTT, compare with production data, interview suppliers about local sourcing rates. Focus on the gap between "Made in Morocco" and "Assembled in Morocco."*
*IDM Section:* Data/Analysis
*Key Sources:* EXTT (Office des Changes), ONPIMC, AMIF, supplier companies
*Pitch Line:* "Morocco exported 560,000 vehicles last year. But how much of each car is actually made here? The answer reveals more about Morocco's industrial strategy than any press release."
*Language:* French/English
*Timeframe:* Evergreen

---

**4. The Infrastructure Strain**
*Core Question: Can roads, ports, and utilities handle the automotive sector's growth?*
*Reporting Approach: Visit Tangier Med port, road infrastructure, ONEE connections. Interview port authorities, logistics companies, and regional planners.*
*IDM Section:* Infrastructure
*Key Sources:* Tangier Med port authority, ONEE, regional planning office, logistics companies
*Pitch Line:* "Tangier Med handled 7 million vehicles last year. The roads connecting it to automotive plants weren't built for that volume."
*Language:* French
*Timeframe:* Evergreen with infrastructure news hooks

---

**5. The European Dependency**
*Core Question: How vulnerable is Morocco's automotive sector to European demand fluctuations?*
*Reporting Approach: Analyze export destination data, interview trade officials about diversification efforts, examine EU-Morocco trade terms.*
*IDM Section:* Trade
*Key Sources:* EXTT, AMDIE, trade ministry, EU-Morocco business council
*Pitch Line:* "90% of Morocco's automotive exports go to Europe. When Europe slows down, Morocco feels it. The sector is working to diversify — but where else can these cars go?"
*Language:* French/English
*Timeframe:* Evergreen

---

**6. The Women on the Line**
*Core Question: What is the experience of women working in automotive manufacturing in Morocco?*
*Reporting Approach: Profile women at different levels in automotive plants — line workers, engineers, managers. Focus on working conditions, career advancement, and the gender dimension of Morocco's industrialization.*
*IDM Section:* Feature/Profile
*Key Sources:* Women workers and managers at automotive plants, labor unions, gender equality organizations
*Pitch Line:* "In Tangier's automotive plants, 40% of workers are women. Their stories tell you more about Morocco's industrial transformation than any production statistic."
*Language:* Arabic/French
*Timeframe:* Evergreen; strong human-interest angle

---

**7. The Environmental Trade-Off**
*Core Question: What is the environmental cost of Morocco's automotive boom?*
*Reporting Approach: Examine emissions data, water usage, waste management at automotive plants. Interview environmental regulators and activists. Compare with European environmental standards.*
*IDM Section:* Sustainability
*Key Sources:* ONEE, environmental ministry, ONHYM, plant environmental officers
*Pitch Line:* "Morocco's automotive sector is booming. So is its industrial water consumption. The environmental trade-offs are starting to show."
*Language:* French
*Timeframe:* Evergreen

---

**8. The Counter-Trend: Who's Leaving?**
*Core Question: Are any automotive suppliers leaving northern Morocco, and why?*
*Reporting Approach: Research companies that have downsized, relocated, or closed. Interview former employees and industry analysts. Counterbalances the triumphalist narrative.*
*IDM Section:* Investigation
*Key Sources:* Former plant managers, industry analysts, regional economic officials
*Pitch Line:* "Everyone talks about the companies coming to Tangier. Nobody writes about the ones leaving. Here are five of them."
*Language:* French
*Timeframe:* Evergreen; counterintuitive angle

---

*Note: Angles 1, 3, and 6 are strongest for IDM feature sections. Angles 2, 4, and 7 suit the news and analysis sections. Angle 5 is strong for international readers. Angle 8 is a counterintuitive investigation.*

## Known Limitations

- Angles are generated from the topic description only; the assistant does not have access to current news databases — always verify an angle has not been recently covered
- The strength of any angle depends on source access; some angles require embedded reporting that may not be feasible
- For breaking news, time-sensitive assessment may be inaccurate without current context

## Related IDM Skills

- **idm-article-builder** — Develop a chosen angle into a full article
- **idm-interview-prep** — Prepare for interviews with sources identified in the angle
- **idm-source-verification** — Verify claims found during angle research
- **idm-fact-checker** — Fact-check the final article

---

## Skill Metadata

| Field | Value |
|-------|-------|
| version | 1.0.0 |
| created | 2026-07-13 |
| updated | 2026-07-13 |
| author | IDM Editorial Department |
| domain | industrial journalism, ideation, Morocco |
| complexity | beginner |
| source adapted from | ur-grue/autopunk-media-skills story-angle-finder |
| source license | MIT |
