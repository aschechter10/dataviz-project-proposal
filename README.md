# Olympic Swimming Data Visualization Project

This project explores Olympic swimming data spanning over a century (1912–2020), using visualizations to uncover insights about medal distributions, event performances, and country-level dominance. The dataset, sourced from [Kaggle](https://www.kaggle.com/datasets/datasciencedonut/olympic-swimming-1912-to-2020), provided a rich foundation for analysis and storytelling.

The visualization culminates in an interactive bar chart that displays the total gold medals won by each country across Olympic swimming events. This includes a toggle to filter by stroke type and hover interactions revealing the fastest swim times for men and women.

## Objectives

The project was guided by the following questions:

 * Which country is the best at each event?
 * What was the fastest time recorded for each event?
 * Are there patterns in which countries excel in specific events?

## Methodology

The visualization was implemented in stages, iteratively refining both functionality and design. The key features of the final product are described below.

### Data Cleaning

Initial analysis revealed some missing data, which required filtering out incomplete records. Cleaning the data ensured accurate medal counts and no incomplete data. 

### Visualization Design

The primary visualization is a bar chart where:
* X-axis: Country names as a 3 letter abbrevation e.g. USA for United States of America
* Y-axis: Displays the total gold medals won by each country across all Olympics (combined men’s and women’s medals)
* Toggle Control: Enables switching between stroke types and distances. Covers all Olympic events
* Bar Hover Interaction: reveals details about the fastest man and woman for that event: their names, times, and the year and location of the Olympics where they competed.

This was the first sketch of the project:

![image](./dataviz.jpg)

## Development Timeline

* The first iteration focused on a basic bar chart displaying medal counts per event only for 1 event.
[Version 1 (10/31/24)](https://vizhub.com/aschechter10/olympic-swimming-project-version-1)

* Version 2 added a toggle for switching between events, and improved layout and added consistent color-coding for countries.
[Version 2 (11/8/24)](https://vizhub.com/aschechter10/olympic-swimming-project-2)

* Version 3 added a hover interaction but with no tooltips (just highlighting the bar). There were some bugs with switching events and hovering at this stage but the UI was looking closer to done.
[Version 3 (11/15/24)](https://vizhub.com/aschechter10/olympic-swimming-project-3)

* With version 4 functionality was pretty much done. Hovering over bars works, bars are well color-coded. There is one last bug with some of the bars not having the fastest time on hover.
[Version 4 (11/22/24)](https://vizhub.com/aschechter10/olympic-swimming-project-4)

* Final Version: In progress

## Conclusion

In progress
