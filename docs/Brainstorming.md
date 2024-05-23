# Side Order analysis project brainstorming

## Introduction

This document goes over the initial foundation of the project, it describes what visuals and analysis are going to be included for this project.
I will mainly go over what features and formula's are innovating as well as intresting to make an analysis on.


## Brainstorming

**what is going to be analysed for this project?**

- **1.**  include each source of data files related to the subject
- **2.** colorchips mainly go into effect when giving customization towards damage types. If possible make visuals for each category in this case with optimal colorchip filters.
- **3.** each category should have its own description and explanation of what it is.

- **4.** give detailed info for each floors scalability in rewards and drop rate.
- **5.** enemies also have data that can be manipulated to show the most optimal way to farm for resources.
- **6.** the colorpallete stores 30 colorchips inside, wich could be referenced by using a variable, and may include numpy arrays for each colorchip.
- **7.** rewards are visable.
- **8.** Marina's hack are permanent, however they can always be disabled if necessary for the analysis.
- **9.** **(Optional)** Include the first chamber of 10 floors that serve as the tutorial stage for the game.

<br />

## How can this be implemented?

**how will visuals be aqcuanted?**
- main, sub and special weapon types need horizantal bar graphs to better dictate there overall damage output. On the subject, also make filter options when including colorchips have seperate bar graphs that go perpanicular to the main graph.
- when scaling enemy danger levels, they can be put in percentages and be predicted in pie charts.
- For the floors, they will be visualized in line charts to better understand the layout structure that goes in later. It might be better to use subplots when visualizing them.
- The colorpallete can be visualized in a 3D scatter plot, with each colorchip being a point in the plot.
- Rewards can be visualized in a bar graph, with the x-axis being the floors and the y-axis being the rewards.
- Marina's hack can be visualized in a pie chart, with the x-axis being the hacks and the y-axis being the percentage of the hacks.

**how will interaction work?**
- when it comes to the filter options, they can mainly consist of dropdowns or button selectors.
- when it comes to the line charts, they can be interactive by hovering over the points to get more information.
- when it comes to the pie charts, they can be interactive by clicking on the slices to get more information.

**Furder adjustments**
- to give better intrepetations of what certained data is meant to represent, giving general descriptions of what each data point is meant to represent.
