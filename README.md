# Data Visualization Project

## Data

The data I propose to visualize for my project is [Olympic Swimming Dataset](https://www.kaggle.com/datasets/datasciencedonut/olympic-swimming-1912-to-2020)


## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * Which country is the best at each event?
 * What was the fastest time of each event?
 * Are there any patterns in which countries win which event?
 * How many complete records are there? How many will need to be discarded because of missing data?

## Sketches

![image](./dataviz.jpg)

- The data will be visualized in the form of a bar chart
- The X axis will have the event distances (50m, 100m, 200m, ...)
- The Y axis will have the total number of gold medals won by a country in that event across all valid Olympics (men's and women's medals combined)
- The top right of the bar chart will have a toggle to switch which stroke you are looking at (in the sketch, it says Freestyle. This will have all the strokes as options as laid out in the right side of the sketch)
- Hovering on the bar charts will hopefully show the fastest times for men and women respectively in that specific event (so for 50m freestyle, it would show the fastest man to ever swim 50m freestyle at any Olympics and the fastest woman. It will show their name, final time, and which olympics it was swam at)


## Prototypes

So far, I do not have a working prototype for this dataset. I am currently working on establishing a bar chart that can pull from the data in some capacity. Not necessarily the aggregation I mentioned earlier, but just getting a working bar chart with this dataset.

## Open Questions

I'm not sure how realistic the toggle between events button will be. I'm hoping I can implement it as I feel as though it's crucial to encapsulating the dataset in the visualization well. 

## Milestones

ASAP: working prototype
2-3 weeks: Working bar chart for 1 stroke (all events showing properly on x-axis and accurate medal counts)
4-6 weeks: Ability to either hover as mentioned, or toggle strokes as mentioned
By the end: Have both hover and stroke selection working
