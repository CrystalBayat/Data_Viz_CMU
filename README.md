| [home page](https://crystalbayat.github.io/Data_Viz_CMU/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Portfolio
My data visualization work for 94-870 at CMU

# About me
A passionate woman from Afghanistan, using data to drive social impact. I love turning complex data into clear, compelling visualizations for non-expert. MSPPM

# What I hope to learn
I want to learn how to professionally and powerfully tell a story through data. After graduation, I plan to work at the intersection of data, public policy, and international development using visualization to drive impact for women and girls globally.


# Portfolio

## Assignment 2: Visualizing government Debt

<div class='tableauPlaceholder' id='viz1775008456004' style='position: relative'><noscript><a href='#'><img alt='OECD Countries Spending More Relative To What They Earn ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;TS&#47;TSWDAssignmentOECD_17748102150730&#47;OECDCountriesSpendingMoreRelativeToWhatTheyEarn&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='TSWDAssignmentOECD_17748102150730&#47;OECDCountriesSpendingMoreRelativeToWhatTheyEarn' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;TS&#47;TSWDAssignmentOECD_17748102150730&#47;OECDCountriesSpendingMoreRelativeToWhatTheyEarn&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    
  var divElement = document.getElementById('viz1775008456004');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

For my redesigned visualization, I chose to create a horizontal bar chart showing the debt-to-GDP ratio for all OECD countries in 2023, three years after the start of the COVID-19 pandemic. I wanted to answer a simple but important question: which countries still owe more than they earn? To make this clear, I used a reference line at 100% of GDP and split the colors at that threshold — orange for countries whose debt exceeds their GDP, and blue for countries below that line. I chose orange and blue because they provide strong contrast and are easy to tell apart, even for viewers with color vision differences. The reference line at 100% gives the reader an instant anchor point, so they do not need to read every number to understand the story.

I chose a horizontal bar chart because it is easy to read when there are many countries to compare. The country names sit on the left side and the bars extend to the right, which makes it natural to scan from top to bottom and quickly see which countries carry the highest debt. I sorted the bars in descending order so the most indebted countries appear first, drawing attention to Japan, Greece, and Italy right away. I also added the exact debt values at the end of each bar so the reader can get precise numbers without hovering. Compared to the heatmap from Part 2, I think this visualization tells a more focused story. The heatmap is useful for seeing patterns across many years, but it is dense and hard to pull out one clear message. My bar chart focuses on a single year and a single question, which makes it easier for the viewer to walk away with a clear takeaway: in 2023, ten OECD countries still owed more than they earned in a year, with Japan leading at 228% of GDP.

## Heat Map 
<div class='tableauPlaceholder' id='viz1775008735114' style='position: relative'><noscript><a href='#'><img alt='Government Debt-to-GDP Ratios Across OECD Countries (2007–2023) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Fi&#47;Final_Version_Assignment_DV_2&#47;Heatmap&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Final_Version_Assignment_DV_2&#47;Heatmap' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Fi&#47;Final_Version_Assignment_DV_2&#47;Heatmap&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1775008735114');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

## References and AI Acknowledgement: 
I used the OECD dataset provided in the assignment (General Government Debt, % of GDP, 2007–2024). I also referenced the Datawrapper article on choosing colors for data visualization and the "Make Grey Your Best Friend" article from Visualising Data. I used Claude (AI) to help me brainstorm visualization ideas. 
