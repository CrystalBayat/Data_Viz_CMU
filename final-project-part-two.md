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

<h2>Data Visualizations and Wireframes</h2>

<h2>Wireframes and Sketches</h2>

<style>
.sketch-block{background:#fff;border:1px solid #e5e7eb;border-radius:8px;padding:24px;margin:28px 0;}
.sketch-block h3{font-size:16px;font-weight:700;color:#2563eb;margin-bottom:12px;}
.spec-list{padding-left:20px;margin:12px 0;font-size:14px;color:#374151;}
.spec-list li{margin:6px 0;}
.pill{display:inline-block;width:10px;height:10px;border-radius:50%;vertical-align:middle;margin-right:3px;}
.green-pill{background:#4ade80;}
.red-pill{background:#f87171;}
.gray-pill{background:#9ca3af;}
.gold-pill{background:#f59e0b;}
.final-label{font-family:'Courier New',monospace;font-size:11px;text-transform:uppercase;letter-spacing:.08em;color:#6b7280;margin:20px 0 8px;}
.viz-wrap{background:#0a0a0a;border-radius:6px;overflow:hidden;min-height:400px;margin-bottom:8px;}
.tableau-link{font-family:'Courier New',monospace;font-size:12px;color:#2563eb;text-decoration:none;}
.tableau-link:hover{text-decoration:underline;}
.impl-note{font-size:13px;color:#374151;background:#f0fdf4;border-left:3px solid #4ade80;padding:8px 12px;margin-top:12px;}
.stat-compare{display:grid;grid-template-columns:1fr auto 1fr;gap:16px;align-items:center;margin:16px 0;}
.stat-side{background:#0a0a0a;border-radius:6px;padding:20px;}
.side-label{font-family:'Courier New',monospace;font-size:10px;text-transform:uppercase;letter-spacing:.1em;margin-bottom:14px;color:#6b7280;}
.stat-item{display:flex;align-items:baseline;gap:10px;margin:10px 0;}
.stat-num{font-family:Georgia,serif;font-size:22px;font-weight:700;}
.stat-num.green{color:#4ade80;}
.stat-num.gray{color:#6b7280;}
.stat-desc{font-size:12px;color:#9ca3af;}
.stat-arrow{font-size:28px;color:#6b7280;text-align:center;}
</style>

<!-- SKETCH 1 -->
<div class="sketch-block">
<h3>Sketch 1 — Before/After Stat Comparison</h3>
<p>Four stat cards showing the scale of progress from 2001 to 2021. Starting point vs peak achievement.</p>
<div class="stat-compare">
  <div class="stat-side">
    <div class="side-label">2001 — Starting Point</div>
    <div class="stat-item"><span class="stat-num gray">50,000</span><span class="stat-desc">Girls in school</span></div>
    <div class="stat-item"><span class="stat-num gray">11%</span><span class="stat-desc">Female youth literacy</span></div>
    <div class="stat-item"><span class="stat-num gray">$2.8B</span><span class="stat-desc">GDP</span></div>
  </div>
  <div class="stat-arrow">→</div>
  <div class="stat-side">
    <div class="side-label">2021 — Peak Progress</div>
    <div class="stat-item"><span class="stat-num green">3.2M</span><span class="stat-desc">Girls in school</span></div>
    <div class="stat-item"><span class="stat-num green">44%</span><span class="stat-desc">Female youth literacy</span></div>
    <div class="stat-item"><span class="stat-num green">$19.9B</span><span class="stat-desc">GDP</span></div>
  </div>
</div>
<p class="impl-note">→ Implemented as: Shorthand stat card section with green numbers on black background.</p>
</div>

<!-- SKETCH 2 + CHART 1 -->
<div class="sketch-block">
<h3>Sketch 2 — Dual Axis Line Chart: Girls Enrollment + GDP (2001–2021)</h3>
<p>Two lines on one chart. Green solid line for girls enrolled (left axis). Gray dashed line for GDP (right axis). Both move upward together demonstrating the correlation between education and economic growth.</p>
<ul class="spec-list">
  <li>X axis: Year (2001–2021)</li>
  <li>Y axis left: Girls enrolled (0 to 3.5M)</li>
  <li>Y axis right: GDP in billions USD ($0B to $22B)</li>
  <li><span class="pill green-pill"></span>Green (#4ade80) enrollment · <span class="pill gray-pill"></span>Gray dashed GDP · Background: #0a0a0a</li>
  <li>Source: World Bank Open Data · Macrotrends</li>
</ul>
<p class="final-label">Final Tableau Visualization — Chart 1:</p>
<div class="viz-wrap">
  <div class='tableauPlaceholder' id='viz_c1' style='position:relative;width:100%;'>
    <noscript><a href='#'><img alt='Education built the economy' src='https://public.tableau.com/static/images/Bo/Book1_17761379516120/GirlsenrollmentandGDProsetogether20012021/1_rss.png' style='border:none;width:100%'/></a></noscript>
    <object class='tableauViz' style='display:none;'>
      <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F'/>
      <param name='embed_code_version' value='3'/>
      <param name='site_root' value=''/>
      <param name='name' value='Book1_17761379516120/GirlsenrollmentandGDProsetogether20012021'/>
      <param name='tabs' value='no'/><param name='toolbar' value='no'/>
      <param name='animate_transition' value='yes'/>
      <param name='display_static_image' value='yes'/>
      <param name='display_spinner' value='yes'/>
      <param name='display_count' value='yes'/>
      <param name='language' value='en-US'/>
    </object>
  </div>
</div>
<a class="tableau-link" href="https://public.tableau.com/views/Book1_17761379516120/GirlsenrollmentandGDProsetogether20012021" target="_blank">→ View on Tableau Public</a>
</div>

<!-- SKETCH 3 + CHART 2 -->
<div class="sketch-block">
<h3>Sketch 3 — GDP Line Chart: Green to Red (2001–2023)</h3>
<p>A single continuous line showing Afghanistan GDP from 2001 to 2023. Green during growth, turns red at August 2021. Vertical reference line marks the Taliban takeover.</p>
<ul class="spec-list">
  <li>X axis: Year (2001–2023) · Y axis: GDP in billions USD</li>
  <li><span class="pill green-pill"></span>Green (#4ade80) before 2021 · <span class="pill red-pill"></span>Red (#f87171) after 2021</li>
  <li>Reference line: Red vertical at 2021 labeled "Taliban Aug 2021"</li>
  <li>Background: #0a0a0a · Source: World Bank · Macrotrends</li>
</ul>
<p class="final-label">Final Tableau Visualization — Chart 2:</p>
<div class="viz-wrap">
  <div class='tableauPlaceholder' id='viz_c2' style='position:relative;width:100%;'>
    <noscript><a href='#'><img alt='GDP collapse' src='https://public.tableau.com/static/images/GD/GDP_17761769902120/Sheet1/1_rss.png' style='border:none;width:100%'/></a></noscript>
    <object class='tableauViz' style='display:none;'>
      <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F'/>
      <param name='embed_code_version' value='3'/>
      <param name='site_root' value=''/>
      <param name='name' value='GDP_17761769902120/Sheet1'/>
      <param name='tabs' value='no'/><param name='toolbar' value='no'/>
      <param name='animate_transition' value='yes'/>
      <param name='display_static_image' value='yes'/>
      <param name='display_spinner' value='yes'/>
      <param name='display_count' value='yes'/>
      <param name='language' value='en-US'/>
      <param name='filter' value='publish=yes'/>
    </object>
  </div>
</div>
<a class="tableau-link" href="https://public.tableau.com/views/GDP_17761769902120/Sheet1" target="_blank">→ View on Tableau Public</a>
</div>

<!-- SKETCH 4 + CHART 3 -->
<div class="sketch-block">
<h3>Sketch 4 — Female Youth Literacy Bar Chart (2001–2025)</h3>
<p>Four bars showing female youth literacy at key points. Each bar color signals meaning: gray start, gold progress, green peak, red reversal.</p>
<ul class="spec-list">
  <li><span class="pill gray-pill"></span>2001 (11%) · <span class="pill gold-pill"></span>2011 (17%) · <span class="pill green-pill"></span>2021 (44%) · <span class="pill red-pill"></span>2025 projected (28%)</li>
  <li>Labels: Percentage on top of each bar · "(Projected)" annotation on 2025</li>
  <li>Background: #0a0a0a · Source: UNESCO Institute for Statistics · World Bank WDI</li>
</ul>
<p class="final-label">Final Tableau Visualization — Chart 3:</p>
<div class="viz-wrap">
  <div class='tableauPlaceholder' id='viz_c3' style='position:relative;width:100%;'>
    <noscript><a href='#'><img alt='Literacy bars' src='https://public.tableau.com/static/images/li/literacyrate_17761763986470/Sheet1/1_rss.png' style='border:none;width:100%'/></a></noscript>
    <object class='tableauViz' style='display:none;'>
      <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F'/>
      <param name='embed_code_version' value='3'/>
      <param name='site_root' value=''/>
      <param name='name' value='literacyrate_17761763986470/Sheet1'/>
      <param name='tabs' value='no'/><param name='toolbar' value='no'/>
      <param name='animate_transition' value='yes'/>
      <param name='display_static_image' value='yes'/>
      <param name='display_spinner' value='yes'/>
      <param name='display_count' value='yes'/>
      <param name='language' value='en-US'/>
    </object>
  </div>
</div>
<a class="tableau-link" href="https://public.tableau.com/views/literacyrate_17761763986470/Sheet1" target="_blank">→ View on Tableau Public</a>
</div>

<!-- SKETCH 5 + CHART 4 -->
<div class="sketch-block">
<h3>Sketch 5 — GDP Collapse Bar Chart (2017–2022)</h3>
<p>Six bars showing Afghanistan GDP 2017–2022. Four tall green bars of stable growth, then two dramatic red bars — the collapse after August 2021.</p>
<ul class="spec-list">
  <li><span class="pill green-pill"></span>2017–2020 (green) stable growth · <span class="pill red-pill"></span>2021–2022 (red) collapse</li>
  <li>Dollar value labels on top of every bar · "−28% in one year" annotation on 2021</li>
  <li>Background: #0a0a0a · Source: World Bank · Macrotrends</li>
</ul>
<p class="final-label">Final Tableau Visualization — Chart 4:</p>
<div class="viz-wrap">
  <div class='tableauPlaceholder' id='viz_c4' style='position:relative;width:100%;'>
    <noscript><a href='#'><img alt='GDP collapse bars' src='https://public.tableau.com/static/images/Bo/Book2_17761805420180/Dashboard1/1_rss.png' style='border:none;width:100%'/></a></noscript>
    <object class='tableauViz' style='display:none;'>
      <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F'/>
      <param name='embed_code_version' value='3'/>
      <param name='site_root' value=''/>
      <param name='name' value='Book2_17761805420180/Dashboard1'/>
      <param name='tabs' value='no'/><param name='toolbar' value='no'/>
      <param name='animate_transition' value='yes'/>
      <param name='display_static_image' value='yes'/>
      <param name='display_spinner' value='yes'/>
      <param name='display_count' value='yes'/>
      <param name='language' value='en-US'/>
      <param name='filter' value='publish=yes'/>
    </object>
  </div>
</div>
<a class="tableau-link" href="https://public.tableau.com/views/Book2_17761805420180/Sheet1" target="_blank">→ View on Tableau Public</a>
</div>

<!-- TABLEAU LOADER -->
<script type='text/javascript'>
window.addEventListener('load',function(){
  [
    {id:'viz_c1',h:null},
    {id:'viz_c2',h:null},
    {id:'viz_c3',h:null},
    {id:'viz_c4',h:'795px'}
  ].forEach(function(c){
    var d=document.getElementById(c.id);
    if(!d)return;
    var v=d.getElementsByTagName('object')[0];
    v.style.width='100%';
    v.style.height=c.h||(d.offsetWidth*0.65)+'px';
    var s=document.createElement('script');
    s.src='https://public.tableau.com/javascripts/api/viz_v1.js';
    v.parentNode.insertBefore(s,v);
  });
});
</script>

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
