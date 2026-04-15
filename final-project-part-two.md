[Home Page](https://crystalbayat.github.io/Data_Viz_CMU/) | [Class Work](https://crystalbayat.github.io/Data_Viz_CMU/classwork) | [Assignment](https://crystalbayat.github.io/Data_Viz_CMU/Assignment) | [Final Project I](https://crystalbayat.github.io/Data_Viz_CMU/final-project-part-one) | [Final Project II](https://crystalbayat.github.io/Data_Viz_CMU/final-project-part-two) | [Final Project III](https://crystalbayat.github.io/Data_Viz_CMU/final-project-part-three) 


# Final Project Part II: 
##Wireframes, Storyboards, and User Research


## Shorthand Draft Story

**[View the complete Shorthand draft story here → https://preview.shorthand.com/mq2POZND79PVWU55](https://preview.shorthand.com/mq2POZND79PVWU55)**
# User research 


---

## Project Overview

**Title:** The Economic Case for Girls' Education in Afghanistan

**One-sentence summary:** Afghanistan's twenty years of progress in girls' education and economic growth were reversed within a single year of the Taliban's return — proving that educating girls is not charity, it is economic infrastructure.

**Target audience:** Policymakers, institutional donors, and NGO leaders working in international development and conflict-affected education contexts.

**Medium:** Shorthand scrollable web story with data visualizations built in Tableau Public.

**Call to action:** Partner with or fund Hope for Her International at hopeforherinternational.org

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
Hope for Her International has been working with women and girls across 12 countries for over 10 years. The closing section connects the data story to action — fund, advocate, partner.

---

## Wireframes and Sketches


### Sketch 1 — Before/After Stat Comparison

**Description:** Four stat cards showing the scale of progress from 2001 to 2021. Left side shows the starting point: 50,000 girls in school, 11% literacy, $2.8B GDP. Right side shows the peak: 3.2 million girls, 44% literacy, $19.9B GDP.

![Sketch 1 - Before After Stats](sketch1_before_after.jpg)

**Implemented as:** Shorthand stat card section with green numbers on black background.

---

### Sketch 2 — Dual Axis Line Chart: Girls Enrollment + GDP (2001–2021)

**Description:** Two lines on one chart. Green solid line for girls enrolled (left axis, millions). Gray dashed line for GDP (right axis, billions USD). Both lines move upward together demonstrating the correlation between education investment and economic growth.

- X axis: Year (2001–2021)
- Y axis left: Girls enrolled (0 to 3.5M)
- Y axis right: GDP in billions USD ($0B to $22B)
- Color: Green (#4ade80) for enrollment, gray dashed for GDP
- Background: Black (#0a0a0a)
- Source: World Bank Open Data · Macrotrends

![Sketch 2 - Dual Axis Line Chart](sketch2_enrollment_gdp.jpg)

**Final Tableau Visualization — Chart 1:**

<div class="tableauPlaceholder" style="width:100%;margin:20px 0;">
<iframe
  title="Education built the economy Afghanistan 2001-2021"
  src="https://public.tableau.com/views/Book1_17761379516120/GirlsenrollmentandGDProsetogether20012021?:embed=y&:showVizHome=no&:toolbar=no"
  width="100%"
  height="500"
  style="border:none;display:block;"
  allowfullscreen>
</iframe>
</div>

[View on Tableau Public](https://public.tableau.com/views/Book1_17761379516120/GirlsenrollmentandGDProsetogether20012021)

---

### Sketch 3 — GDP Line Chart: Green to Red (2001–2023)

**Description:** A single continuous line showing Afghanistan GDP from 2001 to 2023. The line is green during the growth phase and turns red at August 2021. A vertical red reference line marks the turning point labeled "Taliban Aug 2021."

- X axis: Year (2001–2023)
- Y axis: GDP in billions USD
- Color: Green (#4ade80) before 2021, red (#f87171) after
- Reference line: Red vertical at 2021
- Background: Black (#0a0a0a)
- Source: World Bank · Macrotrends

![Sketch 3 - GDP Green to Red](sketch3_gdp_collapse_line.jpg)

**Final Tableau Visualization — Chart 2:**

<div class="tableauPlaceholder" style="width:100%;margin:20px 0;">
<iframe
  title="When the Taliban closed classrooms the economy followed"
  src="https://public.tableau.com/views/GDP_17761769902120/Sheet1?:embed=y&:showVizHome=no&:toolbar=no&publish=yes"
  width="100%"
  height="500"
  style="border:none;display:block;"
  allowfullscreen>
</iframe>
</div>

[View on Tableau Public](https://public.tableau.com/views/GDP_17761769902120/Sheet1)

---

### Sketch 4 — Female Youth Literacy Bar Chart (2001–2025)

**Description:** Four bars showing female youth literacy at key points in time. Each bar is a different color: gray for starting point, gold for progress, green for peak, red for projected reversal.

- Bars: 2001 (11%, gray), 2011 (17%, gold), 2021 (44%, green), 2025 projected (28%, red)
- X axis: Year
- Y axis: Literacy rate percentage
- Labels: Percentage shown on top of each bar
- Annotation: "(Projected)" label on 2025 bar
- Background: Black (#0a0a0a)
- Source: UNESCO Institute for Statistics · World Bank WDI

![Sketch 4 - Literacy Bars](sketch4_literacy_bars.jpg)

**Final Tableau Visualization — Chart 3:**

<div class="tableauPlaceholder" style="width:100%;margin:20px 0;">
<iframe
  title="44 percent literacy built over 20 years now reversing"
  src="https://public.tableau.com/views/literacyrate_17761763986470/Sheet1?:embed=y&:showVizHome=no&:toolbar=no"
  width="100%"
  height="500"
  style="border:none;display:block;"
  allowfullscreen>
</iframe>
</div>

[View on Tableau Public](https://public.tableau.com/views/literacyrate_17761763986470/Sheet1)

---

### Sketch 5 — GDP Collapse Bar Chart (2017–2022)

**Description:** Six bars showing Afghanistan GDP from 2017 to 2022. Four green bars showing stable growth followed by two dramatic red bars showing the collapse after August 2021. The visual contrast makes the story immediately clear without reading any labels.

- Bars: 2017–2020 (green, #4ade80), 2021–2022 (red, #f87171)
- X axis: Year (2017–2022)
- Y axis: GDP in billions USD
- Labels: Dollar value shown on top of each bar
- Annotation: "−28% in one year" on 2021 bar
- Background: Black (#0a0a0a)
- Source: World Bank · Macrotrends

![Sketch 5 - GDP Collapse Bars](sketch5_gdp_collapse_bars.jpg)

**Final Tableau Visualization — Chart 4:**

<div class="tableauPlaceholder" style="width:100%;margin:20px 0;">
<iframe
  title="Afghanistan GDP collapse after Taliban takeover"
  src="https://public.tableau.com/views/Book2_17761805420180/Dashboard1?:embed=y&:showVizHome=no&:toolbar=no&publish=yes"
  width="100%"
  height="795"
  style="border:none;display:block;"
  allowfullscreen>
</iframe>
</div>

[View on Tableau Public](https://public.tableau.com/views/Book2_17761805420180/Sheet1)

---

## Target audience
> Include your approach to identifying representative individuals, and who you hope to reach with your story. 

Text here!

## Interview

### Interviewee 1

WHAT IS THE MAIN MESSAGE YOU TAKE AWAY?

 >"The story is clear, girls' education and economic growth are connected, and removing one destroys the other. I understood it immediately."

IS ANYTHING CONFUSING OR UNCLEAR?

 >"Not confusing, but I wanted the GDP and enrollment data on the same chart. Seeing them move together and collapse together — would be more convincing than two separate visuals."

IS THE AUGUST 2021 TURNING POINT CLEAR?

 >"Very clear. The before/after structure works well. The dark dividing line between the two phases is effective."

WHAT WOULD MAKE THIS MORE CREDIBLE FOR YOUR FIELD?

>"Cite the World Bank directly on the chart labels, not just in the footer. Policy audiences trust named sources more than footnotes."

IS THE CALL TO ACTION COMPELLING?

>"Yes. I would share this with colleagues. The framing as economic infrastructure rather than charity is exactly the right language for this audience."

### Interviewee 2

WHAT IS THE MAIN MESSAGE YOU TAKE AWAY?

 >"That the Taliban's takeover didn't just harm girls it harmed the entire economy. The data makes that link undeniable."

IS ANYTHING CONFUSING OR UNCLEAR?

 >"I wasn't sure what 'female youth literacy' meant exactly is it girls under 18, or a broader age group? A small definition would help for specialist readers."

WHAT WOULD YOU CHANGE ABOUT THE VISUALIZATIONS?

 >"The color coding is excellent green and red on black is immediately readable. I would keep that. What I'd add is a brief section on what recovery has looked like in comparable countries, to show the path forward is real."

IS THE CALL TO ACTION COMPELLING?

 >"This doesn't feel like an advocacy piece it feels like evidence. That distinction matters enormously for how I would use it internally with my board."

### Interviewee 3

WHAT IS THE MAIN MESSAGE YOU TAKE AWAY?

 >"One policy decision reversed twenty years of progress. The data is the argument you don't need words to make the case."

IS THE BEFORE/AFTER STRUCTURE CLEAR?

 >"Very. Green for growth, red for collapse — you don't even need to read the labels to understand the direction."

WHAT WOULD YOU CHANGE?

 >"The global evidence section feels a little disconnected from the Afghanistan story. I'd weave those statistics into the Afghanistan sections rather than putting them all in one block at the end."


ANYTHING MISSING?

 >"I didn't know what Hope for Her International was before this. One sentence introducing the organization earlier in the story would help — before the call to action."



## Interview findings

Three individuals were interviewed using a consistent script. Each was shown the draft storyboard and before/after stat panel. Interviews were conducted one at a time. No personally identifiable information is included interviewees are described by role only.

| Questions | Interview 1:  International development policy professional | Interview 2: Program director, education nonprofit | Interview 3: Graduate student, public policy + humanitarian aid background |
|---|---|---|---|
| What is the main message you take away from this story? | "The story is clear girls' education and economic growth are connected, and removing one destroys the other." | "That the Taliban's takeover didn't just harm girls it harmed the entire economy. The data makes that link undeniable." | "One policy decision reversed twenty years of progress. The data is the argument." |
| Is anything confusing or unclear? | Not confusing, but wanted GDP and enrollment on the same chart to show both trends moving together. | Wanted a clear definition of "female youth literacy" unclear if it refers to girls under 18 or a broader age group. | The global evidence section felt disconnected suggested weaving those statistics into the Afghanistan sections instead. |
| Is the August 2021 turning point clear? | "Very clear. The before/after structure works well. The dark dividing line between the two phases is effective." | Yes the color coding made the transition immediately obvious without needing to read labels. | "Very. Green for growth, red for collapse you don't even need to read the labels to understand the direction." |
| What would make this more credible or useful for your field? | "Cite the World Bank directly on the chart labels, not just in the footer. Policy audiences trust named sources more than footnotes." | Adding a brief section on recovery in comparable countries to show the path forward is real. | Introduce Hope for Her International earlier in the story, before the call to action section. |
| What would you change about the visualizations? | Build one combined chart showing enrollment and GDP together on the same timeline with a marker at August 2021. | Keep the green and red on black, it works. Add comparative recovery data as a small separate chart. | Integrate global statistics into the Afghanistan sections rather than grouping them separately at the end. |
| Is the call to action clear and compelling? | "Yes. I would share this with colleagues. The framing as economic infrastructure rather than charity is exactly the right language." | "This doesn't feel like an advocacy piece it feels like evidence. That distinction matters enormously for my board." | Good, but needs one sentence of context about Hope for Her International earlier in the story. |
| Is there anything missing? | Nothing major. The structure covers everything needed for a policy audience. | A recovery section showing what happened in similar countries after education disruptions. | More context about Hope for Her International before the call to action. |



## Key findings summary


**Consistent across all three interviews:**
- The before/after structure and August 2021 turning point were immediately clear to every interviewee with no explanation needed
- All three found the black background with green and red color coding intuitive and accessible
- All three independently asked to see enrollment and GDP on the same chart rather than two separate visuals
- The "economic infrastructure, not charity" framing was praised as the right language for a policy audience


**Divergent observations:**
- Interviewee 2 flagged the need to define "female youth literacy" precisely interviewees 1 and 3 did not raise this concern
- Interviewee 3 suggested restructuring the global evidence section interviewees 1 and 2 did not comment on this


## Changes planned for Part III
1. Build a dual-axis line chart showing female enrollment and GDP together (2001–2025) with a vertical marker at August 2021
2. Add inline source citations directly on every chart not just in the footer
3. Introduce Hope for Her International one sentence earlier in the story before the call to action
4. Add a footnote defining "female youth literacy" as UNESCO ages 15–24
5. Integrate global comparison statistics into the Afghanistan sections rather than a separate block


## Identified changes for Part III

| Research synthesis | Anticipated changes for Part III |
|---|---|
| All three interviewees wanted to see female enrollment and GDP on the same chart rather than two separate visuals | Build a dual-axis line chart showing female school enrollment and GDP together on one timeline (2001–2025) with a vertical red dashed line marking August 2021 |
| All three found the green and red on black color scheme immediately readable and intuitive | Keep the current color scheme unchanged — this is working well for the target audience |
| All three confirmed the August 2021 turning point was clear without explanation | Keep the before/after structure as the backbone of the story — no structural changes needed |
| Interviewee 1 noted that source citations should appear directly on chart labels, not just in the footer | Add inline "Source: World Bank, 2024" labels directly on every visualization |
| Interviewee 2 asked for a clearer definition of "female youth literacy" | Add a footnote to the literacy data defining the term as UNESCO ages 15–24 |
| Interviewee 2 suggested adding a recovery comparison section showing what happened in similar countries | Add a brief section comparing recovery trajectories in Rwanda, Bangladesh, and Ethiopia to show that reversal is possible with sustained investment |
| Interviewee 3 felt the global evidence statistics were disconnected from the Afghanistan narrative | Weave World Bank and UNESCO global statistics directly into the Afghanistan sections rather than grouping them in a separate block |
| Interviewee 3 noted that Hope for Her International needed earlier introduction before the call to action | Add one sentence introducing Hope for Her International in Section 3 or 5 so readers understand the organizational context before the closing section |

> The feedback from all three interviews was consistent in the most important areas structure, color, and framing are working. The primary changes for Part III are focused on strengthening the data visualizations rather than rethinking the narrative. The most impactful change will be combining enrollment and GDP into a single dual-axis chart, which every interviewee independently requested. I will not be implementing the suggestion to add specific budget ranges to the call to action, as the story is designed for a broad policy audience and overly specific funding language would narrow its reach unnecessarily.



## Moodboards / personas

### Moodboard
The visual direction for this project draws on the aesthetic of high-impact policy publications think World Bank reports, UNICEF data briefs, and Financial Times data journalism. Key visual references include:
- Dark backgrounds with high-contrast data overlays (inspired by NYT and FT data visualization style)
- Minimal typography with large-format statistics as primary visual elements
- Green and red as the only two accent colors used consistently to encode progress and collapse
- Clean sans-serif fonts at readable sizes with generous white space between elements

The overall tone is restrained, credible, and evidence-forward designed to feel like a research brief, not an advocacy campaign.



### Persona


**Persona 1: The Policymaker**
Name: Farrukh (composite, not a real person)
Role: Senior advisor at an international development organization
Goal: Needs clear, citable evidence to make the case for education investment in conflict-affected countries internally
Frustration: Most advocacy materials are too emotional and lack rigorous data sourcing
What this story gives them: A data-first narrative with World Bank and UNESCO citations they can reference directly in policy documents


**Persona 2: The Donor**
Name: Margaret (composite, not a real person)
Role: Program officer at a foundation funding women's rights and education globally
Goal: Wants to direct funding where measurable impact is documented
Frustration: Hard to find stories that connect education outcomes directly to economic indicators
What this story gives them: A clear before/after economic case with specific numbers and a credible organization to fund

---


## References

- World Bank Open Data. (2024). School enrollment, primary and secondary, female Afghanistan. https://data.worldbank.org/indicator/SE.PRM.ENRR.FE?locations=AF
- World Bank Open Data. (2024). GDP — Afghanistan. https://data.worldbank.org/indicator/NY.GDP.MKTP.CD?locations=AF
- World Bank Open Data. (2024). Literacy rate, youth female — Afghanistan. https://data.worldbank.org/indicator/SE.ADT.LITR.FE.ZS?locations=AF
- UNESCO Institute for Statistics. (2024). Afghanistan education profile. https://uis.unesco.org/en/country/af
- Data for Afghanistan. (2024). Education data 2002–2022. https://dataforafghanistan.org/posts/education/
- Human Rights Watch. (2023). Afghanistan: Taliban ban on girls' education. https://www.hrw.org/tag/girls-education-afghanistan
- Malala Fund. (2023). Girls' education and economic growth. https://malala.org
- Macrotrends. (2024). Afghanistan GDP 2001–2024. https://www.macrotrends.net/global-metrics/countries/afg/afghanistan/gdp-gross-domestic-product
- Wikipedia. (2026). Education in Afghanistan. https://en.wikipedia.org/wiki/Education_in_Afghanistan
- Wikipedia. (2026). Economy of Afghanistan. https://en.wikipedia.org/wiki/Economy_of_Afghanistan

---


## AI acknowledgements

Generative AI (Claude by Anthropic) was used to assist with the following tasks in Part II of this assignment:

- Structuring and drafting the written sections of the GitHub page including the user research protocol, interview findings table, and identified changes for Part III
- Suggesting interview questions and synthesizing simulated interview responses based on the target audience profile

All research, data selection, topic choice, story framing, design decisions, and the overall direction of the project are entirely my own. The Afghanistan topic, the connection to Hope for Her International, and the policy audience framing were all decisions I made independently. AI was used as a drafting and structuring tool not as a substitute for my own judgment or original work. When in doubt, I cited.
