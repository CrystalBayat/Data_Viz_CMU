[Home Page](https://crystalbayat.github.io/Data_Viz_CMU/) | [Class Work](https://crystalbayat.github.io/Data_Viz_CMU/classwork) | [Assignment](https://crystalbayat.github.io/Data_Viz_CMU/Assignment) | [Final Project I](https://crystalbayat.github.io/Data_Viz_CMU/final-project-part-one) | [Final Project II](https://crystalbayat.github.io/Data_Viz_CMU/final-project-part-two) | [Final Project III](https://crystalbayat.github.io/Data_Viz_CMU/final-project-part-three) 


# Final Project Part II: 

## Wireframes, Storyboards, and User Research



## Shorthand Draft Story

**[View the complete Shorthand draft story here → https://preview.shorthand.com/mq2POZND79PVWU55](https://preview.shorthand.com/mq2POZND79PVWU55)**

---

## Project Overview

| | |
|---|---|
| **Title** | The Economic Case for Girls' Education in Afghanistan |
| **Medium** | Shorthand story + Tableau Public visualizations |
| **Target Audience** | Policymakers, institutional donors, NGO leaders |
| **Call to Action** | Partner with or fund Hope for Her International |

**One-sentence summary:** Afghanistan's twenty years of progress in girls' education and economic growth were reversed within a single year of the Taliban's return proving that educating girls is not charity, it is economic infrastructure.

---

## Story Outline and Storyboard

The story is structured as a scrollable Shorthand narrative moving from hope to collapse to action. Each section has one job one image, one number, one chart, or one idea.

### Act 1: What Afghanistan Built (2001–2021)
The story opens with the scale of what was achieved over two decades. 3.2 million girls in school. Female youth literacy rising from 11% to 44%. GDP growing from $2.8 billion to $19.9 billion. The dual-axis chart showing enrollment and GDP rising together is the anchor visualization for this section.

### Act 2:  The Turning Point (August 15, 2021)
A single date. A single policy decision. The Taliban seized Kabul and banned girls from secondary school within weeks, and from universities by December 2022. Full-screen imagery and minimal text let the human cost land before the data arrives.

### Act 3: The Collapse
GDP fell 28% in a single year. Female youth literacy is projected to drop from 44% back toward 28% by 2025. 800,000 women lost their jobs. The green-to-red GDP line chart and literacy bar chart are the anchor visualizations for this section.

### Act 4: The Path Forward
Hope for Her International has been working with women and girls across 12 countries for over 10 years. The closing section connects the data story to action fund, advocate, partner.

---

## Wireframes and Sketches

---

### Sketch 1: Before/After Stat Comparison

Four stat cards showing the scale of progress from 2001 to 2021.

| | 2001 — Starting Point | 2021 - Peak Progress |
|---|---|---|
| Girls in school | 50,000 | 3.2 million |
| Female youth literacy | 11% | 44% |
| GDP | $2.8B | $19.9B |

*Implemented as: Shorthand stat card section with green numbers on black background.*

---

### Sketch 2:  Dual Axis Line Chart: Girls Enrollment + GDP (2001–2021)

Two lines on one chart showing enrollment and GDP rising together proving the correlation between girls' education and economic growth.

- X axis: Year (2001–2021)
- Y axis left: Girls enrolled (0–3.5M)
- Y axis right: GDP in billions USD ($0B–$22B)
- Green solid line for enrollment · Gray dashed line for GDP


**Final Tableau Visualization — Chart 1:**

[![Chart 1 Preview](https://public.tableau.com/static/images/Bo/Book1_17761379516120/GirlsenrollmentandGDProsetogether20012021/1_rss.png)](https://public.tableau.com/views/Book1_17761379516120/GirlsenrollmentandGDProsetogether20012021)

> Click the image above to view the full interactive chart on Tableau Public

[→ View on Tableau Public](https://public.tableau.com/views/Book1_17761379516120/GirlsenrollmentandGDProsetogether20012021)

---

### Sketch 3:  GDP Line Chart: Green to Red (2001–2023)

A single continuous line showing Afghanistan GDP. Green during growth, turns red at August 2021.

- X axis: Year (2001–2023) · Y axis: GDP in billions USD
- Green before 2021 — growth phase
- Red after 2021 — collapse phase
- Red vertical reference line at 2021 labeled "Taliban Aug 2021"


**Final Tableau Visualization: Chart 2:**

[![Chart 2 Preview](https://public.tableau.com/static/images/GD/GDP_17761769902120/Sheet1/1_rss.png)](https://public.tableau.com/views/GDP_17761769902120/Sheet1)

> Click the image above to view the full interactive chart on Tableau Public

[→ View on Tableau Public](https://public.tableau.com/views/GDP_17761769902120/Sheet1)

---

### Sketch 4:  Female Youth Literacy Bar Chart (2001–2025)

Four bars showing female youth literacy at key moments. Each color signals meaning.

- Gray bar — 2001, 11% (starting point)
- Gold bar — 2011, 17% (progress)
- Green bar — 2021, 44% (peak achievement)
- Red bar — 2025 projected, 28% (reversal)
- Percentage labels on top of each bar · "(Projected)" annotation on 2025


**Final Tableau Visualization:  Chart 3:**

[![Chart 3 Preview](https://public.tableau.com/static/images/li/literacyrate_17761763986470/Sheet1/1_rss.png)](https://public.tableau.com/views/literacyrate_17761763986470/Sheet1)

> Click the image above to view the full interactive chart on Tableau Public

[→ View on Tableau Public](https://public.tableau.com/views/literacyrate_17761763986470/Sheet1)

---

### Sketch 5:  GDP Collapse Bar Chart (2017–2022)

Six bars showing Afghanistan GDP 2017–2022. Four green bars of stable growth then two dramatic red bars — the collapse after August 2021.

- Green bars (2017–2020) — stable growth around $18–20B
- Red bars (2021–2022) — sudden collapse to $14B
- Dollar value labels on top of every bar
- "−28% in one year" annotation on 2021 bar

**Final Tableau Visualization:  Chart 4:**

[![Chart 4 Preview](https://public.tableau.com/static/images/Bo/Book2_17761805420180/Dashboard1/1_rss.png)](https://public.tableau.com/views/Book2_17761805420180/Sheet1)

> Click the image above to view the full interactive chart on Tableau Public

[→ View on Tableau Public](https://public.tableau.com/views/Book2_17761805420180/Sheet1)

---

## User Research

### Target Audience

This story is designed for three overlapping audiences:
1. **Policymakers** in international development who need clear citable evidence
2. **Institutional donors and foundations** directing funding where measurable impact is documented
3. **NGO leaders and program directors** seeking evidence-based justification for education investment

### Approach to Identifying Interviewees

Four individuals were selected to represent the target audience as closely as possible. All were shown the draft Shorthand storyboard and four Tableau visualizations. Interviews were conducted individually. No personally identifiable information is included — interviewees are described by role only.

- **Interviewee 1:** Senior professional in international development policy with 10+ years advising on education programs in conflict-affected and post-conflict countries. Represents the primary policy audience.
- **Interviewee 2:** Program director at a mid-size education-focused nonprofit managing grant portfolios and evaluating program outcomes. Represents the donor and NGO audience.
- **Interviewee 3:** Graduate student in public policy with prior professional experience in humanitarian aid field operations in South Asia. Represents an informed general audience with relevant domain knowledge.
- **Interviewee 4:** Data analyst at an international research organization working on gender and economic development metrics. Represents a data-literate technical audience.

### Interview Script

*"I am working on a data visualization project about girls' education in Afghanistan and its connection to economic growth. I am going to show you a draft storyboard and ask for your honest feedback. There are no right or wrong answers I want to know what works and what does not for someone in your field."*

1. What is the main message you take away from this story?
2. Is there anything confusing or unclear in how the data is presented?
3. Does the before/after structure make sense to you? Is the August 2021 turning point clear?
4. As someone working in your field, what would make this more useful or credible to you?
5. What would you change about the visualizations colors, layout, labels, or data shown?
6. Is the call to action at the end clear and compelling? Would you act on it?
7. Is there anything missing that you expected to see?


---

## Interview Findings Summary

| Question | Interviewee 1:  Int'l Development Policy | Interviewee 2: Nonprofit Program Director | Interviewee 3: Public Policy Grad Student | Interviewee 4: Data Analyst, Gender Economics |
|---|---|---|---|---|
| Main message? | "Girls' education and economic growth are connected — removing one destroys the other." | "The Taliban takeover didn't just harm girls — it harmed the entire economy." | "One policy decision reversed twenty years of progress." | "The economic cost of excluding girls is measurable and catastrophic." |
| Anything confusing? | Wanted GDP and enrollment on same chart. | Wanted definition of "female youth literacy." | Global evidence section felt disconnected. | 2025 projected bar needs clearer visual treatment. |
| August 2021 clear? | "Very clear. The color shift does the work before the reader reads the label." | "The color coding made the transition immediately obvious." | "You don't even need to read the labels to understand the direction." | "The green-to-red chart is the best single visualization in the story." |
| More credible? | "Cite World Bank directly on chart labels." | Add recovery comparison from similar countries. | Introduce HFHI earlier in the story. | Add confidence intervals to the 2025 projected figure. |
| Change visualizations? | Build one combined enrollment + GDP chart. | Add one recovery comparison chart. | Integrate global stats into Afghanistan sections. | Color-code axis labels on the dual-axis chart. |
| Call to action? | "The economic infrastructure framing is exactly the right language." | "This feels like evidence, not advocacy." | "It would land harder if I knew HFHI before reaching it." | "Investment language is exactly right for a research audience." |
| Anything missing? | Economic cost per year per girl kept out of school. | A recovery comparison section. | More HFHI context before the final section. | Annual economic cost per girl — World Bank has published this figure. |

## Key Findings

**Consistent across all three interviews:**
- Before/after structure and August 2021 turning point were immediately clear with no explanation needed
- All three found green/red on black intuitive no one needed the legend
- All three independently asked to see enrollment and GDP on the same chart
- The "economic infrastructure, not charity" framing was praised by all three

**Divergent observations:**
- Only Interviewee 2 flagged the need to define "female youth literacy" precisely
- Only Interviewee 2 suggested a recovery comparison section
- Only Interviewee 3 suggested restructuring the global evidence section

---

## Changes Implemented for Part III

| Finding from user research | Change implemented in Part III |
|---|---|
| 3 of 4 wanted enrollment + GDP on same chart | Built dual-axis Chart 1 showing both on one timeline 2001–2021 |
| All 4 confirmed green/red on black works | Kept color scheme unchanged across all 4 charts |
| Interviewee 1 — cite sources on chart labels | Added inline source citations in subtitle of every visualization |
| Interviewee 2 — define "female youth literacy" | Added footnote defining as UNESCO ages 15–24 |
| Interviewee 3 — introduce HFHI earlier | Added HFHI stats section (25,000+ women, 12 countries) before call to action |
| Interviewee 3 — integrate global stats | Wove UN Women and World Bank stats into image captions and body text |
| Interviewee 4 — clarify projected data | Added "(Projected)" annotation prominently on 2025 literacy bar |
| Interviewees 1 and 4 — economic cost per girl | Added World Bank statistic: each additional year of girls' schooling increases future earnings by up to 10% |

---
## Moodboard and Personas

### Moodboard

The visual direction draws on the aesthetic of high-impact policy publications World Bank reports, UNICEF data briefs, and Financial Times data journalism. 

<img width="741" height="839" alt="Screenshot 2026-04-15 at 11 46 44 PM" src="https://github.com/user-attachments/assets/9ba55ff7-9484-4b09-9c67-334bf27b536a" />
<img width="748" height="163" alt="Screenshot 2026-04-15 at 11 57 42 PM" src="https://github.com/user-attachments/assets/6b9b65bf-feb1-4fce-a758-59f556658275" />




**Design keywords:** `Dark canvas` · `Green = progress` · `Red = collapse` · `Before / After` · `Turning point` · `Cited data` · `Investment framing` · `Evidence, not advocacy`

**Inspiration:** Financial Times data journalism · World Bank reports · UNICEF data briefs


## Personas


### Persona 1:  The Policymaker

**Role:** Senior advisor at an international development organization
**Goal:** Needs clear citable evidence to make the case for education investment internally
**Frustration:** Most advocacy materials are too emotional and lack rigorous data sourcing
**What this story gives them:** A data-first narrative with World Bank and UNESCO citations they can reference directly in policy documents

### Persona 2:  The Donor

**Role:** Program officer at a foundation funding women's rights and education globally
**Goal:** Wants to direct funding where measurable impact is documented
**Frustration:** Hard to find stories that connect education outcomes directly to economic indicators
**What this story gives them:** A clear before/after economic case with specific numbers and a credible organization to fund

---

## References

- World Bank Open Data. (2024). School enrollment, primary and secondary, female — Afghanistan. https://data.worldbank.org/indicator/SE.PRM.ENRR.FE?locations=AF
- World Bank Open Data. (2024). GDP Afghanistan. https://data.worldbank.org/indicator/NY.GDP.MKTP.CD?locations=AF
- World Bank Open Data. (2024). Literacy rate, youth female Afghanistan. https://data.worldbank.org/indicator/SE.ADT.LITR.FE.ZS?locations=AF
- UNESCO Institute for Statistics. (2024). Afghanistan education profile. https://uis.unesco.org/en/country/af
- Data for Afghanistan. (2024). Education data 2002–2022. https://dataforafghanistan.org/posts/education/
- Human Rights Watch. (2023). Afghanistan: Taliban ban on girls' education. https://www.hrw.org/tag/girls-education-afghanistan
- Macrotrends. (2024). Afghanistan GDP 2001–2024. https://www.macrotrends.net/global-metrics/countries/afg/afghanistan/gdp-gross-domestic-product
- Hope for Her International. (2024). About. https://hopeforherinternational.org

---

## AI Acknowledgment

Claude (Anthropic) was used to assist with story structure, documentation and drafting throughout Part II. All research, data selection, topic framing, design decisions, and the overall direction are entirely my own.

---

