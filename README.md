# Data Journalism
Interactive scatterplot that shows a D3 visualization on the health risks facing particular demographics across different states in the U.S 


### Background

![background](https://media.giphy.com/media/v2xIous7mnEYg/giphy.gif)

Welcome to the newsroom! You've just accepted a data visualization position for a major metro paper. You're tasked with analyzing the current trends shaping people's lives, as well as creating charts, graphs and interactives to help readers understand your findings.

The editor wants to run a series of feature stories about the health risks facing particular demographics. She's counting on you to sniff out the first story idea by sifting through the latest information from the U.S. Census Bureau and the Behavioral Risk Factor Surveillance System.

The beat reporters will go out and investigate the relationship you find, sourcing experts and finding anecdotes to back up your research. That's tough work, and they won't be happy about digging for a story that doesn't exist—you'll need to find a convincing correlation before you even think about pitching your first article. The editor also wants you to make a scatter plot to show the correlation—you are the data visualizer, after all.

### Data
- U.S. Census Bureau and the Behavioral Risk Factor Surveillance System.
- The [data set](https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml) included with the assignment is based on 2014 ACS 1-year estimates. The current data set incldes data on rates of income, obesity, age, household income, poverty etc. by state. MOE stands for "margin of error."

### Visualization of the Data

The visualization is intended to show various health risks facing particular demographics across different states in the U.S. (for example, access to healthcare vs median household income). To compare different factors or data variables, you can click on the x and/or y labels to change the view of the visualization. I created a scatter plot that represents each state with circle elements. My scatter plot appeared like the image seen here

<img src="Images/7-animated-scatter.gif">


Each circle on the visualization represents a different state in the U.S. To see the actual values for a particular state, you can hover over the circle for that state to see a tooltip, which contains the actual data values based on the currently selected x and y axis labels. The tooltip was created using d3-tip, a plugin developed by [Justin Palmer](https://github.com/Caged).

The dataset used for this project is based on 2014 ACS 1-year estimates. It includes data on rates of income, obesity, poverty, etc. by state. The information comes from the U.S. Census Bureau and the Behavioral Risk Factor Surveillance System.

This repository includes a scatter plot visualization, which was deployed [here](https://sahobitayo.github.io/D3-challenge/D3_data_journalism/). The D3 code is available here inside this repository.


