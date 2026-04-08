[Home Page](https://crystalbayat.github.io/Data_Viz_CMU/) | [Class Work](https://crystalbayat.github.io/Data_Viz_CMU/classwork) | [Assignment](https://crystalbayat.github.io/Data_Viz_CMU/Assignment) | [Final Project I](https://crystalbayat.github.io/Data_Viz_CMU/final-project-part-one) | [Final Project II](https://crystalbayat.github.io/Data_Viz_CMU/final-project-part-two) | [Final Project III](https://crystalbayat.github.io/Data_Viz_CMU/final-project-part-three)


This page documents my assignments and critques from Telling Stories with Data

## Assignment I

# Critique by Design

**Graphic Selected:** Graphic 2:  Access to Electricity (% of population), World Bank 2023

---

## The Original Graphic
<img width="593" height="539" alt="Screenshot 2026-04-06 at 10 31 31 PM" src="https://github.com/user-attachments/assets/cdbb0ea3-2ba2-4de2-953e-aef2e7f7812b" />

> **Source:** SDG 7.1.1 Electrification Dataset, World Bank (WB)
> **Published:** 2023 | **License:** CC BY-4.0
> [View Original Source](https://data.worldbank.org/indicator/EG.ELC.ACCS.ZS?type=shaded&view=map)


---

## What I Observed First

The first thing I noticed when I look at this map is **Africa**. Most of the countries in sub-Saharan Africa are shown in very light blue, which means they have the lowest electricity access. My eye goes there right away because it is the region with the lightest color and the most visible difference from the rest of the world.

After that, I look at the legend in the bottom right corner and I see that the lightest color means **less than 22.10%** of the population has electricity. This is a very alarming number, but the chart does not make it feel urgent at all.

I also notice that the ocean color is almost the same blue as some of the country colors, which makes it hard to see where the ocean ends and where a country begins. The title just says *"Access to electricity (% of population)"* which describes the data but does not tell me what I should take away from looking at this map.



## What I Like

- The **choice to use a map** is right for this kind of data. It helps the reader understand geographic patterns in a way a bar chart or table could not.
- The **data source is clearly written** at the top it includes the SDG reference, the World Bank as publisher, the date, and the license. This makes the chart feel trustworthy.
- The chart has **three views: Line, Bar, and Map** which gives different types of readers different ways to explore the data.

---

## What I Dislike

- **The color palette** is the biggest problem. All five categories use shades of the same blue, and the middle three shades look almost identical. It is very hard to tell them apart without staring at the legend.
- **The legend** is very small, placed in the bottom right corner where it overlaps with some countries, and the font is too small to read comfortably.
- **The ocean background** is a teal blue that looks very similar to the country fill colors, especially for smaller island countries and coastal areas.
- **No country names or labels** anywhere on the map — a reader who does not know African geography will not be able to identify which countries have the worst electricity access.
- **The title does not tell a story** it only describes the data, not what it means.
- **Typography issues** the legend font is around 9pt, which is too small. There is no visual hierarchy in the title.

---

## What I Wish I Saw

- A **diverging color scale** — red or orange for low electricity access, green for high access — so a reader immediately feels urgency.
- A **story-driven title** like: *"Hundreds of millions of people in sub-Saharan Africa still have no electricity in 2023."*
- A **zoomed-in panel showing Africa** in more detail, since that is where the most important story is.
- A **larger legend** with population figures knowing a percentage applies to hundreds of millions of people makes the data feel more real.
- A **visible play button** on the time slider so readers can watch change from 2000 to 2023.

---

## Three Things I Would Change

### 1. Change the Color Palette
**I would replace the five shades of blue with a diverging color scale.**

| Range | Old Color | New Color |
|-------|-----------|-----------|
| < 22.10% | Light blue | 🔴 Deep red |
| 22.10 – 40.50% | Light-medium blue | 🟠 Orange |
| 40.50 – 62.00% | Medium blue | 🟡 Yellow |
| 62.00 – 76.80% | Medium-dark blue | 🟢 Light green |
| > 76.80% | Dark blue | 🟢 Dark green |

Using only shades of blue makes the most important differences invisible. A diverging palette from red to green would immediately show which countries are in crisis and which have succeeded.

---

### 2. Rewrite the Title
**I would change the title from:** *"Access to electricity (% of population)"*

**To:** *"Sub-Saharan Africa and parts of South Asia are the most left behind on electricity access in 2023."*

The current title only describes the structure of the data. A story-driven title helps a non-expert reader understand the point of the map in the first five seconds.

---

### 3. Improve the Legend
**I would make the legend bigger, move it to the left side, increase font size to at least 14pt, and add population estimates.**

For example: *"> 76.80% — approximately 5.8 billion people"*

Moving it to the left and making it larger would make it much easier to use. Adding population figures would transform the legend from just a color key into a real piece of data that helps the reader understand the scale of the problem.

---

## What Copilot Recommended

| Recommendation | Because |
|----------------|---------|
| Change the ocean/background to neutral light gray | The teal-blue ocean is too similar to mid-range country colors, making it hard to distinguish land from water |
| Add a zoomed-in inset map of sub-Saharan Africa | The full world map compresses Africa into a small space; an inset would let readers clearly see individual countries |
| Make the time slider larger with a play button and labeled key years (2000, 2010, 2015, 2023) | The thin slider is easy to miss; a play button would make the chart much more engaging |

---

## Final Synthesized Recommendations

### Recommendation 1 *(My observation)*
> **Change the color palette** from five shades of blue to a diverging scale deep red for lowest access to dark green for highest. This is the most important design problem in the entire chart. A reader should be able to look at this map for five seconds and immediately understand which regions are in crisis.

### Recommendation 2 *(Synthesis — Me + Copilot)*
> **Change the ocean background to neutral light gray AND move the legend** to the left side, make the font larger, and add population figures. These two changes work together a cleaner background makes the country colors easier to read, and a better legend makes those colors easier to understand. Doing one without the other would only solve half the problem.

### Recommendation 3 *(Copilot recommendation, extended by me)*
> **Make the timeline slider more visible** with a clear play button and labeled key years (2000, 2010, 2015), AND connect it to a **dynamic title** that updates as the year changes for example: *"In 2000, over 1.5 billion people lacked electricity access."* This goes beyond Copilot's suggestion by connecting the animation to the title so the whole chart tells a story of change over time.

---

## Good Charts Matrix Score

I placed this graphic at approximately **+5 on design execution** and **+6 on contextual awareness.**

- **Contextual awareness is high** because the data comes directly from the World Bank's SDG 7.1.1 tracking system one of the most credible global sources for development data. The chart clearly cites its source, license, and date.
- **Design execution is moderately positive** the chart type and data sourcing are done well, but the color palette, legend, and title still hold it back from being excellent.

> The chart has very strong data but the design does not fully do justice to the story inside it.

---

## Reflection on AI Use

I relied **more on my own observations** for this assignment. The two most important recommendations, changing the color palette and rewriting the title both came from my own reaction when I first looked at the chart.

Copilot's suggestions were helpful for thinking about smaller details like the background color and the time slider, but they were more surface-level fixes. I think of AI as a starting point for thinking, not a final answer, and this assignment confirmed that for me.

I feel most confident in my **color palette recommendation** because it came entirely from my own observation and addresses the root cause of the chart's communication failure.

---

## References

- Berinato, S. (2016). *Good charts: The HBR guide to making smarter, more persuasive data visualizations.*
- World Bank. (2023). Access to electricity (% of population). SDG 7.1.1 Electrification Dataset. [https://data.worldbank.org](https://data.worldbank.org/indicator/EG.ELC.ACCS.ZS?type=shaded&view=map)
- OpenAI. (2026). ChatGPT (March 2026 version). [https://chat.openai.com](https://chat.openai.com/)

---
## Assignment II 

# Working with Tableau: Visualizing Government Debt
 
# After the Pandemic: Which OECD Countries Owe More Than They Earn? (2023)


<div class='tableauPlaceholder' id='viz1775531663915' style='position: relative'><noscript><a href='#'><img alt='After the Pandemic: Which OECD Countries Owe More Than They Earn? (2023) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Fi&#47;Final_Version_Assignment_DV_2_2&#47;Part3Assignment&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Final_Version_Assignment_DV_2_2&#47;Part3Assignment' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Fi&#47;Final_Version_Assignment_DV_2_2&#47;Part3Assignment&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>                   
 var divElement = document.getElementById('viz1775531663915');
 var vizElement = divElement.getElementsByTagName('object')[0]; vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
 var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';           vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>


 
For my redesigned visualization, I chose to create a horizontal bar chart showing the debt-to-GDP ratio for all OECD countries in 2023, three years after the start of the COVID-19 pandemic. I wanted to answer a simple but important question: which countries still owe more than they earn? To make this clear, I used a reference line at 100% of GDP and split the colors at that threshold orange for countries whose debt exceeds their GDP, and blue for countries below that line. I chose orange and blue because they provide strong contrast and are easy to tell apart, even for viewers with color vision differences. The reference line at 100% gives the reader an instant anchor point, so they do not need to read every number to understand the story. 
I chose a horizontal bar chart because it is easy to read when there are many countries to compare. The country names sit on the left side and the bars extend to the right, which makes it natural to scan from top to bottom and quickly see which countries carry the highest debt. I sorted the bars in descending order so the most indebted countries appear first, drawing attention to Japan, Greece, and Italy right away. I also added the exact debt values at the end of each bar so the reader can get precise numbers without hovering. 

# Government Debt-to-GDP Ratios Across OECD Countries (2007–2023) 

<div class='tableauPlaceholder' id='viz1775531798635' style='position: relative'><noscript><a href='#'><img alt='Government Debt-to-GDP Ratios Across OECD Countries (2007–2023) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Fi&#47;Final_Version_Assignment_DV_2&#47;Heatmap&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Final_Version_Assignment_DV_2&#47;Heatmap' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Fi&#47;Final_Version_Assignment_DV_2&#47;Heatmap&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    
 var divElement = document.getElementById('viz1775531798635');                    
 var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
 var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js'; vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>


Compared to the heatmap from Part 2, I think this visualization tells a more focused story. The heatmap is useful for seeing patterns across many years, but it is dense and hard to pull out one clear message. My bar chart focuses on a single year and a single question, which makes it easier for the viewer to walk away with a clear takeaway: in 2023, ten OECD countries still owed more than they earned in a year, with Japan leading at 228% of GDP.

# References and AI Acknowledgement: 
I used the OECD dataset provided in the assignment (General Government Debt, % of GDP, 2007–2024). I also referenced the Datawrapper article on choosing colors for data visualization and the "Make Grey Your Best Friend" article from Visualising Data. I used Claude (AI) to help me brainstorm visualization ideas. 



## Assignment III

# Gold Spot Price Chart

## Step one:

I selected the BullionVault Live Gold Spot Price Chart from MakeoverMonday Week 5, 2026. The chart shows one month of gold prices in March 2026, displayed as a line/area chart with dual y-axes (USD/kg and USD/oz).
I chose this visualization because gold prices experienced a dramatic crash in March 2026 due to the escalating Iran-Israel conflict, and I wanted to see how well the original chart communicated that story. I noticed right away that while the chart showed the price movement, it offered no context or explanation for why prices were moving - which seemed like a missed opportunity for a financial platform whose users are making buying and selling decisions.


<img width="1076" height="612" alt="Screenshot 2026-04-01 at 10 50 52 PM" src="https://github.com/user-attachments/assets/873a3ffe-02a1-4a1e-aeb1-bceccb4ff4a2" />

Image Source: BullionVault, March 2026


## Step two: The Critique
Using Stephen Few's Data Visualization Effectiveness Profile, I evaluated the chart across seven categories. Here are the key findings:
What worked well: The chart uses a familiar line chart format that most people understand immediately (Intuitiveness: 7/10). The current price is clearly labeled, and the general trend is easy to follow. For a quick price check, the chart does its job.

What didn't work well: The chart has several issues that limit its effectiveness:
Completeness (4/10): There are no annotations explaining the big price drop around March 19-23. The news article below the chart mentions the Iran war and Turkey selling gold reserves, but none of that context appears on the chart itself.

Truthfulness (5/10): The y-axis doesn't start at zero, which makes a roughly 15% price decline look like an even more dramatic crash. While truncated axes are common in financial charts, the visual impression is more alarming than the data warrants.

Perceptibility (5/10): The large "BullionVault" watermark sits directly on top of the data, making it harder to read. Dual y-axes (USD/kg and USD/oz) add unnecessary cognitive load.

Aesthetics (4/10): The watermark, cluttered toolbar, and low-contrast gold/yellow color scheme all hurt the visual presentation.

Engagement (4/10): The chart doesn't tell a story. There are no annotations, narrative elements, or context that would draw a viewer in.

Comparing Few's method to Good Charts: Few's method is more systematic. It forces you to evaluate specific measurable qualities one at a time. The Good Charts method focuses more on whether the chart successfully communicates an idea. I found that Few's method was better for identifying technical problems (truncated axes, poor contrast), while Good Charts was better for thinking about the overall story. One thing missing from Few's method is a category for storytelling or narrative whether the chart helps the audience understand not just the data but the meaning behind it.


## Step three: Sketch a solution

Based on my critique, I focused my redesign on three improvements:  Annotated line chart A clean line chart with a single y-axis (USD/oz), a descriptive title, and annotations marking the Iran conflict escalation and the subsequent recovery.

# Sketch 1

![IMG_0331](https://github.com/user-attachments/assets/351e43ac-59fc-4c9e-ab74-648a2cadac0c)


# Sketch 2

![IMG_0333](https://github.com/user-attachments/assets/c583a962-c0c7-4618-9307-e09f1eae773a)


Percentage change chart - Instead of raw price,I changed the percentage from the start of the month. This fixed the truthfulness issue by showing the actual magnitude of the drop with a clear baseline at 0%.

## Step four: Test the solution

I showed my wireframe sketches to two people and asked for feedback.

Person 1: student, MSPPM program
Understood it was a gold price chart right away
Found the annotations helpful said "I like that it tells me why the price dropped" was confused by sketch 2 (percentage change) asked what the baseline was suggested adding a data source label

Person 2: student, MISM
Preferred sketch 1 because it shows actual dollar values investors care about. Said the "loss zone" shading in sketch 2 was useful but felt dramatic
Suggested keeping the annotated line chart but adding reference lines for monthly high and low

Patterns: Both preferred sketch 1 (annotated line chart) over sketch 2 (percentage change). Sketch 2 needed more explanation, which goes against the goal of making the chart immediately understandable. Both valued the annotations as a major improvement over the original.

Design changes based on feedback: I decided to go with the annotated line chart approach (sketch 1), add a clear source label, and focus on making the story clear through three key annotations: the crash, the bottom, and the recovery.


## Step five: build the solution
Based on my critique and user feedback, I built the final redesign in Tableau. Here are the key changes I made from the original:
Single y-axis (USD per troy ounce) instead of dual axes reduces confusion
Clear, descriptive title that tells the viewer what happened before they even look at the data
Three annotations marking the key moments: the Iran conflict crash, the lowest point, and the partial recovery, No watermark obscuring the data, Source citation clearly labeled, Clean line chart with minimal visual clutter
The redesigned chart follows the narrative structure from Chapter 4 of Good Charts: setup (gold prices holding around $5,200), conflict (Iran-Israel conflict causes a crash), and resolution (partial recovery to $4,495).

<div class='tableauPlaceholder' id='viz1775100132678' style='position: relative'><noscript><a href='#'><img alt='Gold prices crash in March 2026 amid Iran conflict ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GoldPricesCrashes&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='GoldPricesCrashes&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GoldPricesCrashes&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
 var divElement = document.getElementById('viz1775100132678');
 var vizElement = divElement.getElementsByTagName('object')[0];
vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
 var scriptElement = document.createElement('script');
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>


# Summary
The original BullionVault chart was functional for a quick price check but missed an opportunity to help its audience investors understand what was happening and why. By adding annotations, simplifying the layout, and using a descriptive title, the redesigned chart tells the story of March 2026's gold price crash in a way that is both informative and immediately understandable. The biggest lesson from this process was how much impact simple additions like annotations and a clear title can have on turning raw data into a meaningful narrative.

## AI Usage: 
I used Claude (Anthropic) to help organize my critique responses, clean the raw data file for Tableau. All design decisions and the final Tableau visualization are my own work. 

## References: 
Data source: BullionVault via MakeoverMonday.


