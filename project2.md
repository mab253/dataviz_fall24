# 🤖🗺️📈 project #2

For this assignment, you will work with a team to research, analyze, develop, refine, and produce **web-based data map**, going through the entire life cycle of [computational information design](https://benfry.com/phd/dissertation/5.html).

### 🤸‍♀️ #1: form teams

- Your team is due by _before class_ on Nov. 13th.
- **Use your week Nov. 6th-13th** to form small teams as a class, preferably 2-3 people.
- I encourage you to look at the [sources list](https://github.com/mab253/dataviz_fall24/blob/main/sources-list.md) for data ideas, and maybe making "pitches" to your classmates. What data do you want to explore, and what are some skills that you could add to a team project?
- Your team list, and a short description of data domain that you will explore, is due by **Nov. 13th before class**, via a Discord post in `#general` channel. Only 1 submission necesary per team!
- If you would like me to match you to a team, please send me an e-mail before Nov. 13th.

### 📑 #2: collaborative data work!

- Go through a brief research phase as you explore the data domain and your dataset attributes. What context do you need to learn to understand the data? What key research questions might you focus on?
- Conduct exploratory data analysis - even though the final result will be JS, maybe you will use Python and `pandas` first - but you are welcome to use any tool.
- How many datasets do you need for your map? 
- Perform any data transformation or formatting that your project requires.
- Find a **story** in the data. What do you want to communicate in your final visualization?

### 📀 #3: deliverables

Every team will be responsible for:
- Presentation, 5-7 minutes, showing your map, including telling the story of your domain and any research questions, and giving the class a look into your process and analysis. Include a slide deck of visuals, on **Dec. 4th** in-class.
- Online-accessible, interactive version of your project, hosted at a [Glitch.com](https://glitch.com) URL, **due Sunday Dec. 1st** by 11:59pm
- Methodology section included as Markdown file (`README.md`) in Glitch project [(see below)](#📄-writings:-methodology-and-report), **due Dec. 1st** by 11:59pm
- Any supporting code (Jupyter notebook for Pandas, for example), with comments, **due Dec. 1st** by 11:59pm

SOME SUGGESTIONS ON PROCESS:
- some class time will be dedicated to teamwork on Nov. 13th and Nov. 20th, but this project also assumes significant work outside of class for the rest of the semester. I recommend using Discord, Glitch, Google Colab, and Zoom to collaborate, and to meet in-person if you can!
- ask for help! Please use the Discord to: post code that confuses you, request help debugging, ask for feedback on any drafts, etc. - from me or your classmates
- do create rough drafts - I recommend sketching by hand if that helps you, or use simple tools before your complex visualizations. If making a map, for example, you could try a draft in [Felt](https://felt.com/) before you work in code.
- you may delegate and divide the labor among your team members, but your final project needs to come together cohesively as 1 complete whole
- you may (and are encouraged to!) find outside sources to help with code, new libraries, online examples, etc. When you use these, **💥 remember to [cite your sources](https://github.com/mab253/dataviz_fall24/blob/main/ai-citations.md)!**
- document your process as you go; it will be helpful for your final reflection 

SOME THOUGHTS ON SCOPE & EXAMPLES:
- The goal here is to push beyond the defaults in all the platforms that we've learned to create something **original, beautiful, and full of useful information.**
- The work and final visualization(s) should show growth from project #1. How deeply can you dive into the data? How many drafts and exploratory visuals might you need? What new techniques or libraries might you need to learn?  How polished and user-friendly can the final viz be?
- Ideally, this project could go in your professional portfolios!

The project is open-ended for a reason - let your curiosity be your guide, and your final work should be unique rather than a copy of any of the following examples!

- a map, for example, could have area + points + pop-ups, multiple layers, or a scrolling story map - you could use your Leaflet skills or try [Mapbox](https://docs.mapbox.com/mapbox-gl-js/example/)
- for example: [Mapping Stop and Frisk, NYC](https://www.nytimes.com/interactive/2014/09/19/nyregion/stop-and-frisk-map.html), NYT
- for example: [AAPI Census Data](https://ucla-center-for-neighborhood-knowledge.github.io/hub-census-map/), Movement Hub
- for example: [Shipmap!](https://www.shipmap.org/)
- for example: [A Map of Citi Bike](https://projects.newyorker.com/story/citi-bike.html), New Yorker
- for example: [2020 Election Results Map](https://www.nytimes.com/interactive/2021/upshot/2020-election-map.html), NYT
- for example: [Unlock NYC](https://weunlock.nyc/data/soi-map/) - choropleth + points combination, housing discrimination data (MAB project)
- for example: [Networks Beyond Borders](https://migration.nyudri.org/map/) - your map could tell a story, fly between locations! (MAB project)

maybe you make a complex hand-drawn based map, (I am open to this! - with online documentation)
- for example: "[Bats and the Origins of Outbreaks](https://www.reuters.com/graphics/HEALTH-CORONAVIRUS/BATS/qzjpqglbxpx/)"
- for example: "[Dear Data](http://www.dear-data.com/theproject)"

## 🔎 evaluation criteria

Your work will be evaluated based on your analysis process, final visualizations, and your report. In general I am looking for:
  - Relevant data transformation in pandas or other methods, documented
  - Breadth and depth of exploratory analysis, documented
  - Clear explanation of your process in your methodology, and your choices in your report
  - Expressive and effective visualizations, solid design choices based on what we've learned (color, shape, interactivity, information density/placement, etc.)
  - Complexity: final visualizations should both tackle complexity, and present complex information in an inviting way ("rewards study", Tufte)
  - Final visualizations are polished, presented cleanly for the user, clearly labelled and documented, and they can "stand alone" and tell a story

Grading:
  - Proposal complete & on-time (5%)
  - In-class Presentation (15%)
  - Documentation (30%)
  - Final Visualization(s) (50%)

## 📄 writings: methodology and report

For the methodology section:
- Edit the default `README.md` (md=Markdown) file in the final Glitch project to create a "Methodology" portion of your project
- Markdown is a language like HTML - you can pick up some pointers [here!](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- Write, in paragraph form, an overview of your domain and dataset; some background on what you know about the origin of the data; any data transformation/processing that your group did on the dataset; and an introduction to your audience on how to "read" and "use" the visualization.
- You can check out the [Ukko wind map](https://project-ukko.net/more-info.html) or the [Unlock NYC](https://weunlock.nyc/data/soi-map/) "About this Map" sections as examples. Yours does not need to be as extensive, but these examples should provide direction. Think of this as front-end, public-facing key information - what do you want your users to know? What do you need them to know about your process? 

## ✉️ submit your work
  - deadlines:
      - team list: Nov. 13th (Discord)
      - code delivered: Dec. 1st - one submission per team!
      - presentation: in-class, Dec. 4th
  
## Please use [this form](https://airtable.com/app6HibgdChLzfvNP/shrmci4vEu7NvudHl) to submit your code work **by Dec. 1st, 11:59pm.**

